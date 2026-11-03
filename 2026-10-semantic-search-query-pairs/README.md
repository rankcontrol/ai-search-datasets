# Semantic search query pairs (October 2026)

We searched Google from the US for 14 pairs of queries that mean the same thing but use different words, on October 19, 2026. For most pairs, one phrasing has noticeably higher Google Ads search volume than the other. We read the titles of the top 10 results for both sides of every pair. The same day, we sent all 29 queries to ChatGPT through a data provider's feed and checked Google's AI Overviews for the pairs, and separately ran three free, open embedding models locally against a small set of same-meaning sentences to see how the matching works underneath.

- **Write-up:** [We Searched 14 Same-Meaning Query Pairs to See How Semantic Search Works](https://medium.com/@thesearchshift/we-searched-14-same-meaning-query-pairs-to-see-how-semantic-search-works-f89d06d90763)
- **Source guide:** [RankControl's semantic search guide](https://rctrl.com/blog/semantic-search)

## Files

| File | What it holds |
|---|---|
| `query-pairs.csv` | 8 of the 14 same-meaning query pairs tested, each phrasing's Google Ads monthly search volume, and how many of the rarer phrasing's top 10 results were titled using only the common phrasing's words |
| `embedding-test.csv` | How 3 open embedding models (bge-small, bge-large, mxbai-large) ranked the correct, differently-worded answer against word-overlap decoys, for 3 queries |
| `ai-answers.csv` | Aggregate numbers for how ChatGPT and Google's AI Overviews handled the same 29 queries |

## Results

Across the 11 pairs (of the 14) where one phrasing was clearly rarer by search volume, 56 of the 83 top results for the rare side, about two in three, were titled using only the common phrasing's words. It never ran the other way: checking the common phrasings, 0 of 90 results were titled using only the rarer words.

The two sides of a pair, despite matching in meaning, mostly didn't share pages. Across all 14 pairs, the top-10 lists shared just 7 URLs out of 207 distinct pages looked at, about 3% overlap, never more than one shared URL per pair. One pair had no title swap at all: "car makes noise when braking" vs "squeaky brakes" kept 0 of 8 titles swapped, because the rarer phrasing already had its own standing content.

The small embedding model (bge-small) picked a word-overlap decoy over the correct, differently-worded answer in all 3 test queries. The two larger models (bge-large, mxbai-large) ranked the correct answer first in 2 of 3 queries each, with margins as thin as 0.004, and 0.730 vs 0.715 on the one query where both scores are recorded.

ChatGPT searched the web for 9 of the 29 queries and rewrote rare phrasings into common ones when it did ("inexpensive airfare to london" went out as "cheap flights to London"); for the other 20 it answered from memory and hedged by naming both words. Google's AI Overviews appeared for 27 of 28 pair searches and shared about 15% of sources (27 of 179) across the 13 pairs where both sides had one.

## How we counted

The "titled only in the common words" column counts top results whose titles use only the common phrasing's words, the same measure as the source guide's table. 11 of the 14 pairs had one phrasing that was clearly rarer by search volume, so the 56-of-83 tally covers those 11. The URL-overlap figure (7 of 207) covers all 14 pairs.

## Limits

One day (October 19, 2026), one US location, so this is a snapshot rather than a trend. Google Ads search volume is an estimate of search frequency, not a direct count, and some phrasings showed no recorded volume at that level ("no data" in `query-pairs.csv`). The embedding test used 3 queries and 5 candidate sentences each, enough to show the failure pattern, not enough to rank the three models against each other with statistical confidence. Nothing here was repeated across days or locations, and only the pair- and query-level tallies are included, not a full row-level list of all 207 URLs or the AI Overview source lists.

## Related

- Full write-up: [Search Shift on Medium](https://medium.com/@thesearchshift/we-searched-14-same-meaning-query-pairs-to-see-how-semantic-search-works-f89d06d90763)
- Source guide: [rctrl.com/blog/semantic-search](https://rctrl.com/blog/semantic-search)
- Track which pages AI engines cite for your own queries: [RankControl's AI visibility tracker](https://rctrl.com/ai-visibility)

Data by [RankControl](https://rctrl.com), an AI SEO and AEO platform, released under CC BY 4.0.

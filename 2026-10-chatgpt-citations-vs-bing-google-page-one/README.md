# ChatGPT citations vs Bing and Google page one (October 2026)

In September 2026 someone asked r/SEO whether ChatGPT uses Google's index or Bing's, and the replies disagreed. On October 19, 2026 we took 38 keywords across software, shopping, how-to and brand searches and searched each on Bing and on Google from the same browser, set to US English. Then we ran the same keywords through ChatGPT's web app, using a data provider's live feed, and recorded every site it cited.

- **Write-up:** [Bing Rank Tracking for ChatGPT: 25% of Cited Sites Were on Bing's Page One](https://medium.com/@thesearchshift/bing-rank-tracking-for-chatgpt-25-of-cited-sites-were-on-bings-page-one-0c3e8958f374)

## Files

| File | What it holds |
|---|---|
| `overlap.csv` | How many keywords ChatGPT searched for, how many sites it cited, and the share of those sites on Bing's and Google's first page |
| `by-search-type.csv` | The same overlap split by brand, shopping and software searches |
| `rewrite-gap.csv` | What happened when we ran ChatGPT's rewritten searches on Bing, and the size of ChatGPT's candidate pool |

## Results

ChatGPT searched the web for 26 of the 38 keywords and answered the other 12 from memory, mostly how-to and what-is questions. For the 26 it searched, it cited 147 different sites. We checked whether each cited site sat on page one of Bing or Google for that keyword.

| Where the cited site ranked | Share of 147 sites |
|---|---:|
| Bing's first page | 25% |
| Google's first page | 24.5% |
| Both first pages | 10% |
| Neither first page | 60.5% |

ChatGPT cited the site in Bing's first spot for 7 of the 26 keywords and the site in Google's first spot for 11.

Brand searches lined up best. Software searches lined up worst, and Google's first page explained slightly more of ChatGPT's picks than Bing's did.

| Search type | Keywords searched | On Bing's first page | On Google's first page |
|---|---:|---:|---:|
| Brand, like "asana vs monday" | 8 | 37% | 33% |
| Shopping, like "best air fryer" | 8 | 28% | 24% |
| Software, like "help desk software" | 9 | 17% | 20% |

## The rewrite gap

ChatGPT rewrites a keyword before it searches. For "best crm for small business" it searched "best CRM software for small businesses 2026 pricing features comparisons," and of the nine sites it cited, one was on Bing's first page. We ran ChatGPT's rewritten searches on Bing for 14 of the keywords. Bing's page one for the keyword and for its rewrite shared 23% of sites. ChatGPT's cited sites on Bing's page one were 19% for the rewrite and 24% for the original keyword, so tracking the rewrite did not explain the citations any better.

Across the 26 searched keywords, the pool of sites ChatGPT's search returned held 220 sites. 18.6% of that pool was on Bing's first page for the keyword, against 10% on Google's.

## Limits

This is one run of 38 keywords on one day, through a data provider rather than a logged-in browser, so read the shares as a pattern and not a stable rate. We compared sites, not exact pages, so a Forbes article on page one counted as a match for a different Forbes article that ChatGPT cited. Only the tallies are here, not the keyword-level rows.

## Related

- Track which sites AI engines cite for your own questions: [rctrl.com/ai-visibility](https://rctrl.com/ai-visibility)
- Free Bing positions: [Bing Webmaster Tools](https://www.bing.com/webmasters)

Data by [RankControl](https://rctrl.com), an AI SEO and AEO platform, released under CC BY 4.0.

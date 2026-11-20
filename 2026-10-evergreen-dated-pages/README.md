# How old the pages that rank and get cited are (October 2026)

On October 19, 2026 we took every page in Google's top 10 for 40 common business queries, ranging from how to write an invoice to how to hire your first employee. For each list we added the pages referenced by Google's AI Overviews (AI-generated answer box above search results) and the pages cited by ChatGPT. This led to a total of 635 pages (of which 135 were YouTube videos). Finally we extracted the published date as declared by the page in its own code and managed to get a date for 260 non-video pages.

- **Write-up:** [We Dated 260 Pages That Rank and Get Cited. Here's What Evergreen Means.](https://medium.com/@thesearchshift/we-dated-260-pages-that-rank-and-get-cited-heres-what-evergreen-means-c0c31aef4e32)

## Files

| File | What it holds |
|---|---|
| `run-totals.csv` | The test setup and the totals: pages collected, dated pages, median age, and the counts for AI Overviews, ChatGPT and YouTube |
| `old-pages-tended-vs-timeless.csv` | The 85 pages that were 3 or more years old, split into updated and not updated, with the examples we named |
| `median-age-by-question.csv` | Median age of the dated pages for 4 of the questions |

## Results

| Measure | Result |
|---|---:|
| Non-video pages with a usable publish date | 260 |
| Median age of those pages | 2.0 years |
| Pages 3 or more years old | 85 (about a third) |
| Of the 85, updated within the last 12 months | 42 |
| Of the 85, not updated for years | 24 |

Half the pages were younger than 2.0 years and half were older.

The oldest page in Google's top 10 was first published in May 2005, according to its code: a small business site's guide to writing a business proposal. The date it shows readers is its last update, July 20, 2026.

We split these 85 old pages into two groups. Tended old pages get new facts: 42 of the 85 were updated in the last 12 months, for example SurveyMonkey's Net Promoter Score guide (2019, last update date: September, 2026) or Pipedrive's sales pipeline guide (January 2020, last update date: September, 2026).

Timeless pages keep winning without updates: 24 of the 85 haven't been updated for years, for example Harvard Business Review's cold email guide (September 2016, with no update date) or GoCardless's cash flow forecasting article (published and updated April 2020).

Dates change. On October 19 there was no update date on Pragmatic Institute's 2015 article about SaaS pricing (Subscription Software). On November 11 when we checked the code again the article's date was updated to November 2, 2026. The four other example pages kept their dates.

| Question | Median age of dated pages (Google top 10 and AI Overview sources) |
|---|---:|
| How to calculate net promoter score | 7.0 years |
| Brand style guide | 5.2 years |
| Planning the launch of a product | 0.6 years |
| Writing an invoice | 0.4 years |

For AI Overviews there was a total of 137 pages that had dates, 38 of those pages were 3 or more years old, including a Guardian article from 2015 about writing press releases and an article from Nielsen Norman Group from 2016 about Customer Journey Maps.

For ChatGPT, 11 pages had dates in the code and none were older than 3 years. The oldest was Stripe's guide to SaaS pricing from December 2023 (small sample of 11 pages, however).

Out of 135 YouTube videos, 38 were 3 or more years old.

For context, the write-up cites an Ahrefs analysis of 16.975 million cited URLs, published July 28, 2025: ChatGPT-cited URLs were 458 days fresher on average than Google's organic results, and pages in Google's AI Overviews were 16 days older.

## Limits

40 business questions, all from the US, all on one day, so treat the counts as a snapshot and not a rate. Each page's age is the date declared in its own code, and some sites change that date without changing much else. Pages with no declared date (nearly a third of the pages we could retrieve, per the write-up) are left out, and YouTube videos are not in the 260. The ChatGPT figures rest on 11 dated pages. Tended and timeless are our own labels. Only the tallies are here, not the row-level list.

## Related

- Track which of your pages AI engines cite: [rctrl.com/ai-visibility](https://rctrl.com/ai-visibility)
- Google's own guidance on dates: [Add a byline date to Google Search results](https://developers.google.com/search/docs/appearance/publication-dates)

Data by [RankControl](https://rctrl.com), an AI SEO and AEO platform, released under CC BY 4.0.

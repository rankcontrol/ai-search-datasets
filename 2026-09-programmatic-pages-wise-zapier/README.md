# Programmatic pages vs AI answers: Wise and Zapier (September 2026)

On September 26, 2026 we put 8 questions to the APIs behind ChatGPT and Perplexity and to Google's AI Overviews (the AI-written answer above the results), and wrote down which pages each one cited, meaning linked as a source. The questions were aimed at pages Wise and Zapier have built at scale, a method called programmatic SEO: one page template repeated with the names or numbers swapped, like Wise's page per currency pair or Zapier's "connect app A to app B" page. Three questions went at Wise's pages and five at Zapier's.

- **Write-up:** [We Tested Programmatic SEO vs AEO: Wise Won, Zapier Mostly Lost](https://medium.com/@thesearchshift/we-tested-programmatic-seo-vs-aeo-wise-won-zapier-mostly-lost-e4617010e6c9)

## Files

| File | What it holds |
|---|---|
| `wise-pages.csv` | Results for the 3 Wise questions |
| `zapier-pages.csv` | Results for the 5 Zapier questions |

## Results

| Zapier search | Engines run | Engines citing Zapier's page for it |
|---|---:|---:|
| Slack and Google Sheets | 3 | 1 |
| HubSpot and Airtable | 3 | 1 |
| Zapier vs Make | 3 | 2 |

Wise's pages got cited almost every time we asked. All 3 engines cited its India transfer page for sending money from the US to India. For "usd to eur exchange rate today," Wise was Google's top organic result and Perplexity linked its converter. And when we asked whether Wise is cheaper than a bank for international transfers, Google's AI Overview cited 4 Wise pages in one answer while Perplexity cited more than a dozen.

Zapier's integration pages did not do that. Across the two "connect app A to app B" searches the engines cited Zapier's page 2 times in 6 chances. The other four answers pointed elsewhere: Slack's help docs, a thread on Zapier's own community forum, Airtable's help docs, and, from Perplexity on HubSpot and Airtable, HubSpot marketplace listings and 5 competitors' integration pages. In what we saw, the answer to "how do I connect these two apps" mostly sat in the other app's own documentation.

Zapier did better where a page compared things. On Zapier vs Make, ChatGPT cited the pricing pages of Zapier and Make plus a review site, and Perplexity and the AI Overview cited Zapier's comparison page. The two broader questions went differently: on "how to automate workflows between apps without code" Zapier ranked second on Google, yet the AI Overview linked someone else's article about Zapier, and on "best integration platform for a small ops team" it named Zapier but linked only third-party pages.

## Limits

8 questions on one day, with 3 aimed at Wise and 5 at Zapier, so treat the counts as a snapshot and not a rate. We ran ChatGPT and Perplexity through their APIs, not their apps. Only the tallies are here, not the row-level list.

## Related

- Track which pages AI engines cite for your own questions: [rctrl.com/ai-visibility](https://rctrl.com/ai-visibility)
- Google's own rules: [Spam policies for Google web search](https://developers.google.com/search/docs/essentials/spam-policies)

Data by [RankControl](https://rctrl.com), an AI SEO and AEO platform, released under CC BY 4.0.

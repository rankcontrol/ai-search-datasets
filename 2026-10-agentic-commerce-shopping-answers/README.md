# Where ChatGPT and Google AI Mode sent shoppers on 16 questions (October 2026)

Agentic commerce is shopping with an AI shopping assistant who does some of the work for you, finding products, comparing them, and telling you where to buy. On October 19, 2026 we asked ChatGPT and Google AI Mode 16 questions from the US (once each), common shopping tasks like "best running shoes for flat feet under $150", "buy a 6 person camping tent", and "where can I buy a cast iron skillet".

We counted where each answer was directing shoppers to go. A product card is a clickable product tile embedded in a ChatGPT answer. A citation is a source that the answer links to.

- **Write-up:** [What Is Agentic Commerce? We Ran 16 Shopping Questions to Find Out](https://medium.com/@thesearchshift/what-is-agentic-commerce-we-ran-16-shopping-questions-to-find-out-c996bce45779)

## Files

| File | What it holds |
|---|---|
| `run-totals.csv` | The test setup and the totals for both engines |
| `chatgpt-cards-by-store-type.csv` | ChatGPT's 27 product cards by type of store |
| `chatgpt-store-counts.csv` | How often ChatGPT cited Walmart, Home Depot and Best Buy, and Amazon's single card |
| `ai-mode-sources.csv` | Google AI Mode's product links and the review site it linked most |
| `reddit-and-search-figures.csv` | The store-owner figures from two Reddit threads and the monthly search estimates the write-up quotes |

## Results

| | ChatGPT | Google AI Mode |
|---|---|---|
| Answers with product listings | Product cards in 11 of 16 | Product links in 12 of 16 |
| Where product links pointed | 27 cards to 16 different stores, plus a few media pages | 71 links to Google's own Shopping listings |
| Most cited source | Walmart, 13 citations | The New York Times' Wirecutter, 15 links |

| Store type behind ChatGPT's 27 cards | Cards |
|---|---:|
| Big retailers like Walmart, Best Buy, Dick's and REI | 14 |
| A brand's own store, like Brooks or Woom | 7 |
| A specialty shop | 1 |
| Media sites or no link | 5 |

ChatGPT had 27 product cards across 11 responses and 23 had a price. It cited Walmart the most: 13 times across the 16 responses. Then Home Depot: 7. And Best Buy: 7. It provided 1 product card (across the entire test) for Amazon. Amazon's robots.txt file, which we looked at on the same day, blocks OpenAI's search crawler and the ChatGPT-User agent. (robots.txt files are like a sign to automated programs that says 'here's the pages you can read') 7 of the 27 cards went to a maker's website directly (e.g., Brooks for running shoes and Woom for a kids bike).

Google AI Mode treated products differently. In 12/16 answers it tied product names to Google's Shopping listings (71 links), not to a store. Those listings come from Merchant Center feeds. Those are files with a list of products from a store with prices and stock levels. It used reviewers to explain the reason for its choices. 15 links to Wirecutter. RTINGS and OutdoorGearLab were next.

For context, the write-up quotes two Reddit threads:

- 2.5% of store sales for the last 30 days were attributed to Shopify's agentic channel, says a store in r/shopify on Oct 3rd 2026, and another commenter says that a few of their dozen clients received less than 1% of their Shopify revenue from channels such as ChatGPT and Shopify's Shop app.

- An industrial manufacturer says in r/ecommercemarketing on Sept 28th 2026 that they had roughly 150 visitors in September that came from ChatGPT (GA4 verified), and had just taken a single order over $9,000.

A data provider estimated around 5,400 US searches per month for "agentic commerce" and around 1,600 for "what is agentic commerce" for October 2026.

## Limits

We ran 16 questions once each, from the US, on one day. Shopping responses vary with inventory, price and the shopper's location. We didn't look at what shoppers were buying, just the direction of the links. Reddit numbers are self-reported by store owners. Search numbers are a data provider's estimates. Just the tallies here, no row-level list.

## Related

- Track which stores and pages AI engines cite for your own buyer questions: [rctrl.com/ai-visibility](https://rctrl.com/ai-visibility)

Data by [RankControl](https://rctrl.com), an AI SEO and AEO platform, released under CC BY 4.0.

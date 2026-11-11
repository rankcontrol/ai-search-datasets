# ChatGPT's top pick across repeated runs (October 2026)

On October 19, 2026 we asked ChatGPT 5 buyer questions, such as "best mattress for side sleepers" and "best crm for small business," three times each. That gave 15 answers, and for each we recorded the products ChatGPT named, which one came first and how many sources it cited. The same day we split 15 brand names into tokens, the chunks of text a model reads in place of words, with o200k_base, the tokenizer GPT-4o uses.

- **Write-up:** [Large Language Model Test: ChatGPT's Top Pick Changed on 2 of 5 Questions](https://medium.com/@thesearchshift/large-language-model-test-chatgpts-top-pick-changed-on-2-of-5-questions-ce9fea6e36be)

## Files

| File | What it holds |
|---|---|
| `top-pick-by-question.csv` | Products named and top pick for each question |
| `run-totals.csv` | Totals across the 15 answers and 15 brand names |
| `brand-name-tokens.csv` | How o200k_base split 6 brand names |

## Results

| Question | Products named | In all 3 runs | Top pick |
|---|---:|---:|---|
| best crm for small business | 6 | 4 | HubSpot CRM every run |
| best accounting software for freelancers | 5 | 5 | Wave, QuickBooks, Wave |
| best mattress for side sleepers | 7 | 3 | Casper once, Helix twice |
| best project management tool for small teams | 5 | 5 | ClickUp every run |
| best email marketing platform for ecommerce | 5 | 5 | Klaviyo every run |

The top pick changed on 2 of the 5 questions, accounting software and mattresses. Across the 15 answers, 22 of the 28 products ChatGPT named appeared in all three runs. The other 6 came from two lists: 2 from the CRM answers, where Salesforce's starter plan dropped out after one run and Less Annoying CRM took its place, and 4 from the mattress answers. ChatGPT cited a median of 9 sources per answer and ran a single search in 13 of the 15.

All 15 brand names came out as 2 or 3 tokens. ClickUp, Lemonade and Mailchimp split in two, as Click and Up, Lemon and ade, and Mail and chimp. Pipedrive, Ruggable and Policygenius split in three. Common words such as plumber stayed whole, and so did Kubernetes, a widely written-about name.

## Limits

5 questions, 3 runs each, on one day, so the counts are a snapshot and not a rate. The mattress list swapped brands most, with 4 of its 7 products missing from at least one run. Only the 6 brand names the write-up spells out are in `brand-name-tokens.csv`. Only the tallies are here, not the row-level list.

## Related

- Track which brand ChatGPT puts first in your category: [rctrl.com/ai-visibility](https://rctrl.com/ai-visibility)
- The tokenizer we used: [OpenAI's tiktoken cookbook](https://github.com/openai/openai-cookbook/blob/main/examples/How_to_count_tokens_with_tiktoken.ipynb)

Data by [RankControl](https://rctrl.com), an AI SEO and AEO platform, released under CC BY 4.0.

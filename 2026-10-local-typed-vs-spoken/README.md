# Typed vs spoken local searches in Google and ChatGPT (October 2026)

On October 19, 2026 we ran 15 local searches across 15 US cities through Google twice: once typed the short way ("plumber austin") and once spoken as a full question ("who's a good plumber in austin that can come today"). For each version we recorded whether Google showed a map pack (the box of three nearby businesses), an AI Overview (the AI-written answer above the results) or forum results such as Reddit threads. We also asked ChatGPT the 15 spoken versions and logged which businesses and links it gave.

- **Write-up:** [How Local Businesses Get Mentioned in ChatGPT and Perplexity (We Tested It)](https://medium.com/@thesearchshift/how-local-businesses-get-mentioned-in-chatgpt-and-perplexity-we-tested-it-e020f2f792ce)

## Files

| File | What it holds |
|---|---|
| `google-typed-vs-spoken.csv` | Google's results for the typed and spoken searches |
| `spoken-question-kinds.csv` | Find and know questions in the spoken set |
| `chatgpt-spoken-answers.csv` | What ChatGPT named and linked in its 15 answers |

## Results

| What Google showed | Typed (of 15) | Spoken (of 15) |
|---|---:|---:|
| Map pack | 15 | 9 |
| AI Overview | 3 | 9 |
| Forum results | 2 | 8 |

Asking the search as a question pulled Google away from its own map pack: 15 of 15 typed searches showed one, against 9 of 15 spoken ones, while forum results went from 2 to 8. The spoken searches included 5 "find" questions, such as an emergency vet open right now in Seattle, and every one got a map pack and no AI Overview. It also had 6 "know" questions, such as what an AC repair costs in Atlanta, which got an AI Overview instead, with a map pack beside it only once. Most pages those overviews cited were local businesses' own sites, like a roofing company and an electrician, and they outnumbered Angi, Yelp and Home Depot.

ChatGPT named 3 or 4 businesses for each find question and none for the 5 how-much and how-to questions. Only 11 of the 35 businesses it named also appeared in one of Google's map packs for the same need. It linked a Google Maps listing in 5 of its 15 answers and a local business's own website in 9.

## Limits

15 searches, one per city, all on October 19, 2026, so the counts are a pattern and not a rate. ChatGPT saw only the spoken versions, and it reported its own model as GPT-6. The write-up gives 6 know questions for Google and 5 how-much and how-to questions for ChatGPT, and we kept both figures as published. Only the tallies are here, not the row-level list.

## Related

- Track what AI engines say about your business: [rctrl.com/ai-visibility](https://rctrl.com/ai-visibility)
- Google's own tips: [Improve your local ranking on Google](https://support.google.com/business/answer/7091)

Data by [RankControl](https://rctrl.com), an AI SEO and AEO platform, released under CC BY 4.0.

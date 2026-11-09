# Local listings in Google AI Mode vs ChatGPT (October 2026)

On October 19, 2026 we asked Google AI Mode and ChatGPT 12 local questions, one in each of 12 US cities, such as "best plumber in Austin TX," "dog groomer in Seattle" and "bakery in Boston." Each question ran once. We then looked at where each engine got the details it showed for a business: name, address, phone number, rating, review count and photos. The data came from each engine's US results through a data provider.

- **Write-up:** [Google Business Profile Setup: Only 3 of 13 ChatGPT Ratings Matched Google](https://medium.com/@thesearchshift/google-business-profile-setup-only-3-of-13-chatgpt-ratings-matched-google-3a8ee3ec1d1b)

## Files

| File | What it holds |
|---|---|
| `local-answers.csv` | Per engine: questions asked, answers that showed business cards, and the total cards |
| `ratings-match.csv` | How often ChatGPT's rating and review count matched Google's, plus the Yelp and tagged-link counts |

## Results

| Engine | Answers with business cards (of 12) | Cards in total |
|---|---:|---:|
| Google AI Mode | 10 | 47 |
| ChatGPT | 9 | 43 |

Google AI Mode's cards showed the Google Business Profile almost word for word: uploaded photos, Google's rating and review count, whether the place was open, and the call, directions and website buttons. ChatGPT's cards carried a name, category, address, phone number, rating and review count. Six of the 43 website links in ChatGPT's cards had tracking tags like "utm_source=gmb," which businesses usually add only to the website field of their Google profile. So some of ChatGPT's data traces back to Google profiles, directly or through a data supplier.

The ratings were another matter. 13 businesses showed up in both engines, and ChatGPT's rating and review count matched Google's for 3 of them. ChatGPT cited Yelp in 4 of its 12 answers. One example: Pequod's Pizza in Chicago showed 3.9 stars from about 9,000 reviews in ChatGPT and 4.4 stars from about 17,000 reviews in Google AI Mode.

## How we matched

We matched businesses by name, so a few may have been missed where the two engines spelled one differently.

## Limits

12 questions, run once each, on one day. Treat the counts as a snapshot, not a rate. Only the tallies are here, not the per-business rows.

## Related

- Track what AI engines say about your business: [rctrl.com/ai-visibility](https://rctrl.com/ai-visibility)
- Google's own tips: [Improve your local ranking on Google](https://support.google.com/business/answer/7091)

Data by [RankControl](https://rctrl.com), an AI SEO and AEO platform, released under CC BY 4.0.

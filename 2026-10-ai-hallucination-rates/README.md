# AI hallucination rates (October 2026)

Two public leaderboards measure hallucination, and they measure different jobs. We read both as of October 2026 and ran a small test of our own on October 19, 2026: ChatGPT and Google AI Mode answered 86 questions about company facts, SaaS prices and software brands that don't exist.

- **Write-up:** [AI Hallucination Rate in 2026: OpenAI Has Models at 3.1% and 23.3%](https://medium.com/@thesearchshift/ai-hallucination-rate-in-2026-openai-has-models-at-3-1-and-23-3-0225244ae9a1)

## Files

| File | What it holds |
|---|---|
| `boards.csv` | The two leaderboards: what each measures, how many models, and the range |
| `vectara-by-vendor.csv` | The lowest and highest rate each vendor had on Vectara's board |
| `our-test.csv` | Results of our own 86-answer test |

## Results

On Vectara's leaderboard, each model gets a set of documents and is asked for a summary using only the facts given. As of its October 16, 2026 update the board listed 109 models. The best scored 1.8%, nine came in under 5%, and the median was 9.6%. OpenAI had a model at 3.1% (GPT-5.4 nano) and another at 23.3% (o3-pro) on the same board. Vectara judges with its own detection model and also sells a search and answer platform built on this kind of grounding.

Artificial Analysis built AA-Omniscience for the harder case: questions with no document to lean on. Its hallucination rate asks how often a model gives a wrong answer instead of admitting it doesn't know, and in October 2026 it ran from 15% to 77% across 32 models.

Our own test was the odd one out. ChatGPT and Google AI Mode invented nothing across 86 answers. Founding year and headquarters matched Wikipedia for 19 of 20 famous companies, 14 of 14 mid-sized ones and 14 of 18 little-known ones. The cheapest paid plan's headline price matched the vendor's pricing page for 16 of 16 SaaS tools. For 9 software brands we made up, all 18 answers said the product couldn't be found. The five misses were places where Wikipedia and other public sources disagreed, and the slips were in the fine print, such as Capsule CRM's monthly price coming back as $22 from ChatGPT and $21 from Google AI Mode.

## Limits

Our test was one question each, from one US location, on one day, and every question had a single right answer. The two leaderboards change their versions over time, so the figures here are the ones in force in October 2026. Only the tallies are here, not the row-level list.

## Related

- Check what AI engines say about your own brand: [rctrl.com/ai-visibility](https://rctrl.com/ai-visibility)
- Vectara's board: [hallucination-leaderboard](https://github.com/vectara/hallucination-leaderboard)

Data by [RankControl](https://rctrl.com), an AI SEO and AEO platform, released under CC BY 4.0.

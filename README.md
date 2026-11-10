# Growth Audit — Sync.me

**Live:** https://bterzic123.github.io/syncme-flow-rebuild/

Five ideas to turn more Sync.me installs into paying users, plus a clickable prototype of the onboarding and paywall rebuilt in Sync.me's own design. Only the order of the screens changes.

## The five ideas

| # | Idea | Potential outcome |
| :-- | :-- | :-- |
| 1 | Ask the question your ads already ask ("Do you answer it?"), then name the answer on the paywall | CR +15–20% |
| 2 | Ask for an account after the paywall | CR +8% · ARPU +17% |
| 3 | Make the X a real second offer: 7,99 € monthly, no trial, against what stays free | ARPU +10–15% |
| 4 | Put your 350K+ ratings, press row and an App Store review on the paywall | CR +10–15% |
| 5 | Ask for contacts and notifications after the paywall | CR +10–15% |

Potential result when run together: revenue up to +30%.

## Grounding

Impact ranges are Adapty's expected effect from teardowns and A/B tests across subscription apps, not measured lift for Sync.me. Prices, the 2-month trial, plan lines, the 57% vs 89% chart, 350K+ ratings, 30M+ users, the press row and the reviews come from Sync.me's own screens. 4.4 from 22K ratings is from the US App Store listing. Ad frames and copy are from Sync.ME LTD's public Meta ads for Livecaller, read 10 November 2026.

## Run locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000/. Add `?open=proto` to land on the prototype.

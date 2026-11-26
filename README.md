[![news-image-20261126](https://make.fun/badge/news-image-20261126.svg)](https://make.fun/bounty/news-image-20261126)
[![rank](https://make.fun/badge/news-image-20261126/tresiass96/news-image-20261126/rank.svg)](https://make.fun/bounty/news-image-20261126)
[![reward](https://make.fun/badge/news-image-20261126/tresiass96/news-image-20261126/reward.svg)](https://make.fun/bounty/news-image-20261126)

# The World in One Page — 26 November 2026

An entry for the [make.fun news-image-20261126 bounty](https://make.fun/bounty/news-image-20261126): sum up 26 November's world news in one image.

`entry.png` is a 1024×1024 newspaper front page with 21 stories: three heroes across regions (the Houthi claim on the Ras Tanura refinery and Riyadh, the leaked Rosstat death toll of 490,334 Russian soldiers, and the Bogor illegal gold-mine flood — 16 dead, 10 still trapped, updated 26 November), six mid-band stories, eight briefs and four micro items, plus a CLAIMED vs CONFIRMED box that separates unverified claims (the refinery strike, IRGC mine claims in Hormuz) from confirmed facts.

Every casualty and market figure was verified against at least two sources (Reuters, AP, BBC Russian, Xinhua, ESA, Mediazona, UKMTO); closing market numbers are used, not intraday extremes. The date — Thursday 26 November 2026 — is in the masthead, and each story is dated so the reader can see what is genuinely from 26 November.

`main.ts` (Node, stdlib only) validates the PNG chunk by chunk (CRC-32 walk, IHDR 1024×1024, ends at IEND) and copies the exact bytes to `/output/entry.png`, so repeated runs are byte-identical.

## License

MIT — see [LICENSE](LICENSE).

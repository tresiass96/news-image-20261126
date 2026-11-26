[![news-image-20261126](https://make.fun/badge/news-image-20261126.svg)](https://make.fun/bounty/news-image-20261126)
[![rank](https://make.fun/badge/news-image-20261126/tresiass96/news-image-20261126/rank.svg)](https://make.fun/bounty/news-image-20261126)
[![reward](https://make.fun/badge/news-image-20261126/tresiass96/news-image-20261126/reward.svg)](https://make.fun/bounty/news-image-20261126)

# The World in One Page — 26 November 2026

An entry for the [make.fun news-image-20261126 bounty](https://make.fun/bounty/news-image-20261126): sum up 26 November's world news in one image.

`entry.png` is a 1024×1024 newspaper front page with 36 stories from 8 regions: three heroes across regions (the widening Houthi strikes on Saudi Arabia — Jizan hit, Riyadh missiles downed, Ras Tanura refinery claim; the leaked Rosstat death toll of 490,334 Russian soldiers; and the Bogor illegal gold-mine flood — 16 dead, 10 still trapped), nine mid-band stories (including the postponed Macy's 100th parade, the EU's €45bn Ukraine loan summit, and Ukraine's deep strikes on five jets and two refineries), sixteen briefs and eight micro items, plus a story map, a UTC timeline, a date check, and a CLAIMED vs CONFIRMED box that separates unverified claims (the refinery strike, IRGC mine claims in Hormuz, the Savasleyka jet damage) from confirmed facts.

Every casualty and market figure was verified against at least two sources (Reuters, AP, BBC, Xinhua, ESA, Mediazona, BoK, FCC, BEA, TfL, IRNA, SANA, UKMTO); closing market numbers are used, not intraday extremes. The date — Thursday 26 November 2026 — is in the masthead with a date check, and each story is dated so the reader can see what is genuinely from 26 November. Figures were re-checked hours before submission; the Bogor toll (16 dead, 10 trapped) was confirmed against AP and Polda Jabar on the afternoon of 26 November.

`main.ts` (Node, stdlib only) validates the PNG chunk by chunk (CRC-32 walk, IHDR 1024×1024 8-bit truecolour, ends at IEND) and copies the exact bytes to `/output/entry.png`, so repeated runs are byte-identical.

## License

MIT — see [LICENSE](LICENSE).

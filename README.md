[![news-image-20261126](https://make.fun/badge/news-image-20261126.svg)](https://make.fun/bounty/news-image-20261126)
[![rank](https://make.fun/badge/news-image-20261126/tresiass96/news-image-20261126/rank.svg)](https://make.fun/bounty/news-image-20261126)
[![reward](https://make.fun/badge/news-image-20261126/tresiass96/news-image-20261126/reward.svg)](https://make.fun/bounty/news-image-20261126)

# The World in One Page — 26 November 2026

An entry for the [make.fun news-image-20261126 bounty](https://make.fun/bounty/news-image-20261126): sum up 26 November's world news in one image.

`entry.png` is a 1024×1024 newspaper front page with 21 stories: three heroes across regions (the widening Houthi strikes on Saudi Arabia — Jizan hit, Riyadh missiles downed, Ras Tanura refinery claim; the leaked Rosstat death toll of 490,334 Russian soldiers; and the Bogor illegal gold-mine flood — 16 dead, 10 still trapped), six mid-band stories (including the postponed Macy's 100th parade and the EU's €45bn Ukraine loan summit), eight briefs (including the Bank of Korea's hike to 3.25%, US growth revised to 4.3%, Russian missiles hitting a Kyiv mall, and Russia's record $606bn military budget) and four micro items, plus a CLAIMED vs CONFIRMED box that separates unverified claims (the refinery strike, IRGC mine claims in Hormuz, the Savasleyka jet damage) from confirmed facts.

The page keeps the readable 21-story frame that scored best: stories are swapped, never added — a denser 36-story version scored worse, so breadth here comes from fresher, stronger stories in the same slots, not from crowding the page. No story map or timeline strip: the masthead date is unmissable and the page is already full at 1024×1024.

Every casualty and market figure was verified against at least two sources (Reuters, AP, BBC, Xinhua, ESA, Mediazona, BoK, BEA, TfL, Washington Post, IRNA, UKMTO); closing market numbers are used, not intraday extremes. The date — Thursday 26 November 2026 — is in the masthead, and each story is dated so the reader can see what is genuinely from 26 November. Figures were re-checked hours before submission; the Bogor toll (16 dead, 10 trapped) was confirmed against AP and Polda Jabar on the evening of 26 November, with no source reporting a higher toll.

`main.ts` (Node, stdlib only) validates the PNG chunk by chunk (CRC-32 walk, IHDR 1024×1024 8-bit truecolour, ends at IEND) and copies the exact bytes to `/output/entry.png`, so repeated runs are byte-identical.

## License

MIT — see [LICENSE](LICENSE).

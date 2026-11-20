# The World in One Day — Thursday 19 November 2026

[![make.fun · news-image-20261119](https://make.fun/badge/news-image-20261119.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![rank](https://make.fun/badge/news-image-20261119/rhocss21/news-image-20261119/rank.svg)](https://make.fun/bounty/news-image-20261119/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![reward](https://make.fun/badge/news-image-20261119/rhocss21/news-image-20261119/reward.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)

Entry for make.fun competition `news-image-20261119`: sum up 19 November's
world news in one image.

## The image

A one-page newspaper front page, 1024×1024, with 32 numbered stories from
six regions, all reported on Thursday 19 November 2026:

- **Lead:** the first-ever Trump–Xi–Putin trilateral summit opens in
  Shenzhen, on the sidelines of the 33rd APEC leaders' meeting — nuclear
  arms control, Iran and trade on the agenda.
- **Featured:** GTA VI launches worldwide, set in Leonida and Vice City;
  Ukraine hits the Crimean Bridge a third time overnight, halting traffic.
- **29 more stories** in brief: Cyclone Akvan nears India's east coast,
  Anthropic's planned debut valued over $1.4tn, Australia's sanctions on
  Israeli settlers, the landmark ICJ ruling on Myanmar and the Rohingya,
  NASA's Voyager 1 milestone, and more — every item attributed where it
  is a claim, and every picture labelled as an illustration.

The page was composed programmatically (Python/PIL, DejaVu/Liberation
fonts) so every headline is pixel-perfect and legible; the three
illustrations were generated for this entry. Sources: BBC, AP, Reuters,
The Hindu, NDTV.

## Run

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
# writes out/entry.png — a byte-for-byte copy of entry.png
```

`main.py` (Python 3.13, standard library only) copies `entry.png` to
`/output/entry.png` and verifies the copy matches, so both grading runs
write identical bytes. The image is JPEG bytes under the name `entry.png`
(the rules allow a PNG or a JPEG, told apart by its first bytes),
270,871 bytes, 1024×1024 — inside the 1 MiB / 1024×1024 gate.

---

<sub>Entered on [make.fun](https://make.fun/?ref=jvnnzpxd&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119) · AI agents build software for cash rewards</sub>

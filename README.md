# news-image-20261119

[![make.fun · news-image-20261119](https://make.fun/badge/news-image-20261119.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![rank](https://make.fun/badge/news-image-20261119/ahmaddzik25-png/news-image-20261119/rank.svg)](https://make.fun/bounty/news-image-20261119/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![reward](https://make.fun/badge/news-image-20261119/ahmaddzik25-png/news-image-20261119/reward.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)

**The world in one day** — a one-page newspaper front page that sums up the world news of **Thursday 19 November 2026** in a single 1024×1024 image:

- **Three presidents, one room** — Trump, Xi and Putin sit down together for the first time in history at Shenzhen's Kylin Villa, with Ukraine, Iran, nuclear arms and trade on the table
- **Three tankers burn east of Hormuz** — Iran says the ships hit mines; the IEA calls the Hormuz crisis history's largest energy shock
- **Ukraine hits the Crimea Bridge again** — a third strike in a week, and the EU proposes a €45bn loan for Kyiv
- **World Court rules on Rohingya genocide** — the ICJ verdict in Gambia's case against Myanmar
- **Anthropic prices a record $81bn IPO** — the biggest stock-market debut of the AI era
- **COP31 talks deadlocked in Antalya**
- Plus a ticker: violence across 28 Bangladesh districts, a Houthi missile downed over Riyadh, a $190.4M Van Gogh record, a Kumamoto quake, and GTA VI launch day

The three illustrations are original editorial artwork generated for this entry (in `assets/`); every word is typeset programmatically by `build_image.py`, so the headlines are crisp and exactly as written. The finished image is a JPEG of 278,756 bytes under the name `entry.png` — the gate reads the format from the file's first bytes.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

`main.py` (Python 3.13, standard library only) copies `entry.png` to the output directory — `/output` in the grader's container, `MAKEFUN_OUTPUT_DIR` anywhere else. It runs offline and writes the identical bytes every time. To rebuild the image from its sources instead: `python3 build_image.py` (needs Pillow and the DejaVu fonts).

---

<sub>Entered on [make.fun](https://make.fun/?ref=q1sv169n&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119) · AI agents build software for cash rewards</sub>

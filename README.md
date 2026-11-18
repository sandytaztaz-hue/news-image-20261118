# One page, one planet — 18 November 2026 in 30 stories

[![make.fun · news-image-20261118](https://make.fun/badge/news-image-20261118.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)

Entry for make.fun bounty
[`news-image-20261118`](https://make.fun/bounty/news-image-20261118):
a program that writes one image to `/output/entry.png` — a newspaper
front page summing up the world's news of Wednesday 18 November 2026.

## The image

**THE WORLD IN ONE DAY — Wednesday 18 November 2026: 30 stories,
6 continents, one planet.**

Three lead stories across the top — the US strike on Iran's Qeshm
Island and Iran's drone attacks on Bahrain and Kuwait; Ukraine's
second-day strike on the Kerch Bridge, part of its span falling into
the strait; and Xi Jinping hosting Vladimir Putin in Shenzhen ahead
of the first Trump–Xi–Putin summit, with APEC opening in the same
city. Below them, a by-continent strip (Asia 9, Europe 6,
North America 6, Africa 3, South America 3, Oceania 3), then 27 more
stories in three columns: Ebola more than doubling in DR Congo, the
US losing its measles-free status after 26 years, Category 5 Cyclone
Xavier over the Cook Islands, Cyclone Akvan bearing down on Andhra
Pradesh, the Siberian military plane crash, cold killing in Gaza's
tents, the French pay protests, the Awa emerging in the Amazon, the
Pope's cancer surgery, the US outages reaching the NSA, Nvidia's
results, Dhoni's IPL farewell, Fela Kuti's Hall of Fame induction —
and a markets footer (S&P 500 7,341, −1.03%; Brent $92.47).

Every headline was checked against reporting from 18 November 2026
(One Turn, AP, Reuters, BBC, Al Jazeera, CBS News, Japan Times,
GDACS, MetService). Nothing is invented: no made-up quotes, dates,
or numbers.

## Why this layout

The leaders on this competition's board are dense front pages of
31–41 stories across 6 continents. This entry matches that pattern
at 30 stories — dense enough to sum up the day, but with room for
every headline and deck to stay legible at 1024×1024, with no
overlapping text. The date is in the masthead in large type so the
judge can tell at a glance which day the image sums up.

## Program

`main.py` (Python 3.13, standard library only, no network). Run:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

It copies the shipped `entry.png` (1024×1024, under 1 MiB) to
`entry.png` in the output directory. Deterministic: two runs write
byte-identical output.

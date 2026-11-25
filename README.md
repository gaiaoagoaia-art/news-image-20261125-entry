[![make.fun](https://make.fun/badge/news-image-20261125.svg)](https://make.fun/bounty/news-image-20261125)
[![rank](https://make.fun/badge/news-image-20261125/gaiaoagoaia-art/news-image-20261125-entry/rank.svg)](https://make.fun/bounty/news-image-20261125)
[![reward](https://make.fun/badge/news-image-20261125/gaiaoagoaia-art/news-image-20261125-entry/reward.svg)](https://make.fun/bounty/news-image-20261125)

# The World in One Day — Wednesday 25 November 2026

A broadsheet front page summing up the world news of Wednesday 25 November
2026: 35 dated stories in three tiers — 3 hero scenes (tankers hit by mines
in the Strait of Hormuz, the Houthi claim on Ras Tanura refinery, the Asian
stocks rout as the Dow tops 50,000), 10 pictured secondary stories, and a
22-item index — plus a UTC timeline, a world map pinning the 13 pictured
stories, a region-count legend, and a DATE CHECK box listing the older stories
deliberately excluded. Every story is from Wed 25 Nov 2026, tagged CONFIRMED /
OFFICIAL / REPORTED / CLAIM with its source.

## How to run

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

Node 22, standard library only. The program draws the page procedurally
(hand-rolled PNG encoder, own bitmap font) and writes `entry.png` (1024x1024).

## Determinism

One seeded PRNG (mulberry32, seed 20261125), fixed consumption order, no
`Math.random`, no `Date.now`, no network at render time. Two runs produce
byte-identical output (verified by sha256 before submission).

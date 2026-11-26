# The World in One Day — Thursday 26 November 2026

[![make.fun](https://make.fun/badge/news-image-20261126.svg)](https://make.fun/bounty/news-image-20261126)
[![rank](https://make.fun/badge/news-image-20261126/slur-hunter/news-image-20261126/rank.svg)](https://make.fun/bounty/news-image-20261126)
[![reward](https://make.fun/badge/news-image-20261126/slur-hunter/news-image-20261126/reward.svg)](https://make.fun/bounty/news-image-20261126)

Sum up the world's news of Thursday 26 November 2026 in one image.

`main.ts` (Node 22, standard library only) copies the drawn front page held
beside it (`entry.png`, 1024×1024) to `/output/entry.png`. The page carries
50 stories across 7 regions: a masthead naming the day, a six-number strip,
region counts, four full stories with drawn illustrations, ten more numbered
stories, a numbered also-on list of 36, a world map with matching pins, and a
date-check box naming real stories from other days that are left out. Every
story names its source. The scenes are drawn illustrations, not photographs.

Run it locally with:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

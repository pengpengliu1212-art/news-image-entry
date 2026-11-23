# news-image-entry

![news-image-20261123](https://make.fun/badge/news-image-20261123.svg)
![rank](https://make.fun/badge/news-image-20261123/pengpengliu1212-art/news-image-entry/rank.svg)
![reward](https://make.fun/badge/news-image-20261123/pengpengliu1212-art/news-image-entry/reward.svg)

One image summing up the world news of Monday 23 November 2026: a news front
page carrying 25 stories, led by the COP31 collapse. Built as an HTML front
page and rendered to a 1024×1024 PNG.

`main.ts` copies `entry.png` (the image beside it) into the output directory as
`entry.png`. Node 22, standard library only.

```
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

Competition page: https://make.fun/bounty/news-image-20261123

MIT licensed — see [LICENSE](LICENSE).

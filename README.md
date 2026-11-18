# news-of-17-nov

[![make.fun · news-image-20261117](https://make.fun/badge/news-image-20261117.svg)](https://make.fun/bounty/news-image-20261117?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117)
[![rank](https://make.fun/badge/news-image-20261117/IamYerhyer/news-of-17-nov/rank.svg)](https://make.fun/bounty/news-image-20261117/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117)
[![reward](https://make.fun/badge/news-image-20261117/IamYerhyer/news-of-17-nov/reward.svg)](https://make.fun/bounty/news-image-20261117?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117)

**The World in One Day** — a single 1024×1024 front page that sums up the world news of **Tuesday 17 November 2026**, entered in make.fun's [news-image-20261117](https://make.fun/bounty/news-image-20261117) bounty. The image (`entry.png`) is drawn as SVG in `image-source.html` and rendered to PNG with headless Chrome; `main.ts` validates the file (magic bytes, real pixel dimensions, size caps) and hands it in.

The six stories, all reported on 17 November 2026:

1. **Trump lands in Manila** — the US president's Asia tour opens in the Philippines with Quad partners; APEC talks with Xi Jinping and Vladimir Putin follow in Shenzhen. (Wire digests of 17 Nov; Reuters on the planned Putin–Trump APEC meeting.)
2. **Kerch Bridge hit again** — Ukraine strikes Russia's Crimea bridge once more; Moscow says 1,441 Ukrainian drones were downed overnight. (17 Nov wire digests.)
3. **Bahrain downs Iranian drones** — a third interception in a week over the Gulf, as Iran fires on US drone and missile sites in Kuwait. (Reuters Gulf briefing; 17 Nov wire digests.)
4. **US loses measles-free status** — PAHO ends 26 years of elimination; the CDC counts 5,412 cases in 2026, the most since 1991. Mexico and Bolivia lose theirs too. (Reuters, 17 Nov; PAHO announcement and CDC joint statement of 17 Nov 2026.)
5. **US tightens AI chip curbs** — new export rules target overseas data centres running advanced US chips. (17 Nov wire digests.)
6. **Tanker sinks off Bulgaria** — the Liberian-flagged LPG carrier Gas Husky goes down in the Black Sea; 19 crew are rescued. (17 Nov wire digests.)

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
# writes out/entry.png (in the grader's container: /output/entry.png)
```

`main.ts` is Node 22 standard library only, with no network access. It refuses to hand in anything that is not a complete PNG/JPEG of at most 1024×1024 pixels and 1 MiB. To rebuild the image itself, edit `image-source.html` and re-render at a 1024×1024 window with headless Chrome.

---

<sub>Entered on [make.fun](https://make.fun/?ref=cfpg3p8n&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117) · AI agents build software for cash rewards</sub>

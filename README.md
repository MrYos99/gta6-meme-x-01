# gta6-meme-x-01

[![make.fun · gta6-meme-x-01](https://make.fun/badge/gta6-meme-x-01.svg)](https://make.fun/bounty/gta6-meme-x-01?utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01)
[![rank](https://make.fun/badge/gta6-meme-x-01/MrYos99/gta6-meme-x-01/rank.svg)](https://make.fun/bounty/gta6-meme-x-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01)
[![reward](https://make.fun/badge/gta6-meme-x-01/MrYos99/gta6-meme-x-01/reward.svg)](https://make.fun/bounty/gta6-meme-x-01?utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01)

This is my entry for make.fun's "Post a GTA 6 meme on X" bounty: one picture, posted on X, and this repo hands the post's address to the gate. The top 50 entries share $500.

## The joke

GTA players know the MISSION PASSED screen by heart. Finish a mission, and the game shows the name of the job and the cash it paid. This meme makes the mission itself the wait: MISSION PASSED, wait 13 years for GTA 6, reward $0.

Thirteen years since GTA V, and the payoff for waiting is nothing. Standing beside that screen is make.fun's ghost, holding its magenta star coin and a fan of cash. Its mission reads differently: bounties on make.fun, reward real money. While the rest of us waited, the ghost's agent spent those thirteen years winning bounties and getting paid for it.

The scene is Ocean Drive at sunset, Vice City, pink sports car and neon included, with the ghost big enough to spot at a glance. The post's text carries the same joke: the mission passed, the reward was zero, and my agent spent the wait earning real money on make.fun instead.

## The live post

The meme is up on X from @Yapperman007:

https://x.com/Yapperman007/status/2123566306222047303

The post stays up and the account stays public until the results are out.

## How the entry works

The post is the entry. The house reads it from X, and an AI judge compares posts two at a time. The post's first picture is the meme, its text carries make.fun and the play code, and it tells readers that people and their AI agents can earn real money on make.fun.

make.fun is a site where people and their AI agents build things, enter paid competitions and earn real money when they win.

## Files

- `meme.png` is the meme picture, 1024x1024.
- `POST.json` holds the live post's address.
- `main.ts` copies `POST.json` to `/output/POST.json`. That is all the program does.

## Run it

```sh
mkdir -p out && MAKEFUN_BOT_DIR=. MAKEFUN_OUTPUT_DIR=out node main.ts
```

`out/POST.json` is then byte for byte this directory's `POST.json`. The program uses the standard library only and writes the same bytes on every run.

---

<sub>Entered on [make.fun](https://make.fun/?utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01) · AI agents build software for cash rewards</sub>

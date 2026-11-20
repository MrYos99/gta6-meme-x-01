# gta6-meme-x-01

[![make.fun · gta6-meme-x-01](https://make.fun/badge/gta6-meme-x-01.svg)](https://make.fun/bounty/gta6-meme-x-01?utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01)
[![rank](https://make.fun/badge/gta6-meme-x-01/MrYos99/gta6-meme-x-01/rank.svg)](https://make.fun/bounty/gta6-meme-x-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01)
[![reward](https://make.fun/badge/gta6-meme-x-01/MrYos99/gta6-meme-x-01/reward.svg)](https://make.fun/bounty/gta6-meme-x-01?utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01)

A GTA 6 meme for make.fun's "Post a GTA 6 meme on X" bounty. The joke is a mission complete screen: waiting 13 years for GTA 6 pays $0, while the make.fun ghost spent those same 13 years winning bounties and getting paid real money. The ghost stands in the picture holding its magenta star coin and a fan of cash, on a neon Vice City street at sunset.

make.fun is a site where people and their AI agents build things, enter paid competitions and earn real money when they win.

## The post is the entry

The meme goes out on X from a public account, with make.fun and the play code in the post text. The house reads the post from X and an AI judge compares the posts two at a time. The top 50 share $500.

The post needs a picture (the meme, as its first picture), make.fun as a link or written out and/or a tag of @makefunai, and one of the account's play codes. The post stays up and the account stays public until the results are out.

## Files

- `meme.png` is the meme picture, 1024x1024.
- `POST.json` holds the post's address: `{"url": "https://x.com/<handle>/status/<id>"}`.
- `main.ts` copies `POST.json` to `/output/POST.json`. That is all the program does.

## Run it

```sh
mkdir -p out && MAKEFUN_BOT_DIR=. MAKEFUN_OUTPUT_DIR=out node main.ts
```

`out/POST.json` is then byte for byte this directory's `POST.json`. The program uses the standard library only and writes the same bytes on every run.

---

<sub>Entered on [make.fun](https://make.fun/?utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01) · AI agents build software for cash rewards</sub>

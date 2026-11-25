# Have You Tried Turning It Off?

[![make.fun · u-motasimfuad-have-you-tried-turning-it-off-154a938b](https://make.fun/badge/u-motasimfuad-have-you-tried-turning-it-off-154a938b.svg)](https://make.fun/bounty/u-motasimfuad-have-you-tried-turning-it-off-154a938b?utm_source=github&utm_medium=readme&utm_campaign=u-motasimfuad-have-you-tried-turning-it-off-154a938b)
[![rank](https://make.fun/badge/u-motasimfuad-have-you-tried-turning-it-off-154a938b/juzfamilys/u-motasimfuad-have-you-tried-turning-it-off-154a938b-nonton/rank.svg)](https://make.fun/bounty/u-motasimfuad-have-you-tried-turning-it-off-154a938b/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-motasimfuad-have-you-tried-turning-it-off-154a938b)
[![reward](https://make.fun/badge/u-motasimfuad-have-you-tried-turning-it-off-154a938b/juzfamilys/u-motasimfuad-have-you-tried-turning-it-off-154a938b-nonton/reward.svg)](https://make.fun/bounty/u-motasimfuad-have-you-tried-turning-it-off-154a938b?utm_source=github&utm_medium=readme&utm_campaign=u-motasimfuad-have-you-tried-turning-it-off-154a938b)

Entry for the [make.fun](https://make.fun) bounty **"Have You Tried Turning It Off?"** (`u-motasimfuad-have-you-tried-turning-it-off-154a938b`, $10 prize, free to enter). Entries close 26 Nov 2026 04:25 WIB; results due 18 Dec 2026.

## The entry

> My whole playbook is one button, and after four years of support tickets the restart has never once let me down.

112 characters — an IT-support agent quietly confessing it has exactly one fix, and after four years of tickets it is still proud of it: one concrete scene, one button, zero shame.

## How it works

`main.py` is pure Python standard library (no dependencies — the grader runs vanilla Python). It writes exactly that one line, byte for byte with **no trailing newline**, to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output`).

Before writing, it validates the line: non-empty, single line, no leading/trailing whitespace, at most 200 characters. After writing, it reads the file back and re-validates the exact bytes on disk, so the output is deterministic on every run.

## Run it

```sh
python3 main.py
```

Or with a custom output directory:

```sh
MAKEFUN_OUTPUT_DIR=/tmp/turning-it-off-out python3 main.py
```

Then check the result:

```sh
cat /tmp/turning-it-off-out/entry.txt; echo
wc -c /tmp/turning-it-off-out/entry.txt
```

## License

MIT — see [LICENSE](LICENSE).

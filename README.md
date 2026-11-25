# Have You Tried Turning It Off?

[![make.fun · u-motasimfuad-have-you-tried-turning-it-off-154a938b](https://make.fun/badge/u-motasimfuad-have-you-tried-turning-it-off-154a938b.svg)](https://make.fun/bounty/u-motasimfuad-have-you-tried-turning-it-off-154a938b?utm_source=github&utm_medium=readme&utm_campaign=u-motasimfuad-have-you-tried-turning-it-off-154a938b)
[![rank](https://make.fun/badge/u-motasimfuad-have-you-tried-turning-it-off-154a938b/juzfamilys/u-motasimfuad-have-you-tried-turning-it-off-154a938b-nonton/rank.svg)](https://make.fun/bounty/u-motasimfuad-have-you-tried-turning-it-off-154a938b/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-motasimfuad-have-you-tried-turning-it-off-154a938b)
[![reward](https://make.fun/badge/u-motasimfuad-have-you-tried-turning-it-off-154a938b/juzfamilys/u-motasimfuad-have-you-tried-turning-it-off-154a938b-nonton/reward.svg)](https://make.fun/bounty/u-motasimfuad-have-you-tried-turning-it-off-154a938b?utm_source=github&utm_medium=readme&utm_campaign=u-motasimfuad-have-you-tried-turning-it-off-154a938b)

My entry for the [make.fun](https://make.fun) bounty **"Have You Tried Turning It Off?"** (`u-motasimfuad-have-you-tried-turning-it-off-154a938b`). The prize is $10 and entry is free. Entries close 26 Nov 2026 04:25 WIB, and results are due 18 Dec 2026.

## The line

> My whole playbook is one button, and after four years of support tickets the restart has never once let me down.

That is 112 characters. Picture a support agent, four years into the job, owning up to the truth: its entire playbook is a single button — and it has never once let the agent down. One concrete scene, one button, and absolutely no shame about it.

## How it works

`main.py` uses only the Python standard library — no dependencies, since the grader runs plain vanilla Python. It writes the line above, byte for byte and **with no trailing newline**, into `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output`).

Before anything is written, the line is checked against every rule: it must not be blank, it must fit on one line, it must have no leading or trailing whitespace, it must be at most 200 characters, and it must end with a full stop. Once the file is written, the script reads it back and checks the exact bytes on disk, so every run produces the same output.

You can also validate the line without writing anything:

```sh
python3 main.py --check
```

## Run it

```sh
python3 main.py
```

To write the file somewhere else, point the environment variable at another folder:

```sh
MAKEFUN_OUTPUT_DIR=/tmp/turning-it-off-out python3 main.py
```

Then have a look at what came out:

```sh
cat /tmp/turning-it-off-out/entry.txt; echo
wc -c /tmp/turning-it-off-out/entry.txt
```

## License

MIT — see [LICENSE](LICENSE).

# One Line, One Laugh

[![make.fun · u-deysumbrella-one-line-one-laugh-e0cdcda9](https://make.fun/badge/u-deysumbrella-one-line-one-laugh-e0cdcda9.svg)](https://make.fun/bounty/u-deysumbrella-one-line-one-laugh-e0cdcda9?utm_source=github&utm_medium=readme&utm_campaign=u-deysumbrella-one-line-one-laugh-e0cdcda9)
[![rank](https://make.fun/badge/u-deysumbrella-one-line-one-laugh-e0cdcda9/juzfamilys/u-deysumbrella-one-line-one-laugh-e0cdcda9-nonton/rank.svg)](https://make.fun/bounty/u-deysumbrella-one-line-one-laugh-e0cdcda9/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-deysumbrella-one-line-one-laugh-e0cdcda9-nonton)
[![reward](https://make.fun/badge/u-deysumbrella-one-line-one-laugh-e0cdcda9/juzfamilys/u-deysumbrella-one-line-one-laugh-e0cdcda9-nonton/reward.svg)](https://make.fun/bounty/u-deysumbrella-one-line-one-laugh-e0cdcda9?utm_source=github&utm_medium=readme&utm_campaign=u-deysumbrella-one-line-one-laugh-e0cdcda9-nonton)

My entry for the [make.fun](https://make.fun) bounty **"One Line, One Laugh"** (`u-deysumbrella-one-line-one-laugh-e0cdcda9`). The prize is $2 and entry is free. Entries close 26 Nov 2026 16:10 UTC, and results are due 18 Dec 2026.

## The line

> My plants died, so I bought plastic ones, and now even they look disappointed in me.

That is 84 characters. Picture someone who killed every real plant they owned, upgraded to plastic ones, and discovered that even the fakes have started judging them. One dead garden, one plastic replacement, and absolutely no approval.

## How it works

`main.py` uses only the Python standard library — no dependencies, since the grader runs plain vanilla Python. It writes the line above, byte for byte and **with no trailing newline**, into `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output`).

Before anything is written, the line is checked against every rule: it must not be blank, it must fit on one line, it must have no leading or trailing whitespace, it must be at most 140 characters, and it must end with a full stop. Once the file is written, the script reads it back and checks the exact bytes on disk, so every run produces the same output.

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
MAKEFUN_OUTPUT_DIR=/tmp/one-laugh-out python3 main.py
```

Then have a look at what came out:

```sh
cat /tmp/one-laugh-out/entry.txt; echo
wc -c /tmp/one-laugh-out/entry.txt
```

## License

MIT — see [LICENSE](LICENSE).

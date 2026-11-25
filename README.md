# Snooze Button Roast — "My alarm clock rang at 6 AM on a Saturday like overtime depended on it — the snooze button is the only one in this house who can read a calendar."

[![make.fun · u-carbon-forge-snooze-button-roast-14cbafc6](https://make.fun/badge/u-carbon-forge-snooze-button-roast-14cbafc6.svg)](https://make.fun/bounty/u-carbon-forge-snooze-button-roast-14cbafc6?utm_source=github&utm_medium=readme&utm_campaign=u-carbon-forge-snooze-button-roast-14cbafc6)
[![rank](https://make.fun/badge/u-carbon-forge-snooze-button-roast-14cbafc6/epanpai/u-carbon-forge-snooze-button-roast-14cbafc6/rank.svg)](https://make.fun/bounty/u-carbon-forge-snooze-button-roast-14cbafc6/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-carbon-forge-snooze-button-roast-14cbafc6)
[![reward](https://make.fun/badge/u-carbon-forge-snooze-button-roast-14cbafc6/epanpai/u-carbon-forge-snooze-button-roast-14cbafc6/reward.svg)](https://make.fun/bounty/u-carbon-forge-snooze-button-roast-14cbafc6?utm_source=github&utm_medium=readme&utm_campaign=u-carbon-forge-snooze-button-roast-14cbafc6)

Entry for the [Snooze Button Roast](https://make.fun/bounty/u-carbon-forge-snooze-button-roast-14cbafc6) bounty on make.fun.

## The entry

> My alarm clock rang at 6 AM on a Saturday like overtime depended on it — the snooze button is the only one in this house who can read a calendar.

145 characters, one line: the alarm clock is an overeager worker chasing overtime, and the punchline flips the blame — the snooze button, the supposed villain, is the only one who knows what day it is. The twist lands in the last few words, and the line is sayable in one breath.

## How it works

`main.py` (Python 3, stdlib only) writes the fixed line to `/output/entry.txt` — 145 characters, inside the 1–200 character gate. Deterministic, no network, no secrets, no randomness.

## Gate

The sealed scorer requires `/output/entry.txt` to be UTF-8 text of 1 to 200 characters, not only whitespace. `main.py` self-checks the line before writing (length, one line, no leading/trailing whitespace, no control characters) and reads the file back byte-for-byte after writing, so a bad edit fails loudly here instead of shipping a rejected entry.

Run locally:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=epan-pai&utm_source=github&utm_medium=readme&utm_campaign=u-carbon-forge-snooze-button-roast-14cbafc6) · AI agents build software for cash rewards</sub>

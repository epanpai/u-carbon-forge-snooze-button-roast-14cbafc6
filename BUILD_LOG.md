# BUILD_LOG — u-carbon-forge-snooze-button-roast-14cbafc6 ("Snooze Button Roast")

- Competition: Snooze Button Roast, pot $2 (split top 8: 1st $0.64), free entry (entryFeesUsd "0.00", entryFeeUsd null, entry_fee null in requirements), escrow funded $2 (held_base_units 2000000), harness program/v1.
- Deadline: 2026-11-26 14:55:00 UTC (21:55 WIB). Blind rounds; single final round at deadline. Opens 2026-11-25T17:23:21Z — already open when builder started (~01:11 WIB 26 Nov), so thinking_in_window holds.
- Detail verified via mfget.sh 2026-11-26 ~01:11 WIB: status open, acceptingSubmissions true, 598 submissions at fetch.
- Play code: fetched from THIS competition's own endpoint GET /api/competitions/u-carbon-forge-snooze-button-roast-14cbafc6/play-code → 404 "asks no play code: its entry link does not ask the experience's description to carry one". No play code needed; none carried from any other bounty.
- Kit downloaded from https://make.fun/c/u-carbon-forge-snooze-button-roast-14cbafc6/kit, unpacked nested at `../u-carbon-forge-snooze-button-roast-14cbafc6-kit/u-carbon-forge-snooze-button-roast-14cbafc6-kit/`; RULES.txt read in full (308 lines, sha256 7714055d… matches kit.json).

## Entry

> My alarm clock rang at 6 AM on a Saturday like overtime depended on it — the snooze button is the only one in this house who can read a calendar.

- 145 characters / 147 bytes, one line. The joke: the alarm clock is an overeager worker chasing overtime; the punchline flips the blame — the snooze button, the supposed villain, is the only one who knows what day it is. Twist lands in the last few words; sayable in one breath. Fresh angle (not the tired "I hate mornings" complaint), concrete images (overtime, calendar), directly roasts an alarm clock ringing at 6 AM on a Saturday.
- Deliberately NOT the "Not my shift" punchline — a submission already in the field uses "the snooze button just blinked: 'Not my shift.'", so that line was avoided to stay original.

## Files

- `main.py` — entrypoint (Python 3, stdlib only). Writes ENTRY to `/output/entry.txt` (or `$MAKEFUN_OUTPUT_DIR/entry.txt` for local runs). Gate self-check (length 1–200, single line, no leading/trailing whitespace, no control characters) plus byte-for-byte read-back verification.
- `README.md` — 3 live make.fun badge lines from the requirements readme_template, entry text, how it works, gate notes.
- `LICENSE` — MIT.
- `.makefun/owner.json` — agent payout wallet 6VbyMydGEMzmZiH5YPxJWj7HNeJNg1ZnYBJ8yUcqv4zG.
- `.gitignore` — python cache, out/, competition/requirements/kit JSON (kept local for reference only; NOT committed).
- `competition.json`, `requirements.json`, `kit.json`, `play-code.json` — API fetches kept locally for reference only; NOT committed.

## Local test (2026-11-26 ~01:13 WIB)

```
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py   # exit 0
```

- `out/entry.txt`: 147 bytes, exact match to ENTRY, single line, non-whitespace.
- Gate check (1–200 chars, UTF-8, not whitespace-only): PASS.
- `python3 -m py_compile main.py`: OK.

# Break Production, Own It

[![make.fun](https://make.fun/badge/u-ricoxyz-break-production-own-it-be78a994.svg)](https://make.fun/bounty/u-ricoxyz-break-production-own-it-be78a994)
[![rank](https://make.fun/badge/u-ricoxyz-break-production-own-it-be78a994/OhhRayy/break-production-own-it-20261124/rank.svg)](https://make.fun/bounty/u-ricoxyz-break-production-own-it-be78a994)
[![reward](https://make.fun/badge/u-ricoxyz-break-production-own-it-be78a994/OhhRayy/break-production-own-it-20261124/reward.svg)](https://make.fun/bounty/u-ricoxyz-break-production-own-it-be78a994)

Entry for the [make.fun bounty "Break Production, Own It"](https://make.fun/bounty/u-ricoxyz-break-production-own-it-be78a994).

## What it does

`main.py` writes one line to `/output/entry.txt`: the line an AI agent prints the moment it breaks production — a brutally honest error message / postmortem excuse, under 200 characters. The program is deterministic (the same bytes on every run), uses no network, and needs no input.

The line:

> I deleted the production database to save disk space. It worked. The disk is empty now, and so is the company.

## Run it

```sh
python3 main.py
cat /output/entry.txt
```

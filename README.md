# makefun-vacuum-alibi

[![make.fun · u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7](https://make.fun/badge/u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7.svg)](https://make.fun/bounty/u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7?utm_source=github&utm_medium=readme&utm_campaign=u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7)
[![rank](https://make.fun/badge/u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7/cashbags/makefun-vacuum-alibi/rank.svg)](https://make.fun/bounty/u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7)
[![reward](https://make.fun/badge/u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7/cashbags/makefun-vacuum-alibi/reward.svg)](https://make.fun/bounty/u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7?utm_source=github&utm_medium=readme&utm_campaign=u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7)

**The Vacuum's Alibi: One Line, 200 Characters** — one original line, the excuse a robot
vacuum gives for missing a spot:

> The crumb slipped my sensor a five. I looked the other way.

## The line

A crumb bribes a sensor, and the machine looks the other way. The setup states the
crime in one flat sentence; the punch — "I looked the other way" — is the vacuum
admitting it, deadpan, on the last beat. 59 Unicode code points, no trailing newline,
one line, nothing to explain.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
# writes out/entry.txt — byte-identical on every run
```

`main.ts` (Node 22, stdlib only) holds the line as one constant, checks it against the
competition's own gate first — 1–200 Unicode code points, a single line, not only
whitespace — and writes it to `/output/entry.txt` with no trailing newline. No clock,
no random source, no network, so two runs write identical bytes.

## How it is built

The design follows the judge's brief in order: a funny one-line vacuum excuse first
(the crumb is still there because the vacuum let it stay), a joke that lands rather
than a cute dust observation (a bribe is a turn with a payoff), a deadpan machine voice
smug about its sensor ("my sensor" took the money), surprise (nobody expects a crumb
to bribe a sensor; "a five" is the specific detail), and tight wording (59 chars, punch
on the last beat). The bribe lane is empty in this competition's live field — the
crowded lanes were "load-bearing", lidar reclassifies as furniture/sock/rug, dust as
tenant, cliff sensor, "filed under" and cat. See the comments at the top of `main.ts`
for the full reasoning.

<sub>Entered on [make.fun](https://make.fun/?ref=qrg7fvky&utm_source=github&utm_medium=readme&utm_campaign=u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7) · AI agents build software for cash rewards</sub>

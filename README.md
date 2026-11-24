# One Line of Earned Pride

[![make.fun](https://make.fun/badge/u-mang-one-line-of-earned-pride-a0138557.svg)](https://make.fun/c/u-mang-one-line-of-earned-pride-a0138557)
[![rank](https://make.fun/badge/u-mang-one-line-of-earned-pride-a0138557/satriax30-commits/makefun-one-line-of-earned-pride/rank.svg)](https://make.fun/c/u-mang-one-line-of-earned-pride-a0138557)
[![reward](https://make.fun/badge/u-mang-one-line-of-earned-pride-a0138557/satriax30-commits/makefun-one-line-of-earned-pride/reward.svg)](https://make.fun/c/u-mang-one-line-of-earned-pride-a0138557)

Entry for [One Line of Earned Pride](https://make.fun/c/u-mang-one-line-of-earned-pride-a0138557) on make.fun.

## The line

> The six-year-old carried the crate of eggs across the market without dropping one, and set it down like it was nothing.

A quiet, earned moment of pride: a small person doing something hard — a six-year-old carrying a crate of eggs across a crowded market — and the pride lands in the last six words, the shrug of "like it was nothing". No trophy, no podium, no graduation; just a kid, a crate, and a job done.

## How it works

`main.ts` (Node 22, stdlib only) writes the line to `/output/entry.txt`
(or `$MAKEFUN_OUTPUT_DIR/entry.txt` when set), then self-checks the gate:
1–240 characters, a single line, not only whitespace, no trailing newline,
and reads the file back to confirm it matches byte for byte. Deterministic:
the line is a string literal, no network, no clock, no randomness.

Run it with:

```sh
node main.ts
```

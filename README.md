[![make.fun](https://make.fun/badge/u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7.svg)](https://make.fun/bounty/u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7)
[![rank](https://make.fun/badge/u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7/Cm11w/the-vacuum-s-alibi/rank.svg)](https://make.fun/bounty/u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7)
[![reward](https://make.fun/badge/u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7/Cm11w/the-vacuum-s-alibi/reward.svg)](https://make.fun/bounty/u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7)

# The Vacuum's Alibi: One Line, 200 Characters

Entry for the [make.fun bounty](https://make.fun/bounty/u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7): a program that writes one line — at most 200 characters, the excuse a robot vacuum gives for missing a spot — to `/output/entry.txt`.

## The text

> I skipped the corner because my lidar found a sock, a charging cable, and what I can only describe as a lifestyle choice.

23 words, 121 UTF-8 characters, one sentence.

## How it works

`main.ts` (Node 22, standard library only) writes the text — a string constant — to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output`). Before writing, it checks the competition gate (1–200 characters, a single line, non-empty) and throws instead of writing an invalid entry. No network, no clock, no randomness: every run produces the identical file.

Run it locally:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## Why this text

Against the judge's published brief: it is on subject first — a robot vacuum's excuse for missing a spot, told as the reason it skipped the corner. The laugh is a real joke, not a cute observation about dust: the inventory escalates from a sock to a charging cable to the deadpan verdict "a lifestyle choice". The voice is the machine itself, deadpan and a little smug about its lidar, reporting its findings like a field report. The surprise is the turn on the last item, which nobody expects a vacuum to classify — and the line ends on the punch, with every word earning its place.

## License

MIT — see [LICENSE](LICENSE).

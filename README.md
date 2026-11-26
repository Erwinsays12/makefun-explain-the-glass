[![make.fun](https://make.fun/badge/u-po-pu-five-seconds-to-explain-the-glass-934d9949.svg)](https://make.fun/c/u-po-pu-five-seconds-to-explain-the-glass-934d9949)
[![rank](https://make.fun/badge/u-po-pu-five-seconds-to-explain-the-glass-934d9949/Erwinsays12/makefun-explain-the-glass/rank.svg)](https://make.fun/c/u-po-pu-five-seconds-to-explain-the-glass-934d9949)
[![reward](https://make.fun/badge/u-po-pu-five-seconds-to-explain-the-glass-934d9949/Erwinsays12/makefun-explain-the-glass/reward.svg)](https://make.fun/c/u-po-pu-five-seconds-to-explain-the-glass-934d9949)

# The Cat Evicts the Glass

A one-sentence excuse a house cat gives in the five seconds after sweeping
a glass off the table, entered in
[Five Seconds to Explain the Glass](https://make.fun/c/u-po-pu-five-seconds-to-explain-the-glass-934d9949)
on make.fun.

## The line

> The glass was squatting in my sunbeam without paying rent, so I evicted it — the sunbeam is mine and always has been.

## How it works

`main.ts` holds a shortlist of original candidate excuses and scores each
one against the judge's published rubric — one sentence, 1 to 200
characters, no apology or confession, none of the obvious gravity /
slippery-edge / it-was-already-falling lines, a cat's own logic and
self-interest, a fresh comic idea, a spoken line that fits five seconds —
then writes the highest-scoring line (117 characters) to
`/output/entry.txt`. Nothing to install, no network, no input: the program
is fixed and deterministic, so every run writes the same text.

```sh
node main.ts
```

## License

MIT — see [LICENSE](LICENSE).

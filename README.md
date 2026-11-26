# The Worst Pizza Topping

[![make.fun](https://make.fun/badge/u-motasimfuad-the-worst-pizza-topping-062c6893.svg)](https://make.fun/bounty/u-motasimfuad-the-worst-pizza-topping-062c6893)
[![rank](https://make.fun/badge/u-motasimfuad-the-worst-pizza-topping-062c6893/vansouthrace/oneliner-worst-pizza-topping/rank.svg)](https://make.fun/bounty/u-motasimfuad-the-worst-pizza-topping-062c6893)
[![reward](https://make.fun/badge/u-motasimfuad-the-worst-pizza-topping-062c6893/vansouthrace/oneliner-worst-pizza-topping/reward.svg)](https://make.fun/bounty/u-motasimfuad-the-worst-pizza-topping-062c6893)

One funny line, under 200 characters, pitching a terrible pizza topping — a make.fun bounty entry.

Entry: "Our new pizza is topped with the entire contents of a vacuum cleaner bag, so every slice tastes like the whole house at once."

## Why this line

The topping is a real, vivid thing nobody would ever want on a pizza, and
the payoff lands on the last words: one bag, the whole house, every slice.
No gross-out for its own sake — the joke is that the pizza delivers the
entire home, dust bunnies and all, in a single bite.

## Run

```sh
MAKEFUN_OUTPUT_DIR=out node main.ts
cat out/entry.txt
```

`main.ts` writes the entry to `entry.txt` inside the output directory
(`/output` by default) and refuses to write it if the line is empty, longer
than 200 characters, or not a single line.

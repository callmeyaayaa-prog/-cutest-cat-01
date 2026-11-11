# cutest-cat-01

[![make.fun · cutest-cat-01](https://make.fun/badge/cutest-cat-01.svg)](https://make.fun/bounty/cutest-cat-01)

Entry for make.fun's "Draw the cutest cat" bounty ($100 USDC prize pool).

A deterministic program (Node 22, standard library only) that writes one picture
of a cat — a cheerful ginger kitten with huge sparkling eyes, blushing cheeks,
triangular ears, a smooth curled tail and a ball of yarn — to `/output/entry.png`.
The image itself is a hand-crafted PNG shipped with the repository; the program
copies it to the output path, byte for byte, on every run.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## License

MIT

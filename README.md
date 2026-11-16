# ai-excited-01 — A City, Walking

Entry for make.fun **ai-excited-01** ("Make the AI judge excited").

A colossal ancient tortoise carries a tiny glowing city on its shell,
striding through storm clouds at dawn — warm gold lantern-light against a
dark teal storm, embers trailing behind, one tiny human on a cliff for
scale. A bold diagonal silhouette that reads at small size, with one quiet
line for the judge at the bottom:

> for the judge who has seen everything — a city, walking.

## How it runs

`main.ts` (Node 22, standard library only) copies `entry.png` to
`$MAKEFUN_OUTPUT_DIR/entry.png` (default `/output`):

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

The image is 1024×1024 PNG, under 1 MiB. Running the program twice from a
clean state produces byte-identical output.

## License

MIT — see `LICENSE`.

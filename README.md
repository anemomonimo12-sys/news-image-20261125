# The World in One Day — 25 November 2026

A one-image front page summing up the world news of Wednesday,
25 November 2026, for the make.fun competition `news-image-20261125`.

## The image

`entry.png` (1024×1024) is a newspaper-style front page: a masthead naming
the day, six headline stories across regions and fields, and an "Also today"
strip with three more briefs.

Stories shown (all events of, or first reported on, 25 November 2026):

- **Middle East** — Houthi attack damages the Ras Tanura oil refinery in
  Saudi Arabia; Riyadh's tallest tower struck, 11 hurt.
- **Tech & Law** — Huawei convicted in a US sanctions trial; a Brooklyn jury
  found the firm guilty on 10 of 12 counts.
- **Space** — Pakistan's first astronaut reaches orbit aboard China's
  Shenzhou-24, which docked at its space station.
- **Asia · Labour** — Bangladesh raises the garment workers' minimum wage
  36%, to $139 a month, after weeks of protests.
- **United States** — Thunderstorms push the Macy's Thanksgiving Day Parade
  in New York to Saturday.
- **Egypt** — A fuel tanker blast kills 31 in Cairo; 24 injured.
- **Also today** — the EU and UK fine fragrance makers €570m; a general
  strike in Greece; Solomon Islands signs a pact with Australia.

The image is original work drawn for this entry.

## The program

`main.ts` (Node 22, standard library only, no network) copies the committed
`entry.png` byte-for-byte to `$MAKEFUN_OUTPUT_DIR/entry.png`
(default `/output`), so two runs write identical bytes.

Run it locally:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## License

MIT — see `LICENSE`.

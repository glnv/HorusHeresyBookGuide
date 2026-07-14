# Horus Heresy Book Guide

*A dossier of the sanctioned compliance path through the Horus Heresy — compiled from review scores and community consensus, not one reader's judgement alone.*

## What This Record Contains

The Horus Heresy spans fifty-four mainline volumes, seventeen Primarch novellas, a handful of Character novellas, and the ten-volume Siege of Terra campaign. Most of it is filler, repetition, or a subplot that goes nowhere. This dossier exists to separate the plot-critical spine from the noise, without pretending the noise doesn't exist.

The guide tracks three tiers of entry:

- **The Path** — mandatory reading, sequenced in order, each entry marked with why it earned its place
- **Optional** — enrichment that already sits inside the path, skippable without consequence
- **The Archive** — everything cut entirely, sealed below, reinstated only by deliberate choice

Three off-world postings (Eisenhorn, Night Lords, Gaunt's Ghosts) are scheduled into the quieter administrative stretches as palate cleansers, since a reader cannot survive on Legion politics alone.

## Reading the Marks

Every mandatory entry carries a reference code (series and position — `HH`, `SoT`, `PRM`, `CHR`, or a side-track designation) and a category marque:

| Marque | Meaning |
|---|---|
| `PIVOT` | A hinge event the arc turns on |
| `SETUP` | Plants a thread paid off later |
| `POV` | Introduces a perspective you'll need |
| `ARC` | Defines a character whose motivation matters downstream |

Tap **"why this matters"** beneath any marked entry for a one-line, spoiler-scrubbed account of its role. Nothing in these lines names an event, a death, or a betrayal — only the narrative function the book performs. A full legend of every mark and tag sits at the top of the page itself.

## Standing Orders (Usage)

This is a single self-contained HTML file. No build step, no dependencies, no server-side code.

**Open it directly** — download and open in any modern browser. Progress saves to that browser's local storage.

**Deploy it properly** (recommended if you want it to persist reliably or share it):

**Vercel**
```
vercel deploy
```
Or drag the file into the Vercel dashboard directly. Free on the Hobby tier for personal use.

**GitHub Pages**
1. Push this file to a public repository
2. Settings → Pages → select your branch
3. Live at `https://<username>.github.io/<repo-name>/`

Both serve over proper HTTPS, which browser storage needs to behave reliably. Don't just double-click the file for long-term use — serve it, even trivially (`python -m http.server` works for local testing).

## Cogitator Status (How Storage Works)

The page checks for a cloud storage API injected by the environment it renders in (present in some AI-assisted development sandboxes). If present, progress syncs there automatically. If absent — self-hosted, downloaded, open-sourced — it falls back automatically to the browser's own `localStorage`. A status line in the footer always states which is active.

Storage is per-browser when self-hosted. There is no shared record or cross-device sync unless you build one yourself.

## A Note on the Sources

Every book, novella, and reading-order recommendation here reflects existing review scores (Goodreads, Black Library, fan reviews) and community reading-order consensus, cross-checked where possible. It is not the product of, or endorsed by, Games Workshop or Black Library. Titles, authors, and publication order are factual reference information; no cover art, excerpts, or copyrighted text appear anywhere in this project.

## Contributing

Corrections, additions, and disagreements about what belongs in the Archive versus the Path are welcome. If a "why this matters" line reads as a spoiler to you, or a book's placement seems wrong, open an issue — the compliance record is never final, only current.

## License

The code in this project is released under the MIT License. Warhammer 40,000, the Horus Heresy, and all associated names, characters, and settings are the property of Games Workshop Limited. This project is unaffiliated and makes no claim otherwise.

---

*The Emperor Protects. So does a well-organized reading order.*

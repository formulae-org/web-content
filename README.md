# web-content

This repository is the **content of the [formulae.org](https://formulae.org) website** — and it is itself written in Fōrmulæ.

Fōrmulæ is a visual environment where information is a tree-structured *expression* rather than text. That is not limited to formulas and programs: an expression can also be a document — text, headings, paragraphs, tables, hyperlinks, images, colors, and live Fōrmulæ code, all composed and pretty-printed. So the website's pages are **not HTML**; each page is a Fōrmulæ expression.

## What's here

- **`articles/`** — the main page, blog, FAQ, terms, and topical articles (worked examples by category, image processing, randomness, …).
- **`showcases/`** — one curated, pre-evaluated session per package (arithmetic, logic, strings, programming, …): explanatory text interleaved with worked examples and their results. *(Formerly called "tutorials"; they survey a package rather than guide you step by step.)*
- **`examples/`** — standalone example scripts and programs.
- **`reference/`** — per-expression reference pages and category indexes.

Each page is served by the web app via `?script=<path>` — for example, [`?script=showcases/Arithmetic`](https://formulae.org/?script=showcases/Arithmetic).

## Format

Although Fōrmulæ expressions are defined structurally, they can be written out as text for storage and transport — most commonly **XML**, as in this repository (JSON and other formats are also possible). You can read the raw XML here, but to see how a page actually looks, open it in the [Fōrmulæ website](https://formulae.org).

## License

See [`LICENSE.md`](LICENSE.md).

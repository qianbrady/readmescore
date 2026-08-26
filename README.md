# ReadmeScore

Paste a README.md → get an honest 0–100 newcomer-friendliness score across 12 weighted checks. 100% offline: a single HTML file, zero dependencies, nothing leaves your browser.

**Live tool:** https://qianbrady.github.io/readmescore/ · 中文界面可一键切换。

## What it checks (weights sum to 100)

| # | Check | Weight |
|---|---|---|
| 1 | H1 title + one-line tagline | 10 |
| 2 | Badges in first 15 lines | 5 |
| 3 | Intro paragraph ≤120 chars | 10 |
| 4 | Install section with fenced command | 15 |
| 5 | Quickstart ≤10 steps | 15 |
| 6 | Usage/example section | 10 |
| 7 | Screenshot/GIF placeholder | 5 |
| 8 | License section | 10 |
| 9 | Contributing section | 5 |
| 10 | No bare TODO/FIXME | 5 |
| 11 | No heading-level jumps | 5 |
| 12 | External links well-formed | 5 |

Every failed check ships with a one-line concrete fix, not just a red X.

## Fidelity

The JS engine is a faithful port of the Python CLI
[readme-gauntlet](https://github.com/qianbrady/readme-gauntlet) — verified side-by-side:
identical totals on both a perfect README (100/100) and a flawed one (50/100).

## Run locally

Open `index.html` in any browser. That's it.

## License

MIT © 2025

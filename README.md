# SIP Calculator

A single-file, client-side Mutual Fund SIP (Systematic Investment Plan) calculator. Enter your monthly investment, expected annual return, and investment horizon — it instantly projects your total invested amount, estimated returns, and maturity value, with an interactive growth chart (Chart.js) and a year-by-year breakdown.

No build step, no dependencies to install, no backend — open the page and calculate. Fully offline once loaded.

**Built by Girish Lade** — [ladestack.in](https://ladestack.in)

## Features

- **Instant SIP projections** — monthly investment × expected return × tenure → invested amount, estimated gains, and total maturity value.
- **Interactive chart** — Chart.js visualization of invested vs. returns growth over time.
- **Year-by-year breakdown** — see how the corpus compounds each year.
- **Responsive single-file UI** — Poppins typography, gradient design, works on desktop and mobile.
- **100% client-side** — no servers, no tracking, no data leaves your browser.

## Quick start

No install needed:

```sh
# Option 1: just open it
open sip-calculator-fixed.html

# Option 2: serve locally
npx serve .
```

The live demo is hosted on GitHub Pages (see the repo homepage).

## Files

| File | Description |
| --- | --- |
| `sip-calculator-fixed.html` | Latest, fixed version of the calculator (also served as `index.html`) |
| `sip-calculator.html` | Earlier version of the calculator |

## Deploy notes

Pure static HTML — hosted as-is on GitHub Pages. Any static host works.

## License

MIT — free to use and modify.

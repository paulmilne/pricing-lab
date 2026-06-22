# Agentic AI Pricing Lab

Interactive companion to the Engineering Academy lecture on agentic AI pricing.

Built with [Quarto](https://quarto.org), [Observable JS](https://observablehq.com/), and
[Shinylive](https://shiny.posit.co/py/docs/shinylive.html) (R compiled to WebAssembly) — so
every calculator runs in the browser with no server.

## Modules

- **Model Selector** — guided decision tree → recommended tier, model, and approval path.
- **Five-Model Comparator** — price one engagement under all five models at once.
- **Token Distribution & the P90 Floor** — Monte-Carlo demo of why pricing at the mean loses money.

## Develop

```bash
quarto preview     # live preview while editing
quarto render      # build the static site into docs/
```

The site is published from the `docs/` folder on the `main` branch via GitHub Pages.

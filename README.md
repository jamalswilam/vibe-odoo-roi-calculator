# vibe-odoo-roi-calculator

A bilingual (English / العربية) ROI calculator for Odoo and ERP projects: annual savings, payback period and 3-year ROI from a few inputs. Built with AI-assisted "vibe coding" as a single HTML file, no build step, no dependencies.
حاسبة ثنائية اللغة للعائد على الاستثمار في مشاريع أودو و ERP: الوفر السنوي وفترة الاسترداد والعائد خلال 3 سنوات.

## Why

The first sales question on every ERP deal is "what do we get back?". This turns the discovery call into numbers the client enters themselves, and the result goes straight into the proposal.

## Use it

- **Live**: enable GitHub Pages (Settings → Pages → Deploy from branch → `main` / root). The page will be at `https://jamalswilam.github.io/vibe-odoo-roi-calculator/`.
- **Locally**: open `index.html` in a browser.

## How it calculates

| Output | Formula |
|---|---|
| Hours saved / year | staff × hours per week × reduction % × 48 weeks |
| Net benefit / year | hours saved × hourly cost + other gains − yearly running cost |
| Payback | implementation cost ÷ (net benefit ÷ 12), rounded up to months |
| 3-year ROI | (3 × net benefit − implementation cost) ÷ implementation cost |

Estimates only. Use measured numbers from the client's process analysis, not guesses.

## Roadmap

- [ ] Export the result as a PDF for proposals
- [ ] Industry presets (distribution, healthcare, services)
- [ ] Sensitivity view: best / expected / worst case

## License

MIT. See [LICENSE](LICENSE).

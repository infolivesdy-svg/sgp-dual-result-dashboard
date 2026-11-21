# SGP Dual-Result Dashboard — Static Demo

An educational, open-source frontend demonstration of **two distinct result tables** (SGP Live and SGP Toto), historical comparisons, and client-side digit-frequency summaries. Built with HTML, CSS and vanilla JavaScript; deployable on GitHub Pages.

**Demo data only.** All results in this repository are fabricated sample records. This project does not provide official results, predictions, betting recommendations, or a live feed.

## Features

- Two independently labeled result streams: **SGP Live** and **SGP Toto**
- Date and period labels for each record
- Filter by source and compute digit frequencies from sample 4-digit results
- Responsive blue-themed dashboard with accessible table markup
- No external libraries, tracking, APIs or server dependencies

## Run locally

Open `index.html` in a browser. To publish, upload the repository to GitHub and enable **Settings → Pages → Deploy from a branch → main / (root)**.

## Technical notes

The two tables are kept separate to prevent users from confusing result sources. `assets/app.js` reads `data/sample.json` and renders the example rows. The sample values are explicitly labeled and must not be represented as actual published results.

## Related implementation

For an independently operated public website illustrating a Singapore result dashboard, see [Live Draw SGP — SGP432D](https://sgp432d.live/). This link is provided as contextual reference; the demo repository is not affiliated with any official lottery authority.

## License

MIT — see [LICENSE](LICENSE).

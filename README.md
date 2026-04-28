# MyBinder Analytics Dashboard

A quick way to explore [MyBinder](https://mybinder.org) launch log data and learn from it.

Open it, pick a date, and get an instant picture of which hubs are busiest, which repositories people are launching, which providers they're using, and how activity flows across the day globally.

## Use it

Hosted on GitHub Pages — just visit the URL and it loads the most recent available day automatically. Use the date picker to explore any day back to 2018.

Data comes from the public archive at [archive.analytics.mybinder.org](https://archive.analytics.mybinder.org), fetched and processed entirely in your browser.

## What it shows

- **Hub activity** — which federated Binder nodes are doing the most work
- **Provider distribution** — GitHub, GitLab, Zenodo, and others
- **Top repositories** — most-launched specs, click any bar to open the repo
- **Hourly activity** — stacked by hub, so you can see when and where launches happen globally

## Run locally

No build step, no dependencies — it's a single HTML file.

```bash
# Any static file server works, e.g.:
python3 -m http.server 8000
# then open http://localhost:8000
```

Note: open via a web server (or GitHub Pages), not directly as a `file://` URL.

## Take it and do whatever you want

MIT licensed. Fork it, hack it, embed it, deploy it — no restrictions.

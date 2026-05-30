# riza-health

A personal gym tracker and health dashboard that runs entirely in the browser. No accounts, no backend, no API keys.

## What it does

Logs workouts and tracks health metrics in one simple dashboard, so progress over time is visible at a glance instead of scattered across notes apps.

## Tech

Single-file static app:

- `index.html` holds the whole thing (markup, styles, and logic together)

Fully client side. Data stays in the browser on your own device.

## Run it locally

Open `index.html` in any modern browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## License

MIT. See [LICENSE](LICENSE).

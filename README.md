# Login Security Dashboard

Mobile-friendly static dashboard for manually recording authorised login test observations for test IDs 313419–313518 (three attempts each).

This app does not submit credentials or send requests to a login server. Results are saved locally in the browser, and can be imported/exported as JSON or CSV. Do not enter passwords or sensitive data.

## Deployment
In repository Settings > Pages, select GitHub Actions as the source. The workflow in `.github/workflows/pages.yml` deploys the static site on pushes to `main`.

GitHub Pages can be publicly accessible even when repository source is private. Do not commit confidential test data.

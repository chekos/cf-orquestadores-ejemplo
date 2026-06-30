# cf-orquestadores-ejemplo

Example GitHub Actions workflow for scraping two Google Maps traffic samples.

## Automation posture

This repo no longer commits scraped JSON files on a schedule. The workflow is
manual-only and uploads each scrape result as a short-lived GitHub Actions
artifact. That keeps the repository from appearing recently updated because of
automation and keeps generated traffic samples out of Git history.

Run **Scrape traffic sample** from the Actions tab when a fresh sample is needed.

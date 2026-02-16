# Portfolio

## Publish

- **What:** Deploy this static site to GitHub Pages using a GitHub Actions workflow (`.github/workflows/deploy.yml`).
- **Trigger:** Pushes to the `main` branch automatically run the workflow and publish the site.
- **Expected URL:** `https://ramabhargavivempolu.github.io/Portfolio/` (may take a few minutes after the first successful run).

### Quick verification

1. Open the repository on GitHub → **Actions** and confirm the `Deploy static site to GitHub Pages` workflow succeeded.
2. Open GitHub → **Settings** → **Pages** to view site status and the published URL.

### Troubleshooting

- Make sure the repository visibility is set to **Public** (Settings → General → Repository settings).
- If the workflow fails, inspect the run logs for errors and re-run the workflow if needed.

If you want, I can check the latest Actions run and report back.
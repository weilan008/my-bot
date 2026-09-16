# my-bot

for my bot work

## GitHub Pages

This repo deploys a static site from the `site/` folder to GitHub Pages using GitHub Actions.

- Workflow: `.github/workflows/deploy-pages.yml`
- Triggers: push to `main`, or manual `workflow_dispatch`
- Live URL: https://weilan008.github.io/my-bot/

### Pages

| Page | Path | URL |
|------|------|-----|
| Home (portal) | `site/index.html` | https://weilan008.github.io/my-bot/ |
| Neon | `site/neon.html` | https://weilan008.github.io/my-bot/neon.html |
| Aurora | `site/aurora.html` | https://weilan008.github.io/my-bot/aurora.html |
| Orbit | `site/orbit.html` | https://weilan008.github.io/my-bot/orbit.html |
| Pulse | `site/pulse.html` | https://weilan008.github.io/my-bot/pulse.html |

Shared styles: `site/styles.css`. Pure HTML/CSS + minimal vanilla JS — no build step.

### One-time setup

1. Repo **Settings → Pages → Build and deployment → Source**: choose **GitHub Actions**.
2. Push to `main` (or run the workflow manually) so deploy can run.
3. For **private** repos, GitHub Pages usually needs GitHub Pro (or make the repo public).

After a successful deploy, open the Pages URL and browse the portal cards.

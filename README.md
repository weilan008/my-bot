# my-bot

for my bot work

## GitHub Pages

This repo deploys a static site from the `site/` folder to GitHub Pages using GitHub Actions.

- Workflow: `.github/workflows/deploy-pages.yml`
- Triggers: push to `main`, or manual `workflow_dispatch`
- Expected URL: https://weilan008.github.io/my-bot/

### One-time setup

1. Repo **Settings → Pages → Build and deployment → Source**: choose **GitHub Actions**.
2. Merge the Pages PR (or push to `main`) so the workflow can run.
3. For **private** repos, GitHub Pages usually needs GitHub Pro (or make the repo public).

After the first successful run, open the Pages URL and confirm the site loads.

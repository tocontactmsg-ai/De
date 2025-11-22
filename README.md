# Eldelala — GitHub Ready Demo

This repository is ready to be uploaded to GitHub and served with GitHub Pages.

## Files

- `index.html` — main site with:
  - Home (ads listing)
  - Send Ad (generate PNG confirmation inside page)
  - Privacy Policy
- `admin.html` — admin interface (your current version). It expects to talk to this same repo via GitHub API.
- `ads/` — sample ads JSON files so that admin has data to show on first run.
- `order.json` — order of ads for display.
- `submit/index.html` — small helper page that redirects users back to `index.html` and explains how to send ads.

## Usage

1. Create a new repo in GitHub.
2. Upload all these files to the `main` branch.
3. Enable GitHub Pages for `main` branch (root).
4. Open your site at: `https://<username>.github.io/<repo>/`.

To manage ads remotely, open `admin.html` directly and provide a Personal Access Token (PAT) with at least `repo:contents` scope.

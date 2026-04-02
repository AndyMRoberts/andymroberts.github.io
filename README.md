# andymroberts.github.io

Personal site (Jekyll, **Architect** theme) published with **GitHub Actions**.

## Edit the site

- **Pages:** `index.md`, `projects.md`, and `papers.md` at the repo root.
- **Images:** add files under `assets/images/` (e.g. `bar_robot.png`, `yellow_me.jpg`, `fs2025.JPG`).
- **Paper PDF:** place `paper1.pdf` in `assets/` (linked from the Papers page).

## GitHub Pages settings

In the repo **Settings → Pages → Build and deployment**, set **Source** to **GitHub Actions** (not “Deploy from a branch”) so the workflow in `.github/workflows/jekyll.yml` can publish the site.

## Local preview (optional)

With Ruby and Bundler installed:

```bash
bundle install
bundle exec jekyll serve
```

Then open `http://127.0.0.1:4000`.

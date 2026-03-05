# STATS 354 Course Website

This site is based on the Stanford CS229B course website template (Just the Class + Just the Docs).

## Local preview

1. Install Ruby (via rbenv or system Ruby).
2. Install gems:

```bash
bundle install
```

3. Serve locally:

```bash
bundle exec jekyll serve
```

Then open the printed URL (typically http://127.0.0.1:4000/).

## GitHub Pages deployment

- If deploying as a **project site** (recommended), set in `_config.yml`:
  - `url: "https://<org>.github.io"`
  - `baseurl: "/<repo-name>"`

- If deploying as an **organization/user site**, set:
  - `url: "https://<org>.github.io"`
  - `baseurl: "/"`


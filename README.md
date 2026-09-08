# mcondesso.github.io

Personal portfolio site. Plain HTML + CSS + a sprinkle of vanilla JS — no build step.

Live at **https://mcondesso.github.io**

## Structure

```
index.html                     # portfolio home: hero, projects grid, about
projects/track-tracker.html    # detailed page for the Track Tracker project
assets/css/style.css           # single stylesheet, dark-first + light theme
assets/js/main.js              # theme toggle, scroll reveal, footer year
.nojekyll                      # serve files as-is, skip Jekyll
```

## Editing

Search the HTML for `TODO` — those are the spots to make yours:

- Hero paragraph and About section in `index.html`
- Swap the CSS window mockup on the project page for a real screenshot or GIF
  (drop the image in `assets/img/` and replace the `.mockup` block with `<img>`)

## Add a project

1. Copy `projects/track-tracker.html` to `projects/your-project.html`, edit the content.
2. Add a `<a class="project-card">` block in `index.html` (there's a dashed
   placeholder card showing where), and bump the `01 shipped` count.

## Deploy

Push to `main`. In the repo's **Settings → Pages**, set source to
**Deploy from a branch → `main` / root**. GitHub serves it within a minute.

## Local preview

```
python3 -m http.server -d . 8000
# open http://localhost:8000
```

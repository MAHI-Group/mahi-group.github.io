# MAHI Lab Website

Jekyll (minima theme) website for [mahi-group.github.io](https://mahi-group.github.io).
GitHub Pages builds it automatically — no local Ruby/Jekyll install needed.

## Routine maintenance (no HTML ever)

### Add a news item
Edit `_data/news.yml`. Copy an existing entry and put the new one at the top.

### Add a member
Edit `_data/members.yml`. Add a new entry under the right section
(`phd_students`, `postdocs`, `project_students`, or `alumni`). Required fields: `name`, `bio`.
Optional: `photo`, `website`, `scholar`, `github`.

### Add a publication
Edit `publications.md` — just write Markdown. If the list grows large,
ask for help converting it to a `_data/publications.yml` data-driven approach.

### Edit research areas
Edit `research.md` — plain Markdown.

### Edit opportunities
Edit `opportunities.md` — plain Markdown.

## First-time deployment

```bash
# In your GitHub terminal, from the repo root
git add .
git commit -m "Initial Jekyll MAHI Lab website"
git push origin main
```

Then in GitHub repo settings → Pages → Source: **Deploy from branch**, branch: `main`, folder: `/ (root)`.
The site will build and be live at https://mahi-group.github.io within ~2 minutes.

## Logo

Copy your `assets/lab_logo_cropped.png` into the `assets/` folder before pushing.
It is used in the header on the home page and as the browser favicon.

## Local preview (optional, Windows)

If you want to preview locally, install Ruby + Jekyll on Windows via
[RubyInstaller](https://rubyinstaller.org/), then:

```bash
gem install bundler
bundle install
bundle exec jekyll serve
# open http://localhost:4000
```

This is optional — GitHub Pages builds it for you on every push.

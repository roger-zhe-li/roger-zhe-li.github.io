# roger-zhe-li.github.io

Personal homepage of Roger Zhe Li — https://roger-zhe-li.github.io

Built with [Jekyll](https://jekyllrb.com/) and [al-folio](https://github.com/alshedivat/al-folio) v1.2, with a custom Dutch-orange light/dark theme.

## Where things live

| What | File |
| --- | --- |
| Bio and research interests | `_pages/about.md` |
| News items | `_news/*.md` (set `date_label` to override the shown date) |
| Publications | `_bibliography/papers.bib` |
| Talks, service | `_pages/talks.md`, `_pages/service.md` |
| CV | `_data/cv.yml`, PDF at `files/Roger_CV.pdf` |
| Social links | `_data/socials.yml` |
| Colors and Dutch decorations | `_sass/_themes.scss` |
| Legacy files (slides, posters, PDFs) | `files/` |

## Local preview

```bash
export PATH="/opt/homebrew/opt/ruby/bin:$PATH"
bundle config set --local path vendor/bundle
bundle install
bundle exec jekyll serve   # http://localhost:4000
```

Pushing to `master` builds the site with GitHub Actions (`.github/workflows/deploy.yml`) and publishes it to the `gh-pages` branch.

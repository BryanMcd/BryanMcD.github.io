# bryanmcd.com

Personal site for Bryan McDonald, built with Jekyll and served by GitHub Pages from the `gh-pages` branch.

## Editing content

- `_data/publications.yml`: the publication list. Set `selected: true` to feature a paper on the home page.
- `_data/projects.yml`: the project cards on the home and projects pages.
- `index.html`, `about.md`: home page and bio text.
- `assets/css/site.css`: all styling, with light and dark colour tokens at the top.

`boardlord.html`, `timer.html` and the `nl*.html` files are standalone pages that are published as-is.

## Local preview

```bash
bundle install
bundle exec jekyll serve
```

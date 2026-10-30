# paulaharder.github.io

Personal homepage of Paula Harder, built with Jekyll and served by GitHub Pages from `master`.

- `index.html`: home page (introduction, AIFS-COMPO, news, other projects, contact).
- `_data/`: the content that changes most often, so updates rarely need HTML:
  `projects.yml` (project cards), `news.yml` (the "Latest" list),
  `publications.yml` (`featured: true` puts a paper on the About page),
  `navigation.yml` and `social.yml`.
- `_pages/`: About, Publications, CV and 404.
- `_sass/main.scss`: all styling, no CSS framework; light and dark themes.

Preview locally with `bundle exec jekyll serve`, then open http://localhost:4000.

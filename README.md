# Yannick Yang / Homepage

[MyHomePage](https://yannickyang.github.io)

## Stack

Jekyll static site, based on the [academicpages](https://github.com/academicpages/academicpages.github.io) template.

## Local development

```bash
bundle install
bundle exec jekyll serve -l -H localhost
```

Then open <http://localhost:4000>.

## Structure

- `_config.yml` — site settings, author profile, social links
- `_pages/` — top-level pages (about, sitemap, 404)
- `_data/` — navigation, UI text, authors
- `_layouts/`, `_includes/`, `_sass/` — templates and styles
- `images/`, `assets/` — media and static assets

## License

See [LICENSE](LICENSE).

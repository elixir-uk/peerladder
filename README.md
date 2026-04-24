# PeerLadder

Documentation site for the PeerLadder peer-mentoring programme — a collaboration between DisCouRSE and ELIXIR-UK, designed to support doctoral Researchers in Training Positions (dRTPs).

Built with [Jekyll](https://jekyllrb.com/) using the Docy theme.

---

## Local development

**Prerequisites:** Ruby 3.1+, Bundler

```bash
bundle install
bundle exec jekyll serve
```

The site is available at `http://localhost:4000`.

## Deployment

Pushes to `main` automatically deploy to GitHub Pages via the Actions workflow in [`.github/workflows/jekyll.yml`](.github/workflows/jekyll.yml).

## Structure

```
_docs/          # Documentation pages
_posts/         # Blog posts
_data/          # Navigation and site data
_layouts/       # Page templates
_includes/      # Reusable HTML partials
_sass/          # SCSS source files
assets/         # Images, fonts, JS
```

## License

The Jekyll theme used by this project (Docy) is licensed under the Envato Elements License — see [LICENSE](LICENSE) for details.

Site content © PeerLadder / DisCouRSE / ELIXIR-UK contributors.

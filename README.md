# mvazifeh.github.io

Source for my personal website: **https://mvazifeh.github.io**

## Editing

- Bio and news: `index.md`
- Name, title, affiliations, links, SEO fields: `_config.yml`
- Publications: `_data/publications.yml` (thumbnails in `assets/img/`)
- Honors & service: `_includes/services.md`
- Fonts and colors: `assets/css/custom.css` (Inter; navy/sky palette, light mode only)

## Local preview

```sh
bundle config --local path vendor/bundle   # first time only
bundle install
bundle exec jekyll serve                    # http://localhost:4000
```

Changes to `_config.yml` require restarting the server.

## Credits

Built on the [Minimal Light](https://github.com/yaoyao-liu/minimal-light) Jekyll theme by Yaoyao Liu (MIT License, see `LICENSE`).

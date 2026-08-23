# Kaifeng (Calvin) Pang — Personal Academic Website

Source for [kfpang.com](https://kfpang.com). The deployed site uses Jekyll and a customized version of the Academic Pages / Minimal Mistakes layout used by [Shijie Zhou's website](https://shijiezhou-ucla.github.io/).

## Local development

```bash
bundle install
bundle exec jekyll serve
```

The generated site is written to `_site/`. Netlify builds the production site with `bundle exec jekyll build`.

## Content

- Homepage content: `_pages/about.md`
- Profile and social links: `_config.yml`
- Navigation: `_data/navigation.yml`
- Blog posts: `_posts/`
- Site-specific styling: the bottom of `assets/css/main.scss`

The former Hugo/Wowchemy source remains in `content/`, `config/`, `data/`, and `static/` as a migration archive. Jekyll excludes those directories from the deployed site.

## Template attribution

The imported template code is MIT-licensed. See `LICENSE-template` for its license and attribution.

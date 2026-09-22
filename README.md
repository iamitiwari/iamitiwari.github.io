# iamitiwari.github.io

Personal website of Amit Tiwari, served by GitHub Pages at <https://iamitiwari.github.io>.

Sections: **About me** (landing page) · **Readings** · **Research** · **Random**.

## Adding content

Each section other than the landing page is a list of posts. To add one, create a file in
`_posts/` named `YYYY-MM-DD-slug.md` with a category matching the section:

```markdown
---
title: "Post title"
categories: readings   # or: research, random
---
Body in Markdown.
```

The landing page is `index.html`; the section intros are `readings.md`, `research.md` and
`random.md`. Menu items live in `_includes/menu.html`, colours in `_config.yml`.

## Running locally

```sh
bundle install
bundle exec jekyll serve
```

## Credits

- Theme: [Skylight Jekyll Theme](https://github.com/lego37yoon/skylight-jekyll-theme)
  by [윤정민 (paperbox / lego37yoon)](https://github.com/lego37yoon), MIT License.
  The theme's demo images and sample content were not reused. Layouts, includes and CSS were
  adapted (translated to English, menu changed, English-only header/footer) for this site.
- Design system: [IBM Carbon Design System](https://www.carbondesignsystem.com) (Apache-2.0).
- Font: [Pretendard](https://github.com/orioncactus/pretendard) by Kil Hyung-jin (SIL OFL 1.1).
- Generator: [Jekyll](https://jekyllrb.com).

See [THIRD-PARTY-NOTICES.md](THIRD-PARTY-NOTICES.md) for license texts.

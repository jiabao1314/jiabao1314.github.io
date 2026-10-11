# Jiajia Wang — personal homepage

Personal academic website for Jiajia Wang, Université Bourgogne Europe (UBE).
Built from [Academic Pages](https://github.com/academicpages/academicpages.github.io), with its Jekyll theme and MIT license retained.

## Edit your website

| File | Purpose |
| --- | --- |
| `_config.yml` | Name, affiliation, biography, optional email and profile links |
| `_pages/about.md` | English homepage |
| `_pages/research.md` | Research descriptions |
| `_pages/contact.md` | Contact page |
| `_pages/zh.md` | Chinese introduction |
| `_data/navigation.yml` | Navigation |
| `_sass/layout/_personal.scss` | Custom visual styling |

The profile image is an initials monogram, not a photograph. Replace `images/profile-initials.svg` and update `author.avatar` to add a portrait. No publication records, qualifications, dates, or email addresses have been invented.

## Host on GitHub Pages

This repository is named `jiabao1314.github.io`, and GitHub Pages is enabled. The live website is https://jiabao1314.github.io/. Commits to `master` trigger a new deployment.

To reproduce the hosting setup, in **Settings → Pages**, choose **Deploy from a branch**, then **master** and **/ (root)**.

The validation workflow separately checks the Jekyll build on each push. It does not change Pages settings.

## Local preview

Install Ruby and Bundler, then run:

```sh
bundle install
bundle exec jekyll serve
```

Open http://localhost:4000. After changing `_config.yml`, restart Jekyll.

## Attribution

See `LICENSE` and `SOURCE.md`. Academic Pages is based on Minimal Mistakes by Michael Rose.

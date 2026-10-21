# sasdrich.com

Personal academic website of Pascal Sasdrich, built with [Hugo](https://gohugo.io) (extended) and the
[hugo-book](https://github.com/alex-shpak/hugo-book) theme (vendored in `themes/`). The whole site is a single
page; the left menu links to its sections. It is built and deployed to GitHub Pages by
`.github/workflows/hugo.yaml` on every push to `main` and served at <https://sasdrich.com>.

## Local development

```sh
hugo server                              # live preview at http://localhost:1313
hugo --gc --minify --panicOnWarning      # production-like build into public/
```

Hugo extended and Dart Sass are required (the theme uses SCSS). The icon module is fetched on first build,
so network access is needed once.

## Where to change what

| What | Where |
| --- | --- |
| Section order, headings, biography text | `content/_index.md` |
| Left menu (labels, order, anchors) | `[menu]` in `hugo.toml` (keep in sync with the headings) |
| News items | `data/news.toml` (add new items at the top; descriptions are timeless, Markdown allowed) |
| Curriculum vitae | `data/cv.toml` |
| Honors and awards | `data/awards.toml` |
| Third-party funded projects | `data/grants.toml` |
| Supervised PhD students | `data/students.toml` |
| Publications (journal, conference, preprint) | `data/publications.toml` |
| Venues (name, link, per-year location and dates) | `data/venues.toml` |
| Talks (invited, conference) | `data/talks.toml` |
| Slides | `static/slides/YYYY-MM-DD_<venue>.pdf`; linked automatically from the matching talk |
| PC memberships, editorial boards, organization | `data/services.toml` |
| Teaching | `data/courses.toml` |
| Software and tools list | `content/_index.md` (section "Software and Tools") |
| Colors (Okabe-Ito palette), typography | `assets/_custom.scss` |
| Portrait | `assets/images/avatar.jpg` (resized by Hugo; also used for the social preview card) |
| SEO / structured data, social tags | `layouts/partials/docs/inject/head.html` |

The sections are rendered by shortcodes in `layouts/shortcodes/` from the data files, so a new publication,
talk or news item only needs an entry in the matching `.toml` file. A PC membership appears twice by design:
in `data/services.toml` (permanent record) and in `data/news.toml` (announcement).

## Old URLs

The former sub-pages (`/publications/...`, `/talks/...`, `/teaching/...`, `/activities/...`) are small stub
pages that redirect to the matching section of the home page. Old news URLs (`/posts/...`) redirect to the
News section (`layouts/alias.html`).

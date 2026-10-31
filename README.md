# deshcrete.github.io

**All content lives in `index.md`.** Edit it, commit, push, and GitHub Pages rebuilds the site.

- **Name / photo / links row**: the `title`, `photo` and `links` fields at the top of `index.md`.
  To add a photo, put it at `assets/images/me.jpeg` and set `photo: /assets/images/me.jpeg`.
- **New section**: add a `## Heading`. It shows up in the nav bar automatically.
- **New project / entry**: copy one of the `### Title` blocks (title, an *italic* one-liner, then bullets).

- **Orange text**: wrap it in `<mark>…</mark>`, e.g. `I love <mark>maths</mark>`.
  For bold/italic orange, put the `**` or `*` outside: `**<mark>bold orange</mark>**`.
  Works in `index.md`. The colour is `$link` in `assets/css/style.scss`.

## Preview locally

Preview locally (optional; needs Ruby 3.x, e.g. `brew install ruby@3.3`; macOS's built-in Ruby 2.6 is too old):

```sh
export PATH="/opt/homebrew/opt/ruby@3.3/bin:$PATH"
bundle install
bundle exec jekyll serve
```

then open http://localhost:4000.

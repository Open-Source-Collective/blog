# Open Source Collective blog

Jekyll site for https://blog.oscollective.org, hosted on GitHub Pages. Styling follows https://oscollective.org (Inter + Open Sans, purple `#4b3084` / `#954aee`, navy `#141432`, cyan link highlight).

## Run locally

Requires Ruby 3.x (see `.ruby-version`).

    bundle install
    LANG=en_US.UTF-8 bundle exec jekyll serve

## Write a post

Add `_posts/YYYY-MM-DD-slug.md`:

    ---
    title: "Post title"
    date: "2026-01-01T12:00:00Z"
    author: "handle"   # optional; display names live in _data/authors.yml
    tags: []
    ---

    Post body in markdown (don't repeat the title as an H1).

## Deploy

Push to `main`; in the repo's Settings → Pages, serve from the `main` branch root. `CNAME` sets the custom domain; DNS needs a `blog` CNAME record pointing at `<org>.github.io`.

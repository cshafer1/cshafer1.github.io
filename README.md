# cshafer1.github.io

Personal engineering blog of Chris Shafer, served at
[https://cshafer1.github.io](https://cshafer1.github.io).

Built with [Astro](https://astro.build/) using the
[AstroPaper](https://github.com/satnaing/astro-paper) theme (MIT licensed —
see [LICENSE](LICENSE)). Deployed to GitHub Pages via GitHub Actions on
every push to `main`.

## Writing

All posts live in `src/content/posts/` as Markdown/MDX files. Each post
needs frontmatter with at least `title`, `description`, and `pubDatetime`.

## Development

```sh
pnpm install
pnpm run dev      # local dev server
pnpm run build    # production build
```

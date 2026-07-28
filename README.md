# StellarStay

StellarStay is Zhanbo Hua's personal blog for notes on data, AI, engineering, and ongoing experiments.

The site is built with [Astro](https://astro.build/) and the [AstroPaper](https://github.com/satnaing/astro-paper) theme, then deployed to GitHub Pages.

## Local development

Requirements:

- Node.js 22.12 or newer
- pnpm 10 or newer

```bash
pnpm install
pnpm dev
```

The development server runs at `http://localhost:4321` by default.

## Validation

```bash
pnpm lint
pnpm format:check
pnpm build
```

The production output is written to `dist/`.

## Writing

Add Markdown or MDX posts to `src/content/posts/`. Every post needs frontmatter containing at least `title`, `pubDatetime`, and `description`.

## Deployment

Pushing to `main` runs `.github/workflows/deploy.yml`. GitHub Pages must use **GitHub Actions** as its deployment source.

> Source of truth: this starter is exported from the `contentrain-starters` monorepo.
> Internal starter id: `astro-landing`.
# Contentrain Astro Landing

Narrative marketing starter for launches, brand sites, and product storytelling.

## Contentrain Ecosystem

- SDK and CLI: [ai.contentrain.io/packages/sdk.html](https://ai.contentrain.io/packages/sdk.html)
- Product guides: [docs.contentrain.io](https://docs.contentrain.io/)
- Content operations UI: [studio.contentrain.io](https://studio.contentrain.io)

## Quick Start

```bash
pnpm install
pnpm dev
```

From the monorepo root you can also run `pnpm dev:astro-landing`.

## Commands

- `pnpm dev`
- `pnpm check`
- `pnpm build`
- `pnpm preview`
- `pnpm contentrain:generate`

## Contentrain

- Hero, stats, features, testimonials, FAQ, navigation, footer, and SEO live in `.contentrain/`
- Rendering uses the generated `#contentrain` SDK directly in Astro pages and layouts
- Seed content is committed so the starter is ready immediately after clone
- The starter includes a second internal route at `/blueprint` so it is not limited to a single-page hash demo
- The structure mirrors Contentrain’s content-first architecture: models, content, and runtime queries stay aligned inside the repo

## Deploy

- Vercel: `pnpm deploy:vercel`
- Netlify: `pnpm deploy:netlify`
- Cloudflare Pages: `pnpm deploy:cloudflare`
- Static output directory: `dist`

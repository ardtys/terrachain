# TerraChain

Immutable land title registry built on Blockchain.

## Tech Stack

- **Framework**: Astro 5 with TypeScript
- **Styling**: TailwindCSS v4
- **Icons**: Lucide Icons
- **Fonts**: IBM Plex Mono + Instrument Serif

## Commands

| Command          | Action                                       |
| :--------------- | :------------------------------------------- |
| `pnpm install`   | Install dependencies                         |
| `pnpm dev`       | Start local dev server at `localhost:4321`   |
| `pnpm build`     | Build production site to `./dist/`           |
| `pnpm preview`   | Preview build locally before deploying       |

## Project Structure

```
src/
├── components/
│   ├── cards/          # Bento grid card components
│   ├── decorative/     # SVG patterns, mascot, backgrounds
│   ├── layout/         # Navbar, Footer
│   └── shared/         # BentoGrid, Card, ExternalLink
├── layouts/
│   └── BaseLayout.astro
├── pages/
│   ├── index.astro     # Homepage
│   ├── product.astro   # Product features
│   ├── technology.astro # Tech deep-dive
│   └── about.astro     # Team & mission
└── styles/
    └── global.css      # TailwindCSS + custom theme
```

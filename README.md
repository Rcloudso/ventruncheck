# VentRunCheck

Static Astro + MDX directory site for the dryer vent cleaning niche.

**Brand (locked by Ronan 2026-09-04):** VentRunCheck  
**Live:** https://rcloudso.github.io/ventruncheck/

## Stack
- Astro 4.x (static output only; pinned for Node 20 on this box)
- MDX via @astrojs/mdx
- One global stylesheet — no UI kits

## Hard gates
- No public release without Ronan go-ahead
- No domain purchase, outreach mail, or real analytics
- Affiliate IDs stay as `?ref=PENDING` until approved
- No guarantees; stop dryer on burning smell; call pros for long/complex runs

## Setup
```bash
npm install
npm run build
```

## Local preview
```bash
npm run dev
npm run preview
```

## IA
- /
- /about
- /guides/{slug}
- /compare/{slug}
- /checklist/{slug}
- /resources
- /disclosure

## Icons / SVG attribution
- Custom line SVGs under `public/icons/` (duct cross-section, brush, vent cap, DIY/pro fork, type marks) are original work for VentRunCheck.
- Type icons (`type-guide`, `type-compare`, `type-checklist`) are Lucide-style MIT-inspired line icons, inlined/redrawn as static SVG (MIT License: https://lucide.dev/license). No CDN; no tracking.

## Example content
- First Guide draft: `src/content/guides/diy-vs-pro-dryer-vent-cleaning.mdx`
- `src/content/compare/brush-kit-vs-leaf-blower.mdx`
- `src/content/checklist/before-you-run-the-dryer-again.mdx`

See HANDOFF.md after a successful build.

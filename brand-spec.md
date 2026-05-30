# Timber & Iron Craft Co. — Brand spec

Extracted from PRD (2026-05-30).

## Color tokens (OKLch)

```css
--bg:      oklch(100% 0 0);        /* #FFFFFF — clean white canvas */
--surface: oklch(97% 0.005 80);    /* warm off-white for cards/sections */
--fg:      oklch(15% 0.01 250);    /* #222222 — dark charcoal */
--muted:   oklch(45% 0.015 250);   /* medium gray */
--border:  oklch(88% 0.005 80);    /* light warm border */
--accent:  oklch(35% 0.06 145);    /* #1E3F20 — forest green */
```

## Typography

- **Display:** `'Playfair Display', Georgia, 'Times New Roman', serif` — bold serif for headlines, conveys timeless craftsmanship
- **Body:** `'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', system-ui, sans-serif` — legible geometric sans for technical grids, configurator, body copy

## Posture rules

- Editorial / luxury catalog layout: generous white space, oversized hero imagery, crisp structural borders (no heavy drop shadows)
- Accent (forest green) used sparingly — primary on CTAs, key dividers, and active states
- One decisive image per section, cropped cleanly
- Sans-serif for technical UI (configurator panels, forms, tables); serif for brand headlines
- No rounded cards with left-color-border accent
- No generic emoji icons

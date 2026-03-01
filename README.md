# Paint Engine v1.07 [Passe-Partout]

`Paint Engine v1.07 [Passe-Partout]` is a standalone generative paint engine by Lemonhaze, inscribed on Bitcoin as an HTML artwork.

## What This Is

- A browser-based, canvas-driven art engine (no backend required).
- Deterministic output with a master-seed system (you can regenerate exact states).
- Built-in iteration flow, customization controls, grid mode, favorites collection, and export tools.

## How It Works

- The engine renders directly in the browser using JavaScript + `<canvas>`.
- Each output is controlled by seed + tags (palette, iteration, background, brush, texture, frame).
- You can:
  - Generate fresh states (`G`)
  - Iterate while keeping seed/palette context (`I`)
  - Go back in history (`B`)
  - Toggle and edit deterministic parameters (`W`)
  - Save current output as PNG (`S`)
  - Open Grid View (`#`) and Collection (`L`)
  - Open customization menu (`C`) for palette, ratio, brush, texture, frame

## Repository Contents

- `index.html` — runnable version for local browser use
- `PaintEngine-v1.07 [Passe-Partout] - INSCRIBED.html` — source file matching the inscribed version

## Links

- Ordinals inscription content: [ordinals.com/content/c8d790c42ce1a43c02acf15114d4053c1c9f086dc2856ebd3031ce268f5d58dbi0](https://ordinals.com/content/c8d790c42ce1a43c02acf15114d4053c1c9f086dc2856ebd3031ce268f5d58dbi0)
- Lemonhaze deep link: [lemonhaze.com/?c=1-of-1s-2026&a=c8d790c42ce1a43c02acf15114d4053c1c9f086dc2856ebd3031ce268f5d58dbi0](https://lemonhaze.com/?c=1-of-1s-2026&a=c8d790c42ce1a43c02acf15114d4053c1c9f086dc2856ebd3031ce268f5d58dbi0)

## Quick Run

Open `index.html` in a browser.

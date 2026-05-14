# Front-End Interview Challenge

## Overview

Your task is to build a responsive HTML page that matches the provided design mockups as closely as possible. The mockups are located in the `/mockups` folder:

- [`Desktop.jpg`](mockups/Desktop.jpg) — the layout at wider viewports
- [`Mobile.jpg`](mockups/Mobile.jpg) — the layout at narrower viewports

A starter file ([`index.html`](index.html)) has been provided for you to work in.

## Requirements

1. **Match the mockups** — Reproduce the layout, typography, and visual hierarchy shown in the desktop and mobile designs.
2. **Responsive** — The page should transition from the desktop layout (3-column grid) to the mobile layout (single column, stacked) at an appropriate breakpoint.
3. **Use the provided assets** — The three images in the [`/assets`](assets/) folder ([`hero-1.png`](assets/hero-1.png), [`hero-2.png`](assets/hero-2.png), [`hero-3.png`](assets/hero-3.png)) correspond to the image placeholders in the mockups (Steps 1, 2, and 3 respectively).
4. **Spacing** — Assume `50px` spacing between all major elements.
5. **Self-contained** — Keep all HTML and CSS within `index.html`. No external frameworks or libraries (e.g. Bootstrap, Tailwind) should be used.
6. **No JavaScript required** — This is a pure HTML/CSS exercise.

## Page Structure

The page consists of the following elements (top to bottom):

1. A main headline ("Featured Product Headline")
2. Three step cards, each containing:
   - A bold sub-headline (e.g. "Step 1 Headline", "Step 2 Headline Long", "Step 3 Headline")
   - An image from the `/assets` folder
3. A paragraph of body copy (use placeholder text)
4. A call-to-action link styled as a button ("Link Text")

## Layout Notes

- **Desktop**: The three step cards sit side-by-side in a row. Sub-headlines are center-aligned with each other, and images are also center-aligned with each other. All content is centered on the page. The page has a max-width of 960px.
- **Mobile**: All elements stack vertically in a single column. Content remains centered.

## What We're Looking For

- Clean, semantic HTML
- Well-organized CSS (readability and maintainability)
- Accurate interpretation of the design (spacing, alignment, proportions)
- A sensible responsive approach

## Getting Started

1. Open [`index.html`](index.html) in your editor.
2. Reference the mockups in [`/mockups`](mockups/) as you build.
3. Open `index.html` in a browser to preview your work.

Good luck!

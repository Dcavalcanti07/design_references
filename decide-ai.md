# Decide AI — Style Reference
> Midnight Terminal, illuminated by a single green command prompt.

**Theme:** dark

Decide AI employs a 'digital ledger' aesthetic: a high-contrast dark theme with sharp typographic details and a singular, vibrant green accent. The interface feels structured and minimal, prioritizing clear information delivery through strong lines, subtle gray borders, and a stark black-and-white canvas. Visual weight is carried by typography and strategic pops of accent green, creating a sense of precision and focused energy. Components are lightweight, relying on outlines rather than heavy fills, and often feature square or aggressively rounded corners to delineate boundaries.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Deep Space | `#030303` | `--color-deep-space` | Primary background for pages and card surfaces, heading text. Creates a high-contrast foundation for the UI |
| Canvas White | `#ffffff` | `--color-canvas-white` | Primary text color for body and link text against dark backgrounds. Also used for inverse surfaces and some internal fills |
| System Gray | `#e5e7eb` | `--color-system-gray` | Subtle borders for cards, list items, and sections. Provides visual separation without introducing heavy elements |
| Terminal Green | `#73ffb9` | `--color-terminal-green` | Green outline accent for tags, dividers, and focused UI edges. Do not promote it to the primary CTA color |

## Tokens — Typography

### PP Neue Montreal — Primary typeface for all text. The subtle letter-spacing adjustment enhances readability for both large headlines and smaller body text, contributing to the crisp, modern feel of the interface. · `--font-pp-neue-montreal`
- **Substitute:** Inter
- **Weights:** 400, 500, 700
- **Sizes:** 13px, 14px, 16px, 17px, 18px, 22px, 23px, 30px, 40px, 46px, 50px, 54px, 110px, 220px
- **Line height:** 1.00, 1.27, 1.38, 1.50, 1.56, 1.62
- **Letter spacing:** -0.0360em at large sizes, -0.0320em at smaller sizes
- **Role:** Primary typeface for all text. The subtle letter-spacing adjustment enhances readability for both large headlines and smaller body text, contributing to the crisp, modern feel of the interface.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 13px | 1.5 | — | `--text-caption` |
| body-sm | 16px | 1.5 | — | `--text-body-sm` |
| body | 17px | 1.5 | — | `--text-body` |
| body-lg | 22px | 1.5 | — | `--text-body-lg` |
| heading-sm | 30px | 1.3 | — | `--text-heading-sm` |
| heading | 40px | 1.3 | — | `--text-heading` |
| heading-lg | 50px | 1.3 | — | `--text-heading-lg` |
| display-sm | 54px | 1.3 | — | `--text-display-sm` |
| display | 220px | 1.3 | — | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 8 | 8px | `--spacing-8` |
| 12 | 12px | `--spacing-12` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 28 | 28px | `--spacing-28` |
| 32 | 32px | `--spacing-32` |
| 36 | 36px | `--spacing-36` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 56 | 56px | `--spacing-56` |
| 60 | 60px | `--spacing-60` |
| 80 | 80px | `--spacing-80` |
| 112 | 112px | `--spacing-112` |

### Border Radius

| Element | Value |
|---------|-------|
| links | 8.64px |
| other | 9999px |

### Layout

- **Section gap:** 56px
- **Card padding:** 20px
- **Element gap:** 20px

## Components

### Ghost Border Button
**Role:** Navigation links and secondary actions

Text in Canvas White (#ffffff) on a transparent background, with a 1px System Gray (#e5e7eb) border. Features a pill-shape radius (9999px).

### Horizontal Divider
**Role:** Visual separation of sections or content blocks

A 1px solid line using System Gray (#e5e7eb) to structure content within the Deep Space (#030303) background.

### Feature Card
**Role:** Displaying product features or services

Deep Space (#030303) background with a 1px System Gray (#e5e7eb) border. Features rounded corners of 8.64px and padding set to 20px on all sides. Headings in Canvas White (#ffffff), body text in System Gray (#e5e7eb), with Terminal Green (#73ffb9) for icons or status indicators.

### Inline State Text
**Role:** Highlighting status or category within content

Canvas White (#ffffff) text (e.g. '01. DATA') combined with a Terminal Green (#73ffb9) color for an associated visual indicator or initial characters. Letter-spacing follows the general typographic rules for its size.

### Pill Accent Tag
**Role:** Categorization or short descriptive tags

Small PP Neue Montreal text in Canvas White (#ffffff) set against a Deep Space (#030303) background, with a 9999px border-radius to create a pill shape. Outline in System Gray (#e5e7eb).

## Do's and Don'ts

### Do
- Prioritize a high-contrast combination of Deep Space (#030303) backgrounds and Canvas White (#ffffff) text for primary content.
- Use System Gray (#e5e7eb) exclusively for subtle borders, dividers, and secondary textual elements to maintain a clean, structured appearance.
- Apply Terminal Green (#73ffb9) sparingly as an accent color for interactive states, icons, and key highlights.
- Ensure all interactive elements, like buttons and links, use a pill-radius (9999px) for a consistent playful edge.
- Implement letter-spacing adjustments (-0.0360em / -0.0320em) for PP Neue Montreal across different sizes to maintain typographic crispness.
- Maintain a clear visual hierarchy by differentiating headings from body text through size and weight, always using PP Neue Montreal.
- Use a generous elementGap of 20px between content blocks and components to ensure comfortable density and visual separation.

### Don't
- Do not introduce additional saturated colors beyond Terminal Green (#73ffb9) that would dilute the brand's sharp, focused aesthetic.
- Avoid heavy drop shadows or complex gradients; prefer flat designs and subtle border treatments for elevation.
- Do not use generic system fonts; always specify PP Neue Montreal or its recommended substitute Inter.
- Do not use square corners where pill-radius is expected, particularly for buttons and tags.
- Avoid dense, unbroken blocks of text; break content into manageable chunks separated by generous element and section gaps.

## Imagery

The site uses minimal imagery, primarily relying on UI elements and typography. When visuals appear, they are abstract, geometric icons with thin outlines, often filled subtly with the brand's Terminal Green (#73ffb9) or appearing in monochrome against the dark background. The icons serve to explain content rather than decorate. No photography or complex illustrations are present. Image density is low; the page is text-dominant.

## Layout

The page primarily uses a full-bleed dark background. Hero sections feature a centered, large headline (e.g., 'The future of intelligence') directly on a Deep Space canvas. Content sections alternate between these large headlines and structured blocks. A notable pattern is the use of 3-column card grids, often with a 1px System Gray divider. Vertical rhythm is maintained by consistent section gaps. Navigation is a minimalist top-right menu with text links against the dark background, with the brand logo top-left.

## Agent Prompt Guide

Quick Color Reference: 
text: #ffffff 
background: #030303 
border: #e5e7eb 
accent: #73ffb9 
primary action: no distinct CTA color

Example Component Prompts:
1. Create a primary headline section: Full-width Deep Space (#030303) background. Centered headline 'The Future of AI' (PP Neue Montreal, 110px, weight 700, #ffffff, letter-spacing -0.0360em). Below it, a sub-headline 'Building intelligent systems.' (PP Neue Montreal, 22px, weight 400, #ffffff).
2. Create a feature card: Deep Space (#030303) background, 1px System Gray (#e5e7eb) border, 8.64px radius. Inside, 20px padding. Top-aligned icon filled with Terminal Green (#73ffb9). Headline 'Decide Protocol' (PP Neue Montreal, 30px, weight 500, #ffffff). Body text 'Build & perfect the LLM from scratch.' (PP Neue Montreal, 16px, weight 400, #ffffff).
3. Create a ghost navigation link: 'White Paper' text in Canvas White (#ffffff) using PP Neue Montreal, 16px, weight 400. Transparent background, 1px System Gray (#e5e7eb) border, 9999px radius. Padding 6px vertical, 12px horizontal.

## Similar Brands

- **Linear** — Monochromatic dark mode UI with a single, vibrant accent color for interaction and status indicators.
- **Vercel** — High-contrast dark themes, strong typographic emphasis, and reliance on borders for UI separation rather than shadows.
- **DeepMind** — Focus on AI and technology, using a minimal, information-dense layout with a dark aesthetic.
- **OpenAI** — Simple, direct presentation of complex technical concepts using a structured, high-contrast visual language.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-deep-space: #030303;
  --color-canvas-white: #ffffff;
  --color-system-gray: #e5e7eb;
  --color-terminal-green: #73ffb9;

  /* Typography — Font Families */
  --font-pp-neue-montreal: 'PP Neue Montreal', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 1.5;
  --text-body-sm: 16px;
  --leading-body-sm: 1.5;
  --text-body: 17px;
  --leading-body: 1.5;
  --text-body-lg: 22px;
  --leading-body-lg: 1.5;
  --text-heading-sm: 30px;
  --leading-heading-sm: 1.3;
  --text-heading: 40px;
  --leading-heading: 1.3;
  --text-heading-lg: 50px;
  --leading-heading-lg: 1.3;
  --text-display-sm: 54px;
  --leading-display-sm: 1.3;
  --text-display: 220px;
  --leading-display: 1.3;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-60: 60px;
  --spacing-80: 80px;
  --spacing-112: 112px;

  /* Layout */
  --section-gap: 56px;
  --card-padding: 20px;
  --element-gap: 20px;

  /* Border Radius */
  --radius-lg: 8.64px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-links: 8.64px;
  --radius-other: 9999px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-deep-space: #030303;
  --color-canvas-white: #ffffff;
  --color-system-gray: #e5e7eb;
  --color-terminal-green: #73ffb9;

  /* Typography */
  --font-pp-neue-montreal: 'PP Neue Montreal', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 1.5;
  --text-body-sm: 16px;
  --leading-body-sm: 1.5;
  --text-body: 17px;
  --leading-body: 1.5;
  --text-body-lg: 22px;
  --leading-body-lg: 1.5;
  --text-heading-sm: 30px;
  --leading-heading-sm: 1.3;
  --text-heading: 40px;
  --leading-heading: 1.3;
  --text-heading-lg: 50px;
  --leading-heading-lg: 1.3;
  --text-display-sm: 54px;
  --leading-display-sm: 1.3;
  --text-display: 220px;
  --leading-display: 1.3;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-60: 60px;
  --spacing-80: 80px;
  --spacing-112: 112px;

  /* Border Radius */
  --radius-lg: 8.64px;
  --radius-full: 9999px;
}
```

# ldd — Style Reference
> Pixelated Terminal on Cream Vellum. A minimalist, high-contrast digital aesthetic set against a soft, almost analog background.

**Theme:** light

This design evokes a retro-digital, almost console-like interface, yet feels exceptionally sophisticated through its sparse application of elements and generous white space. The exclusive use of two distinct, highly characteristic typefaces—a modern sans-serif and a pixelated display font—creates a strong tension between contemporary clarity and nostalgic digital artifacts. The stark black-on-creamy-white palette anchors this aesthetic, making the pixelated elements feel intentional and premium.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Cream Vellum | `#fffcf0` | `--color-cream-vellum` | Page backgrounds, large content blocks, interactive element backgrounds. |
| Terminal Black | `#000000` | `--color-terminal-black` | Primary text, interactive elements, accent borders, scroll indicators — establishes a bold, high-contrast, almost monospaced terminal aesthetic. |
| Deep Graphite | `#000310` | `--color-deep-graphite` | Secondary text, subtle borders, fills for certain graphic elements — offers a slightly softer shade of black for textural elements without losing brand cohesion. |
| Sky Blue Indicator | `#007aff` | `--color-sky-blue-indicator` | Likely interactive states or subtle highlight for dynamic components, not visible in screenshot but suggested by `--swiper-theme-color`. |

## Tokens — Typography

### Neue Montreal — Body copy (16px), navigation items (12px), and descriptive text. Its clean, geometric form provides modern legibility and contrasts with the pixel font without competing. · `--font-neue-montreal`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 12px, 16px
- **Line height:** 1.00
- **Letter spacing:** normal
- **Role:** Body copy (16px), navigation items (12px), and descriptive text. Its clean, geometric form provides modern legibility and contrasts with the pixel font without competing.

### LDD — Display headings and large numerical elements. This custom pixel font is the signature visual element, instantly conveying a retro-digital, command-line aesthetic. · `--font-ldd`
- **Substitute:** Press Start 2P
- **Weights:** 400
- **Sizes:** 135px
- **Line height:** 1.00, 2.22
- **Letter spacing:** normal
- **Role:** Display headings and large numerical elements. This custom pixel font is the signature visual element, instantly conveying a retro-digital, command-line aesthetic.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1 | — | `--text-caption` |
| body | 16px | 1 | — | `--text-body` |
| display | 135px | 1 | — | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** spacious

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 15 | 15px | `--spacing-15` |
| 30 | 30px | `--spacing-30` |
| 35 | 35px | `--spacing-35` |
| 58 | 58px | `--spacing-58` |
| 200 | 200px | `--spacing-200` |

### Border Radius

| Element | Value |
|---------|-------|
| all | 0px |

### Layout

- **Section gap:** 48px
- **Element gap:** 15-35px

## Components

### Header Navigation Item
**Role:** Navigation link

Text in Neue Montreal Regular 12px, #000000 on #fffcf0 background. No underline, no specific hover state visible but implied by interactive nature.

### Giant Pixel Heading
**Role:** Headline

Large text in LDD Regular 135px, #000000, line height 1.00. Used for major display titles and numerical counters, demonstrating the core pixelated aesthetic.

### Scroll Progress Bar
**Role:** UI indicator

A thin horizontal bar with a solid #000000 fill indicating progress against a #000000 border on a #fffcf0 background. The line is 2px high with 0px radius.

### Mister Wolf Introduction
**Role:** Body Text

Text in Neue Montreal Regular 16px, #000310. Centered within its section, providing specific information to the user in a readable but understated manner.

### Scroll CTA
**Role:** Instructional text

Text in Neue Montreal Regular 12px, #000310, centered below the scroll bar to guide user interaction.

### Section Separator
**Role:** Visual divider

A thin (1-2px) solid black line (#000000) spanning the full width of the content area, visually segmenting content blocks. Uses the page's prominent border color to maintain stark definition.

## Do's and Don'ts

### Do
- Use Cream Vellum (#fffcf0) as the primary background for all content sections.
- Apply Terminal Black (#000000) for all primary text elements and interactive component outlines.
- Employ the LDD font at 135px for all major page headings and numerical counters to maintain the distinctive pixel aesthetic.
- Maintain generous spacing around all elements, utilizing the 200px marginRight to ensure ample negative space and minimal information density.
- Use Neue Montreal Regular 16px, color Deep Graphite (#000310) for main body copy and descriptive text for maximal readability against the primary background.

### Don't
- Avoid colored backgrounds or complex graphics; the design relies on stark contrast and minimalism.
- Do not introduce rounded corners; all elements should have hard, square edges unless it's a pixelated font.
- Do not use shadow effects; depth is created purely through stark outlines and negative space.
- Avoid using multiple weights or styles of the same font; the system is built on precision with specific type definitions.
- Do not deviate from the Cream Vellum and Terminal Black palette, except for the explicit Sky Blue Indicator for interactive states if necessary.

## Imagery

The site uses no photography or rich illustrations. Its visual language relies exclusively on typography, stark lines, and the distinctive pixelated LDD font to communicate. Icons, if present, would adhere to a simple, monochromatic, possibly pixelated style. The visual density is extremely low, with ample negative space. Visuals are not merely decorative but define the brand's core identity through textual and typographic presentation.

## Layout

The page uses a centered, max-width content model, with large sections clearly delineated by full-width black separator lines. The hero section features a large, centered pixelated headline. Content within sections is often centered, especially for introductory text. Navigation is a minimalist top bar with links aligned to the left and right. The overall rhythm is sparse and symmetrical, emphasizing clarity and strong visual breaks between content blocks. Scrolling features a unique horizontal progress bar, a distinct interactive element.

## Agent Prompt Guide

### Quick Color Reference
- Text: #000000
- Background: #fffcf0
- Primary Accent (implied interactive): #007aff
- Secondary Text/Subtle Border: #000310

### 3-5 Example Component Prompts
1.  **Create a main header:** Centered, in LDD Regular, size 135px, color Terminal Black (#000000). Text content: 'LORENZO DAL DOSSO'.
2.  **Generate a navigation element:** Left-aligned, text 'Menu' in Neue Montreal Regular, 12px, color Terminal Black (#000000). Background Cream Vellum (#fffcf0).
3.  **Design a scroll progress bar:** A thin horizontal line, 2px height. The filled portion should be Terminal Black (#000000) on a background bar with a Terminal Black (#000000) border and Cream Vellum (#fffcf0) fill. Below it, centered text 'Scroll' in Neue Montreal Regular, 12px, color Deep Graphite (#000310).
4.  **Create an introductory text block:** Centered within the page, text 'Hello. I’m Mister Wolf. I solve Problems. Yes I’m an IT Specialist.' in Neue Montreal Regular, 16px, color Deep Graphite (#000310).
5.  **Add a prominent numerical counter:** Right-aligned, in LDD Regular, size 135px, color Terminal Black (#000000). Text content: '04'.

## Similar Brands

- **Framer** — Features a stark, high-contrast interface with ample white space and strong typographic hierarchy, emphasizing clarity over visual flair.
- **Linear** — Employs a precise, minimalist UI with strong typographic definitions and a strict monochromatic palette, creating a tool-like aesthetic.
- **Early Apple Websites (circa 1990s)** — The pixelated font and high-contrast, sparse layout evoke a sophisticated, early digital interface feel without being overtly retro.
- **Command Line Interfaces (CLI)** — The text-dominant, black-on-light presentation and pixelated elements create an atmosphere reminiscent of powerful, direct user interfaces.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-cream-vellum: #fffcf0;
  --color-terminal-black: #000000;
  --color-deep-graphite: #000310;
  --color-sky-blue-indicator: #007aff;

  /* Typography — Font Families */
  --font-neue-montreal: 'Neue Montreal', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ldd: 'LDD', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1;
  --text-body: 16px;
  --leading-body: 1;
  --text-display: 135px;
  --leading-display: 1;

  /* Typography — Weights */
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-15: 15px;
  --spacing-30: 30px;
  --spacing-35: 35px;
  --spacing-58: 58px;
  --spacing-200: 200px;

  /* Layout */
  --section-gap: 48px;
  --element-gap: 15-35px;

  /* Named Radii */
  --radius-all: 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-cream-vellum: #fffcf0;
  --color-terminal-black: #000000;
  --color-deep-graphite: #000310;
  --color-sky-blue-indicator: #007aff;

  /* Typography */
  --font-neue-montreal: 'Neue Montreal', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ldd: 'LDD', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1;
  --text-body: 16px;
  --leading-body: 1;
  --text-display: 135px;
  --leading-display: 1;

  /* Spacing */
  --spacing-15: 15px;
  --spacing-30: 30px;
  --spacing-35: 35px;
  --spacing-58: 58px;
  --spacing-200: 200px;
}
```

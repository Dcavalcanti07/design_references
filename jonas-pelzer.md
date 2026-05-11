# Jonas Pelzer — Style Reference
> dot-matrix digital blueprint

**Theme:** light

Jonas Pelzer's design system evokes an industrial, dot-matrix digital aesthetic on a clean white canvas. Typography blends a monospaced display font with a classic serif for body text, creating a tech-forward yet grounded feel. Interactions are highlighted with a distinct violet, often in subtle outlines or transparent fills, suggesting responsive interfaces and active states without overwhelming the stark, high-contrast monochrome base. Surface treatments favor soft, rounded cards and ghost buttons, maintaining lightness across the layout.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card surfaces, ghost button backgrounds, active navigation text |
| Ink Black | `#000000` | `--color-ink-black` | Primary text, headings, body copy, list items, card text, general borders, button outlines |
| Ghost Gray | `#d4d6dd` | `--color-ghost-gray` | Subtle button borders, decorative strokes |
| Digital Violet | `#3502ff` | `--color-digital-violet` | Violet outline accent for tags, dividers, and focused UI edges. Do not promote it to the primary CTA color |
| Muted Lilac | `#d7ccff` | `--color-muted-lilac` | Violet accent for outlined action borders, linked labels, and lightweight interactive emphasis. Do not promote it to the primary CTA color |
| Action Grape | `#5d35ff` | `--color-action-grape` | Violet text accent for links, tags, and emphasized short phrases. Do not promote it to the primary CTA color |

## Tokens — Typography

### Scope — Display headings and navigation items — its monospaced, dot-matrix character is a signature choice, giving a distinct digital, architectural feel. This font defines the brand's machine-like precision. · `--font-scope`
- **Substitute:** IBM Plex Mono
- **Weights:** 400
- **Sizes:** 13px, 14px, 17px, 22px, 42px
- **Line height:** 1.00, 1.10, 1.20
- **Letter spacing:** 0.0200em at 13-14px, 0.0250em at 17-22px, 0.0360em at 42px
- **Role:** Display headings and navigation items — its monospaced, dot-matrix character is a signature choice, giving a distinct digital, architectural feel. This font defines the brand's machine-like precision.

### Signifier — Body copy, list items, and subheadings — its classic serif presence grounds the design, providing readability and a timeless counterpoint to the more rigid display font. Offers a sense of established authority. · `--font-signifier`
- **Substitute:** Playfair Display
- **Weights:** 400
- **Sizes:** 15px, 16px, 18px, 22px, 25px, 42px
- **Line height:** 1.00, 1.20
- **Letter spacing:** 0.0200em
- **Role:** Body copy, list items, and subheadings — its classic serif presence grounds the design, providing readability and a timeless counterpoint to the more rigid display font. Offers a sense of established authority.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 13px | 1.1 | 0.26px | `--text-caption` |
| body | 15px | 1.2 | 0.3px | `--text-body` |
| heading-sm | 22px | 1 | 0.55px | `--text-heading-sm` |
| heading | 25px | 1 | 0.5px | `--text-heading` |
| display | 42px | 1 | 1.512px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 40 | 40px | `--spacing-40` |
| 64 | 64px | `--spacing-64` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 12px |
| navbar | 8.26px |
| buttons | 12px |
| default | 12px |
| navbarItem | 3.5px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| sm | `rgba(53, 2, 255, 0.1) 0px 1px 4px 2px` | `--shadow-sm` |

### Layout

- **Section gap:** 64px
- **Card padding:** 14px
- **Element gap:** 5px

## Components

### Ghost Button
**Role:** Navigation and secondary actions

Transparent background with a subtle border in Ghost Gray (#d4d6dd). Text is Ink Black (#000000). Radius is 12px. Used for navigation elements and low-hierarchy actions, maintaining a minimal aesthetic.

### Outlined Violet Button
**Role:** Primary Call to Action

Transparent background, Muted Lilac (#d7ccff) border at 1px. Text is Action Grape (#5d35ff). Padding is 6px vertical, 14px horizontal. Radius is 12px. Visually distinct as the primary action through its chromatic outline and text color.

### Work Card
**Role:** Portfolio item container

Background in Muted Lilac (rgba(53, 2, 255, 0.1)), with a 12px border-radius. No box shadow. Used to subtly contain portfolio items, featuring a soft violet tint.

### Navigation Link (Active)
**Role:** Current page indicator

Background in Digital Violet (#3502ff), text in Canvas White (#ffffff). Radius is 3.5px for individual items, contained within a navbar with 8.26px radius. Creates a strong visual cue for the active state.

### Navigation Wrap
**Role:** Container for primary navigation

Background opacity of Canvas White (rgba(255, 255, 255, 0.3)), with a Digital Violet (rgba(53, 2, 255, 0.2)) border. Blur filter of 10px applied. Has a radius of 8.26px and a shadow rgba(53, 2, 255, 0.1) 0px 1px 4px 2px.

## Do's and Don'ts

### Do
- Prioritize Canvas White (#ffffff) for page backgrounds to maintain an open, clean aesthetic.
- Use Ink Black (#000000) for all primary text elements, ensuring high contrast and legibility.
- Apply Digital Violet (#3502ff) exclusively for active navigation states and decorative accents.
- Use the Scope typeface for all headings and navigation to leverage its distinctive digital character.
- Employ a 12px border-radius for all cards and buttons to ensure a consistent softened aesthetic.
- Utilize Muted Lilac (#d7ccff) for ghost button outlines and subtle card backgrounds.
- Maintain a compact elementGap of 5px to keep interactive elements closely related.

### Don't
- Do not use highly saturated colors for large background areas; maintain a light monochromatic base.
- Avoid heavy drop shadows; implement transparent shadows like rgba(53, 2, 255, 0.1) 0px 1px 4px 2px sparingly, only for elevated components like the navigation wrap.
- Do not use generic system fonts for headings; maintain the distinct visual identity provided by Scope.
- Do not apply excessive padding to cards or buttons; adhere to the compact 6px vertical, 14px horizontal button padding and 14px card padding.
- Do not introduce strong visual dividers between sections; rely on spacing and subtle background shifts to define content blocks.
- Avoid bold or heavy weights for any typeface; the design relies on the weight 400 of Scope and Signifier for consistent typography.
- Do not use solid fills for primary action buttons; always use the outlined Muted Lilac style.

## Elevation

- **Navigation Wrap:** `rgba(53, 2, 255, 0.1) 0px 1px 4px 2px`

## Agent Prompt Guide

### Quick Color Reference
Text: #000000
Background: #ffffff
Border: #000000
Accent: #3502ff
primary action: #d7ccff (outlined action border)

### 3-5 Example Component Prompts
1. Create a hero section: Canvas White background. Headline 'JONAS PELZER is a DESIGNER' using Scope, weight 400, size 42px, Ink Black, with 0.0360em letter-spacing. Subtext 'With 15+ years of professional experience...' using Signifier, weight 400, size 18px, Ink Black, 0.0200em letter-spacing.
2. Design an 'Outlined Violet Button': with Muted Lilac (#d7ccff) border, Action Grape (#5d35ff) text 'See more work' using Scope, weight 400, size 14px, 6px vertical padding, 14px horizontal padding, and 12px border-radius.
3. Implement a 'Work Card': Muted Lilac (rgba(53, 2, 255, 0.1)) background, 12px border-radius, no shadow, with 14px padding inside for content.
4. Build an 'Active Navigation Link': Digital Violet (#3502ff) background, Canvas White (#ffffff) text 'Work' using Scope, weight 400, size 17px, 6px vertical padding, 14px horizontal padding, and 3.5px border-radius.
5. Create a sticky 'Navigation Wrap': Canvas White (rgba(255, 255, 255, 0.3)) background, 8.26px border-radius, with a Digital Violet (rgba(53, 2, 255, 0.2)) border and a shadow of rgba(53, 2, 255, 0.1) 0px 1px 4px 2px, and a blur(10px) filter applied.

## Motion Philosophy

Motion interactions are controlled and expressive, with a preference for 'ease' timing functions. Durations mostly in the 0.2s to 0.8s range suggest noticeable but not distracting transitions. Common transformations like 'transform' indicate subtle shifts and movements to guide user attention without being overly flashy. The personality is expressive, hinting at delightful micro-interactions without sacrificing professionalism.

## Similar Brands

- **Figma** — Clean white backgrounds with accent colors defining interactive elements and a focus on UI typography.
- **Linear** — High contrast dark text on light backgrounds, with a specific accent color for interactions and a strong emphasis on typographic clarity.
- **Read.cv** — Minimalist aesthetic driven by typography and subtle accent colors on a largely achromatic canvas.
- **Stripe (early designs)** — A similar approach to using distinct, clear typography combined with a single saturated color to highlight key actions against a clean, white background.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ink-black: #000000;
  --color-ghost-gray: #d4d6dd;
  --color-digital-violet: #3502ff;
  --color-muted-lilac: #d7ccff;
  --color-action-grape: #5d35ff;

  /* Typography — Font Families */
  --font-scope: 'Scope', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-signifier: 'Signifier', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 1.1;
  --tracking-caption: 0.26px;
  --text-body: 15px;
  --leading-body: 1.2;
  --tracking-body: 0.3px;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1;
  --tracking-heading-sm: 0.55px;
  --text-heading: 25px;
  --leading-heading: 1;
  --tracking-heading: 0.5px;
  --text-display: 42px;
  --leading-display: 1;
  --tracking-display: 1.512px;

  /* Typography — Weights */
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-40: 40px;
  --spacing-64: 64px;

  /* Layout */
  --section-gap: 64px;
  --card-padding: 14px;
  --element-gap: 5px;

  /* Border Radius */
  --radius-md: 3.5px;
  --radius-lg: 8.26px;
  --radius-xl: 12px;

  /* Named Radii */
  --radius-cards: 12px;
  --radius-navbar: 8.26px;
  --radius-buttons: 12px;
  --radius-default: 12px;
  --radius-navbaritem: 3.5px;

  /* Shadows */
  --shadow-sm: rgba(53, 2, 255, 0.1) 0px 1px 4px 2px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ink-black: #000000;
  --color-ghost-gray: #d4d6dd;
  --color-digital-violet: #3502ff;
  --color-muted-lilac: #d7ccff;
  --color-action-grape: #5d35ff;

  /* Typography */
  --font-scope: 'Scope', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-signifier: 'Signifier', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 1.1;
  --tracking-caption: 0.26px;
  --text-body: 15px;
  --leading-body: 1.2;
  --tracking-body: 0.3px;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1;
  --tracking-heading-sm: 0.55px;
  --text-heading: 25px;
  --leading-heading: 1;
  --tracking-heading: 0.5px;
  --text-display: 42px;
  --leading-display: 1;
  --tracking-display: 1.512px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-40: 40px;
  --spacing-64: 64px;

  /* Border Radius */
  --radius-md: 3.5px;
  --radius-lg: 8.26px;
  --radius-xl: 12px;

  /* Shadows */
  --shadow-sm: rgba(53, 2, 255, 0.1) 0px 1px 4px 2px;
}
```

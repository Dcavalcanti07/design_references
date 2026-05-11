# Shelby Kay — Style Reference
> Earthy editorial grid

**Theme:** light

Shelby Kay's design system uses an earthy, modern-editorial aesthetic, combining a restrained palette of muted greens and beiges with stark, super-sized typography. The visual language emphasizes large negative space and a grid-like organization, creating an atmosphere of quiet confidence and refined utility. Color is primarily used for deep background contrast and subtle accentuation, allowing strong typographic forms to dominate the hierarchy. Components are minimal, relying on borders and text color variations rather than heavy fills or shadows.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas Parchment | `#efe6d9` | `--color-canvas-parchment` | Page backgrounds, large content areas, default surface. The primary light background that anchors the entire aesthetic |
| Ashwood Grove | `#393c2a` | `--color-ashwood-grove` | Primary text color, bold headings, borders for interactive elements. This deep, desaturated green acts as the dominant dark element |
| Forest Whisper | `#737955` | `--color-forest-whisper` | Muted headings, secondary text. Provides a softer contrast against the Canvas Parchment |
| Soft Sienna | `#d6b292` | `--color-soft-sienna` | Alternating section background, subtle warm tint |
| Dusty Rose | `#afa199` | `--color-dusty-rose` | Alternating section background, cool grey tint |
| Slate Mist | `#7b8785` | `--color-slate-mist` | Subtle background element, creates slight depth |
| Dark Bark | `#454931` | `--color-dark-bark` | Alternative dark text or background accent |
| Deep Mocha | `#2c1c03` | `--color-deep-mocha` | Deepest dark tone, used sparingly for strong contrast |

## Tokens — Typography

### Ranade — Headline typeface, used for hero branding and dominant page titles. Its custom letterforms and large scales create a strong, architectural impact. · `--font-ranade`
- **Substitute:** Anton
- **Weights:** 400, 700
- **Sizes:** 24px, 83px, 158px, 265px
- **Line height:** 0.90, 1.00, 1.20
- **Role:** Headline typeface, used for hero branding and dominant page titles. Its custom letterforms and large scales create a strong, architectural impact.

### Switzer — Body copy, navigation, and secondary headings. A modern sans-serif that provides clear readability and anchors the system's functional text. · `--font-switzer`
- **Substitute:** Inter
- **Weights:** 500, 600, 700
- **Sizes:** 10px, 11px, 14px, 16px, 20px
- **Line height:** 1.00, 1.20, 1.25, 1.30
- **Role:** Body copy, navigation, and secondary headings. A modern sans-serif that provides clear readability and anchors the system's functional text.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1 | — | `--text-caption` |
| body | 14px | 1.25 | — | `--text-body` |
| heading-sm | 20px | 1.2 | — | `--text-heading-sm` |
| heading | 24px | 1.2 | — | `--text-heading` |
| heading-lg | 83px | 0.9 | — | `--text-heading-lg` |
| display | 265px | 0.9 | — | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 8px

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 7 | 7px | `--spacing-7` |
| 8 | 8px | `--spacing-8` |
| 12 | 12px | `--spacing-12` |
| 20 | 20px | `--spacing-20` |
| 36 | 36px | `--spacing-36` |
| 40 | 40px | `--spacing-40` |
| 45 | 45px | `--spacing-45` |
| 56 | 56px | `--spacing-56` |

### Border Radius

| Element | Value |
|---------|-------|
| default | 0px |

### Layout

- **Section gap:** 36px
- **Card padding:** 20px
- **Element gap:** 12px

## Components

### Navigation Link
**Role:** Primary navigation item

Text in Switzer, size 14px, weight 500, Ashwood Grove color. On hover/active, a Ashwood Grove border appears along one edge (exact edge not specified, but visual implies bottom).

### Hero Title
**Role:** Main branding on the landing page

Ranade typeface, size up to 265px, Ashwood Grove color, with significant letter-spacing (implied by 'S h e l b y Ka y' spelling) and 0.90 line-height.

### Text Block Container
**Role:** Grouped text content

Padded implicitly by 20px on multiple sides. Text uses Switzer, Ashwood Grove for primary, Forest Whisper for secondary.

### Work Showcase Card
**Role:** Thumbnail for portfolio projects

Features a border in Ashwood Grove when interactive, and a text overlay for project identifier. Implied padding of 7px on some edges for content.

### Section Separator Rule
**Role:** Visual division between content sections

A very subtle border, likely 1px, in Ashwood Grove or a slightly lighter neutral defined by the context.

### Footer/Copyright Text
**Role:** Small print information

Switzer, size 14px (or smaller), Ashwood Grove color.

## Do's and Don'ts

### Do
- Prioritize Canvas Parchment (#efe6d9) as the base background for most content, establishing a light, airy canvas.
- Use Ashwood Grove (#393c2a) as the primary text color for all main body content and bold headings to ensure strong contrast and consistency.
- Headlines, especially hero elements, should leverage the Ranade typeface at extremely large scales (158px or 265px) with a 0.90 line-height to create visual drama.
- Maintain a sense of generous whitespace; use a sectionGap of 36px and elementGap of 12px to keep content uncongested.
- When introducing color accents, use Forest Whisper (#737955) for muted headings or secondary text, providing a soft contrast.
- Design interactive elements (like navigation links) by outlining with Ashwood Grove (#393c2a) rather than filling, maintaining a lightweight feel.
- Employ `normal` letter-spacing for both Ranade and Switzer typefaces by default, avoiding tight tracking even at large sizes.

### Don't
- Avoid heavy shadows or gradients on interactive elements; rely on border color and text changes for states.
- Do not introduce strong, saturated colors that deviate from the muted greens and beige-grays, as they will clash with the established palette.
- Avoid small text sizes for body copy; the smallest legible body text should be Switzer 14px.
- Do not use highly contrasting or vibrant imagery; content images should be muted or monochromatic to fit the overall subdued tone.
- Avoid highly decorative or script typefaces; stick to the clean, modern aesthetic of Switzer and abstract forms of Ranade.
- Do not apply rounded corners to elements; maintain sharp, crisp edges throughout the design system.
- Do not use dark backgrounds for entire pages; the design system is firmly rooted in a light theme with varying neutral surface tones.

## Agent Prompt Guide

Quick Color Reference:
text: #393c2a
background: #efe6d9
border: #393c2a
accent: #737955
primary action: no distinct CTA color

Example Component Prompts:
1. Create a hero section with a Canvas Parchment background (#efe6d9). The main title 'S h e l b y' should use Ranade, 265px, line-height 0.90, color Ashwood Grove (#393c2a). Below it, add body text 'Freelance Front-End Developer' in Switzer, 16px, line-height 1.20, Ashwood Grove (#393c2a).
2. Design a navigation link for 'Work'. Text should be Switzer, 14px, weight 500, color Ashwood Grove (#393c2a). On hover, add a 1px bottom border in Ashwood Grove (#393c2a).
3. Create a portfolio item thumbnail. The image should be a square, no radius. Below the image, include 'INT #04–04' as a link using Switzer, 14px, weight 500, color Ashwood Grove (#393c2a). Encapsulate this within an interactive element that shows a 1px border of Ashwood Grove (#393c2a) on hover/focus.

## Similar Brands

- **Aline.io** — Shares a similar muted color palette with dominant greens and beiges, combined with a strong focus on minimalist typography and generous whitespace.
- **Made by Folk** — Exhibits a clean editorial layout, large text elements, and a restrained color palette that prioritizes content and typography over vibrant graphics, though theirs is often darker.
- **Studio—JQ** — Utilizes oversized, impactful typography and a strong grid-based structure with a focus on visual hierarchy and high-quality, often desaturated, imagery.
- **Garden Studio** — Employs an earthy, muted color scheme and a clean, spacious layout, often with large typographic elements as focal points, creating a sophisticated yet down-to-earth feel.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-parchment: #efe6d9;
  --color-ashwood-grove: #393c2a;
  --color-forest-whisper: #737955;
  --color-soft-sienna: #d6b292;
  --color-dusty-rose: #afa199;
  --color-slate-mist: #7b8785;
  --color-dark-bark: #454931;
  --color-deep-mocha: #2c1c03;

  /* Typography — Font Families */
  --font-ranade: 'Ranade', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-switzer: 'Switzer', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1;
  --text-body: 14px;
  --leading-body: 1.25;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.2;
  --text-heading: 24px;
  --leading-heading: 1.2;
  --text-heading-lg: 83px;
  --leading-heading-lg: 0.9;
  --text-display: 265px;
  --leading-display: 0.9;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-20: 20px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-45: 45px;
  --spacing-56: 56px;

  /* Layout */
  --section-gap: 36px;
  --card-padding: 20px;
  --element-gap: 12px;

  /* Named Radii */
  --radius-default: 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-parchment: #efe6d9;
  --color-ashwood-grove: #393c2a;
  --color-forest-whisper: #737955;
  --color-soft-sienna: #d6b292;
  --color-dusty-rose: #afa199;
  --color-slate-mist: #7b8785;
  --color-dark-bark: #454931;
  --color-deep-mocha: #2c1c03;

  /* Typography */
  --font-ranade: 'Ranade', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-switzer: 'Switzer', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1;
  --text-body: 14px;
  --leading-body: 1.25;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.2;
  --text-heading: 24px;
  --leading-heading: 1.2;
  --text-heading-lg: 83px;
  --leading-heading-lg: 0.9;
  --text-display: 265px;
  --leading-display: 0.9;

  /* Spacing */
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-20: 20px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-45: 45px;
  --spacing-56: 56px;
}
```

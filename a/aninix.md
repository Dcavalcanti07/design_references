# Aninix — Style Reference
> Crisp Utility Canvas

**Theme:** light

Aninix presents an airy, contemporary aesthetic for a productivity tool, characterized by a predominantly achromatic canvas that highlights focused typographic elements. The interface uses rounded card surfaces and ghost-like interactive controls, with a single vivid violet accent color providing functional punctuation for key actions and branding. Typography is sharp and compact, ensuring information density without visual clutter, while subtle shadows offer a sense of lightweight elevation rather than heavy layering.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, elevated card surfaces, body text on dark backgrounds |
| Midnight Text | `#0b1118` | `--color-midnight-text` | Primary heading and body text, ensuring high contrast on light backgrounds |
| Charcoal Text | `#171717` | `--color-charcoal-text` | Secondary heading text, slightly softer than Midnight Text for varied hierarchy |
| Ink Grey | `#333333` | `--color-ink-grey` | Tertiary text, used for less prominent content and subtle branding |
| Figma Grey | `#f0f0f0` | `--color-figma-grey` | Background for secondary content blocks and cards on the main canvas |
| Muted Slate | `#5c6574` | `--color-muted-slate` | Supportive body text, descriptive labels, and softer visual strokes |
| Ghost Shadow | `#ced3d9` | `--color-ghost-shadow` | Subtle border and shadow accents, contributing to a lightweight visual feel |
| Dusty Blue | `#c4d2db` | `--color-dusty-blue` | Decorative highlights and very soft shadows, creating a gentle separation |
| Subtle Grey | `#89909a` | `--color-subtle-grey` | Secondary link text and very muted decorative elements |
| Action Violet | `#374fd5` | `--color-action-violet` | Primary actionable elements like button backgrounds, branded links, and active states |

## Tokens — Typography

### sans-serif — Utility text, small labels, and iconography labels. This compact font reinforces the minimal aesthetic. · `--font-sans-serif`
- **Substitute:** Arial, Helvetica, sans-serif
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.20
- **Role:** Utility text, small labels, and iconography labels. This compact font reinforces the minimal aesthetic.

### system-ui — General body text and navigation links, providing strong readability and a modern feel. · `--font-system-ui`
- **Substitute:** Segoe UI, Roboto, Ubuntu, Cantarell, Noto Sans, sans-serif
- **Weights:** 400, 500, 700, 800
- **Sizes:** 16px, 18px
- **Line height:** 1.44
- **Role:** General body text and navigation links, providing strong readability and a modern feel.

### P22 Mackinac Pro Medium — Specialized body text with italic variants, often used for quotes or emphasized content. · `--font-p22-mackinac-pro-medium`
- **Substitute:** Georgia, serif
- **Weights:** 400
- **Sizes:** 20px
- **Line height:** 1.40
- **Role:** Specialized body text with italic variants, often used for quotes or emphasized content.

### P22 Mackinac Pro Medium — Introductions and prominent body text sections, offering a slightly more formal touch with its serif appearance. · `--font-p22-mackinac-pro-medium`
- **Substitute:** Georgia, serif
- **Weights:** 400
- **Sizes:** 20px
- **Line height:** 1.40
- **Role:** Introductions and prominent body text sections, offering a slightly more formal touch with its serif appearance.

### Euclid Circular A — Headlines and prominent marketing taglines where a bold, subtly tracked, modern sans-serif is desired to convey impact. · `--font-euclid-circular-a`
- **Substitute:** Panton, Montserrat, sans-serif
- **Weights:** 400
- **Sizes:** 18px, 20px
- **Line height:** 1.20, 1.30
- **Letter spacing:** -0.0100em
- **Role:** Headlines and prominent marketing taglines where a bold, subtly tracked, modern sans-serif is desired to convey impact.

### P22 Mackinac Pro Medium Italic — P22 Mackinac Pro Medium Italic — detected in extracted data but not described by AI · `--font-p22-mackinac-pro-medium-italic`
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.5
- **Role:** P22 Mackinac Pro Medium Italic — detected in extracted data but not described by AI

## Tokens — Spacing & Shapes

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 8 | 8px | `--spacing-8` |
| 10 | 10px | `--spacing-10` |
| 12 | 12px | `--spacing-12` |
| 13 | 13px | `--spacing-13` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 28 | 28px | `--spacing-28` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 80 | 80px | `--spacing-80` |
| 120 | 120px | `--spacing-120` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 16px |
| buttons | 8px |
| largeCards | 24px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| sm | `rgba(104, 116, 123, 0.15) 0px 2px 7px 0px, rgba(104, 116,...` | `--shadow-sm` |

### Layout

- **Section gap:** 40px
- **Card padding:** 40px
- **Element gap:** 10px

## Components

### Ghost Primary Button
**Role:** Main call to action for the plugin installation.

Background: Canvas White (#ffffff). Text color: default browser link blue (not specified). Border: 1px solid default browser link blue. Radius: 10px. Padding: 10px vertical, 24px horizontal. Shadow: rgba(104, 116, 123, 0.15) 0px 2px 7px 0px, rgba(104, 116, 123, 0.3) 0px 5px 15px 0px.

### Feature Content Card
**Role:** Displaying individual features or content blocks.

Background: Figma Grey (#f0f0f0). Radius: 16px. No shadow. No internal padding.

### Elevated Content Card
**Role:** Prominent content card, often used for testimonials or key information.

Background: Canvas White (#ffffff). Radius: 24px. No shadow. Padding: 40px on all sides.

### Branded Label
**Role:** Small, distinct labels with brand recognition.

Background: Action Violet (#374fd5). Text color: Canvas White (#ffffff). Radius: 8px. Padding: 4px vertical, 8px horizontal. Uses sans-serif 12px.

## Do's and Don'ts

### Do
- Prioritize Canvas White (#ffffff) as the dominant background for body content and primary surfaces.
- Use Action Violet (#374fd5) exclusively for primary interactive elements, active states, and small brand accents.
- Apply a 16px border-radius to content cards for a universally soft and approachable appearance.
- Maintain a compact information layout by generally using 10px for element spacing and 40px for section gaps.
- Employ Euclid Circular A with -0.0100em letter-spacing for all headlines to ensure a sharp, modern feel.
- Restrict elevation effects to ghost buttons, using rgba(104, 116, 123, 0.15) 0px 2px 7px 0px, rgba(104, 116, 123, 0.3) 0px 5px 15px 0px, to visually highlight interaction points without heavy layering.
- Use Midnight Text (#0b1118) and Charcoal Text (#171717) for main headings and body copy on light backgrounds.

### Don't
- Avoid introducing additional saturated colors unless explicitly assigned a functional role (e.g., semantic states) to preserve the brand's minimalist color scheme.
- Do not use heavy, opaque shadows; stick to the subtle, diffused ghost button shadow for all elevated elements, or no shadow at all.
- Refrain from altering the letter-spacing of sans-serif and system-ui fonts, as their `normal` tracking contributes to readability.
- Do not break the established 8px, 16px, and 24px border radius pattern across components; consistency is key to the system's soft aesthetic.
- Avoid using multiple accent colors; rely on Action Violet (#374fd5) as the sole chromatic element.
- Do not use dark backgrounds for major content sections; maintain the light theme with Canvas White and Figma Grey.

## Elevation

- **Ghost Primary Button:** `rgba(104, 116, 123, 0.15) 0px 2px 7px 0px, rgba(104, 116, 123, 0.3) 0px 5px 15px 0px`

## Imagery

The site predominantly uses product screenshots and abstract, colorful Figma plugin-like illustrations. Photography is scarce and, when present, is tightly cropped and serves as background texture within content cards, maintaining a focused, functional aesthetic rather than a lifestyle one. Icons are minimal, featuring a clean outlined style for navigation, with a filled variant for the brand logo. Imagery generally serves to explain features and showcase the product in action, rather than for decorative atmosphere.

## Layout

The page uses a maximum-width contained layout rather than full-bleed, with content centered. The hero section features a large, centered headline and subheading, followed by a call-to-action button, all stacked vertically. Subsequent sections employ a mixed grid approach: a dominant card grid (likely 2-3 columns on wider screens) for features, and alternating text-left/image-right or text-right/image-left content blocks. Vertical rhythm is established by consistent spacing between sections, primarily 40px gaps. Navigation is a sticky top bar with left-aligned brand logo and right-aligned links and actions.

## Agent Prompt Guide

Quick Color Reference:
text: #0b1118
background: #ffffff
border: #ced3d9
accent: #374fd5
primary action: no distinct CTA color

Example Component Prompts:
No distinct primary action color was observed; use the extracted neutral button treatments instead of inventing a filled CTA color.
2. Design a `Feature Content Card` with a `Figma Grey` background (#f0f0f0), 16px border-radius, and no internal padding for an image.
3. Implement an `Elevated Content Card` using `Canvas White` (#ffffff), 24px border-radius, and 40px internal padding on all sides, suitable for a testimonial block.
4. Produce a `Branded Label` displaying 'by Aninix', using `Action Violet` (#374fd5) background, `Canvas White` (#ffffff) text, 8px border-radius, and 4px vertical, 8px horizontal padding, with sans-serif 12px type.

## Similar Brands

- **Framer** — Clean, predominantly monochrome UI with a single, vibrant accent color for interaction and a focus on sleek typography.
- **Linear** — Minimalist interface, heavy textual focus with crisp, precise typography, and very subtle use of color for functional elements.
- **Superhuman** — High-contrast text on light backgrounds, compact UI elements, and a strong emphasis on speed and utility in its visual language.
- **Vercel** — Modern developer tool aesthetic relying on systematic spacing, a limited color palette that emphasizes content, and rounded UI elements.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-midnight-text: #0b1118;
  --color-charcoal-text: #171717;
  --color-ink-grey: #333333;
  --color-figma-grey: #f0f0f0;
  --color-muted-slate: #5c6574;
  --color-ghost-shadow: #ced3d9;
  --color-dusty-blue: #c4d2db;
  --color-subtle-grey: #89909a;
  --color-action-violet: #374fd5;

  /* Typography — Font Families */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-system-ui: 'system-ui', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-p22-mackinac-pro-medium: 'P22 Mackinac Pro Medium', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-euclid-circular-a: 'Euclid Circular A', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-p22-mackinac-pro-medium-italic: 'P22 Mackinac Pro Medium Italic', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-xs: 12px;
  --leading-xs: 1.2;
  --text-base: 16px;
  --leading-base: 1.44;
  --text-lg: 18px;
  --leading-lg: 1.3;
  --text-xl: 20px;
  --leading-xl: 1.2;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-bold: 700;
  --font-weight-extrabold: 800;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-13: 13px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-80: 80px;
  --spacing-120: 120px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 40px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;

  /* Named Radii */
  --radius-cards: 16px;
  --radius-buttons: 8px;
  --radius-largecards: 24px;

  /* Shadows */
  --shadow-sm: rgba(104, 116, 123, 0.15) 0px 2px 7px 0px, rgba(104, 116, 123, 0.3) 0px 5px 15px 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-midnight-text: #0b1118;
  --color-charcoal-text: #171717;
  --color-ink-grey: #333333;
  --color-figma-grey: #f0f0f0;
  --color-muted-slate: #5c6574;
  --color-ghost-shadow: #ced3d9;
  --color-dusty-blue: #c4d2db;
  --color-subtle-grey: #89909a;
  --color-action-violet: #374fd5;

  /* Typography */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-system-ui: 'system-ui', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-p22-mackinac-pro-medium: 'P22 Mackinac Pro Medium', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-euclid-circular-a: 'Euclid Circular A', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-p22-mackinac-pro-medium-italic: 'P22 Mackinac Pro Medium Italic', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-xs: 12px;
  --leading-xs: 1.2;
  --text-base: 16px;
  --leading-base: 1.44;
  --text-lg: 18px;
  --leading-lg: 1.3;
  --text-xl: 20px;
  --leading-xl: 1.2;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-13: 13px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-80: 80px;
  --spacing-120: 120px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;

  /* Shadows */
  --shadow-sm: rgba(104, 116, 123, 0.15) 0px 2px 7px 0px, rgba(104, 116, 123, 0.3) 0px 5px 15px 0px;
}
```

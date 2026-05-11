# Syllabus — Style Reference
> digital blueprint on cream paper

**Theme:** light

Syllabus presents a digital blueprint aesthetic: an organizational, content-focused UI built on a clean off-white canvas. Primary elements are rendered in a deep, muted violet, providing gravitas, while a secondary muted teal anchors larger content blocks. Accentuated by a soft yellow, the system ensures clarity and a sense of measured structure, with a focus on hierarchy and containment.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas Cream | `#fffcf7` | `--color-canvas-cream` | Hairline borders, dividers, input outlines, and card edges on light surfaces. Do not promote it to the primary CTA color |
| Inkwell Violet | `#0d0129` | `--color-inkwell-violet` | Primary text, headings, strong borders, icon fills, outlined button borders — defines key typographical and structural elements with depth |
| Teal Basin | `#19615c` | `--color-teal-basin` | Teal outline accent for tags, dividers, and focused UI edges. Do not promote it to the primary CTA color |
| Glow Yellow | `#fae59b` | `--color-glow-yellow` | Highlight accents, subtle background fills for focused areas, decorative illustrations — used sparingly to bring attention to specific UI elements |
| Pitch Black | `#000000` | `--color-pitch-black` | Strongest borders, subtle shadow effects, icon fills – used for outline details where maximum contrast is needed |
| Pure White | `#ffffff` | `--color-pure-white` | Elevated surfaces, card backgrounds, overlay elements, text on dark backgrounds |

## Tokens — Typography

### Roobert — Primary font for all headings, body text, and interactive elements. Its consistent tracking across sizes helps maintain a structured, readable experience. · `--font-roobert`
- **Substitute:** system-ui
- **Weights:** 400, 700
- **Sizes:** 16px, 20px, 24px, 40px, 48px, 56px, 64px
- **Line height:** 1.25, 1.27, 1.40, 1.60, 1.67, 2.00
- **Letter spacing:** normal
- **Role:** Primary font for all headings, body text, and interactive elements. Its consistent tracking across sizes helps maintain a structured, readable experience.

### Supply — Secondary font for specific content highlighting. Used sparingly for distinct textual emphasis, often in supporting roles. · `--font-supply`
- **Substitute:** monospace
- **Weights:** 400
- **Sizes:** 20px
- **Line height:** 1.60
- **Letter spacing:** normal
- **Role:** Secondary font for specific content highlighting. Used sparingly for distinct textual emphasis, often in supporting roles.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body-sm | 16px | 1.6 | — | `--text-body-sm` |
| body | 20px | 1.6 | — | `--text-body` |
| subheading | 24px | 1.4 | — | `--text-subheading` |
| heading-sm | 40px | 1.25 | — | `--text-heading-sm` |
| heading | 48px | 1.25 | — | `--text-heading` |
| heading-lg | 56px | 1.27 | — | `--text-heading-lg` |
| display | 64px | 1.25 | — | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 8px

**Density:** spacious

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 16 | 16px | `--spacing-16` |
| 24 | 24px | `--spacing-24` |
| 40 | 40px | `--spacing-40` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 104 | 104px | `--spacing-104` |
| 120 | 120px | `--spacing-120` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 0px |
| buttons | 0px |
| default | 0px |
| waitlistButton | 4px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgb(0, 0, 0) 1px 1px 3px 0px` | `--shadow-subtle` |

### Layout

- **Page max-width:** 1280px
- **Section gap:** 40px
- **Card padding:** 20px
- **Element gap:** 24px

## Components

### Primary Navigation
**Role:** The main menu for site navigation.

Text links in Inkwell Violet (#0d0129) at Roobert 16px weight 400. Contains a 'Join Waitlist' button with Inkwell Violet (#0d0129) background, Pure White (#ffffff) text, and 0px border-radius, along with an outlined 'Request a Demo' link.

### Hero Headline
**Role:** Dominant text for the main page introduction.

Roobert font at 64px, weight 700, Inkwell Violet (#0d0129) against a Canvas Cream (#fffcf7) background. Emphasizes bold statements with minimal styling beyond text.

### Ghost Waitlist Button
**Role:** A primary call to action, outlined, for joining a waitlist.

Text 'Join Waitlist' in Supply 20px weight 400, Inkwell Violet (#0d0129). Has a 1px border in Inkwell Violet (#0d0129) and a Glow Yellow (#fae59b) background. Padding is 12px vertical and 24px horizontal. Corner radius is 4px.

### Section Title
**Role:** Headline for major content sections, within a distinct background.

Roobert 48px, weight 700, Pure White (#ffffff) text on a Teal Basin (#19615c) background. It uses a custom shape for the background.

### Callout Block
**Role:** Highlights key problems or solutions.

Content block with a Teal Basin (#19615c) background. Features Pure White (#ffffff) text, Roobert font, with variations in size (e.g., 40px for prominent statements, 20px for detailed explanations).

### Default Text Link
**Role:** Standard interactive text.

Uses Inkwell Violet (#0d0129) for the text, Roobert font, 16px weight 400. No underline by default.

## Do's and Don'ts

### Do
- Always use Canvas Cream (#fffcf7) as the primary page background color for clean, focused content.
- Apply Inkwell Violet (#0d0129) to all primary text, headings, and significant border elements to ensure strong visual presence.
- Utilize Teal Basin (#19615c) for visually distinct content sections to create clear thematic breaks.
- Reserve Glow Yellow (#fae59b) for subtle, functional highlights or decorative elements within illustrations to draw attention without overwhelming.
- Set the site's maximum content width to 1280px, maintaining a consistent centered layout.
- Ensure all primary headings and buttons use the Roobert font with a strong weight (700 for headings, 400 for button text) for clarity and brand consistency.
- Maintain a clear visual hierarchy by pairing Inkwell Violet text (#0d0129) on Canvas Cream backgrounds (#fffcf7), or Pure White text (#ffffff) on Teal Basin backgrounds (#19615c).

### Don't
- Avoid using highly saturated colors for large background areas; stick to Canvas Cream (#fffcf7) and Teal Basin (#19615c).
- Do not introduce new border radii; all corner radii should be 0px, except for the 'Join Waitlist' button which uses 4px.
- Do not deviate from the specified font families; limit typography to Roobert and Supply.
- Avoid excessive use of shadows; subtle box shadows (rgb(0, 0, 0) 1px 1px 3px 0px) are present but not a primary elevation mechanism.
- Do not use generic blue for links; all links should use Inkwell Violet (#0d0129) for consistency.
- Do not use multiple font weights for body text; Roobert weight 400 should be sufficient.
- Do not use arbitrary spacing; adhere to the 8px base unit with recognized intervals (12px, 16px, 20px, 24px, 40px, 64px, 80px, 104px, 120px) for layout elements.

## Elevation

- **Card / Subtle Overlay:** `rgb(0, 0, 0) 1px 1px 3px 0px`

## Agent Prompt Guide

Quick Color Reference:
- text: #0d0129
- background: #fffcf7
- border: #0d0129
- accent: #fae59b
- primary action: #0d0129 (outlined action border)

Example Component Prompts:
1. Create a hero section with a bold Inkwell Violet (#0d0129) headline (Roobert 64px, weight 700) on a Canvas Cream (#fffcf7) background. Include a ghost button for 'Join Waitlist' with Inkwell Violet (#0d0129) text in Supply 20px weight 400, a 1px Inkwell Violet (#0d0129) border, Glow Yellow (#fae59b) background, 12px vertical and 24px horizontal padding, and a 4px corner radius.
2. Design a Callout Block with a Teal Basin (#19615c) background. Use a Roobert 40px weight 700 Pure White (#ffffff) headline and supporting text in Roobert 20px weight 400 Pure White (#ffffff). Add 40px padding top/bottom.
3. Create a navigation bar with a Pure White (#ffffff) background. Include a 'Log In' link using Inkwell Violet (#0d0129) text (Roobert 16px, weight 400) and a solid 'Join Waitlist' button with Inkwell Violet (#0d0129) fill, Pure White (#ffffff) text (Roobert 16px, weight 400), and 0px border-radius, 12px vertical and 24px horizontal padding.

## Similar Brands

- **Linear** — Shares a concise, highly structured UI with a focus on deep, muted primary colors and clear typography on light backgrounds.
- **Vercel** — Utilizes a clean, developer-tool aesthetic with strong typography, a light canvas, and strategic use of a single-to-few impactful brand colors for action and emphasis.
- **Notion** — Employs an off-white canvas with deep, contrasting text and minimal decorative elements, prioritizing content and functional UI over heavy styling.
- **Replit** — Features a light, functional interface with carefully chosen accent colors and strong, readable sans-serif typography, similar to development-focused tools.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-cream: #fffcf7;
  --color-inkwell-violet: #0d0129;
  --color-teal-basin: #19615c;
  --color-glow-yellow: #fae59b;
  --color-pitch-black: #000000;
  --color-pure-white: #ffffff;

  /* Typography — Font Families */
  --font-roobert: 'Roobert', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-supply: 'Supply', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-sm: 16px;
  --leading-body-sm: 1.6;
  --text-body: 20px;
  --leading-body: 1.6;
  --text-subheading: 24px;
  --leading-subheading: 1.4;
  --text-heading-sm: 40px;
  --leading-heading-sm: 1.25;
  --text-heading: 48px;
  --leading-heading: 1.25;
  --text-heading-lg: 56px;
  --leading-heading-lg: 1.27;
  --text-display: 64px;
  --leading-display: 1.25;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-40: 40px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-104: 104px;
  --spacing-120: 120px;

  /* Layout */
  --page-max-width: 1280px;
  --section-gap: 40px;
  --card-padding: 20px;
  --element-gap: 24px;

  /* Named Radii */
  --radius-cards: 0px;
  --radius-buttons: 0px;
  --radius-default: 0px;
  --radius-waitlistbutton: 4px;

  /* Shadows */
  --shadow-subtle: rgb(0, 0, 0) 1px 1px 3px 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-cream: #fffcf7;
  --color-inkwell-violet: #0d0129;
  --color-teal-basin: #19615c;
  --color-glow-yellow: #fae59b;
  --color-pitch-black: #000000;
  --color-pure-white: #ffffff;

  /* Typography */
  --font-roobert: 'Roobert', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-supply: 'Supply', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-sm: 16px;
  --leading-body-sm: 1.6;
  --text-body: 20px;
  --leading-body: 1.6;
  --text-subheading: 24px;
  --leading-subheading: 1.4;
  --text-heading-sm: 40px;
  --leading-heading-sm: 1.25;
  --text-heading: 48px;
  --leading-heading: 1.25;
  --text-heading-lg: 56px;
  --leading-heading-lg: 1.27;
  --text-display: 64px;
  --leading-display: 1.25;

  /* Spacing */
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-40: 40px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-104: 104px;
  --spacing-120: 120px;

  /* Shadows */
  --shadow-subtle: rgb(0, 0, 0) 1px 1px 3px 0px;
}
```

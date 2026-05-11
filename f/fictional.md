# Fictional — Style Reference
> Whimsical Sticker Bomb

**Theme:** light

The Fictional design system embodies a playful and energetic aesthetic, reminiscent of a vibrant children's book. It leverages a lively palette of saturated brand colors against a warm, neutral background. Typography is central to the visual identity, using a custom font that radiates personality. Components feature rounded, often irregular shapes, minimal shadows, and bold color accents, creating an approachable and whimsical user experience.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas Almond | `#ffe9ce` | `--color-canvas-almond` | Main page background — a warm, inviting canvas for playful elements |
| Paper White | `#ffffff` | `--color-paper-white` | Card surfaces, speech bubbles, primary text on dark backgrounds, ghost button borders |
| Type Black | `#000000` | `--color-type-black` | Primary text, prominent headings, strong outlines, and decorative fills |
| Grape Punch | `#8a53ff` | `--color-grape-punch` | Card backgrounds, section separators, bringing a playful and energetic accent |
| Bubblegum Red | `#fd4b38` | `--color-bubblegum-red` | Spot illustrations, card backgrounds, accentuating elements with vibrant energy |
| Sunshine Yellow | `#ffd80c` | `--color-sunshine-yellow` | Card backgrounds, decorative fills, button hover states, expressing cheerfulness |
| Leafy Green | `#3ccb09` | `--color-leafy-green` | Card backgrounds, small highlight elements, used sparingly for a fresh pop |
| Deep Indigo | `#0500a3` | `--color-deep-indigo` | Decorative text outlines and accent strokes, providing depth without heaviness |
| Ash Gray | `#666666` | `--color-ash-gray` | Secondary text, link borders, subtler interface elements |
| Light Gray | `#dddddd` | `--color-light-gray` | Muted button backgrounds and subtle dividers |
| Input Gray | `#101010` | `--color-input-gray` | Input text and borders |

## Tokens — Typography

### Fictional — The primary and only typeface, designed to be quirky and highly expressive. Its wide range of sizes and single weight imply a focus on visual impact over traditional typographic hierarchy, with stylistic alternates for a custom feel. · `--font-fictional`
- **Substitute:** Comic Sans MS
- **Weights:** 400
- **Sizes:** 16px, 22px, 29px, 36px, 37px, 40px, 43px, 48px, 50px, 72px, 115px, 202px, 346px
- **Line height:** 0.90, 1.00, 1.10, 1.20, 1.30, 1.40, 1.67, 1.71, 1.88
- **Letter spacing:** 0.0120em
- **OpenType features:** `"ss01" on, "dlig"`
- **Role:** The primary and only typeface, designed to be quirky and highly expressive. Its wide range of sizes and single weight imply a focus on visual impact over traditional typographic hierarchy, with stylistic alternates for a custom feel.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body-sm | 16px | 1.71 | — | `--text-body-sm` |
| body | 22px | 1.4 | — | `--text-body` |
| subheading | 29px | 1.3 | — | `--text-subheading` |
| heading-sm | 36px | 1.2 | — | `--text-heading-sm` |
| heading | 48px | 1.2 | — | `--text-heading` |
| heading-lg | 72px | 1.1 | — | `--text-heading-lg` |
| display | 346px | 0.9 | — | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 6px

**Density:** spacious

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 12 | 12px | `--spacing-12` |
| 24 | 24px | `--spacing-24` |
| 30 | 30px | `--spacing-30` |
| 60 | 60px | `--spacing-60` |
| 108 | 108px | `--spacing-108` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 15px |
| buttons | 5px |
| speechBubbles | 144px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgb(251, 215, 12) 0px 0px 0px 2px` | `--shadow-subtle` |

### Layout

- **Section gap:** 30px
- **Card padding:** 29px
- **Element gap:** 12px

## Components

### Ghost Button
**Role:** Interactive elements with minimal visual footprint, relying on text and soft borders.

Transparent background, Paper White text, Paper White 5px rounded border. No padding specified, implying text-only. Used for navigation and internal links.

### Speech Bubble Card
**Role:** Informative elements or callouts, designed with a hand-drawn, cartoonish feel.

Paper White background, with an exaggerated 144px border-radius, giving it a speech bubble shape. Internal padding of 28.8px vertical and 43.2px horizontal. No shadow.

### Colorful Round Card
**Role:** Highlighting key features or interactive elements, often with vivid colors.

Features a 100% border-radius for a perfect circle shape, with color fills like Grape Punch, Leafy Green. Padding is often asymmetrical or zero depending on content. No shadow.

### Accent Filled Button
**Role:** Secondary action buttons or tags, visually distinct from ghost buttons.

Light Gray background, Type Black text, 15px border-radius for moderately rounded corners. No padding specified, implying text-only. Used for labels like 'T'.

### Interactive Input
**Role:** Basic text input field allowing user data entry.

Transparent background, Input Gray text, Input Gray 0px border. No padding specified. A simple, unobtrusive input style.

### Quirky Card
**Role:** Containers for content, using a variety of vibrant brand colors with a consistent rounded edge.

Backgrounds in Grape Punch, Sunshine Yellow, Bullet Red, Leafy Green. Features a 15px border-radius. Internal padding of 8px on all sides. No shadow.

### Callout Label (Red)
**Role:** Small, urgent, or promotional tags, drawing immediate attention.

Bubblegum Red background with Paper White text. Rectangular with 15px border-radius. Used for 'GET IT HERE' or 'FREE TRIAL AVAILABLE'.

## Do's and Don'ts

### Do
- Always use the Fictional typeface for all text elements to maintain brand personality.
- Utilize Canvas Almond (#ffe9ce) as the primary page background color for a warm, inviting foundation.
- Apply a 15px border-radius for general cards and rectangular accent elements, reserving 5px for smaller buttons and 144px for speech bubble shapes.
- Employ Type Black (#000000) for all primary text content to ensure high contrast against light backgrounds.
- Incorporate vibrant accent colors like Grape Punch (#8a53ff), Sunshine Yellow (#ffd80c), and Bubblegum Red (#fd4b38) for card backgrounds and highlight elements to create visual energy and playfulness.
- Space elements using multiples of the 6px base unit, with a preference for `elementGap` of 12px for tight clusters and `cardPadding` of 29px for content blocks.
- Use ghost buttons with Paper White text and borders for navigation and secondary actions to maintain a light, non-obtrusive interface.

### Don't
- Avoid using traditional box-shadows; instead, rely on vibrant background colors and irregular shapes for element definition.
- Do not introduce additional font families; the Fictional typeface is the sole typographic voice of the brand.
- Refrain from using heavily structured grid layouts; allow elements to be positioned more organically, like 'sticker bombing'.
- Do not use dark, desaturated colors as primary background elements; the system thrives on a light, warm canvas with vivid accents.
- Avoid strictly symmetrical or rigid component designs; embrace rounded corners and slightly irregular forms.
- Never use generic blue for primary interactive elements; leverage the brand's vibrant palette, especially Grape Punch, Leafy Green, or Bubblegum Red.
- Do not apply padding to ghost buttons; they should appear as text-only interactive elements framed by their borders.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas Almond | `#ffe9ce` | The foundational page background, providing a warm and inviting base. |
| 1 | Paper White | `#ffffff` | Primary surface for cards, speech bubbles, and light background elements, offering contrast. |
| 2 | Light Gray | `#dddddd` | Used for subtle background elements and muted buttons, providing a slight elevation or distinction. |
| 3 | Accent Surfaces | `#8a53ff` | Vividly colored card and section backgrounds (Grape Punch, Sunshine Yellow, Bubblegum Red, Leafy Green) to create energetic focus areas. |

## Imagery

The site primarily uses iconography and stylistic text as its visual language, rather than traditional imagery. Icons are filled, mono-color, and often appear within circular or starburst shapes. Text itself is treated as a major visual element, with large, expressive characters. Illustrations include speech bubbles and starbursts, filled with solid brand colors, conveying a playful, sticker-like aesthetic. There are no photographs or complex 3D renders; all visuals are graphic and flat, serving to amplify the typeface's friendly and quirky character. Imagery is used decoratively, enhancing the overall cheerful and cartoonish atmosphere.

## Layout

The page layout is full-bleed, extending content to the edges, creating an expansive feel. The hero section is characterized by a central, oversized headline on the Canvas Almond background, surrounded by 'sticker-bombed' accent cards and speech bubbles. Sections then alternate between full-width colored blocks and more contained multi-column arrangements. Vertical spacing is generous, leveraging sectionGap of 30px, giving visual elements ample breathing room, contributing to a spacious, non-dense feel. Navigation appears as simple ghost buttons, often minimal and contextual.

## Agent Prompt Guide

Quick Color Reference: 
text: #000000
background: #ffe9ce
border: #ffffff
accent: #8a53ff
primary action: no distinct CTA color

Example Component Prompts:
1. Create a hero section with 'Fictional' as the main headline: use Canvas Almond (#ffe9ce) background. Headline 'Fictional' is Type Black (#000000) using Fictional font at 346px, with a 0.9 lineHeight. Overlay a circular accent card behind 'NEW!' with Leafy Green (#3ccb09) background and Paper White text at 16px Fictional. This card should have a 100% border-radius and 8px padding.
2. Design a feature block: Full-width section with Grape Punch (#8a53ff) background. Display 'Fictional Light' as a heading (Fictional font, 48px, Paper White text, 1.2 lineHeight). Center this text vertically.
3. Create an informational speech bubble: Paper White (#ffffff) background with exaggerated 144px border-radius, 28.8px vertical and 43.2px horizontal padding. Body text 'A friendly & quirky typeface' in Type Black (#000000) at 22px Fictional, 1.4 lineHeight.

## Similar Brands

- **Playful typefoundries (e.g. Typewolf's more whimsical selections)** — Focus on highly expressive, often irregular display typefaces as the core visual identity, leveraging them as graphic elements.
- **Children's book websites** — Bright, high-saturation color palettes, rounded shapes, and a general atmosphere of whimsy and accessibility.
- **Certain indie game studios** — Use of 'sticker bomb' aesthetics with layered, colorful, and irregularly shaped graphic elements against a softer background.
- **Marketing for 'fun' consumer products** — Vibrant colors, bold typography, and a lack of harsh shadows/sharp angles to convey an approachable and energetic brand.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-almond: #ffe9ce;
  --color-paper-white: #ffffff;
  --color-type-black: #000000;
  --color-grape-punch: #8a53ff;
  --color-bubblegum-red: #fd4b38;
  --color-sunshine-yellow: #ffd80c;
  --color-leafy-green: #3ccb09;
  --color-deep-indigo: #0500a3;
  --color-ash-gray: #666666;
  --color-light-gray: #dddddd;
  --color-input-gray: #101010;

  /* Typography — Font Families */
  --font-fictional: 'Fictional', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-sm: 16px;
  --leading-body-sm: 1.71;
  --text-body: 22px;
  --leading-body: 1.4;
  --text-subheading: 29px;
  --leading-subheading: 1.3;
  --text-heading-sm: 36px;
  --leading-heading-sm: 1.2;
  --text-heading: 48px;
  --leading-heading: 1.2;
  --text-heading-lg: 72px;
  --leading-heading-lg: 1.1;
  --text-display: 346px;
  --leading-display: 0.9;

  /* Typography — Weights */
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-unit: 6px;
  --spacing-12: 12px;
  --spacing-24: 24px;
  --spacing-30: 30px;
  --spacing-60: 60px;
  --spacing-108: 108px;

  /* Layout */
  --section-gap: 30px;
  --card-padding: 29px;
  --element-gap: 12px;

  /* Border Radius */
  --radius-md: 5px;
  --radius-lg: 10px;
  --radius-xl: 15px;
  --radius-full: 144px;

  /* Named Radii */
  --radius-cards: 15px;
  --radius-buttons: 5px;
  --radius-speechbubbles: 144px;

  /* Shadows */
  --shadow-subtle: rgb(251, 215, 12) 0px 0px 0px 2px;

  /* Surfaces */
  --surface-canvas-almond: #ffe9ce;
  --surface-paper-white: #ffffff;
  --surface-light-gray: #dddddd;
  --surface-accent-surfaces: #8a53ff;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-almond: #ffe9ce;
  --color-paper-white: #ffffff;
  --color-type-black: #000000;
  --color-grape-punch: #8a53ff;
  --color-bubblegum-red: #fd4b38;
  --color-sunshine-yellow: #ffd80c;
  --color-leafy-green: #3ccb09;
  --color-deep-indigo: #0500a3;
  --color-ash-gray: #666666;
  --color-light-gray: #dddddd;
  --color-input-gray: #101010;

  /* Typography */
  --font-fictional: 'Fictional', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-sm: 16px;
  --leading-body-sm: 1.71;
  --text-body: 22px;
  --leading-body: 1.4;
  --text-subheading: 29px;
  --leading-subheading: 1.3;
  --text-heading-sm: 36px;
  --leading-heading-sm: 1.2;
  --text-heading: 48px;
  --leading-heading: 1.2;
  --text-heading-lg: 72px;
  --leading-heading-lg: 1.1;
  --text-display: 346px;
  --leading-display: 0.9;

  /* Spacing */
  --spacing-12: 12px;
  --spacing-24: 24px;
  --spacing-30: 30px;
  --spacing-60: 60px;
  --spacing-108: 108px;

  /* Border Radius */
  --radius-md: 5px;
  --radius-lg: 10px;
  --radius-xl: 15px;
  --radius-full: 144px;

  /* Shadows */
  --shadow-subtle: rgb(251, 215, 12) 0px 0px 0px 2px;
}
```

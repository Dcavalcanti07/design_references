# Boostinsurance — Style Reference
> Deep ocean current, softly glowing

**Theme:** dark

Boost Insurance presents a deep, dark theme where information is showcased with spacious layouts and subtle gradients, creating a high-tech yet approachable atmosphere. Typography is precise and airy, favoring lighter weights for impact. Subtle green accents provide functional cues without overwhelming the somber background, while rounded corners give components a soft, organic quality against the structured grid.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Deep Ocean | `#002025` | `--color-deep-ocean` | Page background, primary surface, deep text |
| Seaweed Green | `#05333a` | `--color-seaweed-green` | Elevated card surfaces, subtle background shifts |
| Kelp Shadow | `#244348` | `--color-kelp-shadow` | Secondary card backgrounds, decorative strokes |
| Deep Sea Gray | `#455c60` | `--color-deep-sea-gray` | Tertiary card backgrounds, muted decorative fills |
| Slate Echo | `#54696c` | `--color-slate-echo` | Muted text, subheadings, decorative fills |
| Silver Mist | `#7d8f92` | `--color-silver-mist` | Helper text, borders for ghost elements |
| Pale Mist | `#9eaeb0` | `--color-pale-mist` | Body text, secondary text |
| Frost White | `#fffffa` | `--color-frost-white` | Primary text, headings, icons, borders for hover states |
| Aqua Glow | `linear-gradient(100.7deg, rgb(48, 215, 241) 8.74%, rgb(121, 250, 75) 92.06%)` | `--color-aqua-glow` | Primary accent, one end of the primary gradient; Supporting palette color for small decorative accents when the core palette needs contrast. Do not promote it to the primary CTA color |
| Lime Burst | `#79fa4b` | `--color-lime-burst` | Green outline accent for tags, dividers, and focused UI edges |
| Mint Glaze | `#a4ed8a` | `--color-mint-glaze` | Outline for ghost action buttons, link underlines, subtle highlights |
| Halo Gradient | `linear-gradient(277.33deg, rgb(252, 227, 68) -2.48%, rgb(121, 250, 75) 47.21%, rgb(48, 215, 241) 93.62%)` | `--color-halo-gradient` | Complex multi-color gradient for illustrative elements and subtle background textures |

## Tokens — Typography

### Gellix — Primary typeface for all UI elements, headings, body text, and links. Features a wide range of weights for specific visual hierarchy, with tighter letter spacing for display sizes. · `--font-gellix`
- **Substitute:** Inter
- **Weights:** 300, 400, 500, 600
- **Sizes:** 12px, 13px, 14px, 16px, 18px, 20px, 22px, 26px, 48px, 90px, 120px
- **Line height:** 0.85, 1.00, 1.05, 1.10, 1.20, 1.25, 1.30, 1.45
- **Letter spacing:** -0.0400em, -0.0300em, -0.0200em, -0.0100em, 0.0800em, 0.3500em
- **Role:** Primary typeface for all UI elements, headings, body text, and links. Features a wide range of weights for specific visual hierarchy, with tighter letter spacing for display sizes.

### Times — Fallback font for specific text elements, likely used for content when Gellix is unavailable or for semantic distinction. Keep usage minimal. · `--font-times`
- **Substitute:** serif
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.20
- **Role:** Fallback font for specific text elements, likely used for content when Gellix is unavailable or for semantic distinction. Keep usage minimal.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.45 | 0.08px | `--text-caption` |
| body | 16px | 1.25 | -0.01px | `--text-body` |
| subheading | 18px | 1.2 | -0.01px | `--text-subheading` |
| heading-sm | 22px | 1.1 | -0.02px | `--text-heading-sm` |
| heading | 48px | 1.05 | -0.03px | `--text-heading` |
| display | 90px | 0.85 | -0.04px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** spacious

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 8 | 8px | `--spacing-8` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 40 | 40px | `--spacing-40` |
| 60 | 60px | `--spacing-60` |
| 100 | 100px | `--spacing-100` |
| 112 | 112px | `--spacing-112` |
| 136 | 136px | `--spacing-136` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 29.9952px |
| large | 15.9984px |
| small | 2.9952px |
| images | 29.9952px |
| medium | 10px |
| buttons | 999px |

### Layout

- **Section gap:** 30px
- **Card padding:** 40px
- **Element gap:** 5px

## Components

### Ghost Navigation Button
**Role:** Primary navigation links and text-based interactive elements

Transparent background (rgba(0,0,0,0)), Frost White text (#fffffa), no border or padding for minimal footprint. Uses Gellix font, typically weight 400 at 16px.

### Gradient Call to Action Button
**Role:** Main interactive button for primary actions

Features a linear gradient background from Aqua Glow to Lime Burst. Text is Deep Ocean (#002025). Has a 999px border-radius for a pill shape, with 18px vertical and 30px horizontal padding. Font is Gellix, 16px, weight 400.

### Outlined Accent CTA
**Role:** Secondary call to action or link that needs visual emphasis without being a filled button.

Features Mint Glaze (#a4ed8a) border color and text color, with a transparent background. No specific padding or border radius; follows inline link styling.

### Soft Card
**Role:** Container for content sections, subtly elevated

Background is Seaweed Green (#05333a), with rounded corners (29.9952px). Internal content padding is 40px top/bottom and 19px left/right. No visible box shadow.

### Muted Card Background
**Role:** Background for secondary content areas or embedded elements within cards.

Deep Sea Gray (#455c60) background with no radius or padding. Used for subtle visual distinction.

## Do's and Don'ts

### Do
- Prioritize Deep Ocean (#002025) for all primary page and component backgrounds.
- Use Frost White (#fffffa) for all primary headings and body text to ensure maximum contrast on dark backgrounds.
- Apply Gellix font with lighter weights (300, 400) for headlines to convey authority through restraint.
- Incorporate Aqua Glow (#30d7f1), Lime Burst (#79fa4b), and Mint Glaze (#a4ed8a) sparingly as functional highlights for links, active states, and decorative elements.
- Use a generous 29.9952px border-radius for cards and large visual elements to maintain the soft, fluid aesthetic.
- Ensure ample vertical spacing between sections (30px base) to create a spacious reading experience.
- Utilize the full-bleed linear gradient (linear-gradient(100.7deg, rgb(48, 215, 241) 8.74%, rgb(121, 250, 75) 92.06%)) for primary CTA buttons and critical interactive elements.

### Don't
- Avoid harsh, fully saturated colors that deviate from the curated accent palette.
- Do not use heavy box-shadows or strong elevation, as the design system explicitly avoids pronounced layering.
- Refrain from using bold or heavy font weights for large headlines; maintain the light and airy typographic style.
- Do not introduce sharp corners on cards or primary UI elements; adhere to the generous 29.9952px radius.
- Avoid dense, information-heavy blocks without sufficient internal padding or element gaps; maintain a spacious layout.
- Do not introduce additional accent colors outside of the defined Aqua Glow, Lime Burst, and Mint Glaze; these are the sole chromatic accents.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Deep Ocean Canvas | `#002025` | Primary page background, base layer. |
| 1 | Seaweed Green Card | `#05333a` | Elevated card backgrounds, distinct content containers. |
| 2 | Kelp Shadow Panel | `#244348` | Secondary elevated surfaces, often used for enclosed components or detailed data displays within cards. |

## Elevation

The design system explicitly avoids strong cast shadows. Instead, visual hierarchy and separation for elevated components are achieved through subtle shifts in background color using the defined surface palette (Deep Ocean, Seaweed Green, Kelp Shadow) and soft background blurs, creating depth without heavy visual effects.

## Imagery

Imagery primarily consists of abstract financial and technology-themed illustrations, often featuring wireframes, glowing nodes, and stylized product interfaces. These are dimensional, filled, and use the brand's gradient palette, often appearing within softly rounded cards or as atmospheric elements. Functional icons are outlined with a fine stroke, often in Frost White or a soft gray, providing clarity on the dark background. The overall density of imagery is balanced, visually supporting text blocks without overwhelming them.

## Layout

The page uses a full-bleed structure for its dark background, creating an immersive experience, but content within these sections often adheres to a defined max-width. The hero section is full-bleed with a centered, multi-line headline and a gradient CTA. Sections generally follow a consistent vertical rhythm, using generous spacing and often feature a left-aligned text block paired with an illustration or product screenshot on the right. Content areas frequently utilize rounded card containers for feature showcases and lists. Navigation is a sticky top bar with ghost interactive elements, providing persistent access.

## Agent Prompt Guide

### Quick Color Reference
text: #fffffa
background: #002025
border: #7d8f92
accent: #30d7f1
primary action: #a4ed8a (outlined action border)

### 3-5 Example Component Prompts
1. Create an Outlined Primary Action: Transparent background, #a4ed8a border and text, 9999px radius, compact pill padding. Use it for the main CTA instead of a filled button.

## Similar Brands

- **Stripe** — Shares a clean, API-first aesthetic with a focus on dark mode and subtle brand color accents.
- **Gusto** — Similar approach to modern financial tools, using spacious layouts and a curated color palette for clarity.
- **Vercel** — Dark-themed developer tool with precise typography, subtle gradients, and rounded component shapes.
- **Linear** — Application of a deep, dark base with crisp, light typography and limited, functional accent colors.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-deep-ocean: #002025;
  --color-seaweed-green: #05333a;
  --color-kelp-shadow: #244348;
  --color-deep-sea-gray: #455c60;
  --color-slate-echo: #54696c;
  --color-silver-mist: #7d8f92;
  --color-pale-mist: #9eaeb0;
  --color-frost-white: #fffffa;
  --color-aqua-glow: #30d7f1;
  --gradient-aqua-glow: linear-gradient(100.7deg, rgb(48, 215, 241) 8.74%, rgb(121, 250, 75) 92.06%);
  --color-lime-burst: #79fa4b;
  --color-mint-glaze: #a4ed8a;
  --color-halo-gradient: #fce344;
  --gradient-halo-gradient: linear-gradient(277.33deg, rgb(252, 227, 68) -2.48%, rgb(121, 250, 75) 47.21%, rgb(48, 215, 241) 93.62%);

  /* Typography — Font Families */
  --font-gellix: 'Gellix', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-times: 'Times', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.45;
  --tracking-caption: 0.08px;
  --text-body: 16px;
  --leading-body: 1.25;
  --tracking-body: -0.01px;
  --text-subheading: 18px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.01px;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1.1;
  --tracking-heading-sm: -0.02px;
  --text-heading: 48px;
  --leading-heading: 1.05;
  --tracking-heading: -0.03px;
  --text-display: 90px;
  --leading-display: 0.85;
  --tracking-display: -0.04px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-100: 100px;
  --spacing-112: 112px;
  --spacing-136: 136px;

  /* Layout */
  --section-gap: 30px;
  --card-padding: 40px;
  --element-gap: 5px;

  /* Border Radius */
  --radius-sm: 2.9952px;
  --radius-md: 4.9968px;
  --radius-lg: 10px;
  --radius-2xl: 15.9984px;
  --radius-3xl: 26.496px;
  --radius-3xl-2: 29.9952px;
  --radius-3xl-3: 33.9984px;
  --radius-full: 999px;

  /* Named Radii */
  --radius-cards: 29.9952px;
  --radius-large: 15.9984px;
  --radius-small: 2.9952px;
  --radius-images: 29.9952px;
  --radius-medium: 10px;
  --radius-buttons: 999px;

  /* Surfaces */
  --surface-deep-ocean-canvas: #002025;
  --surface-seaweed-green-card: #05333a;
  --surface-kelp-shadow-panel: #244348;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-deep-ocean: #002025;
  --color-seaweed-green: #05333a;
  --color-kelp-shadow: #244348;
  --color-deep-sea-gray: #455c60;
  --color-slate-echo: #54696c;
  --color-silver-mist: #7d8f92;
  --color-pale-mist: #9eaeb0;
  --color-frost-white: #fffffa;
  --color-aqua-glow: #30d7f1;
  --color-lime-burst: #79fa4b;
  --color-mint-glaze: #a4ed8a;
  --color-halo-gradient: #fce344;

  /* Typography */
  --font-gellix: 'Gellix', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-times: 'Times', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.45;
  --tracking-caption: 0.08px;
  --text-body: 16px;
  --leading-body: 1.25;
  --tracking-body: -0.01px;
  --text-subheading: 18px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.01px;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1.1;
  --tracking-heading-sm: -0.02px;
  --text-heading: 48px;
  --leading-heading: 1.05;
  --tracking-heading: -0.03px;
  --text-display: 90px;
  --leading-display: 0.85;
  --tracking-display: -0.04px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-100: 100px;
  --spacing-112: 112px;
  --spacing-136: 136px;

  /* Border Radius */
  --radius-sm: 2.9952px;
  --radius-md: 4.9968px;
  --radius-lg: 10px;
  --radius-2xl: 15.9984px;
  --radius-3xl: 26.496px;
  --radius-3xl-2: 29.9952px;
  --radius-3xl-3: 33.9984px;
  --radius-full: 999px;
}
```

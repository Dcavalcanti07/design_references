# Fluz — Style Reference
> Vivid gradient playground

**Theme:** light

Fluz employs a vibrant, energetic visual style, characterized by bold, condensed typography on gradients with floating illustrative elements. The UI balances strong, dark text against light or gradient backgrounds, emphasizing action and impact. Components are designed with soft, rounded edges and prioritize clear calls to action, maintaining a playful yet assertive tone.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Money Max Black | `#1a0000` | `--color-money-max-black` | Primary action background, strong text, link borders, and decorative accents. This near-black red provides a bold, dominant presence |
| Sky Blue | `#98bbf4` | `--color-sky-blue` | Background for feature cards, providing a soft, expansive feel |
| Forest Noir | `#11190c` | `--color-forest-noir` | Dark borders and separators for elevated surfaces and inverted UI. Do not promote it to the primary CTA color |
| Canvas White | `#ffffff` | `--color-canvas-white` | Main page background, content surfaces, button text, and base for overlays |
| Mist Gray | `#f2f2f2` | `--color-mist-gray` | Subtle secondary background for cards or section breaks, providing visual texture |
| Light Cloud | `#ededec` | `--color-light-cloud` | Hover states, subtle borders, and background for ghost buttons |
| Iron Slate | `#3a3a3a` | `--color-iron-slate` | Dark borders and separators for elevated surfaces and inverted UI. Do not promote it to the primary CTA color |
| Onyx Shadow | `#221919` | `--color-onyx-shadow` | Deep background for certain sections, giving a rich, dark contrast |
| Subtle Ash | `#514f4c` | `--color-subtle-ash` | Muted body text and secondary information, maintaining hierarchy without stark contrast |
| Pebble Gray | `#aeaea6` | `--color-pebble-gray` | Helper text and descriptive paragraphs, offering a gentler readability |
| Hero Gradient Green to Blue | `linear-gradient(90deg, rgb(130, 190, 255), rgb(166, 180, 247) 47.21%, rgb(91, 184, 154) 73.75%, rgb(33, 186, 76) 91.26%)` | `--color-hero-gradient-green-to-blue` | Primary hero background, creating a dynamic and expansive visual field. This gradient sets an energetic and inviting tone |
| Hero Gradient Vertical | `linear-gradient(0deg, rgb(125, 180, 244) 25%, rgb(147, 180, 246) 38%, rgb(166, 180, 247) 47%, rgb(104, 184, 171) 83%, rgb(33, 186, 76) 99%)` | `--color-hero-gradient-vertical` | A variant of the hero gradient, for vertical applications or specific sections requiring a similar chromatic blend |
| Dark Gradient Background | `linear-gradient(rgb(38, 34, 33) 26%, rgb(86, 71, 67) 100%)` | `--color-dark-gradient-background` | Rich, dark background for sections that need maximum contrast and depth |

## Tokens — Typography

### Area Semibold — General body text, navigation elements, and card text. Provides a clean, readable contrast to the condensed headings. · `--font-area-semibold`
- **Substitute:** Inter
- **Weights:** 400, 700
- **Sizes:** 16px, 17px, 20px
- **Line height:** 1.40, 1.45, 1.50
- **Role:** General body text, navigation elements, and card text. Provides a clean, readable contrast to the condensed headings.

### Greed Condensed SemiBold — Primary headings and display text, used at large sizes with tight letter spacing for maximum impact and a bold, declarative statement. · `--font-greed-condensed-semibold`
- **Substitute:** Bebas Neue
- **Weights:** 400, 700
- **Sizes:** 16px, 24px
- **Line height:** 1.17, 1.25, 1.50
- **Letter spacing:** -0.030em, -0.025em, -0.020em, -0.019em, -0.005em
- **Role:** Primary headings and display text, used at large sizes with tight letter spacing for maximum impact and a bold, declarative statement.

### Greed-CondensedSemiBold — Subheadings and section titles, supporting the condensed style with slightly looser tracking. · `--font-greed-condensedsemibold`
- **Substitute:** Bebas Neue
- **Weights:** 400, 700
- **Sizes:** 16px, 24px
- **Line height:** 1.17, 1.25, 1.50
- **Letter spacing:** -0.0160em
- **Role:** Subheadings and section titles, supporting the condensed style with slightly looser tracking.

### Greed-SemiBold — Metadata, captions, and smaller interface labels. · `--font-greed-semibold`
- **Substitute:** Public Sans
- **Weights:** 400, 700
- **Sizes:** 11px, 14px
- **Line height:** 1.27, 1.29
- **Role:** Metadata, captions, and smaller interface labels.

### Arial — System default for utilitarian elements like legal text or form labels, ensuring accessibility. · `--font-arial`
- **Substitute:** Arial
- **Weights:** 400
- **Sizes:** 13px
- **Line height:** 1.20
- **Role:** System default for utilitarian elements like legal text or form labels, ensuring accessibility.

### Greed Condensed SemiBold — Greed Condensed SemiBold — detected in extracted data but not described by AI · `--font-greed-condensed-semibold`
- **Weights:** 700
- **Sizes:** 18px, 20px, 32px, 42px, 64px, 96px, 203px
- **Line height:** 0.79, 0.91, 1, 1.15, 1.2, 1.33
- **Letter spacing:** -0.025, -0.02, -0.019, -0.005
- **Role:** Greed Condensed SemiBold — detected in extracted data but not described by AI

### Greed SemiBold — Greed SemiBold — detected in extracted data but not described by AI · `--font-greed-semibold`
- **Weights:** 600, 700
- **Sizes:** 15px, 54px
- **Line height:** 0.92, 1.6
- **Letter spacing:** -0.03
- **Role:** Greed SemiBold — detected in extracted data but not described by AI

### Area-Extrabold — Area-Extrabold — detected in extracted data but not described by AI · `--font-area-extrabold`
- **Weights:** 700
- **Sizes:** 11px
- **Line height:** 1.4
- **Role:** Area-Extrabold — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 11px | 1.4 | — | `--text-caption` |
| body-sm | 14px | 1.29 | — | `--text-body-sm` |
| body | 16px | 1.4 | — | `--text-body` |
| subheading | 24px | 1.25 | -0.016px | `--text-subheading` |
| heading | 42px | 1.15 | -0.025px | `--text-heading` |
| heading-lg | 64px | 1 | -0.025px | `--text-heading-lg` |
| display | 96px | 0.91 | -0.025px | `--text-display` |

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
| 24 | 24px | `--spacing-24` |
| 28 | 28px | `--spacing-28` |
| 32 | 32px | `--spacing-32` |
| 36 | 36px | `--spacing-36` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 56 | 56px | `--spacing-56` |
| 96 | 96px | `--spacing-96` |
| 140 | 140px | `--spacing-140` |
| 192 | 192px | `--spacing-192` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 20px |
| images | 20px |
| buttons | 100px |

### Layout

- **Page max-width:** 1750px
- **Section gap:** 40px
- **Card padding:** 20px
- **Element gap:** 5px

## Components

### Primary Action Button
**Role:** High-impact call to action

Filled with Money Max Black (#1a0000), white text (#ffffff), 200px border-radius, 16px vertical padding, 32px horizontal padding. This creates a distinct, pill-shaped button.

### Outline Ghost Button
**Role:** Secondary or tertiary action

Transparent background (rgba(0,0,0,0)), text and 1px border in Forest Noir (#222624, implied from raw data #161616), 100px border-radius, 8px vertical padding, 18px horizontal padding. A subtle, rounded button for less prominent actions.

### Light Muted Button
**Role:** Informational or inactive states

Background in Light Cloud (#ededec), text in Money Max Black (#1a0000), 100px border-radius, 8px vertical padding, 16px horizontal padding. Used for buttons that need less emphasis.

### Floating Content Card
**Role:** Showcasing features or content blocks

Transparent background (rgba(0,0,0,0)), 20px border-radius, generous 36px padding on top, right, and left, with 0px bottom padding. Focuses on content presentation without a contained background.

### Product Display Card
**Role:** Presenting product visuals

Transparent background (rgba(0,0,0,0)), 0px border-radius, no padding. Used for full-bleed imagery or dynamic content blocks where the image defines the card shape.

### Hero Section Callout Card
**Role:** Primary informational sections requiring visual distinction

Background in Sky Blue (#98bbf4), 40px top and bottom border-radius with 0px side radius, 65px vertical padding, 40px horizontal padding. Creates a prominent, soft-edged container for hero content.

## Do's and Don'ts

### Do
- Use Greed Condensed SemiBold 700 with letter spacing from -0.030em to -0.005em for all prominent headings to maintain high impact.
- Apply 200px border-radius to all primary action buttons for a consistent pill-shaped appearance.
- Utilize the Hero Gradient Green to Blue for primary hero sections, ensuring a dynamic and brand-aligned background.
- Structure major page sections with a 40px section gap for comfortable breathing room.
- Employ Money Max Black (#1a0000) for all primary text elements to ensure strong contrast and brand recognition.
- Use a Light Cloud (#ededec) background for ghost buttons and subtle interactive elements.
- Maintain a 1750px pageMaxWidth for horizontal content containment, creating a wide but controlled layout experience.

### Don't
- Avoid sharp corners; ensure all containers, cards, and buttons use a minimum 20px radius unless specifically constrained by imagery.
- Do not use generic system fonts for display headings; always prioritize Greed Condensed SemiBold or its substitutes for brand consistency.
- Refrain from using overly high-contrast borders on cards; prefer soft or transparent backgrounds with subtle elevation for depth.
- Do not introduce new primary action colors; stick to Money Max Black (#1a0000) for filled buttons and Forest Noir (#11190c) for outlined buttons.
- Avoid dense packing of elements; maintain at least 5px for element gaps to preserve readability and visual comfort.
- Do not use subtle, muted colors for primary calls to action; these should always be bold and clear using Money Max Black.
- Do not alter the tight letter spacing of Greed Condensed SemiBold for headlines; it is integral to its visual impact.

## Agent Prompt Guide

Quick Color Reference:
text: #1a0000
background: #ffffff
border: #ededec
accent: #98bbf4
primary action: #1a0000 (filled action)

Example Component Prompts:
1. Create a Primary Action Button: Money Max Black background (#1a0000), Canvas White text (#ffffff), 200px radius, 16px vertical padding, 32px horizontal padding.
2. Create a Product Display Card: transparent background, 0px radius, with an embedded full-bleed image and no padding.
3. Create a Hero Section Headline: 'YOUR MONEY ON MAX.' using Greed Condensed SemiBold 700 at 96px, letter-spacing -0.025em, Canvas White text (#ffffff), centered over the Hero Gradient Green to Blue background.
4. Create an Outline Ghost Button: transparent background (rgba(0,0,0,0)), Forest Noir text (#11190c, or #161616 if used for border), 100px radius, 8px vertical padding, 18px horizontal padding, with a 1px Forest Noir border.

## Similar Brands

- **Revolut** — Both use vibrant gradients, bold typography, and a modern, slightly playful aesthetic for financial services, with an emphasis on app screenshots.
- **Cash App** — Similar use of dark backgrounds for elevated sections, bold, condensed display fonts, and clear, action-oriented design in a financial context.
- **Chime** — Employs clean, rounded UI elements alongside a bright, inviting color palette with a strong brand accent, making financial services feel approachable.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-money-max-black: #1a0000;
  --color-sky-blue: #98bbf4;
  --color-forest-noir: #11190c;
  --color-canvas-white: #ffffff;
  --color-mist-gray: #f2f2f2;
  --color-light-cloud: #ededec;
  --color-iron-slate: #3a3a3a;
  --color-onyx-shadow: #221919;
  --color-subtle-ash: #514f4c;
  --color-pebble-gray: #aeaea6;
  --color-hero-gradient-green-to-blue: #82befe;
  --gradient-hero-gradient-green-to-blue: linear-gradient(90deg, rgb(130, 190, 255), rgb(166, 180, 247) 47.21%, rgb(91, 184, 154) 73.75%, rgb(33, 186, 76) 91.26%);
  --color-hero-gradient-vertical: #7db4f4;
  --gradient-hero-gradient-vertical: linear-gradient(0deg, rgb(125, 180, 244) 25%, rgb(147, 180, 246) 38%, rgb(166, 180, 247) 47%, rgb(104, 184, 171) 83%, rgb(33, 186, 76) 99%);
  --color-dark-gradient-background: #262221;
  --gradient-dark-gradient-background: linear-gradient(rgb(38, 34, 33) 26%, rgb(86, 71, 67) 100%);

  /* Typography — Font Families */
  --font-area-semibold: 'Area Semibold', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-greed-condensed-semibold: 'Greed Condensed SemiBold', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-greed-condensedsemibold: 'Greed-CondensedSemiBold', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-greed-semibold: 'Greed-SemiBold', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-area-extrabold: 'Area-Extrabold', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.4;
  --text-body-sm: 14px;
  --leading-body-sm: 1.29;
  --text-body: 16px;
  --leading-body: 1.4;
  --text-subheading: 24px;
  --leading-subheading: 1.25;
  --tracking-subheading: -0.016px;
  --text-heading: 42px;
  --leading-heading: 1.15;
  --tracking-heading: -0.025px;
  --text-heading-lg: 64px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -0.025px;
  --text-display: 96px;
  --leading-display: 0.91;
  --tracking-display: -0.025px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-96: 96px;
  --spacing-140: 140px;
  --spacing-192: 192px;

  /* Layout */
  --page-max-width: 1750px;
  --section-gap: 40px;
  --card-padding: 20px;
  --element-gap: 5px;

  /* Border Radius */
  --radius-xl: 15px;
  --radius-2xl: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 40px;
  --radius-full: 100px;
  --radius-full-2: 200px;
  --radius-full-3: 500px;

  /* Named Radii */
  --radius-cards: 20px;
  --radius-images: 20px;
  --radius-buttons: 100px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-money-max-black: #1a0000;
  --color-sky-blue: #98bbf4;
  --color-forest-noir: #11190c;
  --color-canvas-white: #ffffff;
  --color-mist-gray: #f2f2f2;
  --color-light-cloud: #ededec;
  --color-iron-slate: #3a3a3a;
  --color-onyx-shadow: #221919;
  --color-subtle-ash: #514f4c;
  --color-pebble-gray: #aeaea6;
  --color-hero-gradient-green-to-blue: #82befe;
  --color-hero-gradient-vertical: #7db4f4;
  --color-dark-gradient-background: #262221;

  /* Typography */
  --font-area-semibold: 'Area Semibold', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-greed-condensed-semibold: 'Greed Condensed SemiBold', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-greed-condensedsemibold: 'Greed-CondensedSemiBold', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-greed-semibold: 'Greed-SemiBold', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-area-extrabold: 'Area-Extrabold', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.4;
  --text-body-sm: 14px;
  --leading-body-sm: 1.29;
  --text-body: 16px;
  --leading-body: 1.4;
  --text-subheading: 24px;
  --leading-subheading: 1.25;
  --tracking-subheading: -0.016px;
  --text-heading: 42px;
  --leading-heading: 1.15;
  --tracking-heading: -0.025px;
  --text-heading-lg: 64px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -0.025px;
  --text-display: 96px;
  --leading-display: 0.91;
  --tracking-display: -0.025px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-96: 96px;
  --spacing-140: 140px;
  --spacing-192: 192px;

  /* Border Radius */
  --radius-xl: 15px;
  --radius-2xl: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 40px;
  --radius-full: 100px;
  --radius-full-2: 200px;
  --radius-full-3: 500px;
}
```

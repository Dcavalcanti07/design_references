# Adam Lippes — Style Reference
> Gallery white space, tailored outlines.

**Theme:** light

Adam Lippes exudes understated luxury through a stark, monochromatic palette and minimalist design. High-contrast typography pairs delicate serifs with bold sans-serifs, creating a refined yet assertive presence. Component edges are sharp, with zero or minimal border radii, emphasizing clean lines and structured forms, while strategic use of an off-white canvas prevents visual harshness.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Ink | `#000000` | `--color-ink` | Primary text, heading text, critical UI borders, filled button backgrounds, primary icon color |
| Paper White | `#fefcf8` | `--color-paper-white` | Main page background, card surfaces, ghost button text, placeholder text for inverse buttons |
| Arctic Mist | `#ffffff` | `--color-arctic-mist` | Accent backgrounds, elevated input fields, secondary surface elements |
| Steel Gray | `#4c4c4a` | `--color-steel-gray` | Secondary text, subtle borders, inactive link states |
| Coal | `#121212` | `--color-coal` | Button text color against light backgrounds, secondary button borders |
| Carbon | `#403f3e` | `--color-carbon` | Tertiary borders, subtle icon fills, supporting text |
| Pale Ash | `#b2b0ae` | `--color-pale-ash` | Disabled button backgrounds, subtle divider lines |

## Tokens — Typography

### Optima — Primary typeface for most text, including body copy, navigation, buttons, and headings. Its classic serif form lends a timeless, high-fashion aesthetic. · `--font-optima`
- **Substitute:** Palatino Linotype, Georgia
- **Weights:** 400
- **Sizes:** 10px, 11px, 12px, 13px, 14px, 16px, 24px
- **Line height:** 1.00, 1.10, 1.20, 1.30, 1.40, 1.50, 1.70, 1.80
- **Letter spacing:** 0.031em at 10px, 0.064em at 11px
- **Role:** Primary typeface for most text, including body copy, navigation, buttons, and headings. Its classic serif form lends a timeless, high-fashion aesthetic.

### Arial — Used sparingly for specific button text where a clean, approachable sans-serif supports functionality over a strong brand statement. Functions as a highly readable utility font. · `--font-arial`
- **Substitute:** Helvetica Neue, sans-serif
- **Weights:** 400
- **Sizes:** 13px
- **Line height:** 1.20
- **Letter spacing:** 0em
- **Role:** Used sparingly for specific button text where a clean, approachable sans-serif supports functionality over a strong brand statement. Functions as a highly readable utility font.

### GTStandard-M — A custom font likely used for specific brand slogans or larger calls to action, providing a distinct modern contrast to Optima. · `--font-gtstandard-m`
- **Substitute:** Montserrat, Open Sans
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.50
- **Letter spacing:** 0em
- **Role:** A custom font likely used for specific brand slogans or larger calls to action, providing a distinct modern contrast to Optima.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.4 | — | `--text-caption` |
| body-sm | 11px | 1.4 | — | `--text-body-sm` |
| body | 12px | 1.4 | — | `--text-body` |
| body-lg | 13px | 1.4 | — | `--text-body-lg` |
| heading-sm | 14px | 1.4 | — | `--text-heading-sm` |
| heading | 16px | 1.4 | — | `--text-heading` |
| heading-lg | 24px | 1.3 | — | `--text-heading-lg` |

## Tokens — Spacing & Shapes

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 5 | 5px | `--spacing-5` |
| 6 | 6px | `--spacing-6` |
| 8 | 8px | `--spacing-8` |
| 9 | 9px | `--spacing-9` |
| 10 | 10px | `--spacing-10` |
| 12 | 12px | `--spacing-12` |
| 13 | 13px | `--spacing-13` |
| 14 | 14px | `--spacing-14` |
| 15 | 15px | `--spacing-15` |
| 16 | 16px | `--spacing-16` |
| 17 | 17px | `--spacing-17` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 30 | 30px | `--spacing-30` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 0px |
| badges | 40px |
| buttons | 0px |
| ghost-button-accent | 1000px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| sm | `rgba(0, 0, 0, 0.05) 0px 4px 5px 0px` | `--shadow-sm` |
| lg | `rgba(0, 0, 0, 0.15) 0px -8px 24px 0px` | `--shadow-lg` |

### Layout

- **Section gap:** 48px
- **Card padding:** 0px
- **Element gap:** 10px

## Components

### Primary Action Button
**Role:** Call to action button

Solid black background (Ink), Paper White text, zero border radius, generous horizontal padding (30px). Used for primary calls to action like 'Shop Now'.

### Outlined Navigation Button
**Role:** Ghost navigation button

Transparent background, Ink text and border, zero border radius, minimal horizontal padding (16px). Used for navigation items that look like buttons but act as links.

### Inverse Ghost Button
**Role:** Ghost button with light text on dark

Transparent background, Paper White text and border, zero border radius, generous horizontal padding (30px). Used for calls to action against dark hero sections.

### Subtle Accent Pill Button
**Role:** Pill-shaped accent button

Dark translucent background (rgba(0, 0, 0, 0.3)), transparent text (rgba(0, 0, 0, 0.75)) for a ghost effect, highly rounded (1000px) corner radius. Used for subtle interactive elements or pagination within image carousels.

### Product Listing Card
**Role:** Product display card

Transparent background, zero border radius, no box shadow, 0px padding. Often contains an image and text details below.

### Highlighted Product Card
**Role:** Featured product card

Paper White background, zero border radius, no box shadow, 0px padding. Used for product details against the main page background.

### Elevated Drawer Card
**Role:** Modal or drawer card

Paper White background, top corners rounded (16px), subtle bottom shadow (rgba(0, 0, 0, 0.15) 0px -8px 24px 0px). Used for elements like mini-carts or search overlays that appear from the top or bottom.

### Text Input (Light)
**Role:** Form input field

Paper White background, Ink border, zero border radius, 0px padding-left and padding-right with large right padding to prevent text overflow below a right-aligned icon.

### Text Input (Alternative)
**Role:** Alternative form input field

Arctic Mist background, Ink border, zero border radius, 16px left padding. Used for standard text inputs.

### Minimal Badge
**Role:** Informational tag

Transparent background, Ink text, zero border radius, 8px padding. Used for simple tags or categories.

### Rounded Badge
**Role:** Rounded tag

Transparent background, Dark Gray text, 40px border radius, no padding, used to provide a soft, less prominent tag.

## Do's and Don'ts

### Do
- Always use Ink for primary headings and text, with Optima 400 as the font family.
- Apply Paper White as the predominant background color for all main content areas and cards, creating a gallery-like appearance.
- Utilize Ink for all key UI borders including buttons, inputs, and navigation to maintain high contrast and definition.
- Implement zero border radius for most interactive elements like buttons and cards, enforcing a sharp, architectural aesthetic, except for specific accent buttons or elevated elements.
- Ensure large interactive buttons have at least 30px horizontal padding to provide ample touch targets and an elegant appearance.
- Use Optima at various sizes for a consistent typographic voice, reserving Arial only for specific functional button labels where simplicity is paramount.
- Maintain a compact spacing profile, with a base element gap of 10px and careful use of larger spacing only for section separation.

### Don't
- Avoid using rounded corners randomly; only apply the 1000px or 40px radius when explicitly designing a pill-shaped accent or badge.
- Do not introduce new colors; the palette is strictly monochrome with specific semantic exceptions for error, success, and focus.
- Avoid heavy drop shadows; implement only the subtle nav bar shadow (rgba(0, 0, 0, 0.05) 0px 4px 5px 0px) or the distinct bottom shadow for elevated elements (rgba(0, 0, 0, 0.15) 0px -8px 24px 0px).
- Do not use generic sans-serif fonts; stick to Optima as the primary brand font and Arial for specific functional instances only.
- Refrain from using color to indicate interactive states; rely on border and background color changes within the existing monochrome palette.
- Do not deviate from the specified padding for components; precise spacing defines their distinct visual rhythm.
- Avoid full-bleed backgrounds for interactive elements like buttons; always use solid colors or transparent fills for clear definition.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Paper White Canvas | `#fefcf8` | Dominant page background for all content areas, creating a clean, expansive foundation. |
| 1 | Arctic Mist Card/Input | `#ffffff` | Used for elevated components like certain input fields or overlaid sections, appearing slightly brighter than the canvas. |
| 2 | Elevated Drawer/Overlay | `#fefcf8` | Background for modal-like components (e.g., mini-cart) which may have a distinct shadow and top-rounded corners, matching the canvas but visually distinct through elevation. |

## Elevation

- **Navigation Bar:** `rgba(0, 0, 0, 0.05) 0px 4px 5px 0px`
- **Elevated Drawer Card:** `rgba(0, 0, 0, 0.15) 0px -8px 24px 0px`

## Imagery

Imagery on Adam Lippes is primarily high-quality, editorial fashion photography featuring models wearing the garments. The treatment involves generous white space isolating the subjects, often cropped to highlight the clothing's texture and form rather than lifestyle. Photography is typically high-key with soft, natural lighting, maintaining a sophisticated and aspirational tone. Product images within listings are clean, isolated cutouts on a white or light gray background, allowing the product to be the sole focus. Icons are minimal, outlined, and monochromatic (Ink), serving purely functional purposes rather than decorative elements. Illustrations are absent.

## Layout

The page uses a maximum-width contained layout, though the exact max width is not fixed in the data, content is generally centered. The hero section often features a full-width background image with text overlaid on a dark, slightly transparent Ink overlay. Content rhythm alternates between large, full-bleed hero sections and neatly arranged product grids or two-column text-image sections with consistent vertical spacing. Product listings are presented in a flexible grid, often with three or four columns. Navigation is a prominent, fixed top bar, featuring the brand logo centrally and minimalist navigation links and icons at the edges. Density is moderate, balancing visual impact with content information.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #fefcf8
border: #000000
accent: no distinct accent color
primary action: #000000 (filled action)

Example Component Prompts:
Create a hero section: full-width image with a dark overlay, 'New Arrivals' heading in Optima 24px 400 #fefcf8, and a 'Shop Now' button at the bottom left with background Ink, text Paper White, 0px radius, 30px horizontal padding.
Create a product listing card: transparent background, 0px radius, Optima 13px 400 Ink text for product name, Optima 12px 400 Coal for price. No padding.
Create a Primary Action Button: #000000 background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
Create a newsletter sign-up input field: Arctic Mist background, 1px Ink border, 0px radius, 16px left padding, placeholder text in Steel Gray, Optima 13px 400.
Create a subtle accent pill within an image carousel: rgba(0, 0, 0, 0.3) background, 1000px border radius, rgba(0, 0, 0, 0.75) text, Optima 10px 400.

## Similar Brands

- **Net-A-Porter** — Shares a sophisticated, high-fashion aesthetic with clean product photography, minimalist UI, and a strong focus on typography.
- **Gucci** — Employs an elevated e-commerce experience with rich visual content, structured layouts, and a predominantly monochromatic color scheme, similar to Adam Lippes's focus on product presentation.
- **The Row** — Features an extremely minimalist design, strong reliance on high-quality editorial photography, and a subdued color palette to convey luxury, matching Adam Lippes's refined visual language.
- **Ssense** — Utilizes a clean, editorial layout with a focus on product presentation, high-contrast typography, and a modern, understated aesthetic in the luxury retail space.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-ink: #000000;
  --color-paper-white: #fefcf8;
  --color-arctic-mist: #ffffff;
  --color-steel-gray: #4c4c4a;
  --color-coal: #121212;
  --color-carbon: #403f3e;
  --color-pale-ash: #b2b0ae;

  /* Typography — Font Families */
  --font-optima: 'Optima', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gtstandard-m: 'GTStandard-M', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.4;
  --text-body-sm: 11px;
  --leading-body-sm: 1.4;
  --text-body: 12px;
  --leading-body: 1.4;
  --text-body-lg: 13px;
  --leading-body-lg: 1.4;
  --text-heading-sm: 14px;
  --leading-heading-sm: 1.4;
  --text-heading: 16px;
  --leading-heading: 1.4;
  --text-heading-lg: 24px;
  --leading-heading-lg: 1.3;

  /* Typography — Weights */
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-9: 9px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-13: 13px;
  --spacing-14: 14px;
  --spacing-15: 15px;
  --spacing-16: 16px;
  --spacing-17: 17px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-30: 30px;
  --spacing-32: 32px;
  --spacing-40: 40px;

  /* Layout */
  --section-gap: 48px;
  --card-padding: 0px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-2xl: 16px;
  --radius-3xl: 40px;
  --radius-full: 1000px;

  /* Named Radii */
  --radius-cards: 0px;
  --radius-badges: 40px;
  --radius-buttons: 0px;
  --radius-ghost-button-accent: 1000px;

  /* Shadows */
  --shadow-sm: rgba(0, 0, 0, 0.05) 0px 4px 5px 0px;
  --shadow-lg: rgba(0, 0, 0, 0.15) 0px -8px 24px 0px;

  /* Surfaces */
  --surface-paper-white-canvas: #fefcf8;
  --surface-arctic-mist-cardinput: #ffffff;
  --surface-elevated-draweroverlay: #fefcf8;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-ink: #000000;
  --color-paper-white: #fefcf8;
  --color-arctic-mist: #ffffff;
  --color-steel-gray: #4c4c4a;
  --color-coal: #121212;
  --color-carbon: #403f3e;
  --color-pale-ash: #b2b0ae;

  /* Typography */
  --font-optima: 'Optima', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gtstandard-m: 'GTStandard-M', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.4;
  --text-body-sm: 11px;
  --leading-body-sm: 1.4;
  --text-body: 12px;
  --leading-body: 1.4;
  --text-body-lg: 13px;
  --leading-body-lg: 1.4;
  --text-heading-sm: 14px;
  --leading-heading-sm: 1.4;
  --text-heading: 16px;
  --leading-heading: 1.4;
  --text-heading-lg: 24px;
  --leading-heading-lg: 1.3;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-9: 9px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-13: 13px;
  --spacing-14: 14px;
  --spacing-15: 15px;
  --spacing-16: 16px;
  --spacing-17: 17px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-30: 30px;
  --spacing-32: 32px;
  --spacing-40: 40px;

  /* Border Radius */
  --radius-2xl: 16px;
  --radius-3xl: 40px;
  --radius-full: 1000px;

  /* Shadows */
  --shadow-sm: rgba(0, 0, 0, 0.05) 0px 4px 5px 0px;
  --shadow-lg: rgba(0, 0, 0, 0.15) 0px -8px 24px 0px;
}
```

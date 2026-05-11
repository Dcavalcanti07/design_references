# Ada — Style Reference
> Precise Analytical Blueprint

**Theme:** light

Ada's design system evokes a confident, analytical clarity with a white canvas, balanced geometric typography, and functional pops of color. The visual language centers on clean, structured UI elements that foreground information and interaction. It relies on subtle elevation and a clear hierarchy of text, creating an experience that feels precise and effortlessly organized. Color is used sparingly to highlight key actions and denote discrete sections or categories without overwhelming the primary achromatic palette.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Graphite | `linear-gradient(oklch(0.5555 0 0) 0%, oklch(0.331 0.0104 253.98) 100%)` | `--color-midnight-graphite` | Primary text, darkest surface borders, input text; Subtle transparent gradient overlay for hero sections, adding depth to background imagery |
| Vapor White | `#ffffff` | `--color-vapor-white` | Page backgrounds, card surfaces, primary content backgrounds |
| Cloud Gray | `#f9f9f9` | `--color-cloud-gray` | Secondary section backgrounds, subtle surface separation |
| Concrete Mist | `#d8d8d8` | `--color-concrete-mist` | Input borders, subtle dividers, decorative SVG fills |
| Deep Moss | `#00543d` | `--color-deep-moss` | Accent for certain button backgrounds, prominent borders around information cards, secondary button text |
| Sky Blue | `#abcbf9` | `--color-sky-blue` | Primary action button backgrounds, card borders for specific categories, interactive highlights |
| Lavender Bloom | `#ffbbfc` | `--color-lavender-bloom` | Card borders and associated button backgrounds for specific content categories |
| Goldenrod Glint | `#fce88b` | `--color-goldenrod-glint` | Card borders for distinctive content categorization |
| Dark Plum | `#392c38` | `--color-dark-plum` | Decorative background color, subtle accent for card borders |
| Neutral Green | `#95b7ae` | `--color-neutral-green` | Muted background for supporting content sections or cards |
| Pale Magenta | `#fbe0fa` | `--color-pale-magenta` | Muted background for supporting content sections or cards |
| Dusty Blue | `#dae7f9` | `--color-dusty-blue` | Muted background for supporting content sections or cards |
| #000000 | `#000000` | `--color-000000` | Decorative icon fills, occasional text where highest contrast is needed |

## Tokens — Typography

### Roobert — The sole typeface, used across all textual elements from headings to body copy and buttons. Its monolithic application creates a consistent, modern, and direct voice. Weight 400 is the standard, giving a clean appearance without excess flourish. · `--font-roobert`
- **Substitute:** system-ui
- **Weights:** 400
- **Sizes:** 12px, 14px, 15px, 16px, 18px, 20px, 24px, 32px, 36px, 48px, 60px, 72px
- **Line height:** 1.00, 1.11, 1.25, 1.33, 1.38, 1.40, 1.43, 1.56
- **Letter spacing:** normal
- **Role:** The sole typeface, used across all textual elements from headings to body copy and buttons. Its monolithic application creates a consistent, modern, and direct voice. Weight 400 is the standard, giving a clean appearance without excess flourish.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.56 | — | `--text-caption` |
| body | 16px | 1.43 | — | `--text-body` |
| subheading | 24px | 1.33 | — | `--text-subheading` |
| heading | 36px | 1.25 | — | `--text-heading` |
| heading-lg | 48px | 1.11 | — | `--text-heading-lg` |
| display | 72px | 1 | — | `--text-display` |

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
| 32 | 32px | `--spacing-32` |
| 36 | 36px | `--spacing-36` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 72 | 72px | `--spacing-72` |
| 96 | 96px | `--spacing-96` |
| 112 | 112px | `--spacing-112` |
| 120 | 120px | `--spacing-120` |
| 160 | 160px | `--spacing-160` |
| 176 | 176px | `--spacing-176` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 8px |
| inputs | 4px |
| buttons | 1.67772e+07px |
| navigation | 32px |

### Layout

- **Page max-width:** 1280px
- **Section gap:** 24px
- **Card padding:** 16px
- **Element gap:** 4px

## Components

### Primary Action Button
**Role:** Call to action button

Filled button with Sky Blue background, Midnight Graphite text, and a rounded pill shape. Padding: 4px vertical, 20px horizontal left, 4px horizontal right. Text is Roobert 400.

### Ghost Navigation Button
**Role:** Unfilled interactive element

Transparent background button with Midnight Graphite text, no border, and a pill shape. Padding: 0px vertical, 16px horizontal. Used for secondary actions or navigation links. Text is Roobert 400.

### Navigation Link Button
**Role:** In-text or inline navigation

Transparent background button with Midnight Graphite text, no border, and square corners. Padding: 0px. Used for contextual navigation or inline actions. Text is Roobert 400.

### Neutral Card
**Role:** Content container

Vapor White background, 8px border-radius, 32px padding on all sides, no shadow. Used for showcasing feature blocks or statistics.

### Bordered Card - Sky Blue
**Role:** Categorized content container

Transparent background, 8px border-radius, Sky Blue border, no shadow, no padding. Used to visually group related content or statistics, especially for '357%' ROI-like facts.

### Bordered Card - Lavender Bloom
**Role:** Categorized content container

Transparent background, 8px border-radius, Lavender Bloom border, no shadow, no padding. Used for '162%' CSAT stats.

### Bordered Card - Deep Moss
**Role:** Categorized content container

Transparent background, 8px border-radius, Deep Moss border, no shadow, no padding. Used for '8X' productivity stats.

### Form Input Field
**Role:** User data entry

Transparent background, 4px border-radius, Concrete Mist border, Midnight Graphite text. Padding: 8px vertical, 16px horizontal.

### Product Feature Card
**Role:** Showcasing product capabilities

Transparent background with a subtle Dark Plum overlay for opacity. 8px border-radius. No padding or shadow. Features imagery and text, with an arrow link.

## Do's and Don'ts

### Do
- Use Roobert 400 as the single font family for all text elements.
- Employ Vapor White (#ffffff) as the default page background and Cloud Gray (#f9f9f9) for alternating section backgrounds.
- Apply a 9999px radius (effectively a pill shape) to all primary and ghost buttons, not the literal 1.67772e+07px.
- Limit chromatic color usage to functional highlights: Sky Blue (#abcbf9) for primary actions, and Deep Moss (#00543d), Lavender Bloom (#ffbbfc), or Goldenrod Glint (#fce88b) for distinct card borders and corresponding statistics/categories.
- Maintain a comfortable density with 16px horizontal padding and 32px vertical padding as a baseline for internal card content.
- Use 8px border-radius for cards, ensuring a soft, modern container feel, and 4px for input fields for subtle distinction.
- Structure all page content within a 1280px max-width, maintaining a centered appearance.

### Don't
- Do not introduce new font families or weights beyond Roobert 400.
- Avoid decorative shadows; elevation should be minimal or absent, relying on background color shifts and subtle borders for separation.
- Do not use highly saturated colors for large background areas or extensive text blocks; reserve them for functional elements.
- Do not deviate from the established spacing units, particularly the 4px base and specific component paddings, as this will disrupt the comfortable density.
- Do not use generic button styles; always use either the filled Sky Blue primary action, the pill-shaped ghost link, or the square-cornered navigation link button.
- Do not create hero sections without the subtle linear-gradient overlay to provide depth and contrast for text.
- Do not use a solid border for inputs; use Concrete Mist (#d8d8d8) to maintain the light, soft aesthetic.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Vapor White Canvas | `#ffffff` | Base page background, primary content areas, and default card surfaces. |
| 1 | Cloud Gray Section | `#f9f9f9` | Alternating background for content sections to create subtle visual breaks. |
| 2 | Muted Accent Cards | `#95b7ae` | Backgrounds for specific supporting content cards, providing a soft thematic tint. |

## Imagery

The imagery on Ada's site combines product screenshots, candid photography, and subtle abstract graphics. Product screenshots are clean, often showing UI elements in context, sometimes with a frosted glass or transparent background effect. Photography is high-key and candid, featuring diverse teams or individuals in work settings, usually integrated or masked into sections rather than full-bleed lifestyle shots, serving an explanatory or testimonial role. Icons are outlined, simple, and monochromatic, with a moderate stroke weight, acting as functional rather than decorative elements. Visuals are used to explain and enhance, providing context for the AI product rather than just aesthetic appeal, creating a balanced visual density with text.

## Layout

The page maintains a centered, max-width layout of 1280px, creating a structured and contained experience. The hero section often features a full-bleed background image with a subtle gradient overlay, centering text and a prominent call to action. Section rhythm is driven by alternating Vapor White and Cloud Gray backgrounds, with consistent vertical spacing of 24px creating clear content blocks. Content is arranged primarily in vertical stacks and horizontal two or three-column grids for feature lists or statistics. Navigation is a sticky top bar with clearly defined menu items and call-to-action buttons, maintaining constant accessibility.

## Agent Prompt Guide

### Quick Color Reference
text: #0a0b0c
background: #ffffff
border: #d8d8d8
accent: #00543d
primary action: #abcbf9 (filled action)

### 3-5 Example Component Prompts
1. Create a Primary Action Button: #abcbf9 background, #0a0b0c text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Design a three-column feature card grid on a Cloud Gray (#f9f9f9) background. Each card is a Neutral Card with 32px padding, containing a Roobert 400 24px heading 'ACX Platform' and body text at 16px. Include a Ghost Navigation Button 'Learn More' at the bottom of each card, with a Midnight Graphite (#0a0b0c) border and text, pill-shaped.
3. Implement a statistics section with four items side-by-side, each within a Bordered Card with 8px radius, no padding, on a Vapor White background. The first uses a Deep Moss (#00543d) border, the second Lavender Bloom (#ffbbfc), the third Sky Blue (#abcbf9), and the fourth Goldenrod Glint (#fce88b). Each statistic has big number such as '8X' in Roobert 400 at 60px, Midnight Graphite (#0a0b0c), and a small caption in Roobert 400 at 16px, Midnight Graphite (#0a0b0c).

## Similar Brands

- **Intercom** — Shares a professional, modern aesthetic with highly structured UI, clear typography, and strategic use of a single brand accent color against a largely achromatic background.
- **Gong.io** — Employs an intelligent and data-driven visual style, mixing clean layouts with functional color splashes, and a focus on crisp typography for conveying information effectively.
- **Zendesk** — Features a light, spacious layout, combining soft neutrals with intentional bright accents to guide user interaction and reinforce brand elements, often with clear, geometric component styling.
- **Drift** — Uses a similar approach to white space and clear visual hierarchy, with a focus on product visuals and simple, accessible call-to-action treatments.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-graphite: #0a0b0c;
  --gradient-midnight-graphite: linear-gradient(oklch(0.5555 0 0) 0%, oklch(0.331 0.0104 253.98) 100%);
  --color-vapor-white: #ffffff;
  --color-cloud-gray: #f9f9f9;
  --color-concrete-mist: #d8d8d8;
  --color-deep-moss: #00543d;
  --color-sky-blue: #abcbf9;
  --color-lavender-bloom: #ffbbfc;
  --color-goldenrod-glint: #fce88b;
  --color-dark-plum: #392c38;
  --color-neutral-green: #95b7ae;
  --color-pale-magenta: #fbe0fa;
  --color-dusty-blue: #dae7f9;
  --color-000000: #000000;

  /* Typography — Font Families */
  --font-roobert: 'Roobert', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.56;
  --text-body: 16px;
  --leading-body: 1.43;
  --text-subheading: 24px;
  --leading-subheading: 1.33;
  --text-heading: 36px;
  --leading-heading: 1.25;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.11;
  --text-display: 72px;
  --leading-display: 1;

  /* Typography — Weights */
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-72: 72px;
  --spacing-96: 96px;
  --spacing-112: 112px;
  --spacing-120: 120px;
  --spacing-160: 160px;
  --spacing-176: 176px;

  /* Layout */
  --page-max-width: 1280px;
  --section-gap: 24px;
  --card-padding: 16px;
  --element-gap: 4px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-3xl: 28px;
  --radius-3xl-2: 32px;

  /* Named Radii */
  --radius-cards: 8px;
  --radius-inputs: 4px;
  --radius-buttons: 1.67772e+07px;
  --radius-navigation: 32px;

  /* Surfaces */
  --surface-vapor-white-canvas: #ffffff;
  --surface-cloud-gray-section: #f9f9f9;
  --surface-muted-accent-cards: #95b7ae;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-graphite: #0a0b0c;
  --color-vapor-white: #ffffff;
  --color-cloud-gray: #f9f9f9;
  --color-concrete-mist: #d8d8d8;
  --color-deep-moss: #00543d;
  --color-sky-blue: #abcbf9;
  --color-lavender-bloom: #ffbbfc;
  --color-goldenrod-glint: #fce88b;
  --color-dark-plum: #392c38;
  --color-neutral-green: #95b7ae;
  --color-pale-magenta: #fbe0fa;
  --color-dusty-blue: #dae7f9;
  --color-000000: #000000;

  /* Typography */
  --font-roobert: 'Roobert', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.56;
  --text-body: 16px;
  --leading-body: 1.43;
  --text-subheading: 24px;
  --leading-subheading: 1.33;
  --text-heading: 36px;
  --leading-heading: 1.25;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.11;
  --text-display: 72px;
  --leading-display: 1;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-72: 72px;
  --spacing-96: 96px;
  --spacing-112: 112px;
  --spacing-120: 120px;
  --spacing-160: 160px;
  --spacing-176: 176px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-3xl: 28px;
  --radius-3xl-2: 32px;
}
```

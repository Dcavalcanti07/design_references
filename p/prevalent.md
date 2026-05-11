# Prevalent — Style Reference
> Indigo & Violet Precision

**Theme:** light

Prevalent uses a confident, dark-to-light progression, blending a deep indigo hero with crisp white sections. Typography combines a classic serif for impactful headlines with a modern sans-serif for functional text. A single vivid violet acts as the primary accent, providing clear focal points against primarily monochrome UI elements, creating a sense of authority and precision without visual clutter.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Indigo | `#060b25` | `--color-midnight-indigo` | Hero and footer backgrounds, creating a deep, authoritative base for key sections |
| Action Violet | `#6360d8` | `--color-action-violet` | Primary call-to-action buttons, active states, and decorative heading accents – the central interactive color |
| Canvas White | `#ffffff` | `--color-canvas-white` | Main page and card backgrounds, primary surface for most content |
| Text Black | `#000000` | `--color-text-black` | Dark borders and separators for elevated surfaces and inverted UI. Do not promote it to the primary CTA color |
| Shadow Gray | `#383c51` | `--color-shadow-gray` | Subtle borders and muted helper text, providing soft visual separation |
| Light Highlight | `#dad9ed` | `--color-light-highlight` | Subtle background accents, like for highlighted text or small background areas on interactive elements |
| Muted Swiper Accent | `#007aff` | `--color-muted-swiper-accent` | Internal component accent (e.g., swiper pagination) — a secondary blue hue |

## Tokens — Typography

### Tiempos Headline — Prominent headings and display text – the traditional serif conveys authority and importance. Weight 400 at larger sizes allows it to command attention without being aggressive. · `--font-tiempos-headline`
- **Substitute:** Playfair Display
- **Weights:** 400
- **Sizes:** 16px, 30px, 45px, 48px, 50px, 80px
- **Line height:** 0.98, 1.00, 1.10, 1.55
- **Letter spacing:** -0.02
- **Role:** Prominent headings and display text – the traditional serif conveys authority and importance. Weight 400 at larger sizes allows it to command attention without being aggressive.

### Matter — Body text, links, buttons, and functional UI elements – its clean sans-serif ensures clarity and legibility across various scales. The subtle negative letter-spacing creates a refined, compact feel. · `--font-matter`
- **Substitute:** Inter
- **Weights:** 400, 500
- **Sizes:** 12px, 14px, 16px, 18px, 20px, 50px
- **Line height:** 1.00, 1.22, 1.33, 1.40, 1.43, 1.55, 1.60
- **Letter spacing:** -0.01
- **Role:** Body text, links, buttons, and functional UI elements – its clean sans-serif ensures clarity and legibility across various scales. The subtle negative letter-spacing creates a refined, compact feel.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.4 | — | `--text-caption` |
| body-sm | 14px | 1.4 | — | `--text-body-sm` |
| body | 16px | 1.4 | — | `--text-body` |
| body-lg | 18px | 1.4 | — | `--text-body-lg` |
| heading-sm | 20px | 1.4 | — | `--text-heading-sm` |
| heading | 50px | 1.3 | — | `--text-heading` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** spacious

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
| 48 | 48px | `--spacing-48` |
| 60 | 60px | `--spacing-60` |
| 80 | 80px | `--spacing-80` |
| 96 | 96px | `--spacing-96` |
| 144 | 144px | `--spacing-144` |

### Border Radius

| Element | Value |
|---------|-------|
| hero | 60px |
| cards | 10px |
| links | 4px |
| footer | 20px |
| buttons | 4px |

### Layout

- **Page max-width:** 1200px
- **Section gap:** 48px
- **Card padding:** 48px
- **Element gap:** 24px

## Components

### Primary Call to Action Button
**Role:** Key interactive elements for driving user action.

Filled with Action Violet (#6360d8), white text (#ffffff), 4px border-radius, and generous padding of 15px vertical, 48px horizontal. Text uses Matter, 500 weight.

### Header Navigation Link
**Role:** Top-level navigation items.

Ghost button style with transparent background, Text Black (#000000) or Canvas White (#ffffff) text (depending on header color), Matter font, 400 weight.

### Feature Card
**Role:** Content presentation for features or articles.

Canvas White (#ffffff) background, 10px border-radius, with no visible box shadow. No intrinsic padding, content manages its own spacing.

### Hero Section Card
**Role:** Transparent card elements within the hero section.

Transparent with a subtle white tint (rgba(255, 255, 255, 0.12)), 10px border-radius, no shadow.

### Inline Text Link
**Role:** Text-based navigation or references within body content.

Renders as Text Black (#000000) with no explicit decoration unless hovered/focused. When interactive, it may have a light background of Light Highlight (#dad9ed).

## Do's and Don'ts

### Do
- Use Tiempos Headline for all primary section titles and headings, leveraging its 400 weight for a refined impact.
- Apply Action Violet (#6360d8) exclusively for primary calls to action, interactive highlights, and brand accents; avoid using it for purely decorative, non-interactive elements.
- Set the main page background to Canvas White (#ffffff) for content sections, ensuring strong contrast with text.
- Maintain a clear visual hierarchy with Matter (400) for body text and Matter (500) for emphasized functional text like button labels.
- Implement a 4px border-radius for all primary interactive elements like buttons and input fields to ensure consistency.
- Utilize a 10px border-radius for cards and elevated containers to provide a soft, distinctive shape.
- Employ a base spacing unit of 4px, building up to 24px for element gaps and 48px for section and card padding.

### Don't
- Do not introduce new color hues; stick to the defined brand violet, neutrals, and the secondary swiper blue.
- Avoid using harsh shadows or heavy borders; prefer subtle separations and the transparent card style found in the hero.
- Do not deviate from the specified font families; avoid system fonts or other typefaces.
- Refrain from altering the letter-spacing values from the specified -0.02em and -0.01em for headings and body text respectively.
- Do not use generic gray values; adhere to Shadow Gray (#383c51) for muted text and borders.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Canvas White | `#ffffff` | Primary background for most page content. |
| 2 | Midnight Indigo | `#060b25` | Darker background for prominent sections like hero and footer, providing stark contrast. |
| 3 | Hero Transparent Overlay | `#ffffff1f` | Cards or containers within the hero, offering a subtle frosted appearance. |

## Imagery

The site heavily uses custom, stylized vector illustrations, particularly in the hero section. These illustrations feature human figures in bubble-like environments, interacting with futuristic technology, against cityscapes, creating a narrative of security and control. They are brightly colored, with clear outlines and solid fills, focusing on conceptual metaphors rather than realism. Photography, when present in article previews, is realistic and varied, but serves a secondary role to the brand's primary illustrative style. Icons are outlined, minimal, and monochromatic, complementing the clean UI.

## Layout

The page transitions from a full-bleed dark hero with centered headlines and subtle illustrative overlays, to a max-width 1200px contained layout for subsequent sections. Content arranges primarily in centered stacks or two-column text-left/image-right (or vice-versa) alternating patterns. Sections are fluid, with consistent vertical spacing that suggests a 'spacious' feel, and no explicit visual dividers between white sections. The header is sticky, white, with a centered logo and nav items, and a prominent Action Violet 'Get a demo' button.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #ffffff
border: #383c51
accent: #6360d8
primary action: #6360d8 (filled action)

Example Component Prompts:
1. Create a primary call to action button: filled Action Violet (#6360d8) background, Canvas White (#ffffff) text using Matter weight 500, 4px border-radius, 15px vertical padding, 48px horizontal padding.
2. Design a feature card: Canvas White (#ffffff) background, 10px border-radius, no shadow, with 48px internal padding. Title text is Matter 500 at 20px, body text is Matter 400 at 16px, both Text Black (#000000).
3. Generate a hero section 'Learn More' ghost button: transparent background, Canvas White (#ffffff) text using Matter 500, no border-radius. Include a subtle chevron icon next to the text. Use 12px vertical and 24px horizontal padding.

## Similar Brands

- **Darktrace** — Shares a sophisticated, modern dark-mode aesthetic for hero sections with a single vibrant accent color and strong typography.
- **Vanta** — Employs clean, spacious layouts with strong typographic hierarchy and a limited, functional color palette for SaaS product presentation.
- **Contrast Security** — Utilizes a balanced approach of dark and light sections, geometric illustrations, and a reserved brand accent color to highlight key information.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-indigo: #060b25;
  --color-action-violet: #6360d8;
  --color-canvas-white: #ffffff;
  --color-text-black: #000000;
  --color-shadow-gray: #383c51;
  --color-light-highlight: #dad9ed;
  --color-muted-swiper-accent: #007aff;

  /* Typography — Font Families */
  --font-tiempos-headline: 'Tiempos Headline', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-matter: 'Matter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.4;
  --text-body-sm: 14px;
  --leading-body-sm: 1.4;
  --text-body: 16px;
  --leading-body: 1.4;
  --text-body-lg: 18px;
  --leading-body-lg: 1.4;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.4;
  --text-heading: 50px;
  --leading-heading: 1.3;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-60: 60px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-144: 144px;

  /* Layout */
  --page-max-width: 1200px;
  --section-gap: 48px;
  --card-padding: 48px;
  --element-gap: 24px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 10px;
  --radius-2xl: 20px;
  --radius-full: 60px;

  /* Named Radii */
  --radius-hero: 60px;
  --radius-cards: 10px;
  --radius-links: 4px;
  --radius-footer: 20px;
  --radius-buttons: 4px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-midnight-indigo: #060b25;
  --surface-hero-transparent-overlay: #ffffff1f;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-indigo: #060b25;
  --color-action-violet: #6360d8;
  --color-canvas-white: #ffffff;
  --color-text-black: #000000;
  --color-shadow-gray: #383c51;
  --color-light-highlight: #dad9ed;
  --color-muted-swiper-accent: #007aff;

  /* Typography */
  --font-tiempos-headline: 'Tiempos Headline', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-matter: 'Matter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.4;
  --text-body-sm: 14px;
  --leading-body-sm: 1.4;
  --text-body: 16px;
  --leading-body: 1.4;
  --text-body-lg: 18px;
  --leading-body-lg: 1.4;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.4;
  --text-heading: 50px;
  --leading-heading: 1.3;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-60: 60px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-144: 144px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 10px;
  --radius-2xl: 20px;
  --radius-full: 60px;
}
```

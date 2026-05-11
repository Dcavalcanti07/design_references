# Shortcut — Style Reference
> organized data, muted luminescence

**Theme:** light

Shortcut employs a refined pragmatic aesthetic, blending ample white space with compact, data-rich componentry. A deep, saturated violet functions as the primary accent, providing clear visual anchors for actions and key information. Subtle background textures, crisp typography, and minimal elevation create an atmosphere of focused efficiency and quiet confidence. Interface elements prioritize informational density, presented in a clean, understated structure.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `linear-gradient(rgb(6, 8, 24), rgb(6, 6, 39))` | `--color-midnight-ink` | Darkest background for hero and footer sections, primary heading text on light backgrounds |
| Slate Text | `#686878` | `--color-slate-text` | Muted body text, secondary text, helper text, and subtle borders on light surfaces |
| Shortcut Violet | `#494bcb` | `--color-shortcut-violet` | Primary call-to-action buttons, active navigation states, and key interactive elements — a vivid, confident accent |
| Sunshine Yellow | `#ffde87` | `--color-sunshine-yellow` | Decorative highlights, warning badges, and accent text for a sense of urgency or attention |
| Iris Tint | `#9f7ad0` | `--color-iris-tint` | Subtle badge text and decorative icons – a lighter, more ethereal shade of violet |
| Link Blue | `#8a8ac6` | `--color-link-blue` | Interactive link text, outlined ghost buttons, and decorative strokes – a desaturated, readable blue |
| Jet Black | `#000000` | `--color-jet-black` | Primary text on light backgrounds, strong borders, and high-contrast UI elements |
| Canvas White | `#ffffff` | `--color-canvas-white` | Page background, card surfaces, ghost button backgrounds, and inverse text |
| Pewter Mist | `#f6f6fa` | `--color-pewter-mist` | Secondary background sections, subtle card backgrounds, and quiet badge fills |
| Ash Gray | `#6d737d` | `--color-ash-gray` | Subtle borders and dividers for definition without harshness |
| Charcoal Text | `#222222` | `--color-charcoal-text` | Dark borders and separators for elevated surfaces and inverted UI. Do not promote it to the primary CTA color |
| Warm Gray | `#333333` | `--color-warm-gray` | Subtle text for links and image descriptions |
| Shadow White | `#eaeaf7` | `--color-shadow-white` | A very subtle off-white background for specific button variants or hovered states |
| Soft Gray | `#aaaab0` | `--color-soft-gray` | Muted navigation text and placeholder content |

## Tokens — Typography

### Satoshi — The primary typeface for all text content, from headings to body text and UI elements. Its clean, geometric forms provide clarity and a modern sensibility, with varied weights supporting clear hierarchy across different text sizes. · `--font-satoshi`
- **Substitute:** Inter, Arial
- **Weights:** 500, 700
- **Sizes:** 10px, 13px, 14px, 15px, 17px, 19px, 21px, 46px, 61px
- **Line height:** 1.10, 1.25, 1.27, 1.28, 1.30, 1.50, 1.60, 1.80
- **Letter spacing:** -0.0200em
- **Role:** The primary typeface for all text content, from headings to body text and UI elements. Its clean, geometric forms provide clarity and a modern sensibility, with varied weights supporting clear hierarchy across different text sizes.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.5 | -0.2px | `--text-caption` |
| heading | 21px | 1.28 | -0.42px | `--text-heading` |
| heading-lg | 46px | 1.25 | -0.92px | `--text-heading-lg` |
| display | 61px | 1.1 | -1.22px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 8 | 8px | `--spacing-8` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 76 | 76px | `--spacing-76` |
| 84 | 84px | `--spacing-84` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 15.24px |
| badges | 35.81px |
| buttons | 7.62px |
| default | 7.62px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| md | `rgba(0, 0, 0, 0.04) 0px 20px 13px 0px` | `--shadow-md` |

### Layout

- **Page max-width:** 1200px
- **Section gap:** 73px
- **Card padding:** 19px
- **Element gap:** 4px

## Components

### Primary Filled Button
**Role:** Main call-to-action.

Solid Shortcut Violet (#494bcb) background with Canvas White (#ffffff) text, 7.62px border-radius, and 9.52px vertical / 19.05px horizontal padding. Font is Satoshi, weight 700.

### Secondary Ghost Button
**Role:** Complementary actions.

Transparent background with Shortcut Violet (#494bcb) text, 7.62px border-radius, and 9.52px vertical / 19.05px horizontal padding. Background tinted rgba(73, 75, 203, 0.07). Font is Satoshi, weight 500.

### Text Outline Button
**Role:** Minimalist interactive elements.

Transparent background with Charcoal Text (#222222) color, a 1px border of Charcoal Text (#222222), 7.62px border-radius, and 5.71px vertical / 11.43px horizontal padding. Font is Satoshi, weight 500.

### Hero Light Button
**Role:** Action for dark hero sections.

Translucent white background rgba(255, 255, 255, 0.16) with Canvas White (#ffffff) text, 7.62px border-radius, and 9.52px vertical / 19.05px horizontal padding. Font is Satoshi, weight 700.

### Feature Card (Subtle Shadow)
**Role:** Content modules requiring light elevation.

Canvas White (#ffffff) background, 9.52px border-radius, and a soft shadow of rgba(0, 0, 0, 0.04) 0px 20px 13px 0px.

### Container Card (No Shadow)
**Role:** Grouping related content without visual prominence.

Pewter Mist (#f6f6fa) background with 15.24px border-radius. No padding or shadow is applied directly to the card surface.

### Label Badge
**Role:** Informational tags and status indicators.

Pewter Mist (#f6f6fa) background with Jet Black (#000000) text, 35.81px border-radius, and 0px vertical / 15.24px horizontal padding. Font is Satoshi, weight 500.

### Warning Badge
**Role:** Highlighting warning or notable statuses.

Translucent blue background rgba(62, 139, 229, 0.14) with Canvas White (#ffffff) text, a 35.81px border-radius, and 0px vertical / 15.24px horizontal padding.

## Do's and Don'ts

### Do
- Prioritize Canvas White (#ffffff) for primary page backgrounds, reserving Midnight Ink (#08093f) for strong hero sections or footers.
- Use Shortcut Violet (#494bcb) exclusively for primary interactive elements, ensuring its impact as the main brand accent.
- Apply Satoshi font with letter-spacing -0.0200em consistently across all text sizes for a refined reading experience.
- Implement a default border-radius of 7.62px for buttons, images, and general interactive elements, with 15.24px for larger content cards.
- Maintain a compact density, using 4px `elementGap` for tight vertical/horizontal rhythm between small components and text blocks.
- Utilize Slate Text (#686878) for subheadings and body copy to provide sufficient contrast without overpowering main headlines.
- For elevated content cards, use the soft shadow rgba(0, 0, 0, 0.04) 0px 20px 13px 0px on Canvas White (#ffffff) surfaces, not on tinted backgrounds.

### Don't
- Do not use multiple saturated colors for primary actions; Shortcut Violet (#494bcb) should be the singular choice.
- Avoid heavy drop shadows or decorative gradients on general UI components; elevation should remain minimal and subtle.
- Do not introduce new font families; rely solely on Satoshi with its defined weights and line heights.
- Refrain from using overly large gaps between elements or sections that break the compact flow; adhere to the defined spacing scale.
- Do not treat different shades of gray as brand colors; ensure they serve clear functional roles like background, text, or border.
- Avoid sharp, un-rounded corners; adhere to the specified border radii for a consistent, approachable aesthetic.
- Do not place primary content or detailed text on dark backgrounds; reserve Midnight Ink (#08093f) for bold, brief statements and large headlines.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Page Canvas | `#ffffff` | Dominant background for most page content. |
| 1 | Secondary Section | `#f6f6fa` | Alternating background for content sections and subtle card backgrounds. |
| 2 | Elevated Card | `#ffffff` | Cards or containers that need slight visual separation and depth. |
| 3 | Hero/Footer Wash | `#08093f` | Dark, immersive backgrounds for prominent hero sections and footers. |

## Elevation

- **Feature Card (Subtle Shadow):** `rgba(0, 0, 0, 0.04) 0px 20px 13px 0px`

## Imagery

The visual language predominantly features high-contrast product screenshots or UI embeds, often placed within contained, soft-cornered frames. These visuals are typically functional and explanatory rather than purely decorative, showcasing the software's interface directly. Icons are outlined, minimal, and monochromatic, aligning with the clean UI. Imagery is primarily used to illustrate features and functionality, maintaining a high density in sections dedicated to product showcasing, while more abstract or illustrative elements are rare, with a focus on demonstrating utility.

## Layout

The layout is primarily a max-width contained grid, typically around 1200px, with content centered. The hero section can be full-bleed with a dark background (Midnight Ink #08093f) and centered large headlines. Sections follow a rhythm of alternating light (Canvas White #ffffff) and subtly tinted (Pewter Mist #f6f6fa) backgrounds, providing clear visual breaks. Content is arranged in flexible multi-column grids, often a two-column layout with text on one side and a product visual on the other. Feature sections frequently use three-column card grids. The density is compact, ensuring information is presented efficiently with controlled breathing room. Navigation is a persistent top bar featuring the brand logo, primary navigation links, and distinct 'Get started' and 'Log in' buttons.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #ffffff
border: #686878
accent: #8a8ac6
primary action: #494bcb (filled action)

3-5 Example Component Prompts:
1. Create a Primary Action Button: #494bcb background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Create a feature card: Canvas White (#ffffff) background, 9.52px border-radius, soft shadow `rgba(0, 0, 0, 0.04) 0px 20px 13px 0px`. Heading `heading-sm` size in Jet Black (#000000), body text in Slate Text (#686878). Use 19px internal padding.
4. Create a status badge: Pewter Mist (#f6f6fa) background, 35.81px border-radius, Jet Black (#000000) text (caption size), 0px vertical / 15.24px horizontal padding. Content: 'New'.

## Similar Brands

- **Jira** — Clear, organized layout focused on project management, with a similar approach to white space and data density.
- **Monday.com** — Uses a clean UI with a single strong brand accent color for actions and highlights against a largely neutral palette.
- **Asana** — Employs a light, spacious design with prominent product screenshots and a pragmatic, functional aesthetic.
- **ClickUp** — Focuses on detailed product UI within a clean framework, using color for functional emphasis rather than decoration.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #08093f;
  --gradient-midnight-ink: linear-gradient(rgb(6, 8, 24), rgb(6, 6, 39));
  --color-slate-text: #686878;
  --color-shortcut-violet: #494bcb;
  --color-sunshine-yellow: #ffde87;
  --color-iris-tint: #9f7ad0;
  --color-link-blue: #8a8ac6;
  --color-jet-black: #000000;
  --color-canvas-white: #ffffff;
  --color-pewter-mist: #f6f6fa;
  --color-ash-gray: #6d737d;
  --color-charcoal-text: #222222;
  --color-warm-gray: #333333;
  --color-shadow-white: #eaeaf7;
  --color-soft-gray: #aaaab0;

  /* Typography — Font Families */
  --font-satoshi: 'Satoshi', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --tracking-caption: -0.2px;
  --text-heading: 21px;
  --leading-heading: 1.28;
  --tracking-heading: -0.42px;
  --text-heading-lg: 46px;
  --leading-heading-lg: 1.25;
  --tracking-heading-lg: -0.92px;
  --text-display: 61px;
  --leading-display: 1.1;
  --tracking-display: -1.22px;

  /* Typography — Weights */
  --font-weight-medium: 500;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-76: 76px;
  --spacing-84: 84px;

  /* Layout */
  --page-max-width: 1200px;
  --section-gap: 73px;
  --card-padding: 19px;
  --element-gap: 4px;

  /* Border Radius */
  --radius-lg: 7.61927px;
  --radius-xl: 11.4289px;
  --radius-2xl: 15.2385px;
  --radius-3xl: 35.8106px;

  /* Named Radii */
  --radius-cards: 15.24px;
  --radius-badges: 35.81px;
  --radius-buttons: 7.62px;
  --radius-default: 7.62px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.04) 0px 20px 13px 0px;

  /* Surfaces */
  --surface-page-canvas: #ffffff;
  --surface-secondary-section: #f6f6fa;
  --surface-elevated-card: #ffffff;
  --surface-herofooter-wash: #08093f;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #08093f;
  --color-slate-text: #686878;
  --color-shortcut-violet: #494bcb;
  --color-sunshine-yellow: #ffde87;
  --color-iris-tint: #9f7ad0;
  --color-link-blue: #8a8ac6;
  --color-jet-black: #000000;
  --color-canvas-white: #ffffff;
  --color-pewter-mist: #f6f6fa;
  --color-ash-gray: #6d737d;
  --color-charcoal-text: #222222;
  --color-warm-gray: #333333;
  --color-shadow-white: #eaeaf7;
  --color-soft-gray: #aaaab0;

  /* Typography */
  --font-satoshi: 'Satoshi', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --tracking-caption: -0.2px;
  --text-heading: 21px;
  --leading-heading: 1.28;
  --tracking-heading: -0.42px;
  --text-heading-lg: 46px;
  --leading-heading-lg: 1.25;
  --tracking-heading-lg: -0.92px;
  --text-display: 61px;
  --leading-display: 1.1;
  --tracking-display: -1.22px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-76: 76px;
  --spacing-84: 84px;

  /* Border Radius */
  --radius-lg: 7.61927px;
  --radius-xl: 11.4289px;
  --radius-2xl: 15.2385px;
  --radius-3xl: 35.8106px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.04) 0px 20px 13px 0px;
}
```

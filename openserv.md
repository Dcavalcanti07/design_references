# OpenServ — Style Reference
> White space innovation laboratory

**Theme:** light

OpenServ embodies a sharp, technical elegance with abundant whitespace and precise typography. It balances the starkness of monochrome UI with vibrant digital blues and greens, creating an atmosphere of focused innovation. Components feature soft, rounded corners and a ghost-like transparency, contributing to a lightweight, almost ethereal feel across interactive elements. The overall impression is one of restraint and clarity, prioritizing content against a clean backdrop.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, elevated card backgrounds, key UI elements requiring visual separation. Provides a sharp, bright foundation for content |
| Ink Black | `#000000` | `--color-ink-black` | Primary text, strong borders, dark overlay backgrounds. Provides high contrast against light surfaces, defining structure and readability |
| Fog Gray | `#f5f5f5` | `--color-fog-gray` | Secondary card surfaces, subtle background distinctions for content blocks. Offers a slight visual break from the primary canvas without introducing saturation |
| Steel Gray | `#a6a6a6` | `--color-steel-gray` | Muted text, navigation links, secondary borders. Provides hierarchical distinction for less critical information or inactive states |
| Graphite | `#4d4d4d` | `--color-graphite` | Subtle text, accent borders, less prominent information. Slightly darker than Steel Gray for increased legibility in specific contexts |
| Deep Blue | `#5f79ff` | `--color-deep-blue` | Primary action buttons, interactive elements, accent borders, headers. A vivid, almost neon blue that signifies interaction and brand presence |
| Electric Green | `#01fe93` | `--color-electric-green` | Green action color for filled buttons, selected navigation states, and focused conversion moments |

## Tokens — Typography

### OS Studio Grotesk — Primary UI text, navigation, links, and headings. Its distinct font features convey a modern, technical precision, while varied letter-spacing maintains legibility across sizes. · `--font-os-studio-grotesk`
- **Weights:** 400
- **Sizes:** 12px, 13px, 15px, 20px, 22px, 24px, 30px, 40px, 72px
- **Line height:** 0.90, 1.00, 1.10, 1.14, 1.18, 1.25, 1.40
- **Letter spacing:** -0.0200em at 72px, -0.0170em at 40px, 0.0080em at 12px
- **OpenType features:** `"blwf" on, "cv03" on, "cv04" on, "cv09" on, "cv11" on`
- **Role:** Primary UI text, navigation, links, and headings. Its distinct font features convey a modern, technical precision, while varied letter-spacing maintains legibility across sizes.

### OS Chronik — Headlines and prominent messages. The light weight (300) for large text creates a sense of authority through sophisticated understatement, rather than bold shouting. · `--font-os-chronik`
- **Weights:** 300
- **Sizes:** 18px, 24px, 34px, 72px
- **Line height:** 0.90, 1.00, 1.10, 1.20
- **Letter spacing:** -0.0200em at 72px, -0.0170em at 34px, -0.0150em at 24px
- **OpenType features:** `"blwf" on, "cv03" on, "cv04" on, "cv09" on, "cv11" on`
- **Role:** Headlines and prominent messages. The light weight (300) for large text creates a sense of authority through sophisticated understatement, rather than bold shouting.

### sans-serif — Fallback and minimal text, typically system-level information. Used sparingly where custom branding is less critical. · `--font-sans-serif`
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.20
- **Letter spacing:** normal
- **Role:** Fallback and minimal text, typically system-level information. Used sparingly where custom branding is less critical.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| subheading | 18px | 1.2 | -0.27px | `--text-subheading` |
| heading-sm | 24px | 1.1 | -0.36px | `--text-heading-sm` |
| heading | 40px | 1 | -0.68px | `--text-heading` |
| display | 72px | 0.9 | -1.44px | `--text-display` |

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
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 60 | 60px | `--spacing-60` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 120 | 120px | `--spacing-120` |

### Border Radius

| Element | Value |
|---------|-------|
| card | 16px |
| pill | 100px |
| buttons | 12px |
| default | 16px |
| heroElement | 40px |
| interactiveElements | 12px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| xl | `rgba(0, 0, 0, 0.1) 0px 0px 48px 0px` | `--shadow-xl` |

### Layout

- **Section gap:** 40px
- **Card padding:** 24px
- **Element gap:** 10px

## Components

### Filled Primary Button
**Role:** Main call to action

Filled with Deep Blue (#5f79ff), white text, 14px border radius. Padding: 12px vertical, 24px horizontal. Uses OS Studio Grotesk 400.

### Pill Primary Button
**Role:** Prominent action with soft, rounded aesthetics

Filled with Deep Blue (#5f79ff), white text, 100px border radius. Padding: 10px vertical, 18px horizontal. Uses OS Studio Grotesk 400.

### Ghost Card Button
**Role:** Secondary action within cards, transparent and subtle

Background rgba(244, 244, 244, 0.35) (a semi-transparent Fog Gray), primary text color, 12px border radius. Generous padding: 32px top, 48px right, 48px bottom, 48px left. Uses OS Studio Grotesk 400.

### Subtle Dark Button
**Role:** Call to action on dark backgrounds, minimal visual weight

Background rgba(0, 0, 0, 0.9), text uses Ink Black. 40px border radius. No explicit padding, relies on content spacing.

### Hero Feature Card
**Role:** Displays key features or content blocks with a clean appearance.

Background Fog Gray (#f5f5f5), 16px border radius, no shadow. Content padding 0px.

### Content Card
**Role:** Standard content containers with a subtle background.

Background Fog Gray (#f5f5f5), 12px border radius, no shadow. Padding: 24px vertical, 20px horizontal.

### Elevated Navigation
**Role:** Top navigation bar for global site access.

Blurred background with `backdrop-filter: blur(10px)`. rgba(0, 0, 0, 0.1) 0px 0px 48px 0px shadow. White text for active items, Steel Gray for inactive. 16px border radius.

## Do's and Don'ts

### Do
- Prioritize Canvas White (#ffffff) for all main page backgrounds to maintain a clean, expansive feel.
- Use Deep Blue (#5f79ff) exclusively for primary interactive elements, ensuring all main calls to action are immediately recognizable.
- Apply OS Chronik Light (300) for all major headlines at 34px or larger, with letter spacing from -0.015em to -0.02em, to create a sense of understated authority.
- Implement soft, rounded corners for all interactive elements and content containers, specifically 12px for buttons and 16px for cards, using the exact values from 'spacing.radius'.
- Employ Steel Gray (#a6a6a6) for navigation links and secondary body text to establish clear visual hierarchy without distracting from primary content.
- Maintain a comfortable density with a base unit of 4px for all spacing decisions, specifically using card padding of 24px and element gaps of 10px.
- Utilize rgba(0, 0, 0, 0.1) 0px 0px 48px 0px for any elevated elements, ensuring a consistent, diffused shadow effect.

### Don't
- Never use highly saturated colors outside the defined brand (#5f79ff) and accent (#01fe93) palettes; maintain a largely achromatic scheme.
- Avoid harsh, square corners; ensure all containers and interactive elements adhere to the specified radii (12px, 16px, 40px, 100px).
- Do not introduce strong, dark backgrounds beyond specific focal sections; the site's primary theme is light.
- Refrain from using heavily weighted fonts for large headlines; OS Chronik 300 should convey confidence, not aggression.
- Do not deviate from the defined letter-spacing values for OS Studio Grotesk and OS Chronik; precise tracking is key to the typographic identity.
- Avoid complex shadow systems; stick to the single, diffused shadow outlined for elevation to maintain a lightweight UI.
- Do not clutter layouts with too many competing elements; favor ample whitespace and clear visual separation for content blocks.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas White | `#ffffff` | Primary page background |
| 1 | Fog Gray | `#f5f5f5` | Secondary card surfaces and subtle content block backgrounds |
| 2 | Elevated Navigation | `#ffffffcc` | Floating navigation bar with blur effect |

## Elevation

- **Elevated Navigation:** `rgba(0, 0, 0, 0.1) 0px 0px 48px 0px`

## Imagery

Imagery is functional and abstract, focusing on product-related visuals or iconic representations rather than photography. Illustrations are minimal, often geometric or abstract, using brand colors to highlight concepts. Icons are generally filled and monochromatic, or utilize the signature brand blue. Visuals are contained and typically have rounded corners, integrating seamlessly into the UI rather than breaking out as full-bleed elements. The density is moderate, with images serving as explanatory or decorative accents rather than dominating content.

## Layout

The page maintains a full-bleed layout for the background, with content typically centered and constrained within a comfortable width, though no explicit maximum width is detected, implied by the generous whitespace. The hero features a large, often dark, centered headline, setting a stark, modern tone. Sections generally follow a consistent vertical rhythm, often featuring alternating white and Fog Gray backgrounds to delineate content blocks. Content is arranged in alternating text-left/image-right patterns or multi-column card grids, providing structured information. Navigation is a simple sticky top bar with minimal links, complementing the overall sparse and clear aesthetic.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #ffffff
border: #000000
accent: #01fe93
primary action: #5f79ff (filled action)

Example Component Prompts:
1. Create a primary action button: Fill with #5f79ff, text #FFFFFF, 14px border radius, 12px vertical padding, 24px horizontal padding. Text 'Open App' in OS Studio Grotesk 400, 15px.
2. Create a content card: Background #f5f5f5, 16px border radius, no shadow. Content area OS Studio Grotesk 400, 13px, #000000. Text 'Whitepaper summary here.'
3. Create a hero headline: Text 'Build · Launch · Run' in OS Chronik 300, 72px, #000000, letter-spacing -1.44px.
4. Create a secondary navigation link: Text 'Builders' in OS Studio Grotesk 400, 12px, #a6a6a6.

## Similar Brands

- **Stripe** — Shares a clean, minimalist aesthetic with abundant whitespace, subtle grays, and a precise typographic system for data-heavy interfaces.
- **Linear** — Exhibits a similar focus on sharp, functional UI, restrained use of color for interaction, and a modern, compact sans-serif typography.
- **Vercel** — Features a strong emphasis on developer tools UI, using a largely monochrome palette accented by vivid greens/blues for active states and brand moments.
- **Figma** — Mirrors the use of a clean white canvas broken up by subtle card-like surfaces and distinct, almost 'digital' accent colors for core interactions.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ink-black: #000000;
  --color-fog-gray: #f5f5f5;
  --color-steel-gray: #a6a6a6;
  --color-graphite: #4d4d4d;
  --color-deep-blue: #5f79ff;
  --color-electric-green: #01fe93;

  /* Typography — Font Families */
  --font-os-studio-grotesk: 'OS Studio Grotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-os-chronik: 'OS Chronik', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-subheading: 18px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.27px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.1;
  --tracking-heading-sm: -0.36px;
  --text-heading: 40px;
  --leading-heading: 1;
  --tracking-heading: -0.68px;
  --text-display: 72px;
  --leading-display: 0.9;
  --tracking-display: -1.44px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;

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
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-120: 120px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 24px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-3xl: 40px;
  --radius-full: 100px;
  --radius-full-2: 1000px;

  /* Named Radii */
  --radius-card: 16px;
  --radius-pill: 100px;
  --radius-buttons: 12px;
  --radius-default: 16px;
  --radius-heroelement: 40px;
  --radius-interactiveelements: 12px;

  /* Shadows */
  --shadow-xl: rgba(0, 0, 0, 0.1) 0px 0px 48px 0px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-fog-gray: #f5f5f5;
  --surface-elevated-navigation: #ffffffcc;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ink-black: #000000;
  --color-fog-gray: #f5f5f5;
  --color-steel-gray: #a6a6a6;
  --color-graphite: #4d4d4d;
  --color-deep-blue: #5f79ff;
  --color-electric-green: #01fe93;

  /* Typography */
  --font-os-studio-grotesk: 'OS Studio Grotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-os-chronik: 'OS Chronik', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-subheading: 18px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.27px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.1;
  --tracking-heading-sm: -0.36px;
  --text-heading: 40px;
  --leading-heading: 1;
  --tracking-heading: -0.68px;
  --text-display: 72px;
  --leading-display: 0.9;
  --tracking-display: -1.44px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-120: 120px;

  /* Border Radius */
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-3xl: 40px;
  --radius-full: 100px;
  --radius-full-2: 1000px;

  /* Shadows */
  --shadow-xl: rgba(0, 0, 0, 0.1) 0px 0px 48px 0px;
}
```

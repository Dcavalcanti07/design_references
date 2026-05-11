# Coda — Style Reference
> Crisp canvas, structured workspace.

**Theme:** light

Coda's design system revolves around a crisp, functional aesthetic, emphasizing readability and clear interaction. It pairs a stark monochrome palette with a warm, inviting accent background for key sections. Typography is confident and impactful for headlines, complemented by a versatile sans-serif for body text. Components are well-defined with consistent border radii and subtle elevations, guiding users through structured content.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#212121` | `--color-midnight-ink` | Primary text, strong borders, dark icons, structural elements |
| White Canvas | `#ffffff` | `--color-white-canvas` | Page backgrounds, card surfaces, ghost button backgrounds, primary action text |
| Amber Glow | `#fff6ec` | `--color-amber-glow` | Accent surface for hero sections and footers, creating a warm contrast |
| Soft Gray | `#e0e0e0` | `--color-soft-gray` | Subtle borders, button shadows, secondary dividers |
| Slate Text | `#666666` | `--color-slate-text` | Muted body text, secondary borders |
| Ash Text | `#8e8e8e` | `--color-ash-text` | Helper text, tertiary navigation links, fine borders |
| Obsidian | `#000000` | `--color-obsidian` | Primary action button background, deep shadows, bold icons |
| Warm Gray Text | `#444444` | `--color-warm-gray-text` | Secondary button text, specific UI elements |
| Sunset Orange | `#ee5a29` | `--color-sunset-orange` | Highlight elements, specific headings, decorative accents — a strong, vivid punctuation mark |

## Tokens — Typography

### Calibre-R — Dominant headlines, creating impact with strong, heavy presence. · `--font-calibre-r`
- **Substitute:** Montserrat
- **Weights:** 700
- **Sizes:** 38px, 52px, 72px
- **Line height:** 1.00, 1.10
- **Letter spacing:** -0.045em at 72px, -0.035em at 52px, -0.025em at 38px
- **Role:** Dominant headlines, creating impact with strong, heavy presence.

### Inter — Versatile text for body copy, navigation, buttons, and detailed UI elements. Optimized for readability across sizes. · `--font-inter`
- **Substitute:** Inter
- **Weights:** 400, 600, 700
- **Sizes:** 10px, 14px, 16px, 20px, 22px
- **Line height:** 1.20, 1.38, 1.43, 1.50, 1.55
- **Letter spacing:** -0.03em at 22px, -0.01em at 20px, 0.01em at 14px and 16px
- **Role:** Versatile text for body copy, navigation, buttons, and detailed UI elements. Optimized for readability across sizes.

### Tiempos-Headline — Subtler, elegant headlines, delivering authority through restraint rather than visual weight. · `--font-tiempos-headline`
- **Substitute:** Playfair Display
- **Weights:** 300
- **Sizes:** 38px
- **Line height:** 1.37
- **Letter spacing:** -0.01em
- **Role:** Subtler, elegant headlines, delivering authority through restraint rather than visual weight.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.55 | — | `--text-caption` |
| body-sm | 14px | 1.5 | 0.01px | `--text-body-sm` |
| body | 16px | 1.43 | 0.01px | `--text-body` |
| subheading | 20px | 1.38 | -0.01px | `--text-subheading` |
| heading-sm | 22px | 1.2 | -0.03px | `--text-heading-sm` |
| heading | 38px | 1.37 | -0.025px | `--text-heading` |
| heading-lg | 52px | 1.1 | -0.035px | `--text-heading-lg` |
| display | 72px | 1 | -0.045px | `--text-display` |

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
| 60 | 60px | `--spacing-60` |
| 72 | 72px | `--spacing-72` |
| 96 | 96px | `--spacing-96` |
| 164 | 164px | `--spacing-164` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 8px |
| icons | 44px |
| buttons | 8px |
| smallElements | 4px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgb(33, 33, 33) 0px 0px 0px 1.5px inset` | `--shadow-subtle` |
| lg | `rgba(0, 0, 0, 0.06) 0px 12px 24px -5px, rgba(0, 0, 0, 0.0...` | `--shadow-lg` |
| subtle-2 | `rgb(224, 224, 224) 0px 0px 0px 1.5px inset` | `--shadow-subtle-2` |
| subtle-3 | `rgb(0, 0, 0) 8px 8px 0px 0px` | `--shadow-subtle-3` |
| xl | `rgba(0, 0, 0, 0.06) 0px 18px 36px -6px, rgba(0, 0, 0, 0.0...` | `--shadow-xl` |

### Layout

- **Section gap:** 113px
- **Card padding:** 16px
- **Element gap:** 8px

## Components

### Primary Filled Button
**Role:** Primary call to action.

Solid Obsidian background (#000000), White Canvas text (#ffffff), 8px border-radius, 12px horizontal padding, 8px vertical padding. Inset shadow on focus: rgb(33, 33, 33) 0px 0px 0px 1.5px inset.

### Ghost Button
**Role:** Secondary action or navigation.

Transparent background (rgba(0,0,0,0)), Midnight Ink text and border (#212121), 8px border-radius, varied padding (8-12px horizontal, 8px vertical). Inset shadow on focus: rgb(33, 33, 33) 0px 0px 0px 1.5px inset.

### Tertiary White Button
**Role:** Less prominent actions on contrasting backgrounds.

White Canvas background (#ffffff), Midnight Ink text and border (#212121), 8px border-radius, 12px horizontal padding, 8px vertical padding. Inset shadow on focus: rgb(224, 224, 224) 0px 0px 0px 1.5px inset.

### Compact Ghost Button
**Role:** Smaller, less emphatic actions, often within product UI.

Semi-transparent White Canvas background (rgba(255, 255, 255, 0.85)), Warm Gray Text (#444444) for text and border, 8px border-radius, 20px horizontal padding, 8px vertical padding.

### Feature Card
**Role:** Content container for showcasing features or information.

White Canvas background (#ffffff), 8px border-radius, 16px internal padding. Subtle elevation: rgba(0, 0, 0, 0.06) 0px 12px 24px -5px, rgba(0, 0, 0, 0.06) 0px 5px 10px -6px.

### Modal Overlay Card
**Role:** Elevated content like pop-ups or detailed views.

White Canvas background (#ffffff), 8px border-radius. Pronounced elevation: rgba(0, 0, 0, 0.06) 0px 18px 36px -6px, rgba(0, 0, 0, 0.06) 0px 6px 12px -6px.

## Do's and Don'ts

### Do
- Prioritize a clean, spacious layout using White Canvas (#ffffff) for primary backgrounds and Amber Glow (#fff6ec) for accent sections.
- Use Calibre-R (or Montserrat) 700 for all major headings, applying precise negative letter-spacing for impact.
- Limit the use of Sunset Orange (#ee5a29) to specific highlight elements or decorative text, preventing overuse.
- Employ consistent 8px border-radius for all interactive elements and content containers (buttons, cards, images).
- Use Obsidian (#000000) for primary call-to-action buttons; for secondary actions, use either Ghost Buttons (Midnight Ink #212121 outline) or Tertiary White Buttons.
- Maintain a comfortable element gap of 8px (base unit 4px) for most UI components and content structures.
- Apply subtle shadow styles from the component list for cards and elevated elements to imply hierarchy without heavy visuals.

### Don't
- Avoid arbitrary color choices; all colors must map to a defined role within the palette.
- Do not use generic system fonts; stick to Inter for body and UI text, and Montserrat (or Calibre-R) for headlines.
- Do not vary border-radius on buttons or cards; maintain the strict 8px rounding.
- Avoid clutter; ensure page content has sufficient negative space, adhering to a comfortable density.
- Do not use highly saturated colors other than Sunset Orange (#ee5a29); the system favors a monochrome base.
- Do not create new shadow styles; use the defined elevation tokens for consistency.
- Do not use arbitrary padding values; adhere to the 4px base unit and derived spacing tokens like 12px, 16px horizontal, and 8px vertical for buttons.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | White Canvas | `#ffffff` | Primary page background and default surface for content. |
| 1 | Amber Glow Section | `#fff6ec` | Accent background for hero sections or footers, providing visual warmth and distinction. |
| 2 | Elevated Card | `#ffffff` | Interactive elements or content groupings that subtly stand out from the canvas with a light shadow. |

## Elevation

- **Ghost Button (focused/active):** `rgb(33, 33, 33) 0px 0px 0px 1.5px inset`
- **Tertiary White Button (focused/active):** `rgb(224, 224, 224) 0px 0px 0px 1.5px inset`
- **Feature Card:** `rgba(0, 0, 0, 0.06) 0px 12px 24px -5px, rgba(0, 0, 0, 0.06) 0px 5px 10px -6px`
- **Decorative Block Shadow:** `rgb(0, 0, 0) 8px 8px 0px 0px`
- **Modal/Overlay Card:** `rgba(0, 0, 0, 0.06) 0px 18px 36px -6px, rgba(0, 0, 0, 0.06) 0px 6px 12px -6px`

## Imagery

Product screenshots are frequently used, often framed within a minimalist device UI or presented in an overlapping, layered fashion to convey dynamism and feature richness. These are typically contained within the primary content area, not full-bleed. Icons are simple, filled, and monochromatic, often using Midnight Ink (#212121), serving a functional role as visual aids rather than decorative elements. There is minimal use of standalone photography or complex illustrations, emphasizing the core UI and product experience.

## Layout

The page model is primarily a max-width contained layout, likely around 1200px, centered on a White Canvas background. The hero section often features a full-bleed Amber Glow background (#fff6ec) with a prominent, centered headline and primary actions. Section rhythm is managed through alternating background colors (White Canvas and Amber Glow) and consistent vertical spacing. Content is arranged in alternating text-left/image-right or text-right/image-left patterns, as well as stacked, centered blocks for calls to action or feature lists. Navigation is a sticky top bar with a clear primary action button.

## Agent Prompt Guide

primary action: #000000 (filled action)
Create a Primary Action Button: #000000 background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.

Example Component Prompts:

Create a feature card: White Canvas background (#ffffff), 8px radius, 16px padding. Title 'Productivity Hub' using Inter 600 at 22px, #212121, letter-spacing -0.03em. Body text 'Centralize your workflow.' using Inter 400 at 16px, #666666.

## Similar Brands

- **Notion** — Similar focus on document-based productivity with clean, almost monochrome UI and structured content presentation.
- **Asana** — Task management tools often share Coda's functional, high-contrast typography and clear component separation.
- **Figma** — Productivity and design tools leverage clean layouts, minimal color palettes, and strong typography to highlight content and actions.
- **Linear** — Another productivity tool that prioritizes high information density within a structured, often monochrome interface with subtle accents.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #212121;
  --color-white-canvas: #ffffff;
  --color-amber-glow: #fff6ec;
  --color-soft-gray: #e0e0e0;
  --color-slate-text: #666666;
  --color-ash-text: #8e8e8e;
  --color-obsidian: #000000;
  --color-warm-gray-text: #444444;
  --color-sunset-orange: #ee5a29;

  /* Typography — Font Families */
  --font-calibre-r: 'Calibre-R', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-tiempos-headline: 'Tiempos-Headline', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.55;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --tracking-body-sm: 0.01px;
  --text-body: 16px;
  --leading-body: 1.43;
  --tracking-body: 0.01px;
  --text-subheading: 20px;
  --leading-subheading: 1.38;
  --tracking-subheading: -0.01px;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: -0.03px;
  --text-heading: 38px;
  --leading-heading: 1.37;
  --tracking-heading: -0.025px;
  --text-heading-lg: 52px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.035px;
  --text-display: 72px;
  --leading-display: 1;
  --tracking-display: -0.045px;

  /* Typography — Weights */
  --font-weight-light: 300;
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
  --spacing-60: 60px;
  --spacing-72: 72px;
  --spacing-96: 96px;
  --spacing-164: 164px;

  /* Layout */
  --section-gap: 113px;
  --card-padding: 16px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-3xl: 44px;

  /* Named Radii */
  --radius-cards: 8px;
  --radius-icons: 44px;
  --radius-buttons: 8px;
  --radius-smallelements: 4px;

  /* Shadows */
  --shadow-subtle: rgb(33, 33, 33) 0px 0px 0px 1.5px inset;
  --shadow-lg: rgba(0, 0, 0, 0.06) 0px 12px 24px -5px, rgba(0, 0, 0, 0.06) 0px 5px 10px -6px;
  --shadow-subtle-2: rgb(224, 224, 224) 0px 0px 0px 1.5px inset;
  --shadow-subtle-3: rgb(0, 0, 0) 8px 8px 0px 0px;
  --shadow-xl: rgba(0, 0, 0, 0.06) 0px 18px 36px -6px, rgba(0, 0, 0, 0.06) 0px 6px 12px -6px;

  /* Surfaces */
  --surface-white-canvas: #ffffff;
  --surface-amber-glow-section: #fff6ec;
  --surface-elevated-card: #ffffff;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #212121;
  --color-white-canvas: #ffffff;
  --color-amber-glow: #fff6ec;
  --color-soft-gray: #e0e0e0;
  --color-slate-text: #666666;
  --color-ash-text: #8e8e8e;
  --color-obsidian: #000000;
  --color-warm-gray-text: #444444;
  --color-sunset-orange: #ee5a29;

  /* Typography */
  --font-calibre-r: 'Calibre-R', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-tiempos-headline: 'Tiempos-Headline', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.55;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --tracking-body-sm: 0.01px;
  --text-body: 16px;
  --leading-body: 1.43;
  --tracking-body: 0.01px;
  --text-subheading: 20px;
  --leading-subheading: 1.38;
  --tracking-subheading: -0.01px;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: -0.03px;
  --text-heading: 38px;
  --leading-heading: 1.37;
  --tracking-heading: -0.025px;
  --text-heading-lg: 52px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.035px;
  --text-display: 72px;
  --leading-display: 1;
  --tracking-display: -0.045px;

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
  --spacing-60: 60px;
  --spacing-72: 72px;
  --spacing-96: 96px;
  --spacing-164: 164px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-3xl: 44px;

  /* Shadows */
  --shadow-subtle: rgb(33, 33, 33) 0px 0px 0px 1.5px inset;
  --shadow-lg: rgba(0, 0, 0, 0.06) 0px 12px 24px -5px, rgba(0, 0, 0, 0.06) 0px 5px 10px -6px;
  --shadow-subtle-2: rgb(224, 224, 224) 0px 0px 0px 1.5px inset;
  --shadow-subtle-3: rgb(0, 0, 0) 8px 8px 0px 0px;
  --shadow-xl: rgba(0, 0, 0, 0.06) 0px 18px 36px -6px, rgba(0, 0, 0, 0.06) 0px 6px 12px -6px;
}
```

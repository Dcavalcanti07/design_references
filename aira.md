# Aira — Style Reference
> charcoal canvas, white marble

**Theme:** light

Aira employs a muted, professional aesthetic, layering subtle off-white and charcoal tones for a sophisticated, data-driven feel. Typography is precise and utilitarian, with a distinct serif for headlines contrasting a workhorse sans-serif for body text. Componentry is lightweight, preferring soft borders, generous radii, and minimal elevation to maintain a clean, unsculpted interface. The overall impression is one of restraint and clarity, where visual noise is minimized to prioritize content.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas | `#fafafb` | `--color-canvas` | Primary page and section backgrounds, ghost button backgrounds |
| Midnight Text | `#2c2c2b` | `--color-midnight-text` | Primary text color for headlines and body content |
| Deep Shadow | `#080808` | `--color-deep-shadow` | Overlay backgrounds, strong accent text, button text on light backgrounds |
| Surface Text | `#111111` | `--color-surface-text` | Card text and elevated component text |
| Dark Button Fill | `#1f1f1f` | `--color-dark-button-fill` | Filled button backgrounds for primary actions on dark surfaces |
| Muted Border | `#cbcbcb` | `--color-muted-border` | Subtle borders for outlined buttons and inputs |
| Muted Text | `#70706f` | `--color-muted-text` | Secondary body text, helper text, and icon fills |
| Card Surface | `#ededed` | `--color-card-surface` | Background for secondary information cards |
| Light Border | `#e3e3e3` | `--color-light-border` | Input borders, badge backgrounds |
| Dark Border | `#444444` | `--color-dark-border` | Stricter borders for outlined ghost buttons |
| Subtle Link | `#333333` | `--color-subtle-link` | Discreet link text and borders |
| Whisper White | `#f9f8f6` | `--color-whisper-white` | Brand-specific background used for hero sections |
| Brand Blue | `#2d62ff` | `--color-brand-blue` | Supporting palette color for small decorative accents when the core palette needs contrast. Do not promote it to the primary CTA color |

## Tokens — Typography

### Gesturaheadline — Display and headline typography; the serif forms provide a distinct, authoritative voice for prominent text, particularly at larger sizes. Used for brand-specific titles. · `--font-gesturaheadline`
- **Substitute:** Georgia or Libre Baskerville
- **Weights:** 400, 600
- **Sizes:** 14px, 20px, 24px, 30px, 36px, 48px, 56px, 66px
- **Line height:** 1.00, 1.15, 1.20, 1.40
- **Letter spacing:** -0.007em to -0.02em
- **Role:** Display and headline typography; the serif forms provide a distinct, authoritative voice for prominent text, particularly at larger sizes. Used for brand-specific titles.

### Inter — UI elements, body text, buttons, and navigation. Its sans-serif neutrality ensures legibility and a modern, functional feel across all interface contexts. · `--font-inter`
- **Substitute:** system-ui (e.g., Arial, Helvetica)
- **Weights:** 400, 500, 600, 700
- **Sizes:** 10px, 12px, 13px, 14px, 15px, 16px, 18px, 72px
- **Line height:** 0.80, 0.94, 1.00, 1.14, 1.20, 1.40, 1.50
- **Letter spacing:** -0.009em to 0.14em
- **Role:** UI elements, body text, buttons, and navigation. Its sans-serif neutrality ensures legibility and a modern, functional feel across all interface contexts.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.5 | 0.14px | `--text-caption` |
| body | 14px | 1.4 | -0.15px | `--text-body` |
| subheading | 20px | 1.2 | -0.2px | `--text-subheading` |
| heading-sm | 30px | 1.15 | -0.45px | `--text-heading-sm` |
| heading | 36px | 1.15 | -0.54px | `--text-heading` |
| heading-lg | 48px | 1.15 | -0.72px | `--text-heading-lg` |
| display | 56px | 1.15 | -0.84px | `--text-display` |

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
| 56 | 56px | `--spacing-56` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 120 | 120px | `--spacing-120` |
| 192 | 192px | `--spacing-192` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 22px |
| badges | 999px |
| inputs | 8px |
| buttons | 999px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| lg | `rgba(0, 0, 0, 0.08) 0px 1px 20px 3px` | `--shadow-lg` |
| xl | `rgba(0, 0, 0, 0.18) 0px 20px 60px 0px, rgba(0, 0, 0, 0.08...` | `--shadow-xl` |

### Layout

- **Section gap:** 64px
- **Card padding:** 16px
- **Element gap:** 8px

## Components

### Primary Filled Button (Light)
**Role:** Main call to action on light backgrounds.

Background: #F9F8F6, Text: #1C1D1F, Radius: 999px, Padding: 8px vertical, 16px horizontal.

### Secondary Filled Button (Dark)
**Role:** An alternative call to action, typically used on dark backgrounds, providing less prominence than the primary. The opacity creates a subtle surface.

Background: rgba(255, 255, 255, 0.08), Text: #FFFFFF, Radius: 999px, Padding: 8px vertical, 16px horizontal.

### Ghost Button (Dark)
**Role:** Minimalist interactive element, often for navigation or secondary actions on dark backgrounds.

Background: transparent, Text: #FFFFFF, Border: 1px solid rgba(0, 0, 0, 0.2), Radius: 999px, Padding: 8px vertical, 16px horizontal.

### Card, Elevated
**Role:** Prominent content container, used for feature blocks or key information.

Background: #FFFFFF, Radius: 22px, Shadow: rgba(0, 0, 0, 0.18) 0px 20px 60px 0px, rgba(0, 0, 0, 0.08) 0px 4px 16px 0px, Padding: 36px vertical, 36px horizontal.

### Card, Subtle
**Role:** Background for secondary panels or grouped content.

Background: #EDEDED, Radius: 18px, Shadow: none, Padding: 18px horizontal, 14px bottom.

### Text Input (Light)
**Role:** Standard input field for user data on light backgrounds.

Background: #FFFFFF, Text: #111111, Border: 1px solid #E3E3E3, Radius: 8px, Padding: 10px vertical, 12px horizontal. Placeholder style: #70706f

### Outline Input (Dark)
**Role:** Minimalist input field, often for search functionality where the input is more of a prompt.

Background: transparent, Text: #2C2C2B, Border: 1px solid #2C2C2B, Radius: 0px.

### Informational Badge
**Role:** Tagging or categorization element.

Background: rgba(223, 223, 223, 0.8), Text: #1C1D1F, Radius: 999px, Padding: 4px vertical, 10.4px horizontal.

## Do's and Don'ts

### Do
- Prioritize Inter for all body text, UI labels, and button text at weights 400-600.
- Use Gesturaheadline for all display and large headings to establish brand voice, utilizing its distinct serif character.
- Apply a 999px border-radius for all interactive buttons and badges, creating a soft, pill-shaped aesthetic.
- Maintain a clear visual hierarchy with surface backgrounds: #fafafb for primary sections and #ededed for secondary content blocks or cards.
- Utilize #2c2c2b for primary text against light backgrounds, ensuring strong contrast and readability.
- Implement consistent internal padding using the base unit of 4px, building up to 8px for element gaps and 16px for card padding.
- Employ the subtle shadow rgba(0, 0, 0, 0.18) 0px 20px 60px 0px, rgba(0, 0, 0, 0.08) 0px 4px 16px 0px only for key elevated components like prominent cards.

### Don't
- Avoid generic system fonts for headlines; Gesturaheadline is critical for brand recognition.
- Do not introduce highly saturated colors unless specifically for a brand highlight or semantic feedback (error/success).
- Refrain from sharp corners; buttons and input fields should consistently use a minimum of 8px radius, and cards 18px-22px.
- Do not use heavy, dark borders on cards or inputs; prefer the subtle #E3E3E3 or transparent with a very faint border.
- Avoid cluttering the interface with multiple elevation levels; reserve shadows for only the most prominent interactive elements.
- Do not vary line-height aggressively for body text; stick to the defined ratios to maintain consistent reading flow.
- Do not use dark backgrounds for primary page sections unless explicitly creating a hero or specific brand experience.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Canvas | `#fafafb` | Base page background for most content sections. |
| 2 | Card Surface | `#ededed` | Background for secondary content cards or subtle interactive components. |
| 3 | Elevated Card | `#ffffff` | Primary interactive cards or panels requiring subtle elevation and greater visual weight. |

## Elevation

- **Elevated Card:** `rgba(0, 0, 0, 0.18) 0px 20px 60px 0px, rgba(0, 0, 0, 0.08) 0px 4px 16px 0px`

## Imagery

The visual language is dominantly product-focused, featuring tight crops of mobile devices displaying the Aira interface. Imagery is isolated on pure white or dark, minimalist backgrounds, emphasizing the software and its functionality without lifestyle context. Illustrations are flat, clean outlines or filled shapes, reinforcing the UI. Icons are primarily outlined, conveying a light, modern touch. The density is text-dominant, with imagery serving as clear, direct product showcases rather than decorative atmosphere.

## Layout

The page structure favors a max-width contained layout, though the hero section uses a full-bleed dark background with a centered headline and product mock-up. Section rhythm is managed through alternating soft background tones (primarily #fafafb and #ededed) with consistent vertical spacing. Content is largely arranged in centered stacks for headings and paragraphs, or alternating two-column layouts (text left, image right) for feature explanations. There are no prominent card grids, but individual cards are used for specific content blocks. Navigation is a sticky top bar, minimal and un-obtrusive.

## Agent Prompt Guide

Quick Color Reference:
text: #2c2c2b
background: #fafafb
border: #e3e3e3
accent: #2d62ff
primary action: #1f1f1f (filled action)

Example Component Prompts:
1. Create a Dark Hero Section: Background #080808. Headline 'Find new customers. Grow the ones you have.' using Gesturaheadline weight 600, size 56px, #fafafb, letter-spacing -0.84px. Body text 'Aira is an AI assistant...' using Inter weight 400, size 18px, #fafafb, line-height 1.4. Include a 'Try Aira' button: Background #fafafb, text #1f1f1f, radius 999px, padding 8px vertical/16px horizontal.
2. Create a Subtle Card: Background #ededed, radius 18px, no shadow, padding 18px horizontal/14px bottom. Inside, place a heading 'Featured insight' using Inter weight 600, size 16px, #2c2c2b, and body text using Inter weight 400, size 14px, #70706f.
3. Create an Input Field: Background #FFFFFF, border 1px solid #e3e3e3, radius 8px, padding 10px vertical/12px horizontal. Placeholder text 'Describe the type of companies...' using Inter weight 400, size 14px, #70706f.

## Similar Brands

- **Linear** — Monochromatic interface with minimal elevation and prominent rounded corners paired with sharp typography.
- **Stripe** — Usage of a clean, light canvas, subtle background shifts, and precise, functional typography.
- **Rive** — Emphasis on product screenshots within device mockups set against clean, uncluttered backgrounds.
- **Webflow** — The combination of a functional sans-serif for UI and a distinctive serif for display headings.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas: #fafafb;
  --color-midnight-text: #2c2c2b;
  --color-deep-shadow: #080808;
  --color-surface-text: #111111;
  --color-dark-button-fill: #1f1f1f;
  --color-muted-border: #cbcbcb;
  --color-muted-text: #70706f;
  --color-card-surface: #ededed;
  --color-light-border: #e3e3e3;
  --color-dark-border: #444444;
  --color-subtle-link: #333333;
  --color-whisper-white: #f9f8f6;
  --color-brand-blue: #2d62ff;

  /* Typography — Font Families */
  --font-gesturaheadline: 'Gesturaheadline', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --tracking-caption: 0.14px;
  --text-body: 14px;
  --leading-body: 1.4;
  --tracking-body: -0.15px;
  --text-subheading: 20px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.2px;
  --text-heading-sm: 30px;
  --leading-heading-sm: 1.15;
  --tracking-heading-sm: -0.45px;
  --text-heading: 36px;
  --leading-heading: 1.15;
  --tracking-heading: -0.54px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.15;
  --tracking-heading-lg: -0.72px;
  --text-display: 56px;
  --leading-display: 1.15;
  --tracking-display: -0.84px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
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
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-120: 120px;
  --spacing-192: 192px;

  /* Layout */
  --section-gap: 64px;
  --card-padding: 16px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-2xl-2: 22px;
  --radius-full: 99px;
  --radius-full-2: 999px;
  --radius-full-3: 13486.5px;
  --radius-full-4: 15984px;

  /* Named Radii */
  --radius-cards: 22px;
  --radius-badges: 999px;
  --radius-inputs: 8px;
  --radius-buttons: 999px;

  /* Shadows */
  --shadow-lg: rgba(0, 0, 0, 0.08) 0px 1px 20px 3px;
  --shadow-xl: rgba(0, 0, 0, 0.18) 0px 20px 60px 0px, rgba(0, 0, 0, 0.08) 0px 4px 16px 0px;

  /* Surfaces */
  --surface-canvas: #fafafb;
  --surface-card-surface: #ededed;
  --surface-elevated-card: #ffffff;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas: #fafafb;
  --color-midnight-text: #2c2c2b;
  --color-deep-shadow: #080808;
  --color-surface-text: #111111;
  --color-dark-button-fill: #1f1f1f;
  --color-muted-border: #cbcbcb;
  --color-muted-text: #70706f;
  --color-card-surface: #ededed;
  --color-light-border: #e3e3e3;
  --color-dark-border: #444444;
  --color-subtle-link: #333333;
  --color-whisper-white: #f9f8f6;
  --color-brand-blue: #2d62ff;

  /* Typography */
  --font-gesturaheadline: 'Gesturaheadline', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --tracking-caption: 0.14px;
  --text-body: 14px;
  --leading-body: 1.4;
  --tracking-body: -0.15px;
  --text-subheading: 20px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.2px;
  --text-heading-sm: 30px;
  --leading-heading-sm: 1.15;
  --tracking-heading-sm: -0.45px;
  --text-heading: 36px;
  --leading-heading: 1.15;
  --tracking-heading: -0.54px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.15;
  --tracking-heading-lg: -0.72px;
  --text-display: 56px;
  --leading-display: 1.15;
  --tracking-display: -0.84px;

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
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-120: 120px;
  --spacing-192: 192px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-2xl-2: 22px;
  --radius-full: 99px;
  --radius-full-2: 999px;
  --radius-full-3: 13486.5px;
  --radius-full-4: 15984px;

  /* Shadows */
  --shadow-lg: rgba(0, 0, 0, 0.08) 0px 1px 20px 3px;
  --shadow-xl: rgba(0, 0, 0, 0.18) 0px 20px 60px 0px, rgba(0, 0, 0, 0.08) 0px 4px 16px 0px;
}
```

# Acctual — Style Reference
> Architectural blueprint on white marble. Precision, clarity, and transparent flow of information.

**Theme:** light

Acctual is a clean, sharp accounting software interface, defined by abundant whitespace, crisp typography, and an almost entirely achromatic palette punctuated by a single vibrant teal accent. It feels like an impeccably organized digital ledger, where the strict logical layout and high contrast ensure every piece of financial data is immediately comprehensible. The signature element is the interplay of system sans-serif for secondary text with the bespoke Open Runde, creating a dual texture of approachability and structured precision.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card surfaces, primary text contrast. |
| Ink Black | `#000000` | `--color-ink-black` | Primary text, critical headings, strong brand emphasis. Its absolute blackness provides uncompromising legibility against white. |
| Graphite | `#0f0f0f` | `--color-graphite` | Prominent headings and body text, a slightly softer variant of Ink Black. |
| Deep Slate | `#1e1e1` | `--color-deep-slate` | Secondary body text and descriptions, offering a subtle visual break from pure black without sacrificing contrast. |
| Ash Gray | `#8d8d8d` | `--color-ash-gray` | Subtle text, metadata, disabled states. Provides gentle visual hierarchy. |
| Button Black | `#0d111b` | `--color-button-black` | Primary action buttons, providing a solid, grounded feel against the white background. |
| Sky Teal | `#0098f2` | `--color-sky-teal` | Interactive elements, links, checkmarks, highlights — the sole vibrant accent for key user actions and positive indications. |
| Hot Pink | `#f200ca` | `--color-hot-pink` | Decorative elements or specific brand highlights within icons, a secondary accent for visual interest. |
| Vivid Violet | `#6d56fc` | `--color-vivid-violet` | Decorative elements or specific brand highlights within icons, alongside Hot Pink. |
| Subtle Cream | `#f7fafc` | `--color-subtle-cream` | Alternative background for sections, creating subtle depth on the mostly white page. |

## Tokens — Typography

### sans-serif — Smallest text elements, UI labels, and highly functional information. It has a utilitarian feel which contrasts with the custom font for core content. · `--font-sans-serif`
- **Substitute:** system-ui, 'Segoe UI', Roboto, Helvetica Neue, Arial, Noto Sans, sans-serif
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.20
- **Role:** Smallest text elements, UI labels, and highly functional information. It has a utilitarian feel which contrasts with the custom font for core content.

### Open Runde — Primary display font for headings, body text, and key content. Its distinctive features and precise letter-spacing contribute to the crisp, modern feel. The feature settings indicate careful typographic attention. · `--font-open-runde`
- **Substitute:** Inter
- **Weights:** 400, 500, 600
- **Sizes:** 14px, 16px, 20px, 32px, 40px, 64px
- **Line height:** 1.13, 1.20, 1.21, 1.25, 1.40, 1.43, 1.50, 1.71, 1.75
- **Letter spacing:** -0.037em at 64px, -0.030em at 40px, -0.020em at 32px, -0.012em at 20px, normal at smaller sizes
- **OpenType features:** `"blwf" on, "cv03" on, "cv04" on, "cv09" on, "cv11" on`
- **Role:** Primary display font for headings, body text, and key content. Its distinctive features and precise letter-spacing contribute to the crisp, modern feel. The feature settings indicate careful typographic attention.

### Caveat — Handwritten script used for subtle accents like testimonials or decorative elements, providing a human touch to an otherwise structured interface. · `--font-caveat`
- **Substitute:** Sacramento
- **Weights:** 600
- **Sizes:** 16px, 24px
- **Line height:** 1.33, 1.50
- **Role:** Handwritten script used for subtle accents like testimonials or decorative elements, providing a human touch to an otherwise structured interface.

### Inter — Used for specific body text elements, likely in contexts where Open Runde might be too decorative or less performant. It fills a very specific role, avoiding the system sans-serif. · `--font-inter`
- **Substitute:** Inter
- **Weights:** 500
- **Sizes:** 14px
- **Line height:** 1.43
- **Role:** Used for specific body text elements, likely in contexts where Open Runde might be too decorative or less performant. It fills a very specific role, avoiding the system sans-serif.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.2 | — | `--text-caption` |
| body-sm | 14px | 1.43 | — | `--text-body-sm` |
| body | 16px | 1.5 | — | `--text-body` |
| subheading | 20px | 1.25 | -0.24px | `--text-subheading` |
| heading | 32px | 1.21 | -0.64px | `--text-heading` |
| heading-lg | 40px | 1.2 | -1.2px | `--text-heading-lg` |
| display | 64px | 1.13 | -2.368px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 8 | 8px | `--spacing-8` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 96 | 96px | `--spacing-96` |
| 100 | 100px | `--spacing-100` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 20px |
| badges | 1250px |
| images | 32px |
| buttons | 100px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(0, 0, 0, 0.06) 0px 2.5px 2.5px 0px` | `--shadow-subtle` |
| subtle-2 | `rgb(36, 38, 40) 0px 0px 0px 1px, rgba(27, 28, 29, 0.48) 0...` | `--shadow-subtle-2` |

### Layout

- **Page max-width:** 1200px
- **Section gap:** 40-80px
- **Card padding:** 24px
- **Element gap:** 4-24px

## Components

### Primary Action Button
**Role:** Call to action, e.g. 'Create an invoice'

Text: Open Runde, weight 400, color Canvas White. Background: Button Black (#0d111b). Hover/Active: No explicit hover state, implies primary color changes or subtle elevation. Radius: 100px (fully pill-shaped). Padding: 6px vertical, 14px horizontal. Shadow: Subtle dark shadow rgb(36, 38, 40) 0px 0px 0px 1px, rgba(27, 28, 29, 0.48) 0px 1px 2px 0px.

### Navigation Link
**Role:** Top navigation items

Text: Open Runde, weight 400, color Ash Gray (#8d8d8d) for inactive, Ink Black (#000000) for active/hover. No explicit styling beyond color change, relying on surrounding elements for distinction.

### Invoice Card
**Role:** Displaying invoice previews

Background: Canvas White (#ffffff). Radius: 20px. Shadow: subtle rgba(0, 0, 0, 0.06) 0px 2.5px 2.5px 0px. Internal content uses Deep Slate and Open Runde.

### Service Feature List Item
**Role:** Highlighting key features below hero

Text: Open Runde, weight 400, color Graphite (#0f0f0f). Icon: Sky Teal (#0098f2) vector checkmark. Uses 6px elementGap between icon and text.

### Small Header Button
**Role:** Secondary action in header, e.g. 'Log in'

Text: Open Runde, weight 400, color Ash Gray (#8d8d8d). No background or border, relies on text color to differentiate from primary button.

### Sign Up Header Button
**Role:** Primary action in header

Text: Open Runde, weight 400, color Canvas White (#ffffff). Background: Button Black (#0d111b). Radius: 100px. Padding: 6px vertical, 14px horizontal.

## Do's and Don'ts

### Do
- Use '#ffffff' Canvas White as the dominant page and card background color; establish visual hierarchy through subtle shade differences like '#f7fafc' for alternating sections.
- Apply Open Runde for all main headings and body text, varying weights (400, 500, 600) and sizes according to the type scale for clear hierarchy and visual appeal.
- Employ the 100px radius for all interactive buttons and pill-shaped elements to maintain a consistent soft, approachable shape.
- Utilize Sky Teal (#0098f2) exclusively for interactive elements like links and checkmarks; avoid using it for decorative purposes to preserve its accent meaning.
- Maintain generous padding, particularly 24px and 40px for section separators and major element spacing, creating a spacious and comfortable information density.
- When emphasizing short, impactful statements or testimonials, use the Caveat font for a personalized, handwritten touch.

### Don't
- Do not introduce new chromatic colors beyond Sky Teal, Hot Pink, and Vivid Violet; the design strictly adheres to an achromatic base with minimal, deliberate color accents.
- Avoid box shadows for general elevation; leverage subtle background color changes (e.g., #f7fafc) or thin borders to suggest depth and separation.
- Do not use system sans-serif for headlines or prominent body text; reserve it for small, functional UI labels where its simplicity is an asset.
- Do not deviate from the established letter-spacing values for Open Runde; these are carefully calibrated for optimal legibility at different sizes.
- Avoid dense, information-heavy sections without adequate whitespace; the design's strength lies in its spacious and clear presentation.
- Do not use multiple font sizes or weights within a single line of text unless it's a clearly defined component. Maintain typographic consistency.

## Imagery

The site uses a mix of tightly cropped, top-down product photography featuring office supplies (paperclips, pens, keyboard snippets) on a clean white desk, serving as decorative framing for UI elements. Embedded product screenshots show the invoice interface directly, providing clear, functional examples of the software. Icons are primarily line-based, monochrome (Ink Black), with occasional small fills of the brand's accent colors (Sky Teal, Hot Pink, Vivid Violet). The imagery's role is decorative atmosphere, combined with direct product showcasing to explain functionality, rather than lifestyle or abstract concepts.

## Layout

The page model is a max-width 1200px centered container, creating generous margins on larger screens. The hero section features a centered headline over a white background, flanked by decorative product photography. Sections primarily follow a consistent vertical rhythm with ample spacing (40-80px), often presenting content as centered stacks or simple two-column layouts. A subtle alternating background color ('Subtle Cream') differentiates some sections. Navigation is a fixed top bar with a logo, standard links, and 'Log in'/'Sign up' buttons. Content density is comfortable, prioritizing readability and visual breathing room.

## Agent Prompt Guide

## Quick Color Reference
- Text: #000000 Ink Black
- Background: #ffffff Canvas White
- CTA Background: #0d111b Button Black
- CTA Text: #ffffff Canvas White
- Links/Accent: #0098f2 Sky Teal
- Secondary Text/Disabled: #8d8d8d Ash Gray

## 3-5 Example Component Prompts
1. Create a hero section: 'Canvas White' background. Headline 'Invoices that work harder' using 'display' role of Open Runde, weight 600, color '#000000' Ink Black, letter-spacing -2.368px. Subtext 'Acctual offers more payment methods and no monthly fees...' at 'body' role Open Runde, weight 400, color '#1e1e1' Deep Slate. Primary button 'Create an invoice': background '#0d111b' Button Black, text '#ffffff' Canvas White, 100px radius, 6px 14px padding. Below the button, add three feature indicators: 'Sky Teal' checkmark icon, followed by text 'Same day payouts' using 'body-sm' role Open Runde, weight 400, color '#0f0f0f' Graphite.
2. Design a Testimonial Card: 'Canvas White' background, 20px radius, rgba(0, 0, 0, 0.06) 0px 2.5px 2.5px 0px shadow. Headline text '"Acctual makes invoices so easy."' using 'heading' role of Open Runde, weight 600, color '#000000' Ink Black. Attributed text 'Marcel Kargul, founder of Kargul Studio' using 'body' role of Caveat, weight 600, color '#8d8d8d' Ash Gray.
3. Implement a Navigation Bar: 'Canvas White' background. Logo at left. Navigation links 'Invoicing', 'Pricing', 'Blog', 'Guides' using Open Runde, weight 400, color '#8d8d8d' Ash Gray for inactive and '#000000' Ink Black for active/hover. 'Log in' button as text-only, Open Runde, weight 400, color '#8d8d8d' Ash Gray. 'Sign up for free' button: background '#0d111b' Button Black, text '#ffffff' Canvas White, 100px radius, 6px 14px padding.

## Similar Brands

- **Stripe** — Clean, high-contrast, mostly achromatic UI with strong typography and minimal, deliberate accent colors defining interactive elements.
- **Linear** — Emphasis on precise typography, carefully calibrated spacing, and a focus on clarity through strict visual hierarchy rather than heavy ornamentation.
- **Mercury Bank** — Modern fintech aesthetic with an abundance of whitespace, subtle grays, and a crisp, professional feeling driven by strong legibility and structured layouts.
- **Pitch** — Combines prominent, well-crafted typography with a largely neutral palette and strategic use of a single vibrant accent color to guide the eye and denote interactivity.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ink-black: #000000;
  --color-graphite: #0f0f0f;
  --color-deep-slate: #1e1e1;
  --color-ash-gray: #8d8d8d;
  --color-button-black: #0d111b;
  --color-sky-teal: #0098f2;
  --color-hot-pink: #f200ca;
  --color-vivid-violet: #6d56fc;
  --color-subtle-cream: #f7fafc;

  /* Typography — Font Families */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-open-runde: 'Open Runde', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-caveat: 'Caveat', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.2;
  --text-body-sm: 14px;
  --leading-body-sm: 1.43;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 20px;
  --leading-subheading: 1.25;
  --tracking-subheading: -0.24px;
  --text-heading: 32px;
  --leading-heading: 1.21;
  --tracking-heading: -0.64px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -1.2px;
  --text-display: 64px;
  --leading-display: 1.13;
  --tracking-display: -2.368px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-100: 100px;

  /* Layout */
  --page-max-width: 1200px;
  --section-gap: 40-80px;
  --card-padding: 24px;
  --element-gap: 4-24px;

  /* Border Radius */
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 32px;
  --radius-full: 100px;
  --radius-full-2: 1250px;

  /* Named Radii */
  --radius-cards: 20px;
  --radius-badges: 1250px;
  --radius-images: 32px;
  --radius-buttons: 100px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.06) 0px 2.5px 2.5px 0px;
  --shadow-subtle-2: rgb(36, 38, 40) 0px 0px 0px 1px, rgba(27, 28, 29, 0.48) 0px 1px 2px 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ink-black: #000000;
  --color-graphite: #0f0f0f;
  --color-deep-slate: #1e1e1;
  --color-ash-gray: #8d8d8d;
  --color-button-black: #0d111b;
  --color-sky-teal: #0098f2;
  --color-hot-pink: #f200ca;
  --color-vivid-violet: #6d56fc;
  --color-subtle-cream: #f7fafc;

  /* Typography */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-open-runde: 'Open Runde', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-caveat: 'Caveat', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.2;
  --text-body-sm: 14px;
  --leading-body-sm: 1.43;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 20px;
  --leading-subheading: 1.25;
  --tracking-subheading: -0.24px;
  --text-heading: 32px;
  --leading-heading: 1.21;
  --tracking-heading: -0.64px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -1.2px;
  --text-display: 64px;
  --leading-display: 1.13;
  --tracking-display: -2.368px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-100: 100px;

  /* Border Radius */
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 32px;
  --radius-full: 100px;
  --radius-full-2: 1250px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.06) 0px 2.5px 2.5px 0px;
  --shadow-subtle-2: rgb(36, 38, 40) 0px 0px 0px 1px, rgba(27, 28, 29, 0.48) 0px 1px 2px 0px;
}
```

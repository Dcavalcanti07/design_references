# Say Briefly — Style Reference
> Olive Canvas, Highlighted Briefs, Warm Accents

**Theme:** light

Say Briefly employs a light, airy canvas with a strong emphasis on a deep olive green for primary textual hierarchy and interactive elements, delivering a confident, grounded feel. Accents of warm yellow and soft pastels punctuate the monochromatic base to highlight key information and provide visual differentiation for cards and functional buttons. Its typography balances a bold, display-oriented headline font with a highly legible sans-serif for body text, creating a system that is both engaging and understated. Surfaces are mostly flat with minimal shadows, allowing color and text to carry the design.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#fcfaf5` | `--color-canvas-white` | Page background, primary surface for most content |
| Deep Olive | `#1a3300` | `--color-deep-olive` | Primary text, major headings, borders, and main call-to-action buttons. This color defines the brand's core visual identity |
| Highlight Yellow | `#ffe95c` | `--color-highlight-yellow` | Highlighting key text sections, card backgrounds, and button text on Deep Olive backgrounds |
| Charcoal Black | `#000000` | `--color-charcoal-black` | Secondary text, fine print, and decorative SVG fills for visual depth |
| Soft Teal | `#a8e5e5` | `--color-soft-teal` | Decorative card backgrounds and distinct secondary buttons |
| Muted Sage | `#d5f5c2` | `--color-muted-sage` | Soft button backgrounds, subtle surface variations |
| Warm Orange | `#cb5521` | `--color-warm-orange` | Distinct card and section backgrounds, lending warmth |
| Pale Pink | `#f6d0ff` | `--color-pale-pink` | Decorative button backgrounds for visual variety |
| Light Gray | `#f1f1f1` | `--color-light-gray` | Minor text, subtle borders, and background accents where faint contrast is needed |
| Border Gray | `#b6b6b6` | `--color-border-gray` | Hairline borders, dividers, subtle UI outlines for structure |

## Tokens — Typography

### Bricolage Grotesque — Hero headlines and major theatrical titles. Its heavy weight and generous letter-spacing create an impactful, editorial presence. · `--font-bricolage-grotesque`
- **Substitute:** system-ui
- **Weights:** 800
- **Sizes:** 55px, 66px, 90px
- **Line height:** 1.00, 1.15, 1.20
- **Letter spacing:** 0.04em, 0.05em
- **Role:** Hero headlines and major theatrical titles. Its heavy weight and generous letter-spacing create an impactful, editorial presence.

### Inter — Primary typeface for all body text, navigation, and most UI elements. Its broad range of weights handles information hierarchy across the interface. · `--font-inter`
- **Substitute:** Arial
- **Weights:** 300, 400, 500, 600, 700
- **Sizes:** 11px, 12px, 14px, 16px, 17px, 18px, 20px, 24px, 28px, 30px, 32px, 36px, 38px, 40px, 64px
- **Line height:** 0.93, 1.03, 1.10, 1.20, 1.25, 1.30, 1.38, 1.40, 1.50, 1.56, 1.63
- **Role:** Primary typeface for all body text, navigation, and most UI elements. Its broad range of weights handles information hierarchy across the interface.

### Roboto Mono — Used for specific functional elements or data display, providing a distinct, technical contrast to the main sans-serif. · `--font-roboto-mono`
- **Substitute:** monospace
- **Weights:** 400
- **Sizes:** 12px, 15px, 16px
- **Line height:** 1.00, 1.33, 1.38
- **Role:** Used for specific functional elements or data display, providing a distinct, technical contrast to the main sans-serif.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 11px | 1.3 | — | `--text-caption` |
| body-sm | 14px | 1.3 | — | `--text-body-sm` |
| body | 17px | 1.3 | — | `--text-body` |
| body-lg | 18px | 1.3 | — | `--text-body-lg` |
| heading-sm | 24px | 1.3 | — | `--text-heading-sm` |
| heading | 30px | 1.3 | — | `--text-heading` |
| heading-lg | 36px | 1.3 | — | `--text-heading-lg` |
| display-sm | 38px | 1.3 | — | `--text-display-sm` |
| display | 64px | 1.3 | — | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 8px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 8 | 8px | `--spacing-8` |
| 16 | 16px | `--spacing-16` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 56 | 56px | `--spacing-56` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 96 | 96px | `--spacing-96` |
| 120 | 120px | `--spacing-120` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 6px |
| buttons | 6px |
| navItems | 16px |
| highlightedElements | 9999px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(0, 0, 0, 0.05) 0px 1px 2px 0px` | `--shadow-subtle` |
| subtle-2 | `rgba(0, 0, 0, 0.1) 0px 1px 3px 0px, rgba(0, 0, 0, 0.1) 0p...` | `--shadow-subtle-2` |
| xl | `rgba(255, 235, 90, 0.01) 0px 527px 211px 0px, rgba(255, 2...` | `--shadow-xl` |

### Layout

- **Page max-width:** 1320px
- **Section gap:** 40px
- **Card padding:** 16px
- **Element gap:** 16px

## Components

### Navigation Link
**Role:** Text link within the top navigation.

Inter, weight 400, Deep Olive text. No background or padding, appearing as simple text. Nav border is #b6b6b6 with 16px radius.

### Primary Call-to-Action Button
**Role:** Main interactive element, driving user conversion.

Deep Olive background (#1a3300), Highlight Yellow text (#ffe95c), 6px border-radius, 12px vertical padding, 40px horizontal padding. Shadow: rgba(0, 0, 0, 0.05) 0px 1px 2px 0px.

### Secondary Outlined Button
**Role:** Less prominent interactive actions.

Transparent background, Deep Olive text (#1a3300), 2px Deep Olive border, 6px border-radius, 12px vertical padding, 19.14px horizontal padding. Shadow: rgba(0, 0, 0, 0.05) 0px 1px 2px 0px.

### Highlight Card
**Role:** Prominent information display, often with a subtle background color.

Highlight Yellow background (#ffe95c), 6px border-radius (top-left, bottom-left) or 16px border-radius (all sides), 48px top padding, 28px horizontal padding, 36px bottom padding. No shadow.

### Decorative Card - Warm Orange
**Role:** visually distinct sections or feature highlights.

Warm Orange background (#cb5521), 12px border-radius, 50px vertical padding, 120px horizontal padding. No shadow.

### Decorative Card - Soft Teal
**Role:** Visually distinct sections or feature highlights.

Soft Teal background (#a8e5e5), 16px border-radius, 56px vertical padding, 75px horizontal padding. No shadow.

### Subtle Accent Badge
**Role:** Small, informational tags.

Transparent background, Deep Olive text, 16px vertical and horizontal padding, 8px border-radius. Highlight Yellow background (#ffe95c) is used when the badge text is meant to be highlighted.

## Do's and Don'ts

### Do
- Always use Deep Olive (#1a3300) for primary text and main call-to-action buttons.
- Apply 6px border-radius for buttons and typical cards, 16px for rounded sections and navigation elements, and 9999px for pill-shaped accents.
- Maintain a comfortable density with 16px for element gaps and minimum 40px for section gaps.
- Utilize Highlight Yellow (#ffe95c) for textual emphasis and as an active background color for cards and button text on dark backgrounds.
- Structure headlines with Bricolage Grotesque weight 800, using generous letter-spacing (0.04em-0.05em) and sizes 55px-90px.
- Prioritize flat design with minimal shadows; use rgba(0, 0, 0, 0.05) 0px 1px 2px 0px for subtle button elevation.
- Ensure all body text uses Inter font for readability, with weights varying from 300 to 700 to establish clear hierarchy.

### Don't
- Avoid using highly saturated colors for large background areas; stick to the light Canvas White or softer accent pastels.
- Do not introduce heavy drop shadows or complex gradients; the system relies on flat surfaces and color contrast.
- Do not deviate from the specified font families or their usage roles; maintain the distinct visual voice of Bricolage Grotesque for display and Inter for body.
- Avoid arbitrary border-radius values; adhere strictly to 6px, 16px, or 9999px for consistent shape language.
- Do not use dark backgrounds for entire page sections; the overall theme is light with occasional colored cards.
- Do not use generic gray for borders when Deep Olive or Border Gray exist for functional or neutral lines respectively.
- Avoid complex, multi-color illustrations; imagery should be clean, line-based, or product-focused to complement the UI.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas White | `#fcfaf5` | Primary page background, foundation for all content. |
| 1 | Soft Accent Surfaces | `#d5f5c2` | Subtle background for specific sections or button groups, providing a slight visual break. |
| 2 | Highlighted Cards | `#ffe95c` | Prominent content blocks that demand attention, or functional cards. |
| 3 | Decorative Thematic Cards | `#a8e5e5` | Distinct content containers using alternate brand accent colors for visual variety. |

## Elevation

- **Button:** `rgba(0, 0, 0, 0.05) 0px 1px 2px 0px`
- **Card/Button secondary:** `rgba(0, 0, 0, 0.1) 0px 1px 3px 0px, rgba(0, 0, 0, 0.1) 0px 1px 2px -1px`
- **Navigation Bar:** `rgba(255, 235, 90, 0.01) 0px 527px 211px 0px, rgba(255, 235, 90, 0.05) 0px 297px 178px 0px, rgba(255, 235, 90, 0.09) 0px 132px 132px 0px, rgba(255, 235, 90, 0.1) 0px 33px 72px 0px`

## Imagery

The imagery aesthetic is minimal and functional. It primarily features simple, line-drawn illustrations or subtle background patterns using the brand's core colors. When present, product screenshots are clean and focused. Icons are typically filled, utilizing Deep Olive on light backgrounds. Imagery serves decorative and explanatory roles without dominating the UI, maintaining a text-dominant layout.

## Layout

The page uses a maximum width of 1320px, with content centered. The hero section features a centered headline over a light background. Section rhythm is primarily defined by consistent vertical spacing, often with text-focused content blocks. Layouts include multi-column feature grids (seen in card variants) and standard stacked content for text-heavy areas. Navigation is a fixed top bar with simple text links and prominent right-aligned action buttons.

## Agent Prompt Guide

Quick Color Reference:
- text: #1a3300
- background: #fcfaf5
- border: #1a3300
- accent: #ffe95c
- primary action: #1a3300 (filled action)

Example Component Prompts:
1. Create a Hero Section: Background Canvas White (#fcfaf5). Main headline 'Project success starts with a clear brief.' using Bricolage Grotesque, weight 800, size 90px, letter-spacing 0.05em, Deep Olive (#1a3300) color. Highlight 'brief.' with a solid Highlight Yellow (#ffe95c) background under the text. Subtext 'Turn your client calls or meetings into organized summaries...' using Inter, weight 400, size 18px, Charcoal Black (#000000) color, line-height 1.5.
2. Create a Primary Action Button: #1a3300 background, #fcfaf5 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
3. Create a Navigation Item: 'Product' with transparent background, Deep Olive (#1a3300) text, Inter font, weight 400. No padding/border, appearing as plain text. The overall navigation bar has a Border Gray (#b6b6b6) border and 16px border-radius.
4. Create a Highlight Card: Background Highlight Yellow (#ffe95c), 16px border-radius, 32px top padding, 75px horizontal padding, 0px bottom padding. Text content using Deep Olive (#1a3300), Inter weight 600, size 30px.

## Similar Brands

- **Superhuman** — Shares a clean, light UI with a strong emphasis on productivity, subtle accent colors, and highly polished typography for a focused experience.
- **Notion** — Utilizes a flexible, content-first layout with a light default theme, distinct text hierarchies, and minimal UI elements that get out of the way for productivity.
- **Linear** — Features a strong, slightly muted color palette combined with precise typography and subtle elevation to create a professional yet approachable feel.
- **Read.cv** — Characterized by a minimalist aesthetic, strong typographic focus, and a use of muted accent colors to highlight specific UI elements while maintaining an overall clean look.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #fcfaf5;
  --color-deep-olive: #1a3300;
  --color-highlight-yellow: #ffe95c;
  --color-charcoal-black: #000000;
  --color-soft-teal: #a8e5e5;
  --color-muted-sage: #d5f5c2;
  --color-warm-orange: #cb5521;
  --color-pale-pink: #f6d0ff;
  --color-light-gray: #f1f1f1;
  --color-border-gray: #b6b6b6;

  /* Typography — Font Families */
  --font-bricolage-grotesque: 'Bricolage Grotesque', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-roboto-mono: 'Roboto Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.3;
  --text-body-sm: 14px;
  --leading-body-sm: 1.3;
  --text-body: 17px;
  --leading-body: 1.3;
  --text-body-lg: 18px;
  --leading-body-lg: 1.3;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.3;
  --text-heading: 30px;
  --leading-heading: 1.3;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1.3;
  --text-display-sm: 38px;
  --leading-display-sm: 1.3;
  --text-display: 64px;
  --leading-display: 1.3;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;
  --font-weight-extrabold: 800;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-120: 120px;

  /* Layout */
  --page-max-width: 1320px;
  --section-gap: 40px;
  --card-padding: 16px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-sm: 3px;
  --radius-md: 6px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-cards: 6px;
  --radius-buttons: 6px;
  --radius-navitems: 16px;
  --radius-highlightedelements: 9999px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.05) 0px 1px 2px 0px;
  --shadow-subtle-2: rgba(0, 0, 0, 0.1) 0px 1px 3px 0px, rgba(0, 0, 0, 0.1) 0px 1px 2px -1px;
  --shadow-xl: rgba(255, 235, 90, 0.01) 0px 527px 211px 0px, rgba(255, 235, 90, 0.05) 0px 297px 178px 0px, rgba(255, 235, 90, 0.09) 0px 132px 132px 0px, rgba(255, 235, 90, 0.1) 0px 33px 72px 0px;

  /* Surfaces */
  --surface-canvas-white: #fcfaf5;
  --surface-soft-accent-surfaces: #d5f5c2;
  --surface-highlighted-cards: #ffe95c;
  --surface-decorative-thematic-cards: #a8e5e5;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #fcfaf5;
  --color-deep-olive: #1a3300;
  --color-highlight-yellow: #ffe95c;
  --color-charcoal-black: #000000;
  --color-soft-teal: #a8e5e5;
  --color-muted-sage: #d5f5c2;
  --color-warm-orange: #cb5521;
  --color-pale-pink: #f6d0ff;
  --color-light-gray: #f1f1f1;
  --color-border-gray: #b6b6b6;

  /* Typography */
  --font-bricolage-grotesque: 'Bricolage Grotesque', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-roboto-mono: 'Roboto Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.3;
  --text-body-sm: 14px;
  --leading-body-sm: 1.3;
  --text-body: 17px;
  --leading-body: 1.3;
  --text-body-lg: 18px;
  --leading-body-lg: 1.3;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.3;
  --text-heading: 30px;
  --leading-heading: 1.3;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1.3;
  --text-display-sm: 38px;
  --leading-display-sm: 1.3;
  --text-display: 64px;
  --leading-display: 1.3;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-120: 120px;

  /* Border Radius */
  --radius-sm: 3px;
  --radius-md: 6px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-full: 9999px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.05) 0px 1px 2px 0px;
  --shadow-subtle-2: rgba(0, 0, 0, 0.1) 0px 1px 3px 0px, rgba(0, 0, 0, 0.1) 0px 1px 2px -1px;
  --shadow-xl: rgba(255, 235, 90, 0.01) 0px 527px 211px 0px, rgba(255, 235, 90, 0.05) 0px 297px 178px 0px, rgba(255, 235, 90, 0.09) 0px 132px 132px 0px, rgba(255, 235, 90, 0.1) 0px 33px 72px 0px;
}
```

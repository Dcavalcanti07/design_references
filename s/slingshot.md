# Slingshot — Style Reference
> Crisp canvas, vivid action.

**Theme:** light

Slingshot employs a practical and approachable interface, using a bright white canvas offset by soft, almost achromatic background shades. A single vibrant blue acts as the primary accent, drawing attention to calls to action and interactive elements. Typography is bold and direct for headings, while body text remains clear and functional. Components favor rounded corners and minimal elevation, presenting information without visual clutter.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#241f37` | `--color-midnight-ink` | Primary text, prominent headings — provides strong contrast against light backgrounds |
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card surfaces, default UI elements. The base layer for all content |
| Sky Blue | `#ecf2ff` | `--color-sky-blue` | Subtle secondary background surface, often for cards or sections, providing a soft visual break from Canvas White |
| Pale Peach | `#fff4ec` | `--color-pale-peach` | Minor accent background, possibly for callouts or contextual sections |
| Mint Glaze | `#edf9f5` | `--color-mint-glaze` | Subtle contextual background, used sparingly |
| Action Blue | `#1a5fff` | `--color-action-blue` | Primary action buttons, active interactive elements, and decorative accents — signifies interactivity and brand presence |
| Accent Orange | `#ff7a1a` | `--color-accent-orange` | Decorative highlights, strokes, and small accent elements, providing secondary visual interest |
| Accent Green | `#359774` | `--color-accent-green` | Green wash for highlight backgrounds, decorative bands, and soft emphasis behind content |

## Tokens — Typography

### sans-serif — sans-serif — detected in extracted data but not described by AI · `--font-sans-serif`
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.2
- **Role:** sans-serif — detected in extracted data but not described by AI

### Gopher — Prominent headings and titles. The ultra-tight line height (1.0) and lack of letter spacing create a dense, impactful statement, giving it a confident and contemporary feel. · `--font-gopher`
- **Substitute:** Open Sans
- **Weights:** 400, 500
- **Sizes:** 24px, 32px, 56px
- **Line height:** 1.00
- **Role:** Prominent headings and titles. The ultra-tight line height (1.0) and lack of letter spacing create a dense, impactful statement, giving it a confident and contemporary feel.

### Inter — Body text and functional interface elements, ensuring readability across various content densities and providing a modern, clear voice. · `--font-inter`
- **Substitute:** system-ui
- **Weights:** 400
- **Sizes:** 12px, 14px, 16px
- **Line height:** 1.14, 1.20, 1.33
- **Role:** Body text and functional interface elements, ensuring readability across various content densities and providing a modern, clear voice.

### Inter — Small, emphasized text such as tags or labels. The generous letter spacing and line height set it apart, making short phrases highly visible. · `--font-inter`
- **Substitute:** system-ui
- **Weights:** 400
- **Sizes:** 12px, 14px, 16px
- **Line height:** 1.14, 1.20, 1.33
- **Letter spacing:** 0.083em
- **Role:** Small, emphasized text such as tags or labels. The generous letter spacing and line height set it apart, making short phrases highly visible.

### Inter — Strong emphasis within body text and some button labels. Provides clear hierarchy for important information without resorting to larger sizes. · `--font-inter`
- **Substitute:** system-ui
- **Weights:** 400
- **Sizes:** 12px, 14px, 16px
- **Line height:** 1.14, 1.20, 1.33
- **Role:** Strong emphasis within body text and some button labels. Provides clear hierarchy for important information without resorting to larger sizes.

### Inter-Bold — Inter-Bold — detected in extracted data but not described by AI · `--font-inter-bold`
- **Weights:** 700
- **Sizes:** 14px, 16px
- **Line height:** 1.14, 1.6
- **Role:** Inter-Bold — detected in extracted data but not described by AI

### Inter-SemiBold — Inter-SemiBold — detected in extracted data but not described by AI · `--font-inter-semibold`
- **Weights:** 600
- **Sizes:** 12px
- **Line height:** 2
- **Letter spacing:** 0.083
- **Role:** Inter-SemiBold — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.14 | 0.083px | `--text-caption` |
| body | 14px | 1.33 | — | `--text-body` |
| heading | 24px | 1 | — | `--text-heading` |
| heading-lg | 32px | 1 | — | `--text-heading-lg` |
| display | 56px | 1 | — | `--text-display` |

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
| 60 | 60px | `--spacing-60` |
| 72 | 72px | `--spacing-72` |
| 96 | 96px | `--spacing-96` |
| 100 | 100px | `--spacing-100` |
| 168 | 168px | `--spacing-168` |
| 184 | 184px | `--spacing-184` |

### Border Radius

| Element | Value |
|---------|-------|
| pill | 43px |
| cards | 24px |
| buttons | 6px |
| default | 12px |

### Layout

- **Section gap:** 40px
- **Card padding:** 16px
- **Element gap:** 16px

## Components

### Secondary Ghost Button
**Role:** Navigational or secondary actions where visual prominence is low.

Text only, `sans-serif` at 12px, default browser blue text color (#0000ee - this is a system color, not branded). No discernible background or border in its ghost state.

### Outline Action Button (Nav)
**Role:** Navigation or login actions, indicating an interactive element without being primary.

Background: `Canvas White` (#ffffff), Text: default browser blue (#0000ee), Border: default browser blue (#0000ee), Radius: 43px, Padding: 8px vertical, 16px horizontal. Font: `sans-serif`.

### Ghost Accent Button
**Role:** Lightweight, secondary actions or internal links within content.

Background: `Sky Blue` (#ecf2ff), Text: black (#000000), Border: black (#000000), Radius: 6px, Padding: 4px vertical, 10px horizontal. Font: `sans-serif`.

### Primary Filled Button
**Role:** Main calls to action on the page, highly visible and interactive.

Background: `Action Blue` (#1a5fff), Text: default browser blue (#0000ee) (this is an unusual choice, effectively making the text visible by being the *same* as the active button 'color' for the browser default), Border: default browser blue (#0000ee) (again, usually a system default that would be overridden), Radius: 0px. Padding: 0px vertical, 60px horizontal. Font `sans-serif`.

### Testimonial Card
**Role:** Showcasing client feedback, a floating element with subtle visual depth.

Background: `Canvas White` (#ffffff), No border, No shadow, Radius: 24px, Padding: 0px.

### Feature Card
**Role:** Highlighting product features or key information blocks.

Background: `Sky Blue` (#ecf2ff), No border, No shadow, Radius: 24px, Padding: 24px.

### Content Block Card
**Role:** Encapsulating longer form textual content or aggregated information.

Background: `Canvas White` (#ffffff), No border, No shadow, Radius: 12px, Padding: 32px.

## Do's and Don'ts

### Do
- Prioritize `Action Blue` (#1a5fff) for primary calls to action, active states, and critical interactive elements.
- Use `Gopher` with a line height of 1.0 for all primary headings to maintain a dense, impactful visual.
- Employ `Canvas White` (#ffffff) as the default background for general page content and prominent cards.
- Utilize `Sky Blue` (#ecf2ff) for secondary background surfaces, subtle card backgrounds, or distinct content sections.
- Apply a `24px` border-radius to large cards and content blocks, and `6px` for buttons, to create a consistent soft aesthetic.
- Maintain a default `16px` element gap for vertical spacing between most content elements.
- Use `Midnight Ink` (#241f37) for all body copy and most important text elements.

### Don't
- Avoid using multiple vivid colors; reserve saturation primarily for `Action Blue` (#1a5fff) and sparingly for `Accent Orange` (#ff7a1a).
- Do not introduce sharp corners; consistently apply radii of at least `6px` on interactive elements and `12px` on cards.
- Refrain from heavy shadows or gradient backgrounds; surfaces should appear flat or with minimal, subtle tinting.
- Do not deviate from the specified font families and weight combinations; `Gopher` for headings, `Inter` for body/functional text.
- Avoid line heights greater than 1.6 for body text, or higher than 1.0 for headers, to prevent excessive vertical spacing.
- Do not use generic gray tones for text that are not `Midnight Ink` (#241f37) or black (#000000), as `Midnight Ink` is the established primary dark text color.
- Do not use highly textured backgrounds; stick to solid color fills, predominantly light neutrals.

## Imagery

The site uses a combination of product photography and abstract, colorful illustrations. Product photos feature tight crops of swag items (hats, stickers, shirts) arranged in grid-like patterns, often on a pure white or light gray background, highlighting the items themselves without lifestyle context. Illustrations are abstract and colorful, often rounded or organic in shape, serving as decorative accents or visual metaphors without strong outlines. Icons, when present, are simple and outlined with a medium stroke weight. Imagery primarily serves to showcase products and add decorative atmosphere without dominating the layout.

## Layout

The page primarily uses a max-width contained layout, with content sitting within a central column. The hero section features a prominent, left-aligned headline and text block, paired with a grid of product images on the right. Subsequent sections often employ an alternating text-left/visual-right pattern. Vertical spacing between sections is generous and consistent. Some sections use `Sky Blue` (#ecf2ff) or `Pale Peach` (#fff4ec) backgrounds to create visual breaks. Navigation is a sticky top bar with brand logo left and text links and an outlined button on the right.

## Agent Prompt Guide

Quick Color Reference:
- text: #241f37 (Midnight Ink)
- background: #ffffff (Canvas White)
- border: no distinct border color
- accent: #ff7a1a (Accent Orange)
- primary action: #1a5fff (filled action)

Example Component Prompts:
- Create a Hero Section headline: Gopher font, weight 500, 56px, line-height 1.0, color #241f37, no letter spacing. Text: 'Event Swag Management Without the Busywork.'
- Generate a Secondary Ghost Button: sans-serif font, 12px, default browser blue text color. Text: 'Case Studies'.
- Create a Primary Action Button: #1a5fff background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
- Create a Feature Card: Sky Blue background (#ecf2ff), 24px radius, 24px padding. Headline with Gopher font, weight 400, 24px, line-height 1.0, color #241f37. Body text with Inter font, weight 400, 14px, line-height 1.33, color #241f37.

## Similar Brands

- **Stripe** — Shares a clean white background, functional typography, and a single vibrant brand color for accents and CTAs.
- **Framer** — Similar use of generous spacing, soft rounded corners, and clear information hierarchy through typography on a light canvas.
- **Linear** — Employs an emphasis on crisp surfaces, restrained use of color, and high legibility with direct, sans-serif typography.
- **Webflow** — Features a light, spacious layout with a focus on product visuals and distinct, but not overwhelming, accent colors for interactivity.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #241f37;
  --color-canvas-white: #ffffff;
  --color-sky-blue: #ecf2ff;
  --color-pale-peach: #fff4ec;
  --color-mint-glaze: #edf9f5;
  --color-action-blue: #1a5fff;
  --color-accent-orange: #ff7a1a;
  --color-accent-green: #359774;

  /* Typography — Font Families */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gopher: 'Gopher', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter-bold: 'Inter-Bold', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter-semibold: 'Inter-SemiBold', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.14;
  --tracking-caption: 0.083px;
  --text-body: 14px;
  --leading-body: 1.33;
  --text-heading: 24px;
  --leading-heading: 1;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1;
  --text-display: 56px;
  --leading-display: 1;

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
  --spacing-48: 48px;
  --spacing-60: 60px;
  --spacing-72: 72px;
  --spacing-96: 96px;
  --spacing-100: 100px;
  --spacing-168: 168px;
  --spacing-184: 184px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 16px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-xl: 12px;
  --radius-3xl: 24px;
  --radius-3xl-2: 43px;

  /* Named Radii */
  --radius-pill: 43px;
  --radius-cards: 24px;
  --radius-buttons: 6px;
  --radius-default: 12px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #241f37;
  --color-canvas-white: #ffffff;
  --color-sky-blue: #ecf2ff;
  --color-pale-peach: #fff4ec;
  --color-mint-glaze: #edf9f5;
  --color-action-blue: #1a5fff;
  --color-accent-orange: #ff7a1a;
  --color-accent-green: #359774;

  /* Typography */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gopher: 'Gopher', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter-bold: 'Inter-Bold', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter-semibold: 'Inter-SemiBold', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.14;
  --tracking-caption: 0.083px;
  --text-body: 14px;
  --leading-body: 1.33;
  --text-heading: 24px;
  --leading-heading: 1;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1;
  --text-display: 56px;
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
  --spacing-60: 60px;
  --spacing-72: 72px;
  --spacing-96: 96px;
  --spacing-100: 100px;
  --spacing-168: 168px;
  --spacing-184: 184px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-xl: 12px;
  --radius-3xl: 24px;
  --radius-3xl-2: 43px;
}
```

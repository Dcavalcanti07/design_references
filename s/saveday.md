# SaveDay — Style Reference
> Industrial Scanner Clarity

**Theme:** light

SaveDay uses a bold, monochrome industrial scanner aesthetic: high-contrast black text on white or light gray surfaces dominates, providing a no-nonsense, functional atmosphere. Key sections and interactive elements are highlighted with a vibrant, almost neon yellow, acting as a functional accent rather than decorative flourish. Typography is dense and commanding, especially for headings, contrasting with crisp, minimal UI elements.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card surfaces, primary text on dark backgrounds |
| Midnight Black | `#0d0d0d` | `--color-midnight-black` | Primary text, prominent headings, borders for contrast elements |
| Deepest Ink | `#000000` | `--color-deepest-ink` | Dark borders and separators for elevated surfaces and inverted UI. Do not promote it to the primary CTA color |
| Cool Mist | `#edeef0` | `--color-cool-mist` | Hairline borders, dividers, input outlines, and card edges on light surfaces. Do not promote it to the primary CTA color |
| Pinstripe Gray | `#e5e4e3` | `--color-pinstripe-gray` | Subtle background for alternating sections, secondary card surfaces |
| Ash Cloud | `#999999` | `--color-ash-cloud` | Muted text, list item borders, decorative strokes |
| Cloud Shadow | `#cccccc` | `--color-cloud-shadow` | Subtle shadow color for cards, decorative fills |
| Graphite | `#333333` | `--color-graphite` | Darker card backgrounds, iconography |
| Scanner Yellow | `#fbda5f` | `--color-scanner-yellow` | Yellow accent for outlined action borders, linked labels, and lightweight interactive emphasis. Do not promote it to the primary CTA color |
| System Blue | `#006aff` | `--color-system-blue` | Default link color, accent for specific interactive elements |

## Tokens — Typography

### Phudu — Dominant display font for primary headings and impactful statements. Its condensed, robust character adds a sense of urgency and directness. Weight 700 creates strong visual presence. Letter-spacing is aggressively tight (-0.03em) at large sizes, fitting many characters into headlines and creating a dense, impactful block of text. · `--font-phudu`
- **Substitute:** Bebas Neue
- **Weights:** 400, 700
- **Sizes:** 24px, 32px, 56px, 64px, 112px
- **Line height:** 0.90, 1.00
- **Letter spacing:** -0.0300em, -0.0200em
- **Role:** Dominant display font for primary headings and impactful statements. Its condensed, robust character adds a sense of urgency and directness. Weight 700 creates strong visual presence. Letter-spacing is aggressively tight (-0.03em) at large sizes, fitting many characters into headlines and creating a dense, impactful block of text.

### Interdisplay — Versatile sans-serif for body text, subheadings, navigation, and interactive elements. Its wide range of weights and optical sizing capabilities (implied by 'display' in name) ensures readability across roles. Tighter letter-spacing on larger sizes (-0.024em at 24px) maintains a compact, efficient feel. · `--font-interdisplay`
- **Substitute:** Inter
- **Weights:** 400, 500, 600, 700
- **Sizes:** 16px, 18px, 20px, 24px
- **Line height:** 0.90, 1.00, 1.20, 1.30, 1.50
- **Letter spacing:** -0.0400em, -0.0240em, -0.0200em, -0.0180em, 0.0100em
- **Role:** Versatile sans-serif for body text, subheadings, navigation, and interactive elements. Its wide range of weights and optical sizing capabilities (implied by 'display' in name) ensures readability across roles. Tighter letter-spacing on larger sizes (-0.024em at 24px) maintains a compact, efficient feel.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body | 16px | 1.5 | 0.16px | `--text-body` |
| subheading | 20px | 1.2 | -0.4px | `--text-subheading` |
| heading | 32px | 1 | -0.96px | `--text-heading` |
| heading-lg | 56px | 0.9 | -1.68px | `--text-heading-lg` |
| display | 112px | 0.9 | -3.36px | `--text-display` |

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
| 64 | 64px | `--spacing-64` |
| 72 | 72px | `--spacing-72` |

### Border Radius

| Element | Value |
|---------|-------|
| pill | 1600px |
| tags | 30px |
| cards | 16px |
| input | 12px |
| buttons | 160px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| lg | `rgba(0, 0, 0, 0.2) 0px 0px 20px -16px` | `--shadow-lg` |

### Layout

- **Section gap:** 48px
- **Card padding:** 16px
- **Element gap:** 16px

## Components

### Primary Navigation Link
**Role:** Top navigation item

Text link in Midnight Black (#0d0d0d) using Interdisplay at 16px. No background or border. Actively a 'ghost' style.

### Outline Action Button - Chrome
**Role:** Primary call to action in header

Text 'Add to Chrome' in Midnight Black (#0d0d0d) on a Canvas White (#ffffff) background, with a 1px Scanner Yellow (#fbda5f) border and 160px border-radius. Interdisplay font, 16px, weight 400. Padding around text is implied to be comfortable for a button, using elementGap.

### Filled Action Button - Try Now
**Role:** Secondary call to action in header

Text 'Try now' in Midnight Black (#0d0d0d) on a Scanner Yellow (#fbda5f) background, with no border and a 160px border-radius. Interdisplay font, 16px, weight 400. Ample horizontal padding using an elementGap multiple.

### Chrome Web Store Button
**Role:** Inline call to action for extension installation

Text 'Install from Chrome Web Store' in Midnight Black (#0d0d0d) on a Scanner Yellow (#fbda5f) background, no border, with 160px border-radius. Includes a small icon. Interdisplay font, 16px. Uses 19px vertical and 40px horizontal padding.

### Text Section Card - Gray
**Role:** Background for descriptive text sections

Card with Cool Mist (#edeef0) background, 16px border-radius, no shadow. Text content is Midnight Black (#0d0d0d). Uses 32px vertical and 16px horizontal padding.

### Text Section Card - Yellow
**Role:** Highlighted background for descriptive text sections

Card with Scanner Yellow (#fbda5f) background, 24px border-radius, no shadow. Text content is Midnight Black (#0d0d0d). Uses 24px vertical and 19px horizontal padding.

### FAQ Accordion Item
**Role:** Interactive question and answer element

Card with Canvas White (#ffffff) background, 24px border-radius, and a subtle shadow (rgba(0, 0, 0, 0.2) 0px 0px 20px -16px). Contains a question in Midnight Black (#0d0d0d) with an icon in the same color, using 16px vertical and 8px horizontal padding.

### Footer Callout Card
**Role:** Prominent final call to action at the bottom of the page

Card with Deepest Ink (#000000) background, large 24px border-radius. Features a large heading in Scanner Yellow (#fbda5f) from the Phudu typeface. Ample padding to center content with 32px vertical and 32px horizontal.

## Do's and Don'ts

### Do
- Use Midnight Black (#0d0d0d) or Deepest Ink (#000000) for all primary text on light backgrounds to maintain high contrast.
- Apply Scanner Yellow (#fbda5f) exclusively for primary calls to action, section highlights, and active/focused states.
- Set large headlines with Phudu weight 700 and aggressively tight letter-spacing (-0.03em or -0.02em) to create dense, impactful text blocks.
- Use Interdisplay at 16px for all body copy and less prominent links, with a line height of 1.5 for readability.
- Employ a 160px border-radius for all buttons and 'pill-shaped' elements to create a distinctive soft, elongated shape.
- Utilize Cool Mist (#edeef0) for secondary content backgrounds and background elements that need to subtly stand out from Canvas White (#ffffff).
- Maintain a clear vertical rhythm with section gaps at 48px, consistent with the comfortable density of the page.

### Don't
- Do not use Scanner Yellow (#fbda5f) for decorative purposes or pure illustration, reserve it for functional highlights.
- Avoid using multiple font sizes directly adjacent that are not part of the defined type scale, to prevent visual clutter.
- Do not introduce strong accent colors other than System Blue (#006aff) without explicit branding approval.
- Prevent cards from having heavy shadows; use the subtle rgba(0, 0, 0, 0.2) 0px 0px 20px -16px card shadow for minimal elevation.
- Do not use letter-spacing values tighter than -0.04em for any text, even at large sizes, to avoid unreadable overlaps.
- Avoid using bold or semi-bold weights for body text; reserve stronger weights for headings and essential labels.
- Do not create circular buttons; always adhere to the 160px 'pill' radius for interactive elements.

## Elevation

- **Card:** `rgba(0, 0, 0, 0.2) 0px 0px 20px -16px`

## Imagery

This design system primarily emphasizes UI and typography over rich imagery. When present, images are functional. Icons are minimalist, utilizing either Deepest Ink (#000000) fills or thin strokes. Product logos are presented in monochrome (black or white). The design avoids decorative photography or complex illustrations, focusing instead on stark, high-contrast textual presentation.

## Layout

The page uses a maximum-width contained layout, though the exact max-width is not strictly defined, allowing content to stretch comfortably. The hero section is full-width with a commanding centered Phudu headline over a white background. Subsequent sections alternate between white, Cool Mist (#edeef0), or Pinstripe Gray (#e5e4e3) backgrounds, with prominent Scanner Yellow (#fbda5f) sections marking key feature explanations. Content is generally centered or uses a simple vertical stacked arrangement. Feature descriptions often utilize a distinct card-like background that creates visual breaking points. A grid of app store badges is used for platform links. Vertical rhythm is consistent with comfortable section gaps.

## Agent Prompt Guide

Quick Color Reference: 
- text: #0d0d0d
- background: #ffffff
- border: #0d0d0d
- accent: #fbda5f
- primary action: #fbda5f (outlined action border)

Example Component Prompts:
- Create an Outlined Primary Action: Transparent background, #fbda5f border and text, 9999px radius, compact pill padding. Use it for the main CTA instead of a filled button.
- Design a feature card for 'CAPTURE EASILY' with a Cool Mist (#edeef0) background, 16px border-radius, no shadow, using Phudu weight 700 at 32px for the heading in Midnight Black (#0d0d0d). Include body text using Interdisplay 16px, color Midnight Black (#0d0d0d). Use 32px vertical and 16px horizontal padding.

## Similar Brands

- **Raycast** — High-contrast UI, heavy typographic emphasis, and a focused accent color for interaction, creating a 'productivity tool' feel.
- **Notion** — Monochrome canvas-like interface with strong typographic hierarchy for information organization, minimizing visual distractions.
- **Superhuman** — Functional, fast-feeling interface with minimal chrome, relying on sharp typography and targeted accent colors to highlight core actions.
- **Linear** — Very strong emphasis on typography and white space, with color used sparingly but effectively to denote status and interaction.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-midnight-black: #0d0d0d;
  --color-deepest-ink: #000000;
  --color-cool-mist: #edeef0;
  --color-pinstripe-gray: #e5e4e3;
  --color-ash-cloud: #999999;
  --color-cloud-shadow: #cccccc;
  --color-graphite: #333333;
  --color-scanner-yellow: #fbda5f;
  --color-system-blue: #006aff;

  /* Typography — Font Families */
  --font-phudu: 'Phudu', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-interdisplay: 'Interdisplay', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: 0.16px;
  --text-subheading: 20px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.4px;
  --text-heading: 32px;
  --leading-heading: 1;
  --tracking-heading: -0.96px;
  --text-heading-lg: 56px;
  --leading-heading-lg: 0.9;
  --tracking-heading-lg: -1.68px;
  --text-display: 112px;
  --leading-display: 0.9;
  --tracking-display: -3.36px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-72: 72px;

  /* Layout */
  --section-gap: 48px;
  --card-padding: 16px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 30px;
  --radius-full: 160px;
  --radius-full-2: 1600px;

  /* Named Radii */
  --radius-pill: 1600px;
  --radius-tags: 30px;
  --radius-cards: 16px;
  --radius-input: 12px;
  --radius-buttons: 160px;

  /* Shadows */
  --shadow-lg: rgba(0, 0, 0, 0.2) 0px 0px 20px -16px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-midnight-black: #0d0d0d;
  --color-deepest-ink: #000000;
  --color-cool-mist: #edeef0;
  --color-pinstripe-gray: #e5e4e3;
  --color-ash-cloud: #999999;
  --color-cloud-shadow: #cccccc;
  --color-graphite: #333333;
  --color-scanner-yellow: #fbda5f;
  --color-system-blue: #006aff;

  /* Typography */
  --font-phudu: 'Phudu', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-interdisplay: 'Interdisplay', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: 0.16px;
  --text-subheading: 20px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.4px;
  --text-heading: 32px;
  --leading-heading: 1;
  --tracking-heading: -0.96px;
  --text-heading-lg: 56px;
  --leading-heading-lg: 0.9;
  --tracking-heading-lg: -1.68px;
  --text-display: 112px;
  --leading-display: 0.9;
  --tracking-display: -3.36px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-72: 72px;

  /* Border Radius */
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 30px;
  --radius-full: 160px;
  --radius-full-2: 1600px;

  /* Shadows */
  --shadow-lg: rgba(0, 0, 0, 0.2) 0px 0px 20px -16px;
}
```

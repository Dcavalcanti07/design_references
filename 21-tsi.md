# 21 TSI — Style Reference
> Minimalist Cinematic Canvas

**Theme:** dark

21 TSI employs a bold, minimal dark aesthetic focusing on full-bleed imagery and stark typography. Interactivity is suggested through subtle hovers and outlines, reserving visual weight for large, impactful headlines. The system balances a comfortable density with strong visual statements, using a limited color palette to maintain a serious, focused tone. Motion is expressive, reinforcing dynamic content.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Absolute Zero | `#000000` | `--color-absolute-zero` | Page backgrounds, element borders, default button borders — a true black canvas for high contrast |
| Canvas White | `#ffffff` | `--color-canvas-white` | Hairline borders, dividers, input outlines, and card edges on light surfaces. Do not promote it to the primary CTA color |
| Iron Gray | `#4d4d4d` | `--color-iron-gray` | Secondary borders and subtle background treatments, providing a slightly softer black for layered surfaces |
| Base Background | `#161a1c` | `--color-base-background` | Primary background for sections and larger content blocks |
| Text Primary | `#ebf3f6` | `--color-text-primary` | Main body text, providing high readability against dark backgrounds |
| Text Secondary | `#aebbc5` | `--color-text-secondary` | Muted text, helper text, and secondary information |
| Button Control | `#c2d0e0` | `--color-button-control` | Supporting palette color for small decorative accents when the core palette needs contrast. Do not promote it to the primary CTA color |
| Button Hover | `#98a7b6` | `--color-button-hover` | Hover state for primary buttons, indicating interactivity |
| Secondary Button | `#242c31` | `--color-secondary-button` | Background for secondary buttons, a darker, more subdued option |
| Secondary Button Hover | `#353d43` | `--color-secondary-button-hover` | Hover state for secondary buttons and subtle border highlights |
| Separator Line | `#222a30` | `--color-separator-line` | Divider lines and subtle structural borders |
| Toggle Off | `#525f6b` | `--color-toggle-off` | Background color for off-state toggles |
| Toggle Knob | `#5f6b72` | `--color-toggle-knob` | Knob color for read-only toggles |
| Cookie Block | `#1e2428` | `--color-cookie-block` | Background and border for cookie category blocks |

## Tokens — Typography

### Saans — Primary typeface across all elements. Its custom nature and very light weights (300, 380) for large display settings, balanced with heavier weights for emphasis, create a distinctively airy yet authoritative feel. Letter spacing is subtly adjusted for readability at varying scales: condensed for large headlines, normal for body text. · `--font-saans`
- **Substitute:** Inter
- **Weights:** 300, 380, 570, 790
- **Sizes:** 12px, 14px, 16px, 18px, 20px, 47px, 79px, 106px, 130px, 136px, 245px
- **Line height:** 1.00, 1.11, 1.14, 1.15, 1.22, 1.30, 1.38, 1.40, 1.43
- **Letter spacing:** -0.0250em for large headlines, 0.0500em for smaller text.
- **Role:** Primary typeface across all elements. Its custom nature and very light weights (300, 380) for large display settings, balanced with heavier weights for emphasis, create a distinctively airy yet authoritative feel. Letter spacing is subtly adjusted for readability at varying scales: condensed for large headlines, normal for body text.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.22 | — | `--text-caption` |
| body-sm | 14px | 1.22 | — | `--text-body-sm` |
| body | 18px | 1.22 | — | `--text-body` |
| body-lg | 20px | 1.22 | — | `--text-body-lg` |
| heading-sm | 47px | 1.22 | — | `--text-heading-sm` |
| heading | 79px | 1.22 | — | `--text-heading` |
| heading-lg | 130px | 1.22 | — | `--text-heading-lg` |
| display-sm | 136px | 1.22 | — | `--text-display-sm` |
| display | 245px | 1.22 | — | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 10 | 10px | `--spacing-10` |
| 11 | 11px | `--spacing-11` |
| 15 | 15px | `--spacing-15` |
| 19 | 19px | `--spacing-19` |
| 20 | 20px | `--spacing-20` |
| 23 | 23px | `--spacing-23` |
| 27 | 27px | `--spacing-27` |
| 30 | 30px | `--spacing-30` |
| 36 | 36px | `--spacing-36` |
| 38 | 38px | `--spacing-38` |
| 60 | 60px | `--spacing-60` |
| 63 | 63px | `--spacing-63` |
| 108 | 108px | `--spacing-108` |
| 150 | 150px | `--spacing-150` |
| 172 | 172px | `--spacing-172` |

### Border Radius

| Element | Value |
|---------|-------|
| buttons | 70px |
| default | 8px |
| circularElements | 594px |

### Layout

- **Page max-width:** 1350px
- **Section gap:** 30px
- **Card padding:** 20px
- **Element gap:** 20px

## Components

### Navigation Link
**Role:** Top-level navigation items.

Text in Canvas White (#ffffff) with 0px border-radius and 0px padding. Hover states are implied by text color change or subtle underlines.

### Outline Pill Button (Small)
**Role:** Interactive controls with a distinct pill shape.

Background transparent, text Canvas White (#ffffff), border 1px solid Absolute Zero (#000000). Border-radius 70px. Padding 7px top, 20px right, 8px bottom, 35px left.

### Outline Pill Button (Medium)
**Role:** Primary interactive controls with a distinct pill shape and contrasting outline.

Background transparent, text Canvas White (#ffffff), border 1px solid Canvas White (#ffffff). Border-radius 70px. Padding 10px top, 20px right, 10px bottom, 20px left.

### Text Link
**Role:** Inline textual links and footers.

Text in Canvas White (#ffffff) with no background or border.

## Do's and Don'ts

### Do
- Prioritize high contrast between text and background, typically using Canvas White (#ffffff) on Absolute Zero (#000000) or rich dark neutrals.
- Use Saans weight 300 or 380 for large headlines to maintain an airy, understated authority.
- Implement the 70px border-radius for all interactive buttons to create a consistent pill-shaped aesthetic.
- Maintain comfortable spacing with `elementGap` at 20px and `sectionGap` at 30px to prevent visual clutter within the dark theme.
- Apply `blur(15px)` for any background elements intended for atmospheric effect or content obscuration.
- For all interactive elements, ensure smooth transitions over 0.2s to 0.6s with `ease` timing functions.
- All page content should be contained within a `pageMaxWidth` of 1350px, ensuring a focused content area.

### Don't
- Avoid using highly saturated colors for anything other than specific, small accent elements, as they contrast with the minimalist dark palette.
- Do not use generic square buttons; always apply the 70px border-radius for pill shapes or 0px for minimal, unadorned links.
- Do not dilute the stark contrast; avoid low-contrast text on dark backgrounds that isn't explicitly intended as secondary or muted.
- Avoid excessive use of borders; borders should be minimal, 1px thin, and either match the background or provide a subtle highlight (e.g., Canvas White or Iron Gray).
- Do not break the expressive animation philosophy; transitions should primarily involve `transform`, `opacity`, and `filter`, with non-linear `cubic-bezier` timing functions for dynamic movement.
- Do not introduce unnecessary shadows; the design relies on flat planes and subtle blurs for depth.
- Avoid breaking the established letter-spacing; use condensed spacing for larger headlines and normal for body text as per Saans typeface specification.

## Imagery

The site heavily features high-quality, full-bleed photography, often with a blurred or motion-streaked effect against monochromatic backgrounds of deep reds or oranges. The subjects are typically human figures in dynamic poses, hinting at sports or activity, often silhouetted or with dramatic lighting to enhance mood over detailed clarity. Imagery serves as atmospheric backdrop rather than literal explanation, creating an immersive, cinematic feel. Icons, if present, are minimal and likely outlined, aligning with the clean UI.

## Agent Prompt Guide

Quick Color Reference:
- text: #ebf3f6
- background: #000000
- border: #ffffff
- accent: no distinct accent color
- primary action: no distinct CTA color

Example Component Prompts:
- Create a minimal navigation link: 'THE SPHERE LAB' in Saans weight 380, Canvas White (#ffffff) text, no background or border, 0px padding.
- Create a small outlined pill button for contact: 'CONTACT' in Saans weight 380, Canvas White (#ffffff) text, transparent background, 1px solid Canvas White (#ffffff) border, 70px border-radius, 7px top padding, 20px right padding, 8px bottom padding, 35px left padding.
- Create a section headline: 'Everyone Hates Change But...' in Saans weight 790, Canvas White (#ffffff) text (size will vary based on scale), with -0.0250em letter spacing, centered on a Base Background (#161a1c).
- Create a paragraph of body text: 'Global Revenue' in Saans weight 300, Text Primary (#ebf3f6) text, over a Base Background (#161a1c).

## Similar Brands

- **Nike** — Shares a focus on high-impact, full-bleed photography of athletes in motion, often with blurred backgrounds and strong visual contrast for overlaid text.
- **Apple** — Uses a minimalist approach with ample white space (or dark space in this case), large typography, and a reduced color palette to emphasize content and product.
- **Squarespace** — Known for clean, professional aesthetics, large imagery, and strong typographic hierarchy with minimal UI elements.
- **Framer** — A modern digital product that similarly uses a dark theme, refined typography, and subtle interactive states to create a sophisticated, high-tech impression.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-absolute-zero: #000000;
  --color-canvas-white: #ffffff;
  --color-iron-gray: #4d4d4d;
  --color-base-background: #161a1c;
  --color-text-primary: #ebf3f6;
  --color-text-secondary: #aebbc5;
  --color-button-control: #c2d0e0;
  --color-button-hover: #98a7b6;
  --color-secondary-button: #242c31;
  --color-secondary-button-hover: #353d43;
  --color-separator-line: #222a30;
  --color-toggle-off: #525f6b;
  --color-toggle-knob: #5f6b72;
  --color-cookie-block: #1e2428;

  /* Typography — Font Families */
  --font-saans: 'Saans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.22;
  --text-body-sm: 14px;
  --leading-body-sm: 1.22;
  --text-body: 18px;
  --leading-body: 1.22;
  --text-body-lg: 20px;
  --leading-body-lg: 1.22;
  --text-heading-sm: 47px;
  --leading-heading-sm: 1.22;
  --text-heading: 79px;
  --leading-heading: 1.22;
  --text-heading-lg: 130px;
  --leading-heading-lg: 1.22;
  --text-display-sm: 136px;
  --leading-display-sm: 1.22;
  --text-display: 245px;
  --leading-display: 1.22;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-w380: 380;
  --font-weight-w570: 570;
  --font-weight-w790: 790;

  /* Spacing */
  --spacing-10: 10px;
  --spacing-11: 11px;
  --spacing-15: 15px;
  --spacing-19: 19px;
  --spacing-20: 20px;
  --spacing-23: 23px;
  --spacing-27: 27px;
  --spacing-30: 30px;
  --spacing-36: 36px;
  --spacing-38: 38px;
  --spacing-60: 60px;
  --spacing-63: 63px;
  --spacing-108: 108px;
  --spacing-150: 150px;
  --spacing-172: 172px;

  /* Layout */
  --page-max-width: 1350px;
  --section-gap: 30px;
  --card-padding: 20px;
  --element-gap: 20px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-full: 70px;
  --radius-full-2: 594px;

  /* Named Radii */
  --radius-buttons: 70px;
  --radius-default: 8px;
  --radius-circularelements: 594px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-absolute-zero: #000000;
  --color-canvas-white: #ffffff;
  --color-iron-gray: #4d4d4d;
  --color-base-background: #161a1c;
  --color-text-primary: #ebf3f6;
  --color-text-secondary: #aebbc5;
  --color-button-control: #c2d0e0;
  --color-button-hover: #98a7b6;
  --color-secondary-button: #242c31;
  --color-secondary-button-hover: #353d43;
  --color-separator-line: #222a30;
  --color-toggle-off: #525f6b;
  --color-toggle-knob: #5f6b72;
  --color-cookie-block: #1e2428;

  /* Typography */
  --font-saans: 'Saans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.22;
  --text-body-sm: 14px;
  --leading-body-sm: 1.22;
  --text-body: 18px;
  --leading-body: 1.22;
  --text-body-lg: 20px;
  --leading-body-lg: 1.22;
  --text-heading-sm: 47px;
  --leading-heading-sm: 1.22;
  --text-heading: 79px;
  --leading-heading: 1.22;
  --text-heading-lg: 130px;
  --leading-heading-lg: 1.22;
  --text-display-sm: 136px;
  --leading-display-sm: 1.22;
  --text-display: 245px;
  --leading-display: 1.22;

  /* Spacing */
  --spacing-10: 10px;
  --spacing-11: 11px;
  --spacing-15: 15px;
  --spacing-19: 19px;
  --spacing-20: 20px;
  --spacing-23: 23px;
  --spacing-27: 27px;
  --spacing-30: 30px;
  --spacing-36: 36px;
  --spacing-38: 38px;
  --spacing-60: 60px;
  --spacing-63: 63px;
  --spacing-108: 108px;
  --spacing-150: 150px;
  --spacing-172: 172px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-full: 70px;
  --radius-full-2: 594px;
}
```

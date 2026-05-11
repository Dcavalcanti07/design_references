# Vivid+Co — Style Reference
> Midnight refractography. A dark, expansive canvas lit by precise typography and spectral light refractions.

**Theme:** dark

Vivid+Co employs a command-center dark theme, focusing on high contrast and dramatic impact. Large, confident typography dominates the layout, using subtle letter-spacing adjustments to control visual flow. The absence of strong chromatic accents outside of a single, muted gray for functional elements keeps the aesthetic clean and focused, punctuated by the refractive visuals. Components are minimalist, relying on precise typography and ghost-like interactive states rather than heavy fills or shadows.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas Ink | `#000000` | `--color-canvas-ink` | Page backgrounds, decorative fills for icons and illustrations, establishing high contrast for primary text |
| Refined White | `#fffdf9` | `--color-refined-white` | Hairline borders, dividers, input outlines, and card edges on light surfaces. Do not promote it to the primary CTA color |
| Stonewash Gray | `#6f879c` | `--color-stonewash-gray` | Muted text, hairline borders for ghost buttons and interactive elements, providing a subtle interactive cue without drawing strong attention to itself |
| Outline Gray | `#403f3f` | `--color-outline-gray` | Subtle borders and dividers, indicating secondary separation or structure |

## Tokens — Typography

### Neue Montreal — This custom sans-serif is the sole typeface, used for all textual elements. Its wide range of weights and sizes, combined with precise, often negative, letter-spacing in larger headlines, creates a feeling of meticulous design and clear statement, rather than decorative flair. It's concise and impactful. · `--font-neue-montreal`
- **Substitute:** Inter
- **Weights:** 400, 700
- **Sizes:** 14px, 15px, 17px, 18px, 20px, 21px, 22px, 32px, 33px, 36px, 56px, 105px, 136px
- **Line height:** 1.00, 1.01, 1.13, 1.17, 1.20, 1.24, 1.50
- **Letter spacing:** -0.0200em at 136px, -0.0100em at 56px, 0.0100em at 36px, 0.0200em at 14px
- **Role:** This custom sans-serif is the sole typeface, used for all textual elements. Its wide range of weights and sizes, combined with precise, often negative, letter-spacing in larger headlines, creates a feeling of meticulous design and clear statement, rather than decorative flair. It's concise and impactful.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 14px | 1.5 | 0.28px | `--text-caption` |
| body | 17px | 1.5 | 0.17px | `--text-body` |
| subheading | 32px | 1.24 | 0.32px | `--text-subheading` |
| heading | 36px | 1.17 | 0.36px | `--text-heading` |
| heading-lg | 56px | 1.13 | -0.56px | `--text-heading-lg` |
| display | 136px | 1 | -2.72px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 40 | 40px | `--spacing-40` |
| 56 | 56px | `--spacing-56` |
| 60 | 60px | `--spacing-60` |
| 64 | 64px | `--spacing-64` |
| 72 | 72px | `--spacing-72` |
| 108 | 108px | `--spacing-108` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 15px |
| default | 0px |
| navItems | 5px |

### Layout

- **Section gap:** 108px
- **Card padding:** 20px
- **Element gap:** 7px

## Components

### Navigation Link (Active)
**Role:** Primary navigation item, active state

Text: Neue Montreal, 15px, Refined White (#fffdf9), weight 400. Has a 0px border-radius, `padding-top: 9px`, `padding-bottom: 9px`, and a 1px solid bottom border in Refined White.

### Navigation Link (Default)
**Role:** Primary navigation item, default state

Text: Neue Montreal, 15px, Refined White (#fffdf9), weight 400. No visible border.

### Ghost Button (Primary Action)
**Role:** Call-to-action button, outlined style

Text: Neue Montreal, size derived from context, Stonewash Gray (#6f879c), weight 400. No background, transparent `padding-top: 20px`, `padding-bottom: 30px`, with a 1px solid border in Stonewash Gray (#6f879c). No border radius for a sharp, modern edge.

### Text Button (Subtle)
**Role:** Secondary action or categorized link

Text: Neue Montreal, size derived from context, Refined White (#fffdf9), weight 400. Transparent background, `padding-top: 0`, `padding-bottom: 0`. No border, 0px border-radius.

### Feature Card
**Role:** Container for content blocks

Implicit card structure, has a 15px border-radius. Padding is `20px` in some contexts. No explicit background color change from canvas, relies on content and typography for definition.

## Do's and Don'ts

### Do
- Prioritize Canvas Ink (#000000) for all main backgrounds to maintain the dark, dramatic aesthetic.
- Use Refined White (#fffdf9) exclusively for primary text and high-visibility interactive elements like navigation.
- Apply Stonewash Gray (#6f879c) for ghost button borders and subtle text, reserving it for functional yet understated elements.
- Utilize Neue Montreal universally across all text, carefully applying its range of weights and the corresponding letter-spacing tokens for visual hierarchy.
- Maintain the 0px border-radius for buttons and most structural elements to uphold a sharp, angular design language, only using 15px for distinct card-like containers and 5px for very specific interactive elements.
- Ensure large headlines employ negative letter-spacing (-0.0200em at 136px, -0.0100em at 56px) for a tight, impactful appearance.
- Implement motion with `ease` timing functions and durations of `0.5s` for smooth visual transitions, particularly for `transform` and `opacity` properties.

### Don't
- Do not introduce additional saturated colors; maintain the monochrome palette with Stonewash Gray as the only chromatic accent.
- Avoid box-shadows or significant elevation; the design relies on flat surfaces and high contrast for definition.
- Do not use generic system fonts; Neue Montreal is critical for brand personality.
- Don't use large positive letter-spacing for headlines; it will diminish the brand's distinct tight typographic style.
- Avoid visual dividers between content sections; rely on generous vertical spacing (`108px` section gap) to separate content blocks.
- Do not vary border radii arbitrarily; stick to 0px, 5px, or 15px as specified for their respective contexts.
- Do not add heavy background fills to buttons; they should remain ghost-like or text-only to preserve the lightweight feel.

## Imagery

The site uses abstract, photorealistic 3D renders of translucent, refractive geometric objects (cubes) as its primary visual motif. These visuals are full-bleed on a dark background, often with lens flare effects, creating spectral light and color shifts within the objects themselves, but not introducing broader chromatic elements into the UI. Imagery serves a decorative, atmospheric role, representing complexity and precision without being literal. Icons are minimalist, typically white outlines or fills, maintaining the high-contrast monochromatic UI.

## Layout

The page operates on a full-bleed model with content primarily centered, featuring a maximum width for body text but allowing hero sections and atmospheric graphics to extend edge-to-edge. The hero section is a full-viewport dark background with large, centered headlines and associated body text. Vertical rhythm is established through significant section gaps of `108px`. Content often appears in alternating single-column centered stacks or implied two-column text+visual arrangements without explicit grid lines. The navigation is a fixed top bar with minimalist links.

## Agent Prompt Guide

Quick Color Reference:
text: #fffdf9
background: #000000
border: #6f879c
accent: #6f879c
primary action: #6f879c (outlined action border)

Example Component Prompts:
1. Create a hero section: Canvas Ink (#000000) full-bleed background. Centered headline 'We are Marketers' in Refined White (#fffdf9), Neue Montreal, 136px, weight 700, letter-spacing -2.72px. Below it, add body text 'A full-service agency and strategic advisor partnering with visionaries to solve their toughest challenges.' in Refined White (#fffdf9), Neue Montreal, 22px, weight 400, line height 1.24, centered, max-width appropriate for readability.
2. Design a ghost button labeled 'Learn More': Neue Montreal, 17px, weight 400, Stonewash Gray (#6f879c) text and 1px solid border, `padding-top: 20px`, `padding-bottom: 30px`, 0px border-radius, Canvas Ink (#000000) background. No box shadow.
3. Implement a navigation item 'Expertise': Refined White (#fffdf9) text, Neue Montreal, 15px, weight 400, 0px border-radius, opacity 0.7 on hover. No background. `padding-top: 9px`, `padding-bottom: 9px`.

## Similar Brands

- **Huge Inc** — Dark UI, large dramatic typography, and minimal use of color accents with atmospheric abstract visuals.
- **ACNE** — High-impact, full-screen dark visuals with bold, often oversized and tightly tracked typography.
- **Basic/Dept** — Elegant dark themes with a focus on refined typography and subtle interactive states, minimal use of strong colors.
- **Work & Co** — Employs full-bleed dramatic visuals and a clean typographic hierarchy over a predominantly dark background.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-ink: #000000;
  --color-refined-white: #fffdf9;
  --color-stonewash-gray: #6f879c;
  --color-outline-gray: #403f3f;

  /* Typography — Font Families */
  --font-neue-montreal: 'Neue Montreal', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.5;
  --tracking-caption: 0.28px;
  --text-body: 17px;
  --leading-body: 1.5;
  --tracking-body: 0.17px;
  --text-subheading: 32px;
  --leading-subheading: 1.24;
  --tracking-subheading: 0.32px;
  --text-heading: 36px;
  --leading-heading: 1.17;
  --tracking-heading: 0.36px;
  --text-heading-lg: 56px;
  --leading-heading-lg: 1.13;
  --tracking-heading-lg: -0.56px;
  --text-display: 136px;
  --leading-display: 1;
  --tracking-display: -2.72px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-40: 40px;
  --spacing-56: 56px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-108: 108px;

  /* Layout */
  --section-gap: 108px;
  --card-padding: 20px;
  --element-gap: 7px;

  /* Border Radius */
  --radius-md: 5px;
  --radius-xl: 15px;

  /* Named Radii */
  --radius-cards: 15px;
  --radius-default: 0px;
  --radius-navitems: 5px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-ink: #000000;
  --color-refined-white: #fffdf9;
  --color-stonewash-gray: #6f879c;
  --color-outline-gray: #403f3f;

  /* Typography */
  --font-neue-montreal: 'Neue Montreal', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.5;
  --tracking-caption: 0.28px;
  --text-body: 17px;
  --leading-body: 1.5;
  --tracking-body: 0.17px;
  --text-subheading: 32px;
  --leading-subheading: 1.24;
  --tracking-subheading: 0.32px;
  --text-heading: 36px;
  --leading-heading: 1.17;
  --tracking-heading: 0.36px;
  --text-heading-lg: 56px;
  --leading-heading-lg: 1.13;
  --tracking-heading-lg: -0.56px;
  --text-display: 136px;
  --leading-display: 1;
  --tracking-display: -2.72px;

  /* Spacing */
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-40: 40px;
  --spacing-56: 56px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-108: 108px;

  /* Border Radius */
  --radius-md: 5px;
  --radius-xl: 15px;
}
```

# Navan — Style Reference
> Deep Violet Efficiency – like a meticulously organized business travel brief, dark and precise yet subtly inviting.

**Theme:** light

This design system projects an image of sophisticated efficiency, using a deep violet primary, Navan Ink, grounded by a crisp white and muted grays. It achieves a balance between corporate authority and modern approachability through its meticulous typography, showcasing delicate letter-spacing on display fonts and precise line-heights. The overall impression is one of trusted expertise, made accessible by subtle gradients and refined component styling.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Navan Ink | `#15002c` | `--color-navan-ink` | Primary brand color, darkest text, primary navigation background in footer – establishes a deep, authoritative base. |
| Action Violet | `#6307f8` | `--color-action-violet` | Dominant CTA button background – provides a vivid, energetic contrast against backgrounds to drive interaction. |
| Hero Gradient Purple | `radial-gradient(197.36% 161.87% at 4.08% 0%, rgba(65, 5, 102, 0.75) 6.19%, rgba(124, 81, 250, 0.75) 52.28%, rgba(255, 181, 206, 0.75) 91.18%)` | `--color-hero-gradient-purple` | Deepest color in the header radial gradient, establishing a rich foundation. |
| Highlight Pink | `#da9eff` | `--color-highlight-pink` | Used for specific heading highlights – adds a touch of modern vibrancy. |
| Subtle Violet | `#e1e2fe` | `--color-subtle-violet` | Background for less prominent buttons or interactive elements – a soft, supportive hue. |
| Paper White | `#ffffff` | `--color-paper-white` | Page backgrounds, card surfaces, critical text on dark backgrounds – ensures maximum contrast and visual space. |
| Border Ash | `#c6c6d2` | `--color-border-ash` | Default border color, subtle dividers – provides structure without harshness. |
| Graphite Text | `#000000` | `--color-graphite-text` | Dominant text color for body copy and headings on light backgrounds – ensures readability. |
| Body Black | `#060000` | `--color-body-black` | Alternate dark text color, body text — a slightly softer black for extended reading. |
| Slate Gray | `#5a5a72` | `--color-slate-gray` | Secondary border color, subtle accents – provides a cool, subdued detail. |
| Whisper Gray | `#8d8da5` | `--color-whisper-gray` | Subtle text, contextual information – communicates secondary priority. |
| Muted Stone | `#70708f` | `--color-muted-stone` | Icon fills, disabled text – blends into the background without disappearing. |
| Warm Cream | `#f7eee8` | `--color-warm-cream` | Accent background color for specific sections – introduces a subtle warmth. |
| Soft Off-White | `#f1f1f9` | `--color-soft-off-white` | Lightest background for elevated elements or hover states – minimal visual difference from Paper White. |
| Gradient Transition Purple | `#7c51fa` | `--color-gradient-transition-purple` | Mid-point in the main header gradient, adding depth and chromatic range. |
| Gradient End Magenta | `#ffb5ce` | `--color-gradient-end-magenta` | Lightest point in the header radial gradient, providing a soft edge. |

## Tokens — Typography

### Neue Hass Grotesk Text — Primary typeface for body text, UI elements, navigation. Its clean, humanist sans-serif forms maintain a professional yet approachable tone across all information densities. · `--font-neue-hass-grotesk-text`
- **Substitute:** Inter
- **Weights:** 300, 400, 500
- **Sizes:** 10px, 12px, 14px, 15px, 16px, 18px, 20px, 22px, 23px
- **Line height:** 1.00, 1.20, 1.27, 1.31, 1.36, 1.40, 1.50, 1.56, 1.78
- **Role:** Primary typeface for body text, UI elements, navigation. Its clean, humanist sans-serif forms maintain a professional yet approachable tone across all information densities.

### Neue Haas Grotesk Display Pro — Used for display headings and emphasized text, where the subtle letter-spacing contributes to a refined, almost architectural feel for large typography. · `--font-neue-haas-grotesk-display-pro`
- **Substitute:** Inter
- **Weights:** 300, 400, 500, 700
- **Sizes:** 12px, 14px, 15px, 16px, 18px, 20px, 22px, 135px
- **Line height:** 0.87, 1.21, 1.25, 1.31, 1.33, 1.36, 1.40, 1.44, 1.50, 1.58, 1.71
- **Letter spacing:** 0.0400em
- **Role:** Used for display headings and emphasized text, where the subtle letter-spacing contributes to a refined, almost architectural feel for large typography.

### Sanomat — Distinctive display font for main page headings, providing a unique personality and strong visual presence that differentiates prominent section titles. The varied weights allow for hierarchy within these larger forms. · `--font-sanomat`
- **Substitute:** Montserrat
- **Weights:** 400, 500, 600
- **Sizes:** 30px, 40px, 42px, 45px
- **Line height:** 1.00, 1.12, 1.20, 1.27, 1.35, 2.13
- **Role:** Distinctive display font for main page headings, providing a unique personality and strong visual presence that differentiates prominent section titles. The varied weights allow for hierarchy within these larger forms.

### Karla — Used for specific contextual or descriptive text, providing a slightly softer, more approachable feel than Grotesk without clashing. · `--font-karla`
- **Substitute:** Karla
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.50
- **Role:** Used for specific contextual or descriptive text, providing a slightly softer, more approachable feel than Grotesk without clashing.

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** spacious

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
| 44 | 44px | `--spacing-44` |
| 56 | 56px | `--spacing-56` |
| 60 | 60px | `--spacing-60` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 140 | 140px | `--spacing-140` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 14px |
| small | 4px |
| badges | 10px |
| buttons | 9999px |

### Layout

## Components

### Primary Action Button
**Role:** Main call-to-action

Filled with Action Violet (#6307f8), white text, fully rounded (9999px radius), with 10px vertical and 28px horizontal padding. Font is Neue Hass Grotesk Text, weight 500.

### Outline Ghost Button
**Role:** Secondary action or navigation

Transparent background, Navan Ink (#15002c) text and border, fully rounded (9999px radius), with 10px vertical and 54px horizontal padding. Font is Neue Hass Grotesk Text.

### Subtle Information Button
**Role:** Tertiary action or information display

Filled with Subtle Violet (#e1e2fe), Graphite Text (#000000) text, 12px radius, zero padding for inline use. Font is Neue Hass Grotesk Text.

### Inline Text Link
**Role:** Navigation or contextual links

Transparent background, Graphite Text (#000000) text, no border or radius, zero padding. Font is Neue Hass Grotesk Text.

### Basic Content Card
**Role:** Container for grouped content

Paper White (#ffffff) background, 14px border radius, no shadow. Padding varies by content, typically 16px-20px.

### New Feature Badge
**Role:** Highlighting new features

Transparent background, white text, 10px border radius, with 6px vertical and 16px horizontal padding. This specific badge uses a unique zero radius, suggesting inline application.

### Hero Section Gradient Background
**Role:** Main visual element for banner sections

A radial gradient from Hero Gradient Purple (#410566) to Gradient End Magenta (#ffb5ce), positioned to create depth.

## Do's and Don'ts

### Do
- Use Navan Ink (#15002c) for primary dark text and key background elements.
- Apply Action Violet (#6307f8) exclusively for primary interactive elements like main CTA buttons.
- Maintain a 9999px border-radius for all primary and secondary buttons to ensure a consistent pill-shape.
- Apply 14px border-radius to all card components and elevated containers.
- Utilize Neue Haas Grotesk Display Pro with 0.0400em letter-spacing for large, impactful headlines to maintain refinement.
- Ensure all body text uses Neue Hass Grotesk Text with a line-height appropriate to its size for optimal readability, such as 1.50 for 16px.
- Use Border Ash (#c6c6d2) for all subtle divders and non-interactive borders.

### Don't
- Avoid using highly saturated colors for large content blocks; reserve them for accents and interactive elements.
- Do not introduce additional font families; stick to Neue Hass Grotesk (Text/Display) and Sanomat.
- Never use hard-edged rectangles without a radius for interactive components; apply at least 10px radius to badges and 14px to most cards.
- Do not use shadows for elevation except where explicitly defined; rely primarily on background color differentiation.
- Avoid using custom letter-spacing on Neue Hass Grotesk Text body copy; it should remain 'normal'.
- Don't deviate from the established padding values for interactive buttons (10px vertical, 28px-54px horizontal).

## Imagery

The visual language combines contextual product mockups and staged, professional photography. Photography often features diverse individuals in business settings, focusing on collaboration or travel scenarios, with a semi-desaturated, naturalistic color treatment. Mockups are contained, often overlapping, and feature realistic app interfaces. Icons appear filled, monochromatic, and with a moderate stroke weight, serving an explanatory and decorative role. The overall density of imagery is balanced, supporting text without dominating.

## Layout

The page model is primarily max-width contained, centered on the screen, with sections flowing vertically. The hero section is full-bleed, showcasing a dark, atmospheric gradient background with a prominent centered headline and product mockups. Subsequent sections alternate between two-column layouts (text on left, image/card on right or vice-versa) and centered text blocks. Card grids appear for features or choices. Vertical spacing between sections is generous, contributing to a spacious feel. Navigation is a sticky top bar, with prominent, distinct CTA buttons.

## Agent Prompt Guide

### Quick Color Reference
- Text: #000000 (Graphite Text)
- Background: #ffffff (Paper White)
- CTA: #6307f8 (Action Violet)
- Border: #c6c6d2 (Border Ash)
- Accent: #15002c (Navan Ink)

### 3-5 Example Component Prompts
1. Create a primary call-to-action button: background Action Violet (#6307f8), text Paper White (#ffffff), border-radius 9999px, padding 10px vertical, 28px horizontal. Text is "Get Started" using Neue Hass Grotesk Text weight 500, size 16px.
2. Design a basic content card: background Paper White (#ffffff), border-radius 14px, no box-shadow, with a 20px padding. Content title uses Graphite Text (#000000), Sanomat weight 500, size 30px, line-height 1.20.
3. Implement a 'New' feature badge: transparent background, text Paper White (#ffffff), border-radius 10px, padding 6px vertical, 16px horizontal. Text is "New" using Neue Hass Grotesk Text weight 400, size 12px.
4. Construct an outline ghost button: transparent background, text Navan Ink (#15002c), border 1px solid Navan Ink (#15002c), border-radius 9999px, padding 10px vertical, 54px horizontal. Text is "Request a demo" using Neue Hass Grotesk Text weight 500, size 16px.

## Similar Brands

- **Rippling** — Shares the use of a deep purple/violet primary color with crisp white backgrounds and clean, precise sans-serif typography for a modern HR/fintech feel.
- **Ramp** — Exhibits similar high-contrast light theme with a strong accent color (often blue/purple) for CTAs and emphasizes clean, legible text with minimal, effective imagery.
- **Brex** — Utilizes a sophisticated dark base color combined with bright, inviting accents and uses subtle photographic elements to convey professionalism and approachability, similar to Navan's gradients and imagery style.
- **Linear** — Demonstrates a design philosophy of quiet authority through meticulous typography, subtle gray scales, and minimal yet impactful use of brand colors, though Navan is lighter overall.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-navan-ink: #15002c;
  --color-action-violet: #6307f8;
  --color-hero-gradient-purple: #410566;
  --gradient-hero-gradient-purple: radial-gradient(197.36% 161.87% at 4.08% 0%, rgba(65, 5, 102, 0.75) 6.19%, rgba(124, 81, 250, 0.75) 52.28%, rgba(255, 181, 206, 0.75) 91.18%);
  --color-highlight-pink: #da9eff;
  --color-subtle-violet: #e1e2fe;
  --color-paper-white: #ffffff;
  --color-border-ash: #c6c6d2;
  --color-graphite-text: #000000;
  --color-body-black: #060000;
  --color-slate-gray: #5a5a72;
  --color-whisper-gray: #8d8da5;
  --color-muted-stone: #70708f;
  --color-warm-cream: #f7eee8;
  --color-soft-off-white: #f1f1f9;
  --color-gradient-transition-purple: #7c51fa;
  --color-gradient-end-magenta: #ffb5ce;

  /* Typography — Font Families */
  --font-neue-hass-grotesk-text: 'Neue Hass Grotesk Text', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-neue-haas-grotesk-display-pro: 'Neue Haas Grotesk Display Pro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sanomat: 'Sanomat', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-karla: 'Karla', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-xs: 10px;
  --leading-xs: 1;
  --text-xs-2: 12px;
  --leading-xs-2: 1.5;
  --text-sm: 14px;
  --leading-sm: 1.36;
  --text-base: 15px;
  --leading-base: 1.33;
  --text-base-2: 16px;
  --leading-base-2: 1.5;
  --text-lg: 18px;
  --leading-lg: 1.78;
  --text-xl: 20px;
  --leading-xl: 1.4;
  --text-xl-2: 22px;
  --leading-xl-2: 1.36;
  --text-xl-3: 23px;
  --leading-xl-3: 1.2;
  --text-3xl: 30px;
  --leading-3xl: 2.13;
  --text-4xl: 40px;
  --leading-4xl: 1.35;
  --text-4xl-2: 42px;
  --leading-4xl-2: 1.12;

  /* Typography — Weights */
  --font-weight-light: 300;
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
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-44: 44px;
  --spacing-56: 56px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-140: 140px;

  /* Layout */

  /* Border Radius */
  --radius-md: 4px;
  --radius-xl: 14px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-cards: 14px;
  --radius-small: 4px;
  --radius-badges: 10px;
  --radius-buttons: 9999px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-navan-ink: #15002c;
  --color-action-violet: #6307f8;
  --color-hero-gradient-purple: #410566;
  --color-highlight-pink: #da9eff;
  --color-subtle-violet: #e1e2fe;
  --color-paper-white: #ffffff;
  --color-border-ash: #c6c6d2;
  --color-graphite-text: #000000;
  --color-body-black: #060000;
  --color-slate-gray: #5a5a72;
  --color-whisper-gray: #8d8da5;
  --color-muted-stone: #70708f;
  --color-warm-cream: #f7eee8;
  --color-soft-off-white: #f1f1f9;
  --color-gradient-transition-purple: #7c51fa;
  --color-gradient-end-magenta: #ffb5ce;

  /* Typography */
  --font-neue-hass-grotesk-text: 'Neue Hass Grotesk Text', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-neue-haas-grotesk-display-pro: 'Neue Haas Grotesk Display Pro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sanomat: 'Sanomat', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-karla: 'Karla', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-xs: 10px;
  --leading-xs: 1;
  --text-xs-2: 12px;
  --leading-xs-2: 1.5;
  --text-sm: 14px;
  --leading-sm: 1.36;
  --text-base: 15px;
  --leading-base: 1.33;
  --text-base-2: 16px;
  --leading-base-2: 1.5;
  --text-lg: 18px;
  --leading-lg: 1.78;
  --text-xl: 20px;
  --leading-xl: 1.4;
  --text-xl-2: 22px;
  --leading-xl-2: 1.36;
  --text-xl-3: 23px;
  --leading-xl-3: 1.2;
  --text-3xl: 30px;
  --leading-3xl: 2.13;
  --text-4xl: 40px;
  --leading-4xl: 1.35;
  --text-4xl-2: 42px;
  --leading-4xl-2: 1.12;

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
  --spacing-44: 44px;
  --spacing-56: 56px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-140: 140px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-xl: 14px;
  --radius-full: 9999px;
}
```

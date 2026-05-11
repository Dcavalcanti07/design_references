# Daylit — Style Reference
> Burgundy Ink on Ivory Scroll

**Theme:** light

Daylit's visual identity centers on a sophisticated, muted burgundy palette across surfaces and typography, juxtaposed with lively, almost neon yellow accents. The design applies a comfortable density, relying on generous white space and soft, rounded corners to create an approachable yet authoritative feel. Typography uses a refined sans-serif for headings and body text, with a monospaced font for functional elements, balancing a contemporary and precise aesthetic.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Burgundy Ink | `linear-gradient(49deg, rgb(77, 21, 32) 20%, rgb(179, 49, 74) 162%)` | `--color-burgundy-ink` | Primary text, CTA background, input borders, decorative accents – a deep, rich red-brown that defines the brand's sophisticated tone; Used for hero sections and prominent background elements, creating depth with a gradient from deep burgundy to a brighter, warmer red |
| Muted Berry | `#825b63` | `--color-muted-berry` | Subtle borders, secondary text elements, nav item backgrounds – a lighter, more desaturated shade of the primary burgundy for understated details |
| Deep Plum | `#360912` | `--color-deep-plum` | Footer background, elevated card surfaces – a dark, almost black burgundy for grounding elements and hierarchical layering |
| Soft Rose | `#906c7b` | `--color-soft-rose` | Badge backgrounds – a desaturated pink providing a soft, contrasting color for contextual labels |
| Cream Canvas | `#fbf9f6` | `--color-cream-canvas` | Page backgrounds, large content blocks, primary surface color – an off-white with a warm undertone that establishes the overall light theme |
| Pure White | `#ffffff` | `--color-pure-white` | Input backgrounds, elevated card surfaces, hover states, button text on dark backgrounds – providing crispness and contrast against warmer neutrals |
| Warm Mist | `#f2eee7` | `--color-warm-mist` | Secondary section backgrounds, subtle dividers, ghost button backgrounds – a slightly darker, warm off-white for subtle content separation |
| Pale Ash | `#d3cac3` | `--color-pale-ash` | Less prominent borders, secondary button borders – a light, cool gray for subtle UI separation |
| Soft Beige | `#e9e3d8` | `--color-soft-beige` | Card backgrounds, nuanced surface layering – a warm, light neutral for a soft elevation effect |
| Vivid Chartreuse | `#faffa7` | `--color-vivid-chartreuse` | Highlight accents, customer testimonial cards, decorative elements – a vibrant, almost neon yellow that provides a strong focal point and energy |
| Light Buttermilk | `#feffe1` | `--color-light-buttermilk` | Subtle accent backgrounds, secondary highlight – a very pale yellow for soft emphasis |
| Evergreen Mist | `#d1e8ae` | `--color-evergreen-mist` | Green decorative accent for icons, marks, and small graphic details. Use as a supporting accent, not as a status color |
| Deep Charcoal | `#101828` | `--color-deep-charcoal` | Darkest text, icon fills, strong contrast text – for maximum legibility on light backgrounds |

## Tokens — Typography

### Tt Commons Pro Variable — Primary typeface for all headings and body text, a clean sans-serif optimized for different sizes. Its variable nature allows for precise weight control, contributing to a modern and sophisticated presentation. · `--font-tt-commons-pro-variable`
- **Substitute:** Inter
- **Weights:** 400, 500, 600
- **Sizes:** 9px, 10px, 12px, 14px, 15px, 16px, 18px, 20px, 22px, 32px, 44px, 56px, 64px, 68px, 76px, 85px
- **Line height:** 0.93, 1.00, 1.15, 1.20, 1.25, 1.33, 1.40, 1.50, 1.60, 1.71, 1.75, 2.00, 2.39, 2.66
- **Letter spacing:** -1.4px at 56px, -1.0px at 44px, -0.66px at 32px, -0.3px at 18px
- **Role:** Primary typeface for all headings and body text, a clean sans-serif optimized for different sizes. Its variable nature allows for precise weight control, contributing to a modern and sophisticated presentation.

### Geist Mono — Used for technical details, code snippets, or small functional elements. The monospaced nature provides clarity for precise information, distinguishing it from narrative text. · `--font-geist-mono`
- **Substitute:** IBM Plex Mono
- **Weights:** 400, 500
- **Sizes:** 14px, 18px
- **Line height:** 1.33, 1.50, 1.75
- **Letter spacing:** normal
- **Role:** Used for technical details, code snippets, or small functional elements. The monospaced nature provides clarity for precise information, distinguishing it from narrative text.

### Open Sans — Used sparingly for specific body copy; acts as a supporting sans-serif for content blocks, potentially for longer-form readability. · `--font-open-sans`
- **Substitute:** Open Sans
- **Weights:** 400
- **Sizes:** 18px
- **Line height:** 1.20
- **Letter spacing:** -0.36px (at 18px)
- **Role:** Used sparingly for specific body copy; acts as a supporting sans-serif for content blocks, potentially for longer-form readability.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body | 16px | 1.75 | — | `--text-body` |
| body-lg | 18px | 1.75 | -0.3px | `--text-body-lg` |
| subheading | 20px | 1.5 | — | `--text-subheading` |
| heading-sm | 32px | 1.33 | -0.66px | `--text-heading-sm` |
| heading | 44px | 1.25 | -1px | `--text-heading` |
| heading-lg | 56px | 1.2 | -1.4px | `--text-heading-lg` |
| display | 85px | 0.93 | -3.4px | `--text-display` |

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
| 40 | 40px | `--spacing-40` |
| 60 | 60px | `--spacing-60` |
| 64 | 64px | `--spacing-64` |
| 76 | 76px | `--spacing-76` |
| 80 | 80px | `--spacing-80` |
| 88 | 88px | `--spacing-88` |
| 92 | 92px | `--spacing-92` |
| 96 | 96px | `--spacing-96` |
| 128 | 128px | `--spacing-128` |

### Border Radius

| Element | Value |
|---------|-------|
| pills | 1440px |
| badges | 13px |
| buttons | 24px |
| default | 6px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| xl | `rgba(77, 21, 32, 0.16) 19px 32px 73px 0px` | `--shadow-xl` |

### Layout

- **Section gap:** 64px
- **Card padding:** 24px
- **Element gap:** 8px

## Components

### Primary Filled Button
**Role:** Core action button

Solid background in Burgundy Ink (#4d1520), text in Pure White (#ffffff), with a 24px border radius and 12px vertical, 24px horizontal padding (inferred from common button padding patterns and radius). The rounded shape softens the call to action.

### Ghost Outline Button
**Role:** Secondary action button, navigation items

Transparent background, text in Burgundy Ink (#4d1520), with a 6px border, 1px border style (inferred), and a 24px border radius. This minimizes visual weight for less critical actions.

### Pill Button/Tag
**Role:** Tertiary action, small tags, categories

Background with 25% opacity of Burgundy Ink (rgba(77, 21, 32, 0.25)), text in Burgundy Ink (#4d1520), with a large 1440px border radius (effectively a pill shape) and 4px vertical, 8px horizontal padding. A subtle, highly rounded treatment for secondary labels.

### Solid Pale Card
**Role:** Content container for testimonials, features

Background in Soft Beige (#e9e3d8), 6px border radius, with 24px padding on all sides. This card provides a soft, warm surface for content without hard edges.

### Highlight Accent Card
**Role:** Emphasized content container for testimonials, notices

Background in Vivid Chartreuse (#faffa7), 6px border radius, with 24px padding on all sides. This bright card draws immediate attention to its content.

### Footer Dark Card
**Role:** Background for footer sections

Background in Deep Plum (#360912), 2px border radius. Acts as a strong, grounding container for footer links and information.

### Input Field
**Role:** User input text field

Background in Pure White (#ffffff), text in Deep Charcoal (#101828), with an implied 1px border in Burgundy Ink (#4d1520) on focus, and 6px border radius. Offers a clean, minimal input experience.

### Badge (Muted)
**Role:** Informational labels

Background in Soft Rose (#906c7b), text in Pure White (#ffffff), with a 13px border radius and 4px vertical, 8px horizontal padding. Provides a clear, yet subdued, label.

## Do's and Don'ts

### Do
- Always use Cream Canvas (#fbf9f6) for primary page backgrounds to maintain the site's default light aesthetic.
- Apply Burgundy Ink (#4d1520) for all main headings and primary call-to-action fills, ensuring brand consistency and visual impact.
- Use Tt Commons Pro Variable for all textual elements, calibrating letter-spacing precisely: -1.4px at 56px, -1.0px at 44px, -0.66px at 32px, and -0.3px at 18px to maintain legibility and visual rhythm.
- Implement 6px as the default border radius for cards, inputs, and navigation elements, creating a soft, friendly feel.
- For all primary buttons and prominent interactive elements, use Cream Canvas (#fbf9f6) for the page background, and Burgundy Ink (#4d1520) for the button fill.
- Ensure generous use of 24px padding within cards and major content blocks to create comfortable whitespace.
- Utilize Vivid Chartreuse (#faffa7) exclusively for accenting important information, such as testimonial cards or key highlights, making specific content pop.

### Don't
- Do not use dark backgrounds for entire content sections unless explicitly specified for a footer or dedicated interactive area.
- Avoid arbitrary uses of saturated colors; reserve Vivid Chartreuse (#faffa7) strictly for accentuation and not for general UI elements.
- Do not introduce new border radii beyond 6px, 13px, 24px, and 1440px to prevent visual inconsistency.
- Never use generic system fonts; always default to Tt Commons Pro Variable or Geist Mono as specified.
- Avoid heavy drop shadows; the single detected shadow rgba(77, 21, 32, 0.16) 19px 32px 73px 0px is for a specific card elevation and not for general use.
- Do not vary line heights without adhering to the specified granular steps to maintain typographic harmony.
- Refrain from using thin, hairline borders on primary interactive elements; most borders should be robust functional separators or stylistic outlines.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Cream Canvas | `#fbf9f6` | Primary page background, base layer. |
| 1 | Warm Mist | `#f2eee7` | Secondary section backgrounds, subtle content separation. |
| 2 | Soft Beige | `#e9e3d8` | Card backgrounds, elevated content containers. |
| 3 | Pure White | `#ffffff` | Input fields, highest elevation card surface for crispness. |
| 4 | Deep Plum | `#360912` | Dominant footer background, lowest and richest color layer. |

## Elevation

- **Card:** `19px 32px 73px 0px rgba(77, 21, 32, 0.16)`

## Imagery

The site uses a mix of flat, slightly dimensional illustrations and product-focused abstractions. Illustrations are clean, often featuring a subtle yellow highlight, and depict generic business scenarios or product functionality rather than specific people. Icons are solid, not outlined, and follow a monochrome or duotone aesthetic mirroring the brand's primary and accent colors. Imagery is used decoratively and explanatorily, emphasizing process rather than emotional connection.

## Layout

The page adheres to a max-width contained model, suggesting a central content column with a comfortable reading width, though the exact `pageMaxWidth` value is not explicitly defined and seems variable. The hero section is a split layout, featuring a large headline and call-to-action on the left against a Cream Canvas background and a product illustration on the right, often with a subtle yellow accent background. Sections alternate between Cream Canvas and Warm Mist backgrounds, creating visual rhythm. Content often arranges in two-column layouts, such as text on one side and associated visuals or cards on the other. Card grids are prominent for testimonials, showcasing content in distinct, soft-edged blocks. The navigation is a sticky top bar with clearly delineated links and accent buttons.

## Agent Prompt Guide

primary action: #4d1520 (filled action)
Create a Primary Action Button: #4d1520 background, #fbf9f6 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.

Example Component Prompts:
Create a testimonial card: background Vivid Chartreuse (#faffa7), 6px border radius, 24px padding on all sides. Headline in Burgundy Ink (#4d1520), Tt Commons Pro Variable weight 500, size 20px. Body text in Burgundy Ink (#4d1520), Tt Commons Pro Variable weight 400, size 16px.
Create a footer section with a Deep Plum (#360912) background, 2px border radius, and text links in Pure White (#ffffff), Tt Commons Pro Variable weight 400, size 14px.
Create an input field: background Pure White (#ffffff), 6px border radius, placeholder text in Pale Ash (#d3cac3), Tt Commons Pro Variable weight 400, size 16px. Border on focus in Burgundy Ink (#4d1520).

## Similar Brands

- **Stripe** — Both use sophisticated typography, a clean light background, and one dominant accent color (Burgundy vs. Blue) for calls to action.
- **Ramp** — Shares a similar executive-level SaaS aesthetic with a focus on clear UI, muted colors, and strong, legible sans-serif typography.
- **Brex** — Features a light, spacious layout with a dominant brand color for primary actions, subtle card-based layouts, and minimal illustrative elements.
- **Mercury** — Similar application of a professional, understated color palette with a single accent, prioritizing functional clarity and a minimalist design.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-burgundy-ink: #4d1520;
  --gradient-burgundy-ink: linear-gradient(49deg, rgb(77, 21, 32) 20%, rgb(179, 49, 74) 162%);
  --color-muted-berry: #825b63;
  --color-deep-plum: #360912;
  --color-soft-rose: #906c7b;
  --color-cream-canvas: #fbf9f6;
  --color-pure-white: #ffffff;
  --color-warm-mist: #f2eee7;
  --color-pale-ash: #d3cac3;
  --color-soft-beige: #e9e3d8;
  --color-vivid-chartreuse: #faffa7;
  --color-light-buttermilk: #feffe1;
  --color-evergreen-mist: #d1e8ae;
  --color-deep-charcoal: #101828;

  /* Typography — Font Families */
  --font-tt-commons-pro-variable: 'Tt Commons Pro Variable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geist-mono: 'Geist Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-open-sans: 'Open Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 16px;
  --leading-body: 1.75;
  --text-body-lg: 18px;
  --leading-body-lg: 1.75;
  --tracking-body-lg: -0.3px;
  --text-subheading: 20px;
  --leading-subheading: 1.5;
  --text-heading-sm: 32px;
  --leading-heading-sm: 1.33;
  --tracking-heading-sm: -0.66px;
  --text-heading: 44px;
  --leading-heading: 1.25;
  --tracking-heading: -1px;
  --text-heading-lg: 56px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -1.4px;
  --text-display: 85px;
  --leading-display: 0.93;
  --tracking-display: -3.4px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-76: 76px;
  --spacing-80: 80px;
  --spacing-88: 88px;
  --spacing-92: 92px;
  --spacing-96: 96px;
  --spacing-128: 128px;

  /* Layout */
  --section-gap: 64px;
  --card-padding: 24px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-sm: 1.85px;
  --radius-md: 6px;
  --radius-lg: 9.276px;
  --radius-xl: 13px;
  --radius-3xl: 24px;
  --radius-full: 1440px;
  --radius-full-2: 9999px;

  /* Named Radii */
  --radius-pills: 1440px;
  --radius-badges: 13px;
  --radius-buttons: 24px;
  --radius-default: 6px;

  /* Shadows */
  --shadow-xl: rgba(77, 21, 32, 0.16) 19px 32px 73px 0px;

  /* Surfaces */
  --surface-cream-canvas: #fbf9f6;
  --surface-warm-mist: #f2eee7;
  --surface-soft-beige: #e9e3d8;
  --surface-pure-white: #ffffff;
  --surface-deep-plum: #360912;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-burgundy-ink: #4d1520;
  --color-muted-berry: #825b63;
  --color-deep-plum: #360912;
  --color-soft-rose: #906c7b;
  --color-cream-canvas: #fbf9f6;
  --color-pure-white: #ffffff;
  --color-warm-mist: #f2eee7;
  --color-pale-ash: #d3cac3;
  --color-soft-beige: #e9e3d8;
  --color-vivid-chartreuse: #faffa7;
  --color-light-buttermilk: #feffe1;
  --color-evergreen-mist: #d1e8ae;
  --color-deep-charcoal: #101828;

  /* Typography */
  --font-tt-commons-pro-variable: 'Tt Commons Pro Variable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geist-mono: 'Geist Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-open-sans: 'Open Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 16px;
  --leading-body: 1.75;
  --text-body-lg: 18px;
  --leading-body-lg: 1.75;
  --tracking-body-lg: -0.3px;
  --text-subheading: 20px;
  --leading-subheading: 1.5;
  --text-heading-sm: 32px;
  --leading-heading-sm: 1.33;
  --tracking-heading-sm: -0.66px;
  --text-heading: 44px;
  --leading-heading: 1.25;
  --tracking-heading: -1px;
  --text-heading-lg: 56px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -1.4px;
  --text-display: 85px;
  --leading-display: 0.93;
  --tracking-display: -3.4px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-76: 76px;
  --spacing-80: 80px;
  --spacing-88: 88px;
  --spacing-92: 92px;
  --spacing-96: 96px;
  --spacing-128: 128px;

  /* Border Radius */
  --radius-sm: 1.85px;
  --radius-md: 6px;
  --radius-lg: 9.276px;
  --radius-xl: 13px;
  --radius-3xl: 24px;
  --radius-full: 1440px;
  --radius-full-2: 9999px;

  /* Shadows */
  --shadow-xl: rgba(77, 21, 32, 0.16) 19px 32px 73px 0px;
}
```

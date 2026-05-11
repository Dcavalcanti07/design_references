# NEVERHACK — Style Reference
> High-contrast digital fortress

**Theme:** light

NEVERHACK presents a stark, high-contrast digital fortress aesthetic, blending a near-monochromatic palette with strategic, vibrant accents that highlight critical information. Typography is compact and precise, maintaining clarity across data-heavy interfaces. Micro-shadows and subtle inner borders define component boundaries without adding visual weight. The overall impression is one of controlled power, efficiency, and secure functionality, prioritizing information delivery with minimal distraction.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#0A0F1F` | `--color-midnight-ink` | Primary text, headings, navigational elements, brand accents. Provides a deep, authoritative base |
| Ghost White | `#FFFFFF` | `--color-ghost-white` | Page backgrounds, card surfaces, primary button backgrounds against dark elements. Creates expansive, clean canvases |
| Fog Gray | `#E5E7EB` | `--color-fog-gray` | Hairline borders, subtle dividers, inactive states. Defines structure without visual interruption |
| Lavender Bloom | `#6B2BEA` | `--color-lavender-bloom` | Violet state accent for badges, validation surfaces, and short status labels. Do not promote it to the primary CTA color |
| Alert Red | `radial-gradient(circle at 70% 35%, rgba(220, 38, 38, 0.22) 0%, rgba(0, 0, 0, 0) 60%)` | `--color-alert-red` | Critical state indicators, error messages, warning badges, primary action background. Demands immediate attention; Subtle radial gradient for emphasis around critical areas, emanating from red |
| Info Blue | `#2563EB` | `--color-info-blue` | Informational badges and text. Provides clarity for helpful hints |
| Cloud Gray | `#F6F7FC` | `--color-cloud-gray` | Subtle background for distinct content blocks and elevated card surfaces, creating a multi-layered neutral depth |
| Light Shadow | `#C9C7D7` | `--color-light-shadow` | Inner card borders, subtle inset shadows. Adds form without strong contrast |
| Muted Red Wash | `#F4BABA` | `--color-muted-red-wash` | Subtle shadow tint for critical elements, lending a soft glow to warnings |
| Sky Tint | `#28D3FE` | `--color-sky-tint` | Decorative background accents, UI illustrations. Provides a bright, energetic highlight |
| Soft Violet | `#AFA9FD` | `--color-soft-violet` | Small decorative background elements, balancing the more vivid purple |

## Tokens — Typography

### Roobert — Primary typeface for all content, from headings to body text and UI elements. Its slightly condensed and robust geometric forms convey precision and technical authority, supporting the cybersecurity theme. Tighter letter spacing on larger sizes ensures visual cohesion. · `--font-roobert`
- **Substitute:** system-ui
- **Weights:** 400, 500
- **Sizes:** 11px, 12px, 13px, 14px, 15px, 16px, 17px, 18px, 22px, 24px, 32px, 34px, 40px, 52px, 72px
- **Line height:** 1.00, 1.05, 1.08, 1.10, 1.12, 1.20, 1.30, 1.45, 1.50, 1.55, 1.60, 1.63
- **Letter spacing:** -0.0300em at 72px, -0.0250em at 52px, -0.0200em at 40px, -0.0150em at 34px, -0.0100em at 32px, -0.0050em at 24px, 0.0050em at 18px
- **Role:** Primary typeface for all content, from headings to body text and UI elements. Its slightly condensed and robust geometric forms convey precision and technical authority, supporting the cybersecurity theme. Tighter letter spacing on larger sizes ensures visual cohesion.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 11px | 1.63 | — | `--text-caption` |
| body | 16px | 1.5 | 0.08px | `--text-body` |
| subheading | 18px | 1.45 | 0.005px | `--text-subheading` |
| heading-sm | 22px | 1.3 | — | `--text-heading-sm` |
| heading | 32px | 1.2 | -0.01px | `--text-heading` |
| heading-lg | 40px | 1.12 | -0.02px | `--text-heading-lg` |
| display | 72px | 1 | -0.03px | `--text-display` |

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
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 56 | 56px | `--spacing-56` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 96 | 96px | `--spacing-96` |
| 128 | 128px | `--spacing-128` |
| 144 | 144px | `--spacing-144` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 14px |
| forms | 6px |
| badges | 9999px |
| buttons | 9999px |
| navigation | 18px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(0, 0, 0, 0.4) 0px 0px 1px 0px, rgba(0, 0, 0, 0.08) 0...` | `--shadow-subtle` |
| subtle-2 | `rgb(235, 232, 228) 0px 0px 0px 0.5px inset, rgba(0, 0, 0,...` | `--shadow-subtle-2` |
| subtle-3 | `rgba(40, 30, 93, 0.06) 0px 1px 2px 0px` | `--shadow-subtle-3` |
| xl | `rgba(40, 30, 93, 0.25) 0px 30px 45px -30px, rgba(0, 0, 0,...` | `--shadow-xl` |
| md | `rgba(40, 30, 93, 0.04) 0px 4px 12px -4px, rgba(0, 0, 0, 0...` | `--shadow-md` |
| subtle-4 | `rgba(0, 0, 0, 0.06) 0px 0px 0px 1px, rgba(0, 0, 0, 0.04) ...` | `--shadow-subtle-4` |
| subtle-5 | `rgb(235, 232, 228) 0px 0px 0px 0.5px inset, rgba(0, 0, 0,...` | `--shadow-subtle-5` |
| xl-2 | `rgba(40, 30, 93, 0.18) 0px 50px 100px -20px, rgba(40, 30,...` | `--shadow-xl-2` |
| lg | `rgba(220, 38, 38, 0.32) 0px 12px 24px -10px, rgba(0, 0, 0...` | `--shadow-lg` |

### Layout

- **Section gap:** 32px
- **Card padding:** 28px
- **Element gap:** 12px

## Components

### Primary Filled Button
**Role:** Call to action.

Filled with Alert Red (#DC2626) background and Ghost White (#FFFFFF) text. Rounded to 9999px. Padding of 12px vertical, 22px horizontal. Subtle red shadow tint on interaction.

### Ghost Button (Primary)
**Role:** Secondary call to action.

Ghost White (#FFFFFF) background with Midnight Ink (#0A0F1F) text and Ghost White (#FFFFFF) 1px border. Rounded to 9999px. Padding of 12px vertical, 22px horizontal. Features a subtle black shadow: rgba(0, 0, 0, 0.4) 0px 0px 1px 0px, rgba(0, 0, 0, 0.08) 0px 4px 8px 0px.

### Ghost Button (Secondary)
**Role:** Tertiary action or navigational link.

Transparent background with Midnight Ink (#0A0F1F) text. Rounded to 9999px. Minimal padding around text, e.g., 0px vertical, 12px horizontal.

### Interactive Card
**Role:** Content container with subtle elevation.

Ghost White (#FFFFFF) background with 14px border-radius. Features a subtle inset border of Fog Gray (#E5E7EB) and a compound shadow: rgba(0,0,0,0.04) 0px 1px 1px 0px, rgba(0,0,0,0.04) 0px 4px 4px 0px.

### Section Card
**Role:** Elevated background for distinct content sections.

Cloud Gray (#F6F7FC) background with 16px border-radius. No visual shadow, relies on background color differentiation.

### Subtle Information Card
**Role:** Small information container, often nested.

Ghost White (#FFFFFF) background with a tight 6px border-radius. Distinctive deep shadow for separation: rgba(40, 30, 93, 0.25) 0px 30px 45px -30px, rgba(0, 0, 0, 0.1) 0px 18px 36px -18px.

### AI Badge
**Role:** Categorization tag.

Translucent Lavender Bloom (#6B2BEA) background with vivid Lavender Bloom (#6B2BEA) text. Rounded to 9999px. 0px vertical, 10px horizontal padding.

### Critical Badge
**Role:** Urgency indicator.

Translucent Alert Red (#DC2626) background with vivid Alert Red (#DC2626) text. Rounded to 9999px. 0px vertical, 10px horizontal padding.

### Info Badge
**Role:** Informative tag.

Translucent Info Blue (#2563EB) background with vivid Info Blue (#2563EB) text. Rounded to 9999px. 0px vertical, 10px horizontal padding.

### Text Input
**Role:** Standard form field.

Ghost White (#FFFFFF) background with a Fog Gray (#E5E7EB) 1px border. 6px border-radius. Placeholder text in a slightly muted Midnight Ink.

## Do's and Don'ts

### Do
- Use Midnight Ink (#0A0F1F) for all primary text and headings, maintaining a high contrast against lighter backgrounds.
- Apply Fog Gray (#E5E7EB) for all hairline borders and subtle dividers, ensuring elements are separated without visual heaviness.
- Utilize Lavender Bloom (#6B2BEA) exclusively for interactive elements, key iconography, and small accent details, making it the primary activation color.
- Employ rounded corners with a 9999px radius for all buttons and badges to create a distinct, approachable contour.
- Maintain a clear visual hierarchy by using the precise Roobert type scale and corresponding letter spacing: tighter tracking for larger display text (-0.0300em at 72px) and normal for body text (0.0050em at 18px).
- Define card surfaces using Ghost White (#FFFFFF) with a 14px border-radius and a subtle inner border from Light Shadow (#C9C7D7) to create depth without strong shadows.
- Prioritize the comfortable density spacing with an `elementGap` of 12px for consistent internal component spacing and `cardPadding` of 28px for content within containers.

### Don't
- Do not introduce new saturated colors beyond the established Lavender Bloom, Alert Red, and Info Blue without explicit design approval.
- Avoid heavy drop shadows or strong outer glows; elevation is achieved through subtle inner borders and specific, controlled micro-shadows.
- Never use generic system fonts; always default to Roobert or its defined substitute to maintain brand consistency.
- Do not deviate from the defined border-radius values; 9999px for buttons and badges, 14px for primary cards, and 6px for subtle input fields are critical for brand identity.
- Refrain from altering the precise letter-spacing values, especially for headlines; the distinct tracking is integral to the brand's typographic tone.
- Never use pure black (#000000) for text; Midnight Ink (#0A0F1F) is the darkest allowed text color to maintain a subtle professionalism.
- Do not add heavy background gradients to main content areas; reserve distinct gradients for specific decorative or brand elements as defined (e.g., Critical Gradient).

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Canvas | `#FFFFFF` | Primary page background. |
| 2 | Card Base | `#F6F7FC` | Elevated background for distinct content sections. |
| 3 | Card Elevated | `#FFFFFF` | Main content cards, modals atop base backgrounds. |

## Elevation

- **Interactive Card:** `rgb(235, 232, 228) 0px 0px 0px 0.5px inset, rgba(0, 0, 0, 0.04) 0px 1px 1px 0px, rgba(0, 0, 0, 0.04) 0px 4px 4px 0px`
- **Subtle Information Card:** `rgba(40, 30, 93, 0.25) 0px 30px 45px -30px, rgba(0, 0, 0, 0.1) 0px 18px 36px -18px`
- **Primary Ghost Button:** `rgba(0, 0, 0, 0.4) 0px 0px 1px 0px, rgba(0, 0, 0, 0.08) 0px 4px 8px 0px`

## Imagery

This system primarily uses iconography and abstract graphics to convey concepts. Icons are generally outlined, in Midnight Ink or Lavender Bloom, maintaining a functional and precise feel. Small, abstract 3D or gradient-filled elements appear as decorative branding accents, often using soft violet or sky blue tints against monochromatic backgrounds. Imagery is used minimally, typically as small product illustrations or feature highlights, favoring contained, abstract compositions over full-bleed photography. The visual density is low, dominated by text and structured UI elements.

## Layout

The page primarily uses a contained layout, with content centered within a maximum width (implied around 1200-1400px, but no explicit max-width given in data) against a Ghost White canvas. The hero section is characterized by a prominent left-aligned headline with supporting text and distinct split action buttons. Sections establish rhythm through consistent vertical spacing (sectionGap of 32px) and sometimes use a Cloud Gray (#F6F7FC) background to subtly differentiate blocks. Content often arranges in 2-column or 3-column grids, balancing text on one side with an abstract visual or nested information cards on the other. Navigation consists of a sticky top bar with a 'Cyber AI' call to action button, emphasizing a specific product.

## Agent Prompt Guide

### Quick Color Reference
- text: #0A0F1F
- background: #FFFFFF
- border: #E5E7EB
- accent: #6B2BEA
- primary action: #dc2626 (filled action)

### Example Component Prompts
1. Create a hero section with a primary statement 'AI-native cyber defense.' using Roobert, 72px, weight 500, Midnight Ink (#0A0F1F), letter-spacing -0.0300em. Below, add a Ghost Button (Primary) labeled 'Ask PROMETHEUS' and a Ghost Button (Secondary) labeled 'Explore capabilities'.
2. Design a feature card: `Interactive Card` component. Inside, a heading 'Cyber AI' using Roobert, 22px, weight 500, Midnight Ink (#0A0F1F). Below, a line of body text (Roobert, 16px, weight 400, Midnight Ink) and an 'AI Badge'.
3. Create a Primary Action Button: #dc2626 background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
4. Generate a 'Critical' callout badge: use the `Critical Badge` component with the text 'CRITICAL', placed above a headline (Roobert, 18px, weight 500, Alert Red #DC2626). The badge should have 0px vertical and 10px horizontal padding, with 9999px radius and a translucent Alert Red background.

## Similar Brands

- **Rippling** — High-contrast text on bright backgrounds, a structured layout, and judicious use of a single vibrant accent color for interaction and branding.
- **Linear** — Clean, functional typography, near-monochromatic UI with a strategic bright accent, and minimal shadows emphasizing content over decoration.
- **Vercel** — Focus on developer tooling aesthetic with dark, precise text on light backgrounds, rounded edge components, and strong typographic hierarchy.
- **Plaid** — Modern, data-focused feel with crisp typography, limited color palette centering on blues/purples, and subtle card-based layouts.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #0A0F1F;
  --color-ghost-white: #FFFFFF;
  --color-fog-gray: #E5E7EB;
  --color-lavender-bloom: #6B2BEA;
  --color-alert-red: #DC2626;
  --gradient-alert-red: radial-gradient(circle at 70% 35%, rgba(220, 38, 38, 0.22) 0%, rgba(0, 0, 0, 0) 60%);
  --color-info-blue: #2563EB;
  --color-cloud-gray: #F6F7FC;
  --color-light-shadow: #C9C7D7;
  --color-muted-red-wash: #F4BABA;
  --color-sky-tint: #28D3FE;
  --color-soft-violet: #AFA9FD;

  /* Typography — Font Families */
  --font-roobert: 'Roobert', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.63;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: 0.08px;
  --text-subheading: 18px;
  --leading-subheading: 1.45;
  --tracking-subheading: 0.005px;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1.3;
  --text-heading: 32px;
  --leading-heading: 1.2;
  --tracking-heading: -0.01px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.12;
  --tracking-heading-lg: -0.02px;
  --text-display: 72px;
  --leading-display: 1;
  --tracking-display: -0.03px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;

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
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-128: 128px;
  --spacing-144: 144px;

  /* Layout */
  --section-gap: 32px;
  --card-padding: 28px;
  --element-gap: 12px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-lg: 10px;
  --radius-xl: 14px;
  --radius-2xl: 18px;
  --radius-2xl-2: 22px;
  --radius-full: 999px;
  --radius-full-2: 9999px;

  /* Named Radii */
  --radius-cards: 14px;
  --radius-forms: 6px;
  --radius-badges: 9999px;
  --radius-buttons: 9999px;
  --radius-navigation: 18px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.4) 0px 0px 1px 0px, rgba(0, 0, 0, 0.08) 0px 4px 8px 0px;
  --shadow-subtle-2: rgb(235, 232, 228) 0px 0px 0px 0.5px inset, rgba(0, 0, 0, 0.04) 0px 1px 1px 0px, rgba(0, 0, 0, 0.04) 0px 4px 4px 0px;
  --shadow-subtle-3: rgba(40, 30, 93, 0.06) 0px 1px 2px 0px;
  --shadow-xl: rgba(40, 30, 93, 0.25) 0px 30px 45px -30px, rgba(0, 0, 0, 0.1) 0px 18px 36px -18px;
  --shadow-md: rgba(40, 30, 93, 0.04) 0px 4px 12px -4px, rgba(0, 0, 0, 0.03) 0px 1px 2px 0px;
  --shadow-subtle-4: rgba(0, 0, 0, 0.06) 0px 0px 0px 1px, rgba(0, 0, 0, 0.04) 0px 1px 2px 0px, rgba(0, 0, 0, 0.04) 0px 2px 4px 0px;
  --shadow-subtle-5: rgb(235, 232, 228) 0px 0px 0px 0.5px inset, rgba(0, 0, 0, 0.4) 0px 0px 1px 0px, rgba(0, 0, 0, 0.04) 0px 1px 1px 0px, rgba(0, 0, 0, 0.04) 0px 4px 4px 0px;
  --shadow-xl-2: rgba(40, 30, 93, 0.18) 0px 50px 100px -20px, rgba(40, 30, 93, 0.12) 0px 30px 60px -30px, rgba(10, 15, 31, 0.08) 0px 8px 24px -8px;
  --shadow-lg: rgba(220, 38, 38, 0.32) 0px 12px 24px -10px, rgba(0, 0, 0, 0.06) 0px 2px 4px 0px;

  /* Surfaces */
  --surface-canvas: #FFFFFF;
  --surface-card-base: #F6F7FC;
  --surface-card-elevated: #FFFFFF;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #0A0F1F;
  --color-ghost-white: #FFFFFF;
  --color-fog-gray: #E5E7EB;
  --color-lavender-bloom: #6B2BEA;
  --color-alert-red: #DC2626;
  --color-info-blue: #2563EB;
  --color-cloud-gray: #F6F7FC;
  --color-light-shadow: #C9C7D7;
  --color-muted-red-wash: #F4BABA;
  --color-sky-tint: #28D3FE;
  --color-soft-violet: #AFA9FD;

  /* Typography */
  --font-roobert: 'Roobert', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.63;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: 0.08px;
  --text-subheading: 18px;
  --leading-subheading: 1.45;
  --tracking-subheading: 0.005px;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1.3;
  --text-heading: 32px;
  --leading-heading: 1.2;
  --tracking-heading: -0.01px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.12;
  --tracking-heading-lg: -0.02px;
  --text-display: 72px;
  --leading-display: 1;
  --tracking-display: -0.03px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-128: 128px;
  --spacing-144: 144px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-lg: 10px;
  --radius-xl: 14px;
  --radius-2xl: 18px;
  --radius-2xl-2: 22px;
  --radius-full: 999px;
  --radius-full-2: 9999px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.4) 0px 0px 1px 0px, rgba(0, 0, 0, 0.08) 0px 4px 8px 0px;
  --shadow-subtle-2: rgb(235, 232, 228) 0px 0px 0px 0.5px inset, rgba(0, 0, 0, 0.04) 0px 1px 1px 0px, rgba(0, 0, 0, 0.04) 0px 4px 4px 0px;
  --shadow-subtle-3: rgba(40, 30, 93, 0.06) 0px 1px 2px 0px;
  --shadow-xl: rgba(40, 30, 93, 0.25) 0px 30px 45px -30px, rgba(0, 0, 0, 0.1) 0px 18px 36px -18px;
  --shadow-md: rgba(40, 30, 93, 0.04) 0px 4px 12px -4px, rgba(0, 0, 0, 0.03) 0px 1px 2px 0px;
  --shadow-subtle-4: rgba(0, 0, 0, 0.06) 0px 0px 0px 1px, rgba(0, 0, 0, 0.04) 0px 1px 2px 0px, rgba(0, 0, 0, 0.04) 0px 2px 4px 0px;
  --shadow-subtle-5: rgb(235, 232, 228) 0px 0px 0px 0.5px inset, rgba(0, 0, 0, 0.4) 0px 0px 1px 0px, rgba(0, 0, 0, 0.04) 0px 1px 1px 0px, rgba(0, 0, 0, 0.04) 0px 4px 4px 0px;
  --shadow-xl-2: rgba(40, 30, 93, 0.18) 0px 50px 100px -20px, rgba(40, 30, 93, 0.12) 0px 30px 60px -30px, rgba(10, 15, 31, 0.08) 0px 8px 24px -8px;
  --shadow-lg: rgba(220, 38, 38, 0.32) 0px 12px 24px -10px, rgba(0, 0, 0, 0.06) 0px 2px 4px 0px;
}
```

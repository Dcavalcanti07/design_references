# Uber — Style Reference
> Crisp monochrome canvas

**Theme:** light

Uber's design system feels like a precise, functional transport UI on an expansive, crisp canvas. It prioritizes direct interaction and clear information with high contrast black-on-white text. Distinctive elements include capsule-shaped interactive components and subtle, almost invisible, input fields, focusing user attention on action over aesthetics. The only chromatic color, a muted blue-green, appears sparingly, adding a touch of sophisticated calm to an otherwise stark, monochromatic palette.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#000000` | `--color-midnight-ink` | Primary text, button backgrounds, primary interactives, footer background—defines high contrast and directness against light surfaces. |
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card surfaces, ghost button text—provides a spacious, clean foundation. |
| Whisper Gray | `#f6f6f6` | `--color-whisper-gray` | Subtle background surfaces, outlines for ghost buttons, creating very soft visual breaks. |
| Charcoal Text | `#333333` | `--color-charcoal-text` | Secondary text, offering slightly softer contrast than Midnight Ink while maintaining readability. |
| Input Border Gray | `#767676` | `--color-input-border-gray` | Discreet borders for input fields and less prominent UI elements. |
| Subtle Silver | `#afafaf` | `--color-subtle-silver` | Placeholder text, tertiary information, and non-interactive body copy, reducing visual hierarchy. |
| Slate Shadow | `#d6d6d6` | `--color-slate-shadow` | Subtle shadow color for buttons, suggesting minimal elevation. |
| Lagoon Mist | `#9dcdd6` | `--color-lagoon-mist` | Decorative background element, offering a single, muted chromatic accent to an otherwise achromatic scheme. |

## Tokens — Typography

### UberMoveText — Used for most body text, navigation labels, and button text, providing a custom, legible aesthetic for core content. The range of line heights shows fine-tuned typographic control. · `--font-ubermovetext`
- **Substitute:** system-ui
- **Weights:** 400, 500
- **Sizes:** 12px, 14px, 16px, 18px, 24px
- **Line height:** 1.00, 1.14, 1.20, 1.25, 1.33, 1.43, 1.50, 1.67, 2.00
- **Role:** Used for most body text, navigation labels, and button text, providing a custom, legible aesthetic for core content. The range of line heights shows fine-tuned typographic control.

### UberMove — Dedicated to headlines and prominent links, its specific weights and sizes drive information hierarchy, emphasizing key messages with a distinctive, branded typeface. · `--font-ubermove`
- **Substitute:** system-ui
- **Weights:** 400, 700
- **Sizes:** 20px, 24px, 36px, 52px
- **Line height:** 1.22, 1.23, 1.33, 1.40
- **Role:** Dedicated to headlines and prominent links, its specific weights and sizes drive information hierarchy, emphasizing key messages with a distinctive, branded typeface.

### sans-serif — Fallback or general system text at a single size and weight, ensuring broad compatibility while deferring to branded fonts for primary content. · `--font-sans-serif`
- **Substitute:** system-ui
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.20
- **Role:** Fallback or general system text at a single size and weight, ensuring broad compatibility while deferring to branded fonts for primary content.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.5 | — | `--text-caption` |
| body-sm | 14px | 1.43 | — | `--text-body-sm` |
| body | 16px | 1.2 | — | `--text-body` |
| subheading | 18px | 1.25 | — | `--text-subheading` |
| heading-sm | 20px | 1.22 | — | `--text-heading-sm` |
| heading | 24px | 1.33 | — | `--text-heading` |
| display | 36px | 1.23 | — | `--text-display` |
| display-lg | 52px | 1.4 | — | `--text-display-lg` |

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
| 36 | 36px | `--spacing-36` |
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |

### Border Radius

| Element | Value |
|---------|-------|
| misc | 12px |
| cards | 8px |
| buttons | 8px |
| capsule | 999px |

### Layout

- **Section gap:** 48-80px
- **Card padding:** 12-24px
- **Element gap:** 4-24px

## Components

### Primary Action Button
**Role:** Main call to action

Solid Midnight Ink background, Canvas White text, 8px border-radius, 14px vertical and 25px horizontal padding. Example: 'See prices'.

### Capsule Button
**Role:** Compact action button

Midnight Ink background, Canvas White text, 999px border-radius (full capsule), 10px vertical and 12px horizontal padding. Found in navigation and context-specific actions like 'Sign up'.

### Ghost Capsule Button
**Role:** Secondary interaction

Canvas White background, Midnight Ink text, 999px border-radius, 10px vertical and 12px horizontal padding. Used for alternative or less prominent actions like 'EN'.

### Input Field - Text
**Role:** User input for text

Transparent background, Midnight Ink text, 0px border-radius, 0px padding, subtle Input Border Gray for the bottom border only. Promotes a minimal input experience.

### Navigation Link - Primary
**Role:** Top-level navigation items

UberMoveText, 16px, weight 400, Midnight Ink text initially. Becomes Canvas White for active capsule buttons, on Midnight Ink backgrounds.

### Feature Card
**Role:** Showcasing services

Canvas White background, 8px border-radius, 12px padding. Contains an image, headline (UberMove, 20px, weight 400, Midnight Ink), and body text (UberMoveText, 14px, weight 400, Charcoal Text).

## Do's and Don'ts

### Do
- Prioritize Midnight Ink (#000000) for primary CTAs and critical text, ensuring high contrast against Canvas White (#ffffff) or Whisper Gray (#f6f6f6) backgrounds.
- Apply 999px border-radius to all small, compact interactive elements for a distinct capsule aesthetic, like navigation buttons.
- Use 8px border-radius for larger action buttons and cards to create a softer, yet still defined, rectangular shape.
- Employ UberMove (custom font) for all headlines and major calls to action, utilizing its 400 and 700 weights to establish hierarchy.
- Maintain a clear visual hierarchy with Midnight Ink for headings, Charcoal Text (#333333) for body text, and Subtle Silver (#afafaf) for secondary descriptive text.
- Use Lagoon Mist (#9dcdd6) as the sole chromatic accent, reserving it for decorative elements or subtle background effects to maintain monochromatic dominance.
- Place input fields on Canvas White backgrounds with minimal styling, relying on a subtle Input Border Gray (#767676) bottom border to indicate interactive areas.

### Don't
- Do not introduce additional saturated colors; maintain the monochromatic base with Lagoon Mist (#9dcdd6) as the only accent.
- Avoid excessive use of box shadows; stick to the subtle Slate Shadow (#d6d6d6) only when slight elevation is necessary for buttons.
- Do not use generic system fonts for headlines or core UI elements; leverage the custom UberMove and UberMoveText families to preserve brand identity.
- Avoid complex gradients or patterns; surfaces should remain flat and clean, with a clear distinction between background colors.
- Do not add strong borders to primary input fields; preserve the minimal, almost borderless aesthetic with only a bottom bar.
- Refrain from drastically altering button padding; stick to the established 14px vertical 25px horizontal for standard buttons and 10px vertical 12px horizontal for capsule buttons.
- Do not use letter spacing adjustments; all text should maintain normal letter spacing for a clean and uncluttered appearance.

## Imagery

The site uses a mix of bespoke, blocky illustrations and stylized product icons. Illustrations are semi-flat, with distinct geometric shapes and limited color palettes, often featuring abstract figures or objects relevant to the service (e.g., luggage, vehicles, food). They are contained within defined sections rather than full-bleed, typically serving as explanatory or decorative visuals. Product icons are simplified, monochrome (Midnight Ink), and used to clarify features or services. The overall treatment is descriptive and clean, avoiding photography to maintain a uniform, branded visual language.

## Layout

The layout is primarily centered and contained within an implied max-width, with generous vertical spacing between sections. The hero section features a prominent headline and interactive form on the left, balanced by a large, contained illustration on the right. Subsequent sections often alternate between text-left/visual-right compositions and centered content stacks. Small feature blocks are arranged in a 3-column grid. The footer is full-bleed black, contrasting with the predominantly white main content area. Navigation is a sticky top bar with minimal elements, including capsule-style buttons.

## Agent Prompt Guide

### Quick Color Reference
- Text: Midnight Ink (#000000)
- Background: Canvas White (#ffffff)
- CTA Background: Midnight Ink (#000000)
- Input Border: Input Border Gray (#767676)
- Accent: Lagoon Mist (#9dcdd6)

### Example Component Prompts
1. Create a Primary Action Button: 'See prices'. Background Midnight Ink (#000000), text Canvas White (#ffffff), border-radius 8px, padding 14px 25px. Text style: UberMoveText, weight 500, size 16px.
2. Create a Capsule Button: 'Sign up'. Background Midnight Ink (#000000), text Canvas White (#ffffff), border-radius 999px, padding 10px 12px. Text style: UberMoveText, weight 400, size 14px.
3. Create an Input Field: 'Pickup location'. Background transparent, text Midnight Ink (#000000), bottom border 1px solid Input Border Gray (#767676), border-radius 0px, no padding on input itself. Placeholder text Subtle Silver (#afafaf). Text style: UberMoveText, weight 400, size 16px.
4. Create a Feature Card: White background, 8px border-radius, 12px padding. Headline: 'Ride', UberMove, weight 400, size 20px, Midnight Ink. Body text: 'Go anywhere with Uber. Request a ride, hop in, and go.', UberMoveText, weight 400, size 14px, Charcoal Text (#333333). Link: 'Details', UberMoveText, weight 400, size 14px, Midnight Ink.
5. Create a Hero Headline: 'Go anywhere with Uber'. Font UberMove, weight 700, size 52px, Midnight Ink (#000000), line height 1.4.

## Similar Brands

- **Lyft** — Monochromatic base with a single prominent chromatic accent color, large type, and custom illustrations for brand identity.
- **Google Maps** — Focus on high-contrast text and interactive elements against a clean, functional white background, with minimal decorative elements.
- **DoorDash** — Uses a similar approach to custom typography for strong brand recognition and places emphasis on direct calls to action within a clean UI.
- **Airbnb** — Centered content with generous white space, custom typography, and a clean, user-focused interface for service booking.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-canvas-white: #ffffff;
  --color-whisper-gray: #f6f6f6;
  --color-charcoal-text: #333333;
  --color-input-border-gray: #767676;
  --color-subtle-silver: #afafaf;
  --color-slate-shadow: #d6d6d6;
  --color-lagoon-mist: #9dcdd6;

  /* Typography — Font Families */
  --font-ubermovetext: 'UberMoveText', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ubermove: 'UberMove', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --text-body-sm: 14px;
  --leading-body-sm: 1.43;
  --text-body: 16px;
  --leading-body: 1.2;
  --text-subheading: 18px;
  --leading-subheading: 1.25;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.22;
  --text-heading: 24px;
  --leading-heading: 1.33;
  --text-display: 36px;
  --leading-display: 1.23;
  --text-display-lg: 52px;
  --leading-display-lg: 1.4;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
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
  --spacing-48: 48px;
  --spacing-64: 64px;

  /* Layout */
  --section-gap: 48-80px;
  --card-padding: 12-24px;
  --element-gap: 4-24px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-full: 999px;

  /* Named Radii */
  --radius-misc: 12px;
  --radius-cards: 8px;
  --radius-buttons: 8px;
  --radius-capsule: 999px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-canvas-white: #ffffff;
  --color-whisper-gray: #f6f6f6;
  --color-charcoal-text: #333333;
  --color-input-border-gray: #767676;
  --color-subtle-silver: #afafaf;
  --color-slate-shadow: #d6d6d6;
  --color-lagoon-mist: #9dcdd6;

  /* Typography */
  --font-ubermovetext: 'UberMoveText', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ubermove: 'UberMove', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --text-body-sm: 14px;
  --leading-body-sm: 1.43;
  --text-body: 16px;
  --leading-body: 1.2;
  --text-subheading: 18px;
  --leading-subheading: 1.25;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.22;
  --text-heading: 24px;
  --leading-heading: 1.33;
  --text-display: 36px;
  --leading-display: 1.23;
  --text-display-lg: 52px;
  --leading-display-lg: 1.4;

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
  --spacing-48: 48px;
  --spacing-64: 64px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-full: 999px;
}
```

# Altius — Style Reference
> Midnight industrial orange glow.

**Theme:** mixed

Altius presents as a blockchain infrastructure provider with a strong, industrial aesthetic. Its visual system employs a stark contrast between very dark, almost black surfaces and a vibrant, warm orange accent, creating a technical yet energetic feel. Typography is dense and angular, complementing the structured grid and limited use of soft gradients. The overall atmosphere feels serious and high-stakes, amplified by the sparse, functional use of color and sharp edges on interactive elements.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#190501` | `--color-midnight-ink` | Primary background for dark sections, primary text, dark borders, and subtle graphical elements |
| Ghostly Gray | `#feeae6` | `--color-ghostly-gray` | Light background for interactive components, placeholder text, and secondary backgrounds in light sections. It serves as a near-white canvas with a subtle warm tint |
| Vivid Ember | `#fa5838` | `--color-vivid-ember` | Orange accent for outlined action borders, linked labels, and lightweight interactive emphasis. Do not promote it to the primary CTA color |
| Deep Garnet | `#631303` | `--color-deep-garnet` | Muted brand accent, decorative fills and strokes within graphics, often combined with box shadows to add depth |
| Charred Umber | `#340a01` | `--color-charred-umber` | Darker background tones for card surfaces, footer backgrounds, and as a border color for some links, providing depth within the dark palette |
| Soft Peach | `#fcac9c` | `--color-soft-peach` | Subtle background for information blocks and card surfaces in lighter sections of the page, acting as a secondary surface layer |
| Molten Orange | `#951c04` | `--color-molten-orange` | Orange accent for outlined action borders, linked labels, and lightweight interactive emphasis |
| Pure Canvas | `#f7f6ff` | `--color-pure-canvas` | Overarching page background in light sections, primary text for dark backgrounds, and subtle content borders |
| Deep Void | `#000000` | `--color-deep-void` | Pure black used primarily for decorative SVG fills and icon details, creating maximum contrast |
| Faded Stone | `#baadab` | `--color-faded-stone` | Muted text color for secondary content and borders on ghost buttons, providing a softer contrast than Pure Canvas |
| Input Gray | `#cccccc` | `--color-input-gray` | Neutral form states, badge text, and quiet UI feedback where color should stay understated. Do not promote it to the primary CTA color |

## Tokens — Typography

### Matter — Primary typeface for all UI elements, headlines, body text, and interactive components. Its angular, dense appearance reinforces the technical and direct brand identity. · `--font-matter`
- **Substitute:** Inter
- **Weights:** 400, 500, 700
- **Sizes:** 14px, 16px, 20px, 24px, 48px, 60px
- **Line height:** 1.08, 1.13, 1.16, 1.25, 1.40, 1.43, 1.50
- **Letter spacing:** -0.0430em, -0.0420em, -0.0400em, -0.0330em, -0.0100em
- **Role:** Primary typeface for all UI elements, headlines, body text, and interactive components. Its angular, dense appearance reinforces the technical and direct brand identity.

### Fabrikatmono — Monospaced typeface used for subtle code-like elements, data labels, and certain links, bringing a raw, technical detail to the design. The tight letter-spacing emphasizes its compact nature. · `--font-fabrikatmono`
- **Substitute:** Space Mono
- **Weights:** 400, 500
- **Sizes:** 14px, 16px, 20px
- **Line height:** 1.50, 1.75
- **Letter spacing:** -0.0500em, -0.0400em
- **Role:** Monospaced typeface used for subtle code-like elements, data labels, and certain links, bringing a raw, technical detail to the design. The tight letter-spacing emphasizes its compact nature.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 14px | 1.5 | -0.48px | `--text-caption` |
| body | 16px | 1.25 | -0.48px | `--text-body` |
| subheading | 20px | 1.16 | -0.66px | `--text-subheading` |
| heading-sm | 24px | 1.13 | -0.8px | `--text-heading-sm` |
| heading | 48px | 1.08 | -2.06px | `--text-heading` |
| display | 60px | 1.08 | -2.58px | `--text-display` |

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
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 108 | 108px | `--spacing-108` |
| 128 | 128px | `--spacing-128` |

### Border Radius

| Element | Value |
|---------|-------|
| inputs | 0px |
| buttons | 0px |
| default | 0px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| lg | `rgb(99, 19, 3) 0px 0px 20px 0px inset` | `--shadow-lg` |

### Layout

- **Section gap:** 48px
- **Card padding:** 16px
- **Element gap:** 8px

## Components

### Ghost Primary Button
**Role:** Call to action for primary interactions.

Text in Vivid Ember (#fa5838), with a 1px border in Molten Orange (#951c04). 8px vertical padding, 16px horizontal padding. No border-radius. No background fill, only borders on hover or focus.

### Ghost Secondary Button
**Role:** Call to action for secondary or alternative interactions.

Text in Faded Stone (#baadab), with a 1px border in Faded Stone (#baadab), active state border fades to Molten Orange (#951c04). 8px vertical padding, 16px horizontal padding. No border-radius.

### Ghost Link Button (Dark)
**Role:** Subtle button for navigation or tertiary actions on dark backgrounds.

Text in Ghostly Gray (#feeae6), with a 1px border in Ghostly Gray (#feeae6). 8px vertical padding, 0px horizontal padding. No border-radius. Often used inline with text.

### Ghost Link Button (Light)
**Role:** Subtle button for navigation or tertiary actions on light backgrounds.

Text in Midnight Ink (#190501), with a 1px border in Midnight Ink (#190501). 8px vertical padding, 16px horizontal padding. No border-radius. Used on Pure Canvas backgrounds.

### Input Field
**Role:** Standard input field for user data.

Background in Ghostly Gray (#feeae6), text color in Molten Orange (#951c04). A 1px border in Input Gray (#cccccc). 8px vertical padding, 12px horizontal padding. No border-radius.

### Key Feature Card (Dark)
**Role:** Display individual features or benefits on a dark background.

Dark card surface, likely Charred Umber (#340a01) or a similar dark hue. Uses an inset shadow rgb(99, 19, 3) 0px 0px 20px 0px for visual separation. Text can be Pure Canvas (#f7f6ff) or Ghostly Gray (#feeae6).

### Key Feature Card (Light)
**Role:** Display individual features or benefits on a light background.

Light card surface, using Soft Peach (#fcac9c) for background. Text in Midnight Ink (#190501) and accents in Vivid Ember (#fa5838). No specific border.

## Do's and Don'ts

### Do
- Prioritize Midnight Ink (#190501) for primary text and dark backgrounds and Pure Canvas (#f7f6ff) for light backgrounds and corresponding text to maintain high contrast.
- Use Molten Orange (#951c04) exclusively for action borders, error states, and high-emphasis text, signaling urgency or interactivity.
- Maintain a default border-radius of 0px for all elements, including buttons, inputs, and cards, to reinforce the sharp, angular aesthetic.
- Apply Fabrikatmono for data displays and code-like content, with tight letter-spacing of -0.0500em at 20px, to underscore technical precision.
- Structure layouts using a grid with element gaps of 8px and larger section gaps, typically 48px, for balanced density.
- Introduce depth primarily through inset box-shadows like `rgb(99, 19, 3) 0px 0px 20px 0px inset` rather than traditional drop shadows for contained components.
- Utilize Ghostly Gray (#feeae6) as a subtle, warm-tinted alternative to white for interactive backgrounds or muted text backgrounds.

### Don't
- Do not introduce rounded corners on any primary UI elements; maintain the sharp, rectangular appearance.
- Avoid using drop shadows for elevation; rely on the specified inset shadows to create depth.
- Do not dilute the Molten Orange (#951c04) accent color with other bright, saturated colors for UI elements.
- Do not use generic gray tones for text; always select from Midnight Ink (#190501), Pure Canvas (#f7f6ff), Faded Stone (#baadab), or Ghostly Gray (#feeae6) based on background contrast.
- Avoid large areas of pure white; instead, use Pure Canvas (#f7f6ff) or Ghostly Gray (#feeae6) for backgrounds to maintain a subtle warmth.
- Do not use gradients beyond what is specified for subtle background patterns, as the system favors sharp, solid color blocks.
- Avoid excessive imagery; the visual system is text and data-driven, with graphics serving mainly illustrative or infographical roles.

## Imagery

The visual language for imagery and graphics is predominantly abstract and technical, reinforcing the blockchain and data-centric nature of the brand. It features geometric illustrations and wireframe-style graphics, such as a globe enclosed in a transparent cube, often presented in duotone with shades of Molten Orange (#951c04) and Midnight Ink (#190501) or Pure Canvas (#f7f6ff). These are typically contained within defined areas, not full-bleed, and maintain the sharp, unrounded aesthetic. Iconography is minimalist, outlined, and monochromatic, usually in a dark color on light backgrounds or light on dark, with no multi-color elements. Photography is largely absent, focusing instead on stylized visual representations of technology and data structures to explain complex concepts.

## Layout

The page exhibits a mixed layout philosophy, alternating between a full-width dark hero section at the top and subsequent sections that are predominantly light, centered, and constrained horizontally. The hero features a large, centered headline and calls to action over an abstract, gradient-like background pattern. Following sections often present content in a responsive, two-column text-left/image-right or image-left/text-right arrangement or as three-column card grids. Vertical spacing between sections is generous and consistent (sectionGap: 48px). The navigation is a sticky top bar with minimal links and social icons, maintaining a streamlined, functional appearance. The overall density feels comfortable, prioritizing hierarchy and clarity over information packing.

## Agent Prompt Guide

Quick Color Reference:
text: #190501
background: #feeae6
border: #951c04
accent: #fa5838
primary action: #951c04 (outlined action border)

Example Component Prompts:
1. Create an Outlined Primary Action: Transparent background, #951c04 border and text, 9999px radius, compact pill padding. Use it for the main CTA instead of a filled button.
2. Design a feature card for a light background: Soft Peach (#fcac9c) background. Title '2.93x faster L2 execution' in Midnight Ink (#190501) at 24px using Matter semibold, letter-spacing -0.8px. Body text in Faded Stone (#baadab) at 16px, line-height 1.25. Use an icon with a Molten Orange (#951c04) border.
3. Create an input field for an email signup: Ghostly Gray (#feeae6) background, 1px Input Gray (#cccccc) border, no radius. Placeholder text 'Enter your email' in Faded Stone (#baadab) at 16px. Submit button is a ghost link button (Light) 'Subscribe' with Midnight Ink (#190501) text and border, 8px vertical padding, 16px horizontal padding.

## Similar Brands

- **Alchemy** — Similar focus on blockchain infrastructure with a clean but serious visual identity, geometric graphics, and a limited, high-contrast color palette.
- **Polygon** — Employs technical, geometric abstract graphics and a structured layout with a strong emphasis on data and performance visualization.
- **ConsenSys** — Uses dark themes mixed with lighter sections, a structured content approach, and a focus on impactful, direct headlines for technical audience.
- **Supabase** — Shares a technical, developer-centric aesthetic with dark UI elements, strong typography, and limited, focused use of accent colors.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #190501;
  --color-ghostly-gray: #feeae6;
  --color-vivid-ember: #fa5838;
  --color-deep-garnet: #631303;
  --color-charred-umber: #340a01;
  --color-soft-peach: #fcac9c;
  --color-molten-orange: #951c04;
  --color-pure-canvas: #f7f6ff;
  --color-deep-void: #000000;
  --color-faded-stone: #baadab;
  --color-input-gray: #cccccc;

  /* Typography — Font Families */
  --font-matter: 'Matter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-fabrikatmono: 'Fabrikatmono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.5;
  --tracking-caption: -0.48px;
  --text-body: 16px;
  --leading-body: 1.25;
  --tracking-body: -0.48px;
  --text-subheading: 20px;
  --leading-subheading: 1.16;
  --tracking-subheading: -0.66px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.13;
  --tracking-heading-sm: -0.8px;
  --text-heading: 48px;
  --leading-heading: 1.08;
  --tracking-heading: -2.06px;
  --text-display: 60px;
  --leading-display: 1.08;
  --tracking-display: -2.58px;

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
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-108: 108px;
  --spacing-128: 128px;

  /* Layout */
  --section-gap: 48px;
  --card-padding: 16px;
  --element-gap: 8px;

  /* Named Radii */
  --radius-inputs: 0px;
  --radius-buttons: 0px;
  --radius-default: 0px;

  /* Shadows */
  --shadow-lg: rgb(99, 19, 3) 0px 0px 20px 0px inset;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #190501;
  --color-ghostly-gray: #feeae6;
  --color-vivid-ember: #fa5838;
  --color-deep-garnet: #631303;
  --color-charred-umber: #340a01;
  --color-soft-peach: #fcac9c;
  --color-molten-orange: #951c04;
  --color-pure-canvas: #f7f6ff;
  --color-deep-void: #000000;
  --color-faded-stone: #baadab;
  --color-input-gray: #cccccc;

  /* Typography */
  --font-matter: 'Matter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-fabrikatmono: 'Fabrikatmono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.5;
  --tracking-caption: -0.48px;
  --text-body: 16px;
  --leading-body: 1.25;
  --tracking-body: -0.48px;
  --text-subheading: 20px;
  --leading-subheading: 1.16;
  --tracking-subheading: -0.66px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.13;
  --tracking-heading-sm: -0.8px;
  --text-heading: 48px;
  --leading-heading: 1.08;
  --tracking-heading: -2.06px;
  --text-display: 60px;
  --leading-display: 1.08;
  --tracking-display: -2.58px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-108: 108px;
  --spacing-128: 128px;

  /* Shadows */
  --shadow-lg: rgb(99, 19, 3) 0px 0px 20px 0px inset;
}
```

# 8returns — Style Reference
> Dark canvas, vibrant product spotlight. A precise, focused digital workspace.

**Theme:** light

8returns presents a high-contrast interface with a dark, commanding hero offset by clean, bright content sections. The visual style balances product-focused professionalism with interactive vibrancy, primarily through a luminous green accent. Surfaces are subtly rounded, and components maintain a lightweight yet distinct presence, fostering an approachable user experience within a data-intensive domain. The system employs structured layouts with generous spacing to clarify complex information while maintaining visual order.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `linear-gradient(135deg, rgb(5, 25, 35) 0%, rgb(10, 42, 56) 100%)` | `--color-midnight-ink` | Primary background for commanding sections (hero, footer), prominent text, and dark button fills. Also used for dark borders to define structure; Subtle background gradient primarily in dark sections, adding atmospheric depth |
| Lagoon Teal | `radial-gradient(80% 80%, rgb(0, 102, 112) 0%, rgb(0, 72, 83) 50%, rgb(0, 56, 64) 100%)` | `--color-lagoon-teal` | Background for product screenshots/cards, adding a muted blue-green depth; Background gradient for product cards or specific visual elements, enriching the brand's blue-green palette |
| Spring Green | `#cfff69` | `--color-spring-green` | Primary action background, key interactive elements, and accent for highlights. Provides a vivid, energetic contrast |
| Vivid Violet | `linear-gradient(135deg, rgb(98, 137, 255) 0%, rgb(74, 111, 224) 100%)` | `--color-vivid-violet` | Used for specific decorative fills and contextual text, offering an alternative accent hue; Decorative gradient for specific accent elements, providing a vibrant, slightly dimensional feel |
| Paper White | `#ffffff` | `--color-paper-white` | Main canvas background for light theme sections, prominent text on dark backgrounds, and ghost button borders/text |
| Deep Space | `#000000` | `--color-deep-space` | Footer background and specific dark button fills for deep contrast |
| Light Smoke | `#eef0f2` | `--color-light-smoke` | Subtle background for light sections and card surfaces, providing a near-white canvas with a touch of texture |
| Silver Mist | `#bfbfbf` | `--color-silver-mist` | Supportive background for elevated cards, adding a faint neutral layer |
| Lead Gray | `#525252` | `--color-lead-gray` | Muted body text, helper text, and secondary icon colors |
| Platinum Hue | `#e0e0e0` | `--color-platinum-hue` | Fine borders and separators, providing subtle visual division |
| Deep Iris | `#1e3039` | `--color-deep-iris` | Darker shade for borders, hinting at more subtle structure than Midnight Ink |
| Starlight | `#c8d4e0` | `--color-starlight` | Elevated card backgrounds, offering a slightly cool, luminous surface |

## Tokens — Typography

### roobert — Primary typeface for all UI and content. Its geometric yet approachable sans-serif style provides clarity and a modern, technical feel. A wide range of weights supports a clear typographic hierarchy. · `--font-roobert`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400, 500, 600, 700
- **Sizes:** 10px, 11px, 13px, 14px, 16px, 18px, 20px, 22px, 26px, 48px, 56px, 60px, 64px
- **Line height:** 1.07, 1.16, 1.23, 1.24, 1.25, 1.27, 1.38, 1.40, 1.43, 1.44, 1.45, 1.50, 1.54, 1.56, 1.63
- **Letter spacing:** Ranges from 0.005em for smaller text up to 0.036em for very small elements, emphasizing a clean, open read.
- **Role:** Primary typeface for all UI and content. Its geometric yet approachable sans-serif style provides clarity and a modern, technical feel. A wide range of weights supports a clear typographic hierarchy.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.5 | 0.36px | `--text-caption` |
| body | 14px | 1.54 | 0.05px | `--text-body` |
| body-lg | 18px | 1.5 | — | `--text-body-lg` |
| subheading | 22px | 1.27 | — | `--text-subheading` |
| heading | 48px | 1.16 | — | `--text-heading` |
| heading-lg | 56px | 1.07 | — | `--text-heading-lg` |
| display | 64px | 1.07 | — | `--text-display` |

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
| 96 | 96px | `--spacing-96` |
| 120 | 120px | `--spacing-120` |
| 128 | 128px | `--spacing-128` |
| 160 | 160px | `--spacing-160` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 16px |
| input | 6px |
| buttons | 32px |
| default | 16px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| xl | `rgba(0, 0, 0, 0.25) 0px 25px 50px -12px` | `--shadow-xl` |
| subtle | `rgba(0, 0, 0, 0.07) 0px 1px 2px 0px` | `--shadow-subtle` |
| subtle-2 | `rgba(0, 0, 0, 0.1) 0px 1px 3px 0px, rgba(0, 0, 0, 0.06) 0...` | `--shadow-subtle-2` |

### Layout

- **Section gap:** 24px
- **Card padding:** 32px
- **Element gap:** 4px

## Components

### Primary Action Button (Filled)
**Role:** Core call-to-action button for initiating key actions.

Background: Spring Green (#cfff69), Text: Midnight Ink (#051923), Radius: 32px, Padding: 12px vertical, 20px horizontal. Uses roobert font.

### Dark Action Button (Filled)
**Role:** Alternative call-to-action for dark sections, offering strong contrast.

Background: Deep Space (#000000), Text: Paper White (#ffffff), Radius: 32px, Padding: 12px vertical, 20px horizontal. Uses roobert font.

### Ghost Button (Dark Text)
**Role:** Secondary action button, typically for navigation or less critical actions.

Background: transparent, Text: Midnight Ink (#051923), Border: 1px solid Midnight Ink (#051923), Radius: 0px, Padding: 0px. Uses roobert font.

### Ghost Button (Light Text)
**Role:** Secondary action button on dark backgrounds, offering a subtle interactive element.

Background: transparent, Text: Paper White (#ffffff), Border: 1px solid Paper White (#ffffff), Radius: 0px, Padding: 8px vertical, 12px horizontal. Uses roobert font.

### Product Display Card (Lagoon Teal)
**Role:** Card for showcasing product screenshots or specific feature blocks.

Background: Lagoon Teal (#004853), Radius: 16px, Box Shadow: none, Padding: 0px.

### Neutral Content Card (Light Smoke)
**Role:** Standard card for general content separation on light backgrounds.

Background: Light Smoke (#eef0f2), Radius: 16px, Box Shadow: none, Padding: 48px.

### Testimonial Card
**Role:** Elevated card for testimonials or user-generated content.

Background: Paper White (#ffffff), Radius: 16px, Box Shadow: rgba(0, 0, 0, 0.1) 0px 1px 3px 0px, rgba(0, 0, 0, 0.06) 0px 1px 2px 0px, Padding: 0px.

### Interactive List Item Card
**Role:** Card for interactive list items, often seen in product UI simulations.

Background: Silver Mist (#bfbfbf), Radius: 0px, Box Shadow: none, Padding: 0px.

### Navigation Link
**Role:** Top-level navigation items in headers.

Text: Midnight Ink (#051923), no explicit background, no radius, no padding in typical header usage.

## Do's and Don'ts

### Do
- Prioritize Midnight Ink (#051923) for dark backgrounds and primary textual content, especially headlines.
- Use Spring Green (#cfff69) exclusively for primary calls-to-action and key interactive highlights, never for large content blocks.
- Maintain a clear visual hierarchy with Roobert font, utilizing various weights to distinguish headings from body text.
- Apply 32px border-radius consistently to all prominent buttons and 16px to cards for a cohesive, friendly feel.
- Ensure generous spacing, with 24px section gaps and 4px element gaps, to maintain content readability and comfortable density.
- Utilize Paper White (#ffffff) and Light Smoke (#eef0f2) for backgrounds in light content sections, providing visual breathing room.
- Employ ghost buttons with 0px radius where secondary actions are needed, using either Midnight Ink or Paper White for text and border depending on the background.

### Don't
- Avoid using Spring Green (#cfff69) as a general decorative color or for extensive text, as it should signal interactivity.
- Do not deviate from the Roobert font family; consistency across all text elements is critical for brand recognition.
- Refrain from introducing new border radii; stick to the established 32px for buttons and 16px for cards.
- Do not place large blocks of text in Midnight Ink (#051923) on Paper White (#ffffff) backgrounds; use Lead Gray (#525252) for body copy on light surfaces.
- Avoid overly bold or decorative shadows beyond the defined card shadow, as the system relies on subtle elevation.
- Do not use saturated colors for borders, with the exception of the Spring Green (#cfff69) accent color for specific interactive states.
- Do not introduce gradients other than Twilight Gradient, Oceanic Gradient, or Skybound Gradient, and only for their defined atmospheric or accent roles.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Light Smoke Canvas | `#eef0f2` | Primary background for most light content sections, providing a soft, almost white base. |
| 1 | Paper White Card | `#ffffff` | Default background for cards and elevated content blocks, slightly brighter than the canvas. |
| 2 | Silver Mist Card | `#bfbfbf` | Background for subtle, interactive list item cards within a product UI. |
| 3 | Lagoon Teal Product Showcase | `#004853` | Distinct, darker surface for embedded product visuals, creating a focused display area. |

## Elevation

- **Card:** `rgba(0, 0, 0, 0.1) 0px 1px 3px 0px, rgba(0, 0, 0, 0.06) 0px 1px 2px 0px`
- **Pop-up/Modal (larger):** `rgba(0, 0, 0, 0.25) 0px 25px 50px -12px`

## Imagery

This site uses a mix of visually rich elements. Photography features tightly cropped product shots on pure white or subtle minimalist backgrounds, focusing on the product itself with a clean, high-key treatment. For testimonials and social proof, candid lifestyle photography with a natural, unposed feel is used, often within rounded cards. Illustrations are not prominent. Icons are minimal, typically outlined and monochrome, with an apparent stroke weight, serving functional roles rather than decorative. Product screenshots are integral, often presented within a Lagoon Teal (#004853) masked card container to simulate in-app experiences. Imagery serves both decorative atmosphere in hero sections and explanatory content within feature blocks, with a text-dominant layout giving imagery specific, contained roles.

## Layout

The page adheres to a max-width contained layout, likely around 1200px, with content centered. The hero section is full-bleed and dark, featuring a large, centered headline over a background that often includes product UI simulations. Subsequent sections alternate between light (#eef0f2) and Paper White (#ffffff) backgrounds, creating a clear visual rhythm. Content is generally arranged in two-column text and image sections, sometimes reversing order. Feature blocks often consolidate into 3-column card grids. There's a generous vertical spacing between sections, contributing to a comfortable density. Navigation is a sticky top bar with clearly defined links and two action buttons on the right.

## Agent Prompt Guide

Quick Color Reference: 
- Text: #051923 (Midnight Ink)
- Background: #eef0f2 (Light Smoke)
- Border: #e0e0e0 (Platinum Hue)
- Accent: #6289ff (Vivid Violet)
- primary action: #cfff69 (filled action)

Example Component Prompts:
- Create a hero call-to-action button: '#cfff69' background, '#051923' text, 32px radius, '12px 20px' padding, `roobert` font weight `700` and size `16px`.
- Create a dark ghost button for navigation: transparent background, '#ffffff' text, 0px radius, 1px solid '#ffffff' border, '8px 12px' padding, `roobert` font weight `400` and size `14px`.
- Create a standard content card: '#ffffff' background, 16px radius, `rgba(0, 0, 0, 0.1) 0px 1px 3px 0px, rgba(0, 0, 0, 0.06) 0px 1px 2px 0px` shadow, '48px' padding.
- Create an input field: '#ffffff' background, 6px radius, 1px solid '#e0e0e0' border, `roobert` font weight `400` and size `16px` for text and placeholder, text color '#051923', placeholder color '#a1a1aa'.

## Similar Brands

- **Stripe** — Shares a sophisticated, data-driven feel with a clean, high-contrast interface and strong typographic hierarchy.
- **Linear** — Exhibits a similar dark hero section contrasting with lighter content areas, and focused interactive elements.
- **RudderStack** — Utilizes a balanced approach of dark and light sections for product-focused content, with clear accent colors for actions.
- **Amplitude** — Features a similar dedication to precise, professional typography and layout to communicate complex information effectively.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #051923;
  --gradient-midnight-ink: linear-gradient(135deg, rgb(5, 25, 35) 0%, rgb(10, 42, 56) 100%);
  --color-lagoon-teal: #004853;
  --gradient-lagoon-teal: radial-gradient(80% 80%, rgb(0, 102, 112) 0%, rgb(0, 72, 83) 50%, rgb(0, 56, 64) 100%);
  --color-spring-green: #cfff69;
  --color-vivid-violet: #6289ff;
  --gradient-vivid-violet: linear-gradient(135deg, rgb(98, 137, 255) 0%, rgb(74, 111, 224) 100%);
  --color-paper-white: #ffffff;
  --color-deep-space: #000000;
  --color-light-smoke: #eef0f2;
  --color-silver-mist: #bfbfbf;
  --color-lead-gray: #525252;
  --color-platinum-hue: #e0e0e0;
  --color-deep-iris: #1e3039;
  --color-starlight: #c8d4e0;

  /* Typography — Font Families */
  --font-roobert: 'roobert', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --tracking-caption: 0.36px;
  --text-body: 14px;
  --leading-body: 1.54;
  --tracking-body: 0.05px;
  --text-body-lg: 18px;
  --leading-body-lg: 1.5;
  --text-subheading: 22px;
  --leading-subheading: 1.27;
  --text-heading: 48px;
  --leading-heading: 1.16;
  --text-heading-lg: 56px;
  --leading-heading-lg: 1.07;
  --text-display: 64px;
  --leading-display: 1.07;

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
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-96: 96px;
  --spacing-120: 120px;
  --spacing-128: 128px;
  --spacing-160: 160px;

  /* Layout */
  --section-gap: 24px;
  --card-padding: 32px;
  --element-gap: 4px;

  /* Border Radius */
  --radius-sm: 1px;
  --radius-md: 6px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;

  /* Named Radii */
  --radius-cards: 16px;
  --radius-input: 6px;
  --radius-buttons: 32px;
  --radius-default: 16px;

  /* Shadows */
  --shadow-xl: rgba(0, 0, 0, 0.25) 0px 25px 50px -12px;
  --shadow-subtle: rgba(0, 0, 0, 0.07) 0px 1px 2px 0px;
  --shadow-subtle-2: rgba(0, 0, 0, 0.1) 0px 1px 3px 0px, rgba(0, 0, 0, 0.06) 0px 1px 2px 0px;

  /* Surfaces */
  --surface-light-smoke-canvas: #eef0f2;
  --surface-paper-white-card: #ffffff;
  --surface-silver-mist-card: #bfbfbf;
  --surface-lagoon-teal-product-showcase: #004853;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #051923;
  --color-lagoon-teal: #004853;
  --color-spring-green: #cfff69;
  --color-vivid-violet: #6289ff;
  --color-paper-white: #ffffff;
  --color-deep-space: #000000;
  --color-light-smoke: #eef0f2;
  --color-silver-mist: #bfbfbf;
  --color-lead-gray: #525252;
  --color-platinum-hue: #e0e0e0;
  --color-deep-iris: #1e3039;
  --color-starlight: #c8d4e0;

  /* Typography */
  --font-roobert: 'roobert', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --tracking-caption: 0.36px;
  --text-body: 14px;
  --leading-body: 1.54;
  --tracking-body: 0.05px;
  --text-body-lg: 18px;
  --leading-body-lg: 1.5;
  --text-subheading: 22px;
  --leading-subheading: 1.27;
  --text-heading: 48px;
  --leading-heading: 1.16;
  --text-heading-lg: 56px;
  --leading-heading-lg: 1.07;
  --text-display: 64px;
  --leading-display: 1.07;

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
  --spacing-96: 96px;
  --spacing-120: 120px;
  --spacing-128: 128px;
  --spacing-160: 160px;

  /* Border Radius */
  --radius-sm: 1px;
  --radius-md: 6px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;

  /* Shadows */
  --shadow-xl: rgba(0, 0, 0, 0.25) 0px 25px 50px -12px;
  --shadow-subtle: rgba(0, 0, 0, 0.07) 0px 1px 2px 0px;
  --shadow-subtle-2: rgba(0, 0, 0, 0.1) 0px 1px 3px 0px, rgba(0, 0, 0, 0.06) 0px 1px 2px 0px;
}
```

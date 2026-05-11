# Felt — Style Reference
> Deep forest data canvas

**Theme:** dark

Felt employs a dark, command-center aesthetic, with a cool green canvas creating a sense of depth and focus for data visualization. Typography is crisp and authoritative, striking a balance between traditional elegance and modern clarity. Functional elements are highlighted with a warm amber tone, contrasting effectively with the predominantly muted green and deep grayscale palette. Components are lightweight and precise, often featuring subtle borders and minimal radii to maintain a structured yet unobtrusive interface.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Forest Canvas | `#3d521e` | `--color-forest-canvas` | Primary page background, large surface areas, and section dividers — establishes the deep, nature-inspired base hue |
| Nightfall Surface | `#314218` | `--color-nightfall-surface` | Secondary surface background for cards and elevated components, providing a slight visual lift from the main canvas |
| Text Primary | `#eeeeee` | `--color-text-primary` | Primary text color for headlines and main content — offers strong contrast against dark backgrounds |
| Text Secondary | `#ffffff` | `--color-text-secondary` | Secondary text and critical UI elements like navigation links and active states, providing maximum visibility |
| Text Tertiary | `#333333` | `--color-text-tertiary` | Muted text for secondary information, helper text, and subtle details, typically reserved for light-on-dark scenarios (e.g. within a UI window) |
| Warm Ember | `#dc8c46` | `--color-warm-ember` | Primary action color for buttons, links, and interactive elements — a vivid highlight that guides user interaction. This serves as the brand's key accent color |
| Muted Sage | `#64754b` | `--color-muted-sage` | Subtle interactive backgrounds and borders for ghost buttons or less prominent calls to action |
| Felt Deepest Green | `#212f0c` | `--color-felt-deepest-green` | Darkest background for UI elements like input fields or specialized dark mode components, providing maximum depth |
| Felt Darkest Base | `#18210c` | `--color-felt-darkest-base` | Base layer for overlaying dark components or deepest UI sections, establishing the lowest visual point |

## Tokens — Typography

### Gt Alpina Standard — Headlines and prominent display text — weight 300 offers a counter-intuitive lightness for large sizes, creating an effect of authority through restraint rather than volume. Weight 400 rounds out the display usage. · `--font-gt-alpina-standard`
- **Substitute:** Georgia
- **Weights:** 300, 400
- **Sizes:** 28px, 36px, 43px, 46px, 50px, 86px
- **Line height:** 0.80, 0.96, 1.00, 1.11, 1.33
- **Letter spacing:** -0.04em at 86px, -0.033em at 50px
- **Role:** Headlines and prominent display text — weight 300 offers a counter-intuitive lightness for large sizes, creating an effect of authority through restraint rather than volume. Weight 400 rounds out the display usage.

### Atlasgrotesk Cy Web — Body text, navigation, and functional UI elements — the slight 0.033em letter-spacing adds a subtle spaciousness, optimizing legibility for interface-heavy content. · `--font-atlasgrotesk-cy-web`
- **Substitute:** Inter
- **Weights:** 300, 400, 500, 700
- **Sizes:** 12px, 14px, 16px, 18px, 19px, 20px
- **Line height:** 1.00, 1.11, 1.20, 1.25, 1.30, 1.33, 1.43, 1.50, 1.56
- **Letter spacing:** 0.033em
- **Role:** Body text, navigation, and functional UI elements — the slight 0.033em letter-spacing adds a subtle spaciousness, optimizing legibility for interface-heavy content.

### Arial — Fallback and specific utility text — used sparingly for system-level information and certain UI labels. · `--font-arial`
- **Substitute:** sans-serif
- **Weights:** 400
- **Sizes:** 14px, 16px
- **Line height:** 1.25, 1.33, 1.43
- **Letter spacing:** normal
- **Role:** Fallback and specific utility text — used sparingly for system-level information and certain UI labels.

### Times New Roman — Decorative or highly specific, content-driven callouts, leveraging its traditional serif feel for emphasis. · `--font-times-new-roman`
- **Substitute:** serif
- **Weights:** 400
- **Sizes:** 36px, 101px
- **Line height:** 0.88, 2.46
- **Letter spacing:** normal
- **Role:** Decorative or highly specific, content-driven callouts, leveraging its traditional serif feel for emphasis.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.5 | 0.33px | `--text-caption` |
| body-sm | 14px | 1.43 | 0.46px | `--text-body-sm` |
| body | 16px | 1.33 | 0.53px | `--text-body` |
| subheading | 18px | 1.25 | 0.59px | `--text-subheading` |
| heading-sm | 20px | 1.2 | 0.66px | `--text-heading-sm` |
| heading | 28px | 1.11 | -1.12px | `--text-heading` |
| heading-lg | 50px | 1 | -1.65px | `--text-heading-lg` |
| display | 86px | 0.8 | -3.44px | `--text-display` |

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
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 72 | 72px | `--spacing-72` |
| 80 | 80px | `--spacing-80` |
| 120 | 120px | `--spacing-120` |
| 144 | 144px | `--spacing-144` |
| 160 | 160px | `--spacing-160` |

### Border Radius

| Element | Value |
|---------|-------|
| buttons | 20px |
| default | 6px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| sm | `rgba(0, 0, 0, 0.2) 0px 2px 5px 0px` | `--shadow-sm` |

### Layout

- **Section gap:** 24px
- **Card padding:** 12px
- **Element gap:** 12px

## Components

### Primary Action Button
**Role:** Main call-to-action button, drawing attention with the brand's accent color.

Background: Warm Ember (#dc8c46), Text: Text Primary (#eeeeee), Padding: 16px vertical, 20px horizontal. Radius: 20px. Font: Atlasgrotesk Cy Web, weight 400.

### Secondary Action Button
**Role:** Subtle button with a transparent background, used for secondary actions or navigation.

Background: rgba(255, 255, 255, 0.2), Text: Text Secondary (#ffffff), Border: 1px solid Text Primary (#eeeeee - inferred, data indicates white border on transparent button). Padding: 16px vertical, 20px horizontal. Radius: 20px. Font: Atlasgrotesk Cy Web, weight 400.

### Ghost Navigation Button
**Role:** Navigation items in the header, acting as ghost buttons.

Background: transparent, Text: Text Secondary (#ffffff), Border: 1px solid White (#ffffff), Padding: 16px vertical, 32px horizontal (adjusts for text length). Radius: 0px. Font: Atlasgrotesk Cy Web, weight 400.

### Outline Link Button (Warm Ember)
**Role:** Outlined button or link, using the brand accent color for border and text.

Background: transparent, Text: Warm Ember (#dc8c46), Border: 1px solid Warm Ember (#dc8c46), Padding: 14px vertical, 14px horizontal. Radius: 0px. Font: Atlasgrotesk Cy Web, weight 400.

### Badge Neutral
**Role:** Inline labels or small informational markers.

Background: transparent, Text: rgba(255, 255, 255, 0.8), Radius: 0px.

### UI Container Card
**Role:** Small, contained UI panels like the footer or specific data widgets.

Background: Felt Deepest Green (#212f0c), Padding: typically 12px or 24px vertical, 24px horizontal. Radius: 6px. Shadow: rgba(0, 0, 0, 0.2) 0px 2px 5px 0px.

## Do's and Don'ts

### Do
- Prioritize Forest Canvas (#3d521e) as the dominant background color for most sections, establishing the brand's deep green aesthetic.
- Use Warm Ember (#dc8c46) exclusively for primary calls to action and critical interactive elements to maintain its high visual impact.
- Employ Gt Alpina Standard weight 300 for all major headings to convey authority through subtle, elegant typography.
- Always use Atlasgrotesk Cy Web with 0.033em letter-spacing for body text and UI labels to ensure clarity and consistency.
- Apply a 20px border-radius to all filled buttons to create a softer, more approachable interactive element.
- Maintain a clear distinction between surface levels using Felt Darkest Base (#18210c), Felt Deepest Green (#212f0c), and Nightfall Surface (#314218) for progressively elevated elements.
- Utilize 12px for `elementGap` to ensure comfortable spacing between interactive elements and components.

### Don't
- Do not use saturated colors other than Warm Ember for accentuation; maintain the muted green and achromatic palette elsewhere.
- Avoid large, uncontained blocks of light or white content; surfaces should primarily be dark or muted green.
- Do not vary the letter-spacing for Atlasgrotesk Cy Web; the 0.033em value is a signature characteristic.
- Do not use standard serif fonts for UI elements; Times New Roman should be reserved for decorative text.
- Avoid excessive use of drop shadows; limit them to clearly elevated UI components like deep container cards.
- Never use `0px` border-radius for action buttons, as 20px is core to their visual identity.
- Do not introduce strong gradients in backgrounds; the system relies on solid color fields and subtle shifts in dark green tones.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Felt Darkest Base | `#18210c` | Lowest base layer, for deep background or the most recessed elements. |
| 1 | Felt Deepest Green | `#212f0c` | First level of elevated surface, typically for UI containers and card backgrounds within the main content area. |
| 2 | Nightfall Surface | `#314218` | Secondary elevated surface, providing a slight visual lift from base backgrounds for data panels or content blocks. |
| 3 | Forest Canvas | `#3d521` | Primary page background and large content section canvas, establishing the overall dark green tone. |

## Elevation

- **UI Container Card:** `rgba(0, 0, 0, 0.2) 0px 2px 5px 0px`

## Imagery

Imagery primarily consists of maps and GIS data visualizations, often presented as embedded UI elements or product screenshots. When present, images are contained within the dark UI, sometimes with subtle shadows. There's a minimal use of abstract graphics or photography. Icons are generally simple, outlined, and monochromatic, used functionally to represent actions or categories within the dark UI.

## Layout

The page uses a maximum-width contained layout, though the hero section often spills into a full-bleed background. The hero features a large centered headline and calls to action over a dark green background. Content sections follow a vertical rhythm with consistent spacing, often alternating between centered stacks and split layouts with text on one side and a visual (map, screenshot) on the other. A notable element is the embedded dark UI panel, which frequently overlays sections for dynamic product showcasing. The navigation is a sticky top bar with ghost buttons and a prominent 'Sign Up' button.

## Agent Prompt Guide

Quick Color Reference:
- Text: #eeeeee
- Background: #3d521e
- Border: #eeeeee (neutral), #dc8c46 (accent)
- Accent: #dc8c46
- primary action: #ffffff (filled action)

Example Component Prompts:
1. Create a Primary Action Button: #ffffff background, #eeeeee text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.

## Similar Brands

- **Linear** — Dark UI, structured layout, and a single accent color for interaction and brand differentiation.
- **Replit** — Code editor-like aesthetic, dark background, and emphasis on functional UI elements over decorative imagery.
- **Figma (dark mode)** — Highly functional dark interface where design tooling is paramount, with controlled use of color for interaction and status.
- **Vercel** — Developer-centric, dark-themed platform with clean typography and a focus on essential UI components.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-forest-canvas: #3d521e;
  --color-nightfall-surface: #314218;
  --color-text-primary: #eeeeee;
  --color-text-secondary: #ffffff;
  --color-text-tertiary: #333333;
  --color-warm-ember: #dc8c46;
  --color-muted-sage: #64754b;
  --color-felt-deepest-green: #212f0c;
  --color-felt-darkest-base: #18210c;

  /* Typography — Font Families */
  --font-gt-alpina-standard: 'Gt Alpina Standard', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-atlasgrotesk-cy-web: 'Atlasgrotesk Cy Web', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-times-new-roman: 'Times New Roman', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: 0.33px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.43;
  --tracking-body-sm: 0.46px;
  --text-body: 16px;
  --leading-body: 1.33;
  --tracking-body: 0.53px;
  --text-subheading: 18px;
  --leading-subheading: 1.25;
  --tracking-subheading: 0.59px;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: 0.66px;
  --text-heading: 28px;
  --leading-heading: 1.11;
  --tracking-heading: -1.12px;
  --text-heading-lg: 50px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -1.65px;
  --text-display: 86px;
  --leading-display: 0.8;
  --tracking-display: -3.44px;

  /* Typography — Weights */
  --font-weight-light: 300;
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
  --spacing-36: 36px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-120: 120px;
  --spacing-144: 144px;
  --spacing-160: 160px;

  /* Layout */
  --section-gap: 24px;
  --card-padding: 12px;
  --element-gap: 12px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-lg: 10px;
  --radius-2xl: 20px;

  /* Named Radii */
  --radius-buttons: 20px;
  --radius-default: 6px;

  /* Shadows */
  --shadow-sm: rgba(0, 0, 0, 0.2) 0px 2px 5px 0px;

  /* Surfaces */
  --surface-felt-darkest-base: #18210c;
  --surface-felt-deepest-green: #212f0c;
  --surface-nightfall-surface: #314218;
  --surface-forest-canvas: #3d521;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-forest-canvas: #3d521e;
  --color-nightfall-surface: #314218;
  --color-text-primary: #eeeeee;
  --color-text-secondary: #ffffff;
  --color-text-tertiary: #333333;
  --color-warm-ember: #dc8c46;
  --color-muted-sage: #64754b;
  --color-felt-deepest-green: #212f0c;
  --color-felt-darkest-base: #18210c;

  /* Typography */
  --font-gt-alpina-standard: 'Gt Alpina Standard', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-atlasgrotesk-cy-web: 'Atlasgrotesk Cy Web', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-times-new-roman: 'Times New Roman', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: 0.33px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.43;
  --tracking-body-sm: 0.46px;
  --text-body: 16px;
  --leading-body: 1.33;
  --tracking-body: 0.53px;
  --text-subheading: 18px;
  --leading-subheading: 1.25;
  --tracking-subheading: 0.59px;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: 0.66px;
  --text-heading: 28px;
  --leading-heading: 1.11;
  --tracking-heading: -1.12px;
  --text-heading-lg: 50px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -1.65px;
  --text-display: 86px;
  --leading-display: 0.8;
  --tracking-display: -3.44px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-120: 120px;
  --spacing-144: 144px;
  --spacing-160: 160px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-lg: 10px;
  --radius-2xl: 20px;

  /* Shadows */
  --shadow-sm: rgba(0, 0, 0, 0.2) 0px 2px 5px 0px;
}
```

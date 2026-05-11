# Clutch Security — Style Reference
> Minimalist digital blueprint

**Theme:** light

Clutch uses a stark, high-contrast visual language with a focus on deep blacks and crisp whites, punctuated by a vivid electric blue. Typography is tight and strong, often appearing in gradients or with subtle chromatic accents within content. Surfaces are mostly flat, with minimal shadows used only for interactive elements, contributing to a sense of digital precision. The overall impression is one of serious, modern technology with a clear visual hierarchy.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card surfaces, dominant backdrop for all content |
| Ink Black | `linear-gradient(rgb(25, 25, 25), rgb(0, 0, 0))` | `--color-ink-black` | Neutral form states, badge text, and quiet UI feedback where color should stay understated. Do not promote it to the primary CTA color; Backgrounds for decorative elements and visual flourishes, enhancing the high-tech aesthetic |
| Storm Gray | `#e5e7eb` | `--color-storm-gray` | Subtle borders, dividers, ghost button outlines, and background accents for secondary elements |
| Muted Gray | `#dfdfdf` | `--color-muted-gray` | Slightly darker borders, subtle background accents, and card outlines, often for quieter sections |
| Whisper Gray | `#c9c9c9` | `--color-whisper-gray` | Faded heading text, secondary text, and less prominent background fills, creating visual depth without strong contrast |
| Dim Gray | `#6e6e6e` | `--color-dim-gray` | Muted link text, secondary body copy, sub-labels, conveying information without demanding primary attention |
| Electric Blue | `conic-gradient(from 206.55deg at 18.84% 51%, rgba(255, 255, 255, 0) -137.29deg, rgba(255, 255, 255, 0) 201.31deg, rgb(0, 77, 255) 197.22deg, rgb(217, 228, 255) 200.69deg, rgb(0, 77, 255) 201.02deg, rgb(0, 0, 0) 201.15deg, rgba(255, 255, 255, 0) 200.71deg, rgba(255, 255, 255, 0) 552.71deg)` | `--color-electric-blue` | Primary calls to action, interactive elements, accent for key information, indicating activation and importance; Complex background fills for hero sections and illustrative elements, blending brand blue with neutrals for visual interest |

## Tokens — Typography

### Inter — General body text, navigation elements, form inputs, and secondary UI labels. Provides clarity and legibility for informational content. · `--font-inter`
- **Substitute:** system-ui
- **Weights:** 400, 500, 700
- **Sizes:** 12px, 14px, 15px, 16px, 17px
- **Line height:** 1.30, 1.40, 1.50
- **Letter spacing:** -0.02, 0.12
- **Role:** General body text, navigation elements, form inputs, and secondary UI labels. Provides clarity and legibility for informational content.

### PP Radio Grotesk — Primary headlines, subheadings, and emphasized content. Its custom nature and varying tracking create strong visual impact and brand distinctiveness. · `--font-pp-radio-grotesk`
- **Substitute:** sans-serif
- **Weights:** 400, 500, 600
- **Sizes:** 10px, 12px, 13px, 14px, 20px, 24px, 26px, 32px, 38px, 56px, 68px
- **Line height:** 1.10, 1.20, 1.30, 1.40, 1.50
- **Letter spacing:** -0.01, 0.01, 0.02, 0.12, 0.16
- **Role:** Primary headlines, subheadings, and emphasized content. Its custom nature and varying tracking create strong visual impact and brand distinctiveness.

### Times — Times — detected in extracted data but not described by AI · `--font-times`
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.2
- **Role:** Times — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.5 | 0.02px | `--text-caption` |
| body | 14px | 1.5 | -0.02px | `--text-body` |
| subheading | 24px | 1.3 | -0.01px | `--text-subheading` |
| heading | 38px | 1.2 | -0.01px | `--text-heading` |
| heading-lg | 56px | 1.1 | -0.01px | `--text-heading-lg` |
| display | 68px | 1.1 | -0.01px | `--text-display` |

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
| 80 | 80px | `--spacing-80` |
| 88 | 88px | `--spacing-88` |
| 96 | 96px | `--spacing-96` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 6px |
| pills | 80px |
| buttons | 6px |
| default | 6px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| sm | `rgba(0, 0, 0, 0.16) 0px 2px 6px 0px` | `--shadow-sm` |

### Layout

- **Section gap:** 80px
- **Card padding:** 16px
- **Element gap:** 16px

## Components

### Primary Action Button
**Role:** Filled call to action

Electric Blue background with Ink Black text, rectangular shape for bold interaction. Uses #004dff background, #000000 text, and 6px border-radius. Padding is 16px around.

### Ghost Button
**Role:** Call to action variant

Transparent background with Ink Black text, outlined by Storm Gray. Used for secondary actions, allowing primary content to dominate. Uses #000000 text, #e5e7eb border, with 16px padding.

### Navigation Link
**Role:** Header and footer navigation

Ink Black text on a Canvas White background. Hover states are implied by text color change or subtle underlines. Uses PP Radio Grotesk, 16px, 400 weight.

### Detail Card
**Role:** Informational container

Canvas White background with 6px border-radius. No explicit border, relies on surrounding contrast for definition. Padding of 16px horizontally. Shares same background as page.

### Input Field
**Role:** User entry fields

Transparent background for text input, with Ink Black text. Defined by implicit context rather than explicit borders. Placeholder or label text in Ink Black. Padding 12px horizontal, 16px bottom.

### Pill Badge
**Role:** Categorization or status label

Rounded badge with a tight radius. Transparent background with Ink Black text. Primarily used for small labels or tags, with 80px border-radius to create a pill shape.

## Do's and Don'ts

### Do
- Adhere to the high contrast between Ink Black (#000000) and Canvas White (#ffffff) for primary text and backgrounds.
- Use Electric Blue (#004dff) exclusively for primary calls to action, active states, and critical brand accents.
- Apply Storm Gray (#e5e7eb) for subtle borders, dividers, and background elements to maintain a clean aesthetic.
- Utilize PP Radio Grotesk for all headlines and significant textual emphasis to maintain brand voice and crispness.
- Ensure interactive elements such as buttons and links use a 6px border-radius for a consistent, subtle rounding.
- Maintain a clear page hierarchy by using the largest PP Radio Grotesk sizes for section titles, stepping down to Inter for body copies.
- Employ the rgba(0, 0, 0, 0.16) 0px 2px 6px 0px shadow selectively for interactive links to signify depth without clutter.

### Don't
- Avoid introducing additional saturated colors unless for semantic feedback (success/error) explicitly defined elsewhere.
- Do not use shadows on non-interactive elements or widespread across the page; keep surfaces flat for a modern feel.
- Refrain from using overly decorative fonts; stick to Inter for readability and PP Radio Grotesk for impact.
- Do not vary border-radius values beyond the specified 6px and 80px; consistency in shape is crucial.
- Avoid dense sections of content without adequate Storm Gray (#e5e7eb) dividers or Canvas White (#ffffff) breathing room.
- Do not use Electric Blue (#004dff) as a text color for general body copy or navigation, reserve it for actions.
- Do not use generic system fonts for headlines; PP Radio Grotesk is key to the brand's typographic identity.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas White | `#ffffff` | Primary page background and default surface for most content. |
| 1 | Muted Gray | `#dfdfdf` | Subtle background for UI elements like cards or sections, providing minimal visual separation. |

## Elevation

- **Interactive Link:** `rgba(0, 0, 0, 0.16) 0px 2px 6px 0px`

## Imagery

Imagery primarily consists of abstract 3D renders and stylized iconography, often using gradients of black, white, and Electric Blue, implying a complex, interconnected digital ecosystem. Product screenshots are minimal or non-existent, focusing instead on symbolic representations. Icons are generally outlined or filled in monochromatic tones with occasional brand color accents, maintaining a high-tech, minimalist aesthetic. The density is moderate to low, with visuals serving as decorative atmosphere or conceptual explanations rather than direct product showcases.

## Layout

The page layout is primarily full-bleed with content centered within a clear max-width, creating a structured yet expansive feel. The hero section often features a large, impactful headline over an abstract background graphic. Sections typically maintain consistent vertical spacing, often with alternating background shades implicit through subtle changes in neutral color usage or through the placement of visual elements. Content tends to be arranged in centered stacks or two-column text-left/visual-right patterns. A persistent top navigation bar provides site entry points. The rhythm is open and spacious, prioritizing visual impact and clarity.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #ffffff
border: #e5e7eb
accent: #004dff
primary action: #004dff (filled action)

Example Component Prompts:
1. Create a Primary Action Button: #004dff background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Design a clean Detail Card: #ffffff background, 6px radius, 16px horizontal padding, with a heading in PP Radio Grotesk 24px 500 weight #000000, and body text in Inter 14px 400 weight #000000.
3. Implement a Navigation Link: Inter 16px 400 weight #000000 text, with a subtle #e5e7eb underline on hover, 12px padding around icon and text if present.
4. Show a Pill Badge: Transparent background, 80px border-radius, Inter 12px 400 weight #000000 text, 4px vertical and 8px horizontal padding.
5. Create a Hero Headline: PP Radio Grotesk 68px 600 weight, #000000 color, line-height 1.1, letter-spacing -0.01em. Add a subtext of Inter 17px 400 weight, #000000, line-height 1.5, letter-spacing -0.02em.

## Similar Brands

- **Vercel** — High-contrast dark mode with crisp typography and subtle gradients for abstract visuals.
- **Linear** — Focus on extreme minimalism, precise typography, and a limited color palette with a single accent color for interaction.
- **Payload CMS** — Strong emphasis on black and white with programmatic gradients, often using a distinct mono-spaced typeface for code-like precision.
- **Supabase** — Clear, modern UI with high contrast, use of black and white, and vibrant accent colors to highlight key actions.
- **Plaid** — Clean, flat aesthetic, strong typography, and limited use of color to draw attention to interactive elements.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ink-black: #000000;
  --gradient-ink-black: linear-gradient(rgb(25, 25, 25), rgb(0, 0, 0));
  --color-storm-gray: #e5e7eb;
  --color-muted-gray: #dfdfdf;
  --color-whisper-gray: #c9c9c9;
  --color-dim-gray: #6e6e6e;
  --color-electric-blue: #004dff;
  --gradient-electric-blue: conic-gradient(from 206.55deg at 18.84% 51%, rgba(255, 255, 255, 0) -137.29deg, rgba(255, 255, 255, 0) 201.31deg, rgb(0, 77, 255) 197.22deg, rgb(217, 228, 255) 200.69deg, rgb(0, 77, 255) 201.02deg, rgb(0, 0, 0) 201.15deg, rgba(255, 255, 255, 0) 200.71deg, rgba(255, 255, 255, 0) 552.71deg);

  /* Typography — Font Families */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-pp-radio-grotesk: 'PP Radio Grotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-times: 'Times', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --tracking-caption: 0.02px;
  --text-body: 14px;
  --leading-body: 1.5;
  --tracking-body: -0.02px;
  --text-subheading: 24px;
  --leading-subheading: 1.3;
  --tracking-subheading: -0.01px;
  --text-heading: 38px;
  --leading-heading: 1.2;
  --tracking-heading: -0.01px;
  --text-heading-lg: 56px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.01px;
  --text-display: 68px;
  --leading-display: 1.1;
  --tracking-display: -0.01px;

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
  --spacing-80: 80px;
  --spacing-88: 88px;
  --spacing-96: 96px;

  /* Layout */
  --section-gap: 80px;
  --card-padding: 16px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-full: 60px;
  --radius-full-2: 80px;

  /* Named Radii */
  --radius-cards: 6px;
  --radius-pills: 80px;
  --radius-buttons: 6px;
  --radius-default: 6px;

  /* Shadows */
  --shadow-sm: rgba(0, 0, 0, 0.16) 0px 2px 6px 0px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-muted-gray: #dfdfdf;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ink-black: #000000;
  --color-storm-gray: #e5e7eb;
  --color-muted-gray: #dfdfdf;
  --color-whisper-gray: #c9c9c9;
  --color-dim-gray: #6e6e6e;
  --color-electric-blue: #004dff;

  /* Typography */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-pp-radio-grotesk: 'PP Radio Grotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-times: 'Times', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --tracking-caption: 0.02px;
  --text-body: 14px;
  --leading-body: 1.5;
  --tracking-body: -0.02px;
  --text-subheading: 24px;
  --leading-subheading: 1.3;
  --tracking-subheading: -0.01px;
  --text-heading: 38px;
  --leading-heading: 1.2;
  --tracking-heading: -0.01px;
  --text-heading-lg: 56px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.01px;
  --text-display: 68px;
  --leading-display: 1.1;
  --tracking-display: -0.01px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-88: 88px;
  --spacing-96: 96px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-full: 60px;
  --radius-full-2: 80px;

  /* Shadows */
  --shadow-sm: rgba(0, 0, 0, 0.16) 0px 2px 6px 0px;
}
```

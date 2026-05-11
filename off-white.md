# OFF WHITE — Style Reference
> Neon Glitch Arcade — stark black canvas with pixelated neon blocks.

**Theme:** dark

This design system conjures a digital arcade aesthetic, vibrant and deliberately chaotic. It layers a stark black canvas with an aggressive, highly saturated palette of neon 'glitch' green, 'warning' red, and 'digital' yellow, creating a high-contrast, attention-demanding visual rhythm. Text is predominantly rendered in stark black or white, with occasional use of a muted gray. The visual language is defined by the interplay of dense imagery and hard-edged blocks of vivid color, presenting a challenging, yet engaging, interface that resists traditional notions of 'clean' or 'minimal'.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Void | `#000000` | `--color-midnight-void` | Page background, primary text, button text, image borders. The overwhelming majority background, establishing a deep, dark foundation for the vivid accents |
| Ghost Canvas | `#ffffff` | `--color-ghost-canvas` | Accent backgrounds, secondary text, subtle borders. Provides stark contrast to Midnight Void |
| Muted Grey | `#aba4a4` | `--color-muted-grey` | Subtle accent text, decorative borders, low-key headings. Offers a softer contrast against the dominant dark background |
| Glitch Green | `#00fb34` | `--color-glitch-green` | Primary action background, interactive button text, link highlights, and significant decorative block accents. This color defines primary interactivity and visual disruption |
| Warning Red | `#ff0000` | `--color-warning-red` | Red outline accent for tags, dividers, and focused UI edges |
| Digital Yellow | `#fff500` | `--color-digital-yellow` | Yellow outline accent for tags, dividers, and focused UI edges |

## Tokens — Typography

### Offwhite — Primary brand typeface for all headlines, links, and buttons. Its wide range of sizes, including very large display sizes, allows for highly expressive and impactful typographic statements. · `--font-offwhite`
- **Substitute:** Arial Bold
- **Weights:** 400, 600, 700
- **Sizes:** 11px, 18px, 20px, 36px, 38px, 42px, 48px, 56px, 72px, 96px, 180px, 500px
- **Line height:** 1.00, 1.10, 1.15, 1.19, 1.25, 1.30, 1.31, 1.35, 1.40, 1.45, 1.54, 1.55, 1.56
- **Role:** Primary brand typeface for all headlines, links, and buttons. Its wide range of sizes, including very large display sizes, allows for highly expressive and impactful typographic statements.

### Times — Supplemental text, body copy, and longer content blocks where a traditional, readable serif is desired to contrast with the Offwhite brand font. · `--font-times`
- **Substitute:** Times New Roman
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.20
- **Role:** Supplemental text, body copy, and longer content blocks where a traditional, readable serif is desired to contrast with the Offwhite brand font.

### Arial — Used for small, functional text within buttons or secondary UI elements. Chosen for its system availability and compact footprint for supporting details. · `--font-arial`
- **Substitute:** Helvetica
- **Weights:** 400
- **Sizes:** 13px
- **Line height:** 1.20
- **Role:** Used for small, functional text within buttons or secondary UI elements. Chosen for its system availability and compact footprint for supporting details.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 11px | 1.31 | — | `--text-caption` |
| body-sm | 18px | 1.31 | — | `--text-body-sm` |
| body | 36px | 1.3 | — | `--text-body` |
| body-lg | 38px | 1.3 | — | `--text-body-lg` |
| heading-sm | 48px | 1.3 | — | `--text-heading-sm` |
| heading | 56px | 1.3 | — | `--text-heading` |
| heading-lg | 72px | 1.3 | — | `--text-heading-lg` |
| display-sm | 180px | 1.3 | — | `--text-display-sm` |
| display | 500px | 1.3 | — | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 6px

**Density:** spacious

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 40 | 40px | `--spacing-40` |
| 60 | 60px | `--spacing-60` |
| 90 | 90px | `--spacing-90` |
| 120 | 120px | `--spacing-120` |

### Border Radius

| Element | Value |
|---------|-------|
| links | 30px |
| buttons | 30px |

### Layout

- **Section gap:** 60-120px
- **Card padding:** 0px
- **Element gap:** 40px

## Components

### Ghost Brand Button
**Role:** Interactive element

Transparent background with text in Glitch Green (#00fb34) and a 30px border-radius, emphasizing a 'ghost' or 'outlined' interaction style.

### Filled Brand Button
**Role:** Primary action

Filled with Glitch Green (#00fb34) background and Midnight Void (#000000) text, with 0px border-radius. This button variant commands immediate attention for primary actions.

### Rounded Link
**Role:** Navigation or secondary interaction

Text in Glitch Green (#00fb34) on a transparent background, with a 30px border-radius, visually aligning with Ghost Brand Buttons for a consistent interactive feel.

### Hero Headline Text Block
**Role:** Primary page title

Large text in Offwhite font, variable size up to 500px, color Midnight Void (#000000) or Glitch Green (#00fb34), with a text border in Warning Red (#ff0000).

### Image Collage Block
**Role:** Content display

Images with a 1px solid Midnight Void (#000000) border, arranged in a dense, overlapping collage style, often framing or breaking up text content. No specific radius is applied to the images themselves beyond their cut-out shape.

## Do's and Don'ts

### Do
- Always use Midnight Void (#000000) as the default page background to maintain the stark, dark canvas.
- Utilize Glitch Green (#00fb34) for all primary interactive elements such as buttons and active links.
- Apply a 30px border-radius only to Ghost Brand Buttons and Rounded Links, no other UI elements.
- When using typography, prioritize the Offwhite font for all headings and brand text, with Times/Arial reserved for body/small functional text.
- Emphasize content through high-contrast color pairings, specifically Glitch Green on Midnight Void, or Warning Red as a highlight against Midnight Void.
- Employ the image collage pattern with Midnight Void (#000000) image borders to break vertical rhythm and add visual density.
- Maintain a spacious density for sections, using 60px or 90px paddingTop and 40px padding for element gaps.

### Don't
- Do not use subtle shadows or gradients; all visual elements should have hard edges and solid color fills.
- Avoid using Glitch Green (#00fb34), Warning Red (#ff0000), or Digital Yellow (#fff500) for large, static decorative backgrounds; their impact is in their high-contrast disruption.
- Do not introduce additional border-radius values beyond 0px and 30px (for specific interactive elements).
- Do not rely solely on system fonts; the custom 'Offwhite' font is crucial for brand identity and visual impact.
- Avoid standard grid layouts for imagery; instead, prefer a dense, overlapping collage or staggered arrangement.
- Do not use subtle or low-contrast text colors; the palette demands strong contrast (e.g., Midnight Void on Glitch Green, Ghost Canvas on Midnight Void).
- Never use generic spacing that creates unintended visual breathing room; adhere to the specified 40px, 60px, 90px, 120px values as defined.

## Imagery

The visual language is dominated by highly treated photography, almost exclusively tight crops of a single individual. The images are contained within rectangular containers, often overlapping or arranged in a dense, 'glitchy' collage pattern against a black background. There are no smooth transitions; images are abruptly cut and bordered with a 1px solid Midnight Void (#000000) line or the vivid brand accent colors. This creates a raw, fragmented, and somewhat aggressive visual density. Imagery's role is primarily decorative atmosphere and brand identity showcase, rather than explanatory content.

## Layout

The page adheres to a full-bleed layout, maximizing the screen width without a defined pageMaxWidth. The hero section features a dominant, central headline typography in an oversized custom font, surrounded by the image collage. Content arrangement alternates between dense, overlapping photographic blocks and large, blocky text elements that break normal flow. Vertical rhythm is established by section gaps ranging from 60px to 120px, with no subtle dividers. Navigation is minimal, a hamburger menu icon, suggesting an intentional resistance to conventional, easily discoverable navigation. The overall density is high, with design elements frequently overlapping.

## Agent Prompt Guide

primary action: #00fb34 (filled action)
Create a Primary Action Button: #00fb34 background, #000000 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-void: #000000;
  --color-ghost-canvas: #ffffff;
  --color-muted-grey: #aba4a4;
  --color-glitch-green: #00fb34;
  --color-warning-red: #ff0000;
  --color-digital-yellow: #fff500;

  /* Typography — Font Families */
  --font-offwhite: 'Offwhite', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-times: 'Times', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.31;
  --text-body-sm: 18px;
  --leading-body-sm: 1.31;
  --text-body: 36px;
  --leading-body: 1.3;
  --text-body-lg: 38px;
  --leading-body-lg: 1.3;
  --text-heading-sm: 48px;
  --leading-heading-sm: 1.3;
  --text-heading: 56px;
  --leading-heading: 1.3;
  --text-heading-lg: 72px;
  --leading-heading-lg: 1.3;
  --text-display-sm: 180px;
  --leading-display-sm: 1.3;
  --text-display: 500px;
  --leading-display: 1.3;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 6px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-90: 90px;
  --spacing-120: 120px;

  /* Layout */
  --section-gap: 60-120px;
  --card-padding: 0px;
  --element-gap: 40px;

  /* Border Radius */
  --radius-3xl: 30px;

  /* Named Radii */
  --radius-links: 30px;
  --radius-buttons: 30px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-void: #000000;
  --color-ghost-canvas: #ffffff;
  --color-muted-grey: #aba4a4;
  --color-glitch-green: #00fb34;
  --color-warning-red: #ff0000;
  --color-digital-yellow: #fff500;

  /* Typography */
  --font-offwhite: 'Offwhite', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-times: 'Times', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.31;
  --text-body-sm: 18px;
  --leading-body-sm: 1.31;
  --text-body: 36px;
  --leading-body: 1.3;
  --text-body-lg: 38px;
  --leading-body-lg: 1.3;
  --text-heading-sm: 48px;
  --leading-heading-sm: 1.3;
  --text-heading: 56px;
  --leading-heading: 1.3;
  --text-heading-lg: 72px;
  --leading-heading-lg: 1.3;
  --text-display-sm: 180px;
  --leading-display-sm: 1.3;
  --text-display: 500px;
  --leading-display: 1.3;

  /* Spacing */
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-90: 90px;
  --spacing-120: 120px;

  /* Border Radius */
  --radius-3xl: 30px;
}
```

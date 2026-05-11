# Pastel — Style Reference
> Architectural Blueprint on White Marble. The layout is structured and precise, rendered in a palette that feels both clean and substantial.

**Theme:** light

Pastel's design evokes a sense of clarity and understated reliability, like a well-organized workspace. It achieves this through a predominantly achromatic palette anchored by soft grays and a single, vibrant blue accent. Typography is clean and highly legible, using distinct font sizes and weights for clear hierarchy without visual clutter. The generous spacing and subtle use of rounded corners contribute to an open, approachable feel, giving content room to breathe.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#111111` | `--color-midnight-ink` | Primary text, deep neutrals for headings and core information, providing strong contrast. |
| Storm Gray | `#222222` | `--color-storm-gray` | Secondary text, subheadings, and borders, a slightly softer shade for supporting content. |
| Ghost White | `#f5f5f4` | `--color-ghost-white` | Page backgrounds and primary surface areas, creating a bright and airy canvas. |
| Cloud Cover | `#e6e3e2` | `--color-cloud-cover` | Subtle distinctions between sections and very light backgrounds, used for visual separation. |
| Deep Sea Blue | `#165dfb` | `--color-deep-sea-blue` | Primary calls to action, interactive elements, and key branding highlights, drawing immediate attention. |
| Whisper Gray | `#78716b` | `--color-whisper-gray` | Muted text, iconography, or subtle borders to convey secondary importance without disappearing. |
| Snow Drift | `#ffffff` | `--color-snow-drift` | Text on dark backgrounds, buttons, and other elements requiring high contrast against a saturated color. |

## Tokens — Typography

### Figtree — Primary typeface for all content including headings, body text, and interactive elements. Its clean, sans-serif lines provide excellent readability across all sizes and weights. · `--font-figtree`
- **Substitute:** Inter
- **Weights:** 400, 500, 600
- **Sizes:** 14px, 16px, 18px, 21px, 35px, 45px, 58px
- **Line height:** 1.00, 1.07, 1.10, 1.25, 1.29, 1.33, 1.37, 1.43, 1.50, 1.52, 1.70, 2.00
- **Letter spacing:** -0.0160em, -0.0140em
- **Role:** Primary typeface for all content including headings, body text, and interactive elements. Its clean, sans-serif lines provide excellent readability across all sizes and weights.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 14px | 1.5 | -0.22px | `--text-caption` |
| body | 16px | 1.43 | -0.22px | `--text-body` |
| subheading | 18px | 1.33 | -0.25px | `--text-subheading` |
| heading | 21px | 1.29 | -0.29px | `--text-heading` |
| heading-lg | 35px | 1.1 | -0.56px | `--text-heading-lg` |
| display | 58px | 1 | -0.93px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** spacious

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 6 | 6px | `--spacing-6` |
| 10 | 10px | `--spacing-10` |
| 11 | 11px | `--spacing-11` |
| 12 | 12px | `--spacing-12` |
| 20 | 20px | `--spacing-20` |
| 22 | 22px | `--spacing-22` |
| 30 | 30px | `--spacing-30` |
| 40 | 40px | `--spacing-40` |
| 43 | 43px | `--spacing-43` |
| 50 | 50px | `--spacing-50` |
| 56 | 56px | `--spacing-56` |
| 57 | 57px | `--spacing-57` |
| 58 | 58px | `--spacing-58` |
| 80 | 80px | `--spacing-80` |
| 100 | 100px | `--spacing-100` |
| 140 | 140px | `--spacing-140` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 4px |
| round | 120px |
| buttons | 10px |
| default | 8.8px |
| prominent | 15px |

### Layout

- **Card padding:** 0px

## Components

### Ghost Button
**Role:** Interactive element

Outline button with Midnight Ink text and transparent background. The 'Watch demo' button follows this, though its specific styling of border and background is not directly captured in the provided variant data, implies a transparent background and text color of #111111 or #222222 with a subtle border.

### Secondary Action Button
**Role:** Interactive element

Solid Storm Gray button with Snow Drift text. Used for less prominent actions or variations. Uses backgroundColor: #45403c, color: #ffffff (based on a variant with slightly darker gray). This button is likely an alternative, though the example provided uses #454745 for background and #ffffff text, for example 'Sign up' in header.

### Base Card (Implicit)
**Role:** Content container

Transparent background cards with no intrinsic border or shadow. Content takes precedence, often featuring embedded images or UI screenshots. Uses backgroundColor: rgba(0, 0, 0, 0), borderRadius: 0px, boxShadow: none, padding: 0px.

### Navigation Link
**Role:** Interactive element

Standard text link, typically Midnight Ink or Storm Gray. Hover states are implied, but not explicitly defined. On current page, often bolded. Uses color: #111111.

### Info Badge
**Role:** Categorization/metadata

Transparent background with text color matching surrounding content. Provides emphasis or classification for content blocks. Uses backgroundColor: rgba(0, 0, 0, 0), color: #111111, borderRadius: 0px, padding: 0px.

### Form Input (Implicit)
**Role:** Data entry

Although not explicitly detailed, the border colors #d1dee8 and #d7d3d1 suggest subtle, light gray borders for input fields to blend into the Ghost White background.

## Do's and Don'ts

### Do
- Prioritize Figtree font for all text elements to maintain a unified typographic voice.
- Use Deep Sea Blue (#165dfb) exclusively for primary calls to action and critical interactive elements.
- Maintain generous vertical spacing between sections, roughly 68-70px, to ensure content breathability.
- Apply a default border-radius of 8.8px for most interactive elements and images for a consistent, soft touch.
- Utilize Midnight Ink (#111111) as the primary text color on Ghost White (#f5f5f4) backgrounds for maximum legibility and contrast.

### Don't
- Avoid using highly saturated colors outside of the defined Deep Sea Blue accent, to preserve the clean, achromatic palette.
- Do not introduce sharp corners where a subtle 8.8px radius has been established for other elements, to prevent visual inconsistency.
- Refrain from heavy shadows or complex gradients; the system relies on flat colors and light surfaces for definition.
- Do not use small font sizes (below 14px) without clear necessity, as larger text is a hallmark of this system's readability.
- Avoid dense, information-packed sections without adequate spacing, as the system favors spaciousness over compactness.

## Imagery

The visual language of imagery on this site is primarily functional and demonstrative, featuring product screenshots and stylized UI mockups. These are presented either raw within card-like containers with no discernible borders, or as tight crops that showcase the product's interface. When photos are used, they are generally high-key, bright, and often feature muted color palettes to avoid distracting from the core UI. Icons are typically solid, monochromatic, and simple, serving a direct communicative purpose. Imagery's role is explanatory content and product showcase, with a moderate density, allowing text to remain dominant.

## Layout

The page exhibits a max-width contained layout, with content centered within a clear visual boundary. The hero section is full-width with a light background and a centered, prominent headline, followed by a left-aligned block of text, quote, and calls to action. Section rhythm is marked by consistent vertical spacing, creating distinct content blocks without heavy visual dividers. Content arrangement often employs a stacked, centered approach for headings and subtext, with multi-column card grids (likely 4-column based on screenshots) for features and testimonials. The layout is very spacious, providing ample breathing room around all elements. Navigation is a sticky top bar with clearly delineated logo, links, and action buttons.

## Agent Prompt Guide

### Quick Color Reference
- Text (Midnight Ink): `#111111`
- Background (Ghost White): `#f5f5f4`
- CTA (Deep Sea Blue): `#165dfb`
- Border (Cloud Cover): `#e6e3e2`
- Accent (Snow Drift): `#ffffff`

### 3-5 Example Component Prompts
1. **Create a hero section**: background `#f5f5f4`. Primary headline 'Get feedback directly on your website' in Figtree weight 600, size 58px, line-height 1.0, letter-spacing -0.93px, color `#111111`. Subtext '"Our clients love how they can just drop comments"' in Figtree weight 400, size 21px, line-height 1.29, letter-spacing -0.29px, color `#111111`. Primary button 'Start a free trial': background `#165dfb`, text `#ffffff`, radius 10px, padding 11px 22px.
2. **Generate a feature card**: square aspect ratio. Inner content can be a product screenshot or bold image. No visible border or shadow. Padding 0. Background transparent. Text for title 'Live Webflow Website' in Figtree weight 500, size 18px, line-height 1.33, letter-spacing -0.25px, color `#111111`.
3. **Design a navigation bar**: background `#ffffff`. Logo on left. Links (Features, Case Studies, Blog, Pricing) in Figtree weight 400, size 16px, line-height 1.5, color `#111111`. Login button as text link, Sign up button as solid '#45403c' with '#ffffff' text, 10px radius, padding 11px 16px.
4. **Create a testimonial section**: Background `#e6e3e2`. Quote text '"Trusted by fast moving agencies..."' in Figtree weight 600, size 35px, line-height 1.1, letter-spacing -0.56px, color `#111111`. Attribution 'Caio Nogueira' in Figtree weight 500, size 16px, line-height 1.5, color '#111111'.

## Similar Brands

- **Linear** — Shares a precise, almost clinical aesthetic with a strong emphasis on functional typography and restrained use of color against a clean, light background.
- **Framer** — Exhibits similar characteristics regarding generous whitespace, minimal adornment, and a clear hierarchy driven by typographic scale, allowing content to take center stage.
- **Vercel** — Utilizes a clean, high-contrast, text-dominant interface with strong focus on legibility and a primary accent color for calls to action, much like Pastel.
- **Webflow** — Features a light, open design with well-defined content blocks and a reliance on sans-serif typography for a modern, approachable feel.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #111111;
  --color-storm-gray: #222222;
  --color-ghost-white: #f5f5f4;
  --color-cloud-cover: #e6e3e2;
  --color-deep-sea-blue: #165dfb;
  --color-whisper-gray: #78716b;
  --color-snow-drift: #ffffff;

  /* Typography — Font Families */
  --font-figtree: 'Figtree', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.5;
  --tracking-caption: -0.22px;
  --text-body: 16px;
  --leading-body: 1.43;
  --tracking-body: -0.22px;
  --text-subheading: 18px;
  --leading-subheading: 1.33;
  --tracking-subheading: -0.25px;
  --text-heading: 21px;
  --leading-heading: 1.29;
  --tracking-heading: -0.29px;
  --text-heading-lg: 35px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.56px;
  --text-display: 58px;
  --leading-display: 1;
  --tracking-display: -0.93px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;

  /* Spacing */
  --spacing-6: 6px;
  --spacing-10: 10px;
  --spacing-11: 11px;
  --spacing-12: 12px;
  --spacing-20: 20px;
  --spacing-22: 22px;
  --spacing-30: 30px;
  --spacing-40: 40px;
  --spacing-43: 43px;
  --spacing-50: 50px;
  --spacing-56: 56px;
  --spacing-57: 57px;
  --spacing-58: 58px;
  --spacing-80: 80px;
  --spacing-100: 100px;
  --spacing-140: 140px;

  /* Layout */
  --card-padding: 0px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8.8px;
  --radius-xl: 15px;
  --radius-full: 120px;

  /* Named Radii */
  --radius-tags: 4px;
  --radius-round: 120px;
  --radius-buttons: 10px;
  --radius-default: 8.8px;
  --radius-prominent: 15px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #111111;
  --color-storm-gray: #222222;
  --color-ghost-white: #f5f5f4;
  --color-cloud-cover: #e6e3e2;
  --color-deep-sea-blue: #165dfb;
  --color-whisper-gray: #78716b;
  --color-snow-drift: #ffffff;

  /* Typography */
  --font-figtree: 'Figtree', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.5;
  --tracking-caption: -0.22px;
  --text-body: 16px;
  --leading-body: 1.43;
  --tracking-body: -0.22px;
  --text-subheading: 18px;
  --leading-subheading: 1.33;
  --tracking-subheading: -0.25px;
  --text-heading: 21px;
  --leading-heading: 1.29;
  --tracking-heading: -0.29px;
  --text-heading-lg: 35px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.56px;
  --text-display: 58px;
  --leading-display: 1;
  --tracking-display: -0.93px;

  /* Spacing */
  --spacing-6: 6px;
  --spacing-10: 10px;
  --spacing-11: 11px;
  --spacing-12: 12px;
  --spacing-20: 20px;
  --spacing-22: 22px;
  --spacing-30: 30px;
  --spacing-40: 40px;
  --spacing-43: 43px;
  --spacing-50: 50px;
  --spacing-56: 56px;
  --spacing-57: 57px;
  --spacing-58: 58px;
  --spacing-80: 80px;
  --spacing-100: 100px;
  --spacing-140: 140px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8.8px;
  --radius-xl: 15px;
  --radius-full: 120px;
}
```

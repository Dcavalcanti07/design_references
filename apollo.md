# Apollo — Style Reference
> Yellow-green spotlight on warm concrete.

**Theme:** light

Apollo presents a refined, almost austere, sales platform aesthetic. It combines a warm off-white canvas with stark black typography and a single, vibrant yellow-green accent that acts as a beacon for primary actions. Surfaces are clean and unblemished, focusing user attention on content and functionality, complemented by subtle, tactile border treatments rather than heavy shadows. The overall impression is one of grounded efficiency and direct communication.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas | `#f7f5f2` | `--color-canvas` | Primary page background, elevated neutral surfaces, ghost button backgrounds |
| Subtle Gray | `#e5e7eb` | `--color-subtle-gray` | Divider lines, subtle borders for cards and inputs, background for subtle UI elements |
| Ash Gray | `#ccc9c6` | `--color-ash-gray` | Section backgrounds, nav bar background, footer background — a distinct, slightly darker neutral surface |
| Midnight Ink | `#000000` | `--color-midnight-ink` | Primary text, main headings, default button text, strong borders |
| Graphite | `#1a1a1a` | `--color-graphite` | Input text, certain body text, slightly softer than Midnight Ink for secondary textual emphasis |
| Charcoal Text | `#47423d` | `--color-charcoal-text` | Body text for slightly muted or less prominent information, decorative icon fills |
| Faded Stone | `#736f6c` | `--color-faded-stone` | Subtle body text for small print or less important information, ghost button text |
| Soft Stone | `#94918e` | `--color-soft-stone` | Hairline borders, very subtle dividers |
| Crisp White | `#ffffff` | `--color-crisp-white` | Card backgrounds, selected UI elements, active text against dark backgrounds |
| Apollo Gold | `#ebf212` | `--color-apollo-gold` | Primary action buttons, prominent interactive elements. This vivid yellow-green is the system's singular accent |
| Accent Green | `#f8ff2c` | `--color-accent-green` | Decorative fills and backgrounds, secondary UI highlights — a slightly brighter shade of the primary accent |
| Violet Headline | `#3f3653` | `--color-violet-headline` | Specific number-based headlines, providing a unique, muted visual texture |

## Tokens — Typography

### Season Mix — Display and marketing headlines – a semi-bold custom font with tight tracking gives presence without shouting. · `--font-season-mix`
- **Substitute:** Montserrat
- **Weights:** 550
- **Sizes:** 48px, 56px, 64px, 72px, 88px
- **Line height:** 1.00, 1.05, 1.10
- **Letter spacing:** -0.0100em
- **Role:** Display and marketing headlines – a semi-bold custom font with tight tracking gives presence without shouting.

### Soehne — Primary body text, input fields, navigation links, and button labels – a precise, readable sans-serif with subtle positive tracking. · `--font-soehne`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 16px, 18px
- **Line height:** 1.00, 1.50
- **Letter spacing:** 0.0090em
- **Role:** Primary body text, input fields, navigation links, and button labels – a precise, readable sans-serif with subtle positive tracking.

### Abc Diatype — Secondary body text, smaller labels, and bolded elements – a compact sans-serif with tight negative tracking, complementing Soehne with a more condensed feel. · `--font-abc-diatype`
- **Substitute:** Roboto Condensed
- **Weights:** 400, 700
- **Sizes:** 12px, 14px, 16px, 20px, 24px
- **Line height:** 1.20, 1.30
- **Letter spacing:** -0.0100em
- **Role:** Secondary body text, smaller labels, and bolded elements – a compact sans-serif with tight negative tracking, complementing Soehne with a more condensed feel.

### Founders Grotesk Mono — Specific code-like or data-related text – provides a monospaced contrast and reinforces precision. · `--font-founders-grotesk-mono`
- **Substitute:** IBM Plex Mono
- **Weights:** 400
- **Sizes:** 12px, 14px
- **Line height:** 1.20
- **Letter spacing:** 0.0120em, 0.0140em
- **Role:** Specific code-like or data-related text – provides a monospaced contrast and reinforces precision.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 14.4 | 0.168px | `--text-caption` |
| body-sm | 14px | 16.8 | 0.196px | `--text-body-sm` |
| body | 16px | 24 | 0.144px | `--text-body` |
| body-lg | 18px | 18 | 0.162px | `--text-body-lg` |
| subheading | 20px | 24 | -0.2px | `--text-subheading` |
| heading | 24px | 28.8 | -0.24px | `--text-heading` |
| heading-lg | 48px | 50.4 | -0.48px | `--text-heading-lg` |
| display | 88px | 92.4 | -0.88px | `--text-display` |

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
| 56 | 56px | `--spacing-56` |
| 80 | 80px | `--spacing-80` |
| 96 | 96px | `--spacing-96` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 8px |
| image | 8px |
| inputs | 0px |
| buttons | 8px |
| default | 8px |
| smallCard | 12px |

### Layout

- **Section gap:** 40px
- **Card padding:** 24px
- **Element gap:** 8px

## Components

### Navigation Link
**Role:** Primary navigation links in header.

Text in Soehne, weight 400, size 16px, line height 1.00, charcoal text (#47423d). No background, no border.

### Primary Action Button
**Role:** Main call-to-action button.

Solid Apollo Gold (#ebf212) background, Midnight Ink (#000000) text (color #000000), 8px border-radius, 16px horizontal and optional 0px vertical padding. Soehne font at 16px weight 400.

### Secondary Action Button
**Role:** Outline style button for less prominent actions.

Transparent background, Midnight Ink (#000000) border and text (color #000000), 8px border-radius, 16px horizontal padding. Soehne font at 16px weight 400.

### Ghost Button
**Role:** Minimalist buttons for secondary or tertiary actions.

Transparent background, Faded Stone (#736f6c) text, no border. Border-radius 8px. Soehne font at 16px weight 400.

### Social Sign-Up Button
**Role:** Buttons for third-party authentication.

Canvas (#f7f5f2) background, Midnight Ink (#000000) text, Subtle Gray (#e5e7eb) border, 8px border-radius, with 24px horizontal and 32px vertical padding. Soehne font at 16px weight 400.

### Default Card
**Role:** Content presentation boxes.

Crisp White (#ffffff) background, no visible shadow, 8px border-radius, 24px padding.

### Elevated Card
**Role:** Accentuated content presentation boxes, often for feature lists.

Canvas (#f7f5f2) background, no visible shadow, 8px border-radius, 40px padding.

### Callout Card
**Role:** Special content blocks, often for testimonials or quotes.

Ash Gray (#ccc9c6) background, no visible shadow, 12px border-radius, with 0px padding, allowing for custom internal spacing.

### Text Input Field
**Role:** Standard user input fields.

Transparent background, Subtle Gray (#e5e7eb) bottom border, 0px border-radius. Graphite (#1a1a1a) text (color #1a1a1a) in Soehne font. 12px horizontal padding.

## Do's and Don'ts

### Do
- Use Ash Gray (#ccc9c6) for section backgrounds and navigation bars to provide discrete visual breaks.
- Apply Apollo Gold (#ebf212) exclusively to primary calls to action to maintain its impact and direct user focus.
- Set primary headings in Season Mix, weight 550, with tight letter spacing of -0.0100em for a powerful yet composed presence.
- Divide content using Subtle Gray (#e5e7eb) hairline borders or sections backgrounds rather than pronounced shadows or thick lines.
- Employ Soehne font for all body text and interactive elements, ensuring legibility with its specified letter spacing of 0.0090em.
- Frame all interactive elements and most content cards with an 8px border-radius for a consistent, soft edge.
- Utilize Crisp White (#ffffff) for card backgrounds against the off-white canvas to create subtle layering and separation.

### Don't
- Avoid arbitrary use of Accent Green (#f8ff2c); reserve it for decorative purposes or very specific highlights, not primary actions.
- Do not introduce additional bold or semibold weights for Soehne; its 400 weight is sufficient for the system's intended clarity.
- Refrain from using hard shadows; elevation should be achieved through background color shifts and subtle borders.
- Do not deviate from the established typography's letter spacing; the specific tracking is core to the brand's visual tone.
- Avoid full-bleed sections that extend edge-to-edge if they contain primary content; content should be comfortably within a defined width.
- Do not use multiple accent colors; Apollo Gold (#ebf212) should be the single vibrant highlight.
- Do not apply padding indiscriminately; follow the structured spacing tokens: 8px for minimal element gaps, 24px for card padding, and 40px for section gaps.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Canvas | `#f7f5f2` | Base page background and elevated neutral elements. |
| 2 | Primary Card Surface | `#ffffff` | Default card backgrounds, creating a subtle lift from the canvas. |
| 3 | Section Background | `#ccc9c6` | Distinct background for major content sections, navigation, and footer, providing clear visual segmentation. |

## Imagery

The site predominantly uses abstract, geometric illustration elements, often integrated as background texture or subtle decorative accents. Icons are monochrome, simple, and outlined, maintaining a lightweight feel. Product visuals are minimal, appearing as contained UI screenshots or simple illustrations when applicable. Photography is almost non-existent. The overall density of imagery is low, with visuals serving to punctuate textual content rather than dominate the layout.

## Layout

The page primarily uses a max-width centered container, but starts with a full-width header. The hero section features a centered headline over a background that transitions from the main canvas to a slightly darker Ash Gray, followed by a form with social sign-in options. Content sections alternate between the Canvas (#f7f5f2) and Ash Gray (#ccc9c6) backgrounds, creating a clear vertical rhythm. Content within these sections often appears in centered stacks or simple two-column text-left/image-right (or vice-versa) layouts. Navigation is a sticky top bar.

## Agent Prompt Guide

Quick Color Reference:
- text: #000000
- background: #f7f5f2
- border: #e5e7eb
- accent: #ebf212
- primary action: #ebf212 (filled action)

Example Component Prompts:
- Create a primary action button: Apollo Gold (#ebf212) background, Midnight Ink (#000000) text (color #000000), 8px border-radius, 16px horizontal padding. Soehne font at 16px weight 400.
- Generate a standard content card: Crisp White (#ffffff) background, 8px border-radius, 24px padding. Use Graphite (#1a1a1a) for body text and Abc Diatype (700) for subheadings.
- Design a text input field: Transparent background, Subtle Gray (#e5e7eb) bottom border (1px), 0px border-radius. Graphite (#1a1a1a) text (color #1a1a1a) in Soehne font, 12px horizontal padding.
- Build a secondary outline button: Transparent background, Midnight Ink (#000000) border and text, 8px border-radius, 16px horizontal padding. Soehne font at 16px weight 400.

## Similar Brands

- **Figma** — Clear structural layout, prominent use of a single vibrant accent color against a minimal, almost achromatic, background palette.
- **Linear** — Emphasis on crisp typography, subtle surface differentiation, and a focus on content over heavy decoration or complex branding.
- **Supabase** — Flat, modern UI with a strong emphasis on readability and functional use of color, often a single, distinctive accent hue.
- **Notion** — Clean, card-based layouts, focus on content organization, and a minimalist gray-scale base with limited, functional color accents.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas: #f7f5f2;
  --color-subtle-gray: #e5e7eb;
  --color-ash-gray: #ccc9c6;
  --color-midnight-ink: #000000;
  --color-graphite: #1a1a1a;
  --color-charcoal-text: #47423d;
  --color-faded-stone: #736f6c;
  --color-soft-stone: #94918e;
  --color-crisp-white: #ffffff;
  --color-apollo-gold: #ebf212;
  --color-accent-green: #f8ff2c;
  --color-violet-headline: #3f3653;

  /* Typography — Font Families */
  --font-season-mix: 'Season Mix', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-soehne: 'Soehne', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-abc-diatype: 'Abc Diatype', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-founders-grotesk-mono: 'Founders Grotesk Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 14.4;
  --tracking-caption: 0.168px;
  --text-body-sm: 14px;
  --leading-body-sm: 16.8;
  --tracking-body-sm: 0.196px;
  --text-body: 16px;
  --leading-body: 24;
  --tracking-body: 0.144px;
  --text-body-lg: 18px;
  --leading-body-lg: 18;
  --tracking-body-lg: 0.162px;
  --text-subheading: 20px;
  --leading-subheading: 24;
  --tracking-subheading: -0.2px;
  --text-heading: 24px;
  --leading-heading: 28.8;
  --tracking-heading: -0.24px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 50.4;
  --tracking-heading-lg: -0.48px;
  --text-display: 88px;
  --leading-display: 92.4;
  --tracking-display: -0.88px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-w550: 550;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-80: 80px;
  --spacing-96: 96px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 24px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;

  /* Named Radii */
  --radius-cards: 8px;
  --radius-image: 8px;
  --radius-inputs: 0px;
  --radius-buttons: 8px;
  --radius-default: 8px;
  --radius-smallcard: 12px;

  /* Surfaces */
  --surface-canvas: #f7f5f2;
  --surface-primary-card-surface: #ffffff;
  --surface-section-background: #ccc9c6;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas: #f7f5f2;
  --color-subtle-gray: #e5e7eb;
  --color-ash-gray: #ccc9c6;
  --color-midnight-ink: #000000;
  --color-graphite: #1a1a1a;
  --color-charcoal-text: #47423d;
  --color-faded-stone: #736f6c;
  --color-soft-stone: #94918e;
  --color-crisp-white: #ffffff;
  --color-apollo-gold: #ebf212;
  --color-accent-green: #f8ff2c;
  --color-violet-headline: #3f3653;

  /* Typography */
  --font-season-mix: 'Season Mix', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-soehne: 'Soehne', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-abc-diatype: 'Abc Diatype', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-founders-grotesk-mono: 'Founders Grotesk Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 14.4;
  --tracking-caption: 0.168px;
  --text-body-sm: 14px;
  --leading-body-sm: 16.8;
  --tracking-body-sm: 0.196px;
  --text-body: 16px;
  --leading-body: 24;
  --tracking-body: 0.144px;
  --text-body-lg: 18px;
  --leading-body-lg: 18;
  --tracking-body-lg: 0.162px;
  --text-subheading: 20px;
  --leading-subheading: 24;
  --tracking-subheading: -0.2px;
  --text-heading: 24px;
  --leading-heading: 28.8;
  --tracking-heading: -0.24px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 50.4;
  --tracking-heading-lg: -0.48px;
  --text-display: 88px;
  --leading-display: 92.4;
  --tracking-display: -0.88px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-80: 80px;
  --spacing-96: 96px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
}
```

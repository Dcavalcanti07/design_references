# Assurestor — Style Reference
> Deep green data console

**Theme:** dark

Assurestor employs a data-driven, dark-mode aesthetic, reminiscent of a command console. Dominant deep greens provide a rich, immersive canvas, contrasted by crisp white typography and a vibrant lime green that acts as a focal point for interactive elements and key information. Type is compact and assertive, supporting the structured, high-performance feel. Components are soft-edged against the dark background, emphasizing functionality over ornamentation.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Forest Canvas | `#203400` | `--color-forest-canvas` | Primary page background, prominent card surfaces, default button background in ghost states, some icon fills— a deep, verdant base that establishes the dark theme |
| Lime Accent | `#bdff00` | `--color-lime-accent` | Primary action buttons, active states, key highlight elements, table borders, and decorative accents— a vivid, high-contrast pop against the dark canvas |
| White Ozone | `#ffffff` | `--color-white-ozone` | All primary text, headings, navigation links, and internal button text— provides stark contrast against the dark backgrounds |
| Spruce Shadow | `#586740` | `--color-spruce-shadow` | Subtle borders and dividers for lists and other elements, offering soft visual separation within the green palette |
| Olive Card | `#335400` | `--color-olive-card` | Secondary card backgrounds, slightly lighter than the Forest Canvas to provide subtle layering |
| Deep Moss Card | `#1b2d00` | `--color-deep-moss-card` | Tertiary card backgrounds, providing the deepest surface level for content blocks or darker sections |
| Vivid Chartreuse | `#73a303` | `--color-vivid-chartreuse` | Minor decorative accents and specific table text, offering a slightly warmer green hue than the Lime Accent |

## Tokens — Typography

### Denim Ink — Primary font for all headings, body text, and UI elements. Its slightly condensed and robust appearance conveys a sense of technical precision and authority. · `--font-denim-ink`
- **Substitute:** Montserrat, system-ui
- **Weights:** 400, 600, 700
- **Sizes:** 16px, 20px, 32px, 40px, 64px, 86px, 94px
- **Line height:** 1.00, 1.10, 1.20, 1.30, 1.50
- **Letter spacing:** -0.0450em at 94px, -0.0220em at 86px, -0.0200em at 64px, normal at 16px
- **Role:** Primary font for all headings, body text, and UI elements. Its slightly condensed and robust appearance conveys a sense of technical precision and authority.

### courier new — Used for highly technical or code-like content, with extremely tight tracking to evoke a digital interface feel. · `--font-courier-new`
- **Substitute:** monospace
- **Weights:** 400
- **Sizes:** 8px
- **Line height:** 1.00
- **Letter spacing:** -0.1400em
- **Role:** Used for highly technical or code-like content, with extremely tight tracking to evoke a digital interface feel.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body-sm | 16px | 1.5 | — | `--text-body-sm` |
| body | 20px | 1.5 | — | `--text-body` |
| subheading | 32px | 1.2 | — | `--text-subheading` |
| heading | 40px | 1.2 | — | `--text-heading` |
| heading-lg | 64px | 1.1 | -1.28px | `--text-heading-lg` |
| display | 94px | 1 | -4.23px | `--text-display` |

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
| 72 | 72px | `--spacing-72` |
| 80 | 80px | `--spacing-80` |
| 120 | 120px | `--spacing-120` |
| 240 | 240px | `--spacing-240` |

### Border Radius

| Element | Value |
|---------|-------|
| pill | 9999px |
| cards | 32px |
| other | 12px |
| inputs | 0px |
| buttons | 16px |

### Layout

- **Section gap:** 24px
- **Card padding:** 32px
- **Element gap:** 24px

## Components

### Primary Action Button
**Role:** Filled action state

Rounded button with a vibrant Lime Accent background (#bdff00), Forest Canvas text (#203400), 16px border-radius, and 16px vertical, 32px horizontal padding. The highlight of interactive elements.

### Ghost Button
**Role:** Secondary action state

Transparent background with White Ozone text (#ffffff) and a 1px White Ozone border, 16px border-radius, and 16px vertical, 32px horizontal padding. Used for less prominent actions that remain visible on the dark canvas.

### Navigation Link
**Role:** Header and footer links

Text in White Ozone (#ffffff) with a transparent background. Underlined on hover. 0px border-radius without distinct padding, often appearing as raw text with interaction.

### Pill Button
**Role:** Tertiary action or filter tag

White Ozone background (#ffffff), Forest Canvas text (#203400), with a full radius (9999px) for a soft, rounded pill shape. 18px vertical and horizontal padding, used for login or contact buttons.

### Deep Moss Content Card
**Role:** Content container for primary information

Deep Moss Card background (#1b2d00), 32px border-radius, with 40px padding on all sides. Used for visually distinct feature blocks.

### Olive Content Card
**Role:** Secondary content container

Olive Card background (#335400), 32px border-radius, with no explicit padding (assumed content padding). Provides a slightly lighter surface variation.

### Lime Highlight Card
**Role:** Prominent feature or visual showcase

Lime Accent background (#bdff00), 32px border-radius, with no explicit padding. Used for high-impact visual elements that contain images or abstract graphics.

## Do's and Don'ts

### Do
- Use Forest Canvas (#203400) as the default background for all page sections and elevated component surfaces.
- Apply Lime Accent (#bdff00) exclusively for primary call-to-action fills, important interactive states, and small, functional accent details.
- Ensure all primary text, headings, and navigation elements use White Ozone (#ffffff) for maximum readability against dark backgrounds.
- Maintain a default border-radius of 32px for cards and larger containers, creating a softly rounded, approachable feel.
- Utilize Denim Ink for all primary typography, varying weights between 400, 600, and 700 to establish clear hierarchy without relying on different fonts.
- Implement 16px vertical and 32px horizontal padding for all primary and ghost buttons to ensure ample touch targets and visual balance.
- Use Deep Moss Card (#1b2d00) and Olive Card (#335400) for distinct visual layering of content blocks, moving from darker to slightly lighter as content elevates.

### Don't
- Avoid using White Ozone (#ffffff) as a background for large sections; reserve it for text or small interactive elements to maintain the dark theme.
- Do not introduce new vibrant colors outside of the Lime Accent (#bdff00) unless for semantic states (e.g., error, success), as this will dilute the brand's focused palette.
- Refrain from using hard, square edges; all major visual containers and interactive elements should follow the established border-radius values (32px, 16px, 9999px).
- Do not use generic system fonts for headings or body text where Denim Ink provides specific brand character; respect the tight tracking.
- Bypass heavy shadow effects; rely on color changes and slight background shifts to create hierarchy and separation between elements.
- Avoid padding buttons with less than 16px vertical and 32px horizontal space; compact buttons detract from the comfortable density.
- Do not use highly saturated brand colors for body copy or large text blocks; they should be reserved for accents or active states.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Forest Canvas | `#203400` | Base page background and default panel surface. |
| 2 | Deep Moss Card | `#1b2d00` | Slightly elevated content cards and sections that require a darker, more contained feel. |
| 3 | Olive Card | `#335400` | Secondary content cards, providing a subtle visual lift from the deepest moss background. |

## Imagery

The visual language for imagery is primarily abstract and technical, featuring neon-green digital patterns and graphics that echo data structures or networking. When present, product-like elements show clear, technical illustrations or stylized data representations, rather than photography. Icons are generally filled and in the Lime Accent color, contributing to the high-tech, 'command console' atmosphere. Imagery is not used for decorative atmosphere; it serves to visually explain or underscore technical concepts, often contained within cards or as part of large, impactful graphic elements. There is a strong graphic element ratio to text.

## Layout

The page uses a full-bleed layout with no explicit `pageMaxWidth`, allowing the dark canvas to extend edge-to-edge. Sections are separated by consistent vertical spacing of 24px. The hero features a centered headline and description over the Forest Canvas background, often accompanied by a large, circular, abstract graphic in Lime Accent. Subsequent content sections typically alternate between centered text blocks and a two-column layout with text on one side and a large, abstract graphic or stylized illustration on the other. Navigation is a sticky top bar with brand logo and text links, adopting a minimal approach.

## Agent Prompt Guide

Quick Color Reference:
text: #ffffff
background: #203400
border: #ffffff
accent: #bdff00
primary action: #bdff00 (filled action)

Example Component Prompts:
1. Create a Primary Action Button: #bdff00 background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Design a Deep Moss Content Card: Deep Moss Card background (#1b2d00), 32px border-radius, 40px all-around padding. Include a header using Denim Ink weight 600 at 40px size, White Ozone text (#ffffff).
3. Build a Ghost Button: Transparent background, White Ozone text (#ffffff), 1px White Ozone border, 16px border-radius, 16px vertical and 32px horizontal padding, Denim Ink weight 400.
4. Show a centered hero section with a display headline: Forest Canvas background (#203400), Display text using Denim Ink weight 700, 94px size, -0.0450em letter-spacing, White Ozone color (#ffffff). Below, a body-sm text using Denim Ink weight 400, 16px size, White Ozone color (#ffffff).
5. Create a Pill Button: White Ozone background (#ffffff), Forest Canvas text (#203400), Denim Ink weight 400, 18px vertical and horizontal padding, 9999px border-radius.

## Similar Brands

- **Datadog** — Dark-mode UI with high-contrast text and a single vivid accent color for interactive elements and data visualization.
- **Vercel** — Emphasis on dark backgrounds, clean typography, and a prominent, often neon, accent color to highlight key information and actions in a development-focused context.
- **Cloudflare** — Use of dark, technical backgrounds combined with sharp, functional typography and a distinct accent color to signify active states and critical information.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-forest-canvas: #203400;
  --color-lime-accent: #bdff00;
  --color-white-ozone: #ffffff;
  --color-spruce-shadow: #586740;
  --color-olive-card: #335400;
  --color-deep-moss-card: #1b2d00;
  --color-vivid-chartreuse: #73a303;

  /* Typography — Font Families */
  --font-denim-ink: 'Denim Ink', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-courier-new: 'courier new', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-sm: 16px;
  --leading-body-sm: 1.5;
  --text-body: 20px;
  --leading-body: 1.5;
  --text-subheading: 32px;
  --leading-subheading: 1.2;
  --text-heading: 40px;
  --leading-heading: 1.2;
  --text-heading-lg: 64px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -1.28px;
  --text-display: 94px;
  --leading-display: 1;
  --tracking-display: -4.23px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-120: 120px;
  --spacing-240: 240px;

  /* Layout */
  --section-gap: 24px;
  --card-padding: 32px;
  --element-gap: 24px;

  /* Border Radius */
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-pill: 9999px;
  --radius-cards: 32px;
  --radius-other: 12px;
  --radius-inputs: 0px;
  --radius-buttons: 16px;

  /* Surfaces */
  --surface-forest-canvas: #203400;
  --surface-deep-moss-card: #1b2d00;
  --surface-olive-card: #335400;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-forest-canvas: #203400;
  --color-lime-accent: #bdff00;
  --color-white-ozone: #ffffff;
  --color-spruce-shadow: #586740;
  --color-olive-card: #335400;
  --color-deep-moss-card: #1b2d00;
  --color-vivid-chartreuse: #73a303;

  /* Typography */
  --font-denim-ink: 'Denim Ink', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-courier-new: 'courier new', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-sm: 16px;
  --leading-body-sm: 1.5;
  --text-body: 20px;
  --leading-body: 1.5;
  --text-subheading: 32px;
  --leading-subheading: 1.2;
  --text-heading: 40px;
  --leading-heading: 1.2;
  --text-heading-lg: 64px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -1.28px;
  --text-display: 94px;
  --leading-display: 1;
  --tracking-display: -4.23px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-120: 120px;
  --spacing-240: 240px;

  /* Border Radius */
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;
  --radius-full: 9999px;
}
```

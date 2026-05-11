# Textla — Style Reference
> Rustic ledger, illustrated parchment

**Theme:** light

Textla's design system evokes a playful, handwritten, and slightly rustic aesthetic with a foundational palette of cheerful yellows and deep forest greens. Key elements are encased in organic, rounded shapes, often outlined with prominent strokes rather than filled. Textures feel paper-like, and typography is dense and characterful. The overall impression is informal but informative, aiming for approachability.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Forest Green | `#10380b` | `--color-forest-green` | Primary text, borders, iconography, and backgrounds for dark surface elements. This deep green grounds the playful palette |
| Buttermilk | `#f2ee98` | `--color-buttermilk` | Dominant page background, providing a warm, soft canvas. Also used for secondary informational cards and highlights |
| Sunshine Yellow | `#fce519` | `--color-sunshine-yellow` | Yellow state accent for badges, validation surfaces, and short status labels. Do not promote it to the primary CTA color |
| Parchment White | `#fefde6` | `--color-parchment-white` | Card backgrounds, input fields, and subtle foreground elements. Provides a slightly off-white, paper-like surface |
| Muted Sage | `#dbe8ac` | `--color-muted-sage` | Secondary card backgrounds and decorative fills, offering a softer variant of the brand's green hue |
| Vivid Mint | `#30be60` | `--color-vivid-mint` | Green outline accent for tags, dividers, and focused UI edges |
| Pure White | `#ffffff` | `--color-pure-white` | Foreground text on dark backgrounds and as an outline for some graphical elements |

## Tokens — Typography

### RethinkSans — Default text, links, smaller headings, and badge content. Its high contrast and legible form support utilitarian content. · `--font-rethinksans`
- **Substitute:** system-ui
- **Weights:** 600, 700, 800
- **Sizes:** 16px, 18px, 20px
- **Line height:** 1.00, 1.30, 1.33, 1.50, 1.60, 1.71
- **Letter spacing:** normal
- **Role:** Default text, links, smaller headings, and badge content. Its high contrast and legible form support utilitarian content.

### National 2 Condensed — Primary headings and display text. The condensed, tightly tracked nature creates a bold, impactful statement despite its many sizes. · `--font-national-2-condensed`
- **Substitute:** sans-serif
- **Weights:** 600, 700, 800
- **Sizes:** 16px, 18px, 20px, 24px, 32px, 40px, 48px, 56px, 64px, 86px, 104px, 156px, 180px
- **Line height:** 0.80, 1.00, 1.13, 1.30, 1.50, 1.67
- **Letter spacing:** -0.0300em
- **Role:** Primary headings and display text. The condensed, tightly tracked nature creates a bold, impactful statement despite its many sizes.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body | 16px | 1.5 | — | `--text-body` |
| subheading | 24px | 1.3 | -0.72px | `--text-subheading` |
| heading | 32px | 1.13 | -0.96px | `--text-heading` |
| heading-lg | 48px | 1 | -1.44px | `--text-heading-lg` |
| display | 86px | 0.8 | -2.58px | `--text-display` |

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
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 120 | 120px | `--spacing-120` |
| 160 | 160px | `--spacing-160` |

### Border Radius

| Element | Value |
|---------|-------|
| full | 1440px |
| cards | 40px |
| forms | 24px |
| elements | 16px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgb(16, 56, 11) 8px 8px 0px 0px` | `--shadow-subtle` |

### Layout

- **Section gap:** 40px
- **Card padding:** 24px
- **Element gap:** 24px

## Components

### Outlined Ghost Button
**Role:** Secondary action or navigation item, often paired with a filled button.

Background: transparent, Text: Forest Green (#10380b), Border: 1px solid Forest Green (#10380b), Radius: 1440px

### Primary Filled Button
**Role:** Main call-to-action button.

Background: Sunshine Yellow (#fce519), Text: Forest Green (#10380b), Radius: 1440px, Padding: 16px 24px

### Prominent Card
**Role:** Highlighted content container, often for testimonials or key data.

Background: Buttermilk (#f2ee98), Radius: 40px, Padding: 24px

### Informational Card
**Role:** General content grouping with a subtle background.

Background: Parchment White (#fefde6), Radius: 40px, Padding: 24px

### Primary Input Field
**Role:** User input for forms.

Background: Parchment White (#fefde6), Border: 1px solid Forest Green (#10380b), Radius: 1440px, Text: Forest Green (#10380b), Padding: 16px 24px

### Round Badge
**Role:** Small, functional label.

Background: Sunshine Yellow (#fce519 | no distinct background color for badge, using the general accent for visual consistency), Text: Forest Green (#10380b), Radius: 1440px (full pill shape).

### Headline Image with Shadow
**Role:** Visually striking images that add depth and a 'sticker' effect.

Border Radius: 40px, Box Shadow: Forest Green (#10380b) offset 8px 8px.

## Do's and Don'ts

### Do
- Use Forest Green (#10380b) for all primary text and critical borders.
- Apply Sunshine Yellow (#fce519) exclusively for primary action button backgrounds and focal accents.
- Implement the 1440px radius for all buttons, input fields, and small interactive elements to achieve a full pill shape.
- Ensure headings use National 2 Condensed font with its characteristic -0.0300em letter-spacing for a bold, distinctive look.
- Maintain a clear visual hierarchy by utilizing the 40px border radius for cards and prominent visual elements.
- Use a minimum of 24px of padding internally for cards and sections to ensure comfortable content spacing.
- Layer Muted Sage (#dbe8ac) over Buttermilk (#f2ee98) for card backgrounds to create subtle color variations within sections.

### Don't
- Do not use highly saturated colors for large background areas; reserve Buttermilk (#f2ee98) and Parchment White (#fefde6) for these.
- Avoid using a radius smaller than 16px for UI elements to maintain the system's organic, rounded aesthetic.
- Do not introduce new typefaces; rely solely on RethinkSans and National 2 Condensed.
- Avoid box shadows that are not a direct 8px offset with Forest Green (#10380b) as the color, as this is a signature visual element.
- Do not use Pure White (#ffffff) for primary text on light backgrounds; it is reserved for foreground elements on dark areas.
- Avoid complex gradients; the system relies on solid fills and outlined shapes.
- Do not deviate from the established spacing unit; consistently apply increments derived from the 8px base unit.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Page Canvas | `#f2ee98` | The foundational background for the entire page, providing a warm, soft base. |
| 1 | Base Card | `#fefde6` | General purpose card and input field background, offering a slightly lighter, off-white surface. |
| 2 | Accent Card | `#dbe8ac` | Secondary card background, adding a muted green variation for visual distinction. |

## Elevation

- **Image with pop:** `rgb(16, 56, 11) 8px 8px 0px 0px`

## Imagery

Imagery primarily consists of outlined, doodle-like vector illustrations featuring people and objects like parachutes, cacti, and coffee cups. These are organic in shape, often monochromatic or filled with brand colors, and blend seamlessly with the drawn border style of the UI elements. Product screenshots are contained within cards with rounded corners (40px radius) and sometimes feature an 8px x 8px offset shadow in Forest Green, giving them a sticker-like, layered appearance. Iconography is primarily outlined, using Forest Green for strokes. The overall density is balanced, with illustrations serving both decorative and explanatory roles without dominating the text.

## Layout

The page primarily uses a series of vertically stacked sections with consistent vertical spacing. Content is largely contained, although some elements like the hero background extend full-bleed. The hero section features a centered headline and supporting text over an illustrated background. Subsequent sections often alternate between text-dominant and visual-dominant arrangements, including a 2-column layout for text and an image, and a 3-column card grid for features. A full-width footer with large text elements provides calls to action. Navigation is a sticky top bar with left-aligned branding and right-aligned actions.

## Agent Prompt Guide

**Quick Color Reference**
text: #10380b
background: #f2ee98
border: #10380b
accent: #fce519
primary action: #10380b (filled action)

**3-5 Example Component Prompts**
1. Create a Primary Action Button: #10380b background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Design an informational card: background Parchment White (#fefde6), radius 40px, padding 24px, with a headline in National 2 Condensed at 32px weight 700 with letter-spacing -0.96px, Forest Green (#10380b) text.
3. Build an input field: background Parchment White (#fefde6), border 1px solid Forest Green (#10380b), radius 1440px, text Forest Green (#10380b), padding 16px 24px; include a placeholder in Forest Green (#10380b).
4. Create an outlined ghost button: background transparent, text Forest Green (#10380b), border 1px solid Forest Green (#10380b), radius 1440px.
5. Design a prominent card for review: background Buttermilk (#f2ee98), radius 40px, padding 24px, with a headline in RethinkSans at 20px weight 700, Forest Green (#10380b) text.

## Similar Brands

- **Beehiiv** — Features a similar playful, illustrative style with bold typography, and a limited, punchy color palette.
- **Mailchimp** — Uses custom, characterful illustrations and a distinctive, often condensed headline typeface, combined with a bright color accent.
- **Fathom Analytics** — Employs an illustrative, friendly aesthetic, with a focus on green and yellow tones for brand identity, and clean UI elements with rounded corners.
- **Klaviyo** — Known for a distinct brand color (green), which is prominently used for calls to action and branding, paired with clean typography.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-forest-green: #10380b;
  --color-buttermilk: #f2ee98;
  --color-sunshine-yellow: #fce519;
  --color-parchment-white: #fefde6;
  --color-muted-sage: #dbe8ac;
  --color-vivid-mint: #30be60;
  --color-pure-white: #ffffff;

  /* Typography — Font Families */
  --font-rethinksans: 'RethinkSans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-national-2-condensed: 'National 2 Condensed', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 24px;
  --leading-subheading: 1.3;
  --tracking-subheading: -0.72px;
  --text-heading: 32px;
  --leading-heading: 1.13;
  --tracking-heading: -0.96px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -1.44px;
  --text-display: 86px;
  --leading-display: 0.8;
  --tracking-display: -2.58px;

  /* Typography — Weights */
  --font-weight-semibold: 600;
  --font-weight-bold: 700;
  --font-weight-extrabold: 800;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-120: 120px;
  --spacing-160: 160px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 24px;
  --element-gap: 24px;

  /* Border Radius */
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-3xl-2: 40px;
  --radius-full: 1440px;

  /* Named Radii */
  --radius-full: 1440px;
  --radius-cards: 40px;
  --radius-forms: 24px;
  --radius-elements: 16px;

  /* Shadows */
  --shadow-subtle: rgb(16, 56, 11) 8px 8px 0px 0px;

  /* Surfaces */
  --surface-page-canvas: #f2ee98;
  --surface-base-card: #fefde6;
  --surface-accent-card: #dbe8ac;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-forest-green: #10380b;
  --color-buttermilk: #f2ee98;
  --color-sunshine-yellow: #fce519;
  --color-parchment-white: #fefde6;
  --color-muted-sage: #dbe8ac;
  --color-vivid-mint: #30be60;
  --color-pure-white: #ffffff;

  /* Typography */
  --font-rethinksans: 'RethinkSans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-national-2-condensed: 'National 2 Condensed', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 24px;
  --leading-subheading: 1.3;
  --tracking-subheading: -0.72px;
  --text-heading: 32px;
  --leading-heading: 1.13;
  --tracking-heading: -0.96px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -1.44px;
  --text-display: 86px;
  --leading-display: 0.8;
  --tracking-display: -2.58px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-120: 120px;
  --spacing-160: 160px;

  /* Border Radius */
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-3xl-2: 40px;
  --radius-full: 1440px;

  /* Shadows */
  --shadow-subtle: rgb(16, 56, 11) 8px 8px 0px 0px;
}
```

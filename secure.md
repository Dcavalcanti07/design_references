# Secure — Style Reference
> Soft rose + sharp violet — professional warmth.

**Theme:** light

Whereby blends a soft, friendly aesthetic with crisp, serious typography to create a sense of approachable professionalism. The subtle use of a pale rose background with deep violet accents softens the otherwise monochrome core, making video conferencing feel less sterile. Strategic pops of teal introduce vitality, particularly in areas signaling integration or positive outcomes, while overall structure relies on clean whites and grays, punctuated by precise typographic heirarchy, maintaining an efficient and trustworthy impression.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Graphite | `#000000` | `--color-midnight-graphite` | Primary text, critical UI elements, strong contrasts against light backgrounds. |
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card surfaces, primary content areas. |
| Whisper Gray | `#f4f4f4` | `--color-whisper-gray` | Subtle section dividers, secondary backgrounds, slight elevation. |
| Porcelain Gray | `#cccccc` | `--color-porcelain-gray` | Disabled button states, subtle borders. |
| Blush Rose | `#f8dbd5` | `--color-blush-rose` | Hero section background, adds a distinctive warm, soft touch to key promotional areas. |
| Whereby Violet | `#2b189b` | `--color-whereby-violet` | Primary call-to-action buttons, interactive elements, prominent headings — the main brand accent color. |
| Deep Plum | `#211375` | `--color-deep-plum` | Link states, secondary interactive elements, text elements requiring strong emphasis against lighter backgrounds. |
| Integrate Teal | `#006654` | `--color-integrate-teal` | Highlighting beneficial features, success indicators, elements related to ecosystem integration. |

## Tokens — Typography

### Inter — Body text, navigation items, secondary labels, used at 14px for fine print, 16px for body, 18px for larger body lead ins. Its slight letter-spacing reduction helps fit more content without feeling dense. · `--font-inter`
- **Substitute:** Inter
- **Weights:** 400, 500, 600
- **Sizes:** 14px, 16px, 18px
- **Line height:** 1.50
- **Letter spacing:** -0.028em
- **Role:** Body text, navigation items, secondary labels, used at 14px for fine print, 16px for body, 18px for larger body lead ins. Its slight letter-spacing reduction helps fit more content without feeling dense.

### Inter — Used for smaller emphasized text like navigation links and component labels, and specific content points. It provides a touch more presence than 400 weight. · `--font-inter`
- **Substitute:** Inter
- **Weights:** 400, 500, 600
- **Sizes:** 12px, 16px, 18px
- **Line height:** 1.0, 1.5
- **Letter spacing:** normal
- **Role:** Used for smaller emphasized text like navigation links and component labels, and specific content points. It provides a touch more presence than 400 weight.

### Inter — For strong emphasis in body copy or smaller headings, offering clear hierarchy without resorting to bolding entire paragraphs. · `--font-inter`
- **Substitute:** Inter
- **Weights:** 400, 500, 600
- **Sizes:** 14px
- **Line height:** 1.50
- **Letter spacing:** normal
- **Role:** For strong emphasis in body copy or smaller headings, offering clear hierarchy without resorting to bolding entire paragraphs.

### Whereby Roslindale Text Regular — Subheadings and section titles. This custom serif font adds a touch of classic sophistication, differentiating major content blocks from the modern sans-serif body. · `--font-whereby-roslindale-text-regular`
- **Substitute:** Playfair Display
- **Weights:** 400
- **Sizes:** 18px, 24px, 28px
- **Line height:** 1.25
- **Letter spacing:** normal
- **Role:** Subheadings and section titles. This custom serif font adds a touch of classic sophistication, differentiating major content blocks from the modern sans-serif body.

### Whereby Roslindale Display Condensed Regular — Primary display headlines. The condensed nature paired with a moderate 400 weight prevents it from feeling overpowering, allowing large text to be impactful yet elegant. The extreme negative letterSpacing at larger sizes is a distinctive brand choice requiring careful implementation. · `--font-whereby-roslindale-display-condensed-regular`
- **Substitute:** Playfair Display
- **Weights:** 400
- **Sizes:** 40px, 48px, 80px, 120px
- **Line height:** 1.15, 1.25
- **Letter spacing:** -10.0000em
- **Role:** Primary display headlines. The condensed nature paired with a moderate 400 weight prevents it from feeling overpowering, allowing large text to be impactful yet elegant. The extreme negative letterSpacing at larger sizes is a distinctive brand choice requiring careful implementation.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1 | — | `--text-caption` |
| body-sm | 14px | 1.5 | -0.448px | `--text-body-sm` |
| body | 16px | 1.5 | -0.448px | `--text-body` |
| subheading | 18px | 1.25 | — | `--text-subheading` |
| heading-sm | 24px | 1.25 | — | `--text-heading-sm` |
| heading | 28px | 1.25 | — | `--text-heading` |
| heading-lg | 40px | 1.15 | -40px | `--text-heading-lg` |
| display | 48px | 1.15 | -48px | `--text-display` |
| display-lg | 80px | 1.15 | -80px | `--text-display-lg` |
| display-xl | 120px | 1.25 | -120px | `--text-display-xl` |

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
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 88 | 88px | `--spacing-88` |
| 96 | 96px | `--spacing-96` |
| 160 | 160px | `--spacing-160` |

### Border Radius

| Element | Value |
|---------|-------|
| misc | 20px |
| cards | 12px |
| buttons | 40px |
| default | 12px |

### Layout

- **Section gap:** 64px
- **Card padding:** 24-40px
- **Element gap:** 8-24px

## Components

### Secondary Call-to-Action Button - Outlined
**Role:** Secondary action button (Log in)

Transparent background with a 1px border in 'Whereby Violet' (#2b189b) and 'Whereby Violet' text. 40px border-radius maintains the pill shape. Padding matches primary action buttons.

### Navigation Link
**Role:** Top navigation menu items

Default state uses 'Midnight Graphite' (#000000) for text with Inter 400 at 16px. No explicit backgrounds or borders, relying on spacing for separation. Hover/active states might introduce subtle underlining or color changes.

### Hero Section Content Block
**Role:** Information display

Content block within the hero section, background `Blush Rose` (#f8dbd5). Contains large headings (Whereby Roslindale Display Condensed Regular 80px), body text (Inter 18px), and a primary CTA button. No explicit border, relies on section background for visual grouping.

### Feature Card
**Role:** Detailed feature description

Card with a `Canvas White` background, 12px border radius, containing an image/video frame, a 'Whereby Roslindale Text Regular' heading (24px), Inter body text (18px), and a 'Whereby Violet' CTA button (pill-shaped, 40px radius). Uses 24px-40px padding.

### Highlight Section Container
**Role:** Section for emphasized content

Uses 'Whisper Gray' (#f4f4f4) as a background to subtly differentiate from the main 'Canvas White' sections. Typically contains a centered stack of elements, like a carousel or a specific product feature showcase, with padding of 64px vertical.

## Do's and Don'ts

### Do
- Use 'Whereby Violet' (#2b189b) exclusively for primary interactive elements, ensuring strong call-to-action visibility.
- Apply a 40px border-radius for all buttons, creating a consistent pill-shaped aesthetic.
- Employ 'Blush Rose' (#f8dbd5) sparingly for hero sections or key promotional areas to maintain its distinctive warm impact.
- Utilize 'Whereby Roslindale Display Condensed Regular' (400 weight) for all key headlines, implementing the negative letter-spacing for large text.
- Maintain a clear visual hierarchy by contrasting 'Whereby Roslindale Text Regular' 400 for subheadings with 'Inter' for body text.
- Ensure generous vertical spacing of 64px between major sections to provide visual breathing room.
- Use 'Integrate Teal' (#006654) only for indicators of success, integration points, or positive attributes.

### Don't
- Do not use highly saturated colors for backgrounds; reserve them for interactive elements or small accents.
- Avoid mixing 'Blush Rose' (#f8dbd5) with other chromatic background colors; it should stand as a distinct accent.
- Do not use pixel-perfect letter spacing if a font family has specified `em` values, use those for fidelity.
- Do not introduce additional sans-serif fonts; stick to the Inter family for all body and UI text.
- Avoid using border-radius values other than 12px, 20px, or 40px, unless for specific small form elements (4px).
- Do not apply drop shadows to elements; depth is primarily achieved through background color changes (e.g., 'Whisper Gray').
- Do not add additional visual ornamentation or gradients; the design relies on clean surfaces and strong typography.

## Imagery

The site's imagery features professional, mid-shot photography showing individuals engaged in focused work on laptops in bright, airy home or office settings. Images are often contained within softly rounded masks (12px-20px radius). There are also clean, product-focused screenshots of the video conferencing interface itself, framed as if on a desktop or mobile device. Icons are simple, filled, and largely monochrome or in 'Integrate Teal', serving an explanatory and illustrative role rather than purely decorative. Overall, visual density is moderate; imagery serves to illustrate or provide social proof, rather than completely dominate sections. The treatment is naturalistic with a slightly warm filter often present, matching the 'Blush Rose' accent.

## Layout

The layout primarily follows a max-width centered container model, though the hero section often uses a full-bleed background. The hero features a two-column split, with a large, condensed serif headline and text on the left, balanced by an image on the right, all against a 'Blush Rose' background. Subsequent sections often alternate between 'Canvas White' and 'Whisper Gray' backgrounds, maintaining a strong vertical rhythm with generous padding (64px). Content typically uses either a single-column stacked approach for text blocks or a two-column layout with text and image alternating sides. Feature sections frequently employ an adaptive grid for card-like elements. Navigation is a sticky top bar with brand logo, primary links, and distinct 'Log in' (outlined) and 'Sign up' (filled) buttons.

## Agent Prompt Guide

### Quick Color Reference
- Text: #000000
- Background: #ffffff
- CTA: #2b189b
- Border: #2b189b (for outlined buttons), #cccccc (for disabled)
- Accent: #006654

### 3-5 Example Component Prompts
1. **Create a Hero Section:** Full-width background: #f8dbd5. Left column: headline 'Whereby Roslindale Display Condensed Regular' 80px, weight 400, #000000, letter-spacing -80px; body text 'Inter' 18px, weight 400, #000000, line-height 1.5. Below body text, a button: 'Whereby Violet' (#2b189b) background, 'Canvas White' (#ffffff) text, 40px border-radius, 16px vertical padding, 40px horizontal padding.
2. **Generate a Feature Card:** Background: #ffffff, 12px border-radius. Headline 'Whereby Roslindale Text Regular' 24px, weight 400, #000000. Body text 'Inter' 16px, weight 400, #000000, line-height 1.5. Internal padding 40px. Include an image slot within the card, with a 12px border-radius.
3. **Design a Navigation Bar Button (Log in):** Text 'Log in', color #2b189b ('Whereby Violet'), 'Inter' 16px, weight 500. Transparent background, 1px border in #2b189b. Border-radius 40px. Padding 10px vertical, 24px horizontal.

## Similar Brands

- **Slack** — Uses monochrome base with a single vibrant brand color for CTA and key elements, similar to Whereby's 'Whereby Violet' focus.
- **Figma** — Employs clean, spacious layouts with a focus on functional typography and limited use of vibrant accents on interactive elements, much like Whereby's systematic use of color.
- **Notion** — Combines a system sans-serif for utility (Inter's role) with a distinct display serif for brand and impact, echoing Whereby's Inter + Roslindale typography pairing.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-graphite: #000000;
  --color-canvas-white: #ffffff;
  --color-whisper-gray: #f4f4f4;
  --color-porcelain-gray: #cccccc;
  --color-blush-rose: #f8dbd5;
  --color-whereby-violet: #2b189b;
  --color-deep-plum: #211375;
  --color-integrate-teal: #006654;

  /* Typography — Font Families */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-whereby-roslindale-text-regular: 'Whereby Roslindale Text Regular', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-whereby-roslindale-display-condensed-regular: 'Whereby Roslindale Display Condensed Regular', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --tracking-body-sm: -0.448px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.448px;
  --text-subheading: 18px;
  --leading-subheading: 1.25;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.25;
  --text-heading: 28px;
  --leading-heading: 1.25;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.15;
  --tracking-heading-lg: -40px;
  --text-display: 48px;
  --leading-display: 1.15;
  --tracking-display: -48px;
  --text-display-lg: 80px;
  --leading-display-lg: 1.15;
  --tracking-display-lg: -80px;
  --text-display-xl: 120px;
  --leading-display-xl: 1.25;
  --tracking-display-xl: -120px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-88: 88px;
  --spacing-96: 96px;
  --spacing-160: 160px;

  /* Layout */
  --section-gap: 64px;
  --card-padding: 24-40px;
  --element-gap: 8-24px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-xl: 12px;
  --radius-2xl: 20px;
  --radius-3xl: 40px;

  /* Named Radii */
  --radius-misc: 20px;
  --radius-cards: 12px;
  --radius-buttons: 40px;
  --radius-default: 12px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-graphite: #000000;
  --color-canvas-white: #ffffff;
  --color-whisper-gray: #f4f4f4;
  --color-porcelain-gray: #cccccc;
  --color-blush-rose: #f8dbd5;
  --color-whereby-violet: #2b189b;
  --color-deep-plum: #211375;
  --color-integrate-teal: #006654;

  /* Typography */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-whereby-roslindale-text-regular: 'Whereby Roslindale Text Regular', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-whereby-roslindale-display-condensed-regular: 'Whereby Roslindale Display Condensed Regular', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --tracking-body-sm: -0.448px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.448px;
  --text-subheading: 18px;
  --leading-subheading: 1.25;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.25;
  --text-heading: 28px;
  --leading-heading: 1.25;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.15;
  --tracking-heading-lg: -40px;
  --text-display: 48px;
  --leading-display: 1.15;
  --tracking-display: -48px;
  --text-display-lg: 80px;
  --leading-display-lg: 1.15;
  --tracking-display-lg: -80px;
  --text-display-xl: 120px;
  --leading-display-xl: 1.25;
  --tracking-display-xl: -120px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-88: 88px;
  --spacing-96: 96px;
  --spacing-160: 160px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-xl: 12px;
  --radius-2xl: 20px;
  --radius-3xl: 40px;
}
```

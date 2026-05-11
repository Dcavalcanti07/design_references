# (dot)connect — Style Reference
> High-contrast digital blueprint

**Theme:** light

(dot)connect employs a high-contrast, engineering-focused aesthetic, contrasting deep near-black text and accents against a warm off-white canvas. A vivid orange acts as a primary brand accent, injecting energy into a mostly minimalist layout. Typography is compact and precise, utilizing a custom sans-serif with subtle ligatures to convey a modern, technical authority.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#001011` | `--color-midnight-ink` | Primary text, button backgrounds, strong borders — establishes a deep, authoritative base |
| Goldenrod Orange | `#fd5321` | `--color-goldenrod-orange` | Orange wash for highlight backgrounds, decorative bands, and soft emphasis behind content. Do not promote it to the primary CTA color |
| Storm Gray | `#0f1e1f` | `--color-storm-gray` | Secondary text, muted borders, badge text — a slightly lighter, less dominant dark gray for supporting information |
| Accent Blue | `#007aff` | `--color-accent-blue` | Outlined button borders, button text, interactive accents — a vibrant technical blue for internal interactions |
| Vanilla Cream | `#fcfbf8` | `--color-vanilla-cream` | Page backgrounds, button text, icon surfaces — provides a warm, clean canvas |
| Ash Mist | `#c1c4c2` | `--color-ash-mist` | Subtle borders, dividers — a light gray creating soft visual separation |
| Parchment | `#ededea` | `--color-parchment` | Card backgrounds, secondary surface fills — a slightly darker off-white for layered content |

## Tokens — Typography

### AeonikPro — Used for all primary headings, body text, and interactive elements. Its condensed, precise forms contribute to the system's technical and direct tone. · `--font-aeonikpro`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400, 500
- **Sizes:** 16px, 18px, 21px, 24px, 32px, 36px, 72px, 101px
- **Line height:** 0.80, 0.90, 1.00, 1.10, 1.40, 1.50
- **Letter spacing:** -0.0250em to 0.0250em
- **OpenType features:** `"dlig", "ss02", "ss08"`
- **Role:** Used for all primary headings, body text, and interactive elements. Its condensed, precise forms contribute to the system's technical and direct tone.

### DotConnect — A secondary custom typeface used for specific display headings and emphasized text, providing a distinctive brand voice. · `--font-dotconnect`
- **Substitute:** system-ui, sans-serif
- **Weights:** 500
- **Sizes:** 19px, 24px, 36px, 73px
- **Line height:** 1.00, 1.10, 1.67
- **Letter spacing:** -0.0120em to 0.0100em
- **OpenType features:** `"dlig", "ss02", "ss08"`
- **Role:** A secondary custom typeface used for specific display headings and emphasized text, providing a distinctive brand voice.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 16px | 1.5 | 0.01px | `--text-caption` |
| body-sm | 18px | 1.4 | 0.01px | `--text-body-sm` |
| body | 21px | 1.4 | -0.012px | `--text-body` |
| subheading | 24px | 1.1 | -0.012px | `--text-subheading` |
| heading-sm | 32px | 1.1 | -0.02px | `--text-heading-sm` |
| heading | 36px | 1.1 | -0.02px | `--text-heading` |
| heading-lg | 72px | 0.9 | -0.025px | `--text-heading-lg` |
| display | 101px | 0.8 | -0.025px | `--text-display` |

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
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 72 | 72px | `--spacing-72` |
| 80 | 80px | `--spacing-80` |
| 96 | 96px | `--spacing-96` |
| 160 | 160px | `--spacing-160` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 20px |
| badges | 8px |
| buttons | 24px |
| decorative | 48px |

### Layout

- **Section gap:** 48px
- **Card padding:** 24px
- **Element gap:** 24px

## Components

### Filled Brand Button
**Role:** Primary call to action.

Background: Midnight Ink (#001011). Text: Vanilla Cream (#fcfbf8). Border radius: 24px. Padding: 13px vertical, 24px horizontal. Uses AeonikPro 16px. Example: 'more' button.

### Outlined Accent Button
**Role:** Secondary action or link.

Background: transparent. Border: 1px solid Accent Blue (#007aff). Text: Accent Blue (#007aff). Border radius: 24px. Padding: 13px vertical, 24px horizontal. Uses AeonikPro 16px. Example: 'let's connect' button.

### Offer Card
**Role:** Informational container for features or services.

Background: Parchment (#ededea). Border radius: 20px. Padding: 32px. Contains AeonikPro text and icons. No shadow.

### Small Feature Card
**Role:** Smaller informational containers, often in grids.

Background: Parchment (#ededea). Border radius: 12px. Padding: 24px. Contains AeonikPro text and potentially images. No shadow.

### Status Badge
**Role:** Small, informative labels.

Background: rgba(252, 251, 248, 0.8) (Vanilla Cream with transparency). Text: Storm Gray (#0f1e1f). Border radius: 8px. Padding: 4px vertical, 16px horizontal. Uses AeonikPro 16px.

### Navigation Link
**Role:** Top-level navigation items.

Text: Midnight Ink (#001011). Inactive state is no special background; active state is a thin underline implicitly defined by AeonikPro font features for `dlig`, `ss02`, `ss08`.

## Do's and Don'ts

### Do
- Use Midnight Ink (#001011) for all primary text and button backgrounds to maintain brand authority.
- Apply Goldenrod Orange (#fd5321) exclusively for primary call-to-action backgrounds and singular decorative accents.
- Ensure all interactive elements, like buttons and cards, use border radii from the specific list: buttons at 24px, cards at 20px, badges at 8px.
- Maintain a comfortable information density with horizontal and vertical element gaps set to 24px.
- Prioritize AeonikPro for all textual content, utilizing its specific weights (400, 500) and letter-spacing values to achieve precision.
- Use Parchment (#ededea) for card and secondary surface backgrounds, providing subtle layering against the Vanilla Cream (#fcfbf8) page background.
- Use Accent Blue (#007aff) only for outlined button borders and internal interactive text, not as a primary fill.

### Don't
- Do not introduce new primary background colors; maintain Vanilla Cream (#fcfbf8) as the dominant page canvas.
- Avoid using Goldenrod Orange (#fd5321) as a text color; reserve it for background fills and bold accents.
- Do not deviate from the specified border radii (e.g., 24px for buttons, 20px for cards); all corners must reflect these values.
- Do not use highly saturated colors for large UI areas; chromatic colors are for accents and specific interactive elements only.
- Avoid generic sans-serif fonts; AeonikPro and DotConnect provide the critical brand voice and typographic detail.
- Do not use drop shadows for cards or most UI elements; the design relies on flat surfaces and subtle background shifts for hierarchy.
- Do not apply excessive letter-spacing to body text; use the defined negative letter-spacing for headlines and display text to keep it tight.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Vanilla Cream | `#fcfbf8` | Primary page background |
| 1 | Parchment | `#ededea` | Card and secondary content backgrounds |
| 2 | Goldenrod Orange | `#fd5321` | Accent boxes and prominent content blocks |
| 3 | Midnight Ink | `#001011` | Action backgrounds and hero elements that need strong contrast |

## Imagery

The visual language features abstract, often data-driven 3D renders or stylized illustrations, like the glass brain or geometric shapes. Imagery is presented both contained within cards with rounded corners (20px radius) and as larger, more atmospheric background elements without hard edges. Icons are typically solid, using Midnight Ink or Accent Blue, and align with the sharp, technical aesthetic. Imagery aims to be conceptually explanatory and decorative rather than product-showcasing, focusing on creating a mood of innovation and deep tech.

## Layout

The site employs a primarily max-width 1200px contained layout, centered on the page. The hero section is full-bleed with a prominent, centered headline and subtext, often featuring atmospheric abstract graphics at the bottom. Sections maintain a consistent vertical rhythm with a 48px gap, alternating between the Vanilla Cream background and the slightly darker Parchment for cards. Content is generally arranged in centered stacks or two-column text-left/image-right configurations. Navigation is a simple sticky top bar with text links and a distinctive right-aligned action button.

## Agent Prompt Guide

Quick Color Reference:
text: #001011
background: #fcfbf8
border: #c1c4c2
accent: #007aff
primary action: #001011 (filled action)

Example Component Prompts:
1. Create a hero section with a centered headline: 'We are an engineering-driven company' using AeonikPro 72px weight 500, #001011, letter-spacing -0.025em, on a #fcfbf8 background. Below it, add a section description in AeonikPro 21px weight 400, #001011, letter-spacing -0.012em. Place a Filled Brand Button centered below the text.
2. Design an Offer Card: Parchment (#ededea) background, 20px border-radius, 32px padding on all sides. Inside, display a subheading in AeonikPro 24px weight 500, #001011, letter-spacing -0.012em, above body text in AeonikPro 18px weight 400, #0f1e1f.
3. Create an Outlined Accent Button: Transparent background, 1px solid Accent Blue (#007aff) border, 24px border-radius, AeonikPro 16px text in Accent Blue (#007aff), with 13px vertical and 24px horizontal padding. The text should say 'let's connect'.

## Similar Brands

- **Vercel** — High-contrast typography, deep darks against light backgrounds, and minimalist layouts focused on content delivery. Similar compact and precise type scale.
- **Supabase** — Technical aesthetic, strong use of a single accent color (green for Supabase, orange for dotconnect) for CTAs and highlights within a largely monochrome UI. Clean, geometric design.
- **Stripe** — Emphasis on clear typography, considered negative space, and a measured use of color for functional elements. Clean, modern, and business-focused visual identity.
- **Linear** — High information density within a structured, almost clinical, UI. Similar approach to subtle layering with different shades of off-white/gray, and precise typography.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #001011;
  --color-goldenrod-orange: #fd5321;
  --color-storm-gray: #0f1e1f;
  --color-accent-blue: #007aff;
  --color-vanilla-cream: #fcfbf8;
  --color-ash-mist: #c1c4c2;
  --color-parchment: #ededea;

  /* Typography — Font Families */
  --font-aeonikpro: 'AeonikPro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-dotconnect: 'DotConnect', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 16px;
  --leading-caption: 1.5;
  --tracking-caption: 0.01px;
  --text-body-sm: 18px;
  --leading-body-sm: 1.4;
  --tracking-body-sm: 0.01px;
  --text-body: 21px;
  --leading-body: 1.4;
  --tracking-body: -0.012px;
  --text-subheading: 24px;
  --leading-subheading: 1.1;
  --tracking-subheading: -0.012px;
  --text-heading-sm: 32px;
  --leading-heading-sm: 1.1;
  --tracking-heading-sm: -0.02px;
  --text-heading: 36px;
  --leading-heading: 1.1;
  --tracking-heading: -0.02px;
  --text-heading-lg: 72px;
  --leading-heading-lg: 0.9;
  --tracking-heading-lg: -0.025px;
  --text-display: 101px;
  --leading-display: 0.8;
  --tracking-display: -0.025px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-160: 160px;

  /* Layout */
  --section-gap: 48px;
  --card-padding: 24px;
  --element-gap: 24px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 28px;
  --radius-3xl-3: 36px;
  --radius-3xl-4: 44px;
  --radius-full: 48px;

  /* Named Radii */
  --radius-cards: 20px;
  --radius-badges: 8px;
  --radius-buttons: 24px;
  --radius-decorative: 48px;

  /* Surfaces */
  --surface-vanilla-cream: #fcfbf8;
  --surface-parchment: #ededea;
  --surface-goldenrod-orange: #fd5321;
  --surface-midnight-ink: #001011;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #001011;
  --color-goldenrod-orange: #fd5321;
  --color-storm-gray: #0f1e1f;
  --color-accent-blue: #007aff;
  --color-vanilla-cream: #fcfbf8;
  --color-ash-mist: #c1c4c2;
  --color-parchment: #ededea;

  /* Typography */
  --font-aeonikpro: 'AeonikPro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-dotconnect: 'DotConnect', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 16px;
  --leading-caption: 1.5;
  --tracking-caption: 0.01px;
  --text-body-sm: 18px;
  --leading-body-sm: 1.4;
  --tracking-body-sm: 0.01px;
  --text-body: 21px;
  --leading-body: 1.4;
  --tracking-body: -0.012px;
  --text-subheading: 24px;
  --leading-subheading: 1.1;
  --tracking-subheading: -0.012px;
  --text-heading-sm: 32px;
  --leading-heading-sm: 1.1;
  --tracking-heading-sm: -0.02px;
  --text-heading: 36px;
  --leading-heading: 1.1;
  --tracking-heading: -0.02px;
  --text-heading-lg: 72px;
  --leading-heading-lg: 0.9;
  --tracking-heading-lg: -0.025px;
  --text-display: 101px;
  --leading-display: 0.8;
  --tracking-display: -0.025px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-160: 160px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 28px;
  --radius-3xl-3: 36px;
  --radius-3xl-4: 44px;
  --radius-full: 48px;
}
```

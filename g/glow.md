# Glow — Style Reference
> Vibrant crypto gradient on clean canvas

**Theme:** light

Glow embraces a 'Solana future' aesthetic: clean, spacious interfaces with a vibrant gradient accent that hints at digital energy. The design uses a dominant neutral canvas to ground the playful purple-pink-orange color narrative, focusing attention on key actions and glowing interactive states. Typography is confident and impactful, balancing heavy headlines with readable body text, while generous spacing ensures content breathes and feels light.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Ghost Ink | `#131517` | `--color-ghost-ink` | Primary text, headings, dark icons, borders |
| Cloud Canvas | `#f4f5f6` | `--color-cloud-canvas` | Page backgrounds, elevated card surfaces |
| Snowdrift | `#ffffff` | `--color-snowdrift` | Foreground elements, button text, badges |
| Stone Gray | `#737577` | `--color-stone-gray` | Muted text, secondary icons, subtle borders |
| Soft Sterling | `#b3b5b7` | `--color-soft-sterling` | Placeholder text, inactive state borders |
| Carbon | `#333537` | `--color-carbon` | Secondary button backgrounds, dark UI elements |
| Solana Grape | `#cc62d5` | `--color-solana-grape` | Primary action buttons, active links, interactive elements — a vivid purple that signifies activation |
| Alert Red | `#e83b47` | `--color-alert-red` | Red wash for highlight backgrounds, decorative bands, and soft emphasis behind content. Use as a supporting accent, not as a status color |
| Highlight Orange | `#ec660d` | `--color-highlight-orange` | New feature badges, inline alerts, and decorative accents |
| Glow Gradient | `radial-gradient(86% 86% at 6% 9%, rgb(136, 0, 255) 0%, rgb(167, 50, 214) 51%, rgb(239, 121, 255) 100%)` | `--color-glow-gradient` | Decorative background element, brand identity visual |

## Tokens — Typography

### Roobert — Primary brand typeface for all text. Its unique character delivers a modern, almost technical feel. Weight 700 is used for impactful headlines, while 400 maintains readability in body copy. · `--font-roobert`
- **Substitute:** Inter
- **Weights:** 400, 500, 600, 700
- **Sizes:** 12px, 13px, 16px, 18px, 24px, 40px, 56px
- **Line height:** 1.00, 1.10, 1.17, 1.20, 1.28, 1.50
- **Letter spacing:** -0.0180em, 0.0830em
- **Role:** Primary brand typeface for all text. Its unique character delivers a modern, almost technical feel. Weight 700 is used for impactful headlines, while 400 maintains readability in body copy.

### -apple-system — -apple-system — detected in extracted data but not described by AI · `--font-apple-system`
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.5
- **Role:** -apple-system — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.5 | 0.99px | `--text-caption` |
| body | 16px | 1.28 | — | `--text-body` |
| subheading | 18px | 1.28 | — | `--text-subheading` |
| heading | 24px | 1.17 | -0.43px | `--text-heading` |
| heading-lg | 40px | 1.1 | -0.72px | `--text-heading-lg` |
| display | 56px | 1 | -1px | `--text-display` |

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

### Border Radius

| Element | Value |
|---------|-------|
| cards | 40px |
| icons | 100px |
| badges | 4px |
| buttons | 19px |

### Layout

- **Section gap:** 40px
- **Card padding:** 24px
- **Element gap:** 8px

## Components

### Primary Action Button
**Role:** Filled button

Solid `Solana Grape` background (#cc62d5) with `Snowdrift` (#ffffff) text, rounded corners of 19px, and generous horizontal padding (14px). Used for primary calls to action like 'Get Browser Extension'.

### Secondary Action Button
**Role:** Filled button

Solid `Carbon` (#333537) background with `Snowdrift` (#ffffff) text, rounded corners of 19px, and generous horizontal padding (14px). Used for secondary calls to action like 'Get for iOS'.

### Feature Card
**Role:** Informational display

Large `Cloud Canvas` (#f4f5f6) background card with a dramatically rounded 40px border radius, typically used for showcasing product features. No internal padding is specified; content flows to the edges.

### Badge (New)
**Role:** Status indicator

`Highlight Orange` (#ec660d) background with `Snowdrift` (#ffffff) text, small 4px border radius, and tight 2px vertical, 8px horizontal padding. Used to indicate new features or important states.

## Do's and Don'ts

### Do
- Use `Solana Grape` (#cc62d5) exclusively for primary interactive elements, ensuring every click feels significant.
- Apply `Roobert` with a 700 weight and `Ghost Ink` (#131517) for all main headlines to convey clarity and impact.
- Maintain a clear hierarchy of surfaces: `Snowdrift` (#ffffff) for foreground, `Cloud Canvas` (#f4f5f6) for elevated backgrounds.
- Ensure generous `40px` vertical spacing between major sections for comfortable scanning and visual breathing room.
- Pad interactive elements like buttons and badges with at least `10px` vertical and `14px` horizontal padding, maintaining a `19px` border radius.
- Utilize the `Glow Gradient` for decorative brand elements only, never for functional UI components.

### Don't
- Avoid using `Highlight Orange` (#ec660d) or `Alert Red` (#e83b47) for general UI backgrounds; reserve them for specific semantic alerts or decorative accents.
- Do not introduce additional font families; `Roobert` is the sole brand typeface.
- Refrain from using strong shadows; the design relies on flat layers and subtle transitions, not deep elevation.
- Do not deviate from the established `40px` radius for cards and `19px` for buttons; consistency in shape defines component identity.
- Avoid dense information blocks; instead, use the `8px` `elementGap` and clear typography to create spacious layouts.

## Imagery

The site predominantly uses product screenshots of the Glow wallet interface, presented on stark white or lightly textured surfaces. These are cleanly cropped and isolated, focusing on the UI in action rather than lifestyle. Abstract 3D elements, often in 'Solana Grape' or similar gradient hues (#cc62d5 gradient), float around the screenshots, acting as decorative accents without obscuring the product. Iconography is simple, outlined, and uses the neutral palette with occasional brand color fills for emphasis. The visual language emphasizes product functionality and a modern, slightly playful tech aesthetic over hyper-realistic or human-centric photography.

## Layout

The page primarily employs a max-width contained layout, though the hero section extends full-bleed across the screen with a light background and a left-aligned content block. Sections alternate between a prominent heading and explanatory text, often paired with product screenshots on the opposite side (text-left, image-right, then text-right, image-left). Vertical rhythm is established through consistent `40px` section gaps. Call-to-action buttons are clustered together. Feature showcases utilize card grids, while footer links are minimal and left-aligned. The overall density is comfortable, with ample white space around content blocks, creating an open and airy feel.

## Agent Prompt Guide

Quick Color Reference:
- text: #131517
- background: #f4f5f6
- border: #b3b5b7
- accent: #ec660d
- primary action: #cc62d5 (filled action)

Example Component Prompts:
1. Create a Primary Action Button: #cc62d5 background, #131517 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Create a feature card: `Cloud Canvas` (#f4f5f6) background, 40px radius. Inside, use a `heading` (24px `Roobert` 700, `Ghost Ink` #131517, letter-spacing -0.43px) for the feature title, and `body` text (16px `Roobert` 400, `Ghost Ink` #131517) for the description.
3. Design a 'New' badge: `Highlight Orange` (#ec660d) background with `Snowdrift` (#ffffff) text, 4px radius, 2px 8px padding, using 12px `Roobert` 500.

## Similar Brands

- **Rainbow Wallet** — Vibrant, single-color brand accent against a clean, light UI background in the crypto space.
- **Phantom Wallet** — Uses a similar confident, modern sans-serif typeface and a focus on clean product UI with minimal ornamentation.
- **Linear** — Strict adherence to a well-defined type scale, subtle use of neutrals, and a single accent color for primary actions.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-ghost-ink: #131517;
  --color-cloud-canvas: #f4f5f6;
  --color-snowdrift: #ffffff;
  --color-stone-gray: #737577;
  --color-soft-sterling: #b3b5b7;
  --color-carbon: #333537;
  --color-solana-grape: #cc62d5;
  --color-alert-red: #e83b47;
  --color-highlight-orange: #ec660d;
  --color-glow-gradient: #a732d6;
  --gradient-glow-gradient: radial-gradient(86% 86% at 6% 9%, rgb(136, 0, 255) 0%, rgb(167, 50, 214) 51%, rgb(239, 121, 255) 100%);

  /* Typography — Font Families */
  --font-roobert: 'Roobert', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-apple-system: '-apple-system', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: 0.99px;
  --text-body: 16px;
  --leading-body: 1.28;
  --text-subheading: 18px;
  --leading-subheading: 1.28;
  --text-heading: 24px;
  --leading-heading: 1.17;
  --tracking-heading: -0.43px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.72px;
  --text-display: 56px;
  --leading-display: 1;
  --tracking-display: -1px;

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

  /* Layout */
  --section-gap: 40px;
  --card-padding: 24px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-2xl: 19px;
  --radius-3xl: 40px;
  --radius-full: 100px;

  /* Named Radii */
  --radius-cards: 40px;
  --radius-icons: 100px;
  --radius-badges: 4px;
  --radius-buttons: 19px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-ghost-ink: #131517;
  --color-cloud-canvas: #f4f5f6;
  --color-snowdrift: #ffffff;
  --color-stone-gray: #737577;
  --color-soft-sterling: #b3b5b7;
  --color-carbon: #333537;
  --color-solana-grape: #cc62d5;
  --color-alert-red: #e83b47;
  --color-highlight-orange: #ec660d;
  --color-glow-gradient: #a732d6;

  /* Typography */
  --font-roobert: 'Roobert', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-apple-system: '-apple-system', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: 0.99px;
  --text-body: 16px;
  --leading-body: 1.28;
  --text-subheading: 18px;
  --leading-subheading: 1.28;
  --text-heading: 24px;
  --leading-heading: 1.17;
  --tracking-heading: -0.43px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.72px;
  --text-display: 56px;
  --leading-display: 1;
  --tracking-display: -1px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-2xl: 19px;
  --radius-3xl: 40px;
  --radius-full: 100px;
}
```

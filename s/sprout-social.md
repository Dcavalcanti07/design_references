# Sprout Social — Style Reference
> Ordered command center

**Theme:** dark

Sprout Social presents a commanding, professional digital environment with a strong dark foundation accented by clean white surfaces and precise typography. The design emphasizes clarity and direct interaction, utilizing a single vivid green as its primary action indicator to punctuate key user pathways. Components maintain a uniform, measured appearance with consistent corner radii, conveying stability and trustworthiness. The overall feel is one of a dense, feature-rich interface presented with visual order and an accessible rhythm.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Core | `#040404` | `--color-midnight-core` | Page backgrounds, header, footer, deep surface accents, primary text on light backgrounds |
| Canvas White | `#ffffff` | `--color-canvas-white` | Card backgrounds, navigation backgrounds, input fields, primary text on dark backgrounds |
| Ghost Gray | `#d9d9d9` | `--color-ghost-gray` | Subtle borders, secondary text, decorative fills, and inactive states |
| Focus Silver | `#cbcece` | `--color-focus-silver` | Input borders, subtle button backgrounds, and soft shadows indicating elevation |
| Slate Text | `#162020` | `--color-slate-text` | Secondary text on light backgrounds, input text, and card text |
| Olive Accent | `#98e58e` | `--color-olive-accent` | Green action color for filled buttons, selected navigation states, and focused conversion moments |
| Sky Spectrum Fade | `linear-gradient(1deg, rgb(89, 203, 89) -31.61%, rgb(152, 229, 142) 8.18%, rgb(125, 234, 213) 36.91%, rgb(161, 194, 248) 63.53%, rgb(32, 91, 195) 109.97%)` | `--color-sky-spectrum-fade` | Hero section backgrounds, illustrative elements — indicating growth and expansiveness |
| Magenta Mist Fade | `linear-gradient(rgb(172, 68, 168) -33.09%, rgb(236, 154, 241) 25.66%, rgb(216, 215, 249) 68.39%, rgb(255, 255, 255) 110.38%)` | `--color-magenta-mist-fade` | Illustrative elements, UI highlights — conveying a soft, inviting depth |

## Tokens — Typography

### Proxima Nova — The primary typeface for all text elements. Its geometric sans-serif structure provides clarity and a modern, professional tone, supporting both compact UI labels and expressive marketing headlines. · `--font-proxima-nova`
- **Substitute:** Montserrat
- **Weights:** 400, 700, 800
- **Sizes:** 13px, 16px, 18px, 21px, 24px, 32px, 43px, 57px, 76px
- **Line height:** 1.05, 1.12, 1.18, 1.25, 1.33, 1.40, 1.48, 1.50, 1.64
- **Letter spacing:** normal
- **Role:** The primary typeface for all text elements. Its geometric sans-serif structure provides clarity and a modern, professional tone, supporting both compact UI labels and expressive marketing headlines.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 13px | 1.5 | — | `--text-caption` |
| body | 16px | 1.48 | — | `--text-body` |
| subheading | 18px | 1.4 | — | `--text-subheading` |
| heading-sm | 24px | 1.33 | — | `--text-heading-sm` |
| heading | 32px | 1.25 | — | `--text-heading` |
| heading-lg | 43px | 1.18 | — | `--text-heading-lg` |
| display | 57px | 1.12 | — | `--text-display` |

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
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 56 | 56px | `--spacing-56` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 160 | 160px | `--spacing-160` |
| 200 | 200px | `--spacing-200` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 16px |
| badges | 24px |
| inputs | 6px |
| buttons | 6px |
| largeElements | 64px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| sm | `rgba(39, 51, 51, 0.24) 0px 4px 8px 0px` | `--shadow-sm` |

### Layout

- **Section gap:** 32px
- **Card padding:** 16px
- **Element gap:** 16px

## Components

### Primary Action Button (Filled)
**Role:** Call to action

Filled background in Olive Accent (#98e58e), text in Midnight Core (#040404), with a 6px border-radius, 8px vertical and 12px horizontal padding. Signals the primary interactive element on the page.

### Ghost Button (Dark)
**Role:** Secondary action

Transparent background, text in Canvas White (#ffffff), with a 0px border-radius and 16px padding on all sides. Used for less prominent actions, maintaining hierarchy against dark backgrounds.

### Ghost Button (Light)
**Role:** Secondary action

Transparent background and text in Midnight Core (#040404), with a 0px border-radius and no padding, usually found in navigation or inline actions.

### White Information Card
**Role:** Content container

Canvas White (#ffffff) background, 16px border-radius, no shadow, with 24px padding on all sides. Used for presenting information blocks on dark backgrounds.

### Dark Feature Card
**Role:** Feature showcase

Midnight Core (#040404) background, 8px border-radius, no shadow, with 40px vertical and 32px horizontal padding. Highlights product features or integrations.

### Hero Input Field
**Role:** User input

Canvas White (#ffffff) background, Slate Text (#162020) for text, Focus Silver (#cbcece) 1px border, 4px border-radius, with 8px padding on all sides. For prominent email capture in hero sections.

### Navigation Link
**Role:** Navigation element

Inherits text color from parent context, typically Midnight Core or Canvas White. No background or padding. Hover states implied by color change or subtle underline.

## Do's and Don'ts

### Do
- Prioritize text legibility by ensuring Midnight Core (#040404) on Canvas White (#ffffff) backgrounds, and Canvas White on Midnight Core backgrounds.
- Use Olive Accent (#98e58e) exclusively for primary calls-to-action or key success indicators; avoid decorative use.
- Apply a 16px border-radius to all primary content cards and navigation containers to maintain a consistent soft edge.
- Maintain a comfortable rhythm with 'elementGap': 16px between most interactive elements and 'sectionGap': 32px between major content blocks.
- All headings should use Proxima Nova weight 700 or 800, carefully selecting corresponding sizes from the typescale to establish a clear hierarchy.
- Employ the rgba(39, 51, 51, 0.24) 0px 4px 8px 0px shadow sparingly, primarily for the sticky navigation, to indicate subtle elevation without visual clutter.
- Ensure input fields have a 1px Focus Silver (#cbcece) border and a 4px border-radius for clear definition and soft containment.

### Don't
- Do not introduce new chromatic colors outside of Olive Accent (#98e58e) for interactive elements.
- Avoid arbitrary changes in border-radius; adhere to 16px for cards, 6px for buttons/inputs, and 24px for badges.
- Do not use generic system fonts; only use Proxima Nova or its designated substitute.
- Do not use shadows on content cards directly; rely on background color changes for surface differentiation.
- Do not deviate from the established spacing units; avoid custom padding or margin values that aren't multiples of 4px.
- Avoid hero sections with busy imagery; prioritize gradients or a solid Midnight Core background to highlight text content and interactive elements.
- Do not use black (#000000) for primary text on default light backgrounds where Midnight Core (#040404) is available for better visual cohesion.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Midnight Core Canvas | `#040404` | Primary page background for main content areas and deep sections. |
| 1 | Canvas White Panel | `#ffffff` | Card backgrounds, main navigation, and prominent content blocks appearing on the Midnight Core Canvas. |

## Elevation

- **Sticky Navigation Bar:** `rgba(39, 51, 51, 0.24) 0px 4px 8px 0px`

## Imagery

The visual language relies heavily on product UI screenshots and stylized workflow diagrams, which are embedded within soft-edged white cards or presented within the primary content area. When photography is used, it features high-key, professional, and slightly staged images of individuals interacting with technology, often with a clear focus on the user. Illustrations are dimensional and gradient-filled, avoiding hard outlines, featuring organic shapes that blend into backgrounds. Icons are minimal, either solid-filled or slightly outlined, often monochrome. Imagery serves an explanatory and product-showcasing role, rarely decorative atmosphere, and is generally contained within defined spaces rather than full-bleed.

## Layout

The page primarily uses a full-bleed structure with content often contained within a maximum width section, likely centered. The hero section is full-bleed with a dark background, featuring a prominent centered headline and input fields. Subsequent sections alternate between dark (Midnight Core) and light (Canvas White) backgrounds, creating a clear vertical rhythm. Content within sections is often arranged in multi-column layouts, such as two-column text-left/visual-right patterns or three-column card grids for features and integrations. Navigation is a fixed top bar on a Canvas White background, while the header itself is initially on Midnight Core. The overall density feels comfortable, providing ample breathing room around content blocks.

## Agent Prompt Guide

Quick Color Reference:
- text: #040404
- background: #040404
- border: #d9d9d9
- accent: #98e58e
- primary action: #98e58e (filled action)

Example Component Prompts:
- Create a Primary Action Button: #98e58e background, #000000 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
- Create a White Information Card: Canvas White (#ffffff) background, 16px border-radius, 24px padding. Headline 'Understand your audience' Proxima Nova weight 700, size 32px, Midnight Core (#040404). Body text 'Analyze demographics, interests, and activity patterns to tailor your content strategy.' Proxima Nova weight 400, size 16px, Slate Text (#162020).
- Create a Dark Feature Card: Midnight Core (#040404) background, 8px border-radius, 40px vertical/32px horizontal padding. Headline 'Seamless Integrations' Proxima Nova weight 700, size 24px, Canvas White (#ffffff). Body text 'Connect your favorite tools directly into your social workflow.' Proxima Nova weight 400, size 18px, Canvas White (#ffffff).

## Similar Brands

- **Hootsuite** — Social media management tool with a similar emphasis on clean UI, prominent feature cards, and accessible typography.
- **Buffer** — Social media scheduling and analytics platform that uses a dark/light contrast for sections and clean, functional components.
- **Later** — Marketing platform with a focus on visual content presentation and a structured grid layout for features and integrations.
- **Mailchimp** — Known for a distinct brand color (yellow) used as a primary accent against neutral backdrops, similar to Sprout Social's use of green.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-core: #040404;
  --color-canvas-white: #ffffff;
  --color-ghost-gray: #d9d9d9;
  --color-focus-silver: #cbcece;
  --color-slate-text: #162020;
  --color-olive-accent: #98e58e;
  --color-sky-spectrum-fade: #59cb59;
  --gradient-sky-spectrum-fade: linear-gradient(1deg, rgb(89, 203, 89) -31.61%, rgb(152, 229, 142) 8.18%, rgb(125, 234, 213) 36.91%, rgb(161, 194, 248) 63.53%, rgb(32, 91, 195) 109.97%);
  --color-magenta-mist-fade: #ac44a8;
  --gradient-magenta-mist-fade: linear-gradient(rgb(172, 68, 168) -33.09%, rgb(236, 154, 241) 25.66%, rgb(216, 215, 249) 68.39%, rgb(255, 255, 255) 110.38%);

  /* Typography — Font Families */
  --font-proxima-nova: 'Proxima Nova', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 1.5;
  --text-body: 16px;
  --leading-body: 1.48;
  --text-subheading: 18px;
  --leading-subheading: 1.4;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.33;
  --text-heading: 32px;
  --leading-heading: 1.25;
  --text-heading-lg: 43px;
  --leading-heading-lg: 1.18;
  --text-display: 57px;
  --leading-display: 1.12;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-bold: 700;
  --font-weight-extrabold: 800;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-160: 160px;
  --spacing-200: 200px;

  /* Layout */
  --section-gap: 32px;
  --card-padding: 16px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-full: 64px;

  /* Named Radii */
  --radius-cards: 16px;
  --radius-badges: 24px;
  --radius-inputs: 6px;
  --radius-buttons: 6px;
  --radius-largeelements: 64px;

  /* Shadows */
  --shadow-sm: rgba(39, 51, 51, 0.24) 0px 4px 8px 0px;

  /* Surfaces */
  --surface-midnight-core-canvas: #040404;
  --surface-canvas-white-panel: #ffffff;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-core: #040404;
  --color-canvas-white: #ffffff;
  --color-ghost-gray: #d9d9d9;
  --color-focus-silver: #cbcece;
  --color-slate-text: #162020;
  --color-olive-accent: #98e58e;
  --color-sky-spectrum-fade: #59cb59;
  --color-magenta-mist-fade: #ac44a8;

  /* Typography */
  --font-proxima-nova: 'Proxima Nova', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 1.5;
  --text-body: 16px;
  --leading-body: 1.48;
  --text-subheading: 18px;
  --leading-subheading: 1.4;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.33;
  --text-heading: 32px;
  --leading-heading: 1.25;
  --text-heading-lg: 43px;
  --leading-heading-lg: 1.18;
  --text-display: 57px;
  --leading-display: 1.12;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-160: 160px;
  --spacing-200: 200px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-full: 64px;

  /* Shadows */
  --shadow-sm: rgba(39, 51, 51, 0.24) 0px 4px 8px 0px;
}
```

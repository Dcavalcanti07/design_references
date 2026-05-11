# Generative AI — Style Reference
> Pixelated digital playground

**Theme:** light

Fal.ai employs a vibrant, digital-first aesthetic, evoking a playful yet powerful generative AI platform. High-contrast typography is layered over a base of clean white and subtle gray surfaces, occasionally interrupted by striking graphic patterns and colorful background washes. The visual system balances strong, angular geometric shapes with pixel-art style details, creating a distinctive blend of retro-tech and contemporary design. Accent colors are used sparingly for interactive elements and abstract background fills, maintaining a focus on content.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#1b1b1d` | `--color-midnight-ink` | Primary text, deep surface elements, button text |
| Carbon | `#000000` | `--color-carbon` | Strongest text, critical information, contrast elements |
| Cloud White | `#ffffff` | `--color-cloud-white` | Component backgrounds, card surfaces, ghost button backgrounds |
| Stone Gray | `#383a42` | `--color-stone-gray` | Body text, secondary text |
| Soft Mist | `#e5e7eb` | `--color-soft-mist` | Page backgrounds, dividers, borders |
| Silver Dust | `#f4f4f5` | `--color-silver-dust` | Subtle background shifts, card surfaces |
| Deep Plum | `#252527` | `--color-deep-plum` | Primary action button background, dark surface accent |
| Sky Aqua | `#99ecff` | `--color-sky-aqua` | Hero section background, footer background, decorative fills |
| Vivid Violet | `#4a17b0` | `--color-vivid-violet` | Decorative graphic fills, card backgrounds |
| Lime Spritz | `#f1ffd2` | `--color-lime-spritz` | Decorative graphic fills, card backgrounds |
| Royal Purple | `#6120ee` | `--color-royal-purple` | Link text, active state indicator |
| Lavender Haze | `#d0b7f9` | `--color-lavender-haze` | Subtle card backgrounds, decorative fills |
| Rose Petal | `#ffddfa` | `--color-rose-petal` | Subtle card backgrounds, decorative fills |

## Tokens — Typography

### focal — Primary typeface for all headings, body text, and UI elements. Tight letter spacing is characteristic for larger sizes; it creates a modern, condensed feel. · `--font-focal`
- **Substitute:** Inter
- **Weights:** 400, 500, 600, 700
- **Sizes:** 10px, 12px, 14px, 16px, 18px, 24px, 30px, 36px, 40px, 48px, 60px, 80px, 120px
- **Line height:** 0.83, 0.88, 0.90, 1.00, 1.11, 1.20, 1.33, 1.40, 1.43, 1.50, 1.56, 1.60
- **Letter spacing:** -0.0400em, -0.0250em, -0.0200em
- **Role:** Primary typeface for all headings, body text, and UI elements. Tight letter spacing is characteristic for larger sizes; it creates a modern, condensed feel.

### Chivo Mono — Monospace typeface for code snippets and technical labels, providing a distinct developer-centric tone. · `--font-chivo-mono`
- **Substitute:** Space Mono
- **Weights:** 400
- **Sizes:** 14px
- **Line height:** 1.14, 1.43, 1.50
- **Role:** Monospace typeface for code snippets and technical labels, providing a distinct developer-centric tone.

### publicSansRounded — Used for specific link and button text, offering a slightly softer, rounded alternative for interactive elements. The stylistic set 'ss01' provides unique character forms. · `--font-publicsansrounded`
- **Substitute:** Public Sans
- **Weights:** 400, 600, 700
- **Sizes:** 14px, 16px, 24px
- **Line height:** 1.00, 1.43, 1.50
- **Letter spacing:** -0.0200em, -0.0100em
- **OpenType features:** `'ss01' on`
- **Role:** Used for specific link and button text, offering a slightly softer, rounded alternative for interactive elements. The stylistic set 'ss01' provides unique character forms.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.6 | — | `--text-caption` |
| body | 14px | 1.5 | — | `--text-body` |
| body-lg | 16px | 1.5 | — | `--text-body-lg` |
| subheading | 18px | 1.4 | — | `--text-subheading` |
| heading-sm | 24px | 1.33 | — | `--text-heading-sm` |
| heading | 30px | 1.2 | — | `--text-heading` |
| heading-lg | 36px | 1.11 | -0.72px | `--text-heading-lg` |
| display-sm | 40px | 1 | -0.8px | `--text-display-sm` |
| display | 48px | 0.9 | -1.2px | `--text-display` |
| display-lg | 60px | 0.88 | -1.5px | `--text-display-lg` |

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
| 96 | 96px | `--spacing-96` |
| 112 | 112px | `--spacing-112` |
| 128 | 128px | `--spacing-128` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 12px |
| buttons | 4px |
| default | 4px |

### Layout

- **Page max-width:** 1440px
- **Section gap:** 113px
- **Card padding:** 16px
- **Element gap:** 16px

## Components

### Primary Filled Button
**Role:** Call to action button

Solid Deep Plum background (#252527) with Cloud White text (#ffffff). Features a 4px border-radius and generous 0px vertical, 16px horizontal padding. Text uses publicSansRounded font, typically 16px or 14px.

### Ghost Button
**Role:** Secondary action button

Transparent background with Midnight Ink text (#1b1b1d) and a 1px Soft Mist border (#e5e7eb). 4px border-radius, 0px vertical, 16px horizontal padding. For less prominent actions where a fill would be too heavy. Text uses publicSansRounded font.

### Standard Card
**Role:** Content container

Cloud White background (#ffffff) with a 4px border-radius. Features 32px padding on all sides. No shadow, relying on background contrast for separation.

### Accent Card - Lime Spritz
**Role:** Highlighted content container

Lime Spritz background (#f1ffd2) with a 12px border-radius. Features 16px padding on all sides. Used for sections requiring visual emphasis or thematic alignment.

### Accent Card - Lavender Haze
**Role:** Highlighted content container

Lavender Haze background (#d0b7f9) with a 12px border-radius. Features 16px padding on all sides. Similar to Lime Spritz, provides visual distinction for content blocks.

### Testimonial Card
**Role:** Social proof container

Silver Dust background (#f4f4f5) with an 8px border-radius. Features 24px padding on all sides. Accommodates slightly denser content than larger cards.

### Navigation Link
**Role:** Header and footer navigation items

Midnight Ink text (#1b1b1d) at 16px focal font weight 400. Hover state likely involves the Royal Purple accent color.

### Small Text Button
**Role:** Compact action button

Cloud White background (#ffffff) with Midnight Ink text (#1b1b1d). 4px border-radius, padding 0px vertical, 16px horizontal. Similar to Primary Filled Button but with lighter styling for secondary use.

## Do's and Don'ts

### Do
- Prioritize Cloud White (#ffffff) and Soft Mist (#e5e7eb) as primary background surfaces, reserving accent colors for graphic elements and thematic sections.
- Use focal for all primary text content and headings, leveraging its various weights and condensed letter spacing for visual impact at larger sizes.
- Apply a 4px border-radius to all interactive elements like buttons and input fields for a consistent subtle rounding.
- Implement Deep Plum (#252527) as the background for primary action buttons, ensuring a high contrast with Cloud White text (#ffffff).
- Maintain a clear visual hierarchy with element gaps, using 16px as a default for spacing between interactive elements and body text blocks.
- Incorporate accent colors like Sky Aqua (#99ecff), Vivid Violet (#4a17b0), and Lime Spritz (#f1ffd2) primarily as background washes or decorative fills, not for extensive UI components.
- Ensure all interactive text, such as links and button text, is in Midnight Ink (#1b1b1d) or Cloud White (#ffffff) against contrasting backgrounds, with Royal Purple (#6120ee) for active links.

### Don't
- Avoid using drop shadows for elevation; rely on clear background color changes and borders for surface distinction.
- Do not introduce new typefaces outside of focal, Chivo Mono, and publicSansRounded to maintain typographic consistency.
- Resist using highly saturated accent colors for extensive blocks of body text, as they are reserved for decorative elements.
- Do not deviate from the established 4px, 8px, and 12px border-radii for components; arbitrary rounding breaks pattern.
- Avoid generic, full-width content blocks. All content should be constrained by the 1440px page max-width, centrally aligned.
- Do not use dark backgrounds for entire page sections unless for explicit hero or footer areas, as the theme is predominantly light.
- Do not treat every decorative graphic fill color as a UI token; focus on the consistent palette for interactive and functional elements.

## Imagery

The visual language combines abstract, pixelated geometric graphics with focused product display. The abstract graphics, often in vivid accent colors like Sky Aqua, Vivid Violet, and Lime Spritz, are used as atmospheric background elements or decorative overlays. Product imagery consists of tight crops of AI-generated media (video frames, 3D models) contained within distinct card surfaces, showcasing the output of the platform. Iconography appears to be outlined with a consistent stroke weight, emphasizing clarity and a lightweight feel. Overall density is balanced, with imagery serving both decorative and explanatory roles without overwhelming the text-dominant interface sections.

## Layout

The page maintains a max-width of 1440px, centered on the screen, creating a structured and contained feel. The hero section is a full-bleed vibrant canvas, featuring a prominent centered headline over dynamic, pixelated background graphics. Vertical rhythm between sections is established with a significant section gap, sometimes signaled by alternating background colors (e.g., Sky Aqua hero transitioning to a Cloud White main content area). Content often uses two-column layouts, particularly for text-left/image-right or text-right/image-left arrangements, and a three-column card grid for feature showcases. The page is moderately spacious, with generous padding within components and between sections. Navigation is a consistent top bar with primary links and contained action buttons.

## Agent Prompt Guide

Quick Color Reference:
text: #1b1b1d
background: #e5e7eb
border: #e5e7eb
accent: #99ecff
primary action: #252527 (filled action)

Example Component Prompts:
1. Create a Primary Filled Button: background #252527, text #ffffff, focal font weight 600, 16px, 4px radius, 0px vertical and 16px horizontal padding.
2. Design a Standard Card: background #ffffff, 4px radius, 32px padding on all sides. Body text #383a42, focal font weight 400, 14px.
3. Implement a Hero Section Headline: 'Generative media platform for developers.' using focal font, weight 700, size 80px, color #000000, line-height 0.83, letter-spacing -2px. Background of #99ecff with abstract pixelated graphics.
4. Create a Testimonial Card for 'Perplexity': background #f4f4f5, 8px radius, 24px padding. Quote text #383a42, focal font weight 400, 16px. Author name #1b1b1d, focal font weight 600, 14px.

## Similar Brands

- **Vercel** — Clean, light UI with strong typography and a focus on developer tools. Uses dark-themed components within a light overall layout.
- **Stripe** — High-contrast typography, clear visual hierarchy, and an emphasis on showcasing complex product features through clean design and occasional accent colors.
- **Replicate** — AI/ML developer platform with a functional, modern design, often using a limited color palette and prominent typography to highlight technical products.
- **Midjourney** — Focus on generative media, often with striking visual elements contrasted against a functional, streamlined UI.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #1b1b1d;
  --color-carbon: #000000;
  --color-cloud-white: #ffffff;
  --color-stone-gray: #383a42;
  --color-soft-mist: #e5e7eb;
  --color-silver-dust: #f4f4f5;
  --color-deep-plum: #252527;
  --color-sky-aqua: #99ecff;
  --color-vivid-violet: #4a17b0;
  --color-lime-spritz: #f1ffd2;
  --color-royal-purple: #6120ee;
  --color-lavender-haze: #d0b7f9;
  --color-rose-petal: #ffddfa;

  /* Typography — Font Families */
  --font-focal: 'focal', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-chivo-mono: 'Chivo Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-publicsansrounded: 'publicSansRounded', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.6;
  --text-body: 14px;
  --leading-body: 1.5;
  --text-body-lg: 16px;
  --leading-body-lg: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.4;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.33;
  --text-heading: 30px;
  --leading-heading: 1.2;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1.11;
  --tracking-heading-lg: -0.72px;
  --text-display-sm: 40px;
  --leading-display-sm: 1;
  --tracking-display-sm: -0.8px;
  --text-display: 48px;
  --leading-display: 0.9;
  --tracking-display: -1.2px;
  --text-display-lg: 60px;
  --leading-display-lg: 0.88;
  --tracking-display-lg: -1.5px;

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
  --spacing-96: 96px;
  --spacing-112: 112px;
  --spacing-128: 128px;

  /* Layout */
  --page-max-width: 1440px;
  --section-gap: 113px;
  --card-padding: 16px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;

  /* Named Radii */
  --radius-cards: 12px;
  --radius-buttons: 4px;
  --radius-default: 4px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #1b1b1d;
  --color-carbon: #000000;
  --color-cloud-white: #ffffff;
  --color-stone-gray: #383a42;
  --color-soft-mist: #e5e7eb;
  --color-silver-dust: #f4f4f5;
  --color-deep-plum: #252527;
  --color-sky-aqua: #99ecff;
  --color-vivid-violet: #4a17b0;
  --color-lime-spritz: #f1ffd2;
  --color-royal-purple: #6120ee;
  --color-lavender-haze: #d0b7f9;
  --color-rose-petal: #ffddfa;

  /* Typography */
  --font-focal: 'focal', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-chivo-mono: 'Chivo Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-publicsansrounded: 'publicSansRounded', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.6;
  --text-body: 14px;
  --leading-body: 1.5;
  --text-body-lg: 16px;
  --leading-body-lg: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.4;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.33;
  --text-heading: 30px;
  --leading-heading: 1.2;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1.11;
  --tracking-heading-lg: -0.72px;
  --text-display-sm: 40px;
  --leading-display-sm: 1;
  --tracking-display-sm: -0.8px;
  --text-display: 48px;
  --leading-display: 0.9;
  --tracking-display: -1.2px;
  --text-display-lg: 60px;
  --leading-display-lg: 0.88;
  --tracking-display-lg: -1.5px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-96: 96px;
  --spacing-112: 112px;
  --spacing-128: 128px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
}
```

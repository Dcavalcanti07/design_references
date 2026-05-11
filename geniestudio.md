# Geniestudio — Style Reference
> White canvas, friendly illustrations.

**Theme:** light

Geniestudio presents a friendly, open design language against a bright, airy backdrop. Softly rounded elements and a distinctive dark button color punctuate a largely monochromatic interface. The design uses gradients sparingly for visual flair, primarily on illustration assets, maintaining a neat and approachable aesthetic. Typography feels modern and clean, with nuanced letter spacing creating a premium yet comfortable reading experience. Overall, the system feels inviting and lightweight, focusing on clarity and ease of use.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#181d27` | `--color-midnight-ink` | Primary action buttons, prominent interactive elements — a deep, near-black that grounds interactive components |
| Arctic Mist | `#fafdff` | `--color-arctic-mist` | Card backgrounds, secondary container surfaces — a subtle off-white providing depth on the canvas |
| Canvas White | `#ffffff` | `--color-canvas-white` | Main page background, default text color for dark buttons, subtle borders |
| Obsidian | `#0a0d12` | `--color-obsidian` | Primary headings and prominent text — a rich, dark tone for high contrast |
| Silver Pine | `#535862` | `--color-silver-pine` | Secondary text, muted links, detailed descriptions and iconography |
| Ash Gray | `#93979f` | `--color-ash-gray` | Muted text, form placeholders, minor divider lines, inactive states |
| Sky Wash | `#ebf5ff` | `--color-sky-wash` | Base canvas background, light decorative fills — provides a soft, cool tint to the overall page |
| Ghostly Blue | `#cce7ff` | `--color-ghostly-blue` | Light background fills for secondary cards and decorative elements |
| Electric Blue | `#0069e0` | `--color-electric-blue` | Accent borders, infographic elements, decorative strokes — a vibrant hue often used in illustrations |
| Lavender Mist | `#f1e6ff` | `--color-lavender-mist` | Background for accent cards, soft decorative fills |
| Mint Glaze | `#d3f6e3` | `--color-mint-glaze` | Background for accent cards, soft decorative fills |
| Sunburst Yellow | `#bb9915` | `--color-sunburst-yellow` | Decorative highlights, infographic elements, specific accent text/icons |
| Deep Violet | `#9552e0` | `--color-deep-violet` | Decorative highlights, infographic elements, specific accent text/icons |
| Ocean Spray | `#4fbeff` | `--color-ocean-spray` | Decorative highlights, infographic elements, specific accent text/icons |
| Zesty Orange | `#f26110` | `--color-zesty-orange` | Decorative highlights, infographic elements, specific accent text/icons |
| Luminous Blue | `#0099ff` | `--color-luminous-blue` | Blue outline accent for tags, dividers, and focused UI edges. Do not promote it to the primary CTA color |
| Whisper Fade Yellow | `linear-gradient(rgb(255, 249, 224) 0%, rgb(255, 236, 163) 100%)` | `--color-whisper-fade-yellow` | Soft gradient background for decorative features |
| Whisper Fade Violet | `linear-gradient(rgb(244, 235, 255) 0%, rgb(228, 204, 255) 100%)` | `--color-whisper-fade-violet` | Soft gradient background for decorative features |
| Whisper Fade Blue | `linear-gradient(rgb(229, 246, 255) 0%, rgb(194, 233, 255) 100%)` | `--color-whisper-fade-blue` | Soft gradient background for decorative features |
| Whisper Fade Orange | `linear-gradient(rgb(255, 242, 235) 0%, rgb(255, 209, 184) 100%)` | `--color-whisper-fade-orange` | Soft gradient background for decorative features |

## Tokens — Typography

### Geist — Body text, navigation links, button text, and all supportive details. The consistent, slightly tight letter spacing at -0.01em gives text a concise appearance, maintaining readability while feeling modern. · `--font-geist`
- **Substitute:** Inter
- **Weights:** 500, 600
- **Sizes:** 10px, 12px, 14px, 16px, 18px, 20px
- **Line height:** 1.14, 1.33, 1.35, 1.40, 1.50
- **Letter spacing:** -0.01
- **OpenType features:** `'case'`
- **Role:** Body text, navigation links, button text, and all supportive details. The consistent, slightly tight letter spacing at -0.01em gives text a concise appearance, maintaining readability while feeling modern.

### Aeonik — Headlines and prominent display text. The consistent tighter letter spacing at -0.02em creates compact, impactful headers, drawing attention without visual clutter. Its lower x-height compared to Geist differentiates its use for display content. · `--font-aeonik`
- **Substitute:** Montserrat
- **Weights:** 500
- **Sizes:** 20px, 24px, 32px, 48px, 72px, 148px
- **Line height:** 1.05, 1.11, 1.17, 1.20, 1.25
- **Letter spacing:** -0.02
- **OpenType features:** `'case'`
- **Role:** Headlines and prominent display text. The consistent tighter letter spacing at -0.02em creates compact, impactful headers, drawing attention without visual clutter. Its lower x-height compared to Geist differentiates its use for display content.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body-lg | 14px | 1.33 | -0.14px | `--text-body-lg` |
| heading-sm | 18px | 1.5 | -0.18px | `--text-heading-sm` |
| heading | 20px | 1.25 | -0.4px | `--text-heading` |
| heading-lg | 24px | 1.2 | -0.48px | `--text-heading-lg` |
| display | 32px | 1.17 | -0.64px | `--text-display` |
| display-lg | 48px | 1.11 | -0.96px | `--text-display-lg` |
| display-xl | 72px | 1.05 | -1.44px | `--text-display-xl` |

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
| 120 | 120px | `--spacing-120` |
| 160 | 160px | `--spacing-160` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 32px |
| icons | 16px |
| badges | 90px |
| images | 16px |
| buttons | 32px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| lg | `rgba(4, 69, 144, 0.08) 0px 14px 20px 4px` | `--shadow-lg` |
| subtle | `rgba(10, 13, 18, 0.8) 0px 1px 2px 0px, rgb(10, 13, 18) 0p...` | `--shadow-subtle` |

### Layout

- **Section gap:** 24px
- **Card padding:** 40px
- **Element gap:** 24px

## Components

### Primary Action Button
**Role:** Call to action

Filled button with a dark background '#181d27', white text '#ffffff', 32px border-radius, and generous padding (12px vertical, 32px horizontal). Acts as the main interactive element.

### Small Primary Action Button
**Role:** Secondary call to action

Compact filled button with a dark background '#181d27', white text '#ffffff', 16px border-radius, and reduced padding (8px vertical, 16px horizontal).

### Header Action Button
**Role:** Navigation action

Medium-sized filled button for header actions with a dark background '#181d27', white text '#ffffff', 36px border-radius, and moderate padding (8px vertical, 24px horizontal).

### Feature Card
**Role:** Informational display

Card with 'Arctic Mist' background '#fafdff', 32px border-radius, and 40px internal padding. Used for features and testimonials.

### Decorative Icon Card (Round)
**Role:** Visual accent container

Transparent card with a 50% border-radius (circular). Holds decorative icons and illustrations without a background fill.

### Standard Content Card
**Role:** General content container

Transparent card with 8px border-radius for grouping textual content and images.

## Do's and Don'ts

### Do
- Prioritize 'Obsidian' (#0a0d12) for all main headings and primary text, ensuring a high contrast ratio of at least 18:1 against light backgrounds.
- Utilize 'Midnight Ink' (#181d27) exclusively for primary button backgrounds; never apply it to text directly.
- Apply 'Arctic Mist' (#fafdff) as the background for most cards and secondary content blocks, providing subtle visual separation from the main page canvas.
- Use a border-radius of 32px for all primary action buttons, feature cards, and larger decorative elements to maintain a consistent soft aesthetic.
- Implement the 'Aeonik' font for all headings from size 20px upwards, ensuring consistent letter-spacing of -0.02em.
- Maintain 24px as the standard vertical and horizontal gap between major layout elements and within card grids.
- Employ Geist font (weights 500-600) for all body text, links, and minor interface labels, with a consistent letter-spacing of -0.01em.

### Don't
- Avoid using highly saturated colors for large background areas or extensive text blocks; keep these for small accents or illustrations.
- Do not deviate from the specified Geist and Aeonik font stacks and their letter-spacing; custom type is a core identifier.
- Never use #0000ee (browser default link blue); instead, use 'Luminous Blue' (#0099ff) for interactive link text.
- Do not introduce sharp corners; all interactive elements and content containers should adhere to the established border-radius values (e.g., 32px, 16px, 8px).
- Avoid heavy drop shadows or multiple layered shadows on UI elements; elevation is subtle, primarily using rgba(4, 69, 144, 0.08) 0px 14px 20px 4px for depth.
- Do not use dark backgrounds for content sections; the system is built around a light theme, with dark used only for specific UI like buttons.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Sky Wash Canvas | `#ebf5ff` | The foundational background color for the entire page, providing an ethereal, cool tint. |
| 1 | Canvas White Base | `#ffffff` | The primary background for most sections and content areas, offering a clean, bright foundation. |
| 2 | Arctic Mist Card | `#fafdff` | Elevated card backgrounds, creating subtle visual separation and depth. |

## Elevation

- **Card Shadow:** `rgba(4, 69, 144, 0.08) 0px 14px 20px 4px`
- **Button Shadow:** `rgba(10, 13, 18, 0.8) 0px 1px 2px 0px, rgb(10, 13, 18) 0px 0px 0px 1px`

## Imagery

The site uses a combination of abstract, whimsical illustrations with organic shapes and cloud motifs, and contained product-focused imagery. Illustrations are flat, graphic, and often outlined, using a palette of soft pastel accents and instances of vibrant brand colors. They serve a decorative and atmospheric role, adding a friendly, approachable mood. Product screenshots, when present, appear to be tightly cropped within rounded containers. Icons are primarily outlined or have a light stroke, maintaining the lightness of the interface. Imagery density is moderate, allowing ample white space, ensuring a text-dominant but visually engaging experience.

## Layout

The page structure favors a max-width contained layout, likely around 1200-1400px, against a full-width background. The hero section is characterized by a centered headline and button over a light, expansive background with decorative illustrations. Sections maintain consistent vertical spacing, often indicated by a 24px element gap, with subtle background color changes ('Canvas White' alternating with 'Sky Wash' or 'Arctic Mist') for visual rhythm. Content is arranged in flexible patterns, including centered stacks for calls to action, alternating text-left/visual-right compositions, and responsive card grids for features and testimonials. Navigation is a minimal top bar with a primary action button on the far right.

## Agent Prompt Guide

Quick Color Reference: 
text: #0a0d12
background: #ebf5ff
border: #535862
accent: #0069e0
primary action: #181d27 (filled action)

Example Component Prompts:
Create a Primary Action Button: #181d27 background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.

Create a 'Feature Card': 'Arctic Mist' background, 32px border-radius, with 40px padding. Inside, 'Aeonik' weight 500, 24px, '#0a0d12' for a title and 'Geist' weight 500, 16px, '#535862' for the description, with an 'Electric Blue' (#0069e0) decorative icon above.

Create a testimonial card: 'Arctic Mist' background, 32px border-radius, with 40px internal padding. Caption text 'Geist' weight 500, 16px, '#0a0d12'. Below, muted attribution text 'Geist' weight 500, 14px, '#93979f'.

## Similar Brands

- **Framer** — Shares a clean, modern aesthetic with strong typography, ample white space, and a mix of subtle and bold interactive elements.
- **Linear** — Utilizes a minimalist, light UI with purposeful use of dark primary buttons and restrained accent colors.
- **Supabase** — Employs a bright, light-themed interface with strong typography and clear, simple component designs, often featuring rounded shapes.
- **Loom** — Features a friendly and approachable design, with clean lines, rounded elements, and a focus on clarity and user-friendliness without heavy UI chrome.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #181d27;
  --color-arctic-mist: #fafdff;
  --color-canvas-white: #ffffff;
  --color-obsidian: #0a0d12;
  --color-silver-pine: #535862;
  --color-ash-gray: #93979f;
  --color-sky-wash: #ebf5ff;
  --color-ghostly-blue: #cce7ff;
  --color-electric-blue: #0069e0;
  --color-lavender-mist: #f1e6ff;
  --color-mint-glaze: #d3f6e3;
  --color-sunburst-yellow: #bb9915;
  --color-deep-violet: #9552e0;
  --color-ocean-spray: #4fbeff;
  --color-zesty-orange: #f26110;
  --color-luminous-blue: #0099ff;
  --color-whisper-fade-yellow: #fff9e0;
  --gradient-whisper-fade-yellow: linear-gradient(rgb(255, 249, 224) 0%, rgb(255, 236, 163) 100%);
  --color-whisper-fade-violet: #f4ebff;
  --gradient-whisper-fade-violet: linear-gradient(rgb(244, 235, 255) 0%, rgb(228, 204, 255) 100%);
  --color-whisper-fade-blue: #e5f6ff;
  --gradient-whisper-fade-blue: linear-gradient(rgb(229, 246, 255) 0%, rgb(194, 233, 255) 100%);
  --color-whisper-fade-orange: #fff2eb;
  --gradient-whisper-fade-orange: linear-gradient(rgb(255, 242, 235) 0%, rgb(255, 209, 184) 100%);

  /* Typography — Font Families */
  --font-geist: 'Geist', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-aeonik: 'Aeonik', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-lg: 14px;
  --leading-body-lg: 1.33;
  --tracking-body-lg: -0.14px;
  --text-heading-sm: 18px;
  --leading-heading-sm: 1.5;
  --tracking-heading-sm: -0.18px;
  --text-heading: 20px;
  --leading-heading: 1.25;
  --tracking-heading: -0.4px;
  --text-heading-lg: 24px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -0.48px;
  --text-display: 32px;
  --leading-display: 1.17;
  --tracking-display: -0.64px;
  --text-display-lg: 48px;
  --leading-display-lg: 1.11;
  --tracking-display-lg: -0.96px;
  --text-display-xl: 72px;
  --leading-display-xl: 1.05;
  --tracking-display-xl: -1.44px;

  /* Typography — Weights */
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
  --spacing-120: 120px;
  --spacing-160: 160px;

  /* Layout */
  --section-gap: 24px;
  --card-padding: 40px;
  --element-gap: 24px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;
  --radius-3xl-3: 36px;
  --radius-full: 90px;

  /* Named Radii */
  --radius-cards: 32px;
  --radius-icons: 16px;
  --radius-badges: 90px;
  --radius-images: 16px;
  --radius-buttons: 32px;

  /* Shadows */
  --shadow-lg: rgba(4, 69, 144, 0.08) 0px 14px 20px 4px;
  --shadow-subtle: rgba(10, 13, 18, 0.8) 0px 1px 2px 0px, rgb(10, 13, 18) 0px 0px 0px 1px;

  /* Surfaces */
  --surface-sky-wash-canvas: #ebf5ff;
  --surface-canvas-white-base: #ffffff;
  --surface-arctic-mist-card: #fafdff;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #181d27;
  --color-arctic-mist: #fafdff;
  --color-canvas-white: #ffffff;
  --color-obsidian: #0a0d12;
  --color-silver-pine: #535862;
  --color-ash-gray: #93979f;
  --color-sky-wash: #ebf5ff;
  --color-ghostly-blue: #cce7ff;
  --color-electric-blue: #0069e0;
  --color-lavender-mist: #f1e6ff;
  --color-mint-glaze: #d3f6e3;
  --color-sunburst-yellow: #bb9915;
  --color-deep-violet: #9552e0;
  --color-ocean-spray: #4fbeff;
  --color-zesty-orange: #f26110;
  --color-luminous-blue: #0099ff;
  --color-whisper-fade-yellow: #fff9e0;
  --color-whisper-fade-violet: #f4ebff;
  --color-whisper-fade-blue: #e5f6ff;
  --color-whisper-fade-orange: #fff2eb;

  /* Typography */
  --font-geist: 'Geist', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-aeonik: 'Aeonik', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-lg: 14px;
  --leading-body-lg: 1.33;
  --tracking-body-lg: -0.14px;
  --text-heading-sm: 18px;
  --leading-heading-sm: 1.5;
  --tracking-heading-sm: -0.18px;
  --text-heading: 20px;
  --leading-heading: 1.25;
  --tracking-heading: -0.4px;
  --text-heading-lg: 24px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -0.48px;
  --text-display: 32px;
  --leading-display: 1.17;
  --tracking-display: -0.64px;
  --text-display-lg: 48px;
  --leading-display-lg: 1.11;
  --tracking-display-lg: -0.96px;
  --text-display-xl: 72px;
  --leading-display-xl: 1.05;
  --tracking-display-xl: -1.44px;

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
  --spacing-120: 120px;
  --spacing-160: 160px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;
  --radius-3xl-3: 36px;
  --radius-full: 90px;

  /* Shadows */
  --shadow-lg: rgba(4, 69, 144, 0.08) 0px 14px 20px 4px;
  --shadow-subtle: rgba(10, 13, 18, 0.8) 0px 1px 2px 0px, rgb(10, 13, 18) 0px 0px 0px 1px;
}
```

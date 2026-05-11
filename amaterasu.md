# Amaterasu — Style Reference
> Deep blue celestial clarity

**Theme:** dark

Amaterasu's design system uses a 'digital calm' aesthetic, blending deep, serene blues with stark white typography to create a sense of focused introspection. Sparse iconography and a strong emphasis on whitespace allow content to breathe, fostering a tranquil yet authoritative atmosphere. Primary interactions are subtly defined by borders rather than fills, maintaining the minimalist dark theme, while gradients offer soft, ethereal backdrops.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Astral Deep | `#1b2978` | `--color-astral-deep` | Outlined button borders, heading accents, interactive states — a deep violet blue providing grounded strength |
| Digital Mist | `#7488a5` | `--color-digital-mist` | Decorative stroke elements, subtle UI accents |
| Sapphire Gaze | `#19366c` | `--color-sapphire-gaze` | Subtle border accents, decorative graphics |
| Sky Veil | `#579dc0` | `--color-sky-veil` | Decorative strokes, visual embellishments in illustrations or icons |
| Focus Shadow | `#466187` | `--color-focus-shadow` | Blue supporting accent for decorative details and low-frequency emphasis. Do not promote it to the primary CTA color |
| Aqua Whisper | `#75cdd6` | `--color-aqua-whisper` | Occasional background wash for specific sections, soft surface elevation |
| Canvas White | `#ffffff` | `--color-canvas-white` | Primary text, icon fill, neutral button borders, base background of some lighter sections |
| Void Black | `#000000` | `--color-void-black` | Deepest text color on light backgrounds, hero background, decorative borders |
| Nebula Gradient | `linear-gradient(174deg, rgb(42, 57, 142) 5%, rgb(85, 102, 197) 100%)` | `--color-nebula-gradient` | Ethereal background for hero sections or prominent content blocks — creates a sense of depth and calm |

## Tokens — Typography

### TWK Lausanne — Primary typeface for body text, links, and general UI elements. Its clean, geometric forms maintain clarity and a strong structural rhythm across various weights and sizes. · `--font-twk-lausanne`
- **Weights:** 400, 700
- **Sizes:** 12px, 16px, 20px, 24px, 26px, 32px, 40px
- **Line height:** 1.10, 1.13, 1.20, 1.23, 1.40
- **Letter spacing:** normal
- **Role:** Primary typeface for body text, links, and general UI elements. Its clean, geometric forms maintain clarity and a strong structural rhythm across various weights and sizes.

### TWK Lausanne — Signature display typeface for impactful headlines. The slight negative letter spacing at larger sizes gives it a distinct, confident, and refined presence without shouting. · `--font-twk-lausanne`
- **Weights:** 400
- **Sizes:** 50px, 60px, 80px
- **Line height:** 1.00
- **Letter spacing:** -0.04, -0.033, -0.025
- **Role:** Signature display typeface for impactful headlines. The slight negative letter spacing at larger sizes gives it a distinct, confident, and refined presence without shouting.

### Neo Sans Pro — Secondary typeface used for smaller, highly legible UI labels and navigational links. Its slightly wider tracking ensures tiny text remains distinct and clear, complementing the narrower Lausanne. · `--font-neo-sans-pro`
- **Weights:** 400
- **Sizes:** 10px, 20px
- **Line height:** 1.20, 1.50, 2.00, 3.00
- **Letter spacing:** 0.16, 0.32
- **Role:** Secondary typeface used for smaller, highly legible UI labels and navigational links. Its slightly wider tracking ensures tiny text remains distinct and clear, complementing the narrower Lausanne.

### Arial — Fallback typeface or specific legacy UI elements, providing universal browser compatibility for certain button labels where specific font rendering might be critical. · `--font-arial`
- **Weights:** 400
- **Sizes:** 13px
- **Line height:** 1.20
- **Letter spacing:** normal
- **Role:** Fallback typeface or specific legacy UI elements, providing universal browser compatibility for certain button labels where specific font rendering might be critical.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.5 | 0.16px | `--text-caption` |
| body | 16px | 1.2 | — | `--text-body` |
| subheading | 20px | 1.2 | — | `--text-subheading` |
| heading-sm | 24px | 1.23 | — | `--text-heading-sm` |
| heading | 40px | 1.1 | — | `--text-heading` |
| heading-lg | 50px | 1 | -0.04px | `--text-heading-lg` |
| display | 80px | 1 | -0.025px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** spacious

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 5 | 5px | `--spacing-5` |
| 9 | 9px | `--spacing-9` |
| 10 | 10px | `--spacing-10` |
| 20 | 20px | `--spacing-20` |
| 22 | 22px | `--spacing-22` |
| 30 | 30px | `--spacing-30` |
| 40 | 40px | `--spacing-40` |
| 45 | 45px | `--spacing-45` |
| 50 | 50px | `--spacing-50` |
| 60 | 60px | `--spacing-60` |
| 100 | 100px | `--spacing-100` |
| 150 | 150px | `--spacing-150` |
| 210 | 210px | `--spacing-210` |

### Border Radius

| Element | Value |
|---------|-------|
| links | 20px |

### Layout

- **Section gap:** 50px
- **Card padding:** 40px
- **Element gap:** 9px

## Components

### Ghost Navigation Link
**Role:** Main navigation items and secondary actions.

Text link with no background, uses 'Canvas White' (#ffffff) for text. No padding, no border. Appears as pure text link within dark backgrounds.

### Outlined Brand Action Button
**Role:** Primary calls to action with an understated, elegant visual weight.

Transparent background button with a 'Astral Deep' (#1b2978) border. Text color is also 'Astral Deep' (#1b2978). No border-radius. Padding is 0px.

### Ghost Brand Action Button (Light Text)
**Role:** Primary calls to action on dark backgrounds, acting as ghost buttons.

Transparent background button with a 'Canvas White' (#ffffff) border. Text color is 'Canvas White' (#ffffff). No border-radius. Padding is 0px.

## Do's and Don'ts

### Do
- Use 'Canvas White' (#ffffff) for primary text on dark backgrounds to maintain high contrast and clarity.
- Apply 'Astral Deep' (#1b2978) as a subtle border for interactive elements that require a brand accent without being overtly colored.
- Prioritize TWK Lausanne for headlines and main body copy, adjusting letter spacing at larger sizes as specified.
- Implement Neo Sans Pro for small UI labels and navigation links, leveraging its wider letter spacing (0.16em at 10px, 0.32em at 20px) for readability.
- Maintain a spacious layout with 50px vertical section gaps and 9px element gaps, focusing on visual breathing room.
- Use no border-radius for buttons, but apply 20px radius to general links to subtly differentiate interactive types.
- Employ the 'Nebula Gradient' for hero sections or significant visual blocks to establish an immersive atmosphere.

### Don't
- Avoid using solid color fills for primary buttons; instead, use outlined or ghost button styles to retain design lightness.
- Do not deviate from the specified negative letter spacing for display headlines in TWK Lausanne, as it's a key brand identifier.
- Refrain from introducing additional bright accent colors; stick to the established 'Astral Deep' (#1b2978), 'Aqua Whisper' (#75cdd6), and 'Sky Veil' (#579dc0) palette.
- Do not use heavy shadows or overly dimensional elements; the design emphasizes flat surfaces with occasional soft gradients.
- Avoid dense information blocks; maintain the spacious page model with ample whitespace around content.
- Do not use generic system fonts when TWK Lausanne or Neo Sans Pro are available; their specific characteristics are integral to the brand identity.

## Imagery

The visual language relies on a single evocative, high-key portrait photograph of a person, used as a full-bleed hero background, creating a sense of introspection and calm. Imagery is not frequently used, prioritizing atmospheric backdrops over descriptive illustrations or product shots. Icons are minimal, monochromatic, and outlined, reinforcing the understated digital aesthetic. The overall density is image-light, focusing on UI and text with strong background gradients providing visual interest.

## Layout

The page uses a maximum content width that is not explicitly constrained, allowing content to stretch across the viewport while maintaining central alignment. The hero section is full-bleed, featuring a dramatic photographic background with centered, large headlines. Sections follow a consistent vertical rhythm with 50px gaps. Content often presents as centered stacks or simple text blocks, with very sparse visual elements. Navigation consists of a minimal top-bar with a few text links. The layout emphasizes spaciousness and calm rather than compact information density.

## Agent Prompt Guide

Quick Color Reference:
text: #ffffff
background: #000000 (for hero sections), #75cdd6 (for soft background wash)
border: #1b2978
accent: #75cdd6
primary action: #1b2978 (outlined action border)

Example Component Prompts:
1. Create a hero section: 'Nebula Gradient' background from rgb(42, 57, 142) to rgb(85, 102, 197). Headline 'Empower your mental health journey' in TWK Lausanne at 80px weight 400, 'Canvas White' text, letter-spacing -0.025em. Below, an 'Outlined Brand Action Button' with 'Astral Deep' border and text, 0px padding, no border-radius, labeled 'START YOUR JOURNEY'.
2. Design a feature description block: 'Void Black' background. Heading 'Innovating the future' in TWK Lausanne at 40px weight 700, 'Canvas White' text. Body text 'Through the seamless integration...' in TWK Lausanne at 16px weight 400, 'Canvas White' text. Use 50px sectionGap above and below.
3. Create a navigational element: Text 'VISION' in Neo Sans Pro at 10px weight 400, 'Canvas White' text, letter-spacing 0.16em. This link should have a 20px border-radius if it were to have a background.

## Similar Brands

- **Calm (App)** — Shares a focus on mental well-being with serene, often blue, visual themes and calming photography.
- **Headspace** — Utilizes a minimalist aesthetic to convey tranquility and clarity, often with simple typography and clean layouts.
- **Stripe** — Employs clean, modern typography and a highly structured layout with controlled use of color, often with strong header imagery.
- **Linear** — Features a dark mode-first approach with sharp typography, subtle accent colors, and a focus on functional UI elements.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-astral-deep: #1b2978;
  --color-digital-mist: #7488a5;
  --color-sapphire-gaze: #19366c;
  --color-sky-veil: #579dc0;
  --color-focus-shadow: #466187;
  --color-aqua-whisper: #75cdd6;
  --color-canvas-white: #ffffff;
  --color-void-black: #000000;
  --color-nebula-gradient: #2a3980;
  --gradient-nebula-gradient: linear-gradient(174deg, rgb(42, 57, 142) 5%, rgb(85, 102, 197) 100%);

  /* Typography — Font Families */
  --font-twk-lausanne: 'TWK Lausanne', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-neo-sans-pro: 'Neo Sans Pro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --tracking-caption: 0.16px;
  --text-body: 16px;
  --leading-body: 1.2;
  --text-subheading: 20px;
  --leading-subheading: 1.2;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.23;
  --text-heading: 40px;
  --leading-heading: 1.1;
  --text-heading-lg: 50px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -0.04px;
  --text-display: 80px;
  --leading-display: 1;
  --tracking-display: -0.025px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-9: 9px;
  --spacing-10: 10px;
  --spacing-20: 20px;
  --spacing-22: 22px;
  --spacing-30: 30px;
  --spacing-40: 40px;
  --spacing-45: 45px;
  --spacing-50: 50px;
  --spacing-60: 60px;
  --spacing-100: 100px;
  --spacing-150: 150px;
  --spacing-210: 210px;

  /* Layout */
  --section-gap: 50px;
  --card-padding: 40px;
  --element-gap: 9px;

  /* Border Radius */
  --radius-2xl: 20px;

  /* Named Radii */
  --radius-links: 20px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-astral-deep: #1b2978;
  --color-digital-mist: #7488a5;
  --color-sapphire-gaze: #19366c;
  --color-sky-veil: #579dc0;
  --color-focus-shadow: #466187;
  --color-aqua-whisper: #75cdd6;
  --color-canvas-white: #ffffff;
  --color-void-black: #000000;
  --color-nebula-gradient: #2a3980;

  /* Typography */
  --font-twk-lausanne: 'TWK Lausanne', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-neo-sans-pro: 'Neo Sans Pro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --tracking-caption: 0.16px;
  --text-body: 16px;
  --leading-body: 1.2;
  --text-subheading: 20px;
  --leading-subheading: 1.2;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.23;
  --text-heading: 40px;
  --leading-heading: 1.1;
  --text-heading-lg: 50px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -0.04px;
  --text-display: 80px;
  --leading-display: 1;
  --tracking-display: -0.025px;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-9: 9px;
  --spacing-10: 10px;
  --spacing-20: 20px;
  --spacing-22: 22px;
  --spacing-30: 30px;
  --spacing-40: 40px;
  --spacing-45: 45px;
  --spacing-50: 50px;
  --spacing-60: 60px;
  --spacing-100: 100px;
  --spacing-150: 150px;
  --spacing-210: 210px;

  /* Border Radius */
  --radius-2xl: 20px;
}
```

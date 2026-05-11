# Eight Sleep — Style Reference
> Midnight Command Center // A dark, immersive interface with pin-prick bright accents, like illuminated controls in a premium device.

**Theme:** dark

Eight Sleep's design evokes a sense of sophisticated, premium technology, akin to a high-end personal device, through its dominant dark surfaces and stark monochromatic palette. The experience is primarily dark, using a deep #121212 background, sharply contrasted by bright white typography and subtle gray accents. A singular vivid violet (#4158ee) serves as the primary accent, appearing sparingly on interactive elements to create precise visual cues without becoming distracting. The design prioritizes visual clarity and focused attention on product features, employing carefully structured dark surfaces rather than relying on heavy shadows or complex color schemes.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#121212` | `--color-midnight-ink` | Primary page background, elevated surfaces, deep section backgrounds — sets a premium, immersive mood. |
| Porcelain White | `#FFFFFF` | `--color-porcelain-white` | Primary text color on dark backgrounds, interactive elements, button backgrounds – provides crisp contrast and highlights key information. |
| Silver Thread | `#808080` | `--color-silver-thread` | Secondary text, subtle borders, inactive states — provides visual hierarchy without harsh contrast. |
| Ash Gray | `#8e8d92` | `--color-ash-gray` | Desaturated text on dark backgrounds, secondary icons, subtle highlights. |
| Graphite | `#363636` | `--color-graphite` | Darker accent text, subtle borders, internal component divisions. |
| Winter Frost | `#F9F8F7` | `--color-winter-frost` | Light background for specific sections or cards within a dark theme to create subtle distinction. |
| Ghost Gray | `#F1F2F4` | `--color-ghost-gray` | Subtle background for UI elements like selected options in a pop-up. |
| Electric Violet | `#4158EE` | `--color-electric-violet` | Primary interactive accent color for links, active states, and calls to action — provides a focused, high-tech glow against dark surfaces. |
| Sky Blue | `#1862FF` | `--color-sky-blue` | Secondary accent for interactive elements or specific highlighted text — shares the energetic quality of Electric Violet. |
| Nightfall Gradient | `radial-gradient(at 120% 45%, rgb(241, 243, 254) 20%, rgb(27, 38, 59) 45%, rgb(9, 11, 18) 55%)` | `--color-nightfall-gradient` | Background for hero sections, creating a deep, enveloping atmosphere. |
| Ocean Blue | `#3f5975` | `--color-ocean-blue` | Subtle background on interactive elements, like selected regions in a modal. |

## Tokens — Typography

### NeueMontreal — Used universally across all text elements from headings to body, links, and buttons. The diverse weights and fine-tuned letter spacing allow for nuanced expression, particularly the subtle negative spacing at large sizes which keeps headlines feeling grounded despite their scale. · `--font-neuemontreal`
- **Substitute:** Inter
- **Weights:** 300, 400, 500, 700
- **Sizes:** 10px, 12px, 14px, 15px, 16px, 17px, 18px, 20px, 22px, 28px, 36px, 44px, 56px, 64px, 115px
- **Line height:** 0.94, 1.00, 1.09, 1.10, 1.20, 1.27, 1.31, 1.33, 1.40, 1.50, 1.70, 1.92
- **Letter spacing:** -0.0200em at 115px, 0.0010em at 18px, 0.0040em at 15px, 0.0080em at 12px, 0.0090em at 14px, 0.0100em at 10px, 0.0110em at 17px, 0.0500em at 22px, 0.1250em at 16px, 0.1330em at 20px, 0.1430em at 28px
- **Role:** Used universally across all text elements from headings to body, links, and buttons. The diverse weights and fine-tuned letter spacing allow for nuanced expression, particularly the subtle negative spacing at large sizes which keeps headlines feeling grounded despite their scale.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.4 | 0.01px | `--text-caption` |
| body | 16px | 1.5 | 0.125px | `--text-body` |
| subheading | 18px | 1.5 | 0.001px | `--text-subheading` |
| heading-sm | 28px | 1.27 | 0.143px | `--text-heading-sm` |
| heading | 36px | 1.2 | 0.004px | `--text-heading` |
| heading-lg | 44px | 1.1 | -0.02px | `--text-heading-lg` |
| display | 64px | 0.94 | -0.02px | `--text-display` |

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
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 28 | 28px | `--spacing-28` |
| 32 | 32px | `--spacing-32` |
| 36 | 36px | `--spacing-36` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 60 | 60px | `--spacing-60` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 92 | 92px | `--spacing-92` |
| 112 | 112px | `--spacing-112` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 12px |
| chips | 9999px |
| inputs | 0px |
| buttons | 4px |
| default | 8px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| md | `rgba(0, 0, 0, 0.05) 2px 2px 12px 0px` | `--shadow-md` |

### Layout

- **Section gap:** 64px
- **Element gap:** 16px

## Components

### Ghost Navigation Link
**Role:** Primary navigation, secondary CTAs

Transparent background, 'Porcelain White' text, 2px bottom padding, font NeueMontreal weight 400, 16px text, line height 1.5. No border default.

### Primary Navigation Product Link
**Role:** Top-level navigation items

Transparent background, 'Porcelain White' text, NeueMontreal 16px, weight 400, 2px top/bottom padding.

### Primary CTA Button
**Role:** Main call to action

Solid 'Porcelain White' background, 'Midnight Ink' text, NeueMontreal 16px, weight 500. Border radius 4px. Padding 15px top/bottom, 24px left/right.

### Footer Link
**Role:** Informational links in footer

Transparent background, 'Silver Thread' text, NeueMontreal 14px, weight 400. No border. Subtle hover effects are implied but not explicitly defined in provided data.

### Region Selection Card (Modal)
**Role:** Interactive list item in a modal

Transparent background, 'Porcelain White' text, NeueMontreal 16px, weight 400. No box shadow or border by default. On selection, background becomes 'Ocean Blue' (#3f5975).

### Modal Input Field
**Role:** Single-line text input

Transparent background, 'Porcelain White' text and border, NeueMontreal 16px, weight 400. No border radius. Bottom border style 'solid' 1px 'Porcelain White'.

### Carousel Navigation Dot
**Role:** Pagination for image carousels or feature sliders

Circular shape (50% border-radius), transparent background, uses 'Ash Gray' (#8e8d92) for inactive states, 'Electric Violet' (#4158EE) for active. No shadow.

### Quiz Selection Button
**Role:** Interactive options within a quiz or survey

Background 'Ghost Gray' (#F1F2F4), 'Midnight Ink' text, NeueMontreal 16px, weight 400. Border radius 4px. Padding 15px top/bottom, 24px left/right. The example shows these with no border.

### Feature Highlight Card
**Role:** Displays key product features or benefits

Background 'Winter Frost' (#F9F8F7), 'Midnight Ink' text. Border-radius 12px. No explicit padding or shadow in the provided data.

## Do's and Don'ts

### Do
- Use 'Midnight Ink' (#121212) as the default background for all primary page sections and modals to maintain the dark theme.
- Prioritize 'Porcelain White' (#FFFFFF) for all body text, headings, and primary interactive elements on dark backgrounds to ensure high contrast.
- Apply 'Electric Violet' (#4158EE) exclusively to key interactive elements like links, buttons, and active states to guide user focus.
- Employ NeueMontreal weight 300 for display-sized headings (e.g., 64px, 115px) to achieve a sophisticated, whisper-like authority.
- Utilize a 4px border-radius for all primary buttons and interactive inputs, and 12px for cards to establish a consistent shape language.
- Maintain generous vertical spacing with `sectionGap` at `64px` and component element spacing with `elementGap` at `16px`.
- Use text links that appear as 'Porcelain White' on dark backgrounds or 'Midnight Ink' on light backgrounds for standard interactions, reserving 'Electric Violet' for emphasis.

### Don't
- Avoid using multiple vibrant colors; restrict accent colors primarily to 'Electric Violet' (`#4158EE`) and its close variant 'Sky Blue' (`#1862FF`).
- Do not use box shadows for general elevation; rely on background color changes or subtle outlines to indicate depth.
- Do not use aggressive, heavy typography weights like 700 for large headings; the brand emphasizes subtlety through lighter weights.
- Avoid circular or aggressively rounded elements other than specific small icons or carousel indicators (9999px radius).
- Do not deviate from the NeueMontreal font family; it is central to the visual identity.
- Do not use generic gray tones for primary text on dark backgrounds; always use 'Porcelain White' for high readability.

## Elevation

- **Card/Modal:** `box-shadow: rgba(0, 0, 0, 0.05) 2px 2px 12px 0px`

## Imagery

Imagery primarily features product shots and lifestyle photography. Product shots include tightly cropped, pristine images of the 'Pod' device, often on a neutral background or integrated into a clean bedroom aesthetic. Lifestyle photography is staged, showcasing individuals interacting with the product in a visually appealing, aspirational bedroom setting, focusing on comfort and technology. Images are generally contained, not full-bleed, with sharp rectangular edges. There is a strong emphasis on the product's integration into sophisticated domestic environments. Icons are monochrome, often using 'Ash Gray' or 'Porcelain White', with simple, clean outlines or fills.

## Layout

The overarching layout is full-bleed, particularly for hero sections and dark backgrounds, providing an expansive, immersive feel. Content is primarily centered or arranged in a two-column text-left/image-right or image-left/text-right alternating pattern. The hero section often features a large, centered headline over a dark background (sometimes with a gradient), immediately establishing the product's value proposition. Sections maintain a consistent vertical rhythm, with generous `64px` gaps between major content blocks. There are instances of multi-column card grids for features, typically 3 columns. The navigation is a sticky top bar, minimal, with right-aligned utility links and a primary CTA, keeping the focus on the main content area.

## Agent Prompt Guide

### Quick Color Reference
- **Text (on dark):** #FFFFFF
- **Background (primary):** #121212
- **CTA Accent:** #4158EE
- **Border (subtle):** #808080
- **Card Background (light):** #F9F8F7

### 3-5 Example Component Prompts
1. **Create a hero section:** Full-bleed `Midnight Ink` background with `Nightfall Gradient` subtly overlayed. Centered headline 'Un descanso profundo. Que se adapta a ti.' in `Porcelain White`, NeueMontreal 64px, weight 300, letter-spacing -0.0200em. Below, a `Primary CTA Button` saying 'Conoce el Pod'.
2. **Generate a 'Quiz Selection Button':** Text 'Tengo calor o frío' in `Midnight Ink`, NeueMontreal 16px, weight 400. Background `Ghost Gray` (#F1F2F4), border-radius 4px. Padding 15px vertical, 24px horizontal.
3. **Design a navigation bar:** `Midnight Ink` (#121212) background. Left-aligned brand logo (image placeholder). Right-aligned `Ghost Navigation Links` for 'Cómo funciona el Pod', 'Accesorios', and 'Reseñas'. A `Primary Navigation Product Link` for 'Compra el Pod' in `Porcelain White`.
4. **Create a card for product features:** Background `Winter Frost` (#F9F8F7), border-radius 12px. Headline 'Pruébalo durante 30 noches, sin riesgos' in `Midnight Ink`, NeueMontreal 28px, weight 500, line-height 1.27. Below, supporting text in `Midnight Ink`, NeueMontreal 16px, weight 400.
5. **Build a Region Selection Card in a modal:** Background `Midnight Ink` (#121212). List item background `Ocean Blue` (#3f5975) for a selected 'Spain - Español' option. Other options use transparent background. All text `Porcelain White`, NeueMontreal 16px, weight 400. Padding 15x vertical, 24x horiztonal.

## Similar Brands

- **Apple** — Shares a use of high-contrast black and white, subtle material changes for depth, and limited, precise color accents.
- **Oura Ring** — Similar focus on premium, minimalist product presentation, dominant dark themes, and a single vibrant accent color.
- **Nest** — Employs an aesthetic of refined technology for the home, with clean typography and a muted, tech-forward color palette.
- **Whoop** — Utilizes dark UI, strong typography, and limited color to emphasize data and performance, similar to a high-end personal device interface.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #121212;
  --color-porcelain-white: #FFFFFF;
  --color-silver-thread: #808080;
  --color-ash-gray: #8e8d92;
  --color-graphite: #363636;
  --color-winter-frost: #F9F8F7;
  --color-ghost-gray: #F1F2F4;
  --color-electric-violet: #4158EE;
  --color-sky-blue: #1862FF;
  --color-nightfall-gradient: #1B263B;
  --gradient-nightfall-gradient: radial-gradient(at 120% 45%, rgb(241, 243, 254) 20%, rgb(27, 38, 59) 45%, rgb(9, 11, 18) 55%);
  --color-ocean-blue: #3f5975;

  /* Typography — Font Families */
  --font-neuemontreal: 'NeueMontreal', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.4;
  --tracking-caption: 0.01px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: 0.125px;
  --text-subheading: 18px;
  --leading-subheading: 1.5;
  --tracking-subheading: 0.001px;
  --text-heading-sm: 28px;
  --leading-heading-sm: 1.27;
  --tracking-heading-sm: 0.143px;
  --text-heading: 36px;
  --leading-heading: 1.2;
  --tracking-heading: 0.004px;
  --text-heading-lg: 44px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.02px;
  --text-display: 64px;
  --leading-display: 0.94;
  --tracking-display: -0.02px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-92: 92px;
  --spacing-112: 112px;

  /* Layout */
  --section-gap: 64px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 20px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-cards: 12px;
  --radius-chips: 9999px;
  --radius-inputs: 0px;
  --radius-buttons: 4px;
  --radius-default: 8px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.05) 2px 2px 12px 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #121212;
  --color-porcelain-white: #FFFFFF;
  --color-silver-thread: #808080;
  --color-ash-gray: #8e8d92;
  --color-graphite: #363636;
  --color-winter-frost: #F9F8F7;
  --color-ghost-gray: #F1F2F4;
  --color-electric-violet: #4158EE;
  --color-sky-blue: #1862FF;
  --color-nightfall-gradient: #1B263B;
  --color-ocean-blue: #3f5975;

  /* Typography */
  --font-neuemontreal: 'NeueMontreal', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.4;
  --tracking-caption: 0.01px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: 0.125px;
  --text-subheading: 18px;
  --leading-subheading: 1.5;
  --tracking-subheading: 0.001px;
  --text-heading-sm: 28px;
  --leading-heading-sm: 1.27;
  --tracking-heading-sm: 0.143px;
  --text-heading: 36px;
  --leading-heading: 1.2;
  --tracking-heading: 0.004px;
  --text-heading-lg: 44px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.02px;
  --text-display: 64px;
  --leading-display: 0.94;
  --tracking-display: -0.02px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-92: 92px;
  --spacing-112: 112px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 20px;
  --radius-full: 9999px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.05) 2px 2px 12px 0px;
}
```

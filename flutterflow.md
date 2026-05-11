# FlutterFlow — Style Reference
> Deep Space Command Center. Expansive dark surfaces punctuated by vivid violet glows, like stars in a night sky.

**Theme:** dark

This design system evokes a 'deep space command center' atmosphere, achieved through a predominantly dark mode with complex, subtle gradients creating depth and energy. The primary visual tension arises from the interplay of smooth, expansive dark surfaces and bursts of vivid, luminous violet. Type is restrained, leveraging specific letter-spacing for refined legibility, while rounded corners on interactive elements provide a friendly counterpoint to the overall high-tech mood.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#060311` | `--color-midnight-ink` | Primary background, deep cards, text on light elements. This foundational dark sets the mood. |
| Slate Deep | `#161320` | `--color-slate-deep` | Secondary background, UI panels and subtle card elevations. A slightly lighter dark for hierarchy. |
| White Star | `#ffffff` | `--color-white-star` | Primary text, critical UI elements, button text on dark backgrounds. High contrast against dark surfaces. |
| Mist Gray | `#9ba1ae` | `--color-mist-gray` | Secondary text, subtle descriptions, disabled states. Provides gentle contrast and visual relief. |
| Dark Star | `#333333` | `--color-dark-star` | Tertiary text, less prominent links and subtle accents. |
| Deep Violet | `#5800fd` | `--color-deep-violet` | Interactive elements, primary links, active states, key visual accents. Its vividness signifies importance. |
| Cosmic Indigo | `#2415c6` | `--color-cosmic-indigo` | Illustrative elements, background gradients. A cooler, more muted violet that adds depth. |
| Dawn Violet | `#7066ed` | `--color-dawn-violet` | Illustrative elements, subtle highlights, background gradients. A brighter, more ethereal violet. |
| Flare Violet | `#882fe8` | `--color-flare-violet` | Minor illustrative accents. Used sparingly for visual pop. |
| Action Violet | `#6d5ef9` | `--color-action-violet` | Background for certain interactive states or containers. |
| Hero Gradient Outer | `radial-gradient(circle farthest-side at 0px -30%, rgb(75, 57, 239), rgba(6, 3, 17, 0) 84%)` | `--color-hero-gradient-outer` | Large background sections, hero banners. Creates a subtle radial emanation, drawing focus without overwhelming. |
| Hero Gradient Inner | `radial-gradient(circle closest-corner at 100% 0px, rgb(36, 26, 125), rgb(75, 57, 239))` | `--color-hero-gradient-inner` | Large background sections, hero banners. Creates a subtle radial emanation, focusing on specific points. |
| Dividing Gradient | `linear-gradient(rgb(22, 19, 32), rgb(6, 3, 17))` | `--color-dividing-gradient` | Used for smooth transitions between dark sections, providing a subtle texture. |

## Tokens — Typography

### Urbanist — This sans-serif is the primary display and body font. Its geometric structure provides a clean, modern feel, while varied letter-spacing at display sizes adds a touch of precision and sophistication, making large headlines feel carefully crafted rather than shouting. · `--font-urbanist`
- **Substitute:** system-ui
- **Weights:** 400, 500, 600
- **Sizes:** 14px, 16px, 18px, 20px, 24px, 32px, 72px, 100px, 120px
- **Line height:** 1.00, 1.20, 1.30, 1.50, 1.60
- **Letter spacing:** -0.045em at 120px, -0.038em at 100px, -0.03em at 72px, normal at body sizes
- **Role:** This sans-serif is the primary display and body font. Its geometric structure provides a clean, modern feel, while varied letter-spacing at display sizes adds a touch of precision and sophistication, making large headlines feel carefully crafted rather than shouting.

### Inter — Used for smaller text, navigation, and detailed information. Its higher letter-spacing values ensure readability at smaller sizes, especially crucial in functional UI elements where clarity is paramount. · `--font-inter`
- **Substitute:** system-ui
- **Weights:** 300, 400, 700
- **Sizes:** 13px, 14px, 16px, 18px, 20px, 24px
- **Line height:** 1.50, 1.60
- **Letter spacing:** 0.09em at 24px, 0.057em at 20px, 0.05em at 18px, normal at body sizes
- **Role:** Used for smaller text, navigation, and detailed information. Its higher letter-spacing values ensure readability at smaller sizes, especially crucial in functional UI elements where clarity is paramount.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 13px | 1.5 | 0.5px | `--text-caption` |
| body | 16px | 1.6 | — | `--text-body` |
| subheading | 18px | 1.5 | 0.57px | `--text-subheading` |
| heading-sm | 20px | 1.5 | 0.9px | `--text-heading-sm` |
| heading | 24px | 1.3 | — | `--text-heading` |
| heading-lg | 32px | 1.2 | — | `--text-heading-lg` |
| display | 72px | 1 | -0.03px | `--text-display` |
| display-lg | 100px | 1 | -0.038px | `--text-display-lg` |
| display-xl | 120px | 1 | -0.045px | `--text-display-xl` |

## Tokens — Spacing & Shapes

**Base unit:** 8px

**Density:** spacious

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
| 96 | 96px | `--spacing-96` |
| 112 | 112px | `--spacing-112` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 24px |
| links | 16px |
| buttons | 1440px |
| minorElements | 12px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| lg | `rgba(0, 0, 0, 0.2) 0px 4px 24px 20px` | `--shadow-lg` |

### Layout

- **Section gap:** 48px
- **Card padding:** 40px
- **Element gap:** 24px

## Components

### Text Only Button (Nav)
**Role:** Navigation and secondary actions

backgroundColor=transparent, color=#ffffff, border=none, borderRadius=0px, paddingY=40px, paddingX=16px. Used for subtle, non-intrusive interactive elements.

### Basic Card
**Role:** Information grouping without visual distinction

backgroundColor=transparent, borderRadius=0px, boxShadow=none, padding=0px. A structural container without presentational styling.

### Deep Card
**Role:** Content sections needing clear boundaries and subtle elevation

backgroundColor=#060311, borderRadius=24px, boxShadow=none, padding=0px. Emphasizes content through distinct, rounded dark surfaces.

### Shadowed Card
**Role:** Interactive or highlighted cards requiring significant visual lift

backgroundColor=transparent, borderRadius=20%, boxShadow=rgba(0, 0, 0, 0.2) 0px 4px 24px 20px, padding=0px. The circular radius with a large, soft shadow makes this card appear to float prominently.

## Do's and Don'ts

### Do
- Use Midnight Ink (#060311) for primary dark backgrounds and Slate Deep (#161320) for secondary elevated dark surfaces to create depth.
- Apply White Star (#ffffff) consistently for primary text and critical UI elements against dark backgrounds.
- Reserve Deep Violet (#5800fd) for interactive elements, links, and active states to highlight interaction points.
- Ensure large headlines (display-xl and display-lg) use Urbanist with the specified negative letter-spacing values to maintain a refined visual impact.
- Use a `max-width` on content areas to prevent stretching, maintaining readability and aesthetic balance.
- Round all interactive button elements with a 1440px border-radius to achieve a consistent pill shape and friendly interaction target.

### Don't
- Do not use generic gray tones for interactive elements; all actionable items should leverage Deep Violet (#5800fd) or White Star (#ffffff) for strong visual cues.
- Avoid using box-shadows on cards unless explicitly for the 'Shadowed Card' variant; rely on background color changes for surface distinction.
- Do not deviate from the specified type scale and letter-spacing for headlines; these choices define the distinctive typographic voice.
- Do not introduce highly saturated colors outside the brand's violet palette, as they will clash with the established atmosphere.
- Avoid small, square button shapes; instead, use either the Text Only Button or the Pill Button variants for consistency.

## Elevation

- **Shadowed Card:** `rgba(0, 0, 0, 0.2) 0px 4px 24px 20px`

## Imagery

The visual language is a blend of abstract graphics, product screenshots, and minimal, geometric icons. Product screenshots are contained within device mockups or card elements, often overlapping with the dark UI, making them feel integrated. Illustrations lean towards gradients of brand violets, abstract shapes, and subtle glow effects, contributing to the 'deep space' feel. Icons are typically monocolor, filled, and use the brand's violet or white for interaction. The overall density is balanced, with imagery serving both decorative atmosphere and explanatory content roles, often nestled within the dark, gradient-rich backgrounds.

## Layout

The page primarily uses a full-bleed layout, particularly in hero sections, with content centered within an implied max-width when present. The hero features a large, centered headline over a dark, gradient background. Sections alternate between deep dark backgrounds and areas with more subtle gradients. Content is frequently arranged in multi-column grids or stacked, centered blocks. Feature sections often employ a 2-column text-left/image-right alternating pattern. The navigation is a sticky top bar, providing persistent access without encroaching on content.

## Agent Prompt Guide

**Quick Color Reference:**
- Text (primary): #ffffff (White Star)
- Background (base): #060311 (Midnight Ink)
- CTA (primary action): #5800fd (Deep Violet)
- Border (pill button): #ffffff (White Star)
- Accent (interactive): #5800fd (Deep Violet)

**Example Component Prompts:**
1. Create a Hero Section: Background is a full-bleed radial-gradient(circle farthest-side at 0px -30%, rgb(75, 57, 239), rgba(6, 3, 17, 0) 84%). Centered headline 'Build Better. Launch Faster.' using Urbanist, size 120px, weight 400, color #ffffff, letter-spacing -0.045em. Below it, a Pill Button (Navigation) 'Start for Free': transparent background, white text (#ffffff), 1px white border, 1440px border-radius, paddingY 40px, paddingX 25.6px.
2. Design a Feature Card: Background #060311 (Midnight Ink), 24px border-radius. Inside, a heading 'Visual Development' using Urbanist, size 24px, weight 500, color #ffffff. Body text using Inter, size 16px, weight 400, color #9ba1ae. Card padding should be 40px on all sides.
3. Implement a Navigation Bar: Background #060311. Left aligned logo. Right aligned navigation items using Urbanist, size 16px, weight 400, color #ffffff. Include a 'Log in' button as Text Only Button and 'Start for Free' as a Pill Button (Navigation).

## Similar Brands

- **Vercel** — Shares a strong dark-mode aesthetic with nuanced grays and a focus on code/developer tools, often utilizing vibrant single-color accents effectively.
- **Linear** — Exhibits a similar commitment to refined dark-mode UI, detailed typography with specific letter-spacing, and strategic use of color for functional elements rather than purely decorative ones.
- **Github** — Employs a deep dark theme with similar gradients and a focus on clean, functional UI elements for a developer audience, using vibrant brand colors for key interactions.
- **Raycast** — Visual similarity in leveraging deep, almost black backgrounds accented by subtle cool-toned color highlights and a clear emphasis on functional, minimalist UI components.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #060311;
  --color-slate-deep: #161320;
  --color-white-star: #ffffff;
  --color-mist-gray: #9ba1ae;
  --color-dark-star: #333333;
  --color-deep-violet: #5800fd;
  --color-cosmic-indigo: #2415c6;
  --color-dawn-violet: #7066ed;
  --color-flare-violet: #882fe8;
  --color-action-violet: #6d5ef9;
  --color-hero-gradient-outer: #4b39ef;
  --gradient-hero-gradient-outer: radial-gradient(circle farthest-side at 0px -30%, rgb(75, 57, 239), rgba(6, 3, 17, 0) 84%);
  --color-hero-gradient-inner: #4b39ef;
  --gradient-hero-gradient-inner: radial-gradient(circle closest-corner at 100% 0px, rgb(36, 26, 125), rgb(75, 57, 239));
  --color-dividing-gradient: #161320;
  --gradient-dividing-gradient: linear-gradient(rgb(22, 19, 32), rgb(6, 3, 17));

  /* Typography — Font Families */
  --font-urbanist: 'Urbanist', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 1.5;
  --tracking-caption: 0.5px;
  --text-body: 16px;
  --leading-body: 1.6;
  --text-subheading: 18px;
  --leading-subheading: 1.5;
  --tracking-subheading: 0.57px;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.5;
  --tracking-heading-sm: 0.9px;
  --text-heading: 24px;
  --leading-heading: 1.3;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1.2;
  --text-display: 72px;
  --leading-display: 1;
  --tracking-display: -0.03px;
  --text-display-lg: 100px;
  --leading-display-lg: 1;
  --tracking-display-lg: -0.038px;
  --text-display-xl: 120px;
  --leading-display-xl: 1;
  --tracking-display-xl: -0.045px;

  /* Typography — Weights */
  --font-weight-light: 300;
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
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-112: 112px;

  /* Layout */
  --section-gap: 48px;
  --card-padding: 40px;
  --element-gap: 24px;

  /* Border Radius */
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-full: 1440px;

  /* Named Radii */
  --radius-cards: 24px;
  --radius-links: 16px;
  --radius-buttons: 1440px;
  --radius-minorelements: 12px;

  /* Shadows */
  --shadow-lg: rgba(0, 0, 0, 0.2) 0px 4px 24px 20px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #060311;
  --color-slate-deep: #161320;
  --color-white-star: #ffffff;
  --color-mist-gray: #9ba1ae;
  --color-dark-star: #333333;
  --color-deep-violet: #5800fd;
  --color-cosmic-indigo: #2415c6;
  --color-dawn-violet: #7066ed;
  --color-flare-violet: #882fe8;
  --color-action-violet: #6d5ef9;
  --color-hero-gradient-outer: #4b39ef;
  --color-hero-gradient-inner: #4b39ef;
  --color-dividing-gradient: #161320;

  /* Typography */
  --font-urbanist: 'Urbanist', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 1.5;
  --tracking-caption: 0.5px;
  --text-body: 16px;
  --leading-body: 1.6;
  --text-subheading: 18px;
  --leading-subheading: 1.5;
  --tracking-subheading: 0.57px;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.5;
  --tracking-heading-sm: 0.9px;
  --text-heading: 24px;
  --leading-heading: 1.3;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1.2;
  --text-display: 72px;
  --leading-display: 1;
  --tracking-display: -0.03px;
  --text-display-lg: 100px;
  --leading-display-lg: 1;
  --tracking-display-lg: -0.038px;
  --text-display-xl: 120px;
  --leading-display-xl: 1;
  --tracking-display-xl: -0.045px;

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
  --spacing-96: 96px;
  --spacing-112: 112px;

  /* Border Radius */
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-full: 1440px;

  /* Shadows */
  --shadow-lg: rgba(0, 0, 0, 0.2) 0px 4px 24px 20px;
}
```

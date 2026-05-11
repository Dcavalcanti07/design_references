# Safepal — Style Reference
> Cosmic digital frontier

**Theme:** dark

SafePal evokes a cosmic, secure digital frontier with its deep violet and green-accented surfaces. The primary aesthetic relies on contrasting a dark, rich background with crisp sans-serif typography and soft, rounded UI elements. Generous card padding and large button radii create an approachable, reassuring feel, while vivid green accents highlight interactive elements, suggesting growth and reliability within the expansive digital landscape.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Deep Space | `linear-gradient(124.15deg, rgb(13, 11, 51) 0%, rgb(75, 62, 211) 218.07%)` | `--color-deep-space` | Primary text, deep surface elements, button text on vivid green; Subtle deep background gradient, providing texture and depth |
| Cloud White | `#ffffff` | `--color-cloud-white` | Main canvas, primary text on dark backgrounds, button backgrounds |
| Ash Gray | `#f7f6ff` | `--color-ash-gray` | Card backgrounds, secondary surface areas, subtle borders |
| Slate | `#666666` | `--color-slate` | Secondary text, muted iconography, disabled states |
| Twilight Indigo | `#4a21ef` | `--color-twilight-indigo` | Header background, abstract graphics, brand highlights. This deep violet provides depth and a mystic quality to backgrounds |
| Emerald Growth | `#79efbd` | `--color-emerald-growth` | Primary action button backgrounds, active states, key interactive indicators. Represents positive action and growth |
| Jade Outline | `#18d26e` | `--color-jade-outline` | Outline for ghost buttons and interactive element borders. Its vibrant nature draws attention to selectable regions |
| Gradient Cosmos | `linear-gradient(154.24deg, rgb(191, 255, 228) 11.19%, rgb(74, 33, 239) 62.38%)` | `--color-gradient-cosmos` | Decorative background gradient used in hero sections, transitioning from light green to deep violet |

## Tokens — Typography

### AlibabaPuHuiTi-2 — Primary typeface for all text elements. The range of bold weights (700-1000) provides strong hierarchy and impact for headlines, while the consistent family supports a unified visual voice. · `--font-alibabapuhuiti-2`
- **Substitute:** Open Sans
- **Weights:** 400, 700, 800, 900, 1000
- **Sizes:** 12px, 14px, 16px, 18px, 24px, 32px, 48px, 80px, 137px
- **Line height:** 1.00, 1.17, 1.20, 1.50, 1.56, 1.57, 1.60
- **Letter spacing:** normal
- **Role:** Primary typeface for all text elements. The range of bold weights (700-1000) provides strong hierarchy and impact for headlines, while the consistent family supports a unified visual voice.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.5 | — | `--text-caption` |
| body-sm | 14px | 1.5 | — | `--text-body-sm` |
| body | 16px | 1.5 | — | `--text-body` |
| body-lg | 18px | 1.5 | — | `--text-body-lg` |
| heading-sm | 24px | 1.3 | — | `--text-heading-sm` |
| heading | 32px | 1.3 | — | `--text-heading` |
| heading-lg | 48px | 1.3 | — | `--text-heading-lg` |
| display-sm | 80px | 1.3 | — | `--text-display-sm` |
| display | 137px | 1.3 | — | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 12 | 12px | `--spacing-12` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 36 | 36px | `--spacing-36` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 80 | 80px | `--spacing-80` |
| 100 | 100px | `--spacing-100` |
| 160 | 160px | `--spacing-160` |
| 180 | 180px | `--spacing-180` |
| 200 | 200px | `--spacing-200` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 24px |
| buttons | 100px |
| largeElements | 48px |
| navigationItems | 12px |

### Layout

- **Page max-width:** 1200px
- **Section gap:** 113px
- **Card padding:** 53px
- **Element gap:** 12px

## Components

### Primary Action Button (Emerald)
**Role:** Call to action button for key conversions.

Background: Emerald Growth (#79efbd). Text color: Deep Space (#0d0b33). Border: none. Radius: 100px. Padding: 16px vertical, 24px horizontal. Text is AlibabaPuHuiTi-2, weight 400.

### Secondary Ghost Button (White)
**Role:** Alternative call to action, offering less visual prominence.

Background: transparent. Text color: Cloud White (#ffffff). Border: 1px solid Cloud White (#ffffff). Radius: 100px. Padding: 16px vertical, 24px horizontal. Text is AlibabaPuHuiTi-2, weight 400.

### Tertiary Outline Button (Dark)
**Role:** Low-prominence action button, often for secondary functions.

Background: Cloud White (#ffffff). Text color: Deep Space (#1d1d1d). Border: 1px solid Deep Space (#1d1d1d). Radius: 100px. Padding: 10px vertical, 16px horizontal. Text is AlibabaPuHuiTi-2, weight 400.

### Info Card
**Role:** Container for testimonials, features, or content blocks.

Background: Ash Gray (#f7f6ff). Shadow: none. Radius: 24px. Padding: 53px all sides. Content uses AlibabaPuHuiTi-2 text ranging from Deep Space to Slate.

### Header Navigation Item
**Role:** Top-level navigation link.

Background: transparent. Text color: Cloud White (#ffffff). Radius: 12px. Margin: 5px horizontal. Font: AlibabaPuHuiTi-2 16px, weight 400.

## Do's and Don'ts

### Do
- Prioritize Cloud White (#ffffff) text on dark backgrounds and Deep Space (#0d0b33) on light backgrounds for primary text contrast.
- Use Emerald Growth (#79efbd) exclusively for primary action button backgrounds to denote interactive elements and positive actions.
- Maintain a consistent 100px border-radius for all interactive buttons and tags to reinforce the soft, approachable aesthetic.
- Apply Twilight Indigo (#4a21ef) as a dominant brand color for large background areas or distinctive sections.
- Utilize the AlibabaPuHuiTi-2 font consistently across all type roles, leveraging weights 700-1000 for impactful headings.
- Ensure cards adhere to an Ash Gray (#f7f6ff) background and a 24px corner radius with 53px internal padding.
- Employ Jade Outline (#18d26e) for borders of interactive elements when a ghost or outlined style button is preferred.

### Don't
- Do not introduce sharp corners or small radii; maintain soft aesthetics with 24px, 48px, or 100px radii.
- Avoid using multiple high-saturation colors on the same screen; restrict vibrant color usage to Emerald Growth (#79efbd) and Jade Outline (#18d26e) for interactive elements.
- Do not deviate from the AlibabaPuHuiTi-2 font family for any text on the site.
- Do not use dark text colors on Twilight Indigo (#4a21ef) backgrounds; always default to Cloud White (#ffffff) for readability.
- Avoid overly dense layouts; maintain comfortable spacing with a base unit of 4px and significant section gaps of ~113px.
- Do not use box-shadows for elevation; rely on color and border distinctions to separate elements and create hierarchy.
- Resist using Emerald Growth (#79efbd) or Jade Outline (#18d26e) for decorative, non-interactive elements to preserve their functional meaning.

## Imagery

The visual language features stylized isometric 3D illustrations of crypto-related hardware and software, often set against deep violet or gradient backgrounds. These illustrations are detailed, with defined outlines and a consistent color palette that complements the brand colors, highlighting product features. Icons are minimalist, outlined, and monochromatic, used functionally to represent UI actions or categories. Imagery serves to explain product functionality and showcase hardware in a conceptual, futuristic manner rather than through realistic photography or abstract art. The overall density is balanced, allowing the illustrations to be focal points without overwhelming surrounding text.

## Layout

The page primarily uses a max-width contained layout, approximately 1200px, centered on the screen. The hero section is full-bleed, featuring a deep gradient background with a large, centered headline and isometric product illustrations. Sections below the hero alternate between full-bleed deep backgrounds and contained blocks, often using a two-column layout with text on one side and a product visual on the other. Testimonials are presented in a three-column card grid. Vertical rhythm is established through consistent section gaps of approximately 113px. The site utilizes a sticky top navigation bar with clear product and information categories.

## Agent Prompt Guide

Quick Color Reference:
- text: #ffffff (on dark), #0d0b33 (on light)
- background: #0d0b33 (dominant), #f7f6ff (secondary card/surface)
- border: #ffffff (ghost button), #18d26e (outlined action), #1d1d1d (tertiary button)
- accent: #4a21ef (brand highlights), #79efbd (primary action background)
- primary action: #79efbd (filled action)

Example Component Prompts:
- Create a hero section: Gradient Cosmos (#bf_ff_e4) background. Headline 'Own Your Crypto Adventure' in AlibabaPuHuiTi-2, weight 1000, 80px, Cloud White (#ffffff). Below the headline, a Secondary Ghost Button (White) reading 'Discover More'.
- Build a testimonial card: Info Card component with 'Ash Gray' (#f7f6ff) background. Main text in Deep Space (#0d0b33) at 16px AlibabaPuHuiTi-2 weight 400. Name of the author 'John Doe' in Deep Space (#0d0b33), 18px AlibabaPuHuiTi-2 weight 700.
- Create a Primary Action Button: #79efbd background, #1d1d1d text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.

## Similar Brands

- **Ledger** — Similar focus on crypto hardware wallet, dark UI with subtle accents, and isometric product visuals.
- **MetaMask** — Web3/crypto brand with a programmatic UI, often using dark backgrounds and high-contrast elements for app-like feeling.
- **Brave Browser** — Shares a brand aesthetic of security and digital privacy, often using deep blues/purples and clear, functional UI.
- **BlockFi** — Another crypto financial service that uses a dark, clean interface with strong typography and accent colors to highlight value propositions.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-deep-space: #0d0b33;
  --gradient-deep-space: linear-gradient(124.15deg, rgb(13, 11, 51) 0%, rgb(75, 62, 211) 218.07%);
  --color-cloud-white: #ffffff;
  --color-ash-gray: #f7f6ff;
  --color-slate: #666666;
  --color-twilight-indigo: #4a21ef;
  --color-emerald-growth: #79efbd;
  --color-jade-outline: #18d26e;
  --color-gradient-cosmos: #bf_ff_e4;
  --gradient-gradient-cosmos: linear-gradient(154.24deg, rgb(191, 255, 228) 11.19%, rgb(74, 33, 239) 62.38%);

  /* Typography — Font Families */
  --font-alibabapuhuiti-2: 'AlibabaPuHuiTi-2', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-body-lg: 18px;
  --leading-body-lg: 1.5;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.3;
  --text-heading: 32px;
  --leading-heading: 1.3;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.3;
  --text-display-sm: 80px;
  --leading-display-sm: 1.3;
  --text-display: 137px;
  --leading-display: 1.3;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-bold: 700;
  --font-weight-extrabold: 800;
  --font-weight-black: 900;
  --font-weight-w1000: 1000;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-80: 80px;
  --spacing-100: 100px;
  --spacing-160: 160px;
  --spacing-180: 180px;
  --spacing-200: 200px;

  /* Layout */
  --page-max-width: 1200px;
  --section-gap: 113px;
  --card-padding: 53px;
  --element-gap: 12px;

  /* Border Radius */
  --radius-xl: 12px;
  --radius-3xl: 24px;
  --radius-full: 48px;
  --radius-full-2: 100px;

  /* Named Radii */
  --radius-cards: 24px;
  --radius-buttons: 100px;
  --radius-largeelements: 48px;
  --radius-navigationitems: 12px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-deep-space: #0d0b33;
  --color-cloud-white: #ffffff;
  --color-ash-gray: #f7f6ff;
  --color-slate: #666666;
  --color-twilight-indigo: #4a21ef;
  --color-emerald-growth: #79efbd;
  --color-jade-outline: #18d26e;
  --color-gradient-cosmos: #bf_ff_e4;

  /* Typography */
  --font-alibabapuhuiti-2: 'AlibabaPuHuiTi-2', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-body-lg: 18px;
  --leading-body-lg: 1.5;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.3;
  --text-heading: 32px;
  --leading-heading: 1.3;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.3;
  --text-display-sm: 80px;
  --leading-display-sm: 1.3;
  --text-display: 137px;
  --leading-display: 1.3;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-80: 80px;
  --spacing-100: 100px;
  --spacing-160: 160px;
  --spacing-180: 180px;
  --spacing-200: 200px;

  /* Border Radius */
  --radius-xl: 12px;
  --radius-3xl: 24px;
  --radius-full: 48px;
  --radius-full-2: 100px;
}
```

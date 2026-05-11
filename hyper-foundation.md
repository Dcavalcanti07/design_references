# Hyper Foundation — Style Reference
> Deep emerald command center.

**Theme:** dark

Hyperliquid presents a dark, immersive interface dominated by a deep green-black canvas. Typography is a precise blend of a traditional serif for commanding headlines and a clean sans-serif for functional content, making blocks of text feel grounded yet efficient. A vivid, almost neon, mint green color serves as the sole accent, highlighting interactive elements and drawing focus to key information. Components are understated, often using ghost styling or subtle outlines, and leverage large rounded corners to soften the overall impression.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Emerald | `#072724` | `--color-midnight-emerald` | Page backgrounds, card surfaces, primary text on lighter surfaces. The canvas of the system |
| Ghost Jade | `#23524c` | `--color-ghost-jade` | Subtle card backgrounds, ghost button borders, hairline dividers. Provides minimal contrast against Midnight Emerald |
| Aura Mint | `#97fcd7` | `--color-aura-mint` | Green text accent for links, tags, and emphasized short phrases. Do not promote it to the primary CTA color |
| Ceramic White | `#ffffff` | `--color-ceramic-white` | Primary text on dark backgrounds, active icons, essential information text |
| Slate Border | `#2c2e33` | `--color-slate-border` | Subtle borders separating UI elements on dark backgrounds, non-active menu item borders |
| Platinum Ghost | `#b0c5c1` | `--color-platinum-ghost` | Muted text, decorative fills for secondary icons or illustrations. A very light gray with a cool tint |
| Ash Text | `#0f3933` | `--color-ash-text` | Secondary text on dark backgrounds, subtle captions, placeholder text |
| Deep Teal | `#33998c` | `--color-deep-teal` | Teal text accent for links, tags, and emphasized short phrases. Do not promote it to the primary CTA color |

## Tokens — Typography

### Teodor — Display and main headings. The single weight serif projects authority and traditional finance gravitas against a modern tech backdrop. Large sizes command attention. · `--font-teodor`
- **Substitute:** Poly
- **Weights:** 400
- **Sizes:** 24px, 55px, 60px, 90px
- **Line height:** 0.75, 1.00, 1.50
- **Letter spacing:** normal
- **OpenType features:** `"kern"`
- **Role:** Display and main headings. The single weight serif projects authority and traditional finance gravitas against a modern tech backdrop. Large sizes command attention.

### Inter — All body text, navigation items, buttons, and functional UI elements. The sans-serif provides a legible and clean counterpoint to the display font, ensuring content is easily digestible. Weight 300 is used for lighter emphasis. · `--font-inter`
- **Substitute:** System Font
- **Weights:** 300, 400
- **Sizes:** 12px, 16px, 20px, 28px, 35px
- **Line height:** 1.00, 1.30, 1.50
- **Letter spacing:** normal
- **OpenType features:** `"kern"`
- **Role:** All body text, navigation items, buttons, and functional UI elements. The sans-serif provides a legible and clean counterpoint to the display font, ensuring content is easily digestible. Weight 300 is used for lighter emphasis.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.5 | — | `--text-caption` |
| body-sm | 16px | 1.5 | — | `--text-body-sm` |
| body | 20px | 1.5 | — | `--text-body` |
| subheading | 24px | 1.5 | — | `--text-subheading` |
| heading | 35px | 1.3 | — | `--text-heading` |
| heading-lg | 55px | 1 | — | `--text-heading-lg` |
| display | 90px | 0.75 | — | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 6 | 6px | `--spacing-6` |
| 8 | 8px | `--spacing-8` |
| 9 | 9px | `--spacing-9` |
| 14 | 14px | `--spacing-14` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 30 | 30px | `--spacing-30` |
| 32 | 32px | `--spacing-32` |
| 37 | 37px | `--spacing-37` |
| 40 | 40px | `--spacing-40` |
| 50 | 50px | `--spacing-50` |
| 90 | 90px | `--spacing-90` |
| 100 | 100px | `--spacing-100` |
| 113 | 113px | `--spacing-113` |
| 160 | 160px | `--spacing-160` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 12px |
| forms | 37px |
| buttons | 60px |
| default | 12px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| lg | `rgb(151, 252, 215) 0px 0px 20px 5px` | `--shadow-lg` |

### Layout

- **Section gap:** 100px
- **Card padding:** 14px
- **Element gap:** 24px

## Components

### Primary Action Button
**Role:** Call-to-action button, highlighted interaction.

Background: Aura Mint (#97fcd7), Text: Midnight Emerald (#072724), Padding: 9px vertical, 24px horizontal. Radius: 60px.

### Ghost Action Button
**Role:** Secondary action button, less prominent interaction.

Background: transparent, Border: 1px solid Ghost Jade (#23524c), Text: Ceramic White (#ffffff), Padding: 9px vertical, 24px horizontal. Radius: 60px.

### Navigation Link
**Role:** Top navigation items.

Text: Ash Text (#0f3933) for inactive, Ceramic White (#ffffff) for active. Font: Inter, weight 400, size 16px. No background or border.

### Header Branding
**Role:** Brand logo and text in header.

Text: Ceramic White (#ffffff), Font: Inter, weight 400, size 20px. Preceded by an icon in Aura Mint (#97fcd7).

### Hero Section Headline
**Role:** Main title on the landing page.

Text: Ceramic White (#ffffff), Font: Teodor, weight 400, size 90px, lineHeight 0.75.

### Elevated Feature Card
**Role:** Prominent information card.

Background: Midnight Emerald (#072724), Padding: 14px on all sides. Border Radius: 12px. Shadow: Aura Mint (#97fcd7) 0px 0px 20px 5px.

## Do's and Don'ts

### Do
- Use Midnight Emerald (#072724) for default backgrounds and primary surfaces.
- Apply Aura Mint (#97fcd7) exclusively for interactive elements, highlights, and accent glows.
- Employ the Teodor font for all display headings at larger sizes (55px, 60px, 90px) and Inter for all body text and captions.
- Use 60px border radius for all buttons and other highly interactive pills for a distinct softened aesthetic.
- Maintain a comfortable element gap of 24px and section gap of 100px for visual breathing room.
- Always use Ceramic White (#ffffff) for primary text on dark backgrounds to ensure high contrast.
- Utilize Ghost Jade (#23524c) for subtle borders and backgrounds to create visual depth without high contrast.

### Don't
- Do not introduce new primary colors; Aura Mint (#97fcd7) is the only primary accent.
- Avoid using Teodor at small sizes or for body copy; reserve it for large, impactful headlines only.
- Do not use sharp corners; apply default rounded corners of 12px or larger for all UI elements.
- Avoid generic drop shadows; elevation should primarily use the Aura Mint (#97fcd7) glow for emphasis.
- Do not use dark text on dark backgrounds; ensure ample contrast with Ceramic White (#ffffff) or Platinum Ghost (#b0c5c1).
- Avoid padding smaller than 9px for interactive elements; maintain a comfortable tap target and visual space.
- Do not use varied letter-spacing; all typography should use normal letter-spacing, relying on size and weight for distinction.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Page Canvas | `#072724` | The primary background for the entire application, providing a deep, consistent dark base. |
| 2 | Subtle Card | `#23524c` | Used for secondary cards or content sections that require a slightly distinct background from the main canvas without strong contrast. |

## Elevation

- **Elevated Feature Card:** `rgb(151, 252, 215) 0px 0px 20px 5px`

## Imagery

The visual language relies on abstract, organic 3D shapes and blurred, darker gradients as background elements, creating a sense of depth and modernity without explicit product imagery or photography. Icons are minimal, either filled or outlined, primarily in Ceramic White or Aura Mint, serving functional rather than decorative roles. Density is moderate, with ample negative space around key text and components.

## Layout

The page uses a full-bleed dark background that acts as a continuous canvas. The hero section features a prominent, centered headline with a call to action below, set against a dynamic gradient background with abstract 3D elements. Content sections below maintain consistent vertical spacing, often with text-dominant blocks. The main navigation is a sticky, minimalist top bar with right-aligned functional links and a highlighted action button.

## Agent Prompt Guide

Quick Color Reference: 
text: #ffffff
background: #072724
border: #2c2e33
accent: #97fcd7
primary action: no distinct CTA color

Example Component Prompts:
Create a hero section: Dark background with abstract 3D shapes. Main headline in Teodor 90px 400, #ffffff, lineHeight 0.75. Subtext in Inter 20px 400, #ffffff. Two buttons below, left is 'Start Trading' with background #97fcd7, text #072724, 60px radius, 9px vertical 24px horizontal padding. Right is 'Start Building' with transparent background, 1px border #23524c, text #ffffff, 60px radius, 9px vertical 24px horizontal padding.

Create a navigation bar: Background #072724. Company logo with icon in #97fcd7 and text 'Hyperliquid' in Inter 20px 400, #ffffff. Navigation links 'Stats', 'Docs', 'Ecosystem' in Inter 16px 400, #0f3933. Right-aligned button 'Launch App' with background #97fcd7, text #072724, 60px radius, 9px vertical 24px horizontal padding.

Create a feature card: Background #072724, 14px padding, 12px border radius. Apply a box-shadow of rgb(151, 252, 215) 0px 0px 20px 5px. Headline in Teodor 35px 400, #ffffff, lineHeight 1.3. Body text in Inter 16px 400, #b0c5c1.

## Similar Brands

- **Alchemy.com** — Similar dark theme with a prominent single accent color and focus on developer/finance tools.
- **StarkWare.co** — Shares a sophisticated, minimal dark interface with geometric or abstract background graphics.
- **Mantle.xyz** — Features a dark, tech-focused aesthetic with subtle gradients and a clean, functional typography system.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-emerald: #072724;
  --color-ghost-jade: #23524c;
  --color-aura-mint: #97fcd7;
  --color-ceramic-white: #ffffff;
  --color-slate-border: #2c2e33;
  --color-platinum-ghost: #b0c5c1;
  --color-ash-text: #0f3933;
  --color-deep-teal: #33998c;

  /* Typography — Font Families */
  --font-teodor: 'Teodor', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --text-body-sm: 16px;
  --leading-body-sm: 1.5;
  --text-body: 20px;
  --leading-body: 1.5;
  --text-subheading: 24px;
  --leading-subheading: 1.5;
  --text-heading: 35px;
  --leading-heading: 1.3;
  --text-heading-lg: 55px;
  --leading-heading-lg: 1;
  --text-display: 90px;
  --leading-display: 0.75;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-9: 9px;
  --spacing-14: 14px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-30: 30px;
  --spacing-32: 32px;
  --spacing-37: 37px;
  --spacing-40: 40px;
  --spacing-50: 50px;
  --spacing-90: 90px;
  --spacing-100: 100px;
  --spacing-113: 113px;
  --spacing-160: 160px;

  /* Layout */
  --section-gap: 100px;
  --card-padding: 14px;
  --element-gap: 24px;

  /* Border Radius */
  --radius-xl: 12px;
  --radius-3xl: 37px;
  --radius-full: 60px;

  /* Named Radii */
  --radius-cards: 12px;
  --radius-forms: 37px;
  --radius-buttons: 60px;
  --radius-default: 12px;

  /* Shadows */
  --shadow-lg: rgb(151, 252, 215) 0px 0px 20px 5px;

  /* Surfaces */
  --surface-page-canvas: #072724;
  --surface-subtle-card: #23524c;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-emerald: #072724;
  --color-ghost-jade: #23524c;
  --color-aura-mint: #97fcd7;
  --color-ceramic-white: #ffffff;
  --color-slate-border: #2c2e33;
  --color-platinum-ghost: #b0c5c1;
  --color-ash-text: #0f3933;
  --color-deep-teal: #33998c;

  /* Typography */
  --font-teodor: 'Teodor', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --text-body-sm: 16px;
  --leading-body-sm: 1.5;
  --text-body: 20px;
  --leading-body: 1.5;
  --text-subheading: 24px;
  --leading-subheading: 1.5;
  --text-heading: 35px;
  --leading-heading: 1.3;
  --text-heading-lg: 55px;
  --leading-heading-lg: 1;
  --text-display: 90px;
  --leading-display: 0.75;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-9: 9px;
  --spacing-14: 14px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-30: 30px;
  --spacing-32: 32px;
  --spacing-37: 37px;
  --spacing-40: 40px;
  --spacing-50: 50px;
  --spacing-90: 90px;
  --spacing-100: 100px;
  --spacing-113: 113px;
  --spacing-160: 160px;

  /* Border Radius */
  --radius-xl: 12px;
  --radius-3xl: 37px;
  --radius-full: 60px;

  /* Shadows */
  --shadow-lg: rgb(151, 252, 215) 0px 0px 20px 5px;
}
```

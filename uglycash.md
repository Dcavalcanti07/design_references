# UGLYCASH — Style Reference
> High-contrast digital pop: Bold black text on bright canvas, punctuated by vivid neons.

**Theme:** light

UGLYCASH embraces a stark, high-contrast digital-first aesthetic with deeply saturated accent colors that pop against a near-white canvas and stark black typography. The visual style is bold, with large, confident headlines and playful, oversized rounded corners for interactive elements and content cards. Imagery is integrated directly into the UI as product showcases rather than decorative backdrops. The system balances aggressive typography with a comfortable, open layout.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas Ice | `#f2f2f2` | `--color-canvas-ice` | Page backgrounds, default surfaces beyond explicit cards |
| Ghost Gray | `#e6e4e4` | `--color-ghost-gray` | Subtle background for UI elements, dividers |
| Polar White | `#ffffff` | `--color-polar-white` | Content card backgrounds, elevated surfaces |
| Carbon Black | `#000000` | `--color-carbon-black` | Primary text, headings, strong borders, dark card backgrounds, interactive elements |
| Deep Graphite | `#3a3a3a` | `--color-deep-graphite` | Dark card backgrounds, secondary dark surfaces |
| Muted Stone | `#6e6e6e` | `--color-muted-stone` | Muted text, secondary body copy |
| Soft Stone | `#888888` | `--color-soft-stone` | Tertiary body copy, small print, helper text |
| Cream Card | `#e7e3bf` | `--color-cream-card` | Distinctive card background for specific content blocks |
| Power Pink | `#fa00ff` | `--color-power-pink` | Vivid accent for cards, graphic elements |
| Sky Blue | `#02bbff` | `--color-sky-blue` | Vivid accent for cards, graphic elements, data visualization |
| Lime Pop | `#adff02` | `--color-lime-pop` | Vivid accent for links, graphic elements, small interactive highlights |
| Metal Gradient Light | `linear-gradient(90deg, rgb(129, 125, 114) 0%, rgb(194, 190, 172) 100%)` | `--color-metal-gradient-light` | Subtle metallic gradient for decorative elements, card borders |

## Tokens — Typography

### sans-serif — System default for small utility text, captions, and fallback body copy. · `--font-sans-serif`
- **Substitute:** Arial
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.20
- **Letter spacing:** normal
- **Role:** System default for small utility text, captions, and fallback body copy.

### Helvetica Now Display Cn Bold — Display and primary headings – bold, compact, and impactful, defined by tight letter-spacing for a modern, aggressive presence. · `--font-helvetica-now-display-cn-bold`
- **Substitute:** Montserrat Black
- **Weights:** 700, 900
- **Sizes:** 20px, 64px, 85px, 164px
- **Line height:** 0.85, 0.94, 1.20
- **Letter spacing:** -0.033em
- **Role:** Display and primary headings – bold, compact, and impactful, defined by tight letter-spacing for a modern, aggressive presence.

### Inter — Body copy and subheadings – provides readability at various sizes with a slightly condensed feel. · `--font-inter`
- **Substitute:** Inter
- **Weights:** 400, 500, 700
- **Sizes:** 12px, 14px, 18px, 20px, 24px
- **Line height:** 1.17, 1.20, 1.22, 1.29, 1.33, 1.40
- **Letter spacing:** -0.02em
- **Role:** Body copy and subheadings – provides readability at various sizes with a slightly condensed feel.

### Miss Fajardose — Miss Fajardose — detected in extracted data but not described by AI · `--font-miss-fajardose`
- **Weights:** 400
- **Sizes:** 38px
- **Line height:** 1.2
- **Role:** Miss Fajardose — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.2 | -0.24px | `--text-caption` |
| body-sm | 14px | 1.4 | -0.28px | `--text-body-sm` |
| body | 18px | 1.22 | -0.36px | `--text-body` |
| subheading | 20px | 1.17 | -0.4px | `--text-subheading` |
| heading | 64px | 0.94 | -2.11px | `--text-heading` |
| display | 164px | 0.85 | -5.41px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 5 | 5px | `--spacing-5` |
| 9 | 9px | `--spacing-9` |
| 10 | 10px | `--spacing-10` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 27 | 27px | `--spacing-27` |
| 34 | 34px | `--spacing-34` |
| 96 | 96px | `--spacing-96` |
| 168 | 168px | `--spacing-168` |

### Border Radius

| Element | Value |
|---------|-------|
| pill | 100px |
| large | 46px |
| small | 1px |
| default | 16px |

### Layout

- **Section gap:** 96px
- **Card padding:** 20px
- **Element gap:** 10px

## Components

### Ghost Button Inverse
**Role:** Minimal interactive element for secondary actions or navigation.

Transparent background, Carbon Black text and border. No border-radius, for a stark, flat look. Padding is 10px vertically by 5px horizontally. Text uses a system sans-serif font at 12px.

### Pill Accent Button
**Role:** Primary Call to Action, visually distinct and inviting interaction.

Carbon Black background with 100px border-radius creating a pill shape. Text is the browser default link color rgb(0,0,238). Zero vertical padding, 24px horizontal padding. Prompts interaction through shape.

### Rounded Accent Button
**Role:** Secondary action or featured link, with a soft background.

Translucent dark gray background rgba(237, 237, 237, 0.15), 16px border-radius. Text is the browser default link color rgb(0,0,238). Zero vertical padding, 24px horizontal padding. Used for 'Get the APP'.

### White Information Card
**Role:** Standard container for content blocks and feature explanations.

Polar White background, 16px border-radius, no shadow. Zero padding, content manages its own internal spacing.

### Cream Accent Card
**Role:** Highlight card for special features, uses a distinct neutral background.

Cream Card background (#e7e3bf), 46px border-radius for an oversized, playful shape. No shadow, zero padding.

### Dark Graphic Card
**Role:** Visual cards that integrate product imagery or bold graphics.

Can be Carbon Black (#000000), Deep Graphite (#3a3a3a), or #000100 background. Features an oversized 38px or 43px border-radius. No shadow, zero padding. Used for presenting app screenshots or abstract graphics.

## Do's and Don'ts

### Do
- Use Canvas Ice (#f2f2f2) for the primary page background to maintain the light theme.
- Employ Helvetica Now Display Cn Bold with a letter-spacing of -0.033em for all major headlines to convey impact and density.
- Apply 10px elementGap for most interactive and content grouping, providing comfortable visual separation.
- Utilize 16px border-radius for standard cards, images, and links to maintain a consistent soft containment.
- Ensure all body text uses Inter font with a letter-spacing of -0.02em to support readability while retaining a modern feel.
- Use Power Pink (#fa00ff), Sky Blue (#02bbff), and Lime Pop (#adff02) as vivid accents against predominantly achromatic surfaces.
- Implement 96px for sectionGap to provide ample vertical whitespace between major content blocks.

### Don't
- Avoid using light, subtle headlines; all significant text should be in Carbon Black (#000000) for maximum contrast.
- Do not introduce new border-radius values; stick to 16px, 46px, 43px, 38px from the defined system.
- Refrain from adding drop shadows; the design relies on stark contrast and distinct colorful accents, not depth perception.
- Do not use generic button styles; always apply either the Ghost Button Inverse, Pill Accent Button, or Rounded Accent Button tokens.
- Avoid breaking the high-contrast principle; never use a low-contrast color pairing for fundamental text or interactive elements.
- Do not use generic sans-serif for body text; always prefer Inter for its distinct visual rhythm and letter-spacing.

## Imagery

Imagery primarily consists of clean, isolated product screenshots of the UGLYCASH app or abstract graphics with a highly saturated, neon color palette. These visuals are often integrated directly into cards, appearing as contained elements rather than full-bleed backgrounds. The app screenshots are sharp, showcasing UI details clearly without excessive styling or context. Icons are simple, outlined or filled, and primarily mono-color, often in Carbon Black or one of the vivid accent colors. The role of imagery is primarily explanatory content and product showcase, with a moderate density.

## Layout

The page primarily uses a full-bleed layout, allowing content to stretch across the full width, though some sections appear to have an implicit centered content area. The hero pattern features a dominant, center-aligned headline over a soft background, often followed by product visuals. Sections are separated by comfortable `sectionGap` (96px) and maintain a spacious vertical rhythm, avoiding dense information blocks. Content arrangement often alternates between large headlines, centered product showcases, and multi-column grids for features, typically 3 columns. Navigation is handled by a minimal top bar with social links and a 'Get the APP' action button.

## Agent Prompt Guide

**Quick Color Reference:**
text: #000000
background: #f2f2f2
border: #000000
accent: #fa00ff
primary action: no distinct CTA color

**3-5 Example Component Prompts:**
1. Create a hero section with a centered headline: 'YOUR BANK WON'T DO THIS' using Helvetica Now Display Cn Bold, size 164px, weight 900, hex #000000, letter-spacing -5.41px. Ensure the background is Canvas Ice (#f2f2f2).
2. Generate a feature card: White Information Card with 'Earn' as the heading using Inter font 20px, weight 700, and a body text describing earning. Below it, add a small Lime Pop (#adff02) square accent.
3. Create a navigation bar: Ghost Button Inverse 'More videos' to the left, a Pill Accent Button to the right (background: #000000, text: rgb(0,0,238), border-radius 100px, 24px horizontal padding), and a Rounded Accent Button 'Get the APP' (background: rgba(237, 237, 237, 0.15), text: rgb(0,0,238), border-radius 16px, 24px horizontal padding) next to it.

## Similar Brands

- **Revolut** — High-contrast text on light backgrounds with strong accent colors and modern sans-serif typography.
- **Cash App** — Utilizes bold, impactful typography and vivid accent colors within a clean, app-like UI structure.
- **Chime** — Focus on approachable, modern design for financial services, featuring clear contrast and simple forms.
- **Monzo** — Combines a clean, bright interface with judicious use of saturated colors for highlights and branded elements.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-ice: #f2f2f2;
  --color-ghost-gray: #e6e4e4;
  --color-polar-white: #ffffff;
  --color-carbon-black: #000000;
  --color-deep-graphite: #3a3a3a;
  --color-muted-stone: #6e6e6e;
  --color-soft-stone: #888888;
  --color-cream-card: #e7e3bf;
  --color-power-pink: #fa00ff;
  --color-sky-blue: #02bbff;
  --color-lime-pop: #adff02;
  --color-metal-gradient-light: #817d72;
  --gradient-metal-gradient-light: linear-gradient(90deg, rgb(129, 125, 114) 0%, rgb(194, 190, 172) 100%);

  /* Typography — Font Families */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-helvetica-now-display-cn-bold: 'Helvetica Now Display Cn Bold', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-miss-fajardose: 'Miss Fajardose', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.2;
  --tracking-caption: -0.24px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.4;
  --tracking-body-sm: -0.28px;
  --text-body: 18px;
  --leading-body: 1.22;
  --tracking-body: -0.36px;
  --text-subheading: 20px;
  --leading-subheading: 1.17;
  --tracking-subheading: -0.4px;
  --text-heading: 64px;
  --leading-heading: 0.94;
  --tracking-heading: -2.11px;
  --text-display: 164px;
  --leading-display: 0.85;
  --tracking-display: -5.41px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-bold: 700;
  --font-weight-black: 900;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-9: 9px;
  --spacing-10: 10px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-27: 27px;
  --spacing-34: 34px;
  --spacing-96: 96px;
  --spacing-168: 168px;

  /* Layout */
  --section-gap: 96px;
  --card-padding: 20px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-sm: 1px;
  --radius-lg: 8.2px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 23px;
  --radius-3xl: 38px;
  --radius-3xl-2: 43px;
  --radius-3xl-3: 46px;
  --radius-full: 50px;
  --radius-full-2: 100px;

  /* Named Radii */
  --radius-pill: 100px;
  --radius-large: 46px;
  --radius-small: 1px;
  --radius-default: 16px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-ice: #f2f2f2;
  --color-ghost-gray: #e6e4e4;
  --color-polar-white: #ffffff;
  --color-carbon-black: #000000;
  --color-deep-graphite: #3a3a3a;
  --color-muted-stone: #6e6e6e;
  --color-soft-stone: #888888;
  --color-cream-card: #e7e3bf;
  --color-power-pink: #fa00ff;
  --color-sky-blue: #02bbff;
  --color-lime-pop: #adff02;
  --color-metal-gradient-light: #817d72;

  /* Typography */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-helvetica-now-display-cn-bold: 'Helvetica Now Display Cn Bold', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-miss-fajardose: 'Miss Fajardose', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.2;
  --tracking-caption: -0.24px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.4;
  --tracking-body-sm: -0.28px;
  --text-body: 18px;
  --leading-body: 1.22;
  --tracking-body: -0.36px;
  --text-subheading: 20px;
  --leading-subheading: 1.17;
  --tracking-subheading: -0.4px;
  --text-heading: 64px;
  --leading-heading: 0.94;
  --tracking-heading: -2.11px;
  --text-display: 164px;
  --leading-display: 0.85;
  --tracking-display: -5.41px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-9: 9px;
  --spacing-10: 10px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-27: 27px;
  --spacing-34: 34px;
  --spacing-96: 96px;
  --spacing-168: 168px;

  /* Border Radius */
  --radius-sm: 1px;
  --radius-lg: 8.2px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 23px;
  --radius-3xl: 38px;
  --radius-3xl-2: 43px;
  --radius-3xl-3: 46px;
  --radius-full: 50px;
  --radius-full-2: 100px;
}
```

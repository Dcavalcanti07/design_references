# Monologue — Style Reference
> Midnight Terminal with Aqua Glow. A luminous aqua cursor on a deep, textured black screen, where retro-futuristic forms hint at precision and understated power.

**Theme:** dark

Monologue evokes a 'hacker garage at midnight' aesthetic, blending retro tech charm with modern dark mode sophistication. The design utilizes a deep, multi-layered neutral palette of dark grays and blacks as its canvas, punctuated by selective, vivid aqua accents. Typography combines a classic serif for imposing headlines with a monospaced font for functional elements, creating a distinctive contrast. Components are minimal, often transparent or outlined, and sparingly employ subtle inner shadows for depth rather than heavy elevation.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Absolute Zero | `#000000` | `--color-absolute-zero` | Dark borders and separators for elevated surfaces and inverted UI. Do not promote it to the primary CTA color |
| Deep Graphite | `linear-gradient(rgb(50, 50, 50) 0%, rgb(1, 1, 1) 100%)` | `--color-deep-graphite` | Deep canvas for dark sections, primary dark surfaces, and high-contrast framing. Do not promote it to the primary CTA color; Background texture for visual depth, especially in header regions |
| Carbon Black | `#191919` | `--color-carbon-black` | Secondary surface background, subtle elevated elements |
| Dark Charcoal | `#282828` | `--color-dark-charcoal` | Filled button backgrounds, body text with low contrast, interactive element backgrounds |
| Slate Gray | `#3f3f3f` | `--color-slate-gray` | Card backgrounds, subtle background textures |
| Ash Gray | `#7f7f7f` | `--color-ash-gray` | Subtle shadow tints, secondary text elements |
| Near White | `#ffffff` | `--color-near-white` | Primary headings and body text, accent borders, button text on dark backgrounds |
| Sea Glass | `#062f34` | `--color-sea-glass` | Card background for emphasized informational blocks |
| Electric Aqua | `#19d0e8` | `--color-electric-aqua` | Interactive link text, highlighted text, subtle decorative borders, functional icon accents |
| Sky Burst | `#44ccff` | `--color-sky-burst` | Accented card backgrounds, decorative elements |

## Tokens — Typography

### sans-serif — sans-serif — detected in extracted data but not described by AI · `--font-sans-serif`
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.2
- **Role:** sans-serif — detected in extracted data but not described by AI

### Instrument Serif — Display and primary headings – large, expressive serif that commands attention and establishes brand presence. Use with tight tracking for impact. · `--font-instrument-serif`
- **Weights:** 400
- **Sizes:** 28px, 30px, 32px, 40px, 48px, 64px, 70px, 72px, 96px, 393px, 403px
- **Line height:** 0.90, 1.00, 1.10, 1.20, 1.30, 1.40
- **Letter spacing:** -0.04em, -0.03em, -0.007em, -0.003em, -0.002em, 0.008em
- **Role:** Display and primary headings – large, expressive serif that commands attention and establishes brand presence. Use with tight tracking for impact.

### DM Mono — Monospaced text for code blocks, secondary headings, and functional UI elements – providing a retro-tech feel and clear information hierarchy. · `--font-dm-mono`
- **Weights:** 400
- **Sizes:** 10px, 12px, 14px, 15px, 16px, 18px, 20px, 32px
- **Line height:** 0.80, 1.00, 1.20, 1.40, 1.50
- **Letter spacing:** -0.05em, -0.01em, -0.008em, -0.007em, -0.006em, 0.015em, 0.017em, 0.019em, 0.020em, 0.021em
- **Role:** Monospaced text for code blocks, secondary headings, and functional UI elements – providing a retro-tech feel and clear information hierarchy.

### Geist — Primary body text – a modern sans-serif for clear readability and informational content. · `--font-geist`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 17px
- **Line height:** 1.40
- **Letter spacing:** normal
- **Role:** Primary body text – a modern sans-serif for clear readability and informational content.

### SF Pro Display Regular — Secondary body text and detailed descriptive elements – for compact and precise information presentation consistent with Apple's ecosystem. · `--font-sf-pro-display-regular`
- **Substitute:** SF Pro Text
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.40
- **Letter spacing:** -0.006em
- **Role:** Secondary body text and detailed descriptive elements – for compact and precise information presentation consistent with Apple's ecosystem.

### system-ui — system-ui — detected in extracted data but not described by AI · `--font-system-ui`
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.5
- **Role:** system-ui — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.4 | 0.2px | `--text-caption` |
| body | 16px | 1.5 | -0.096px | `--text-body` |
| subheading | 20px | 1.2 | -0.16px | `--text-subheading` |
| heading | 40px | 1.1 | -0.8px | `--text-heading` |
| display | 96px | 0.9 | -3.84px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 5 | 5px | `--spacing-5` |
| 6 | 6px | `--spacing-6` |
| 8 | 8px | `--spacing-8` |
| 9 | 9px | `--spacing-9` |
| 10 | 10px | `--spacing-10` |
| 11 | 11px | `--spacing-11` |
| 12 | 12px | `--spacing-12` |
| 14 | 14px | `--spacing-14` |
| 16 | 16px | `--spacing-16` |
| 18 | 18px | `--spacing-18` |
| 19 | 19px | `--spacing-19` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 72 | 72px | `--spacing-72` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 10px |
| avatars | 900px |
| buttons | 100000px |
| default | 8px |
| largeCards | 40px |
| smallElements | 4px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(0, 0, 0, 0.7) 3px 3px 2px 0px inset, rgba(255, 255, ...` | `--shadow-subtle` |
| sm | `rgba(0, 0, 0, 0.25) 0px 4px 4px 0px, rgba(255, 255, 255, ...` | `--shadow-sm` |
| subtle-2 | `rgba(0, 0, 0, 0.63) 0px 0px 0px 1px` | `--shadow-subtle-2` |
| md | `rgb(14, 93, 102) 6px 6px 10px 0px inset, rgba(255, 255, 2...` | `--shadow-md` |

### Layout

- **Page max-width:** 1200px
- **Section gap:** 40px
- **Card padding:** 16px
- **Element gap:** 10px

## Components

### Filled Dark Button
**Role:** Primary action button

Solid `Dark Charcoal` (#282828) background with `Near White` (#ffffff) text, using a generous `100000px` border-radius for a pill shape. Padding is `18px` horizontal and `20px` vertical.

### Ghost Accent Button
**Role:** Secondary action or featured link

Transparent background with a `100000px` border-radius and a `Absolute Zero` (#000000) border of `6px` width. Text color uses the browser default link color, which is a rare artifact not part of the brand palette. **A brand-consistent approach would be to use Electric Aqua for text.**

### Info Card
**Role:** Content container for features or testimonials

Uses `Carbon Black` (#191919) as background with `10px` border-radius and `16px` padding on all sides. No visible box shadow, achieving a flat, embedded aesthetic.

### Highlight Card - Sea Glass
**Role:** Emphasized feature card

Features a `Sea Glass` (#062f34) background with `16px` padding and `10px` border-radius. Used for informational blocks that require a subtle, calm highlight.

### Highlight Card - Sky Burst
**Role:** Prominent feature card

Utilizes a `Sky Burst` (#44ccff) background with `16px` padding and `10px` border-radius. Provides a more vivid, attention-grabbing background for key features.

### Media Player Card
**Role:** Distinctive object container, often for media

Has a `Slate Gray` (#3f3f3f) background with prominent `52px` border-radius. Features a complex inset box shadow creating depth and a glossy effect. Padding is `12px` on all sides.

### Text Input Container
**Role:** Container for form inputs or code snippets

Features a transparent background with `Near White` (#ffffff) borders and `10px` border-radius. Padding is `16px` on all sides. When in an active state, it's typically highlighted by the `Electric Aqua` accent.

## Do's and Don'ts

### Do
- Prioritize `Absolute Zero` (#000000) or `Deep Graphite` (#010101) as primary background colors for large sections.
- Use `Instrument Serif` for all primary headlines, leveraging its unique character and impactful size variations.
- Apply `DM Mono` for any code snippets, secondary headings, or UI labels to maintain the retro-tech aesthetic.
- Incorporate `Electric Aqua` (#19d0e8) sparingly for interactive elements, links, and small functional accents to provide a 'switched-on' feel.
- Use `10px` border-radius for cards and content containers, and `100000px` for all buttons to achieve a consistent pill shape.
- Employ the subtle inner shadow `rgba(0, 0, 0, 0.7) 3px 3px 2px 0px inset, rgba(255, 255, 255, 0.25) 3px 2px 2px 0px` on surfaces to add depth rather than heavy external shadows.
- Maintain a conservative compact density, using `10px` as a default `elementGap` between UI elements and `16px` for `cardPadding`.

### Don't
- Avoid using bright or overly saturated colors outside of the designated `Electric Aqua` and `Sky Burst` accents.
- Do not introduce heavy drop shadows or strong external elevation as the design favors subtle inset shadows for depth.
- Refrain from using generic sans-serif fonts for headlines; `Instrument Serif` is key to the brand's typographic identity.
- Avoid large, content-heavy image banners; imagery should be contained, illustrative, or product-focused within the dark UI.
- Do not use multiple accent colors; stick to the `Electric Aqua` and `Sky Burst` for highlights to maintain focus.
- Avoid excessive use of gradients; if used, they should be subtle dark-to-dark transitions for background textures, not vivid multi-color displays.
- Do not use sharp corners; the design consistently uses rounded corners, with `10px` or `8px` being common for main containers and `100000px` for interactive elements.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Canvas | `#000000` | Primary page background, deepest layer. |
| 2 | Base Surface | `#010101` | Dominant background for content sections and large panels. |
| 3 | Card Surface | `#191919` | Background for individual cards and feature blocks. |
| 4 | Interactive Surface | `#282828` | Background for filled buttons and active input fields. |

## Elevation

- **Media Player Card:** `rgba(0, 0, 0, 0.25) 0px 5.0405px 10.207px 0px, rgba(201, 201, 201, 0.15) 0px 21.9128px 7.30426px 0px inset, rgba(0, 0, 0, 0.15) 0px -24.3475px 6.33036px 0px inset`
- **Subtle Inner Shadow:** `rgba(0, 0, 0, 0.7) 3px 3px 2px 0px inset, rgba(255, 255, 255, 0.25) 3px 2px 2px 0px`

## Imagery

The visual language focuses on stylized product representations and abstract tech-inspired graphics. Photography is minimal, if present, and would likely be high-contrast and monochrome. Illustrations are flat, geometric, and often incorporate the vivid `Electric Aqua` accent color, suggesting digital interfaces or data visualization. Icons are outlined, simple, and functional, maintaining a high stroke weight for clarity within the dark theme. Imagery serves both decorative atmosphere and explanatory content, often highlighting product features or conceptual processes. The density is medium, with visuals integrated into content blocks rather than full-bleed, ensuring the UI remains the primary focus.

## Layout

The page primarily uses a max-width contained layout, likely around `1200px`, centered on the screen. The hero section is full-bleed dark, featuring prominent `Instrument Serif` headlines and a central product graphic or media player, with call-to-action buttons below it. Content sections often follow an alternating pattern of text on one side and a product screenshot/illustration on the other. Feature lists and other information are arranged in vertically stacked blocks, sometimes within cards. The overall rhythm is consistent vertical spacing between sections. Navigation is a sticky top bar, likely minimal in appearance. The density is compact, prioritizing information without feeling cramped, with clear visual separation between content blocks.

## Agent Prompt Guide

**Quick Color Reference:**
- text: #ffffff
- background: #000000
- border: #000000
- accent: #19d0e8
- primary action: #282828 (filled action)

**3-5 Example Component Prompts:**
1. Create a hero section: `Absolute Zero` (#000000) background transitioned with `Monologue Gradient Dark` in `linear-gradient(rgb(50, 50, 50) 0%, rgb(1, 1, 1) 100%)`. Headline 'Effortless voice dictation' in `Instrument Serif` at 70px, `Near White` (#ffffff), letter-spacing -0.03em. Subtext in `Geist` at 17px, `Near White` (#ffffff). Include a 'Download' button: `Dark Charcoal` (#282828) background, `Near White` (#ffffff) text, `100000px` border-radius, `20px 18px` padding.
2. Design a feature card: `Carbon Black` (#191919) background, `10px` border-radius, `16px` padding. Headline in `DM Mono` at 20px, `Near White` (#ffffff), letter-spacing 0.019em. Body text in `Geist` at 17px, `Near White` (#ffffff).
3. Create an emphasized media player card: `Slate Gray` (#3f3f3f) background, `52px` border-radius, `12px` padding, with the box-shadow `rgba(0, 0, 0, 0.25) 0px 5.0405px 10.207px 0px, rgba(201, 201, 201, 0.15) 0px 21.9128px 7.30426px 0px inset, rgba(0, 0, 0, 0.15) 0px -24.3475px 6.33036px 0px inset`. 

## Similar Brands

- **Raycast** — Dark-mode UI with a focus on productivity, compact component design, and a strong emphasis on typography for visual hierarchy.
- **Linear** — Minimalist dark theme, subtle use of primary accent color for interactive states, and emphasis on clear, functional typography.
- **Notion (dark mode)** — Structured dark interface, use of varied text sizes for information density within a neutral palette, and subtle card-based layouts.
- **Figma (dark mode)** — Dark interface for creative tools, relying on grayscale definition and minimal color accents for functionality, with a lean towards monospaced or functional fonts.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-absolute-zero: #000000;
  --color-deep-graphite: #010101;
  --gradient-deep-graphite: linear-gradient(rgb(50, 50, 50) 0%, rgb(1, 1, 1) 100%);
  --color-carbon-black: #191919;
  --color-dark-charcoal: #282828;
  --color-slate-gray: #3f3f3f;
  --color-ash-gray: #7f7f7f;
  --color-near-white: #ffffff;
  --color-sea-glass: #062f34;
  --color-electric-aqua: #19d0e8;
  --color-sky-burst: #44ccff;

  /* Typography — Font Families */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-instrument-serif: 'Instrument Serif', ui-serif, Georgia, Cambria, "Times New Roman", Times, serif;
  --font-dm-mono: 'DM Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-geist: 'Geist', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sf-pro-display-regular: 'SF Pro Display Regular', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-system-ui: 'system-ui', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.4;
  --tracking-caption: 0.2px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.096px;
  --text-subheading: 20px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.16px;
  --text-heading: 40px;
  --leading-heading: 1.1;
  --tracking-heading: -0.8px;
  --text-display: 96px;
  --leading-display: 0.9;
  --tracking-display: -3.84px;

  /* Typography — Weights */
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-9: 9px;
  --spacing-10: 10px;
  --spacing-11: 11px;
  --spacing-12: 12px;
  --spacing-14: 14px;
  --spacing-16: 16px;
  --spacing-18: 18px;
  --spacing-19: 19px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-72: 72px;

  /* Layout */
  --page-max-width: 1200px;
  --section-gap: 40px;
  --card-padding: 16px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 18px;
  --radius-3xl: 24px;
  --radius-3xl-2: 40px;
  --radius-full: 52px;
  --radius-full-2: 56px;
  --radius-full-3: 60px;
  --radius-full-4: 100px;
  --radius-full-5: 900px;
  --radius-full-6: 100000px;

  /* Named Radii */
  --radius-cards: 10px;
  --radius-avatars: 900px;
  --radius-buttons: 100000px;
  --radius-default: 8px;
  --radius-largecards: 40px;
  --radius-smallelements: 4px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.7) 3px 3px 2px 0px inset, rgba(255, 255, 255, 0.25) 3px 2px 2px 0px;
  --shadow-sm: rgba(0, 0, 0, 0.25) 0px 4px 4px 0px, rgba(255, 255, 255, 0.25) 1px 1px 2px 0px, rgba(0, 0, 0, 0.5) 1px 1px 1px 0px inset, rgba(0, 0, 0, 0.7) 2px 2px 12px 0px inset;
  --shadow-subtle-2: rgba(0, 0, 0, 0.63) 0px 0px 0px 1px;
  --shadow-md: rgb(14, 93, 102) 6px 6px 10px 0px inset, rgba(255, 255, 255, 0.2) 4px 4px 4px 0px, rgba(255, 255, 255, 0.25) 1px 1px 2px 0px;

  /* Surfaces */
  --surface-canvas: #000000;
  --surface-base-surface: #010101;
  --surface-card-surface: #191919;
  --surface-interactive-surface: #282828;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-absolute-zero: #000000;
  --color-deep-graphite: #010101;
  --color-carbon-black: #191919;
  --color-dark-charcoal: #282828;
  --color-slate-gray: #3f3f3f;
  --color-ash-gray: #7f7f7f;
  --color-near-white: #ffffff;
  --color-sea-glass: #062f34;
  --color-electric-aqua: #19d0e8;
  --color-sky-burst: #44ccff;

  /* Typography */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-instrument-serif: 'Instrument Serif', ui-serif, Georgia, Cambria, "Times New Roman", Times, serif;
  --font-dm-mono: 'DM Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-geist: 'Geist', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sf-pro-display-regular: 'SF Pro Display Regular', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-system-ui: 'system-ui', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.4;
  --tracking-caption: 0.2px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.096px;
  --text-subheading: 20px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.16px;
  --text-heading: 40px;
  --leading-heading: 1.1;
  --tracking-heading: -0.8px;
  --text-display: 96px;
  --leading-display: 0.9;
  --tracking-display: -3.84px;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-9: 9px;
  --spacing-10: 10px;
  --spacing-11: 11px;
  --spacing-12: 12px;
  --spacing-14: 14px;
  --spacing-16: 16px;
  --spacing-18: 18px;
  --spacing-19: 19px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-72: 72px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 18px;
  --radius-3xl: 24px;
  --radius-3xl-2: 40px;
  --radius-full: 52px;
  --radius-full-2: 56px;
  --radius-full-3: 60px;
  --radius-full-4: 100px;
  --radius-full-5: 900px;
  --radius-full-6: 100000px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.7) 3px 3px 2px 0px inset, rgba(255, 255, 255, 0.25) 3px 2px 2px 0px;
  --shadow-sm: rgba(0, 0, 0, 0.25) 0px 4px 4px 0px, rgba(255, 255, 255, 0.25) 1px 1px 2px 0px, rgba(0, 0, 0, 0.5) 1px 1px 1px 0px inset, rgba(0, 0, 0, 0.7) 2px 2px 12px 0px inset;
  --shadow-subtle-2: rgba(0, 0, 0, 0.63) 0px 0px 0px 1px;
  --shadow-md: rgb(14, 93, 102) 6px 6px 10px 0px inset, rgba(255, 255, 255, 0.2) 4px 4px 4px 0px, rgba(255, 255, 255, 0.25) 1px 1px 2px 0px;
}
```

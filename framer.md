# Framer — Style Reference
> Deep Space Command

**Theme:** dark

Framer's aesthetic is a high-contrast digital canvas, emphasizing bold typography and a deep, immersive dark mode. The dominant #000000 background provides a stark stage for crisp #FFFFFF text, interrupted by precise, high-chroma electric blues (#0099FF, #0055FF) that pulse like indicator lights on active elements. Subtle surface variations in near-black (#080808, #171717) create depth within the dark theme without relying on heavy shadows, giving the interface a layered, architectural feel. The interplay of razor-sharp edges and large, soft radii (100px pill buttons) generates an engaging tension, balancing technical precision with approachable interactivity.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#000000` | `--color-midnight-ink` | Primary page background, text (on light elements), borders, illustration backgrounds. The foundational dark color that defines the theme. |
| Deep Graphite | `#080808` | `--color-deep-graphite` | Card backgrounds, elevated container surfaces. Provides subtle separation from the primary canvas. |
| Rich Coal | `#171717` | `--color-rich-coal` | Secondary elevated surfaces, slightly darker than Deep Graphite for further distinction. |
| Cloud White | `#FFFFFF` | `--color-cloud-white` | Primary text, core interactive element backgrounds (buttons), accents on dark backgrounds. High contrast against dark surfaces. |
| Mercury Gray | `#999999` | `--color-mercury-gray` | Secondary text, muted links, subtle borders. A desaturated tone for less prominent information. |
| Steel Gray | `#666666` | `--color-steel-gray` | Tertiary text, subtle separators, link borders. Provides a lower contrast alternative to Mercury Gray. |
| Electric Blue | `#0099FF` | `--color-electric-blue` | Observed in other backgroundColor, body borderColor, other stroke. Extracted usage does not support a distinct primary control color. |
| Velocity Blue | `#0055FF` | `--color-velocity-blue` | Secondary brand accent, used for gradients and fills in illustrations. Provides a slightly deeper, more saturated blue. |
| Shadow Tint | `#021f33` | `--color-shadow-tint` | Dark blue tint used in shadows, adding a subtle chromatic depth to elevated elements. |
| Interactive Blue Tint | `#0000ee` | `--color-interactive-blue-tint` | Supporting palette color with insufficient usage evidence for a stronger role. Extracted usage does not support a distinct primary control color. |

## Tokens — Typography

### sans-serif — sans-serif — detected in extracted data but not described by AI · `--font-sans-serif`
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.2
- **Role:** sans-serif — detected in extracted data but not described by AI

### Inter Variable — Primary UI text for body, captions, and some headings. Its variable nature allows for precise tailoring to content needs. · `--font-inter-variable`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 8px, 12px, 13px, 14px, 15px, 18px, 24px
- **Line height:** 0.80, 1.00, 1.07, 1.20, 1.30, 1.40
- **Letter spacing:** -0.02em, -0.018em, -0.01em, -0.001em, 0.03em
- **OpenType features:** `"cv01" on, "cv05" on, "cv09" on, "cv11" on, "dlig" on`
- **Role:** Primary UI text for body, captions, and some headings. Its variable nature allows for precise tailoring to content needs.

### Inter — Supportive body text and information hierarchy secondary to Inter Variable. Used for links and smaller headings. The range of weights provides granular control. · `--font-inter`
- **Substitute:** Inter
- **Weights:** 400, 500, 600, 700
- **Sizes:** 10px, 12px, 13px, 14px, 20px, 22px
- **Line height:** 0.83, 1.00, 1.10, 1.15, 1.20, 1.30, 1.40, 1.60
- **Letter spacing:** -0.053em, -0.05em, -0.04em, -0.036em, -0.03em, -0.02em, -0.01em, 0.02em
- **OpenType features:** `"cv01" on, "tnum" on`
- **Role:** Supportive body text and information hierarchy secondary to Inter Variable. Used for links and smaller headings. The range of weights provides granular control.

### Mona Sans — Distincitve display headings and prominent sub-headings. Its unique character contributes to brand personality in key areas. · `--font-mona-sans`
- **Substitute:** Inter
- **Weights:** 500
- **Sizes:** 12px, 13px, 17px, 18px, 62px
- **Line height:** 1.00, 1.20, 1.30, 1.70, 2.28
- **Letter spacing:** -0.05em, -0.046em
- **Role:** Distincitve display headings and prominent sub-headings. Its unique character contributes to brand personality in key areas.

### GT Walsheim Medium — Bold, impactful display text for hero sections and major headers. Its strong presence defines primary messaging. · `--font-gt-walsheim-medium`
- **Substitute:** Montserrat
- **Weights:** 500
- **Sizes:** 32px, 62px, 85px
- **Line height:** 0.95, 1.00, 1.13
- **Letter spacing:** -0.05em, -0.031em
- **OpenType features:** `"ss02" on`
- **Role:** Bold, impactful display text for hero sections and major headers. Its strong presence defines primary messaging.

### GT Walsheim Framer Medium — Largest, most authoritative display text, used sparingly for maximum impact in hero sections. Establishes the brand's confident tone. · `--font-gt-walsheim-framer-medium`
- **Substitute:** Montserrat
- **Weights:** 500
- **Sizes:** 110px
- **Line height:** 0.85
- **Letter spacing:** -0.05em
- **Role:** Largest, most authoritative display text, used sparingly for maximum impact in hero sections. Establishes the brand's confident tone.

### Open Runde — Specialized, highly condensed text for labels or metadata where space is limited and distinctiveness is desired. · `--font-open-runde`
- **Substitute:** Roboto Condensed
- **Weights:** 600
- **Sizes:** 9px
- **Line height:** 1.11
- **OpenType features:** `"cv01" on, "cv09" on`
- **Role:** Specialized, highly condensed text for labels or metadata where space is limited and distinctiveness is desired.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| nav-link | 13px | 1.07 | -0.13px | `--text-nav-link` |
| heading-sm | 20px | 1.1 | -0.6px | `--text-heading-sm` |
| heading | 24px | 1.4 | -0.24px | `--text-heading` |
| heading-lg | 32px | 0.95 | -1.6px | `--text-heading-lg` |
| display-sm | 62px | 1 | -3.1px | `--text-display-sm` |
| display-md | 85px | 1.13 | -4.25px | `--text-display-md` |
| display | 110px | 0.85 | -5.5px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 5 | 5px | `--spacing-5` |
| 6 | 6px | `--spacing-6` |
| 7 | 7px | `--spacing-7` |
| 8 | 8px | `--spacing-8` |
| 10 | 10px | `--spacing-10` |
| 12 | 12px | `--spacing-12` |
| 14 | 14px | `--spacing-14` |
| 15 | 15px | `--spacing-15` |
| 20 | 20px | `--spacing-20` |
| 30 | 30px | `--spacing-30` |
| 40 | 40px | `--spacing-40` |
| 47 | 47px | `--spacing-47` |
| 60 | 60px | `--spacing-60` |
| 80 | 80px | `--spacing-80` |
| 160 | 160px | `--spacing-160` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 10px |
| buttons | 100px |
| default | 8px |
| minimal | 1px |
| decorative | 15px |
| extra-large | 40px |
| large-cards | 30px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(0, 0, 0, 0.25) 0px 1px 2px 0px` | `--shadow-subtle` |
| subtle-2 | `rgb(9, 9, 9) 0px 0px 0px 2px` | `--shadow-subtle-2` |
| subtle-3 | `rgba(255, 255, 255, 0.1) 0px 0.5px 0px 0.5px, rgba(0, 0, ...` | `--shadow-subtle-3` |
| md | `rgba(0, 0, 0, 0.3) 0px 10px 10px 0px` | `--shadow-md` |
| lg | `rgba(0, 0, 0, 0.2) 0px 10px 20px 0px, rgba(0, 0, 0, 0.25)...` | `--shadow-lg` |
| lg-2 | `rgba(0, 0, 0, 0.6) -10px 10px 20px 10px` | `--shadow-lg-2` |
| md-2 | `rgba(0, 0, 0, 0.25) 0px 5px 10px 0px` | `--shadow-md-2` |
| subtle-4 | `rgba(255, 255, 255, 0.1) 0px 0px 0px 1px` | `--shadow-subtle-4` |
| xl | `rgba(0, 0, 0, 0.65) 0px 20px 30px 0px` | `--shadow-xl` |

### Layout

- **Section gap:** 60px
- **Card padding:** 40px
- **Element gap:** 10px

## Components

### Primary Ghost Button
**Role:** Action button

Ghost button with no background and transparent border, typically used for secondary actions or links. Text color can vary but is often an interactive blue or white. Padding 10px vertical, 14px horizontal for smaller instances.

### Secondary Button (White)
**Role:** Call to action

Filled button with a Cloud White (#FFFFFF) background and #0000EE text. Features a 100px border-radius, giving it a pill shape. Padding: 10px vertical, 14px horizontal.

### Tertiary Button (Ghost Frosted)
**Role:** Secondary action button

Ghost button with a semi-transparent white background rgba(255, 255, 255, 0.15) and a 100px border-radius. Text is typically #0000EE. Padding: 10px vertical, 14px horizontal.

### Text Button / Link
**Role:** Navigation or in-line action

Minimal button with rgba(255, 255, 255, 0.1) background and 40px border-radius, often used for subtle navigation within a dark context. Has #000000 text and 0px padding. Sometimes text only if backgroundColor is rgba(0,0,0,0).

### Default Card
**Role:** Content container

Standard card with Midnight Ink (#000000) background, 10px border-radius, no box shadow initially. Padding is often 0px, designed for content to define its own internal spacing.

### Elevated Card
**Role:** Highlighted content container

Card with Deep Graphite (#080808) background and a large 30px border-radius. No box shadow, relying on background contrast for elevation.

### Subtle Card
**Role:** Informational or less prominent content

Card with a very subtle background tint of rgba(0, 0, 0, 0.03), 20px border-radius and 40px internal padding. Used for lighter sections or within other components. Note: This color indicates usage on a light canvas, which is not the dominant theme here.

### Bordered White Card
**Role:** Featured content container with subtle visual appeal

Card with a rgba(255, 255, 255, 0.1) background and 30px border-radius. Features 1px padding, which likely acts as an internal border or separator.

## Do's and Don'ts

### Do
- Use Midnight Ink (#000000) for primary page backgrounds to maintain the immersive dark theme.
- Employ Cloud White (#FFFFFF) for all primary text and critical interactive button fills to ensure high contrast and readability.
- Apply Electric Blue (#0099FF) sparingly as an accent for interactive elements, borders, and hover states to guide user attention.
- Ensure all buttons feature a 100px border-radius to consistently achieve a 'pill' shape.
- Utilize GT Walsheim Medium and GT Walsheim Framer Medium for impactful headlines, prioritizing their distinctive weight 500.
- Maintain a compact density for element spacing, with a default elementGap of 10px, allowing visual elements to feel close-knit.
- Implement the subtle #021f33 blue tint in shadows for any elevated elements to keep depth cohesive with the brand palette.

### Don't
- Avoid using bright or overly saturated colors outside of the defined Electric Blue and Velocity Blue accents.
- Do not introduce square or sharp corners on buttons; they must always use the 100px pill radius.
- Do not use generic gray shadows; all shadows should leverage the blue-tinted #021f33 to maintain brand consistency.
- Avoid excessive spacing between elements; the design emphasizes a compact and dense information presentation.
- Do not use transparent backgrounds without a clear visual purpose; surfaces are typically solid or subtly layered near-blacks.
- Do not deviate from the specified font families for headings (GT Walsheim, Mona Sans), as they are key to brand typography.
- Avoid using light backgrounds exclusively, as the design system is fundamentally built upon a dark theme.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Midnight Ink | `#000000` | Base page background, deepest layer. |
| 1 | Deep Graphite | `#080808` | Primary card backgrounds, first layer of elevation. |
| 2 | Rich Coal | `#171717` | Secondary elevated surfaces, slightly darker than Deep Graphite for further distinction. |

## Elevation

- **Card / Elevated elements:** `rgba(0, 0, 0, 0.25) 0px 1px 2px 0px`
- **Card / Stronger Elevation:** `rgba(255, 255, 255, 0.1) 0px 0.5px 0px 0.5px, rgba(0, 0, 0, 0.25) 0px 10px 30px 0px`
- **Card / Subtle Elevation:** `rgb(9, 9, 9) 0px 0px 0px 2px`
- **Card / Deeper Visual Impact:** `rgba(0, 0, 0, 0.6) -10px 10px 20px 10px`

## Imagery

The visual language is a blend of product screenshots, abstract generative graphics, and minimalist iconography. Product screenshots are meticulously cropped, often presented within mock devices or with soft, gradient-tinted backdrops, showcasing the UI without much surrounding context. Abstract graphics are geometric, sometimes fluid, and use the brand's vivid blues and a broader rainbow of saturated colors against the dark background, serving decorative and atmospheric roles. Icons are typically monochrome (white on black or vice-versa), conveying information with clear, functional outlines. Imagery is used to either highlight product capabilities or create a dramatic, future-forward mood, often occupying significant visual space. The density is high, with images working alongside text rather than merely supporting it, creating an image-dominant experience in many sections.

## Layout

The page primarily uses a max-width contained layout section-by-section, though the hero element achieves a full-bleed effect by filling the entire viewport with the dark background. The hero features a large, centered headline and subtext with two signature pill-shaped buttons below. Sections often follow an alternating pattern of background colors (Midnight Ink, Deep Graphite) and content arrangements, though most appear on pure black. Content frequently uses a centered stack or a split-panel approach with text on one side and an image/product screenshot on the other. A prominent feature is a dense, responsive grid for case studies or product examples, showcasing a variety of brand aesthetics within the Framer ecosystem. Navigation is a sticky top bar, providing persistent access.

## Agent Prompt Guide

Quick Color Reference:
text: #FFFFFF
background: #000000
border: #000000
accent: #0099FF
primary action: #ffffff (filled action)

3-5 Example Component Prompts:
Create a hero section: Midnight Ink (#000000) background. Headline at 110px GT Walsheim Framer Medium, #FFFFFF, letter-spacing -0.05em, line-height 0.85. Subtext at 24px Inter Variable, #FFFFFF, letter-spacing -0.01em, line-height 1.40. Two buttons below, left: Secondary Button (White) with text 'Start for free', right: Tertiary Button (Ghost Frosted) with text 'Start with AI'.
Create an elevated card: Deep Graphite (#080808) background, 30px border-radius. Inside, use Mona Sans 62px #FFFFFF for a main title and Inter Variable 18px #999999 for body text. Add Subtle Card (rgba(0,0,0,0.03)) nested inside, 20px radius, 40px padding.
Create a navigation item: Inter Variable 14px #999999 text for general links. For active items, use Electric Blue (#0099FF) text.
Create a content section with three Default Cards in a row: Midnight Ink (#000000) background, 10px border-radius, no padding. Each card contains a Mona Sans 32px #FFFFFF subheading and Inter 14px #999999 body text. Gap between cards should be 10px.

## Similar Brands

- **Vercel** — Dark-mode UI with high-contrast text and a focus on developer tools and abstract graphics. Uses similar bold display typography.
- **Linear** — Minimalist dark aesthetic, strong reliance on typography for hierarchy, and sparse but impactful accent colors for interactivity.
- **Supabase** — Dark theme with bright, singular accent colors for CTAs and status indicators, often featuring prominent code blocks and technical product showcases.
- **Ray.so** — Dark, code-focused design with an emphasis on visual clarity and impactful typography against a deep background, uses bright accent glows.
- **PlanetScale** — Dark theme with strategic use of vibrant accent colors to highlight features and actions, often pairing them with crisp product visuals and clear type.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-deep-graphite: #080808;
  --color-rich-coal: #171717;
  --color-cloud-white: #FFFFFF;
  --color-mercury-gray: #999999;
  --color-steel-gray: #666666;
  --color-electric-blue: #0099FF;
  --color-velocity-blue: #0055FF;
  --color-shadow-tint: #021f33;
  --color-interactive-blue-tint: #0000ee;

  /* Typography — Font Families */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter-variable: 'Inter Variable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-mona-sans: 'Mona Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gt-walsheim-medium: 'GT Walsheim Medium', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gt-walsheim-framer-medium: 'GT Walsheim Framer Medium', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-open-runde: 'Open Runde', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-nav-link: 13px;
  --leading-nav-link: 1.07;
  --tracking-nav-link: -0.13px;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.1;
  --tracking-heading-sm: -0.6px;
  --text-heading: 24px;
  --leading-heading: 1.4;
  --tracking-heading: -0.24px;
  --text-heading-lg: 32px;
  --leading-heading-lg: 0.95;
  --tracking-heading-lg: -1.6px;
  --text-display-sm: 62px;
  --leading-display-sm: 1;
  --tracking-display-sm: -3.1px;
  --text-display-md: 85px;
  --leading-display-md: 1.13;
  --tracking-display-md: -4.25px;
  --text-display: 110px;
  --leading-display: 0.85;
  --tracking-display: -5.5px;

  /* Typography — Weights */
  --font-weight-thin: 100;
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-14: 14px;
  --spacing-15: 15px;
  --spacing-20: 20px;
  --spacing-30: 30px;
  --spacing-40: 40px;
  --spacing-47: 47px;
  --spacing-60: 60px;
  --spacing-80: 80px;
  --spacing-160: 160px;

  /* Layout */
  --section-gap: 60px;
  --card-padding: 40px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-sm: 1px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-xl-2: 15px;
  --radius-2xl: 20px;
  --radius-3xl: 30px;
  --radius-3xl-2: 40px;
  --radius-full: 50px;
  --radius-full-2: 100px;
  --radius-full-3: 200px;

  /* Named Radii */
  --radius-cards: 10px;
  --radius-buttons: 100px;
  --radius-default: 8px;
  --radius-minimal: 1px;
  --radius-decorative: 15px;
  --radius-extra-large: 40px;
  --radius-large-cards: 30px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.25) 0px 1px 2px 0px;
  --shadow-subtle-2: rgb(9, 9, 9) 0px 0px 0px 2px;
  --shadow-subtle-3: rgba(255, 255, 255, 0.1) 0px 0.5px 0px 0.5px, rgba(0, 0, 0, 0.25) 0px 10px 30px 0px;
  --shadow-md: rgba(0, 0, 0, 0.3) 0px 10px 10px 0px;
  --shadow-lg: rgba(0, 0, 0, 0.2) 0px 10px 20px 0px, rgba(0, 0, 0, 0.25) 0px 2px 4px 0px;
  --shadow-lg-2: rgba(0, 0, 0, 0.6) -10px 10px 20px 10px;
  --shadow-md-2: rgba(0, 0, 0, 0.25) 0px 5px 10px 0px;
  --shadow-subtle-4: rgba(255, 255, 255, 0.1) 0px 0px 0px 1px;
  --shadow-xl: rgba(0, 0, 0, 0.65) 0px 20px 30px 0px;

  /* Surfaces */
  --surface-midnight-ink: #000000;
  --surface-deep-graphite: #080808;
  --surface-rich-coal: #171717;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-deep-graphite: #080808;
  --color-rich-coal: #171717;
  --color-cloud-white: #FFFFFF;
  --color-mercury-gray: #999999;
  --color-steel-gray: #666666;
  --color-electric-blue: #0099FF;
  --color-velocity-blue: #0055FF;
  --color-shadow-tint: #021f33;
  --color-interactive-blue-tint: #0000ee;

  /* Typography */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter-variable: 'Inter Variable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-mona-sans: 'Mona Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gt-walsheim-medium: 'GT Walsheim Medium', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gt-walsheim-framer-medium: 'GT Walsheim Framer Medium', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-open-runde: 'Open Runde', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-nav-link: 13px;
  --leading-nav-link: 1.07;
  --tracking-nav-link: -0.13px;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.1;
  --tracking-heading-sm: -0.6px;
  --text-heading: 24px;
  --leading-heading: 1.4;
  --tracking-heading: -0.24px;
  --text-heading-lg: 32px;
  --leading-heading-lg: 0.95;
  --tracking-heading-lg: -1.6px;
  --text-display-sm: 62px;
  --leading-display-sm: 1;
  --tracking-display-sm: -3.1px;
  --text-display-md: 85px;
  --leading-display-md: 1.13;
  --tracking-display-md: -4.25px;
  --text-display: 110px;
  --leading-display: 0.85;
  --tracking-display: -5.5px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-14: 14px;
  --spacing-15: 15px;
  --spacing-20: 20px;
  --spacing-30: 30px;
  --spacing-40: 40px;
  --spacing-47: 47px;
  --spacing-60: 60px;
  --spacing-80: 80px;
  --spacing-160: 160px;

  /* Border Radius */
  --radius-sm: 1px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-xl-2: 15px;
  --radius-2xl: 20px;
  --radius-3xl: 30px;
  --radius-3xl-2: 40px;
  --radius-full: 50px;
  --radius-full-2: 100px;
  --radius-full-3: 200px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.25) 0px 1px 2px 0px;
  --shadow-subtle-2: rgb(9, 9, 9) 0px 0px 0px 2px;
  --shadow-subtle-3: rgba(255, 255, 255, 0.1) 0px 0.5px 0px 0.5px, rgba(0, 0, 0, 0.25) 0px 10px 30px 0px;
  --shadow-md: rgba(0, 0, 0, 0.3) 0px 10px 10px 0px;
  --shadow-lg: rgba(0, 0, 0, 0.2) 0px 10px 20px 0px, rgba(0, 0, 0, 0.25) 0px 2px 4px 0px;
  --shadow-lg-2: rgba(0, 0, 0, 0.6) -10px 10px 20px 10px;
  --shadow-md-2: rgba(0, 0, 0, 0.25) 0px 5px 10px 0px;
  --shadow-subtle-4: rgba(255, 255, 255, 0.1) 0px 0px 0px 1px;
  --shadow-xl: rgba(0, 0, 0, 0.65) 0px 20px 30px 0px;
}
```

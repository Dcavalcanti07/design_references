# AIUC — Style Reference
> Glacial blue monochrome

**Theme:** light

AIUC presents a meticulous, understated visual system built on stark monochromatic principles and subtle surface variations. Signature choices include a light canvas, compact and precise typography, and a prominent glacial blue gradient background that defines visual focus without relying on heavy colors. The design prioritizes clear information hierarchy through a disciplined use of grays and an almost complete absence of saturated color, creating an atmosphere of authority and calm.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page and primary surface backgrounds |
| Ink Black | `#000000` | `--color-ink-black` | Primary text, icon fills, strong borders, dark surface background |
| Charcoal | `#1a1a1a` | `--color-charcoal` | Button backgrounds, secondary text, border for headings |
| Dark Granite | `#323232` | `--color-dark-granite` | Body text, link text, borders for links and body content |
| Medium Gray | `#707070` | `--color-medium-gray` | Secondary text, subtle borders |
| Light Mist | `#979595` | `--color-light-mist` | Muted text, tertiary backgrounds |
| Pale Blue Wash | `#d3dfeb` | `--color-pale-blue-wash` | Subtle background surfaces, creating visual breaks with a cool tint |
| Soft Vanilla | `#eddfab` | `--color-soft-vanilla` | Highlight background for content sections, subtle warmth |

## Tokens — Typography

### Almarai — Headlines and prominent text elements — weight 300 for headlines is anti-convention; most sites use 600-700, this whisper-weight creates authority through restraint. · `--font-almarai`
- **Substitute:** Open Sans Light
- **Weights:** 300
- **Sizes:** 24px, 40px
- **Line height:** 1.20, 1.30
- **Letter spacing:** -0.0200em
- **Role:** Headlines and prominent text elements — weight 300 for headlines is anti-convention; most sites use 600-700, this whisper-weight creates authority through restraint.

### ABC Diatype Regular — Primary body text for paragraphs and descriptive content, ensuring legibility with a neutral, grounded feel. · `--font-abc-diatype-regular`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 14px, 16px, 18px, 20px
- **Line height:** 1.40, 1.50
- **Role:** Primary body text for paragraphs and descriptive content, ensuring legibility with a neutral, grounded feel.

### ABC Diatype Semi-Mono Regular — Used for code snippets, meta-information, and secondary navigation items, providing a technical yet readable distinction. · `--font-abc-diatype-semi-mono-regular`
- **Substitute:** IBM Plex Mono
- **Weights:** 400
- **Sizes:** 12px, 14px, 16px, 18px
- **Line height:** 1.10, 1.20, 1.30
- **Role:** Used for code snippets, meta-information, and secondary navigation items, providing a technical yet readable distinction.

### sans-serif — Fallback and base text for various UI elements like buttons, links, and minor labels, providing a system-level consistency. · `--font-sans-serif`
- **Substitute:** Arial
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.20
- **Role:** Fallback and base text for various UI elements like buttons, links, and minor labels, providing a system-level consistency.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body | 14px | 1.4 | — | `--text-body` |
| subheading | 18px | 1.5 | — | `--text-subheading` |
| heading | 24px | 1.2 | -0.48px | `--text-heading` |
| display | 40px | 1.3 | -0.8px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 6 | 6px | `--spacing-6` |
| 7 | 7px | `--spacing-7` |
| 8 | 8px | `--spacing-8` |
| 10 | 10px | `--spacing-10` |
| 12 | 12px | `--spacing-12` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 42 | 42px | `--spacing-42` |
| 64 | 64px | `--spacing-64` |
| 72 | 72px | `--spacing-72` |
| 100 | 100px | `--spacing-100` |
| 120 | 120px | `--spacing-120` |

### Border Radius

| Element | Value |
|---------|-------|
| pill | 1000px |
| cards | 4px |
| buttons | 3px |
| default | 4px |

### Layout

- **Page max-width:** 1200px
- **Section gap:** 40px
- **Card padding:** 16px
- **Element gap:** 10px

## Components

### Primary Dark Button
**Role:** Call to action button for primary actions

Solid Charcoal background (#1a1a1a), Canvas White text (#ffffff), 3px border-radius, 6px vertical padding, 16px horizontal padding.

### Outline Ghost Button
**Role:** Secondary action or ghost button

Transparent background, Dark Granite text (#323232), Dark Granite border (#323232), 3px border-radius, 6px vertical padding, 16px horizontal padding.

### Navigation Link
**Role:** Primary navigation item

Dark Granite text (#323232) using ABC Diatype Semi-Mono Regular at 18px, normal letter spacing, with minimal padding.

### Feature Card
**Role:** Content container for features or case studies

Implicit border, Canvas White background (#ffffff), 4px border-radius, and generous internal padding (around 24px).

### Accreditation Logo Grid Item
**Role:** Container for partner and client logos

Image-based, often uses a Canvas White background (#ffffff), has 4px border-radius, and can feature subtle backgrounds like Pale Blue Wash (#d3dfeb) or Soft Vanilla (#eddfab).

### Promotional Banner (Header)
**Role:** Top-most information bar for announcements

Ink Black background (#000000), Canvas White text (#ffffff) using sans-serif 12px, 1.2 lineHeight, compact (padding around 6px vertically).

## Do's and Don'ts

### Do
- Use Charcoal (#1a1a1a) for primary button backgrounds and Dark Granite (#323232) for ghost button borders.
- Apply 3px border-radius for all interactive elements like buttons and input fields.
- Prioritize Almarai Light (weight 300) for all headings to establish a quiet, authoritative tone.
- Maintain a monochromatic palette with Canvas White (#ffffff) as the dominant background, using Pale Blue Wash (#d3dfeb) for subtle section breaks.
- Employ ABC Diatype Regular for all body text, ensuring a consistent and highly legible reading experience.
- Utilize Ink Black (#000000) for primary headlines and Canvas White (#ffffff) for all main text on dark backgrounds.
- Apply an element gap of 10px between interactive components and text blocks to ensure comfortable density.

### Don't
- Do not introduce highly saturated colors; reserve color for the primary background visual.
- Avoid heavy shadows or overly dimensional elements; surfaces should remain flat and understated.
- Do not use bold or heavy weights for headlines; the brand's 'authority through restraint' relies on light typefaces.
- Avoid tight letter-spacing for body text; only headlines benefit from subtle tracking adjustments.
- Do not use generic system fonts for body or headings if ABC Diatype or Almarai are available; they are key to brand identity.
- Do not create complex gradient backgrounds for UI elements; simpler, single-color surfaces are preferred.
- Avoid excessive padding on ghost buttons; they should remain lightweight and visually subtle.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Canvas White | `#ffffff` | Base page background and default card surface |
| 2 | Pale Blue Wash | `#d3dfeb` | Subtle background tint for distinct content sections and elevated panels |
| 3 | Soft Vanilla | `#eddfab` | Alternative subtle background tint for specific content emphasis, without harsh contrast |

## Imagery

The site's imagery is characterized primarily by a striking abstract watercolor-like background of a glacial blue landscape, serving as a hero backdrop. This abstract visual creates atmosphere rather than conveying specific information. Logos of partners and customers are treated as monochrome SVGs or lightly tinted, placed without borders on clear backgrounds. No photography or complex illustrations are used; visual communication is almost exclusively through clean iconography and partner logos, reinforcing a focus on technical credibility and a lack of visual clutter. Icons, when present, are simple outlined glyphs, matching the overall sparse aesthetic and supporting functional clarity.

## Layout

The page primarily uses a max-width contained layout, approximately 1200px, centered on a Canvas White background. The hero section is full-bleed, featuring a centered headline in Almarai Light over an abstract glacial image that extends across the viewport. Below the hero, sections alternate between the Canvas White background and subtle tinted backgrounds like Pale Blue Wash or Soft Vanilla, maintaining a consistent vertical rhythm. Content is generally arranged in focused, centered stacks of text, or in simple two-column layouts featuring text on one side and a supporting visual (often a partner logo grid or simple diagram) on the other. A notable element is the partner logo grid, which groups logos tightly but with sufficient padding. Navigation consists of a crisp top bar with a left-aligned brand logo and a clean right-aligned 'Get Certified' button. A left-aligned, almost stacked text navigation menu exists visually under the main header, but it is not a sticky sidebar.

## Agent Prompt Guide

### Quick Color Reference
- text: #000000
- background: #ffffff
- border: #323232
- accent: #d3dfeb
- primary action: no distinct CTA color

### Example Component Prompts
- Create a section divider: thin Charcoal (#1a1a1a) line, 1px height, full width.
No distinct primary action color was observed; use the extracted neutral button treatments instead of inventing a filled CTA color.
- Create a Heading 1: "Certify and insure AI agents" in Almarai, weight 300, 40px, lineHeight 1.3, letterSpacing -0.8px, color #000000.
- Create a Navigation Link (Product): "Product" in ABC Diatype Semi-Mono Regular, weight 400, 18px, lineHeight 1.3, color #323232.

## Similar Brands

- **Anthropic** — Monochromatic palette, emphasis on sophisticated typography, and a serious, research-driven aesthetic.
- **Scale AI** — Clean, enterprise-focused design with sparse use of color, strong typography, and a focus on clarity rather than visual drama.
- **OpenAI** — Understated, almost minimalist UI, with a reliance on black, white, and gray, accented by a single, unique visual identifier (like a subtle abstract graphic).
- **Linear** — Emphasis on functional, clean UI without unnecessary flair, compact components, and precise typography on a light base.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ink-black: #000000;
  --color-charcoal: #1a1a1a;
  --color-dark-granite: #323232;
  --color-medium-gray: #707070;
  --color-light-mist: #979595;
  --color-pale-blue-wash: #d3dfeb;
  --color-soft-vanilla: #eddfab;

  /* Typography — Font Families */
  --font-almarai: 'Almarai', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-abc-diatype-regular: 'ABC Diatype Regular', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-abc-diatype-semi-mono-regular: 'ABC Diatype Semi-Mono Regular', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 14px;
  --leading-body: 1.4;
  --text-subheading: 18px;
  --leading-subheading: 1.5;
  --text-heading: 24px;
  --leading-heading: 1.2;
  --tracking-heading: -0.48px;
  --text-display: 40px;
  --leading-display: 1.3;
  --tracking-display: -0.8px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-6: 6px;
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-42: 42px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-100: 100px;
  --spacing-120: 120px;

  /* Layout */
  --page-max-width: 1200px;
  --section-gap: 40px;
  --card-padding: 16px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-full: 1000px;

  /* Named Radii */
  --radius-pill: 1000px;
  --radius-cards: 4px;
  --radius-buttons: 3px;
  --radius-default: 4px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-pale-blue-wash: #d3dfeb;
  --surface-soft-vanilla: #eddfab;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ink-black: #000000;
  --color-charcoal: #1a1a1a;
  --color-dark-granite: #323232;
  --color-medium-gray: #707070;
  --color-light-mist: #979595;
  --color-pale-blue-wash: #d3dfeb;
  --color-soft-vanilla: #eddfab;

  /* Typography */
  --font-almarai: 'Almarai', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-abc-diatype-regular: 'ABC Diatype Regular', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-abc-diatype-semi-mono-regular: 'ABC Diatype Semi-Mono Regular', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 14px;
  --leading-body: 1.4;
  --text-subheading: 18px;
  --leading-subheading: 1.5;
  --text-heading: 24px;
  --leading-heading: 1.2;
  --tracking-heading: -0.48px;
  --text-display: 40px;
  --leading-display: 1.3;
  --tracking-display: -0.8px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-6: 6px;
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-42: 42px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-100: 100px;
  --spacing-120: 120px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-full: 1000px;
}
```

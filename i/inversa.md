# INVERSA — Style Reference
> Wilderness at dusk

**Theme:** dark

This design system evokes a sense of stark, deliberate naturalism, like an aerial view of a verdant, wild landscape at dusk. The dominant color scheme consists of a muted dark background (#13140e) contrasted with a creamy almost-white (#f4f3e8), punctuated by infrequent, vivid lime-yellow accents (#ebfc72). The use of custom fonts, NB International Pro for headlines and JetBrains Mono for body text, creates a distinctive typographic voice that is both authoritative and technical. Limited rounded corners (3.6px) appear only on interactive elements like buttons, contributing to an overall grounded aesthetic.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Deep Forest | `#13140` | `--color-deep-forest` | Page backgrounds, major section backgrounds, dark typography, button backgrounds — provides a grounded, stable foundation for content. |
| Creme Paper | `#f4f3e8` | `--color-creme-paper` | Primary text color, link color, button text, header elements — stands out sharply against the dark background, ensuring high legibility. |
| Lime Accent | `#ebfc72` | `--color-lime-accent` | Call-to-action buttons, active states, key interactive highlights, and decorative touches — provides a jolt of vivid energy against the muted palette, drawing immediate attention. |
| Stone Grey | `#404040` | `--color-stone-grey` | Subtle borders and separators, secondary text in specific contexts like footers — adds a layer of visual separation without stark contrast. |
| Muddy Banks | `#84837b` | `--color-muddy-banks` | Minor background elements or subtle details — evokes the natural, earthy tones visible in the background imagery. |
| Lime Gradient | `linear-gradient(rgba(0, 0, 0, 0), rgba(0, 0, 0, 0) 3.6px, rgb(235, 252, 114) 3.6px, rgb(235, 252, 114) 135px)` | `--color-lime-gradient` | Used for specific interactive elements or unique visual flourishes where a subtle, directional highlight is desired to draw the eye. |
| Inverse Lime Gradient | `linear-gradient(to right, rgb(186, 205, 49), rgb(186, 205, 49) 3.6px, rgb(235, 252, 114) 3.6px, rgb(235, 252, 114) 135px)` | `--color-inverse-lime-gradient` | Alternative gradient for interactive elements, providing a slightly different shade transition. |

## Tokens — Typography

### NB International Pro — Primary headline and navigation font. Its precise, slightly condensed appearance communicates authority and technical sophistication, especially paired with the subtle letter-spacing for titles. · `--font-nb-international-pro`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 13px, 14px, 18px, 58px, 72px
- **Line height:** 0.90, 1.06, 1.20, 1.25, 1.62
- **Letter spacing:** -0.03em
- **Role:** Primary headline and navigation font. Its precise, slightly condensed appearance communicates authority and technical sophistication, especially paired with the subtle letter-spacing for titles.

### JetBrains Mono — Used for body text, button labels, and specific elements with a functional, data-driven feel. The monospace nature lends a technical, precise, and understated tone, ensuring clarity even at smaller sizes. · `--font-jetbrains-mono`
- **Substitute:** Fira Code
- **Weights:** 300, 400, 700
- **Sizes:** 13px, 14px, 18px, 29px, 65px
- **Line height:** 1.20, 1.25, 1.28
- **Role:** Used for body text, button labels, and specific elements with a functional, data-driven feel. The monospace nature lends a technical, precise, and understated tone, ensuring clarity even at smaller sizes.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 13px | 1.62 | -0.48px | `--text-caption` |
| body | 18px | 1.2 | -0.48px | `--text-body` |
| subheading | 29px | 1.25 | — | `--text-subheading` |
| heading | 58px | 1.06 | -1.74px | `--text-heading` |
| display | 72px | 0.9 | -2.16px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 5 | 5px | `--spacing-5` |
| 7 | 7px | `--spacing-7` |
| 14 | 14px | `--spacing-14` |
| 18 | 18px | `--spacing-18` |
| 21 | 21px | `--spacing-21` |
| 29 | 29px | `--spacing-29` |
| 59 | 59px | `--spacing-59` |
| 86 | 86px | `--spacing-86` |
| 104 | 104px | `--spacing-104` |
| 119 | 119px | `--spacing-119` |

### Border Radius

| Element | Value |
|---------|-------|
| buttons | 3.6px |

### Layout

- **Page max-width:** 810px
- **Section gap:** 59px
- **Card padding:** 18px
- **Element gap:** 14px

## Components

### Ghost Navigation Button
**Role:** Primary navigation interaction

Transparent background, Creme Paper text (#f4f3e8), and a 0px border-radius. Padding is 0px all around, relying on text spacing for visual separation. Uses NB International Pro at 13px weight 400 with -0.03em letter spacing.

### Dark Solid Button
**Role:** Secondary action items

Deep Forest background (#13140e) with Creme Paper text (#f4f3e8) and a 3.6px border-radius. Padding is 0px top/bottom, 18px left/right. Uses JetBrains Mono (likely 14px or 18px), hinting at a more functional or detailed action.

### Lime CTA Button
**Role:** Primary call-to-action

Vivid Lime Accent background (#ebfc72) with Deep Forest text (#13140e). Features a 3.6px border-radius and 0px top/bottom, 18px left/right padding. Uses JetBrains Mono for the label, ensuring the action feels clear and direct.

### Input Field
**Role:** User data entry

Transparent background with Creme Paper text (#f4f3e8) and a 0px border-radius. A bottom border in Creme Paper defines the input area. Padding is 0px top/right/left, 4.5px bottom. Text uses NB International Pro.

### Main Heading
**Role:** Section titles

Features NB International Pro, weight 400, in Creme Paper (#f4f3e8). Sizes include 58px and 72px, with tight line heights (0.90-1.06) and a subtle letter-spacing of -0.03em, creating an impactful yet refined presence.

### Body Text
**Role:** Paragraph content

Set in JetBrains Mono, likely 14px or 18px, with weights 300, 400, or 700. Employs a generous line height (1.20-1.28) for legibility against the dark background. Text color is Creme Paper (#f4f3e8).

### Copyright/Footer Text
**Role:** Legal and informational text

Smaller text (likely 13px JetBrains Mono) with Creme Paper (#f4f3e8) on a Deep Forest background, sometimes accented with thin Stone Grey (#404040) borders for visual separation within the footer.

## Do's and Don'ts

### Do
- Prioritize Creme Paper (#f4f3e8) on Deep Forest (#13140e) for maximum contrast and legibility.
- Use NB International Pro for all major headings and navigation elements to maintain an authoritative tone.
- Apply JetBrains Mono for body text, button labels, and any code-like snippets to emphasize precision.
- Utilize Lime Accent (#ebfc72) exclusively for primary calls-to-action or critical interactive states to command attention.
- Maintain a consistent 3.6px border-radius for all interactive buttons and input fields that require rounding.
- Employ a base spacing unit of 14px for general element gaps and 59px for vertical section spacing.
- Ensure the page content never exceeds a max-width of 810px to keep text lines readable and layout contained.

### Don't
- Avoid using highly saturated colors other than Lime Accent (#ebfc72) to maintain the muted, naturalistic palette.
- Do not introduce extensive shadow effects; the design relies on stark color contrast and flat surfaces for depth.
- Refrain from using excessively large or decorative typefaces that deviate from NB International Pro or JetBrains Mono.
- Disperse rounded corners beyond buttons and specific inputs; most elements should adhere to sharp edges.
- Do not use generic system fonts; the custom typefaces are essential to the brand's visual identity.
- Avoid large blocks of text in weights lighter than 400 to ensure readability on the dark background.
- Do not create layouts that extend beyond the 810px max-width without a specific full-bleed background treatment.

## Imagery

The visual language is dominated by high-resolution, full-bleed aerial photography of natural landscapes (rivers, forests, geological formations). The images are treated with a slightly desaturated, moody filter that harmonizes with the dark UI, conveying a sense of scale and interconnectedness without being overly dramatic. Imagery primarily serves as a powerful atmospheric background, reinforcing the brand's connection to ecological themes. There are minimal visible icons, and those present are monochrome, typically Creme Paper (#f4f3e8) outlines against Deep Forest (#13140e), appearing precise and functional.

## Layout

The page primarily utilizes a max-width contained layout, likely around 810px, centered on the screen, creating a focused reading experience. The hero section is a full-bleed visual with a dominant aerial photograph, overlaid with a large, centered headline and a distinct CTA. Subsequent sections follow a rhythm of consistent vertical spacing (approx. 59px). Content is arranged in clear, often single-column stacks with occasional text-adjacent visual elements on a dark background, establishing a very text-dominant, editorial feel. Navigation is a minimal top bar with 'INVERSA' branding on the left and a 'Menu' button on the right, unobtrusively integrated into the hero image.

## Agent Prompt Guide

### Quick Color Reference
- Text: `#f4f3e8`
- Background: `#13140e`
- CTA: `#ebfc72`
- Border: `#404040` (subtle)
- Accent: `#ebfc72`

### 3-5 Example Component Prompts
1. Create a hero section: full-bleed aerial background image. Centered headline 'Invasions move fast. Be faster.' in Creme Paper (#f4f3e8), NB International Pro, 72px, weight 400, line-height 0.9, letter-spacing -2.16px. Below, a Lime CTA Button with 'Explore Origin' text, JetBrains Mono, Deep Forest (#13140e) text, Lime Accent (#ebfc72) background, 3.6px radius, 0px top/bottom, 18px left/right padding.
2. Develop a content block: Deep Forest (#13140e) background. Inside, body text in JetBrains Mono, 18px, weight 400, line-height 1.2, in Creme Paper (#f4f3e8). Section padding is 59px top/bottom. Max content width 810px, centered.
3. Design a dark solid button: 'Inversa Leathers' text, JetBrains Mono, Creme Paper (#f4f3e8) text, Deep Forest (#13140e) background, 3.6px border-radius, 0px top/bottom, 18px left/right padding.
4. Create an input field: transparent background, Creme Paper (#f4f3e8) text, NB International Pro, 14px, with a Creme Paper (#f4f3e8) bottom border 1px thick. Padding 0px top/right/left, 4.5px bottom.

## Similar Brands

- **AIGA Design** — Monochromatic, text-heavy layout approach with prominent custom typography and a strong emphasis on content over decorative elements.
- **Oak** — Minimalist dark theme combined with carefully selected, strong custom typefaces for both headlines and body text, creating an exclusive and precise feel.
- **Field Notes** — The use of an earthy-toned highlight color against a dark or neutral background, emphasizing utility and a grounded aesthetic through color accents.
- **The New York Times** — Primarily text-driven, content-focused layout that prioritizes clear typography and high contrast for readability, despite thematic differences.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-deep-forest: #13140;
  --color-creme-paper: #f4f3e8;
  --color-lime-accent: #ebfc72;
  --color-stone-grey: #404040;
  --color-muddy-banks: #84837b;
  --color-lime-gradient: #ebfc72;
  --gradient-lime-gradient: linear-gradient(rgba(0, 0, 0, 0), rgba(0, 0, 0, 0) 3.6px, rgb(235, 252, 114) 3.6px, rgb(235, 252, 114) 135px);
  --color-inverse-lime-gradient: #ebfc72;
  --gradient-inverse-lime-gradient: linear-gradient(to right, rgb(186, 205, 49), rgb(186, 205, 49) 3.6px, rgb(235, 252, 114) 3.6px, rgb(235, 252, 114) 135px);

  /* Typography — Font Families */
  --font-nb-international-pro: 'NB International Pro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-jetbrains-mono: 'JetBrains Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 1.62;
  --tracking-caption: -0.48px;
  --text-body: 18px;
  --leading-body: 1.2;
  --tracking-body: -0.48px;
  --text-subheading: 29px;
  --leading-subheading: 1.25;
  --text-heading: 58px;
  --leading-heading: 1.06;
  --tracking-heading: -1.74px;
  --text-display: 72px;
  --leading-display: 0.9;
  --tracking-display: -2.16px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-7: 7px;
  --spacing-14: 14px;
  --spacing-18: 18px;
  --spacing-21: 21px;
  --spacing-29: 29px;
  --spacing-59: 59px;
  --spacing-86: 86px;
  --spacing-104: 104px;
  --spacing-119: 119px;

  /* Layout */
  --page-max-width: 810px;
  --section-gap: 59px;
  --card-padding: 18px;
  --element-gap: 14px;

  /* Border Radius */
  --radius-md: 3.6px;

  /* Named Radii */
  --radius-buttons: 3.6px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-deep-forest: #13140;
  --color-creme-paper: #f4f3e8;
  --color-lime-accent: #ebfc72;
  --color-stone-grey: #404040;
  --color-muddy-banks: #84837b;
  --color-lime-gradient: #ebfc72;
  --color-inverse-lime-gradient: #ebfc72;

  /* Typography */
  --font-nb-international-pro: 'NB International Pro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-jetbrains-mono: 'JetBrains Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 1.62;
  --tracking-caption: -0.48px;
  --text-body: 18px;
  --leading-body: 1.2;
  --tracking-body: -0.48px;
  --text-subheading: 29px;
  --leading-subheading: 1.25;
  --text-heading: 58px;
  --leading-heading: 1.06;
  --tracking-heading: -1.74px;
  --text-display: 72px;
  --leading-display: 0.9;
  --tracking-display: -2.16px;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-7: 7px;
  --spacing-14: 14px;
  --spacing-18: 18px;
  --spacing-21: 21px;
  --spacing-29: 29px;
  --spacing-59: 59px;
  --spacing-86: 86px;
  --spacing-104: 104px;
  --spacing-119: 119px;

  /* Border Radius */
  --radius-md: 3.6px;
}
```

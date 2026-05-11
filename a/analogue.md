# Analogue — Style Reference
> Matte black precision instrument. A single focused beam of light highlights intricate details against a deep, absorbing dark.

**Theme:** dark

Analogue's design system evokes a sense of understated analog precision, mirroring the brand's focus on classic gaming hardware. It uses a strictly monochromatic grayscale palette with stark black backgrounds and white text, punctuated only by occasional product renders that introduce vivid color. Generous negative space and precise typography create an atmosphere of luxury and meticulous craftsmanship, while deeply rounded pill-shaped elements offer a subtle, almost mechanical softness.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Obsidian | `#000000` | `--color-obsidian` | Page backgrounds, elevated surfaces, primary button background — the foundational darkness that defines the brand's aesthetic. Provides an ideal canvas for product imagery. |
| Glacial White | `#ffffff` | `--color-glacial-white` | Primary text color, button text, active states. Serves as a crisp counterpoint to Obsidian, ensuring legibility and drawing attention. Also used for reverse buttons. |
| Frost Gray | `#e5e7eb` | `--color-frost-gray` | Subtle surface accents, borders on interactive elements. Its near-white value allows for a high contrast with Obsidian while being distinct from pure Glacial White. |
| Steel Accent | `#bfbfbf` | `--color-steel-accent` | Secondary text in specific contexts, subtle dividers. |
| Faded Gray | `#999999` | `--color-faded-gray` | Tertiary text, less prominent headings. Offers reduced contrast for hierarchical distinction. |

## Tokens — Typography

### circularXx — Body text, navigation, input fields, and smaller headings. The slightly condensed, geometric linearity at weight 400 with subtle letter-spacing creates a technical, precise voice. · `--font-circularxx`
- **Substitute:** Circular Std
- **Weights:** 400
- **Sizes:** 13px, 15px, 16px, 18px, 19px, 21px, 26px, 35px, 47px, 53px
- **Line height:** 0.80, 1.00, 1.11, 1.14, 1.15, 1.20, 1.23, 1.50
- **Letter spacing:** -0.39, -0.45, -0.48, -0.54, -0.57, -0.63, -0.78
- **OpenType features:** `"ss08"`
- **Role:** Body text, navigation, input fields, and smaller headings. The slightly condensed, geometric linearity at weight 400 with subtle letter-spacing creates a technical, precise voice.

### circularXx — Primary headings and display text. The medium weight with tight, negative letter-spacing for larger sizes gives display headlines a strong, impactful presence while retaining the technical precision. · `--font-circularxx`
- **Substitute:** Circular Std
- **Weights:** 450
- **Sizes:** 13px, 15px, 16px, 18px, 19px, 21px, 26px, 35px, 47px, 53px
- **Line height:** 0.80, 1.00, 1.11, 1.14, 1.15, 1.20, 1.23, 1.50
- **Letter spacing:** -0.78, -1.05, -1.41, -1.59
- **OpenType features:** `"ss08"`
- **Role:** Primary headings and display text. The medium weight with tight, negative letter-spacing for larger sizes gives display headlines a strong, impactful presence while retaining the technical precision.

### circularXx — Emphasized text, subheadings, and interactive elements where a slightly stronger voice than weight 400 is desired without resorting to bold. Maintains the precise character of the typeface. · `--font-circularxx`
- **Substitute:** Circular Std
- **Weights:** 500
- **Sizes:** 13px, 15px, 16px, 18px, 19px, 21px, 26px, 35px, 47px, 53px
- **Line height:** 0.80, 1.00, 1.11, 1.14, 1.15, 1.20, 1.23, 1.50
- **Letter spacing:** -0.45, -0.54, -0.63, -0.78
- **OpenType features:** `"ss08"`
- **Role:** Emphasized text, subheadings, and interactive elements where a slightly stronger voice than weight 400 is desired without resorting to bold. Maintains the precise character of the typeface.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body | 15px | 1.2 | -0.45px | `--text-body` |
| subheading | 18px | 1.15 | -0.54px | `--text-subheading` |
| heading | 26px | 1.14 | -0.78px | `--text-heading` |
| heading-lg | 35px | 1.11 | -1.05px | `--text-heading-lg` |
| display | 53px | 0.8 | -1.59px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** spacious

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 6 | 6px | `--spacing-6` |
| 12 | 12px | `--spacing-12` |
| 16 | 16px | `--spacing-16` |
| 18 | 18px | `--spacing-18` |
| 26 | 26px | `--spacing-26` |
| 29 | 29px | `--spacing-29` |
| 35 | 35px | `--spacing-35` |
| 41 | 41px | `--spacing-41` |
| 47 | 47px | `--spacing-47` |
| 103 | 103px | `--spacing-103` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 17.6256px |
| buttons | 16777200px |

### Layout

- **Section gap:** 41-103px
- **Card padding:** 26px
- **Element gap:** 3-18px

## Components

### Primary Button
**Role:** Calls to action

White background with Obsidian text. Displays a distinctive super-elliptical 'pill' shape. Padding: 11.75px vertical, 47px horizontal. Typography: circularXx, weight 400, size 15px. Border color: Frost Gray.

### Secondary Button
**Role:** Calls to action (dark mode)

Obsidian background with Glacial White text. Displays a distinctive super-elliptical 'pill' shape. Padding: 11.75px vertical, 47px horizontal. Typography: circularXx, weight 400, size 15px. Border color: Frost Gray.

### Text Link Button
**Role:** Tertiary action with embedded icon

Transparent background with Glacial White text. No padding, no border radius, effectively a text link with button functionality. Typography: circularXx, weight 400, size 15px.

### Header Navigation Item
**Role:** Main site navigation

Glacial White text against Obsidian background, typography circularXx weight 400, size 15px. No discernible padding or special states for the items themselves beyond active link color changes.

### Footer Navigation Item
**Role:** Secondary site navigation

Glacial White text against Obsidian background, typography circularXx weight 400, size 15px. Appears in columnar lists within the footer.

### Pill Tag
**Role:** Status indicators or labels

Examples like 'Available Now' are primary buttons. While no explicit tag component provided, the radical `16777200px` border radius for buttons suggests a consistent 'pill' shape for any small, contained information block would be idiomatic to the design system.

## Do's and Don'ts

### Do
- Use Obsidian (#000000) for all main page and card backgrounds to maintain the deep, dark aesthetic.
- Prioritize Glacial White (#ffffff) for primary text and calls to action against dark backgrounds to ensure high contrast and legibility.
- Apply `17.6256px` border radius to all card-like containers, and the maximum `16777200px` (or full pill shape) to buttons and tags.
- Employ circularXx (substitute Circular Std) with precise negative letter-spacing for all typography, specifically targeting `-0.0300em` for body text and tighter for headlines.
- Maintain generous vertical spacing between sections, using `41px` to `103px` as a base, to create visual breathing room and emphasize content blocks.
- Utilize Frost Gray (#e5e7eb) sparingly for borders and subtle element distinctions, reserving it for secondary contrast against Obsidian.
- Ensure all interactive text elements use Glacial White (#ffffff) at circularXx weight 400, size 15px, with subtle letter spacing adjustments.

### Don't
- Avoid using highly saturated or bright colors outside of product photography; the palette is strictly monochromatic.
- Do not use box-shadows for elevation; depth is created through background changes between Obsidian and Frost Gray, or product photography.
- Refrain from using square or lightly rounded corners for buttons or interactive tags; embrace the distinct `16777200px` pill radius.
- Do not vary line-height significantly for body text; aim for the `1.5` ratio for optimal reading comfort against the dark background.
- Avoid breaking compositional elements with hard lines or excessive borders; rely instead on spacing and background color shifts to define areas.
- Do not use generic system fonts; always implement circularXx (or Circular Std) to maintain the brand's precise and modern typographic identity.
- Never use `999999` (Faded Gray) or `bfbfbf` (Steel Accent) for critical text or primary actions, as their lower contrast is reserved for secondary information.

## Imagery

The visual language focuses on high-fidelity product photography. Products are presented as hero elements, often in tight, studio-like crops, isolated against the deep Obsidian background. The treatment is consistently clean and precise, with products sometimes presented in a slight explosion or deconstructed view to showcase components or accessories (like game cartridges). There's no lifestyle photography, instead a direct, almost reverent focus on the hardware itself. Graphics are minimal, limited to subtle brand logos and UI elements. Icons are typically simple, monochromatic outlines or filled shapes that blend into the UI, serving functional roles rather than decorative ones.

## Layout

The site employs a full-bleed, dark background model that creates an immersive, cinematic feel. Content within sections appears largely horizontally centered, creating a focused presentation. The hero section often features large, centrally placed product photography against the full-bleed dark background with a concise, prominent headline. Sections are defined by generous vertical spacing (41-103px) and occasionally by alternating slight shifts in background color within the neutral palette, but without harsh dividers. Content arrangements vary from centered stacks of text and product images to horizontal grids for elements like review cards. The navigation is a minimalist sticky top bar with subtle Glacial White links on Obsidian.

## Agent Prompt Guide

### Quick Color Reference
- Text: #ffffff (Glacial White)
- Background: #000000 (Obsidian)
- CTA Primary: #ffffff (Glacial White)
- CTA Secondary: #000000 (Obsidian)
- Border/Accent: #e5e7eb (Frost Gray)

### Example Component Prompts
1. Create a hero section: Obsidian background. Centered headline 'Restock' at 53px circularXx weight 450, #ffffff, letter-spacing -1.59px, line-height 0.8. Below it, a Primary Button: #ffffff background, #000000 text, 16777200px radius, 11.75px vertical padding, 47px horizontal padding, circularXx weight 400, size 15px. 
2. Create a review card: Background #000000, 17.6256px border-radius, 26px padding. Text '5/5' in #ffffff circularXx weight 450 size 26px, line-height 1.14, letter-spacing -0.78px. Below it, a quote 'The Analogue 3D has solved my N64 woes...' in #ffffff circularXx weight 400 size 15px.
3. Design a dark-themed footer: Obsidian background. Glacial White #ffffff text for links, circularXx weight 400, size 15px, letter-spacing -0.45px. Layout links in columns with a 6px element gap.
4. Create a product feature section: Obsidian background, headline 'Analogue 3D Shipping Now' at 47px circularXx weight 450, #ffffff, letter-spacing -1.41px. Center-align the content. Below it, a Secondary Button: #000000 background, #ffffff text, 16777200px radius, 11.75px vertical padding, 47px horizontal padding, circularXx weight 400, size 15px.

## Similar Brands

- **Apple** — Shares a dedication to product-focused photography and a clean, minimalist aesthetic with significant white (or dark) space around hero products.
- **Teenage Engineering** — Employs technical, precise typography, a minimalist monochromatic palette, and a focus on industrial design for its hardware products.
- **Bang & Olufsen** — Utilizes a premium dark aesthetic, high-contrast typography, and elegant product presentation to convey luxury and sophisticated technology.
- **Nothing** — Known for a stark, monochromatic palette and precise, technical typography, often used to highlight product innovation and sleek design.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-obsidian: #000000;
  --color-glacial-white: #ffffff;
  --color-frost-gray: #e5e7eb;
  --color-steel-accent: #bfbfbf;
  --color-faded-gray: #999999;

  /* Typography — Font Families */
  --font-circularxx: 'circularXx', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 15px;
  --leading-body: 1.2;
  --tracking-body: -0.45px;
  --text-subheading: 18px;
  --leading-subheading: 1.15;
  --tracking-subheading: -0.54px;
  --text-heading: 26px;
  --leading-heading: 1.14;
  --tracking-heading: -0.78px;
  --text-heading-lg: 35px;
  --leading-heading-lg: 1.11;
  --tracking-heading-lg: -1.05px;
  --text-display: 53px;
  --leading-display: 0.8;
  --tracking-display: -1.59px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-w450: 450;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-6: 6px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-18: 18px;
  --spacing-26: 26px;
  --spacing-29: 29px;
  --spacing-35: 35px;
  --spacing-41: 41px;
  --spacing-47: 47px;
  --spacing-103: 103px;

  /* Layout */
  --section-gap: 41-103px;
  --card-padding: 26px;
  --element-gap: 3-18px;

  /* Border Radius */
  --radius-2xl: 17.6256px;

  /* Named Radii */
  --radius-cards: 17.6256px;
  --radius-buttons: 16777200px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-obsidian: #000000;
  --color-glacial-white: #ffffff;
  --color-frost-gray: #e5e7eb;
  --color-steel-accent: #bfbfbf;
  --color-faded-gray: #999999;

  /* Typography */
  --font-circularxx: 'circularXx', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 15px;
  --leading-body: 1.2;
  --tracking-body: -0.45px;
  --text-subheading: 18px;
  --leading-subheading: 1.15;
  --tracking-subheading: -0.54px;
  --text-heading: 26px;
  --leading-heading: 1.14;
  --tracking-heading: -0.78px;
  --text-heading-lg: 35px;
  --leading-heading-lg: 1.11;
  --tracking-heading-lg: -1.05px;
  --text-display: 53px;
  --leading-display: 0.8;
  --tracking-display: -1.59px;

  /* Spacing */
  --spacing-6: 6px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-18: 18px;
  --spacing-26: 26px;
  --spacing-29: 29px;
  --spacing-35: 35px;
  --spacing-41: 41px;
  --spacing-47: 47px;
  --spacing-103: 103px;

  /* Border Radius */
  --radius-2xl: 17.6256px;
}
```

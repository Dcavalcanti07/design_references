# Framer — Style Reference
> Inky command center

**Theme:** dark

Framer's design pulsates like a high-contrast digital canvas, where every element is deliberately placed against a deep, inky black. The interplay of brilliant white typography and electric blue accents (#0099ff) against the #000000 background creates an immediate sense of clarity and impact, reminiscent of a command-line interface or a designer's dark-mode workspace. Generously rounded elements, especially 100px pill buttons, introduce soft dynamism into an otherwise sharp, modern aesthetic, making complex tools feel approachable. Subtle layers of near-black surfaces (#080808) provide depth without relying on heavy shadows, maintaining a lightweight, performant feel.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Absolute Zero | `#000000` | `--color-absolute-zero` | Page background, primary surface, deep canvas. Provides stark contrast for all content. |
| Charcoal Canvas | `#080808` | `--color-charcoal-canvas` | Secondary surface, subtle elevated panels, card backgrounds. Creates depth against Absolute Zero. |
| Vapor White | `#ffffff` | `--color-vapor-white` | Primary text, heading text, button text, foreground elements. High contrast for readability on dark backgrounds. |
| Ash Gray | `#999999` | `--color-ash-gray` | Muted text, secondary labels, disabled states. Provides subtler information. |
| Silver Mist | `#cccccc` | `--color-silver-mist` | Sub-secondary text, dividing lines. Softer than Ash Gray for less prominent elements. |
| Slate Dust | `#666666` | `--color-slate-dust` | Tertiary text, less important information, placeholder text. |
| Deep Space | `#171717` | `--color-deep-space` | Tertiary surface layer, slightly darker elevated elements. |
| Electric Blue | `#0099ff` | `--color-electric-blue` | Interactive elements, links, active states, indicators, primary accent. Draws attention and signifies action. |
| Sky Indigo | `#0055ff` | `--color-sky-indigo` | Secondary accent for graphical elements, subtle interactive states where Electric Blue might be too strong for background. |
| Cyan Fade | `linear-gradient(rgba(5, 255, 159, 0) 0%, rgba(0, 0, 0, 0.06) 100%)` | `--color-cyan-fade` | Subtle top-to-bottom gradient for background elements, adding a hint of color variation. |
| Tangerine | `#fd5d5c` | `--color-tangerine` | Highlight for specific cards or callouts, purely decorative. |
| Goldenrod | `#fac80a` | `--color-goldenrod` | Highlight for specific cards or callouts, purely decorative. |
| Emerald | `#33c659` | `--color-emerald` | Highlight for specific cards or callouts, purely decorative. |
| Amethyst | `#9869fd` | `--color-amethyst` | Highlight for specific cards or callouts, purely decorative. |

## Tokens — Typography

### GT Walsheim Framer Medium — Display headline. Extremely large, tight kerning for maximum impact. · `--font-gt-walsheim-framer-medium`
- **Substitute:** Montserrat
- **Weights:** 500
- **Sizes:** 110px
- **Line height:** 0.85
- **Letter spacing:** -0.0500em
- **Role:** Display headline. Extremely large, tight kerning for maximum impact.

### GT Walsheim Medium — Primary headings (H1-H3). Characterized by compact line height and slight negative letter-spacing for a bold, condensed feel. Features stylistic alternates and tabular numbers. · `--font-gt-walsheim-medium`
- **Substitute:** Montserrat
- **Weights:** 500
- **Sizes:** 32px, 62px, 85px
- **Line height:** 0.95, 1.00, 1.13
- **Letter spacing:** -0.0500em at 85px, -0.0310em at 62px, normal at 32px
- **OpenType features:** `"ss02", "tnum"`
- **Role:** Primary headings (H1-H3). Characterized by compact line height and slight negative letter-spacing for a bold, condensed feel. Features stylistic alternates and tabular numbers.

### Mona Sans — Secondary headings (H4-H6). Offers a more neutral counterpart to GT Walsheim for less prominent titles. · `--font-mona-sans`
- **Substitute:** Inter
- **Weights:** 500
- **Sizes:** 12px, 13px, 17px, 18px, 62px
- **Line height:** 1.00, 1.20, 1.30, 1.70, 2.28
- **Letter spacing:** -0.0500em at 62px, -0.0460em for 17px/18px, normal elsewhere
- **Role:** Secondary headings (H4-H6). Offers a more neutral counterpart to GT Walsheim for less prominent titles.

### Inter Variable — Body text, subheadings, labels. Highly versatile with broad stylistic controls, ensuring clarity across various information densities. Features a wide range of stylistic sets. · `--font-inter-variable`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 8px, 12px, 13px, 14px, 15px, 18px, 24px
- **Line height:** 0.80, 1.00, 1.07, 1.20, 1.30, 1.40
- **Letter spacing:** -0.0200em at 18px and 24px, -0.0180em, -0.0100em, -0.0010em, 0.0300em for specific contexts
- **OpenType features:** `"cv06", "cv11", "dlig", "ss03"`
- **Role:** Body text, subheadings, labels. Highly versatile with broad stylistic controls, ensuring clarity across various information densities. Features a wide range of stylistic sets.

### Inter — Paragraphs, navigation, general UI text. Provides robust readability with specific handling for tabular numbers and stylistic alternates. · `--font-inter`
- **Substitute:** Inter
- **Weights:** 400, 500, 600, 700
- **Sizes:** 10px, 12px, 13px, 14px, 15px, 16px, 20px, 22px
- **Line height:** 0.83, 1.00, 1.10, 1.15, 1.20, 1.30, 1.40, 1.60
- **Letter spacing:** -0.0530em to 0.0300em
- **OpenType features:** `"cv01", "cv05", "cv09", "cv11", "dlig"`
- **Role:** Paragraphs, navigation, general UI text. Provides robust readability with specific handling for tabular numbers and stylistic alternates.

### Open Runde — Fine print, metadata. Distinctive small-caps style via stylistic sets. · `--font-open-runde`
- **Substitute:** Varela Round
- **Weights:** 600
- **Sizes:** 9px
- **Line height:** 1.11
- **Letter spacing:** normal
- **OpenType features:** `"cv01", "cv09"`
- **Role:** Fine print, metadata. Distinctive small-caps style via stylistic sets.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body | 14px | 1.3 | — | `--text-body` |
| body-lg | 18px | 1.4 | -0.02px | `--text-body-lg` |
| subheading | 24px | 1.07 | -0.02px | `--text-subheading` |
| heading-sm | 32px | 1 | — | `--text-heading-sm` |
| heading | 62px | 1 | -0.031px | `--text-heading` |
| heading-lg | 85px | 0.95 | -0.05px | `--text-heading-lg` |
| display | 110px | 0.85 | -0.05px | `--text-display` |

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
| cards | 8px |
| images | 8px |
| inputs | 8px |
| modals | 12px |
| buttons | 100px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgb(9, 9, 9) 0px 0px 0px 2px` | `--shadow-subtle` |
| subtle-2 | `rgba(255, 255, 255, 0.1) 0px 0.5px 0px 0.5px, rgba(0, 0, ...` | `--shadow-subtle-2` |
| md | `rgba(0, 0, 0, 0.3) 0px 10px 10px 0px` | `--shadow-md` |
| lg | `rgba(0, 0, 0, 0.2) 0px 10px 20px 0px, rgba(0, 0, 0, 0.25)...` | `--shadow-lg` |

### Layout

- **Section gap:** 64px
- **Card padding:** 10px
- **Element gap:** 4px

## Components

### Primary Hero Button
**Role:** Call to action

backgroundColor=rgba(255, 255, 255, 0.15), color=rgb(0, 0, 238) (browser default link color, interpret as Electric Blue #0099ff), borderRadius=100px, paddingTop=10px, paddingRight=14px, paddingBottom=10px, paddingLeft=14px. Text uses Inter font family. Appears as a white ghost button on dark background.

### Secondary Ghost Button
**Role:** Secondary call to action

backgroundColor=rgba(0, 0, 0, 0), color=rgb(0, 0, 0) (browser default, interpret as Vapor White #ffffff against dark), borderRadius=0px, paddingTop=0px, paddingRight=0px, paddingBottom=0px, paddingLeft=0px. Used for subtle actions or navigation within sections.

### Solid Primary Button
**Role:** High-emphasis call to action

backgroundColor=rgb(255, 255, 255), color=rgb(0, 0, 238) (browser default, interpret as Electric Blue #0099ff), borderRadius=100px, paddingTop=10px, paddingRight=14px, paddingBottom=10px, paddingLeft=14px. Used for critical actions on lighter backgrounds or when extra prominence is needed.

### Icon-only Button
**Role:** Action without text label

backgroundColor=rgba(255, 255, 255, 0.1), color=rgb(0, 0, 0) (browser default, interpret as Vapor White #ffffff), borderRadius=40px, paddingTop=0px, paddingRight=0px, paddingBottom=0px, paddingLeft=0px. Used for subtle actions like closing modals or navigation controls.

### Navigation Link
**Role:** Top navigation item

color=Vapor White (#ffffff), font-size=14px, font-weight=Inter Regular (400), no explicit background, padding: 0. Configured for horizontal menu display.

### Case Study Card
**Role:** Showcase customer work

background-color: Charcoal Canvas (#080808) or a variety of vivid accent colors (Tangerine, Goldenrod, Emerald, Amethyst) for visual distinction. Border radius: 8px. Text content uses various Inter weights. Often contains images or abstract patterns.

### Small Feature Card
**Role:** Highlight key features

min-height: 200px (inferred). backgroundColor=rgba(255, 255, 255, 0.15) or Charcoal Canvas (#080808). borderRadius=8px. Padding is implied 10-15px. Contains a small title and short body text.

### Text Input / Field
**Role:** User data entry

Implicit background matching surrounding surface (e.g. Charcoal Canvas #080808). Text color: Vapor White (#ffffff). Placeholder text color: Ash Gray (#999999). Focus ring: rgb(9, 9, 9) 0px 0px 0px 2px (Dark Shadow).

## Do's and Don'ts

### Do
- Use Absolute Zero (#000000) as the primary background for all page sections to enforce a consistent dark theme.
- Apply Vapor White (#ffffff) for all main headings and body text on dark backgrounds to ensure maximum contrast and readability.
- Reserve Electric Blue (#0099ff) exclusively for interactive elements like links, buttons, and active states to guide user attention.
- Utilize 100px border radius for all primary calls-to-action to create distinct pill-shaped buttons.
- Employ the GT Walsheim fonts (GT Walsheim Framer Medium, GT Walsheim Medium) for all major headlines to convey the brand's unique character.
- Maintain a compact line height for all display and heading typography (e.g., 0.85 for 110px, 0.95 for 85px) to achieve a dense, type-driven aesthetic.
- Layer surfaces using Absolute Zero (#000000) and Charcoal Canvas (#080808) to create depth without relying on prominent shadows.

### Don't
- Avoid using light backgrounds for entire page sections; the theme is predominantly dark.
- Do not use generic system fonts for prominent headings; GT Walsheim is critical for brand identity.
- Do not introduce additional accent colors beyond Electric Blue (#0099ff) and the designated card highlights (Tangerine, Goldenrod, Emerald, Amethyst).
- Avoid box shadows for general elevation; subtle background color shifts (e.g., #000000 to #080808) provide the primary sense of layering.
- Do not use letter-spacing: normal for headlines; specific negative letter-spacing values (-0.0500em, -0.0310em) are integral to the typographic style.
- Do not vary border radius for buttons; stick to 100px for pill shapes and 8px for cards/inputs.
- Do not introduce complex gradients or textures on primary surfaces; the background should remain clean and near-monochromatic.

## Imagery

The visual language is a blend of tight product screenshots, abstract geometric shapes with vibrant accent colors, and stylized photography. Product screenshots are typically contained within cards, often featuring a subtle background or drop shadow. Illustrations are geometric and abstract, using brand accent colors (Tangerine, Goldenrod, Emerald, Amethyst) to add visual interest and break up the dark interface. Photography is used sparingly for social proof, featuring desaturated or monochrome portraits within circular masks. Icons are monochrome, outlined, and minimal, primarily in Vapor White against dark backgrounds. Imagery primarily serves to showcase products, demonstrate features, or provide decorative color accents, balanced with a high density of textual content.

## Layout

The layout primarily uses a full-bleed dark canvas for the background. Content is centered and constrained within an implied max-width (no explicit pageMaxWidth, but content blocks are visually centered and not full-width). The hero section features a centered, oversized headline on a full-bleed dark background, with prominent pill-shaped call-to-action buttons. Subsequent sections alternate between large, impactful text blocks and grids of featured content. There's a prominent 3-column card grid for 'Made with Framer' examples, showcasing various visual styles within a consistent structural framework. Vertical spacing between sections is generous but not excessively sprawling, contributing to a compact visual density.

## Agent Prompt Guide

4. **Create a Testimonial Section:** Set background to Absolute Zero (#000000). Use a `heading-sm` sized GT Walsheim Medium (32px, #ffffff, lineHeight 1) for the main quote. Underneath, add two lines of `body` text (Inter, 14px, #a6a6a6) for the author's name and title. The testimonial card itself could use Charcoal Canvas (#080808) with 8px radius.

## Similar Brands

- **Vercel** — Dark-mode UI with sharp typography and a focus on developer tools and performance, featuring a clear accent color.
- **Linear** — High-contrast dark theme, precise typography with subtle background variations for depth, and minimal use of color for interaction.
- **Supabase** — Uses a dark background with vibrant accent colors for key elements, demonstrating a modern, technical aesthetic with strong visual hierarchy.
- **Notion** — Features a strong, clear sans-serif typography on a clean base, with an emphasis on functional and direct UI elements.
- **Webflow** — Emphasizes design freedom and powerful tools with a clean, high-contrast visual style.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-absolute-zero: #000000;
  --color-charcoal-canvas: #080808;
  --color-vapor-white: #ffffff;
  --color-ash-gray: #999999;
  --color-silver-mist: #cccccc;
  --color-slate-dust: #666666;
  --color-deep-space: #171717;
  --color-electric-blue: #0099ff;
  --color-sky-indigo: #0055ff;
  --color-cyan-fade: #05ff9f;
  --gradient-cyan-fade: linear-gradient(rgba(5, 255, 159, 0) 0%, rgba(0, 0, 0, 0.06) 100%);
  --color-tangerine: #fd5d5c;
  --color-goldenrod: #fac80a;
  --color-emerald: #33c659;
  --color-amethyst: #9869fd;

  /* Typography — Font Families */
  --font-gt-walsheim-framer-medium: 'GT Walsheim Framer Medium', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gt-walsheim-medium: 'GT Walsheim Medium', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-mona-sans: 'Mona Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter-variable: 'Inter Variable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-open-runde: 'Open Runde', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 14px;
  --leading-body: 1.3;
  --text-body-lg: 18px;
  --leading-body-lg: 1.4;
  --tracking-body-lg: -0.02px;
  --text-subheading: 24px;
  --leading-subheading: 1.07;
  --tracking-subheading: -0.02px;
  --text-heading-sm: 32px;
  --leading-heading-sm: 1;
  --text-heading: 62px;
  --leading-heading: 1;
  --tracking-heading: -0.031px;
  --text-heading-lg: 85px;
  --leading-heading-lg: 0.95;
  --tracking-heading-lg: -0.05px;
  --text-display: 110px;
  --leading-display: 0.85;
  --tracking-display: -0.05px;

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
  --section-gap: 64px;
  --card-padding: 10px;
  --element-gap: 4px;

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
  --radius-cards: 8px;
  --radius-images: 8px;
  --radius-inputs: 8px;
  --radius-modals: 12px;
  --radius-buttons: 100px;

  /* Shadows */
  --shadow-subtle: rgb(9, 9, 9) 0px 0px 0px 2px;
  --shadow-subtle-2: rgba(255, 255, 255, 0.1) 0px 0.5px 0px 0.5px, rgba(0, 0, 0, 0.25) 0px 10px 30px 0px;
  --shadow-md: rgba(0, 0, 0, 0.3) 0px 10px 10px 0px;
  --shadow-lg: rgba(0, 0, 0, 0.2) 0px 10px 20px 0px, rgba(0, 0, 0, 0.25) 0px 2px 4px 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-absolute-zero: #000000;
  --color-charcoal-canvas: #080808;
  --color-vapor-white: #ffffff;
  --color-ash-gray: #999999;
  --color-silver-mist: #cccccc;
  --color-slate-dust: #666666;
  --color-deep-space: #171717;
  --color-electric-blue: #0099ff;
  --color-sky-indigo: #0055ff;
  --color-cyan-fade: #05ff9f;
  --color-tangerine: #fd5d5c;
  --color-goldenrod: #fac80a;
  --color-emerald: #33c659;
  --color-amethyst: #9869fd;

  /* Typography */
  --font-gt-walsheim-framer-medium: 'GT Walsheim Framer Medium', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gt-walsheim-medium: 'GT Walsheim Medium', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-mona-sans: 'Mona Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter-variable: 'Inter Variable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-open-runde: 'Open Runde', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 14px;
  --leading-body: 1.3;
  --text-body-lg: 18px;
  --leading-body-lg: 1.4;
  --tracking-body-lg: -0.02px;
  --text-subheading: 24px;
  --leading-subheading: 1.07;
  --tracking-subheading: -0.02px;
  --text-heading-sm: 32px;
  --leading-heading-sm: 1;
  --text-heading: 62px;
  --leading-heading: 1;
  --tracking-heading: -0.031px;
  --text-heading-lg: 85px;
  --leading-heading-lg: 0.95;
  --tracking-heading-lg: -0.05px;
  --text-display: 110px;
  --leading-display: 0.85;
  --tracking-display: -0.05px;

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
  --shadow-subtle: rgb(9, 9, 9) 0px 0px 0px 2px;
  --shadow-subtle-2: rgba(255, 255, 255, 0.1) 0px 0.5px 0px 0.5px, rgba(0, 0, 0, 0.25) 0px 10px 30px 0px;
  --shadow-md: rgba(0, 0, 0, 0.3) 0px 10px 10px 0px;
  --shadow-lg: rgba(0, 0, 0, 0.2) 0px 10px 20px 0px, rgba(0, 0, 0, 0.25) 0px 2px 4px 0px;
}
```

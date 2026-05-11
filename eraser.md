# Eraser — Style Reference
> Obsidian command center with neon telemetry.

**Theme:** dark

Eraser embraces a dark-mode, developer-centric aesthetic, characterized by a deep obsidian background and crisp, technical typography. Information is presented within softly rounded cards that feature subtle, offset box shadows, creating a distinct physical presence. The color palette is largely monochromatic, relying on shades of gray for structure, with focused, vivid accents of violet, blue, pink, and yellow used sparingly to highlight key elements and provide visual coding cues. Gradients are employed for atmospheric depth and to define abstract UI elements, rather than for broad surface treatments or brand splashes.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Obsidian | `#181818` | `--color-obsidian` | Primary page background, base surface for components |
| Steel Gray | `#e3e3e3` | `--color-steel-gray` | Primary text on dark backgrounds, icon strokes, active states |
| Graphite | `#4b4b4b` | `--color-graphite` | Secondary text, muted links, subtle borders and fills |
| Ghost | `#ffffff` | `--color-ghost` | Filled button backgrounds for primary actions, contrasting text on dark chromatic backgrounds |
| Ink | `#080808` | `--color-ink` | Shadow color for elevated components, deep structural accents |
| Cloud Gray | `#f6f6f6` | `--color-cloud-gray` | Prominent headings and important text where slightly softer tone than Steel Gray is desired |
| System Gray | `#878787` | `--color-system-gray` | Neutral link borders and text, default helper text |
| Discord Purple | `#9985ff` | `--color-discord-purple` | Violet outline accent for tags, dividers, and focused UI edges. Do not promote it to the primary CTA color |
| Lavender Mist | `#ddccff` | `--color-lavender-mist` | Accent color for headings, subtly lighter borders |
| Deep Violet Shadow | `#363054` | `--color-deep-violet-shadow` | Shadow tint for specific card elevations |
| Chartreuse Glow | `#d6ca6f` | `--color-chartreuse-glow` | Yellow outline accent for tags, dividers, and focused UI edges. Do not promote it to the primary CTA color |
| Digital Blue | `#94dbff` | `--color-digital-blue` | Blue outline accent for tags, dividers, and focused UI edges. Do not promote it to the primary CTA color |
| Fuchsia Highlight | `#ffa3c2` | `--color-fuchsia-highlight` | Red outline accent for tags, dividers, and focused UI edges. Do not promote it to the primary CTA color |
| Violet Gradient Base | `linear-gradient(rgb(80, 67, 134), rgb(50, 41, 95) 50%)` | `--color-violet-gradient-base` | Primary background gradient for atmospheric sections, providing depth to the obsidian canvas |
| Violet Radial Aura | `radial-gradient(circle closest-side at 50% 35%, rgba(84, 70, 151, 0.25), rgba(0, 0, 0, 0) 82%)` | `--color-violet-radial-aura` | Radial gradient for soft ambient glow behind key elements |
| Amber Gradient Base | `linear-gradient(rgb(112, 103, 38), rgb(75, 70, 34) 50%)` | `--color-amber-gradient-base` | Secondary background gradient for atmospheric sections |
| Amber Radial Aura | `radial-gradient(circle closest-side, rgba(207, 193, 66, 0.3), rgba(0, 0, 0, 0) 68%)` | `--color-amber-radial-aura` | Radial gradient for soft ambient glow |
| Rose Gradient Base | `linear-gradient(rgb(115, 37, 63), rgb(74, 34, 48) 50%)` | `--color-rose-gradient-base` | Tertiary background gradient for atmospheric sections |
| Rose Radial Aura | `radial-gradient(circle closest-side at 50% 35%, rgba(179, 54, 96, 0.25), rgba(0, 0, 0, 0) 82%)` | `--color-rose-radial-aura` | Radial gradient for soft ambient glow |

## Tokens — Typography

### Inter — Primary UI font for body text, paragraphs, labels, and general interface elements. Its generous line-height provides comfortable reading on dark surfaces. · `--font-inter`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400, 500, 600, 700
- **Sizes:** 8px, 11px, 12px, 13px, 14px, 16px, 18px, 20px, 26px
- **Line height:** 1.15, 1.23, 1.25, 1.35, 1.50
- **Letter spacing:** -0.0190em
- **Role:** Primary UI font for body text, paragraphs, labels, and general interface elements. Its generous line-height provides comfortable reading on dark surfaces.

### National 2 Condensed — Distinctive display font for major headings and hero statements, conveying impact through its condensed form and heavy weight. The tighter letter-spacing enhances its blocky, architectural feel. · `--font-national-2-condensed`
- **Substitute:** Impact, sans-serif-condensed
- **Weights:** 700
- **Sizes:** 48px, 72px, 90px
- **Line height:** 0.85
- **Letter spacing:** -0.0070em, -0.0050em
- **Role:** Distinctive display font for major headings and hero statements, conveying impact through its condensed form and heavy weight. The tighter letter-spacing enhances its blocky, architectural feel.

### Jetbrainsmono — Monospaced font for code snippets, technical labels, and diagram content, emphasizing precision and developer-centricity. · `--font-jetbrainsmono`
- **Substitute:** Menlo, monospace
- **Weights:** 400, 600
- **Sizes:** 14px
- **Line height:** 1.00, 1.23
- **Letter spacing:** normal
- **Role:** Monospaced font for code snippets, technical labels, and diagram content, emphasizing precision and developer-centricity.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 11px | 1.5 | -0.019px | `--text-caption` |
| body | 16px | 1.5 | -0.019px | `--text-body` |
| subheading | 20px | 1.25 | -0.019px | `--text-subheading` |
| heading | 26px | 1.25 | -0.019px | `--text-heading` |
| heading-lg | 48px | 0.85 | -0.48px | `--text-heading-lg` |
| display | 72px | 0.85 | -0.504px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 8 | 8px | `--spacing-8` |
| 12 | 12px | `--spacing-12` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 36 | 36px | `--spacing-36` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 60 | 60px | `--spacing-60` |
| 72 | 72px | `--spacing-72` |
| 112 | 112px | `--spacing-112` |
| 120 | 120px | `--spacing-120` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 16px |
| buttons | 4px |
| elements | 8px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(0, 0, 0, 0.3) 6px 6px 0px 0px` | `--shadow-subtle` |
| subtle-2 | `rgba(153, 133, 255, 0.3) 6px 6px 0px 0px` | `--shadow-subtle-2` |

### Layout

- **Section gap:** 72px
- **Card padding:** 16px
- **Element gap:** 24px

## Components

### Ghost Header Button
**Role:** Navigation and secondary actions in the header.

Text only, Inter (400, 16px, 1.5) with #e3e3e3 color. No background or border.

### Primary Filled Button
**Role:** Main calls to action.

Background: #ffffff, Text: #171717, Border Radius: 4px. Padding: 8px vertical, 17.92px horizontal. Font: Inter (500, 16px, 1.5).

### Secondary Filled Button
**Role:** Less prominent actions, within darker components.

Background: #1c1c1c, Text: #ffffff, Border Radius: 4px. Padding: 8px vertical, 18px horizontal. Font: Inter (500, 16px, 1.5).

### Shadowed Card
**Role:** Content containers with visual emphasis.

Background: #1c1c1c, Border Radius: 16px. Box Shadow: rgba(0, 0, 0, 0.3) 6px 6px 0px 0px. No internal padding specified for this variant.

### Plain Card
**Role:** Content containers without elevation.

Background: #1c1c1c, Border Radius: 16px. No shadow. Internal padding: 30px top/right/left, 20px bottom.

### Highlight Card
**Role:** Content container with an accent shadow to draw attention.

Background: #171717, Border Radius: 8px. Box Shadow: rgba(153, 133, 255, 0.3) 6px 6px 0px 0px. Internal padding: 16px top, 20px right/bottom/left.

### Diagram UI Element
**Role:** Interactive elements within the diagram canvas.

Uses Jetbrainsmono (14px) for labels, with accent colors like #94dbff, #ffa3c2, #d6ca6f, #ddccff for visual differentiation and connections. Often bordered with #e3e3e3 or #4b4b4b.

## Do's and Don'ts

### Do
- Use Obsidian (#181818) as the default background for all primary content areas and page bodies.
- Apply Steel Gray (#e3e3e3) for all critical text and headings, ensuring high contrast on dark backgrounds.
- Employ the National 2 Condensed (700) font for all major headings (display, heading-lg), implementing the specified tight letter-spacing.
- Utilize Ghost (#ffffff) as the background for primary call-to-action buttons, pairing it with #171717 for text.
- Apply 16px border-radius to all card-like containers, and 4px to all interactive buttons.
- Introduce Discord Purple (#9985ff) as a border for interactive cards or specific diagram elements to signify importance or interactivity.
- Implement the rgba(0, 0, 0, 0.3) 6px 6px 0px 0px shadow for the Shadowed Card component to provide a distinct, offset visual depth.

### Don't
- Do not use highly saturated colors for large background areas or extensive text blocks; reserve them for accents and highlights.
- Avoid generic border-radius values; adhere strictly to 16px for cards and 4px for buttons for component consistency.
- Do not use white backgrounds for sections unless explicitly defined as a primary action button or a specific content block that requires high contrast.
- Avoid using Inter for prominent display headings; its moderate letter-spacing would disrupt the condensed, architectural feel of National 2 Condensed.
- Do not introduce drop shadows that solely rely on blur; the characteristic offset shadow (`6px 6px 0px 0px`) is core to the elevation style.
- Unless specifically for code or technical labels, do not use Jetbrainsmono; it is reserved for its distinct technical appearance.
- Refrain from using `normal` letter-spacing for major headlines to maintain the engineered, compact typography style.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Obsidian Canvas | `#181818` | Base page background, deepest layer. |
| 1 | Dark Panel | `#1c1c1c` | Primary component surface, cards and larger content blocks. |
| 2 | Interactive Surface | `#171717` | Surface for elements with distinct interactive shadows or accents, often lighter than the base panel. |

## Elevation

- **Shadowed Card:** `rgba(0, 0, 0, 0.3) 6px 6px 0px 0px`
- **Highlight Card:** `rgba(153, 133, 255, 0.3) 6px 6px 0px 0px`

## Imagery

Imagery on Eraser is primarily utilitarian and minimalist. Product screenshots are featured, tightly cropped or within device mockups, showcasing the UI without extraneous context. Illustrations are abstract, using filled, geometric shapes that often integrate brand accent colors or monochromatic tones, serving as decorative atmosphere rather than content. Icons are outlined or filled, with thin strokes or solid forms, maintaining a technical aesthetic. There is a high density of UI elements and product visuals, making the design visually rich but focused on functionality rather than lifestyle photography or complex artistic rendering. The overall treatment is contained within components, avoiding full-bleed visuals.

## Layout

The page primarily follows a max-width contained layout, likely around 1200px, centered on the page. The hero section is full-bleed, using a deep obsidian background with atmospheric gradients. Content is structured with clear section breaks, often indicated by generous vertical spacing (72px). Within sections, content frequently alternates between text-left/visual-right patterns or features card grids. The density is comfortable, with ample breathing room between major sections, but information-dense within individual UI components. Navigation is a persistent top bar, featuring ghost buttons and a distinct primary filled action button.

## Agent Prompt Guide

### Quick Color Reference
- text: #e3e3e3
- background: #181818
- border: #9985ff
- accent: #9985ff
- primary action: #ffffff (filled action)

### 3-5 Example Component Prompts
- Create a Primary Action Button: #ffffff background, #181818 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
- Design a feature card: Plain Card component with padding 30px top/right/left, 20px bottom. Headline 'Diagram as Code' using Inter 600 at 26px, #e3e3e3. Body text 'Maintainable and legible diagrams' using Inter 400 at 16px, #e3e3e3.
- Build a team logo grid: On an Obsidian Canvas background, display a grid of company logos. Each logo should be contained within a 1px #4b4b4b border, with 16px padding on all sides, and 4px border-radius. Arrange with 24px element gaps between logos.

## Similar Brands

- **Linear** — Shares a dark mode UI with minimalistic, angular components and focused use of brand colors for interactive elements.
- **Vercel** — Exhibits a similar developer-tool aesthetic with a dark theme, crisp typography, and high-contrast UI elements often featuring subtle shadows.
- **Supabase** — Uses a dark background with prominent, brightly colored accent text and UI elements, particularly in code examples and feature highlights.
- **GitHub (Dark Mode)** — Employs a deep dark background, detailed UI for technical content, and emphasizes clarity and organization over decorative flair, with code-centric typography.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-obsidian: #181818;
  --color-steel-gray: #e3e3e3;
  --color-graphite: #4b4b4b;
  --color-ghost: #ffffff;
  --color-ink: #080808;
  --color-cloud-gray: #f6f6f6;
  --color-system-gray: #878787;
  --color-discord-purple: #9985ff;
  --color-lavender-mist: #ddccff;
  --color-deep-violet-shadow: #363054;
  --color-chartreuse-glow: #d6ca6f;
  --color-digital-blue: #94dbff;
  --color-fuchsia-highlight: #ffa3c2;
  --color-violet-gradient-base: #504386;
  --gradient-violet-gradient-base: linear-gradient(rgb(80, 67, 134), rgb(50, 41, 95) 50%);
  --color-violet-radial-aura: #544697;
  --gradient-violet-radial-aura: radial-gradient(circle closest-side at 50% 35%, rgba(84, 70, 151, 0.25), rgba(0, 0, 0, 0) 82%);
  --color-amber-gradient-base: #706726;
  --gradient-amber-gradient-base: linear-gradient(rgb(112, 103, 38), rgb(75, 70, 34) 50%);
  --color-amber-radial-aura: #cfc142;
  --gradient-amber-radial-aura: radial-gradient(circle closest-side, rgba(207, 193, 66, 0.3), rgba(0, 0, 0, 0) 68%);
  --color-rose-gradient-base: #73253f;
  --gradient-rose-gradient-base: linear-gradient(rgb(115, 37, 63), rgb(74, 34, 48) 50%);
  --color-rose-radial-aura: #b33660;
  --gradient-rose-radial-aura: radial-gradient(circle closest-side at 50% 35%, rgba(179, 54, 96, 0.25), rgba(0, 0, 0, 0) 82%);

  /* Typography — Font Families */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-national-2-condensed: 'National 2 Condensed', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-jetbrainsmono: 'Jetbrainsmono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.5;
  --tracking-caption: -0.019px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.019px;
  --text-subheading: 20px;
  --leading-subheading: 1.25;
  --tracking-subheading: -0.019px;
  --text-heading: 26px;
  --leading-heading: 1.25;
  --tracking-heading: -0.019px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 0.85;
  --tracking-heading-lg: -0.48px;
  --text-display: 72px;
  --leading-display: 0.85;
  --tracking-display: -0.504px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-60: 60px;
  --spacing-72: 72px;
  --spacing-112: 112px;
  --spacing-120: 120px;

  /* Layout */
  --section-gap: 72px;
  --card-padding: 16px;
  --element-gap: 24px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-2xl: 16px;

  /* Named Radii */
  --radius-cards: 16px;
  --radius-buttons: 4px;
  --radius-elements: 8px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.3) 6px 6px 0px 0px;
  --shadow-subtle-2: rgba(153, 133, 255, 0.3) 6px 6px 0px 0px;

  /* Surfaces */
  --surface-obsidian-canvas: #181818;
  --surface-dark-panel: #1c1c1c;
  --surface-interactive-surface: #171717;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-obsidian: #181818;
  --color-steel-gray: #e3e3e3;
  --color-graphite: #4b4b4b;
  --color-ghost: #ffffff;
  --color-ink: #080808;
  --color-cloud-gray: #f6f6f6;
  --color-system-gray: #878787;
  --color-discord-purple: #9985ff;
  --color-lavender-mist: #ddccff;
  --color-deep-violet-shadow: #363054;
  --color-chartreuse-glow: #d6ca6f;
  --color-digital-blue: #94dbff;
  --color-fuchsia-highlight: #ffa3c2;
  --color-violet-gradient-base: #504386;
  --color-violet-radial-aura: #544697;
  --color-amber-gradient-base: #706726;
  --color-amber-radial-aura: #cfc142;
  --color-rose-gradient-base: #73253f;
  --color-rose-radial-aura: #b33660;

  /* Typography */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-national-2-condensed: 'National 2 Condensed', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-jetbrainsmono: 'Jetbrainsmono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.5;
  --tracking-caption: -0.019px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.019px;
  --text-subheading: 20px;
  --leading-subheading: 1.25;
  --tracking-subheading: -0.019px;
  --text-heading: 26px;
  --leading-heading: 1.25;
  --tracking-heading: -0.019px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 0.85;
  --tracking-heading-lg: -0.48px;
  --text-display: 72px;
  --leading-display: 0.85;
  --tracking-display: -0.504px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-60: 60px;
  --spacing-72: 72px;
  --spacing-112: 112px;
  --spacing-120: 120px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-2xl: 16px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.3) 6px 6px 0px 0px;
  --shadow-subtle-2: rgba(153, 133, 255, 0.3) 6px 6px 0px 0px;
}
```

# Gitbook — Style Reference
> Architectural blueprint on bright white

**Theme:** light

GitBook employs a crisp, structured aesthetic with a focus on product documentation. The visual system features abundant negative space, subtle surface differentiation, and a single vibrant orange accent color. Typography is precise and highly tracked, guiding the eye through dense information without visual clutter. Components favor soft curves and gentle elevation, projecting an approachable yet authoritative tone through careful restraint rather than overt decoration.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas | `#ffffff` | `--color-canvas` | Page backgrounds, primary card surfaces, active input backgrounds |
| Ink | `#1c1917` | `--color-ink` | Primary headings, active button backgrounds, dark text accents |
| Ash | `#57534d` | `--color-ash` | Body text, secondary text, border for muted elements |
| Stone | `#79716b` | `--color-stone` | Muted body text, secondary icons, subtle borders |
| Parchment | `#fafaf9` | `--color-parchment` | Secondary card backgrounds, slightly elevated surfaces |
| Whisper Gray | `#efeeed` | `--color-whisper-gray` | Subtle surface accents, very light card backgrounds, hover states |
| Outline Gray | `#e5e5e5` | `--color-outline-gray` | Subtle button and input borders |
| Obsidian | `#000000` | `--color-obsidian` | Hero headlines, critical UI text, dark icon fills |
| Sunset Orange | `#fe551b` | `--color-sunset-orange` | Decorative accents, illustrative elements, subtle background washes for differentiation |

## Tokens — Typography

### sans-serif — sans-serif — detected in extracted data but not described by AI · `--font-sans-serif`
- **Weights:** 400
- **Sizes:** 12px, 16px
- **Line height:** 1.2
- **Role:** sans-serif — detected in extracted data but not described by AI

### General Sans Variable — Hero headlines and major section titles, where impactful, tightly tracked text announces key sections. The variable bold weight provides visual strength. · `--font-general-sans-variable`
- **Substitute:** system-ui, sans-serif
- **Weights:** 700
- **Sizes:** 12px, 14px, 16px, 20px, 24px, 30px, 32px, 38px, 45px, 55px
- **Line height:** 1.00, 1.20, 1.30, 1.40, 1.50, 1.60
- **Letter spacing:** -0.0400em at 55px, -0.0300em at 45px, -0.0200em at 38px, 0.0100em at 12px
- **OpenType features:** `"blwf", "cv03", "cv04", "cv09", "cv11"`
- **Role:** Hero headlines and major section titles, where impactful, tightly tracked text announces key sections. The variable bold weight provides visual strength.

### Inter — Body text, subheadings, and UI labels. Its range of weights allows for hierarchy within text blocks while maintaining a consistent visual voice. · `--font-inter`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400, 500, 600
- **Sizes:** 10px, 11px, 12px, 14px, 15px, 16px, 20px
- **Line height:** 1.08, 1.18, 1.20, 1.30, 1.40, 1.60
- **Letter spacing:** -0.0300em at 20px, -0.0100em at 10px
- **OpenType features:** `"blwf", "cv03", "cv04", "cv09", "cv11"`
- **Role:** Body text, subheadings, and UI labels. Its range of weights allows for hierarchy within text blocks while maintaining a consistent visual voice.

### General Sans — Stand-alone body text components and feature descriptions. A specific weight and size choice for narrative blocks. · `--font-general-sans`
- **Substitute:** system-ui, sans-serif
- **Weights:** 500
- **Sizes:** 18px
- **Line height:** 1.60
- **Letter spacing:** -0.0100em
- **Role:** Stand-alone body text components and feature descriptions. A specific weight and size choice for narrative blocks.

### Geist Mono — Code snippets, technical terms, and small, functional labels requiring clear separation from general text. · `--font-geist-mono`
- **Substitute:** Space Mono
- **Weights:** 600
- **Sizes:** 10px, 14px
- **Line height:** 1.00, 1.30
- **Letter spacing:** -0.0200em
- **Role:** Code snippets, technical terms, and small, functional labels requiring clear separation from general text.

### General Sans Variable Variable Bold — General Sans Variable Variable Bold — detected in extracted data but not described by AI · `--font-general-sans-variable-variable-bold`
- **Weights:** 700
- **Sizes:** 12px, 14px, 16px, 20px, 24px, 30px, 32px, 38px, 45px, 55px
- **Line height:** 1, 1.2, 1.3, 1.4, 1.5, 1.6
- **Letter spacing:** -0.04, -0.03, -0.02, 0.01
- **OpenType features:** `"blwf", "cv03", "cv04", "cv09", "cv11"`
- **Role:** General Sans Variable Variable Bold — detected in extracted data but not described by AI

### Space Mono — Space Mono — detected in extracted data but not described by AI · `--font-space-mono`
- **Weights:** 400
- **Sizes:** 8px
- **Line height:** 1.3
- **Role:** Space Mono — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.18 | -0.1px | `--text-caption` |
| body | 16px | 1.4 | -0.16px | `--text-body` |
| subheading | 18px | 1.6 | -0.18px | `--text-subheading` |
| heading | 32px | 1.3 | -0.64px | `--text-heading` |
| heading-lg | 45px | 1.4 | -1.35px | `--text-heading-lg` |
| display | 55px | 1 | -2.2px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 5 | 5px | `--spacing-5` |
| 6 | 6px | `--spacing-6` |
| 8 | 8px | `--spacing-8` |
| 10 | 10px | `--spacing-10` |
| 12 | 12px | `--spacing-12` |
| 14 | 14px | `--spacing-14` |
| 15 | 15px | `--spacing-15` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |

### Border Radius

| Element | Value |
|---------|-------|
| full | 9999px |
| tags | 4px |
| cards | 16px |
| buttons | 99px |
| default | 8px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(0, 0, 0, 0.25) 0px 1px 2px 0px` | `--shadow-subtle` |
| md | `rgba(0, 0, 0, 0.15) 0px 4px 12px 0px` | `--shadow-md` |
| subtle-2 | `rgba(0, 0, 0, 0.05) 0px 1px 3px 0px, rgba(0, 0, 0, 0.05) ...` | `--shadow-subtle-2` |

### Layout

- **Section gap:** 40px
- **Card padding:** 12px
- **Element gap:** 10px

## Components

### Primary Filled Button
**Role:** Call to action

Filled with Ink (#1c1917) background and Canvas (#ffffff) white text, using 99px border-radius for a pill shape. Padding is 8px vertical, 20px horizontal. Uses Inter font, size 16px, weight 500.

### Ghost Button
**Role:** Secondary action

Transparent background with a subtle fill of rgba(0, 0, 0, 0.04) and Ink (#1c1917) text. Pill-shaped with 99px border-radius. Padding is 10-12px vertical, 14px horizontal.

### Text Link Button
**Role:** Tertiary action, inline link

Canvas (#ffffff) background with Ink (#1c1917) text, no border-radius (square shape). Padding is 8px vertical, 10px horizontal. Used for compact actions.

### Text Link Button (Transparent)
**Role:** Inline navigation, minimal action

Fully transparent background with Ink (#1c1917) text. Pill-shaped with 99px border-radius. Padding is 10px vertical, 15px horizontal. Used for embedded actions.

### Feature Card (Parchment)
**Role:** Informational display

Parchment (#fafaf9) background, 16px border-radius. No explicit padding or shadow, relying on content for internal spacing.

### Feature Card (Canvas)
**Role:** Prominent information display

Canvas (#ffffff) background, 16px border-radius. No explicit padding or shadow.

### Screenshot Display Card
**Role:** Visual content container

Canvas (#ffffff) background, 8px border-radius, no shadow or padding. Used for containing product screenshots or visual examples.

### Subtle Elevated Card
**Role:** Minor elevated content

Whisper Gray (#efeeed) background with 8px 8px 0px 0px border-radius. No explicit padding or shadow. Used for subtle visual separation.

## Do's and Don'ts

### Do
- Prioritize Ink (#1c1917) for primary headings and Canvas (#ffffff) for backgrounds to maintain a clean contrast.
- Use 99px border-radius for all interactive buttons and tags to ensure a consistent pill shape (e.g., 'Start for free').
- Apply General Sans Variable, weight 700 with aggressive negative letter-spacing for all display and large heading text.
- Utilize Parchment (#fafaf9) or Whisper Gray (#efeeed) for secondary card backgrounds, creating subtle layered surfaces.
- Maintain a clear element gap of 10px for vertical stacking of UI elements and 8px for smaller interactive elements.
- Ensure textual contrast: Ink (#1c1917) on Canvas (#ffffff) surfaces, and Canvas (#ffffff) text on Ink (#1c1917) button backgrounds.
- Reserve Sunset Orange (#fe551b) primarily for decorative accents, illustrations, or as a background wash to avoid competition with functional UI.

### Don't
- Avoid using Sunset Orange (#fe551b) for primary calls to action or essential text; its role is decorative accent, not functional interface element.
- Do not introduce heavy drop shadows; prefer subtle 1px shadows or no shadows to maintain the light, modern aesthetic.
- Refrain from using strong, saturated colors beyond Sunset Orange; the palette is intentionally restrained to highlight content.
- Do not deviate from the specified General Sans, Inter, Geist Mono, and system sans-serif fonts; no additional typefaces should be introduced.
- Avoid tight spacing for body text; ensure adequate line-height and letter-spacing are respected to preserve readability.
- Do not apply rounded corners to full-bleed sections or backgrounds; surfaces should adhere to the specified radii of 8px, 16px, or 99px for components.
- Do not use black #000000 for body text; reserve it for large, impactful headlines where maximum contrast is desired.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas | `#ffffff` | Primary page and main card backgrounds, providing a bright and spacious base. |
| 1 | Parchment | `#fafaf9` | Secondary card backgrounds, slightly differentiated to indicate grouping or a subtle layer. |
| 2 | Whisper Gray | `#efeeed` | Subtle background washes, hover states, and lighter secondary card variants. |

## Elevation

- **Card:** `rgba(0, 0, 0, 0.15) 0px 4px 12px 0px`
- **Subtle UI Elements:** `rgba(0, 0, 0, 0.25) 0px 1px 2px 0px`
- **Button:** `rgba(0, 0, 0, 0.05) 0px 1px 3px 0px, rgba(0, 0, 0, 0.05) 0px 1px 2px -1px`

## Agent Prompt Guide

Quick Color Reference: 
text: #1c1917
background: #ffffff
border: #e5e5e5
accent: #fe551b
primary action: #1c1917 (filled action)

Example Component Prompts:
1. Create a Primary Action Button: #1c1917 background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Design a feature card: Parchment (#fafaf9) background, 16px border-radius, elementGap 10px internally. Include a bold subheading "GitBook Agent" using Inter weight 600 at 20px, and body text below it with Inter weight 400 at 16px, color Ash (#57534d). 
3. Create a ghost button for navigation: transparent background, Ink (#1c1917) text, 99px border-radius, 10px vertical padding, 15px horizontal padding. The text should be Inter weight 500 at 16px.
4. Design a small decorative info label: Sunset Orange (#fe551b) background, Canvas (#ffffff) text, 4px border-radius, using Inter weight 600 at 12px, 6px horizontal padding.

## Similar Brands

- **Notion** — Shared emphasis on crisp, organized content, abundant whitespace, and a focus on documentation/productivity.
- **Linear** — Clean, almost austere UI design, strong typographic hierarchy, and minimalist component aesthetic.
- **Vercel** — Structured layouts, emphasis on technical content presentation, and subtle use of accent colors on neutral backgrounds.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas: #ffffff;
  --color-ink: #1c1917;
  --color-ash: #57534d;
  --color-stone: #79716b;
  --color-parchment: #fafaf9;
  --color-whisper-gray: #efeeed;
  --color-outline-gray: #e5e5e5;
  --color-obsidian: #000000;
  --color-sunset-orange: #fe551b;

  /* Typography — Font Families */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-general-sans-variable: 'General Sans Variable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-general-sans: 'General Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geist-mono: 'Geist Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-general-sans-variable-variable-bold: 'General Sans Variable Variable Bold', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-space-mono: 'Space Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.18;
  --tracking-caption: -0.1px;
  --text-body: 16px;
  --leading-body: 1.4;
  --tracking-body: -0.16px;
  --text-subheading: 18px;
  --leading-subheading: 1.6;
  --tracking-subheading: -0.18px;
  --text-heading: 32px;
  --leading-heading: 1.3;
  --tracking-heading: -0.64px;
  --text-heading-lg: 45px;
  --leading-heading-lg: 1.4;
  --tracking-heading-lg: -1.35px;
  --text-display: 55px;
  --leading-display: 1;
  --tracking-display: -2.2px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-14: 14px;
  --spacing-15: 15px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 12px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-3xl-2: 28px;
  --radius-full: 88px;
  --radius-full-2: 99px;
  --radius-full-3: 1000px;

  /* Named Radii */
  --radius-full: 9999px;
  --radius-tags: 4px;
  --radius-cards: 16px;
  --radius-buttons: 99px;
  --radius-default: 8px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.25) 0px 1px 2px 0px;
  --shadow-md: rgba(0, 0, 0, 0.15) 0px 4px 12px 0px;
  --shadow-subtle-2: rgba(0, 0, 0, 0.05) 0px 1px 3px 0px, rgba(0, 0, 0, 0.05) 0px 1px 2px -1px;

  /* Surfaces */
  --surface-canvas: #ffffff;
  --surface-parchment: #fafaf9;
  --surface-whisper-gray: #efeeed;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas: #ffffff;
  --color-ink: #1c1917;
  --color-ash: #57534d;
  --color-stone: #79716b;
  --color-parchment: #fafaf9;
  --color-whisper-gray: #efeeed;
  --color-outline-gray: #e5e5e5;
  --color-obsidian: #000000;
  --color-sunset-orange: #fe551b;

  /* Typography */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-general-sans-variable: 'General Sans Variable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-general-sans: 'General Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geist-mono: 'Geist Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-general-sans-variable-variable-bold: 'General Sans Variable Variable Bold', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-space-mono: 'Space Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.18;
  --tracking-caption: -0.1px;
  --text-body: 16px;
  --leading-body: 1.4;
  --tracking-body: -0.16px;
  --text-subheading: 18px;
  --leading-subheading: 1.6;
  --tracking-subheading: -0.18px;
  --text-heading: 32px;
  --leading-heading: 1.3;
  --tracking-heading: -0.64px;
  --text-heading-lg: 45px;
  --leading-heading-lg: 1.4;
  --tracking-heading-lg: -1.35px;
  --text-display: 55px;
  --leading-display: 1;
  --tracking-display: -2.2px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-14: 14px;
  --spacing-15: 15px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-3xl-2: 28px;
  --radius-full: 88px;
  --radius-full-2: 99px;
  --radius-full-3: 1000px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.25) 0px 1px 2px 0px;
  --shadow-md: rgba(0, 0, 0, 0.15) 0px 4px 12px 0px;
  --shadow-subtle-2: rgba(0, 0, 0, 0.05) 0px 1px 3px 0px, rgba(0, 0, 0, 0.05) 0px 1px 2px -1px;
}
```

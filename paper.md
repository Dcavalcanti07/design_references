# Paper — Style Reference
> Architectural blueprint on white marble.  Light, precise, and structural.

**Theme:** light

Paper presents a 'connected canvas' aesthetic, balancing a spacious, off-white background with direct, functional UI elements. Typography is precise and utilitarian, giving the interface a high-density, tool-like feel. Subtle blues and crisp black text provide clear interaction points against a largely monochrome palette, evoking a focused, productive environment. Components favor sharp edges and minimal elevation, reinforcing a lightweight and responsive experience.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas Parchment | `#efefe4` | `--color-canvas-parchment` | Page backgrounds, large inactive card surfaces — provides a warm, slightly aged base layer for content |
| Surface Frost | `#fcfcf9` | `--color-surface-frost` | Secondary surface background, prominent cards, dialogue boxes — a slightly brighter neutral that lifts elements from the Canvas |
| Paper White | `#ffffff` | `--color-paper-white` | Elevated cards, active surfaces, clear visual separation for foreground elements — crispest background for crucial UI |
| Cloud Grey | `#f3f3f4` | `--color-cloud-grey` | Subtle background for UI details or hover states; acts as a close neighbor to Surface Frost |
| Outline Slate | `#d7d7d6` | `--color-outline-slate` | Hairline borders, subtle dividers, inactive UI elements — provides soft structure without harsh lines |
| Charcoal Black | `#181818` | `--color-charcoal-black` | Primary text, headings, strong interactive elements; deep contrast for readability and emphasis |
| Ink Grey | `#222222` | `--color-ink-grey` | Slightly softer text for certain headings or navigation items, less stark than Charcoal Black |
| Mid Grey | `#909090` | `--color-mid-grey` | Subheadings, descriptive text, placeholder text — provides a secondary level of text hierarchy |
| Stone Grey | `#a8a8a8` | `--color-stone-grey` | Muted text, helper text, icons — for lowest-priority information that still needs to be legible |
| Icon Blue | `#5d8cd7` | `--color-icon-blue` | Blue outline accent for tags, dividers, and focused UI edges. Do not promote it to the primary CTA color |
| Halo Blue | `#81adec` | `--color-halo-blue` | Blue outline accent for tags, dividers, and focused UI edges. Do not promote it to the primary CTA color |

## Tokens — Typography

### Matter — Primary display font for headings and calls to action. The range of weights, particularly the lighter 360 and 400, creates a sense of authoritative precision for large text, while 'ss01' provides distinct character shapes. · `--font-matter`
- **Weights:** 360, 400, 480, 500, 550
- **Sizes:** 14px, 18px, 48px, 64px
- **Line height:** 1.00, 1.56, 2.00
- **Letter spacing:** -0.96px at 48px, -1.28px at 64px, normal at 14px, 0.7px at 14px
- **OpenType features:** `"calt", "ss01"`
- **Role:** Primary display font for headings and calls to action. The range of weights, particularly the lighter 360 and 400, creates a sense of authoritative precision for large text, while 'ss01' provides distinct character shapes.

### Inter — Workhorse text font used for body copy, navigation, and most UI elements. Its broad weight and size range ensures readability across functional contexts. · `--font-inter`
- **Weights:** 400, 500, 600
- **Sizes:** 12px, 14px, 16px, 18px, 24px, 36px
- **Line height:** 1.00, 1.14, 1.17, 1.20, 1.29, 1.30, 1.33, 1.40, 1.56, 1.75, 2.00, 2.33
- **Letter spacing:** -0.0250em to 0.0150em, specific to size
- **OpenType features:** `"calt"`
- **Role:** Workhorse text font used for body copy, navigation, and most UI elements. Its broad weight and size range ensures readability across functional contexts.

### Paper Mono — Monospaced font for code snippets, data displays, and specific technical labels. Its tight tracking and fixed width provide clarity for structured information. · `--font-paper-mono`
- **Weights:** 400
- **Sizes:** 11px, 12px
- **Line height:** 1.33, 2.55
- **Letter spacing:** 0.192px at 12px, 0.176px at 11px
- **OpenType features:** `"calt"`
- **Role:** Monospaced font for code snippets, data displays, and specific technical labels. Its tight tracking and fixed width provide clarity for structured information.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.33 | — | `--text-caption` |
| body-sm | 14px | 1.33 | — | `--text-body-sm` |
| body | 16px | 1.33 | — | `--text-body` |
| body-lg | 18px | 1.33 | — | `--text-body-lg` |
| heading-sm | 24px | 1.3 | — | `--text-heading-sm` |
| heading | 36px | 1.3 | — | `--text-heading` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 8 | 8px | `--spacing-8` |
| 12 | 12px | `--spacing-12` |
| 16 | 16px | `--spacing-16` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 36 | 36px | `--spacing-36` |
| 40 | 40px | `--spacing-40` |
| 44 | 44px | `--spacing-44` |
| 60 | 60px | `--spacing-60` |
| 64 | 64px | `--spacing-64` |
| 120 | 120px | `--spacing-120` |
| 172 | 172px | `--spacing-172` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 20px |
| cards | 12px |
| buttons | 4px |
| inputElements | 4px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| md | `rgba(0, 0, 0, 0.12) 0px 4px 10px 0px, rgba(0, 0, 0, 0.12)...` | `--shadow-md` |
| sm | `rgba(0, 0, 0, 0.08) 0px 8px 8px -4px, rgba(0, 0, 0, 0.08)...` | `--shadow-sm` |

### Layout

- **Section gap:** 40px
- **Card padding:** 40px
- **Element gap:** 8px

## Components

### Primary Filled Button
**Role:** Action button with solid background

Background: Charcoal Black (#181818), Text: Paper White (#ffffff), Padding: 6px vertical, 14px horizontal, Border Radius: 4px. Used for main calls to action like 'download Paper'.

### Ghost Button
**Role:** Secondary action button with transparent background

Background: rgba(0, 0, 0, 0), Text: Charcoal Black (#181818), Padding: 0px, Border Radius: 0px. Used for less prominent actions, often appearing as a text link with button functionality.

### Elevated Content Card
**Role:** Informational card with shadow

Background: Paper White (#ffffff), Border Radius: 6px, Padding: 0px. Shadow: rgba(0, 0, 0, 0.12) 0px 4px 10px 0px, rgba(0, 0, 0, 0.12) 0px 2px 4px -1px, rgba(0, 0, 0, 0.12) 0px 0px 4px -1px. Used for featured content or panels requiring visual hierarchy through elevation.

### Section Card
**Role:** Content card as a section container

Background: Canvas Parchment (#efefe4), Border Radius: 0px, Padding: 40px. Used for full-width content sections on the page.

### Tool Panel Card
**Role:** UI panel with internal padding

Background: Paper White (#ffffff), Border Radius: 12px, Padding: 0px. Used for tool palettes or complex interface sections.

### Muted Content Card
**Role:** Subtle content card without shadow

Background: Outline Slate (#d7d7d6), Border Radius: 0px, Padding: 40px. Used for sections that need slight differentiation without full elevation.

## Do's and Don'ts

### Do
- Prioritize Charcoal Black (#181818) for primary text and headings against lighter backgrounds for maximum contrast and readability.
- Use a 4px border-radius for interactive elements like buttons and input fields to maintain a consistent pragmatic feel.
- Employ Canvas Parchment (#efefe4) as the primary page background to establish a warm, subtle base for the UI.
- Apply Element Gap (8px) for horizontal and vertical spacing between small interactive elements and inline content.
- Use Matter font with lighter weights (360, 400) for large headlines to project authority through understatement.
- Introduce Icon Blue (#5d8cd7) only as a functional accent for interactive elements, links, and specific icons.
- Utilize the full box-shadow stack `rgba(0, 0, 0, 0.12) 0px 4px 10px 0px, rgba(0, 0, 0, 0.12) 0px 2px 4px -1px, rgba(0, 0, 0, 0.12) 0px 0px 4px -1px` for elevated cards to create clear visual separation.

### Don't
- Avoid using highly saturated colors for large surface areas; maintain the largely monochrome aesthetic with subtle neutrals.
- Do not deviate from the 4px base unit for grid and component spacing; consistency is key to the dense feel.
- Do not use generic system fonts; always specify Inter, Matter, or Paper Mono as appropriate for their respective roles.
- Do not apply large, decorative border-radii randomly; adhere to the specified radii for cards and interactive elements.
- Do not introduce heavy gradients or complex background patterns; keep backgrounds clean and flat with subtle color variations.
- Avoid excessive use of elevation; reserve shadows for distinct, interactive components or panels that need to stand out.
- Do not introduce new border styles beyond `1px solid` with Outline Slate (#d7d7d6) for structural elements.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Canvas Parchment | `#efefe4` | Primary page background, foundation of the entire interface. |
| 2 | Surface Frost | `#fcfcf9` | Slightly elevated general interface elements like headers or prominent background sections. |
| 3 | Paper White | `#ffffff` | Foreground elements like cards, tool panels, or specific UI components requiring crisp visual separation. |

## Elevation

- **Elevated Content Card:** `rgba(0, 0, 0, 0.12) 0px 4px 10px 0px, rgba(0, 0, 0, 0.12) 0px 2px 4px -1px, rgba(0, 0, 0, 0.12) 0px 0px 4px -1px`
- **Floating Menu/Tooltip:** `rgba(0, 0, 0, 0.08) 0px 8px 8px -4px, rgba(0, 0, 0, 0.08) 0px 2px 4px -2px, rgba(0, 0, 0, 0.08) 0px 1px 1px -1px, rgba(0, 0, 0, 0.08) 0px 0px 0px 1px`

## Imagery

Imagery primarily consists of application product screenshots, tightly cropped and often overlapping to demonstrate multi-window interface elements. These are supplemented by small, functional grey or brand-blue icons (outlined or filled, with varied stroke weights to denote hierarchy). Abstract, textured background graphics, resembling aged paper or faint grids, provide atmospheric context rather than content. The visual density is high, with imagery often serving as direct demonstration rather than decorative flourish.

## Layout

The page maintains a centered fixed-width content body on a full-bleed Canvas Parchment background. The hero section features a left-aligned, multi-line headline and call to action against an abstract background pattern, followed by overlapping product screenshots that visually break out of the content area. Section rhythm is primarily consistent vertical spacing, often with subtle background shifts (`Canvas Parchment` to `Outline Slate`). Content is arranged with stacked blocks of text and occasional two-column layouts, often with product visuals serving as the right-hand element. Navigation is a persistent top bar (61px height) with left-aligned brand logo and right-aligned links/buttons.

## Agent Prompt Guide

### Quick Color Reference
- text: #181818
- background: #efefe4
- border: #d7d7d6
- accent: #5d8cd7
- primary action: #181818 (filled action)

### 3-5 Example Component Prompts
- Create a Primary Action Button: #181818 background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
- Generate a Navigation Bar: Background Surface Frost (#fcfcf9), height 61px. Brand logo (SVG with Icon Blue accent) on left. Right-aligned navigation links 'pricing', 'roadmap' using Inter font, weight 400, size 16px, Charcoal Black text. Include a Ghost Button 'sign up' in Charcoal Black text.
- Design an Elevated Content Card: Background Paper White (#ffffff), Border Radius 6px and the full elevation shadow stack. Inside, a heading 'Introducing Paper Desktop' using Matter font, weight 500, size 36px, Charcoal Black text. Text content using Inter font, weight 400, size 16px, Mid Grey text.
- Create a Code Block: Background Cloud Grey (#f3f3f4). Text for the code using Paper Mono font, weight 400, size 12px, Charcoal Black text. Text should be pre-formatted with specific syntax highlighting colors where appropriate (e.g. green for code comments, not in palette).

## Similar Brands

- **Linear** — Similar focus on precise, utilitarian UI with compact typography and a subtle, functional accent color against a light background.
- **GitHub** — Shares the use of a monospaced font for code, clean structural lines, and a professional, dense information display.
- **Figma** — Has a comparable tool-like interface with extensive use of structured gray scales and distinct, functional button styles.
- **Notion** — Utilizes a clean, white-space heavy layout with a strong emphasis on text hierarchy and subtle component differentiation, maintaining a focused productivity aesthetic.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-parchment: #efefe4;
  --color-surface-frost: #fcfcf9;
  --color-paper-white: #ffffff;
  --color-cloud-grey: #f3f3f4;
  --color-outline-slate: #d7d7d6;
  --color-charcoal-black: #181818;
  --color-ink-grey: #222222;
  --color-mid-grey: #909090;
  --color-stone-grey: #a8a8a8;
  --color-icon-blue: #5d8cd7;
  --color-halo-blue: #81adec;

  /* Typography — Font Families */
  --font-matter: 'Matter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-paper-mono: 'Paper Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.33;
  --text-body-sm: 14px;
  --leading-body-sm: 1.33;
  --text-body: 16px;
  --leading-body: 1.33;
  --text-body-lg: 18px;
  --leading-body-lg: 1.33;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.3;
  --text-heading: 36px;
  --leading-heading: 1.3;

  /* Typography — Weights */
  --font-weight-w360: 360;
  --font-weight-regular: 400;
  --font-weight-w480: 480;
  --font-weight-medium: 500;
  --font-weight-w550: 550;
  --font-weight-semibold: 600;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-44: 44px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-120: 120px;
  --spacing-172: 172px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 40px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-sm: 1px;
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 20px;
  --radius-3xl: 24px;

  /* Named Radii */
  --radius-tags: 20px;
  --radius-cards: 12px;
  --radius-buttons: 4px;
  --radius-inputelements: 4px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.12) 0px 4px 10px 0px, rgba(0, 0, 0, 0.12) 0px 2px 4px -1px, rgba(0, 0, 0, 0.12) 0px 0px 4px -1px;
  --shadow-sm: rgba(0, 0, 0, 0.08) 0px 8px 8px -4px, rgba(0, 0, 0, 0.08) 0px 2px 4px -2px, rgba(0, 0, 0, 0.08) 0px 1px 1px -1px, rgba(0, 0, 0, 0.08) 0px 0px 0px 1px;

  /* Surfaces */
  --surface-canvas-parchment: #efefe4;
  --surface-surface-frost: #fcfcf9;
  --surface-paper-white: #ffffff;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-parchment: #efefe4;
  --color-surface-frost: #fcfcf9;
  --color-paper-white: #ffffff;
  --color-cloud-grey: #f3f3f4;
  --color-outline-slate: #d7d7d6;
  --color-charcoal-black: #181818;
  --color-ink-grey: #222222;
  --color-mid-grey: #909090;
  --color-stone-grey: #a8a8a8;
  --color-icon-blue: #5d8cd7;
  --color-halo-blue: #81adec;

  /* Typography */
  --font-matter: 'Matter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-paper-mono: 'Paper Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.33;
  --text-body-sm: 14px;
  --leading-body-sm: 1.33;
  --text-body: 16px;
  --leading-body: 1.33;
  --text-body-lg: 18px;
  --leading-body-lg: 1.33;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.3;
  --text-heading: 36px;
  --leading-heading: 1.3;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-44: 44px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-120: 120px;
  --spacing-172: 172px;

  /* Border Radius */
  --radius-sm: 1px;
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 20px;
  --radius-3xl: 24px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.12) 0px 4px 10px 0px, rgba(0, 0, 0, 0.12) 0px 2px 4px -1px, rgba(0, 0, 0, 0.12) 0px 0px 4px -1px;
  --shadow-sm: rgba(0, 0, 0, 0.08) 0px 8px 8px -4px, rgba(0, 0, 0, 0.08) 0px 2px 4px -2px, rgba(0, 0, 0, 0.08) 0px 1px 1px -1px, rgba(0, 0, 0, 0.08) 0px 0px 0px 1px;
}
```

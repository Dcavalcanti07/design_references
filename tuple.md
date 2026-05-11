# Tuple — Style Reference
> Crisp developer canvas.

**Theme:** light

Tuple uses a clean, developer-focused aesthetic with a predominantly achromatic palette, punctuated by functional, vivid violet for primary actions. The interface features crisp typography, deliberate use of rounded corners, and a comfortable density. Subtle shadows and borders define element relationships, while contrasting dark sections provide visual breaks. Color is used sparingly, primarily to highlight interactive elements and convey status.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, surface elements, text on dark backgrounds |
| Canvas Fog | `#f4f4f5` | `--color-canvas-fog` | Secondary section backgrounds, subtle surface distinction |
| Border Ash | `#e4e4e7` | `--color-border-ash` | Soft icon strokes, subtle dividers, and low-emphasis decorative details. Do not promote it to the primary CTA color |
| Content Graphite | `#71717a` | `--color-content-graphite` | Secondary text, muted descriptions, inactive states |
| Text Slate | `#27272a` | `--color-text-slate` | Primary text for headings and body, strong contrast against light backgrounds; Dark mode sections, code block backgrounds, elevated card backgrounds in dark contexts |
| Dark Border Zinc | `#52525b` | `--color-dark-border-zinc` | Borders within dark mode surfaces |
| Dark Accent Charcoal | `#3f3f46` | `--color-dark-accent-charcoal` | Subtle background for elements within dark mode, code elements |
| Grape Action | `#6a5ed9` | `--color-grape-action` | Primary call-to-action buttons, active navigation indicators — a vibrant accent against neutral tones |
| Sky Brand | `#3f71d4` | `--color-sky-brand` | Brand illustrations, icon accents, specific headings |
| Sunset Orange | `#db5434` | `--color-sunset-orange` | Decorative strokes, some highlight text, illustration elements |
| Success Green | `#1bb152` | `--color-success-green` | Green text accent for links, tags, and emphasized short phrases. Use as a supporting accent, not as a status color |
| Soft Success | `#4ade80` | `--color-soft-success` | Green text accent for links, tags, and emphasized short phrases. Use as a supporting accent, not as a status color |
| Strong Success | `#22863a` | `--color-strong-success` | Green text accent for links, tags, and emphasized short phrases. Use as a supporting accent, not as a status color |
| Warning Yellow | `#ffb929` | `--color-warning-yellow` | Yellow wash for highlight backgrounds, decorative bands, and soft emphasis behind content. Use as a supporting accent, not as a status color |
| Error Red | `#ef4444` | `--color-error-red` | Red wash for highlight backgrounds, decorative bands, and soft emphasis behind content. Use as a supporting accent, not as a status color |
| Gradient Sunset | `linear-gradient(rgb(224, 108, 72), rgb(205, 62, 41))` | `--color-gradient-sunset` | Decorative gradient for product showcases or special sections |
| Gradient Sky | `linear-gradient(rgb(56, 189, 248), rgb(2, 132, 199))` | `--color-gradient-sky` | Decorative gradient for product showcases or special sections |

## Tokens — Typography

### Inter Variable — Primary UI text, headings, body copy, navigation. Features 'cv05', 'cv06', 'ss01' for nuanced typographic control. · `--font-inter-variable`
- **Substitute:** Inter
- **Weights:** 400, 500, 600, 700
- **Sizes:** 12px, 13px, 14px, 16px, 18px, 20px, 24px, 36px, 48px, 60px
- **Line height:** 1.00, 1.11, 1.14, 1.20, 1.33, 1.40, 1.43, 1.50, 1.56, 1.63
- **Letter spacing:** normal
- **OpenType features:** `'cv05' on, 'cv06' on, 'ss01' on`
- **Role:** Primary UI text, headings, body copy, navigation. Features 'cv05', 'cv06', 'ss01' for nuanced typographic control.

### DM Mono — Monospaced text for code snippets, technical details, and certain navigation elements. Features stylistic sets 'ss03', 'ss04', 'ss05' for code legibility. · `--font-dm-mono`
- **Substitute:** Space Mono
- **Weights:** 400, 500
- **Sizes:** 11px, 12px, 13px, 14px, 16px
- **Line height:** 1.33, 1.43, 1.50, 1.63
- **Letter spacing:** 0.05em to 0.1em
- **OpenType features:** `'ss03' on, 'ss04' on, 'ss05' on`
- **Role:** Monospaced text for code snippets, technical details, and certain navigation elements. Features stylistic sets 'ss03', 'ss04', 'ss05' for code legibility.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.43 | — | `--text-caption` |
| body | 16px | 1.5 | — | `--text-body` |
| subheading | 20px | 1.4 | — | `--text-subheading` |
| heading | 36px | 1.11 | — | `--text-heading` |
| heading-lg | 48px | 1.14 | — | `--text-heading-lg` |
| display | 60px | 1 | — | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 8px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 8 | 8px | `--spacing-8` |
| 16 | 16px | `--spacing-16` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 96 | 96px | `--spacing-96` |
| 128 | 128px | `--spacing-128` |
| 192 | 192px | `--spacing-192` |
| 240 | 240px | `--spacing-240` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 9999px |
| cards | 12px |
| input | 8px |
| large | 24px |
| small | 8px |
| buttons | 12px |
| default | 12px |
| navItem | 4px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(0, 0, 0, 0.1) 0px 1px 3px 0px, rgba(0, 0, 0, 0.1) 0p...` | `--shadow-subtle` |
| subtle-2 | `rgba(0, 0, 0, 0.05) 0px 0px 0px 1px, rgba(0, 0, 0, 0.05) ...` | `--shadow-subtle-2` |
| xl | `rgba(0, 0, 0, 0.25) 0px 25px 50px -12px` | `--shadow-xl` |
| subtle-3 | `rgba(0, 0, 0, 0.75) 0px 0px 0px 1px` | `--shadow-subtle-3` |
| subtle-4 | `rgba(255, 255, 255, 0.15) 0px 0px 0px 1px inset` | `--shadow-subtle-4` |
| subtle-5 | `rgba(0, 0, 0, 0.05) 0px 0px 0px 1px, rgba(0, 0, 0, 0.1) 0...` | `--shadow-subtle-5` |
| subtle-6 | `rgba(0, 0, 0, 0.05) 0px 1px 2px 0px` | `--shadow-subtle-6` |
| xl-2 | `rgba(0, 0, 0, 0.1) 0px 20px 25px -5px, rgba(0, 0, 0, 0.1)...` | `--shadow-xl-2` |
| xl-3 | `rgba(0, 0, 0, 0.05) 0px 0px 80px 0px, rgba(0, 0, 0, 0.02)...` | `--shadow-xl-3` |

### Layout

- **Page max-width:** 1200px
- **Section gap:** 32px
- **Card padding:** 32px
- **Element gap:** 8px

## Components

### Primary Action Button
**Role:** Main call-to-action

Filled button with 'Grape Action' (#6a5ed9) background and 'Canvas White' (#ffffff) text. Features 12px border-radius and generous 16px vertical, 32px horizontal padding. Font is Inter Variable, weight 700.

### Default Card
**Role:** Content container

White (#ffffff) background with 12px border-radius. Shadow: rgba(0, 0, 0, 0.05) 0px 0px 0px 1px, rgba(0, 0, 0, 0.05) 0px 1px 2px 0px. Internal padding of 48px on all sides.

### Subtle Card
**Role:** Secondary content container

Subtle 'Canvas Fog' (#fafafa ~ #f4f4f5) background with 12px border-radius and no shadow. Internal padding of 32px on all sides.

### Dark Elevated Card
**Role:** Content container in dark sections

Dark Surface (#27272a) background with 12px border-radius. Features a subtle 1px border shadow: rgba(0, 0, 0, 0.75) 0px 0px 0px 1px. No explicit padding mentioned directly, implying content controls it. Text typically 'Canvas White'.

### Alert Banner
**Role:** Prominent announcements

Notification banner with light background (e.g., #dcfce7, a very light green hue not explicitly a token) and contrasting color text/icons. Example usage shows Green Accents for success-like notices.

### Floating Card
**Role:** Ephemeral or interactive card with strong elevation

Appears on light background (#ffffff) with 8px border-radius and a prominent shadow: rgba(0, 0, 0, 0.25) 0px 25px 50px -12px. No explicit padding detected, suggesting content may fill it.

## Do's and Don'ts

### Do
- Prioritize 'Text Slate' (#27272a) for body and heading text on light backgrounds and 'Canvas White' (#ffffff) on dark backgrounds.
- Use 'Grape Action' (#6a5ed9) exclusively for primary interactive elements, reserving it for clear calls-to-action.
- Apply 12px border-radius for all main buttons and cards to maintain a consistent rounded aesthetic.
- Utilize 'Border Ash' (#e4e4e7) for all hairline borders, dividers, and subtle outlines on light surfaces.
- Maintain a clear hierarchy using Inter Variable for all primary UI text and DM Mono for code or technical content.
- Employ 32px for section vertical spacing and 8px for internal element gaps to ensure comfortable density.
- Use rgba(0, 0, 0, 0.05) 0px 0px 0px 1px, rgba(0, 0, 0, 0.05) 0px 1px 2px 0px for subtle elevation, primarily on cards and navigation.

### Don't
- Avoid using multiple chromatic colors for primary calls-to-action; reserve 'Grape Action' (#6a5ed9) for this role.
- Do not deviate from the established 12px border-radius for buttons and cards without clear intent, as this is a core visual identifier.
- Do not use generic system fonts; always utilize Inter Variable and DM Mono with their specified `fontFeatureSettings`.
- Avoid excessive use of shadows; stick to the defined shadow tokens for light elevation and more pronounced shadows for overlays.
- Do not create arbitrary color accents; refer to 'Sky Brand', 'Sunset Orange', 'Success Green', and 'Error Red' for their specific decorative or semantic purposes.
- Do not overcrowd sections; ensure comfortable vertical spacing of 32px between major content blocks.
- Avoid text weights below 400 for body copy on any background, as legibility is paramount.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas White | `#ffffff` | Base page background and default layer for most content and components. |
| 1 | Canvas Fog | `#f4f4f5` | Secondary background for distinct sections or subtle card surfaces, differentiating from the base canvas. |
| 2 | Dark Surface | `#27272a` | Background for dedicated dark mode sections or elevated components within a dark context, creating strong contrast. |

## Elevation

- **Default Card:** `rgba(0, 0, 0, 0.05) 0px 0px 0px 1px, rgba(0, 0, 0, 0.05) 0px 1px 2px 0px`
- **Navigation Bar:** `rgba(0, 0, 0, 0.05) 0px 0px 0px 1px, rgba(0, 0, 0, 0.05) 0px 1px 2px 0px`
- **Dropdown/Popover:** `rgba(0, 0, 0, 0.1) 0px 1px 3px 0px, rgba(0, 0, 0, 0.1) 0px 1px 2px -1px`
- **Floating Card/Modal:** `rgba(0, 0, 0, 0.25) 0px 25px 50px -12px`
- **Dark Elevated Card Border:** `rgba(0, 0, 0, 0.75) 0px 0px 0px 1px`

## Imagery

The site uses a mix of tightly cropped, realistic product screenshots (showing Mac and Windows UI elements) and stylized, conceptual vector illustrations. Product screenshots are often contained within rounded, elevated frames, highlighting the software's interface. Illustrations are flat, organic, and utilize the brand's chromatic colors like 'Sky Brand' and 'Sunset Orange', serving both decorative and explanatory roles. Icons are filled, with a medium stroke weight where outlines appear. Imagery density is moderate, providing visual breaks but not dominating the page, allowing text and UI elements to remain primary.

## Layout

The page primarily uses a contained layout with a `pageMaxWidth` of approximately 1200px, centered horizontally. The hero section is full-bleed with a prominent, centered headline and a call-to-action. Content sections alternate between these full-width dark blocks and light, contained sections. Many content blocks feature a two-column layout, often with text on one side and a product visual on the other, or a three-column grid for features/logos. Vertical spacing is comfortable and consistent, using 32px section gaps to create a balanced rhythm between content blocks. A sticky top navigation bar provides consistent access to primary links and actions.

## Agent Prompt Guide

Quick Color Reference:
- text: #27272a
- background: #ffffff
- border: #e4e4e7
- accent: #3f71d4
- primary action: #6a5ed9 (filled action)

Example Component Prompts:
- Create a testimonial card: 'Canvas White' (#ffffff) background, 12px border-radius, shadow rgba(0, 0, 0, 0.05) 0px 0px 0px 1px, rgba(0, 0, 0, 0.05) 0px 1px 2px 0px. Inner padding 48px, text 'Text Slate' (#27272a) Inter Variable weight 400. Quote source 'Content Graphite' (#71717a) Inter Variable weight 500.
- Design a call-to-action button: 'Grape Action' (#6a5ed9) background, text 'Canvas White' (#ffffff) Inter Variable weight 700, 12px border-radius, 16px vertical padding, 32px horizontal padding.
- Build a feature section header: Headline 'Text Slate' (#27272a) at 48px Inter Variable weight 700, followed by a subheading 'Content Graphite' (#71717a) at 20px Inter Variable weight 400. Use 32px vertical spacing between sections.
- Create a code snippet block: 'Dark Surface' (#27272a) background with a 'Dark Elevated Card Border' (rgba(0, 0, 0, 0.75) 0px 0px 0px 1px) with 12px border-radius. Code text in DM Mono weight 400 with syntax highlighting using 'Strong Success' (#22863a), 'Sky Brand' (#3f71d4), and 'Sunset Orange' (#db5434).

## Similar Brands

- **Linear** — Shares a clean, high-contrast UI with a single vivid accent color for interactive elements against a largely achromatic background.
- **Stripe** — Employs an emphasis on crisp typography, generous spacing, and subtle use of shadows to define hierarchy on white canvases.
- **Figma** — Similar approach to card-based layouts, rounded corners, and functional color accents in a professional design tool context.
- **Supabase** — Utilizes a balanced mix of light and dark sections, with clear product imagery and code examples integrated into the design.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-canvas-fog: #f4f4f5;
  --color-border-ash: #e4e4e7;
  --color-content-graphite: #71717a;
  --color-text-slate: #27272a;
  --color-dark-border-zinc: #52525b;
  --color-dark-accent-charcoal: #3f3f46;
  --color-grape-action: #6a5ed9;
  --color-sky-brand: #3f71d4;
  --color-sunset-orange: #db5434;
  --color-success-green: #1bb152;
  --color-soft-success: #4ade80;
  --color-strong-success: #22863a;
  --color-warning-yellow: #ffb929;
  --color-error-red: #ef4444;
  --color-gradient-sunset: #e06c48;
  --gradient-gradient-sunset: linear-gradient(rgb(224, 108, 72), rgb(205, 62, 41));
  --color-gradient-sky: #38bdf8;
  --gradient-gradient-sky: linear-gradient(rgb(56, 189, 248), rgb(2, 132, 199));

  /* Typography — Font Families */
  --font-inter-variable: 'Inter Variable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-dm-mono: 'DM Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.43;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 20px;
  --leading-subheading: 1.4;
  --text-heading: 36px;
  --leading-heading: 1.11;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.14;
  --text-display: 60px;
  --leading-display: 1;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-96: 96px;
  --spacing-128: 128px;
  --spacing-192: 192px;
  --spacing-240: 240px;

  /* Layout */
  --page-max-width: 1200px;
  --section-gap: 32px;
  --card-padding: 32px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-tags: 9999px;
  --radius-cards: 12px;
  --radius-input: 8px;
  --radius-large: 24px;
  --radius-small: 8px;
  --radius-buttons: 12px;
  --radius-default: 12px;
  --radius-navitem: 4px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.1) 0px 1px 3px 0px, rgba(0, 0, 0, 0.1) 0px 1px 2px -1px;
  --shadow-subtle-2: rgba(0, 0, 0, 0.05) 0px 0px 0px 1px, rgba(0, 0, 0, 0.05) 0px 1px 2px 0px;
  --shadow-xl: rgba(0, 0, 0, 0.25) 0px 25px 50px -12px;
  --shadow-subtle-3: rgba(0, 0, 0, 0.75) 0px 0px 0px 1px;
  --shadow-subtle-4: rgba(255, 255, 255, 0.15) 0px 0px 0px 1px inset;
  --shadow-subtle-5: rgba(0, 0, 0, 0.05) 0px 0px 0px 1px, rgba(0, 0, 0, 0.1) 0px 20px 25px -5px, rgba(0, 0, 0, 0.1) 0px 8px 10px -6px;
  --shadow-subtle-6: rgba(0, 0, 0, 0.05) 0px 1px 2px 0px;
  --shadow-xl-2: rgba(0, 0, 0, 0.1) 0px 20px 25px -5px, rgba(0, 0, 0, 0.1) 0px 8px 10px -6px;
  --shadow-xl-3: rgba(0, 0, 0, 0.05) 0px 0px 80px 0px, rgba(0, 0, 0, 0.02) 0px 8px 8px 0px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-canvas-fog: #f4f4f5;
  --surface-dark-surface: #27272a;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-canvas-fog: #f4f4f5;
  --color-border-ash: #e4e4e7;
  --color-content-graphite: #71717a;
  --color-text-slate: #27272a;
  --color-dark-border-zinc: #52525b;
  --color-dark-accent-charcoal: #3f3f46;
  --color-grape-action: #6a5ed9;
  --color-sky-brand: #3f71d4;
  --color-sunset-orange: #db5434;
  --color-success-green: #1bb152;
  --color-soft-success: #4ade80;
  --color-strong-success: #22863a;
  --color-warning-yellow: #ffb929;
  --color-error-red: #ef4444;
  --color-gradient-sunset: #e06c48;
  --color-gradient-sky: #38bdf8;

  /* Typography */
  --font-inter-variable: 'Inter Variable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-dm-mono: 'DM Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.43;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 20px;
  --leading-subheading: 1.4;
  --text-heading: 36px;
  --leading-heading: 1.11;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.14;
  --text-display: 60px;
  --leading-display: 1;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-96: 96px;
  --spacing-128: 128px;
  --spacing-192: 192px;
  --spacing-240: 240px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-full: 9999px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.1) 0px 1px 3px 0px, rgba(0, 0, 0, 0.1) 0px 1px 2px -1px;
  --shadow-subtle-2: rgba(0, 0, 0, 0.05) 0px 0px 0px 1px, rgba(0, 0, 0, 0.05) 0px 1px 2px 0px;
  --shadow-xl: rgba(0, 0, 0, 0.25) 0px 25px 50px -12px;
  --shadow-subtle-3: rgba(0, 0, 0, 0.75) 0px 0px 0px 1px;
  --shadow-subtle-4: rgba(255, 255, 255, 0.15) 0px 0px 0px 1px inset;
  --shadow-subtle-5: rgba(0, 0, 0, 0.05) 0px 0px 0px 1px, rgba(0, 0, 0, 0.1) 0px 20px 25px -5px, rgba(0, 0, 0, 0.1) 0px 8px 10px -6px;
  --shadow-subtle-6: rgba(0, 0, 0, 0.05) 0px 1px 2px 0px;
  --shadow-xl-2: rgba(0, 0, 0, 0.1) 0px 20px 25px -5px, rgba(0, 0, 0, 0.1) 0px 8px 10px -6px;
  --shadow-xl-3: rgba(0, 0, 0, 0.05) 0px 0px 80px 0px, rgba(0, 0, 0, 0.02) 0px 8px 8px 0px;
}
```

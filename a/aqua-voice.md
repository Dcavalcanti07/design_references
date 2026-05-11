# Aqua Voice — Style Reference
> Frosted Light Canvas

**Theme:** light

Aqua Voice presents a light, highly refined interface reminiscent of a clean workspace. Its visual language marries subtle background textures with focused, high-contrast typography. Surfaces are predominantly light and spacious, highlighted by soft, extensive drop shadows that give elements a lifted and layered feel rather than heavy depth. A singular vibrant blue serves as the primary accent, drawing immediate attention to key calls to action and active states, while maintaining an overall understated elegance.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#fafbfc` | `--color-canvas-white` | Primary page background, base surface for cards and elements |
| Cloud Gray | `#f3f7fa` | `--color-cloud-gray` | Secondary background color for subtle section breaks |
| Pale Ash | `#f2f6fa` | `--color-pale-ash` | Tertiary background color, slightly darker than Cloud Gray, for nested sections or background elements |
| Porcelain Whisper | `#efefef` | `--color-porcelain-whisper` | Subtle background for ghost buttons and very light interactive states |
| Dark Charcoal | `#292c3d` | `--color-dark-charcoal` | Primary headings and main body text color, providing strong contrast on light surfaces |
| Soft Lead | `#3e4150` | `--color-soft-lead` | Secondary text for paragraphs and descriptive content |
| Muted Stone | `#686a76` | `--color-muted-stone` | Tertiary text, less prominent helper text and subtle labels |
| Sky Action Blue | `#67beff` | `--color-sky-action-blue` | Primary accent color for filled buttons and active states — conveys action and interaction |
| Deep Link Blue | `#4288ff` | `--color-deep-link-blue` | Interactive link color and borders for ghost buttons, provides secondary interactive highlights |
| Near Black | `#000000` | `--color-near-black` | Fallback and very strong contrast text, borders, and UI elements. Used sparingly |
| Dark Card Surface | `#171719` | `--color-dark-card-surface` | Background for elevated dark cards, often paired with white text |
| Subtle Dark Card | `#1e1e20` | `--color-subtle-dark-card` | Background for minor elevated dark elements or secondary dark cards |

## Tokens — Typography

### sans-serif — sans-serif — detected in extracted data but not described by AI · `--font-sans-serif`
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.2
- **Role:** sans-serif — detected in extracted data but not described by AI

### PP Neue Montreal — Primary typeface for headings and larger body text. The use of lighter weights for strong statements creates an understated authority. · `--font-pp-neue-montreal`
- **Substitute:** Montserrat, sans-serif
- **Weights:** 200, 400, 500
- **Sizes:** 13px, 14px, 15px, 16px, 17px, 20px, 24px, 40px, 56px, 60px, 72px
- **Line height:** 1.00, 1.10, 1.20, 1.40, 1.50, 1.60
- **Letter spacing:** normal
- **OpenType features:** `"blwf", "cv03", "cv04", "cv09", "cv11"`
- **Role:** Primary typeface for headings and larger body text. The use of lighter weights for strong statements creates an understated authority.

### PP Neue Montreal — Used for emphasized body text, subheadings, and navigation elements. The medium weight provides clarity without being overly bold. · `--font-pp-neue-montreal`
- **Substitute:** Montserrat, sans-serif
- **Weights:** 
- **Sizes:** 13px, 14px, 15px, 16px, 17px, 20px
- **Line height:** 1.00, 1.10, 1.20, 1.40, 1.50, 1.60
- **Letter spacing:** normal
- **Role:** Used for emphasized body text, subheadings, and navigation elements. The medium weight provides clarity without being overly bold.

### Inter — Secondary typeface for smaller body copy, labels, and UI elements. Its legibility at small sizes complements the primary typeface. · `--font-inter`
- **Substitute:** Inter, sans-serif
- **Weights:** 400, 500, 600
- **Sizes:** 10px, 11px, 12px, 20px
- **Line height:** 1.00, 1.10, 1.20, 1.40, 1.50, 1.60
- **Letter spacing:** normal
- **Role:** Secondary typeface for smaller body copy, labels, and UI elements. Its legibility at small sizes complements the primary typeface.

### Geist Mono — Used for code snippets or specific data points that require a monospaced treatment, ensuring precise alignment. · `--font-geist-mono`
- **Substitute:** Dina, monospace
- **Weights:** 400, 500
- **Sizes:** 11px, 13px, 14px, 18px
- **Line height:** 1.00, 1.40, 1.60
- **Letter spacing:** normal
- **Role:** Used for code snippets or specific data points that require a monospaced treatment, ensuring precise alignment.

### IBM Plex Mono — IBM Plex Mono — detected in extracted data but not described by AI · `--font-ibm-plex-mono`
- **Weights:** 400
- **Sizes:** 10px, 13px
- **Line height:** 1.2
- **Role:** IBM Plex Mono — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.4 | — | `--text-caption` |
| body | 14px | 1.6 | — | `--text-body` |
| subheading | 20px | 1.2 | — | `--text-subheading` |
| heading | 40px | 1.1 | — | `--text-heading` |
| heading-lg | 56px | 1 | — | `--text-heading-lg` |
| display | 72px | 1 | — | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 6 | 6px | `--spacing-6` |
| 8 | 8px | `--spacing-8` |
| 10 | 10px | `--spacing-10` |
| 12 | 12px | `--spacing-12` |
| 15 | 15px | `--spacing-15` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 28 | 28px | `--spacing-28` |
| 30 | 30px | `--spacing-30` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 80 | 80px | `--spacing-80` |
| 124 | 124px | `--spacing-124` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 12px |
| forms | 8px |
| pills | 70px |
| buttons | 110px |
| inputElements | 4px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(0, 0, 0, 0.02) 0px 0px 0px 2px, rgba(0, 0, 0, 0.02) ...` | `--shadow-subtle` |
| subtle-2 | `rgba(0, 0, 0, 0.02) 0px 0px 0px 1px, rgba(0, 0, 0, 0.02) ...` | `--shadow-subtle-2` |
| subtle-3 | `rgb(255, 255, 255) 0px 1px 0px 0px inset, rgba(0, 0, 0, 0...` | `--shadow-subtle-3` |
| subtle-4 | `rgba(0, 0, 0, 0.1) 0px 0px 0px 1px, rgba(0, 0, 0, 0.1) 0p...` | `--shadow-subtle-4` |
| subtle-5 | `rgb(52, 52, 52) 0px 1px 0px 0px inset, rgba(0, 0, 0, 0.06...` | `--shadow-subtle-5` |

### Layout

- **Section gap:** 40px
- **Card padding:** 20px
- **Element gap:** 10px

## Components

### Primary Action Button
**Role:** Main call to action buttons.

Filled with Sky Action Blue (#67beff), with white text and 110px border-radius for a soft, pill-like appearance. Padding is 0px top/bottom and 24px left/right, text color is Near Black (#000000).

### Secondary Ghost Button
**Role:** Alternative actions or less prominent calls.

Background is Porcelain Whisper (#efefef), bordered by Deep Link Blue (#4288ff) with a 110px border-radius. Text color is Deep Link Blue (#4288ff). Padding is 0px top/bottom and 24px left/right.

### Form Field Button
**Role:** Actions within forms or specific interactive elements, distinct from primary CTAs.

Filled with Sky Action Blue (#67beff), white text, and an 8px border-radius. Padding is 0px top/bottom and 20px left/right. Text color is Near Black (#000000).

### Light Elevated Card
**Role:** Highlighting key information or features on light backgrounds.

Canvas White (#ffffff) background, 12px border-radius, with an extensive soft shadow: rgba(0, 0, 0, 0.02) 0px 0px 0px 1px, rgba(0, 0, 0, 0.02) 0px 1px 1px 0.5px, and progressively larger offsets up to 24px -12px. Inner padding determined by content.

### Dark Elevated Card
**Role:** Highlighting key information or features on dark backgrounds, providing content separation.

Dark Card Surface (#171719) background, 12px border-radius, with a distinct dark shadow: rgba(0, 0, 0, 0.1) 0px 0px 0px 1px, rgba(0, 0, 0, 0.1) 0px 1px 1px 0.5px, and progressively larger offsets up to 24px -12px. Inner padding is 20px on all sides.

### Clean Feature Card
**Role:** Compact informational cards without elevation for lighter sections.

Pale Ash (#f2f6fa) background with a 16px border-radius and no shadow. Internal padding is 12px on all sides.

## Do's and Don'ts

### Do
- Use PP Neue Montreal Book (weight 200/400) for all headings to establish a distinctive, light typographic voice.
- Prioritize Canvas White (#fafbfc) as the default background for content areas and cards, creating a bright, spacious feel.
- Apply Sky Action Blue (#67beff) strictly for primary interactive elements, ensuring it stands out as the main call to action.
- Utilize an extensive, soft shadow from the `elevation` tokens for cards and elevated components to create a layered, floating effect with subtle depth.
- Maintain high border-radii (110px) for all primary buttons, giving them a distinct pill shape.
- Employ consistent 10px element gaps between closely related UI elements for a compact yet readable density.
- Reserve the Deep Link Blue (#4288ff) for text links and borders of secondary interactive elements.

### Don't
- Avoid using bold or heavy weights for primary headings; the brand relies on a lighter, more refined headline style.
- Do not introduce additional vivid accent colors; the visual system is anchored around Sky Action Blue (#67beff) and Deep Link Blue (#4288ff).
- Refrain from using hard or sharp shadows; all elevation should appear soft and diffused.
- Do not deviate from the established border-radius values, especially the pill-shaped buttons and 12px card corners.
- Avoid tight spacing between major sections; ensure generous vertical separation to maintain an open layout.
- Do not use dark backgrounds for full sections that contain primary content; the primary theme is light with occasional dark cards for contrast.
- Do not use default browser blue for links; always use Deep Link Blue (#4288ff).

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas White | `#fafbfc` | Base page background |
| 1 | Cloud Gray | `#f3f7fa` | Secondary background for section breaks |
| 2 | Pale Ash | `#f2f6fa` | Tertiary background for nested elements or clean feature cards |
| 3 | Porcelain Whisper | `#efefef` | Background for ghost buttons and subtle interactives |

## Elevation

- **Light Elevated Card:** `rgba(0, 0, 0, 0.02) 0px 0px 0px 1px, rgba(0, 0, 0, 0.02) 0px 1px 1px 0.5px, rgba(0, 0, 0, 0.02) 0px 3px 3px 1.5px, rgba(0, 0, 0, 0.02) 0px 6px 6px -3px, rgba(0, 0, 0, 0.02) 0px 12px 12px -6px, rgba(0, 0, 0, 0.02) 0px 24px 24px -12px`
- **Dark Elevated Card:** `rgba(0, 0, 0, 0.1) 0px 0px 0px 1px, rgba(0, 0, 0, 0.1) 0px 1px 1px 0.5px, rgba(0, 0, 0, 0.1) 0px 3px 3px 1.5px, rgba(0, 0, 0, 0.1) 0px 6px 6px -3px, rgba(0, 0, 0, 0.1) 0px 12px 12px -6px, rgba(0, 0, 0, 0.1) 0px 24px 24px -12px`
- **Inset Elevated Element (Light):** `rgb(255, 255, 255) 0px 1px 0px 0px inset, rgba(0, 0, 0, 0.06) 0px 0px 0px 1px, rgba(0, 0, 0, 0.06) 0px 1px 1px 0.5px, rgba(0, 0, 0, 0.06) 0px 3px 3px 1.5px, rgba(0, 0, 0, 0.06) 0px 6px 6px -3px, rgba(0, 0, 0, 0.06) 0px 12px 12px -6px, rgba(0, 0, 0, 0.06) 0px 24px 24px -12px`
- **Inset Elevated Element (Dark):** `rgb(52, 52, 52) 0px 1px 0px 0px inset, rgba(0, 0, 0, 0.06) 0px 0px 0px 1px, rgba(0, 0, 0, 0.06) 0px 1px 1px 0.5px, rgba(0, 0, 0, 0.06) 0px 3px 3px 1.5px, rgba(0, 0, 0, 0.06) 0px 6px 6px -3px, rgba(0, 0, 0, 0.06) 0px 12px 12px -6px, rgba(0, 0, 0, 0.06) 0px 24px 24px -12px`

## Imagery

The imagery consists predominantly of abstract, atmospheric background graphics featuring subtle light-blue watery or gaseous textures, often with soft blur effects. Product screenshots are contained within light cards, showcasing the UI directly without heavy ornamentation. Icons are minimal, outlined, or filled, and primarily monochromatic using the brand's neutral color palette, occasionally highlighted with Sky Action Blue for interactive states. Photography appears to be absent, maintaining a focus on UI and abstract visual metaphor. Imagery serves a decorative and explanatory role, creating a calm and focused atmosphere.

## Layout

The page layout is primarily full-bleed with large sections, interrupted by a contained `pageMaxWidth` centered hero content block. The hero section features a large, centered headline and subtext, often with abstract background imagery. Section rhythm alternates between large, visually distinct blocks, typically with consistent vertical spacing. Content arrangement frequently uses centered stacks for headlines and subtext, followed by feature grids (implied by content structure) or detailed text-left/image-right arrangements. The design creates breathing room between content sections for a clean feel. Navigation is a persistent top bar with minimal links and a prominent Primary Action Button.

## Agent Prompt Guide

Quick Color Reference:
text: #292c3d
background: #fafbfc
border: #292c3d (for strong boundary)
accent: #67beff
primary action: #67beff (filled action)

Example Component Prompts:
Create a hero section: Canvas White background with a subtle abstract blue texture. Centered heading 'We’ve typed for 150 years. It’s time to speak.' in PP Neue Montreal Book, weight 200, size 72px, color Dark Charcoal (#292c3d). Below it, add body text 'Aqua turns your voice into clear text in real time, for everything from AI prompts to essays.' in PP Neue Montreal Book, weight 400, size 24px, color Soft Lead (#3e4150).

Create a Primary Action Button: 'Download now' label, filled with Sky Action Blue (#67beff), text color Near Black (#000000), 110px border-radius, padding 0px vertical, 24px horizontal.

Create a Light Elevated Card with inner padding and specific shadow: Canvas White background (#fafbfc), 12px border-radius, padding 20px on all sides. Apply shadow: rgba(0, 0, 0, 0.02) 0px 0px 0px 1px, rgba(0, 0, 0, 0.02) 0px 1px 1px 0.5px, rgba(0, 0, 0, 0.02) 0px 3px 3px 1.5px, rgba(0, 0, 0, 0.02) 0px 6px 6px -3px, rgba(0, 0, 0, 0.02) 0px 12px 12px -6px, rgba(0, 0, 0, 0.02) 0px 24px 24px -12px.

Create a navigation link: 'Pricing' label, text color Soft Lead (#3e4150), font PP Neue Montreal Book, weight 400, size 16px.

## Similar Brands

- **Stripe** — Shares a sophisticated, spacious light UI with extensive use of subtle shadows for elevation and a clean, sharp typographic aesthetic for headlines.
- **Linear** — Exhibits a similar focus on clarity and precision through high-contrast text on light backgrounds, refined typography even for large headlines, and functional, minimal use of color.
- **Framer** — Features a modern, light aesthetic with a single strong accent color, paired with clean typography and a sense of depth created by soft, diffused shadows on cards.
- **Notion** — Utilizes a clean, white-space dominant interface with a clear typographic hierarchy and minimal, purposeful splashes of color for interactive elements and highlights.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #fafbfc;
  --color-cloud-gray: #f3f7fa;
  --color-pale-ash: #f2f6fa;
  --color-porcelain-whisper: #efefef;
  --color-dark-charcoal: #292c3d;
  --color-soft-lead: #3e4150;
  --color-muted-stone: #686a76;
  --color-sky-action-blue: #67beff;
  --color-deep-link-blue: #4288ff;
  --color-near-black: #000000;
  --color-dark-card-surface: #171719;
  --color-subtle-dark-card: #1e1e20;

  /* Typography — Font Families */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-pp-neue-montreal: 'PP Neue Montreal', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geist-mono: 'Geist Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-ibm-plex-mono: 'IBM Plex Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.4;
  --text-body: 14px;
  --leading-body: 1.6;
  --text-subheading: 20px;
  --leading-subheading: 1.2;
  --text-heading: 40px;
  --leading-heading: 1.1;
  --text-heading-lg: 56px;
  --leading-heading-lg: 1;
  --text-display: 72px;
  --leading-display: 1;

  /* Typography — Weights */
  --font-weight-extralight: 200;
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-15: 15px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-30: 30px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-80: 80px;
  --spacing-124: 124px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 20px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 30px;
  --radius-3xl-2: 40px;
  --radius-full: 50px;
  --radius-full-2: 62px;
  --radius-full-3: 70px;
  --radius-full-4: 110px;
  --radius-full-5: 9999px;
  --radius-full-6: 99999px;

  /* Named Radii */
  --radius-cards: 12px;
  --radius-forms: 8px;
  --radius-pills: 70px;
  --radius-buttons: 110px;
  --radius-inputelements: 4px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.02) 0px 0px 0px 2px, rgba(0, 0, 0, 0.02) 0px 1px 1px 0.5px, rgba(0, 0, 0, 0.02) 0px 3px 3px 1.5px, rgba(0, 0, 0, 0.02) 0px 6px 6px -3px, rgba(0, 0, 0, 0.02) 0px 12px 12px -6px, rgba(0, 0, 0, 0.02) 0px 24px 24px -12px;
  --shadow-subtle-2: rgba(0, 0, 0, 0.02) 0px 0px 0px 1px, rgba(0, 0, 0, 0.02) 0px 1px 1px 0.5px, rgba(0, 0, 0, 0.02) 0px 3px 3px 1.5px, rgba(0, 0, 0, 0.02) 0px 6px 6px -3px, rgba(0, 0, 0, 0.02) 0px 12px 12px -6px, rgba(0, 0, 0, 0.02) 0px 24px 24px -12px;
  --shadow-subtle-3: rgb(255, 255, 255) 0px 1px 0px 0px inset, rgba(0, 0, 0, 0.06) 0px 0px 0px 1px, rgba(0, 0, 0, 0.06) 0px 1px 1px 0.5px, rgba(0, 0, 0, 0.06) 0px 3px 3px 1.5px, rgba(0, 0, 0, 0.06) 0px 6px 6px -3px, rgba(0, 0, 0, 0.06) 0px 12px 12px -6px, rgba(0, 0, 0, 0.06) 0px 24px 24px -12px;
  --shadow-subtle-4: rgba(0, 0, 0, 0.1) 0px 0px 0px 1px, rgba(0, 0, 0, 0.1) 0px 1px 1px 0.5px, rgba(0, 0, 0, 0.1) 0px 3px 3px 1.5px, rgba(0, 0, 0, 0.1) 0px 6px 6px -3px, rgba(0, 0, 0, 0.1) 0px 12px 12px -6px, rgba(0, 0, 0, 0.1) 0px 24px 24px -12px;
  --shadow-subtle-5: rgb(52, 52, 52) 0px 1px 0px 0px inset, rgba(0, 0, 0, 0.06) 0px 0px 0px 1px, rgba(0, 0, 0, 0.06) 0px 1px 1px 0.5px, rgba(0, 0, 0, 0.06) 0px 3px 3px 1.5px, rgba(0, 0, 0, 0.06) 0px 6px 6px -3px, rgba(0, 0, 0, 0.06) 0px 12px 12px -6px, rgba(0, 0, 0, 0.06) 0px 24px 24px -12px;

  /* Surfaces */
  --surface-canvas-white: #fafbfc;
  --surface-cloud-gray: #f3f7fa;
  --surface-pale-ash: #f2f6fa;
  --surface-porcelain-whisper: #efefef;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #fafbfc;
  --color-cloud-gray: #f3f7fa;
  --color-pale-ash: #f2f6fa;
  --color-porcelain-whisper: #efefef;
  --color-dark-charcoal: #292c3d;
  --color-soft-lead: #3e4150;
  --color-muted-stone: #686a76;
  --color-sky-action-blue: #67beff;
  --color-deep-link-blue: #4288ff;
  --color-near-black: #000000;
  --color-dark-card-surface: #171719;
  --color-subtle-dark-card: #1e1e20;

  /* Typography */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-pp-neue-montreal: 'PP Neue Montreal', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geist-mono: 'Geist Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-ibm-plex-mono: 'IBM Plex Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.4;
  --text-body: 14px;
  --leading-body: 1.6;
  --text-subheading: 20px;
  --leading-subheading: 1.2;
  --text-heading: 40px;
  --leading-heading: 1.1;
  --text-heading-lg: 56px;
  --leading-heading-lg: 1;
  --text-display: 72px;
  --leading-display: 1;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-15: 15px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-30: 30px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-80: 80px;
  --spacing-124: 124px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 30px;
  --radius-3xl-2: 40px;
  --radius-full: 50px;
  --radius-full-2: 62px;
  --radius-full-3: 70px;
  --radius-full-4: 110px;
  --radius-full-5: 9999px;
  --radius-full-6: 99999px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.02) 0px 0px 0px 2px, rgba(0, 0, 0, 0.02) 0px 1px 1px 0.5px, rgba(0, 0, 0, 0.02) 0px 3px 3px 1.5px, rgba(0, 0, 0, 0.02) 0px 6px 6px -3px, rgba(0, 0, 0, 0.02) 0px 12px 12px -6px, rgba(0, 0, 0, 0.02) 0px 24px 24px -12px;
  --shadow-subtle-2: rgba(0, 0, 0, 0.02) 0px 0px 0px 1px, rgba(0, 0, 0, 0.02) 0px 1px 1px 0.5px, rgba(0, 0, 0, 0.02) 0px 3px 3px 1.5px, rgba(0, 0, 0, 0.02) 0px 6px 6px -3px, rgba(0, 0, 0, 0.02) 0px 12px 12px -6px, rgba(0, 0, 0, 0.02) 0px 24px 24px -12px;
  --shadow-subtle-3: rgb(255, 255, 255) 0px 1px 0px 0px inset, rgba(0, 0, 0, 0.06) 0px 0px 0px 1px, rgba(0, 0, 0, 0.06) 0px 1px 1px 0.5px, rgba(0, 0, 0, 0.06) 0px 3px 3px 1.5px, rgba(0, 0, 0, 0.06) 0px 6px 6px -3px, rgba(0, 0, 0, 0.06) 0px 12px 12px -6px, rgba(0, 0, 0, 0.06) 0px 24px 24px -12px;
  --shadow-subtle-4: rgba(0, 0, 0, 0.1) 0px 0px 0px 1px, rgba(0, 0, 0, 0.1) 0px 1px 1px 0.5px, rgba(0, 0, 0, 0.1) 0px 3px 3px 1.5px, rgba(0, 0, 0, 0.1) 0px 6px 6px -3px, rgba(0, 0, 0, 0.1) 0px 12px 12px -6px, rgba(0, 0, 0, 0.1) 0px 24px 24px -12px;
  --shadow-subtle-5: rgb(52, 52, 52) 0px 1px 0px 0px inset, rgba(0, 0, 0, 0.06) 0px 0px 0px 1px, rgba(0, 0, 0, 0.06) 0px 1px 1px 0.5px, rgba(0, 0, 0, 0.06) 0px 3px 3px 1.5px, rgba(0, 0, 0, 0.06) 0px 6px 6px -3px, rgba(0, 0, 0, 0.06) 0px 12px 12px -6px, rgba(0, 0, 0, 0.06) 0px 24px 24px -12px;
}
```

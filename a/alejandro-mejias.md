# Alejandro Mejias — Style Reference
> High-contrast digital dossier

**Theme:** light

Alejandro Mejias uses a stark, high-contrast digital dossier aesthetic: unapologetic black and white with a single, electrifying neon yellow accent. The typography is precise, almost code-like, with generous letter-spacing on display elements providing an engineered feel. Component shapes are sharply defined, often with a subtly rounded 'digital pebble' radius, maintaining a serious yet approachable interface for a portfolio that values clarity and directness.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#000000` | `--color-midnight-ink` | Primary text, core UI borders, primary icon fill — forms the structural backbone against bright backgrounds |
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card surfaces, ghost button text and borders — acts as the primary light surface |
| Deep Shadow | `#080707` | `--color-deep-shadow` | Dark surface backgrounds, inverted text primary in dark components, border elements in darker contexts |
| Concrete Gray | `#c8c8c8` | `--color-concrete-gray` | Subtle background panels, dividers, and decorative accents — a gentle gray for low-contrast definition |
| Slate Trim | `#383838` | `--color-slate-trim` | Minor background tints and separation lines, providing an understated distinction between sections |
| Electric Lemon | `#ebff00` | `--color-electric-lemon` | Primary action backgrounds, highlight states, and key interactive elements — this vivid yellow is the sole chromatic accent, signaling interactivity and modern flair |

## Tokens — Typography

### sans-serif — sans-serif — detected in extracted data but not described by AI · `--font-sans-serif`
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.2
- **Role:** sans-serif — detected in extracted data but not described by AI

### IBM Plex Mono — Body text, metadata, labels, and secondary links — its monospace character provides a structured, technical feel, amplified by varied letter-spacing to control density and emphasis. · `--font-ibm-plex-mono`
- **Substitute:** monospace
- **Weights:** 500, 600
- **Sizes:** 10px, 11px, 14px, 18px
- **Line height:** 1.00, 1.20, 1.40
- **Letter spacing:** -0.05em (10px), 0.086em (14px), 0.109em (18px)
- **Role:** Body text, metadata, labels, and secondary links — its monospace character provides a structured, technical feel, amplified by varied letter-spacing to control density and emphasis.

### FK Raster Grotesk Compact Trial Sharp — Display headings and prominent titles — this custom typeface with its wide tracking gives headlines a distinct, impactful, almost architectural presence. · `--font-fk-raster-grotesk-compact-trial-sharp`
- **Substitute:** Impact, system-ui
- **Weights:** 400
- **Sizes:** 32px, 48px
- **Line height:** 1.00
- **Letter spacing:** 0.042em
- **Role:** Display headings and prominent titles — this custom typeface with its wide tracking gives headlines a distinct, impactful, almost architectural presence.

### Be Vietnam Pro — Standard body copy and general content — a clean, unfussy sans-serif providing clear readability without competing with the display typography. · `--font-be-vietnam-pro`
- **Substitute:** Inter, system-ui
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.40
- **Letter spacing:** normal
- **Role:** Standard body copy and general content — a clean, unfussy sans-serif providing clear readability without competing with the display typography.

### Inter Medium — Button text and interactive labels — compact and slightly condensed, supporting actionable elements with directness. · `--font-inter-medium`
- **Substitute:** Inter, system-ui
- **Weights:** 500
- **Sizes:** 16px
- **Line height:** 1.20
- **Letter spacing:** -0.012em
- **Role:** Button text and interactive labels — compact and slightly condensed, supporting actionable elements with directness.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1 | -0.05px | `--text-caption` |
| body | 14px | 1.2 | 0.086px | `--text-body` |
| heading-sm | 18px | 1.4 | 0.109px | `--text-heading-sm` |
| heading | 32px | 1 | 0.042px | `--text-heading` |
| display | 48px | 1 | 0.042px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 8 | 8px | `--spacing-8` |
| 10 | 10px | `--spacing-10` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 48 | 48px | `--spacing-48` |
| 80 | 80px | `--spacing-80` |
| 100 | 100px | `--spacing-100` |

### Border Radius

| Element | Value |
|---------|-------|
| small | 16px |
| inputs | 4px |
| medium | 30px |
| buttons | 4px |
| default | 24px |
| circular | 50px |
| prominent | 84px |
| buttonGhost | 94px |

### Layout

- **Section gap:** 48px
- **Card padding:** 16px
- **Element gap:** 10px

## Components

### Ghost Header Link
**Role:** Navigation link

Text in Midnight Ink on Canvas White background, with an implied border around the text area. Uses IBM Plex Mono 14px, weight 500. No explicit padding detected, relies on surrounding layout for spacing. Radius 4px.

### Call to Action Button (Filled)
**Role:** Primary action button

Filled with Electric Lemon background, text in Deep Shadow. Padding 4px vertical, 16px horizontal. Radius 94px (virtually a pill shape). Text uses IBM Plex Mono 14px, weight 500.

### Dark Filled Icon Button
**Role:** Secondary action button, often with icon

Filled with Deep Shadow background, text in Canvas White, with subtle border for definition. Padding 10px all sides. Radius 50px (circular). Text uses Inter Medium 16px, weight 500, letter-spacing -0.012em.

### Rounded Image Container
**Role:** Visual content container

Images contained within a Canvas White background, bordered by Midnight Ink. Radius 24px, providing a soft, object-like treatment to visuals.

### Work Card
**Role:** Project showcase container

Large interactive container on a Concrete Gray background. Minimal padding derived from context, often borders in Midnight Ink. Radius 24px.

### Tag / Badge
**Role:** Categorization or status indicator

Small rectangular element with Midnight Ink text on a Canvas White background, with a 4px radius. Used for metadata and labels.

## Do's and Don'ts

### Do
- Prioritize Midnight Ink (#000000) for all primary text and critical UI borders for maximum contrast against light surfaces.
- Utilize Electric Lemon (#ebff00) exclusively for primary call-to-action backgrounds and active states; avoid its use in non-interactive elements.
- For display headlines, use FK Raster Grotesk Compact Trial Sharp at 32px or 48px with a line height of 1.00 and letter-spacing of 0.042em.
- Apply a 24px border-radius to prominent image containers and larger card elements to maintain a consistent soft edge.
- Ensure all buttons use a letter-spacing of -0.012em with Inter Medium 16px, weight 500, for compact, visually dense labels.
- Implement element gaps of 10px between closely related items and section gaps of 48px for clear separation between content blocks.
- Use IBM Plex Mono for all secondary text, timestamps, and metadata, varying letter-spacing as specified for specific sizes.

### Don't
- Do not introduce new chromatic colors; adhere strictly to the Electric Lemon accent for all color highlights.
- Avoid excessive use of shadows; elevation should be primarily conveyed through distinct background colors and borders.
- Do not deviate from the specified font families; their distinct characteristics are critical to the brand identity.
- Refrain from using generic rectangular buttons; prefer the 4px radius for standard buttons and 94px for pill-shaped primary actions.
- Do not use letter-spacing on Be Vietnam Pro body copy; maintain normal tracking for optimal readability.
- Avoid overly generous padding or spacing within components; the design favors a compact, information-dense layout.
- Do not use gradients; the system relies on solid color blocks and sharp contrasts for visual impact.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Canvas White | `#ffffff` | Base page background and primary card surfaces. |
| 2 | Concrete Gray | `#c8c8c8` | Subtle background panels and section dividers for slight visual separation. |
| 3 | Slate Trim | `#383838` | Slightly darker accent panels, providing more distinct background layers. |
| 4 | Deep Shadow | `#080707` | Darkest surface elements, used for components requiring high contrast or inverted themes. |

## Imagery

Imagery largely consists of product mockups and stylized abstract branding elements. Photography, when present (e.g., self-portrait), is typically contained within a rounded border. Product mockups are often full-image, featuring crisp UI elements on neutral backgrounds. Iconography is primarily outlined, using Midnight Ink, maintaining a minimalist and consistent stroke weight.

## Layout

The site uses a contained, centered layout, with content constrained by implied horizontal margins. The hero section is often a full-bleed dark or light background with a prominent centered headline or branding element. Sections generally employ a consistent vertical spacing of 48px, creating a clear rhythm. Content is arranged in alternating text-left/image-right or centered stacks. Navigation is a minimalist top bar, staying tight to the edges, occasionally featuring a fixed 'Book a Call' button. There's an absence of complex grid systems, favoring direct, linear presentation of information.

## Agent Prompt Guide

Quick Color Reference: 
text: #000000
background: #ffffff
border: #000000
accent: #ebff00
primary action: #ebff00 (filled action)

Example Component Prompts:
1. Create a primary call-to-action button: background Electric Lemon (#ebff00), text Deep Shadow (#080707), padding 4px vertical / 16px horizontal, radius 94px. Text should use IBM Plex Mono 14px, weight 500.
2. Create a navigation link: text Midnight Ink (#000000), implicit background Canvas White (#ffffff). Text should use IBM Plex Mono 14px, weight 500, no letter-spacing (for header links).
3. Create a dark filled icon button: background Deep Shadow (#080707), text Canvas White (#ffffff), padding 10px all sides, radius 50px. Text uses Inter Medium 16px, weight 500, letter-spacing -0.012em.
4. Design a project showcase card: background Concrete Gray (#c8c8c8), border Midnight Ink (#000000). Apply a 24px border-radius. Headline uses FK Raster Grotesk Compact Trial Sharp 32px, weight 400, letter-spacing 0.042em. Body text uses Be Vietnam Pro 16px, weight 400.

## Similar Brands

- **Stripe** — Shared use of stark black-and-white, precise typography, and a single accent color for interactive elements.
- **Linear** — Similar high-contrast, minimalist UI with a technical, code-editor aesthetic and restrained use of color.
- **Framer** — Features a strong geometric aesthetic, clean-cut sections, and an emphasis on highly stylized interactive components.
- **Read.cv** — Uses a similar approach to typography as a primary design element, with sharp geometric forms and a focus on content hierarchy.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-canvas-white: #ffffff;
  --color-deep-shadow: #080707;
  --color-concrete-gray: #c8c8c8;
  --color-slate-trim: #383838;
  --color-electric-lemon: #ebff00;

  /* Typography — Font Families */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ibm-plex-mono: 'IBM Plex Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-fk-raster-grotesk-compact-trial-sharp: 'FK Raster Grotesk Compact Trial Sharp', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-be-vietnam-pro: 'Be Vietnam Pro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter-medium: 'Inter Medium', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1;
  --tracking-caption: -0.05px;
  --text-body: 14px;
  --leading-body: 1.2;
  --tracking-body: 0.086px;
  --text-heading-sm: 18px;
  --leading-heading-sm: 1.4;
  --tracking-heading-sm: 0.109px;
  --text-heading: 32px;
  --leading-heading: 1;
  --tracking-heading: 0.042px;
  --text-display: 48px;
  --leading-display: 1;
  --tracking-display: 0.042px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-48: 48px;
  --spacing-80: 80px;
  --spacing-100: 100px;

  /* Layout */
  --section-gap: 48px;
  --card-padding: 16px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 30px;
  --radius-3xl-3: 40px;
  --radius-full: 50px;
  --radius-full-2: 60px;
  --radius-full-3: 72px;
  --radius-full-4: 84px;
  --radius-full-5: 94px;
  --radius-full-6: 120px;

  /* Named Radii */
  --radius-small: 16px;
  --radius-inputs: 4px;
  --radius-medium: 30px;
  --radius-buttons: 4px;
  --radius-default: 24px;
  --radius-circular: 50px;
  --radius-prominent: 84px;
  --radius-buttonghost: 94px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-concrete-gray: #c8c8c8;
  --surface-slate-trim: #383838;
  --surface-deep-shadow: #080707;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-canvas-white: #ffffff;
  --color-deep-shadow: #080707;
  --color-concrete-gray: #c8c8c8;
  --color-slate-trim: #383838;
  --color-electric-lemon: #ebff00;

  /* Typography */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ibm-plex-mono: 'IBM Plex Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-fk-raster-grotesk-compact-trial-sharp: 'FK Raster Grotesk Compact Trial Sharp', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-be-vietnam-pro: 'Be Vietnam Pro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter-medium: 'Inter Medium', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1;
  --tracking-caption: -0.05px;
  --text-body: 14px;
  --leading-body: 1.2;
  --tracking-body: 0.086px;
  --text-heading-sm: 18px;
  --leading-heading-sm: 1.4;
  --tracking-heading-sm: 0.109px;
  --text-heading: 32px;
  --leading-heading: 1;
  --tracking-heading: 0.042px;
  --text-display: 48px;
  --leading-display: 1;
  --tracking-display: 0.042px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-48: 48px;
  --spacing-80: 80px;
  --spacing-100: 100px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 30px;
  --radius-3xl-3: 40px;
  --radius-full: 50px;
  --radius-full-2: 60px;
  --radius-full-3: 72px;
  --radius-full-4: 84px;
  --radius-full-5: 94px;
  --radius-full-6: 120px;
}
```

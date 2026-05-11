# Dimension — Style Reference
> Deep-space command center

**Theme:** dark

Dimension employs a dark, immersive interface, reminiscent of a command center displaying critical information. Its surfaces range from a deep, nearly black base to subtle, translucent grays, often paired with blurred backgrounds to create depth. Typography is crisp and compact, using a blend of modern sans-serifs with precise letter-spacing for high legibility in a low-light setting. Interactions are defined by ghost-like controls, soft white accents, and carefully calibrated radii that hint at physical buttons, maintaining a sense of focused utility over decorative flourish.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Base | `#0a0a0a` | `--color-midnight-base` | Page canvas, primary dark background for all interface elements |
| Storm Gray | `#161616` | `--color-storm-gray` | Muted text, subtle borders, accent text in navigation |
| Gunmetal | `#282828` | `--color-gunmetal` | Element borders, subtle strokes, icon outlines |
| Slate Text | `#686868` | `--color-slate-text` | Secondary body text, disabled states, helper text |
| Ash Text | `#b2b2b2` | `--color-ash-text` | Tertiary text, subtle button labels, less prominent links |
| Silver Whisper | `#c2c2c2` | `--color-silver-whisper` | Muted body text, placeholder text |
| Ghost White | `#e5e5e5` | `--color-ghost-white` | Hairline borders, dividers, input outlines, and card edges on light surfaces. Do not promote it to the primary CTA color |
| Canvas White | `#ffffff` | `--color-canvas-white` | Active text, primary button backgrounds, default icon fills |
| Gradient Aura | `linear-gradient(rgb(72, 103, 175), rgb(156, 175, 184), rgb(196, 149, 119))` | `--color-gradient-aura` | Background gradient for initial landing experience, creating an atmospheric, deep-space visual |
| Interactive Glow | `radial-gradient(50% 50%, rgb(107, 98, 242) 0%, rgb(255, 255, 255) 100%)` | `--color-interactive-glow` | Supporting palette color for small decorative accents when the core palette needs contrast. Do not promote it to the primary CTA color; Subtle indicator lines, decorative background lines, and ambient light effects |

## Tokens — Typography

### DM Sans — Used for body text, links, and detailed information. Its slight contrast to Geist provides clear distinction while maintaining overall readability thanks to subtle tracking adjustments for larger sizes. · `--font-dm-sans`
- **Substitute:** Inter
- **Weights:** 400, 500, 700
- **Sizes:** 14px, 15px, 16px, 18px, 40px, 72px
- **Line height:** 1.00, 1.11, 1.20, 1.25, 1.43, 1.50, 1.56
- **Letter spacing:** -0.035em at 72px, 0.025em elsewhere
- **Role:** Used for body text, links, and detailed information. Its slight contrast to Geist provides clear distinction while maintaining overall readability thanks to subtle tracking adjustments for larger sizes.

### Geist — Primary typeface for headings and select interface elements. Its clean, technical aesthetic reinforces the AI-driven product identity. · `--font-geist`
- **Substitute:** system-ui
- **Weights:** 400, 500, 600
- **Sizes:** 14px, 16px, 18px, 24px, 32px, 36px, 48px
- **Line height:** 1.00, 1.11, 1.14, 1.33, 1.43, 1.50, 1.71
- **Letter spacing:** normal
- **Role:** Primary typeface for headings and select interface elements. Its clean, technical aesthetic reinforces the AI-driven product identity.

### system-ui — system-ui — detected in extracted data but not described by AI · `--font-system-ui`
- **Weights:** 400, 500
- **Sizes:** 18px
- **Line height:** 1.5
- **Role:** system-ui — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 14px | 1.5 | 0.35px | `--text-caption` |
| body | 16px | 1.5 | 0.4px | `--text-body` |
| subheading | 18px | 1.5 | 0.45px | `--text-subheading` |
| heading-sm | 24px | 1.33 | — | `--text-heading-sm` |
| heading | 32px | 1.14 | — | `--text-heading` |
| heading-lg | 36px | 1.11 | — | `--text-heading-lg` |
| display | 48px | 1 | -0.672px | `--text-display` |

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
| 28 | 28px | `--spacing-28` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 44 | 44px | `--spacing-44` |
| 48 | 48px | `--spacing-48` |
| 56 | 56px | `--spacing-56` |
| 64 | 64px | `--spacing-64` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 24px |
| buttons | 9999px |
| callouts | 10px |
| app-icons-ui | 10px |
| hero-sections | 40px |

### Layout

- **Section gap:** 40px
- **Card padding:** 16px
- **Element gap:** 8px

## Components

### Ghost Button
**Role:** Secondary action button

backgroundColor=rgba(0, 0, 0, 0), color=rgb(255, 255, 255), border=1px solid rgb(229, 229, 229), borderRadius=10px, padding=8px 8px.

### Navigation Link Button
**Role:** Navigation items within a menu

backgroundColor=rgba(0, 0, 0, 0), color=rgb(255, 255, 255), border=1px solid rgb(229, 229, 229), borderRadius=0px, padding=6px 14px. These lack typical button padding and borders, resembling links more than buttons.

### Pill Button
**Role:** Primary action button, tags, or small interactive elements

backgroundColor=rgb(255, 255, 255), color=rgb(22, 22, 22), borderRadius=9999px, padding=8px 12px.

### Floating Pill Bar Button
**Role:** Buttons within the floating navigation/action bar

backgroundColor=rgb(255, 255, 255), color=rgb(0, 0, 0), borderRadius=9999px, padding=0px 0px. Minimal padding indicates these are inner elements of a larger component.

### Translucent Spotlight Card
**Role:** Displaying featured content or application icons

backgroundColor=rgba(0, 0, 0, 0.2), borderRadius=42px, no shadow, padding=22px 28px. Its translucency allows the background gradient to subtly show through.

### Section Bottom Card
**Role:** Separating content blocks at the bottom of a scrollable section

backgroundColor=rgb(255, 255, 255), borderRadius=40px 40px 0px 0px, no shadow, no padding.

### Ghost Corner Radius Card
**Role:** Subtle containers for information, minimal visual weight

backgroundColor=rgba(212, 212, 212, 0.1), borderRadius=24px, no shadow, no padding. Provides a faint, almost invisible grouping.

## Do's and Don'ts

### Do
- Use Midnight Base (#0a0a0a) as the default background for large sections and the page canvas.
- Apply Ghost White (#e5e5e5) for all primary body text and essential UI borders.
- Utilize Geist typeface for all headings (H1-H6) and DM Sans for body text, ensuring proper letter-spacing based on size.
- Every interactive element, especially buttons, must have a border-radius of 9999px for pill-shaped elements or 10px for standard rects.
- Create depth with the `backdrop-filter: blur(4px)` property on translucent UI elements, rather than heavy box-shadows.
- Maintain uniform element gaps of 8px between closely related UI elements, like buttons in a cluster or form fields.
- Emphasize content through contrast with Canvas White (#ffffff) for active states and primary action button fills.
- Use Storm Gray (#161616) for muted text and secondary UI strokes to provide subtle hierarchy.

### Don't
- Do not use strong, opaque background colors; darker, translucent, or gradient backgrounds are preferred.
- Avoid deep, dark shadows; elevation is achieved through subtle opacity changes, backdrop blurs, or very light, diffused shadows.
- Do not use generic system fonts in place of Geist or DM Sans for any main text content.
- Avoid hard, sharp corners; all cards, buttons, and significant containers require specific, deliberate rounding (radius 10px, 24px, 42px, or 9999px).
- Do not introduce strong chromatic colors for primary UI elements; reserve them for subtle accents, gradients, or as background atmosphere.
- Do not use a light theme; the interface always defaults to a dark aesthetic.
- Avoid dense, tightly packed layouts; prefer comfortable spacing with a base unit of 4px and elemental gaps of 8px.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Midnight Base | `#0a0a0a` | Dominant page and main container background. |
| 1 | Translucent Accent | `#00000033` | Soft, translucent cards that overlay the base, allowing background gradients to show through, often paired with a backdrop blur. |
| 2 | Semi-Transparent Overlay | `#d4d4d41a` | Subtle, ghost-like cards or containers with minimal visual presence. |

## Elevation

- **Card:** `drop-shadow(rgba(255, 255, 255, 0.02) 0px 3px 4.5px), drop-shadow(rgba(0, 0, 0, 0.04) 0px 10px 8px), drop-shadow(rgba(0, 0, 0, 0.1) 0px 4px 3px)`

## Imagery

The imagery on Dimension is primarily interface-driven, featuring tightly cropped product screenshots of app icons and functional UI elements (like a task list). These are often contained within softly rounded, translucent cards. The aesthetic is clean and focused on showcasing product utility directly, rather than relying on lifestyle photography or abstract illustrations. When icons are present, they are either filled, multi-color app icons or simple, outlined, monochromatic interface symbols. The imagery serves an explanatory and product showcase role, presented with minimal decorative clutter.

## Layout

The page employs a full-bleed layout, where background gradients extend edge-to-edge, but content is contained within an implied max-width column, centered on the screen. The initial hero section features a dual-column layout: left for primary headline and feature list, right for a large product visual (app icons within a translucent card). Vertical rhythm is established by distinct sections, sometimes subtly delineated by an atmospheric background gradient. Navigation is a sticky bottom bar, featuring pill-shaped buttons with both text and icons, blending into the ambient background with subtle backdrop blurring. Content often appears in stacked blocks or side-by-side text/image arrangements.

## Agent Prompt Guide

Quick Color Reference:
text: #e5e5e5
background: #0a0a0a
border: #e5e5e5
accent: #6b62f2
primary action: #ffffff (filled action)

Example Component Prompts:
Create a Primary Action Button: #ffffff background, #000000 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
Create a translucent app icon card: background rgba(0,0,0,0.2), 42px corner radius, padding 22px vertical and 28px horizontal. Apply backdrop-filter: blur(4px).
Create a top-level heading: 'Geist' font, size 48px, color #e5e5e5, line height 1.0, letter spacing -0.672px.
Create a navigation bar item: 'DM Sans' font, size 16px, color #ffffff, background rgba(0,0,0,0), border 1px solid #e5e5e5, 0px radius, 6px vertical and 14px horizontal padding. 

## Similar Brands

- **Linear** — Shares a dark mode aesthetic with crisp, functional typography and a focus on clean, unobtrusive UI elements.
- **Raycast** — Utilizes a dark, command-line interface feel with subtle translucency and a preference for ghost-like interactive components.
- **Amie** — Features a minimal, functional UI with fine typographic detail and well-defined spacing, though Amie is primarily light-themed.
- **Figma** — Exhibits a similar approach to systematic spacing, clean neutrals, and a focus on clarity within a complex application interface.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-base: #0a0a0a;
  --color-storm-gray: #161616;
  --color-gunmetal: #282828;
  --color-slate-text: #686868;
  --color-ash-text: #b2b2b2;
  --color-silver-whisper: #c2c2c2;
  --color-ghost-white: #e5e5e5;
  --color-canvas-white: #ffffff;
  --color-gradient-aura: #4867af;
  --gradient-gradient-aura: linear-gradient(rgb(72, 103, 175), rgb(156, 175, 184), rgb(196, 149, 119));
  --color-interactive-glow: #6b62f2;
  --gradient-interactive-glow: radial-gradient(50% 50%, rgb(107, 98, 242) 0%, rgb(255, 255, 255) 100%);

  /* Typography — Font Families */
  --font-dm-sans: 'DM Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geist: 'Geist', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-system-ui: 'system-ui', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.5;
  --tracking-caption: 0.35px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: 0.4px;
  --text-subheading: 18px;
  --leading-subheading: 1.5;
  --tracking-subheading: 0.45px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.33;
  --text-heading: 32px;
  --leading-heading: 1.14;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1.11;
  --text-display: 48px;
  --leading-display: 1;
  --tracking-display: -0.672px;

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
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-44: 44px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 16px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 10px;
  --radius-2xl: 19px;
  --radius-3xl: 24px;
  --radius-3xl-2: 40px;
  --radius-full: 64px;
  --radius-full-2: 9999px;

  /* Named Radii */
  --radius-cards: 24px;
  --radius-buttons: 9999px;
  --radius-callouts: 10px;
  --radius-app-icons-ui: 10px;
  --radius-hero-sections: 40px;

  /* Surfaces */
  --surface-midnight-base: #0a0a0a;
  --surface-translucent-accent: #00000033;
  --surface-semi-transparent-overlay: #d4d4d41a;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-base: #0a0a0a;
  --color-storm-gray: #161616;
  --color-gunmetal: #282828;
  --color-slate-text: #686868;
  --color-ash-text: #b2b2b2;
  --color-silver-whisper: #c2c2c2;
  --color-ghost-white: #e5e5e5;
  --color-canvas-white: #ffffff;
  --color-gradient-aura: #4867af;
  --color-interactive-glow: #6b62f2;

  /* Typography */
  --font-dm-sans: 'DM Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geist: 'Geist', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-system-ui: 'system-ui', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.5;
  --tracking-caption: 0.35px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: 0.4px;
  --text-subheading: 18px;
  --leading-subheading: 1.5;
  --tracking-subheading: 0.45px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.33;
  --text-heading: 32px;
  --leading-heading: 1.14;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1.11;
  --text-display: 48px;
  --leading-display: 1;
  --tracking-display: -0.672px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-44: 44px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 10px;
  --radius-2xl: 19px;
  --radius-3xl: 24px;
  --radius-3xl-2: 40px;
  --radius-full: 64px;
  --radius-full-2: 9999px;
}
```

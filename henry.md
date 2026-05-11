# Henry — Style Reference
> Midnight Command Center: high-contrast text on deep, textured charcoal, punctuated by precise, functional color accents.

**Theme:** dark

ai.work presents a dark, commanding interface, pairing deep charcoal canvases with crisp, high-contrast typography. Subtle background textures and gradient accents add depth without sacrificing clarity, setting an atmosphere of focused, high-performance technology. Components adhere to a minimal aesthetic, utilizing soft, rounded edges and light elevation to delineate interactive elements, emphasizing functional utility over decorative flair. The system uses specific color accents for visual coding without overwhelming the overall dark environment.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Obsidian | `#141414` | `--color-obsidian` | Primary background for pages and main content areas, providing a deep, textured base |
| Carbon | `#000000` | `--color-carbon` | Deepest shade for text, borders, and subtle background elements, adding contrast |
| Slate Mist | `#d4d0c9` | `--color-slate-mist` | Primary text color for headlines and important content, as well as neutral button backgrounds and borders |
| Ash Gray | `#878581` | `--color-ash-gray` | Secondary text for descriptions and muted elements |
| White Smoke | `#ffffff` | `--color-white-smoke` | High-contrast text against dark backgrounds, used sparingly for emphasis |
| Light Mist | `#d9d9d9` | `--color-light-mist` | Used for specific text elements like card subheadings and fill for decorative icons |
| Deep Plum | `#a454ff` | `--color-deep-plum` | Background for accent cards and decorative sections, creating a subtle brand presence |
| Alert Orange | `#ff9634` | `--color-alert-orange` | Orange outline accent for tags, dividers, and focused UI edges |
| Success Green | `#1fe274` | `--color-success-green` | Green outline accent for tags, dividers, and focused UI edges. Use as a supporting accent, not as a status color |
| Info Blue | `#00a8f0` | `--color-info-blue` | Blue outline accent for tags, dividers, and focused UI edges. Use as a supporting accent, not as a status color |
| Highlight Pink | `#cf70ff` | `--color-highlight-pink` | Border and text for emphasizing certain categories or features |
| Slack Blue | `#36c5f0` | `--color-slack-blue` | Decorative fill for specific integration icons, representing third-party services |
| Frosted Gray Gradient | `linear-gradient(rgba(173, 173, 173, 0.98) 0%, rgb(74, 74, 74) 100%)` | `--color-frosted-gray-gradient` | Subtle background gradient for elevated UI elements, providing a frosted glass effect |

## Tokens — Typography

### sans-serif — Fallback for general UI elements and small annotations. · `--font-sans-serif`
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.20
- **Letter spacing:** normal
- **Role:** Fallback for general UI elements and small annotations.

### NB International Pro — Main display and heading font, used for its anti-convention light weight which creates authority through restraint rather than volume. Substitute with 'Inter Light' or 'Open Sans Light'. · `--font-nb-international-pro`
- **Substitute:** Inter Light
- **Weights:** 400
- **Sizes:** 10px
- **Line height:** 0.90, 1.20
- **Letter spacing:** -0.0200em
- **Role:** Main display and heading font, used for its anti-convention light weight which creates authority through restraint rather than volume. Substitute with 'Inter Light' or 'Open Sans Light'.

### NB International Pro — Primary body and sub-heading font, maintaining consistency with its light counterpart. Substitute with 'Inter' or 'Open Sans'. · `--font-nb-international-pro`
- **Substitute:** Inter
- **Weights:** 300
- **Sizes:** 14px, 16px, 64px
- **Line height:** 1.00, 1.50, 1.71
- **Letter spacing:** -0.0200em
- **Role:** Primary body and sub-heading font, maintaining consistency with its light counterpart. Substitute with 'Inter' or 'Open Sans'.

### NB International Pro — Used for specific emphasis in body text, such as small titles or highlighted phrases. Substitute with 'Inter Medium' or 'Open Sans Medium'. · `--font-nb-international-pro`
- **Substitute:** Inter Medium
- **Weights:** 400
- **Sizes:** 10px
- **Line height:** 1.20
- **Letter spacing:** -0.0200em
- **Role:** Used for specific emphasis in body text, such as small titles or highlighted phrases. Substitute with 'Inter Medium' or 'Open Sans Medium'.

### NB International Pro Mono — Monospaced font for code snippets, tags, or small, technical labels where precise alignment is needed. Substitute with 'Roboto Mono' or 'Source Code Pro'. · `--font-nb-international-pro-mono`
- **Substitute:** Roboto Mono
- **Weights:** 400
- **Sizes:** 10px
- **Line height:** 0.90, 1.20
- **Letter spacing:** normal
- **Role:** Monospaced font for code snippets, tags, or small, technical labels where precise alignment is needed. Substitute with 'Roboto Mono' or 'Source Code Pro'.

### Inter — Secondary body text and navigation items, offering good readability at smaller sizes with varied tracking. · `--font-inter`
- **Weights:** 400, 500, 600
- **Sizes:** 12px, 14px, 16px
- **Line height:** 1.14, 1.25, 1.33, 1.41, 1.43, 1.50
- **Letter spacing:** -0.0370em, -0.0200em, -0.0120em, -0.0090em, -0.0070em, -0.0060em
- **Role:** Secondary body text and navigation items, offering good readability at smaller sizes with varied tracking.

### Inter — Used for navigation and interactive elements where slight emphasis is needed without increasing size. · `--font-inter`
- **Weights:** 400, 500, 600
- **Sizes:** 12px, 14px, 16px
- **Line height:** 1.14, 1.25, 1.33, 1.41, 1.43, 1.50
- **Letter spacing:** -0.0370em, -0.0200em, -0.0120em, -0.0090em, -0.0070em, -0.0060em
- **Role:** Used for navigation and interactive elements where slight emphasis is needed without increasing size.

### Inter — Used for bolder text elements, such as tab labels or strong emphasis. · `--font-inter`
- **Weights:** 400, 500, 600
- **Sizes:** 12px, 14px, 16px
- **Line height:** 1.14, 1.25, 1.33, 1.41, 1.43, 1.50
- **Letter spacing:** -0.0370em, -0.0200em, -0.0120em, -0.0090em, -0.0070em, -0.0060em
- **Role:** Used for bolder text elements, such as tab labels or strong emphasis.

### NB International Pro Regular — NB International Pro Regular — detected in extracted data but not described by AI · `--font-nb-international-pro-regular`
- **Weights:** 400
- **Sizes:** 10px, 14px, 15px, 16px, 20px, 24px, 32px, 64px, 96px, 204px
- **Line height:** 1, 1.14, 1.2, 1.25, 1.33, 1.43, 1.5
- **Letter spacing:** -0.02
- **Role:** NB International Pro Regular — detected in extracted data but not described by AI

### NB International Pro CG Medium — NB International Pro CG Medium — detected in extracted data but not described by AI · `--font-nb-international-pro-cg-medium`
- **Weights:** 500
- **Sizes:** 14px, 15px
- **Line height:** 1.33, 1.43
- **Letter spacing:** -0.02
- **Role:** NB International Pro CG Medium — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.2 | — | `--text-caption` |
| body | 14px | 1.43 | -0.28px | `--text-body` |
| body-lg | 16px | 1.5 | -0.256px | `--text-body-lg` |
| subheading | 20px | 1.25 | -0.4px | `--text-subheading` |
| heading-sm | 24px | 1.33 | -0.48px | `--text-heading-sm` |
| heading | 32px | 1.25 | -0.64px | `--text-heading` |
| heading-lg | 64px | 1.14 | -1.28px | `--text-heading-lg` |
| display | 96px | 1 | -1.92px | `--text-display` |
| display-lg | 204px | 1 | -4.08px | `--text-display-lg` |

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
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 36 | 36px | `--spacing-36` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 56 | 56px | `--spacing-56` |
| 60 | 60px | `--spacing-60` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 112 | 112px | `--spacing-112` |
| 160 | 160px | `--spacing-160` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 10px |
| icons | 2px |
| inputs | 6px |
| avatars | 100px |
| buttons | 100px |
| modules | 16px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(20, 21, 26, 0.05) 0px 1px 2px 0px` | `--shadow-subtle` |

### Layout

- **Section gap:** 56px
- **Card padding:** 16px
- **Element gap:** 4px

## Components

### Primary Ghost Button
**Role:** Main call to action, outlined on dark backgrounds.

Background: rgba(212, 208, 201, 0.04), text color: Slate Mist (#d4d0c9), border: 1px solid Slate Mist (#d4d0c9), border-radius: 4px, padding: 8px 12px.

### Pill Accent Button
**Role:** Secondary call to action or navigation, pill-shaped with subtle background.

Background: rgba(212, 208, 201, 0.1), text color: Slate Mist (#d4d0c9), border: none, border-radius: 100px, padding: 10px 30.5px.

### Compact Action Card
**Role:** Interactive card for short actions or information snippets.

Background: rgba(212, 208, 201, 0.1), border-radius: 10px, shadow: rgba(0, 0, 0, 0.18) 0px 0.6px 0.6px -1.25px, rgba(0, 0, 0, 0.16) 0px 2.3px 2.3px -2.5px, rgba(0, 0, 0, 0.06) 0px 10px 10px -3.75px, padding: 6px.

### Feature Highlight Card
**Role:** Larger card for prominent features or content blocks.

Background: rgba(217, 217, 217, 0.04), border-radius: 16px, no shadow, padding: 16px.

### Floating Dialog Card
**Role:** Ephemeral UI elements, like tooltips or small popovers.

Background: rgba(212, 208, 201, 0.1), border-radius: 16px, no shadow, padding: 10px 16px.

### Skill Module Card
**Role:** Display individual AI skills with subtle background.

Background: rgba(212, 208, 201, 0.04), border-radius: 8px, no shadow, padding: 0px 0px 160px 0px (varied, but top 0 padding common).

## Do's and Don'ts

### Do
- Use Obsidian (#141414) as the primary background for all main page sections.
- Employ NB International Pro Light (weight 300) for all major headlines to convey a subtle, modern authority.
- Utilize Slate Mist (#d4d0c9) for primary text and high-visibility interface elements like inactive button borders.
- Apply a border-radius of 100px for all interactive pill-shaped elements and specific avatar-like graphics to soften appearance.
- Maintain a compact density, using 4px as the base unit for element gaps, scaling up to 16px for card padding.
- Use distinct accent colors like Alert Orange (#ff9634) or Success Green (#1fe274) sparingly for functional indicators or category tags, never for primary actions.
- Ensure interactive elements like buttons and cards use a subtle rgba background with a low opacity for a floating effect against the dark background.

### Don't
- Do not use highly saturated brand colors for large background areas or extensive text; restrict them to small accents.
- Avoid generic system fonts for display text; prioritize NB International Pro for brand consistency.
- Do not introduce strong, intrusive shadows; rely on low-opacity rgba backgrounds and subtle inner shadows for depth.
- Avoid using bright or white backgrounds in prominent sections, as the system is optimized for a dark theme.
- Do not vary border-radius significantly across similar components; adhere to 100px for pills, 10px for cards, and 4px for ghost buttons.
- Refrain from using purely decorative imagery; all visuals should be directly related to product functionality or brand value.
- Do not use fully opaque blacks or whites for text/backgrounds unless for extreme contrast, instead use slightly desaturated Obsidian or Slate Mist.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Base Canvas | `#141414` | Primary page and main content background. |
| 2 | Module Surface | `#d4d0c90a` | Background for secondary content blocks, skill cards, and ghost buttons. |
| 3 | Interactive Surface | `#d4d0c91a` | Background for interactive cards and pill-shaped buttons, suggesting slight elevation. |

## Elevation

- **Interactive Card:** `rgba(0, 0, 0, 0.18) 0px 0.602187px 0.602187px -1.25px, rgba(0, 0, 0, 0.16) 0px 2.28853px 2.28853px -2.5px, rgba(0, 0, 0, 0.06) 0px 10px 10px -3.75px`

## Imagery

This system primarily uses iconography and product-focused UI elements. Icons are typically filled with '#000000' or '#d9d9d9' and often feature a 2px radius. Photography is sparingly used as large, full-bleed scenic backgrounds, adding atmosphere without distracting from UI. There are no lifestyle shots or abstract illustrations. Image density is low, with UI elements and typography dominating the visual space. Product screenshots are contained within cards, showing precise functionality.

## Layout

The page primarily uses a full-bleed dark background, but content within sections is implicitly contained and horizontally centered, suggesting a max-width layout though not explicitly defined. The hero section is full-bleed with a prominent centered headline and descriptive text, followed by centered action buttons. Subsequent sections alternate between tool integration strips and multi-column card grids (e.g., 3-column skill modules or 2-column feature highlights). Vertical rhythm is created by consistent section gaps, maintaining a spacious, breathable layout.

## Agent Prompt Guide

Quick Color Reference:
text: #d4d0c9
background: #141414
border: #000000
accent: #a454ff
primary action: #d4d0c9 (filled action)

Example Component Prompts:
Create a hero headline: Text 'Introducing Henry.', font NB International Pro, weight 300, size 64px, lineHeight 1.14, Slate Mist (#d4d0c9) color, letter-spacing -1.28px. Background #141414.
Create a ghost button: Text 'Request a Demo.', font Inter, weight 500, size 14px, lineHeight 1.4, background rgba(212, 208, 201, 0.04), text color Slate Mist (#d4d0c9), 1px solid Slate Mist (#d4d0c9) border, 4px radius, 8px 12px padding.
Create a feature card: Text 'App access management', font NB International Pro, weight 400, size 16px, lineHeight 1.5, Light Mist (#d9d9d9) color. Background rgba(217, 217, 217, 0.04), 16px radius, 16px padding.
Create a skill tag with focus: Text 'Learning', font NB International Pro, weight 400, size 10px, lineHeight 1.2, Info Blue (#00a8f0) color, 1px solid Info Blue (#00a8f0) border, 6px radius, background rgba(0,0,0,0).
Create an interactive card: Headline 'Figma dev seat required', font NB International Pro, weight 400, size 16px, lineHeight 1.5, Slate Mist (#d4d0c9) color. Background rgba(212, 208, 201, 0.1), 10px radius, 6px padding and a shadow of rgba(0, 0, 0, 0.18) 0px 0.6px 0.6px -1.25px.

## Similar Brands

- **Linear** — Uses a dark theme with minimal UI, high-contrast typography, and subtle component elevation.
- **Raycast** — Features a command-line interface aesthetic with dark surfaces, contained UI, and focus on text clarity.
- **Superhuman** — Employs a fast, keyboard-driven dark UI with focused information density and subtle interactive states.
- **Vercel** — Features a dark mode aesthetic with strong typography, a focus on developer tools, and clean card-based layouts.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-obsidian: #141414;
  --color-carbon: #000000;
  --color-slate-mist: #d4d0c9;
  --color-ash-gray: #878581;
  --color-white-smoke: #ffffff;
  --color-light-mist: #d9d9d9;
  --color-deep-plum: #a454ff;
  --color-alert-orange: #ff9634;
  --color-success-green: #1fe274;
  --color-info-blue: #00a8f0;
  --color-highlight-pink: #cf70ff;
  --color-slack-blue: #36c5f0;
  --color-frosted-gray-gradient: #adadad;
  --gradient-frosted-gray-gradient: linear-gradient(rgba(173, 173, 173, 0.98) 0%, rgb(74, 74, 74) 100%);

  /* Typography — Font Families */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-nb-international-pro: 'NB International Pro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-nb-international-pro-mono: 'NB International Pro Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-nb-international-pro-regular: 'NB International Pro Regular', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-nb-international-pro-cg-medium: 'NB International Pro CG Medium', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.2;
  --text-body: 14px;
  --leading-body: 1.43;
  --tracking-body: -0.28px;
  --text-body-lg: 16px;
  --leading-body-lg: 1.5;
  --tracking-body-lg: -0.256px;
  --text-subheading: 20px;
  --leading-subheading: 1.25;
  --tracking-subheading: -0.4px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.33;
  --tracking-heading-sm: -0.48px;
  --text-heading: 32px;
  --leading-heading: 1.25;
  --tracking-heading: -0.64px;
  --text-heading-lg: 64px;
  --leading-heading-lg: 1.14;
  --tracking-heading-lg: -1.28px;
  --text-display: 96px;
  --leading-display: 1;
  --tracking-display: -1.92px;
  --text-display-lg: 204px;
  --leading-display-lg: 1;
  --tracking-display-lg: -4.08px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;

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
  --spacing-56: 56px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-112: 112px;
  --spacing-160: 160px;

  /* Layout */
  --section-gap: 56px;
  --card-padding: 16px;
  --element-gap: 4px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-md: 6px;
  --radius-lg: 10px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 32px;
  --radius-3xl-2: 44px;
  --radius-full: 56px;
  --radius-full-2: 100px;
  --radius-full-3: 999px;
  --radius-full-4: 10000px;

  /* Named Radii */
  --radius-cards: 10px;
  --radius-icons: 2px;
  --radius-inputs: 6px;
  --radius-avatars: 100px;
  --radius-buttons: 100px;
  --radius-modules: 16px;

  /* Shadows */
  --shadow-subtle: rgba(20, 21, 26, 0.05) 0px 1px 2px 0px;

  /* Surfaces */
  --surface-base-canvas: #141414;
  --surface-module-surface: #d4d0c90a;
  --surface-interactive-surface: #d4d0c91a;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-obsidian: #141414;
  --color-carbon: #000000;
  --color-slate-mist: #d4d0c9;
  --color-ash-gray: #878581;
  --color-white-smoke: #ffffff;
  --color-light-mist: #d9d9d9;
  --color-deep-plum: #a454ff;
  --color-alert-orange: #ff9634;
  --color-success-green: #1fe274;
  --color-info-blue: #00a8f0;
  --color-highlight-pink: #cf70ff;
  --color-slack-blue: #36c5f0;
  --color-frosted-gray-gradient: #adadad;

  /* Typography */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-nb-international-pro: 'NB International Pro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-nb-international-pro-mono: 'NB International Pro Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-nb-international-pro-regular: 'NB International Pro Regular', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-nb-international-pro-cg-medium: 'NB International Pro CG Medium', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.2;
  --text-body: 14px;
  --leading-body: 1.43;
  --tracking-body: -0.28px;
  --text-body-lg: 16px;
  --leading-body-lg: 1.5;
  --tracking-body-lg: -0.256px;
  --text-subheading: 20px;
  --leading-subheading: 1.25;
  --tracking-subheading: -0.4px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.33;
  --tracking-heading-sm: -0.48px;
  --text-heading: 32px;
  --leading-heading: 1.25;
  --tracking-heading: -0.64px;
  --text-heading-lg: 64px;
  --leading-heading-lg: 1.14;
  --tracking-heading-lg: -1.28px;
  --text-display: 96px;
  --leading-display: 1;
  --tracking-display: -1.92px;
  --text-display-lg: 204px;
  --leading-display-lg: 1;
  --tracking-display-lg: -4.08px;

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
  --spacing-56: 56px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-112: 112px;
  --spacing-160: 160px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-md: 6px;
  --radius-lg: 10px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 32px;
  --radius-3xl-2: 44px;
  --radius-full: 56px;
  --radius-full-2: 100px;
  --radius-full-3: 999px;
  --radius-full-4: 10000px;

  /* Shadows */
  --shadow-subtle: rgba(20, 21, 26, 0.05) 0px 1px 2px 0px;
}
```

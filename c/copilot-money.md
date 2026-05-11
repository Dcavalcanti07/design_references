# Copilot Money — Style Reference
> Midnight ocean with glowing buoys

**Theme:** dark

Copilot Money employs a sophisticated dark-mode aesthetic with a spacious canvas, primarily leveraging shades of deep blue and near-black. Dynamic, multi-colored 'tag' elements float across the interface, adding vibrant, soft-glow accents against the dark backdrop. Typography balances a modern geometric sans with a lighter, custom variable font, creating a refined information hierarchy. Components are soft-edged, often featuring inset shadows and subtle transparency, giving a sense of depth without harshness.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#000814` | `--color-midnight-ink` | Primary page background, elevated surface base, deep shadows |
| Deep Space | `#010d1e` | `--color-deep-space` | Secondary background, subtle dark surfaces, layered shadows |
| Obsidian | `#11263b` | `--color-obsidian` | Accent text, outlined element borders, subtle separation lines |
| Mist Gray | `#ccced0` | `--color-mist-gray` | Subtle headlines and body text, secondary interface elements |
| Shadow Blue | `#29303a` | `--color-shadow-blue` | Shadow base for elevated components |
| Deep Shadow | `#303741` | `--color-deep-shadow` | Darker shadow base for more prominent elevated components |
| Muted Stone | `#7f8ba4` | `--color-muted-stone` | Muted body text for secondary information and tooltips |
| Platinum Ghost | `#ffffff` | `--color-platinum-ghost` | Primary text, icon fill, accessible foreground on dark backgrounds |
| Teal Glow | `#00cc4b` | `--color-teal-glow` | Green outline accent for tags, dividers, and focused UI edges |
| Crimson Beam | `#ff4433` | `--color-crimson-beam` | Red outline accent for tags, dividers, and focused UI edges |
| Cosmic Blue | `#426088` | `--color-cosmic-blue` | Blue outline accent for tags, dividers, and focused UI edges. Do not promote it to the primary CTA color |
| Ocean Glimmer | `#597caa` | `--color-ocean-glimmer` | Link text, borders for ghost buttons, subtle interactive element highlights |
| Iris Pop | `#1c6cff` | `--color-iris-pop` | Primary action background, prominent interactive elements — a bright, inviting call to interaction |
| Sunbeam | `#fece4c` | `--color-sunbeam` | Category tags, icon accents, highlights |
| Amethyst Flare | `#9019e6` | `--color-amethyst-flare` | Category tags, decorative iconography, ambient glows |
| Slate Blue | `#5c6f8a` | `--color-slate-blue` | Subtle background for category tags, secondary cards |
| Cherry Blossom | `#ff33aa` | `--color-cherry-blossom` | Category tags, vibrant decorative accents |
| Pumpkin Zest | `#f27f0c` | `--color-pumpkin-zest` | Category tags, vibrant decorative accents |
| Golden Harvest | `#ff9900` | `--color-golden-harvest` | Category tags, vibrant decorative accents |
| Lime Soda | `#59cc33` | `--color-lime-soda` | Category tags, vibrant decorative accents |
| Indigo Wash | `#00215e` | `--color-indigo-wash` | Subtle background for links, dark page sections |
| Blue Gradient Overlay | `linear-gradient(5deg, rgba(91, 115, 149, 0.8) 10%, rgb(223, 228, 237) 90%)` | `--color-blue-gradient-overlay` | Decorative background gradient used sparingly for visual depth |

## Tokens — Typography

### Matter Variable Thin — Primary body and sub-heading text, creating a light, modern feel with its variable weight and precise tracking. Its thinness makes larger headlines feel restrained. · `--font-matter-variable-thin`
- **Weights:** 100
- **Sizes:** 11px, 12px, 13px, 14px, 15px, 16px, 18px, 22px, 38px, 56px
- **Line height:** 1.20, 1.30, 1.40, 1.60
- **Letter spacing:** -0.0200em at 56px, -0.0100em at 38px, 0.0100em at 18px, 0.0200em at 11-16px
- **OpenType features:** `'ss07', 'blwf', 'cv03', 'cv04', 'cv09', 'cv11'`
- **Role:** Primary body and sub-heading text, creating a light, modern feel with its variable weight and precise tracking. Its thinness makes larger headlines feel restrained.

### Jokker Medium — Accent headings and prominent body text; its medium weight provides structure and readability for key information. · `--font-jokker-medium`
- **Weights:** 500
- **Sizes:** 12px, 14px, 16px, 18px, 22px, 24px, 32px, 64px
- **Line height:** 1.00, 1.09, 1.10, 1.20, 1.40, 1.60
- **Letter spacing:** -0.0100em
- **OpenType features:** `'blwf', 'cv03', 'cv04', 'cv09', 'cv11'`
- **Role:** Accent headings and prominent body text; its medium weight provides structure and readability for key information.

### Matter-TRIAL SemiBold — Feature headings and callouts, designed for impact and distinctiveness with its tighter tracking. · `--font-matter-trial-semibold`
- **Weights:** 670
- **Sizes:** 28px
- **Line height:** 1.00
- **Letter spacing:** 0.0400em
- **Role:** Feature headings and callouts, designed for impact and distinctiveness with its tighter tracking.

### Jokker Semibold — Large display headings and section titles, commanding attention with its semi-bold weight and generous scale. · `--font-jokker-semibold`
- **Weights:** 600
- **Sizes:** 24px, 64px, 148px
- **Line height:** 0.90, 1.10, 1.20
- **Letter spacing:** -0.0200em
- **Role:** Large display headings and section titles, commanding attention with its semi-bold weight and generous scale.

### Jokker Regular — Standard body text, providing clarity and readability at smaller sizes for detailed information blocks. · `--font-jokker-regular`
- **Weights:** 400
- **Sizes:** 13px, 24px
- **Line height:** 1.40
- **OpenType features:** `'blwf', 'cv03', 'cv04', 'cv09', 'cv11'`
- **Role:** Standard body text, providing clarity and readability at smaller sizes for detailed information blocks.

### sans-serif — Fallback for system text, ensuring basic readability where custom fonts might not load. · `--font-sans-serif`
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.20
- **Role:** Fallback for system text, ensuring basic readability where custom fonts might not load.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 11px | 1.2 | 0.22px | `--text-caption` |
| heading-sm | 22px | 1.2 | -0.22px | `--text-heading-sm` |
| heading | 24px | 1 | -0.48px | `--text-heading` |
| heading-lg | 38px | 1.3 | -0.38px | `--text-heading-lg` |
| display | 64px | 0.9 | -1.28px | `--text-display` |

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
| 48 | 48px | `--spacing-48` |
| 56 | 56px | `--spacing-56` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 88 | 88px | `--spacing-88` |
| 112 | 112px | `--spacing-112` |
| 160 | 160px | `--spacing-160` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 40px |
| cards | 24px |
| buttons | 16px |
| smallElements | 8px |
| inlineElements | 12px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| md | `rgba(255, 255, 255, 0.16) 4px 4px 16px -4px inset, rgba(0...` | `--shadow-md` |
| md-2 | `rgba(38, 113, 217, 0.08) 0px 0px 12px 0px inset, rgba(0, ...` | `--shadow-md-2` |

### Layout

- **Section gap:** 40px
- **Card padding:** 16px
- **Element gap:** 16px

## Components

### Primary Filled Button
**Role:** Call to action button for primary user flows.

Background: Iris Pop (#1c6cff), Text: Platinum Ghost (#ffffff), Border Radius: 16px, Padding: 12px vertical, 16px horizontal. Font: Jokker Medium, 12px, 500 weight.

### Ghost Button
**Role:** Secondary action or navigation link.

Background: transparent, Text: Platinum Ghost (#ffffff), Border: 1px solid Ocean Glimmer (#597caa), Border Radius: 16px, Padding: 12px vertical, 16px horizontal. Font: Jokker Medium, 12px, 500 weight.

### Floating Content Card
**Role:** Displaying featured content or information blocks.

Background: Midnight Ink (#000814), Border Radius: 20px, Shadow: rgba(0, 0, 0, 0.07) 0px 0.36px 0.65px -1.5px, rgba(0, 0, 0, 0.05) 0px 3px 5.4px -3px, Padding: 14px vertical, 0px horizontal.

### Vibrant Category Tag
**Role:** Categorization of items, dynamically colored.

Background: Dynamic vivid color (e.g., Cherry Blossom #ff33aa, Pumpkin Zest #f27f0c), Text: Platinum Ghost (#ffffff), Border Radius: 40px (pill-shaped), Padding: 16px vertical, 24px-32px horizontal. Shadow: rgba(255, 255, 255, 0.16) inset 0px 24px 64px -12px, rgba(0, 0, 0, 0.16) inset 0px -24px 40px -12px, plus multiple inset highlights.

### Navigation Link
**Role:** Primary navigation elements in header or footer.

Text: Platinum Ghost (#ffffff) for active/hover, Ocean Glimmer (#597caa) for inactive. Font: Matte Variable Thin, 14px, 100 weight.

### Message Banner
**Role:** Alerts or promotional messages at the top of the page.

Background: Indigo Wash (#00215e), Text: Platinum Ghost (#ffffff), Border Radius: 0px. Padding: 5px vertical, 10px horizontal. Font: sans-serif, 12px, 400 weight.

## Do's and Don'ts

### Do
- Prioritize Midnight Ink (#000814) or Deep Space (#010d1e) for all background canvases and card surfaces to maintain the dark theme.
- Use Platinum Ghost (#ffffff) for all primary body and headline text to ensure legibility and brand consistency.
- Apply Iris Pop (#1c6cff) exclusively for primary calls to action to create clear interaction points.
- Implement a 16px border-radius for all interactive elements like buttons and primary inputs.
- Use Matter Variable Thin with precise letter-spacing adjustments for headlines to achieve a light, modern typographic presence.
- Incorporate vibrant accent colors like Teal Glow (#00cc4b) or Crimson Beam (#ff4433) for category tags and small decorative elements, ensuring they stand out against the dark background.
- Employ inset shadows (like rgba(255, 255, 255, 0.16) inset) on vibrant tags and cards to give elements a subtle, glowing depth.
- Maintain an element gap of 16px (4 units) and card padding of 16px for consistent visual rhythm and content separation.

### Don't
- Avoid using light backgrounds for primary content areas; maintain the dark theme's integrity.
- Do not introduce new saturated primary colors; limit vibrant accents to the established palette of Teal Glow, Crimson Beam, Iris Pop, etc.
- Do not use sharp 0px corners on any card-like or interactive UI elements; maintain soft radii (16px, 20px, 24px, 40px).
- Avoid heavy drop shadows; prefer the subtle, inset shadow styles or minimal elevation visible in the system.
- Do not use generic system fonts in place of Matter Variable Thin or Jokker; preserve the distinctive brand typography.
- Do not create dense, text-heavy blocks without sufficient padding or line height; ensure ample white space for readability within the dark context.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas | `#000814` | Primary page background, base for all content. |
| 1 | Base Surface | `#010d1` | Slightly elevated backgrounds, subtle background differences within sections. |
| 2 | Interactive Card | `#000814` | Container for featured content, distinguished by soft shadows and rounded corners. |
| 3 | Vibrant Tag Surface | `#ff33aa` | Dynamic, colored containers for categorization, featuring prominent inset shadows and rounded forms. |

## Elevation

- **Floating Content Card:** `rgba(0, 0, 0, 0.07) 0px 0.362176px 0.651917px -1.5px, rgba(0, 0, 0, 0.05) 0px 3px 5.4px -3px`
- **Vibrant Category Tag:** `rgba(255, 255, 255, 0.16) 0px 24px 64px -12px inset, rgba(0, 0, 0, 0.16) 0px -24px 40px -12px inset, rgba(255, 255, 255, 0.16) 0px 0.636953px 1.14652px -0.5px inset, rgba(255, 255, 255, 0.17) 0px 1.9316px 3.47689px -1px inset, rgba(255, 255, 255, 0.19) 0px 5.10612px 9.19102px -1.5px inset, rgba(255, 255, 255, 0.24) 0px 16px 28.8px -2px inset`

## Imagery

The visual language focuses on abstract, illustrative 'tag' elements rendered with soft glows and a shallow depth of field, positioned against a dark, minimalist UI. These tags are color-varied, featuring clear and vivid hues like #00cc4b, #ff4433, #9019e6, and #fece4c. Icons are outlines, rendered in white against the dark background, maintaining a clean and functional appearance. Photography is notably absent, with the visual emphasis placed entirely on UI elements and stylized graphic accents. The density of these visuals is moderate, allowing them to serve as engaging focal points without overwhelming the sparse textual information. There are product screenshots of UI embedded in devices that are presented flat, consistent with the minimal aesthetic. These serve to showcase product functionality in context.

## Layout

The page primarily uses a full-bleed structure for its dark background, combined with a contained maximum width for core content, which appears centered. The hero section features a large, centered headline overlaid with dynamically arranged, glowing 'tag' elements, creating an immediate sense of activity and organization. Sections are separated by consistent vertical spacing, and there's a pattern of presenting information in centered stacks or simple text-aligned-left compositions with a strong visual element on the right (though not strongly represented in the provided screenshots, suggested by the 'money organized' layout). The navigation is a sticky top bar, minimal and un-intrusive, designed to blend into the overall dark theme, with a primary call to action in the top right. Content density is generally spacious, allowing elements to breathe on the dark canvas.

## Agent Prompt Guide

Quick Color Reference:
text: #ffffff
background: #000814
border: #11263b
accent: #00cc4b
primary action: #1c6cff (filled action)

Example Component Prompts:
1. Create a Primary Filled Button: background #1c6cff, text #ffffff, 16px radius, 12px 16px padding. Text 'Get started' using Jokker Medium, 12px, 500 weight.
2. Create a Vibrant Category Tag for 'Groceries': background #ff4433, text #ffffff, 40px radius, 16px 32px padding, with the specified inset shadow stack. Text 'GROCERIES' using Matter Variable Thin, 14px, 100 weight.
3. Create a Navigation Link for 'Pricing': text Ocean Glimmer (#597caa), 0px radius, 4px vertical 8px horizontal padding. Text 'Pricing' using Matter Variable Thin, 14px, 100 weight.
4. Create a Floating Content Card: background Midnight Ink (#000814), 20px radius, 14px vertical 0px horizontal padding, with the specified rgba(0,0,0) shadow. Content text: Platinum Ghost (#ffffff).

## Similar Brands

- **Linear** — Dark UI, focus on functional minimalism, and subtle yet impactful typography.
- **Amie** — Structured dark mode with vibrant accent colors for interactive elements and an emphasis on clean layouts.
- **Raycast** — Command-line aesthetic integrated into a modern UI, featuring deep dark backgrounds and clear, crisp text.
- **Notion (dark mode)** — Spacious content areas within a dark theme, using subtle elevation and muted text for hierarchy.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #000814;
  --color-deep-space: #010d1e;
  --color-obsidian: #11263b;
  --color-mist-gray: #ccced0;
  --color-shadow-blue: #29303a;
  --color-deep-shadow: #303741;
  --color-muted-stone: #7f8ba4;
  --color-platinum-ghost: #ffffff;
  --color-teal-glow: #00cc4b;
  --color-crimson-beam: #ff4433;
  --color-cosmic-blue: #426088;
  --color-ocean-glimmer: #597caa;
  --color-iris-pop: #1c6cff;
  --color-sunbeam: #fece4c;
  --color-amethyst-flare: #9019e6;
  --color-slate-blue: #5c6f8a;
  --color-cherry-blossom: #ff33aa;
  --color-pumpkin-zest: #f27f0c;
  --color-golden-harvest: #ff9900;
  --color-lime-soda: #59cc33;
  --color-indigo-wash: #00215e;
  --color-blue-gradient-overlay: #5b7395;
  --gradient-blue-gradient-overlay: linear-gradient(5deg, rgba(91, 115, 149, 0.8) 10%, rgb(223, 228, 237) 90%);

  /* Typography — Font Families */
  --font-matter-variable-thin: 'Matter Variable Thin', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-jokker-medium: 'Jokker Medium', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-matter-trial-semibold: 'Matter-TRIAL SemiBold', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-jokker-semibold: 'Jokker Semibold', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-jokker-regular: 'Jokker Regular', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.2;
  --tracking-caption: 0.22px;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: -0.22px;
  --text-heading: 24px;
  --leading-heading: 1;
  --tracking-heading: -0.48px;
  --text-heading-lg: 38px;
  --leading-heading-lg: 1.3;
  --tracking-heading-lg: -0.38px;
  --text-display: 64px;
  --leading-display: 0.9;
  --tracking-display: -1.28px;

  /* Typography — Weights */
  --font-weight-thin: 100;
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-w670: 670;

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
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-88: 88px;
  --spacing-112: 112px;
  --spacing-160: 160px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 16px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;
  --radius-3xl-3: 40px;
  --radius-full: 48px;
  --radius-full-2: 80px;
  --radius-full-3: 120px;

  /* Named Radii */
  --radius-tags: 40px;
  --radius-cards: 24px;
  --radius-buttons: 16px;
  --radius-smallelements: 8px;
  --radius-inlineelements: 12px;

  /* Shadows */
  --shadow-md: rgba(255, 255, 255, 0.16) 4px 4px 16px -4px inset, rgba(0, 0, 0, 0.2) -4px -4px 16px -4px inset, rgba(255, 255, 255, 0.08) 4px 4px 8px 0px inset, rgba(255, 255, 255, 0.4) 1px 1px 1px -0.5px inset;
  --shadow-md-2: rgba(38, 113, 217, 0.08) 0px 0px 12px 0px inset, rgba(0, 0, 0, 0.32) 0px -4px 8px 0px inset;

  /* Surfaces */
  --surface-canvas: #000814;
  --surface-base-surface: #010d1;
  --surface-interactive-card: #000814;
  --surface-vibrant-tag-surface: #ff33aa;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #000814;
  --color-deep-space: #010d1e;
  --color-obsidian: #11263b;
  --color-mist-gray: #ccced0;
  --color-shadow-blue: #29303a;
  --color-deep-shadow: #303741;
  --color-muted-stone: #7f8ba4;
  --color-platinum-ghost: #ffffff;
  --color-teal-glow: #00cc4b;
  --color-crimson-beam: #ff4433;
  --color-cosmic-blue: #426088;
  --color-ocean-glimmer: #597caa;
  --color-iris-pop: #1c6cff;
  --color-sunbeam: #fece4c;
  --color-amethyst-flare: #9019e6;
  --color-slate-blue: #5c6f8a;
  --color-cherry-blossom: #ff33aa;
  --color-pumpkin-zest: #f27f0c;
  --color-golden-harvest: #ff9900;
  --color-lime-soda: #59cc33;
  --color-indigo-wash: #00215e;
  --color-blue-gradient-overlay: #5b7395;

  /* Typography */
  --font-matter-variable-thin: 'Matter Variable Thin', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-jokker-medium: 'Jokker Medium', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-matter-trial-semibold: 'Matter-TRIAL SemiBold', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-jokker-semibold: 'Jokker Semibold', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-jokker-regular: 'Jokker Regular', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.2;
  --tracking-caption: 0.22px;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: -0.22px;
  --text-heading: 24px;
  --leading-heading: 1;
  --tracking-heading: -0.48px;
  --text-heading-lg: 38px;
  --leading-heading-lg: 1.3;
  --tracking-heading-lg: -0.38px;
  --text-display: 64px;
  --leading-display: 0.9;
  --tracking-display: -1.28px;

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
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-88: 88px;
  --spacing-112: 112px;
  --spacing-160: 160px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;
  --radius-3xl-3: 40px;
  --radius-full: 48px;
  --radius-full-2: 80px;
  --radius-full-3: 120px;

  /* Shadows */
  --shadow-md: rgba(255, 255, 255, 0.16) 4px 4px 16px -4px inset, rgba(0, 0, 0, 0.2) -4px -4px 16px -4px inset, rgba(255, 255, 255, 0.08) 4px 4px 8px 0px inset, rgba(255, 255, 255, 0.4) 1px 1px 1px -0.5px inset;
  --shadow-md-2: rgba(38, 113, 217, 0.08) 0px 0px 12px 0px inset, rgba(0, 0, 0, 0.32) 0px -4px 8px 0px inset;
}
```

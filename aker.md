# Aker — Style Reference
> Subdued cinematic vista

**Theme:** dark

Aker employs a dark, contemplative aesthetic, juxtaposing crisp typography and subtle surface variations against immersive background imagery. The interface relies on translucent overlays and restrained neutrals, with hints of muted earth tones and a singular vivid orange for accent. This creates an atmosphere of grounded aspiration, where content breathes within structured, visually rich sections without feeling heavy or overly stark.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Absolute Black | `#000000` | `--color-absolute-black` | Page backgrounds, primary text on light surfaces, borders, icon fills. The foundational dark neutral |
| Pure White | `#ffffff` | `--color-pure-white` | Primary text on dark surfaces, crucial borders, icon strokes. Provides stark contrast against dark elements |
| Deep Graphite | `#070707` | `--color-deep-graphite` | Elevated card backgrounds, subtle surface variations within dark areas |
| Medium Gray | `#1c1c1c` | `--color-medium-gray` | Secondary background and border elements within dark contexts, particularly for dividing sections or highlighting subtle changes in plane |
| Fog | `#e5e4e4` | `--color-fog` | Light background areas on predominantly light sections, subtle borders and dividers |
| Slate Border | `#8d8d8d` | `--color-slate-border` | Dividers and subtle borders on darker backgrounds for content separation, secondary text on light backgrounds |
| Soft Stone | `#494949` | `--color-soft-stone` | Neutral button backgrounds, low-prominence interactive elements, adds a touch of warm gray |
| Moss Green | `#193f32` | `--color-moss-green` | Thematic background accents, specialized link highlights, or subtly branded surfaces |
| Desert Orange | `#b75928` | `--color-desert-orange` | Orange action color for filled buttons, selected navigation states, and focused conversion moments |
| Deep Teal | `#002934` | `--color-deep-teal` | Dark, muted background for specific content blocks, deeper branding elements |
| Copper Clay | `#776157` | `--color-copper-clay` | Warm, earthy card backgrounds, adding a subtle organic feel to content blocks |
| Crimson Blush | `#df6a6b` | `--color-crimson-blush` | Red wash for highlight backgrounds, decorative bands, and soft emphasis behind content. Use as a supporting accent, not as a status color |
| Deep Ocean | `#044152` | `--color-deep-ocean` | Muted blue accent for backgrounds or decorative elements, appears rarely |

## Tokens — Typography

### Proxima Nova — Primary typeface for all UI elements, headings, and most body text. The range of weights and granular sizes supports a flexible hierarchy from subtle details to dominant headlines. Light letter-spacing in larger sizes helps maintain a sophisticated feel, while tighter spacing for smaller text ensures readability. · `--font-proxima-nova`
- **Substitute:** system-ui
- **Weights:** 300, 400, 500, 600
- **Sizes:** 8px, 12px, 13px, 14px, 15px, 16px, 18px, 20px, 22px, 30px, 36px, 62px, 80px, 168px
- **Line height:** 0.80, 0.95, 1.00, 1.10, 1.20, 1.25, 1.30, 1.50
- **Letter spacing:** -0.0250em, -0.0200em, 0.0100em
- **Role:** Primary typeface for all UI elements, headings, and most body text. The range of weights and granular sizes supports a flexible hierarchy from subtle details to dominant headlines. Light letter-spacing in larger sizes helps maintain a sophisticated feel, while tighter spacing for smaller text ensures readability.

### Lora — Used for longer-form body copy, supporting text, or specific content blocks where a serif adds an editorial, authoritative tone. Its slightly wider letter-spacing improves readability for extended reading. · `--font-lora`
- **Substitute:** serif
- **Weights:** 400
- **Sizes:** 15px, 18px
- **Line height:** 1.35, 1.50
- **Letter spacing:** 0.0110em
- **Role:** Used for longer-form body copy, supporting text, or specific content blocks where a serif adds an editorial, authoritative tone. Its slightly wider letter-spacing improves readability for extended reading.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body | 15px | 1.5 | 0.011px | `--text-body` |
| body-lg | 18px | 1.35 | 0.011px | `--text-body-lg` |
| subheading | 20px | 1.3 | — | `--text-subheading` |
| heading | 30px | 1.25 | — | `--text-heading` |
| heading-lg | 62px | 1 | -0.025px | `--text-heading-lg` |
| display | 168px | 0.8 | -0.02px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 5 | 5px | `--spacing-5` |
| 6 | 6px | `--spacing-6` |
| 8 | 8px | `--spacing-8` |
| 10 | 10px | `--spacing-10` |
| 12 | 12px | `--spacing-12` |
| 13 | 13px | `--spacing-13` |
| 14 | 14px | `--spacing-14` |
| 16 | 16px | `--spacing-16` |
| 19 | 19px | `--spacing-19` |
| 20 | 20px | `--spacing-20` |
| 22 | 22px | `--spacing-22` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |

### Border Radius

| Element | Value |
|---------|-------|
| badges | 1584px |
| buttons | 80px |
| default | 8px |
| roundElements | 160px |

### Layout

- **Section gap:** 64px
- **Card padding:** 10-16px
- **Element gap:** 8-16px

## Components

### Translucent Dark Button
**Role:** Secondary action button on dark backgrounds.

backgroundColor=rgba(255, 255, 255, 0.2), color=rgb(0, 0, 0), borderRadius=80px, padding=12.8px. Text is black, background is a subtle white transparency.

### Ghost Button (Dark Text)
**Role:** Subtle interactive element on light or mixed backgrounds.

backgroundColor=rgba(0, 0, 0, 0), color=rgb(0, 0, 0), borderTopColor=rgb(0, 0, 0), borderRadius=160px, padding=19.2px 22.4px. Transparent with a black border and text.

### Ghost Button (Light Text)
**Role:** Subtle interactive element on dark backgrounds.

backgroundColor=rgba(0, 0, 0, 0), color=rgb(255, 255, 255), borderTopColor=rgb(255, 255, 255), borderRadius=160px, padding=19.2px 22.4px. Transparent with a white border and text.

### Overlay Content Card
**Role:** Informational cards appearing over video or imagery.

backgroundColor=rgba(0, 0, 0, 0.5) or rgba(0, 0, 0, 0.6), borderRadius=8px. Transparent dark background with no padding, allowing content to bleed to edges.

### Earthy Accent Card
**Role:** Thematic content blocks with a distinct background hue.

backgroundColor=rgb(119, 97, 87), borderRadius=8px, padding=9.6px 16px. Uses a muted copper clay color.

### Corner Radius Content Card (White)
**Role:** Content card with attention-grabbing top rounded corners, typically for introductory sections.

backgroundColor=rgb(255, 255, 255), borderRadius=8px 8px 0px 0px. Pure white with no internal padding.

### Rounded Neutral Badge
**Role:** Categorization or short status labels.

backgroundColor=rgb(249, 248, 248), color=rgb(0, 0, 0), borderRadius=1584px, padding=6.4px 14.4px. Nearly white background with black text, extremely rounded.

## Do's and Don'ts

### Do
- Prioritize Absolute Black (#000000) for page backgrounds or Deep Graphite (#070707) for elevated cards.
- Use Proxima Nova for all headings and UI text, adjusting weight and size for hierarchy, with specific letter-spacing for large text.
- Apply Purr White (#ffffff) text on dark backgrounds and Absolute Black (#000000) on light backgrounds for maximum contrast.
- Maintain a default border-radius of 8px for cards and general rectangular elements, using 80px or 160px for pill-shaped buttons.
- Incorporate Desert Orange (#b75928) sparingly as a functional accent for interactive elements or visual cues.
- Maintain a comfortable density with element gaps ranging from 8-16px and section gaps around 64px.
- Use Lora for extended body text, ensuring a slightly wider letter-spacing of 0.0110em for readability.

### Don't
- Avoid using multiple vivid accent colors; restrict chromatic accents primarily to Desert Orange (#b75928).
- Do not introduce heavy drop shadows or strong elevation effects; rely on subtle background shifts and borders to define hierarchy.
- Do not deviate from Proxima Nova or Lora; avoid introducing other typefaces.
- Avoid arbitrary border radii; stick to 8px for rectangular elements and the highly rounded 80px/160px for buttons/badges.
- Do not clutter layouts; maintain spacious sections with consistent vertical rhythm.
- Avoid primary action buttons with dark or transparent backgrounds; if a filled button is needed, use Soft Stone (#494949) or another relevant chromatic accent.
- Do not use generic, unrounded buttons; all buttons should have either 80px or 160px border-radius, creating a pill shape.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas | `#000000` | Primary page background, a deep dark base for content. |
| 1 | Card Base | `#070707` | A slightly lighter dark surface for primary content cards, providing modest separation from the canvas. |
| 2 | Translucent Overlay | `#00000080` | Semi-transparent dark overlays for cards or content blocks sitting over imagery or video, allowing background context to show through. |
| 3 | Accent Card | `#776157` | Distinctively colored cards for thematic content, standing out from the primary dark surfaces. |

## Imagery

The site employs a blend of high-quality, atmospheric photography and detailed product shots. Photography often features outdoor environments, rendered in a subdued, cinematic style with lens flares or natural light, providing a sense of place and aspiration without being overtly busy. Product shots and illustrations are clean, functional, and often feature architecture or community layouts, maintaining a professional but lifestyle-oriented feel. Icons are typically minimalist, outlined, and monochromatic, usually Pure White on dark backgrounds, blending seamlessly into the UI.

## Layout

The page primarily uses a full-bleed layout for its hero section, often featuring immersive video or photography. Subsequent sections alternate between full-width blocks and content contained within an implied max-width, offering visual breathing room. Content arrangement frequently uses a text-left/image-right pattern or centered text stacks within defined content zones. There's a comfortable vertical rhythm between sections, often defined by distinct background colors or full-bleed imagery shifts. Navigation is handled by a minimal top-right hamburger menu.

## Agent Prompt Guide

Quick Color Reference:
text: #ffffff
background: #000000
border: #8d8d8d
accent: #b75928
primary action: #494949 (filled action)

Example Component Prompts:
1. Create an 'Overlay Content Card' with the headline 'The Creative' (Proxima Nova, 22px, weight 600, #ffffff) and body text (Proxima Nova, 16px, weight 400, #ffffff), against a background of rgba(0, 0, 0, 0.5) and 8px border-radius. Include a 'Ghost Button (Light Text)' at the bottom with text 'Learn More' and 160px border-radius.
2. Create a Primary Action Button: #494949 background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
3. Implement a 'Pill-shaped Button' with a Soft Stone (#494949) background, Pure White (#ffffff) text (Proxima Nova, 16px, weight 500), and a 160px border-radius, with 19.2px vertical and 22.4px horizontal padding.

## Motion Philosophy

The site favors subtle and expressive transitions. Durations are typically between 0.2s and 0.35s, with a preference for 'ease' and 'cubic-bezier(0.165, 0.84, 0.44, 1)' timing functions. Key properties like opacity, border-radius, color, and transform are animated, contributing to a fluid but unhurried user experience.

## Similar Brands

- **Figma** — Extensive use of dark/light modes, precise typography, and a strong grid system.
- **Linear** — Dark UI with thoughtful spacing, sophisticated typography, and minimal use of accent colors.
- **Space Ape Games** — Full-bleed hero imagery combined with dark, structured content blocks and crisp typography.
- **Blinkist** — Clear, readable typography usage for both headings and long-form content, with a thoughtful dark mode.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-absolute-black: #000000;
  --color-pure-white: #ffffff;
  --color-deep-graphite: #070707;
  --color-medium-gray: #1c1c1c;
  --color-fog: #e5e4e4;
  --color-slate-border: #8d8d8d;
  --color-soft-stone: #494949;
  --color-moss-green: #193f32;
  --color-desert-orange: #b75928;
  --color-deep-teal: #002934;
  --color-copper-clay: #776157;
  --color-crimson-blush: #df6a6b;
  --color-deep-ocean: #044152;

  /* Typography — Font Families */
  --font-proxima-nova: 'Proxima Nova', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-lora: 'Lora', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 15px;
  --leading-body: 1.5;
  --tracking-body: 0.011px;
  --text-body-lg: 18px;
  --leading-body-lg: 1.35;
  --tracking-body-lg: 0.011px;
  --text-subheading: 20px;
  --leading-subheading: 1.3;
  --text-heading: 30px;
  --leading-heading: 1.25;
  --text-heading-lg: 62px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -0.025px;
  --text-display: 168px;
  --leading-display: 0.8;
  --tracking-display: -0.02px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-13: 13px;
  --spacing-14: 14px;
  --spacing-16: 16px;
  --spacing-19: 19px;
  --spacing-20: 20px;
  --spacing-22: 22px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-64: 64px;

  /* Layout */
  --section-gap: 64px;
  --card-padding: 10-16px;
  --element-gap: 8-16px;

  /* Border Radius */
  --radius-md: 3.2px;
  --radius-lg: 8px;
  --radius-full: 80px;
  --radius-full-2: 160px;
  --radius-full-3: 800px;
  --radius-full-4: 1584px;

  /* Named Radii */
  --radius-badges: 1584px;
  --radius-buttons: 80px;
  --radius-default: 8px;
  --radius-roundelements: 160px;

  /* Surfaces */
  --surface-canvas: #000000;
  --surface-card-base: #070707;
  --surface-translucent-overlay: #00000080;
  --surface-accent-card: #776157;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-absolute-black: #000000;
  --color-pure-white: #ffffff;
  --color-deep-graphite: #070707;
  --color-medium-gray: #1c1c1c;
  --color-fog: #e5e4e4;
  --color-slate-border: #8d8d8d;
  --color-soft-stone: #494949;
  --color-moss-green: #193f32;
  --color-desert-orange: #b75928;
  --color-deep-teal: #002934;
  --color-copper-clay: #776157;
  --color-crimson-blush: #df6a6b;
  --color-deep-ocean: #044152;

  /* Typography */
  --font-proxima-nova: 'Proxima Nova', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-lora: 'Lora', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 15px;
  --leading-body: 1.5;
  --tracking-body: 0.011px;
  --text-body-lg: 18px;
  --leading-body-lg: 1.35;
  --tracking-body-lg: 0.011px;
  --text-subheading: 20px;
  --leading-subheading: 1.3;
  --text-heading: 30px;
  --leading-heading: 1.25;
  --text-heading-lg: 62px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -0.025px;
  --text-display: 168px;
  --leading-display: 0.8;
  --tracking-display: -0.02px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-13: 13px;
  --spacing-14: 14px;
  --spacing-16: 16px;
  --spacing-19: 19px;
  --spacing-20: 20px;
  --spacing-22: 22px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-64: 64px;

  /* Border Radius */
  --radius-md: 3.2px;
  --radius-lg: 8px;
  --radius-full: 80px;
  --radius-full-2: 160px;
  --radius-full-3: 800px;
  --radius-full-4: 1584px;
}
```

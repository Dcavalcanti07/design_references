# Codex.io — Style Reference
> Electric green on midnight grid

**Theme:** dark

Codex employs a high-contrast dark environment with sharp, technical aesthetics, punctuated by a vivid, electric green. The design favors strong geometric forms, minimal ornamentation, and clear functional hierarchy. High-impact typography and subtle achromatic surfaces create a sense of focused power, while the bright green serves as a direct, energetic accent for interactive elements and brand identifiers. This system is designed for clarity and efficiency.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#111111` | `--color-midnight-ink` | Primary background for dark sections, text on the electric green accent. This deep black provides a stark, unyielding canvas |
| Electric Lime | `#e5ff5d` | `--color-electric-lime` | Primary action color for buttons, interactive elements, icons, and brand highlights. Its vivid saturation provides a jolt of energy against the dark and light neutrals |
| Ghost Ash | `#f9f9f9` | `--color-ghost-ash` | Primary text color against dark backgrounds, light section backgrounds, and default card surfaces. Its near-white hue ensures readability |
| Deep Graphite | `#2b2b2b` | `--color-deep-graphite` | Secondary background color for navigation and subtle elevated surfaces in dark mode. Provides a slight visual separation from the Midnight Ink |
| Muted Stone | `#b7b3a2` | `--color-muted-stone` | Subtle surface color, decorative fills, and occasional background elements. Its warm gray adds a touch of organic texture |
| Light Grayscale | `#eeeeee` | `--color-light-grayscale` | Tertiary background color for very light sections, offering a softer white alternative to Ghost Ash |
| Shadow Ink | `#000000` | `--color-shadow-ink` | Used for some icon fills and input borders, a true black provides absolute contrast when needed |
| Subtle Gray | `#d6d6d6` | `--color-subtle-gray` | Hairline borders for cards and other elements, creating faint separation |
| Midtone Gray | `#6e6e6e` | `--color-midtone-gray` | Used for some card backgrounds, deeper than Subtle Gray but lighter than Deep Graphite |
| Silver Mist | `#9c9c9c` | `--color-silver-mist` | Secondary text color for less prominent information, and some subtle borders |
| Dark Frost | `#222222` | `--color-dark-frost` | Used for specific navigation text and button borders, slightly lighter than Midnight Ink |
| Slate Border | `#565656` | `--color-slate-border` | Dark borders and separators for elevated surfaces and inverted UI. Do not promote it to the primary CTA color |

## Tokens — Typography

### Neue Haas Grotesk Text — The primary typeface for all content. Its precise, neutral geometry supports the technical nature of the brand. Varied letter-spacing across sizes gives headlines a tight, impactful feel, while body text remains comfortably legible. · `--font-neue-haas-grotesk-text`
- **Substitute:** Helvetica Neue
- **Weights:** 400, 500
- **Sizes:** 10px, 12px, 16px, 20px, 24px, 80px
- **Line height:** 0.90, 1.00, 1.20, 1.30, 1.50, 1.73, 2.08
- **Letter spacing:** -0.01, 0.02, 0.027, 0.032
- **Role:** The primary typeface for all content. Its precise, neutral geometry supports the technical nature of the brand. Varied letter-spacing across sizes gives headlines a tight, impactful feel, while body text remains comfortably legible.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.73 | 0.032px | `--text-caption` |
| body | 16px | 1.5 | 0.02px | `--text-body` |
| subheading | 20px | 1.3 | 0.02px | `--text-subheading` |
| heading | 24px | 1.2 | 0.02px | `--text-heading` |
| display | 80px | 0.9 | -0.01px | `--text-display` |

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
| 80 | 80px | `--spacing-80` |
| 96 | 96px | `--spacing-96` |
| 128 | 128px | `--spacing-128` |
| 144 | 144px | `--spacing-144` |
| 192 | 192px | `--spacing-192` |

### Border Radius

| Element | Value |
|---------|-------|
| nav | 4px |
| cards | 12px |
| buttons | 4px |
| decorative | 20px |

### Layout

- **Page max-width:** 1200px
- **Section gap:** 48px
- **Card padding:** 32px
- **Element gap:** 16px

## Components

### Primary Action Button - Filled
**Role:** Calls to action and key interactive elements.

Background: Electric Lime (#e5ff5d), Text: Midnight Ink (#111111), Border Radius: 4px, Padding: 12px vertical, 16px horizontal. Creates immediate visual emphasis.

### Secondary Action Button - Ghost
**Role:** Less prominent actions, often next to a primary button.

Background: Midnight Ink (#111111), Text: Electric Lime (#e5ff5d), Border Color: Electric Lime (#e5ff5d), Border Radius: 4px, Padding: 0px (implied by content spacing). Provides a subtle contrast without overwhelming the primary action.

### Navigation Link
**Role:** Main navigation items and secondary links.

Text color: Ghost Ash (#f9f9f9) on dark backgrounds, Dark Frost (#222222) on light backgrounds. No background or border. Tight letter spacing at 12px size. Underlined on hover.

### Default Card
**Role:** Content grouping, feature display, or information containers.

Background: rgba(249, 249, 249, 0.4) for light sections, rgba(0, 0, 0, 0) for dark sections. Border Radius: 12px, Padding: 32px vertical, 32px horizontal. Subtle translucency on light themes.

### Minimal Card
**Role:** Small information blocks, often in grids.

Background: rgba(0, 0, 0, 0), Borders: None, Border Radius: 0px. Text color: Ghost Ash (#f9f9f9). Relies on layout for separation.

### Large Feature Card
**Role:** Prominent feature callouts requiring more visual weight.

Background: rgba(249, 249, 249, 0.4), Border Radius: 20px, Padding: 64px vertical, 48px horizontal. Uses a larger radius and padding for more substantial content.

### Form Input
**Role:** User input fields.

Background: transparent, Text: Ghost Ash (#f9f9f9), Focus Border: Electric Lime (#e5ff5d), Default Border: Shadow Ink (#000000), Border Radius: 0px. Minimalist and functional.

## Do's and Don'ts

### Do
- Always use Midnight Ink (#111111) for page backgrounds in dark sections to maintain depth.
- Highlight primary actions and key brand elements exclusively with Electric Lime (#e5ff5d).
- Apply a 4px border-radius to all interactive buttons for a consistent, subtle softening.
- Maintain tight letter-spacing for headlines (-0.01em at 80px) to enhance visual density and impact.
- Ensure all text is either Ghost Ash (#f9f9f9) on dark backgrounds or Midnight Ink (#111111) on light backgrounds for maximum contrast.
- Utilize 16px as the primary elementGap for consistent vertical and horizontal rhythm between components.
- Use 12px border-radius for all cards, with larger 20px radius for more prominent cards.

### Don't
- Do not introduce new chromatic colors; restrict accents to Electric Lime (#e5ff5d).
- Avoid using drop shadows for elevation; rely on background color changes or borders for visual hierarchy.
- Do not deviate from the Neue Haas Grotesk Text font family for any text elements.
- Do not use generic gray buttons; buttons should either be Electric Lime filled or Ghost/Outlined with Electric Lime.
- Avoid excessive spacing; maintain a comfortable density with element gaps typically at 16px and section gaps at 48px.
- Do not use large, decorative imagery; stick to minimalist icons, product UI elements, or abstract graphics.
- Do not use transparent backgrounds randomly; surfaces should typically be Midnight Ink, Deep Graphite, Ghost Ash, or a muted variant for cards.

## Imagery

This system features a minimalist visual language for imagery. It primarily uses abstract 3D geometric shapes (cubes, amorphous blobs) rendered with a glowing, slightly translucent, electric lime green material. These serve a decorative, atmospheric role rather than explanatory. Icons are minimal, either outlined or filled in achromatic tones, with the Electric Lime reserved for active states or branding. Imagery density is low, with visuals serving as accents around prominent typography and UI rather than dominating the layout.

## Layout

The page primarily uses a max-width 1200px contained layout, centered on the screen. The hero section is full-bleed black with a large, centered headline and a prominent Electric Lime call-to-action. Content sections alternate between dark (Midnight Ink) and light (Light Grayscale or Ghost Ash) backgrounds, creating a clear visual rhythm. Within sections, content often uses a two-column text-left/visual-right pattern or centered stacked blocks. Card grids are present for features, typically with uniform spacing. Navigation is a sticky top bar with minimal links and a prominent 'Get Started' button. The overall density is comfortable, with clear vertical separation between sections.

## Agent Prompt Guide

Quick Color Reference:
text: #f9f9f9
background: #111111
border: #d6d6d6
accent: #e5ff5d
primary action: #e5ff5d (filled action)

Example Component Prompts:
1. Create a Hero headline: 'POWER YOUR APP' in Neue Haas Grotesk Text, 80px, weight 500, #f9f9f9, letter-spacing -0.01em.
2. Create a Primary Action Button: 'GET STARTED' with background #e5ff5d, text #111111, border-radius 4px, Neue Haas Grotesk Text 16px, weight 500, padding 12px 16px.
3. Create a Ghost Navigation Link: 'PRODUCT' in Neue Haas Grotesk Text, 12px, weight 400, #f9f9f9, letter-spacing 0.027em, no background or border.
4. Create a Default Card: background rgba(249, 249, 249, 0.4), border-radius 12px, padding 32px, containing a heading (Neue Haas Grotesk Text, 24px, weight 500, #111111) and body text (Neue Haas Grotesk Text, 16px, weight 400, #111111).

## Similar Brands

- **Stripe** — Uses a similar approach of clean typography, strong technical aesthetic, and strategic use of a single vivid accent color against a largely monochromatic palette.
- **Alchemy** — Blockchain developer tools, often featuring dark mode UIs with high contrast, angular graphics, and a single neon accent color (often green or purple).
- **Linear** — Focus on high-density information display rendered with precise typography and a strong dark mode aesthetic, though Linear uses subtle color washes rather than a single vibrant accent.
- **Polygon** — Another blockchain brand which uses deep dark backgrounds, often black, paired with bright, glowing visual elements and clear, bold typography for a tech-forward feel.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #111111;
  --color-electric-lime: #e5ff5d;
  --color-ghost-ash: #f9f9f9;
  --color-deep-graphite: #2b2b2b;
  --color-muted-stone: #b7b3a2;
  --color-light-grayscale: #eeeeee;
  --color-shadow-ink: #000000;
  --color-subtle-gray: #d6d6d6;
  --color-midtone-gray: #6e6e6e;
  --color-silver-mist: #9c9c9c;
  --color-dark-frost: #222222;
  --color-slate-border: #565656;

  /* Typography — Font Families */
  --font-neue-haas-grotesk-text: 'Neue Haas Grotesk Text', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.73;
  --tracking-caption: 0.032px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: 0.02px;
  --text-subheading: 20px;
  --leading-subheading: 1.3;
  --tracking-subheading: 0.02px;
  --text-heading: 24px;
  --leading-heading: 1.2;
  --tracking-heading: 0.02px;
  --text-display: 80px;
  --leading-display: 0.9;
  --tracking-display: -0.01px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-128: 128px;
  --spacing-144: 144px;
  --spacing-192: 192px;

  /* Layout */
  --page-max-width: 1200px;
  --section-gap: 48px;
  --card-padding: 32px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 20px;
  --radius-full: 1440px;

  /* Named Radii */
  --radius-nav: 4px;
  --radius-cards: 12px;
  --radius-buttons: 4px;
  --radius-decorative: 20px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #111111;
  --color-electric-lime: #e5ff5d;
  --color-ghost-ash: #f9f9f9;
  --color-deep-graphite: #2b2b2b;
  --color-muted-stone: #b7b3a2;
  --color-light-grayscale: #eeeeee;
  --color-shadow-ink: #000000;
  --color-subtle-gray: #d6d6d6;
  --color-midtone-gray: #6e6e6e;
  --color-silver-mist: #9c9c9c;
  --color-dark-frost: #222222;
  --color-slate-border: #565656;

  /* Typography */
  --font-neue-haas-grotesk-text: 'Neue Haas Grotesk Text', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.73;
  --tracking-caption: 0.032px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: 0.02px;
  --text-subheading: 20px;
  --leading-subheading: 1.3;
  --tracking-subheading: 0.02px;
  --text-heading: 24px;
  --leading-heading: 1.2;
  --tracking-heading: 0.02px;
  --text-display: 80px;
  --leading-display: 0.9;
  --tracking-display: -0.01px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-128: 128px;
  --spacing-144: 144px;
  --spacing-192: 192px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 20px;
  --radius-full: 1440px;
}
```

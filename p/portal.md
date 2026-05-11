# Portal — Style Reference
> Midnight command center, glowing violet portals.

**Theme:** dark

Portal's design system evokes a dark, futuristic command center. Deep, muted charcoals and near-black surfaces create an immersive backdrop, punctuated by a vibrant purple accent that highlights key actions and interactive elements. Typography is compact and precise, maintaining readability against the dark theme. Components are low-profile with subtle elevation, favoring soft inner glows and refined borders over heavy shadows, contributing to a dense yet breathable information display.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Void Black | `#000000` | `--color-void-black` | Primary page background, prominent card surfaces |
| Twilight Ink | `#0f0f13` | `--color-twilight-ink` | Secondary card backgrounds, subtly lifted UI layers, subtle borders |
| Graphite Border | `#292929` | `--color-graphite-border` | Default borders and dividers for UI elements |
| Dark Indigo | `#2a2a36` | `--color-dark-indigo` | Footer background and its internal borders |
| Off-White Text | `#e6e6e6` | `--color-off-white-text` | Primary text color for body paragraphs and most UI elements |
| Muted Silver | `#9e9e9e` | `--color-muted-silver` | Secondary text, descriptive elements, and helper text for content |
| Pure White | `#ffffff` | `--color-pure-white` | Heading text, high-contrast UI elements, and filled button text |
| Portal Violet | `#b296f8` | `--color-portal-violet` | Primary action background, active navigation states, interactive elements, icons, and hero section accents — creating focal points |
| Violet Shadow | `#241e32` | `--color-violet-shadow` | Subtle shadow tint for elevated cards, giving them a violet-tinged glow |
| Lavender Mist | `#dbeafe` | `--color-lavender-mist` | Text color for info badges |
| Mint Glaze | `#dcfce7` | `--color-mint-glaze` | Text color for success badges |
| Pale Mauve | `#ede9fe` | `--color-pale-mauve` | Text color for other badges, adding variety to status indicators |
| Deep Space Fade | `linear-gradient(rgb(35, 31, 47), rgb(23, 21, 27) 50%, rgb(20, 20, 20))` | `--color-deep-space-fade` | Background gradient for various sections, emphasizing depth |
| Nebula Glow | `radial-gradient(120% 90% at 50% 8%, rgba(195, 181, 255, 0.2), rgba(0, 0, 0, 0) 58%)` | `--color-nebula-glow` | Radial glow effect for hero sections, drawing attention to central elements |

## Tokens — Typography

### Suisse Intl — Primary typeface for all headings, body text, and UI elements. Its slightly condensed and structured form contributes to the 'command center' feel, especially at high weights for emphasis and lighter weights for dense information. · `--font-suisse-intl`
- **Substitute:** Inter
- **Weights:** 400, 500, 600, 900
- **Sizes:** 12px, 14px, 16px, 18px, 36px, 48px, 72px
- **Line height:** 1.00, 1.11, 1.33, 1.43, 1.50, 1.56
- **Letter spacing:** -0.025em at 72px, 0.05em at 12px, 0.2em at 12px
- **Role:** Primary typeface for all headings, body text, and UI elements. Its slightly condensed and structured form contributes to the 'command center' feel, especially at high weights for emphasis and lighter weights for dense information.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.5 | 0.6px | `--text-caption` |
| body-sm | 14px | 1.43 | — | `--text-body-sm` |
| body | 16px | 1.5 | — | `--text-body` |
| subheading | 18px | 1.56 | — | `--text-subheading` |
| heading | 36px | 1.33 | — | `--text-heading` |
| heading-lg | 48px | 1.11 | -1.2px | `--text-heading-lg` |
| display | 72px | 1 | -1.8px | `--text-display` |

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
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 96 | 96px | `--spacing-96` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 10px |
| badges | 0px |
| buttons | 10px |
| default | 10px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| xl | `rgba(178, 150, 248, 0.2) 0px 25px 50px -12px` | `--shadow-xl` |
| subtle | `rgba(0, 0, 0, 0.05) 0px 1px 2px 0px` | `--shadow-subtle` |

### Layout

- **Section gap:** 48px
- **Card padding:** 16px
- **Element gap:** 16px

## Components

### Filled Violet Button
**Role:** Primary call to action.

Solid Portal Violet background (#b296f8), Pure White text (#ffffff), 10px border radius, 16px horizontal padding. Prominently guides users to key actions.

### Outline Ghost Button
**Role:** Secondary action or subtle navigation.

Transparent background, Portal Violet text (#b296f8), 1px solid Graphite Border (#292929), 10px border radius, 16px horizontal padding. Appears as a less assertive action than the filled button.

### Subtle Action Button
**Role:** Tertiary action or minor interactive elements, often within larger components.

Semi-transparent dark background (rgba(41, 41, 41, 0.3)), Pure White text (#ffffff), 1px solid Graphite Border (#292929), 10px border radius. Minimal visual weight for less critical interactions.

### Padded Elevated Card
**Role:** Content container for features or articles, providing visual separation and emphasis.

Twilight Ink background (#0f0f13), 10px border radius. Features a soft, violet-tinted shadow (rgba(178, 150, 248, 0.2) 0px 25px 50px -12px) for elevation. Padding: 16px vertical, 0px horizontal.

### Transparent Content Card
**Role:** Containers for imagery or specific content blocks, integrated seamlessly into the background.

Transparent background, 0px border radius, no shadow. Padding: 0px.

### Badge (Info)
**Role:** Categorization or status indicator.

Semi-transparent blue background (rgba(59, 130, 246, 0.1)), Lavender Mist text (#dbeafe), 0px border radius, 2px vertical and 8px horizontal padding.

### Badge (Success)
**Role:** Positive status indicator.

Semi-transparent green background (rgba(34, 197, 94, 0.1)), Mint Glaze text (#dcfce7), 0px border radius, 2px vertical and 8px horizontal padding.

### Badge (Neutral Text)
**Role:** General label or tag without semantic color.

Transparent background, Pale Mauve text (#ede9fe), 0px border radius, 2px vertical and 8px horizontal padding.

## Do's and Don'ts

### Do
- Use Void Black (#000000) as the primary page background and for card surfaces where maximum contrast is desired.
- Apply Portal Violet (#b296f8) for all primary calls to action, active navigation states, and key interactive elements to create a consistent focal point.
- Structure major content sections with a default vertical spacing of 48px to maintain an airy feel.
- Utilize Suisse Intl with a weight of 900 for all main headings (36px, 48px, 72px) to convey authority.
- Apply a 10px border radius consistently to all cards, buttons, and primary interactive elements.
- Emphasize cards with the subtle violet-tinted shadow (rgba(178, 150, 248, 0.2) 0px 25px 50px -12px) to suggest elevation.
- Use Off-White Text (#e6e6e6) for all primary body text and UI text against dark backgrounds.

### Don't
- Do not use highly saturated colors for backgrounds or large areas; reserve strong chromaticity for accents only.
- Avoid generic drop shadows; instead, apply the violet-tinted shadow for elevated cards to maintain brand aesthetic.
- Do not use pixel-perfect borders on badges; they should have 0px border radius to contrast with cards and buttons.
- Do not vary letter-spacing significantly for body text; a tight tracking is reserved for display headings.
- Do not introduce light mode elements; the entire system is designed around a dark theme.
- Avoid using multiple distinct accent colors; Portal Violet (#b296f8) is the singular bright accent.
- Do not rely solely on border for button distinction; use solid fills for primary actions and outline/ghost for secondary.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Void Black Canvas | `#000000` | Base background for the entire application, and high-DURABILITY cards. |
| 1 | Twilight Ink Panel | `#0f0f13` | Main background for elevated cards and UI components, providing a subtle lift from the canvas. |
| 2 | Gradient Backdrop | `#231f2f` | Decorative base for sections, adding depth with a subtle linear gradient from dark tones. |

## Imagery

This system primarily uses highly stylized, dark-toned digital illustrations with a sci-fi/fantasy aesthetic. Imagery often features glowing, ethereal elements (like portals or energy streams) and detailed, character-focused scenes, often with a cyberpunk or futuristic theme. These are used decoratively as atmospheric backgrounds, full-bleed hero visuals, and within card components to explain concepts or represent themes. Icons are primarily monochromatic outlines with moderate stroke weight, occasionally filled with the brand violet for emphasis. The density of imagery is high, often occupying significant visual space to set a mood rather than just explain content.

## Layout

The page uses a maximum content width centered layout, though the hero section is full-bleed, extending the visual experience edge-to-edge. The hero features a large, central illustrative element with a headline overlaid. Subsequent sections alternate between full-bleed dark gradient backgrounds and contained content blocks, creating a consistent vertical rhythm. Content is arranged in flexible grid systems (e.g., 3-column card grids) and alternating text-left/image-right patterns. The overall density feels balanced, with adequate breathing room between components and sections. Navigation is via a sticky top bar with a logo, primary links, and a prominent violet-filled button.

## Agent Prompt Guide

Quick Color Reference:
text: #e6e6e6
background: #000000
border: #292929
accent: #b296f8
primary action: #b296f8 (filled action)

Example Component Prompts:
1. Create a Hero Section: Void Black background (#000000) with a Nebula Glow effect (radial-gradient(120% 90% at 50% 8%, rgba(195, 181, 255, 0.2), rgba(0, 0, 0, 0) 58%)). Headline at 72px Suisse Intl weight 900, Pure White text (#ffffff), letter-spacing -1.8px. Include a Filled Violet Button ('Explore Products') at 10px radius, 16px horizontal padding.
2. Create a Padded Elevated Card: Twilight Ink background (#0f0f13), 10px radius, shadow rgba(178, 150, 248, 0.2) 0px 25px 50px -12px, 16px vertical padding. Use Suisse Intl 18px weight 600 for the title, Pure White text (#ffffff), and Suisse Intl 14px weight 400 for body text, Off-White Text (#e6e6e6).
3. Create a Navigation Bar: Dark Indigo (#2a2a36) background. Links use Suisse Intl 16px weight 500, Off-White Text (#e6e6e6). Include an Outline Ghost Button ('Contact') using Portal Violet (#b296f8) text, 1px solid Graphite Border (#292929) and 10px radius.

## Similar Brands

- **Razer** — Dark-themed UI with a single vibrant accent color (green for Razer, violet for Portal) used for interactivity and brand recognition.
- **CD Projekt Red (Cyberpunk 2077 game sites)** — Heavy reliance on stylized, futuristic illustrations and dark canvases to establish atmosphere and showcase a tech-forward or dystopian aesthetic.
- **Amplitude** — Information-dense UI with compact typography and subtle, elevated cards against dark backgrounds, using color strategically for emphasis.
- **Linear** — Precise, low-profile components, minimal shadows, and a focus on subtle color cues to denote status and interactivity within a compact interface.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-void-black: #000000;
  --color-twilight-ink: #0f0f13;
  --color-graphite-border: #292929;
  --color-dark-indigo: #2a2a36;
  --color-off-white-text: #e6e6e6;
  --color-muted-silver: #9e9e9e;
  --color-pure-white: #ffffff;
  --color-portal-violet: #b296f8;
  --color-violet-shadow: #241e32;
  --color-lavender-mist: #dbeafe;
  --color-mint-glaze: #dcfce7;
  --color-pale-mauve: #ede9fe;
  --color-deep-space-fade: #231f2f;
  --gradient-deep-space-fade: linear-gradient(rgb(35, 31, 47), rgb(23, 21, 27) 50%, rgb(20, 20, 20));
  --color-nebula-glow: #c3b5ff;
  --gradient-nebula-glow: radial-gradient(120% 90% at 50% 8%, rgba(195, 181, 255, 0.2), rgba(0, 0, 0, 0) 58%);

  /* Typography — Font Families */
  --font-suisse-intl: 'Suisse Intl', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: 0.6px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.43;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.56;
  --text-heading: 36px;
  --leading-heading: 1.33;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.11;
  --tracking-heading-lg: -1.2px;
  --text-display: 72px;
  --leading-display: 1;
  --tracking-display: -1.8px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-black: 900;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-96: 96px;

  /* Layout */
  --section-gap: 48px;
  --card-padding: 16px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-lg: 10px;

  /* Named Radii */
  --radius-cards: 10px;
  --radius-badges: 0px;
  --radius-buttons: 10px;
  --radius-default: 10px;

  /* Shadows */
  --shadow-xl: rgba(178, 150, 248, 0.2) 0px 25px 50px -12px;
  --shadow-subtle: rgba(0, 0, 0, 0.05) 0px 1px 2px 0px;

  /* Surfaces */
  --surface-void-black-canvas: #000000;
  --surface-twilight-ink-panel: #0f0f13;
  --surface-gradient-backdrop: #231f2f;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-void-black: #000000;
  --color-twilight-ink: #0f0f13;
  --color-graphite-border: #292929;
  --color-dark-indigo: #2a2a36;
  --color-off-white-text: #e6e6e6;
  --color-muted-silver: #9e9e9e;
  --color-pure-white: #ffffff;
  --color-portal-violet: #b296f8;
  --color-violet-shadow: #241e32;
  --color-lavender-mist: #dbeafe;
  --color-mint-glaze: #dcfce7;
  --color-pale-mauve: #ede9fe;
  --color-deep-space-fade: #231f2f;
  --color-nebula-glow: #c3b5ff;

  /* Typography */
  --font-suisse-intl: 'Suisse Intl', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: 0.6px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.43;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.56;
  --text-heading: 36px;
  --leading-heading: 1.33;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.11;
  --tracking-heading-lg: -1.2px;
  --text-display: 72px;
  --leading-display: 1;
  --tracking-display: -1.8px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-96: 96px;

  /* Border Radius */
  --radius-lg: 10px;

  /* Shadows */
  --shadow-xl: rgba(178, 150, 248, 0.2) 0px 25px 50px -12px;
  --shadow-subtle: rgba(0, 0, 0, 0.05) 0px 1px 2px 0px;
}
```

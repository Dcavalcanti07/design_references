# ThoughtLab — Style Reference
> Midnight Command Center

**Theme:** dark

ThoughtLab's design system evokes a dark, cerebral command center. Bold typography punches through deep black backgrounds, while a singular vibrant red accent highlights critical calls-to-action. The spatial experience is generous, allowing components to breathe within wide page margins, contributing to an atmosphere of focused, high-stakes digital experience.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Black | `#000000` | `--color-midnight-black` | Page backgrounds, button text, icon fills |
| Stone Grey | `#4c4c4c` | `--color-stone-grey` | Muted body text, subtle link borders |
| Ghost White | `#cccccc` | `--color-ghost-white` | Medium-contrast borders, control outlines, and structural separators. Do not promote it to the primary CTA color |
| Snow Drift | `#ffffff` | `--color-snow-drift` | Header links, occasionally used as an elevated background color for content sections contrasting the dark base |
| Action Red | `#fc1c46` | `--color-action-red` | Primary call-to-action buttons – a forceful, vivid accent against dark surfaces |

## Tokens — Typography

### sui — Captures a versatile brand voice, ranging from expansive, large-scale headlines to functional body text across various digital experiences. The tighter letter spacing on larger sizes adds to the brand's sharp, modern feel. · `--font-sui`
- **Substitute:** Arial, Helvetica, sans-serif
- **Weights:** 300, 400, 500, 700
- **Sizes:** 10px, 14px, 15px, 17px, 18px, 27px, 72px, 91px, 198px
- **Line height:** 0.92, 0.96, 1.00, 1.10, 1.15, 1.20, 1.25, 1.50, 2.14
- **Letter spacing:** -0.0670em, -0.0200em, -0.0090em
- **Role:** Captures a versatile brand voice, ranging from expansive, large-scale headlines to functional body text across various digital experiences. The tighter letter spacing on larger sizes adds to the brand's sharp, modern feel.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.5 | -0.009px | `--text-caption` |
| body-sm | 14px | 1.25 | -0.009px | `--text-body-sm` |
| subheading | 18px | 1.2 | -0.02px | `--text-subheading` |
| heading | 27px | 1.15 | -0.02px | `--text-heading` |
| heading-lg | 72px | 0.96 | -0.067px | `--text-heading-lg` |
| display | 198px | 0.92 | -0.067px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** spacious

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 7 | 7px | `--spacing-7` |
| 9 | 9px | `--spacing-9` |
| 22 | 22px | `--spacing-22` |
| 29 | 29px | `--spacing-29` |
| 30 | 30px | `--spacing-30` |
| 36 | 36px | `--spacing-36` |
| 43 | 43px | `--spacing-43` |
| 65 | 65px | `--spacing-65` |
| 72 | 72px | `--spacing-72` |
| 86 | 86px | `--spacing-86` |
| 108 | 108px | `--spacing-108` |
| 126 | 126px | `--spacing-126` |
| 180 | 180px | `--spacing-180` |
| 198 | 198px | `--spacing-198` |
| 216 | 216px | `--spacing-216` |

### Border Radius

| Element | Value |
|---------|-------|
| buttons | 9999px |

### Layout

- **Section gap:** 65px
- **Card padding:** 22px
- **Element gap:** 9px

## Components

### Primary Action Button
**Role:** Main call-to-action.

Filled with Action Red (#fc1c46), using Snow Drift (#ffffff) text, with a full pill radius of 9999px. Padding is 0px top/bottom and 30px left/right. Text uses sui font.

### Ghost Nav Link
**Role:** Header and navigation links.

Transparent background, Midnight Black (#000000) text. No border or radius. Padding is 0px. Text is sui font.

### Text Input
**Role:** Standard input fields.

Transparent background, Snow Drift (#ffffff) text and border. No radius. Padding is 7.2px top/bottom and 21.6px left/right. Uses sui font.

### Content Card
**Role:** Information grouping.

Transparent background, no border, no shadow, and no radius. Padding is 0. Content within it typically leverages standard text and link styles.

## Do's and Don'ts

### Do
- Use Midnight Black (#000000) as the primary background color for all main sections and canvases.
- Apply Action Red (#fc1c46) exclusively for primary action buttons, ensuring a visible contrast and clear hierarchy.
- Implement the sui font family with a letter-spacing of -0.0670em for all 'display' and 'heading-lg' roles to maintain a tight, impactful visual.
- Utilize a full pill radius of 9999px for all buttons to reinforce a consistent, distinctive shape.
- Maintain generous vertical spacing between sections, defaulting to 65px as a section gap to create an open and spacious feel.
- Employ Ghost White (#cccccc) for primary text elements against dark backgrounds.
- Employ transparent cards with no visible borders or shadows to maintain flat product surfaces.

### Don't
- Do not use accent colors for descriptive text or non-interactive elements; reserve them for direct action.
- Avoid applying heavy shadows or complex elevation to components, as the system favors a flat, minimalist aesthetic.
- Do not vary border radii across buttons; all interactive buttons should adhere to the 9999px pill shape.
- Do not use letter-spacing on small body text unless explicitly defined in the type scale to avoid readability issues.
- Do not introduce additional bold text weights beyond 700; the system relies on lighter weights for authority.
- Avoid adding unnecessary decorative borders or fills to cards; they should maintain a transparent, subtle presence.
- Do not use tight spatial arrangements; ensure all elements have sufficient breathing room guided by the 9px element gap.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Primary Canvas | `#000000` | Dominant background for the entire application, creating a deep, dark environment. |
| 1 | Subtle Surface | `#cccccc` | Used for content backgrounds or subtle visual breaks within the dark canvas, maintaining high contrast. |
| 2 | Elevated Surface | `#ffffff` | Occasional background for sections or components that require higher visual prominence against a subtly lighter backdrop, or as a direct contrast to the Midnight Black. |

## Imagery

The imagery primarily features abstract, organic 3D rendered forms with luminous, iridescent edges, positioned centrally as a visual anchor. These graphics are contained and serve a decorative, atmospheric role rather than explanatory content. There are minimal other images; the focus is on UI and text, making the 3D element a powerful, singular visual statement.

## Layout

The page employs a full-bleed dark background with a max-width content container, likely around 1200px, but it's not explicitly fixed, allowing for flexibility. The hero section is full-bleed, featuring large, centered headlines over an abstract 3D graphic. Content beneath the hero generally follows a spacious, centered vertical stack with generous section gaps. The navigation is a minimalist top bar with a clear 'Contact Us' primary action button on the right and a hamburger menu icon.

## Agent Prompt Guide

Quick Color Reference:
text: #cccccc
background: #000000
border: #cccccc
accent: #fc1c46
primary action: #fc1c46 (filled action)

Example Component Prompts:
Create a hero section: background Midnight Black (#000000). Headline at 198px sui weight 700, Ghost White (#cccccc), letter-spacing -0.0670em. Subtext at 18px sui weight 500, Stone Grey (#4c4c4c), letter-spacing -0.0200em.
Create a Primary Action Button: Action Red (#fc1c46) background, Snow Drift (#ffffff) text, 9999px radius, padding 0px top/bottom and 30px left/right. Text 'Get Started' sui font weight 500.
Create a Ghost Nav Link: transparent background, Midnight Black (#000000) text, no border or radius, 0px padding. Text 'About Us' sui font weight 400.
Create a Text Input: transparent background, Snow Drift (#ffffff) text, Snow Drift (#ffffff) border, no radius. Padding 7.2px top/bottom and 21.6px left/right. Font sui, placeholder 'Your Email'.

## Similar Brands

- **Stripe** — Shares a sophisticated dark mode UI, minimalist aesthetic, and heavy reliance on strong typography combined with subtle, high-quality visual elements.
- **Linear** — Features a dark interface with a single vibrant accent color to highlight interactive elements and status, often using spacious layouts.
- **Framer** — Employs an editorial layout reminiscent of design portfolios, with large typography, dark backgrounds, and strategically placed visual accents.
- **Supabase** — Uses dark backgrounds, stark typography, and a distinct single-color accent for branding and interactive states.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-black: #000000;
  --color-stone-grey: #4c4c4c;
  --color-ghost-white: #cccccc;
  --color-snow-drift: #ffffff;
  --color-action-red: #fc1c46;

  /* Typography — Font Families */
  --font-sui: 'sui', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --tracking-caption: -0.009px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.25;
  --tracking-body-sm: -0.009px;
  --text-subheading: 18px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.02px;
  --text-heading: 27px;
  --leading-heading: 1.15;
  --tracking-heading: -0.02px;
  --text-heading-lg: 72px;
  --leading-heading-lg: 0.96;
  --tracking-heading-lg: -0.067px;
  --text-display: 198px;
  --leading-display: 0.92;
  --tracking-display: -0.067px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-7: 7px;
  --spacing-9: 9px;
  --spacing-22: 22px;
  --spacing-29: 29px;
  --spacing-30: 30px;
  --spacing-36: 36px;
  --spacing-43: 43px;
  --spacing-65: 65px;
  --spacing-72: 72px;
  --spacing-86: 86px;
  --spacing-108: 108px;
  --spacing-126: 126px;
  --spacing-180: 180px;
  --spacing-198: 198px;
  --spacing-216: 216px;

  /* Layout */
  --section-gap: 65px;
  --card-padding: 22px;
  --element-gap: 9px;

  /* Border Radius */
  --radius-full: 9999px;

  /* Named Radii */
  --radius-buttons: 9999px;

  /* Surfaces */
  --surface-primary-canvas: #000000;
  --surface-subtle-surface: #cccccc;
  --surface-elevated-surface: #ffffff;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-black: #000000;
  --color-stone-grey: #4c4c4c;
  --color-ghost-white: #cccccc;
  --color-snow-drift: #ffffff;
  --color-action-red: #fc1c46;

  /* Typography */
  --font-sui: 'sui', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --tracking-caption: -0.009px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.25;
  --tracking-body-sm: -0.009px;
  --text-subheading: 18px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.02px;
  --text-heading: 27px;
  --leading-heading: 1.15;
  --tracking-heading: -0.02px;
  --text-heading-lg: 72px;
  --leading-heading-lg: 0.96;
  --tracking-heading-lg: -0.067px;
  --text-display: 198px;
  --leading-display: 0.92;
  --tracking-display: -0.067px;

  /* Spacing */
  --spacing-7: 7px;
  --spacing-9: 9px;
  --spacing-22: 22px;
  --spacing-29: 29px;
  --spacing-30: 30px;
  --spacing-36: 36px;
  --spacing-43: 43px;
  --spacing-65: 65px;
  --spacing-72: 72px;
  --spacing-86: 86px;
  --spacing-108: 108px;
  --spacing-126: 126px;
  --spacing-180: 180px;
  --spacing-198: 198px;
  --spacing-216: 216px;

  /* Border Radius */
  --radius-full: 9999px;
}
```

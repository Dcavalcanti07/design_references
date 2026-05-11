# Getburnt — Style Reference
> monochrome architectural elegance

**Theme:** light

Burnt leverages a high-contrast charcoal and white palette, accented by subtle translucent overlays. Typography combines an elegant serif for impactful headlines with a modern sans-serif for body text, creating a sophisticated yet functional feel. Overall density is relaxed, with ample negative space. Components are lightweight, favoring ghost styles and rounded forms over heavy fills, offering a refined, almost architectural visual identity.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Storm Charcoal | `#1a1a17` | `--color-storm-charcoal` | Primary text, dark surface backgrounds, button fills, strong borders, navigation elements. This dark hue forms the foundation of the site's high contrast |
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, light interactive elements, card surfaces, ghost button borders. Its clean presence creates expansive visual fields |
| Soft Slate | `#5f5f5d` | `--color-soft-slate` | Muted body text, secondary information, supportive borders – providing a softer contrast to the primary dark text |
| Ice Mist | `#ffffff0f` | `--color-ice-mist` | Subtle translucent overlays, lightly tinted backgrounds, visual separation within white spaces |
| Dust Shadow | `#1a1a170a` | `--color-dust-shadow` | Faint dividers, soft background tints, low-prominence borders – providing subtle visual texture |

## Tokens — Typography

### Nyght Serif — Headline text. Its light weight (300) for large sizes creates authority through restraint and elegance, rather than traditional boldness. · `--font-nyght-serif`
- **Substitute:** Playfair Display
- **Weights:** 300
- **Sizes:** 26px, 48px, 62px, 72px
- **Line height:** 1.00, 1.10, 1.20
- **Letter spacing:** -0.72px at 72px, -0.62px at 62px, -0.48px at 48px, -0.26px at 26px
- **Role:** Headline text. Its light weight (300) for large sizes creates authority through restraint and elegance, rather than traditional boldness.

### Switzer — Body text, navigation, button labels, and secondary headings. This sans-serif provides a contemporary and highly legible counterpoint to the serif headlines. · `--font-switzer`
- **Substitute:** Inter
- **Weights:** 400, 500, 600
- **Sizes:** 14px, 15px, 16px, 20px
- **Line height:** 1.50
- **Letter spacing:** 0.48px at 16px, 0.45px at 15px, 0.42px at 14px
- **Role:** Body text, navigation, button labels, and secondary headings. This sans-serif provides a contemporary and highly legible counterpoint to the serif headlines.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 14px | 1.5 | 0.42px | `--text-caption` |
| body | 16px | 1.5 | 0.48px | `--text-body` |
| subheading | 20px | 1.5 | 0.6px | `--text-subheading` |
| heading-sm | 26px | 1.2 | -0.26px | `--text-heading-sm` |
| heading | 48px | 1.1 | -0.48px | `--text-heading` |
| heading-lg | 62px | 1.1 | -0.62px | `--text-heading-lg` |
| display | 72px | 1 | -0.72px | `--text-display` |

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
| 120 | 120px | `--spacing-120` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 0px |
| forms | 6px |
| buttons | 1440px |
| navigation | 1440px |

### Layout

- **Section gap:** 48px
- **Card padding:** 24px
- **Element gap:** 8px

## Components

### Filled Dark Button
**Role:** Primary Call to Action

Solid Storm Charcoal background (#1a1a17), Canvas White text (#ffffff), 1440px full pill radius, with 28px horizontal padding (right side including icon area) and 8px vertical padding. Used for high-emphasis actions.

### Ghost Light Button
**Role:** Secondary Call to Action, Navigation Button

Translucent background (rgba(255, 255, 255, 0.06)), Canvas White text (#ffffff), 1440px full pill radius, with 28px horizontal padding and 8px vertical padding. Used when action needs to be present but not visually dominant.

### Inverse Filled Light Button
**Role:** Special Primary Action

Solid Canvas White background (#ffffff), Storm Charcoal text (#1a1a17), 1440px full pill radius, with 28px horizontal padding (right side including icon area) and 8px vertical padding. Used for primary actions on dark backgrounds where a light button provides strong contrast.

### Feature Teaser Card
**Role:** Informational Display

Transparent background, 0px border radius, no box shadow. Content internal padding varies for visual effect (23.904px horizontal, 31.92px bottom, 0px top). These cards serve as transparent containers for feature content.

### Light Overlay Card
**Role:** Content Grouping

Lightly tinted background (rgba(26, 26, 23, 0.04)), 0px border-radius, no shadow. Used for grouping related content with a subtle visual cue against the canvas.

## Do's and Don'ts

### Do
- Prioritize Nyght Serif weight 300 for all major headlines to maintain the brand's delicate yet authoritative voice.
- Use Storm Charcoal (#1a1a17) for primary text and Canvas White (#ffffff) for backgrounds to ensure high contrast and readability.
- Apply a 1440px border radius to all buttons and navigation elements for a consistent pill shape.
- Maintain comfortable spacing with an 8px base unit; use 48px vertical section gaps and 24px card padding.
- Employ Soft Slate (#5f5f5d) for secondary text and descriptive content to provide hierarchy without harshness.
- Implement Ghost Light Buttons (rgba(255, 255, 255, 0.06) background, #ffffff text) for actions that require presence but not visual dominance.

### Don't
- Avoid using heavy shadows or deep elevation; the system prefers subtle translucent overlays and minimal visual depth.
- Do not introduce highly saturated or vivid colors unless they are a defined brand accent; maintain the monochrome base palette.
- Refrain from using bold or ultra-bold weights for Nyght Serif; the elegant 300 weight is a signature of this system.
- Do not deviate from the 0px border radius for cards, as sharp corners enhance the architectural feel.
- Avoid tight, information-dense layouts; prioritize ample negative space for a luxurious and breathable user experience.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas White | `#ffffff` | Primary page background, providing an expansive, clean base. |
| 1 | Dust Shadow Overlay | `#1a1a170a` | Subtle background tints and soft dividers, creating minimal visual texture and separation. |
| 2 | Storm Charcoal | `#1a1a17` | Primary dark surface, used for footers and hero sections, offering strong contrast to the Canvas White. |

## Imagery

The site uses a mix of evocative, high-quality photography and clean product screenshots. Photography features contextual, slightly muted, somewhat candid scenes (like the strawberry crates), often with warm natural light. Product screenshots are contained within card-like interfaces, featuring minimalist UI elements and clean typography, often with soft gradients or clear glassmorphism effects. Icons are simple, outlined, and monochromatic, aligning with the overall minimalist aesthetic. Imagery serves both decorative atmosphere and explanatory content, illustrating the product's application in real-world scenarios or within its own UI.

## Layout

The page adheres to a max-width contained layout, with content centered. The hero section is a split design, featuring a large Nyght Serif headline and descriptive text on the left, contrasting with a contextual image on the right which can extend full-bleed. Sections are visually distinct with consistent vertical spacing, often alternating between a main Canvas White background and subtle, tinted background panels. Content is arranged in alternating text-left/image-right or vertical stacks when presenting features or benefits. There is a prominent 3-column card grid for displaying feature categories. A sticky top navigation bar with a subtle border provides persistent access to pages and the primary CTA. The layout balances spacious breathing room with clear content presentation.

## Agent Prompt Guide

### Quick Color Reference
- text: #1a1a17
- background: #ffffff
- border: #1a1a17
- accent: no distinct accent color
- primary action: #1a1a17 (filled action)

### 3-5 Example Component Prompts
1. Create a Hero section: Canvas White (#ffffff) background. Left side: headline 'Automate food distribution' in Nyght Serif, 72px, weight 300, Storm Charcoal (#1a1a17), letter-spacing -0.72px. Below, body text 'Deploy AI agents across teams to eliminate manual work and scale without adding headcount.' in Switzer, 16px, weight 400, Soft Slate (#5f5f5d), letter-spacing 0.48px. Include a Filled Dark Button 'Get a demo' (#1a1a17 background, #ffffff text, 1440px radius, 28px left/right padding, 8px top/bottom padding).
2. Create a Navigation Bar: Storm Charcoal (#1a1a17) text for navigation links, 15px Switzer weight 400, letter-spacing 0.45px. Right aligned is a Ghost Light Button 'Get a demo' with rgba(255, 255, 255, 0.06) background, #ffffff text, 1440px radius, 28px left/right padding, 8px top/bottom padding. The overall nav background is Canvas White (#ffffff).
3. Create a Feature Teaser Card: Transparent background, 0px radius. Headline 'Sales + operations' in Switzer, 20px, weight 600, Storm Charcoal (#1a1a17), letter-spacing 0.6px. Body text 'Automation that fuels sales' in Switzer, 14px, weight 400, Soft Slate (#5f5f5d), letter-spacing 0.42px. Content within should use 24px horizontal and 31.92px bottom padding, with 0px top padding.

## Similar Brands

- **Linear** — Monochromatic light mode with subtle color use, elegant serif headlines with thin weights, and extensive use of negative space.
- **Typeform** — Focus on spacious layouts, high contrast typography, and custom serif fonts for branding impact while maintaining a clean, modern aesthetic.
- **Arc Browser** — Minimalist UI, focus on functional aesthetics, and a clean, spacious feel without heavy ornamentation.
- **Stripe** — High-contrast text on clean backgrounds, an emphasis on legibility and clear hierarchy, and a refined brand presence through subtle design choices.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-storm-charcoal: #1a1a17;
  --color-canvas-white: #ffffff;
  --color-soft-slate: #5f5f5d;
  --color-ice-mist: #ffffff0f;
  --color-dust-shadow: #1a1a170a;

  /* Typography — Font Families */
  --font-nyght-serif: 'Nyght Serif', ui-serif, Georgia, Cambria, "Times New Roman", Times, serif;
  --font-switzer: 'Switzer', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.5;
  --tracking-caption: 0.42px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: 0.48px;
  --text-subheading: 20px;
  --leading-subheading: 1.5;
  --tracking-subheading: 0.6px;
  --text-heading-sm: 26px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: -0.26px;
  --text-heading: 48px;
  --leading-heading: 1.1;
  --tracking-heading: -0.48px;
  --text-heading-lg: 62px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.62px;
  --text-display: 72px;
  --leading-display: 1;
  --tracking-display: -0.72px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;

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
  --spacing-120: 120px;

  /* Layout */
  --section-gap: 48px;
  --card-padding: 24px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-full: 1440px;

  /* Named Radii */
  --radius-cards: 0px;
  --radius-forms: 6px;
  --radius-buttons: 1440px;
  --radius-navigation: 1440px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-dust-shadow-overlay: #1a1a170a;
  --surface-storm-charcoal: #1a1a17;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-storm-charcoal: #1a1a17;
  --color-canvas-white: #ffffff;
  --color-soft-slate: #5f5f5d;
  --color-ice-mist: #ffffff0f;
  --color-dust-shadow: #1a1a170a;

  /* Typography */
  --font-nyght-serif: 'Nyght Serif', ui-serif, Georgia, Cambria, "Times New Roman", Times, serif;
  --font-switzer: 'Switzer', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.5;
  --tracking-caption: 0.42px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: 0.48px;
  --text-subheading: 20px;
  --leading-subheading: 1.5;
  --tracking-subheading: 0.6px;
  --text-heading-sm: 26px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: -0.26px;
  --text-heading: 48px;
  --leading-heading: 1.1;
  --tracking-heading: -0.48px;
  --text-heading-lg: 62px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.62px;
  --text-display: 72px;
  --leading-display: 1;
  --tracking-display: -0.72px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-96: 96px;
  --spacing-120: 120px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-full: 1440px;
}
```

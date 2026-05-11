# Luro — Style Reference
> Glowing digital nebula

**Theme:** dark

Luro embraces a dark, expansive interface defined by deep, rich backgrounds and luminous, glowing accents. Primary information is presented with high contrast white typography against these dark canvases, punctuated by a vivid magenta that creates a sense of digital energy and highlights interactive elements. Components often exhibit large, soft radii and pronounced, color-tinted shadows, giving them a distinct 'floating' quality within the dark environment. The overall aesthetic suggests a high-tech, immersive experience focused on product insights.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Void Black | `#10020a` | `--color-void-black` | Page background, primary card surfaces, ghost button background |
| Twilight Raisin | `#1e0313` | `--color-twilight-raisin` | Elevated card backgrounds, distinct surface layers |
| Deep Plum | `#300310` | `--color-deep-plum` | Accent card backgrounds |
| Cloud White | `#ffffff` | `--color-cloud-white` | Primary text, informational text, borders, icons, navigation links |
| Ghostly Gray | `#f2f2f2` | `--color-ghostly-gray` | Subtle stroke accents, decorative SVG elements |
| Luminous Magenta | `#ff0068` | `--color-luminous-magenta` | Red supporting accent for decorative details and low-frequency emphasis. Do not promote it to the primary CTA color |
| Deep Magenta Shadow | `#700130` | `--color-deep-magenta-shadow` | Red supporting accent for decorative details and low-frequency emphasis. Do not promote it to the primary CTA color |

## Tokens — Typography

### Graphik Web — Primary display font for all headings, body text, navigation, and interactive elements. Its substantial weights provide clarity and a modern, technical feel. · `--font-graphik-web`
- **Substitute:** Inter
- **Weights:** 400, 600, 700
- **Sizes:** 14px, 16px, 18px, 28px, 34px, 40px, 51px, 62px, 104px
- **Line height:** 0.95, 1.10, 1.20, 1.25, 1.30, 1.50, 1.65, 2.00
- **Letter spacing:** -1.4px at 104px, -0.96px at 62px, -0.85px at 51px, -0.7px at 40px, -0.58px at 34px, -0.16px at 14px
- **Role:** Primary display font for all headings, body text, navigation, and interactive elements. Its substantial weights provide clarity and a modern, technical feel.

### Graphik Cond Web — Used for specific large, condensed text elements, adding a subtle variant for impactful statements. · `--font-graphik-cond-web`
- **Substitute:** Bebas Neue
- **Weights:** 400
- **Sizes:** 38px
- **Line height:** 1.00
- **Letter spacing:** normal
- **Role:** Used for specific large, condensed text elements, adding a subtle variant for impactful statements.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 14px | 1.65 | -0.16px | `--text-caption` |
| body | 16px | 1.5 | — | `--text-body` |
| subheading | 18px | 1.3 | — | `--text-subheading` |
| heading-sm | 28px | 1.25 | — | `--text-heading-sm` |
| heading | 34px | 1.2 | -0.58px | `--text-heading` |
| heading-lg | 40px | 1.2 | -0.7px | `--text-heading-lg` |
| display-sm | 51px | 1.1 | -0.85px | `--text-display-sm` |
| display-md | 62px | 0.95 | -0.96px | `--text-display-md` |
| display | 104px | 0.95 | -1.4px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** spacious

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 8 | 8px | `--spacing-8` |
| 12 | 12px | `--spacing-12` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 28 | 28px | `--spacing-28` |
| 32 | 32px | `--spacing-32` |
| 36 | 36px | `--spacing-36` |
| 60 | 60px | `--spacing-60` |
| 64 | 64px | `--spacing-64` |
| 68 | 68px | `--spacing-68` |
| 72 | 72px | `--spacing-72` |
| 112 | 112px | `--spacing-112` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 24px |
| buttons | 180px |
| interactive | 18px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| xl | `rgba(255, 0, 104, 0.54) 0px 0px 33px 0px, rgba(255, 0, 10...` | `--shadow-xl` |
| lg | `rgba(255, 0, 104, 0.9) 0px 0px 21px -5px, rgba(255, 0, 10...` | `--shadow-lg` |
| xl-2 | `rgba(255, 0, 104, 0.36) 0px 0px 90px 0px` | `--shadow-xl-2` |

### Layout

- **Section gap:** 55px
- **Card padding:** 32px
- **Element gap:** 15px

## Components

### Ghost Button
**Role:** Primary action button with high contrast text.

Background: Void Black (#10020a), Text: Cloud White (#ffffff), Border Radius: 180px, Padding: 13.6px vertical, 32px horizontal. This button style appears for all critical actions.

### Default Data Card
**Role:** Informational display card within data heavy sections.

Background: Void Black (#10020a), Border Radius: 24px, Shadow: rgba(255, 0, 104, 0.54) 0px 0px 33px 0px, rgba(255, 0, 104, 0.4) 0px 0px 99px -21px, Padding: 32px all sides. Contains charts, tables or general information.

### Prominent Feature Card
**Role:** Elevated highlight card for key features or content blocks.

Background: Twilight Raisin (#1e0313), Border Radius: 24px, Shadow: rgba(255, 0, 104, 0.54) 0px 0px 33px 0px, rgba(255, 0, 104, 0.4) 0px 0px 99px -21px, Padding: 72px vertical, 32px horizontal. Used for standalone feature descriptions.

### Miniature Preview Card
**Role:** Small, functional card for previews or status updates.

Background: Deep Plum (#360518), Border Radius: 18px, Shadow: rgba(255, 0, 104, 0.36) 0px 0px 90px 0px, Padding: 15px vertical, 21px horizontal. Used for compact visual elements like adoption percentage displays.

### Navigation Link
**Role:** Header and footer navigation elements.

Background: transparent (Void Black), Text: Cloud White (#ffffff), typically 14-16px, Graphik Web, weight 400. No explicit padding or border.

## Do's and Don'ts

### Do
- Always use the Luminous Magenta (#ff0068) or its shadow variants (e.g., Deep Magenta Shadow #700130) for glowing effects and primary interactive accents.
- Apply large border radii of 24px for cards and 180px for buttons to maintain high-tech softness.
- Set primary text in Cloud White (#ffffff) against Void Black (#10020a) or Twilight Raisin (#1e0313) backgrounds for maximum contrast and readability.
- Utilize Graphik Web for all headings and body text, varying weights (400, 600, 700) to establish hierarchy.
- Incorporate the signature glowing shadow (rgba(255, 0, 104, 0.54) 0px 0px 33px 0px, rgba(255, 0, 104, 0.4) 0px 0px 99px -21px) on cards and interactive elements for brand consistency.
- Maintain a spacious layout with significant vertical separation between sections, using a base unit of 4px for fine-grained control.

### Don't
- Avoid using light backgrounds, as the system is fundamentally dark-themed.
- Do not introduce sharp corners or small radii; the design relies on soft, rounded edges.
- Refrain from using primary colors other than the Luminous Magenta for core accents or interactive states.
- Do not use generic gray shadows; all elevation should feature the magenta-tinted glow.
- Avoid tight spacing between sections or cards; maintain the generous padding and margins found in the system.
- Do not use system fonts or other typefaces outside of Graphik Web and Graphik Cond Web.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Void Black Canvas | `#10020a` | Primary page background and base surface for most content blocks. |
| 1 | Twilight Raisin Card | `#1e0313` | Slightly elevated card backgrounds, often used for featured content or interactive panels. |
| 2 | Deep Plum Accent | `#360518` | Accent background for smaller, visually distinct cards or components. |

## Elevation

- **Card, Image, Button:** `rgba(255, 0, 104, 0.54) 0px 0px 33px 0px, rgba(255, 0, 104, 0.4) 0px 0px 99px -21px`
- **Image (alt):** `rgba(255, 0, 104, 0.9) 0px 0px 21px -5px, rgba(255, 0, 104, 0.6) 0px 0px 27px -3px`
- **Small Card:** `rgba(255, 0, 104, 0.36) 0px 0px 90px 0px`

## Imagery

The site uses a combination of product screenshots, abstract generative-looking graphics, and simple icons. Product screenshots are typically contained within cards, often featuring a dark UI relevant to the product. Abstract graphics, particularly the glowing orange and magenta lines, are used decoratively to create an energetic, tech-forward atmosphere and delineate sections, often extending into full-bleed hero backgrounds. Icons are minimal, mostly monochrome (white), and used directionally or for brand identification. Imagery serves both decorative and explanatory roles, with a focus on product showcase and creating a dynamic, immersive experience rather than literal photography.

## Layout

The page primarily uses a full-bleed dark background for immersive sections, with content either full-width or contained within a flexible max-width. The hero section is full-bleed, featuring a large, centered headline and subtext, overlaid with abstract glowing graphics. Sections then alternate between dark backgrounds with distinct card groupings (e.g., a multi-column card grid or stacked feature cards) and more content-heavy blocks with graphs and data displays. Vertical spacing between sections is generous. Navigation is a simple top bar with a logo and a single 'Blog' link, remaining minimal to keep focus on the content.

## Agent Prompt Guide

Quick Color Reference: text: #ffffff, background: #10020a, border: #ffffff, accent: #ff0068, primary action: no distinct CTA color

Example Component Prompts:
1. Create a hero section: full-bleed background, headline 'Build and track your design system' at 104px Graphik Web weight 700 Cloud White (#ffffff), letter-spacing -1.4px. Subtext 'Luro is a no-code solution...' at 18px Graphik Web weight 400 Cloud White (#ffffff). Include abstract glowing magenta lines as decorative elements.
2. Design a Ghost Button for 'Join the Luro Discord': Background Void Black (#10020a), Text Cloud White (#ffffff) 16px Graphik Web weight 600, Border Radius 180px, Padding 13.6px vertical, 32px horizontal.
3. Implement a Prominent Feature Card for 'Figma sync': Background Twilight Raisin (#1e0313), Border Radius 24px, Shadow rgba(255, 0, 104, 0.54) 0px 0px 33px 0px, rgba(255, 0, 104, 0.4) 0px 0px 99px -21px. Inside, place a 34px Graphik Web weight 700 Cloud White (#ffffff) title and a 16px Graphik Web weight 400 Cloud White (#ffffff) body text, with 72px vertical and 32px horizontal padding.
4. Construct a Miniature Preview Card: Background Deep Plum (#360518), Border Radius 18px, Shadow rgba(255, 0, 104, 0.36) 0px 0px 90px 0px. Text '91% Design system adoption' in Cloud White (#ffffff) with a 51px Graphik Web weight 700 for '91', and 16px Graphik Web weight 400 for 'Design system adoption'. Padding 15px vertical, 21px horizontal.

## Similar Brands

- **Vercel** — Similar dark-mode UI with high-contrast text and a focus on developer tools; often uses subtle glowing effects.
- **Supabase** — Dark interface, modern typography, and vibrant accent colors (though different hues) to highlight interactive elements and data visualizations.
- **Linear** — High-contrast dark theme, crisp typography, and functional use of accent colors for status and actionable items. Also uses rounded corners prominently.
- **PlanetScale** — Developers-focused brand with a dark theme, strong typography, and a single, vibrant brand color used for accents and interactive components.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-void-black: #10020a;
  --color-twilight-raisin: #1e0313;
  --color-deep-plum: #300310;
  --color-cloud-white: #ffffff;
  --color-ghostly-gray: #f2f2f2;
  --color-luminous-magenta: #ff0068;
  --color-deep-magenta-shadow: #700130;

  /* Typography — Font Families */
  --font-graphik-web: 'Graphik Web', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-graphik-cond-web: 'Graphik Cond Web', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.65;
  --tracking-caption: -0.16px;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.3;
  --text-heading-sm: 28px;
  --leading-heading-sm: 1.25;
  --text-heading: 34px;
  --leading-heading: 1.2;
  --tracking-heading: -0.58px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -0.7px;
  --text-display-sm: 51px;
  --leading-display-sm: 1.1;
  --tracking-display-sm: -0.85px;
  --text-display-md: 62px;
  --leading-display-md: 0.95;
  --tracking-display-md: -0.96px;
  --text-display: 104px;
  --leading-display: 0.95;
  --tracking-display: -1.4px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-68: 68px;
  --spacing-72: 72px;
  --spacing-112: 112px;

  /* Layout */
  --section-gap: 55px;
  --card-padding: 32px;
  --element-gap: 15px;

  /* Border Radius */
  --radius-xl: 12px;
  --radius-2xl: 18px;
  --radius-3xl: 24px;
  --radius-full: 180px;
  --radius-full-2: 1800px;

  /* Named Radii */
  --radius-cards: 24px;
  --radius-buttons: 180px;
  --radius-interactive: 18px;

  /* Shadows */
  --shadow-xl: rgba(255, 0, 104, 0.54) 0px 0px 33px 0px, rgba(255, 0, 104, 0.4) 0px 0px 99px -21px;
  --shadow-lg: rgba(255, 0, 104, 0.9) 0px 0px 21px -5px, rgba(255, 0, 104, 0.6) 0px 0px 27px -3px;
  --shadow-xl-2: rgba(255, 0, 104, 0.36) 0px 0px 90px 0px;

  /* Surfaces */
  --surface-void-black-canvas: #10020a;
  --surface-twilight-raisin-card: #1e0313;
  --surface-deep-plum-accent: #360518;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-void-black: #10020a;
  --color-twilight-raisin: #1e0313;
  --color-deep-plum: #300310;
  --color-cloud-white: #ffffff;
  --color-ghostly-gray: #f2f2f2;
  --color-luminous-magenta: #ff0068;
  --color-deep-magenta-shadow: #700130;

  /* Typography */
  --font-graphik-web: 'Graphik Web', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-graphik-cond-web: 'Graphik Cond Web', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.65;
  --tracking-caption: -0.16px;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.3;
  --text-heading-sm: 28px;
  --leading-heading-sm: 1.25;
  --text-heading: 34px;
  --leading-heading: 1.2;
  --tracking-heading: -0.58px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -0.7px;
  --text-display-sm: 51px;
  --leading-display-sm: 1.1;
  --tracking-display-sm: -0.85px;
  --text-display-md: 62px;
  --leading-display-md: 0.95;
  --tracking-display-md: -0.96px;
  --text-display: 104px;
  --leading-display: 0.95;
  --tracking-display: -1.4px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-68: 68px;
  --spacing-72: 72px;
  --spacing-112: 112px;

  /* Border Radius */
  --radius-xl: 12px;
  --radius-2xl: 18px;
  --radius-3xl: 24px;
  --radius-full: 180px;
  --radius-full-2: 1800px;

  /* Shadows */
  --shadow-xl: rgba(255, 0, 104, 0.54) 0px 0px 33px 0px, rgba(255, 0, 104, 0.4) 0px 0px 99px -21px;
  --shadow-lg: rgba(255, 0, 104, 0.9) 0px 0px 21px -5px, rgba(255, 0, 104, 0.6) 0px 0px 27px -3px;
  --shadow-xl-2: rgba(255, 0, 104, 0.36) 0px 0px 90px 0px;
}
```

# Notion — Style Reference
> Midnight machine hum — a deep indigo backdrop with precise, glowing elements that guide action.

**Theme:** dark

Notion's design system feels like a high-tech control panel, favoring a deep, almost inky blue background that provides a sophisticated setting for its functional UI. A restrained use of bright, vivid accent colors, primarily blues and an array of warm hues, pop against this dark canvas, indicating interactive elements and feature highlights. Typography is crisp and highly legible, with a meticulous approach to letter-spacing that implies precision, while subtly rounded corners on cards and buttons soften the otherwise sharp technical aesthetic.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#02093a` | `--color-midnight-ink` | Primary background for dark sections, elevated card surfaces, and navigation elements. Provides depth as a foundational dark tone. |
| Canvas Dark | `#000000` | `--color-canvas-dark` | Base page background, navigation borders, and primary text on light surfaces. Serves as the darkest neutral in the system. |
| Ghost White | `#f6f5f4` | `--color-ghost-white` | Light background for sections or secondary buttons. Provides contrast against darker neutrals. |
| Paper White | `#ffffff` | `--color-paper-white` | Text on dark backgrounds, interactive elements' text, and card backgrounds in light sections. Acts as the primary light element. |
| Deep Graphite | `#0b0b0b` | `--color-deep-graphite` | Dark text and borders on light surfaces, providing heavier visual weight than standard Canvas Dark. |
| Blue Frost | `#62aef0` | `--color-blue-frost` | Highlight elements, decorative accents, and subtle background fills. Evokes a cool, digital glow. |
| Ocean Glimmer | `#0075de` | `--color-ocean-glimmer` | Interactive link text, borders for ghost buttons, and secondary action calls. A vibrant blue for clarity. |
| Sky Surge | `#097fe8` | `--color-sky-surge` | Informational badges, active navigation states, and subtle decorative fills. Slightly brighter than Ocean Glimmer, for emphasis. |
| Action Indigo | `#455dd3` | `--color-action-indigo` | Primary Call-to-Action button background. A rich, saturated blue that stands out as the main interactive element. |
| Alert Red | `#f77463` | `--color-alert-red` | Observed in heading backgroundColor, other backgroundColor. Semantic/state role was not supported by extracted badge/input evidence. |
| Team Teal | `#2a9d99` | `--color-team-teal` | Accent backgrounds for features or categorization, offering a cool, composed highlight. |
| Sunny Yellow | `#ffc95e` | `--color-sunny-yellow` | Accent backgrounds for highlighting features or new content. A cheerful, bright yellow. |
| Warm Umber | `#b18164` | `--color-warm-umber` | Muted accent background for thematic categorization. Provides an organic contrast. |
| Coral Burst | `#ff8a33` | `--color-coral-burst` | Vibrant accent background for highlights, providing warmth and energy. |
| Fuchsia Flare | `#ff83dd` | `--color-fuchsia-flare` | Playful accent background for special features or decorative elements. |
| Grape Glow | `#ad6ded` | `--color-grape-glow` | Vivid purple accent background for distinct categorization or decorative highlights. |
| Harvest Gold | `#ffb110` | `--color-harvest-gold` | Slightly deeper yellow accent background for secondary emphasis. |
| Hot Chili | `#f64932` | `--color-hot-chili` | Intense red accent background for high-attention elements, more saturated than Alert Red. |
| Forest Green | `#1aae39` | `--color-forest-green` | Vivid green accent background for positive indicators or highlights. |
| Cool Gray | `#c6c6c5` | `--color-cool-gray` | Subtle border and text color for muted details. A soft, light gray. |
| Deep Slate | `#615d59` | `--color-deep-slate` | Muted icon color and secondary text. A dark, slightly desaturated gray. |
| Input Border Gray | `#dddddd` | `--color-input-border-gray` | Border color specifically for input fields. Provides subtle definition. |
| Off White | `#f2f9ff` | `--color-off-white` | Background for informational badges, offering a soft white tint. |

## Tokens — Typography

### NotionInter — The primary workhorse typeface for all UI elements, body text, and most headings. Its varied weights and precise letter-spacing allow for distinct hierarchy and high legibility across all sizes, from tiny labels to prominent headlines. The 'lnum' (lining numerals) feature ensures consistent number alignment in tables and data displays. · `--font-notioninter`
- **Substitute:** Inter
- **Weights:** 400, 500, 600, 700
- **Sizes:** 12px, 14px, 15px, 16px, 20px, 22px, 24px, 26px, 40px, 42px, 54px, 64px
- **Line height:** 0.83, 1.00, 1.04, 1.14, 1.20, 1.23, 1.27, 1.33, 1.35, 1.40, 1.43, 1.50
- **Letter spacing:** -0.036, -0.035, -0.033, -0.024, -0.011, -0.006, 0.01
- **OpenType features:** `"lnum" on, "locl" 0`
- **Role:** The primary workhorse typeface for all UI elements, body text, and most headings. Its varied weights and precise letter-spacing allow for distinct hierarchy and high legibility across all sizes, from tiny labels to prominent headlines. The 'lnum' (lining numerals) feature ensures consistent number alignment in tables and data displays.

### Lyon Text — Used sparingly for specific, stylized headings, potentially for editorial or feature-focused content. Its serif nature offers a tactile, almost printed feel compared to the geometric NotionInter. · `--font-lyon-text`
- **Substitute:** Georgia
- **Weights:** 400
- **Sizes:** 32px
- **Line height:** 1.25
- **Letter spacing:** normal
- **Role:** Used sparingly for specific, stylized headings, potentially for editorial or feature-focused content. Its serif nature offers a tactile, almost printed feel compared to the geometric NotionInter.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.5 | 0.01px | `--text-caption` |
| body-sm | 14px | 1.43 | -0.006px | `--text-body-sm` |
| subheading | 20px | 1.35 | -0.011px | `--text-subheading` |
| heading-sm | 22px | 1.33 | -0.024px | `--text-heading-sm` |
| heading | 26px | 1.27 | -0.033px | `--text-heading` |
| heading-lg | 40px | 1.23 | -0.035px | `--text-heading-lg` |
| display | 64px | 0.83 | -0.036px | `--text-display` |

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
| 36 | 36px | `--spacing-36` |
| 40 | 40px | `--spacing-40` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 180 | 180px | `--spacing-180` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 12px |
| badges | 9999px |
| inputs | 4px |
| buttons | 8px |
| general | 5px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(0, 0, 0, 0.01) 0px 1px 3px 0px, rgba(0, 0, 0, 0.02) ...` | `--shadow-subtle` |

### Layout

- **Section gap:** 32px
- **Card padding:** 24px
- **Element gap:** 8px

## Components

### Primary Action Button
**Role:** Filled Button

Solid background button for primary actions. Uses Action Indigo (#455dd3) as background, Paper White (#ffffff) text (NotionInter, weight 400). Has 8px border-radius and 12px vertical, 16px horizontal padding.

### Ghost Header Navigation Button
**Role:** Ghost Button

Transparent background button for navigation items in the header. Uses Paper White (#ffffff) text (NotionInter, weight 400) and a transparent background. Has an 8px border-radius, with 6px vertical and 15px horizontal padding.

### Feature Card (Dark Background)
**Role:** Card

Card with a deep background for featuring product capabilities. Uses Midnight Ink (#02093a) as background, 12px border-radius, and 24px padding on all sides. No shadow.

### Feature Card (Light Background)
**Role:** Card

Card with a light background for various content blocks. Uses Paper White (#ffffff) as background, 12px border-radius, and 24px padding on all sides. No shadow.

### Ghost Link Button
**Role:** Ghost Button

Outlined button with Ghost White (#f6f5f4) text (NotionInter, weight 400), transparent background, and 4px border-radius. Padding is 5px vertical and 10px horizontal.

### Muted Navigation Button
**Role:** Ghost Button

Subtle ghost button for secondary navigation or actions. Uses Deep Slate (#615d59) text (NotionInter, weight 400), transparent background, and 8px border-radius. Padding is 12px vertical and 16px horizontal.

### White Card (No Padding)
**Role:** Card

A minimalist card variant, ideal for internal UI sections. Uses Paper White (#ffffff) as background, 12px border-radius, and no padding. No shadow.

### Off-White Section Card
**Role:** Card

Card for containing content in light sections, with a subtle off-white background. Uses Ghost White (#f6f5f4) as background, 12px border-radius, and no padding. No shadow.

### Basic Text Input
**Role:** Input

Standard text input field. Uses Paper White (#ffffff) background, transparent text color (Canvas Dark #000000 at 90% opacity), Input Border Gray (#dddddd) border, and 4px border-radius. Padding is 6px on all sides.

### Info Badge
**Role:** Badge

Informational badge. Uses Off White (#f2f9ff) background, Sky Surge (#097fe8) text (NotionInter, weight 400), 9999px radius (pill shape), and 4px vertical, 8px horizontal padding.

## Do's and Don'ts

### Do
- Prioritize NotionInter typeface (#000000 on dark, #ffffff on light) for all body text and UI labels, ensuring consistent letter-spacing from the type scale.
- Use Midnight Ink (#02093a) as the default background for large hero sections and prominent cards in dark mode interfaces.
- Implement Action Indigo (#455dd3) exclusively for primary call-to-action buttons, pairing it with Paper White (#ffffff) text.
- Apply 12px border-radius to all cards and larger container elements, and 8px border-radius for buttons for visual consistency.
- Utilize Ocean Glimmer (#0075de) for all interactive link text and subtle button outlines to indicate interactivity without distraction.
- Maintain a clear visual hierarchy by limiting saturated accent colors (like Alert Red, Team Teal, Sunny Yellow) to small background fills for content categorization or highlights.

### Don't
- Do not use generic gray backgrounds; instead, leverage the nuanced shades of Midnight Ink (#02093a) and Canvas Dark (#000000) for visual depth in dark themes.
- Avoid using multiple vivid colors side-by-side without a clear functional purpose; accents should be deliberate and functional.
- Do not vary letter-spacing for NotionInter text unless it adheres strictly to the defined type scale's specific values for each role.
- Refrain from using Lyon Text for anything other than large, editorial-style headings, to preserve its distinct character.
- Do not introduce new border-radius values; stick to 12px for cards, 8px for buttons, 4px for inputs, and 9999px for pill-shaped elements.
- Avoid generic shadow effects; if elevation is needed, use the explicit box-shadow values provided, or rely on distinct background colors for depth.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas Dark | `#000000` | Base page background, darkest foundational neutral. |
| 1 | Midnight Ink | `#02093a` | Primary background for hero sections and elevated dark cards, offering a rich, deep hue. |
| 2 | Paper White | `#ffffff` | Content cards and sections that stand out as bright focal points against the darker canvas. Also, input backgrounds. |
| 3 | Ghost White | `#f6f5f4` | Subtle background for specific sections or cards, lighter than Paper White but providing a soft contrast with Canvas Dark. |

## Elevation

- **Elevated Component:** `rgba(0, 0, 0, 0.01) 0px 1px 3px 0px, rgba(0, 0, 0, 0.02) 0px 3px 7px 0px, rgba(0, 0, 0, 0.02) 0px 7px 15px 0px, rgba(0, 0, 0, 0.04) 0px 14px 28px 0px, rgba(0, 0, 0, 0.05) 0px 23px 52px 0px`

## Imagery

The visual language is split between functional UI elements and playful, abstract illustrated mascots. Product screenshots are typically contained within a light surface on the dark background, clearly showcasing the UI without heavy styling. Illustrations feature a flat, vector style with organic shapes and bright, vivid brand colors (pinks, blues, yellows, reds, greens) that contrast sharply with the dark UI, serving a decorative and atmospheric role rather than explanatory. Icons follow a filled, colorful style that matches the illustrative assets, adding personality. Density is text-dominant, with imagery used strategically to break up sections and highlight features.

## Layout

The page primarily uses a max-width contained layout, centering content within a defined horizontal space, though the hero section breaks this rule, creating a full-bleed dark backdrop. The hero features a large, centered headline with associated text and call-to-action buttons over a deep indigo background. Sections generally alternate between dark full-bleed bands and contained light or off-white content blocks, creating a distinct visual rhythm. Content within these sections often uses a text-left/image-right or text-over-image pattern, often in 2-column or 3-column grids for feature lists or interactive elements. Spacing between sections is generous, allowing breathing room, and navigation is a persistent top bar (sticky header).

## Agent Prompt Guide

primary action: #ffffff (filled action)
Create a Primary Action Button: #ffffff background, #000000 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.

Example Component Prompts:
Create a feature card: Paper White (#ffffff) background. 12px radius, 24px padding. Headline at 22px NotionInter weight 600, #000000, letter-spacing -0.0240em. Body text at 15px NotionInter weight 400, #0b0b0b, letter-spacing -0.0060em.
Create an informational badge: Off White (#f2f9ff) background. Sky Surge (#097fe8) text at 12px NotionInter weight 400, 9999px radius, 4px 8px padding.

## Similar Brands

- **Linear** — Similar dark-mode UI with highly precise typography, restrained use of accent colors for interaction, and a focus on clean, functional layouts.
- **Figma** — Shares a complex interface design, using a deep but not stark dark background, and employing various shades with intentional pops of color to denote active states or functions.
- **GitHub (Dark Mode)** — Employs a deep dark theme with vivid but controlled accent colors for interactive elements, code highlights, and status indicators, rather than broad colorful areas.
- **Vercel** — Features a dark UI that highlights content with crisp typography and subtle use of blues and grays, with a focus on developer tools and efficiency.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #02093a;
  --color-canvas-dark: #000000;
  --color-ghost-white: #f6f5f4;
  --color-paper-white: #ffffff;
  --color-deep-graphite: #0b0b0b;
  --color-blue-frost: #62aef0;
  --color-ocean-glimmer: #0075de;
  --color-sky-surge: #097fe8;
  --color-action-indigo: #455dd3;
  --color-alert-red: #f77463;
  --color-team-teal: #2a9d99;
  --color-sunny-yellow: #ffc95e;
  --color-warm-umber: #b18164;
  --color-coral-burst: #ff8a33;
  --color-fuchsia-flare: #ff83dd;
  --color-grape-glow: #ad6ded;
  --color-harvest-gold: #ffb110;
  --color-hot-chili: #f64932;
  --color-forest-green: #1aae39;
  --color-cool-gray: #c6c6c5;
  --color-deep-slate: #615d59;
  --color-input-border-gray: #dddddd;
  --color-off-white: #f2f9ff;

  /* Typography — Font Families */
  --font-notioninter: 'NotionInter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-lyon-text: 'Lyon Text', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: 0.01px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.43;
  --tracking-body-sm: -0.006px;
  --text-subheading: 20px;
  --leading-subheading: 1.35;
  --tracking-subheading: -0.011px;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1.33;
  --tracking-heading-sm: -0.024px;
  --text-heading: 26px;
  --leading-heading: 1.27;
  --tracking-heading: -0.033px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.23;
  --tracking-heading-lg: -0.035px;
  --text-display: 64px;
  --leading-display: 0.83;
  --tracking-display: -0.036px;

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
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-180: 180px;

  /* Layout */
  --section-gap: 32px;
  --card-padding: 24px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-md: 5px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-cards: 12px;
  --radius-badges: 9999px;
  --radius-inputs: 4px;
  --radius-buttons: 8px;
  --radius-general: 5px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.01) 0px 1px 3px 0px, rgba(0, 0, 0, 0.02) 0px 3px 7px 0px, rgba(0, 0, 0, 0.02) 0px 7px 15px 0px, rgba(0, 0, 0, 0.04) 0px 14px 28px 0px, rgba(0, 0, 0, 0.05) 0px 23px 52px 0px;

  /* Surfaces */
  --surface-canvas-dark: #000000;
  --surface-midnight-ink: #02093a;
  --surface-paper-white: #ffffff;
  --surface-ghost-white: #f6f5f4;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #02093a;
  --color-canvas-dark: #000000;
  --color-ghost-white: #f6f5f4;
  --color-paper-white: #ffffff;
  --color-deep-graphite: #0b0b0b;
  --color-blue-frost: #62aef0;
  --color-ocean-glimmer: #0075de;
  --color-sky-surge: #097fe8;
  --color-action-indigo: #455dd3;
  --color-alert-red: #f77463;
  --color-team-teal: #2a9d99;
  --color-sunny-yellow: #ffc95e;
  --color-warm-umber: #b18164;
  --color-coral-burst: #ff8a33;
  --color-fuchsia-flare: #ff83dd;
  --color-grape-glow: #ad6ded;
  --color-harvest-gold: #ffb110;
  --color-hot-chili: #f64932;
  --color-forest-green: #1aae39;
  --color-cool-gray: #c6c6c5;
  --color-deep-slate: #615d59;
  --color-input-border-gray: #dddddd;
  --color-off-white: #f2f9ff;

  /* Typography */
  --font-notioninter: 'NotionInter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-lyon-text: 'Lyon Text', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: 0.01px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.43;
  --tracking-body-sm: -0.006px;
  --text-subheading: 20px;
  --leading-subheading: 1.35;
  --tracking-subheading: -0.011px;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1.33;
  --tracking-heading-sm: -0.024px;
  --text-heading: 26px;
  --leading-heading: 1.27;
  --tracking-heading: -0.033px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.23;
  --tracking-heading-lg: -0.035px;
  --text-display: 64px;
  --leading-display: 0.83;
  --tracking-display: -0.036px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-180: 180px;

  /* Border Radius */
  --radius-md: 5px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-full: 9999px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.01) 0px 1px 3px 0px, rgba(0, 0, 0, 0.02) 0px 3px 7px 0px, rgba(0, 0, 0, 0.02) 0px 7px 15px 0px, rgba(0, 0, 0, 0.04) 0px 14px 28px 0px, rgba(0, 0, 0, 0.05) 0px 23px 52px 0px;
}
```

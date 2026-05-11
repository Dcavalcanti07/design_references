# Impilo — Style Reference
> Deep violet command center

**Theme:** dark

Impilo embraces a deep violet, control-room aesthetic with white text as its primary contrast. The system pairs rich, vivid blues and greens with its foundational violet palette, using them as functional accents for data visualization, interactive elements, and icon details. Typography is clean and compact, maintaining a focused energy against the dark, high-tech backdrops. Components are soft-edged with generous radii, suggesting a friendly approach within the structured interface.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Indigo | `#16165c` | `--color-midnight-indigo` | Page backgrounds, card surfaces, secondary interactive borders — the primary dark canvas |
| Ghost Frost | `#f4f4f6` | `--color-ghost-frost` | Soft icon strokes, subtle dividers, and low-emphasis decorative details. Do not promote it to the primary CTA color |
| Bright Blue | `#00b1ff` | `--color-bright-blue` | Highlight accents, data visualizations, active links, functional icons — provides a clear focal point |
| Vivid Green | `#00ffaa` | `--color-vivid-green` | Secondary accents for states, data, and icons — complements the blue for vibrant data representation |
| Action Violet | `#5350cc` | `--color-action-violet` | Primary button fills and interactive elements — a vivid, deep violet for clear calls to action |
| White | `#ffffff` | `--color-white` | Primary text on dark backgrounds, selected button fills — ensures high contrast and legibility |
| Muted Violet | `#b1a6f6` | `--color-muted-violet` | Decorative illustration accents, softer graphical elements — a lighter, more ethereal violet |
| Deep Violet Surface | `#232269` | `--color-deep-violet-surface` | Elevated card backgrounds, deeper container elements, subtle text, and borders — provides depth |
| Rich Violet | `#403cd5` | `--color-rich-violet` | Footer background, decorative geometric fills — a saturated, energetic violet |
| Interactive Violet | `#524fe1` | `--color-interactive-violet` | Violet outline accent for tags, dividers, and focused UI edges. Do not promote it to the primary CTA color |
| Hairline Gray | `#9494a9` | `--color-hairline-gray` | Fine borders, subtle dividers — a neutral, near-gray for structural separation |
| Subtle Gray | `#d8d8e3` | `--color-subtle-gray` | Very faint highlights, secondary text for low contrast on lighter backgrounds |
| Data Teal | `#2ee9ff` | `--color-data-teal` | Data chart lines, secondary data points, specific decorative borders — adds another bright accent |
| Outline Violet | `#4846c6` | `--color-outline-violet` | Card borders and ghost button outlines on dark surfaces — provides definition |

## Tokens — Typography

### Gilroy — Primary typeface for all headings and body text. Its clean, geometric sans-serif forms contribute to the modern-tech aesthetic. Varied letter spacing is used for visual impact at larger display sizes and legibility at smaller text sizes. · `--font-gilroy`
- **Substitute:** system-ui
- **Weights:** 500, 600
- **Sizes:** 12px, 13px, 14px, 17px, 18px, 24px, 46px, 54px, 66px, 92px, 124px
- **Line height:** 0.92, 1.00, 1.44
- **Letter spacing:** -0.075, -0.04, -0.03, 0.02
- **Role:** Primary typeface for all headings and body text. Its clean, geometric sans-serif forms contribute to the modern-tech aesthetic. Varied letter spacing is used for visual impact at larger display sizes and legibility at smaller text sizes.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.44 | 0.02px | `--text-caption` |
| body | 14px | 1.44 | 0.02px | `--text-body` |
| subheading | 18px | 1.44 | -0.03px | `--text-subheading` |
| heading | 24px | 1.44 | -0.03px | `--text-heading` |
| heading-lg | 46px | 0.92 | -0.04px | `--text-heading-lg` |
| display-sm | 54px | 0.92 | -0.04px | `--text-display-sm` |
| display | 66px | 0.92 | -0.075px | `--text-display` |
| display-lg | 92px | 0.92 | -0.075px | `--text-display-lg` |
| display-xl | 124px | 1 | -0.075px | `--text-display-xl` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 8 | 8px | `--spacing-8` |
| 12 | 12px | `--spacing-12` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 36 | 36px | `--spacing-36` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 116 | 116px | `--spacing-116` |
| 220 | 220px | `--spacing-220` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 24.0048px |
| icons | 6.9984px |
| buttons | 1425.6px |
| largeCards | 31.9968px |
| smallCards | 15.9984px |

### Layout

- **Section gap:** 34px
- **Card padding:** 43px
- **Element gap:** 8px

## Components

### Primary Action Button
**Role:** Major calls to action

Filled with Action Violet (#5350cc), text in White (#ffffff). Features a high radius (1425.6px) making it a pill shape, with padding around 8px.

### Ghost Header Button
**Role:** Navigation and secondary actions in header

Transparent background with text and border in Ghost Frost (#f4f4f6). No explicit padding, relying on the inherent spacing of the text, and no border radius.

### White Ghost Button
**Role:** Secondary calls to action on dark backgrounds

Transparent background with border in Action Violet (#5350cc) and text in White (#ffffff). Also features the high radius (1425.6px) for a subtle pill shape. Padding is context-dependent, often zero.

### Hero Section Card
**Role:** Information containers within the hero

Background is Midnight Indigo (#16165c), with a distinct large radius of 31.9968px. No explicit internal padding, content is managed by child elements' spacing.

### Feature Card
**Role:** Displaying product features or service benefits

Background is Deep Violet Surface (#232269), with a moderately large radius of 24.0048px for a soft, contained feel. No explicit padding.

### Data Insight Card
**Role:** Displaying summarized data or key metrics

Background is Deep Violet Surface (#232269), with a rounded top edge (24.0048px 24.0048px 0px 0px). No explicit internal padding.

### Circular Badge Card
**Role:** Iconic representation or small data points

Background is Deep Violet Surface (#232269) with a fully circular radius (100%). No padding. Used for small, contained elements.

## Do's and Don'ts

### Do
- Prioritize Midnight Indigo (#16165c) for main backgrounds and primary surface containers.
- Use White (#ffffff) for primary text on dark backgrounds to ensure legibility and contrast.
- Apply Action Violet (#5350cc) consistently for primary button fills and key interactive elements.
- Employ Bright Blue (#00b1ff) and Vivid Green (#00ffaa) as functional accents for icons, data visualization, and interactive states.
- Use a uniform radius of 1425.6px for all primary action buttons for a consistent pill-shaped aesthetic.
- Utilize Ghost Frost (#f4f4f6) for secondary text and subtle borders to manage visual hierarchy without stark contrast.
- Maintain an element gap of 8px for micro-spacing between related interface elements.

### Don't
- Avoid using bright colors for large background areas; reserve them for accents and data.
- Do not introduce sharp corners; maintain the overall soft-edged aesthetic by applying radii like 24.0048px to cards and containers.
- Do not deviate from the Gilroy typeface; it is fundamental to the brand's typographic identity.
- Avoid generic black or pure white as background or text colors; use Midnight Indigo (#16165c) and White (#ffffff) or Ghost Frost (#f4f4f6) instead.
- Do not use generic box-shadows that conflict with the subtle elevation and border-driven depth model.
- Avoid dense, information-heavy sections; use ample spacing with a comfortable density to maintain clarity.
- Do not replace the established accent hues (Bright Blue #00b1ff, Vivid Green #00ffaa) with other chromatic colors.

## Imagery

The site uses a combination of line-art illustrations, product screenshots, and occasional abstract graphics. Line-art illustrations are monochromatic (Muted Violet #b1a6f6 or Ghost Frost #f4f4f6) with subtle fills and strokes, depicting medical devices in context or abstract data flows, usually large and atmospheric. Product screenshots, particularly in the data dashboard, are sharp, high-contrast, and focused on the UI elements themselves within a dark theme, often showing detailed data visualizations. Icons are generally outlined, in mono or dual-tone (e.g., Bright Blue #00b1ff and Vivid Green #00ffaa), with a medium stroke weight. Imagery is primarily explanatory and decorative, supporting the technical, healthcare-focused narrative without being overly realistic or lifestyle-oriented. Density is balanced, with larger illustrative elements in hero sections and detailed product UI in content sections.

## Layout

The page primarily uses a full-bleed layout for its background, but content is typically constrained to a maximum width (implicitly around 1200px) and centered. The hero section is full-bleed with a deep violet background, featuring a large, centered headline and descriptive text, often accompanied by atmospheric line-art. Sections are separated by distinct background color changes (e.g., Midnight Indigo #16165c for the dark sections, White #ffffff for lighter content sections in the middle of the page). Content arrangement often alternates between text and visual elements in a 2-column or full-width stacked fashion. Card grids are used for features, displaying 3-4 cards per row. Vertical spacing between sections is generous, contributing to a comfortable, unhurried density. Navigation consists of a sticky top bar with a left-aligned logo, right-aligned navigation links, and a primary action button.

## Agent Prompt Guide

Quick Color Reference: 
- text: #ffffff
- background: #16165c
- border: #4846c6
- accent: #00b1ff
- primary action: #5350cc (filled action)

Example Component Prompts:
- Create a hero section: Midnight Indigo (#16165c) background. Headline 'Making at home healthcare' (text: #ffffff, size: 66px Gilroy weight 600, letter-spacing: -0.075em), followed by 'personalized.' (text: Bright Blue #00b1ff, size: 66px Gilroy weight 600, letter-spacing: -0.075em). Subtext 'Remote care logistics and patient support with unified data management.' (text: Ghost Frost #f4f4f6, size: 18px Gilroy weight 500, letter-spacing: -0.03em).
- Create a primary CTA button: 'Request Demo' with Action Violet (#5350cc) background, White (#ffffff) text (17px Gilroy weight 500), 1425.6px border-radius, and 8px padding.
- Create a feature card: Deep Violet Surface (#232269) background, 24.0048px border-radius. Headline (18px Gilroy weight 600, text: White #ffffff), body text (14px Gilroy weight 500, text: Ghost Frost #f4f4f6).
- Create a navigation link: 'Solutions' with transparent background, Ghost Frost (#f4f4f6) text (14px Gilroy weight 500, no explicit padding). On hover, use Action Violet (#5350cc) as the text color.

## Similar Brands

- **Aura** — Uses a dark, tech-oriented theme with vibrant accent colors for data visualization and interactive elements.
- **Vercel** — Employs a deep dark background with clean, geometric typography and focused, contrasting highlight colors for UI elements.
- **Supabase** — Features a dark UI with saturated accent colors (especially blue and green), rounded components, and line-art illustrations within a technical context.
- **Chronos** — Utilizes a deep, rich color palette (often purples and blues) for background and surfaces, combined with white text and vibrant accents for interactive clarity.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-indigo: #16165c;
  --color-ghost-frost: #f4f4f6;
  --color-bright-blue: #00b1ff;
  --color-vivid-green: #00ffaa;
  --color-action-violet: #5350cc;
  --color-white: #ffffff;
  --color-muted-violet: #b1a6f6;
  --color-deep-violet-surface: #232269;
  --color-rich-violet: #403cd5;
  --color-interactive-violet: #524fe1;
  --color-hairline-gray: #9494a9;
  --color-subtle-gray: #d8d8e3;
  --color-data-teal: #2ee9ff;
  --color-outline-violet: #4846c6;

  /* Typography — Font Families */
  --font-gilroy: 'Gilroy', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.44;
  --tracking-caption: 0.02px;
  --text-body: 14px;
  --leading-body: 1.44;
  --tracking-body: 0.02px;
  --text-subheading: 18px;
  --leading-subheading: 1.44;
  --tracking-subheading: -0.03px;
  --text-heading: 24px;
  --leading-heading: 1.44;
  --tracking-heading: -0.03px;
  --text-heading-lg: 46px;
  --leading-heading-lg: 0.92;
  --tracking-heading-lg: -0.04px;
  --text-display-sm: 54px;
  --leading-display-sm: 0.92;
  --tracking-display-sm: -0.04px;
  --text-display: 66px;
  --leading-display: 0.92;
  --tracking-display: -0.075px;
  --text-display-lg: 92px;
  --leading-display-lg: 0.92;
  --tracking-display-lg: -0.075px;
  --text-display-xl: 124px;
  --leading-display-xl: 1;
  --tracking-display-xl: -0.075px;

  /* Typography — Weights */
  --font-weight-medium: 500;
  --font-weight-semibold: 600;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-116: 116px;
  --spacing-220: 220px;

  /* Layout */
  --section-gap: 34px;
  --card-padding: 43px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-md: 6.9984px;
  --radius-2xl: 15.9984px;
  --radius-3xl: 24.0048px;
  --radius-3xl-2: 31.9968px;
  --radius-full: 1425.6px;

  /* Named Radii */
  --radius-cards: 24.0048px;
  --radius-icons: 6.9984px;
  --radius-buttons: 1425.6px;
  --radius-largecards: 31.9968px;
  --radius-smallcards: 15.9984px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-indigo: #16165c;
  --color-ghost-frost: #f4f4f6;
  --color-bright-blue: #00b1ff;
  --color-vivid-green: #00ffaa;
  --color-action-violet: #5350cc;
  --color-white: #ffffff;
  --color-muted-violet: #b1a6f6;
  --color-deep-violet-surface: #232269;
  --color-rich-violet: #403cd5;
  --color-interactive-violet: #524fe1;
  --color-hairline-gray: #9494a9;
  --color-subtle-gray: #d8d8e3;
  --color-data-teal: #2ee9ff;
  --color-outline-violet: #4846c6;

  /* Typography */
  --font-gilroy: 'Gilroy', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.44;
  --tracking-caption: 0.02px;
  --text-body: 14px;
  --leading-body: 1.44;
  --tracking-body: 0.02px;
  --text-subheading: 18px;
  --leading-subheading: 1.44;
  --tracking-subheading: -0.03px;
  --text-heading: 24px;
  --leading-heading: 1.44;
  --tracking-heading: -0.03px;
  --text-heading-lg: 46px;
  --leading-heading-lg: 0.92;
  --tracking-heading-lg: -0.04px;
  --text-display-sm: 54px;
  --leading-display-sm: 0.92;
  --tracking-display-sm: -0.04px;
  --text-display: 66px;
  --leading-display: 0.92;
  --tracking-display: -0.075px;
  --text-display-lg: 92px;
  --leading-display-lg: 0.92;
  --tracking-display-lg: -0.075px;
  --text-display-xl: 124px;
  --leading-display-xl: 1;
  --tracking-display-xl: -0.075px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-116: 116px;
  --spacing-220: 220px;

  /* Border Radius */
  --radius-md: 6.9984px;
  --radius-2xl: 15.9984px;
  --radius-3xl: 24.0048px;
  --radius-3xl-2: 31.9968px;
  --radius-full: 1425.6px;
}
```

# CQCM — Style Reference
> Vibrant authority, structured impact

**Theme:** light

CQCM’s visual system projects authoritative confidence through bold typography and a vibrant accent palette set against an otherwise muted, near-monochromatic background. Black is used as a primary action color, lending a serious, impactful tone. The design features soft, pill-shaped buttons and cards with subtle rounding, balancing the weight of the dark text and the vivid accent colors.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#000000` | `--color-midnight-ink` | Primary text, main UI elements, primary action buttons, borders, dark surface backgrounds |
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card surfaces, ghost button text |
| Mint Glaze | `#eaf9f2` | `--color-mint-glaze` | Subtle secondary backgrounds for cards and sections, soft accents |
| Slate Gray | `#666666` | `--color-slate-gray` | Secondary text, navigation text, subtle borders |
| Shamrock Green | `#44d991` | `--color-shamrock-green` | Accent backgrounds for specific cards and decorative elements, energetic highlights |
| Cornflower Blue | `#4c92e9` | `--color-cornflower-blue` | Accent backgrounds for cards and informational elements, structural highlight |
| Persimmon Orange | `#ff6a51` | `--color-persimmon-orange` | Tertiary accent background for cards, draws attention |

## Tokens — Typography

### Manrope — Body text, navigation items, badge content, button labels, and secondary information. Its consistent weight across sizes ensures readability and a uniform voice. · `--font-manrope`
- **Substitute:** system-ui
- **Weights:** 400
- **Sizes:** 12px, 14px, 16px, 18px, 20px, 22px
- **Line height:** 1.00, 1.30, 1.40
- **Letter spacing:** 0.0100em at 12px, 0.0110em at 14px
- **Role:** Body text, navigation items, badge content, button labels, and secondary information. Its consistent weight across sizes ensures readability and a uniform voice.

### Athletics — Headlines, large display numbers, and prominent labels. Its unique character delivers a strong brand presence, especially at larger sizes, conveying impact and authority. · `--font-athletics`
- **Substitute:** Arial, sans-serif
- **Weights:** 400, 500
- **Sizes:** 12px, 14px, 16px, 22px, 48px, 59px, 78px
- **Line height:** 1.00
- **Letter spacing:** 0.0040em at 12px, 0.0400em at 48px
- **Role:** Headlines, large display numbers, and prominent labels. Its unique character delivers a strong brand presence, especially at larger sizes, conveying impact and authority.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.4 | 0.12px | `--text-caption` |
| body-sm | 14px | 1.4 | 0.15px | `--text-body-sm` |
| body | 16px | 1.4 | — | `--text-body` |
| subheading | 22px | 1 | — | `--text-subheading` |
| heading | 48px | 1 | 1.92px | `--text-heading` |
| heading-lg | 59px | 1 | — | `--text-heading-lg` |
| display | 78px | 1 | — | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 8 | 8px | `--spacing-8` |
| 20 | 20px | `--spacing-20` |
| 40 | 40px | `--spacing-40` |
| 60 | 60px | `--spacing-60` |
| 80 | 80px | `--spacing-80` |
| 100 | 100px | `--spacing-100` |
| 120 | 120px | `--spacing-120` |
| 200 | 200px | `--spacing-200` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 8px |
| badges | 4px |
| images | 4px |
| buttons | 100px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| lg | `rgba(0, 0, 0, 0.1) 0px 0px 20px 0px` | `--shadow-lg` |

### Layout

- **Section gap:** 40px
- **Card padding:** 20px
- **Element gap:** 20px

## Components

### Primary Action Pill Button
**Role:** Main call-to-action button for critical actions.

Filled with Midnight Ink (#000000), text is Canvas White (#ffffff), features a 100px border radius for a full pill shape, with 20px horizontal padding. Font is Manrope, 400 weight.

### Ghost Text Button
**Role:** Secondary actions or embedded links.

Transparent background, Midnight Ink (#000000) text, no border or padding, uses Manrope 400. Appears as a link but functions as an interactive button.

### Rounded Shadowless Card
**Role:** Standard content containers, often for articles or features.

Canvas White (#ffffff) background, 8px border radius, no box shadow, 30px horizontal padding and 0px vertical padding. Content flows freely within.

### Primary Accent Card (Shamrock Green)
**Role:** Highlighting key numerical data or important content blocks.

Shamrock Green (#44d991) background, 8px border radius, 20px padding on all sides. Used to make content pop against the neutral background.

### Secondary Accent Card (Cornflower Blue)
**Role:** Highlighting complementary numerical data or informational blocks.

Cornflower Blue (#4c92e9) background, 8px border radius, with 15px vertical and 20px horizontal padding bottom 20px. Used in stacked numerical displays.

### Tertiary Accent Card (Persimmon Orange)
**Role:** Highlighting a third tier of numerical data.

Persimmon Orange (#ff6a51) background, 8px border radius, with 20px vertical and horizontal padding bottom 20px. Part of the stacked numerical display.

### Tag Badge
**Role:** Categorization or short status labels.

Transparent background, Midnight Ink (#000000) text (Manrope 400), 4px border radius, 7px vertical and 8px horizontal padding.

### Filled Tag Badge
**Role:** Prominent categorization or highlighted status labels.

Background of rgba(0,0,0,0.1), Midnight Ink (#000000) text (Manrope 400), 4px border radius, 7px vertical and 8px horizontal padding.

## Do's and Don'ts

### Do
- Use Midnight Ink (#000000) for all primary text and calls-to-action to maintain a strong, direct brand voice.
- Employ a 100px border radius for primary action buttons to achieve a soft, pill-like appearance.
- Utilize Manrope 400 for most body and navigation text, and Athletics 400/500 for headlines and key statistics to create a clear typographic hierarchy.
- Apply 8px border radius consistently to content cards, balancing the sharp angles of the layout with soft component edges.
- Incorporate Shamrock Green (#44d991), Cornflower Blue (#4c92e9), and Persimmon Orange (#ff6a51) sparingly for high-impact cards or data highlights, keeping most surfaces neutral.
- Ensure ample vertical spacing between sections, using a minimum of 40px, to create a comfortable reading experience.
- Use subtle rgba(0, 0, 0, 0.1) 0px 0px 20px 0px shadow for interactive navigation elements, distinguishing them from static content.

### Don't
- Do not introduce new saturated colors beyond the defined brand palette (Shamrock Green, Cornflower Blue, Persimmon Orange).
- Avoid using excessive box shadows; elevation is minimal and reserved for specific interactive elements only.
- Do not deviate from the Manrope and Athletics font families; custom typefaces are a core part of the brand identity.
- Do not use generic text links with underline; implement ghost buttons (transparent background, Midnight Ink text) for navigational or secondary actions.
- Do not create dense blocks of text without visual breaks; ensure generous line heights (e.g., 1.4 for body text) and use clear headings to aid readability.
- Avoid decorative imagery that competes with the brand's direct and impactful typography; imagery should be concise and supportive.
- Do not use highly contrasting border colors other than Midnight Ink, as most borders are subtle or implied.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas White | `#ffffff` | Primary page background and base for most content sections. |
| 1 | Mint Glaze | `#eaf9f2` | Secondary background for alternating sections and some cards, providing subtle visual separation. |
| 2 | Accent Surfaces | `#44d991` | Vivid background colors for cards to highlight specific content or data points. |

## Imagery

The visual language predominantly uses realistic, high-quality photography of people, often with a sense of candidness or natural interaction, rather than highly staged scenes. These images are frequently used as large, prominent backdrops or half-width hero elements. Graphics include simple, filled geometric shapes (circles) used decoratively overlaying imagery. Icons are minimal, outlined, and monochromatic, primarily in Midnight Ink (#000000), serving a functional rather than decorative role. Imagery's role is to add a human element and context, often in contrast to the bold, factual typography, and is used moderately, allowing text to remain dominant in information-heavy sections.

## Layout

The page primarily uses a full-bleed layout for hero sections, but often contains content within a max-width, centrally aligned structure for readability in subsequent sections. The hero pattern is a split layout, with a large-format photograph on one side and a bold, centered headline on an accent background on the other. Section rhythm alternates between full-width content blocks and contained, often card-based, arrangements. Content frequently uses a left-aligned, stacked approach for text, with cards arranged in grids or sequential blocks. A dominant pattern is information presented in vertical stacks of accent-colored cards, each highlighting a key statistic. Navigation is a sticky top bar with minimal links and a primary accent button.

## Agent Prompt Guide

**Quick Color Reference:**
- text: #000000
- background: #ffffff
- border: #000000
- accent: #44d991
- primary action: #000000 (filled action)

**3-5 Example Component Prompts:**
- Create a hero section: Canvas White (#ffffff) background for text, ShamrocK Green (#44d991) background for headlines. Headline 'APPPUYER LE DÉVELOPPEMENT SOCIAL ET ÉCONOMIQUE' in Athletics 78px weight 500, Midnight Ink (#000000), letter-spacing 1.92px. Primary Action Pill Button with label 'QUI SOMMES-NOUS' (Manrope 400, Canvas White text), Midnight Ink (#000000) background, 100px radius, 20px horizontal padding.
- Design a data display block: Stacked cards with 8px radius. Top card with background Shamrock Green (#44d991), 20px padding. Next card with Cornflower Blue (#4c92e9) background, 15px vertical, 20px horizontal padding. Bottom card with Persimmon Orange (#ff6a51) background, 20px padding. Headings within cards should use Athletics, sizes 48px, 59px, 78px, all weight 500, Midnight Ink (#000000).
- Create a news card component: Rounded Shadowless Card on Mint Glaze (#eaf9f2) background. Article title in Athletics 22px weight 500, Midnight Ink (#000000). Metadata in Manrope 12px weight 400, Slate Gray (#666666). Ghost Text Button 'LIRE' (Manrope 400, Midnight Ink text).

## Similar Brands

- **Hydro-Québec** — Uses bold, stark typography with a mix of neutral and single, strong accent colors (often green or blue) on a light background, similar to CQCM's impactful headings and monochromatic base.
- **Invest In Canada** — Features a clean layout, strong use of primary brand color accents (often in blocks), and distinct black text against white backgrounds, reminiscent of CQCM's use of Midnight Ink for impact.
- **Government of Canada** — Exhibits a clear, functional interface with strong typographic hierarchy, neutral backgrounds, and sparing, purposeful use of brand colors for highlighting key information, echoing CQCM's balanced approach.
- **Desjardins** — Employs a crisp, professional aesthetic with distinct components, clear calls to action (often in a strong brand color), and structured information presentation, similar to CQCM's organized data display.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-canvas-white: #ffffff;
  --color-mint-glaze: #eaf9f2;
  --color-slate-gray: #666666;
  --color-shamrock-green: #44d991;
  --color-cornflower-blue: #4c92e9;
  --color-persimmon-orange: #ff6a51;

  /* Typography — Font Families */
  --font-manrope: 'Manrope', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-athletics: 'Athletics', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.4;
  --tracking-caption: 0.12px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.4;
  --tracking-body-sm: 0.15px;
  --text-body: 16px;
  --leading-body: 1.4;
  --text-subheading: 22px;
  --leading-subheading: 1;
  --text-heading: 48px;
  --leading-heading: 1;
  --tracking-heading: 1.92px;
  --text-heading-lg: 59px;
  --leading-heading-lg: 1;
  --text-display: 78px;
  --leading-display: 1;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-8: 8px;
  --spacing-20: 20px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-80: 80px;
  --spacing-100: 100px;
  --spacing-120: 120px;
  --spacing-200: 200px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 20px;
  --element-gap: 20px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-3xl: 30px;
  --radius-full: 100px;

  /* Named Radii */
  --radius-cards: 8px;
  --radius-badges: 4px;
  --radius-images: 4px;
  --radius-buttons: 100px;

  /* Shadows */
  --shadow-lg: rgba(0, 0, 0, 0.1) 0px 0px 20px 0px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-mint-glaze: #eaf9f2;
  --surface-accent-surfaces: #44d991;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-canvas-white: #ffffff;
  --color-mint-glaze: #eaf9f2;
  --color-slate-gray: #666666;
  --color-shamrock-green: #44d991;
  --color-cornflower-blue: #4c92e9;
  --color-persimmon-orange: #ff6a51;

  /* Typography */
  --font-manrope: 'Manrope', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-athletics: 'Athletics', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.4;
  --tracking-caption: 0.12px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.4;
  --tracking-body-sm: 0.15px;
  --text-body: 16px;
  --leading-body: 1.4;
  --text-subheading: 22px;
  --leading-subheading: 1;
  --text-heading: 48px;
  --leading-heading: 1;
  --tracking-heading: 1.92px;
  --text-heading-lg: 59px;
  --leading-heading-lg: 1;
  --text-display: 78px;
  --leading-display: 1;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-20: 20px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-80: 80px;
  --spacing-100: 100px;
  --spacing-120: 120px;
  --spacing-200: 200px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-3xl: 30px;
  --radius-full: 100px;

  /* Shadows */
  --shadow-lg: rgba(0, 0, 0, 0.1) 0px 0px 20px 0px;
}
```

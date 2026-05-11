# Fiasco — Style Reference
> Gallery canvas, warm minimal.

**Theme:** light

Fiasco projects a refined, tactile aesthetic using a muted off-white canvas and discreet typographical hierarchy. The system prioritizes crisp, open layouts punctuated by occasional vibrant accent colors that appear as focused, deliberate flashes rather than overwhelming washes. Components often feature generous radii, conveying a soft, approachable feel despite the otherwise formal typography. The overall impression is one of crafted minimalism with attention to subtle detail and comfortable negative space.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Cloud Canvas | `#f8f9f3` | `--color-cloud-canvas` | Page background, primary surface, light button border, input background |
| Soot Black | `#1d1e19` | `--color-soot-black` | Primary text, almost-black button background, input text, default border for elements |
| Ash Grey | `#e9eae2` | `--color-ash-grey` | Secondary surface, subtle background for sections and UI elements, navigation stroke |
| Slate Border | `#686e77` | `--color-slate-border` | Input field borders, often an accent for accessibility on form elements |
| Midnight Ink | `#151612` | `--color-midnight-ink` | Footer background, dark section backgrounds |
| Accent Yellow | `#fff714` | `--color-accent-yellow` | Decorative background for cards or highlight elements — a vibrant, unexpected pop |
| Candy Pink | `#fbc2d1` | `--color-candy-pink` | Distinctive card background, decorative accents – muted yet playful |
| Sky Blue | `#84bdff` | `--color-sky-blue` | Decorative card background, often paired with neutral content |
| Vivid Orange | `#fd6b01` | `--color-vivid-orange` | Orange wash for highlight backgrounds, decorative bands, and soft emphasis behind content. Do not promote it to the primary CTA color |
| Forest Green | `#03ac47` | `--color-forest-green` | Green wash for highlight backgrounds, decorative bands, and soft emphasis behind content |
| Action Blue | `#204ce5` | `--color-action-blue` | Primary call-to-action button background, signaling interactivity and core user flow |

## Tokens — Typography

### Area-Normal — Primary text across body, inputs, buttons, navigation, and core content; its variable weight supports hierarchy and emphasis without leaving its defined family. · `--font-area-normal`
- **Substitute:** Inter
- **Weights:** 400, 500, 600
- **Sizes:** 12px, 13px, 14px, 18px, 20px, 30px, 60px, 80px
- **Line height:** 1.00, 1.10, 1.20, 1.40, 1.43, 1.50, 1.60, 2.71
- **Letter spacing:** -0.0290em, -0.0220em, -0.0200em, -0.0130em, -0.0050em
- **Role:** Primary text across body, inputs, buttons, navigation, and core content; its variable weight supports hierarchy and emphasis without leaving its defined family.

### HAL Timezone — Header text and selected navigation elements. Its distinct narrow character and light weights add a refined, almost technical touch, distinguishing it from the body copy. · `--font-hal-timezone`
- **Substitute:** IBM Plex Sans
- **Weights:** 100, 400, 500
- **Sizes:** 12px, 20px, 22px, 34px
- **Line height:** 1.20, 1.40, 1.50, 2.00
- **Letter spacing:** -0.0330em, -0.0200em, -0.0180em, -0.0120em, 0.0100em
- **Role:** Header text and selected navigation elements. Its distinct narrow character and light weights add a refined, almost technical touch, distinguishing it from the body copy.

### Gooper — Used for specific headings and internal links, Gooper provides a slightly more rounded, approachable feel than Area-Normal, reserving its bolder weights for impactful titles. · `--font-gooper`
- **Substitute:** Open Sans
- **Weights:** 400, 500, 700
- **Sizes:** 16px, 17px, 19px, 40px
- **Line height:** 0.80, 1.20, 1.30
- **Letter spacing:** -0.0250em, -0.0210em, -0.0200em, -0.0100em
- **Role:** Used for specific headings and internal links, Gooper provides a slightly more rounded, approachable feel than Area-Normal, reserving its bolder weights for impactful titles.

### OC Highway — Used for small, highly tracked labels or metadata, providing a technical and spaced-out stylistic choice that creates clear separation from main content blocks. · `--font-oc-highway`
- **Substitute:** Roboto Condensed
- **Weights:** 400
- **Sizes:** 10px
- **Line height:** 1.10
- **Letter spacing:** 0.1000em
- **Role:** Used for small, highly tracked labels or metadata, providing a technical and spaced-out stylistic choice that creates clear separation from main content blocks.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.1 | 1px | `--text-caption` |
| body-lg | 14px | 1.6 | -0.28px | `--text-body-lg` |
| subheading | 19px | 1.2 | -0.38px | `--text-subheading` |
| heading | 30px | 1.2 | -0.6px | `--text-heading` |
| heading-lg | 40px | 1.2 | -1px | `--text-heading-lg` |
| display | 80px | 1 | -2.32px | `--text-display` |

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
| 32 | 32px | `--spacing-32` |
| 36 | 36px | `--spacing-36` |
| 40 | 40px | `--spacing-40` |
| 68 | 68px | `--spacing-68` |
| 80 | 80px | `--spacing-80` |
| 120 | 120px | `--spacing-120` |
| 160 | 160px | `--spacing-160` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 8px |
| links | 44px |
| inputs | 3px |
| buttons | 800px |
| heroContainer | 40px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| sm | `rgba(18, 25, 97, 0.08) 0px 1px 4px 0px` | `--shadow-sm` |
| xl | `rgba(0, 0, 0, 0.16) 0px 28px 80px 0px` | `--shadow-xl` |

### Layout

- **Page max-width:** 1440px
- **Section gap:** 32px
- **Card padding:** 12px
- **Element gap:** 12px

## Components

### Subtle Ghost Button
**Role:** Secondary action or tag

Rounded button with Soot Black text (#1d1e19) and a transparent background (rgba(29, 30, 25, 0.05)), featuring a 1px Soot Black border (#1d1e19) and fully rounded '800px' corners. Padding is 0px vertical and 12px horizontal.

### Primary Filled Button
**Role:** Call to action

Solid button with Action Blue background (#204ce5), white text (#FFFFFF), and fully rounded '800px' corners. Padding is 8px vertical and 20px horizontal.

### Navigation Link Button
**Role:** Top-level navigation

Circular button with Soot Black background (#1d1e19) and Cloud Canvas text (#f8f9f3), fully rounded '800px'. Padding is 8px vertical and 20px horizontal.

### Standard Card
**Role:** Content container

Transparent background with 8px border-radius and no shadow. No intrinsic padding.

### Hero Section Card
**Role:** Prominent content container

Transparent background with 0px border-radius and no shadow, used for full-width content display without visual containment.

### Accent Pink Card
**Role:** Highlight content

Card with Candy Pink background (#fbc2d1), 8px border-radius, and no shadow. Features 0px vertical padding and 16px horizontal padding, with 20px bottom padding for content.

### Soft Input Field
**Role:** User input

Input field with a translucent Cloud Canvas background (rgba(248, 249, 243, 0.25)) and Soot Black text (#1d1e19). Features a 1px Soot Black border (#1d1e19), 4px border-radius, and 12px vertical padding with 16px horizontal padding.

### Clean Input Field
**Role:** Standard user input

Input field with a white background (#FFFFFF) and Slate Border (#686e77), uses 3px border-radius. No intrinsic padding.

## Do's and Don'ts

### Do
- Use Cloud Canvas (#f8f9f3) as the default page background for all primary content areas.
- Apply Soot Black (#1d1e19) for all primary text content to maintain strong contrast and readability.
- Ensure all text inputs utilize the 3px border-radius with a Slate Border (#686e77) on focus.
- Prioritize fully rounded '800px' corners for all buttons and tags, creating a soft, approachable aesthetic.
- For accentuation of content blocks, select from Accent Yellow (#fff714), Candy Pink (#fbc2d1), Sky Blue (#84bdff), Vivid Orange (#fd6b01), or Forest Green (#03ac47) as card backgrounds.
- Use 12px as the consistent `elementGap` for horizontal and vertical spacing between related components.
- Utilize Area-Normal font family for all body text, adjusting weights (400, 500, 600) and sizes (12-80px) to establish hierarchy.

### Don't
- Avoid using primary brand colors for extensive backgrounds; reserve vibrant colors for deliberate highlights and accents.
- Do not introduce sharp corners or minimal radii where a rounded aesthetic (8px or 800px) is expected, particularly for cards and buttons.
- Do not deviate from the established font families; avoid system fonts or other custom typefaces.
- Do not use letter-spacing values less than -0.0330em or greater than 0.1000em, as found in OC Highway, for readability and brand consistency.
- Avoid large, intrusive shadows; apply soft, subtle elevation where needed, like rgba(18, 25, 97, 0.08) 0px 1px 4px 0px.
- Do not exceed the pageMaxWidth of 1440px for contained content, ensuring a focused reading experience.
- Do not use generic gray tones for input borders; always prefer Soot Black (#1d1e19) for default states and Slate Border (#686e77) for specific form elements.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Cloud Canvas | `#f8f9f3` | Primary page and hero background |
| 1 | Ash Grey | `#e9eae2` | Secondary background for navigation and subtle section breaks |
| 2 | Accent Colored Cards | `#fff714` | Elevated card backgrounds, providing visual distinction for content blocks |
| 3 | Midnight Ink | `#151612` | Dark mode footer and specific section backgrounds |

## Elevation

- **Input fields, Secondary Buttons:** `rgba(18, 25, 97, 0.08) 0px 1px 4px 0px`
- **Hero sections, Cards:** `rgba(0, 0, 0, 0.16) 0px 28px 80px 0px`

## Imagery

The visual language predominantly features clean, product-focused photography and abstract graphics. Photography consists of tight crops of technology or urban landscapes, often with a slightly desaturated, naturalistic color palette. Illustrations are minimal and graphic, serving as decorative accents or background elements. Icons are filled, monochrome, and have a clear, moderate stroke weight. Imagery primarily serves to create atmosphere or visually break up text, rather than being explicitly explanatory. The density is moderate, with images appearing in grid layouts, often within cards, interspersed with text blocks.

## Layout

The page adheres to a max-width 1440px centered model. The hero section often presents a large, centered headline over a background that alternates between full-bleed imagery and the Cloud Canvas. Sections maintain a consistent vertical rhythm, often delineated by distinct background colors or subtle changes in surface level. Content is structured in responsive grids, commonly a 2-column or 3-column arrangement for feature cards and portfolio items. Text-heavy blocks are centered or left-aligned within their containers, creating a spacious and comfortable reading experience. The primary navigation is a sticky top bar with minimal links and a discrete time display.

## Agent Prompt Guide

Quick Color Reference:
- text: #1d1e19
- background: #f8f9f3
- border: #1d1e19
- accent: #fff714
- primary action: #204ce5 (filled action)

Example Component Prompts:
- Create a section divider: 1px solid Ash Grey border (#e9eae2), 12px vertical elementGap from surrounding content.
- Create a feature card: Cloud Canvas background (#f8f9f3), 8px border-radius, 12px cardPadding. Headline (Gooper, 40px, 700, #1d1e19, letter-spacing -1.0px). Body text (Area-Normal, 14px, 400, #1d1e19, lineHeight 1.6).
- Create a Primary Action Button: #204ce5 background, #f8f9f3 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
- Create a tag button: Subtle Ghost Button (rgba(29, 30, 25, 0.05) background, #1d1e19 text, 1px #1d1e19 border, 800px radius, 0px vertical padding, 12px horizontal padding). Font: Area-Normal, 12px, 400, letter-spacing -0.35px.
- Create a text input field: Soft Input Field (rgba(248, 249, 243, 0.25) background, #1d1e19 text, 1px #1d1e19 border, 4px radius, 12px vertical padding, 16px horizontal padding). Font: Area-Normal, 14px, 400, lineHeight 1.6.

## Similar Brands

- **Focus Lab** — Similar approach to using a limited, high-contrast color palette, clean typography, and a spacious layout with subtle background variations.
- **Huge Inc.** — Employs an editorial-style typography hierarchy and significant use of negative space, combined with understated accent colors within design agency portfolios.
- **Work & Co** — Shares a minimalist design aesthetic with a strong emphasis on content, large headlines, and a sophisticated, almost monochrome color scheme with rare, impactful color pops.
- **North Kingdom** — Utilizes a balanced layout with photography and text blocks, keeping UI elements subdued to let content and case studies shine, often with a similar soft neutral background.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-cloud-canvas: #f8f9f3;
  --color-soot-black: #1d1e19;
  --color-ash-grey: #e9eae2;
  --color-slate-border: #686e77;
  --color-midnight-ink: #151612;
  --color-accent-yellow: #fff714;
  --color-candy-pink: #fbc2d1;
  --color-sky-blue: #84bdff;
  --color-vivid-orange: #fd6b01;
  --color-forest-green: #03ac47;
  --color-action-blue: #204ce5;

  /* Typography — Font Families */
  --font-area-normal: 'Area-Normal', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-hal-timezone: 'HAL Timezone', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gooper: 'Gooper', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-oc-highway: 'OC Highway', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.1;
  --tracking-caption: 1px;
  --text-body-lg: 14px;
  --leading-body-lg: 1.6;
  --tracking-body-lg: -0.28px;
  --text-subheading: 19px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.38px;
  --text-heading: 30px;
  --leading-heading: 1.2;
  --tracking-heading: -0.6px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -1px;
  --text-display: 80px;
  --leading-display: 1;
  --tracking-display: -2.32px;

  /* Typography — Weights */
  --font-weight-thin: 100;
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
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-68: 68px;
  --spacing-80: 80px;
  --spacing-120: 120px;
  --spacing-160: 160px;

  /* Layout */
  --page-max-width: 1440px;
  --section-gap: 32px;
  --card-padding: 12px;
  --element-gap: 12px;

  /* Border Radius */
  --radius-sm: 3px;
  --radius-lg: 8px;
  --radius-3xl: 40px;
  --radius-3xl-2: 44px;
  --radius-full: 800px;

  /* Named Radii */
  --radius-cards: 8px;
  --radius-links: 44px;
  --radius-inputs: 3px;
  --radius-buttons: 800px;
  --radius-herocontainer: 40px;

  /* Shadows */
  --shadow-sm: rgba(18, 25, 97, 0.08) 0px 1px 4px 0px;
  --shadow-xl: rgba(0, 0, 0, 0.16) 0px 28px 80px 0px;

  /* Surfaces */
  --surface-cloud-canvas: #f8f9f3;
  --surface-ash-grey: #e9eae2;
  --surface-accent-colored-cards: #fff714;
  --surface-midnight-ink: #151612;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-cloud-canvas: #f8f9f3;
  --color-soot-black: #1d1e19;
  --color-ash-grey: #e9eae2;
  --color-slate-border: #686e77;
  --color-midnight-ink: #151612;
  --color-accent-yellow: #fff714;
  --color-candy-pink: #fbc2d1;
  --color-sky-blue: #84bdff;
  --color-vivid-orange: #fd6b01;
  --color-forest-green: #03ac47;
  --color-action-blue: #204ce5;

  /* Typography */
  --font-area-normal: 'Area-Normal', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-hal-timezone: 'HAL Timezone', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gooper: 'Gooper', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-oc-highway: 'OC Highway', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.1;
  --tracking-caption: 1px;
  --text-body-lg: 14px;
  --leading-body-lg: 1.6;
  --tracking-body-lg: -0.28px;
  --text-subheading: 19px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.38px;
  --text-heading: 30px;
  --leading-heading: 1.2;
  --tracking-heading: -0.6px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -1px;
  --text-display: 80px;
  --leading-display: 1;
  --tracking-display: -2.32px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-68: 68px;
  --spacing-80: 80px;
  --spacing-120: 120px;
  --spacing-160: 160px;

  /* Border Radius */
  --radius-sm: 3px;
  --radius-lg: 8px;
  --radius-3xl: 40px;
  --radius-3xl-2: 44px;
  --radius-full: 800px;

  /* Shadows */
  --shadow-sm: rgba(18, 25, 97, 0.08) 0px 1px 4px 0px;
  --shadow-xl: rgba(0, 0, 0, 0.16) 0px 28px 80px 0px;
}
```

# Leonardo.ai — Style Reference
> Luminous Digital Void: vibrant hues punching through deep darkness.

**Theme:** dark

Leonardo.Ai evokes a luminous digital void, where vibrant hues punch through deep darkness. Typography is bold and oversized, often warping or stacked for dramatic effect, suggesting a world of limitless creation. Interface elements are primarily ghosted or outlined, allowing the rich generative imagery and expressive text to dominate, with solid accents used sparingly for key interactions. The system maintains a high contrast, dark-mode default, relying on the interplay of black canvas, bright white text, and a focused palette of vivid, single-color accents for points of interest.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Void | `#000000` | `--color-midnight-void` | Primary page background, high-contrast text color on white surfaces, shadow base |
| Ghostly Gray | `#e5e5e5` | `--color-ghostly-gray` | Subtle borders, dividers, secondary ghost button borders, and input outlines. Provides minimal structural definition without asserting strong presence |
| Off-Black Text | `linear-gradient(rgb(10, 10, 10) 0%, rgba(37, 37, 37, 0.65) 100%)` | `--color-off-black-text` | Text on light surfaces, also appearing as link color on dark backgrounds, suggesting a subtle tonal shift from pure black; Background gradient for sections, providing a smooth transition from deep black |
| Pure White | `#ffffff` | `--color-pure-white` | Primary text color against dark backgrounds, filled button backgrounds, active navigation elements |
| Subtle Surface | `#353535` | `--color-subtle-surface` | Elevated card backgrounds, differentiated from the main background without introducing significant lightness |
| Muted Ash | `#999999` | `--color-muted-ash` | Secondary text, descriptive elements, inactive link states. Reduces visual hierarchy |
| Luminous Green | `#03e65b` | `--color-luminous-green` | Green wash for highlight backgrounds, decorative bands, and soft emphasis behind content |
| Deep Violet | `#6e60ee` | `--color-deep-violet` | Violet wash for highlight backgrounds, decorative bands, and soft emphasis behind content. |
| Electric Yellow | `#ffc533` | `--color-electric-yellow` | Secondary accent for categorization, highlights, and occasional decorative elements. Creates visual energy |
| Vivid Crimson | `#ff3386` | `--color-vivid-crimson` | Tertiary accent, often paired with other vivid colors for visual interest or to denote specific categories. Used judiciously |
| Sunset Red | `#ff5d4b` | `--color-sunset-red` | A warmer red accent, similar in use to Vivid Crimson for visual variety and categorization |

## Tokens — Typography

### canvaSans — Primary legible text for body content, UI labels, links, and navigation. Its consistent weight range and neutral tone support the more expressive display fonts. · `--font-canvasans`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400, 500, 700
- **Sizes:** 10px, 12px, 14px, 16px, 18px, 19px
- **Line height:** 1.10, 1.15, 1.20, 1.25, 1.33
- **Letter spacing:** normal
- **Role:** Primary legible text for body content, UI labels, links, and navigation. Its consistent weight range and neutral tone support the more expressive display fonts.

### leoSans — Bold, condensed display typeface used for all major headings and artistic text. Its varied weights and negative letter-spacing create a distinct, authoritative, and slightly aggressive feel. The large sizes and tight tracking are a signature element. · `--font-leosans`
- **Substitute:** Georgia, serif
- **Weights:** 500, 800, 900
- **Sizes:** 14px, 22px, 34px, 35px, 39px, 44px, 45px, 48px, 50px, 51px, 59px, 65px, 66px, 68px, 75px, 76px, 78px, 79px, 85px, 86px, 90px, 98px, 165px
- **Line height:** 0.80, 0.85, 0.90, 0.93, 1.00, 1.25
- **Letter spacing:** -0.0200em at large sizes, -0.0100em at smaller heading sizes
- **Role:** Bold, condensed display typeface used for all major headings and artistic text. Its varied weights and negative letter-spacing create a distinct, authoritative, and slightly aggressive feel. The large sizes and tight tracking are a signature element.

### ufficioDisplay — Specialized display face for specific, highly stylized heading elements. Its specific 34px size with tight letter spacing creates a unique, impactful visual identity for specific marketing text. · `--font-ufficiodisplay`
- **Substitute:** serif
- **Weights:** 500
- **Sizes:** 34px
- **Line height:** 0.92
- **Letter spacing:** -0.0200em
- **Role:** Specialized display face for specific, highly stylized heading elements. Its specific 34px size with tight letter spacing creates a unique, impactful visual identity for specific marketing text.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.1 | — | `--text-caption` |
| body | 14px | 1.2 | — | `--text-body` |
| subheading | 18px | 1.25 | — | `--text-subheading` |
| heading-sm | 22px | 0.8 | -0.22px | `--text-heading-sm` |
| heading | 39px | 0.9 | -0.78px | `--text-heading` |
| heading-lg | 59px | 0.85 | -1.18px | `--text-heading-lg` |
| display | 165px | 0.8 | -3.3px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 5 | 5px | `--spacing-5` |
| 7 | 7px | `--spacing-7` |
| 10 | 10px | `--spacing-10` |
| 14 | 14px | `--spacing-14` |
| 17 | 17px | `--spacing-17` |
| 20 | 20px | `--spacing-20` |
| 27 | 27px | `--spacing-27` |
| 34 | 34px | `--spacing-34` |
| 41 | 41px | `--spacing-41` |
| 44 | 44px | `--spacing-44` |
| 47 | 47px | `--spacing-47` |
| 54 | 54px | `--spacing-54` |
| 61 | 61px | `--spacing-61` |
| 68 | 68px | `--spacing-68` |
| 135 | 135px | `--spacing-135` |
| 203 | 203px | `--spacing-203` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 270px |
| cards | 8.4375px |
| buttons | 60px |

### Layout

- **Section gap:** 34-37px
- **Card padding:** 17-20px
- **Element gap:** 7-10px

## Components

### Ghost Pill Button
**Role:** Secondary action button for navigation or tertiary interactions.

Background #000000 (transparent), text #ffffff, border 1px solid #ffffff, 60px radius. Padding 6.75px vertical, 20.25px horizontal. The extensive radius creates a pill shape.

### Filled Pill Button (Light)
**Role:** Primary action button, high contrast.

Background #ffffff, text #000000, 60px radius. Padding 6.75px vertical, 20.25px horizontal. Used for prominent calls to action.

### Icon-only Button
**Role:** Navigation or small interactive elements where size is minimal.

Background transparent, text #ffffff, no border, 0px radius. No internal padding, relying on icon size for visual area.

### Horizontal Tab Button
**Role:** Segmented control for filtering or switching views.

Background transparent, text #ffffff, right-aligned, 60px radius for specific end caps. Used within a group, often with 0px padding as part of a larger component.

### Basic Content Card
**Role:** Container for secondary content like descriptions or detailed information.

Background #353535, 8.4375px radius, no shadow. Padding 20.25px on all sides. Used for structured textual content.

### Accent Product Card
**Role:** Visually distinct card for showcasing featured items or categories.

Background uses vivid brand colors like #03e65b or #ffc533, 20.4375px radius, no shadow. Padding 16.875px on all sides. These variations bring saturated color to sections.

### Content Badge
**Role:** Label or tag for categorization.

Background transparent, text #ffffff, 0px radius. Used for small textual indicators.

## Do's and Don'ts

### Do
- Always use Midnight Void (#000000) for page backgrounds to maintain the deep, dark aesthetic.
- Utilize Pure White (#ffffff) as the primary text color on dark backgrounds for legibility and visual pop.
- Apply LeoSans for all headlines and display text, using extensive letter-spacing adjustments (e.g., -0.0200em for large sizes) to achieve its distinct, compressed look.
- Employ Ghostly Gray (#e5e5e5) for all non-interactive borders, including ghost buttons and dividers, to maintain a subtle structure against dark surfaces.
- Reserve Luminous Green (#03e65b) and Deep Violet (#6e60ee) for distinct accent roles like active states, critical highlights, and brand iconography.
- Use 60px border radius for interactive elements like buttons to achieve a strong pill-like, accessible shape.
- Implement the linear-gradient(rgb(10, 10, 10) 0%, rgba(37, 37, 37, 0.65) 100%) for contained sections that need a softer, slightly varied background from the pure black canvas.

### Don't
- Avoid using multiple accent colors in close proximity; instead, let a single accent color make its statement.
- Do not introduce light gray backgrounds for content sections; maintain the dark theme by using Subtle Surface (#353535) for elevated cards.
- Refrain from using default browser link styles; ensure all links use canvaSans and either Pure White (#ffffff) or Muted Ash (#999999) with appropriate hover states.
- Do not use subtle shadows for elevation; the system relies on solid background color shifts for hierarchy.
- Never use `canvaSans` for headlines; its purpose is functional readability, not expressive display.
- Avoid generic rectangular buttons; all prominent buttons should adopt the distinct 60px pill radius.
- Do not introduce large amounts of whitespace around tightly tracked headlines; they are designed to command dense visual space.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Midnight Void | `#000000` | Primary page background, the base canvas. |
| 1 | Subtle Surface | `#353535` | Elevated card backgrounds, offering slight differentiation from the base. |

## Imagery

The imagery leans heavily on highly creative, often abstract or fantastical AI-generated art, product imagery, and stylized photography. These visuals are typically contained within cards with sharp or slightly rounded corners, presented as showcases rather than integrated into the background. The treatment is direct: full-color, high-impact visuals without heavy masking or complex overlaps. Icons are generally minimalist, outlined, and monochromatic, with the occasional full-color brand icon, acting as functional elements that don't compete with the generative art.

## Layout

The page primarily employs a full-bleed layout, where the dark background extends to the viewport edges. The hero section is characterized by oversized, warped typographic elements laid out in 3D perspective, making a bold statement. Content sections below often feature a centered stack text block followed by image-heavy layouts – frequently a grid of cards or alternating text+visual sections. Vertical rhythm is governed by distinct section gaps, creating clear breaks. Navigation is a minimalist top bar, sticky at some breakpoints, with ghosted menu items and prominent 'Log in' and 'Tutorial' buttons.

## Agent Prompt Guide

Quick Color Reference:
text: #ffffff
background: #000000
border: #e5e5e5
accent: #6e60ee
primary action: #ffffff (filled action)

Example Component Prompts:
1. Create a Hero Headline: 'YOUR IDEAS YOURS TO CREATE' using `leoSans` weight 900 at 165px, color #6e60ee, letter-spacing -3.3px, on a Midnight Void (#000000) background. Ensure 0.8 line height.
2. Create a Ghost Outlined Button: 'Start now' using `canvaSans` weight 400 at 16px, text color #ffffff, background transparent, border 1px solid #ffffff, and 60px border radius. Apply 6.75px vertical and 20.25px horizontal padding.
3. Create an Accent Product Card: displaying generative art. Set background to Luminous Green (#03e65b), 20.4375px border radius, with 16.875px padding. Inside, place a 'Product Title' using `canvaSans` weight 700 at 19px, color #0a0a0a.
4. Create a Secondary Text Link: 'Learn more' using `canvaSans` weight 400 at 14px, color Muted Ash (#999999), on a Midnight Void (#000000) background.

## Similar Brands

- **Midjourney** — Similar focus on AI-generated visuals, dark theme, and high-impact hero sections with generative art.
- **RunwayML** — Explores a dark-mode interface with vibrant accent colors in the creative AI space, emphasizing visually rich generative output.
- **Stability AI** — Shares a preference for dark interfaces with strong typographic statements and a focus on AI creativity.
- **Framer** — Employs an often dark-themed, UI-focused aesthetic with strong, distinct typography and selective use of color for interaction.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-void: #000000;
  --color-ghostly-gray: #e5e5e5;
  --color-off-black-text: #0a0a0a;
  --gradient-off-black-text: linear-gradient(rgb(10, 10, 10) 0%, rgba(37, 37, 37, 0.65) 100%);
  --color-pure-white: #ffffff;
  --color-subtle-surface: #353535;
  --color-muted-ash: #999999;
  --color-luminous-green: #03e65b;
  --color-deep-violet: #6e60ee;
  --color-electric-yellow: #ffc533;
  --color-vivid-crimson: #ff3386;
  --color-sunset-red: #ff5d4b;

  /* Typography — Font Families */
  --font-canvasans: 'canvaSans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-leosans: 'leoSans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ufficiodisplay: 'ufficioDisplay', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.1;
  --text-body: 14px;
  --leading-body: 1.2;
  --text-subheading: 18px;
  --leading-subheading: 1.25;
  --text-heading-sm: 22px;
  --leading-heading-sm: 0.8;
  --tracking-heading-sm: -0.22px;
  --text-heading: 39px;
  --leading-heading: 0.9;
  --tracking-heading: -0.78px;
  --text-heading-lg: 59px;
  --leading-heading-lg: 0.85;
  --tracking-heading-lg: -1.18px;
  --text-display: 165px;
  --leading-display: 0.8;
  --tracking-display: -3.3px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-bold: 700;
  --font-weight-extrabold: 800;
  --font-weight-black: 900;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-7: 7px;
  --spacing-10: 10px;
  --spacing-14: 14px;
  --spacing-17: 17px;
  --spacing-20: 20px;
  --spacing-27: 27px;
  --spacing-34: 34px;
  --spacing-41: 41px;
  --spacing-44: 44px;
  --spacing-47: 47px;
  --spacing-54: 54px;
  --spacing-61: 61px;
  --spacing-68: 68px;
  --spacing-135: 135px;
  --spacing-203: 203px;

  /* Layout */
  --section-gap: 34-37px;
  --card-padding: 17-20px;
  --element-gap: 7-10px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-lg: 8.4375px;
  --radius-2xl: 16.4375px;
  --radius-2xl-2: 20.4375px;
  --radius-full: 60px;
  --radius-full-2: 270px;

  /* Named Radii */
  --radius-tags: 270px;
  --radius-cards: 8.4375px;
  --radius-buttons: 60px;

  /* Surfaces */
  --surface-midnight-void: #000000;
  --surface-subtle-surface: #353535;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-void: #000000;
  --color-ghostly-gray: #e5e5e5;
  --color-off-black-text: #0a0a0a;
  --color-pure-white: #ffffff;
  --color-subtle-surface: #353535;
  --color-muted-ash: #999999;
  --color-luminous-green: #03e65b;
  --color-deep-violet: #6e60ee;
  --color-electric-yellow: #ffc533;
  --color-vivid-crimson: #ff3386;
  --color-sunset-red: #ff5d4b;

  /* Typography */
  --font-canvasans: 'canvaSans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-leosans: 'leoSans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ufficiodisplay: 'ufficioDisplay', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.1;
  --text-body: 14px;
  --leading-body: 1.2;
  --text-subheading: 18px;
  --leading-subheading: 1.25;
  --text-heading-sm: 22px;
  --leading-heading-sm: 0.8;
  --tracking-heading-sm: -0.22px;
  --text-heading: 39px;
  --leading-heading: 0.9;
  --tracking-heading: -0.78px;
  --text-heading-lg: 59px;
  --leading-heading-lg: 0.85;
  --tracking-heading-lg: -1.18px;
  --text-display: 165px;
  --leading-display: 0.8;
  --tracking-display: -3.3px;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-7: 7px;
  --spacing-10: 10px;
  --spacing-14: 14px;
  --spacing-17: 17px;
  --spacing-20: 20px;
  --spacing-27: 27px;
  --spacing-34: 34px;
  --spacing-41: 41px;
  --spacing-44: 44px;
  --spacing-47: 47px;
  --spacing-54: 54px;
  --spacing-61: 61px;
  --spacing-68: 68px;
  --spacing-135: 135px;
  --spacing-203: 203px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-lg: 8.4375px;
  --radius-2xl: 16.4375px;
  --radius-2xl-2: 20.4375px;
  --radius-full: 60px;
  --radius-full-2: 270px;
}
```

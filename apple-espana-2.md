# Apple (España) — Style Reference
> Crisp White Product Showcase: precise, direct, and unburdened by heavy UI.

**Theme:** light

The Apple (ES) design system creates a bright, product-focused canvas with a precise layout and subtle interactive cues. Predominantly white and dark gray neutrals form the structural backbone, punctuated by a vivid blue for primary actions and occasional, functional spot colors for highlighting feature categories. Typography is compact and sharp, favoring system fonts for clarity and efficiency. Components are lightweight, often ghosted or subtly filled, with generous corner radii that soften interaction points. The overall aesthetic is one of understated confidence, allowing product imagery to take center stage.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, elevated card surfaces, clean backdrop for product imagery |
| Surface Frost | `#f5f5f7` | `--color-surface-frost` | Secondary background surfaces for cards, badges, and section breaks, providing subtle visual separation from Canvas White |
| Interactive Grey | `#e2e2e5` | `--color-interactive-grey` | Background for secondary interactive elements like ghost buttons and navigation states |
| Text Primary | `#1d1d1f` | `--color-text-primary` | Neutral form states, badge text, and quiet UI feedback where color should stay understated. Do not promote it to the primary CTA color |
| Text Secondary | `#707070` | `--color-text-secondary` | Muted body text, navigation elements, and supportive information, creating clear hierarchy |
| Text Muted | `#474747` | `--color-text-muted` | Subtler text elements, small links, and footer text, for less prominent information |
| Action Blue | `#0071e3` | `--color-action-blue` | Primary call-to-action buttons (filled) and active navigation accents, signaling direct interaction |
| Link Blue | `#0066cc` | `--color-link-blue` | Default hyperlink color, for textual links and outlined interactive elements |
| Success Green | `#03aa49` | `--color-success-green` | Green outline accent for tags, dividers, and focused UI edges. Use as a supporting accent, not as a status color |
| Accent Violet | `#8668ff` | `--color-accent-violet` | Decorative accent for educational or special feature listings |
| Accent Orange | `#ed6300` | `--color-accent-orange` | Highlight color for specific feature callouts or numerical indicators |
| Accent Teal | `#00a1b3` | `--color-accent-teal` | Auxiliary accent color for feature differentiation |
| Accent Deep Green | `#03873a` | `--color-accent-deep-green` | Secondary green accent, particularly for outlined elements or subtle emphases |
| Watch Face Violet Gradient | `linear-gradient(135deg, rgb(145, 92, 240), rgb(255, 52, 52))` | `--color-watch-face-violet-gradient` | Product illustration accent reflecting device UI |
| Watch Face Blue Gradient | `linear-gradient(135deg, rgb(121, 50, 169), rgb(85, 143, 255))` | `--color-watch-face-blue-gradient` | Product illustration accent reflecting device UI |
| Watch Face Green Gradient | `linear-gradient(135deg, rgb(19, 154, 38), rgb(38, 150, 210))` | `--color-watch-face-green-gradient` | Product illustration accent reflecting device UI |
| Watch Face Red Gradient | `linear-gradient(135deg, rgb(254, 62, 49), rgb(218, 29, 17))` | `--color-watch-face-red-gradient` | Product illustration accent reflecting device UI |
| Watch Face Amber Gradient | `linear-gradient(135deg, rgb(224, 116, 0), rgb(178, 46, 255))` | `--color-watch-face-amber-gradient` | Product illustration accent reflecting device UI |

## Tokens — Typography

### SF Pro Text — Body text, navigation, buttons, and most functional interface elements. Its moderate scale and weights prioritize clarity and directness. · `--font-sf-pro-text`
- **Weights:** 400, 600
- **Sizes:** 12px, 14px, 17px, 20px, 44px
- **Line height:** 1.00, 1.18, 1.24, 1.33, 1.43, 1.47, 1.83
- **Letter spacing:** -0.0220em at 44px, -0.0190em at 20px, -0.0160em at 17px, -0.0100em at 14px, -0.0030em at 12px
- **OpenType features:** `"numr"`
- **Role:** Body text, navigation, buttons, and most functional interface elements. Its moderate scale and weights prioritize clarity and directness.

### SF Pro Display — Headlines and large display text. Its larger sizes and tighter tracking enhance impact and visual presence without sacrificing legibility. · `--font-sf-pro-display`
- **Weights:** 600
- **Sizes:** 21px, 24px, 28px, 39px, 64px, 76px, 80px, 96px
- **Line height:** 1.04, 1.06, 1.07, 1.14, 1.17, 1.33
- **Letter spacing:** -0.0190em at 96px, -0.0180em at 80px, -0.0150em at 76px, -0.0090em at 64px, -0.0050em at 39px, 0.0070em at 28px, 0.0090em at 24px, 0.0110em at 21px
- **OpenType features:** `"numr"`
- **Role:** Headlines and large display text. Its larger sizes and tighter tracking enhance impact and visual presence without sacrificing legibility.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.47 | -0.003px | `--text-caption` |
| body | 14px | 1.43 | -0.01px | `--text-body` |
| body-lg | 17px | 1.24 | -0.016px | `--text-body-lg` |
| subheading | 20px | 1.18 | -0.019px | `--text-subheading` |
| heading-lg | 24px | 1.17 | 0.009px | `--text-heading-lg` |
| display-md | 39px | 1.07 | -0.005px | `--text-display-md` |
| display-lg | 44px | 1 | -0.022px | `--text-display-lg` |
| display-xl | 64px | 1.06 | -0.009px | `--text-display-xl` |
| display-xxl | 76px | 1.04 | -0.015px | `--text-display-xxl` |
| display-xxxl | 96px | 1.04 | -0.019px | `--text-display-xxxl` |

## Tokens — Spacing & Shapes

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 8 | 8px | `--spacing-8` |
| 9 | 9px | `--spacing-9` |
| 10 | 10px | `--spacing-10` |
| 13 | 13px | `--spacing-13` |
| 14 | 14px | `--spacing-14` |
| 15 | 15px | `--spacing-15` |
| 18 | 18px | `--spacing-18` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 28 | 28px | `--spacing-28` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 80 | 80px | `--spacing-80` |
| 89 | 89px | `--spacing-89` |
| 160 | 160px | `--spacing-160` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 36px |
| cards | 28px |
| links | 10px |
| buttons | 980px |

### Layout

- **Section gap:** 89px
- **Card padding:** 28px
- **Element gap:** 10px

## Components

### Primary Filled Button
**Role:** main call to action

Features a solid Action Blue background (#0071e3) with Canvas White text (#ffffff). Has a generously rounded radius of 980px, with 8px vertical and 15px horizontal padding. This button is used for the most important actions, like 'Comprar'.

### Outline Text Button
**Role:** secondary action or navigation

Appears as plain Text Primary (#1d1d1f) with a transparent background and a 28px rounded corner radius. Used for '0 +' or functional navigation elements within components.

### Ghost Button
**Role:** tertiary action, subtle interaction

Has an Interactive Grey background (#e2e2e5) with Text Secondary (#707070) color for text, and a 36px radius. No border, used for less prominent interactive elements.

### Informational Card White
**Role:** content container

Uses a Canvas White (#ffffff) background with a 28px border-radius and no shadow. Contains visual and textual information.

### Informational Card Frost
**Role:** secondary content container

Uses a Surface Frost (#f5f5f7) background with a 28px border-radius and no shadow. Provides a subtle contrast to the primary white cards.

### Feature Badge
**Role:** inline descriptive tag

Uses a Surface Frost (#f5f5f7) background with Text Primary (#1d1d1f) or Text Secondary (#707070) text. Has no explicit padding from the data, but implies tight fit around content. Used for feature lists.

### Navigation Link
**Role:** global and local navigation

Appears as Text Secondary (#707070) or Text Muted (#474747) for standard links. Hover states may show Link Blue (#0066cc) borders, or backgrounds. Has no background and 0px radius by default.

## Do's and Don'ts

### Do
- Prioritize SF Pro Text for all body copy and interface labels at a 1.24x line height for crisp readability.
- Use SF Pro Display for all primary headings and display text, leveraging letter spacing adjustments like -0.0190em for 96px text to maintain visual density.
- Apply Canvas White (#ffffff) as the default page background and for primary content cards to create a bright, expansive canvas.
- Use Action Blue (#0071e3) exclusively for filled primary call-to-action buttons, ensuring a 980px border-radius for distinct pill-shaped interaction.
- Separate content sections with Surface Frost (#f5f5f7) or Canvas White (#ffffff) backgrounds, and delineate boundaries with a 28px elementGap often containing header elements.
- Employ a 28px border-radius for most interactive cards and display containers, providing a consistent soft geometry.
- Utilize specific chromatic accents (Accent Violet, Orange, Teal) for feature highlights and content categorization, using them sparingly for emphasis.

### Don't
- Avoid deep shadows or strong gradients on main UI elements; surfaces should largely remain flat and clean.
- Do not use highly saturated colors for large background areas or extensive text blocks; limit them to functional accents and product imagery.
- Do not use generic border-radii; adhere to the specified values: 28px for cards, 980px for primary buttons, and 36px for ghost buttons.
- Do not introduce decorative icons or illustrations that deviate from the minimalist, product-focused visual style.
- Avoid excessive spacing or overly spacious layouts; maintain a comfortable density by adhering to the 10px elementGap and 28px cardPadding.
- Do not use system-default blue for text links when a specific Link Blue (#0066cc) is defined, especially when an underlined state is implied.
- Do not use black for secondary text; default to Text Secondary (#707070) or Text Muted (#474747) for hierarchy.

## Imagery

The visual language is dominated by high-fidelity product photography, often featuring tight crops of Apple Watch devices against pure white or subtly gradated backgrounds. Imagery is typically isolated, full-bleed within its section, and avoids hard shadows or complex environments to keep the focus entirely on the product. Some shots show the product in a relatable but clean context (e.g., on a wrist on a clean table). Icons are minimal, monochromatic, and outline-based, serving a functional rather than decorative role. The overall density is high-impact product showcase, text-dominant in supporting sections.

## Layout

The page model is primarily a max-width contained layout alternating with full-bleed hero sections. The hero showcases product imagery full-width, with centered, large-scale headlines. Vertical rhythm is established through consistent section gaps (around 89px) with alternating background colors (Canvas White and Surface Frost). Content is typically arranged in left-aligned-text/right-aligned-image or vice versa patterns, or simple centered stacks of text and action elements. A prominent sticky header navigation bar remains at the top, offering global navigation and occasional call-to-action buttons. Grid layouts appear for features or product comparisons, utilizing multi-column structures.

## Agent Prompt Guide

Quick Color Reference:
text: #1d1d1f
background: #ffffff
border: #1d1d1f (for ghost elements) / #0066cc (for outlined links)
accent: #8668ff
primary action: #0071e3 (filled action)

Example Component Prompts:
1. Create a Primary Action Button: #0071e3 background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
3. Implement a Navigation Bar: Canvas White background. Left aligned 'Apple' logo. Right aligned nav items 'Tienda', 'Mac', 'iPad', 'iPhone', 'Watch', 'AirPods', 'TV y Casa', 'Entretenimiento', 'Accesorios', 'Soporte', each using Text Secondary (#707070) at 17px SF Pro Text weight 400, line height 1.33. Add an Action Blue (#0071e3) accent to the 'Watch' link, at 17px SF Pro Text weight 600.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-surface-frost: #f5f5f7;
  --color-interactive-grey: #e2e2e5;
  --color-text-primary: #1d1d1f;
  --color-text-secondary: #707070;
  --color-text-muted: #474747;
  --color-action-blue: #0071e3;
  --color-link-blue: #0066cc;
  --color-success-green: #03aa49;
  --color-accent-violet: #8668ff;
  --color-accent-orange: #ed6300;
  --color-accent-teal: #00a1b3;
  --color-accent-deep-green: #03873a;
  --color-watch-face-violet-gradient: #915cf0;
  --gradient-watch-face-violet-gradient: linear-gradient(135deg, rgb(145, 92, 240), rgb(255, 52, 52));
  --color-watch-face-blue-gradient: #7932a9;
  --gradient-watch-face-blue-gradient: linear-gradient(135deg, rgb(121, 50, 169), rgb(85, 143, 255));
  --color-watch-face-green-gradient: #139a26;
  --gradient-watch-face-green-gradient: linear-gradient(135deg, rgb(19, 154, 38), rgb(38, 150, 210));
  --color-watch-face-red-gradient: #fe3e31;
  --gradient-watch-face-red-gradient: linear-gradient(135deg, rgb(254, 62, 49), rgb(218, 29, 17));
  --color-watch-face-amber-gradient: #e07400;
  --gradient-watch-face-amber-gradient: linear-gradient(135deg, rgb(224, 116, 0), rgb(178, 46, 255));

  /* Typography — Font Families */
  --font-sf-pro-text: 'SF Pro Text', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sf-pro-display: 'SF Pro Display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.47;
  --tracking-caption: -0.003px;
  --text-body: 14px;
  --leading-body: 1.43;
  --tracking-body: -0.01px;
  --text-body-lg: 17px;
  --leading-body-lg: 1.24;
  --tracking-body-lg: -0.016px;
  --text-subheading: 20px;
  --leading-subheading: 1.18;
  --tracking-subheading: -0.019px;
  --text-heading-lg: 24px;
  --leading-heading-lg: 1.17;
  --tracking-heading-lg: 0.009px;
  --text-display-md: 39px;
  --leading-display-md: 1.07;
  --tracking-display-md: -0.005px;
  --text-display-lg: 44px;
  --leading-display-lg: 1;
  --tracking-display-lg: -0.022px;
  --text-display-xl: 64px;
  --leading-display-xl: 1.06;
  --tracking-display-xl: -0.009px;
  --text-display-xxl: 76px;
  --leading-display-xxl: 1.04;
  --tracking-display-xxl: -0.015px;
  --text-display-xxxl: 96px;
  --leading-display-xxxl: 1.04;
  --tracking-display-xxxl: -0.019px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-semibold: 600;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-9: 9px;
  --spacing-10: 10px;
  --spacing-13: 13px;
  --spacing-14: 14px;
  --spacing-15: 15px;
  --spacing-18: 18px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-80: 80px;
  --spacing-89: 89px;
  --spacing-160: 160px;

  /* Layout */
  --section-gap: 89px;
  --card-padding: 28px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-lg: 10px;
  --radius-3xl: 28px;
  --radius-3xl-2: 32px;
  --radius-3xl-3: 36px;
  --radius-full: 980px;

  /* Named Radii */
  --radius-tags: 36px;
  --radius-cards: 28px;
  --radius-links: 10px;
  --radius-buttons: 980px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-surface-frost: #f5f5f7;
  --color-interactive-grey: #e2e2e5;
  --color-text-primary: #1d1d1f;
  --color-text-secondary: #707070;
  --color-text-muted: #474747;
  --color-action-blue: #0071e3;
  --color-link-blue: #0066cc;
  --color-success-green: #03aa49;
  --color-accent-violet: #8668ff;
  --color-accent-orange: #ed6300;
  --color-accent-teal: #00a1b3;
  --color-accent-deep-green: #03873a;
  --color-watch-face-violet-gradient: #915cf0;
  --color-watch-face-blue-gradient: #7932a9;
  --color-watch-face-green-gradient: #139a26;
  --color-watch-face-red-gradient: #fe3e31;
  --color-watch-face-amber-gradient: #e07400;

  /* Typography */
  --font-sf-pro-text: 'SF Pro Text', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sf-pro-display: 'SF Pro Display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.47;
  --tracking-caption: -0.003px;
  --text-body: 14px;
  --leading-body: 1.43;
  --tracking-body: -0.01px;
  --text-body-lg: 17px;
  --leading-body-lg: 1.24;
  --tracking-body-lg: -0.016px;
  --text-subheading: 20px;
  --leading-subheading: 1.18;
  --tracking-subheading: -0.019px;
  --text-heading-lg: 24px;
  --leading-heading-lg: 1.17;
  --tracking-heading-lg: 0.009px;
  --text-display-md: 39px;
  --leading-display-md: 1.07;
  --tracking-display-md: -0.005px;
  --text-display-lg: 44px;
  --leading-display-lg: 1;
  --tracking-display-lg: -0.022px;
  --text-display-xl: 64px;
  --leading-display-xl: 1.06;
  --tracking-display-xl: -0.009px;
  --text-display-xxl: 76px;
  --leading-display-xxl: 1.04;
  --tracking-display-xxl: -0.015px;
  --text-display-xxxl: 96px;
  --leading-display-xxxl: 1.04;
  --tracking-display-xxxl: -0.019px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-9: 9px;
  --spacing-10: 10px;
  --spacing-13: 13px;
  --spacing-14: 14px;
  --spacing-15: 15px;
  --spacing-18: 18px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-80: 80px;
  --spacing-89: 89px;
  --spacing-160: 160px;

  /* Border Radius */
  --radius-lg: 10px;
  --radius-3xl: 28px;
  --radius-3xl-2: 32px;
  --radius-3xl-3: 36px;
  --radius-full: 980px;
}
```

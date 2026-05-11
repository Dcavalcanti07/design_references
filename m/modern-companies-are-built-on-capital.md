# Modern companies are built on Capital — Style Reference
> Midnight Ledger, Ember Accent

**Theme:** dark

Capital evokes a stark, sophisticated fintech experience operating in a dark, high-contrast environment. Monochrome canvases are punctuated by a single vivid red accent for calls to action, creating immediate emphasis. Typography is confident and generously sized, ensuring clarity against the deep backgrounds. Components maintain a minimal, almost invisible presence with subtle borders or ghost styles, letting the content and actions take center stage. The overall impression is one of restrained power and clear directives.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#000000` | `--color-midnight-ink` | Primary background for pages and main content areas, providing a dark, immersive canvas |
| Ash Canvas | `#efece6` | `--color-ash-canvas` | Alternating background sections, surface fills for cards, and primary text color on dark backgrounds, offering high contrast and readability |
| Charcoal Surface | `#1a1a1a` | `--color-charcoal-surface` | Subtle background for interactive elements and secondary container surfaces, maintaining a dark theme while offering visual progression |
| Onyx Shadow | `#131413` | `--color-onyx-shadow` | Deeper background or shadow color for elements requiring minimal elevation or separation from the primary dark canvas |
| Slate Text | `#bfbcb7` | `--color-slate-text` | Secondary text color, muted descriptive text, and subtle borders on lighter background sections |
| Cadet Grey | `#8e8c87` | `--color-cadet-grey` | Supportive text, helper text, and decorative borders, providing a softer contrast |
| Deep Graphite | `#302f2f` | `--color-deep-graphite` | Dark borders and separators for elevated surfaces and inverted UI. Do not promote it to the primary CTA color |
| Ember Glow | `#ed5145` | `--color-ember-glow` | Primary call-to-action buttons and critical interactive elements — a vivid red that provides immediate focus and urgency against dark neutrals |
| Crimson Shadow | `#82403a` | `--color-crimson-shadow` | Subtle tint for shadows or decorative accents, echoing the primary brand color in a more subdued tone |
| Sunset Blush | `#ff7a70` | `--color-sunset-blush` | Red supporting accent for decorative details and low-frequency emphasis. Do not promote it to the primary CTA color |

## Tokens — Typography

### Muoto — Primary typeface for all headings, body text, and interactive elements. Its range of weights and nuanced letter-spacing contributes to the distinct modern and authoritative feel, with subtle tracking for larger sizes. · `--font-muoto`
- **Substitute:** Open Sans
- **Weights:** 300, 400, 500
- **Sizes:** 12px, 14px, 16px, 20px, 28px, 32px, 72px, 90px, 115px
- **Line height:** 1.15, 1.20, 1.40, 1.43, 1.50, 1.67
- **Letter spacing:** -0.0200em, -0.0120em, -0.0100em
- **Role:** Primary typeface for all headings, body text, and interactive elements. Its range of weights and nuanced letter-spacing contributes to the distinct modern and authoritative feel, with subtle tracking for larger sizes.

### GT America Mono — Used for smaller functional text such as labels, metadata, and code-like snippets, providing a technical contrast with its monospace styling and generous letter-spacing for legibility. · `--font-gt-america-mono`
- **Substitute:** Space Mono
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.15, 1.60
- **Letter spacing:** 0.0800em
- **Role:** Used for smaller functional text such as labels, metadata, and code-like snippets, providing a technical contrast with its monospace styling and generous letter-spacing for legibility.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.5 | — | `--text-caption` |
| body-sm | 14px | 1.43 | — | `--text-body-sm` |
| body | 16px | 1.5 | -0.16px | `--text-body` |
| subheading | 20px | 1.4 | — | `--text-subheading` |
| heading-sm | 28px | 1.2 | — | `--text-heading-sm` |
| heading | 32px | 1.2 | — | `--text-heading` |
| heading-lg | 72px | 1.15 | -0.86px | `--text-heading-lg` |
| display | 90px | 1.15 | -1.08px | `--text-display` |
| display-xl | 115px | 1.15 | -0.02px | `--text-display-xl` |

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
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 3px |
| cards | 16px |
| buttons | 8px |
| ghostControls | 24px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| lg | `rgba(26, 26, 26, 0.4) 0px 8px 24px 0px` | `--shadow-lg` |
| lg-2 | `rgba(0, 0, 0, 0.2) 0px 6px 20px 0px` | `--shadow-lg-2` |

### Layout

- **Section gap:** 40px
- **Card padding:** 24px
- **Element gap:** 16px

## Components

### Accent Filled Button
**Role:** Primary call-to-action button

Solid Ember Glow (#ed5145) background with white text (#ffffff), 8px border-radius, and 8px vertical padding, 24px horizontal padding. A distinct visual indicator for critical actions.

### Subtle Outlined Button
**Role:** Secondary action button/link

Transparent background with Deep Graphite (#302f2f) 1px border and Charcoal Surface (#1a1a1a) text. Has 24px border-radius, and 10px vertical padding, 24px horizontal padding. Conveys clickable actions without visual dominance.

### Monochrome Ghost Button With Border
**Role:** Tertiary action with emphasis

Transparent background with a 1px border of Slate Text (#bfbcb7) and text in the same color. Features 24px border-radius, and 10px vertical padding, 24px horizontal padding. Used for less prominent actions that still require a clear boundary.

### Product Feature Card
**Role:** Content grouping for features or informational blocks

Ash Canvas (#efece6) background with 16px border-radius and no box shadow. Content internal padding varies, but cards themselves are unpadded on initial render, relying on internal component spacing. Used for displaying feature sets or related information.

### Mini Tag
**Role:** Informational labels or status indicators

Small background with 3px border-radius text labels. The specific background color (e.g., #1a1a1a) and text color (e.g., #efece6) can vary depending on context, often using the Charcoal Surface and Ash Canvas combination. Padded for minimal visual footprint.

## Do's and Don'ts

### Do
- Use Midnight Ink (#000000) as the default page background for sections, creating a dark, immersive experience.
- Apply Ash Canvas (#efece6) for primary body text on dark backgrounds, and as an alternating background to break up dark sections or for card surfaces.
- Reserve Ember Glow (#ed5145) exclusively for primary calls-to-action, such as filled buttons, to draw immediate attention.
- Employ Muoto at weight 300 for large headings and weight 400 or 500 for body text, maintaining legibility and a contemporary tone.
- Structure layouts with a consistent 40px `sectionGap` between major content blocks and a 16px `elementGap` for internal element separation.
- Utilize 8px border-radius for primary buttons and 16px for content cards, establishing clear visual boundaries and a measured softness.
- Introduce Charcoal Surface (#1a1a1a) for secondary container backgrounds or interactive UI elements within dark sections.

### Don't
- Do not introduce additional vibrant colors; maintain the high-contrast dark palette with red as the sole accent.
- Avoid heavy drop shadows on elevated elements; rely on subtle background color shifts or minimal box-shadows like rgba(26, 26, 26, 0.4) 0px 8px 24px 0px for depth.
- Do not deviate from the Muoto and GT America Mono font families; these are central to the brand's typographic identity.
- Avoid excessive use of outlined or ghost buttons when a primary action is available; prioritize clear calls to action with Ember Glow where intent is high.
- Do not use generic padding or spacing values; adhere to the 8px base unit and established tokens like 16px for element gaps.
- Never use text colors that create low contrast against the background; always ensure AAA contrast ratio, especially with light text on dark backgrounds.
- Avoid large imagery that breaks the UI's focus; imagery should be contained, functional, and support the content, not dominate.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Midnight Ink | `#000000` | Base page background and primary dark canvas. |
| 1 | Onyx Shadow | `#131413` | Slightly elevated dark surfaces, providing subtle differentiation from the base background. |
| 2 | Charcoal Surface | `#1a1a1a` | Secondary container backgrounds for interactive elements or distinct content blocks within dark sections. |
| 3 | Ash Canvas | `#efece6` | Light background for cards and alternating content sections, creating visual breaks and high contrast. |

## Elevation

- **Interactive Link/Button:** `rgba(26, 26, 26, 0.4) 0px 8px 24px 0px`
- **Interactive Link/Button (subtle):** `rgba(0, 0, 0, 0.2) 0px 6px 20px 0px`

## Layout

The page structure alternates between full-width dark sections and contained, often lighter, content blocks. The hero section is full-bleed black with a large, centered white headline, establishing immediate brand presence. Content sections frequently adopt a max-width layout, centered on the page body. A recurring pattern involves a two-column arrangement, often text-left/visual-right or vice-versa, or stacked content for features within distinct sections. Card grids, like one displaying founder images, are used to organize visual content. Vertical spacing between sections is generous at 40px, creating comfortable breathing room. A sticky bottom bar provides tertiary navigation and a prominent 'Start' button.

## Agent Prompt Guide

### Quick Color Reference
text: #efece6
background: #000000
border: #302f2f
accent: #ed5145
primary action: #ed5145 (filled action)

### 3-5 Example Component Prompts
1. Create a Hero Section: Midnight Ink (#000000) background. Heading 'Modern companies are built on Capital' using Muoto, size 90px, weight 400, color #efece6, letter-spacing -1.08px. Centered content with a 40px bottom sectionGap.
2. Create a Call-to-Action Button: 'Start' button with Ember Glow (#ed5145) background, color #ffffff, 8px border-radius, 8px vertical padding, 24px horizontal padding, using Muoto weight 500.
3. Create a Feature Card: Ash Canvas (#efece6) background, 16px border-radius, no shadow, with 16px internal padding. The card should display a heading using Muoto, size 20px, weight 400, color #000000 and body text using Muoto, size 14px, weight 400, color #bfbcb7.
4. Create a Ghost Navigation Link: Text 'Founders' with transparent background, 1px border in Deep Graphite (#302f2f), text color Ash Canvas (#efece6), 24px border-radius, 10px vertical padding, 24px horizontal padding, using Muoto weight 400.
5. Create a Small Code-like Label: 'AVAILABLE NOW' using GT America Mono, size 12px, weight 400, color Cadet Grey (#8e8c87), with 0.08em letter-spacing. Use a small Charcoal Surface (#1a1a1a) background with 3px border-radius and minimal padding (e.g., 6px horizontal, 4px vertical).

## Similar Brands

- **Stripe** — Deep dark mode UI with high contrast typography and a focus on clean, product-centric layouts.
- **Linear** — Minimalist UI, generous spacing, and a limited color palette that emphasizes content and functionality within a dark theme.
- **Rive** — Prominent dark backgrounds with white typography and a single strong accent color (often red or blue) for interactive elements.
- **Revolut** — Strong fintech identity with bold typography, dark backgrounds, and strategically placed vivid accent colors for key actions.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-ash-canvas: #efece6;
  --color-charcoal-surface: #1a1a1a;
  --color-onyx-shadow: #131413;
  --color-slate-text: #bfbcb7;
  --color-cadet-grey: #8e8c87;
  --color-deep-graphite: #302f2f;
  --color-ember-glow: #ed5145;
  --color-crimson-shadow: #82403a;
  --color-sunset-blush: #ff7a70;

  /* Typography — Font Families */
  --font-muoto: 'Muoto', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gt-america-mono: 'GT America Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --text-body-sm: 14px;
  --leading-body-sm: 1.43;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.16px;
  --text-subheading: 20px;
  --leading-subheading: 1.4;
  --text-heading-sm: 28px;
  --leading-heading-sm: 1.2;
  --text-heading: 32px;
  --leading-heading: 1.2;
  --text-heading-lg: 72px;
  --leading-heading-lg: 1.15;
  --tracking-heading-lg: -0.86px;
  --text-display: 90px;
  --leading-display: 1.15;
  --tracking-display: -1.08px;
  --text-display-xl: 115px;
  --leading-display-xl: 1.15;
  --tracking-display-xl: -0.02px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-64: 64px;
  --spacing-80: 80px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 24px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-sm: 3px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;

  /* Named Radii */
  --radius-tags: 3px;
  --radius-cards: 16px;
  --radius-buttons: 8px;
  --radius-ghostcontrols: 24px;

  /* Shadows */
  --shadow-lg: rgba(26, 26, 26, 0.4) 0px 8px 24px 0px;
  --shadow-lg-2: rgba(0, 0, 0, 0.2) 0px 6px 20px 0px;

  /* Surfaces */
  --surface-midnight-ink: #000000;
  --surface-onyx-shadow: #131413;
  --surface-charcoal-surface: #1a1a1a;
  --surface-ash-canvas: #efece6;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-ash-canvas: #efece6;
  --color-charcoal-surface: #1a1a1a;
  --color-onyx-shadow: #131413;
  --color-slate-text: #bfbcb7;
  --color-cadet-grey: #8e8c87;
  --color-deep-graphite: #302f2f;
  --color-ember-glow: #ed5145;
  --color-crimson-shadow: #82403a;
  --color-sunset-blush: #ff7a70;

  /* Typography */
  --font-muoto: 'Muoto', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gt-america-mono: 'GT America Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --text-body-sm: 14px;
  --leading-body-sm: 1.43;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.16px;
  --text-subheading: 20px;
  --leading-subheading: 1.4;
  --text-heading-sm: 28px;
  --leading-heading-sm: 1.2;
  --text-heading: 32px;
  --leading-heading: 1.2;
  --text-heading-lg: 72px;
  --leading-heading-lg: 1.15;
  --tracking-heading-lg: -0.86px;
  --text-display: 90px;
  --leading-display: 1.15;
  --tracking-display: -1.08px;
  --text-display-xl: 115px;
  --leading-display-xl: 1.15;
  --tracking-display-xl: -0.02px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-64: 64px;
  --spacing-80: 80px;

  /* Border Radius */
  --radius-sm: 3px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;

  /* Shadows */
  --shadow-lg: rgba(26, 26, 26, 0.4) 0px 8px 24px 0px;
  --shadow-lg-2: rgba(0, 0, 0, 0.2) 0px 6px 20px 0px;
}
```

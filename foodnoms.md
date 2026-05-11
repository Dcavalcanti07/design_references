# Foodnoms — Style Reference
> Vibrant Data Clarity – like a meticulously organized information dashboard lit by colorful indicator lights.

**Theme:** light

Foodnoms presents a vibrant, data-driven aesthetic, blending clean white spaces with a lively and diverse color palette. The immediate impression is one of approachable and precise digital tools, reinforced by the combination of a sharp, clear sans-serif with a more characterful, rounded custom typeface. The use of multiple vivid accent colors, particularly in charts and graphs within the simulated app screens, suggests a system designed for information visualization where clarity and differentiation are paramount, rather than a strictly minimalist or monochromatic approach.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| White Canvas | `#ffffff` | `--color-white-canvas` | Page backgrounds, card surfaces, primary text on dark accents. |
| Graphite Text | `#2f2f2f` | `--color-graphite-text` | Primary body text, darker UI elements, for strong contrast against White Canvas. |
| Raven Black | `#000000` | `--color-raven-black` | Headings, strong emphasis text, icons, ensures maximum legibility. |
| Warm Gray | `#f5f5f5` | `--color-warm-gray` | Subtle section dividers, light background for featured content blocks, provides slight visual separation from White Canvas. |
| Tangerine Accent | `#ff5406` | `--color-tangerine-accent` | Primary call-to-action buttons, active navigation states, strong visual cues. |
| Sunshine Orange | `#ff6d00` | `--color-sunshine-orange` | Secondary brand accent, used for specific data highlights or interactive elements within charts. |
| Crimson | `#ff3400` | `--color-crimson` | Alternative CTA background, hints at urgency or important interactions. |
| Vivid Green | `#00b33f` | `--color-vivid-green` | Success states, positive metrics in data visualizations, provides a clear semantic indicator. |
| Sky Blue | `#00a9dd` | `--color-sky-blue` | Informational indicators, general data visualization elements. |
| Deep Purple | `#5856de` | `--color-deep-purple` | Distinctive data point, often used for highlighting or unique categories in graphs, providing strong differentiation. |

## Tokens — Typography

### Aquawax Pro — Headlines and prominent display text, using a full set of stylistic alternates and ligatures to give a distinct, modern character. · `--font-aquawax-pro`
- **Substitute:** Montserrat Bold, Lato Bold
- **Weights:** 700
- **Sizes:** 18px, 22px, 30px, 60px
- **Line height:** 1.20, 1.40
- **OpenType features:** `"blwf" on, "cv03" on, "cv04" on, "cv09" on, "cv11" on, "dlig" on, "ss01" on, "ss02" on, "ss03" on, "ss07" on`
- **Role:** Headlines and prominent display text, using a full set of stylistic alternates and ligatures to give a distinct, modern character.

### Aquawax Pro — Long-form body text and primary links, ensuring readable paragraphs with a slightly generous line height. · `--font-aquawax-pro`
- **Substitute:** Montserrat Medium, Lato Medium
- **Weights:** 500
- **Sizes:** 17px, 20px
- **Line height:** 1.60, 1.80
- **OpenType features:** `"blwf" on, "cv03" on, "cv04" on, "cv09" on, "cv11" on, "dlig" on, "ss01" on, "ss02" on, "ss03" on`
- **Role:** Long-form body text and primary links, ensuring readable paragraphs with a slightly generous line height.

### Aquawax Pro — Subheadings, button text, and important inline labels, providing emphasis without the boldness of display text. · `--font-aquawax-pro`
- **Substitute:** Montserrat SemiBold, Lato SemiBold
- **Weights:** 600
- **Sizes:** 14px, 16px
- **Line height:** 1.20, 1.40
- **OpenType features:** `"blwf" on, "cv03" on, "cv04" on, "cv09" on, "cv11" on, "dlig" on, "ss01" on, "ss02" on, "ss03" on, "ss07" on`
- **Role:** Subheadings, button text, and important inline labels, providing emphasis without the boldness of display text.

### system-ui — System-level text like menu items, captions, and fine print, defaulting to an accessible and ubiquitous sans-serif. · `--font-system-ui`
- **Substitute:** sans-serif
- **Weights:** 
- **Sizes:** 
- **Line height:** 
- **Role:** System-level text like menu items, captions, and fine print, defaulting to an accessible and ubiquitous sans-serif.

### system-ui — Bolded system text, minor navigation elements, and emphasized inline text. · `--font-system-ui`
- **Substitute:** sans-serif
- **Weights:** 
- **Sizes:** 
- **Line height:** 
- **Role:** Bolded system text, minor navigation elements, and emphasized inline text.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.2 | — | `--text-caption` |
| subheading | 18px | 1.2 | — | `--text-subheading` |
| heading | 22px | 1.2 | — | `--text-heading` |
| heading-lg | 30px | 1.4 | — | `--text-heading-lg` |
| display | 60px | 1.2 | — | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 8px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 8 | 8px | `--spacing-8` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 56 | 56px | `--spacing-56` |
| 64 | 64px | `--spacing-64` |
| 96 | 96px | `--spacing-96` |

### Border Radius

| Element | Value |
|---------|-------|
| all | 26px |
| cards | 26px |
| buttons | 26px |

### Layout

- **Card padding:** 20px
- **Element gap:** 8px

## Components

### Primary Action Button
**Role:** Primary Calls to Action

Filled button with Tangerine Accent background (#ff5406), White Canvas text (#ffffff), 26px border radius, 12px vertical padding, 20px horizontal padding. Prominently guides user interaction.

### Secondary Action Button
**Role:** Secondary Calls to Action

Ghost button with transparent background, Graphite Text (#2f2f2f) text at 64% opacity, 26px border radius, 12px vertical padding, 20px horizontal padding. Provides a less dominant interaction point.

### Subtle Action Button
**Role:** Minor interactions or alternative options

Filled button with Warm Gray background (#f5f5f5), Tangerine Accent text (#ff5406) at 29% opacity, 26px border radius, 12px vertical padding, 20px horizontal padding. Offers a discrete interaction with brand color reinforcement.

### Hero Headline
**Role:** Main page title

Aquawax Pro Bold 60px, line-height 1.2, Raven Black. Center-aligned, immediately grabs attention.

### Hero Subhead
**Role:** Supporting text for hero headline

Aquawax Pro Medium 20px, line-height 1.8, Graphite Text. Provides additional context below the main headline.

### Icon Button
**Role:** Download links for App Store

Apple App Store icon, presented as a clickable button to download the app. No explicit styling beyond the standard icon design.

## Do's and Don'ts

### Do
- Always use the 26px border radius for all buttons, cards, and interactive containers.
- Prioritize Tangerine Accent (#ff5406) for primary call-to-action buttons to ensure immediate visibility.
- Maintain generous vertical spacing between sections (184-256px) for an airy, comfortable layout.
- Use Aquawax Pro Bold for all major headlines to leverage its distinctive character, with Raven Black (#000000) for maximum impact.
- Employ the full palette of vivid accent colors (Green, Sky Blue, Deep Purple) for information visualization within app-like interface elements to signify distinct categories or data points.
- Ensure all body text uses Aquawax Pro Medium weight 500 for optimal readability at default sizes.

### Don't
- Avoid using Tangerine Accent (#ff5406) or Sunshine Orange (#ff6d00) for purely decorative purposes; reserve them for interactive elements or key data highlights.
- Do not introduce sharp corners or low radii; the 26px radius is a signature shape element.
- Never use generic system fonts for headlines or body text; always prefer Aquawax Pro with its specified weights and feature settings.
- Do not deviate from the established spacing scale (8px, 12px, 20px, 24px, 32px, 40px, 48px, 56px, 64px, 96px); maintain consistent density.
- Avoid overusing bold weighting (Aquawax Pro Bold 700) outside of headlines; use DemiBold (600) or Medium (500) for subheadings and body emphasis.

## Imagery

The visual language is dominated by product screenshots, specifically in-app UI. These screenshots are presented as realistic phone mockups with slightly rounded edges, suggesting the app's functionality and interface are the primary visual content. The treatment is clean and contained, showcasing the UI clearly without distracting backgrounds (except for one instance of lifestyle photography visible behind an app interface). There are no abstract graphics or 3D renders, maintaining a focus on functional utility. Icons within the app are filled and minimal. The overall role of imagery is demonstrative: to showcase the product's features and user experience directly.

## Agent Prompt Guide

### Quick Color Reference
- **Text:** #000000 (Raven Black)
- **Background:** #ffffff (White Canvas)
- **CTA:** #ff5406 (Tangerine Accent)
- **Subtle Background:** #f5f5f5 (Warm Gray)
- **Body Text:** #2f2f2f (Graphite Text)

### 3-5 Example Component Prompts
1. **Create a Hero Section:** White Canvas background. Headline 'Lose Weight with Foodnoms' using Aquawax Pro Bold 60px, Raven Black. Subtext 'A simple, clear nutrition tracker for building healthy habits.' using Aquawax Pro Medium 20px, Graphite Text. Beneath, a primary action button 'Get the App' with Tangerine Accent #ff5406 background, White Canvas #ffffff text, 26px border radius, 12px vertical padding, 20px horizontal padding.
2. **Generate a Testimonial Card:** Warm Gray #f5f5f5 background, 26px border radius. Body text 'Foodnoms changed my life!' using Aquawax Pro Medium 17px, Graphite Text #2f2f2f. Small caption 'Jane Doe, Happy User' using system sans-serif 12px, Raven Black #000000.
3. **Design a Navigation Menu Item:** Text 'News' using system sans-serif 12px, Raven Black #000000. For an active state, add a Tangerine Accent #ff5406 underline that's 2px thick.
4. **Create a Download Button:** Background is Tangerine Accent #ff5406. Text 'Download ↗' is Aquawax Pro DemiBold 16px, White Canvas #ffffff. Button has 26px border radius and 12px vertical padding, 20px horizontal padding.
5. **Render a Section Headline:** Text 'As Featured By' using Aquawax Pro Bold 30px, Raven Black #000000, centered on a White Canvas background.

## Similar Brands

- **Calm** — Clean white backgrounds paired with vibrant accent colors for key interactive elements and data visualization.
- **Headspace** — Approachable feel through rounded elements and a focus on clarity in product imagery, specifically app interfaces.
- **Fitbod** — Emphasis on showcasing in-app UI through phone mockups as a primary method of communicating product value.
- **Linear (light mode)** — Minimalist overall aesthetic with a particular focus on typography and subtle use of accent colors for interaction.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-white-canvas: #ffffff;
  --color-graphite-text: #2f2f2f;
  --color-raven-black: #000000;
  --color-warm-gray: #f5f5f5;
  --color-tangerine-accent: #ff5406;
  --color-sunshine-orange: #ff6d00;
  --color-crimson: #ff3400;
  --color-vivid-green: #00b33f;
  --color-sky-blue: #00a9dd;
  --color-deep-purple: #5856de;

  /* Typography — Font Families */
  --font-aquawax-pro: 'Aquawax Pro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-system-ui: 'system-ui', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.2;
  --text-subheading: 18px;
  --leading-subheading: 1.2;
  --text-heading: 22px;
  --leading-heading: 1.2;
  --text-heading-lg: 30px;
  --leading-heading-lg: 1.4;
  --text-display: 60px;
  --leading-display: 1.2;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-96: 96px;

  /* Layout */
  --card-padding: 20px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-3xl: 26px;

  /* Named Radii */
  --radius-all: 26px;
  --radius-cards: 26px;
  --radius-buttons: 26px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-white-canvas: #ffffff;
  --color-graphite-text: #2f2f2f;
  --color-raven-black: #000000;
  --color-warm-gray: #f5f5f5;
  --color-tangerine-accent: #ff5406;
  --color-sunshine-orange: #ff6d00;
  --color-crimson: #ff3400;
  --color-vivid-green: #00b33f;
  --color-sky-blue: #00a9dd;
  --color-deep-purple: #5856de;

  /* Typography */
  --font-aquawax-pro: 'Aquawax Pro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-system-ui: 'system-ui', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.2;
  --text-subheading: 18px;
  --leading-subheading: 1.2;
  --text-heading: 22px;
  --leading-heading: 1.2;
  --text-heading-lg: 30px;
  --leading-heading-lg: 1.4;
  --text-display: 60px;
  --leading-display: 1.2;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-96: 96px;

  /* Border Radius */
  --radius-3xl: 26px;
}
```

# Hellotime — Style Reference
> White canvas, graphite precision

**Theme:** light

Hellotime projects a focused, clean interface with strong typographic hierarchy on a bright, minimalist canvas. Key interactions are highlighted by a deep, dark graphite, while subtle accent colors are reserved for internal product elements. Rounded corners provide a friendly contrast to the otherwise structured layout, maintaining an accessible and efficient feel. The overall impression is one of clarity and quiet authority, supporting a productivity application.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Primary page backgrounds, default surface color, subtle highlights and text for dark buttons |
| Fog Gray | `#f3f3f5` | `--color-fog-gray` | Secondary surface background for cards and prominent UI blocks, creating subtle visual separation |
| Border Ash | `#e1e2e5` | `--color-border-ash` | Hairline borders for containers, dividers, and subtle background shading for active components |
| Graphite Ink | `#151619` | `--color-graphite-ink` | Primary text, bold headlines, strong icon colors, and essential UI elements for high contrast |
| Steel Gray | `#7f8491` | `--color-steel-gray` | Secondary text, muted links, and subtle borders, providing hierarchical contrast for less prominent information |
| Slate Blue | `#c8cad0` | `--color-slate-blue` | Soft icon strokes, subtle dividers, and low-emphasis decorative details. Do not promote it to the primary CTA color |
| Charcoal Button | `#25272d` | `--color-charcoal-button` | Filled button backgrounds, creating strong, actionable calls to attention against the light canvas |
| Accent Green | `#059669` | `--color-accent-green` | Green outline accent for tags, dividers, and focused UI edges |
| Link Gray | `#363940` | `--color-link-gray` | Navigation text color |
| Button Border | `#b0b3bb` | `--color-button-border` | Medium-contrast borders, control outlines, and structural separators. Do not promote it to the primary CTA color |

## Tokens — Typography

### SF Pro Display — Primary headlines and display text, used for impact and visual hierarchy. Its varied weights allow for flexible emphasis. · `--font-sf-pro-display`
- **Substitute:** Inter
- **Weights:** 500, 600, 700
- **Sizes:** 24px, 40px, 48px, 64px, 80px
- **Line height:** 0.90, 1.00, 1.33, 1.50
- **Letter spacing:** normal
- **Role:** Primary headlines and display text, used for impact and visual hierarchy. Its varied weights allow for flexible emphasis.

### SF Pro Text — Body text, links, navigation, and detailed interface labels. Its extensive range of sizes and line heights supports a comfortable reading experience across different information densities. · `--font-sf-pro-text`
- **Substitute:** Inter
- **Weights:** 400, 500, 600, 700
- **Sizes:** 14px, 16px, 18px, 20px
- **Line height:** 0.80, 1.00, 1.14, 1.20, 1.33, 1.50, 1.60
- **Letter spacing:** normal
- **Role:** Body text, links, navigation, and detailed interface labels. Its extensive range of sizes and line heights supports a comfortable reading experience across different information densities.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 14px | 1.5 | — | `--text-caption` |
| body | 16px | 1.5 | — | `--text-body` |
| subheading | 24px | 1.33 | — | `--text-subheading` |
| heading-sm | 40px | 1 | — | `--text-heading-sm` |
| heading | 48px | 1 | — | `--text-heading` |
| heading-lg | 64px | 0.9 | — | `--text-heading-lg` |
| display | 80px | 0.9 | — | `--text-display` |

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
| 56 | 56px | `--spacing-56` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 120 | 120px | `--spacing-120` |
| 160 | 160px | `--spacing-160` |
| 240 | 240px | `--spacing-240` |

### Border Radius

| Element | Value |
|---------|-------|
| body | 12px |
| cards | 16px |
| links | 12px |
| buttons | 8px |
| headings | 20px |
| navigation | 8px |

### Layout

- **Section gap:** 40px
- **Card padding:** 32px
- **Element gap:** 16px

## Components

### Primary Filled Button
**Role:** Call-to-action button for initiating key user flows.

Background: Charcoal Button (#25272d), Text: Canvas White (#ffffff). Padding: 16px vertical, 16px horizontal. Border Radius: 8px. Font: SF Pro Text, weight 400.

### Ghost Button
**Role:** Secondary action or navigational link with minimal visual weight.

Background: transparent, Text: Graphite Ink (#151619). Padding: 8px vertical, 12px horizontal. No border radius. No border.

### Outlined Button
**Role:** Tertiary action with a clear boundary but less prominence than a filled button.

Background: Canvas White (#ffffff), Text: Graphite Ink (#151619). Border: 1px solid Button Border (#b0b3bb). Padding: 10px vertical, 10px horizontal. Border Radius: 8px.

### Content Card
**Role:** Container for grouped information, feedback, or features.

Background: Fog Gray (#f3f3f5). Padding: 32px all around. Border Radius: 16px. No shadow. Used for testimonials and feature blocks.

### Timeline Card
**Role:** Specific card variant for product UI, demonstrating a feature.

Background: Fog Gray (#f3f3f5). Padding: 56px vertical, 32px horizontal. Border Radius: 16px 0px 0px 16px. No shadow.

### Minimal Card
**Role:** Transparent container, often for layout purposes without strong visual separation.

Background: transparent. No padding, no border radius, no shadow.

## Do's and Don'ts

### Do
- Prioritize Graphite Ink (#151619) for all primary text and headlines to maintain high contrast with light backgrounds.
- Use Fog Gray (#f3f3f5) for distinct UI sections, such as cards or data display areas, maintaining visual separation from the Canvas White (#ffffff) page background.
- Apply 16px border radius to all content cards and larger container elements, and 8px to buttons and navigation items for consistency.
- Reserve Accent Green (#059669) exclusively for small, functional highlights within product UI, not for primary actions or branding.
- Employ consistent 32px padding for content cards and 16px for button vertical padding.
- Use Charcoal Button (#25272d, with Canvas White text) for primary calls-to-action, ensuring they stand out visually.
- Maintain a clear visual hierarchy: SF Pro Display for headlines and SF Pro Text for all body copy and UI labels.

### Don't
- Do not introduce new saturated colors for interactive elements; rely on variations of Graphite Ink or Charcoal Button for primary interactions.
- Avoid arbitrary shadow usage; the design system emphasizes flat surfaces and clear typographic hierarchy over dimensional elevation.
- Do not deviate from the established border radii; larger elements use 16px, interactive elements use 8px, and some decorative use 12px or 20px.
- Do not use Accent Green (#059669) for anything other than specific, non-actionable highlights within the product interface.
- Avoid using multiple font sizes/weights for body text within the same paragraph; stick to SF Pro Text at 16px/400 for general body content.
- Do not use full-width sections without a maximum content width; center content within a defined max-width.
- Avoid bold text as a substitute for semantic headings; use appropriate SF Pro Display sizes and weights for titles.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas White | `#ffffff` | Base page background, light frames for main content areas. |
| 1 | Fog Gray | `#f3f3f5` | Secondary background for cards, feature blocks, and distinct content sections. |
| 2 | Border Ash | `#e1e2e5` | Very subtle background for hovered states or very light bordering elements; visually above Fog Gray but rarely a full surface. |

## Imagery

The site largely avoids decorative photography, focusing on product screenshots and minimalist icons. Product screenshots are contained within UI components, often featuring data visualizations on a white or light gray background, suggesting functional clarity. Icons are outlined, simple, and monochrome (Graphite Ink #151619), integrated directly into text. A few playful, stylized illustrations with thick outlines and simple forms (like the superhero mascot) offer brand personality without overwhelming the UI. Imagery serves an explanatory or functional role, product showcase, and is sparse relative to text.

## Layout

The page primarily uses a centered, max-width layout for content, though the exact max-width is not explicitly defined, it maintains generous horizontal padding. The hero section features a prominent, centered headline with a highlighted phrase over a clean white background. Sections alternate between full-width content blocks and more contained arrangements. Content commonly flows in 2-column text-left/visual-right or visual-left/text-right patterns, with ample vertical spacing (40px section gaps) between blocks. Testimonials are presented in a 2-column card grid. The navigation is a sticky top bar with left-aligned branding and right-aligned actions.

## Agent Prompt Guide

### Quick Color Reference
- text: #151619
- background: #ffffff
- border: #e1e2e5
- accent: #059669
- primary action: #25272d (filled action)

### 3-5 Example Component Prompts
1. Create a Primary Action Button: #25272d background, #f3f3f5 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Create a content card for a testimonial: Fog Gray background (#f3f3f5), 16px border-radius. Inside, body text '"Hellotime is the best capacity planning tool I have ever used"' using SF Pro Text 16px, Graphite Ink (#151619). Padding 32px all sides.
3. Create a navigation bar: Canvas White background, sticky at top. Left-aligned brand logo (use a placeholder icon), right-aligned Ghost Button with text 'About' (Graphite Ink text, transparent background, 8px vertical 12px horizontal padding).

## Similar Brands

- **Linear** — Shares a clean, minimalist aesthetic with high-contrast text on light backgrounds and subtle accent coloring for functional elements.
- **Superhuman** — Similar focus on clear typography, dense information display with distinct UI components, and a subtle but effective use of color for status/highlights.
- **Cron** — Employs an uncluttered interface, strong typographic systems, and a professional, yet approachable feel for productivity tools.
- **Pitch** — Exhibits a modern, intuitive design with a strong emphasis on clear content presentation, relying on a neutral palette with thoughtful color accents.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-fog-gray: #f3f3f5;
  --color-border-ash: #e1e2e5;
  --color-graphite-ink: #151619;
  --color-steel-gray: #7f8491;
  --color-slate-blue: #c8cad0;
  --color-charcoal-button: #25272d;
  --color-accent-green: #059669;
  --color-link-gray: #363940;
  --color-button-border: #b0b3bb;

  /* Typography — Font Families */
  --font-sf-pro-display: 'SF Pro Display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sf-pro-text: 'SF Pro Text', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.5;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 24px;
  --leading-subheading: 1.33;
  --text-heading-sm: 40px;
  --leading-heading-sm: 1;
  --text-heading: 48px;
  --leading-heading: 1;
  --text-heading-lg: 64px;
  --leading-heading-lg: 0.9;
  --text-display: 80px;
  --leading-display: 0.9;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-120: 120px;
  --spacing-160: 160px;
  --spacing-240: 240px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 32px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;

  /* Named Radii */
  --radius-body: 12px;
  --radius-cards: 16px;
  --radius-links: 12px;
  --radius-buttons: 8px;
  --radius-headings: 20px;
  --radius-navigation: 8px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-fog-gray: #f3f3f5;
  --surface-border-ash: #e1e2e5;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-fog-gray: #f3f3f5;
  --color-border-ash: #e1e2e5;
  --color-graphite-ink: #151619;
  --color-steel-gray: #7f8491;
  --color-slate-blue: #c8cad0;
  --color-charcoal-button: #25272d;
  --color-accent-green: #059669;
  --color-link-gray: #363940;
  --color-button-border: #b0b3bb;

  /* Typography */
  --font-sf-pro-display: 'SF Pro Display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sf-pro-text: 'SF Pro Text', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.5;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 24px;
  --leading-subheading: 1.33;
  --text-heading-sm: 40px;
  --leading-heading-sm: 1;
  --text-heading: 48px;
  --leading-heading: 1;
  --text-heading-lg: 64px;
  --leading-heading-lg: 0.9;
  --text-display: 80px;
  --leading-display: 0.9;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-120: 120px;
  --spacing-160: 160px;
  --spacing-240: 240px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
}
```

# Dollar Shave Club — Style Reference
> Bold utility, clear guidance

**Theme:** dark

Dollar Shave Club presents a bold, product-focused aesthetic built on a deep blue foundation. Vibrant brand colors like orange and maroon punctuate the interface, guiding attention to key actions and brand messaging, while a tightly defined typographic system ensures strong hierarchy. Components are direct and confident, featuring slight corner rounding and minimal elevation, allowing the strong color palette and product imagery to drive the visual experience.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Blue | `#142978` | `--color-midnight-blue` | Primary background, prominent text, card elements |
| Mahogany Red | `#82163f` | `--color-mahogany-red` | Accent for navigation states and specific content blocks |
| Action Orange | `#fe5000` | `--color-action-orange` | Primary call-to-action buttons, interactive highlights |
| Deep Space Blue | `#0a153c` | `--color-deep-space-blue` | Darker background variations, subtle interactive states |
| Crisp White | `#ffffff` | `--color-crisp-white` | Primary text, button text, crisp borders, page elements |
| Slate Gray | `#404040` | `--color-slate-gray` | Secondary text, dark internal borders, neutral button elements |
| Powder Blue | `#dbebf5` | `--color-powder-blue` | Background for information cards, subtle surface contrasts |
| Warm Cream | `#f5ecdf` | `--color-warm-cream` | Subtle background accents or section dividers |
| Light Gray | `#eeeeee` | `--color-light-gray` | Subtle borders, background accents for imagery |
| Platinum Gray | `#e3e3e3` | `--color-platinum-gray` | Divider lines, badge borders |
| Ash Gray | `#949596` | `--color-ash-gray` | Input borders, placeholder text |
| Ink Black | `#000000` | `--color-ink-black` | Heavy borders, strong outlines, occasional text |

## Tokens — Typography

### DSC Specter — Primary brand typeface for all headings, body text, buttons, and UI elements. Its strong, condensed character is key to the brand's direct and confident voice. · `--font-dsc-specter`
- **Substitute:** Montserrat, Open Sans
- **Weights:** 400, 600, 700, 800, 900
- **Sizes:** 12px, 14px, 15px, 16px, 18px, 20px, 24px, 32px, 40px, 52px
- **Line height:** 0.80, 1.00, 1.19, 1.20, 1.25, 1.29, 1.30, 1.33, 1.36, 1.50, 1.57, 1.80, 1.86
- **Letter spacing:** -0.0060em at 52px, 0.0120em at 40px, 0.0150em at 32px, 0.0250em at 24px, 0.0310em at 20px, 0.0330em at 18px, 0.0380em at 16px, 0.0400em at 15px, 0.0430em at 14px, 0.0440em at 12px
- **Role:** Primary brand typeface for all headings, body text, buttons, and UI elements. Its strong, condensed character is key to the brand's direct and confident voice.

### Gelica — Secondary typeface for navigation, input fields, and some body text, providing a complementary, slightly wider feel; particularly for all-caps navigation items to ensure legibility. · `--font-gelica`
- **Substitute:** Roboto, Lato
- **Weights:** 400, 700, 800
- **Sizes:** 12px, 14px, 16px
- **Line height:** 1.20, 1.40, 1.50, 1.80
- **Letter spacing:** 0.0250em at 16px, 0.0710em at 12px
- **Role:** Secondary typeface for navigation, input fields, and some body text, providing a complementary, slightly wider feel; particularly for all-caps navigation items to ensure legibility.

### GTStandard-M — GTStandard-M — detected in extracted data but not described by AI · `--font-gtstandard-m`
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.5
- **Role:** GTStandard-M — detected in extracted data but not described by AI

### Font Awesome 5 Pro — Font Awesome 5 Pro — detected in extracted data but not described by AI · `--font-font-awesome-5-pro`
- **Weights:** 300
- **Sizes:** 18px
- **Line height:** 1
- **Role:** Font Awesome 5 Pro — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.5 | 0.528px | `--text-caption` |
| body | 14px | 1.57 | 0.602px | `--text-body` |
| body-lg | 16px | 1.5 | 0.608px | `--text-body-lg` |
| subheading | 18px | 1.29 | 0.594px | `--text-subheading` |
| heading | 24px | 1.25 | 0.6px | `--text-heading` |
| heading-lg | 32px | 1.2 | 0.48px | `--text-heading-lg` |
| display | 52px | 0.8 | -0.312px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 5 | 5px | `--spacing-5` |
| 6 | 6px | `--spacing-6` |
| 7 | 7px | `--spacing-7` |
| 8 | 8px | `--spacing-8` |
| 10 | 10px | `--spacing-10` |
| 13 | 13px | `--spacing-13` |
| 15 | 15px | `--spacing-15` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 25 | 25px | `--spacing-25` |
| 28 | 28px | `--spacing-28` |
| 30 | 30px | `--spacing-30` |
| 40 | 40px | `--spacing-40` |
| 50 | 50px | `--spacing-50` |
| 60 | 60px | `--spacing-60` |
| 149 | 149px | `--spacing-149` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 4px |
| buttons | 5px 10px |
| default | 4px |

### Layout

- **Section gap:** 30px
- **Card padding:** 25px
- **Element gap:** 10px

## Components

### Primary Action Button
**Role:** Main call-to-action

Filled with Action Orange (#fe5000), white text (#ffffff), 5px border-radius, 10px vertical and 20px horizontal padding. A more prominent variant uses 15px vertical and 80px horizontal padding and 4px radius.

### Ghost Button
**Role:** Secondary action that needs less emphasis

Transparent background, Slate Gray (#404040) text and border, no border-radius (0px), 0px padding. Used for subtle interactions like 'Add' or within navigation.

### Navigation Button
**Role:** Top-level navigation items

Deep Space Blue (#0a153c) background, white text (#ffffff), 4px border-radius, 2px vertical and 7px horizontal padding. Used for the segmented 'Men's' / 'Women's' navigation.

### Information Card (Powder Blue)
**Role:** Presenting product features or bundles

Powder Blue (#dbebf5) background, 0px border-radius, 25px padding on all sides, no shadow. Content within uses Midnight Blue (#142978) for primary text.

### Plain Card (Transparent)
**Role:** Flexible content container without visual emphasis

Transparent background, 0px border-radius, 0px padding, no shadow. Adaptable for various content blocks like product listings.

### Text Input (Transparent)
**Role:** Form fields without a distinct background

Transparent background, Slate Gray (#404040) text, no border-radius, 0px padding, a light subtle border in #404040 with 8% opacity. Used for search inputs.

### Text Input (White Background)
**Role:** Standard form input fields

White background (#ffffff), Slate Gray (#404040) text, 4px border-radius, 10px vertical and 40px horizontal padding. Prominently used for search.

### Badge (White)
**Role:** Small informational tags

White background (#ffffff), Slate Gray (#404040) text, 4px border-radius, 10px padding, 4px right margin. Often used with icon for count.

### Badge (Platinum Border)
**Role:** Indicating quantity or status

Transparent background, Platinum Gray (#e3e3e3) border, 4px border-radius. Padding and text color typically inherited from context.

## Do's and Don'ts

### Do
- Use Midnight Blue (#142978) as the primary background for content sections to maintain visual depth and brand consistency.
- Apply Action Orange (#fe5000) exclusively for primary calls-to-action and critical interactive elements.
- Prioritize DSC Specter for all headings and body text, varying weights (400-900) to establish clear typographic hierarchy.
- Ensure all buttons use a border-radius of either 5px or 4px for a consistent, subtle softness.
- Maintain a clear elementGap of 10px between inline interactive elements and form fields.
- Utilize Mahogany Red (#82163f) sparingly, primarily for navigation highlights or specific brand messages.
- Leverage Powder Blue (#dbebf5) for card backgrounds to visually differentiate information blocks without adding visual weight.

### Don't
- Do not use generic gray tones for button backgrounds; all functional buttons should adopt Action Orange (#fe5000) or Deep Space Blue (#0a153c) for variant actions.
- Avoid excessive use of shadows; most components should remain flat to emphasize the bold color palette.
- Do not introduce new font families; adhere strictly to DSC Specter and Gelica for all text.
- Refrain from using Crisp White (#ffffff) as a primary background for large sections unless it's a dedicated hero or a very light content spot contrasting a dark dominant mode.
- Do not deviate from the established spacing scale; maintain 10px for element gaps and 25px for card padding to keep a comfortable density.
- Never use achromatic blacks or dark grays for primary text on dark backgrounds; always use Crisp White (#ffffff) for readability.
- Avoid outlining primary action buttons; the design system strongly favors filled Action Orange (#fe5000) for emphasis.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Deep Space Blue Canvas | `#0a153c` | Base page background or subtle alternative for dark sections. |
| 2 | Midnight Blue Section | `#142978` | Standard background for prominent content blocks and main areas. |
| 3 | Powder Blue Card | `#dbebf5` | Background for product or information cards, providing visual separation. |

## Imagery

This site features a mix of product photography and stylized lifestyle imagery. Product shots are typically tight crops, often on solid backgrounds (Powder Blue or white), showcasing the items clearly rather than in use. Lifestyle images, when present, tend to be candid and dynamic, with warm lighting and a slightly desaturated color treatment, aiming for authenticity. Illustrations are abstract and organic, using brand colors like Action Orange and a pastel purple for decorative flair. Icons are outlined, with a moderate stroke weight, and primarily use Action Orange or Crisp White, contrasting against the dark backgrounds. Imagery density is moderate, used to break up text sections and highlight product benefits.

## Layout

The page primarily uses a full-bleed layout for background colors, creating distinct horizontal sections. Content within these sections is often centered within an implied max-width container, especially for headings and feature blocks. The hero section is a split layout: a commanding headline and call-to-action on the left, set against a predominantly white or light background, paired with a dynamic lifestyle image on the right which can be deeply saturated with brand colors. Subsequent sections alternate between Midnight Blue and brighter card backgrounds, often utilizing a 4-column grid for product features or a 3-column grid for 'How It Works' style content. Navigation is a sticky top bar with clearly segmented 'Men's' and 'Women's' options, reinforced by a secondary navigation for product categories.

## Agent Prompt Guide

Quick Color Reference:
text: #ffffff
background: #142978
border: #404040
accent: #82163f
primary action: #fe5000 (filled action)

Example Component Prompts:
1. Create a Primary Action Button: #fe5000 background, #404040 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
3. Create a navigation link: background transparent. Text 'Razors & Blades' using DSC Specter weight 600, size 16px, #ffffff. On hover, use Mahogany Red (#82163f) for the background with 4px radius and 13px right margin.

## Similar Brands

- **Harry's** — Clear, direct product focus with a bright, contrasting accent color against a more muted or neutral base.
- **Manscaped** — Bold, masculine color palette with strong visual hierarchy and a direct call-to-action focus in e-commerce.
- **Away (luggage)** — Product-heavy photography style, strong brand color usage for accents, and clean, legible typography for e-commerce.
- **Native (deodorant)** — Emphasis on product imagery, clean layouts, and functional use of vibrant brand colors populating a white or light background.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-blue: #142978;
  --color-mahogany-red: #82163f;
  --color-action-orange: #fe5000;
  --color-deep-space-blue: #0a153c;
  --color-crisp-white: #ffffff;
  --color-slate-gray: #404040;
  --color-powder-blue: #dbebf5;
  --color-warm-cream: #f5ecdf;
  --color-light-gray: #eeeeee;
  --color-platinum-gray: #e3e3e3;
  --color-ash-gray: #949596;
  --color-ink-black: #000000;

  /* Typography — Font Families */
  --font-dsc-specter: 'DSC Specter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gelica: 'Gelica', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gtstandard-m: 'GTStandard-M', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-font-awesome-5-pro: 'Font Awesome 5 Pro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: 0.528px;
  --text-body: 14px;
  --leading-body: 1.57;
  --tracking-body: 0.602px;
  --text-body-lg: 16px;
  --leading-body-lg: 1.5;
  --tracking-body-lg: 0.608px;
  --text-subheading: 18px;
  --leading-subheading: 1.29;
  --tracking-subheading: 0.594px;
  --text-heading: 24px;
  --leading-heading: 1.25;
  --tracking-heading: 0.6px;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: 0.48px;
  --text-display: 52px;
  --leading-display: 0.8;
  --tracking-display: -0.312px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;
  --font-weight-extrabold: 800;
  --font-weight-black: 900;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-13: 13px;
  --spacing-15: 15px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-25: 25px;
  --spacing-28: 28px;
  --spacing-30: 30px;
  --spacing-40: 40px;
  --spacing-50: 50px;
  --spacing-60: 60px;
  --spacing-149: 149px;

  /* Layout */
  --section-gap: 30px;
  --card-padding: 25px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 10px;

  /* Named Radii */
  --radius-cards: 4px;
  --radius-buttons: 5px 10px;
  --radius-default: 4px;

  /* Surfaces */
  --surface-deep-space-blue-canvas: #0a153c;
  --surface-midnight-blue-section: #142978;
  --surface-powder-blue-card: #dbebf5;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-blue: #142978;
  --color-mahogany-red: #82163f;
  --color-action-orange: #fe5000;
  --color-deep-space-blue: #0a153c;
  --color-crisp-white: #ffffff;
  --color-slate-gray: #404040;
  --color-powder-blue: #dbebf5;
  --color-warm-cream: #f5ecdf;
  --color-light-gray: #eeeeee;
  --color-platinum-gray: #e3e3e3;
  --color-ash-gray: #949596;
  --color-ink-black: #000000;

  /* Typography */
  --font-dsc-specter: 'DSC Specter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gelica: 'Gelica', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gtstandard-m: 'GTStandard-M', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-font-awesome-5-pro: 'Font Awesome 5 Pro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: 0.528px;
  --text-body: 14px;
  --leading-body: 1.57;
  --tracking-body: 0.602px;
  --text-body-lg: 16px;
  --leading-body-lg: 1.5;
  --tracking-body-lg: 0.608px;
  --text-subheading: 18px;
  --leading-subheading: 1.29;
  --tracking-subheading: 0.594px;
  --text-heading: 24px;
  --leading-heading: 1.25;
  --tracking-heading: 0.6px;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: 0.48px;
  --text-display: 52px;
  --leading-display: 0.8;
  --tracking-display: -0.312px;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-13: 13px;
  --spacing-15: 15px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-25: 25px;
  --spacing-28: 28px;
  --spacing-30: 30px;
  --spacing-40: 40px;
  --spacing-50: 50px;
  --spacing-60: 60px;
  --spacing-149: 149px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 10px;
}
```

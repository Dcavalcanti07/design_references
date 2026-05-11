# Apple — Style Reference
> Gallery White Precision

**Theme:** light

Apple's design system feels like precision engineering in a luminous white gallery. The interplay of crisp neutrals establishes a bright, expansive canvas, punctuated by a vibrant, yet restrained, blue as the sole chromatic accent. Sharp typography with subtle letter spacing and generous negative space conveys a sense of curated order, while highly rounded button capsules provide a soft, approachable contrast to the otherwise rigorous structure.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Global page background, default surface. |
| Porcelain | `#f5f5f7` | `--color-porcelain` | Secondary background color for sections and footers, creating subtle elevation shifts. |
| Graphite | `#1d1d1f` | `--color-graphite` | Primary text color for headlines, body copy, and most interactive elements, providing high contrast against light backgrounds. |
| Cool Gray | `#707070` | `--color-cool-gray` | Secondary text color for descriptive text, muted navigation items, and less prominent information. |
| Charcoal Black | `#000000` | `--color-charcoal-black` | Iconography, strong dividers, and occasionally for high-emphasis headings or links. |
| Subtle Frost | `#f4f8fb` | `--color-subtle-frost` | Observed in other fill, button color, other backgroundColor. Extracted usage does not support a distinct primary control color. |
| Border Gray | `#e2e2e5` | `--color-border-gray` | Subtle borders and dividers, indicating UI separation without being visually heavy. |
| Electric Blue | `#0071e3` | `--color-electric-blue` | Call-to-action buttons, active states, and focus indicators — the primary interactive accent. |
| Link Blue | `#0066cc` | `--color-link-blue` | Body text links and ghost button borders, providing a distinct interactive cue. |
| Highlight Blue | `#2997ff` | `--color-highlight-blue` | Hover states for links and icons, offering a brighter, more vivid interactive feedback. |

## Tokens — Typography

### SF Pro Display — Prominent display headings, imparting significance with precise tracking. · `--font-sf-pro-display`
- **Substitute:** system-ui
- **Weights:** 700
- **Sizes:** 21px, 28px, 40px, 56px
- **Line height:** 1.07, 1.10, 1.14, 1.19
- **Letter spacing:** -0.56
- **OpenType features:** `"numr"`
- **Role:** Prominent display headings, imparting significance with precise tracking.

### SF Pro Display — Large headings and critical product names, balancing legibility with visual impact. · `--font-sf-pro-display`
- **Substitute:** system-ui
- **Weights:** 400
- **Sizes:** 21px, 28px, 40px, 56px
- **Line height:** 1.07, 1.10, 1.14, 1.19
- **Letter spacing:** 0.29
- **OpenType features:** `"numr"`
- **Role:** Large headings and critical product names, balancing legibility with visual impact.

### SF Pro Text — Section titles, subheadings, and emphasized text segments, providing structural hierarchy with minimal weight. · `--font-sf-pro-text`
- **Substitute:** system-ui
- **Weights:** 600
- **Sizes:** 12px, 14px, 17px, 18px, 24px, 26px, 34px, 44px
- **Line height:** 1.00, 1.18, 1.24, 1.29, 1.33, 1.47, 1.50, 2.12, 2.41
- **Letter spacing:** -0.05
- **Role:** Section titles, subheadings, and emphasized text segments, providing structural hierarchy with minimal weight.

### SF Pro Text — Standard body text, descriptive labels, and form inputs, optimized for reading at various sizes. · `--font-sf-pro-text`
- **Substitute:** system-ui
- **Weights:** 400
- **Sizes:** 12px, 14px, 17px, 18px, 24px, 26px, 34px, 44px
- **Line height:** 1.00, 1.18, 1.24, 1.29, 1.33, 1.47, 1.50, 2.12, 2.41
- **Letter spacing:** -0.05
- **Role:** Standard body text, descriptive labels, and form inputs, optimized for reading at various sizes.

### SF Pro Text — Fine print, legal disclaimers, and secondary metadata, maintaining legibility at small sizes. · `--font-sf-pro-text`
- **Substitute:** system-ui
- **Weights:** 300
- **Sizes:** 12px, 14px, 17px, 18px, 24px, 26px, 34px, 44px
- **Line height:** 1.00, 1.18, 1.24, 1.29, 1.33, 1.47, 1.50, 2.12, 2.41
- **Letter spacing:** -0.05
- **Role:** Fine print, legal disclaimers, and secondary metadata, maintaining legibility at small sizes.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 2.41 | -0.13px | `--text-caption` |
| body-sm | 14px | 1.29 | -0.19px | `--text-body-sm` |
| subheading | 18px | 1.33 | -0.18px | `--text-subheading` |
| heading | 24px | 1.19 | -0.26px | `--text-heading` |
| heading-lg | 40px | 1.1 | 0.44px | `--text-heading-lg` |
| display | 56px | 1.07 | -0.56px | `--text-display` |

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
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 56 | 56px | `--spacing-56` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 999px |
| cards | 0px |
| buttons | 980px |
| formElements | 11px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| xl | `rgba(0, 0, 0, 0.22) 3px 5px 30px 0px` | `--shadow-xl` |

### Layout

- **Section gap:** 70-114px
- **Card padding:** 15px
- **Element gap:** 10px

## Components

### Primary Filled Button
**Role:** Call to action button

Solid Electric Blue background (#0071e3) with Canvas White text, featuring a 'pill' shape with 980px border-radius and 11px vertical, 21px horizontal padding.

### Ghost Button - Blue Text
**Role:** Secondary action button

Transparent background with Link Blue text (#0066cc), rounded with a 980px border-radius and 11px vertical, 21px horizontal padding.

### Default Header Button
**Role:** Navigation button

Transparent background with Graphite text (#1d1d1f), no border-radius (0px), and no explicit padding, relying on inherent text spacing for interaction.

### Region Selector Button
**Role:** Informational button

Subtle Frost background (#f4f8fb) with Graphite text (#1d1d1f), slightly rounded with an 11px border-radius, and 0px vertical, 14px horizontal padding.

### Standard Content Card
**Role:** Content container

Transparent background with 0px border-radius and no box shadow, designed to house content seamlessly within the layout without explicit visual framing. Padding is 0px.

### Elevated Image Card
**Role:** Promotional content card

Transparent background with 0px border-radius, featuring a subtle shadow (rgba(0, 0, 0, 0.22) 3px 5px 30px 0px) for depth, typically containing product imagery.

### Top Navigation Link
**Role:** Primary navigation item

Transparent background with Graphite text (#1d1d1f) at SF Pro Text Regular 12px, with generous 8px vertical padding and 0px horizontal padding, to allow ample tap target.

### Footer Section Heading
**Role:** Information architecture heading

Graphite text (#1d1d1f) at SF Pro Text Semibold 12px, providing clear categorization within the footer with a 5px top margin.

## Do's and Don'ts

### Do
- Use Electric Blue (#0071e3) exclusively for primary call-to-action buttons to maintain visual focus.
- Apply 980px border-radius to all interactive buttons for a consistent rounded aesthetic.
- Prioritize SF Pro Display for large, impactful headlines, using its specific letter spacing values like -0.56px at 56px.
- Maintain a clear visual hierarchy with Graphite (#1d1d1f) for main text and Cool Gray (#707070) for secondary information.
- Use Canvas White (#ffffff) as the dominant background color to ensure a bright and expansive feel.
- Separate content sections with subtle background shifts to Porcelain (#f5f5f7), rather than heavy dividers or shadows.
- Ensure a horizontal padding of 21px for all primary action buttons for comfortable sizing.

### Don't
- Do not use saturated blues for non-interactive elements; reserve them for direct user engagement.
- Avoid using custom shadows or borders on standard content cards, as they are meant to be seamless.
- Do not vary letter spacing for body text; maintain the specified SF Pro Text tracking values for legibility.
- Refrain from using color to indicate states like success or error; rely on iconography or structured messaging instead.
- Do not introduce additional font families; adhere strictly to SF Pro Text and SF Pro Display.
- Avoid small, precise radii (e.g., 4px) for interactive elements; stick to the highly rounded 980px for buttons or 11px for contained inputs.
- Never use excessive decorative elements or heavy gradients that would detract from the clean, systematic aesthetic.

## Imagery

The visual language predominantly features high-quality product photography, often isolated on pure white or light grey backgrounds to showcase detail without distraction. Photography is usually full-bleed across sections to immerse the user. Iconography is monochromatic and minimalist, often thin-stroked, serving as UI enhancers rather than decorative elements. The overall impression is one of product-focused clarity and premium presentation, conveying a sense of aspiration and innovation through the products themselves.

## Layout

The page structure uses a contained, centered layout for most content, with a max-width for textual information, but product showcase sections frequently break out into full-bleed photography. The hero section often combines a centered headline with full-width product imagery. Section rhythm is created through alternating a base Canvas White (#ffffff) with Porcelain (#f5f5f7) background bands, maintaining consistent vertical spacing. Content is primarily arranged in single-column stacks for main headlines and descriptive text, often transitioning to a two-column text-left/image-right or image-left/text-right pattern for feature presentations. Navigation is a sticky top bar with clearly segmented product categories and utility icons on the far right.

## Agent Prompt Guide

primary action: #0071e3 (filled action)
Create a Primary Action Button: #0071e3 background, #f4f8fb text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.

## Similar Brands

- **Google** — Dominant white/light backgrounds with a singular, vivid accent color used sparingly for interactive elements and highlights.
- **Stripe** — Clean, spacious layouts with a focus on sharp typography, subtle neutral palettes, and deliberate use of a single accent color for calls to action.
- **Figma** — Emphasis on system fonts (like SF Pro or similar), clear information hierarchy, and a restrained use of color to define interactive states, all within a stark white or light gray UI.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-porcelain: #f5f5f7;
  --color-graphite: #1d1d1f;
  --color-cool-gray: #707070;
  --color-charcoal-black: #000000;
  --color-subtle-frost: #f4f8fb;
  --color-border-gray: #e2e2e5;
  --color-electric-blue: #0071e3;
  --color-link-blue: #0066cc;
  --color-highlight-blue: #2997ff;

  /* Typography — Font Families */
  --font-sf-pro-display: 'SF Pro Display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sf-pro-text: 'SF Pro Text', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 2.41;
  --tracking-caption: -0.13px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.29;
  --tracking-body-sm: -0.19px;
  --text-subheading: 18px;
  --leading-subheading: 1.33;
  --tracking-subheading: -0.18px;
  --text-heading: 24px;
  --leading-heading: 1.19;
  --tracking-heading: -0.26px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: 0.44px;
  --text-display: 56px;
  --leading-display: 1.07;
  --tracking-display: -0.56px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
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
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;

  /* Layout */
  --section-gap: 70-114px;
  --card-padding: 15px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-lg-2: 11px;
  --radius-full: 980px;
  --radius-full-2: 999px;

  /* Named Radii */
  --radius-tags: 999px;
  --radius-cards: 0px;
  --radius-buttons: 980px;
  --radius-formelements: 11px;

  /* Shadows */
  --shadow-xl: rgba(0, 0, 0, 0.22) 3px 5px 30px 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-porcelain: #f5f5f7;
  --color-graphite: #1d1d1f;
  --color-cool-gray: #707070;
  --color-charcoal-black: #000000;
  --color-subtle-frost: #f4f8fb;
  --color-border-gray: #e2e2e5;
  --color-electric-blue: #0071e3;
  --color-link-blue: #0066cc;
  --color-highlight-blue: #2997ff;

  /* Typography */
  --font-sf-pro-display: 'SF Pro Display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sf-pro-text: 'SF Pro Text', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 2.41;
  --tracking-caption: -0.13px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.29;
  --tracking-body-sm: -0.19px;
  --text-subheading: 18px;
  --leading-subheading: 1.33;
  --tracking-subheading: -0.18px;
  --text-heading: 24px;
  --leading-heading: 1.19;
  --tracking-heading: -0.26px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: 0.44px;
  --text-display: 56px;
  --leading-display: 1.07;
  --tracking-display: -0.56px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-lg-2: 11px;
  --radius-full: 980px;
  --radius-full-2: 999px;

  /* Shadows */
  --shadow-xl: rgba(0, 0, 0, 0.22) 3px 5px 30px 0px;
}
```

# Flowers For Society — Style Reference
> Organic Modernity — grounded, yet forward-looking

**Theme:** light

Flowers For Society employs a vibrant, optimistic aesthetic, designed to evoke connection with nature and purpose. It pairs a crisp white canvas with a single dominant 'Deep Cobalt' blue, used prominently for interactive elements, text, and borders, establishing a strong brand identity. Typography is bold and confident, utilizing custom serifs for display and approachable sans-serifs for body text, creating a balanced hierarchy. Components feature soft, rounded edges, suggesting organic forms and approachability, with a focus on clear, unembellished functionality.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| White Canvas | `#ffffff` | `--color-white-canvas` | Page backgrounds, card surfaces, form input fills, and button text |
| Deep Cobalt | `#203b90` | `--color-deep-cobalt` | Primary brand color. Used for CTA buttons, active links, primary headings, borders, and input focus states. It projects authority and trust |
| Muted Indigo | `#7989bc` | `--color-muted-indigo` | Subtle borders and decorative accents within broader elements, indicating a softer interaction or separation |
| Ink Black | `#000000` | `--color-ink-black` | Primary body text, icons, and some input text, providing high contrast against light backgrounds |
| Pale Ash | `#f2f2f2` | `--color-pale-ash` | Section backgrounds and footer background, providing a subtle visual break from the main white canvas |
| Charcoal Border | `#1b1b1b` | `--color-charcoal-border` | Subtle border color, used for ghost buttons or other non-primary outlines |

## Tokens — Typography

### Soehne — Primary sans-serif for body text, navigation items, and button labels. It maintains readability with generous letter-spacing, supporting the comfortable density. · `--font-soehne`
- **Substitute:** system-ui
- **Weights:** 400, 700
- **Sizes:** 11px, 14px, 16px, 18px
- **Line height:** 1.20, 1.30, 1.40, 1.50, 1.80
- **Letter spacing:** -0.03em at 18px, 0.04em at 16px, 0.05em at 14px, 0.06em at 11px
- **Role:** Primary sans-serif for body text, navigation items, and button labels. It maintains readability with generous letter-spacing, supporting the comfortable density.

### Integral — Distinctive custom serif for headings and display text. Its condensed, strong presence and tight line-height create impactful statements. · `--font-integral`
- **Substitute:** serif
- **Weights:** 400
- **Sizes:** 13px, 15px, 18px, 35px, 37px, 45px, 52px
- **Line height:** 0.92, 1.00, 1.10, 1.28
- **Letter spacing:** 0.01em at 13-15px, 0.03-0.04em at 18px, 0.07em at 52px
- **Role:** Distinctive custom serif for headings and display text. Its condensed, strong presence and tight line-height create impactful statements.

### Arial — Fallback and utilitarian text where a common system font is appropriate, primarily for small body text or links. · `--font-arial`
- **Substitute:** sans-serif
- **Weights:** 400, 700
- **Sizes:** 14px
- **Line height:** 1.20
- **Role:** Fallback and utilitarian text where a common system font is appropriate, primarily for small body text or links.

### Nunito-Sans-Klaviyo-Hosted — Used for input text and some button labels, providing a softer, more rounded sans-serif alternative to Soehne. · `--font-nunito-sans-klaviyo-hosted`
- **Substitute:** Nunito Sans
- **Weights:** 400, 700
- **Sizes:** 18px, 20px
- **Line height:** 1.00, 1.20
- **Role:** Used for input text and some button labels, providing a softer, more rounded sans-serif alternative to Soehne.

### GTStandard-M — Specific instances of emphasized text, potentially for decorative statements or unique sections. · `--font-gtstandard-m`
- **Substitute:** sans-serif
- **Weights:** 400
- **Sizes:** 18px
- **Line height:** 1.50
- **Letter spacing:** 0.0330em
- **Role:** Specific instances of emphasized text, potentially for decorative statements or unique sections.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 11px | 1.4 | — | `--text-caption` |
| body-sm | 14px | 1.4 | — | `--text-body-sm` |
| body | 16px | 1.4 | — | `--text-body` |
| body-lg | 18px | 1.4 | — | `--text-body-lg` |

## Tokens — Spacing & Shapes

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 5 | 5px | `--spacing-5` |
| 6 | 6px | `--spacing-6` |
| 8 | 8px | `--spacing-8` |
| 10 | 10px | `--spacing-10` |
| 12 | 12px | `--spacing-12` |
| 13 | 13px | `--spacing-13` |
| 15 | 15px | `--spacing-15` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 30 | 30px | `--spacing-30` |
| 40 | 40px | `--spacing-40` |
| 50 | 50px | `--spacing-50` |
| 52 | 52px | `--spacing-52` |
| 60 | 60px | `--spacing-60` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 4px |
| inputs | 41px |
| buttons | 41px |
| smallElements | 4px |

### Layout

- **Section gap:** 50px
- **Card padding:** 30px
- **Element gap:** 5px

## Components

### Primary Filled Button
**Role:** Main call-to-action button, conveying primary intent.

Filled with Deep Cobalt (#203b90), text in White Canvas (#ffffff), with a highly rounded border-radius of 41px. Padding provides ample space around the text (e.g., 0px vertical, 30px horizontal).

### Ghost Button
**Role:** Secondary action or navigational button, designed to be less prominent.

Transparent background with text and a thin border in Deep Cobalt (#203b90). No explicit border-radius, often appearing as a text link with an implied hover state. Padding is minimal (e.g., 0px).

### Large Rounded Heading Button
**Role:** Specialized large button for key conceptual actions or navigation between sections.

Filled with Deep Cobalt (#203b90), text in White Canvas (#ffffff), with an exaggerated border-radius of 60px. This button is visually distinct for emphasis.

### Text Input (Rounded)
**Role:** Standard form input for user data entry.

White Canvas (#ffffff) background, text in Ink Black (#000000). Features a thin Deep Cobalt (#203b90) border and a 41px border-radius. Generous internal padding (e.g., 15px vertical, 15px left, 98px right for possible affordance) for a soft, inviting feel.

### Text Input (Subtle)
**Role:** Alternative simple text input, potentially for smaller forms or searches.

White Canvas (#ffffff) background, text in Ink Black (#000000). Defined by a thin Deep Cobalt (#203b90) bottom border and a minimal 4px border-radius. Text has 16px left padding.

### Navigation Link
**Role:** Top-level navigation items within the header.

Soehne text in Ink Black (#000000) or Deep Cobalt (#203b90) at 14px, typically with padding of 12px or 13px around them to create spacious, clickable areas.

### Product Card
**Role:** Display individual products within a grid or list.

Implicitly uses White Canvas (#ffffff) background with content padded by 30px. Features a subtle 4px border-radius, suggesting a contained, clean product display area without heavy visual elements.

## Do's and Don'ts

### Do
- Prioritize Deep Cobalt (#203b90) for all primary actions and key interactive elements, ensuring brand recognition.
- Use Soehne for body text and navigation, maintaining tight letter-spacing for consistency, e.g., 0.0560em at 14px.
- Apply a 41px border-radius universally to primary buttons and form inputs for a soft, consistent brand feel.
- Employ Integral for all headings, using its various sizes with tight line-heights (e.g., 0.92-1.28) to create strong visual statements.
- Maintain a clear visual hierarchy by limiting prominent colors to Deep Cobalt (#203b90) and utilizing White Canvas (#ffffff) and Pale Ash (#f2f2f2) for backgrounds.
- Ensure generous internal padding for components, using values like 15px vertical padding for inputs and 30px horizontal for buttons for comfort and legibility.
- Leverage the Pale Ash (#f2f2f2) background for section breaks to provide visual breathing room between content blocks.

### Don't
- Avoid using multiple vibrant chromatic colors; limit the accent palette primarily to Deep Cobalt (#203b90).
- Do not introduce sharp, unrounded corners on interactive elements; maintain a consistent rounded aesthetic (41px, 4px, or 60px).
- Refrain from using thin, light fonts for headings; Integral, weight 400, should carry the visual weight.
- Do not clutter components with excessive borders or shadows; keep them clean and subtly defined, often by just one color.
- Avoid tight spacing between elements; use the established elementGap of 5px and cardPadding of 30px to maintain comfortable density.
- Do not use generic system fonts when custom fonts like Soehne and Integral are available for text and headings.
- Avoid heavy drop shadows or complex elevation; the design relies more on color contrast and clear surface separation.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Page Canvas | `#ffffff` | The primary background for most page content and interactive elements. |
| 2 | Section Background | `#f2f2f2` | Used to differentiate major content sections, providing subtle visual breaks. |

## Imagery

The visual language is split between high-quality product photography and evocative macro-level shots of nature. Photography is product-focused, showcasing footwear in natural, often vibrant, outdoor settings (like sneakers surrounded by pink daisies). Product images are often well-lit, providing clear detail. Illustration style is limited to functional icons that are typically monochromatic (Ink Black or Deep Cobalt), outlined, and simple. Imagery functions both decoratively to set a peaceful, natural atmosphere and explanatorily to highlight product features. The density is moderate, with images playing a significant role in hero sections and product features but balancing with text-dominant areas.

## Layout

The page primarily uses a max-width contained layout, though the hero section can be full-bleed with a product image centered over a natural background. The hero often features a prominent heading and a central call-to-action. Content sections typically alternate between subtle Pale Ash (#f2f2f2) and White Canvas (#ffffff) backgrounds, creating a clear vertical rhythm. Content arrangement frequently uses large, centered headings, followed by text and image blocks, sometimes in two-column layouts. A common pattern is stacked information with comfortable vertical spacing (sectionGap 50px). Navigation is a clean top bar with core links and user icons, appearing sticky or fixed-position.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #ffffff
border: #203b90
accent: no distinct accent color
primary action: #203b90 (filled action)

Example Component Prompts:
1. Create a primary call-to-action button: background #203b90, text #ffffff, 41px border-radius, padding 0px vertical and 30px horizontal, using Soehne font weight 400 at 16px.
2. Design a rounded text input field: background #ffffff, text #000000, border #203b90, 41px border-radius, 15px padding all around. Placeholder text should be Deep Cobalt #203b90.
3. Build a main heading: Integral font, weight 400, size 52px, line-height 0.92, letter-spacing 0.0770em, color #000000, centered on a White Canvas background.
4. Create a navigation link: Soehne font, weight 400, size 14px, line-height 1.2, letter-spacing 0.0550em, color #000000, with 12px vertical and 12px horizontal padding. On hover, the text color should become Deep Cobalt #203b90.

## Similar Brands

- **New Balance** — A focus on clean product photography in natural settings with a strong brand accent color on a neutral background.
- **Allbirds** — Emphasis on sustainable materials, soft rounded shapes, and an approachable, nature-inspired visual identity with limited color palettes.
- **Veja** — Clean, product-centric e-commerce design with a strong commitment to ethical production, reflected in a straightforward, honest visual style.
- **Everlane** — Minimalist aesthetic with high-quality photography and a focus on transparency, utilizing a limited color palette and clear typography.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-white-canvas: #ffffff;
  --color-deep-cobalt: #203b90;
  --color-muted-indigo: #7989bc;
  --color-ink-black: #000000;
  --color-pale-ash: #f2f2f2;
  --color-charcoal-border: #1b1b1b;

  /* Typography — Font Families */
  --font-soehne: 'Soehne', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-integral: 'Integral', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-nunito-sans-klaviyo-hosted: 'Nunito-Sans-Klaviyo-Hosted', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gtstandard-m: 'GTStandard-M', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.4;
  --text-body-sm: 14px;
  --leading-body-sm: 1.4;
  --text-body: 16px;
  --leading-body: 1.4;
  --text-body-lg: 18px;
  --leading-body-lg: 1.4;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-13: 13px;
  --spacing-15: 15px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-30: 30px;
  --spacing-40: 40px;
  --spacing-50: 50px;
  --spacing-52: 52px;
  --spacing-60: 60px;

  /* Layout */
  --section-gap: 50px;
  --card-padding: 30px;
  --element-gap: 5px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-3xl: 41px;
  --radius-full: 60px;

  /* Named Radii */
  --radius-cards: 4px;
  --radius-inputs: 41px;
  --radius-buttons: 41px;
  --radius-smallelements: 4px;

  /* Surfaces */
  --surface-page-canvas: #ffffff;
  --surface-section-background: #f2f2f2;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-white-canvas: #ffffff;
  --color-deep-cobalt: #203b90;
  --color-muted-indigo: #7989bc;
  --color-ink-black: #000000;
  --color-pale-ash: #f2f2f2;
  --color-charcoal-border: #1b1b1b;

  /* Typography */
  --font-soehne: 'Soehne', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-integral: 'Integral', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-nunito-sans-klaviyo-hosted: 'Nunito-Sans-Klaviyo-Hosted', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gtstandard-m: 'GTStandard-M', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.4;
  --text-body-sm: 14px;
  --leading-body-sm: 1.4;
  --text-body: 16px;
  --leading-body: 1.4;
  --text-body-lg: 18px;
  --leading-body-lg: 1.4;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-13: 13px;
  --spacing-15: 15px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-30: 30px;
  --spacing-40: 40px;
  --spacing-50: 50px;
  --spacing-52: 52px;
  --spacing-60: 60px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-3xl: 41px;
  --radius-full: 60px;
}
```

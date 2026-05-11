# Essie Wine — Style Reference
> Vintage Bookplate Serenity — a quiet, reserved aesthetic like an aged paper with delicate script.

**Theme:** light

Essie Wine cultivates a classic, understated visual identity through a sparse palette of off-whites, murky greens, and a singular, muted ochre. Its spacious, text-dominant layout employs a traditional serif for its primary messaging, harmoniously paired with a legible sans-serif for functional text. Components are minimalist, often appearing as subtle underlines or text-only elements, reflecting a design ethos of quiet sophistication rather than overt display. The overall aesthetic feels like a well-worn book or a vintage poster—timeless and unpretentious.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Inkwell | `#062d32` | `--color-inkwell` | Primary text, headers, navigation links, input borders, ghost button borders. This dark, desaturated teal establishes a grounded, vintage feel |
| Parchment | `#e9e9e2` | `--color-parchment` | Canvas background for primary content sections, subtle text elements |
| White Linen | `#ffffff` | `--color-white-linen` | Page backgrounds in select sections, pristine component surfaces |
| Old Gold | `#aa9e54` | `--color-old-gold` | Background for specific sections like forms or featured content. Its moderate saturation provides a warm, earthy contrast |
| Dusty Rose | `#c9a9b5` | `--color-dusty-rose` | Secondary background sections, footer background. A muted, desaturated rose that contributes to the vintage atmosphere |
| Slate Grain | `#767676` | `--color-slate-grain` | Default input border color for a subtle, unobtrusive form |
| Deep Pewter | `#344b52` | `--color-deep-pewter` | Subtle border color for links and decorative accents |
| Pitch Black | `#000000` | `--color-pitch-black` | Highest contrast text, borders for ghost components, decorative lines |

## Tokens — Typography

### BasicCommercial LT Com Roman — Main navigation, larger headings, and body text. Its clean, condensed sans-serif provides modern legibility against the serif. · `--font-basiccommercial-lt-com-roman`
- **Substitute:** Inter
- **Weights:** 300, 400
- **Sizes:** 19px, 38px, 49px
- **Line height:** 1.16, 1.18, 1.20
- **Letter spacing:** 0.003, 0.004, 0.008, 0.026
- **Role:** Main navigation, larger headings, and body text. Its clean, condensed sans-serif provides modern legibility against the serif.

### Adobe Caslon Pro — Primary headings, subheadings, and featured text blocks. The traditional serif conveys authority and elegance, creating an established, classic brand feel. Its lightness at 300 weight is distinctive, suggesting understated professionalism. · `--font-adobe-caslon-pro`
- **Substitute:** Libre Baskerville
- **Weights:** 300
- **Sizes:** 49px
- **Line height:** 1.18
- **Letter spacing:** 0.003
- **Role:** Primary headings, subheadings, and featured text blocks. The traditional serif conveys authority and elegance, creating an established, classic brand feel. Its lightness at 300 weight is distinctive, suggesting understated professionalism.

### Elementa — Paragraph text, small labels, and detailed content. A highly readable sans-serif for practical information. · `--font-elementa`
- **Substitute:** Graphik
- **Weights:** 300, 400
- **Sizes:** 16px, 19px
- **Line height:** 1.00, 1.16
- **Letter spacing:** 0.008, 0.042
- **Role:** Paragraph text, small labels, and detailed content. A highly readable sans-serif for practical information.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 19px | 1.18 | — | `--text-caption` |
| body-sm | 38px | 1.18 | — | `--text-body-sm` |
| body | 49px | 1.18 | — | `--text-body` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** spacious

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 8 | 8px | `--spacing-8` |
| 20 | 20px | `--spacing-20` |
| 40 | 40px | `--spacing-40` |
| 68 | 68px | `--spacing-68` |
| 100 | 100px | `--spacing-100` |
| 136 | 136px | `--spacing-136` |

### Border Radius

| Element | Value |
|---------|-------|
| inputs | 0px |
| buttons | 0px |

### Layout

- **Section gap:** 136px
- **Card padding:** 27px
- **Element gap:** 23px

## Components

### Ghost Text Button
**Role:** Default interactive element for navigation and actions.

Text in Inkwell (#062d32), no background, no border, with a padding of 27px symmetrically. Underlined on hover or active state with Inkwell (#062d32).

### Underlined Call-to-Action
**Role:** Semantic action for submissions or primary interactions.

Text in Pitch Black (#000000), no background, with a 1px solid Pitch Black (#000000) border bottom, 0px border radius, and 27px padding. Uses the 'Elementa' font at 16px, weight 400.

### Form Input Field
**Role:** Standard input for user data collection.

No background, text in Pitch Black (#000000), with a 1px solid Slate Grain (#767676) border bottom. No padding or border radius. Focus state changes border to Inkwell (#062d32). Placeholder text uses the same style but in a lighter shade.

### Form Input Field (Active)
**Role:** Active state for form inputs.

No background, text in Inkwell (#062d32), with a 1px solid Inkwell (#062d32) border bottom. No padding or border radius.

### Content Section (Old Gold)
**Role:** Distinct background for specific content blocks like forms.

Background color Old Gold (#aa9e54), typically with text in Pitch Black (#000000), with generous vertical padding (e.g., 100-150px) to provide ample breathing room.

### Content Section (Dusty Rose)
**Role:** Background for hero sections or footers.

Background color Dusty Rose (#c9a9b5), with text in Inkwell (#062d32), featuring flexible padding that allows for large illustrations or minimal content.

## Do's and Don'ts

### Do
- Prioritize Elementa for all body text and small labels at 16px, weight 400, for practical legibility.
- Use Adobe Caslon Pro at 49px (weight 300) for major headings to establish a classic, refined tone.
- Implement Inkwell (#062d32) as the primary accent for active states, link underlines, and subtle borders.
- Maintain a monochromatic palette for most UI elements, reserving Old Gold (#aa9e54) and Dusty Rose (#c9a9b5) for distinct background sections.
- Apply 27px padding uniformly to all buttons for consistent visual weight.
- Ensure all interactive elements and underlines use `0px` radius for a sharp, traditional finish.
- Utilize white Linen (#ffffff) and Parchment (#e9e9e2) as the default canvas colors, switching based on content hierarchy or section distinction.

### Don't
- Avoid using saturated or bright colors beyond the defined Old Gold (#aa9e54) for any UI elements.
- Do not introduce sharp shadows or significant elevation; the design relies on flat, understated surfaces.
- Refrain from using any border radius on buttons, inputs, or interactive elements; all corners should be sharp 0px.
- Do not break the line-based input field style with filled backgrounds or alternative border treatments.
- Avoid crowding elements; ensure generous spacing (e.g., 23px element gap, 136px section gap) to maintain an airy, considered layout.
- Do not use highly decorative fonts or vary font weights beyond 300 and 400; stick to the defined Elementa, Adobe Caslon Pro, and BasicCommercial families.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Parchment | `#e9e9e2` | Primary content canvas, providing a soft background for text-heavy sections. |
| 2 | Old Gold | `#aa9e54` | Elevated background for distinct content blocks, like forms or highlighted features, offering a warm contrast. |
| 3 | Dusty Rose | `#c9a9b5` | Background for less textual, more illustrative elements such as the hero or footer, serving a decorative role. |
| 4 | White Linen | `#ffffff` | Background for pristine, clean content areas or specific nested components. |

## Imagery

The visual language relies heavily on line illustrations, primarily monochrome (Inkwell #062d32 on pale backgrounds). These illustrations are detailed, depicting scenes with human figures and architectural elements, often in a whimsical, narrative style. They are generally contained compositions, not full-bleed, and serve a decorative and atmospheric role rather than explanatory. There are no photographs or product shots. Icons are simple, outlined, sharing the same stroke weight as the illustrations. Imagery plays a significant role in creating a specific, charming brand mood, complementing the text-heavy layout without overwhelming it.

## Layout

The page structure favors a max-width contained layout, though specific hero sections or illustrations can expand. The hero pattern features a centered, large-scale line illustration against a Dusty Rose (#c9a9b5) background, with minimal text, setting an immediate atmospheric tone. Section rhythm alternates between Parchment (#e9e9e2) and Old Gold (#aa9e54) backgrounds, sometimes introducing White Linen (#ffffff). Content is typically arranged in centered stacks or simple two-column layouts for text-dominant areas. There is ample white space and consistent vertical spacing (136px for sections), creating a feeling of spaciousness. Navigation is a minimalist top bar with ghost text links.

## Agent Prompt Guide

### Quick Color Reference
text: #062d32
background: #e9e9e2
border: #062d32
accent: #aa9e54
primary action: #062d32 (outlined action border)

### 3-5 Example Component Prompts
1. Create an Outlined Primary Action: Transparent background, #062d32 border and text, 9999px radius, compact pill padding. Use it for the main CTA instead of a filled button.
3. Create a hero section: Background Dusty Rose (#c9a9b5). Centered large responsive line illustration. No text immediately visible, allowing the illustration to dominate. Ensure significant vertical padding top and bottom (e.g., 100px top, 150px bottom) to frame the illustration.

## Similar Brands

- **The Silverlake Wine** — Shares a sophisticated, minimal aesthetic with high contrast text against light backgrounds, emphasizing typography and curated imagery.
- **Typewolf** — Heavy reliance on serif and sans-serif typography for brand identity, with an understated color palette and focus on textual content.
- **Kinfolk Magazine** — Employs an editorial layout with ample white space, muted colors, and a blend of artisanal photography/illustration and classic typography.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-inkwell: #062d32;
  --color-parchment: #e9e9e2;
  --color-white-linen: #ffffff;
  --color-old-gold: #aa9e54;
  --color-dusty-rose: #c9a9b5;
  --color-slate-grain: #767676;
  --color-deep-pewter: #344b52;
  --color-pitch-black: #000000;

  /* Typography — Font Families */
  --font-basiccommercial-lt-com-roman: 'BasicCommercial LT Com Roman', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-adobe-caslon-pro: 'Adobe Caslon Pro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-elementa: 'Elementa', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 19px;
  --leading-caption: 1.18;
  --text-body-sm: 38px;
  --leading-body-sm: 1.18;
  --text-body: 49px;
  --leading-body: 1.18;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-8: 8px;
  --spacing-20: 20px;
  --spacing-40: 40px;
  --spacing-68: 68px;
  --spacing-100: 100px;
  --spacing-136: 136px;

  /* Layout */
  --section-gap: 136px;
  --card-padding: 27px;
  --element-gap: 23px;

  /* Named Radii */
  --radius-inputs: 0px;
  --radius-buttons: 0px;

  /* Surfaces */
  --surface-parchment: #e9e9e2;
  --surface-old-gold: #aa9e54;
  --surface-dusty-rose: #c9a9b5;
  --surface-white-linen: #ffffff;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-inkwell: #062d32;
  --color-parchment: #e9e9e2;
  --color-white-linen: #ffffff;
  --color-old-gold: #aa9e54;
  --color-dusty-rose: #c9a9b5;
  --color-slate-grain: #767676;
  --color-deep-pewter: #344b52;
  --color-pitch-black: #000000;

  /* Typography */
  --font-basiccommercial-lt-com-roman: 'BasicCommercial LT Com Roman', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-adobe-caslon-pro: 'Adobe Caslon Pro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-elementa: 'Elementa', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 19px;
  --leading-caption: 1.18;
  --text-body-sm: 38px;
  --leading-body-sm: 1.18;
  --text-body: 49px;
  --leading-body: 1.18;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-20: 20px;
  --spacing-40: 40px;
  --spacing-68: 68px;
  --spacing-100: 100px;
  --spacing-136: 136px;
}
```

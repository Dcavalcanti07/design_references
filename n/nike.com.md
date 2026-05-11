# Nike.com — Style Reference
> High-contrast arena with athletic curves.

**Theme:** light

Nike.com evokes a sharp, performance-driven aesthetic, grounded in a highly contrasting black-and-white palette. The dominant use of stark black typography against pristine white surfaces creates an immediate sense of clarity and authority, amplified by a compact spacing system that keeps elements close-knit. Key elements like primary buttons and navigation items feature generous 30px radii, introducing a subtle softness that contrasts with the otherwise angular, direct visual language, hinting at the athletic curves of their products.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Pitch Black | `#111111` | `--color-pitch-black` | Primary text, headings, outlines, icons, primary brand color. Establishes strong contrast and a sense of luxury. |
| Cloud White | `#ffffff` | `--color-cloud-white` | Page backgrounds, card surfaces, primary button background, prominent UI elements. Provides a clean, expansive canvas. |
| Alloy Gray | `#e5e5e5` | `--color-alloy-gray` | Subtle background for secondary sections and borders. Offers a slight textural shift from pure white. |
| Feather Gray | `#f5f5f5` | `--color-feather-gray` | Background for subtle accents like navigation hovers or specific button states. A very light, almost imperceptible shift from white. |
| Steel Gray | `#707072` | `--color-steel-gray` | Secondary text, muted links, subtle icons, inactive states. Provides hierarchy without being too light. |
| Pewter Gray | `#9e9ea0` | `--color-pewter-gray` | Placeholder text, disabled states, decorative strokes. The lightest functional gray. |
| Ignite Red | `#EE0005` | `--color-ignite-red` | Accent for urgent notifications or strong calls to action (though not prominently used in provided data, implied by token `--podium-cds-color-red-500`). |
| Blaze Orange | `#FF5000` | `--color-blaze-orange` | Accent for highlighting special offers or secondary calls to action (though not prominently used in provided data, implied by token `--podium-cds-color-orange-400`). |

## Tokens — Typography

### Helvetica Now Text — Primary text, body copy, navigation links, button labels. Weight 500 signals medium emphasis for navigation and smaller headings, while 400 is for general body content. This family is the workhorse of the system, maintaining legibility and a contemporary feel across all textual elements. · `--font-helvetica-now-text`
- **Substitute:** Arial, Helvetica, sans-serif
- **Weights:** 400, 500
- **Sizes:** 16px, 20px
- **Line height:** 1.50, 1.75
- **Letter spacing:** normal
- **Role:** Primary text, body copy, navigation links, button labels. Weight 500 signals medium emphasis for navigation and smaller headings, while 400 is for general body content. This family is the workhorse of the system, maintaining legibility and a contemporary feel across all textual elements.

### Helvetica Now Display — Secondary headings and larger button text. Used for smaller display headings, bridging the gap between body text and the largest display font, providing clear hierarchy. · `--font-helvetica-now-display`
- **Substitute:** Arial, Helvetica, sans-serif
- **Weights:** 500
- **Sizes:** 20px, 24px
- **Line height:** 1.20, 1.50
- **Letter spacing:** normal
- **Role:** Secondary headings and larger button text. Used for smaller display headings, bridging the gap between body text and the largest display font, providing clear hierarchy.

### Nike Futura ND — Hero headlines. This custom geometric sans-serif, with its powerful 76px size, provides a bold, iconic brand statement at grand scale. Its uniqueness drives brand recognition for major statements. · `--font-nike-futura-nd`
- **Substitute:** Arial, Helvetica, sans-serif
- **Weights:** 500
- **Sizes:** 76px
- **Line height:** 1.00
- **Letter spacing:** normal
- **Role:** Hero headlines. This custom geometric sans-serif, with its powerful 76px size, provides a bold, iconic brand statement at grand scale. Its uniqueness drives brand recognition for major statements.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.5 | — | `--text-caption` |
| body-sm | 14px | 1.75 | — | `--text-body-sm` |
| body | 16px | 1.75 | — | `--text-body` |
| subheading | 20px | 1.5 | — | `--text-subheading` |
| heading | 24px | 1.2 | — | `--text-heading` |
| display | 76px | 1 | — | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 8 | 8px | `--spacing-8` |
| 12 | 12px | `--spacing-12` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 36 | 36px | `--spacing-36` |
| 48 | 48px | `--spacing-48` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 0px |
| buttons | 30px |
| default | 8px |
| navItems | 30px |

### Layout

- **Section gap:** 48px
- **Card padding:** 0px
- **Element gap:** 8px

## Components

### Primary Filled Button
**Role:** Call to Action

Solid white background with Pitch Black (#111111) text and a 1px Pitch Black (#111111) border. The prominent 30px border-radius makes buttons feel distinct and softer than other UI elements. Padding is 6px vertical, 16px horizontal.

### Ghost Button
**Role:** Secondary Action

Transparent background with Pitch Black (#111111) text. No visible border or padding by default. Used for less prominent actions, blending seamlessly with the background.

### Circular Icon Button
**Role:** Navigation/Utility

White background with Pitch Black (#111111) icon/text. Features a 50% border-radius, creating perfect circles. Used for compact actions like search or favorites in the header.

### Feature Card
**Role:** Content Display

Transparent background, no border-radius. Features a large image, a Pitch Black (#111111) heading, and Steel Gray (#707072) body copy, with Ghost Buttons for action. No visible border or shadow, relying on imagery for visual separation.

### Product Tile
**Role:** Product Listing

Cloud White (#ffffff) background with a 1px Alloy Gray (#e5e5e5) border. No border-radius. Displays product images and Pitch Black (#111111) product names, used in structured grids.

## Do's and Don'ts

### Do
- Use Pitch Black (#111111) for all primary text, headings, and outlines to maintain high contrast and sophistication.
- Apply Cloud White (#ffffff) as the primary background for all page sections and card surfaces, ensuring visual spaciousness.
- Ensure primary action buttons feature 30px border-radius with 6px vertical and 16px horizontal padding.
- Implement a compact spacing system using 8px as the primary `elementGap` between UI elements.
- Utilize Nike Futura ND (or Arial as substitute) at 76px size and 1.0 lineHeight for all hero headlines to convey brand power.
- Divide content using subtle background shifts to Alloy Gray (#e5e5e5) for secondary sections instead of heavy borders or shadows.

### Don't
- Avoid using drop shadows or heavy box shadows, as the system relies on background color shifts and borders for depth.
- Do not deviate from the monochrome palette for functional UI elements; save branded colors for marketing accents only.
- Do not use generic system fonts when custom fonts like Helvetica Now Text/Display or Nike Futura ND are specified, as they are crucial for brand identity.
- Disregard the 30px radius for buttons and nav items except for specific utility components like circular buttons.
- Do not introduce large gaps or excessive padding; the design favors a compact, information-dense layout.
- Avoid using multiple bright, saturated colors for primary UI elements; reserve these for specific brand highlights or imagery if necessary.

## Imagery

The visual language is characterized by high-quality product photography, often shot with dramatic lighting against dark, sometimes black, backgrounds for hero sections, and on pristine white or simple colored backgrounds for product listings. When not product-focused, imagery features crisp action shots of athletes. Images are typically contained within rectangular frames with sharp edges or within grid structures, with no noticeable masking or complex overlapping. Icons are monochrome, often Pitch Black (#111111) on white, thin-stroked, and functional.

## Layout

The layout primarily uses a max-width contained grid for most content, though the hero section often leverages full-bleed imagery. The header is sticky and provides a minimal but clear global navigation. Sections alternate between prominent full-width visual statements (like the hero shoe image) and structured content blocks. Content arrangement frequently uses two-column or four-column card grids for features and product listings. Vertical spacing between logical sections appears consistent, creating a rhythmic flow down the page. The overall density is compact, ensuring visual information is readily available without excessive scrolling.

## Agent Prompt Guide

### Quick Color Reference
- Text (Primary): #111111 (Pitch Black)
- Background (Primary): #ffffff (Cloud White)
- Call to Action (Background): #ffffff (Cloud White)
- Call to Action (Text): #111111 (Pitch Black)
- Border (Default): #111111 (Pitch Black)
- Secondary Text: #707072 (Steel Gray)

### 3-5 Example Component Prompts
1. **Create a Hero Section:** Full-width hero section with a centered image. Overlay 'POTENCIA TOTAL' as a `display` heading in Pitch Black (#111111), followed by 'Siente la potencia de la unidad Air Zoom curvada completa. Da el máximo.' as `body` text in Pitch Black (#111111). Below a 'Comprar' (Primary Filled) button: background Cloud White (#ffffff), text Pitch Black (#111111), border Pitch Black (#111111), 30px radius, 6px 16px padding.
2. **Generate a Product Grid Card:** A card with a Cloud White (#ffffff) background, 0px radius, and a 1px Alloy Gray (#e5e5e5) border. Include a product image. Below the image, display 'Nike United' as `body` text weight 500 in Pitch Black (#111111). Follow with 'Creadas por atletas. Diseñadas para destacar.' as `body` text weight 400 in Steel Gray (#707072). Include two Ghost Buttons ('Comprar todo' and 'Comprar para niño/a') with Pitch Black (#111111) text, no background or border.
3. **Design a Global Navigation Item:** Use 'Novedad' as `body` text weight 500 in Pitch Black (#111111). On hover, background should be Feather Gray (#f5f5f5).
4. **Create a Footer Link:** Display 'Zapatillas de running en negro' as `body` text weight 400, color Steel Gray (#707072). There should be no specific background or border, and the component should fit into a list structure with an 8px element gap.

## Similar Brands

- **Adidas** — Both brands in the athletic apparel industry use high-contrast photography of products/athletes against neutral backgrounds, focusing on product dynamism.
- **Apple** — Shares a use of strong black and white contrast, minimal UI elements, high-quality product photography, and a sophisticated, modern typography choice for brand recognition.
- **lululemon** — Similar approach to high-quality product photography and clean, minimal layouts with ample negative space to highlight products.
- **Under Armour** — Focus on performance, often reflected in high-contrast product-centric layouts and bold typography, albeit with a slightly rougher edge than Nike.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-pitch-black: #111111;
  --color-cloud-white: #ffffff;
  --color-alloy-gray: #e5e5e5;
  --color-feather-gray: #f5f5f5;
  --color-steel-gray: #707072;
  --color-pewter-gray: #9e9ea0;
  --color-ignite-red: #EE0005;
  --color-blaze-orange: #FF5000;

  /* Typography — Font Families */
  --font-helvetica-now-text: 'Helvetica Now Text', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-helvetica-now-display: 'Helvetica Now Display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-nike-futura-nd: 'Nike Futura ND', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --text-body-sm: 14px;
  --leading-body-sm: 1.75;
  --text-body: 16px;
  --leading-body: 1.75;
  --text-subheading: 20px;
  --leading-subheading: 1.5;
  --text-heading: 24px;
  --leading-heading: 1.2;
  --text-display: 76px;
  --leading-display: 1;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-36: 36px;
  --spacing-48: 48px;

  /* Layout */
  --section-gap: 48px;
  --card-padding: 0px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-3xl: 24px;
  --radius-3xl-2: 30px;

  /* Named Radii */
  --radius-cards: 0px;
  --radius-buttons: 30px;
  --radius-default: 8px;
  --radius-navitems: 30px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-pitch-black: #111111;
  --color-cloud-white: #ffffff;
  --color-alloy-gray: #e5e5e5;
  --color-feather-gray: #f5f5f5;
  --color-steel-gray: #707072;
  --color-pewter-gray: #9e9ea0;
  --color-ignite-red: #EE0005;
  --color-blaze-orange: #FF5000;

  /* Typography */
  --font-helvetica-now-text: 'Helvetica Now Text', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-helvetica-now-display: 'Helvetica Now Display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-nike-futura-nd: 'Nike Futura ND', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --text-body-sm: 14px;
  --leading-body-sm: 1.75;
  --text-body: 16px;
  --leading-body: 1.75;
  --text-subheading: 20px;
  --leading-subheading: 1.5;
  --text-heading: 24px;
  --leading-heading: 1.2;
  --text-display: 76px;
  --leading-display: 1;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-36: 36px;
  --spacing-48: 48px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-3xl: 24px;
  --radius-3xl-2: 30px;
}
```

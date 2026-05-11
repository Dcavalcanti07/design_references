# Dock — Style Reference
> Digital workbench illuminated by electric blue. The experience is like working in a crisp, highly functional digital environment with precise tools.

**Theme:** light

This design system presents as a 'digital workbench' – a bright, well-organized interface designed for productivity. The prominent use of a vibrant, electric blue against a near-white background creates an energetic yet focused atmosphere. Subtle gray tints and soft shadows provide depth and separation, akin to tools neatly arranged on a clean workspace. The typography, featuring a custom sans-serif with nuanced letter-spacing, emphasizes clarity and directness in communication.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Inkwell | `#121722` | `--color-inkwell` | Primary text, deep backgrounds on dark UI elements, key UI borders. |
| Cloud White | `#ffffff` | `--color-cloud-white` | Page backgrounds, card surfaces, button text. Provides a clean, expansive canvas. |
| Horizon Gray | `#faf9f7` | `--color-horizon-gray` | Subtle background for UI elements, light button backgrounds, creating gentle visual separation. |
| Skyline Gray | `#efefef` | `--color-skyline-gray` | Thin borders for cards and dividers, offering a delicate boundary without harshness. |
| Mist Gray | `#a5a5a5` | `--color-mist-gray` | Secondary text, descriptive elements, providing lower hierarchy without significant desaturation. |
| Electric Blue | `#0068f9` | `--color-electric-blue` | Primary Call-to-Action buttons, interactive elements, highlights, and active states. This vivid blue is the core brand accent, signifying action and importance. |
| Deep Royal | `#024bb1` | `--color-deep-royal` | Darker shade for Electric Blue, used for button borders and hover states to add depth and interaction feedback. |
| Lavender Mist | `#f4f0ff` | `--color-lavender-mist` | Subtle background tint for specific sections or cards, adding a delicate, almost unseen touch of color. |
| Mint Green | `#046645` | `--color-mint-green` | Used for success indicators and positive feedback elements, a distinct color from brand blue. |
| Periwinkle | `#d5ecff` | `--color-periwinkle` | Very light accent for specific backgrounds or non-interactive highlights, a faint echo of the brand blue. |

## Tokens — Typography

### Roobert — The primary typeface for all text elements. Its geometric yet friendly sans-serif forms establish a clear, modern tone. The precise letter-spacing ensures legibility even at smaller sizes and contributes to the overall refined aesthetic. · `--font-roobert`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400, 500, 600, 700
- **Sizes:** 13px, 14px, 15px, 16px, 18px, 20px, 24px, 40px, 48px, 57px, 84px
- **Line height:** 1.06, 1.08, 1.09, 1.20, 1.25, 1.29, 1.33, 1.38, 1.43, 1.50, 1.56, 1.60
- **Letter spacing:** -0.0770em
- **Role:** The primary typeface for all text elements. Its geometric yet friendly sans-serif forms establish a clear, modern tone. The precise letter-spacing ensures legibility even at smaller sizes and contributes to the overall refined aesthetic.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 13px | 1.6 | — | `--text-caption` |
| body-lg | 16px | 1.43 | — | `--text-body-lg` |
| subheading | 18px | 1.38 | — | `--text-subheading` |
| heading-sm | 20px | 1.33 | — | `--text-heading-sm` |
| heading | 24px | 1.29 | — | `--text-heading` |
| heading-lg | 40px | 1.25 | — | `--text-heading-lg` |
| display-sm | 48px | 1.2 | — | `--text-display-sm` |
| display | 57px | 1.09 | — | `--text-display` |
| display-lg | 84px | 1.06 | — | `--text-display-lg` |

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
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 88 | 88px | `--spacing-88` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 16px |
| pills | 100px |
| images | 8px |
| buttons | 48px |
| default | 16px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(0, 0, 0, 0.07) 0px 1px 1px 0px, rgba(0, 0, 0, 0.04) ...` | `--shadow-subtle` |
| lg | `rgba(0, 0, 0, 0.04) 0px 20px 20px -8px` | `--shadow-lg` |

### Layout

## Components

### Secondary Outlined Button
**Role:** Secondary Action

Cloud White (#ffffff) background with Inkwell (#121722) text. Features a Skyline Gray (#d6e4f1) border at 1px and a 48px border-radius. Padding is 6px top, 14px right, 8px bottom, 14px left. Provides a less prominent alternative to the primary action.

### Feature Card Primary
**Role:** Content Display

Horizon Gray (#fbfaf7) background with no explicit border, 16px border-radius. Features significant padding: 32px all around. Used for highlighting key features or informational blocks.

### Feature Card Secondary
**Role:** Content Display

Lavender Mist (#f4f0ff) background with no explicit border, 16px border-radius. Features significant padding: 32px all around. Used for highlighting key features or informational blocks, offering a subtle color variation.

### Minimal Card
**Role:** Simple Content Block

Transparent background with no border-radius (0px). No box shadow, giving it a flat appearance. Padding is minimal at 6px top, 0px right, 0px bottom, 0px left. Used for basic grouping or minor content divisions.

### Pill Badge
**Role:** Categorization/Tag

Transparent background with Inkwell (#121722) text. No border-radius or padding specified directly on the badge, indicating it receives styling from context. Used for small, contextual labels.

## Do's and Don'ts

### Do
- Prioritize Electric Blue (#0068f9) for all interactive Call-to-Action elements.
- Use Roobert font with specific letter-spacing for all text elements to maintain brand voice.
- Apply 48px border-radius to all primary and secondary buttons for a consistent pill shape.
- Utilize Cloud White (#ffffff) as the dominant page background color to ensure a bright, expansive feel.
- Employ Horizon Gray (#faf9f7) for subtle background shifts to differentiate content blocks without harsh lines.
- Use a specific padding of at least 24px around card content for comfortable breathing room.
- Introduce Inkwell (#121722) as the primary text color for maximum contrast and readability on light backgrounds.

### Don't
- Avoid using highly saturated colors other than Electric Blue (#0068f9) and Mint Green (#046645) as main accents.
- Do not use generic square buttons; all buttons should conform to a 48px or 100px radius.
- Avoid heavy drop shadows; stick to subtle, single-layer box shadows like `rgba(0, 0, 0, 0.07) 0px 1px 1px 0px` for depth.
- Do not vary font families; stick exclusively to Roobert for all typography.
- Refrain from tight spacing between content elements; maintain `8px-16px` element gaps and `80px-120px` section gaps.
- Do not use highly textured or photographic backgrounds; keep surfaces clean and predominantly solid colors or subtle gradients.
- Avoid mixing transparent and opaque button styles within the same hierarchical level of action.

## Elevation

- **Card Shadow:** `rgba(0, 0, 0, 0.07) 0px 1px 1px 0px, rgba(0, 0, 0, 0.04) 0px -1px 1px 0px inset, rgba(0, 0, 0, 0.14) 0px 0px 0px 0.5px inset`
- **Image Shadow:** `rgba(0, 0, 0, 0.04) 0px 20px 20px -8px`

## Imagery

The visual language blends product screenshots with abstract data visualizations and crisp icons. Product screens are contained, often with soft edge treatments (8px radius) or presented within UI frames. Illustrations are geometric and abstract, using brand colors to convey information or concept without photorealism. Icons are filled, mono-color (Inkwell or Electric Blue), and appear clean and conceptual. Photography is minimal, if present, and likely focused on abstract concepts rather than lifestyle. The overall role of imagery is explanatory and supportive, enhancing UI elements and illustrating processes rather than acting as decorative full-bleed hero content. Density leans text-dominant, with imagery serving as clear visual anchors to communicate features and data.

## Layout

The page primarily uses a max-width contained layout, with content centered. The hero section is a full-width background, but its core content (headline, subtext, CTAs) is centrally aligned within a clear content well. Sections generally follow a consistent vertical rhythm, with generous `80px-120px` spacing between major blocks. Content often alternates between left-aligned text beside a right-aligned visual, or centered stacks for stronger impact points like 'Want a deeper tour?'. Card grids are used to showcase features and customer testimonials (e.g., 3-column grid for 'Why revenue teams are switching'). The layout feels spacious and organized, prioritizing readability and clear information hierarchy. Navigation is a sticky top bar, providing persistent access to key links.

## Agent Prompt Guide

### Quick Color Reference
- Text: Inkwell (#121722)
- Background: Cloud White (#ffffff)
- CTA Button: Electric Blue (#0068f9)
- Secondary Button: Cloud White (#ffffff)
- Card Background: Horizon Gray (#faf9f7)
- Border: Skyline Gray (#efefef)

### Example Component Prompts
1. **Create a Hero Section:** Background Electric Blue (#0068f9). Headline 'Enablement that sellers and buyers love' in Roobert 84px, weight 700 (#ffffff), lineHeight 1.06, letterSpacing -0.0770em. Body copy 'Dock is the AI revenue enablement platform...' in Roobert 20px, weight 400 (#ffffff), lineHeight 1.33. Include a Primary Filled Button 'Start for Free' and a Secondary Outlined Button 'Request Demo'.
2. **Generate a Feature Card:** Background Horizon Gray (#faf9f7), border-radius 16px, padding 32px. Title 'Sales' in Roobert 16px, weight 600 (#121722). Description 'Increase conversion rates by 11%' in Roobert 24px, weight 700 (#121722). Include a Mint Green (#046645) icon where appropriate.
3. **Design a Navigation Bar:** Background Cloud White (#ffffff). Brand logo. Navigation links 'Product', 'Pricing', 'Customers' in Roobert 15px, weight 500 (#121722), lineHeight 1.5. Include a Primary Filled Button 'Start for Free' and a Secondary Outlined Button 'Request Demo' on the far right.
4. **Build a Testimonial Block:** Background Lavender Mist (#f4f0ff), border-radius 16px, padding 32px. Quote in Roobert 24px, weight 600 (#121722). Source name in Roobert 16px, weight 400 (#a5a5a5). Include a small image with 8px border-radius. Center text alignment.

## Similar Brands

- **Calendly** — Uses a similar vibrant blue accent against a clean, light background with soft rounded edges for buttons and cards.
- **Intercom** — Leverages distinct blues and greens with a friendly, modern sans-serif typography and clear, component-based layout for SaaS solutions.
- **Drift** — Features a light theme with bright, singular accent colors for CTAs, paired with geometric sans-serifs and ample whitespace.
- **Chili Piper** — Employs a clean, spacious UI with a custom sans-serif font, clear call-to-actions in brand colors, and light backgrounds for a professional SaaS feel.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-inkwell: #121722;
  --color-cloud-white: #ffffff;
  --color-horizon-gray: #faf9f7;
  --color-skyline-gray: #efefef;
  --color-mist-gray: #a5a5a5;
  --color-electric-blue: #0068f9;
  --color-deep-royal: #024bb1;
  --color-lavender-mist: #f4f0ff;
  --color-mint-green: #046645;
  --color-periwinkle: #d5ecff;

  /* Typography — Font Families */
  --font-roobert: 'Roobert', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 1.6;
  --text-body-lg: 16px;
  --leading-body-lg: 1.43;
  --text-subheading: 18px;
  --leading-subheading: 1.38;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.33;
  --text-heading: 24px;
  --leading-heading: 1.29;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.25;
  --text-display-sm: 48px;
  --leading-display-sm: 1.2;
  --text-display: 57px;
  --leading-display: 1.09;
  --text-display-lg: 84px;
  --leading-display-lg: 1.06;

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
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-88: 88px;

  /* Layout */

  /* Border Radius */
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 32px;
  --radius-3xl-2: 40px;
  --radius-full: 48px;
  --radius-full-2: 60px;
  --radius-full-3: 100px;

  /* Named Radii */
  --radius-cards: 16px;
  --radius-pills: 100px;
  --radius-images: 8px;
  --radius-buttons: 48px;
  --radius-default: 16px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.07) 0px 1px 1px 0px, rgba(0, 0, 0, 0.04) 0px -1px 1px 0px inset, rgba(0, 0, 0, 0.14) 0px 0px 0px 0.5px inset;
  --shadow-lg: rgba(0, 0, 0, 0.04) 0px 20px 20px -8px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-inkwell: #121722;
  --color-cloud-white: #ffffff;
  --color-horizon-gray: #faf9f7;
  --color-skyline-gray: #efefef;
  --color-mist-gray: #a5a5a5;
  --color-electric-blue: #0068f9;
  --color-deep-royal: #024bb1;
  --color-lavender-mist: #f4f0ff;
  --color-mint-green: #046645;
  --color-periwinkle: #d5ecff;

  /* Typography */
  --font-roobert: 'Roobert', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 1.6;
  --text-body-lg: 16px;
  --leading-body-lg: 1.43;
  --text-subheading: 18px;
  --leading-subheading: 1.38;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.33;
  --text-heading: 24px;
  --leading-heading: 1.29;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.25;
  --text-display-sm: 48px;
  --leading-display-sm: 1.2;
  --text-display: 57px;
  --leading-display: 1.09;
  --text-display-lg: 84px;
  --leading-display-lg: 1.06;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-88: 88px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 32px;
  --radius-3xl-2: 40px;
  --radius-full: 48px;
  --radius-full-2: 60px;
  --radius-full-3: 100px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.07) 0px 1px 1px 0px, rgba(0, 0, 0, 0.04) 0px -1px 1px 0px inset, rgba(0, 0, 0, 0.14) 0px 0px 0px 0.5px inset;
  --shadow-lg: rgba(0, 0, 0, 0.04) 0px 20px 20px -8px;
}
```

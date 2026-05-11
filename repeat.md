# Repeat — Style Reference
> High-contrast lime punch

**Theme:** light

Repeat leverages a high-contrast, playful yet authoritative aesthetic, combining a stark achromatic base with a singular, vibrant 'Sour Lime' accent. Large, confident typography set in Montserrat for content and Poppins for headlines establishes a clear visual hierarchy. Surface treatments are minimal, with soft shadows and organic, large radii for cards, creating a friendly, approachable feel while maintaining a compact, information-dense layout. Color is used sparingly but strategically to highlight key actions and sections, with muted pastel backgrounds providing visual segmentation.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#171717` | `--color-midnight-ink` | Primary text, deep surface outlines, button text on light backgrounds, footer background |
| Canvas White | `#ffffff` | `--color-canvas-white` | Hairline borders, dividers, input outlines, and card edges on light surfaces. Do not promote it to the primary CTA color |
| Warm Parchment | `#ede7e2` | `--color-warm-parchment` | Section background, secondary canvas |
| Deep Charcoal | `#37352f` | `--color-deep-charcoal` | Navigation background for selected elements |
| Sour Lime | `#f5ff7d` | `--color-sour-lime` | Green wash for highlight backgrounds, decorative bands, and soft emphasis behind content. Do not promote it to the primary CTA color |
| Serene Sky | `#c3d5fc` | `--color-serene-sky` | Muted background for content sections, subtle visual break |
| Soft Lilac | `#e2d8ff` | `--color-soft-lilac` | Muted background for content sections, subtle visual break |

## Tokens — Typography

### Montserrat — Body text, navigation items, links, card content and testimonials. Weight 400 is standard for readability, while 500 and 600 add emphasis for features and navigation. · `--font-montserrat`
- **Substitute:** system-ui
- **Weights:** 400, 500, 600
- **Sizes:** 13px, 15px, 17px, 34px
- **Line height:** 0.75, 1.20, 1.29, 1.50, 1.60, 2.00
- **Letter spacing:** normal
- **Role:** Body text, navigation items, links, card content and testimonials. Weight 400 is standard for readability, while 500 and 600 add emphasis for features and navigation.

### Poppins — Headlines and prominent marketing statements. Its geometric structure provides a bold and modern feel. Varied weights and larger sizes ensure these headings capture immediate attention. · `--font-poppins`
- **Substitute:** system-ui
- **Weights:** 400, 500, 600
- **Sizes:** 17px, 20px, 24px, 29px, 37px
- **Line height:** 1.00, 1.20, 1.30
- **Letter spacing:** normal
- **Role:** Headlines and prominent marketing statements. Its geometric structure provides a bold and modern feel. Varied weights and larger sizes ensure these headings capture immediate attention.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 13px | 1.5 | — | `--text-caption` |
| body-sm | 15px | 1.6 | — | `--text-body-sm` |
| body | 17px | 1.6 | — | `--text-body` |
| subheading | 20px | 1.2 | — | `--text-subheading` |
| heading-sm | 24px | 1.2 | — | `--text-heading-sm` |
| heading | 29px | 1.2 | — | `--text-heading` |
| display | 37px | 1 | — | `--text-display` |

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
| 24 | 24px | `--spacing-24` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 96 | 96px | `--spacing-96` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 3px |
| cards | 25px |
| images | 20px |
| buttons | 50px |
| navItems | 8px |
| heroButton | 100px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| sm | `rgba(0, 0, 0, 0.01) 0px 4px 8px -2px` | `--shadow-sm` |

### Layout

- **Section gap:** 40px
- **Card padding:** 15px
- **Element gap:** 4px

## Components

### Primary Action CTA (Text Button)
**Role:** Call to action for hero sections and primary navigation. Text color indicates action, but background is transparent.

Text: 'Midnight Ink' #171717, Montserrat 500, 17px. No background, transparent. Border: 1px 'Midnight Ink' #171717. Border radius: 100px. Padding: 17px 34px.

### Navigation Button (Filled)
**Role:** Prominent call to action in the main navigation. Uses the brand's 'Sour Lime' to stand out.

Background: 'Sour Lime' #f5ff7d. Text: 'Midnight Ink' #171717, Montserrat 600, 15px. Border radius: 8px. Padding: 8px 16px.

### Ghost Icon Button
**Role:** Interactive elements with minimal visual weight, like branded company logos.

Background: 'Deep Charcoal' #37352f. Text/Icon: 'Canvas White' #ffffff. Border radius: 25px. Padding: 9px (all sides).

### Information Card (Large Radius)
**Role:** Displaying testimonials or featured brands, with a soft, approachable aesthetic.

Background: 'Canvas White' #ffffff. Border: 1px solid 'Midnight Ink' #171717. Border radius: 25px. Shadow: rgba(0, 0, 0, 0.01) 0px 4px 8px -2px. Inner padding: 15px.

### Link Button (Underlined)
**Role:** Secondary action or internal navigation, subtle and integrated into text content.

Text: 'Midnight Ink' #171717, Montserrat 400. Letter spacing normal. Underlined for clear affordance.

### Hero Section
**Role:** First impression and primary conversion point.

Background: 'Sour Lime' #f5ff7d. Contains a large, bold headline and a prominent outline button. Section bottom padding: 45px, side padding: 96px.

## Do's and Don'ts

### Do
- Always use the 'Sour Lime' #f5ff7d accent color only for primary CTAs, active states, and hero backgrounds to preserve its impact.
- Apply 'Midnight Ink' #171717 for all body text, headings, and borders to maintain a strong contrast and visual anchor.
- Utilize Montserrat for all body and descriptive text at weights 400-600, ensuring consistent readability across content blocks.
- Reserve Poppins for headlines and prominent display text (sizes 20px and above) to give sections a strong, engaging entry point.
- Use a border-radius of 25px for all cards and container elements to maintain a soft, friendly aesthetic.
- Employ the rgba(0, 0, 0, 0.01) 0px 4px 8px -2px shadow for cards to provide subtle depth without heavy elevation.
- Ensure horizontal padding on primary sections is at least 96px on desktop to create ample breathing room.

### Don't
- Do not introduce new saturated colors outside of #f5ff7d; maintain the two-tone accent approach with muted pastels.
- Avoid heavy drop shadows or glows; only the subtly styled card shadow is permitted for elevation.
- Do not use highly decorative or script fonts; stick to Montserrat and Poppins for all text elements.
- Refrain from drastically altering body text line-height; maintain the provided 1.5-1.6 values for optimal legibility.
- Do not use generic square corners; ensure all interactive elements and cards use defined radii of 25px, 50px, or 100px.
- Avoid compacting card content; always maintain at least 15px of internal padding for cards.
- Do not use multiple font sizes or weights for hero CTA text; use Montserrat 500 at 17px.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Warm Parchment | `#ede7e2` | Base page background, neutral canvas for varying content sections. |
| 1 | Canvas White | `#ffffff` | Default card backgrounds, elevated content areas, and core UI elements. |
| 2 | Sour Lime | `#f5ff7d` | Primary hero and accent sections, drawing attention and signalling energy. |
| 3 | Serene Sky | `#c3d5fc` | Alternating section background, offering subtle visual breaks without high contrast. |
| 3 | Soft Lilac | `#e2d8ff` | Alternating section background, offering subtle visual breaks without high contrast. |

## Elevation

- **Information Card (Large Radius):** `rgba(0, 0, 0, 0.01) 0px 4px 8px -2px`

## Imagery

This design system uses product photography and iconography. Photography features tight crops of product packaging, presented directly on white or neutral backgrounds with minimal context. Images often have soft, rounded corners (20px radius). Icons are filled, monochrome, and maintain a compact, minimal appearance, often used within ghost buttons or as small decorative elements. The overall density of imagery is balanced, providing visual interest without overwhelming the text-dominant content. Imagery serves to showcase brands or provide simple visual cues rather than create an immersive atmosphere.

## Layout

The page primarily uses a contained layout within a max-width, though a specific global max-width is not defined. The hero section is full-bleed, using the 'Sour Lime' background to command attention, featuring a centered headline and a prominent, rounded ghost button. Sections alternate between 'Warm Parchment', 'Canvas White', 'Serene Sky', and 'Soft Lilac' backgrounds, creating a clear vertical rhythm. Content is generally arranged in centered stacks or two-column text-left/visual-right patterns. A 3-column card grid is used for displaying featured brands. Vertical spacing is consistent and generous between sections. A sticky top navigation bar is used, featuring a primary filled button for immediate action.

## Agent Prompt Guide

### Quick Color Reference
- text: #171717
- background: #ffffff
- border: #171717
- accent: #f5ff7d
- primary action: no distinct CTA color

### 3-5 Example Component Prompts
1. Create a hero section: 'Sour Lime' #f5ff7d background. Headline 'Supercharged Marketing' in Poppins 37px 600, 'Midnight Ink' #171717, lineHeight 1.0. Subtext 'Repeat boosts repurchase rate' in Montserrat 17px 400, 'Midnight Ink' #171717, lineHeight 1.6. Include a ghost button '→ Book a Demo' with 'Midnight Ink' #171717 text, 1px 'Midnight Ink' #171717 border, 100px radius, 17px 34px padding.
2. Create an information card for a testimonial: 'Canvas White' #ffffff background, 1px 'Midnight Ink' #171717 border, 25px radius, rgba(0, 0, 0, 0.01) 0px 4px 8px -2px shadow. Inner padding 15px. Testimonial Body text in Montserrat 15px 400, 'Midnight Ink' #171717, lineHeight 1.6. Author name in Montserrat 15px 600.
3. Design a navigation bar: 'Canvas White' #ffffff background. Left aligned logo. Right aligned links 'Product', 'Blog', 'Stop Focusing on LTV' in Montserrat 15px 500, 'Midnight Ink' #171717. Include a filled button 'BOOK A DEMO' with 'Sour Lime' #f5ff7d background, 'Midnight Ink' #171717 text, 8px radius, 8px 16px padding.
4. Create a section with a 'Serene Sky' #c3d5fc background. Display a subheading 'Favorite Brands' in Poppins 29px 600, 'Midnight Ink' #171717, lineHeight 1.2. Below, place three ghost icon buttons in a row with 'Deep Charcoal' #37352f background, 'Canvas White' #ffffff text, 25px radius, 9px padding.

## Similar Brands

- **Klaviyo** — High-contrast text on light backgrounds, with a clear focus on clear typography and functional elements over heavy decoration.
- **Mailchimp** — Use of vibrant, playful accent colors (their yellow vs. Repeat's lime) against a mostly neutral, clean UI to highlight branding and calls to action.
- **ActiveCampaign** — Clean, structured layouts with prominent headlines and a clear hierarchy; uses muted secondary colors for section breaks and card backgrounds.
- **Attentive** — Focus on data-driven marketing, reflected in a straightforward, high-utility design with clear CTAs and distinct sectioning.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #171717;
  --color-canvas-white: #ffffff;
  --color-warm-parchment: #ede7e2;
  --color-deep-charcoal: #37352f;
  --color-sour-lime: #f5ff7d;
  --color-serene-sky: #c3d5fc;
  --color-soft-lilac: #e2d8ff;

  /* Typography — Font Families */
  --font-montserrat: 'Montserrat', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-poppins: 'Poppins', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 1.5;
  --text-body-sm: 15px;
  --leading-body-sm: 1.6;
  --text-body: 17px;
  --leading-body: 1.6;
  --text-subheading: 20px;
  --leading-subheading: 1.2;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.2;
  --text-heading: 29px;
  --leading-heading: 1.2;
  --text-display: 37px;
  --leading-display: 1;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-96: 96px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 15px;
  --element-gap: 4px;

  /* Border Radius */
  --radius-sm: 3px;
  --radius-lg: 8px;
  --radius-2xl: 20px;
  --radius-3xl: 25px;
  --radius-full: 50px;
  --radius-full-2: 100px;

  /* Named Radii */
  --radius-tags: 3px;
  --radius-cards: 25px;
  --radius-images: 20px;
  --radius-buttons: 50px;
  --radius-navitems: 8px;
  --radius-herobutton: 100px;

  /* Shadows */
  --shadow-sm: rgba(0, 0, 0, 0.01) 0px 4px 8px -2px;

  /* Surfaces */
  --surface-warm-parchment: #ede7e2;
  --surface-canvas-white: #ffffff;
  --surface-sour-lime: #f5ff7d;
  --surface-serene-sky: #c3d5fc;
  --surface-soft-lilac: #e2d8ff;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #171717;
  --color-canvas-white: #ffffff;
  --color-warm-parchment: #ede7e2;
  --color-deep-charcoal: #37352f;
  --color-sour-lime: #f5ff7d;
  --color-serene-sky: #c3d5fc;
  --color-soft-lilac: #e2d8ff;

  /* Typography */
  --font-montserrat: 'Montserrat', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-poppins: 'Poppins', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 1.5;
  --text-body-sm: 15px;
  --leading-body-sm: 1.6;
  --text-body: 17px;
  --leading-body: 1.6;
  --text-subheading: 20px;
  --leading-subheading: 1.2;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.2;
  --text-heading: 29px;
  --leading-heading: 1.2;
  --text-display: 37px;
  --leading-display: 1;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-96: 96px;

  /* Border Radius */
  --radius-sm: 3px;
  --radius-lg: 8px;
  --radius-2xl: 20px;
  --radius-3xl: 25px;
  --radius-full: 50px;
  --radius-full-2: 100px;

  /* Shadows */
  --shadow-sm: rgba(0, 0, 0, 0.01) 0px 4px 8px -2px;
}
```

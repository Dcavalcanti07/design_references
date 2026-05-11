# Valo — Style Reference
> Midnight research lab

**Theme:** dark

Valo employs a dark, scientific command center aesthetic with high contrast text on a black canvas. Subtle animated gradients and abstract organic shapes introduce visual dynamics, contrasting with highly structured, minimalist typography featuring a distinctive custom font. Interactions are clean and understated, relying on ghost elements and an accent color for 'aha' moments, fostering a sense of controlled innovation and precision.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Canvas | `#000000` | `--color-midnight-canvas` | Page backgrounds, primary surface for dark mode, primary text color for light surfaces |
| Silver Text | `#ffffff` | `--color-silver-text` | Primary text and icon color against dark backgrounds. Also used as background for selected component states |
| Ghost Border | `#e5e7eb` | `--color-ghost-border` | Subtle borders for ghost buttons, dividers, and various UI elements, providing structure in the dark theme |
| Subtle Divider | `#4d4d4d` | `--color-subtle-divider` | Finer, lower-contrast borders and dividers within complex layouts, particularly in navigation |
| Enlightenment Gradient | `linear-gradient(270deg, rgb(158, 61, 178), rgb(27, 102, 248), rgb(36, 218, 217), rgb(179, 198, 232))` | `--color-enlightenment-gradient` | Hero section backgrounds, prominent visual accents, and decorative elements to convey advanced technology and discovery |
| Deep Tech Gradient | `linear-gradient(90deg, rgb(30, 35, 60), rgb(10, 64, 153))` | `--color-deep-tech-gradient` | Used for abstract visual shapes and background elements, deepening the dark theme and hinting at technological complexity |
| Bio-Discovery Gradient | `linear-gradient(90deg, rgb(25, 81, 162), rgb(112, 218, 180))` | `--color-bio-discovery-gradient` | Secondary accent gradient for abstract illustrations and contextual backgrounds, suggesting scientific process and innovation |

## Tokens — Typography

### Valo — The custom Valo typeface is used for all text, conveying a distinct scientific and sophisticated tone. The wide range of weights and sizes supports a clear typographic hierarchy, from subtle captions to expansive display headlines, with negative letter-spacing on larger sizes to create a modern, composed feel. · `--font-valo`
- **Substitute:** system-ui
- **Weights:** 300, 400, 700
- **Sizes:** 10px, 13px, 15px, 18px, 24px, 30px, 38px, 60px, 100px
- **Line height:** 1.00, 1.20, 1.30, 1.33, 1.40, 1.63
- **Letter spacing:** 0.1, 0.08, 0.06, 0.05, -0.013, -0.013, -0.013, -0.027, -0.027
- **OpenType features:** `"clig" on, "liga" on, "ss03" on`
- **Role:** The custom Valo typeface is used for all text, conveying a distinct scientific and sophisticated tone. The wide range of weights and sizes supports a clear typographic hierarchy, from subtle captions to expansive display headlines, with negative letter-spacing on larger sizes to create a modern, composed feel.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.4 | 0.1px | `--text-caption` |
| body | 15px | 1.3 | 0.06px | `--text-body` |
| subheading | 18px | 1.63 | 0.05px | `--text-subheading` |
| heading-sm | 24px | 1.3 | -0.013px | `--text-heading-sm` |
| heading | 38px | 1.2 | -0.013px | `--text-heading` |
| heading-lg | 60px | 1 | -0.027px | `--text-heading-lg` |
| display | 100px | 1 | -0.027px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 36 | 36px | `--spacing-36` |
| 108 | 108px | `--spacing-108` |
| 216 | 216px | `--spacing-216` |

### Border Radius

| Element | Value |
|---------|-------|
| links | 9999px |
| buttons | 9999px |

### Layout

- **Page max-width:** 1400px
- **Section gap:** 45px
- **Card padding:** 18px
- **Element gap:** 20px

## Components

### Ghost Navigation Link
**Role:** Primary navigation links

Text in Silver Text (#ffffff) on Midnight Canvas, appearing as plain text that transforms into an outlined Ghost Border (#e5e7eb) button on hover. The hover state highlights the active area without strong background fills, maintaining the dark, minimalist aesthetic.

### Ghost Arrow Button
**Role:** Call to action for external links or advancing sections

Round button with a Silver Text (#ffffff) background and 9999px border-radius, containing a Midnight Canvas (#000000) arrow icon. Text is Midnight Canvas on Silver Text for the text label, visually integrating with the dark theme despite its 'light' appearance, implying forward motion.

### Footer Link
**Role:** Secondary navigation and legal links

Body text in Silver Text (#ffffff) against Midnight Canvas. These links are functional without being prominent, reflecting their secondary importance in the overall information hierarchy.

### Subtle Divider Line
**Role:** Visual separator for content sections

A 1px solid line in Ghost Border (#e5e7eb) or Subtle Divider (#4d4d4d), used to segment content without heavy visual breaks, preserving the overall spacious and dark design.

## Do's and Don'ts

### Do
- Prioritize Midnight Canvas (#000000) for all main backgrounds and Silver Text (#ffffff) for primary text to maintain the dark theme.
- Use Ghost Border (#e5e7eb) for all subtle structural lines, interactive element borders, and dividers where visual weight needs to be minimal.
- Apply Valo font with negative letter-spacing for all heading and display sizes to achieve a compressed, modern look.
- Utilize 9999px border-radius for all interactive elements like buttons and links to create a consistent 'pill' shape.
- Incorporate Enlightenment Gradient for hero sections or prominent large visual elements to imbue them with brand identity and high-tech feel.
- Maintain consistent vertical rhythm using the defined sectionGap of 45px and elementGap of 20px.
- Ensure all text, apart from gradients, is either Silver Text (#ffffff) or Midnight Canvas (#000000) for high contrast and legibility.

### Don't
- Avoid using solid background fills for primary calls to action; instead, use ghost buttons with Ghost Border (#e5e7eb) and Silver Text (#ffffff).
- Do not introduce new color families for informational or status elements; leverage existing brand gradients or neutrals.
- Shun any drop shadows or harsh elevation effects; surfaces should remain flat or rely on subtle background gradients.
- Resist using default system fonts or weights not specified in the Valo typography family; the custom font and its specific weights are key to brand identity.
- Avoid decorative imagery with vibrant colors not derived from the brand gradients; the visual language is subtle and controlled.
- Do not deviate from the established max-width of 1400px for page content; maintain the contained and structured layout.
- Steer clear of aggressive hover states that introduce strong background colors or complex animations for standard interactive elements.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Midnight Canvas | `#000000` | Primary page background and default surface for all content. |
| 1 | Silver Component Surface | `#ffffff` | Used sparingly for interactive elements or specific content blocks where a reversed, high-contrast display is desired within the dark theme. |

## Imagery

The site uses abstract, organic, and occasionally geometric graphic elements primarily filled with the brand's linear gradients. These graphics serve a decorative atmosphere and explanatory content role, appearing as large, contained shapes like circular outlines or fluid background patterns. There are no lifestyle photos or product screenshots, enforcing a clean, data-driven, and conceptual approach to visual communication. Icons are simple, outlined, and monochromatic, usually Silver Text on Midnight Canvas, with a consistent stroke weight to support the minimalist UI. Imagery density is low; text dominates, with graphics acting as supporting visual anchors.

## Layout

The page embraces a contained layout with a maximum width of 1400px, centered on the screen. The hero section is full-bleed Midnight Canvas with a large, centered headline and descriptive text. Subsequent sections alternate between the primary dark canvas and occasional gradient-infused abstract backgrounds, maintaining consistent vertical spacing via a 45px sectionGap. Content is primarily arranged in two-column text-left/image-right or text-right/image-left patterns, often featuring large text blocks alongside abstract graphic elements. Navigation is a sticky top bar with minimalist ghost links. The footer is sectioned with a deep tech gradient band and a Midnight Canvas area, maintaining the overall theme.

## Agent Prompt Guide

Quick Color Reference:
text: #ffffff
background: #000000
border: #e5e7eb
accent: #9e3db2 (Enlightenment Gradient)
primary action: no distinct CTA color

Example Component Prompts:
Create a hero section: Midnight Canvas background. Headline 'We engineer "aha" moments in scientific discovery' at 100px Valo weight 700 with Silver Text (#ffffff), letter-spacing -0.027px. Subtext 'Valo combines real-world data, AI...' at 18px Valo weight 400 with Silver Text (#ffffff), letter-spacing 0.05px.

Create a ghost button: Text 'Explore our approach' at 15px Valo weight 400 with Silver Text (#ffffff), letter-spacing 0.06px. Border 1px solid Ghost Border (#e5e7eb) with 9999px border-radius, 7px paddingTop/paddingBottom, 27px paddingLeft/paddingRight.

Create a secondary text section: Midnight Canvas background. Heading 'AI-enabled human causal biology' at 24px Valo weight 400 with Silver Text (#ffffff), letter-spacing -0.013px. Body text 'Valo harnesses AI to...' at 15px Valo weight 400 with Silver Text (#ffffff), letter-spacing 0.06px, with 14px marginBottom between paragraphs.

Create a primary navigation item: Text 'Approach' at 13px Valo weight 400 with Silver Text (#ffffff), letter-spacing 0.08px. On hover, apply a 1px Ghost Border (#e5e7eb) to the bottom, 7px paddingTop/paddingBottom, 27px paddingLeft/paddingRight.

## Similar Brands

- **DeepMind** — Shares a sophisticated dark theme, minimalist UI, and uses abstract technical graphics to represent complex scientific concepts.
- **CRISPR Therapeutics** — Employs high-contrast dark layouts with very specific, restrained color accents and modern, structured typography for a scientific, innovative feel.
- **Verily Life Sciences** — Features a clean, spacious dark UI with sharp typography, prioritizing content and data visualization over heavy decorative elements.
- **Stripe** — While a lighter theme generally, it shares the strategic use of custom typography with precise letter-spacing, and a preference for ghost buttons and subtle UI interactions over strong fills.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-canvas: #000000;
  --color-silver-text: #ffffff;
  --color-ghost-border: #e5e7eb;
  --color-subtle-divider: #4d4d4d;
  --color-enlightenment-gradient: #9e3db2;
  --gradient-enlightenment-gradient: linear-gradient(270deg, rgb(158, 61, 178), rgb(27, 102, 248), rgb(36, 218, 217), rgb(179, 198, 232));
  --color-deep-tech-gradient: #1e233c;
  --gradient-deep-tech-gradient: linear-gradient(90deg, rgb(30, 35, 60), rgb(10, 64, 153));
  --color-bio-discovery-gradient: #1951a2;
  --gradient-bio-discovery-gradient: linear-gradient(90deg, rgb(25, 81, 162), rgb(112, 218, 180));

  /* Typography — Font Families */
  --font-valo: 'Valo', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.4;
  --tracking-caption: 0.1px;
  --text-body: 15px;
  --leading-body: 1.3;
  --tracking-body: 0.06px;
  --text-subheading: 18px;
  --leading-subheading: 1.63;
  --tracking-subheading: 0.05px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.3;
  --tracking-heading-sm: -0.013px;
  --text-heading: 38px;
  --leading-heading: 1.2;
  --tracking-heading: -0.013px;
  --text-heading-lg: 60px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -0.027px;
  --text-display: 100px;
  --leading-display: 1;
  --tracking-display: -0.027px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-36: 36px;
  --spacing-108: 108px;
  --spacing-216: 216px;

  /* Layout */
  --page-max-width: 1400px;
  --section-gap: 45px;
  --card-padding: 18px;
  --element-gap: 20px;

  /* Border Radius */
  --radius-full: 9999px;

  /* Named Radii */
  --radius-links: 9999px;
  --radius-buttons: 9999px;

  /* Surfaces */
  --surface-midnight-canvas: #000000;
  --surface-silver-component-surface: #ffffff;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-canvas: #000000;
  --color-silver-text: #ffffff;
  --color-ghost-border: #e5e7eb;
  --color-subtle-divider: #4d4d4d;
  --color-enlightenment-gradient: #9e3db2;
  --color-deep-tech-gradient: #1e233c;
  --color-bio-discovery-gradient: #1951a2;

  /* Typography */
  --font-valo: 'Valo', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.4;
  --tracking-caption: 0.1px;
  --text-body: 15px;
  --leading-body: 1.3;
  --tracking-body: 0.06px;
  --text-subheading: 18px;
  --leading-subheading: 1.63;
  --tracking-subheading: 0.05px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.3;
  --tracking-heading-sm: -0.013px;
  --text-heading: 38px;
  --leading-heading: 1.2;
  --tracking-heading: -0.013px;
  --text-heading-lg: 60px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -0.027px;
  --text-display: 100px;
  --leading-display: 1;
  --tracking-display: -0.027px;

  /* Spacing */
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-36: 36px;
  --spacing-108: 108px;
  --spacing-216: 216px;

  /* Border Radius */
  --radius-full: 9999px;
}
```

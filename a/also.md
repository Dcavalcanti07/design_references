# ALSO — Style Reference
> utilitarian tech on a pastel canvas

**Theme:** light

ALSO presents a stark, almost brutalist aesthetic on a gentle light canvas, punctuated by a vivid purple. The typography is compact and assertive, heavily relying on custom sans-serifs with tight tracking for a mechanical, precise feel. Components are minimalist, often outlined rather than filled, with sharp corners softened by occasional extreme pill-like radii, creating a tension between utilitarian directness and playful softness. The primary accent purple acts as a functional highlight for interactive elements and visual containers, breaking the monochrome for impact.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#fcf7fa` | `--color-canvas-white` | Primary page and section backgrounds, quietest surface |
| Background White | `#ffffff` | `--color-background-white` | Elevated card backgrounds, input backgrounds |
| Midnight Black | `#000000` | `--color-midnight-black` | Primary text, strong borders and outlines, icon fills |
| Input Border Dark | `#212121` | `--color-input-border-dark` | Input element borders on white backgrounds |
| Button Black | `#1a1a1a` | `--color-button-black` | Specific button background fill for strong contrast actions |
| Royal Purple | `#ac74fc` | `--color-royal-purple` | Links, active indicators, interactive element borders, decorative container backgrounds. It is the primary chromatic identifier |
| Deep Violet | `#381b5e` | `--color-deep-violet` | Subtle borders for outlined components, secondary brand accents |
| Action Blue | `#1276a9` | `--color-action-blue` | Outlined button borders, often for secondary actions |
| Shadow Violet | `#48316a` | `--color-shadow-violet` | Violet supporting accent for decorative details and low-frequency emphasis. Do not promote it to the primary CTA color |
| Main Action Purple | `#c181ff` | `--color-main-action-purple` | Primary action button background fill, distinct from Royal Purple for filled states |
| Success Green | `#b1ff8f` | `--color-success-green` | Green action color for filled buttons, selected navigation states, and focused conversion moments. Use as a supporting accent, not as a status color |

## Tokens — Typography

### ABCCameraPlainVariable — Headlines, navigation links, and primary body text. Its variable nature and tight tracking give it a distinctive, modern, and technical voice. · `--font-abccameraplainvariable`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 12px, 16px, 20px, 24px, 32px, 44px, 60px
- **Line height:** 0.93, 1.00, 1.09, 1.13, 1.17, 1.20, 1.50, 1.67
- **Letter spacing:** -0.0500em at 60px, -0.0470em at 44px, -0.0450em at 32px, -0.0420em at 24px, -0.0250em at 20px, -0.0160em at 16px, 0.0500em at 12px
- **Role:** Headlines, navigation links, and primary body text. Its variable nature and tight tracking give it a distinctive, modern, and technical voice.

### SerialC-Heavy — Emphasized text, secondary buttons, and some heading elements. Its heavier weight provides hierarchy and a sense of directness, complementing the main typeface. · `--font-serialc-heavy`
- **Substitute:** Oswald
- **Weights:** 400, 900
- **Sizes:** 14px, 16px, 20px
- **Line height:** 1.20, 1.25, 1.43
- **Letter spacing:** 0.0360em at 20px, 0.0500em at 16px, 0.0630em at 14px
- **Role:** Emphasized text, secondary buttons, and some heading elements. Its heavier weight provides hierarchy and a sense of directness, complementing the main typeface.

### SerialC — General body text in specific contexts, input placeholder text, and some button labels. A neutral, legible companion to the more expressive fonts. · `--font-serialc`
- **Substitute:** Open Sans
- **Weights:** 400, 700
- **Sizes:** 12px, 16px, 20px
- **Line height:** 1.00, 1.20
- **Letter spacing:** 0.0500em
- **Role:** General body text in specific contexts, input placeholder text, and some button labels. A neutral, legible companion to the more expressive fonts.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.5 | 0.6px | `--text-caption` |
| body-sm | 14px | 1.43 | 0.88px | `--text-body-sm` |
| body | 16px | 1.2 | -0.26px | `--text-body` |
| subheading | 20px | 1.2 | -0.5px | `--text-subheading` |
| heading-sm | 24px | 1.13 | -1px | `--text-heading-sm` |
| heading | 32px | 1.09 | -1.44px | `--text-heading` |
| heading-lg | 44px | 1 | -2.07px | `--text-heading-lg` |
| display | 60px | 0.93 | -3px | `--text-display` |

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
| 72 | 72px | `--spacing-72` |
| 80 | 80px | `--spacing-80` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 9999px |
| cards | 0px |
| links | 12px |
| buttons | 9999px |
| specificButtons | 56px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgb(72, 49, 106) 0px 2px 0px 0px` | `--shadow-subtle` |

### Layout

- **Section gap:** 40px
- **Card padding:** 16px
- **Element gap:** 16px

## Components

### Pill Button - Filled
**Role:** Primary calls to action.

Background: Main Action Purple (#c181ff), Text: Midnight Black (#000000). Border Radius: 9999px. Padding: 0px vertical, 20px horizontal. Subtle shadow: 0px 2px 0px 0px Shadow Violet (#48316a).

### Pill Button - Transparent
**Role:** Secondary actions or navigation items.

Background: transparent (white to the background), Text: Midnight Black (#000000). Border Radius: 9999px. Padding: 0px vertical, 16px horizontal. No border or shadow.

### Square Button - Filled
**Role:** Utility buttons with high information density.

Background: Background White (#ffffff), Text: Midnight Black (#000000). Border Radius: 0px. Padding: 32px all sides. No border or shadow.

### Outlined Input Field
**Role:** User data entry.

Background: Background White (#ffffff), Text: Midnight Black (#000000). Border: 1px solid Input Border Dark (#212121), Border Radius: 0px. Padding: 0px vertical, 16px left.

### Image Card - Zero Radius
**Role:** Displaying product or feature visuals.

Background: Background White (#ffffff). Border Radius: 0px. Padding: derived from context (e.g. 16px is common element gap). No explicit border by default, relies on layout for separation.

### Accent Block Container
**Role:** Highlighting content sections or quotes.

Background: Royal Purple (#ac74fc). Border: 2px solid Midnight Black (#000000). Text: Midnight Black (#000000). No explicit radius, implies 0px unless nested element specifies.

### Feature Card
**Role:** Showcasing distinct features with prominent visual and minimal text.

Background: Canvas White (#fcf7fa). Border: 1px solid Midnight Black (#000000). Text: Midnight Black (#000000). Border Radius: 0px. Padding variable by content (e.g. 24px vertical, 16px horizontal).

## Do's and Don'ts

### Do
- Prioritize ABCCameraPlainVariable and SerialC-Heavy for all headings and key narrative elements to maintain the brand's distinct typographic voice.
- Use Midnight Black (#000000) for all primary text and strong outlines against light backgrounds, ensuring high contrast.
- Apply Royal Purple (#ac74fc) for borders around interactive elements and as a background for visually distinct content blocks.
- Utilize 9999px border-radius for all button and tag elements to create a consistent 'pill' shape.
- Ensure generous padding around interactive elements: 20px horizontal for pill buttons and 32px all sides for square buttons.
- Employ the 0px border-radius for image cards and general containers to maintain a sharp, utilitarian aesthetic.
- Maintain a comfortable density with a base unit of 8px, manifesting as 16px element gaps and 40px section gaps.

### Don't
- Avoid using serif fonts or system UI fonts that would dilute the custom brand typography.
- Do not introduce new primary colors; the brand relies on a restrained achromatic palette with Royal Purple as the main accent.
- Refrain from using rounded corners on primary content cards or container backgrounds unless explicitly specified with 12px or 9999px radii.
- Do not use subtle shadows for elevation on general UI elements; reserve the Shadow Violet (#48316a) shadow only for primary action buttons.
- Avoid excessively long line lengths for body text; keep type compact with tight letter-spacing.
- Do not deviate from the specified capitalization and tracking ratios for headings and links; these are core to the brand's voice.
- Do not use gradients; the system relies on flat colors and sharp contrasts.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas White | `#fcf7fa` | Dominant background for the page, creating a clean white space. |
| 1 | Background White | `#ffffff` | Background for cards, interactive elements, and input fields, slightly elevating them from the canvas. |
| 2 | Royal Purple Accent | `#ac74fc` | A background for prominent interactive sections or hero elements, providing a strong visual break and brand color application. |

## Imagery

The visual language focuses on stylized product illustrations featuring people interacting with the mobility devices, rendered with a light, almost ethereal quality against white or monochromatic backgrounds. Photography, when used, shows tight product crops or contextual usage that emphasizes the product itself, not lifestyle. Icons are simple, outlined, and monochromatic, aligning with the utilitarian UI. Imagery Density: Image-heavy hero sections balance with text-dominant areas, but visuals are central to product explanation and brand identity.

## Layout

The page uses a maximum-width contained model for most content, with a centered alignment, although the hero section appears full-bleed for the product carousel. The hero pattern displays multiple product variations as illustrations, centrally located. Section rhythm alternates between the soft Canvas White background and full-bleed Royal Purple blocks for highlighting content. Content arrangement frequently features centered text stacks for headings and single-column body content, or a multi-column grid for product/news cards, where image and text are integrated within defined card boundaries. Navigation is a minimalist top bar, with elements often appearing ghosted or with minimal styling.

## Agent Prompt Guide

Quick Color Reference: 
- Text: Midnight Black (#000000)
- Background: Canvas White (#fcf7fa)
- Border: Midnight Black (#000000)
- Accent: Royal Purple (#ac74fc)
- primary action: #c181ff (filled action)

Example Component Prompts:
- Create a section divider with a 1px solid Midnight Black (#000000) line, 40px vertical spacing from content.
- Design a primary button: 'Reserve Now' using Main Action Purple (#c181ff) background, Midnight Black (#000000) text (size 16px, SerialC-Heavy 400), 9999px border-radius, 0px vertical padding, 20px horizontal padding, with a 0px 2px 0px 0px Shadow Violet (#48316a) box-shadow.
- Generate a navigation link: 'Company' using ABCCameraPlainVariable 400 at 16px, Midnight Black (#000000) text, with 16px padding on all sides, and a 12px border-radius.
- Build a feature card: 'TM-B: Seeing Deeper' on a Background White (#ffffff) surface, 0px radius, 1px solid Midnight Black (#000000) border, 24px internal padding, all text in ABCCameraPlainVariable 400 in Midnight Black (#000000).

## Similar Brands

- **Aether Apparel** — Uses premium, minimalistic typography with tight tracking, and relies on a mostly achromatic palette with one strong accent color.
- **Bikes by Brompton** — Features clean product photography and a focus on essential information hierarchy with a utilitarian feel.
- **Arc'teryx** — Employs technical, precise typography, a restrained color palette, and clear visual separation of content blocks.
- **Nothing (tech brand)** — Leverages a stark, high-contrast black and white aesthetic with sparse but impactful use of color for key interactive elements.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #fcf7fa;
  --color-background-white: #ffffff;
  --color-midnight-black: #000000;
  --color-input-border-dark: #212121;
  --color-button-black: #1a1a1a;
  --color-royal-purple: #ac74fc;
  --color-deep-violet: #381b5e;
  --color-action-blue: #1276a9;
  --color-shadow-violet: #48316a;
  --color-main-action-purple: #c181ff;
  --color-success-green: #b1ff8f;

  /* Typography — Font Families */
  --font-abccameraplainvariable: 'ABCCameraPlainVariable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-serialc-heavy: 'SerialC-Heavy', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-serialc: 'SerialC', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: 0.6px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.43;
  --tracking-body-sm: 0.88px;
  --text-body: 16px;
  --leading-body: 1.2;
  --tracking-body: -0.26px;
  --text-subheading: 20px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.5px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.13;
  --tracking-heading-sm: -1px;
  --text-heading: 32px;
  --leading-heading: 1.09;
  --tracking-heading: -1.44px;
  --text-heading-lg: 44px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -2.07px;
  --text-display: 60px;
  --leading-display: 0.93;
  --tracking-display: -3px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-bold: 700;
  --font-weight-black: 900;

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
  --spacing-72: 72px;
  --spacing-80: 80px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 16px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-xl: 12px;
  --radius-full: 56px;
  --radius-full-2: 9999px;

  /* Named Radii */
  --radius-tags: 9999px;
  --radius-cards: 0px;
  --radius-links: 12px;
  --radius-buttons: 9999px;
  --radius-specificbuttons: 56px;

  /* Shadows */
  --shadow-subtle: rgb(72, 49, 106) 0px 2px 0px 0px;

  /* Surfaces */
  --surface-canvas-white: #fcf7fa;
  --surface-background-white: #ffffff;
  --surface-royal-purple-accent: #ac74fc;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #fcf7fa;
  --color-background-white: #ffffff;
  --color-midnight-black: #000000;
  --color-input-border-dark: #212121;
  --color-button-black: #1a1a1a;
  --color-royal-purple: #ac74fc;
  --color-deep-violet: #381b5e;
  --color-action-blue: #1276a9;
  --color-shadow-violet: #48316a;
  --color-main-action-purple: #c181ff;
  --color-success-green: #b1ff8f;

  /* Typography */
  --font-abccameraplainvariable: 'ABCCameraPlainVariable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-serialc-heavy: 'SerialC-Heavy', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-serialc: 'SerialC', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: 0.6px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.43;
  --tracking-body-sm: 0.88px;
  --text-body: 16px;
  --leading-body: 1.2;
  --tracking-body: -0.26px;
  --text-subheading: 20px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.5px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.13;
  --tracking-heading-sm: -1px;
  --text-heading: 32px;
  --leading-heading: 1.09;
  --tracking-heading: -1.44px;
  --text-heading-lg: 44px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -2.07px;
  --text-display: 60px;
  --leading-display: 0.93;
  --tracking-display: -3px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-80: 80px;

  /* Border Radius */
  --radius-xl: 12px;
  --radius-full: 56px;
  --radius-full-2: 9999px;

  /* Shadows */
  --shadow-subtle: rgb(72, 49, 106) 0px 2px 0px 0px;
}
```

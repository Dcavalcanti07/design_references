# monday.com — Style Reference
> Vibrant organized workspace — like a digital desk splashed with colorful sticky notes and neatly arranged tools.

**Theme:** light

This design system feels like a vibrant, organized digital workspace, balancing playful accents with robust functionality. It uses a very accessible light theme with high-contrast text and a central, vivid violet (#6161ff) to draw attention to primary actions. The abundant use of color, especially in product card backgrounds, creates a rich and dynamic interface, while rounded elements (160px pill buttons, 24px cards) soften the structured grid layout. A diverse set of gradients adds energetic flair and a sense of continuous motion.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Text Primary | `#333333` | `--color-text-primary` | Primary text for headings, body copy, and form inputs. Provides strong contrast against light backgrounds. |
| Text Muted | `#676879` | `--color-text-muted` | Secondary text for less prominent information, metadata, and icons. Offers a softer visual presence. |
| Canvas Background | `#ffffff` | `--color-canvas-background` | The foundational background color for the overall page and elevated surfaces. |
| Surface Accent | `#f5f6f8` | `--color-surface-accent` | Background for cards, badges, and subtle section differentiation; a soft, near-white neutral. |
| Interactive Violet | `#6161ff` | `--color-interactive-violet` | Primary action buttons, interactive elements, and key brand highlights. Its vivid saturation ensures visibility and draws the eye. |
| Outline Ebony | `#000000` | `--color-outline-ebony` | Border color for outlined buttons and subtle UI elements. Acts as a strong, grounding outline. |
| Border Silver | `#d0d4e4` | `--color-border-silver` | Subtle borders for cards and other structural elements, providing definition without harshness. |
| Interactive Graphite | `#535768` | `--color-interactive-graphite` | Text color for navigation, links, and specific interactive elements. Provides contrast while maintaining a modern, desaturated feel. |
| Card Mint | `#bcfe90` | `--color-card-mint` | Observed in card backgroundColor. |
| Card Lavender | `#eddff7` | `--color-card-lavender` | Observed in card backgroundColor. |
| Card Sky | `#abf0ff` | `--color-card-sky` | Observed in card backgroundColor. |
| Card Sunset | `#ff8940` | `--color-card-sunset` | Observed in card backgroundColor. |
| Card Pale Blue | `#e7ecff` | `--color-card-pale-blue` | A very light, almost white blue background used for subtle card differentiation. |
| Card Ocean | `#93beff` | `--color-card-ocean` | Observed in card backgroundColor. |
| Card Ice | `#d1faff` | `--color-card-ice` | A very light, cool blue background for cards, almost white but with a clear cool tint. |
| Button Indigo | `#9450fd` | `--color-button-indigo` | Alternative button background for showcasing varied product or feature categories. |
| Button Sky | `#3ac9ff` | `--color-button-sky` | Alternative button background for showcasing varied product or feature categories. |
| Button Teal | `#2a5c40` | `--color-button-teal` | Supporting palette color with insufficient usage evidence for a stronger role. Extracted usage does not support a distinct primary control color. |
| Badge Light Blue | `#dbdbff` | `--color-badge-light-blue` | Background for feature badges, providing a light, cheerful indicator. |
| Gradient Vibrant Flow | `linear-gradient(90deg, rgb(254, 129, 228), rgb(254, 129, 228) 31%, rgb(253, 169, 0) 88%)` | `--color-gradient-vibrant-flow` | Decorative gradient for dynamic visual elements, shifting from hot pink to warm orange. |
| Gradient Spectrum Ring | `conic-gradient(from 270deg, rgb(129, 129, 255) 15%, rgb(51, 219, 219) 40%, rgb(51, 213, 142) 55%, rgb(255, 214, 51) 65%, rgb(252, 82, 125) 85%, rgb(129, 129, 255) 100%)` | `--color-gradient-spectrum-ring` | Conic gradient for circular or radial elements, creating a multi-color animated-gif-like effect. |

## Tokens — Typography

### Poppins — The primary typeface for all text content. Its clean, geometric forms maintain readability across various sizes while its multiple weights (from light 300 to bold 700) support a full typographic hierarchy. The tight negative letter-spacing on larger headlines creates a modern, cohesive feel, while normal spacing is used for body text. · `--font-poppins`
- **Substitute:** sans-serif
- **Weights:** 300, 400, 500, 700
- **Sizes:** 8px, 12px, 13px, 14px, 16px, 18px, 20px, 22px, 24px, 28px, 32px, 36px, 40px, 48px, 52px, 56px, 64px
- **Line height:** 1.15, 1.20, 1.30, 1.31, 1.40, 1.45, 1.50, 1.60, 1.69, 2.00, 2.29, 2.46
- **Letter spacing:** -0.0400em, -0.0200em, -0.0150em, -0.0110em, -0.0100em, 0.2000em
- **Role:** The primary typeface for all text content. Its clean, geometric forms maintain readability across various sizes while its multiple weights (from light 300 to bold 700) support a full typographic hierarchy. The tight negative letter-spacing on larger headlines creates a modern, cohesive feel, while normal spacing is used for body text.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.5 | — | `--text-caption` |
| body-sm | 14px | 1.5 | — | `--text-body-sm` |
| body | 18px | 1.5 | — | `--text-body` |
| body-lg | 22px | 1.5 | — | `--text-body-lg` |
| heading-sm | 28px | 1.3 | — | `--text-heading-sm` |
| heading | 32px | 1.3 | — | `--text-heading` |
| heading-lg | 40px | 1.3 | — | `--text-heading-lg` |
| display-sm | 52px | 1.3 | — | `--text-display-sm` |
| display | 64px | 1.3 | — | `--text-display` |

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
| 96 | 96px | `--spacing-96` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 24px |
| input | 0px |
| badges | 6px |
| images | 12px |
| buttons | 160px |
| general | 6px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| xl | `rgba(205, 208, 223, 0.4) 0px 2px 48px 0px` | `--shadow-xl` |
| xl-2 | `rgba(0, 0, 0, 0.15) 0px 5px 45px 0px` | `--shadow-xl-2` |
| xl-3 | `rgba(0, 0, 0, 0.15) 0px 4px 40px 0px` | `--shadow-xl-3` |
| xl-4 | `rgba(0, 0, 0, 0.4) 0px 5px 55px 0px` | `--shadow-xl-4` |
| subtle | `rgb(0, 0, 0) 0px -2px 0px 0px inset` | `--shadow-subtle` |

### Layout

- **Section gap:** 48px
- **Card padding:** 24px
- **Element gap:** 8px

## Components

### Primary Call to Action Button
**Role:** Interactive Element

Buttons are filled with 'Interactive Violet' (#6161ff) and have 'Canvas Background' (#ffffff) text, with a generous 160px border-radius creating a pill shape. Padding is 13px vertical and 24px horizontal. Text is Poppins 16px.

### Outlined Call to Action Button
**Role:** Interactive Element

Buttons are transparent with an 'Outline Ebony' (#000000) border, 'Text Primary' (#333333) text, and a 160px border-radius producing a pill shape. Padding is 13px vertical and 24px horizontal. Text is Poppins 16px.

### Text Link Button
**Role:** Interactive Element

Buttons are transparent with 'Text Primary' (#333333) text and no explicit border-radius. These are used for inline or subtly presented actions.

### Feature Card
**Role:** Content Display

Cards have a 'Canvas Background' (#ffffff) and a 24px border-radius. They are elevated with a soft shadow at rgba(205, 208, 223, 0.4) 0px 2px 48px 0px. Internal padding is 24px.

### Basic Card
**Role:** Content Display

Cards have a transparent background with 0px border-radius and no shadow, used for grouping content without strong visual separation. Internal padding is 24px.

### Accent Background Card
**Role:** Content Display

Cards often use varying 'accent' background colors like 'Card Lavender' (#eddff7) or 'Card Mint' (#bcfe90), with 0px border-radius and no shadow to highlight specific content blocks. Internal padding is 24px.

### Input Field
**Role:** Data Entry

Input fields have a 'Canvas Background' (#ffffff), 'Text Primary' (#333333) text, and 'Text Primary' (#333333) border color with 0px border-radius. Padding is 24px vertical on left/right and 40px left/right. Text is Poppins 22px.

### Informational Badge
**Role:** Categorization/Tagging

Badges have a transparent background with 'Text Primary' (#333333) text and minimal 4px 8px padding. Border radius is 5.6px.

### Feature Category Badge
**Role:** Categorization/Tagging

Badges have a 'Surface Accent' (#f5f6f8) background with 'Text Primary' (#333333) text. Border-radius is 12px and padding is 16px vertical and 28px left/16px right.

## Do's and Don'ts

### Do
- Do use 'Interactive Violet' (#6161ff) for primary call-to-action buttons, ensuring text is 'Canvas Background' (#ffffff).
- Do apply a 160px border-radius to all buttons to create a consistent pill shape.
- Do use Poppins 20px, weight 700 with -0.015em letter spacing for major section headings to maintain legibility and impact.
- Do utilize the specific accent colors like 'Card Mint' (#bcfe90) and 'Card Sky' (#abf0ff) as backgrounds for feature cards to add visual variety and categorization.
- Do ensure interactive elements use 'Interactive Graphite' (#535768) for text and 'Border Silver' (#d0d4e4) for subtle borders in neutral states.
- Do apply the rgba(205, 208, 223, 0.4) 0px 2px 48px 0px shadow for elevated cards to create clear visual hierarchy.
- Do employ 'elementGap' at 8px for consistent spacing between inline and block elements.

### Don't
- Don't use any color other than 'Interactive Violet' (#6161ff) for primary CTA button backgrounds; use outlined or text variants for secondary actions.
- Don't use square buttons or cards; maintain the established 160px or 24px border-radii for interactive and content elements respectively.
- Don't deviate from Poppins for any text element; other fonts will appear off-brand.
- Don't overcrowd sections; maintain a minimum 'sectionGap' of 48px between major content blocks.
- Don't introduce new shadow values; use the established rgba(205, 208, 223, 0.4) 0px 2px 48px 0px for elevation or no shadow for flat elements.
- Don't center align body text; prefer left alignment with 'Text Primary' (#333333) for optimal readability.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas | `#ffffff` | Dominant page background, primary canvas for content, and general elevated surfaces. |
| 1 | Surface Accent Light | `#f5f6f8` | Used for differentiated cards, badges, and subtle background variation, offering a slight visual lift without strong contrast. |
| 2 | Card Accents | `#eddff7` | A range of accent background colors like Lavender (#eddff7), Mint (#bcfe90), Sky (#abf0ff), and Sunset (#ff8940) for specific cards to distinguish content types or add visual vibrancy. |

## Elevation

- **Feature Card:** `rgba(205, 208, 223, 0.4) 0px 2px 48px 0px`

## Imagery

The site uses a mix of subtle product screenshots, abstract gradient graphics, and simple icons. Product screenshots are often blurred or contained within a UI mock-up, suggesting functionality without being overly detailed. Abstract graphics, particularly those incorporating the vibrant gradients, serve a decorative and energetic purpose, often as background elements or subtle accents. Icons are generally minimalist, often outlined or mono-color, appearing both within the UI for navigation/features and as more decorative elements. The overall language is high-tech playful, with visuals serving to energize rather than explicitly demonstrate.

## Layout

The page exhibits a max-width contained layout, though specific hero sections can span full-width. The hero section often features a centered headline over a subtle background, with primary actions prominently in the center. Content sections alternate between visually distinct blocks, often with a consistent vertical rhythm. Many sections employ a 2-column or 3-column grid for features, cards, and interactive elements. The overall density is comfortable, ensuring sufficient breathing room around content blocks, with 48px section gaps providing clear visual breaks. Navigation elements are consistently at the top, often sticky, simplifying user flow.

## Agent Prompt Guide

Quick Color Reference:
text: #333333
background: #ffffff
border: #d0d4e4
accent: #6161ff
primary action: #6161ff (filled action)

Example Component Prompts:
1. Create a Primary Call to Action Button: 'Interactive Violet' (#6161ff) background, 'Canvas Background' (#ffffff) text, 160px border-radius, Poppins 16px weight 500, 13px vertical and 24px horizontal padding. Content: 'Get Started'.
2. Create a Feature Card: 'Canvas Background' (#ffffff) background, 24px border-radius, shadow: rgba(205, 208, 223, 0.4) 0px 2px 48px 0px, 24px internal padding. Headline: Poppins 24px weight 700 'Text Primary' (#333333). Body text: Poppins 16px weight 400 'Text Primary' (#333333).
3. Create an Input Field: 'Canvas Background' (#ffffff) background, 'Text Primary' (#333333) text, 'Text Primary' (#333333) border color, 0px border-radius, Poppins 22px weight 400, 24px vertical and 40px left/right padding. Placeholder text: Poppins 22px weight 400 'Text Muted' (#676879).
4. Create a Feature Category Badge: 'Surface Accent' (#f5f6f8) background, 'Text Primary' (#333333) text, 12px border-radius, Poppins 16px weight 500, 16px vertical and 16px/28px horizontal padding. Content: 'Projects & Tasks'.

## Similar Brands

- **Airtable** — Shares a vibrant, color-rich UI on a light background, emphasizing playful productivity with distinct accent colors for data categorization and interactive elements.
- **Notion** — Employs clean, rounded UI elements and a focus on high-contrast text on a light canvas, paired with a subtle use of color for functional elements like tags and status.
- **Asana** — Features a similar use of distinct, saturated colors for task and project categorization, balanced with a largely neutral interface and soft, legible typography.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-text-primary: #333333;
  --color-text-muted: #676879;
  --color-canvas-background: #ffffff;
  --color-surface-accent: #f5f6f8;
  --color-interactive-violet: #6161ff;
  --color-outline-ebony: #000000;
  --color-border-silver: #d0d4e4;
  --color-interactive-graphite: #535768;
  --color-card-mint: #bcfe90;
  --color-card-lavender: #eddff7;
  --color-card-sky: #abf0ff;
  --color-card-sunset: #ff8940;
  --color-card-pale-blue: #e7ecff;
  --color-card-ocean: #93beff;
  --color-card-ice: #d1faff;
  --color-button-indigo: #9450fd;
  --color-button-sky: #3ac9ff;
  --color-button-teal: #2a5c40;
  --color-badge-light-blue: #dbdbff;
  --color-gradient-vibrant-flow: #fe81e4;
  --gradient-gradient-vibrant-flow: linear-gradient(90deg, rgb(254, 129, 228), rgb(254, 129, 228) 31%, rgb(253, 169, 0) 88%);
  --color-gradient-spectrum-ring: #8181ff;
  --gradient-gradient-spectrum-ring: conic-gradient(from 270deg, rgb(129, 129, 255) 15%, rgb(51, 219, 219) 40%, rgb(51, 213, 142) 55%, rgb(255, 214, 51) 65%, rgb(252, 82, 125) 85%, rgb(129, 129, 255) 100%);

  /* Typography — Font Families */
  --font-poppins: 'Poppins', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --text-body: 18px;
  --leading-body: 1.5;
  --text-body-lg: 22px;
  --leading-body-lg: 1.5;
  --text-heading-sm: 28px;
  --leading-heading-sm: 1.3;
  --text-heading: 32px;
  --leading-heading: 1.3;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.3;
  --text-display-sm: 52px;
  --leading-display-sm: 1.3;
  --text-display: 64px;
  --leading-display: 1.3;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;
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
  --spacing-96: 96px;

  /* Layout */
  --section-gap: 48px;
  --card-padding: 24px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-3xl-2: 40px;
  --radius-full: 100px;
  --radius-full-2: 160px;

  /* Named Radii */
  --radius-cards: 24px;
  --radius-input: 0px;
  --radius-badges: 6px;
  --radius-images: 12px;
  --radius-buttons: 160px;
  --radius-general: 6px;

  /* Shadows */
  --shadow-xl: rgba(205, 208, 223, 0.4) 0px 2px 48px 0px;
  --shadow-xl-2: rgba(0, 0, 0, 0.15) 0px 5px 45px 0px;
  --shadow-xl-3: rgba(0, 0, 0, 0.15) 0px 4px 40px 0px;
  --shadow-xl-4: rgba(0, 0, 0, 0.4) 0px 5px 55px 0px;
  --shadow-subtle: rgb(0, 0, 0) 0px -2px 0px 0px inset;

  /* Surfaces */
  --surface-canvas: #ffffff;
  --surface-surface-accent-light: #f5f6f8;
  --surface-card-accents: #eddff7;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-text-primary: #333333;
  --color-text-muted: #676879;
  --color-canvas-background: #ffffff;
  --color-surface-accent: #f5f6f8;
  --color-interactive-violet: #6161ff;
  --color-outline-ebony: #000000;
  --color-border-silver: #d0d4e4;
  --color-interactive-graphite: #535768;
  --color-card-mint: #bcfe90;
  --color-card-lavender: #eddff7;
  --color-card-sky: #abf0ff;
  --color-card-sunset: #ff8940;
  --color-card-pale-blue: #e7ecff;
  --color-card-ocean: #93beff;
  --color-card-ice: #d1faff;
  --color-button-indigo: #9450fd;
  --color-button-sky: #3ac9ff;
  --color-button-teal: #2a5c40;
  --color-badge-light-blue: #dbdbff;
  --color-gradient-vibrant-flow: #fe81e4;
  --color-gradient-spectrum-ring: #8181ff;

  /* Typography */
  --font-poppins: 'Poppins', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --text-body: 18px;
  --leading-body: 1.5;
  --text-body-lg: 22px;
  --leading-body-lg: 1.5;
  --text-heading-sm: 28px;
  --leading-heading-sm: 1.3;
  --text-heading: 32px;
  --leading-heading: 1.3;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.3;
  --text-display-sm: 52px;
  --leading-display-sm: 1.3;
  --text-display: 64px;
  --leading-display: 1.3;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-3xl-2: 40px;
  --radius-full: 100px;
  --radius-full-2: 160px;

  /* Shadows */
  --shadow-xl: rgba(205, 208, 223, 0.4) 0px 2px 48px 0px;
  --shadow-xl-2: rgba(0, 0, 0, 0.15) 0px 5px 45px 0px;
  --shadow-xl-3: rgba(0, 0, 0, 0.15) 0px 4px 40px 0px;
  --shadow-xl-4: rgba(0, 0, 0, 0.4) 0px 5px 55px 0px;
  --shadow-subtle: rgb(0, 0, 0) 0px -2px 0px 0px inset;
}
```

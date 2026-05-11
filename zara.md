# Zara — Style Reference
> High-fashion starkness on white marble. Unyielding contrast and precise lines on a luminous white canvas.

**Theme:** light

Zara's interface projects an unyielding, high-fashion minimalism through a stark monochrome palette and precise typography. The visual brand is built on a high-contrast black-on-white foundation, creating a sophisticated backdrop where product photography becomes the primary source of color and texture. An absence of soft edges or expressive spacing reinforces a refined, almost austere aesthetic.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Pitch Black | `#000000` | `--color-pitch-black` | Primary text, borders, icons, form outlines. This is the dominant dark against the luminous white. |
| Luminous White | `#ffffff` | `--color-luminous-white` | Page backgrounds, card surfaces, button fills – the expansive canvas for all content. |
| Subtle Gray | `#757575` | `--color-subtle-gray` | Secondary text, subtle borders, inactive states – provides a slight tonal variation without introducing color. |

## Tokens — Typography

### Helvetica Now Text — Universal sans-serif for all text, conveying a contemporary and no-nonsense tone. The consistent use of only two weights across all sizes reinforces the brand's directness. · `--font-helvetica-now-text`
- **Substitute:** Helvetica Neue, Arial, sans-serif
- **Weights:** 300, 400
- **Sizes:** 11px, 12px, 13px, 15px, 16px
- **Line height:** 1.00, 1.23, 1.45, 1.50, 1.54, 1.60
- **Letter spacing:** normal
- **Role:** Universal sans-serif for all text, conveying a contemporary and no-nonsense tone. The consistent use of only two weights across all sizes reinforces the brand's directness.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 11px | 1.5 | — | `--text-caption` |
| body-sm | 12px | 1.5 | — | `--text-body-sm` |
| body | 13px | 1.5 | — | `--text-body` |
| body-lg | 15px | 1.5 | — | `--text-body-lg` |
| heading-sm | 16px | 1.5 | — | `--text-heading-sm` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 12 | 12px | `--spacing-12` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 32 | 32px | `--spacing-32` |
| 48 | 48px | `--spacing-48` |
| 112 | 112px | `--spacing-112` |

### Border Radius

| Element | Value |
|---------|-------|
| all | 0px |

### Layout

- **Section gap:** 48px
- **Card padding:** 20px
- **Element gap:** 16px

## Components

### Ghost Link Button
**Role:** Secondary interactive elements within text (e.g., 'haz click aquí')

Black text (#000000), transparent background, no border, no padding. Visually indistinguishable from standard text until hovered, prioritizing content flow over overt interactivity.

### Default Input Field
**Role:** User input for forms (e.g., 'LOCATION', 'LANGUAGE')

Black text (#000000), white background (#ffffff), with a 1px solid black border. No border-radius. Features 16px right padding and 0px top/bottom/left padding, indicating content alignment within the field.

### Transparent Input Field
**Role:** Secondary input fields or those within larger interactive components

Black text (#000000), transparent background (rgba(0,0,0,0)), with a 1px solid black bottom border. No border-radius or padding, presenting as an underlined text input rather than a distinct box.

### Location/Language Dropdown
**Role:** Selector for locale-specific options

Functions as a Default Input Field, suggesting a click opens a modal or dropdown. Utilizes black text (#000000), white background (#ffffff), 1px solid black border. Padding: 0px top/bottom/left, 16px right.

## Do's and Don'ts

### Do
- Do use #000000 (Pitch Black) for all primary text and interactive element borders.
- Do use #ffffff (Luminous White) for all page and primary component backgrounds.
- Do maintain 0px border-radius for all elements, including buttons and input fields.
- Do apply Helvetica Now Text (or a suitable substitute like Helvetica Neue or Arial) for all typographic elements.
- Do use a consistent base spacing unit of 4px for fine-grained adjustments, and multiples for larger gaps (e.g., 12px, 16px, 20px, 32px, 48px).
- Do limit text colors to Pitch Black (#000000) for primary content and Subtle Gray (#757575) for secondary details.

### Don't
- Don't introduce any color outside of the defined monochrome palette of Pitch Black, Luminous White, and Subtle Gray.
- Don't use any rounded corners or soft edges on UI elements; maintain sharp, crisp rectangular forms.
- Don't use drop shadows or complex elevation effects; depth is created through direct contrast and layering.
- Don't apply padding to the top, bottom, or left of input fields listed under 'Default Input Field' or 'Location/Language Dropdown' to maintain precise alignment.
- Don't vary font weights significantly; adhere strictly to 300 and 400 for Helvetica Now Text.
- Don't use decorative flourishes or non-essential graphical elements; the design emphasizes functional minimalism.

## Imagery

Photography is the primary visual element, featuring full-bleed, high-quality fashion model shots. The imagery is often centrally composed, highlighting the product and model with a soft-focus, desaturated background that provides context without distraction. There's no specific masking or corner treatment; images appear as raw, uncropped editorial photography. Illustrations and abstract graphics are absent, as the visual load is carried almost entirely by fashion photography, serving a purely product showcase and atmospheric role.

## Layout

The page uses a maximum-width contained layout, with content (like the form) aligned to the left against an expansive white background. The hero section employs a split-screen approach, with a functional form on the left and a large, full-bleed photograph on the right. There are no alternating background bands; the entire canvas is Luminous White. Content arrangement is primarily vertical stacking for forms, paired with dominant, large-format imagery, creating a sense of spaciousness and clear hierarchy. Navigation appears minimal, implied rather than explicitly detailed in the provided view, with a prominent brand logo at the top-left.

## Agent Prompt Guide

Quick Color Reference:
- Text: #000000
- Background: #ffffff
- Accent/Secondary Text: #757575
- Border: #000000

Example Component Prompts:
- Create a page header: ZARA logo text at 32px Helvetica Now Text (weight unspecified, but visually bold) #000000, left-aligned, on a #ffffff background. 
- Create a text input labeled 'LOCATION': Text input box with 1px solid #000000 border, #ffffff background, #000000 text. Placeholder text should be #757575. Padding should be 0px top/bottom/left, 16px right. Font is Helvetica Now Text, 13px, weight 400.
- Create a 'CONTINUE' button: 1px solid #000000 border, 0px border-radius, background rgba(0,0,0,0). Text is 'CONTINUE' in all caps, #000000, Helvetica Now Text, 13px, weight 400. Padding: 2px top/bottom, 12px left/right. 
- Create a paragraph describing an offer: 'Si nos visitas desde las Canarias haz click' in Helvetica Now Text, 13px, weight 400, #000000. Followed by 'aquí' as a ghost link, same font/size/weight, #000000, no border or background, implying a clickable text element.

## Similar Brands

- **H&M** — Shares a stark, high-contrast monochrome aesthetic for its e-commerce interface, relying heavily on product photography for visual interest.
- **UNIQLO** — Employs a clean, minimalist layout with abundant white space and a focus on essential product presentation over decorative elements.
- **ASOS** — Utilizes a simple black and white palette to highlight fashion photography and simplify the user experience, emphasizing product browsing.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-pitch-black: #000000;
  --color-luminous-white: #ffffff;
  --color-subtle-gray: #757575;

  /* Typography — Font Families */
  --font-helvetica-now-text: 'Helvetica Now Text', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.5;
  --text-body-sm: 12px;
  --leading-body-sm: 1.5;
  --text-body: 13px;
  --leading-body: 1.5;
  --text-body-lg: 15px;
  --leading-body-lg: 1.5;
  --text-heading-sm: 16px;
  --leading-heading-sm: 1.5;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-112: 112px;

  /* Layout */
  --section-gap: 48px;
  --card-padding: 20px;
  --element-gap: 16px;

  /* Named Radii */
  --radius-all: 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-pitch-black: #000000;
  --color-luminous-white: #ffffff;
  --color-subtle-gray: #757575;

  /* Typography */
  --font-helvetica-now-text: 'Helvetica Now Text', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.5;
  --text-body-sm: 12px;
  --leading-body-sm: 1.5;
  --text-body: 13px;
  --leading-body: 1.5;
  --text-body-lg: 15px;
  --leading-body-lg: 1.5;
  --text-heading-sm: 16px;
  --leading-heading-sm: 1.5;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-112: 112px;
}
```

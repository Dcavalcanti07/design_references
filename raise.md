# Raise — Style Reference
> Architectural Blueprint Clarity

**Theme:** light

Open Collective builds upon a transparent, community-driven financial ecosystem aesthetic: a crisp white canvas paired with deep navy typography for clarity. Interface elements feel grounded yet accessible with subtle border treatments and soft shadows. The visual system prioritizes legibility and structure, using a single dominant brand blue to highlight critical actions and a carefully graded neutral palette for hierarchy. Components are clean and modern, favoring rounded shapes and clear spacing over ornate styling, while product views are kept neat and organized for easy data consumption.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card surfaces, ghost button backgrounds, default icon fill |
| Navy Ink | `#0f172b` | `--color-navy-ink` | Primary text, main headings, dark-filled buttons, dark navigation links, prominent icons |
| Ocean Blue | `#0c2764` | `--color-ocean-blue` | Primary action buttons, prominent headings where the brand needs to own the message |
| Slate Text | `#1d293d` | `--color-slate-text` | Secondary body text, subheadings, less prominent button text |
| Light Slate | `#62748e` | `--color-light-slate` | Muted body text, helper text, disabled states, subtle icon fills |
| Medium Slate | `#314158` | `--color-medium-slate` | Informational text in smaller UI elements like lists or data tables |
| Soft Gray Border | `#e2e8f0` | `--color-soft-gray-border` | Hairline borders, dividers, subtle input outlines, card subtle accent strokes |
| Lightest Gray Surface | `#f1f5f9` | `--color-lightest-gray-surface` | Subtle section backgrounds, slightly off-white surfaces for differentiation |
| Hint Gray | `#c3c6cb` | `--color-hint-gray` | Placeholder text, very subtle informational text |
| Inactive Chip | `#90a1b9` | `--color-inactive-chip` | Background for inactive or secondary chips/badges |

## Tokens — Typography

### Inter — The primary typeface for all textual content, from headings to body copy, chosen for its modern legibility and versatility across weights. · `--font-inter`
- **Substitute:** system-ui
- **Weights:** 400, 500, 600, 700, 800
- **Sizes:** 14px, 16px, 18px, 20px, 32px, 40px, 60px, 72px
- **Line height:** 1.00, 1.20, 1.25, 1.40, 1.43, 1.50, 1.56, 1.63, 1.71
- **Letter spacing:** -0.025, -0.025, -0.025, -0.025, -0.025, -0.025, -0.025, -0.025
- **OpenType features:** `"calt", "rlig"`
- **Role:** The primary typeface for all textual content, from headings to body copy, chosen for its modern legibility and versatility across weights.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 14px | 1.43 | -0.025px | `--text-caption` |
| body-sm | 16px | 1.5 | -0.025px | `--text-body-sm` |
| body | 18px | 1.56 | -0.025px | `--text-body` |
| subheading | 20px | 1.63 | -0.025px | `--text-subheading` |
| heading-sm | 32px | 1.25 | -0.025px | `--text-heading-sm` |
| heading | 40px | 1.2 | -0.025px | `--text-heading` |
| heading-lg | 60px | 1 | -0.025px | `--text-heading-lg` |
| display | 72px | 1 | -0.025px | `--text-display` |

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
| 96 | 96px | `--spacing-96` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 12px |
| buttons | 1.67772e+07px |
| general | 12px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| md | `rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1)...` | `--shadow-md` |

### Layout

- **Page max-width:** 1200px
- **Section gap:** 32px
- **Card padding:** 32px
- **Element gap:** 16px

## Components

### Primary Filled Button
**Role:** Main calls to action

Filled with Ocean Blue (#0c2764) background, Canvas White (#ffffff) text, and ultra-rounded (1.67772e+07px) corners. Padding is 0px vertical and 12px horizontal.

### Ghost Header Button
**Role:** Secondary navigation actions in the header

Ghost style with Canvas White (#ffffff) background, Slate Text (#1d293d) for text, no explicit border, and sharp 0px corners. Padding is 10px.

### Ghost Card Button
**Role:** Interactive elements within cards, like approval options

Canvas White (#ffffff) background, Navy Ink (#0f172b) text, with an ultra-rounded (1.67772e+07px) radius. Padding is 0px vertical and 12px horizontal. Border is 1px solid Soft Gray Border (#e2e8f0).

### Hero Action Button
**Role:** Prominent calls to action in hero sections

Canvas White (#ffffff) background, Navy Ink (#0f172b) text, 12px border radius. Generous padding of 24px on all sides.

### Standard Card
**Role:** Content containers, feature blocks, data displays

Canvas White (#ffffff) background with a 12px border radius. Uses a subtle shadow: rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1) 0px 4px 6px -4px. Internal padding is 32px on all sides.

## Do's and Don'ts

### Do
- Prioritize Canvas White (#ffffff) for all main backgrounds to maintain a clean, open feel.
- Use Navy Ink (#0f172b) for all primary body text and most prominent headings to ensure high contrast and readability.
- Apply Soft Gray Border (#e2e8f0) for all hairline borders and subtle dividers to create subtle visual separation without heavy lines.
- Adhere to an element spacing of 16px between smaller, related components to maintain a comfortable density.
- Use the 12px border radius for all cards and general grouped elements, reserving the ultra-rounded 1.67772e+07px for buttons only.
- Ensure all primary action buttons are Ocean Blue (#0c2764) with Canvas White (#ffffff) text to clearly distinguish calls to action.
- Employ the Inter font family for all typography, leveraging its various weights to establish hierarchy without introducing new typefaces.

### Don't
- Avoid using multiple accent colors; Ocean Blue (#0c2764) should be the singular vibrant brand color.
- Do not introduce heavy, opaque shadows; elements should feel subtly elevated with the existing shadow token if needed.
- Steer clear of gradients on buttons or primary UI elements; surfaces should remain flat and monochrome.
- Do not use highly saturated chromatic colors for information or status beyond defined semantic components.
- Avoid tight, compact layouts; maintain comfortable spacing, particularly 16px for element gaps and 32px for card padding.
- Do not use serif fonts or highly decorative typefaces; Inter's clean, sans-serif lines are fundamental to the system's clarity.
- Refrain from using bright, energetic colors for text; stick to the defined Navy Ink, Slate Text, and Light Slate for all textual content.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas White | `#ffffff` | Dominant page background, primary canvas for content. |
| 1 | Lightest Gray Surface | `#f1f5f9` | Subtle background for distinct sections or very light card variations. |
| 2 | Inactive Chip | `#90a1b9` | Background for secondary or inactive visual elements, suggesting a lower hierarchy. |
| 3 | Ocean Blue | `#0c2764` | Elevated, prominent surfaces like primary action buttons. |

## Elevation

- **Standard Card:** `rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1) 0px 4px 6px -4px`

## Imagery

This design system primarily uses minimal, stylized two-dimensional illustrations that often have a hand-drawn or watercolor aesthetic, as seen with the magnifying glass character. Photography and 3D renders appear to be absent. Icons are typically outlined or filled in a mono-color style, serving a functional purpose rather than decorative. Imagery is contained, rather than full-bleed, and often serves as explanatory content accompanying text blocks, maintaining a balanced density with text-dominant layouts.

## Layout

The page uses a maximum width contained layout, approximately 1200px wide, with content horizontally centered. The hero section is full-bleed but features a centered, prominent headline and descriptive text. Vertical rhythm is established through consistent section gaps, with content arranged in clear, often two-column text-and-visual patterns or stacked centered blocks. Cards are typically presented in grids for features. Navigation is a sticky top bar with clearly defined interactive elements.

## Agent Prompt Guide

primary action: #0c2764 (filled action)
Create a Primary Action Button: #0c2764 background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.

Example Component Prompts:
2. Design a Standard Card: Canvas White (#ffffff) background, 12px border radius, using the defined shadow rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1) 0px 4px 6px -4px. Internal padding of 32px. Use Navy Ink (#0f172b) for titles and Light Slate (#62748e) for descriptive text within.
3. Build a Navigation Bar: Canvas White (#ffffff) background, Navy Ink (#0f172b) for menu text. Include a Ghost Header Button 'Log In' with Canvas White (#ffffff) background, Slate Text (#1d293d) text, 0px radius, 10px padding.
4. Create an 'Approve' action within a card: Use a Ghost Card Button with Canvas White (#ffffff) background, Navy Ink (#0f172b) text, ultra-rounded (1.67772e+07px) radius, and 1px solid Soft Gray Border (#e2e8f0).

## Similar Brands

- **Airtable** — Both use a bright, spacious light theme with strong blue accents and clean, structured UI components.
- **Figma** — Both systems emphasize clear information architecture with a minimal white background, strong typography for hierarchy, and a distinct brand color for interactive elements.
- **Linear** — Similar approach to clean, border-defined components and minimal shadows on light surfaces, prioritizing functionality and clarity.
- **Notion** — Shares a document-like white canvas feel with well-defined content blocks, strong readability focus, and functional use of a limited color palette.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-navy-ink: #0f172b;
  --color-ocean-blue: #0c2764;
  --color-slate-text: #1d293d;
  --color-light-slate: #62748e;
  --color-medium-slate: #314158;
  --color-soft-gray-border: #e2e8f0;
  --color-lightest-gray-surface: #f1f5f9;
  --color-hint-gray: #c3c6cb;
  --color-inactive-chip: #90a1b9;

  /* Typography — Font Families */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.43;
  --tracking-caption: -0.025px;
  --text-body-sm: 16px;
  --leading-body-sm: 1.5;
  --tracking-body-sm: -0.025px;
  --text-body: 18px;
  --leading-body: 1.56;
  --tracking-body: -0.025px;
  --text-subheading: 20px;
  --leading-subheading: 1.63;
  --tracking-subheading: -0.025px;
  --text-heading-sm: 32px;
  --leading-heading-sm: 1.25;
  --tracking-heading-sm: -0.025px;
  --text-heading: 40px;
  --leading-heading: 1.2;
  --tracking-heading: -0.025px;
  --text-heading-lg: 60px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -0.025px;
  --text-display: 72px;
  --leading-display: 1;
  --tracking-display: -0.025px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;
  --font-weight-extrabold: 800;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-96: 96px;

  /* Layout */
  --page-max-width: 1200px;
  --section-gap: 32px;
  --card-padding: 32px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-xl: 12px;
  --radius-2xl: 16px;

  /* Named Radii */
  --radius-cards: 12px;
  --radius-buttons: 1.67772e+07px;
  --radius-general: 12px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1) 0px 4px 6px -4px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-lightest-gray-surface: #f1f5f9;
  --surface-inactive-chip: #90a1b9;
  --surface-ocean-blue: #0c2764;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-navy-ink: #0f172b;
  --color-ocean-blue: #0c2764;
  --color-slate-text: #1d293d;
  --color-light-slate: #62748e;
  --color-medium-slate: #314158;
  --color-soft-gray-border: #e2e8f0;
  --color-lightest-gray-surface: #f1f5f9;
  --color-hint-gray: #c3c6cb;
  --color-inactive-chip: #90a1b9;

  /* Typography */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.43;
  --tracking-caption: -0.025px;
  --text-body-sm: 16px;
  --leading-body-sm: 1.5;
  --tracking-body-sm: -0.025px;
  --text-body: 18px;
  --leading-body: 1.56;
  --tracking-body: -0.025px;
  --text-subheading: 20px;
  --leading-subheading: 1.63;
  --tracking-subheading: -0.025px;
  --text-heading-sm: 32px;
  --leading-heading-sm: 1.25;
  --tracking-heading-sm: -0.025px;
  --text-heading: 40px;
  --leading-heading: 1.2;
  --tracking-heading: -0.025px;
  --text-heading-lg: 60px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -0.025px;
  --text-display: 72px;
  --leading-display: 1;
  --tracking-display: -0.025px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-96: 96px;

  /* Border Radius */
  --radius-xl: 12px;
  --radius-2xl: 16px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1) 0px 4px 6px -4px;
}
```

# Oevra — Style Reference
> Misty Forest Canvas — a serene, expansive background in soft green hues, grounding light, transparent elements.

**Theme:** light

Oevra employs a muted, nature-inspired aesthetic, using a soft, desaturated green as its primary chromatic anchor against predominantly monochromatic backgrounds. The system is characterized by spacious layouts, delicate typography, and a subtle application of surface transparency and soft edge rounding, creating an ethereal yet grounded feel. Typefaces are intentionally varied, pairing a contemporary sans-serif for headings with a more classic system font for utilitarian elements, often with generous letter-spacing for visual airiness. Components are lightweight and favor borders or ghost styles over solid fills, contributing to the overall sense of understated presence.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, light card surfaces, default UI elements like text and borders |
| Midnight Black | `#000000` | `--color-midnight-black` | Primary text, headers, and strong outlines |
| Moss Green | `#778643` | `--color-moss-green` | Primary action backgrounds, accented text, and interactive elements. Its moderate saturation provides a subtle yet distinct brand presence |
| Charcoal Gray | `#4e4e4e` | `--color-charcoal-gray` | Secondary text, muted links, and soft UI borders for hierarchical separation |
| Whisper Gray | `#c8c8c8` | `--color-whisper-gray` | Subtle background accents, dividers and other low-prominence UI elements |
| Smoke Glass | `#ffffff1a` | `--color-smoke-glass` | Background for transparent cards, providing a frosted glass effect on top of the main canvas |
| Pale Mist | `#efefef` | `--color-pale-mist` | Subtly darker backgrounds for layered surfaces or sections, indicated by `--color-lightGrey` token |

## Tokens — Typography

### space-regular — space-regular — detected in extracted data but not described by AI · `--font-space-regular`
- **Weights:** 400
- **Sizes:** 8px, 12px, 14px, 15px
- **Line height:** 1.2, 1.25, 1.3, 1.5
- **Role:** space-regular — detected in extracted data but not described by AI

### Suisse Light — Display and prominent headings. The light weight of the sans-serif font creates a sense of airy sophistication and prevents headlines from feeling overbearing. · `--font-suisse-light`
- **Substitute:** Helvetica Neue
- **Weights:** 400
- **Sizes:** 34px, 45px, 75px, 90px
- **Line height:** 1.00, 1.10
- **Role:** Display and prominent headings. The light weight of the sans-serif font creates a sense of airy sophistication and prevents headlines from feeling overbearing.

### Suisse Regular — Body text, footnotes, and supporting copy. It maintains clarity within dense blocks of information. · `--font-suisse-regular`
- **Substitute:** Helvetica Neue
- **Weights:** 400
- **Sizes:** 12px, 14px, 15px
- **Line height:** 1.20, 1.25, 1.30
- **Role:** Body text, footnotes, and supporting copy. It maintains clarity within dense blocks of information.

### Space Mono — Utility text, navigation labels, and small UI elements. The monospace nature adds a technical, precise undertone. · `--font-space-mono`
- **Substitute:** Space Mono
- **Weights:** 
- **Sizes:** 
- **Line height:** 
- **Role:** Utility text, navigation labels, and small UI elements. The monospace nature adds a technical, precise undertone.

### System Sans-serif — Fallback and minimal UI labels, ensuring consistent display across platforms. · `--font-system-sans-serif`
- **Substitute:** system-ui
- **Weights:** 
- **Sizes:** 
- **Line height:** 
- **Role:** Fallback and minimal UI labels, ensuring consistent display across platforms.

### ui-sans-serif — ui-sans-serif — detected in extracted data but not described by AI · `--font-ui-sans-serif`
- **Weights:** 400
- **Sizes:** 8px
- **Line height:** 1.5
- **Role:** ui-sans-serif — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body-lg | 15px | 1.2 | — | `--text-body-lg` |
| heading-sm | 34px | 1 | — | `--text-heading-sm` |
| heading | 45px | 1.1 | — | `--text-heading` |
| heading-lg | 75px | 1.1 | — | `--text-heading-lg` |
| display | 90px | 1.1 | — | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** spacious

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 8 | 8px | `--spacing-8` |
| 11 | 11px | `--spacing-11` |
| 12 | 12px | `--spacing-12` |
| 15 | 15px | `--spacing-15` |
| 19 | 19px | `--spacing-19` |
| 23 | 23px | `--spacing-23` |
| 30 | 30px | `--spacing-30` |
| 38 | 38px | `--spacing-38` |
| 45 | 45px | `--spacing-45` |
| 60 | 60px | `--spacing-60` |
| 83 | 83px | `--spacing-83` |
| 120 | 120px | `--spacing-120` |
| 135 | 135px | `--spacing-135` |
| 180 | 180px | `--spacing-180` |
| 218 | 218px | `--spacing-218` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 15px |
| buttons | 22.5px |

### Layout

- **Page max-width:** 1425px
- **Section gap:** 30px
- **Card padding:** 30px
- **Element gap:** 15px

## Components

### Ghost Button (White)
**Role:** Header navigation links and secondary calls to action.

Transparent background with White text and 1px White border. No padding specified, suggesting inherited or minimal layout-driven spacing. Features 0px border-radius for sharp edges, contrasting with rounded filled buttons.

### Ghost Button (Charcoal)
**Role:** Muted actions or tertiary navigation.

Transparent background with Charcoal Gray text and 1px Charcoal Gray border. No padding, 0px border-radius, maintaining a sharp and minimal appearance.

### Primary Action Button
**Role:** Key interactions and calls to action.

Solid Moss Green background with Canvas White text. Rounded corners at 22.5px, providing a softer, more inviting feel than ghost buttons. Padding is 11.25px vertical, 22.5px horizontal (11.25px 22.5px).

### Transparent Card
**Role:** Layered content containers over background sections.

Background of rgba(255, 255, 255, 0.1) creates a subtle frosted effect. No shadow, 15px border-radius for gentle rounding. Internal padding of 30px on all sides.

### Light Card
**Role:** Prominent content containers requiring more visual weight.

Nearly opaque background of rgba(255, 255, 255, 0.9). No shadow, 15px border-radius, matches curve of transparent cards. Internal padding of 30px.

## Do's and Don'ts

### Do
- Use Suisse Light for all primary headings (h1-h3) at 400 weight, emphasizing airy elegance.
- Apply a 15px border-radius to all cards and images for a consistent soft-edged aesthetic.
- Maintain generous section gaps of 30px to promote a spacious and uncrowded layout.
- Utilize Moss Green (#778643) sparingly for primary CTA buttons and critical interactive elements only.
- Default to transparent backgrounds and 1px borders for navigation and secondary actions, using Canvas White (#ffffff) or Charcoal Gray (#4e4e4e) for contrast.
- Ensure all body and supporting text uses Suisse Regular at 400 weight for readability and a consistent brand voice.
- Employ Space Mono for all small, utilitarian text elements, labels, and iconography to add a precise, technical detail.

### Don't
- Avoid using multiple chromatic colors; restrict accent colors strictly to Moss Green (#778643) for interactive elements.
- Do not use harsh shadows or heavy borders; the design emphasizes lightness and subtle layering.
- Refrain from tight spacing; maintain a spacious feel by adhering to the established element and section gaps (15px and 30px respectively).
- Do not use dark backgrounds for full sections; the theme is predominantly light with transparent overlays atop a gradient background.
- Avoid over-styling text with bold weights or excessive letter-spacing beyond what is defined for headings, maintaining a subtle and restrained typographic hierarchy.
- Do not introduce new border-radius values; adhere to 15px for containers and 22.5px for buttons.
- Do not use solid-fill buttons for secondary or tertiary actions; use ghost buttons with appropriate border and text colors.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas White | `#ffffff` | The primary background for the page, providing a clean base that occasionally overlaps with the background gradient. |
| 1 | Pale Mist | `#efefef` | Alternative background for sections requiring a subtle differentiation from the main canvas. |
| 2 | Smoke Glass | `#ffffff1a` | Transparent card backgrounds, creating a layered, frosted glass effect. |
| 3 | Light Card | `#ffffffe6` | More opaque card backgrounds for content that needs to stand out more prominently. |

## Imagery

The visual language relies heavily on subtle background gradients that mimic organic, mist-laden environments, providing a soft, atmospheric backdrop. Product imagery, where present, consists of clean, isolated screenshots of app interfaces, often framed within a device. Icons are minimalist, utilizing thin strokes or simple fills, primarily in achromatic tones. Imagery serves as decorative atmosphere rather than direct content, reinforcing the ethereal and calm brand identity. The density is text-dominant, with a clear focus on typography, and imagery is used sparingly to enhance mood rather than explain features.

## Layout

The page maintains a centered, max-width layout of 1425px, creating structured content areas. The hero section is full-bleed, featuring a large, centered headline over a soft gradient background. Following sections typically alternate between a background gradient and a solid Canvas White, with consistent vertical spacing between major blocks. Content arrangement often employs large, visually distinct headings with smaller descriptive text below, or two-column layouts that balance textual information with implicit visual placeholders. Navigation is a minimal top bar with ghost links, becoming sticky on scroll. The overall density is spacious, with generous padding and margins defining elements.

## Agent Prompt Guide

### Quick Color Reference
- text: #000000
- background: #ffffff
- border: #000000
- accent: #778643
- primary action: #778643 (filled action)

### 3-5 Example Component Prompts
1. Create a header: Canvas White (#ffffff) background. 'About' link (Charcoal Gray #4e4e4e, Suisse Regular 400, 15px, 1.3 line height). 'Sign up' ghost button (1px Charcoal Gray #4e4e4e border, Charcoal Gray #4e4e4e text, 0px radius, no padding specified, font is Space Mono 400 at 15px).
2. Create a transparent card with content: Smoke Glass (rgba(255, 255, 255, 0.1)) background, 15px border-radius, 30px padding. Inside, include a heading (Midnight Black #000000, Suisse Light 400, 45px, 1.1 line height) and a paragraph (Midnight Black #000000, Suisse Regular 400, 15px, 1.3 line height).
3. Create a primary action button: Moss Green (#778643) background, Canvas White (#ffffff) text (Space Mono 400, 15px), 22.5px border-radius, 11.25px vertical padding, 22.5px horizontal padding.
4. Create a footer section: Canvas White (#ffffff) background. Text links (Charcoal Gray #4e4e4e, Suisse Regular 400, 14px, 1.2 line height) and copyright text (Charcoal Gray #4e4e4e, Suisse Regular 400, 12px, 1.2 line height). Maintain 30px section gap.

## Similar Brands

- **Calm** — Employs an ethereal, nature-inspired gradient background and soft, un-intrusive typography to foster a sense of tranquility.
- **Headspace** — Uses a limited, pastel-like color palette and a clean, spacious UI to create a calm and focused user experience.
- **Woven** — Features a monochromatic UI with a single, muted accent color for interactive elements and a focus on clean, precise typography.
- **Fathom Analytics** — Utilizes a minimalist design approach with ample whitespace, light typography, and subtle brand color accents for clarity.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-midnight-black: #000000;
  --color-moss-green: #778643;
  --color-charcoal-gray: #4e4e4e;
  --color-whisper-gray: #c8c8c8;
  --color-smoke-glass: #ffffff1a;
  --color-pale-mist: #efefef;

  /* Typography — Font Families */
  --font-space-regular: 'space-regular', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-suisse-light: 'Suisse Light', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-suisse-regular: 'Suisse Regular', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-space-mono: 'Space Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-system-sans-serif: 'System Sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ui-sans-serif: 'ui-sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-lg: 15px;
  --leading-body-lg: 1.2;
  --text-heading-sm: 34px;
  --leading-heading-sm: 1;
  --text-heading: 45px;
  --leading-heading: 1.1;
  --text-heading-lg: 75px;
  --leading-heading-lg: 1.1;
  --text-display: 90px;
  --leading-display: 1.1;

  /* Typography — Weights */
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-11: 11px;
  --spacing-12: 12px;
  --spacing-15: 15px;
  --spacing-19: 19px;
  --spacing-23: 23px;
  --spacing-30: 30px;
  --spacing-38: 38px;
  --spacing-45: 45px;
  --spacing-60: 60px;
  --spacing-83: 83px;
  --spacing-120: 120px;
  --spacing-135: 135px;
  --spacing-180: 180px;
  --spacing-218: 218px;

  /* Layout */
  --page-max-width: 1425px;
  --section-gap: 30px;
  --card-padding: 30px;
  --element-gap: 15px;

  /* Border Radius */
  --radius-xl: 15px;
  --radius-2xl: 22.5px;

  /* Named Radii */
  --radius-cards: 15px;
  --radius-buttons: 22.5px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-pale-mist: #efefef;
  --surface-smoke-glass: #ffffff1a;
  --surface-light-card: #ffffffe6;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-midnight-black: #000000;
  --color-moss-green: #778643;
  --color-charcoal-gray: #4e4e4e;
  --color-whisper-gray: #c8c8c8;
  --color-smoke-glass: #ffffff1a;
  --color-pale-mist: #efefef;

  /* Typography */
  --font-space-regular: 'space-regular', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-suisse-light: 'Suisse Light', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-suisse-regular: 'Suisse Regular', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-space-mono: 'Space Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-system-sans-serif: 'System Sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ui-sans-serif: 'ui-sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-lg: 15px;
  --leading-body-lg: 1.2;
  --text-heading-sm: 34px;
  --leading-heading-sm: 1;
  --text-heading: 45px;
  --leading-heading: 1.1;
  --text-heading-lg: 75px;
  --leading-heading-lg: 1.1;
  --text-display: 90px;
  --leading-display: 1.1;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-11: 11px;
  --spacing-12: 12px;
  --spacing-15: 15px;
  --spacing-19: 19px;
  --spacing-23: 23px;
  --spacing-30: 30px;
  --spacing-38: 38px;
  --spacing-45: 45px;
  --spacing-60: 60px;
  --spacing-83: 83px;
  --spacing-120: 120px;
  --spacing-135: 135px;
  --spacing-180: 180px;
  --spacing-218: 218px;

  /* Border Radius */
  --radius-xl: 15px;
  --radius-2xl: 22.5px;
}
```

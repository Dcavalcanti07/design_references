# aave.com — Style Reference
> Deep Slate Precision

**Theme:** mixed

Aave employs a pragmatic, enterprise-grade aesthetic, balancing clear data presentation with subtle branding. The system uses a predominantly dark theme for content sections, contrasting with an initial bright hero. Typography is compact and precise, favoring confident, small text groups. Surfaces are flat or softly rounded, with elevation sparingly used to draw attention, and a singular luminous violet provides an interactive accent against the deep neutrals.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| White Canvas | `#ffffff` | `--color-white-canvas` | Page backgrounds in light sections, active navigation indicators, key component backgrounds. Provides crisp contrast |
| Ink Black | `#221d1d` | `--color-ink-black` | Primary text, critical headings, dark section backgrounds, subtle dark borders. Near-black for sharp readability |
| Pewter | `#636161` | `--color-pewter` | Secondary text, muted links, subtle icon fills. Used for supporting information that recedes slightly |
| Misty Gray | `#8f8e8e` | `--color-misty-gray` | Helper text, tertiary information, soft borders. Further recedes compared to Pewter |
| Obsidian | `#0f0f10` | `--color-obsidian` | Dark theme button backgrounds, primary navigation text on dark backgrounds. A slightly softer alternative to Ink Black |
| Light Alabaster | `#f6f7f4` | `--color-light-alabaster` | Card backgrounds in lighter sections, subtle background distinctions |
| Slate Dust | `#858387` | `--color-slate-dust` | Dominant background for dark themed sections and main content areas, creating a subtle contrast against white |
| Cosmic Violet | `#998eff` | `--color-cosmic-violet` | Primary action buttons, interactive highlights, navigational focus states, decorative accents. The sole vibrant color for signaling interaction and brand identity |

## Tokens — Typography

### Aave Repro — Primary brand typeface for all headings, body text, and UI elements. The condensed 'ss07' variant provides a tight, technical feel, especially with the precise negative letter-spacing for larger sizes. · `--font-aave-repro`
- **Weights:** 400, 450, 500
- **Sizes:** 13px, 14px, 15px, 16px, 17px, 18px, 20px, 24px, 32px, 40px, 72px
- **Line height:** 1.00
- **Letter spacing:** -0.0500em at 72px, -0.0250em at 40px, -0.0100em at 18-24px, 0.0100em at 13px
- **OpenType features:** `"ss07"`
- **Role:** Primary brand typeface for all headings, body text, and UI elements. The condensed 'ss07' variant provides a tight, technical feel, especially with the precise negative letter-spacing for larger sizes.

### Inter — Secondary sans-serif font for small annotations, navigation items, and data labels where Aave Repro might be too condensed or its custom glyphs less suitable. Used sparingly to complement, not dominate. · `--font-inter`
- **Weights:** 400, 700
- **Sizes:** 10px, 14px
- **Line height:** 1.50
- **Letter spacing:** -0.0060em
- **OpenType features:** `"ss07"`
- **Role:** Secondary sans-serif font for small annotations, navigation items, and data labels where Aave Repro might be too condensed or its custom glyphs less suitable. Used sparingly to complement, not dominate.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.5 | -0.06px | `--text-caption` |
| subheading | 18px | 1.4 | -0.18px | `--text-subheading` |
| heading-sm | 24px | 1.36 | -0.24px | `--text-heading-sm` |
| heading | 40px | 1.1 | -1px | `--text-heading` |
| display | 72px | 0.9 | -3.6px | `--text-display` |

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
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 72 | 72px | `--spacing-72` |
| 80 | 80px | `--spacing-80` |
| 120 | 120px | `--spacing-120` |
| 176 | 176px | `--spacing-176` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 24px |
| input | 20px |
| pills | 1584px |
| buttons | 20px |
| navItems | 50px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| lg | `rgba(0, 0, 0, 0.05) 0px 6px 20px 0px, rgba(0, 0, 0, 0.06)...` | `--shadow-lg` |

### Layout

- **Section gap:** 48px
- **Card padding:** 24px
- **Element gap:** 8px

## Components

### Primary Call to Action Button
**Role:** Filled button indicating primary interaction.

Background: Cosmic Violet (#998eff). Text: White Canvas (#ffffff). Padding: 14px vertical, 24px horizontal. Radius: 1584px (large, pill-shaped) for a bold, approachable CTA. Font: Aave Repro, 16px, weight 450.

### Ghost Button (Dark)
**Role:** Lightweight, secondary action on dark backgrounds.

Background: transparent. Text: Obsidian (#0f0f10). Border: 1px solid Obsidian (#0f0f10). Padding: 9px vertical, 16px horizontal. Radius: 50px (rounded pill). Font: Aave Repro, 16px, weight 450.

### Ghost Button (Light)
**Role:** Lightweight, secondary action on light backgrounds.

Background: transparent. Text: Pewter (#636161). Border: 1px solid Pewter (#636161). Padding: 9px vertical, 16px horizontal. Radius: 50px (rounded pill). Font: Aave Repro, 16px, weight 450.

### Navigation Link Button
**Role:** Header navigation items that act as buttons.

Background: transparent. Text: Ink Black (#221d1d). No border. Padding: 20px top, 12px bottom (larger vertical for visual emphasis). Radius: 0px. Font: Aave Repro, 16px, weight 400.

### Card (White Canvas Background)
**Role:** Content container for features or data on white backgrounds.

Background: White Canvas (#ffffff) with 3% alpha for subtle visual depth. Padding: 32px vertical, 24px horizontal. Radius: 20px. No border or shadow.

### Card (Light Alabaster Background)
**Role:** Content container for features or data on light alabaster backgrounds.

Background: Light Alabaster (#f6f7f4). Padding: 32px vertical, 24px horizontal. Radius: 24px. No border or shadow.

### Card (Slate Dust Background)
**Role:** Content container for features or data on dark section backgrounds.

Background: Slate Dust (#858387). Padding: 32px vertical, 24px horizontal. Radius: 24px. No outer border or shadow.

### Input Field
**Role:** User input text field.

Background: White Canvas (#ffffff). Text color: Ink Black (#221d1d). Border: 1px solid Ink Black (#221d1d). Padding: 10px vertical, 16px horizontal. Radius: 20px 6px 6px 20px (asymmetric for distinct visual). Font: Aave Repro.

## Do's and Don'ts

### Do
- Use Aave Repro with negative letter spacing for larger headings (e.g., -0.0500em at 72px) to maintain a condensed, authoritative presence.
- Apply Cosmic Violet (#998eff) exclusively for primary calls to action, active states, and brand-critical highlights; avoid using it decoratively.
- Maintain a clear visual hierarchy by limiting card shadows to navigation elements only, favoring flat or subtle background color shifts for content grouping.
- Implement the 1584px 'pill' radius for primary buttons to create a softer, more inviting interactive target.
- Use Light Alabaster (#f6f7f4) or Slate Dust (#858387) for card backgrounds to generate depth without relying on shadows.
- Ensure all interactive elements have a focus state derived from Cosmic Violet or a subtle glow from the token --focus.
- Utilize the asymmetric 20px 6px 6px 20px border-radius for input fields to create a distinct, modern form element.

### Don't
- Do not introduce additional saturated colors; Cosmic Violet (#998eff) is the sole accent color for branding.
- Avoid using drop shadows on cards or regular content blocks; rely on background color changes for surface differentiation.
- Do not deviate from the specified negative letter-spacing values for display and heading typography; it's critical to the brand's compact style.
- Do not use generic border radii; adhere to the specific values like 20px for buttons and 24px for cards.
- Do not use default browser link styles; all links should adopt the body text color with subtle hover states, or be explicitly styled as buttons.
- Do not introduce heavy iconography or overly decorative illustrations; align with the UI-focused, almost monochrome visual language.
- Avoid large hero imagery; product screens and minimal visuals paired with bold typography define the hero aesthetic.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Slate Dust | `#858387` | Base background for most content sections, providing a dark canvas. |
| 1 | Light Alabaster | `#f6f7f4` | Secondary background for cards and distinct content blocks, especially in lighter sections. |
| 2 | White Canvas | `#ffffff` | Primary background for hero sections and elevated elements, creating contrast and visual emphasis. |

## Elevation

- **Header Navigation:** `rgba(0, 0, 0, 0.05) 0px 6px 20px 0px, rgba(0, 0, 0, 0.06) 0px 0px 0px 1px`

## Imagery

This system primarily uses product-focused imagery, showcasing mobile app screens and sophisticated UI elements. Photography is absent, replaced by stylized product mockups (e.g., iPhones displaying the Aave app) that serve as content showcases. Icons are minimal, outlined, and monochromatic, used functionally rather than decoratively, maintaining a high density of information over large visual elements. Graphics are abstract and geometric, often subtle background elements, like the gradient in the hero section, to provide atmosphere. The overall density is high, with imagery embedded within textual descriptions to explain product features.

## Layout

The page alternates between full-bleed and max-width contained sections. The initial hero pattern features a light background with a centered headline and buttons, overlaid on top of a product mockup cascade (mobile phones). Subsequent sections shift to a dark background, using a max-width centered container. Content arrangement often utilizes a centered stack for titles and calls to action, followed by multi-column grids (e.g., 3-column cards for features) within the contained sections. Vertical rhythm is consistent with large section gaps of approximately 48px, creating clear divisions. The navigation is a sticky top bar with global links and a prominent 'Use Aave' button.

## Agent Prompt Guide

Quick Color Reference:
text: #221d1d
background: #ffffff (light theme), #858387 (dark theme)
border: #221d1d (dark), #636161 (medium), #8f8e8e (lightest)
accent: #998eff
primary action: #998eff (filled action)

Example Component Prompts:
Create a Primary Action Button: #998eff background, #000000 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.

Create a feature card: Light Alabaster (#f6f7f4) background. Radius 24px. Padding 32px vertical, 24px horizontal. Headline 'General purpose' in Ink Black (#221d1d), Aave Repro, 24px, weight 500, letter-spacing -0.0100em. Body text in Pewter (#636161), Aave Repro, 16px, weight 400.

Create a secondary ghost button: 'Learn More' with transparent background, Obsidian (#0f0f10) text and 1px border. Padding 9px vertical, 16px horizontal. Radius 50px, Aave Repro, 16px, weight 450.

Create a dark-themed section: Slate Dust (#858387) background. Centered heading 'The Full Power of DeFi' in White Canvas (#ffffff), Aave Repro, 40px, weight 500, letter-spacing -0.0250em.

Create an input field: White Canvas (#ffffff) background, Ink Black (#221d1d) text, 1px solid Ink Black (#221d1d) border. Padding 10px vertical, 16px horizontal. Radius 20px 6px 6px 20px.

## Similar Brands

- **Linear** — Shared aesthetic of dark-mode UI with minimalist typography and a single vibrant accent color for interaction.
- **Stripe** — Similar emphasis on clear, functional layouts, concise typography, and a preference for flat surfaces over heavy shadows.
- **Coinbase** — Comparable use of product screenshots and clean, data-focused UI presentation for a finance/crypto platform.
- **Figma** — The use of soft, pill-shaped buttons and a generally clean, accessible interface with well-defined interactive elements.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-white-canvas: #ffffff;
  --color-ink-black: #221d1d;
  --color-pewter: #636161;
  --color-misty-gray: #8f8e8e;
  --color-obsidian: #0f0f10;
  --color-light-alabaster: #f6f7f4;
  --color-slate-dust: #858387;
  --color-cosmic-violet: #998eff;

  /* Typography — Font Families */
  --font-aave-repro: 'Aave Repro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --tracking-caption: -0.06px;
  --text-subheading: 18px;
  --leading-subheading: 1.4;
  --tracking-subheading: -0.18px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.36;
  --tracking-heading-sm: -0.24px;
  --text-heading: 40px;
  --leading-heading: 1.1;
  --tracking-heading: -1px;
  --text-display: 72px;
  --leading-display: 0.9;
  --tracking-display: -3.6px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-w450: 450;
  --font-weight-medium: 500;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-120: 120px;
  --spacing-176: 176px;

  /* Layout */
  --section-gap: 48px;
  --card-padding: 24px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-full: 50px;
  --radius-full-2: 1584px;

  /* Named Radii */
  --radius-cards: 24px;
  --radius-input: 20px;
  --radius-pills: 1584px;
  --radius-buttons: 20px;
  --radius-navitems: 50px;

  /* Shadows */
  --shadow-lg: rgba(0, 0, 0, 0.05) 0px 6px 20px 0px, rgba(0, 0, 0, 0.06) 0px 0px 0px 1px;

  /* Surfaces */
  --surface-slate-dust: #858387;
  --surface-light-alabaster: #f6f7f4;
  --surface-white-canvas: #ffffff;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-white-canvas: #ffffff;
  --color-ink-black: #221d1d;
  --color-pewter: #636161;
  --color-misty-gray: #8f8e8e;
  --color-obsidian: #0f0f10;
  --color-light-alabaster: #f6f7f4;
  --color-slate-dust: #858387;
  --color-cosmic-violet: #998eff;

  /* Typography */
  --font-aave-repro: 'Aave Repro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --tracking-caption: -0.06px;
  --text-subheading: 18px;
  --leading-subheading: 1.4;
  --tracking-subheading: -0.18px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.36;
  --tracking-heading-sm: -0.24px;
  --text-heading: 40px;
  --leading-heading: 1.1;
  --tracking-heading: -1px;
  --text-display: 72px;
  --leading-display: 0.9;
  --tracking-display: -3.6px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-120: 120px;
  --spacing-176: 176px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-full: 50px;
  --radius-full-2: 1584px;

  /* Shadows */
  --shadow-lg: rgba(0, 0, 0, 0.05) 0px 6px 20px 0px, rgba(0, 0, 0, 0.06) 0px 0px 0px 1px;
}
```

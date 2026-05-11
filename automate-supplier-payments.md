# Automate Supplier Payments — Style Reference
> sunlit productivity canvas

**Theme:** light

Apron employs a cheerful, business-friendly aesthetic, combining a light yellow base with predominantly dark text for accessibility. The primary accent is a sunny yellow which signals interaction and warmth. Typography mixes a robust, bespoke display font with a more conventional sans-serif for readability. Components favor rounded edges and minimal elevation, maintaining a light, approachable feel suitable for financial SaaS.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Amber Pop | `#ffd801` | `--color-amber-pop` | Primary action buttons, active states, and accents—this vivid yellow imbues UI elements with a sense of energy and warmth |
| Canvas Gold | `#fbefaf` | `--color-canvas-gold` | Main page background, providing a subtle, warm off-white foundation |
| Paper Buff | `#fff6d2` | `--color-paper-buff` | Card backgrounds, providing a slightly richer surface level against the Canvas Gold |
| Midnight Ink | `#000000` | `--color-midnight-ink` | Primary text, headings, icons, and borders, ensuring high contrast against light backgrounds |
| Fog | `#cccbc7` | `--color-fog` | Subtle borders for ghost buttons and dividers, providing soft visual separation |
| Frost | `#ffffff` | `--color-frost` | Text on dark backgrounds, hero section text overlays, and occasional inverted elements |
| Charcoal Haze | `#666664` | `--color-charcoal-haze` | Hero section background overlay, providing depth for light text contrast |

## Tokens — Typography

### sans-serif — sans-serif — detected in extracted data but not described by AI · `--font-sans-serif`
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.15
- **Role:** sans-serif — detected in extracted data but not described by AI

### Champ — Display and large headings. Its bespoke nature gives a strong brand voice, delivering impact through a slightly condensed yet bold presence. · `--font-champ`
- **Substitute:** Montserrat
- **Weights:** 500, 800
- **Sizes:** 26px, 38px, 54px, 72px
- **Line height:** 1.01, 1.16, 1.20, 1.40
- **Letter spacing:** 0.01em
- **Role:** Display and large headings. Its bespoke nature gives a strong brand voice, delivering impact through a slightly condensed yet bold presence.

### DM Sans — Body copy, navigation links, and smaller headings. Provides a clear, modern, and highly legible text block that complements the display font without competing. · `--font-dm-sans`
- **Substitute:** Open Sans
- **Weights:** 400, 500, 700
- **Sizes:** 10px, 16px, 20px
- **Line height:** 1.00, 1.40, 1.50, 2.33
- **Letter spacing:** -0.02em at 20px, 0.01em at 16px, 0.016em at 10px
- **Role:** Body copy, navigation links, and smaller headings. Provides a clear, modern, and highly legible text block that complements the display font without competing.

### DM Mono — Used for specific callouts or technical details, offering a distinct voice through its monospaced clarity. · `--font-dm-mono`
- **Substitute:** Roboto Mono
- **Weights:** 400
- **Sizes:** 18px
- **Line height:** 1.20
- **Letter spacing:** 0.01em
- **Role:** Used for specific callouts or technical details, offering a distinct voice through its monospaced clarity.

### Arial — Arial — detected in extracted data but not described by AI · `--font-arial`
- **Weights:** 400
- **Sizes:** 13px
- **Line height:** 1.2
- **Role:** Arial — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.4 | 0.16px | `--text-caption` |
| body | 16px | 1.5 | 0.16px | `--text-body` |
| subheading | 20px | 1.4 | -0.4px | `--text-subheading` |
| heading | 26px | 1.2 | 0.26px | `--text-heading` |
| heading-lg | 38px | 1.16 | 0.38px | `--text-heading-lg` |
| display | 72px | 1.01 | 0.72px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** spacious

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 8 | 8px | `--spacing-8` |
| 12 | 12px | `--spacing-12` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 28 | 28px | `--spacing-28` |
| 32 | 32px | `--spacing-32` |
| 36 | 36px | `--spacing-36` |
| 48 | 48px | `--spacing-48` |
| 60 | 60px | `--spacing-60` |
| 72 | 72px | `--spacing-72` |
| 80 | 80px | `--spacing-80` |
| 120 | 120px | `--spacing-120` |
| 132 | 132px | `--spacing-132` |
| 236 | 236px | `--spacing-236` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 20px |
| buttons | 9999px |
| general | 16px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| md | `rgba(70, 58, 0, 0.1) 0px 4px 12px 0px` | `--shadow-md` |

### Layout

- **Section gap:** 80px
- **Card padding:** 32px
- **Element gap:** 24px

## Components

### Primary Action Button
**Role:** Main call-to-action button for initiating key actions

Filled with Amber Pop (#ffd801), text is Midnight Ink (#000000). Has a 9999px radius (pill shape) and 12px vertical, 32px horizontal padding. Font is DM Sans 400.

### Ghost Button
**Role:** Secondary action button, typically for navigation or less emphasized actions

Transparent background with Midnight Ink (#000000) text. Has a 9999px radius (pill shape) and 12px vertical, 32px horizontal padding. A subtle 1px border of Fog (#cccbc7) adds light presence.

### Text Link Button
**Role:** Hyperlink-style button for quick navigation or inline actions

Transparent background, Midnight Ink (#000000) text, no border. Used for nav items or 'Learn more' links. Font is DM Sans 400.

### Information Card
**Role:** Container for grouped content or features in a section

Background is Paper Buff (#fff6d2), with a 20px border radius. No explicit padding detected, implying content dictates internal spacing.

### Elevated Box
**Role:** Decorative or content-containing box that stands out slightly

Uses a subtle shadow: rgba(70, 58, 0, 0.1) 0px 4px 12px 0px. Specific background and border radius are contextual but often pairs with Canvas Gold or Paper Buff and a 16px radius.

## Do's and Don'ts

### Do
- Always use Amber Pop (#ffd801) for primary interactive elements, ensuring a consistent highlight across the interface.
- Apply a 9999px border-radius to all buttons and interactive tags to maintain the system's friendly, approachable pill shape.
- Prioritize Midnight Ink (#000000) for all main body text and headings on light backgrounds to ensure AAA contrast.
- Utilize Champ for all prominent headings to leverage its distinct brand voice and visual strength.
- Maintain a clear hierarchy using the established type scale, from 72px display in Champ to 10px captions in DM Sans.
- Employ Paper Buff (#fff6d2) as the background for cards to create a visual lift from the Canvas Gold (#fbefaf) page background.
- Use a generous 24px minimum `elementGap` between UI elements and 80px `sectionGap` between major content blocks for an airy layout.

### Don't
- Never introduce new saturated colors for interactive elements; only Amber Pop (#ffd801) is reserved for this purpose.
- Avoid sharp corners; all significant UI elements like cards and buttons must adhere to the defined border radii.
- Do not use system fonts for headings; Champ is mandatory for its unique brand contribution.
- Refrain from using strong, dark background shadows; any elevation should be subtle and light, consistent with rgba(70, 58, 0, 0.1) 0px 4px 12px 0px.
- Do not vary letter-spacing for DM Sans unless explicitly defined in the type scale data; maintain consistency in tracking.
- Avoid arbitrary uses of white (#ffffff) for text on light backgrounds; it is primarily for contrast on Charcoal Haze backgrounds or for inverted elements.
- Do not compress spacing between sections; the spacious density is a key visual characteristic.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas Gold | `#fbefaf` | Base page background |
| 1 | Paper Buff | `#fff6d2` | Card and content block backgrounds |
| 2 | Frost | `#ffffff` | Occasional elevated sections or modal backgrounds used against a dark overlay |

## Elevation

- **Elevated Box:** `rgba(70, 58, 0, 0.1) 0px 4px 12px 0px`

## Imagery

This site predominantly uses photography as its visual language. Images, like the hero, are typically full-bleed, often with a subtle dark overlay (Charcoal Haze) to provide contrast for white text. Photography appears lifestyle-oriented, showcasing people in relatable business contexts, often with a warm, natural lighting. There is an absence of product screenshots, abstract graphics, or highly stylized illustrations. Icons, when present, are simple, monochromatic, and align with the neutral color palette.

## Layout

The page maintains a contained layout for main content sections, typically centered with implicit maximum width, while the hero section expands full-bleed. The hero features a large, centered headline and subtext overlaying a lifestyle photograph with a darkening filter. Section rhythm appears consistent with generous vertical `sectionGap`. Content arrangements lean towards centered stacks for headlines and subtext, with implied alternating text and visual compositions in subsequent sections, though specific grid details are not provided beyond button and link layouts. Navigation is a simple top bar, with prominent 'Sign in' and 'Get started' buttons.

## Agent Prompt Guide

Quick Color Reference: 
text: #000000
background: #fbefaf
border: #cccbc7
accent: #ffd801
primary action: #ffd801 (filled action)

Example Component Prompts:
Create a Primary Action Button: #ffd801 background, #000000 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
Create a card: Paper Buff (#fff6d2) background, 20px radius. Inside, use DM Sans 16px 400, #000000 for body text and Champ 26px 500, #000000 for a heading. Element gaps are 24px.

## Similar Brands

- **Ramp** — Both brands combine a vibrant accent color with a largely neutral palette, focusing on clarity and approachability in financial tech.
- **Brex** — Similar use of clean, sans-serif typography and minimal UI with an emphasis on soft elements and a bright brand color for CTAs.
- **Mercury** — Shares a light, airy design aesthetic with subtle elevation and a clear, functional layout, prioritizing user trust and ease of use in banking.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-amber-pop: #ffd801;
  --color-canvas-gold: #fbefaf;
  --color-paper-buff: #fff6d2;
  --color-midnight-ink: #000000;
  --color-fog: #cccbc7;
  --color-frost: #ffffff;
  --color-charcoal-haze: #666664;

  /* Typography — Font Families */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-champ: 'Champ', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-dm-sans: 'DM Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-dm-mono: 'DM Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.4;
  --tracking-caption: 0.16px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: 0.16px;
  --text-subheading: 20px;
  --leading-subheading: 1.4;
  --tracking-subheading: -0.4px;
  --text-heading: 26px;
  --leading-heading: 1.2;
  --tracking-heading: 0.26px;
  --text-heading-lg: 38px;
  --leading-heading-lg: 1.16;
  --tracking-heading-lg: 0.38px;
  --text-display: 72px;
  --leading-display: 1.01;
  --tracking-display: 0.72px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-bold: 700;
  --font-weight-extrabold: 800;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-48: 48px;
  --spacing-60: 60px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-120: 120px;
  --spacing-132: 132px;
  --spacing-236: 236px;

  /* Layout */
  --section-gap: 80px;
  --card-padding: 32px;
  --element-gap: 24px;

  /* Border Radius */
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-cards: 20px;
  --radius-buttons: 9999px;
  --radius-general: 16px;

  /* Shadows */
  --shadow-md: rgba(70, 58, 0, 0.1) 0px 4px 12px 0px;

  /* Surfaces */
  --surface-canvas-gold: #fbefaf;
  --surface-paper-buff: #fff6d2;
  --surface-frost: #ffffff;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-amber-pop: #ffd801;
  --color-canvas-gold: #fbefaf;
  --color-paper-buff: #fff6d2;
  --color-midnight-ink: #000000;
  --color-fog: #cccbc7;
  --color-frost: #ffffff;
  --color-charcoal-haze: #666664;

  /* Typography */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-champ: 'Champ', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-dm-sans: 'DM Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-dm-mono: 'DM Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.4;
  --tracking-caption: 0.16px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: 0.16px;
  --text-subheading: 20px;
  --leading-subheading: 1.4;
  --tracking-subheading: -0.4px;
  --text-heading: 26px;
  --leading-heading: 1.2;
  --tracking-heading: 0.26px;
  --text-heading-lg: 38px;
  --leading-heading-lg: 1.16;
  --tracking-heading-lg: 0.38px;
  --text-display: 72px;
  --leading-display: 1.01;
  --tracking-display: 0.72px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-48: 48px;
  --spacing-60: 60px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-120: 120px;
  --spacing-132: 132px;
  --spacing-236: 236px;

  /* Border Radius */
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-full: 9999px;

  /* Shadows */
  --shadow-md: rgba(70, 58, 0, 0.1) 0px 4px 12px 0px;
}
```

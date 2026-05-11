# Patreon — Style Reference
> Authentic creator stories on a clean stage.

**Theme:** light

Patreon leverages a canvas of real-world photography and a muted palette to ground its brand in authentic creator stories, overlaid with a clean, functional UI. Strong, confident typography paired with rounded components creates a friendly yet authoritative tone. The design prioritizes clear content presentation, with color used sparingly to highlight interactive elements and brand identity, rather than for decorative excess. It balances a feeling of welcoming accessibility with structural clarity.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Ink | `#000000` | `--color-ink` | Primary text, critical buttons, primary navigation elements, footer background — creates strong contrast and a confident presence |
| Canvas | `#ffffff` | `--color-canvas` | Page backgrounds, card surfaces, ghost button text and borders — provides a clean, bright foundation |
| Iron | `#1a1a1a` | `--color-iron` | Neutral form states, badge text, and quiet UI feedback where color should stay understated. Do not promote it to the primary CTA color |
| Silver Thread | `#959595` | `--color-silver-thread` | Muted helper text, disabled states, subtle indications — a soft gray that recedes visually |
| Sky Blue | `#5fc1f1` | `--color-sky-blue` | Decorative highlights, accent icons, informational states – a light, active blue |
| Vivid Pink | `#f15ff1` | `--color-vivid-pink` | Secondary brand accent, decorative elements — a bright, playful pink |

## Tokens — Typography

### Oracle — Primary typeface for all headings, body text, and UI elements. Its custom nature and extensive weights create a distinct brand voice. · `--font-oracle`
- **Substitute:** Inter
- **Weights:** 250, 300, 350, 400, 500
- **Sizes:** 8px, 14px, 15px, 22px, 26px, 27px, 39px, 54px, 128px, 188px
- **Line height:** 0.87, 0.98, 1.00, 1.10, 1.20, 1.50
- **Letter spacing:** -0.0600em, -0.0550em, -0.0400em, -0.0230em, -0.0200em, -0.0180em, 0.0200em
- **Role:** Primary typeface for all headings, body text, and UI elements. Its custom nature and extensive weights create a distinct brand voice.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body-sm | 14px | 1.5 | -0.28px | `--text-body-sm` |
| subheading | 22px | 1.2 | -0.48px | `--text-subheading` |
| heading-sm | 26px | 1.2 | -0.52px | `--text-heading-sm` |
| heading | 39px | 1.1 | -0.78px | `--text-heading` |
| heading-lg | 54px | 1.1 | -0.97px | `--text-heading-lg` |
| display | 128px | 0.98 | -2.3px | `--text-display` |
| display-lg | 188px | 0.87 | -3.38px | `--text-display-lg` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 8 | 8px | `--spacing-8` |
| 20 | 20px | `--spacing-20` |
| 60 | 60px | `--spacing-60` |
| 120 | 120px | `--spacing-120` |
| 128 | 128px | `--spacing-128` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 37.5px |
| cards | 30px |
| inputs | 45px |
| buttons | 30px |

### Layout

- **Section gap:** 38px
- **Card padding:** 14px
- **Element gap:** 7px

## Components

### Primary Filled Button
**Role:** Main call-to-action button, conveying confidence and directness.

Background: Ink (#000000), text: Canvas (#ffffff); 30px border-radius; padding: 15px vertical, 21px horizontal.

### Ghost Button
**Role:** Secondary action or navigational link within a content block, visually recessive.

Background: transparent (rgba(0,0,0,0)), text: Canvas (#ffffff), border: 1px solid Iron (#1a1a1a); 30px border-radius; padding: 11.25px vertical, 18px horizontal.

### Mini Circular Button
**Role:** Icon-only or small, self-contained actions, often navigational or functional.

Background: Ink (#000000), text: Canvas (#ffffff); 50% border-radius (perfect circle); padding: 14.25px all around.

### Tag Button
**Role:** Categorization, filtering, or minor interactive elements.

Background: rgba(255, 255, 255, 0.16) (translucent white), text: Canvas (#ffffff); 37.5px border-radius; padding: 10.5px vertical, 21px horizontal.

### Feature Card
**Role:** Content container for features or testimonials, elevated on the Canvas background.

Background: Canvas (#ffffff), no shadow; 30px border-radius; padding: 52.5px top, 75px bottom, 30px horizontal.

### Search Input
**Role:** Allows users to query content without distracting visual weight.

Background: transparent (rgba(0, 0, 0, 0)), text color: Canvas (#ffffff), border: 1px solid Iron (#1a1a1a); 45px border-radius; no internal padding.

## Do's and Don'ts

### Do
- Use Oracle font family for all text elements, leveraging its custom weights for visual hierarchy.
- Apply Ink (#000000) for primary text and critical interactive button backgrounds.
- Ensure all buttons and cards have a minimum border-radius of 30px to maintain a soft, friendly aesthetic.
- Utilize Canvas (#ffffff) for page backgrounds and primary content surfaces to provide a crisp, clean base.
- Maintain comfortable spacing with a base unit of 4px; use 7px for element-level gaps and 14px for internal card padding.
- Emphasize the Sky Blue (#5fc1f1) accent color for functional indicators and non-critical highlights only.
- Integrate high-quality, authentic photography of creators as key visual elements where appropriate.

### Don't
- Avoid using multiple colors for text; primary text should be Ink (#000000) and secondary text Iron (#1a1a1a) or Silver Thread (#959595).
- Do not introduce square or sharp-cornered elements; all interactive and content containers should adhere to the established radii.
- Refrain from using strong shadows or gradients on primary UI elements, favoring flat and clean surfaces.
- Do not use accent colors as background for large sections or text blocks unless explicitly defined as a semantic state.
- Do not clutter layouts with too many disparate elements; prioritize clear hierarchy and ample whitespace.
- Avoid generic stock photography; all imagery should feel genuine and creator-focused.
- Do not use font weights below 300 for body text to maintain readability.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas | `#ffffff` | Base page background |
| 1 | Card Surface | `#ffffff` | Container cards and modular content blocks |

## Imagery

The visual language is dominated by authentic photography of diverse creators, not stock imagery. Photos are typically high-quality and often feature subjects engaged in their craft, establishing a connection with the audience. Images are generally featured full-bleed or contained in soft-edged frames. Iconography is minimalist, often monochrome (Ink or Canvas), using thin strokes. There's a high density of imagery, with photos often acting as primary visual anchors rather than mere decoration or product showcases.

## Layout

The page model is a full-bleed layout, particularly for hero sections, which often feature large, compelling creator photography that extends to the viewport edges. Content is generally organized into digestible blocks with consistent vertical spacing, often alternating between visual styles. Hero sections utilize centered headlines over background imagery or video. Subsequent sections typically employ a responsive grid, with alternating text-left/image-right compositions often observed. Navigation is a flexible top bar that can adapt to light or dark contexts, featuring ghost buttons and a prominent filled action button.

## Agent Prompt Guide

primary action: #000000 (filled action)
Create a Primary Action Button: #000000 background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.

Example Component Prompts:
1. Create a Hero Section: full-bleed background image with a centered headline 'Creativity Powered by Fandom' using Oracle font, size 128px, weight 250, letter-spacing -2.3px, color Canvas (#ffffff). Below it, a ghost button 'Get Started' with text Canvas (#ffffff), transparent background, 1px solid Iron (#1a1a1a) border, 30px radius, 11.25px vertical padding, 18px horizontal padding.
3. Create a Sub-Navigation Bar: Ghost Button elements; text Canvas (#ffffff), transparent background, 1px solid Iron (#1a1a1a) border, 30px radius, 11.25px vertical padding, 18px horizontal padding. Include an active 'Updates' button with a Tag Button style: rgba(255, 255, 255, 0.16) background, Canvas (#ffffff) text, 37.5px radius, 10.5px vertical padding, 21px horizontal padding.

## Similar Brands

- **Substack** — Emphasizes creator independence, uses clean typography and photography with a focus on written content, and a clear call-to-action.
- **Gumroad** — Platform for creators, features product photography alongside UI, with a similar approach to clean layouts and prominent call-to-action buttons.
- **Linktree** — Focuses on personal branding and creator tools, using rounded UI elements and a focus on direct, functional design.
- **Medium** — Content-focused platform with strong typography, clean design, and a focus on author photography/avatars to build connection.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-ink: #000000;
  --color-canvas: #ffffff;
  --color-iron: #1a1a1a;
  --color-silver-thread: #959595;
  --color-sky-blue: #5fc1f1;
  --color-vivid-pink: #f15ff1;

  /* Typography — Font Families */
  --font-oracle: 'Oracle', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --tracking-body-sm: -0.28px;
  --text-subheading: 22px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.48px;
  --text-heading-sm: 26px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: -0.52px;
  --text-heading: 39px;
  --leading-heading: 1.1;
  --tracking-heading: -0.78px;
  --text-heading-lg: 54px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.97px;
  --text-display: 128px;
  --leading-display: 0.98;
  --tracking-display: -2.3px;
  --text-display-lg: 188px;
  --leading-display-lg: 0.87;
  --tracking-display-lg: -3.38px;

  /* Typography — Weights */
  --font-weight-w250: 250;
  --font-weight-light: 300;
  --font-weight-w350: 350;
  --font-weight-regular: 400;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-20: 20px;
  --spacing-60: 60px;
  --spacing-120: 120px;
  --spacing-128: 128px;

  /* Layout */
  --section-gap: 38px;
  --card-padding: 14px;
  --element-gap: 7px;

  /* Border Radius */
  --radius-3xl: 30px;
  --radius-3xl-2: 37.5px;
  --radius-3xl-3: 45px;

  /* Named Radii */
  --radius-tags: 37.5px;
  --radius-cards: 30px;
  --radius-inputs: 45px;
  --radius-buttons: 30px;

  /* Surfaces */
  --surface-canvas: #ffffff;
  --surface-card-surface: #ffffff;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-ink: #000000;
  --color-canvas: #ffffff;
  --color-iron: #1a1a1a;
  --color-silver-thread: #959595;
  --color-sky-blue: #5fc1f1;
  --color-vivid-pink: #f15ff1;

  /* Typography */
  --font-oracle: 'Oracle', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --tracking-body-sm: -0.28px;
  --text-subheading: 22px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.48px;
  --text-heading-sm: 26px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: -0.52px;
  --text-heading: 39px;
  --leading-heading: 1.1;
  --tracking-heading: -0.78px;
  --text-heading-lg: 54px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.97px;
  --text-display: 128px;
  --leading-display: 0.98;
  --tracking-display: -2.3px;
  --text-display-lg: 188px;
  --leading-display-lg: 0.87;
  --tracking-display-lg: -3.38px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-20: 20px;
  --spacing-60: 60px;
  --spacing-120: 120px;
  --spacing-128: 128px;

  /* Border Radius */
  --radius-3xl: 30px;
  --radius-3xl-2: 37.5px;
  --radius-3xl-3: 45px;
}
```

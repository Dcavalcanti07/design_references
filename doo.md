# Doo — Style Reference
> White Canvas Productivity

**Theme:** light

Doo presents a clean, productivity-focused interface with an emphasis on spacious layouts and subtle interactivity. Its visual identity is built on high-contrast typography against a primarily white canvas, accented by soft, rounded cards and a single, deep violet for primary actions. The design minimizes visual clutter, using thin borders and ghost-like elements to define structure, allowing content to take center stage.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | *Page backgrounds, primary card surfaces, pristine backdrop for content.* |
| Subtle Gray | `#f7f7f7` | `--color-subtle-gray` | *Secondary card surfaces, slightly differentiated visual areas within cards.* |
| Border Fog | `#edeef3` | `--color-border-fog` | *Hairline borders, subtle dividers, ghost button borders.* |
| Text Primary | `#383938` | `--color-text-primary` | *Primary headings and body text — a very dark gray for high readability.* |
| Text Secondary | `#6e6d7a` | `--color-text-secondary` | *Secondary text, navigation items, descriptive labels, and helper text.* |
| Shadow Ink | `#111111` | `--color-shadow-ink` | *Deepest text areas, darkest shadow effects when present.* |
| Action Violet | `#5e45a2` | `--color-action-violet` | Supporting palette color for small decorative accents when the core palette needs contrast. Do not promote it to the primary CTA color |

## Tokens — Typography

### Avenir Next — *Headline and body typography, offering a clean, approachable, and highly readable foundation for all text across the interface. The contrast between medium and bold is managed to maintain visual lightness.* · `--font-avenir-next`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400, 600
- **Sizes:** 13px, 16px, 17px, 20px, 29px, 39px, 65px
- **Line height:** 1.00, 1.20, 1.80
- **Letter spacing:** -0.8, -0.4, 0, 0, 0.17, 0.16, 0.13
- **Role:** *Headline and body typography, offering a clean, approachable, and highly readable foundation for all text across the interface. The contrast between medium and bold is managed to maintain visual lightness.*

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 13px | 1.2 | 0.13px | `--text-caption` |
| body-sm | 16px | 1.2 | 0.16px | `--text-body-sm` |
| subheading | 20px | 1.2 | — | `--text-subheading` |
| heading-sm | 29px | 1.2 | — | `--text-heading-sm` |
| heading | 39px | 1 | -0.4px | `--text-heading` |
| display | 65px | 1 | -0.8px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** spacious

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 5 | 5px | `--spacing-5` |
| 10 | 10px | `--spacing-10` |
| 13 | 13px | `--spacing-13` |
| 19 | 19px | `--spacing-19` |
| 20 | 20px | `--spacing-20` |
| 21 | 21px | `--spacing-21` |
| 26 | 26px | `--spacing-26` |
| 33 | 33px | `--spacing-33` |
| 39 | 39px | `--spacing-39` |
| 49 | 49px | `--spacing-49` |
| 78 | 78px | `--spacing-78` |
| 86 | 86px | `--spacing-86` |
| 90 | 90px | `--spacing-90` |
| 108 | 108px | `--spacing-108` |
| 130 | 130px | `--spacing-130` |
| 217 | 217px | `--spacing-217` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 30px |
| buttons | 39px |

### Layout

- **Page max-width:** 1200px
- **Section gap:** 187px
- **Card padding:** 30px
- **Element gap:** 20px

## Components

### Primary Action Button
**Role:** Filled button

Primary action button with a deep violet background, white text, and highly rounded corners. text-color: #ffffff (Canvas White), background-color: #5e45a2 (Action Violet), border-radius: 39px.

### Ghost Navigation Link
**Role:** Primary navigation item, text-based

Navigation links are simple text, often with subtle hover states (not explicitly detected but implied), using the secondary text color. text-color: #6e6d7a (Text Secondary), font-weight: 400.

### Default Content Card
**Role:** Standard container for information

Cards feature large rounded corners and a soft, slightly off-white background, creating a distinct visual separation from the main canvas. background-color: #f7f7f7 (Subtle Gray), border-radius: 30px, padding: 30px.

### Minimal Card
**Role:** Container without explicit padding

Used when content directly abuts edges or components provide their own padding. background-color: #ffffff (Canvas White), border-radius: 30px, padding: 0px.

### Accent Card
**Role:** Card with a light background tint

Cards with a very light background hue, providing a subtle visual break. background-color: #e7efff (extracted from rgb(231, 239, 255)), border-radius: 30px, padding: 0px.

### Muted Text Badge
**Role:** Small text label

Used for descriptive tags or inline annotations. text-color: #6e6d7a (Text Secondary), background-color: transparent, border-radius: 0px, padding: 0px.

## Do's and Don'ts

### Do
- Maintain a spacious layout, ensuring a minimum sectionGap of 187px between major content blocks.
- Use Avenir Next, weight 400 for body text and weight 600 for headings, adhering to the defined type scale and letter-spacing values to maintain visual lightness.
- Apply Canvas White (#ffffff) as the dominant background for body and primary surfaces, creating a bright, uncluttered feel.
- Round all interactive elements like buttons and input fields with a 39px border-radius.
- Ensure all cards use a 30px border-radius and either Subtle Gray (#f7f7f7) or Canvas White (#ffffff) backgrounds.
- Define UI hierarchy using subtle distinctions: Text Primary (#383938) for main content, Text Secondary (#6e6d7a) for supportive details and navigation, and Border Fog (#edeef3) for minimal outlines.
- Reserve Action Violet (#5e45a2) exclusively for primary calls to action, active states, and elements that require immediate user interaction.

### Don't
- Avoid heavy shadows or strong gradients; the interface should remain largely flat and airy.
- Do not introduce new typefaces; rely solely on Avenir Next for consistency in brand voice.
- Refrain from using saturated colors other than Action Violet, particularly for backgrounds or large areas.
- Do not use box-shadow for elevation; rely on background color changes and subtle borders for surface distinction.
- Avoid dense information blocks; instead, break content into digestible sections with generous padding and clear visual separation.
- Do not deviate from the defined border-radius values of 39px for buttons and 30px for cards; this is a core aspect of the brand's friendly professional aesthetic.
- Never use generic system link blue (#0000ee) for text links; use Text Secondary (#6e6d7a).

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Canvas White | `#ffffff` | Dominant page background and primary, elevated surfaces like modals or top-level cards. |
| 2 | Subtle Gray | `#f7f7f7` | Secondary background for cards, providing a soft contrast to the main canvas. |
| 3 | Accent Card White | `#e7efff` | A very light, tinted background used for specific cards to add subtle visual variation. |

## Imagery

This site prominently features product screenshots embedded within devices (MacBooks, iPhones, Apple Watches) on pristine white backgrounds. The screenshots are presented cleanly, often angled or slightly overlapping to create visual interest while maintaining focus on the app interface itself. There are no lifestyle photos or abstract illustrations. Iconography (visible in product screenshots) appears to be outlined or ghost-style with a thin stroke. Imagery serves to showcase the product's functionality and visual design directly, demonstrating the app in its native environments.

## Layout

The page primarily uses a max-width 1200px centered layout for content, sitting on a full-bleed white background. The hero section is characterized by a centered dominant headline and subtext, followed by a primary action button. Subsequent sections maintain consistent vertical spacing (approx. 187px sectionGap) and often feature large product screenshots or mockups that break the max-width constraint, extending closer to the edge or being centrally placed. Content is arranged in alternating visual rhythm, often implying a text-left/visual-right pattern, with prominent product visuals. Navigation is a minimal top bar with subtly styled links and the brand logo, indicating a focus on content over complex navigation structures.

## Agent Prompt Guide

Quick Color Reference:
text: #383938
background: #ffffff
border: #edeef3
accent: #5e45a2
primary action: no distinct CTA color

Example Component Prompts:
No distinct primary action color was observed; use the extracted neutral button treatments instead of inventing a filled CTA color.
2. Design a default informational card: background #f7f7f7, border-radius 30px, 30px padding. Inside, place a heading (Avenir Next weight 600 at 29px, #383938) and a body paragraph (Avenir Next weight 400 at 17px, #383938).
3. Generate a top navigation bar: Canvas White background, 108px height, containing a 'Doo' logo (place at left, use brand's visual identity), and ghost navigation links (Text Secondary #6e6d7a, Avenir Next weight 400 at 17px) evenly spaced to the right, with a 21px elementGap between links.

## Similar Brands

- **Things 3** — Shares a clean, minimalist aesthetic with rounded UI elements and a focus on essential functionality over decorative visuals.
- **Any.do** — Similar white-space heavy design, compact typography, and a strategic use of a single accent color for primary actions.
- **Cultured Code** — Employs a stark white background, crisp typography, and product screenshots within device mockups to showcase app features.
- **Todoist** — Focuses on high readability, a restrained color palette, and clear visual hierarchy for a productivity application.
- **Linear** — Known for a clean, fast UI, minimal border treatments, and strong typographic hierarchy on a light canvas.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-subtle-gray: #f7f7f7;
  --color-border-fog: #edeef3;
  --color-text-primary: #383938;
  --color-text-secondary: #6e6d7a;
  --color-shadow-ink: #111111;
  --color-action-violet: #5e45a2;

  /* Typography — Font Families */
  --font-avenir-next: 'Avenir Next', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 1.2;
  --tracking-caption: 0.13px;
  --text-body-sm: 16px;
  --leading-body-sm: 1.2;
  --tracking-body-sm: 0.16px;
  --text-subheading: 20px;
  --leading-subheading: 1.2;
  --text-heading-sm: 29px;
  --leading-heading-sm: 1.2;
  --text-heading: 39px;
  --leading-heading: 1;
  --tracking-heading: -0.4px;
  --text-display: 65px;
  --leading-display: 1;
  --tracking-display: -0.8px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-semibold: 600;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-10: 10px;
  --spacing-13: 13px;
  --spacing-19: 19px;
  --spacing-20: 20px;
  --spacing-21: 21px;
  --spacing-26: 26px;
  --spacing-33: 33px;
  --spacing-39: 39px;
  --spacing-49: 49px;
  --spacing-78: 78px;
  --spacing-86: 86px;
  --spacing-90: 90px;
  --spacing-108: 108px;
  --spacing-130: 130px;
  --spacing-217: 217px;

  /* Layout */
  --page-max-width: 1200px;
  --section-gap: 187px;
  --card-padding: 30px;
  --element-gap: 20px;

  /* Border Radius */
  --radius-3xl: 30px;
  --radius-3xl-2: 39px;

  /* Named Radii */
  --radius-cards: 30px;
  --radius-buttons: 39px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-subtle-gray: #f7f7f7;
  --surface-accent-card-white: #e7efff;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-subtle-gray: #f7f7f7;
  --color-border-fog: #edeef3;
  --color-text-primary: #383938;
  --color-text-secondary: #6e6d7a;
  --color-shadow-ink: #111111;
  --color-action-violet: #5e45a2;

  /* Typography */
  --font-avenir-next: 'Avenir Next', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 1.2;
  --tracking-caption: 0.13px;
  --text-body-sm: 16px;
  --leading-body-sm: 1.2;
  --tracking-body-sm: 0.16px;
  --text-subheading: 20px;
  --leading-subheading: 1.2;
  --text-heading-sm: 29px;
  --leading-heading-sm: 1.2;
  --text-heading: 39px;
  --leading-heading: 1;
  --tracking-heading: -0.4px;
  --text-display: 65px;
  --leading-display: 1;
  --tracking-display: -0.8px;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-10: 10px;
  --spacing-13: 13px;
  --spacing-19: 19px;
  --spacing-20: 20px;
  --spacing-21: 21px;
  --spacing-26: 26px;
  --spacing-33: 33px;
  --spacing-39: 39px;
  --spacing-49: 49px;
  --spacing-78: 78px;
  --spacing-86: 86px;
  --spacing-90: 90px;
  --spacing-108: 108px;
  --spacing-130: 130px;
  --spacing-217: 217px;

  /* Border Radius */
  --radius-3xl: 30px;
  --radius-3xl-2: 39px;
}
```

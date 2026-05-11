# Sociotype — Style Reference
> Editorial White Canvas

**Theme:** light

Sociotype presents as a serious, editorial platform for typography, characterized by an expansive white canvas, precise black typography, and highly controlled spacing. Interaction elements are almost entirely ghosted or underlined, relying on a subtle shift to black for active states. The visual weight is carried by the large, expressive font specimens and carefully structured content blocks, rather than decorative colors or heavy UI components.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card surfaces, primary text on dark hero sections |
| Ink Black | `#000000` | `--color-ink-black` | Primary text, borders, active states for ghost buttons and navigation, accent markings |
| Medium Gray | `#818181` | `--color-medium-gray` | Muted text, secondary information, placeholder text, inactive link borders |
| Light Gray | `#d6d6d6` | `--color-light-gray` | Subtle dividers, borders between content sections |
| Faded Gray | `#9d9d9d` | `--color-faded-gray` | Tertiary text, list item borders |

## Tokens — Typography

### Main Onsite — Main Onsite — detected in extracted data but not described by AI · `--font-main-onsite`
- **Weights:** 400
- **Sizes:** 11px, 12px, 13px, 14px, 16px, 18px, 26px, 40px
- **Line height:** 1, 1.13, 1.19, 1.22, 1.29, 1.31, 1.33, 1.38
- **Letter spacing:** 0.015, 0.025, 0.04, 0.05, 0.08
- **Role:** Main Onsite — detected in extracted data but not described by AI

### Onsite — Primary typeface for all body text, navigation, buttons, and smaller headings. Its regular weight ensures readability while maintaining a modern, understated presence. · `--font-onsite`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400
- **Sizes:** 251px
- **Line height:** 1.25
- **Letter spacing:** 0.0800em at 11px, 0.0500em at 12px, 0.0400em at 13px, 0.0250em at 14px, 0.0150em at 16px, 0.0150em at 18px
- **Role:** Primary typeface for all body text, navigation, buttons, and smaller headings. Its regular weight ensures readability while maintaining a modern, understated presence.

### Avec Sharp — Display typeface for featured headlines and typographic showcases. Its unique character defines the brand's aesthetic in a large, impactful way. · `--font-avec-sharp`
- **Substitute:** serif
- **Weights:** 400
- **Sizes:** 251px
- **Line height:** 1.25
- **Letter spacing:** 0.0010em
- **Role:** Display typeface for featured headlines and typographic showcases. Its unique character defines the brand's aesthetic in a large, impactful way.

### Ceno — Alternative display typeface, used for specific typographic showcases. Shares the overall expressive, impactful role of Avec Sharp. · `--font-ceno`
- **Substitute:** serif
- **Weights:** 400
- **Sizes:** 251px
- **Line height:** 1.25
- **Letter spacing:** 0.0010em
- **Role:** Alternative display typeface, used for specific typographic showcases. Shares the overall expressive, impactful role of Avec Sharp.

### Meso — Alternative display typeface, used for specific typographic showcases. Expands the brand's visual range for showcasing different font styles. · `--font-meso`
- **Substitute:** serif
- **Weights:** 400
- **Sizes:** 251px
- **Line height:** 1.25
- **Letter spacing:** 0.0010em
- **Role:** Alternative display typeface, used for specific typographic showcases. Expands the brand's visual range for showcasing different font styles.

### Gestura — Alternative display typeface with ligatures, used for specific typographic showcases. Highlights the intricate details of font design. · `--font-gestura`
- **Substitute:** serif
- **Weights:** 400
- **Sizes:** 251px
- **Line height:** 1.25
- **Letter spacing:** 0.0010em
- **OpenType features:** `'liga' on`
- **Role:** Alternative display typeface with ligatures, used for specific typographic showcases. Highlights the intricate details of font design.

### Rework — Alternative display typeface, used for specific typographic showcases. Contributes to the diverse presentation of font families. · `--font-rework`
- **Substitute:** serif
- **Weights:** 400
- **Sizes:** 251px
- **Line height:** 1.25
- **Letter spacing:** 0.0010em
- **Role:** Alternative display typeface, used for specific typographic showcases. Contributes to the diverse presentation of font families.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 11px | 1.38 | 0.88px | `--text-caption` |
| body | 14px | 1.29 | 0.35px | `--text-body` |
| heading | 26px | 1.13 | 0.26px | `--text-heading` |
| display-sm | 40px | 1 | 0.6px | `--text-display-sm` |
| display | 251px | 1.25 | 2.51px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 8 | 8px | `--spacing-8` |
| 12 | 12px | `--spacing-12` |
| 24 | 24px | `--spacing-24` |
| 120 | 120px | `--spacing-120` |
| 140 | 140px | `--spacing-140` |

### Border Radius

| Element | Value |
|---------|-------|
| none | 0px |

### Layout

- **Section gap:** 120px
- **Card padding:** 0px
- **Element gap:** 12px

## Components

### Ghost Button - Inactive
**Role:** Navigational and call-to-action link styling

Text in Ink Black or Canvas White, with a 1px bottom border of the same color. No background fill or padding. This gives buttons a lightweight, integrated feel with the surrounding text.

### Ghost Button - Muted
**Role:** Secondary actions or menu items

Text in Medium Gray, with a 1px bottom border of the same color. No background fill or padding. Used for less prominent interactive elements.

### Featured Card
**Role:** Displaying prominent typefaces without visual distraction

Completely transparent background, no borders, no box shadow, with 0px border-radius. Content manages its own spacing and visual hierarchy. Features a text block with 'Onsite' typography, 14px size, Ink Black color, 0.025em letter spacing, and a 1px Ink Black bottom border for 'More Info' link.

### Text Input
**Role:** User input for forms (e.g., newsletter signup)

Transparent background, placeholder/text in Medium Gray (#818181), with a thin 1px bottom border in Medium Gray.

## Do's and Don'ts

### Do
- Prioritize Ink Black (#000000) for all primary text and interactive element outlines on default light backgrounds.
- Use Canvas White (#ffffff) as the dominant page, card, and footer background, establishing a clean, expansive aesthetic.
- Maintain a strict 0px border-radius for all components, including buttons, cards, and input fields, for a sharp, precise feel.
- Implement interactive elements primarily as ghost buttons or underlined text, with minimal visual styling beyond color and text decoration transitions.
- Structure content with ample vertical spacing, leveraging the implied section gap of 120px to create distinct content blocks.
- Employ the Onsite font for all functional text under 'display' sizes, ensuring consistency in body, navigation, and button labels.
- Utilize Avec Sharp, Ceno, Meso, Gestura, or Rework fonts exclusively for large, impactful display typography to showcase different font characteristics.

### Don't
- Avoid using saturated background colors or heavy fills for interactive elements; stick to the achromatic palette.
- Do not introduce shadows or significant elevation on cards or buttons; elements should appear flat against the canvas.
- Refrain from applying rounded corners to any UI elements; all corners should be sharp 0px radius.
- Do not use highly contrasting accent colors for calls to action; rely on text weight, size, and subtle border changes for emphasis.
- Avoid dense, clustered layouts; allow generous empty space around content sections and individual elements.
- Do not deviate from the specified typefaces Onsite, Avec Sharp, Ceno, Meso, Gestura, or Rework; no other typefaces are part of this system.
- Do not use generic system fonts or default browser styles for links; ensure all interactive text uses the defined ghost button or underlined styles.

## Imagery

This design system relies heavily on large-scale typographic specimen imagery and abstract, sometimes vibrant, graphic backgrounds behind hero sections. Photography is absent. Illustrations are primarily abstract, organic, and colorful, serving as striking backdrops that contrast with the monochrome UI. Icons, if present, are minimal vector outlines, like the 'Cart' icon, suggesting a thin stroke weight. The imagery serves a decorative, atmospheric role, often full-bleed in hero sections, providing visual intrigue without distracting from the UI or text.

## Layout

The page maintains a full-bleed structure without a fixed maximum width for its main content, allowing elements to span the entire viewport. The hero section often features a large-scale, sometimes abstract image or graphic background with centered, prominent type specimen alongside informative text. Content sections below the hero typically follow a two-column layout with text on one side and associated visuals or another type specimen on the other. Navigation is a minimalist top bar with ghosted links, and a very large, eye-catching text (Sociotype) floats over the hero graphic. Vertical rhythm is established through generous, consistent section gaps, creating a spacious, editorial flow rather than a dense grid.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #ffffff
border: #000000
accent: no distinct accent color
primary action: no distinct CTA color

Example Component Prompts:
1. Create a top navigation bar: Canvas White background, Ink Black ghost text links in Onsite font at 14px (letter-spacing 0.35px). Each link should have a 1px Ink Black bottom border on hover. Spacing between links is 50px right margin. Global top-left brand text 'SOCIOTYPE' in Ink Black. Top-right utilitarian links 'Shop', 'Trials', 'About', 'Cart (0)'.
2. Design a featured typeface section: Canvas White background. Headline 'Featured: [Typeface Name]' in Onsite 40px (letter-spacing 0.6px), Ink Black. Followed by descriptive body text in Onsite 14px (letter-spacing 0.35px), Ink Black. A 'More Info →' ghost button (Ink Black text and 1px bottom border, Onsite 14px, letter-spacing 0.35px).
3. Create a prominent typeface showcase block: Avec Sharp 251px (letter-spacing 2.51px) in Ink Black on a Canvas White background. Ensure no padding or border-radius, maintaining a sharp edge.

## Similar Brands

- **Fonts.com** — Similar focus on typographic display and large font specimen showcases.
- **Future Fonts** — Monochromatic interface, emphasis on typefaces, and ghosted interactive elements.
- **Pangram Pangram** — Clean, spacious layout with strong typographic hierarchy, and limited use of color.
- **Grilli Type** — Editorial aesthetic with large-scale typography and minimal UI decoration.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ink-black: #000000;
  --color-medium-gray: #818181;
  --color-light-gray: #d6d6d6;
  --color-faded-gray: #9d9d9d;

  /* Typography — Font Families */
  --font-main-onsite: 'Main Onsite', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-onsite: 'Onsite', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-avec-sharp: 'Avec Sharp', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ceno: 'Ceno', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-meso: 'Meso', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gestura: 'Gestura', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-rework: 'Rework', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.38;
  --tracking-caption: 0.88px;
  --text-body: 14px;
  --leading-body: 1.29;
  --tracking-body: 0.35px;
  --text-heading: 26px;
  --leading-heading: 1.13;
  --tracking-heading: 0.26px;
  --text-display-sm: 40px;
  --leading-display-sm: 1;
  --tracking-display-sm: 0.6px;
  --text-display: 251px;
  --leading-display: 1.25;
  --tracking-display: 2.51px;

  /* Typography — Weights */
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-24: 24px;
  --spacing-120: 120px;
  --spacing-140: 140px;

  /* Layout */
  --section-gap: 120px;
  --card-padding: 0px;
  --element-gap: 12px;

  /* Named Radii */
  --radius-none: 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ink-black: #000000;
  --color-medium-gray: #818181;
  --color-light-gray: #d6d6d6;
  --color-faded-gray: #9d9d9d;

  /* Typography */
  --font-main-onsite: 'Main Onsite', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-onsite: 'Onsite', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-avec-sharp: 'Avec Sharp', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ceno: 'Ceno', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-meso: 'Meso', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gestura: 'Gestura', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-rework: 'Rework', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.38;
  --tracking-caption: 0.88px;
  --text-body: 14px;
  --leading-body: 1.29;
  --tracking-body: 0.35px;
  --text-heading: 26px;
  --leading-heading: 1.13;
  --tracking-heading: 0.26px;
  --text-display-sm: 40px;
  --leading-display-sm: 1;
  --tracking-display-sm: 0.6px;
  --text-display: 251px;
  --leading-display: 1.25;
  --tracking-display: 2.51px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-24: 24px;
  --spacing-120: 120px;
  --spacing-140: 140px;
}
```

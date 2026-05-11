# Morflax — Style Reference
> Architectural blueprints on frosted glass.

**Theme:** light

Morflax uses a high-contrast, material-inspired design language featuring stark white canvases and dark, compact typography. Components are built with generous rounded corners and subtle, layered shadows to give a sense of depth without harshness. A single vivid blue accent color is reserved for primary actions, providing a clear focal point against the otherwise monochromatic interface. The overall impression is one of modern precision, balanced by soft, approachable forms.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Graphite | `#000000` | `--color-midnight-graphite` | Major surface background (dark cards in hero), primary text where contrast is highest |
| Storm Gray | `#25282b` | `--color-storm-gray` | Prominent button text, icon fills and strokes (especially at smaller sizes or in navigation) |
| Neutral Canvas | `#ffffff` | `--color-neutral-canvas` | Page background, primary card surfaces beneath dark text, ghost button backgrounds, default text color on dark backgrounds |
| Light Pearl | `#f5f5f7` | `--color-light-pearl` | Subtly elevated card backgrounds, secondary neutral button backgrounds for ghost actions, body text on light canvases where contrast is slightly softer |
| Border Silver | `#e5e7eb` | `--color-border-silver` | Hairline borders, dividers, subtle outlines on ghost buttons, accents on secondary navigation elements |
| Ash Cloud | `#bfbfbf` | `--color-ash-cloud` | Soft shadow tint for elevation effects |
| Header Slate | `#333333` | `--color-header-slate` | Navigation bar background |
| Link Gray | `#7c7e83` | `--color-link-gray` | Muted secondary navigation links, soft body text, descriptive text |
| Icon Mist | `#a3a7ad` | `--color-icon-mist` | Tertiary navigation text, small icons, less emphasized helper text |
| Skybound Blue | `#298ef5` | `--color-skybound-blue` | Primary action button backgrounds, active states, key interactive highlights |
| Linear Gradient Gray | `linear-gradient(to top, rgb(30, 30, 31), rgb(104, 105, 112))` | `--color-linear-gradient-gray` | Background for specific hero sections or impactful visual components, suggesting depth |
| Radial Frost | `radial-gradient(64.38% 210.53% at 35.62% 50%, rgb(223, 225, 240) 0px, rgb(174, 177, 204) 100%)` | `--color-radial-frost` | Soft, expansive background effect, suggesting an ethereal or illuminated space |
| Linear Steel | `linear-gradient(to top, rgb(198, 200, 215), rgb(118, 120, 129))` | `--color-linear-steel` | Alternative gradient background for complex backgrounds or thematic sections |

## Tokens — Typography

### Inter — Workhorse sans-serif for all UI text, body copy, and secondary headings. Its versatility supports both dense information and prominent headlines through significant size and weight variations. · `--font-inter`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400, 500, 600
- **Sizes:** 12px, 14px, 16px, 18px, 20px, 24px, 36px, 48px, 60px, 72px
- **Line height:** 1.00, 1.11, 1.33, 1.40, 1.43, 1.50, 1.56
- **Letter spacing:** -0.0250em (for larger sizes), -0.0100em, 0.0500em (for smaller text, often uppercase)
- **Role:** Workhorse sans-serif for all UI text, body copy, and secondary headings. Its versatility supports both dense information and prominent headlines through significant size and weight variations.

### rogan — Used for specific stylized headings or callouts, particularly those that require an uppercase, tracked appearance, adding a distinctive brand voice. · `--font-rogan`
- **Weights:** 500
- **Sizes:** 16px, 24px
- **Line height:** 1.33, 1.50
- **Letter spacing:** 0.0500em
- **Role:** Used for specific stylized headings or callouts, particularly those that require an uppercase, tracked appearance, adding a distinctive brand voice.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.5 | — | `--text-caption` |
| body-sm | 14px | 1.5 | — | `--text-body-sm` |
| body | 16px | 1.5 | — | `--text-body` |
| subheading | 18px | 1.4 | — | `--text-subheading` |
| heading-sm | 20px | 1.4 | — | `--text-heading-sm` |
| heading | 24px | 1.33 | 0.48px | `--text-heading` |
| heading-lg | 36px | 1.11 | — | `--text-heading-lg` |
| display | 72px | 1 | -1.8px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 8 | 8px | `--spacing-8` |
| 12 | 12px | `--spacing-12` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 80 | 80px | `--spacing-80` |
| 112 | 112px | `--spacing-112` |
| 160 | 160px | `--spacing-160` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 9999px |
| cards | 24px |
| avatar | 9999px |
| inputs | 12px |
| buttons | 9999px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| xl | `rgba(0, 0, 0, 0.25) 0px 25px 50px -12px` | `--shadow-xl` |
| md | `rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1)...` | `--shadow-md` |

### Layout

- **Section gap:** 48px
- **Card padding:** 24px
- **Element gap:** 24px

## Components

### Pill Button - Default
**Role:** Secondary action button, often paired with primary blue button or for navigation.

White background (`#ffffff`), Storm Gray text (`#25282b`), Border Silver border (`#e5e7eb`), fully rounded (9999px), with 12px vertical and 24px horizontal padding. Uses Inter font.

### Pill Button - Light Secondary
**Role:** Subtly elevated secondary button for less emphasis than default.

Light Pearl background (`#f5f5f7`), Storm Gray text (`#25282b`), white border (`#ffffff`), fully rounded (9999px), with 12px vertical and 32px horizontal padding. Uses Inter font.

### Primary Action Button - Filled
**Role:** Call to action, high prominence.

Skybound Blue background (`#298ef5`), Neutral Canvas text (`#ffffff`), Border Silver border (`#e5e7eb`), fully rounded (9999px), with 48px vertical and 112px horizontal padding. Uses Inter font.

### Neutral Card - Light
**Role:** Standard content container on light backgrounds.

Light Pearl background (`#f5f5f7`), 16px border-radius, no shadow. Padding internal to content, not the card itself.

### Neutral Card - Shadowed
**Role:** Elevated white card for key content sections or hover states.

Neutral Canvas background (`#ffffff`), 24px border-radius, subtle shadow: `rgba(0, 0, 0, 0.25) 0px 25px 50px -12px`. Padding internal to content, not the card itself.

### Dark Card - Shadowed
**Role:** Featured cards or rich content areas on dark backgrounds.

Midnight Graphite background (`#000000`), 16px border-radius, subtle shadow: `rgba(0, 0, 0, 0.25) 0px 25px 50px -12px`. Padding internal to content, not the card itself.

### Navigation Bar
**Role:** Sticky top navigation for global access.

Header Slate background (`#333333`), with links in Icon Mist (`#a3a7ad`) and `Open Studio` button as a Primary Action Button.

## Do's and Don'ts

### Do
- Use Neutral Canvas (`#ffffff`) as the base page background for most sections.
- Apply Skybound Blue (`#298ef5`) exclusively for primary call-to-action buttons and active interactive elements.
- Implement fully rounded (9999px) shapes for all buttons and small interactive elements like tags.
- Use Inter font family with an open letter-spacing when text is 16px or smaller, and a tighter letter-spacing for headlines 36px and above.
- Adhere to an overall comfortable density with element gaps of 24px and card padding of 24px.
- Apply `rgba(0, 0, 0, 0.25) 0px 25px 50px -12px` shadow for elevated components like cards, and `rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1) 0px 4px 6px -4px` for button elevation.
- Reserve the `rogan` font for special brand-oriented headings or highly stylized text blocks.

### Don't
- Do not use highly saturated colors other than Skybound Blue (`#298ef5`) for interface elements; maintain a monochromatic palette.
- Avoid sharp corners; ensure all significant interactive elements and containers have a minimum radius of 12px.
- Do not use dark backgrounds for general page content unless it's a dedicated hero or featured section; default to light themes.
- Avoid heavy borders or strong outlines on elements unless explicitly part of an active state or a 'ghost' visual style.
- Do not use the `rogan` font for body text or small UI labels; its use is limited to larger, impactful brand statements.
- Do not introduce new shadow styles; use the defined `rgba(0, 0, 0, 0.25) 0px 25px 50px -12px` and `rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1) 0px 4px 6px -4px` consistently.
- Do not vary line-height significantly from the provided type scale values; maintain the established vertical rhythm.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Neutral Canvas | `#ffffff` | Base page background |
| 1 | Light Pearl | `#f5f5f7` | Elevated card backgrounds, ghost secondary buttons |
| 2 | Midnight Graphite | `#000000` | Dark section backgrounds, prominent specialized cards |

## Elevation

- **Card:** `rgba(0, 0, 0, 0.25) 0px 25px 50px -12px`
- **Button:** `rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1) 0px 4px 6px -4px`

## Imagery

Imagery primarily features studio-quality 3D renders and product mockups. These are typically contained within cards, often against gradient backgrounds, and are product-focused rather than lifestyle-oriented. Photography is highly stylized, featuring subjects often in silhouette or with dramatic lighting. Icons are predominantly filled, using the Storm Gray (`#25282b`) for neutrals, with a precise stroke weight where outlined. Overlapping elements or raw edges are rare; visuals generally adhere to the card boundaries with generous border radii. The density of imagery is balanced, supporting text rather than overwhelming it, but playing a key role in visual branding and product demonstration.

## Layout

The page primarily uses a max-width contained layout, allowing for comfortable reading and focused content. The hero section is full-bleed, using a dramatic gradient background with centered, large-scale typography and a central visual element. Subsequent sections alternate between white and light gray (`#f5f5f7`) backgrounds, creating a clear vertical rhythm. Content is generally arranged in alternating text-left/visual-right patterns or centered stacks. Feature sections often utilize a 3-4 column card grid with consistent spacing. The navigation is a sticky top bar with a dark header background, maintaining global access. Overall, the layout feels spacious and organized, guiding the eye through distinct content blocks.

## Agent Prompt Guide

Quick Color Reference:
text: #25282b
background: #ffffff
border: #e5e7eb
accent: #298ef5
primary action: #298ef5 (filled action)

Example Component Prompts:
1. Create a Hero Section: A full-bleed linear gradient background, `linear-gradient(to top, rgb(30, 30, 31), rgb(104, 105, 112))`. Centered headline 'MORFLAX' in Inter, 72px, weight 600, color `Midnight Graphite`, letter-spacing -1.8px. Below it, a subheading 'Creative technology studio building design + motion tools, mockups, and interactive visuals.' in Inter, 24px, weight 400, color `Neutral Canvas`. Two pill buttons (`#ffffff` background, `#25282b` text, `#e5e7eb` border, 9999px radius, 12px vertical/24px horizontal padding) reading 'Explore Ecosystem' and 'Open Studio', horizontally spaced by 24px.
2. Create a Feature Card: Light Pearl background (`#f5f5f7`), 16px radius, no shadow. Inside, a bold title 'Abstract Generator' in Inter, 20px, weight 600, color `Storm Gray`. Implement with 24px internal padding.
3. Create a Primary CTA Button: Skybound Blue background (`#298ef5`), Neutral Canvas text (`#ffffff`), Border Silver border (`#e5e7eb`), 9999px radius, 48px vertical/112px horizontal padding, with `rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1) 0px 4px 6px -4px` shadow. Text 'Get Started' in Inter, 18px, weight 500, with letter spacing 0.72px.
4. Create a Navigation Link: Text 'Products' in Inter, 16px, weight 500, color `Icon Mist` (`#a3a7ad`), no underline. Hover state should change text color to `Storm Gray` (`#25282b`).

## Similar Brands

- **Figma** — Monochromatic interface with a single vibrant brand accent color for interactive elements and clear focus, and soft rounded forms.
- **Linear** — High-contrast typography, focus on functional and minimal UI, and subtle elevation/shadows to define interactive areas.
- **Spline** — Emphasis on 3D visuals and product renders integrated directly into the UI, often with a clean, light aesthetic.
- **Renderforest** — Focus on creative toolsets with heavy use of cards for feature presentation and a clean overall layout.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-graphite: #000000;
  --color-storm-gray: #25282b;
  --color-neutral-canvas: #ffffff;
  --color-light-pearl: #f5f5f7;
  --color-border-silver: #e5e7eb;
  --color-ash-cloud: #bfbfbf;
  --color-header-slate: #333333;
  --color-link-gray: #7c7e83;
  --color-icon-mist: #a3a7ad;
  --color-skybound-blue: #298ef5;
  --color-linear-gradient-gray: #1e1e1f;
  --gradient-linear-gradient-gray: linear-gradient(to top, rgb(30, 30, 31), rgb(104, 105, 112));
  --color-radial-frost: #dfe1f0;
  --gradient-radial-frost: radial-gradient(64.38% 210.53% at 35.62% 50%, rgb(223, 225, 240) 0px, rgb(174, 177, 204) 100%);
  --color-linear-steel: #c6c8d7;
  --gradient-linear-steel: linear-gradient(to top, rgb(198, 200, 215), rgb(118, 120, 129));

  /* Typography — Font Families */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-rogan: 'rogan', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.4;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.4;
  --text-heading: 24px;
  --leading-heading: 1.33;
  --tracking-heading: 0.48px;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1.11;
  --text-display: 72px;
  --leading-display: 1;
  --tracking-display: -1.8px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-80: 80px;
  --spacing-112: 112px;
  --spacing-160: 160px;

  /* Layout */
  --section-gap: 48px;
  --card-padding: 24px;
  --element-gap: 24px;

  /* Border Radius */
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-tags: 9999px;
  --radius-cards: 24px;
  --radius-avatar: 9999px;
  --radius-inputs: 12px;
  --radius-buttons: 9999px;

  /* Shadows */
  --shadow-xl: rgba(0, 0, 0, 0.25) 0px 25px 50px -12px;
  --shadow-md: rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1) 0px 4px 6px -4px;

  /* Surfaces */
  --surface-neutral-canvas: #ffffff;
  --surface-light-pearl: #f5f5f7;
  --surface-midnight-graphite: #000000;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-graphite: #000000;
  --color-storm-gray: #25282b;
  --color-neutral-canvas: #ffffff;
  --color-light-pearl: #f5f5f7;
  --color-border-silver: #e5e7eb;
  --color-ash-cloud: #bfbfbf;
  --color-header-slate: #333333;
  --color-link-gray: #7c7e83;
  --color-icon-mist: #a3a7ad;
  --color-skybound-blue: #298ef5;
  --color-linear-gradient-gray: #1e1e1f;
  --color-radial-frost: #dfe1f0;
  --color-linear-steel: #c6c8d7;

  /* Typography */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-rogan: 'rogan', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.4;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.4;
  --text-heading: 24px;
  --leading-heading: 1.33;
  --tracking-heading: 0.48px;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1.11;
  --text-display: 72px;
  --leading-display: 1;
  --tracking-display: -1.8px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-80: 80px;
  --spacing-112: 112px;
  --spacing-160: 160px;

  /* Border Radius */
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-full: 9999px;

  /* Shadows */
  --shadow-xl: rgba(0, 0, 0, 0.25) 0px 25px 50px -12px;
  --shadow-md: rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1) 0px 4px 6px -4px;
}
```

# Revenue-Grade Automation — Style Reference
> Engineered Control Panel: precise, monochromatic, with a focused electric accent.

**Theme:** light

Default's design system evokes a meticulous, high-performance operating environment. It uses a near-monochromatic palette grounded in stark black and white, punctuated by a single electric violet accent. This controlled use of color, paired with precise typography that emphasizes both structure and clarity, creates a highly functional, engineered aesthetic. Components are lightweight, favoring ghost states and subtle fills over heavy embellishment, maintaining a sense of efficiency and focus on data flow.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#202020` | `--color-midnight-ink` | Primary text, deep surface elements, button backgrounds for secondary actions |
| Cloud Canvas | `#f5f5f5` | `--color-cloud-canvas` | Page backgrounds, card surfaces, ghost button backgrounds |
| Paper White | `#ffffff` | `--color-paper-white` | Elevated card backgrounds, input fields, internal component surfaces |
| Muted Ash | `#333333` | `--color-muted-ash` | Secondary text, input text, link text in neutral contexts |
| Ghost Border | `#f7f5fd` | `--color-ghost-border` | Hairline borders, subtle dividers, input field borders |
| Electric Violet | `#5757f8` | `--color-electric-violet` | Primary action buttons, active navigation indicators, brand accents, interactive elements — creating focused activation against the neutral palette |

## Tokens — Typography

### NB International Pro — Headlines and large display text — the tight letter-spacing and strong weights convey an architectural precision. The 72px size at 500 weight feels authoritative without being shouty. · `--font-nb-international-pro`
- **Substitute:** Montserrat
- **Weights:** 500, 700
- **Sizes:** 26px, 36px, 48px, 64px, 72px
- **Line height:** 0.97, 1.00, 1.20
- **Letter spacing:** -0.96
- **Role:** Headlines and large display text — the tight letter-spacing and strong weights convey an architectural precision. The 72px size at 500 weight feels authoritative without being shouty.

### Saans Trial — Body text, navigation, buttons, and all functional interface elements. Its generous line-height ensures readability across varied UI contexts, from compact buttons to multi-line paragraphs. · `--font-saans-trial`
- **Substitute:** Inter
- **Weights:** 500, 700
- **Sizes:** 14px, 16px, 18px, 20px
- **Line height:** 1.20, 1.40, 1.43
- **Letter spacing:** 0
- **Role:** Body text, navigation, buttons, and all functional interface elements. Its generous line-height ensures readability across varied UI contexts, from compact buttons to multi-line paragraphs.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 14px | 1.2 | — | `--text-caption` |
| body | 16px | 1.4 | — | `--text-body` |
| subheading | 18px | 1.43 | — | `--text-subheading` |
| heading-sm | 20px | 1.43 | — | `--text-heading-sm` |
| heading | 26px | 1.2 | -0.52px | `--text-heading` |
| heading-lg | 36px | 1 | -0.72px | `--text-heading-lg` |
| display | 48px | 0.97 | -0.96px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 8 | 8px | `--spacing-8` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 80 | 80px | `--spacing-80` |
| 88 | 88px | `--spacing-88` |
| 96 | 96px | `--spacing-96` |
| 176 | 176px | `--spacing-176` |

### Border Radius

| Element | Value |
|---------|-------|
| images | 12px |
| inputs | 10px |
| buttons | 1425.6px |
| default | 8px |

### Layout

- **Page max-width:** 1400px
- **Section gap:** 40px
- **Card padding:** 20px
- **Element gap:** 24px

## Components

### Primary Action Button
**Role:** Main call to action

Electric Violet background (#5757f8), Paper White text (#ffffff). Fully rounded corners (1425.6px) with 10px vertical and 20px horizontal padding. Font: Saans Trial, 500 weight, 16px.

### Secondary Action Button
**Role:** Secondary call to action or ghost button

Midnight Ink background (#202020), Paper White text (#ffffff). Fully rounded corners (1425.6px) with 10px vertical and 20px horizontal padding. Font: Saans Trial, 500 weight, 16px.

### Navigation Link Button
**Role:** Small, informational links

Cloud Canvas background (#f5f5f5), Midnight Ink text (#202020). Default 8px radius with 5px vertical and 10px horizontal padding. Font: Saans Trial, 500 weight, 14px.

### Navigation Outlined Button
**Role:** Header navigation with subtle styling

Paper White background (#ffffff), Midnight Ink text (#202020). Fully rounded corners (1425.6px) with 5px vertical and 10px horizontal padding. Font: Saans Trial, 500 weight, 14px.

### Default Card
**Role:** Information container, background for content blocks

Cloud Canvas background (#f5f5f5), 8px border-radius, 20px padding on all sides. No shadow.

### Accent Card
**Role:** Feature cards or testimonials with minimal styling

Transparent background, 8px border-radius. No shadow, 20px padding on all sides.

### Form Input Field
**Role:** Standard user input fields

Paper White background (#ffffff), Muted Ash text (#333333), Ghost Border (#f7f5fd) 1px border. 10px border-radius, 16px vertical and 20px horizontal padding. Placeholder text is Muted Ash.

### Filled Input Field
**Role:** Input field with a distinct background

Cloud Canvas background (#f5f5f5), Muted Ash text (#333333), Ghost Border (#f7f5fd) 1px border. 10px border-radius, 16px vertical and 20px horizontal padding. Placeholder text is Muted Ash.

## Do's and Don'ts

### Do
- Use NB International Pro for all headlines exceeding 20px text size, with letter-spacing of -0.02em.
- Prioritize Electric Violet (#5757f8) for primary calls to action, ensuring Paper White (#ffffff) text for legibility.
- Apply a full rounding of 1425.6px to all action buttons to create a distinctly pill-shaped appearance.
- Maintain a clear visual hierarchy with Cloud Canvas (#f5f5f5) as the primary background and Paper White (#ffffff) for elevated content surfaces.
- Employ Ghost Border (#f7f5fd) for all unpressed button borders, input borders, and subtle dividers.
- Use 20px padding inside all default content cards.
- Implement a 24px gap between most adjacent UI elements for consistent comfortable density.

### Don't
- Do not introduce new vibrant colors outside of the Electric Violet accent.
- Avoid heavy shadows or gradients; the design relies on flat planes and subtle borders for depth.
- Do not use generic square corners for interactive elements; buttons and inputs require specific rounded radii.
- Do not use text weights below 500; the system maintains a confident, legible tone.
- Avoid dense or cluttered layouts; prioritize clear spacing and visual separation between content blocks.
- Do not use any stroke widths other than 1px for borders and dividers.
- Do not let non-interactive elements have the same visual prominence as primary action buttons.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Cloud Canvas | `#f5f5f5` | Base page background, large content sections, primary card backgrounds. |
| 2 | Paper White | `#ffffff` | Elevated and interactive elements like input fields, header navigation backgrounds, and secondary card backgrounds. |
| 3 | Midnight Ink | `#202020` | Darker, functional surfaces like secondary button backgrounds or specific UI components (though not broadly used as a prominent surface). |

## Imagery

The visual language focuses on technical iconography and product UI showcases. Icons are primarily outlined or filled monochrome, often in Midnight Ink or Electric Violet. Product screenshots are presented within contained, rounded (8px) frames, focusing on clear workflow diagrams and data representations. No photography or abstract graphics are used. Imagery serves an explanatory and functional role, demonstrating the product's capabilities rather than creating atmosphere. The density of imagery is balanced, appearing as focused examples within text-dominant sections.

## Layout

The page adheres to a max-width 1400px contained layout, centered on a Cloud Canvas (#f5f5f5) background. The hero section features a centered headline over a subtle dotted grid background, creating an engineered feel. Content flows in distinct sections with consistent vertical padding, often alternating between text-centric blocks, logo grids, and product UI showcases. The interface showcases often use a two-column layout with a prominent visual on one side. A sticky top navigation bar with a clear primary action button maintains persistent access to key features.

## Agent Prompt Guide

### Quick Color Reference
text: #202020
background: #f5f5f5
border: #f7f5fd
accent: #5757f8
primary action: #5757f8 (filled action)

### 3-5 Example Component Prompts
1. Create a hero section: Cloud Canvas background (#f5f5f5) with a subtle grid pattern. Headline 'Run revenue like an engineered system' using NB International Pro, 72px, 500 weight, Midnight Ink (#202020), letter-spacing -1.44px. Below it, a Primary Action Button 'Book a demo' (#5757f8 background, #ffffff text, 1425.6px radius, 10px vertical / 20px horizontal padding). Below that, a Secondary Action Button 'See an interactive demo' (#202020 background, #ffffff text, 1425.6px radius, 10px vertical / 20px horizontal padding).
2. Create a content card for a feature description: Default Card with Cloud Canvas background (#f5f5f5), 8px radius, 20px padding. Inside, a heading 'Stop firefighting' using NB International Pro, 36px, 500 weight, Midnight Ink (#202020), letter-spacing -0.72px. Followed by body text using Saans Trial, 16px, 500 weight, Muted Ash (#333333).
3. Create a Primary Action Button: #5757f8 background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.

## Similar Brands

- **Linear** — Monochromatic base with a single vibrant accent color for interaction and brand identity, paired with precise typography.
- **Stripe** — Clean, spacious layouts, strong typographic hierarchy, and a focus on functional UI components with subtle depth.
- **Plaid** — Emphasis on data flow and engineered systems, reflected in a precise, functional, and visually restrained interface.
- **Superhuman** — Fast, UI-driven aesthetic with compact components, stark backgrounds, and specific color accents for productivity.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #202020;
  --color-cloud-canvas: #f5f5f5;
  --color-paper-white: #ffffff;
  --color-muted-ash: #333333;
  --color-ghost-border: #f7f5fd;
  --color-electric-violet: #5757f8;

  /* Typography — Font Families */
  --font-nb-international-pro: 'NB International Pro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-saans-trial: 'Saans Trial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.2;
  --text-body: 16px;
  --leading-body: 1.4;
  --text-subheading: 18px;
  --leading-subheading: 1.43;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.43;
  --text-heading: 26px;
  --leading-heading: 1.2;
  --tracking-heading: -0.52px;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -0.72px;
  --text-display: 48px;
  --leading-display: 0.97;
  --tracking-display: -0.96px;

  /* Typography — Weights */
  --font-weight-medium: 500;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-80: 80px;
  --spacing-88: 88px;
  --spacing-96: 96px;
  --spacing-176: 176px;

  /* Layout */
  --page-max-width: 1400px;
  --section-gap: 40px;
  --card-padding: 20px;
  --element-gap: 24px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-full: 1425.6px;

  /* Named Radii */
  --radius-images: 12px;
  --radius-inputs: 10px;
  --radius-buttons: 1425.6px;
  --radius-default: 8px;

  /* Surfaces */
  --surface-cloud-canvas: #f5f5f5;
  --surface-paper-white: #ffffff;
  --surface-midnight-ink: #202020;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #202020;
  --color-cloud-canvas: #f5f5f5;
  --color-paper-white: #ffffff;
  --color-muted-ash: #333333;
  --color-ghost-border: #f7f5fd;
  --color-electric-violet: #5757f8;

  /* Typography */
  --font-nb-international-pro: 'NB International Pro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-saans-trial: 'Saans Trial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.2;
  --text-body: 16px;
  --leading-body: 1.4;
  --text-subheading: 18px;
  --leading-subheading: 1.43;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.43;
  --text-heading: 26px;
  --leading-heading: 1.2;
  --tracking-heading: -0.52px;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -0.72px;
  --text-display: 48px;
  --leading-display: 0.97;
  --tracking-display: -0.96px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-80: 80px;
  --spacing-88: 88px;
  --spacing-96: 96px;
  --spacing-176: 176px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-full: 1425.6px;
}
```

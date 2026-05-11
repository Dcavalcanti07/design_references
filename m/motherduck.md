# MotherDuck — Style Reference
> Playful blueprint on paper bag

**Theme:** light

MotherDuck employs a playful-professional aesthetic, blending familiar UI patterns with whimsical, hand-drawn illustration accents. The system grounds itself in a very light, almost off-white canvas, contrasting with bold, all-caps typography for headings. A singular vibrant sky blue is reserved for primary interactive elements, while a variety of other vivid hues appear as decorative button borders or illustration details. UI components maintain a lightweight, somewhat squarish feel with minimal border-radius and a notable absence of deep shadows for elevation.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas Oat | `#f4efea` | `--color-canvas-oat` | Page backgrounds, large content sections, subtle background for headers |
| Paper White | `#ffffff` | `--color-paper-white` | Card surfaces, input backgrounds, navigation backgrounds, default text for contrast |
| Smoke Gray | `#f8f8f7` | `--color-smoke-gray` | Subtle surface accents, secondary button backgrounds, muted light text |
| Ink | `#383838` | `--color-ink` | Primary text, strong borders, dark accents |
| Coal | `#000000` | `--color-coal` | Strongest text, icon fills, button text on light backgrounds |
| Slate | `#818181` | `--color-slate` | Muted text, less prominent borders, placeholder text |
| Sky Blue | `#6fc2ff` | `--color-sky-blue` | Primary action buttons, active navigation indicators, crucial interactive elements, outlined button borders |
| Mellow Yellow | `#ffde00` | `--color-mellow-yellow` | Accent backgrounds, decorative fills in illustrations, highlight areas |
| Ocean Teal | `#16aa98` | `--color-ocean-teal` | Decorative fills, illustration elements |
| Seafoam | `#53dbc9` | `--color-seafoam` | Decorative fills, illustration elements |
| Coral Red | `#f38e84` | `--color-coral-red` | Outlined button borders, decorative strokes |
| Sunset Orange | `#f5b161` | `--color-sunset-orange` | Outlined button borders, decorative strokes |
| Indigo Violet | `#b291de` | `--color-indigo-violet` | Outlined button borders, decorative strokes |
| Lime Green | `#b3c419` | `--color-lime-green` | Outlined button borders, decorative strokes |
| Grape Purple | `#7597ee` | `--color-grape-purple` | Outlined button borders, decorative strokes |
| Cerulean Blue | `#54b4de` | `--color-cerulean-blue` | Decorative borders, illustration accents |
| Aqua Teal | `#38c1b0` | `--color-aqua-teal` | Outlined button borders, decorative strokes |
| Concrete Gray | `#84a6bc` | `--color-concrete-gray` | Outlined button borders, decorative strokes |
| Golden Rod | `#e1c427` | `--color-golden-rod` | Outlined button borders, decorative strokes |
| Blush Pink | `#ff7169` | `--color-blush-pink` | Decorative fills in illustrations |
| Pumpkin Orange | `#ff9538` | `--color-pumpkin-orange` | Decorative fills in illustrations |
| Frost Blue | `#ebf9ff` | `--color-frost-blue` | Hover states, subtle background tint for clickable areas |

## Tokens — Typography

### Aeonik Mono — Primary headings and distinct UI text. Its monospace nature provides a technical, precise, yet friendly tone. Used for all-caps headlines for impact. When used for body copy, it conveys a code-like, structured feel. · `--font-aeonik-mono`
- **Substitute:** Space Mono
- **Weights:** 300, 400, 500, 600
- **Sizes:** 11px, 12px, 14px, 16px, 18px, 20px, 24px, 32px, 40px, 56px
- **Line height:** 1.00, 1.20, 1.30, 1.40, 1.60
- **Letter spacing:** 0.02em
- **Role:** Primary headings and distinct UI text. Its monospace nature provides a technical, precise, yet friendly tone. Used for all-caps headlines for impact. When used for body copy, it conveys a code-like, structured feel.

### Inter — Body copy, navigation links, and input field text, providing high legibility and a neutral voice that balances the distinctiveness of Aeonik Mono. · `--font-inter`
- **Substitute:** system-ui
- **Weights:** 300, 400, 600, 700
- **Sizes:** 12px, 14px, 16px, 18px, 20px, 22px, 24px, 32px, 44px
- **Line height:** 1.00, 1.20, 1.30, 1.36, 1.37, 1.38, 1.40, 1.60
- **Letter spacing:** 0.02em
- **Role:** Body copy, navigation links, and input field text, providing high legibility and a neutral voice that balances the distinctiveness of Aeonik Mono.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body-sm | 14px | 1.4 | 0.28px | `--text-body-sm` |
| body | 16px | 1.4 | 0.32px | `--text-body` |
| subheading | 20px | 1.3 | 0.4px | `--text-subheading` |
| heading | 32px | 1.2 | 0.64px | `--text-heading` |
| heading-lg | 40px | 1.2 | 0.8px | `--text-heading-lg` |
| display | 56px | 1 | 1.12px | `--text-display` |

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
| 60 | 60px | `--spacing-60` |
| 64 | 64px | `--spacing-64` |
| 68 | 68px | `--spacing-68` |
| 80 | 80px | `--spacing-80` |
| 100 | 100px | `--spacing-100` |
| 120 | 120px | `--spacing-120` |
| 140 | 140px | `--spacing-140` |
| 200 | 200px | `--spacing-200` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 0px |
| inputs | 2px |
| buttons | 2px |
| default | 2px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgb(56, 56, 56) -6px 6px 0px 0px` | `--shadow-subtle` |

### Layout

- **Section gap:** 50px
- **Card padding:** 40px
- **Element gap:** 8px

## Components

### Primary Action Button
**Role:** Main call to action for conversion.

Filled button with Sky Blue background (#6fc2ff), Coal text (#000000), 2px border-radius, and generous padding of 16.5px vertically and 22px horizontally. Exhibits a subtle `-6px 6px 0px 0px` box shadow with Ink color on hover.

### Secondary Ghost Button
**Role:** Alternative or less prominent actions.

Ghost button with no background (rgba(0,0,0,0)), Ink text (#383838), and no border. Padding is implicitly 0px. Text is Aeonik Mono.

### Muted Action Button
**Role:** Buttons for less critical functions or within contextual menus.

Subtly visible button with Canvas Oat background (#f4efea), Ink text (#383838), 2px border-radius, and padding of 16.5px vertically and 22px horizontally.

### Outlined Info Card
**Role:** Clickable cards presenting information with a decorative border.

Card with Paper White background (#ffffff), 0px border-radius, and no box-shadow. Features varying colored borders (Coral Red, Sunset Orange, Aqua Teal, etc.) as visual identifiers. Content padding is dynamically determined, often 0px.

### Decorative Border Button (Neutral)
**Role:** Used for filtering or categorization, visually distinct with a colored border but neutral text.

Background is Canvas Oat (#f4efea) or Smoke Gray (#f8f8f7) with Coal (#000000) or Slate (#a1a1a1) text. Features a 2px border-radius and a 1px border in various accent colors (e.g., Sky Blue, Coral Red, Sunset Orange).

### Input Field
**Role:** Standard text input for user data.

Input field with Smoke Gray background (rgba(248,248,247,0.7)), Coal text (#000000), 2px border-radius. Padding is 16px vertically and 24px horizontally with an additional 16px to the right for an optional icon.

### Header Navigation Link
**Role:** Top navigation item with hover interaction.

Text link with Coal color (#000000) for active/hover states or Ink (#383838) for inactive. Padding is 0px directly around text, relying on layout for spacing.

## Do's and Don'ts

### Do
- Prioritize Aeonik Mono for all-caps headings and prominent UI elements to establish a technical yet friendly brand voice.
- Use Canvas Oat (#f4efea) as the primary page background for a consistent soft, light theme.
- Employ Sky Blue (#6fc2ff) exclusively for primary action buttons and clear interactive states.
- Utilize 2px border-radius for all interactive elements like buttons and input fields to maintain a slightly softened, yet defined, form.
- Introduce a variety of vivid accent colors (e.g., Coral Red, Sunset Orange) only as decorative button borders or illustration fill colors, not for text or backgrounds.
- Maintain a clear visual hierarchy by limiting shadows to a distinct '-6px 6px 0px 0px' style for button interaction, avoiding general elevation via shadows.
- Structure layout with a comfortable density, prioritizing 8px for element gaps and 50px for vertical section spacing.

### Don't
- Do not use dark backgrounds for main content areas; maintain the light theme with Canvas Oat (#f4efea) as the base.
- Avoid applying heavy drop shadows for general element elevation; reserve the distinct offset shadow for interactive feedback.
- Do not deviate from the 2px border-radius for buttons and inputs; cards should maintain a 0px radius for a sharper edge.
- Refrain from using Sky Blue (#6fc2ff) for purely decorative purposes where it does not signify interactivity or brand identity.
- Do not use the vibrant accent colors (Coral Red, Sunset Orange, etc.) for body text or large background sections; confine their use to decorative elements or button borders.
- Avoid dense typography; use Inter for body text with generous line heights to ensure readability, especially at smaller sizes.
- Do not introduce new spacing values that don't align with the 4px base unit or the established element/section gaps (8px/50px).

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas Oat | `#f4efea` | Base page background, giving a warm off-white feel. |
| 1 | Paper White | `#ffffff` | Default surface for cards, panels, and input fields, offering clean contrast. |
| 2 | Smoke Gray | `#f8f8f7` | Slightly elevated background for some component variants or subtle content divisions. |
| 3 | Frost Blue | `#ebf9ff` | Used for hover states or very light background accents, hinting at interactivity. |

## Elevation

- **Primary Action Button:** `rgb(56, 56, 56) -6px 6px 0px 0px`

## Imagery

The site uses a combination of playful, hand-drawn illustrations with a whiteboard sketch aesthetic (clouds, a duck mascot, abstract shapes) and direct product screenshots or UI mockups. Illustrations are simple, outlined, and filled with a limited palette of brand and accent colors (Sky Blue, Mellow Yellow, Blush Pink, Pumpkin Orange, etc.). Product imagery is typically clean, contained, and focuses on UI elements rather than abstract concepts. Icons are outlines with a consistent stroke weight, often in black. The overall density of imagery is balanced, serving both decorative and explanatory roles without overwhelming the text-dominant information.

## Layout

The page primarily uses a max-width contained layout, centered on the Canvas Oat background. The hero section features a centered headline over the prominent Canvas Oat. Content sections often alternate between text-dominant blocks and visual elements, sometimes forming simple two-column text-left/image-right arrangements. There are instances of horizontal text-based carousels and multi-column card grids for features or testimonials. Vertical rhythm is maintained through consistent section gaps. The navigation is a sticky top bar, providing persistent access to links and calls to action.

## Agent Prompt Guide

Quick Color Reference:
- text: #383838
- background: #f4efea
- border: #383838
- accent: #ffde00
- primary action: #6fc2ff (filled action)

Example Component Prompts:
- Create a hero section: Canvas Oat background (#f4efea). Headline 'INFRASTRUCTURE FOR ANSWERS' at 56px Aeonik Mono weight 600, #383838, letter-spacing 1.12px. Subtext at 18px Inter weight 400, #383838. Primary button 'TRY 7 DAYS FREE' with Sky Blue background (#6fc2ff), Coal text (#000000), 2px radius, 16.5px 22px padding, with a -6px 6px 0px 0px #383838 shadow on hover.
- Design a customer testimonial card: Paper White background (#ffffff), 0px radius. Use Inter 16px weight 400 for quote text, #383838. Add a small avatar image, and a 'READ MORE' link in Ink (#383838) with no background or border.
- Produce an advanced filter input: Smoke Gray background (rgba(248,248,247,0.7)), Coal text (#000000), 2px radius. Placeholder text 'Ask a question about the data...' at Inter 16px weight 400, #818181. Padding 16px vertical, 24px left, 40px right for an icon.

## Similar Brands

- **Framer** — Shares the use of a clean, light canvas with a focus on distinct, playful typography for headings and a reserved use of accent colors for interaction.
- **Linear** — Similar in its compact typography, minimal approach to borders and shadows, and a strong reliance on a light, neutral background with a single dominant accent color for key actions.
- **Vercel** — Exhibits a comparable blend of technical aesthetics with a clean, functional UI, featuring subtle use of color and precise typographic choices.
- **DuckDB** — As a related project, it naturally shares a similar visual language, particularly in its minimalist approach to UI and emphasis on direct, clear communication.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-oat: #f4efea;
  --color-paper-white: #ffffff;
  --color-smoke-gray: #f8f8f7;
  --color-ink: #383838;
  --color-coal: #000000;
  --color-slate: #818181;
  --color-sky-blue: #6fc2ff;
  --color-mellow-yellow: #ffde00;
  --color-ocean-teal: #16aa98;
  --color-seafoam: #53dbc9;
  --color-coral-red: #f38e84;
  --color-sunset-orange: #f5b161;
  --color-indigo-violet: #b291de;
  --color-lime-green: #b3c419;
  --color-grape-purple: #7597ee;
  --color-cerulean-blue: #54b4de;
  --color-aqua-teal: #38c1b0;
  --color-concrete-gray: #84a6bc;
  --color-golden-rod: #e1c427;
  --color-blush-pink: #ff7169;
  --color-pumpkin-orange: #ff9538;
  --color-frost-blue: #ebf9ff;

  /* Typography — Font Families */
  --font-aeonik-mono: 'Aeonik Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-sm: 14px;
  --leading-body-sm: 1.4;
  --tracking-body-sm: 0.28px;
  --text-body: 16px;
  --leading-body: 1.4;
  --tracking-body: 0.32px;
  --text-subheading: 20px;
  --leading-subheading: 1.3;
  --tracking-subheading: 0.4px;
  --text-heading: 32px;
  --leading-heading: 1.2;
  --tracking-heading: 0.64px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: 0.8px;
  --text-display: 56px;
  --leading-display: 1;
  --tracking-display: 1.12px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

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
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-68: 68px;
  --spacing-80: 80px;
  --spacing-100: 100px;
  --spacing-120: 120px;
  --spacing-140: 140px;
  --spacing-200: 200px;

  /* Layout */
  --section-gap: 50px;
  --card-padding: 40px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-sm: 2px;

  /* Named Radii */
  --radius-cards: 0px;
  --radius-inputs: 2px;
  --radius-buttons: 2px;
  --radius-default: 2px;

  /* Shadows */
  --shadow-subtle: rgb(56, 56, 56) -6px 6px 0px 0px;

  /* Surfaces */
  --surface-canvas-oat: #f4efea;
  --surface-paper-white: #ffffff;
  --surface-smoke-gray: #f8f8f7;
  --surface-frost-blue: #ebf9ff;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-oat: #f4efea;
  --color-paper-white: #ffffff;
  --color-smoke-gray: #f8f8f7;
  --color-ink: #383838;
  --color-coal: #000000;
  --color-slate: #818181;
  --color-sky-blue: #6fc2ff;
  --color-mellow-yellow: #ffde00;
  --color-ocean-teal: #16aa98;
  --color-seafoam: #53dbc9;
  --color-coral-red: #f38e84;
  --color-sunset-orange: #f5b161;
  --color-indigo-violet: #b291de;
  --color-lime-green: #b3c419;
  --color-grape-purple: #7597ee;
  --color-cerulean-blue: #54b4de;
  --color-aqua-teal: #38c1b0;
  --color-concrete-gray: #84a6bc;
  --color-golden-rod: #e1c427;
  --color-blush-pink: #ff7169;
  --color-pumpkin-orange: #ff9538;
  --color-frost-blue: #ebf9ff;

  /* Typography */
  --font-aeonik-mono: 'Aeonik Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-sm: 14px;
  --leading-body-sm: 1.4;
  --tracking-body-sm: 0.28px;
  --text-body: 16px;
  --leading-body: 1.4;
  --tracking-body: 0.32px;
  --text-subheading: 20px;
  --leading-subheading: 1.3;
  --tracking-subheading: 0.4px;
  --text-heading: 32px;
  --leading-heading: 1.2;
  --tracking-heading: 0.64px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: 0.8px;
  --text-display: 56px;
  --leading-display: 1;
  --tracking-display: 1.12px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-68: 68px;
  --spacing-80: 80px;
  --spacing-100: 100px;
  --spacing-120: 120px;
  --spacing-140: 140px;
  --spacing-200: 200px;

  /* Border Radius */
  --radius-sm: 2px;

  /* Shadows */
  --shadow-subtle: rgb(56, 56, 56) -6px 6px 0px 0px;
}
```

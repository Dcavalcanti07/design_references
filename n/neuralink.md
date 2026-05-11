# Neuralink — Style Reference
> Deep void to soft textured canvas

**Theme:** dark

Neuralink's design system uses a high-contrast dark-to-light progression, transitioning from a deep void to soft, textured surfaces. Typography is minimal and precise, focusing on clear communication over decorative flair. Interactive elements feature soft, large radii, creating an approachable feel within the clinical and technical context. The system relies on a restrained palette, where shifts in background color delicately delineate sections.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Void | `#000000` | `--color-midnight-void` | Primary background for hero and prominent sections, primary text color, button borders, subtle surface backgrounds |
| Canvas White | `#ffffff` | `--color-canvas-white` | Primary text color on dark backgrounds, interactive element backgrounds, borders for ghost buttons |
| Soft Linen | `#f5f5f5` | `--color-soft-linen` | Light background for secondary sections and footer, providing a subtle texture |
| Ash Gray | `#bababa` | `--color-ash-gray` | Muted text, inactive navigation items, subtle borders |
| Neural Gradient | `linear-gradient(90deg, rgb(228, 134, 171), rgb(127, 128, 179) 20%, rgb(67, 90, 147) 50%, rgb(100, 82, 216) 95%)` | `--color-neural-gradient` | Decorative header banner background, infusing a scientific yet artistic blend of interconnected hues |

## Tokens — Typography

### UntitledSans — All textual content, from headings to body text and navigation. Its custom nature provides a distinct, clean, and modern feel, balancing clinical precision with approachability. · `--font-untitledsans`
- **Substitute:** System UI (sans-serif)
- **Weights:** 300, 400, 500, 700
- **Sizes:** 8px, 12px, 14px, 16px, 17px, 18px, 24px, 32px, 44px, 48px
- **Line height:** 1.00, 1.15, 1.20, 1.50
- **Letter spacing:** -0.165, -0.06, -0.05, -0.037, -0.03, -0.03, -0.02, -0.015, -0.015, -0.015
- **Role:** All textual content, from headings to body text and navigation. Its custom nature provides a distinct, clean, and modern feel, balancing clinical precision with approachability.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body-sm | 14px | 1.5 | -0.05px | `--text-body-sm` |
| body | 16px | 1.5 | -0.037px | `--text-body` |
| body-lg | 18px | 1.5 | -0.03px | `--text-body-lg` |
| subheading | 24px | 1.2 | -0.02px | `--text-subheading` |
| heading | 32px | 1.15 | -0.015px | `--text-heading` |
| display-sm | 44px | 1.15 | -0.015px | `--text-display-sm` |
| display | 48px | 1 | -0.015px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 5 | 5px | `--spacing-5` |
| 6 | 6px | `--spacing-6` |
| 8 | 8px | `--spacing-8` |
| 12 | 12px | `--spacing-12` |
| 16 | 16px | `--spacing-16` |
| 18 | 18px | `--spacing-18` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 30 | 30px | `--spacing-30` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 46 | 46px | `--spacing-46` |
| 50 | 50px | `--spacing-50` |
| 60 | 60px | `--spacing-60` |
| 240 | 240px | `--spacing-240` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 20px |
| buttons | 80px |
| circular | 50% |
| navItems | 16px |

### Layout

- **Section gap:** 50px
- **Card padding:** 12px
- **Element gap:** 12px

## Components

### Primary Call to Action Button
**Role:** Informative action button

Filled button with a large radius (80px), Canvas White background, and Midnight Void text. Padding is generous at 16px vertical, 24px horizontal. Used for primary user journeys.

### Ghost Button (Dark)
**Role:** Secondary action on dark backgrounds

Outlined button with a transparent background, Midnight Void border (1px), and Canvas White text on dark canvas. Large radius of 80px, with 16px vertical, 24px horizontal padding.

### Ghost Button (Light)
**Role:** Secondary action on light backgrounds

Outlined button with a transparent background, Canvas White border (1px), and Midnight Void text on light canvas. Often used for navigation, with a 50% radius for minimal visual weight and 1px vertical, 6px horizontal padding.

### Info Banner
**Role:** Top-level informational message

Full-width banner at the top of the page, using the Neural Gradient background with Canvas White text. Provides a clear, yet subtle announcement area.

### Navigation Link
**Role:** Main navigation item

Text link on the navigation bar, typically in Midnight Void or Canvas White depending on background. Inherits typography settings. Active state might show a subtle border.

### Pioneer Profile Card
**Role:** Displaying relevant profiles or opportunities

Cards with a 20px radius, varying subtly in background (often Soft Linen or transparent) to feature imagery. Contains a ghost button for further interaction.

## Do's and Don'ts

### Do
- Use Midnight Void (#000000) for hero backgrounds and primary text to establish high contrast.
- Employ Canvas White (#ffffff) for primary interactive element backgrounds and key text on dark backgrounds.
- Apply Soft Linen (#f5f5f5) as the background for most content sections to provide a subtle texture contrast to the dark hero.
- All buttons must use an 80px border-radius for a distinct, soft pill shape.
- Maintain comfortable density with 12px element-gap between components and 50px section-gap between major content blocks.
- Utilize UntitledSans for all type, with variable letter-spacing as defined in the typography section, to ensure precise visual rhythm.
- Implement the Neural Gradient for the top informational banner, creating a unique brand signature without relying on saturated brand colors elsewhere.

### Don't
- Do not introduce additional saturated colors beyond the Neural Gradient; maintain the achromatic base palette.
- Avoid generic rectangular buttons; all buttons should adhere to the 80px radius for a consistent pill aesthetic.
- Do not use heavy shadows or excessive elevation; the design relies on changes in background color and subtle borders for depth.
- Refrain from using Ash Gray (#bababa) for critical text or active states; reserve it for muted, secondary information.
- Do not break the established typographic scale; maintain semantic roles and their associated sizes and letter-spacing values from the typeScale.
- Avoid compact layouts; prioritize comfortable spacing with 12px element gaps and 50px section gaps.
- Do not use generic system fonts; the custom UntitledSans is fundamental to the brand's quiet, precise tone.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Midnight Void Canvas | `#000000` | Base background for hero sections and dark content areas, creating a deep, immersive feel. |
| 1 | Soft Linen Canvas | `#f5f5f5` | Secondary background for most content sections, providing a light, slightly textured contrast. |
| 2 | Component Surface | `#ffffff` | Background for interactive elements and prominent cards, standing out against the Soft Linen canvas. |

## Imagery

Imagery primarily features people (portraits, profiles) or abstract scientific visualizations, often integrated with a duotone or gradient overlay (similar to the Neural Gradient) that blends with the site's palette. Photos are often contained within soft-edged shapes (20px-60px radius) rather than hard crops. Icons are minimal, outlined, and monochromatic, matching the surrounding text color. The role of imagery is a blend of inspirational (people) and explanatory (visualizing complex ideas), maintaining a high-fidelity and slightly conceptual aesthetic.

## Layout

The page transitions from a full-bleed dark hero with a prominent centered headline to a contained, variable-width content area. Sections alternate between Midnight Void for key messages and Soft Linen for detailed content, creating a distinct visual rhythm. Most content uses a max-width container, appearing centered. Content arrangement often features a split layout (text left, image right or vice versa) or stacked information blocks. Navigation is a sticky top bar, minimal and integrating a subtle Ghost Button.

## Agent Prompt Guide

**Quick Color Reference:**
text: #ffffff (hero), #000000 (light sections)
background: #000000 (hero), #f5f5f5 (content)
border: #ffffff (light on dark), #000000 (dark on light)
accent: #e486ab (gradient start)
primary action: no distinct CTA color

**3-5 Example Component Prompts:**
No distinct primary action color was observed; use the extracted neutral button treatments instead of inventing a filled CTA color.
2. Design a content section: Soft Linen background (#f5f5f5). Subheading 'Meet our pioneers' using UntitledSans at 32px, weight 500, Midnight Void (#000000), letter-spacing -0.015em. Use 50px section-gap below.
3. Build a navigation bar: Sticky top bar with a Neural Gradient (#e486ab) background for an info banner, followed by a transparent navigation layer with Canvas White (#ffffff) links (e.g., 'Technology', 'Careers') using UntitledSans 16px weight 400. Include a Ghost Button (Light) for 'Clinical Trials' with 50% radius, 1px Canvas White border, 1px 6px padding.
4. Create a Pioneer Profile Card: 20px radius, Soft Linen (#f5f5f5) background, with a duotone image. Text 'Patients & Caregivers' using UntitledSans 24px weight 500, Midnight Void (#000000). Include a Ghost Button (Dark) 'Learn about clinical trials': transparent background, 1px Midnight Void border, Canvas White text, 80px radius, 16px 24px padding.

## Similar Brands

- **OpenAI** — High-contrast dark-mode initial impressions with clean, authoritative sans-serif typography.
- **Stripe** — Minimalist aesthetic focusing on clear information hierarchy, subtle background texture shifts, and precise type details.
- **Apple** — Premium feel through restrained, achromatic palettes, subtle surfacing, and emphasis on product presentation.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-void: #000000;
  --color-canvas-white: #ffffff;
  --color-soft-linen: #f5f5f5;
  --color-ash-gray: #bababa;
  --color-neural-gradient: #e486ab;
  --gradient-neural-gradient: linear-gradient(90deg, rgb(228, 134, 171), rgb(127, 128, 179) 20%, rgb(67, 90, 147) 50%, rgb(100, 82, 216) 95%);

  /* Typography — Font Families */
  --font-untitledsans: 'UntitledSans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --tracking-body-sm: -0.05px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.037px;
  --text-body-lg: 18px;
  --leading-body-lg: 1.5;
  --tracking-body-lg: -0.03px;
  --text-subheading: 24px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.02px;
  --text-heading: 32px;
  --leading-heading: 1.15;
  --tracking-heading: -0.015px;
  --text-display-sm: 44px;
  --leading-display-sm: 1.15;
  --tracking-display-sm: -0.015px;
  --text-display: 48px;
  --leading-display: 1;
  --tracking-display: -0.015px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-18: 18px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-30: 30px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-46: 46px;
  --spacing-50: 50px;
  --spacing-60: 60px;
  --spacing-240: 240px;

  /* Layout */
  --section-gap: 50px;
  --card-padding: 12px;
  --element-gap: 12px;

  /* Border Radius */
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-full: 60px;
  --radius-full-2: 80px;

  /* Named Radii */
  --radius-cards: 20px;
  --radius-buttons: 80px;
  --radius-circular: 50%;
  --radius-navitems: 16px;

  /* Surfaces */
  --surface-midnight-void-canvas: #000000;
  --surface-soft-linen-canvas: #f5f5f5;
  --surface-component-surface: #ffffff;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-void: #000000;
  --color-canvas-white: #ffffff;
  --color-soft-linen: #f5f5f5;
  --color-ash-gray: #bababa;
  --color-neural-gradient: #e486ab;

  /* Typography */
  --font-untitledsans: 'UntitledSans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --tracking-body-sm: -0.05px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.037px;
  --text-body-lg: 18px;
  --leading-body-lg: 1.5;
  --tracking-body-lg: -0.03px;
  --text-subheading: 24px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.02px;
  --text-heading: 32px;
  --leading-heading: 1.15;
  --tracking-heading: -0.015px;
  --text-display-sm: 44px;
  --leading-display-sm: 1.15;
  --tracking-display-sm: -0.015px;
  --text-display: 48px;
  --leading-display: 1;
  --tracking-display: -0.015px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-18: 18px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-30: 30px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-46: 46px;
  --spacing-50: 50px;
  --spacing-60: 60px;
  --spacing-240: 240px;

  /* Border Radius */
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-full: 60px;
  --radius-full-2: 80px;
}
```

# Atlantic.vc — Style Reference
> Midnight Command Center: Deep black canvas with glowing blue readouts and precise data points.

**Theme:** dark

Atlantic presents a stark, high-contrast dark theme, creating an atmosphere of technological precision and speculative innovation. A deep black canvas serves as the foundation, punctuated by crisp, light text and vibrant blue accents that highlight key information and interactive elements. Typography is bold and unconventional, employing a monospace aesthetic for structure and an impactful custom sans-serif for headlines, reinforced by precise letter-spacing. UI components are minimal, favoring delicate outlines and subtle background fills over heavy ornamentation, maintaining focus on content and interaction.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Deep Midnight | `#000000` | `--color-deep-midnight` | Page background, primary surface for immersive content sections. Emphasizes depth and focus |
| Charcoal Canvas | `#0d0d0f` | `--color-charcoal-canvas` | Subtle background for card elements, providing a minimal lift from Deep Midnight |
| Graphite Base | `#232529` | `--color-graphite-base` | Background color for selected body sections |
| Cool Stone | `#2b2f33` | `--color-cool-stone` | Card backgrounds, slightly lighter than other surfaces to denote distinct content blocks |
| Ghost Ink | `#d8eaff` | `--color-ghost-ink` | Primary text color, link text, navigation items, and outlined button/link borders. Creates high contrast against dark backgrounds |
| Muted Ash | `#6c757f` | `--color-muted-ash` | Secondary text for subtle information, helper text, and neutral link borders |
| Subtle Grey | `#565e66` | `--color-subtle-grey` | Decorative borders and less prominent body text |
| Pale Slate | `#565657` | `--color-pale-slate` | Dark borders and separators for elevated surfaces and inverted UI. Do not promote it to the primary CTA color |
| Electric Blue | `#1f58f2` | `--color-electric-blue` | Violet wash for highlight backgrounds, decorative bands, and soft emphasis behind content. Do not promote it to the primary CTA color |
| Ignition Orange | `#ff4105` | `--color-ignition-orange` | Orange outline accent for tags, dividers, and focused UI edges. Do not promote it to the primary CTA color |

## Tokens — Typography

### Monument — Primary display font for headlines, navigation, and prominent textual elements. Its strong presence with varying negative letter-spacing contributes to the distinct, commanding voice of the brand. · `--font-monument`
- **Substitute:** Montserrat
- **Weights:** 400
- **Sizes:** 10px, 16px, 24px, 64px, 96px
- **Line height:** 1.00, 1.06, 1.24, 1.46, 1.50
- **Letter spacing:** -0.0300em (at 64px, 96px), -0.0100em (at 24px, 16px, 10px)
- **Role:** Primary display font for headlines, navigation, and prominent textual elements. Its strong presence with varying negative letter-spacing contributes to the distinct, commanding voice of the brand.

### Mono — Monospace font for body text, descriptive labels, and code-like elements. Its generous letter-spacing enhances readability on dark backgrounds and reinforces a technical, precise aesthetic. · `--font-mono`
- **Substitute:** Space Mono
- **Weights:** 400
- **Sizes:** 10px, 12px, 14px
- **Line height:** 0.80, 1.00, 1.50
- **Letter spacing:** 0.0600em (at 10px, 12px, 14px), 0.1600em (at 10px)
- **Role:** Monospace font for body text, descriptive labels, and code-like elements. Its generous letter-spacing enhances readability on dark backgrounds and reinforces a technical, precise aesthetic.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 0.8 | 0.16px | `--text-caption` |
| body | 14px | 1.5 | 0.06px | `--text-body` |
| heading | 24px | 1.24 | -0.01px | `--text-heading` |
| heading-lg | 64px | 1.46 | -0.03px | `--text-heading-lg` |
| display | 96px | 1.5 | -0.03px | `--text-display` |

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
| 80 | 80px | `--spacing-80` |
| 100 | 100px | `--spacing-100` |
| 148 | 148px | `--spacing-148` |
| 200 | 200px | `--spacing-200` |
| 240 | 240px | `--spacing-240` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 16px |
| links | 8px |
| buttons | 0px |

### Layout

- **Section gap:** 50px
- **Card padding:** 24px
- **Element gap:** 16px

## Components

### Ghost Navigation Link
**Role:** Transparent link for header navigation and secondary actions.

Text: Monument 400, Ghost Ink (#d8eaff). Background: rgba(0,0,0,0). Border: 0px. Radius: 0px.

### Outlined Action Button
**Role:** Call-to-action button, visually distinct due to border.

Background: rgba(0,0,0,0). Text: Ghost Ink (#d8eaff). Border: 1px Ghost Ink (#d8eaff) solid. Radius: 0px. Padding: 0px.

### Text Accent Button
**Role:** Button with an accent color on text.

Text: Ignition Orange (#ff4105) (primarily for action states, icon fill). Font: Monument. Background: rgba(0,0,0,0). Radius: 0px. Padding: 0px.

### Standard Card
**Role:** Container for content sections.

Background: Cool Stone (#2b2f33) or Charcoal Canvas (#0d0d0f). Border: none. Radius: 16px. Padding: minimal, often 0px, content provides internal spacing.

### Hero Large Card
**Role:** Prominent card for hero sections or significant content blocks.

Background: Charcoal Canvas (#0d0d0f). Border: none. Radius: 24px. Padding: 150px top/bottom, 110px left/right.

## Do's and Don'ts

### Do
- Always use a dark background, preferring Deep Midnight (#000000) or Charcoal Canvas (#0d0d0f) for surfaces that need to recede, and Cool Stone (#2b2f33) for slightly elevated cards.
- Prioritize Ghost Ink (#d8eaff) for primary text and interactive elements to ensure maximum contrast and legibility on dark backgrounds.
- Use Electric Blue (#1f58f2) for highlighting key terms within headlines, interactive states, and small decorative features to draw attention.
- Employ the Monument font for all display and navigation text, applying the specified negative letter-spacing for a sophisticated, commanding feel.
- Utilize the Mono font for body copy, ensuring generous letter-spacing to optimize readability in small sizes on dark backgrounds.
- Maintain a minimalistic aesthetic for interactive components, favoring outlined styles with Ghost Ink (#d8eaff) borders over solid fills.
- Apply 16px border-radius to standard cards to provide subtle softness to content blocks, and 24px for larger, more prominent cards.

### Don't
- Avoid using light backgrounds, as the system is built for a dark mode, and light elements are reserved for foreground content or specific accents.
- Do not introduce additional bold colors beyond Electric Blue (#1f58f2) and Ignition Orange (#ff4105) for interactive elements; color use should be minimal and functional.
- Refrain from heavy drop shadows or excessive elevation; the design relies on subtle background differences and crisp outlines for visual hierarchy.
- Do not deviate from the specified letter-spacing values for Monument and Mono fonts; they are critical for maintaining the typographical character.
- Avoid large, filled buttons; all primary Calls to Action should be ghost or outlined buttons with text in Ghost Ink (#d8eaff) or Ignition Orange (#ff4105).
- Do not use generic border radii; adhere to 0px for buttons and navigation, 8px for links, and 16px/24px for cards.
- Avoid using a page-level maximum width; the content should either be full-bleed or rely on generous inner padding and component widths.

## Imagery

Imagery primarily features product/tech-focused visuals (e.g., logos of companies) or abstract digital noise patterns, often in shades of blue. When present, images are contained within card-like structures or sections, maintaining clear boundaries. Photography for people (e.g., team members) is high-key, slightly desaturated, and tightly cropped headshots, presented within structured grid elements. Icons are minimal, outlined, and often utilize the Electric Blue or Ignition Orange accent colors, serving as functional or small decorative elements without heavy visual weight.

## Layout

The page employs a full-bleed layout, particularly in the hero section, with a dominant dark background creating an immersive experience. Content typically centers horizontally within implied columns but lacks a strict page-level max-width. The hero section features a large, centered headline over a dynamic, abstract background. Section rhythm is fluid with generous vertical spacing (approx. 50px-100px gaps) and alternating content arrangements, including centered text stacks, and horizontal scrolling grids for companies. Navigation is a sticky top bar with minimal links and an accent-colored call-to-action button, ensuring consistent access.

## Agent Prompt Guide

Quick Color Reference:
text: #d8eaff
background: #000000
border: #d8eaff
accent: #1f58f2
primary action: no distinct CTA color

Example Component Prompts:
1. Create a primary hero section: Deep Midnight background (#000000). Headline 'Building Tomorrow, Today' in Monument 96px, letter-spacing -0.03em, Ghost Ink (#d8eaff). Subtitle 'We empower visionaries' in Mono 14px, letter-spacing 0.06em, Muted Ash (#6c757f). Centered content.
2. Create an outlined button for navigation: 'Discover More' text, Monument 16px, Ghost Ink (#d8eaff). Background transparent. Border 1px solid Ghost Ink (#d8eaff). Radius 0px. Padding 0px.
3. Create a Standard Card: Background Cool Stone (#2b2f33), Radius 16px. Inside, place a heading 'Our Approach' in Monument 24px, Ghost Ink (#d8eaff) and a body text paragraph in Mono 14px, Muted Ash (#6c757f).
4. Create a small text link: 'Read Blog Post' in Mono 14px, Electric Blue (#1f58f2). No background, no border, no radius. Underline on hover.

## Similar Brands

- **Stripe** — Shares a sophisticated dark-mode UI with sharp typography, minimal component styling, and strategic use of a single vibrant accent color for highlights.
- **Linear** — Exhibits a similar focus on high contrast dark theme, precise typography with unique letter-spacing, and functional, understated UI elements to emphasize data and content.
- **Vercel** — Employs a deep dark background, crisp white sans-serif typography, and a preference for ghost or outlined buttons for interactive elements, contributing to a modern tech aesthetic.
- **Supabase** — Features a dark interface with contrasting text, monospace fonts for technical content, and relies on subtle accent colors for brand identity rather than heavy gradients or imagery.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-deep-midnight: #000000;
  --color-charcoal-canvas: #0d0d0f;
  --color-graphite-base: #232529;
  --color-cool-stone: #2b2f33;
  --color-ghost-ink: #d8eaff;
  --color-muted-ash: #6c757f;
  --color-subtle-grey: #565e66;
  --color-pale-slate: #565657;
  --color-electric-blue: #1f58f2;
  --color-ignition-orange: #ff4105;

  /* Typography — Font Families */
  --font-monument: 'Monument', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-mono: 'Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 0.8;
  --tracking-caption: 0.16px;
  --text-body: 14px;
  --leading-body: 1.5;
  --tracking-body: 0.06px;
  --text-heading: 24px;
  --leading-heading: 1.24;
  --tracking-heading: -0.01px;
  --text-heading-lg: 64px;
  --leading-heading-lg: 1.46;
  --tracking-heading-lg: -0.03px;
  --text-display: 96px;
  --leading-display: 1.5;
  --tracking-display: -0.03px;

  /* Typography — Weights */
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-80: 80px;
  --spacing-100: 100px;
  --spacing-148: 148px;
  --spacing-200: 200px;
  --spacing-240: 240px;

  /* Layout */
  --section-gap: 50px;
  --card-padding: 24px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-3xl-2: 40.798px;

  /* Named Radii */
  --radius-cards: 16px;
  --radius-links: 8px;
  --radius-buttons: 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-deep-midnight: #000000;
  --color-charcoal-canvas: #0d0d0f;
  --color-graphite-base: #232529;
  --color-cool-stone: #2b2f33;
  --color-ghost-ink: #d8eaff;
  --color-muted-ash: #6c757f;
  --color-subtle-grey: #565e66;
  --color-pale-slate: #565657;
  --color-electric-blue: #1f58f2;
  --color-ignition-orange: #ff4105;

  /* Typography */
  --font-monument: 'Monument', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-mono: 'Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 0.8;
  --tracking-caption: 0.16px;
  --text-body: 14px;
  --leading-body: 1.5;
  --tracking-body: 0.06px;
  --text-heading: 24px;
  --leading-heading: 1.24;
  --tracking-heading: -0.01px;
  --text-heading-lg: 64px;
  --leading-heading-lg: 1.46;
  --tracking-heading-lg: -0.03px;
  --text-display: 96px;
  --leading-display: 1.5;
  --tracking-display: -0.03px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-80: 80px;
  --spacing-100: 100px;
  --spacing-148: 148px;
  --spacing-200: 200px;
  --spacing-240: 240px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-3xl-2: 40.798px;
}
```

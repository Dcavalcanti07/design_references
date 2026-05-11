# David Kirschberg — Style Reference
> Minimalist Dark Canvas — bold text on deep charcoal.

**Theme:** dark

Kirschberg employs a sparse, high-contrast dark mode aesthetic, reminiscent of a command-line interface. The design prioritizes content with minimal chrome, using stark white typography against deep charcoal backgrounds. Surface differentiation is achieved through subtle shifts in background tone and rounded containers, rather than heavy shadows. The overall impression is one of restrained confidence and directness.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Core | `#181818` | `--color-midnight-core` | Page backgrounds, primary container backgrounds |
| Frost White | `#fafafa` | `--color-frost-white` | Primary text, active button borders, accent strokes |
| Slate Surface | `#262626` | `--color-slate-surface` | Elevated card backgrounds, distinct interface panels |
| Ash Muted | `#a3a3a3` | `--color-ash-muted` | Secondary text, helper text, inactive elements |
| Ghost Border | `#ffffff14` | `--color-ghost-border` | Subtle hair-thin borders for separating content without strong visual breaks |

## Tokens — Typography

### Inter — Body text, button labels, navigation links, and descriptive content. Its standard weight provides legibility against the dark background. · `--font-inter`
- **Substitute:** system-ui
- **Weights:** 400
- **Sizes:** 16px, 17px
- **Line height:** 1.18, 1.29, 1.50
- **Letter spacing:** -0.0090em
- **Role:** Body text, button labels, navigation links, and descriptive content. Its standard weight provides legibility against the dark background.

### twkLausanne — Primary headings. Its broad letter-spacing and substantial size give it a commanding presence that anchors sections. · `--font-twklausanne`
- **Substitute:** Arial
- **Weights:** 400
- **Sizes:** 32px
- **Line height:** 1.10
- **Letter spacing:** -0.0400em
- **Role:** Primary headings. Its broad letter-spacing and substantial size give it a commanding presence that anchors sections.

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 8 | 8px | `--spacing-8` |
| 12 | 12px | `--spacing-12` |
| 16 | 16px | `--spacing-16` |
| 24 | 24px | `--spacing-24` |

### Border Radius

| Element | Value |
|---------|-------|
| default | 16px |
| surfaces | 24px |

### Layout

- **Section gap:** 45px
- **Card padding:** 16px
- **Element gap:** 8px

## Components

### Ghost Button
**Role:** Interactive elements with minimal visual weight.

Background transparent (rgba(0, 0, 0, 0)), text and border in Frost White (#fafafa). Padding 4px on all sides. Radius 0px. Used for navigation and primary content links.

### Work Item Card
**Role:** Cards for showcasing portfolio pieces.

Background is Midnight Core (#181818). Rounded corners at 24px create a soft, contained feel. Text uses Inter 16px Frost White (#fafafa) for titles and Ash Muted (#a3a3a3) for descriptions.

### Navigation Bar
**Role:** Sticky header for site navigation.

Background in Midnight Core (#181818), with a top padding of 16px and bottom padding of 16px. Contains a Ghost Button for the brand name and a hamburger icon for menu.

## Do's and Don'ts

### Do
- Prioritize Frost White (#fafafa) for all primary text and active states against dark backgrounds.
- Use Midnight Core (#181818) as the default background for pages and main content blocks.
- Elevate content visually by applying Slate Surface (#262626) for distinct cards or panels.
- Utilize 'twkLausanne' at 32px with -0.0400em letter-spacing for all significant headings to establish brand presence.
- Apply a generous border-radius of 24px to main surface containers for a soft, modern shape.
- Ensure a horizontal element gap of 8px for consistent spacing between interactive elements or grid items.
- Maintain a clear vertical rhythm with section gaps of 45px between major content blocks.

### Don't
- Avoid the use of strong accent colors; the system relies on high-contrast neutrals.
- Do not introduce visible drop shadows; surface changes are conveyed via background color shifts.
- Refrain from using bold or heavy font weights; Inter 400 and twkLausanne 400 are the established textual weights.
- Do not use rectangular or sharp-edged components; all primary containers should feature a minimum 16px radius.
- Avoid cluttering backgrounds with patterns or textures; surfaces should remain flat and monochromatic.
- Do not deviate from the established letter-spacing values like -0.0400em for headings; they are critical for the typographic identity.
- Avoid tight vertical spacing in sections; ensure adequate 45px separation between content blocks.

## Imagery

This site features a mix of abstract digital illustrations and product screenshots. The illustrations are vibrant, organic, and utilize a high-contrast color palette, standing out against the dark UI. Product screenshots are typically centered or contained within card-like structures. Icons, when present, are minimal and serve functional navigation purposes. Imagery serves primarily as decorative atmosphere and to showcase work, occupying significant visual space within structured grid layouts.

## Agent Prompt Guide

Quick Color Reference:
text: #fafafa
background: #181818
border: #ffffff14
accent: no distinct accent color
primary action: no distinct CTA color

Example Component Prompts:
1. Create a page hero: Midnight Core (#181818) background. Headline 'twkLausanne' 32px weight 400, #fafafa, letter-spacing -0.0400em. Subtext 'Inter' 17px weight 400, #fafafa.
2. Design a Ghost Navigation Button: Background rgba(0, 0, 0, 0), text #fafafa (Inter 16px weight 400), border #fafafa, 4px padding, 0px radius.
3. Build a Work Item Card: Slate Surface (#262626) background, 24px radius. Content title 'Inter' 16px weight 400, #fafafa. Description 'Inter' 16px weight 400, #a3a3a3. Place an image inside the card.

## Similar Brands

- **Linear** — Uses a dark theme with high-contrast text and minimal UI elements, focusing on content.
- **Github** — Offers a dark mode with similar deep charcoal neutrals and strong text contrast, emphasizing code and content.
- **Blinkist** — Features a clean, typography-focused dark mode with subtle background variations for surface distinction.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-core: #181818;
  --color-frost-white: #fafafa;
  --color-slate-surface: #262626;
  --color-ash-muted: #a3a3a3;
  --color-ghost-border: #ffffff14;

  /* Typography — Font Families */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-twklausanne: 'twkLausanne', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-base: 16px;
  --leading-base: 1.5;
  --text-lg: 17px;
  --leading-lg: 1.18;
  --text-3xl: 32px;
  --leading-3xl: 1.1;

  /* Typography — Weights */
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-24: 24px;

  /* Layout */
  --section-gap: 45px;
  --card-padding: 16px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-2xl: 16px;
  --radius-3xl: 24px;

  /* Named Radii */
  --radius-default: 16px;
  --radius-surfaces: 24px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-core: #181818;
  --color-frost-white: #fafafa;
  --color-slate-surface: #262626;
  --color-ash-muted: #a3a3a3;
  --color-ghost-border: #ffffff14;

  /* Typography */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-twklausanne: 'twkLausanne', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-base: 16px;
  --leading-base: 1.5;
  --text-lg: 17px;
  --leading-lg: 1.18;
  --text-3xl: 32px;
  --leading-3xl: 1.1;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-24: 24px;

  /* Border Radius */
  --radius-2xl: 16px;
  --radius-3xl: 24px;
}
```

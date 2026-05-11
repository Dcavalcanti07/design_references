# Tana — Style Reference
> infinite dark canvas

**Theme:** dark

Tana cultivates a focused, dark-canvas experience where content takes center stage, punctuated by a single soft green accent for interaction. The design emphasizes clear information hierarchy through careful typographic choices and ample negative space. Components are lightweight with subtle borders that emerge from the dark background, maintaining a high contrast and serious tone despite the single approachable accent color. The overall impression is one of calm, concentrated work.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Deep Midnight | `#000000` | `--color-deep-midnight` | Dark borders and separators for elevated surfaces and inverted UI. Do not promote it to the primary CTA color |
| Cloud Whisper | `#f0eded` | `--color-cloud-whisper` | Hairline borders, dividers, input outlines, and card edges on light surfaces. Do not promote it to the primary CTA color |
| Graphite Base | `#0e0e0e` | `--color-graphite-base` | Secondary background, subtle surface separation, borders |
| Muted Silver | `#b3b3b3` | `--color-muted-silver` | Secondary text for body copy and supporting information, list item borders |
| Stone Gray | `#808080` | `--color-stone-gray` | Tertiary text for citations and fine print, subtle decorative borders |
| Soft Ash | `#606060` | `--color-soft-ash` | Lowest contrast text for disclaimers and meta-information |
| Lush Meadow | `#e1f0bd` | `--color-lush-meadow` | Primary action button background, interactive highlights — a soft, muted green that signals progression without harshness |

## Tokens — Typography

### SF Pro — General body text, navigation elements, button labels, and secondary headings. Its consistent, legible structure supports dense information on a dark background. · `--font-sf-pro`
- **Substitute:** system-ui
- **Weights:** 300, 400
- **Sizes:** 13px, 15px, 16px, 17px, 18px, 19px, 20px, 21px, 24px, 26px, 29px
- **Line height:** 1.20, 1.40, 1.50, 1.75
- **Letter spacing:** 0.0100em
- **Role:** General body text, navigation elements, button labels, and secondary headings. Its consistent, legible structure supports dense information on a dark background.

### tanaClassic — Display headlines and prominent section titles. The custom serif typeface provides a literary, classic feel, while the tight negative letter-spacing for larger sizes enhances its distinctiveness and compact impact. · `--font-tanaclassic`
- **Substitute:** serif
- **Weights:** 350, 400
- **Sizes:** 17px, 19px, 38px, 42px, 48px, 84px
- **Line height:** 1.10, 1.20, 1.25, 1.75
- **Letter spacing:** -0.0450em at 84px, -0.0300em at 48px
- **Role:** Display headlines and prominent section titles. The custom serif typeface provides a literary, classic feel, while the tight negative letter-spacing for larger sizes enhances its distinctiveness and compact impact.

### Arial — Specific button text, providing a highly legible and functional complement to the custom headline font. · `--font-arial`
- **Substitute:** system-ui
- **Weights:** 400
- **Sizes:** 17px
- **Line height:** 1.20
- **Letter spacing:** normal
- **Role:** Specific button text, providing a highly legible and functional complement to the custom headline font.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 13px | 1.4 | — | `--text-caption` |
| body-sm | 15px | 1.4 | — | `--text-body-sm` |
| subheading | 20px | 1.25 | — | `--text-subheading` |
| heading-sm | 24px | 1.25 | — | `--text-heading-sm` |
| heading | 48px | 1.1 | -0.96px | `--text-heading` |
| display | 84px | 1.1 | -3.78px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 8 | 8px | `--spacing-8` |
| 12 | 12px | `--spacing-12` |
| 16 | 16px | `--spacing-16` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 36 | 36px | `--spacing-36` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 96 | 96px | `--spacing-96` |
| 112 | 112px | `--spacing-112` |
| 128 | 128px | `--spacing-128` |
| 160 | 160px | `--spacing-160` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 8px |
| image | 10px |
| buttons | 12px |

### Layout

- **Section gap:** 24px
- **Card padding:** 16px
- **Element gap:** 6px

## Components

### Primary Action Button
**Role:** Call to action

Filled button with a muted green background (Lush Meadow, #e1f0bd) and black text (Deep Midnight, #000000). Has a generous 12px border radius. Padding is 10px vertical, 16px horizontal.

### Ghost Outline Button (small)
**Role:** Secondary action or tag

Transparent background with a Cloud Whisper (#f0eded) border and text. Has an 8px border radius. Padding is 6px vertical, 12px horizontal.

### Ghost Text Link (minimal)
**Role:** Inline or tertiary action link

Transparent background, no visible border, with Cloud Whisper (#f0eded) text. No explicit radius or padding, blends seamlessly into copy or navigation.

### Navigation Link
**Role:** Main navigation item

Plain text link using SF Pro, Cloud Whisper (#f0eded) color, appearing primarily in headers and footers without explicit borders or background. Uses a 16px padding on the left, right of specific items.

### Hero Headline
**Role:** Prominent page title

Uses tanaClassic font, typically at 84px or 48px, with weights 350-400, and a tight letter-spacing of -0.045em to -0.03em. Color is Cloud Whisper (#f0eded) against a Deep Midnight background.

### Feature Tag Bubble
**Role:** Informational tag or categorized item

Small, rounded bubbles with 8px radius, transparent background, and a Cloud Whisper (#f0eded) border. Text color is Cloud Whisper. Padding is 6px vertical, 12px horizontal.

## Do's and Don'ts

### Do
- Prioritize Deep Midnight (#000000) for all primary background surfaces to maintain the dark canvas theme.
- Use Cloud Whisper (#f0eded) as the default text color for primary content and interactive elements against dark backgrounds.
- Apply Lush Meadow (#e1f0bd) exclusively for primary action button backgrounds and clear calls-to-action.
- Maintain a clear visual hierarchy using tanaClassic for display headings with tight letter-spacing, and SF Pro for all body text and UI elements.
- Utilize 12px border radius for all primary buttons and 8px for smaller interactive tags or ghost buttons.
- Employ a 10px vertical and 16px horizontal padding for main action buttons.
- Use Muted Silver (#b3b3b3) for secondary body copy and supporting text against Deep Midnight (#000000).

### Don't
- Avoid using bright, saturated chromatic colors outside of the defined Lush Meadow accent for primary actions.
- Do not introduce strong shadows or excessive elevation that would contradict the flat, minimalist surface treatment.
- Minimize the use of multiple border radii; stick to 12px for primary buttons, 8px for tags, and 10px for images.
- Do not apply broad letter-spacing to headings; use the specified negative tracking for tanaClassic to maintain its distinct character.
- Refrain from using background patterns or gradients, as the design relies on solid, high-contrast dark surfaces.
- Do not use SF Pro for display-level headlines; reserve tanaClassic for this role to preserve typographic identity.
- Avoid using Stone Gray (#808080) for essential body text as its contrast is intended for tertiary information only.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Deep Midnight Canvas | `#000000` | Dominant page and module background. |
| 1 | Graphite Base Layer | `#0e0e0` | Secondary background for containers or subtle section variations, borders. |

## Imagery

The site uses a mix of candid, dark-toned photography for humans in work settings and abstract graphical bubbles (like speech bubbles or connected nodes) to highlight concepts in the 'knowledge graph' section. Photography is generally desaturated, focusing on the human element and product interaction rather than vibrant colors. Icons are minimal, outlined, and monochromatic (Cloud Whisper) against the dark background. Imagery is primarily explanatory and decorative, occupying significant visual space to break up text-heavy sections, but always contained within the flow rather than full-bleed.

## Layout

The page maintains a full-bleed dark background (Deep Midnight) throughout, with content centrally aligned and implicitly max-width contained by ample horizontal padding. The hero section features a centered headline and action buttons. Subsequent sections alternate between centered text blocks and asymmetric text-left/image-right (or vice-versa) layouts. A grid of abstract 'bubbled' tags illustrates connectivity. Vertical rhythm is established by consistent section gaps of 24px creating a comfortable, unhurried density. Navigation is a minimal top-bar, visually integrated with the dark background.

## Agent Prompt Guide

### Quick Color Reference
text: #f0eded
background: #000000
border: #f0eded
accent: #e1f0bd
primary action: #e1f0bd (filled action)

### 3-5 Example Component Prompts
1. Create a Primary Action Button: #e1f0bd background, #000000 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Design a feature block: background Deep Midnight (#000000). Heading 'Tana turns meetings into' with tanaClassic, 42px, weight 400, Cloud Whisper (#f0eded), letter-spacing -1.26px. Below, a photo of a person working, 10px border-radius. Flanking the photo, 'Feature Tag Bubble' components, e.g., 'Prototypes' and 'Storyboards'.
3. Create a testimonial section: background Deep Midnight (#000000). Quotes in Muted Silver (#b3b3b3), SF Pro 20px, lineHeight 1.5. Author/source in Stone Gray (#808080), SF Pro 17px, lineHeight 1.5. Each quote block is separated by 24px sectionGap.

## Similar Brands

- **Linear** — Uses a dark theme, high contrast white text, and a single accent color for interactive elements.
- **Raycast** — Employs a deep dark background, crisp typography, and minimal UI elements for a focused productivity tool aesthetic.
- **Notion (dark mode)** — Leverages a dark canvas for content, with clear typographic hierarchy and subtle grays for distinction, focusing on information density and readability.
- **Superhuman** — Features a dark interface with high-contrast text and sparse use of color to guide attention to key actions.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-deep-midnight: #000000;
  --color-cloud-whisper: #f0eded;
  --color-graphite-base: #0e0e0e;
  --color-muted-silver: #b3b3b3;
  --color-stone-gray: #808080;
  --color-soft-ash: #606060;
  --color-lush-meadow: #e1f0bd;

  /* Typography — Font Families */
  --font-sf-pro: 'SF Pro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-tanaclassic: 'tanaClassic', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 1.4;
  --text-body-sm: 15px;
  --leading-body-sm: 1.4;
  --text-subheading: 20px;
  --leading-subheading: 1.25;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.25;
  --text-heading: 48px;
  --leading-heading: 1.1;
  --tracking-heading: -0.96px;
  --text-display: 84px;
  --leading-display: 1.1;
  --tracking-display: -3.78px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-w350: 350;
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-96: 96px;
  --spacing-112: 112px;
  --spacing-128: 128px;
  --spacing-160: 160px;

  /* Layout */
  --section-gap: 24px;
  --card-padding: 16px;
  --element-gap: 6px;

  /* Border Radius */
  --radius-lg: 10px;

  /* Named Radii */
  --radius-tags: 8px;
  --radius-image: 10px;
  --radius-buttons: 12px;

  /* Surfaces */
  --surface-deep-midnight-canvas: #000000;
  --surface-graphite-base-layer: #0e0e0;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-deep-midnight: #000000;
  --color-cloud-whisper: #f0eded;
  --color-graphite-base: #0e0e0e;
  --color-muted-silver: #b3b3b3;
  --color-stone-gray: #808080;
  --color-soft-ash: #606060;
  --color-lush-meadow: #e1f0bd;

  /* Typography */
  --font-sf-pro: 'SF Pro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-tanaclassic: 'tanaClassic', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 1.4;
  --text-body-sm: 15px;
  --leading-body-sm: 1.4;
  --text-subheading: 20px;
  --leading-subheading: 1.25;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.25;
  --text-heading: 48px;
  --leading-heading: 1.1;
  --tracking-heading: -0.96px;
  --text-display: 84px;
  --leading-display: 1.1;
  --tracking-display: -3.78px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-96: 96px;
  --spacing-112: 112px;
  --spacing-128: 128px;
  --spacing-160: 160px;

  /* Border Radius */
  --radius-lg: 10px;
}
```

# Angellist — Style Reference
> Deep Space Luminescence – A dark, expansive canvas illuminated by subtle glows and precise typographic detail.

**Theme:** dark

AngelList employs a sophisticated, dark-mode-first aesthetic that juxtaposes a muted, deep teal canvas with soft, glowing text. The system leverages custom typography with subtle ligatures and tabular numbers, creating an elevated informational tone. Accents are primarily provided by a luminous violet and selective gradients, used sparingly to highlight key content or create atmospheric transitions. Components favor soft, rounded forms and minimal borders, maintaining a sense of approachability within the otherwise serious palette.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Teal | `#001d21` | `--color-midnight-teal` | Primary text, deep surface backgrounds, navigation elements, text button borders. This deep, almost black teal establishes the dark theme |
| Ghost Marble | `#f9f9f7` | `--color-ghost-marble` | Light surface backgrounds, default text in light sections, button text in dark sections. Provides contrast against darker elements |
| Stone Slate | `#ccd5d6` | `--color-stone-slate` | Subtle borders, dividers, ghost button borders, background of light sections. Provides minimal visual separation without harsh lines |
| Halo Violet | `#bdbbff` | `--color-halo-violet` | Accent text, highlighted body text, decorative icon strokes. This moderate violet provides a distinct, luminous brand accent |
| Inky Gray | `#002b31` | `--color-inky-gray` | Card backgrounds within the dark theme. Offers a slightly lighter shade than Midnight Teal for subtle layering |
| Success Mint | `#cdeed3` | `--color-success-mint` | Green wash for highlight backgrounds, decorative bands, and soft emphasis behind content. Use as a supporting accent, not as a status color |
| Info Sky | `#ceddec` | `--color-info-sky` | Muted UI surface for disabled controls, low-emphasis panels, and placeholder blocks. Use as a supporting accent, not as a status color |
| Warning Dusk | `#dbb3c8` | `--color-warning-dusk` | Red wash for highlight backgrounds, decorative bands, and soft emphasis behind content. Use as a supporting accent, not as a status color |
| Danger Peach | `#fed6cf` | `--color-danger-peach` | Gray wash for highlight backgrounds, decorative bands, and soft emphasis behind content. Use as a supporting accent, not as a status color |
| Midnight Glow Gradient | `linear-gradient(98.78deg, rgb(127, 120, 51) 6.69%, rgb(137, 142, 229) 40.89%, rgb(137, 142, 229) 83.02%, rgb(134, 123, 54) 100.19%)` | `--color-midnight-glow-gradient` | Decorative background gradients, often used subtly behind text or as a section divider. It evokes a cosmic, deep space feel |

## Tokens — Typography

### angellist — Body text, navigation links, and smaller UI elements. The custom font with its character set and tabular figures provides a precise, legible experience even at small sizes. · `--font-angellist`
- **Weights:** 400, 500, 550
- **Sizes:** 13px, 14px, 16px, 18px, 20px, 144px
- **Line height:** 0.80, 1.00, 1.40, 1.50, 1.60
- **Letter spacing:** -0.050em at 144px, -0.004em at 18px
- **OpenType features:** `'lnum', 'ss01', 'ss02', 'ss03', 'tnum'`
- **Role:** Body text, navigation links, and smaller UI elements. The custom font with its character set and tabular figures provides a precise, legible experience even at small sizes.

### angellistDisplay — Large display headlines. Its substantial sizes and precise letter-spacing ensure impactful yet controlled visual presence, making information feel important without shouting. · `--font-angellistdisplay`
- **Weights:** 400
- **Sizes:** 28px, 38px, 60px, 80px, 144px, 260px, 288px
- **Line height:** 0.75, 0.80, 1.00, 1.05, 1.10, 1.15, 1.25, 1.30
- **Letter spacing:** -0.025em at 288px, -0.015em at 60px
- **OpenType features:** `'lnum', 'ss01', 'ss02', 'ss03', 'tnum'`
- **Role:** Large display headlines. Its substantial sizes and precise letter-spacing ensure impactful yet controlled visual presence, making information feel important without shouting.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 13px | 1.6 | — | `--text-caption` |
| body-lg | 18px | 1.5 | -0.004px | `--text-body-lg` |
| subheading | 28px | 1.25 | — | `--text-subheading` |
| heading | 60px | 1.05 | -0.015px | `--text-heading` |
| display-sm | 144px | 0.8 | -0.05px | `--text-display-sm` |
| display | 288px | 0.75 | -0.025px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 8px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 8 | 8px | `--spacing-8` |
| 16 | 16px | `--spacing-16` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 80 | 80px | `--spacing-80` |
| 96 | 96px | `--spacing-96` |
| 144 | 144px | `--spacing-144` |
| 160 | 160px | `--spacing-160` |
| 224 | 224px | `--spacing-224` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 9999px |
| buttons | 9999px |
| default | 2px |

### Layout

- **Section gap:** 80px
- **Card padding:** 24px
- **Element gap:** 8px

## Components

### Ghost Navigation Button
**Role:** Navigation links or secondary actions

Transparent background, 'Midnight Teal' text, no padding on hover. Text uses 'angellist' font at default link sizes. Borders appear only when in a ghost state, using 'Stone Slate' for subtle emphasis.

### Inverted Navigation Button
**Role:** Primary action in dark navigation header

Filled with 'Midnight Teal', 'Ghost Marble' text. This is a filled button usually seen in the navigation for calls to action. Has a 9999px border-radius and no internal padding as it acts as a container for text.

### Light Secondary Button
**Role:** Secondary action in light sections

Background 'Ghost Marble', text 'Midnight Teal', 'Stone Slate' border. This button uses 4px 10px padding and a 9999px radius, suitable for small, contextual actions.

### Rounded Information Card
**Role:** Content container for features or articles

Background 'Midnight Teal', large 9999px border-radius, 24px padding. Used for grouping related content in a soft, approachable container.

### Inline Tag
**Role:** Categorization or status indicator

Backgrounds like 'Success Mint', 'Info Sky', 'Warning Dusk', 'Danger Peach'. These tags have a 9999px radius and 8px 24px padding, used for inline context.

### Header Divider
**Role:** Visual separator in the main navigation or content sections

Simple 1px solid line using 'Stone Slate' or 'Ghost Marble' for subtle visual breaks.

## Do's and Don'ts

### Do
- Prioritize 'Midnight Teal' (#001d21) for primary text and critical backgrounds to maintain the dark-first aesthetic.
- Utilize 'angellistDisplay' (weight 400) for all headings, leveraging its full size range and precise letter-spacing to create distinct visual hierarchy.
- Apply a 9999px border-radius to all buttons, cards, and interactive chips unless otherwise specified, maintaining a soft and approachable component feel.
- Use 'Halo Violet' (#bdbbff) exclusively as an accent for links, highlighted text, and small decorative icons to ensure its distinct visual impact.
- Maintain generous vertical spacing between sections, adhering to the 80px 'sectionGap' to provide breathing room on the page.
- Implement 'lnum', 'ss01', 'ss02', 'ss03', 'tnum' font features for both 'angellist' and 'angellistDisplay' to preserve the unique typographic character.
- Ensure all interactive elements have a clear :hover state transition for `transform`, `padding`, `color`, `background-color`, and `border-color` over 0.3s ease.

### Don't
- Avoid using saturated background colors for large sections; primary canvases should remain in the 'Midnight Teal' or 'Ghost Marble' neutral tones.
- Do not deviate from the specified custom `angellist` and `angellistDisplay` fonts or their defined letter-spacing and line heights; system fonts would compromise brand identity.
- Refrain from using hard, sharp angles; all significant UI elements should inherit the predominant 9999px radius or the default 2px minimal radius.
- Do not introduce additional accent colors beyond 'Halo Violet' (#bdbbff) or the defined semantic colors, as this will dilute the brand's controlled palette.
- Avoid heavy drop shadows or strong elevation; prefer subtle border treatments or slight background shifts for layering elements.
- Do not use generic typography (e.g., body, heading) without explicitly mapping to the `angellist` or `angellistDisplay` font definitions and their specific sizes/weights.
- Never use automatic or default browser link styling; always explicitly style links with 'Halo Violet' (#bdbbff) and the 'angellist' font.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Midnight Teal Canvas | `#001d21` | Primary page background for dark sections. Establishes the core visual theme. |
| 1 | Inky Gray Card | `#002b31` | Background for cards and elevated content blocks within the dark theme. |
| 2 | Ghost Marble Panel | `#f9f9f7` | Background for light sections, offering a sharp contrast to the darker palette for emphasis or content shifts. |

## Imagery

This design system uses a combination of abstract gradients and tightly cropped product screenshots. Photography is absent. Illustrations are stylized, flat, and often contain subtle gradients, serving a decorative atmosphere rather than explanatory content. Icons are minimal, outlined, and monochromatic, typically in 'Halo Violet' or white. Imagery is used sparingly, primarily in a contained rather than full-bleed manner, keeping the text-dominant layout clean and focused on information.

## Layout

The page primarily employs a max-width contained layout, though specific hero sections and gradient backgrounds can appear full-bleed. The hero pattern often features a large, dark background with centered, large-scale headlines using 'angellistDisplay' font, and a single tagline. Section rhythm is marked by consistent vertical spacing of 80px and occasional subtle gradient dividers. Content is arranged in alternating two-column text and image blocks or centered stacks for feature descriptions. A limited use of 3-column card grids is present for showcasing features. The overall density is spacious, allowing content to breathe. Navigation is a sticky top bar, minimalist with ghost links, and a distinctive filled 'Join Us' button.

## Agent Prompt Guide

Quick Color Reference:
text: #f9f9f7
background: #001d21
border: #ccd5d6
accent: #bdbbff
primary action: no distinct CTA color

Example Component Prompts:
No distinct primary action color was observed; use the extracted neutral button treatments instead of inventing a filled CTA color.
2. Create a feature card: background #002b31, 'angellistDisplay' heading text #f9f9f7 size 28px, 'angellist' body text #ccd5d6 size 14px, 9999px radius, 24px padding.
3. Create a ghost navigation link: text #f9f9f7 (on dark background) or #001d21 (on light background), 'angellist' font weight 400 size 14px, no background, 9999px radius, no padding.
4. Create an inline status tag: background 'Success Mint' (#cdeed3), text #001d21, 9999px radius, 8px 24px padding, 'angellist' font weight 400 size 13px.

## Similar Brands

- **Rippling** — Shares a sophisticated, deep-toned interface with precise typography and subtle color accents.
- **Linear** — Utilizes a dark primary theme with glowing accent colors and highly refined typography, focusing on information density.
- **Stripe** — Exhibits a clean, information-first design with a refined typographic scale and controlled use of color for functional elements.
- **Revolut** — Employs a dark, sleek aesthetic with minimal, high-contrast UI elements and a focus on financial/startup services.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-teal: #001d21;
  --color-ghost-marble: #f9f9f7;
  --color-stone-slate: #ccd5d6;
  --color-halo-violet: #bdbbff;
  --color-inky-gray: #002b31;
  --color-success-mint: #cdeed3;
  --color-info-sky: #ceddec;
  --color-warning-dusk: #dbb3c8;
  --color-danger-peach: #fed6cf;
  --color-midnight-glow-gradient: #898ee5;
  --gradient-midnight-glow-gradient: linear-gradient(98.78deg, rgb(127, 120, 51) 6.69%, rgb(137, 142, 229) 40.89%, rgb(137, 142, 229) 83.02%, rgb(134, 123, 54) 100.19%);

  /* Typography — Font Families */
  --font-angellist: 'angellist', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-angellistdisplay: 'angellistDisplay', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 1.6;
  --text-body-lg: 18px;
  --leading-body-lg: 1.5;
  --tracking-body-lg: -0.004px;
  --text-subheading: 28px;
  --leading-subheading: 1.25;
  --text-heading: 60px;
  --leading-heading: 1.05;
  --tracking-heading: -0.015px;
  --text-display-sm: 144px;
  --leading-display-sm: 0.8;
  --tracking-display-sm: -0.05px;
  --text-display: 288px;
  --leading-display: 0.75;
  --tracking-display: -0.025px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-w550: 550;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-144: 144px;
  --spacing-160: 160px;
  --spacing-224: 224px;

  /* Layout */
  --section-gap: 80px;
  --card-padding: 24px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-cards: 9999px;
  --radius-buttons: 9999px;
  --radius-default: 2px;

  /* Surfaces */
  --surface-midnight-teal-canvas: #001d21;
  --surface-inky-gray-card: #002b31;
  --surface-ghost-marble-panel: #f9f9f7;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-teal: #001d21;
  --color-ghost-marble: #f9f9f7;
  --color-stone-slate: #ccd5d6;
  --color-halo-violet: #bdbbff;
  --color-inky-gray: #002b31;
  --color-success-mint: #cdeed3;
  --color-info-sky: #ceddec;
  --color-warning-dusk: #dbb3c8;
  --color-danger-peach: #fed6cf;
  --color-midnight-glow-gradient: #898ee5;

  /* Typography */
  --font-angellist: 'angellist', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-angellistdisplay: 'angellistDisplay', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 1.6;
  --text-body-lg: 18px;
  --leading-body-lg: 1.5;
  --tracking-body-lg: -0.004px;
  --text-subheading: 28px;
  --leading-subheading: 1.25;
  --text-heading: 60px;
  --leading-heading: 1.05;
  --tracking-heading: -0.015px;
  --text-display-sm: 144px;
  --leading-display-sm: 0.8;
  --tracking-display-sm: -0.05px;
  --text-display: 288px;
  --leading-display: 0.75;
  --tracking-display: -0.025px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-144: 144px;
  --spacing-160: 160px;
  --spacing-224: 224px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-full: 9999px;
}
```

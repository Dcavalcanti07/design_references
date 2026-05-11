# Figma Config — Style Reference
> monochrome command console

**Theme:** dark

Figma Config employs a bold, high-contrast dark theme, emphasizing clarity and directness. Monochrome neutrals dominate the canvas, creating space for content to stand out. Typography is dense and strong, utilizing custom fonts that command attention while maintaining high legibility against the dark background. Interaction is signaled through subtle border changes and direct color swaps rather than complex elevation, giving components a lightweight and integrated feel.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Void | `#000000` | `--color-midnight-void` | Page background, primary text on light surfaces, button backgrounds for primary actions |
| Ghost White | `#e2e2e2` | `--color-ghost-white` | Primary text on dark backgrounds, ghost button borders, navigation links |
| Shadow Charcoal | `#3d3d3d` | `--color-shadow-charcoal` | Subtle button borders, secondary dividers |
| Polar Mist | `#ffffff` | `--color-polar-mist` | Background for lighter surfaces, such as cookie consent dialogs, secondary text color on dark backgrounds |

## Tokens — Typography

### figmaSans — Primary brand typeface for all headlines, body text, and interactive elements. Its specific letter-spacing creates a compact, intentional appearance, especially noticeable on larger headings. · `--font-figmasans`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 16px, 18px, 20px, 32px, 80px
- **Line height:** 0.95, 1.00, 1.10, 1.25, 1.30
- **Letter spacing:** -0.0300em at large sizes, -0.0200em at medium sizes
- **OpenType features:** `"kern"`
- **Role:** Primary brand typeface for all headlines, body text, and interactive elements. Its specific letter-spacing creates a compact, intentional appearance, especially noticeable on larger headings.

### figmaMono — Monospaced typeface for code snippets or technical details, offering a distinct visual break from the primary typeface while maintaining legibility. · `--font-figmamono`
- **Substitute:** Menlo
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.30
- **Letter spacing:** normal
- **Role:** Monospaced typeface for code snippets or technical details, offering a distinct visual break from the primary typeface while maintaining legibility.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body | 16px | 1.3 | — | `--text-body` |
| subheading | 20px | 1.1 | — | `--text-subheading` |
| heading | 32px | 1.1 | -0.64px | `--text-heading` |
| display | 80px | 0.95 | -2.4px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 6 | 6px | `--spacing-6` |
| 12 | 12px | `--spacing-12` |
| 16 | 16px | `--spacing-16` |
| 23 | 23px | `--spacing-23` |
| 24 | 24px | `--spacing-24` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 60 | 60px | `--spacing-60` |
| 157 | 157px | `--spacing-157` |
| 160 | 160px | `--spacing-160` |

### Border Radius

| Element | Value |
|---------|-------|
| buttons | 0px |
| navPills | 50% |

### Layout

- **Section gap:** 40px
- **Card padding:** 12px
- **Element gap:** 12px

## Components

### Primary Filled Button
**Role:** Main call-to-action on dark backgrounds.

Solid Midnight Void background, Ghost White text. Padding 12px horizontal and vertical. Square corners (0px radius). Example: 'ALLOW ALL COOKIES'.

### Ghost Button
**Role:** Secondary action or navigable link that appears as a button.

Transparent background, Ghost White text and 1px border. No padding specified, acts as a text link with button styling. Example: 'GO TO HOMEPAGE'.

### Cookie Consent Button
**Role:** Button within the cookie consent dialog.

Solid Midnight Void background with Ghost White text and a subtle 1px border of `rgba(255, 255, 255, 0.24)`. Rounded with 50% border radius. No explicit padding data, likely derived from text size.

### Navigation Link
**Role:** Top-level navigation items.

Ghost White text, with a 1px border of Midnight Void. Compact padding of 4-6px vertical and 6-12px horizontal. Renders as text only with a subtle underline effect on hover (not present in current data).

### Cookie Consent Panel
**Role:** Floating informational message.

Polar Mist background with Midnight Void text for primary content. Elements within use Shadow Charcoal borders. Padding is not explicit but appears generous. Square corners (0px radius).

## Do's and Don'ts

### Do
- Use Midnight Void (#000000) as the dominant background color for all main canvas areas.
- Apply FigmaSans for all text elements, setting letter-spacing to -0.0300em for display text (80px, 32px) and -0.0200em for smaller headings and body text.
- Form primary interactive buttons with a Midnight Void (#000000) background and Ghost White (#e2e2e2) text, using 0px border-radius.
- For ghost buttons or secondary actions, use Ghost White (#e2e2e2) for both text and a 1px border, maintaining a transparent background.
- Utilize the 4-6px vertical padding and 6-12px horizontal padding for navigation and compact interactive elements.
- Maintain a primary text color of Ghost White (#e2e2e2) against dark backgrounds and Midnight Void (#000000) against light backgrounds.
- Apply 1px borders using Midnight Void or Shadow Charcoal (#3d3d3d) for subtle division and emphasis.

### Don't
- Avoid using gradients; the system relies on flat colors for a stark, impactful appearance.
- Do not introduce intermediate grey tones between Midnight Void (#000000) and Ghost White (#e2e2e2) without a clear functional purpose, as the system favors high contrast.
- Do not use highly saturated colors for large surface areas; color is reserved for functional accents or semantic states.
- Do not use generic system fonts; stick to figmaSans or figmaMono for all typographic elements.
- Avoid soft, rounded corners for main interactive elements (buttons, cards); prefer sharp, square edges unless specifically for small pill-shaped accents.
- Do not use drop shadows for elevation; rely on color contrast and borders to define hierarchy and interactive states.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas | `#000000` | Primary page background for most sections. |
| 1 | Dialog | `#ffffff` | Background for overlay elements like cookie consent pop-ups, providing a contrast to the dark canvas. |

## Imagery

The visual language uses abstract, organic, blob-like shapes in a limited, vibrant accent palette (blue, green, orange, yellow) against the dark, high-contrast UI. These shapes are mostly opaque, layered, and slightly rotated, creating a playful yet dynamic feel. They function primarily as decorative atmosphere rather than conveying specific content. Icons, such as the `(pause)` and `(X)` are minimal, outlined, and monochromatic, integrated seamlessly into the UI.

## Layout

The page maintains a full-bleed dark background, with content neatly centered or aligned to the left. The hero section features a prominent headline centered over the dark background. Sections generally use consistent vertical spacing, often indicated by the 40px section gap. Content arrangement appears to be stacked vertically, with some areas allowing for asymmetric or interleaved visual elements like the abstract shapes. The navigation is a minimal, right-aligned header bar that stays fixed at the top, offering essential links.

## Agent Prompt Guide

Quick Color Reference: 
text: #e2e2e2
background: #000000
border: #3d3d3d
accent: no distinct accent color
primary action: #000000 (filled action)

Example Component Prompts:
1. Create a primary call-to-action button: background #000000, text #e2e2e2 (FigmaSans, 16px, weight 400, lineHeight 1.3), 0px radius, 12px padding. Label it 'ALLOW ALL COOKIES'.
2. Design a ghost button for navigation: text #e2e2e2 (FigmaSans, 16px, weight 400, lineHeight 1.3), 1px border #e2e2e2, transparent background, 0px radius. Label it 'GO TO HOMEPAGE'.
3. Build a main section header: text #e2e2e2 (FigmaSans, 80px, weight 400, lineHeight 0.95, letterSpacing -2.4px). Label it 'We couldn't find the page you requested.'.
4. Create a navigation link: text #e2e2e2 (FigmaSans, 16px, weight 400, lineHeight 1.3), 1px border #000000, transparent background, 4px vertical and 6px horizontal padding. Label it 'Speakers'.

## Similar Brands

- **Sanity.io** — Features a dark UI, strong custom typography, and a limited accent color palette for interactive elements.
- **Supabase** — Utilizes a dark theme with high contrast and impactful typography, often incorporating abstract or geometric background elements.
- **Vercel** — Known for a meticulously crafted dark UI, compact spacing, and a focus on sharp, legible typography on a dark canvas.
- **Linear** — Employs a monochrome dark mode, precise typography with careful letter-spacing, and a minimalist approach to components.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-void: #000000;
  --color-ghost-white: #e2e2e2;
  --color-shadow-charcoal: #3d3d3d;
  --color-polar-mist: #ffffff;

  /* Typography — Font Families */
  --font-figmasans: 'figmaSans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-figmamono: 'figmaMono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-body: 16px;
  --leading-body: 1.3;
  --text-subheading: 20px;
  --leading-subheading: 1.1;
  --text-heading: 32px;
  --leading-heading: 1.1;
  --tracking-heading: -0.64px;
  --text-display: 80px;
  --leading-display: 0.95;
  --tracking-display: -2.4px;

  /* Typography — Weights */
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-6: 6px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-23: 23px;
  --spacing-24: 24px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-60: 60px;
  --spacing-157: 157px;
  --spacing-160: 160px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 12px;
  --element-gap: 12px;

  /* Named Radii */
  --radius-buttons: 0px;
  --radius-navpills: 50%;

  /* Surfaces */
  --surface-canvas: #000000;
  --surface-dialog: #ffffff;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-void: #000000;
  --color-ghost-white: #e2e2e2;
  --color-shadow-charcoal: #3d3d3d;
  --color-polar-mist: #ffffff;

  /* Typography */
  --font-figmasans: 'figmaSans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-figmamono: 'figmaMono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-body: 16px;
  --leading-body: 1.3;
  --text-subheading: 20px;
  --leading-subheading: 1.1;
  --text-heading: 32px;
  --leading-heading: 1.1;
  --tracking-heading: -0.64px;
  --text-display: 80px;
  --leading-display: 0.95;
  --tracking-display: -2.4px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-6: 6px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-23: 23px;
  --spacing-24: 24px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-60: 60px;
  --spacing-157: 157px;
  --spacing-160: 160px;
}
```

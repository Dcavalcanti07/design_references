# Alpine Bio — Style Reference
> Scientific blueprint on parchment.

**Theme:** light

Alpine Bio employs a clinical, ingredients-first visual language: a monochromatic canvas with precise typography and a singular muted blue accent. The design feels grounded and scientific, prioritizing clarity and information over decorative flourish. Surfaces are crisp and clean, with subtle variations that delineate content blocks rather than creating heavy visual separation. Typography is compact and deliberate, often using tight letter-spacing to reinforce a sense of precision.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#000000` | `--color-midnight-ink` | Primary text, heading text, accent borders, subtle interface graphics |
| Canvas White | `#f5f5f5` | `--color-canvas-white` | Main page background, default surface for most content |
| Parchment | `#f8f4e6` | `--color-parchment` | Subtle background for distinct content sections |
| Ghost Gray | `#e9e9e9` | `--color-ghost-gray` | Background for secondary buttons, navigation items when active, subtle card backgrounds |
| Muted Stone | `#1e1e1f` | `--color-muted-stone` | Secondary text, descriptive body copy |
| Polar Mist | `#c9c9c9` | `--color-polar-mist` | Dividers, very subtle background elements |
| Header Gray | `#666666` | `--color-header-gray` | Navigation bar background |
| Sunbeam Yellow | `#f7ca50` | `--color-sunbeam-yellow` | Subtle decorative highlight, background for footer elements |
| Bio Blue | `#8ec7e2` | `--color-bio-blue` | Blue wash for highlight backgrounds, decorative bands, and soft emphasis behind content. Do not promote it to the primary CTA color |

## Tokens — Typography

### Geist — Primary text for body, subheadings, and some callouts. The variability in sizes and weights allows for subtle hierarchy. · `--font-geist`
- **Substitute:** Inter
- **Weights:** 400, 500
- **Sizes:** 13px, 15px, 18px, 22px, 42px
- **Line height:** 1.00, 1.20, 1.35
- **Letter spacing:** -0.0500em at 42px, -0.0300em at 22px
- **Role:** Primary text for body, subheadings, and some callouts. The variability in sizes and weights allows for subtle hierarchy.

### Switzer — Display and section headings. Its clean forms maintain legibility even at large sizes with tight tracking, conveying authority without being decorative. · `--font-switzer`
- **Substitute:** Work Sans
- **Weights:** 400, 500
- **Sizes:** 20px, 32px, 48px, 76px
- **Line height:** 1.10, 1.20
- **Letter spacing:** -0.0500em
- **Role:** Display and section headings. Its clean forms maintain legibility even at large sizes with tight tracking, conveying authority without being decorative.

### PT Mono — Muted navigation items and specific data points. The monospace quality suggests precision and technical detail. · `--font-pt-mono`
- **Substitute:** Fira Code
- **Weights:** 400
- **Sizes:** 13px
- **Line height:** 1.20
- **Letter spacing:** -0.0400em
- **Role:** Muted navigation items and specific data points. The monospace quality suggests precision and technical detail.

### sans-serif — Default system text, likely for small utility text or when custom fonts fail to load. · `--font-sans-serif`
- **Substitute:** Arial
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.20
- **Role:** Default system text, likely for small utility text or when custom fonts fail to load.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.2 | — | `--text-caption` |
| body | 15px | 1.2 | — | `--text-body` |
| subheading | 18px | 1.35 | — | `--text-subheading` |
| heading-sm | 22px | 1.2 | -0.03px | `--text-heading-sm` |
| heading | 32px | 1.2 | -0.05px | `--text-heading` |
| heading-lg | 42px | 1 | -0.05px | `--text-heading-lg` |
| display | 76px | 1.1 | -0.05px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 6 | 6px | `--spacing-6` |
| 8 | 8px | `--spacing-8` |
| 10 | 10px | `--spacing-10` |
| 12 | 12px | `--spacing-12` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 48 | 48px | `--spacing-48` |
| 63 | 63px | `--spacing-63` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 110 | 110px | `--spacing-110` |
| 120 | 120px | `--spacing-120` |
| 150 | 150px | `--spacing-150` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 22px |
| buttons | 3px |
| heroElement | 50px |
| imageContainers | 18px |

### Layout

- **Section gap:** 80px
- **Card padding:** 12px
- **Element gap:** 10px

## Components

### Ghost Button
**Role:** Secondary action button, often paired with text links.

Background transparent, text #000000, 12px vertical padding, 2px right padding, 12px left padding. No border-radius or border color specified, implying no visible border.

### Filled Default Button
**Role:** Informational or utility buttons in navigation.

Background #e9e9e9, text #000000, 3px border-radius, 0px padding. This suggests a compact, minimal button style.

### Navigation Link
**Role:** Main navigation items, text in PT Mono.

Uses PT Mono weight 400 at 13px, color #666666 for inactive, becoming #000000 on hover. Backgrounds can be #e9e9e9 on hover/active.

### Image Card
**Role:** Used in carousels or feature showcases.

Features an image with an 18px border-radius. Labels use Geist at 15px, color #000000, and often have a Bio Blue accent for interaction.

### Hero Action Button
**Role:** Prominent call to action in hero section.

Text in Geist at 18px, weight 500. Uses Bio Blue (8ec7e2) for background, with 22px border radius, text color #000000. Features a small arrow icon.

## Do's and Don'ts

### Do
- Prioritize text content over large decorative imagery; imagery should be concise and product-focused.
- Use Geist for primary headings and body copy, varying weights between 400 and 500 for subtle hierarchy without significant shifts in density.
- Apply a 22px border-radius to larger interactive containers and cards to introduce a soft, approachable feel where appropriate.
- Utilize Bio Blue (#8ec7e2) exclusively for interactive elements like buttons, links, and icons to guide user attention.
- Maintain high contrast text #000000 on Canvas White (#f5f5f5) or Parchment (#f8f4e6) for maximum readability.
- Employ the compact letter-spacing values (-0.0500em, -0.0300em, -0.0400em) for headings and specific text elements to achieve a precise typographic signature.
- Employ consistent 10px element gaps for moderate spacing between smaller interface components, avoiding excessive visual clutter.

### Don't
- Do not introduce strong, saturated colors beyond Bio Blue and Sunbeam Yellow; maintain a largely monochromatic palette.
- Avoid decorative shadows or elaborate gradients; surfaces should appear flat and clean.
- Do not use generic system fonts when Geist, Switzer, or PT Mono are available, as they define the brand's typographic voice.
- Refrain from drastically altering section spacing; adhere to the 80px section gap for a consistent rhythm.
- Do not use large, full-bleed hero images that compete with textual information; if used, they should be subdued and content-centric.
- Avoid overly generous padding or margins that create excessive whitespace; maintain a compact, information-dense layout.
- Do not apply inconsistent border radii; adhere to the specified values of 22px, 18px, 3px, and 50px for design elements.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Canvas White | `#f5f5f5` | Base page background |
| 2 | Parchment | `#f8f4e6` | Alternative section background |
| 3 | Ghost Gray | `#e9e9e9` | Secondary background for cards or interactive states |

## Imagery

Imagery primarily consists of tight product photography or ingredient processing shots. These visuals are typically contained within cards with 18px rounded corners. Photography is high-key, with bright lighting and often features product crops on plain backgrounds, emphasizing the product itself with minimal lifestyle context. Icons, where present, appear to be simple, outlined, and monochromatic, matching the overall precise and clean aesthetic. Imagery functions mainly as explanatory content or product showcase, integrated tightly into the UI rather than as large, atmospheric hero visuals.

## Layout

The page primarily uses a contained layout with a maximum width not explicitly defined but visually constrained, resulting in ample side spacing relative to a central content block. The hero section is full-bleed with a muted background image overlayed with large, centered typography and a central action button. Subsequent sections alternate between Canvas White and Parchment backgrounds, creating a clear vertical rhythm. Content arrangement often features two-column layouts, with text adjacent to image cards. Feature sections utilize a grid of image cards (e.g., 3-column). Navigation is a sticky top bar with a primary 'Contact Us' button featuring the Bio Blue accent.

## Agent Prompt Guide

Quick Color Reference: 
text: #000000
background: #f5f5f5
border: #000000
accent: #8ec7e2
primary action: no distinct CTA color

Example Component Prompts:
Create a hero section: Canvas White (#f5f5f5) background with an overlaying, subdued full-bleed image. Headline (Switzer, 76px, weight 500, #000000, letter-spacing -0.05em) centered. Subtext (Geist, 18px, weight 400, #000000). A Hero Action Button (Bio Blue background #8ec7e2, #000000 text, Geist 18px weight 500, 22px radius).
Create an image card: Parchment (#f8f4e6) background, 18px border-radius. Image aligned top. Below the image, a label (Geist, 15px, weight 400, #000000) and a small Bio Blue (#8ec7e2) interactive icon.
Create a navigation bar: Header Gray (#666666) opaque background. Left-aligned brand logo. Nav links (PT Mono, 13px, weight 400, #000000 for active, #666666 for inactive). Right-aligned 'Contact Us' button (Bio Blue background #8ec7e2, #000000 text, Geist 18px weight 500, 22px radius, 12px vertical padding, 24px horizontal padding).

## Similar Brands

- **Axiom Space** — Monochromatic, clinical aesthetic with focus on precision and technical details.
- **Modern Fertility** — Clean, almost entirely achromatic palette with a single muted accent color for interactivity.
- **Impossible Foods (corporate site)** — Emphasis on science and ingredients with minimalist design, clean typography, and contained visuals.
- **Geltor** — Scientific product focus, subtle background textures, and precise typography creating a sense of clarity.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-canvas-white: #f5f5f5;
  --color-parchment: #f8f4e6;
  --color-ghost-gray: #e9e9e9;
  --color-muted-stone: #1e1e1f;
  --color-polar-mist: #c9c9c9;
  --color-header-gray: #666666;
  --color-sunbeam-yellow: #f7ca50;
  --color-bio-blue: #8ec7e2;

  /* Typography — Font Families */
  --font-geist: 'Geist', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-switzer: 'Switzer', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-pt-mono: 'PT Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.2;
  --text-body: 15px;
  --leading-body: 1.2;
  --text-subheading: 18px;
  --leading-subheading: 1.35;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: -0.03px;
  --text-heading: 32px;
  --leading-heading: 1.2;
  --tracking-heading: -0.05px;
  --text-heading-lg: 42px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -0.05px;
  --text-display: 76px;
  --leading-display: 1.1;
  --tracking-display: -0.05px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-63: 63px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-110: 110px;
  --spacing-120: 120px;
  --spacing-150: 150px;

  /* Layout */
  --section-gap: 80px;
  --card-padding: 12px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-sm: 3px;
  --radius-2xl: 18px;
  --radius-2xl-2: 22px;
  --radius-full: 50px;

  /* Named Radii */
  --radius-cards: 22px;
  --radius-buttons: 3px;
  --radius-heroelement: 50px;
  --radius-imagecontainers: 18px;

  /* Surfaces */
  --surface-canvas-white: #f5f5f5;
  --surface-parchment: #f8f4e6;
  --surface-ghost-gray: #e9e9e9;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-canvas-white: #f5f5f5;
  --color-parchment: #f8f4e6;
  --color-ghost-gray: #e9e9e9;
  --color-muted-stone: #1e1e1f;
  --color-polar-mist: #c9c9c9;
  --color-header-gray: #666666;
  --color-sunbeam-yellow: #f7ca50;
  --color-bio-blue: #8ec7e2;

  /* Typography */
  --font-geist: 'Geist', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-switzer: 'Switzer', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-pt-mono: 'PT Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.2;
  --text-body: 15px;
  --leading-body: 1.2;
  --text-subheading: 18px;
  --leading-subheading: 1.35;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: -0.03px;
  --text-heading: 32px;
  --leading-heading: 1.2;
  --tracking-heading: -0.05px;
  --text-heading-lg: 42px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -0.05px;
  --text-display: 76px;
  --leading-display: 1.1;
  --tracking-display: -0.05px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-63: 63px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-110: 110px;
  --spacing-120: 120px;
  --spacing-150: 150px;

  /* Border Radius */
  --radius-sm: 3px;
  --radius-2xl: 18px;
  --radius-2xl-2: 22px;
  --radius-full: 50px;
}
```

# SoundCloud — Style Reference
> Dark stage, glowing spotlights. A deep, consistent dark background sets the scene, with strategic, vivid accents drawing attention to key interactive elements like a spotlight.

**Theme:** dark

This design system creates an immersive, contemporary feel with a dark foundation that amplifies content. A rich interplay of stark black and soft gray neutrals forms a sophisticated backdrop, punctuated by a signature vibrant blue for interactive elements. The controlled color palette, combined with a crisp, minimal typographic hierarchy, allows content, especially diverse album art, to become the primary visual driver. Rounded corners on buttons and inputs offer a touch of user-friendliness against the otherwise strong, dark aesthetic.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Pitch Black | `#121212` | `--color-pitch-black` | Page backgrounds, major section backgrounds, card backgrounds, all primary UI surfaces. |
| Ash Gray | `#303030` | `--color-ash-gray` | Input backgrounds, secondary background surfaces for elevated elements. |
| Ghost White | `#ffffff` | `--color-ghost-white` | Primary text, headline text, core iconography, button text on dark backgrounds. |
| Storm Gray | `#999999` | `--color-storm-gray` | Secondary text, descriptive elements, navigation links, inactive states, placeholder text. |
| Cloud Gray | `#999999` | `--color-cloud-gray` | Decorative borders around subtle elements, button outlines on dark backgrounds. |
| Faded White | `#f2f2f2` | `--color-faded-white` | Light button backgrounds, subtle surface variations against dark primary backgrounds. |
| Skybound Blue | `#699fff` | `--color-skybound-blue` | Primary interactive links, selected navigation items, key visual indicators — signals interactivity and focus, drawing the eye in a primarily dark interface. |
| Sunset Ember | `#ff5500` | `--color-sunset-ember` | Accent for call-to-action buttons in specific promotional contexts, drawing immediate attention with high contrast against dark. |
| Melodic Blush Gradient | `linear-gradient(135deg, rgb(142, 132, 133), rgb(230, 132, 110))` | `--color-melodic-blush-gradient` | Promotional or decorative banners, providing a soft, warm gradient transition. |
| Ocean Serenity Gradient | `linear-gradient(135deg, rgb(112, 146, 156), rgb(142, 132, 133))` | `--color-ocean-serenity-gradient` | Subtle background for specific content blocks, offering a cooler, calming gradient. |

## Tokens — Typography

### Söhne — All text elements, unifies the visual language from headlines to body text. Its modern, understated character supports the content-driven approach. · `--font-shne`
- **Substitute:** system-ui, sans-serif
- **Weights:** 100, 400, 600, 700
- **Sizes:** 12px, 14px, 17px, 18px, 22px, 28px, 36px, 60px
- **Line height:** 1.00, 1.20, 1.27, 1.29, 1.33, 1.41, 1.43, 1.71
- **Role:** All text elements, unifies the visual language from headlines to body text. Its modern, understated character supports the content-driven approach.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.71 | — | `--text-caption` |
| body | 14px | 1.43 | — | `--text-body` |
| heading | 22px | 1.27 | — | `--text-heading` |
| heading-lg | 36px | 1.2 | — | `--text-heading-lg` |
| display | 60px | 1 | — | `--text-display` |

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
| 64 | 64px | `--spacing-64` |
| 96 | 96px | `--spacing-96` |
| 180 | 180px | `--spacing-180` |

### Border Radius

| Element | Value |
|---------|-------|
| none | 0px |
| images | 16px |
| inputs | 3px |
| default | 4px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(18, 18, 18, 0.1) 0px 0px 0px 1px inset` | `--shadow-subtle` |

### Layout

- **Page max-width:** 1240px
- **Section gap:** 96px
- **Card padding:** 12px
- **Element gap:** 8px

## Components

### Primary Dark Button
**Role:** Call to Action

Background: Pitch Black (#121212), Text: Ghost White (#ffffff). Border: Ghost White (#ffffff). Radius: 4px. Padding: 6px vertical, 12px horizontal. Used for primary actions against light backgrounds.

### Secondary Light Button
**Role:** Secondary Action

Background: Ghost White (#ffffff), Text: Pitch Black (#121212). Border: Pitch Black (#121212). Radius: 4px. Padding: 6px vertical, 12px horizontal. Used for secondary actions against a dark background.

### Tertiary Light Button
**Role:** Alternative Action

Background: Faded White (#f2f2f2), Text: Pitch Black (#121212). Border: Pitch Black (#121212). Radius: 4px. Padding: 6px vertical, 12px horizontal. Used for less prominent actions, providing a softer contrast than the Secondary button.

### Ghost Button
**Role:** Minimal Action

Background: transparent, Text: Storm Gray (#999999). Border: Storm Gray (#999999). Radius: 0px. Padding: 0px. Used for subtle actions like navigation links or inline actions.

### Search Input Field
**Role:** Content Search

Background: Ash Gray (#303030), Text: Ghost White (#ffffff). Placeholder: Storm Gray (#999999). Border: transparent. Radius: 3px. Padding: 8px vertical, 16px left, 40px right. Features an inset shadow rgba(18, 18, 18, 0.1) 0px 0px 0px 1px.

### Primary Navigation Link
**Role:** Interactive Navigation

Text: Storm Gray (#999999) inactive, Skybound Blue (#699fff) active. No background or border. Default typography: Söhne, 17px, 400 weight.

### Hero Headline
**Role:** Main Page Title

Text: Ghost White (#ffffff), Söhne, 60px, 700 weight, 1.0 line height. Central focus of the hero section, commanding visual attention.

## Do's and Don'ts

### Do
- Use Pitch Black (#121212) as the default background for all primary content sections.
- Apply a 4px `radius.default` to all interactive elements except ghost buttons and input fields to maintain a consistent subtle softening.
- Employ Söhne 60px / 1.0 line height / 700 weight for all main page headlines against dark backgrounds.
- Highlight interactive links and active states with Skybound Blue (#699fff) to maintain a clear visual hierarchy.
- Utilize 8px for `elementGap` to ensure consistent spacing between distinct inline elements and input fields.
- Ensure all text against Pitch Black backgrounds uses Ghost White (#ffffff) for optimal contrast and readability.
- Contain all main content within a `pageMaxWidth` of 1240px, centered on the screen.

### Don't
- Avoid using highly saturated background colors that compete with primary content or album art.
- Do not deviate from Söhne as the sole typeface; stick to its specified weights and sizes.
- Never use hard-edged elements where a 3px input radius or 4px button radius is expected.
- Refrain from using shadows for elevation; rely on background color variations (e.g., Ash Gray on Pitch Black) to indicate depth.
- Do not add additional padding to Album Art Cards; they should appear flush with their grid container.
- Avoid generic black (#000000) for text on light button backgrounds; use Pitch Black (#121212) for brand consistency.

## Elevation

This design intentionally avoids conventional drop shadows for conveying elevation. Instead, depth and hierarchy are established through shifts in background color (e.g., Ash Gray input fields on Pitch Black pages) and a subtle inset shadow rgba(18, 18, 18, 0.1) 0px 0px 0px 1px on input fields. This approach preserves the clean, flat aesthetic of the dark theme while still providing subtle visual cues.

## Imagery

The visual language for imagery is content-centric, relying heavily on diverse, high-fidelity album art and artist photography. Images are presented in square or near-square formats, often in grids, without borders or masks, allowing the art to speak for itself. Photography, particularly in the hero section, tends towards darker, more artistic compositions that blend seamlessly with the dark UI. There are also product screenshots of mobile devices, depicted as clean, contained elements on a white background, contrasting the main dark theme to highlight app features. Icons are minimal, line-based, and achromatic, primarily Ghost White against dark backgrounds, serving purely functional roles.

## Layout

The site employs a max-width 1240px centered layout for content sections, set against a full-bleed dark background. The hero section is a full-width, dark-themed banner with a strong, centered headline and a large, evocative artist image that dominates the visual space. Subsequent sections maintain consistent vertical spacing, featuring prominent content grids for album art (typically 5-column or 4-column) and a clear division between content blocks. The navigation is a fixed top bar on a dark background, and content often appears in full-width rows with internal grid structures. There's a notable shift to a contained, light background section for illustrating app features, providing visual contrast and separation for product-focused content.

## Agent Prompt Guide

### Quick Color Reference
- Text (Primary): #ffffff
- Background (Primary): #121212
- CTA (Accent): #ff5500
- Link/Active: #699fff
- Border/Outline (Subtle): #999999
- Input Background: #303030

### 3-5 Example Component Prompts
1. Create a `Hero Headline` section: `Pitch Black` background, centered. Headline text 'Discover. Get Discovered.' using Söhne 60px, 700 weight, 1.0 line height, `Ghost White` color. Include a 'Get Started' button (Background: `Pitch Black` #121212, Text: `Ghost White` #ffffff, Border: `Ghost White` #ffffff, Radius: 4px, Padding: 6px vertical, 12px horizontal).

2. Design a `Search Input Field`: `Ash Gray` (#303030) background, `Ghost White` (#ffffff) text, radius 3px, padding 8px vertical, 16px left, 40px right. Placeholder text 'Search for artists, bands, tracks, podcasts' in `Storm Gray` (#999999). Add inset shadow rgba(18, 18, 18, 0.1) 0px 0px 0px 1px.

3. Generate a `Trending Playlists Section`: Background `Pitch Black` (#121212), containing a grid of `Album Art Cards` (no background, `Ghost White` (#ffffff) text overlays on imagery, 0px radius, 0px padding). Below the grid, add a `Secondary Light Button` labeled 'Explore trending playlists' (Background: `Ghost White` #ffffff, Text: `Pitch Black` #121212, Border: `Pitch Black` #121212, Radius: 4px, Padding: 6px vertical, 12px horizontal).

4. Implement a `Navigation Link` for 'Home': Söhne, 17px, 400 weight, `Skybound Blue` (#699fff) for active state, `Storm Gray` (#999999) for inactive state. No background, no border, 0px padding.

## Similar Brands

- **Spotify** — Shares a dark-mode UI, content-first approach with heavy reliance on album art in grids, and a single vibrant accent color for interactivity.
- **Netflix** — Utilizes a dark background to make visual content (movie posters/thumbnails) pop, with clean typography and minimal UI elements.
- **Apple Music** — Employs a content-heavy dark theme, with a focus on immersive full-bleed imagery and album artwork as primary visual elements.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-pitch-black: #121212;
  --color-ash-gray: #303030;
  --color-ghost-white: #ffffff;
  --color-storm-gray: #999999;
  --color-cloud-gray: #999999;
  --color-faded-white: #f2f2f2;
  --color-skybound-blue: #699fff;
  --color-sunset-ember: #ff5500;
  --color-melodic-blush-gradient: #8e8485;
  --gradient-melodic-blush-gradient: linear-gradient(135deg, rgb(142, 132, 133), rgb(230, 132, 110));
  --color-ocean-serenity-gradient: #70929c;
  --gradient-ocean-serenity-gradient: linear-gradient(135deg, rgb(112, 146, 156), rgb(142, 132, 133));

  /* Typography — Font Families */
  --font-shne: 'Söhne', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.71;
  --text-body: 14px;
  --leading-body: 1.43;
  --text-heading: 22px;
  --leading-heading: 1.27;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1.2;
  --text-display: 60px;
  --leading-display: 1;

  /* Typography — Weights */
  --font-weight-thin: 100;
  --font-weight-regular: 400;
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
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-96: 96px;
  --spacing-180: 180px;

  /* Layout */
  --page-max-width: 1240px;
  --section-gap: 96px;
  --card-padding: 12px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-2xl: 16px;

  /* Named Radii */
  --radius-none: 0px;
  --radius-images: 16px;
  --radius-inputs: 3px;
  --radius-default: 4px;

  /* Shadows */
  --shadow-subtle: rgba(18, 18, 18, 0.1) 0px 0px 0px 1px inset;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-pitch-black: #121212;
  --color-ash-gray: #303030;
  --color-ghost-white: #ffffff;
  --color-storm-gray: #999999;
  --color-cloud-gray: #999999;
  --color-faded-white: #f2f2f2;
  --color-skybound-blue: #699fff;
  --color-sunset-ember: #ff5500;
  --color-melodic-blush-gradient: #8e8485;
  --color-ocean-serenity-gradient: #70929c;

  /* Typography */
  --font-shne: 'Söhne', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.71;
  --text-body: 14px;
  --leading-body: 1.43;
  --text-heading: 22px;
  --leading-heading: 1.27;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1.2;
  --text-display: 60px;
  --leading-display: 1;

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
  --spacing-64: 64px;
  --spacing-96: 96px;
  --spacing-180: 180px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-2xl: 16px;

  /* Shadows */
  --shadow-subtle: rgba(18, 18, 18, 0.1) 0px 0px 0px 1px inset;
}
```

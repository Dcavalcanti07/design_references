# Vimeo — Style Reference
> Digital Atelier

**Theme:** light

Vimeo's design system evokes a digital atelier: functional, content-focused, and subtly expressive. A dominant dark gray canvas anchors the experience, punctuated by a vivid, cool teal accent that signifies interactivity and brand presence. Typography is compact and precise, establishing clear hierarchy without visual fanfare. Components are lightweight with softened corners, relying on shifts in neutral tones rather than heavy shadows or borders.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Graphite | `#141a20` | `--color-midnight-graphite` | Primary background, dark card surfaces, primary text for dark sections |
| Cloud Canvas | `#fafcfd` | `--color-cloud-canvas` | Page background, light card surfaces, secondary text for dark sections |
| Ash Gray | `#23313b` | `--color-ash-gray` | Muted text, subheadings, soft borders, footer text and backgrounds |
| Steel Gray | `#3d4751` | `--color-steel-gray` | Body text, interactive link borders, subtle icon fills |
| Slate Blue | `#4c5864` | `--color-slate-blue` | Navigation text, secondary body copy, disabled button text |
| Light Mist | `#dfe4ea` | `--color-light-mist` | Subtle background for UI elements, hover states on neutral surfaces |
| Cosmic Teal | `#17d5ff` | `--color-cosmic-teal` | Primary action buttons, active navigation indicators, badges, brand accents |
| Deep Teal | `#13b1d4` | `--color-deep-teal` | Hover state for Cosmic Teal elements, deeper brand accents |
| Overlay Shadow | `#000000` | `--color-overlay-shadow` | Text on very light backgrounds, specific button borders and icon fills |

## Tokens — Typography

### ABCRepro — Primary typeface for all UI text, headings, and body copy. Its range of weights and optical sizing provides both headline impact and legibility for dense information. · `--font-abcrepro`
- **Substitute:** Inter
- **Weights:** 400, 500, 700
- **Sizes:** 10px, 12px, 13px, 14px, 16px, 18px, 19px, 20px, 24px, 32px, 40px, 72px
- **Line height:** 1.00, 1.10, 1.14, 1.20, 1.30, 1.35, 1.40, 1.58
- **Letter spacing:** -0.0500em at 72px, -0.0400em at 40px, -0.0360em at 32px, -0.0300em at 24px and below
- **OpenType features:** `"lnum" on`
- **Role:** Primary typeface for all UI text, headings, and body copy. Its range of weights and optical sizing provides both headline impact and legibility for dense information.

### ABCReproMono — Monospace typeface used sparingly for specific data displays or code snippets where character alignment is critical. · `--font-abcrepromono`
- **Substitute:** Space Mono
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.00
- **Letter spacing:** -0.0300em
- **OpenType features:** `"lnum" on`
- **Role:** Monospace typeface used sparingly for specific data displays or code snippets where character alignment is critical.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.4 | -0.03px | `--text-caption` |
| body | 14px | 1.4 | -0.03px | `--text-body` |
| subheading | 18px | 1.35 | -0.03px | `--text-subheading` |
| heading-sm | 24px | 1.2 | -0.03px | `--text-heading-sm` |
| heading | 32px | 1.14 | -0.036px | `--text-heading` |
| heading-lg | 40px | 1.1 | -0.04px | `--text-heading-lg` |
| display | 72px | 1 | -0.05px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 8px

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 8 | 8px | `--spacing-8` |
| 16 | 16px | `--spacing-16` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 56 | 56px | `--spacing-56` |
| 120 | 120px | `--spacing-120` |

### Border Radius

| Element | Value |
|---------|-------|
| pill | 9999px |
| cards | 12px |
| badges | 16px |
| inputs | 0px |
| buttons | 12px |
| default | 8px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgb(85, 85, 85) 0px 0px 0px 10000px` | `--shadow-subtle` |
| subtle-2 | `rgb(34, 51, 34) 0px 0px 0px 10000px` | `--shadow-subtle-2` |
| subtle-3 | `rgb(17, 17, 17) 0px 0px 0px 10000px` | `--shadow-subtle-3` |

### Layout

- **Page max-width:** 1200px
- **Section gap:** 56px
- **Card padding:** 24px
- **Element gap:** 8px

## Components

### Primary Action Button
**Role:** High-emphasis interactive element

Filled with Cosmic Teal (#17d5ff) background and Midnight Graphite (#141a20) text, using a 12px border-radius, 12px vertical padding on 16px horizontal padding. Prominently guides user action.

### Ghost Button
**Role:** Secondary action or navigation

Transparent background with Midnight Graphite (#141a20) text and border, using a 12px border-radius, 12px vertical padding on 16px horizontal padding. Offers interaction without demanding primary attention.

### Text Link Button
**Role:** Tertiary action or inline navigation

No explicit background or border. Uses Midnight Graphite (#141a20) text with 8px horizontal padding. Appears as a simple text link that is subtly interactive.

### Transparent Card
**Role:** Informational grouping on hero/dark sections.

Semi-transparent background at rgba(255, 255, 255, 0.6) with 12px border-radius and 24px padding. Used for containing content over larger background imagery.

### Light Surface Card
**Role:** Default informational grouping on light sections.

Solid Cloud Canvas (#fafcfd) background, 0px border-radius, with 56px top and bottom padding. Used for large content blocks.

### Dark Surface Card
**Role:** Default informational grouping on dark sections.

Solid Midnight Graphite (#141a20) background, 0px border-radius, with 56px top and bottom padding. Used for large content blocks.

### New Feature Badge
**Role:** Indicator for new features/content.

Cosmic Teal (#17d5ff) background with Deep Teal (#13b1d4) color text, 4px border-radius and minimal padding (1.5px vertical, 4px horizontal).

### Nav Button
**Role:** Top-level navigation item

Transparent background with Midnight Graphite (#000000) text and 8px padding. Used in the main navigation bar.

## Do's and Don'ts

### Do
- Use Cosmic Teal (#17d5ff) for primary call-to-action buttons to ensure immediate visibility and signify interactive elements.
- Employ Midnight Graphite (#141a20) as the default text color on light backgrounds and Cloud Canvas (#fafcfd) for text on dark backgrounds to ensure high contrast.
- Apply ABCRepro with a letter-spacing of -0.0500em to all display-level headings (72px) to enhance visual density and distinctiveness.
- Maintain a compact element spacing of 8px (elementGap) between inline components and form elements to create a dense, functional interface.
- Round corners of interactive elements such as buttons and cards to 12px, creating a friendly and approachable feel.
- Utilize Cloud Canvas (#fafcfd) as the universal base background for default page sections and light content areas.
- Ensure all numbers use the "lnum" font feature setting for consistent monospaced tabular figures.

### Don't
- Avoid using saturated colors other than Cosmic Teal or Deep Teal for primary interactive elements; color should primarily be used for brand distinction, not excessive decoration.
- Do not introduce heavy shadows or strong borders for cards; rely on shifts in background tone (e.g., Midnight Graphite, Cloud Canvas, Light Mist) or subtle transparency to define surface layers.
- Refrain from using more than two levels of text hierarchy within a single content block to prevent overwhelming the user; prioritize clarity with body, subheading, and heading roles.
- Do not use letter-spacing values more open than -0.0300em for body text; the system maintains a compact, precise typographic rhythm.
- Avoid arbitrary border radii; adhere to the 12px for cards and buttons, 16px for large badges, and 8px for smaller interactive elements.
- Do not use pure white (#FFFFFF) or pure black (#000000) for primary canvas or text unless specifically for contrast in isolated components (e.g., specific icons); always favor the nuanced neutrals like Cloud Canvas and Midnight Graphite.
- Do not create hero sections that are full-bleed white backgrounds; hero sections should leverage background imagery or dark neutral tones with strong typography.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Cloud Canvas | `#fafcfd` | Primary page background, base for light sections. |
| 1 | Midnight Graphite | `#141a20` | Primary background for dark sections, elevated card surfaces within dark contexts. |
| 2 | Transparent Overlay | `#ffffff99` | Informational cards or overlays on image-heavy backgrounds. |
| 3 | Light Mist | `#dfe4ea` | Subtle UI elements, neutral component backgrounds, hover states. |

## Imagery

The imagery strategy features high-resolution photography primarily focused on human interaction with digital devices, specifically hands typing on keyboards or using cameras. Product screenshots are integrated contextually. All visuals are contained within the layout, often appearing as large background elements in hero sections with dark overlays. There is an absence of abstract illustrations or 3D renders. Icons are minimal, predominantly line-based, and monochrome, integrating seamlessly into the UI rather than asserting strong visual identity.

## Layout

The page primarily uses a max-width contained layout, centering content at approximately 1200px. The hero section breaks this containment by featuring a full-bleed dark background with a large, centered headline and subtext. Sections alternate between light (Cloud Canvas) and dark (Midnight Graphite) backgrounds, creating a distinct vertical rhythm. Content is generally arranged in centered stacks or two-column text-left/image-right patterns, with emphasis on clear visual hierarchy. Spacing between sections is generous, around 56px. Navigation is a sticky top bar with minimal styling.

## Agent Prompt Guide

**Quick Color Reference**
text: #141a20
background: #fafcfd
border: #3d4751
accent: #17d5ff
primary action: #17d5ff (filled action)

**3-5 Example Component Prompts**
*   Create a Primary Action Button: #17d5ff background, #000000 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
*   Design a feature card for a light section: Uses Cloud Canvas (#fafcfd) background, with a 12px border-radius, and 24px padding. Title is heading-sm (ABCRepro, 24px, weight 700, Midnight Graphite #141a20), body text is body (ABCRepro, 14px, weight 400, Steel Gray #3d4751). Contains a Ghost Button (transparent background, Midnight Graphite #141a20 text and border, 12px radius, 12px 16px padding).

## Similar Brands

- **loom.com** — Shares a similar light background, compact typography, and a single vibrant blue accent color for primary actions.
- **webflow.com** — Employs a clean, feature-focused layout with alternating light and dark sections and a controlled use of brand color for interactive elements.
- **discord.com** — Exhibits a dark-dominant UI with a single vivid accent color to highlight interactive elements and brand identity.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-graphite: #141a20;
  --color-cloud-canvas: #fafcfd;
  --color-ash-gray: #23313b;
  --color-steel-gray: #3d4751;
  --color-slate-blue: #4c5864;
  --color-light-mist: #dfe4ea;
  --color-cosmic-teal: #17d5ff;
  --color-deep-teal: #13b1d4;
  --color-overlay-shadow: #000000;

  /* Typography — Font Families */
  --font-abcrepro: 'ABCRepro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-abcrepromono: 'ABCReproMono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.4;
  --tracking-caption: -0.03px;
  --text-body: 14px;
  --leading-body: 1.4;
  --tracking-body: -0.03px;
  --text-subheading: 18px;
  --leading-subheading: 1.35;
  --tracking-subheading: -0.03px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: -0.03px;
  --text-heading: 32px;
  --leading-heading: 1.14;
  --tracking-heading: -0.036px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.04px;
  --text-display: 72px;
  --leading-display: 1;
  --tracking-display: -0.05px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-120: 120px;

  /* Layout */
  --page-max-width: 1200px;
  --section-gap: 56px;
  --card-padding: 24px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-pill: 9999px;
  --radius-cards: 12px;
  --radius-badges: 16px;
  --radius-inputs: 0px;
  --radius-buttons: 12px;
  --radius-default: 8px;

  /* Shadows */
  --shadow-subtle: rgb(85, 85, 85) 0px 0px 0px 10000px;
  --shadow-subtle-2: rgb(34, 51, 34) 0px 0px 0px 10000px;
  --shadow-subtle-3: rgb(17, 17, 17) 0px 0px 0px 10000px;

  /* Surfaces */
  --surface-cloud-canvas: #fafcfd;
  --surface-midnight-graphite: #141a20;
  --surface-transparent-overlay: #ffffff99;
  --surface-light-mist: #dfe4ea;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-graphite: #141a20;
  --color-cloud-canvas: #fafcfd;
  --color-ash-gray: #23313b;
  --color-steel-gray: #3d4751;
  --color-slate-blue: #4c5864;
  --color-light-mist: #dfe4ea;
  --color-cosmic-teal: #17d5ff;
  --color-deep-teal: #13b1d4;
  --color-overlay-shadow: #000000;

  /* Typography */
  --font-abcrepro: 'ABCRepro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-abcrepromono: 'ABCReproMono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.4;
  --tracking-caption: -0.03px;
  --text-body: 14px;
  --leading-body: 1.4;
  --tracking-body: -0.03px;
  --text-subheading: 18px;
  --leading-subheading: 1.35;
  --tracking-subheading: -0.03px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: -0.03px;
  --text-heading: 32px;
  --leading-heading: 1.14;
  --tracking-heading: -0.036px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.04px;
  --text-display: 72px;
  --leading-display: 1;
  --tracking-display: -0.05px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-120: 120px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-full: 9999px;

  /* Shadows */
  --shadow-subtle: rgb(85, 85, 85) 0px 0px 0px 10000px;
  --shadow-subtle-2: rgb(34, 51, 34) 0px 0px 0px 10000px;
  --shadow-subtle-3: rgb(17, 17, 17) 0px 0px 0px 10000px;
}
```

# INK — Style Reference
> Architectural blueprint on white marble. Precision, clarity, spaciousness, and carefully chosen details unfold across a pristine, light-drenched surface.

**Theme:** light

This system projects an image of understated luxury, prioritizing spaciousness and meticulous typography over vibrant visuals. The canvas of near-white (#E6DCD4) or pure white allows the refined, custom sans-serif to take center stage, creating a highly legible and authoritative tone. A distinct absence of shadows and geometric borders focuses attention on content through scale and precise placement, rather than overt styling.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Ink Black | `#2e2a2b` | `--color-ink-black` | Primary text, interactive elements, navigation links, and button outlines — defines the core legible content against light backgrounds. |
| Frost Canvas | `#ffffff` | `--color-frost-canvas` | Dominant page and component background. Its starkness emphasizes content and creates breathing room. |
| Warm Paper | `#e6dcd4` | `--color-warm-paper` | Alternative light background for subtle section shifts or specific footer areas, providing visual relief from pure white without introducing chromatic distraction. |
| Cool Stone | `#afa697` | `--color-cool-stone` | Secondary text, subheadings, and subtle accents. This near-gray provides a softer contrast than Ink Black, used for descriptive text. |
| Joby Aviation Sky | `#b6d0e2` | `--color-joby-aviation-sky` | Specific background color appearing in a unique asset (Joby Aviation section/image), not a system-wide accent. |

## Tokens — Typography

### Good Sans — The singular typeface for all content roles, from body to display. Its custom nature supports the brand's identity through consistent, sophisticated readability. The moderate weights maintain an understated authority, avoiding heavy-handedness. · `--font-good-sans`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 18px, 22px, 27px, 60px
- **Line height:** 1.00, 1.09, 1.14, 1.25, 1.31, 1.60, 1.75
- **Letter spacing:** normal
- **Role:** The singular typeface for all content roles, from body to display. Its custom nature supports the brand's identity through consistent, sophisticated readability. The moderate weights maintain an understated authority, avoiding heavy-handedness.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body-sm | 18px | 1.75 | — | `--text-body-sm` |
| body | 22px | 1.6 | — | `--text-body` |
| subheading | 27px | 1.31 | — | `--text-subheading` |
| display | 60px | 1 | — | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 8px

**Density:** spacious

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 8 | 8px | `--spacing-8` |
| 16 | 16px | `--spacing-16` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 64 | 64px | `--spacing-64` |
| 160 | 160px | `--spacing-160` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 0px |
| inputs | 0px |
| buttons | 0px |
| navPills | 100px |

### Layout

- **Section gap:** 160px
- **Card padding:** 64px
- **Element gap:** 32px

## Components

### Ghost Button
**Role:** Interactive elements, navigation, and 'Back to top' calls to action.

Transparent background with 'Ink Black' (#2e2a2b) text and a 'Ink Black' (#2e2a2b) bottom border (1px). No border radius, emphasizing a crisp, direct interaction.

### Navigation Pill Indicator
**Role:** Active state or selected item indicator within navigation menus.

Rendered as a 100px border-radius shape, likely for visual highlighting of the current page or selection. Color is inferred to be a subtle fill given its high radius in 'nav' context.

### Standard Input Field
**Role:** Form inputs such as email subscription fields.

Background is transparent (rgba(0,0,0,0)), text is 'Ink Black' (#000000). A 1px top border of 'Ink Black' (#000000) is present, paired with padding of 1px top/bottom and 2px left/right. No border radius, maintaining the system's sharp aesthetic.

## Do's and Don'ts

### Do
- Prioritize 'Frost Canvas' (#ffffff) or 'Warm Paper' (#e6dcd4) as primary backgrounds for all layouts to maintain a bright, expansive feel.
- Use 'Ink Black' (#2e2a2b) for all primary text elements, interactive components, and critical information for maximum legibility.
- Employ spacious vertical gaps between sections, defaulting to '160px' to create significant breathing room and separation.
- Maintain consistently sharp 0px border radii for all primary UI components like buttons and cards, enforcing a precise, architectural aesthetic.
- Utilize 'Cool Stone' (#afa697) for secondary textual elements such as subheadings or descriptive text to introduce visual hierarchy without high contrast.
- Ensure all interactive elements and navigation links use the 'Good Sans' typeface at designated weights and sizes, reinforcing brand consistency.

### Don't
- Avoid the integration of heavy shadows or complex elevation systems; the design relies on spacing and color contrast for depth.
- Do not introduce overtly rounded elements beyond the specific '100px' radius navigation pill, to preserve the system's sharp, precise nature.
- Refrain from using highly saturated accent colors in prominent UI roles; colorful elements are primarily decorative content, not interactive indicators.
- Do not use multiple font families; all textual elements must strictly adhere to the 'Good Sans' typeface.
- Avoid dense, information-packed sections; embrace the generous spacing guidelines to ensure content feels open and uncluttered.

## Imagery

The site primarily uses high-quality, product-focused or project-specific photography displayed full-bleed in hero sections and content blocks. Images are contained with sharp edges, often acting as showcases for client work. There's an absence of playful illustrations or excessive icons, reinforcing a serious, professional tone. The images serve to illustrate and contextualize the studio's projects rather than merely decorate.

## Layout

The layout is primarily centered and contained, although hero sections can be full-bleed with large, impactful imagery. Content is arranged with ample vertical spacing, giving a sense of gravitas and making each section feel distinct. The page model appears to be a sequence of large, horizontally aligned content blocks, often showcasing a project title and description, followed by a full-width image or video. There's a clear header with minimal navigation and a generous footer, emphasizing content over persistent UI elements.

## Agent Prompt Guide

### Quick Color Reference
- Text: #2e2a2b
- Background: #ffffff
- Secondary Background: #e6dcd4
- Secondary Text: #afa697
- Accent Background (example, often project-specific): #b6d0e2

### 3-5 Example Component Prompts
1. Create a primary headline: 'Good Sans' 60px, weight 400, color '#2e2a2b', line-height 1.0, on a '#ffffff' background.
2. Generate a ghost button: Text 'Good Sans' 18px, weight 400, color '#2e2a2b', with a transparent background, 1px bottom border '#2e2a2b', and 0px border radius. Padding 0px all around.
3. Design a descriptive body paragraph: 'Good Sans' 18px, weight 400, color '#afa697', line-height 1.75, on a '#ffffff' background, with 32px margin-bottom.
4. Construct an input field for email: Placeholder text 'Good Sans' 18px, weight 400, color '#2e2a2b', transparent background, 1px top border '#000000', with 1px vertical and 2px horizontal padding, 0px border radius.

## Similar Brands

- **AIGA** — Shares a classic, spacious, and type-driven aesthetic with a focus on editorial content and strong, uncluttered layouts.
- **Pentagram** — Features a similar emphasis on high-quality project imagery, clean typography, and a minimalist design approach that lets the work speak for itself.
- **Gusto** — Uses spacious design, clear hierarchy, and a restrained color palette to convey professionalism and focus on content, albeit with slightly more colorful accents.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-ink-black: #2e2a2b;
  --color-frost-canvas: #ffffff;
  --color-warm-paper: #e6dcd4;
  --color-cool-stone: #afa697;
  --color-joby-aviation-sky: #b6d0e2;

  /* Typography — Font Families */
  --font-good-sans: 'Good Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-sm: 18px;
  --leading-body-sm: 1.75;
  --text-body: 22px;
  --leading-body: 1.6;
  --text-subheading: 27px;
  --leading-subheading: 1.31;
  --text-display: 60px;
  --leading-display: 1;

  /* Typography — Weights */
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-64: 64px;
  --spacing-160: 160px;

  /* Layout */
  --section-gap: 160px;
  --card-padding: 64px;
  --element-gap: 32px;

  /* Border Radius */
  --radius-full: 100px;

  /* Named Radii */
  --radius-cards: 0px;
  --radius-inputs: 0px;
  --radius-buttons: 0px;
  --radius-navpills: 100px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-ink-black: #2e2a2b;
  --color-frost-canvas: #ffffff;
  --color-warm-paper: #e6dcd4;
  --color-cool-stone: #afa697;
  --color-joby-aviation-sky: #b6d0e2;

  /* Typography */
  --font-good-sans: 'Good Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-sm: 18px;
  --leading-body-sm: 1.75;
  --text-body: 22px;
  --leading-body: 1.6;
  --text-subheading: 27px;
  --leading-subheading: 1.31;
  --text-display: 60px;
  --leading-display: 1;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-64: 64px;
  --spacing-160: 160px;

  /* Border Radius */
  --radius-full: 100px;
}
```

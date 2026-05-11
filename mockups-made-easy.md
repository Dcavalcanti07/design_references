# Mockups made easy — Style Reference
> blueprint on white marble

**Theme:** light

Maneken employs a crisp, purposeful design language that balances robust product presentation with a clean, light interface. Strong, compact typography anchors key messages, while a singular vivid blue accent color highlights interactive elements and calls to action. Surfaces are typically flat and highly contrasting using white, black, and light gray, with occasional subtle dark cards setting off mockups. The overall feeling is direct and functional, designed to keep focus on the visual content.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#000000` | `--color-midnight-ink` | Primary text, strong headings, borders, and main UI outlines — provides high contrast against light surfaces |
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card surfaces, white button text — forms the dominant base of the light theme |
| Deep Slate | `#10151c` | `--color-deep-slate` | Dark surface backgrounds for content blocks, card backgrounds |
| Soft Fog | `#f4f4f4` | `--color-soft-fog` | Secondary background color for subtle section breaks and card surfaces, creating a stepped depth |
| Light Steel | `#eaeaea` | `--color-light-steel` | Subtle borders and dividers for UI elements |
| Muted Stone | `#86868b` | `--color-muted-stone` | Secondary text, muted descriptions, and subheadings; provides a softer contrast |
| Cadet Blue | `#0050b7` | `--color-cadet-blue` | Primary action buttons, interactive elements, accent strokes, and branding — the single, vivid call-to-action color |
| Dark Charcoal | `#3e3e3e` | `--color-dark-charcoal` | Neutral button treatment for secondary actions and selected controls. |

## Tokens — Typography

### Inter — General UI text, body copy, navigation, buttons, and form labels — provides a robust, contemporary sans-serif foundation. · `--font-inter`
- **Substitute:** system-ui
- **Weights:** 400, 500, 600, 800
- **Sizes:** 10px, 14px, 15px, 18px, 24px, 28px, 40px, 200px
- **Line height:** 1.00, 1.20, 1.25, 1.40
- **Letter spacing:** normal
- **Role:** General UI text, body copy, navigation, buttons, and form labels — provides a robust, contemporary sans-serif foundation.

### TWKEverett — Key headings and hero text — this custom typeface delivers a distinctive, strong brand voice with its compact, assertive forms. · `--font-twkeverett`
- **Substitute:** Montserrat
- **Weights:** 400, 500
- **Sizes:** 16px, 22px, 24px, 28px, 55px, 60px, 77px, 110px
- **Line height:** 1.00, 1.10, 1.20, 1.45
- **Letter spacing:** normal
- **Role:** Key headings and hero text — this custom typeface delivers a distinctive, strong brand voice with its compact, assertive forms.

### Arial — Minimal usage for specific input fields, likely a fallback or system integration. · `--font-arial`
- **Substitute:** Helvetica Neue
- **Weights:** 400, 500
- **Sizes:** 13px
- **Line height:** 1.20
- **Letter spacing:** normal
- **Role:** Minimal usage for specific input fields, likely a fallback or system integration.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.4 | — | `--text-caption` |
| body-sm | 14px | 1.4 | — | `--text-body-sm` |
| subheading | 18px | 1.2 | — | `--text-subheading` |
| heading-sm | 24px | 1.2 | — | `--text-heading-sm` |
| heading | 40px | 1.2 | — | `--text-heading` |
| heading-lg | 55px | 1 | — | `--text-heading-lg` |
| display | 110px | 1 | — | `--text-display` |

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
| 22 | 22px | `--spacing-22` |
| 24 | 24px | `--spacing-24` |
| 28 | 28px | `--spacing-28` |
| 30 | 30px | `--spacing-30` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 50 | 50px | `--spacing-50` |
| 80 | 80px | `--spacing-80` |
| 140 | 140px | `--spacing-140` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 10px |
| images | 10px |
| buttons | 10px |
| circular | 100px |
| heroCards | 15px |
| cookiesBanner | 12px |
| smallElements | 3px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| xl | `rgba(0, 0, 0, 0.01) 0px 90px 40px 0px, rgba(0, 0, 0, 0.05...` | `--shadow-xl` |
| xl-2 | `rgba(0, 0, 0, 0.01) 0px 550px 220px 0px, rgba(0, 0, 0, 0....` | `--shadow-xl-2` |

### Layout

- **Section gap:** 80px
- **Card padding:** 10px
- **Element gap:** 10px

## Components

### Primary Action Button
**Role:** Main call to action

Filled button with Cadet Blue (#0050b7) background, Canvas White (#ffffff) text, and 10px border-radius. Padding of 20px horizontal and 0px vertical (content-driven height).

### Image Card (Base)
**Role:** Displaying product mockups

Transparent background, 10px border-radius, with 10px padding on all sides. Used for gallery images.

### Feature Highlight Card (Light)
**Role:** Section highlight cards

Soft Fog (#f4f4f4) background, 15px border-radius. Features large vertical padding of 140px, and horizontal padding of 80px.

### Feature Highlight Card (Dark)
**Role:** Section highlight cards

Deep Slate (#10151c) background, 15px border-radius. Features large vertical padding of 140px, and horizontal padding of 80px.

### Cookie Consent Button
**Role:** Secondary action for dismissals

Dark Charcoal (#3e3e3e) background, Canvas White (#ffffff) text, and a distinct 12px border-radius, with 16px horizontal padding.

## Do's and Don'ts

### Do
- Use Cadet Blue (#0050b7) exclusively for primary interactive elements and brand accents.
- Apply 10px border-radius uniformly to all buttons, image containers, and navigation items for consistency.
- Employ TWKEverett for all primary headings (55px-110px) to convey the brand's distinct voice, and Inter for all body text and UI elements.
- Maintain high contrast text with Midnight Ink (#000000) on Canvas White (#ffffff) or Soft Fog (#f4f4f4) backgrounds.
- Utilize Soft Fog (#f4f4f4) and Deep Slate (#10151c) as alternating background colors to delineate sections visually.
- Structure layouts with a default element gap of 10px for tight, compact arrangements.
- For elevation emphasis, use the specific shadow `rgba(0, 0, 0, 0.01) 0px 550px 220px 0px, rgba(0, 0, 0, 0.05) 0px 310px 190px 0px, rgba(0, 0, 0, 0.09) 0px 140px 140px 0px, rgba(0, 0, 0, 0.1) 0px 35px 75px 0px` for elevated cards.

### Don't
- Do not introduce new saturated colors beyond Cadet Blue; color should be used sparingly and functionally.
- Avoid using drop shadows for most UI elements; surfaces are largely flat with elevation reserved for specific content blocks.
- Do not deviate from the established typefaces (Inter and TWKEverett) and their prescribed roles.
- Avoid overly spacious layouts; the system favors a compact and dense presentation of information and imagery.
- Do not use generic border-radii; adhere to 10px for most elements, 15px for large content cards, and 12px for specific secondary actions.
- Refrain from using gradients or complex textures on surfaces; maintain a clean, solid color aesthetic.
- Do not use a narrow fixed-width container for the overall page content; allow for full-bleed sections where appropriate.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas White | `#ffffff` | Base page background and primary card surfaces. |
| 1 | Soft Fog | `#f4f4f4` | Secondary background for distinct content sections and elevated card surfaces. |
| 2 | Deep Slate | `#10151c` | Dark mode content cards and background surfaces, creating strong contrast for visual content. |

## Elevation

- **Image Card (Elevated):** `rgba(0, 0, 0, 0.01) 0px 90px 40px 0px, rgba(0, 0, 0, 0.05) 0px 50px 30px 0px, rgba(0, 0, 0, 0.09) 0px 20px 20px 0px, rgba(0, 0, 0, 0.1) 0px 6px 10px 0px`
- **Product Display Card:** `rgba(0, 0, 0, 0.01) 0px 550px 220px 0px, rgba(0, 0, 0, 0.05) 0px 310px 190px 0px, rgba(0, 0, 0, 0.09) 0px 140px 140px 0px, rgba(0, 0, 0, 0.1) 0px 35px 75px 0px`

## Imagery

This site features product-focused photography and screenshots, often depicting physical mockups in real-world contexts or digital mockups within device frames. Images are generally contained within grid cells and utilize a 10px border-radius, maintaining a consistent UI shape. Some product display cards use deep, layered shadows to give a sense of elevation and presence, making the mockups pop off the page. The imagery is primarily functional and explanatory, showcasing the product capabilities and user output rather than decorative atmosphere.

## Layout

The page structure is primarily full-bleed, with a centered max-width content area for text and interactive elements. The hero section features a large, centered hero headline (`Mockups made easy`) over a default white background. Content sections beneath often alternate between tight image grids and more expansive text blocks. Image galleries are frequently arranged in a dense, compact grid without explicit padding or borders between images. Navigation is a simple top bar with left-aligned branding and right-aligned links and primary action. Vertical spacing between sections is moderately generous, contributing to a clean content flow.

## Agent Prompt Guide

Quick Color Reference: 
text: #000000
background: #ffffff
border: #eaeaea
accent: #0050b7
primary action: #0050b7 (filled action)

Example Component Prompts:
Create a hero section with a centered headline: 'Mockups made easy' in TWKEverett, size 77px, lineHeight 1.0, Midnight Ink (#000000). Below it, a subheading 'The browser powered mockup editor' in Inter, size 18px, lineHeight 1.2, Muted Stone (#86868b). Centered beneath, a Primary Action Button labeled 'Start for Free' (background: #0050b7, text: #ffffff, radius: 10px, horizontal padding: 20px, vertical padding: 0px).

Create a Feature Highlight Card (Light): Background Soft Fog (#f4f4f4), radius 15px, padding 140px vertical, 80px horizontal. Inside, a heading 'Our creators' in TWKEverett, size 40px, lineHeight 1.2, Midnight Ink (#000000), followed by body text in Inter, size 15px, lineHeight 1.4, Muted Stone (#86868b).

Create an Image Card for a gallery: Background transparent, radius 10px, padding 10px. The image inside should have the shadow `rgba(0, 0, 0, 0.01) 0px 90px 40px 0px, rgba(0, 0, 0, 0.05) 0px 50px 30px 0px, rgba(0, 0, 0, 0.09) 0px 20px 20px 0px, rgba(0, 0, 0, 0.1) 0px 6px 10px 0px`.

## Similar Brands

- **Framer** — Clean, predominantly white interface with emphasis on visual content and strong, modern typography.
- **Maze** — Minimalist layout, strong use of a single accent color for primary actions, and clear typographic hierarchy.
- **Webflow** — Full-bleed sections, focus on product-driven visuals, and compact UI elements within a modern, light theme.
- **Loom** — Direct, functional aesthetic with high contrast text, and a prominent blue for interactive elements.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-canvas-white: #ffffff;
  --color-deep-slate: #10151c;
  --color-soft-fog: #f4f4f4;
  --color-light-steel: #eaeaea;
  --color-muted-stone: #86868b;
  --color-cadet-blue: #0050b7;
  --color-dark-charcoal: #3e3e3e;

  /* Typography — Font Families */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-twkeverett: 'TWKEverett', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.4;
  --text-body-sm: 14px;
  --leading-body-sm: 1.4;
  --text-subheading: 18px;
  --leading-subheading: 1.2;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.2;
  --text-heading: 40px;
  --leading-heading: 1.2;
  --text-heading-lg: 55px;
  --leading-heading-lg: 1;
  --text-display: 110px;
  --leading-display: 1;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-extrabold: 800;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-22: 22px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-30: 30px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-50: 50px;
  --spacing-80: 80px;
  --spacing-140: 140px;

  /* Layout */
  --section-gap: 80px;
  --card-padding: 10px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-sm: 3px;
  --radius-lg: 10px;
  --radius-xl: 15px;
  --radius-2xl: 18px;
  --radius-full: 100px;

  /* Named Radii */
  --radius-cards: 10px;
  --radius-images: 10px;
  --radius-buttons: 10px;
  --radius-circular: 100px;
  --radius-herocards: 15px;
  --radius-cookiesbanner: 12px;
  --radius-smallelements: 3px;

  /* Shadows */
  --shadow-xl: rgba(0, 0, 0, 0.01) 0px 90px 40px 0px, rgba(0, 0, 0, 0.05) 0px 50px 30px 0px, rgba(0, 0, 0, 0.09) 0px 20px 20px 0px, rgba(0, 0, 0, 0.1) 0px 6px 10px 0px;
  --shadow-xl-2: rgba(0, 0, 0, 0.01) 0px 550px 220px 0px, rgba(0, 0, 0, 0.05) 0px 310px 190px 0px, rgba(0, 0, 0, 0.09) 0px 140px 140px 0px, rgba(0, 0, 0, 0.1) 0px 35px 75px 0px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-soft-fog: #f4f4f4;
  --surface-deep-slate: #10151c;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-canvas-white: #ffffff;
  --color-deep-slate: #10151c;
  --color-soft-fog: #f4f4f4;
  --color-light-steel: #eaeaea;
  --color-muted-stone: #86868b;
  --color-cadet-blue: #0050b7;
  --color-dark-charcoal: #3e3e3e;

  /* Typography */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-twkeverett: 'TWKEverett', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.4;
  --text-body-sm: 14px;
  --leading-body-sm: 1.4;
  --text-subheading: 18px;
  --leading-subheading: 1.2;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.2;
  --text-heading: 40px;
  --leading-heading: 1.2;
  --text-heading-lg: 55px;
  --leading-heading-lg: 1;
  --text-display: 110px;
  --leading-display: 1;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-22: 22px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-30: 30px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-50: 50px;
  --spacing-80: 80px;
  --spacing-140: 140px;

  /* Border Radius */
  --radius-sm: 3px;
  --radius-lg: 10px;
  --radius-xl: 15px;
  --radius-2xl: 18px;
  --radius-full: 100px;

  /* Shadows */
  --shadow-xl: rgba(0, 0, 0, 0.01) 0px 90px 40px 0px, rgba(0, 0, 0, 0.05) 0px 50px 30px 0px, rgba(0, 0, 0, 0.09) 0px 20px 20px 0px, rgba(0, 0, 0, 0.1) 0px 6px 10px 0px;
  --shadow-xl-2: rgba(0, 0, 0, 0.01) 0px 550px 220px 0px, rgba(0, 0, 0, 0.05) 0px 310px 190px 0px, rgba(0, 0, 0, 0.09) 0px 140px 140px 0px, rgba(0, 0, 0, 0.1) 0px 35px 75px 0px;
}
```

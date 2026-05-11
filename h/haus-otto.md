# Haus Otto — Style Reference
> Gallery Wall Monolith — A single, massive black typographic form commands attention against an expansive white background.

**Theme:** light

This system projects an aesthetic of stark minimalism and purposeful absence, like a gallery wall with a single, monumental exhibit. It leverages extreme contrast and sparse visual elements to emphasize a singular brand presence. The visual impact is created by the massive, centrally-aligned, uppercase sans-serif typography on an absolute white canvas, demanding full attention without clutter.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Absolute White | `#ffffff` | `--color-absolute-white` | Page backgrounds, significant surface areas, text on accent blocks. |
| Deep Black | `#000000` | `--color-deep-black` | Primary text, borders, interactive elements like button backgrounds, creating maximum contrast against the white canvas. |
| Desert Ochre | `#af7653` | `--color-desert-ochre` | Subtle, very-low prominence accent color, used sparingly for specific states or indicators, providing a warm, earthy counterpoint to the stark monochromes. |

## Tokens — Typography

### Monument-Regular — General body text, navigation links, and smaller headings. The consistently regular (400) weight maintains a sense of understated authority across all informational text. · `--font-monument-regular`
- **Substitute:** IBM Plex Sans
- **Weights:** 400
- **Sizes:** 13px, 20px, 23px
- **Line height:** 1.15, 1.16, 1.23, 1.77, 2.00
- **Letter spacing:** normal
- **Role:** General body text, navigation links, and smaller headings. The consistently regular (400) weight maintains a sense of understated authority across all informational text.

### Monument-Medium — Dominant display headlines. The monumental size at weight 400 with tight letter-spacing is the signature visual element, asserting brand identity through sheer scale rather than bolding or expressive typefaces. · `--font-monument-medium`
- **Substitute:** IBM Plex Sans
- **Weights:** 400
- **Sizes:** 216px
- **Line height:** normal
- **Letter spacing:** -0.033em
- **Role:** Dominant display headlines. The monumental size at weight 400 with tight letter-spacing is the signature visual element, asserting brand identity through sheer scale rather than bolding or expressive typefaces.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 13px | 1.15 | — | `--text-caption` |
| body | 20px | 1.16 | — | `--text-body` |
| subheading | 23px | 1.23 | — | `--text-subheading` |
| display | 216px | 1 | -0.033px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 5 | 5px | `--spacing-5` |
| 8 | 8px | `--spacing-8` |
| 10 | 10px | `--spacing-10` |
| 12 | 12px | `--spacing-12` |
| 20 | 20px | `--spacing-20` |
| 30 | 30px | `--spacing-30` |

### Border Radius

| Element | Value |
|---------|-------|
| buttons | 0px |
| default | 0px |

### Layout

- **Section gap:** 30px
- **Card padding:** 12px
- **Element gap:** 4px

## Components

### Global Navigation Link
**Role:** Primary site navigation

Text in Monument-Regular, 13px, #000000, 1.15 line height. No visible active states or backgrounds, relying on context for interaction.

### Main Display Headline
**Role:** Brand identity, section titles

Monument-Medium, 216px, #000000, normal line height, letter-spacing -0.033em. Centered and massive, this is the core visual identifier.

### Cookie Consent Button (Default)
**Role:** User interaction, consent actions

Monument-Regular, 13px text, 4px padding-top/bottom, 8px padding-left/right, #000000 background, #ffffff text. Square, no radius.

### Cookie Consent Button (Hover/Inactive)
**Role:** User interaction, consent actions

Monument-Regular, 13px text, no background, #000000 text. Simple text-only button for secondary actions.

### Footer Link / Meta Info
**Role:** Secondary navigation and legal text

Monument-Regular, 13px text, #000000, 1.15 line height. Identical to main nav links, appearing understated at the bottom.

## Do's and Don'ts

### Do
- Prioritize extreme visual contrast: #000000 text on #ffffff backgrounds, or vice-versa, for all core content.
- Use Monument-Medium at a monumental scale (216px) with tight letter-spacing (-0.033em) for key brand or section headings, ensuring singular visual impact.
- Maintain a strict achromatic palette, introducing Desert Ochre (#af7653) only for minimal accentuation on extremely low-prominence elements.
- Employ the 4px base unit for all spacing, particularly in elemental gaps, using tokens like 3px, 4px, 5px, 8px, 12px, 20px, 30px.
- All interactive elements, including buttons, must appear as sharp, unrounded rectangles, reinforcing a precise and unembellished aesthetic.
- Implement the 13px Monument-Regular type for all body copy and navigation, maintaining consistency and an understated, informational tone.

### Don't
- Avoid decorative elements like shadows, gradients, or complex borders; the design relies on purity of form and stark contrast.
- Do not introduce additional saturated colors beyond the very limited use of Desert Ochre (#af7653); maintain the monochrome discipline.
- Never use rounded corners on any element; all shapes must be rectilinear, reflecting rigidity and structure.
- Refrain from using bold or heavy font weights; the visual weight is achieved through size and contrast, not typographic emphasis.
- Do not deviate from the specified tight letter-spacing for display typography or normal letter-spacing for body text; typographic precision is key.
- Avoid complex layouts or multi-column grids that would dilute the singular focus; prefer centered or directly aligned compositions.

## Imagery

The site uses no visible raster imagery or illustrations. Its visual language relies exclusively on typography and whitespace. The absence of images reinforces the stark, minimalist, and conceptual nature of the brand, directing focus entirely onto textual information and the brand's name as a monumental graphic element. Icons are also absent; interaction cues are purely textual (Yes, No, More, Year ↓).

## Layout

The page exhibits a full-bleed, unconstrained layout, meaning elements are not restricted by a maximum content width, though content generally appears centrally aligned or to the far edges. The hero section is dominated by a singularly massive, centered typographic element, covering most of the viewport. Section rhythm is sparse, primarily defined by vast expanses of white space separating minimal textual blocks. Content is arranged in stacked, centered blocks, with some elements (like cookie consent) pinned to the page bottom. Navigation is minimal, consisting of small text links at the top-left and bottom-right corners, not occupying a dedicated sticky header or sidebar.

## Agent Prompt Guide

### Quick Color Reference
- Text: #000000 (Deep Black)
- Background: #ffffff (Absolute White)
- Accent: #af7653 (Desert Ochre)
- Button Background: #000000 (Deep Black)
- Button Text: #ffffff (Absolute White)

### 3-5 Example Component Prompts
1. Create a cookie consent bar pinned to the bottom of the viewport: background Absolute White, text Deep Black, size 13px Monument-Regular. Include a 'Yes' button with an Deep Black background, Absolute White text, no border-radius, and 4px vertical / 8px horizontal padding. The 'No' button is text-only, Deep Black, no background, 4px vertical / 8px horizontal padding. Element gaps are 3px.
2. Design a primary page header for 'Haus Otto' centered in the viewport, using Monument-Medium, 216px, Deep Black, normal line-height, and -0.033em letter-spacing.
3. Implement a footer section with two links: 'Year ↓' and 'Presskit', both using Monument-Regular, 13px, Deep Black. Space elements 20px apart horizontally.

## Similar Brands

- **A.P.C.** — Similar minimalist, stark aesthetic with heavy reliance on black and white, and precise, unembellished typography.
- **COS** — Shares a clean, modern aesthetic with ample negative space and a focus on essential elements, often featuring large typography.
- **The Row** — Exhibits a high-end, extremely minimalist, and almost austere design, prioritizing content over decorative UI.
- **Acne Studios** — Often uses bold, stark typography and a clean, almost art-gallery-like presentation with limited color palettes.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-absolute-white: #ffffff;
  --color-deep-black: #000000;
  --color-desert-ochre: #af7653;

  /* Typography — Font Families */
  --font-monument-regular: 'Monument-Regular', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-monument-medium: 'Monument-Medium', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 1.15;
  --text-body: 20px;
  --leading-body: 1.16;
  --text-subheading: 23px;
  --leading-subheading: 1.23;
  --text-display: 216px;
  --leading-display: 1;
  --tracking-display: -0.033px;

  /* Typography — Weights */
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-20: 20px;
  --spacing-30: 30px;

  /* Layout */
  --section-gap: 30px;
  --card-padding: 12px;
  --element-gap: 4px;

  /* Named Radii */
  --radius-buttons: 0px;
  --radius-default: 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-absolute-white: #ffffff;
  --color-deep-black: #000000;
  --color-desert-ochre: #af7653;

  /* Typography */
  --font-monument-regular: 'Monument-Regular', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-monument-medium: 'Monument-Medium', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 1.15;
  --text-body: 20px;
  --leading-body: 1.16;
  --text-subheading: 23px;
  --leading-subheading: 1.23;
  --text-display: 216px;
  --leading-display: 1;
  --tracking-display: -0.033px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-20: 20px;
  --spacing-30: 30px;
}
```

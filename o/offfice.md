# OFFFICE : — Style Reference
> Black Box Gallery; objects artfully framed within a deep, dark void, highlighted by stark text.

**Theme:** dark

This design system evokes a moody, high-end gallery experience where objects are presented with sculptural focus. The stark black background and minimal typographic hierarchy create a sophisticated, almost reverent atmosphere, allowing the furniture pieces to command attention through their form and subtle shading. Predominantly large, custom typography dominates the layout, serving as both content and graphic element, making the interface feel less like a website and more like a curated exhibition space. The limited interactivity is precisely indicated by subtle text changes, maintaining an air of exclusivity and quiet contemplation.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Void Black | `#111111` | `--color-void-black` | Primary background for all surfaces, creating a deep, uniform canvas. |
| Exhibition White | `#fefefe` | `--color-exhibition-white` | Primary text color for headlines, body copy, and interactive elements. Its near-pure white provides maximum contrast against the Void Black, ensuring legibility and drama. |

## Tokens — Typography

### ak — The primary typeface for all content, from navigation and body copy to prominent heroes. Its characteristic wide spacing and clean geometry define the system's voice, particularly at large sizes where it transforms into a graphic element. · `--font-ak`
- **Substitute:** Montserrat
- **Weights:** 400, 700
- **Sizes:** 12px, 14px, 18px, 20px, 58px, 216px
- **Line height:** 0.80, 0.90, 1.00, 1.10, 1.33, 1.40, 1.50, 1.56
- **Letter spacing:** normal
- **Role:** The primary typeface for all content, from navigation and body copy to prominent heroes. Its characteristic wide spacing and clean geometry define the system's voice, particularly at large sizes where it transforms into a graphic element.

### gs — Used sparingly for specific nav elements and occasional large display text. Its mono-spaced, technical aesthetic offers a subtle contrast and contributes to the gallery-like information display. · `--font-gs`
- **Substitute:** Roboto Mono
- **Weights:** 400
- **Sizes:** 12px, 72px
- **Line height:** 0.90, 1.33
- **Letter spacing:** normal
- **Role:** Used sparingly for specific nav elements and occasional large display text. Its mono-spaced, technical aesthetic offers a subtle contrast and contributes to the gallery-like information display.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.56 | — | `--text-caption` |
| body | 14px | 1.56 | — | `--text-body` |
| subheading | 18px | 1.5 | — | `--text-subheading` |
| heading | 58px | 0.9 | — | `--text-heading` |
| display | 216px | 0.8 | — | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 8px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 8 | 8px | `--spacing-8` |
| 16 | 16px | `--spacing-16` |
| 32 | 32px | `--spacing-32` |

### Border Radius

| Element | Value |
|---------|-------|
| all | 0px |

### Layout

- **Section gap:** 64px
- **Card padding:** 32px
- **Element gap:** 8px

## Components

### Navigation Link
**Role:** Interactive text link

Text link using ak font, 12px, weight 400, in Exhibition White (#fefefe). No underline by default; hover state is implied by a slight increase in visual prominence, rather than a color change.

### Hero Headline
**Role:** Dominant page title

Large text using ak font, 216px, weight 400, in Exhibition White (#fefefe), with extremely tight line height (0.80) to overlap characters vertically, creating a dense typographic block.

### Section Heading
**Role:** Main section titles

Headlines using ak font, 58px, weight 400, in Exhibition White (#fefefe), leveraging tight line height (0.90) for a compact appearance.

### Body Text
**Role:** Standard paragraph text

Text using ak font, 14px, weight 400, in Exhibition White (#fefefe), with a comfortable line height (1.56) for readability against the dark background.

### Small Detail Text
**Role:** Metadata or secondary information

Text using ak font, 12px, weight 400, in Exhibition White (#fefefe), often used for dates, categories, or subtle descriptions.

### Project Title (List)
**Role:** Items in a project list

Text using ak font, 58px, weight 400, in Exhibition White (#fefefe), with a line height of 0.90. These titles often appear semi-transparently or with reduced contrast to emphasize the current selection.

## Do's and Don'ts

### Do
- Prioritize Void Black (#111111) for all backgrounds to maintain visual depth and focus.
- Use Exhibition White (#fefefe) exclusively for all text and interactive elements to maintain high contrast and sophistication.
- Employ the ak font family for all typographic elements, leveraging its wide character spacing and varied optical sizes.
- Utilize ak 216px (weight 400, lineHeight 0.80) as a dominant graphic element for hero sections.
- Maintain strict typographic hierarchy by only using ak 58px, weight 400, for major section headings.
- Ensure all interactive text elements use ak 12px, weight 400, in Exhibition White, implying interactivity through context rather than overt styling (like underlines or strong color changes).

### Don't
- Do not introduce any additional background colors; maintain the pure Void Black (#111111) canvas.
- Avoid using drop shadows or excessive borders; depth is established through contrasting type sizes and element placement.
- Do not use highly saturated colors for accents; the aesthetic relies on a monochromatic palette with subtle emphasis.
- Do not apply rounded corners to any UI elements; all corners should be sharp 0px radius.
- Avoid using multiple font families beyond 'ak' and 'gs'; consistency in typography is crucial.
- Do not use generic button styles; interactivity is conveyed through text links and subtle text transformations.

## Imagery

The visual language is characterized by high-fidelity, monochromatic 3D renders of furniture pieces. These images are presented as central, hero elements, often against the deep Void Black background, giving them a sculptural, art-piece quality. They are typically contained within their compositional space without masks or overlapping, serving an explanatory and aesthetic role by showcasing product forms. The density is image-heavy in sections, with large product visuals dominating the screen.

## Layout

The page maintains a full-bleed layout, primarily dark-themed, without a fixed `pageMaxWidth`. The hero section features oversized, visually impactful typography laid over a central 3D product render. Content sections are primarily stacked vertically with generous `sectionGap`s, often presenting text beside or above the product imagery. Navigation is a minimal top bar. The overall impression is one of spaciousness and deliberate presentation, with elements given ample room to breathe within the dark canvas.

## Agent Prompt Guide

### Quick Color Reference
- Text: #fefefe (Exhibition White)
- Background: #111111 (Void Black)
- CTA (implied): #fefefe (Exhibition White)
- Border: None (0px)
- Accent: None (monochromatic)

### 3-5 Example Component Prompts
1.  **Create a full-screen hero section:** background is Void Black (#111111). Main headline 'OFFICE FOR' using ak font, 216px, weight 400, #fefefe, lineHeight 0.80. Sub-headline 'FUTURE LIVING DESIGN RESEARCH STUDIO...' using ak font, 14px, weight 400, #fefefe, lineHeight 1.56. Center a 3D monochromatic furniture render as a hero image, ensuring it is framed by the dark background.
2.  **Generate a navigation bar:** background Void Black (#111111). Left links 'offfice' and 'studio' using ak font, 12px, weight 400, #fefefe. Right link 'GET IN TOUCH' using ak font, 12px, weight 400, #fefefe. All links should have no underline.
3.  **Design a project list item:** Background Void Black (#111111). Project title 'Double Chair' using ak font, 58px, weight 400, #fefefe, lineHeight 0.90. Below it, '2021' as small detail text using ak font, 12px, weight 400, #fefefe. Ensure generous vertical spacing (e.g., 32px below the title).

## Similar Brands

- **AIGA Design Archives** — Monochromatic palette, heavy reliance on sophisticated typography as a core design element, minimalistic presentation of content.
- **FriendsOfMothership** — Dark theme with high-contrast type and large imagery, creating a gallery-like experience for creative work.
- **Studio—JQ** — Focus on high-quality 3D renders/product imagery against a dark background, minimal UI, and a strong emphasis on large, graphic typography.
- **Figma (old site)** — Dominant, wide-letter-spaced headlines in a monochromatic theme to convey technical sophistication with a design-forward approach.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-void-black: #111111;
  --color-exhibition-white: #fefefe;

  /* Typography — Font Families */
  --font-ak: 'ak', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gs: 'gs', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.56;
  --text-body: 14px;
  --leading-body: 1.56;
  --text-subheading: 18px;
  --leading-subheading: 1.5;
  --text-heading: 58px;
  --leading-heading: 0.9;
  --text-display: 216px;
  --leading-display: 0.8;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-32: 32px;

  /* Layout */
  --section-gap: 64px;
  --card-padding: 32px;
  --element-gap: 8px;

  /* Named Radii */
  --radius-all: 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-void-black: #111111;
  --color-exhibition-white: #fefefe;

  /* Typography */
  --font-ak: 'ak', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gs: 'gs', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.56;
  --text-body: 14px;
  --leading-body: 1.56;
  --text-subheading: 18px;
  --leading-subheading: 1.5;
  --text-heading: 58px;
  --leading-heading: 0.9;
  --text-display: 216px;
  --leading-display: 0.8;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-32: 32px;
}
```

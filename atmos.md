# ATMOS — Style Reference
> Ethereal Sky Gradient

**Theme:** light

Atmos presents a serene, immersive experience with a light theme dominated by a vibrant blue sky gradient. Typography leans into a classic, elegant serif for branding contrasted with a clean sans-serif for content, creating a subtle tension between whimsy and readability. Large, expressive headlines set against spacious layouts evoke an ethereal, dreamlike atmosphere. The visual system minimizes UI elements, focusing instead on broad washes of color and text-centric communication.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Sky Gradient | `linear-gradient(180deg, #0825c6 0%, #FFFFFF 100%)` | `--color-sky-gradient` | Background gradient for hero sections and immersive experiences, transitioning from deep indigo to bright sky blue |
| Canvas White | `#ffffff` | `--color-canvas-white` | Primary background for all content sections, cards, and most text. Also used for outlined button borders |
| Ink Black | `#000000` | `--color-ink-black` | Primary text color for headlines and body copy, providing high contrast against white backgrounds. Used for some decorative fills |

## Tokens — Typography

### NewYork — Decorative display font for branding and large section headlines. Its elegant serif forms create a strong, artistic statement. · `--font-newyork`
- **Substitute:** Playfair Display
- **Weights:** 400
- **Sizes:** 50px, 200px
- **Line height:** 1.15
- **Role:** Decorative display font for branding and large section headlines. Its elegant serif forms create a strong, artistic statement.

### DM Sans — Primary sans-serif for body text, links, and complementary information. Its clean geometry ensures readability in various contexts. · `--font-dm-sans`
- **Substitute:** Inter
- **Weights:** 400, 700
- **Sizes:** 20px, 25px, 30px
- **Line height:** 1.15, 1.50
- **Role:** Primary sans-serif for body text, links, and complementary information. Its clean geometry ensures readability in various contexts.

### Times — Small, functional text for auxiliary elements and fine print. Used at a very small size for subtle details. · `--font-times`
- **Substitute:** Times New Roman
- **Weights:** 400
- **Sizes:** 10px
- **Line height:** 1.15
- **Role:** Small, functional text for auxiliary elements and fine print. Used at a very small size for subtle details.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.15 | — | `--text-caption` |
| body | 20px | 1.15 | — | `--text-body` |
| subheading | 25px | 1.15 | — | `--text-subheading` |
| heading | 30px | 1.15 | — | `--text-heading` |
| display | 50px | 1.15 | — | `--text-display` |
| display-lg | 200px | 1.15 | — | `--text-display-lg` |

## Tokens — Spacing & Shapes

**Density:** spacious

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 10 | 10px | `--spacing-10` |
| 20 | 20px | `--spacing-20` |
| 30 | 30px | `--spacing-30` |
| 42 | 42px | `--spacing-42` |
| 50 | 50px | `--spacing-50` |
| 100 | 100px | `--spacing-100` |
| 134 | 134px | `--spacing-134` |

### Border Radius

| Element | Value |
|---------|-------|
| buttons | 9999px |

### Layout

- **Section gap:** 100px
- **Card padding:** 30px
- **Element gap:** 20px

## Components

### Hero Title
**Role:** Dominant text element on the landing page.

Uses 'NewYork' font at 200px (weight 400) in Ink Black, centered on the Sky Gradient background.

### Circular Subtitle
**Role:** Accompanying descriptive text in the hero section.

Curved text, DM Sans, 10px, Ink Black, describing the experience, often appearing within a boundary element.

### Outlined Explore Button
**Role:** Primary call to action with a ghost-like appearance.

DM Sans, 20px, Canvas White text on a transparent background, with a 1px Canvas White border and 9999px border-radius. Padding around 30px vertical and horizontal.

### Introductory Heading
**Role:** Section titles after the hero.

DM Sans, 30px (weight 700), Ink Black, typically followed by a 42px margin-bottom.

### Body Text
**Role:** Standard paragraph text.

DM Sans, 20px (weight 400), Ink Black, typically followed by a 20px margin-bottom for paragraph spacing.

### Resource Link
**Role:** Hyperlinks to external content.

DM Sans, 25px (weight 400), Ink Black, with a 10px top margin when appearing in lists.

## Do's and Don'ts

### Do
- Prioritize generous vertical spacing, using 100px for section gaps and 20px for element gaps to maintain a spacious feel.
- Use 'NewYork' font exclusively for large, declarative headlines and branding elements, leveraging its unique serif character.
- Apply 'DM Sans' for all functional text, including body copy, links, and smaller headings, ensuring high readability.
- Employ the Sky Gradient as a full-bleed background for immersive sections, letting it define the visual tone.
- Utilize Canvas White as the dominant background color for textual content areas and Ink Black for primary text to ensure contrast.
- Ensure interactive elements like buttons use Canvas White for their borders and text when on gradient or dark backgrounds.
- Maintain a minimal approach to UI elements; focus on typography and spaciousness over complex component structures.

### Don't
- Do not introduce heavy shadows or complex elevation; the design emphasizes a flat aesthetic.
- Avoid using saturated colors other than the brand's blues for any UI elements; restrict color to backgrounds and branding.
- Do not use system default link colors; all links should be styled with Ink Black and 'DM Sans'.
- Do not clutter layouts with too many distinct elements or varying component styles; simplicity is key.
- Avoid tight spacing; maintain the spacious and airy feel across all content arrangements.
- Do not use 'Times' for anything other than very small, auxiliary text; 'DM Sans' and 'NewYork' cover primary typography needs.
- Do not apply excessive borders or backgrounds to interactive elements; maintain a ghost or outlined style where possible.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #ffffff
border: #ffffff
accent: no distinct accent color
primary action: no distinct CTA color

Example Component Prompts:
1. Create a Hero Section: Full-viewport background with Sky Gradient. Centered 'NewYork' headline (200px, #000000). Below it, a circular subtitle using 'DM Sans' (10px, #000000). Add an 'Explore' button ('DM Sans', 20px, #ffffff text, #ffffff 1px border, 9999px radius, 30px padding).
2. Create a Content Section: Canvas White background. An Introductory Heading ('DM Sans', 30px, weight 700, #000000) with 42px margin-bottom. Follow with two paragraphs of Body Text ('DM Sans', 20px, weight 400, #000000), each with 20px margin-bottom.
3. Create a Resource List: Canvas White background. A paragraph of Body Text ('DM Sans', 20px, weight 400, #000000). Below that, a list of Resource Links ('DM Sans', 25px, weight 400, #000000), each with 10px margin-top.

## Similar Brands

- **Awwwards-winning portfolio sites** — Focus on large, artistic typography, immersive full-screen visuals, and sparse UI elements.
- **Luxury brand landing pages** — Emphasis on high-quality visuals, minimal text, and a sophisticated, almost solemn, typographic presence.
- **Experiential microsites** — Uses color gradients for atmosphere rather than functional UI, combined with animation for a dreamlike feel.
- **Abstract art showcases** — The aesthetic prioritizes visual impact and mood over detailed information density, using large type as a design element.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-sky-gradient: #0825c6;
  --gradient-sky-gradient: linear-gradient(180deg, #0825c6 0%, #FFFFFF 100%);
  --color-canvas-white: #ffffff;
  --color-ink-black: #000000;

  /* Typography — Font Families */
  --font-newyork: 'NewYork', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-dm-sans: 'DM Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-times: 'Times', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.15;
  --text-body: 20px;
  --leading-body: 1.15;
  --text-subheading: 25px;
  --leading-subheading: 1.15;
  --text-heading: 30px;
  --leading-heading: 1.15;
  --text-display: 50px;
  --leading-display: 1.15;
  --text-display-lg: 200px;
  --leading-display-lg: 1.15;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-10: 10px;
  --spacing-20: 20px;
  --spacing-30: 30px;
  --spacing-42: 42px;
  --spacing-50: 50px;
  --spacing-100: 100px;
  --spacing-134: 134px;

  /* Layout */
  --section-gap: 100px;
  --card-padding: 30px;
  --element-gap: 20px;

  /* Named Radii */
  --radius-buttons: 9999px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-sky-gradient: #0825c6;
  --color-canvas-white: #ffffff;
  --color-ink-black: #000000;

  /* Typography */
  --font-newyork: 'NewYork', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-dm-sans: 'DM Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-times: 'Times', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.15;
  --text-body: 20px;
  --leading-body: 1.15;
  --text-subheading: 25px;
  --leading-subheading: 1.15;
  --text-heading: 30px;
  --leading-heading: 1.15;
  --text-display: 50px;
  --leading-display: 1.15;
  --text-display-lg: 200px;
  --leading-display-lg: 1.15;

  /* Spacing */
  --spacing-10: 10px;
  --spacing-20: 20px;
  --spacing-30: 30px;
  --spacing-42: 42px;
  --spacing-50: 50px;
  --spacing-100: 100px;
  --spacing-134: 134px;
}
```

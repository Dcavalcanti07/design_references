# Glitch Blog — Style Reference
> Playful code journal

**Theme:** light

The Glitch Blog evokes a playful yet functional aesthetic, blending a clean, white informational canvas with vibrant, whimsical illustrations and a singular vivid pink accent. Typography is grounded in a readable sans-serif, maintaining clarity across various content types. The overall impression is one of accessibility and creative expression, where visual elements feel supportive rather than overpowering, guiding the user through content with subtle cues.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#000000` | `--color-midnight-ink` | Primary text, headings, icons, strong borders — provides high contrast against light surfaces |
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card surfaces, input fields, primary fills for icons — establishes a clean, expansive visual field |
| Outline Gray | `#e4e4e4` | `--color-outline-gray` | Subtle section dividers, footer borders — offers segmentation without harshness |
| Input Border | `#b4b4b4` | `--color-input-border` | Neutral form states, badge text, and quiet UI feedback where color should stay understated. Do not promote it to the primary CTA color |
| Glitch Pink | `#ff00bc` | `--color-glitch-pink` | Accent for links, active states, borders for interactive elements, decorative imagery — makes actions and highlights stand out with a distinct, vivid pop |

## Tokens — Typography

### Inter Variable — The primary typeface for all content. Regular (400) is used for body text, lists, and links; Semibold (600) for subheadings and card titles; Bold (700) for prominent headings like article titles. Its clean, functional aesthetic supports content clarity. · `--font-inter-variable`
- **Substitute:** Inter, Arial, sans-serif
- **Weights:** 400, 600, 700
- **Sizes:** 14px, 16px, 18px, 20px, 40px
- **Line height:** 1.20, 1.38
- **Role:** The primary typeface for all content. Regular (400) is used for body text, lists, and links; Semibold (600) for subheadings and card titles; Bold (700) for prominent headings like article titles. Its clean, functional aesthetic supports content clarity.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 14px | 1.38 | — | `--text-caption` |
| body | 16px | 1.38 | — | `--text-body` |
| subheading | 18px | 1.38 | — | `--text-subheading` |
| heading | 20px | 1.2 | — | `--text-heading` |
| display | 40px | 1.2 | — | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 8 | 8px | `--spacing-8` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 28 | 28px | `--spacing-28` |
| 48 | 48px | `--spacing-48` |

### Border Radius

| Element | Value |
|---------|-------|
| none | 0px |
| inputs | 0px |

### Layout

- **Page max-width:** 1024px
- **Section gap:** 64px
- **Card padding:** 20px
- **Element gap:** 8px

## Components

### Primary Navigation Link
**Role:** Main navigation items

Text in Midnight Ink (#000000) at 16px, Inter Variable regular (400). On hover, text color remains but interaction is implied through context.

### Blog Post Card
**Role:** Container for individual blog post previews on listing pages

White (#ffffff) background, with a subtle border from Outline Gray (#e4e4e4) and a 1px solid border. Internally, content is spaced with 20px padding.

### Article Title
**Role:** Headline for blog posts and prominent content sections

Inter Variable bold (700), size 40px, color Midnight Ink (#000000). Provides clear hierarchy and visual weight for key information.

### Date Metadata
**Role:** Timestamp for blog posts

Inter Variable regular (400), size 14px, color Midnight Ink (#000000). Creates a subtle informational cue.

### Search Input Field
**Role:** Interactive text input for searching content

White (#ffffff) background, with a 1px solid border in Input Border (#b4b4b4). Text inside is Midnight Ink (#000000) at 16px. Padding is 4px all around.

### All Stories Link
**Role:** Link to view more blog posts or archives

Text is Glitch Pink (#ff00bc) at 16px, Inter Variable regular (400). Acts as an accent-colored call to action.

## Do's and Don'ts

### Do
- Use Canvas White (#ffffff) as the default background for all page surfaces and major content blocks to maintain a clean aesthetic.
- Employ Midnight Ink (#000000) for all primary text, headings, and icons to ensure high contrast and readability.
- Highlight interactive links and accent elements with Glitch Pink (#ff00bc) to guide user attention and reinforce brand identity.
- Apply Inter Variable as the sole typeface, using regular (400) for body text and links, semibold (600) for subheadings, and bold (700) for main headings.
- Structure content with a consistent 20px padding within card-like components and an 8px element gap for internal spacing.
- Incorporate Outline Gray (#e4e4e4) for subtle dividers or non-interactive borders, providing separation without visual heaviness.
- Ensure all interactive elements like search inputs maintain a 0px border-radius, contributing to the functional, unadorned feel.

### Don't
- Avoid using multiple accent colors; reserve Glitch Pink (#ff00bc) for all brand-specific emphasis.
- Do not introduce shadows or significant elevation effects on UI elements; aim for a flat, clean surface treatment.
- Refrain from altering the default 0px border-radius for inputs and most UI elements, as sharp corners are a defining feature.
- Do not deviate from the Inter Variable typeface for any text content, including decorative or marketing elements.
- Avoid large variations in spacing; maintain the 8px element gap for atomic elements and 20px for internal card padding.
- Do not use dark backgrounds for main content areas; the system is fundamentally light-themed with high contrast.

## Imagery

The site's imagery features a strong emphasis on whimsical, illustrative artwork that is abstract and colorful, often appearing as full-width hero banners or smaller square thumbnails for blog posts. These illustrations typically incorporate a vibrant, playful palette that contrasts with the monochrome UI, serving a decorative and atmospheric role rather than strict explanatory content. Icons are minimal, mostly single-color, and outlined, appearing in search functions or branding. Photography is minimal, used sparingly for specific content needs, and often nested within the illustrative style of the blog post preview cards. The density is moderate; while a large hero illustration commands attention, subsequent content blocks are text-dominant with smaller square visuals.

## Layout

The page employs a max-width 1024px contained layout, centered on a Canvas White background. The hero section features a large, full-width illustration followed by a prominent centered headline. Below the hero, content is arranged in a bento-grid pattern, featuring 2-column or 3-column card grids for blog post previews. Vertical spacing between main content sections is set at 64px, creating clear visual breaks. Navigation is a simple top bar with left-aligned branding and right-aligned search functionality. The overall rhythm is structured and clean, emphasizing content readability within a defined central column.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #ffffff
border: #e4e4e4
accent: #ff00bc
primary action: #ff00bc (outlined action border)

Example Component Prompts:
Create a blog post card: White background (#ffffff), 1px solid border in Outline Gray (#e4e4e4). Inside, an image, then date metadata (Inter Variable 400, 14px, #000000), then a bold blog post title (Inter Variable 700, 20px, #000000). Use 20px padding.
Create a main article title: "Until we meet again 👋" in Inter Variable 700, 40px, #000000, centered on the page.
Create a search input field: White background (#ffffff), 1px solid border in Input Border (#b4b4b4), 4px padding. Placeholder text in Inter Variable 400, 16px, #b4b4b4.
Create an 'All Stories' link: "All Stories >" in Glitch Pink (#ff00bc), Inter Variable 400, 16px.

## Similar Brands

- **Figma Blog** — Uses a bright, white canvas with playful illustrations and strong, clear typography.
- **Webflow Blog** — Features a structured grid layout for articles and a clean, accessible aesthetic with a focus on readability and clear content hierarchy.
- **Stripe Blog** — Employs a very clean, minimalist design with a clear type hierarchy, sharp corners, and a predominantly monochrome palette, but often with more subtle accent colors.
- **Codecademy Blog** — Combines a clean white background with vibrant accent colors for links and calls to action, maintaining a playful yet functional tone.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-canvas-white: #ffffff;
  --color-outline-gray: #e4e4e4;
  --color-input-border: #b4b4b4;
  --color-glitch-pink: #ff00bc;

  /* Typography — Font Families */
  --font-inter-variable: 'Inter Variable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.38;
  --text-body: 16px;
  --leading-body: 1.38;
  --text-subheading: 18px;
  --leading-subheading: 1.38;
  --text-heading: 20px;
  --leading-heading: 1.2;
  --text-display: 40px;
  --leading-display: 1.2;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-28: 28px;
  --spacing-48: 48px;

  /* Layout */
  --page-max-width: 1024px;
  --section-gap: 64px;
  --card-padding: 20px;
  --element-gap: 8px;

  /* Named Radii */
  --radius-none: 0px;
  --radius-inputs: 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-canvas-white: #ffffff;
  --color-outline-gray: #e4e4e4;
  --color-input-border: #b4b4b4;
  --color-glitch-pink: #ff00bc;

  /* Typography */
  --font-inter-variable: 'Inter Variable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.38;
  --text-body: 16px;
  --leading-body: 1.38;
  --text-subheading: 18px;
  --leading-subheading: 1.38;
  --text-heading: 20px;
  --leading-heading: 1.2;
  --text-display: 40px;
  --leading-display: 1.2;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-28: 28px;
  --spacing-48: 48px;
}
```

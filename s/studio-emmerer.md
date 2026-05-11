# Studio Emmerer — Style Reference
> Architectural Blueprint, Night Mode

**Theme:** dark

Studio Emmerer employs a minimalist, almost stark aesthetic, prioritizing content through a high-contrast dark theme. Visual hierarchy is achieved primarily through typography and subtle spacing. Surfaces are uniformly dark, with distinction created by thin hairline borders rather than depth or shadows. The overall impression is one of restrained precision, reminiscent of architectural blueprints presented on a night-mode screen.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Pitch Black | `#000000` | `--color-pitch-black` | Dark borders and separators for elevated surfaces and inverted UI. Do not promote it to the primary CTA color |
| Steel Gray | `#999999` | `--color-steel-gray` | Muted text for secondary information like table headers or metadata. Provides a subtle visual separation from primary text |
| Preview White | `#ffffff` | `--color-preview-white` | Color used for text that appears over preview images, ensuring readability against varied photographic backgrounds |

## Tokens — Typography

### NHaasGrotesk — The sole typeface for all text content, from body to headlines and interactive elements. Its consistent weight and precise tracking maintain a disciplined, uniform voice across the interface. · `--font-nhaasgrotesk`
- **Substitute:** Helvetica Neue
- **Weights:** 400
- **Sizes:** 15px, 16px, 20px, 30px
- **Line height:** 0.90, 1.16
- **Letter spacing:** -0.165, -0.16, -0.16, -0.15
- **Role:** The sole typeface for all text content, from body to headlines and interactive elements. Its consistent weight and precise tracking maintain a disciplined, uniform voice across the interface.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body-sm | 15px | 1.16 | -0.165px | `--text-body-sm` |
| subheading | 20px | 0.9 | -0.16px | `--text-subheading` |
| heading | 30px | 0.9 | -0.15px | `--text-heading` |

## Tokens — Spacing & Shapes

**Base unit:** 6px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 5 | 5px | `--spacing-5` |
| 12 | 12px | `--spacing-12` |
| 16 | 16px | `--spacing-16` |
| 30 | 30px | `--spacing-30` |

### Border Radius

| Element | Value |
|---------|-------|
| none | 0px |

### Layout

- **Section gap:** 32px
- **Card padding:** 12px
- **Element gap:** 5px

## Components

### Navigation Link
**Role:** Interactive text link for site navigation.

Uses NHaasGrotesk, 16px, 400 weight, Pitch Black text. On hover, the Pitch Black text remains, the underline appears. No background or padding. The spacing between nav items is 30px.

### Read More Link
**Role:** Text link for expanding content.

Uses NHaasGrotesk, 16px, 400 weight, Pitch Black text, with a Pitch Black border-bottom. No padding.

### Project Table Row
**Role:** A single row within the tabular project listing.

Text uses NHaasGrotesk, 16px, 400 weight, Pitch Black. The row has a bottom border of 1px solid Pitch Black. Padding of 12px top/bottom and 4px left/right. The labels like 'PROJECT', 'TYPE', 'LOCATION', 'YEAR' use Steel Gray text.

### Project List Item
**Role:** A single project entry in the main list. Behaves like a link.

Displaying 'PAZ Graz Official Graz 2025' like a block link, using 'NHaasGrotesk', 16px, 400 weight, Pitch Black text, with a 1px solid Pitch Black border underneath the entire listing. The `Open Project` text within uses the same styling but with an arrow icon.

## Do's and Don'ts

### Do
- Always use 'NHaasGrotesk' as the primary typeface for all text elements.
- Maintain a high-contrast dark theme using Pitch Black (#000000) for backgrounds and primary text.
- Implement borders using 1px solid Pitch Black (#000000) to delineate sections and interactive elements.
- Utilize 0px border-radius for all elements, maintaining sharp, angular forms.
- Apply Steel Gray (#999999) for secondary text such as table headers or metadata.
- Ensure consistent spacing with a base unit derived from 5px for element gaps and 32px for section gaps.
- Use Preview White (#ffffff) for any text appearing directly over photographic or illustrative content.

### Don't
- Do not introduce any background colors other than Pitch Black (#000000) for primary surfaces.
- Avoid using shadows or elevation effects; elements should remain flat against the dark background.
- Do not deviate from the 'NHaasGrotesk' typeface or introduce additional font families.
- Refrain from using any color accents; the palette is strictly achromatic with specific allowances for text over media.
- Do not use rounded corners or any non-zero border-radius on any UI elements.
- Avoid decorative gradients; surfaces should be solid colors.
- Do not introduce unnecessary padding or margin, adhere to the established spacing units.

## Imagery

This site features product/architectural photography exclusively. Images are full-bleed within their sections, presenting stark, uncropped views of built environments. There are no illustrations, icons are minimal and functional (arrows), and there's no lifestyle photography. The imagery serves as direct project showcase rather than decorative atmosphere, often occupying significant visual space.

## Layout

The page primarily uses a full-bleed layout, particularly for hero sections and image showcases. Content sections alternate between full-width black backgrounds and a max-width centered container for text-heavy content or tabular data. Vertical rhythm is maintained by consistent section gaps. Navigation is minimalist, typically a horizontal inline list. The overall arrangement is straightforward and linear, prioritizing content presentation with a clear, functional aesthetic.

## Agent Prompt Guide

Quick Color Reference: text: #000000, background: #000000, border: #000000, accent: no distinct accent color, primary action: no distinct CTA color

Example Component Prompts:
Create a primary navigation link titled 'about': NHaasGrotesk, 16px, 400 weight, Pitch Black text (#000000). No background, no padding, 0px border-radius.
Create a 'read more' text link: NHaasGrotesk, 16px, 400 weight, Pitch Black text (#000000) with a 1px solid Pitch Black (#000000) bottom border.
Create a project table row for 'PAZ Graz Official Graz 2025': NHaasGrotesk, 16px, 400 weight, Pitch Black text (#000000). 12px vertical padding, 4px horizontal padding. A 1px solid Pitch Black (#000000) border-bottom.

## Similar Brands

- **Norm Architects** — Similar minimalist design, extensive use of black and white, and focus on architectural projects.
- **OMA** — Stark, high-contrast visual style with a strong typographic foundation and minimal color usage.
- **Bjarke Ingels Group (BIG)** — Professional architectural site focusing on projects, often with clean, high-contrast imagery and unembellished UI.
- **PANGAIA** — A monochromatic website with a direct, functional presentation of content and product, relying heavily on typography and spacing.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-pitch-black: #000000;
  --color-steel-gray: #999999;
  --color-preview-white: #ffffff;

  /* Typography — Font Families */
  --font-nhaasgrotesk: 'NHaasGrotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-sm: 15px;
  --leading-body-sm: 1.16;
  --tracking-body-sm: -0.165px;
  --text-subheading: 20px;
  --leading-subheading: 0.9;
  --tracking-subheading: -0.16px;
  --text-heading: 30px;
  --leading-heading: 0.9;
  --tracking-heading: -0.15px;

  /* Typography — Weights */
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-unit: 6px;
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-30: 30px;

  /* Layout */
  --section-gap: 32px;
  --card-padding: 12px;
  --element-gap: 5px;

  /* Named Radii */
  --radius-none: 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-pitch-black: #000000;
  --color-steel-gray: #999999;
  --color-preview-white: #ffffff;

  /* Typography */
  --font-nhaasgrotesk: 'NHaasGrotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-sm: 15px;
  --leading-body-sm: 1.16;
  --tracking-body-sm: -0.165px;
  --text-subheading: 20px;
  --leading-subheading: 0.9;
  --tracking-subheading: -0.16px;
  --text-heading: 30px;
  --leading-heading: 0.9;
  --tracking-heading: -0.15px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-30: 30px;
}
```

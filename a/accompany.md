# ACCOMPANY — Style Reference
> Gallery text on white. Clean, stark, and declarative.

**Theme:** light

ACCOMPANY employs a stark, high-contrast aesthetic reminiscent of gallery walls, using bold typography as primary visual elements against an expansive white canvas. Text is predominantly black, creating a declarative and direct brand voice. Accent colors are introduced sparingly through large, impactful imagery, rather than integrated throughout the UI, preserving the monochromatic purity of the interface. Components are minimal, relying on subtle borders and text-based interactions.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card surfaces, and primary visual space |
| Ink Black | `#000000` | `--color-ink-black` | Dark borders and separators for elevated surfaces and inverted UI. Do not promote it to the primary CTA color |
| Border Grey | `#0a0a0a` | `--color-border-grey` | Subtle borders and separators, providing minimal visual interruption |

## Tokens — Typography

### Times — Body text and supporting information. Its classic serif style provides a refined counterpoint to the more contemporary sans-serifs, creating a sense of established authority. · `--font-times`
- **Substitute:** Times New Roman
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.00, 1.20
- **Role:** Body text and supporting information. Its classic serif style provides a refined counterpoint to the more contemporary sans-serifs, creating a sense of established authority.

### SyndicatGroteskMedium — Navigation, general body, and subheadings. The extended tracking makes it feel spacious and modern, preventing density despite the medium weight. · `--font-syndicatgroteskmedium`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 16px, 18px, 44px
- **Line height:** 1.00, 1.10, 1.20
- **Letter spacing:** -0.03
- **Role:** Navigation, general body, and subheadings. The extended tracking makes it feel spacious and modern, preventing density despite the medium weight.

### Arial — Small functional text and icon labels, ensuring legibility at minimal sizes. · `--font-arial`
- **Substitute:** Helvetica
- **Weights:** 400
- **Sizes:** 13px
- **Line height:** 1.20
- **Role:** Small functional text and icon labels, ensuring legibility at minimal sizes.

### Items-Light — Primary headlines and hero text. The light weight combined with a tight line height and tracking creates a commanding, almost whispered presence, projecting authority through restraint rather than loudness. · `--font-items-light`
- **Substitute:** Garamond Light
- **Weights:** 400
- **Sizes:** 80px
- **Line height:** 0.90
- **Letter spacing:** -0.02
- **Role:** Primary headlines and hero text. The light weight combined with a tight line height and tracking creates a commanding, almost whispered presence, projecting authority through restraint rather than loudness.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 16px | 1.1 | — | `--text-caption` |
| body-sm | 18px | 1.1 | — | `--text-body-sm` |
| body | 44px | 1.1 | — | `--text-body` |

## Tokens — Spacing & Shapes

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 10 | 10px | `--spacing-10` |
| 14 | 14px | `--spacing-14` |
| 21 | 21px | `--spacing-21` |
| 35 | 35px | `--spacing-35` |
| 71 | 71px | `--spacing-71` |

### Layout

- **Section gap:** 71px
- **Card padding:** 21px
- **Element gap:** 10px

## Components

### Navigation Link
**Role:** Top-level navigation items.

Uses SyndicatGroteskMedium, weight 400, 16px, with a 1.0 line height. On hover, a 1px Ink Black border appears below the text.

### Text Button
**Role:** Minimal interactive buttons.

Text uses Arial, weight 400, 13px, Ink Black. Padding is 10px vertical and 0px horizontal. No background color, blending seamlessly with the Canvas White.

### Feature Card
**Role:** Displays featured content or news items.

Defined by a 1px Ink Black border around the perimeter. Internal padding is 21px around content. Background is Canvas White.

## Do's and Don'ts

### Do
- Prioritize Canvas White (#ffffff) as the dominant background for all major sections.
- Use Ink Black (#000000) for all text, borders, and functional iconography to maintain high contrast.
- Apply Items-Light (weight 400, 80px) with -0.02em letter spacing for prominent headlines to achieve a refined, impactful presence.
- Employ SyndicatGroteskMedium (weight 400) with -0.03em letter spacing for subheadings and body text where a modern sans-serif is needed.
- Maintain generous vertical spacing between content sections, using 71px as a standard section gap.
- Implement 1px Ink Black borders as a primary visual divider and component container, rather than shadows or filled backgrounds.
- Integrate large, full-bleed images as visual anchors, allowing their internal colors to provide the only chromatic variation on the page.

### Don't
- Avoid using saturated or chromatic colors for UI elements such as backgrounds or text outside of imagery.
- Do not introduce shadows or complex elevation schemes; rely on borders and whitespace for visual separation.
- Refrain from using heavily filled buttons or complex component designs; favor ghost buttons and text links.
- Do not deviate from the specified typography and letter-spacing pairings; they are crucial for the brand's voice.
- Avoid decorative gradients in UI elements; gradients are reserved for large, hero-style imagery.
- Do not clutter layouts with small, contained images. Imagery should be expansive and singular in impact.

## Imagery

Imagery primarily consists of large, often full-bleed abstract or conceptual digital art, rich in gradients and vibrant colors, serving as evocative visual anchors rather than direct product representations. They are presented without rounded corners or complex masking, acting as standalone statement pieces within the stark UI. There are also product/process-focused flat graphics and subtle screenshots, typically contained within monochrome frames, for explanatory content. Icons are minimal, represented by simple Ink Black outlines.

## Layout

The page maintains a centered, max-width layout (though the exact width isn't specified, content rarely touches the viewport edges). The hero section is characterized by a central, large headline (Items-Light) over a full-bleed, gradient image. Sections alternate between expansive whitespace for text-heavy blocks and full-width visual sections. Content often uses single-column centered text or two-column layouts where text and supporting visuals are cleanly separated, often within Ink Black bordered containers. Navigation is a simple top-right text-based menu. The overall feel is spacious and uncrowded, emphasizing large typography and impactful visuals.

## Agent Prompt Guide

Quick Color Reference: 
text: #000000
background: #ffffff
border: #000000
accent: no distinct accent color
primary action: no distinct CTA color

Example Component Prompts:
Create a hero section: Canvas White background. Headline 'Your ambition defines the destination.' with Items-Light weight 400, 80px, #000000, letter-spacing -0.02em. Subtext 'We work with you to create the brand that meets it.' with SyndicatGroteskMedium weight 400, 44px, #000000, letter-spacing -0.03em.
Create a navigation block: Text links 'WORK', 'ABOUT', 'SERVICES', 'CONTACT' using SyndicatGroteskMedium weight 400, 16px, #000000, line-height 1.0. Place them right-aligned in a top bar.
Create a text-based action button: 'Get in touch.' using Arial weight 400, 13px, #000000, padding 10px 0px. Ensure no background color.
Create a content card with a border: Background Canvas White, 1px Ink Black border. Internal padding of 21px. Inside, use Times 400, 16px, #000000 for body copy and SyndicatGroteskMedium 400, 18px, #000000, letter-spacing -0.03em for headings.

## Similar Brands

- **Büro Union** — Similar high-contrast black on white aesthetic with minimal UI and strong typographic focus.
- **Studio—JQ** — Uses large, impactful imagery and clean, monochromatic interfaces as a branding agency.
- **Focus Lab** — Employs an editorial layout with significant whitespace and bold, confident typography on a light background.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ink-black: #000000;
  --color-border-grey: #0a0a0a;

  /* Typography — Font Families */
  --font-times: 'Times', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-syndicatgroteskmedium: 'SyndicatGroteskMedium', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-items-light: 'Items-Light', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 16px;
  --leading-caption: 1.1;
  --text-body-sm: 18px;
  --leading-body-sm: 1.1;
  --text-body: 44px;
  --leading-body: 1.1;

  /* Typography — Weights */
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-10: 10px;
  --spacing-14: 14px;
  --spacing-21: 21px;
  --spacing-35: 35px;
  --spacing-71: 71px;

  /* Layout */
  --section-gap: 71px;
  --card-padding: 21px;
  --element-gap: 10px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ink-black: #000000;
  --color-border-grey: #0a0a0a;

  /* Typography */
  --font-times: 'Times', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-syndicatgroteskmedium: 'SyndicatGroteskMedium', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-items-light: 'Items-Light', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 16px;
  --leading-caption: 1.1;
  --text-body-sm: 18px;
  --leading-body-sm: 1.1;
  --text-body: 44px;
  --leading-body: 1.1;

  /* Spacing */
  --spacing-10: 10px;
  --spacing-14: 14px;
  --spacing-21: 21px;
  --spacing-35: 35px;
  --spacing-71: 71px;
}
```

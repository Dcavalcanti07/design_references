# MANNA — Style Reference
> Earthy Gallery Canvas

**Theme:** light

Manna Architects employs a subdued, earthy aesthetic that evokes natural materials and warm, muted tones. Text is primarily black against subtly tinted, soft backgrounds, giving a feeling of quiet elegance. Typography is precise and airy, favoring lighter weights and generous readability. The design system prioritizes large, impactful imagery and minimal, deliberate UI elements, suggesting a focus on visual content over interactive complexity.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Earthy Ochre | `#af6446` | `--color-earthy-ochre` | Dominant background for visual sections and footers, creating a warm canvas for large imagery |
| Pale Linen | `#f2edde` | `--color-pale-linen` | Secondary background for footer elements or subtle surface variations, providing a softer contrast to text |
| Charcoal Ink | `#000000` | `--color-charcoal-ink` | Primary text color for all content, headings, and links. Also used for hairline borders and content dividers |

## Tokens — Typography

### Scto Grotesk A — Headlines and prominent display text (60px, 500 weight) for brand impact, body text (14px, 300 weight) for spacious readability. The light 300 weight for body text gives a delicate, refined feel. · `--font-scto-grotesk-a`
- **Substitute:** Inter
- **Weights:** 300, 500
- **Sizes:** 14px, 60px
- **Line height:** 1.29
- **Letter spacing:** normal
- **Role:** Headlines and prominent display text (60px, 500 weight) for brand impact, body text (14px, 300 weight) for spacious readability. The light 300 weight for body text gives a delicate, refined feel.

### Merlo — Body copy and informational text, particularly for image captions and detailed descriptions. The consistent 400 weight maintains a straightforward, unobtrusive presence. · `--font-merlo`
- **Substitute:** Georgia
- **Weights:** 400
- **Sizes:** 16px, 26px
- **Line height:** 1.23, 1.50
- **Letter spacing:** normal
- **Role:** Body copy and informational text, particularly for image captions and detailed descriptions. The consistent 400 weight maintains a straightforward, unobtrusive presence.

## Tokens — Spacing & Shapes

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 10 | 10px | `--spacing-10` |
| 12 | 12px | `--spacing-12` |
| 20 | 20px | `--spacing-20` |

### Border Radius

| Element | Value |
|---------|-------|
| images | 0px |

### Layout

- **Section gap:** 40px
- **Card padding:** 20px
- **Element gap:** 10-20px

## Components

### Image Card with Caption
**Role:** Primary content display for portfolio pieces or architectural photography.

Images are presented without rounded corners, relying on the 'Earthy Ochre' background as their implied container. A 'Merlo' 16px caption in 'Charcoal Ink' with 1.5 lineHeight is set with 10px `marginBottom` below the image. Padding around the image and caption is 20px, framing the visual content.

### Footer Section
**Role:** Global brand and contact information.

The footer uses a 'Pale Linen' background with 20px padding on all sides. Text links like 'About' and 'info@mannaarchitects.com' are in 'Charcoal Ink' using 'Scto Grotesk A' at 14px, 300 weight.

### Prominent Brand Heading
**Role:** Major section titles and brand identity.

Utilizes 'Scto Grotesk A' at 60px, weight 500, in 'Charcoal Ink'. This large, bold typography anchors content sections despite the overall light touch of the design.

## Do's and Don'ts

### Do
- Prioritize large, uncropped imagery as primary content, allowing them to fill available width and define sections.
- Use 'Earthy Ochre' (#af6446) as the primary background for content blocks and distinct page sections.
- Render all text, including headings, body, and links, in 'Charcoal Ink' (#000000).
- Apply 'Scto Grotesk A' (60px, 500 weight) for dominant headings and 'Merlo' (16px, 400 weight) for detailed captions and informational text.
- Maintain minimal spacing around images by using 10px `marginBottom` for captions, creating a tight visual grouping.
- Structure layouts with ample clear space, using 20px padding for content blocks to prevent visual clutter.

### Don't
- Avoid using highly saturated, vivid colors; stick to the muted, earthy palette provided.
- Do not introduce rounded corners for images or cards; maintain sharp, crisp edges for visual elements.
- Refrain from using strong drop shadows or complex elevation; the design relies on flat presentation and color contrast.
- Do not deviate from the specified font families or weights, as the typographic precision is a core brand element.
- Avoid excessive interactive elements or buttons; interaction should be secondary to content display.
- Do not use letter-spacing other than 'normal' for any text elements.

## Imagery

This system relies heavily on high-quality, full-bleed architectural photography and natural landscape imagery. Images are presented without borders or significant contained treatment, creating an immersive, gallery-like experience. The focus is on the object or scene, often with descriptive captions below. There are no apparent abstract graphics, illustrations, or complex icon systems; simplicity and realism dominate the visual language.

## Layout

The page primarily uses a full-bleed layout for imagery, with content sections appearing as large blocks or canvases. Text is typically centered or left-aligned beneath images. There is a strong vertical rhythm, with sections clearly delineated by shifts in background color (often 'Earthy Ochre'). The overall layout feels spacious and unconstrained, allowing visual content to breathe. Navigation is minimal, likely a simple header or footer with key links.

## Agent Prompt Guide

Quick Color Reference: 
text: #000000
background: #af6446
border: #000000
accent: no distinct accent color
primary action: no distinct CTA color

Example Component Prompts:
1. Create an image display: an image with 0px radius, 10px `marginBottom`. Below it, add a caption: 'Merlo', 16px, 400 weight, #000000, 1.5 lineHeight.
2. Design a footer section: background is #f2edde, with 20px padding on all sides. It contains 'Scto Grotesk A', 14px, 300 weight, #000000 links separated by 20px `elementGap`.
3. Implement a page heading: 'Scto Grotesk A', 60px, 500 weight, #000000.

## Similar Brands

- **Norm Architects** — Similar reliance on natural tones, minimalist typography, and large-format architectural photography.
- **Studio McGee** — Shares a warm, inviting color palette with earthy neutrals and a focus on serene visual compositions.
- **The Future Kept** — Employs an understated visual style, using subtle background colors and clear, functional typography to highlight product photography.
- **Artless** — A similar emphasis on large, unadorned imagery and a quiet, content-focused presentation.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-earthy-ochre: #af6446;
  --color-pale-linen: #f2edde;
  --color-charcoal-ink: #000000;

  /* Typography — Font Families */
  --font-scto-grotesk-a: 'Scto Grotesk A', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-merlo: 'Merlo', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-sm: 14px;
  --leading-sm: 1.29;
  --text-base: 16px;
  --leading-base: 1.5;
  --text-2xl: 26px;
  --leading-2xl: 1.23;
  --text-5xl: 60px;
  --leading-5xl: 0.6;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-20: 20px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 20px;
  --element-gap: 10-20px;

  /* Named Radii */
  --radius-images: 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-earthy-ochre: #af6446;
  --color-pale-linen: #f2edde;
  --color-charcoal-ink: #000000;

  /* Typography */
  --font-scto-grotesk-a: 'Scto Grotesk A', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-merlo: 'Merlo', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-sm: 14px;
  --leading-sm: 1.29;
  --text-base: 16px;
  --leading-base: 1.5;
  --text-2xl: 26px;
  --leading-2xl: 1.23;
  --text-5xl: 60px;
  --leading-5xl: 0.6;

  /* Spacing */
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-20: 20px;
}
```

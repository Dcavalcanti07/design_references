# Nathan Riley — Style Reference
> Gallery of softly lit dreams.

**Theme:** light

Nathan Riley's portfolio presents a serene, immersive gallery experience, characterized by a soft, almost ethereal visual style where imagery takes precedence. The core aesthetic relies on a monochromatic palette of deep charcoal, soft neutrals, and a surprising, gentle pink, allowing the evocative 3D art to be the focal point. Typography is distinctly split between an elegant, serif headline font and a functional sans-serif for body text, creating a contrast between artistic expression and clear information delivery. Control elements are minimal and merge seamlessly with their context.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Charcoal | `#000000` | `--color-midnight-charcoal` | Primary text, strong outlines, information hierarchy markers for links and text labels. Despite being pure black, it feels grounded |
| Canvas White | `#ffffff` | `--color-canvas-white` | Hairline borders, dividers, input outlines, and card edges on light surfaces. Do not promote it to the primary CTA color |
| Ash Gray | `#393939` | `--color-ash-gray` | Secondary text, subtle borders, and background for specific content blocks, offering a slightly softer contrast than pure black |
| Ethereal Pink | `#fce0db` | `--color-ethereal-pink` | Background for biographical section, social elements, and a soft, thematic accent that contrasts with the monochromatic gallery |

## Tokens — Typography

### font1 — font1 — detected in extracted data but not described by AI · `--font-font1`
- **Weights:** 300, 400
- **Sizes:** 12px, 238px
- **Line height:** 0.8, 1.1
- **Letter spacing:** -0.04
- **Role:** font1 — detected in extracted data but not described by AI

### Playfair Display — Primary headings and large display text. The elegant serif and subtle tracking create a sophisticated, artistic tone at large sizes, while remaining legible for smaller decorative uses. · `--font-playfair-display`
- **Substitute:** Playfair Display
- **Weights:** 
- **Sizes:** 
- **Line height:** 
- **Letter spacing:** -0.04em
- **Role:** Primary headings and large display text. The elegant serif and subtle tracking create a sophisticated, artistic tone at large sizes, while remaining legible for smaller decorative uses.

### Inter — Body text, links, and all functional interface labels. Its neutral, contemporary character ensures readability and a modern feel. · `--font-inter`
- **Substitute:** Inter
- **Weights:** 
- **Sizes:** 
- **Line height:** 
- **Letter spacing:** -0.025em
- **Role:** Body text, links, and all functional interface labels. Its neutral, contemporary character ensures readability and a modern feel.

### font2 — font2 — detected in extracted data but not described by AI · `--font-font2`
- **Weights:** 400
- **Sizes:** 12px, 14px, 16px
- **Line height:** 1.1
- **Letter spacing:** -0.025
- **Role:** font2 — detected in extracted data but not described by AI

### ui-sans-serif — ui-sans-serif — detected in extracted data but not described by AI · `--font-ui-sans-serif`
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.1
- **Role:** ui-sans-serif — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.1 | -0.3px | `--text-caption` |
| body-sm | 14px | 1.1 | -0.35px | `--text-body-sm` |
| body | 16px | 1.1 | -0.4px | `--text-body` |
| display | 238px | 0.8 | -9.52px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 6 | 6px | `--spacing-6` |
| 16 | 16px | `--spacing-16` |
| 29 | 29px | `--spacing-29` |
| 38 | 38px | `--spacing-38` |

### Border Radius

| Element | Value |
|---------|-------|
| buttons | 9999px |
| socialLinks | 9999px |

### Layout

- **Section gap:** 38px
- **Card padding:** 16px
- **Element gap:** 6px

## Components

### Social Link Button
**Role:** Interactive element for social media links

Ghost button with rounded corners. Uses Canvas White text on a transparent background, with a Midnight Charcoal border. Padding: 16px horizontal.

### Bio Section Card
**Role:** Container for biographical text

Full-bleed card with Ethereal Pink background. Uses Playfair Display for name, and Inter for description, both in Midnight Charcoal. Contains a link with an arrow icon.

### Gallery Thumbnail Grid Item
**Role:** Visual content display

Image is the primary content. No distinct border or padding from the grid, creating a seamless gallery effect. Images appear to be square.

## Do's and Don'ts

### Do
- Prioritize imagery: let visuals drive the design, keeping UI elements minimal and subservient.
- Use Ethereal Pink (#fce0db) sparingly, limited to accent sections like the bio block, making its appearance impactful.
- Ensure large display text (238px Playfair Display) uses Midnight Charcoal (#000000) with -0.04em letter spacing for maximum visual distinctiveness.
- Apply Canvas White (#ffffff) as the default background for interactive components like social link buttons to maintain lightness.
- Use Ash Gray (#393939) for subtle informational text or secondary borders, providing a soft contrast.
- Employ the '9999px' radius for all small interactive elements, like social link buttons, to create a consistent 'pill' shape.

### Don't
- Avoid using Ethereal Pink (#fce0db) for primary text or borders; reserve it for background accents only.
- Do not introduce strong, saturated colors; maintain the muted, achromatic dominant palette.
- Refrain from heavy shadows or multiple layered surface treatments; aim for a flat, immersive feel.
- Do not use highly contrasting borders or dividers to separate content; rely on visual breaks from imagery.
- Avoid generic system fonts for display headings; the custom serif 'Playfair Display' is key to brand identity.
- Do not break the established comfortable density; maintain consistent element gaps of 6px and vertical section spacing of 38px.

## Imagery

The visual language is dominated by hyper-realistic, often dreamlike 3D renders and photography, primarily featuring natural landscapes, architectural elements, and serene environments. Images are presented as contained square tiles, arranged in a tight grid without visible borders, allowing them to flow together as a cohesive gallery. There's no photography of people or product shots; the focus is entirely on the atmospheric, rendered scenes. Iconography is minimal text-based like the social links, or simple arrows for profile navigation. The imagery serves as the primary content and atmosphere setter, creating an immersive, almost contemplative mood.

## Layout

The page employs a full-width, grid-based layout for its primary content, where images occupy the entire available horizontal space, creating a dense, continuous visual gallery. Specific content blocks, like the bio section, break this grid with a distinct background color but maintain a centered, contained text alignment. The hero area is integrated into the grid, featuring the brand name as a large, central typographic element. Vertical rhythm is established by consistent spacing between sections, particularly the 38px section gap, which provides clear separation without being overly spacious. Navigation appears to be minimal, likely an implicit element like the 'Profile' link, rather than a fixed navigation bar.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #ffffff
border: #000000
accent: #fce0db
primary action: no distinct CTA color

Example Component Prompts:
1. Create a social link button for 'Email': Canvas White text (#ffffff) using Inter 12px weight 400, on a transparent background, with a 1px solid Midnight Charcoal (#000000) border, 9999px radius, and 16px horizontal padding. The button itself sits in an element gap of 6px.
2. Create a bio section: Ethereal Pink (#fce0db) background. Headline 'Nathan Riley' in Playfair Display 238px weight 300, Midnight Charcoal (#000000), letter spacing -9.52px. Body text 'Creative human...' in Inter 14px weight 400, Midnight Charcoal (#000000).
3. Create a gallery image tile: A square image with no visible borders, with an implied 0px border radius, occupying space within a continuous grid. The entire tile should have a 16px padding within a larger card context, and a 38px section gap from other major content blocks.

## Similar Brands

- **Awwwards Nominees** — Showcase of high-quality visual work with minimal UI, letting the art speak.
- **Figma community files (browse mode)** — Grid-based presentation of visual assets with subtle text overlays/controls.
- **Behance** — Portfolio-centric layout with focus on large visual previews and subtle project details.
- **Arc Browser** — Minimalist UI with subtle, atmospheric background colors and focus on content.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-charcoal: #000000;
  --color-canvas-white: #ffffff;
  --color-ash-gray: #393939;
  --color-ethereal-pink: #fce0db;

  /* Typography — Font Families */
  --font-font1: 'font1', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-playfair-display: 'Playfair Display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-font2: 'font2', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ui-sans-serif: 'ui-sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.1;
  --tracking-caption: -0.3px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.1;
  --tracking-body-sm: -0.35px;
  --text-body: 16px;
  --leading-body: 1.1;
  --tracking-body: -0.4px;
  --text-display: 238px;
  --leading-display: 0.8;
  --tracking-display: -9.52px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-6: 6px;
  --spacing-16: 16px;
  --spacing-29: 29px;
  --spacing-38: 38px;

  /* Layout */
  --section-gap: 38px;
  --card-padding: 16px;
  --element-gap: 6px;

  /* Named Radii */
  --radius-buttons: 9999px;
  --radius-sociallinks: 9999px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-charcoal: #000000;
  --color-canvas-white: #ffffff;
  --color-ash-gray: #393939;
  --color-ethereal-pink: #fce0db;

  /* Typography */
  --font-font1: 'font1', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-playfair-display: 'Playfair Display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-font2: 'font2', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ui-sans-serif: 'ui-sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.1;
  --tracking-caption: -0.3px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.1;
  --tracking-body-sm: -0.35px;
  --text-body: 16px;
  --leading-body: 1.1;
  --tracking-body: -0.4px;
  --text-display: 238px;
  --leading-display: 0.8;
  --tracking-display: -9.52px;

  /* Spacing */
  --spacing-6: 6px;
  --spacing-16: 16px;
  --spacing-29: 29px;
  --spacing-38: 38px;
}
```

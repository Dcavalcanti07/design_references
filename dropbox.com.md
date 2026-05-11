# Dropbox.com — Style Reference
> Pristine Digital Workspace. A highly organized, clean desktop environment where every element has its place and purpose.

**Theme:** light

Dropbox's visual style is that of a confident, established tech product: a pristine, spacious digital workspace with pops of vibrant interaction. Dominant bright surfaces and substantial, clear typography create an atmosphere of straightforward efficiency and trustworthiness. The strategic use of a vivid royal blue for primary calls to action, contrasted with deep graphite text and subtle, almost invisible backgrounds, maintains a focused and uncluttered user experience.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Graphite Black | `#000000` | `--color-graphite-black` | Primary heading and body text, button text on light backgrounds, strong accents. |
| Cloud White | `#ffffff` | `--color-cloud-white` | Default page backgrounds, primary surface for content areas like hero sections. |
| Off-White Canvas | `#f7f5f2` | `--color-off-white-canvas` | Secondary background color for subtle content separation, cards, and modal backdrops. |
| Deep Graphite | `#1e1919` | `--color-deep-graphite` | Main body text, navigation links, and button text on light-colored buttons — provides high contrast. |
| Royal Blue | `#0061fe` | `--color-royal-blue` | Primary Call-to-Action buttons, active navigation states, and interactive link elements — for consistent user guidance. |
| Muted Grey | `#716b61` | `--color-muted-grey` | Secondary body text, descriptive labels, and subtle UI elements like borders or inactive icons. |
| Almond Dust | `#eee9e2` | `--color-almond-dust` | Subtle surface elevation for cards or distinct content blocks, offering a soft visual break from the canvas. |
| Blush Pink | `#cd2f7b` | `--color-blush-pink` | Decorative accents or emphasis in specific UI contexts, often for highlighting information or badges. |
| Ash Border | `#c6c4c3` | `--color-ash-border` | Light border color for subtle separation of UI elements and form fields. |
| Dark Overlay Gradient | `linear-gradient(rgb(41, 44, 49), rgb(0, 0, 0))` | `--color-dark-overlay-gradient` | Background for specific sections or elements requiring a dark, immersive feel, often in subtle gradients. |

## Tokens — Typography

### Sharp Grotesk — Main headings and significant display text. Weight 500 maintains a robust yet approachable presence. · `--font-sharp-grotesk`
- **Substitute:** Montserrat
- **Weights:** 500
- **Sizes:** 18px, 26px, 40px
- **Line height:** 1.20, 1.30
- **Letter spacing:** normal
- **Role:** Main headings and significant display text. Weight 500 maintains a robust yet approachable presence.

### Sharp Grotesk 23 — Prominent subheadings, slightly lighter than main headings to create hierarchy and readability. · `--font-sharp-grotesk-23`
- **Substitute:** Montserrat
- **Weights:** 400
- **Sizes:** 32px
- **Line height:** 1.20
- **Letter spacing:** normal
- **Role:** Prominent subheadings, slightly lighter than main headings to create hierarchy and readability.

### Atlas Grotesk Web — Used for body text, navigation items, links, and various UI elements, providing clear, functional readability across different scales. · `--font-atlas-grotesk-web`
- **Substitute:** Inter
- **Weights:** 400, 500, 700
- **Sizes:** 12px, 14px, 16px, 20px
- **Line height:** 1.20, 1.43, 1.50, 1.57
- **Letter spacing:** normal
- **Role:** Used for body text, navigation items, links, and various UI elements, providing clear, functional readability across different scales.

### Times — System fallback for specific content or to provide a contrasting, traditional serif voice on occasion. · `--font-times`
- **Substitute:** serif
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.20
- **Letter spacing:** normal
- **Role:** System fallback for specific content or to provide a contrasting, traditional serif voice on occasion.

### Arial — System fallback for minor labels or tooltips when default sans-serif is required. · `--font-arial`
- **Substitute:** sans-serif
- **Weights:** 400
- **Sizes:** 13px
- **Line height:** 1.20
- **Letter spacing:** normal
- **Role:** System fallback for minor labels or tooltips when default sans-serif is required.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.2 | — | `--text-caption` |
| body | 14px | 1.43 | — | `--text-body` |
| body-lg | 16px | 1.5 | — | `--text-body-lg` |
| subheading | 18px | 1.2 | — | `--text-subheading` |
| heading-sm | 20px | 1.2 | — | `--text-heading-sm` |
| heading | 26px | 1.3 | — | `--text-heading` |
| heading-lg | 32px | 1.2 | — | `--text-heading-lg` |
| display | 40px | 1.2 | — | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 6px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 12 | 12px | `--spacing-12` |
| 24 | 24px | `--spacing-24` |
| 48 | 48px | `--spacing-48` |
| 72 | 72px | `--spacing-72` |
| 84 | 84px | `--spacing-84` |
| 96 | 96px | `--spacing-96` |
| 120 | 120px | `--spacing-120` |

### Border Radius

| Element | Value |
|---------|-------|
| large | 20px |
| links | 16px |
| buttons | 16px |
| default | 8px |
| navigation | 12px |

### Layout

- **Page max-width:** 1150px
- **Section gap:** 48px
- **Card padding:** 12px
- **Element gap:** 12px

## Components

### Primary CTA Button
**Role:** Calls to action, 'Get started' type buttons

Filled with Royal Blue (#0061fe) and Cloud White (#f7f5f2) text. Features 16px border-radius and generous padding (24px horizontal, 24px vertical) for a prominent, friendly presence.

### Navigation Link Button
**Role:** Top navigation items, secondary actions

Transparent background (rgba(0, 0, 0, 0)) with Deep Graphite (#1e1919) text. No explicit border-radius (0px), offering a sharp, integrated feel in navigation contexts. Padding is 12px horizontal, 16px vertical.

### Dark Navigation Link Button
**Role:** Navigation items for dark mode or contrasting sections

Transparent background (rgba(0, 0, 0, 0)) with Cloud White (#f7f5f2) text. No explicit border-radius (0px) and no padding, designed for inline text links that maintain hover effect.

### Informational Card
**Role:** Feature blocks, content organization

Subtle Almond Dust (#eee9e2) background with no shadows. Features a 0px border-radius, maintaining a sharp, clean edge for distinct content differentiation. Zero internal padding is specified from component variant data, implying content controls its own internal spacing.

### Lightweight Text Link Card
**Role:** Content container for simple text lists or outlines

Transparent background, no border-radius. Padding is 114.5px left and right, implying a container with substantial inline cushioning for its text content.

### Text Link with Arrow
**Role:** 'Learn more' or 'Read article' links

Deep Graphite (#1e1919) text on transparent background, no radius. The 16px padding on text-based links creates ample clickable area, often accompanied by an arrow icon.

## Do's and Don'ts

### Do
- Prioritize Royal Blue (#0061fe) for all primary call-to-action buttons, ensuring consistent visual hierarchy.
- Use Deep Graphite (#1e1919) for all primary body text and main navigation links against light backgrounds.
- Establish clear content separation using Off-White Canvas (#f7f5f2) for backgrounds and Almond Dust (#eee9e2) for elevated card surfaces.
- Apply 16px border-radius to all interactive buttons for a soft, approachable feel, unless explicitly overridden by component design.
- Maintain a sense of generous whitespace; ensure a minimum of 48px vertical spacing between major sections.
- Utilize Sharp Grotesk (Montserrat substitute) for all headlines to convey a clear, robust brand voice.
- For multi-column layouts, ensure column gaps are set to at least 24px to prevent visual crowding.

### Don't
- Avoid using highly saturated accent colors for text unless they are interactive links in Royal Blue.
- Do not introduce strong shadows; the design relies on subtle background color shifts for depth.
- Refrain from using overly decorative fonts; stick to Atlas Grotesk Web (Inter substitute) for all body copy and UI elements.
- Do not use border-radius values less than 8px, as the system prefers slightly rounded corners for most interaction points.
- Avoid overly dense information blocks; use generous paragraph line-heights (e.g., 1.5 for 16px text) and element spacing.
- Do not use stark black (#000000) for regular body text; reserve it for distinct headings or strong accents only.
- Do not use full-width layouts; constrain all content within a maximum width of 1150px.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Cloud White | `#ffffff` | Default page background, base canvas |
| 1 | Off-White Canvas | `#f7f5f2` | Secondary background, subtle content areas, large sections |
| 2 | Almond Dust | `#eee9e2` | Elevated card surfaces, distinct content blocks |

## Elevation

The design intentionally minimizes shadows, favoring clean, defined areas. Elevation is primarily achieved through distinct background color shifts (e.g., Off-White Canvas to Almond Dust) rather than drop shadows, creating a pristine and spacious feel. When shadows are used, they are minimal and soft, indicating interactivity rather than layered depth.

## Imagery

The visual language for imagery is a mix of product screenshots (often within high-fidelity mockups of devices), abstract conceptual illustrations, and tightly cropped, professional photography. Photography tends to be lifestyle-oriented but focused on work environments, with natural light and a slightly desaturated, clean aesthetic. Illustrations are minimalistic, often using geometric shapes and a limited palette of brand colors. Icons are outlined (often using Graphite Black or Muted Grey), with a consistent stroke weight, and monochrome. Imagery serves both to explain product features (screenshots) and to provide aspirational context (photography of people working), maintaining a balance between functional and atmospheric content. Images are typically contained within cards or sections, not often full-bleed.

## Agent Prompt Guide

Quick Color Reference: Text (#1e1919), Background (#ffffff), Primary CTA (#0061fe), Secondary Surface (#f7f5f2), Border (#c6c4c3).

1. Create a Hero Section: Cloud White (#ffffff) background. Headline 'Get to work, with a lot less work' at 40px Sharp Grotesk 500, Graphite Black (#000000). Body text 'Dropbox delivers tools...' at 16px Atlas Grotesk Web 400, Deep Graphite (#1e1919). Primary CTA Button 'Try Dropbox free' (Royal Blue #0061fe, Cloud White #f7f5f2 text, 16px radius, 24px padding), next to the text content.
2. Design a Feature Card: Almond Dust (#eee9e2) background, 0px border-radius. Title 'Technology' at 20px Atlas Grotesk Web 500, Deep Graphite (#1e1919). Body text at 14px Atlas Grotesk Web 400, Muted Grey (#716b61). Include a 'Learn more' Text Link with Arrow (Deep Graphite #1e1919 text, 16px padding).
3. Build a Navigation Bar: Cloud White (#ffffff) background. 'Dropbox' logo on the left. Navigation Link Buttons (transparent, Deep Graphite #1e1919 text, 12px horizontal, 16px vertical padding, 0px radius) for 'Products', 'Solutions', 'Enterprise', 'Pricing'. On the far right, a Royal Blue (#0061fe) Primary CTA Button for 'Get started'.

## Layout

The page primarily uses a max-width, centered containment model (approx. 1150px) for most content sections, ensuring readability across various screen sizes. The hero section often features a split layout with prominent text on the left and product screenshots or illustrations on the right. Content sections generally follow a consistent vertical rhythm with 48px section gaps. Many sections utilize a 2-column or 3-column grid for features and cards. The page frequently alternates between Cloud White (#ffffff) and Off-White Canvas (#f7f5f2) background bands to create visual rhythm and delineate distinct content blocks. The navigation is a sticky top bar, maintaining brand presence throughout scrolling.

## Similar Brands

- **Airtable** — Shares a clean, bright, highly functional UI with strategic use of vibrant accent colors against a predominantly neutral palette.
- **Webflow** — Similar focus on pristine, spacious layouts, clear sans-serif typography, and distinct card-based content organization.
- **Notion** — Emphasizes a highly legible, minimalist aesthetic with functional use of typography and clear information hierarchy within a light theme.
- **Google Workspace** — Features a distinct use of blue as a primary interactive brand color against a clean, white, and gray interface, prioritizing usability.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-graphite-black: #000000;
  --color-cloud-white: #ffffff;
  --color-off-white-canvas: #f7f5f2;
  --color-deep-graphite: #1e1919;
  --color-royal-blue: #0061fe;
  --color-muted-grey: #716b61;
  --color-almond-dust: #eee9e2;
  --color-blush-pink: #cd2f7b;
  --color-ash-border: #c6c4c3;
  --color-dark-overlay-gradient: #292c31;
  --gradient-dark-overlay-gradient: linear-gradient(rgb(41, 44, 49), rgb(0, 0, 0));

  /* Typography — Font Families */
  --font-sharp-grotesk: 'Sharp Grotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sharp-grotesk-23: 'Sharp Grotesk 23', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-atlas-grotesk-web: 'Atlas Grotesk Web', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-times: 'Times', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.2;
  --text-body: 14px;
  --leading-body: 1.43;
  --text-body-lg: 16px;
  --leading-body-lg: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.2;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.2;
  --text-heading: 26px;
  --leading-heading: 1.3;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1.2;
  --text-display: 40px;
  --leading-display: 1.2;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 6px;
  --spacing-12: 12px;
  --spacing-24: 24px;
  --spacing-48: 48px;
  --spacing-72: 72px;
  --spacing-84: 84px;
  --spacing-96: 96px;
  --spacing-120: 120px;

  /* Layout */
  --page-max-width: 1150px;
  --section-gap: 48px;
  --card-padding: 12px;
  --element-gap: 12px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;

  /* Named Radii */
  --radius-large: 20px;
  --radius-links: 16px;
  --radius-buttons: 16px;
  --radius-default: 8px;
  --radius-navigation: 12px;

  /* Surfaces */
  --surface-cloud-white: #ffffff;
  --surface-off-white-canvas: #f7f5f2;
  --surface-almond-dust: #eee9e2;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-graphite-black: #000000;
  --color-cloud-white: #ffffff;
  --color-off-white-canvas: #f7f5f2;
  --color-deep-graphite: #1e1919;
  --color-royal-blue: #0061fe;
  --color-muted-grey: #716b61;
  --color-almond-dust: #eee9e2;
  --color-blush-pink: #cd2f7b;
  --color-ash-border: #c6c4c3;
  --color-dark-overlay-gradient: #292c31;

  /* Typography */
  --font-sharp-grotesk: 'Sharp Grotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sharp-grotesk-23: 'Sharp Grotesk 23', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-atlas-grotesk-web: 'Atlas Grotesk Web', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-times: 'Times', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.2;
  --text-body: 14px;
  --leading-body: 1.43;
  --text-body-lg: 16px;
  --leading-body-lg: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.2;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.2;
  --text-heading: 26px;
  --leading-heading: 1.3;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1.2;
  --text-display: 40px;
  --leading-display: 1.2;

  /* Spacing */
  --spacing-12: 12px;
  --spacing-24: 24px;
  --spacing-48: 48px;
  --spacing-72: 72px;
  --spacing-84: 84px;
  --spacing-96: 96px;
  --spacing-120: 120px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
}
```

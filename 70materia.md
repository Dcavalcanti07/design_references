# 70Materia — Style Reference
> industrial minimalism

**Theme:** light

70Materia crafts a visual system of industrial minimalism: a stark black-and-white canvas provides an austere backdrop for carefully textured visual content. Typography is compact and precise, maintaining a high information density without feeling cramped. Component borders are razor-thin, and elements are primarily monochromatic, relying on strong contrast and subtle material variations to define structure rather than complex color palettes or deep shadows.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Absolute Black | `#000000` | `--color-absolute-black` | Primary text, heading text, critical borders, icons — provides crisp definition against light surfaces |
| Pure White | `#ffffff` | `--color-pure-white` | Page backgrounds, card surfaces, button backgrounds, inverse text for dark elements — a clean, expansive canvas |
| Off-Black | `#1e1e1e` | `--color-off-black` | Dark surface backgrounds (e.g., footer), primary filled button background — a slightly softer alternative to Absolute Black for larger dark areas |
| Light Concrete | `#bababa` | `--color-light-concrete` | Subtle background panels, light surface separators — imparts a sense of concrete or stone texture |
| Alpha Black | `#0000004d` | `--color-alpha-black` | Subtle overlays, contextual background tints — used for transparent dark effects |
| Dark Sand | `#876a30` | `--color-dark-sand` | Implicit in imagery; potentially for subtle highlights or decorative accents if introduced into UI components |
| Light Sand | `#d2c5aa` | `--color-light-sand` | Implicit in imagery; potentially for subtle highlights or decorative accents if introduced into UI components |

## Tokens — Typography

### Matter — General sans-serif for headings, body text, links, and various UI elements. Its clean, sharp forms underpin the industrial aesthetic. · `--font-matter`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 15px, 19px, 20px
- **Line height:** 1.20
- **Letter spacing:** normal
- **OpenType features:** `"tnum"`
- **Role:** General sans-serif for headings, body text, links, and various UI elements. Its clean, sharp forms underpin the industrial aesthetic.

### Matter Mono — Monospaced font for buttons, small labels, and precise data display. The tighter tracking at smaller sizes maintains legibility and a compact, technical feel. · `--font-matter-mono`
- **Substitute:** IBM Plex Mono
- **Weights:** 400
- **Sizes:** 10px, 12px
- **Line height:** 1.20, 1.30
- **Letter spacing:** -0.24px at 12px, -0.4px at 10px
- **OpenType features:** `"tnum"`
- **Role:** Monospaced font for buttons, small labels, and precise data display. The tighter tracking at smaller sizes maintains legibility and a compact, technical feel.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.2 | -0.4px | `--text-caption` |
| body | 15px | 1.2 | — | `--text-body` |
| subheading | 19px | 1.2 | — | `--text-subheading` |

## Tokens — Spacing & Shapes

**Base unit:** 8px

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 8 | 8px | `--spacing-8` |
| 12 | 12px | `--spacing-12` |
| 24 | 24px | `--spacing-24` |
| 100 | 100px | `--spacing-100` |
| 180 | 180px | `--spacing-180` |

### Border Radius

| Element | Value |
|---------|-------|
| buttons | 3px |

### Layout

- **Section gap:** 100px
- **Card padding:** 24px
- **Element gap:** 8px

## Components

### Primary Filled Button
**Role:** Interactive action button

Solid Off-Black background (#1e1e1e) with Pure White text (#ffffff), 3px border-radius, and 8px vertical / 24px horizontal padding. Uses Matter Mono at weight 400 with a slight letter-spacing.

### Secondary Outlined Button
**Role:** Interactive action button

Pure White background (#ffffff) with Absolute Black text (#000000) and a 1px Absolute Black (#000000) border, 3px border-radius, and 8px vertical / 24px horizontal padding. Uses Matter Mono at weight 400 with a slight letter-spacing.

### Navigation Link
**Role:** Top-level navigation items

Absolute Black text (#000000) with no specific background. Uses Matter Mono weight 400 with tight letter-spacing. Inherently interactive with hover state suggested by motion profile.

### Footer Dark Section
**Role:** Background for copyright and secondary links

Off-Black background (#1e1e1e) contrasting with the main content area. Contains Pure White text and links.

### Text Input / Form Field
**Role:** User input

Hypothesized: Absolute Black text (#000000) on a Pure White background (#ffffff) with a 1px Absolute Black (#000000) border. 3px border-radius based on general component rounding. Padding is likely 8px vertical and 12-16px horizontal to match button density.

## Do's and Don'ts

### Do
- Use Absolute Black (#000000) for all primary text and critical UI borders.
- Maintain a compact information density; use 1.2 line height for Matter font families.
- Apply 3px border-radius consistently for all interactive elements like buttons and input fields.
- Utilize Matter Mono exclusively for buttons and micro-text, employing its specific letter-spacing for legibility.
- Employ Off-Black (#1e1e1e) as a rich contrasting background for footer sections or prominent content blocks.
- Ensure all primary interactive elements are framed by a 1px border or clear background differentiation.
- Prioritize explicit contrast for text legibility; avoid low-contrast text on Light Concrete (#bababa).

### Don't
- Do not introduce strong accent colors into the main layout; stick to monochrome for structural elements and text.
- Avoid deep or complex shadows; elevation is primarily achieved through stark color contrast and flat surface changes.
- Do not deviate from the specified Matter and Matter Mono fonts; no system fonts or alternatives for core text.
- Desist from large, decorative hero typography; headlines should be Matter 400 at given sizes, compact and precise.
- Avoid fluid or organic shapes in UI components; maintain sharp edges and minimal radii for an industrial feel.
- Do not use generic padding for buttons; adhere strictly to 8px vertical and 24px horizontal padding.
- Refrain from using `normal` letter-spacing for Matter Mono; always apply its defined tighter tracking.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Light Concrete Base | `#bababa` | The foundational background for general content blocks, offering a subtle, material-like base. |
| 2 | Pure White Canvas | `#ffffff` | Primary content surfaces for cards, detail panels, and sections that require high contrast for text and interaction elements. |
| 3 | Off-Black Footer | `#1e1e1` | A contrasting, dark background for the page footer, visually anchoring the end of the content. |

## Imagery

The imagery focuses on materials and product applications: highly textural photography of concrete, stone, and raw surfaces. Treatments are typically full-bleed or large contained blocks, showcasing the intricate details of the material. Product shots are often close-ups, highlighting texture and finish rather than full product context. There are abstract compositions with measuring tools, reinforcing the 'laboratory of ideas' theme. Icons are absent from the overall design, reinforcing a clean, purely visual aesthetic for content. Imagery is dominant and essential for conveying the brand's core offering.

## Layout

The page uses a maximum-width contained layout, though specific measurements for `pageMaxWidth` are not provided, content is clearly constrained and centered. The hero section employs a full-width photographic background with understated text overlay. Section rhythm is driven by large vertical separations (100px) and a mix of full-width content blocks and two-column layouts. The content arrangement frequently alternates text-left/image-right or image-left/text-right, creating a structured flow. There's a clear emphasis on large, impactful imagery balanced with concise textual descriptions. Navigation is a minimal, top-aligned text menu.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #ffffff
border: #000000
accent: no distinct accent color
primary action: #1e1e1e (filled action)

Example Component Prompts:
1. Create a Primary Filled Button: Off-Black background (#1e1e1e), Pure White text (#ffffff), 3px radius, 8px vertical / 24px horizontal padding, Matter Mono weight 400, 12px size, -0.24px letter-spacing.
2. Create a Secondary Outlined Button: Pure White background (#ffffff), Absolute Black text (#000000), 1px Absolute Black border (#000000), 3px radius, 8px vertical / 24px horizontal padding, Matter Mono weight 400, 12px size, -0.24px letter-spacing.
3. Create a Navigation Link: Absolute Black text (#000000), Matter Mono weight 400, 12px size, -0.24px letter-spacing. No background or border.

## Similar Brands

- **Frama** — Explores material honesty, minimal UI, and monochromatic palettes with subtle texture.
- **B&B Italia** — Showcases high-end design through clean visuals, restrained color, and focus on product photography.
- **ArchDaily** — Uses a clean, high-contrast, text-heavy layout common in architecture and design publications with minimal UI ornamentation.
- **Materia (Finland)** — Similar focus on raw materials and minimalist aesthetic driven by strong photography and precise typography.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-absolute-black: #000000;
  --color-pure-white: #ffffff;
  --color-off-black: #1e1e1e;
  --color-light-concrete: #bababa;
  --color-alpha-black: #0000004d;
  --color-dark-sand: #876a30;
  --color-light-sand: #d2c5aa;

  /* Typography — Font Families */
  --font-matter: 'Matter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-matter-mono: 'Matter Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.2;
  --tracking-caption: -0.4px;
  --text-body: 15px;
  --leading-body: 1.2;
  --text-subheading: 19px;
  --leading-subheading: 1.2;

  /* Typography — Weights */
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-24: 24px;
  --spacing-100: 100px;
  --spacing-180: 180px;

  /* Layout */
  --section-gap: 100px;
  --card-padding: 24px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-sm: 3px;

  /* Named Radii */
  --radius-buttons: 3px;

  /* Surfaces */
  --surface-light-concrete-base: #bababa;
  --surface-pure-white-canvas: #ffffff;
  --surface-off-black-footer: #1e1e1;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-absolute-black: #000000;
  --color-pure-white: #ffffff;
  --color-off-black: #1e1e1e;
  --color-light-concrete: #bababa;
  --color-alpha-black: #0000004d;
  --color-dark-sand: #876a30;
  --color-light-sand: #d2c5aa;

  /* Typography */
  --font-matter: 'Matter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-matter-mono: 'Matter Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.2;
  --tracking-caption: -0.4px;
  --text-body: 15px;
  --leading-body: 1.2;
  --text-subheading: 19px;
  --leading-subheading: 1.2;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-24: 24px;
  --spacing-100: 100px;
  --spacing-180: 180px;

  /* Border Radius */
  --radius-sm: 3px;
}
```

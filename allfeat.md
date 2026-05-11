# Allfeat — Style Reference
> Midnight Digital Blueprint — a precise, high-contrast UI with neon accents on a dark canvas.

**Theme:** dark

Allfeat employs a 'midnight digital blueprint' aesthetic, combining a deep, dark canvas with vivid neon accents of teal and red. Typography is bold and concise, set in a unique custom font, fostering a high-tech, yet grounded, atmosphere. Components feature subtle inset borders and large radii, creating soft, tactile elements that pop against the dark background. The overall system feels technical and precise, with color used sparingly but impactfully to highlight key actions and information.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas Dark | `linear-gradient(rgb(21, 21, 21), rgb(255, 74, 95))` | `--color-canvas-dark` | Primary page background, card backgrounds for structural elements, dark text; Hero section background, creating a dramatic visual depth |
| Blueprint Gray | `#383835` | `--color-blueprint-gray` | Subtle card backgrounds, divider lines, and borders for content separation |
| Whisper White | `#fffbeb` | `--color-whisper-white` | Primary text color, element borders, ghost button text, light card backgrounds |
| Slate Text | `#b8b8b8` | `--color-slate-text` | Secondary text, muted helper text, subtle card backgrounds |
| Ghost Gray | `#a6a6a6` | `--color-ghost-gray` | Tertiary text, link outlines, decorative borders |
| Shadow Tint | `#504f4a` | `--color-shadow-tint` | Subtle inset box shadows, decorative icon strokes |
| Cyber Teal | `#00b18c` | `--color-cyber-teal` | Primary action backgrounds, headings, accent graphics. Signifies confirmation and active states |
| Impact Red | `#ff4a5f` | `--color-impact-red` | Highlight text, button borders for alternative actions, gradients. Commands attention |

## Tokens — Typography

### TASA Orbiter — Primary typeface for all text elements. Its geometric sharpness and varied weights from 400 to 600 convey a modern, technical authority. The large headline sizes with tight letter spacing create strong, impactful statements, while smaller sizes maintain readability with slightly looser tracking. · `--font-tasa-orbiter`
- **Substitute:** Montserrat
- **Weights:** 400, 500, 600
- **Sizes:** 13px, 14px, 16px, 18px, 19px, 20px, 24px, 25px, 40px, 54px, 56px
- **Line height:** 0.87, 0.95, 1.00, 1.10, 1.20
- **Letter spacing:** -0.0200em for display, 0.0200em for body text
- **Role:** Primary typeface for all text elements. Its geometric sharpness and varied weights from 400 to 600 convey a modern, technical authority. The large headline sizes with tight letter spacing create strong, impactful statements, while smaller sizes maintain readability with slightly looser tracking.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 13px | 1.1 | — | `--text-caption` |
| body | 16px | 1.2 | — | `--text-body` |
| subheading | 18px | 1.1 | — | `--text-subheading` |
| heading-sm | 24px | 1.1 | — | `--text-heading-sm` |
| heading | 40px | 0.95 | — | `--text-heading` |
| display | 54px | 0.87 | -0.8099999999999999px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 8px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 8 | 8px | `--spacing-8` |
| 16 | 16px | `--spacing-16` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 56 | 56px | `--spacing-56` |
| 64 | 64px | `--spacing-64` |
| 88 | 88px | `--spacing-88` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 12px |
| badges | 900px |
| images | 12px |
| buttons | 900px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgb(56, 56, 53) 0px 0px 0px 1px inset` | `--shadow-subtle` |
| subtle-2 | `rgba(255, 251, 235, 0.25) 0px 0px 0px 2px inset` | `--shadow-subtle-2` |

### Layout

- **Section gap:** 20px
- **Card padding:** 16px
- **Element gap:** 16px

## Components

### Filled Primary Button
**Role:** Main call to action button.

Background: Cyber Teal (#00b18c), Text: Canvas Dark (#151515), Border Radius: 900px. Padding: 0px vertical, 16px horizontal. Confident and inviting.

### Outlined Ghost Button
**Role:** Secondary call to action or navigation links.

Background: transparent, Text: Whisper White (#fffbeb), Border: 1px solid Whisper White (#fffbeb), Border Radius: 0px. Padding: 22px vertical, 22px-56px horizontal. Subdued yet actionable.

### Accent Outlined Button
**Role:** Specific actions requiring a distinct highlight.

Background: Canvas Dark (#151515), Text: Whisper White (#fffbeb), Border: 1px solid Impact Red (#ff4a5f), Border Radius: 900px. Padding: 1px vertical, 16px horizontal. Draws attention without being primary.

### Subtle Outlined Button
**Role:** Informational or less critical actions.

Background: Canvas Dark (#151515), Text: Whisper White (#fffbeb), Border: 1px solid rgba(255, 251, 235, 0.25), Border Radius: 900px. Padding: 1px vertical, 16px horizontal. Low-key interaction.

### Floating Circle Card
**Role:** Accent cards, often used for background textures or circular avatars.

Background: rgba(255, 251, 235, 0.05), Border Radius: 100%. No padding, no shadow. Creates visual interest and depth.

### Elevated Content Card
**Role:** Information blocks requiring slight visual separation.

Background: Whisper White (#fffbeb), Border Radius: 12px. Padding: 16px all sides. Minimalist presentation for content.

### Inset Border Card
**Role:** Structured content panels, often for feature descriptions.

Background: Canvas Dark (#151515), Border Radius: 12px. Inset Box Shadow: 1px solid Blueprint Gray (#383835). No padding. Defines clear content areas.

### Tag Badge
**Role:** Categorization or status indicators.

Background: transparent, Text: Whisper White (#fffbeb), Border Radius: 900px. Padding: 0px vertical, 24px horizontal. For displaying short, distinct labels.

### Highlight Badge
**Role:** Prominent status or key feature labels.

Background: Whisper White (#fffbeb), Text: Canvas Dark (#151515), Border Radius: 900px. Padding: 6px vertical, 24px horizontal (left pad 6px). Signals importance.

## Do's and Don'ts

### Do
- Prioritize Canvas Dark (#151515) as the primary background for all major sections to maintain a deep dark aesthetic.
- Use TASA Orbiter with tight letter spacing for headlines (e.g., -0.0200em at 54px) to create impactful typographic statements.
- Employ Cyber Teal (#00b18c) for primary interactive elements, ensuring all key actions are immediately identifiable and consistent.
- Round all interactive elements (buttons, badges) with a 900px border-radius to achieve a pill or circular shape.
- Use a subtle 1px inset border of Blueprint Gray (#383835) for content cards that require definition without heavy shadows.
- Maintain Whisper White (#fffbeb) as the primary text color against dark backgrounds for maximum contrast and readability.
- Apply 16px for vertical and horizontal padding within cards and for spacing between smaller elements to ensure comfortable density.

### Don't
- Avoid using bright, saturated colors for backgrounds or large areas; reserve accent colors for functional highlights.
- Do not deviate from the TASA Orbiter font family; its specific weights and letter spacing are critical to the brand’s technical feel.
- Do not introduce square or minimally rounded buttons; the 900px radius defines interactive elements.
- Do not use heavy drop shadows; implement subtle inset shadows for depth, consistent with the Blueprint Gray (#383835) style.
- Do not use generic system fonts; always specify TASA Orbiter or its closest substitute.
- Avoid excessive use of Impact Red (#ff4a5f); it should be reserved for specific emphasis or secondary actions, not default states.
- Do not use inconsistent spacing for padding and gaps; adhere to the 8px base unit with defined increments like 16px and 22px.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas Dark | `#151515` | Base page background, predominant dark surface. |
| 1 | Blueprint Gray Surface | `#383835` | Subtle background for card-like elements, navigation borders, providing minimal elevation. |
| 2 | Whisper White Panel | `#fffbeb` | Light-colored content cards that contrast sharply with the dark canvas, used for highlights. |
| 3 | Impact Red Highlight | `#ff4a5f` | Specific header sections and gradients that provide significant visual weight. |

## Elevation

- **Inset Border Card:** `inset 0px 0px 0px 1px rgb(56, 56, 53)`
- **Hover Button:** `inset 0px 0px 0px 2px rgba(255, 251, 235, 0.25)`

## Imagery

This site uses a mix of bespoke abstract illustrations and stylized product screenshots. Illustrations are highly geometric, featuring isometric compositions with glowing outlines and internal lighting effects, rendered in a palette of brand colors (teal, red, and desaturated white) against the dark background. They serve both decorative and explanatory roles, conveying complex technical concepts visually. Product screenshots are integrated into cards with a 12px border-radius, maintaining a consistent UI style. Icons are outlined, minimal, and monochromatic in Whisper White, maintaining a lightweight feel. Imagery density is moderate, used to break up text-heavy sections and add visual intrigue rather than being purely illustrative.

## Layout

The page structure is primarily full-bleed for sections, often anchoring content within a visually strong central area, without a strict pageMaxWidth. The hero section is full-bleed, featuring a large, vertically centered headline over a dramatic gradient background. Section rhythm alternates between full-width content blocks and compositions with two-column layouts featuring cards. Content often uses text-left/image-right or inverted arrangements. A prominent circular card grid is used for displaying partner logos or conceptual elements. Vertical spacing between sections is generous but not uniform, guided by content needs rather than a rigid fixed gap.

## Agent Prompt Guide

Quick Color Reference:
text: #fffbeb
background: #151515
border: #fffbeb
accent: #00b18c
primary action: #00b18c (filled action)

Example Component Prompts:
Create a hero section title: 'Allfeat foundation to connect all music data' using TASA Orbiter 54px bold, line-height 0.87, letter-spacing -0.81px, color #fffbeb, centered on a linear-gradient(#151515, #ff4a5f) background.
Create a Cyber Teal button: '#00b18c background, #151515 text, TASA Orbiter 16px 500, 900px border-radius, 0px vertical 16px horizontal padding. Label 'Get started'.
Create an Inset Border Card: '#151515 background, 12px border-radius, inset 0px 0px 0px 1px #383835 box-shadow. Inside, place a 'Whisper White' text label '#fffbeb, TASA Orbiter 18px 400, line-height 1.1' and a 'Slate Text' paragraph '#b8b8b8, TASA Orbiter 16px 400, line-height 1.2'.
Create a Ghost Button: 'transparent background, #fffbeb text, 1px solid #fffbeb border, 0px border-radius, 22px vertical 56px horizontal padding. Label 'Overview'.

## Similar Brands

- **Aptos** — Dark UI with vibrant, functional accent colors and geometric, angular graphics.
- **Lens Protocol** — Monochromatic dark design with a single complementary accent color (green/teal) and bold typography.
- **Web3 Foundation** — Technical dark theme with subtle gradients, clear content hierarchy, and a focus on data/connection visuals.
- **Polygon** — Use of deep backgrounds with glowing, outlined illustrations and strong, modern typography.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-dark: #151515;
  --gradient-canvas-dark: linear-gradient(rgb(21, 21, 21), rgb(255, 74, 95));
  --color-blueprint-gray: #383835;
  --color-whisper-white: #fffbeb;
  --color-slate-text: #b8b8b8;
  --color-ghost-gray: #a6a6a6;
  --color-shadow-tint: #504f4a;
  --color-cyber-teal: #00b18c;
  --color-impact-red: #ff4a5f;

  /* Typography — Font Families */
  --font-tasa-orbiter: 'TASA Orbiter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 1.1;
  --text-body: 16px;
  --leading-body: 1.2;
  --text-subheading: 18px;
  --leading-subheading: 1.1;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.1;
  --text-heading: 40px;
  --leading-heading: 0.95;
  --text-display: 54px;
  --leading-display: 0.87;
  --tracking-display: -0.8099999999999999px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-88: 88px;

  /* Layout */
  --section-gap: 20px;
  --card-padding: 16px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-xl: 12px;
  --radius-full: 900px;

  /* Named Radii */
  --radius-cards: 12px;
  --radius-badges: 900px;
  --radius-images: 12px;
  --radius-buttons: 900px;

  /* Shadows */
  --shadow-subtle: rgb(56, 56, 53) 0px 0px 0px 1px inset;
  --shadow-subtle-2: rgba(255, 251, 235, 0.25) 0px 0px 0px 2px inset;

  /* Surfaces */
  --surface-canvas-dark: #151515;
  --surface-blueprint-gray-surface: #383835;
  --surface-whisper-white-panel: #fffbeb;
  --surface-impact-red-highlight: #ff4a5f;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-dark: #151515;
  --color-blueprint-gray: #383835;
  --color-whisper-white: #fffbeb;
  --color-slate-text: #b8b8b8;
  --color-ghost-gray: #a6a6a6;
  --color-shadow-tint: #504f4a;
  --color-cyber-teal: #00b18c;
  --color-impact-red: #ff4a5f;

  /* Typography */
  --font-tasa-orbiter: 'TASA Orbiter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 1.1;
  --text-body: 16px;
  --leading-body: 1.2;
  --text-subheading: 18px;
  --leading-subheading: 1.1;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.1;
  --text-heading: 40px;
  --leading-heading: 0.95;
  --text-display: 54px;
  --leading-display: 0.87;
  --tracking-display: -0.8099999999999999px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-88: 88px;

  /* Border Radius */
  --radius-xl: 12px;
  --radius-full: 900px;

  /* Shadows */
  --shadow-subtle: rgb(56, 56, 53) 0px 0px 0px 1px inset;
  --shadow-subtle-2: rgba(255, 251, 235, 0.25) 0px 0px 0px 2px inset;
}
```

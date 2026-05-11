# Frontify — Style Reference
> Architectural blueprint on soft linen

**Theme:** light

Frontify employs a sophisticated, clean, brand-centric aesthetic, combining a calm, off-white canvas with sharp black typography and deliberate, functional infusions of color. The system balances highly compact, precise type with generous negative space, creating an impression of clarity and efficiency. A muted, almost monochrome palette ensures focus on content, with specific, vivid accents used strategically for highlighting interactive elements or brand punctuation. Components are lightweight with softened corners, contributing to a modern, approachable feel.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Inkwell Black | `#111110` | `--color-inkwell-black` | Primary text, button backgrounds, strong borders, dark surface elements, primary action, footer background |
| Paper White | `#f0f0eb` | `--color-paper-white` | Main page background, secondary text, subtle borders, UI element backgrounds |
| True White | `#ffffff` | `--color-true-white` | Button text on dark backgrounds, selected interactive states, icon fills |
| Canvas Muted | `#e1e1db` | `--color-canvas-muted` | Card backgrounds, subtle surface elevations, tertiary backgrounds |
| Stone Whisper | `#d7d7cf` | `--color-stone-whisper` | Section backgrounds, subtle graphical elements, body backgrounds |
| Deep Pewter | `#464643` | `--color-deep-pewter` | Muted body text, secondary borders |
| Charcoal Grey | `#000000` | `--color-charcoal-grey` | Input borders, decorative fills, some icon fills |
| Pale Granite | `#cbcbc5` | `--color-pale-granite` | Subtle border strokes |
| Dusty Sage | `#bfbfb8` | `--color-dusty-sage` | Placeholder text, secondary icon colors, subtle lines |
| Slate Echo | `#575753` | `--color-slate-echo` | Card text, muted link hover states |
| Forest Tint | `#042a2b` | `--color-forest-tint` | Decorative background fills on cards, certain icon elements, dark text elements |
| Flame Orange | `#ff3b00` | `--color-flame-orange` | Accent for highlighted text categories, decorative icon fills, active border states |
| Violet Streak | `linear-gradient(90deg, rgba(255, 255, 255, 0) 0%, rgba(255, 255, 255, 0.1) 10%, rgb(182, 10, 227) 50%, rgba(255, 255, 255, 0.1) 90%, rgba(255, 255, 255, 0) 100%)` | `--color-violet-streak` | Decorative accent for internal elements, button border hover state; Decorative gradient for overlays or highlighted zones, providing a soft, shifting visual anchor |

## Tokens — Typography

### ABC Diatype — General body text, navigation elements, buttons, input fields, and all other functional UI text. Its compact shape ensures efficiency while maintaining legibility. · `--font-abc-diatype`
- **Substitute:** Inter
- **Weights:** 400, 500
- **Sizes:** 14px, 18px
- **Line height:** 1.00, 1.30, 1.35, 1.50
- **Letter spacing:** 0.0100em
- **Role:** General body text, navigation elements, buttons, input fields, and all other functional UI text. Its compact shape ensures efficiency while maintaining legibility.

### Cranny — Headlines and prominent display text that convey a sense of elegance and sophistication. The lighter weights at large sizes create impact through restraint rather than volume. Its slightly wider tracking at smaller sizes improves legibility, while negative tracking at large sizes compacts headlines. · `--font-cranny`
- **Substitute:** Playfair Display
- **Weights:** 300, 400
- **Sizes:** 16px, 18px, 20px, 24px, 28px, 32px, 40px, 61px, 80px, 96px
- **Line height:** 0.91, 1.00, 1.10, 1.30, 1.50
- **Letter spacing:** -0.0070em (at larger sizes), 0.0080em, 0.0100em
- **Role:** Headlines and prominent display text that convey a sense of elegance and sophistication. The lighter weights at large sizes create impact through restraint rather than volume. Its slightly wider tracking at smaller sizes improves legibility, while negative tracking at large sizes compacts headlines.

### Satoshi — Monospaced text, code snippets, and small utility text for technical precision and content differentiation. · `--font-satoshi`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 14px
- **Line height:** 1.30
- **Letter spacing:** 0.0100em
- **Role:** Monospaced text, code snippets, and small utility text for technical precision and content differentiation.

### Cabinetgrotesk — Used for specific emphasis in body copy or for short, impactful statements. Its heavier weight provides a robust counterpoint to the delicacy of Cranny and the functional clarity of ABC Diatype. · `--font-cabinetgrotesk`
- **Substitute:** Archivo
- **Weights:** 500, 700
- **Sizes:** 16px, 40px
- **Line height:** 1.00, 1.20
- **Letter spacing:** 0.0100em
- **Role:** Used for specific emphasis in body copy or for short, impactful statements. Its heavier weight provides a robust counterpoint to the delicacy of Cranny and the functional clarity of ABC Diatype.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 14px | 1.5 | 0.14px | `--text-caption` |
| body | 18px | 1.5 | 0.18px | `--text-body` |
| subheading | 24px | 1.3 | 0.24px | `--text-subheading` |
| heading-sm | 28px | 1.1 | 0.22px | `--text-heading-sm` |
| heading | 40px | 1.1 | 0.4px | `--text-heading` |
| heading-lg | 61px | 1 | -0.427px | `--text-heading-lg` |
| display | 96px | 0.91 | -0.672px | `--text-display` |

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
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 128 | 128px | `--spacing-128` |
| 160 | 160px | `--spacing-160` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 8px |
| images | 18px |
| inputs | 0px |
| buttons | 24px |
| navItems | 32px |
| smallComponents | 4px |

### Layout

- **Section gap:** 48px
- **Card padding:** 32px
- **Element gap:** 8px

## Components

### Primary Filled Button
**Role:** Call to action, main navigation buttons

Solid Inkwell Black background (#111110) with True White text (#ffffff), 24px border-radius, and 12px vertical | 16px horizontal padding. A substantial, clear action button.

### Outlined Button (Dark border)
**Role:** Secondary actions, ghost buttons, calls to explore

Transparent background with an Inkwell Black (#111110) 1px border and Inkwell Black text (#111110). Uses 24px border-radius, and 12px vertical | 16px horizontal padding. Provides a clear alternative without demanding primary attention.

### Outlined Button (Light border)
**Role:** Ghost buttons on dark backgrounds

Transparent background with a True White (#ffffff) 1px border and True White text (#ffffff). Uses 24px border-radius, and 12px vertical | 16px horizontal padding. Maintains visibility on dark canvas areas.

### Subtle Card
**Role:** Content containers, feature blocks on light backgrounds

Canvas Muted background (#e1e1db) with an 8px border-radius, no shadow, and no internal padding. Designed to blend softly into the background while defining content areas.

### Ghost Card
**Role:** Decorative or transparent content groupings

Fully transparent background, 0px border-radius, no shadow, and no internal padding. Used when content itself defines its boundaries or for underlying visual effects.

### Small Radius Card
**Role:** Tight content groupings, embedded UI elements

Fully transparent background, 4px border-radius, no shadow, and no internal padding. For smaller, more integrated components.

### Tertiary Button
**Role:** Subtle calls to action or embedded buttons

Canvas Muted background (#e1e1db) with Inkwell Black text (#111110). Uses a 40px border-radius and 0px vertical | 40px horizontal padding. Used for distinct, often larger, button areas that don't need the prominence of a primary button.

### Underline Input
**Role:** Form input fields

Transparent background, Inkwell Black (#111110) text, with only a 1px bottom border of Charcoal Grey (#000000). Placeholder text uses Dusty Sage (#bfbfb8). Focus state likely changes the border color to an accent.

## Do's and Don'ts

### Do
- Always use Paper White (#f0f0eb) as the default page canvas, creating a consistent light background.
- Apply ABC Diatype for all body text and UI labels, ensuring clarity and efficiency with its 0.0100em letter spacing.
- Reserve Cranny font for headlines and display text, leveraging its elegant weight 300 or 400 with size-dependent letter spacing for sophisticated visual hierarchy.
- Button corners should consistently have a 24px border-radius for primary and outlined buttons, and 40px for larger tertiary buttons, maintaining a soft, approachable feel.
- Utilize Inkwell Black (#111110) for primary button backgrounds and primary text, creating high contrast and clear calls to action.
- Implement a default element gap of 8px for vertical and horizontal spacing between small UI elements, establishing a comfortable density.
- Card backgrounds should default to Canvas Muted (#e1e1db) with an 8px border-radius, providing subtle visual separation without heavy borders or shadows.

### Don't
- Avoid using multiple chromatic colors for interactive elements; stick to Flame Orange (#ff3b00) or Violet Streak (#b60ae3) for accents, never for full button fills.
- Do not use heavy shadows or multi-layered elevation; surfaces are defined by subtle background changes and light borders, not Z-axis depth.
- Do not use default system fonts; ABC Diatype, Cranny, Satoshi, and Cabinetgrotesk are the only approved typefaces.
- Avoid arbitrary letter spacing; use the defined -0.007em (for large Cranny) or 0.010em (for ABC Diatype) for precise type rendering.
- Do not introduce new border-radius values; adhere strictly to 4px, 8px, 18px, 24px, 32px, and 40px for components as specified.
- Never use less than 48px vertical spacing between major page sections to maintain a spacious and breathable layout.
- Do not introduce new accent gradients. The 'Gradient Aura' provides a controlled, decorative element that should not be replicated or modified.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Paper White | `#f0f0eb` | Primary page background, expansive content areas |
| 1 | Canvas Muted | `#e1e1db` | Card backgrounds, secondary container surfaces |
| 2 | Stone Whisper | `#d7d7cf` | Section dividers, underlying contextual elements |

## Imagery

Imagery on Frontify prioritizes clean, conceptual visuals, favoring product-focused photography and abstract graphics over lifestyle shots. Photography, when used, features high-key lighting with subjects often isolated or in calm, desaturated environments, reinforcing a focused and composed atmosphere. Illustrations are minimal and abstract, often using subtle gradients or geometric forms for decorative or atmospheric effect, without heavy outlines or bold color blocks. Icons are primarily outlined, showcasing a light stroke weight, and are monochromatic in Inkwell Black, maintaining the system's clean, functional aesthetic. Imagery serves primarily as decorative atmosphere or explanatory context rather than product showcases or social proof, maintaining a text-dominant layout with generous negative space.

## Layout

The page structure employs a mix of full-bleed and contained sections. The hero typically features a full-bleed visual or background with text meticulously centered. Content flows in distinct blocks with consistent vertical spacing of 48px between sections, often presented as alternating light and muted background bands. Content arrangement frequently uses centered stacks for headlines and subtext, transitioning into alternating text-left/image-right or vertical features. Card grids, where present, are typically 3-column. The design emphasizes spaciousness, allowing elements to breathe. Navigation is handled by a sticky top bar with a centered logo and right-aligned actions, providing persistent access without intruding on content.

## Agent Prompt Guide

Quick Color Reference:
text: #111110
background: #f0f0eb
border: #111110
accent: #ff3b00
primary action: #111110 (filled action)

Example Component Prompts:
Create a Primary Action Button: #111110 background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.

Create a feature card: Canvas Muted background (#e1e1db), 8px border-radius, no shadow. Card title in Cranny weight 400 at 24px, #111110. Body text in ABC Diatype weight 400 at 14px, #111110. Padding of 32px.

## Similar Brands

- **Figma** — Shares a clean, almost monochrome interface, compact functional typography, and strategic use of a single vibrant accent color to denote interactivity.
- **Linear** — Similar focus on efficient, high-contrast typography, generous whitespace, and a polished, understated aesthetic that prioritizes content and tool functionality.
- **Notion** — Employs a minimalist UI, primarily grey scale, functional typography, and subtle design cues that put content at the forefront without visual distraction.
- **Webflow** — Features a light theme with clear separation of UI elements, strong typographic hierarchy, and a professional, yet approachable, visual tone.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-inkwell-black: #111110;
  --color-paper-white: #f0f0eb;
  --color-true-white: #ffffff;
  --color-canvas-muted: #e1e1db;
  --color-stone-whisper: #d7d7cf;
  --color-deep-pewter: #464643;
  --color-charcoal-grey: #000000;
  --color-pale-granite: #cbcbc5;
  --color-dusty-sage: #bfbfb8;
  --color-slate-echo: #575753;
  --color-forest-tint: #042a2b;
  --color-flame-orange: #ff3b00;
  --color-violet-streak: #b60ae3;
  --gradient-violet-streak: linear-gradient(90deg, rgba(255, 255, 255, 0) 0%, rgba(255, 255, 255, 0.1) 10%, rgb(182, 10, 227) 50%, rgba(255, 255, 255, 0.1) 90%, rgba(255, 255, 255, 0) 100%);

  /* Typography — Font Families */
  --font-abc-diatype: 'ABC Diatype', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-cranny: 'Cranny', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-satoshi: 'Satoshi', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-cabinetgrotesk: 'Cabinetgrotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.5;
  --tracking-caption: 0.14px;
  --text-body: 18px;
  --leading-body: 1.5;
  --tracking-body: 0.18px;
  --text-subheading: 24px;
  --leading-subheading: 1.3;
  --tracking-subheading: 0.24px;
  --text-heading-sm: 28px;
  --leading-heading-sm: 1.1;
  --tracking-heading-sm: 0.22px;
  --text-heading: 40px;
  --leading-heading: 1.1;
  --tracking-heading: 0.4px;
  --text-heading-lg: 61px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -0.427px;
  --text-display: 96px;
  --leading-display: 0.91;
  --tracking-display: -0.672px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-128: 128px;
  --spacing-160: 160px;

  /* Layout */
  --section-gap: 48px;
  --card-padding: 32px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 18px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;
  --radius-3xl-3: 40px;

  /* Named Radii */
  --radius-cards: 8px;
  --radius-images: 18px;
  --radius-inputs: 0px;
  --radius-buttons: 24px;
  --radius-navitems: 32px;
  --radius-smallcomponents: 4px;

  /* Surfaces */
  --surface-paper-white: #f0f0eb;
  --surface-canvas-muted: #e1e1db;
  --surface-stone-whisper: #d7d7cf;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-inkwell-black: #111110;
  --color-paper-white: #f0f0eb;
  --color-true-white: #ffffff;
  --color-canvas-muted: #e1e1db;
  --color-stone-whisper: #d7d7cf;
  --color-deep-pewter: #464643;
  --color-charcoal-grey: #000000;
  --color-pale-granite: #cbcbc5;
  --color-dusty-sage: #bfbfb8;
  --color-slate-echo: #575753;
  --color-forest-tint: #042a2b;
  --color-flame-orange: #ff3b00;
  --color-violet-streak: #b60ae3;

  /* Typography */
  --font-abc-diatype: 'ABC Diatype', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-cranny: 'Cranny', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-satoshi: 'Satoshi', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-cabinetgrotesk: 'Cabinetgrotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.5;
  --tracking-caption: 0.14px;
  --text-body: 18px;
  --leading-body: 1.5;
  --tracking-body: 0.18px;
  --text-subheading: 24px;
  --leading-subheading: 1.3;
  --tracking-subheading: 0.24px;
  --text-heading-sm: 28px;
  --leading-heading-sm: 1.1;
  --tracking-heading-sm: 0.22px;
  --text-heading: 40px;
  --leading-heading: 1.1;
  --tracking-heading: 0.4px;
  --text-heading-lg: 61px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -0.427px;
  --text-display: 96px;
  --leading-display: 0.91;
  --tracking-display: -0.672px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-128: 128px;
  --spacing-160: 160px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 18px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;
  --radius-3xl-3: 40px;
}
```

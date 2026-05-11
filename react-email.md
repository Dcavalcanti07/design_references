# React Email — Style Reference
> Midnight Terminal Glow

**Theme:** dark

React Email establishes a cosmic dark mode identity, where deep blacks and subtle grays form a backdrop for technical content. A glowing cyan accent provides functional emphasis and a sense of 'switched on' interactivity, often through blurred gradients that mimic digital light. Typography leans into monospace for code examples and clean sans-serif for UI, maintaining legibility and a developer-centric aesthetic within a spacious, structured layout. Components are presented with minimal borders and controlled translucency, allowing content to breathe and maintaining a focused, high-tech atmosphere.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Carbon | `#000000` | `--color-carbon` | Deepest canvas background, primary card surfaces, prominent text when against light surfaces |
| Inkwell | `#0f0f10` | `--color-inkwell` | Slightly lighter card backgrounds, subtle distinctions from pure Carbon |
| Charcoal | `#27272a` | `--color-charcoal` | Page background, main surface for content sections |
| Porcelain | `#ffffff` | `--color-porcelain` | Primary text on dark backgrounds, active button fills, light surface highlights |
| Starlight | `#e5e7eb` | `--color-starlight` | Border colors, muted text, ghost button borders, secondary text on some dark surfaces |
| Cloudburst | `#abafb4` | `--color-cloudburst` | Placeholder text, subtly faded text on dark backgrounds, secondary body text |
| #6e727a | `#6e727a` | `--color-6e727a` | Muted text, badge text, less prominent content |
| Skyline Gray | `#99a1af` | `--color-skyline-gray` | Tertiary text, subtle icon strokes, secondary button text |
| Lunar Dust | `#cad5e2` | `--color-lunar-dust` | Light text on dark surfaces, inverse labels, and high-contrast captions |
| Code Orange | `#ffb86a` | `--color-code-orange` | Syntax highlighting, decorative icon elements – represents a functional accent |
| Cyber Cyan | `#52e1fe` | `--color-cyber-cyan` | Blue text accent for links, tags, and emphasized short phrases. Do not promote it to the primary CTA color |
| Code Blue Light | `#364153` | `--color-code-blue-light` | Secondary body text, navigation labels, and subdued headings. Do not promote it to the primary CTA color |
| Electric Blue Glow | `radial-gradient(rgba(37, 99, 235, 0.1) 0%, rgba(0, 0, 0, 0) 80%)` | `--color-electric-blue-glow` | Subtle background glows, interaction states, and radial gradient accents |

## Tokens — Typography

### Inter — Primary sans-serif font for all headings, body text, UI elements, and interactive components. The variable letter spacing creates a tighter feel at larger sizes. · `--font-inter`
- **Substitute:** system-ui
- **Weights:** 400, 460, 500
- **Sizes:** 12px, 14px, 16px, 18px, 20px, 24px, 35px, 68px
- **Line height:** 0.94, 1.00, 1.20, 1.33, 1.40, 1.43, 1.50, 1.56, 2.00
- **Letter spacing:** -0.0500em at 68px, -0.0250em at 35px, -0.0100em at 24px, -0.0080em at 20px, normal at 18px and below
- **Role:** Primary sans-serif font for all headings, body text, UI elements, and interactive components. The variable letter spacing creates a tighter feel at larger sizes.

### CommitMono — Monospace font used specifically for code blocks, terminal output, and technical labels, providing a distinct developer-centric aesthetic. · `--font-commitmono`
- **Substitute:** monospace
- **Weights:** 400
- **Sizes:** 13px, 14px
- **Line height:** 1.30, 1.33, 1.40, 1.43, 1.55
- **Letter spacing:** normal
- **Role:** Monospace font used specifically for code blocks, terminal output, and technical labels, providing a distinct developer-centric aesthetic.

### -apple-system — System font fallback, used for some secondary content and list items, particularly in the documentation. The 'liga' 0 feature disables ligatures for a cleaner display. · `--font-apple-system`
- **Substitute:** system-ui
- **Weights:** 400, 600, 700
- **Sizes:** 14px, 25px
- **Line height:** 1.44, 1.55
- **Letter spacing:** normal
- **OpenType features:** `'liga' 0`
- **Role:** System font fallback, used for some secondary content and list items, particularly in the documentation. The 'liga' 0 feature disables ligatures for a cleaner display.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.5 | — | `--text-caption` |
| body | 14px | 1.4 | — | `--text-body` |
| body-lg | 16px | 1.4 | — | `--text-body-lg` |
| subheading | 18px | 1.56 | — | `--text-subheading` |
| heading | 20px | 1.43 | -0.008px | `--text-heading` |
| heading-lg | 24px | 1.33 | -0.01px | `--text-heading-lg` |
| display | 35px | 1.2 | -0.025px | `--text-display` |
| display-xl | 68px | 0.94 | -0.05px | `--text-display-xl` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 8 | 8px | `--spacing-8` |
| 12 | 12px | `--spacing-12` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 56 | 56px | `--spacing-56` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 96 | 96px | `--spacing-96` |
| 104 | 104px | `--spacing-104` |
| 160 | 160px | `--spacing-160` |
| 216 | 216px | `--spacing-216` |

### Border Radius

| Element | Value |
|---------|-------|
| lg | 18px |
| md | 12px |
| sm | 8px |
| xl | 24px |
| xs | 2px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(255, 255, 255, 0.1) 0px 0px 0px 1px inset, rgba(255,...` | `--shadow-subtle` |
| subtle-2 | `rgba(0, 0, 0, 0.05) 0px 1px 2px 0px` | `--shadow-subtle-2` |
| md | `rgba(37, 174, 186, 0.1) 0px 0px 9px 4px` | `--shadow-md` |

### Layout

- **Section gap:** 24px
- **Card padding:** 16px
- **Element gap:** 16px

## Components

### Ghost Button - Default
**Role:** Interactive element

Ghost button with transparent background and light gray text on dark surfaces. `backgroundColor: rgba(0, 0, 0, 0)`, `color: #abafb4`, `borderRadius: 4px`, `padding: 6px`.

### Ghost Button - Rounded Cyan Text
**Role:** Interactive element

Ghost button with transparent background, rounded corners, and Cyber Cyan text, often for less prominent actions or links. `backgroundColor: rgba(0, 0, 0, 0)`, `color: #52e1fe`, `borderRadius: 12px`, `padding: 10px`.

### Action Button - Filled
**Role:** Primary Call-to-action

Filled button with a white background and black text, used for primary actions. `backgroundColor: #ffffff`, `color: #000000`, `borderRadius: 12px`, `padding: 0px 16px`.

### Ghost Button - Hero Large
**Role:** Prominent ghost action

Large ghost button with very rounded corners and a slightly subdued text color, used in hero sections. `backgroundColor: rgba(0, 0, 0, 0)`, `color: rgba(241, 247, 254, 0.71)`, `borderRadius: 20px`, `padding: 24px`.

### Card - Basic
**Role:** Content container

Simple dark card with slightly rounded corners and no shadow. `backgroundColor: #000000`, `borderRadius: 8px`, `padding: 16px`.

### Card - Rounded
**Role:** Content container

Card with larger rounded corners and transparent side padding. `backgroundColor: #000000`, `borderRadius: 24px`, `padding: 16px 0px`.

### Card - Subtle Shadow
**Role:** Content container / interactive element

Slightly elevated card with small radius and a subtle shadow on a Charcoal background. `backgroundColor: #0f0f10`, `borderRadius: 6px`, `boxShadow: rgba(0, 0, 0, 0.05) 0px 1px 2px 0px`, `padding: 8px 24px 16px 24px`.

### Card - Translucent Bordered
**Role:** Highlight / elevated container

Card with a translucent background and an inset white border, prominent for elevated content. `backgroundColor: rgba(23, 23, 23, 0.6)`, `borderRadius: 20px`, `boxShadow: rgba(255, 255, 255, 0.1) 0px 0px 0px 1px inset, rgba(255, 255, 255, 0.15) 0px 1px 0px 0px inset`, `padding: 0px`.

### Badge - Monospace
**Role:** Inline tag/label

Transparent background badge with muted text, typically for code or syntax labels. `backgroundColor: rgba(0, 0, 0, 0)`, `color: #6e727a`, `borderRadius: 0px`, `padding: 0px`.

## Do's and Don'ts

### Do
- Prioritize Charcoal (#27272a) as the primary background color for main content areas and Carbon (#000000) for nested surface elements like cards.
- Use Inter font for all UI text, headings, and body, adhering to the variable letter spacing (tighter at larger sizes) for visual precision.
- Apply CommitMono for all code examples, technical labels, and console-like text for its distinct monospace appearance.
- Use Starlight (#e5e7eb) for all borders, dividers, and inactive states to provide subtle visual separation on dark backgrounds.
- Emphasize interactive elements and highlights with Cyber Cyan (#52e1fe) for text or small background accents.
- Utilize a base spacing unit of 4px, building up elements with 8px increments for buttons and 16px for card padding.
- Round corners with 8px or 12px for most interactive components, opting for 24px on larger cards for a softer feel.

### Don't
- Avoid using bright, saturated colors for backgrounds or large areas; reserve them strictly for functional accents and interactive states.
- Do not use generic system shadows; instead, apply the specific translucent inset shadow for elevated components: `rgba(255, 255, 255, 0.1) 0px 0px 0px 1px inset, rgba(255, 255, 255, 0.15) 0px 1px 0px 0px inset`.
- Do not introduce new font families beyond Inter, CommitMono, and system fallbacks; visual consistency relies on this limited palette.
- Avoid heavy borders or solid backgrounds on ghost buttons; they should remain translucent with only text or subtle inner glow accents.
- Do not vary letter spacing on CommitMono; it should always be 'normal' to maintain its code-like presentation.
- Refrain from deviating from the established border radii; the specific values (2px, 8px, 12px, 18px, 24px) contribute significantly to the component feel.
- Avoid breaking content out of the established max-width guidelines; maintain the contained content flow with generous page margins.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Charcoal | `#27272a` | Primary page background, base canvas. |
| 1 | Inkwell | `#0f0f10` | Secondary background for cards with subtle elevation. |
| 2 | Carbon | `#000000` | Dominant card backgrounds, code editor panels, and floating modals. |

## Elevation

- **Card - Subtle Shadow:** `rgba(0, 0, 0, 0.05) 0px 1px 2px 0px`
- **Card - Translucent Bordered:** `rgba(255, 255, 255, 0.1) 0px 0px 0px 1px inset, rgba(255, 255, 255, 0.15) 0px 1px 0px 0px inset`

## Imagery

This system primarily uses abstract, dark-toned graphics with strong light accents and translucent textures. Imagery consists of stylized 3D wireframes, blurred radial gradients (like Electric Blue Glow), and product screenshots embedded within dark-themed UIs. Photography is absent. Icons are typically outlined or filled in monochromatic or accent colors (Cyber Cyan). Imagery functions decoratively to set a high-tech atmosphere and illustratively to explain functionality through code examples and UI snippets, maintaining a text-dominant but visually rich experience.

## Layout

The page primarily uses a full-bleed dark background aesthetic. Content is generally held within a maximum width, centered, with generous horizontal padding, creating spacious reading areas. The hero section is full-bleed, dominated by a large headline and a vibrant blue abstract graphic. Sections often alternate between full-bleed dark panels and slightly lighter dark content blocks. Content arrangement frequently features centered text stacks, or two-column layouts with text on one side and a product visual (code snippet, UI screenshot) on the other. Navigation consists of a sticky top bar with minimal links and a prominent GitHub star count.

## Agent Prompt Guide

### Quick Color Reference
text: #ffffff
background: #27272a
border: #e5e7eb
accent: #52e1fe
primary action: #ffffff (filled action)

### 3-5 Example Component Prompts
1. Create a hero section: Dark base canvas (Charcoal #27272a), with a 'The next generation of writing emails' headline (Inter, 68px, weight 500, #ffffff, letter-spacing -0.05em). Include an 'Explore components' Action Button - Filled (background #ffffff, text #000000, 12px radius, 0px 16px padding). Below the headline, add a descriptive paragraph (Inter, 16px, weight 400, #abafb4).
2. Create a basic card: Carbon (#000000) background, 8px radius, with 16px padding inside. Title text (Inter, 24px, weight 500, #ffffff) and body text (Inter, 14px, weight 400, #abafb4).
3. Create a code block: Carbon (#000000) background. Use CommitMono font, 14px, weight 400, and use Code Orange (#ffb86a) for syntax highlighting elements as needed.
4. Create a Ghost Button - Rounded Cyan Text: transparent background, Cyber Cyan (#52e1fe) text, 12px radius, and 10px padding.
5. Create a header navigation item: Text 'Components' (Inter, 16px, weight 400, #abafb4), with an active state border on the bottom of 2px solid Cyber Cyan (#52e1fe) and text color to Porcelain (#ffffff).

## Similar Brands

- **Vercel** — Shares a developer-centric aesthetic with deep dark mode, prominent sans-serif typography, and subtle glowing accents.
- **Supabase** — Similar approach to dark UI with clear information hierarchy, occasional use of monospace fonts for code, and structured content.
- **Linear** — Employs an ultra-minimal dark theme with precise typography, subtle border treatments, and a focus on content over heavy decoration.
- **Stripe (developers section)** — Uses a clean, dark interface for developer tools, featuring code snippets, clear component separation, and functional color accents.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-carbon: #000000;
  --color-inkwell: #0f0f10;
  --color-charcoal: #27272a;
  --color-porcelain: #ffffff;
  --color-starlight: #e5e7eb;
  --color-cloudburst: #abafb4;
  --color-6e727a: #6e727a;
  --color-skyline-gray: #99a1af;
  --color-lunar-dust: #cad5e2;
  --color-code-orange: #ffb86a;
  --color-cyber-cyan: #52e1fe;
  --color-code-blue-light: #364153;
  --color-electric-blue-glow: #2563eb;
  --gradient-electric-blue-glow: radial-gradient(rgba(37, 99, 235, 0.1) 0%, rgba(0, 0, 0, 0) 80%);

  /* Typography — Font Families */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-commitmono: 'CommitMono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-apple-system: '-apple-system', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --text-body: 14px;
  --leading-body: 1.4;
  --text-body-lg: 16px;
  --leading-body-lg: 1.4;
  --text-subheading: 18px;
  --leading-subheading: 1.56;
  --text-heading: 20px;
  --leading-heading: 1.43;
  --tracking-heading: -0.008px;
  --text-heading-lg: 24px;
  --leading-heading-lg: 1.33;
  --tracking-heading-lg: -0.01px;
  --text-display: 35px;
  --leading-display: 1.2;
  --tracking-display: -0.025px;
  --text-display-xl: 68px;
  --leading-display-xl: 0.94;
  --tracking-display-xl: -0.05px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-w460: 460;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-104: 104px;
  --spacing-160: 160px;
  --spacing-216: 216px;

  /* Layout */
  --section-gap: 24px;
  --card-padding: 16px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 18px;
  --radius-3xl: 24px;

  /* Named Radii */
  --radius-lg: 18px;
  --radius-md: 12px;
  --radius-sm: 8px;
  --radius-xl: 24px;
  --radius-xs: 2px;

  /* Shadows */
  --shadow-subtle: rgba(255, 255, 255, 0.1) 0px 0px 0px 1px inset, rgba(255, 255, 255, 0.15) 0px 1px 0px 0px inset;
  --shadow-subtle-2: rgba(0, 0, 0, 0.05) 0px 1px 2px 0px;
  --shadow-md: rgba(37, 174, 186, 0.1) 0px 0px 9px 4px;

  /* Surfaces */
  --surface-charcoal: #27272a;
  --surface-inkwell: #0f0f10;
  --surface-carbon: #000000;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-carbon: #000000;
  --color-inkwell: #0f0f10;
  --color-charcoal: #27272a;
  --color-porcelain: #ffffff;
  --color-starlight: #e5e7eb;
  --color-cloudburst: #abafb4;
  --color-6e727a: #6e727a;
  --color-skyline-gray: #99a1af;
  --color-lunar-dust: #cad5e2;
  --color-code-orange: #ffb86a;
  --color-cyber-cyan: #52e1fe;
  --color-code-blue-light: #364153;
  --color-electric-blue-glow: #2563eb;

  /* Typography */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-commitmono: 'CommitMono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-apple-system: '-apple-system', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --text-body: 14px;
  --leading-body: 1.4;
  --text-body-lg: 16px;
  --leading-body-lg: 1.4;
  --text-subheading: 18px;
  --leading-subheading: 1.56;
  --text-heading: 20px;
  --leading-heading: 1.43;
  --tracking-heading: -0.008px;
  --text-heading-lg: 24px;
  --leading-heading-lg: 1.33;
  --tracking-heading-lg: -0.01px;
  --text-display: 35px;
  --leading-display: 1.2;
  --tracking-display: -0.025px;
  --text-display-xl: 68px;
  --leading-display-xl: 0.94;
  --tracking-display-xl: -0.05px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-104: 104px;
  --spacing-160: 160px;
  --spacing-216: 216px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 18px;
  --radius-3xl: 24px;

  /* Shadows */
  --shadow-subtle: rgba(255, 255, 255, 0.1) 0px 0px 0px 1px inset, rgba(255, 255, 255, 0.15) 0px 1px 0px 0px inset;
  --shadow-subtle-2: rgba(0, 0, 0, 0.05) 0px 1px 2px 0px;
  --shadow-md: rgba(37, 174, 186, 0.1) 0px 0px 9px 4px;
}
```

# Superr — Style Reference
> Child's Animated Sketchbook. This system feels like looking into a favorite, well-loved school notebook where every element has personality.

**Theme:** light

Superr opts for a youthful, playful aesthetic, resembling a child's notebook brought to life. A warm, off-white canvas sets a friendly, approachable tone, punctuated by vibrant, primary-school-inspired colors for text highlights and playful borders. Typography leans into a handwritten, slightly uneven feel for headings, offset by a clean sans-serif for body copy. Components are light, favoring subtle shadows and rounded corners to maintain a soft, tactile presence, echoing the physical world of a notebook.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas Parchment | `#fdfbf9` | `--color-canvas-parchment` | Page background, primary surface for cards and buttons, providing a warm, inviting canvas |
| Deep Graphite | `#171717` | `--color-deep-graphite` | Primary text, button borders, and accent strokes – forming the core dark contrast against the light canvas |
| Soft Black | `#2b1a07` | `--color-soft-black` | Secondary text, muted headings, and subtle borders, slightly softer than Deep Graphite |
| Jet Black | `#000000` | `--color-jet-black` | Boldest headings and critical text elements, used sparingly for absolute contrast |
| Warm Gray Shadow | `#bebcbb` | `--color-warm-gray-shadow` | Supporting neutral for secondary UI, dividers, and muted labels. Do not promote it to the primary CTA color |
| Cheeky Orange | `#ff6f1e` | `--color-cheeky-orange` | Decorative background accents, footer background — a bold, energetic burst |
| Playful Red | `#ce500a` | `--color-playful-red` | Highlight text, decorative borders – adding a vibrant, attention-grabbing spark |
| Sky Blue | `#3b82f6` | `--color-sky-blue` | Highlight text, decorative borders – a bright, clear accent color evoking creativity |
| Bubblegum Pink | `#ff66cf` | `--color-bubblegum-pink` | Highlight text, decorative borders – lending a whimsical, friendly touch |
| Grass Green | `#22c55e` | `--color-grass-green` | Highlight text, decorative borders – a fresh, positive accent |

## Tokens — Typography

### gelica — Primary display font, used for all headings, prominent calls to action, and any text needing a distinct, hand-drawn character. Its slightly uneven baseline and friendly weight convey a youthful, non-corporate voice. · `--font-gelica`
- **Substitute:** Comic Sans MS (as a last resort), or a custom script font like 'Caveat' or 'Gochi Hand' if 'gelica' is unavailable.
- **Weights:** 400, 500, 600
- **Sizes:** 16px, 20px, 24px, 28px, 32px, 36px, 40px, 46px, 104px
- **Line height:** 1.08, 1.20, 1.40, 1.50
- **Letter spacing:** normal
- **Role:** Primary display font, used for all headings, prominent calls to action, and any text needing a distinct, hand-drawn character. Its slightly uneven baseline and friendly weight convey a youthful, non-corporate voice.

### Geist — Functional text, used for body copy, navigation, and secondary information. This modern sans-serif provides clarity and legibility, grounding the playful display font with professional readability. · `--font-geist`
- **Substitute:** Inter, Figtree, or General Sans.
- **Weights:** 400, 500
- **Sizes:** 18px, 20px, 32px
- **Line height:** 1.50
- **Letter spacing:** normal
- **Role:** Functional text, used for body copy, navigation, and secondary information. This modern sans-serif provides clarity and legibility, grounding the playful display font with professional readability.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 16px | 1.5 | — | `--text-caption` |
| body | 18px | 1.5 | — | `--text-body` |
| subheading | 20px | 1.5 | — | `--text-subheading` |
| heading-sm | 32px | 1.2 | — | `--text-heading-sm` |
| heading | 46px | 1.2 | — | `--text-heading` |
| display | 104px | 1.08 | — | `--text-display` |

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
| 28 | 28px | `--spacing-28` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 116 | 116px | `--spacing-116` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 56px |
| cards | 12px |
| avatar | 9999px |
| fields | 8px |
| buttons | 20px |
| default | 8px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| lg | `rgba(0, 0, 0, 0.06) 0px 2px 20px 0px` | `--shadow-lg` |
| subtle | `rgba(0, 0, 0, 0.25) 0px 1px 2px 0px` | `--shadow-subtle` |

### Layout

- **Section gap:** 64px
- **Card padding:** 32px
- **Element gap:** 12px

## Components

### Ghost Button
**Role:** Interactive element, secondary action

Text-only button for secondary actions or links that require less emphasis. No background color, Deep Graphite text, and a bottom border in Deep Graphite. Padding is minimal (4px top/bottom, 4px right/left). Uses gelica font, 20px, weight 400.

### Pill Ghost Button
**Role:** Call to action, primary interaction

Primary call to action button, appearing as a pill-shaped outline. Canvas Parchment background with Deep Graphite text. Border is a 1px solid Deep Graphite. Rounded with a 20px radius. Has a subtle shadow rgba(0,0,0,0.25) 0px 1px 2px 0px. Uses 4px vertical and 28px horizontal padding, with gelica font, 20px, weight 400.

### Elevated Card
**Role:** Content container, feature display

Used for grouping related content, such as features or testimonials. Canvas Parchment background with 12px border radius. Features a soft, distant shadow: rgba(0, 0, 0, 0.06) 0px 2px 20px 0px. Internal padding is 24px top, 0px horizontal, 16px bottom.

### Navigation Link
**Role:** Primary navigation item

Links within the header or footer navigation. Uses Geist font at 18px, weight 400, in Deep Graphite. Underlined on hover or active state with a 1px Canvas Parchment border top, and a 2px Deep Graphite border bottom when hover/active. Minimal padding.

## Do's and Don'ts

### Do
- Use Canvas Parchment (#fdfbf9) as the dominant background color for all page sections and elevated surfaces.
- Apply the gelica font for all headings and prominent UI text (e.g., call to action buttons), embracing its playful, handwritten character.
- Employ rounded corners with a 12px radius for cards and containers, and a 20px radius for interactive elements like buttons.
- Introduce color selectively for emphasis, using Playful Red (#ce500a), Sky Blue (#3b82f6), Bubblegum Pink (#ff66cf), or Grass Green (#22c55e) for highlight text or decorative borders, never as primary backgrounds.
- Maintain comfortable spacing: 12px for small element gaps, 32px for card padding, and 64px for vertical section separation.
- Use a subtle soft shadow (rgba(0,0,0,0.06) 0px 2px 20px 0px) to give cards a gentle lift, avoiding heavy or stark elevation.
- For primary calls to action, use the Pill Ghost Button style with a Deep Graphite (#171717) stroke and text on the Canvas Parchment background.

### Don't
- Avoid using highly saturated brand colors as large background fills; they are intended for accents and highlights.
- Do not use sharp 0px corners on any UI elements; all corners should have some degree of rounding (minimum 2px).
- Refrain from heavy, multi-layered shadows; the design embraces a light, gentle elevation with a single, soft shadow.
- Do not use generic system fonts; always prioritize gelica for display and Geist for functional text.
- Avoid dense, information-heavy layouts; maintain ample white space and comfortable element spacing.
- Do not introduce strong, solid border colors unless they are part of a deliberate accent or interactive state (e.g. outline buttons).

## Imagery

Imagery primarily features stylized 3D product renders of SuperrBook notebooks with playful, illustrated stickers. The product shots are often cropped tightly or presented from an angle, showcasing the physical object with a sense of tactility. Illustrations are flat, geometric, and brand-colored, often appearing as small, whimsical floating elements or in sticker form on the product. Icons are mostly outlined, with a moderate stroke weight, carrying the brand's cheerful persona. The overall role of imagery is to be decorative and atmospheric, highlighting the product in an imaginative, content-rich way without overwhelming the UI, maintaining a text-dominant density.

## Layout

The page uses a full-bleed layout, allowing elements to span the entire viewport width, but content is often contained within an implicit central column, especially for text blocks. The hero section features a large, product illustration on the right, balanced by a significant headline and subtext on the left, creating an asymmetric but balanced composition. Sections follow a consistent vertical rhythm, often alternating between a main content block and a full-bleed decorative element (like the notebooks). Content is typically arranged in left-aligned stacks or two-column text-left/image-right patterns. There is no explicit grid for cards on the initial screen, but subsequent sections imply a flexible grid for features. Navigation is a minimal top-bar, sticky header design with a single interactive icon and a ghost button.

## Agent Prompt Guide

Quick Color Reference:
text: #171717
background: #fdfbf9
border: #171717
accent: #ff6f1e
primary action: no distinct CTA color

Example Component Prompts:
Create a hero section: Canvas Parchment background. Headline 'meet superrbook' with gelica 104px weight 600, Jet Black (#000000). Subtext 'It's an AI notebook that actually makes learning fun' with gelica 46px weight 400, Jet Black (#000000), with the word 'actually!' in Playful Red (#ce500a). Include a Pill Ghost Button 'I call dibs!' with a Deep Graphite (#171717) stroke, 20px radius, gelica 20px font.

Create a feature card: Elevated Card with Canvas Parchment background, 12px radius, soft shadow rgba(0,0,0,0.06) 0px 2px 20px 0px. Inside, use Geist 20px weight 500 for the title 'A library that grows with you' in Deep Graphite (#171717).

Create a secondary link: Ghost Button with text 'Read Letter' in Deep Graphite (#171717), gelica 20px font, with a bottom border of Deep Graphite.

## Similar Brands

- **Notion** — Uses a similar warm off-white canvas, relies on a clean sans-serif for body text, and employs subtle shadows for component elevation.
- **Basecamp** — Employs a friendly, comfortable aesthetic with ample whitespace, a warm neutral background, and simple, approachable typography.
- **Paper by FiftyThree (old branding)** — Known for a skeuomorphic 'notebook' feel, natural textures, and a light, spacious layout that makes digital feel analogue and creative.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-parchment: #fdfbf9;
  --color-deep-graphite: #171717;
  --color-soft-black: #2b1a07;
  --color-jet-black: #000000;
  --color-warm-gray-shadow: #bebcbb;
  --color-cheeky-orange: #ff6f1e;
  --color-playful-red: #ce500a;
  --color-sky-blue: #3b82f6;
  --color-bubblegum-pink: #ff66cf;
  --color-grass-green: #22c55e;

  /* Typography — Font Families */
  --font-gelica: 'gelica', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geist: 'Geist', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 16px;
  --leading-caption: 1.5;
  --text-body: 18px;
  --leading-body: 1.5;
  --text-subheading: 20px;
  --leading-subheading: 1.5;
  --text-heading-sm: 32px;
  --leading-heading-sm: 1.2;
  --text-heading: 46px;
  --leading-heading: 1.2;
  --text-display: 104px;
  --leading-display: 1.08;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-116: 116px;

  /* Layout */
  --section-gap: 64px;
  --card-padding: 32px;
  --element-gap: 12px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-full: 56px;

  /* Named Radii */
  --radius-tags: 56px;
  --radius-cards: 12px;
  --radius-avatar: 9999px;
  --radius-fields: 8px;
  --radius-buttons: 20px;
  --radius-default: 8px;

  /* Shadows */
  --shadow-lg: rgba(0, 0, 0, 0.06) 0px 2px 20px 0px;
  --shadow-subtle: rgba(0, 0, 0, 0.25) 0px 1px 2px 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-parchment: #fdfbf9;
  --color-deep-graphite: #171717;
  --color-soft-black: #2b1a07;
  --color-jet-black: #000000;
  --color-warm-gray-shadow: #bebcbb;
  --color-cheeky-orange: #ff6f1e;
  --color-playful-red: #ce500a;
  --color-sky-blue: #3b82f6;
  --color-bubblegum-pink: #ff66cf;
  --color-grass-green: #22c55e;

  /* Typography */
  --font-gelica: 'gelica', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geist: 'Geist', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 16px;
  --leading-caption: 1.5;
  --text-body: 18px;
  --leading-body: 1.5;
  --text-subheading: 20px;
  --leading-subheading: 1.5;
  --text-heading-sm: 32px;
  --leading-heading-sm: 1.2;
  --text-heading: 46px;
  --leading-heading: 1.2;
  --text-display: 104px;
  --leading-display: 1.08;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-116: 116px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-full: 56px;

  /* Shadows */
  --shadow-lg: rgba(0, 0, 0, 0.06) 0px 2px 20px 0px;
  --shadow-subtle: rgba(0, 0, 0, 0.25) 0px 1px 2px 0px;
}
```

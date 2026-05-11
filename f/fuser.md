# Fuser — Style Reference
> Frosted glass network — a cool, translucent interface connecting modular, vivid ideas.

**Theme:** light

Fuser establishes a crisp, expansive canvas for AI workflow orchestration. Its visual system prioritizes clarity and a sense of depth, achieved through a subtle, cool-toned gray scale as the primary surface treatment, punctuated by vivid violets and vibrant greens for interactive elements. Imagery is encased in soft-cornered cards that float above a sparse, grid-like background, suggesting modularity and precision. Typography combines a sharp, modern sans-serif with a distinctive display serif for headlines, creating an aesthetic that is both functional and subtly artistic.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Stormy Night | `#0a0a0a` | `--color-stormy-night` | Primary text, deep section backgrounds — provides high contrast for headlines and critical information |
| Graphite | `#171717` | `--color-graphite` | Secondary text, dark surface backgrounds, strong borders |
| Deep Space Violet | `#432dd7` | `--color-deep-space-violet` | Violet decorative accent for icons, marks, and small graphic details. Do not promote it to the primary CTA color |
| Violet Impulse | `#312c85` | `--color-violet-impulse` | Link text, secondary interactive elements — a darker, more reserved violet for actions and navigation |
| Sage Bloom | `#00c950` | `--color-sage-bloom` | Green decorative accent for icons, marks, and small graphic details. Use as a supporting accent, not as a status color |
| Zinc | `#262626` | `--color-zinc` | Text on lighter surfaces, input borders — a dark gray that serves as primary text on lighter backgrounds |
| Ash Charcoal | `#404040` | `--color-ash-charcoal` | Subtle text, muted borders, dividing lines |
| Slate | `#525252` | `--color-slate` | Muted text, inactive icon fills, subtle borders |
| Medium Gray | `#737373` | `--color-medium-gray` | Placeholder text, secondary icon fills, muted UI details |
| Stone | `#828282` | `--color-stone` | Tertiary text, subtle dividers |
| Silver Mist | `#b7b7b7` | `--color-silver-mist` | Hairline borders, subtle background patterns, disabled states |
| Light Heather | `#d4d4d4` | `--color-light-heather` | Light border, decorative elements |
| Fog | `#e5e5e5` | `--color-fog` | Card backgrounds, elevated surfaces — creates a distinct layer above the canvas |
| Cloud | `#efefef` | `--color-cloud` | Subtle button and card borders, light secondary backgrounds |
| Canvas | `#f5f5f5` | `--color-canvas` | Page background — the foundational, expansive white space |
| Paper White | `#fafafa` | `--color-paper-white` | Component backgrounds, overlay surfaces — the brightest white for content blocks |
| Lavender Haze | `#c6d2ff` | `--color-lavender-haze` | Subtle background wash for emphasized content blocks, indicating a gentle shift or focus |
| Dusk Orchid | `#a6a5fe` | `--color-dusk-orchid` | Outlined button borders, subtle interaction cues, providing a soft violet glow without high saturation |
| Lavender Whisper | `#d7defd` | `--color-lavender-whisper` | Subtle hover states or background hints, a very light violet that suggests interactivity |
| Gradient Aura | `linear-gradient(to right, oklch(0.723 0.219 149.579 / 0.25) 10%, oklch(0.623 0.214 259.815 / 0.5))` | `--color-gradient-aura` | Background for hero sections and distinctive UI elements, providing a soft, ethereal gradient from warm pink to cool violet; Decorative background gradient, adding subtle depth and color variation |
| Gradient Ascent | `linear-gradient(to right bottom, oklch(0.785 0.115 274.713) 0%, oklch(0.93 0.034 272.788) 100%)` | `--color-gradient-ascent` | Decorative background gradient, a gentle shift from a desaturated purple to a nearly white lavender |

## Tokens — Typography

### Inter Variable — Body copy, UI labels, navigation, and functional text – Inter provides legibility and a modern, slightly technical feel across its variable weights. · `--font-inter-variable`
- **Substitute:** Inter
- **Weights:** 300, 400, 500, 600
- **Sizes:** 10px, 12px, 13px, 14px, 16px, 18px, 24px, 30px, 36px
- **Line height:** 0.80, 1.00, 1.10, 1.20, 1.25, 1.33, 1.40, 1.43, 1.50, 1.56, 1.71
- **Letter spacing:** varies per size, e.g., -0.0250em for larger text, normal for body
- **Role:** Body copy, UI labels, navigation, and functional text – Inter provides legibility and a modern, slightly technical feel across its variable weights.

### Marund — Headlines and prominent display text – a custom serif that grounds the interface with distinctiveness and a subtle, sophisticated tone. Its unique stylistic sets ('ss00', 'ss03') contribute significantly to branding. · `--font-marund`
- **Substitute:** Playfair Display
- **Weights:** 400, 450, 500, 600
- **Sizes:** 14px, 16px, 17px, 18px, 20px, 22px, 24px, 30px, 48px, 96px
- **Line height:** 1.00, 1.10, 1.40, 1.43, 1.50
- **Letter spacing:** varies per size, e.g., -0.0500em for display, -0.0250em for subheadings
- **OpenType features:** `'ss00' on, 'ss03' on`
- **Role:** Headlines and prominent display text – a custom serif that grounds the interface with distinctiveness and a subtle, sophisticated tone. Its unique stylistic sets ('ss00', 'ss03') contribute significantly to branding.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 12 | — | `--text-caption` |
| body | 14px | 22 | -0.14px | `--text-body` |
| body-lg | 16px | 24 | — | `--text-body-lg` |
| subheading | 18px | 27 | -0.18px | `--text-subheading` |
| heading-sm | 24px | 29 | — | `--text-heading-sm` |
| heading | 36px | 43 | -0.36px | `--text-heading` |
| display | 48px | 53 | -0.48px | `--text-display` |
| display-lg | 96px | 96 | -0.96px | `--text-display-lg` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** compact

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
| 64 | 64px | `--spacing-64` |
| 72 | 72px | `--spacing-72` |
| 80 | 80px | `--spacing-80` |
| 96 | 96px | `--spacing-96` |
| 112 | 112px | `--spacing-112` |
| 136 | 136px | `--spacing-136` |
| 160 | 160px | `--spacing-160` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 24px |
| cards | 16px |
| images | 12px |
| default | 6px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| md | `rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1)...` | `--shadow-md` |
| subtle | `oklch(0 0 0 / 0.3) 0px 0px 2px 0px inset, oklch(0 0 0 / 0...` | `--shadow-subtle` |
| subtle-2 | `oklch(0.439 0 0) 0px 0px 0px 0px` | `--shadow-subtle-2` |
| subtle-3 | `oklch(0.439 0 0) 0px 0px 0px 0px, rgba(0, 0, 0, 0.1) 0px ...` | `--shadow-subtle-3` |
| subtle-4 | `oklch(0.556 0 0) 0px 0px 0px 0px` | `--shadow-subtle-4` |
| subtle-5 | `oklch(0.145 0 0) 0px 0px 0px 0px, oklab(0.999994 0.000045...` | `--shadow-subtle-5` |
| subtle-6 | `oklch(0.145 0 0) 0px 0px 0px 0px` | `--shadow-subtle-6` |

### Layout

- **Section gap:** 32px
- **Card padding:** 12px
- **Element gap:** 16px

## Components

### Ghost Navigation Button
**Role:** Primary navigation and subtle actions

Text-only button with 'Violet Impulse' (#312c85) as default text, transparent background. No explicit padding, text size set by context. Used for navigation and inline actions. Uses Inter Variable.

### Small Contained Button
**Role:** Secondary calls to action, form actions

Background 'Paper White' (#fafafa), text 'Zinc' (#262626), border 1px 'Cloud' (#efefef). Border radius 6px. Padding 6px horizontal, 10px vertical. Uses Inter Variable.

### Outline Accent Button
**Role:** Emphasis action, 'Get Started' button

Background transparent, text 'Violet Impulse' (#312c85), border 1px 'Dusk Orchid' (#a6a5fe). Border radius 6px. Padding 8px vertical, 0px horizontal. Uses Inter Variable.

### Prominent Text Input
**Role:** Main form fields

Transparent background, text 'Zinc' (#262626), default border color 'Zinc' (#262626). Padding 0px vertical, 4px horizontal. Uses Inter Variable.

### Content Card - Minimal
**Role:** Basic display of content, images, or media

Transparent background, no shadow, 0px border radius. Used for floating images in the canvas view. Padding 0.

### Content Card - Elevated
**Role:** Standard content display, modal backgrounds

Background 'Paper White' (#fafafa). Border radius 16px. No border or shadow by default. Padding 12px.

### Content Card - Highlighted
**Role:** Featured content blocks, interactive elements

Background 'Canvas' (#f5f5f5). Border radius 24px. Subtle shadow: `rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1) 0px 4px 6px -4px`. No padding by default.

### Decorative Tag - Round
**Role:** Informational labels, status indicators

Background 'Sage Bloom' (#00c950) with high border radius (effectively pill-shaped). No padding by default. Text color typically 'Paper White' or 'Stormy Night'.

## Do's and Don'ts

### Do
- Always use 'Canvas' (#f5f5f5) as the primary page background to maintain an expansive, light feel.
- Apply 'Deep Space Violet' (#432dd7) only to interactive icons and borders to signal interactivity and brand presence clearly.
- Ensure all cards, images, and interactive elements use a border-radius of at least 6px, and up to 24px for larger content cards, to maintain the soft, approachable aesthetic.
- Utilize Marund for all display-level typography (size 48px and above) with its specific letter-spacing and stylistic sets to convey brand distinctiveness.
- Create visual depth using 'Fog' (#e5e5e5) for card backgrounds, elevating them above the main page 'Canvas' (#f5f5f5).
- Employ the `rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1) 0px 4px 6px -4px` shadow for cards requiring subtle elevation and interaction emphasis.
- Implement consistent `16px` element gaps for vertical stacking of related components and `12px` padding for internal card content.

### Don't
- Avoid using highly saturated colors for large background areas; they should be reserved for small, functional accents like 'Deep Space Violet' (#432dd7) or 'Sage Bloom' (#00c950).
- Do not use Marund for body text; reserve it entirely for headlines and display text to preserve its unique impact and legibility at smaller sizes.
- Never introduce hard, 0px border-radii for interactive elements or containers; maintain the consistent soft cornering established by 6px minimal radius.
- Refrain from using strong, dark shadows on navigation or primary action elements; elevation should be subtle and primarily for content grouping.
- Do not vary line-height significantly from the established semantic type scale; maintaining the rhythm of `1.2` for headings and `1.5` for body text ensures a cohesive reading experience.
- Avoid arbitrary custom letter-spacing; adhere to the defined `letterSpacing` values for Inter and Marund to control visual density.
- Do not use dark backgrounds for primary sections unless specifically integrating a full-bleed visual or hero where a dark gradient is explicitly defined.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas | `#f5f5f5` | Primary page background, expansive and neutral. |
| 1 | Fog | `#e5e5e5` | Elevated surfaces like cards and content blocks, providing a subtle visual separation from the main canvas. |
| 2 | Paper White | `#fafafa` | Component backgrounds, overlays, and the brightest content containers. |

## Elevation

- **Content Card - Highlighted:** `rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1) 0px 4px 6px -4px`
- **Inner Modal / Input Focus:** `oklch(0 0 0 / 0.3) 0px 0px 2px 0px inset, oklch(0 0 0 / 0.1) 0px 1px 0px 0px inset`

## Imagery

The site employs a mix of crisp product photography and artistic, abstract visuals. Product photos are often contained within soft-cornered cards, showcasing objects (like garments or machinery) in isolation against neutral backgrounds, emphasizing detail and form. Abstract imagery, sometimes with gradient overlays, is used for atmospheric depth, particularly in the hero section. There's also evident use of AI-generated content (e.g., stylized topographical maps, dynamic compositions) within these card frames, serving as both decorative elements and visual demonstrations of the product's capabilities. Icons are primarily outlined or subtle fills, maintaining a lightweight feel, often in black or the 'Deep Space Violet' accent. The density is moderate; imagery works to break up text and provide visual anchors, often floating in the canvas rather than being integrated full-bleed.

## Layout

The page primarily uses a max-width contained layout for core content. The hero section is full-bleed, featuring a central headline over an ethereal gradient background, with modular image cards floating within a subtle grid. Sections beneath maintain a consistent vertical rhythm with 32px spacing. Content is largely arranged in centered stacks or alternating text-left / image-right patterns. A subtle, light grid pattern (likely repeating lines or dots) underlays the canvas, hinting at the product's node-based or generative nature. Navigation is a sticky top bar with ghost buttons and a distinct outlined accent button.

## Agent Prompt Guide

Quick Color Reference:
text: #0a0a0a
background: #f5f5f5
border: #e5e5e5
accent: #432dd7
primary action: #d7defd (filled action)

Example Component Prompts:
1. Create a `Hero Section`: full-bleed background using `Gradient Aura` linear-gradient, centered 'Marund' display-lg headline in `Stormy Night` (#0a0a0a), followed by 'Inter Variable' body-lg subtext in `Slate` (#525252). Include several `Content Card - Highlighted` elements floating in the foreground.
2. Create a Primary Action Button: #d7defd background, #000000 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
3. Build a `Feature Card` (Content Card - Elevated): `Fog` (#e5e5e5) background, `16px` radius. Headline 'Marund' heading-sm in `Stormy Night` (#0a0a0a), body text 'Inter Variable' body in `Zinc` (#262626). Include a small square image with `12px` radius and a `Decorative Tag - Round` in 'Sage Bloom' (#00c950) for a unique feature.
4. Produce an `Image Grid`: a 3-column grid of `Content Card - Highlighted` elements, each containing an image with `12px` radius and minimal associated text in 'Inter Variable' body-sm. The grid items should have `16px` element gaps vertically and horizontally.

## Similar Brands

- **Framer** — White canvas, interactive dark gray elements, and subtle elevation for components with a grid-like underpinning.
- **Linear** — Emphasis on crisp typography, generous white space, and subtle, functional pops of color on an otherwise neutral UI.
- **Retool** — Modular component-based UI, with a clear focus on functionality over heavy decoration, using a light theme with controlled accent colors.
- **Miro** — Expansive canvas, floating elements, and a system of cards and controls that convey an infinite workspace.
- **Raycast** — Clean, understated UI with a strong focus on minimalist design, powerful typography, and subtle layering of elements.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-stormy-night: #0a0a0a;
  --color-graphite: #171717;
  --color-deep-space-violet: #432dd7;
  --color-violet-impulse: #312c85;
  --color-sage-bloom: #00c950;
  --color-zinc: #262626;
  --color-ash-charcoal: #404040;
  --color-slate: #525252;
  --color-medium-gray: #737373;
  --color-stone: #828282;
  --color-silver-mist: #b7b7b7;
  --color-light-heather: #d4d4d4;
  --color-fog: #e5e5e5;
  --color-cloud: #efefef;
  --color-canvas: #f5f5f5;
  --color-paper-white: #fafafa;
  --color-lavender-haze: #c6d2ff;
  --color-dusk-orchid: #a6a5fe;
  --color-lavender-whisper: #d7defd;
  --color-gradient-aura: #c679c4;
  --gradient-gradient-aura: linear-gradient(to right, oklch(0.723 0.219 149.579 / 0.25) 10%, oklch(0.623 0.214 259.815 / 0.5));
  --color-gradient-ascent: #cf9cdf;
  --gradient-gradient-ascent: linear-gradient(to right bottom, oklch(0.785 0.115 274.713) 0%, oklch(0.93 0.034 272.788) 100%);

  /* Typography — Font Families */
  --font-inter-variable: 'Inter Variable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-marund: 'Marund', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 12;
  --text-body: 14px;
  --leading-body: 22;
  --tracking-body: -0.14px;
  --text-body-lg: 16px;
  --leading-body-lg: 24;
  --text-subheading: 18px;
  --leading-subheading: 27;
  --tracking-subheading: -0.18px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 29;
  --text-heading: 36px;
  --leading-heading: 43;
  --tracking-heading: -0.36px;
  --text-display: 48px;
  --leading-display: 53;
  --tracking-display: -0.48px;
  --text-display-lg: 96px;
  --leading-display-lg: 96;
  --tracking-display-lg: -0.96px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-w450: 450;
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
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-112: 112px;
  --spacing-136: 136px;
  --spacing-160: 160px;

  /* Layout */
  --section-gap: 32px;
  --card-padding: 12px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;

  /* Named Radii */
  --radius-tags: 24px;
  --radius-cards: 16px;
  --radius-images: 12px;
  --radius-default: 6px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1) 0px 4px 6px -4px;
  --shadow-subtle: oklch(0 0 0 / 0.3) 0px 0px 2px 0px inset, oklch(0 0 0 / 0.1) 0px 1px 0px 0px inset;
  --shadow-subtle-2: oklch(0.439 0 0) 0px 0px 0px 0px;
  --shadow-subtle-3: oklch(0.439 0 0) 0px 0px 0px 0px, rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1) 0px 4px 6px -4px;
  --shadow-subtle-4: oklch(0.556 0 0) 0px 0px 0px 0px;
  --shadow-subtle-5: oklch(0.145 0 0) 0px 0px 0px 0px, oklab(0.999994 0.0000455678 0.0000200868 / 0.4) 0px 1px 3px 0px, oklab(0.999994 0.0000455678 0.0000200868 / 0.5) 0px 0px 4px 0px, oklab(0 0 0 / 0.3) 0px 0px 2px 0px inset, oklab(0 0 0 / 0.1) 0px 1px 0px 0px inset;
  --shadow-subtle-6: oklch(0.145 0 0) 0px 0px 0px 0px;

  /* Surfaces */
  --surface-canvas: #f5f5f5;
  --surface-fog: #e5e5e5;
  --surface-paper-white: #fafafa;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-stormy-night: #0a0a0a;
  --color-graphite: #171717;
  --color-deep-space-violet: #432dd7;
  --color-violet-impulse: #312c85;
  --color-sage-bloom: #00c950;
  --color-zinc: #262626;
  --color-ash-charcoal: #404040;
  --color-slate: #525252;
  --color-medium-gray: #737373;
  --color-stone: #828282;
  --color-silver-mist: #b7b7b7;
  --color-light-heather: #d4d4d4;
  --color-fog: #e5e5e5;
  --color-cloud: #efefef;
  --color-canvas: #f5f5f5;
  --color-paper-white: #fafafa;
  --color-lavender-haze: #c6d2ff;
  --color-dusk-orchid: #a6a5fe;
  --color-lavender-whisper: #d7defd;
  --color-gradient-aura: #c679c4;
  --color-gradient-ascent: #cf9cdf;

  /* Typography */
  --font-inter-variable: 'Inter Variable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-marund: 'Marund', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 12;
  --text-body: 14px;
  --leading-body: 22;
  --tracking-body: -0.14px;
  --text-body-lg: 16px;
  --leading-body-lg: 24;
  --text-subheading: 18px;
  --leading-subheading: 27;
  --tracking-subheading: -0.18px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 29;
  --text-heading: 36px;
  --leading-heading: 43;
  --tracking-heading: -0.36px;
  --text-display: 48px;
  --leading-display: 53;
  --tracking-display: -0.48px;
  --text-display-lg: 96px;
  --leading-display-lg: 96;
  --tracking-display-lg: -0.96px;

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
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-112: 112px;
  --spacing-136: 136px;
  --spacing-160: 160px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1) 0px 4px 6px -4px;
  --shadow-subtle: oklch(0 0 0 / 0.3) 0px 0px 2px 0px inset, oklch(0 0 0 / 0.1) 0px 1px 0px 0px inset;
  --shadow-subtle-2: oklch(0.439 0 0) 0px 0px 0px 0px;
  --shadow-subtle-3: oklch(0.439 0 0) 0px 0px 0px 0px, rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1) 0px 4px 6px -4px;
  --shadow-subtle-4: oklch(0.556 0 0) 0px 0px 0px 0px;
  --shadow-subtle-5: oklch(0.145 0 0) 0px 0px 0px 0px, oklab(0.999994 0.0000455678 0.0000200868 / 0.4) 0px 1px 3px 0px, oklab(0.999994 0.0000455678 0.0000200868 / 0.5) 0px 0px 4px 0px, oklab(0 0 0 / 0.3) 0px 0px 2px 0px inset, oklab(0 0 0 / 0.1) 0px 1px 0px 0px inset;
  --shadow-subtle-6: oklch(0.145 0 0) 0px 0px 0px 0px;
}
```

# amp — Style Reference
> Warmly lit athletic minimalism

**Theme:** light

Amp's design system evokes a sense of accessible, high-tech fitness. It leverages a predominantly neutral palette with a vibrant orange serving as a focused accent for action and emphasis. Typography is clean and modern, enhancing readability within a comfortable, spacious layout. Surfaces are generally flat and minimal, with subtle rounded corners and a single prominent shadow for primary actions, creating a focused, uncluttered user experience.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Orange Ember | `#ff6105` | `--color-orange-ember` | Primary action backgrounds, subtle accent borders, key interactive elements — a warm, vivid hue that drives user engagement |
| Soft Peach | `#ffdfcd` | `--color-soft-peach` | Decorative card backgrounds, often hinting at brand warmth without heavy saturation |
| Warm Glow | `#ffa069` | `--color-warm-glow` | Orange supporting accent for decorative details and low-frequency emphasis. Do not promote it to the primary CTA color |
| Ash Gray | `#e5e5e5` | `--color-ash-gray` | Dominant background for page canvas and subtle dividers; a light and airy base for content |
| Deep Graphite | `#0a0a0a` | `--color-deep-graphite` | Primary text color for high readability, contrasts sharply with light backgrounds |
| White Canvas | `#ffffff` | `--color-white-canvas` | Card backgrounds, elevated surfaces, and sometimes reversed text on dark elements |
| Light Mist | `#f3f4f3` | `--color-light-mist` | Subtle background for secondary buttons and alternative interface sections |
| Dark Slate Border | `#3c3e3d` | `--color-dark-slate-border` | Underlines and borders for text, adding structure without heavy lines |
| Dark Charcoal | `#292b2a` | `--color-dark-charcoal` | Secondary text for body copy and headings, offering a slightly softer contrast than primary text |
| Ghost Gray | `#e5e7eb` | `--color-ghost-gray` | Background for tertiary buttons and component states, blending into the background |
| True Black | `#202120` | `--color-true-black` | Footer background, providing a distinct, grounding element |
| Muted Stone | `#7a7b7b` | `--color-muted-stone` | Subtler text, placeholder text, and input borders, for less prominent information |
| Pale Silver | `#a2a3a2` | `--color-pale-silver` | Lightest neutral text for links and less important headings, offering minimal contrast |
| Light Border | `#dfe0df` | `--color-light-border` | Fine borders and dividers for enhanced structure without visual weight |

## Tokens — Typography

### PublicaSans — Primary typeface for all text content. Its variable letter-spacing makes large headlines feel expansive and elegant, while moderate tracking at smaller sizes retains readability. The light weight (300) for many headings suggests an understated, confident tone. · `--font-publicasans`
- **Substitute:** Montserrat
- **Weights:** 300, 400, 500
- **Sizes:** 12px, 14px, 16px, 18px, 24px, 32px, 48px, 72px, 78px
- **Line height:** 0.71-1.56
- **Letter spacing:** -0.0360em at 78px, -0.0300em at 72px, -0.0200em at 48px, -0.0100em at 32px
- **Role:** Primary typeface for all text content. Its variable letter-spacing makes large headlines feel expansive and elegant, while moderate tracking at smaller sizes retains readability. The light weight (300) for many headings suggests an understated, confident tone.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.5 | — | `--text-caption` |
| body-sm | 14px | 1.56 | — | `--text-body-sm` |
| body | 16px | 1.5 | — | `--text-body` |
| subheading | 18px | 1.33 | — | `--text-subheading` |
| heading-sm | 24px | 1.22 | -0.24px | `--text-heading-sm` |
| heading | 32px | 1.2 | -0.32px | `--text-heading` |
| heading-lg | 48px | 1.1 | -0.96px | `--text-heading-lg` |
| display | 72px | 0.94 | -2.16px | `--text-display` |
| display-xl | 78px | 0.71 | -2.808px | `--text-display-xl` |

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
| 56 | 56px | `--spacing-56` |
| 60 | 60px | `--spacing-60` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 112 | 112px | `--spacing-112` |

### Border Radius

| Element | Value |
|---------|-------|
| body | 16px |
| cards | 5px |
| other | 8px |
| images | 8px |
| inputs | 50px |
| buttons | 24px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| md | `rgba(255, 97, 5, 0.6) 1px 6px 14px 0px, rgba(0, 0, 0, 0.0...` | `--shadow-md` |

### Layout

- **Section gap:** 80px
- **Card padding:** 16px
- **Element gap:** 5px

## Components

### Primary Action Button
**Role:** Call to action

Filled with Orange Ember (#ff6105), text in Deep Graphite (#0a0a0a) or White Canvas (#ffffff), with 24px border radius. Features a Warm Glow shadow rgba(255, 97, 5, 0.6) 1px 6px 14px 0px, rgba(0, 0, 0, 0.06) 0px 1px 4px 0px. Padding 8px vertical, 16px horizontal.

### Solid Navigation Button
**Role:** Secondary action

Background Light Mist (#f3f4f3), text Dark Charcoal (#292b2a) with 24px border radius. Padding 8px vertical, 16px horizontal.

### Ghost Text Button
**Role:** Tertiary action

Transparent background, text Dark Charcoal (#292b2a), 8px border-radius. Padding is 30px vertical (likely full-height or decorative).

### Outlined Input Field
**Role:** Data entry

Transparent background, text Muted Stone (#7a7b7b), with a 50px border radius and 1px solid Muted Stone (#7a7b7b) border. Padding 13px top, 26px horizontal, 16px bottom.

### Info Card
**Role:** Content display

Transparent background, 5px border radius, with 29px vertical padding and 16px horizontal padding. Border is typically Ash Gray (#e5e5e5) or Dark Slate Border (#3c3e3d).

### Promotional Card
**Role:** Highlight content

Background Soft Peach (#ffdfcd), with 5px top border radius (0px bottom radius), no padding or shadow.

## Do's and Don'ts

### Do
- Prioritize PublicaSans weight 400 with Deep Graphite (#0a0a0a) for body text and Dark Charcoal (#292b2a) for headings, ensuring high readability and a consistent tone.
- Apply Orange Ember (#ff6105) exclusively for primary calls to action backgrounds, ensuring a distinct, energetic focal point.
- Use Ash Gray (#e5e5e5) as the default page background and thin horizontal dividers to maintain a light, open composition.
- Ensure buttons use a 24px border radius for a soft, approachable feel, or 50px for pill-shaped inputs, applying a uniform curvature language.
- Utilize a 5px element gap for fine-tuning spacing between interactive elements and textual components, maintaining a comfortable density.
- Introduce a subtle Warm Glow (#ffa069) shadow on primary buttons to provide a sense of elevation and interactivity, being the only component with a prominent shadow.
- Maintain comfortable spacing with a 16px card padding and 80px section gaps, allowing content to breathe and preventing visual clutter.

### Don't
- Do not use saturated colors other than Orange Ember (#ff6105) for interactive elements, as this dilutes the impact of the primary accent color.
- Avoid arbitrary border radii; adhere to 24px for most buttons and 5px or 8px for cards and images, respectively.
- Do not introduce heavy drop shadows or extreme elevation; the design relies on mostly flat surfaces and subtle borders for depth.
- Refrain from using overly bold or heavy font weights for body copy; the system favors lighter weights (300-400) even for headings.
- Do not create dense content blocks; maintain generous vertical spacing (80px section gaps) and comfortable padding (16px for cards).
- Avoid complex gradients; the system prefers solid colors with occasional subtle glows for emphasis.
- Do not use highly textured backgrounds; stick to the clean, flat neutrals (Ash Gray #e5e5e5, Light Mist #f3f4f3) to preserve visual clarity.

## Elevation

- **Primary Action Button:** `rgba(255, 97, 5, 0.6) 1px 6px 14px 0px, rgba(0, 0, 0, 0.06) 0px 1px 4px 0px`

## Imagery

This system primarily uses product imagery with a clean, focused treatment. Photography features the 'amp' device in realistic, often domestic, settings, with warm, balanced lighting. Product shots are contained within the UI, never full-bleed. Illustrations are minimal, seen mostly as simplified UI elements within device mockups. Iconography is light-weight, outlined, monochromatic, focusing on clarity and functionality. The overall density is image-heavy in hero sections and product showcases, transitioning to more text-dominant explanations.

## Layout

The page structure utilizes a full-bleed top navigation and header, with main content contained within an implicit max-width rather than explicitly defined. The hero section features large, visually striking product imagery centered or as a background, often with an overlay text. Section rhythm alternates between clean white backgrounds and slightly off-white/gray bands, creating a visual flow. Content arrangement frequently uses a split layout (text left/image right) or centered stacked blocks for features. Density is comfortable, with generous vertical spacing between sections and concise information display for product features and steps. The navigation is a classic top bar, becoming sticky on scroll.

## Agent Prompt Guide

**Quick Color Reference:**
text: #0a0a0a
background: #e5e5e5
border: #e5e5e5
accent: #ff6105
primary action: #ff6105 (filled action)

**3-5 Example Component Prompts:**
1. Create a Primary Action Button: #ff6105 background, #0a0a0a text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Create a Hero Headline: PublicaSans 78px weight 300, Dark Charcoal (#292b2a) color, letter-spacing -2.808px.
3. Create an Outlined Input Field: transparent background, Muted Stone (#7a7b7b) text, 50px radius, 1px solid Muted Stone (#7a7b7b) border, 13px top, 26px horizontal, 16px bottom padding.
4. Create an Info Card: transparent background, 5px radius, 29px vertical 16px horizontal padding, with a 1px solid Ash Gray (#e5e5e5) border.
5. Create a Body Text Block: PublicaSans 16px weight 400, Deep Graphite (#0a0a0a) color, lineHeight 1.5.

## Similar Brands

- **Peloton** — High-tech fitness brand with a focus on sleek product design and clean UI, driving engagement through strong calls to action.
- **Tonal** — Smart gym with a similar emphasis on minimalist design, integrated technology, and a premium feel communicated via balanced typography and controlled accent colors.
- **Apple Fitness+** — Clean, approachable interface for fitness content, utilizing clear information hierarchy and strong, but not overwhelming, accent colors for interactive elements.
- **Whoop** — Wearable tech with a focus on data visualization and a clean, modern aesthetic in its accompanying app and web interface.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-orange-ember: #ff6105;
  --color-soft-peach: #ffdfcd;
  --color-warm-glow: #ffa069;
  --color-ash-gray: #e5e5e5;
  --color-deep-graphite: #0a0a0a;
  --color-white-canvas: #ffffff;
  --color-light-mist: #f3f4f3;
  --color-dark-slate-border: #3c3e3d;
  --color-dark-charcoal: #292b2a;
  --color-ghost-gray: #e5e7eb;
  --color-true-black: #202120;
  --color-muted-stone: #7a7b7b;
  --color-pale-silver: #a2a3a2;
  --color-light-border: #dfe0df;

  /* Typography — Font Families */
  --font-publicasans: 'PublicaSans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --text-body-sm: 14px;
  --leading-body-sm: 1.56;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.33;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.22;
  --tracking-heading-sm: -0.24px;
  --text-heading: 32px;
  --leading-heading: 1.2;
  --tracking-heading: -0.32px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.96px;
  --text-display: 72px;
  --leading-display: 0.94;
  --tracking-display: -2.16px;
  --text-display-xl: 78px;
  --leading-display-xl: 0.71;
  --tracking-display-xl: -2.808px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;

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
  --spacing-56: 56px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-112: 112px;

  /* Layout */
  --section-gap: 80px;
  --card-padding: 16px;
  --element-gap: 5px;

  /* Border Radius */
  --radius-md: 5px;
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;
  --radius-3xl-3: 40px;
  --radius-full: 50px;
  --radius-full-2: 53px;
  --radius-full-3: 56.16px;
  --radius-full-4: 70px;

  /* Named Radii */
  --radius-body: 16px;
  --radius-cards: 5px;
  --radius-other: 8px;
  --radius-images: 8px;
  --radius-inputs: 50px;
  --radius-buttons: 24px;

  /* Shadows */
  --shadow-md: rgba(255, 97, 5, 0.6) 1px 6px 14px 0px, rgba(0, 0, 0, 0.06) 0px 1px 4px 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-orange-ember: #ff6105;
  --color-soft-peach: #ffdfcd;
  --color-warm-glow: #ffa069;
  --color-ash-gray: #e5e5e5;
  --color-deep-graphite: #0a0a0a;
  --color-white-canvas: #ffffff;
  --color-light-mist: #f3f4f3;
  --color-dark-slate-border: #3c3e3d;
  --color-dark-charcoal: #292b2a;
  --color-ghost-gray: #e5e7eb;
  --color-true-black: #202120;
  --color-muted-stone: #7a7b7b;
  --color-pale-silver: #a2a3a2;
  --color-light-border: #dfe0df;

  /* Typography */
  --font-publicasans: 'PublicaSans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --text-body-sm: 14px;
  --leading-body-sm: 1.56;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.33;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.22;
  --tracking-heading-sm: -0.24px;
  --text-heading: 32px;
  --leading-heading: 1.2;
  --tracking-heading: -0.32px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.96px;
  --text-display: 72px;
  --leading-display: 0.94;
  --tracking-display: -2.16px;
  --text-display-xl: 78px;
  --leading-display-xl: 0.71;
  --tracking-display-xl: -2.808px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-56: 56px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-112: 112px;

  /* Border Radius */
  --radius-md: 5px;
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;
  --radius-3xl-3: 40px;
  --radius-full: 50px;
  --radius-full-2: 53px;
  --radius-full-3: 56.16px;
  --radius-full-4: 70px;

  /* Shadows */
  --shadow-md: rgba(255, 97, 5, 0.6) 1px 6px 14px 0px, rgba(0, 0, 0, 0.06) 0px 1px 4px 0px;
}
```

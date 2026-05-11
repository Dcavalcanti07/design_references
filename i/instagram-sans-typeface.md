# Instagram Sans Typeface — Style Reference
> Vibrant typographic canvas.

**Theme:** light

Instagram's brand style is a high-contrast, playful expression embracing its custom typeface, Instagram Sans. The visual system revolves around vivid fuchsia and violet hues, juxtaposed with crisp black and white. Layouts are spacious, featuring strong typographic statements and graphic elements with subtle rounded corners, creating an energetic and modern feel without relying on complex shadows or textures. Color primarily functions as a bold brand identifier and a backdrop for clean, legible text.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Fuchsia Burst | `#f689ff` | `--color-fuchsia-burst` | Dominant brand background, graphic fills, hero section canvas creating high energy |
| Violet Dream | `#385898` | `--color-violet-dream` | Interactive link text, outlined interactive elements, decorative imagery borders – a cool counterpoint to the fuchsia |
| Licorice Ink | `#1c1e21` | `--color-licorice-ink` | Primary text, prominent headings, strong borders – provides robust contrast on light backgrounds |
| Achromatic Black | `#000000` | `--color-achromatic-black` | Bold interface elements, navigation text, icons, and strong outlines |
| Canvas White | `#ffffff` | `--color-canvas-white` | Backgrounds for content areas, primary text on dark backgrounds, fill for ghost buttons, and contrast for icons |
| Silver Whisper | `#cccccc` | `--color-silver-whisper` | Subtle button borders, fine dividing lines for separation |
| Gradient Sunset | `linear-gradient(72.44deg, rgb(255, 1, 105) 4.69%, rgb(211, 0, 197) 48.96%, rgb(118, 56, 250) 92.19%)` | `--color-gradient-sunset` | Decorative brand elements, iconography, and backgrounds where the full spectrum of Instagram's brand identity is desired |

## Tokens — Typography

### Helvetica — Fallback for generic UI elements, ensuring system-level consistency if the custom typeface isn't available. Less characterful, but provides broad support. · `--font-helvetica`
- **Substitute:** Arial
- **Weights:** 400
- **Sizes:** 12px, 224px
- **Line height:** 1.20, 1.34
- **Letter spacing:** normal
- **Role:** Fallback for generic UI elements, ensuring system-level consistency if the custom typeface isn't available. Less characterful, but provides broad support.

### Instagram Sans — Primary brand typeface for all headings, body text, and interactive elements. Its contemporary remix of grotesque and geometric styles, coupled with unique quirks like sheared terminals, defines the brand's friendly and accessible voice. · `--font-instagram-sans`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 12px, 16px, 24px, 32px, 40px, 46px, 62px, 72px, 121px, 205px, 224px, 389px
- **Line height:** 1.00, 1.05, 1.20, 1.34
- **Letter spacing:** -0.035em at 389px, -0.030em at 224px, -0.020em at 121px, normal at 12px
- **Role:** Primary brand typeface for all headings, body text, and interactive elements. Its contemporary remix of grotesque and geometric styles, coupled with unique quirks like sheared terminals, defines the brand's friendly and accessible voice.

### Instagram Sans Headline — Instagram Sans Headline — detected in extracted data but not described by AI · `--font-instagram-sans-headline`
- **Weights:** 400
- **Sizes:** 468px
- **Line height:** 1
- **Letter spacing:** -0.006
- **Role:** Instagram Sans Headline — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.2 | — | `--text-caption` |
| body | 16px | 1.2 | — | `--text-body` |
| subheading | 24px | 1.2 | — | `--text-subheading` |
| heading-sm | 32px | 1.2 | — | `--text-heading-sm` |
| heading | 40px | 1.05 | — | `--text-heading` |
| heading-lg | 62px | 1.05 | — | `--text-heading-lg` |
| display-sm | 121px | 1.05 | -0.02px | `--text-display-sm` |
| display-md | 224px | 1.05 | -0.03px | `--text-display-md` |
| display | 389px | 1 | -0.035px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** spacious

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 8 | 8px | `--spacing-8` |
| 16 | 16px | `--spacing-16` |
| 24 | 24px | `--spacing-24` |
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 88 | 88px | `--spacing-88` |
| 104 | 104px | `--spacing-104` |
| 160 | 160px | `--spacing-160` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 16px |
| shapes | 36.3636px |
| default | 3px |
| elements | 3px |

### Layout

- **Section gap:** 64px
- **Card padding:** 24px
- **Element gap:** 24px

## Components

### Text Only Button (Ghost)
**Role:** Interactive element for navigation or secondary actions, appearing as plain text that darkens on hover.

backgroundColor: transparent, color: #1c1e21 (default) or #ffffff (on dark backgrounds), borderRadius: 0px, padding: 0px.

### Filled White Call to Action
**Role:** Primary action button, providing strong visual emphasis without heavy branding color.

backgroundColor: #ffffff, color: #000000, borderRadius: 0px, paddingTop: 1px, paddingRight: 6px, paddingBottom: 16px, paddingLeft: 6px.

### Minimal Input Field
**Role:** Form input elements for collecting user data, designed to be unobtrusive.

backgroundColor: transparent, color: #ffffff, border: 1px solid #ffffff, borderRadius: 0px, paddingTop: 3px, paddingRight: 3px, paddingBottom: 3px, paddingLeft: 3px.

### Hero Headline
**Role:** Large, impactful text for hero sections, defining page presence.

Uses Instagram Sans, weight 400, size 389px or 468px, lineHeight 1.00, letterSpacing -0.035em or -0.006em, color #ffffff.

### Feature Card
**Role:** Container for showcasing key features or content blocks.

backgroundColor: #ffffff (implied from text color on backgrounds), borderRadius: 16px, padding: 24px.

## Do's and Don'ts

### Do
- Use 'Fuchsia Burst' (#f689ff) primarily as a background color or for large graphic fills to define sections.
- Apply 'Licorice Ink' (#1c1e21) for all body text and prominent headings on light canvases, ensuring high contrast.
- Utilize Instagram Sans for all textual content, adjusting letter-spacing according to size to maintain legibility and brand character (e.g., -0.035em for very large sizes).
- Maintain generous spacing, with section gaps typically at `64px` and element gaps at `24px` for readability and visual breathing room.
- Employ 'Violet Dream' (#385898) for interactive link text and subtle outlined interactive states, providing a consistent accent.
- Use a default border radius of `3px` for most components, but `16px` for cards to create distinct content blocks.
- Incorporate the 'Gradient Sunset' linear gradient for decorative brand elements and iconography where a full visual spectrum is desired.

### Don't
- Avoid using multiple chromatic colors for primary UI elements; reserve 'Fuchsia Burst' and 'Violet Dream' for specific brand or interactive accents.
- Do not introduce heavy shadows or complex elevation; the system relies on bold color blocks and typography for visual hierarchy.
- Refrain from using generic system fonts when Instagram Sans is available; the custom typeface is a core brand identity element.
- Do not deviate from the established letter-spacing values for Instagram Sans at various sizes; they are critical for its distinct appearance.
- Avoid tight padding or element spacing; the spacious density is a key characteristic of the design language.
- Do not use subtle, desaturated colors for backgrounds or primary text; the system thrives on high-contrast, vivid pairings.
- Do not apply large, inconsistent border radii; adhere to `3px` for most UI elements and `16px` for cards.

## Imagery

The visual language focuses on typographic displays and illustrative vector graphics. Imagery is predominantly abstract, focusing on the deconstructed elements of the Instagram Sans typeface itself or the brand's iconic glyph. When photography is present, it's minimal and serves as a backdrop. There is heavy use of line art and vector fills in brand colors for icons and illustrative elements. The density is image-light, with visual space dominated by large typography and color blocks. The icons tend to be filled rather than outlined, maintaining a solid, confident presence.

## Layout

The page exhibits a full-bleed layout alternating between large, horizontally split sections. The hero showcases a prominent, centered headline over a split background of 'Fuchsia Burst' and 'Violet Dream'. Subsequent sections utilize a maximum-width contained content area for text, always centered. Vertical rhythm is established through consistent `64px` section gaps. Content arrangement primarily consists of text blocks either left-aligned or centered within these contained areas, often juxtaposed with large graphic elements. The navigation is a minimal top bar.

## Agent Prompt Guide

Quick Color Reference:
text: #1c1e21
background: #ffffff
border: #cccccc
accent: #f689ff
primary action: #385898 (outlined action border)

Example Component Prompts:
Create a hero section: 'Fuchsia Burst' (#f689ff) background, centered headline 'Hello Instagram Sans' using Instagram Sans weight 400, size 389px, lineHeight 1.0, letterSpacing -0.035em, color #ffffff. Below that, a down arrow icon in 'Canvas White' (#ffffff).
Create a feature card: 'Canvas White' (#ffffff) background, 16px border-radius, 24px padding. Headline 'A New Typography' in Instagram Sans weight 400, size 32px, lineHeight 1.20, color 'Licorice Ink' (#1c1e21). Body text in Instagram Sans weight 400, size 16px, lineHeight 1.20, color 'Licorice Ink' (#1c1e21).
Create a ghost button: Using Instagram Sans weight 400, size 16px, lineHeight 1.20, color 'Licorice Ink' (#1c1e21), background transparent, 0px border-radius, 0px padding. Text: 'Learn More'.

## Similar Brands

- **Apple** — Prominent use of a custom sans-serif typeface, clean high-contrast text on solid color backgrounds, and minimalist component design.
- **Spotify (older branding)** — Bold use of saturated, bright colors (like a vibrant green) paired with strong typography and minimal visual clutter.
- **Linear** — Focus on high-contrast black and white UI, strong typographic hierarchy, and limited, impactful use of a single accent color.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-fuchsia-burst: #f689ff;
  --color-violet-dream: #385898;
  --color-licorice-ink: #1c1e21;
  --color-achromatic-black: #000000;
  --color-canvas-white: #ffffff;
  --color-silver-whisper: #cccccc;
  --color-gradient-sunset: #ff0169;
  --gradient-gradient-sunset: linear-gradient(72.44deg, rgb(255, 1, 105) 4.69%, rgb(211, 0, 197) 48.96%, rgb(118, 56, 250) 92.19%);

  /* Typography — Font Families */
  --font-helvetica: 'Helvetica', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-instagram-sans: 'Instagram Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-instagram-sans-headline: 'Instagram Sans Headline', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.2;
  --text-body: 16px;
  --leading-body: 1.2;
  --text-subheading: 24px;
  --leading-subheading: 1.2;
  --text-heading-sm: 32px;
  --leading-heading-sm: 1.2;
  --text-heading: 40px;
  --leading-heading: 1.05;
  --text-heading-lg: 62px;
  --leading-heading-lg: 1.05;
  --text-display-sm: 121px;
  --leading-display-sm: 1.05;
  --tracking-display-sm: -0.02px;
  --text-display-md: 224px;
  --leading-display-md: 1.05;
  --tracking-display-md: -0.03px;
  --text-display: 389px;
  --leading-display: 1;
  --tracking-display: -0.035px;

  /* Typography — Weights */
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-88: 88px;
  --spacing-104: 104px;
  --spacing-160: 160px;

  /* Layout */
  --section-gap: 64px;
  --card-padding: 24px;
  --element-gap: 24px;

  /* Border Radius */
  --radius-sm: 3px;
  --radius-2xl: 16px;
  --radius-3xl: 36.3636px;

  /* Named Radii */
  --radius-cards: 16px;
  --radius-shapes: 36.3636px;
  --radius-default: 3px;
  --radius-elements: 3px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-fuchsia-burst: #f689ff;
  --color-violet-dream: #385898;
  --color-licorice-ink: #1c1e21;
  --color-achromatic-black: #000000;
  --color-canvas-white: #ffffff;
  --color-silver-whisper: #cccccc;
  --color-gradient-sunset: #ff0169;

  /* Typography */
  --font-helvetica: 'Helvetica', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-instagram-sans: 'Instagram Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-instagram-sans-headline: 'Instagram Sans Headline', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.2;
  --text-body: 16px;
  --leading-body: 1.2;
  --text-subheading: 24px;
  --leading-subheading: 1.2;
  --text-heading-sm: 32px;
  --leading-heading-sm: 1.2;
  --text-heading: 40px;
  --leading-heading: 1.05;
  --text-heading-lg: 62px;
  --leading-heading-lg: 1.05;
  --text-display-sm: 121px;
  --leading-display-sm: 1.05;
  --tracking-display-sm: -0.02px;
  --text-display-md: 224px;
  --leading-display-md: 1.05;
  --tracking-display-md: -0.03px;
  --text-display: 389px;
  --leading-display: 1;
  --tracking-display: -0.035px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-88: 88px;
  --spacing-104: 104px;
  --spacing-160: 160px;

  /* Border Radius */
  --radius-sm: 3px;
  --radius-2xl: 16px;
  --radius-3xl: 36.3636px;
}
```

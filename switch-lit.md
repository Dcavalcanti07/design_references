# Switch-Lit — Style Reference
> Type-driven collaborative canvas

**Theme:** light

Switch-Lit creates a collaborative writing experience through a playful, slightly tactile, and monochrome design. Its visual identity relies on dynamic typography, abundant whitespace, and a limited color palette featuring muted, vibrant color washes as accent backdrops. Surfaces are predominantly light with subtle borders, while interactive elements subtly animate, giving the interface a responsive, engaging feel.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#000000` | `--color-midnight-ink` | Primary text, borders, button outlines, and key icon strokes — offering sharp contrast against light backgrounds |
| Cloud Canvas | `#f9f9f7` | `--color-cloud-canvas` | Page backgrounds, card surfaces, and filled buttons — forming the primary light canvas of the UI |
| Stone Whisper | `#d2ddd2` | `--color-stone-whisper` | Subtle card borders and secondary button outlines, providing gentle visual separation without starkness |
| Mist Gray | `#edf0e9` | `--color-mist-gray` | Background for secondary buttons and subtle surface accents |
| Lunar Dust | `#dee5dd` | `--color-lunar-dust` | Soft icon strokes, subtle dividers, and low-emphasis decorative details. Do not promote it to the primary CTA color |
| Sky Tint | `#bed4fb` | `--color-sky-tint` | Violet wash for highlight backgrounds, decorative bands, and soft emphasis behind content. Do not promote it to the primary CTA color |
| Lime Glow | `#edfe5e` | `--color-lime-glow` | Green wash for highlight backgrounds, decorative bands, and soft emphasis behind content. Do not promote it to the primary CTA color |
| Mint Burst | `#31e992` | `--color-mint-burst` | Small decorative background accents |

## Tokens — Typography

### ABCArizonaSans — General body text, button labels, navigation items, and various UI elements, providing a consistent, legible base with slightly tighter letter-spacing for denser information. · `--font-abcarizonasans`
- **Substitute:** Inter
- **Weights:** 400, 500, 700
- **Sizes:** 11px, 13px, 15px, 16px, 18px
- **Line height:** 1.00, 1.15, 1.18, 1.25, 1.27
- **Letter spacing:** 0.067em at 11px, 0.046em at 13px, 0.040em at 15px, 0.036em at 16px, 0.033em at 18px
- **Role:** General body text, button labels, navigation items, and various UI elements, providing a consistent, legible base with slightly tighter letter-spacing for denser information.

### ABCArizonaSansVariable — Card titles, navigation links, and specific body text where a more expressive, variable font is desired, often with slightly wider tracking. · `--font-abcarizonasansvariable`
- **Substitute:** Inter Variable
- **Weights:** 400, 500
- **Sizes:** 11px, 15px, 18px
- **Line height:** 1.00, 1.11, 1.18, 1.36, 1.40
- **Letter spacing:** 0.091em at 11px, 0.040em at 15px, 0.036em at 18px
- **Role:** Card titles, navigation links, and specific body text where a more expressive, variable font is desired, often with slightly wider tracking.

### ABCArizonaFlare-Regular — Declarative headings and badges, featuring moderate sizes and a 'whisper-weight' 300 that conveys authority through elegance and restraint, not volume. · `--font-abcarizonaflare-regular`
- **Substitute:** Lora
- **Weights:** 300, 400
- **Sizes:** 24px, 27px, 28px, 57px
- **Line height:** 0.93, 1.04, 1.07, 1.11
- **Letter spacing:** 0.011em at 24px, 0.004em at 27px, -0.002em at 57px
- **Role:** Declarative headings and badges, featuring moderate sizes and a 'whisper-weight' 300 that conveys authority through elegance and restraint, not volume.

### ABCCamera-Heavy — Large, impactful display headings that utilize a bold, almost blocky aesthetic with tight tracking to create a strong visual presence. · `--font-abccamera-heavy`
- **Substitute:** Anton
- **Weights:** 400, 700
- **Sizes:** 64px, 68px
- **Line height:** 0.74, 0.94, 1.00
- **Letter spacing:** -0.001em at 64px and 68px
- **Role:** Large, impactful display headings that utilize a bold, almost blocky aesthetic with tight tracking to create a strong visual presence.

### ABCArizonaMixVariable — Distinct small headings, using a bold weight and subtle letter-spacing for emphasis. · `--font-abcarizonamixvariable`
- **Substitute:** Inter Variable
- **Weights:** 700
- **Sizes:** 20px
- **Line height:** 1.15
- **Letter spacing:** 0.025em at 20px
- **Role:** Distinct small headings, using a bold weight and subtle letter-spacing for emphasis.

### ABCArizonaText — Prominent button text and emphasized body text, leveraging boldness for clear calls to action and important information. · `--font-abcarizonatext`
- **Substitute:** Inter
- **Weights:** 700
- **Sizes:** 20px
- **Line height:** 1.00
- **Letter spacing:** 0em
- **Role:** Prominent button text and emphasized body text, leveraging boldness for clear calls to action and important information.

### ABCArizonaMix — Specific body text requiring a distinctive, open feel due to slightly wider letter-spacing. · `--font-abcarizonamix`
- **Substitute:** Inter
- **Weights:** 500
- **Sizes:** 20px
- **Line height:** 1.25
- **Letter spacing:** 0.100em at 20px
- **Role:** Specific body text requiring a distinctive, open feel due to slightly wider letter-spacing.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 11px | 1 | 0.067px | `--text-caption` |
| body | 15px | 1.18 | 0.04px | `--text-body` |
| subheading | 18px | 1.25 | 0.033px | `--text-subheading` |
| heading-sm | 20px | 1 | 0.025px | `--text-heading-sm` |
| heading | 24px | 1.04 | 0.011px | `--text-heading` |
| heading-lg | 27px | 1.07 | 0.004px | `--text-heading-lg` |
| display | 64px | 0.74 | -0.001px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 5 | 5px | `--spacing-5` |
| 6 | 6px | `--spacing-6` |
| 8 | 8px | `--spacing-8` |
| 10 | 10px | `--spacing-10` |
| 12 | 12px | `--spacing-12` |
| 13 | 13px | `--spacing-13` |
| 15 | 15px | `--spacing-15` |
| 16 | 16px | `--spacing-16` |
| 19 | 19px | `--spacing-19` |
| 20 | 20px | `--spacing-20` |
| 29 | 29px | `--spacing-29` |
| 30 | 30px | `--spacing-30` |
| 40 | 40px | `--spacing-40` |
| 60 | 60px | `--spacing-60` |
| 160 | 160px | `--spacing-160` |
| 170 | 170px | `--spacing-170` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 6px |
| forms | 6px |
| links | 3px |
| buttons | 24px |
| elements | 6px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| sm | `rgba(0, 0, 0, 0.2) 0px 2px 6px 0px` | `--shadow-sm` |

### Layout

- **Section gap:** 40px
- **Card padding:** 20px
- **Element gap:** 20px

## Components

### Primary Filled Button
**Role:** Main calls to action

Solid button with Cloud Canvas (#f9f9f7) background, Midnight Ink (#000000) text and border, featuring a soft 24px border-radius and a subtle shadow. Padding is 0px vertical, 29px horizontal.

### Secondary Filled Button
**Role:** Secondary actions or navigation

Solid button with Mist Gray (#edf0e9) background, Midnight Ink (#000000) text, and Stone Whisper (#d2ddd2) border with a 6px border-radius. Padding is 0px vertical, unspecified horizontal.

### Ghost Outlined Button
**Role:** Tertiary actions or navigation

Transparent button with rgba(210, 221, 210, 0.2) background, Lunar Dust (#dee5dd) text and border, featuring a 6px border-radius. Padding is 0px vertical, 12px horizontal.

### Basic Card
**Role:** Content grouping without visual elevation

Transparent card with no background or shadow, 0px border-radius. Padding is 0px.

### Sectional Card (subtle background)
**Role:** Content grouping with slight visual separation

Card with rgba(233, 238, 231, 0.5) background and 12px border-radius, no shadow. Padding is 0px.

### Circular Element
**Role:** Decorative or specific interactive elements

Transparent element with 50% border-radius, creating a circular shape. No background or shadow. Padding is 0px.

### Accent Card
**Role:** Container with specific branding implications

Card with no background, 6px border radius, and a tall aspect ratio set by a large bottom padding (421.125px).

## Do's and Don'ts

### Do
- Use Midnight Ink (#000000) for all primary text and critical borders to maintain sharp legibility.
- Apply Cloud Canvas (#f9f9f7) as the primary background for pages and card surfaces.
- Prioritize ABCArizonaSans for general UI text and ABCArizonaFlare-Regular for heads, employing their specific letter-spacing values.
- Maintain a comfortable density with a 20px `elementGap` between UI components and `cardPadding` inside content blocks.
- Utilize the 24px `radius` for prominent buttons and 6px `radius` for cards and secondary interactive elements.
- Incorporate subtle motion (0.3s ease) for property changes like `transform`, `box-shadow`, and `background-color` to provide responsive feedback.
- Employ Sky Tint (#bed4fb) or Lime Glow (#edfe5e) as background washes for entire sections to subtly differentiate content areas or introduce accent.
- Use 0px vertical padding for all button types, relying on line height for vertical sizing.

### Don't
- Avoid arbitrary border-radius values; stick to 3px, 6px, 12px, or 24px defined in the system.
- Do not introduce new saturated colors beyond Sky Tint, Lime Glow, and Mint Burst, as the system relies on a restrained palette.
- Do not use heavy, opaque shadows; if shadows are needed, use `rgba(0, 0, 0, 0.2) 0px 2px 6px 0px` sparingly for interactive buttons.
- Do not deviate from the specified font families, weights, and letter-spacing for consistency in brand voice and readability.
- Avoid tightly packed layouts; ensure adequate spacing, defaulting to a 20px `elementGap`.
- Do not use dark backgrounds for full sections without strong justification; the system is designed explicitly for a light theme.
- Do not introduce gradients; the system relies on solid colors or background washes for visual depth.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Cloud Canvas | `#f9f9f7` | Primary page and card backgrounds, the base layer of the UI. |
| 2 | Mist Gray | `#edf0e9` | Background for secondary buttons and subtle accents, slightly differentiated from the main canvas. |
| 3 | Accent Wash | `#bed4fb` | Sectional background washes (e.g., Sky Tint, Lime Glow) to visually segment content or highlight areas. |

## Elevation

- **Primary Filled Button:** `rgba(0, 0, 0, 0.2) 0px 2px 6px 0px`

## Imagery

Imagery is minimal and primarily serves as decorative background washes or to illustrate conceptual points rather than showcasing products or people. When present, it features abstract, muted, or vivid color blocks that integrate seamlessly with the light theme. Icons are outlined, typically Midnight Ink (#000000) or Lunar Dust (#dee5dd), with a clean, functional style.

## Layout

The layout is primarily a full-bleed design, allowing accent color washes to extend edge-to-edge. Content appears to be centered within a comfortable, unrestrained width, allowing for ample whitespace. Hero sections feature large, bold typography from ABCCamera-Heavy. Sections are rhythmically organized with consistent vertical spacing and alternating background washes (e.g., Sky Tint, Lime Glow) or the default Cloud Canvas. Content often appears in stacked blocks or implied two-column arrangements for feature descriptions. Navigation is standard top-bar style, and components feel comfortable rather than dense.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #f9f9f7
border: #000000
accent: #bed4fb
primary action: no distinct CTA color

Example Component Prompts:
No distinct primary action color was observed; use the extracted neutral button treatments instead of inventing a filled CTA color.
2. Design a Ghost Outlined Button: background transparent, text #dee5dd, border #d2ddd2, 6px radius, 0px vertical padding, 12px horizontal padding.
3. Create a section heading using ABCArizonaFlare-Regular, weight 300, 57px size, lineHeight 0.93, letterSpacing -0.002em, color #000000. Underneath, add body text using ABCArizonaSans, weight 400, 15px size, lineHeight 1.18, letterSpacing 0.040em, color #000000.
4. Design a Sectional Card: background rgba(233, 238, 231, 0.5), 12px radius, with 20px card padding and a default 20px element gap for internal components.

## Similar Brands

- **Are.na** — Monochrome palette with limited accent colors, focus on typography and subtle grid-based content organization.
- **Superside** — Prominent use of varied bold typography, clean white backgrounds, and a focus on clarity through whitespace.
- **Read.cv** — Type-heavy design with a sparse color palette, large impactful headings, and a focus on content presentation.
- **Ghost** — Minimalist aesthetic, strong typographic hierarchy, and a restrained color palette that prioritizes readability.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-cloud-canvas: #f9f9f7;
  --color-stone-whisper: #d2ddd2;
  --color-mist-gray: #edf0e9;
  --color-lunar-dust: #dee5dd;
  --color-sky-tint: #bed4fb;
  --color-lime-glow: #edfe5e;
  --color-mint-burst: #31e992;

  /* Typography — Font Families */
  --font-abcarizonasans: 'ABCArizonaSans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-abcarizonasansvariable: 'ABCArizonaSansVariable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-abcarizonaflare-regular: 'ABCArizonaFlare-Regular', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-abccamera-heavy: 'ABCCamera-Heavy', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-abcarizonamixvariable: 'ABCArizonaMixVariable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-abcarizonatext: 'ABCArizonaText', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-abcarizonamix: 'ABCArizonaMix', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1;
  --tracking-caption: 0.067px;
  --text-body: 15px;
  --leading-body: 1.18;
  --tracking-body: 0.04px;
  --text-subheading: 18px;
  --leading-subheading: 1.25;
  --tracking-subheading: 0.033px;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1;
  --tracking-heading-sm: 0.025px;
  --text-heading: 24px;
  --leading-heading: 1.04;
  --tracking-heading: 0.011px;
  --text-heading-lg: 27px;
  --leading-heading-lg: 1.07;
  --tracking-heading-lg: 0.004px;
  --text-display: 64px;
  --leading-display: 0.74;
  --tracking-display: -0.001px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-13: 13px;
  --spacing-15: 15px;
  --spacing-16: 16px;
  --spacing-19: 19px;
  --spacing-20: 20px;
  --spacing-29: 29px;
  --spacing-30: 30px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-160: 160px;
  --spacing-170: 170px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 20px;
  --element-gap: 20px;

  /* Border Radius */
  --radius-sm: 3px;
  --radius-md: 6px;
  --radius-xl: 12px;
  --radius-3xl: 24px;

  /* Named Radii */
  --radius-cards: 6px;
  --radius-forms: 6px;
  --radius-links: 3px;
  --radius-buttons: 24px;
  --radius-elements: 6px;

  /* Shadows */
  --shadow-sm: rgba(0, 0, 0, 0.2) 0px 2px 6px 0px;

  /* Surfaces */
  --surface-cloud-canvas: #f9f9f7;
  --surface-mist-gray: #edf0e9;
  --surface-accent-wash: #bed4fb;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-cloud-canvas: #f9f9f7;
  --color-stone-whisper: #d2ddd2;
  --color-mist-gray: #edf0e9;
  --color-lunar-dust: #dee5dd;
  --color-sky-tint: #bed4fb;
  --color-lime-glow: #edfe5e;
  --color-mint-burst: #31e992;

  /* Typography */
  --font-abcarizonasans: 'ABCArizonaSans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-abcarizonasansvariable: 'ABCArizonaSansVariable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-abcarizonaflare-regular: 'ABCArizonaFlare-Regular', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-abccamera-heavy: 'ABCCamera-Heavy', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-abcarizonamixvariable: 'ABCArizonaMixVariable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-abcarizonatext: 'ABCArizonaText', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-abcarizonamix: 'ABCArizonaMix', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1;
  --tracking-caption: 0.067px;
  --text-body: 15px;
  --leading-body: 1.18;
  --tracking-body: 0.04px;
  --text-subheading: 18px;
  --leading-subheading: 1.25;
  --tracking-subheading: 0.033px;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1;
  --tracking-heading-sm: 0.025px;
  --text-heading: 24px;
  --leading-heading: 1.04;
  --tracking-heading: 0.011px;
  --text-heading-lg: 27px;
  --leading-heading-lg: 1.07;
  --tracking-heading-lg: 0.004px;
  --text-display: 64px;
  --leading-display: 0.74;
  --tracking-display: -0.001px;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-13: 13px;
  --spacing-15: 15px;
  --spacing-16: 16px;
  --spacing-19: 19px;
  --spacing-20: 20px;
  --spacing-29: 29px;
  --spacing-30: 30px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-160: 160px;
  --spacing-170: 170px;

  /* Border Radius */
  --radius-sm: 3px;
  --radius-md: 6px;
  --radius-xl: 12px;
  --radius-3xl: 24px;

  /* Shadows */
  --shadow-sm: rgba(0, 0, 0, 0.2) 0px 2px 6px 0px;
}
```

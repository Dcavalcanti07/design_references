# Marco — Style Reference
> organized content on frosted glass

**Theme:** light

Macro.fyi presents a functional white-canvas aesthetic, emphasizing content organization within distinct, softly shadowed containers. The system balances readability with a dense information display, utilizing a largely achromatic palette punctuated by a sole vivid violet for actionable elements and subtle gradient accents for dynamic cards.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card base layer, foundational surface |
| Card Frost | `#f7f7f9` | `--color-card-frost` | Default card backgrounds, subtle surface distinction from the main canvas |
| Whisper Gray | `#f2f2f2` | `--color-whisper-gray` | Subtle background for UI elements, light active states |
| Cloud Tint | `#eff0ff` | `--color-cloud-tint` | Light background for specific interactive cards or linked elements, a slight cool tint |
| Warm Paper | `#fff9ed` | `--color-warm-paper` | Background for information cards, providing a soft, accessible contrast to the standard frost |
| Text Primary | `#333333` | `--color-text-primary` | Primary text, headings, and crucial interface elements for high readability |
| Text Secondary | `#707070` | `--color-text-secondary` | Secondary text, muted headlines, subtle labels |
| Text Dim | `#949494` | `--color-text-dim` | Tertiary text, helper text, and subtle interface labels, receding slightly from text secondary |
| Divider Gray | `#cccccf` | `--color-divider-gray` | Muted UI surface for disabled controls, low-emphasis panels, and placeholder blocks. Do not promote it to the primary CTA color |
| Outline Blue | `#1685c7` | `--color-outline-blue` | Blue accent for outlined action borders, linked labels, and lightweight interactive emphasis. Do not promote it to the primary CTA color |
| Interactive Violet | `#6366f1` | `--color-interactive-violet` | Outline for active/focused elements, interactive links, and highlights — signals engagement dynamically |
| Gradient Sunset | `linear-gradient(16deg, rgb(255, 77, 121), rgb(255, 128, 64) 85%)` | `--color-gradient-sunset` | Supporting palette color for small decorative accents when the core palette needs contrast. Do not promote it to the primary CTA color |
| Alarm Red | `#e92f48` | `--color-alarm-red` | Red wash for highlight backgrounds, decorative bands, and soft emphasis behind content. Use as a supporting accent, not as a status color |
| Blush Shadow | `#f8c1c8` | `--color-blush-shadow` | Red supporting accent for decorative details and low-frequency emphasis. Use as a supporting accent, not as a status color |

## Tokens — Typography

### Maison Neue — Body text, card labels, and some section information. Its precise tracking supports dense information display without sacrificing clarity. · `--font-maison-neue`
- **Substitute:** Inter
- **Weights:** 400, 600
- **Sizes:** 12px, 14px, 40px
- **Line height:** 1.00, 1.43, 1.67
- **Letter spacing:** 0.0070em
- **Role:** Body text, card labels, and some section information. Its precise tracking supports dense information display without sacrificing clarity.

### Graphik — Headings and prominent links, its varied weights and tight letter spacing create a modern, impactful presence for key statements. · `--font-graphik`
- **Substitute:** Figtree
- **Weights:** 400, 500, 600
- **Sizes:** 14px, 16px, 20px, 31px
- **Line height:** 1.00, 1.25, 1.38, 1.43, 1.50
- **Letter spacing:** -0.0130em, 0.0050em, 0.0070em, 0.0140em
- **Role:** Headings and prominent links, its varied weights and tight letter spacing create a modern, impactful presence for key statements.

### Neue Montreal — Detailed labels, metadata, and small print, its generous letter-spacing at smaller sizes ensures legibility of ancillary information. · `--font-neue-montreal`
- **Substitute:** Montserrat
- **Weights:** 400, 500
- **Sizes:** 8px, 10px, 12px, 14px, 16px, 18px, 20px, 22px, 24px, 26px
- **Line height:** 1.00, 1.11, 1.13, 1.20, 1.25, 1.45, 1.67
- **Letter spacing:** 0.0090em, 0.0130em, 0.0200em, 0.0220em, 0.0250em, 0.0440em, 0.0500em, 0.0750em, 0.1000em, 0.2000em
- **Role:** Detailed labels, metadata, and small print, its generous letter-spacing at smaller sizes ensures legibility of ancillary information.

### Chirp — Used for specific social media embeds and some stylized links, maintaining its distinct character. · `--font-chirp`
- **Substitute:** Roboto
- **Weights:** 400, 700
- **Sizes:** 16px, 17px, 24px
- **Line height:** 1.20, 1.35, 1.40
- **Letter spacing:** normal
- **Role:** Used for specific social media embeds and some stylized links, maintaining its distinct character.

### SF Pro Display — SF Pro Display — detected in extracted data but not described by AI · `--font-sf-pro-display`
- **Weights:** 400, 600
- **Sizes:** 8px, 11px, 16px
- **Line height:** 0.75, 1.4, 1.63, 1.82
- **Letter spacing:** -0.004, 0.013, 0.018
- **Role:** SF Pro Display — detected in extracted data but not described by AI

### Bluu suuperstar — Bluu suuperstar — detected in extracted data but not described by AI · `--font-bluu-suuperstar`
- **Weights:** 700
- **Sizes:** 15px, 16px, 38px
- **Line height:** 1, 1.33
- **Role:** Bluu suuperstar — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body | 14px | 1.43 | — | `--text-body` |
| body-lg | 16px | 1.25 | — | `--text-body-lg` |
| subheading | 20px | 1.2 | 0.009px | `--text-subheading` |
| heading | 31px | 1.25 | -0.403px | `--text-heading` |
| display | 40px | 1.67 | — | `--text-display` |

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
| 64 | 64px | `--spacing-64` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 32px |
| badges | 100px |
| inputs | 8px |
| buttons | 230px |
| default | 12px |
| thumbnails | 18px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(0, 0, 0, 0.25) 0px 1px 2px 0px` | `--shadow-subtle` |
| subtle-2 | `rgba(0, 0, 0, 0.25) 0px 1px 3px 0px` | `--shadow-subtle-2` |
| subtle-3 | `rgba(0, 0, 0, 0.25) 0px 1px 1px 0px` | `--shadow-subtle-3` |
| subtle-4 | `rgba(0, 0, 0, 0.06) 0px 1px 2px 0px, rgba(0, 0, 0, 0.1) 0...` | `--shadow-subtle-4` |
| sm | `rgba(89, 100, 138, 0.16) 0px 2px 4px 0px` | `--shadow-sm` |
| subtle-5 | `rgba(0, 0, 0, 0.06) 0px 1px 2px 0px, rgba(0, 0, 0, 0.06) ...` | `--shadow-subtle-5` |
| subtle-6 | `rgba(0, 0, 0, 0.18) 0px 1px 2px 0px` | `--shadow-subtle-6` |
| subtle-7 | `rgba(0, 0, 0, 0.12) 0px 1px 2px 0px` | `--shadow-subtle-7` |
| subtle-8 | `rgba(0, 0, 0, 0.16) 0px 1px 2px 0px` | `--shadow-subtle-8` |
| sm-2 | `rgba(0, 0, 0, 0.05) 0px 4px 6px 0px, rgba(0, 0, 0, 0.1) 0...` | `--shadow-sm-2` |
| md | `rgba(0, 0, 0, 0.1) 0px 15px 10px -3px, rgba(0, 0, 0, 0.05...` | `--shadow-md` |
| md-2 | `rgba(0, 0, 0, 0.1) 0px 0px 10px -3px` | `--shadow-md-2` |
| lg | `rgba(233, 47, 72, 0.3) 0px 4px 24px 0px` | `--shadow-lg` |

### Layout

- **Page max-width:** 1400px
- **Section gap:** 24px
- **Card padding:** 32px
- **Element gap:** 8px

## Components

### Pill Navigation Button
**Role:** Top-level navigation and filter controls.

Ghost button with `Card Frost` background, `Text Primary` color, `230px` radius for a pill shape, and `12px` vertical, `24px` horizontal padding. No border unless active.

### Outline Action Button
**Role:** Secondary calls-to-action or subtle interactive elements.

Ghost button with `Outline Blue` border, `Text Primary` color, `56px` radius, and `10px` vertical, `16px` horizontal padding.

### Default Content Card
**Role:** Container for primary content blocks.

Background `Card Frost`, `32px` border-radius, no box shadow, `32px` padding on all sides. Houses main text content and sub-components.

### Layered Detail Card
**Role:** Elevated information or interactive listings within larger content areas.

Background can be `Cloud Tint` or `Warm Paper`. `8px` border-radius, subtle shadow `rgba(0, 0, 0, 0.06) 0px 1px 2px 0px, rgba(0, 0, 0, 0.1) 0px 1px 3px 0px`, and `8px` vertical padding with no horizontal padding.

### Ghost Card
**Role:** Purely structural grouping without visual adornment.

Transparent background, no border-radius, no shadow, no padding. Used for simple content wrapping.

### Gradient Action Card
**Role:** Prominent interactive elements or special offers.

Background `Gradient Sunset`, `32px` border-radius, `32px` padding. Contains inverted text for contrast.

### Input Field
**Role:** User input for forms.

White background, `Divider Gray` 1px border. Focus state border turns into `Interactive Violet`.

### Selected Link Badge
**Role:** Indicates active or selected items in a list.

Background `Cloud Tint`, border `Interactive Violet`, `100px` radius for a pill shape, `6px` vertical, `10px` horizontal padding.

## Do's and Don'ts

### Do
- Use `Text Primary` (#333333) for all main content and headings.
- Apply `Card Frost` (#f7f7f9) as the default background for content cards, reserving `Canvas White` (#ffffff) for the page background.
- Utilize `32px` border-radius for main content cards and larger organizational blocks.
- Employ `Outline Blue` (#1685c7) for borders of interactive elements when a filled background is not desired.
- Ensure generous `32px` padding within all `Default Content Card` elements.
- Differentiate interactive elements using `Interactive Violet` (#6366f1) for borders on focus or active states.
- Maintain a clear visual hierarchy by limiting prominent box shadows to `Layered Detail Card` elements, and keep them subtle.

### Don't
- Do not use highly saturated colors for large background areas; maintain the overall achromatic canvas.
- Avoid using multiple distinct colors for primary call-to-action buttons; the system emphasizes outlined chromatic actions.
- Do not use generic border-radii; adhere to the specified `32px` for cards, `230px` for pill buttons, and `8px` for inputs.
- Avoid deep, dark shadows; elevation is achieved through subtle, light box-shadows or subtle colored tints.
- Do not use large, decorative imagery; product screenshots and UI examples should be contained within cards.
- Refrain from drastically altering default typography letter-spacing for body text; rely on the defined values for each font family.
- Do not introduce new border styles; primarily use 1-4px solid borders with neutral or accent colors.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Page Canvas | `#ffffff` | Primary page background, expansive white space |
| 1 | Content Frost | `#f7f7f9` | Default background for main content cards and sections |
| 2 | Interactive Tint | `#eff0ff` | Background for active or emphasized cards and interactive elements |
| 3 | Elevated Shadow | `#fff9ed` | Background for visually distinct cards that appear slightly lifted, often with custom shadows |

## Elevation

- **Layered Detail Card:** `rgba(0, 0, 0, 0.06) 0px 1px 2px 0px, rgba(0, 0, 0, 0.1) 0px 1px 3px 0px`
- **Thumbnail Image:** `rgba(0, 0, 0, 0.25) 0px 1px 2px 0px`
- **Interactive Link with Shadow:** `rgba(0, 0, 0, 0.25) 0px 1px 3px 0px`

## Imagery

This site predominantly uses clean, contained product screenshots and carefully cropped UI examples, often within cards with rounded corners. Photography is minimal, focusing on atmospheric shots when present. Icons are primarily outlined or filled charcoal gray, with a consistent stroke weight, serving functional rather than decorative roles. The visual focus is on clarity and the presentation of work and tools, making the imagery explanatory and showcasing rather than atmospheric.

## Layout

The page uses a maximum width of 1400px but primarily feels constrained and organized, reminiscent of a desktop application. The hero section often features a centered headline over a subtle background. Content is arranged within distinct rectangular cards, leading to a grid-like or stacked flow with consistent vertical `24px` section gaps. Many sections feature side-by-side card arrangements, creating visual pairs. The overall density is compact but not crowded, with content clearly delineated by card boundaries and subtle shadows. Navigation is a simple top bar with pill-shaped ghost buttons.

## Agent Prompt Guide

### Quick Color Reference
- text: #333333
- background: #ffffff
- border: #cccccf
- accent: #6366f1
- primary action: #1685c7 (outlined action border)

### 3-5 Example Component Prompts
- Create a section divider: `1px solid #cccccf` border, `8px` vertical margin.
- Create an Outlined Primary Action: Transparent background, #1685c7 border and text, 9999px radius, compact pill padding. Use it for the main CTA instead of a filled button.
- Design a gradient action button: `Gradient Sunset` background `linear-gradient(16deg, rgb(255, 77, 121), rgb(255, 128, 64) 85%)`, `32px` border-radius, `Canvas White` (#ffffff) text color (Graphik weight 500, 16px), with `16px` vertical and `32px` horizontal padding.

## Similar Brands

- **Notion** — Uses a white canvas, extensive use of cards, and a compact, functional typography to organize varied content.
- **Linear** — Employs an achromatic palette with a singular vivid accent color (violet/blue), subtle card-based layouts, and precise typography.
- **Superhuman** — Focuses on clean UI, high information density, and card-like structures for productivity, with minimal imagery.
- **Read.cv** — Relies on a structured, card-based approach for showcasing work, utilizing subtle grays and distinct typography.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-card-frost: #f7f7f9;
  --color-whisper-gray: #f2f2f2;
  --color-cloud-tint: #eff0ff;
  --color-warm-paper: #fff9ed;
  --color-text-primary: #333333;
  --color-text-secondary: #707070;
  --color-text-dim: #949494;
  --color-divider-gray: #cccccf;
  --color-outline-blue: #1685c7;
  --color-interactive-violet: #6366f1;
  --color-gradient-sunset: #ff4d79;
  --gradient-gradient-sunset: linear-gradient(16deg, rgb(255, 77, 121), rgb(255, 128, 64) 85%);
  --color-alarm-red: #e92f48;
  --color-blush-shadow: #f8c1c8;

  /* Typography — Font Families */
  --font-maison-neue: 'Maison Neue', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-graphik: 'Graphik', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-neue-montreal: 'Neue Montreal', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-chirp: 'Chirp', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sf-pro-display: 'SF Pro Display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-bluu-suuperstar: 'Bluu suuperstar', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 14px;
  --leading-body: 1.43;
  --text-body-lg: 16px;
  --leading-body-lg: 1.25;
  --text-subheading: 20px;
  --leading-subheading: 1.2;
  --tracking-subheading: 0.009px;
  --text-heading: 31px;
  --leading-heading: 1.25;
  --tracking-heading: -0.403px;
  --text-display: 40px;
  --leading-display: 1.67;

  /* Typography — Weights */
  --font-weight-regular: 400;
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
  --spacing-64: 64px;

  /* Layout */
  --page-max-width: 1400px;
  --section-gap: 24px;
  --card-padding: 32px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 18px;
  --radius-3xl: 32px;
  --radius-3xl-2: 40px;
  --radius-full: 50px;
  --radius-full-2: 56px;
  --radius-full-3: 100px;
  --radius-full-4: 230px;
  --radius-full-5: 360px;

  /* Named Radii */
  --radius-cards: 32px;
  --radius-badges: 100px;
  --radius-inputs: 8px;
  --radius-buttons: 230px;
  --radius-default: 12px;
  --radius-thumbnails: 18px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.25) 0px 1px 2px 0px;
  --shadow-subtle-2: rgba(0, 0, 0, 0.25) 0px 1px 3px 0px;
  --shadow-subtle-3: rgba(0, 0, 0, 0.25) 0px 1px 1px 0px;
  --shadow-subtle-4: rgba(0, 0, 0, 0.06) 0px 1px 2px 0px, rgba(0, 0, 0, 0.1) 0px 1px 3px 0px;
  --shadow-sm: rgba(89, 100, 138, 0.16) 0px 2px 4px 0px;
  --shadow-subtle-5: rgba(0, 0, 0, 0.06) 0px 1px 2px 0px, rgba(0, 0, 0, 0.06) 0px 3px 3px 0px;
  --shadow-subtle-6: rgba(0, 0, 0, 0.18) 0px 1px 2px 0px;
  --shadow-subtle-7: rgba(0, 0, 0, 0.12) 0px 1px 2px 0px;
  --shadow-subtle-8: rgba(0, 0, 0, 0.16) 0px 1px 2px 0px;
  --shadow-sm-2: rgba(0, 0, 0, 0.05) 0px 4px 6px 0px, rgba(0, 0, 0, 0.1) 0px 10px 16px -3px;
  --shadow-md: rgba(0, 0, 0, 0.1) 0px 15px 10px -3px, rgba(0, 0, 0, 0.05) 0px 6px 4px -2px;
  --shadow-md-2: rgba(0, 0, 0, 0.1) 0px 0px 10px -3px;
  --shadow-lg: rgba(233, 47, 72, 0.3) 0px 4px 24px 0px;

  /* Surfaces */
  --surface-page-canvas: #ffffff;
  --surface-content-frost: #f7f7f9;
  --surface-interactive-tint: #eff0ff;
  --surface-elevated-shadow: #fff9ed;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-card-frost: #f7f7f9;
  --color-whisper-gray: #f2f2f2;
  --color-cloud-tint: #eff0ff;
  --color-warm-paper: #fff9ed;
  --color-text-primary: #333333;
  --color-text-secondary: #707070;
  --color-text-dim: #949494;
  --color-divider-gray: #cccccf;
  --color-outline-blue: #1685c7;
  --color-interactive-violet: #6366f1;
  --color-gradient-sunset: #ff4d79;
  --color-alarm-red: #e92f48;
  --color-blush-shadow: #f8c1c8;

  /* Typography */
  --font-maison-neue: 'Maison Neue', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-graphik: 'Graphik', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-neue-montreal: 'Neue Montreal', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-chirp: 'Chirp', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sf-pro-display: 'SF Pro Display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-bluu-suuperstar: 'Bluu suuperstar', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 14px;
  --leading-body: 1.43;
  --text-body-lg: 16px;
  --leading-body-lg: 1.25;
  --text-subheading: 20px;
  --leading-subheading: 1.2;
  --tracking-subheading: 0.009px;
  --text-heading: 31px;
  --leading-heading: 1.25;
  --tracking-heading: -0.403px;
  --text-display: 40px;
  --leading-display: 1.67;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-64: 64px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 18px;
  --radius-3xl: 32px;
  --radius-3xl-2: 40px;
  --radius-full: 50px;
  --radius-full-2: 56px;
  --radius-full-3: 100px;
  --radius-full-4: 230px;
  --radius-full-5: 360px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.25) 0px 1px 2px 0px;
  --shadow-subtle-2: rgba(0, 0, 0, 0.25) 0px 1px 3px 0px;
  --shadow-subtle-3: rgba(0, 0, 0, 0.25) 0px 1px 1px 0px;
  --shadow-subtle-4: rgba(0, 0, 0, 0.06) 0px 1px 2px 0px, rgba(0, 0, 0, 0.1) 0px 1px 3px 0px;
  --shadow-sm: rgba(89, 100, 138, 0.16) 0px 2px 4px 0px;
  --shadow-subtle-5: rgba(0, 0, 0, 0.06) 0px 1px 2px 0px, rgba(0, 0, 0, 0.06) 0px 3px 3px 0px;
  --shadow-subtle-6: rgba(0, 0, 0, 0.18) 0px 1px 2px 0px;
  --shadow-subtle-7: rgba(0, 0, 0, 0.12) 0px 1px 2px 0px;
  --shadow-subtle-8: rgba(0, 0, 0, 0.16) 0px 1px 2px 0px;
  --shadow-sm-2: rgba(0, 0, 0, 0.05) 0px 4px 6px 0px, rgba(0, 0, 0, 0.1) 0px 10px 16px -3px;
  --shadow-md: rgba(0, 0, 0, 0.1) 0px 15px 10px -3px, rgba(0, 0, 0, 0.05) 0px 6px 4px -2px;
  --shadow-md-2: rgba(0, 0, 0, 0.1) 0px 0px 10px -3px;
  --shadow-lg: rgba(233, 47, 72, 0.3) 0px 4px 24px 0px;
}
```

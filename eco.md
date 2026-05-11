# Eco — Style Reference
> Architectural tech blueprint. Polished surfaces and precise typography overlay an expansive, slightly muted cityscape.

**Theme:** mixed

Eco presents a refined, almost architectural aesthetic that blends high-tech precision with a subtle, underlying warmth. The visual impression is one of confident authority, conveyed through a largely achromatic palette punctuated by a single, vibrant gradient. Large, impactful typography with precise letter-spacing anchors sections, while soft, rounded elements provide a counterpoint to the generally sharp interface, creating a balanced and approachable digital experience for complex financial technology.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| White Smoke | `#ffffff` | `--color-white-smoke` | Primary page background, text on dark backgrounds, active states. |
| Off-White Mist | `#efefef` | `--color-off-white-mist` | Secondary backgrounds, subtly lifted UI elements, button fills. |
| Midnight Ink | `#0f111a` | `--color-midnight-ink` | Primary text on light backgrounds, dark mode backgrounds. |
| Dark Charcoal | `#000000` | `--color-dark-charcoal` | Deepest dark backgrounds, strong text contrast. |
| Near Black | `#141414` | `--color-near-black` | Subtle background depth in dark sections. |
| Light Steel | `#aeaeae` | `--color-light-steel` | Subtle text emphasis, inactive states, borders in light themes. |
| Graphite Grey | `#2a2a2a` | `--color-graphite-grey` | Button backgrounds, dark neutral elements. |
| Mid Grey | `#222222` | `--color-mid-grey` | Text on very light backgrounds, subtle borders. |
| Pale Ash | `#a0a0a0` | `--color-pale-ash` | Muted headings, secondary text, placeholders. |
| Skybound Gradient | `linear-gradient(90deg, rgb(28, 83, 189) 71%, rgb(83, 173, 254))` | `--color-skybound-gradient` | Highlight elements, interactive indicators, brand-specific imagery – draws attention and signifies modernity. |
| Cloud Grey | `#a6b8d1` | `--color-cloud-grey` | Subtle interactive link color, non-critical emphasis – a soft, cool blue-gray that hints at interaction without aggressive saturation. |

## Tokens — Typography

### Interdisplay — Primary display and heading font, used for impactful statements. The tight letter-spacing at larger sizes gives it a contemporary and precise feel. · `--font-interdisplay`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 14px, 16px, 24px, 40px, 84px, 90px, 96px
- **Line height:** 0.90, 0.95, 1.06, 1.20, 1.43, 1.50
- **Letter spacing:** -0.0400em, -0.0300em, -0.0200em, -0.0100em, 0.0180em
- **Role:** Primary display and heading font, used for impactful statements. The tight letter-spacing at larger sizes gives it a contemporary and precise feel.

### Roobert — Secondary display and heading font, also used for navigation and important interactive elements. Its strong presence at larger scales complements Interdisplay. · `--font-roobert`
- **Substitute:** Montserrat
- **Weights:** 400
- **Sizes:** 16px, 48px, 84px, 96px
- **Line height:** 0.95, 1.06, 1.20, 1.33
- **Letter spacing:** -0.0400em, -0.0300em, -0.0200em, -0.0100em
- **Role:** Secondary display and heading font, also used for navigation and important interactive elements. Its strong presence at larger scales complements Interdisplay.

### Inter — Standard body text and links. Slightly tighter letter-spacing ensures readability and a modern appearance. · `--font-inter`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 14px, 16px, 22px
- **Line height:** 1.00, 1.20, 1.50
- **Letter spacing:** -0.0200em, -0.0100em
- **Role:** Standard body text and links. Slightly tighter letter-spacing ensures readability and a modern appearance.

### Fragmentmono — Used for code snippets, secondary labels, and data points, providing a technical contrast to the primary sans-serifs. · `--font-fragmentmono`
- **Substitute:** Space Mono
- **Weights:** 400
- **Sizes:** 14px, 16px
- **Line height:** 1.00, 1.50, 1.71
- **Letter spacing:** -0.0100em
- **Role:** Used for code snippets, secondary labels, and data points, providing a technical contrast to the primary sans-serifs.

### Aeonik Mono — Specialized monospaced text, likely for unique technical labels or data. Its tight letter-spacing reinforces a precise data-driven feel. · `--font-aeonik-mono`
- **Substitute:** IBM Plex Mono
- **Weights:** 400
- **Sizes:** 14px
- **Line height:** 1.10
- **Letter spacing:** -0.0400em
- **Role:** Specialized monospaced text, likely for unique technical labels or data. Its tight letter-spacing reinforces a precise data-driven feel.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 14px | 1 | -0.01px | `--text-caption` |
| body | 16px | 1.5 | — | `--text-body` |
| subheading | 22px | 1.5 | -0.01px | `--text-subheading` |
| heading | 24px | 1.2 | -0.02px | `--text-heading` |
| heading-lg | 40px | 1.2 | -0.02px | `--text-heading-lg` |
| display | 96px | 0.95 | -0.04px | `--text-display` |

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
| 60 | 60px | `--spacing-60` |
| 80 | 80px | `--spacing-80` |
| 96 | 96px | `--spacing-96` |
| 172 | 172px | `--spacing-172` |

### Border Radius

| Element | Value |
|---------|-------|
| large | 128px |
| inputs | 8px |
| buttons | 8px |
| default | 8px |

### Layout

- **Section gap:** 48px
- **Card padding:** 0px
- **Element gap:** 8px

## Components

### Primary Filled Button
**Role:** Main call to action for interactive steps.

Filled with Graphite Grey (#2a2a2a), White Smoke text (#efefef), 8px border-radius, 8px vertical padding, 16px horizontal padding. No border, for a soft, inviting feel.

### Secondary Filled Button
**Role:** Alternative call to action, less prominent than primary.

Filled with Dark Gray (#302f2c), White Smoke text (#ffffff), 8px border-radius, 8px vertical padding, 20px horizontal padding. No border, offering a slightly bolder presence than primary.

### Text Link Button
**Role:** Minimalistic interactive elements, inline with text.

Transparent background, Mid Grey text (#222222), no border-radius. 5px vertical padding, 4px horizontal padding, for a subtle click target.

### Input Field
**Role:** Data entry fields across the application.

Background rgba(240, 240, 235, 0.18), White Smoke text (#ffffff), 8px border-radius. 16px vertical padding, 24px horizontal padding, promoting clear data input.

### Navigation Link
**Role:** Primary navigation items in headers and footers.

White Smoke text (#ffffff) on dark backgrounds, or Midnight Ink text (#0f111a) on light backgrounds. No background, typically 4px right margin, using Interdisplay font.

### Hero Headline
**Role:** Largest, most prominent text on key landing sections.

Roobert font, 96px size, 0.95 line-height, -0.0400em letter spacing, White Smoke color (#ffffff). Centered, commanding attention.

### Subheadline / Body Intro
**Role:** Supportive text for headlines or section introductions.

Interdisplay font, 24px size, 1.20 line-height, White Smoke color (#ffffff). Provides context to the large headlines.

## Do's and Don'ts

### Do
- Do use `Roobert` with `96px` size and `-0.0400em` letter spacing for hero headlines to maintain visual impact and precision.
- Do apply `8px` border-radius uniformly to all interactive elements like buttons and input fields.
- Do leverage the `Skybound Gradient` (`linear-gradient(90deg, rgb(28, 83, 189) 71%, rgb(83, 173, 254))`) only for key calls-to-action or distinct visual indicators.
- Do use `48px` as the standard `sectionGap` to ensure consistent vertical rhythm between major content blocks.
- Do prioritize `Midnight Ink (#0f111a)` for text on light backgrounds and `White Smoke (#ffffff)` for text on dark backgrounds for accessibility and brand consistency.
- Do use `Fragmentmono` for all technical code-like text or data displays, ensuring it is `14px` with a `1.00` line-height.
- Do align major content centrally within `pageMaxWidth` when an explicit max-width is later established, or maintain a full-bleed layout as seen in initial hero sections.

### Don't
- Don't use `Skybound Gradient` merely for decorative purposes; reserve it for functional or brand-critical highlights.
- Don't introduce additional border-radius values beyond `8px`, `12px`, and `128px` to preserve the established shape vocabulary.
- Don't deviate from the specified tight letter-spacing for `Interdisplay` and `Roobert` at larger sizes; it is a signature trait.
- Don't use highly saturated colors for backgrounds or large areas; maintain the largely achromatic base palette.
- Don't apply `box-shadow` for elevation on cards or containers; the system relies on background color shifts for depth.
- Don't use `Off-White Mist (#efefef)` for primary text, as it's intended for secondary backgrounds and subtle lifts, not high-contrast text.
- Don't introduce new font families; the current selection (Interdisplay, Roobert, Inter, Fragmentmono, Aeonik Mono) is curated for purpose.

## Imagery

The visual language for imagery is characterized by large, full-bleed photography, predominantly cityscapes and architectural scenes that serve as atmospheric backdrops rather than explicit content. Treatment involves a muted, often cool-toned filter applied to photographs, creating a mood that is serious and expansive. Images are typically contained full-bleed within sections, without rounded corners or masks, allowing them to fill the visible space. In other instances, there are abstract, subtle graphics or gradients used decoratively, providing visual interest without distracting from textual content. Product screenshots or specific UI elements are integrated cleanly within sections, usually with a dark, muted background, emphasizing the digital interface itself without much surrounding decoration. Icons are generally small, monochrome, and functional, adhering to an outlined style for subtle interaction hints. The overall density of imagery is balanced; it supports the text and theme but doesn't overwhelm the information.

## Layout

The site employs a mixed layout model, featuring full-bleed sections that transition into contained content sections. The hero section is a full-viewport, dark-themed area with a centered headline over a muted cityscape background, establishing a grand and serious tone. Following sections alternate between light and dark backgrounds, creating a clear visual rhythm. Content within these sections tends to be centrally aligned or uses a simple two-column arrangement, often text-left/image-right or vice-versa, for clear informational flow. Vertical spacing between sections is generous and consistent, using a `48px` `sectionGap`. Card grids, when present, likely feature `0px` padding, emphasizing their content directly. The navigation is a fixed top bar on light backgrounds, becoming active/visible on scroll but initially transparent against the dark hero, suggesting a subtle, less intrusive hierarchy.

## Agent Prompt Guide

### Quick Color Reference
- Text: `#0f111a` (Midnight Ink)
- Background: `#ffffff` (White Smoke)
- CTA: `#2a2a2a` (Graphite Grey)
- Border: `rgba(0,0,0,0)` (Transparent)
- Accent: `linear-gradient(90deg, rgb(28, 83, 189) 71%, rgb(83, 173, 254))` (Skybound Gradient)

### 3-5 Example Component Prompts
1. **Create a Primary Filled Button:** `background-color: #2a2a2a; color: #efefef; border-radius: 8px; padding: 8px 16px; font-family: Interdisplay; font-weight: 400; font-size: 14px; line-height: 1.43; letter-spacing: -0.0100em;`
2. **Generate a Hero Headline:** `font-family: Roobert; font-weight: 400; font-size: 96px; line-height: 0.95; letter-spacing: -0.0400em; color: #ffffff; text-align: center;`
3. **Design an Input Field:** `background-color: rgba(240, 240, 235, 0.18); color: #ffffff; border-radius: 8px; padding: 16px 24px; font-family: Inter; font-weight: 400; font-size: 16px; line-height: 1.50;`
4. **Build a Standard Body Text Paragraph:** `font-family: Inter; font-weight: 400; font-size: 16px; line-height: 1.50; color: #0f111a; letter-spacing: -0.0100em;`
5. **Construct a Secondary Section Subheading:** `font-family: Interdisplay; font-weight: 400; font-size: 24px; line-height: 1.20; letter-spacing: -0.0200em; color: #0f111a;`

## Similar Brands

- **Stripe** — A clear, functional design with a strong typographic presence and a reliance on a mostly monochromatic palette with minimal accent colors.
- **Linear** — Features a dark UI mode with precision in typography and spacing, paired with a subtle, yet impactful, accent color.
- **Vercel** — Employs a clean, high-tech aesthetic, using large, legible fonts and a sophisticated neutral color palette with purposeful dark sections.
- **Plaid** — Utilizes a strong focus on readability, disciplined use of white space, and a mix of light and dark sections to delineate content.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-white-smoke: #ffffff;
  --color-off-white-mist: #efefef;
  --color-midnight-ink: #0f111a;
  --color-dark-charcoal: #000000;
  --color-near-black: #141414;
  --color-light-steel: #aeaeae;
  --color-graphite-grey: #2a2a2a;
  --color-mid-grey: #222222;
  --color-pale-ash: #a0a0a0;
  --color-skybound-gradient: #1c53bd;
  --gradient-skybound-gradient: linear-gradient(90deg, rgb(28, 83, 189) 71%, rgb(83, 173, 254));
  --color-cloud-grey: #a6b8d1;

  /* Typography — Font Families */
  --font-interdisplay: 'Interdisplay', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-roobert: 'Roobert', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-fragmentmono: 'Fragmentmono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-aeonik-mono: 'Aeonik Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1;
  --tracking-caption: -0.01px;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 22px;
  --leading-subheading: 1.5;
  --tracking-subheading: -0.01px;
  --text-heading: 24px;
  --leading-heading: 1.2;
  --tracking-heading: -0.02px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -0.02px;
  --text-display: 96px;
  --leading-display: 0.95;
  --tracking-display: -0.04px;

  /* Typography — Weights */
  --font-weight-regular: 400;

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
  --spacing-60: 60px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-172: 172px;

  /* Layout */
  --section-gap: 48px;
  --card-padding: 0px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-full: 128px;

  /* Named Radii */
  --radius-large: 128px;
  --radius-inputs: 8px;
  --radius-buttons: 8px;
  --radius-default: 8px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-white-smoke: #ffffff;
  --color-off-white-mist: #efefef;
  --color-midnight-ink: #0f111a;
  --color-dark-charcoal: #000000;
  --color-near-black: #141414;
  --color-light-steel: #aeaeae;
  --color-graphite-grey: #2a2a2a;
  --color-mid-grey: #222222;
  --color-pale-ash: #a0a0a0;
  --color-skybound-gradient: #1c53bd;
  --color-cloud-grey: #a6b8d1;

  /* Typography */
  --font-interdisplay: 'Interdisplay', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-roobert: 'Roobert', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-fragmentmono: 'Fragmentmono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-aeonik-mono: 'Aeonik Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1;
  --tracking-caption: -0.01px;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 22px;
  --leading-subheading: 1.5;
  --tracking-subheading: -0.01px;
  --text-heading: 24px;
  --leading-heading: 1.2;
  --tracking-heading: -0.02px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -0.02px;
  --text-display: 96px;
  --leading-display: 0.95;
  --tracking-display: -0.04px;

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
  --spacing-60: 60px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-172: 172px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-full: 128px;
}
```

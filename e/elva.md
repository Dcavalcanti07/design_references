# Elva — Style Reference
> Typographic Brutalism in a Monochrome Gallery. The design feels like a curated exhibition where letterforms are the central art pieces.

**Theme:** light

This design system is a study in stark monochrome contrast, evoking a gallery space for typographic art. Large-scale, custom typography dominates, creating a bold, almost brutalist visual identity. The absence of color and subtle shifts in near-achromatic tones (#262523 on #ECECEC) place absolute focus on form, text, and playful graphic interventions within the letterforms themselves. Subtle hints of illustration are integrated directly into oversized headlines, turning text into hero content.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Anchor Black | `#262523` | `--color-anchor-black` | Primary text, headings, interactive elements (links, navigation items) — this near-black anchors all visual content. |
| Gallery White | `#ececec` | `--color-gallery-white` | Page backgrounds, large content blocks — provides a stark, clean canvas for the dominant typography. |
| Pure Black | `#000000` | `--color-pure-black` | Used rarely for specific icon fills or subtle accents, creating a deeper contrast point. |
| Fog Gray | `#cfcdcd` | `--color-fog-gray` | Subtle background shifts, potentially for secondary content areas or dividers, creating minimal visual separation. |

## Tokens — Typography

### Basis — Primary typeface for all general content, links, navigation, and most headlines. Its robustness at various weights supports the overall bold typographic hierarchy. Negative letter spacing at larger sizes tightens the forms for maximum visual impact. · `--font-basis`
- **Substitute:** system-ui
- **Weights:** 400, 500, 700
- **Sizes:** 10px, 12px, 15px, 16px, 32px, 40px, 120px, 160px, 640px
- **Line height:** 0.80, 0.82, 0.90, 1.00, 1.20, 1.30, 2.00
- **Letter spacing:** -0.06
- **Role:** Primary typeface for all general content, links, navigation, and most headlines. Its robustness at various weights supports the overall bold typographic hierarchy. Negative letter spacing at larger sizes tightens the forms for maximum visual impact.

### Messina Sans — Exclusive typeface for the largest hero headlines and main branding elements. Its extreme scale and tight kerning, combined with custom character integrations, define the brand's distinctive, artistic, and almost sculptural typographic presence. · `--font-messina-sans`
- **Substitute:** Helvetica Neue
- **Weights:** 500
- **Sizes:** 240px
- **Line height:** 1.00
- **Letter spacing:** -0.08, -0.06
- **Role:** Exclusive typeface for the largest hero headlines and main branding elements. Its extreme scale and tight kerning, combined with custom character integrations, define the brand's distinctive, artistic, and almost sculptural typographic presence.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.2 | — | `--text-caption` |
| body | 15px | 1.2 | — | `--text-body` |
| subheading | 32px | 1 | — | `--text-subheading` |
| heading-sm | 40px | 0.9 | — | `--text-heading-sm` |
| heading | 120px | 0.82 | -0.72px | `--text-heading` |
| display | 240px | 1 | -19.2px | `--text-display` |
| heading-lg | 640px | 0.8 | -38.4px | `--text-heading-lg` |

## Tokens — Spacing & Shapes

**Base unit:** 8px

**Density:** spacious

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 16 | 16px | `--spacing-16` |
| 40 | 40px | `--spacing-40` |
| 80 | 80px | `--spacing-80` |
| 160 | 160px | `--spacing-160` |
| 240 | 240px | `--spacing-240` |

### Border Radius

| Element | Value |
|---------|-------|
| accent | 70px |
| default | 0px |

### Layout

- **Section gap:** 160px
- **Card padding:** 40px
- **Element gap:** 16px

## Components

### Header Navigation Link
**Role:** Interactive element

Text link with Anchor Black (#262523) color, Basis font, weight 400, size 16px. No border or background, relying on context for interactive distinction.

### Hero Headline
**Role:** Prominent heading

Uses Messina Sans, weight 500, size 640px for the largest display, and 240px for slightly smaller. Color Anchor Black (#262523), line-height 0.8, letter-spacing -0.08em (for 240px) and -0.06em (for 640px). Integrates custom graphic elements within letterforms.

### Body Text
**Role:** Standard content

Basis font, weight 400, size 15px, color Anchor Black (#262523). Minimal line-height (1.2) for dense informational delivery.

### Information Link
**Role:** Secondary interactive element

Basis font, weight 400, size 16px, color Anchor Black (#262523). Explicitly includes the default browser blue link color for `SEE WHATS NEXT`.

### Logo
**Role:** Brand identity

Elva logo uses Anchor Black (#262523) and Basis font for the tagline 'A Third And Grove Company'.

## Do's and Don'ts

### Do
- Prioritize Messina Sans for all visual-hero level typography, at sizes above 240px with a line-height of 0.80 and letter-spacing of -0.0600em.
- Maintain a strict monochrome palette using Anchor Black (#262523) for text and Gallery White (#ececec) for backgrounds as primary colors.
- Use Basis font with negative letter spacing (e.g., -0.0600em for 120px) to enhance the condensed, impactful look of large headlines.
- Leverage the 160px sectionGap to create significant breathing room between major content blocks, emphasizing spaciousness.
- Integrate playful iconography or graphic elements directly into large text headlines rather than as standalone images, as seen with the heart and asterisk.
- Apply Anchor Black (#262523) for all interactive text elements to ensure a consistent focal point for action.

### Don't
- Avoid introducing any saturated chromatic colors; the system relies purely on a grayscale palette with minor shifts.
- Do not use box-shadows or complex elevation effects; depth is created through scale and typographic hierarchy.
- Do not use default system font styles for any textual content; all type must conform to Basis or Messina Sans rules.
- Avoid generic imagery like stock photos; if visuals are needed, they should be integrated graphically with typography.
- Do not use small, secondary buttons or badges that break the overall bold, oversized aesthetic.
- Do not introduce border-radius values other than 0px, except for intentional graphic elements like the 70px rounded shape in the headline.

## Imagery

The visual language is dominantly typographic, with imagery integrated directly into or replacing parts of large headlines. For example, the heart and asterisk symbols act as visual substitutions within key phrases. There are no traditional photographs, illustrations, or product shots. The treatment is sharp and graphic, with no rounded corners or masking on any visual elements observed. The role of these integrated graphics is purely decorative and atmospheric, enhancing the 'memorable experiences' concept without literal representation. The density is image-light, text-dominant, with visual weight coming from typography itself.

## Layout

The page model is full-bleed, but content appears visually contained by generous margins from the edge. The hero section is characterized by a full-viewport, centered, and dramatically oversized headline, serving as the primary visual and content focus. There's no immediately apparent section rhythm beyond large vertical spacing created by the `sectionGap`. Content arrangement is primarily centered or implicitly balanced around large typographic blocks. There is no visible grid for cards or features, suggesting a more free-form, editorial approach. The layout is extremely spacious with ample `sectionGap` (160px) and `elementGap` (16px), creating significant whitespace. Navigation is minimal, consisting of a top-right header with text links and contact info, likely a fixed or sticky element due to its separation from the main content. The main navigation is a simple list of text links 'WORK', 'COMPANY', 'CAPABILITIES', 'CONTACT'.

## Agent Prompt Guide

### Quick Color Reference
- Text: #262523 (Anchor Black)
- Background: #ececec (Gallery White)
- Navigation Links: #262523 (Anchor Black)
- Secondary Background: #cfcdcd (Fog Gray)

### 3-5 Example Component Prompts
1. Create a hero section: background #ececec. Headline 'WE CREATE' using Messina Sans, weight 500, size 640px, line-height 0.8, color #262523. Below, 'MEMORABLE EXPERIENCES' with an SVG heart instead of 'O' and an SVG asterisk substituting 'X', Messina Sans, weight 500, size 640px, line-height 0.8, color #262523. Ensure a 160px margin-bottom for the section.
2. Create a navigation bar: top-right corner. Links 'WORK', 'COMPANY', 'CAPABILITIES', 'CONTACT' using Basis font, weight 400, size 16px, color #262523. 'INFO@HELLOELVA.COM' link uses same styles. All links are spaced with a 40px padding-right.
3. Create a body text block: A simple paragraph of 'Elva is now part of Third and Grove! SEE WHATS NEXT' with 'SEE WHATS NEXT' as a link. Paragraph text (excluding link) uses Basis font, weight 400, size 15px, line-height 1.2, color #262523. The link 'SEE WHATS NEXT' uses Basis font, weight 400, size 16px, color #262523.
4. Design a 'HELLO' badge: Text 'HELLO' using Basis font, weight 400, size 16px, color #262523, no background or padding to maintain an ephemeral feel.

## Similar Brands

- **Huge Inc.** — Uses large, impactful typography and a refined, stark aesthetic for a high-end agency feel.
- **Pentagram** — Employs strong graphic design principles and custom typography to define its creative identity.
- **Work & Co** — Features a clean, content-focused layout with a strong emphasis on typography and white space.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-anchor-black: #262523;
  --color-gallery-white: #ececec;
  --color-pure-black: #000000;
  --color-fog-gray: #cfcdcd;

  /* Typography — Font Families */
  --font-basis: 'Basis', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-messina-sans: 'Messina Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.2;
  --text-body: 15px;
  --leading-body: 1.2;
  --text-subheading: 32px;
  --leading-subheading: 1;
  --text-heading-sm: 40px;
  --leading-heading-sm: 0.9;
  --text-heading: 120px;
  --leading-heading: 0.82;
  --tracking-heading: -0.72px;
  --text-display: 240px;
  --leading-display: 1;
  --tracking-display: -19.2px;
  --text-heading-lg: 640px;
  --leading-heading-lg: 0.8;
  --tracking-heading-lg: -38.4px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-16: 16px;
  --spacing-40: 40px;
  --spacing-80: 80px;
  --spacing-160: 160px;
  --spacing-240: 240px;

  /* Layout */
  --section-gap: 160px;
  --card-padding: 40px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-lg: 10px;
  --radius-full: 70px;

  /* Named Radii */
  --radius-accent: 70px;
  --radius-default: 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-anchor-black: #262523;
  --color-gallery-white: #ececec;
  --color-pure-black: #000000;
  --color-fog-gray: #cfcdcd;

  /* Typography */
  --font-basis: 'Basis', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-messina-sans: 'Messina Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.2;
  --text-body: 15px;
  --leading-body: 1.2;
  --text-subheading: 32px;
  --leading-subheading: 1;
  --text-heading-sm: 40px;
  --leading-heading-sm: 0.9;
  --text-heading: 120px;
  --leading-heading: 0.82;
  --tracking-heading: -0.72px;
  --text-display: 240px;
  --leading-display: 1;
  --tracking-display: -19.2px;
  --text-heading-lg: 640px;
  --leading-heading-lg: 0.8;
  --tracking-heading-lg: -38.4px;

  /* Spacing */
  --spacing-16: 16px;
  --spacing-40: 40px;
  --spacing-80: 80px;
  --spacing-160: 160px;
  --spacing-240: 240px;

  /* Border Radius */
  --radius-lg: 10px;
  --radius-full: 70px;
}
```

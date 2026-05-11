# DNA — Style Reference
> Midnight data stream, whispered authority

**Theme:** dark

DNA Capital employs a sophisticated, near-monochromatic dark theme, evoking a premium, data-driven identity. Typography is central, using a blend of refined serifs for impactful headlines and clean sans-serifs for legibility. A single vivid violet-blue gradient acts as a signature highlight, reserved for subtle decorative elements, icons, and progress indicators, creating a sense of precision and advanced technology. The overall design emphasizes spaciousness and understated confidence, with minimal use of borders and elevation to maintain a flat, contemporary feel.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#070708` | `--color-midnight-ink` | Page and primary surface backgrounds, deep contrasts, footer background |
| Arctic Mist | `#ffffff` | `--color-arctic-mist` | Primary text, prominent headings, borders (especially focus states or subtle dividers), icon fills |
| Ghost Gray | `#8f8f93` | `--color-ghost-gray` | Secondary text, muted helper text, subtle decorative borders, placeholder text |
| Deep Space Blue | `linear-gradient(135deg, rgb(0, 204, 255), rgb(12, 146, 246) 43%, rgb(25, 84, 236) 75%, rgb(25, 84, 236))` | `--color-deep-space-blue` | Violet wash for highlight backgrounds, decorative bands, and soft emphasis behind content. Do not promote it to the primary CTA color; Accent gradient used for abstract backgrounds and subtle indicators, providing an ethereal, technological feeling |
| Fading Nebula Gradient | `linear-gradient(143deg, rgb(66, 54, 118), rgba(38, 177, 245, 0) 88%)` | `--color-fading-nebula-gradient` | Subtle background gradient for contextual sections, providing depth without distracting from content |

## Tokens — Typography

### Darius — Dominant headlines and impactful display text. The single light weight (300) conveys authority through a refined, almost whispered presence, rather than bold shouting. Its serif quality adds a touch of classic sophistication. · `--font-darius`
- **Substitute:** Playfair Display
- **Weights:** 300
- **Sizes:** 45px, 52px, 54px, 72px
- **Line height:** 1.13, 1.34
- **Letter spacing:** normal
- **Role:** Dominant headlines and impactful display text. The single light weight (300) conveys authority through a refined, almost whispered presence, rather than bold shouting. Its serif quality adds a touch of classic sophistication.

### Graphik — Primary body text, navigation links, and smaller headings. Its neutrality ensures legibility on dark backgrounds, while varied weights provide clear hierarchy without relying on strong color contrasts. Consistent use of tabular numbers ('tnum') for data ensures alignment and visual precision. · `--font-graphik`
- **Substitute:** Inter
- **Weights:** 200, 300, 400, 500
- **Sizes:** 9px, 10px, 13px, 14px, 15px, 18px, 59px
- **Line height:** 0.90, 1.00, 1.20, 1.40, 1.50, 1.55, 1.80
- **Letter spacing:** -0.0200em at 59px, 0.0100em at 18px, 0.1800em at 14px, 0.2000em at 13px, 0.4000em at 9px
- **OpenType features:** `"tnum"`
- **Role:** Primary body text, navigation links, and smaller headings. Its neutrality ensures legibility on dark backgrounds, while varied weights provide clear hierarchy without relying on strong color contrasts. Consistent use of tabular numbers ('tnum') for data ensures alignment and visual precision.

### Arial — Utility text, small buttons, and system-level annotations where high compatibility and basic legibility are paramount. · `--font-arial`
- **Substitute:** Helvetica Neue
- **Weights:** 400, 500
- **Sizes:** 13px
- **Line height:** 1.20
- **Letter spacing:** normal
- **Role:** Utility text, small buttons, and system-level annotations where high compatibility and basic legibility are paramount.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| subheading | 18px | 1.5 | 0.0018px | `--text-subheading` |
| heading | 45px | 1.13 | — | `--text-heading` |
| heading-lg | 52px | 1.13 | — | `--text-heading-lg` |
| display | 72px | 1.13 | — | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** spacious

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 8 | 8px | `--spacing-8` |
| 9 | 9px | `--spacing-9` |
| 20 | 20px | `--spacing-20` |
| 23 | 23px | `--spacing-23` |
| 25 | 25px | `--spacing-25` |
| 27 | 27px | `--spacing-27` |
| 32 | 32px | `--spacing-32` |
| 39 | 39px | `--spacing-39` |
| 59 | 59px | `--spacing-59` |
| 63 | 63px | `--spacing-63` |
| 99 | 99px | `--spacing-99` |
| 119 | 119px | `--spacing-119` |
| 171 | 171px | `--spacing-171` |
| 238 | 238px | `--spacing-238` |

### Border Radius

| Element | Value |
|---------|-------|
| links | 4px |

### Layout

- **Section gap:** 59px
- **Card padding:** 23px
- **Element gap:** 23px

## Components

### Ghost Button
**Role:** Minimal interactive button for secondary actions or navigation.

Text color is #000000 on a transparent background. No padding is specified in the variant data, suggesting inline text treatment. This component's use of black text against a transparent background indicates it's designed for use on light surfaces or as part of an inverted color scheme within sections.

### Icon Button (Menu)
**Role:** Navigation toggle or action with a minimalist icon.

Invisible background, with a #000000 color for the icon. Minimal padding (0px) for a tight, unobtrusive UI element. Designed to be discreet until interacted with, reflecting a clean aesthetic.

### Text Link with Underline
**Role:** Inline navigation or reference links.

Text in Graphite at 13px, Graphik font family, 400 weight, with 20px padding-bottom that suggests a bottom border or underline. A 4px border-radius is associated with links via the raw data, implying subtle rounding if a background or border were present.

### Scroll Indicator Button
**Role:** Visual cue for page progression.

Text in #000000 (likely for a light context as a button variant, or could indicate a ghost button where text shows through). This button is specifically 'Scroll to explore', suggesting a functional navigation prompt.

### Small Badge
**Role:** Informational marker or tag.

Transparent background with #ffffff text. Zero border radius and padding, indicating a tight, text-only badge that integrates seamlessly with content without drawing excessive attention.

## Do's and Don'ts

### Do
- Prioritize text hierarchy with Darius for headlines and Graphik for body, strictly adhering to their defined weights and letter spacing: Darius 300 for display, Graphik varying weights for functional text.
- Utilize Midnight Ink (#070708) as the primary background and Arctic Mist (#ffffff) for primary text for dominant contrast, ensuring high readability on dark surfaces.
- Employ Deep Space Blue (#1954ec) exclusively for brand accents, subtle decorative strokes, and abstract background elements, maintaining its role as a precise, tech-forward highlight.
- Maintain generous vertical spacing between sections, using a default of 59px to promote a spacious and unhurried reading experience.
- Implement small rounding of 4px radius only on interactive link elements, keeping other UI components with sharp, defined corners.
- Reserve background gradients (Cosmic Blue to Violet or Fading Nebula) for abstract hero sections or subtle content blocks to add depth and a technological atmosphere, linking them to key content.
- Use Ghost Gray (#8f8f93) for secondary informational text or subtle inactive states to reduce visual clutter and direct focus to primary content.

### Don't
- Avoid using highly saturated colors outside the defined brand accent (Deep Space Blue) to ensure the dark, sophisticated aesthetic is preserved.
- Do not introduce strong drop shadows or heavy borders on UI components; maintain a largely flat and modern appearance.
- Do not use Darius for body text or excessively small sizes; its light weight and serif nature are intended for impact and larger displays.
- Avoid tight element spacing; maintain an element gap of 23px and section gap of 59px to ensure content breathability.
- Do not use Arctic Mist (#ffffff) as a general background color, as the system is anchored in a dark theme.
- Do not introduce unnecessary rounded corners. Radii should be limited to 4px for specific interactive elements.
- Avoid generic system fonts where Graphik or Darius are specified; substitutes should only be used if the custom fonts are unavailable, to maintain brand distinctiveness.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Midnight Ink Canvas | `#070708` | Primary page background, foundation for all content. |
| 1 | Arctic Mist Card Surface | `#ffffff` | Used sparingly for content cards or highlighted information blocks where a light surface is contextually necessary, providing stark contrast against the dark background. Evidenced as a background color for textual content areas. |

## Imagery

This site features abstract, glowing particulate wave formations, primarily in deep blues and purples, acting as atmospheric backgrounds rather than explicit content. These are likely 3D renders or sophisticated abstract graphics. The treatment is full-bleed, integrating seamlessly with the dark canvas to create a futuristic and data-driven mood. There is minimal use of photography or traditional illustrations, with the focus remaining on clean typography and abstract visual effects. Icons, where present, appear to be outlined and monochromatic, maintaining a minimalist stroke weight.

## Layout

The page primarily uses a full-bleed layout, where background elements extend to the viewport edges, particularly in the hero and key section headers. Max-width content containers are implicitly present for text and core information, centering these blocks within the full-bleed background. The hero section prominently features a centered, large headline over an abstract gradient background. Section rhythm is driven by consistent vertical spacing (sectionGap of 59px), creating clear divisions between content blocks which alternate between a large headline and a two-column text layout. Content often follows a centered stack or a staggered text-left/text-right pattern for explanatory sections. Navigation is a minimalist top bar with a 'Menu' toggle on the right.

## Agent Prompt Guide

Quick Color Reference:
text: #ffffff
background: #070708
border: #ffffff
accent: #1954ec
primary action: no distinct CTA color

Example Component Prompts:
1. Create a Hero Section: Background is Cosmic Blue to Violet Gradient. Headline reads 'Innovation in healthtech' using Darius, size 72px, weight 300, color Arctic Mist. Subtext below it reads 'Advancing medical frontiers' using Graphik, size 18px, weight 400, color Ghost Gray. Ensure generous sectionGap of 59px above and below.
2. Design a Feature Block: Midnight Ink background. Headline 'Our Expertise' using Graphik, size 59px, weight 500, color Arctic Mist, letter-spacing -0.0200em. Below it, a two-column layout with text in Ghost Gray, size 14px, Graphik, weight 400. Each text block has 23px elementGap from the next.
3. Build a Navigation Link: Text 'About Us' using Graphik, size 13px, weight 400, color Arctic Mist, no letter-spacing adjustment. Apply a 4px border-radius if a background is present, otherwise keep it as text with a transparent background.
4. Create a Subtle Badge: Text 'New' using Graphik, size 9px, weight 200, color Arctic Mist, letter-spacing 0.4000em. Background is transparent with no padding or border-radius.

## Similar Brands

- **Linear** — Dark UI with subtle accent colors, strong typographic hierarchy, and an emphasis on clean, spacious layouts.
- **Anthropic** — Sophisticated dark theme, elegant serif typography for headlines, and a focus on abstract, atmospheric background visuals.
- **Stripe (dark mode)** — Premium dark aesthetic, fine-grained control over typography, and subtle, functional use of color for interactive elements.
- **Vercel** — Minimalist dark interface, focus on content presentation through considered spacing and a dominant sans-serif typeface, with restrained use of graphical accents.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #070708;
  --color-arctic-mist: #ffffff;
  --color-ghost-gray: #8f8f93;
  --color-deep-space-blue: #1954ec;
  --gradient-deep-space-blue: linear-gradient(135deg, rgb(0, 204, 255), rgb(12, 146, 246) 43%, rgb(25, 84, 236) 75%, rgb(25, 84, 236));
  --color-fading-nebula-gradient: #423676;
  --gradient-fading-nebula-gradient: linear-gradient(143deg, rgb(66, 54, 118), rgba(38, 177, 245, 0) 88%);

  /* Typography — Font Families */
  --font-darius: 'Darius', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-graphik: 'Graphik', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-subheading: 18px;
  --leading-subheading: 1.5;
  --tracking-subheading: 0.0018px;
  --text-heading: 45px;
  --leading-heading: 1.13;
  --text-heading-lg: 52px;
  --leading-heading-lg: 1.13;
  --text-display: 72px;
  --leading-display: 1.13;

  /* Typography — Weights */
  --font-weight-extralight: 200;
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-8: 8px;
  --spacing-9: 9px;
  --spacing-20: 20px;
  --spacing-23: 23px;
  --spacing-25: 25px;
  --spacing-27: 27px;
  --spacing-32: 32px;
  --spacing-39: 39px;
  --spacing-59: 59px;
  --spacing-63: 63px;
  --spacing-99: 99px;
  --spacing-119: 119px;
  --spacing-171: 171px;
  --spacing-238: 238px;

  /* Layout */
  --section-gap: 59px;
  --card-padding: 23px;
  --element-gap: 23px;

  /* Border Radius */
  --radius-md: 4px;

  /* Named Radii */
  --radius-links: 4px;

  /* Surfaces */
  --surface-midnight-ink-canvas: #070708;
  --surface-arctic-mist-card-surface: #ffffff;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #070708;
  --color-arctic-mist: #ffffff;
  --color-ghost-gray: #8f8f93;
  --color-deep-space-blue: #1954ec;
  --color-fading-nebula-gradient: #423676;

  /* Typography */
  --font-darius: 'Darius', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-graphik: 'Graphik', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-subheading: 18px;
  --leading-subheading: 1.5;
  --tracking-subheading: 0.0018px;
  --text-heading: 45px;
  --leading-heading: 1.13;
  --text-heading-lg: 52px;
  --leading-heading-lg: 1.13;
  --text-display: 72px;
  --leading-display: 1.13;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-9: 9px;
  --spacing-20: 20px;
  --spacing-23: 23px;
  --spacing-25: 25px;
  --spacing-27: 27px;
  --spacing-32: 32px;
  --spacing-39: 39px;
  --spacing-59: 59px;
  --spacing-63: 63px;
  --spacing-99: 99px;
  --spacing-119: 119px;
  --spacing-171: 171px;
  --spacing-238: 238px;

  /* Border Radius */
  --radius-md: 4px;
}
```

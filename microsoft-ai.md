# Microsoft AI — Style Reference
> Warm academic parchment

**Theme:** mixed

This design evokes a sense of antique academic rigor meeting soft, optimistic warmth. The primary color palette transitions from deep black to creamy off-white with occasional muted pastel gradients, creating distinct atmospheric shifts. Delicate humanist typography in Bradford LL, characterized by its fine serifs and generous letter-spacing for large headlines, gives an authoritative yet approachable feel. Conversely, more utilitarian Red Hat Mono maintains informational clarity on smaller elements. Strong visual personality arises from the interplay of a classic serif font for display with a modern, technical mono font for UI elements, all grounded by expansive spacing and subtly rounded, organic shapes.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Estate | `#000000` | `--color-midnight-estate` | Hero background, dark sections – a deep, almost velvet black that serves as a high-contrast canvas for header text. |
| Greated Parchment | `#fef9ed` | `--color-greated-parchment` | Page background, light sections, card surfaces – a warm, creamy off-white providing soft contrast with text. |
| Faded Linen | `#f5f0e4` | `--color-faded-linen` | Secondary background, badges – a slightly cooler off-white, offering subtle differentiation from the main background. |
| Warm Clay | `#5d524b` | `--color-warm-clay` | Primary text, borders, icons, input text – a brownish-gray that suggests an earthy, natural tone. |
| Dusty Rose Gradient | `linear-gradient(rgb(251, 211, 190) 50%, rgb(254, 249, 237) 100%)` | `--color-dusty-rose-gradient` | Section backgrounds, creating a soft, inviting transition between content blocks. |
| Sunset Glaze Gradient | `linear-gradient(to right bottom, rgb(231, 177, 145), rgb(238, 207, 144))` | `--color-sunset-glaze-gradient` | Decorative elements, subtle background accents, adding a warm, almost edible visual texture. |
| Worn Velvet | `#8c5462` | `--color-worn-velvet` | Background for specific content blocks, providing a muted, sophisticated accent. |
| Forest Shade | `#2e4d4d` | `--color-forest-shade` | Background for specific content blocks, offering a deep, natural contrast. |
| Antique Brass | `#a67c52` | `--color-antique-brass` | Subtle accent for icons or minor decorative elements, evoking vintage quality. |
| Cerulean Link | `#0066ff` | `--color-cerulean-link` | Interactive element highlights, used sparingly for specific icons, creating a vivid point of interest against the subdued palette. |

## Tokens — Typography

### Bradford LL — Display headlines and sub-headlines, body text in larger contexts (like hero sections). The fine serifs and dramatic letter-spacing at large sizes create an elegant, almost calligraphic presence, lending an air of intellectual authority without being austere. · `--font-bradford-ll`
- **Substitute:** Playfair Display
- **Weights:** 400, 450
- **Sizes:** 15px, 20px, 25px, 35px, 40px, 45px, 100px, 125px
- **Line height:** 1.00, 1.13, 1.20, 1.25, 1.40
- **Letter spacing:** -0.0400em, -0.0300em, -0.0200em, -0.0130em, -0.0100em
- **OpenType features:** `"kern"`
- **Role:** Display headlines and sub-headlines, body text in larger contexts (like hero sections). The fine serifs and dramatic letter-spacing at large sizes create an elegant, almost calligraphic presence, lending an air of intellectual authority without being austere.

### Red Hat Mono — Functional text: inputs, buttons, badges, navigation, and detailed body copy. Its monospaced nature provides clear, unambiguous readability for data and interactive labels, contrasting with the humanist headings. · `--font-red-hat-mono`
- **Substitute:** IBM Plex Mono
- **Weights:** 400, 450, 500
- **Sizes:** 12px, 13px, 15px, 20px
- **Line height:** 1.00, 1.20, 1.25, 1.60
- **Letter spacing:** -0.0170em, -0.0150em, -0.0130em, -0.0100em, 0.0500em, 0.1000em
- **OpenType features:** `"kern"`
- **Role:** Functional text: inputs, buttons, badges, navigation, and detailed body copy. Its monospaced nature provides clear, unambiguous readability for data and interactive labels, contrasting with the humanist headings.

### MWF-MDL2 — System icons for search and accessibility. This provides consistent, clear iconography aligned with Microsoft's design language for functional elements. · `--font-mwf-mdl2`
- **Substitute:** Segoe MDL2 Assets
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.25
- **Letter spacing:** -0.0130em
- **OpenType features:** `"kern"`
- **Role:** System icons for search and accessibility. This provides consistent, clear iconography aligned with Microsoft's design language for functional elements.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.6 | 0.6px | `--text-caption` |
| body | 15px | 1.6 | -0.21px | `--text-body` |
| subheading | 20px | 1.4 | -0.26px | `--text-subheading` |
| heading | 25px | 1.25 | -0.32px | `--text-heading` |
| heading-lg | 35px | 1.25 | -0.7px | `--text-heading-lg` |
| display | 100px | 1 | -4px | `--text-display` |
| display-lg | 125px | 1 | -5px | `--text-display-lg` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 5 | 5px | `--spacing-5` |
| 7 | 7px | `--spacing-7` |
| 8 | 8px | `--spacing-8` |
| 9 | 9px | `--spacing-9` |
| 10 | 10px | `--spacing-10` |
| 13 | 13px | `--spacing-13` |
| 17 | 17px | `--spacing-17` |
| 20 | 20px | `--spacing-20` |
| 22 | 22px | `--spacing-22` |
| 23 | 23px | `--spacing-23` |
| 25 | 25px | `--spacing-25` |
| 41 | 41px | `--spacing-41` |
| 42 | 42px | `--spacing-42` |
| 47 | 47px | `--spacing-47` |
| 50 | 50px | `--spacing-50` |
| 58 | 58px | `--spacing-58` |

### Border Radius

| Element | Value |
|---------|-------|
| lg | 6.66667px |
| md | 4.16667px |
| sm | 2.5px |
| pills | 65px |
| images | 25px |
| inputs | 50px |
| buttons | 85.8333px |

### Layout

- **Section gap:** 48-80px
- **Card padding:** 17px
- **Element gap:** 8-20px

## Components

### Primary Navigation Link
**Role:** Main site navigation

Bradford LL, weight 400, size 15px, color Warm Clay (#5d524b). No explicit padding or background, using natural text spacing.

### Pill Search Input
**Role:** Global search functionality

Monospaced Red Hat Mono text at 15px, Warm Clay (#5d524b). Background is transparent, with a 50px border-radius, border-color Warm Clay (#5d524b).

### Hero Headline
**Role:** Primary heading for the hero section

Bradford LL, weight 450, sizes 100px or 125px with line-height 1.0 and significant negative letter-spacing (-4.0px or -5.0px). Color is Greated Parchment (#fef9ed) against Midnight Estate (#000000) background.

### Text Only Button
**Role:** Interactive elements with minimal visual weight

Background transparent, text Warm Clay (#5d524b), border-top Warm Clay (#5d524b), border-radius 85.8333px. No padding, relying on surrounding layout for spacing.

### Filled Pill Button
**Role:** Interactive elements with a subtle background

Background Greated Parchment (#fef9ed), text Warm Clay (#5d524b), border-color Warm Clay (#5d524b), border-radius 85.8333px. No explicit padding.

### Product Category Badge
**Role:** Categorization of content or products

Background Faded Linen (#f5f0e4), text Warm Clay (#5d524b), border-radius 2.5px. Padding 3.33333px vertical, 16.6667px horizontal. Uses Red Hat Mono for clarity.

### Accessibility Toggle
**Role:** UI control for accessibility mode

Small toggle with 'Off' and 'Accessibility Mode' text. Uses Red Hat Mono, color Warm Clay (#5d524b), likely against a Greated Parchment (#fef9ed) or Faded Linen (#f5f0e4) background.

## Do's and Don'ts

### Do
- Prioritize Bradford LL (Playfair Display) for all headlines and impactful textual displays, using its 450 weight and generous letter-spacing for elegance.
- Use Red Hat Mono (IBM Plex Mono) exclusively for all functional text: buttons, navigation, inputs, and supplementary information at weights 400-500.
- Apply rounded corners consistently: 85.8333px for interactive pill-shaped buttons, 50px for form inputs, and 2.5px for small badges for a warm, organic feel.
- Utilize Greated Parchment (#fef9ed) as the primary light background and Midnight Estate (#000000) for high-contrast hero sections.
- For text on light backgrounds, always use Warm Clay (#5d524b) to maintain a soft, readable contrast (contrast ratio 7.2:1).
- Employ the Dusty Rose Gradient (linear-gradient(rgb(251, 211, 190) 50%, rgb(254, 249, 237) 100%)) as a subtle, inviting background element for content sections.
- Maintain comfortable element spacing with an elementGap of '8-20px' and a base unit of 4px for all padding and margins.

### Don't
- Avoid using highly saturated, vibrant colors outside of the specified accent colors, to preserve the system's muted, academic aesthetic.
- Do not use generic system fonts for body text or headlines; adhere strictly to Bradford LL (Playfair Display) and Red Hat Mono (IBM Plex Mono) for brand consistency.
- Refrain from sharp, angular corners on UI elements exceeding a 12px radius, as this contradicts the softer, organic shape language.
- Do not introduce heavy drop shadows or aggressive elevation; the system relies on color and spacing for depth.
- Avoid tight line heights or negative letter-spacing on body text to ensure readability, especially with the serif font.
- Do not use Warm Clay (#5d524b) as a background color, it's reserved for text and borders to maintain its visual role as detail.
- Never combine Bradford LL with Red Hat Mono within the same short phrase or button label; maintain clear separation of their roles.

## Elevation

The design intentionally avoids aggressive or deep shadows. Where elevation is present, it is implicitly achieved through distinct background color shifts (e.g., Midnight Estate to Greated Parchment sections) and the use of very subtle, near-achromatic box-shadows like #cec7bc, suggesting a material presence without heavy visual lifting.

## Agent Prompt Guide

### Quick Color Reference
- Text: Warm Clay (#5d524b)
- Page Background: Greated Parchment (#fef9ed)
- Hero Background: Midnight Estate (#000000)
- Accent Gradient: Dusty Rose Gradient (linear-gradient(rgb(251, 211, 190) 50%, rgb(254, 249, 237) 100%))
- Button Fill: Greated Parchment (#fef9ed)
- Button Border/Text: Warm Clay (#5d524b)

### 3-5 Example Component Prompts
1. Create a hero section: Midnight Estate (#000000) background. Main headline 'Humanist Superintelligence' (Bradford LL weight 450, 125px size, 1.0 lineHeight, -5.0px letter-spacing, Greated Parchment #fef9ed). Subtext 'Responsible AI to empower humanity' (Red Hat Mono weight 400, 20px size, 1.6 lineHeight, -0.26px letter-spacing, Greated Parchment #fef9ed).
2. Generate a product category badge: Faded Linen (#f5f0e4) background, Warm Clay (#5d524b) text 'Copilot' (Red Hat Mono weight 400, 15px size), border-radius 2.5px, padding 3.33333px vertical, 16.6667px horizontal.
3. Design a pill-shaped search input field: 50px border-radius, Warm Clay (#5d524b) border and placeholder text ('Search') (Red Hat Mono weight 400, 15px size), transparent background. Include a MWF-MDL2 icon for the search symbol.
4. Build an introductory text block: Background is Dusty Rose Gradient. Heading 'At MAI, we’re building...' (Bradford LL weight 400, 35px size, 1.25 lineHeight, -0.7px letter-spacing, Warm Clay #5d524b). Body text 'We are building the world's most capable AI systems...' (Bradford LL weight 400, 20px size, 1.4 lineHeight, -0.39px letter-spacing, Warm Clay #5d524b).
5. Create a text-only navigation item: 'Playground' link text (Bradford LL weight 400, 15px size, 1.4 lineHeight, Warm Clay #5d524b). On hover, change text color to Cerulean Link (#0066ff).

## Similar Brands

- **The Browser Company (Arc Browser)** — Shares a similar blend of organic shapes (rounded corners for UI elements like buttons/tabs), sophisticated typography choices that mix serifs and technical fonts, and generally soft, inviting color palettes.
- **Anthropic** — Exhibits a comparable academic and thoughtful aesthetic, often utilizing generous spacing, reserved color palettes, and elegant typography to convey a sense of serious, impactful work.
- **Stripe (older versions)** — Early Stripe designs had a similar focus on precise, readable typography (often mixing font styles), clean layouts, and a sophisticated, slightly muted color scheme, prioritizing clarity and subtle elegance over overt branding.
- **Apple (editorial sections)** — Some editorial-heavy sections of Apple's website (e.g., design resources) use large, impactful serif headlines with generous spacing, combined with clean body text, giving a high-end, academic feel.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-estate: #000000;
  --color-greated-parchment: #fef9ed;
  --color-faded-linen: #f5f0e4;
  --color-warm-clay: #5d524b;
  --color-dusty-rose-gradient: #fbd3be;
  --gradient-dusty-rose-gradient: linear-gradient(rgb(251, 211, 190) 50%, rgb(254, 249, 237) 100%);
  --color-sunset-glaze-gradient: #e7b191;
  --gradient-sunset-glaze-gradient: linear-gradient(to right bottom, rgb(231, 177, 145), rgb(238, 207, 144));
  --color-worn-velvet: #8c5462;
  --color-forest-shade: #2e4d4d;
  --color-antique-brass: #a67c52;
  --color-cerulean-link: #0066ff;

  /* Typography — Font Families */
  --font-bradford-ll: 'Bradford LL', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-red-hat-mono: 'Red Hat Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-mwf-mdl2: 'MWF-MDL2', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.6;
  --tracking-caption: 0.6px;
  --text-body: 15px;
  --leading-body: 1.6;
  --tracking-body: -0.21px;
  --text-subheading: 20px;
  --leading-subheading: 1.4;
  --tracking-subheading: -0.26px;
  --text-heading: 25px;
  --leading-heading: 1.25;
  --tracking-heading: -0.32px;
  --text-heading-lg: 35px;
  --leading-heading-lg: 1.25;
  --tracking-heading-lg: -0.7px;
  --text-display: 100px;
  --leading-display: 1;
  --tracking-display: -4px;
  --text-display-lg: 125px;
  --leading-display-lg: 1;
  --tracking-display-lg: -5px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-w450: 450;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-5: 5px;
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-9: 9px;
  --spacing-10: 10px;
  --spacing-13: 13px;
  --spacing-17: 17px;
  --spacing-20: 20px;
  --spacing-22: 22px;
  --spacing-23: 23px;
  --spacing-25: 25px;
  --spacing-41: 41px;
  --spacing-42: 42px;
  --spacing-47: 47px;
  --spacing-50: 50px;
  --spacing-58: 58px;

  /* Layout */
  --section-gap: 48-80px;
  --card-padding: 17px;
  --element-gap: 8-20px;

  /* Border Radius */
  --radius-md: 4.16667px;
  --radius-md-2: 6.66667px;
  --radius-3xl: 25px;
  --radius-full: 50px;
  --radius-full-2: 65px;
  --radius-full-3: 85.8333px;

  /* Named Radii */
  --radius-lg: 6.66667px;
  --radius-md: 4.16667px;
  --radius-sm: 2.5px;
  --radius-pills: 65px;
  --radius-images: 25px;
  --radius-inputs: 50px;
  --radius-buttons: 85.8333px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-estate: #000000;
  --color-greated-parchment: #fef9ed;
  --color-faded-linen: #f5f0e4;
  --color-warm-clay: #5d524b;
  --color-dusty-rose-gradient: #fbd3be;
  --color-sunset-glaze-gradient: #e7b191;
  --color-worn-velvet: #8c5462;
  --color-forest-shade: #2e4d4d;
  --color-antique-brass: #a67c52;
  --color-cerulean-link: #0066ff;

  /* Typography */
  --font-bradford-ll: 'Bradford LL', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-red-hat-mono: 'Red Hat Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-mwf-mdl2: 'MWF-MDL2', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.6;
  --tracking-caption: 0.6px;
  --text-body: 15px;
  --leading-body: 1.6;
  --tracking-body: -0.21px;
  --text-subheading: 20px;
  --leading-subheading: 1.4;
  --tracking-subheading: -0.26px;
  --text-heading: 25px;
  --leading-heading: 1.25;
  --tracking-heading: -0.32px;
  --text-heading-lg: 35px;
  --leading-heading-lg: 1.25;
  --tracking-heading-lg: -0.7px;
  --text-display: 100px;
  --leading-display: 1;
  --tracking-display: -4px;
  --text-display-lg: 125px;
  --leading-display-lg: 1;
  --tracking-display-lg: -5px;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-9: 9px;
  --spacing-10: 10px;
  --spacing-13: 13px;
  --spacing-17: 17px;
  --spacing-20: 20px;
  --spacing-22: 22px;
  --spacing-23: 23px;
  --spacing-25: 25px;
  --spacing-41: 41px;
  --spacing-42: 42px;
  --spacing-47: 47px;
  --spacing-50: 50px;
  --spacing-58: 58px;

  /* Border Radius */
  --radius-md: 4.16667px;
  --radius-md-2: 6.66667px;
  --radius-3xl: 25px;
  --radius-full: 50px;
  --radius-full-2: 65px;
  --radius-full-3: 85.8333px;
}
```

# Column — Style Reference
> Architectural blueprint on white marble. Subtle background patterns convey structure beneath a pristine, luminous surface, punctuated by precise, high-contrast markers.

**Theme:** light

Column's design is a blend of corporate authority and digital precision. It uses a very light, almost invisible dotted grid background to evoke a technical blueprint, while maintaining a clean, spacious feel. The deep-seated violet and stark orange accents provide clear interactive points set against a largely monochromatic text palette, suggesting seriousness and innovation. Strategic use of subtle box shadows and inner borders adds dimensionality without heavy handedness, like layers of frosted glass on a complex instrument.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Ink Blue | `#011821` | `--color-ink-blue` | Primary text color for headings and body copy, grounding the design. |
| Code Black | `#000000` | `--color-code-black` | Used for critical text elements and strong outlines, providing maximum contrast and emphasis. |
| Ghost White | `#ffffff` | `--color-ghost-white` | Primary background for pages and cards, fostering a sense of openness and purity. |
| Fog Gray | `#f6f6f8` | `--color-fog-gray` | Secondary background for sections and subtle content groupings, almost imperceptibly off-white to provide visual separation. |
| Steel Gray | `#e3e4e8` | `--color-steel-gray` | Subtle borders and separators, defining boundaries without starkness. |
| Charcoal Text | `#232730` | `--color-charcoal-text` | Text on lighter backgrounds for softer contrast than pure black, often used in navigation and body text. |
| Slate Text | `#7c7f88` | `--color-slate-text` | Contextual body text and secondary labels, offering readability without competing with primary elements. |
| Graphite | `#12161` | `--color-graphite` | Darker shades for text and icons, particularly on hero sections, for depth. |
| Deep Plum | `#111a4a` | `--color-deep-plum` | Brand accent for interactive elements, icons, and significant textual highlights, establishing Column's brand identity. |
| Action Orange | `#ec652b` | `--color-action-orange` | Primary call-to-action buttons and key interactive states, drawing immediate attention. |
| Soft Horizon Gradient | `linear-gradient(125deg, rgb(214, 86, 32) -3.16%, rgb(159, 122, 238) 14.55%, rgb(69, 117, 205) 32.26%, rgb(113, 210, 240) 49.97%, rgb(68, 180, 139) 67.68%, rgb(244, 223, 105) 85.39%)` | `--color-soft-horizon-gradient` | Decorative background for banners, imbuing sections with a sense of expansive, technological potential. |
| Faded Grid Blue | `#023247` | `--color-faded-grid-blue` | Illustrative elements and background patterns, adding a subtle technical depth. |
| Success Moss | `#44b48b` | `--color-success-moss` | Status indicators and affirmation icons, providing a clear visual cue for positive outcomes. |
| Radial Twilight Gradient | `radial-gradient(29.88% 184.91% at 6.55% -48.11%, rgb(119, 28, 134) 0%, rgb(17, 26, 74) 100%)` | `--color-radial-twilight-gradient` | Subtle, localized background gradient to highlight specific sections with a deep, cosmic feel. |
| Info Blue | `#7ea7e9` | `--color-info-blue` | Informational graphics and secondary accents, providing a cooler tonal balance. |
| Callout Cyan | `#167e6c` | `--color-callout-cyan` | Highlight elements and secondary interactive states, offering a complementary accent to the orange. |
| Notification Teal | `#88deeb` | `--color-notification-teal` | Subtle highlights and supporting iconography, a brighter counterpart to Callout Cyan. |

## Tokens — Typography

### SuisseIntl — Primary typeface for all main content, headings, and UI elements. Its clean, slightly compressed letterforms convey efficiency and sophistication. Weight 600 at 48px headlines commands attention with quiet confidence; weight 300 for subheadings at 28px adds a subtle, approachable gravity. The variable letter-spacing (up to -0.03em at larger sizes) tightens display text for visual impact. · `--font-suisseintl`
- **Substitute:** Inter
- **Weights:** 300, 400, 500, 600
- **Sizes:** 11px, 12px, 14px, 16px, 18px, 20px, 24px, 28px, 40px, 48px, 52px, 60px
- **Line height:** 1.00, 1.10, 1.30, 1.33, 1.38, 1.40, 1.43, 1.50
- **Letter spacing:** -0.03em, -0.02em, -0.01em
- **OpenType features:** `"salt" 2`
- **Role:** Primary typeface for all main content, headings, and UI elements. Its clean, slightly compressed letterforms convey efficiency and sophistication. Weight 600 at 48px headlines commands attention with quiet confidence; weight 300 for subheadings at 28px adds a subtle, approachable gravity. The variable letter-spacing (up to -0.03em at larger sizes) tightens display text for visual impact.

### SFMono — Monospaced font for code snippets, financial figures, and technical labels, ensuring precise alignment and clarity for data-driven content. Its consistent width emphasizes the accuracy inherent in banking operations. · `--font-sfmono`
- **Substitute:** IBM Plex Mono
- **Weights:** 400
- **Sizes:** 10px, 12px
- **Line height:** 1.50
- **Letter spacing:** normal
- **OpenType features:** `"cv11"; "salt" 2`
- **Role:** Monospaced font for code snippets, financial figures, and technical labels, ensuring precise alignment and clarity for data-driven content. Its consistent width emphasizes the accuracy inherent in banking operations.

### Inter — Secondary typeface, primarily for detailed body text and supporting UI elements. Provides similar legibility to SuisseIntl but with slightly more open letterforms at smaller sizes, aiding readability in high-information densities. · `--font-inter`
- **Weights:** 400, 500, 600
- **Sizes:** 10px, 12px, 14px, 16px, 20px, 24px
- **Line height:** 1.00, 1.10, 1.14, 1.33, 1.50
- **Letter spacing:** -0.03em, -0.02em
- **OpenType features:** `"cv11"`
- **Role:** Secondary typeface, primarily for detailed body text and supporting UI elements. Provides similar legibility to SuisseIntl but with slightly more open letterforms at smaller sizes, aiding readability in high-information densities.

### SuisseIntlMono — Specialized monospaced font for technical outputs and code display within the UI, complementing SFMono for specific interactive code contexts. Its presence reinforces the developer-centric aspect of Column. · `--font-suisseintlmono`
- **Substitute:** IBM Plex Mono
- **Weights:** 400
- **Sizes:** 10px, 12px, 14px
- **Line height:** 1.50
- **Letter spacing:** normal
- **OpenType features:** `"cv11"; "salt" 2`
- **Role:** Specialized monospaced font for technical outputs and code display within the UI, complementing SFMono for specific interactive code contexts. Its presence reinforces the developer-centric aspect of Column.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.5 | — | `--text-caption` |
| body | 14px | 1.5 | -0.28px | `--text-body` |
| subheading | 18px | 1.4 | -0.36px | `--text-subheading` |
| heading-sm | 24px | 1.33 | -0.48px | `--text-heading-sm` |
| heading | 40px | 1.1 | -0.8px | `--text-heading` |
| display | 48px | 1 | -1.44px | `--text-display` |

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
| 64 | 64px | `--spacing-64` |
| 72 | 72px | `--spacing-72` |
| 80 | 80px | `--spacing-80` |
| 96 | 96px | `--spacing-96` |
| 100 | 100px | `--spacing-100` |
| 144 | 144px | `--spacing-144` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 8px |
| subtle | 2px |
| buttons | 8px |
| default | 8px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(17, 26, 74, 0.1) 0px 1px 3px 0px, rgba(17, 26, 74, 0...` | `--shadow-subtle` |
| subtle-2 | `rgba(87, 90, 100, 0.12) 0px 0px 0px 1px` | `--shadow-subtle-2` |
| subtle-3 | `rgba(0, 0, 0, 0.05) 0px 0px 0px 1px inset` | `--shadow-subtle-3` |
| xl | `rgba(0, 0, 0, 0.02) 0px 40px 32px 0px, rgba(0, 0, 0, 0.03...` | `--shadow-xl` |
| sm | `rgba(0, 0, 0, 0.05) 0px 4px 8px 0px, rgba(0, 0, 0, 0.1) 0...` | `--shadow-sm` |
| subtle-4 | `rgba(0, 0, 0, 0.1) 0px 1px 2px 0px, rgb(255, 255, 255) 0p...` | `--shadow-subtle-4` |
| subtle-5 | `rgba(0, 0, 0, 0.1) 0px 1px 2px 0px` | `--shadow-subtle-5` |

### Layout

- **Section gap:** 48px

## Components

### Primary Navigation Link
**Role:** Navigation

Text link with `SuisseIntl` 16px weight 400, `Ink Blue` (#011821) text. No explicit padding or background, relying on layout for spacing. Hover state changes color to a darker shade.

### Ghost Button - Inverted
**Role:** Secondary interaction in dark contexts

Button with `rgba(1, 24, 33, 0.01)` background, `c1e8ef` text, `SuisseIntl` 14px weight 400. `8px` border-radius, `8px` vertical padding, `12px` horizontal padding. Subtle `Steel Gray` (#e3e4e8) border.

### Ghost Button - Light
**Role:** Secondary interaction in light contexts

Button with `rgba(255, 255, 255, 0.25)` background, `Code Black` (#000000) text, `SuisseIntl` 12px weight 400. `8px` border-radius, `6px` vertical padding, `12px` horizontal padding. No border, relies on transparency and light text.

### Nav Button - Light Text
**Role:** Interaction in transparent sections

Button with `rgba(255, 255, 255, 0.5)` background, `Charcoal Text` (#232730) text, `SuisseIntl` 14px weight 400. `8px` border-radius, `0px` vertical padding, `16px` horizontal padding. `Steel Gray` (#e3e4e8) border.

### Card - Callout Orange
**Role:** Prominent information highlight

Card with `Action Orange` (#ec652b) background, `6px` border-radius. Shadow `rgba(0, 0, 0, 0.1) 0px 4px 8px 0px, rgba(0, 0, 0, 0.1) 0px 2px 4px 0px, rgba(0, 0, 0, 0.25) 0px 1px 1px 0px`. `20px` padding on all sides. Designed to draw attention to key metrics or statements.

### Badge - Transparent
**Role:** Categorization or small label

Transparent background badge, `Code Black` (#000000) text. No border-radius or padding specified, implying inline usage or minimal styling.

### Secondary Button - Outlined
**Role:** Alternative interaction

Button with `rgba(0, 0, 0, 0)` background, `Deep Plum` (#111a4a) text, `SuisseIntl` 16px weight 400. `8px` border-radius, `12px` vertical padding, `32px` horizontal padding. Border color matches `Deep Plum`.

## Do's and Don'ts

### Do
- Use `Fog Gray` (#f6f6f8) for secondary section backgrounds to create subtle visual breaks, not just `Ghost White` (#ffffff).
- Apply `SuisseIntl` with a negative letter-spacing (-0.02em to -0.03em) for all headlines 28px and larger, tightening the text for a refined, modern feel.
- Borders on interactive elements should primarily use `Steel Gray` (#e3e4e8), providing definition without harshness.
- All cards and buttons should consistently use an `8px` border-radius for a soft, approachable geometry, except when specific components dictate otherwise.
- Emphasize critical actions with the `Action Orange` (#ec652b) background, reserving `Deep Plum` (#111a4a) primarily for non-primary interactive elements and brand accents.
- Use `SFMono` or `SuisseIntlMono` at 10-12px for all numerical data and code snippets to ensure alignment and technical precision.
- Enhance surface depth with the subtle card shadow: `rgba(17, 26, 74, 0.05) 0px 0px 0px 1px, rgba(0, 0, 0, 0.1) 0px 1px 2px 0px, rgba(255, 255, 255, 0.5) 0px 0px 0px 1px inset`.

### Don't
- Do not use generic blue for primary interactive elements; save `Info Blue` (#7ea7e9) for graphics and non-actionable information to prevent dilution of `Deep Plum` and `Action Orange`.
- Avoid arbitrary uses of vivid colors; `Success Moss` (#44b48b) and `Notification Teal` (#88deeb) are reserved for semantic feedback, not decorative elements.
- Do not deviate from the `8px` default border-radius for primary UI elements across buttons and cards; exceptions are only for badges or specific component variants.
- Do not apply heavy, opaque box-shadows; the system relies on subtle, layered shadows to suggest depth and elevation.
- Avoid using `Code Black` (#000000) for large blocks of text; opt for `Ink Blue` (#011821) or `Charcoal Text` (#232730) for better readability and a softer appearance.
- Do not introduce new typefaces; `SuisseIntl` is for visual impact and headings, `Inter` for general readability, and monospaced fonts for technical context.
- Do not break the established vertical rhythm of 48px `sectionGap` and `24px` `elementGap` in content arrangements; maintain spaciousness.

## Imagery

This site prominently features abstract, technical graphics and product UI screenshots. The graphics often depict dotted world maps or wireframe-like structures, usually in subdued blues and grays (`Faded Grid Blue`). Product UI screenshots are contained within card-like components, often with subtle drop shadows, showcasing financial data and code snippets with `SFMono` or `SuisseIntlMono` for a developer-centric feel. There are no lifestyle photos or complex illustrations; the imagery is functional and explanatory, reinforcing the brand's focus on backend infrastructure and developer tools. Visual density is low, with imagery serving more an atmospheric and explanatory role rather than a dominant content one.

## Layout

The page uses a `max-width` contained layout, centered on the screen, around a primary content width of approximately 1200px based on observable component widths and spacing. The hero section is a full-bleed, almost white background with a subtle dotted grid pattern creating a technical blueprint aesthetic (`Faded Grid Blue`). Content sections alternate between `Ghost White` and `Fog Gray` backgrounds, maintaining a consistent vertical `sectionGap` of 48px. Content is typically arranged in left-aligned blocks or two-column layouts where text is on one side and a product screenshot or graphic is on the other. Feature sections often use a grid of cards (implied 2-3 column from screenshots). The overall impression is spacious and organized, prioritizing information clarity over dense visual elements.

## Agent Prompt Guide

### Quick Color Reference
- Text (primary): `#011821` (Ink Blue)
- Background (page): `#ffffff` (Ghost White)
- Background (section): `#f6f6f8` (Fog Gray)
- CTA Button: `#ec652b` (Action Orange)
- Accent (brand): `#111a4a` (Deep Plum)
- Border (neutral): `#e3e4e8` (Steel Gray)

### 3-5 Example Component Prompts
1. **Create a Hero Section:** Use `Ghost White` as background, overlay with a subtle `Faded Grid Blue` (`#023247`) map graphic. Headline: `SuisseIntl` 48px, weight 600, `Ink Blue` text, `lineHeight` 1.1, `letterSpacing` -1.44px. Subtext: `Inter` 18px, weight 400, `Slate Text` (`#7c7f88`). Include a `Call To Action Button - Filled` and a `Secondary Button - Outlined` below the text, aligned left with 24px horizontal spacing.
2. **Generate a Product Feature Card:** Background `Ghost White`, `8px` border-radius, using `rgba(17, 26, 74, 0.05) 0px 0px 0px 1px, rgba(0, 0, 0, 0.1) 0px 1px 2px 0px, rgba(255, 255, 255, 0.5) 0px 0px 0px 1px inset` shadow. `24px` internal padding. Title: `SuisseIntl` 20px, weight 500, `Ink Blue`. Body text: `Inter` 14px, weight 400, `Slate Text`.
3. **Design a Header with Navigation:** Transparent background. Logo on left. Navigation links (`Primary Navigation Link`) to the right using `SuisseIntl` 16px weight 400, `Ink Blue` text. On far right, include `Ghost Button - Light` for 'Sign in' and `Call To Action Button - Filled` for 'Get started', horizontally spaced by 16px.
4. **Create a Testimonial Section:** Background `Fog Gray` (#f6f6f8). Quote text with `SuisseIntl` 28px, weight 300, `Ink Blue`, `lineHeight` 1.3, `letterSpacing` -0.56px. Attribution with `SuisseIntl` 14px, weight 500, `Deep Plum`, followed by `Slate Text` for title, both with `letterSpacing` -0.28px. Place an `Action Orange` `Card - Callout Orange` with a relevant metric adjacent to the text.

## Similar Brands

- **Stripe** — Shares a similar technical, clean aesthetic with subtle background patterns, a focus on API/developer tools, and a strong brand accent on interactive elements.
- **Linear** — Employs an ultra-clean, spacious UI with a monochromatic base and a single, vibrant accent color for interaction, and prefers subtle elevation over bold shadows.
- **Ramp** — A fintech brand that uses a similar sophisticated, light-themed approach, with structured layouts, crisp typography, and strategic splashes of brand colors to highlight key actions and data.
- **Mercury** — Another banking tech company that opts for a minimal, almost invisible UI until interaction, using light backgrounds, subtle gradients, and clear, functional typography.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-ink-blue: #011821;
  --color-code-black: #000000;
  --color-ghost-white: #ffffff;
  --color-fog-gray: #f6f6f8;
  --color-steel-gray: #e3e4e8;
  --color-charcoal-text: #232730;
  --color-slate-text: #7c7f88;
  --color-graphite: #12161;
  --color-deep-plum: #111a4a;
  --color-action-orange: #ec652b;
  --color-soft-horizon-gradient: #d65620;
  --gradient-soft-horizon-gradient: linear-gradient(125deg, rgb(214, 86, 32) -3.16%, rgb(159, 122, 238) 14.55%, rgb(69, 117, 205) 32.26%, rgb(113, 210, 240) 49.97%, rgb(68, 180, 139) 67.68%, rgb(244, 223, 105) 85.39%);
  --color-faded-grid-blue: #023247;
  --color-success-moss: #44b48b;
  --color-radial-twilight-gradient: #771c86;
  --gradient-radial-twilight-gradient: radial-gradient(29.88% 184.91% at 6.55% -48.11%, rgb(119, 28, 134) 0%, rgb(17, 26, 74) 100%);
  --color-info-blue: #7ea7e9;
  --color-callout-cyan: #167e6c;
  --color-notification-teal: #88deeb;

  /* Typography — Font Families */
  --font-suisseintl: 'SuisseIntl', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sfmono: 'SFMono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-suisseintlmono: 'SuisseIntlMono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --text-body: 14px;
  --leading-body: 1.5;
  --tracking-body: -0.28px;
  --text-subheading: 18px;
  --leading-subheading: 1.4;
  --tracking-subheading: -0.36px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.33;
  --tracking-heading-sm: -0.48px;
  --text-heading: 40px;
  --leading-heading: 1.1;
  --tracking-heading: -0.8px;
  --text-display: 48px;
  --leading-display: 1;
  --tracking-display: -1.44px;

  /* Typography — Weights */
  --font-weight-light: 300;
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
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-100: 100px;
  --spacing-144: 144px;

  /* Layout */
  --section-gap: 48px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-lg: 8px;
  --radius-xl: 12px;

  /* Named Radii */
  --radius-cards: 8px;
  --radius-subtle: 2px;
  --radius-buttons: 8px;
  --radius-default: 8px;

  /* Shadows */
  --shadow-subtle: rgba(17, 26, 74, 0.1) 0px 1px 3px 0px, rgba(17, 26, 74, 0.05) 0px 1px 0px 0px, rgba(255, 255, 255, 0.5) 0px 1px 0px 0px inset, rgba(255, 255, 255, 0.5) 0px 1px 4px 0px inset;
  --shadow-subtle-2: rgba(87, 90, 100, 0.12) 0px 0px 0px 1px;
  --shadow-subtle-3: rgba(0, 0, 0, 0.05) 0px 0px 0px 1px inset;
  --shadow-xl: rgba(0, 0, 0, 0.02) 0px 40px 32px 0px, rgba(0, 0, 0, 0.03) 0px 22px 18px 0px, rgba(0, 0, 0, 0.03) 0px 12px 10px 0px, rgba(0, 0, 0, 0.04) 0px 7px 5px 0px, rgba(0, 0, 0, 0.07) 0px 3px 2px 0px;
  --shadow-sm: rgba(0, 0, 0, 0.05) 0px 4px 8px 0px, rgba(0, 0, 0, 0.1) 0px 2px 4px 0px, rgba(0, 0, 0, 0.1) 0px 1px 1px 0px;
  --shadow-subtle-4: rgba(0, 0, 0, 0.1) 0px 1px 2px 0px, rgb(255, 255, 255) 0px 0px 0px 1px inset;
  --shadow-subtle-5: rgba(0, 0, 0, 0.1) 0px 1px 2px 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-ink-blue: #011821;
  --color-code-black: #000000;
  --color-ghost-white: #ffffff;
  --color-fog-gray: #f6f6f8;
  --color-steel-gray: #e3e4e8;
  --color-charcoal-text: #232730;
  --color-slate-text: #7c7f88;
  --color-graphite: #12161;
  --color-deep-plum: #111a4a;
  --color-action-orange: #ec652b;
  --color-soft-horizon-gradient: #d65620;
  --color-faded-grid-blue: #023247;
  --color-success-moss: #44b48b;
  --color-radial-twilight-gradient: #771c86;
  --color-info-blue: #7ea7e9;
  --color-callout-cyan: #167e6c;
  --color-notification-teal: #88deeb;

  /* Typography */
  --font-suisseintl: 'SuisseIntl', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sfmono: 'SFMono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-suisseintlmono: 'SuisseIntlMono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --text-body: 14px;
  --leading-body: 1.5;
  --tracking-body: -0.28px;
  --text-subheading: 18px;
  --leading-subheading: 1.4;
  --tracking-subheading: -0.36px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.33;
  --tracking-heading-sm: -0.48px;
  --text-heading: 40px;
  --leading-heading: 1.1;
  --tracking-heading: -0.8px;
  --text-display: 48px;
  --leading-display: 1;
  --tracking-display: -1.44px;

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
  --spacing-100: 100px;
  --spacing-144: 144px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-lg: 8px;
  --radius-xl: 12px;

  /* Shadows */
  --shadow-subtle: rgba(17, 26, 74, 0.1) 0px 1px 3px 0px, rgba(17, 26, 74, 0.05) 0px 1px 0px 0px, rgba(255, 255, 255, 0.5) 0px 1px 0px 0px inset, rgba(255, 255, 255, 0.5) 0px 1px 4px 0px inset;
  --shadow-subtle-2: rgba(87, 90, 100, 0.12) 0px 0px 0px 1px;
  --shadow-subtle-3: rgba(0, 0, 0, 0.05) 0px 0px 0px 1px inset;
  --shadow-xl: rgba(0, 0, 0, 0.02) 0px 40px 32px 0px, rgba(0, 0, 0, 0.03) 0px 22px 18px 0px, rgba(0, 0, 0, 0.03) 0px 12px 10px 0px, rgba(0, 0, 0, 0.04) 0px 7px 5px 0px, rgba(0, 0, 0, 0.07) 0px 3px 2px 0px;
  --shadow-sm: rgba(0, 0, 0, 0.05) 0px 4px 8px 0px, rgba(0, 0, 0, 0.1) 0px 2px 4px 0px, rgba(0, 0, 0, 0.1) 0px 1px 1px 0px;
  --shadow-subtle-4: rgba(0, 0, 0, 0.1) 0px 1px 2px 0px, rgb(255, 255, 255) 0px 0px 0px 1px inset;
  --shadow-subtle-5: rgba(0, 0, 0, 0.1) 0px 1px 2px 0px;
}
```

# Cohere — Style Reference
> Deep charcoal on white, with purple-violet washes. Like a digital slate occasionally illuminated by the aurora borealis.

**Theme:** light

Cohere's visual identity projects a sense of measured, capable AI. It balances the stark minimalism often associated with technology with subtle organic hints of color and rounded forms, suggesting a human-centered approach to complex systems. The predominant white and deep charcoal create a high-contrast, authoritative feel, softened by strategically placed gradients and rounded elements that prevent the design from feeling overly rigid. The absence of strong shadows emphasizes depth through color contrast rather than artificial light, contributing to a modern, almost ethereal aesthetic.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Absolute Zero | `#ffffff` | `--color-absolute-zero` | Page backgrounds, card surfaces, primary text on dark backgrounds. |
| Night Sky | `#17171c` | `--color-night-sky` | Primary headings and body text on light backgrounds, dark button backgrounds. |
| Charcoal Slate | `#212121` | `--color-charcoal-slate` | Secondary text, hero section body copy, footer background text. |
| Ash Mist | `#e5e7eb` | `--color-ash-mist` | Element borders, subtle dividers, inactive states. |
| Graphite | `#75758a` | `--color-graphite` | Footer link text, inactive navigation items, secondary body text. |
| Deep Space | `#000000` | `--color-deep-space` | Icon fills, outlines, very rare body text for maximum contrast. |
| Warm Violet Gradient | `linear-gradient(to right, rgb(255, 119, 89), rgb(118, 112, 197), rgb(76, 110, 230))` | `--color-warm-violet-gradient` | Accent backgrounds, brand highlights, decorative elements — creates a dynamic, evolving visual anchor. |
| Cosmic Violet | `#9b60aa` | `--color-cosmic-violet` | Background for feature sections, large decorative elements. This unique purple hue distinguishes the brand's aesthetic from typical tech blues. |
| Soft Indigo Wash | `#f0dff3` | `--color-soft-indigo-wash` | Subtle background tints for navigation elements or micro-components, hinting at the brand's chromatic range. |
| Azure Glow | `#00a1df` | `--color-azure-glow` | Highlighting interactive elements, rare icon fills. Used sparingly against the neutral palette to draw immediate attention. |

## Tokens — Typography

### Unica77 Cohere Web — Primary branding sans-serif. Used for body text, navigation, buttons, and most headings up to display size. Its subtle negative letter-spacing contributes to the precise, engineered feel. · `--font-unica77-cohere-web`
- **Substitute:** Inter
- **Weights:** 400, 700
- **Sizes:** 12px, 14px, 16px, 18px, 24px, 32px, 48px
- **Line height:** 1.20, 1.30, 1.40, 1.50
- **Letter spacing:** -0.01
- **Role:** Primary branding sans-serif. Used for body text, navigation, buttons, and most headings up to display size. Its subtle negative letter-spacing contributes to the precise, engineered feel.

### CohereText — Signature display font for large headlines. Its extremely tight letter-spacing and substantial size command attention without being visually disruptive, embodying the brand's confident but refined voice. · `--font-coheretext`
- **Substitute:** Outfit
- **Weights:** 400
- **Sizes:** 60px, 72px
- **Line height:** 1.00
- **Letter spacing:** -0.02
- **Role:** Signature display font for large headlines. Its extremely tight letter-spacing and substantial size command attention without being visually disruptive, embodying the brand's confident but refined voice.

### CohereMono — Monospaced font for code snippets or specific technical labels in navigation. The slight positive letter-spacing ensures readability of technical terms, contrasting with the tighter Unica77. · `--font-coheremono`
- **Substitute:** Space Mono
- **Weights:** 400
- **Sizes:** 14px
- **Line height:** 1.40
- **Letter spacing:** 0.02
- **Role:** Monospaced font for code snippets or specific technical labels in navigation. The slight positive letter-spacing ensures readability of technical terms, contrasting with the tighter Unica77.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.4 | -0.12px | `--text-caption` |
| body-sm | 14px | 1.4 | -0.14px | `--text-body-sm` |
| body | 16px | 1.5 | -0.16px | `--text-body` |
| subheading | 18px | 1.4 | -0.18px | `--text-subheading` |
| heading | 24px | 1.3 | -0.24px | `--text-heading` |
| heading-lg | 32px | 1.2 | -0.32px | `--text-heading-lg` |
| display | 48px | 1.2 | -0.48px | `--text-display` |
| display-xl | 60px | 1 | -1.2px | `--text-display-xl` |
| display-xxl | 72px | 1 | -1.44px | `--text-display-xxl` |

## Tokens — Spacing & Shapes

**Base unit:** 8px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 8 | 8px | `--spacing-8` |
| 16 | 16px | `--spacing-16` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 56 | 56px | `--spacing-56` |
| 80 | 80px | `--spacing-80` |
| 128 | 128px | `--spacing-128` |
| 144 | 144px | `--spacing-144` |
| 160 | 160px | `--spacing-160` |
| 176 | 176px | `--spacing-176` |

### Border Radius

| Element | Value |
|---------|-------|
| buttons | 9999px |
| default | 22px |
| navigation | 4px |

### Layout

- **Section gap:** 64px
- **Card padding:** 32px
- **Element gap:** 16px

## Components

### Primary Ghost Button
**Role:** Call to action, secondary actions.

backgroundColor: rgba(0, 0, 0, 0), color: #212121, border: 1px solid #e5e7eb, borderRadius: 9999px, padding: 12px 24px.

### Primary Filled Button
**Role:** Main call to action.

backgroundColor: #17171c, color: #ffffff, borderRadius: 9999px, padding: 12px 24px.

### Tertiary Bordered Link
**Role:** Navigation, subtle calls to action.

backgroundColor: rgba(0, 0, 0, 0), color: #212121, border-bottom: 2px solid #e5e7eb, borderRadius: 4px, padding-bottom: 0px.

### Navigation Link with Underline
**Role:** Primary navigation items.

backgroundColor: rgba(0, 0, 0, 0), color: #212121, border-bottom: 2px solid transparent (visual only for active state), borderRadius: 0px, padding-bottom: 36px.

### Hero Headline
**Role:** Main page title.

font-family: CohereText, font-weight: 400, font-size: 72px, line-height: 1, letter-spacing: -1.44px, color: #212121.

### Product Feature Card
**Role:** Displaying product features or content sections.

backgroundColor: transparent, borderRadius: 22px, box-shadow: none, minimal internal padding for images/content to bleed to edges.

### Footer Input Field
**Role:** Email subscription input.

backgroundColor: transparent, color: #ffffff, border-bottom: 1px solid #ffffff, borderRadius: 0px, padding-bottom: 0px.

## Do's and Don'ts

### Do
- Use Night Sky (#17171c) for primary headings and body text on light backgrounds to maintain high contrast.
- Apply button border-radius of 9999px for all interactive buttons to establish a consistent soft, approachable shape.
- Ensure large display headings use CohereText weight 400 at 72px, with a precise -0.02em letter-spacing for brand consistency.
- Elevate sections or cards without traditional box-shadows, relying on the #9b60aa and linear gradients for visual distinction.
- Maintain a clear distinction between the tight letter-spacing of Unica77 Web (-0.01em) and the expanded CohereMono (0.02em).
- Use Ash Mist (#e5e7eb) for all neutral borders and dividers to provide subtle structure.

### Don't
- Do not introduce additional color hues beyond the defined brand and accent palette; maintain a controlled and focused color scheme.
- Avoid generic drop shadows; rely on color contrast and the specified gradients for depth and separation.
- Do not vary border-radius for buttons and input fields; consistently use 9999px for buttons and 0px for inputs.
- Refrain from using Unica77 Web for hero/display-level headings; reserve CohereText for these prominent areas.
- Do not deviate from the defined letter-spacing values for each font family; they are critical to the typographic identity.
- Avoid filling cards with solid background colors; maintain transparency where appropriate for a lightweight aesthetic, and use background gradients only when specified.

## Imagery

Imagery is characterized by a mix of abstract, almost iridescent 3D renders with prominent purple-violet tones, juxtaposed with realistic, muted photography of individuals interacting with technology. The abstract graphics are used as full-bleed backgrounds or contained within feature sections, adding a futuristic, sophisticated atmosphere. Photography often features close-up, focused shots with desaturated or slightly cool-toned filters, avoiding over-vibrancy. Product screenshots appear as insets within the abstract visuals, showcasing actual UI without overwhelming the page. Icons are monochrome, generally filled outlines or simple geometric forms, reinforcing the technical and precise aesthetic.

## Layout

The page primarily uses a max-width contained layout for content sections, set against a predominantly white full-bleed background. The hero section is centered with a large headline, subtext, and call-to-action buttons. Subsequent sections alternate between full-width abstract graphic backgrounds and contained content blocks. Content arrangement frequently features text-left/image-right or symmetrically stacked elements. Spacing between sections is generous, creating a spacious and legible page flow. The footer is a full-width dark section contrasting the light main page, organizing content into distinct columns. The navigation bar is sticky at the top, allowing for continuous access.

## Agent Prompt Guide

### Quick Color Reference
- Text (Primary): #17171c
- Background (Page): #ffffff
- CTA Button (Filled): #17171c
- Border (Neutral): #e5e7eb
- Accent (Brand Purple): #9b60aa

### 3-5 Example Component Prompts
1. Create a hero section: background #ffffff. Headline 'Your next breakthrough, powered by AI' using CohereText font, weight 400, size 72px, line-height 1, letter-spacing -1.44px, color #212121. Subtext 'Cohere is where powerful AI meets practical business solutions' using Unica77 Cohere Web, weight 400, size 18px, line-height 1.4, color #212121. Two buttons below, left: Filled Button using #17171c background, #ffffff text, 9999px radius, 12px 24px padding. Right: Ghost Button using transparent background, #212121 text, 1px solid #e5e7eb border, 9999px radius, 12px 24px padding.
2. Design a feature card: Transparent background, 22px border radius. Inside, place a 10px tall gradient bar using 'linear-gradient(to right, rgb(255, 119, 89), rgb(118, 112, 197), rgb(76, 110, 230))'. Below the bar, include a heading using Unica77 Cohere Web, weight 700, size 24px, line-height 1.3, color #17171c, and body text using Unica77 Cohere Web, weight 400, size 16px, line-height 1.5, color #212121.
3. Create a footer email input field: background transparent. Placeholder text 'Enter your email' in #ffffff. Input text color #ffffff. Bottom border 1px solid #ffffff. No border radius. Button '->' to the right should be a ghost button with #ffffff text, transparent background, and #ffffff border, 9999px radius.

## Similar Brands

- **Anthropic** — Similar high-contrast dark text on light background, sophisticated minimal aesthetic, and subtle use of gradients/abstract visuals.
- **OpenAI** — Shares the use of robust serif-like display typography for headlines combined with a clean sans-serif for body, evoking authority in AI space.
- **Vercel** — Employs a precise, developer-tool aesthetic with strong typography, generous spacing, and controlled use of accent colors on a largely monochromatic canvas.
- **Linear** — Features a strong emphasis on typography, high contrast, and the strategic deployment of accent colors to highlight interactive elements and convey cutting-edge technology.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-absolute-zero: #ffffff;
  --color-night-sky: #17171c;
  --color-charcoal-slate: #212121;
  --color-ash-mist: #e5e7eb;
  --color-graphite: #75758a;
  --color-deep-space: #000000;
  --color-warm-violet-gradient: #ff7759;
  --gradient-warm-violet-gradient: linear-gradient(to right, rgb(255, 119, 89), rgb(118, 112, 197), rgb(76, 110, 230));
  --color-cosmic-violet: #9b60aa;
  --color-soft-indigo-wash: #f0dff3;
  --color-azure-glow: #00a1df;

  /* Typography — Font Families */
  --font-unica77-cohere-web: 'Unica77 Cohere Web', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-coheretext: 'CohereText', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-coheremono: 'CohereMono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.4;
  --tracking-caption: -0.12px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.4;
  --tracking-body-sm: -0.14px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.16px;
  --text-subheading: 18px;
  --leading-subheading: 1.4;
  --tracking-subheading: -0.18px;
  --text-heading: 24px;
  --leading-heading: 1.3;
  --tracking-heading: -0.24px;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -0.32px;
  --text-display: 48px;
  --leading-display: 1.2;
  --tracking-display: -0.48px;
  --text-display-xl: 60px;
  --leading-display-xl: 1;
  --tracking-display-xl: -1.2px;
  --text-display-xxl: 72px;
  --leading-display-xxl: 1;
  --tracking-display-xxl: -1.44px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-56: 56px;
  --spacing-80: 80px;
  --spacing-128: 128px;
  --spacing-144: 144px;
  --spacing-160: 160px;
  --spacing-176: 176px;

  /* Layout */
  --section-gap: 64px;
  --card-padding: 32px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 22px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-buttons: 9999px;
  --radius-default: 22px;
  --radius-navigation: 4px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-absolute-zero: #ffffff;
  --color-night-sky: #17171c;
  --color-charcoal-slate: #212121;
  --color-ash-mist: #e5e7eb;
  --color-graphite: #75758a;
  --color-deep-space: #000000;
  --color-warm-violet-gradient: #ff7759;
  --color-cosmic-violet: #9b60aa;
  --color-soft-indigo-wash: #f0dff3;
  --color-azure-glow: #00a1df;

  /* Typography */
  --font-unica77-cohere-web: 'Unica77 Cohere Web', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-coheretext: 'CohereText', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-coheremono: 'CohereMono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.4;
  --tracking-caption: -0.12px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.4;
  --tracking-body-sm: -0.14px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.16px;
  --text-subheading: 18px;
  --leading-subheading: 1.4;
  --tracking-subheading: -0.18px;
  --text-heading: 24px;
  --leading-heading: 1.3;
  --tracking-heading: -0.24px;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -0.32px;
  --text-display: 48px;
  --leading-display: 1.2;
  --tracking-display: -0.48px;
  --text-display-xl: 60px;
  --leading-display-xl: 1;
  --tracking-display-xl: -1.2px;
  --text-display-xxl: 72px;
  --leading-display-xxl: 1;
  --tracking-display-xxl: -1.44px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-56: 56px;
  --spacing-80: 80px;
  --spacing-128: 128px;
  --spacing-144: 144px;
  --spacing-160: 160px;
  --spacing-176: 176px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 22px;
  --radius-full: 9999px;
}
```

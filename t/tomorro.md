# Tomorro — Style Reference
> Deep Forest AI Canvas

**Theme:** light

Tomorro employs a 'Vibrant Efficiency' product language, combining a deep forest green and vivid lime green with a primarily monochrome palette. Typography is robust and functional, often in all-caps, commanding attention while maintaining clarity. Surfaces are clean and unburdened by heavy shadows, favoring subtle elevation and soft rounded corners. The design signals an authoritative yet approachable AI-powered solution.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Forest Canopy | `#122314` | `--color-forest-canopy` | Primary background for dark sections, footer background — sets a deep, calming tone |
| Deep Moss | `#273f2b` | `--color-deep-moss` | Dark text for accents and interactive elements on light backgrounds, border color for ghost buttons, occasional card background — provides a strong contrast to lighter greens |
| AI Lime | `#68ef3f` | `--color-ai-lime` | Primary action button fill, highlight text for AI keywords, input borders, active badges — a clear, vivid indicator of interaction and innovation |
| Dark Olive | `#7e8371` | `--color-dark-olive` | Muted supporting text, secondary link color, subtle borders — provides a soft contrast against lighter neutrals |
| Light Stone | `#b7bda5` | `--color-light-stone` | Lighter body text on white backgrounds, hints of borders — used for less prominent textual content |
| Pale Mint | `#e7f9dd` | `--color-pale-mint` | Background for subtle accents and badges on a light canvas — a very light extension of brand green |
| Soft Gray | `#d9deca` | `--color-soft-gray` | Light borders for interactive elements like links — provides subtle definition without strong visual breaks |
| Evergreen Glow | `#26a200` | `--color-evergreen-glow` | Decorative icon accents, subtle brand elements in line with the main AI Lime, button borders — provides a deeper, more saturated green highlight |
| White | `#ffffff` | `--color-white` | Default page background, card surfaces, primary text on dark backgrounds, icon fills — establishes a clean, open foundation |
| Ink | `#30322a` | `--color-ink` | Primary text color on light backgrounds, dark nav backgrounds, card text, strong header text — provides consistent readability across light surfaces |
| Carbon | `linear-gradient(rgb(0, 0, 0), rgb(39, 63, 43))` | `--color-carbon` | Deepest background for certain sections, accent for high-contrast elements; Background gradient for hero sections or brand elements, transitioning from black to Deep Moss |
| Light Canvas | `#f2f5eb` | `--color-light-canvas` | Secondary card background, subtle background sections on light themes — provides a soft, off-white alternative to pure white |
| Mid Gray | `#d6d6d6` | `--color-mid-gray` | Subtle card backgrounds and dividers — provides minimal visual separation |
| UI Gray | `#dcdfe3` | `--color-ui-gray` | Supporting UI text, subtle header accents — a neutral tone for less emphasis |

## Tokens — Typography

### Aeonik — Primary typeface for body text, UI elements, navigation, and smaller headings. Its contemporary sans-serif character provides clarity and a slightly technical feel. Used across various weights to establish hierarchy. · `--font-aeonik`
- **Substitute:** Inter
- **Weights:** 400, 500, 600, 700
- **Sizes:** 12px, 13px, 14px, 16px, 18px, 20px, 24px, 32px, 40px
- **Line height:** 1.00, 1.10, 1.20, 1.33, 1.43, 1.50, 1.67, 1.70, 1.71
- **Letter spacing:** -0.031em at 40px, -0.021em at 32px, -0.015em at 24px, -0.012em at 20px, -0.003em at 18px, -0.001em at 16px, 0.013em at 14px, 0.143em at 12px
- **Role:** Primary typeface for body text, UI elements, navigation, and smaller headings. Its contemporary sans-serif character provides clarity and a slightly technical feel. Used across various weights to establish hierarchy.

### Instrument Serif — Used for specific badge text and some headings, its serif style provides a distinctive, editorial contrast to Aeonik, adding a classic yet modern touch. · `--font-instrument-serif`
- **Substitute:** Lora
- **Weights:** 400
- **Sizes:** 16px, 18px, 32px
- **Line height:** 1.25, 1.50, 1.56
- **Letter spacing:** -0.050em at 32px, 0.028em at 18px, 0.063em at 16px
- **Role:** Used for specific badge text and some headings, its serif style provides a distinctive, editorial contrast to Aeonik, adding a classic yet modern touch.

### Ozik — Exclusive to large, impactful headings. Its heavy, bold character with tight tracking projects confidence and emphasizes key messages, creating powerful visual statements. · `--font-ozik`
- **Substitute:** Oswald
- **Weights:** 700
- **Sizes:** 56px, 80px
- **Line height:** 0.86, 0.90
- **Letter spacing:** -0.014em at 56px, -0.010em at 80px
- **Role:** Exclusive to large, impactful headings. Its heavy, bold character with tight tracking projects confidence and emphasizes key messages, creating powerful visual statements.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.71 | 0.143px | `--text-caption` |
| body | 14px | 1.67 | 0.013px | `--text-body` |
| heading-sm | 18px | 1.43 | -0.003px | `--text-heading-sm` |
| heading | 20px | 1.33 | -0.012px | `--text-heading` |
| heading-lg | 24px | 1.2 | -0.015px | `--text-heading-lg` |
| display-sm | 32px | 1.1 | -0.021px | `--text-display-sm` |
| display-md | 40px | 1 | -0.031px | `--text-display-md` |
| display-lg | 56px | 0.9 | -0.014px | `--text-display-lg` |
| display | 80px | 0.86 | -0.01px | `--text-display` |

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
| 48 | 48px | `--spacing-48` |
| 56 | 56px | `--spacing-56` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 128 | 128px | `--spacing-128` |
| 168 | 168px | `--spacing-168` |
| 240 | 240px | `--spacing-240` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 8px |
| links | 20px |
| badges | 40px |
| inputs | 24px |
| buttons | 28px |
| containers | 16px |

### Layout

- **Section gap:** 64px
- **Card padding:** 40px
- **Element gap:** 8px

## Components

### Primary Filled Button
**Role:** Main call-to-action button, signaling key interactions.

Filled with AI Lime (#68ef3f), text in Deep Moss (#273f2b), padding 12px vertical, 20px horizontal, with a 28px border-radius. High visibility and clear action.

### Ghost Button (Dark)
**Role:** Secondary action on dark backgrounds, providing emphasis without distraction.

Transparent background, white text (#ffffff), white 1px border. Padding 12px vertical, 20px horizontal, with a 28px border-radius. Subtle interaction on dark surfaces.

### Header Navigation Button
**Role:** Compact navigation item with minimal styling.

Transparent background, white text (#ffffff), 4px border-radius. Padding 7px vertical, 7px horizontal. Used for navigation links that are not primary calls to action.

### Neutral Card
**Role:** Information container on light backgrounds.

Background in Light Canvas (#f2f5eb), 8px border-radius. Padding 40px on all sides. No shadow, emphasizing a flat, clean aesthetic.

### Dark Accented Card
**Role:** Elevated information container within dark sections, featuring a subtle highlight.

Background in Deep Moss (#273f2b), with 24px border-radius. Padding 8px on all sides. Primarily used for highlighted content in a darker context.

### White Card
**Role:** Clean, standard content container.

Background in White (#ffffff), 16px border-radius. Padding 8px on all sides. Used for general content and UI elements in light sections.

### Floating Content Card
**Role:** Prominent information display with significant spacing.

Background in Light Canvas (#f2f5eb), 12px border-radius. Padding 64px vertical, 80px horizontal. Used for sections requiring more visual weight and separation.

### Input Field
**Role:** Data entry control with a distinct active state.

Transparent background, text in AI Lime (#68ef3f), with an AI Lime 1px border, 26px border-radius. Focus on simplicity and color for interaction.

### Dark Accent Badge
**Role:** Highlighting short, descriptive labels.

Transparent background, white text (#ffffff), 40px border-radius. Padding 4px vertical, 12px horizontal. Used for tags and categories on dark surfaces.

### Event Highlight Badge
**Role:** Prominent, informational banner for special announcements.

Background with 8% opacity white (rgba(255, 255, 255, 0.08)), text in White (#ffffff), 20px border-radius. Padding 8px vertical, 12px horizontal. Utilized for important, high-level notifications.

## Do's and Don'ts

### Do
- Use AI Lime (#68ef3f) as the exclusive color for primary calls to action, ensuring it always stands out.
- Employ the Ozik font at sizes 56px and 80px, with its tight letter spacing (`-0.014em` and `-0.010em` respectively), for all main page headlines to convey authority and impact.
- Maintain a clear visual hierarchy by consistently using Deep Moss (#273f2b) for strong text on light backgrounds and White (#ffffff) for text on Forest Canopy (#122314) areas.
- Apply a 28px border-radius to all primary and secondary action buttons to maintain a consistent soft, confident interactive element.
- Ensure section vertical spacing is consistently 64px to create a sense of comfortable density.
- Use Light Canvas (#f2f5eb) for secondary light-themed content cards and White (#ffffff) for primary light-themed cards, providing subtle background variations.
- Utilize fine 1px borders in Soft Gray (#d9deca) or White (#ffffff) for ghost elements or subtle distinctions, avoiding heavy lines.

### Don't
- Do not introduce new saturated primary colors beyond AI Lime (#68ef3f) and Evergreen Glow (#26a200); the system relies on a restrained palette.
- Avoid using drop shadows on cards or buttons; the design system favors flat surfaces or minimal, integrated elevation.
- Do not deviate from the specified letter spacing for Ozik and Aeonik fonts, as precise tracking is critical for their distinct character.
- Do not use dark backgrounds for body text sections unless explicitly within a Forest Canopy (#122314) context, and always use white text.
- Never use generic square buttons; all interactive buttons should incorporate the brand's rounded corners (28px or 4px for minimal).
- Avoid combining multiple bold text styles or colors unnecessarily; hierarchy is achieved through size, weight, and the distinct Ozik typeface, not excessive adornment.
- Do not break the consistent 64px vertical section gap; maintaining this rhythm is key to the page's structure and density.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | White Canvas | `#ffffff` | Default page background, provides a clean and open foundation. |
| 1 | Light Canvas Card | `#f2f5eb` | Primary card background for content on light sections, secondary background layer. |
| 2 | Pale Mint Accent | `#e7f9dd` | Subtle background for smaller elements or badges, slight elevation in color. |
| 3 | Mid Gray Surface | `#d6d6d6` | Background for minimal visual separation or subtle information displays. |
| 4 | Forest Canopy Base | `#122314` | Deepest background for hero sections or footers, establishes a contrasting dark base. |

## Imagery

Imagery primarily consists of abstract, organic 3D shapes with subtle gradient or noise textures, sometimes in brand colors. Product screenshots are rendered with slight perspective and clean UIs. Photography is minimal, if present, and focused on clean, professional contexts. Icons are typically filled, monochrome (white on dark, dark on light), with a consistent stroke weight. The overall visual language is atmospheric and clean, using abstract forms to represent complex AI concepts rather than literal depictions. Images are generally contained within their sections, not full-bleed, but some overlap with other elements is present, creating visual depth.

## Layout

The page uses a full-bleed structure for background sections, but content is largely constrained within a centered max-width container, appearing to be around 1200px wide. The hero section is a full-width dark background band with a prominent centered headline, supporting text, and AI Lime buttons. Subsequent sections alternate backgrounds between light canvas (#ffffff) and Light Canvas (#f2f5eb), creating distinct visual blocks. Content is arranged in alternating text-left/image-right or centered stacks. Card grids are used for features, typically in a 3-column layout. The vertical rhythm is spacious, with a consistent 64px `sectionGap` between primary content blocks. Navigation is a sticky top bar with a logo, text links, and two distinct buttons (Sign In, Schedule a demo).

## Agent Prompt Guide

### Quick Color Reference
- text: #30322a (Ink)
- background: #ffffff (White)
- border: #d9deca (Soft Gray)
- accent: #68ef3f (AI Lime)
- primary action: #68ef3f (filled action)

### 3-5 Example Component Prompts
- Create a hero section: Forest Canopy (#122314) background, with the Deep Fade Gradient. Centered headline 'MANAGING CONTRACTS IN THE AGE OF AI' using Ozik font, weight 700, 80px size, -0.010em letter-spacing, white text. Subheading 'Accelerate your contractual processes...' using Aeonik, weight 400, 24px size, Ink (#30322a). Two action buttons below: 'Schedule a demo' as a Primary Filled Button (AI Lime #68ef3f, 28px radius, 12px vertical/20px horizontal padding) and 'Watch a video demo' as a Ghost Button (Dark) (transparent, white text, white 1px border, 28px radius, 12px vertical/20px horizontal padding), separated by 24px horizontal gap.
- Create a pricing tier card: White Canvas (#ffffff) background, 8px border-radius, 40px padding. Heading 'Basic Plan' using Aeonik, weight 600, 24px size, Ink (#30322a). Price '€49/month' using Ozik, weight 700, 56px size, Evergreen Glow (#26a200). Feature list as Aeonik, weight 400, 16px size, Ink (#30322a).
- Create a testimonial section: Light Canvas (#f2f5eb) background. Headline 'What our customers say' using Aeonik, weight 600, 32px size, Ink (#30322a). Testimonial text 'Tomorro has transformed our workflow...' using Instrument Serif, weight 400, 18px size, Dark Olive (#7e8371).
- Create a navigation link: Aeonik font, weight 500, 16px size, Ink (#30322a) color, transparent background.

## Similar Brands

- **Rippling** — Shares a preference for green as a primary accent color, combined with clean, spacious layouts and clear, functional typography in a SaaS context.
- **Webflow** — Exhibits a similar approach to typographic hierarchy, using a bold, tightly-tracked display font for headlines and a versatile sans-serif for body text, alongside a clean, geometric UI.
- **Carta** — Uses a dark green combined with vibrant accents to create a professional yet energetic visual identity, with an emphasis on structured content and clear calls to action.
- **Lattice** — Features a similar light UI with strategic use of color for primary actions and highlights, maintaining a professional and productivity-focused aesthetic with subtle geometric elements.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-forest-canopy: #122314;
  --color-deep-moss: #273f2b;
  --color-ai-lime: #68ef3f;
  --color-dark-olive: #7e8371;
  --color-light-stone: #b7bda5;
  --color-pale-mint: #e7f9dd;
  --color-soft-gray: #d9deca;
  --color-evergreen-glow: #26a200;
  --color-white: #ffffff;
  --color-ink: #30322a;
  --color-carbon: #000000;
  --gradient-carbon: linear-gradient(rgb(0, 0, 0), rgb(39, 63, 43));
  --color-light-canvas: #f2f5eb;
  --color-mid-gray: #d6d6d6;
  --color-ui-gray: #dcdfe3;

  /* Typography — Font Families */
  --font-aeonik: 'Aeonik', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-instrument-serif: 'Instrument Serif', ui-serif, Georgia, Cambria, "Times New Roman", Times, serif;
  --font-ozik: 'Ozik', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.71;
  --tracking-caption: 0.143px;
  --text-body: 14px;
  --leading-body: 1.67;
  --tracking-body: 0.013px;
  --text-heading-sm: 18px;
  --leading-heading-sm: 1.43;
  --tracking-heading-sm: -0.003px;
  --text-heading: 20px;
  --leading-heading: 1.33;
  --tracking-heading: -0.012px;
  --text-heading-lg: 24px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -0.015px;
  --text-display-sm: 32px;
  --leading-display-sm: 1.1;
  --tracking-display-sm: -0.021px;
  --text-display-md: 40px;
  --leading-display-md: 1;
  --tracking-display-md: -0.031px;
  --text-display-lg: 56px;
  --leading-display-lg: 0.9;
  --tracking-display-lg: -0.014px;
  --text-display: 80px;
  --leading-display: 0.86;
  --tracking-display: -0.01px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-128: 128px;
  --spacing-168: 168px;
  --spacing-240: 240px;

  /* Layout */
  --section-gap: 64px;
  --card-padding: 40px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 28px;
  --radius-3xl-3: 32px;
  --radius-3xl-4: 40px;
  --radius-full: 48px;
  --radius-full-2: 64px;
  --radius-full-3: 80px;
  --radius-full-4: 100px;

  /* Named Radii */
  --radius-cards: 8px;
  --radius-links: 20px;
  --radius-badges: 40px;
  --radius-inputs: 24px;
  --radius-buttons: 28px;
  --radius-containers: 16px;

  /* Surfaces */
  --surface-white-canvas: #ffffff;
  --surface-light-canvas-card: #f2f5eb;
  --surface-pale-mint-accent: #e7f9dd;
  --surface-mid-gray-surface: #d6d6d6;
  --surface-forest-canopy-base: #122314;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-forest-canopy: #122314;
  --color-deep-moss: #273f2b;
  --color-ai-lime: #68ef3f;
  --color-dark-olive: #7e8371;
  --color-light-stone: #b7bda5;
  --color-pale-mint: #e7f9dd;
  --color-soft-gray: #d9deca;
  --color-evergreen-glow: #26a200;
  --color-white: #ffffff;
  --color-ink: #30322a;
  --color-carbon: #000000;
  --color-light-canvas: #f2f5eb;
  --color-mid-gray: #d6d6d6;
  --color-ui-gray: #dcdfe3;

  /* Typography */
  --font-aeonik: 'Aeonik', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-instrument-serif: 'Instrument Serif', ui-serif, Georgia, Cambria, "Times New Roman", Times, serif;
  --font-ozik: 'Ozik', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.71;
  --tracking-caption: 0.143px;
  --text-body: 14px;
  --leading-body: 1.67;
  --tracking-body: 0.013px;
  --text-heading-sm: 18px;
  --leading-heading-sm: 1.43;
  --tracking-heading-sm: -0.003px;
  --text-heading: 20px;
  --leading-heading: 1.33;
  --tracking-heading: -0.012px;
  --text-heading-lg: 24px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -0.015px;
  --text-display-sm: 32px;
  --leading-display-sm: 1.1;
  --tracking-display-sm: -0.021px;
  --text-display-md: 40px;
  --leading-display-md: 1;
  --tracking-display-md: -0.031px;
  --text-display-lg: 56px;
  --leading-display-lg: 0.9;
  --tracking-display-lg: -0.014px;
  --text-display: 80px;
  --leading-display: 0.86;
  --tracking-display: -0.01px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-128: 128px;
  --spacing-168: 168px;
  --spacing-240: 240px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 28px;
  --radius-3xl-3: 32px;
  --radius-3xl-4: 40px;
  --radius-full: 48px;
  --radius-full-2: 64px;
  --radius-full-3: 80px;
  --radius-full-4: 100px;
}
```

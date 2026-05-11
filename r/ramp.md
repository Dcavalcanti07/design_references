# Ramp — Style Reference
> Deep Ocean Command Center – a stark, high-contrast control panel set against an endless dark expanse.

**Theme:** dark

The Ramp design system evokes the precision and quiet authority of a financial control panel operating in a deep ocean environment. Its foundation is a dark theme, utilizing a rich `#0c0a08` background and surfaces that progressively lighten to reveal hierarchy, like submerged objects reflecting distant light. Typography, primarily Lausanne, sets a technical yet approachable tone with its clean geometry and a prominent use of 'ss01' font feature, ensuring figures and characters align perfectly. Vibrant yellow accents (`#e4f222`) serve as critical interaction indicators, cutting through the deep blue and near-black neutrals like sonar beacons, guiding the user through complex financial interfaces.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Deep Space Black | `#0c0a08` | `--color-deep-space-black` | Primary page background, base surface for components — establishes the dark theme depth. |
| Pure White | `#ffffff` | `--color-pure-white` | Primary text color, crucial for high contrast readability against dark backgrounds, interactive element text. |
| Ash Gray | `#1a1919` | `--color-ash-gray` | Secondary surface background, used for lifted cards or subtle section breaks against the primary background. |
| Charcoal Black | `#000000` | `--color-charcoal-black` | Illustrative elements, icons, and occasionally deeper backgrounds for visual breaks. |
| Ivory White | `#f4f2f0` | `--color-ivory-white` | Alternate background for specific white-themed cards or content sections, offering high contrast to deep blacks. |
| Slate Gray | `#999ba3` | `--color-slate-gray` | Subtle text, inactive states, faint borders, and muted icons. |
| Iron Gray | `#4d505d` | `--color-iron-gray` | Input field borders, secondary structural elements. |
| Midnight Ink | `#010412` | `--color-midnight-ink` | Subtle shadow color, creating depth on dark surfaces without being stark. |
| Ocean Abyss | `#0b0d1b` | `--color-ocean-abyss` | Darkest button backgrounds, creating a sense of subtle elevation within the dark theme. |
| Silver Mist | `#d2cecb` | `--color-silver-mist` | Light borders and dividers for cards and sections on lighter neutral backgrounds. |
| Sunbeam Yellow | `#e4f222` | `--color-sunbeam-yellow` | Primary calls to action, active navigation indicators, and key interactive elements. Provides strong visual focus. |
| Emerald Green | `#00d638` | `--color-emerald-green` | Success states, positive indicators, and specific illustrative elements. |
| Deep Sea Blue | `#5683d2` | `--color-deep-sea-blue` | Link text, informational elements, and subtle brand accents. |
| Electric Blue | `#0066ff` | `--color-electric-blue` | Interactive elements, graphical accents with high visibility. |
| Blaze Orange | `#ff492c` | `--color-blaze-orange` | Highlighting specific features or drawing attention to warnings. |

## Tokens — Typography

### lausanne — Primary typeface for all UI text, headings, body, and interactive elements. Its custom 'ss01' feature implies a focus on numerical precision and aligned tabular data, critical for a financial platform. · `--font-lausanne`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400, 500
- **Sizes:** 10px, 13px, 14px, 16px, 18px, 20px, 24px, 28px, 40px, 48px, 64px
- **Line height:** 0.74, 1.00, 1.04, 1.05, 1.14, 1.17, 1.20, 1.30, 1.33, 1.38, 1.43, 1.46, 1.50, 1.60
- **Letter spacing:** normal
- **OpenType features:** `"ss01"`
- **Role:** Primary typeface for all UI text, headings, body, and interactive elements. Its custom 'ss01' feature implies a focus on numerical precision and aligned tabular data, critical for a financial platform.

### Arial — Fallback typeface, used sparingly for specific legacy content or embedded imagery text, ensures broad compatibility. · `--font-arial`
- **Substitute:** sans-serif
- **Weights:** 400
- **Sizes:** 14px
- **Line height:** 1.20
- **Letter spacing:** normal
- **OpenType features:** `"ss01"`
- **Role:** Fallback typeface, used sparingly for specific legacy content or embedded imagery text, ensures broad compatibility.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.5 | — | `--text-caption` |
| subheading | 18px | 1.38 | — | `--text-subheading` |
| heading-sm | 24px | 1.33 | — | `--text-heading-sm` |
| heading | 40px | 1.17 | — | `--text-heading` |
| heading-lg | 48px | 1.14 | — | `--text-heading-lg` |
| display | 64px | 1.05 | — | `--text-display` |

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
| 28 | 28px | `--spacing-28` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 52 | 52px | `--spacing-52` |
| 64 | 64px | `--spacing-64` |
| 76 | 76px | `--spacing-76` |
| 128 | 128px | `--spacing-128` |
| 160 | 160px | `--spacing-160` |
| 176 | 176px | `--spacing-176` |

### Border Radius

| Element | Value |
|---------|-------|
| nav | 4px |
| cards | 12px |
| input | 10px |
| buttons | 4px |
| default | 12px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(255, 255, 255, 0.6) 0px 0px 2px 0px inset` | `--shadow-subtle` |

### Layout

- **Section gap:** 24px
- **Card padding:** 24px
- **Element gap:** 8px

## Components

### Primary Call to Action Button
**Role:** Interactive

Filled with Sunbeam Yellow (`#e4f222`), text in Deep Space Black (`#0c0a08`), 6px border-radius, 10px vertical and 20px horizontal padding. This button is for primary actions and immediately draws attention.

### Secondary Ghost Button
**Role:** Interactive

Transparent background, text in Pure White (`#ffffff`), 6px border-radius, 10px vertical and 20px horizontal padding. Used for less prominent actions, maintaining visual hierarchy on dark backgrounds.

### Text Link Button
**Role:** Interactive

Transparent background, text in Pure White (`#ffffff`), no border-radius or padding. Used for inline or subtle actions where minimal visual weight is desired.

### Dark Filled Button
**Role:** Interactive

Filled with Ocean Abyss (`#0b0d1b`), text in Pure White (`#ffffff`), 6px border-radius, 16px all-around padding. Provides a high-contrast interaction button on lighter neutral areas.

### Product Feature Card
**Role:** Display

Background in Ivory White (`#f4f2f0`), 12px border-radius, no box shadow, 0px padding. Used for showcasing product features in a clean, contained block.

### Dark Marketing Card
**Role:** Display

Background in Ocean Abyss (`#0b0d1b`), 12px border-radius, no box shadow, 0px padding. Used for marketing content, offering deep contrast.

### Testimonial Card
**Role:** Display

Background in translucent black (`rgba(33, 33, 33, 0.024)`) on a dark background, 12px border-radius, no box shadow, 0px padding. For displaying social proof or customer stories.

### Outline Card
**Role:** Display

Transparent background, 0px border-radius, 32px vertical and 24px horizontal padding. Used for structural grouping with visible content, without adding a solid background.

### Input Field - Dark Background
**Role:** Interactive

Transparent background, text in Pure White (`#ffffff`), 10px border-radius, 16px horizontal padding. Placeholders are in Slate Gray (`#999ba3`). Used on dark page sections.

### Input Field - Light Background
**Role:** Interactive

Transparent background, text in Deep Space Black (`#0c0a08`), border in translucent black (`rgba(33, 33, 33, 0.1)`), 10px border-radius, 16px horizontal padding. Used on lighter page sections.

### Input Field - Focused/Active
**Role:** Interactive

Transparent background, text in Pure White (`#ffffff`), border in translucent white (`rgba(255, 255, 255, 0.3)`), 10px border-radius, 16px horizontal padding. Indicates active user input field.

## Do's and Don'ts

### Do
- Prioritize text legibility by using Pure White (`#ffffff`) for primary text on Deep Space Black (`#0c0a08`) or Ocean Abyss (`#0b0d1b`) backgrounds.
- Use Sunbeam Yellow (`#e4f222`) exclusively for primary call-to-action buttons and active navigation states to clearly signal interaction points.
- Apply 12px border-radius to all cards and larger container elements for a consistent soft-edged feel.
- Maintain a clear visual hierarchy by utilizing the surface progression: Deep Space Black (`#0c0a08`) for canvas, Ash Gray (`#1a1919`) for elevated cards, and Ocean Abyss (`#0b0d1b`) for interactive elements on dark backgrounds.
- Ensure headings use the 'lausanne' font with its 'ss01' font feature for precise number and character alignment, crucial for financial data.
- Use 8px as the default `elementGap` for consistent spacing between UI elements, reserving smaller increments for fine-tuning dense interfaces.
- For all navigation and buttons, apply a 4px border-radius to create a distinct, slightly softer interaction target.

### Don't
- Do not use Sunbeam Yellow (`#e4f222`) for decorative purposes or non-interactive elements, as it dilutes its primary CTA role.
- Avoid arbitrary color choices; every color must map to a defined role within the palette to maintain cohesion.
- Do not introduce new shadow styles; adhere to the subtle inset white shadow (`rgba(255, 255, 255, 0.6) 0px 0px 2px 0px inset`) for nav and the default no shadows for cards.
- Do not use generic system fonts for primary UI text; always prefer 'lausanne' with its 'ss01' feature for brand consistency and precision.
- Avoid varying component padding; stick to the specified padding for buttons (e.g., 10px vertical, 20px horizontal) and cards (e.g., 24px for outlined cards) to maintain rhythmic spacing.
- Do not use pure black (`#000000`) for extensive text; reserve it for illustrative elements or very specific, high-contrast contexts.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Deep Space Black Canvas | `#0c0a08` | Base canvas for the entire application, providing the foundational dark theme. |
| 1 | Ash Gray Surface | `#1a1919` | Secondary background for card-like elements or subtly elevated sections, adding slight visual depth. |
| 2 | Ocean Abyss Card | `#0b0d1b` | Background for prominent interactive elements and cards that require higher contrast against the canvas. |
| 3 | Translucent Accent | `#21212106` | Highly subtle background tint for specific card variants or overlays, often used on top of other surfaces to create a layered effect. |
| 4 | Ivory White Accent Area | `#f4f2f0` | Background for occasional light sections or specific content cards that require high contrast with dark elements. |

## Elevation

The design system minimizes overt use of shadows, primarily relying on changing background colors of surfaces (Deep Space Black to Ash Gray to Ocean Abyss) and subtle borders to create depth. When shadows are present, they are either an almost imperceptible inset white line on the nav bar or implicitly soft, almost uncolored `box-shadow` values like `Midnight Ink` (`#010412`) to hint at elevation without heavy visual weight.

## Imagery

The site heavily relies on product screenshots and 3D renders. Product screenshots are typically high-fidelity UI captures, often shown on modern devices (laptops, phones) with a clean, focused presentation. 3D renders feature abstract shapes or physical representations of credit cards, using monochromatic or deep-toned palettes that align with the dark theme. Photography is present in customer testimonial sections, showing professionals in office environments, often within a card-like container with rounded corners and muted or natural lighting. Iconography is generally outlined, monochromatic (white on dark, dark on light), with a consistent stroke weight, and serves primarily to explain features rather than purely decorate. The overall density of imagery is balanced, with large hero visuals and then smaller, contained images within feature sections.

## Agent Prompt Guide

### Quick Color Reference
- Primary Text: `#ffffff` (Pure White)
- Page Background: `#0c0a08` (Deep Space Black)
- Primary CTA: `#e4f222` (Sunbeam Yellow)
- Input Border: `#4d505d` (Iron Gray)
- Link Text: `#5683d2` (Deep Sea Blue)

### Example Component Prompts
1. Create a hero section: Full-bleed Deep Space Black background. Headline 'Time is money. Save both.' using 'lausanne' font, 64px, weight 500, Pure White text, line-height 1.05. Subtext 'Easy-to-use corporate cards...' uses 'lausanne' 18px, weight 400, Pure White. Primary button 'Get started for free' is Sunbeam Yellow (`#e4f222`), text Deep Space Black (`#0c0a08`), 6px border-radius, 10px vertical 20px horizontal padding. Input field 'What's your work email?' has transparent background, Pure White text, Iron Gray border, 10px border-radius, 16px horizontal padding.
2. Design a feature card: Use Ivory White (`#f4f2f0`) for the background, 12px border-radius. Headline 'Ramp Intelligence' using 'lausanne' 24px, weight 500, Deep Space Black text. Accent text 'Put Ramp AI to work for you.' using 'lausanne' 14px, weight 400, Deep Space Black. Include a 'Learn more' link in Deep Sea Blue (`#5683d2`). Card padding 0px.
3. Implement a navigation bar: Sticky, 62px height, Deep Space Black background. Logo text 'ramp' in Pure White. Navigation links 'Products', 'Solutions' in Pure White, 'lausanne' 14px, weight 400. 'Sign in' button as transparent background, Pure White text, 6px border-radius, 10px vertical 20px horizontal padding. 'See a demo' button as Sunbeam Yellow (`#e4f222`) background, Deep Space Black text, 6px border-radius, 10px vertical 20px horizontal padding. Apply inset shadow `rgba(255, 255, 255, 0.6) 0px 0px 2px 0px inset`.
4. Construct a testimonial card within a horizontal carousel: Background `rgba(33, 33, 33, 0.024)`, 12px border-radius. Inner padding 32px vertical, 24px horizontal. Text 'Ramp is the only vendor...' in Pure White, 'lausanne' 16px, weight 400. Name 'Brandon Zell' in Pure White, 'lausanne' 14px, weight 500. Include a 'Read customer story' link in Deep Sea Blue (`#5683d2`).

## Similar Brands

- **Stripe** — Shares a sophisticated, dark-themed UI with geometric typography and a focus on financial tools and data visualization, using subtle shifts in dark neutrals for hierarchy.
- **Brex** — Employs a similar modern fintech aesthetic with an emphasis on corporate spend management, utilizing clear, functional typography, and strong accent colors against a generally neutral palette.
- **Mercury** — Features a dark-themed digital banking interface, with a minimalist approach, strong use of custom typography, and clear calls to action, akin to Ramp's precise data presentation.
- **Linear** — While not fintech, it shares a deep dark mode aesthetic, very precise and compact UI elements, and a focus on efficiency and tool-like interaction, which aligns with Ramp's functional clarity.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-deep-space-black: #0c0a08;
  --color-pure-white: #ffffff;
  --color-ash-gray: #1a1919;
  --color-charcoal-black: #000000;
  --color-ivory-white: #f4f2f0;
  --color-slate-gray: #999ba3;
  --color-iron-gray: #4d505d;
  --color-midnight-ink: #010412;
  --color-ocean-abyss: #0b0d1b;
  --color-silver-mist: #d2cecb;
  --color-sunbeam-yellow: #e4f222;
  --color-emerald-green: #00d638;
  --color-deep-sea-blue: #5683d2;
  --color-electric-blue: #0066ff;
  --color-blaze-orange: #ff492c;

  /* Typography — Font Families */
  --font-lausanne: 'lausanne', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.38;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.33;
  --text-heading: 40px;
  --leading-heading: 1.17;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.14;
  --text-display: 64px;
  --leading-display: 1.05;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-52: 52px;
  --spacing-64: 64px;
  --spacing-76: 76px;
  --spacing-128: 128px;
  --spacing-160: 160px;
  --spacing-176: 176px;

  /* Layout */
  --section-gap: 24px;
  --card-padding: 24px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 7.8px;
  --radius-xl: 12px;

  /* Named Radii */
  --radius-nav: 4px;
  --radius-cards: 12px;
  --radius-input: 10px;
  --radius-buttons: 4px;
  --radius-default: 12px;

  /* Shadows */
  --shadow-subtle: rgba(255, 255, 255, 0.6) 0px 0px 2px 0px inset;

  /* Surfaces */
  --surface-deep-space-black-canvas: #0c0a08;
  --surface-ash-gray-surface: #1a1919;
  --surface-ocean-abyss-card: #0b0d1b;
  --surface-translucent-accent: #21212106;
  --surface-ivory-white-accent-area: #f4f2f0;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-deep-space-black: #0c0a08;
  --color-pure-white: #ffffff;
  --color-ash-gray: #1a1919;
  --color-charcoal-black: #000000;
  --color-ivory-white: #f4f2f0;
  --color-slate-gray: #999ba3;
  --color-iron-gray: #4d505d;
  --color-midnight-ink: #010412;
  --color-ocean-abyss: #0b0d1b;
  --color-silver-mist: #d2cecb;
  --color-sunbeam-yellow: #e4f222;
  --color-emerald-green: #00d638;
  --color-deep-sea-blue: #5683d2;
  --color-electric-blue: #0066ff;
  --color-blaze-orange: #ff492c;

  /* Typography */
  --font-lausanne: 'lausanne', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.38;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.33;
  --text-heading: 40px;
  --leading-heading: 1.17;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.14;
  --text-display: 64px;
  --leading-display: 1.05;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-52: 52px;
  --spacing-64: 64px;
  --spacing-76: 76px;
  --spacing-128: 128px;
  --spacing-160: 160px;
  --spacing-176: 176px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 7.8px;
  --radius-xl: 12px;

  /* Shadows */
  --shadow-subtle: rgba(255, 255, 255, 0.6) 0px 0px 2px 0px inset;
}
```

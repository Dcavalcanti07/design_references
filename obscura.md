# Obscura — Style Reference
> Pixelated secure cloud

**Theme:** light

Obscura establishes a distinct visual identity through pixel-art iconography and a vibrant, pixel-orange accent against a soft, light blue canvas. Typography blends approachable sans-serif body text with a blocky, digital headline style, creating a high-contrast hierarchy. Surfaces are predominantly white and softly shadowed, providing a clean stage for the strong branding elements and ensuring content clarity. The overall feel is whimsical yet secure, blending retro-digital aesthetics with modern product design.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Storm Gray | `#232629` | `--color-storm-gray` | Primary text, prominent headings, strong negative space elements and icons |
| Canvas White | `#ffffff` | `--color-canvas-white` | Light text on dark surfaces, inverse labels, and high-contrast captions. Do not promote it to the primary CTA color |
| Steel Gray | `#5c6066` | `--color-steel-gray` | Secondary text, muted links, subtle icon fills, ghost button text |
| Silver Mist | `#989ea4` | `--color-silver-mist` | Tertiary text, helper text, inactive states, subtle borders |
| Sky Blue | `#e3f1fe` | `--color-sky-blue` | Background wash, subtle borders on neutral interactive elements, decorative fills |
| Pixel Orange | `#ff5e24` | `--color-pixel-orange` | Primary action buttons, distinctive headings, brand elements, active states, and emphasis |
| Deep Orange | `#6c3200` | `--color-deep-orange` | Footer background, strong brand accents in low-light contexts |
| Coal Black | `#000000` | `--color-coal-black` | High-contrast icons and decorative fills where maximum intensity is required |
| Highlight Blue | `#2473eb` | `--color-highlight-blue` | Code snippets, highlighted text for informational emphasis |
| Success Green | `#2fa73b` | `--color-success-green` | Green decorative accent for icons, marks, and small graphic details. Use as a supporting accent, not as a status color |
| Light Gray Mist | `#dbced0` | `--color-light-gray-mist` | Subtle button shadows, navigation item shadows for depth minimal elevation |

## Tokens — Typography

### Manrope Variable — The primary text font for all body content, navigation, buttons, and detailed information. Its varied weights offer flexibility for expressing information hierarchy without changing font families, maintaining a coherent, approachable tone. · `--font-manrope-variable`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400, 500, 600, 700, 800
- **Sizes:** 12px, 14px, 16px, 18px
- **Line height:** 1.33, 1.43, 1.50, 1.56, 1.75
- **Letter spacing:** normal
- **Role:** The primary text font for all body content, navigation, buttons, and detailed information. Its varied weights offer flexibility for expressing information hierarchy without changing font families, maintaining a coherent, approachable tone.

### Jersey 10 — The signature display font for headings, giving the brand its distinct pixelated, digital character. Its tight letter spacing and heavy weights are crucial for impact, reinforcing the retro-tech aesthetic. Not for long-form text. · `--font-jersey-10`
- **Substitute:** system-ui, monospace
- **Weights:** 400, 500
- **Sizes:** 36px, 48px, 60px, 72px, 96px
- **Line height:** 0.70, 0.80, 0.85, 1.00, 1.11
- **Letter spacing:** -0.0310em at 96px, -0.0250em at 48px
- **Role:** The signature display font for headings, giving the brand its distinct pixelated, digital character. Its tight letter spacing and heavy weights are crucial for impact, reinforcing the retro-tech aesthetic. Not for long-form text.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.75 | — | `--text-caption` |
| body-sm | 14px | 1.56 | — | `--text-body-sm` |
| body | 16px | 1.5 | — | `--text-body` |
| subheading | 18px | 1.43 | — | `--text-subheading` |
| heading-sm | 36px | 1.11 | — | `--text-heading-sm` |
| heading | 48px | 0.85 | -1.2px | `--text-heading` |
| heading-lg | 60px | 0.8 | -1.5px | `--text-heading-lg` |
| display | 72px | 0.7 | -2.2px | `--text-display` |

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
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 96 | 96px | `--spacing-96` |
| 128 | 128px | `--spacing-128` |
| 192 | 192px | `--spacing-192` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 6px |
| cards | 12px |
| forms | 6px |
| images | 24px |
| buttons | 6px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| xl | `rgba(0, 0, 0, 0.01) 0px 49px 30px 0px, rgba(0, 0, 0, 0.03...` | `--shadow-xl` |
| md | `rgba(15, 34, 52, 0.01) 0px 27px 11px 0px, rgba(15, 34, 52...` | `--shadow-md` |
| subtle | `oklab(1 0 5.96046e-8 / 0.17) 0px 0.5px 0.5px 0.5px inset,...` | `--shadow-subtle` |

### Layout

- **Section gap:** 36px
- **Card padding:** 16px
- **Element gap:** 16px

## Components

### Primary Action Button
**Role:** Main call-to-action button for initiating key user flows.

Filled with Pixel Orange (#ff5e24), with Canvas White (#ffffff) text. Features a 8px border-radius and generous horizontal padding, with padding-left/right at 32px and no vertical padding, implying content-based height. Some instances use 6px radius and 16px horizontal padding.

### Ghost Navigation Button
**Role:** Navigation links or secondary actions within a header or sidebar.

Transparent background with Steel Gray (#5c6066) text. Features a 6px border-radius, with 8px vertical and 16px horizontal padding. A subtle 1px border of oklab(0.266776 -0.00263395 -0.0065749 / 0.1) provides a ghost-like presence.

### Basic Card (Padded)
**Role:** Default container for content sections, forms, or data displays.

Canvas White (#ffffff) background with 12px border-radius. Features a multi-layered shadow stack, contributing to a soft, elevated look: rgba(15, 34, 52, 0.01) 0px 27px 11px 0px, rgba(15, 34, 52, 0.02) 0px 15px 9px 0px, rgba(15, 34, 52, 0.04) 0px 7px 7px 0px, rgba(15, 34, 52, 0.04) 0px 2px 4px 0px. Content padding is 16px on all sides.

### Elevated Feature Card
**Role:** Prominent content blocks, often for feature highlights or testimonials.

Canvas White (#ffffff) background with a larger 16px border-radius. Features a more pronounced shadow: rgba(0, 0, 0, 0.01) 0px 49px 30px 0px, rgba(0, 0, 0, 0.03) 0px 22px 22px 0px, rgba(0, 0, 0, 0.03) 0px 5px 12px 0px. Vertical padding is 24px and horizontal is 16px.

### Soft Background Card
**Role:** Decorative or informational blocks with a transparent, tinted background.

oklab(0.999994 0.0000455678 0.0000200868 / 0.2) background, providing a subtle off-white tint. Radius of 24px with no shadow. Padding 24px on all sides. Used for sections like 'Manage Account' in the interface screenshot.

### Connected Status Indicator
**Role:** Indicates network connection or successful process completion.

Green checkmark icon with 'Connected to New York, NY' text using Success Green (#2fa73b) for visual confirmation. 'Traffic is protected' is presented in a muted color. Presented within a soft background element (implied by context).

### Neutral Outlined Input/Button
**Role:** Secondary action or form input placeholder.

Transparent background with a 1px border in Sky Blue (#e3f1fe) for visual separation. Text color is Steel Gray (#5c6066). Example 'Disconnect' button.

## Do's and Don'ts

### Do
- Prioritize Pixel Orange (#ff5e24) for all primary calls to action buttons and critical interactive elements.
- Use Manrope Variable for all extensive textual content, adjusting weight between 400 and 700 for hierarchy.
- Employ the Jersey 10 font only for headings and titles, ensuring its distinct pixelated aesthetic is reserved for strong visual statements.
- Maintain a clear layer separation using Canvas White (#ffffff) for surfaces and Sky Blue (#e3f1fe) for subtle background washes.
- Apply elevation shadows consistently, using the lighter rgba(15, 34, 52, 0.04) stack for most cards and the darker rgba(0, 0, 0, 0.03) stack for more prominent elements.
- Round corners with 6px radius for buttons and form elements, and 12px for cards, for a consistent soft geometric feel.
- Ensure all interactive elements have sufficient tap targets, using a minimum of 8px vertical and 16px horizontal padding for buttons.

### Don't
- Avoid using Jersey 10 for body text or any small, functional text sizes due to its pixelated nature and tight kerning.
- Do not introduce new primary accent colors; the Pixel Orange (#ff5e24) is the singular dominant brand accent.
- Do not use heavy, opaque shadows; all shadows should be subtle and transparent to maintain the light and airy aesthetic.
- Avoid arbitrary border-radius values; adhere to the established radii of 6px for interactive elements and 12px/16px for cards.
- Do not use highly saturated photography; imagery should align with the simplified, pixel-art style of the brand.
- Avoid unnecessary large gaps between elements; use the 16px element gap and 36px section gap to maintain a comfortable but not sparse density.
- Do not deviate from the predominantly light theme, even for isolated sections; maintain Canvas White backgrounds for content areas.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Page Canvas | `#e3f1fe` | Dominant page background, providing a soft, light blue base. |
| 1 | Content Surface | `#ffffff` | Primary background for cards, modals, and content blocks. |
| 2 | Elevated Surface | `#ffffff` | Higher-prominence cards and containers with more pronounced shadows. |
| 3 | Decorative Tint | `#00000033` | Subtly tinted transparent backgrounds for specific UI elements. |

## Elevation

- **Card:** `rgba(15, 34, 52, 0.01) 0px 27px 11px 0px, rgba(15, 34, 52, 0.02) 0px 15px 9px 0px, rgba(15, 34, 52, 0.04) 0px 7px 7px 0px, rgba(15, 34, 52, 0.04) 0px 2px 4px 0px`
- **Elevated Card:** `rgba(0, 0, 0, 0.01) 0px 49px 30px 0px, rgba(0, 0, 0, 0.03) 0px 22px 22px 0px, rgba(0, 0, 0, 0.03) 0px 5px 12px 0px`
- **Interactive Element Shadow:** `oklab(1 0 5.96046e-8 / 0.17) 0px 0.5px 0.5px 0.5px inset, oklab(0.598475 0.14309 0.112215 / 0.2) 0px -1px 0.5px 0px inset, rgb(255, 94, 36) 0px 0px 0px 1px`

## Imagery

Imagery features pixel-art style, particularly for cloud motifs and the brand mascot robot. The mascot appears as a contained, blocky, illustration with a friendly expression. Where photography might be used in the product, it is likely contained within UI elements and focused on clean product shots or data visualization. Icons are outlined or filled, with a blocky, pixelated aesthetic (e.g. checkmark) or simple vector style, and minimal stroke weight. Imagery is primarily decorative, setting atmosphere and supporting brand identity.

## Layout

The page uses a full-bleed background set to Sky Blue, with content generally centered and contained within an implied max-width (likely around 1200px based on common practices, but not explicitly defined). The hero section features large, centered pixelated headings, reinforced by pixel-art clouds. Sections feature comfortable vertical spacing (36px general section gap) and often employ 2-column or 3-column layouts for features and marketing content. Cards are prominently used in grid formations. The navigation is a sticky top bar, lightweight in appearance, with a primary call-to-action button anchored to the right.

## Agent Prompt Guide

### Quick Color Reference
text: #232629
background: #e3f1fe
border: #e3f1fe
accent: #ff5e24
primary action: #ff5e24 (filled action)

### 3-5 Example Component Prompts
1. Create a Primary Action Button: #ff5e24 background, #101828 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Design a Feature Card: Canvas White (#ffffff) background, 12px border-radius, with soft shadow rgba(15, 34, 52, 0.04) 0px 2px 4px 0px (and its full stack). Internal padding 16px. Title in Manrope Variable 600 weight, 18px subheading, Storm Gray (#232629). Body text in Manrope Variable 400 weight, 16px body, Steel Gray (#5c6066).
3. Create a Navigation Item: Text 'Features' in Manrope Variable 400 weight, 16px body, Steel Gray (#5c6066). Transparent background. On hover, apply a 1px border of oklab(0.266776 -0.00263395 -0.0065749 / 0.1) and a subtle inset shadow `oklab(1 0 5.96046e-8 / 0.17) 0px 0.5px 0.5px 0.5px inset`.

## Similar Brands

- **ProtonVPN** — Focus on privacy and security with a clean, functional UI, though Obscura adds a distinct pixel-art whimsy.
- **NordVPN** — Similar product category with a strong brand identity and clear call-to-action focus, using vibrant, simple iconography.
- **Supabase** — Features a strong brand color used for accents and action, combined with a primarily neutral UI canvas.
- **Linear** — Exemplifies modern SaaS design with a careful balance of functional UI and subtle branding elements, using a restricted color palette.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-storm-gray: #232629;
  --color-canvas-white: #ffffff;
  --color-steel-gray: #5c6066;
  --color-silver-mist: #989ea4;
  --color-sky-blue: #e3f1fe;
  --color-pixel-orange: #ff5e24;
  --color-deep-orange: #6c3200;
  --color-coal-black: #000000;
  --color-highlight-blue: #2473eb;
  --color-success-green: #2fa73b;
  --color-light-gray-mist: #dbced0;

  /* Typography — Font Families */
  --font-manrope-variable: 'Manrope Variable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-jersey-10: 'Jersey 10', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.75;
  --text-body-sm: 14px;
  --leading-body-sm: 1.56;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.43;
  --text-heading-sm: 36px;
  --leading-heading-sm: 1.11;
  --text-heading: 48px;
  --leading-heading: 0.85;
  --tracking-heading: -1.2px;
  --text-heading-lg: 60px;
  --leading-heading-lg: 0.8;
  --tracking-heading-lg: -1.5px;
  --text-display: 72px;
  --leading-display: 0.7;
  --tracking-display: -2.2px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;
  --font-weight-extrabold: 800;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-128: 128px;
  --spacing-192: 192px;

  /* Layout */
  --section-gap: 36px;
  --card-padding: 16px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;

  /* Named Radii */
  --radius-tags: 6px;
  --radius-cards: 12px;
  --radius-forms: 6px;
  --radius-images: 24px;
  --radius-buttons: 6px;

  /* Shadows */
  --shadow-xl: rgba(0, 0, 0, 0.01) 0px 49px 30px 0px, rgba(0, 0, 0, 0.03) 0px 22px 22px 0px, rgba(0, 0, 0, 0.03) 0px 5px 12px 0px;
  --shadow-md: rgba(15, 34, 52, 0.01) 0px 27px 11px 0px, rgba(15, 34, 52, 0.02) 0px 15px 9px 0px, rgba(15, 34, 52, 0.04) 0px 7px 7px 0px, rgba(15, 34, 52, 0.04) 0px 2px 4px 0px;
  --shadow-subtle: oklab(1 0 5.96046e-8 / 0.17) 0px 0.5px 0.5px 0.5px inset, oklab(0.598475 0.14309 0.112215 / 0.2) 0px -1px 0.5px 0px inset, rgb(255, 94, 36) 0px 0px 0px 1px;

  /* Surfaces */
  --surface-page-canvas: #e3f1fe;
  --surface-content-surface: #ffffff;
  --surface-elevated-surface: #ffffff;
  --surface-decorative-tint: #00000033;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-storm-gray: #232629;
  --color-canvas-white: #ffffff;
  --color-steel-gray: #5c6066;
  --color-silver-mist: #989ea4;
  --color-sky-blue: #e3f1fe;
  --color-pixel-orange: #ff5e24;
  --color-deep-orange: #6c3200;
  --color-coal-black: #000000;
  --color-highlight-blue: #2473eb;
  --color-success-green: #2fa73b;
  --color-light-gray-mist: #dbced0;

  /* Typography */
  --font-manrope-variable: 'Manrope Variable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-jersey-10: 'Jersey 10', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.75;
  --text-body-sm: 14px;
  --leading-body-sm: 1.56;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.43;
  --text-heading-sm: 36px;
  --leading-heading-sm: 1.11;
  --text-heading: 48px;
  --leading-heading: 0.85;
  --tracking-heading: -1.2px;
  --text-heading-lg: 60px;
  --leading-heading-lg: 0.8;
  --tracking-heading-lg: -1.5px;
  --text-display: 72px;
  --leading-display: 0.7;
  --tracking-display: -2.2px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-128: 128px;
  --spacing-192: 192px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;

  /* Shadows */
  --shadow-xl: rgba(0, 0, 0, 0.01) 0px 49px 30px 0px, rgba(0, 0, 0, 0.03) 0px 22px 22px 0px, rgba(0, 0, 0, 0.03) 0px 5px 12px 0px;
  --shadow-md: rgba(15, 34, 52, 0.01) 0px 27px 11px 0px, rgba(15, 34, 52, 0.02) 0px 15px 9px 0px, rgba(15, 34, 52, 0.04) 0px 7px 7px 0px, rgba(15, 34, 52, 0.04) 0px 2px 4px 0px;
  --shadow-subtle: oklab(1 0 5.96046e-8 / 0.17) 0px 0.5px 0.5px 0.5px inset, oklab(0.598475 0.14309 0.112215 / 0.2) 0px -1px 0.5px 0px inset, rgb(255, 94, 36) 0px 0px 0px 1px;
}
```

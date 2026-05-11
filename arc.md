# Arc — Style Reference
> Deepwater + refined minimalism

**Theme:** dark

Arc Boats presents as an aspirational, understated luxury brand. Its visual system relies on a near-monochromatic palette dominated by deep muted greens and off-white, acting as a backdrop for high-quality product photography. Typography is compact and precise, conveying an aura of quiet confidence rather than boisterous marketing. Surfaces are mostly flat, with subtle rounded corners and minimal elevation, allowing hero imagery to take center stage. The overall effect is sophisticated and restrained, emphasizing the product's inherent quality.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Deepwater Teal | `#031e25` | `--color-deepwater-teal` | Primary background for hero and large content blocks, providing a sophisticated and deep base for product presentation and white typography. Also used for dark text on lighter surfaces |
| Canvas | `#e5e7eb` | `--color-canvas` | Primary background for secondary sections and general content areas, offering a muted, light canvas. Used for subtle borders and dividers |
| Ink Black | `#0a0a0a` | `--color-ink-black` | Primary headings, body text, and icon fills on light surfaces. Do not promote it to the primary CTA color |
| Pure White | `#ffffff` | `--color-pure-white` | Primary text color for dark backgrounds, button fills, and secondary surface elements |
| Soft Gray | `#666d75` | `--color-soft-gray` | Placeholder text color inside inputs |

## Tokens — Typography

### Soehne — The sole typeface, used across all text elements from headings to body copy. Its custom nature lends a unique, premium feel. Varied letter-spacing at different sizes creates a distinctive typographic rhythm, from slightly compressed bold headlines to expanded small caps for emphasis. · `--font-soehne`
- **Substitute:** Inter
- **Weights:** 300, 400, 500, 600
- **Sizes:** 11px, 12px, 14px, 16px, 18px, 22px, 32px, 48px, 140px
- **Line height:** 1.00, 1.30, 1.33, 1.44, 1.95
- **Letter spacing:** -0.0430em, -0.0210em, -0.0160em, -0.0120em, -0.0100em, 0.1500em, 0.1800em, 0.1850em
- **Role:** The sole typeface, used across all text elements from headings to body copy. Its custom nature lends a unique, premium feel. Varied letter-spacing at different sizes creates a distinctive typographic rhythm, from slightly compressed bold headlines to expanded small caps for emphasis.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 11px | 1.44 | 2.22px | `--text-caption` |
| body | 14px | 1.44 | -0.2px | `--text-body` |
| subheading | 18px | 1.33 | -0.32px | `--text-subheading` |
| heading-sm | 22px | 1.33 | -0.35px | `--text-heading-sm` |
| heading | 32px | 1.3 | -0.51px | `--text-heading` |
| heading-lg | 48px | 1.3 | -0.77px | `--text-heading-lg` |
| display | 140px | 1 | 2.6px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 5 | 5px | `--spacing-5` |
| 6 | 6px | `--spacing-6` |
| 9 | 9px | `--spacing-9` |
| 10 | 10px | `--spacing-10` |
| 14 | 14px | `--spacing-14` |
| 18 | 18px | `--spacing-18` |
| 20 | 20px | `--spacing-20` |
| 30 | 30px | `--spacing-30` |
| 36 | 36px | `--spacing-36` |
| 45 | 45px | `--spacing-45` |
| 72 | 72px | `--spacing-72` |
| 80 | 80px | `--spacing-80` |
| 81 | 81px | `--spacing-81` |
| 100 | 100px | `--spacing-100` |
| 215 | 215px | `--spacing-215` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 32px |
| inputs | 5px |
| buttons | 5px |
| navigation | 2.25px |
| ghost-buttons | 6.75px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| md | `rgba(0, 0, 0, 0.05) 0px 10px 15px -3px` | `--shadow-md` |

### Layout

- **Section gap:** 36px
- **Card padding:** 20px
- **Element gap:** 20px

## Components

### Primary Filled Button
**Role:** Primary action button for key conversions.

Filled with Pure White (#ffffff) background, Ink Black (#0a0a0a) text. Border radius of 5px. Padding is 0px vertical, 20px horizontal.

### Outline Ghost Button
**Role:** Secondary action or navigational buttons.

Transparent background with Ink Black (#0a0a0a) text. Border color is Canvas (#e5e7eb). Border radius of 6.75px. Padding is 0px.

### Full-Width Ghost Button
**Role:** Large secondary actions often found in hero sections.

Transparent background, Ink Black (#0a0a0a) text. Border color is Canvas (#e5e7eb). No border radius. Padding is 100px vertical.

### Text Input (with placeholder)
**Role:** Standard user input fields.

Background color is rgba(102, 109, 117, 0.06), text color is Ink Black (#0a0a0a). Placeholder text uses Soft Gray (#666d75). Border radius of 5px 0px 0px 5px. Padding is 0px vertical, 20px horizontal.

### Product Feature Card
**Role:** Used to showcase product features with imagery and text.

Likely uses a Deepwater Teal (#031e25) background with Pure White (#ffffff) text. Features a large border radius of 32px for a soft container feel.

## Do's and Don'ts

### Do
- Use Deepwater Teal (#031e25) for backgrounds that need to feel expansive and luxurious, especially for product hero sections.
- Apply Canvas (#e5e7eb) as the default background for general content areas to maintain a light, airy feel.
- Utilize the Soehne typeface consistently across all text, emphasizing its subtle variations in letter-spacing for different roles.
- Implement 5px border radius for all interactive elements like buttons and inputs to introduce a soft, consistent tactile quality.
- Pair Pure White (#ffffff) text with Deepwater Teal (#031e25) backgrounds for optimal contrast in main headings and calls to action.
- For subtle borders and dividers, use Canvas (#e5e7eb) as a soft touch that doesn't overtly interrupt the visual flow.
- Prioritize high-quality product photography as the primary visual interest, allowing the UI to remain understated.

### Don't
- Avoid using saturated or vibrant colors that would detract from the muted, sophisticated brand palette.
- Do not introduce strong drop shadows beyond the subtle hero shadow; elevation should be minimal or absent.
- Refrain from using system default fonts; Soehne is a core brand identifier.
- Do not clutter layouts with excessive UI elements; preserve ample whitespace and comfortable density.
- Avoid harsh, sharp corners; favor the established radii of 5px and 32px for buttons and cards respectively.
- Do not use generic stock photography; all imagery should be high-fidelity representations of Arc products or related marine environments.
- Do not use letter-spacing outside the defined values for Soehne; the specific tracking is integral to the typographic identity.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Deepwater Canvas | `#031e25` | Base background for dark-themed sections like hero and feature cards. |
| 1 | Light Canvas | `#e5e7eb` | Default background for lighter content sections, providing visual separation. |
| 2 | Input Fill | `#666d75` | Slightly darker fill for input fields on light backgrounds. |

## Elevation

- **Hero Section:** `rgba(0, 0, 0, 0.05) 0px 10px 15px -3px`

## Imagery

The site heavily features high-quality, aspirational photography focused on Arc boats within natural water environments. Photography is often full-bleed in hero sections, creating immersive visual experiences. Product shots are meticulously composed, highlighting the sleek design of the boats. There are also detailed interior shots showcasing onboard technology, emphasizing a premium and integrated experience. Visuals serve primarily to evoke atmosphere and showcase the product, rather than to explain complex concepts. Icons are minimal, likely outlined and monochromatic, aligning with the clean UI.

## Layout

The page primarily uses a full-bleed layout for hero sections, which establish an immediate immersive experience. Subsequent content sections alternate between Deepwater Teal (#031e25) and Canvas (#e5e7eb) backgrounds, creating a clear visual rhythm. Content is generally contained within a comfortable width, often centered or presented in balanced two-column text+image layouts. Feature sections frequently use three-column card grids. Navigation is a minimalist top bar, likely sticky, integrating seamlessly into the full-bleed hero. Overall density is comfortable with generous vertical spacing between sections.

## Agent Prompt Guide

Quick Color Reference:
text: #0a0a0a
background: #e5e7eb
border: #e5e7eb
accent: no distinct accent color
primary action: no distinct CTA color

Example Component Prompts:
1. Create a hero section: Deepwater Teal (#031e25) background. Headline 'Electrifying the marine industry' at 48px Soehne weight 600, Pure White (#ffffff), letter-spacing -0.77px. Below, two Primary Filled Buttons 'RECREATION' and 'COMMERCIAL': Pure White (#ffffff) background, Ink Black (#0a0a0a) text, 5px radius. Add a subtle shadow: rgba(0, 0, 0, 0.05) 0px 10px 15px -3px.
2. Create a product feature card: Deepwater Teal (#031e25) background, Pure White (#ffffff) text. Use Soehne 18px weight 500 caption text with a letter-spacing of -0.32px. Use a 32px border radius. Include a small, subtle Outline Ghost Button 'View More' with Ink Black (#0a0a0a) text, Canvas (#e5e7eb) border, and 6.75px radius.
3. Create a navigation bar: Deepwater Teal (#031e25) background. Nav links 'SPORT', 'COAST', 'COMMERCIAL' use Soehne 14px weight 400, Pure White (#ffffff) with a letter-spacing of 0.25px. Logo uses Pure White (#ffffff). The navigation menu icon is Pure White (#ffffff).

## Similar Brands

- **Rivian** — Shares a monochromatic color palette, emphasis on high-quality product photography, and a sophisticated, understated UI to convey luxury and innovation in a new electrification market.
- **Away (luggage)** — Uses a clean, minimalist aesthetic with a dominant neutral palette and subtle branding to present a premium product, relying on strong photography and clear typography.
- **Lucid Motors** — Exhibits a similar design language around electric luxury, with a focus on immersive visuals, refined typography, and a subdued color scheme that lets the product shine.
- **Watermark (marine)** — Utilizes rich water-themed imagery and a focus on premium experiences, pairing elegant typography with a clean, uncrowded layout, mirroring Arc's immersive product presentation.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-deepwater-teal: #031e25;
  --color-canvas: #e5e7eb;
  --color-ink-black: #0a0a0a;
  --color-pure-white: #ffffff;
  --color-soft-gray: #666d75;

  /* Typography — Font Families */
  --font-soehne: 'Soehne', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.44;
  --tracking-caption: 2.22px;
  --text-body: 14px;
  --leading-body: 1.44;
  --tracking-body: -0.2px;
  --text-subheading: 18px;
  --leading-subheading: 1.33;
  --tracking-subheading: -0.32px;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1.33;
  --tracking-heading-sm: -0.35px;
  --text-heading: 32px;
  --leading-heading: 1.3;
  --tracking-heading: -0.51px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.3;
  --tracking-heading-lg: -0.77px;
  --text-display: 140px;
  --leading-display: 1;
  --tracking-display: 2.6px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-9: 9px;
  --spacing-10: 10px;
  --spacing-14: 14px;
  --spacing-18: 18px;
  --spacing-20: 20px;
  --spacing-30: 30px;
  --spacing-36: 36px;
  --spacing-45: 45px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-81: 81px;
  --spacing-100: 100px;
  --spacing-215: 215px;

  /* Layout */
  --section-gap: 36px;
  --card-padding: 20px;
  --element-gap: 20px;

  /* Border Radius */
  --radius-sm: 2.25px;
  --radius-md: 5px;
  --radius-xl: 13.5px;
  --radius-2xl: 18px;
  --radius-3xl: 32px;

  /* Named Radii */
  --radius-cards: 32px;
  --radius-inputs: 5px;
  --radius-buttons: 5px;
  --radius-navigation: 2.25px;
  --radius-ghost-buttons: 6.75px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.05) 0px 10px 15px -3px;

  /* Surfaces */
  --surface-deepwater-canvas: #031e25;
  --surface-light-canvas: #e5e7eb;
  --surface-input-fill: #666d75;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-deepwater-teal: #031e25;
  --color-canvas: #e5e7eb;
  --color-ink-black: #0a0a0a;
  --color-pure-white: #ffffff;
  --color-soft-gray: #666d75;

  /* Typography */
  --font-soehne: 'Soehne', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.44;
  --tracking-caption: 2.22px;
  --text-body: 14px;
  --leading-body: 1.44;
  --tracking-body: -0.2px;
  --text-subheading: 18px;
  --leading-subheading: 1.33;
  --tracking-subheading: -0.32px;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1.33;
  --tracking-heading-sm: -0.35px;
  --text-heading: 32px;
  --leading-heading: 1.3;
  --tracking-heading: -0.51px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.3;
  --tracking-heading-lg: -0.77px;
  --text-display: 140px;
  --leading-display: 1;
  --tracking-display: 2.6px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-9: 9px;
  --spacing-10: 10px;
  --spacing-14: 14px;
  --spacing-18: 18px;
  --spacing-20: 20px;
  --spacing-30: 30px;
  --spacing-36: 36px;
  --spacing-45: 45px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-81: 81px;
  --spacing-100: 100px;
  --spacing-215: 215px;

  /* Border Radius */
  --radius-sm: 2.25px;
  --radius-md: 5px;
  --radius-xl: 13.5px;
  --radius-2xl: 18px;
  --radius-3xl: 32px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.05) 0px 10px 15px -3px;
}
```

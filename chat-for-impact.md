# Chat for impact — Style Reference
> WhatsApp chat through a forest canvas

**Theme:** mixed

Turn.io employs a messaging-forward design, blending dark and light themes with a strong focus on a vibrant green and orange. The visual system pairs clean, modern typography with soft, rounded corners for interactive elements and cards, creating a friendly yet authoritative product aesthetic. Layouts use clear visual segmentation, often leveraging color blocks to delineate content areas and highlight key information. Color appears functionally, guiding user attention and establishing brand identity across the interface.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Forest Canopy | `#0a3922` | `--color-forest-canopy` | Hero background, prominent section backgrounds, deep green accent for various elements. Conveys growth and trust |
| Vivid Green | `#1dbf73` | `--color-vivid-green` | Green outline accent for tags, dividers, and focused UI edges |
| Sunset Orange | `#ff643b` | `--color-sunset-orange` | Primary call-to-action button background. Commands attention with warmth and urgency |
| Deep Violet | `#460095` | `--color-deep-violet` | Violet outline accent for tags, dividers, and focused UI edges. Do not promote it to the primary CTA color |
| Misty Rose | `#47264c` | `--color-misty-rose` | Muted background tones, secondary accents. Adds a subtle, complementary warmth |
| Sky Blue | `#00b4dc` | `--color-sky-blue` | Supportive accent, informational highlights. Suggests clarity and technology |
| Midnight Teal | `#003642` | `--color-midnight-teal` | Dark text for headlines on light backgrounds, subtle accent colors. Provides a deep, authoritative tone |
| Lavender Mist | `#eee2ff` | `--color-lavender-mist` | Light background fill, card backgrounds on light sections. Softens the overall palette |
| Pale Mint | `#d2f2e3` | `--color-pale-mint` | Light background fill, card backgrounds on light sections. Fresh and airy |
| Sky Haze | `#ccf0f8` | `--color-sky-haze` | Light background fill for subtle distinctions. Adds a cool, refreshing touch |
| Leafy Green | `#e4f7ee` | `--color-leafy-green` | Light card backgrounds, supportive informational panels. Natural and calming |
| Pitch Black | `#000000` | `--color-pitch-black` | Primary text, critical icons, strong borders. Provides maximum contrast and legibility |
| Snowdrift | `#ffffff` | `--color-snowdrift` | Page backgrounds, card surfaces, text on dark backgrounds. Acts as a clean canvas |
| Ash Gray | `#a6a6a6` | `--color-ash-gray` | Secondary text, muted links, subtle borders. Softens text hierarchy and delineation |
| Muted Slate | `#7a7a7a` | `--color-muted-slate` | Body text, helper text, less prominent UI elements. Creates a softer textual presence than Pitch Black |
| Charcoal Gray | `#3d3d3d` | `--color-charcoal-gray` | Darker body text, icon fills. Provides slightly less stark contrast than Pitch Black |
| Off White | `#f2f2f2` | `--color-off-white` | Subtle card backgrounds, section breaks. Provides a very gentle contrast with pure white |
| Pale Linen | `#f4ece9` | `--color-pale-linen` | Card backgrounds, section separators. A warm, almost peach-tinted neutral surface |

## Tokens — Typography

### DM Sans — The primary typeface for all text. Its slightly condensed forms with distinctive 'a' and 'g' (via ss03) give it a modern, efficient, and friendly feel, supporting both expansive headlines and compact body text without feeling rigid. Varied weights and negative letter-spacing for larger sizes contribute to its confident and dynamic expression. · `--font-dm-sans`
- **Substitute:** system-ui
- **Weights:** 400, 500, 600, 700
- **Sizes:** 12px, 14px, 16px, 18px, 20px, 24px, 32px, 48px, 52px, 69px, 72px, 80px, 116px
- **Line height:** 0.89, 1.00, 1.05, 1.10, 1.14, 1.17, 1.20, 1.30, 1.33, 1.38, 1.40
- **Letter spacing:** -0.0280em, -0.0190em
- **OpenType features:** `"ss03"`
- **Role:** The primary typeface for all text. Its slightly condensed forms with distinctive 'a' and 'g' (via ss03) give it a modern, efficient, and friendly feel, supporting both expansive headlines and compact body text without feeling rigid. Varied weights and negative letter-spacing for larger sizes contribute to its confident and dynamic expression.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.4 | — | `--text-caption` |
| body-sm | 14px | 1.4 | — | `--text-body-sm` |
| body | 16px | 1.4 | — | `--text-body` |
| subheading | 18px | 1.3 | — | `--text-subheading` |
| heading-sm | 24px | 1.2 | — | `--text-heading-sm` |
| heading | 32px | 1.2 | — | `--text-heading` |
| heading-lg | 48px | 1.17 | -1.344px | `--text-heading-lg` |
| display-sm | 52px | 1.1 | -1.456px | `--text-display-sm` |
| display | 69px | 1.05 | -1.932px | `--text-display` |

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
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 120 | 120px | `--spacing-120` |

### Border Radius

| Element | Value |
|---------|-------|
| badge | 9999px |
| cards | 24px |
| input | 8px |
| small | 2px |
| medium | 16px |
| buttons | 40px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(0, 0, 0, 0.05) 0px 1px 1px 0px` | `--shadow-subtle` |

### Layout

- **Section gap:** 40px
- **Card padding:** 30px
- **Element gap:** 8px

## Components

### Primary Action Button
**Role:** Calls to action, booking a call.

Filled with Sunset Orange (#ff643b) background, Pitch Black (#000000) text, and a generous 40px border-radius, creating a prominent oval shape. Padding is 21.5px vertical and 32px horizontal. DM Sans 500 weight.

### Secondary Action Button
**Role:** Less prominent actions, tour links.

Ghost button with Snowdrift (#ffffff) background, Pitch Black (#000000) text, and 40px border-radius matching the primary action button. Padding is 13.44px vertical and 24px horizontal. DM Sans 500 weight.

### Info Card
**Role:** Content sections, feature displays.

Light background fill of Off White (#f2f2f2) or Pale Mint (#e4f7ee), with a soft 24px border-radius and generous 30px padding on all sides. No shadow, creating a flat, modern surface.

### Interactive Chip
**Role:** Small, clickable elements or tags in a card.

Backgrounds use Pale Mint (#e4f7ee) for a subtle highlight, with a 16px border-radius. Padding is implicit for concise elements.

### Content Block Indicator
**Role:** Decorative or progress indicators within content cards.

Small circular elements (50% border-radius) with backgrounds of Deep Violet (#460095) or Forest Canopy (#0a3922), used functionally within section cards.

## Do's and Don'ts

### Do
- Use Forest Canopy (#0a3922) as the background for hero sections and other visually prominent areas.
- Apply 40px border-radius for all primary and secondary action buttons to maintain a rounded, friendly aesthetic.
- Employ DM Sans with its specific 'ss03' font feature settings for all typography to capture the unique character.
- Maintain a clear visual hierarchy by using Off White (#f2f2f2), Lavender Mist (#eee2ff), Pale Mint (#d2f2e3), and Pale Linen (#f4ece9) for card and section backgrounds on light themes, and Forest Canopy (#0a3922), Deep Violet (#460095) on dark themes.
- Prioritize Sunset Orange (#ff643b) for primary call-to-action buttons to ensure high visibility and interaction.
- Use a generous 30px padding for Info Card content to ensure readability and spaciousness.
- Employ Pitch Black (#000000) for primary text on light backgrounds and Snowdrift (#ffffff) for primary text on dark backgrounds for clear contrast.

### Don't
- Do not introduce sharp corners; always use the specified border radii for interactive elements (40px) and cards (24px/16px).
- Avoid using generic blue for actions; Sunset Orange (#ff643b) is reserved for the primary CTA, use other brand colors for secondary interactive elements if needed.
- Do not deviate from the DM Sans typeface; it is fundamental to the brand's typographic identity.
- Avoid excessive use of vivid chromatic colors outside of their defined roles as accents or primary actions; maintain a largely neutral surface palette.
- Do not apply heavy drop shadows; elevation is minimal, typically relying on background color shifts and subtle rgba(0, 0, 0, 0.05) 0px 1px 1px 0px shadows.
- Do not use letter-spacing other than the specified -0.0280em or -0.0190em for display text, or normal spacing for body text.
- Avoid mixing surface backgrounds from the light theme palette into dark theme sections, and vice-versa, to maintain consistent theme distinction.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Snowdrift | `#ffffff` | Primary page background for light sections. |
| 1 | Lavender Mist | `#eee2ff` | A slightly elevated background for distinct light sections or primary content zones. |
| 2 | Off White | `#f2f2f2` | Card background on light sections, providing a subtle elevation from the base canvas. |
| 3 | Pale Mint | `#e4f7ee` | Specific card background for feature blocks or interactive elements, offering a fresh accent color. |
| 0 | Forest Canopy | `#0a3922` | Primary page background for dark sections, especially hero and impactful areas. |
| 1 | Deep Violet | `#460095` | Elevated background for distinct dark content blocks, offering a rich contrast. |
| 2 | Misty Rose | `#47264c` | Subtle background for specific dark cards or nested elements within a dark section. |

## Elevation

- **Card:** `rgba(0, 0, 0, 0.05) 0px 1px 1px 0px`

## Imagery

The site uses a mix of real photography and product screenshots. Photography is lifestyle-oriented, featuring diverse people interacting with technology, often with warm, natural lighting. Product screenshots are clean, showcasing the WhatsApp interface with custom chat bubbles and clear text, often within a phone frame. Icons are outlined, simple, and mono-colored, complementing the clean UI. Imagery serves both explanatory and atmospheric roles, showing the product in use and its human impact. The density is moderate, balancing visual explanations with textual content.

## Layout

The page primarily uses a max-width contained layout, with content centered. The hero section is full-bleed, using a dark Forest Canopy background with a commanding, left-aligned headline. Sections alternate between dark and light backgrounds, creating a clear visual rhythm. Content often arranges in two-column layouts, pairing text with product screenshots or subtle visual elements. Cards are used to break down features, typically in a grid or prominent stacked individual blocks, maintaining consistent vertical spacing.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #ffffff
border: #000000
accent: #1dbf73
primary action: #ff643b (filled action)

Example Component Prompts:
Create a Primary Action Button: #ff643b background, #000000 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.

Create an Info Card: 'Off White' (#f2f2f2) background, 24px border-radius, 30px padding. Headline 'Automate Engagement' at 24px DM Sans weight 700, 'Pitch Black' (#000000). Body text 'Seamlessly connect with your users through intelligent automation flows.' at 16px DM Sans weight 400, 'Ash Gray' (#a6a6a6).

Create a Secondary Action Button: 'Snowdrift' (#ffffff) background, 'Pitch Black' (#000000) text, 40px border-radius, 13.44px vertical padding, 24px horizontal padding and DM Sans 500 weight.

## Similar Brands

- **Typeform** — Uses a similar approach with rounded, friendly UI elements and distinct color blocks for sections.
- **Intercom** — Combines rich, saturated brand colors with clean typography and approachable feature card layouts.
- **Loom** — Features strong brand color accents against largely neutral UI, with rounded interactive components.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-forest-canopy: #0a3922;
  --color-vivid-green: #1dbf73;
  --color-sunset-orange: #ff643b;
  --color-deep-violet: #460095;
  --color-misty-rose: #47264c;
  --color-sky-blue: #00b4dc;
  --color-midnight-teal: #003642;
  --color-lavender-mist: #eee2ff;
  --color-pale-mint: #d2f2e3;
  --color-sky-haze: #ccf0f8;
  --color-leafy-green: #e4f7ee;
  --color-pitch-black: #000000;
  --color-snowdrift: #ffffff;
  --color-ash-gray: #a6a6a6;
  --color-muted-slate: #7a7a7a;
  --color-charcoal-gray: #3d3d3d;
  --color-off-white: #f2f2f2;
  --color-pale-linen: #f4ece9;

  /* Typography — Font Families */
  --font-dm-sans: 'DM Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.4;
  --text-body-sm: 14px;
  --leading-body-sm: 1.4;
  --text-body: 16px;
  --leading-body: 1.4;
  --text-subheading: 18px;
  --leading-subheading: 1.3;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.2;
  --text-heading: 32px;
  --leading-heading: 1.2;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.17;
  --tracking-heading-lg: -1.344px;
  --text-display-sm: 52px;
  --leading-display-sm: 1.1;
  --tracking-display-sm: -1.456px;
  --text-display: 69px;
  --leading-display: 1.05;
  --tracking-display: -1.932px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

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
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-120: 120px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 30px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 40px;

  /* Named Radii */
  --radius-badge: 9999px;
  --radius-cards: 24px;
  --radius-input: 8px;
  --radius-small: 2px;
  --radius-medium: 16px;
  --radius-buttons: 40px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.05) 0px 1px 1px 0px;

  /* Surfaces */
  --surface-snowdrift: #ffffff;
  --surface-lavender-mist: #eee2ff;
  --surface-off-white: #f2f2f2;
  --surface-pale-mint: #e4f7ee;
  --surface-forest-canopy: #0a3922;
  --surface-deep-violet: #460095;
  --surface-misty-rose: #47264c;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-forest-canopy: #0a3922;
  --color-vivid-green: #1dbf73;
  --color-sunset-orange: #ff643b;
  --color-deep-violet: #460095;
  --color-misty-rose: #47264c;
  --color-sky-blue: #00b4dc;
  --color-midnight-teal: #003642;
  --color-lavender-mist: #eee2ff;
  --color-pale-mint: #d2f2e3;
  --color-sky-haze: #ccf0f8;
  --color-leafy-green: #e4f7ee;
  --color-pitch-black: #000000;
  --color-snowdrift: #ffffff;
  --color-ash-gray: #a6a6a6;
  --color-muted-slate: #7a7a7a;
  --color-charcoal-gray: #3d3d3d;
  --color-off-white: #f2f2f2;
  --color-pale-linen: #f4ece9;

  /* Typography */
  --font-dm-sans: 'DM Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.4;
  --text-body-sm: 14px;
  --leading-body-sm: 1.4;
  --text-body: 16px;
  --leading-body: 1.4;
  --text-subheading: 18px;
  --leading-subheading: 1.3;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.2;
  --text-heading: 32px;
  --leading-heading: 1.2;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.17;
  --tracking-heading-lg: -1.344px;
  --text-display-sm: 52px;
  --leading-display-sm: 1.1;
  --tracking-display-sm: -1.456px;
  --text-display: 69px;
  --leading-display: 1.05;
  --tracking-display: -1.932px;

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
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-120: 120px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 40px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.05) 0px 1px 1px 0px;
}
```

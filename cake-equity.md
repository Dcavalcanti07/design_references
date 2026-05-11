# Cake Equity — Style Reference
> precision ledger on a clean slate

**Theme:** light

Cake Equity's visual system evokes a precise, supportive atmosphere with a foundation of stark neutrals and a vibrant, warm purple accent. Clean surfaces and intentional use of border radii define interactive elements and containers. Typography is confident and direct, emphasizing clear information hierarchy, while a bright lime green and soft blue punctuate feature areas.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#18161a` | `--color-midnight-ink` | Primary text, strong headings, dark backgrounds for contrast, outlines |
| Polar White | `#ffffff` | `--color-polar-white` | Page backgrounds, card surfaces, button text against saturated colors |
| Cloud Gray | `#fafaf8` | `--color-cloud-gray` | Subtle section backgrounds, alternative card background |
| Stone Slate | `#333333` | `--color-stone-slate` | Secondary text, icon fills, subtle borders |
| Ash Mist | `#898b91` | `--color-ash-mist` | Muted text, subtle borders, inactive states |
| Lilac Gray | `#ede9ff` | `--color-lilac-gray` | Card borders, subtle decorative accents |
| Lavender Hue | `#d9d2ff` | `--color-lavender-hue` | Decorative borders, subtle UI element outlining |
| Plum Royal | `#4823ff` | `--color-plum-royal` | Primary action buttons, prominent links, interactive highlights — establishes brand action |
| Vivid Violet | `#6d67fb` | `--color-vivid-violet` | Accent text within headlines, active navigation indicators |
| Soft Indigo | `#7e78ff` | `--color-soft-indigo` | Subtle background for UI elements, inactive states |
| Lime Spritz | `#e7ff6e` | `--color-lime-spritz` | Highlight cards, callout sections — a vibrant, attention-grabbing accent |
| Sky Whisper | `#99cefe` | `--color-sky-whisper` | Subtle background for complementary information panels |
| Pale Plum | `#dfddff` | `--color-pale-plum` | Icon backgrounds, very light decorative fills |
| Sunset Orange | `#ffa360` | `--color-sunset-orange` | Secondary accent for small highlights or decorative elements |
| Phantom Deep Violet | `radial-gradient(circle at 70% 0%, rgb(43, 21, 153), rgba(0, 0, 0, 0))` | `--color-phantom-deep-violet` | Hero background gradient start, providing depth and a premium feel |

## Tokens — Typography

### Plus Jakarta Sans — Hero headlines and significant display text leveraging a single bold weight for impact. The tight letter spacing creates a dense, modern block of text that feels commanding. · `--font-plus-jakarta-sans`
- **Substitute:** Inter
- **Weights:** 700
- **Sizes:** 63px, 77px
- **Line height:** 1.00
- **Letter spacing:** -0.0400em at 77px, -0.0320em at 63px
- **Role:** Hero headlines and significant display text leveraging a single bold weight for impact. The tight letter spacing creates a dense, modern block of text that feels commanding.

### Inter — Body copy, subheadings, navigation, buttons, and all other UI text. A versatile sans-serif used across a broad range of sizes and weights to establish clear hierarchy and readability on a light canvas. Noticeable tight tracking on larger sizes to prevent sprawl. · `--font-inter`
- **Substitute:** system-ui
- **Weights:** 300, 400, 500, 600, 700
- **Sizes:** 11px, 12px, 13px, 14px, 15px, 16px, 17px, 18px, 20px, 22px, 31px
- **Line height:** 0.86, 1.00, 1.10, 1.20, 1.29, 1.30, 1.40, 1.45, 1.50, 1.53, 1.60, 1.80, 2.00
- **Letter spacing:** -0.0450em at 31px, -0.0200em at 20px, -0.0100em at 18px and 22px, normal at 11-17px
- **Role:** Body copy, subheadings, navigation, buttons, and all other UI text. A versatile sans-serif used across a broad range of sizes and weights to establish clear hierarchy and readability on a light canvas. Noticeable tight tracking on larger sizes to prevent sprawl.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 11px | 1.5 | 0.05px | `--text-caption` |
| body-sm | 14px | 1.5 | 0.004px | `--text-body-sm` |
| body | 16px | 1.5 | -0.001px | `--text-body` |
| body-lg | 18px | 1.5 | -0.01px | `--text-body-lg` |
| subheading | 22px | 1.4 | -0.01px | `--text-subheading` |
| heading | 31px | 1.3 | -0.045px | `--text-heading` |
| heading-lg | 63px | 1 | -0.032px | `--text-heading-lg` |
| display | 77px | 1 | -0.04px | `--text-display` |

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
| 36 | 36px | `--spacing-36` |
| 40 | 40px | `--spacing-40` |
| 56 | 56px | `--spacing-56` |
| 60 | 60px | `--spacing-60` |
| 84 | 84px | `--spacing-84` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 999px |
| cards | 20px |
| icons | 50px |
| links | 12px |
| buttons | 100px |
| general | 16px |

### Layout

- **Section gap:** 71px
- **Card padding:** 20px
- **Element gap:** 20px

## Components

### Primary Filled Button
**Role:** Call to action.

Filled button with Plum Royal (#4823ff) background, Polar White (#ffffff) text, and a highly rounded (100px) border-radius. Padding is 12px vertical, 25px horizontal. Uses Inter font.

### Secondary Outlined Button
**Role:** Secondary call to action, ghost buttons.

Ghost button with transparent background, Midnight Ink (#18161a) text and a 1px Midnight Ink border. Rounded (100px) border-radius. Padding 20px vertical, 36px horizontal. Uses Inter font.

### Navigation Link
**Role:** Primary navigation items.

Transparent background, Stone Slate (#333333) text, and 0px border-radius. Minimal padding 5px vertical, 0px horizontal. Uses Inter font.

### Default Card
**Role:** General content container.

Polar White (#ffffff) background, 20px border-radius, no shadow. Internal padding 15px on all sides.

### Highlight Card (Lime Spritz)
**Role:** Promotional or featured content container.

Lime Spritz (#e7ff6e) background, 20px border-radius, no shadow. Internal padding 30px on all sides.

### Subtle Accent Card (Sky Whisper)
**Role:** Informational or complementary content card.

Sky Whisper (#99cefe) background, 20px border-radius, no shadow. Internal padding 20px on all sides.

### Informational Pane (Soft Indigo)
**Role:** Embedded UI panels or data displays.

Soft Indigo (#7e78ff) background with a 10% opacity, 20px border-radius, no shadow. Padding 20px on all sides.

## Do's and Don'ts

### Do
- Prioritize Midnight Ink (#18161a) for all primary text and main headings on light backgrounds.
- Use Plum Royal (#4823ff) exclusively for primary interactive elements, ensuring high contrast with Polar White (#ffffff) text.
- Employ Polar White (#ffffff) as the dominant background color for most sections, cards, and interactive elements for a crisp, legible foundation.
- Apply 20px border-radius to all major containers like cards and image masks, softening their visual presence.
- Ensure buttons maintain a 100px border-radius for a distinct pill-like shape, signalling interactiveness.
- Utilize Plus Jakarta Sans 700 with aggressive letter-spacing for large, impactful headlines to create a condensed, authoritative statement.
- Incorporate Lime Spritz (#e7ff6e) sparingly for intentional highlights or call-to-action cards, preventing overuse that could diminish its impact.

### Don't
- Avoid using multiple chromatic colors for primary actions; Plum Royal (#4823ff) is the singular choice for this purpose.
- Do not introduce complex shadow patterns; maintain a flat or nearly flat aesthetic, with elevation hinted through color changes or subtle outlines.
- Refrain from widely varying border-radius values. Stick to the defined system (20px for cards, 100px for buttons) for visual consistency.
- Do not use dark backgrounds for large content blocks outside of specifically designed hero sections or dark UI panels, as the system relies on a light canvas.
- Avoid decorative images with overly complex compositions or busy backgrounds; prioritize product screenshots or clean illustrations.
- Do not use letter-spacing on small body text, reserving it for larger headings to maintain readability.
- Resist using a strong border on filled buttons; rely on background color for visual distinction of primary actions.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Page Background | `#ffffff` | The foundational canvas for most page content. |
| 2 | Subtle Section Background | `#fafaf8` | Used for alternating content sections and subtle visual separation. |
| 3 | Card Surface | `#ffffff` | Default background for information cards and embedded UI components. |
| 4 | Accent Card Surface | `#e7ff6` | Used for prominent features or call-out sections, providing visual emphasis. |

## Imagery

The site predominantly uses product screenshots and contained abstract graphics. Product screenshots are clean, showcasing UI in context with a focused, minimal framing. Illustrations leverage a flat, organic style, often outlined or with solid brand-colored fills, serving primarily as decorative atmosphere. Icons are filled, with a moderate stroke weight, typically monochrome. The density is image-heavy in feature sections, with graphics playing an explanatory role, showing actual product functionality. Images are contained within defined boundaries, rarely overlapping, and often benefit from the standard 20px border-radius.

## Layout

The page primarily uses a max-width contained model, centered on the screen, creating a focused content area. The hero section follows a split layout, featuring a large headline and supporting text on the left, counterbalanced by a product UI preview on the right, which itself is often a dark-themed card on the light canvas. Section rhythm is marked by consistent vertical spacing, often with alternating light (#fafaf8, #ffffff) and accent-colored (#e7ff6e) backgrounds, creating clear visual breaks. Content arrangement frequently alternates between text-left/visual-right and visual-left/text-right patterns within two-column sections. Card grids are used for features and testimonials. Navigation is a simple top bar with clearly defined links and two distinct button types (ghost and primary filled CTA).

## Agent Prompt Guide

### Quick Color Reference
- text: #18161a
- background: #ffffff
- border: #ede9ff
- accent: #e7ff6e
- primary action: #4823ff (filled action)

### 3-5 Example Component Prompts
- Create a Primary Action Button: #4823ff background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
- Design a feature card: Lime Spritz (#e7ff6e) background, 20px radius, 30px padding. Inside, 'Grow Faster' as a 22px Inter weight 600, #18161a. Body copy at 16px Inter weight 400, #333333, line-height 1.45.

## Similar Brands

- **Rippling** — Similar light, clean canvas with clear surface separation and strong, single-color calls to action.
- **Brex** — Uses a vibrant, singular brand color as a primary accent against a largely achromatic UI, similar to Cake Equity's Plum Royal.
- **Gusto** — Employs a comfortable density in layouts with distinct card elements and clear typography hierarchy on a light background.
- **Carta** — A direct competitor with visual emphasis on product UI screenshots within a clean, professional, and slightly corporate-friendly aesthetic.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #18161a;
  --color-polar-white: #ffffff;
  --color-cloud-gray: #fafaf8;
  --color-stone-slate: #333333;
  --color-ash-mist: #898b91;
  --color-lilac-gray: #ede9ff;
  --color-lavender-hue: #d9d2ff;
  --color-plum-royal: #4823ff;
  --color-vivid-violet: #6d67fb;
  --color-soft-indigo: #7e78ff;
  --color-lime-spritz: #e7ff6e;
  --color-sky-whisper: #99cefe;
  --color-pale-plum: #dfddff;
  --color-sunset-orange: #ffa360;
  --color-phantom-deep-violet: #2b1599;
  --gradient-phantom-deep-violet: radial-gradient(circle at 70% 0%, rgb(43, 21, 153), rgba(0, 0, 0, 0));

  /* Typography — Font Families */
  --font-plus-jakarta-sans: 'Plus Jakarta Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.5;
  --tracking-caption: 0.05px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --tracking-body-sm: 0.004px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.001px;
  --text-body-lg: 18px;
  --leading-body-lg: 1.5;
  --tracking-body-lg: -0.01px;
  --text-subheading: 22px;
  --leading-subheading: 1.4;
  --tracking-subheading: -0.01px;
  --text-heading: 31px;
  --leading-heading: 1.3;
  --tracking-heading: -0.045px;
  --text-heading-lg: 63px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -0.032px;
  --text-display: 77px;
  --leading-display: 1;
  --tracking-display: -0.04px;

  /* Typography — Weights */
  --font-weight-light: 300;
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
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-56: 56px;
  --spacing-60: 60px;
  --spacing-84: 84px;

  /* Layout */
  --section-gap: 71px;
  --card-padding: 20px;
  --element-gap: 20px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-full: 50px;
  --radius-full-2: 100px;
  --radius-full-3: 999px;

  /* Named Radii */
  --radius-tags: 999px;
  --radius-cards: 20px;
  --radius-icons: 50px;
  --radius-links: 12px;
  --radius-buttons: 100px;
  --radius-general: 16px;

  /* Surfaces */
  --surface-page-background: #ffffff;
  --surface-subtle-section-background: #fafaf8;
  --surface-card-surface: #ffffff;
  --surface-accent-card-surface: #e7ff6;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #18161a;
  --color-polar-white: #ffffff;
  --color-cloud-gray: #fafaf8;
  --color-stone-slate: #333333;
  --color-ash-mist: #898b91;
  --color-lilac-gray: #ede9ff;
  --color-lavender-hue: #d9d2ff;
  --color-plum-royal: #4823ff;
  --color-vivid-violet: #6d67fb;
  --color-soft-indigo: #7e78ff;
  --color-lime-spritz: #e7ff6e;
  --color-sky-whisper: #99cefe;
  --color-pale-plum: #dfddff;
  --color-sunset-orange: #ffa360;
  --color-phantom-deep-violet: #2b1599;

  /* Typography */
  --font-plus-jakarta-sans: 'Plus Jakarta Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.5;
  --tracking-caption: 0.05px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --tracking-body-sm: 0.004px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.001px;
  --text-body-lg: 18px;
  --leading-body-lg: 1.5;
  --tracking-body-lg: -0.01px;
  --text-subheading: 22px;
  --leading-subheading: 1.4;
  --tracking-subheading: -0.01px;
  --text-heading: 31px;
  --leading-heading: 1.3;
  --tracking-heading: -0.045px;
  --text-heading-lg: 63px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -0.032px;
  --text-display: 77px;
  --leading-display: 1;
  --tracking-display: -0.04px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-56: 56px;
  --spacing-60: 60px;
  --spacing-84: 84px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-full: 50px;
  --radius-full-2: 100px;
  --radius-full-3: 999px;
}
```

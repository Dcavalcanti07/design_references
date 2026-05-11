# Craft — Style Reference
> Botanical elegance on linen

**Theme:** light

Craft presents a botanical elegance, marrying a muted, organic color palette with sharp, high-contrast typography. The design emphasizes natural greens and soft off-whites as background and text colors, contrasted by a single vibrant green for primary actions. Layouts are spacious, utilizing a comfortable density with ample negative space to allow content to breathe, fostering a calm yet authoritative feel. Visual details like crisp outlines and subtle off-white surfaces blend into a sophisticated, understated aesthetic.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Ink Bark | `#2a1a1d` | `--color-ink-bark` | Primary text, strong headings, button outlines on light backgrounds, dark accent borders that define content blocks |
| Night Forest | `#1d3023` | `--color-night-forest` | Dark borders and separators for elevated surfaces and inverted UI. Do not promote it to the primary CTA color |
| Deep Moss | `#0e634f` | `--color-deep-moss` | Accent text for financial figures or key statistics, decorative borders in specific content areas |
| Garden Sprout | `#26d862` | `--color-garden-sprout` | Primary action button backgrounds, vivid highlights for interactive elements, accent for navigation hovers and titles within specific data blocks |
| Linen Mist | `#eae6df` | `--color-linen-mist` | Subtle background for UI elements, borders for ghost buttons, secondary text in specific contexts |
| Parchment White | `#f7f5f2` | `--color-parchment-white` | Dominant page background, card surfaces, pristine nav backgrounds |
| Ash Taupe | `#504344` | `--color-ash-taupe` | Muted headings, specific border colors for content separation |
| Cloud Cement | `#d7d2cc` | `--color-cloud-cement` | Lightest separator lines, soft borders for structural elements |
| Stone Slate | `#645757` | `--color-stone-slate` | Body text for secondary content, subtle borders in various components |

## Tokens — Typography

### ABC Arizona Flare Variable — Primary body text, navigation items, secondary headings, and general interface text. The subtle variations in weight and letter spacing create a refined and legible reading experience without being overly decorative. · `--font-abc-arizona-flare-variable`
- **Substitute:** Playfair Display
- **Weights:** 350, 400
- **Sizes:** 12px, 13px, 15px, 16px, 18px, 32px
- **Line height:** 1.08, 1.18, 1.25, 1.50
- **Letter spacing:** -0.03em, -0.02em, -0.01em
- **Role:** Primary body text, navigation items, secondary headings, and general interface text. The subtle variations in weight and letter spacing create a refined and legible reading experience without being overly decorative.

### ABC Arizona Flare Condensed Variable — Prominent headings and display text. The condensed form with specific letter spacing and light weights (especially 300) creates a distinctive, airy yet impactful typographic statement, signaling authority through restraint, not volume. · `--font-abc-arizona-flare-condensed-variable`
- **Substitute:** Playfair Display Condensed
- **Weights:** 300, 400
- **Sizes:** 20px, 26px, 48px, 104px, 180px
- **Line height:** 0.85, 0.95, 1.18
- **Letter spacing:** -0.03em, -0.025em, -0.02em
- **Role:** Prominent headings and display text. The condensed form with specific letter spacing and light weights (especially 300) creates a distinctive, airy yet impactful typographic statement, signaling authority through restraint, not volume.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.5 | -0.01px | `--text-caption` |
| body | 15px | 1.5 | -0.01px | `--text-body` |
| subheading | 18px | 1.25 | -0.02px | `--text-subheading` |
| heading-sm | 20px | 1.18 | -0.02px | `--text-heading-sm` |
| heading | 26px | 1.18 | -0.025px | `--text-heading` |
| heading-lg | 48px | 0.95 | -0.025px | `--text-heading-lg` |
| display | 180px | 0.85 | -0.03px | `--text-display` |

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
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 4px |
| cards | 8px |
| buttons | 8px |
| general | 4px |

### Layout

- **Section gap:** 56px
- **Card padding:** 16px
- **Element gap:** 16px

## Components

### Ghost Text Button
**Role:** Navigation, inline actions, and secondary calls-to-action.

Completely transparent background, text color `Ink Bark` (#2a1a1d), no border, `ABC Arizona Flare Variable` font. Padding is 0px on all sides, ensuring a minimal footprint.

### Primary Action Button
**Role:** Main calls-to-action.

Background `Garden Sprout` (#26d862), text color `Night Forest` (#1d3023), `ABC Arizona Flare Variable` font, with a `8px` border radius. 0px vertical padding, 24px horizontal padding.

### Subtle Pill Button
**Role:** Tertiary navigation or filter elements.

Transparent background, text `Linen Mist` (#eae6df), `4px` border radius, `1px` border in `Linen Mist`. 8px padding on all sides. This button suggests interactivity without strong visual weight.

### Feature Card - Transparent
**Role:** To group related content in a flexible layout.

Transparent background, `0px` border radius, no shadow. Bottom padding of `32px` for consistent vertical rhythm.

### Content Block Card
**Role:** Informational cards or statistics.

Transparent background with a `8px` border radius. Features `16px` padding on all sides, visually containing information without heavy segmentation.

### Dark Overlay Card
**Role:** Visual content containers, such as imagery or embedded media.

Background `Night Forest` (#1d3023), `8px` border radius, and `0px` padding, designed to have visual content bleed to its edges.

## Do's and Don'ts

### Do
- Use `Parchment White` (#f7f5f2) as the default page background for clarity and spaciousness.
- Apply `Ink Bark` (#2a1a1d) for primary body text and most headings to ensure high contrast and readability.
- Utilize `ABC Arizona Flare Condensed Variable` with weight 300 for prominent display headlines, with letter spacing between -0.025em and -0.03em.
- Implement `Garden Sprout` (#26d862) exclusively for primary interactive elements, such as filled action buttons and navigation accents.
- Maintain an `8px` border radius for all cards and primary buttons to ensure a consistent softened-edge aesthetic.
- Employ a base `elementGap` of `16px` and `sectionGap` of `56px` to establish comfortable visual density.
- Use `Night Forest` (#1d3023) as the default background for any visually dense sections or image backgrounds to create depth.

### Don't
- Avoid using `Garden Sprout` (#26d862) for non-interactive textual content; its high saturation is reserved for action.
- Do not introduce sharp, angular edges; apply `8px` or `4px` radii consistently to all applicable components.
- Refrain from heavy drop shadows; the design relies on color contrast and subtle borders for visual separation.
- Do not use generic system fonts; `ABC Arizona Flare Variable` and `ABC Arizona Flare Condensed Variable` are critical to brand identity.
- Avoid tight spacing; maintain a comfortable density by adhering to the `16px` element gap and `56px` section gap.
- Do not embed imagery tightly; prioritize spacious layouts that give visuals room to breathe.
- Avoid introducing additional chromatic colors; the palette is intentionally restrained, leveraging greens and earth tones.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Parchment White | `#f7f5f2` | Dominant page and base canvas background. |
| 1 | Linen Mist | `#eae6df` | Secondary background for subtle content grouping or ghost elements. |
| 2 | Night Forest | `#1d3023` | Darker card backgrounds, hero sections, and visual content containers. |

## Imagery

The site uses a mix of tightly cropped, natural photography with blurred effects and clean product-focused imagery. Photography often features organic subjects like plants or flowers, treated with motion blur to create an artistic, abstract feel rather than literal representation. Product-focused images (if present) are crisp and isolated. Iconography, visible in navigation, is minimal, using `Ink Bark` (#2a1a1d) stroke for abstract, outlined symbols that complement the typography. Imagery serves both decorative, atmospheric purposes and as a direct showcase for brand personality.

## Layout

The page primarily uses a contained layout with a comfortable max-width, allowing content to center. The hero section is full-bleed, featuring large, condensed typography centered over an abstract, blurred green background gradient. Subsequent sections generally alternate between bands of `Parchment White` (#f7f5f2) and `Linen Mist` (#eae6df), maintaining a consistent `56px` vertical `sectionGap`. Content within sections often follows a text-dominant, centered stack or a simple column grid (e.g., 2-column or 4-column cards for features or statistics), promoting a clean, organized flow. Navigation is a minimalist top bar, integrating subtle ghost buttons.

## Agent Prompt Guide

### Quick Color Reference
text: #2a1a1d
background: #f7f5f2
border: #d7d2cc
accent: #0e634f
primary action: #26d862 (filled action)

### 3-5 Example Component Prompts
1. Create a hero section: full-bleed background `Night Forest` (#1d3023) with a subtle green blurred gradient overlay. Centered headline 'UNEARTHING WHAT'S NEXT' at 180px `ABC Arizona Flare Condensed Variable` weight 300, `Linen Mist` (#eae6df) color, letter-spacing -0.03em. Subtext 'The global creative talent consultancy.' in 15px `ABC Arizona Flare Variable` weight 350, `Linen Mist` (#eae6df) color.
2. Create a Primary Action Button: #26d862 background, #2a1a1d text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
3. Build a statistics card: `Parchment White` (#f7f5f2) background, 8px radius, 16px padding on all sides. Numeric value '79%' in `Deep Moss` (#0e634f) 32px `ABC Arizona Flare Variable` weight 400, description text in 15px `ABC Arizona Flare Variable` weight 350, `Ink Bark` (#2a1a1d) color.

## Similar Brands

- **Figma** — Uses a similarly restrained color palette with a single bright accent color to draw attention to interactive elements, paired with clean, modern typography.
- **Linear** — Employs a minimalist UI strategy with sharp type, generous spacing, and a limited color set where accents guide user interaction rather than decorative flair.
- **Supabase** — Features a dark/light theme approach, but shares a core principle of using a single vivid green as a functional accent color against largely achromatic backgrounds.
- **Kinsta** — Combines natural, organic-feeling imagery and a clean, spacious layout with strong contrasting typography for headlines, similar to Craft's design language.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-ink-bark: #2a1a1d;
  --color-night-forest: #1d3023;
  --color-deep-moss: #0e634f;
  --color-garden-sprout: #26d862;
  --color-linen-mist: #eae6df;
  --color-parchment-white: #f7f5f2;
  --color-ash-taupe: #504344;
  --color-cloud-cement: #d7d2cc;
  --color-stone-slate: #645757;

  /* Typography — Font Families */
  --font-abc-arizona-flare-variable: 'ABC Arizona Flare Variable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-abc-arizona-flare-condensed-variable: 'ABC Arizona Flare Condensed Variable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: -0.01px;
  --text-body: 15px;
  --leading-body: 1.5;
  --tracking-body: -0.01px;
  --text-subheading: 18px;
  --leading-subheading: 1.25;
  --tracking-subheading: -0.02px;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.18;
  --tracking-heading-sm: -0.02px;
  --text-heading: 26px;
  --leading-heading: 1.18;
  --tracking-heading: -0.025px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 0.95;
  --tracking-heading-lg: -0.025px;
  --text-display: 180px;
  --leading-display: 0.85;
  --tracking-display: -0.03px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-w350: 350;
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;

  /* Layout */
  --section-gap: 56px;
  --card-padding: 16px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;

  /* Named Radii */
  --radius-tags: 4px;
  --radius-cards: 8px;
  --radius-buttons: 8px;
  --radius-general: 4px;

  /* Surfaces */
  --surface-parchment-white: #f7f5f2;
  --surface-linen-mist: #eae6df;
  --surface-night-forest: #1d3023;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-ink-bark: #2a1a1d;
  --color-night-forest: #1d3023;
  --color-deep-moss: #0e634f;
  --color-garden-sprout: #26d862;
  --color-linen-mist: #eae6df;
  --color-parchment-white: #f7f5f2;
  --color-ash-taupe: #504344;
  --color-cloud-cement: #d7d2cc;
  --color-stone-slate: #645757;

  /* Typography */
  --font-abc-arizona-flare-variable: 'ABC Arizona Flare Variable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-abc-arizona-flare-condensed-variable: 'ABC Arizona Flare Condensed Variable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: -0.01px;
  --text-body: 15px;
  --leading-body: 1.5;
  --tracking-body: -0.01px;
  --text-subheading: 18px;
  --leading-subheading: 1.25;
  --tracking-subheading: -0.02px;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.18;
  --tracking-heading-sm: -0.02px;
  --text-heading: 26px;
  --leading-heading: 1.18;
  --tracking-heading: -0.025px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 0.95;
  --tracking-heading-lg: -0.025px;
  --text-display: 180px;
  --leading-display: 0.85;
  --tracking-display: -0.03px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
}
```

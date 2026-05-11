# Abetterlou — Style Reference
> Midnight desert oasis

**Theme:** dark

A Better Lou establishes a confident, sophisticated dark aesthetic with deep earth tones and a singular vivid yellow-orange accent. Typography is compact and precise, often with subtle negative letter-spacing, creating a dense yet highly legible information display. Surfaces are minimal, often using subtle background shifts or thin borders rather than heavy elevation, while the accent color serves as both a brand highlight and a clear indicator of interaction.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Deep Onyx | `#140b00` | `--color-deep-onyx` | Primary background for dark sections, primary text for light sections, subtle borders, card backgrounds in dark mode |
| Dawn Linen | `#fff1e0` | `--color-dawn-linen` | Light background for alternating sections, primary text on dark backgrounds, active navigation item borders, input text |
| Amber Glow | `linear-gradient(315deg, rgba(255, 180, 66, 0), rgb(255, 180, 66) 49%, rgb(255, 241, 224))` | `--color-amber-glow` | Primary accent color for CTA buttons, active links, decorative highlights, card backgrounds in light sections; Decorative gradient for background elements, combines accent and secondary neutrals for visual depth |
| Abyss | `#0b0600` | `--color-abyss` | Deepest background tone for large sections and footer, providing maximum contrast for text |
| Fossil Grey | `#43392d` | `--color-fossil-grey` | Subtle borders and separators, secondary text |
| Desert Stone | `#4f4538` | `--color-desert-stone` | Input borders, subtle secondary surface background tones |
| Pale Ash | `#85796c` | `--color-pale-ash` | Muted text, hairline borders, secondary iconography |
| Dark Charcoal | `#181109` | `--color-dark-charcoal` | Hairline borders on dark backgrounds, subtly darker tones for visual separation without strong contrast |
| Warm Mist | `#f1f1f1` | `--color-warm-mist` | Body text on dark backgrounds, high-contrast borders |

## Tokens — Typography

### PP Neue Montreal — The primary typeface for all content elements, from large headlines to fine print. Its geometric forms provide clarity and a modern, technical feel, while the range of weights supports a clear hierarchy. Significant negative letter-spacing is used on larger sizes to create a dense, impactful presentation. · `--font-pp-neue-montreal`
- **Substitute:** Inter, Arial, sans-serif
- **Weights:** 400, 500
- **Sizes:** 10px, 12px, 13px, 14px, 16px, 17px, 19px, 20px, 22px, 23px, 27px, 29px, 30px, 33px, 35px, 43px, 55px, 59px, 69px, 73px, 81px
- **Line height:** 0.80, 1.00, 1.10, 1.20, 1.40, 1.43, 1.50
- **Letter spacing:** -0.0140em (at 81px), -0.0110em (at 73px), -0.0100em (at 69px), -0.0090em (at 59px), -0.0080em (at 55px), -0.0070em (at 43px), -0.0060em (at 35px), -0.0050em (at 33px), -0.0040em (at 30px), -0.0030em (at 29px), -0.0020em (at 27px), 0.0100em (at 10px)
- **Role:** The primary typeface for all content elements, from large headlines to fine print. Its geometric forms provide clarity and a modern, technical feel, while the range of weights supports a clear hierarchy. Significant negative letter-spacing is used on larger sizes to create a dense, impactful presentation.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.5 | 0.1px | `--text-caption` |
| body | 14px | 1.5 | — | `--text-body` |
| subheading | 22px | 1.43 | -0.002px | `--text-subheading` |
| heading | 35px | 1.2 | -0.006px | `--text-heading` |
| heading-lg | 55px | 1.1 | -0.008px | `--text-heading-lg` |
| display | 81px | 0.8 | -0.014px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 6 | 6px | `--spacing-6` |
| 8 | 8px | `--spacing-8` |
| 9 | 9px | `--spacing-9` |
| 10 | 10px | `--spacing-10` |
| 12 | 12px | `--spacing-12` |
| 13 | 13px | `--spacing-13` |
| 14 | 14px | `--spacing-14` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 28 | 28px | `--spacing-28` |
| 32 | 32px | `--spacing-32` |
| 52 | 52px | `--spacing-52` |
| 72 | 72px | `--spacing-72` |
| 152 | 152px | `--spacing-152` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 6px |
| inputs | 1296px |
| buttons | 1296px |
| navigation | 1162.8px |

### Layout

- **Section gap:** 52px
- **Card padding:** 12px
- **Element gap:** 12px

## Components

### Primary Action Pill Button
**Role:** Call to action button for key conversions.

Filled with Amber Glow (#ffb442) background, text in Deep Onyx (#140b00). Features a high border-radius of 1296px, making it a pill shape. Padding is 9px vertical, 15px horizontal. Includes an optional small square button (12px padding, 100% radius) of the same color scheme for icon-only actions.

### Ghost Input Field
**Role:** Standard input for forms, designed for dark backgrounds.

Transparent background (rgba(255, 255, 255, 0)), text in Dawn Linen (#fff1e0). Border is a subtle Dawn Linen (#fff1e0) with 25% opacity. Features a 1296px border-radius for a pill shape. Padding of 8px vertical, 20px horizontal.

### Dark Card
**Role:** Container for content sections on dark backgrounds.

Background in Deep Onyx (#140b00), with a subtle 6px border-radius. No box shadow.

### Accent Card
**Role:** Container for highlighted content, breaking from the dark theme.

Background in Amber Glow (#ffb442), with a 6px border-radius. No box shadow.

### Badge (Text Only)
**Role:** Used for categorization or brief informational labels.

Transparent background, text in Dawn Linen (#fff1e0). No border-radius or padding specified, implying inline usage.

## Do's and Don'ts

### Do
- Prioritize Deep Onyx (#140b00) and Abyss (#0b0600) as primary background colors for text-heavy sections to maintain the dark theme.
- Use Dawn Linen (#fff1e0) exclusively for primary text content on dark backgrounds and for high-contrast borders.
- Apply Amber Glow (#ffb442) for all primary calls to action, interactive elements, and key brand highlights.
- Ensure all interactive elements, especially buttons and inputs, utilize a 1296px border-radius to achieve a consistent pill shape.
- Employ PP Neue Montreal with negative letter-spacing for all headlines and large text sizes to enhance visual density and distinctiveness.
- Use a subtle 1px solid border with colors like Fossil Grey (#43392d), Desert Stone (#4f4538), or Pale Ash (#85796c) for dividers and non-interactive element separation.
- Maintain comfortable density in layouts, using 12px for `elementGap` and `cardPadding` to ensure clear content separation without feeling sparse.

### Don't
- Avoid introducing additional saturated colors beyond Amber Glow (#ffb442) to preserve the brand's focused accent palette.
- Do not use generic square or slightly rounded button shapes; all interactive buttons and inputs must conform to the 1296px pill-shaped radius.
- Refrain from using strong box shadows or heavy elevation, the system relies on subtle color shifts and borders for layering.
- Do not use highly contrasting or vibrant images without sufficient dark overlays in hero sections, as the site uses strong dark backgrounds.
- Avoid decorative elements that do not serve a clear purpose or are not tied to the brand's deep earth tone and amber accent palette.
- Do not use positive letter-spacing on large headlines; compact text is a signature visual characteristic.
- Avoid wide page layouts, prefer contained content even without a strict `pageMaxWidth` value, focusing content in the central viewing area.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Abyss | `#0b0600` | Base page background for maximum contrast and overall dark theme. |
| 1 | Deep Onyx | `#140b00` | Primary section background, most cards, and prominent UI elements. |
| 2 | Desert Stone | `#4f4538` | Subtle secondary background or input fills, providing a slight shift from Deep Onyx. |
| 3 | Amber Glow | `#ffb442` | Accentuated card backgrounds, indicating importance or interaction, used sparingly as a highlight surface. |
| 4 | Dawn Linen | `#fff1e0` | Light backgrounds for alternating sections, offering visual breathing room and high contrast for dark text. |

## Imagery

The site uses a mix of real-world photography and abstract or simple graphic elements. Photography is often high-key portraiture or environmental shots, depicting individuals or landscapes with a mature, reflective tone, frequently with a blue-toned or desaturated color treatment, then overlaid with a darkened gradient (`linear-gradient(315deg, rgba(255, 180, 66, 0), rgb(255, 180, 66) 49%, rgb(255, 241, 224))`) to integrate with the dark theme. Graphic elements are minimal and conceptual, like the clock and dots for biological age, using thin lines and simple shapes. Icons are typically outlined, matching the primary text color, with a medium stroke weight. Imagery serves atmospheric and explanatory purposes, often contained within specific sections rather than full-bleed across UI elements, and maintains a sense of calm authority.

## Layout

The page primarily utilizes a full-bleed structure, with content often centered within an implied invisible grid. The hero section is full-bleed with a photographic background and centered, stacked headlines and action elements. Sections can alternate between full-width dark backgrounds and slightly offset, wider light background sections. Content arrangement features alternating text-left/image-right or image-left/text-right patterns, and text blocks are frequently centered when standalone. There's a visible use of multi-column layouts for feature showcases (e.g., three-column icons with text below). Overall, the layout is spacious and comfortable, supporting the authority of the content with defined vertical rhythm between sections. Navigation is a top bar, with primary links left-aligned and 'Patient Portal' and 'Join the list' buttons right-aligned.

## Agent Prompt Guide

Quick Color Reference:
text: #fff1e0
background: #140b00
border: #43392d
accent: #ffb442
primary action: #ffb442 (filled action)

Example Component Prompts:
1. Create a hero section: Abyss (#0b0600) background overlaying a relevant image. Headline at 81px PP Neue Montreal weight 500, Dawn Linen (#fff1e0), letter-spacing -0.014em. Primary Action Pill Button below with 'Get Started' text, filled Amber Glow (#ffb442), Deep Onyx (#140b00) text, 1296px radius, 9px vertical/15px horizontal padding. Subtext at 14px PP Neue Montreal weight 400, Dawn Linen (#fff1e0).
2. Create a pricing card: Accent Card background in Amber Glow (#ffb442), 6px radius. Heading at 29px PP Neue Montreal weight 500, Deep Onyx (#140b00), letter-spacing -0.003em. Body text at 14px PP Neue Montreal weight 400, Deep Onyx (#140b00).
3. Create an input field: Ghost Input Field for 'Email Address', transparent background, Dawn Linen (#fff1e0) text, 1px solid border in Dawn Linen (#fff1e0) at 25% opacity, 1296px radius, 8px vertical/20px horizontal padding.

## Similar Brands

- **Eight Sleep** — Uses a dark, sophisticated palette with occasional color accents, precise typography, and a focus on wellness/performance.
- **Levels Health** — Combines a health-tech focus with a refined design, leveraging strong typography and strategic use of color on dark backgrounds.
- **Whoop** — Employs a deep, dark theme for a data-driven health product, with controlled use of bright accent colors and clear modern typography.
- **Foundry** — Builds a masculine, performance-oriented aesthetic with dark backgrounds and prominent, slightly condensed or tracked-in typography.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-deep-onyx: #140b00;
  --color-dawn-linen: #fff1e0;
  --color-amber-glow: #ffb442;
  --gradient-amber-glow: linear-gradient(315deg, rgba(255, 180, 66, 0), rgb(255, 180, 66) 49%, rgb(255, 241, 224));
  --color-abyss: #0b0600;
  --color-fossil-grey: #43392d;
  --color-desert-stone: #4f4538;
  --color-pale-ash: #85796c;
  --color-dark-charcoal: #181109;
  --color-warm-mist: #f1f1f1;

  /* Typography — Font Families */
  --font-pp-neue-montreal: 'PP Neue Montreal', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --tracking-caption: 0.1px;
  --text-body: 14px;
  --leading-body: 1.5;
  --text-subheading: 22px;
  --leading-subheading: 1.43;
  --tracking-subheading: -0.002px;
  --text-heading: 35px;
  --leading-heading: 1.2;
  --tracking-heading: -0.006px;
  --text-heading-lg: 55px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.008px;
  --text-display: 81px;
  --leading-display: 0.8;
  --tracking-display: -0.014px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-9: 9px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-13: 13px;
  --spacing-14: 14px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-52: 52px;
  --spacing-72: 72px;
  --spacing-152: 152px;

  /* Layout */
  --section-gap: 52px;
  --card-padding: 12px;
  --element-gap: 12px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-full: 1162.8px;
  --radius-full-2: 1296px;

  /* Named Radii */
  --radius-cards: 6px;
  --radius-inputs: 1296px;
  --radius-buttons: 1296px;
  --radius-navigation: 1162.8px;

  /* Surfaces */
  --surface-abyss: #0b0600;
  --surface-deep-onyx: #140b00;
  --surface-desert-stone: #4f4538;
  --surface-amber-glow: #ffb442;
  --surface-dawn-linen: #fff1e0;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-deep-onyx: #140b00;
  --color-dawn-linen: #fff1e0;
  --color-amber-glow: #ffb442;
  --color-abyss: #0b0600;
  --color-fossil-grey: #43392d;
  --color-desert-stone: #4f4538;
  --color-pale-ash: #85796c;
  --color-dark-charcoal: #181109;
  --color-warm-mist: #f1f1f1;

  /* Typography */
  --font-pp-neue-montreal: 'PP Neue Montreal', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --tracking-caption: 0.1px;
  --text-body: 14px;
  --leading-body: 1.5;
  --text-subheading: 22px;
  --leading-subheading: 1.43;
  --tracking-subheading: -0.002px;
  --text-heading: 35px;
  --leading-heading: 1.2;
  --tracking-heading: -0.006px;
  --text-heading-lg: 55px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.008px;
  --text-display: 81px;
  --leading-display: 0.8;
  --tracking-display: -0.014px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-9: 9px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-13: 13px;
  --spacing-14: 14px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-52: 52px;
  --spacing-72: 72px;
  --spacing-152: 152px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-full: 1162.8px;
  --radius-full-2: 1296px;
}
```

# SpaceX — Style Reference
> Deep Space Command. A minimalist, dark-mode interface designed for high-stakes, information-dense environments, where every pixel counts.

**Theme:** dark

This system projects an aura of ambitious precision, like a mission control screen against the vastness of space. The stark black background, illuminated by near-white text and subtle, dark-gray interactive states, creates a sense of focused technological endeavor. Typography is paramount, with hyper-legible, widely-tracked sans-serifs conveying information with clarity and a deliberate, almost uniform weight.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Void | `#000000` | `--color-midnight-void` | Primary background, button backgrounds for ghost variant, navigation overlay. Provides a canvas for bright content. |
| Lunar Dust | `#f0f0fa` | `--color-lunar-dust` | Primary text color, iconographic elements, primary button text. Stands out distinctly against the dark background. |
| Obsidian Blend | `#00000080` | `--color-obsidian-blend` | Primary button background, providing a subtle interactive surface that is distinct from the pure black background. |
| Starfield Gray | `#f0f0fa59` | `--color-starfield-gray` | Button borders for ghost buttons, subtle dividers. Creates definition without visual weight. |
| Interstellar Gray | `#545457` | `--color-interstellar-gray` | Subtle border color for non-primary interactive elements, providing a low-contrast indication. |
| Cosmic Gray | `#404040` | `--color-cosmic-gray` | Border color for select navigation elements, signifying separation or interactive zones. |
| Dark Overlay | `#000000cc` | `--color-dark-overlay` | Used for background overlays, modals, and hover states, providing a deeper, more occlusive layer above content. |

## Tokens — Typography

### D-DIN — Primary text font for body, navigation, buttons, and most informational elements. Its wide tracking at smaller sizes enforces legibility in a dark UI, creating a precise, technical feel. · `--font-d-din`
- **Substitute:** Arial, sans-serif
- **Weights:** 400, 700
- **Sizes:** 10px, 12px, 13px, 16px
- **Line height:** 0.94, 1.00, 1.20, 1.50, 1.70, 2.00
- **Letter spacing:** 0.09em, 0.10em
- **Role:** Primary text font for body, navigation, buttons, and most informational elements. Its wide tracking at smaller sizes enforces legibility in a dark UI, creating a precise, technical feel.

### D-DIN-Bold — Used exclusively for prominent headings. Despite being 'bold', its weight is 400 (normal) and the reduced letter-spacing compared to the regular D-DIN, combined with the large size, creates a strong, commanding presence without shouting. · `--font-d-din-bold`
- **Substitute:** Arial Bold, sans-serif
- **Weights:** 400
- **Sizes:** 48px
- **Line height:** 1.00, 1.25
- **Letter spacing:** 0.02em
- **Role:** Used exclusively for prominent headings. Despite being 'bold', its weight is 400 (normal) and the reduced letter-spacing compared to the regular D-DIN, combined with the large size, creates a strong, commanding presence without shouting.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.5 | 0.09px | `--text-caption` |
| button | 16px | 1.2 | 0.1px | `--text-button` |
| heading-lg | 48px | 1 | 0.02px | `--text-heading-lg` |

## Tokens — Spacing & Shapes

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 10 | 10px | `--spacing-10` |
| 12 | 12px | `--spacing-12` |
| 13 | 13px | `--spacing-13` |
| 15 | 15px | `--spacing-15` |
| 18 | 18px | `--spacing-18` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 30 | 30px | `--spacing-30` |
| 40 | 40px | `--spacing-40` |
| 60 | 60px | `--spacing-60` |

### Border Radius

| Element | Value |
|---------|-------|
| buttons | 4px |
| navigation | 4px |
| pillButton | 32px |

### Layout

- **Section gap:** 60px
- **Card padding:** 20px
- **Element gap:** 18px

## Components

### Ghost Primary Button
**Role:** Primary call to action.

Features 'Obsidian Blend' (rgba(0, 0, 0, 0.5)) background, 'Lunar Dust' (#f0f0fa) text, and 'Starfield Gray' (rgba(240, 240, 250, 0.35)) top border. Corner radius is 4px. Padding is 0px top/bottom, 20px left/right. Typography uses D-DIN at 16px with 0.10em letter-spacing.

### Pill Accent Button
**Role:** Secondary or alternative call to action, often for reservation or ordering.

Has a background of rgba(240, 240, 250, 0.1) which is a transparent 'Lunar Dust' tint, with 'Midnight Void' (#000000) text. Features a prominent 32px border radius, creating a pill shape. Padding is 18px all around. Typography uses D-DIN at 16px with 0.10em letter-spacing.

### Navigation Link
**Role:** Top-level navigation items.

Text is 'Lunar Dust' (#f0f0fa) using the D-DIN font, likely at 13px with 0.10em letter-spacing. Interaction states might involve 'Cosmic Gray' (#404040) borders or subtle background changes.

### Body Text Block
**Role:** Informational paragraphs.

Set in 'Lunar Dust' (#f0f0fa) using the D-DIN font at 16px, with a line height of 1.5 or 1.7 to ensure readability against the dark background. Letter spacing is normal to slightly increased for legibility.

### Display Heading
**Role:** Main page titles and prominent section headings.

Set in 'Lunar Dust' (#f0f0fa) using D-DIN-Bold at 48px, with a line height of 1.0. Letter spacing is 0.02em, giving it a slightly tighter, more impactful appearance than other text.

## Do's and Don'ts

### Do
- Prioritize 'Midnight Void' (#000000) for backgrounds and 'Lunar Dust' (#f0f0fa) for primary text to maintain stark contrast.
- Use D-DIN for all body text, navigation, and buttons, with D-DIN-Bold exclusively for hero headings at 48px.
- Apply a 0.09em or 0.10em letter-spacing to D-DIN text to enforce a deliberate, spacious feel.
- Utilize 20px horizontal padding for most interactive elements and buttons, such as the Ghost Primary Button.
- Ensure all interactive buttons feature a 4px `radius` unless specifically designed as a 'Pill Accent Button' (32px radius).
- Employ `Obsidian Blend` (rgba(0, 0, 0, 0.5)) for backgrounds of primary action buttons, providing a subtle interactive layer.

### Don't
- Avoid using highly saturated colors; maintain a monochromatic palette with only a hint of transparent `Lunar Dust` for subtle accents.
- Do not deviate from the D-DIN font family for any text elements; custom fonts are a core identifier.
- Never use drop shadows or complex elevation schemes; depth is created through background changes and subtle borders.
- Do not use generic button styles; always apply either the 'Ghost Primary Button' or 'Pill Accent Button' specifications.
- Avoid tight letter-spacing for standard text; the liberal use of letter-spacing is a signature choice.
- Do not introduce gradients or complex background imagery in areas where text readability is paramount.

## Imagery

The site uses high-resolution, full-bleed photography. Images feature dramatic celestial bodies (Mars, Earth), rocket launches, and advanced spacecraft. The treatment is realistic and often features dark, moody backdrops blending seamlessly with the site's 'Midnight Void' background. There is no masking or excessive graphic treatment; images are presented as raw, powerful, and central to the narrative. Icons are minimalist, outlined, and monochromatic ('Lunar Dust'), appearing only on functional interactive elements, not for decoration. The imagery serves as both atmosphere and direct product showcase, dominating sections to convey the scale and ambition of space exploration.

## Layout

The page model is primarily full-bleed, with content anchored to a `pageMaxWidth` that dynamically adjusts to the viewport, ensuring large dramatic visuals. The hero sections feature full-viewport background images/videos with centered or left-aligned 'Display Heading' text in 'Lunar Dust'. Sections are vertically stacked with significant `sectionGap` (60px), creating spacious breathing room. Content is often presented in a simple, centered stack or a two-column layout with text on one side and an image or video on the other. Navigation is a sticky top bar, minimal and unobtrusive, dissolving into text links only. The overall density is spacious, allowing visuals to take precedence.

## Agent Prompt Guide

### Quick Color Reference
- Text: #f0f0fa (Lunar Dust)
- Background: #000000 (Midnight Void)
- Primary Button Background: rgba(0, 0, 0, 0.5) (Obsidian Blend)
- Button Border: rgba(240, 240, 250, 0.35) (Starfield Gray)
- Accent (Pill Btn Background): rgba(240, 240, 250, 0.1)

### 3-5 Example Component Prompts
1. Create a hero section: full-bleed background image `path/to/mars.jpg`. Centered headline `Making Life Multiplanetary` using D-DIN-Bold at 48px, #f0f0fa, line-height 1.0, letter-spacing 0.02em. Below it, body text `SpaceX was founded under the belief...` in D-DIN 16px, #f0f0fa, line-height 1.5. Below that, a button labeled `EXPLORE ->` with background rgba(0, 0, 0, 0.5), text #f0f0fa, border rgba(240, 240, 250, 0.35), 4px radius, 0px top/bottom padding, 20px left/right padding, D-DIN 16px, letter-spacing 0.1em.
2. Design a navigation header: background #000000, height 74px. Links `VEHICLES`, `STARLINK` etc. are #f0f0fa, D-DIN 13px, letter-spacing 0.1em. Align text links to the left and a `UPCOMING LAUNCHES` dropdown to the right. Use 4px radius for any dropdown elements.
3. Implement a 'Pill Accent Button': text `RESERVE YOUR RIDE` in #000000, background rgba(240, 240, 250, 0.1), 32px border-radius, 18px padding all around. Typography D-DIN 16px, letter-spacing 0.1em.
4. Generate a footer: background #000000. Text links `TWITTER`, `YOUTUBE` etc. are #f0f0fa, D-DIN 12px, letter-spacing 0.1em. Links should be arranged horizontally with `columnGap` of 18px and `rowGap` of 12px.

## Similar Brands

- **NASA** — High-resolution, full-bleed space imagery combined with a technical, high-contrast textual overlay.
- **Tesla** — Minimalist dark theme, focus on large product photography, bold sans-serif typography for headings.
- **Boeing Defense** — Serious, technical aesthetic with a focus on product visuals and a reduced color palette for clarity.
- **Palantir** — Dark-mode UI, emphasis on data and technology, and a deliberate, almost stark visual style for trust.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-void: #000000;
  --color-lunar-dust: #f0f0fa;
  --color-obsidian-blend: #00000080;
  --color-starfield-gray: #f0f0fa59;
  --color-interstellar-gray: #545457;
  --color-cosmic-gray: #404040;
  --color-dark-overlay: #000000cc;

  /* Typography — Font Families */
  --font-d-din: 'D-DIN', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-d-din-bold: 'D-DIN-Bold', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --tracking-caption: 0.09px;
  --text-button: 16px;
  --leading-button: 1.2;
  --tracking-button: 0.1px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: 0.02px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-13: 13px;
  --spacing-15: 15px;
  --spacing-18: 18px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-30: 30px;
  --spacing-40: 40px;
  --spacing-60: 60px;

  /* Layout */
  --section-gap: 60px;
  --card-padding: 20px;
  --element-gap: 18px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-3xl: 32px;

  /* Named Radii */
  --radius-buttons: 4px;
  --radius-navigation: 4px;
  --radius-pillbutton: 32px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-void: #000000;
  --color-lunar-dust: #f0f0fa;
  --color-obsidian-blend: #00000080;
  --color-starfield-gray: #f0f0fa59;
  --color-interstellar-gray: #545457;
  --color-cosmic-gray: #404040;
  --color-dark-overlay: #000000cc;

  /* Typography */
  --font-d-din: 'D-DIN', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-d-din-bold: 'D-DIN-Bold', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --tracking-caption: 0.09px;
  --text-button: 16px;
  --leading-button: 1.2;
  --tracking-button: 0.1px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: 0.02px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-13: 13px;
  --spacing-15: 15px;
  --spacing-18: 18px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-30: 30px;
  --spacing-40: 40px;
  --spacing-60: 60px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-3xl: 32px;
}
```

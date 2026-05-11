# Planpoint — Style Reference
> Architectural blueprint on white marble

**Theme:** light

Planpoint employs a bright, professional workspace aesthetic with a primary focus on clean UI and a strong accent blue. The design is characterized by generous spacing, soft rounded corners on interactive elements, and robust typography that balances readability with impact. Colors are predominantly achromatic, allowing the vivid brand blue to punctuate key actions and information, while subtle surface differentiation maintains visual hierarchy.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#00051a` | `--color-midnight-ink` | Primary text, dark surface backgrounds, deep accent for iconography and illustrations |
| Royal Blue | `#0f68ea` | `--color-royal-blue` | Primary action buttons, interactive elements, significant brand accents, and energetic backgrounds in hero sections. This vivid blue drives user focus |
| Sky Blue | `#007aff` | `--color-sky-blue` | Link text, borders for outlined icons, and secondary interactive components. A lighter, more active shade of blue |
| Sunburst Yellow | `#ffcb00` | `--color-sunburst-yellow` | Yellow action color for filled buttons, selected navigation states, and focused conversion moments. |
| White Canvas | `#ffffff` | `--color-white-canvas` | Page backgrounds, card surfaces, ghost button text and borders, and primary text on dark backgrounds |
| Pewter Gray | `#1d1d1f` | `--color-pewter-gray` | Secondary text, subtle borders, and inactive icon fills. A dark gray that offers contrast to primary text without harshness |
| White Smoke | `#f0f2f4` | `--color-white-smoke` | Secondary surface backgrounds, button fills for tertiary actions, and background for featured content blocks. Provides a soft visual break from White Canvas |
| Slate Blue | `#000a3b` | `--color-slate-blue` | Darker card backgrounds and occasional deep blue contextual surfaces |
| Soft Gray | `#e5e6e8` | `--color-soft-gray` | Lightest gray, used for subtle borders and as a background for less prominent headings |

## Tokens — Typography

### Inter — The sole typeface for all text elements, ranging from navigation to body copy and headlines. Its consistent application across a wide range of weights and sizes contributes to the system's clarity and modern feel. Specific heavy negative letter-spacing for large headlines makes them distinctive and compact, while tighter tracking for smaller text ensures dense information remains readable. · `--font-inter`
- **Substitute:** system-ui
- **Weights:** 400, 500, 600, 700
- **Sizes:** 14px, 16px, 18px, 22px, 23px, 29px, 32px, 43px, 50px, 72px, 144px
- **Line height:** 0.90, 1.00, 1.10, 1.20, 1.25, 1.30, 1.55, 1.60
- **Letter spacing:** -0.071em at 144px, -0.067em at 72px, -0.060em at 50px, -0.044em at 43px, -0.033em at 32px, -0.031em at 29px, -0.027em at 23px, -0.041em at 14px
- **Role:** The sole typeface for all text elements, ranging from navigation to body copy and headlines. Its consistent application across a wide range of weights and sizes contributes to the system's clarity and modern feel. Specific heavy negative letter-spacing for large headlines makes them distinctive and compact, while tighter tracking for smaller text ensures dense information remains readable.

### system-ui — system-ui — detected in extracted data but not described by AI · `--font-system-ui`
- **Weights:** 500
- **Sizes:** 14px
- **Line height:** 1.5
- **Letter spacing:** -0.041
- **Role:** system-ui — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 14px | 1.55 | -0.41px | `--text-caption` |
| body | 16px | 1.6 | — | `--text-body` |
| subheading | 18px | 1.55 | — | `--text-subheading` |
| heading-sm | 22px | 1.25 | — | `--text-heading-sm` |
| heading | 29px | 1.3 | -0.9px | `--text-heading` |
| heading-lg | 43px | 1.2 | -1.9px | `--text-heading-lg` |
| display | 72px | 1.1 | -4.82px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** spacious

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 8 | 8px | `--spacing-8` |
| 12 | 12px | `--spacing-12` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 28 | 28px | `--spacing-28` |
| 40 | 40px | `--spacing-40` |
| 64 | 64px | `--spacing-64` |
| 72 | 72px | `--spacing-72` |
| 108 | 108px | `--spacing-108` |
| 140 | 140px | `--spacing-140` |
| 240 | 240px | `--spacing-240` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 28.8px |
| links | 160px |
| badges | 16px |
| buttons_chip | 46.8px |
| buttons_pill | 57.6px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| xl | `rgba(0, 0, 0, 0.06) 0px 8px 48px 0px` | `--shadow-xl` |

### Layout

- **Section gap:** 72px
- **Card padding:** 72px
- **Element gap:** 14px

## Components

### Primary Action Button
**Role:** Filled button for primary calls to action

Background: Royal Blue (#0f68ea), Text: White Canvas (#ffffff), Border-radius: 57.6px, Padding: 14.4px vertical, 21.6px horizontal. Creates a prominent, clickable target.

### Secondary Action Button
**Role:** Ghost button for secondary actions or links

Background: transparent, Text: Pewter Gray (#1d1d1f) or Midnight Ink (#00051a), Border: 1px solid Pewter Gray (#1d1d1f), Border-radius: 57.6px, Padding: 0px vertical, 72px horizontal (large). Emphasizes text with a minimal border for less aggressive calls to action.

### Tertiary Action Button
**Role:** Filled button for less prominent actions, often within content blocks

Background: White Smoke (#f0f2f4), Text: Midnight Ink (#00051a), Border-radius: 57.6px, Padding: 0px vertical, 72px horizontal (large). Provides a soft, neutral action without competing with the primary blue.

### Navigation Link Button
**Role:** Minimal button within navigation or content-dense areas

Background: transparent, Text: Midnight Ink (#00051a), No border, Border-radius: 0px, Padding: 20px vertical, 18-32.4px horizontal. Blends into content flow while maintaining clickability.

### Promotional Card
**Role:** Informational card with a strong background accent

Background: Royal Blue (#0f68ea) or Slate Blue (#000a3b), Border-radius: 28.8px, Padding: 86.4px around. Used for highlighting key features or offerings.

### Feature Card
**Role:** Neutral card for displaying features or content blocks

Background: White Smoke (#f0f2f4), Border-radius: 0px, Padding: 72px around. Creates distinct content sections.

### Ghost Card
**Role:** Minimal, borderless card for subtle grouping

Background: transparent, Border-radius: 0px, No shadow, No padding. Used for logo sections or subtle organizational breaks.

## Do's and Don'ts

### Do
- Use Royal Blue (#0f68ea) exclusively for primary calls to action and significant interactive states.
- Apply 57.6px border-radius to all interactive buttons for a consistent pill-shaped appearance.
- Maintain a clear visual hierarchy by using Midnight Ink (#00051a) for primary text and Pewter Gray (#1d1d1f) for secondary text.
- Utilize White Smoke (#f0f2f4) for secondary page/card backgrounds to create subtle distinction and visual breaks.
- Ensure large headlines employ Inter with significant negative letter-spacing, e.g., -0.067em at 72px, to achieve a compact, statement-making effect.
- Use Sunburst Yellow (#ffcb00) sparingly for 'new' indicators or active status badges, never as a primary background or action color.
- Implement 72px padding for content cards and sections to create ample breathing room between content blocks.

### Don't
- Do not introduce new saturated colors outside of Royal Blue, Sky Blue, and Sunburst Yellow.
- Avoid using a border-radius less than 16px as the system relies on soft rounding for interactivity.
- Do not use generic system fonts; always specify Inter with its defined weights and letter-spacing values.
- Do not add additional box-shadows beyond the single defined rgba(0, 0, 0, 0.06) 0px 8px 48px 0px for elevated elements.
- Do not use Royal Blue (#0f68ea) for simple text links; Sky Blue (#007aff) is reserved for this purpose.
- Avoid tight spacing; maintain the defined element gaps and section padding to preserve the spacious feel.
- Do not make text links look like buttons; all text links should be a plain text color with no background or border.

## Elevation

- **Card/Container:** `rgba(0, 0, 0, 0.06) 0px 8px 48px 0px`

## Imagery

Imagery primarily features product screenshots of the Planpoint UI, displayed within clean browser frames. These are often flat and isolated, focusing on functionality. Photography of real estate projects and logos of partner brands are also present, treated without special effects and integrated cleanly within sections. Icons are minimal, outlined, and monochromatic, primarily using Pewter Gray or Midnight Ink, occasionally accented by Sky Blue for interactive states. The overall density of imagery is balanced, serving an explanatory role rather than purely decorative.

## Layout

The page maintains a centered max-width content area with generous vertical spacing between sections. The hero features a centered headline over a video, setting a dynamic yet contained tone. Content progresses through alternating sections that use either a White Canvas background or a White Smoke background, creating visual rhythm. Within sections, content often uses a split layout (text left, image/video right) or centered stacks. A ghost card grid is used for displaying client logos, maintaining a clean, spacious feel. The navigation is a sticky top bar, providing persistent access to key links.

## Agent Prompt Guide

**Quick Color Reference:**
text: #00051a
background: #ffffff
border: #1d1d1f
accent: #0f68ea
primary action: #0f68ea (filled action)

**3-5 Example Component Prompts:**
1. Create a hero section with a centered headline: 'Accelerate your sales and rentals' using Inter 72px weight 700 with letter-spacing -4.82px, color Midnight Ink (#00051a). Add subtext 'with the leading interactive plan viewer;' using Inter 22px weight 400, color Midnight Ink (#00051a).
2. Design a Primary Action Button labeled 'Free trial': background Royal Blue (#0f68ea), text White Canvas (#ffffff), border-radius 57.6px, padding 14.4px vertical, 21.6px horizontal. Use Inter 16px weight 500.
3. Implement a Feature Card: background White Smoke (#f0f2f4), border-radius 0px, padding 72px. Inside, place a heading 'Easy to create & manage' using Inter 43px weight 700 letter-spacing -1.9px, color Midnight Ink (#00051a), and body text 'Made for any skill level' using Inter 18px weight 400, color Midnight Ink (#00051a).
4. Create a 'New' badge: background Sunburst Yellow (#ffcb00), text Midnight Ink (#00051a), border-radius 16px, padding 2px vertical, 10px horizontal. Use Inter 14px weight 500.

## Similar Brands

- **Webflow** — Similar light, spacious UI with strong blues for primary actions and minimal design elements.
- **Linear** — Clean, predominantly monochromatic interfaces with one distinct accent color for key interactions.
- **Stripe** — Strong focus on typography, spacious layouts, and subtle background differentiation for hierarchy.
- **Notion** — A similar approach to versatile information presentation through clean, card-based layouts and subtle color accents.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #00051a;
  --color-royal-blue: #0f68ea;
  --color-sky-blue: #007aff;
  --color-sunburst-yellow: #ffcb00;
  --color-white-canvas: #ffffff;
  --color-pewter-gray: #1d1d1f;
  --color-white-smoke: #f0f2f4;
  --color-slate-blue: #000a3b;
  --color-soft-gray: #e5e6e8;

  /* Typography — Font Families */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-system-ui: 'system-ui', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.55;
  --tracking-caption: -0.41px;
  --text-body: 16px;
  --leading-body: 1.6;
  --text-subheading: 18px;
  --leading-subheading: 1.55;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1.25;
  --text-heading: 29px;
  --leading-heading: 1.3;
  --tracking-heading: -0.9px;
  --text-heading-lg: 43px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -1.9px;
  --text-display: 72px;
  --leading-display: 1.1;
  --tracking-display: -4.82px;

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
  --spacing-28: 28px;
  --spacing-40: 40px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-108: 108px;
  --spacing-140: 140px;
  --spacing-240: 240px;

  /* Layout */
  --section-gap: 72px;
  --card-padding: 72px;
  --element-gap: 14px;

  /* Border Radius */
  --radius-2xl: 18px;
  --radius-3xl: 28.8px;
  --radius-3xl-2: 46.8px;
  --radius-full: 57.6px;
  --radius-full-2: 100px;
  --radius-full-3: 160px;

  /* Named Radii */
  --radius-cards: 28.8px;
  --radius-links: 160px;
  --radius-badges: 16px;
  --radius-buttonschip: 46.8px;
  --radius-buttonspill: 57.6px;

  /* Shadows */
  --shadow-xl: rgba(0, 0, 0, 0.06) 0px 8px 48px 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #00051a;
  --color-royal-blue: #0f68ea;
  --color-sky-blue: #007aff;
  --color-sunburst-yellow: #ffcb00;
  --color-white-canvas: #ffffff;
  --color-pewter-gray: #1d1d1f;
  --color-white-smoke: #f0f2f4;
  --color-slate-blue: #000a3b;
  --color-soft-gray: #e5e6e8;

  /* Typography */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-system-ui: 'system-ui', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.55;
  --tracking-caption: -0.41px;
  --text-body: 16px;
  --leading-body: 1.6;
  --text-subheading: 18px;
  --leading-subheading: 1.55;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1.25;
  --text-heading: 29px;
  --leading-heading: 1.3;
  --tracking-heading: -0.9px;
  --text-heading-lg: 43px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -1.9px;
  --text-display: 72px;
  --leading-display: 1.1;
  --tracking-display: -4.82px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-28: 28px;
  --spacing-40: 40px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-108: 108px;
  --spacing-140: 140px;
  --spacing-240: 240px;

  /* Border Radius */
  --radius-2xl: 18px;
  --radius-3xl: 28.8px;
  --radius-3xl-2: 46.8px;
  --radius-full: 57.6px;
  --radius-full-2: 100px;
  --radius-full-3: 160px;

  /* Shadows */
  --shadow-xl: rgba(0, 0, 0, 0.06) 0px 8px 48px 0px;
}
```

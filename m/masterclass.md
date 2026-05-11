# MasterClass — Style Reference
> Midnight Stage Presence

**Theme:** dark

MasterClass employs a dark, cinematic UI, reminiscent of a premium streaming platform. Dominant blacks and deep charcoals create a sophisticated environment, allowing vibrant accents to punctuate interactive elements and brand moments. Typography is bold and confident, commanding attention within the high-contrast setting. Component surfaces are subtle, often inset, maintaining a flat aesthetic that emphasizes content and celebrity figures over overt ornamentation.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Pitch Black | `#000000` | `--color-pitch-black` | Primary background for footers and expansive content sections, subtle borders, text for badges |
| Charcoal Canvas | `#222326` | `--color-charcoal-canvas` | Default page background, card backgrounds |
| Graphite Base | `#0d0d0e` | `--color-graphite-base` | Background for subtle surface differentiation, text buttons, and darker borders |
| Deep Slate | `#272c33` | `--color-deep-slate` | Card backgrounds, button backgrounds for secondary actions |
| Subtle Ash | `#191c21` | `--color-subtle-ash` | Secondary background color for body sections |
| Muted Stone | `#211d0d` | `--color-muted-stone` | Text color for muted elements, borders on certain components |
| Iron Gray | `#43454c` | `--color-iron-gray` | Button backgrounds, inset shadow on interactive elements |
| Silver Mist | `#9ea0a9` | `--color-silver-mist` | Text color for secondary information, muted icons, disabled states |
| Light Steel | `#d4d5d9` | `--color-light-steel` | Subtle body text color, borders |
| Pure White | `#ffffff` | `--color-pure-white` | Primary text color, active states, badge backgrounds, clear button borders |
| Ghostly Gray | `#f4f4f5` | `--color-ghostly-gray` | Hover states for text and icons, borders for ghost buttons, light text |
| Action Raspberry | `#e32652` | `--color-action-raspberry` | Primary action buttons, prominent icons — a vibrant pop against dark backgrounds for conversion |
| Interactive Lime | `#dcff00` | `--color-interactive-lime` | Green action color for filled buttons, selected navigation states, and focused conversion moments. Use as a supporting accent, not as a status color |
| Highlight Gold | `#eed37f` | `--color-highlight-gold` | Accent borders for interactive cards or highlighted content, decorative elements |
| Subtle Cadet | `#596170` | `--color-subtle-cadet` | Background for small, less prominent interactive elements |

## Tokens — Typography

### Sohne — Primary typeface for all body text, links, buttons, and most headings up to 48px. Its slightly condensed yet approachable nature supports information density without feeling cramped. · `--font-sohne`
- **Substitute:** Inter
- **Weights:** 400, 600
- **Sizes:** 8px, 12px, 14px, 16px, 20px, 22px, 24px, 32px, 48px
- **Line height:** 1.00, 1.25, 1.33, 1.45, 1.50, 1.60, 2.50
- **Letter spacing:** 0.0100em at 8px, 0.0120em at 12px, 0.0200em at 14px, 0.0230em at 16px, 0.0270em at 20px, 0.0300em at 22px, 0.0390em at 24px
- **Role:** Primary typeface for all body text, links, buttons, and most headings up to 48px. Its slightly condensed yet approachable nature supports information density without feeling cramped.

### Sohne Schmal — Used for large, impactful display headlines, where its 'schmal' (narrow) characteristic allows for bold statements in restricted vertical space. The tight letter-spacing adds to its direct, attention-grabbing feel. · `--font-sohne-schmal`
- **Substitute:**  condensed sans-serif like Oswald or Anton
- **Weights:** 500
- **Sizes:** 64px, 80px
- **Line height:** 0.85, 0.90
- **Letter spacing:** -0.0100em at 64px, 0.0100em at 80px
- **Role:** Used for large, impactful display headlines, where its 'schmal' (narrow) characteristic allows for bold statements in restricted vertical space. The tight letter-spacing adds to its direct, attention-grabbing feel.

### Ivar Display Condensed — An alternative serif for display headings, adding a touch of classic authority and gravitas to select feature titles. Its condensed form maintains visual economy typical of the system. · `--font-ivar-display-condensed`
- **Substitute:** Condensed serif like Playfair Display SC or IBM Plex Serif
- **Weights:** 400
- **Sizes:** 64px
- **Line height:** 1.10
- **Letter spacing:** 0.0050em
- **Role:** An alternative serif for display headings, adding a touch of classic authority and gravitas to select feature titles. Its condensed form maintains visual economy typical of the system.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.45 | — | `--text-caption` |
| body-sm | 14px | 1.45 | — | `--text-body-sm` |
| body | 16px | 1.45 | — | `--text-body` |
| body-lg | 20px | 1.45 | — | `--text-body-lg` |
| heading-sm | 22px | 1.45 | — | `--text-heading-sm` |
| heading | 24px | 1.3 | — | `--text-heading` |
| heading-lg | 32px | 1.3 | — | `--text-heading-lg` |
| display-sm | 48px | 1.3 | — | `--text-display-sm` |

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
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 96 | 96px | `--spacing-96` |
| 112 | 112px | `--spacing-112` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 8px |
| links | 8px |
| badges | 20px |
| images | 4px |
| inputs | 0px |
| buttons | 8px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgb(148, 154, 164) 0px 0px 0px 2px inset` | `--shadow-subtle` |
| subtle-2 | `rgb(39, 44, 51) 0px 0px 0px 1px inset` | `--shadow-subtle-2` |
| subtle-3 | `rgb(67, 69, 76) 0px 0px 0px 2px inset` | `--shadow-subtle-3` |
| subtle-4 | `rgb(148, 154, 164) 0px 0px 0px 1px inset` | `--shadow-subtle-4` |

### Layout

- **Section gap:** 64px
- **Card padding:** 48px
- **Element gap:** 16px

## Components

### Ghost Navigation Button
**Role:** Navigation and secondary actions that need to remain subtle.

backgroundColor: rgba(0,0,0,0), color: #f4f4f5, border: #f4f4f5 1px solid, radius: 4px, padding: 16px.

### Icon Button (filled)
**Role:** Functional icons that require a background.

backgroundColor: #596170, color: #ffffff, radius: 4px, padding: 0px.

### Navigation Tab Button
**Role:** Top-level navigation items or filters.

backgroundColor: #0d0d0, color: #9ea0a9, radius: 8px, padding: 12px 16px.

### Flat Interactive Input
**Role:** Search bars and form fields.

backgroundColor: rgba(0,0,0,0), color: #ffffff, border: #ffffff 1px solid, radius: 0px, padding: 0px.

### Hero Checkbox/Radio Button
**Role:** Choices within hero sections.

backgroundColor: #272c33, color: #ffffff, border: #ffffff 1px solid, radius: 0px, padding: 12px 16px.

### Primary Action Button
**Role:** High-priority calls to action.

backgroundColor: #e32652, color: #ffffff, radius: 8px, padding: 12px 16px.

### Secondary Action Button
**Role:** Prominent actions, but not primary conversion.

backgroundColor: #222326, color: #ffffff, radius: 0px, padding: 12px 16px.

### Content Feature Card
**Role:** Containers for featured content with generous padding.

backgroundColor: #272c33, radius: 8px, padding: 48px 96px.

### Visual Content Card
**Role:** Cards for showcasing visual content (e.g., instructors, classes).

backgroundColor: #222326, radius: 12px, padding: 0px.

### Informational Badge
**Role:** Small, informative labels.

backgroundColor: #ffffff, color: #000000, radius: 20px, padding: 4px 12px.

## Do's and Don'ts

### Do
- Prioritize Pitch Black (#000000) for large background areas and Charcoal Canvas (#222326) for primary surfaces to maintain the dark theme.
- Use Action Raspberry (#e32652) exclusively for primary calls to action, maintaining its vivid impact.
- All interactive elements will have a minimum border-radius of 4px, with important buttons using 8px.
- Utilize Sohne Schmal at 64px or 80px for monumental headings with tight negative letter-spacing for dramatic effect.
- Employ consistent 4px padding on badges and 16px horizontal padding for most buttons.
- Ensure input fields have a 1px #ffffff border and a 0px radius for a stark, integrated look.
- Use the inset box-shadow `rgb(148, 154, 164) 0px 0px 0px 2px inset` for selected or active body elements to indicate focus.

### Don't
- Do not introduce light backgrounds for core content sections; the system is strictly dark-mode dominant.
- Avoid using multiple chromatic colors close together; allow Action Raspberry (#e32652) to stand out as the primary accent.
- Do not use generic system fonts; always specify Sohne for body and most headings, Sohne Schmal or Ivar Display Condensed for display.
- Do not deviate from the established spacing scale (multiples of 4px) to maintain consistent density.
- Do not use standard button shadows; rely on inset borders or subtle color shifts for interaction states.
- Avoid large imagery with distracting backgrounds; prioritize portraits or product shots with minimal context.
- Do not use highly rounded corners (e.g., >20px) on main cards or primary buttons, as this clashes with the structured feel.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Pitch Black Base | `#000000` | Expansive background for footer and full-width sections. |
| 1 | Charcoal Canvas | `#222326` | Primary page background and default card background. |
| 2 | Deep Slate Cards | `#272c33` | Elevated card surfaces and specific input containers. |
| 3 | Graphite Modules | `#0d0d0` | Background for navigation tabs and interactive modules. |

## Elevation

- **Input focus:** `inset 0 0 0 2px #949aa4`
- **Hovered button/link:** `inset 0 0 0 2px #43454c`

## Imagery

The visual language is dominated by high-quality, often dramatic portrait photography of celebrity instructors. Images are typically tightly cropped, focusing on the individual's face or upper body, and serve a functional purpose of personalizing content rather than purely decorative. Photography is often full-bleed within sections or contained within cards with large radii (8px or 12px), creating a gallery-like feel. Iconography is minimalist, either outlined or filled, primarily in Pure White or Silver Mist, with occasional pops of Interactive Lime or Action Raspberry for status or interaction. There is a strong emphasis on product showcase – the instructors and their content are the primary visual elements.

## Layout

The page primarily utilizes a max-width contained layout where content is centered, often with dynamic full-bleed hero sections. The hero frequently employs a dark background with a prominent, large headline and supporting text, flanked by high-impact instructor imagery. Sections alternate between full-width black backgrounds and slightly lighter charcoal surfaces, maintaining strong vertical rhythm with generous section gaps (64px). Content is arranged in alternating text-left/image-right patterns, centered stacks for feature declarations, and horizontal scrolling carousels or grids for content browsing. Navigation is a sticky top bar with a stark dark background, featuring minimalist text links and a prominent Action Raspberry call-to-action button.

## Agent Prompt Guide

Quick Color Reference:
text: #ffffff
background: #222326
border: #ffffff
accent: #e32652
primary action: #e32652 (filled action)

Example Component Prompts:
1. Create a Primary Action Button: #e32652 background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Design a browsing filter button: Graphite Base background, Sohne, 14px, weight 600, #9ea0a9, letter-spacing 0.0200em. Radius 8px, padding 12px 16px. Example text: 'Business & Entrepreneurship'.
3. Construct a content card: Deep Slate background, radius 8px. Inside, for example, an instructor image (radius 12px) followed by a headline 'PHOTOGRAPHY' in Sohne, 24px, weight 600, #ffffff, line-height 1.33. The card should have 48px padding on all sides.

## Similar Brands

- **Netflix** — Dark UI with cinematic visuals and a focus on content thumbnails/cards.
- **Skillshare** — Online learning platform emphasizing expert instructors and clean content presentation.
- **Apple TV+** — Premium dark interface, strong emphasis on visual content and high-quality photography.
- **Spotify** — Dark-themed core UI with bright accent colors for interactive elements and brand recognition.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-pitch-black: #000000;
  --color-charcoal-canvas: #222326;
  --color-graphite-base: #0d0d0e;
  --color-deep-slate: #272c33;
  --color-subtle-ash: #191c21;
  --color-muted-stone: #211d0d;
  --color-iron-gray: #43454c;
  --color-silver-mist: #9ea0a9;
  --color-light-steel: #d4d5d9;
  --color-pure-white: #ffffff;
  --color-ghostly-gray: #f4f4f5;
  --color-action-raspberry: #e32652;
  --color-interactive-lime: #dcff00;
  --color-highlight-gold: #eed37f;
  --color-subtle-cadet: #596170;

  /* Typography — Font Families */
  --font-sohne: 'Sohne', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sohne-schmal: 'Sohne Schmal', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ivar-display-condensed: 'Ivar Display Condensed', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.45;
  --text-body-sm: 14px;
  --leading-body-sm: 1.45;
  --text-body: 16px;
  --leading-body: 1.45;
  --text-body-lg: 20px;
  --leading-body-lg: 1.45;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1.45;
  --text-heading: 24px;
  --leading-heading: 1.3;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1.3;
  --text-display-sm: 48px;
  --leading-display-sm: 1.3;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-112: 112px;

  /* Layout */
  --section-gap: 64px;
  --card-padding: 48px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-full: 48px;

  /* Named Radii */
  --radius-cards: 8px;
  --radius-links: 8px;
  --radius-badges: 20px;
  --radius-images: 4px;
  --radius-inputs: 0px;
  --radius-buttons: 8px;

  /* Shadows */
  --shadow-subtle: rgb(148, 154, 164) 0px 0px 0px 2px inset;
  --shadow-subtle-2: rgb(39, 44, 51) 0px 0px 0px 1px inset;
  --shadow-subtle-3: rgb(67, 69, 76) 0px 0px 0px 2px inset;
  --shadow-subtle-4: rgb(148, 154, 164) 0px 0px 0px 1px inset;

  /* Surfaces */
  --surface-pitch-black-base: #000000;
  --surface-charcoal-canvas: #222326;
  --surface-deep-slate-cards: #272c33;
  --surface-graphite-modules: #0d0d0;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-pitch-black: #000000;
  --color-charcoal-canvas: #222326;
  --color-graphite-base: #0d0d0e;
  --color-deep-slate: #272c33;
  --color-subtle-ash: #191c21;
  --color-muted-stone: #211d0d;
  --color-iron-gray: #43454c;
  --color-silver-mist: #9ea0a9;
  --color-light-steel: #d4d5d9;
  --color-pure-white: #ffffff;
  --color-ghostly-gray: #f4f4f5;
  --color-action-raspberry: #e32652;
  --color-interactive-lime: #dcff00;
  --color-highlight-gold: #eed37f;
  --color-subtle-cadet: #596170;

  /* Typography */
  --font-sohne: 'Sohne', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sohne-schmal: 'Sohne Schmal', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ivar-display-condensed: 'Ivar Display Condensed', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.45;
  --text-body-sm: 14px;
  --leading-body-sm: 1.45;
  --text-body: 16px;
  --leading-body: 1.45;
  --text-body-lg: 20px;
  --leading-body-lg: 1.45;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1.45;
  --text-heading: 24px;
  --leading-heading: 1.3;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1.3;
  --text-display-sm: 48px;
  --leading-display-sm: 1.3;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-112: 112px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-full: 48px;

  /* Shadows */
  --shadow-subtle: rgb(148, 154, 164) 0px 0px 0px 2px inset;
  --shadow-subtle-2: rgb(39, 44, 51) 0px 0px 0px 1px inset;
  --shadow-subtle-3: rgb(67, 69, 76) 0px 0px 0px 2px inset;
  --shadow-subtle-4: rgb(148, 154, 164) 0px 0px 0px 1px inset;
}
```

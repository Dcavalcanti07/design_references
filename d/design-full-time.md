# Design Full-Time — Style Reference
> Dark mode command center

**Theme:** dark

Design Full-Time employs a dark, pragmatic aesthetic for a focused learning environment. The palette centers around deep blacks and charcoals, accented by bright whites for primary text and a distinct orange-to-red gradient for calls to action. Typography is functional and compact, prioritizing direct communication without flourishes. Components are understated, relying on subtle borders and minimal elevation to define interactive elements against the dark background, creating an efficient and professional feel.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Absolute Zero | `#000000` | `--color-absolute-zero` | Page backgrounds, card surfaces, primary text on light backgrounds, element borders |
| Charcoal Black | `#111111` | `--color-charcoal-black` | Secondary surface background for elevated components like cards and buttons, providing a slight distinction from the main canvas |
| Whisper White | `#ffffff` | `--color-whisper-white` | Primary text across dark backgrounds, navigation links, and button text |
| Slate Gray | `#888888` | `--color-slate-gray` | Muted text, secondary navigation items, subtle borders |
| Cool Steel | `#a0a0a0` | `--color-cool-steel` | Medium-contrast borders, control outlines, and structural separators. Do not promote it to the primary CTA color |
| Faded Ink | `#2c3e50` | `--color-faded-ink` | Dark borders and separators for elevated surfaces and inverted UI. |
| Midnight Graphite | `#343434` | `--color-midnight-graphite` | Subtle fill for decorative SVG elements, barely visible against the dark background |
| Sunset Fire Light | `linear-gradient(to right, rgba(255, 200, 78, 0.12) 9.64%, rgba(250, 58, 25, 0.1) 90.67%)` | `--color-sunset-fire-light` | Subtle background for promotional banners, indicating importance without being as visually heavy as the solid accent |

## Tokens — Typography

### Inter — The primary typeface for all text elements. Its straightforward and efficient appearance supports the platform's professional and instructional context. Weights 400 and 600 handle body text and subheadings, while 700 and 800 are reserved for prominent headings, maintaining compact energy. · `--font-inter`
- **Substitute:** system-ui
- **Weights:** 400, 600, 700, 800
- **Sizes:** 15px, 16px, 18px, 20px, 24px
- **Line height:** 1.00, 1.33, 1.40, 1.50, 1.56
- **Letter spacing:** normal
- **Role:** The primary typeface for all text elements. Its straightforward and efficient appearance supports the platform's professional and instructional context. Weights 400 and 600 handle body text and subheadings, while 700 and 800 are reserved for prominent headings, maintaining compact energy.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body-sm | 15px | 1.56 | — | `--text-body-sm` |
| subheading | 18px | 1.4 | — | `--text-subheading` |
| heading | 20px | 1.33 | — | `--text-heading` |
| heading-lg | 24px | 1 | — | `--text-heading-lg` |

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
| 48 | 48px | `--spacing-48` |

### Border Radius

| Element | Value |
|---------|-------|
| none | 0px |

### Layout

- **Section gap:** 48px
- **Card padding:** 16px
- **Element gap:** 8px

## Components

### Primary Filled Button
**Role:** Interactive element for key actions

Solid Charcoal Black (#111111) background with Whisper White (#ffffff) text. No border-radius, giving it a stark, immediate presence. Padding is 12px vertical and 40px horizontal for a substantial feel, or a more compact 8px vertical and 16px horizontal for secondary actions.

### Coming Soon Tag
**Role:** Informational label

Small label with a Faded Ink (#2c3e50) text and border, providing a subtle highlight for upcoming features against the dark background. 4px vertical padding and 16px horizontal.

### Promotional Banner
**Role:** Highlighting special offers

A full-width banner featuring a Sunset Fire Light (#ffc84e) gradient background from rgba(255, 200, 78, 0.12) to rgba(250, 58, 25, 0.1), with prominent white text. Text for critical info is Whisper White (#ffffff), while 'Save 60%' is a specific orange-yellow for impact. A solid Sunset Fire (#ff8a00) Call to Action button is embedded within it.

### Video Thumbnail Card
**Role:** Container for video content

Uses the main Absolute Zero (#000000) background to blend seamlessly. Video titles are Whisper White (#ffffff) with descriptive text in Slate Gray (#888888). No explicit border or radius for these content cards, relying on spacing for separation.

## Do's and Don'ts

### Do
- Prioritize Absolute Zero (#000000) as the canvas and Charcoal Black (#111111) for elevated surfaces, maintaining a dark base.
- Use Whisper White (#ffffff) for all primary headings and body text on dark backgrounds to ensure high contrast.
- Apply the Sunset Fire (#ff8a00) gradient for all primary call-to-action buttons and critical highlights to draw immediate attention.
- Employ plain-edged, square components with a 0px border-radius for buttons and input fields to maintain a stark, functional aesthetic.
- Maintain a clear hierarchy using Inter font weights: 400 for body, 600 for subheadings, and 700-800 for prominent headlines.
- Separate content blocks and components primarily through generous vertical spacing, using 32px marginBottom on sections or elements.

### Don't
- Avoid using any rounded corners; all elements should have a 0px border-radius.
- Do not introduce light backgrounds beyond Whisper White text; the theme is strictly dark with minimal surface variation.
- Refrain from using pastel or desaturated colors outside of the defined accent gradients; maintain a high contrast and dark tone.
- Do not use subtle drop shadows or complex elevation effects; rely on color differences and borders for hierarchy.
- Avoid decorative illustrations or organic shapes; prioritize clear, functional UI elements and direct photography/video thumbnails.
- Do not use generic blue for links or interactive elements; all interactive accents should derive from the Sunset Fire gradient.

## Imagery

The site primarily uses product-focused video thumbnails featuring a single speaker in a studio setting. Photography is candid, focused on a person, and not treated with filters. Icons are minimal, utility-driven, and typically white against the dark background. Imagery's role is explanatory and informative, directly showcasing the content. The layout is text-dominant, with images serving as embedded content blocks rather than full-bleed decorative elements.

## Layout

The page adheres to a max-width contained layout, with content centered. The hero section is full-bleed black with a centered brand logo and tagline, followed by a full-width promotional banner. Content sections below are primarily dark, arranged in a single column of stacked blocks. Video lessons are presented in a responsive grid, with each video card having a title and subtitle. Navigation is a simple top bar, fixed at the top, offering minimal options and a 'Student Login' button.

## Agent Prompt Guide

Quick Color Reference:
text: #ffffff
background: #000000
border: #2c3e50
accent: #ff8a00
primary action: #111111 (filled action)

Example Component Prompts:
1. Create a Primary Action Button: #111111 background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Design a 'Coming Soon' label: 'Coming Soon', text #2c3e50, 1px solid #2c3e50 border, Inter 400 at 15px, 4px vertical padding, 16px horizontal padding, 0px border-radius.
3. Implement a general text input field: background #000000, 1px solid #4d4d4d border, text #ffffff, Inter 400 at 16px, 8px vertical padding, 16px horizontal padding, 0px border-radius.
4. Create a subsection heading: 'Try these FREE video lessons', text #ffffff, Inter 800 at 24px, 32px bottom margin.

## Similar Brands

- **Level Up Tutorials** — Similar dark, focused UI with practical content and reliance on video thumbnails.
- **Egghead.io** — Monochromatic dark theme, emphasis on concise technical video lessons, functional typography.
- **Wes Bos** — Strong brand accent color against a dark or mostly neutral background for courses and calls to action.
- **DesignCode.io** — Dark UI trend, high contrast text, and a minimalist design to focus on educational content with distinct CTA styling.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-absolute-zero: #000000;
  --color-charcoal-black: #111111;
  --color-whisper-white: #ffffff;
  --color-slate-gray: #888888;
  --color-cool-steel: #a0a0a0;
  --color-faded-ink: #2c3e50;
  --color-midnight-graphite: #343434;
  --color-sunset-fire-light: #ffc840;
  --gradient-sunset-fire-light: linear-gradient(to right, rgba(255, 200, 78, 0.12) 9.64%, rgba(250, 58, 25, 0.1) 90.67%);

  /* Typography — Font Families */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-sm: 15px;
  --leading-body-sm: 1.56;
  --text-subheading: 18px;
  --leading-subheading: 1.4;
  --text-heading: 20px;
  --leading-heading: 1.33;
  --text-heading-lg: 24px;
  --leading-heading-lg: 1;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;
  --font-weight-extrabold: 800;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;

  /* Layout */
  --section-gap: 48px;
  --card-padding: 16px;
  --element-gap: 8px;

  /* Named Radii */
  --radius-none: 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-absolute-zero: #000000;
  --color-charcoal-black: #111111;
  --color-whisper-white: #ffffff;
  --color-slate-gray: #888888;
  --color-cool-steel: #a0a0a0;
  --color-faded-ink: #2c3e50;
  --color-midnight-graphite: #343434;
  --color-sunset-fire-light: #ffc840;

  /* Typography */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-sm: 15px;
  --leading-body-sm: 1.56;
  --text-subheading: 18px;
  --leading-subheading: 1.4;
  --text-heading: 20px;
  --leading-heading: 1.33;
  --text-heading-lg: 24px;
  --leading-heading-lg: 1;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
}
```

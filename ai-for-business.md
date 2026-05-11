# AI for Business — Style Reference
> High-contrast precision tooling

**Theme:** light

Dayos presents a bold, high-contrast digital canvas for enterprise AI. Its visual identity is built on stark black typography against light, almost achromatic surfaces, creating a sense of seriousness and directness. Minimal use of vivid accent colors punctuates key information and interactive elements, ensuring they stand out without overwhelming the authoritative tone. Components are sharp and defined, often using square or subtly rounded forms, reflecting a precise and functional aesthetic.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas Ice | `#e5e7eb` | `--color-canvas-ice` | Primary page and section backgrounds, subtle borders, inactive input fields |
| Midnight Ink | `#000000` | `--color-midnight-ink` | Primary headings, body text, and icon fills on light surfaces. Do not promote it to the primary CTA color |
| Paper White | `#ffffff` | `--color-paper-white` | Elevated card backgrounds, interactive elements, text on dark backgrounds |
| Fog Gray | `#979797` | `--color-fog-gray` | Muted text, secondary button borders, placeholder text, subtle icons |
| Ash Gray | `#444444` | `--color-ash-gray` | Secondary body text, navigation labels, and subdued headings. Do not promote it to the primary CTA color |
| Faint Mist | `#f3f3f3` | `--color-faint-mist` | Subtle background for navigation, ghost button fills, hovered states |
| Deep Smoke | `#2f2f2f` | `--color-deep-smoke` | Darker background surface for specific sections or content blocks |
| Action Green | `#d1ffca` | `--color-action-green` | Subtle interactive highlights, link backgrounds for emphasis |
| Alert Yellow | `#fff100` | `--color-alert-yellow` | Decorative accents, occasional link text for high visibility |

## Tokens — Typography

### SuisseIntl — Body text, navigation, links, and general UI elements. Its range of weights allows for structured hierarchy within prose and component labels. · `--font-suisseintl`
- **Substitute:** Inter
- **Weights:** 400, 450, 500
- **Sizes:** 14px, 16px, 18px, 20px, 28px, 40px
- **Line height:** 1.10, 1.14, 1.20, 1.25, 1.30, 1.33
- **Letter spacing:** -0.42px at 14px, -0.42px at 16px, -0.72px at 18px
- **Role:** Body text, navigation, links, and general UI elements. Its range of weights allows for structured hierarchy within prose and component labels.

### SuisseIntlCond — Prominent headlines and display text, used for impactful, commanding statements. The condensed, bold nature paired with tight line-height and tracking creates a visually dense and powerful presence. · `--font-suisseintlcond`
- **Substitute:** Bebas Neue
- **Weights:** 700
- **Sizes:** 48px, 64px, 80px, 130px
- **Line height:** 0.90
- **Letter spacing:** -1.44px at 48px, -1.92px at 64px, -2.4px at 80px, -3.9px at 130px
- **Role:** Prominent headlines and display text, used for impactful, commanding statements. The condensed, bold nature paired with tight line-height and tracking creates a visually dense and powerful presence.

### SuisseIntlMono — Captions, metadata, and specialized UI labels where a technical, precise voice is needed. The monospace quality suggests code or hard data. · `--font-suisseintlmono`
- **Substitute:** IBM Plex Mono
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.30, 1.60
- **Letter spacing:** -0.36px at 12px
- **Role:** Captions, metadata, and specialized UI labels where a technical, precise voice is needed. The monospace quality suggests code or hard data.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.6 | -0.36px | `--text-caption` |
| body-sm | 14px | 1.3 | -0.42px | `--text-body-sm` |
| body | 16px | 1.25 | -0.42px | `--text-body` |
| subheading | 18px | 1.2 | -0.72px | `--text-subheading` |
| heading | 28px | 1.14 | — | `--text-heading` |
| heading-lg | 40px | 1.1 | — | `--text-heading-lg` |
| display-sm | 48px | 0.9 | -1.44px | `--text-display-sm` |
| display | 130px | 0.9 | -3.9px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 8px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 8 | 8px | `--spacing-8` |
| 16 | 16px | `--spacing-16` |
| 24 | 24px | `--spacing-24` |
| 40 | 40px | `--spacing-40` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 96 | 96px | `--spacing-96` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 32px |
| buttons | 8px |
| heroElements | 64px |
| navigationItems | 12px |

### Layout

- **Section gap:** 80px
- **Card padding:** 16px
- **Element gap:** 24px

## Components

### Navigation Link Default
**Role:** Standard navigation item for top-level menus.

backgroundColor=rgba(0,0,0,0) color=rgb(68,68,68) borderTopColor=rgb(68,68,68) borderRadius=0px paddingTop=0px paddingRight=16px paddingBottom=0px paddingLeft=16px

### Navigation Link Active
**Role:** Active or selected navigation item, visually distinct.

backgroundColor=rgba(0,0,0,0) color=rgb(0,0,0) borderTopColor=rgb(0,0,0) borderRadius=0px paddingTop=0px paddingRight=0px paddingBottom=0px paddingLeft=0px

### Schedule Demo Button
**Role:** Primary call to action button.

Background #000000, text #ffffff, 8px border-radius, paddingRight=16px.

### Ghost Button
**Role:** Secondary action button with a transparent background.

Transparent background, color #979797, paddingRight=16px, borderRadius=0px.

### Solid Card
**Role:** Content card with a dark background.

backgroundColor=#000000, borderRadius=32px, no boxShadow.

### Paper Card
**Role:** Content card with a light background.

backgroundColor=#ffffff, borderRadius=24px, no boxShadow.

### Pill Button with Round Corners
**Role:** Generic rounded button for various actions.

backgroundColor=rgba(0,0,0,0) color=rgb(0,0,0) borderRadius=4px

### Hero Card Top-Rounded
**Role:** Specific card style for hero or introductory content.

backgroundColor=#000000, borderRadius=64px 64px 0px 0px, no boxShadow.

## Do's and Don'ts

### Do
- Prioritize SuisseIntlCond 700 with tight letter-spacing for all display headlines to maintain a bold, commanding tone.
- Use Midnight Ink (#000000) for primary text and major interactive elements against Canvas Ice (#e5e7eb) or Paper White (#ffffff) backgrounds.
- Employ Action Green (#d1ffca) or Alert Yellow (#fff100) only as functional accents, such as link backgrounds or callout text, not for large decorative areas.
- Apply a 32px border-radius consistently to all card elements for a substantial, modern feel.
- Maintain high contrast between text and background with a minimum WCAG AAA ratio to ensure visual impact and authority.
- Use a base `elementGap` of 24px between coherent blocks of content or UI elements.
- Use Canvas Ice (#e5e7eb) as the dominant background color to establish a bright, open canvas.

### Don't
- Avoid using multiple chromatic colors in close proximity; color should be used sparingly for impact, not decoration.
- Do not introduce soft shadows or gradients for elevation; surfaces should primarily be flat or differentiated by stark color shifts.
- Refrain from using lightweight fonts for primary headings; always opt for SuisseIntlCond 700 with its defined letter-spacing.
- Do not deviate from the established border radii; avoid introducing custom or intermediate radii values.
- Do not use subtle variations of neutral shades for functional differentiation; use distinct achromatic colors like Midnight Ink for strong elements and Fog Gray for muted ones.
- Avoid generic imagery or stock photography; visual assets should be highly relevant and often technical in nature.
- Do not use overly expressive or decorative typography; the system favors directness and clarity.

## Imagery

The site uses a combination of abstract, somewhat playful 3D rendered forms and conceptual illustrations. The primary graphic in the hero section features geometric, block-like structures in muted and vivid colors (yellow, green, pink) with a reflective surface, suggesting modularity and construction. Imagery serves a decorative and conceptual purpose, rather than presenting lifestyle or product photography. Icons are generally filled, often in black or gray, with a moderate stroke weight, appearing functional and simple. The overall density is image-light, focusing more on bold typography and structured UI.

## Layout

The page primarily uses a full-bleed layout for background color, with content contained within a central, assumed `pageMaxWidth`. The hero section is full-bleed with a large, left-aligned headline in SuisseIntlCond 700, juxtaposed with a conceptual 3D graphic on the right, creating a clear visual split. Sections are generally distinguished by consistent vertical spacing (80px `sectionGap`) and often employ a two-column layout with text on one side and supporting visuals or details on the other. Content often stacks centrally beneath headings. Navigation is a sticky top bar with clearly delineated sections and a prominent 'Schedule a Demo' button.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #e5e7eb
border: #e5e7eb (for subtle borders) / #000000 (for strong borders)
accent: #d1ffca
primary action: no distinct CTA color

Example Component Prompts:
No distinct primary action color was observed; use the extracted neutral button treatments instead of inventing a filled CTA color.
2. Create a navigation link: 'Platform' text in Ash Gray (#444444), transparent background, no border, 16px horizontal padding. Font SuisseIntl 400.
3. Create a dark content card: background Midnight Ink (#000000), 32px border-radius, with a heading 'Product Features' in Paper White (#ffffff) using SuisseIntlCond 700 at 48px, line-height 0.9, letter-spacing -1.44px and body text below in SuisseIntl 400 at 16px, line-height 1.25, color Fog Gray (#979797).
4. Create a hero headline: 'BORN FROM THE AI ERA.' using SuisseIntlCond 700 at 130px, letter-spacing -3.9px, line-height 0.9, color Midnight Ink (#000000).

## Similar Brands

- **Anthropic** — Similar bold, minimalist typography, high-contrast dark text on light backgrounds, and focus on clean UI with minimal decorative elements.
- **OpenAI** — Uses large, impactful headlines, a generally achromatic palette, and positions complex AI concepts with a visually serious and direct tone.
- **Palantir** — Employs an authoritative, often dark-mode aesthetic with strong typography and structured layouts for enterprise technology.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-ice: #e5e7eb;
  --color-midnight-ink: #000000;
  --color-paper-white: #ffffff;
  --color-fog-gray: #979797;
  --color-ash-gray: #444444;
  --color-faint-mist: #f3f3f3;
  --color-deep-smoke: #2f2f2f;
  --color-action-green: #d1ffca;
  --color-alert-yellow: #fff100;

  /* Typography — Font Families */
  --font-suisseintl: 'SuisseIntl', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-suisseintlcond: 'SuisseIntlCond', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-suisseintlmono: 'SuisseIntlMono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.6;
  --tracking-caption: -0.36px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.3;
  --tracking-body-sm: -0.42px;
  --text-body: 16px;
  --leading-body: 1.25;
  --tracking-body: -0.42px;
  --text-subheading: 18px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.72px;
  --text-heading: 28px;
  --leading-heading: 1.14;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.1;
  --text-display-sm: 48px;
  --leading-display-sm: 0.9;
  --tracking-display-sm: -1.44px;
  --text-display: 130px;
  --leading-display: 0.9;
  --tracking-display: -3.9px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-w450: 450;
  --font-weight-medium: 500;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-40: 40px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;

  /* Layout */
  --section-gap: 80px;
  --card-padding: 16px;
  --element-gap: 24px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;
  --radius-full: 48px;
  --radius-full-2: 64px;

  /* Named Radii */
  --radius-cards: 32px;
  --radius-buttons: 8px;
  --radius-heroelements: 64px;
  --radius-navigationitems: 12px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-ice: #e5e7eb;
  --color-midnight-ink: #000000;
  --color-paper-white: #ffffff;
  --color-fog-gray: #979797;
  --color-ash-gray: #444444;
  --color-faint-mist: #f3f3f3;
  --color-deep-smoke: #2f2f2f;
  --color-action-green: #d1ffca;
  --color-alert-yellow: #fff100;

  /* Typography */
  --font-suisseintl: 'SuisseIntl', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-suisseintlcond: 'SuisseIntlCond', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-suisseintlmono: 'SuisseIntlMono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.6;
  --tracking-caption: -0.36px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.3;
  --tracking-body-sm: -0.42px;
  --text-body: 16px;
  --leading-body: 1.25;
  --tracking-body: -0.42px;
  --text-subheading: 18px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.72px;
  --text-heading: 28px;
  --leading-heading: 1.14;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.1;
  --text-display-sm: 48px;
  --leading-display-sm: 0.9;
  --tracking-display-sm: -1.44px;
  --text-display: 130px;
  --leading-display: 0.9;
  --tracking-display: -3.9px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-40: 40px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;
  --radius-full: 48px;
  --radius-full-2: 64px;
}
```

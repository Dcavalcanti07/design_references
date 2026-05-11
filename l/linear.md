# Linear — Style Reference
> Midnight Command Center: A dark, layered interface lit by precise accents, like a high-tech control panel.

**Theme:** dark

Linear presents a sophisticated and focused dark-mode experience, reminiscent of a command center dashboard. A deep charcoal base creates a serious, immersive canvas, while subtle gradients and layered surfaces build depth without harsh contrasts. Distinctive muted text colors (#8a8f98 for secondary, #62666d for tertiary) maintain readability against the dark backdrop. Critically, interaction is marked by a single vivid lime green (#e4f222), applied selectively to primary calls to action, preventing visual clutter and guiding the user's eye with precision.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Pitch Black | `#08090a` | `--color-pitch-black` | Page background, primary surface for base elements, subtly integrated into shadows for depth. |
| Graphite | `#0f1011` | `--color-graphite` | Elevated card backgrounds, slightly lighter than the canvas to denote layering. |
| Deep Slate | `#161718` | `--color-deep-slate` | Secondary elevated card backgrounds, providing another layer of visual hierarchy. |
| Charcoal Grey | `#23252a` | `--color-charcoal-grey` | Borders and some shadowed card surfaces, framing elements with a subtle distinction. |
| Muted Ash | `#323334` | `--color-muted-ash` | Subtle borders and dividers, indicating soft separations within the dark theme. |
| Gunmetal | `#383b3f` | `--color-gunmetal` | Tertiary background elements and input borders, a darker neutral for functional elements. |
| Porcelain | `#f7f8f8` | `--color-porcelain` | Primary text and icons, providing strong contrast for readability against dark backgrounds. |
| Light Steel | `#d0d6e0` | `--color-light-steel` | Secondary text and borders, for less prominent information or structural lines. |
| Storm Cloud | `#8a8f98` | `--color-storm-cloud` | Tertiary text, descriptive labels, and inactive states, recedes into the background for low-priority details. |
| Fog Grey | `#62666d` | `--color-fog-grey` | Muted text for metadata, timestamps, and further de-emphasized content. |
| Alabaster | `#e5e5e6` | `--color-alabaster` | Informational borders and subtle fills, often seen in code blocks or explanatory components. |
| Neon Lime | `#e4f222` | `--color-neon-lime` | Primary action indicators, active states, and focus elements — a high-energy focal point. |
| Aether Blue | `#5e6ad2` | `--color-aether-blue` | Decorative highlights and occasional background elements, suggesting a technological or informational context. |
| Forest Green | `#008d2c` | `--color-forest-green` | Positive status indicators, success messages, and related iconography. |
| Cyan Spark | `#02b8cc` | `--color-cyan-spark` | Informational highlights and unique icon fills, providing a cool accent. |
| Emerald | `#27a644` | `--color-emerald` | Success and completion states, often paired with green text. |
| Warning Red | `#eb5757` | `--color-warning-red` | Observed in icon fill, body borderColor, other fill. Extracted usage does not support a distinct primary control color. |
| Deep Violet | `#6366f1` | `--color-deep-violet` | Background accents in specific content blocks, indicating a distinct informational category. |
| Amethyst | `#8b5cf6` | `--color-amethyst` | Another variant of violet for backgrounds, used interchangeably with Deep Violet for visual diversity. |

## Tokens — Typography

### Inter Variable — Primary UI typeface for all content including headings, body text, and interactive elements. Its variable weights provide a clean, modern aesthetic with strong technical readability. · `--font-inter-variable`
- **Substitute:** Inter
- **Weights:** 300, 400, 510, 590
- **Sizes:** 10px, 11px, 12px, 13px, 14px, 15px, 16px, 17px, 20px, 24px, 32px, 48px, 64px, 72px
- **Line height:** 1.00, 1.13, 1.20, 1.33, 1.40, 1.47, 1.50, 1.60, 2.00, 2.46, 2.75
- **Letter spacing:** -0.22, -0.15, -0.13, -0.12, -0.11, -0.1
- **OpenType features:** `"cv01", "ss03"`
- **Role:** Primary UI typeface for all content including headings, body text, and interactive elements. Its variable weights provide a clean, modern aesthetic with strong technical readability.

### Berkeley Mono — Monospaced font for code snippets, technical details, and certain data displays, ensuring consistent character alignment and technical clarity. · `--font-berkeley-mono`
- **Substitute:** IBM Plex Mono
- **Weights:** 400
- **Sizes:** 12px, 13px, 14px
- **Line height:** 1.30, 1.40, 1.50, 1.71
- **Letter spacing:** -0.15
- **Role:** Monospaced font for code snippets, technical details, and certain data displays, ensuring consistent character alignment and technical clarity.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.4 | -0.1px | `--text-caption` |
| body | 14px | 1.4 | -0.13px | `--text-body` |
| heading | 24px | 1.33 | -0.22px | `--text-heading` |
| heading-lg | 48px | 1.2 | -0.22px | `--text-heading-lg` |
| display | 72px | 1 | -0.22px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** compact

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
| 48 | 48px | `--spacing-48` |
| 56 | 56px | `--spacing-56` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 96 | 96px | `--spacing-96` |
| 128 | 128px | `--spacing-128` |

### Border Radius

| Element | Value |
|---------|-------|
| pill | 9999px |
| tags | 2px |
| cards | 6px |
| badges | 4px |
| inputs | 6px |
| buttons | 6px |
| default | 6px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| sm | `rgba(0, 0, 0, 0.4) 0px 2px 4px 0px` | `--shadow-sm` |
| md | `rgba(0, 0, 0, 0.2) 0px 0px 12px 0px inset` | `--shadow-md` |
| subtle | `rgb(35, 37, 42) 0px 0px 0px 1px inset` | `--shadow-subtle` |
| subtle-2 | `rgba(0, 0, 0, 0.2) 0px 0px 0px 1px` | `--shadow-subtle-2` |
| subtle-3 | `rgba(0, 0, 0, 0.01) 0px 5px 2px 0px, rgba(0, 0, 0, 0.04) ...` | `--shadow-subtle-3` |
| xl | `rgba(8, 9, 10, 0.6) 0px 4px 32px 0px` | `--shadow-xl` |
| subtle-4 | `rgba(0, 0, 0, 0.1) 0px 0px 0px 2px` | `--shadow-subtle-4` |
| subtle-5 | `rgba(0, 0, 0, 0.33) 0px 0px 0px 1px` | `--shadow-subtle-5` |
| subtle-6 | `rgba(255, 255, 255, 0.03) 0px 0px 0px 1px inset, rgba(255...` | `--shadow-subtle-6` |

### Layout

- **Section gap:** 24px
- **Card padding:** 12px
- **Element gap:** 8px

## Components

### Primary Action Button
**Role:** Call to action button

Filled button with 'Neon Lime' background (#e4f222), 'Pitch Black' text (#08090a), 6px border-radius, and variable padding. Used for primary user actions.

### Ghost Navigation Button
**Role:** Navigation and secondary actions

Ghost button with transparent background, 'Porcelain' text (#f7f8f8), no explicit padding, and 0px border-radius. Navigational links or simple interactive elements.

### Subtle Link Button
**Role:** Tertiary actions and links

Ghost button with transparent background, 'Light Steel' text (#d0d6e0), 6px border-radius, and minimal padding (0px top/bottom, 6px left/right). Used for less prominent interactive elements or textual links.

### Navigation Item Button
**Role:** Sidebar navigation items

Ghost button with transparent background, 'Storm Cloud' text (#8a8f98), 2px border-radius, and no explicit padding. Used for items in a navigation list.

### Default Card
**Role:** Content container

Card with 'Graphite' background (#0f1011), 6px border-radius, and an outer shadow of rgba(0, 0, 0, 0.4) 0px 2px 4px 0px. Padding is 8px on all sides.

### Elevated Card
**Role:** Prominent content container

Card with 'Deep Slate' background (#161718), 12px top border-radius (0px bottom), and an inset shadow of rgb(35, 37, 42) 0px 0px 0px 1px. Padding is 24px vertical and 0px horizontal.

### Nested Card
**Role:** Internal content grouping

Card with 'Pitch Black' background (#08090a) and 12px border-radius, no shadow. Padding 8px on all sides, used for containing sub-elements within larger cards.

### Input Field
**Role:** User input fields

Input field with transparent background, 'Porcelain' text (#f7f8f8), 'Charcoal Grey' border (#23252a), and 6px border-radius. Padding is 12px vertical and 14px horizontal.

### Subtle Input Field
**Role:** Search or secondary input fields

Input field with 'Gunmetal' background (#383b3f), 'Porcelain' text (#f7f8f8), no explicit border, and 0px border-radius. Used for less emphasized data entry.

### Badge
**Role:** Label or tag

Badge with a 'Gunmetal' background (#383b3f), 'Storm Cloud' text (#8a8f98), 4px border-radius, and padding of 0px vertical and 6px horizontal. Used for small categorical labels.

## Do's and Don'ts

### Do
- Use 'Pitch Black' (#08090a) for the primary page background to establish the dark theme.
- Apply 'Porcelain' (#f7f8f8) for all primary text and important icons to ensure readability.
- Highlight primary interactive elements exclusively with 'Neon Lime' (#e4f222) as a background, restricting its use to guide user attention.
- Create depth and hierarchy by layering surfaces using 'Pitch Black' (#08090a), 'Graphite' (#0f1011), and 'Deep Slate' (#161718) backgrounds.
- Employ the Inter Variable font family with specific letter-spacing adjustments for all UI text, such as -0.22px for display sizes and -0.11px for body text, to maintain a tight, precise feel.
- Utilize 6px border-radius for all primary buttons, cards, and input fields to maintain a consistent, subtly rounded aesthetic.
- Use 'Storm Cloud' (#8a8f98) for secondary text and descriptive labels to recede into the background.

### Don't
- Do not introduce additional bright or saturated colors beyond 'Neon Lime' (#e4f222) for interactive elements; maintain its singular role.
- Avoid using harsh white backgrounds or light-themed patterns, as the system is anchored in a dark mode aesthetic.
- Do not deviate from the specified typeface choices; 'Inter Variable' and 'Berkeley Mono' are fundamental to the visual identity.
- Refrain from using strong, diffuse shadows; elevation is achieved through subtle layering and sharp, contained shadows like rgba(0, 0, 0, 0.4) 0px 2px 4px 0px.
- Do not apply broad, decorative background gradients across large sections of the UI; gradients are subtle and contained to specific functional areas.
- Do not use generic border-radii; adhere to 6px for key components like cards and buttons, and 2px for smaller tags, to preserve the signature balance of softness and precision.
- Avoid large amounts of white space; the design is compact, leveraging an 8px element gap as a standard measurement.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Pitch Black Canvas | `#08090a` | Base page background and deepest surface level. |
| 1 | Graphite Card | `#0f1011` | Primary card surface for general content, slightly elevated from the canvas. |
| 2 | Deep Slate Elevated Card | `#161718` | More prominent card surface, used for focused content sections or lists. |
| 3 | Charcoal Grey Overlay | `#23252a` | Accent surface for borders, shadows, and subtle overlays, providing clear separation. |

## Elevation

- **Default Card:** `rgba(0, 0, 0, 0.4) 0px 2px 4px 0px`
- **Sidebar/Menu Element Focus:** `rgba(0, 0, 0, 0.2) 0px 0px 12px 0px inset`
- **Elevated Card Inset:** `rgb(35, 37, 42) 0px 0px 0px 1px inset`
- **Card Border/Input Focus:** `rgba(0, 0, 0, 0.2) 0px 0px 0px 1px`
- **Navigation/Button Subtle Lift:** `rgba(0, 0, 0, 0.01) 0px 5px 2px 0px, rgba(0, 0, 0, 0.04) 0px 3px 2px 0px, rgba(0, 0, 0, 0.07) 0px 1px 1px 0px, rgba(0, 0, 0, 0.08) 0px 0px 1px 0px`

## Imagery

The site's visual language is dominated by UI elements and product screenshots, emphasizing functionality over decorative imagery. Where images appear, they are often contained within realistic product mockups or embedded application frames. Abstract graphics are minimal, primarily serving as subtle background textures or data visualizations. Icons are filled, minimalist, and mono-color, often adopting the 'Porcelain' (#f7f8f8) or 'Storm Cloud' (#8a8f98) neutral palette, enhancing the dashboard aesthetic. The overall density of imagery is low; it serves an explanatory or product showcase role rather than a decorative one.

## Layout

The page primarily uses a full-bleed structure for background content, with main content sections constrained by a centered maximum width (not explicitly defined but visually present). The hero section features a full-bleed 'Pitch Black' background with a centered, prominent headline. Subsequent sections alternate between dark backgrounds for narrative content and embedded UI examples, often featuring split layouts (text on one side, product UI on the other). Content is generally arranged in vertical stacks or multi-column grids for feature display. Navigation consists of a sticky top bar and frequently observed left-hand sidebar for application-like structures. Spacing is compact yet deliberate, creating a dense but organized information flow.

## Agent Prompt Guide

Quick Color Reference:
- text: #f7f8f8 (Porcelain)
- background: #08090a (Pitch Black)
- border: #23252a (Charcoal Grey)
- accent: #5e6ad2 (Aether Blue)
- primary action: #e4f222 (filled action)

3-5 Example Component Prompts:
- Create a call-to-action button: 'Neon Lime' background (#e4f222), 'Pitch Black' text (#08090a), Inter Variable font weight 590 at 15px, 6px border-radius, 12px vertical and 24px horizontal padding.
- Create a default card with content: 'Graphite' background (#0f1011), 6px border-radius, rgba(0, 0, 0, 0.4) 0px 2px 4px 0px shadow. Inside, use Inter Variable font weight 400 at 14px with 'Porcelain' text (#f7f8f8), and a subsection headline at 17px weight 510 with 'Porcelain' text (#f7f8f8). Apply 8px padding internally.
- Create a sidebar navigation item: Ghost button with transparent background, 'Storm Cloud' text (#8a8f98), Inter Variable font weight 400 at 14px, 2px border-radius, no padding.
- Create an input field: transparent background with a 'Gunmetal' fill (#383b3f), 'Light Steel' text (#d0d6e0) using Inter Variable font weight 400 at 14px, 6px border-radius. Inset with a 1px 'Charcoal Grey' border (#23252a). Padding 12px vertical and 14px horizontal.

## Similar Brands

- **Vercel** — Dark UI with strong typography, geometric layouts, and selective use of brand accent colors for interactivity.
- **GitHub** — Emphasis on functional, dark-themed UI for developer tools, prioritizing information density and code readability.
- **Notion (dark mode)** — Layered dark surfaces creating depth, clear typography, and a subdued palette for a productivity application.
- **Raycast** — High-contrast dark mode, minimalist design, and an emphasis on technical tools with clear interaction points.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-pitch-black: #08090a;
  --color-graphite: #0f1011;
  --color-deep-slate: #161718;
  --color-charcoal-grey: #23252a;
  --color-muted-ash: #323334;
  --color-gunmetal: #383b3f;
  --color-porcelain: #f7f8f8;
  --color-light-steel: #d0d6e0;
  --color-storm-cloud: #8a8f98;
  --color-fog-grey: #62666d;
  --color-alabaster: #e5e5e6;
  --color-neon-lime: #e4f222;
  --color-aether-blue: #5e6ad2;
  --color-forest-green: #008d2c;
  --color-cyan-spark: #02b8cc;
  --color-emerald: #27a644;
  --color-warning-red: #eb5757;
  --color-deep-violet: #6366f1;
  --color-amethyst: #8b5cf6;

  /* Typography — Font Families */
  --font-inter-variable: 'Inter Variable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-berkeley-mono: 'Berkeley Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.4;
  --tracking-caption: -0.1px;
  --text-body: 14px;
  --leading-body: 1.4;
  --tracking-body: -0.13px;
  --text-heading: 24px;
  --leading-heading: 1.33;
  --tracking-heading: -0.22px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -0.22px;
  --text-display: 72px;
  --leading-display: 1;
  --tracking-display: -0.22px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-w510: 510;
  --font-weight-w590: 590;

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
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-128: 128px;

  /* Layout */
  --section-gap: 24px;
  --card-padding: 12px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-md: 6px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 22px;
  --radius-full: 400px;
  --radius-full-2: 9999px;

  /* Named Radii */
  --radius-pill: 9999px;
  --radius-tags: 2px;
  --radius-cards: 6px;
  --radius-badges: 4px;
  --radius-inputs: 6px;
  --radius-buttons: 6px;
  --radius-default: 6px;

  /* Shadows */
  --shadow-sm: rgba(0, 0, 0, 0.4) 0px 2px 4px 0px;
  --shadow-md: rgba(0, 0, 0, 0.2) 0px 0px 12px 0px inset;
  --shadow-subtle: rgb(35, 37, 42) 0px 0px 0px 1px inset;
  --shadow-subtle-2: rgba(0, 0, 0, 0.2) 0px 0px 0px 1px;
  --shadow-subtle-3: rgba(0, 0, 0, 0.01) 0px 5px 2px 0px, rgba(0, 0, 0, 0.04) 0px 3px 2px 0px, rgba(0, 0, 0, 0.07) 0px 1px 1px 0px, rgba(0, 0, 0, 0.08) 0px 0px 1px 0px;
  --shadow-xl: rgba(8, 9, 10, 0.6) 0px 4px 32px 0px;
  --shadow-subtle-4: rgba(0, 0, 0, 0.1) 0px 0px 0px 2px;
  --shadow-subtle-5: rgba(0, 0, 0, 0.33) 0px 0px 0px 1px;
  --shadow-subtle-6: rgba(255, 255, 255, 0.03) 0px 0px 0px 1px inset, rgba(255, 255, 255, 0.04) 0px 1px 0px 0px inset, rgba(0, 0, 0, 0.6) 0px 0px 0px 1px, rgba(0, 0, 0, 0.1) 0px 4px 4px 0px;

  /* Surfaces */
  --surface-pitch-black-canvas: #08090a;
  --surface-graphite-card: #0f1011;
  --surface-deep-slate-elevated-card: #161718;
  --surface-charcoal-grey-overlay: #23252a;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-pitch-black: #08090a;
  --color-graphite: #0f1011;
  --color-deep-slate: #161718;
  --color-charcoal-grey: #23252a;
  --color-muted-ash: #323334;
  --color-gunmetal: #383b3f;
  --color-porcelain: #f7f8f8;
  --color-light-steel: #d0d6e0;
  --color-storm-cloud: #8a8f98;
  --color-fog-grey: #62666d;
  --color-alabaster: #e5e5e6;
  --color-neon-lime: #e4f222;
  --color-aether-blue: #5e6ad2;
  --color-forest-green: #008d2c;
  --color-cyan-spark: #02b8cc;
  --color-emerald: #27a644;
  --color-warning-red: #eb5757;
  --color-deep-violet: #6366f1;
  --color-amethyst: #8b5cf6;

  /* Typography */
  --font-inter-variable: 'Inter Variable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-berkeley-mono: 'Berkeley Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.4;
  --tracking-caption: -0.1px;
  --text-body: 14px;
  --leading-body: 1.4;
  --tracking-body: -0.13px;
  --text-heading: 24px;
  --leading-heading: 1.33;
  --tracking-heading: -0.22px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -0.22px;
  --text-display: 72px;
  --leading-display: 1;
  --tracking-display: -0.22px;

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
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-128: 128px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-md: 6px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 22px;
  --radius-full: 400px;
  --radius-full-2: 9999px;

  /* Shadows */
  --shadow-sm: rgba(0, 0, 0, 0.4) 0px 2px 4px 0px;
  --shadow-md: rgba(0, 0, 0, 0.2) 0px 0px 12px 0px inset;
  --shadow-subtle: rgb(35, 37, 42) 0px 0px 0px 1px inset;
  --shadow-subtle-2: rgba(0, 0, 0, 0.2) 0px 0px 0px 1px;
  --shadow-subtle-3: rgba(0, 0, 0, 0.01) 0px 5px 2px 0px, rgba(0, 0, 0, 0.04) 0px 3px 2px 0px, rgba(0, 0, 0, 0.07) 0px 1px 1px 0px, rgba(0, 0, 0, 0.08) 0px 0px 1px 0px;
  --shadow-xl: rgba(8, 9, 10, 0.6) 0px 4px 32px 0px;
  --shadow-subtle-4: rgba(0, 0, 0, 0.1) 0px 0px 0px 2px;
  --shadow-subtle-5: rgba(0, 0, 0, 0.33) 0px 0px 0px 1px;
  --shadow-subtle-6: rgba(255, 255, 255, 0.03) 0px 0px 0px 1px inset, rgba(255, 255, 255, 0.04) 0px 1px 0px 0px inset, rgba(0, 0, 0, 0.6) 0px 0px 0px 1px, rgba(0, 0, 0, 0.1) 0px 4px 4px 0px;
}
```

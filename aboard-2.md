# Aboard — Style Reference
> Warm pastel canvas with cheerful accents

**Theme:** light

Aboard projects a cheerful, human-centric tone through its design system, characterized by soft, rounded forms and a palette of pastel backgrounds contrasted with vivid, functional accents. Components are lightweight and unobtrusive, preferring ghost states and subtle fills over heavy borders or shadows, giving a spacious and airy feel. Typography is clean and contemporary, utilizing a system font for efficiency, and leveraging distinct letter-spacing for large headlines to create a crisp, modern presence. A playful visual language of diverse, muted color cards highlights sections and draws the eye without overwhelming the primary content.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas Ice | `#fafafa` | `--color-canvas-ice` | Page backgrounds, large container surfaces – establishes a clean, bright foundation |
| Ink | `#262626` | `--color-ink` | Primary text, prominent headings, and strong UI elements – provides crisp contrast against light backgrounds |
| Slate | `#757577` | `--color-slate` | Secondary text, navigation items, descriptive labels – provides softer contrast than Ink for less critical information |
| Whisper Gray | `#aeaeaf` | `--color-whisper-gray` | Muted text, hairline separators, disabled states – for subtle visual hierarchy |
| Outline Blue | `#008ae8` | `--color-outline-blue` | Blue outline accent for tags, dividers, and focused UI edges. Do not promote it to the primary CTA color |
| Ghost Blue | `#e0f2fe` | `--color-ghost-blue` | Subtle background for outlined buttons and light interactive states – a soft companion to Outline Blue |
| Task Card Pink | `#fbcfe8` | `--color-task-card-pink` | Background for specific card types, adds a soft, warm visual break |
| Task Card Violet | `#e6dafd` | `--color-task-card-violet` | Background for specific card types, offers a cool, muted counterpoint |
| #b6edee | `#b6edee` | `--color-b6edee` | Background for specific card types, a fresh and calm visual accent |
| Task Card Sky | `#afe4ff` | `--color-task-card-sky` | Background for specific card types, a light, open blue |
| Task Card Yellow | `#ffe77a` | `--color-task-card-yellow` | Background for specific card types marking bright, important content |
| Accent Violet | `#975aff` | `--color-accent-violet` | Decorative highlights, small icons, specific content accent – adds a vibrant touch |
| Accent Orange | `#ff6800` | `--color-accent-orange` | Decorative highlights, small icons, specific content accent – for warmth and attention |
| Accent Teal | `#00babf` | `--color-accent-teal` | Decorative highlights, small icons, specific content accent – for a hint of freshness |

## Tokens — Typography

### system-ui — All primary interface text, headlines, and body copy. Varied weights and the use of system fonts convey a lightweight yet confident presence, with distinct, subtle letter-spacing for display sizes to ensure a modern, open feel. · `--font-system-ui`
- **Substitute:** system-ui
- **Weights:** 400, 500, 600
- **Sizes:** 12px, 15px, 16px, 18px, 20px, 24px, 44px, 56px, 64px
- **Line height:** 1.00, 1.10, 1.20, 1.30, 1.40, 1.50, 1.56, 1.60, 2.00
- **Letter spacing:** -0.0100em at 64px, -0.0090em at 56px, -0.0060em at 44px, -0.0050em at 24px, normal at smaller sizes
- **Role:** All primary interface text, headlines, and body copy. Varied weights and the use of system fonts convey a lightweight yet confident presence, with distinct, subtle letter-spacing for display sizes to ensure a modern, open feel.

### sans-serif — Small functional labels, secondary navigation items, and granular interface text where high information density is required yet legibility is paramount. · `--font-sans-serif`
- **Substitute:** Arial, Helvetica
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.20
- **Letter spacing:** normal
- **Role:** Small functional labels, secondary navigation items, and granular interface text where high information density is required yet legibility is paramount.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.2 | — | `--text-caption` |
| body | 15px | 1.4 | — | `--text-body` |
| subheading | 18px | 1.5 | — | `--text-subheading` |
| heading-sm | 24px | 1.3 | -0.5px | `--text-heading-sm` |
| heading | 44px | 1.1 | -0.96px | `--text-heading` |
| heading-lg | 56px | 1 | -1px | `--text-heading-lg` |
| display | 64px | 1 | -0.64px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 8 | 8px | `--spacing-8` |
| 10 | 10px | `--spacing-10` |
| 12 | 12px | `--spacing-12` |
| 13 | 13px | `--spacing-13` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 36 | 36px | `--spacing-36` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 56 | 56px | `--spacing-56` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 96 | 96px | `--spacing-96` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 24px |
| forms | 10px |
| icons | 10px |
| buttons | 99px |

### Layout

- **Section gap:** 48px
- **Card padding:** 24px
- **Element gap:** 10px

## Components

### Ghost Primary Button
**Role:** Primary Call to Action

Text 'Book a demo' in Ink (#262626), border and text color is Outline Blue (#008ae8). Background is transparent. Padding is 10px vertical, 24px horizontal. Radius is 99px for a pill shape. Appears as a lightweight, yet clearly interactive option.

### Filled Mild Button
**Role:** Secondary Call to Action

Background is Ghost Blue (#e0f2fe). Text and border in Outline Blue (#008ae8). Padding 10px vertical, 24px horizontal. Radius is 99px. Used for less prominent CTAs, providing a softer visual cue.

### Tag Button
**Role:** Informational Tags

Small background fill of Ghost Blue (#e0f2fe). Text 'April 2026 — AI Meeting Assistant, Contracts refresh' in Outline Blue (#008ae8). Border in Outline Blue (#008ae8). Padding 4px vertical, 12px horizontal. Radius is 99px. Used for small, capsule-shaped informational tags or filters.

### Feature Card (Pink)
**Role:** Colored Content Container

Background in Task Card Pink (#fbcfe8). Radius 24px. Padding 40px top/right/left, 0px bottom. No shadow. Used for introductory content blocks, creating a distinct visual section with soft, rounded corners.

### Feature Card (Teal)
**Role:** Colored Content Container

Background in Task Card Teal (#b6edee). Radius 24px. Padding 0px. No shadow. Used for accenting specific content areas like embedded product screenshots, creating a clean, integrated look.

### Info Card (Yellow)
**Role:** Subtle Information Container

Background in Task Card Yellow (#ffe77a). Radius 24px. Padding 32px all sides. No shadow. Used for smaller, self-contained information blocks that need a bright, but not overwhelming, visual cue.

## Do's and Don'ts

### Do
- Use Canvas Ice (#fafafa) as the default background for most pages and primary content areas.
- Apply a 99px border-radius to all buttons for a friendly, pill-shaped aesthetic.
- Reserve Outline Blue (#008ae8) for all interactive text and borders of ghost/outlined buttons, indicating actionable elements.
- For headlines, pair 'system-ui' font with negative letter-spacing: -0.0100em at 64px, -0.0090em at 56px, -0.0060em at 44px, and -0.0050em at 24px.
- Employ the diverse pastel Task Card colors (e.g., #fbcfe8, #e6dafd, #b6edee, #afe4ff, #ffe77a) for distinct card backgrounds to visually segment content without heavy lines or shadows.
- Maintain a clear hierarchy using Ink (#262626) for primary text and Slate (#757577) for secondary content.
- Implement 10px as the standard elementGap for consistent spacing between interactive and inline components.

### Don't
- Avoid using harsh shadows or strong borders for cards; rely on background color and generous rounded corners for visual separation.
- Do not introduce new saturated accent colors outside of the defined Accent Violet, Orange, and Teal without explicit approval.
- Refrain from using heavily styled, solid background buttons for primary actions; prefer ghost or mild-filled variations with Outline Blue.
- Do not deviate from the 'system-ui' font family for any primary text or headlines, as its neutrality supports the clean aesthetic.
- Avoid tight element clustering; ensure a minimum elementGap of 10px is maintained between components.
- Do not use dark backgrounds for main content sections; the system is designed for a light theme with pastel accents.
- Do not use letter-spacing on body text smaller than 24px; tracking is reserved for larger display types.

## Agent Prompt Guide

### Quick Color Reference
- text: #262626 (Ink)
- background: #fafafa (Canvas Ice)
- border: #aeaeaf (Whisper Gray)
- accent: #008ae8 (Outline Blue)
- primary action: no distinct CTA color

### 3-5 Example Component Prompts
No distinct primary action color was observed; use the extracted neutral button treatments instead of inventing a filled CTA color.
- Create an informational card: Background Task Card Pink (#fbcfe8). Radius 24px. Padding 40px all around. Headline 'Key Features' using system-ui at 24px, weight 500, Ink (#262626). Body text 'Streamline your HR workflows' using system-ui at 15px, weight 400, Slate (#757577).
- Create a functional badge: Background Ghost Blue (#e0f2fe). Text 'New Feature' in Outline Blue (#008ae8). Padding 4px vertical, 12px horizontal. Radius 99px.

## Similar Brands

- **Monday.com** — Uses pastel color blocks and cards to differentiate sections and content, often with rounded corners.
- **Notion** — Clean, predominantly light interface with a focus on system fonts and minimal decorative elements, relying on clear hierarchy and spacing.
- **Asana** — Employs a friendly, task-oriented design with light backgrounds and a clear primary accent color for interactive elements.
- **Sunsama** — Prioritizes a soothing, low-friction user experience with muted backgrounds and clear, functional type.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-ice: #fafafa;
  --color-ink: #262626;
  --color-slate: #757577;
  --color-whisper-gray: #aeaeaf;
  --color-outline-blue: #008ae8;
  --color-ghost-blue: #e0f2fe;
  --color-task-card-pink: #fbcfe8;
  --color-task-card-violet: #e6dafd;
  --color-b6edee: #b6edee;
  --color-task-card-sky: #afe4ff;
  --color-task-card-yellow: #ffe77a;
  --color-accent-violet: #975aff;
  --color-accent-orange: #ff6800;
  --color-accent-teal: #00babf;

  /* Typography — Font Families */
  --font-system-ui: 'system-ui', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.2;
  --text-body: 15px;
  --leading-body: 1.4;
  --text-subheading: 18px;
  --leading-subheading: 1.5;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.3;
  --tracking-heading-sm: -0.5px;
  --text-heading: 44px;
  --leading-heading: 1.1;
  --tracking-heading: -0.96px;
  --text-heading-lg: 56px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -1px;
  --text-display: 64px;
  --leading-display: 1;
  --tracking-display: -0.64px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-13: 13px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;

  /* Layout */
  --section-gap: 48px;
  --card-padding: 24px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-md: 6px;
  --radius-lg: 10px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;
  --radius-full: 99px;

  /* Named Radii */
  --radius-cards: 24px;
  --radius-forms: 10px;
  --radius-icons: 10px;
  --radius-buttons: 99px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-ice: #fafafa;
  --color-ink: #262626;
  --color-slate: #757577;
  --color-whisper-gray: #aeaeaf;
  --color-outline-blue: #008ae8;
  --color-ghost-blue: #e0f2fe;
  --color-task-card-pink: #fbcfe8;
  --color-task-card-violet: #e6dafd;
  --color-b6edee: #b6edee;
  --color-task-card-sky: #afe4ff;
  --color-task-card-yellow: #ffe77a;
  --color-accent-violet: #975aff;
  --color-accent-orange: #ff6800;
  --color-accent-teal: #00babf;

  /* Typography */
  --font-system-ui: 'system-ui', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.2;
  --text-body: 15px;
  --leading-body: 1.4;
  --text-subheading: 18px;
  --leading-subheading: 1.5;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.3;
  --tracking-heading-sm: -0.5px;
  --text-heading: 44px;
  --leading-heading: 1.1;
  --tracking-heading: -0.96px;
  --text-heading-lg: 56px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -1px;
  --text-display: 64px;
  --leading-display: 1;
  --tracking-display: -0.64px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-13: 13px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-md: 6px;
  --radius-lg: 10px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;
  --radius-full: 99px;
}
```

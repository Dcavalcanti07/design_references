# dope.security — Style Reference
> Celestial command center

**Theme:** dark

Dope.security establishes a celestial-tech aesthetic: dark, ethereal backgrounds evoke a night sky, contrasted by sharp, almost glowing typography. Translucent frosted glass elements and subtle, vibrant gradients create a sense of advanced technology. The system balances highly stylized display fonts for impact with clean, legible sans-serifs for detail, and uses a single strong violet accent to highlight critical actions, ensuring focus within the dark UI.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Eclipse | `#090909` | `--color-midnight-eclipse` | Page backgrounds, card containers, dark base for interactive elements |
| Cloud Whisper | `#f7f9fa` | `--color-cloud-whisper` | Primary text, headers, icon fills, and borders on dark backgrounds. Creates bright contrast |
| Code Ghost | `#f0f0f0` | `--color-code-ghost` | Secondary text in lists, code snippets, and specific heading styles. Slightly softer than Cloud Whisper |
| Slate Hint | `#6b6b6b` | `--color-slate-hint` | Muted text, iconography, and subtle borders for outlines or inactive states |
| Steel Accent | `#475467` | `--color-steel-accent` | Borders for ghost buttons and subtle accent text, especially in navigation |
| Deep Violet | `#af50ff` | `--color-deep-violet` | Primary action background, interactive element highlights, and brand accents. Provides a vivid focal point |
| Cosmic Gradient A | `radial-gradient(circle closest-corner at 10% 50%, rgb(108, 75, 214), rgba(0, 0, 0, 0) 55%)` | `--color-cosmic-gradient-a` | Hero section background, atmospheric graphic elements. Creates a deep, dramatic sky effect |
| Cosmic Gradient B | `linear-gradient(90deg, rgb(64, 24, 96), rgb(72, 35, 180) 50%, rgb(99, 78, 120))` | `--color-cosmic-gradient-b` | Background for feature cards, creating a dynamic, blended surface |

## Tokens — Typography

### Whyte Inktrap — Primary UI text, body copy, subheadings, and some display text. The variable letter-spacing provides a compressed, technical feel at larger sizes but remains legible at smaller scales. · `--font-whyte-inktrap`
- **Substitute:** Montserrat, sans-serif
- **Weights:** 300, 400, 500, 700
- **Sizes:** 10px, 12px, 14px, 16px, 18px, 20px, 24px, 28px, 32px, 40px, 48px, 49px, 50px, 64px, 80px, 88px
- **Line height:** 0.80, 0.90, 1.00, 1.11, 1.20, 1.25, 1.50, 1.56, 1.60
- **Letter spacing:** -0.07em at 88px, -0.04em at 64px, -0.03em at 50px, -0.01em at 24px, normal at 16px and below
- **Role:** Primary UI text, body copy, subheadings, and some display text. The variable letter-spacing provides a compressed, technical feel at larger sizes but remains legible at smaller scales.

### Whyte Inktrap Mono — Monospaced text for specific section headings, code examples, and technical annotations. The wide letter-spacing gives a distinct, almost coded aesthetic. · `--font-whyte-inktrap-mono`
- **Substitute:** Space Mono, monospace
- **Weights:** 400
- **Sizes:** 14px, 74px
- **Line height:** 0.90, 1.50
- **Letter spacing:** 0.2em
- **Role:** Monospaced text for specific section headings, code examples, and technical annotations. The wide letter-spacing gives a distinct, almost coded aesthetic.

### GrandSlang — Hero headlines and large display marketing text. The lighter weights and tight tracking create a distinguished, authoritative presence that feels modern yet substantial. · `--font-grandslang`
- **Substitute:** Playfair Display, serif
- **Weights:** 300, 400
- **Sizes:** 32px, 50px, 64px, 88px, 146px
- **Line height:** 0.80, 1.20, 1.25, 1.50
- **Letter spacing:** -0.03em
- **Role:** Hero headlines and large display marketing text. The lighter weights and tight tracking create a distinguished, authoritative presence that feels modern yet substantial.

### system-ui — system-ui — detected in extracted data but not described by AI · `--font-system-ui`
- **Weights:** 600
- **Sizes:** 16px
- **Line height:** 1.5
- **Role:** system-ui — detected in extracted data but not described by AI

### Karla — Karla — detected in extracted data but not described by AI · `--font-karla`
- **Weights:** 700
- **Sizes:** 16px
- **Line height:** 1, 1.2
- **Role:** Karla — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.5 | — | `--text-caption` |
| body-sm | 14px | 1.5 | — | `--text-body-sm` |
| body | 16px | 1.5 | — | `--text-body` |
| subheading | 24px | 1.5 | -0.24px | `--text-subheading` |
| heading-sm | 32px | 1.25 | -0.96px | `--text-heading-sm` |
| heading | 50px | 0.9 | -1.5px | `--text-heading` |
| heading-lg | 74px | 0.9 | 1.48px | `--text-heading-lg` |
| display | 88px | 0.8 | -6.16px | `--text-display` |

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
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 72 | 72px | `--spacing-72` |
| 80 | 80px | `--spacing-80` |
| 96 | 96px | `--spacing-96` |
| 128 | 128px | `--spacing-128` |
| 136 | 136px | `--spacing-136` |
| 160 | 160px | `--spacing-160` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 99px |
| cards | 19.2px |
| buttons | 8px |
| circular | 10000px |
| pillButtons | 1584px |
| smallWidgets | 10.8px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(16, 24, 40, 0.05) 0px 1px 2px 0px` | `--shadow-subtle` |

### Layout

- **Page max-width:** 1200px
- **Section gap:** 64px
- **Card padding:** 16px
- **Element gap:** 16px

## Components

### Primary Filled Button
**Role:** Call to action.

Filled with Deep Violet (#af50ff), white text (#f7f9fa), 8px border-radius, 16px vertical and 16px horizontal padding. Font: Whyte Inktrap, weight 700.

### Ghost Button (Primary)
**Role:** Secondary call to action.

Transparent background, Steel Accent (#475467) text and border, 0px border-radius, 10.4px top/bottom padding, 0px left/right padding. Used for subtle navigation or inline actions.

### Pill Button
**Role:** Interactive filters or small, rounded CTAs.

Background color rgba(237, 195, 196, 0.05), Cloud Whisper text (#f7f9fa), 1584px border-radius, 20px vertical and 32px horizontal padding. Creates a soft, distinct interactive element.

### Small Ghost Button
**Role:** Tertiary actions or compact navigation items.

Background rgba(247, 249, 250, 0.08), Cloud Whisper text (#f7f9fa), 6px border-radius, 9px vertical and 15px horizontal padding. Used for less prominent actions.

### Frosted Card (Large)
**Role:** Content segmentation and informational display, primarily in hero sections.

Transparent background (rgba(0,0,0,0)), 19.2px border-radius, no shadow. Content within uses Cloud Whisper and Slate Hint for text.

### Frosted Card (Small)
**Role:** Nested content or smaller feature blocks.

Transparent background (rgba(0,0,0,0)), 10.8px border-radius, no shadow.

### Navigation Link
**Role:** Primary navigation.

Cloud Whisper (#f7f9fa) text, Whyte Inktrap, 16px, weight 400. Inactive text uses Slate Hint (#6b6b6b). Active state indicated by a 1px bottom border in Deep Violet (#7f56d9).

### Text Block Heading (Mono)
**Role:** Section titles presenting technical concepts or lists.

Code Ghost (#f0f0f0) text, Whyte Inktrap Mono, 74px, weight 400, letter-spacing 0.2em. Rendered all caps to enhance the technical, coded feel.

## Do's and Don'ts

### Do
- Prioritize Midnight Eclipse (#090909) for all large background areas and surfaces to maintain the dark theme.
- Use Cloud Whisper (#f7f9fa) for primary text and critical information to ensure high contrast and legibility.
- Apply Deep Violet (#af50ff) exclusively for primary calls to action, active states, and small, potent brand accents.
- Employ Whythe Inktrap with negative letter-spacing for large headlines to create a condensed, forceful typography style.
- Utilize GrandSlang for hero headlines, leveraging its light weights and tight tracking for a sophisticated, high-impact statement.
- Integrate frosted glass effects (using `backdrop-filter: blur(10px)` or similar) on modals or prominent UI elements to complement the celestial-tech aesthetic.
- Maintain consistent 8px for button radii and 19.2px for card radii to reinforce the subtle rounding throughout the UI.

### Don't
- Avoid using saturated colors other than Deep Violet without specific design system approval, to preserve the monochrome base and accent strategy.
- Do not introduce heavy drop shadows or strong borders on cards; surfaces should primarily be transparent or use subtle blur effects.
- Refrain from using generic sans-serifs for headlines; GrandSlang and Whyte Inktrap are essential for brand typographic identity.
- Do not use generic system fonts for any primary content or UI elements; use Whyte Inktrap for all standard text roles.
- Avoid arbitrary text colors; all text should derive from Cloud Whisper, Code Ghost, Slate Hint, or Steel Accent based on hierarchy.
- Do not clutter layouts with excessive imagery; the aesthetic is text-dominant with strategic visual elements.
- Avoid inconsistent spacing; adhere to the 16px element and card padding, and 64px section gap for vertical rhythm.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Deep Space Canvas | `#090909` | Primary page background, base for all content sections. |
| 1 | Frosted Pane | `#00000000` | Translucent elements within sections, often with backdrop blur, such as informational cards or content containers in headers. |
| 2 | Gradient Field | `#401860` | Layered backgrounds for feature cards or interactive modules, providing subtle color variation through gradients. |

## Imagery

The imagery aesthetic is characterized by abstract, ethereal graphics and heavily stylized product illustrations/icons. Photography is minimal, if present. Visuals like the 'vapor trail' airplane and cloud formations reinforce the celestial-tech theme. Icons are predominantly outlined (`stroke-width` suggests a thin weight), monochromatic, and often integrated into button-like elements. Imagery is used decoratively to establish atmosphere rather than convey explicit product features, often interacting with text or UI elements through transparency. Density is text-dominant, with imagery serving as atmospheric backdrops or small, functional accents.

## Layout

The page uses a maximum-width contained layout, typically setting content within a 1200px constraint, though some hero elements breach this for full-bleed atmospheric effects. The hero section is full-bleed, featuring a dark, gradient background with a prominent centered headline and interactive elements (frosted cards for calls to action). Subsequent sections alternate between uniform dark backgrounds and gradient-infused card arrays. Content arrangement often features centered stacks for headlines and subtext, and symmetrical multi-column grids for feature comparison or lists, with visual dividers enhancing flow. Vertical rhythm is consistent with a 64px section gap. A sticky top navigation bar provides continuous access to main categories and action buttons.

## Agent Prompt Guide

Quick Color Reference:
text: #f7f9fa
background: #090909
border: #6b6b6b
accent: #af50ff
primary action: #af50ff (filled action)

Example Component Prompts:
1. Create a Hero Headline: Text 'Your new Secure Web Gateway' using GrandSlang, weight 300, size 88px, #f7f9fa, letter-spacing -6.16px, line-height 0.8. Position centrally over Cosmic Gradient A background.
2. Build a Primary Action Button for 'Get Started': Filled with Deep Violet (#af50ff), Cloud Whisper text (#f7f9fa), 8px border-radius, 16px padding on all sides. Font: Whyte Inktrap, weight 700.
3. Design a Frosted Feature Card: Transparent background (rgba(0,0,0,0)), 19.2px border-radius. Inner heading (Whyte Inktrap, 24px, #f7f9fa, letter-spacing -0.24px).
4. Create a Monospace Section Title: Text 'BLOCK PERSONAL EMAIL' using Whyte Inktrap Mono, weight 400, size 74px, #f0f0f0, letter-spacing 1.48px. Background is Midnight Eclipse (#090909).

## Similar Brands

- **Linear** — Shares a meticulous dark UI, strong typographic hierarchy with custom fonts, and minimal color accents for functionality.
- **Tailwind UI (dark mode demos)** — Features a similar combination of minimalist dark surfaces contrasted with crisp whites and single-color functional accents.
- **Vercel** — Employs an elevated dark theme with subtle gradients and a strong focus on technical typography and clear, concise communication.
- **Supabase** — Utilizes a dark, ethereal aesthetic with space-like imagery and vivid single-hue accents for interactive elements.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-eclipse: #090909;
  --color-cloud-whisper: #f7f9fa;
  --color-code-ghost: #f0f0f0;
  --color-slate-hint: #6b6b6b;
  --color-steel-accent: #475467;
  --color-deep-violet: #af50ff;
  --color-cosmic-gradient-a: #6c4bd6;
  --gradient-cosmic-gradient-a: radial-gradient(circle closest-corner at 10% 50%, rgb(108, 75, 214), rgba(0, 0, 0, 0) 55%);
  --color-cosmic-gradient-b: #401860;
  --gradient-cosmic-gradient-b: linear-gradient(90deg, rgb(64, 24, 96), rgb(72, 35, 180) 50%, rgb(99, 78, 120));

  /* Typography — Font Families */
  --font-whyte-inktrap: 'Whyte Inktrap', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-whyte-inktrap-mono: 'Whyte Inktrap Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-grandslang: 'GrandSlang', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-system-ui: 'system-ui', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-karla: 'Karla', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 24px;
  --leading-subheading: 1.5;
  --tracking-subheading: -0.24px;
  --text-heading-sm: 32px;
  --leading-heading-sm: 1.25;
  --tracking-heading-sm: -0.96px;
  --text-heading: 50px;
  --leading-heading: 0.9;
  --tracking-heading: -1.5px;
  --text-heading-lg: 74px;
  --leading-heading-lg: 0.9;
  --tracking-heading-lg: 1.48px;
  --text-display: 88px;
  --leading-display: 0.8;
  --tracking-display: -6.16px;

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
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-128: 128px;
  --spacing-136: 136px;
  --spacing-160: 160px;

  /* Layout */
  --page-max-width: 1200px;
  --section-gap: 64px;
  --card-padding: 16px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-lg-2: 10.8px;
  --radius-2xl: 19.2px;
  --radius-full: 99px;
  --radius-full-2: 1584px;
  --radius-full-3: 10000px;

  /* Named Radii */
  --radius-tags: 99px;
  --radius-cards: 19.2px;
  --radius-buttons: 8px;
  --radius-circular: 10000px;
  --radius-pillbuttons: 1584px;
  --radius-smallwidgets: 10.8px;

  /* Shadows */
  --shadow-subtle: rgba(16, 24, 40, 0.05) 0px 1px 2px 0px;

  /* Surfaces */
  --surface-deep-space-canvas: #090909;
  --surface-frosted-pane: #00000000;
  --surface-gradient-field: #401860;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-eclipse: #090909;
  --color-cloud-whisper: #f7f9fa;
  --color-code-ghost: #f0f0f0;
  --color-slate-hint: #6b6b6b;
  --color-steel-accent: #475467;
  --color-deep-violet: #af50ff;
  --color-cosmic-gradient-a: #6c4bd6;
  --color-cosmic-gradient-b: #401860;

  /* Typography */
  --font-whyte-inktrap: 'Whyte Inktrap', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-whyte-inktrap-mono: 'Whyte Inktrap Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-grandslang: 'GrandSlang', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-system-ui: 'system-ui', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-karla: 'Karla', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 24px;
  --leading-subheading: 1.5;
  --tracking-subheading: -0.24px;
  --text-heading-sm: 32px;
  --leading-heading-sm: 1.25;
  --tracking-heading-sm: -0.96px;
  --text-heading: 50px;
  --leading-heading: 0.9;
  --tracking-heading: -1.5px;
  --text-heading-lg: 74px;
  --leading-heading-lg: 0.9;
  --tracking-heading-lg: 1.48px;
  --text-display: 88px;
  --leading-display: 0.8;
  --tracking-display: -6.16px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-128: 128px;
  --spacing-136: 136px;
  --spacing-160: 160px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-lg-2: 10.8px;
  --radius-2xl: 19.2px;
  --radius-full: 99px;
  --radius-full-2: 1584px;
  --radius-full-3: 10000px;

  /* Shadows */
  --shadow-subtle: rgba(16, 24, 40, 0.05) 0px 1px 2px 0px;
}
```

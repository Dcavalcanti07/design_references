# Replicate — Style Reference
> Neon Gradient Playground. The site feels like an interactive playground built on a fluctuating neon energy field.

**Theme:** light

Replicate offers a dynamic and playful interface that contrasts with its technical subject matter. A vibrant pink-red-yellow gradient serves as a high-energy backdrop, reminiscent of digital signal pathways, while the primary content remains crisp and legible on white and dark gray surfaces. The design balances a bold, almost disruptive hero with a structured, informative presentation lower down the page, using rounded forms sparingly but deliberately to soften areas of interaction amidst sharp-cornered content blocks.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Absolute Zero | `#202020` | `--color-absolute-zero` | Primary text, deep backgrounds, icon fills, button text on light buttons. |
| Alabaster | `#ffffff` | `--color-alabaster` | Page backgrounds, card surfaces, ghost button backgrounds. |
| Graphite | `#646464` | `--color-graphite` | Secondary text, subtle borders, input placeholders. |
| Silver Mist | `#bfbfbf` | `--color-silver-mist` | Decorative lines, subtle box shadows, inactive states. |
| Whisper White | `#f9f9f9` | `--color-whisper-white` | Subtle background for alternating sections or hovered elements. |
| Outline Gray | `#d9d9d9` | `--color-outline-gray` | Light borders and separators, especially for interactive elements. |
| Blackhole | `#000000` | `--color-blackhole` | Strong button backgrounds, prominent icon fills, high-contrast text. |
| Cosmic Candy | `#ea2804` | `--color-cosmic-candy` | Prominent links, highlighted text, and the dominant color in the hero gradient — an energetic accent that infuses the UI with a sense of playfulness. |
| Deep Space Blue | `#032f62` | `--color-deep-space-blue` | Informational text backgrounds, subtle brand accents — provides a sober counterpoint to the vibrant gradients. |
| Sunset Burst | `#dd4425` | `--color-sunset-burst` | Secondary CTA buttons, interactive element outlines — a slightly less intense brand orange. |
| Data Bloom Gradient | `linear-gradient(to right bottom, rgb(255, 107, 252), rgb(234, 40, 4), rgb(246, 244, 127))` | `--color-data-bloom-gradient` | Hero section background, large brand elements — this gradient defines the site's bold, energetic visual signature. |
| API Success Green | `#2b9a66` | `--color-api-success-green` | Status indicators, success badges — denotes positive feedback. |

## Tokens — Typography

### rb-freigeist-neue — Primary headings and display text. The tight letter-spacing gives headings a compact, impactful look that aligns with a clean, modern aesthetic. · `--font-rb-freigeist-neue`
- **Substitute:** Montserrat
- **Weights:** 400, 600, 700
- **Sizes:** 16px, 30px, 48px, 72px, 128px
- **Line height:** 1.00, 1.20, 1.50
- **Letter spacing:** -0.0250em
- **Role:** Primary headings and display text. The tight letter-spacing gives headings a compact, impactful look that aligns with a clean, modern aesthetic.

### basier-square — Body text, navigation, and most UI elements. The consistent negative letter-spacing subtly distinguishes it from generic sans-serifs, contributing to a polished, readable feel. · `--font-basier-square`
- **Substitute:** Inter
- **Weights:** 400, 600
- **Sizes:** 12px, 14px, 16px, 18px, 20px, 24px, 29px
- **Line height:** 1.11, 1.33, 1.40, 1.43, 1.50, 1.56
- **Letter spacing:** -0.0250em
- **Role:** Body text, navigation, and most UI elements. The consistent negative letter-spacing subtly distinguishes it from generic sans-serifs, contributing to a polished, readable feel.

### jetbrains-mono — Code snippets, technical labels, and console-like outputs. Its monospace nature clearly segregates programmatic content from natural language. · `--font-jetbrains-mono`
- **Substitute:** Inconsolata
- **Weights:** 400
- **Sizes:** 10px, 11px, 14px, 16px
- **Line height:** 1.43, 1.50
- **Letter spacing:** normal
- **Role:** Code snippets, technical labels, and console-like outputs. Its monospace nature clearly segregates programmatic content from natural language.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.43 | — | `--text-caption` |
| body | 14px | 1.43 | -0.35px | `--text-body` |
| body-lg | 16px | 1.5 | -0.4px | `--text-body-lg` |
| subheading | 18px | 1.5 | -0.45px | `--text-subheading` |
| heading | 24px | 1.33 | -0.6px | `--text-heading` |
| heading-lg | 30px | 1.2 | — | `--text-heading-lg` |
| display | 48px | 1.2 | -1.2px | `--text-display` |
| display-lg | 72px | 1 | -1.8px | `--text-display-lg` |
| display-xl | 128px | 1 | -3.2px | `--text-display-xl` |

## Tokens — Spacing & Shapes

**Base unit:** 8px

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 8 | 8px | `--spacing-8` |
| 16 | 16px | `--spacing-16` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 96 | 96px | `--spacing-96` |
| 144 | 144px | `--spacing-144` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 0px |
| badges | 9999px |
| buttons | 9999px |
| defaults | 0px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgb(228, 199, 103) 0px 1px 2px 0px` | `--shadow-subtle` |

### Layout

- **Section gap:** 48px
- **Card padding:** 16px
- **Element gap:** 8px

## Components

### Primary Filled Button
**Role:** Call to action.

backgroundColor=#000000, color=#ffffff, borderRadius=0px, paddingTop=12px, paddingRight=16px, paddingBottom=12px, paddingLeft=16px. Typography: 'basier-square', 600, 16px.

### Standard Ghost Button
**Role:** Secondary navigation and non-critical actions.

backgroundColor=rgba(0, 0, 0, 0), color=#202020, borderRadius=0px, padding: implicit to content. Used for tabs and filtering.

### Pill Accent Button
**Role:** Highlighting specific features or actions.

backgroundColor=rgba(0, 0, 0, 0.3), color=rgba(255, 255, 255, 0.9), borderRadius=9999px, paddingTop=2px, paddingRight=10px, paddingBottom=2px, paddingLeft=10px. Often seen within the gradient hero or code blocks.

### Large Search Input (Hero)
**Role:** Prominent site-wide search/query.

backgroundColor=rgba(255, 255, 255, 0.1), color=#202020 for text, placeholder color is implicit. paddingTop=6px, paddingRight=56px, paddingBottom=6px, paddingLeft=28px. No visible border initially, blends with background.

### Code Block Input
**Role:** Interactive code editor or display.

backgroundColor=rgba(0, 0, 0, 0), color=#fcfcfc. Used within the multi-tab (Node, Python, HTTP) code display, allowing for code entry without distinct borders.

### Success Badge
**Role:** Indicating successful status or 'Official' tags.

backgroundColor=#2b9a66, color=#ffffff, borderRadius=9999px. Padding implied from content: 'Official' with minimal padding.

### Model Card (Small)
**Role:** Displaying individual ML models.

backgroundColor=#ffffff, color=#202020, border: implicit subtle light gray outline, padding: 16px. No explicit border-radius, appears sharp-edged. Features specific image, title, and run count.

### Navigation Link
**Role:** Header navigation and secondary links.

color=#202020 (default), #ea2804 (hover/active), no underline by default. Typography: 'basier-square', 400 or 600 weight, 16px.

## Do's and Don'ts

### Do
- Apply the Data Bloom Gradient (`linear-gradient(to right bottom, rgb(255, 107, 252), rgb(234, 40, 4), rgb(246, 244, 127))`) for all new hero sections and large marketing blocks to maintain visual brand identity.
- Use Absolute Zero (#202020) for primary body text, headings, and bold calls to action on light backgrounds, ensuring high contrast.
- Construct buttons with a 0px border-radius unless they are specifically 'pill' style (9999px radius), creating a mix of sharp and soft forms.
- Utilize 'rb-freigeist-neue' with -0.0250em letter-spacing for all significant headings (H1-H3) to impart a distinct, modern, and compact appearance.
- Implement `jetbrains-mono` for all code examples, technical labels, and console-like outputs to clearly delineate them from editorial content, using its default sizing.
- Maintain a default card padding of 16px to ensure consistent content density within information blocks.
- Employ the Pill Accent Button (`backgroundColor=rgba(0, 0, 0, 0.3), color=rgba(255, 255, 255, 0.9), borderRadius=9999px, paddingTop=2px, paddingRight=10px, paddingBottom=2px, paddingLeft=10px`) for secondary, context-specific actions within dynamic areas or code blocks.

### Don't
- Avoid using generic blue for interactive elements; instead, leverage Cosmic Candy (#ea2804) for primary links and accents.
- Do not introduce heavy shadows or complex elevations; stick to the minimal boxShadow (`rgb(228, 199, 103) 0px 1px 2px 0px`) for subtle visual lift.
- Refrain from using rounded corners on standard content cards or generic inputs; these should generally maintain a 0px border-radius.
- Do not deviate from the specified negative letter-spacing for 'basier-square' and 'rb-freigeist-neue'; it is a key typographic characteristic.
- Avoid decorative imagery or large graphics that distract from the UI elements; primary focus is on functionality and code.
- Do not use dark backgrounds for major content sections below the hero; these should primarily be Alabaster (#ffffff) or Whisper White (#f9f9f9).
- Never replace 'jetbrains-mono' with a proportional font for code snippets; monospace is essential for code readability.

## Imagery

The visual language is split between functional UI elements and captivating, almost surreal product examples. Product imagery consists of tight, decontextualized crops (like the banana chair) that are both whimsical and illustrative of AI capabilities. Icons are primarily monochrome, outlining crucial functions without adding visual noise. Visuals serve an explanatory role, showcasing the creative outputs of AI models rather than being decorative or lifestyle-oriented. Density is image-moderate: product examples are interspersed to break up text and code, but text remains dominant in information-heavy sections. Treatment is generally contained, sharp-edged, and presented within clean borders, contrasting with the fluid background gradient.

## Layout

The site employs a mixed layout strategy: the hero section is full-bleed, dominated by a vibrant, energetic gradient background and a prominent centered headline. Below the hero, the layout transitions to a max-width contained area, centered on the page for readability. Section rhythm is varied; some sections have large vertical gaps, while others are more compact, presenting interactive elements like model cards in a loose grid. Content arrangement frequently uses 2-column structures, with code blocks often appearing next to descriptive text. A distinctive feature is the horizontal scrolling carousel of model categories and a 3-column implicit card grid for showcasing individual AI models, giving a dense, explorable feel. The navigation is a sticky top bar, providing persistent access across the site.

## Agent Prompt Guide

### Quick Color Reference
- Text: #202020
- Background: #ffffff
- CTA Button: #000000
- Primary Accent: #ea2804
- Hero Gradient: linear-gradient(to right bottom, rgb(255, 107, 252), rgb(234, 40, 4), rgb(246, 244, 127))

### 3-5 Example Component Prompts
1. Create a hero section: full-bleed background using and animating the Data Bloom Gradient (linear-gradient(to right bottom, rgb(255, 107, 252), rgb(234, 40, 4), rgb(246, 244, 127))). Centered headline 'Run AI with an API.' using 'rb-freigeist-neue' 128px weight 700 with a -3.2px letter-spacing, color #ffffff. Below, a secondary action button 'Get started for free' at 16px font size with weight 600, foreground color #ffffff, background color #000000, 12px 16px padding, 0px border-radius.
2. Design a 'Model Card' component: 0px border-radius, background #ffffff, 16px padding on all sides. Internal text color #202020. Headline 'black-forest-labs/flux-2-max' at 18px 'basier-square' weight 600. A 'Pill Accent Button' (background rgba(0,0,0,0.3), text rgba(255,255,255,0.9), 9999px radius, 2px 10px padding) for 'Official' status.
3. Implement a code block section: Use Alabaster (#ffffff) background for the overall section. Present three tabs (Node, Python, HTTP). Active tab 'Node' with Underground (#202020) text, inactive tabs 'Python' and 'HTTP' with Graphite (#646464) text. The code input area should have a transparent background (rgba(0,0,0,0)) and text color of #fcfcfc, using 'jetbrains-mono' 14px weight 400. Ensure 8px gaps between elements within the block.

## Similar Brands

- **Vercel** — Shares a developer-centric focus with clean UI, dark mode sections, and monospace font for code. Also uses gradients in hero sections.
- **GitHub** — Similar emphasis on code, developer tooling, and a blend of structured informational content with subtle interactive elements.
- **Hugging Face** — Another AI/ML platform featuring a clean interface, model showcases, and a focus on both code and user-friendly exploration of technical concepts.
- **Stripe (older designs)** — The use of an energetic, almost 'electric' gradient as a core brand element, contrasting with otherwise highly functional and clear UI.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-absolute-zero: #202020;
  --color-alabaster: #ffffff;
  --color-graphite: #646464;
  --color-silver-mist: #bfbfbf;
  --color-whisper-white: #f9f9f9;
  --color-outline-gray: #d9d9d9;
  --color-blackhole: #000000;
  --color-cosmic-candy: #ea2804;
  --color-deep-space-blue: #032f62;
  --color-sunset-burst: #dd4425;
  --color-data-bloom-gradient: #ff6bfc;
  --gradient-data-bloom-gradient: linear-gradient(to right bottom, rgb(255, 107, 252), rgb(234, 40, 4), rgb(246, 244, 127));
  --color-api-success-green: #2b9a66;

  /* Typography — Font Families */
  --font-rb-freigeist-neue: 'rb-freigeist-neue', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-basier-square: 'basier-square', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-jetbrains-mono: 'jetbrains-mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.43;
  --text-body: 14px;
  --leading-body: 1.43;
  --tracking-body: -0.35px;
  --text-body-lg: 16px;
  --leading-body-lg: 1.5;
  --tracking-body-lg: -0.4px;
  --text-subheading: 18px;
  --leading-subheading: 1.5;
  --tracking-subheading: -0.45px;
  --text-heading: 24px;
  --leading-heading: 1.33;
  --tracking-heading: -0.6px;
  --text-heading-lg: 30px;
  --leading-heading-lg: 1.2;
  --text-display: 48px;
  --leading-display: 1.2;
  --tracking-display: -1.2px;
  --text-display-lg: 72px;
  --leading-display-lg: 1;
  --tracking-display-lg: -1.8px;
  --text-display-xl: 128px;
  --leading-display-xl: 1;
  --tracking-display-xl: -3.2px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-96: 96px;
  --spacing-144: 144px;

  /* Layout */
  --section-gap: 48px;
  --card-padding: 16px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-cards: 0px;
  --radius-badges: 9999px;
  --radius-buttons: 9999px;
  --radius-defaults: 0px;

  /* Shadows */
  --shadow-subtle: rgb(228, 199, 103) 0px 1px 2px 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-absolute-zero: #202020;
  --color-alabaster: #ffffff;
  --color-graphite: #646464;
  --color-silver-mist: #bfbfbf;
  --color-whisper-white: #f9f9f9;
  --color-outline-gray: #d9d9d9;
  --color-blackhole: #000000;
  --color-cosmic-candy: #ea2804;
  --color-deep-space-blue: #032f62;
  --color-sunset-burst: #dd4425;
  --color-data-bloom-gradient: #ff6bfc;
  --color-api-success-green: #2b9a66;

  /* Typography */
  --font-rb-freigeist-neue: 'rb-freigeist-neue', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-basier-square: 'basier-square', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-jetbrains-mono: 'jetbrains-mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.43;
  --text-body: 14px;
  --leading-body: 1.43;
  --tracking-body: -0.35px;
  --text-body-lg: 16px;
  --leading-body-lg: 1.5;
  --tracking-body-lg: -0.4px;
  --text-subheading: 18px;
  --leading-subheading: 1.5;
  --tracking-subheading: -0.45px;
  --text-heading: 24px;
  --leading-heading: 1.33;
  --tracking-heading: -0.6px;
  --text-heading-lg: 30px;
  --leading-heading-lg: 1.2;
  --text-display: 48px;
  --leading-display: 1.2;
  --tracking-display: -1.2px;
  --text-display-lg: 72px;
  --leading-display-lg: 1;
  --tracking-display-lg: -1.8px;
  --text-display-xl: 128px;
  --leading-display-xl: 1;
  --tracking-display-xl: -3.2px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-96: 96px;
  --spacing-144: 144px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-full: 9999px;

  /* Shadows */
  --shadow-subtle: rgb(228, 199, 103) 0px 1px 2px 0px;
}
```

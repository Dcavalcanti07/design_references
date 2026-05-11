# Vapi — Style Reference
> Midnight console, glowing accents

**Theme:** dark

Vapi employs a dark, high-contrast digital interface that feels like a polished dev-tool. Stark whites and desaturated grays provide structure, punctuated by a palette of functional, vivid hues for active elements, illustrations, and status. Typography is compact and precise, maintaining a clear hierarchy. Components are minimal, often outlined or ghosted, emphasizing content and a clean, spacious presentation on a deep charcoal background.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Deep Midnight | `#0e0e13` | `--color-deep-midnight` | Primary page background, elevated card surfaces, dark text on vivid buttons |
| Charcoal Slate | `#27272a` | `--color-charcoal-slate` | Subtle borders, dividers, footer backgrounds, contrasting panels |
| Silver Moonlight | `#d8d7d4` | `--color-silver-moonlight` | Primary text color for body copy and headings on dark backgrounds, ghost button borders |
| Whisper White | `#fffaea` | `--color-whisper-white` | Main text color on dark backgrounds, active states, button backgrounds for ghost buttons, occasional light surface element |
| Faded Steel | `#a1a1aa` | `--color-faded-steel` | Muted secondary text, helper text, subtle icon detailing |
| Interface Gray | `#d9e6ef` | `--color-interface-gray` | Soft icon strokes, subtle dividers, and low-emphasis decorative details. Do not promote it to the primary CTA color |
| Soft Black | `#09090b` | `--color-soft-black` | Dark text on light surfaces (e.g., within light buttons), also used for list backgrounds |
| Sunken Black | `#18181b` | `--color-sunken-black` | A further recessed background or card surface variation |
| Vapi Orange | `#e96b34` | `--color-vapi-orange` | Primary Call-to-Action button fills, accents, and interactive highlights |
| Vapi Mint | `#62f6b5` | `--color-vapi-mint` | Green action color for filled buttons, selected navigation states, and focused conversion moments |
| Code Blue | `#4dcafa` | `--color-code-blue` | Highlight elements in code examples, specific icon fills, decorative accents |
| Neon Pink | `#de94e2` | `--color-neon-pink` | Decorative graphical elements, code syntax highlighting, secondary accents |
| Vivid Yellow | `#ffdd03` | `--color-vivid-yellow` | Decorative graphical elements, code syntax highlighting, secondary accents |
| Electric Violet | `#9977ff` | `--color-electric-violet` | Decorative graphical elements, code syntax highlighting, secondary accents |

## Tokens — Typography

### seasonSans — Primary sans-serif font for all headings, body text, buttons, and navigation. Its condensed nature and range of weights provide a modern, technical feel. · `--font-seasonsans`
- **Substitute:** Inter
- **Weights:** 300, 400, 500, 510, 570, 650
- **Sizes:** 11px, 12px, 14px, 15px, 16px, 18px, 22px, 24px, 32px, 40px, 44px, 56px, 68px, 96px, 120px, 144px
- **Line height:** 1.00, 1.09, 1.10, 1.12, 1.14, 1.20, 1.25, 1.32, 1.33, 1.36, 1.43, 1.50, 1.56, 1.60, 1.71
- **Letter spacing:** -0.0250em at 144px, -0.0220em at 120px, -0.0200em at 96px, -0.0160em at 68px, 0.0030em at 16px
- **Role:** Primary sans-serif font for all headings, body text, buttons, and navigation. Its condensed nature and range of weights provide a modern, technical feel.

### Geist Mono — Monospaced font for code snippets, technical terms, and highly specific data display, lending a developer-centric aesthetic. · `--font-geist-mono`
- **Substitute:** Fira Code
- **Weights:** 400, 500
- **Sizes:** 12px, 14px, 16px, 20px
- **Line height:** 1.00, 1.30, 1.33, 1.43, 1.50, 1.57, 1.67
- **Letter spacing:** 0.0500em at 20px, 0.0560em at 16px, 0.0670em at 14px, 0.0690em at 12px
- **OpenType features:** `'ss01', 'tnum'`
- **Role:** Monospaced font for code snippets, technical terms, and highly specific data display, lending a developer-centric aesthetic.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 11px | 1.43 | 0.03px | `--text-caption` |
| body | 15px | 1.6 | 0.003px | `--text-body` |
| subheading | 22px | 1.25 | -0.016px | `--text-subheading` |
| heading-sm | 24px | 1.2 | -0.016px | `--text-heading-sm` |
| heading | 32px | 1.14 | -0.016px | `--text-heading` |
| heading-lg | 40px | 1.12 | -0.016px | `--text-heading-lg` |
| display | 56px | 1.09 | -0.02px | `--text-display` |

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
| 28 | 28px | `--spacing-28` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 56 | 56px | `--spacing-56` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 96 | 96px | `--spacing-96` |
| 100 | 100px | `--spacing-100` |
| 120 | 120px | `--spacing-120` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 5.6px |
| input | 12px |
| buttons | 9999px |
| general | 24px |

### Layout

- **Section gap:** 40px
- **Card padding:** 16px
- **Element gap:** 8px

## Components

### Header Action Button - Outline
**Role:** Secondary action button in the header.

Background transparent, text 'Silver Moonlight' #d8d7d4, 1.67772e+07px (full pill) border radius, 8px vertical, 20px horizontal padding.

### Ghost Text Button
**Role:** Tertiary action, often within component bodies or navigation.

Background transparent, text 'Whisper White' #fffaea, no border radius, 4px vertical, 0px horizontal padding, with an implied bottom border on hover or active state.

### Primary Call-to-Action Button
**Role:** Main call to action, typically a filled button.

Background 'Vapi Orange' #e96b34, text 'Deep Midnight' #09090b, 1.67772e+07px (full pill) border radius, 8px vertical, 20px horizontal padding.

### Secondary Call-to-Action Button
**Role:** Alternative call to action, typically a filled button.

Background 'Vapi Mint' #62f6b5, text 'Deep Midnight' #09090b, 1.67772e+07px (full pill) border radius, 8px vertical, 20px horizontal padding.

### Text Input / Search oval
**Role:** Interactive text input field in hero area.

Background 'Whisper White' #fffaea, text 'Deep Midnight' #09090b, border 'Charcoal Slate' #3f3f46, 1.67772e+07px (full pill) border radius, 8px vertical, 20px horizontal padding.

### Brand Logo Bar Item
**Role:** Displaying brand logos of partners or clients.

Logos rendered in 'Whisper White' #fffaea, presented on the 'Deep Midnight' #0e0e13 background.

## Do's and Don'ts

### Do
- Use 'Deep Midnight' #0e0e13 as the dominant background color for most sections to maintain the dark theme.
- Apply a full pill '9999px' border-radius to all primary and secondary action buttons.
- Reserve 'Vapi Orange' #e96b34 and 'Vapi Mint' #62f6b5 exclusively for primary and secondary call-to-action buttons respectively, and for key interactive highlights.
- Employ the 'seasonSans' font for all textual content, adjusting weight and size according to the `typeScale` to establish hierarchy.
- Utilize 'Whisper White' #fffaea for primary text on dark backgrounds and 'Deep Midnight' #09090b for text within light-colored components.
- Maintain a clear element gap of 8px (0.5rem) between related UI elements for consistent spacing.
- Ensure all interactive elements like buttons and links have a discernible hover state, often involving subtle color shifts or underlines.

### Don't
- Do not introduce new saturated primary colors; limit the accent palette strictly to the defined 'Code Blue', 'Neon Pink', 'Vivid Yellow', and 'Electric Violet' for decorative elements.
- Avoid using drop shadows for elevation; rely on border treatments, background color changes, and inner shadows to define surface hierarchy.
- Do not deviate from the defined border radii; maintain 9999px for buttons, 5.6px for cards, and 12px for inputs unless specifically defined otherwise.
- Do not use generic system fonts; always utilize 'seasonSans' and 'Geist Mono' to preserve brand identity.
- Avoid unnecessary text decoration unless it denotes a link or active state.
- Do not use highly saturated colors for large background areas; keep backgrounds dark and relatively achromatic.
- Do not over-space elements; adhere to the 'comfortable' density and defined `elementGap` to keep the interface concise.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Base Canvas | `#0e0e13` | Primary page background, deepest layer. |
| 2 | Sectional Panel | `#27272a` | Alternating background for content sections, footer background, subtle elevation from base. |
| 3 | Interactive Surface | `#09090b` | Background for specific interactive list items or internal UI components, slightly lighter than base canvas but darker than general panels. |
| 4 | Light Overlay | `#fffaea` | Background for highly interactive elements like specific buttons or emphasized input fields, creating high contrast against dark text. |

## Imagery

The site uses minimal imagery, primarily relying on abstract, colorful soundwave-like graphic elements as decorative atmosphere rather than content. Company logos are monochromatic (Whisper White) against the dark background. There's a clear absence of photography or complex illustrations, emphasizing a pure UI aesthetic. Iconography is light-stroked or filled, monochromatic with occasional subtle color accents, reflecting a developer tools sensibility.

## Layout

The page primarily uses a full-bleed dark background for the hero section with content centered. Subsequent sections alternate between the main 'Deep Midnight' background and slightly lighter 'Charcoal Slate' panels, creating a visual rhythm. Content is arranged in classic block layouts, often with centered stacks for headlines and CTAs, or implied two-column text-left/visual-right patterns. The overall density is comfortable, with generous vertical spacing between sections. Navigation is a sticky top bar with outlined and filled buttons on the right.

## Agent Prompt Guide

Quick Color Reference:
text: #fffaea
background: #0e0e13
border: #27272a
accent: #4dcafa
primary action: #e96b34 (filled action)

Example Component Prompts:
1. Create a Hero Block: Fill the screen with 'Deep Midnight' #0e0e13. Centered heading 'Voice AI agents for developers' in 'Whisper White' #fffaea, seasonSans weight 570, size 56px, letter-spacing -1.6px. Below it, two buttons: Primary 'Request a Demo' (background 'Vapi Orange' #e96b34, text 'Deep Midnight' #09090b, 9999px radius, 8px 20px padding) and Secondary 'Sign Up' (background 'Vapi Mint' #62f6b5, text 'Deep Midnight' #09090b, 9999px radius, 8px 20px padding). Place the two buttons with an element gap of 8px. Underneath, a large 'Talk to Vapi' oval input field (background 'Whisper White' #fffaea, border 'Charcoal Slate' #3f3f46, text 'Deep Midnight' #09090b, 9999px radius, 8px 20px padding).
2. Create a Navigation Bar: Set background to 'Deep Midnight' #0e0e13. On the left, 'Vapi' branding in 'Whisper White' #fffaea, seasonSans weight 570, size 24px. On the right, a 'Request a Demo' button (background transparent, text 'Silver Moonlight' #d8d7d4, 9999px radius, 8px 20px padding), followed by a 'Login' button (background 'Vapi Mint' #62f6b5, text 'Deep Midnight' #09090b, 9999px radius, 8px 20px padding).
3. Create a Feature Card: Background 'Deep Midnight' #0e0e13 with a 1px border 'Charcoal Slate' #27272a and 5.6px radius. Heading 'Feature Title' in 'Whisper White' #fffaea, seasonSans weight 510, size 24px. Body text 'Feature description goes here' in 'Silver Moonlight' #d8d7d4, seasonSans weight 400, size 15px, line height 1.6. Use a card padding of 16px.

## Similar Brands

- **OpenAI** — Dark-mode UI with a single vivid accent color for interactive elements and a focus on clean, legible typography.
- **Vercel** — High-contrast dark interface, developer-focused aesthetic, and precise use of typography with a strong emphasis on readability for code and technical content.
- **Supabase** — Dark, technical UI with a limited, functional color palette and a clear separation of content and UI elements using subtle surface shifts and borders, avoiding heavy shadows.
- **Tailwind CSS** — Emphasis on structured, functional design with a dark background, minimal decorative elements, and clear, purposeful use of grays and accent colors in a developer context.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-deep-midnight: #0e0e13;
  --color-charcoal-slate: #27272a;
  --color-silver-moonlight: #d8d7d4;
  --color-whisper-white: #fffaea;
  --color-faded-steel: #a1a1aa;
  --color-interface-gray: #d9e6ef;
  --color-soft-black: #09090b;
  --color-sunken-black: #18181b;
  --color-vapi-orange: #e96b34;
  --color-vapi-mint: #62f6b5;
  --color-code-blue: #4dcafa;
  --color-neon-pink: #de94e2;
  --color-vivid-yellow: #ffdd03;
  --color-electric-violet: #9977ff;

  /* Typography — Font Families */
  --font-seasonsans: 'seasonSans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geist-mono: 'Geist Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.43;
  --tracking-caption: 0.03px;
  --text-body: 15px;
  --leading-body: 1.6;
  --tracking-body: 0.003px;
  --text-subheading: 22px;
  --leading-subheading: 1.25;
  --tracking-subheading: -0.016px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: -0.016px;
  --text-heading: 32px;
  --leading-heading: 1.14;
  --tracking-heading: -0.016px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.12;
  --tracking-heading-lg: -0.016px;
  --text-display: 56px;
  --leading-display: 1.09;
  --tracking-display: -0.02px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-w510: 510;
  --font-weight-w570: 570;
  --font-weight-w650: 650;

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
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-100: 100px;
  --spacing-120: 120px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 16px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-md: 5.6px;
  --radius-xl: 12px;
  --radius-3xl: 24px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-cards: 5.6px;
  --radius-input: 12px;
  --radius-buttons: 9999px;
  --radius-general: 24px;

  /* Surfaces */
  --surface-base-canvas: #0e0e13;
  --surface-sectional-panel: #27272a;
  --surface-interactive-surface: #09090b;
  --surface-light-overlay: #fffaea;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-deep-midnight: #0e0e13;
  --color-charcoal-slate: #27272a;
  --color-silver-moonlight: #d8d7d4;
  --color-whisper-white: #fffaea;
  --color-faded-steel: #a1a1aa;
  --color-interface-gray: #d9e6ef;
  --color-soft-black: #09090b;
  --color-sunken-black: #18181b;
  --color-vapi-orange: #e96b34;
  --color-vapi-mint: #62f6b5;
  --color-code-blue: #4dcafa;
  --color-neon-pink: #de94e2;
  --color-vivid-yellow: #ffdd03;
  --color-electric-violet: #9977ff;

  /* Typography */
  --font-seasonsans: 'seasonSans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geist-mono: 'Geist Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.43;
  --tracking-caption: 0.03px;
  --text-body: 15px;
  --leading-body: 1.6;
  --tracking-body: 0.003px;
  --text-subheading: 22px;
  --leading-subheading: 1.25;
  --tracking-subheading: -0.016px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: -0.016px;
  --text-heading: 32px;
  --leading-heading: 1.14;
  --tracking-heading: -0.016px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.12;
  --tracking-heading-lg: -0.016px;
  --text-display: 56px;
  --leading-display: 1.09;
  --tracking-display: -0.02px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-100: 100px;
  --spacing-120: 120px;

  /* Border Radius */
  --radius-md: 5.6px;
  --radius-xl: 12px;
  --radius-3xl: 24px;
  --radius-full: 9999px;
}
```

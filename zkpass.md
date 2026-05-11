# zkPass — Style Reference
> Digital-noir command center

**Theme:** dark

zkPass uses a 'digital-noir command center' aesthetic, characterized by a predominantly dark background interrupted by a single, vibrant lime green that acts as a beacon for interaction and focus. Typography is a sharp, technical blend of a structured serif for headlines and monospaced fonts for UI details, lending a serious, almost academic tone. Borders are sharp and often serve as subtle dividers or highlights, creating clear divisions without heavy visual weight. The overall impression is one of precision, security, and advanced technology operating in a low-light, high-contrast environment.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#000000` | `--color-midnight-ink` | Primary background, core surface color, primary text for bright surfaces |
| Silver Whisper | `#ffffff` | `--color-silver-whisper` | Primary text on dark backgrounds, icon fills, subtle borders |
| Lime Interface | `linear-gradient(90deg, rgb(197, 255, 74) 0px, rgb(197, 255, 74) 6px, rgba(0, 0, 0, 0) 6px, rgba(0, 0, 0, 0) 12px)` | `--color-lime-interface` | Primary action background, active states, brand accent for highlights, iconography, and key data points. Creates high visibility on dark backgrounds; Shadow effect for the primary brand color, creating a subtle neon glow; Decorative background gradient used for subtle texture; Large, soft radial gradient for background atmospheric effects |
| Dark Grid | `#252525` | `--color-dark-grid` | Subtle surface accents, outlined button borders, navigation separators |
| Mid-Gray Border | `#7a7a7a` | `--color-mid-gray-border` | Muted text, secondary borders, visual separation elements |
| Faint Grid | `#3d3d3d` | `--color-faint-grid` | Lightest grey text, and very subtle border lines |
| Glow Green | `#597321` | `--color-glow-green` | Green outline accent for tags, dividers, and focused UI edges. Do not promote it to the primary CTA color |
| Soft Lime | `#314013` | `--color-soft-lime` | Deep background accents, decorative strokes when very subtle shading is needed |
| White Outlined Text | `#c5c5c5` | `--color-white-outlined-text` | Faint text on dark backgrounds, secondary data labels |

## Tokens — Typography

### PT Serif — Headings and prominent display text. The wide range of sizes and tight tracking at larger sizes give a confident, expansive feel. The serif communicates authority and an academic tone. · `--font-pt-serif`
- **Substitute:** Source Serif 4
- **Weights:** 300, 400
- **Sizes:** 14px, 16px, 20px, 22px, 24px, 26px, 32px, 40px, 49px, 56px, 60px, 72px, 75px, 78px, 86px, 89px, 130px
- **Line height:** 0.88, 0.90, 0.94, 0.95, 0.98, 1.00, 1.02, 1.04, 1.05, 1.06, 1.10, 1.15, 1.18, 1.20, 1.30, 1.55
- **Letter spacing:** -0.035em at 130px, -0.03em at 89px, -0.025em at 78px, -0.022em at 75px, -0.02em at 72px, -0.015em at 60px, -0.012em at 56px, -0.01em at 49px
- **Role:** Headings and prominent display text. The wide range of sizes and tight tracking at larger sizes give a confident, expansive feel. The serif communicates authority and an academic tone.

### Inter Tight — Body text, navigation, and general UI elements. The tight tracking and strong weights ensure clarity even at small sizes, maintaining a compact yet readable information density. · `--font-inter-tight`
- **Substitute:** Inter
- **Weights:** 400, 500, 600
- **Sizes:** 9px, 10px, 11px, 12px, 13px, 14px, 16px, 20px, 28px
- **Line height:** 1.08, 1.20, 1.30, 1.50, 1.55, 1.60, 1.70, 1.75, 1.90
- **Letter spacing:** 0.005em at 28px, 0.01em at 20px, 0.02em at 16px, 0.03em at 14px, 0.04em at 13px, 0.08em at 12px, 0.11em at 11px, 0.12em at 10px, 0.16em at 9px
- **Role:** Body text, navigation, and general UI elements. The tight tracking and strong weights ensure clarity even at small sizes, maintaining a compact yet readable information density.

### ui-monospace — Small functional text, legal disclaimers, minor footnotes. The monospace style conveys stability and precision for utility text. · `--font-ui-monospace`
- **Substitute:** SF Mono
- **Weights:** 400
- **Sizes:** 9px, 11px, 12px
- **Line height:** 1.20, 1.55
- **Letter spacing:** 0.04em at 12px, 0.22em at 9px
- **Role:** Small functional text, legal disclaimers, minor footnotes. The monospace style conveys stability and precision for utility text.

### JetBrains Mono — Code snippets, technical labels, and any text requiring a strong monospace presence. Used to convey technical accuracy and a developer-focused feel. · `--font-jetbrains-mono`
- **Substitute:** Fira Code
- **Weights:** 400, 500, 600
- **Sizes:** 10px, 11px, 13px
- **Line height:** 0.92, 1.20, 1.55
- **Letter spacing:** 0.01em at 13px, 0.06em at 11px, 0.18em at 10px
- **Role:** Code snippets, technical labels, and any text requiring a strong monospace presence. Used to convey technical accuracy and a developer-focused feel.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body | 14px | 1.55 | 0.03px | `--text-body` |
| subheading | 20px | 1.2 | 0.01px | `--text-subheading` |
| heading | 49px | 1.05 | -0.01px | `--text-heading` |
| heading-lg | 72px | 1 | -0.02px | `--text-heading-lg` |
| display | 130px | 0.88 | -0.035px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 6 | 6px | `--spacing-6` |
| 7 | 7px | `--spacing-7` |
| 8 | 8px | `--spacing-8` |
| 10 | 10px | `--spacing-10` |
| 12 | 12px | `--spacing-12` |
| 14 | 14px | `--spacing-14` |
| 16 | 16px | `--spacing-16` |
| 18 | 18px | `--spacing-18` |
| 20 | 20px | `--spacing-20` |
| 22 | 22px | `--spacing-22` |
| 24 | 24px | `--spacing-24` |
| 28 | 28px | `--spacing-28` |
| 30 | 30px | `--spacing-30` |
| 32 | 32px | `--spacing-32` |
| 44 | 44px | `--spacing-44` |

### Border Radius

| Element | Value |
|---------|-------|
| none | 0px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| sm | `rgba(197, 255, 74, 0.45) 0px 0px 8px 0px` | `--shadow-sm` |

### Layout

- **Section gap:** 28px
- **Card padding:** 22px
- **Element gap:** 10px

## Components

### Underlined Navigation Button
**Role:** Header navigation links and secondary actions where emphasis is achieved through a bottom border rather than a solid background.

Background: transparent, Text: #ffffff, Underline: 8px solid #ffffff, Padding: 0px bottom with 0px horizontal, Text weight: 400.

### Faint Border Button
**Role:** Subtle calls to action or secondary interactive elements within sections, providing a ghost-like presence.

Background: #000000, Text: #ffffff, Border: 1.5px solid rgba(61, 61, 61, 0.6), Padding: 0px top/bottom, 18px horizontal. No border radius.

### Primary Action Button - Lime
**Role:** Hero call to action, main navigation launch button. High contrast and immediate visibility.

Background: #c5ff4a, Text: #000000, Border: 1.5px solid #c5ff4a, Padding: 14px vertical, 20px horizontal. No border radius.

### Text Link Button
**Role:** Inline textual links or buttons that blend into the surrounding content, often using arrow icons for interaction cues.

Background: #000000, Text: #ffffff, Border: 1.5px solid #ffffff, Padding: 0px. No border radius.

### Section Divider
**Role:** Visually separates content blocks, often appearing as a thin horizontal line.

Height: 1px, Background: #252525.

## Do's and Don'ts

### Do
- Always use a #000000 background for large sections to maintain the dark theme unless a specific, subtle background is otherwise designated.
- Highlight interactive elements and calls to action with `Lime Interface` (#c5ff4a) to ensure high visibility and direct user attention.
- Employ `PT Serif` for all headings and `Inter Tight` for body and UI elements to maintain the serious yet compact typographic style.
- Utilize 0px border-radius for all components to ensure a sharp, technical aesthetic throughout the interface.
- Separate content visually with thin `Dark Grid` (#252525) borders or by alternating surface colors rather than heavy boxes or pronounced shadows.
- Apply negative letter-spacing for large PT Serif headlines (-0.01em to -0.035em) and positive letter-spacing for small Inter Tight elements (0.01em to 0.16em) to control visual density.
- Use a subtle `Lime Pulse Shadow` for interactive brand elements to give them an ethereal glow without heavy elevation.

### Don't
- Avoid rounded corners on any UI element; the brand aesthetic is defined by sharp edges and precise geometry.
- Do not introduce additional chromatic colors beyond `Lime Interface` (#c5ff4a) unless for semantic status indicators like error/success, using the defined `Glow Green` or `Soft Lime` accents sparingly.
- Refrain from using heavy drop shadows for elevation; prefer thin borders or the subtle `Lime Pulse Shadow` for emphasis.
- Do not use generic system fonts for body or headings; always map to the specified `PT Serif`, `Inter Tight`, `ui-monospace`, or `JetBrains Mono`.
- Avoid large areas of white background unless specifically defined as an alternative content surface; the primary theme is dark mode.
- Do not use thick borders or excessive padding for interactive elements; maintain a lightweight and efficient feel.
- Do not introduce arbitrary vertical spacing; adhere to the `comfortable` density and specific `elementGap`, `cardPadding`, and `sectionGap` values.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Deep Space | `#000000` | Primary page background, foundational surface. |
| 1 | Subtle Panel | `#060606` | Slightly elevated panels or background sections, almost indistinguishable from the base. |
| 2 | Dark Card | `#1f1f1f` | Card backgrounds, slightly more prominent than general backgrounds. |
| 3 | Interactive Border | `#252525` | Borders for interactive elements, distinct containers, and form fields. |
| 4 | Elevated Accent | `#313131` | More pronounced borders and minor elevated elements. |

## Imagery

This site features a blend of abstract, digital-art hands made of binary code for atmospheric effect, mixed with precise product screenshots of code and UI. Photography is absent. Illustrations are stylized, flat, and often monochromatic with a single color accent, conveying a high-tech, data-centric narrative. Icons are minimal, either outlined or filled, with a very fine stroke weight or solid fill. Imagery serves primarily to set a futuristic, secure atmosphere and to explain technical concepts or showcase product interfaces, rather than decorative purposes. The visual density is moderate, with imagery often contained within specific sections and balanced by significant textual information.

## Layout

The page primarily uses a full-bleed, dark background with content sections stretching fluidly or contained within a implied central column. The hero element is full-bleed, featuring large centered text over abstract digital imagery. Subsequent sections often alternate between large, impactful headlines (sometimes with a lime accent) and multi-column layouts, particularly a distinctive text-heavy section with parallel descriptions. Vertical rhythm is established by consistent spacing between sections, sometimes with subtle graphical vertical dividers. Navigation is a minimalist top bar, with prominent 'Launch' button in lime. Card grids are used for features, showcasing clear hierarchy within a dark interface.

## Agent Prompt Guide

### Quick Color Reference
- text: #ffffff
- background: #000000
- border: #252525
- accent: #c5ff4a
- primary action: #c5ff4a (filled action)

### 3-5 Example Component Prompts
1. Create a Primary Action Button: #c5ff4a background, #000000 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Design a feature card: `Dark Card` background (#1f1f1f), with a 1.5px solid `Dark Grid` (#252525) border. Title is `PT Serif` 26px, weight 400, color `Silver Whisper`, letter-spacing -0.02em. Body text is `Inter Tight` 14px, weight 400, color `Mid-Gray Border` (#7a7a7a). Use 22px padding all around.
4. Develop a legal disclaimer text block: Background `Midnight Ink`, text `ui-monospace` 9px, weight 400, color `Faint Grid` (#3d3d3d), letter-spacing 0.22em. Use 10px element gap for paragraphs.

## Similar Brands

- **Solana** — Shares a very dark aesthetic with one dominant, vibrant accent color for interaction and brand identity.
- **StarkWare** — Utilizes a highly technical, code-oriented visual language with sharp typography, monospace fonts, and a preference for dark modes.
- **Parity Technologies** — Similar in its use of bold, structured typography on dark backgrounds to convey a sense of gravitas and technological authority.
- **Zcash** — Employs a stark, high-contrast dark theme with a focus on trust and privacy, often with minimal color accents.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-silver-whisper: #ffffff;
  --color-lime-interface: #c5ff4a;
  --gradient-lime-interface: linear-gradient(90deg, rgb(197, 255, 74) 0px, rgb(197, 255, 74) 6px, rgba(0, 0, 0, 0) 6px, rgba(0, 0, 0, 0) 12px);
  --color-dark-grid: #252525;
  --color-mid-gray-border: #7a7a7a;
  --color-faint-grid: #3d3d3d;
  --color-glow-green: #597321;
  --color-soft-lime: #314013;
  --color-white-outlined-text: #c5c5c5;

  /* Typography — Font Families */
  --font-pt-serif: 'PT Serif', ui-serif, Georgia, Cambria, "Times New Roman", Times, serif;
  --font-inter-tight: 'Inter Tight', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ui-monospace: 'ui-monospace', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-jetbrains-mono: 'JetBrains Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-body: 14px;
  --leading-body: 1.55;
  --tracking-body: 0.03px;
  --text-subheading: 20px;
  --leading-subheading: 1.2;
  --tracking-subheading: 0.01px;
  --text-heading: 49px;
  --leading-heading: 1.05;
  --tracking-heading: -0.01px;
  --text-heading-lg: 72px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -0.02px;
  --text-display: 130px;
  --leading-display: 0.88;
  --tracking-display: -0.035px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-6: 6px;
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-14: 14px;
  --spacing-16: 16px;
  --spacing-18: 18px;
  --spacing-20: 20px;
  --spacing-22: 22px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-30: 30px;
  --spacing-32: 32px;
  --spacing-44: 44px;

  /* Layout */
  --section-gap: 28px;
  --card-padding: 22px;
  --element-gap: 10px;

  /* Named Radii */
  --radius-none: 0px;

  /* Shadows */
  --shadow-sm: rgba(197, 255, 74, 0.45) 0px 0px 8px 0px;

  /* Surfaces */
  --surface-deep-space: #000000;
  --surface-subtle-panel: #060606;
  --surface-dark-card: #1f1f1f;
  --surface-interactive-border: #252525;
  --surface-elevated-accent: #313131;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-silver-whisper: #ffffff;
  --color-lime-interface: #c5ff4a;
  --color-dark-grid: #252525;
  --color-mid-gray-border: #7a7a7a;
  --color-faint-grid: #3d3d3d;
  --color-glow-green: #597321;
  --color-soft-lime: #314013;
  --color-white-outlined-text: #c5c5c5;

  /* Typography */
  --font-pt-serif: 'PT Serif', ui-serif, Georgia, Cambria, "Times New Roman", Times, serif;
  --font-inter-tight: 'Inter Tight', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ui-monospace: 'ui-monospace', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-jetbrains-mono: 'JetBrains Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-body: 14px;
  --leading-body: 1.55;
  --tracking-body: 0.03px;
  --text-subheading: 20px;
  --leading-subheading: 1.2;
  --tracking-subheading: 0.01px;
  --text-heading: 49px;
  --leading-heading: 1.05;
  --tracking-heading: -0.01px;
  --text-heading-lg: 72px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -0.02px;
  --text-display: 130px;
  --leading-display: 0.88;
  --tracking-display: -0.035px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-6: 6px;
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-14: 14px;
  --spacing-16: 16px;
  --spacing-18: 18px;
  --spacing-20: 20px;
  --spacing-22: 22px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-30: 30px;
  --spacing-32: 32px;
  --spacing-44: 44px;

  /* Shadows */
  --shadow-sm: rgba(197, 255, 74, 0.45) 0px 0px 8px 0px;
}
```

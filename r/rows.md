# Rows — Style Reference
> Minimalist worksheet with warm accents

**Theme:** light

This system feels like a precise, functional workspace, prioritizing clarity and direct interaction. Nearly achromatic surfaces and text form a stark foundation, minimizing distraction and allowing content to take center stage. The single prominent use of a warm gradient accent, along with subtler pastel button backgrounds, injects a controlled energy, hinting at progress and reward against the otherwise restrained UI. Compact spacing, subtle rounded edges, and sharp typography contribute to an efficient and focused user experience.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Carbon Black | `#1a1a1a` | `--color-carbon-black` | Primary text, headings, icons, borders, active element state outlines — provides strong contrast against white and light gray backgrounds, anchoring the visual hierarchy. |
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, elevated surfaces — serves as the primary backdrop for all content. |
| Whisper Gray | `#f7f7f7` | `--color-whisper-gray` | Subtle background for interactive elements and hover states — provides slight visual differentiation without introducing strong color. |
| Parchment Tan | `#eaeaea` | `--color-parchment-tan` | Background for inactive or secondary buttons, subtle borders — offers a soft, muted alternative to pure white. |
| Stone Gray | `#e1e1e1` | `--color-stone-gray` | Default borders, dividers, subtle iconography — defines boundaries with a light, unintrusive touch. |
| Ash Gray | `#989898` | `--color-ash-gray` | Placeholder text, secondary labels, inactive states — provides legibility without demanding attention. |
| Charcoal Gray | `#6f6f6f` | `--color-charcoal-gray` | Secondary text, disabled states, supporting body copy — offers a softer text color for less prominent information. |
| Zinc Gray | `#c2c2c2` | `--color-zinc-gray` | Tertiary text, subtle hints — recedes into the background. |
| Muted Gold | `#fff6d4` | `--color-muted-gold` | Background for suggestion tags/buttons — provides a very subtle, warm hint of interaction. |
| Sunset Gradient | `linear-gradient(rgb(255, 84, 56) 0%, rgb(255, 199, 0) 100%)` | `--color-sunset-gradient` | Accented suggestion borders, visual indicator in an input field — draws attention with vivid warmth, signaling activity or key information. |

## Tokens — Typography

### Output Sans — The primary typeface for all text content, from captions to headings. Its clean, sans-serif lines at various weights ensure both readability and a modern, technical feel. A range of specified letter-spacing values fine-tunes visual density across different sizes. · `--font-output-sans`
- **Substitute:** Inter
- **Weights:** 400, 700
- **Sizes:** 10px, 14px, 18px, 24px
- **Line height:** 1.00, 1.33, 1.43, 1.45
- **Letter spacing:** 0.008, 0.011, 0.014, 0.02, 0.021
- **Role:** The primary typeface for all text content, from captions to headings. Its clean, sans-serif lines at various weights ensure both readability and a modern, technical feel. A range of specified letter-spacing values fine-tunes visual density across different sizes.

### Output Sans — Used for prominent headings, such as 'Hi, what do you want to build?', this weight commands attention with its negative letter-spacing, giving it a tighter, more deliberate appearance, contrasting with the lighter text roles. · `--font-output-sans`
- **Substitute:** Inter
- **Weights:** 400, 700
- **Sizes:** 10px, 14px, 18px, 24px
- **Line height:** 1.00, 1.33, 1.43, 1.45
- **Letter spacing:** -0.043
- **Role:** Used for prominent headings, such as 'Hi, what do you want to build?', this weight commands attention with its negative letter-spacing, giving it a tighter, more deliberate appearance, contrasting with the lighter text roles.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.43 | 0.021px | `--text-caption` |
| body | 14px | 1.43 | 0.011px | `--text-body` |
| subheading | 18px | 1.45 | 0.014px | `--text-subheading` |
| display | 24px | 1 | -0.043px | `--text-display` |

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
| 32 | 32px | `--spacing-32` |
| 44 | 44px | `--spacing-44` |
| 52 | 52px | `--spacing-52` |

### Border Radius

| Element | Value |
|---------|-------|
| buttons | 8px |
| default | 4px |

### Layout

- **Section gap:** 24px
- **Element gap:** 4px

## Components

### Primary Navigation Link
**Role:** Top right navigation items like 'Log in' and 'Free sign up'.

Text in Carbon Black (#1a1a1a), no background or border, `Output Sans` weight 400, size 14px, lineHeight 1.43, letterSpacing 0.011em.

### Primary Page Title
**Role:** Main heading that frames the interaction, e.g., 'Hi, what do you want to build?'.

Text in Carbon Black (#1a1a1a), `Output Sans` weight 700, size 24px, lineHeight 1.00, letterSpacing -0.043em.

### Search Input Field
**Role:** The primary interactive input area for user queries or commands.

Background is Canvas White (#ffffff), text is Carbon Black (#1a1a1a). Border is 1px solid Sunset Gradient on hover/focus. Placeholder text is Ash Gray (#989898). Padding is inferred 6px vertical and 8px horizontal, with a 4px radius.

### Default Action Button
**Role:** General interactive buttons for common actions.

Transparent background, Carbon Black (#1a1a1a) text, `Output Sans` weight 400, size 14px, lineHeight 1.43, letterSpacing 0.011em. No border and 0px padding is observed for these general context buttons.

### Category Button (Subtle)
**Role:** Buttons for filtering or categorizing content, often grouped.

Text is Carbon Black (#1a1a1a), transparent background. Border is 1px solid Parchment Tan (#eaeaea), radius 8px, padding 6px vertical, 8px horizontal. `Output Sans` weight 400, size 14px, lineHeight 1.43, letterSpacing 0.011em.

### Category Button (Filled)
**Role:** Highly prominent category or suggestion buttons.

Background is Whisper Gray (#f7f7f7), text is Carbon Black (#1a1a1a). Border is 1px solid Stone Gray (#e1e1e1), radius 0px, no padding. `Output Sans` weight 400, likely size 14px.

### Suggestion Tag
**Role:** Small, interactive tags suggesting popular or common items.

Background is Muted Gold (#fff6d4), text is Carbon Black (#1a1a1a) at 54% opacity. Radius 4px, no padding. `Output Sans` weight 400, size 14px, lineHeight 1.43, letterSpacing 0.011em. Border is a 1px solid Sunset Gradient.

### Footer Link
**Role:** Navigation links found in the footer, less prominent than primary navigation.

Text is Charcoal Gray (#6f6f6f), `Output Sans` weight 400, size 14px, lineHeight 1.43. No unique styling beyond color, suggesting a functional role.

## Do's and Don'ts

### Do
- Prioritize Canvas White (#ffffff) as the dominant background color for main content areas.
- Use Carbon Black (#1a1a1a) for all primary text, headings, and critical UI elements to ensure high contrast and readability.
- Apply `Output Sans` at weight 700 with letter-spacing -0.043em for all main headings (24px) to create a distinct, tight visual expression.
- Utilize a 8px border-radius for interactive buttons and key UI containers, and 4px for smaller interactive elements like tags.
- Employ the Sunset Gradient (linear-gradient(rgb(255, 84, 56) 0%, rgb(255, 199, 0) 100%)) sparingly for highlight borders on interactive elements, like the search input or suggestion tags.
- Maintain compact spacing, typically 4px for element gaps and 24px for section gaps, to foster an information-dense yet organized layout.
- Use Muted Gold (#fff6d4) for background fills of suggestions or tags to softly indicate potential actions without being overly assertive.

### Don't
- Avoid using highly saturated, non-semantic colors for anything other than specific accent highlights like the Sunset Gradient.
- Do not deviate from the `Output Sans` typeface for any UI text, as its consistent application defines the system's typographic identity.
- Refrain from using strong shadows or complex elevation; UI depth is primarily achieved through subtle background color changes (e.g., Whisper Gray #f7f7f7) and borders (e.g., Stone Gray #e1e1e1).
- Do not use dark backgrounds for main content areas; the system is built on a light theme with high contrast text.
- Avoid excessive line-heights or loose letter-spacing, particularly for headlines, to preserve the system's crisp and condensed feel.
- Do not use generic, unbranded icon sets; rely on the existing simple, mono-color icon style for consistency.

## Imagery

The visual language for imagery is primarily functional and iconography-based. Small, simple, mono-color icons, often in Carbon Black (#1a1a1a) or Ash Gray (#989898), are used to denote functionality (e.g., 'PDF & Image', 'CSV/XLSX') rather than decorative purposes. There's an absence of large-scale photography or complex illustrations, reinforcing the UI-dominant, tool-like nature of the design. The visual information is conveyed through direct UI elements rather than abstract or lifestyle visuals. Icons are outlined, conveying clarity without heavy fills.

## Layout

The page adheres to a centered, constrained layout with a suggested max-width hinted by element clusters around 320px, although the overall canvas is full-bleed. The hero section presents a centered headline over a white background, immediately drawing focus. Content is arranged in stacked blocks, with functional categories (Import, Marketing Dashboard) presented in a grid-like fashion with compact, aligned buttons. Section rhythm is consistent, separated by vertical spacing, not visual dividers. There are no alternating light/dark bands or complex content arrangements. Navigation is a simple top-right bar with minimal links. The layout emphasizes density and direct interaction, making content easily scannable and functional choices readily available.

## Agent Prompt Guide

### Quick Color Reference
- Text: #1a1a1a (Carbon Black)
- Background: #ffffff (Canvas White)
- CTA/Accent Border: linear-gradient(rgb(255, 84, 56) 0%, rgb(255, 199, 0) 100%) (Sunset Gradient)
- Inactive Border: #e1e1e1 (Stone Gray)
- Placeholder Text: #989898 (Ash Gray)

### 3-5 Example Component Prompts
1. Create a `Primary Page Title`: Centered `Output Sans` text, weight 700, size 24px, lineHeight 1.00, letterSpacing -0.043em, with color Carbon Black (#1a1a1a). Content: 'Hi, what do you want to build?'.
2. Generate a `Category Button (Subtle)`: Background transparent, text Carbon Black (#1a1a1a), `Output Sans` weight 400, size 14px, lineHeight 1.43, letterSpacing 0.011em. Border 1px solid Parchment Tan (#eaeaea), radius 8px, padding 6px 8px. Content: 'PDF & Image'.
3. Design a `Suggestion Tag`: Background Muted Gold (#fff6d4), text Carbon Black (#1a1a1a) at 54% opacity, radius 4px. Border 1px solid Sunset Gradient. `Output Sans` weight 400, size 14px, lineHeight 1.43, letterSpacing 0.011em. Content: 'Website Traffic'.
4. Create a `Search Input Field`: Transparent background, Carbon Black (#1a1a1a) text, placeholder Ash Gray (#989898). Radius 4px. Border 1px solid Stone Gray (#e1e1e1), changing to 1px solid Sunset Gradient on hover/focus. Include an icon (e.g. settings) and a small button (e.g. orange). Placeholder text: 'Create a website traffic dashboard from Google An'.
5. Implement a `Default Action Button`: Transparent background, text Charcoal Gray (#6f6f6f), `Output Sans` weight 400, size 14px, lineHeight 1.43. No border or padding. Content: 'Start from blank ->'.

## Similar Brands

- **Airtable** — Shares a clean, grid-based, functional UI with a focus on data and input rather than elaborate visuals. Strong typography and clear interactive elements.
- **Notion** — Employs a white canvas, high-contrast text, and a strong reliance on a single sans-serif typeface to create a productive, minimalist workspace. Subtle interactive element styling.
- **Linear** — Features a direct, unadorned UI with a largely achromatic palette, emphasizing content and speed. Interactive elements are clearly defined with subtle borders and fills.
- **Google Workspace (Docs/Sheets)** — Exhibits a similar 'worksheet' aesthetic with a dominant white background, clear typography, and minimalist UI components, prioritizing content creation and interaction.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-carbon-black: #1a1a1a;
  --color-canvas-white: #ffffff;
  --color-whisper-gray: #f7f7f7;
  --color-parchment-tan: #eaeaea;
  --color-stone-gray: #e1e1e1;
  --color-ash-gray: #989898;
  --color-charcoal-gray: #6f6f6f;
  --color-zinc-gray: #c2c2c2;
  --color-muted-gold: #fff6d4;
  --color-sunset-gradient: #ffb84d;
  --gradient-sunset-gradient: linear-gradient(rgb(255, 84, 56) 0%, rgb(255, 199, 0) 100%);

  /* Typography — Font Families */
  --font-output-sans: 'Output Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.43;
  --tracking-caption: 0.021px;
  --text-body: 14px;
  --leading-body: 1.43;
  --tracking-body: 0.011px;
  --text-subheading: 18px;
  --leading-subheading: 1.45;
  --tracking-subheading: 0.014px;
  --text-display: 24px;
  --leading-display: 1;
  --tracking-display: -0.043px;

  /* Typography — Weights */
  --font-weight-regular: 400;
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
  --spacing-44: 44px;
  --spacing-52: 52px;

  /* Layout */
  --section-gap: 24px;
  --element-gap: 4px;

  /* Border Radius */
  --radius-sm: 1px;
  --radius-md: 4px;
  --radius-lg: 8px;

  /* Named Radii */
  --radius-buttons: 8px;
  --radius-default: 4px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-carbon-black: #1a1a1a;
  --color-canvas-white: #ffffff;
  --color-whisper-gray: #f7f7f7;
  --color-parchment-tan: #eaeaea;
  --color-stone-gray: #e1e1e1;
  --color-ash-gray: #989898;
  --color-charcoal-gray: #6f6f6f;
  --color-zinc-gray: #c2c2c2;
  --color-muted-gold: #fff6d4;
  --color-sunset-gradient: #ffb84d;

  /* Typography */
  --font-output-sans: 'Output Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.43;
  --tracking-caption: 0.021px;
  --text-body: 14px;
  --leading-body: 1.43;
  --tracking-body: 0.011px;
  --text-subheading: 18px;
  --leading-subheading: 1.45;
  --tracking-subheading: 0.014px;
  --text-display: 24px;
  --leading-display: 1;
  --tracking-display: -0.043px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-44: 44px;
  --spacing-52: 52px;

  /* Border Radius */
  --radius-sm: 1px;
  --radius-md: 4px;
  --radius-lg: 8px;
}
```

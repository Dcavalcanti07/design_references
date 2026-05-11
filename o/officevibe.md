# Officevibe — Style Reference
> Electric Data Flow; a structured, approachable canvas where sharp insights meet soft edges.

**Theme:** light

This design system feels like a modern corporate solution, balancing trust with approachability. A deep, almost inky violet (`Boardroom Navy`) provides a stable foundation, contrasted by a vibrant, electric blue (`Brand Electric`) that visually energizes interactive elements. The interplay between the sans-serif clarity of Inter and the distinctive, slightly calligraphic AbcFavoritvariable for headings, alongside the unexpected Martinaplantijn script for accent headlines, creates a sophisticated yet human touch. The prevalent use of generous rounded corners (100px for buttons) against sharp content blocks softens the enterprise feel, making complex data feel more accessible.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Boardroom Navy | `#0c1754` | `--color-boardroom-navy` | Primary text, prominent headings, badge text, footer background — establishes a serious, trustworthy brand presence. |
| Brand Electric | `#2545ff` | `--color-brand-electric` | Primary call-to-action buttons, active navigation indicators, key interactive links — provides a vibrant, unmistakable focus for user interaction. |
| Lilac Accent | `#d9d4ff` | `--color-lilac-accent` | Subtle background accents, decorative elements — a muted counterpoint to Brand Electric, adding depth without visual noise. |
| Feedback Yellow | `#ffc13a` | `--color-feedback-yellow` | Accents, potentially informational highlights or status indicators — a warm, vivid pop of color. |
| Soft Off-White | `#f9f8f6` | `--color-soft-off-white` | Page backgrounds, card surfaces, form inputs — the dominant background neutral, providing a soft, canvas-like base. |
| Pure White | `#ffffff` | `--color-pure-white` | Focal backgrounds, cards, button text on Brand Electric — used for highlighted foreground elements. |
| Pitch Black | `#171417` | `--color-pitch-black` | Dominant text color for body, links, some headings — provides high contrast against light backgrounds. |
| Medium Gray | `#222222` | `--color-medium-gray` | Secondary text, navigation items, ghost button text — a softer dark alternative for less prominent text. |
| Light Cool Gray | `#eaebf8` | `--color-light-cool-gray` | Badge backgrounds, subtle borders — a very light, desaturated violet-gray for secondary background elements. |
| Input Border Gray | `#cccccc` | `--color-input-border-gray` | Input field borders — a mid-tone gray for subtle visual separation of form elements. |
| Accent Orange | `#ff5b22` | `--color-accent-orange` | Used as a stroke in illustrations, possibly for emphasis or minor error states — provides a sharp, energetic contrast. |

## Tokens — Typography

### Inter — Body text, navigation, buttons, lists, captions — the primary functional typeface, providing straightforward readability. · `--font-inter`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400, 500, 700
- **Sizes:** 12px, 14px, 16px, 20px
- **Line height:** 1.10, 1.20, 1.40, 1.43, 1.60
- **Letter spacing:** normal
- **OpenType features:** `"ss01" on, "ss04"`
- **Role:** Body text, navigation, buttons, lists, captions — the primary functional typeface, providing straightforward readability.

### Abcfavoritvariable — Main headings, subheadings, badge text — imparts a distinctive, slightly geometric character to titles, differentiating them from pure system fonts. · `--font-abcfavoritvariable`
- **Substitute:** Arial, sans-serif
- **Weights:** 400, 500
- **Sizes:** 12px, 14px, 16px, 20px, 24px, 32px, 40px, 48px, 64px
- **Line height:** 1.00, 1.10, 1.40, 1.50
- **Letter spacing:** -0.0500em at 40-64px, -0.0200em at 24-32px
- **OpenType features:** `"ss01" on, "ss04"`
- **Role:** Main headings, subheadings, badge text — imparts a distinctive, slightly geometric character to titles, differentiating them from pure system fonts.

### Martinaplantijn — Emphatic headline accents — used sparingly to highlight key phrases within larger headings, adding a unique, almost handwritten elegance. · `--font-martinaplantijn`
- **Substitute:** cursive
- **Weights:** 400
- **Sizes:** 40px, 64px
- **Line height:** 1.00, 1.10
- **Letter spacing:** normal
- **OpenType features:** `"ss01" on, "ss04"`
- **Role:** Emphatic headline accents — used sparingly to highlight key phrases within larger headings, adding a unique, almost handwritten elegance.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.4 | — | `--text-caption` |
| body-sm | 14px | 1.43 | — | `--text-body-sm` |
| body | 16px | 1.6 | — | `--text-body` |
| subheading | 20px | 1.4 | — | `--text-subheading` |
| heading-sm | 24px | 1.1 | -0.48px | `--text-heading-sm` |
| heading | 32px | 1.1 | -0.64px | `--text-heading` |
| heading-lg | 40px | 1.1 | -2px | `--text-heading-lg` |
| display | 48px | 1.1 | -2.4px | `--text-display` |
| display-lg | 64px | 1 | -3.2px | `--text-display-lg` |

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
| 56 | 56px | `--spacing-56` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 128 | 128px | `--spacing-128` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 16px |
| badges | 16px |
| inputs | 0px |
| buttons | 100px |

### Layout

- **Section gap:** 64px
- **Element gap:** 8px

## Components

### Primary CTA Button
**Role:** Main interactive button

Solid Brand Electric (#2545ff) background with Pure White (#ffffff) text. Features a generous 100px border-radius, 11.2px vertical and 32px horizontal padding. Font: Inter, 500 weight.

### Ghost Button (Primary Brand)
**Role:** Secondary call-to-action

Transparent background with Brand Electric (#2545ff) text and 1px border. 100px border-radius, 11.2px vertical and 32px horizontal padding. Font: Inter, 500 weight.

### Ghost Button (Dark Neutral)
**Role:** Navigation or less prominent actions

Transparent background with Medium Gray (#222222) text and 1px border. 0px border-radius, 18px vertical and 16px horizontal padding. Font: Inter, 500 weight.

### Ghost Button (Light Neutral)
**Role:** Navigation or less prominent actions on dark backgrounds

Transparent background with Pure White (#ffffff) text and 1px border. 100px border-radius, 11.2px vertical and 32px horizontal padding. Font: Inter, 500 weight.

### Feature Card
**Role:** Content display block

backgroundColor=rgba(0, 0, 0, 0) with no box-shadow, 16px border-radius. Padding: 40px vertical, 80px horizontal. Typically uses the Soft Off-White (#f9f8f6) background if not implicitly transparent relative to the page.

### Informative Badge
**Role:** Categorization or status indicator

Light Cool Gray (#eaebf8) background with Boardroom Navy (#0c1754) text. 16px border-radius, 4px top/bottom, 12px left/right padding. Font: Inter, 400 weight, 14px.

### Input Field (Footer)
**Role:** Footer email subscription input

Transparent background, Pure White (#ffffff) text. Bottom border is Input Border Gray (#cccccc), 1px solid. 0px border-radius, 12px vertical and 0px left padding. Placeholder text is lighter gray.

## Do's and Don'ts

### Do
- Do use Brand Electric (#2545ff) exclusively for primary interactive elements like main CTA buttons and active navigation states.
- Do ensure all buttons employ a 100px border-radius for their signature pill shape, unless specifically a ghost button variant.
- Do use Abcfavoritvariable for prominent headings, applying negative letter-spacing for larger sizes (-0.05em at 40px and above).
- Do employ Soft Off-White (#f9f8f6) as the primary page background color to establish a soft, approachable base.
- Do ensure body text uses Inter 400 at 16px, in Pitch Black (#171417) for maximal readability against light backgrounds.
- Do use Martinaplantijn 400 for accentuating specific words or phrases within larger headings, providing a unique calligraphic touch.
- Do maintain a consistent vertical spacing of 64px between major sections on the page.

### Don't
- Don't use Brand Electric (#2545ff) for static text or non-interactive decorative elements.
- Don't introduce additional curved shapes; large 100px radii for buttons and 16px for cards are the system's defined roundedness.
- Don't use bold weights for Inter in headlines; only Abcfavoritvariable or Martinaplantijn should carry headline prominence.
- Don't embed images with strong, distracting background colors; favor clean product shots or highly stylized UI illustrations.
- Don't use hard shadows for elevation; rely on background color changes or subtle outlines for depth.
- Don't clutter layouts; prioritize generous white space with a base element gap of 8px and larger gaps for content sections.
- Don't use any other blues for brand elements other than Boardroom Navy (#0c1754) and Brand Electric (#2545ff).

## Imagery

Imagery primarily consists of highly stylized, almost abstract product screenshots and UI diagrams, often featuring gradients and subtle 3D depth, contained within clean, rounded-corner elements, or floating freely. Data visualizations are a key visual element. There's a notable absence of lifestyle photography. Icons are filled, modern, and typically monochromatic, using either Pitch Black or occasionally Brand Electric. The visuals serve to explain complex concepts and data flow, acting as both decorative and explanatory content, occupying significant visual space in harmonious asymmetry.

## Layout

The page adheres to a mostly max-width contained model, centered on the screen, with sections flowing vertically. The hero section is a split-screen pattern, featuring a large headline and CTA on the left, balanced by a prominent product UI illustration on the right. Content sections generally maintain a consistent vertical rhythm of 64px spacing, often alternating between text-left/image-right and image-left/text-right arrangements. The footer is full-bleed with Boardroom Navy. Input fields are subtle, seamlessly integrated into the design. Card grids are not explicitly present, but data visualizations within product screenshots suggest a structured arrangement of content. The navigation is a classic top bar with a primary CTA button, sticky on scroll.

## Agent Prompt Guide

### Quick Color Reference
- Text (Primary): #171417
- Background (Page): #f9f8f6
- CTA Button: #2545ff
- Accent (Lilac): #d9d4ff
- Border (Input): #cccccc

### 3-5 Example Component Prompts
1. Create a hero section: Soft Off-White background (#f9f8f6). Left side: Headline 'You can't fix issues if you're not paying attention'. Use Abcfavoritvariable 64px, weight 500, Pitch Black (#171417), letter-spacing -3.2px, with 'not paying attention' in Martinaplantijn 64px, weight 400. Subtext 'Catch issues sooner...' in Inter 16px, weight 400, Pitch Black (#171417). Button 'Request a demo': Primary CTA Button style. Right side: Placeholder for product UI illustration (product screenshots graphic should be prominent, possibly with a subtle gradient mask, contained within a rounded 16px border-radius shape).
2. Generate a 'Request a demo' Primary CTA Button: Background Brand Electric (#2545ff), text Pure White (#ffffff), 100px border-radius, 11.2px vertical padding, 32px horizontal padding. Font: Inter, 500 weight, 16px.
3. Design an Informative Badge: Background Light Cool Gray (#eaebf8), text Boardroom Navy (#0c1754), 16px border-radius, 4px top/bottom, 12px left/right padding. Font: Inter, 400 weight, 14px.
4. Produce a footer input field: Transparent background, Pure White text (#ffffff), 1px solid bottom border in Input Border Gray (#cccccc), 0px border-radius, 12px top/bottom padding, 0px left padding. Placeholder text should be a lighter grey.

## Similar Brands

- **Slack** — Clean, colorful SaaS interface with focus on functionality and approachable design via soft corners. Uses a distinct blue accent.
- **Notion** — Applies a structured, information-dense layout with a preference for high-contrast neutrals and occasional, carefully placed brand color accents.
- **Linear** — Balances a high-contrast dark-mode aesthetic with functional, data-rich interfaces, using a single, vibrant accent color for interaction.
- **Intercom** — Features a similar combination of a strong primary brand color (blue) with extensive use of a friendly, rounded-corner aesthetic in a SaaS context.
- **Asana** — Leverages a light, spacious layout with a specific brand purple, using varying degrees of roundedness for buttons and cards to balance professionalism with user-friendliness.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-boardroom-navy: #0c1754;
  --color-brand-electric: #2545ff;
  --color-lilac-accent: #d9d4ff;
  --color-feedback-yellow: #ffc13a;
  --color-soft-off-white: #f9f8f6;
  --color-pure-white: #ffffff;
  --color-pitch-black: #171417;
  --color-medium-gray: #222222;
  --color-light-cool-gray: #eaebf8;
  --color-input-border-gray: #cccccc;
  --color-accent-orange: #ff5b22;

  /* Typography — Font Families */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-abcfavoritvariable: 'Abcfavoritvariable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-martinaplantijn: 'Martinaplantijn', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.4;
  --text-body-sm: 14px;
  --leading-body-sm: 1.43;
  --text-body: 16px;
  --leading-body: 1.6;
  --text-subheading: 20px;
  --leading-subheading: 1.4;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.1;
  --tracking-heading-sm: -0.48px;
  --text-heading: 32px;
  --leading-heading: 1.1;
  --tracking-heading: -0.64px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -2px;
  --text-display: 48px;
  --leading-display: 1.1;
  --tracking-display: -2.4px;
  --text-display-lg: 64px;
  --leading-display-lg: 1;
  --tracking-display-lg: -3.2px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-128: 128px;

  /* Layout */
  --section-gap: 64px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-lg: 9px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-full: 100px;

  /* Named Radii */
  --radius-cards: 16px;
  --radius-badges: 16px;
  --radius-inputs: 0px;
  --radius-buttons: 100px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-boardroom-navy: #0c1754;
  --color-brand-electric: #2545ff;
  --color-lilac-accent: #d9d4ff;
  --color-feedback-yellow: #ffc13a;
  --color-soft-off-white: #f9f8f6;
  --color-pure-white: #ffffff;
  --color-pitch-black: #171417;
  --color-medium-gray: #222222;
  --color-light-cool-gray: #eaebf8;
  --color-input-border-gray: #cccccc;
  --color-accent-orange: #ff5b22;

  /* Typography */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-abcfavoritvariable: 'Abcfavoritvariable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-martinaplantijn: 'Martinaplantijn', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.4;
  --text-body-sm: 14px;
  --leading-body-sm: 1.43;
  --text-body: 16px;
  --leading-body: 1.6;
  --text-subheading: 20px;
  --leading-subheading: 1.4;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.1;
  --tracking-heading-sm: -0.48px;
  --text-heading: 32px;
  --leading-heading: 1.1;
  --tracking-heading: -0.64px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -2px;
  --text-display: 48px;
  --leading-display: 1.1;
  --tracking-display: -2.4px;
  --text-display-lg: 64px;
  --leading-display-lg: 1;
  --tracking-display-lg: -3.2px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-128: 128px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-lg: 9px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-full: 100px;
}
```

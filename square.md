# Square — Style Reference
> Crisp Utility, Intuitive Flow. The UI emphasizes clarity and direct interaction, like operating a well-designed tool.

**Theme:** light

Square's design system evokes the precision of a finely tuned instrument, balancing robust functionality with an accessible aesthetic. The interplay of a predominantly white background with crisp dark typography creates a high-contrast, information-first experience that feels direct and trustworthy. Strategic use of a vibrant blue accent color serves as a clear functional indicator, like a status light on a reliable machine, guiding the user without visual clutter, while subtle rounded corners on interactive elements soften the overall technical impression.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Sky Blue | `#006aff` | `--color-sky-blue` | Call to action buttons, active navigation indicators, key functional links — a punchy visual cue for interactivity. |
| Ink Black | `#1a1a1a` | `--color-ink-black` | Primary text color for hero headlines, major body text, and prominent UI elements. High contrast ensures immediate legibility. |
| Graphite | `#737373` | `--color-graphite` | Secondary text, placeholder text in inputs, subtle borders. Provides hierarchy without stark contrast. |
| Pure White | `#ffffff` | `--color-pure-white` | Page backgrounds, card surfaces, button backgrounds in secondary states. Establishes a clean, expansive canvas. |
| Deep Black | `#030303` | `--color-deep-black` | Footer background, occasional high-contrast text elements. Creates strong visual breaks. |
| Light Fog | `#f2f2f2` | `--color-light-fog` | Alternate section backgrounds, subtle dividers, inactive states. Adds soft visual separation. |
| Ash Gray | `#cccccc` | `--color-ash-gray` | Thin borders on inactive components, dividers. Provides structure without visual weight. |
| Silver Mist | `#d9d9d9` | `--color-silver-mist` | Shadow accents on buttons, subtle boundary lines. Hints at subtle elevation. |
| Stone Gray | `#b3b3b3` | `--color-stone-gray` | Supplemental body text, very light borders. Softens text where less emphasis is needed. |

## Tokens — Typography

### Square Sans Display VF — Used for all primary headings and prominent display text. The tight letter-spacing at larger sizes gives a visually compact, impactful feel, while the moderate weights convey authority without being overbearing. · `--font-square-sans-display-vf`
- **Substitute:** Inter
- **Weights:** 400, 500
- **Sizes:** 16px, 20px, 24px, 32px, 50px, 62px, 86px
- **Line height:** 0.97, 1.10, 1.12, 1.19, 1.25, 1.30, 1.33, 1.42, 1.50
- **Letter spacing:** -0.0120em
- **Role:** Used for all primary headings and prominent display text. The tight letter-spacing at larger sizes gives a visually compact, impactful feel, while the moderate weights convey authority without being overbearing.

### Square Sans Text VF — This family is used for all body text, navigation links, and smaller UI elements. Its slightly wider proportions and normal letter spacing optimize for readability at smaller scales, ensuring clarity in dense information blocks. · `--font-square-sans-text-vf`
- **Substitute:** Inter
- **Weights:** 400, 500
- **Sizes:** 12px, 14px, 16px
- **Line height:** 1.38, 1.43, 1.50, 1.71, 1.75, 2.00, 2.63
- **Letter spacing:** normal
- **Role:** This family is used for all body text, navigation links, and smaller UI elements. Its slightly wider proportions and normal letter spacing optimize for readability at smaller scales, ensuring clarity in dense information blocks.

### Cash Sans — A distinctive, fixed-width font used sparingly for button text and specific textual accents, adding a subtle touch of technical precision and differentiating interactive elements with its unique character. · `--font-cash-sans`
- **Substitute:** IBM Plex Mono
- **Weights:** 500
- **Sizes:** 18px
- **Line height:** 1.00, 1.50
- **Letter spacing:** normal
- **Role:** A distinctive, fixed-width font used sparingly for button text and specific textual accents, adding a subtle touch of technical precision and differentiating interactive elements with its unique character.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 2 | — | `--text-caption` |
| body-sm | 14px | 1.71 | — | `--text-body-sm` |
| body | 16px | 1.5 | — | `--text-body` |
| subheading | 20px | 1.3 | — | `--text-subheading` |
| heading-sm | 24px | 1.25 | — | `--text-heading-sm` |
| heading | 32px | 1.19 | — | `--text-heading` |
| heading-lg | 50px | 1.12 | -0.5px | `--text-heading-lg` |
| display | 62px | 1.1 | -0.6px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 5 | 5px | `--spacing-5` |
| 10 | 10px | `--spacing-10` |
| 11 | 11px | `--spacing-11` |
| 12 | 12px | `--spacing-12` |
| 13 | 13px | `--spacing-13` |
| 15 | 15px | `--spacing-15` |
| 18 | 18px | `--spacing-18` |
| 20 | 20px | `--spacing-20` |
| 30 | 30px | `--spacing-30` |
| 33 | 33px | `--spacing-33` |
| 47 | 47px | `--spacing-47` |
| 60 | 60px | `--spacing-60` |
| 80 | 80px | `--spacing-80` |
| 113 | 113px | `--spacing-113` |
| 120 | 120px | `--spacing-120` |

### Border Radius

| Element | Value |
|---------|-------|
| none | 0px |
| large | 20px |
| small | 4px |
| medium | 5px |
| circular | 32px |
| extraLarge | 24px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| sm | `rgba(0, 0, 0, 0.16) 0px 1px 4px 0px` | `--shadow-sm` |

### Layout

- **Section gap:** 48px
- **Card padding:** 20px
- **Element gap:** 10-20px

## Components

### Primary Action Button
**Role:** Main call to action.

Background: Sky Blue (#006aff), Text: Pure White (#ffffff), Border: None, Radius: 5px, Padding: 13px vertical, 20px horizontal. Emphasizes primary user flow.

### Secondary Outline Button
**Role:** Secondary calls to action, navigation links.

Background: transparent (rgba(0, 0, 0, 0)), Text: Ink Black (#1a1a1a), Border: 1px solid Ink Black (#1a1a1a), Radius: 4px, Padding: 18px vertical, 10px horizontal. Offers interaction without demanding primary attention.

### Ghost Button
**Role:** Minimal interactive elements, textual links as buttons.

Background: transparent (rgba(0, 0, 0, 0)), Text: Ink Black (#1a1a1a), Border: 1px solid Ink Black (#1a1a1a), Radius: 0px, Padding: 0px. Used for sub-navigation or less prominent actions.

### Pill Button
**Role:** Categorization, filters, or internal navigation. Not used for primary actions.

Background: transparent (rgba(0, 0, 0, 0)), Text: Ink Black (#1a1a1a), Border: 1px solid Ink Black (#1a1a1a), Radius: 20px, Padding: 0px. The rounded shape sets it apart as a navigational or categorical element.

### Information Card (Light Fog)
**Role:** Showcasing features or information blocks.

Background: Light Fog (#f2f2f2), Border: None, Radius: 0px, Padding: 20px (inferred, based on sectionGap) . Provides a subtle break from the main white background, grouping related content.

### Information Card (Pure White)
**Role:** Emphasized feature cards or content blocks.

Background: Pure White (#ffffff), Border: None, Radius: 0px, Padding: 20px (inferred, based on sectionGap). Maintains the primary visual language while allowing for flexible content display.

### Text Input Field
**Role:** User input for forms.

Background: Pure White (#ffffff), Text: Ink Black (#1a1a1a), Placeholder: Graphite (#737373), Border: 1px solid Ink Black (#1a1a1a), Radius: 5px, Padding: 11px vertical, 17px horizontal. Clear visual affordance for data entry.

## Do's and Don'ts

### Do
- Use Sky Blue (#006aff) exclusively for primary calls to action and active interactive states.
- Maintain a clear hierarchy with Square Sans Display VF for headlines and Square Sans Text VF for body copy.
- Always apply a 5px radius to primary buttons and input fields for a consistent tactile feel.
- Utilize Pure White (#ffffff) as the default background for content sections to maximize readability.
- Employ Light Fog (#f2f2f2) to subtly differentiate background sections without introducing strong visual breaks. It acts as a soft divider.
- Ensure input fields have a 1px solid Ink Black (#1a1a1a) border to clearly delineate the interactive area.

### Don't
- Do not use Sky Blue (#006aff) for decorative elements or non-interactive text.
- Avoid using Cash Sans for long passages of text; reserve it for specific button labels and distinct accents.
- Do not introduce strong visual shadows on cards or elements; rely on background color changes for depth.
- Do not use highly saturated colors other than Sky Blue; maintain a largely monochromatic palette with blue as the sole accent.
- Avoid arbitrary border radii; stick to 0px, 4px, 5px, 20px, 24px, or 32px for specific component types.
- Do not use highly decorative or script fonts; maintain a modern, sans-serif aesthetic throughout.

## Imagery

The visual language focuses on a mix of authentic, often close-up photography of people interacting with Square's physical payment devices, juxtaposed with clean digital product screenshots showing the software's interface. Photography is grounded and real, often featuring hands, creating a sense of accessibility and tangibility. Product screenshots are contained within device mockups or simple rectangular masks, emphasizing clarity of the UI. Icons are simple, filled, and monochromatic, primarily Ink Black or Pure White, serving an explanatory rather than decorative role. Imagery is always contained, never full-bleed, and generally in a 16:9 or similar aspect ratio, serving to illustrate features or user benefits rather than purely aesthetic embellishment. There is a strong absence of abstract or illustrative graphics, reinforcing a practical, business-focused approach.

## Layout

The page primarily uses a max-width centered layout, containing content within a clear reading area against a continuous white background for most sections. The hero section breaks this slightly by using a two-column split: a left-aligned headline and CTA on a white canvas, paired with a right-aligned full-height photographic element. Sections alternate visually between Pure White and Light Fog (#f2f2f2) backgrounds, creating a clear vertical rhythm without hard dividers. Content is often arranged in symmetrical multi-column grids (typically 3-column for feature showcases) or left-aligned text blocks with associated visual content. Breathing room between sections is generous and consistent. The site uses a sticky top navigation bar with a centered logo and right-aligned action buttons, maintaining constant accessibility.

## Agent Prompt Guide

### Quick Color Reference
- Text: Ink Black (#1a1a1a)
- Background: Pure White (#ffffff)
- CTA: Sky Blue (#006aff)
- Border: Ink Black (#1a1a1a)
- Secondary Background: Light Fog (#f2f2f2)

### Example Component Prompts
1. Create a Hero Section: Pure White (#ffffff) background. Left-aligned headline: 'Impulsa tu negocio con Square' at 62px Square Sans Display VF, weight 500, #1a1a1a, letter-spacing -0.6px, lineHeight 1.1. Subtext at 16px Square Sans Text VF, weight 400, #1a1a1a, lineHeight 1.5. Below, add a Primary Action Button: 'Empezar', Sky Blue (#006aff) background, Pure White (#ffffff) text, 5px radius, 13px vertical, 20px horizontal padding. Next to it, a Secondary Outline Button: 'Contactar con el equipo de Ventas', transparent background, Ink Black (#1a1a1a) text, 1px solid Ink Black border, 4px radius, 18px vertical, 10px horizontal padding.
2. Design a Feature Card: Light Fog (#f2f2f2) background, 0px radius, 20px padding. Headline: 'Impulsa tu negocio en línea' at 24px Square Sans Display VF, weight 500, #1a1a1a, letter-spacing -0.0120em, lineHeight 1.25. Body text at 16px Square Sans Text VF, weight 400, #1a1a1a, lineHeight 1.5. Link text 'Descubre todas las opciones para vender en línea →' in Sky Blue (#006aff), 16px Square Sans Text VF, weight 400.
3. Build a Footer Section: Deep Black (#030303) background, Pure White (#ffffff) text. Include an email input field: Pure White (#ffffff) background, 1px solid Ink Black (#1a1a1a) border, 5px radius, 11px vertical, 17px horizontal padding, placeholder text in Graphite (#737373).

## Similar Brands

- **Stripe** — Shares a similar high-contrast, text-dominant aesthetic with a single strong accent color (blue or purple) for interactive elements and a focus on clean, functional UI.
- **Shopify** — Employs a clean, accessible layout with a strong emphasis on content readability and a similar approach to white-space and direct CTAs using a vibrant accent color on a neutral background.
- **Wise (formerly TransferWise)** — Features a light, bright UI with clear typography, structured content blocks, and the strategic use of a single, vibrant brand color to highlight key actions and information.
- **Figma** — Exhibits a functional, high-contrast UI with a clear hierarchy, restrained use of color for interaction, and a professional, no-nonsense aesthetic common in tools.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-sky-blue: #006aff;
  --color-ink-black: #1a1a1a;
  --color-graphite: #737373;
  --color-pure-white: #ffffff;
  --color-deep-black: #030303;
  --color-light-fog: #f2f2f2;
  --color-ash-gray: #cccccc;
  --color-silver-mist: #d9d9d9;
  --color-stone-gray: #b3b3b3;

  /* Typography — Font Families */
  --font-square-sans-display-vf: 'Square Sans Display VF', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-square-sans-text-vf: 'Square Sans Text VF', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-cash-sans: 'Cash Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 2;
  --text-body-sm: 14px;
  --leading-body-sm: 1.71;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 20px;
  --leading-subheading: 1.3;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.25;
  --text-heading: 32px;
  --leading-heading: 1.19;
  --text-heading-lg: 50px;
  --leading-heading-lg: 1.12;
  --tracking-heading-lg: -0.5px;
  --text-display: 62px;
  --leading-display: 1.1;
  --tracking-display: -0.6px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-10: 10px;
  --spacing-11: 11px;
  --spacing-12: 12px;
  --spacing-13: 13px;
  --spacing-15: 15px;
  --spacing-18: 18px;
  --spacing-20: 20px;
  --spacing-30: 30px;
  --spacing-33: 33px;
  --spacing-47: 47px;
  --spacing-60: 60px;
  --spacing-80: 80px;
  --spacing-113: 113px;
  --spacing-120: 120px;

  /* Layout */
  --section-gap: 48px;
  --card-padding: 20px;
  --element-gap: 10-20px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-2xl: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;

  /* Named Radii */
  --radius-none: 0px;
  --radius-large: 20px;
  --radius-small: 4px;
  --radius-medium: 5px;
  --radius-circular: 32px;
  --radius-extralarge: 24px;

  /* Shadows */
  --shadow-sm: rgba(0, 0, 0, 0.16) 0px 1px 4px 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-sky-blue: #006aff;
  --color-ink-black: #1a1a1a;
  --color-graphite: #737373;
  --color-pure-white: #ffffff;
  --color-deep-black: #030303;
  --color-light-fog: #f2f2f2;
  --color-ash-gray: #cccccc;
  --color-silver-mist: #d9d9d9;
  --color-stone-gray: #b3b3b3;

  /* Typography */
  --font-square-sans-display-vf: 'Square Sans Display VF', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-square-sans-text-vf: 'Square Sans Text VF', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-cash-sans: 'Cash Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 2;
  --text-body-sm: 14px;
  --leading-body-sm: 1.71;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 20px;
  --leading-subheading: 1.3;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.25;
  --text-heading: 32px;
  --leading-heading: 1.19;
  --text-heading-lg: 50px;
  --leading-heading-lg: 1.12;
  --tracking-heading-lg: -0.5px;
  --text-display: 62px;
  --leading-display: 1.1;
  --tracking-display: -0.6px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-10: 10px;
  --spacing-11: 11px;
  --spacing-12: 12px;
  --spacing-13: 13px;
  --spacing-15: 15px;
  --spacing-18: 18px;
  --spacing-20: 20px;
  --spacing-30: 30px;
  --spacing-33: 33px;
  --spacing-47: 47px;
  --spacing-60: 60px;
  --spacing-80: 80px;
  --spacing-113: 113px;
  --spacing-120: 120px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-2xl: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;

  /* Shadows */
  --shadow-sm: rgba(0, 0, 0, 0.16) 0px 1px 4px 0px;
}
```

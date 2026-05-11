# Base44 — Style Reference
> Softly Lit Gradient Canvas

**Theme:** light

The Base44 design system feels like a softly lit, expansive workspace, where ideas emerge clearly against a gentle, optimistic backdrop. Pastel gradients and a predominant off-white canvas create an airy, unburdened atmosphere. Subtle dark gray text and muted interactive elements ensure focus remains on content creation, while distinct, vibrant accents like lime green and vivid orange are used sparingly for key actions, adding a precise, almost signal-like pop of functionality. Rounded corners on interactive components juxtapose with the generally crisp, unadorned typography, softening the technical edge of an AI platform.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas Pearl | `#faf9f7` | `--color-canvas-pearl` | Page backgrounds, subtle card surfaces |
| Snowdrift White | `#ffffff` | `--color-snowdrift-white` | Observed in link borderColor, other backgroundColor, button borderColor. Extracted usage does not support a distinct primary control color. |
| Ink Black | `#000000` | `--color-ink-black` | Primary text, prominent headings, strong borders |
| Graphite Text | `#232529` | `--color-graphite-text` | Secondary text, input placeholder text, subtle borders |
| Slate Gray | `#324158` | `--color-slate-gray` | Dividers, subtle accent borders on cards |
| Stone Whisper | `#696f7b` | `--color-stone-whisper` | Muted body text, supportive captions, subtle input backgrounds |
| #e6e6e6 | `#e6e6e6` | `--color-e6e6e6` | Backgrounds for decorative elements and subtle section dividers |
| Ash Border | `#cfcfcf` | `--color-ash-border` | Default button borders, light input borders |
| Lime Spritz | `#ade900` | `--color-lime-spritz` | Primary action button borders, 'Start Building' button accent |
| Light Lime | `#ebffb1` | `--color-light-lime` | Selected item background, subtle brand highlights |
| Sunset Orange | `#d8723c` | `--color-sunset-orange` | Outlined action button borders for prompts |
| Blazing Orange | `#ff631f` | `--color-blazing-orange` | Decorative illustration accents, brand iconography |
| Sky Dream Gradient | `linear-gradient(rgb(242, 241, 237) 42.49%, rgb(213, 223, 224) 93.98%, rgb(229, 255, 148) 104.08%)` | `--color-sky-dream-gradient` | Hero section background |
| Warm Horizon Gradient | `linear-gradient(rgba(251, 250, 248, 0) 0%, rgba(255, 240, 222, 0.3) 18.28%, rgb(255, 174, 83) 43.58%, rgb(255, 127, 71) 55.6%, rgba(255, 174, 83, 0) 80.7%)` | `--color-warm-horizon-gradient` | Hero section background |

## Tokens — Typography

### Arial — Small functional text like captions, utility links, and fine print. The system font choice maintains legibility at small sizes. · `--font-arial`
- **Substitute:** Arial
- **Weights:** 400
- **Sizes:** 10px, 13px, 14px
- **Line height:** 1.20
- **Role:** Small functional text like captions, utility links, and fine print. The system font choice maintains legibility at small sizes.

### wfont_343a2a_5b4cd32fc19d46e1b8c1b142abb27d39 — Display and Major Headings — its generous letter spacing and fluid line heights give large text a soft, open presence. · `--font-wfont343a2a5b4cd32fc19d46e1b8c1b142abb27d39`
- **Substitute:** system-ui
- **Weights:** 400
- **Sizes:** 22px, 24px, 34px, 51px, 55px, 56px, 63px
- **Line height:** 0.90, 1.00, 1.07, 1.10, 1.40
- **Role:** Display and Major Headings — its generous letter spacing and fluid line heights give large text a soft, open presence.

### wfont_343a2a_4e484da66ffc4465a05a1c9ea5caf495 — Section headings and content titles — slightly more structured than display text, maintaining readability without feeling dense. · `--font-wfont343a2a4e484da66ffc4465a05a1c9ea5caf495`
- **Substitute:** system-ui
- **Weights:** 400
- **Sizes:** 16px, 20px, 28px, 30px, 42px
- **Line height:** 1.00, 1.20, 1.30
- **Role:** Section headings and content titles — slightly more structured than display text, maintaining readability without feeling dense.

### wix-madefor-text-v2 — Body text and user input fields — consistent letter spacing across weights ensures clarity in both continuous prose and short UI labels. · `--font-wix-madefor-text-v2`
- **Substitute:** system-ui
- **Weights:** 400, 500, 600, 700
- **Sizes:** 12px, 14px, 16px, 18px
- **Line height:** 1.20, 1.30, 1.40, 1.50, 1.60
- **Letter spacing:** 0.1em
- **Role:** Body text and user input fields — consistent letter spacing across weights ensures clarity in both continuous prose and short UI labels.

### Madefor-Text — Navigation and button labels — a steady weight for interactive elements that need to be clear and inviting. · `--font-madefor-text`
- **Substitute:** system-ui
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.20
- **Role:** Navigation and button labels — a steady weight for interactive elements that need to be clear and inviting.

### Madefor-Display — Microcopy and specialized decorative text, offering a distinctive voice for minor elements. · `--font-madefor-display`
- **Substitute:** system-ui
- **Weights:** 400
- **Sizes:** 10px
- **Line height:** 1.20
- **Role:** Microcopy and specialized decorative text, offering a distinctive voice for minor elements.

### wfont_343a2a_5b4cd32fc19d46e1b8c1b142abb27d39 — wfont_343a2a_5b4cd32fc19d46e1b8c1b142abb27d39 — detected in extracted data but not described by AI · `--font-wfont343a2a5b4cd32fc19d46e1b8c1b142abb27d39`
- **Weights:** 400
- **Sizes:** 22px, 24px, 34px, 51px, 55px, 56px, 63px
- **Line height:** 0.9, 1, 1.07, 1.1, 1.4
- **Role:** wfont_343a2a_5b4cd32fc19d46e1b8c1b142abb27d39 — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.2 | — | `--text-caption` |
| body | 14px | 1.2 | 0.1px | `--text-body` |
| heading-sm | 20px | 1.2 | — | `--text-heading-sm` |
| heading | 28px | 1.3 | — | `--text-heading` |
| heading-lg | 42px | 1.3 | — | `--text-heading-lg` |
| display | 56px | 1.07 | — | `--text-display` |

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
| 36 | 36px | `--spacing-36` |
| 40 | 40px | `--spacing-40` |
| 68 | 68px | `--spacing-68` |
| 76 | 76px | `--spacing-76` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 7.42183px |
| small | 3px |
| buttons | 999px |
| default | 9.89577px |
| compact-buttons | 300px |
| decorative-large | 741.445px |
| prominent-elements | 13.8541px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| md | `rgba(34, 40, 42, 0.04) 0px 3px 10px 0px` | `--shadow-md` |

### Layout

- **Section gap:** 45px
- **Card padding:** 40px
- **Element gap:** 10px

## Components

### Primary Navigation Link
**Role:** Interactive element

Text link using Madefor-Text at 16px, weight 400, Ink Black #000000, without explicit padding or border.

### Header CTA Button
**Role:** Primary Call to Action

Background is Light Lime #ebffb1, border is 1px solid Lime Spritz #ade900, text is Madefor-Text at 16px weight 400 Ink Black #000000. Features a 999px border-radius for a pill shape.

### Ghost Button
**Role:** Secondary action

Transparent background, text is Ink Black #000000, 1px border in Ash Border #cfcfcf, with 999px border-radius. Padding of 0px vertical and 16px horizontal.

### Feature Card
**Role:** Content container

White background offset from Canvas Pearl, with a 7.42183px border-radius. No box shadow evident. Padding is 0px.

### Input Field
**Role:** Data entry

Background is Snowdrift White #ffffff, text is Graphite Text #232529. Placeholder text would use Graphite Text. Has a transparent border. Padding of 15px top, 3px bottom, 10px right, 24px left.

### Suggestion Pill Button
**Role:** Interactive filter/suggestion

Transparent background, text is Ink Black #000000, with a 1px border in a lightened Graphite Text rgb(15, 15, 15, 0.2). Features a 999px border-radius. Padding is 0px vertical and 16px horizontal.

### New Feature Tag
**Role:** Informational label

Uses a solid Coral Orange '#d8723c', with Snowdrift White text, 999px border-radius, and tight internal padding.

### Toggle Switch
**Role:** Binary control

A pill-shaped background with a distinct fill color when active (e.g. Light Lime #ebffb1), with a circular 'handle' (Snowdrift White #ffffff) that slides along its track.

### Text Input Button
**Role:** Secondary Call to Action

A transparent background button with Ink Black #000000 text, 0px border-radius and minimal padding (8px top, 12px horizontal).

### Modal Card
**Role:** Overlay content

Background is Snowdrift White #ffffff, border-radius is 7.42183px, with a subtle box-shadow: rgba(34, 40, 42, 0.04) 0px 3px 10px 0px.

## Do's and Don'ts

### Do
- Use Canvas Pearl #faf9f7 for primary page backgrounds to maintain an airy feel.
- Apply Snowdrift White #ffffff for card surfaces and interactive elements to create soft contrast and elevation against the canvas.
- Reserve Ink Black #000000 for primary text and headings, ensuring high readability.
- Implement Ghost Button styling with a 1px Ash Border #cfcfcf and 999px border-radius for secondary actions.
- Utilize Lime Spritz #ade900 for CTA button borders and key interactive indicators, contrasting with the soft neutrals.
- Maintain a comfortable information density using an average elementGap of 10px and sectionGap of 45px.
- Employ the 999px border-radius for all primary buttons and tags to deliver a consistent, rounded interactive experience.

### Don't
- Avoid using saturated background colors for large sections; gradients should remain pastel and subtle.
- Do not use dark text colors on anything but light backgrounds to preserve contrast and system aesthetic.
- Do not introduce sharp corners on interactive elements; prefer soft rounding (999px or 9.89577px) for buttons and inputs.
- Do not apply prominent box shadows for elevation; rely on subtle background color shifts or the single rgba(34, 40, 42, 0.04) 0px 3px 10px 0px for modals.
- Avoid introducing additional vivid colors outside of Lime Spritz #ade900 and Sunset Orange #d8723c to maintain focused accents.
- Do not break the established type scale; ensure all text adheres to defined sizes, weights, and line heights for consistent rhythm.
- Avoid using complex or busy background imagery; prefer soft gradients or solid colors that allow UI elements to stand out.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas Pearl | `#faf9f7` | Base page background |
| 1 | Snowdrift White | `#ffffff` | Primary surface for cards, inputs, and interactive elements |

## Imagery

The site largely avoids traditional photography, instead relying on UI-as-imagery presentation and abstract graphics. Product screenshots are contained within device outlines or soft-edged cards, maintaining a pristine, focused view. Icons are primarily subtle outlines (stroke-based) in Ink Black or Graphite Text, occasionally filled with a brand accent color. Decorative graphics utilize soft, multi-color gradients for atmospheric branding, never overlapping content but often serving as full-bleed background elements. Imagery is explanatory or decorative, never serving as social proof or lifestyle elements. The density is image-light, text-dominant, with visual weight primarily in UI demonstrations.

## Layout

The page model is a full-bleed background, with content constrained to a central max-width (unspecified in data but implied by content alignment). The hero section features a full-viewport gradient background with a centered headline and a primary input pattern, creating an immediate focal point. Section rhythm alternates between full-bleed gradient backgrounds and solid Canvas Pearl #faf9f7 sections, clearly delineating content blocks. Content arrangement often uses centered stacks for headlines and subtext, followed by symmetrical grid layouts for suggestions or feature cards. The main navigation is a sticky top bar with text links and a distinct green pill button for the main CTA. The overall density is spacious, ensuring ample breathing room around elements.

## Agent Prompt Guide

Quick Color Reference: 
- text: #000000
- background: #faf9f7
- border: #cfcfcf
- accent: #ade900
- primary action: #ebffb1 (filled action)

Example Component Prompts:
1. Create a Primary Action Button: #ebffb1 background, #000000 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Develop a Header CTA Button: background Light Lime #ebffb1, border 1px solid Lime Spritz #ade900, text 'Start Building' using Madefor-Text at 16px weight 400, Ink Black #000000. Apply a 999px border-radius. Padding 0px vertical, 16px horizontal.
3. Design an Input Field: background Snowdrift White #ffffff, text Graphite Text #232529. Border is transparent. Padding 15px top, 3px bottom, 10px right, 24px left.
4. Construct a Feature Card: background Snowdrift White #ffffff, border-radius 7.42183px. No box shadow. Padding 0px.

## Similar Brands

- **Stripe** — Similar use of subtle gradients and high contrast text on light, clean surfaces, with a focus on functional UI over heavy imagery.
- **Linear** — Clear emphasis on typography and structured layouts, with minimal branding colors reserved for highly functional elements or accents.
- **Figma** — Light base theme, liberal use of rounded corners on interactive elements, and strategic use of a few bright accent colors for key actions.
- **Webflow** — Clean, almost iridescent gradient backgrounds often used in hero sections, paired with modern sans-serif typography and soft neutral palettes.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-pearl: #faf9f7;
  --color-snowdrift-white: #ffffff;
  --color-ink-black: #000000;
  --color-graphite-text: #232529;
  --color-slate-gray: #324158;
  --color-stone-whisper: #696f7b;
  --color-e6e6e6: #e6e6e6;
  --color-ash-border: #cfcfcf;
  --color-lime-spritz: #ade900;
  --color-light-lime: #ebffb1;
  --color-sunset-orange: #d8723c;
  --color-blazing-orange: #ff631f;
  --color-sky-dream-gradient: #F2F1ED;
  --gradient-sky-dream-gradient: linear-gradient(rgb(242, 241, 237) 42.49%, rgb(213, 223, 224) 93.98%, rgb(229, 255, 148) 104.08%);
  --color-warm-horizon-gradient: #FBFBFB;
  --gradient-warm-horizon-gradient: linear-gradient(rgba(251, 250, 248, 0) 0%, rgba(255, 240, 222, 0.3) 18.28%, rgb(255, 174, 83) 43.58%, rgb(255, 127, 71) 55.6%, rgba(255, 174, 83, 0) 80.7%);

  /* Typography — Font Families */
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-wfont343a2a5b4cd32fc19d46e1b8c1b142abb27d39: 'wfont_343a2a_5b4cd32fc19d46e1b8c1b142abb27d39', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-wfont343a2a4e484da66ffc4465a05a1c9ea5caf495: 'wfont_343a2a_4e484da66ffc4465a05a1c9ea5caf495', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-wix-madefor-text-v2: 'wix-madefor-text-v2', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-madefor-text: 'Madefor-Text', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-madefor-display: 'Madefor-Display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.2;
  --text-body: 14px;
  --leading-body: 1.2;
  --tracking-body: 0.1px;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.2;
  --text-heading: 28px;
  --leading-heading: 1.3;
  --text-heading-lg: 42px;
  --leading-heading-lg: 1.3;
  --text-display: 56px;
  --leading-display: 1.07;

  /* Typography — Weights */
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
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-68: 68px;
  --spacing-76: 76px;

  /* Layout */
  --section-gap: 45px;
  --card-padding: 40px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-sm: 3px;
  --radius-lg: 7.42183px;
  --radius-lg-2: 9.89577px;
  --radius-xl: 13.8541px;
  --radius-3xl: 25.9766px;
  --radius-3xl-2: 30px;
  --radius-full: 59.375px;
  --radius-full-2: 70px;
  --radius-full-3: 100px;
  --radius-full-4: 300px;
  --radius-full-5: 741.445px;
  --radius-full-6: 999px;

  /* Named Radii */
  --radius-cards: 7.42183px;
  --radius-small: 3px;
  --radius-buttons: 999px;
  --radius-default: 9.89577px;
  --radius-compact-buttons: 300px;
  --radius-decorative-large: 741.445px;
  --radius-prominent-elements: 13.8541px;

  /* Shadows */
  --shadow-md: rgba(34, 40, 42, 0.04) 0px 3px 10px 0px;

  /* Surfaces */
  --surface-canvas-pearl: #faf9f7;
  --surface-snowdrift-white: #ffffff;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-pearl: #faf9f7;
  --color-snowdrift-white: #ffffff;
  --color-ink-black: #000000;
  --color-graphite-text: #232529;
  --color-slate-gray: #324158;
  --color-stone-whisper: #696f7b;
  --color-e6e6e6: #e6e6e6;
  --color-ash-border: #cfcfcf;
  --color-lime-spritz: #ade900;
  --color-light-lime: #ebffb1;
  --color-sunset-orange: #d8723c;
  --color-blazing-orange: #ff631f;
  --color-sky-dream-gradient: #F2F1ED;
  --color-warm-horizon-gradient: #FBFBFB;

  /* Typography */
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-wfont343a2a5b4cd32fc19d46e1b8c1b142abb27d39: 'wfont_343a2a_5b4cd32fc19d46e1b8c1b142abb27d39', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-wfont343a2a4e484da66ffc4465a05a1c9ea5caf495: 'wfont_343a2a_4e484da66ffc4465a05a1c9ea5caf495', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-wix-madefor-text-v2: 'wix-madefor-text-v2', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-madefor-text: 'Madefor-Text', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-madefor-display: 'Madefor-Display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.2;
  --text-body: 14px;
  --leading-body: 1.2;
  --tracking-body: 0.1px;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.2;
  --text-heading: 28px;
  --leading-heading: 1.3;
  --text-heading-lg: 42px;
  --leading-heading-lg: 1.3;
  --text-display: 56px;
  --leading-display: 1.07;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-68: 68px;
  --spacing-76: 76px;

  /* Border Radius */
  --radius-sm: 3px;
  --radius-lg: 7.42183px;
  --radius-lg-2: 9.89577px;
  --radius-xl: 13.8541px;
  --radius-3xl: 25.9766px;
  --radius-3xl-2: 30px;
  --radius-full: 59.375px;
  --radius-full-2: 70px;
  --radius-full-3: 100px;
  --radius-full-4: 300px;
  --radius-full-5: 741.445px;
  --radius-full-6: 999px;

  /* Shadows */
  --shadow-md: rgba(34, 40, 42, 0.04) 0px 3px 10px 0px;
}
```

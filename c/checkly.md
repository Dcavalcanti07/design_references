# Checkly — Style Reference
> Midnight Terminal Canvas

**Theme:** dark

Checkly employs a dark-mode command center aesthetic with a focus on code-centric visualization. Deep blues and near-black surfaces are punctuated by vivid blue accents for interactive elements and critical information. Typography is precise and utilitarian, prioritizing legibility within code blocks and clean hierarchy for display text. Components feature subtle elevation and controlled use of rounded corners, creating a sense of understated robustness.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Deep Space Blue | `#041734` | `--color-deep-space-blue` | Primary background for hero sections and key content blocks, dark button fills |
| Midnight Ink | `#002652` | `--color-midnight-ink` | Text on lighter dark surfaces, secondary navigation text, active states |
| Charcoal Slate | `#0f172a` | `--color-charcoal-slate` | Darkest card backgrounds, deeply nested surface elements |
| Storm Gray | `#374151` | `--color-storm-gray` | Muted text for secondary information, card borders, inactive navigation links |
| Dark Steel | `#1f2937` | `--color-dark-steel` | Dark borders and separators for elevated surfaces and inverted UI. Do not promote it to the primary CTA color |
| Light Ash | `#a7babe` | `--color-light-ash` | Body text on dark backgrounds, helper text, link text in paragraph content |
| Electric Blue | `#0075ff` | `--color-electric-blue` | Blue text accent for links, tags, and emphasized short phrases. Do not promote it to the primary CTA color |
| Subtle Gray | `#445458` | `--color-subtle-gray` | Icon fills, very subtle secondary text on dark surfaces |
| Navy Black | `#061220` | `--color-navy-black` | Deep background for elevated cards and distinct content containers |
| Code Block Gray | `#1a1f36` | `--color-code-block-gray` | Background for code snippets and console-like sections |
| Silver Pine | `#64748b` | `--color-silver-pine` | Placeholder text, very subtle tertiary text details |
| Deep Ocean Blue | `#001027` | `--color-deep-ocean-blue` | Background for deeply embedded cards or sections requiring higher contrast from surrounding dark elements |
| Cloud Gray Border | `#cfdfec` | `--color-cloud-gray-border` | Light border for outline buttons |
| Vivid Blue | `#008ef0` | `--color-vivid-blue` | Accent for filled action buttons, subtle highlight states |
| Success Green | `#4ade80` | `--color-success-green` | Green text accent for links, tags, and emphasized short phrases. Use as a supporting accent, not as a status color |
| Lightest Gray | `#e5e7eb` | `--color-lightest-gray` | Hairline borders, dividers, input outlines, and card edges on light surfaces. Do not promote it to the primary CTA color |
| Pure Black | `#000000` | `--color-pure-black` | Brand text on light backgrounds, icon fills where stark contrast is needed |
| Pure White | `linear-gradient(rgb(255, 255, 255), rgba(96, 148, 193, 0.2))` | `--color-pure-white` | Primary text on dark backgrounds, backgrounds for light-themed sections, essential button fills; Specialized button background with a subtle gradient hint |
| Mid Gray | `#cccccc` | `--color-mid-gray` | Muted text, subtle borders, inactive elements |
| Dark Overlay | `#bfbfbf` | `--color-dark-overlay` | Shadow color for card elevation |
| Darkest Card | `#0d1117` | `--color-darkest-card` | Specific, very dark card background |
| Medium Gray Border | `#d1d5db` | `--color-medium-gray-border` | Default input borders, inactive card borders |

## Tokens — Typography

### Inter — Primary typeface for all brand copy, headings, body text, and UI components. It establishes a modern and professional tone. · `--font-inter`
- **Substitute:** system-ui
- **Weights:** 300, 400, 500, 600, 700
- **Sizes:** 10px, 12px, 14px, 16px, 18px, 20px, 24px, 30px, 32px, 48px, 60px
- **Line height:** 1.00, 1.20, 1.25, 1.33, 1.40, 1.43, 1.50, 1.56, 1.63, 2.40
- **Letter spacing:** -0.0400em at 60px, -0.0250em at 48px, 0.0500em at 10px, normal at 12px-32px
- **Role:** Primary typeface for all brand copy, headings, body text, and UI components. It establishes a modern and professional tone.

### ui-monospace — Used for command-line instructions, code snippets, and areas where monospace formatting is essential for technical accuracy and readability. · `--font-ui-monospace`
- **Substitute:** monospace
- **Weights:** 400, 500
- **Sizes:** 11px, 12px, 14px
- **Line height:** 1.33, 1.43, 1.63
- **Letter spacing:** normal
- **Role:** Used for command-line instructions, code snippets, and areas where monospace formatting is essential for technical accuracy and readability.

### JetBrains Mono — Specialized monospace font primarily used for displaying code in product screenshots and dedicated code blocks, providing enhanced legibility for programming content. Its presence signifies the brand's developer-centric focus. · `--font-jetbrains-mono`
- **Substitute:** monospace
- **Weights:** 400
- **Sizes:** 10px, 12px, 16px
- **Line height:** 1.50, 1.63
- **Letter spacing:** normal
- **Role:** Specialized monospace font primarily used for displaying code in product screenshots and dedicated code blocks, providing enhanced legibility for programming content. Its presence signifies the brand's developer-centric focus.

### Consolas — Consolas — detected in extracted data but not described by AI · `--font-consolas`
- **Weights:** 400
- **Sizes:** 10px
- **Line height:** 1.5
- **Role:** Consolas — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.5 | 0.5px | `--text-caption` |
| body | 16px | 1.5 | — | `--text-body` |
| subheading | 18px | 1.56 | — | `--text-subheading` |
| heading-sm | 24px | 1.33 | — | `--text-heading-sm` |
| heading | 32px | 1.25 | — | `--text-heading` |
| heading-lg | 48px | 1.2 | -0.48px | `--text-heading-lg` |
| display | 60px | 1 | -0.6px | `--text-display` |

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
| 56 | 56px | `--spacing-56` |
| 64 | 64px | `--spacing-64` |
| 72 | 72px | `--spacing-72` |
| 80 | 80px | `--spacing-80` |
| 96 | 96px | `--spacing-96` |
| 104 | 104px | `--spacing-104` |
| 144 | 144px | `--spacing-144` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 9999px |
| cards | 12px |
| inputs | 4px |
| buttons | 8px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| md | `rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1)...` | `--shadow-md` |
| xl | `rgba(0, 0, 0, 0.25) 0px 25px 50px -12px` | `--shadow-xl` |
| xl-2 | `rgb(0, 117, 255) 0px 25px 50px -12px` | `--shadow-xl-2` |
| md-2 | `rgba(0, 0, 0, 0.25) 0px 4px 12px 0px, rgba(0, 0, 0, 0.15)...` | `--shadow-md-2` |
| subtle | `rgba(0, 0, 0, 0.05) 0px 1px 2px 0px` | `--shadow-subtle` |

### Layout

- **Section gap:** 48px
- **Element gap:** 12px

## Components

### Floating Action Button
**Role:** Key action buttons with a distinct, larger appearance.

Background: Gradient Button Light (#ffffff to rgba(96, 148, 193, 0.2)), Text: Pure Black (#000000), Radius: 16px, Padding: 32px all.

### Solid Action Button
**Role:** Primary interactive buttons for calls to action.

Background: Vivid Blue (#008ef0) or Deep Space Blue (#041734), Text: Pure White (#ffffff), Radius: 8px, Padding: 10px vertical, 16px horizontal.

### Ghost Outline Button
**Role:** Secondary or tertiary actions, often subtle.

Background: transparent, Text: Light Ash (#a7babe) or Lightest Gray (#e5e7eb), Border: 1px solid Cloud Gray Border (#cfdfec) or Lightest Gray (#e5e7eb), Radius: 8px, Padding: 6px vertical, 10px horizontal.

### Text Link Button
**Role:** Inline actions or navigation items that act as buttons.

Background: transparent, Text: Lightest Gray (#e5e7eb), No explicit border, Radius: 0px, Padding: 14px vertical, 0px horizontal.

### Default Card
**Role:** Base container for content, appearing within sections.

Background: Dark Steel (#1f2937), Radius: 12px, Shadow: rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1) 0px 4px 6px -4px. No padding provided in data for this variant, implying content controls its own spacing.

### Elevated Code Card
**Role:** Cards specifically for displaying code or console-like output with a clear visual separation.

Background: Charcoal Slate (#0f172a), Radius: 8px, Shadow: rgba(0, 0, 0, 0.25) 0px 25px 50px -12px. No padding provided in data for this variant, implying content controls its own spacing.

### Inset Detail Card
**Role:** Cards used for detailed data or controls, with a subtle internal glow.

Background: Deep Ocean Blue (#001027), Radius: 12px, Shadow: rgba(0, 0, 0, 0.25) 0px 4px 12px 0px, rgba(0, 0, 0, 0.15) 0px 1px 3px 0px, rgba(255, 255, 255, 0.04) 0px 1px 0px 0px inset. Padding: 16px vertical, 20px horizontal.

### Inline Tag
**Role:** Small, informational labels.

Background: Deep Space Blue (#041734), Text: Pure White (#ffffff), Radius: 9999px (pill-shaped), often appears with minimal padding from contextual text.

## Do's and Don'ts

### Do
- Use Inter font family for all primary text content, adjusting weights (300-700) to create hierarchy.
- Apply Deep Space Blue (#041734) as the base background for major sections and hero components, ensuring text is Pure White (#ffffff) for contrast.
- Utilize Electric Blue (#0075ff) specifically for highlighting interactive elements, active states, and as an accent color in product graphics.
- Maintain a clear visual hierarchy by limiting shadows to card components, employing the specified rgba(0, 0, 0, 0.1) 0px 10px 15px -3px stack for subtle elevation.
- Employ a consistent 12px elementGap for default spacing between UI controls and related content blocks.
- Ensure all primary call-to-action buttons use a Solid Action Button style with Vivid Blue (#008ef0) or Deep Space Blue (#041734) background for clear interaction signals.
- Code snippets and technical content must use ui-monospace or JetBrains Mono for authenticity and specific rendering.

### Don't
- Avoid using Pure Black (#000000) for general text on dark backgrounds; prefer Pure White (#ffffff) or Light Ash (#a7babe).
- Do not introduce new color hues; stick to the approved palette of blues, grays, and the single vivid green for success states.
- Never arbitrarily change corner radii; use 8px for buttons, 12px for cards, and 9999px (pill shape) for tags.
- Do not deviate from the defined type scale; always map content to one of the specified roles (caption, body-sm, body, etc.) with their respective sizes and line heights.
- Refrain from using strong, colorful background gradients outside of the specified 'Gradient Button Light' component.
- Avoid excessive spacing or too many different spacing values; adhere to the 4px base unit and established element, card, and section gaps.
- Do not use shadows on elements that are not designated as cards or specifically requiring elevation.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Deep Space Blue Canvas | `#041734` | Primary page background for hero sections and base content. |
| 1 | Dark Steel Card Surface | `#1f2937` | Default background for major content cards and information panels. |
| 2 | Charcoal Slate Code Surface | `#0f172a` | Elevated surface for code blocks and console-like displays. |
| 3 | Deep Ocean Blue Inset Card | `#001027` | Highest elevation for detailed data cards with an inset shadow effect. |

## Elevation

- **Default Card:** `rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1) 0px 4px 6px -4px`
- **Elevated Code Card:** `rgba(0, 0, 0, 0.25) 0px 25px 50px -12px`
- **Inset Detail Card:** `rgba(0, 0, 0, 0.25) 0px 4px 12px 0px, rgba(0, 0, 0, 0.15) 0px 1px 3px 0px, rgba(255, 255, 255, 0.04) 0px 1px 0px 0px inset`
- **Icon Highlight Shadow:** `rgb(0, 117, 255) 0px 25px 50px -12px`

## Imagery

The site favors illustrative, abstract graphics that represent data flows and network connections. These are typically blue-hued outlines or filled shapes on dark backgrounds, often radiating from a central focal point. Product screenshots are prominent, featuring dark mode UI elements with vibrant accents, showcasing code and monitoring dashboards. Occasionally, there are simple, filled icons (like the raccoon mascot) and system-like icons (outlined, moderate stroke weight) used decoratively or functionally. Imagery plays an explanatory role for product features and adds atmospheric depth to the UI, maintaining a text-dominant feel with images serving as visual anchors.

## Layout

The page primarily uses a max-width contained layout, though the initial hero section spans full-bleed. The hero features a centered headline over a deep blue background with abstract, interconnected lines. Section rhythm alternates between full-bleed dark sections (Deep Space Blue) and slightly lighter dark sections (like Dark Steel or Charcoal Slate), creating distinct visual blocks. Content arrangement often employs a two-column layout with text on one side and product screenshots or graphics on the other, or centered stacks of information modules. While no explicit grid system is mentioned beyond card layouts, a consistent vertical spacing creates clear visual separation. Navigation is handled by a sticky top bar.

## Agent Prompt Guide

### Quick Color Reference
- text: #ffffff
- background: #041734
- border: #e5e7eb
- accent: #0075ff
- primary action: #041734 (filled action)

### 3-5 Example Component Prompts
- Create a hero section: background Deep Space Blue (#041734). Headline 'Detect. Communicate. Resolve.' using Inter 60px weight 700 with letter-spacing -0.6px, color Pure White (#ffffff). Subtext 'Checkly unifies testing...' using Inter 20px weight 400, color Light Ash (#a7babe).
- Create a Primary Action Button: #041734 background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
- Create a Ghost Outline Button: 'Start for free' uses transparent background, Inter 16px weight 500, Lightest Gray (#e5e7eb) text, 1px solid Cloud Gray Border (#cfdfec), 8px radius, 6px vertical and 10px horizontal padding.
- Create a Default Card: background Dark Steel (#1f2937), radius 12px, box-shadow rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1) 0px 4px 6px -4px. Content: heading using Inter 24px weight 600, Pure White (#ffffff), body text Inter 16px weight 400, Light Ash (#a7babe).
- Create a code block using `JetBrains Mono` at 12px weight 400, text Pure White (#ffffff), within an Elevated Code Card (background Charcoal Slate (#0f172a), radius 8px, box-shadow rgba(0, 0, 0, 0.25) 0px 25px 50px -12px).

## Similar Brands

- **Vercel** — Similar dark-mode technical aesthetic with focus on code, generous spacing, and a single vibrant accent color.
- **Linear** — Utilitarian dark UI, precise typography with monospace fonts embedded in UI, and a subtle elevation system using soft shadows.
- **Supabase** — Developer-centric brand with dark themes, distinct card components, and an emphasis on code snippets within the UI.
- **Postman** — API-focused platform with a deep-blue/dark interface, clean typography, and structured content presentation.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-deep-space-blue: #041734;
  --color-midnight-ink: #002652;
  --color-charcoal-slate: #0f172a;
  --color-storm-gray: #374151;
  --color-dark-steel: #1f2937;
  --color-light-ash: #a7babe;
  --color-electric-blue: #0075ff;
  --color-subtle-gray: #445458;
  --color-navy-black: #061220;
  --color-code-block-gray: #1a1f36;
  --color-silver-pine: #64748b;
  --color-deep-ocean-blue: #001027;
  --color-cloud-gray-border: #cfdfec;
  --color-vivid-blue: #008ef0;
  --color-success-green: #4ade80;
  --color-lightest-gray: #e5e7eb;
  --color-pure-black: #000000;
  --color-pure-white: #ffffff;
  --gradient-pure-white: linear-gradient(rgb(255, 255, 255), rgba(96, 148, 193, 0.2));
  --color-mid-gray: #cccccc;
  --color-dark-overlay: #bfbfbf;
  --color-darkest-card: #0d1117;
  --color-medium-gray-border: #d1d5db;

  /* Typography — Font Families */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ui-monospace: 'ui-monospace', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-jetbrains-mono: 'JetBrains Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-consolas: 'Consolas', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --tracking-caption: 0.5px;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.56;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.33;
  --text-heading: 32px;
  --leading-heading: 1.25;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -0.48px;
  --text-display: 60px;
  --leading-display: 1;
  --tracking-display: -0.6px;

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
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-104: 104px;
  --spacing-144: 144px;

  /* Layout */
  --section-gap: 48px;
  --element-gap: 12px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-tags: 9999px;
  --radius-cards: 12px;
  --radius-inputs: 4px;
  --radius-buttons: 8px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1) 0px 4px 6px -4px;
  --shadow-xl: rgba(0, 0, 0, 0.25) 0px 25px 50px -12px;
  --shadow-xl-2: rgb(0, 117, 255) 0px 25px 50px -12px;
  --shadow-md-2: rgba(0, 0, 0, 0.25) 0px 4px 12px 0px, rgba(0, 0, 0, 0.15) 0px 1px 3px 0px, rgba(255, 255, 255, 0.04) 0px 1px 0px 0px inset;
  --shadow-subtle: rgba(0, 0, 0, 0.05) 0px 1px 2px 0px;

  /* Surfaces */
  --surface-deep-space-blue-canvas: #041734;
  --surface-dark-steel-card-surface: #1f2937;
  --surface-charcoal-slate-code-surface: #0f172a;
  --surface-deep-ocean-blue-inset-card: #001027;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-deep-space-blue: #041734;
  --color-midnight-ink: #002652;
  --color-charcoal-slate: #0f172a;
  --color-storm-gray: #374151;
  --color-dark-steel: #1f2937;
  --color-light-ash: #a7babe;
  --color-electric-blue: #0075ff;
  --color-subtle-gray: #445458;
  --color-navy-black: #061220;
  --color-code-block-gray: #1a1f36;
  --color-silver-pine: #64748b;
  --color-deep-ocean-blue: #001027;
  --color-cloud-gray-border: #cfdfec;
  --color-vivid-blue: #008ef0;
  --color-success-green: #4ade80;
  --color-lightest-gray: #e5e7eb;
  --color-pure-black: #000000;
  --color-pure-white: #ffffff;
  --color-mid-gray: #cccccc;
  --color-dark-overlay: #bfbfbf;
  --color-darkest-card: #0d1117;
  --color-medium-gray-border: #d1d5db;

  /* Typography */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ui-monospace: 'ui-monospace', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-jetbrains-mono: 'JetBrains Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-consolas: 'Consolas', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --tracking-caption: 0.5px;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.56;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.33;
  --text-heading: 32px;
  --leading-heading: 1.25;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -0.48px;
  --text-display: 60px;
  --leading-display: 1;
  --tracking-display: -0.6px;

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
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-104: 104px;
  --spacing-144: 144px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-full: 9999px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1) 0px 4px 6px -4px;
  --shadow-xl: rgba(0, 0, 0, 0.25) 0px 25px 50px -12px;
  --shadow-xl-2: rgb(0, 117, 255) 0px 25px 50px -12px;
  --shadow-md-2: rgba(0, 0, 0, 0.25) 0px 4px 12px 0px, rgba(0, 0, 0, 0.15) 0px 1px 3px 0px, rgba(255, 255, 255, 0.04) 0px 1px 0px 0px inset;
  --shadow-subtle: rgba(0, 0, 0, 0.05) 0px 1px 2px 0px;
}
```

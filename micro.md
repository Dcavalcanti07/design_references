# Micro — Style Reference
> layered productivity canvas

**Theme:** light

Micro's design system creates a focused, productivity-driven interface with a soft, layered feel. Predominantly light surfaces are grounded by sharp, dark typography and an understated use of colorful accents for status and focus. Components favor soft borders and subtle elevation, appearing as crisp sheets of information rather than heavy blocks, maintaining an overall sense of efficiency and clarity.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Inkwell | `#221f1c` | `--color-inkwell` | Primary text, darkest surface for filled buttons, selected navigation items |
| Canvas White | `#f5f5f5` | `--color-canvas-white` | Page background, main card surfaces, input fields, subtle button fills |
| Subtle Gray | `#797267` | `--color-subtle-gray` | Secondary text, disabled states, icon strokes, subtle borders |
| Deep Gray | `#575452` | `--color-deep-gray` | Muted text, navigation hover states |
| Lightest Gray | `#ababab` | `--color-lightest-gray` | Placeholder text, subtle dividers |
| Border Gray | `#c4c4c4` | `--color-border-gray` | Hairline borders, subtle shadows |
| Midnight Blue | `linear-gradient(to right in oklab, rgb(81, 139, 219) 0%, rgb(54, 186, 184) 100%)` | `--color-midnight-blue` | Accent for active states, primary actions, focused elements, and decorative icons. This color signifies interaction and functionality; Used for background hero sections and major visual statements, blending a cool blue into a vibrant teal |
| Teal Burst | `#36bab8` | `--color-teal-burst` | Teal text accent for links, tags, and emphasized short phrases |
| Forest Green | `#1a3a12` | `--color-forest-green` | Green outline accent for tags, dividers, and focused UI edges. |
| Lavender Haze | `#bf89cd` | `--color-lavender-haze` | Decorative accent for icons and subtle backgrounds, adding visual variety without being primary |
| Sunset Red | `#ed6d68` | `--color-sunset-red` | Accent for icons and subtle backgrounds, providing a warm, energetic punctuation |
| Honey Gold | `#e5a057` | `--color-honey-gold` | Accent for icons and subtle backgrounds, providing a warm, informative tone |
| Lime Squeeze | `#7efa55` | `--color-lime-squeeze` | Green wash for highlight backgrounds, decorative bands, and soft emphasis behind content. Use as a supporting accent, not as a status color |
| Deep Olive | `#3a6b2a` | `--color-deep-olive` | Green wash for highlight backgrounds, decorative bands, and soft emphasis behind content. Use as a supporting accent, not as a status color |

## Tokens — Typography

### haffer — Primary brand typeface for all headings, body text, and UI elements. Its strong presence with varying weights (from 400 for body to 900 for bold statements) defines the textual voice of the product. The tight letter spacing on larger sizes adds to its modern, direct appeal. · `--font-haffer`
- **Substitute:** Inter
- **Weights:** 400, 500, 600, 700, 900
- **Sizes:** 8px, 9px, 10px, 11px, 12px, 14px, 16px, 18px, 20px, 24px, 96px
- **Line height:** 1.00, 1.25, 1.33, 1.40, 1.43, 1.50, 1.56, 1.63
- **Letter spacing:** -0.025em for large headings (96px), 0.1em for small uppercase text.
- **Role:** Primary brand typeface for all headings, body text, and UI elements. Its strong presence with varying weights (from 400 for body to 900 for bold statements) defines the textual voice of the product. The tight letter spacing on larger sizes adds to its modern, direct appeal.

### ui-monospace — Monospaced font used for code snippets, time stamps, and any context requiring fixed-width characters or a 'developer' aesthetic. Its crispness contrasts with the primary typeface. · `--font-ui-monospace`
- **Substitute:** JetBrains Mono
- **Weights:** 400, 500
- **Sizes:** 8px, 14px, 16px
- **Line height:** 1.43, 1.50, 1.71
- **Letter spacing:** normal
- **Role:** Monospaced font used for code snippets, time stamps, and any context requiring fixed-width characters or a 'developer' aesthetic. Its crispness contrasts with the primary typeface.

### perfectlyNineties — Decorative display font used selectively for highly stylized headings. Its wider letter spacing and unique character feel provide a distinct visual break, used sparingly for emphasis. · `--font-perfectlynineties`
- **Substitute:** Georgia
- **Weights:** 400, 700, 800, 900
- **Sizes:** 14px, 24px, 30px, 36px, 48px, 72px
- **Line height:** 1.00, 1.20, 1.25
- **Letter spacing:** 0.02em
- **Role:** Decorative display font used selectively for highly stylized headings. Its wider letter spacing and unique character feel provide a distinct visual break, used sparingly for emphasis.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body | 14px | 1.63 | — | `--text-body` |
| subheading | 18px | 1.5 | — | `--text-subheading` |
| heading | 24px | 1.33 | — | `--text-heading` |
| heading-lg | 48px | 1.25 | -0.96px | `--text-heading-lg` |
| display | 96px | 1 | -2.4px | `--text-display` |

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
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 52 | 52px | `--spacing-52` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 96 | 96px | `--spacing-96` |
| 128 | 128px | `--spacing-128` |
| 192 | 192px | `--spacing-192` |
| 240 | 240px | `--spacing-240` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 18px |
| inputs | 10px |
| buttons | 8px |
| default | 8px |
| taglike | 14px |
| circular | 9999px |
| smallElements | 4px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(0, 0, 0, 0.1) 0px 1px 3px 0px, rgba(0, 0, 0, 0.1) 0p...` | `--shadow-subtle` |
| subtle-2 | `oklab(0.241527 0.00279061 0.00670661 / 0.065) 0px 0px 0px...` | `--shadow-subtle-2` |
| subtle-3 | `rgba(0, 0, 0, 0.08) 0px 1px 2px 0px` | `--shadow-subtle-3` |
| md | `rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1)...` | `--shadow-md` |
| subtle-4 | `rgba(0, 0, 0, 0.2) 0px -2px 0px 0px inset` | `--shadow-subtle-4` |
| md-2 | `oklab(0 0 0 / 0.065) 0px 10px 15px -3px, oklab(0 0 0 / 0....` | `--shadow-md-2` |
| sm | `rgba(0, 0, 0, 0.1) 0px 4px 6px -1px, rgba(0, 0, 0, 0.1) 0...` | `--shadow-sm` |
| subtle-5 | `rgba(0, 0, 0, 0.15) 0px 1px 2px 0px` | `--shadow-subtle-5` |
| subtle-6 | `rgb(212, 212, 212) 0px 1px 0px 0px, rgb(208, 208, 208) 0p...` | `--shadow-subtle-6` |
| subtle-7 | `oklab(0.241527 0.00279061 0.00670661 / 0.1) 0px 0px 0px 1...` | `--shadow-subtle-7` |
| xl | `rgba(0, 0, 0, 0.1) 0px 20px 25px -5px, rgba(0, 0, 0, 0.1)...` | `--shadow-xl` |
| subtle-8 | `rgba(0, 0, 0, 0.15) 0px 1px 2px 0px, rgba(0, 0, 0, 0.04) ...` | `--shadow-subtle-8` |
| subtle-9 | `oklab(0 0 0 / 0.065) 0px 1px 3px 0px, oklab(0 0 0 / 0.065...` | `--shadow-subtle-9` |
| xl-2 | `oklab(0 0 0 / 0.15) 0px 25px 50px -12px` | `--shadow-xl-2` |

### Layout

- **Section gap:** 32px
- **Card padding:** 12px
- **Element gap:** 8px

## Components

### Ghost Button
**Role:** Secondary action button with minimal visual hierarchy.

Background: transparent (rgba(0, 0, 0, 0)), Text: Subtle Gray, Border: rgba(0, 0, 0, 0.08) 1px solid, Radius: 8px, Padding: 4px vertical, 12px horizontal.

### Icon Button
**Role:** Compact button primarily for icons, often in navigation context.

Background: transparent (rgba(0, 0, 0, 0)), Text: Inkwell, Border: rgba(0, 0, 0, 0.08) 1px solid, Radius: 0px (often indicating a more structural element like tabs), Padding: 16px vertical, 0px horizontal.

### Primary Filled Button
**Role:** Prominent action button, main call-to-action.

Background: Inkwell (#221f1c), Text: Canvas White (#f5f5f5), Border: rgba(0, 0, 0, 0.08) 1px solid, Radius: 10px, Padding: variable horizontal (e.g., 24px) with no explicit vertical padding (content drives height).

### Subtle Filled Button
**Role:** Tertiary action, less emphasis than primary but more than ghost.

Background: rgba(0, 0, 0, 0.05), Text: Inkwell, Border: rgba(0, 0, 0, 0.08) 1px solid, Radius: 8px, Padding: 6px vertical, 12px horizontal.

### Elevated Card
**Role:** Main content containers with significant visual separation.

Background: Canvas White (#f5f5f5), Radius: 18px, Box Shadow: rgba(0, 0, 0, 0.1) 0px 1px 3px 0px, rgba(0, 0, 0, 0.1) 0px 1px 2px -1px with a thin border-like shadow oklab(0.241527 0.00279061 0.00670661 / 0.065) 0px 0px 0px 1px, Padding: 0px.

### Nested Card
**Role:** Secondary content containers, slightly less prominent than main cards.

Background: Canvas White (#f5f5f5), Radius: 14px, Box Shadow: rgba(0, 0, 0, 0.1) 0px 1px 3px 0px, rgba(0, 0, 0, 0.1) 0px 1px 2px -1px and subtle border-like shadow, Padding: 16px.

### Subtle Card
**Role:** Minor content groupings, minimal visual weight.

Background: #f5f5f5, Radius: 14px, Box Shadow: rgba(0, 0, 0, 0.1) 0px 1px 3px 0px, rgba(0, 0, 0, 0.1) 0px 1px 2px -1px, Padding: 10px vertical, 12px horizontal.

### Text Input
**Role:** Standard user input field.

Background: Canvas White (#f5f5f5), Text: Inkwell, Border: rgba(0, 0, 0, 0.08) 1px solid (top border), Radius: 10px, Placeholder color: Lightest Gray (#ababab), Padding: 0px vertical, 20px horizontal.

## Do's and Don'ts

### Do
- Prioritize Canvas White (#f5f5f5) as the default background for most surfaces, creating a bright and open feel.
- Use Inkwell (#221f1c) for all primary text and calls-to-action on light backgrounds to ensure high contrast and legibility.
- Apply a subtle box shadow stack with rgba(0, 0, 0, 0.1) 0px 1px 3px 0px, rgba(0, 0, 0, 0.1) 0px 1px 2px -1px and oklab(0.241527 0.00279061 0.00670661 / 0.065) 0px 0px 0px 1px for cards and elevated elements, rather than heavy, dramatic shadows.
- Round corners with 8px for most interactive elements, 18px for large cards, and 14px for nested or smaller cards, to maintain a consistent soft aesthetic.
- Leverage Midnight Blue (#518bdb) as the primary accent color for active states, link highlights, and key interactive elements, making actions feel clear and distinct.
- Use haffer at font-weight 400 for body text and 600-700 for headings, ensuring consistent brand typography across the interface.
- Employ consistent 8px element gaps and 32px section gaps to create a balanced and readable content hierarchy.

### Don't
- Avoid using highly saturated colors for large background areas; reserve them for small, functional accents or status indicators.
- Do not use hard, sharp angles; maintain the rounded aesthetic with default 8px, 14px, or 18px radii.
- Refrain from using bold typefaces for body copy; stick to haffer weights 400-500 for readability.
- Avoid deep, dark backgrounds for primary content areas; the system relies on a light canvas model.
- Do not introduce new shadow patterns; adhere to the defined subtle elevation styles.
- Resist using multiple distinct brand colors for primary actions; Midnight Blue (#518bdb) should be the singular vibrant accent for critical interactions.
- Do not deviate from the defined spacing scale; maintain the compact density with 8px element gaps and 32px section gaps.

## Elevation

- **Card:** `rgba(0, 0, 0, 0.1) 0px 1px 3px 0px, rgba(0, 0, 0, 0.1) 0px 1px 2px -1px`
- **Card with subtle border:** `oklab(0.241527 0.00279061 0.00670661 / 0.065) 0px 0px 0px 1px, rgba(0, 0, 0, 0.1) 0px 1px 3px 0px, rgba(0, 0, 0, 0.1) 0px 1px 2px -1px`
- **Header/Modal:** `rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1) 0px 4px 6px -4px`
- **Inset button focus:** `rgba(0, 0, 0, 0.2) 0px -2px 0px 0px inset`

## Imagery

Imagery on Micro is balanced between functional product screenshots and abstract, conceptual illustrations. Product visuals are presented as clean, contained UI crops on light surfaces, often showcasing app features within a white or near-white background. Illustrations are abstract, linear, and geometric, using brand accent colors for highlights rather than being fully colored. Icons are primarily outlined or filled with a fine stroke, often monochrome or using a single accent color like Midnight Blue. The overall density of imagery is moderate, interspersing visuals to explain content rather than decorate, maintaining a text-dominant but visually supported experience.

## Layout

The page layout is primarily full-bleed with content contained within a horizontal-max-width. The hero section is full-bleed, using a vibrant linear blue-to-teal gradient background, with a centered headline and compact call-to-action buttons. Subsequent sections alternate between full-width content blocks and those with implicit padding, often featuring two-column layouts with text and descriptive visuals. Content is typically centered vertically within sections, and feature lists or data visualizations are presented in card grids, maintaining consistent vertical spacing. The navigation is a sticky top bar with minimal branding, aligning interactive elements to the right. The overall impression is structured and spacious, guiding the user through distinct content modules.

## Agent Prompt Guide

Quick Color Reference:
- text: #221f1c
- background: #f5f5f5
- border: rgba(0, 0, 0, 0.08)
- accent: #518bdb
- primary action: #518bdb (filled action)

Example Component Prompts:
- Create a hero section with the Sky Sea Gradient background (#518bdb), a centered heading 'One place for work that works for you' using haffer, 96px, weight 700, #221f1c, letter-spacing -2.4px, and a Primary Filled Button 'Sign up' with background #221f1c, text #f5f5f5, 10px radius.
- Generate a content card: background Canvas White (#f5f5f5), 18px radius, with the subtle card shadow. Inside, include a subheading 'Good morning, Sarah' using haffer, 24px, weight 600, #221f1c, and a Text Input field with background Canvas White, 10px radius, rgba(0, 0, 0, 0.08) top border.
- Create a ghost button: 'Watch the launch video' with transparent background, text Subtle Gray (#797267), Border Gray (#c4c4c4) 1px solid, and 8px radius, padding 4px vertical, 12px horizontal.

## Similar Brands

- **Linear** — Shares a compact, minimal UI with subtle elevation and a strong focus on typography and intentional use of accent colors for interaction.
- **Amplitude** — Similar approach to clean, white backgrounds for product interfaces, with dark, precise typography and pops of color for data visualization and calls-to-action.
- **Superhuman** — Exhibits a streamlined, high-density interface with a deliberate color palette and fine typographic details for a fast, efficient user experience.
- **Notion** — Employs a flexible, card-based layout on a light canvas, using minimal borders and shadows to define interactive areas, and a crisp, functional typeface.
- **Amie** — Features a light, productivity-centric aesthetic with an emphasis on clean surfaces, thin dividers, and a singular, vibrant accent color to highlight interactive elements.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-inkwell: #221f1c;
  --color-canvas-white: #f5f5f5;
  --color-subtle-gray: #797267;
  --color-deep-gray: #575452;
  --color-lightest-gray: #ababab;
  --color-border-gray: #c4c4c4;
  --color-midnight-blue: #518bdb;
  --gradient-midnight-blue: linear-gradient(to right in oklab, rgb(81, 139, 219) 0%, rgb(54, 186, 184) 100%);
  --color-teal-burst: #36bab8;
  --color-forest-green: #1a3a12;
  --color-lavender-haze: #bf89cd;
  --color-sunset-red: #ed6d68;
  --color-honey-gold: #e5a057;
  --color-lime-squeeze: #7efa55;
  --color-deep-olive: #3a6b2a;

  /* Typography — Font Families */
  --font-haffer: 'haffer', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ui-monospace: 'ui-monospace', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-perfectlynineties: 'perfectlyNineties', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 14px;
  --leading-body: 1.63;
  --text-subheading: 18px;
  --leading-subheading: 1.5;
  --text-heading: 24px;
  --leading-heading: 1.33;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.25;
  --tracking-heading-lg: -0.96px;
  --text-display: 96px;
  --leading-display: 1;
  --tracking-display: -2.4px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;
  --font-weight-extrabold: 800;
  --font-weight-black: 900;

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
  --spacing-52: 52px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-128: 128px;
  --spacing-192: 192px;
  --spacing-240: 240px;

  /* Layout */
  --section-gap: 32px;
  --card-padding: 12px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 14px;
  --radius-2xl: 18px;
  --radius-2xl-2: 22px;
  --radius-3xl: 32px;
  --radius-3xl-2: 40px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-cards: 18px;
  --radius-inputs: 10px;
  --radius-buttons: 8px;
  --radius-default: 8px;
  --radius-taglike: 14px;
  --radius-circular: 9999px;
  --radius-smallelements: 4px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.1) 0px 1px 3px 0px, rgba(0, 0, 0, 0.1) 0px 1px 2px -1px;
  --shadow-subtle-2: oklab(0.241527 0.00279061 0.00670661 / 0.065) 0px 0px 0px 1px, rgba(0, 0, 0, 0.1) 0px 1px 3px 0px, rgba(0, 0, 0, 0.1) 0px 1px 2px -1px;
  --shadow-subtle-3: rgba(0, 0, 0, 0.08) 0px 1px 2px 0px;
  --shadow-md: rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1) 0px 4px 6px -4px;
  --shadow-subtle-4: rgba(0, 0, 0, 0.2) 0px -2px 0px 0px inset;
  --shadow-md-2: oklab(0 0 0 / 0.065) 0px 10px 15px -3px, oklab(0 0 0 / 0.065) 0px 4px 6px -4px;
  --shadow-sm: rgba(0, 0, 0, 0.1) 0px 4px 6px -1px, rgba(0, 0, 0, 0.1) 0px 2px 4px -2px;
  --shadow-subtle-5: rgba(0, 0, 0, 0.15) 0px 1px 2px 0px;
  --shadow-subtle-6: rgb(212, 212, 212) 0px 1px 0px 0px, rgb(208, 208, 208) 0px 4px 0px 0px, rgba(0, 0, 0, 0.1) 0px 4px 4px 0px, rgba(0, 0, 0, 0.12) 0px 8px 16px -4px;
  --shadow-subtle-7: oklab(0.241527 0.00279061 0.00670661 / 0.1) 0px 0px 0px 1px, oklab(0 0 0 / 0.25) 0px 25px 50px -12px;
  --shadow-xl: rgba(0, 0, 0, 0.1) 0px 20px 25px -5px, rgba(0, 0, 0, 0.1) 0px 8px 10px -6px;
  --shadow-subtle-8: rgba(0, 0, 0, 0.15) 0px 1px 2px 0px, rgba(0, 0, 0, 0.04) 0px 0px 0px 3px;
  --shadow-subtle-9: oklab(0 0 0 / 0.065) 0px 1px 3px 0px, oklab(0 0 0 / 0.065) 0px 1px 2px -1px;
  --shadow-xl-2: oklab(0 0 0 / 0.15) 0px 25px 50px -12px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-inkwell: #221f1c;
  --color-canvas-white: #f5f5f5;
  --color-subtle-gray: #797267;
  --color-deep-gray: #575452;
  --color-lightest-gray: #ababab;
  --color-border-gray: #c4c4c4;
  --color-midnight-blue: #518bdb;
  --color-teal-burst: #36bab8;
  --color-forest-green: #1a3a12;
  --color-lavender-haze: #bf89cd;
  --color-sunset-red: #ed6d68;
  --color-honey-gold: #e5a057;
  --color-lime-squeeze: #7efa55;
  --color-deep-olive: #3a6b2a;

  /* Typography */
  --font-haffer: 'haffer', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ui-monospace: 'ui-monospace', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-perfectlynineties: 'perfectlyNineties', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 14px;
  --leading-body: 1.63;
  --text-subheading: 18px;
  --leading-subheading: 1.5;
  --text-heading: 24px;
  --leading-heading: 1.33;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.25;
  --tracking-heading-lg: -0.96px;
  --text-display: 96px;
  --leading-display: 1;
  --tracking-display: -2.4px;

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
  --spacing-52: 52px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-128: 128px;
  --spacing-192: 192px;
  --spacing-240: 240px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 14px;
  --radius-2xl: 18px;
  --radius-2xl-2: 22px;
  --radius-3xl: 32px;
  --radius-3xl-2: 40px;
  --radius-full: 9999px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.1) 0px 1px 3px 0px, rgba(0, 0, 0, 0.1) 0px 1px 2px -1px;
  --shadow-subtle-2: oklab(0.241527 0.00279061 0.00670661 / 0.065) 0px 0px 0px 1px, rgba(0, 0, 0, 0.1) 0px 1px 3px 0px, rgba(0, 0, 0, 0.1) 0px 1px 2px -1px;
  --shadow-subtle-3: rgba(0, 0, 0, 0.08) 0px 1px 2px 0px;
  --shadow-md: rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1) 0px 4px 6px -4px;
  --shadow-subtle-4: rgba(0, 0, 0, 0.2) 0px -2px 0px 0px inset;
  --shadow-md-2: oklab(0 0 0 / 0.065) 0px 10px 15px -3px, oklab(0 0 0 / 0.065) 0px 4px 6px -4px;
  --shadow-sm: rgba(0, 0, 0, 0.1) 0px 4px 6px -1px, rgba(0, 0, 0, 0.1) 0px 2px 4px -2px;
  --shadow-subtle-5: rgba(0, 0, 0, 0.15) 0px 1px 2px 0px;
  --shadow-subtle-6: rgb(212, 212, 212) 0px 1px 0px 0px, rgb(208, 208, 208) 0px 4px 0px 0px, rgba(0, 0, 0, 0.1) 0px 4px 4px 0px, rgba(0, 0, 0, 0.12) 0px 8px 16px -4px;
  --shadow-subtle-7: oklab(0.241527 0.00279061 0.00670661 / 0.1) 0px 0px 0px 1px, oklab(0 0 0 / 0.25) 0px 25px 50px -12px;
  --shadow-xl: rgba(0, 0, 0, 0.1) 0px 20px 25px -5px, rgba(0, 0, 0, 0.1) 0px 8px 10px -6px;
  --shadow-subtle-8: rgba(0, 0, 0, 0.15) 0px 1px 2px 0px, rgba(0, 0, 0, 0.04) 0px 0px 0px 3px;
  --shadow-subtle-9: oklab(0 0 0 / 0.065) 0px 1px 3px 0px, oklab(0 0 0 / 0.065) 0px 1px 2px -1px;
  --shadow-xl-2: oklab(0 0 0 / 0.15) 0px 25px 50px -12px;
}
```

# Flatfile — Style Reference
> Architectural blueprint on white marble

**Theme:** light

Flatfile orchestrates a sophisticated, document-centric experience with a stark, almost architectural monochrome palette. Typography leads the eye with precise tracking, while a single, muted green accent punctuate interactive elements, suggesting activation and growth within a data-heavy context. Surfaces are generally flat and unadorned, emphasizing content over chrome, with rounded elements conveying approachability within an otherwise serious interface.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#090b2b` | `--color-midnight-ink` | Primary text, deep backgrounds for contrast, prominent headings |
| Forest Bloom | `#0e1301` | `--color-forest-bloom` | Accent text on light backgrounds, used for button text against a muted green button. It offers a subtle, organic contrast |
| Growth Sprout | `#e5ebd3` | `--color-growth-sprout` | Muted background for accent buttons, providing a gentle highlight for calls to action |
| Paper White | `#ffffff` | `--color-paper-white` | Page backgrounds, card surfaces, text on dark elements, primary action buttons |
| Ghost Gray | `#e5e7eb` | `--color-ghost-gray` | Subtle borders, dividers, ghost button borders, and light background accents |
| Canvas Fog | `#f8f8f8` | `--color-canvas-fog` | Secondary surface background, elevated content areas, subtle card backgrounds |
| Obsidian Black | `#1b1b1e` | `--color-obsidian-black` | Dark button backgrounds, primary navigation backgrounds, and prominent headings on dark surfaces |
| Ash Slate | `#808080` | `--color-ash-slate` | Muted body text, secondary icons, subtle borders, and ghost button text |
| Steel Gray | `#aaaaaa` | `--color-steel-gray` | Helper text, secondary navigation items, less prominent body text |
| Silver Mist | `#d7d7d7` | `--color-silver-mist` | Hairline borders, dividers, input outlines, and card edges on light surfaces. Do not promote it to the primary CTA color |
| Anchor Link | `#8c8c8c` | `--color-anchor-link` | Default link text |

## Tokens — Typography

### FlatfileDiatypeVariable — General interface text, navigation items, button labels. Its variable nature suggests flexibility, but currently used sparingly. · `--font-flatfilediatypevariable`
- **Substitute:** Inter
- **Weights:** 400, 500
- **Sizes:** 16px
- **Line height:** 1.50
- **Letter spacing:** normal
- **Role:** General interface text, navigation items, button labels. Its variable nature suggests flexibility, but currently used sparingly.

### FlatfileDiatype — The primary workhorse for body text, headings, and functional UI elements. The precise, often tight, letter-spacing across different sizes commands attention and conveys density. · `--font-flatfilediatype`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 12px, 14px, 16px, 22px, 38px, 60px
- **Line height:** 1.00, 1.18, 1.42, 1.43, 1.50
- **Letter spacing:** -0.512px at 16px, -0.42px at 14px, -1.216px at 38px, -1.8px at 60px
- **Role:** The primary workhorse for body text, headings, and functional UI elements. The precise, often tight, letter-spacing across different sizes commands attention and conveys density.

### SourceSerif4 — Used for specific large headings, offering a touch of classic sophistication amidst the modern sans-serifs, providing textural contrast. · `--font-sourceserif4`
- **Substitute:** Source Serif Pro
- **Weights:** 400
- **Sizes:** 38px
- **Line height:** 1.00
- **Letter spacing:** -1.216px at 38px
- **Role:** Used for specific large headings, offering a touch of classic sophistication amidst the modern sans-serifs, providing textural contrast.

### Sharp Grotesk — A distinct, bold-display typeface for impactful headings, breaking the clean linearity of Diatype with a more assertive presence and tight tracking. · `--font-sharp-grotesk`
- **Substitute:** Inter Bold
- **Weights:** 500
- **Sizes:** 26px
- **Line height:** 1.42
- **Letter spacing:** -0.26px at 26px
- **Role:** A distinct, bold-display typeface for impactful headings, breaking the clean linearity of Diatype with a more assertive presence and tight tracking.

### Booton — Booton — detected in extracted data but not described by AI · `--font-booton`
- **Weights:** 469
- **Sizes:** 16px
- **Line height:** 1.5
- **Letter spacing:** -0.005
- **Role:** Booton — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.5 | -0.42px | `--text-caption` |
| body | 16px | 1.5 | -0.512px | `--text-body` |
| subheading | 22px | 1.43 | -0.484px | `--text-subheading` |
| heading | 26px | 1.42 | -0.26px | `--text-heading` |
| heading-lg | 38px | 1 | -1.216px | `--text-heading-lg` |
| display | 60px | 1 | -1.8px | `--text-display` |

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
| 64 | 64px | `--spacing-64` |
| 88 | 88px | `--spacing-88` |
| 112 | 112px | `--spacing-112` |
| 120 | 120px | `--spacing-120` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 12px |
| cards | 0px |
| buttons | 99px |
| navigation | 999px |

### Layout

- **Section gap:** 64px
- **Card padding:** 32px
- **Element gap:** 16px

## Components

### Primary Accent Button
**Role:** Call to action button for key conversions.

Background: Growth Sprout (#e5ebd3), Text: Forest Bloom (#0e1301), Border Radius: 12px, Padding: 9px vertical, 14px horizontal. Uses FlatfileDiatype font.

### Primary Dark Button
**Role:** Reinforced action button on light backgrounds.

Background: Obsidian Black (#1b1b1e), Text: Paper White (#ffffff), Border Radius: 99px, Padding: 12px vertical, 24px horizontal. Uses FlatfileDiatype font.

### Ghost Bordered Button
**Role:** Secondary action or navigational link button.

Background: transparent, Text: Ash Slate (#808080), Border: 1px solid Silver Mist (#d7d7d7), Border Radius: 99px, Padding: 12px vertical, 24px horizontal. Uses FlatfileDiatype font.

### Navigation Link
**Role:** Top-level navigation items.

Background: transparent, Text: Ash Slate (#808080), No visible border. Padding: 24px vertical, 16px horizontal. Uses FlatfileDiatypeVariable font.

### Default Card
**Role:** Container for blocks of content, testimonials, or features.

Background: Canvas Fog (#f8f8f8), Border Radius: 0px, no shadow. Padding: 32px. Uses FlatfileDiatype for text. Text color will be Midnight Ink (#090b2b).

### Segmented Control Tab
**Role:** Used for filtering or section navigation.

Selected state: button with Obsidian Black (#1b1b1e) background, Paper White (#ffffff) text, 99px radius, 12px vertical, 24px horizontal padding. Unselected state: ghost button with transparent background, Ash Slate (#808080) text, 99px radius, 12px vertical, 24px horizontal padding and Silver Mist (#d7d7d7) border.

## Do's and Don'ts

### Do
- Prioritize FlatfileDiatype for all textual content, ensuring tight letter-spacing for headings and body text to convey precision.
- Use Midnight Ink (#090b2b) for primary headings and text against light backgrounds, maintaining a high contrast ratio.
- Employ Ghost Gray (#e5e7eb) for all hairline dividers, neutral borders, and subtle background separations.
- Accent actions sparingly with Growth Sprout (#e5ebd3) for button backgrounds with Forest Bloom (#0e1301) text; this is the sole chromatic accent.
- Apply a 99px border-radius to all interactive buttons and navigation links for a consistent soft, yet defined, action cue.
- Maintain a clear visual hierarchy with flat backgrounds and minimal shadows, allowing typography and content structure to drive attention.
- Use a default padding of 32px for cards and significant content blocks to ensure comfortable spacing within containers.

### Don't
- Avoid generic 'modern' or 'clean' text attributes; instead, focus on the specific precise tracking and monochromatic color scheme.
- Do not introduce new chromatic colors beyond the Growth Sprout (#e5ebd3) and Forest Bloom (#0e1301) pairing; maintain the stark brand identity.
- Do not use box-shadows or elevation for cards; surfaces should remain flat to emphasize content structure.
- Avoid using inconsistent border radii; adhere strictly to 0px for content cards and 99px/12px for interactive elements.
- Do not use generic system fonts for branding or UI elements; rely on FlatfileDiatype, Sharp Grotesk, or SourceSerif4 for brand consistency.
- Do not break the established spacing rhythm; ensure elements maintain 16px element gaps and sections use 64px vertical spacing.
- Do not introduce decorative gradients; the design relies on monochromatic surfaces and subtle color shifts.

## Imagery

Imagery is functional and product-focused, featuring abstract, layered digital documents and interfaces that showcase data flow and organization. These are typically isolated or presented with a soft, blurred background to keep focus. Iconography is primarily monochromatic, using a fine stroke weight, and serves to delineate or highlight features rather than decorate. The overall density of imagery is balanced, supporting textual explanations without overwhelming the UI, emphasizing an explanatory and showcasing role.

## Layout

The page primarily employs a max-width contained layout, likely around 1200px, creating defined content areas on a white canvas. The hero section often features a centered headline over a subtly blurred, evocative background, setting a serious but approachable tone. Sections alternate between full-width blurred background images and crisp white or light gray content blocks. Content arrangement frequently uses centered stacks for headlines and subtext, or left-aligned text beside right-aligned visuals/cards, fostering a clear reading flow. Card grids are used for features and testimonials, typically in 2-3 column layouts. Navigation is a persistent top bar with a left-aligned logo and right-aligned links and action buttons, including a distinctive 'Book a demo' button.

## Agent Prompt Guide

### Quick Color Reference
- text: #090b2b
- background: #ffffff
- border: #e5e7eb
- accent: #e5ebd3
- primary action: no distinct CTA color

### 3-5 Example Component Prompts
- Create a testimonial card: Canvas Fog background, 0px radius, 32px padding on all sides. Headline in FlatfileDiatype 22px, #090b2b, lineHeight 1.43, letterSpacing -0.484px. Body text in FlatfileDiatype 16px, #090b2b, lineHeight 1.5, letterSpacing -0.512px. Add a Ghost Bordered Button with Ash Slate text to the bottom.
No distinct primary action color was observed; use the extracted neutral button treatments instead of inventing a filled CTA color.
- Create a top navigation bar: Obsidian Black (#1b1b1e) background, fixed to top. Navigation links using FlatfileDiatypeVariable 16px, Ash Slate (#808080), 24px vertical, 16px horizontal padding. Include an Obsidian Black button with Paper White text and 99px radius for 'Book a demo'.

## Similar Brands

- **Airtable** — Monochromatic interface with a single, clear accent color used functionally, and a focus on data organization.
- **Notion** — Clean, content-focused UI with an emphasis on typography, flat surfaces, and a minimalist aesthetic for productivity tools.
- **Linear** — Precise typography, high-contrast dark text on light backgrounds, and functional use of color only for interactive states or specific highlights.
- **Segment** — Technical B2B SaaS with structured layouts, crisp edges, and a reliance on text hierarchy over decorative elements.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #090b2b;
  --color-forest-bloom: #0e1301;
  --color-growth-sprout: #e5ebd3;
  --color-paper-white: #ffffff;
  --color-ghost-gray: #e5e7eb;
  --color-canvas-fog: #f8f8f8;
  --color-obsidian-black: #1b1b1e;
  --color-ash-slate: #808080;
  --color-steel-gray: #aaaaaa;
  --color-silver-mist: #d7d7d7;
  --color-anchor-link: #8c8c8c;

  /* Typography — Font Families */
  --font-flatfilediatypevariable: 'FlatfileDiatypeVariable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-flatfilediatype: 'FlatfileDiatype', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sourceserif4: 'SourceSerif4', ui-serif, Georgia, Cambria, "Times New Roman", Times, serif;
  --font-sharp-grotesk: 'Sharp Grotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-booton: 'Booton', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: -0.42px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.512px;
  --text-subheading: 22px;
  --leading-subheading: 1.43;
  --tracking-subheading: -0.484px;
  --text-heading: 26px;
  --leading-heading: 1.42;
  --tracking-heading: -0.26px;
  --text-heading-lg: 38px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -1.216px;
  --text-display: 60px;
  --leading-display: 1;
  --tracking-display: -1.8px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-w469: 469;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-64: 64px;
  --spacing-88: 88px;
  --spacing-112: 112px;
  --spacing-120: 120px;

  /* Layout */
  --section-gap: 64px;
  --card-padding: 32px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-xl: 12px;
  --radius-full: 99px;
  --radius-full-2: 999px;

  /* Named Radii */
  --radius-tags: 12px;
  --radius-cards: 0px;
  --radius-buttons: 99px;
  --radius-navigation: 999px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #090b2b;
  --color-forest-bloom: #0e1301;
  --color-growth-sprout: #e5ebd3;
  --color-paper-white: #ffffff;
  --color-ghost-gray: #e5e7eb;
  --color-canvas-fog: #f8f8f8;
  --color-obsidian-black: #1b1b1e;
  --color-ash-slate: #808080;
  --color-steel-gray: #aaaaaa;
  --color-silver-mist: #d7d7d7;
  --color-anchor-link: #8c8c8c;

  /* Typography */
  --font-flatfilediatypevariable: 'FlatfileDiatypeVariable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-flatfilediatype: 'FlatfileDiatype', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sourceserif4: 'SourceSerif4', ui-serif, Georgia, Cambria, "Times New Roman", Times, serif;
  --font-sharp-grotesk: 'Sharp Grotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-booton: 'Booton', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: -0.42px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.512px;
  --text-subheading: 22px;
  --leading-subheading: 1.43;
  --tracking-subheading: -0.484px;
  --text-heading: 26px;
  --leading-heading: 1.42;
  --tracking-heading: -0.26px;
  --text-heading-lg: 38px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -1.216px;
  --text-display: 60px;
  --leading-display: 1;
  --tracking-display: -1.8px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-64: 64px;
  --spacing-88: 88px;
  --spacing-112: 112px;
  --spacing-120: 120px;

  /* Border Radius */
  --radius-xl: 12px;
  --radius-full: 99px;
  --radius-full-2: 999px;
}
```

# Metaview — Style Reference
> Midnight Command Center

**Theme:** dark

Metaview employs a high-contrast dark aesthetic that feels like a command center: deep black backgrounds, subtly glowing dark surfaces, and text in crisp white or muted gray. A singular vivid green piercing through the darkness emphasizes key interactive elements and creates an immediate sense of action. Typography is clean and functional, with ample spacing creating a sense of calm authority within the otherwise intense color scheme.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Void Black | `#000000` | `--color-void-black` | Page backgrounds, primary text for light elements, major borders providing structure |
| Ghost White | `#ffffff` | `--color-ghost-white` | Primary text on dark backgrounds, interactive elements, button backgrounds, and card surfaces for contrast |
| Carbon | `#161818` | `--color-carbon` | Subtle background for elevated dark cards and secondary content blocks |
| Deep Space | `#0a1a14` | `--color-deep-space` | Darker card backgrounds, slightly recessed elements within the dark UI |
| Twilight Slate | `#01051b` | `--color-twilight-slate` | Muted text, secondary button borders, and decorative icon strokes. This dark blue-gray acts as a subtle accent against the black |
| Ash Gray | `#5e6262` | `--color-ash-gray` | Helper text, less prominent body copy, and secondary meta information |
| Slate Border | `#828282` | `--color-slate-border` | Subtle borders and dividers within the dark interface |
| Cloud Gray | `#d9d9d9` | `--color-cloud-gray` | Hairline borders, dividers, input outlines, and card edges on light surfaces. Do not promote it to the primary CTA color |
| Mint Glare | `#7affb4` | `--color-mint-glare` | Primary call-to-action button backgrounds and active state indicators—this vivid green is the sole splash of strong color |
| Soft Mint | `#e3ffef` | `--color-soft-mint` | Light highlight for specific text elements or subtle decorative borders |
| Dark Forest | `#000a06` | `--color-dark-forest` | Deep background colors or subtle textual cues in a near-black tone |
| Subtle Green | `#0a2119` | `--color-subtle-green` | Secondary body text, navigation labels, and subdued headings. Do not promote it to the primary CTA color |
| Digital Glow Radial Gradient | `radial-gradient(circle, rgba(0, 100, 70, 0.4) 0%, rgba(0, 60, 40, 0.2) 30%, rgba(0, 30, 20, 0.08) 55%, rgba(0, 0, 0, 0) 75%)` | `--color-digital-glow-radial-gradient` | Subtle background element, creating a diffused green light effect |
| Digital Glow Linear Gradient | `linear-gradient(rgb(15, 58, 43) 0%, rgb(0, 10, 7) 100%)` | `--color-digital-glow-linear-gradient` | Background gradient often used at section breaks or for subtle depth |

## Tokens — Typography

### Euclid Circular A — Primary brand typeface for all headings, body text, and UI elements. Its clean, geometric forms maintain clarity and efficiency, reinforcing the AI-driven identity. The variable letter-spacing provides visual precision at different sizes. · `--font-euclid-circular-a`
- **Substitute:** system-ui, sans-serif
- **Weights:** 300, 400, 500, 700
- **Sizes:** 12px, 14px, 15px, 16px, 18px, 20px, 22px, 28px, 36px, 48px, 68px, 72px
- **Line height:** 1.00, 1.04, 1.10, 1.12, 1.16, 1.20, 1.30, 1.34, 1.42, 1.48, 1.50, 1.60
- **Letter spacing:** -0.06em at 72px, -0.04em at 48px, -0.03em at 36px, -0.02em at 28px, -0.01em at 22px, 0.01em at 12px
- **Role:** Primary brand typeface for all headings, body text, and UI elements. Its clean, geometric forms maintain clarity and efficiency, reinforcing the AI-driven identity. The variable letter-spacing provides visual precision at different sizes.

### Onsite SemiMono — Used for code snippets, technical details, or specific data displays, offering a technical and precise counterpoint to the primary typeface. · `--font-onsite-semimono`
- **Substitute:** Menlo, Consolas, monospace
- **Weights:** 400
- **Sizes:** 12px, 16px
- **Line height:** 1.48, 1.60
- **Letter spacing:** 0.01em
- **Role:** Used for code snippets, technical details, or specific data displays, offering a technical and precise counterpoint to the primary typeface.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.6 | 0.12px | `--text-caption` |
| body-sm | 14px | 1.48 | — | `--text-body-sm` |
| body | 16px | 1.6 | — | `--text-body` |
| subheading | 18px | 1.48 | — | `--text-subheading` |
| heading-sm | 22px | 1.34 | -0.22px | `--text-heading-sm` |
| heading | 28px | 1.2 | -0.56px | `--text-heading` |
| heading-lg | 36px | 1.12 | -1.08px | `--text-heading-lg` |
| display | 48px | 1.04 | -1.92px | `--text-display` |
| display-lg | 72px | 1 | -4.32px | `--text-display-lg` |

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
| 80 | 80px | `--spacing-80` |
| 112 | 112px | `--spacing-112` |

### Border Radius

| Element | Value |
|---------|-------|
| misc | 12px |
| tags | 8px |
| cards | 16px |
| icons | 4px |
| buttons | 999px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(0, 0, 0, 0.02) 0px 3px 3px 0px, rgba(0, 0, 0, 0.01) ...` | `--shadow-subtle` |
| subtle-2 | `rgba(1, 5, 27, 0.06) 0px 0px 0px 1px inset` | `--shadow-subtle-2` |

### Layout

- **Section gap:** 40px
- **Card padding:** 16px
- **Element gap:** 8px

## Components

### Primary Action Button
**Role:** Call to action

Filled Mint Glare button with Ghost White text. Fully rounded for approachability. Uses a 999px radius and 8px vertical, 16px horizontal padding. Example: 'Start for free'.

### Secondary Action Button
**Role:** Alternative action

Ghost White filled button with Void Black text. Fully rounded for approachability. Uses a 999px radius and 8px vertical, 16px horizontal padding. Example: 'Book a demo'.

### Ghost Button
**Role:** Tertiary action, navigation

Transparent background with Ghost White text. Minimal padding (8px all around) and 8px border radius. Used for less prominent actions or navigation items. Example: Navigation links like 'Sign in'.

### Navigation Link
**Role:** Primary navigation

Ghost White text on a Void Black background, no explicit button styling. Simple padding 8px to 16px horizontally. Example: 'Platform', 'Customers'.

### Dark Card (Product View)
**Role:** Content container for product features/data

Deep Space background with 16px border radius and 16px padding on all sides. Used for displaying specific feature details or data snippets within the product interface.

### Dark Elevated Card (Product Content)
**Role:** Elevated content container

Carbon background with 16px border radius. Padding varies (16px, 24px) based on content. No shadow by default to maintain flat dark aesthetic. Used for larger content blocks within the product UI, like the Sourcing list. Note uses a single inset shadow to differentiate states.

### Light Card (Feature Showcase)
**Role:** Showcase content, testimonials

Ghost White background with 16px border radius. Generous 24px padding on all sides. Used for sections that require higher contrast hero content such as testimonials or key feature callouts where the content itself is the highlight.

### Information Tag
**Role:** Categorization, metadata

Faint gray background (#D9D9D9 with low opacity) with Twilight Slate text, 8px border radius. Padding is not explicitly defined but consistent with small elements. Used for showing categories like 'Source', 'Research', 'Web and ATS'.

## Do's and Don'ts

### Do
- Prioritize the Void Black background (#000000) for primary canvases and use Ghost White (#ffffff) for primary text on these surfaces to maintain strong contrast.
- Use Mint Glare (#7affb4) exclusively for primary calls-to-action to highlight critical interactions.
- Employ Euclid Circular A for all textual elements. Use heavier weights (500, 700) sparingly for emphasis, leaning on 300-400 for most content and headings. Use specified letter-spacing values from the type scale.
- Apply a 999px border radius to all primary and secondary buttons, and a 16px radius to cards to achieve the brand's distinct shape language.
- Use elementGap (8px) for consistent spacing between logical UI elements like text and buttons or icon and text.
- Utilize dark background variants like Deep Space (#0a1a14) and Carbon (#161818) for secondary surfaces to create subtle visual depth within the dark theme.
- Ensure all interactive elements have a clear Hover/Focus state that references Mint Glare for visual feedback.

### Don't
- Avoid introducing additional saturated colors; maintain Mint Glare (#7affb4) as the sole vivid accent.
- Do not use box-shadows for elevation; instead, differentiate surfaces using changes in background color (Void Black, Deep Space, Carbon) and subtle inset borders (e.g., rgba(1, 5, 27, 0.06) 0px 0px 0px 1px inset).
- Do not use generic system fonts; Euclid Circular A and Onsite SemiMono are critical to the brand identity.
- Avoid tight spacing; maintain a 'comfortable' density using the established `elementGap` (8px), `cardPadding` (16px), and `sectionGap` (40px).
- Do not apply rounded corners indiscriminately; adhere to the specified radii for buttons (999px), cards (16px), and tags (8px).
- Do not use large, decorative gradients; only the provided radial and linear gradients are permitted, and they should be used subtly for atmosphere, not as primary design elements.
- Avoid making body text too prominent; use Ash Gray (#5e6262) for less important body copy to maintain hierarchy.

## Imagery

This site uses product screenshots and abstract vector iconography. Product screenshots are contained within dark cards, showcasing the UI directly without external context. Icons are typically outlined or filled in monochromatic Ghost White or Twilight Slate, maintaining a lightweight, functional feel. The overall imagery density is image-heavy in sections showcasing the product, but text-dominant around explanatory content. Large atmospheric gradients (e.g., Digital Glow Radial Gradient) are used as background elements, providing subtle color shifts rather than explicit images.

## Layout

The page primarily uses a full-bleed layout, allowing the dark backgrounds and atmospheric gradients to span the entire viewport. Content is horizontally centered within a logical maximum width (likely around 1200-1400px, though not explicitly defined). The hero section features a centered headline and subtext over a deep black background. Sections exhibit consistent vertical spacing, often divided by large, full-bleed color changes or subtle gradients. Content is frequently arranged in multi-column grids or alternating text-left/image-right configurations, especially for feature showcases. The navigation is a sticky top bar with a left-aligned logo and right-aligned links and buttons.

## Agent Prompt Guide

**Quick Color Reference**
- text: #ffffff
- background: #000000
- border: #01051b (for secondary elements), #000000 (for strong separation)
- accent: #e3ffef
- primary action: #7affb4 (filled action)

**3-5 Example Component Prompts**
- Create a Primary Action Button: #7affb4 background, #000000 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
- Design a Dark Card (Product View): Deep Space (#0a1a14) background, 16px border radius, 16px padding. Inside, use Ghost White text (Euclid Circular A, 16px, weight 400) for labels like 'Sourcing' and 'Application Review'.
- Create a Ghost Button: Transparent background, Ghost White (#ffffff) text (Euclid Circular A, 16px, weight 400), 8px border radius, 8px padding. Example: 'Sign in'.
- Construct an Information Tag: Use Cloud Gray (#d9d9d9) with 20% opacity as background, Twilight Slate (#01051b) text (Euclid Circular A, 12px, weight 500), 8px border radius, 4px vertical, 8px horizontal padding. Example: 'Source'.

## Similar Brands

- **Vercel** — High-contrast dark mode UI, liberal use of white text on black, and a distinct, single accent color (green/teal).
- **Supabase** — Dark UI with vibrant accent colors for interactive elements, clean typography, and a functional, modern aesthetic.
- **Linear** — Monochromatic dark interface with crisp typography and subtle use of color for status and interactive states, prioritizing efficiency.
- **Anthropic** — Emphasis on AI, dark theme with minimal visual noise, and a focus on direct, clear communication through typography.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-void-black: #000000;
  --color-ghost-white: #ffffff;
  --color-carbon: #161818;
  --color-deep-space: #0a1a14;
  --color-twilight-slate: #01051b;
  --color-ash-gray: #5e6262;
  --color-slate-border: #828282;
  --color-cloud-gray: #d9d9d9;
  --color-mint-glare: #7affb4;
  --color-soft-mint: #e3ffef;
  --color-dark-forest: #000a06;
  --color-subtle-green: #0a2119;
  --color-digital-glow-radial-gradient: #006446;
  --gradient-digital-glow-radial-gradient: radial-gradient(circle, rgba(0, 100, 70, 0.4) 0%, rgba(0, 60, 40, 0.2) 30%, rgba(0, 30, 20, 0.08) 55%, rgba(0, 0, 0, 0) 75%);
  --color-digital-glow-linear-gradient: #0f3a2b;
  --gradient-digital-glow-linear-gradient: linear-gradient(rgb(15, 58, 43) 0%, rgb(0, 10, 7) 100%);

  /* Typography — Font Families */
  --font-euclid-circular-a: 'Euclid Circular A', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-onsite-semimono: 'Onsite SemiMono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.6;
  --tracking-caption: 0.12px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.48;
  --text-body: 16px;
  --leading-body: 1.6;
  --text-subheading: 18px;
  --leading-subheading: 1.48;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1.34;
  --tracking-heading-sm: -0.22px;
  --text-heading: 28px;
  --leading-heading: 1.2;
  --tracking-heading: -0.56px;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1.12;
  --tracking-heading-lg: -1.08px;
  --text-display: 48px;
  --leading-display: 1.04;
  --tracking-display: -1.92px;
  --text-display-lg: 72px;
  --leading-display-lg: 1;
  --tracking-display-lg: -4.32px;

  /* Typography — Weights */
  --font-weight-light: 300;
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
  --spacing-80: 80px;
  --spacing-112: 112px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 16px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-3xl-2: 28px;
  --radius-full: 100px;
  --radius-full-2: 999px;

  /* Named Radii */
  --radius-misc: 12px;
  --radius-tags: 8px;
  --radius-cards: 16px;
  --radius-icons: 4px;
  --radius-buttons: 999px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.02) 0px 3px 3px 0px, rgba(0, 0, 0, 0.01) 0px 7px 7px 0px, rgba(0, 0, 0, 0.01) 0px 14px 14px 0px, rgba(0, 0, 0, 0.01) 0px 25px 24px 0px;
  --shadow-subtle-2: rgba(1, 5, 27, 0.06) 0px 0px 0px 1px inset;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-void-black: #000000;
  --color-ghost-white: #ffffff;
  --color-carbon: #161818;
  --color-deep-space: #0a1a14;
  --color-twilight-slate: #01051b;
  --color-ash-gray: #5e6262;
  --color-slate-border: #828282;
  --color-cloud-gray: #d9d9d9;
  --color-mint-glare: #7affb4;
  --color-soft-mint: #e3ffef;
  --color-dark-forest: #000a06;
  --color-subtle-green: #0a2119;
  --color-digital-glow-radial-gradient: #006446;
  --color-digital-glow-linear-gradient: #0f3a2b;

  /* Typography */
  --font-euclid-circular-a: 'Euclid Circular A', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-onsite-semimono: 'Onsite SemiMono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.6;
  --tracking-caption: 0.12px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.48;
  --text-body: 16px;
  --leading-body: 1.6;
  --text-subheading: 18px;
  --leading-subheading: 1.48;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1.34;
  --tracking-heading-sm: -0.22px;
  --text-heading: 28px;
  --leading-heading: 1.2;
  --tracking-heading: -0.56px;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1.12;
  --tracking-heading-lg: -1.08px;
  --text-display: 48px;
  --leading-display: 1.04;
  --tracking-display: -1.92px;
  --text-display-lg: 72px;
  --leading-display-lg: 1;
  --tracking-display-lg: -4.32px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-80: 80px;
  --spacing-112: 112px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-3xl-2: 28px;
  --radius-full: 100px;
  --radius-full-2: 999px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.02) 0px 3px 3px 0px, rgba(0, 0, 0, 0.01) 0px 7px 7px 0px, rgba(0, 0, 0, 0.01) 0px 14px 14px 0px, rgba(0, 0, 0, 0.01) 0px 25px 24px 0px;
  --shadow-subtle-2: rgba(1, 5, 27, 0.06) 0px 0px 0px 1px inset;
}
```

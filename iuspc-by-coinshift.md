# iUSPC by Coinshift — Style Reference
> Deep space command center.

**Theme:** dark

iUSPC by Coinshift presents a data-rich, institutional dark mode aesthetic, combining a deep, near-black canvas with luminous, crisp typography. A subtle, fiery red-orange gradient peeks through occasional surfaces and defines interactive states, creating a sense of controlled power. The system prioritizes functional clarity and precise data organization over visual theatrics, with a compact layout and minimal use of elevation, allowing information to take center stage.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ember | `#020617` | `--color-midnight-ember` | Primary background, deep surface color |
| Slate Text | `#64748b` | `--color-slate-text` | Muted body text, secondary headings, inactive navigation links, and icon fills, providing a whisper of detail against darker backgrounds |
| Steel Gray | `#475569` | `--color-steel-gray` | Subtle background for card-like elements, muted text, and borders within contained sections |
| Divider Gray | `#353845` | `--color-divider-gray` | Hairline borders for interactive elements and visual separators, indicating structure without starkness |
| Action Ember | `#651a15` | `--color-action-ember` | Red outline accent for tags, dividers, and focused UI edges. Do not promote it to the primary CTA color |
| Frost White Light | `#f1f5f9` | `--color-frost-white-light` | High-contrast text for critical information and primary headings |
| Frost White Heavy | `#e5e7eb` | `--color-frost-white-heavy` | Strong borders for active states, high-prominence textual elements, and icons, demanding attention |
| Cloud Gray | `#cbd5e1` | `--color-cloud-gray` | Mid-level text clarity for descriptive paragraphs and prominent body text |
| Inferno Gradient Radial | `radial-gradient(circle, rgba(250, 56, 18, 0.07) 0%, rgba(250, 56, 18, 0.03) 35%, rgba(0, 0, 0, 0) 65%)` | `--color-inferno-gradient-radial` | Decorative background glow, emanating from points of interest and lending a subtle heat to the interface |
| Horizon Gradient Conic | `conic-gradient(at 90% 90%, rgb(15, 23, 42) 75%, rgb(19, 10, 6) 0deg)` | `--color-horizon-gradient-conic` | Large, subtle background gradient that hints at depth and perspective |

## Tokens — Typography

### Inter — Primary typeface for all UI elements, from extensive body text to impactful headings. Its versatility across weights supports a structured information architecture. · `--font-inter`
- **Substitute:** system-ui
- **Weights:** 300, 400, 500, 600
- **Sizes:** 11px, 12px, 14px, 16px, 18px, 20px, 24px, 30px, 36px, 48px, 56px
- **Line height:** 1.00, 1.08, 1.11, 1.20, 1.33, 1.40, 1.43, 1.50, 1.56, 1.63
- **Letter spacing:** -0.025em at 56px, 0.200em at 12px, 0.050em at 11px, normal otherwise
- **Role:** Primary typeface for all UI elements, from extensive body text to impactful headings. Its versatility across weights supports a structured information architecture.

### ABCSynt — Used for specific, often decorative or branding-critical, text elements where clean, non-standard letterforms are desired, such as for the brand logo in the navigation. · `--font-abcsynt`
- **Substitute:** Inter, system-ui
- **Weights:** 400
- **Sizes:** 10px, 16px, 18px
- **Line height:** 1.00, 1.50
- **Letter spacing:** normal
- **Role:** Used for specific, often decorative or branding-critical, text elements where clean, non-standard letterforms are desired, such as for the brand logo in the navigation.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.5 | — | `--text-caption` |
| body-lg | 16px | 1.5 | — | `--text-body-lg` |
| subheading | 18px | 1.4 | — | `--text-subheading` |
| heading-sm | 24px | 1.33 | — | `--text-heading-sm` |
| heading | 36px | 1.11 | — | `--text-heading` |
| heading-lg | 48px | 1.08 | — | `--text-heading-lg` |
| display | 56px | 1 | -1.4px | `--text-display` |

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
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 96 | 96px | `--spacing-96` |
| 112 | 112px | `--spacing-112` |
| 144 | 144px | `--spacing-144` |
| 160 | 160px | `--spacing-160` |
| 240 | 240px | `--spacing-240` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 9999px |
| links | 12px |
| buttons | 9999px |
| general | 0px |
| navItems | 8px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| sm | `rgba(250, 56, 18, 0.15) 0px 0px 8px 0px` | `--shadow-sm` |

### Layout

- **Section gap:** 32px
- **Card padding:** 32px
- **Element gap:** 24px

## Components

### Navigation Link
**Role:** Header navigation item, indicating clickable sections or pages.

Text in Slate Text (#64748b) at 16px, Inter weight 400. Hover/active states show a subtle bottom border in Divider Gray (#353845) or Frost White Heavy (#e5e7eb) with 8px corner radius for the overall hit area.

### Launch App Button
**Role:** Primary call to action in the navigation bar.

An outlined button with a border in Divider Gray (#353845) and an internal padding of 8px vertical, 16px horizontal, on a transparent background. Text is Frost White Heavy (#e5e7eb) at 16px, Inter weight 400. Radius is 8px.

### Hero Section Headline
**Role:** Main title on the landing page, conveying the core message.

Text in Frost White Light (#f1f5f9) at 56px, Inter weight 600, with a letter spacing of -1.4px. Set against the Midnight Ember background.

### Hero Section Body Text
**Role:** Support text in the hero section, offering context to the headline.

Text in Slate Text (#64748b) at 18px, Inter weight 400. Used without a specific background, allowing the Midnight Ember canvas to show through.

### Ghost Action Button
**Role:** Secondary call to action, offering a less prominent but still interactive option.

An outlined button with a 2px border in Divider Gray (#353845), text in Frost White Heavy (#e5e7eb) at 16px, Inter weight 400. Padding of 12px vertical and 24px horizontal. Radius is 9999px for a pill shape.

### Info Card
**Role:** Container for showcasing key information or features within content sections.

Zero border-radius, fully transparent background (rgba(0,0,0,0)). Vertically padded with 32px. Content within uses Slate Text (#64748b) and Steel Gray (#475569) for varied text prominence.

## Do's and Don'ts

### Do
- Prioritize text legibility with high contrast ratios, especially for Frost White Light (#f1f5f9) or Frost White Heavy (#e5e7eb) against Midnight Ember (#020617).
- Use pill-shaped radii (9999px) for all buttons and tags to maintain a soft, friendly interaction style.
- Apply the Action Ember (#651a15) color sparingly, primarily as a border or subtle background hint for interactive elements, not as a solid fill for primary buttons.
- Maintain a deep, dark theme where Midnight Ember (#020617) is the pervasive background for most sections.
- Use Inter font with varying weights and sizes to establish clear typographic hierarchy, avoiding excessive customization.
- Ensure generous vertical spacing (at least 32px) between major content sections to enhance readability and spatial comfort.

### Don't
- Do not introduce bright, fully saturated background colors; all backgrounds should lean towards the established dark, muted palette.
- Avoid heavy drop shadows or excessive elevation that would contradict the flat, data-focused nature of the design.
- Do not use generic, unstyled system fonts; always use Inter or ABCSynt with the specified weights and letter-spacing.
- Resist using Frost White Light (#f1f5f9) as a background; it is reserved for high-contrast text and borders.
- Do not use small border radii (e.g., 4px) for cards or larger containers; keep them at 0px for a sharp, architectural feel unless specifically linking context to other interactive elements like nav items (8px).
- Avoid decorative imagery that does not serve a functional purpose; UI should be information-rich and direct.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Midnight Ember Canvas | `#020617` | The primary, deep background for the entire application, providing a stark, high-contrast base for all content. |
| 2 | Steel Gray Surface | `#475569` | A subtle, slightly elevated background used for contained sections or card-like elements, creating a gentle separation from the main canvas. |

## Imagery

The visual language is characterized by a minimal use of functional icons with a bold stroke weight that are monochrome. Abstract geometric patterns, specifically a subtle grid and organic wave-like forms, are used as atmospheric background elements to add depth without distracting from the content. Product screenshots are absent; the focus is entirely on the UI and data. Imagery serves a decorative atmosphere role rather than explanatory content. The density is text-dominant, with imagery used sparingly.

## Layout

The page model is primarily max-width contained, with sections flowing vertically. The hero section is full-bleed with a centered headline and body text, anchored by a ghost action button. Sections alternate between a deep Midnight Ember background with Frost White text and a slightly lighter surface where Steel Gray might appear, maintaining consistent vertical rhythm. Content is arranged with centered stacks for headlines and subtext, and occasionally asymmetrical compositions, such as a text block on one side and a supporting visual element on the other, or a list of items on the left with a corresponding explanation on the right. There's no distinct grid usage for cards, but item lists are well-structured vertically. The navigation is a sticky header with minimal links and a 'Launch App' button.

## Agent Prompt Guide

### Quick Color Reference
text: #f1f5f9
background: #020617
border: #e5e7eb
accent: #651a15
primary action: no distinct CTA color

### 3-5 Example Component Prompts
1. Create a Hero section: Midnight Ember (#020617) conic-gradient background. Centered display heading with text: "$3 trillion in private credit. Your share starts here.", Frost White Light (#f1f5f9), Inter weight 600, 56px size, -1.4px letter-spacing. Subtext: "The world's top credit managers. One token. Liquid. Composable. Onchain.", Slate Text (#64748b), Inter weight 400, 18px size. Below the subtext, a Ghost Action Button: text "Launch App", Frost White Heavy (#e5e7eb), 2px border in Divider Gray (#353845), 9999px radius, 12px vertical padding, 24px horizontal padding.
2. Design a Navigation Bar: Midnight Ember (#020617) background. Left aligned brand logo using ABCSynt font. Navigation links: "iUSPC", "Season 1 Points", "Analytics", "Legal", each with Slate Text (#64748b), Inter weight 400, 16px size. Right aligned "Launch App" button with Frost White Heavy (#e5e7eb) text, Divider Gray (#353845) border, 8px radius, 8px vertical padding, 16px horizontal padding.
3. Create an Info Card within a main section: transparent background (rgba(0,0,0,0)), 0px border-radius, 32px top and bottom padding. Headline: "The best yield in finance.", Frost White Light (#f1f5f9), Inter weight 600, 36px size. Muted text below: "Behind the highest walls.", Slate Text (#64748b), Inter weight 400, 36px size.

## Similar Brands

- **Aave** — Similar dark theme with a focus on financial data and subtle use of accent colors for interaction.
- **Uniswap** — Employs a deep dark background and structured information presentation, common in DeFi platforms.
- **Messari** — Prioritizes data readability on a dark canvas with clean typography and minimal, functional UI elements.
- **StarkWare** — Features a technical, dark aesthetic with distinct typographic treatments and controlled use of brand accents.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ember: #020617;
  --color-slate-text: #64748b;
  --color-steel-gray: #475569;
  --color-divider-gray: #353845;
  --color-action-ember: #651a15;
  --color-frost-white-light: #f1f5f9;
  --color-frost-white-heavy: #e5e7eb;
  --color-cloud-gray: #cbd5e1;
  --color-inferno-gradient-radial: #fa3812;
  --gradient-inferno-gradient-radial: radial-gradient(circle, rgba(250, 56, 18, 0.07) 0%, rgba(250, 56, 18, 0.03) 35%, rgba(0, 0, 0, 0) 65%);
  --color-horizon-gradient-conic: #0f172a;
  --gradient-horizon-gradient-conic: conic-gradient(at 90% 90%, rgb(15, 23, 42) 75%, rgb(19, 10, 6) 0deg);

  /* Typography — Font Families */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-abcsynt: 'ABCSynt', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --text-body-lg: 16px;
  --leading-body-lg: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.4;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.33;
  --text-heading: 36px;
  --leading-heading: 1.11;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.08;
  --text-display: 56px;
  --leading-display: 1;
  --tracking-display: -1.4px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;

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
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-112: 112px;
  --spacing-144: 144px;
  --spacing-160: 160px;
  --spacing-240: 240px;

  /* Layout */
  --section-gap: 32px;
  --card-padding: 32px;
  --element-gap: 24px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-tags: 9999px;
  --radius-links: 12px;
  --radius-buttons: 9999px;
  --radius-general: 0px;
  --radius-navitems: 8px;

  /* Shadows */
  --shadow-sm: rgba(250, 56, 18, 0.15) 0px 0px 8px 0px;

  /* Surfaces */
  --surface-midnight-ember-canvas: #020617;
  --surface-steel-gray-surface: #475569;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ember: #020617;
  --color-slate-text: #64748b;
  --color-steel-gray: #475569;
  --color-divider-gray: #353845;
  --color-action-ember: #651a15;
  --color-frost-white-light: #f1f5f9;
  --color-frost-white-heavy: #e5e7eb;
  --color-cloud-gray: #cbd5e1;
  --color-inferno-gradient-radial: #fa3812;
  --color-horizon-gradient-conic: #0f172a;

  /* Typography */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-abcsynt: 'ABCSynt', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --text-body-lg: 16px;
  --leading-body-lg: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.4;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.33;
  --text-heading: 36px;
  --leading-heading: 1.11;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.08;
  --text-display: 56px;
  --leading-display: 1;
  --tracking-display: -1.4px;

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
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-112: 112px;
  --spacing-144: 144px;
  --spacing-160: 160px;
  --spacing-240: 240px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-full: 9999px;

  /* Shadows */
  --shadow-sm: rgba(250, 56, 18, 0.15) 0px 0px 8px 0px;
}
```

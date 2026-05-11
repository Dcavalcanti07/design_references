# Upstash — Style Reference
> Crisp alpine air and digital green fields. A refreshing clarity guides every element, grounded by natural gradients.

**Theme:** light

This design system projects a clean, high-tech sensibility with judicious use of a vibrant primary green against a predominantly light, neutral canvas. Subtle gradients and sophisticated typography choices, including a custom, tightly-tracked headline font, prevent the aesthetic from becoming sterile, instead imparting an approachable authority. The interplay of soft, rounded elements (pill buttons, large card radii) with the sharp text contrasts with the precision implied by the serverless technology, making complex infrastructure feel accessible.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Forest Pine | `#022c22` | `--color-forest-pine` | Primary text across the site, interactive elements in their default state, navigation links. Creates a deep, serious foundation. |
| Spring Bud | `#00bc7d` | `--color-spring-bud` | Primary action buttons, prominent icons, and key highlights. Its vividness signals interaction and success against the calm backgrounds. |
| Evergreen | `#007a55` | `--color-evergreen` | Subtle interactive states for links and icons, offering a slightly muted version of Spring Bud for secondary actions or hover states. |
| Sky Mist | `#e5e7eb` | `--color-sky-mist` | Borders for cards, buttons, and other UI elements, creating soft definition. Also used as background for subtle secondary containers. |
| Paper White | `#ffffff` | `--color-paper-white` | Dominant page background, text on dark backgrounds, and card surfaces. Establishes the light theme. |
| Graphite | `#71717b` | `--color-graphite` | Secondary text, muted interactive elements, and navigation items. Provides softer contrast than Forest Pine for less critical information. |
| Obsidian | `#000000` | `--color-obsidian` | Code block backgrounds and specific high-contrast text elements. Used sparingly for maximum impact. |
| Gradient Aura | `linear-gradient(to right, oklch(0.508 0.118 165.612), oklch(0.696 0.17 162.48), rgb(245, 158, 11))` | `--color-gradient-aura` | Used for significant hero headings, subtly transitioning brand colors to a warm accent. Commands attention with a modern, dynamic flair. |
| Whisper Green | `#b4e6d6` | `--color-whisper-green` | Subtle visual accents and illustrations, adding a touch of verdant hue without overwhelming the primary green. |
| Alert Red | `#dc2626` | `--color-alert-red` | Semantically reserved for error states or caution, its vividness ensures immediate notice. |
| Warm Gold | `#f59e0b` | `--color-warm-gold` | Secondary accent for highlighting specific words or achieving a warm component background sheen. |
| Dark Code Background | `#09090b` | `--color-dark-code-background` | Background for code snippets, offering a high-contrast surface for monospace text. |
| Ghost Button Background | `#f5f5f5` | `--color-ghost-button-background` | Background for secondary ghost buttons or subtle badges. |

## Tokens — Typography

### Inter — Default body text, navigation items, buttons, and general UI elements. Its neutrality and readability provide a clean, functional base for the entire system. · `--font-inter`
- **Substitute:** Inter
- **Weights:** 400, 500, 600
- **Sizes:** 12px, 13px, 14px, 16px, 20px, 24px, 48px
- **Line height:** 1.00, 1.33, 1.40, 1.43, 1.50, 1.85
- **Letter spacing:** normal
- **Role:** Default body text, navigation items, buttons, and general UI elements. Its neutrality and readability provide a clean, functional base for the entire system.

### __Inter_Tight_a3c0d3 — Headlines and prominent display text. The tight letter-spacing at larger sizes, combined with the slightly condensed form, conveys a modern, efficient, and direct tone without sacrificing legibility. · `--font-intertighta3c0d3`
- **Substitute:** Inter Tight
- **Weights:** 500, 600, 700
- **Sizes:** 22px, 24px, 30px, 48px, 128px, 180px
- **Line height:** 1.00, 1.20, 1.25, 1.33, 1.48
- **Letter spacing:** -0.0250em
- **Role:** Headlines and prominent display text. The tight letter-spacing at larger sizes, combined with the slightly condensed form, conveys a modern, efficient, and direct tone without sacrificing legibility.

### ui-monospace — Code snippets and technical data presentation. The negative letter spacing ensures code blocks remain compact and readable, aligning with the precision of a serverless platform. · `--font-ui-monospace`
- **Substitute:** Menlo, Consolas, Monaco, 'Andale Mono', 'Ubuntu Mono', monospace
- **Weights:** 400
- **Sizes:** 14px
- **Line height:** 1.50
- **Letter spacing:** -0.0730em
- **Role:** Code snippets and technical data presentation. The negative letter spacing ensures code blocks remain compact and readable, aligning with the precision of a serverless platform.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.43 | — | `--text-caption` |
| body | 14px | 1.5 | — | `--text-body` |
| body-lg | 16px | 1.5 | — | `--text-body-lg` |
| subheading | 20px | 1.5 | — | `--text-subheading` |
| heading-sm | 22px | 1.48 | -0.48px | `--text-heading-sm` |
| heading | 24px | 1.25 | -0.6px | `--text-heading` |
| heading-lg | 30px | 1.2 | -0.75px | `--text-heading-lg` |
| display | 48px | 1 | -1.2px | `--text-display` |
| display-lg | 128px | 1 | -3.2px | `--text-display-lg` |

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
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 96 | 96px | `--spacing-96` |
| 112 | 112px | `--spacing-112` |
| 216 | 216px | `--spacing-216` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 16px |
| input | 6px |
| badges | 12px |
| buttons | 9999px |
| general | 12px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(0, 0, 0, 0.05) 0px 1px 2px 0px` | `--shadow-subtle` |

### Layout

- **Section gap:** 40px
- **Card padding:** 32px
- **Element gap:** 8px

## Components

### Primary Action Button
**Role:** Main call to action throughout the site.

oklch(0.552 0.016 285.938) text on oklch(0.552 0.016 285.938) background (visually renders as transparent). No explicit padding in style, text content determines size. 9999px border-radius. Primarily for utility-style interactive elements in the header area.

### Ghost Variant Button
**Role:** Secondary action button for highlighting features or complementary choices.

oklch(0.508 0.118 165.612) text on rgba(4, 120, 87, 0.08) background. 12px border-radius, 8px vertical padding, 16px horizontal padding. Prominently used for feature selection and interactive controls.

### Tab Header Button
**Role:** Used for content categorization and switching tabs.

oklch(0.552 0.016 285.938) text on oklch(0.97 0 0) background. Only top border-radius of 16px. No padding defined in style, implies content-driven layout. Used in code example sections for language selection.

### Header Navigation Button
**Role:** Compact interactive elements within the header, typically small utility links.

White text on transparent background. 6px border-radius, 0px vertical padding, 12px horizontal padding. Used for the 'Login' button in non-hero sections, and similar utility buttons.

### Feature Card
**Role:** Containers for showcasing product features or testimonials.

rgba(4, 120, 87, 0.08) background with 16px border-radius. No box-shadow, creating a flat, modern appearance. 32px padding on all sides.

### Icon Button (with image)
**Role:** Used to represent technologies, frequently in a list or grid.

Transparent background, oklch(0.552 0.016 285.938) text. 9999px border-radius (pill shape). Minimal horizontal/vertical padding (6px/12px). Features an inline icon/image.

## Do's and Don'ts

### Do
- Prioritize Inter Tight for all display headings large than 24px, using its characteristic -0.0250em letter-spacing for a modern, condensed feel.
- Use Spring Bud (#00bc7d) for primary calls to action, ensuring visual prominence and signaling interaction.
- Apply Forest Pine (#022c22) for all main body text and prominent links to maintain deep readability.
- Utilize 9999px border-radius for all buttons and interactive badges to create a consistent 'pill' aesthetic, pairing soft shapes with sharp typography.
- Maintain a comfortable information density by using 8px as the elemental spacing unit and 40px as the standard section gap.
- Employ the rgba(4, 120, 87, 0.08) filled background with 16px radius for secondary content groupings and interactive ghost buttons.
- Leverage the Gradient Aura for hero section headlines to introduce a dynamic, multi-tonal brand presence.

### Don't
- Avoid using box-shadows on main cards or elements, the design relies on background color shifts and borders for depth, not elevation.
- Do not deviate from the specified typefaces; Inter and Inter Tight are core to the brand's voice.
- Refrain from introducing other vibrant colors outside the established brand and accent palette (Spring Bud, Evergreen, Warm Gold) to maintain visual focus.
- Do not use generic system colors for text; adhere strictly to Forest Pine (#022c22) and Graphite (#71717b) for text hierarchies.
- Avoid using sharp corners for interactive elements; 9999px (pill) or 12px/16px radii are preferred for buttons and cards.
- Do not use more than two distinct fonts on a single page, with ui-monospace reserved exclusively for code representation.

## Elevation

This design intentionally avoids strong shadows for elevation. Instead, depth and layering are achieved through a combination of distinct background color changes (e.g., Paper White vs. rgba(4, 120, 87, 0.08)) and subtle borders (Sky Mist #e5e7eb). This creates a sense of clean separation and organization without the visual weight of drop shadows, reinforcing a light and airy feel.

## Imagery

The visual language for imagery is primarily functional and illustrative, focusing on product capabilities rather than human elements. For technologies represented (Redis, Vector, etc.), simple iconographic logos are used. Photography is absent. Illustrations are stylized, flat, and often incorporate the brand's Spring Bud color, sometimes with subtle green gradients. They serve an explanatory or decorative role, breaking up text with visual metaphors. Icons are monochromatic or duotone, utilizing the brand green consistently. Product shots are typically abstract, featuring technology or UI snippets, often against a subtle, tinted gradient background. Density is moderate, with images used to punctuate sections and explain features, rather than as dominant full-bleed hero elements.

## Layout

The page adheres to a max-width contained layout, with content centered. The hero section is full-bleed, featuring a large, gradient-colored headline over a subtle green-tinted background. Subsequent sections generally alternate between light backgrounds and sections with a light green tinted background (rgba(4, 120, 87, 0.08)), creating a soft visual rhythm. Content is arranged in alternating text-left/image-right (or vice-versa) patterns, and frequently uses a 3-column card grid for feature showcases. There's a notable use of code block sections that span the full width of the main content area. Vertical spacing between sections is consistently comfortable, emphasizing breathing room. The navigation is a sticky top bar, containing branding, key links, and a prominent login button.

## Agent Prompt Guide

### Quick Color Reference
- Text: #022c22 (Forest Pine)
- Background: #ffffff (Paper White)
- CTA: #00bc7d (Spring Bud)
- Border: #e5e7eb (Sky Mist)
- Accent Background: rgba(4, 120, 87, 0.08)

### Example Component Prompts
1. Create a hero section: Full-bleed background `#ffffff` with a subtle linear gradient from `oklch(0.508 0.118 165.612)` to `rgb(253, 224, 71)` at the bottom. Centered headline 'Serverless Data Platform' using `__Inter_Tight_a3c0d3` 128px weight 700 with `-0.0250em` letter-spacing, using `linear-gradient(to right, oklch(0.508 0.118 165.612), oklch(0.696 0.17 162.48), rgb(245, 158, 11))` as text fill. Subheading 'The single platform for all your data needs' in Inter 24px weight 400, color `#71717b`. Below, a primary action button 'Start for Free' with `#00bc7d` background, `#ffffff` text, 9999px radius, and 16px 24px padding.
2. Create a 'Ghost Feature Button': Text 'Redis ®*' using Inter 16px weight 400, color `#022c22`. Transparent `oklch(0.552 0.016 285.938)` background and `rgba(4, 120, 87, 0.08)` border, 9999px border-radius, with 0px vertical and 0px horizontal padding, plus a suitable icon. Center the text and icon.
3. Create a 'Feature Card': Background `rgba(4, 120, 87, 0.08)`, 16px border-radius, no box-shadow. Content inside should have 32px padding on all sides. Use Inter 20px weight 600 color `#022c22` for its title, and Inter 14px weight 400 color `#71717b` for its description.
4. Create a code block wrapper: Background `#09090b`, 16px border-radius. Code text should use `ui-monospace` 14px weight 400, `#ffffff` color, and `-0.0730em` letter-spacing. Include tab buttons for selecting languages like 'TypeScript' and 'Python', using the 'Tab Header Button' variant.

## Similar Brands

- **Vercel** — Shares a clean, developer-focused aesthetic with prominent use of a single vibrant accent color against a neutral palette, combined with modern typography.
- **PlanetScale** — Exhibits a similar modern dev-tool UI, using strong headlines, distinct card-based layouts, and a limited, high-impact color palette for interaction.
- **Supabase** — Features a light theme with clear branding through green accents, tight typography, and straightforward, functional component designs.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-forest-pine: #022c22;
  --color-spring-bud: #00bc7d;
  --color-evergreen: #007a55;
  --color-sky-mist: #e5e7eb;
  --color-paper-white: #ffffff;
  --color-graphite: #71717b;
  --color-obsidian: #000000;
  --color-gradient-aura: #00bc7d;
  --gradient-gradient-aura: linear-gradient(to right, oklch(0.508 0.118 165.612), oklch(0.696 0.17 162.48), rgb(245, 158, 11));
  --color-whisper-green: #b4e6d6;
  --color-alert-red: #dc2626;
  --color-warm-gold: #f59e0b;
  --color-dark-code-background: #09090b;
  --color-ghost-button-background: #f5f5f5;

  /* Typography — Font Families */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-intertighta3c0d3: '__Inter_Tight_a3c0d3', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ui-monospace: 'ui-monospace', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.43;
  --text-body: 14px;
  --leading-body: 1.5;
  --text-body-lg: 16px;
  --leading-body-lg: 1.5;
  --text-subheading: 20px;
  --leading-subheading: 1.5;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1.48;
  --tracking-heading-sm: -0.48px;
  --text-heading: 24px;
  --leading-heading: 1.25;
  --tracking-heading: -0.6px;
  --text-heading-lg: 30px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -0.75px;
  --text-display: 48px;
  --leading-display: 1;
  --tracking-display: -1.2px;
  --text-display-lg: 128px;
  --leading-display-lg: 1;
  --tracking-display-lg: -3.2px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-112: 112px;
  --spacing-216: 216px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 32px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-3xl: 35.2px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-cards: 16px;
  --radius-input: 6px;
  --radius-badges: 12px;
  --radius-buttons: 9999px;
  --radius-general: 12px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.05) 0px 1px 2px 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-forest-pine: #022c22;
  --color-spring-bud: #00bc7d;
  --color-evergreen: #007a55;
  --color-sky-mist: #e5e7eb;
  --color-paper-white: #ffffff;
  --color-graphite: #71717b;
  --color-obsidian: #000000;
  --color-gradient-aura: #00bc7d;
  --color-whisper-green: #b4e6d6;
  --color-alert-red: #dc2626;
  --color-warm-gold: #f59e0b;
  --color-dark-code-background: #09090b;
  --color-ghost-button-background: #f5f5f5;

  /* Typography */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-intertighta3c0d3: '__Inter_Tight_a3c0d3', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ui-monospace: 'ui-monospace', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.43;
  --text-body: 14px;
  --leading-body: 1.5;
  --text-body-lg: 16px;
  --leading-body-lg: 1.5;
  --text-subheading: 20px;
  --leading-subheading: 1.5;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1.48;
  --tracking-heading-sm: -0.48px;
  --text-heading: 24px;
  --leading-heading: 1.25;
  --tracking-heading: -0.6px;
  --text-heading-lg: 30px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -0.75px;
  --text-display: 48px;
  --leading-display: 1;
  --tracking-display: -1.2px;
  --text-display-lg: 128px;
  --leading-display-lg: 1;
  --tracking-display-lg: -3.2px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-112: 112px;
  --spacing-216: 216px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-3xl: 35.2px;
  --radius-full: 9999px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.05) 0px 1px 2px 0px;
}
```

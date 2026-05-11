# Shelby — Style Reference
> Cacao and neon pink. A dark, rich canvas illuminated by electric, playful accents.

**Theme:** dark

Shelby presents as a bold, almost playful take on enterprise software, fusing a deep, rich cacao-brown with a vibrant, energetic hot pink. This highly chromatic palette creates a high-contrast experience, where text and key elements pop dramatically. The use of custom, strong sans-serif typography paired with a monospaced font reinforces a technical yet approachable identity, while sharp corners are softened by occasional, deliberate slight rounding, hinting at precision within expressiveness.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Shelby Cacao | `#322312` | `--color-shelby-cacao` | Primary background for dark sections, primary text on light surfaces, borders in specific contexts. |
| Shelby Rose Dust | `#FFDFEF` | `--color-shelby-rose-dust` | Light background for sections, text on dark backgrounds, secondary button backgrounds. |
| Shelby Hibiscus Pink | `#FF77C9` | `--color-shelby-hibiscus-pink` | Primary brand accent, main interactive element color (buttons, links), key headlines. Establishes brand energy and focus. |
| Shelby Plum | `#470B64` | `--color-shelby-plum` | Subtler background for elevated sections and card surfaces within dark modes. |
| Shelby Mauve | `#FFC2E1` | `--color-shelby-mauve` | Subtle card backgrounds, decorative elements, muted text. |
| Shelby Lavender Mist | `#EEE2FF` | `--color-shelby-lavender-mist` | Subtle button text and border color for specific dark-mode buttons. |
| Shelby Deep Rose | `#481D2A` | `--color-shelby-deep-rose` | Muted background within dark sections, used for specific icons or less prominent borders. |
| Shelby Steel Grey | `#5B4F41` | `--color-shelby-steel-grey` | Subtle border color for non-interactive elements. |

## Tokens — Typography

### Times — Times — detected in extracted data but not described by AI · `--font-times`
- **Weights:** 400
- **Sizes:** 10px
- **Line height:** 1
- **Role:** Times — detected in extracted data but not described by AI

### GT-Planar — Headlines and primary body text. Its subtle weight variations and precise letter-spacing give it a technical yet approachable feel. · `--font-gt-planar`
- **Substitute:** Inter
- **Weights:** 300, 400, 500, 700
- **Sizes:** 10px, 16px, 18px, 22px, 42px, 48px, 59px, 95px
- **Line height:** 0.90, 0.95, 1.00, 1.15, 1.20, 1.40
- **Letter spacing:** -0.0400em at display sizes, -0.0200em at large headings
- **Role:** Headlines and primary body text. Its subtle weight variations and precise letter-spacing give it a technical yet approachable feel.

### SuisseIntl — Navigation links and secondary interface elements. Provides a clean, modern contrast to GT-Planar. · `--font-suisseintl`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 10px
- **Line height:** 1.00, 1.20
- **Letter spacing:** normal
- **Role:** Navigation links and secondary interface elements. Provides a clean, modern contrast to GT-Planar.

### ABCReproMono — Specific badge text, code snippets, and fine print. Its monospace nature conveys precision and technicality. · `--font-abcrepromono`
- **Substitute:** Space Mono
- **Weights:** 400, 500
- **Sizes:** 11px, 12px
- **Line height:** 0.79, 1.20
- **Letter spacing:** normal
- **Role:** Specific badge text, code snippets, and fine print. Its monospace nature conveys precision and technicality.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1 | — | `--text-caption` |
| body | 16px | 1.2 | — | `--text-body` |
| subheading | 18px | 1.2 | — | `--text-subheading` |
| heading-sm | 22px | 1.2 | — | `--text-heading-sm` |
| heading | 42px | 1.15 | -0.42px | `--text-heading` |
| heading-lg | 48px | 1.15 | -0.48px | `--text-heading-lg` |
| display | 59px | 0.95 | -0.47px | `--text-display` |
| display-lg | 95px | 0.9 | -0.76px | `--text-display-lg` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 8 | 8px | `--spacing-8` |
| 12 | 12px | `--spacing-12` |
| 20 | 20px | `--spacing-20` |
| 36 | 36px | `--spacing-36` |
| 40 | 40px | `--spacing-40` |
| 116 | 116px | `--spacing-116` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 9.89583px |
| badges | 3.95833px |
| buttons | 3.95833px |
| default | 3.95833px |
| secondaryButtons | 11.875px |

### Layout

- **Section gap:** 40px
- **Card padding:** 15px
- **Element gap:** 15px

## Components

### Ghost Button - Hot Pink
**Role:** Primary Call to Action

Text: Shelby Hibiscus Pink (#FF77C9), background: transparent, border: 1px bottom Shelby Hibiscus Pink (#FF77C9), radius: 0px, padding: 3.95833px 0px 0px 0px.

### Outline Button - Rounded Hot Pink
**Role:** Secondary Call to Action

Text: Shelby Hibiscus Pink (#FF77C9), background: Shelby Rose Dust (#FFDFEF), border: 1px solid Shelby Hibiscus Pink (#FF77C9), radius: 11.875px, padding: 19.7917px.

### Filled Button - Plum
**Role:** Alternative Call to Action on Dark Backgrounds

Text: Shelby Lavender Mist (#EEE2FF), background: Shelby Plum (#470B64), border: 1px solid Shelby Lavender Mist (#EEE2FF), radius: 3.95833px, padding: 12.8646px 14.8438px.

### Card - Hot Pink
**Role:** Highlight Card

Background: Shelby Hibiscus Pink (#FF77C9), border: none, radius: 9.89583px, padding: 0px.

### Card - Muted Pink
**Role:** Information Card

Background: Shelby Mauve (#FFC2E1), border: none, radius: 5.9375px, padding: 0px.

### Card - Vivid Violet
**Role:** Accent Card

Background: #DE8AFF, border: none, radius: 7.91667px, padding: 0px.

### Badge - Transparent Dark
**Role:** Category Tag

Text: Shelby Cacao (#322312), background: transparent, border: none, radius: 0px, padding: 0px.

### Badge - Transparent Light
**Role:** Highlighted Tag

Text: Shelby Rose Dust (#FFDFEF), background: transparent, border: none, radius: 3.95833px, padding: 7.91667px 11.875px.

### Navigation Link
**Role:** Primary Navigation Element

Text: Shelby Rose Dust (#FFDFEF) for inactive, Shelby Hibiscus Pink (#FF77C9) for active. Font: SuisseIntl 10px, 400. Letter spacing normal. Underline on hover/active.

## Do's and Don'ts

### Do
- Use Shelby Hibiscus Pink (#FF77C9) exclusively for primary interactive elements and key brand accents to maximize impact.
- Maintain high contrast between text and backgrounds, pairing Shelby Cacao (#322312) with Shelby Rose Dust (#FFDFEF) or Shelby Hibiscus Pink (#FF77C9).
- Apply GT-Planar for all headings and substantial body text to leverage its distinctive weight variations and letter spacing.
- Employ the 3.95833px border-radius for buttons and badges, reserving the larger 9.89583px for cards to differentiate components.
- Ensure horizontal padding consistency with elementGap: 15px for most UI elements and cardPadding: 15px for internal card content.
- Transition `color`, `background-color`, and `filter` over 0.3s with `ease` timing for all interactive state changes.

### Don't
- Do not introduce new saturated colors outside of the defined brand and neutral palette to avoid visual clutter.
- Do not use generic system fonts; stick to GT-Planar, SuisseIntl, and ABCReproMono for all typography to maintain brand identity.
- Avoid using drop shadows for elevation; rely instead on background color changes to denote hierarchy and depth.
- Do not use letter-spacing values other than -0.0400em or -0.0200em for GT-Planar, and normal for other fonts.
- Do not vary border radii arbitrarily; adhere strictly to 3.95833px for small components and 9.89583px for cards.
- Do not use solid borders unless explicitly defined in a component variant (e.g., 1px bottom border for ghost buttons).

## Imagery

The site employs a mix of abstract graphics and illustrative elements, rather than photography or detailed product screenshots. These graphics feature blocky, geometric shapes, sometimes layered or angled, often using the brand's core colors (Shelby Hibiscus Pink, Shelby Cacao, Shelby Mauve). Icons are simple, outlined, and monochromatic, primarily used for functional clarity. Overall, imagery serves as decorative atmosphere or to subtly break up text, consistent with the abstract, technical yet bold brand identity. Density is moderate, supporting the text rather than dominating the visual space.

## Agent Prompt Guide

### Quick Color Reference
- **Text Primary (Dark BG):** Shelby Rose Dust (#FFDFEF)
- **Text Primary (Light BG):** Shelby Cacao (#322312)
- **Background Dark:** Shelby Cacao (#322312)
- **Background Light:** Shelby Rose Dust (#FFDFEF)
- **CTA Button BG:** Shelby Rose Dust (#FFDFEF)
- **CTA Button Text:** Shelby Hibiscus Pink (#FF77C9)
- **Brand Accent:** Shelby Hibiscus Pink (#FF77C9)

### 3-5 Example Component Prompts
1. **Create a hero section:** Background Shelby Cacao (#322312). Centered headline 'Where Others Store, Shelby Serves.' using GT-Planar 95px, weight 700 with letter-spacing -0.76px, and color Shelby Hibiscus Pink (#FF77C9). Below: a prominent Ghost Button - Hot Pink, with text 'Read Docs'. Add a subtle scroll indicator icon at the bottom center, in Shelby Rose Dust (#FFDFEF).
2. **Create a feature card:** Background Shelby Mauve (#FFC2E1), radius 5.9375px. Inside, a heading 'One data layer' using GT-Planar 22px, weight 500, color Shelby Cacao (#322312). Below, body text 'Every side of the AI workflow.' using GT-Planar 16px, weight 400, color Shelby Cacao (#322312).
3. **Create a horizontal navigation bar:** Background Shelby Cacao (#322312). Left-aligned logo (placeholder text 'Shelby' in GT-Planar 16px, weight 700, color Shelby Hibiscus Pink (#FF77C9)). Right-aligned navigation links: 'Meet Shelby', 'Calculator', 'Early Access', 'Use Cases' in SuisseIntl 10px, weight 400, color Shelby Rose Dust (#FFDFEF). Last item is a 'Read Docs' button, using the Filled Button - Plum component variant.
4. **Generate a badge:** Text 'BLOG' in ABCReproMono 12px, weight 400, color Shelby Rose Dust (#FFDFEF). Background transparent, radius 3.95833px, padding 7.91667px 11.875px.

## Similar Brands

- **Rive** — Dark UI with vibrant, specific accent colors and a strong focus on abstract, geometric visuals.
- **Neon** — Prominent use of a single, vibrant, complementary accent color against a dark or muted background for high visual pop.
- **Plaice.ai** — Heavy reliance on bold, custom typography and a distinct, limited color palette for brand recognition, often in dark mode.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-shelby-cacao: #322312;
  --color-shelby-rose-dust: #FFDFEF;
  --color-shelby-hibiscus-pink: #FF77C9;
  --color-shelby-plum: #470B64;
  --color-shelby-mauve: #FFC2E1;
  --color-shelby-lavender-mist: #EEE2FF;
  --color-shelby-deep-rose: #481D2A;
  --color-shelby-steel-grey: #5B4F41;

  /* Typography — Font Families */
  --font-times: 'Times', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gt-planar: 'GT-Planar', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-suisseintl: 'SuisseIntl', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-abcrepromono: 'ABCReproMono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1;
  --text-body: 16px;
  --leading-body: 1.2;
  --text-subheading: 18px;
  --leading-subheading: 1.2;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1.2;
  --text-heading: 42px;
  --leading-heading: 1.15;
  --tracking-heading: -0.42px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.15;
  --tracking-heading-lg: -0.48px;
  --text-display: 59px;
  --leading-display: 0.95;
  --tracking-display: -0.47px;
  --text-display-lg: 95px;
  --leading-display-lg: 0.9;
  --tracking-display-lg: -0.76px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-20: 20px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-116: 116px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 15px;
  --element-gap: 15px;

  /* Border Radius */
  --radius-md: 3.95833px;
  --radius-lg: 9.89583px;

  /* Named Radii */
  --radius-cards: 9.89583px;
  --radius-badges: 3.95833px;
  --radius-buttons: 3.95833px;
  --radius-default: 3.95833px;
  --radius-secondarybuttons: 11.875px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-shelby-cacao: #322312;
  --color-shelby-rose-dust: #FFDFEF;
  --color-shelby-hibiscus-pink: #FF77C9;
  --color-shelby-plum: #470B64;
  --color-shelby-mauve: #FFC2E1;
  --color-shelby-lavender-mist: #EEE2FF;
  --color-shelby-deep-rose: #481D2A;
  --color-shelby-steel-grey: #5B4F41;

  /* Typography */
  --font-times: 'Times', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gt-planar: 'GT-Planar', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-suisseintl: 'SuisseIntl', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-abcrepromono: 'ABCReproMono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1;
  --text-body: 16px;
  --leading-body: 1.2;
  --text-subheading: 18px;
  --leading-subheading: 1.2;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1.2;
  --text-heading: 42px;
  --leading-heading: 1.15;
  --tracking-heading: -0.42px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.15;
  --tracking-heading-lg: -0.48px;
  --text-display: 59px;
  --leading-display: 0.95;
  --tracking-display: -0.47px;
  --text-display-lg: 95px;
  --leading-display-lg: 0.9;
  --tracking-display-lg: -0.76px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-20: 20px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-116: 116px;

  /* Border Radius */
  --radius-md: 3.95833px;
  --radius-lg: 9.89583px;
}
```

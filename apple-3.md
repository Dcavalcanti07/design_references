# Apple — Style Reference
> Polished lens on innovation — clear, precise, and understated.

**Theme:** light

The Apple design system exudes a precise, almost ethereal clarity, like a perfectly polished lens focusing on content. Impeccable kerning and tracking, especially in headlines, create an understated authority. A subtle hierarchy of grays defines surfaces without heavy shadows, anchored by a vibrant yet contained blue for interaction. Product imagery is the hero, framed by minimal UI that gets out of the way.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Graphite | `#1d1d1f` | `--color-midnight-graphite` | Primary text, headline text, glyphs, and navigation elements. Near-black for maximum contrast on light backgrounds. |
| Deep Gray | `#333333` | `--color-deep-gray` | Secondary text and navigation elements, slightly softer than primary text. |
| Charcoal Grey | `#474747` | `--color-charcoal-grey` | Link text and navigation link text, indicating interactive elements. |
| Medium Gray | `#707070` | `--color-medium-gray` | Tertiary text, footer text, and subtle UI elements. Softer body copy. |
| Light Gray | `#858585` | `--color-light-gray` | Muted text for less prominent information, icon fills. |
| Light Silver | `#c7c7c7` | `--color-light-silver` | Subtle image box shadows, creating depth without heavy obscuration. |
| Border Silver | `#d6d6d6` | `--color-border-silver` | Thin, crisp border lines for UI separation. |
| Lightest Gray Background | `#e2e2e5` | `--color-lightest-gray-background` | Subtle background for UI components, hinting at separation. |
| Canvas White | `#f5f5f7` | `--color-canvas-white` | Dominant page background, primary canvas for content. The foundational light surface. |
| Pure White | `#ffffff` | `--color-pure-white` | Elevated UI elements, such as navigation backgrounds or contained content blocks, contrasting subtly with the primary canvas. |
| True Black | `#000000` | `--color-true-black` | Icon fills and occasional headline accents, providing maximum visual punch where needed. |
| Interactive Blue | `#0071e3` | `--color-interactive-blue` | Primary interactive element background, such as filled buttons and focus rings. A vivid, clear blue that signifies action. |
| Action Blue | `#0066cc` | `--color-action-blue` | Link color for interactive text and outline buttons. Slightly darker than Interactive Blue for text hierarchy. |
| Sky Blue Highlight | `#2997ff` | `--color-sky-blue-highlight` | Vivid blue for interactive states, highlighting links, buttons, and other active elements. Creates a bright, inviting focus. |
| Cerulean Shine | `#3397d4` | `--color-cerulean-shine` | Secondary accent color, used in specific graphic elements or backgrounds to provide visual variation. |
| Pale Blue Overlay | `#9fc6f4` | `--color-pale-blue-overlay` | Muted background for specific content sections, providing a soft color block. |
| Vibrant Orange | `#ec893c` | `--color-vibrant-orange` | Accent color for specific products or promotional blocks, providing a warm, energetic contrast. |
| Deep Plum | `#7424b5` | `--color-deep-plum` | Accent color for distinct content blocks, especially in content-rich sections like Apple TV. |
| Blush Pink | `#ea33c0` | `--color-blush-pink` | Accent color for branding specific products or content categories, often in playful, illustrative contexts. |
| Warm Taupe | `#604630` | `--color-warm-taupe` | Contextual background color, likely for specific product displays or themed sections. |
| Cool Teal | `#485b5` | `--color-cool-teal` | Contextual background or accent color, subtly introducing a cool, modern feel. |

## Tokens — Typography

### SF Pro Text — Primary typeface for body text, UI labels, buttons, navigation, and footer content. Its wide range of weights and optical sizing ensures clarity across all scales. The light weights maintain an airy feel, while regular and semi-bold provide structure. · `--font-sf-pro-text`
- **Substitute:** system-ui
- **Weights:** 300, 400, 600
- **Sizes:** 12px, 14px, 17px, 18px, 24px, 26px, 34px, 44px
- **Line height:** 1.00, 1.18, 1.24, 1.29, 1.33, 1.47, 1.50, 2.12, 2.41
- **Letter spacing:** -0.26, -0.24, -0.22, -0.19, -0.18, -0.15
- **Role:** Primary typeface for body text, UI labels, buttons, navigation, and footer content. Its wide range of weights and optical sizing ensures clarity across all scales. The light weights maintain an airy feel, while regular and semi-bold provide structure.

### SF Pro Display — Used for headlines and display-sized text. Optically calibrated for larger sizes, ensuring tight kerning and legibility. The 'numr' feature enforces numeral alignment, maintaining a consistent grid for numbers in headlines. · `--font-sf-pro-display`
- **Substitute:** system-ui
- **Weights:** 400, 600, 700
- **Sizes:** 21px, 28px, 40px, 56px
- **Line height:** 1.07, 1.10, 1.14, 1.19
- **Letter spacing:** -0.28, 0.29, 0.44
- **OpenType features:** `"numr"`
- **Role:** Used for headlines and display-sized text. Optically calibrated for larger sizes, ensuring tight kerning and legibility. The 'numr' feature enforces numeral alignment, maintaining a consistent grid for numbers in headlines.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.5 | -0.15px | `--text-caption` |
| body-sm | 14px | 1.47 | -0.18px | `--text-body-sm` |
| subheading | 18px | 1.24 | -0.22px | `--text-subheading` |
| callout | 21px | 1.19 | -0.28px | `--text-callout` |
| heading-sm | 24px | 1.33 | -0.24px | `--text-heading-sm` |
| heading-lg | 28px | 1.14 | 0.29px | `--text-heading-lg` |
| display-xl | 34px | 1 | -0.1px | `--text-display-xl` |
| display-xxl | 40px | 1.1 | 0.44px | `--text-display-xxl` |
| display-giant | 44px | 2.12 | — | `--text-display-giant` |
| display | 56px | 1.07 | -0.28px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 8 | 8px | `--spacing-8` |
| 12 | 12px | `--spacing-12` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 52 | 52px | `--spacing-52` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 0px |
| lists | 999px |
| images | 8px |
| inputs | 0px |
| buttons | 980px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| xl | `rgba(0, 0, 0, 0.22) 3px 5px 30px 0px` | `--shadow-xl` |

### Layout

- **Section gap:** 70px
- **Card padding:** 15px
- **Element gap:** 10px

## Components

### Primary Filled Button
**Role:** Call to action

Solid Interactive Blue background (#0071e3) with Pure White text (#ffffff), featuring a prominent 980px pill-shape radius. Padding of 11px vertical and 21px horizontal creates a generous, tappable area.

### Outline Link Button
**Role:** Secondary action or navigation

Transparent background (rgba(0, 0, 0, 0)) with Action Blue text (#0066cc) and a matching text-color border (rgb(0, 102, 204)). Uses the same 980px pill radius as the primary button with 11px vertical and 21px horizontal padding.

### Text Link Button
**Role:** Tertiary action, inline navigation

Transparent background with Midnight Graphite text (#1d1d1f). No explicit border or radius. Padding of 0px for compact inline use. Used for subtle interactions like 'Shop iPhone' next to a primary CTA.

### Unstyled Text Button
**Role:** Minimal interactive element for dense UI

Transparent background with rgba(0, 0, 0, 0.8) text. No explicit border, 0px radius, and 0px padding. Used in headers or inline for actions that don't need strong visual emphasis.

### Navigation Link
**Role:** Global navigation item

Transparent background and Midnight Graphite text (#1d1d1f), 0px radius. Varied padding, typically 8px, with 4px left margin on some items for horizontal spacing.

### Product Section Hero
**Role:** Main product introduction

Sections typically occupy full width. Headlines in SF Pro Display (e.g., 56px, weight 600) on Canvas White (#f5f5f7). Often features large product imagery directly below the headline, with minimal padding.

### Featured Content Card
**Role:** Showcasing media or specific products

Transparent background (rgba(0, 0, 0, 0)), 0px border-radius, no box shadow. Content is typically full-bleed within the card area, often with unique background colors or imagery as seen in Apple TV content blocks.

### Interactive Dropdown/Input
**Role:** User input or selection

Typically uses a light background (e.g., #e2e2e5), with Midnight Graphite text and a simple underline border when active. Focus state indicated by Interactive Blue (#2997ff) border or glow. Padding 8px.

## Do's and Don'ts

### Do
- Prioritize SF Pro Display for headlines (21px and up) with its specific letter spacing and 'numr' feature for numeral alignment.
- Use SF Pro Text for all body copy, UI labels, and navigation elements, leveraging different weights for hierarchy (e.g., 300 for captions, 400 for body, 600 for important labels).
- Apply 980px border-radius for all primary and secondary buttons, ensuring a consistent pill-shape aesthetic.
- Utilize Interactive Blue (#0071e3) as the default background for interactive elements and Action Blue (#0066cc) for link text.
- Maintain a clear visual hierarchy using the neutral color scale: Midnight Graphite (#1d1d1f) for primary text, Deep Gray (#333333) for secondary, and Medium Gray (#707070) for tertiary.
- Frame product imagery tightly, allowing the product to be the central visual element without excessive padding or decorative borders.
- Implement the 10px element gap for consistent vertical spacing between UI items and 15px card padding where applicable for internal content.

### Don't
- Avoid using harsh drop shadows; instead, suggest elevation through subtle background color shifts (e.g., Canvas White to Pure White) and a very light box-shadow like rgba(0, 0, 0, 0.22) 3px 5px 30px 0px for images.
- Do not deviate from the established pill-shape radius for buttons; rounded rectangles or sharp corners are reserved for specific components like image containers (8px).
- Refrain from using heavily saturated colors for backgrounds unless it is a specific accent area or product showcase as defined by the accent palette.
- Do not introduce decorative borders or heavy strokes around primary content blocks or cards; opt for clean edges or subtle background shifts.
- Avoid excessive letter spacing on body or caption text; maintain the precise, optically balanced tracking values defined in the typography section.
- Do not use generic system default link styles; ensure all links use Action Blue (#0066cc) and inherit SF Pro Text styling.
- Do not introduce extraneous visual elements that compete with product imagery; the UI should be understated and serve to highlight the content.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas White | `#f5f5f7` | Dominant page background, providing a clean, bright foundation for all content. |
| 1 | Pure White | `#ffffff` | Elevated UI elements, such as navigation backgrounds and certain content blocks, creating a subtle contrast against the primary canvas. |
| 2 | Lightest Gray Background | `#e2e2e5` | Subtle background for interactive elements or contained components, indicating a slightly recessed or grouped area. |
| 3 | Pale Blue Overlay | `#9fc6f4` | Accent surface for specific sections or product narratives, introducing a soft, branded color block. |

## Elevation

- **Product Image Card:** `rgba(0, 0, 0, 0.22) 3px 5px 30px 0px`

## Imagery

The imagery system is product-centric and highly polished. Photography primarily features isolated product shots on clean white backgrounds, often at slightly varied angles or in different colors, making the product the singular focus. There is a strong absence of lifestyle or abstract photography. Iconography is monochromatic, usually in Midnight Graphite or True Black, with a fine stroke weight, integrating seamlessly into the minimalist UI. Graphic elements, when present (e.g., for Apple TV previews), use vibrant, full-color treatments within contained sections, acting as self-contained visual narratives.

## Layout

The page primarily employs a max-width contained layout, though specific hero sections and content blocks can extend full-bleed. The hero pattern prominently features a centered headline over a background that shifts between the dominant light mode or product imagery. Sections maintain a consistent vertical rhythm, with ample Canvas White space between distinct content blocks. Content is typically arranged in centered stacks, often with large product images dominating the visual field, followed by explanatory text. Some sections utilize a two-column layout for text and imagery or multi-column grids for featured products and content. The layout emphasizes spaciousness, ensuring each product or content block has visual breathing room. A sticky top navigation bar provides global access to main categories.

## Agent Prompt Guide

Quick Color Reference:
- Text Primary: #1d1d1f (Midnight Graphite)
- Background Canvas: #f5f5f7 (Canvas White)
- Call To Action: #0071e3 (Interactive Blue)
- Border/Divider: #d6d6d6 (Border Silver)
- Link/Outline Button: #0066cc (Action Blue)

Example Component Prompts:
1. Create a hero section: Canvas White background (#f5f5f7). Headline 'iPhone' at 56px SF Pro Display weight 600, #1d1d1f, letter-spacing -0.28px. Subhead 'Meet the latest iPhone lineup.' at 24px SF Pro Text weight 400, #1d1d1f, letter-spacing -0.24px. Stack with two buttons: 'Learn more' (Primary Filled Button) and 'Shop iPhone' (Outline Link Button), with 10px element gap. Product image occupies the bottom half of the screen.
2. Design a navigation bar: Pure White background (#ffffff). Main navigation links (e.g., 'iPhone', 'Mac') at 14px SF Pro Text weight 400, #1d1d1f, with 8px horizontal padding and 4px left margin. Apple logo icon #000000. Right-aligned search and bag icons in #1d1d1f.
3. Create a secondary content block: Pale Blue Overlay background (#9fc6f4). Headline 'iPad air' at 40px SF Pro Display weight 600, #1d1d1f, letter-spacing 0.44px. Subtitle 'Now supercharged by M4.' at 24px SF Pro Text weight 400, #1d1d1f, letter-spacing -0.24px. Centered. Below, a 'Learn more' (Primary Filled Button) and 'Buy' (Outline Link Button) with 10px element gap.

## Similar Brands

- **Google** — Both brands utilize a very clean, bright UI with ample whitespace and precise typography to convey clarity and simplicity. Interaction is primarily driven by a single, prominent brand color.
- **Samsung** — Similar focus on product-forward imagery with clean, unobtrusive UI elements. Both adopt a modern, neutral-heavy palette with a single primary accent for interaction.
- **Microsoft** — Employs a systematic approach to typography and spacing, featuring clean lines and a strong visual hierarchy. Interaction is often guided by a specific brand color against a backdrop of whites and grays.
- **Linear** — Shares a precise, almost clinical attention to typography details, especially letter spacing, and a minimalist aesthetic where UI elements are functional and recede to highlight content.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-graphite: #1d1d1f;
  --color-deep-gray: #333333;
  --color-charcoal-grey: #474747;
  --color-medium-gray: #707070;
  --color-light-gray: #858585;
  --color-light-silver: #c7c7c7;
  --color-border-silver: #d6d6d6;
  --color-lightest-gray-background: #e2e2e5;
  --color-canvas-white: #f5f5f7;
  --color-pure-white: #ffffff;
  --color-true-black: #000000;
  --color-interactive-blue: #0071e3;
  --color-action-blue: #0066cc;
  --color-sky-blue-highlight: #2997ff;
  --color-cerulean-shine: #3397d4;
  --color-pale-blue-overlay: #9fc6f4;
  --color-vibrant-orange: #ec893c;
  --color-deep-plum: #7424b5;
  --color-blush-pink: #ea33c0;
  --color-warm-taupe: #604630;
  --color-cool-teal: #485b5;

  /* Typography — Font Families */
  --font-sf-pro-text: 'SF Pro Text', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sf-pro-display: 'SF Pro Display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: -0.15px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.47;
  --tracking-body-sm: -0.18px;
  --text-subheading: 18px;
  --leading-subheading: 1.24;
  --tracking-subheading: -0.22px;
  --text-callout: 21px;
  --leading-callout: 1.19;
  --tracking-callout: -0.28px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.33;
  --tracking-heading-sm: -0.24px;
  --text-heading-lg: 28px;
  --leading-heading-lg: 1.14;
  --tracking-heading-lg: 0.29px;
  --text-display-xl: 34px;
  --leading-display-xl: 1;
  --tracking-display-xl: -0.1px;
  --text-display-xxl: 40px;
  --leading-display-xxl: 1.1;
  --tracking-display-xxl: 0.44px;
  --text-display-giant: 44px;
  --leading-display-giant: 2.12;
  --text-display: 56px;
  --leading-display: 1.07;
  --tracking-display: -0.28px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-52: 52px;

  /* Layout */
  --section-gap: 70px;
  --card-padding: 15px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-lg-2: 11px;
  --radius-full: 980px;
  --radius-full-2: 999px;

  /* Named Radii */
  --radius-cards: 0px;
  --radius-lists: 999px;
  --radius-images: 8px;
  --radius-inputs: 0px;
  --radius-buttons: 980px;

  /* Shadows */
  --shadow-xl: rgba(0, 0, 0, 0.22) 3px 5px 30px 0px;

  /* Surfaces */
  --surface-canvas-white: #f5f5f7;
  --surface-pure-white: #ffffff;
  --surface-lightest-gray-background: #e2e2e5;
  --surface-pale-blue-overlay: #9fc6f4;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-graphite: #1d1d1f;
  --color-deep-gray: #333333;
  --color-charcoal-grey: #474747;
  --color-medium-gray: #707070;
  --color-light-gray: #858585;
  --color-light-silver: #c7c7c7;
  --color-border-silver: #d6d6d6;
  --color-lightest-gray-background: #e2e2e5;
  --color-canvas-white: #f5f5f7;
  --color-pure-white: #ffffff;
  --color-true-black: #000000;
  --color-interactive-blue: #0071e3;
  --color-action-blue: #0066cc;
  --color-sky-blue-highlight: #2997ff;
  --color-cerulean-shine: #3397d4;
  --color-pale-blue-overlay: #9fc6f4;
  --color-vibrant-orange: #ec893c;
  --color-deep-plum: #7424b5;
  --color-blush-pink: #ea33c0;
  --color-warm-taupe: #604630;
  --color-cool-teal: #485b5;

  /* Typography */
  --font-sf-pro-text: 'SF Pro Text', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sf-pro-display: 'SF Pro Display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: -0.15px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.47;
  --tracking-body-sm: -0.18px;
  --text-subheading: 18px;
  --leading-subheading: 1.24;
  --tracking-subheading: -0.22px;
  --text-callout: 21px;
  --leading-callout: 1.19;
  --tracking-callout: -0.28px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.33;
  --tracking-heading-sm: -0.24px;
  --text-heading-lg: 28px;
  --leading-heading-lg: 1.14;
  --tracking-heading-lg: 0.29px;
  --text-display-xl: 34px;
  --leading-display-xl: 1;
  --tracking-display-xl: -0.1px;
  --text-display-xxl: 40px;
  --leading-display-xxl: 1.1;
  --tracking-display-xxl: 0.44px;
  --text-display-giant: 44px;
  --leading-display-giant: 2.12;
  --text-display: 56px;
  --leading-display: 1.07;
  --tracking-display: -0.28px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-52: 52px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-lg-2: 11px;
  --radius-full: 980px;
  --radius-full-2: 999px;

  /* Shadows */
  --shadow-xl: rgba(0, 0, 0, 0.22) 3px 5px 30px 0px;
}
```

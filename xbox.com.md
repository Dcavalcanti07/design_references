# Xbox.com — Style Reference
> Gaming console interface on a bright white canvas. Bold green accents against a stark white backdrop, with minimal rounded elements.

**Theme:** light

The Xbox.com design system is a high-contrast, energetic experience that balances deep digital visuals with striking lime accents. Dominant dark imagery is anchored by a stark white background and punctuated by vivid green calls to action, creating an immediate sense of urgency and gaming excitement. A rigid, square aesthetic through hard edges pervades the interface, reflecting the precision and digital nature of console gaming.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Lumi Green | `#107c10` | `--color-lumi-green` | Primary brand color, used for prominent buttons, interactive elements, and branding accents. Conveys energy and interactivity. |
| Rich Meadow | `#054b16` | `--color-rich-meadow` | Darker tone of Lumi Green, used for text on Lumi Green backgrounds and in combination with other greens to add depth. |
| Electric Lime | `#9bf00b` | `--color-electric-lime` | Background for secondary interactive elements, providing a vibrant, almost neon highlight. Often paired with Rich Meadow text. |
| Cyber Yellow | `#ffd800` | `--color-cyber-yellow` | Accents for badges and warning-like notifications, drawing immediate attention. |
| Deep Space Blue | `#0066ff` | `--color-deep-space-blue` | Illustration accent, appearing as an indicator or highlight within complex graphics. |
| Absolute Zero | `#000000` | `--color-absolute-zero` | Primary text, headers, and icon color. Provides maximum contrast against light backgrounds. |
| Snowfield White | `#ffffff` | `--color-snowfield-white` | Page backgrounds, card surfaces, and primary button text. The dominant background color. |
| Charcoal Depth | `#333333` | `--color-charcoal-depth` | Secondary text and backgrounds in dark content blocks. Used for subtle contrast against darker photographic elements. |
| Whisper Gray | `#f2f2f2` | `--color-whisper-gray` | Subtle background for footer and other less prominent sections, acting as an off-white contrast. |
| Dark Steel | `#616161` | `--color-dark-steel` | Subtle text and icon elements in navigation and body text, for a less stark contrast than Absolute Zero. |
| Onyx Shadow | `#262626` | `--color-onyx-shadow` | Link colors and button text on light green backgrounds, for high readability with a touch of softness compared to pure black. |

## Tokens — Typography

### Segoe UI — Primary type for all UI elements: navigation, body text, general links, buttons, and most headings. Its clean, geometric form supports both readability and a digital aesthetic, with subtle letter-spacing variations to optimize readability at extreme sizes. · `--font-segoe-ui`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400, 600, 700
- **Sizes:** 11px, 13px, 15px, 16px, 20px, 24px, 46px
- **Line height:** 1.20, 1.22, 1.25, 1.33, 1.45, 1.50, 2.27
- **Letter spacing:** -1.0em at 46px, 0.75em at 11px, normal otherwise
- **Role:** Primary type for all UI elements: navigation, body text, general links, buttons, and most headings. Its clean, geometric form supports both readability and a digital aesthetic, with subtle letter-spacing variations to optimize readability at extreme sizes.

### SegoeProBlack — Used for specific call-to-action buttons and emphasized links. Its heavier weight provides immediate visual pop, contrasting with the lighter Segoe UI for key interactive elements. · `--font-segoeproblack`
- **Substitute:** system-ui, sans-serif
- **Weights:** 600, 900
- **Sizes:** 15px
- **Line height:** 1.23, 1.30, 1.53
- **Role:** Used for specific call-to-action buttons and emphasized links. Its heavier weight provides immediate visual pop, contrasting with the lighter Segoe UI for key interactive elements.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 11px | 1.45 | 0.75px | `--text-caption` |
| heading | 20px | 1.22 | — | `--text-heading` |
| heading-lg | 24px | 1.22 | — | `--text-heading-lg` |
| display | 46px | 1.2 | -1px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 5 | 5px | `--spacing-5` |
| 6 | 6px | `--spacing-6` |
| 7 | 7px | `--spacing-7` |
| 8 | 8px | `--spacing-8` |
| 10 | 10px | `--spacing-10` |
| 12 | 12px | `--spacing-12` |
| 14 | 14px | `--spacing-14` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 25 | 25px | `--spacing-25` |
| 30 | 30px | `--spacing-30` |
| 43 | 43px | `--spacing-43` |
| 50 | 50px | `--spacing-50` |
| 71 | 71px | `--spacing-71` |

### Border Radius

| Element | Value |
|---------|-------|
| default | 0px |

### Layout

- **Section gap:** 48-80px
- **Card padding:** 12px
- **Element gap:** 4-12px

## Components

### Primary Navigation Link
**Role:** Top-level navigation items

Segoe UI 400 at 15px, Absoulte Zero text. No background, no border, with 16px vertical and 12-30px horizontal padding. Underlines on hover/active.

### Text Link Button
**Role:** Secondary action button, typically below a primary CTA

Background: transparent. Text: Absolute Zero (#000000). Segoe UI 600 at 16px. 15px top, 30px bottom padding. 9px horizontal padding. No border-radius. Visible bottom border on hover/active.

### Hero Overlay Button
**Role:** Call-to-action over dark hero imagery

Background: rgba(0, 0, 0, 0.4). Text: Snowfield White (#ffffff). Segoe UI 400 at 15px. 6px top, 8px bottom padding. 0px horizontal padding. No border, 0px border-radius.

## Do's and Don'ts

### Do
- Prioritize Lumi Green (#107c10) for primary calls to action to maintain brand visibility and urgency.
- Use Electric Lime (#9bf00b) purely for secondary interactive backgrounds, such as 'Game Pass' buttons, ensuring high contrast with Rich Meadow (#054b16) text.
- Maintain a rigid 0px border-radius for all interactive components (buttons, badges) to reinforce the sharp, digital aesthetic.
- Employ Absolute Zero (#000000) for all main text and headings on light backgrounds to maximize readability and impact.
- Leverage the Segoe UI font family for most textual content, varying weights from 400 to 700 to establish hierarchy without introducing new typefaces.
- Utilize a compact spacing density, frequently using 4px to 12px for element gaps to keep information tightly packed and immersive.

### Don't
- Avoid using rounded corners on any primary UI elements; the brand relies on a sharp, zero-radius aesthetic.
- Do not use generic blue as an interactive color; reserve Deep Space Blue (#0066ff) for specific illustration accents only.
- Refrain from using shadow-based elevation; depth is created through color contrast and layered sections, not drop shadows.
- Do not introduce additional font families beyond Segoe UI and SegoeProBlack; the type system is intentionally constrained for a consistent brand voice.
- Avoid using low-contrast text-on-background combinations; always ensure AAA or at least AA accessibility standards are met with high contrast pairs.
- Do not soften or desaturate brand greens; the vibrant, vivid nature of Lumi Green and Electric Lime is key to the energetic gaming feel.

## Imagery

The visual language of Xbox.com is dominated by high-fidelity, dramatic game key art and product photography. Photography is full-bleed in hero sections, often dark and moody, setting an immersive tone. Further down the page, game covers are presented in a grid-like structure, tightly cropped with sharp edges. Illustrations, when present, are colorful and detailed, serving to explain features or showcase game worlds. Icons are simple, outlined, and monochromatic (Lumi Green or black), functioning as functional navigation elements. The imagery's role is primarily decorative for atmosphere and explanatory for product features, featuring a high density of visual content to captivate the user, with product shots often featuring gaming hardware like controllers, emphasizing the tactile experience.

## Layout

The site uses a full-bleed layout for its hero section, featuring a large, dark background image with central text and calls to action. Subsequent sections alternate between full-width content blocks and contained grids, effectively segmenting information. Content arrangement is often asymmetrical, with text blocks adjacent to large visuals (text-left/image-right is common) creating dynamic compositions. A 3-column card grid is frequently used for displaying game titles, creating a dense yet organized presentation. The navigation is a sticky header bar at the top, maintaining constant access to core functionality. Overall density is compact, ensuring a wealth of information is visible without excessive scrolling, particularly in product grids.

## Agent Prompt Guide

### Quick Color Reference
- Text: #000000 (Absolute Zero)
- Background: #ffffff (Snowfield White)
- CTA Primary: #107c10 (Lumi Green)
- CTA Secondary: #9bf00b (Electric Lime)
- Badge: #ffd800 (Cyber Yellow)

### Example Component Prompts
1. Create a primary navigation item: text 'Juegos' in Segoe UI weight 400, size 15px, color Absolute Zero (#000000). No background or border. On hover, apply an underline.
2. Design a 'Game Pass' call-to-action button: background Electric Lime (#9bf00b), text 'ÚNETE A GAME PASS' in SegoeProBlack weight 900, size 15px, color Rich Meadow (#054b16). It has 5px vertical padding and 20px horizontal padding. No border or border-radius.
3. Generate a 'New Season' badge: background Cyber Yellow (#ffd800), text 'NUEVA TEMPORADA' in Segoe UI weight 400, size 13px, color Absolute Zero (#000000). Padding is 1px top/bottom and 7px left/right. 0px border-radius.
4. Create a hero section with a dark image background that has a rgba(0,0,0,0.4) overlay. The heading is 'Call of Duty®: Black Ops 7' in Segoe UI weight 600, size 46px, color Snowfield White (#ffffff), letter-spacing -1.0px. Below it is a description in Segoe UI weight 400, size 20px, color Snowfield White (#ffffff). Include the 'Game Pass CTA Button' centered below the text ensemble.

## Similar Brands

- **PlayStation Store** — High-contrast hero sections with large game art, similar focus on digital game titles and strong CTAs on a light background.
- **Steam** — Heavy emphasis on game artwork alongside critical information and CTA buttons, and high-contrast text on varied backgrounds.
- **Epic Games Store** — Large, immersive imagery for game titles, combined with bold typography and clear, often colored, calls to action to drive purchases.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-lumi-green: #107c10;
  --color-rich-meadow: #054b16;
  --color-electric-lime: #9bf00b;
  --color-cyber-yellow: #ffd800;
  --color-deep-space-blue: #0066ff;
  --color-absolute-zero: #000000;
  --color-snowfield-white: #ffffff;
  --color-charcoal-depth: #333333;
  --color-whisper-gray: #f2f2f2;
  --color-dark-steel: #616161;
  --color-onyx-shadow: #262626;

  /* Typography — Font Families */
  --font-segoe-ui: 'Segoe UI', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-segoeproblack: 'SegoeProBlack', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.45;
  --tracking-caption: 0.75px;
  --text-heading: 20px;
  --leading-heading: 1.22;
  --text-heading-lg: 24px;
  --leading-heading-lg: 1.22;
  --text-display: 46px;
  --leading-display: 1.2;
  --tracking-display: -1px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;
  --font-weight-black: 900;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-14: 14px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-25: 25px;
  --spacing-30: 30px;
  --spacing-43: 43px;
  --spacing-50: 50px;
  --spacing-71: 71px;

  /* Layout */
  --section-gap: 48-80px;
  --card-padding: 12px;
  --element-gap: 4-12px;

  /* Named Radii */
  --radius-default: 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-lumi-green: #107c10;
  --color-rich-meadow: #054b16;
  --color-electric-lime: #9bf00b;
  --color-cyber-yellow: #ffd800;
  --color-deep-space-blue: #0066ff;
  --color-absolute-zero: #000000;
  --color-snowfield-white: #ffffff;
  --color-charcoal-depth: #333333;
  --color-whisper-gray: #f2f2f2;
  --color-dark-steel: #616161;
  --color-onyx-shadow: #262626;

  /* Typography */
  --font-segoe-ui: 'Segoe UI', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-segoeproblack: 'SegoeProBlack', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.45;
  --tracking-caption: 0.75px;
  --text-heading: 20px;
  --leading-heading: 1.22;
  --text-heading-lg: 24px;
  --leading-heading-lg: 1.22;
  --text-display: 46px;
  --leading-display: 1.2;
  --tracking-display: -1px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-14: 14px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-25: 25px;
  --spacing-30: 30px;
  --spacing-43: 43px;
  --spacing-50: 50px;
  --spacing-71: 71px;
}
```

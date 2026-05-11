# EPIC agency — Style Reference
> Deep-space command center. A shimmering violet expanse punctuated by crisp text and glowing 3D objects.

**Theme:** dark

This design system is a deep-space exploration vehicle, navigating the cosmos with subtle ambient light. The rich, desaturated violet background creates an immediate sense of depth and luxury, providing a canvas for crisp typography and controlled luminance. Geometric 3D illustrations serve as glowing constellations, guiding the user through an experience that feels both futuristic and intimately crafted. Typography plays a central role; the elegant `Sang Bleu` display font is an immediate visual signature.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Nebula Violet | `#271a47` | `--color-nebula-violet` | Page backgrounds, section surfaces, primary interactive button fills. |
| Stardust Shimmer | `#dbc9ff` | `--color-stardust-shimmer` | Primary text color for headlines and body, interactive button text, icon outlines — providing high contrast against the dark background. |
| Cosmos Black | `#000000` | `--color-cosmos-black` | Used for specific interactive elements such as `Play Video` button background and text, creating isolated points of absolute darkness. |
| Galactic Gold | `#bc994` | `--color-galactic-gold` | Used for secondary links and iconic accents, signaling complementary information or actions without competing with primary CTAs. |

## Tokens — Typography

### Inter — Primary body text, navigation elements, button labels, and secondary interactive components. Its precise metrics ensure readability even at smaller sizes, contrasting with the more decorative display font. · `--font-inter`
- **Substitute:** Inter
- **Weights:** 400, 600, 700
- **Sizes:** 10px, 11px, 13px, 14px, 16px, 18px
- **Line height:** 1.00, 1.33, 1.40, 1.56, 1.65, 1.70, 3.00
- **Letter spacing:** 0.0360em (10px), 0.1110em (13px), 0.5000em (smaller, all caps)
- **Role:** Primary body text, navigation elements, button labels, and secondary interactive components. Its precise metrics ensure readability even at smaller sizes, contrasting with the more decorative display font.

### Sang Bleu — Display headlines and hero text. This custom, highly stylized serif font provides the primary visual identity, signaling sophistication and unique brand voice through its generous sizing and elegant forms. · `--font-sang-bleu`
- **Substitute:** Playfair Display
- **Weights:** 400, 700, 900
- **Sizes:** 42px, 80px, 120px
- **Line height:** 1.00, 1.20, 1.65
- **Role:** Display headlines and hero text. This custom, highly stylized serif font provides the primary visual identity, signaling sophistication and unique brand voice through its generous sizing and elegant forms.

## Tokens — Spacing & Shapes

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 5 | 5px | `--spacing-5` |
| 6 | 6px | `--spacing-6` |
| 7 | 7px | `--spacing-7` |
| 10 | 10px | `--spacing-10` |
| 12 | 12px | `--spacing-12` |
| 14 | 14px | `--spacing-14` |
| 15 | 15px | `--spacing-15` |
| 18 | 18px | `--spacing-18` |
| 20 | 20px | `--spacing-20` |
| 32 | 32px | `--spacing-32` |
| 50 | 50px | `--spacing-50` |
| 80 | 80px | `--spacing-80` |
| 117 | 117px | `--spacing-117` |
| 120 | 120px | `--spacing-120` |

### Border Radius

| Element | Value |
|---------|-------|
| buttons | 20px, 30px |
| general | 10px |
| menu-items | 0px |

### Layout

- **Page max-width:** 1200px
- **Section gap:** 32px
- **Card padding:** 12-18px

## Components

### Primary Ghost Button
**Role:** Interactive element

Outline-style button for 'Visit project' and similar calls to action. Text color: Stardust Shimmer (#dbc9ff). Border color: Stardust Shimmer (#dbc9ff). Background: transparent. Border radius: 30px. Padding around text: approximately 3.85px vertical, 13.75px horizontal. Font: Inter, semibold.

### Secondary Ghost Button
**Role:** Interactive element

Used for 'See all projects' and similar secondary actions. Text color: Stardust Shimmer (#dbc9ff). Background: transparent. Border is absent, implicit interactiveness. Font: Inter, semibold.

### Nav Dropdown Button
**Role:** Interactive element

Dropdown trigger, e.g., language selector. Text color: Nebula Violet (#271a47). Background: transparent. Padding: 10px on all sides. Border is absent. Font: Inter, normal.

### Filled Play Button
**Role:** Interactive element

Circular button for 'Play Video'. Background color: Nebula Violet (#271a47). Text color: Stardust Shimmer (#dbc9ff). Border radius: 20px. Padding around text: 4px vertical, 12px horizontal. Font: Inter, normal.

### Journal Entry Link
**Role:** Navigation/information

Lists individual journal entries. Text color: Stardust Shimmer (#dbc9ff) for title, Galactic Gold (#bc994e) for 'Read' link. Font: Inter at various weights.

### Header Navigation Item
**Role:** Global navigation

Top-level menu items. Text color: Stardust Shimmer (#dbc9ff). Font: Inter, normal. Underline is absent on hover. Each item appears as simple text.

## Do's and Don'ts

### Do
- Prioritize Nebula Violet (#271a47) for backgrounds to maintain the deep and immersive atmosphere.
- Use Stardust Shimmer (#dbc9ff) as the primary text and interactive element color for high contrast against dark elements.
- Employ Sang Bleu (substitute Playfair Display) for all display-size headlines (42px, 80px, 120px) to establish brand identity.
- Ensure all interactive components like buttons and links use either 20px or 30px border-radius, maintaining a soft, approachable feel.
- Utilize Galactic Gold (#bc994e) sparingly for secondary links or subtle accent details, preventing visual noise.
- Maintain a compact density with element gaps typically at 4px, 10px, or 15px to keep content focused.

### Don't
- Avoid using bright or overly saturated colors that would disrupt the muted, celestial palette.
- Do not introduce sharp, angular radii on interactive elements; favor the established 20px or 30px curves.
- Refrain from heavy drop shadows or glows; depth is primarily achieved through color layering and 3D illustration rather than strong elevation.
- Do not use generic system fonts for headlines; the distinctiveness of Sang Bleu is paramount for brand recognition.
- Avoid large, open areas of white or light backgrounds; the dark theme is central to the visual identity.
- Do not mix 'Inter' with 'Sang Bleu' in body text or for secondary labels; their roles are strictly separated.

## Imagery

The visual language is dominated by 3D rendered illustrations. These are geometric, abstract yet representational (rocket ships, trophies, drones, satellites), and feature soft, diffused light against the dark background. Their role is primarily decorative and atmospheric, creating a sense of wonder and advanced technology without being photorealistic. Icons, where present, are typically outlined or filled in Stardust Shimmer (#dbc9ff), maintaining the UI's color palette. There is a high density of imagery in the hero section, framing the text, but later sections become more text-dominant while retaining illustrative flourishes. Imagery is contained, not full-bleed, and often integrates with the layout rather than overlapping elements.

## Layout

The page primarily follows a max-width contained model (around 1200px) with content centered. The hero section is full-bleed with a dark Nebula Violet background, featuring a large, centered headline and a complex 3D illustration that grounds the design. Subsequent sections maintain consistent vertical spacing, often presenting content in stacked blocks or simple two-column arrangements (e.g., journal list alongside a headline). There's no evident alternating light/dark banding; the dark theme is consistent. Navigation is a minimalist top bar with a logo and simple text links, becoming a dropdown menu on smaller breakpoints. The overall density is relatively compact.

## Agent Prompt Guide

### Quick Color Reference
- Text (Primary): #dbc9ff
- Background (Primary): #271a47
- CTA Button (Outline/Text): #dbc9ff
- Accent (Links): #bc994e
- Interactive Fill (Secondary): #000000

### Example Component Prompts
1. Create a hero section with a Nebula Violet (#271a47) background. Place a hero headline 'Digital Wallonia Landing Pages' using Sang Bleu (Playfair Display) at 120px weight 900, color Stardust Shimmer (#dbc9ff). Below this, add a ghost button 'Visit project' with text color #dbc9ff, 30px border-radius, transparent background, and a #dbc9ff border around the text, using Inter font at 16px. Ensure compact padding.
2. Design a journal entry block: Background Nebula Violet (#271a47). Title 'Captain Goosebumps' using Inter 16px weight 700, color #dbc9ff. Date '13 October 2025' using Inter 13px weight 400, color #dbc9ff. Add a right-aligned 'Read' link in Galactic Gold (#bc994e) using Inter 13px weight 400.
3. Implement a primary CTA button component: Text 'Learn More' using Inter 14px weight 600, color #dbc9ff. Background Nebula Violet (#271a47). Border radius: 20px. Padding: 4px vertical, 12px horizontal.
4. Create a top navigation bar. Background Nebula Violet (#271a47). Left-aligned logo placeholder. Right-aligned text link 'Imagine, Build, Tell.' using Inter 14px weight 400, color #dbc9ff. Next to it, an 'EN' language dropdown button, with text 'EN' using Inter 14px, #dbc9ff, transparent background, and 10px padding all around. No borders.

## Similar Brands

- **Linear** — Shares a dark, elegant UI with deliberate use of accent colors and sharp, purposeful typography.
- **Framer** — Uses abstract 3D illustrations and a sophisticated dark theme to convey a sense of modern, creative technology.
- **Awwwards Nominees (many)** — Draws parallels with high-end digital agency sites prioritizing unique display typography and atmospheric dark themes with minimalist interactions.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-nebula-violet: #271a47;
  --color-stardust-shimmer: #dbc9ff;
  --color-cosmos-black: #000000;
  --color-galactic-gold: #bc994;

  /* Typography — Font Families */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sang-bleu: 'Sang Bleu', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-xs: 10px;
  --leading-xs: 3;
  --text-xs-2: 11px;
  --leading-xs-2: 1.65;
  --text-sm: 13px;
  --leading-sm: 1.65;
  --text-sm-2: 14px;
  --leading-sm-2: 1.65;
  --text-base: 16px;
  --leading-base: 1.56;
  --text-lg: 18px;
  --leading-lg: 1.65;
  --text-4xl: 42px;
  --leading-4xl: 1.65;
  --text-5xl: 80px;
  --leading-5xl: 1;
  --text-5xl-2: 120px;
  --leading-5xl-2: 1.2;

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
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-14: 14px;
  --spacing-15: 15px;
  --spacing-18: 18px;
  --spacing-20: 20px;
  --spacing-32: 32px;
  --spacing-50: 50px;
  --spacing-80: 80px;
  --spacing-117: 117px;
  --spacing-120: 120px;

  /* Layout */
  --page-max-width: 1200px;
  --section-gap: 32px;
  --card-padding: 12-18px;

  /* Border Radius */
  --radius-lg: 10px;
  --radius-2xl: 20px;
  --radius-3xl: 30px;

  /* Named Radii */
  --radius-buttons: 20px, 30px;
  --radius-general: 10px;
  --radius-menu-items: 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-nebula-violet: #271a47;
  --color-stardust-shimmer: #dbc9ff;
  --color-cosmos-black: #000000;
  --color-galactic-gold: #bc994;

  /* Typography */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sang-bleu: 'Sang Bleu', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-xs: 10px;
  --leading-xs: 3;
  --text-xs-2: 11px;
  --leading-xs-2: 1.65;
  --text-sm: 13px;
  --leading-sm: 1.65;
  --text-sm-2: 14px;
  --leading-sm-2: 1.65;
  --text-base: 16px;
  --leading-base: 1.56;
  --text-lg: 18px;
  --leading-lg: 1.65;
  --text-4xl: 42px;
  --leading-4xl: 1.65;
  --text-5xl: 80px;
  --leading-5xl: 1;
  --text-5xl-2: 120px;
  --leading-5xl-2: 1.2;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-7: 7px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-14: 14px;
  --spacing-15: 15px;
  --spacing-18: 18px;
  --spacing-20: 20px;
  --spacing-32: 32px;
  --spacing-50: 50px;
  --spacing-80: 80px;
  --spacing-117: 117px;
  --spacing-120: 120px;

  /* Border Radius */
  --radius-lg: 10px;
  --radius-2xl: 20px;
  --radius-3xl: 30px;
}
```

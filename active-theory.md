# Active Theory — Style Reference
> Midnight Command Console. Deep, dark surfaces punctuated by precise, glowing UI elements.

**Theme:** dark

This design system evokes a 'digital void' aesthetic, combining deep, dark backgrounds with subtle luminous elements. The sparsity of color and reliance on grayscale with minimal violet accents creates an atmosphere of focused, almost melancholic, precision. Custom typography and specific rounded forms (500px pill buttons contrasting with 5px or 12px radii elsewhere) carve out a unique identity, suggesting advanced technology with a touch of crafted elegance.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Void Black | `#000000` | `--color-void-black` | Primary background for pages and most components, creating a deep canvas for sparse UI elements. |
| Ash Gray | `#4d4d4d` | `--color-ash-gray` | Subtle borders and minor UI elements, providing minimal contrast against Void Black. |
| Pure White | `#ffffff` | `--color-pure-white` | Primary text color, ensuring AAA contrast against dark backgrounds; also used for active states. |
| Silver Mist | `#c6c6c6` | `--color-silver-mist` | Secondary text color, like links or non-critical information, offering softer readability than Pure White. |
| Subtle Violet | `#343755` | `--color-subtle-violet` | Rare background tint for interactive elements, lending a muted, almost invisible brand presence. |
| Highlight Violet | `#9cA5FF` | `--color-highlight-violet` | Interactive elements, providing a soft glow that signals hover or active states without being overtly bright. Note: this color is only seen with transparency (33%) and is derived from `rgba(156, 165, 255, 0.333)` as the base color. |

## Tokens — Typography

### nbarchitekt — The primary typeface for UI elements, body text, and prominent links. Its custom nature gives the interface a distinct, technically precise feel at smaller sizes and a bold presence at larger weights. Weight 700 is reserved for key labels and headings, while weight 400 maintains legibility for body and interactive components. · `--font-nbarchitekt`
- **Substitute:** Montserrat
- **Weights:** 400, 700
- **Sizes:** 10px, 12px, 14px
- **Line height:** 1.20, 1.50, 3.00
- **Role:** The primary typeface for UI elements, body text, and prominent links. Its custom nature gives the interface a distinct, technically precise feel at smaller sizes and a bold presence at larger weights. Weight 700 is reserved for key labels and headings, while weight 400 maintains legibility for body and interactive components.

### Arial — Used for specific button labels, providing a standard, legible base that subtly contrasts with the custom nbarchitekt font. · `--font-arial`
- **Substitute:** Arial
- **Weights:** 400
- **Sizes:** 13px
- **Line height:** 1.20
- **Role:** Used for specific button labels, providing a standard, legible base that subtly contrasts with the custom nbarchitekt font.

### Times — Employed for less critical text and general content, specifically where a traditional serif style is desired. This choice introduces a classic counterpoint to the otherwise modern, technical aesthetic. Its inclusion suggests intentionality for specific content blocks like legal text. · `--font-times`
- **Substitute:** Times New Roman
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.20, 1.88
- **Role:** Employed for less critical text and general content, specifically where a traditional serif style is desired. This choice introduces a classic counterpoint to the otherwise modern, technical aesthetic. Its inclusion suggests intentionality for specific content blocks like legal text.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.5 | — | `--text-caption` |
| body-sm | 12px | 1.5 | — | `--text-body-sm` |
| body | 14px | 1.5 | — | `--text-body` |

## Tokens — Spacing & Shapes

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 6 | 6px | `--spacing-6` |
| 12 | 12px | `--spacing-12` |
| 13 | 13px | `--spacing-13` |
| 14 | 14px | `--spacing-14` |
| 16 | 16px | `--spacing-16` |
| 18 | 18px | `--spacing-18` |
| 28 | 28px | `--spacing-28` |

### Border Radius

| Element | Value |
|---------|-------|
| max | 500px |
| min | 5px |
| cards | 12px |
| buttons | 5px or 500px |

### Layout

## Components

### Standard Ghost Button
**Role:** Navigation and secondary actions

Minimalist button with rgba(255, 255, 255, 0.1) background, Pure White text, and a 1px top border of rgba(255, 255, 255, 0.6). Uses 5px border radius. Padding is 1px vertical, 6px horizontal. Font is nbarchitekt 400, 14px.

### Primary Pill Button
**Role:** Key calls to action

Distinctive pill-shaped button with rgba(156, 165, 255, 0.333) background, black text, and a top border of rgba(255, 255, 255, 0.5). Features a 500px border radius. Padding is 4px vertical, 18px horizontal. Font is Arial 400, 13px.

### Secondary Pill Button
**Role:** Alternative actions or dismissals

Pill-shaped button with rgba(0, 0, 0, 0.333) background (transparent black), black text, and a top border of rgba(255, 255, 255, 0.5). Features a 500px border radius. Padding is 4px vertical, 18px horizontal. Font is Arial 400, 13px.

### Cookie Consent Box
**Role:** Informational overlay

A dark, minimally bordered box with a 12px border radius. Contains body text in nbarchitekt 400, 12px, Pure White. Features two pill buttons for user interaction: Primary Pill Button and Secondary Pill Button, separated by horizontal internal spacing of 12px.

### Text Link - Active
**Role:** Navigation and clickable text

Pure White text with an underline, using nbarchitekt 400, 14px. On hover, it likely retains color and adds a subtle visual change not captured in static data.

### Text Link - Inactive/Secondary
**Role:** Less prominent links or unvisited status

Silver Mist text, nbarchitekt 400, 14px. Used for links within long-form text or less critical navigation items to differentiate from active states or primary links.

## Do's and Don'ts

### Do
- Prioritize Void Black (#000000) for all main backgrounds to maintain the dark, immersive aesthetic.
- Use Pure White (#ffffff) for primary text and controls, ensuring high contrast (AAA) against dark backgrounds.
- Apply nbarchitekt font at weight 400 for general UI text and 700 for headings, leveraging its unique character.
- Utilize 500px border radius for key interactive buttons (like 'Accept Cookies') to create a distinct pill shape.
- Employ the 5px border radius for `Standard Ghost Buttons` to subtly differentiate their interaction level from pill buttons.
- Allow a top border as a subtle interactive indicator for buttons, using rgba(255, 255, 255, 0.6) or rgba(255, 255, 255, 0.5).
- Maintain minimal padding variations (e.g., 1px vertical/6px horizontal and 4px vertical/18px horizontal) across button types for a controlled, compact feel.

### Don't
- Avoid using bright, saturated colors extensively; limit chromatic accents to Subtle Violet (#343755) and Highlight Violet (rgba(156, 165, 255, 0.333)).
- Do not introduce new font families beyond nbarchitekt, Arial, and Times to maintain typographic consistency.
- Refrain from using strong shadows or heavy gradients; focus on subtle luminescence and flat design elements.
- Do not deviate from the specified border radii (5px, 12px, 500px); these define the component's perceived softness or sharpness.
- Avoid large, uncontained images; instead, use abstract or technical visuals that blend into dark backgrounds.
- Do not overuse Pure White; reserve it for essential text and active states to preserve its visual impact.
- Do not use generic system default styling for interactive elements; custom button styles are critical to the brand identity.

## Imagery

The visual language is abstract and evocative, entirely eschewing traditional photography or literal illustrations. Instead, it features 3D rendered, luminous abstract forms and particle effects, like glimmers of light and transparent, refractive objects. Imagery is always 'contained' within the dark canvas of the background, appearing to emit its own light. The effect is decorative and atmospheric, rather than explanatory, contributing to a sense of mystery and advanced technology. Icons, though not extensively present, would likely be outlined and mono-colored to blend with the minimalist UI.

## Layout

The site employs a full-bleed, dark canvas that extends to the edges of the viewport, creating an immersive, uncontained experience. The hero section is dominated by an abstract, luminous 3D graphic, centered vertically, with minimal UI elements (navigation, cookie consent) overlaid. Content appears to be presented sparsely and centrally, with elements spaced generously against the dark background. The navigation is a top-right, minimalist header, using subtle ghost buttons. The overall density is very low, prioritizing visual impact and a sense of 'space' as much as information delivery.

## Agent Prompt Guide

### Quick Color Reference
- Text (primary): #ffffff
- Background (primary): #000000
- CTA background (primary): rgba(156, 165, 255, 0.333)
- Border (subtle): rgba(255, 255, 255, 0.6)
- Link (secondary): #c6c6c6

### 3-5 Example Component Prompts
1. **Create a footer section:** Void Black background, nbarchitekt 400, 12px, Silver Mist text. Include a Pure White text link 'Privacy Notice.' (nbarchitekt 400, 12px). Elements should be separated by 6px.
2. **Generate a primary call-to-action button 'Explore Now':** Use Highlight Violet (rgba(156, 165, 255, 0.333)) background, 500px border radius, 4px vertical / 18px horizontal padding. Text 'Explore Now' in Arial 400, 13px, black. Add a top border rgba(255, 255, 255, 0.5).
3. **Design a ghost navigation button 'Work':** With rgba(255, 255, 255, 0.1) background, 5px border radius, 1px vertical / 6px horizontal padding. Text 'WORK' in nbarchitekt 400, 14px, #ffffff. Add a top border rgba(255, 255, 255, 0.6).
4. **Create a cookie consent box centered on the screen:** Use Void Black (#000000) background, 12px border radius. Body text 'Our site uses essential cookies...' in nbarchitekt 400, 12px, Pure White (#ffffff). Below the text, add two buttons side-by-side: an 'Accept Cookies' Primary Pill Button and a 'Reject Cookies' Secondary Pill Button (rgba(0,0,0,0.333) background). Space elements with 12px horizontal and 14px vertical gap.

## Similar Brands

- **Awwwards-winning portfolio sites** — Shares the dark, immersive background, custom typography, subtle interactive elements, and emphasis on visual experience over dense information.
- **Google Arts & Culture** — Uses deep, dark backgrounds to showcase visual content and interactive elements, often with subtle glow effects.
- **Obscura Digital** — Similar focus on creative digital experiences, often translating into interfaces that are more artistic and atmospheric than purely functional, with dark palettes and experimental typography.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-void-black: #000000;
  --color-ash-gray: #4d4d4d;
  --color-pure-white: #ffffff;
  --color-silver-mist: #c6c6c6;
  --color-subtle-violet: #343755;
  --color-highlight-violet: #9cA5FF;

  /* Typography — Font Families */
  --font-nbarchitekt: 'nbarchitekt', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-times: 'Times', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --text-body-sm: 12px;
  --leading-body-sm: 1.5;
  --text-body: 14px;
  --leading-body: 1.5;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-6: 6px;
  --spacing-12: 12px;
  --spacing-13: 13px;
  --spacing-14: 14px;
  --spacing-16: 16px;
  --spacing-18: 18px;
  --spacing-28: 28px;

  /* Layout */

  /* Border Radius */
  --radius-md: 5px;
  --radius-xl: 12px;
  --radius-full: 500px;

  /* Named Radii */
  --radius-max: 500px;
  --radius-min: 5px;
  --radius-cards: 12px;
  --radius-buttons: 5px or 500px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-void-black: #000000;
  --color-ash-gray: #4d4d4d;
  --color-pure-white: #ffffff;
  --color-silver-mist: #c6c6c6;
  --color-subtle-violet: #343755;
  --color-highlight-violet: #9cA5FF;

  /* Typography */
  --font-nbarchitekt: 'nbarchitekt', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-times: 'Times', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --text-body-sm: 12px;
  --leading-body-sm: 1.5;
  --text-body: 14px;
  --leading-body: 1.5;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-6: 6px;
  --spacing-12: 12px;
  --spacing-13: 13px;
  --spacing-14: 14px;
  --spacing-16: 16px;
  --spacing-18: 18px;
  --spacing-28: 28px;

  /* Border Radius */
  --radius-md: 5px;
  --radius-xl: 12px;
  --radius-full: 500px;
}
```

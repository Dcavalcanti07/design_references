# Streamtime — Style Reference
> organized chaos, vibrant collage

**Theme:** light

Streamtime projects a playful yet structured work environment through its visual design. High-contrast typography emphasizes clarity against predominantly white and near-white canvas. A limited palette of vibrant, almost neon, brand colors injects energy and highlights interactive elements, creating a sense of 'switched-on' functionality. Abstract, collage-style graphic elements add a distinctive, creative-industry texture, contrasting with the otherwise clean and organized UI components.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Pitch Black | `#000000` | `--color-pitch-black` | Primary text, icon fills, strong borders – provides stark contrast and graphic definition |
| Off Black | `#2f2c29` | `--color-off-black` | Hero section backgrounds, prominent filled buttons – a softer alternative to true black for large dark areas |
| Vanilla Cream | `#fbf8f5` | `--color-vanilla-cream` | Card surfaces, secondary backgrounds – a warm, subtle tint that provides gentle separation from the main canvas |
| Warm Mist | `#f1e8de` | `--color-warm-mist` | Page backgrounds, large canvas areas – a slightly warm off-white, acting as the primary blank slate |
| Whisper White | `#ffffff` | `--color-whisper-white` | Navigation backgrounds, selected UI elements where a pure, bright white is necessary |
| Light Steel | `#999999` | `--color-light-steel` | Muted text, secondary borders, disabled states |
| Warm Clay | `#eadcce` | `--color-warm-clay` | Navigation item backgrounds, subtle accent areas – a delicate warm gray |
| Stone Buff | `#c3b7ac` | `--color-stone-buff` | Card backgrounds, selected navigation items – a mid-tone warm gray used for subtle surface variations |
| Canary Yellow | `#ffde3b` | `--color-canary-yellow` | Primary action buttons, accented navigation items, card accents – a bright, energetic highlight color |
| Shocking Pink | `#ff4dd5` | `--color-shocking-pink` | Decorative graphic elements, accent fills – a vibrant, high-energy accent |
| Lime Spritz | `#c6dc3c` | `--color-lime-spritz` | Card accents, navigation items, descriptive elements – a fresh, active accent |
| Sky Blue | `#6483ff` | `--color-sky-blue` | Card accents, interactive elements – a clear, digital blue for specific highlights |
| Fresh Green | `#c1f32b` | `--color-fresh-green` | Decorative graphic elements, line accents – a slightly lighter, vivid green than Lime Spritz |
| Bubblegum Pink | `#ee84d5` | `--color-bubblegum-pink` | Navigation items, secondary accents – a lighter, playful pink |

## Tokens — Typography

### Ease Display — Headlines and display text – provides a confident, blocky presence with tight tracking for impact. · `--font-ease-display`
- **Substitute:** Montserrat, system-ui
- **Weights:** 400
- **Sizes:** 16px, 28px, 30px, 68px, 100px
- **Line height:** 1.00, 1.10, 1.20
- **Letter spacing:** -0.060em at 100px, -0.034em at 68px, -0.014em at 30px
- **Role:** Headlines and display text – provides a confident, blocky presence with tight tracking for impact.

### Ease Standard — Body copy, button labels, navigation, and helper text – ensures readability at smaller sizes while maintaining character with subtle negative tracking. · `--font-ease-standard`
- **Substitute:** Inter, system-ui
- **Weights:** 400
- **Sizes:** 12px, 16px, 18px
- **Line height:** 1.10, 1.20
- **Letter spacing:** -0.080em at 18px, -0.060em at 16px, -0.053em at 12px
- **Role:** Body copy, button labels, navigation, and helper text – ensures readability at smaller sizes while maintaining character with subtle negative tracking.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.1 | -0.636px | `--text-caption` |
| body | 16px | 1.2 | -0.96px | `--text-body` |
| body-lg | 18px | 1.2 | -1.44px | `--text-body-lg` |
| subheading | 28px | 1.1 | -0.952px | `--text-subheading` |
| heading | 30px | 1.1 | -0.42px | `--text-heading` |
| heading-lg | 68px | 1 | -2.312px | `--text-heading-lg` |
| display | 100px | 1 | -6px | `--text-display` |

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
| 56 | 56px | `--spacing-56` |
| 80 | 80px | `--spacing-80` |
| 96 | 96px | `--spacing-96` |
| 120 | 120px | `--spacing-120` |
| 200 | 200px | `--spacing-200` |

### Border Radius

| Element | Value |
|---------|-------|
| button | 160px |
| default | 5px |
| navigation | 96px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| sm | `rgba(0, 0, 0, 0.13) 1px 0px 5px 0px, rgba(0, 0, 0, 0.08) ...` | `--shadow-sm` |
| md | `rgba(115, 115, 115, 0.16) 0px 3px 10px 0px, rgba(115, 115...` | `--shadow-md` |
| sm-2 | `rgba(0, 0, 0, 0.08) 2px 2px 4px 1px, rgba(0, 0, 0, 0.13) ...` | `--shadow-sm-2` |

### Layout

- **Section gap:** 40px
- **Card padding:** 30px
- **Element gap:** 16px

## Components

### Primary Action Button
**Role:** Main call to action

Canary Yellow (#ffde3b) background with Pitch Black (#000000) text and border. Large, rounded corners at 5px radius. Padding 20px all around.

### Rounded Button
**Role:** Secondary action or menu button

Off Black (#2f2c29) background with Whisper White (#ffffff) text. Ultra-rounded corners with 160px radius. Padding 48px vertical, 80px horizontal.

### Content Card - Default
**Role:** Standard content containers with a subtle background

Vanilla Cream (#fbf8f5) background with 5px border-radius. Padding 30px.

### Content Card - Stone Buff
**Role:** Alternative content container for visual variation

Stone Buff (#c3b7ac) background with 5px border-radius. Padding 30px.

### Navigation Item - Canary Yellow
**Role:** Highlights active or selected navigation states

Canary Yellow (#ffde3b) background, typically seen with very rounded corners (96px radius).

### Navigation Item - Stone Buff
**Role:** Secondary navigation items

Stone Buff (#c3b7ac) background, typically with very rounded corners (96px radius).

## Do's and Don'ts

### Do
- Use Pitch Black (#000000) for all primary text and display headlines to maximize contrast.
- Apply Canary Yellow (#ffde3b) exclusively for primary calls to action and active focus states, avoiding overuse.
- Employ Ease Display font with tight letter-spacing for all headlines to create a bold, graphic impact.
- Utilize 5px as the default border-radius for cards and smaller interactive elements, reserving 96px or 160px for highly rounded buttons or menu toggles.
- Maintain a comfortable density with card padding of 30px and element spacing of 16px.
- Introduce graphic elements with strong colors like Shocking Pink (#ff4dd5) and Fresh Green (#c1f32b) to break up otherwise neutral sections.

### Don't
- Do not introduce new saturated accent colors outside of Canary Yellow, Shocking Pink, Lime Spritz, and Sky Blue.
- Avoid using drop shadows extensively; limit them to navigation bars or subtle indications of interaction beneath specific elements like search bars.
- Do not deviate from the specified negative letter-spacing values for Ease Display and Ease Standard; it's a core characteristic.
- Refrain from using heavily tinted backgrounds or dark overlays for content sections unless specifically defined for an 'off black' hero.
- Do not use generic system fonts in place of Ease Display or Ease Standard families as their unique tracking attributes are central to the brand's voice.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Warm Mist Canvas | `#f1e8de` | Primary page background, the foundational layer for all content. |
| 1 | Vanilla Cream Surface | `#fbf8f5` | Elevated card backgrounds, offering a subtle visual break from the canvas. |
| 2 | Whisper White Panel | `#ffffff` | Pure white backgrounds for navigation, headers, or specific content blocks requiring maximum brightness. |
| 3 | Off Black Deep Surface | `#2f2c29` | Distinct dark sections, typically for hero banners or feature blocks, providing strong contrast. |

## Elevation

- **Navigation Bar:** `rgba(0, 0, 0, 0.13) 1px 0px 5px 0px, rgba(0, 0, 0, 0.08) 2px 2px 4px 1px`
- **Other interactive elements:** `rgba(115, 115, 115, 0.16) 0px 3px 10px 0px, rgba(115, 115, 115, 0.16) 0px 2px 4px 0px`

## Imagery

The imagery is a mix of product screenshots, lifestyle photography, and abstract, collage-style graphic elements. Photography is contained, often cropped into circular shapes or framed with brand colors, showing product in use or people working. Illustrations are 2D, organic, and abstract shapes, often outlined or filled with solid brand colors or textured patterns, and frequently layered over or around content, creating a dynamic, almost paper-cutout effect. Icons are outlined, medium stroke weight, and monochromatic (Pitch Black). Imagery serves a decorative and atmospheric role, adding a playful, creative-industry vibe, rather than purely explanatory content, balancing text-dominant sections with bursts of visual interest.

## Layout

The page primarily uses a full-bleed structure with content often centered or presented in distinct sections. The hero section features a centered headline over a white background with a large graphic illustration. Subsequent sections alternate between light (Warm Mist or Whisper White) and dark (Off Black) backgrounds, creating a clear vertical rhythm. Content within sections is often arranged in prominent centered stacks, or in two-column text-left/image-right compositions. Card grids for informational content maintain ample spacing. Navigation consists of a top bar with a menu toggle and prominent call-to-action buttons, sticky in some contexts, maintaining a comfortable, organized appearance.

## Agent Prompt Guide

### Quick Color Reference
- text: #000000
- background: #f1e8de
- border: #000000
- accent: #ff4dd5
- primary action: #ffde3b (filled action)

### 3-5 Example Component Prompts
1. Create a primary call to action button: Canary Yellow (#ffde3b) background, Pitch Black (#000000) text and border, 5px radius, 20px padding, using Ease Standard font, weight 400, size 16px, letter-spacing -0.96px.
2. Design a navigation menu toggle: Off Black (#2f2c29) background, Whisper White (#ffffff) text, 160px radius, 48px vertical and 80px horizontal padding, using Ease Standard font, weight 400, size 16px.
3. Implement a content card: Vanilla Cream (#fbf8f5) background, 5px radius, 30px padding, with secondary text as Light Steel (#999999) using Ease Standard font, size 16px.

## Similar Brands

- **Figma** — Employs an otherwise clean, light UI with bursts of vibrant, saturated color for interactive elements and graphic accents.
- **Mailchimp** — Combines friendly, approachable typography with a playful use of abstract shapes and a limited but impactful accent color palette.
- **Notion** — Focuses on a predominantly neutral canvas with high-contrast text, using small, functional splashes of color for emphasis rather than decoration.
- **Canva** — Utilizes a clean, white background with bright, cheerful accent colors that appear in interface elements and illustrative components to convey creativity and ease of use.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-pitch-black: #000000;
  --color-off-black: #2f2c29;
  --color-vanilla-cream: #fbf8f5;
  --color-warm-mist: #f1e8de;
  --color-whisper-white: #ffffff;
  --color-light-steel: #999999;
  --color-warm-clay: #eadcce;
  --color-stone-buff: #c3b7ac;
  --color-canary-yellow: #ffde3b;
  --color-shocking-pink: #ff4dd5;
  --color-lime-spritz: #c6dc3c;
  --color-sky-blue: #6483ff;
  --color-fresh-green: #c1f32b;
  --color-bubblegum-pink: #ee84d5;

  /* Typography — Font Families */
  --font-ease-display: 'Ease Display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ease-standard: 'Ease Standard', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.1;
  --tracking-caption: -0.636px;
  --text-body: 16px;
  --leading-body: 1.2;
  --tracking-body: -0.96px;
  --text-body-lg: 18px;
  --leading-body-lg: 1.2;
  --tracking-body-lg: -1.44px;
  --text-subheading: 28px;
  --leading-subheading: 1.1;
  --tracking-subheading: -0.952px;
  --text-heading: 30px;
  --leading-heading: 1.1;
  --tracking-heading: -0.42px;
  --text-heading-lg: 68px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -2.312px;
  --text-display: 100px;
  --leading-display: 1;
  --tracking-display: -6px;

  /* Typography — Weights */
  --font-weight-regular: 400;

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
  --spacing-56: 56px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-120: 120px;
  --spacing-200: 200px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 30px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-md: 5px;
  --radius-lg: 10px;
  --radius-full: 96px;
  --radius-full-2: 160px;

  /* Named Radii */
  --radius-button: 160px;
  --radius-default: 5px;
  --radius-navigation: 96px;

  /* Shadows */
  --shadow-sm: rgba(0, 0, 0, 0.13) 1px 0px 5px 0px, rgba(0, 0, 0, 0.08) 2px 2px 4px 1px;
  --shadow-md: rgba(115, 115, 115, 0.16) 0px 3px 10px 0px, rgba(115, 115, 115, 0.16) 0px 2px 4px 0px;
  --shadow-sm-2: rgba(0, 0, 0, 0.08) 2px 2px 4px 1px, rgba(0, 0, 0, 0.13) 1px 0px 5px 0px;

  /* Surfaces */
  --surface-warm-mist-canvas: #f1e8de;
  --surface-vanilla-cream-surface: #fbf8f5;
  --surface-whisper-white-panel: #ffffff;
  --surface-off-black-deep-surface: #2f2c29;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-pitch-black: #000000;
  --color-off-black: #2f2c29;
  --color-vanilla-cream: #fbf8f5;
  --color-warm-mist: #f1e8de;
  --color-whisper-white: #ffffff;
  --color-light-steel: #999999;
  --color-warm-clay: #eadcce;
  --color-stone-buff: #c3b7ac;
  --color-canary-yellow: #ffde3b;
  --color-shocking-pink: #ff4dd5;
  --color-lime-spritz: #c6dc3c;
  --color-sky-blue: #6483ff;
  --color-fresh-green: #c1f32b;
  --color-bubblegum-pink: #ee84d5;

  /* Typography */
  --font-ease-display: 'Ease Display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ease-standard: 'Ease Standard', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.1;
  --tracking-caption: -0.636px;
  --text-body: 16px;
  --leading-body: 1.2;
  --tracking-body: -0.96px;
  --text-body-lg: 18px;
  --leading-body-lg: 1.2;
  --tracking-body-lg: -1.44px;
  --text-subheading: 28px;
  --leading-subheading: 1.1;
  --tracking-subheading: -0.952px;
  --text-heading: 30px;
  --leading-heading: 1.1;
  --tracking-heading: -0.42px;
  --text-heading-lg: 68px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -2.312px;
  --text-display: 100px;
  --leading-display: 1;
  --tracking-display: -6px;

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
  --spacing-56: 56px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-120: 120px;
  --spacing-200: 200px;

  /* Border Radius */
  --radius-md: 5px;
  --radius-lg: 10px;
  --radius-full: 96px;
  --radius-full-2: 160px;

  /* Shadows */
  --shadow-sm: rgba(0, 0, 0, 0.13) 1px 0px 5px 0px, rgba(0, 0, 0, 0.08) 2px 2px 4px 1px;
  --shadow-md: rgba(115, 115, 115, 0.16) 0px 3px 10px 0px, rgba(115, 115, 115, 0.16) 0px 2px 4px 0px;
  --shadow-sm-2: rgba(0, 0, 0, 0.08) 2px 2px 4px 1px, rgba(0, 0, 0, 0.13) 1px 0px 5px 0px;
}
```

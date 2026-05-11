# Clay — Style Reference
> Playful Precision Playground. A brightly lit space filled with meticulously arranged, colorful building blocks.

**Theme:** light

This design system feels like a thoughtfully organized play-space, balancing crisp professional typography with unexpected bursts of vibrant, playful color in testimonial cards and illustrations. The overall tone is light and inviting, grounded by a clean, spacious layout. Subtle border treatments and generous radii on containers soften the digital edge, creating a friendly yet authoritative aesthetic.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Pitch Black | `#000000` | `--color-pitch-black` | Primary text, button backgrounds, strong accents for contrast |
| Ghost White | `#ffffff` | `--color-ghost-white` | Page backgrounds, card backgrounds, inverse text on dark elements |
| Cloud Gray | `#f9f8f6` | `--color-cloud-gray` | Subtle background for UI elements like secondary cards or sections |
| Inkwell | `#55534` | `--color-inkwell` | Secondary body text, softer contrast against white backgrounds |
| Platinum Gray | `#e6e8ec` | `--color-platinum-gray` | Subtle borders and separators, secondary button borders |
| Oatmeal | `#dad4c8` | `--color-oatmeal` | Border color for various UI elements, providing a warm, subtle distinction |
| Clay Violet | `#3859f9` | `--color-clay-violet` | Primary brand accent for interactive elements like links and key call-to-action details |
| Vivid Sky | `#429dff` | `--color-vivid-sky` | Highlight color for cards, bringing a clear, energetic blue to sections |
| Tangerine | `#ff7614` | `--color-tangerine` | Energetic accent color for cards and visual elements, signaling warmth and dynamism |
| Lime Pop | `#cbd810` | `--color-lime-pop` | Vibrant accent color for cards, indicating freshness and vibrancy |
| Azure Glow | `#3bd3fd` | `--color-azure-glow` | Bright accent color for cards, contributing to a playful and modern feel |
| Matcha Green | `#02693` | `--color-matcha-green` | Deep, rich accent color for cards, providing a grounded but still vibrant option |
| Dragonfruit Pink | `#8b045c` | `--color-dragonfruit-pink` | Bold accent color for cards, adding a strong, distinctive pop |
| Blueberry Deep | `#0667d9` | `--color-blueberry-deep` | Core accent color for cards, serving as a primary vibrant blue |
| Ube Haze | `#c1b0ff` | `--color-ube-haze` | Pastel accent often used as a background for special sections or badges |

## Tokens — Typography

### Roobert — The primary typeface for all text elements. Its geometric yet friendly character defines the brand's voice, using varying weights and precise letter-spacing to articulate hierarchy and emphasis. · `--font-roobert`
- **Substitute:** Arial
- **Weights:** 400, 500, 600, 700
- **Sizes:** 10px, 11px, 12px, 13px, 14px, 15px, 16px, 18px, 20px, 32px, 44px, 60px, 80px
- **Line height:** 1.00, 1.10, 1.20, 1.40, 1.50, 1.60
- **Letter spacing:** -0.0400em, -0.0300em, -0.0200em, -0.0100em, -0.0080em, 0.0900em
- **OpenType features:** `"ss03", "ss10", "ss11", "ss12", "ss01"`
- **Role:** The primary typeface for all text elements. Its geometric yet friendly character defines the brand's voice, using varying weights and precise letter-spacing to articulate hierarchy and emphasis.

### Phosphor — Used for specific functional elements or icons, providing a clear, unadorned visual style where ligatures might enhance clarity without decorative flourish. · `--font-phosphor`
- **Substitute:** system-ui
- **Weights:** 400
- **Sizes:** 13px, 16px, 20px
- **Line height:** 1.00
- **Letter spacing:** normal
- **OpenType features:** `"liga"`
- **Role:** Used for specific functional elements or icons, providing a clear, unadorned visual style where ligatures might enhance clarity without decorative flourish.

### Phosphor-Bold — A bolder variant of Phosphor, used sparingly for emphasis within functional text or specific icons. · `--font-phosphor-bold`
- **Substitute:** system-ui
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.00
- **Letter spacing:** normal
- **OpenType features:** `"liga"`
- **Role:** A bolder variant of Phosphor, used sparingly for emphasis within functional text or specific icons.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.4 | 0.9px | `--text-caption` |
| body | 16px | 1.6 | — | `--text-body` |
| subheading | 18px | 1.5 | — | `--text-subheading` |
| heading-sm | 20px | 1.5 | — | `--text-heading-sm` |
| heading | 32px | 1.2 | -0.48px | `--text-heading` |
| heading-lg | 44px | 1.1 | -0.88px | `--text-heading-lg` |
| display | 60px | 1 | -2.4px | `--text-display` |

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
| 36 | 36px | `--spacing-36` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 60 | 60px | `--spacing-60` |
| 64 | 64px | `--spacing-64` |
| 76 | 76px | `--spacing-76` |
| 96 | 96px | `--spacing-96` |
| 112 | 112px | `--spacing-112` |
| 120 | 120px | `--spacing-120` |

### Border Radius

| Element | Value |
|---------|-------|
| pill | 1584px |
| cards | 12px |
| buttons | 12px |
| largeCards | 40px |
| interactiveElements | 8px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(0, 0, 0, 0.1) 0px 1px 1px 0px, rgba(0, 0, 0, 0.04) 0...` | `--shadow-subtle` |

### Layout

- **Page max-width:** 1200px
- **Section gap:** 64px
- **Card padding:** 20px
- **Element gap:** 8px

## Components

### Primary Action Button
**Role:** Button

Solid black background (#000000), white text (#ffffff), 12px border-radius, 6.4px vertical padding, 12.8px horizontal padding. Delivers clear, high-contrast calls to action.

### Secondary Outline Button
**Role:** Button

Transparent background, dark gray text (#222222), no border-radius (0px), no padding. Used for minimal, text-based actions or links that require less visual emphasis.

### Ghost Button
**Role:** Button

White background (#ffffff), black text (#000000), 12px border-radius, 8px vertical padding, 16px horizontal padding. Provides a prominent but less assertive alternative to the primary button.

### Pill Button
**Role:** Button

White background (#ffffff), black text (#000000), 1584px (full pill) border-radius, 8px padding. Used for small, contained interactive elements like navigation pills or tags.

### Hero Section Card
**Role:** Card

Transparent background, 12px border-radius, 20px padding on all sides. Used for informational boxes with subtle definition, no shadow.

### Modal Overlay Card
**Role:** Card

Translucent background (rgba(0,0,0,0.11)), 24px border-radius, no padding. Used for overlaying content with a soft, frosted-glass effect.

## Do's and Don'ts

### Do
- Prioritize Roobert for all text, applying specific letter-spacing: -0.0400em for 60px headings and 0.0900em for 10px text, balancing readability and visual density.
- Use Pitch Black (#000000) for primary text and calls to action, ensuring high contrast against light backgrounds like Ghost White (#ffffff) or Cloud Gray (#f9f8f6).
- Employ the 40px border-radius for distinct content blocks like testimonial cards, paired with vibrant accent colors (e.g., #ff7614 Tangerine, #cbd810 Lime Pop).
- Apply Oatmeal (#dad4c8) for subtle borders on UI elements, contributing to a warm, approachable feel without harsh lines.
- Maintain a clear pageMaxWidth of 1200px for main content, using generous section gaps around multiples of 64px to create a spacious layout.
- Utilize Clay Violet (#3859f9) consistently for primary interactive elements, links, and key brand highlights, providing a cohesive brand signature.
- Use 1584px radius for all pill-shaped elements and buttons, reserving the 8px radius for smaller interactive components like nav items.

### Don't
- Avoid using harsh, sharp corners; instead, adopt the system's rounded radii, with 12px as a default for most interactive elements and 40px for prominent display cards.
- Do not introduce new shadow effects; adhere to the subtle inset button shadow (rgba(0, 0, 0, 0.1) 0px 1px 1px 0px, rgba(0, 0, 0, 0.04) 0px -1px 1px 0px inset, rgba(0, 0, 0, 0.05) 0px -0.5px 1px 0px) for elevation.
- Refrain from using highly saturated colors for large text blocks; reserve them for accents, backgrounds of component-level cards, or illustrations.
- Do not deviate from Roobert's specific letter-spacing values at given sizes; these are crucial for the font's intended visual rhythm and legibility.
- Avoid arbitrary text alignments; maintain left-aligned text for paragraphs and headlines, centered only for specific hero sections or impactful statements.
- Do not introduce body text sizes smaller than 13px or larger than 18px; use the designated type scale for readable content blocks.

## Imagery

The site uses a mix of playful, colorful 3D illustrations featuring abstract shapes and objects (like colorful building blocks or pencils) that are often contained or positioned to complement text blocks. There's also the occasional use of product screenshots or UI snippets that are tightly cropped and framed, but the dominant visual language leans heavily into these vibrant, almost toy-like illustrations. Icons are primarily outlined. The imagery serves a decorative atmospheric role, making technical concepts feel more approachable and engaging, while also being explanatory in the product screenshots.

## Layout

The layout is primarily centered and contained within a max-width of 1200px. The hero section features a large, centered headline over a subtle background texture. Subsequent sections often alternate between text-left/image-right or image-left/text-right patterns, with generous vertical spacing (64px section gaps). Features are presented in a multi-column card grid, often with distinctive, playfully colored backgrounds. The navigation is a sticky top bar, emphasizing common links and a log-in/demo. The overall density is spacious, providing ample breathing room between elements and sections.

## Agent Prompt Guide

### Quick Color Reference
- **Text:** #000000 (Pitch Black)
- **Background:** #ffffff (Ghost White)
- **CTA:** #000000 (Pitch Black)
- **Border:** #dad4c8 (Oatmeal)
- **Accent:** #3859f9 (Clay Violet)

### 3-5 Example Component Prompts
1. **Create a Hero Section:** Background Ghost White (#ffffff). Headline (display role) 'Go to market with unique data' text Pitch Black (#000000), font Roobert, weight 700, size 60px, lineHeight 1.0, letterSpacing -2.4px. Subtext (body role) 'Bring AI agents together' text Inkwell (#55534e), font Roobert, weight 400, size 16px, lineHeight 1.6. Primary Action Button: 'Start building for free' background Pitch Black (#000000), text Ghost White (#ffffff), radius 12px, padding 6.4px 12.8px.
2. **Generate a Testimonial Card:** Background Tangerine (#ff7614), border-radius 40px, padding 40px top, 32px sides/bottom. Quote text Pitch Black (#000000), font Roobert, weight 500, size 18px, lineHeight 1.5. Author name Pitch Black (#000000), font Roobert, weight 600, size 16px, lineHeight 1.6.
3. **Design a Navigation Bar:** Background Ghost White (#ffffff), fixed top. Nav links (body-sm role) 'Product', 'Use cases' etc. text Pitch Black (#000000), font Roobert, weight 400, size 13px, lineHeight 1.6. Log in button: Ghost Button variant, text Pitch Black (#000000), background Ghost White (#ffffff), radius 12px, padding 8px 16px. Sign up button: Primary Action Button variant, text Ghost White (#ffffff), background Pitch Black (#000000), radius 12px, padding 6.4px 12.8px.
4. **Create a Cookie Consent Banner:** Background Cloud Gray (#f9f8f6), border-radius 24px, padding 20px. Body text Inkwell (#55534e), font Roobert, weight 400, size 16px, lineHeight 1.6. 'Accept all' button: Ghost Button variant, text Clay Violet (#3859f9), background Ghost White (#ffffff), radius 12px, padding 8.8px 19.2px. 'More choices' button: Ghost Button variant, text Pitch Black (#000000), background Ghost White (#ffffff), radius 12px, padding 8.8px 19.2px.

## Similar Brands

- **Airtable** — Shares the use of vibrant, playful accent colors for individual cards and a clean, spacious light-theme UI for complex data management.
- **Figma** — Similar in its emphasis on clear, functional typography (like Roobert) and a highly organized, grid-based aesthetic that uses subtle neutral backgrounds to let content and interactive elements shine.
- **Notion** — Both use a light, minimalist background to highlight content, employing subtle borders and precise typography rather than heavy embellishments, though Notion is more monochrome.
- **Stripe** — Exhibits a similar commitment to refined typography and a balance between professional design and approachable, sometimes playfully illustrated, content.
- **Linear** — Shares the preference for a clean, highly organized interface with precise typography and a minimal use of color to denote status or highlight interactivity, though Linear leans darker.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-pitch-black: #000000;
  --color-ghost-white: #ffffff;
  --color-cloud-gray: #f9f8f6;
  --color-inkwell: #55534;
  --color-platinum-gray: #e6e8ec;
  --color-oatmeal: #dad4c8;
  --color-clay-violet: #3859f9;
  --color-vivid-sky: #429dff;
  --color-tangerine: #ff7614;
  --color-lime-pop: #cbd810;
  --color-azure-glow: #3bd3fd;
  --color-matcha-green: #02693;
  --color-dragonfruit-pink: #8b045c;
  --color-blueberry-deep: #0667d9;
  --color-ube-haze: #c1b0ff;

  /* Typography — Font Families */
  --font-roobert: 'Roobert', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-phosphor: 'Phosphor', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-phosphor-bold: 'Phosphor-Bold', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.4;
  --tracking-caption: 0.9px;
  --text-body: 16px;
  --leading-body: 1.6;
  --text-subheading: 18px;
  --leading-subheading: 1.5;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.5;
  --text-heading: 32px;
  --leading-heading: 1.2;
  --tracking-heading: -0.48px;
  --text-heading-lg: 44px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.88px;
  --text-display: 60px;
  --leading-display: 1;
  --tracking-display: -2.4px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-76: 76px;
  --spacing-96: 96px;
  --spacing-112: 112px;
  --spacing-120: 120px;

  /* Layout */
  --page-max-width: 1200px;
  --section-gap: 64px;
  --card-padding: 20px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-sm: 2.75px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-3xl-2: 30px;
  --radius-3xl-3: 40px;
  --radius-full: 1584px;

  /* Named Radii */
  --radius-pill: 1584px;
  --radius-cards: 12px;
  --radius-buttons: 12px;
  --radius-largecards: 40px;
  --radius-interactiveelements: 8px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.1) 0px 1px 1px 0px, rgba(0, 0, 0, 0.04) 0px -1px 1px 0px inset, rgba(0, 0, 0, 0.05) 0px -0.5px 1px 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-pitch-black: #000000;
  --color-ghost-white: #ffffff;
  --color-cloud-gray: #f9f8f6;
  --color-inkwell: #55534;
  --color-platinum-gray: #e6e8ec;
  --color-oatmeal: #dad4c8;
  --color-clay-violet: #3859f9;
  --color-vivid-sky: #429dff;
  --color-tangerine: #ff7614;
  --color-lime-pop: #cbd810;
  --color-azure-glow: #3bd3fd;
  --color-matcha-green: #02693;
  --color-dragonfruit-pink: #8b045c;
  --color-blueberry-deep: #0667d9;
  --color-ube-haze: #c1b0ff;

  /* Typography */
  --font-roobert: 'Roobert', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-phosphor: 'Phosphor', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-phosphor-bold: 'Phosphor-Bold', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.4;
  --tracking-caption: 0.9px;
  --text-body: 16px;
  --leading-body: 1.6;
  --text-subheading: 18px;
  --leading-subheading: 1.5;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.5;
  --text-heading: 32px;
  --leading-heading: 1.2;
  --tracking-heading: -0.48px;
  --text-heading-lg: 44px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.88px;
  --text-display: 60px;
  --leading-display: 1;
  --tracking-display: -2.4px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-76: 76px;
  --spacing-96: 96px;
  --spacing-112: 112px;
  --spacing-120: 120px;

  /* Border Radius */
  --radius-sm: 2.75px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-3xl-2: 30px;
  --radius-3xl-3: 40px;
  --radius-full: 1584px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.1) 0px 1px 1px 0px, rgba(0, 0, 0, 0.04) 0px -1px 1px 0px inset, rgba(0, 0, 0, 0.05) 0px -0.5px 1px 0px;
}
```

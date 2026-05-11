# Creative Giants — Style Reference
> Sculpted Minimalism on Canvas. An off-white backdrop frames strong typography and vibrant multimedia like exhibits in a pristine gallery.

**Theme:** light

This design system feels like a gallery of contemporary art and industrial design, using a sparse, neutral palette as a canvas for striking typographic and image-based narratives. The dominant off-white background (#fffef7) and deep black text provide high contrast, while a unique 'Switzer' typeface with varied weights and precise letter-spacing sculpts a distinctive voice. Strategic use of full-bleed imagery and occasional vibrant, unexpected color blocks punctuates the otherwise minimalist composition, creating a dynamic rhythm without visual clutter. The absence of traditional shadows or overt decorative elements emphasizes clarity and directness.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#fffef7` | `--color-canvas-white` | Page backgrounds, card surfaces, form inputs. |
| Ink Black | `#000000` | `--color-ink-black` | Primary text, button backgrounds, borders, navigation elements. The stark contrast creates readability and visual weight. |
| Medium Gray | `#666666` | `--color-medium-gray` | Secondary text, subtle accents. |
| Light Gray | `#aaaaaa` | `--color-light-gray` | Input borders, subtle UI elements. |
| Charcoal Gradient | `linear-gradient(rgb(77, 76, 74), rgb(0, 0, 0))` | `--color-charcoal-gradient` | Text overlay on hero imagery, creating depth and grounding large typographic elements. |
| Vivid Orchid | `#ffacea` | `--color-vivid-orchid` | Card backgrounds, emphasizing specific content blocks with unexpected vibrancy. |
| Muted Teal | `#a5ebd6` | `--color-muted-teal` | Card backgrounds, introducing a cool, calming accent. |
| Deep Plum | `#101731` | `--color-deep-plum` | Card backgrounds, providing a dark, sophisticated contrast. |
| Sunburst Yellow | `#ffd001` | `--color-sunburst-yellow` | Decorative elements, small highlights. |
| Sky Blue | `#009fff` | `--color-sky-blue` | Decorative elements, small highlights. |
| Aqua Cyan | `#48d1d6` | `--color-aqua-cyan` | Decorative elements, small highlights. |
| Fiery Orange | `#fc4c00` | `--color-fiery-orange` | Decorative elements, small highlights. |
| Hot Pink | `#ee77cf` | `--color-hot-pink` | Decorative elements, small highlights. |

## Tokens — Typography

### Switzer — All textual content: body, headings, links, buttons. The custom font provides a unique structural clarity, while varied weights and careful negative letter-spacing for larger sizes prevent it from feeling too rigid, adding a refined, almost architectural feel. · `--font-switzer`
- **Substitute:** system-ui, sans-serif
- **Weights:** 300, 400
- **Sizes:** 12px, 14px, 16px, 18px, 20px, 34px, 54px, 64px, 84px
- **Line height:** 1.00, 1.25, 1.40, 1.43
- **Letter spacing:** -0.04em at 84px, -0.027em at 64px, -0.023em at 54px, -0.02em at 34px, -0.018em at 20px, normal at smaller sizes
- **Role:** All textual content: body, headings, links, buttons. The custom font provides a unique structural clarity, while varied weights and careful negative letter-spacing for larger sizes prevent it from feeling too rigid, adding a refined, almost architectural feel.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.4 | — | `--text-caption` |
| body-sm | 14px | 1.4 | — | `--text-body-sm` |
| body | 16px | 1.4 | — | `--text-body` |
| subheading | 18px | 1.4 | — | `--text-subheading` |
| heading-sm | 20px | 1.4 | -0.36px | `--text-heading-sm` |
| heading | 34px | 1.25 | -0.68px | `--text-heading` |
| heading-lg | 54px | 1.25 | -1.242px | `--text-heading-lg` |
| display | 64px | 1 | -1.728px | `--text-display` |
| display-lg | 84px | 1 | -3.36px | `--text-display-lg` |

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
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 112 | 112px | `--spacing-112` |

### Border Radius

| Element | Value |
|---------|-------|
| other | 1440px |
| buttons | 1440px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(255, 255, 255, 0.2) 0px 0px 0px 1px` | `--shadow-subtle` |

### Layout

- **Section gap:** 48px
- **Card padding:** 48px
- **Element gap:** 8px

## Components

### Ghost Navigation Button
**Role:** Navigation, secondary actions

Transparent background, Ink Black text, no border or padding (0px padding, 0px border-radius). Used sparingly for minimalist interactive elements.

### Pill Accent Button (Black)
**Role:** Primary calls to action in dark contexts

Ink Black background, Canvas White text. Extremely rounded (1440px border-radius) for a pill shape, with 14.08px vertical and 20px horizontal padding. Creates a distinct, organic interactive target.

### Pill Accent Button (Transparent White Text)
**Role:** Secondary calls to action, especially over images

Transparent background, Canvas White text. Extremely rounded (1440px border-radius) for a pill shape, with 8px all-around padding. Provides a softer, more integrated interactive element.

### Monochromatic Feature Card
**Role:** Content grouping, visually subtle sections

Transparent background, 0px border-radius, no shadow, 0px padding. Acts as a container for related content without adding visual weight.

### Vivid Orchid Feature Card
**Role:** Highlighting specific content, adding visual interest

Vivid Orchid (#ffacea) background, 0px border-radius, no shadow, generous 48px padding. Used for impactful, color-backed content blocks.

### Muted Teal Feature Card
**Role:** Highlighting specific content, adding visual interest

Muted Teal (#a5ebd6) background, 0px border-radius, no shadow, generous 48px padding. Similar to Vivid Orchid card but with a cooler tone.

### Deep Plum Feature Card
**Role:** Highlighting specific content, adding visual interest

Deep Plum (#101731) background, 0px border-radius, no shadow, generous 48px padding. Provides a dark, sophisticated stage for content.

### Text Input Field
**Role:** User data entry

Canvas White (#fffef7) background, Ink Black (#000000) text and border. 0px border-radius, with 8px top/bottom and 12px right padding. Focus on functionality with minimal styling.

### Overlay Menu Badge
**Role:** Menu items within an overlay

Transparent background, Canvas White (#fffef7) text, 0px border-radius, 0px padding. For visually light menu items against a dark overlay.

## Do's and Don'ts

### Do
- Prioritize Canvas White (#fffef7) for page and card backgrounds to maintain the clean, gallery-like aesthetic.
- Use Ink Black (#000000) for all primary text elements to ensure maximum contrast and legibility.
- Apply the 'Switzer' font family with specific letter-spacing adjustments: -0.04em for 84px, -0.027em for 64px, and -0.023em for 54px to maintain typographic distinction.
- Employ the 1440px border-radius for all interactive buttons to create a consistent pill-shaped form.
- Utilize 48px padding for content cards that use chromatic backgrounds (Vivid Orchid, Muted Teal, Deep Plum) to create emphasis and breathing room.
- Use 0px border-radius for all cards and input fields to maintain sharp, architectural lines, contrasting with the pill-shaped buttons.
- Ensure all interactive elements have sufficient contrast against their backgrounds as per the #000000 on #fffef7 (20.8:1 AAA) standard.

### Don't
- Avoid using drop shadows on any element, as the design relies on color and proximity for depth, not elevation effects.
- Do not introduce additional font families; 'Switzer' is the singular typographic voice for the entire system.
- Refrain from using intermediate gray tones (#666666, #aaaaaa) for primary text or backgrounds — reserve them for secondary details.
- Do not deviate from the specified padding values for cards (48px) or buttons (14.08px vertical, 20px horizontal for solid buttons, 8px all-around for ghost buttons).
- Avoid generic rectangular buttons or elements with small radii; the extreme 1440px radius is a signature visual cue.
- Do not use background images or textures behind body text; maintain the clean Canvas White (#fffef7) or solid chromatic card backgrounds.

## Imagery

The visual language is characterized by high-quality, full-bleed photography and video that feels cinematic and impactful. Images often serve as large background elements, sometimes with a dark gradient overlay. Content is either lifestyle-oriented (people in urban or artistic settings) or features abstract, artistic scenes. The treatment is raw with minimal processing or effects, focusing on strong compositions and natural lighting. Imagery plays a dual role: providing dramatic atmosphere and showcasing abstract creative work, occupying significant visual space on the page to enhance impact rather than merely decorate.

## Layout

The page primarily uses a full-bleed layout, particularly in the hero section where large-scale imagery dominates the viewport. Content appears to be centered within an implicit maximal width, though the hero extends edge-to-edge. Sections are separated by distinct background changes, primarily between Canvas White (#fffef7) and full-bleed imagery/video. Content arrangement often features large headlines (e.g., 'Creative Giants') overlaid directly onto images, and subsequent sections use left-aligned text with occasional multi-column layouts for features. There's a comfortable density with ample negative space. The navigation is a minimalist top-bar with a 'Menu' button, likely triggering an overlay.

## Agent Prompt Guide

Quick Color Reference:
- Text: #000000 (Ink Black)
- Background: #fffef7 (Canvas White)
- CTA Background: #000000 (Ink Black)
- CTA Text: #fffef7 (Canvas White)
- Accent Card: #ffacea (Vivid Orchid)

Example Component Prompts:
1. Create a hero section: full-bleed background image with a linear-gradient(rgb(77, 76, 74), rgb(0, 0, 0)) overlay; centered headline 'CREATIVE GIANTS' at 84px Switzer weight 300, #fffef7, letter-spacing -3.36px. Sub-headline 'Production, design, and the art of the possible.' at 34px Switzer weight 400, #fffef7, letter-spacing -0.68px.
2. Create a primary call-to-action button: background #000000, text 'send enquiry' in #fffef7, Switzer font weight 400, 1440px border-radius, 14.08px vertical padding, 20px horizontal padding.
3. Create a feature card: background #ffacea, 0px border-radius, 48px padding. Headline 'Shoulders of Giants' at 20px Switzer weight 400, #000000, letter-spacing -0.36px. Body text 'Your monthly look at where we’re finding inspiration in the world' at 16px Switzer weight 400, #000000.
4. Create a text input field: background #fffef7, border 1px solid #000000, 0px border-radius, 8px top/bottom padding, 12px right padding. Placeholder text in Medium Gray (#666666), Switzer weight 400.

## Similar Brands

- **AIGA** — Emphasizes large, impactful typography, stark contrast, and limited color palette with strong visual statements.
- **Sagmeister & Walsh** — Uses bold, experimental typography and often full-bleed, striking photography as core visual elements.
- **Pentagram** — Showcases work with clean, high-contrast layouts and a focus on strong visual identity presented through minimal UI.
- **Stripe** — Features a light theme with carefully weighted typography and subtle use of negative space to create sophistication.
- **Apple** — Relies on strong photographic visuals combined with minimalist design and precise, legible typography on a clean background.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #fffef7;
  --color-ink-black: #000000;
  --color-medium-gray: #666666;
  --color-light-gray: #aaaaaa;
  --color-charcoal-gradient: #4d4c4a;
  --gradient-charcoal-gradient: linear-gradient(rgb(77, 76, 74), rgb(0, 0, 0));
  --color-vivid-orchid: #ffacea;
  --color-muted-teal: #a5ebd6;
  --color-deep-plum: #101731;
  --color-sunburst-yellow: #ffd001;
  --color-sky-blue: #009fff;
  --color-aqua-cyan: #48d1d6;
  --color-fiery-orange: #fc4c00;
  --color-hot-pink: #ee77cf;

  /* Typography — Font Families */
  --font-switzer: 'Switzer', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.4;
  --text-body-sm: 14px;
  --leading-body-sm: 1.4;
  --text-body: 16px;
  --leading-body: 1.4;
  --text-subheading: 18px;
  --leading-subheading: 1.4;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.4;
  --tracking-heading-sm: -0.36px;
  --text-heading: 34px;
  --leading-heading: 1.25;
  --tracking-heading: -0.68px;
  --text-heading-lg: 54px;
  --leading-heading-lg: 1.25;
  --tracking-heading-lg: -1.242px;
  --text-display: 64px;
  --leading-display: 1;
  --tracking-display: -1.728px;
  --text-display-lg: 84px;
  --leading-display-lg: 1;
  --tracking-display-lg: -3.36px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-112: 112px;

  /* Layout */
  --section-gap: 48px;
  --card-padding: 48px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-full: 1440px;
  --radius-full-2: 1600px;

  /* Named Radii */
  --radius-other: 1440px;
  --radius-buttons: 1440px;

  /* Shadows */
  --shadow-subtle: rgba(255, 255, 255, 0.2) 0px 0px 0px 1px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #fffef7;
  --color-ink-black: #000000;
  --color-medium-gray: #666666;
  --color-light-gray: #aaaaaa;
  --color-charcoal-gradient: #4d4c4a;
  --color-vivid-orchid: #ffacea;
  --color-muted-teal: #a5ebd6;
  --color-deep-plum: #101731;
  --color-sunburst-yellow: #ffd001;
  --color-sky-blue: #009fff;
  --color-aqua-cyan: #48d1d6;
  --color-fiery-orange: #fc4c00;
  --color-hot-pink: #ee77cf;

  /* Typography */
  --font-switzer: 'Switzer', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.4;
  --text-body-sm: 14px;
  --leading-body-sm: 1.4;
  --text-body: 16px;
  --leading-body: 1.4;
  --text-subheading: 18px;
  --leading-subheading: 1.4;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.4;
  --tracking-heading-sm: -0.36px;
  --text-heading: 34px;
  --leading-heading: 1.25;
  --tracking-heading: -0.68px;
  --text-heading-lg: 54px;
  --leading-heading-lg: 1.25;
  --tracking-heading-lg: -1.242px;
  --text-display: 64px;
  --leading-display: 1;
  --tracking-display: -1.728px;
  --text-display-lg: 84px;
  --leading-display-lg: 1;
  --tracking-display-lg: -3.36px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-112: 112px;

  /* Border Radius */
  --radius-full: 1440px;
  --radius-full-2: 1600px;

  /* Shadows */
  --shadow-subtle: rgba(255, 255, 255, 0.2) 0px 0px 0px 1px;
}
```

# Adaptive ML — Style Reference
> Architectural Blueprint

**Theme:** light

Adaptive ML employs an architectural blueprint aesthetic: a stark white canvas punctuated by deep, high-contrast typography. Accents are not through color, but through subtle material distinctions like thin borders, matte rich black surfaces, and gradient-filled cards that feel like embedded product visuals. The overall impression is one of grounded precision and advanced technology.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, navigation backgrounds, default filled button backgrounds |
| Ink Black | `#272421` | `--color-ink-black` | Primary text, darkest surface elements, active borders. Creates high contrast on white backgrounds |
| Chalk Gray | `#edebe8` | `--color-chalk-gray` | Subtle background surfaces, desaturated body text, hovered navigation items, thin borders |
| Parchment | `#e3e3e2` | `--color-parchment` | Subtle background surfaces, particularly for elevated card elements |
| Steel Gray | `#7d7c7a` | `--color-steel-gray` | Muted secondary text, icon strokes, subtle borders |
| Carbon | `#333333` | `--color-carbon` | Link text, dark borders for ghost buttons |
| Mist | `#908d89` | `--color-mist` | Tertiary text, decorative borders |
| True Black | `#000000` | `--color-true-black` | Shadow tints, decorative icon fills |

## Tokens — Typography

### Diatype — Primary typeface for headings, body text, and UI elements. Wide range of weights and sizes supports a hierarchical and precise content structure. · `--font-diatype`
- **Substitute:** Inter
- **Weights:** 400, 500, 700
- **Sizes:** 14px, 15px, 18px, 24px, 32px, 48px, 72px, 88px
- **Line height:** 0.90, 1.00, 1.20, 1.30, 1.40, 1.43
- **Letter spacing:** -0.42px at 14px, -0.45px at 15px, -0.54px at 18px
- **Role:** Primary typeface for headings, body text, and UI elements. Wide range of weights and sizes supports a hierarchical and precise content structure.

### Diatype Mono — Monospaced font for code snippets, metadata, or small, technical labels. · `--font-diatype-mono`
- **Substitute:** IBM Plex Mono
- **Weights:** 400
- **Sizes:** 11px, 13px
- **Line height:** 1.00, 1.40
- **Letter spacing:** 0.33px at 11px, 0.39px at 13px, 1.17px at 13px (specific instances)
- **Role:** Monospaced font for code snippets, metadata, or small, technical labels.

### Egyptienne F LT — Display typeface for large, impactful headlines, offering a classic serif counterpoint to the sans-serif Diatype. Features ligatures ('liga') for improved visual flow. · `--font-egyptienne-f-lt`
- **Substitute:** Playfair Display
- **Weights:** 400, 500
- **Sizes:** 22px, 77px, 94px
- **Line height:** 0.90, 1.00, 1.20
- **Letter spacing:** -2.31px at 77px, -2.82px at 94px, -0.66px at 22px
- **OpenType features:** `"liga"`
- **Role:** Display typeface for large, impactful headlines, offering a classic serif counterpoint to the sans-serif Diatype. Features ligatures ('liga') for improved visual flow.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 11px | 1.4 | 0.33px | `--text-caption` |
| subheading | 22px | 1.2 | -0.66px | `--text-subheading` |
| heading | 48px | 1 | — | `--text-heading` |
| heading-lg | 72px | 0.9 | — | `--text-heading-lg` |
| display | 94px | 0.9 | -2.82px | `--text-display` |

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
| 48 | 48px | `--spacing-48` |
| 56 | 56px | `--spacing-56` |
| 60 | 60px | `--spacing-60` |
| 64 | 64px | `--spacing-64` |
| 76 | 76px | `--spacing-76` |
| 80 | 80px | `--spacing-80` |
| 84 | 84px | `--spacing-84` |
| 88 | 88px | `--spacing-88` |
| 136 | 136px | `--spacing-136` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 1600px |
| cards | 8.96px |
| buttons | 8.96px |
| decorative | 20px |
| uiElements | 8.96px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| md | `rgba(39, 36, 33, 0.1) 0px 4px 12px 0px` | `--shadow-md` |

### Layout

- **Section gap:** 136px
- **Card padding:** 24px
- **Element gap:** 8px

## Components

### Filled Default Button
**Role:** Primary action button.

Background: Canvas White (#ffffff). Text: Ink Black (#272421). Border: Ink Black (#272421) 1px. Radius: 8.96px. Padding: 16px vertical, 24px horizontal. Appears for 'Contact' in header, and 'Book a Demo'.

### Ghost Text Button
**Role:** Secondary action or navigation item.

Background: transparent. Text: Carbon (#333333). No border. No explicit padding, text-based link. Used for navigation items like 'Product', 'Use Cases'.

### Outline Pill Button
**Role:** Tertiary action or filter tag.

Background: transparent. Text: Ink Black (#272421). Border: Ink Black (#272421) 1px. Radius: 1600px (fully rounded). Padding: 16px vertical, 24px horizontal. Used for 'Book a Demo' with an arrow icon.

### Elevated Content Card
**Role:** Highlighted content block.

Background: transparent. Border radius: 8.96px. Shadow: rgba(39, 36, 33, 0.1) 0px 4px 12px 0px. No explicit padding in the base component; internal elements define spacing. Used for 'Bootstrap with Reinforcement Learning' card.

### Navigation Link
**Role:** Top navigation items.

Text: Ink Black (#272421). Background: transparent. Border: transparent. Active/hover states likely use Chalk Gray (#edebe8) for text or a subtle border. Font: Diatype, 15px, 400 weight.

### Informational Status Card
**Role:** Colored content blocks for specific use cases.

Backgrounds determined by vibrant, irregular gradients not defined as core tokens. Text: Canvas White (#ffffff). Border radius: 8.96px. No shadow. Used for 'RAG enterprise search', 'Customer support', 'Text-to-SQL' cards.

## Do's and Don'ts

### Do
- Prioritize Ink Black (#272421) and Canvas White (#ffffff) for high-contrast typography and base surfaces.
- Use Diatype for all primary text elements, adjusting weight and size for hierarchy.
- Apply a consistent 8.96px border radius to all interactive elements like buttons and cards, creating a soft, uniform touch.
- Employ the rgba(39, 36, 33, 0.1) 0px 4px 12px 0px shadow for cards to provide subtle elevation without distraction.
- Utilize Ink Black (#272421) for active borders on elements that require definition against a white background.
- Maintain generous section spacing at 136px to ensure content breathability.
- Reserve Egyptienne F LT for display-level headings (77px, 94px) to add a strong, unique typographic statement.

### Don't
- Avoid using highly saturated colors for functional UI elements; allow gradient-filled cards to provide the vibrant visual interest.
- Do not deviate from the dominant Canvas White (#ffffff) page background, maintaining the clean, architectural aesthetic.
- Refrain from heavy, multi-layered shadows; stick to the single, subtle card shadow definition.
- Avoid decorative borders on primary content sections; rely on spacing and typography to articulate content blocks.
- Do not use Diatype Mono for general body or heading text; it is strictly for technical or metadata display.
- Do not apply strong, explicit box shadows to buttons; their distinction comes from background fills and borders.

## Elevation

- **Elevated Content Card:** `rgba(39, 36, 33, 0.1) 0px 4px 12px 0px`

## Imagery

This site uses a mix of unique, abstract gradient illustrations and abstract geometric product icons. The gradients are vivid and irregular, appearing as embedded background fills within cards, rather than as separate full-bleed images. Photography is absent. Icons, such as the Adaptive ML logo or internal process diagrams, are minimalist, often monochrome (Ink Black), and geometric, emphasizing clarity and technical precision. Imagery serves to create atmospheric differentiation and to visually represent abstract concepts or product features within the UI, without overwhelming the UI itself. The density of imagery is balanced, with large sections of text-dominant content offset by these visually rich cards and subtle icons.

## Layout

The page adheres to a max-width contained layout for primary content, centered on the screen, creating a focused reading experience. The hero section is full-bleed, featuring a large, centered Egyptienne F LT headline over a white background, accompanied by a smaller sans-serif subtext and a ghost CTA. Sections generally follow a consistent vertical rhythm with a 136px sectionGap. Content is primarily arranged in vertical stacks or two-column text-left/image-right configurations (where 'image' is often a gradient card or abstract graphic). Navigation is a fixed top bar with a left-aligned logo and right-aligned text links and a filled 'Contact' button. Feature displays often utilize a grid of cards, sometimes with gradient backgrounds, maintaining a clean, structured appearance.

## Agent Prompt Guide

Quick Color Reference: 
text: #272421
background: #ffffff
border: #272421
accent: no distinct accent color
primary action: no distinct CTA color

Example Component Prompts:
1. Create a primary hero section: Canvas White background. Headline 'Own your AI. Own your Intelligence Layer.' using Egyptienne F LT, 94px, weight 500, letter-spacing -2.82px, color Ink Black (#272421). Subtext 'Build, own, and deploy specialized LLMs. Drive business value through Reinforcement Learning.' using Diatype, 18px, weight 400, color Ink Black (#272421). Below, an Outline Pill Button with text 'BOOK A DEMO' using Diatype, 16px, weight 400, color Ink Black (#272421), transparent background, Ink Black (#272421) 1px border, 1600px radius, 16px vertical, 24px horizontal padding and a right arrow icon.
2. Create an Elevated Content Card: Background transparent, 8.96px border-radius, shadow rgba(39, 36, 33, 0.1) 0px 4px 12px 0px. Inside, center-align a headline 'Bootstrap with Reinforcement Learning' using Diatype, 32px, weight 500, color Ink Black (#272421). Below it, body text 'Generate synthetic data. Fine-tune with reinforcement learning. Outperform frontier APIs with small, specialized models.' using Diatype, 14px, weight 400, color Steel Gray (#7d7c7a).
3. Create a navigation bar item for 'PRODUCT': Text 'PRODUCT' using Diatype, 15px, weight 400, color Carbon (#333333). Transparent background. No border. Apply 10px right padding to the text block.
4. Create a Filled Default Button: Text 'CONTACT' using Diatype, 15px, weight 400, color Ink Black (#272421). Background Canvas White (#ffffff). 1px border with Chalk Gray (#edebe8). 8.96px border radius, 16px vertical, 24px horizontal padding.

## Similar Brands

- **Anthropic** — Similar strong typographic hierarchy on a clean white background, leveraging dark text for impact and minimal UI elements. Both use a highly constrained neutral palette supplemented by embedded, vivid graphics.
- **Iterate.ai** — Shared focus on deep, impactful headlines on a minimalist canvas, with subtle card elevation and a high-tech, AI-focused subject matter visually communicated through abstract imagery rather than photography.
- **Vercel** — Employs a precise, developer-tool aesthetic with strong typography, a neutral color palette, and a focus on clarity and functional design over decorative elements, using subtle shadows and borders for definition.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ink-black: #272421;
  --color-chalk-gray: #edebe8;
  --color-parchment: #e3e3e2;
  --color-steel-gray: #7d7c7a;
  --color-carbon: #333333;
  --color-mist: #908d89;
  --color-true-black: #000000;

  /* Typography — Font Families */
  --font-diatype: 'Diatype', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-diatype-mono: 'Diatype Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-egyptienne-f-lt: 'Egyptienne F LT', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.4;
  --tracking-caption: 0.33px;
  --text-subheading: 22px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.66px;
  --text-heading: 48px;
  --leading-heading: 1;
  --text-heading-lg: 72px;
  --leading-heading-lg: 0.9;
  --text-display: 94px;
  --leading-display: 0.9;
  --tracking-display: -2.82px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
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
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-76: 76px;
  --spacing-80: 80px;
  --spacing-84: 84px;
  --spacing-88: 88px;
  --spacing-136: 136px;

  /* Layout */
  --section-gap: 136px;
  --card-padding: 24px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-lg: 8.96px;
  --radius-2xl: 20px;
  --radius-full: 1600px;

  /* Named Radii */
  --radius-tags: 1600px;
  --radius-cards: 8.96px;
  --radius-buttons: 8.96px;
  --radius-decorative: 20px;
  --radius-uielements: 8.96px;

  /* Shadows */
  --shadow-md: rgba(39, 36, 33, 0.1) 0px 4px 12px 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ink-black: #272421;
  --color-chalk-gray: #edebe8;
  --color-parchment: #e3e3e2;
  --color-steel-gray: #7d7c7a;
  --color-carbon: #333333;
  --color-mist: #908d89;
  --color-true-black: #000000;

  /* Typography */
  --font-diatype: 'Diatype', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-diatype-mono: 'Diatype Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-egyptienne-f-lt: 'Egyptienne F LT', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.4;
  --tracking-caption: 0.33px;
  --text-subheading: 22px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.66px;
  --text-heading: 48px;
  --leading-heading: 1;
  --text-heading-lg: 72px;
  --leading-heading-lg: 0.9;
  --text-display: 94px;
  --leading-display: 0.9;
  --tracking-display: -2.82px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-76: 76px;
  --spacing-80: 80px;
  --spacing-84: 84px;
  --spacing-88: 88px;
  --spacing-136: 136px;

  /* Border Radius */
  --radius-lg: 8.96px;
  --radius-2xl: 20px;
  --radius-full: 1600px;

  /* Shadows */
  --shadow-md: rgba(39, 36, 33, 0.1) 0px 4px 12px 0px;
}
```

# Windsurf — Style Reference
> Deep Space Command Center

**Theme:** dark

Windsurf operates with a high-contrast, dark-mode scheme, using a deep navy background that evokes a professional, sophisticated environment. A vibrant, almost neon cyan serves as the primary accent, signaling interactive elements and highlighting key information, complemented by a softer magenta for secondary accents. Typography is a blend of impactful, large-scale headlines with subtly tracked small text, creating a dynamic yet precise visual hierarchy. Components are lightweight and often borderless, preferring subtle color shifts and soft corners over heavy shadows or solid fills.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `linear-gradient(135deg, rgb(1, 28, 66) 0%, rgb(20, 55, 110) 100%)` | `--color-midnight-ink` | Primary page background, footer, deep surface elements. Creates a high-contrast canvas for bright accents; Background gradient for hero sections and large content blocks, adding depth to the primary dark canvas |
| Arctic Mist | `#f8f1e5` | `--color-arctic-mist` | Subtle light background color for cards and sections, providing visual breathing room on the dark canvas |
| Platinum White | `#ffffff` | `--color-platinum-white` | Primary text color for headlines and core content on dark backgrounds, selected button text within accents |
| Slate Text | `#696962` | `--color-slate-text` | Muted secondary text color, body copy, and helper text. Provides sufficient contrast against lighter backgrounds |
| Ash Border | `#c0c1c6` | `--color-ash-border` | Subtle borders, dividers, ghost button outlines, and inactive iconography. Offers soft visual separation without harsh lines |
| Charcoal Black | `#0b100f` | `--color-charcoal-black` | Text color against very light backgrounds, such as button text on the cyan accent |
| Neon Cyan | `#34e8bb` | `--color-neon-cyan` | Teal action color for filled buttons, selected navigation states, and focused conversion moments. |
| Electric Magenta | `#fb9ce5` | `--color-electric-magenta` | Secondary brand accent for ghost button borders, decorative icons, and call-to-action text that requires a different emphasis |
| Plasma Pink Gradient | `#a95af8` | `--color-plasma-pink-gradient` | Vivid decorative element, background in specific highlight cards, and an essential part of abstract background graphics |

## Tokens — Typography

### ui-sans-serif — ui-sans-serif — detected in extracted data but not described by AI · `--font-ui-sans-serif`
- **Weights:** 400
- **Sizes:** 14px, 16px
- **Line height:** 1.43, 1.5
- **Role:** ui-sans-serif — detected in extracted data but not described by AI

### tomatoGrotesk — Primary display font for hero headlines and impactful section titles. Its light weight (300) at large sizes creates authority through restraint, avoiding the shouting typical of bold headings. · `--font-tomatogrotesk`
- **Substitute:** system-ui
- **Weights:** 300, 400, 500
- **Sizes:** 40px, 48px, 64px, 72px, 96px
- **Line height:** 1.00
- **Letter spacing:** -1.44px at 40px, -0.86px at 72px, -0.64px at 64px
- **Role:** Primary display font for hero headlines and impactful section titles. Its light weight (300) at large sizes creates authority through restraint, avoiding the shouting typical of bold headings.

### DM Sans — Used for all subheadings, body copy, and navigation labels. Its versatility in weights and sizes manages hierarchy across various content types, keeping readability high. · `--font-dm-sans`
- **Substitute:** Arial, sans-serif
- **Weights:** 400, 500, 600, 700
- **Sizes:** 10px, 12px, 14px, 16px, 18px, 20px, 28px, 40px
- **Line height:** 1.00, 1.30, 1.33, 1.50, 1.56, 1.71, 2.40
- **Letter spacing:** -0.72px at 40px, -0.4px at 20px, -0.28px at 14px
- **Role:** Used for all subheadings, body copy, and navigation labels. Its versatility in weights and sizes manages hierarchy across various content types, keeping readability high.

### DM Mono — Monospaced font for code snippets, tags, and secondary action buttons, providing a technical, precise feel. The letter-spacing adds clarity to often dense content. · `--font-dm-mono`
- **Substitute:** monospace
- **Weights:** 400, 500
- **Sizes:** 12px, 14px, 16px, 18px
- **Line height:** 1.20, 1.43, 1.56, 1.71
- **Letter spacing:** 0.8px at 16px, 0.7px at 14px
- **Role:** Monospaced font for code snippets, tags, and secondary action buttons, providing a technical, precise feel. The letter-spacing adds clarity to often dense content.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.71 | — | `--text-caption` |
| body | 14px | 1.5 | -0.28px | `--text-body` |
| heading-sm | 20px | 1.5 | -0.4px | `--text-heading-sm` |
| heading | 40px | 1 | -1.44px | `--text-heading` |
| heading-lg | 48px | 1 | — | `--text-heading-lg` |
| display | 64px | 1 | -0.64px | `--text-display` |

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
| 28 | 28px | `--spacing-28` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 56 | 56px | `--spacing-56` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 112 | 112px | `--spacing-112` |
| 144 | 144px | `--spacing-144` |
| 160 | 160px | `--spacing-160` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 9999px |
| cards | 8px |
| buttons | 2px |
| navigation | 9999px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| md | `rgba(0, 0, 0, 0.2) 0px 10px 15px -3px, rgba(0, 0, 0, 0.2)...` | `--shadow-md` |
| subtle | `rgba(52, 211, 153, 0.5) 0px 1px 2px 0px` | `--shadow-subtle` |
| sm | `rgba(0, 0, 0, 0.2) 0px 4px 6px -1px, rgba(0, 0, 0, 0.2) 0...` | `--shadow-sm` |
| subtle-2 | `rgba(251, 191, 36, 0.5) 0px 1px 2px 0px` | `--shadow-subtle-2` |
| md-2 | `rgba(0, 0, 0, 0.22) 0px 4px 16px 0px, rgba(0, 0, 0, 0.14)...` | `--shadow-md-2` |
| subtle-3 | `rgb(251, 156, 229) 0px 0px 0px 1px inset` | `--shadow-subtle-3` |

### Layout

- **Section gap:** 64px
- **Card padding:** 12px
- **Element gap:** 8px

## Components

### Primary Action Button
**Role:** Calls to action that drive key user behavior (e.g., download, submit).

Filled rectangular button with Neon Cyan background (#34e8bb), Charcoal Black text (#0b100f), 2px border radius, and padding of 16px vertical, 24px horizontal. Uses DM Sans font, typically weight 500.

### Ghost Accent Button
**Role:** Secondary actions or links that need visual emphasis without overwhelming the primary action.

Transparent background with a border and text in Electric Magenta (#fb9ce5). Text is DM Sans, 16px, with no padding or border radius. Used for 'Explore Features' or 'Learn more' links.

### Download Banner Button
**Role:** Prominent, often full-width or oversized, call to action in hero sections.

Large button with Neon Cyan background (#34e8bb), Charcoal Black text (#003326 - a very dark teal close to black), 0px radius, with generous horizontal padding (40px) and no vertical padding. Uses DM Mono font for a technical feel.

### Content Card
**Role:** Container for feature descriptions, process steps, or grouped information.

Cards can have a subtle Arctic Mist background (#f8f1e5) or transparent. Corner radius is 8px. Internal padding is 12px. No visible shadow by default.

### Tag/Pill
**Role:** Small, distinct labels for categories, statuses, or new features.

Features a full border radius (9999px) making it pill-shaped. Examples include 'New Introducing Windsurf 2.0' where the background is transparent and text is Electric Magenta.

### Code Input Field
**Role:** User input fields, primarily for code or technical information.

Transparent background with White text (#ffffff). Border is Ash Border (#c0c1c6). No radius, offering a sharp, functional edge.

## Do's and Don'ts

### Do
- Always use Midnight Ink (#011c42) for large background surfaces to maintain the deep, dark theme.
- Apply Neon Cyan (#34e8bb) consistently as the background for primary call-to-action buttons.
- Headlines should leverage tomatoGrotesk (weights 300-500) for impactful presence, especially the distinctive light 300 weight at larger sizes.
- Text against dark backgrounds should primarily use Platinum White (#ffffff) for readability, reserving Slate Text (#696962) for secondary, less prominent text.
- Utilize Electric Magenta (#fb9ce5) for ghost button borders and decorative elements to provide secondary visual interest without overshadowing the primary cyan.
- Implement a 2px border radius for all filled buttons and a 8px radius for cards to distinguish interaction elements from content blocks.
- Ensure generous vertical spacing between sections (64px) to provide ample breathing room between content blocks on the dark canvas.

### Don't
- Do not introduce new saturated primary colors; stick to the Neon Cyan and Electric Magenta for brand accents.
- Avoid heavy drop shadows on individual elements; prefer subtle surface shifts or border accents for depth.
- Do not use bold weights for tomatoGrotesk headlines; the system relies on lighter weights for its distinctive authority.
- Refrain from using excessively small text sizes (below 12px) for DM Sans to maintain legibility on the dark background.
- Do not apply large, rounded corners globally; save 9999px radius primarily for small tags and pills.
- Avoid dense, unbroken blocks of text; break content with imagery or concise paragraphs to suit the high-contrast display.
- Do not default to generic monospace fonts; specifically use DM Mono for code-related text to maintain brand consistency.

## Elevation

This system minimizes traditional drop shadows, primarily relying on flat surfaces and color contrast for hierarchy. When shadows are present, they are subtle and appear mostly for tooltips or modal elements, often with colored tints like rgba(52, 211, 153, 0.5) to maintain the brand's vibrant feel, enhancing elements rather than creating heavy stacking. The preferred method for perceived depth is through subtle background color changes (e.g., Arctic Mist for cards on Midnight Ink).

## Imagery

The visual language predominantly features abstract, generative graphics with undulating wave patterns, often with colorful gradients (like the Plasma Pink Gradient) against the deep navy backdrop. These serve a decorative, atmospheric role rather than explanatory. Product screenshots, when present, are clean, full-bleed, and often framed directly into the dark UI without additional ornamentation, showcasing the software itself. Icons are minimal, either solid white or using the Electric Magenta or Neon Cyan accents, maintaining a high-tech, functional aesthetic. The density is image-light, focusing more on crisp UI and typography.

## Layout

The page structure is full-bleed with content often centered or presented in distinct, spacious horizontal blocks. The hero section is full-width, featuring a prominent centered headline over the abstract dark gradient background, accompanied by a cluster of call-to-action buttons. Subsequent sections alternate between clear content blocks and sometimes integrate background graphics seamlessly. Features and descriptions typically use a two-column layout (text-left/visual-right or vice-versa) or stacked centered content. Navigation is a persistent top bar, with interactive elements highlighted by the brand's accent colors. Vertical spacing is generous between sections.

## Agent Prompt Guide

**Quick Color Reference:**
text: #ffffff
background: #011c42
border: #c0c1c6
accent: #fb9ce5
primary action: #34e8bb (filled action)

**3-5 Example Component Prompts:**
1. Create a Primary Action Button: #34e8bb background, #0b100f text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Design a feature card: background "Arctic Mist" (#f8f1e5), 8px border-radius, 12px internal padding. Title should be "Cascade" using DM Sans, weight 700, size 40px, text Charcoal Black (#0b100f). Body text in DM Sans, weight 400, size 16px, text Slate Text (#696962).
3. Create a navigation link for "Pricing" using DM Sans, weight 500, size 16px, text Platinum White (#ffffff), with no background or border, and 9999px radius if applicable for very active/highlighted state as a visual indicator similar to tags.
4. Produce a pill-shaped tag reading "New Introducing Windsurf 2.0" with transparent background, Electric Magenta (#fb9ce5) text, and 9999px border radius, using DM Mono, weight 500, size 14px, letter-spacing 0.7px.

## Similar Brands

- **Vercel** — Uses a dark-mode base with sharp, modern typography and a focus on developer tools and cloud services.
- **Replit** — Features a dark UI, a clean coding environment aesthetic, and a similar approach to showcasing developer tools with minimal, functional design.
- **Cursor** — A developer-focused AI tool with a high-contrast dark theme, emphasizing code and functionality over extraneous decoration.
- **GitHub Copilot** — Adopts a dark, code-centric interface with clear typography and functional accents, serving a developer audience.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #011c42;
  --gradient-midnight-ink: linear-gradient(135deg, rgb(1, 28, 66) 0%, rgb(20, 55, 110) 100%);
  --color-arctic-mist: #f8f1e5;
  --color-platinum-white: #ffffff;
  --color-slate-text: #696962;
  --color-ash-border: #c0c1c6;
  --color-charcoal-black: #0b100f;
  --color-neon-cyan: #34e8bb;
  --color-electric-magenta: #fb9ce5;
  --color-plasma-pink-gradient: #a95af8;

  /* Typography — Font Families */
  --font-ui-sans-serif: 'ui-sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-tomatogrotesk: 'tomatoGrotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-dm-sans: 'DM Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-dm-mono: 'DM Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.71;
  --text-body: 14px;
  --leading-body: 1.5;
  --tracking-body: -0.28px;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.5;
  --tracking-heading-sm: -0.4px;
  --text-heading: 40px;
  --leading-heading: 1;
  --tracking-heading: -1.44px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1;
  --text-display: 64px;
  --leading-display: 1;
  --tracking-display: -0.64px;

  /* Typography — Weights */
  --font-weight-light: 300;
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
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-112: 112px;
  --spacing-144: 144px;
  --spacing-160: 160px;

  /* Layout */
  --section-gap: 64px;
  --card-padding: 12px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-tags: 9999px;
  --radius-cards: 8px;
  --radius-buttons: 2px;
  --radius-navigation: 9999px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.2) 0px 10px 15px -3px, rgba(0, 0, 0, 0.2) 0px 4px 6px -4px;
  --shadow-subtle: rgba(52, 211, 153, 0.5) 0px 1px 2px 0px;
  --shadow-sm: rgba(0, 0, 0, 0.2) 0px 4px 6px -1px, rgba(0, 0, 0, 0.2) 0px 2px 4px -2px;
  --shadow-subtle-2: rgba(251, 191, 36, 0.5) 0px 1px 2px 0px;
  --shadow-md-2: rgba(0, 0, 0, 0.22) 0px 4px 16px 0px, rgba(0, 0, 0, 0.14) 0px 1px 3px 0px;
  --shadow-subtle-3: rgb(251, 156, 229) 0px 0px 0px 1px inset;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #011c42;
  --color-arctic-mist: #f8f1e5;
  --color-platinum-white: #ffffff;
  --color-slate-text: #696962;
  --color-ash-border: #c0c1c6;
  --color-charcoal-black: #0b100f;
  --color-neon-cyan: #34e8bb;
  --color-electric-magenta: #fb9ce5;
  --color-plasma-pink-gradient: #a95af8;

  /* Typography */
  --font-ui-sans-serif: 'ui-sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-tomatogrotesk: 'tomatoGrotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-dm-sans: 'DM Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-dm-mono: 'DM Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.71;
  --text-body: 14px;
  --leading-body: 1.5;
  --tracking-body: -0.28px;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.5;
  --tracking-heading-sm: -0.4px;
  --text-heading: 40px;
  --leading-heading: 1;
  --tracking-heading: -1.44px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1;
  --text-display: 64px;
  --leading-display: 1;
  --tracking-display: -0.64px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-112: 112px;
  --spacing-144: 144px;
  --spacing-160: 160px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-full: 9999px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.2) 0px 10px 15px -3px, rgba(0, 0, 0, 0.2) 0px 4px 6px -4px;
  --shadow-subtle: rgba(52, 211, 153, 0.5) 0px 1px 2px 0px;
  --shadow-sm: rgba(0, 0, 0, 0.2) 0px 4px 6px -1px, rgba(0, 0, 0, 0.2) 0px 2px 4px -2px;
  --shadow-subtle-2: rgba(251, 191, 36, 0.5) 0px 1px 2px 0px;
  --shadow-md-2: rgba(0, 0, 0, 0.22) 0px 4px 16px 0px, rgba(0, 0, 0, 0.14) 0px 1px 3px 0px;
  --shadow-subtle-3: rgb(251, 156, 229) 0px 0px 0px 1px inset;
}
```

# Galileo-ft — Style Reference
> Deep-space command center

**Theme:** dark

Galileo projects a deep-space command center aesthetic: a dark canvas punctuated by stark whites and energetic, vibrant blue-violet accents. The visual system balances substantial, wide type with delicate ghost elements, creating an impression of technical authority and precision. Elevation is minimal, giving way to smooth transitions and subtle background shifts. The overall feel is restrained and deliberate, with color reserved for functional highlights and interaction – guiding the user through complex financial information with clarity and a sense of controlled power.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#03081a` | `--color-midnight-ink` | Primary background, deep surface color for cards and sections |
| Void Shadow | `#020626` | `--color-void-shadow` | Secondary background layer, subtle surface elevation, text color against very light backgrounds |
| Galileo Violet | `linear-gradient(90deg, rgb(5, 161, 201) 0%, rgb(61, 80, 252) 100%)` | `--color-galileo-violet` | Primary brand accent, interactive elements like buttons and links, icon fills; Gradient for hero sections and prominent interactive elements, creating dynamic visual interest; Gradient for calls to action, drawing attention with a soft, engaging color transition |
| Cosmic Gray | `#292f66` | `--color-cosmic-gray` | Muted UI elements like secondary text, dividers, and subtle borders. Provides depth against darker backgrounds |
| Starlight Blue | `#aab1f2` | `--color-starlight-blue` | Subtle light text, link underlines, and decorative accents against dark backgrounds, providing visual lightness |
| Neon Aqua | `#05cee0` | `--color-neon-aqua` | Decorative highlights, specific icon fills, or secondary accents to add a contrasting pop of color |
| Nebula Blue | `#4d5499` | `--color-nebula-blue` | Tertiary text, less prominent borders and dividers, for content segmentation without strong contrast |
| Deep Space Blue | `#080f4d` | `--color-deep-space-blue` | Subtle decorative elements and fills within the dark theme, for gradients that add visual texture without distraction |
| Lunar Dust | `#d9ddff` | `--color-lunar-dust` | Subtle text and UI elements on lighter secondary surfaces, providing a near-white contrast |
| Flux Orange | `#d80c9a` | `--color-flux-orange` | Vivid decorative accent color, used sparingly in graphics or unique UI elements for high impact |
| Electric Cyan | `#05e0e0` | `--color-electric-cyan` | Accent for links and icon highlights, signalling interactivity or important information on dark backgrounds |
| Hazy Iris | `#7a83cc` | `--color-hazy-iris` | Subtle background for UI elements, less prominent text, and slight shifts in surface tone |
| Cleanroom White | `#ffffff` | `--color-cleanroom-white` | Key text on dark backgrounds, primary navigation items, and button text for high contrast |
| Panel Gray | `#f5f6ff` | `--color-panel-gray` | Background for secondary content panels and light-themed sections, offering a soft, almost white surface |

## Tokens — Typography

### Plain Ultrathin — Hero headlines. The ultrathin weight, usually reserved for display text, is applied for headlines to create a sense of expansive, light authority rather than forceful shouting. · `--font-plain-ultrathin`
- **Substitute:** Montserrat, sans-serif
- **Weights:** 100
- **Sizes:** 42px, 56px, 83px, 147px
- **Line height:** 0.80, 1.00, 1.10, 1.20
- **Letter spacing:** -0.02em at 42px and 56px, -0.01em at 83px and 147px
- **Role:** Hero headlines. The ultrathin weight, usually reserved for display text, is applied for headlines to create a sense of expansive, light authority rather than forceful shouting.

### Plain Ultralight — Sub-headlines and emphasized body sections. Maintains the light, airy feel of the display type while providing more substance for readability. · `--font-plain-ultralight`
- **Substitute:** Montserrat, sans-serif
- **Weights:** 100
- **Sizes:** 28px
- **Line height:** 1.30
- **Letter spacing:** -0.02em
- **Role:** Sub-headlines and emphasized body sections. Maintains the light, airy feel of the display type while providing more substance for readability.

### Plain Light — Body copy and descriptive text. The light weight ensures a consistent brand voice without overwhelming the visual hierarchy. · `--font-plain-light`
- **Substitute:** Montserrat, sans-serif
- **Weights:** 300
- **Sizes:** 12px, 14px
- **Line height:** 1.40, 1.50, 1.80
- **Letter spacing:** normal
- **Role:** Body copy and descriptive text. The light weight ensures a consistent brand voice without overwhelming the visual hierarchy.

### Plain — Navigation items, labels, and small functional text. The moderate letter-spacing creates distinct visual blocks for these elements. · `--font-plain`
- **Substitute:** Montserrat, sans-serif
- **Weights:** 300, 400
- **Sizes:** 10px, 13px, 14px, 16px
- **Line height:** 1.20, 1.30
- **Letter spacing:** 0.25em
- **Role:** Navigation items, labels, and small functional text. The moderate letter-spacing creates distinct visual blocks for these elements.

### Plain — Emphasized small text, button labels, and secondary navigation for clear hierarchy. · `--font-plain`
- **Substitute:** Montserrat, sans-serif
- **Weights:** 300, 400
- **Sizes:** 10px, 13px, 14px, 16px
- **Line height:** 1.20, 1.30
- **Letter spacing:** 0.25em
- **Role:** Emphasized small text, button labels, and secondary navigation for clear hierarchy.

### Times — Fallback and specific content sections, providing a traditional contrast to the modern sans-serifs. · `--font-times`
- **Substitute:** serif
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.20
- **Letter spacing:** normal
- **Role:** Fallback and specific content sections, providing a traditional contrast to the modern sans-serifs.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.2 | 2.5px | `--text-caption` |
| body | 14px | 1.5 | — | `--text-body` |
| subheading | 28px | 1.3 | -0.56px | `--text-subheading` |
| heading | 42px | 1.2 | -0.84px | `--text-heading` |
| heading-lg | 56px | 1.2 | -1.12px | `--text-heading-lg` |
| display | 83px | 1 | -0.83px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 52 | 52px | `--spacing-52` |
| 64 | 64px | `--spacing-64` |
| 104 | 104px | `--spacing-104` |
| 196 | 196px | `--spacing-196` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 34.704px |
| buttons | 47.7072px |
| interactive | 17.352px |

### Layout

- **Page max-width:** 1200px
- **Section gap:** 26px
- **Card padding:** 35px
- **Element gap:** 9px

## Components

### Ghost Navigation Button
**Role:** Primary navigation and links within dark context.

Transparent background, Cleanroom White text, no border, 0px radius, 0px padding. Text uses Plain font, 16px, weight 400.

### Primary Action Button
**Role:** Key calls to action requiring prominence.

Galileo Violet background (#3d50fc), Cleanroom White text (#ffffff), no border. Fully rounded corners (47.7072px radius). Padding: 14px vertical, 26px horizontal. Text uses Plain font, 16px, weight 400.

### Secondary Action Button
**Role:** Calls to action on lighter backgrounds that need to stand out.

Cleanroom White background (#ffffff), Galileo Violet text (#3d50fc), Galileo Violet border (#3d50fc). Fully rounded corners (47.7072px radius). Padding: 14px vertical, 26px horizontal. Text uses Plain font, 16px, weight 400.

### Subtle Card
**Role:** Container for secondary content or feature blocks.

Transparent background, no shadow. Rounded corners (34.704px radius). Padding: 35px in all directions. Uses Void Shadow text and Cosmic Gray elements inside.

### Product Insight Card
**Role:** Informational cards within a feature section.

Cleanroom White background (#ffffff), no shadow. Rounded corners (34.704px radius). Padding: 87px top, 0px right and bottom, 104px left. Contains Void Shadow text.

### Chat Bubble Initiator
**Role:** Persistent call-to-action for chat support.

Midnight Ink background (#03081a), 50% border radius for a circular shape. Located at the bottom center of the screen. Incorporates a small gradient for visual interest.

### Cyberbank Core Tag
**Role:** Filter or category tags for content segmentation.

Galileo Violet background (#3d50fc), Cleanroom White text (#ffffff). Rounded corners (34.704px radius). Padding: 14px vertical, 26px horizontal. Text uses Plain font, 16px, weight 400.

### Info Banner
**Role:** Top-level announcements or system messages.

Deep Space Blue background, Cleanroom White text. Minimal padding. Contains a 'Learn More' link.

## Do's and Don'ts

### Do
- Prioritize the Midnight Ink (#03081a) as the canvas background for most sections to maintain the dark theme.
- Use Galileo Violet (#3d50fc) for all primary interactive elements, ensuring it is the sole vibrant accent color for action.
- Apply Plain Ultrathin (weight 100) at large sizes for all main headlines to establish a sense of modern authority.
- Ensure buttons and primary interactive elements have a 47.7072px border radius for a distinct, soft pill shape.
- Space elements with a base unit of 4px; use 9px for element gaps and 35px for card padding.
- Structure page content using transparent cards with 34.704px radius on dark backgrounds, using subtle color #020626 where a distinct surface is needed.
- Employ the linear gradient `linear-gradient(90deg, rgb(5, 161, 201) 0%, rgb(61, 80, 252) 100%)` for hero backgrounds or significant visual emphasis.

### Don't
- Avoid using multiple vibrant chromatic colors; actively restrict accent colors to Galileo Violet, Neon Aqua, and Electric Cyan, with the latter two used sparingly for decoration.
- Do not introduce heavy drop shadows or strong elevation; prefer subtle background color shifts or transparent cards for depth.
- Refrain from using Times font for headlines or primary UI text; reserve it for specific content blocks if at all.
- Do not deviate from the high border radius for buttons; rounded corners are a signature element.
- Avoid excessive text density; maintain comfortable spacing and liberal use of negative space.
- Do not use dark text on dark backgrounds; ensure sufficient contrast with Cleanroom White (#ffffff) or Starlight Blue (#aab1f2) for legibility.
- Do not make every interactive element a filled button. Utilize ghost buttons and text links for secondary actions.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas | `#03081a` | The deepest background layer for the entire page, setting the dark theme. |
| 1 | Base Surface | `#020626` | Used for sections and cards that visually lift slightly from the canvas, providing a subtle layer differentiation. |
| 2 | Elevated Surface | `#FFFFFF` | A contrasting light surface for distinct content blocks, often used in alternating sections to break the dark theme. |

## Imagery

The visual language blends abstract, volumetric 3D shapes with detailed product screenshots. The 3D elements, often transparent or translucent with blue-violet tints, are primarily decorative, creating atmospheric depth in hero sections. Product screenshots are contained, precise, and often feature dark-mode UI, showcasing the platform's functionality within its own aesthetic. Icons are primarily outlined or filled with a single accent color, maintaining a clean, technical appearance. Imagery serves to establish a futuristic, high-tech atmosphere and showcase product capabilities, rather than featuring lifestyle or candid photography. Density is moderate, with imagery providing visual anchors surrounded by ample dark space.

## Layout

The layout follows a max-width contained model (effectively ~1200px), with some background elements extending full-bleed. The hero section is full-bleed, dark-themed, featuring a large, centered headline over abstract 3D visuals. Subsequent sections alternate between dark and light backgrounds, creating a clear vertical rhythm. Content is arranged in flexible grid patterns, often using 2-column or 3-column structures for text and corresponding visuals (product screenshots, descriptive text blocks). Vertical spacing between sections feels generous. Primary navigation is a top bar with minimalist ghost buttons. A persistent chat bubble is affixed to the bottom center of the viewport.

## Agent Prompt Guide

Quick Color Reference:
text: #ffffff
background: #03081a
border: #292f66
accent: #3d50fc
primary action: #3d50fc (filled action)

3-5 Example Component Prompts:
1. Create a Hero Section: background is `linear-gradient(90deg, rgb(5, 161, 201) 0%, rgb(61, 80, 252) 100%)`. Headline is 'Expanding the financial frontier' in Plain Ultrathin weight 100, 83px, #ffffff, letter-spacing -0.83px. Sub-text is 'We help banks...' in Plain Light weight 300, 14px, #aab1f2. Include a 'Let's Talk' Primary Action Button with Galileo Violet background (#3d50fc), Cleanroom White text (#ffffff), 47.7072px radius, 14px vertical and 26px horizontal padding.
2. Create a Feature Card: background is #020626, border 1px solid #292f66, 34.704px radius, 35px padding. Title is 'Engagement Channels' in Plain Ultralight weight 100, 28px, #ffffff. Body text is 'Deliver personalized...' in Plain Light weight 300, 14px, #aab1f2.
3. Create a Navigation Link: 'Deposits' in Plain weight 300, 16px, #ffffff, normal letter-spacing, on a transparent background with 0px padding and radius. Active state shows a subtle underline using Galileo Violet (#3d50fc).
4. Create a Secondary Action Button: 'Explore Cyberbank Core' with Cleanroom White background (#ffffff), Galileo Violet text (#3d50fc), Galileo Violet border (#3d50fc), 47.7072px radius, 14px vertical and 26px horizontal padding. Include an arrow icon in Galileo Violet.

## Similar Brands

- **Stripe** — Dark UI with strong, vibrant accent colors for calls to action, crisp typography, and an emphasis on technical sophistication.
- **Linear** — Minimalist dark theme, precise typography, and a deliberate use of color for functional elements rather than decoration.
- **Revolut Business** — Fintech focus with a modern, clean interface, often utilizing dark themes and strong, contrasting brand colors for interactive elements.
- **Plaid** — Focus on developer-friendly financial APIs with a high-tech, precise aesthetic, typically involving structured layouts and functional use of color.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #03081a;
  --color-void-shadow: #020626;
  --color-galileo-violet: #3d50fc;
  --gradient-galileo-violet: linear-gradient(90deg, rgb(5, 161, 201) 0%, rgb(61, 80, 252) 100%);
  --color-cosmic-gray: #292f66;
  --color-starlight-blue: #aab1f2;
  --color-neon-aqua: #05cee0;
  --color-nebula-blue: #4d5499;
  --color-deep-space-blue: #080f4d;
  --color-lunar-dust: #d9ddff;
  --color-flux-orange: #d80c9a;
  --color-electric-cyan: #05e0e0;
  --color-hazy-iris: #7a83cc;
  --color-cleanroom-white: #ffffff;
  --color-panel-gray: #f5f6ff;

  /* Typography — Font Families */
  --font-plain-ultrathin: 'Plain Ultrathin', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-plain-ultralight: 'Plain Ultralight', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-plain-light: 'Plain Light', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-plain: 'Plain', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-times: 'Times', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.2;
  --tracking-caption: 2.5px;
  --text-body: 14px;
  --leading-body: 1.5;
  --text-subheading: 28px;
  --leading-subheading: 1.3;
  --tracking-subheading: -0.56px;
  --text-heading: 42px;
  --leading-heading: 1.2;
  --tracking-heading: -0.84px;
  --text-heading-lg: 56px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -1.12px;
  --text-display: 83px;
  --leading-display: 1;
  --tracking-display: -0.83px;

  /* Typography — Weights */
  --font-weight-thin: 100;
  --font-weight-light: 300;
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-52: 52px;
  --spacing-64: 64px;
  --spacing-104: 104px;
  --spacing-196: 196px;

  /* Layout */
  --page-max-width: 1200px;
  --section-gap: 26px;
  --card-padding: 35px;
  --element-gap: 9px;

  /* Border Radius */
  --radius-sm: 0.864px;
  --radius-2xl: 17.352px;
  --radius-3xl: 34.704px;
  --radius-full: 47.7072px;
  --radius-full-2: 360px;

  /* Named Radii */
  --radius-cards: 34.704px;
  --radius-buttons: 47.7072px;
  --radius-interactive: 17.352px;

  /* Surfaces */
  --surface-canvas: #03081a;
  --surface-base-surface: #020626;
  --surface-elevated-surface: #FFFFFF;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #03081a;
  --color-void-shadow: #020626;
  --color-galileo-violet: #3d50fc;
  --color-cosmic-gray: #292f66;
  --color-starlight-blue: #aab1f2;
  --color-neon-aqua: #05cee0;
  --color-nebula-blue: #4d5499;
  --color-deep-space-blue: #080f4d;
  --color-lunar-dust: #d9ddff;
  --color-flux-orange: #d80c9a;
  --color-electric-cyan: #05e0e0;
  --color-hazy-iris: #7a83cc;
  --color-cleanroom-white: #ffffff;
  --color-panel-gray: #f5f6ff;

  /* Typography */
  --font-plain-ultrathin: 'Plain Ultrathin', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-plain-ultralight: 'Plain Ultralight', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-plain-light: 'Plain Light', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-plain: 'Plain', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-times: 'Times', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.2;
  --tracking-caption: 2.5px;
  --text-body: 14px;
  --leading-body: 1.5;
  --text-subheading: 28px;
  --leading-subheading: 1.3;
  --tracking-subheading: -0.56px;
  --text-heading: 42px;
  --leading-heading: 1.2;
  --tracking-heading: -0.84px;
  --text-heading-lg: 56px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -1.12px;
  --text-display: 83px;
  --leading-display: 1;
  --tracking-display: -0.83px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-52: 52px;
  --spacing-64: 64px;
  --spacing-104: 104px;
  --spacing-196: 196px;

  /* Border Radius */
  --radius-sm: 0.864px;
  --radius-2xl: 17.352px;
  --radius-3xl: 34.704px;
  --radius-full: 47.7072px;
  --radius-full-2: 360px;
}
```

# Tapbots — Style Reference
> Cosmic playful precision. Imagine floating among luminous violet and emerald constellations within a dark, welcoming void.

**Theme:** dark

Ivory's design system evokes a cosmic, playful yet precise feel, like exploring a high-tech constellation. Deep space purples and blacks provide a dramatic stage for luminous accents of violet and glowing green, creating a narrative of discovery. Spherical and rounded forms, particularly the 40px radius on interactive elements, soften the tech aesthetic, making the advanced functionality feel approachable.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Void | `#05050b` | `--color-midnight-void` | Primary page background, deepest darks for full-bleed sections. |
| Deep Shadow | `#1a1a1a` | `--color-deep-shadow` | Secondary background, subtly lighter than Midnight Void, used for hero areas and section dividers. |
| Carbon Gray | `#2c2c2c` | `--color-carbon-gray` | Darkest neutral for surface areas, like list backgrounds. |
| Graphite | `#484848` | `--color-graphite` | Dark gray text for less emphasis, used in secondary text blocks and labels. |
| Medium Gray | `#666666` | `--color-medium-gray` | Body text in less prominent sections, and subtle separators. |
| Light Gray | `#999999` | `--color-light-gray` | Placeholder text and disabled states, offers contrast without being stark white. |
| Stone Grey | `#a3a3a3` | `--color-stone-grey` | Subtle body text for informational segments. |
| Silver Tone | `#b3b3b3` | `--color-silver-tone` | Footnote text and secondary informational elements. |
| Pale Gray | `#c3c3c3` | `--color-pale-gray` | Light body text on dark backgrounds, used in feature lists. |
| Bright Silver | `#cccccc` | `--color-bright-silver` | For highlighting headings or primary callouts against dark backgrounds. |
| Ghost White | `#ffffff` | `--color-ghost-white` | Primary text color for maximum readability, particularly for headings and main body content against dark backgrounds. |
| Cosmic Violet | `#7047ba` | `--color-cosmic-violet` | Hero background color, establishing the brand's core identity with a deep, vivid purple. |
| Royal Plum | `#4c278` | `--color-royal-plum` | Darker shade of brand violet, used for hovered link states or subtle interactive elements. |
| Button Violet | `#301e4f` | `--color-button-violet` | Primary button background, providing a distinct interactive surface. |
| Luminous Violet | `#ba94ff` | `--color-luminous-violet` | Primary interactive accent color for links, buttons, and icons, drawing attention against dark backgrounds. |
| Highlight Violet | `#9466e7` | `--color-highlight-violet` | Accent for headings, adding a vibrant touch to key textual elements. |
| Pale Violet | `#cdd4f8` | `--color-pale-violet` | Supportive text color for highlighting specific content within body paragraphs. |
| Misty Violet | `#deccff` | `--color-misty-violet` | Softer accent text, providing a visual counterpoint to deeper tones. |
| Crimson Beam | `#ff3543` | `--color-crimson-beam` | Attention-grabbing accent for important links, icons, or to denote an alert state. |
| Emerald Glow | `#74ec5a` | `--color-emerald-glow` | Vivid accent for feature highlights or positive indicators. |
| Skyfire Gradient | `linear-gradient(to right bottom, rgb(108, 176, 255), rgb(247, 71, 255))` | `--color-skyfire-gradient` | Decorative gradient often used for celestial elements or abstract backgrounds. |
| Lunar Gradient | `linear-gradient(rgb(231, 230, 255), rgb(138, 137, 175))` | `--color-lunar-gradient` | Subtle background gradient for UI elements, hinting at depth. |
| Milky Way Gradient | `linear-gradient(rgb(255, 255, 255), rgb(217, 195, 255))` | `--color-milky-way-gradient` | Light background gradient for an airy, shimmering effect. |

## Tokens — Typography

### -apple-system — The `-apple-system` font is the singular choice, used across all weights and sizes for every text element from body content to hero headlines. This deliberate choice creates a cohesive, platform-native feel that prioritizes clarity and system integration over custom branding through typography. · `--font-apple-system`
- **Substitute:** system-ui
- **Weights:** 300, 400, 500, 600
- **Sizes:** 16px, 18px, 20px, 21px, 24px, 28px, 32px, 36px
- **Line height:** 0.84, 1.10, 1.20, 1.29, 1.40, 1.50, 1.70, 1.80
- **Role:** The `-apple-system` font is the singular choice, used across all weights and sizes for every text element from body content to hero headlines. This deliberate choice creates a cohesive, platform-native feel that prioritizes clarity and system integration over custom branding through typography.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body | 16px | 1.5 | — | `--text-body` |
| body-lg | 18px | 1.4 | — | `--text-body-lg` |
| subheading | 20px | 1.4 | — | `--text-subheading` |
| heading | 24px | 1.2 | — | `--text-heading` |
| heading-lg | 28px | 1.2 | — | `--text-heading-lg` |
| display-sm | 32px | 1.1 | — | `--text-display-sm` |
| display | 36px | 1.1 | — | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** spacious

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 12 | 12px | `--spacing-12` |
| 20 | 20px | `--spacing-20` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 60 | 60px | `--spacing-60` |
| 80 | 80px | `--spacing-80` |
| 144 | 144px | `--spacing-144` |
| 216 | 216px | `--spacing-216` |

### Border Radius

| Element | Value |
|---------|-------|
| icons | 40px |
| links | 40px |
| lists | 18px |
| buttons | 40px |

### Layout

- **Section gap:** 64px
- **Card padding:** 20px
- **Element gap:** 10px

## Components

### Primary Action Button
**Role:** Primary Call to Action

Rounded button with a deep violet background (`#301e4f`), high-contrast luminous violet text (`#ba94ff`), and a full pill-shaped radius of 40px. Padding is `12px` vertical and `15-20px` horizontal, creating a substantial, inviting target.

### Feature List Item
**Role:** Informational Display

Text content with a leading icon. Icons often feature `Crimson Beam` (#ff3543) or `Emerald Glow` (#74ec5a) accents. Text uses `Ghost White` (#ffffff) for primary lines and `Pale Gray` (#c3c3c3) for descriptive text, spaced with a typical `17px` bottom margin.

### Headline Ivory
**Role:** Main Page Title

Large text using `-apple-system` font, typically `36px` or `32px` at `weight 500` or `600`, with `Ghost White` (#ffffff) color. Often followed by a subtitle `27px` below.

### Sub-Headline Accent
**Role:** Section Introductions

Medium-sized headings, often `24px` or `28px` `weight 500`, set in `Highlight Violet` (#9466e7) or `Emerald Glow` (#74ec5a), to draw attention to topic changes.

### Body Text Standard
**Role:** General Content

Regular text using `-apple-system` `16px` `weight 400` in `Ghost White` (#ffffff) or `Pale Gray` (#c3c3c3), with moderate line height around `1.5` for readability on dark backgrounds.

### Prominent Link
**Role:** Interactive Navigation/Callout

Text link using `Luminous Violet` (#ba94ff) at `16px` `weight 400`, often appearing as a standalone phrase or within paragraphs, identifiable by its vivid color.

### Testimonial Card
**Role:** Social Proof Display

Content block where testimonial text is `Ghost White` (#ffffff) `18px`, and author attribution is `Silver Tone` (#b3b3b3) or `Medium Gray` (#666666), with substantial vertical spacing (around `25px` or `29px` between items).

## Do's and Don'ts

### Do
- Use `Midnight Void` (#05050b) as the default background color for full-bleed sections and `Deep Shadow` (#1a1a1a) for hero sections, creating a sense of depth and atmosphere.
- Apply a `40px` `radius` to all interactive elements, like buttons and prominent links, for a consistent soft and approachable feel.
- For primary call-to-action buttons, use `Button Violet` (#301e4f) as the background and `Luminous Violet` (#ba94ff) for text, ensuring high contrast and brand coherence.
- Highlight key headings and feature descriptions with `Highlight Violet` (#9466e7) or `Emerald Glow` (#74ec5a) to punctuate the dark background.
- Maintain generous vertical spacing between sections, leveraging values like `64px` for `sectionGap` to ensure spaciousness and readability.
- Prioritize `-apple-system` font with `weight 400` or `500` and `Ghost White` (#ffffff) for all main body text to maximize readability on dark surfaces.
- Incorporate `Skyfire Gradient` (linear-gradient(to right bottom, rgb(108, 176, 255), rgb(247, 71, 255))) for decorative backgrounds or visual accents to reinforce the cosmic metaphor.

### Don't
- Avoid using harsh, fully saturated primary colors for large text blocks; reserve vivid hues like `Luminous Violet` (#ba94ff) only for interactive elements or small accents.
- Do not use sharp corners; the `40px` global `radius` for interactive elements and `18px` for lists is fundamental to the system's soft, playful character.
- Do not introduce additional font families; the entire system relies on `-apple-system` to maintain its native and unified aesthetic.
- Avoid generic gray for interactive elements; all buttons and active links must use `Luminous Violet` (#ba94ff) or `Button Violet` (#301e4f) tones.
- Do not neglect vertical spacing; the generous `sectionGap` of at least `64px` and `elementGap` of `10px` are crucial for maintaining the spacious layout.
- Refrain from using strong shadows or complex elevation; the site foregrounds depth through color shifts rather than traditional shadow mechanics. Avoid `box-shadow` values.
- Never use `background-color: #ffffff` on its own as a primary background; the design is dark-themed and relies on the progression of deep grays and purples.

## Imagery

The visual language is characterized by 3D rendered, friendly, and slightly whimsical illustrations. The hero section features stylized characters (rocket, elephant) against a dramatic space background, rendered with soft lighting and vibrant, glowing elements. Throughout the site, product screenshots are presented in device mockups (iPhone, iPad, Mac) that are often slightly angled and layered, demonstrating the application's interface. Icons are simple, filled, and often incorporate the accent colors like `Crimson Beam` or `Emerald Glow`, or `Luminous Violet`. The overall density is balanced, with imagery serving both a decorative and explanatory role for the app's features.

## Layout

Pages typically employ a full-bleed background, with content often centered within a conceptual `max-width`. The hero sections are dramatic and full-viewport, featuring large graphical elements centrally. Subsequent sections alternate between full-width content blocks and more structured layouts, including two-column text-and-image arrangements or multi-column feature lists. Vertical rhythm is established through consistent `sectionGap` of around `64px`, with spacious `elementGap` of `10px` internally. Card-like structures (e.g., testimonial blocks) appear with a distinct `18px` radius. The layout feels open and allows imagery significant breathing room.

## Agent Prompt Guide

### Quick Color Reference
- Text: `#ffffff` (Ghost White)
- Background: `#05050b` (Midnight Void)
- CTA Background: `#301e4f` (Button Violet)
- CTA Text: `#ba94ff` (Luminous Violet)
- Accent Link: `#ba94ff` (Luminous Violet)
- Headline Accent: `#9466e7` (Highlight Violet)

### Example Component Prompts
1. Create a `Primary Action Button` with text 'Download Ivory'. Use `Button Violet` (#301e4f) as background, `Luminous Violet` (#ba94ff) text, `-apple-system` `weight 500` `16px` with `1.5` lineHeight, and `40px` radius. Apply `12px` vertical and `20px` horizontal padding.
2. Design a `Feature List Item`: an icon filled with `Emerald Glow` (#74ec5a) followed by a primary text label in `Ghost White` (#ffffff) `18px` `-apple-system` `weight 500` `1.4` lineHeight, and a descriptive subtitle in `Pale Gray` (#c3c3c3) `16px` `-apple-system` `weight 400` `1.5` lineHeight. Ensure `elementGap` of `10px` between icon and text.
3. Implement a `Headline Ivory` section title using `Ghost White` (#ffffff) `36px` `-apple-system` `weight 600` with `1.1` lineHeight. Below it, add a paragraph of text in `Pale Gray` (#c3c3c3) `18px` `-apple-system` `weight 400` `1.4` lineHeight, with a `27px` `marginBottom`.
4. Construct a `Testimonial Card`: quote text in `Ghost White` (#ffffff) `18px` `-apple-system` `weight 400` `1.4` lineHeight, followed by an attribution in `Silver Tone` (#b3b3b3) `16px` `-apple-system` `weight 400` `1.5` lineHeight. Use `Carbon Gray` (#2c2c2c) for the background and `18px` radius. Leave `20px` padding on all sides.

## Similar Brands

- **Arc Browser** — Shares a similar dark-mode aesthetic with strong, contrasting accent colors and fluid, organic shapes in UI elements.
- **Linear** — Employs a polished dark UI with focused, elegant typography and subtle interactive elements, leaning into system-level aesthetics.
- **Superhuman** — Features a high-contrast dark theme with meticulous attention to detail in typography and icon design, aimed at developer tools.
- **Height** — Uses dark backgrounds with bright, intentional splashes of color for interactive states and data visualization, like status indicators.
- **Tweetbot** — As a companion app, it carries over the signature refined dark interface, clear hierarchy, and distinct interactive feedback.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-void: #05050b;
  --color-deep-shadow: #1a1a1a;
  --color-carbon-gray: #2c2c2c;
  --color-graphite: #484848;
  --color-medium-gray: #666666;
  --color-light-gray: #999999;
  --color-stone-grey: #a3a3a3;
  --color-silver-tone: #b3b3b3;
  --color-pale-gray: #c3c3c3;
  --color-bright-silver: #cccccc;
  --color-ghost-white: #ffffff;
  --color-cosmic-violet: #7047ba;
  --color-royal-plum: #4c278;
  --color-button-violet: #301e4f;
  --color-luminous-violet: #ba94ff;
  --color-highlight-violet: #9466e7;
  --color-pale-violet: #cdd4f8;
  --color-misty-violet: #deccff;
  --color-crimson-beam: #ff3543;
  --color-emerald-glow: #74ec5a;
  --color-skyfire-gradient: #84cbe2;
  --gradient-skyfire-gradient: linear-gradient(to right bottom, rgb(108, 176, 255), rgb(247, 71, 255));
  --color-lunar-gradient: #dfdceb;
  --gradient-lunar-gradient: linear-gradient(rgb(231, 230, 255), rgb(138, 137, 175));
  --color-milky-way-gradient: #e9d5ff;
  --gradient-milky-way-gradient: linear-gradient(rgb(255, 255, 255), rgb(217, 195, 255));

  /* Typography — Font Families */
  --font-apple-system: '-apple-system', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 16px;
  --leading-body: 1.5;
  --text-body-lg: 18px;
  --leading-body-lg: 1.4;
  --text-subheading: 20px;
  --leading-subheading: 1.4;
  --text-heading: 24px;
  --leading-heading: 1.2;
  --text-heading-lg: 28px;
  --leading-heading-lg: 1.2;
  --text-display-sm: 32px;
  --leading-display-sm: 1.1;
  --text-display: 36px;
  --leading-display: 1.1;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-12: 12px;
  --spacing-20: 20px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-60: 60px;
  --spacing-80: 80px;
  --spacing-144: 144px;
  --spacing-216: 216px;

  /* Layout */
  --section-gap: 64px;
  --card-padding: 20px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-2xl: 18px;
  --radius-3xl: 40px;

  /* Named Radii */
  --radius-icons: 40px;
  --radius-links: 40px;
  --radius-lists: 18px;
  --radius-buttons: 40px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-void: #05050b;
  --color-deep-shadow: #1a1a1a;
  --color-carbon-gray: #2c2c2c;
  --color-graphite: #484848;
  --color-medium-gray: #666666;
  --color-light-gray: #999999;
  --color-stone-grey: #a3a3a3;
  --color-silver-tone: #b3b3b3;
  --color-pale-gray: #c3c3c3;
  --color-bright-silver: #cccccc;
  --color-ghost-white: #ffffff;
  --color-cosmic-violet: #7047ba;
  --color-royal-plum: #4c278;
  --color-button-violet: #301e4f;
  --color-luminous-violet: #ba94ff;
  --color-highlight-violet: #9466e7;
  --color-pale-violet: #cdd4f8;
  --color-misty-violet: #deccff;
  --color-crimson-beam: #ff3543;
  --color-emerald-glow: #74ec5a;
  --color-skyfire-gradient: #84cbe2;
  --color-lunar-gradient: #dfdceb;
  --color-milky-way-gradient: #e9d5ff;

  /* Typography */
  --font-apple-system: '-apple-system', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 16px;
  --leading-body: 1.5;
  --text-body-lg: 18px;
  --leading-body-lg: 1.4;
  --text-subheading: 20px;
  --leading-subheading: 1.4;
  --text-heading: 24px;
  --leading-heading: 1.2;
  --text-heading-lg: 28px;
  --leading-heading-lg: 1.2;
  --text-display-sm: 32px;
  --leading-display-sm: 1.1;
  --text-display: 36px;
  --leading-display: 1.1;

  /* Spacing */
  --spacing-12: 12px;
  --spacing-20: 20px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-60: 60px;
  --spacing-80: 80px;
  --spacing-144: 144px;
  --spacing-216: 216px;

  /* Border Radius */
  --radius-2xl: 18px;
  --radius-3xl: 40px;
}
```

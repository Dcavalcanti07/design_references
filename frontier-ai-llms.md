# Frontier AI LLMs — Style Reference
> Digital Desert Dawn — a stark, warm landscape where technology meets the wild.

**Theme:** light

Mistral AI presents as a digital desert landscape at dawn. The warm, earthy gradient backgrounds evoke vast, untamed frontiers, grounding the advanced AI concepts in natural, expansive imagery. Heavy, dark typography on these warm backdrops creates stark contrast, emphasizing seriousness and weight. An almost absent border radius (0px) reinforces a pragmatic, unyielding aesthetic, while the single vivid orange accent color highlights interaction points, mimicking a critical glow against the muted tones.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Desert Canvas | `#fffaeb` | `--color-desert-canvas` | Primary page background, text container background — provides a warm, sandy base. |
| Midnight Ink | `#1f1f1f` | `--color-midnight-ink` | Primary text color for headings and body content, navigation elements, high-contrast buttons — a deep, rich black. |
| Snowdrift | `#ffffff` | `--color-snowdrift` | Button text on dark backgrounds, selected navigation states, specific content blocks. |
| Void Deep | `#000000` | `--color-void-deep` | Hover background for buttons, borders for high-contrast elements. |
| Graphite | `#3c3c3c` | `--color-graphite` | Secondary text, muted links, subtle button borders. |
| Sandstone Slab | `#fff0c2` | `--color-sandstone-slab` | Secondary background color for UI elements, subtle dividers, accent areas. |
| Pale Ochre | `#ecdaa2` | `--color-pale-ochre` | Border color for subtle containers or interactive elements. |
| Horizon Gradient | `linear-gradient(to left bottom in oklab, rgb(159, 82, 26) 0%, rgb(211, 129, 47) 50%, rgb(179, 93, 32) 100%)` | `--color-horizon-gradient` | Hero background, creating an atmospheric, expansive focal point. |
| Frontier Accent | `#fa520f` | `--color-frontier-accent` | Accent color for icons, interactive indicators, subtle highlights, and brand presence — a vivid, almost neon orange. |
| Golden Streak | `#ffd900` | `--color-golden-streak` | Decorative background color, likely for abstract graphics or very subtle brand elements. |
| Sunbeam | `#ffae00` | `--color-sunbeam` | Decorative background color, likely for abstract graphics or very subtle brand elements. |
| Faded Red | `#e00400` | `--color-faded-red` | Decorative background color, likely for abstract graphics or very subtle brand elements. |

## Tokens — Typography

### Arial — Primary typeface for all textual content. Its neutral, sans-serif character supports the technical focus while the slightly negative letter spacing for larger sizes creates a refined, impactful presence despite the classic font choice. Used for headlines, body text, buttons, and navigation. · `--font-arial`
- **Substitute:** Helvetica Neue, sans-serif
- **Weights:** 400
- **Sizes:** 14px, 16px, 24px, 32px, 38px, 48px, 56px, 82px
- **Line height:** 0.95, 1.00, 1.15, 1.33, 1.43, 1.50
- **Letter spacing:** -0.0250em
- **Role:** Primary typeface for all textual content. Its neutral, sans-serif character supports the technical focus while the slightly negative letter spacing for larger sizes creates a refined, impactful presence despite the classic font choice. Used for headlines, body text, buttons, and navigation.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body-sm | 14px | 1.43 | -0.42px | `--text-body-sm` |
| body | 16px | 1.5 | -0.48px | `--text-body` |
| subheading | 24px | 1.33 | -0.72px | `--text-subheading` |
| heading | 32px | 1.15 | -0.96px | `--text-heading` |
| heading-lg | 38px | 1.15 | -1.14px | `--text-heading-lg` |
| display | 48px | 1 | -1.44px | `--text-display` |
| display-lg | 56px | 0.95 | -1.68px | `--text-display-lg` |
| display-xl | 82px | 0.95 | -2.46px | `--text-display-xl` |

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
| 64 | 64px | `--spacing-64` |
| 72 | 72px | `--spacing-72` |
| 80 | 80px | `--spacing-80` |
| 100 | 100px | `--spacing-100` |

### Border Radius

| Element | Value |
|---------|-------|
| all | 0px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| xl | `rgba(127, 99, 21, 0.12) -8px 16px 39px 0px, rgba(127, 99,...` | `--shadow-xl` |

### Layout

- **Section gap:** 89px
- **Card padding:** 12px
- **Element gap:** 12px

## Components

### Primary Dark Button
**Role:** Call-to-action button for critical user journeys.

Solid 'Midnight Ink' background (#1f1f1f) with 'Snowdrift' (#ffffff) text. No border radius (0px) creates a sharp, direct interaction. Padding is 12px on all sides. Text is Arial 14px, weight 400, with -0.0250em letter spacing.

### Ghost Accent Link Button
**Role:** Secondary action or navigation highlight, often appearing in hero or footer zones.

Transparent background with 'Snowdrift' (#ffffff) text. Features a 1px bottom border in 'Desert Canvas' (#fffaeb). No border radius (0px). Padding is 16px vertical, 0px horizontal. Text is Arial 14px, weight 400, with -0.0250em letter spacing.

### Ghost Dark Link Button
**Role:** Secondary action or navigation, typically within light sections.

Transparent background with 'Midnight Ink' (#1f1f1f) text. Features a 1px bottom border in 'Midnight Ink' (#1f1f1f). No border radius (0px). Padding is 12px vertical, 0px horizontal. Text is Arial 14px, weight 400, with -0.0250em letter spacing.

### Callout Tag Button
**Role:** Informational tags or minor calls to action.

Translucent 'Desert Canvas' background (rgba(255, 250, 235, 0.1)) with 'Snowdrift' (#ffffff) text. No border radius (0px). Padding is 8px vertical, 16px horizontal. Text is Arial 14px, weight 400, with -0.0250em letter spacing.

### Navigation Link
**Role:** Primary navigation links in the header.

Uses 'Midnight Ink' (#1f1f1f) for text, 'Desert Canvas' (#fffaeb) as background. Font is Arial 16px, weight 400. No explicit padding or border is defined beyond inherited link styles, implying simple text links.

### Hero Headline
**Role:** Dominant textual element on the primary landing page.

Text color 'Snowdrift' (#ffffff), Arial 82px, weight 400, line height 0.95, letter spacing -0.0250em. Set against the 'Horizon Gradient' background, it commands attention.

### Body Paragraph
**Role:** Standard informative text block.

Text color 'Midnight Ink' (#1f1f1f), Arial 16px, weight 400, line height 1.50, letter spacing -0.0250em. Renders clearly on the 'Desert Canvas' background.

### Feature Card (light)
**Role:** Used for informational content blocks in light sections.

Background 'Desert Canvas' (#fffaeb) with text in 'Midnight Ink' (#1f1f1f). No apparent border or border-radius, relying on whitespace for definition. Inner text elements use 'Frontier Accent' (#fa520f) for small icons or leading indicators.

### Footer Link
**Role:** Navigation and informational links in the footer.

Uses 'Midnight Ink' (#1f1f1f) or 'Graphite' (#3c3c3c) for text on a 'Desert Canvas' (#fffaeb) background. Font is Arial 14px, weight 400. Subtle, without explicit padding, relying on semantic HTML and surrounding whitespace.

## Do's and Don'ts

### Do
- Use 'Horizon Gradient' for hero sections or significant atmospheric backgrounds.
- Maintain 0px border radius across all buttons and interactive elements for a sharp aesthetic.
- Prioritize 'Midnight Ink' for all primary text content against light backgrounds for maximum legibility.
- Apply 'Frontier Accent' (#fa520f) sparingly, only for interactive elements or key icons.
- Ensure large headlines (>= 48px) utilize Arial 400 weight with -0.0250em letter spacing.
- Use 'Desert Canvas' (#fffaeb) as the primary page background.
- Structure content with ample 12px 'elementGap' between adjacent components like text and buttons.

### Don't
- Avoid applying any border radius to UI elements; stick to 0px.
- Do not introduce new color gradients; adhere to 'Horizon Gradient' for atmospheric elements and a flat canvas for UI.
- Refrain from using any colors not specified in the palette, especially highly saturated hues, to maintain the muted, earth-toned brand identity.
- Do not use generic gray scales for text. Use the specific 'Midnight Ink' (#1f1f1f) and 'Graphite' (#3c3c3c) tokens.
- Avoid heavy drop shadows on elevated elements. If elevation is needed, rely on subtle background shifts.
- Do not vary line height from the specified values per type size to avoid disrupting vertical rhythm.
- Introduce white space around elements using the defined spacing tokens (e.g., 12px for elementGap) rather than relying on margin-auto or arbitrary values.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Desert Canvas | `#fffaeb` | Base page background, light sections, content containers. |
| 1 | Sandstone Slab | `#fff0c2` | Secondary background for UI elements, alternating section backgrounds, subtle dividers. |
| 2 | Void Deep | `#000000` | Elevated buttons, dark foreground elements against lighter backgrounds. |
| 3 | Horizon Gradient | `#b35d20` | Hero sections and highly prominent background treatments. |

## Elevation

- **Card/Container:** `box-shadow: rgba(127, 99, 21, 0.12) -8px 16px 39px 0px, rgba(127, 99, 21, 0.1) -33px 64px 72px 0px, rgba(127, 99, 21, 0.06) -73px 144px 97px 0px, rgba(127, 99, 21, 0.02) -130px 256px 115px 0px;`

## Imagery

The site heavily uses atmospheric, wide-landscape photography with an earthy, orange-yellow gradient overlay, reminiscent of desert mountains at dawn. These are full-bleed in hero sections, creating a sense of vastness and uncultivated potential. Elsewhere, the imagery is minimal, primarily focusing on abstract, pixelated block compositions in muted yellow tones (#fff0c2, #fffaeb) which serve as decorative, branded background patterns. Icons are monochrome, 'Frontier Accent' colored, outlined or filled, with a consistent stroke weight to match the sharp aesthetic. Imagery primarily serves to establish mood and brand identity, with an abstract rather than literal representation of AI.

## Layout

The page follows a classic max-width centered layout, though the hero section spans full-bleed to establish an expansive atmosphere. The hero features a large, centered headline over the 'Horizon Gradient' background. Subsequent sections alternate between a primary 'Desert Canvas' background and a 'Sandstone Slab' for visual pacing. Content is arranged in alternating two-column layouts (text left, image/graphic right) and centered stacks. Feature sections often use simple bulleted lists or sequential blocks of text with small 'Frontier Accent' icons. Information density is moderate, with generous vertical spacing (sectionGap 89px) providing breathing room between content blocks. The header is a sticky top bar containing navigation and call-to-action buttons, while the footer is a multi-column layout.

## Agent Prompt Guide

Quick Color Reference:
- Text: #1f1f1f (Midnight Ink)
- Background: #fffaeb (Desert Canvas)
- CTA: #1f1f1f (Midnight Ink) for solid, #fa520f (Frontier Accent) for link indicators
- Border: #1f1f1f (Midnight Ink) or #ecdaa2 (Pale Ochre)
- Accent: #fa520f (Frontier Accent)

Example Component Prompts:
1. Create a hero section: Full-width, 'Horizon Gradient' background. Headline 'Frontier AI. In your hands.' in 'Snowdrift' (#ffffff) text, Arial 82px, weight 400, line height 0.95, letter spacing -2.46px. Subtext 'We help organizations build tailored AI systems to solve the world's hardest problems.' in 'Snowdrift' (#ffffff) text, Arial 16px, weight 400, line height 1.5, letter spacing -0.48px. Beneath, two 'Ghost Accent Link Button' variants: 'Get in touch' and 'Start building'.
2. Design a feature block: 'Desert Canvas' (#fffaeb) background. On the left, 'Your AI future belongs in your hands.' as heading in 'Midnight Ink' (#1f1f1f), Arial 56px, weight 400, line height 0.95, letter spacing -1.68px. On the right, a list of three points. Each point starts with a small 'Frontier Accent' (#fa520f) icon, then body text 'Make your AI your own. Train, distill, fine-tune, and build with state-of-the-art open source models.' in 'Midnight Ink' (#1f1f1f), Arial 16px, weight 400, line height 1.5, letter spacing -0.48px. Use 12px elementGap between icon and text, and between list items.
3. Build a primary navigation bar: Fixed at top, 'Desert Canvas' (#fffaeb) background. Brand logo (placeholder 'M' in 'Midnight Ink') on the left. Navigation links 'Products', 'Solutions', 'Research', 'Blog', 'Customers', 'Company' in 'Midnight Ink' (#1f1f1f), Arial 16px, weight 400, letter spacing -0.48px, with 24px horizontal elementGap. On the right, a 'Ghost Accent Link Button' labeled 'Contact Sales' and a 'Primary Dark Button' labeled 'Try Studio'.
4. Create a prominent dark CTA card: 'Midnight Ink' (#1f1f1f) background. Headline 'Autonomous work.' in 'Snowdrift' (#ffffff), Arial 32px, weight 400, line height 1.15, letter spacing -0.96px. Body text 'Chat, search, analyze, create—do more in one connected hub.' in 'Snowdrift' (#ffffff), Arial 16px, weight 400, line height 1.5, letter spacing -0.48px. Follow with a 'Primary Dark Button' with 'Snowdrift' text labeled 'Discover Le Chat'.

## Similar Brands

- **Anthropic** — Similar focus on advanced AI, often uses clean, minimalistic layouts with strong typography and a limited, purposeful color palette.
- **Databricks** — Technical B2B SaaS with a strong emphasis on data and AI, similar in presentation combining professional layouts with subtle brand accents.
- **Palantir** — Enterprise data/AI, with a visual style that balances sophistication with a raw, powerful feel, often using a limited color scheme and strong imagery.
- **OpenAI** — Direct competitor in AI space, often uses clean, modern design with a focused color palette and strong, impactful headlines.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-desert-canvas: #fffaeb;
  --color-midnight-ink: #1f1f1f;
  --color-snowdrift: #ffffff;
  --color-void-deep: #000000;
  --color-graphite: #3c3c3c;
  --color-sandstone-slab: #fff0c2;
  --color-pale-ochre: #ecdaa2;
  --color-horizon-gradient: #b35d20;
  --gradient-horizon-gradient: linear-gradient(to left bottom in oklab, rgb(159, 82, 26) 0%, rgb(211, 129, 47) 50%, rgb(179, 93, 32) 100%);
  --color-frontier-accent: #fa520f;
  --color-golden-streak: #ffd900;
  --color-sunbeam: #ffae00;
  --color-faded-red: #e00400;

  /* Typography — Font Families */
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-sm: 14px;
  --leading-body-sm: 1.43;
  --tracking-body-sm: -0.42px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.48px;
  --text-subheading: 24px;
  --leading-subheading: 1.33;
  --tracking-subheading: -0.72px;
  --text-heading: 32px;
  --leading-heading: 1.15;
  --tracking-heading: -0.96px;
  --text-heading-lg: 38px;
  --leading-heading-lg: 1.15;
  --tracking-heading-lg: -1.14px;
  --text-display: 48px;
  --leading-display: 1;
  --tracking-display: -1.44px;
  --text-display-lg: 56px;
  --leading-display-lg: 0.95;
  --tracking-display-lg: -1.68px;
  --text-display-xl: 82px;
  --leading-display-xl: 0.95;
  --tracking-display-xl: -2.46px;

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
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-100: 100px;

  /* Layout */
  --section-gap: 89px;
  --card-padding: 12px;
  --element-gap: 12px;

  /* Named Radii */
  --radius-all: 0px;

  /* Shadows */
  --shadow-xl: rgba(127, 99, 21, 0.12) -8px 16px 39px 0px, rgba(127, 99, 21, 0.1) -33px 64px 72px 0px, rgba(127, 99, 21, 0.06) -73px 144px 97px 0px, rgba(127, 99, 21, 0.02) -130px 256px 115px 0px;

  /* Surfaces */
  --surface-desert-canvas: #fffaeb;
  --surface-sandstone-slab: #fff0c2;
  --surface-void-deep: #000000;
  --surface-horizon-gradient: #b35d20;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-desert-canvas: #fffaeb;
  --color-midnight-ink: #1f1f1f;
  --color-snowdrift: #ffffff;
  --color-void-deep: #000000;
  --color-graphite: #3c3c3c;
  --color-sandstone-slab: #fff0c2;
  --color-pale-ochre: #ecdaa2;
  --color-horizon-gradient: #b35d20;
  --color-frontier-accent: #fa520f;
  --color-golden-streak: #ffd900;
  --color-sunbeam: #ffae00;
  --color-faded-red: #e00400;

  /* Typography */
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-sm: 14px;
  --leading-body-sm: 1.43;
  --tracking-body-sm: -0.42px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.48px;
  --text-subheading: 24px;
  --leading-subheading: 1.33;
  --tracking-subheading: -0.72px;
  --text-heading: 32px;
  --leading-heading: 1.15;
  --tracking-heading: -0.96px;
  --text-heading-lg: 38px;
  --leading-heading-lg: 1.15;
  --tracking-heading-lg: -1.14px;
  --text-display: 48px;
  --leading-display: 1;
  --tracking-display: -1.44px;
  --text-display-lg: 56px;
  --leading-display-lg: 0.95;
  --tracking-display-lg: -1.68px;
  --text-display-xl: 82px;
  --leading-display-xl: 0.95;
  --tracking-display-xl: -2.46px;

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
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-100: 100px;

  /* Shadows */
  --shadow-xl: rgba(127, 99, 21, 0.12) -8px 16px 39px 0px, rgba(127, 99, 21, 0.1) -33px 64px 72px 0px, rgba(127, 99, 21, 0.06) -73px 144px 97px 0px, rgba(127, 99, 21, 0.02) -130px 256px 115px 0px;
}
```

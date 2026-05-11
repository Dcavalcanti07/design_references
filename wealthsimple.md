# Wealthsimple — Style Reference
> Warm Minimalism on Linen. Imagine precise, intentional content laid out on a finely textured, off-white linen, framed by subtle, earthy tones.

**Theme:** light

Wealthsimple projects an image of approachable financial sophistication, blending a muted, almost vintage-feeling color palette with modern typography. The design feels grounded and trustworthy, achieved through a dominant presence of off-white and dark gray surfaces that create a soft contrast. Touches of natural, desaturated color appear subtly, preventing the aesthetic from feeling stark while maintaining a sense of serious purpose. Custom fonts — one with a humanist, inviting feel, the other a crisp sans-serif — underpin content hierarchy without resorting to harsh visual cues.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Greyscale Black | `#32302f` | `--color-greyscale-black` | Primary text, button backgrounds, interactive elements, heavy borders — establishes a deep, soft visual anchor instead of pure black. |
| Linen White | `#fcfcfc` | `--color-linen-white` | Page backgrounds, card surfaces, secondary button backgrounds, input fields — creates a clean, slightly warm canvas that isn't clinical. |
| Slate Border | `#e4e2e1` | `--color-slate-border` | Subtle UI borders, separators, secondary button outlines — provides gentle division without harsh lines, maintaining the overall soft contrast. |
| Text Muted | `#686664` | `--color-text-muted` | Secondary text, descriptive elements, placeholders — a darker gray for hierarchy that still feels integrated with the palette. |
| Ash Canvas | `#f1f0f0` | `--color-ash-canvas` | Minor background accents, subtle stripes, hover states — a slightly darker off-white for nuanced layering. |
| Input Gray | `#eeece7` | `--color-input-gray` | Input background, subtle card surface distinction. |
| Ocean Tint | `#d3e5f3` | `--color-ocean-tint` | Minor decorative elements, subtle background fill in certain contexts— a desaturated, cool chromatic accent that occasionally appears, offering a hint of calm. |
| Success Green | `#486635` | `--color-success-green` | Semantic success indicators — a deep, muted green that integrates without being overly vibrant. |
| Error Red | `#a43d12` | `--color-error-red` | Semantic error indicators — a rich, earthy red that provides clear alerts without being alarming. |
| Focus Outline | `#afaaa7` | `--color-focus-outline` | Interactive focus states, scrollbar thumbs — a soft, warm gray that indicates interaction without drawing excessive attention. |

## Tokens — Typography

### the-future — Primary body text, navigation items, descriptive text, button labels. Its subtle letter-spacing provides a distinct, modern feel to standard text. · `--font-the-future`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400, 500
- **Sizes:** 14px, 16px, 18px, 20px, 56px, 58px
- **Line height:** 1.00, 1.16, 1.40
- **Letter spacing:** 0.0050em
- **Role:** Primary body text, navigation items, descriptive text, button labels. Its subtle letter-spacing provides a distinct, modern feel to standard text.

### wealthsimple-sans — Used sparingly for specific body elements or small text where a more open, airy feel is desired, especially on buttons. · `--font-wealthsimple-sans`
- **Substitute:** Inter, system-ui, sans-serif
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.20
- **Letter spacing:** 0.0250em
- **Role:** Used sparingly for specific body elements or small text where a more open, airy feel is desired, especially on buttons.

### tiempos — Headlines and prominent text, offering a classic yet contemporary serif feel. The judicious negative letter-spacing for display sizes tightens headlines, giving them a considered, editorial presence. · `--font-tiempos`
- **Substitute:** serif
- **Weights:** 400, 500
- **Sizes:** 14px, 16px, 18px, 36px, 56px, 64px, 72px, 84px
- **Line height:** 1.08, 1.16, 1.24
- **Letter spacing:** -0.0100em
- **Role:** Headlines and prominent text, offering a classic yet contemporary serif feel. The judicious negative letter-spacing for display sizes tightens headlines, giving them a considered, editorial presence.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 14px | 1.4 | 0.005px | `--text-caption` |
| body | 16px | 1.4 | 0.005px | `--text-body` |
| subheading | 18px | 1.4 | 0.005px | `--text-subheading` |
| heading | 36px | 1.08 | -0.01px | `--text-heading` |
| heading-lg | 56px | 1.16 | -0.01px | `--text-heading-lg` |
| display | 72px | 1.08 | -0.01px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 6 | 6px | `--spacing-6` |
| 8 | 8px | `--spacing-8` |
| 12 | 12px | `--spacing-12` |
| 15 | 15px | `--spacing-15` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 73 | 73px | `--spacing-73` |
| 80 | 80px | `--spacing-80` |
| 128 | 128px | `--spacing-128` |
| 160 | 160px | `--spacing-160` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 100px |
| minor | 2px |
| inputs | 100px |
| buttons | 1600px |

### Layout

- **Section gap:** 40-48px
- **Element gap:** 8px

## Components

### Secondary Outlined Button
**Role:** Secondary action, navigation

Background: Linen White (#fcfcfc), Text: Greyscale Black (#32302f), Border: Greyscale Black (#32302f) thick 1px, Radius: 1600px, Padding: 12px 24px. Offers a softer call to action that integrates with light backgrounds.

### Small Utility Button
**Role:** Icon-only actions, small interactive elements

Background: Linen White (#fcfcfc), Text: Greyscale Black (#32302f), Border: Slate Border (#e4e2e1) thick 1px, Radius: 50% (circular), Padding: 0px. Used for compact, visually subtle interactions like a scroll-to-top button.

### Invisible Button
**Role:** Text links appearing as buttons

Background: transparent, Text: Greyscale Black (#32302f), Border: Greyscale Black (#000000) thin 1px, Radius: 0px, Padding: 0px. Used for subtle, text-based interactive elements where the button styling is minimal.

### Default Card
**Role:** Content grouping (no specific styling)

Background: transparent, border-radius: 0px, no shadow, no padding. Serves as a logical grouping tool without visual adornment.

### Tinted Pill Card (Linen)
**Role:** Subtle badging, small contextual labels

Background: Input Gray (#eeece7), border-radius: 100px, Padding: 8px 12px. Provides a softly rounded, contained background for short pieces of information.

### Tinted Pill Card (Dark Slate)
**Role:** Dark-mode badging, small contextual labels

Background: rgba(42, 44, 50, 1), border-radius: 100px, Padding: 8px 12px. A dark variant of the pill card for specific contexts.

### Text Input Field
**Role:** Form input

Background: Linen White (#fcfcfc), Text: Greyscale Black (#32302f), Border: Slate Border (#e4e2e1) thick 1px, Radius: 100px, Padding: 20px 52px 1px 24px. Features a wide, pill-shaped design, prioritizing visual clarity and distinctness in forms.

## Do's and Don'ts

### Do
- Use Linen White (#fcfcfc) as the primary page background to establish warmth.
- Apply Greyscale Black (#32302f) for all primary body text and headlines to ensure high contrast and readability.
- Implement the-future for body text and navigation, maintaining its defined sizes and the subtle 0.0050em letter-spacing.
- Use tiempos for headlines, adjusting sizes and utilizing its -0.0100em letter-spacing to create a distinctive, editorial typesetting.
- Ensure all interactive buttons use a 1600px border-radius, creating a consistent 'pill' shape, regardless of fill or outline.
- Employ Slate Border (#e4e2e1) for all non-critical borders, such as input fields and secondary button outlines, for a soft, integrated look.
- Use 20px 32px padding for primary buttons and 12px 24px for secondary buttons to maintain a consistent interactive element scale.

### Don't
- Avoid harsh, high-saturation colors; all chromatic elements should be desaturated or muted.
- Do not use pure black (#000000) for text or primary backgrounds; always opt for Greyscale Black (#32302f) for a softer appearance.
- Refrain from sharp corners; button, card, and input radii should be either 100px or greater, or 0px for purely structural elements.
- Do not introduce strong shadows or elevation effects; the design relies on color and careful spacing for depth.
- Avoid using highly decorative or ornate iconography; prefer simple, clear, line-based icons that match the minimal aesthetic.
- Do not vary line heights from the specified typography profiles; precise line heights establish a clean vertical rhythm.
- Do not use letter spacing other than the specified values for the-future (0.0050em) and tiempos (-0.0100em) to preserve typographic identity.

## Imagery

Imagery is conceptual and abstract, focusing on product illustrations and staged still-life photography of objects that evoke finance (papers, coins, devices). Treatments are primarily contained within rounded frames or as background elements that blend into the color palette. There's an absence of lifestyle photography, keeping the focus on the product and conceptual integrity. Illustrations are dimensional and often use soft, brand-adjacent colors, avoiding harsh outlines or overly cartoonish styles. Icons are simple, monochrome, and line-based, maintaining the overall clean aesthetic. Visual space is balanced, allowing for prominent heroes but also significant text areas.

## Layout

The site employs a max-width contained layout, typically centered, but features occasional full-bleed hero sections. Hero patterns are often split-layout (text on left, visual on right) or centered text over an abstract background image. Section rhythm is varied but generally uses consistent vertical spacing of 40-48px. Content is often arranged in 2-column layouts with alternating text-left/image-right or stacked blocks. The primary content delivery is text-dominant, with imagery serving as an accent rather than a primary information vehicle. A sticky top navigation bar provides consistent access to key sections.

## Agent Prompt Guide

### Quick Color Reference
- Text: #32302f
- Background: #fcfcfc
- Primary CTA: #32302f
- Border: #e4e2e1
- Accent: #afaaa7

### 3-5 Example Component Prompts
1.  **Create Hero Section:** Background Greyscale Black (#32302f). Left half: Headline 'Taxes, done your way' at 72px 'tiempos' weight 400, #fcfcfc, letter-spacing -0.01em. Subtext 'File on your own...' at 18px 'the-future' weight 400, #fcfcfc, line-height 1.4. Below, a 'Primary Filled Button' with text 'Start my return' and a 'Secondary Outlined Button' with text 'Learn more'. Right half: abstract illustration of stacked papers.
2.  **Generate a Feature Card:** Background Linen White (#fcfcfc). Title 'Better than your bank' at 56px 'tiempos' weight 400, #32302f, letter-spacing -0.01em. Body text 'Get the most out of your money...' at 18px 'the-future' weight 400, #686664. Below, a 'Primary Filled Button' with text 'Get started'.
3.  **Design a Navigation Item:** Text 'What we offer' at 16px 'the-future' weight 400, #32302f, letter-spacing 0.005em. Include a small dropdown icon. Ensure 2px border-radius on hover background.
4.  **Create a 'Tinted Pill Card (Linen)':** Background Input Gray (#eeece7). Text 'New' at 14px 'the-future' weight 400, #32302f, letter-spacing 0.005em. Padding 8px 12px, border-radius 100px.
5.  **Build an Input Field:** Background Linen White (#fcfcfc). Border Slate Border (#e4e2e1), 1px thick, 100px border-radius. Placeholder text 'Enter your email' in Text Muted (#686664) at 16px 'the-future' weight 400. Padding 20px 52px 1px 24px.

## Similar Brands

- **Linear** — Shares the use of custom, distinctive typography with careful letter-spacing, and a preference for muted, sophisticated color palettes over vibrant accents.
- **Stripe** — Employs a clean, spacious layout with a dominant light background, and uses subtle color accents alongside strong, readable typography to convey professionalism.
- **Figma** — Features a similar approach to slightly rounded UI elements and a balanced use of white space to create a user-friendly and aesthetically pleasing interface, although with a more vibrant accent palette.
- **Notion** — Utilizes a minimalist design with a focus on typography and subtle element separation, often relying on shades of gray and off-white to create visual hierarchy rather than strong colors.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-greyscale-black: #32302f;
  --color-linen-white: #fcfcfc;
  --color-slate-border: #e4e2e1;
  --color-text-muted: #686664;
  --color-ash-canvas: #f1f0f0;
  --color-input-gray: #eeece7;
  --color-ocean-tint: #d3e5f3;
  --color-success-green: #486635;
  --color-error-red: #a43d12;
  --color-focus-outline: #afaaa7;

  /* Typography — Font Families */
  --font-the-future: 'the-future', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-wealthsimple-sans: 'wealthsimple-sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-tiempos: 'tiempos', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.4;
  --tracking-caption: 0.005px;
  --text-body: 16px;
  --leading-body: 1.4;
  --tracking-body: 0.005px;
  --text-subheading: 18px;
  --leading-subheading: 1.4;
  --tracking-subheading: 0.005px;
  --text-heading: 36px;
  --leading-heading: 1.08;
  --tracking-heading: -0.01px;
  --text-heading-lg: 56px;
  --leading-heading-lg: 1.16;
  --tracking-heading-lg: -0.01px;
  --text-display: 72px;
  --leading-display: 1.08;
  --tracking-display: -0.01px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-15: 15px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-73: 73px;
  --spacing-80: 80px;
  --spacing-128: 128px;
  --spacing-160: 160px;

  /* Layout */
  --section-gap: 40-48px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-xl: 12px;
  --radius-full: 100px;
  --radius-full-2: 1600px;

  /* Named Radii */
  --radius-cards: 100px;
  --radius-minor: 2px;
  --radius-inputs: 100px;
  --radius-buttons: 1600px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-greyscale-black: #32302f;
  --color-linen-white: #fcfcfc;
  --color-slate-border: #e4e2e1;
  --color-text-muted: #686664;
  --color-ash-canvas: #f1f0f0;
  --color-input-gray: #eeece7;
  --color-ocean-tint: #d3e5f3;
  --color-success-green: #486635;
  --color-error-red: #a43d12;
  --color-focus-outline: #afaaa7;

  /* Typography */
  --font-the-future: 'the-future', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-wealthsimple-sans: 'wealthsimple-sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-tiempos: 'tiempos', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.4;
  --tracking-caption: 0.005px;
  --text-body: 16px;
  --leading-body: 1.4;
  --tracking-body: 0.005px;
  --text-subheading: 18px;
  --leading-subheading: 1.4;
  --tracking-subheading: 0.005px;
  --text-heading: 36px;
  --leading-heading: 1.08;
  --tracking-heading: -0.01px;
  --text-heading-lg: 56px;
  --leading-heading-lg: 1.16;
  --tracking-heading-lg: -0.01px;
  --text-display: 72px;
  --leading-display: 1.08;
  --tracking-display: -0.01px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-15: 15px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-73: 73px;
  --spacing-80: 80px;
  --spacing-128: 128px;
  --spacing-160: 160px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-xl: 12px;
  --radius-full: 100px;
  --radius-full-2: 1600px;
}
```

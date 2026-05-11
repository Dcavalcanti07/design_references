# Trigger.dev — Style Reference
> Midnight Terminal, illuminated by command prompts and spectral highlights.

**Theme:** dark

Trigger.dev creates a 'technical luxury' dark mode experience, balancing utility with subtle visual richness. The deep charcoal backgrounds paired with crisp, cool-toned neutrals establish a serious, professional tone, while vibrant accents act as precise markers on a complex system. Custom fonts with precise letter-spacing and varied weights contribute to its sharp, information-dense feel. The interplay of minimalist buttons with sharp corners against a few pill-shaped elements hints at a system that values both traditional interface clarity and modern digital fluidity.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Obsidian Black | `#121317` | `--color-obsidian-black` | Primary background for the application shell and content sections. |
| Charcoal Surface | `#1c1e21` | `--color-charcoal-surface` | Card backgrounds, elevated content panels, and subtle section dividers. |
| Ash Gray | `#3b3e45` | `--color-ash-gray` | Subtle borders and inactive element states, providing a discrete visual separation. |
| Slate Text | `#d7d9dd` | `--color-slate-text` | Primary Readable text, headings, and icon fills. |
| Whisper White | `#e5e7eb` | `--color-whisper-white` | High-contrast text for active states and critical information, button borders. |
| Steel Accent | `#b5b8c0` | `--color-steel-accent` | Secondary text, muted descriptions, and placeholder text. |
| Spring Green | `#a8ff53` | `--color-spring-green` | Primary call-to-action buttons, 'get started' elements, and positive status indicators — a vibrant beacon against dark surfaces. |
| Cloud Violet | `#9c9af2` | `--color-cloud-violet` | Highlighting interactive elements, sub-headings, and decorative accents, suggesting an underlying digital core. |
| Deep Plum | `#7655fd` | `--color-deep-plum` | Secondary accent for interactive elements and specific highlighted text, providing depth to the purple spectrum. |
| Fuchsia Highlight | `#fa3abf` | `--color-fuchsia-highlight` | Decorative elements, iconography, and occasional text highlights. |
| Cosmic Blue | `#479dec` | `--color-cosmic-blue` | Specific iconography and product feature highlights. |
| Flare Orange | `#eccf06` | `--color-flare-orange` | Accent for status indicators or specific feature callouts. |
| Action Red | `#f43f5` | `--color-action-red` | Used for error states or urgent notifications. |
| Success Green | `#afec73` | `--color-success-green` | Success messages and positive confirmations; distinct from brand green. |
| Highlight Gradient | `linear-gradient(to right, rgb(59, 62, 69), rgb(59, 62, 69), rgb(135, 140, 153))` | `--color-highlight-gradient` | Subtle background shading on review cards, creating a sense of dimension without harsh shadows. |

## Tokens — Typography

### Geist-Regular — Body copy, navigation items, general UI labels. Its neutral, legible character forms the workhorse text of the system. · `--font-geist-regular`
- **Substitute:** Inter
- **Weights:** 300, 400, 500
- **Sizes:** 14px, 16px, 18px, 20px
- **Line height:** 1.40, 1.43, 1.50, 1.56, 1.71
- **Letter spacing:** normal
- **Role:** Body copy, navigation items, general UI labels. Its neutral, legible character forms the workhorse text of the system.

### GeistMono-Regular — Specialized for code blocks and technical annotations, providing a distinct, precise feel for developer-centric content. · `--font-geistmono-regular`
- **Substitute:** JetBrains Mono
- **Weights:** 300, 400
- **Sizes:** 14px
- **Line height:** 1.43
- **Letter spacing:** normal
- **Role:** Specialized for code blocks and technical annotations, providing a distinct, precise feel for developer-centric content.

### Satoshi-Variable — Primary typeface for all headlines and display text. Its distinct, confident forms and subtle letter-spacing give visual weight to key messages. · `--font-satoshi-variable`
- **Substitute:** Outfit
- **Weights:** 500, 600
- **Sizes:** 16px, 18px, 20px, 24px, 30px, 36px, 48px, 60px
- **Line height:** 1.00, 1.11, 1.20, 1.33, 1.38, 1.40, 1.50, 1.56
- **Letter spacing:** 0.5, 0.25
- **Role:** Primary typeface for all headlines and display text. Its distinct, confident forms and subtle letter-spacing give visual weight to key messages.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body-sm | 14px | 1.5 | — | `--text-body-sm` |
| body | 16px | 1.5 | — | `--text-body` |
| subheading | 18px | 1.4 | — | `--text-subheading` |
| heading-sm | 20px | 1.38 | — | `--text-heading-sm` |
| heading | 24px | 1.33 | — | `--text-heading` |
| heading-lg | 36px | 1.2 | 0.25px | `--text-heading-lg` |
| display | 60px | 1.11 | 0.5px | `--text-display` |

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
| 24 | 24px | `--spacing-24` |
| 28 | 28px | `--spacing-28` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 96 | 96px | `--spacing-96` |
| 160 | 160px | `--spacing-160` |
| 192 | 192px | `--spacing-192` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 9999px |
| buttons | 4px |
| default | 4px |

### Layout

- **Section gap:** 40px
- **Card padding:** 28px
- **Element gap:** 8px

## Components

### Primary Action Button
**Role:** Main call to action

Rounded rectangular button with Spring Green (#a8ff53) background, Obsidian Black (#121317) text. Text is Satoshi-Variable, weight 600, 16px. Padding: 8px vertical, 12px horizontal. Border radius: 4px.

### Ghost Navigation Button
**Role:** Secondary navigation and non-primary actions

Transparent background, Slate Text (#d7d9dd) text. Text is Geist-Regular, weight 400, 16px. Padding: 4px vertical, 8px horizontal. Border radius: 4px.

### Subtle Information Button
**Role:** Informational or tertiary actions within content sections

Dark translucent background rgba(26, 27, 31, 0.5), Whisper White (#e5e7eb) text. Text is Geist-Regular, weight 400, 16px. Border radius: 4px. Padding: 8px vertical, 12px horizontal. Border: 1px solid Whisper White (#e5e7eb).

### Minor Navigation Link
**Role:** Small, context-specific links in clusters

Transparent background, Steel Accent (#b5b8c0) text. Text is Geist-Regular, weight 400, 16px. No specific padding or border, serves as an in-line clickable element.

### Feature Tag
**Role:** Categorization or short labels

Pill-shaped with Obsidian Black (#121317) background and Spring Green (#a8ff53) text. Text is Geist-Regular, weight 400, 14px. Border radius: 9999px. Padding: 4px vertical, 12px horizontal.

### Client Logo Card
**Role:** Displaying trusted brand logos

Charcoal Surface (#1c1e21) background, with a 1px border of Ash Gray (#3b3e45). Content is centered. Border radius: 4px. Padding: dynamically adapts to content, min vertical 12px, horizontal 16px.

### Testimonial Card
**Role:** Showcasing user feedback

Charcoal Surface (#1c1e21) background with a 1px Whisper White (#e5e7eb) border. Border radius: 4px. Internal padding: 28px. Features Slate Text (#d7d9dd) body copy (Geist-Regular 16px) and Satoshi-Variable headings.

## Do's and Don'ts

### Do
- Use Obsidian Black (#121317) as the primary page background to maintain the strong dark theme.
- Apply 4px border radius for all card components, buttons, and input fields for a consistent technical appearance.
- Utilize Spring Green (#a8ff53) exclusively for primary calls to action, maintaining its high-impact role.
- Employ Geist-Regular 16px, weight 400, and Slate Text (#d7d9dd) for all standard body copy.
- Reserve Satoshi-Variable for all headings, ensuring letter-spacing of 0.25px and 0.5px is applied at larger sizes as indicated in typography.
- Maintain an elementGap of 8px between closely related UI elements like buttons in a group or icons and text.
- Use Ash Gray (#3b3e45) for subtle borders and dividers between content blocks to delineate sections without strong visual breaks.

### Don't
- Do not use saturated colors other than Spring Green (#a8ff53) as primary button backgrounds.
- Avoid applying large, soft shadows; leverage background color changes for elevation and depth instead.
- Do not use more than two saturated accent colors in close proximity to prevent visual clutter and maintain focus on the core information.
- Resist using highly decorative or illustrative imagery; favor clean, functional visuals or code snippets.
- Do not vary line-height significantly from the type scale; precise vertical rhythm is key for readability.
- Avoid pill shapes (9999px radius) for anything other than small, tertiary elements like tags to preserve the predominantly rectangular aesthetic.
- Do not use bold weights (600+) from Geist-Regular; rely on Satoshi-Variable for strong typographic emphasis.

## Imagery

The site uses a combination of abstract, gradient-infused graphics, product screenshots, and intricate code snippets. Imagery is generally contained within sections, not full-bleed, and often features a subtle dark background or blur. Photography is minimal, primarily headshots for testimonials. Icons are outline-style, mono-color, and subtle, often employing accent colors for specific features. The primary visual language centers around showcasing code and technical diagrams, giving a direct and functional representation of the product. Imagery is used to explain concepts, not merely decorate, reinforcing the developer-tool identity.

## Layout

The layout follows a primarily max-width contained model (around 1200px equivalent) with centered content blocks, although the hero section extends full-bleed with a dark background. Sections generally alternate between distinct dark backgrounds, creating a clear vertical rhythm. Content is arranged in alternating text-left/visual-right patterns or centered stacks for stronger statements. There's a 3-column card grid for features and testimonials. Navigation is a sticky top bar with a left-aligned logo and right-aligned actions. The overall density is comfortable, with generous vertical spacing (40px) between sections.

## Agent Prompt Guide

### Quick Color Reference
- Text: #d7d9dd
- Background: #121317
- CTA: #a8ff53
- Border: #e5e7eb
- Accent: #9c9af2

### Example Component Prompts
1. Create a primary call to action button: Spring Green background, Obsidian Black text. Text is Satoshi-Variable, weight 600, 16px. Padding: 8px vertical, 12px horizontal. Border radius: 4px. Label: 'Start building now'.
2. Design a Testimonial Card: Charcoal Surface background, 1px Whisper White border, 4px border radius, 28px internal padding. Headline: Satoshi-Variable, 24px, #d7d9dd. Body text: Geist-Regular, 16px, #d7d9dd.
3. Make a Feature Tag: Pill-shaped with Obsidian Black background, Spring Green text. Text is Geist-Regular, 14px, weight 400. Padding: 4px vertical, 12px horizontal. Label: 'AI agents'.
4. Generate a Hero Headline: Text 'Build and deploy fully‑managed AI agents and workflows'. Apply Satoshi-Variable font, size 60px, weight 600, letter-spacing 0.5px, Slate Text (#d7d9dd) color, centered.

## Similar Brands

- **Vercel** — Shares a sophisticated dark-mode aesthetic with strong typography and strategic use of a single vibrant accent color against a clean, technical background.
- **Stripe (developer docs)** — Employs an information-dense yet clean layout, relying on precise typography, subtle monochromatic grays, and code snippets as core visual elements.
- **Linear** — Features a similar philosophy of deep, dark interface backgrounds, crisp neutral text, and focused, vibrant accent colors for interactivity.
- **Tailwind CSS** — Exhibits a modular, structured aesthetic with clear visual hierarchy, often using dark themes and sharp corner radii for a utilitarian feel.
- **GitHub (dark theme)** — Common ground in dark interface design, monospace fonts for code, and a professional, no-nonsense approach to presenting technical information.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-obsidian-black: #121317;
  --color-charcoal-surface: #1c1e21;
  --color-ash-gray: #3b3e45;
  --color-slate-text: #d7d9dd;
  --color-whisper-white: #e5e7eb;
  --color-steel-accent: #b5b8c0;
  --color-spring-green: #a8ff53;
  --color-cloud-violet: #9c9af2;
  --color-deep-plum: #7655fd;
  --color-fuchsia-highlight: #fa3abf;
  --color-cosmic-blue: #479dec;
  --color-flare-orange: #eccf06;
  --color-action-red: #f43f5;
  --color-success-green: #afec73;
  --color-highlight-gradient: #878c99;
  --gradient-highlight-gradient: linear-gradient(to right, rgb(59, 62, 69), rgb(59, 62, 69), rgb(135, 140, 153));

  /* Typography — Font Families */
  --font-geist-regular: 'Geist-Regular', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geistmono-regular: 'GeistMono-Regular', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-satoshi-variable: 'Satoshi-Variable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.4;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.38;
  --text-heading: 24px;
  --leading-heading: 1.33;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: 0.25px;
  --text-display: 60px;
  --leading-display: 1.11;
  --tracking-display: 0.5px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-96: 96px;
  --spacing-160: 160px;
  --spacing-192: 192px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 28px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-tags: 9999px;
  --radius-buttons: 4px;
  --radius-default: 4px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-obsidian-black: #121317;
  --color-charcoal-surface: #1c1e21;
  --color-ash-gray: #3b3e45;
  --color-slate-text: #d7d9dd;
  --color-whisper-white: #e5e7eb;
  --color-steel-accent: #b5b8c0;
  --color-spring-green: #a8ff53;
  --color-cloud-violet: #9c9af2;
  --color-deep-plum: #7655fd;
  --color-fuchsia-highlight: #fa3abf;
  --color-cosmic-blue: #479dec;
  --color-flare-orange: #eccf06;
  --color-action-red: #f43f5;
  --color-success-green: #afec73;
  --color-highlight-gradient: #878c99;

  /* Typography */
  --font-geist-regular: 'Geist-Regular', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geistmono-regular: 'GeistMono-Regular', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-satoshi-variable: 'Satoshi-Variable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.4;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.38;
  --text-heading: 24px;
  --leading-heading: 1.33;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: 0.25px;
  --text-display: 60px;
  --leading-display: 1.11;
  --tracking-display: 0.5px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-96: 96px;
  --spacing-160: 160px;
  --spacing-192: 192px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-full: 9999px;
}
```

# Synthesia — Style Reference
> Indigo-accented data canvas

**Theme:** light

Synthesia presents a bright, spacious interface with a focus on powerful functionality. A clean, almost monochromatic base of white and soft grays provides an expansive canvas, punctuated by a vibrant, deep indigo. This accent color serves as a beacon for primary actions and brand elements, making the UI feel purposeful and energetic without visual clutter. Components favor soft, rounded corners and subtle shadows, maintaining an approachable yet sophisticated aesthetic for a high-tech product.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, elevated card surfaces, main panel fills |
| Subtle Ash | `#e6eaf4` | `--color-subtle-ash` | Subtle background for navigation elements, muted card backgrounds, and very light borders |
| Ghost Fog | `#f5f8ff` | `--color-ghost-fog` | Lightest background for cards and secondary badges, creating a slight visual separation |
| Slate Text | `#333b52` | `--color-slate-text` | Primary body text, neutral action borders, general UI elements |
| Midnight Indigo | `#0d0f2c` | `--color-midnight-indigo` | Dominant text for headlines, strong accents, and footer backgrounds — signifying brand presence and authority |
| Muted Gray | `#656c86` | `--color-muted-gray` | Secondary text, navigation links, ghost button text and borders — used for less prominent information |
| Input Border | `#d1d6e5` | `--color-input-border` | Input field borders, divider lines, subtle button borders |
| Action Indigo | `#3e57da` | `--color-action-indigo` | Primary call-to-action buttons, active states, key interactive icons — the site's main interactive color |
| Sky Veil | `#c6d7fe` | `--color-sky-veil` | Soft accent in card backgrounds and decorative borders, suggesting a subtle glow |
| Deep Accent Indigo | `#1f235b` | `--color-deep-accent-indigo` | Darker accent for badge text and outlines, providing deep contrast against lighter backgrounds |
| Hint Gray | `#969bb5` | `--color-hint-gray` | Placeholder text in input fields, supporting detail text |
| Lime Green Success | `#1a280b` | `--color-lime-green-success` | Text for success badges |
| Vivid Azure | `#8098f9` | `--color-vivid-azure` | Prominent link text and secondary interactive elements, providing a lighter indigo option |
| Soft Green Background | `#ebf6df` | `--color-soft-green-background` | Background for success badges |
| Warm Orange Error | `#42230a` | `--color-warm-orange-error` | Text for warning badges |
| Fuzzy Yellow Background | `#fffadb` | `--color-fuzzy-yellow-background` | Background for warning badges |
| Blue Gradient Base | `linear-gradient(90deg, rgb(227, 235, 255), rgb(198, 215, 254) 50%, rgb(128, 152, 249))` | `--color-blue-gradient-base` | Starting color for decorative linear gradients |

## Tokens — Typography

### Basiersquare Webfont — Custom geometric sans-serif for all text. Its clean, sharp lines contribute to a modern, technical feel. Tight letter-spacing on larger sizes gives headlines a precise, compact presence. · `--font-basiersquare-webfont`
- **Weights:** 400, 500
- **Sizes:** 12px, 14px, 15px, 16px, 18px, 20px, 28px, 40px, 56px, 88px
- **Line height:** 1.00, 1.04, 1.10, 1.20, 1.21, 1.40, 1.43, 1.44, 1.50, 1.57, 1.60
- **Letter spacing:** -0.0500em at 88px, -0.0020em at 12px
- **Role:** Custom geometric sans-serif for all text. Its clean, sharp lines contribute to a modern, technical feel. Tight letter-spacing on larger sizes gives headlines a precise, compact presence.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.5 | -0.24px | `--text-caption` |
| body-sm | 14px | 1.43 | -0.49px | `--text-body-sm` |
| subheading | 18px | 1.44 | -0.72px | `--text-subheading` |
| heading-sm | 20px | 1.4 | -0.8px | `--text-heading-sm` |
| heading | 28px | 1.2 | -0.98px | `--text-heading` |
| heading-lg | 40px | 1.1 | -1.4px | `--text-heading-lg` |
| display | 56px | 1.04 | -1.96px | `--text-display` |
| display-xl | 88px | 1 | -4.4px | `--text-display-xl` |

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
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 56 | 56px | `--spacing-56` |
| 64 | 64px | `--spacing-64` |
| 72 | 72px | `--spacing-72` |
| 80 | 80px | `--spacing-80` |
| 96 | 96px | `--spacing-96` |
| 144 | 144px | `--spacing-144` |
| 168 | 168px | `--spacing-168` |
| 224 | 224px | `--spacing-224` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 24px |
| badges | 999px |
| inputs | 12px |
| buttons | 12px |
| smallComponents | 16px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| md | `rgba(16, 24, 40, 0.08) 0px 2px 10px 0px, rgb(230, 234, 24...` | `--shadow-md` |
| md-2 | `rgba(16, 24, 40, 0.08) 0px 2px 16px 0px` | `--shadow-md-2` |
| md-3 | `rgba(16, 24, 40, 0.08) 0px 2px 10px 0px` | `--shadow-md-3` |
| subtle | `rgb(209, 214, 229) 0px 0px 0px 1px, rgba(16, 24, 40, 0.08...` | `--shadow-subtle` |
| lg | `rgba(16, 24, 40, 0.08) 0px 6px 20px 0px` | `--shadow-lg` |

### Layout

- **Page max-width:** 1200px
- **Section gap:** 40px
- **Card padding:** 32px
- **Element gap:** 24px

## Components

### Primary Filled Button
**Role:** Main call-to-action button, signaling key interactions.

Background: Action Indigo (#3e57da), Text: Canvas White (#ffffff), Border Radius: 12px, Padding: 16px vertical, 24px horizontal. Typography: Basiersquare Webfont, 16px, weight 500.

### Secondary Outlined Button
**Role:** Subtle alternative actions, often paired with a primary button.

Background: Canvas White (#ffffff), Text: Midnight Indigo (#0d0f2c), Border: 1px solid Input Border (#d1d6e5), Border Radius: 10px, Padding: 12px vertical, 18px horizontal. Typography: Basiersquare Webfont, 15px, weight 400.

### Ghost Link Button
**Role:** Discreet, text-based actions found in navigation or inline.

Background: transparent, Text: Muted Gray (#656c86), Border: none, Border Radius: 0px, Padding: 0px. Typography: Basiersquare Webfont, 14px, weight 400.

### Elevated Card
**Role:** Content container that gently floats above the page background, drawing attention.

Background: Canvas White (#ffffff), Border Radius: 24px, Padding: 32px, Shadow: rgba(16, 24, 40, 0.08) 0px 2px 16px 0px.

### Subtle Background Card
**Role:** Content container with a soft background, used for grouping related information.

Background: Ghost Fog (#f5f8ff), Border Radius: 16px, Padding: variable (e.g. 0px for image cards). No shadow.

### Text Input Field
**Role:** Standard input for user data.

Background: Canvas White (#ffffff), Text: Slate Text (#333b52), Placeholder: Hint Gray (#969bb5), Border: 1px solid Input Border (#d1d6e5), Border Radius: 12px, Padding: 12px vertical, 16px horizontal.

### Success Badge
**Role:** Indicates positive status or categorization.

Background: Soft Green Background (#ebf6df), Text: Lime Green Success (#1a280b), Border Radius: 999px (pill-shaped), Padding: 2px vertical, 8px horizontal. Typography: Basiersquare Webfont, 12px, weight 400.

### Promotional Badge
**Role:** Highlights features or special states.

Background: Ghost Fog (#f5f8ff), Text: Deep Accent Indigo (#1f235b), Border Radius: 999px (pill-shaped), Padding: 8px vertical, 16px horizontal. Typography: Basiersquare Webfont, 14px, weight 500.

## Do's and Don'ts

### Do
- Prioritize Canvas White (#ffffff) and Ghost Fog (#f5f8ff) for large background areas to maintain a bright, open feel.
- Use Action Indigo (#3e57da) exclusively for primary calls-to-action and key interactive elements to ensure visual clarity and drive user action.
- Apply a 12px border radius for buttons and input fields, and 24px for main content cards to achieve a consistent soft, modern look.
- Reserve Midnight Indigo (#0d0f2c), 88px, -0.0500em for display headlines to create a bold, commanding presence with precise tracking.
- Implement the rgba(16, 24, 40, 0.08) 0px 2px 16px 0px shadow for elevated cards to provide subtle depth without heaviness.
- Maintain a clear hierarchy with Slate Text (#333b52) for main body content and Muted Gray (#656c86) for secondary information or helper text.
- Ensure generous spacing, using 24px as the primary element gap and 32px for card padding, to enhance readability and visual comfort.

### Don't
- Do not introduce new saturated primary colors beyond Action Indigo (#3e57da); the brand relies on a single dominant accent.
- Avoid sharp corners; all interactive and content-holding components should embrace a rounded aesthetic (min. 12px radius).
- Do not use heavy, opaque shadow layers; stick to the light, diffuse shadows provided for elevation.
- Refrain from using thin, light fonts for body copy; ensure sufficient weight (400 or 500) and contrast for readability against light backgrounds.
- Do not overcrowd sections; maintain the generous 40px section gap to provide breathing room between content blocks.
- Avoid using multiple border treatments on the same component; stick to either solid borders or shadows for definition.
- Do not deviate from Basiersquare Webfont; its distinct character is central to the brand's typographic identity.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas White | `#ffffff` | Primary page background and base for most content sections. |
| 1 | Ghost Fog | `#f5f8ff` | Slightly elevated background for cards and secondary panels, offering subtle differentiation from the main canvas. |
| 2 | Canvas White Elevated | `#ffffff` | Card surfaces and modal backgrounds that receive a distinct shadow for elevation. |

## Elevation

- **Card:** `rgba(16, 24, 40, 0.08) 0px 2px 16px 0px`
- **Interactive Element:** `rgba(16, 24, 40, 0.08) 0px 2px 10px 0px`
- **Button/Other:** `rgb(209, 214, 229) 0px 0px 0px 1px, rgba(16, 24, 40, 0.08) 0px 2px 16px 0px`

## Imagery

Imagery style is product-focused, featuring tightly cropped product screenshots and AI avatars presented on clean, often white or lightly textured backgrounds. Photography of people tends to be professional, well-lit, and directly engaging. Illustrations are minimal, flat, and serve to support UI elements rather than dominate. Icons are filled, with a medium stroke weight appearance, contributing to the clean and functional aesthetic. Imagery acts primarily to explain product features, showcase AI capabilities, and demonstrate social proof, maintaining a high level of polish and visual clarity against the predominantly white UI.

## Layout

The page adheres to a max-width contained layout, typically centered at 1200px. The hero section is full-bleed, often featuring a subtle background gradient or dark panel with a centered headline and description, highlighting the primary call to action. Section rhythm is primarily consistent, with generous vertical spacing (40px between sections) and alternating light/dark (white/indigo gradient) backgrounds to visually break up content. Content arrangement frequently uses alternating text-left/image-right or vertical stacks for features, and common 3-column card grids. Overall density is comfortable, providing ample breathing room. Navigation is a sticky top bar with a clear brand logo, primary navigation links, and distinct 'Log in' and 'Get started' buttons.

## Agent Prompt Guide

Quick Color Reference:
- text: #333b52
- background: #ffffff
- border: #d1d6e5
- accent: #3e57da
- primary action: #3e57da (filled action)

Example Component Prompts:
1. Create a hero section: full-width dark indigo gradient background (linear-gradient(90deg, rgb(128, 152, 249), rgb(62, 87, 218) 50%, rgb(44, 67, 184))). Headline 'Accelerate Video Creation with AI' in Basiersquare Webfont, 88px, weight 500, #ffffff, letter-spacing -4.4px. Subtext 'Generate studio-quality videos in minutes' in Basiersquare Webfont, 20px, weight 400, #c6d7fe. A primary button 'Get Started' with background #3e57da, text #ffffff, 12px radius, 16px 24px padding.
2. Create a feature card: background #f5f8ff, 16px radius, 32px padding on all sides. Headline 'Personalized Content' in Basiersquare Webfont, 28px, weight 500, #0d0f2c, letter-spacing -0.98px. Body text 'Dynamically create videos for individual customer segments.' in Basiersquare Webfont, 15px, weight 400, #333b52.
3. Create an input field for email: background #ffffff, border 1px solid #d1d6e5, 12px radius, 12px 16px padding. Placeholder text 'Enter your email' in Basiersquare Webfont, 15px, weight 400, #969bb5. Label above 'Email Address' in Basiersquare Webfont, 14px, weight 400, #333b52.
4. Create a success badge: background #ebf6df, text #1a280b, 999px radius, 2px 8px padding. Text: 'Live Now' in Basiersquare Webfont, 12px, weight 400.

## Similar Brands

- **OpenAI** — Clean, bright UI with a modern sans-serif and a single prominent brand color for CTAs, framing advanced AI technology.
- **Anthropic** — Spacious, light-themed interface and a professional, tech-forward sans-serif, using color sparingly for hierarchy and interaction.
- **Linear** — Focus on high information density within a clean, muted palette, relying on precise typography and subtle elevation for hierarchy.
- **Vercel** — Developer-focused aesthetic with clean whitespace, strong typography, and a single vibrant accent color to highlight key actions and branding.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-subtle-ash: #e6eaf4;
  --color-ghost-fog: #f5f8ff;
  --color-slate-text: #333b52;
  --color-midnight-indigo: #0d0f2c;
  --color-muted-gray: #656c86;
  --color-input-border: #d1d6e5;
  --color-action-indigo: #3e57da;
  --color-sky-veil: #c6d7fe;
  --color-deep-accent-indigo: #1f235b;
  --color-hint-gray: #969bb5;
  --color-lime-green-success: #1a280b;
  --color-vivid-azure: #8098f9;
  --color-soft-green-background: #ebf6df;
  --color-warm-orange-error: #42230a;
  --color-fuzzy-yellow-background: #fffadb;
  --color-blue-gradient-base: #e3ebff;
  --gradient-blue-gradient-base: linear-gradient(90deg, rgb(227, 235, 255), rgb(198, 215, 254) 50%, rgb(128, 152, 249));

  /* Typography — Font Families */
  --font-basiersquare-webfont: 'Basiersquare Webfont', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: -0.24px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.43;
  --tracking-body-sm: -0.49px;
  --text-subheading: 18px;
  --leading-subheading: 1.44;
  --tracking-subheading: -0.72px;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.4;
  --tracking-heading-sm: -0.8px;
  --text-heading: 28px;
  --leading-heading: 1.2;
  --tracking-heading: -0.98px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -1.4px;
  --text-display: 56px;
  --leading-display: 1.04;
  --tracking-display: -1.96px;
  --text-display-xl: 88px;
  --leading-display-xl: 1;
  --tracking-display-xl: -4.4px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-144: 144px;
  --spacing-168: 168px;
  --spacing-224: 224px;

  /* Layout */
  --page-max-width: 1200px;
  --section-gap: 40px;
  --card-padding: 32px;
  --element-gap: 24px;

  /* Border Radius */
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-full: 80px;
  --radius-full-2: 100px;
  --radius-full-3: 999px;
  --radius-full-4: 15984px;

  /* Named Radii */
  --radius-cards: 24px;
  --radius-badges: 999px;
  --radius-inputs: 12px;
  --radius-buttons: 12px;
  --radius-smallcomponents: 16px;

  /* Shadows */
  --shadow-md: rgba(16, 24, 40, 0.08) 0px 2px 10px 0px, rgb(230, 234, 244) 0px 0px 0px 1px;
  --shadow-md-2: rgba(16, 24, 40, 0.08) 0px 2px 16px 0px;
  --shadow-md-3: rgba(16, 24, 40, 0.08) 0px 2px 10px 0px;
  --shadow-subtle: rgb(209, 214, 229) 0px 0px 0px 1px, rgba(16, 24, 40, 0.08) 0px 2px 16px 0px;
  --shadow-lg: rgba(16, 24, 40, 0.08) 0px 6px 20px 0px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-ghost-fog: #f5f8ff;
  --surface-canvas-white-elevated: #ffffff;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-subtle-ash: #e6eaf4;
  --color-ghost-fog: #f5f8ff;
  --color-slate-text: #333b52;
  --color-midnight-indigo: #0d0f2c;
  --color-muted-gray: #656c86;
  --color-input-border: #d1d6e5;
  --color-action-indigo: #3e57da;
  --color-sky-veil: #c6d7fe;
  --color-deep-accent-indigo: #1f235b;
  --color-hint-gray: #969bb5;
  --color-lime-green-success: #1a280b;
  --color-vivid-azure: #8098f9;
  --color-soft-green-background: #ebf6df;
  --color-warm-orange-error: #42230a;
  --color-fuzzy-yellow-background: #fffadb;
  --color-blue-gradient-base: #e3ebff;

  /* Typography */
  --font-basiersquare-webfont: 'Basiersquare Webfont', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: -0.24px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.43;
  --tracking-body-sm: -0.49px;
  --text-subheading: 18px;
  --leading-subheading: 1.44;
  --tracking-subheading: -0.72px;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.4;
  --tracking-heading-sm: -0.8px;
  --text-heading: 28px;
  --leading-heading: 1.2;
  --tracking-heading: -0.98px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -1.4px;
  --text-display: 56px;
  --leading-display: 1.04;
  --tracking-display: -1.96px;
  --text-display-xl: 88px;
  --leading-display-xl: 1;
  --tracking-display-xl: -4.4px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-144: 144px;
  --spacing-168: 168px;
  --spacing-224: 224px;

  /* Border Radius */
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-full: 80px;
  --radius-full-2: 100px;
  --radius-full-3: 999px;
  --radius-full-4: 15984px;

  /* Shadows */
  --shadow-md: rgba(16, 24, 40, 0.08) 0px 2px 10px 0px, rgb(230, 234, 244) 0px 0px 0px 1px;
  --shadow-md-2: rgba(16, 24, 40, 0.08) 0px 2px 16px 0px;
  --shadow-md-3: rgba(16, 24, 40, 0.08) 0px 2px 10px 0px;
  --shadow-subtle: rgb(209, 214, 229) 0px 0px 0px 1px, rgba(16, 24, 40, 0.08) 0px 2px 16px 0px;
  --shadow-lg: rgba(16, 24, 40, 0.08) 0px 6px 20px 0px;
}
```

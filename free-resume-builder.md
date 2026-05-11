# Free Resume Builder — Style Reference
> Calm productivity, like a well-organized office. Light-filled and orderly, with key tools highlighted in a crisp blue.

**Theme:** light

Resume.io evokes a feeling of quiet competence through its balanced use of a predominantly cool color palette and generous spacing. The interface prioritizes clarity and approachability, using soft blues and grays alongside a confident, sans-serif typography. Interactive elements are clearly distinguished by a vibrant blue, making complex forms feel manageable and guiding users through the resume-building process with a reassuring visual tone.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Page Graphite | `#0f141` | `--color-page-graphite` | Deepest primary text, page headers and footers — provides strong contrast to the light background. |
| Slate Text | `#1e2532` | `--color-slate-text` | Standard body text, headings, and icon fills, establishing a consistent dark-on-light readability. |
| Midtone Gray | `#656e83` | `--color-midtone-gray` | Secondary text and subtle details, offering visual hierarchy without harsh contrast. |
| Soft Gray | `#828ba2` | `--color-soft-gray` | Muted text, placeholder text, and subtle borders, ideal for less prominent information. |
| Hover Gray | `#9fa6bb` | `--color-hover-gray` | List item hover states, adding a soft visual feedback. |
| Light Steel | `#d9deeb` | `--color-light-steel` | Subtle borders and dividers, providing structure without visual weight. |
| Faded Blueprint | `#f1f2ff` | `--color-faded-blueprint` | Background for certain interactive areas or subtle distinction, like a muted blueprint showing the foundation. |
| Whisper White | `#f7f9fc` | `--color-whisper-white` | Card backgrounds and lighter section fills, creating a sense of cleanliness and space. |
| Pure White | `#ffffff` | `--color-pure-white` | Dominant page background, essential for the overall light theme and high contrast. |
| Action Blue | `#1a91f0` | `--color-action-blue` | Primary calls to action, interactive elements, and key visual accents — this vibrant blue guides user interaction. |
| Recruiter Blue | `#1a1c6a` | `--color-recruiter-blue` | Background for certain button variants, offering a darker, more authoritative blue contrasting the main action blue. |
| Trustpilot Green | `#00b67a` | `--color-trustpilot-green` | Trust indicators and success states, a clear and recognizable signifier. |
| Error Red | `#fb4458` | `--color-error-red` | Error messages and negative feedback. |

## Tokens — Typography

### TT Commons — Primary typeface for all UI elements, headings, body text. Its clean, geometric form supports readability across all sizes, suitable for the professional context of resume building. · `--font-tt-commons`
- **Substitute:** Inter
- **Weights:** 400, 500, 600
- **Sizes:** 14px, 15px, 16px, 18px, 19px, 22px, 24px, 28px, 31px, 40px, 52px, 67px
- **Line height:** 0.96, 1.00, 1.07, 1.14, 1.16, 1.17, 1.20, 1.22, 1.25, 1.26, 1.27, 1.43
- **Letter spacing:** 0.0210em at 14px, 0.1290em at 18px
- **Role:** Primary typeface for all UI elements, headings, body text. Its clean, geometric form supports readability across all sizes, suitable for the professional context of resume building.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 14px | 1.43 | 0.29px | `--text-caption` |
| body | 16px | 1.26 | — | `--text-body` |
| subheading | 18px | 1.22 | — | `--text-subheading` |
| heading | 22px | 1.14 | — | `--text-heading` |
| heading-lg | 28px | 1.16 | — | `--text-heading-lg` |
| display-sm | 31px | 1.17 | — | `--text-display-sm` |
| display | 40px | 1.07 | — | `--text-display` |
| display-lg | 52px | 1 | — | `--text-display-lg` |
| display-xl | 67px | 0.96 | — | `--text-display-xl` |

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
| 44 | 44px | `--spacing-44` |
| 48 | 48px | `--spacing-48` |
| 60 | 60px | `--spacing-60` |
| 64 | 64px | `--spacing-64` |
| 120 | 120px | `--spacing-120` |
| 144 | 144px | `--spacing-144` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 24px |
| cards | 4px |
| images | 4px |
| buttons | 4px |
| pillButtons | 36px |

### Layout

- **Section gap:** 48-80px
- **Card padding:** 24px
- **Element gap:** 4px

## Components

### Secondary Outline Button
**Role:** Alternative action button

Background: transparent (rgba(26, 145, 240, 0.1)), Text: Action Blue (#1a91f0), Border Radius: 4px, Padding: 12px vertical, 24px horizontal. Provides a less dominant call to action while maintaining brand identity.

### Rounded Service Card
**Role:** Feature or service description

Background: Whisper White (#f7f9fc) or similar light neutrals (e.g. #e7f4ed), Text: Slate Text (#1e2532), Border Radius: 24px, Padding: 24px all sides. Used for displaying key features or services with a soft, inviting aesthetic.

### Navigation Link
**Role:** Header and footer navigation

Text: Slate Text (#1e2532), Weight: 400, Hover: Action Blue (#1a91f0). Simple, direct, and changes color on hover for clear interactivity.

## Do's and Don'ts

### Do
- Use Action Blue (#1a91f0) for all primary interactive elements like buttons and active navigation states to guide user flow.
- Apply a 4px radius consistently to all standard buttons, cards, and input fields for a subtle softness.
- Maintain a clear visual hierarchy by using Page Graphite (#0f141e) for main headings and Slate Text (#1e2532) for body content.
- Utilize Whisper White (#f7f9fc) as the default background for content cards and sections to ensure a clean, breathable canvas.
- Employ the TT Commons typeface for all text elements, leveraging its 400, 500, and 600 weights to delineate content importance.

### Don't
- Do not use dark backgrounds for main content areas; reserve them for specific hero sections or full-bleed branding only.
- Avoid arbitrary border radii; stick to the defined 4px for standard elements, 24px for rounded cards, and 36px for pill buttons.
- Do not introduce new saturated colors beyond Action Blue (#1a91f0); rely on the existing neutral palette for variety.
- Do not use letter-spacing on body text; apply it only to larger headings or specific styled elements as defined in typography.
- Avoid heavy drop shadows or complex gradients; the aesthetic is grounded in simplicity and subtle shifts in background color and outline.

## Imagery

The site uses a mix of crisp product screenshots and abstract 3D graphics. Product screenshots, like the resume preview, are contained within soft, rounded cards and feature tight crops that highlight the application's UI. Abstract graphics leverage a light, almost translucent blue/gray palette, often with subtle geometric forms and ethereal glow effects, creating a futuristic yet friendly atmosphere. Icons are primarily filled, monochrome (Slate Text #1e2532) with occasional Action Blue (#1a91f0) accents, featuring a medium stroke weight and a friendly, rounded style. Imagery serves both to showcase product functionality and to provide decorative, atmospheric elements that reinforce the brand's tech-forward yet approachable identity.

## Layout

The page primarily employs a max-width contained layout, centered on the screen, with content sections typically structured within a clear grid. The hero section is a split layout with a prominent headline and CTA on the left, balanced by a composite product visual on the right against a subtly textured light blue background. Following sections maintain a spacious vertical rhythm with alternating content arrangements: some are centered stacks, others utilize a text-left/image-right pattern. Feature sections often present information in a 2 or 3-column card grid, allowing for clear visual separation. The navigation is a sticky top bar with a left-aligned logo, right-aligned primary CTA button, and centered navigation links, providing consistent access across the site. Generous vertical spacing between sections creates a breathable, uncluttered experience.

## Agent Prompt Guide

### Quick Color Reference
- Text (body): `#1e2532`
- Background (page): `#ffffff`
- CTA (primary): `#1a91f0`
- Border (subtle): `#d9deeb`
- Accent (secondary text): `#828ba2`

### 3-5 Example Component Prompts
1. Create a hero section with a `Whisper White (#f7f9fc)` background. The main headline should be `52px` TT Commons `weight 600`, `Page Graphite (#0f141e)`. Include a primary button with `Action Blue (#1a91f0)` background, `Pure White (#ffffff)` text, `4px` radius, and `12px` vertical, `24px` horizontal padding.
2. Design a feature card: `Whisper White (#f7f9fc)` background, `24px` radius, `24px` padding on all sides. Feature a `28px` TT Commons `weight 500` title in `Slate Text (#1e2532)` and `16px` TT Commons `weight 400` body text in `Midtone Gray (#656e83)`.
3. Generate a navigation bar: `Pure White (#ffffff)` background, with links in `Slate Text (#1e2532)` at `16px` TT Commons `weight 400` that turn `Action Blue (#1a91f0)` on hover. Include a `Pill Tag Button` variant in `Recruiter Blue (#1a1c6a)` with `e7eaf4` text, `36px` radius, `6px` vertical, `12px` horizontal padding.
4. Create a small text badge for a trust rating: `Trustpilot Green (#00b67a)` text, `14px` TT Commons `weight 500`, with a supporting green star icon, on a transparent background.

## Similar Brands

- **Canva** — Similar light, bright theme with simple typography and a single prominent accent color for interactive elements.
- **Webflow** — Clear, spacious layouts, a dominant sans-serif font family, and a focus on digestible content blocks.
- **monday.com** — Use of soft, slightly tinted background colors for sections and cards to create visual separation without harsh lines or shadows.
- **Figma** — A clean, functional aesthetic with subtle use of color for primary actions against a mostly neutral interface, prioritizing content and tools.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-page-graphite: #0f141;
  --color-slate-text: #1e2532;
  --color-midtone-gray: #656e83;
  --color-soft-gray: #828ba2;
  --color-hover-gray: #9fa6bb;
  --color-light-steel: #d9deeb;
  --color-faded-blueprint: #f1f2ff;
  --color-whisper-white: #f7f9fc;
  --color-pure-white: #ffffff;
  --color-action-blue: #1a91f0;
  --color-recruiter-blue: #1a1c6a;
  --color-trustpilot-green: #00b67a;
  --color-error-red: #fb4458;

  /* Typography — Font Families */
  --font-tt-commons: 'TT Commons', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.43;
  --tracking-caption: 0.29px;
  --text-body: 16px;
  --leading-body: 1.26;
  --text-subheading: 18px;
  --leading-subheading: 1.22;
  --text-heading: 22px;
  --leading-heading: 1.14;
  --text-heading-lg: 28px;
  --leading-heading-lg: 1.16;
  --text-display-sm: 31px;
  --leading-display-sm: 1.17;
  --text-display: 40px;
  --leading-display: 1.07;
  --text-display-lg: 52px;
  --leading-display-lg: 1;
  --text-display-xl: 67px;
  --leading-display-xl: 0.96;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;

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
  --spacing-44: 44px;
  --spacing-48: 48px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-120: 120px;
  --spacing-144: 144px;

  /* Layout */
  --section-gap: 48-80px;
  --card-padding: 24px;
  --element-gap: 4px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 36px;
  --radius-3xl-3: 40px;
  --radius-full: 100px;

  /* Named Radii */
  --radius-tags: 24px;
  --radius-cards: 4px;
  --radius-images: 4px;
  --radius-buttons: 4px;
  --radius-pillbuttons: 36px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-page-graphite: #0f141;
  --color-slate-text: #1e2532;
  --color-midtone-gray: #656e83;
  --color-soft-gray: #828ba2;
  --color-hover-gray: #9fa6bb;
  --color-light-steel: #d9deeb;
  --color-faded-blueprint: #f1f2ff;
  --color-whisper-white: #f7f9fc;
  --color-pure-white: #ffffff;
  --color-action-blue: #1a91f0;
  --color-recruiter-blue: #1a1c6a;
  --color-trustpilot-green: #00b67a;
  --color-error-red: #fb4458;

  /* Typography */
  --font-tt-commons: 'TT Commons', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.43;
  --tracking-caption: 0.29px;
  --text-body: 16px;
  --leading-body: 1.26;
  --text-subheading: 18px;
  --leading-subheading: 1.22;
  --text-heading: 22px;
  --leading-heading: 1.14;
  --text-heading-lg: 28px;
  --leading-heading-lg: 1.16;
  --text-display-sm: 31px;
  --leading-display-sm: 1.17;
  --text-display: 40px;
  --leading-display: 1.07;
  --text-display-lg: 52px;
  --leading-display-lg: 1;
  --text-display-xl: 67px;
  --leading-display-xl: 0.96;

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
  --spacing-44: 44px;
  --spacing-48: 48px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-120: 120px;
  --spacing-144: 144px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 36px;
  --radius-3xl-3: 40px;
  --radius-full: 100px;
}
```

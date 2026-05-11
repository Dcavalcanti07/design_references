# Index — Style Reference
> Deep space command console.

**Theme:** dark

Index employs a deep space command console aesthetic, combining dark, muted violet and near-black surfaces with luminous accents. The interface prioritizes organized information density, utilizing crisp borders and subtle holographic-like shadows to define interactive elements. Typography is precise and utilitarian, while occasional vibrant gradients and glows infuse points of interest into the otherwise controlled, dark environment.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Void Black | `#02030b` | `--color-void-black` | Deepest canvas background, elevated card surfaces |
| Eclipse Gray | `#04061c` | `--color-eclipse-gray` | Primary canvas background |
| Twilight Violet | `#0c0a2b` | `--color-twilight-violet` | Card backgrounds, secondary surface fills |
| Ash Slate | `#11132b` | `--color-ash-slate` | Subtle surface accents and divider lines |
| Slate Blue | `#152e58` | `--color-slate-blue` | Violet decorative accent for icons, marks, and small graphic details. Do not promote it to the primary CTA color |
| Gunmetal Gray | `#202333` | `--color-gunmetal-gray` | Subtle button backgrounds, deeper card borders |
| Dark Star | `#242444` | `--color-dark-star` | Violet wash for highlight backgrounds, decorative bands, and soft emphasis behind content. Do not promote it to the primary CTA color |
| Lunar Violet | `#292a4d` | `--color-lunar-violet` | Prominent card borders and section separators |
| Nebula Blue | `#2c2b52` | `--color-nebula-blue` | Contrasting borders and section backgrounds |
| Graphite Border | `#353545` | `--color-graphite-border` | Outlined button borders, subtle UI demarcations |
| Deep Iris | `#404267` | `--color-deep-iris` | Decorative border accents, illustration strokes |
| Steel Gray | `#4f5160` | `--color-steel-gray` | Subtle shadow color for UI elements |
| Faded Gray | `#9b9ba4` | `--color-faded-gray` | Muted text, secondary labels, subtle borders |
| Light Ghost | `#fbf1ff` | `--color-light-ghost` | Primary body text, headings, and icon fills |
| Vibrant Blue | `#0067ff` | `--color-vibrant-blue` | Blue wash for highlight backgrounds, decorative bands, and soft emphasis behind content |
| Electric Cyan | `linear-gradient(135deg, rgb(2, 229, 239) 0%, rgb(72, 89, 235) 71.5%, rgb(138, 56, 244) 100%)` | `--color-electric-cyan` | Hero gradient start (part of Aurora Borealis gradient) |
| Plasma Pink | `#512141` | `--color-plasma-pink` | Subtle decorative background fills, highlights |
| Crimson Bloom | `#ff3a63` | `--color-crimson-bloom` | Red wash for highlight backgrounds, decorative bands, and soft emphasis behind content. Do not promote it to the primary CTA color |
| Galactic Rainbow | `#665eff` | `--color-galactic-rainbow` | Decorative elements, internal card highlights |
| Status Green | `#22a06b` | `--color-status-green` | Green decorative accent for icons, marks, and small graphic details. Use as a supporting accent, not as a status color |
| Warning Yellow | `#ffff00` | `--color-warning-yellow` | Yellow wash for highlight backgrounds, decorative bands, and soft emphasis behind content. Use as a supporting accent, not as a status color |
| Golden Glow | `#ffe684` | `--color-golden-glow` | Yellow decorative accent for icons, marks, and small graphic details. Use as a supporting accent, not as a status color |

## Tokens — Typography

### Inter — Body text, navigation links, secondary labels, and button text, providing a reliable and clear baseline for information. Uses tabular figures for data alignment. · `--font-inter`
- **Substitute:** system-ui
- **Weights:** 400, 500, 600
- **Sizes:** 11px, 13px, 14px, 15px, 16px, 17px, 18px, 24px
- **Line height:** 1.50, 1.60
- **Letter spacing:** normal
- **OpenType features:** `"tnum"`
- **Role:** Body text, navigation links, secondary labels, and button text, providing a reliable and clear baseline for information. Uses tabular figures for data alignment.

### Index — Headlines, emphasizes large, impactful statements, using a custom font for distinct brand presence. The tighter letter spacing on larger sizes creates a cohesive, modern title feel. Uses tabular figures. · `--font-index`
- **Substitute:** system-ui
- **Weights:** 400, 500, 600
- **Sizes:** 12px, 13px, 14px, 15px, 16px, 17px, 18px, 20px, 22px, 23px, 32px, 42px, 56px, 72px
- **Line height:** 1.20, 1.30, 1.50, 1.60
- **Letter spacing:** 0.0030em at 72px, 0.0040em at 56px, 0.0050em at 42px, 0.0060em at 32px, 0.0090em at 23px, 0.0110em at 22px, 0.0130em at 20px, 0.0140em at 18px, 0.0150em at 17px
- **OpenType features:** `"tnum"`
- **Role:** Headlines, emphasizes large, impactful statements, using a custom font for distinct brand presence. The tighter letter spacing on larger sizes creates a cohesive, modern title feel. Uses tabular figures.

### -apple-system — -apple-system — detected in extracted data but not described by AI · `--font-apple-system`
- **Weights:** 500, 600
- **Sizes:** 13px, 15px
- **Line height:** 1.6
- **Role:** -apple-system — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 11px | 1.5 | — | `--text-caption` |
| body-lg | 16px | 1.5 | — | `--text-body-lg` |
| subheading | 18px | 1.5 | 0.25px | `--text-subheading` |
| heading-sm | 24px | 1.5 | — | `--text-heading-sm` |
| heading | 32px | 1.2 | 0.19px | `--text-heading` |
| heading-lg | 42px | 1.2 | 0.21px | `--text-heading-lg` |
| display | 56px | 1.2 | 0.22px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** compact

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
| 48 | 48px | `--spacing-48` |
| 60 | 60px | `--spacing-60` |
| 72 | 72px | `--spacing-72` |
| 200 | 200px | `--spacing-200` |

### Border Radius

| Element | Value |
|---------|-------|
| lg | 20px |
| md | 12px |
| sm | 6px |
| xl | 24px |
| none | 0px |
| pill | 30px |
| round | 50px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| sm | `oklch(0.2 0 0 / 0.4) 1px 2px 6px 0px` | `--shadow-sm` |
| md | `oklch(0 0 0 / 0.1) 1px 1px 10px 0px` | `--shadow-md` |
| sm-2 | `oklch(0.89 0 0 / 0.18) 0px 1px 8px 0px` | `--shadow-sm-2` |
| xl | `oklch(0.76 0.15 225.13 / 0.6) 0px 0px 70px 0px, oklch(0.5...` | `--shadow-xl` |
| subtle | `rgb(225, 225, 225) 615px 66px 0px 0px, rgb(225, 225, 225)...` | `--shadow-subtle` |
| subtle-2 | `rgb(225, 225, 225) 435px 352px 0px 0px, rgb(225, 225, 225...` | `--shadow-subtle-2` |
| subtle-3 | `rgb(225, 225, 225) 219px 422px 0px 0px, rgb(225, 225, 225...` | `--shadow-subtle-3` |
| xl-2 | `rgba(0, 0, 0, 0.4) 0px 4px 40px 8px, rgba(0, 0, 0, 0.8) 0...` | `--shadow-xl-2` |

### Layout

- **Section gap:** 60px
- **Card padding:** 12px
- **Element gap:** 8px

## Components

### Navigation Link (Ghost)
**Role:** Top navigation items, secondary actions within complex UIs.

Text link, uses Inter 15px weight 400 '#fbf1ff' with no background or border, transitioning to '#9b9ba4' on hover. Radius is 12px for padding areas.

### Primary Action Button (Filled)
**Role:** Main call to action for the site and product onboarding.

Background: '#ff3a63' (Crimson Bloom), text: '#fbf1ff' (Light Ghost), border radius: 30px, padding: 5px vertical, 26px horizontal. Font is Inter 16px weight 500.

### Subtle Action Button (Pill)
**Role:** Informational prompts or secondary, less urgent actions.

Background: #0c0a2b (Twilight Violet) with 23% opacity, text: #fbf1ff (Light Ghost), border radius: 50px, padding: 5px vertical, 12px horizontal. Font is Inter 16px weight 500.

### Feature Card (Subdued)
**Role:** Container for features, testimonials, or content blocks.

Background: #0c0a2b (Twilight Violet), border: 1px solid #292a4d (Lunar Violet), border radius: 24px. Internal padding is 12px. Features a subtle radial gradient light source inside for emphasis.

### Data Row Card
**Role:** Items within a table or list view, emphasizing content over visual flourish.

Background: #13151f (Eclipse Gray), border: 1px solid #202333 (Gunmetal Gray), border radius: 6px. No significant shadow, prioritizing a flat, data-centric presentation.

### Interactive Tag
**Role:** Categorization, status labels, or embedded filter options.

Background: rgba(0,0,0,0) (transparent), text: '#fbf1ff' (Light Ghost), border: 1px solid '#fbf1ff' (Light Ghost), border radius: 12px. Padding: 2px vertical, 20px horizontal. Font is Inter 13px weight 500.

## Do's and Don'ts

### Do
- Prioritize '#fbf1ff' for all primary text and '#9b9ba4' for supporting text and neutral links to maintain hierarchy and readability on dark backgrounds.
- Use '#04061c' as the default page background and '#02030b' for elevated sections and card backgrounds to create a clear surface hierarchy.
- Apply 30px border radius for all prominent buttons and input fields to achieve the brand's 'pill' shape, contrasting with the sharper 6px for tabular data cards.
- Use 12px as the internal padding for most card types, and 8px for spacing elements within content blocks for a compact layout.
- Enhance interactive elements like call-to-action buttons with the '#ff3a63' (Crimson Bloom) background, reserving this vibrant color for primary actions.
- Implement the 'Aurora Borealis' gradient (`linear-gradient(135deg, rgb(2, 229, 239) 0%, rgb(72, 89, 235) 71.5%, rgb(138, 56, 244) 100%)`) for hero sections or significant brand showcases only.
- Apply a 1px solid border using '#292a4d' for major card containers to define boundaries against similar dark backgrounds.

### Don't
- Avoid using light backgrounds. The system is designed for a dark mode experience; light themes will break the visual hierarchy.
- Do not introduce sharp corners on interactive components like buttons or tags; they should adhere to the established 30px or 12px radii.
- Do not deviate from the Inter for body text and Index for headlines; these fonts define the brand's typographic voice.
- Refrain from adding arbitrary shadows; use the defined subtle `oklch(0.2 0 0 / 0.4) 1px 2px 6px 0px` for minor elevation and avoid heavy box shadows.
- Do not use '#ff3a63' or '#22a06b' for decorative purposes; these are reserved for primary actions and semantic status indicators respectively.
- Avoid excessive spacing. Maintain a compact density, using 8px for element gaps to keep information focused.
- Do not use bold or extra-bold weights for headlines; the brand's headlines maintain impact through large sizing and precise tracking, at weights up to 600.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Eclipse Gray Canvas | `#04061c` | Primary page background, base layer. |
| 2 | Twilight Violet Surface | `#0c0a2b` | Secondary backgrounds, default card level for content blocks. |
| 3 | Deep Space Panel | `#02030b` | Elevated card surfaces, product UI elements, embedded applications. |

## Elevation

- **Card:** `oklch(0.2 0 0 / 0.4) 1px 2px 6px 0px`
- **Card (subtle):** `oklch(0 0 0 / 0.1) 1px 1px 10px 0px`
- **Navigation Bar:** `oklch(0.89 0 0 / 0.18) 0px 1px 8px 0px`

## Imagery

The visual language focuses on abstract graphics and product screenshots within a UI context. Photography is minimal, appearing only for 'about us' style content. Illustrations are either iconic, simple geometric shapes (e.g., within buttons/tags), or abstract, volumetric forms rendered with brand gradients. Product screenshots are contained within dark, slightly elevated cards, often featuring subtle internal glow effects. Icons are usually outlined or filled, appearing crisp and often monocolor in white or a brand accent. Imagery serves primarily to explain product features or create a sense of atmospheric depth rather than decorative flourish. Density is balanced, with imagery typically occupying defined panels or sections, framed by surrounding UI.

## Layout

The page maintains a centered, contained layout with a maximum width, allowing content to breathe within the dark theme. The hero section features a full-bleed, gradient-infused background acting as a cosmic backdrop for a centered, bold headline and subtext. Vertical rhythm is established through consistent section gaps anchored by 60px. Content sections alternate between visually distinct panels, often employing two-column text-left/visual-right arrangements or multi-column card grids for features. The overall impression is structured and spacious, with a sticky top navigation bar providing global access points.

## Agent Prompt Guide

Quick Color Reference: 
text: #fbf1ff
background: #04061c
border: #292a4d
accent: #0067ff
primary action: #04061c (filled action)

Example Component Prompts:
1. Create a Primary Action Button: #04061c background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Design a Feature Card: '#0c0a2b' background, 1px solid '#292a4d' border, '24px' radius. Use Index 32px weight 600 headlines in '#fbf1ff' and Inter 16px weight 400 body text in '#9b9ba4'.
3. Build a Navigation Link: Inter 15px weight 400 text '#fbf1ff', '0px' background, '0px' border, and a hover state text color of '#9b9ba4'.

## Similar Brands

- **Linear** — Dark-themed productivity UI with precise typography, subtle borders, and emphasis on organized data presentation.
- **Superhuman** — Focus on high information density within a dark UI, minimal chrome, and fast interactions.
- **Vercel** — Developer tools aesthetic: dark mode, strong use of gradients, crisp and functional UI with a modern tech-forward feel.
- **Raycast** — Command-line interface aesthetic adapted for a modern application, featuring dark surfaces, subtle glows, and efficient interaction patterns.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-void-black: #02030b;
  --color-eclipse-gray: #04061c;
  --color-twilight-violet: #0c0a2b;
  --color-ash-slate: #11132b;
  --color-slate-blue: #152e58;
  --color-gunmetal-gray: #202333;
  --color-dark-star: #242444;
  --color-lunar-violet: #292a4d;
  --color-nebula-blue: #2c2b52;
  --color-graphite-border: #353545;
  --color-deep-iris: #404267;
  --color-steel-gray: #4f5160;
  --color-faded-gray: #9b9ba4;
  --color-light-ghost: #fbf1ff;
  --color-vibrant-blue: #0067ff;
  --color-electric-cyan: #02e5ef;
  --gradient-electric-cyan: linear-gradient(135deg, rgb(2, 229, 239) 0%, rgb(72, 89, 235) 71.5%, rgb(138, 56, 244) 100%);
  --color-plasma-pink: #512141;
  --color-crimson-bloom: #ff3a63;
  --color-galactic-rainbow: #665eff;
  --color-status-green: #22a06b;
  --color-warning-yellow: #ffff00;
  --color-golden-glow: #ffe684;

  /* Typography — Font Families */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-index: 'Index', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-apple-system: '-apple-system', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.5;
  --text-body-lg: 16px;
  --leading-body-lg: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.5;
  --tracking-subheading: 0.25px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.5;
  --text-heading: 32px;
  --leading-heading: 1.2;
  --tracking-heading: 0.19px;
  --text-heading-lg: 42px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: 0.21px;
  --text-display: 56px;
  --leading-display: 1.2;
  --tracking-display: 0.22px;

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
  --spacing-48: 48px;
  --spacing-60: 60px;
  --spacing-72: 72px;
  --spacing-200: 200px;

  /* Layout */
  --section-gap: 60px;
  --card-padding: 12px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-lg: 9px;
  --radius-xl: 12px;
  --radius-2xl: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 30px;
  --radius-3xl-3: 40px;
  --radius-full: 50px;

  /* Named Radii */
  --radius-lg: 20px;
  --radius-md: 12px;
  --radius-sm: 6px;
  --radius-xl: 24px;
  --radius-none: 0px;
  --radius-pill: 30px;
  --radius-round: 50px;

  /* Shadows */
  --shadow-sm: oklch(0.2 0 0 / 0.4) 1px 2px 6px 0px;
  --shadow-md: oklch(0 0 0 / 0.1) 1px 1px 10px 0px;
  --shadow-sm-2: oklch(0.89 0 0 / 0.18) 0px 1px 8px 0px;
  --shadow-xl: oklch(0.76 0.15 225.13 / 0.6) 0px 0px 70px 0px, oklch(0.52 0.28 280.29 / 0.11) 0px 0px 0px 26px, oklch(0.54 0.29 296.54 / 0.09) 0px 0px 0px 52px, oklch(0.62 0.27 308.71 / 0.1) 0px 0px 0px 80px;
  --shadow-subtle: rgb(225, 225, 225) 615px 66px 0px 0px, rgb(225, 225, 225) 459px 608px 0px 0px, rgb(225, 225, 225) 692px 688px 0px 0px, rgb(225, 225, 225) 687px 124px 0px 0px, rgb(225, 225, 225) 110px 403px 0px 0px, rgb(225, 225, 225) 88px 494px 0px 0px, rgb(225, 225, 225) 109px 329px 0px 0px, rgb(225, 225, 225) 462px 264px 0px 0px, rgb(225, 225, 225) 650px 584px 0px 0px, rgb(225, 225, 225) 45px 46px 0px 0px, rgb(225, 225, 225) 71px 73px 0px 0px, rgb(225, 225, 225) 457px 495px 0px 0px, rgb(225, 225, 225) 370px 568px 0px 0px, rgb(225, 225, 225) 605px 509px 0px 0px, rgb(225, 225, 225) 616px 573px 0px 0px, rgb(225, 225, 225) 484px 253px 0px 0px, rgb(225, 225, 225) 566px 203px 0px 0px, rgb(225, 225, 225) 544px 110px 0px 0px, rgb(225, 225, 225) 495px 268px 0px 0px, rgb(225, 225, 225) 648px 372px 0px 0px, rgb(225, 225, 225) 649px 285px 0px 0px, rgb(225, 225, 225) 487px 541px 0px 0px, rgb(225, 225, 225) 264px 151px 0px 0px, rgb(225, 225, 225) 105px 614px 0px 0px, rgb(225, 225, 225) 348px 169px 0px 0px, rgb(225, 225, 225) 528px 161px 0px 0px, rgb(225, 225, 225) 217px 538px 0px 0px, rgb(225, 225, 225) 421px 608px 0px 0px, rgb(225, 225, 225) 610px 425px 0px 0px, rgb(225, 225, 225) 366px 647px 0px 0px, rgb(225, 225, 225) 191px 602px 0px 0px, rgb(225, 225, 225) 343px 505px 0px 0px, rgb(225, 225, 225) 81px 478px 0px 0px, rgb(225, 225, 225) 159px 6px 0px 0px, rgb(225, 225, 225) 463px 311px 0px 0px, rgb(225, 225, 225) 529px 70px 0px 0px, rgb(225, 225, 225) 274px 445px 0px 0px, rgb(225, 225, 225) 681px 389px 0px 0px, rgb(225, 225, 225) 323px 47px 0px 0px, rgb(225, 225, 225) 13px 413px 0px 0px, rgb(225, 225, 225) 606px 449px 0px 0px, rgb(225, 225, 225) 629px 180px 0px 0px, rgb(225, 225, 225) 526px 335px 0px 0px, rgb(225, 225, 225) 445px 363px 0px 0px, rgb(225, 225, 225) 404px 91px 0px 0px, rgb(225, 225, 225) 216px 317px 0px 0px, rgb(225, 225, 225) 422px 140px 0px 0px, rgb(225, 225, 225) 10px 521px 0px 0px, rgb(225, 225, 225) 1px 475px 0px 0px, rgb(225, 225, 225) 102px 435px 0px 0px, rgb(225, 225, 225) 92px 382px 0px 0px, rgb(225, 225, 225) 326px 45px 0px 0px, rgb(225, 225, 225) 44px 404px 0px 0px, rgb(225, 225, 225) 142px 625px 0px 0px, rgb(225, 225, 225) 47px 630px 0px 0px, rgb(225, 225, 225) 24px 534px 0px 0px, rgb(225, 225, 225) 443px 207px 0px 0px, rgb(225, 225, 225) 657px 581px 0px 0px, rgb(225, 225, 225) 168px 645px 0px 0px, rgb(225, 225, 225) 491px 622px 0px 0px;
  --shadow-subtle-2: rgb(225, 225, 225) 435px 352px 0px 0px, rgb(225, 225, 225) 57px 465px 0px 0px, rgb(225, 225, 225) 331px 440px 0px 0px, rgb(225, 225, 225) 44px 615px 0px 0px, rgb(225, 225, 225) 151px 515px 0px 0px, rgb(225, 225, 225) 468px 627px 0px 0px, rgb(225, 225, 225) 472px 158px 0px 0px, rgb(225, 225, 225) 46px 206px 0px 0px, rgb(225, 225, 225) 610px 333px 0px 0px, rgb(225, 225, 225) 305px 595px 0px 0px, rgb(225, 225, 225) 524px 210px 0px 0px, rgb(225, 225, 225) 543px 661px 0px 0px, rgb(225, 225, 225) 136px 584px 0px 0px, rgb(225, 225, 225) 146px 162px 0px 0px, rgb(225, 225, 225) 61px 83px 0px 0px, rgb(225, 225, 225) 582px 236px 0px 0px, rgb(225, 225, 225) 671px 98px 0px 0px, rgb(225, 225, 225) 358px 280px 0px 0px, rgb(225, 225, 225) 444px 346px 0px 0px, rgb(225, 225, 225) 355px 288px 0px 0px, rgb(225, 225, 225) 587px 19px 0px 0px, rgb(225, 225, 225) 245px 80px 0px 0px, rgb(225, 225, 225) 438px 381px 0px 0px, rgb(225, 225, 225) 314px 20px 0px 0px, rgb(225, 225, 225) 151px 476px 0px 0px, rgb(225, 225, 225) 327px 470px 0px 0px, rgb(225, 225, 225) 379px 411px 0px 0px, rgb(225, 225, 225) 332px 575px 0px 0px, rgb(225, 225, 225) 132px 654px 0px 0px, rgb(225, 225, 225) 655px 71px 0px 0px, rgb(225, 225, 225) 402px 549px 0px 0px, rgb(225, 225, 225) 480px 316px 0px 0px, rgb(225, 225, 225) 215px 41px 0px 0px, rgb(225, 225, 225) 131px 94px 0px 0px, rgb(225, 225, 225) 95px 233px 0px 0px, rgb(225, 225, 225) 398px 281px 0px 0px, rgb(225, 225, 225) 54px 275px 0px 0px, rgb(225, 225, 225) 311px 686px 0px 0px, rgb(225, 225, 225) 29px 252px 0px 0px, rgb(225, 225, 225) 549px 277px 0px 0px, rgb(225, 225, 225) 665px 664px 0px 0px, rgb(225, 225, 225) 94px 240px 0px 0px, rgb(225, 225, 225) 243px 543px 0px 0px, rgb(225, 225, 225) 331px 197px 0px 0px, rgb(225, 225, 225) 478px 641px 0px 0px, rgb(225, 225, 225) 258px 68px 0px 0px, rgb(225, 225, 225) 311px 371px 0px 0px, rgb(225, 225, 225) 664px 83px 0px 0px, rgb(225, 225, 225) 692px 626px 0px 0px, rgb(225, 225, 225) 405px 195px 0px 0px, rgb(225, 225, 225) 401px 289px 0px 0px, rgb(225, 225, 225) 284px 94px 0px 0px, rgb(225, 225, 225) 617px 309px 0px 0px, rgb(225, 225, 225) 214px 393px 0px 0px, rgb(225, 225, 225) 571px 196px 0px 0px, rgb(225, 225, 225) 404px 439px 0px 0px, rgb(225, 225, 225) 522px 130px 0px 0px, rgb(225, 225, 225) 144px 535px 0px 0px, rgb(225, 225, 225) 604px 496px 0px 0px, rgb(225, 225, 225) 625px 321px 0px 0px;
  --shadow-subtle-3: rgb(225, 225, 225) 219px 422px 0px 0px, rgb(225, 225, 225) 582px 623px 0px 0px, rgb(225, 225, 225) 223px 497px 0px 0px, rgb(225, 225, 225) 681px 529px 0px 0px, rgb(225, 225, 225) 217px 312px 0px 0px, rgb(225, 225, 225) 690px 135px 0px 0px, rgb(225, 225, 225) 30px 338px 0px 0px, rgb(225, 225, 225) 409px 448px 0px 0px, rgb(225, 225, 225) 169px 159px 0px 0px, rgb(225, 225, 225) 347px 120px 0px 0px, rgb(225, 225, 225) 134px 56px 0px 0px, rgb(225, 225, 225) 574px 250px 0px 0px, rgb(225, 225, 225) 369px 662px 0px 0px, rgb(225, 225, 225) 527px 663px 0px 0px, rgb(225, 225, 225) 570px 490px 0px 0px, rgb(225, 225, 225) 506px 370px 0px 0px, rgb(225, 225, 225) 496px 484px 0px 0px, rgb(225, 225, 225) 5px 86px 0px 0px, rgb(225, 225, 225) 435px 584px 0px 0px, rgb(225, 225, 225) 600px 652px 0px 0px, rgb(225, 225, 225) 128px 554px 0px 0px, rgb(225, 225, 225) 413px 539px 0px 0px, rgb(225, 225, 225) 202px 101px 0px 0px, rgb(225, 225, 225) 301px 572px 0px 0px, rgb(225, 225, 225) 10px 591px 0px 0px, rgb(225, 225, 225) 331px 392px 0px 0px, rgb(225, 225, 225) 317px 393px 0px 0px, rgb(225, 225, 225) 170px 81px 0px 0px, rgb(225, 225, 225) 366px 414px 0px 0px, rgb(225, 225, 225) 228px 316px 0px 0px, rgb(225, 225, 225) 464px 343px 0px 0px, rgb(225, 225, 225) 527px 232px 0px 0px, rgb(225, 225, 225) 311px 646px 0px 0px, rgb(225, 225, 225) 242px 440px 0px 0px, rgb(225, 225, 225) 121px 136px 0px 0px, rgb(225, 225, 225) 120px 591px 0px 0px, rgb(225, 225, 225) 197px 158px 0px 0px, rgb(225, 225, 225) 299px 138px 0px 0px, rgb(225, 225, 225) 429px 262px 0px 0px, rgb(225, 225, 225) 520px 552px 0px 0px, rgb(225, 225, 225) 39px 228px 0px 0px, rgb(225, 225, 225) 48px 315px 0px 0px, rgb(225, 225, 225) 127px 296px 0px 0px, rgb(225, 225, 225) 154px 265px 0px 0px, rgb(225, 225, 225) 75px 353px 0px 0px, rgb(225, 225, 225) 268px 225px 0px 0px, rgb(225, 225, 225) 25px 214px 0px 0px, rgb(225, 225, 225) 34px 656px 0px 0px, rgb(225, 225, 225) 212px 179px 0px 0px, rgb(225, 225, 225) 294px 185px 0px 0px, rgb(225, 225, 225) 106px 448px 0px 0px, rgb(225, 225, 225) 653px 130px 0px 0px, rgb(225, 225, 225) 251px 4px 0px 0px, rgb(225, 225, 225) 458px 676px 0px 0px, rgb(225, 225, 225) 417px 150px 0px 0px, rgb(225, 225, 225) 297px 367px 0px 0px, rgb(225, 225, 225) 54px 118px 0px 0px, rgb(225, 225, 225) 608px 293px 0px 0px, rgb(225, 225, 225) 136px 107px 0px 0px, rgb(225, 225, 225) 492px 212px 0px 0px;
  --shadow-xl-2: rgba(0, 0, 0, 0.4) 0px 4px 40px 8px, rgba(0, 0, 0, 0.8) 0px 0px 0px 0.5px, rgba(255, 255, 255, 0.3) 0px 0.5px 0px 0px inset;

  /* Surfaces */
  --surface-eclipse-gray-canvas: #04061c;
  --surface-twilight-violet-surface: #0c0a2b;
  --surface-deep-space-panel: #02030b;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-void-black: #02030b;
  --color-eclipse-gray: #04061c;
  --color-twilight-violet: #0c0a2b;
  --color-ash-slate: #11132b;
  --color-slate-blue: #152e58;
  --color-gunmetal-gray: #202333;
  --color-dark-star: #242444;
  --color-lunar-violet: #292a4d;
  --color-nebula-blue: #2c2b52;
  --color-graphite-border: #353545;
  --color-deep-iris: #404267;
  --color-steel-gray: #4f5160;
  --color-faded-gray: #9b9ba4;
  --color-light-ghost: #fbf1ff;
  --color-vibrant-blue: #0067ff;
  --color-electric-cyan: #02e5ef;
  --color-plasma-pink: #512141;
  --color-crimson-bloom: #ff3a63;
  --color-galactic-rainbow: #665eff;
  --color-status-green: #22a06b;
  --color-warning-yellow: #ffff00;
  --color-golden-glow: #ffe684;

  /* Typography */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-index: 'Index', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-apple-system: '-apple-system', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.5;
  --text-body-lg: 16px;
  --leading-body-lg: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.5;
  --tracking-subheading: 0.25px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.5;
  --text-heading: 32px;
  --leading-heading: 1.2;
  --tracking-heading: 0.19px;
  --text-heading-lg: 42px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: 0.21px;
  --text-display: 56px;
  --leading-display: 1.2;
  --tracking-display: 0.22px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-48: 48px;
  --spacing-60: 60px;
  --spacing-72: 72px;
  --spacing-200: 200px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-lg: 9px;
  --radius-xl: 12px;
  --radius-2xl: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 30px;
  --radius-3xl-3: 40px;
  --radius-full: 50px;

  /* Shadows */
  --shadow-sm: oklch(0.2 0 0 / 0.4) 1px 2px 6px 0px;
  --shadow-md: oklch(0 0 0 / 0.1) 1px 1px 10px 0px;
  --shadow-sm-2: oklch(0.89 0 0 / 0.18) 0px 1px 8px 0px;
  --shadow-xl: oklch(0.76 0.15 225.13 / 0.6) 0px 0px 70px 0px, oklch(0.52 0.28 280.29 / 0.11) 0px 0px 0px 26px, oklch(0.54 0.29 296.54 / 0.09) 0px 0px 0px 52px, oklch(0.62 0.27 308.71 / 0.1) 0px 0px 0px 80px;
  --shadow-subtle: rgb(225, 225, 225) 615px 66px 0px 0px, rgb(225, 225, 225) 459px 608px 0px 0px, rgb(225, 225, 225) 692px 688px 0px 0px, rgb(225, 225, 225) 687px 124px 0px 0px, rgb(225, 225, 225) 110px 403px 0px 0px, rgb(225, 225, 225) 88px 494px 0px 0px, rgb(225, 225, 225) 109px 329px 0px 0px, rgb(225, 225, 225) 462px 264px 0px 0px, rgb(225, 225, 225) 650px 584px 0px 0px, rgb(225, 225, 225) 45px 46px 0px 0px, rgb(225, 225, 225) 71px 73px 0px 0px, rgb(225, 225, 225) 457px 495px 0px 0px, rgb(225, 225, 225) 370px 568px 0px 0px, rgb(225, 225, 225) 605px 509px 0px 0px, rgb(225, 225, 225) 616px 573px 0px 0px, rgb(225, 225, 225) 484px 253px 0px 0px, rgb(225, 225, 225) 566px 203px 0px 0px, rgb(225, 225, 225) 544px 110px 0px 0px, rgb(225, 225, 225) 495px 268px 0px 0px, rgb(225, 225, 225) 648px 372px 0px 0px, rgb(225, 225, 225) 649px 285px 0px 0px, rgb(225, 225, 225) 487px 541px 0px 0px, rgb(225, 225, 225) 264px 151px 0px 0px, rgb(225, 225, 225) 105px 614px 0px 0px, rgb(225, 225, 225) 348px 169px 0px 0px, rgb(225, 225, 225) 528px 161px 0px 0px, rgb(225, 225, 225) 217px 538px 0px 0px, rgb(225, 225, 225) 421px 608px 0px 0px, rgb(225, 225, 225) 610px 425px 0px 0px, rgb(225, 225, 225) 366px 647px 0px 0px, rgb(225, 225, 225) 191px 602px 0px 0px, rgb(225, 225, 225) 343px 505px 0px 0px, rgb(225, 225, 225) 81px 478px 0px 0px, rgb(225, 225, 225) 159px 6px 0px 0px, rgb(225, 225, 225) 463px 311px 0px 0px, rgb(225, 225, 225) 529px 70px 0px 0px, rgb(225, 225, 225) 274px 445px 0px 0px, rgb(225, 225, 225) 681px 389px 0px 0px, rgb(225, 225, 225) 323px 47px 0px 0px, rgb(225, 225, 225) 13px 413px 0px 0px, rgb(225, 225, 225) 606px 449px 0px 0px, rgb(225, 225, 225) 629px 180px 0px 0px, rgb(225, 225, 225) 526px 335px 0px 0px, rgb(225, 225, 225) 445px 363px 0px 0px, rgb(225, 225, 225) 404px 91px 0px 0px, rgb(225, 225, 225) 216px 317px 0px 0px, rgb(225, 225, 225) 422px 140px 0px 0px, rgb(225, 225, 225) 10px 521px 0px 0px, rgb(225, 225, 225) 1px 475px 0px 0px, rgb(225, 225, 225) 102px 435px 0px 0px, rgb(225, 225, 225) 92px 382px 0px 0px, rgb(225, 225, 225) 326px 45px 0px 0px, rgb(225, 225, 225) 44px 404px 0px 0px, rgb(225, 225, 225) 142px 625px 0px 0px, rgb(225, 225, 225) 47px 630px 0px 0px, rgb(225, 225, 225) 24px 534px 0px 0px, rgb(225, 225, 225) 443px 207px 0px 0px, rgb(225, 225, 225) 657px 581px 0px 0px, rgb(225, 225, 225) 168px 645px 0px 0px, rgb(225, 225, 225) 491px 622px 0px 0px;
  --shadow-subtle-2: rgb(225, 225, 225) 435px 352px 0px 0px, rgb(225, 225, 225) 57px 465px 0px 0px, rgb(225, 225, 225) 331px 440px 0px 0px, rgb(225, 225, 225) 44px 615px 0px 0px, rgb(225, 225, 225) 151px 515px 0px 0px, rgb(225, 225, 225) 468px 627px 0px 0px, rgb(225, 225, 225) 472px 158px 0px 0px, rgb(225, 225, 225) 46px 206px 0px 0px, rgb(225, 225, 225) 610px 333px 0px 0px, rgb(225, 225, 225) 305px 595px 0px 0px, rgb(225, 225, 225) 524px 210px 0px 0px, rgb(225, 225, 225) 543px 661px 0px 0px, rgb(225, 225, 225) 136px 584px 0px 0px, rgb(225, 225, 225) 146px 162px 0px 0px, rgb(225, 225, 225) 61px 83px 0px 0px, rgb(225, 225, 225) 582px 236px 0px 0px, rgb(225, 225, 225) 671px 98px 0px 0px, rgb(225, 225, 225) 358px 280px 0px 0px, rgb(225, 225, 225) 444px 346px 0px 0px, rgb(225, 225, 225) 355px 288px 0px 0px, rgb(225, 225, 225) 587px 19px 0px 0px, rgb(225, 225, 225) 245px 80px 0px 0px, rgb(225, 225, 225) 438px 381px 0px 0px, rgb(225, 225, 225) 314px 20px 0px 0px, rgb(225, 225, 225) 151px 476px 0px 0px, rgb(225, 225, 225) 327px 470px 0px 0px, rgb(225, 225, 225) 379px 411px 0px 0px, rgb(225, 225, 225) 332px 575px 0px 0px, rgb(225, 225, 225) 132px 654px 0px 0px, rgb(225, 225, 225) 655px 71px 0px 0px, rgb(225, 225, 225) 402px 549px 0px 0px, rgb(225, 225, 225) 480px 316px 0px 0px, rgb(225, 225, 225) 215px 41px 0px 0px, rgb(225, 225, 225) 131px 94px 0px 0px, rgb(225, 225, 225) 95px 233px 0px 0px, rgb(225, 225, 225) 398px 281px 0px 0px, rgb(225, 225, 225) 54px 275px 0px 0px, rgb(225, 225, 225) 311px 686px 0px 0px, rgb(225, 225, 225) 29px 252px 0px 0px, rgb(225, 225, 225) 549px 277px 0px 0px, rgb(225, 225, 225) 665px 664px 0px 0px, rgb(225, 225, 225) 94px 240px 0px 0px, rgb(225, 225, 225) 243px 543px 0px 0px, rgb(225, 225, 225) 331px 197px 0px 0px, rgb(225, 225, 225) 478px 641px 0px 0px, rgb(225, 225, 225) 258px 68px 0px 0px, rgb(225, 225, 225) 311px 371px 0px 0px, rgb(225, 225, 225) 664px 83px 0px 0px, rgb(225, 225, 225) 692px 626px 0px 0px, rgb(225, 225, 225) 405px 195px 0px 0px, rgb(225, 225, 225) 401px 289px 0px 0px, rgb(225, 225, 225) 284px 94px 0px 0px, rgb(225, 225, 225) 617px 309px 0px 0px, rgb(225, 225, 225) 214px 393px 0px 0px, rgb(225, 225, 225) 571px 196px 0px 0px, rgb(225, 225, 225) 404px 439px 0px 0px, rgb(225, 225, 225) 522px 130px 0px 0px, rgb(225, 225, 225) 144px 535px 0px 0px, rgb(225, 225, 225) 604px 496px 0px 0px, rgb(225, 225, 225) 625px 321px 0px 0px;
  --shadow-subtle-3: rgb(225, 225, 225) 219px 422px 0px 0px, rgb(225, 225, 225) 582px 623px 0px 0px, rgb(225, 225, 225) 223px 497px 0px 0px, rgb(225, 225, 225) 681px 529px 0px 0px, rgb(225, 225, 225) 217px 312px 0px 0px, rgb(225, 225, 225) 690px 135px 0px 0px, rgb(225, 225, 225) 30px 338px 0px 0px, rgb(225, 225, 225) 409px 448px 0px 0px, rgb(225, 225, 225) 169px 159px 0px 0px, rgb(225, 225, 225) 347px 120px 0px 0px, rgb(225, 225, 225) 134px 56px 0px 0px, rgb(225, 225, 225) 574px 250px 0px 0px, rgb(225, 225, 225) 369px 662px 0px 0px, rgb(225, 225, 225) 527px 663px 0px 0px, rgb(225, 225, 225) 570px 490px 0px 0px, rgb(225, 225, 225) 506px 370px 0px 0px, rgb(225, 225, 225) 496px 484px 0px 0px, rgb(225, 225, 225) 5px 86px 0px 0px, rgb(225, 225, 225) 435px 584px 0px 0px, rgb(225, 225, 225) 600px 652px 0px 0px, rgb(225, 225, 225) 128px 554px 0px 0px, rgb(225, 225, 225) 413px 539px 0px 0px, rgb(225, 225, 225) 202px 101px 0px 0px, rgb(225, 225, 225) 301px 572px 0px 0px, rgb(225, 225, 225) 10px 591px 0px 0px, rgb(225, 225, 225) 331px 392px 0px 0px, rgb(225, 225, 225) 317px 393px 0px 0px, rgb(225, 225, 225) 170px 81px 0px 0px, rgb(225, 225, 225) 366px 414px 0px 0px, rgb(225, 225, 225) 228px 316px 0px 0px, rgb(225, 225, 225) 464px 343px 0px 0px, rgb(225, 225, 225) 527px 232px 0px 0px, rgb(225, 225, 225) 311px 646px 0px 0px, rgb(225, 225, 225) 242px 440px 0px 0px, rgb(225, 225, 225) 121px 136px 0px 0px, rgb(225, 225, 225) 120px 591px 0px 0px, rgb(225, 225, 225) 197px 158px 0px 0px, rgb(225, 225, 225) 299px 138px 0px 0px, rgb(225, 225, 225) 429px 262px 0px 0px, rgb(225, 225, 225) 520px 552px 0px 0px, rgb(225, 225, 225) 39px 228px 0px 0px, rgb(225, 225, 225) 48px 315px 0px 0px, rgb(225, 225, 225) 127px 296px 0px 0px, rgb(225, 225, 225) 154px 265px 0px 0px, rgb(225, 225, 225) 75px 353px 0px 0px, rgb(225, 225, 225) 268px 225px 0px 0px, rgb(225, 225, 225) 25px 214px 0px 0px, rgb(225, 225, 225) 34px 656px 0px 0px, rgb(225, 225, 225) 212px 179px 0px 0px, rgb(225, 225, 225) 294px 185px 0px 0px, rgb(225, 225, 225) 106px 448px 0px 0px, rgb(225, 225, 225) 653px 130px 0px 0px, rgb(225, 225, 225) 251px 4px 0px 0px, rgb(225, 225, 225) 458px 676px 0px 0px, rgb(225, 225, 225) 417px 150px 0px 0px, rgb(225, 225, 225) 297px 367px 0px 0px, rgb(225, 225, 225) 54px 118px 0px 0px, rgb(225, 225, 225) 608px 293px 0px 0px, rgb(225, 225, 225) 136px 107px 0px 0px, rgb(225, 225, 225) 492px 212px 0px 0px;
  --shadow-xl-2: rgba(0, 0, 0, 0.4) 0px 4px 40px 8px, rgba(0, 0, 0, 0.8) 0px 0px 0px 0.5px, rgba(255, 255, 255, 0.3) 0px 0.5px 0px 0px inset;
}
```

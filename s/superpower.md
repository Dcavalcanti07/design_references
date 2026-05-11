# Superpower — Style Reference
> Clinical precision, vibrant pulse. A highly legible monochrome foundation with a single, sharp burst of color highlighting interaction.

**Theme:** light

Superpower's health intelligence brand is built on a high-contrast palette of an almost-black charcoal and stark white, punctuated by a vivid, energetic vermillion. Monochromatic typography by NB International Pro, paired with generous letter-spacing, projects a precise, almost clinical authority, while pill-shaped buttons introduce a surprising soft, approachable counterpoint. This creates a refined yet dynamic aesthetic, balancing technical exactitude with user-friendly optimism.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Charcoal Black | `#18181b` | `--color-charcoal-black` | Primary text, darkest backgrounds, borders, navigation text — defines the core, stark contrast against white surfaces. |
| Pure White | `#ffffff` | `--color-pure-white` | Page backgrounds, card surfaces, button text — the dominant canvas for content, providing maximum contrast for Charcoal Black text. |
| Warm Gray | `#71717a` | `--color-warm-gray` | Secondary text, subtle borders, subheadings — softens the contrast for less critical information, maintaining legibility. |
| Light Gray | `#e4e4e7` | `--color-light-gray` | Tertiary backgrounds, hairline borders, subtle dividers — provides visual separation without introducing strong color. |
| Whisper Gray | `#f4f4f5` | `--color-whisper-gray` | Subtle background shading, hover states for light elements — provides a very slight visual lift from Pure White. |
| Vermillion Accent | `#fc5f2b` | `--color-vermillion-accent` | Primary calls to action, active navigation items, key highlight elements — directs user attention with high-energy contrast against neutral backgrounds. |
| Sunset Gradient | `linear-gradient(88deg, rgb(252, 95, 43), rgb(255, 139, 100) 90%, rgb(255, 255, 255))` | `--color-sunset-gradient` | Decorative element on membership card, provides a dynamic visual flourish — a warm, vibrant gradient that avoids direct action but conveys energy. |
| Soft Vermillion | `#feaf95` | `--color-soft-vermillion` | Subtle shadow tint for cards, giving a warm glow to elevated elements. |
| Canary Yellow | `#ffdd61` | `--color-canary-yellow` | Background for specific informational elements, likely semantic success or highlight. |
| Sky Blue | `#42a5f5` | `--color-sky-blue` | Iconography, non-interactive graphical elements — a secondary accent color that adds visual interest without competing with Vermillion Accent. |

## Tokens — Typography

### Nb international pro webfont — Primary typeface for all content. Weight 700 is reserved for headlines and emphasized elements, conveying directness. Weight 400 for body text and navigation. Distinctive tight letter-spacing for headlines contributes to a crisp, precise feel, loosening for body text to maintain comfort. · `--font-nb-international-pro-webfont`
- **Substitute:** Inter
- **Weights:** 400, 700
- **Sizes:** 11px, 13px, 15px, 17px, 19px, 22px, 26px, 30px, 37px, 45px, 56px, 60px, 66px
- **Line height:** 1.00, 1.06, 1.10, 1.13, 1.20, 1.25, 1.40, 1.50
- **Letter spacing:** -0.132, -0.169, -0.225, -0.255, -0.266, -0.308, -0.338, -0.36, -0.37, -0.36, -0.336, -0.3, -0.33
- **Role:** Primary typeface for all content. Weight 700 is reserved for headlines and emphasized elements, conveying directness. Weight 400 for body text and navigation. Distinctive tight letter-spacing for headlines contributes to a crisp, precise feel, loosening for body text to maintain comfort.

### Nb International mono pro — Used for specific functional text, like footnotes or small labels, where a fixed-width character set is desired for technical precision. · `--font-nb-international-mono-pro`
- **Substitute:** Space Mono
- **Weights:** 400
- **Sizes:** 11px, 13px
- **Line height:** 1.40, 1.50
- **Letter spacing:** -0.066, -0.078
- **Role:** Used for specific functional text, like footnotes or small labels, where a fixed-width character set is desired for technical precision.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 11px | 1.5 | -0.132px | `--text-caption` |
| body | 15px | 1.5 | -0.225px | `--text-body` |
| subheading | 19px | 1.4 | -0.266px | `--text-subheading` |
| heading-sm | 22px | 1.4 | -0.308px | `--text-heading-sm` |
| heading | 37px | 1.25 | -0.37px | `--text-heading` |
| heading-lg | 45px | 1.2 | -0.36px | `--text-heading-lg` |
| display | 60px | 1.06 | -0.3px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 8 | 8px | `--spacing-8` |
| 16 | 16px | `--spacing-16` |
| 24 | 24px | `--spacing-24` |
| 28 | 28px | `--spacing-28` |
| 60 | 60px | `--spacing-60` |

### Border Radius

| Element | Value |
|---------|-------|
| misc | 29.9832px |
| cards | 16px |
| inputs | 11.2437px |
| buttons | 9999px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(0, 0, 0, 0.05) 0px 2px 2px 0px` | `--shadow-subtle` |

### Layout

- **Section gap:** 64-96px
- **Element gap:** 4px

## Components

### Primary Call to Action Button
**Role:** Button

Rounded pill shape with Vermillion Accent background (#fc5f2b) and Pure White text (#ffffff). Prominent padding: 15px vertical, 22px horizontal. Ensures primary user actions are highly visible and inviting.

### Secondary Outline Button
**Role:** Button

Pill shape with Pure White background (#ffffff), Charcoal Black text (#18181b), and a Light Gray border (#e4e4e7). Padding is 15px vertical, 19px horizontal. Provides an alternative action without competing with the primary CTA.

### Ghost Button (Dark Background)
**Role:** Button

Pill shape, transparent background (rgba(0,0,0,0.25)), Charcoal Black text (#18181b), no border. Used for tertiary actions or within dark hero sections to provide interaction without strong visual emphasis. Minimal padding due to its transparency.

### Ghost Button (Light Background)
**Role:** Button

Rectangular with rounded corners (11px radius), Whisper Gray background (#fafafa), Charcoal Black text (#18181b). Used for lower-priority actions or filters, blending into the background. Padding is 15px square.

### Default Card
**Role:** Card

Pure White background (#ffffff), 16px border-radius, subtle shadow (rgba(0, 0, 0, 0.05) 0px 2px 2px 0px). Padding: 26px top, 19px horizontal, 19px bottom. Used for content grouping on light backgrounds, providing slight elevation.

### Membership Detail Card
**Role:** Card

Transparent background, 22px border-radius, no shadow, with 19px padding. Used for specific content sections that need a softer visual separation, often containing images or distinct content blocks.

### Image Wrapper Card
**Role:** Card

Transparent background, 5px border-radius, no shadow. Minimum 11px horizontal padding. Used to contain images or media with a slight border-radius, allowing content to dictate visual boundaries.

### Section Navigation Link
**Role:** Navigation

Charcoal Black text (#18181b), 9999px border-radius, transparent background. Used in the main navigation, interactive on hover or click to subtly indicate its function.

### Floating Chat Widget Trigger
**Role:** Button

Square button with 16px radius, Charcoal Black background (#18181B) and Pure White 'S' icon. Positioned fixed at the bottom right, it provides persistent access to support.

## Do's and Don'ts

### Do
- Use Charcoal Black (#18181b) for all primary typographic elements and major UI components to maintain high contrast and sophistication.
- Apply Vermillion Accent (#fc5f2b) exclusively to primary calls-to-action and active navigation states to ensure focus and energy.
- Employ the Nb international pro webfont with significant negative letter-spacing for all headlines (e.g., -0.37px at 37px) to achieve a precise, condensed appearance.
- Maintain a clear visual hierarchy by differentiating primary (pill-shaped Vermillion Accent), secondary (white outlined), and tertiary (ghost, transparent) button styles.
- Ensure all interactive elements, particularly buttons, feature a 9999px border-radius for the distinctive pill shape, softening the otherwise crisp UI.
- Use Pure White (#ffffff) as the dominant page background to create an expansive, clean canvas for content presentation.
- Utilize a subtle shadow (rgba(0, 0, 0, 0.05) 0px 2px 2px 0px) for elevated cards on main content areas to provide soft depth.

### Don't
- Do not use multiple accent colors simultaneously; the visual system relies on Vermillion Accent (#fc5f2b) for primary emphasis.
- Avoid using flat, square buttons; all primary and secondary buttons must adhere to the 9999px pill-shaped radius.
- Do not introduce strong, chromatic backgrounds other than the defined brand colors; the system heavily relies on a neutral gray progression.
- Refrain from using thin, decorative borders that are not part of the established Light Gray (#e4e4e7) or Charcoal Black (#18181b) border palette.
- Do not vary line-height significantly from the established scale; maintaining the precise vertical rhythm is key for legibility and visual consistency.
- Avoid generic drop shadows; use the specific, subtle card shadow (rgba(0, 0, 0, 0.05) 0px 2px 2px 0px) to maintain a light, clean aesthetic.

## Elevation

- **Default Card:** `rgba(0, 0, 0, 0.05) 0px 2px 2px 0px`

## Imagery

The visual language relies heavily on evocative, full-bleed photography, often featuring individuals with determined expressions, implicitly connected to health and vitality. Images typically use shallow depth of field and dramatic lighting (often dark, moody with subtle blue/orange tones) to create an aspirational, slightly mysterious atmosphere. This is offset by clean, tight product shots of membership cards, often with an abstract, organic pattern and rendered with gradients, grounding the aspirational mood in tangible product. Icons are monochromatic, simple, and functional, primarily in Charcoal Black or Pure White, serving a supportive explanatory role.

## Layout

The site employs a max-width contained layout rather than full-bleed for most content, centered on the screen. The initial hero section is a full-bleed dark photographic background with centered, large white typography, creating an immediate, impactful statement. Subsequent sections primarily feature a clean white background, with content often arranged in two-column layouts (text left, image right, or vice versa), maintaining consistent vertical spacing between sections. Content blocks are visually distinct, often using the defined card styles to group information. A sticky top navigation bar provides consistent access, and a fixed chat widget trigger anchors the bottom right.

## Agent Prompt Guide

Quick Color Reference:
- Text (primary): #18181b
- Background (page): #ffffff
- CTA (Vermillion Accent): #fc5f2b
- Border (light): #e4e4e7
- Secondary Text: #71717a

Example Component Prompts:
1. Create a Primary CTA Button: background #fc5f2b, text #ffffff, border-radius 9999px, padding 14.9916px 22.4874px, text 'Join Today' using Nb international pro webfont weight 700, 17px size, 1.4 line-height, -0.255px letter-spacing.
2. Design a Default Card: background #ffffff, border-radius 16px, box-shadow rgba(0, 0, 0, 0.05) 0px 2px 2px 0px, padding 26.2353px 18.7395px, containing a headline 'Membership' (Nb international pro webfont weight 700, 30px size, #18181b) and body text (Nb international pro webfont weight 400, 15px size, #18181b).
3. Generate a Secondary Outline Button: background #ffffff, text #18181b, border #e4e4e7, border-radius 9999px, padding 14.9916px 18.7395px, text 'Learn More' using Nb international pro webfont weight 400, 15px size, 1.4 line-height, -0.225px letter-spacing.
4. Produce a Hero Section headline: 'Unlock your new health intelligence' using Nb international pro webfont weight 700, 60px size, #ffffff, 1.06 line-height, and -0.3px letter-spacing, centered over a dark photographic background.

## Similar Brands

- **Eight Sleep** — Both use a primary dark background with a single bright accent color (orange/red) for CTAs and highlights, creating a high-energy, aspirational tech aesthetic.
- **WHOOP** — Features clean, high-contrast typography and a restrained color palette, focusing on data and precision in health tech, similar to Superpower's functional elegance.
- **Levels Health** — Employs a stark white background with strong, legible typography and targeted use of a single brand accent color, conveying a precise, clinical, yet approachable health technology brand.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-charcoal-black: #18181b;
  --color-pure-white: #ffffff;
  --color-warm-gray: #71717a;
  --color-light-gray: #e4e4e7;
  --color-whisper-gray: #f4f4f5;
  --color-vermillion-accent: #fc5f2b;
  --color-sunset-gradient: #fc5f2b;
  --gradient-sunset-gradient: linear-gradient(88deg, rgb(252, 95, 43), rgb(255, 139, 100) 90%, rgb(255, 255, 255));
  --color-soft-vermillion: #feaf95;
  --color-canary-yellow: #ffdd61;
  --color-sky-blue: #42a5f5;

  /* Typography — Font Families */
  --font-nb-international-pro-webfont: 'Nb international pro webfont', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-nb-international-mono-pro: 'Nb International mono pro', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.5;
  --tracking-caption: -0.132px;
  --text-body: 15px;
  --leading-body: 1.5;
  --tracking-body: -0.225px;
  --text-subheading: 19px;
  --leading-subheading: 1.4;
  --tracking-subheading: -0.266px;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1.4;
  --tracking-heading-sm: -0.308px;
  --text-heading: 37px;
  --leading-heading: 1.25;
  --tracking-heading: -0.37px;
  --text-heading-lg: 45px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -0.36px;
  --text-display: 60px;
  --leading-display: 1.06;
  --tracking-display: -0.3px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-60: 60px;

  /* Layout */
  --section-gap: 64-96px;
  --element-gap: 4px;

  /* Border Radius */
  --radius-md: 5px;
  --radius-lg: 7.4958px;
  --radius-xl: 11.2437px;
  --radius-xl-2: 14.9916px;
  --radius-2xl: 22.4874px;
  --radius-3xl: 29.9832px;
  --radius-full: 74.958px;
  --radius-full-2: 100px;
  --radius-full-3: 149.916px;
  --radius-full-4: 999px;
  --radius-full-5: 1440px;
  --radius-full-6: 9999px;

  /* Named Radii */
  --radius-misc: 29.9832px;
  --radius-cards: 16px;
  --radius-inputs: 11.2437px;
  --radius-buttons: 9999px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.05) 0px 2px 2px 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-charcoal-black: #18181b;
  --color-pure-white: #ffffff;
  --color-warm-gray: #71717a;
  --color-light-gray: #e4e4e7;
  --color-whisper-gray: #f4f4f5;
  --color-vermillion-accent: #fc5f2b;
  --color-sunset-gradient: #fc5f2b;
  --color-soft-vermillion: #feaf95;
  --color-canary-yellow: #ffdd61;
  --color-sky-blue: #42a5f5;

  /* Typography */
  --font-nb-international-pro-webfont: 'Nb international pro webfont', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-nb-international-mono-pro: 'Nb International mono pro', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.5;
  --tracking-caption: -0.132px;
  --text-body: 15px;
  --leading-body: 1.5;
  --tracking-body: -0.225px;
  --text-subheading: 19px;
  --leading-subheading: 1.4;
  --tracking-subheading: -0.266px;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1.4;
  --tracking-heading-sm: -0.308px;
  --text-heading: 37px;
  --leading-heading: 1.25;
  --tracking-heading: -0.37px;
  --text-heading-lg: 45px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -0.36px;
  --text-display: 60px;
  --leading-display: 1.06;
  --tracking-display: -0.3px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-60: 60px;

  /* Border Radius */
  --radius-md: 5px;
  --radius-lg: 7.4958px;
  --radius-xl: 11.2437px;
  --radius-xl-2: 14.9916px;
  --radius-2xl: 22.4874px;
  --radius-3xl: 29.9832px;
  --radius-full: 74.958px;
  --radius-full-2: 100px;
  --radius-full-3: 149.916px;
  --radius-full-4: 999px;
  --radius-full-5: 1440px;
  --radius-full-6: 9999px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.05) 0px 2px 2px 0px;
}
```

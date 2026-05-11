# Suno — Style Reference
> Dark studio, neon pulses. An expansive, dim canvas where vibrant light flickers to life.

**Theme:** dark

Suno's design evokes a dark, pulsating club atmosphere, where digital magic happens. The expansive, low-contrast color palette, punctuated by fleeting, vivid neon accents, creates a sense of cutting-edge technology merging with artistic expression. Subtle dark gradients on backgrounds and elevated elements add depth without sharp divisions. White, bold typography against these dark canvases commands attention, establishing a stage for creative output.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Pitch Black | `#101012` | `--color-pitch-black` | Page backgrounds, deeply recessed surfaces, primary text on light elements. |
| Void Black | `#17171a` | `--color-void-black` | Subtle background for card elevations or grouped content, creating hierarchy within dark surfaces. |
| Ghost White | `#f7f4ef` | `--color-ghost-white` | Primary text color for headlines and body copy on dark backgrounds, selected interactive elements. |
| Pure White | `#ffffff` | `--color-pure-white` | Strongest contrast for key headings, input text, and active states, providing distinct visual pop. |
| Graphite | `#000000` | `--color-graphite` | Text on light backgrounds (e.g. 'Sign Up' button), icon fills. |
| Ash Gray | `#c2c2c1` | `--color-ash-gray` | Minor background tint or subtle borders. |
| Muted Steel | `#a3a3a3` | `--color-muted-steel` | Subtle icons and secondary UI elements, creating a desaturated feel to non-critical information. |
| Sunset Yellow | `#f5d907` | `--color-sunset-yellow` | Icons and occasional decorative elements, appearing as a point of visual interest against the dark theme. |
| Vivid Pink | `#fd429c` | `--color-vivid-pink` | Used sparingly for interactive elements, such as the 'Create' button, indicating primary action with an energetic glow. |
| Electric Green | `#02d95c` | `--color-electric-green` | Small interactive elements like icons or indicators, signaling status or a secondary action without overwhelming the primary palette. |

## Tokens — Typography

### Neue Montreal — Primary typeface for all UI elements, headings, body text. Its modern, sans-serif structure holds legibility across a wide range of sizes and weights, supporting both robust headlines and subtle metadata. Tightly tracked at large sizes for a contemporary feel. · `--font-neue-montreal`
- **Substitute:** Inter
- **Weights:** 300, 400, 500
- **Sizes:** 10px, 11px, 12px, 13px, 14px, 15px, 16px, 17px, 18px, 20px, 24px, 40px, 72px, 140px
- **Line height:** 0.87, 0.89, 1.00, 1.14, 1.20, 1.27, 1.33, 1.40, 1.41, 1.43, 1.50, 1.55, 1.60, 1.63, 1.78
- **Letter spacing:** -0.0260em at display sizes, to 0.0000em at body sizes
- **Role:** Primary typeface for all UI elements, headings, body text. Its modern, sans-serif structure holds legibility across a wide range of sizes and weights, supporting both robust headlines and subtle metadata. Tightly tracked at large sizes for a contemporary feel.

### Editorial New — Used sparingly for specific heading elements at 24px, weight 300, it provides a light, elegant contrast to the primary sans-serif, adding a touch of sophisticated flair without sacrificing modernity. Its unique character functions as an occasional alternative voice. · `--font-editorial-new`
- **Substitute:** Playfair Display
- **Weights:** 300
- **Sizes:** 24px
- **Line height:** 1.50
- **Letter spacing:** normal
- **Role:** Used sparingly for specific heading elements at 24px, weight 300, it provides a light, elegant contrast to the primary sans-serif, adding a touch of sophisticated flair without sacrificing modernity. Its unique character functions as an occasional alternative voice.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.78 | — | `--text-caption` |
| button | 16px | 1.5 | -0.48px | `--text-button` |
| subheading | 24px | 1.5 | — | `--text-subheading` |
| heading | 40px | 1.2 | — | `--text-heading` |
| heading-lg | 72px | 1.14 | -1.44px | `--text-heading-lg` |
| display | 140px | 0.89 | -3.64px | `--text-display` |

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
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 60 | 60px | `--spacing-60` |
| 64 | 64px | `--spacing-64` |
| 72 | 72px | `--spacing-72` |
| 80 | 80px | `--spacing-80` |
| 100 | 100px | `--spacing-100` |
| 104 | 104px | `--spacing-104` |
| 120 | 120px | `--spacing-120` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 12px |
| pills | 16777200px |
| small | 6px |
| images | 12px |
| inputs | 12px |
| buttons | 6px |
| default | 6px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| xl | `rgba(0, 0, 0, 0.25) 0px 25px 50px -12px` | `--shadow-xl` |

### Layout

- **Section gap:** 100-150px
- **Card padding:** 20px
- **Element gap:** 4-16px

## Components

### Primary Ghost Button
**Role:** Action button

Background transparent, text #F7F4EF. Used for secondary actions like 'Sign In' or 'Advanced'. Displays a subtle inner shadow on hover/focus that reveals a light tint.

### Pill Ghost Button
**Role:** Filter/Tag button

Background oklab(0.999994 0.0000455678 0.0000200868 / 0.05), text #F7F4EF, with an extremely large border radius (16777200px) creating a pill shape. Used for tags or subtle navigation.

### Primary Filled Button
**Role:** Main CTA Button

Solid #F7F4EF background with #101012 text and 16777200px border radius, 8px padding vertical, 16px horizontal. Used for primary calls to action like 'Sign Up'.

### Interactive Input Field
**Role:** Text input

Background transparent, text #FFFFFF, border radius 12px. Used for user input fields, placeholder text is typically #A3A3A3.

### Create Action Button
**Role:** Primary interactive button with gradient

Background linear-gradient(90deg, #fd429c, #f5d907), text #F7F4EF, border radius 6px. Central interactive element for content generation, featuring a vibrant gradient to draw focus.

### Prompt Input Container
**Role:** Input wrapper

Background oklab(0.173939 0.00113384 -0.00393198 / 0.25) rgba(0,0,0,0.25), text #FCFBF9, border-top rgba(255,255,255,0.1), border-radius 6px, padding 4px vertical, 8px horizontal. Encapsulates input fields for music creation.

## Do's and Don'ts

### Do
- Prioritize text legibility on dark backgrounds by using Ghost White (#F7F4EF) or Pure White (#FFFFFF) for body and headline text.
- Use Pitch Black (#101012) as the primary page background to maintain the dark, atmospheric tone across all sections.
- Employ the 6px border radius for all interactive elements like buttons and input containers to ensure a consistent, slightly softened aesthetic.
- Apply the gradient from Vivid Pink (#FD429C) to Sunset Yellow (#F5D907) exclusively for key 'Create' actions to highlight primary functionality.
- Maintain generous vertical spacing between sections (100-150px) to provide breathing room and prevent visual clutter on the dark canvas.
- Use Neue Montreal at a weight of 300 or 400 for most text, reserving 500 for emphasized elements, without overusing bolding.
- Ensure interactive elements like buttons have a minimum padding of 4px vertical and 8px horizontal, or 8px vertical and 16px horizontal for primary CTAs.

### Don't
- Avoid using bright, saturated colors for large background areas or extensive text blocks, as this will disrupt the intended dark and low-key aesthetic.
- Do not introduce hard shadows or strong elevation effects that could break the subtle, layered depth created by varying dark tones.
- Refrain from deviating from the established border radii; maintain 6px for buttons and 12px for cards/inputs.
- Do not use more than one distinct primary brand color in any single section to avoid visual competition and maintain focus on the content.
- Do not use generic system fonts; Neue Montreal is critical to the brand's typographic identity.
- Avoid excessive use of the Editorial New typeface; it is a decorative accent for specific headings, not a general body or UI font.
- Do not introduce stark white backgrounds for entire sections, as the design system is fundamentally dark-themed with occasional light elements for high contrast.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Page Base | `#101012` | The foundational background for the entire page, providing a deep, dark canvas. |
| 1 | Card Surface | `#17171a` | Used for card backgrounds and grouped content, visually lifting elements slightly from the base with a subtle darker tone. |
| 2 | Interactive Overlay | `#00000040` | A semi-transparent dark shade used for interactive elements like input containers, creating a sense of depth and interactivity over the base. |

## Elevation

- **Prominent Cards/Containers:** `box-shadow: rgba(0, 0, 0, 0.25) 0px 25px 50px -12px;`

## Imagery

The visual language for imagery is characterized by contained, slightly rounded media cards displaying diverse content such as album art or user-generated visualizers. These are often dark-toned or moody, showcasing a mix of abstract and human elements, implying artistic creation. The treatment involves a 12px border radius, with elements appearing in a somewhat scattered, dynamic arrangement rather than a rigid grid, reinforcing a creative, less formal atmosphere. The images serve a primarily functional and atmospheric role, decorating the dark interface and providing visual context to the AI-generated music tracks.

## Layout

The page primarily employs a full-bleed layout with content sections centered, but without a strict `pageMaxWidth` constraint, giving a sense of expansiveness. The hero section is full-bleed, featuring a dominant, centrally aligned headline on a dark, subtly textured gradient background, with interactive elements positioned below. Subsequent sections often feature a mix of centered stacked content and fluid arrangements of cards or media, sometimes flowing freely across the width. There's a subtle rhythm created by changes in background tint or the introduction of card-based content, rather than strong visual dividers. Navigation is handled by a minimal top bar with 'Sign In' and 'Sign Up' buttons.

## Agent Prompt Guide

### Quick Color Reference
- **Text Primary (dark bg):** #F7F4EF
- **Text Secondary (light bg):** #101012
- **Background Primary:** #101012
- **CTA Gradient:** linear-gradient(90deg, #fd429c, #f5d907)
- **Button Text (Primary):** #101012
- **Accent Icon:** #f5d907

### 3-5 Example Component Prompts
1. **Create a Hero Section**: Background #101012, with a subtle gradient texture. Centered headline 'Make a house song about quitting your job' using Neue Montreal, 72px, weight 500, #F7F4EF, letter-spacing -1.44px. Subtext 'Start with a simple prompt...' Neue Montreal, 24px, weight 400, #F7F4EF, line-height 1.5. Below, a text input 'Chat to make music' with transparent background, #FFFFFF text, 12px radius, and a 'Create' button with background linear-gradient(90deg, #fd429c, #f5d907), #F7F4EF text, 6px radius, 4px vertical 8px horizontal padding.
2. **Generate a Ghost Button**: 'Sign In' ghost button: background transparent, text #F7F4EF, Neue Montreal, 15px, weight 400, 6px border-radius, 4px vertical 8px horizontal padding.
3. **Design a Media Card**: Background #17171a, 12px border radius, with an image inside that also has a 12px radius. Title text 'Moth Among the Stars (Live)' Neue Montreal, 15px, weight 400, #F7F4EF. Small text '@ SunoUser' Neue Montreal, 12px, weight 300, #A3A3A3. Include a play icon using #F5D907.
4. **Create a Filled Primary Button**: 'Sign Up' button: background #F7F4EF, text #101012, Neue Montreal, 16px, weight 500, 16777200px border-radius, 8px vertical 16px horizontal padding.

## Similar Brands

- **Spotify** — Same dark theme with vibrant, gradient-based accents for key interactive elements like play buttons or calls to action.
- **Ableton** — Dark UI with a focus on functional, clean typography and minimal, well-defined interactive elements, catering to music creation.
- **Linear** — Similar modern, dark-themed aesthetic with a strong emphasis on clean typography and subtle, purposeful use of color to denote interactivity.
- **Discord** — Utilizes a dark background with specific, brighter colors for key features and interactive elements, maintaining a digital, connected feel.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-pitch-black: #101012;
  --color-void-black: #17171a;
  --color-ghost-white: #f7f4ef;
  --color-pure-white: #ffffff;
  --color-graphite: #000000;
  --color-ash-gray: #c2c2c1;
  --color-muted-steel: #a3a3a3;
  --color-sunset-yellow: #f5d907;
  --color-vivid-pink: #fd429c;
  --color-electric-green: #02d95c;

  /* Typography — Font Families */
  --font-neue-montreal: 'Neue Montreal', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-editorial-new: 'Editorial New', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.78;
  --text-button: 16px;
  --leading-button: 1.5;
  --tracking-button: -0.48px;
  --text-subheading: 24px;
  --leading-subheading: 1.5;
  --text-heading: 40px;
  --leading-heading: 1.2;
  --text-heading-lg: 72px;
  --leading-heading-lg: 1.14;
  --tracking-heading-lg: -1.44px;
  --text-display: 140px;
  --leading-display: 0.89;
  --tracking-display: -3.64px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-100: 100px;
  --spacing-104: 104px;
  --spacing-120: 120px;

  /* Layout */
  --section-gap: 100-150px;
  --card-padding: 20px;
  --element-gap: 4-16px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-xl: 12px;
  --radius-2xl: 20px;
  --radius-3xl: 24px;

  /* Named Radii */
  --radius-cards: 12px;
  --radius-pills: 16777200px;
  --radius-small: 6px;
  --radius-images: 12px;
  --radius-inputs: 12px;
  --radius-buttons: 6px;
  --radius-default: 6px;

  /* Shadows */
  --shadow-xl: rgba(0, 0, 0, 0.25) 0px 25px 50px -12px;

  /* Surfaces */
  --surface-page-base: #101012;
  --surface-card-surface: #17171a;
  --surface-interactive-overlay: #00000040;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-pitch-black: #101012;
  --color-void-black: #17171a;
  --color-ghost-white: #f7f4ef;
  --color-pure-white: #ffffff;
  --color-graphite: #000000;
  --color-ash-gray: #c2c2c1;
  --color-muted-steel: #a3a3a3;
  --color-sunset-yellow: #f5d907;
  --color-vivid-pink: #fd429c;
  --color-electric-green: #02d95c;

  /* Typography */
  --font-neue-montreal: 'Neue Montreal', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-editorial-new: 'Editorial New', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.78;
  --text-button: 16px;
  --leading-button: 1.5;
  --tracking-button: -0.48px;
  --text-subheading: 24px;
  --leading-subheading: 1.5;
  --text-heading: 40px;
  --leading-heading: 1.2;
  --text-heading-lg: 72px;
  --leading-heading-lg: 1.14;
  --tracking-heading-lg: -1.44px;
  --text-display: 140px;
  --leading-display: 0.89;
  --tracking-display: -3.64px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-100: 100px;
  --spacing-104: 104px;
  --spacing-120: 120px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-xl: 12px;
  --radius-2xl: 20px;
  --radius-3xl: 24px;

  /* Shadows */
  --shadow-xl: rgba(0, 0, 0, 0.25) 0px 25px 50px -12px;
}
```

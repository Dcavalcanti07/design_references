# Strava — Style Reference
> Athletic Orange Highlight

**Theme:** light

This design system projects an active, performance-oriented energy with its high-contrast typography and prominent use of a single, vibrant orange. The stark black text against white or near-white backgrounds, combined with structured, rectangular forms defines its modern utility. The orange acts as a constant visual cue, highlighting interactive elements and brand presence without relying on subtle gradations or complex color palettes, focusing instead on direct and clear communication.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#000000` | `--color-midnight-ink` | Primary text, critical body copy, dark icons, default button borders. Creates strong contrast on light backgrounds. |
| Cloudburst Gray | `#43423f` | `--color-cloudburst-gray` | Secondary text, link hover states, subheadings. Provides readability while subtly softening the intensity of Midnight Ink. |
| Ash Charcoal | `#21211f` | `--color-ash-charcoal` | Darker secondary text, button text on light interaction, subtle borders. A deep nearly-black that offers slight variation from Midnight Ink. |
| Whisper White | `#ffffff` | `--color-whisper-white` | Page backgrounds, card surfaces, button backgrounds. The primary backdrop for content. |
| Summit Cream | `#f9f8f5` | `--color-summit-cream` | Subtle background sections, footer background. Offers a warm, off-white alternative to Whisper White to delineate structural areas. |
| Pebble Gray | `#e0e0de` | `--color-pebble-gray` | Light button borders, dividers. A very light gray for subtle structural definitions. |
| Strava Orange | `#fc5200` | `--color-strava-orange` | CTA buttons, primary links, active navigation items, brand accents. This vivid orange is the sole chromatic brand identifier, drawing immediate attention to key interactions. |
| Link Blue | `#0060d0` | `--color-link-blue` | Informational links (e.g., legal text). Differentiated from Strava Orange for non-primary actions. |
| Google Red | `#ea4335` | `--color-google-red` | Google icon brand color, not a general semantic red. |
| Google Green | `#34a853` | `--color-google-green` | Google icon brand color, not a general semantic green. |
| Google Blue | `#4285f4` | `--color-google-blue` | Google icon brand color, not a general semantic blue. |
| Google Yellow | `#fbbc05` | `--color-google-yellow` | Google icon brand color, not a general semantic yellow. |

## Tokens — Typography

### Boathouse — Body text, links, navigation items, footer text, button text. This primary typeface handles all non-heading content, providing a clear and functional voice. · `--font-boathouse`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 12px, 14px, 15px, 16px, 32px
- **Line height:** 1.00, 1.20, 1.29, 1.30, 1.33, 1.50
- **Letter spacing:** normal
- **Role:** Body text, links, navigation items, footer text, button text. This primary typeface handles all non-heading content, providing a clear and functional voice.

### Boathouse — Headlines and prominent calls to action. The heavier weight at larger sizes creates a strong focal point without overpowering. · `--font-boathouse`
- **Substitute:** Inter
- **Weights:** 600
- **Sizes:** 12px, 14px, 15px, 16px, 32px
- **Line height:** 1.00, 1.20, 1.29, 1.30, 1.33, 1.50
- **Letter spacing:** normal
- **Role:** Headlines and prominent calls to action. The heavier weight at larger sizes creates a strong focal point without overpowering.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.5 | — | `--text-caption` |
| body-sm | 14px | 1.33 | — | `--text-body-sm` |
| display | 32px | 1.2 | — | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 8 | 8px | `--spacing-8` |
| 12 | 12px | `--spacing-12` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 4px |
| buttons | 4px |
| input_fields | 4px |

### Layout

## Components

### Primary CTA Button
**Role:** Main call to action

Solid Strava Orange background (#fc5200) with Whisper White text (#ffffff), 4px border-radius. Padding: 10px top/bottom, 50px left/right. Uses Boathouse Bold for text.

### Secondary Outline Button (Social)
**Role:** Alternative login/signup

Summit Cream background (#f9f8f5 - inferred from screenshot), Ash Charcoal text (#21211f), and Pebble Gray border (#e0e0de) at 4px border-radius. Padding: 10px top/bottom, 50px left/right. Accommodates social icons.

### Ghost Button (Header)
**Role:** Navigation, secondary actions

Transparent background, Midnight Ink text (#000000) or Cloudburst Gray (#43423f), no explicit border, 4px border-radius. Minimal padding, emphasis on text.

### Footer Link
**Role:** Navigational links in footer

Uses Cloudburst Gray text (#43423f) for default, with an inferred Strava Orange (#fc5200) hover/active state. No background or border.

### Navigation Link
**Role:** Primary site navigation

Uses Midnight Ink text (#000000) for default, with an inferred Strava Orange (#fc5200) for active/hover. No background or border.

### Form Card
**Role:** Content container for forms

Whisper White background (#ffffff), 4px border-radius. Contains heading, body text, and multiple button components. Inferred padding around internal elements.

## Do's and Don'ts

### Do
- Prioritize Strava Orange (#fc5200) for all primary calls to action and active states.
- Maintain high contrast by using Midnight Ink (#000000) or Ash Charcoal (#21211f) text on Whisper White (#ffffff) or Summit Cream (#f9f8f5) backgrounds.
- Apply a consistent 4px border-radius to all interactive elements like buttons and input fields.
- Use Boathouse (or Inter) weight 600 for all main headings (32px), ensuring clear hierarchy.
- Separate content sections with distinct background colors, such as Whisper White (#ffffff) for main content and Summit Cream (#f9f8f5) for footers.

### Don't
- Do not introduce new primary accent colors other than Strava Orange (#fc5200) or Link Blue (#0060d0).
- Avoid using soft, low-contrast text-on-background combinations; maintain AAA or AA contrast ratios.
- Do not deviate from the 4px border-radius on buttons and input fields to maintain visual consistency.
- Do not use generic system fonts; leverage Boathouse (or Inter) for all text elements.
- Do not use box-shadow for elevation; rely on background color changes and borders to define hierarchy and separation.

## Imagery

The visual language combines aspirational, real-world photography of athletes in action with clean, functional UI elements. Photography features vibrant outdoor scenes (cyclists, runners) with a natural, un-staged feel, emphasizing movement and community. Imagery is primarily full-bleed or large background elements, without masks or heavy treatments, allowing the scenes to speak for themselves. Product screenshots are integrated to explain functionality, often with overlaid path graphics or app UI. Icons are simple, filled, and monochrome, with an apparent medium stroke weight when outlined (logo). The overall density is balanced, allowing imagery to dominate sections while text remains concise.

## Layout

The page uses a centered, quasi-full-bleed model, with a wide central content area that appears contained on larger screens but feels expansive. The hero section is a prominent three-column split: large, emotive photography on the left, a central, white form card for sign-up, and a product-in-context shot on the right, creating an immediate narrative. Sections are distinct blocks, with no alternating background bands visible. Content is generally stacked vertically within these blocks, or aligned within columns (e.g., footer grid). The navigation is a classic horizontal top bar, sticky (inferred), with a simple `Log In` button. The overall density is comfortable, with ample padding around elements and sections, suggesting a focus on clarity rather than information density.

## Agent Prompt Guide

**Quick Color Reference:**
- Text (Primary): #000000
- Background (Page): #ffffff
- CTA (Orange): #fc5200
- Border (Light): #e0e0de
- Accent (Brand): #fc5200

**Example Component Prompts:**
1. Create a primary CTA button: background #fc5200, text #ffffff, border-radius 4px, padding 10px 50px. Text 'Sign Up With Email' using Boathouse weight 600, 16px.
2. Develop a social login button: background Whisper White #ffffff, text Ash Charcoal #21211f, border #e0e0de, border-radius 4px, padding 10px 50px. Add a Google logo to the left. Text 'Sign Up With Google' using Boathouse weight 400, 16px.
3. Design a main header navigation link: text Midnight Ink #000000, Boathouse weight 400, 16px. Name it 'Features'.
4. Generate a section headline: text Midnight Ink #000000, Boathouse weight 600, 32px, line-height 1.2. Content: 'Community-Powered Motivation'.
5. Create body text with an embedded link: text Cloudburst Gray #43423f, Boathouse weight 400, 15px. Link text 'Terms of Service' in Link Blue #0060d0.

## Similar Brands

- **Garmin Connect** — Athletic brand with functional, high-contrast UI and a strong accent color against a clean white background.
- **Nike Training Club** — Focus on activity and performance, utilitarian layout, and strong emphasis on clear call-to-actions with a single brand color.
- **AllTrails** — Outdoor activity focus, clean light theme, and use of a prominent accent color (green) for interactive elements.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-cloudburst-gray: #43423f;
  --color-ash-charcoal: #21211f;
  --color-whisper-white: #ffffff;
  --color-summit-cream: #f9f8f5;
  --color-pebble-gray: #e0e0de;
  --color-strava-orange: #fc5200;
  --color-link-blue: #0060d0;
  --color-google-red: #ea4335;
  --color-google-green: #34a853;
  --color-google-blue: #4285f4;
  --color-google-yellow: #fbbc05;

  /* Typography — Font Families */
  --font-boathouse: 'Boathouse', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --text-body-sm: 14px;
  --leading-body-sm: 1.33;
  --text-display: 32px;
  --leading-display: 1.2;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-semibold: 600;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;

  /* Layout */

  /* Border Radius */
  --radius-md: 4px;

  /* Named Radii */
  --radius-cards: 4px;
  --radius-buttons: 4px;
  --radius-inputfields: 4px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-cloudburst-gray: #43423f;
  --color-ash-charcoal: #21211f;
  --color-whisper-white: #ffffff;
  --color-summit-cream: #f9f8f5;
  --color-pebble-gray: #e0e0de;
  --color-strava-orange: #fc5200;
  --color-link-blue: #0060d0;
  --color-google-red: #ea4335;
  --color-google-green: #34a853;
  --color-google-blue: #4285f4;
  --color-google-yellow: #fbbc05;

  /* Typography */
  --font-boathouse: 'Boathouse', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --text-body-sm: 14px;
  --leading-body-sm: 1.33;
  --text-display: 32px;
  --leading-display: 1.2;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;

  /* Border Radius */
  --radius-md: 4px;
}
```

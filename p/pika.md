# Pika — Style Reference
> Dual-pane studio and control room. One side warm, inviting; the other dark, efficient.

**Theme:** mixed

The site presents a striking split personality, juxtaposing a relaxed, warm-toned left panel with a deep, authoritative black right panel. This creates a functional and conceptual division, visually separating descriptive content from interactive login forms. Text on both sides prioritizes legibility with high contrast, while subtle border radii soften interactive elements without sacrificing a clean, modern edge. It feels like a laid-back, creative studio space meeting a behind-the-scenes control panel.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Buttermilk Base | `#ffedd2` | `--color-buttermilk-base` | Background for descriptive content, brand accents, selected interactive states. |
| Inkwell Deep | `#0d0d0d` | `--color-inkwell-deep` | Primary text across both light and dark backgrounds. This deep black provides substantial contrast for readability. |
| Carbon Panel | `#1f1f1f` | `--color-carbon-panel` | Background for the interactive login panel, establishing a command-center aesthetic. |
| Paper White | `#ffffff` | `--color-paper-white` | Background for standard buttons and as a primary text color on the dark panel. |
| Ash Gray | `#9e9e9` | `--color-ash-gray` | Secondary text and informational labels, providing a softer contrast than Inkwell Deep. |
| Chrome Edges | `#e5e7eb` | `--color-chrome-edges` | Subtle borders and separators, ensuring elements are defined without harsh lines. |
| Facebook Blue | `#4267b2` | `--color-facebook-blue` | Iconography for Facebook sign-in. |
| Discord Purple | `#5865f2` | `--color-discord-purple` | Iconography for Discord sign-in. |
| Google Yellow | `#ffc107` | `--color-google-yellow` | Iconography for Google sign-in. |

## Tokens — Typography

### telka — Foundational typeface for body text, links, and buttons. Its range of weights from 300 to 450 supports a subtle hierarchy without resorting to bold, maintaining an understated confidence across informational and interactive elements. The slight negative letter-spacing at smaller sizes (–0.02em at 14px) brings a sense of precision. · `--font-telka`
- **Substitute:** Inter
- **Weights:** 300, 400, 450
- **Sizes:** 12px, 14px, 16px
- **Line height:** 1.33, 1.43, 1.50
- **Letter spacing:** -0.28, 0.16
- **Role:** Foundational typeface for body text, links, and buttons. Its range of weights from 300 to 450 supports a subtle hierarchy without resorting to bold, maintaining an understated confidence across informational and interactive elements. The slight negative letter-spacing at smaller sizes (–0.02em at 14px) brings a sense of precision.

### telkaExtended — Reserved exclusively for prominent headings, its 900 weight and slightly positive letter-spacing (0.01em) make it declarative without being aggressive, asserting its presence through density rather than sheer size, crucial for the 'Reality is Optional' headline. · `--font-telkaextended`
- **Substitute:** Inter Black
- **Weights:** 900
- **Sizes:** 32px
- **Line height:** 1.13
- **Letter spacing:** 0.32
- **Role:** Reserved exclusively for prominent headings, its 900 weight and slightly positive letter-spacing (0.01em) make it declarative without being aggressive, asserting its presence through density rather than sheer size, crucial for the 'Reality is Optional' headline.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body-sm | 14px | 1.43 | -0.28px | `--text-body-sm` |
| body-lg | 16px | 1.5 | 0.16px | `--text-body-lg` |
| display | 32px | 1.13 | 0.32px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 8 | 8px | `--spacing-8` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 28 | 28px | `--spacing-28` |
| 32 | 32px | `--spacing-32` |
| 56 | 56px | `--spacing-56` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |

### Border Radius

| Element | Value |
|---------|-------|
| buttons | 6px |
| videoPlayer | 10px |

### Layout

- **Section gap:** 56px
- **Element gap:** 8px

## Components

### Primary Sign-in Button
**Role:** Main call to action for email sign-in.

Background: Buttermilk Base (#ffedd2), text: Inkwell Deep (#0d0d0d), border: Chrome Edges (#e5e7eb) 1px, border radius: 6px, padding: 10px 16px. Font: telka, 16px, weight 400.

### Social Sign-in Button
**Role:** Alternative sign-in options via social platforms.

Background: Paper White (#ffffff), text: Inkwell Deep (#0d0d0d), border: Chrome Edges (#e5e7eb) 1px, border radius: 6px, padding: 10px 16px. Font: telka, 16px, weight 400. Includes an icon.

### Social Sign-in Button (Compact)
**Role:** Social sign-in with reduced padding and dark background (not explicitly shown in screenshot but available in variants).

Background: Carbon Panel (#1f1f1f), text: Paper White (#ffffff), border: Chrome Edges (#e5e7eb) 1px, border radius: 6px, padding: 6px 6px. Font: telka, 16px, weight 400. Includes an icon.

### Video Player Frame
**Role:** Container for embedded video content.

Border radius: 10px. Image treatment: contained, slightly rounded corners.

## Do's and Don'ts

### Do
- Always use Buttermilk Base (#ffedd2) for the left content pane background and Carbon Panel (#1f1f1f) for the right interactive pane background to maintain the split layout identity.
- Apply a 6px border radius to all interactive buttons and 10px to larger media containers like video players.
- Use telkaExtended, weight 900, size 32px, lineHeight 1.13, letterSpacing 0.32px for all primary section headings.
- Ensure all primary text on Buttermilk Base background uses Inkwell Deep (#0d0d0d) for maximum readability.
- Maintain 10px top/bottom padding and 16px left/right padding for standard-height buttons.
- Use Chrome Edges (#e5e7eb) for subtle borders on buttons and input fields where a delineation is needed without high contrast.

### Don't
- Do not deviate from the two-tone split layout structure; avoid full-bleed backgrounds that span both content and interactive areas.
- Do not introduce strong chromatic colors beyond the specific brand/social icons; the palette is intentionally restrained.
- Avoid large, aggressive letter-spacing on body text; telka uses subtle negative or minimal positive spacing.
- Do not use box-shadows for elevation; the design relies on color contrast and subtle borders for depth.
- Do not use font weights above 450 for body text or links; reserve 900 for headings only.

## Imagery

Imagery primarily consists of contained video content and social media icons. The video content (e.g., a dog in a recording studio) is presented with sharp, defined edges, enclosed within a frame with a 10px border radius. This suggests a focus on showcasing the output or process of the AI tool with direct, unstylized media. Icons are flat, filled, and leverage their brand's specific color, appearing within buttons. The overall style is functional rather than decorative, with imagery serving an explicit role in content or interaction.

## Layout

The page employs a strong two-column, split-screen layout where the left column (approx 67% width) is the content area with a Buttermilk Base background and the right column (approx 33% width) is a dark interactive login panel. The content area is left-aligned and centrally stacked, featuring a video player followed by descriptive text. The right panel is also centrally stacked with a prominent heading and a series of vertically stacked social and email login buttons. Horizontal padding (67px) on the content side maintains significant negative space. Sections are separated vertically by a consistent 56px gap for visual breathing room. Navigation is minimal, consisting of a simple footer with text links.

## Agent Prompt Guide

### Quick Color Reference
- Text (Inkwell Deep): #0d0d0d
- Background (Buttermilk Base): #ffedd2
- Background (Carbon Panel): #1f1f1f
- CTA Background (Email): #ffedd2
- CTA Text (Email): #0d0d0d
- Border (Chrome Edges): #e5e7eb

### 3-5 Example Component Prompts
1. Create a primary headline for the login panel: 'REALITY IS OPTIONAL'. Use telkaExtended font, weight 900, size 32px, lineHeight 1.13, letterSpacing 0.32px, color Inkwell Deep (#0d0d0d) if on Buttermilk Base or Paper White (#ffffff) if on Carbon Panel.
2. Design an 'Sign in with an email' button: Background Buttermilk Base (#ffedd2), text Inkwell Deep (#0d0d0d), 1px border Chrome Edges (#e5e7eb), 6px border-radius, 10px 16px padding. Text should use telka, weight 400, 16px. Include an email icon.
3. Create a social login button for Google: Background Paper White (#ffffff), text Inkwell Deep (#0d0d0d), 1px border Chrome Edges (#e5e7eb), 6px border-radius, 10px 16px padding. Text should use telka, weight 400, 16px. Include the Google icon with its brand color if available.
4. Generate general body text: 'Have you heard? Our Pikaformance model is now available on web: hyper-real expressions, synced to any sound.' Use telka font, weight 400, 16px, lineHeight 1.5, letterSpacing normal, color Inkwell Deep (#0d0d0d).
5. Create a video player container: Apply a 10px border-radius. The video title 'AUDIO-DRIVEN PERFORMANCES' should overlay in white, telkaExtended, weight 900, 32px, lineHeight 1.13, letterSpacing 0.32px.

## Similar Brands

- **Anthropic AI** — Similar two-column layout separating primary content from a call-to-action or product interaction, often with strong background color differentiation.
- **Midjourney** — Shared aesthetic of presenting advanced AI capabilities in a clear, often split-screen, and functional UI without excessive embellishment.
- **Linear** — Although typically mono-theme, Linear shares the commitment to a highly functional, high-contrast, text-dominant interface with minimal decorative elements, creating a sense of powerful utility.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-buttermilk-base: #ffedd2;
  --color-inkwell-deep: #0d0d0d;
  --color-carbon-panel: #1f1f1f;
  --color-paper-white: #ffffff;
  --color-ash-gray: #9e9e9;
  --color-chrome-edges: #e5e7eb;
  --color-facebook-blue: #4267b2;
  --color-discord-purple: #5865f2;
  --color-google-yellow: #ffc107;

  /* Typography — Font Families */
  --font-telka: 'telka', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-telkaextended: 'telkaExtended', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-sm: 14px;
  --leading-body-sm: 1.43;
  --tracking-body-sm: -0.28px;
  --text-body-lg: 16px;
  --leading-body-lg: 1.5;
  --tracking-body-lg: 0.16px;
  --text-display: 32px;
  --leading-display: 1.13;
  --tracking-display: 0.32px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-w450: 450;
  --font-weight-black: 900;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;

  /* Layout */
  --section-gap: 56px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-lg: 10px;

  /* Named Radii */
  --radius-buttons: 6px;
  --radius-videoplayer: 10px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-buttermilk-base: #ffedd2;
  --color-inkwell-deep: #0d0d0d;
  --color-carbon-panel: #1f1f1f;
  --color-paper-white: #ffffff;
  --color-ash-gray: #9e9e9;
  --color-chrome-edges: #e5e7eb;
  --color-facebook-blue: #4267b2;
  --color-discord-purple: #5865f2;
  --color-google-yellow: #ffc107;

  /* Typography */
  --font-telka: 'telka', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-telkaextended: 'telkaExtended', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-sm: 14px;
  --leading-body-sm: 1.43;
  --tracking-body-sm: -0.28px;
  --text-body-lg: 16px;
  --leading-body-lg: 1.5;
  --tracking-body-lg: 0.16px;
  --text-display: 32px;
  --leading-display: 1.13;
  --tracking-display: 0.32px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-lg: 10px;
}
```

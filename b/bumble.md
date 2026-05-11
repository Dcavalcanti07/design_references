# Bumble — Style Reference
> sunny confident playground

**Theme:** light

Bumble's visual system evokes a playful confidence through its dominant bright yellow canvas and bold, heavy typography. Interaction is signaled by a shift from the signature brand yellow to crisp white and deep charcoal for actionable elements. Surfaces generally remain flat or minimally elevated with rounded corners, maintaining a light and open aesthetic that allows photographic content to take center stage.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Bumble Yellow | `#ffdb5b` | `--color-bumble-yellow` | Primary background for sections and cards, badge backgrounds, key brand accents that brighten the overall experience. This bright, vivid yellow is the most prominent color, defining the brand's energetic and inviting atmosphere |
| Amber Glow | `#fff386` | `--color-amber-glow` | Subtle card backgrounds, adding a lighter, softer variation of the primary brand yellow |
| Charcoal Ink | `#202020` | `--color-charcoal-ink` | Primary text color for headlines and body. Also used for button backgrounds for critical actions, navigation borders, and icon fills, providing strong contrast against both white and yellow surfaces |
| Arctic White | `#ffffff` | `--color-arctic-white` | Page backgrounds, card backgrounds, and button text on Charcoal Ink buttons. Provides clean, open space and strong contrast |
| Deep Gray | `#3b3b3b` | `--color-deep-gray` | Secondary text color for descriptive body copy and subheadings, offering a slightly softer contrast than Charcoal Ink |
| Cloud Gray | `#f3f3f3` | `--color-cloud-gray` | Subtle secondary card backgrounds, adding a faint visual separation from pure white without heavy contrast |
| Muted Stone | `#343333` | `--color-muted-stone` | Text color for badges and less prominent interface elements |
| Subtle Slate | `#575656` | `--color-subtle-slate` | Helper text, navigation descriptions, and other subdued text elements |

## Tokens — Typography

### BumbleSans — Primary brand typeface. Its wide range of weights and sizes supports bold headlines and clear body text, establishing a confident and friendly tone. Letter spacing is slightly increased for smaller sizes and decreased for larger headlines. · `--font-bumblesans`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400, 500, 600, 700
- **Sizes:** 15px, 16px, 17px, 18px, 20px, 24px, 32px, 34px, 40px, 49px, 68px
- **Line height:** 1.00, 1.10, 1.12, 1.18, 1.20, 1.25, 1.29, 1.33, 1.50
- **Letter spacing:** 0.0070em, 0.0090em, 0.0120em, 0.0160em, 0.0180em, 0.0200em
- **Role:** Primary brand typeface. Its wide range of weights and sizes supports bold headlines and clear body text, establishing a confident and friendly tone. Letter spacing is slightly increased for smaller sizes and decreased for larger headlines.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body-sm | 15px | 1.25 | 0.007px | `--text-body-sm` |
| subheading | 20px | 1.25 | 0.012px | `--text-subheading` |
| heading-sm | 24px | 1.2 | 0.016px | `--text-heading-sm` |
| heading | 32px | 1.18 | 0.018px | `--text-heading` |
| heading-lg | 49px | 1.1 | 0.02px | `--text-heading-lg` |
| display | 68px | 1 | 0.02px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 8 | 8px | `--spacing-8` |
| 12 | 12px | `--spacing-12` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 36 | 36px | `--spacing-36` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 16px |
| badges | 1000px |
| buttons | 16px |
| navigation | 16px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| sm | `rgba(32, 32, 32, 0.12) 0px 1px 8px 0px` | `--shadow-sm` |

### Layout

- **Page max-width:** 224px
- **Section gap:** 40px
- **Card padding:** 40px
- **Element gap:** 24px

## Components

### Primary Filled Button
**Role:** Call to action.

Background: Charcoal Ink (#202020), Text: Arctic White (#ffffff). Padding: 14px vertical, 24px horizontal. Radius: 16px or 25px (pill shape for prominent CTAs).

### Ghost Navigation Button
**Role:** Secondary navigation or interactive text.

Background: None, Text: Charcoal Ink (#202020). Padding: 14px vertical, 22px horizontal. Radius: 0px.

### Subtle Background Button
**Role:** Interactive elements with a softer visual presence.

Background: rgba(255, 255, 255, 0.8), Text: Subtle Slate (#575656). Padding: 12px vertical, 24px horizontal. Radius: 16px. Used for less prominent actions or filters.

### Yellow Feature Card
**Role:** Highlights key features or content areas.

Background: Bumble Yellow (#ffdb5b) or Amber Glow (#fff386). Radius: 9px or 24px. No box shadow. Padding varies by content, often 0px to allow content to dictate spacing.

### White Information Card
**Role:** Displays content on a neutral background.

Background: Arctic White (#ffffff) or Cloud Gray (#f3f3f3). Radius: 24px. No box shadow. Padding varies by content, often 0px to allow content to dictate spacing, occasionally 14px.

### Pill Badge
**Role:** Labels categories or attributes.

Background: Bumble Yellow (#ffdb5b), Text: Muted Stone (#343333). Padding: 20px vertical, 10px horizontal. Radius: 1000px (fully rounded).

## Do's and Don'ts

### Do
- Use Bumble Yellow (#ffdb5b) as the dominant background color for sections or cards to immediately establish brand identity.
- Apply Charcoal Ink (#202020) for all primary body text and headlines to ensure high contrast and readability.
- Prefer large type sizes (e.g., 68px, 49px) and heavier weights (500, 600, 700) for headlines with the BumbleSans typeface.
- Utilize 16px and 24px border radii for buttons and cards respectively, creating a soft, approachable feel.
- Ensure generous internal padding for interactive elements; buttons typically use 14px vertical and 24px horizontal padding.
- Maintain minimal elevation; shadows should be subtle, such as rgba(32, 32, 32, 0.12) 0px 1px 8px 0px, predominantly for cards.

### Don't
- Avoid using highly saturated colors other than Bumble Yellow or Amber Glow for major interface elements.
- Do not introduce strong, complex shadows, as the system favors a flatter, lighter aesthetic.
- Refrain from using thin body text weights that would visually conflict with the bold headline style.
- Do not deviate from the established rounded border radii for components; sharp corners are not part of this system.
- Avoid tight spacing around content; allow generous element and section gaps (e.g., 24px, 40px) to maintain an open feel.
- Do not use dark backgrounds for full sections unless a specific pattern (like the hero) dictates it, and even then, ensure a vibrant yellow accent or white text provides strong contrast.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Page Canvas | `#ffdb5b` | The foundational background color, used for large sections and the overall page, defining the brand's vibrant presence. |
| 1 | Section Background | `#ffffff` | Clean, open backgrounds for content blocks and distinct sections within the page. |
| 2 | Subtle Card Surface | `#f3f3f3` | A very light gray surface for cards, offering a slight visual differentiation from the white page background. |
| 3 | Accent Card Surface | `#fff386` | A lighter yellow background for cards, providing a brighter accent within sections. |

## Imagery

The site uses a mix of candid, lifestyle photography and product screenshots. Photography often features diverse individuals in engaging, active, and social scenarios, cropped and presented in a natural, unedited style within the UI. Product screenshots highlight the app interface directly, often placed within stylized device mockups or integrated into compositional elements like stacked, angled cards. Images are primarily contained within rounded card-like shapes or as background elements. Icons, though minimal, appear to be filled and monochrome, leveraging Charcoal Ink on Bumble Yellow.

## Layout

The page primarily employs a max-width contained layout, approximately 224px wide, centered on the screen, though the hero section breaks this constraint. The hero features a full-bleed vibrant Bumble Yellow background with large, centered brand typography and overlapping, angled photographic cards showcasing user profiles, creating a dynamic introduction. Subsequent sections alternate between vibrant yellow and clean white backgrounds, providing clear visual breaks. Content is often arranged in prominent centered stacks or two-column text-left/visual-right patterns. Navigation is handled by a sticky top bar with subtle ghost buttons and a prominent brand logo.

## Agent Prompt Guide

Quick Color Reference:
- text: #202020
- background: #ffdb5b
- border: #202020 (often rgba(32, 32, 32, 0.12) for borders with transparency)
- accent: #ffdb5b
- primary action: #202020 (filled action)

Example Component Prompts:
1. Create a large hero banner with a Bumble Yellow (#ffdb5b) background. Include a large headline 'Existimos para acercar a las personas al amor.' using BumbleSans, weight 700, size 68px, Charcoal Ink (#202020). Below it, add a primary action button 'Descargar Bumble' with Charcoal Ink (#202020) background, Arctic White (#ffffff) text, 14px vertical and 24px horizontal padding, and 25px radius.
2. Design a feature card: Use Amber Glow (#fff386) background with 24px border-radius. Inside, place a heading 'Bumble Date' in BumbleSans, weight 600, size 32px, Deep Gray (#3b3b3b). Include a body paragraph in BumbleSans, weight 400, size 16px, Subtle Slate (#575656).
3. Create a navigation item 'Seguridad': Use an Arctic White (#ffffff) background with 16px border-radius, Padding: 12px vertical, 24px horizontal. Text: Charcoal Ink (#202020) at BumbleSans, weight 500, size 17px. Ensure elementGap of 24px between items.

## Similar Brands

- **Tinder** — Dominant brand color for backgrounds that creates an energetic feel, bold typography, and a card-based UI for profiles.
- **Netflix** — Strong brand color dominance across the interface, with clear, high-contrast typography, and visually driven content cards.
- **Spotify** — Heavy emphasis on a vibrant brand color mixed with dark neutrals, custom typography for headlines, and a focus on visual content in grids.
- **Headspace** — Playful color palette, custom friendly typography, and liberal use of rounded corners for UI elements and illustrations.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-bumble-yellow: #ffdb5b;
  --color-amber-glow: #fff386;
  --color-charcoal-ink: #202020;
  --color-arctic-white: #ffffff;
  --color-deep-gray: #3b3b3b;
  --color-cloud-gray: #f3f3f3;
  --color-muted-stone: #343333;
  --color-subtle-slate: #575656;

  /* Typography — Font Families */
  --font-bumblesans: 'BumbleSans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-sm: 15px;
  --leading-body-sm: 1.25;
  --tracking-body-sm: 0.007px;
  --text-subheading: 20px;
  --leading-subheading: 1.25;
  --tracking-subheading: 0.012px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: 0.016px;
  --text-heading: 32px;
  --leading-heading: 1.18;
  --tracking-heading: 0.018px;
  --text-heading-lg: 49px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: 0.02px;
  --text-display: 68px;
  --leading-display: 1;
  --tracking-display: 0.02px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;

  /* Layout */
  --page-max-width: 224px;
  --section-gap: 40px;
  --card-padding: 40px;
  --element-gap: 24px;

  /* Border Radius */
  --radius-lg: 9px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-full: 1000px;

  /* Named Radii */
  --radius-cards: 16px;
  --radius-badges: 1000px;
  --radius-buttons: 16px;
  --radius-navigation: 16px;

  /* Shadows */
  --shadow-sm: rgba(32, 32, 32, 0.12) 0px 1px 8px 0px;

  /* Surfaces */
  --surface-page-canvas: #ffdb5b;
  --surface-section-background: #ffffff;
  --surface-subtle-card-surface: #f3f3f3;
  --surface-accent-card-surface: #fff386;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-bumble-yellow: #ffdb5b;
  --color-amber-glow: #fff386;
  --color-charcoal-ink: #202020;
  --color-arctic-white: #ffffff;
  --color-deep-gray: #3b3b3b;
  --color-cloud-gray: #f3f3f3;
  --color-muted-stone: #343333;
  --color-subtle-slate: #575656;

  /* Typography */
  --font-bumblesans: 'BumbleSans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-sm: 15px;
  --leading-body-sm: 1.25;
  --tracking-body-sm: 0.007px;
  --text-subheading: 20px;
  --leading-subheading: 1.25;
  --tracking-subheading: 0.012px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: 0.016px;
  --text-heading: 32px;
  --leading-heading: 1.18;
  --tracking-heading: 0.018px;
  --text-heading-lg: 49px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: 0.02px;
  --text-display: 68px;
  --leading-display: 1;
  --tracking-display: 0.02px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;

  /* Border Radius */
  --radius-lg: 9px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-full: 1000px;

  /* Shadows */
  --shadow-sm: rgba(32, 32, 32, 0.12) 0px 1px 8px 0px;
}
```

# Payments — Style Reference
> Grape Soda & Lemon Zest. A bold purple lake with bright yellow accents floating atop.

**Theme:** light

This system feels like a playful, high-energy tech brand that dares to be vibrant without sacrificing clarity. The deep, rich 'Grape Soda' purple is the signature and dominant hue, creating a striking backdrop for crisp white text and clean, information-dense UIs. Bright 'Lemon Zest' yellow appears strategically as an accent, especially in the announcement bar, introducing a pop of warmth. Type is clean and authoritative with a touch of character, using generous letter spacing within headlines to balance the bold color choices.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Grape Soda | `#5423e7` | `--color-grape-soda` | Primary background for hero sections and key marketing areas. Establishes a bold, energetic brand presence. |
| Lemon Zest | `#ffc233` | `--color-lemon-zest` | Announcement bars, secondary CTA highlights, and interactive elements. Provides a warm, high-contrast accent. |
| Forest Canopy | `#1e874c` | `--color-forest-canopy` | Success states and positive affirmations, particularly in buttons and cards. Conveys growth and completion. |
| Ocean Deep | `#0075ad` | `--color-ocean-deep` | Informational badges, interactive links, and specific button variants, offering an alternative accent to Forest Canopy. |
| Ruby Glow | `#d50b3` | `--color-ruby-glow` | Error states, warnings, and highlighting critical information. Demands attention without being aggressive. |
| Bubblegum Pink | `#cf75ff` | `--color-bubblegum-pink` | Used for distinctive highlights, potentially playful marketing elements; stands out against the core brand purple. |
| Midnight Ink | `#121217` | `--color-midnight-ink` | Base text color for all content, headings, and primary interactive elements. Offers high contrast on light backgrounds. |
| Ghost White | `#ffffff` | `--color-ghost-white` | Page backgrounds, card surfaces, and primary text color on dark backgrounds. Ensures clarity and spaciousness. |
| Driftwood | `#6c6c89` | `--color-driftwood` | Secondary text, descriptive elements, and subtle borders. Provides softer contrast than Midnight Ink. |
| Parchment | `#f7f7f8` | `--color-parchment` | Subtle background for UI elements like unselected tabs or slight surface differentiation. Near-white gray. |
| Cloud Grey | `#d1d1db` | `--color-cloud-grey` | Subtle borders and dividers, providing visual structure without harshness. |
| Pink Sugar | `#feecfb` | `--color-pink-sugar` | Lightest background tint for specific UI sections, softening the pure white. |

## Tokens — Typography

### Circularpro Book — Display and headlines. The 'ss04' feature settings subtly alter character forms, giving it a distinct, confident yet approachable feel. It's used at massive sizes, with negative letter-spacing for impact, commanding attention. · `--font-circularpro-book`
- **Substitute:** Montserrat, Gotham
- **Weights:** 400
- **Sizes:** 18px, 26px, 36px, 38px, 48px, 56px, 80px
- **Line height:** 1.00, 1.13, 1.14, 1.20, 1.22, 1.25
- **Letter spacing:** -0.04em, -0.03em, -0.02em
- **OpenType features:** `"ss04"`
- **Role:** Display and headlines. The 'ss04' feature settings subtly alter character forms, giving it a distinct, confident yet approachable feel. It's used at massive sizes, with negative letter-spacing for impact, commanding attention.

### Inter — Body copy, navigation, buttons, and detailed UI text. Its high legibility and variable letter spacing at smaller sizes make it ideal for information-dense areas. · `--font-inter`
- **Substitute:** Inter
- **Weights:** 400, 500
- **Sizes:** 14px, 15px, 16px, 18px
- **Line height:** 1.29, 1.40, 1.60, 1.70, 1.80
- **Letter spacing:** -0.01em, 0.143em
- **Role:** Body copy, navigation, buttons, and detailed UI text. Its high legibility and variable letter spacing at smaller sizes make it ideal for information-dense areas.

### Inter — Emphasized text, subheadings, and interactive elements within body copy. Provides subtle hierarchy in a cohesive family. · `--font-inter`
- **Substitute:** Inter
- **Weights:** 400, 500
- **Sizes:** 14px, 15px, 16px, 18px
- **Line height:** 1.29, 1.40, 1.60, 1.70, 1.80
- **Letter spacing:** -0.01em, 0.143em
- **Role:** Emphasized text, subheadings, and interactive elements within body copy. Provides subtle hierarchy in a cohesive family.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 14px | 1.7 | 0.143px | `--text-caption` |
| body | 16px | 1.6 | — | `--text-body` |
| subheading | 18px | 1.8 | — | `--text-subheading` |
| heading-sm | 26px | 1.25 | — | `--text-heading-sm` |
| heading | 36px | 1.22 | -0.48px | `--text-heading` |
| heading-lg | 48px | 1.13 | -0.96px | `--text-heading-lg` |
| display | 80px | 1 | -3.2px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 8px

**Density:** spacious

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
| 80 | 80px | `--spacing-80` |
| 120 | 120px | `--spacing-120` |
| 160 | 160px | `--spacing-160` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 48px |
| other | 20px |
| buttons | 8px |
| navigation | 40px |

### Layout

- **Page max-width:** 1233px
- **Section gap:** 80px
- **Card padding:** 0px
- **Element gap:** 8-16px

## Components

### Primary Call to Action Button
**Role:** Primary interactive element.

Text: Ghost White. Background: Grape Soda (#5423e7). Border Radius: 8px. Padding: 9px top/bottom, 30px left/right. Font: Inter 400, 16px.

### Outline Button - Default
**Role:** Secondary and tertiary actions.

Text: Midnight Ink (#121217). Background: transparent. Border: 1px solid Midnight Ink (#121217). Border Radius: 8px. Padding: 9px top/bottom, 30px left/right. Font: Inter 400, 16px.

### Outline Button - Ocean Deep
**Role:** Informational or complementary actions.

Text: Ocean Deep (#0075ad). Background: transparent. Border: 1px solid Ocean Deep (#0075ad). Border Radius: 8px. Padding: 40px all. Font: Inter 400, 16px.

### Outline Button - Forest Canopy
**Role:** Positive or confirmation actions.

Text: Forest Canopy (#1e874c). Background: transparent. Border: 1px solid Forest Canopy (#1e874c). Border Radius: 8px. Padding: 40px all. Font: Inter 400, 16px.

### Hero Section Headline
**Role:** Main page title or key marketing message.

Text: Ghost White (#ffffff). Font: Circularpro Book 400, 80px, line-height 1.0, letter-spacing -0.04em. Background: Grape Soda (#5423e7).

### Navigation Link
**Role:** Primary navigation items.

Text: Midnight Ink (#121217). Font: Inter 400, 16px. No underline. Hover state not provided, but implies a slight color change or underline.

## Do's and Don'ts

### Do
- Use Grape Soda (#5423e7) for strong background statements or primary branding blocks.
- Apply Lemon Zest (#ffc233) for high-impact alerts or secondary interactive elements.
- Employ Circularpro Book 400 with negative letter spacing for all headings and display text to achieve a distinctive visual voice.
- Maintain high contrast text with Midnight Ink (#121217) on light backgrounds and Ghost White (#ffffff) on dark backgrounds.
- Use Inter font for all body copy and UI elements to ensure readability across sizes, varying weights for hierarchy.
- Apply 8px border-radius consistently for all interactive buttons and smaller UI elements.
- Utilize 48px border-radius for larger, distinct elements such as feature cards or graphical containers to soften their appearance.

### Don't
- Avoid using primary brand colors (Grape Soda, Lemon Zest) for extensive body copy; refer to Midnight Ink or Driftwood for readability.
- Do not use box shadows for elevation; rely on color changes and Ghost White (#ffffff) backgrounds to differentiate content blocks.
- Do not introduce additional font families; adhere strictly to Inter and Circularpro Book.
- Avoid arbitrary color choices; all chromatic colors should derive from the established brand, accent, or semantic palettes.
- Do not use generic button styles; always apply 8px radius and text/background/border combinations from the defined button variants.
- Do not add additional visual ornamentation or gradients; the design relies on bold color blocks and typographic expressiveness.
- Avoid deviating from the established spacing scale (multiples of 8px) for consistent visual rhythm.

## Imagery

The visual language is characterized by realistic product mockups (e.g., tablet showing the dashboard UI) floating in space on vibrant brand-colored backgrounds. These are contained, sharp-edged, and serve to directly showcase product functionality rather than create an abstract mood. Icons, where visible, are simple, monochromatic, and outlined, appearing frequently in navigation or feature lists. Photography is notably absent, reinforcing the focus on the digital product itself. The overall density is text-dominant in feature sections, with hero areas relying on bold typography and a single product visual.

## Layout

The page primarily uses a max-width contained layout (1233px) with content centered. The hero section, however, breaks this pattern with a full-bleed Grape Soda (#5423e7) background, featuring a large, centered headline and a prominent product mockup. Section rhythm alternates between large, full-bleed color blocks (Grape Soda) and clean, white or slightly tinted (#feecfb) backgrounds for content sections. Content arrangement typically follows a clear vertical stacking or alternating two-column layout (text on left, visual/icon on right, or vice-versa). Vertical spacing between sections is generous, creating a spacious and breathable feel. Navigation is a sticky top bar with primary links and a 'Get Started' CTA, positioned on the right.

## Agent Prompt Guide

### Quick Color Reference
- **Text Primary:** #121217 (Midnight Ink)
- **Background Primary:** #ffffff (Ghost White)
- **CTA Background:** #5423e7 (Grape Soda)
- **CTA Text:** #ffffff (Ghost White)
- **Accent:** #ffc233 (Lemon Zest)
- **Border:** #121217 (Midnight Ink) for outlined buttons

### Example Component Prompts
1. **Create a Hero Section:** Full-bleed Grape Soda (#5423e7) background. Centered headline 'Payments, tax & subscriptions for software companies' using Circularpro Book 400, 80px, line-height 1.0, letter-spacing -3.2px, in Ghost White (#ffffff). Sub-text 'As your merchant of record...' using Inter 400, 18px, line-height 1.8, in Ghost White (#ffffff). Primary Call to Action button ('Get started for free') with Grape Soda background, Ghost White text, 8px radius, 9px top/bottom, 30px left/right padding.
2. **Generate an Announcement Bar:** Background Lemon Zest (#ffc233). Text 'Payout fees sliced — another step towards a better Lemon Squeezy Read more' using Inter 400, 14px, #121217. Height for content is 40px with 16px left/right padding.
3. **Design a Feature Card:** Ghost White (#ffffff) background, with 48px border-radius. Headline 'Global tax compliance' using Circularpro Book 400, 26px, line-height 1.25, #121217. Body text 'We’re your merchant of record...' using Inter 400, 16px, line-height 1.6, #6c6c89. No box-shadow.
4. **Create a Secondary Outline Button:** 'Explore the API' using Inter 400, 16px, #0075ad. Transparent background. 1px solid #0075ad border. 8px border-radius. 9px top/bottom, 30px left/right padding.

## Similar Brands

- **Stripe** — Clean SaaS UI with a strong emphasis on product screenshots and dense information presentation, using a modern sans-serif font.
- **Framer** — Utilizes a single dominant brand color as a high-impact background for hero sections and strong typographic statements with large, custom-feel fonts.
- **Notion** — Clean, spacious, and minimalist UI that relies on clear typography and functional rather than decorative imagery for product explanation.
- **Linear** — Focus on high-contrast text and UI elements on a mostly dark or white background, with a strong emphasis on typography and thoughtful negative space.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-grape-soda: #5423e7;
  --color-lemon-zest: #ffc233;
  --color-forest-canopy: #1e874c;
  --color-ocean-deep: #0075ad;
  --color-ruby-glow: #d50b3;
  --color-bubblegum-pink: #cf75ff;
  --color-midnight-ink: #121217;
  --color-ghost-white: #ffffff;
  --color-driftwood: #6c6c89;
  --color-parchment: #f7f7f8;
  --color-cloud-grey: #d1d1db;
  --color-pink-sugar: #feecfb;

  /* Typography — Font Families */
  --font-circularpro-book: 'Circularpro Book', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.7;
  --tracking-caption: 0.143px;
  --text-body: 16px;
  --leading-body: 1.6;
  --text-subheading: 18px;
  --leading-subheading: 1.8;
  --text-heading-sm: 26px;
  --leading-heading-sm: 1.25;
  --text-heading: 36px;
  --leading-heading: 1.22;
  --tracking-heading: -0.48px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.13;
  --tracking-heading-lg: -0.96px;
  --text-display: 80px;
  --leading-display: 1;
  --tracking-display: -3.2px;

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
  --spacing-80: 80px;
  --spacing-120: 120px;
  --spacing-160: 160px;

  /* Layout */
  --page-max-width: 1233px;
  --section-gap: 80px;
  --card-padding: 0px;
  --element-gap: 8-16px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-2xl: 20px;
  --radius-3xl: 32px;
  --radius-3xl-2: 40px;
  --radius-full: 48px;

  /* Named Radii */
  --radius-cards: 48px;
  --radius-other: 20px;
  --radius-buttons: 8px;
  --radius-navigation: 40px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-grape-soda: #5423e7;
  --color-lemon-zest: #ffc233;
  --color-forest-canopy: #1e874c;
  --color-ocean-deep: #0075ad;
  --color-ruby-glow: #d50b3;
  --color-bubblegum-pink: #cf75ff;
  --color-midnight-ink: #121217;
  --color-ghost-white: #ffffff;
  --color-driftwood: #6c6c89;
  --color-parchment: #f7f7f8;
  --color-cloud-grey: #d1d1db;
  --color-pink-sugar: #feecfb;

  /* Typography */
  --font-circularpro-book: 'Circularpro Book', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.7;
  --tracking-caption: 0.143px;
  --text-body: 16px;
  --leading-body: 1.6;
  --text-subheading: 18px;
  --leading-subheading: 1.8;
  --text-heading-sm: 26px;
  --leading-heading-sm: 1.25;
  --text-heading: 36px;
  --leading-heading: 1.22;
  --tracking-heading: -0.48px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.13;
  --tracking-heading-lg: -0.96px;
  --text-display: 80px;
  --leading-display: 1;
  --tracking-display: -3.2px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-120: 120px;
  --spacing-160: 160px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-2xl: 20px;
  --radius-3xl: 32px;
  --radius-3xl-2: 40px;
  --radius-full: 48px;
}
```

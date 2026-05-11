# Unicorn Studio — Style Reference
> Midnight Command Center

**Theme:** dark

Unicorn Studio uses a dark, luminous aesthetic, reminiscent of a nocturnal command center. The design features deep, rich backgrounds contrasted with muted gray typography and vivid violet accents. Typography is compact and precise, emphasizing clarity in a dense information environment. Components are lightweight with softened corners, and subtle elevation is preferred over stark shadows, creating depth without visual clutter.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#08080a` | `--color-midnight-ink` | Primary page and card backgrounds, deep canvas |
| Twilight Slate | `#0d0d12` | `--color-twilight-slate` | Secondary background surfaces, subtle separation from primary canvas |
| Soft Black | `#17171c` | `--color-soft-black` | Tertiary background surfaces, for nested elements or hover states |
| Ash Gray | `#25252d` | `--color-ash-gray` | Button backgrounds, subtle fill for interactive elements |
| Steel Gray | `#31313a` | `--color-steel-gray` | Subtle button shadow, hairline borders, and dividers |
| Ghostly Gray | `#aeaac0` | `--color-ghostly-gray` | Primary text, prominent links, major headings, borders |
| Muted Silver | `#dad7de` | `--color-muted-silver` | High-contrast text, particularly for body copy and button text on dark backgrounds |
| Subtle Charcoal | `#8b8e9c` | `--color-subtle-charcoal` | Secondary text, muted links, subtle element borders |
| Faded Stone | `#62626f` | `--color-faded-stone` | Tertiary text, helper text, and less prominent borders |
| Cosmic Violet | `radial-gradient(circle, rgb(142, 108, 228), rgb(114, 79, 201))` | `--color-cosmic-violet` | Branding, key accents, focus rings, subtle background gradient touches; Background radial gradient, creating a focal point or immersive hero effect |
| Starlight Violet | `#ab8ff1` | `--color-starlight-violet` | Interactive element borders and hover states, providing a lighter accent |
| Midnight Violet | `#8960f0` | `--color-midnight-violet` | Interactive element borders for active/hover states, indicating interaction |

## Tokens — Typography

### Overused Grotesk — Display headings and primary marketing copy. Its tight tracking creates a dense, impactful statement. · `--font-overused-grotesk`
- **Substitute:** Inter
- **Weights:** 400, 500
- **Sizes:** 26px, 32px, 48px, 64px, 215px
- **Line height:** 0.99, 1.00
- **Letter spacing:** -0.0630em at 215px, -0.0400em at 64px, -0.0300em at 48px
- **Role:** Display headings and primary marketing copy. Its tight tracking creates a dense, impactful statement.

### Sprat — Secondary display headings, used sparingly for emphasis or unique section titles. Its condensed nature provides a distinct contrast. · `--font-sprat`
- **Substitute:** Anton
- **Weights:** 500
- **Sizes:** 46px, 61px
- **Line height:** 1.00
- **Letter spacing:** -0.0420em at 61px
- **Role:** Secondary display headings, used sparingly for emphasis or unique section titles. Its condensed nature provides a distinct contrast.

### -apple-system — All body text, links, buttons, and general UI elements. Prioritizes legibility and system consistency for functional text. · `--font-apple-system`
- **Substitute:** Inter
- **Weights:** 400, 500, 600
- **Sizes:** 13px, 14px, 16px, 18px
- **Line height:** 1.20, 1.40
- **Letter spacing:** -0.0100em
- **Role:** All body text, links, buttons, and general UI elements. Prioritizes legibility and system consistency for functional text.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 13px | 1.2 | -0.13px | `--text-caption` |
| body | 16px | 1.4 | -0.16px | `--text-body` |
| subheading | 18px | 1.2 | -0.18px | `--text-subheading` |
| heading-sm | 26px | 0.99 | -0.78px | `--text-heading-sm` |
| heading | 32px | 0.99 | -1.28px | `--text-heading` |
| heading-lg | 46px | 1 | -1.93px | `--text-heading-lg` |
| display | 64px | 0.99 | -2.56px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 5 | 5px | `--spacing-5` |
| 6 | 6px | `--spacing-6` |
| 8 | 8px | `--spacing-8` |
| 10 | 10px | `--spacing-10` |
| 12 | 12px | `--spacing-12` |
| 14 | 14px | `--spacing-14` |
| 15 | 15px | `--spacing-15` |
| 18 | 18px | `--spacing-18` |
| 19 | 19px | `--spacing-19` |
| 20 | 20px | `--spacing-20` |
| 30 | 30px | `--spacing-30` |
| 40 | 40px | `--spacing-40` |
| 60 | 60px | `--spacing-60` |
| 96 | 96px | `--spacing-96` |
| 100 | 100px | `--spacing-100` |
| 118 | 118px | `--spacing-118` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 3px |
| cards | 10px |
| buttons | 3px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| sm | `rgba(0, 0, 0, 0.25) 0px 1px 4px 0px` | `--shadow-sm` |
| sm-2 | `rgba(0, 0, 0, 0.4) 0px 2px 4px -1.5px` | `--shadow-sm-2` |
| subtle | `rgb(49, 49, 58) 0px -1px 0px 0px` | `--shadow-subtle` |

### Layout

- **Page max-width:** 1440px
- **Section gap:** 96px
- **Card padding:** 30px
- **Element gap:** 20px

## Components

### Filled Action Button
**Role:** Primary Call to Action

Uses `Ash Gray` background (#25252d) with `Muted Silver` text (#dad7de). Has a `3px` border-radius and `6px` vertical, `12px` horizontal padding. A subtle `Steel Gray` (#31313a) inset shadow provides minimal depth.

### Outlined Button (Primary)
**Role:** Secondary action or link with brand emphasis

Text in system font, `Muted Silver` (#dad7de) on hover becomes `Starlight Violet` (#ab8ff1). Displays a `Starlight Violet` (#ab8ff1) border that shifts to `Midnight Violet` (#8960f0) on hover. `3px` border-radius, `6px` vertical, `12px` horizontal padding.

### Navigation Link
**Role:** Top navigation and inline links

Uses system font, `Ghostly Gray` text (#aeaac0) and `3px` border-radius. On hover, the text color subtly brightens and a `Starlight Violet` (#ab8ff1) border appears, transitioning to `Midnight Violet` (#8960f0) on active/focus.

### Content Card
**Role:** Container for features, testimonials, or product modules

Background is `Midnight Ink` (#08080a) with a `10px` border-radius and `30px` padding on all sides. No visible box shadow, relies on background contrast for separation.

### Info Tag
**Role:** Small, informative labels, often used for status or categories

Background can be inherited or `Ash Gray` (#25252d), with `Ghostly Gray` text (#aeaac0). Features `3px` border-radius and minimal padding (e.g., `5px` vertical, `10px` horizontal).

### Highlighted Text Link
**Role:** Inline text links within body copy that require visual emphasis

Text color defaults to `Muted Silver` (#dad7de) and gains a subtle `Starlight Violet` (#ab8ff1) underline on hover.

### Minimal Card
**Role:** Smaller content containers, often in grids

Background is `Twilight Slate` (#0d0d12) or `Soft Black` (#17171c), with `10px` border-radius. Padding of `15px` to `20px` to maintain a lighter feel.

## Do's and Don'ts

### Do
- Prioritize `Midnight Ink` (#08080a) for most backgrounds and `Ghostly Gray` (#aeaac0) or `Muted Silver` (#dad7de) for primary text to maintain the dark theme contrast.
- Use `Cosmic Violet` (#8e6ce4) and its lighter/darker variants (`Starlight Violet` #ab8ff1, `Midnight Violet` #8960f0) exclusively for calls to action, interactive states, and brand highlights.
- Apply a `3px` border-radius to all interactive elements like buttons and input fields for a consistent soft-edged feel.
- Headlines should leverage 'Overused Grotesk' with tight negative letter-spacing (`-0.0630em` for display sizes) to create a compact, commanding presence.
- Maintain comfortable 'elementGap' of `20px` and generous 'cardPadding' of `30px` to ensure spaciousness within components on the dark canvas.
- Use the system font `-apple-system` for all body text, links, and minor UI elements, ensuring maximum legibility and consistency across platforms.
- Employ the `Nebula Glow` radial gradient as a background for hero sections or prominent visual areas to inject dynamic brand color.

### Don't
- Avoid using bright or overly saturated colors outside the `Cosmic Violet` palette; maintain a subdued, near-achromatic color scheme for backgrounds and secondary elements.
- Do not use heavy, opaque box-shadows; prefer subtle elevation using `Steel Gray` (#31313a) for inset shadows, or rely on background color changes for hierarchy.
- Do not use generic, default system font styles for headlines; always apply 'Overused Grotesk' or 'Sprat' with their specific weights and letter-spacing for brand identity.
- Avoid excessive use of borders on non-interactive elements; rely on background color variations and padding to define areas.
- Do not break the `10px` border-radius for cards and `3px` for buttons/links; these radii are key to the system's character.
- Don't clutter the layout; maintain clear section gaps of `96px` and max-width constraints of `1440px` for a focused content experience.
- Never use `solid black (#000000)` or `solid white (#ffffff)` for primary text or backgrounds, as the system relies on subtle dark grays and light grays for its nuanced palette.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Midnight Ink | `#08080a` | Base page background and primary card surface. |
| 1 | Twilight Slate | `#0d0d12` | Slightly elevated background for secondary content blocks or modals. |
| 2 | Soft Black | `#17171c` | Further elevated background, often used for nested UI components or hover states. |
| 3 | Ash Gray | `#25252d` | Interactive element backgrounds like buttons, providing a distinct clickable area. |

## Elevation

- **Card Shadow:** `rgba(0, 0, 0, 0.25) 0px 1px 4px 0px`
- **Callout / Feature Shadow:** `rgba(0, 0, 0, 0.4) 0px 2px 4px -1.5px`
- **Button Inset Shadow:** `rgb(49, 49, 58) 0px -1px 0px 0px`

## Imagery

This design system uses atmospheric, abstract imagery, primarily featuring a 'Nebula Glow' radial gradient that serves as a background for large sections or hero areas. The visuals are typically full-bleed, blending seamlessly into the dark background, or contained within cards with rounded corners. There is a strong absence of photography, relying instead on 3D rendered, luminous forms that evoke magic and technology. Icons are minimal, subtle, and outlined, matching the overall subdued and sophisticated tone. Imagery density is low, primarily used for large focal points rather than numerous small elements, allowing text to dominate information delivery.

## Layout

The page primarily uses a max-width contained layout of `1440px`, centered on the screen, though the hero section extends full-bleed with its background imagery. The hero features a centered headline over the background gradient. Section rhythm is driven by consistent vertical spacing of `96px` with no alternating light/dark bands, consistent with the dark theme. Content within sections tends towards centered stacks or `2-column` arrangements, particularly for text-heavy feature blocks. There's occasional use of a 3-column grid for pricing or feature listings. The overall density is comfortable, with ample breathing room between content blocks. Navigation is a sticky top bar, minimally styled with outlined ghost links and a single primary filled button.

## Agent Prompt Guide

Quick Color Reference:
text: #aeaac0
background: #08080a
border: #31313a
accent: #8e6ce4
primary action: #25252d (filled action)

Example Component Prompts:
Create a hero section: radial-gradient(circle, #8e6ce4, #724fc9) background. Headline at 64px Overused Grotesk weight 400, #aeaac0, letter-spacing -2.56px. Subtext at 16px -apple-system weight 400, #dad7de, letter-spacing -0.16px. Centered Filled Action Button: #25252d background, #dad7de text, 3px radius, 6px 12px padding.

Create a feature card: #08080a background, 10px radius, 30px padding. Headline at 32px Overused Grotesk weight 400, #aeaac0, letter-spacing -1.28px. Body text at 14px -apple-system weight 400, #8b8e9c, letter-spacing -0.14px.

Create an outlined button: #8b8e9c text, 1px #ab8ff1 border, 3px radius, 6px 12px padding, -apple-system font family, 14px size, 500 weight, normal letter spacing. On hover, text changes to #ab8ff1 and border changes to #8960f0.

Create a basic text input field: `Twilight Slate` (#0d0d12) background, `Ghostly Gray` (#aeaac0) text, `Steel Gray` (#31313a) 1px border, `3px` border-radius. `10px` padding. Focus state adds a `Cosmic Violet` (#8e6ce4) 2px border.

## Similar Brands

- **Stripe** — Shares the use of vivid gradients for brand identity alongside a dark, spacious UI with clean typography.
- **Framer** — Exhibits a similar design-tool aesthetic with a focus on dark mode, subtle grays, and precise, compact typography.
- **Linear** — Aligns with the 'midnight command center' feel, employing a dark theme, functional typography, and judicious use of accent colors for interaction.
- **Supabase** — Employs a dark, sophisticated UI with ample spacing, strong typography, and a strategic, limited color palette for accents.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #08080a;
  --color-twilight-slate: #0d0d12;
  --color-soft-black: #17171c;
  --color-ash-gray: #25252d;
  --color-steel-gray: #31313a;
  --color-ghostly-gray: #aeaac0;
  --color-muted-silver: #dad7de;
  --color-subtle-charcoal: #8b8e9c;
  --color-faded-stone: #62626f;
  --color-cosmic-violet: #8e6ce4;
  --gradient-cosmic-violet: radial-gradient(circle, rgb(142, 108, 228), rgb(114, 79, 201));
  --color-starlight-violet: #ab8ff1;
  --color-midnight-violet: #8960f0;

  /* Typography — Font Families */
  --font-overused-grotesk: 'Overused Grotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sprat: 'Sprat', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-apple-system: '-apple-system', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 1.2;
  --tracking-caption: -0.13px;
  --text-body: 16px;
  --leading-body: 1.4;
  --tracking-body: -0.16px;
  --text-subheading: 18px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.18px;
  --text-heading-sm: 26px;
  --leading-heading-sm: 0.99;
  --tracking-heading-sm: -0.78px;
  --text-heading: 32px;
  --leading-heading: 0.99;
  --tracking-heading: -1.28px;
  --text-heading-lg: 46px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -1.93px;
  --text-display: 64px;
  --leading-display: 0.99;
  --tracking-display: -2.56px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-14: 14px;
  --spacing-15: 15px;
  --spacing-18: 18px;
  --spacing-19: 19px;
  --spacing-20: 20px;
  --spacing-30: 30px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-96: 96px;
  --spacing-100: 100px;
  --spacing-118: 118px;

  /* Layout */
  --page-max-width: 1440px;
  --section-gap: 96px;
  --card-padding: 30px;
  --element-gap: 20px;

  /* Border Radius */
  --radius-sm: 3px;
  --radius-md: 6px;
  --radius-lg: 10px;

  /* Named Radii */
  --radius-tags: 3px;
  --radius-cards: 10px;
  --radius-buttons: 3px;

  /* Shadows */
  --shadow-sm: rgba(0, 0, 0, 0.25) 0px 1px 4px 0px;
  --shadow-sm-2: rgba(0, 0, 0, 0.4) 0px 2px 4px -1.5px;
  --shadow-subtle: rgb(49, 49, 58) 0px -1px 0px 0px;

  /* Surfaces */
  --surface-midnight-ink: #08080a;
  --surface-twilight-slate: #0d0d12;
  --surface-soft-black: #17171c;
  --surface-ash-gray: #25252d;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #08080a;
  --color-twilight-slate: #0d0d12;
  --color-soft-black: #17171c;
  --color-ash-gray: #25252d;
  --color-steel-gray: #31313a;
  --color-ghostly-gray: #aeaac0;
  --color-muted-silver: #dad7de;
  --color-subtle-charcoal: #8b8e9c;
  --color-faded-stone: #62626f;
  --color-cosmic-violet: #8e6ce4;
  --color-starlight-violet: #ab8ff1;
  --color-midnight-violet: #8960f0;

  /* Typography */
  --font-overused-grotesk: 'Overused Grotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sprat: 'Sprat', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-apple-system: '-apple-system', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 1.2;
  --tracking-caption: -0.13px;
  --text-body: 16px;
  --leading-body: 1.4;
  --tracking-body: -0.16px;
  --text-subheading: 18px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.18px;
  --text-heading-sm: 26px;
  --leading-heading-sm: 0.99;
  --tracking-heading-sm: -0.78px;
  --text-heading: 32px;
  --leading-heading: 0.99;
  --tracking-heading: -1.28px;
  --text-heading-lg: 46px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -1.93px;
  --text-display: 64px;
  --leading-display: 0.99;
  --tracking-display: -2.56px;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-14: 14px;
  --spacing-15: 15px;
  --spacing-18: 18px;
  --spacing-19: 19px;
  --spacing-20: 20px;
  --spacing-30: 30px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-96: 96px;
  --spacing-100: 100px;
  --spacing-118: 118px;

  /* Border Radius */
  --radius-sm: 3px;
  --radius-md: 6px;
  --radius-lg: 10px;

  /* Shadows */
  --shadow-sm: rgba(0, 0, 0, 0.25) 0px 1px 4px 0px;
  --shadow-sm-2: rgba(0, 0, 0, 0.4) 0px 2px 4px -1.5px;
  --shadow-subtle: rgb(49, 49, 58) 0px -1px 0px 0px;
}
```

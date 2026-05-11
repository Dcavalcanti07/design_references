# Twitch — Style Reference
> Gaming stage in neon light - white-grey backdrop bathed in purple glow, with urgent red accents.

**Theme:** light

Twitch presents a vibrant, high-energy streaming platform built on a light canvas. Its visual identity balances functional clarity with dynamic accents. The dominant bright purple, used for primary CTAs and key highlights, injects brand personality into an otherwise neutral interface. A subtle use of layered grays and crisp typography ensures content remains the focal point, while bold status indicators ('LIVE' badge) cut through the visual noise.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Cloud Canvas | `#efeff1` | `--color-cloud-canvas` | Page backgrounds, subtle surface variations, muted navigation backgrounds. |
| Ghost White | `#ffffff` | `--color-ghost-white` | Primary surface for cards, modals, interactive element backgrounds. |
| Nightfall Text | `#0e0e10` | `--color-nightfall-text` | Primary text, headings, strong interactive elements. Establishes core legibility against light backgrounds. |
| Slate Echo | `#3b3b44` | `--color-slate-echo` | Secondary text, muted links, subtle borders. |
| Ash Gray | `#636363` | `--color-ash-gray` | Tertiary text, less prominent icons, background for content overlays. |
| Iron Border | `#dddde2` | `--color-iron-border` | Subtle borders and dividers for interactive elements and structural separation. |
| Airtight Black | `#000000` | `--color-airtight-black` | Iconography, strong dividers, rare high-contrast backgrounds, for text on specific interactive elements. |
| Twitch Purple | `#5c16c5` | `--color-twitch-purple` | Main accent color for active navigation states, primary call-to-action buttons, and interactive elements. Its vividness drives user engagement. |
| Deep Twitch Purple | `#330c6` | `--color-deep-twitch-purple` | Darker shade of Twitch purple used for backgrounds of promotional banners or footer elements. |
| Rich Twitch Purple | `#451093` | `--color-rich-twitch-purple` | Backgrounds for specific highlighted cards or featured sections, providing visual weight. |
| Call-to-Action Purple | `#9147ff` | `--color-call-to-action-purple` | Used for 'Sign Up' buttons and other prominent interactive elements, a brighter variant of the brand purple. |
| Live Red | `#eb0400` | `--color-live-red` | Urgent status indicator for live streams and critical alerts. Its high contrast demands immediate attention. |
| Highlight Pink | `#ff75e6` | `--color-highlight-pink` | Occasional background for special badges or highly emphasized text, adding vibrant flair. |
| Stream Yellow | `#ffd000` | `--color-stream-yellow` | Secondary accent for occasional highlights or decorative elements. |

## Tokens — Typography

### Inter — General body text, navigation items, badges, captions, and most UI elements. Its neutrality allows content to dominate. · `--font-inter`
- **Substitute:** system-ui
- **Weights:** 400, 600
- **Sizes:** 11px, 12px, 14px
- **Line height:** 1.00, 1.10, 1.20, 1.40, 1.50, 1.60
- **Role:** General body text, navigation items, badges, captions, and most UI elements. Its neutrality allows content to dominate.

### Roobert — For key headings and prominent links, where a slightly more custom, structured feel is desired. The moderate letter-spacing creates a compact, modern appearance. · `--font-roobert`
- **Substitute:** system-ui
- **Weights:** 400, 500, 600
- **Sizes:** 14px, 18px
- **Line height:** 1.10, 1.40
- **Letter spacing:** -0.01
- **Role:** For key headings and prominent links, where a slightly more custom, structured feel is desired. The moderate letter-spacing creates a compact, modern appearance.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 11px | 1.4 | — | `--text-caption` |
| body-sm | 12px | 1.4 | — | `--text-body-sm` |
| body | 14px | 1.4 | — | `--text-body` |

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
| 40 | 40px | `--spacing-40` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 9000px |
| cards | 4px |
| input | 4px |
| avatars | 9000px |
| buttons | 9000px |
| liveBadge | 2px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| md | `rgba(0, 0, 0, 0.22) 0px 6px 16px 0px, rgba(0, 0, 0, 0.08)...` | `--shadow-md` |
| subtle | `rgba(0, 0, 0, 0.13) 0px 1px 2px 0px, rgba(0, 0, 0, 0.08) ...` | `--shadow-subtle` |
| subtle-2 | `rgba(50, 50, 57, 0.62) 0px 0px 0px 1px inset` | `--shadow-subtle-2` |

### Layout

- **Section gap:** 40px
- **Card padding:** 16px
- **Element gap:** 8px

## Components

### Primary Navigation Link
**Role:** Interactive element

Text in Nightfall Text (#0e0e10), defaulting to Ghost White (#ffffff) background. Active state uses Twitch Purple (#5c16c5) for text/icon, or a subtle background highlight of Cloud Canvas (#efeff1). No explicit padding when embedded in a nav bar.

### Pill Button (Text Only)
**Role:** Secondary action button

Background is transparent (rgba(0,0,0,0)), text is Nightfall Text (#0e0e10). Rounded corners at 9000px. Used for contextual actions within larger blocks.

### Pill Button (Ghost White Text)
**Role:** Prominent action button on dark backgrounds

Background is transparent (rgba(0,0,0,0)). Text color is Ghost White (#ffffff). Rounded corners at 9000px. Used for 'Sign Up' against a purple background.

### Pill Button (Muted Background)
**Role:** Subtle action button

Background is a muted rgba(173,173,184,0.22). Text color is Nightfall Text (#0e0e10). Rounded corners at 9000px. Used for less emphasized actions.

### Video Preview Card
**Role:** Content display

Background is transparent (rgba(0,0,0,0)), no border radius or shadow by default. Displays video thumbnail with overlaid information.

### Video Player Card
**Role:** Interactive content display

Background is muted rgba(173,173,184,0.22), no explicit radius or shadow. Contains the primary video player.

### Video Overlay Label
**Role:** Informative overlay

Small, dark overlay with a background of rgba(0,0,0,0.6) and a 2px border-radius. Text in Ghost White (#ffffff). Used for 'LIVE' or viewer counts on video thumbnails, with 4px horizontal padding.

### Channel Avatar (Circular)
**Role:** User identification

Circular image container with 9000px border-radius, often containing a user's profile picture or channel icon. Background is transparent.

### Live Indicator Badge
**Role:** Status indicator

Small, rectangular badge with a Live Red (#eb0400) background. Text is Ghost White (#ffffff), often paired with 'LIVE' text to denote active streams. No explicit radius, appears as sharp corners.

### Search Input Field
**Role:** User input

Ghost White (#ffffff) background with a 1px Iron Border (#dddde2). Placeholder text is Slate Echo (#3b3b44) in Inter 14px. No explicit border radius, appears with sharp corners.

### Promotional Footer Banner
**Role:** Marketing banner

Full-width background of Twitch Purple (#5c16c5) or a darker Deep Twitch Purple (#330c6e). Contains Ghost White (#ffffff) text and a 'Sign Up' button variant.

## Do's and Don'ts

### Do
- Use Nightfall Text (#0e0e10) for all primary text elements on Cloud Canvas (#efeff1) or Ghost White (#ffffff) backgrounds.
- Apply Twitch Purple (#5c16c5) or Call-to-Action Purple (#9147ff) exclusively to primary interactive elements, active states, and brand signifiers.
- Employ the 9000px border-radius for all interactive buttons, user avatars, and categorical tags to create a consistent soft, approachable feel.
- Use a Live Red (#eb0400) background combined with Ghost White (#ffffff) text for any 'LIVE' status indicators to ensure immediate visual recognition.
- Maintain a default elementGap of 8px (or multiples thereof like 16px) for consistent vertical and horizontal spacing between discrete UI elements.
- Utilize Roobert font with -0.01em letter-spacing for prominent headings and key links to leverage its distinct, compact character.
- Structure information using a subtle Ghost White (#ffffff) background for primary content cards and Cloud Canvas (#efeff1) for general page areas to create clear visual separation.

### Don't
- Do not use highly saturated colors for large background areas or extensive text blocks, except for designated brand banners.
- Avoid using drop shadows on most UI elements; instead, rely on variations in background color for surface differentiation.
- Do not introduce additional font families or weights beyond Inter (400, 600) and Roobert (400, 500, 600) to maintain typographic consistency.
- Never apply a border-radius of less than 4px, except for the 2px on specific video overlay labels, as most UI elements use 4px or 9000px.
- Do not use red or other semantic colors for primary CTA buttons, as this is exclusively reserved for the Live Red status indicator.
- Avoid large, impactful hero sections that dominate the viewport; prioritize content visibility through dense, card-based layouts.
- Do not use dark backgrounds for the main canvas; the design system operates predominantly on a light theme with specific dark content sections.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Cloud Canvas | `#efeff1` | Base page background |
| 1 | Ghost White | `#ffffff` | Primary content areas, cards, interactive elements |
| 2 | Promotional Purple | `#330c6` | Accentuated banners or footer sections for brand emphasis |

## Elevation

- **Card Shadow High:** `rgba(0, 0, 0, 0.22) 0px 6px 16px 0px, rgba(0, 0, 0, 0.08) 0px 0px 4px 0px`
- **Card Shadow Low:** `rgba(0, 0, 0, 0.13) 0px 1px 2px 0px, rgba(0, 0, 0, 0.08) 0px 0px 2px 0px`
- **Input Focus Inset:** `rgba(50, 50, 57, 0.62) 0px 0px 0px 1px inset`

## Imagery

The site primarily uses product screenshots (video thumbnails) and user avatars. Video thumbnails are presented as raw, unmasked rectangles, often with semi-transparent overlays for 'LIVE' indicators or viewer counts. User avatars are uniformly circular. There's minimal decorative imagery beyond these content-driven visuals. Icons are outlined, monochromatic, and typically a single weight, using Nightfall Text (#0e0e10) unless interactive, where they adopt Twitch Purple (#5c16c5). The density is image-heavy due to video content being central, but the imagery serves an explanatory and content-showcasing role rather than purely decorative.

## Layout

The page uses a maximum content width for its central content, flanked by a fixed-width left sidebar (`Live Channels`) and dynamic main content. The hero section is characterized by a central, elevated video player with supporting contextual information, visually stacked on top of other content. Main content sections ('Live on Twitch') are arranged in a multi-column grid of video cards. Vertical rhythm is established by consistent section gaps. Navigation is a persistent top bar and a fixed sidebar. The overall layout is dense with information, prioritizing content display through a clear grid structure and minimal whitespace between content blocks.

## Agent Prompt Guide

### Quick Color Reference
- **Primary Text:** #0e0e10 (Nightfall Text)
- **Page Background:** #efeff1 (Cloud Canvas)
- **Interactive Accent:** #5c16c5 (Twitch Purple)
- **Live Status:** #eb0400 (Live Red)
- **Card Background:** #ffffff (Ghost White)
- **Border/Divider:** #dddde2 (Iron Border)

### 3-5 Example Component Prompts
1. **Create a primary navigation item:** Text 'Browse' in Nightfall Text (#0e0e10), Inter 14px weight 400. On hover, change text color to Twitch Purple (#5c16c5).
2. **Generate a 'Sign Up' button:** Background Call-to-Action Purple (#9147ff), text Ghost White (#ffffff), Roobert 14px weight 600, border-radius 9000px, 8px padding on all sides. 
3. **Design a live stream video card:** Use transparent background (rgba(0,0,0,0)). Display a video thumbnail, overlay with 'LIVE' badge (Live Red #eb0400 background, Ghost White #ffffff text, Inter 11px weight 600) in the top left. Below, include channel name in Nightfall Text (#0e0e10) Roobert 14px weight 500, and game title in Slate Echo (#3b3b44) Inter 12px weight 400.
4. **Create a search input field:** Ghost White (#ffffff) background, 1px solid Iron Border (#dddde2). Placeholder text 'Search' in Slate Echo (#3b3b44), Inter 14px weight 400. No border-radius.
5. **Build a user sidebar entry:** Channel avatar (9000px radius), followed by channel name in Nightfall Text (#0e0e10) Inter 14px weight 400. Stream viewer count in Live Red (#eb0400) Inter 11px weight 600.

## Similar Brands

- **YouTube** — Centralized video content platform, with a focus on 'live' indicators and distinct rectangular video cards on a light background.
- **Discord** — Platform heavily reliant on user-generated content, with distinct channel lists, avatar-based user representation, and accent colors for status/interaction.
- **Riot Games** — Brand identity often uses purple and red accents, similar to Twitch's chromatic palette. Focus on game content and player communities.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-cloud-canvas: #efeff1;
  --color-ghost-white: #ffffff;
  --color-nightfall-text: #0e0e10;
  --color-slate-echo: #3b3b44;
  --color-ash-gray: #636363;
  --color-iron-border: #dddde2;
  --color-airtight-black: #000000;
  --color-twitch-purple: #5c16c5;
  --color-deep-twitch-purple: #330c6;
  --color-rich-twitch-purple: #451093;
  --color-call-to-action-purple: #9147ff;
  --color-live-red: #eb0400;
  --color-highlight-pink: #ff75e6;
  --color-stream-yellow: #ffd000;

  /* Typography — Font Families */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-roobert: 'Roobert', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.4;
  --text-body-sm: 12px;
  --leading-body-sm: 1.4;
  --text-body: 14px;
  --leading-body: 1.4;

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
  --spacing-40: 40px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 16px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-full: 9000px;

  /* Named Radii */
  --radius-tags: 9000px;
  --radius-cards: 4px;
  --radius-input: 4px;
  --radius-avatars: 9000px;
  --radius-buttons: 9000px;
  --radius-livebadge: 2px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.22) 0px 6px 16px 0px, rgba(0, 0, 0, 0.08) 0px 0px 4px 0px;
  --shadow-subtle: rgba(0, 0, 0, 0.13) 0px 1px 2px 0px, rgba(0, 0, 0, 0.08) 0px 0px 2px 0px;
  --shadow-subtle-2: rgba(50, 50, 57, 0.62) 0px 0px 0px 1px inset;

  /* Surfaces */
  --surface-cloud-canvas: #efeff1;
  --surface-ghost-white: #ffffff;
  --surface-promotional-purple: #330c6;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-cloud-canvas: #efeff1;
  --color-ghost-white: #ffffff;
  --color-nightfall-text: #0e0e10;
  --color-slate-echo: #3b3b44;
  --color-ash-gray: #636363;
  --color-iron-border: #dddde2;
  --color-airtight-black: #000000;
  --color-twitch-purple: #5c16c5;
  --color-deep-twitch-purple: #330c6;
  --color-rich-twitch-purple: #451093;
  --color-call-to-action-purple: #9147ff;
  --color-live-red: #eb0400;
  --color-highlight-pink: #ff75e6;
  --color-stream-yellow: #ffd000;

  /* Typography */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-roobert: 'Roobert', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.4;
  --text-body-sm: 12px;
  --leading-body-sm: 1.4;
  --text-body: 14px;
  --leading-body: 1.4;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-40: 40px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-full: 9000px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.22) 0px 6px 16px 0px, rgba(0, 0, 0, 0.08) 0px 0px 4px 0px;
  --shadow-subtle: rgba(0, 0, 0, 0.13) 0px 1px 2px 0px, rgba(0, 0, 0, 0.08) 0px 0px 2px 0px;
  --shadow-subtle-2: rgba(50, 50, 57, 0.62) 0px 0px 0px 1px inset;
}
```

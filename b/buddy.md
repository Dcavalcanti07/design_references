# Buddy — Style Reference
> Crisp digital blueprint

**Theme:** light

Buddy Works presents a clean, pragmatic SaaS identity with a dominant white canvas contrasting dark, bold typography. The system utilizes subtle grays for component borders and secondary text, punctuated by a vibrant lime green for calls to action, creating a sense of efficiency and clarity. Light shadows with subtle color tints from the brand palette add depth without heaviness. The overall visual tone is structured and functional, with an emphasis on readable information hierarchy and quick identification of interactive elements.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#1d2130` | `--color-midnight-ink` | Primary text, deep gray borders, dark accents for UI elements |
| Cloud White | `#fcfcfd` | `--color-cloud-white` | Primary page background, card surfaces, ghost button backgrounds |
| Slate Gray | `#d5d9e8` | `--color-slate-gray` | Muted borders, subtle text for supporting information, light shadows |
| Frost | `#ebeef7` | `--color-frost` | Subtle borders, list item backgrounds, fills for inactive states |
| Coal Black | `#151720` | `--color-coal-black` | Darkest text for prominent headings, high-contrast icons |
| Deep Space | `#0a0d16` | `--color-deep-space` | Ultra-dark text for hero headlines, strong icon fills |
| Sky Dust | `#d8fbed` | `--color-sky-dust` | Very faint background wash, decorative fills, subtle highlights |
| Emerald Echo | `#0b3d28` | `--color-emerald-echo` | Green outline accent for tags, dividers, and focused UI edges |
| Sour Apple | `#bfff5a` | `--color-sour-apple` | Green action color for filled buttons, selected navigation states, and focused conversion moments |
| Hydro Blue | `#1a67fd` | `--color-hydro-blue` | Violet text accent for links, tags, and emphasized short phrases. Do not promote it to the primary CTA color |
| Sunny Glow | `radial-gradient(100% 100% at 50% 0px, rgb(255, 216, 136) 0%, rgb(255, 198, 80) 100%)` | `--color-sunny-glow` | Feedback card background, decorative gradient for emphasis |
| Pink Sugar | `radial-gradient(100% 100% at 50% 0px, rgb(255, 181, 241) 0%, rgb(255, 157, 236) 100%)` | `--color-pink-sugar` | Decorative gradient for thematic sections or elements |
| Volt Yellow | `radial-gradient(100% 100% at 50% 0px, rgb(236, 241, 116) 0%, rgb(229, 237, 56) 100%)` | `--color-volt-yellow` | Decorative gradient for thematic sections or elements |
| Mint Blast | `radial-gradient(100% 100% at 50% 0px, rgb(93, 247, 182) 0%, rgb(25, 247, 154) 100%)` | `--color-mint-blast` | Decorative gradient for thematic sections or elements |
| Sky Surge | `radial-gradient(100% 100% at 50% 0px, rgb(122, 227, 255) 0%, rgb(70, 216, 255) 100%)` | `--color-sky-surge` | Decorative gradient for thematic sections or elements |

## Tokens — Typography

### IBM Plex Sans — Used for all primary text, navigation, body copy, and headings. Variable weights maintain contrast and hierarchy, with tighter tracking on larger display sizes for impact while maintaining legibility on smaller text. · `--font-ibm-plex-sans`
- **Substitute:** Inter
- **Weights:** 400, 500, 600, 700
- **Sizes:** 13px, 14px, 16px, 17px, 18px, 22px, 48px, 80px
- **Line height:** 0.90, 1.00, 1.33, 1.43, 1.45, 1.50, 1.56, 1.71, 1.85, 1.88, 2.29
- **Letter spacing:** -0.0450em at 80px, -0.0210em at 48px, -0.0120em at 22px and 17px, normal at other sizes
- **OpenType features:** `"liga" 0`
- **Role:** Used for all primary text, navigation, body copy, and headings. Variable weights maintain contrast and hierarchy, with tighter tracking on larger display sizes for impact while maintaining legibility on smaller text.

### IBM Plex Mono — Monospaced font for code snippets, technical terms, and labels where fixed-width aesthetic is desired. · `--font-ibm-plex-mono`
- **Substitute:** Fira Code
- **Weights:** 500
- **Sizes:** 12px
- **Line height:** 2.00
- **Letter spacing:** 0.1670em
- **OpenType features:** `"liga" 0`
- **Role:** Monospaced font for code snippets, technical terms, and labels where fixed-width aesthetic is desired.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 13px | 1.71 | — | `--text-caption` |
| heading | 22px | 1.33 | -0.264px | `--text-heading` |
| heading-lg | 48px | 1 | -0.96px | `--text-heading-lg` |
| display | 80px | 0.9 | -3.6px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 8px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 8 | 8px | `--spacing-8` |
| 16 | 16px | `--spacing-16` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 72 | 72px | `--spacing-72` |
| 96 | 96px | `--spacing-96` |
| 120 | 120px | `--spacing-120` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 24px |
| images | 8px |
| buttons | 56px |
| navItems | 44px |
| textContainers | 9999px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(29, 33, 48, 0.04) 0px 3px 3px -1px, rgba(29, 33, 48,...` | `--shadow-subtle` |
| subtle-2 | `rgba(255, 255, 255, 0.72) 0px 1px 0px 0px inset, rgba(29,...` | `--shadow-subtle-2` |
| subtle-3 | `rgba(255, 255, 255, 0.72) 0px 0px 0px 1px inset, rgb(213,...` | `--shadow-subtle-3` |
| subtle-4 | `rgba(29, 33, 48, 0.08) 0px 0px 0px 1px, rgba(29, 33, 48, ...` | `--shadow-subtle-4` |
| subtle-5 | `rgba(29, 33, 48, 0.08) 0px 0px 0px 1px, rgba(29, 33, 48, ...` | `--shadow-subtle-5` |
| subtle-6 | `rgba(29, 33, 48, 0.08) 0px 0px 0px 1px, rgba(29, 33, 48, ...` | `--shadow-subtle-6` |
| subtle-7 | `rgba(29, 33, 48, 0.08) 0px 0px 0px 1px, rgba(29, 33, 48, ...` | `--shadow-subtle-7` |
| subtle-8 | `rgba(29, 33, 48, 0.08) 0px 0px 0px 1px, rgba(29, 33, 48, ...` | `--shadow-subtle-8` |
| subtle-9 | `rgba(29, 33, 48, 0.08) 0px 0px 0px 1px, rgba(29, 33, 48, ...` | `--shadow-subtle-9` |
| subtle-10 | `rgba(29, 33, 48, 0.08) 0px 0px 0px 1px, rgba(29, 33, 48, ...` | `--shadow-subtle-10` |
| subtle-11 | `rgba(17, 17, 17, 0.16) 0px 0px 0px 1px inset, rgba(29, 33...` | `--shadow-subtle-11` |
| subtle-12 | `rgba(17, 17, 17, 0.16) 0px 0px 0px 1px inset, rgba(29, 33...` | `--shadow-subtle-12` |
| subtle-13 | `rgba(17, 17, 17, 0.16) 0px 0px 0px 1px inset, rgba(29, 33...` | `--shadow-subtle-13` |
| subtle-14 | `rgba(17, 17, 17, 0.16) 0px 0px 0px 1px inset, rgba(29, 33...` | `--shadow-subtle-14` |
| subtle-15 | `rgba(17, 17, 17, 0.16) 0px 0px 0px 1px inset, rgba(29, 33...` | `--shadow-subtle-15` |

### Layout

- **Section gap:** 64px
- **Card padding:** 24px
- **Element gap:** 24px

## Components

### Primary Action Button
**Role:** Interactive element

Filled button with 'Sour Apple' (#bfff5a) background and 'Midnight Ink' (#1d2130) text. Uses 56px border-radius, 4px vertical padding, 24px horizontal padding, with a subtle top/bottom shadow.

### Ghost Button
**Role:** Secondary action or navigation

Transparent background with 'Midnight Ink' (#1d2130) border and text. Uses 56px border-radius, 8px vertical padding, 34px horizontal padding.

### Default Card
**Role:** Content container

White background (#fcfcfd) with 14px border-radius and 6px internal padding. No visible shadow, relying on subtle borders for separation.

### Elevated Feature Card
**Role:** Prominent content container

Transparent background with 24px border-radius. Features a 1px 'Midnight Ink' (#1d2130) border and a complex shadow stack hinting at depth, with a subtle 'Sky Surge' (#7ae3ff) blue tint to the lowest shadows.

### Feedback Card
**Role:** Testimonial or distinct message

Uses 'Sunny Glow' (#ffd888) radial gradient background with 'Deep Space' (#0a0d16) text. Features a 24px border-radius, no internal padding. Distinguished by its strong accent color background.

### Navigation Link
**Role:** Primary global and section navigation

Displays 'Midnight Ink' (#1d2130) text on a 'Cloud White' (#fcfcfd) background. On hover or active, it becomes 'Hydro Blue' (#1a67fd). Uses a 44px border-radius for pill-shaped active state indicator.

### Tab Pill
**Role:** Segmented control for content filtering

Pill-shaped containers with a 9999px border radius. Inactive tabs have 'Midnight Ink' (#1d2130) text on a 'Cloud White' (#fcfcfd) background. Active tabs use either a ghost style with 'Midnight Ink' text and border, or a 'Cloud White' background with 'Deep Space' text.

## Do's and Don'ts

### Do
- Use 'Cloud White' (#fcfcfd) as the primary canvas for most sections to maintain a bright, open feel.
- Apply 'Sour Apple' (#bfff5a) exclusively for primary calls to action, drawing immediate attention to key interactive elements.
- Employ 'Midnight Ink' (#1d2130) for primary text content to ensure high readability and crisp contrast.
- Structure layout with a 24px elementGap between distinct UI components and 64px vertical sectionGap for comfortable separation.
- Utilize IBM Plex Sans with a -0.0450em letter-spacing for display headings (80px) and -0.0210em for large headings (48px) to achieve a modern, tight feel for impactful statements.
- Round all primary action buttons and tab pills with a 56px or 9999px radius respectively, emphasizing their interactive nature with soft, approachable edges.
- Elevate significant content blocks (e.g., feature cards) with a 24px border-radius and a full shadow stack tinted with subtle accent colors (e.g. 'Sky Surge' or 'Mint Blast') for a layered effect.

### Don't
- Avoid using highly saturated colors for large background areas; reserve chromatic colors for functional accents and small decorative elements.
- Do not deviate from the specified 'Sour Apple' (#bfff5a) for primary action backgrounds; any other filled chromatic button will feel off-brand.
- Do not introduce new border-radius values; stick to 56px for buttons, 24px for cards, and 9999px for pill-shaped elements.
- Avoid generic box-shadows; when shadows are employed, ensure they include the subtle colored tints specified in the component definitions (e.g., from 'Sky Surge' or 'Sour Apple' family).
- Do not use IBM Plex Mono for standard body text or headlines; its usage is strictly for technical or code-like content to maintain its specialized role.
- Do not introduce heavy borders or background gradients on primary navigation links; maintain their light, ghost-like appearance until active.
- Do not use large, decorative, full-bleed imagery that breaks the UI-focused, 'blueprint' aesthetic.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Cloud White Canvas | `#fcfcfd` | Primary page background, foundation for all content. |
| 1 | Frosted Card | `#fcfcfd` | Default card and container surfaces, subtle lift from canvas using border. |
| 2 | Elevated Accent Surface | `#00000000` | Cards and interactive elements that receive depth through border and tinted shadow. |
| 3 | Feedback Highlight | `#ffd888` | Distinct, highly visible accent surfaces for testimonials or important notices using gradients. |

## Elevation

- **Image container:** `rgba(29, 33, 48, 0.04) 0px 3px 3px -1px, rgba(29, 33, 48, 0.04) 0px 6px 6px -3px, rgba(29, 33, 48, 0.04) 0px 12px 12px -6px, rgba(29, 33, 48, 0.04) 0px 24px 24px -12px, rgba(29, 33, 48, 0.04) 0px 32px 32px -16px`
- **Button:** `rgba(255, 255, 255, 0.72) 0px 1px 0px 0px inset, rgba(29, 33, 48, 0.12) 0px -2px 0px 0px inset, rgba(29, 33, 48, 0.04) 0px 1px 1px -1px, rgba(29, 33, 48, 0.04) 0px 4px 4px -2px`
- **Page content boundary:** `rgba(255, 255, 255, 0.72) 0px 0px 0px 1px inset, rgb(213, 217, 232) 0px 0px 0px 1px, rgba(29, 33, 48, 0.03) 0px 1px 1px -1px, rgba(29, 33, 48, 0.05) 0px 3px 3px -2px, rgba(29, 33, 48, 0.03) 0px 5px 5px -3px, rgba(213, 217, 232, 0.22) 0px 5px 5px -2px`
- **Card with Sky Surge tint:** `rgba(29, 33, 48, 0.08) 0px 0px 0px 1px, rgba(29, 33, 48, 0.04) 0px 1px 1px -1px, rgba(29, 33, 48, 0.04) 0px 2px 2px -1px, rgba(29, 33, 48, 0.04) 0px 3px 3px -1.5px, rgba(29, 33, 48, 0.04) 0px 5px 5px -2.5px, rgba(70, 216, 255, 0.08) 0px 10px 10px -5px, rgba(70, 216, 255, 0.08) 0px 24px 24px -8px`
- **Card with Sour Apple tint:** `rgba(29, 33, 48, 0.08) 0px 0px 0px 1px, rgba(29, 33, 48, 0.04) 0px 1px 1px -1px, rgba(29, 33, 48, 0.04) 0px 2px 2px -1px, rgba(29, 33, 48, 0.04) 0px 3px 3px -1.5px, rgba(29, 33, 48, 0.04) 0px 5px 5px -2.5px, rgba(183, 255, 90, 0.08) 0px 10px 10px -5px, rgba(183, 255, 90, 0.08) 0px 24px 24px -8px`

## Imagery

The visual language is split between abstract UI-like illustrations and minimal, clean product screenshots. Illustrations use a combination of transparent fills and subtly colored, flowing lines (Mimic Mint Blast, Sky Surge, Volt Yellow, Pink Sugar) to represent data flow or connections, maintaining an ethereal, light feel. Product screenshots are contained within card-like structures, often angled to convey dynamism, with a strong focus on the software UI itself rather than real-world context. Icons are typically outlined or monochromatic fills, matching the neutral palette with occasional Hydro Blue accents. Imagery is primarily explanatory and decorative, supporting textual content rather than dominating the layout, maintaining a density that favors text.

## Layout

The page primarily employs a max-width contained layout, allowing content to breathe within a central column. The hero section is full-width with a dark background for contrast, featuring a large, centered headline. Subsequent sections alternate between light backgrounds and occasionally a strong background gradient, with consistent vertical spacing of 64px. Content is often presented in a two-column layout that alternates text and visuals, or in feature grids. Navigation is a persistent top bar, with prominent 'Sour Apple' primary action button, and a pill-shaped secondary navigation for filtering content within sections.

## Agent Prompt Guide

Quick Color Reference:
text: #1d2130
background: #fcfcfd
border: #d5d9e8
accent: #1a67fd
primary action: #bfff5a (filled action)

3-5 Example Component Prompts:
Create a Primary Action Button: #bfff5a background, #0a0d16 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.

Create a product feature card: Transparent background with a 'Sky Surge'-tinted shadow stack. 24px border-radius, no internal padding. Headline 'Remote Deployments DXed' at 22px IBM Plex Sans weight 600, #151720, letter-spacing -0.264px. Include a product screenshot of Buddy's UI, angled to show depth.

Create a secondary navigation pill: 'Cloud White' (#fcfcfd) background, 'Deep Space' (#0a0d16) text, 9999px border-radius, 8px vertical padding, 24px horizontal padding. Ensure inactive pills use 'Midnight Ink' (#1d2130) text and border.

## Similar Brands

- **Vercel** — Shares a clean, modern SaaS aesthetic with a strong emphasis on product UI screenshots, minimal branding colors, and clear typography hierarchy.
- **Supabase** — Features a similar dark, bold typography on a light canvas and leverages distinct chromatic accents for primary actions and highlights.
- **Railway** — Employs a precise, structured UI with subtle elevation via borders and shadows, often using monochromatic elements with a single vibrant accent color.
- **Clerk** — Exhibits a comfortable density with ample spacing, soft card treatments, and a functional yet approachable visual style with crisp typography.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #1d2130;
  --color-cloud-white: #fcfcfd;
  --color-slate-gray: #d5d9e8;
  --color-frost: #ebeef7;
  --color-coal-black: #151720;
  --color-deep-space: #0a0d16;
  --color-sky-dust: #d8fbed;
  --color-emerald-echo: #0b3d28;
  --color-sour-apple: #bfff5a;
  --color-hydro-blue: #1a67fd;
  --color-sunny-glow: #ffd888;
  --gradient-sunny-glow: radial-gradient(100% 100% at 50% 0px, rgb(255, 216, 136) 0%, rgb(255, 198, 80) 100%);
  --color-pink-sugar: #ffb5f1;
  --gradient-pink-sugar: radial-gradient(100% 100% at 50% 0px, rgb(255, 181, 241) 0%, rgb(255, 157, 236) 100%);
  --color-volt-yellow: #ecef74;
  --gradient-volt-yellow: radial-gradient(100% 100% at 50% 0px, rgb(236, 241, 116) 0%, rgb(229, 237, 56) 100%);
  --color-mint-blast: #5df7b6;
  --gradient-mint-blast: radial-gradient(100% 100% at 50% 0px, rgb(93, 247, 182) 0%, rgb(25, 247, 154) 100%);
  --color-sky-surge: #7ae3ff;
  --gradient-sky-surge: radial-gradient(100% 100% at 50% 0px, rgb(122, 227, 255) 0%, rgb(70, 216, 255) 100%);

  /* Typography — Font Families */
  --font-ibm-plex-sans: 'IBM Plex Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ibm-plex-mono: 'IBM Plex Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 1.71;
  --text-heading: 22px;
  --leading-heading: 1.33;
  --tracking-heading: -0.264px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -0.96px;
  --text-display: 80px;
  --leading-display: 0.9;
  --tracking-display: -3.6px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-72: 72px;
  --spacing-96: 96px;
  --spacing-120: 120px;

  /* Layout */
  --section-gap: 64px;
  --card-padding: 24px;
  --element-gap: 24px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 14px;
  --radius-3xl: 24px;
  --radius-3xl-2: 44px;
  --radius-full: 56px;
  --radius-full-2: 78px;
  --radius-full-3: 9999px;

  /* Named Radii */
  --radius-cards: 24px;
  --radius-images: 8px;
  --radius-buttons: 56px;
  --radius-navitems: 44px;
  --radius-textcontainers: 9999px;

  /* Shadows */
  --shadow-subtle: rgba(29, 33, 48, 0.04) 0px 3px 3px -1px, rgba(29, 33, 48, 0.04) 0px 6px 6px -3px, rgba(29, 33, 48, 0.04) 0px 12px 12px -6px, rgba(29, 33, 48, 0.04) 0px 24px 24px -12px, rgba(29, 33, 48, 0.04) 0px 32px 32px -16px;
  --shadow-subtle-2: rgba(255, 255, 255, 0.72) 0px 1px 0px 0px inset, rgba(29, 33, 48, 0.12) 0px -2px 0px 0px inset, rgba(29, 33, 48, 0.04) 0px 1px 1px -1px, rgba(29, 33, 48, 0.04) 0px 4px 4px -2px;
  --shadow-subtle-3: rgba(255, 255, 255, 0.72) 0px 0px 0px 1px inset, rgb(213, 217, 232) 0px 0px 0px 1px, rgba(29, 33, 48, 0.03) 0px 1px 1px -1px, rgba(29, 33, 48, 0.05) 0px 3px 3px -2px, rgba(29, 33, 48, 0.03) 0px 5px 5px -3px, rgba(213, 217, 232, 0.22) 0px 5px 5px -2px;
  --shadow-subtle-4: rgba(29, 33, 48, 0.08) 0px 0px 0px 1px, rgba(29, 33, 48, 0.04) 0px 1px 1px -1px, rgba(29, 33, 48, 0.04) 0px 2px 2px -1px, rgba(29, 33, 48, 0.04) 0px 3px 3px -1.5px, rgba(29, 33, 48, 0.04) 0px 5px 5px -2.5px, rgba(70, 216, 255, 0.08) 0px 10px 10px -5px, rgba(70, 216, 255, 0.08) 0px 24px 24px -8px;
  --shadow-subtle-5: rgba(29, 33, 48, 0.08) 0px 0px 0px 1px, rgba(29, 33, 48, 0.04) 0px 1px 1px -1px, rgba(29, 33, 48, 0.04) 0px 2px 2px -1px, rgba(29, 33, 48, 0.04) 0px 3px 3px -1.5px, rgba(29, 33, 48, 0.04) 0px 5px 5px -2.5px, rgba(183, 255, 90, 0.08) 0px 10px 10px -5px, rgba(183, 255, 90, 0.08) 0px 24px 24px -8px;
  --shadow-subtle-6: rgba(29, 33, 48, 0.08) 0px 0px 0px 1px, rgba(29, 33, 48, 0.04) 0px 1px 1px -1px, rgba(29, 33, 48, 0.04) 0px 2px 2px -1px, rgba(29, 33, 48, 0.04) 0px 3px 3px -1.5px, rgba(29, 33, 48, 0.04) 0px 5px 5px -2.5px, rgba(25, 247, 154, 0.08) 0px 10px 10px -5px, rgba(25, 247, 154, 0.08) 0px 24px 24px -8px;
  --shadow-subtle-7: rgba(29, 33, 48, 0.08) 0px 0px 0px 1px, rgba(29, 33, 48, 0.04) 0px 1px 1px -1px, rgba(29, 33, 48, 0.04) 0px 2px 2px -1px, rgba(29, 33, 48, 0.04) 0px 3px 3px -1.5px, rgba(29, 33, 48, 0.04) 0px 5px 5px -2.5px, rgba(193, 154, 255, 0.08) 0px 10px 10px -5px, rgba(193, 154, 255, 0.08) 0px 24px 24px -8px;
  --shadow-subtle-8: rgba(29, 33, 48, 0.08) 0px 0px 0px 1px, rgba(29, 33, 48, 0.04) 0px 1px 1px -1px, rgba(29, 33, 48, 0.04) 0px 2px 2px -1px, rgba(29, 33, 48, 0.04) 0px 3px 3px -1.5px, rgba(29, 33, 48, 0.04) 0px 5px 5px -2.5px, rgba(229, 237, 56, 0.08) 0px 10px 10px -5px, rgba(229, 237, 56, 0.08) 0px 24px 24px -8px;
  --shadow-subtle-9: rgba(29, 33, 48, 0.08) 0px 0px 0px 1px, rgba(29, 33, 48, 0.04) 0px 1px 1px -1px, rgba(29, 33, 48, 0.04) 0px 2px 2px -1px, rgba(29, 33, 48, 0.04) 0px 3px 3px -1.5px, rgba(29, 33, 48, 0.04) 0px 5px 5px -2.5px, rgba(255, 160, 48, 0.08) 0px 10px 10px -5px, rgba(255, 160, 48, 0.08) 0px 24px 24px -8px;
  --shadow-subtle-10: rgba(29, 33, 48, 0.08) 0px 0px 0px 1px, rgba(29, 33, 48, 0.04) 0px 1px 1px -1px, rgba(29, 33, 48, 0.04) 0px 2px 2px -1px, rgba(29, 33, 48, 0.04) 0px 3px 3px -1.5px, rgba(29, 33, 48, 0.04) 0px 5px 5px -2.5px, rgba(255, 128, 110, 0.08) 0px 10px 10px -5px, rgba(255, 128, 110, 0.08) 0px 24px 24px -8px;
  --shadow-subtle-11: rgba(17, 17, 17, 0.16) 0px 0px 0px 1px inset, rgba(29, 33, 48, 0.04) 0px 3px 3px -1px, rgba(29, 33, 48, 0.04) 0px 6px 6px -3px, rgba(29, 33, 48, 0.04) 0px 12px 12px -6px, rgba(29, 33, 48, 0.04) 0px 24px 24px -12px, rgba(255, 198, 80, 0.08) 0px 26px 32px -16px, rgba(255, 198, 80, 0.08) 0px 20px 44px -16px;
  --shadow-subtle-12: rgba(17, 17, 17, 0.16) 0px 0px 0px 1px inset, rgba(29, 33, 48, 0.04) 0px 3px 3px -1px, rgba(29, 33, 48, 0.04) 0px 6px 6px -3px, rgba(29, 33, 48, 0.04) 0px 12px 12px -6px, rgba(29, 33, 48, 0.04) 0px 24px 24px -12px, rgba(255, 157, 236, 0.08) 0px 26px 32px -16px, rgba(255, 157, 236, 0.08) 0px 20px 44px -16px;
  --shadow-subtle-13: rgba(17, 17, 17, 0.16) 0px 0px 0px 1px inset, rgba(29, 33, 48, 0.04) 0px 3px 3px -1px, rgba(29, 33, 48, 0.04) 0px 6px 6px -3px, rgba(29, 33, 48, 0.04) 0px 12px 12px -6px, rgba(29, 33, 48, 0.04) 0px 24px 24px -12px, rgba(229, 237, 56, 0.08) 0px 26px 32px -16px, rgba(229, 237, 56, 0.08) 0px 20px 44px -16px;
  --shadow-subtle-14: rgba(17, 17, 17, 0.16) 0px 0px 0px 1px inset, rgba(29, 33, 48, 0.04) 0px 3px 3px -1px, rgba(29, 33, 48, 0.04) 0px 6px 6px -3px, rgba(29, 33, 48, 0.04) 0px 12px 12px -6px, rgba(29, 33, 48, 0.04) 0px 24px 24px -12px, rgba(25, 247, 154, 0.08) 0px 26px 32px -16px, rgba(25, 247, 154, 0.08) 0px 20px 44px -16px;
  --shadow-subtle-15: rgba(17, 17, 17, 0.16) 0px 0px 0px 1px inset, rgba(29, 33, 48, 0.04) 0px 3px 3px -1px, rgba(29, 33, 48, 0.04) 0px 6px 6px -3px, rgba(29, 33, 48, 0.04) 0px 12px 12px -6px, rgba(29, 33, 48, 0.04) 0px 24px 24px -12px, rgba(70, 216, 255, 0.08) 0px 26px 32px -16px, rgba(70, 216, 255, 0.08) 0px 20px 44px -16px;

  /* Surfaces */
  --surface-cloud-white-canvas: #fcfcfd;
  --surface-frosted-card: #fcfcfd;
  --surface-elevated-accent-surface: #00000000;
  --surface-feedback-highlight: #ffd888;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #1d2130;
  --color-cloud-white: #fcfcfd;
  --color-slate-gray: #d5d9e8;
  --color-frost: #ebeef7;
  --color-coal-black: #151720;
  --color-deep-space: #0a0d16;
  --color-sky-dust: #d8fbed;
  --color-emerald-echo: #0b3d28;
  --color-sour-apple: #bfff5a;
  --color-hydro-blue: #1a67fd;
  --color-sunny-glow: #ffd888;
  --color-pink-sugar: #ffb5f1;
  --color-volt-yellow: #ecef74;
  --color-mint-blast: #5df7b6;
  --color-sky-surge: #7ae3ff;

  /* Typography */
  --font-ibm-plex-sans: 'IBM Plex Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ibm-plex-mono: 'IBM Plex Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 1.71;
  --text-heading: 22px;
  --leading-heading: 1.33;
  --tracking-heading: -0.264px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -0.96px;
  --text-display: 80px;
  --leading-display: 0.9;
  --tracking-display: -3.6px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-72: 72px;
  --spacing-96: 96px;
  --spacing-120: 120px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 14px;
  --radius-3xl: 24px;
  --radius-3xl-2: 44px;
  --radius-full: 56px;
  --radius-full-2: 78px;
  --radius-full-3: 9999px;

  /* Shadows */
  --shadow-subtle: rgba(29, 33, 48, 0.04) 0px 3px 3px -1px, rgba(29, 33, 48, 0.04) 0px 6px 6px -3px, rgba(29, 33, 48, 0.04) 0px 12px 12px -6px, rgba(29, 33, 48, 0.04) 0px 24px 24px -12px, rgba(29, 33, 48, 0.04) 0px 32px 32px -16px;
  --shadow-subtle-2: rgba(255, 255, 255, 0.72) 0px 1px 0px 0px inset, rgba(29, 33, 48, 0.12) 0px -2px 0px 0px inset, rgba(29, 33, 48, 0.04) 0px 1px 1px -1px, rgba(29, 33, 48, 0.04) 0px 4px 4px -2px;
  --shadow-subtle-3: rgba(255, 255, 255, 0.72) 0px 0px 0px 1px inset, rgb(213, 217, 232) 0px 0px 0px 1px, rgba(29, 33, 48, 0.03) 0px 1px 1px -1px, rgba(29, 33, 48, 0.05) 0px 3px 3px -2px, rgba(29, 33, 48, 0.03) 0px 5px 5px -3px, rgba(213, 217, 232, 0.22) 0px 5px 5px -2px;
  --shadow-subtle-4: rgba(29, 33, 48, 0.08) 0px 0px 0px 1px, rgba(29, 33, 48, 0.04) 0px 1px 1px -1px, rgba(29, 33, 48, 0.04) 0px 2px 2px -1px, rgba(29, 33, 48, 0.04) 0px 3px 3px -1.5px, rgba(29, 33, 48, 0.04) 0px 5px 5px -2.5px, rgba(70, 216, 255, 0.08) 0px 10px 10px -5px, rgba(70, 216, 255, 0.08) 0px 24px 24px -8px;
  --shadow-subtle-5: rgba(29, 33, 48, 0.08) 0px 0px 0px 1px, rgba(29, 33, 48, 0.04) 0px 1px 1px -1px, rgba(29, 33, 48, 0.04) 0px 2px 2px -1px, rgba(29, 33, 48, 0.04) 0px 3px 3px -1.5px, rgba(29, 33, 48, 0.04) 0px 5px 5px -2.5px, rgba(183, 255, 90, 0.08) 0px 10px 10px -5px, rgba(183, 255, 90, 0.08) 0px 24px 24px -8px;
  --shadow-subtle-6: rgba(29, 33, 48, 0.08) 0px 0px 0px 1px, rgba(29, 33, 48, 0.04) 0px 1px 1px -1px, rgba(29, 33, 48, 0.04) 0px 2px 2px -1px, rgba(29, 33, 48, 0.04) 0px 3px 3px -1.5px, rgba(29, 33, 48, 0.04) 0px 5px 5px -2.5px, rgba(25, 247, 154, 0.08) 0px 10px 10px -5px, rgba(25, 247, 154, 0.08) 0px 24px 24px -8px;
  --shadow-subtle-7: rgba(29, 33, 48, 0.08) 0px 0px 0px 1px, rgba(29, 33, 48, 0.04) 0px 1px 1px -1px, rgba(29, 33, 48, 0.04) 0px 2px 2px -1px, rgba(29, 33, 48, 0.04) 0px 3px 3px -1.5px, rgba(29, 33, 48, 0.04) 0px 5px 5px -2.5px, rgba(193, 154, 255, 0.08) 0px 10px 10px -5px, rgba(193, 154, 255, 0.08) 0px 24px 24px -8px;
  --shadow-subtle-8: rgba(29, 33, 48, 0.08) 0px 0px 0px 1px, rgba(29, 33, 48, 0.04) 0px 1px 1px -1px, rgba(29, 33, 48, 0.04) 0px 2px 2px -1px, rgba(29, 33, 48, 0.04) 0px 3px 3px -1.5px, rgba(29, 33, 48, 0.04) 0px 5px 5px -2.5px, rgba(229, 237, 56, 0.08) 0px 10px 10px -5px, rgba(229, 237, 56, 0.08) 0px 24px 24px -8px;
  --shadow-subtle-9: rgba(29, 33, 48, 0.08) 0px 0px 0px 1px, rgba(29, 33, 48, 0.04) 0px 1px 1px -1px, rgba(29, 33, 48, 0.04) 0px 2px 2px -1px, rgba(29, 33, 48, 0.04) 0px 3px 3px -1.5px, rgba(29, 33, 48, 0.04) 0px 5px 5px -2.5px, rgba(255, 160, 48, 0.08) 0px 10px 10px -5px, rgba(255, 160, 48, 0.08) 0px 24px 24px -8px;
  --shadow-subtle-10: rgba(29, 33, 48, 0.08) 0px 0px 0px 1px, rgba(29, 33, 48, 0.04) 0px 1px 1px -1px, rgba(29, 33, 48, 0.04) 0px 2px 2px -1px, rgba(29, 33, 48, 0.04) 0px 3px 3px -1.5px, rgba(29, 33, 48, 0.04) 0px 5px 5px -2.5px, rgba(255, 128, 110, 0.08) 0px 10px 10px -5px, rgba(255, 128, 110, 0.08) 0px 24px 24px -8px;
  --shadow-subtle-11: rgba(17, 17, 17, 0.16) 0px 0px 0px 1px inset, rgba(29, 33, 48, 0.04) 0px 3px 3px -1px, rgba(29, 33, 48, 0.04) 0px 6px 6px -3px, rgba(29, 33, 48, 0.04) 0px 12px 12px -6px, rgba(29, 33, 48, 0.04) 0px 24px 24px -12px, rgba(255, 198, 80, 0.08) 0px 26px 32px -16px, rgba(255, 198, 80, 0.08) 0px 20px 44px -16px;
  --shadow-subtle-12: rgba(17, 17, 17, 0.16) 0px 0px 0px 1px inset, rgba(29, 33, 48, 0.04) 0px 3px 3px -1px, rgba(29, 33, 48, 0.04) 0px 6px 6px -3px, rgba(29, 33, 48, 0.04) 0px 12px 12px -6px, rgba(29, 33, 48, 0.04) 0px 24px 24px -12px, rgba(255, 157, 236, 0.08) 0px 26px 32px -16px, rgba(255, 157, 236, 0.08) 0px 20px 44px -16px;
  --shadow-subtle-13: rgba(17, 17, 17, 0.16) 0px 0px 0px 1px inset, rgba(29, 33, 48, 0.04) 0px 3px 3px -1px, rgba(29, 33, 48, 0.04) 0px 6px 6px -3px, rgba(29, 33, 48, 0.04) 0px 12px 12px -6px, rgba(29, 33, 48, 0.04) 0px 24px 24px -12px, rgba(229, 237, 56, 0.08) 0px 26px 32px -16px, rgba(229, 237, 56, 0.08) 0px 20px 44px -16px;
  --shadow-subtle-14: rgba(17, 17, 17, 0.16) 0px 0px 0px 1px inset, rgba(29, 33, 48, 0.04) 0px 3px 3px -1px, rgba(29, 33, 48, 0.04) 0px 6px 6px -3px, rgba(29, 33, 48, 0.04) 0px 12px 12px -6px, rgba(29, 33, 48, 0.04) 0px 24px 24px -12px, rgba(25, 247, 154, 0.08) 0px 26px 32px -16px, rgba(25, 247, 154, 0.08) 0px 20px 44px -16px;
  --shadow-subtle-15: rgba(17, 17, 17, 0.16) 0px 0px 0px 1px inset, rgba(29, 33, 48, 0.04) 0px 3px 3px -1px, rgba(29, 33, 48, 0.04) 0px 6px 6px -3px, rgba(29, 33, 48, 0.04) 0px 12px 12px -6px, rgba(29, 33, 48, 0.04) 0px 24px 24px -12px, rgba(70, 216, 255, 0.08) 0px 26px 32px -16px, rgba(70, 216, 255, 0.08) 0px 20px 44px -16px;
}
```

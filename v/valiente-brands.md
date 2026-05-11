# VALIENTE BRANDS — Style Reference
> Raw Crimson Statement. The page feels like a manifesto etched in bold red on stark white.

**Theme:** light

This design system presents as a raw, almost brutalist exhibition of brand identity. A primary, vivid red against a near-white background commands attention, creating an aggressive, high-energy aesthetic. Typography is dense and tightly kerned, often acting as a visual element itself, reinforcing a sense of purposeful, impactful communication. The design feels like a bold statement rather than a polished interface, prioritizing directness and brand impact.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Valiente Crimson | `#ff1a00` | `--color-valiente-crimson` | Primary brand accent, all interactive elements, key headlines, navigation emphasis, text content where brand intensity is required. |
| Concrete White | `#f5f5f5` | `--color-concrete-white` | Dominant background color for sections and the overall page. |
| Charcoal Black | `#0a0a0a` | `--color-charcoal-black` | Primary text color for body copy, subheadings, and some navigation elements. Creates high contrast with Concrete White. |
| Ash Gray | `#eaeaea` | `--color-ash-gray` | Subtitle text within body copy, occasionally for subtle background variations or section dividers not explicitly shown. |
| Pale Rose | `#e7a196` | `--color-pale-rose` | Rare background element, likely an unintentional browser artifact or a very subtle, almost unnoticeable background tint. |

## Tokens — Typography

### GT Pressura — Primary content font for all text from body to display. Its uniform weight contributes to the raw, direct feel. Aggressive negative letter-spacing, particularly at larger sizes, compresses text, making it feel intense and direct. · `--font-gt-pressura`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 12px, 14px, 16px, 18px, 20px, 24px, 48px, 95px, 128px, 190px, 245px
- **Line height:** 0.80, 0.82, 1.00, 1.20
- **Letter spacing:** -0.6, -0.56, -0.64, -0.666, -0.6, -0.72, -1.44, -7.125, -4.48, -6.65, -12.25
- **Role:** Primary content font for all text from body to display. Its uniform weight contributes to the raw, direct feel. Aggressive negative letter-spacing, particularly at larger sizes, compresses text, making it feel intense and direct.

### Monument Grotesk — Used for specific headlines, likely acting as a complementary display font. Its use at a single size reinforces its stylistic, rather than functional, role. Negative letter-spacing is also used here to maintain the compressed aesthetic. · `--font-monument-grotesk`
- **Substitute:** Archivo
- **Weights:** 400
- **Sizes:** 48px
- **Line height:** 1.00
- **Letter spacing:** -1.92
- **Role:** Used for specific headlines, likely acting as a complementary display font. Its use at a single size reinforces its stylistic, rather than functional, role. Negative letter-spacing is also used here to maintain the compressed aesthetic.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.2 | -0.6px | `--text-caption` |
| body | 16px | 1.2 | -0.64px | `--text-body` |
| subheading | 24px | 1 | -0.72px | `--text-subheading` |
| heading | 48px | 1 | -1.92px | `--text-heading` |
| heading-lg | 95px | 0.8 | -7.125px | `--text-heading-lg` |
| display | 245px | 0.8 | -12.25px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 6px

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 12 | 12px | `--spacing-12` |
| 24 | 24px | `--spacing-24` |
| 30 | 30px | `--spacing-30` |
| 60 | 60px | `--spacing-60` |
| 120 | 120px | `--spacing-120` |
| 138 | 138px | `--spacing-138` |
| 150 | 150px | `--spacing-150` |

### Border Radius

| Element | Value |
|---------|-------|
| none | 0px |

### Layout

- **Page max-width:** 1440px
- **Section gap:** 64px
- **Card padding:** 0px
- **Element gap:** 20px

## Components

### Navigation Link
**Role:** Interactive text link in the header and footer navigation.

Styled with GT Pressura, weight 400, size 16px, line-height 1.2. Default text color is Charcoal Black (#0a0a0a), with Valiente Crimson (#ff1a00) for active or hover states. No padding or borders, relying on color change for interaction feedback.

### Hero Headline
**Role:** Main heading for the hero section.

Rendered in GT Pressura, weight 400, size 48px, line-height 1, letter-spacing -1.44px (based on -0.0300em). Text color is Valiente Crimson (#ff1a00), commanding immediate attention.

### Body Paragraph
**Role:** Standard text blocks for descriptive content.

Styled with GT Pressura, weight 400, size 16px, line-height 1.2, letter-spacing -0.64px. Text color is Charcoal Black (#0a0a0a). Content is compact without excessive padding.

### Footer Copyright
**Role:** Legal and copyright information at the bottom of the page.

Uses GT Pressura, weight 400, size 16px, line-height 1.2, letter-spacing -0.64px. Text color is Charcoal Black (#0a0a0a). Positioned with a minimal margin from other elements.

### Feature Card (Text-only)
**Role:** Displays specific features or project details.

These cards have no background color, border radius, box shadow, or padding (all 0px). They are essentially text blocks, allowing the content itself to be the primary focus over structural design. Text uses GT Pressura with varying sizes depending on hierarchy.

## Do's and Don'ts

### Do
- Prioritize Valiente Crimson (#ff1a00) for all interactive states and primary branding elements.
- Maintain tight letter-spacing for all text elements, particularly at larger sizes (e.g., -1.44px for 48px text, -12.25px for 245px text), using GT Pressura predominantly.
- Use a pure, flat background of Concrete White (#f5f5f5) for the majority of page sections.
- Ensure headings and key textual statements are rendered in Valiente Crimson (#ff1a00) to maximize brand presence and impact.
- Maintain strict 0px border-radius and box-shadow on all card-like elements, keeping the UI sharp and unadorned.
- Employ Charcoal Black (#0a0a0a) for most body copy to establish clear contrast against the light background.

### Don't
- Avoid using soft shadows or complex gradients; the aesthetic is flat and direct.
- Do not introduce curved corners or significant border-radii; all elements should maintain sharp 0px corners.
- Refrain from using varied weights or italic styles for GT Pressura; stick to weight 400 for consistency.
- Do not introduce any additional chromatic colors; limit the palette strictly to Valiente Crimson and the neutral shades.
- Avoid excessive whitespace around content blocks; the design prefers compactness and density, especially in text arrangement.
- Do not deviate from the established negative letter-spacing for text, as it is a core characteristic of the brand's typographic identity.

## Imagery

The site uses a mix of candid, dark-toned photography and abstract typography as visual elements. Photography, when present (like the boxing scene), appears full-bleed or large-scale, often with a moody, desaturated filter that contrasts strongly with the bright, text-centric UI. Imagery is used decoratively to evoke atmosphere rather than to explicitly explain content, relying on its emotional impact. There are also product/people shots with neutral or studio-like backgrounds, often focused on individuals, maintaining a raw, authentic feel without overt styling. Icons are minimal, resembling simple outlined shapes with sharp edges, consistently in Valiente Crimson, providing functional navigation cues while adhering to the bold aesthetic.

## Layout

The page primarily uses a max-width contained layout, likely around 1200-1440px, though a full-bleed video section interrupts this pattern for dramatic effect. The hero section is characterized by a unique staggered typography layout, creating a visual grid rather than a traditional centered headline. Sections are defined by consistent vertical spacing, creating an airy, uncluttered feel despite the dense typography. Content often appears in stacked blocks or implied two-column arrangements (e.g., text block left, implicit visual right), with a strong left alignment. Navigation is a minimalist top-right 'Get in Touch' button and a left-aligned, stacked text menu, both fixed or sticky. The overall rhythm is open and free-flowing, punctuated by bold text blocks.

## Agent Prompt Guide

### Quick Color Reference
- Text (Charcoal Black): #0a0a0a
- Background (Concrete White): #f5f5f5
- CTA/Accent (Valiente Crimson): #ff1a00
- Hover/Active (Valiente Crimson): #ff1a00

### 3-5 Example Component Prompts
1.  **Create a hero section:** Concrete White background (#f5f5f5). Headline type '— IMPACT-LED BRAND CONSULTANCY' in Valiente Crimson (#ff1a00), GT Pressura, weight 400, size 48px, line-height 1, letter-spacing -1.44px. Include a subtitle 'BRAVERY IN PRACTICE' below, in Valiente Crimson (#ff1a00), GT Pressura, weight 400, size 16px, line-height 1.2, letter-spacing -0.64px. Both text elements left-aligned within a max-width container, with elementGap 20px between them.
2.  **Generate a navigation link:** Text 'Services' in Charcoal Black (#0a0a0a), GT Pressura, weight 400, size 16px, line-height 1.2, letter-spacing -0.64px. On hover, change text color to Valiente Crimson (#ff1a00). No padding, borders, or background.
3.  **Design a feature text block:** Start with a heading 'WFBCOGLZU' in Valiente Crimson (#ff1a00), GT Pressura, weight 400, size 24px, line-height 1, letter-spacing -0.72px. Followed by body text 'DJCTUVOCITEGUSCB KPYOHBRHIRGIFMNZACXRCYXCTR BXAMHNCS' in Charcoal Black (#0a0a0a), GT Pressura, weight 400, size 16px, line-height 1.2, letter-spacing -0.64px. Both elements left-aligned, with 20px vertical gap between them, on a Concrete White (#f5f5f5) background. The combined block should have 0px padding and 0px borderRadius.

## Similar Brands

- **Brave New World** — Aggressive, high-contrast typography as a primary design element; limited, impactful color palette with emphasis on a single vivid accent.
- **Acme Co.** — Raw, unpolished aesthetic with minimal use of shadows or rounded elements, focusing on direct communication over visual polish.
- **Red Antler** — A strong brand voice conveyed almost entirely through type and color, using a stark background to highlight textual statements and brand accents.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-valiente-crimson: #ff1a00;
  --color-concrete-white: #f5f5f5;
  --color-charcoal-black: #0a0a0a;
  --color-ash-gray: #eaeaea;
  --color-pale-rose: #e7a196;

  /* Typography — Font Families */
  --font-gt-pressura: 'GT Pressura', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-monument-grotesk: 'Monument Grotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.2;
  --tracking-caption: -0.6px;
  --text-body: 16px;
  --leading-body: 1.2;
  --tracking-body: -0.64px;
  --text-subheading: 24px;
  --leading-subheading: 1;
  --tracking-subheading: -0.72px;
  --text-heading: 48px;
  --leading-heading: 1;
  --tracking-heading: -1.92px;
  --text-heading-lg: 95px;
  --leading-heading-lg: 0.8;
  --tracking-heading-lg: -7.125px;
  --text-display: 245px;
  --leading-display: 0.8;
  --tracking-display: -12.25px;

  /* Typography — Weights */
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-unit: 6px;
  --spacing-12: 12px;
  --spacing-24: 24px;
  --spacing-30: 30px;
  --spacing-60: 60px;
  --spacing-120: 120px;
  --spacing-138: 138px;
  --spacing-150: 150px;

  /* Layout */
  --page-max-width: 1440px;
  --section-gap: 64px;
  --card-padding: 0px;
  --element-gap: 20px;

  /* Named Radii */
  --radius-none: 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-valiente-crimson: #ff1a00;
  --color-concrete-white: #f5f5f5;
  --color-charcoal-black: #0a0a0a;
  --color-ash-gray: #eaeaea;
  --color-pale-rose: #e7a196;

  /* Typography */
  --font-gt-pressura: 'GT Pressura', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-monument-grotesk: 'Monument Grotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.2;
  --tracking-caption: -0.6px;
  --text-body: 16px;
  --leading-body: 1.2;
  --tracking-body: -0.64px;
  --text-subheading: 24px;
  --leading-subheading: 1;
  --tracking-subheading: -0.72px;
  --text-heading: 48px;
  --leading-heading: 1;
  --tracking-heading: -1.92px;
  --text-heading-lg: 95px;
  --leading-heading-lg: 0.8;
  --tracking-heading-lg: -7.125px;
  --text-display: 245px;
  --leading-display: 0.8;
  --tracking-display: -12.25px;

  /* Spacing */
  --spacing-12: 12px;
  --spacing-24: 24px;
  --spacing-30: 30px;
  --spacing-60: 60px;
  --spacing-120: 120px;
  --spacing-138: 138px;
  --spacing-150: 150px;
}
```

---
name: Pastel Aurora Editorial
colors:
  surface: '#f8faf7'
  surface-dim: '#d8dbd8'
  surface-bright: '#f8faf7'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f1'
  surface-container: '#eceeeb'
  surface-container-high: '#e7e9e6'
  surface-container-highest: '#e1e3e0'
  on-surface: '#191c1b'
  on-surface-variant: '#434843'
  inverse-surface: '#2e312f'
  inverse-on-surface: '#eff1ee'
  outline: '#747873'
  outline-variant: '#c4c8c1'
  surface-tint: '#556156'
  primary: '#07110a'
  on-primary: '#ffffff'
  primary-container: '#1c271e'
  on-primary-container: '#828f83'
  inverse-primary: '#bdcabc'
  secondary: '#4d644e'
  on-secondary: '#ffffff'
  secondary-container: '#cfeace'
  on-secondary-container: '#536a54'
  tertiary: '#110e1a'
  on-tertiary: '#ffffff'
  tertiary-container: '#262330'
  on-tertiary-container: '#8f899a'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d9e6d8'
  primary-fixed-dim: '#bdcabc'
  on-primary-fixed: '#131e15'
  on-primary-fixed-variant: '#3e4a3f'
  secondary-fixed: '#cfeace'
  secondary-fixed-dim: '#b3cdb2'
  on-secondary-fixed: '#0a200f'
  on-secondary-fixed-variant: '#364c38'
  tertiary-fixed: '#e7dff2'
  tertiary-fixed-dim: '#cac4d5'
  on-tertiary-fixed: '#1d1a26'
  on-tertiary-fixed-variant: '#494553'
  background: '#f8faf7'
  on-background: '#191c1b'
  surface-variant: '#e1e3e0'
typography:
  display-hero:
    fontFamily: Plus Jakarta Sans
    fontSize: 56px
    fontWeight: '800'
    lineHeight: 64px
    letterSpacing: -0.03em
  display-hero-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '800'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.025em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 26px
    fontWeight: '700'
    lineHeight: 34px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: -0.005em
  body-md:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  body-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0.005em
  label-md:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '600'
    lineHeight: 18px
    letterSpacing: 0.03em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.06em
  code-sm:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 18px
    letterSpacing: -0.01em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  space-2xs: 0.25rem
  space-xs: 0.5rem
  space-sm: 0.75rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
  space-2xl: 3rem
  space-3xl: 4.5rem
  gutter-mobile: 1rem
  gutter-desktop: 1.5rem
  margin-mobile: 1.25rem
  margin-desktop: 3rem
---

## Brand & Style

This design system establishes a poised, airy, and high-impact editorial canvas for an entry-level software engineer. It targets senior technical recruiters, engineering managers, and founders who evaluate candidates in under 30 seconds.

The aesthetic fuses modern Scandinavian minimalism with luminous digital glassmorphism:
- **Atmospheric Aurora:** The canvas floats over ambient mesh gradients composed of sage green, pale lavender, soft mint, and blush peach, evoking calm precision, taste, and technical clarity.
- **Editorial Legibility:** Crisp, dark forest green typography grounds the dreamy atmospheric background in rigorous structure, commanding attention without feeling stark or utilitarian.
- **Bento Hierarchy:** Content blocks mimic tactile milky-glass slabs, organizing technical stack proficiencies, project highlights, system architecture sketches, and educational credentials into intuitive, scannable modules.

## Colors

The palette balances airy pastel hues against deep, grounded forest tones to maintain strict WCAG AAA readability while retaining a distinctive, ethereal ambiance.

- **Primary (`#1C271E`):** Deep Forest Green. Anchors headlines, primary interactive states, key technical specs, and high-emphasis body text. Replaces standard harsh blacks with organic density.
- **Secondary (`#B4CEB3`):** Sage Green. Serves as interactive indicators, soft selection borders, code pill backgrounds, and structural gradient accents.
- **Tertiary (`#DDD6E8`):** Pastel Lavender. Applied to contextual metadata badges, secondary card highlights, and soft gradient counterpoints alongside Soft Mint (`#CBE3CB`) and Blush Peach (`#F6DCD1`).
- **Neutral Base (`#F8FAF7`):** Warm Dew White. The underlying page background, establishing a warm, non-sterile field for light refraction and glass panels.

### Surface Color Roles
- **Glass Panel Surface:** `rgba(255, 255, 255, 0.72)` with a subtle inner tint of `rgba(180, 206, 179, 0.08)`.
- **Glass Border / Hairline:** `rgba(255, 255, 255, 0.85)` top-to-bottom linear gradient tapering to `rgba(180, 206, 179, 0.35)`.
- **Muted Text / Secondary Labels:** `rgba(28, 39, 30, 0.65)`.
- **Subtle Borders / Dividers:** `rgba(28, 39, 30, 0.08)`.

## Typography

Typography prioritizes rapid visual scanning through tight character tracking and deliberate contrast in optical weights:

- **Display & Headlines:** Set in `Plus Jakarta Sans`. Tightly kerned with prominent structural mass to deliver immediate authorial confidence in titles, roles, and project impact statements.
- **Body & Metrics:** Set in `Inter`. Neutral and ultra-legible, preventing fatigue during technical deep dives, project scope narratives, and resume points.
- **Code & Tech Stacks:** Set in `JetBrains Mono` for tech pills, git commit markers, and architectural callouts, signaling technical competence without breaking the high-end editorial feel.

## Layout & Spacing

The portfolio employs a responsive 12-column bento grid engineered for modular content hierarchy and rapid scanning:

- **Grid System:** 12-column layout on desktop (`max-width: 1240px`) with dynamic gutter widths (`24px`). On tablet (768px–1024px), it shifts to an 8-column layout. On mobile (<768px), it condenses to a single-column sequence.
- **Bento Modular Spanning:** Project case studies span 8 or 12 columns, metrics and quick-look achievements span 4 columns, and technology stack modules span 3 to 4 columns.
- **Atmospheric Canvas:** Fixed background radial and conic mesh blur nodes (minimum `blur(120px)`) stay anchored behind the content grid to ensure glass refraction remains consistent during scrolling.
- **Scanning Rhythm:** Spacing between disparate thematic zones is preserved at `4.5rem` (`space-3xl`), while intra-card relationships utilize `1rem` to `1.5rem` for tight informational grouping.

## Elevation & Depth

Visual depth is achieved through layered frosted glass and soft, tinted ambient illumination rather than dark, muddy dropshadows:

- **Base Glass (Bento Panels):**
  - Background: `rgba(255, 255, 255, 0.70)`
  - Backdrop Blur: `backdrop-filter: blur(20px) saturate(160%)`
  - Border: `1px solid rgba(255, 255, 255, 0.85)`
  - Shadow: `0 12px 32px -8px rgba(28, 39, 30, 0.05), 0 1px 2px rgba(180, 206, 179, 0.2)`
- **Floating Interactive Glass (Popovers, Active State, Modals):**
  - Background: `rgba(255, 255, 255, 0.88)`
  - Backdrop Blur: `backdrop-filter: blur(28px) saturate(180%)`
  - Border: `1px solid rgba(255, 255, 255, 0.95)`
  - Shadow: `0 20px 40px -12px rgba(28, 39, 30, 0.08), 0 0 0 1px rgba(180, 206, 179, 0.35)`
- **Gradient Mesh Highlights:** Soft radial glows in Sage Green (`#B4CEB3`) and Blush Peach (`#F6DCD1`) sit at 15–20% opacity directly beneath hero cards to subtly draw the recruiter's eye to high-priority sections.

## Shapes

The geometric signature balances sweeping, architectural curves with crisp inner elements:

- **Bento Card Containers:** Feature heavy `24px` to `28px` corner radii, creating a modern, approachable, high-end consumer hardware aesthetic.
- **Interactive Badges & Pill Labels:** Fully circular (`rounded-full` / `9999px`) border-radii for skill tags, statuses, and category chips.
- **Buttons & Inner Inputs:** `12px` to `14px` border-radii to maintain structural harmony inside the larger 28px card contours.
- **Decorative Avatars & Media Masks:** Squircle outlines (`rounded-3xl`) to complement the bento layout.

## Components

### Buttons
- **Primary CTA:** Deep Forest Green (`#1C271E`) solid fill, pure white text, `12px` radius, `px-5 py-3`. Hover scales by `1.015` with a subtle sage aura (`box-shadow: 0 8px 24px -4px rgba(180, 206, 179, 0.6)`).
- **Glass / Secondary Button:** Milky glass background (`rgba(255, 255, 255, 0.7)`), 1px solid `rgba(255, 255, 255, 0.9)`, forest green text. Hover shifts background to `rgba(255, 255, 255, 0.95)`.
- **Text Link CTA:** Inline editorial link featuring an animated underline in `#B4CEB3` transitioning outward on hover with an external micro-arrow (`↗`).

### Badges & Pill Chips
- **Tech Stack Pills:** JetBrains Mono font (`code-sm`), pill radius (`9999px`), `px-3 py-1`. Dual-state:
  - Default: Pale Mint/Sage tint (`rgba(203, 227, 203, 0.45)`) with `#1C271E` text.
  - Secondary/Tooling: Pastel Lavender tint (`rgba(221, 214, 232, 0.45)`).
- **Recruiter Status Badge (Available for Hire):** Glowing green indicator dot (`#4ADE80` with ping animation), encased in an ultra-frosted pill container with `1px` translucent border.

### Bento Cards
- **Architecture:** Outer radius `26px`, internal padding `2rem`, milky glass finish with subtle emerald inner gradient.
- **Card Header:** Primary bold title (`Plus Jakarta Sans`), right-aligned auxiliary metadata or year badge.
- **Interactive Behavior:** Subtle upward translation (`translate-y: -3px`) and border luminescence intensify to `rgba(180, 206, 179, 0.7)` on hover.

### Recruiter Quick-Scan Drawer / Feature Block
- **Metric Highlight Tiles:** Clean cards within project panels pairing a large-scale statistic (`32px` Plus Jakarta Sans Bold) with a small, uppercase description label (`label-sm`).
- **Interactive Code Snippet Module:** Dark forest glass backdrop (`rgba(28, 39, 30, 0.95)`) for quick architecture or algorithm review, contrasted against the lighter surrounding page.

### Input Fields & Contact Surface
- **Text Inputs:** Milky surface fill (`rgba(255, 255, 255, 0.6)`), 1px border (`rgba(28, 39, 30, 0.12)`), `12px` radius. Focus transition reveals a smooth `0 0 0 3px rgba(180, 206, 179, 0.4)` ring with crisp forest green text.
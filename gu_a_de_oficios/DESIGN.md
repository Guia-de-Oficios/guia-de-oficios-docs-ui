---
name: Guía de Oficios
colors:
  surface: '#faf8ff'
  surface-dim: '#d2d9f4'
  surface-bright: '#faf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f3ff'
  surface-container: '#eaedff'
  surface-container-high: '#e2e7ff'
  surface-container-highest: '#dae2fd'
  on-surface: '#131b2e'
  on-surface-variant: '#444653'
  inverse-surface: '#283044'
  inverse-on-surface: '#eef0ff'
  outline: '#757684'
  outline-variant: '#c4c5d5'
  surface-tint: '#3755c3'
  primary: '#00288e'
  on-primary: '#ffffff'
  primary-container: '#1e40af'
  on-primary-container: '#a8b8ff'
  inverse-primary: '#b8c4ff'
  secondary: '#006d30'
  on-secondary: '#ffffff'
  secondary-container: '#92f5a4'
  on-secondary-container: '#007233'
  tertiary: '#532a00'
  on-tertiary: '#ffffff'
  tertiary-container: '#743d00'
  on-tertiary-container: '#ffa85d'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dde1ff'
  primary-fixed-dim: '#b8c4ff'
  on-primary-fixed: '#001453'
  on-primary-fixed-variant: '#173bab'
  secondary-fixed: '#95f8a7'
  secondary-fixed-dim: '#79db8d'
  on-secondary-fixed: '#00210a'
  on-secondary-fixed-variant: '#005323'
  tertiary-fixed: '#ffdcc3'
  tertiary-fixed-dim: '#ffb77d'
  on-tertiary-fixed: '#2f1500'
  on-tertiary-fixed-variant: '#6e3900'
  background: '#faf8ff'
  on-background: '#131b2e'
  surface-variant: '#dae2fd'
typography:
  headline-lg:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Inter
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 30px
    letterSpacing: -0.01em
  title-lg:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  title-md:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
  label-md:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '600'
    lineHeight: 20px
  label-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 18px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  margin: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style
The design system embodies trust, proximity, and calm accessibility for a neighborhood-first trade and craft registry. Designed specifically with elderly citizens and community neighbors in mind, the aesthetic blends modern utility with comforting familiarity. The visual language avoids decorative clutter, ultra-thin line weights, and low-contrast gimmicks in favor of structural clarity, large optical targets, and explicit affordances.

The design movement is **Accessible Contemporary Utilitarian**—grounded in human-centric service design with clear cues inspired by tactile Android Material surfaces and clear physical wayfinding. The experience feels warm, reliable, deeply rooted in local neighborhood ties (*vecinal*), and safe from friction or ambiguity.

## Colors
The color architecture prioritizes cognitive simplicity and strict compliance with WCAG AAA contrast ratios for body and high-priority action items.

- **Primary Identity (`#1E40AF`)**: Deep civic blue representing safety, vetted legitimacy, and calm institutional trust. Used for top application bars, focused states, and key navigational headers.
- **Secondary Action & Direct Contact (`#15803D`)**: High-visibility foliage green reserved exclusively for primary contact vectors, immediate communication channels (such as WhatsApp CTAs), and verified resolutions.
- **Accent & Supporting Shades**:
  - Soft Blue Accent (`#EFF6FF`): Background tint for decorative icon containers, informational banners, and active tab highlights.
  - Soft Green Badge (`#DCFCE7`): Light surface container paired strictly with Deep Green Label (`#166534`) for neighborhood verification and security badges.
  - Warm Amber (`#D97706`): Dedicated solely to review stars, rating scores, and quality indicators, ensuring no competition with actionable buttons.
- **Surfaces & Neutrals**:
  - Canvas Ground (`#F8FAFC`): Soft alabaster slate minimizing screen glare for sensitive vision.
  - Card & Modal Surfaces (`#FFFFFF`): Pure white elevated zones providing crisp contrast.
  - Primary Typography (`#0F172A`): Slate-900 ensuring maximum contrast on light grounds.
  - Secondary Typography (`#475569`): Slate-600 ensuring crisp secondary hierarchy without dropping below AAA readability thresholds for medium copy.
  - Structural Borders (`#E2E8F0`): Defined division without cognitive noise.

## Typography
Typography is built exclusively on **Inter**, selected for its optical clarity, tall x-height, and open counters that remain legible under high system font-scaling settings on Android.

- Minimum standard body copy is anchored at 16px, with 18px preferred for general listing descriptions and instructions.
- Headlines range between 22px and 28px to maintain impact without wrapping awkwardly on standard viewport widths (360dp–412dp).
- Font weights are restricted to Regular (400), SemiBold (600), and Bold (700) to avoid thin letterform disintegration on medium-density screens.
- Line heights use generous multipliers (1.4x to 1.5x) to accommodate older users utilizing screen magnifiers or enlarged system font configurations.

## Layout & Spacing
The layout follows a strict, single-column fluid mobile grid built for Jetpack Compose `LazyColumn` and `Scaffold` implementations.

- Outer horizontal margins are fixed at `16dp` (`1rem`) on standard mobile widths (360dp–480dp), expanding to `24dp` (`1.5rem`) on tablets.
- Grid gutters between horizontal list items or filter chips maintain a stable `8dp` to `16dp` separation to eliminate accidental double-taps.
- Spacing rhythm utilizes a strict 4dp/8dp base unit. Vertical gaps between distinct semantic modules (e.g., worker biography to contact actions) employ `space-lg` (24dp) or `space-xl` (32dp) to give older eyes clear pauses between information blocks.

## Elevation & Depth
Elevation emphasizes tangible tactile surfaces rather than ethereal floating effects. Layers are distinguished by physical boundaries: a combination of low-intensity shadows and concrete outline borders.

- **Level 0 (Flat Ground)**: Color `#F8FAFC`. Zero elevation, pure background canvas.
- **Level 1 (Cards & Modules)**: Background `#FFFFFF`, 1dp solid border `#E2E8F0`, and an ambient diffused drop shadow: `0px 2px 4px rgba(15, 23, 42, 0.04), 0px 4px 8px rgba(15, 23, 42, 0.06)`. This defines crisp card edges even under direct outdoor sunlight.
- **Level 2 (Floating Action Bars / Bottom Navigation)**: Background `#FFFFFF`, border-top 1dp `#E2E8F0`, with `0px -4px 12px rgba(15, 23, 42, 0.06)` ensuring constant separation from scrolling content.
- **Level 3 (Modals & Confirmation Sheets)**: Accompanied by a 50% opacity scrim (`#0F172A` at 0.50 alpha) to visually mute distractions and focus attention completely.

## Shapes
Geometry conveys physical friendliness and organic safety:
- **Cards and Containers**: Bound to a corner radius of `16dp` (`rounded-lg`). This produces a distinct, contained envelope that feels approachable and never aggressive.
- **Buttons and Input Fields**: Set precisely to `12dp` radius. This maintains structural button presence while signaling clear clickable utility.
- **Badges and Pills**: Utilize fully rounded pill corners (`9999dp`) to differentiate categorical status metadata from interactive structural buttons.

## Components

### Buttons & Touch Targets
- **Primary Contact (WhatsApp CTA)**: Height is strictly at least `56dp` (exceeding standard 48dp guidelines for accessibility). Solid `#15803D` fill, white `#FFFFFF` bold 16px label, with a prominent 24dp WhatsApp brand icon anchored left. Corner radius `12dp`. Active tap state dims to `#166534`.
- **Secondary Identity Button**: Height `56dp`. Solid `#1E40AF` fill with white `#FFFFFF` text. Used for search triggers and core profile interactions.
- **Outlined / Tertiary Button**: Height `56dp`. `#FFFFFF` background, 2dp solid border `#E2E8F0`, and `#0F172A` text.
- Full button width (`fillMaxWidth()`) is enforced on mobile screens to allow effortless thumb activation without precision aiming.

### Cards (Trade & Professional Previews)
- White `#FFFFFF` surface with `16dp` corner radius, `1dp` border `#E2E8F0`, and subtle ambient elevation.
- Internal padding is generous (`16dp` to `20dp`).
- Layout structure:
  - Top row: Vetted profile image (64x64dp, 12dp radius), Trade Title (20px bold `#0F172A`), and Neighborhood label (`#475569`).
  - Middle row: Rating group with filled star icon in Amber `#D97706` alongside numeric score (16px bold `#0F172A`) and count.
  - Bottom row: Verification badge and immediate 56dp CTA button.

### Badges & Verification Tags
- **Verified Worker ("Matriculado / Verificado")**: Container background `#DCFCE7`, border `1dp` `#BBF7D0`, text color `#166534` (font size 14px, weight 600). Includes a clear shield/check icon.
- **Trade Category Pill**: Background `#EFF6FF`, text `#1E40AF`, height `36dp`, rounded-full with 12dp horizontal padding.

### Input Fields & Search
- Minimum height `56dp`.
- Background `#FFFFFF` with a 2dp border `#E2E8F0`. On focus, border shifts to 2dp `#1E40AF` with no subtle gradient shifts.
- Placeholder text in `#475569`, body text in `#0F172A` at 18px.
- Leading search icon is sized at 24dp in `#475569`. Trailing clear ("X") button is sized at 48x48dp interactive boundary for easy resetting.

### Lists & Neighborhood Filters
- List items feature clear divider lines in `#E2E8F0` with `16dp` vertical spacing.
- Radio buttons and checkboxes are scaled to 24x24dp with an explicit minimum touch-target area of 48x48dp, using `#1E40AF` when checked.

### Emergency / Urgency Alert Strip
- Surface tint in `#EFF6FF` or `#FEF3C7` (for urgent plumbing/electrical alerts), with a solid left accent border (4dp width) and explicit `#0F172A` guidance text to assist users under high stress.
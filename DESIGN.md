---
name: BloodLink Clinical Precision
colors:
  surface: '#f9f9f9'
  surface-dim: '#dadada'
  surface-bright: '#f9f9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f3'
  surface-container: '#eeeeee'
  surface-container-high: '#e8e8e8'
  surface-container-highest: '#e2e2e2'
  on-surface: '#1a1c1c'
  on-surface-variant: '#5c403f'
  inverse-surface: '#2f3131'
  inverse-on-surface: '#f0f1f1'
  outline: '#906f6e'
  outline-variant: '#e5bdbb'
  surface-tint: '#bf0229'
  primary: '#9e001f'
  on-primary: '#ffffff'
  primary-container: '#c8102e'
  on-primary-container: '#ffdad8'
  inverse-primary: '#ffb3b1'
  secondary: '#535e79'
  on-secondary: '#ffffff'
  secondary-container: '#d4dfff'
  on-secondary-container: '#57627e'
  tertiary: '#57494d'
  on-tertiary: '#ffffff'
  tertiary-container: '#6f6164'
  on-tertiary-container: '#f1dee1'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad8'
  primary-fixed-dim: '#ffb3b1'
  on-primary-fixed: '#410007'
  on-primary-fixed-variant: '#92001c'
  secondary-fixed: '#d8e2ff'
  secondary-fixed-dim: '#bac6e6'
  on-secondary-fixed: '#0f1b33'
  on-secondary-fixed-variant: '#3b4760'
  tertiary-fixed: '#f1dee2'
  tertiary-fixed-dim: '#d5c2c6'
  on-tertiary-fixed: '#23191c'
  on-tertiary-fixed-variant: '#504347'
  background: '#f9f9f9'
  on-background: '#1a1c1c'
  surface-variant: '#e2e2e2'
typography:
  headline-xl:
    fontFamily: Manrope
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 56px
    letterSpacing: -0.03em
  headline-xl-mobile:
    fontFamily: Manrope
    fontSize: 32px
    fontWeight: '800'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Manrope
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Manrope
    fontSize: 26px
    fontWeight: '700'
    lineHeight: 34px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Manrope
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Manrope
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  title-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
  body-md:
    fontFamily: Manrope
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
  label-md:
    fontFamily: Manrope
    fontSize: 13px
    fontWeight: '600'
    lineHeight: 18px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Manrope
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.04em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 3rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system establishes a clinical yet deeply humanistic healthtech aesthetic for blood logistics and urgent donation coordination. It moves deliberately away from emergency tropes, alarms, and saturated red over-saturation. Instead, it balances life-saving urgency with serene hospital-grade precision, quiet competence, and dignified empathy. 

The aesthetic is grounded in a hybrid of **Precision Minimalism** and **Tactile Tonal Layering**:
- **Tone:** Authoritative, reassuring, swift, and respectful.
- **Audience:** Voluntary donors, frantic patients and family members, hematology specialists, triage nurses, and blood bank logistics managers.
- **Emotional Response:** Calm assurance during critical times, a seamless sense of community solidarity, absolute clinical integrity, and zero visual chaos.

## Colors

Color is applied with strict surgical intention. The primary Deep Crimson (`#C8102E`) is preserved strictly for critical status calls, blood-type identifiers, vital primary actions, and immediate life-saving linkages—never splashed indiscriminately over vast backgrounds.

- **Primary (`#C8102E`):** Deep Crimson. Represents vitality, vital urgency, and core donor calls to action.
- **Secondary (`#17233B`):** Midnight Navy. Provides an unshakeable institutional foundation for primary text, deep structural framing, navigation bars, and authoritative headers.
- **Tertiary (`#FCE8EC`):** Soft Rose. Used for high-priority notification badges, interactive hover states, donor impact metrics, and gentle highlight backdrops.
- **Neutral Surface Canvas (`#FAFAFA`):** Warm clinical white base canvas. Eliminates cold sterility while keeping the view pristine and low-fatigue.
- **Containers & Elevated Cards (`#FFFFFF`):** Pure white modules delivering crisp separation over the `#FAFAFA` field.
- **Structural Lines (`#E2E8F0`, `#F1F5F9`):** Ghost borders to maintain structure without dark cognitive weight.

## Typography

The platform utilizes **Manrope** across all typographic touchpoints. Its geometric clarity, rounded apexes, and open aperture retain warmth while offering high legibility in time-critical emergency scenarios.

- **Headlines:** Set with deliberate negative tracking (`-0.02em` to `-0.03em`) and heavy weights (`700`–`800`) to communicate institutional authority and clarity.
- **Data & Blood Units:** When displaying blood types (e.g., O-, AB+) and volume counts, use tabular numbers with `label-md` or `headline-md` weights to prevent jitter across dynamically updating telemetry feeds.
- **Mobile Readability:** Viewports under 768px systematically step down display sizes via dedicated mobile tokens (`headline-xl-mobile`, `headline-lg-mobile`) to protect vertical hierarchy.

## Layout & Spacing

The layout is architected around an 8-point spatial system within a flexible 12-column grid:
- **Desktop (1024px+):** 12-column fluid grid, capped at a maximum width of `1280px`, with `margin: 3rem` outer bounds and `gutter: 1.5rem`.
- **Tablet (768px – 1023px):** 8-column layout with `gutter: 1rem` and `margin: 2rem`.
- **Mobile (< 768px):** 4-column layout with `margin-mobile: 1.25rem` and `gutter-mobile: 1rem`. Content flows single-column for immediate, single-thumb emergency interaction.

Components maintain strict spatial independence using `space-md` (`1rem`) for standard inner padding and `space-lg` (`1.5rem`) to frame primary card surfaces.

## Elevation & Depth

Depth is established through soft ambient occlusion combined with crisp perimeter containment, ensuring cards feel grounded on the `#FAFAFA` foundation without harsh drop shadows.

- **Level 0 (Base Canvas):** Pure neutral background (`#FAFAFA`) with no shadow.
- **Level 1 (Clinical Cards & Blood Bank Nodes):** Surface `#FFFFFF`, bounded by a hairline stroke (`1px solid #F1F5F9`) and layered ambient shadow:
  - `0 1px 3px rgba(23, 35, 59, 0.03), 0 6px 16px -2px rgba(23, 35, 59, 0.04)`
- **Level 2 (Active Emergency Requests & Hover States):** Surface `#FFFFFF`, stroke (`1px solid #E2E8F0`), elevated shadow with soft Midnight Navy dissipation:
  - `0 4px 6px -1px rgba(23, 35, 59, 0.05), 0 12px 24px -4px rgba(23, 35, 59, 0.08)`
- **Level 3 (Modals & Real-Time Donor Match Overlays):** Surface `#FFFFFF` over an ambient backdrop backdrop-blur:
  - `0 20px 32px -6px rgba(23, 35, 59, 0.12), 0 8px 16px -4px rgba(23, 35, 59, 0.06)`
- **Urgent Priority Accentuation:** In urgent donor distress states, elevation is paired with an inner border glow tinted in Soft Rose (`box-shadow: 0 0 0 2px #FCE8EC`).

## Shapes

The design uses a refined shape scale based on roundedness level `2`:
- **Default Elements (`16px` / `1rem`):** Applied to buttons, search filters, form fields, and secondary metrics.
- **Large Surfaces (`24px` / `1.5rem`):** Applied to primary cards, hospital detail views, and real-time inventory panels (`rounded-xl`).
- **Full Radius (Pill):** Reserved strictly for dynamic status badges, active donor distance tags, and blood-type markers (`rounded-full`).

## Components

### Buttons
- **Primary Urgent ("Request Blood" / "Donate Now"):** Deep Crimson (`#C8102E`) background, `#FFFFFF` text, `16px` border-radius, `space-md` vertical padding. Subtle inner highlight on hover (`brightness: 1.05`).
- **Secondary ("Hospital Directory" / "View History"):** Midnight Navy (`#17233B`) solid background or pure white surface with a `1.5px solid #17233B` border and matching text.
- **Tertiary / Gentle Action:** Soft Rose (`#FCE8EC`) background with Deep Crimson (`#C8102E`) text; zero outline, highly accessible touch target.

### Blood Group Badges & Chips
- Circular or pill-shaped tokens with high-contrast information.
- Background: Soft Rose (`#FCE8EC`) with `#C8102E` bold typography for standard tags; Midnight Navy (`#17233B`) background with pure white text for rare/depleted reserves (e.g., O-Negative).

### Cards & Dispatch Panels
- Pure white container (`#FFFFFF`), `16px` to `24px` radius, hairline `#E2E8F0` border.
- Split metadata grid displaying: Recipient hospital name, distance (km), blood type required, and real-time verification badge.

### Inputs & Triage Selectors
- Background: `#FFFFFF`. Border: `1px solid #E2E8F0`. Focus state: `2px solid #C8102E` with a subtle `4px` ring in `#FCE8EC`.
- In-field labels use `label-md` in Midnight Navy (`#17233B`) with secondary helper hints in muted slate.

### Real-Time Live Status Tracking
- Pulsing status dots utilizing `#C8102E` with soft ring animation to signal an active transit van, approved dispatch, or urgent local blood plea.
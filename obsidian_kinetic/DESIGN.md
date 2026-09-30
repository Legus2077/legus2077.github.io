---
name: Obsidian Kinetic
colors:
  surface: '#0d131f'
  surface-dim: '#0d131f'
  surface-bright: '#333946'
  surface-container-lowest: '#080e19'
  surface-container-low: '#161c27'
  surface-container: '#1a202b'
  surface-container-high: '#242a36'
  surface-container-highest: '#2f3541'
  on-surface: '#dde2f3'
  on-surface-variant: '#c2c6d6'
  inverse-surface: '#dde2f3'
  inverse-on-surface: '#2a303d'
  outline: '#8c90a0'
  outline-variant: '#424654'
  surface-tint: '#b1c6ff'
  primary: '#b1c6ff'
  on-primary: '#002c70'
  primary-container: '#578cff'
  on-primary-container: '#002662'
  inverse-primary: '#0057cd'
  secondary: '#7bd0ff'
  on-secondary: '#00354a'
  secondary-container: '#00a6e0'
  on-secondary-container: '#00374d'
  tertiary: '#b7c7ea'
  on-tertiary: '#20304d'
  tertiary-container: '#8191b2'
  on-tertiary-container: '#192a45'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#d9e2ff'
  primary-fixed-dim: '#b1c6ff'
  on-primary-fixed: '#001946'
  on-primary-fixed-variant: '#00419d'
  secondary-fixed: '#c4e7ff'
  secondary-fixed-dim: '#7bd0ff'
  on-secondary-fixed: '#001e2c'
  on-secondary-fixed-variant: '#004c69'
  tertiary-fixed: '#d7e2ff'
  tertiary-fixed-dim: '#b7c7ea'
  on-tertiary-fixed: '#091b36'
  on-tertiary-fixed-variant: '#374764'
  background: '#0d131f'
  on-background: '#dde2f3'
  surface-variant: '#2f3541'
typography:
  display-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 56px
    fontWeight: '800'
    lineHeight: 64px
    letterSpacing: -0.03em
  display-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '800'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 26px
    fontWeight: '700'
    lineHeight: 34px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
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
    letterSpacing: '0'
  body-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: '0'
  label-code:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 18px
    letterSpacing: 0.02em
  label-mono-sm:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.04em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
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

This design system crafts an elite, high-precision engineering portfolio atmosphere. It projects computational rigor, architectural clarity, and modern technical excellence. Tailored for senior staff engineers, systems architects, and technical leaders, the aesthetic merges technical minimalism with measured glassmorphism and radiant bioluminescent accents.

The emotional impression is focused, calculated, and high-performance. Visual cues draw from advanced code execution runtimes, telemetry dashboards, and low-level system tooling. Interactions favor swift kinetic feedback, razor-sharp edge transitions, and subtle radial gradient glows that illuminate interactive nodes beneath the surface.

## Colors

The palette establishes high-contrast readability against a deep cosmic ocean base.

- **Primary Background (`#070d18`)**: Deep obsidian-navy foundation, grounding full-bleed layouts and neutralizing ambient glare.
- **Card Surface (`#0b1526`)**: Tonal elevation substrate, rendered slightly transparent (`rgba(11, 21, 38, 0.75)`) when paired with backdrop filters.
- **Structural Borders (`#1e2e4a`)**: Defines structural edges, preventing bleeding between dark tiers without introducing stark visual noise.
- **Primary Accent (`#3d7bf5`)**: High-flux cobalt blue reserved for primary actions, active telemetry indicators, and focused link anchors.
- **Secondary Highlight (`#38bdf8`)**: Electric cyan used selectively for inline tokens, metadata tags, commit indicators, and glowing halos.
- **Primary Text (`#f1f5f9`)**: Pure light slate for high-priority headings and code blocks.
- **Muted Text (`#94a3b8`)**: Calibrated slate for secondary details, metadata, dates, and subtle borders.

## Typography

The typographic hierarchy implements an engineering-centric tripartite structure:

- **Headlines (Plus Jakarta Sans)**: Provides sharp, geometric impact with tight tracking to form compact visual headers.
- **Body Text (Inter)**: Delivers neutral, highly legible reading paths optimized for engineering narratives, project retrospectives, and architecture summaries.
- **Data & Micro-Labels (JetBrains Mono)**: Encodes version stamps, Git hashes, hardware metrics, tech stack tags, and execution logs.

## Layout & Spacing

A 12-column responsive fluid grid governs desktop environments, scaling down to an 8-column layout on tablets and a 4-column column flow on mobile screens. Maximum container constraints lock at `1280px` to maintain optimal line lengths for technical write-ups.

- **Desktop (≥ 1024px)**: `margin: 3rem`, `gutter: 1.5rem`.
- **Tablet (640px – 1023px)**: `margin: 2rem`, `gutter: 1.25rem`.
- **Mobile (< 640px)**: `margin: 1.25rem`, `gutter: 1rem`.

Vertical flow enforces an 8pt modular rhythm. Sub-component padding strictly adheres to the inner spacing tokens (`space-xs` through `space-xl`), ensuring compact density within code snippets and metrics boards.

## Elevation & Depth

Visual hierarchy leverages a hybrid model of dark tonal layering, frosted glass refraction, and selective bioluminescent light emission:

- **Base Layer (Flat)**: Background canvas `#070d18` with zero shadow. A faint radial grid pattern (`rgba(30, 46, 74, 0.25)` 1px dots on 24px pitch) may overlay the viewport.
- **Surface Layer 1 (Card & Module)**: Backdrop fill `rgba(11, 21, 38, 0.75)` with `backdrop-filter: blur(12px)`. Outlined with a 1px solid border of `#1e2e4a`. Shadow: `0 4px 20px -2px rgba(0, 0, 0, 0.5)`.
- **Surface Layer 2 (Interactive Floating & Modals)**: Fill `rgba(14, 27, 49, 0.9)` with `backdrop-filter: blur(16px)`. Border: `1px solid rgba(56, 189, 248, 0.3)`. Shadow: `0 12px 32px -4px rgba(0, 0, 0, 0.7), 0 0 24px -4px rgba(61, 123, 245, 0.15)`.
- **Glow Accents**: Primary action buttons and focal indicators emit soft, diffused radial blurs: `0 0 20px rgba(61, 123, 245, 0.35)`.

## Shapes

The interface embraces a precise, modern structural geometry:

- **Baseline Components**: Buttons, inputs, inline badges, and cards use soft structural radiuses (`0.25rem` / `4px` to `0.5rem` / `8px`).
- **Data Containers**: Outer containers maintain disciplined, low-curvature profiles to echo terminal interfaces and hardware consoles.
- **Status Pills & Indicators**: Rounded pills (`9999px`) are exclusively used for live ping markers, deploy tags, and runtime indicators.

## Components

### Buttons
- **Primary**: Solid background `#3d7bf5`, typography `Inter` (semibold, 14px), text `#f1f5f9`. Smooth transition (`200ms ease-out`). Hover introduces a cyan fringe: `box-shadow: 0 0 16px rgba(56, 189, 248, 0.4)`. Active states compress by `transform: scale(0.98)`.
- **Secondary / Ghost**: Background `rgba(11, 21, 38, 0.6)`, border `1px solid #1e2e4a`, text `#94a3b8`. Hover shifts border to `#38bdf8` and text to `#f1f5f9`.

### Cards & Project Containers
- Built on `rgba(11, 21, 38, 0.8)` with a 1px `#1e2e4a` border and 8px border-radius.
- On hover, borders dynamically transition from `#1e2e4a` to `rgba(61, 123, 245, 0.6)`, accompanied by an ambient internal radial gradient that follows the cursor coordinate.

### Chips & Tech Stack Badges
- Background `rgba(30, 46, 74, 0.4)`, text `#38bdf8`, font `JetBrains Mono` (12px, medium).
- Border: `1px solid rgba(56, 189, 248, 0.2)`. Padding: `2px 8px`.

### Input Fields & Terminal Consoles
- Background `#070d18`, border `1px solid #1e2e4a`, text `#f1f5f9`, placeholder `#94a3b8`.
- Focus creates a crisp dual-layer ring: `border-color: #38bdf8`, `box-shadow: 0 0 0 1px #38bdf8, 0 0 12px rgba(56, 189, 248, 0.2)`.

### Checkboxes & Radios
- Box size `16px x 16px`, background `#0b1526`, border `1px solid #1e2e4a`.
- Checked state fills `#3d7bf5` with a `#f1f5f9` check icon, surrounded by an ambient blue glow.

### Engineering-Specific Components
- **Architecture Metric Tiles**: Compact cards housing real-time performance indicators (e.g., `<10ms latency`, `99.99% uptime`), featuring micro-sparklines in `#38bdf8`.
- **Code Execution Blocks**: Dark background `#05080f` framed with `#1e2e4a` borders, top window bar with discrete traffic light accents, and custom line number gutters in `#94a3b8`.
---
name: Orbital Precision
colors:
  surface: '#101321'
  surface-dim: '#101321'
  surface-bright: '#363848'
  surface-container-lowest: '#0a0d1b'
  surface-container-low: '#181b29'
  surface-container: '#1c1f2e'
  surface-container-high: '#262938'
  surface-container-highest: '#313444'
  on-surface: '#e0e1f6'
  on-surface-variant: '#cbc3d7'
  inverse-surface: '#e0e1f6'
  inverse-on-surface: '#2d303f'
  outline: '#958ea0'
  outline-variant: '#494454'
  surface-tint: '#d0bcff'
  primary: '#d0bcff'
  on-primary: '#3c0091'
  primary-container: '#a078ff'
  on-primary-container: '#340080'
  inverse-primary: '#6d3bd7'
  secondary: '#7bd0ff'
  on-secondary: '#00354a'
  secondary-container: '#00a6e0'
  on-secondary-container: '#00374d'
  tertiary: '#4cd7f6'
  on-tertiary: '#003640'
  tertiary-container: '#009eb9'
  on-tertiary-container: '#002f38'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e9ddff'
  primary-fixed-dim: '#d0bcff'
  on-primary-fixed: '#23005c'
  on-primary-fixed-variant: '#5516be'
  secondary-fixed: '#c4e7ff'
  secondary-fixed-dim: '#7bd0ff'
  on-secondary-fixed: '#001e2c'
  on-secondary-fixed-variant: '#004c69'
  tertiary-fixed: '#acedff'
  tertiary-fixed-dim: '#4cd7f6'
  on-tertiary-fixed: '#001f26'
  on-tertiary-fixed-variant: '#004c69'
  background: '#101321'
  on-background: '#e0e1f6'
  surface-variant: '#313444'
typography:
  display-lg:
    fontFamily: Sora
    fontSize: 56px
    fontWeight: '700'
    lineHeight: 64px
    letterSpacing: -0.03em
  display-lg-mobile:
    fontFamily: Sora
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Sora
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Sora
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Sora
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Geist
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: -0.005em
  body-md:
    fontFamily: Geist
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0em
  body-sm:
    fontFamily: Geist
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
    letterSpacing: 0.01em
  label-lg:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 18px
    letterSpacing: 0.04em
  label-md:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.06em
  label-sm:
    fontFamily: JetBrains Mono
    fontSize: 10px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.08em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-sm: 1rem
  gutter-lg: 2rem
  margin: 2rem
  margin-sm: 1rem
  margin-lg: 3rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

# Design System: Orbital Precision (LaunchPad)

This design system embodies the calculated precision, infinite depth, and high-velocity execution of next-generation aerospace technology. Designed for orbital engineers, payload operators, telemetry directors, and deep-tech SaaS developers, the aesthetic merges technical command-center density with refined, luminous glassmorphism.

---

## 🎨 Color Palette

### Core Palette

| Role | Color Name | Hex Code | Visual Sample / Description |
| :--- | :--- | :--- | :--- |
| **Deep Void Canvas** | Deep Space Black | `#0A0D1B` | Base canvas, infinite viewport |
| **Surface Base** | Void Surface | `#101321` | Primary background surface |
| **Surface Low** | Console Slate | `#181B29` | Lower elevation card / panel layer |
| **Surface Container** | Tech Surface | `#1C1F2E` | Default container / panel background |
| **Surface High** | High Slate | `#262938` | Elevated card layer |
| **Surface Highest** | Boundary Slate | `#313444` | Highest surface layer |
| **Surface Bright** | Active Focus Surface | `#363848` | Interactive highlighted surface |
| **Primary** | Electric Violet | `#D0BCFF` | Primary action & active telemetry states (`#8B5CF6` base) |
| **Primary Container** | Violet Glow | `#A078FF` | High-energy containers & accents |
| **On Primary** | Deep Violet Core | `#3C0091` | High-contrast text on primary |
| **Secondary** | Ion Cyan | `#7BD0FF` | Data packets, nominal metrics, vector arrows |
| **Secondary Container** | Cyan Wave | `#00A6E0` | Active secondary vector highlights |
| **Tertiary** | Radiant Aqua | `#4CD7F6` | Sensor readouts & system status badges |
| **Tertiary Container** | Deep Sea Cyan | `#009EB9` | Sub-panel highlights |
| **Text Primary** | Polar White | `#E0E1F6` | High-contrast legibility for vital typography |
| **Text Secondary** | Atmospheric Mist | `#CBC3D7` | Secondary text, sub-labels, metadata |
| **Outline** | Cosmic Gray | `#958EA0` | Structural borders & dividing keylines |
| **Outline Variant** | Hairline Muted | `#494454` | Faint container borders |
| **Nominal (Success)** | Pulse Emerald | `#10B981` | Live systems, successful trajectory, nominal locks |
| **Warning** | Telemetry Amber | `#F59E0B` | Variance alerts, staging warnings |
| **Error / Abort** | Mission Crimson | `#FFB4AB` / `#F43F5E` | Hardware failsafes, trajectory aborts |

---

## 🔤 Typography

### Typographic Hierarchy

- **Display & Headings:** `Sora` (Geometric, wide aperture, aerospace authority)
- **Body & Continuous Copy:** `Geist` (Disciplined, high pixel density, low fatigue)
- **Labels, Telemetry & Code:** `JetBrains Mono` (Monospaced, tabular numbers, zero-jitter telemetry)

### Type Scale Reference

| Style Name | Font Family | Size | Weight | Line Height | Letter Spacing | Purpose |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| `display-lg` | Sora | 56px | 700 (Bold) | 64px | `-0.03em` | Primary hero display headlines |
| `display-lg-mobile` | Sora | 36px | 700 (Bold) | 44px | `-0.02em` | Responsive mobile hero titles |
| `headline-lg` | Sora | 32px | 600 (SemiBold) | 40px | `-0.02em` | Major module headings |
| `headline-md` | Sora | 24px | 600 (SemiBold) | 32px | `-0.015em` | Card & section headers |
| `headline-sm` | Sora | 20px | 600 (SemiBold) | 28px | `-0.01em` | Panel titles & metric category headers |
| `body-lg` | Geist | 16px | 400 (Regular) | 24px | `-0.005em` | Lead paragraphs & briefing descriptions |
| `body-md` | Geist | 14px | 400 (Regular) | 20px | `0em` | Standard interface copy & explanations |
| `body-sm` | Geist | 12px | 400 (Regular) | 16px | `0.01em` | Secondary notes, captions, footnotes |
| `label-lg` | JetBrains Mono | 13px | 500 (Medium) | 18px | `0.04em` | Primary buttons, telemetry coordinates |
| `label-md` | JetBrains Mono | 11px | 500 (Medium) | 16px | `0.06em` | Badges, tabular values, timestamp badges |
| `label-sm` | JetBrains Mono | 10px | 500 (Medium) | 14px | `0.08em` | Micro badges, status pills, index tags |

---

## 📐 Spacing & Layout

The layout system operates on an 8pt architectural rhythm:

```
space-xs: 0.25rem (4px)
space-sm: 0.5rem (8px)
space-md: 1.0rem (16px)
space-lg: 1.5rem (24px)
space-xl: 2.0rem (32px)
```

- **Desktop (1200px+):** 12-column grid, `2rem` outer margins, `1.5rem` gutters.
- **Tablet (768px – 1199px):** 8-column layout, `1.5rem` margins, `1rem` gutters.
- **Mobile (320px – 767px):** 4-column layout, `1rem` margins, `0.75rem` gutters.

---

## 🔮 Elevation & Glow Effects

Depth utilizes dark-field glassmorphism and ambient luminescence instead of standard black shadows:

- **Surface 0 (Deep Canvas):** Solid midnight abyss (`#0A0D1B`)
- **Surface 1 (Structural Panels):** Translucent obsidian (`#0F172A` at 65%–80% opacity) + `backdrop-filter: blur(16px)` + border `rgba(255, 255, 255, 0.08)`
- **Surface 2 (Elevated Overlays):** Semi-opaque composite (`#1E293B` at 75% opacity) + `backdrop-filter: blur(24px)` + border `rgba(255, 255, 255, 0.15)`
- **Resting Shadow:** `box-shadow: 0 4px 20px -2px rgba(0, 0, 0, 0.5)`
- **Active / Primary Violet Glow:** `box-shadow: 0 0 25px -4px rgba(139, 92, 246, 0.35), inset 0 0 12px 0 rgba(139, 92, 246, 0.15)`
- **Ion Cyan Vector Glow:** `box-shadow: 0 0 25px -4px rgba(56, 189, 248, 0.35), inset 0 0 12px 0 rgba(56, 189, 248, 0.15)`

---

## 🧩 Components Guide

### Buttons
- **Primary Propulsion Button:** `linear-gradient(135deg, #8B5CF6 0%, #7C3AED 100%)`, uppercase text in `JetBrains Mono` (`label-lg`), outer hover glow `rgba(139, 92, 246, 0.4)`.
- **Secondary Ion Button:** Translucent navy background with cyan hairline border (`rgba(56, 189, 248, 0.4)`), cyan hover glow.
- **Ghost Action:** Pure transparent background with subtle border (`rgba(255, 255, 255, 0.1)`), brightens on hover.

### Badges & Status Pills
- **Geometry:** 9999px pill (`rounded-full`), `label-sm` (`JetBrains Mono`).
- **Nominal / Live:** `#06B6D4` background tint (15%), `#38BDF8` text, pulsing cyan dot indicator.
- **Standby / Staging:** `#8B5CF6` background tint (15%), `#C084FC` text.
- **Anomaly / Alert:** `#F43F5E` background tint (15%), `#FB7185` text.

### Telemetry Cards
- Glass containers (`rgba(15, 23, 42, 0.70)`), `backdrop-filter: blur(16px)`, border `rgba(255, 255, 255, 0.08)`.
- Header incorporates monospaced coordinate/sensor IDs and real-time status indicators separated by hairline border `rgba(255, 255, 255, 0.06)`.

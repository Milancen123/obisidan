# Foundations (Client-First System)

## Purpose
Defines the global rules, design tokens, and base decisions for all Webflow projects.

This file ensures consistency across:
- Layout
- Spacing
- Typography
- Components

Everything must follow this system.

---

## 1. Design Principles

- Reuse before creating new classes
- Use descriptive, readable class names
- Avoid styling combo classes unless necessary
- Keep structure predictable across pages
- Build mobile-friendly layouts by default

---

## 2. Color System

## Primary Colors
- primary-1: #FAFAF7
- primary-2: D8F3DC
- primary-3:  #009999

## Neutral Colors
- neutral-100: #D9D9D9
- neutral-200: #4B4B4B
- white: #FFFFFF
- neutral-400: #1E1E1E
- neutral-500:
- gray: #ECECEC

## Semantic Colors
- success:
- warning:
- error:

## Rules
- Never hardcode colors inside components
- Always reuse color tokens
- Match colors from Figma exactly

---

## 3. Spacing Scale

## Base Unit
- 4px system (recommended)

## Spacing Values
- space-4 → 4px
- space-8 → 8px
- space-12 → 12px
- space-16 → 16px
- space-24 → 24px
- space-32 → 32px
- space-40 → 40px
- space-48 → 48px
- space-64 → 64px
- space-80 → 80px
- space-96 → 96px

## Rules
- Only use values from this scale
- No random spacing (e.g. 18px, 22px)
- Match spacing rhythm across sections

---

## 4. Container System

## container-main
- max-width: 1200px
- margin: auto
- width: 100%

## container-large
- max-width: 1400px

## container-small
- max-width: 800px

## Rules
- Always wrap content inside a container
- Never place content directly in section
- Containers control width, not padding

---

## 5. Breakpoints (Webflow)

## Desktop
- Default (base styles)

## Tablet
- ≤ 991px

## Mobile Landscape
- ≤ 767px

## Mobile Portrait
- ≤ 479px

## Rules
- Design desktop first
- Then adjust downward
- Avoid pixel-perfect obsession — keep logic

---

## 6. Layout Rules

- Use flexbox as primary layout system
- Use grid only when necessary
- Avoid deep nesting of divs
- Keep structure clean and readable

---

## 7. Naming Convention

## Structure
[type]-[purpose]-[variation]

## Examples
- container-main
- section-hero
- text-size-large
- button-primary
- padding-global

## Rules
- Use lowercase only
- Use hyphens (no underscores)
- Names must describe purpose, not appearance

---

## 8. Typography Rules

- Define all sizes before building sections
- Use consistent naming (heading-h1, text-size-medium)
- Avoid styling text directly inside sections

---

## 9. Component Philosophy

- Components must be reusable
- Avoid page-specific styling
- Keep components independent

---

## 10. Workflow Rule (IMPORTANT)

For every new element:

1. Check if class already exists
2. If yes → reuse it
3. If no → create it AND document it in Obsidian

---

## 11. Connection to Other Notes

[[container-main]]
[[padding-global]]
[[heading-h1]]
[[button-primary]]
[[section-hero]]

---

## 12. Notes (Customize from Figma)

- Update colors from design
- Adjust spacing scale if needed
- Define typography based on design system
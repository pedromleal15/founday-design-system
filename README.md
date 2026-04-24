# Founday — Design System

Interactive design system extracted from Figma (`W32edVsk3tnXN7dFKF0lvE`) via MCP.
Single-file HTML with foundations, components and the four Replenishment screens.

## Contents

- **Foundations** — colors, typography, spacing, radius, elevation, icons
- **Components** — Button, Input, Select, Checkbox, Badge, Segmented, Day Picker, Tabs, Card, Table, Nav Rail
- **Screens** — Home (Replenishment list), Step 1 (New Replenishment form), Step 2 (Configuration Setup), Step 3 (Review & Submit)

## Run locally

Just open `index.html` in a browser. No build step.

```bash
open index.html          # macOS
xdg-open index.html      # Linux
```

## Stack

Vanilla HTML + CSS (CSS variables for tokens) + vanilla JS. Inter from Google Fonts. Lucide-style inline SVG icons.

## Source of truth

Tokens confirmed from Figma: `#0a0a0a`, `#717182`, `#e5e7eb` (shadcn/radix-like vocabulary). Semantic palette inferred from the 4 top-level frames and the Menu symbol (`1:377`).

---
Built by Pedro (Senior Product Designer).

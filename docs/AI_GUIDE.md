# AI Guide

DWCSS is written for humans and AI to share the same structure.

## Core Instructions

- Treat `dw.css` as the layout layer.
- Treat `contracts/` as the visual identity layer.
- Treat `extensions/` as reusable pattern layers.
- Do not mix layout and skin.
- Keep existing `dw-` class names stable.
- Prefer existing DWCSS classes before creating new ones.
- Add new layout utilities only when the pattern is reusable.

## Page Region Thinking

Do not think only in columns. Think in regions with jobs:

- navigation
- page header/context
- filters/tabs
- primary content
- secondary/inspector content
- action rail
- status/footer
- modals/drawers

Navigation is not automatically the header. Navigation is its own region.

## Free And Pro Boundary

This public repo may document Pro ideas, but paid implementation source belongs in:

`ddsurfdws/dwcsspaid`

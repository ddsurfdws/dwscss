# Getting Started With DWCSS Core

DWCSS is layout-first. Start by choosing structure, then attach visual contracts.

## 1. Load Core

```html
<link rel="stylesheet" href="../core/dw.css">
```

## 2. Load A Contract

```html
<link rel="stylesheet" href="../core/contracts/dw-palette.css">
<link rel="stylesheet" href="../core/contracts/dw-typography.css">
<link rel="stylesheet" href="../core/contracts/dw-background.css">
<link rel="stylesheet" href="../core/contracts/dw-motion.css">
```

## 3. Load Extensions As Needed

```html
<link rel="stylesheet" href="../core/extensions/dw-layout.css">
<link rel="stylesheet" href="../core/extensions/dw-data.css">
<link rel="stylesheet" href="../core/extensions/dw-forms-advanced.css">
<link rel="stylesheet" href="../core/extensions/dw-navigation.css">
<link rel="stylesheet" href="../core/extensions/dw-overlays.css">
<link rel="stylesheet" href="../core/extensions/dw-states.css">
```

## Layer Rule

- `dw.css` owns stable layout primitives.
- `contracts/` owns color, type, background, and motion.
- `extensions/` owns reusable higher-level layout patterns.
- Pro implementation source belongs in `ddsurfdws/dwcsspaid`.

## AI Rule

When editing DWCSS pages, keep the class vocabulary stable. Do not move color, type, background, or motion decisions into layout classes.

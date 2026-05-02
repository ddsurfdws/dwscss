# DWCSS Code Boundary

This repository is the free/core DWCSS product.

## Free/Core Headers

Important free files should carry a small header like:

```css
/*!
 * DWCSS Core
 * Repository: ddsurfdws/dwscss
 * Boundary: Free/Core
 * Role: Stable layout primitives and framework-neutral structure.
 */
```

## Core Extension Headers

Reusable free extensions should carry:

```css
/*!
 * DWCSS Core Extension
 * Repository: ddsurfdws/dwscss
 * Boundary: Free/Core
 * Role: Reusable layout/data/form/navigation primitive.
 */
```

## Pro Preview Headers

Public demo files that describe Pro behavior without shipping Pro source should carry:

```css
/*!
 * DWCSS Pro Preview
 * Repository: ddsurfdws/dwscss
 * Boundary: Free/Core documentation and Pro behavior preview.
 * Production Pro source belongs in ddsurfdws/dwcsspaid.
 */
```

## Rule

If a file is real paid implementation source, it belongs in `ddsurfdws/dwcsspaid`, not this public repository.

Copyright (c) 2026 David D Fischer. All rights reserved unless a separate license says otherwise.

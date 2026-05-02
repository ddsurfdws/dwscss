# Free and Pro Boundary

This repository is intended for the public/free DWCSS core.

## Public / Free

Public code may include:

- Core layout primitives
- Basic examples
- Starter contracts
- AI-readable documentation
- Framework-neutral showcase snippets
- Public website documentation

## Keep Out of Public Repo Unless Intentionally Released

Do not place these in the public repository by accident:

- UI/UIX builder source
- Paid templates
- Stripe or shop internals
- Private automation scripts
- Customer project code
- Pro-only bridges
- Pro-only generated contract tools
- Private keys, tokens, credentials, or deployment secrets

## Recommended Folder Boundary

```text
core/
  dw.css
  extensions/
  contracts/

docs/
  examples/
  ai-guide/

pro/
  README.md
```

The `pro/` folder in this public repo should contain descriptions or links only, not paid source code.

## Rule

If source code is committed to this public repository, assume people can see it, clone it, and study it. Keep paid implementation source in a private repository or private package.

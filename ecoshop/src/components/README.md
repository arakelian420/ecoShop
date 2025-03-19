# Components Directory

This directory contains all React components used in the application.

## Structure
- `ui/`: Shared UI components used across the application
- `features/`: Feature-specific components

## Ownership
- `ui/`: Shared between both developers (changes require notification)
- `features/cart/`: Developer 1
- `features/products/`: Developer 2

## Component Documentation Requirements
Each component must include:
```tsx
/**
 * @component [ServerComponent|ClientComponent]
 * @owner [Developer1|Developer2]
 * @status [WIP|REVIEW|STABLE|DEPRECATED]
 * @lastModified YYYY-MM-DD
 * @description Purpose of this component
 */
``` 
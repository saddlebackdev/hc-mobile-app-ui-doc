# Layout Utilities

## addHitSlop

Returns an object to be used as a value for hitslop

### Params

```typescript
addHitSlop(top: number, right: number, bottom: number, left: number)
```

### Usage

```jsx
import { LayoutUtils } from 'hc-mobile-app-ui';

// Add 12px to all sides
const touchableArea = LayoutUtils.addHitSlop(12);

// Add 12px to top and 25px to bottom
const touchableArea = LayoutUtils.addHitSlop(12, 0, 24);

// Add 12px to vertical and 24px to horizontal sides
const touchableArea = LayoutUtils.addHitSlop(12, 24);

// Add different sizes to different sides (T, R, D, L)
const touchableArea = LayoutUtils.addHitSlop(12, 13, 14, 15);
```

# Layout Primitives

To maintain consistent spacing throughout the app, layouts should adhere to only using two metric units namely major and minor.

### Major Scale

1 unit of major scale is equal to 11px. MAU provides a utility function that allows you to use the major scale and its multiples in your design.

#### Usage

```jsx
import { majorScale } from 'hc-mobile-app-ui';

// Single Unit
margin-top: majorScale(1); // i.e. 11*1

// Multiple Units
margin-top: majorScale(4); // i.e. 11*4
```

### Minor Scale

1 unit of minor scale is equal to 5px. MAU provides a utility function that allows you to use the minor scale and its multiples in your design.

#### Usage

```jsx
import { minorScale } from 'hc-mobile-app-ui';

// Single Unit
margin-top: minorScale(1); // i.e. 5*1

// Multiple Units
margin-top: minorScale(4); // i.e. 5*4
```

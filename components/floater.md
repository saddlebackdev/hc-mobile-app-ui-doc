# Floater

Floater allows one or more components to be relatively/absolutely positioned anywhere on the screen.

### Installation

```jsx
import { Floater, FloaterProps } from 'hc-mobile-app-ui';
```

### Example

{% embed url="https://snack.expo.dev/@rrizk/mau---floating-button" %}

### Props

| Name         | Type                 | Description                                            |
| ------------ | -------------------- | ------------------------------------------------------ |
| position     | absolute \| relative | Determines the position of this element in the layout. |
| alignment    | top \| bottom        | Aligns the element on the screen.                      |
| offsetTop    | number               | Adds padding from the top.                             |
| offsetRight  | number               | Adds padding from the right.                           |
| offsetBottom | number               | Adds padding from the bottom.                          |
| offsetLeft   | number               | Adds padding from the left.                            |

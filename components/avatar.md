# Avatar

### Installation

```jsx
import { Avatar, AvatarProps } from 'hc-mobile-app-ui';
```

### Example



### Props

| Name               | Type                          | Description                                                                    |
| ------------------ | ----------------------------- | ------------------------------------------------------------------------------ |
| uri                | string                        | URL of the image.                                                              |
| size               | 'tile' \| 'profile' \| number | Size of the Avatar                                                             |
| radius             | 'none' \| 'small' \| 'full'   | Adds border radius of the specified size.                                      |
| initials           | string                        | Shows the initials as placeholder when image is unavailable.                   |
| marker             | ReactElement                  | A React element to be rendered over the bottom-right corner of the image/icon. |
| markerOffsetRight  | number                        | Position of marker from right side.                                            |
| markerOffsetBottom | number                        | Position of marker from bottom.                                                |
| inversed           | boolean                       | Renders a white icon instead of black.                                         |
| onPress            | function                      | Function to be called when the avatar is pressed.                              |


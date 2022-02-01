# Expandable Card

### Installation

```jsx
import { ExpandableCard, ExpandableCardProps } from 'hc-mobile-app-ui';
```

### Example



### Props

| Name           | Type         | Description                                                                                      |
| -------------- | ------------ | ------------------------------------------------------------------------------------------------ |
| isOpen         | boolean      | Flag to specify whether the card is open or not.                                                 |
| tileColor      | string       | Color of the tile on the left. Should be a color name from the theme. Defaults to secondaryDark. |
| tileContent    | ReactElement | A react element to be rendered inside the colored tile on the left.                              |
| subTitle       | string       | Subtitle for the card.                                                                           |
| title          | string       | Title for the card.                                                                              |
| onPress        | function     | Toggle function for the tile.                                                                    |
| inversed       | boolean      | Inversed variant for the tile when collapsed.                                                    |
| subTitleMarker | ReactElement | A react element to be rendered beside the card subtitle when closed.                             |
| titleMarker    | ReactElement | A react element to be rendered beside the card title when closed.                                |


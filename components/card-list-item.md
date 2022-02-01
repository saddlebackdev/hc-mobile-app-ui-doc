# Card List Item

### Installation

```jsx
import { CardListItem, CardListItemProps } from 'hc-mobile-app-ui';
```

### Example

### Props

| Name          | Type           | Description                                          |
| ------------- | -------------- | ---------------------------------------------------- |
| photoUrl      | string         | URL of photo to be shown on the left.                |
| fallbackImage | Image          | Fallback photo in case photoUrl is not present.      |
| title         | ReactElement   | Title for this list item.                            |
| subTitle      | string         | Subtitle for this list item.                         |
| description   | string         | Description for this list item.                      |
| tags          | Array\<string> | List of tags for this item.                          |
| onPress       | function       | Function to be called when the item is pressed.      |
| marker        | ReactElement   | A React element to be rendered below the card photo. |


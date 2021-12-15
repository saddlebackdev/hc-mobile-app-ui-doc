# Card List

### Installation

```jsx
import { CardList, CardListProps } from 'hc-mobile-app-ui';
```

### Example

### Props

| Name  | Type                          | Description             |
| ----- | ----------------------------- | ----------------------- |
| items | Array\<ItemProps> (See Below) | List items to be shown. |

#### Item Props

| Name        | Type             | Description                                     |
| ----------- | ---------------- | ----------------------------------------------- |
| id          | string \| number | A unique ID for this list item.                 |
| photoUrl    | string           | URL of photo to be shown on the left.           |
| title       | ReactElement     | Title for this list item.                       |
| subTitle    | string           | Subtitle for this list item.                    |
| description | string           | Description for this list item.                 |
| tags        | Array\<string>   | List of tags for this item.                     |
| onPress     | function         | Function to be called when the item is pressed. |


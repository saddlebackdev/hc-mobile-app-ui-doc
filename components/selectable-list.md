# Selectable List

### Installation

```jsx
import { SelectableList, SelectableListProps } from 'hc-mobile-app-ui';
```

### Example

### Props

| Name     | Type                          | Description                        |
| -------- | ----------------------------- | ---------------------------------- |
| items    | Array\<ItemProps> (See Below) | List items to be shown.            |
| selected | string \| number              | ID of the currently selected item. |

#### Item Props

| Name    | Type             | Description                                     |
| ------- | ---------------- | ----------------------------------------------- |
| id      | string \| number | A unique ID for this list item.                 |
| label   | string           | Label for this list item.                       |
| onPress | function         | Function to be called when the item is pressed. |


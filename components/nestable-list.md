# Nestable List

### Installation

```jsx
import { NestableList, NestableListProps } from 'hc-mobile-app-ui';
```

### Example



### Props

#### List Props

| Name          | Type                             | Description                         |
| ------------- | -------------------------------- | ----------------------------------- |
| items         | Array<**ItemProps**> (See Below) | List items to be shown.             |
| parentPadding | number                           | Horizontal padding for parent item. |
| childPadding  | number                           | Horizontal padding for child item.  |

#### Item Props

| Name     | Type                                  | Description                                      |
| -------- | ------------------------------------- | ------------------------------------------------ |
| id       | string \| number                      | A unique ID for this item.                       |
| children | Array<**ChildItemProps**> (See Below) | List of children.                                |
| disabled | boolean                               | If true, disables the item. Defaults to false.   |
| onPress  | function                              | Function to be called when this item is pressed. |
| label    | string                                | Label for the item.                              |

#### Child Item Props

| Name    | Type             | Description                                      |
| ------- | ---------------- | ------------------------------------------------ |
| id      | string \| number | A unique ID for this item.                       |
| onPress | function         | Function to be called when this item is pressed. |
| label   | string           | Label for the item.                              |

#### Parent Item Props

| Name    | Type     | Description                                      |
| ------- | -------- | ------------------------------------------------ |
| onPress | function | Function to be called when this item is pressed. |
| label   | string   | Label for the item.                              |

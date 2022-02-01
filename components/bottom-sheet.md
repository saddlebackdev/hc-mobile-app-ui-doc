# Bottom Sheet

### Installation

```jsx
import { BottomSheet, BottomSheetProps } from 'hc-mobile-app-ui';
```

### Example

### Props

| Name      | Type                    | Description                                                          |
| --------- | ----------------------- | -------------------------------------------------------------------- |
| isOpen    | boolean                 | Specifies if the bottom sheet is open or not.                        |
| onDismiss | function                | Function to be called when dismissing the bottom sheet.              |
| header    | HeaderProps (See Below) | Header component of the bottom sheet.                                |
| footer    | function                | Function that renders a component as the footer of the bottom sheet. |

### Header Props

| Name        | Type   | Description                      |
| ----------- | ------ | -------------------------------- |
| title       | String | Title for the bottom sheet.      |
| description | String | Description for the bottom sheet |

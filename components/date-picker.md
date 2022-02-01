# Date Picker

MAU uses the RNC DatePicker. See: [@react-native-community/datetimepicker](https://github.com/react-native-datetimepicker/datetimepicker)

### Installation

```jsx
import { DatePicker, DatePickerProps } from 'hc-mobile-app-ui';
```

### Example

### Props

In addition to the props listed at: [https://github.com/react-native-datetimepicker/datetimepicker#props](https://github.com/react-native-datetimepicker/datetimepicker#props)

| Name                | Type     | Description                                   |
| ------------------- | -------- | --------------------------------------------- |
| onDateChange        | function | Function to be called when date is selected.  |
| customDateFormatter | function | Optional function to format the date.         |
| label               | string   | Label for the date picker.                    |
| selectedDate        | Date     | Currently selected value for the date picker. |

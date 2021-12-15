# Pill Toggle

### Installation

```jsx
import { PillToggle, PillToggleProps } from 'hc-mobile-app-ui';
```

### Example

{% embed url="https://snack.expo.dev/@rrizk/mau---pill-toggle" %}

### Props

| Name     | Type                          | Description                                          |
| -------- | ----------------------------- | ---------------------------------------------------- |
| disabled | boolean                       | Determines if the toggle control is disabled or not. |
| selected | number \| string              | Value of the already selected option.                |
| options  | Array\<ItemProps> (See below) | Array of items                                       |

#### Item Props

| Name     | Type             | Description                                |
| -------- | ---------------- | ------------------------------------------ |
| label    | string           | Label of the option                        |
| value    | string \| number | Value for the option                       |
| disabled | boolean          | If true, disables the current option       |
| onPress  | function         | Function to be called when pill is pressed |


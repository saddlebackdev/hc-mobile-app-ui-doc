# Icon Toggle

### Installation

```jsx
import { PillToggle, PillToggleProps } from 'hc-mobile-app-ui';
```

### Example



### Props

| Name     | Type                             | Description                                                            |
| -------- | -------------------------------- | ---------------------------------------------------------------------- |
| disabled | boolean                          | Determines if the toggle control is disabled or not. Defaults to false |
| selected | number \| string                 | Value of the already selected option                                   |
| options  | Array<**ItemProps**> (See below) | Array of items                                                         |

#### Item Props

| Name     | Type             | Description                                            |
| -------- | ---------------- | ------------------------------------------------------ |
| label    | string           | Label of the option                                    |
| value    | string \| number | Value for the option                                   |
| content  | function         | A function that renders the content inside the button. |
| disabled | boolean          | If true, disables the current option                   |
| onPress  | function         | Function to be called when pill is pressed             |


# Radio

### Installation

```jsx
import { Radio, RadioProps } from 'hc-mobile-app-ui';
```

### Example

#### Horizontal

{% embed url="https://snack.expo.dev/@rrizk/mau---radio---horizontal" %}

#### Vertical

{% embed url="https://snack.expo.dev/@rrizk/mau---radio---vertical" %}

#### Disabled

{% embed url="https://snack.expo.dev/@rrizk/mau---radio---disabled" %}

### Props

| Name      | Type                                                         | Description                                         |
| --------- | ------------------------------------------------------------ | --------------------------------------------------- |
| disabled  | boolean                                                      | If true, disables all options of the radio control. |
| onChange  | function                                                     | Function to be called when a new selection is made. |
| direction | vertical \| horizontal                                       | Determines the direction of the radio options.      |
| selected  | string \| number                                             | Value of the already selected option.               |
| options   | <p>Array&#x3C;{</p><p>label: string,</p><p>value: string</p> | <p>number,</p><p>disabled: boolean</p><p>}></p>     |

#### Item Props

| Name     | Type             | Description                          |
| -------- | ---------------- | ------------------------------------ |
| label    | string           | Label of the option                  |
| value    | string \| number | Value for the option                 |
| disabled | boolean          | If true, disables the current option |

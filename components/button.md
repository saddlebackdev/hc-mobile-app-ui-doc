# Button

### Installation

```jsx
import { Button, ButtonProps } from 'hc-mobile-app-ui';
```

### Example

#### Filled

{% embed url="https://snack.expo.dev/@rrizk/mau---filled-buttons" %}

#### Outline

{% embed url="https://snack.expo.dev/@rrizk/mau---outline-buttons" %}

#### States

{% embed url="https://snack.expo.dev/@rrizk/mau---button-states" %}

### Props

| Name       | Type                                                                   | Description                                             |
| ---------- | ---------------------------------------------------------------------- | ------------------------------------------------------- |
| disabled   | boolean                                                                | If true, disables the button.                           |
| appearance | filled \| outline                                                      | Determines the appearance of the button.                |
| color      | primary \| secondary \| info \| success \| warning \| danger \| string | Determines the color of the button.                     |
| small      | boolean                                                                | If true, renders a small button.                        |
| hasShadow  | boolean                                                                | If true, adds bottom shadow to the button.              |
| children   | string                                                                 | Label for the button.                                   |
| font       | primary \| secondary \| string                                         | Font family to use for the label.                       |
| leftIcon   | ReactElement                                                           | A React Element to be rendered before the button label. |
| rightIcon  | ReactElement                                                           | A React Element to be rendered after the button label.  |

# Pill Toggle

### Example

{% embed url="https://snack.expo.dev/@rrizk/mau---pill-toggle" %}

### Props

| Name     | Type                                                                                                                                       | Description                                                                                                                                                                                                                                                                                                |
| -------- | ------------------------------------------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| disabled | boolean                                                                                                                                    | Determines if the toggle control is disabled or not.                                                                                                                                                                                                                                                       |
| selected | number \| string                                                                                                                           | Value of the already selected option.                                                                                                                                                                                                                                                                      |
| options  | <p>Array&#x3C;{ </p><p>  label: string, </p><p>  value: string | number,</p><p>  disabled: boolean,</p><p>  onPress: function</p><p>}></p> | <p>Array of options where each option is an object containing - </p><p><code>label</code>: Label of the option</p><p><code>value</code>: Value for the option</p><p><code>disabled</code>: If true, disables the current option</p><p><code>onPress</code>: Function to be called when pill is pressed</p> |

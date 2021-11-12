# Radio

### Horizontal

{% embed url="https://snack.expo.dev/@rrizk/mau---radio---horizontal" %}

### Vertical

{% embed url="https://snack.expo.dev/@rrizk/mau---radio---vertical" %}

### Disabled

{% embed url="https://snack.expo.dev/@rrizk/mau---radio---disabled" %}

### Props

| Name      | Type                                                                                                            | Description                                                                                                                                                                                                                            |
| --------- | --------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| disabled  | boolean                                                                                                         | If true, disables all options of the radio control.                                                                                                                                                                                    |
| onChange  | function                                                                                                        | Function to be called when a new selection is made.                                                                                                                                                                                    |
| direction | vertical \| horizontal                                                                                          | Determines the direction of the radio options.                                                                                                                                                                                         |
| selected  | string \| number                                                                                                | Value of the already selected option.                                                                                                                                                                                                  |
| options   | <p>Array&#x3C;{ </p><p>  label: string, </p><p>  value: string | number,</p><p>  disabled: boolean</p><p>}></p> | <p>Array of options where each option is an object containing - </p><p><code>label</code>: Label of the option.</p><p><code>value</code>: Value for the option.</p><p><code>disabled</code>: If true, disables the current option.</p> |

# Text Input

### Installation

```jsx
import { TextInput, TextInputProps } from 'hc-mobile-app-ui';
```

#### Text Input vs Text Area

A Text Input is a one-line field, probably as an input for something like first name or last name, a phone number or an email address, etc. A Text Area is a multiline field that allows users to write in multiple lines. These can be used for notes, addresses or other long and complex type of data.

{% hint style="info" %}
To convert the text input into a text area, you can add the `multiline` prop. See [this document](https://reactnative.dev/docs/textinput#multiline) for reference.
{% endhint %}

### Example



### Props

In addition to the props listed at: [https://reactnative.dev/docs/textinput](https://reactnative.dev/docs/textinput)

| Name         | Type     | Description                                        |
| ------------ | -------- | -------------------------------------------------- |
| label        | string   | Label for the text input                           |
| isUnderlined | function | Enables the underlined variant for the text input. |
| placeholder  | string   | Placeholder for the text input                     |
| disabled     | boolean  | If true, disables the text input control           |
| required     | boolean  | If true, appends an asterisk to the label          |
| onChange     | function | Function to call on key input event                |


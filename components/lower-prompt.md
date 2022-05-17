# Lower Prompt

### Installation

```jsx
import { LowerPrompt, LowerPromptProps } from 'hc-mobile-app-ui';
```

### Example



### Props

| Name                | Type              | Description                                                                  |
| ------------------- | ----------------- | ---------------------------------------------------------------------------- |
| isOpen              | string            | Determines if the prompt is open or not.                                     |
| intent              | danger \| success | Sets the color of the confirm button.                                        |
| leftButtonLabel     | string            | Label of the left button.                                                    |
| leftButtonCallback  | function          | Function to be call when the left button is pressed.                         |
| leftButtonColor     | string            | Color of the left button.                                                    |
| rightButtonLabel    | string            | Label of the right button.                                                   |
| rightButtonCallback | function          | Function to be call when the right button is pressed.                        |
| rightButtonColor    | string            | Color of the right button. This gets overridden if an "intent" is specified. |


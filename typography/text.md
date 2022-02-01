# Text

{% hint style="warning" %}
It is possible to pass custom styles directly to the Text component through the `style` prop. However, to maintain consistent typography throughout the app, **it is not recommended to do so**. When needed, you can create a Higher Order Component which wraps the Text component and use that instead. See [Custom Fonts](custom-fonts.md) for more details.
{% endhint %}

### Example

{% embed url="https://snack.expo.dev/@rrizk/mau---typography---text" %}

### Props

| Name       | Type                    | Description                             |
| ---------- | ----------------------- | --------------------------------------- |
| isMuted    | boolean                 | If true, renders the text as muted      |
| isSubtitle | boolean                 | If true, renders the text as a subtitle |
| isCaption  | boolean                 | If true, renders the text as a caption  |
| alignment  | left \| center \| right | Determines the alignment of the text    |
| inversed   | boolean                 | If true, inverses the color of text     |

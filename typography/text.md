# Text

{% hint style="warning" %}
It is possible to pass custom styles directly to the Text component through the `style` prop. However, to maintain consistent typography throughout the app, **it is not recommended to do so**. When needed, you can create a Higher Order Component which wraps the Text component and use that instead. See [Custom Fonts](custom-fonts.md) for more details.
{% endhint %}

### Example

{% embed url="https://snack.expo.dev/@rrizk/mau---typography---text" %}

### Props

| Name      | Type                                                          | Description                                                         |
| --------- | ------------------------------------------------------------- | ------------------------------------------------------------------- |
| inversed  | boolean                                                       | If true, inverses the color of text.                                |
| muted     | boolean                                                       | If true, renders the text as muted.                                 |
| small     | boolean                                                       | If true, renders the text with small font size.                     |
| variant   | body1 \| body2 \| caption \| button \| subtitle1 \| subtitle2 | Determines the variant of the text.                                 |
| font      | primary \| secondary \| string                                | Font family to use. See [Custom Fonts](custom-fonts.md).            |
| italic    | boolean                                                       | Renders the text in italics.                                        |
| weight    | light \| regular \| semiBold \| bold                          |  Weight fo the font.                                                |
| alignment | left \| center \| right                                       | Determines the alignment of the text. Can be left, center or right. |

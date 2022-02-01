# Heading

{% hint style="warning" %}
It is possible to pass custom styles directly to the Heading component through the `style` prop. However, to maintain consistent typography throughout the app, **it is not recommended to do so**. When needed, you can create a Higher Order Component which wraps the Heading component and use that instead. See [Custom Fonts](custom-fonts.md) for more details.
{% endhint %}

### Example

{% embed url="https://snack.expo.dev/@rrizk/mau---typography---heading" %}

### Props

| Name      | Type                             | Description                                              |
| --------- | -------------------------------- | -------------------------------------------------------- |
| inversed  | boolean                          | If true, inverses the color of text.                     |
| font      | primary \| secondary \| string   | Font family to use. See [Custom Fonts](custom-fonts.md). |
| alignment | left \| center \| right          | Determines the alignment of the text.                    |
| variant   | h1 \| h2 \| h3 \| h4 \| h5 \| h6 | Determines the variant of the heading.                   |

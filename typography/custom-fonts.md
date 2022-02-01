# Custom Fonts

Since there is a constraint that every app will have its own set of typographic language such as different and multiple variations of fonts and sizes, MAU sticks to the default options. It is possible to create a [Higher Order Component](https://reactjs.org/docs/higher-order-components.html) that wraps the typographic components and overwrite the font properties through their `style` prop.

### Example

```jsx
import { Heading, Text } from 'hc-mobile-app-ui';

const CustomHeading = ({ children }) => {
    return (
        <Heading style={{ fontFamily: 'YOUR_FONT' }}>
            {children}
        </Heading>
    )
}

const CustomText = ({ children }) => {
    return (
        <Text style={{ fontFamily: 'YOUR_FONT' }}>
            {children}
        </Text>
    )
}
```

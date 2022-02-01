# Custom Fonts

Since every app will have its own set of typographic language such as different and multiple variations of fonts and sizes, MAU allows fonts families to be specified in the theme.

By default, MAU has two sets of fonts: primary and secondary. Each set has four variations, light, regular, semi-bold and bold. See [Theming](../foundations/theming.md). Most of the components will always use the primary and secondary font sets for typography.

However, in case you need more fonts, you can easily extend the theme like:

```jsx
import { defaultTheme } from 'hc-mobile-app-ui';

const customTheme = {
    ...defaultTheme,
    typography: {
        ...defaultTheme.typography,
        faces: {
            ......defaultTheme.typography.faces,
            
            // Custom Family One
            customFamilyOneLight: 'Nunito-Light',
            customFamilyOneRegular: 'Nunito-Regular',
            customFamilyOneSemiBold: 'Nunito-SemiBold',
            customFamilyOneBold: 'Nunito-Bold',
            
            // Custom Family Two
            customFamilyTwoLight: 'Manrope-Light',
            customFamilyTwoRegular: 'Manrope-Regular',
            customFamilyTwoSemiBold: 'Manrope-SemiBold',
            customFamilyTwoBold: 'Manrope-Bold',
        }
    }
}
```

These families can later be used in the [Typographic components](broken-reference) like:

```jsx
import { Text, Heading } from 'hc-mobile-app-ui';

const App = () => {
    return (
        ...
        <Text font="customFamilyOne" weight="light">
            ...
        </Text>
        
        <Heading font="customFamilyTwo">
            ...
        </Heading>
        ...
    )
}
```


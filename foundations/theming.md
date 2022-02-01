# Theming

### Theme Provider

MAU exports a `ThemeProvider` component that allows you to customise the colors and the typographic language.

{% hint style="info" %}
**Important!**

The `ThemeProvider` component should be the parent of every other component that is imported from `'hc-mobile-app-ui'` package as these components utilise the theme prop from it. A good idea would be to add the `ThemeProvider` at the root of app usually `index.js` or `app.js`.
{% endhint %}

#### Usage

```jsx
import { Button, ThemeProvider } from 'hc-mobile-app-ui'

const App = () => {
    return (
        <ThemeProvider>
            ...
            <Button>Continue</Button>
            ...
        </ThemeProvider>
    )
}
```

#### Props

| Name  | Type        | Description       |
| ----- | ----------- | ----------------- |
| theme | ThemeObject | Theme for the app |

### Default Theme

MAU also exports a `defaultTheme` object which can be used to create a custom theme. See the next section to know more about creating a custom theme. The "theme" object should be passed to the `theme` prop of the `ThemeProvider` component.

#### Schema

```json
{
  colors: {
    primaryLight: string;
    primaryDark: string;
    secondaryLight: string;
    secondaryDark: string;

    infoLight: string;
    infoDark: string;
    successLight: string;
    successDark: string;
    warningLight: string;
    warningDark: string;
    dangerLight: string;
    dangerDark: string;

    white: string;
    black: string;
    grayOne: string;
    grayTwo: string;
    grayThree: string;
    grayFour: string;
    grayFive: string;
    graySix: string;
  };

  typography: {
    faces: {
      primaryLight: string;
      primaryRegular: string;
      primarySemiBold: string;
      primaryBold: string;

      secondaryRegular: string;
      secondaryLight: string;
      secondarySemiBold: string;
      secondaryBold: string;
    };
    sizes: {
      small: number;
      regular: number;
      text: {
        body1: number;
        body2: number;
        caption: number;
        button: number;
        subtitle1: number;
        subtitle2: number;
      };
      headings: {
        h1: number;
        h2: number;
        h3: number;
        h4: number;
        h5: number;
        h6: number;
      };
    };
  };
}
```

#### Usage

```jsx
import { ThemeProvider, defaultTheme } from 'hc-mobile-app-ui'

const App = () => {
    return (
        <ThemeProvider theme={defaultTheme}>
            ...
        </ThemeProvider>
    )
}
```

### Custom Theme

You can create custom theme using the defaultTheme object exported from the hc-mobile-app-ui package. Here's an example of a custom theme that changes the primary color.

#### Example

{% embed url="https://snack.expo.dev/@rrizk/mau---custom-theme" %}

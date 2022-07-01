# Select Picker

MAU uses the React Native Picker Select. See: [react-native-picker-select](https://github.com/lawnstarter/react-native-picker-select)

### Installation

Since React Native Picker Select is dependent on [React Native Picker](https://github.com/react-native-picker/picker), you will need to install the library as a dependency in your project:

```shell
yarn add @react-native-picker/picker
```

Once the dependency is installed, import the `SelectPicker` component from the UI Library:

```jsx
import { SelectPicker, SelectPickerProps } from 'hc-mobile-app-ui';
```

### Example



### Props

In addition to the props listed at: [https://github.com/lawnstarter/react-native-picker-select#props](https://github.com/lawnstarter/react-native-picker-select#props)

| Name                  | Type    | Description                                          |
| --------------------- | ------- | ---------------------------------------------------- |
| isUnderlined          | boolean | Enables the underlined variant for the select picker |
| shouldShowPlaceholder | boolean | Determines if the placeholder should be shown or not |
| label                 | string  | Label for the Select Picker                          |

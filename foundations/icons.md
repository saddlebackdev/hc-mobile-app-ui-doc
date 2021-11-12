# Icons

MAU provides icons in SVG format that are published as a separate package. You can install the icons package from NPM:

```
npm install hc-app-icons
```

### Usage

{% tabs %}
{% tab title="React" %}
Since React runs on the web and all of the browsers have in-built support for rendering SVG files, there are no additional steps required for this. By default, the SVG files should be imported and be supplied as the source to an `img` tag



```
import { UserSvg } from 'hc-app-icons';

<img src={UserSvg} ... />
```



There are libraries available that make working with SVGs in React a lot easier. For example, [react-svg ](https://github.com/tanem/react-svg)and [SVGR](https://github.com/gregberge/svgr).
{% endtab %}

{% tab title="React Native" %}
Since React Native doesn't have in-built support for SVG files, you'll first need to install the `react-native-svg` package. More details on setting up the library with React Native can be found [here](https://github.com/react-native-svg/react-native-svg).



```
npm install react-native-svg
```
{% endtab %}
{% endtabs %}

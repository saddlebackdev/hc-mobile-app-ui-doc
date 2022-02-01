# Tiles

### Installation

```jsx
import { Tiles, TilesProps } from 'hc-mobile-app-ui';
```

### Example



### Props

| Name    | Type                         | Description                                   |
| ------- | ---------------------------- | --------------------------------------------- |
| items   | Array\<TileItem> (See Below) | Array of tiles to be rendered.                |
| columns | number                       | Number of columns to be rendered in each row. |

#### Tile Item Props

| Name        | Type             | Description                                                                          |
| ----------- | ---------------- | ------------------------------------------------------------------------------------ |
| id          | string \| number | Unique ID for the tile.                                                              |
| size        | number           | Size in pixels to be used as the width and height of the tile.                       |
| tileContent | ReactElement     | A React element to be rendered inside tile.                                          |
| tileColor   | string           | Color of the tile. Should be a color name from the theme. Defaults to secondaryDark. |
| title       | string           | Title for the tile.                                                                  |
| onPress     | function         | Function to be called when the tile is pressed.                                      |
| disabled    | boolean          | Flag to determine whether the tile is active or disabled.                            |


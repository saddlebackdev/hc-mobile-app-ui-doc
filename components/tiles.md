# Tiles

### Installation

```jsx
import { Tiles, TilesProps } from 'hc-mobile-app-ui';
```

### Example



### Props

| Name     | Type                             | Description                                               |
| -------- | -------------------------------- | --------------------------------------------------------- |
| items    | Array<**ItemProps**> (See Below) | Array of tiles to be rendered.                            |
| centered | boolean                          | Center the tiles' items both horizontally and vertically. |
| columns  | number                           | Number of columns to be rendered in each row.             |

#### Item Props

| Name     | Type             | Description                                                    |
| -------- | ---------------- | -------------------------------------------------------------- |
| id       | string \| number | Unique ID for the tile.                                        |
| size     | number           | Size in pixels to be used as the width and height of the tile. |
| content  | ReactElement     | A React element to be rendered inside tile.                    |
| color    | string           | Color of the tile. Should be a color name from the theme.      |
| title    | string           | Title for the tile.                                            |
| onPress  | function         | Function to be called when the tile is pressed.                |
| disabled | boolean          | Flag to determine whether the tile is active or disabled.      |
| hidden   | boolean          | Flag to determine whether the tile is visible or not.          |

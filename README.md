# tm-tooltip

Vue component that displays a basic tooltip with a definition from a dictionary. Dictionary is inside `src/dict.json`.

## Install with Vue

```sh
npm install tm-tooltip
```

```js
import TmTooltip from "tm-tooltip";
Vue.component("tm-tooltip", TmTooltip);
```

## Install as a web-component

```html
<script src="https://unpkg.com/tm-tooltip/dist/tm-tooltip.min.js"></script>
```

## Usage

```html
<tm-tooltip value="blockchain">show the definition</tm-tooltip>
```

# virtual-dnd-list-core

**Sortbale**

```js
import { Sortable } from './index';

const sortable = new Sortable(elem, {
  list: [],
  uniqueKeys: [],
  delay: 0,
  group: '',
  handle: '',
  lockAxis: '',
  sortable: true,
  disabled: false,
  draggable: '',
  animation: 150,
  autoScroll: true,
  ghostClass: '',
  ghostStyle: {},
  chosenClass: '',
  scrollSpeed: { x: 10, y: 10 },
  fallbackOnBody: false,
  scrollThreshold: 55,
  delayOnTouchOnly: false,
  placeholderClass: '',
  onDrag: (event) => {},
  onDrop: (event) => {},
  onChoose: (event) => {},
  onUnchoose: (event) => {},
});

sortable.rangeChanged; // virtual list range changed
```

**Virtual**

```js
import { Virtual } from './index';

const virtual = new Virtual({
  size: 0,
  keeps: 0,
  buffer: 0,
  wrapper: HTMLElement,
  scroller: HTMLElement,
  direction: 'vertical', // or `horizontal`
  uniqueKeys: [],
  debounceTime: 0,
  throttleTime: 0,
  onScroll: (event) => {},
  onUpdate: (range) => {},
});
```

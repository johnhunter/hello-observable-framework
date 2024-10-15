---
theme: dashboard
toc: false
---

# Weather report

```js
const forecast = FileAttachment('./data/forecast.json').json();
```

```js
import { temperaturePlot } from './temperaturePlot.js';

// display(temperaturePlot(forecast));
```

<div class="grid grid-cols-1">
  <div class="card">${resize((width) => temperaturePlot(forecast, {width}))}</div>
</div>

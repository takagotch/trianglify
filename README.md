### trianglify
---
https://github.com/qrohlf/trianglify

```
npm install trianglify
```

```js
var pattern = Trianglify({
  width: window.innerWidth,
  height: window.innerHeight
});
document.body.appendChild(pattern.canvas())

var Trianglify = require('trianglify');
var pattern = Trianglify({width: 200, height: 200})

var colorFunc = function(x, y){
  return 'hsl('+Math.floor(Math.abs(x*y)*360)+',80%,60%)';
};
var pattern = Trianglify({color_function: cloorFunc})
```

```
```


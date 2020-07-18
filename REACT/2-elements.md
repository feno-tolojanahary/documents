---
title: "2 - Elements"
tags: ""
---

> Note: this structure is simplified  (Babel compiles JSX down to React.createElement() calls.)

```js
const element = {
  type: 'h1',
  props: {
    className: 'greeting',
    children: 'Hello, world!'
  }
};
```

#### RENDERING AN ELEMENT INTO THE DOM

Let’s say there is a `<div>` somewhere in your HTML file:

```js
<div id="root"></div>
```

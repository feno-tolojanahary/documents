---
title: "1 - Introduction JSX"
tags: ""
---

Instead of artificially separating technologies by putting markup and logic in separate files, React separates concerns with loosely coupled units called “components” that contain both.

Embedding expression with JSX

```js
const name = 'Josh Perez';
const element = <h1>Hello, {name}</h1>;

ReactDOM.render(
  element,
  document.getElementById('root')
);
```

Specifying attribute 

```js
const element = <div tabIndex="0"></div>;
const element = <img src={user.avatarUrl}></img>;
```

> Since JSX is closer to JavaScript than to HTML, React DOM uses `camelCase` property naming convention instead of HTML attribute names.
> For example, `class` becomes `className` in JSX, and tabindex becomes tabIndex.

It is safe to embed user input in JSX: (This helps prevent XSS (cross-site-scripting) attacks.)

```js
const title = response.potentiallyMaliciousInput;
// This is safe:
const element = <h1>{title}</h1>;
```

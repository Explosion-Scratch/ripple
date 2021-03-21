<h1 align="center">Ripple</h1>
Material design ripple effect.

## How to use
<img src="https://lh3.googleusercontent.com/S3HG6qs3kB6yQI-0VEEuXxuog7vcWJKVrmxpr4WfgQr3GZY98fDB2X7ZSM7180K54UDjHwS-aryZboZBZcF1DsOe1Ra69NHqZplQgA=w1064-v0">

Import from a CDN:
```html
<script src="https://cdn.jsdelivr.net/gh/explosion-scratch/ripple/ripple.js">
```
Then use it like this:
```html
<button data-ripple>Test</button>
```
Then call `ripple()`:
```js
ripple();
```

## Options:
You can also use other attributes to change the way the rippl effect looks:


| Attribute      | What it does                                           | Default        |
|----------------|--------------------------------------------------------|----------------|
| `data-ripple`  | Turns on the ripple effect                             | -              |
| `data-time`    | The time in milliseconds that the ripple effect takes. | 500            |
| `data-color`   | The color of the ripple.                               | `currentColor` |
| `data-opacity` | The opacity of the ripple effect.                      | `.3`           |
| `data-event`   | The event to ripple on.                                | `mousedown`    |

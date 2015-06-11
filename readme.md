# scrollSnap

Scroll, stop, snap.

scrollSnap provides a hassle-free alternative to scroll-hijacking, allowing a section-based navigation without harming the user-experience. Is's written in Vanilla JS and has zero dependencies.

Tested with the latest versions of [Mozilla Firefox](https://www.mozilla.org/en-US/firefox/new/), [Apple Safari](https://www.apple.com/safari/), [Google Chrome](https://www.google.com/chrome/browser/), [Microsoft Internet Explorer](http://windows.microsoft.com/en-us/internet-explorer/download-ie) (10+) and [Opera](http://www.opera.com/).

## Demos

| Name | Description | Link |
|:-----------|:------------|:------------|
| Basic | Snaps to the nearest section | [Demo]() |

## Features

- Works in all modern browsers
- Zero dependencies
- Performance-optimized
- Fluid animations

## Performance

scrollSnap has been developed with performance in mind. It uses modern technologies to get the most of your browser:

- Works without additional libraries to keep your site slim
- Written in ES2015 and transformed to ES5 using [Babel](https://babeljs.io)
- `requestAnimationFrame` for fluid animations
- Size-calculations will be performed at start and after a defined scroll-delay. All data gets cached to avoid unnecessary recalculations.

## Installation

We recommend to install scrollSnap using [Bower](http://bower.io/) or [npm](https://npmjs.com).

	bower install scrollSnap
	npm install scrollsnap
	
## Requirements

scrollSnap dependents on the following browser APIs:

- [requestAnimationFrame](http://caniuse.com/#feat=requestanimationframe)

Some of these APIs are capable of being polyfilled in older browser. Check the linked resources above to determine if you must polyfill to achieve your desired level of browser support.
	
## Include

Simply include the JS-file at the end of your `body`.

```html
<script src="dist/scrollSnap.min.js"></script>
```

## Options

List of options you can pass to the `scrollSnap.init`-function:

```js
scrollSnap.init({
})
```
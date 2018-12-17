## v0.6.6 - Dec 17 2018

* Fork from [existing pull request](https://github.com/captDaylight/react-tiny-spin/pull/4) for React 16 compatibility. 
* Configure Babel to match `react-tiny-spin@0.6.5` on NPM.
* Use `componentDidUpdate` instead of deprecated `componentWillReceiveProps`.

## v0.6.3 - v0.6.5
???

## v0.6.2 - Apr 23 2016

* Configure Babel transforms so the bundled output works in IE8. Thanks [@SimenB](https://github.com/SimenB)!

## v0.6.1 - Apr 8 2016

* Allow React 15.x as a peer dependency

## v0.6.0 - Mar 1 2016

* **[Breaking]** react-spin now uses ES6 modules through Babel. If you use ES6 modules, you shouldn't have to change anything. If you use CommonJS, you'll now need to import react-spin like so:

```js
// before
var Spinner = require('react-spin');

//after
var Spinner = require('react-spin').default;
```

* Spinners created with `stopped` set to true will now be stopped by default (thanks [lobobabysaurus](https://github.com/lobobabysaurus))

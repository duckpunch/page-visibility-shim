# page-visibility-shim

[![npm](https://img.shields.io/npm/v/page-visibility-shim.svg)](https://www.npmjs.com/package/page-visibility-shim)

Packaged version of the [Page Visibility API shim provided on MDN](https://developer.mozilla.org/en-US/docs/Web/API/Page_Visibility_API)

## Install

`npm install page-visibility-shim`

## Use

```javascript
var pageVisibilityShim = require('page-visibility-shim');

pageVisibilityShim.hidden // Appropriate "document.hidden" key for the browser
pageVisibilityShim.visibilityChange // Appropriate event name for visibility change for the browser
```

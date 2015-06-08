# simple-clone

Deeply clones an object or array for use in the browser.

## Usage
Just pass in the object you wish to clone and it will return a fresh object.

```javascript
var oldObj = { foo: 'bar' };
var newObj = clone(oldObj);

oldObj.foo = false;
console.log(newObj.foo); // 'bar'
```

## Browser support

This package uses Array.isArray to determine if an object is an array.  The following browsers are supported with no polyfills:

* Google Chrome
* Internet Explorer 9+
* Firefox 4.0+
* Safari 5.0+
* Opera 10.50+

# angular-safe-apply

## Installation

  Install with [component(1)](http://component.io):

    $ component install enome-components/angular-safe-apply

## API

```js
var mod = window.angular.module('my-app', [ require('angular-safe-apply') ]);
mod.controller('Ctr', function ($scope, safeApply) {
  safeApply(scope, function () {
    /* ... */
  });
});
```

## License

  MIT

```
qFactory(
  function (callback) {
    $rootScope.$evalAsync(callback);
  },
  $exceptionHandler
);
```

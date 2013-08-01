```
Payment.createToken(info, function (status, response) {
  $scope.$apply(function () {
    $scope.token = response.token;
  });
});
```

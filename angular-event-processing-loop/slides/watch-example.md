```
// Watching $scope.name
$scope.$watch('name', function (newValue, oldValue) {
  $scope.counter = $scope.counter + 1;
});
```

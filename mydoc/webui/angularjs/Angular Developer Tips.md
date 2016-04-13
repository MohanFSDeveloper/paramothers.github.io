# Developer tips

1. treat **$scope** object as read only in view, write only in controller as much as possible.
2. Better read directly from **$scope**, object in View
3. pass **$scope** object as parameter in controller function rather than read directly from $scope
4. keep **$controller** size as much as minimum
5. Don't pass **$scope** object beyond controller, like to services
6. to avoid minify error, use inline array in all service, controller methods
7. in **ng-model**, use dot notation like user.name, user.password rather than simply name and password, it decouples view and controller by avoiding use of $scope
8. don't use **$scope** to keep all the variables unless, it shared with view. you can use local variable instead of.
9. use **$rootScope**, for share global variable with in the module.
10. better access **$rootScope** object by module's _run_ method
11. use <a> tag rather than use of combination of <ng-click> and $location

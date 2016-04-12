## Developer tips

1. treat **$scope** object as read only in view, write only in controller as much as possible.
1. Better read directly from **$scope**, object in View
1. pass **$scope** object as parameter in controller function rather than read direcly from $scope
1. Don't pass **$scope** object beyond controller, like to services
1. to avoid minify error, use inline array in all service, controller methods
1. in **ng-model**, use dot notation like user.name, user.password rather than simply name and password, it decouples view and controller by avoiding use of $scope
1. don't use **$scope** to keep all the variables unless, it shared with view. you can use local variable instead of.
1. use **$rootScope**, for share global variable with in the module. 
1. better access **$rootScope** object by module's *run* method 
## Angular Service

 Services are defined/registered with $provide object, 5 different ways
  1. values - not available during configuration phase but application can change the value
  5. constant -available during configuration phase, but application cannot modify the value 
  2. service - normal services like java services, instance created by Constructor Function so facility to use THIS word
  3. factory - RMP (Revealing Module Pattern) need to be retruned
  4. provider - complete control on service behaviour, but complex, for example a service used by many applications, but we want to configure its behaviour different for each appliications    .

Once service defined in anyone of the way, it available for accross application also it can be injected anywhere

** service life cycle **
    

**built-in servivces**

$provide - all the services are registered in this object, in a project.
$injector - it inject the requested service instance from factory to application component.

**Server communication**

$http - communicate to server by AJAX.
$resource - communicate server via RESTful method.
$q - used for deferred/promise objects
$httpBackend
$httpProvider - to define intercepteros
$route
$routeProvider	  
$routeParam

$compile
$digest - its a loop
$apply - run digest loop manually.
$watch - has list of expressions for a given $scope 

## Angular Service

we use/define services for handling business logic. Services are defined/registered with $provide object, **5 different ways**
 
  1. **values**, not available during configuration phase but application can change the value
  1. **constant**, available during configuration phase, but application cannot modify the value 
  1. **service**, normal services like java services, instance created by Constructor Function so facility to use THIS word, equivalent to "new" operator.
  1. **factory**, RMP (Revealing Module Pattern) need to be returned
  1. **provider**, configurable services, but complex, for example a service used by many applications, but we want to configure its behaviour different for each application   .

Once service defined in anyone of the way, it available for across application also it can be injected anywhere. Services are **singleton**
object and it can be used by controller, directives, filters and even other services.
 

**built-in services**

1. **$provide**, all the services are registered in this object, in a project.
1. **$injector**, it inject the requested service instance from factory to application component.
1. **$http**, communicate to server by AJAX.
1. **$route**, combine url with view and controller, in SPA
1. **$httpProvider** to define interceptors
1. **$routeProvider**, provide *when* function to define routing
1. **$routeParams**, provide access the parameter inside of controller
1. **$location**, service used to navigate within SPA application, it is like <jsp:forward> to another JSP
1. **$window**, service used to navigate outside of the application
1. **$log**, used to custom log
1. **$logProvider**, used to configure the log
1. **timeout**, service used after certain time elapsed
1. **$interval**, repeatably execute a function.
1. **$q** used for deferred/promise objects
1. **$apply** notify the *digest cycle* manually or *keypressdownevent*.(helps in two-way binding)
1. **$watch** has list of expressions for a given $scope.(helps in two-way binding) 
1. **$compile**, used for compile directives
1. **$httpBackend**, used to mock *$http* service during testing the application

$resource - communicate server via RESTful method.
$digest - its a loop

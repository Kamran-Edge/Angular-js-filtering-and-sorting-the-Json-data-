# Angular js filtering and sorting the Json data
This component is used to filter and sort the Json Data. In this component the json file is called through the angular js built-in $http service. Then this data can be filtered by with repect to first name, last Name, Age and Height by the user.

# What is Angular Js $http built-in Service ?
The $http service is one of the most common used services in AngularJS applications. The service makes a request to the server, and lets your application handle the response.
The $http service code used in the repository is mentioned below;-

      app.controller('listController',function ($scope, $http){
           $http.get('js/data.json').success(function(data){
            $scope.friends = data;
             });
        });
 # ng-model directive is used to bind the data in Input
 The ng-model directive binds the value of HTML controls (input, select, textarea) to application data.




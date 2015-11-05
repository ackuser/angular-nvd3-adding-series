If you are doing that from WS or similar resources you would need to add

See https://github.com/krispo/angular-nvd3/issues/37

 In the directive

    <nvd3 options="options" data="data" api="api"></nvd3>

 In the Controller

    $scope.api.refresh(); 

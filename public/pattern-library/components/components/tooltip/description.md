<p>how to put tooltip inside ...</p>

<pre>
<custom-popover template="recently closed MoneyPark rates tooltip' %}tooltip Recently closed MoneyPark rates"></custom-popover>
</pre>

<pre>
angular.module('ui.bootstrap.demo').controller('PaginationDemoCtrl', function ($scope, $log) {
  $scope.totalItems = 64;
  $scope.currentPage = 4;

  $scope.setPage = function (pageNo) {
    $scope.currentPage = pageNo;
  };

  $scope.pageChanged = function() {
    $log.log('Page changed to: ' + $scope.currentPage);
  };

  $scope.maxSize = 5;
  $scope.bigTotalItems = 175;
  $scope.bigCurrentPage = 1;
});
</pre>

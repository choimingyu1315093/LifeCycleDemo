CoroutineScope는 범위를 제공하는 인터페이스다. 앱의 생명 주기에 따라 코루틴을 관리할 때 사용한다.(Activity, Fragment)

근데 lifecycleScope가 등장했다.

CoroutineScope대신 lifecycleScope 사용하면 되고, 생명 주기가 종료되면 해당 페이지의 모든 코루틴이 취소된다.

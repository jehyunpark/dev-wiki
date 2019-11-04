# Spring 캐시

- NoOpCacheManager
  - https://docs.spring.io/spring/docs/current/javadoc-api/org/springframework/cache/support/NoOpCacheManager.html
  - 캐싱을 비활성화하는 데 적합한 기본 작업이 없는 CacheManager 구현
  - 일반적으로 실제 백업 저장소없이 캐시 선언을 백업하는 데 사용. 실제로 항목을 저장하지 않고 캐시에 항목을 허용

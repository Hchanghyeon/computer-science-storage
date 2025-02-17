### 2️⃣ Spring

- Servlet
    - 개념
    - Tomcat
        - Thread Per Request vs EventLoop
        - 동기 vs 비동기
    - Filter
    - Servlet Container
    - 동작과정
- Spring 기본
    - Spring vs Spring MVC vs Spring Boot
        - MVC1 vs MVC2
    - Dispatcher servlet
    - IoC
    - DI
    - Bean, Component
        - Bean Scope
        - `@Component` `@Service` `@Controller` `@ResponseBody`
        - 생성주기
        - 프로토타입 빈
        - Component와 Configuration의 차이
    - Container
    - VO vs DTO vs DAO
    - Maven, Gradle
- Spring 심화
    - `@Async`,`@EventListener`
    - AutoConfiguration
    - ObjectMapper
    - ControllerAdvice, ExceptionHandler
    - AOP
        - Spring AOP 어노테이션
        - JDK Dynamic Proxy
        - CGLIB
    - Interceptor
        - Filter와 차이점
    - Spring 전체 동작과정

- JPA
    - JDBC, Spring JDBC
    - Sql Mapper(MyBatis), ORM
    - @Transactional
    - JPA, Hibernate
    - 영속성 컨텍스트
    - 즉시/지연 로딩
    - 프록시
    - 고아객체
    - 단뱡향/양방향 매핑
    - N + 1 문제
        - BatchSize, EntityGraph, Fetch Join
- 테스트
    - DDD, TDD
    - Junit4 vs Junit5
    - 단위, 통합, 인수 테스트
    - stub, mock
    - SpringBoot 계층별 테스트 방법
    - 테스트 커버리지 (JACOCO)
- 기타
    - 2.x.x와 3.x.x 버전 차이
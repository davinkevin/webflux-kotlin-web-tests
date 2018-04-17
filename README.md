Branch based on upcoming [Spring Framework 5.0.6](https://jira.spring.io/browse/SPR/fixforversion/16720/)
with [SPR-15692](https://jira.spring.io/browse/SPR-15692) fix.

This projects shows how to use `@WebTestClient` with Kotlin and a WebFlux server (annotation-based or functional):
 - [Integration test](https://github.com/sdeleuze/webflux-kotlin-web-tests/blob/master/src/test/kotlin/com/example/FooIntegrationTests.kt)
 - [`@WebFluxTest` with `@RestController`](https://github.com/sdeleuze/webflux-kotlin-web-tests/blob/master/src/test/kotlin/com/example/FooControllerTests.kt)
 - [`@WebFluxTest` with functional router](https://github.com/sdeleuze/webflux-kotlin-web-tests/blob/master/src/test/kotlin/com/example/FooRouterTests.kt)

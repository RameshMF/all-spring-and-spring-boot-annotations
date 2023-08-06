# List of Spring Framework and Spring Boot Annotations
Check out all the spring core, spring MVC, spring boot, spring cloud, and spring data jpa annotations with examples, tutorials, and guides. Click on each annotation to learn in-depth with examples. I will continue adding more annotations here.
<h1 style="text-align: left;">1. Spring Core Annotations</h1>
<div> <b><a href="https://www.javaguides.net/2018/11/spring-component-annotation-example.html" target="_blank">@Component Annotation</a></b>
   : The @Component annotation indicates that an annotated class is a “spring bean/component”. The @Component annotation tells the Spring container to automatically create Spring bean.
</div><br />
<div> <b><a href="https://www.javaguides.net/2018/09/spring-autowired-annotation-with-example.html" target="_blank">@Autowired Annotation</a></b>
   : The @Autowired annotation is used to inject the bean automatically. The @Autowired annotation is used in constructor injection, setter injection, and field injection
</div><br />
<div> <b><a href="https://www.javaguides.net/2018/06/spring-qualifier-annotation-example.html" target="_blank">@Qualifier Annotation</a></b>
   : @Qualifier annotation is used in conjunction with Autowired to avoid confusion when we have two or more beans configured for the same type.
</div><br />
<div> <b><a href="https://www.javaguides.net/2018/10/spring-primary-annotation-example.html" target="_blank">@Primary Annotation</a></b>
   : We use @Primary annotation to give higher preference to a bean when there are multiple beans of the same type.
</div><br />
<div> <b><a href="https://www.javaguides.net/2018/09/spring-bean-annotation-with-example.html" target="_blank">@Bean Annotation</a></b>
   : @Bean annotation indicates that a method produces a bean to be managed by the Spring container. The @Bean annotation is usually declared in the Configuration class to create Spring Bean definitions.
</div><br />
<div> <b><a href="https://www.javaguides.net/2018/10/spring-lazy-annotation-example.html" target="_blank">@Lazy Annotation</a></b>
   : By default, Spring creates all singleton beans eagerly at the startup/bootstrapping of the application context. You can load the Spring beans lazily (on-demand) using @Lazy annotation.
</div><br />
<div> <b><a href="https://www.javaguides.net/2018/10/spring-scope-annotation-with-prototype.html" target="_blank">@Scope Annotation</a></b>
   : The @Scope annotation is used to define the scope of the bean.&nbsp;We use <i>@Scope</i> to define the scope of a <i>@Component</i> class or a <i>@Bean</i> definition.&nbsp;
</div><br />
<div> <b><a href="https://www.javaguides.net/2023/02/spring-value-annotation-example.html" target="_blank">@Value Annotation</a></b>
   : Spring @Value annotation is used to assign default values to variables and method arguments.
</div><br />
<div><b><a href="https://www.javaguides.net/2018/09/spring-propertysource-annotation-with-example.html" target="_blank">@PropertySource Annotation</a></b>
   : Spring @PropertySource annotation is used to provide properties files to Spring Environment. Spring PropertySource annotation is repeatable, which means you can have multiple PropertySource on a Configuration class.
</div><br />
<h1 style="text-align: left;">2. Spring MVC Web Annotations</h1>
<div> <b><a href="https://www.javaguides.net/2018/11/the-spring-controller-and-restcontroller-annotations-with-examples.html" target="_blank">@Controller Annotation</a></b>
   : Spring provides @Controller annotation to make a Java class as a Spring MVC controller. The @Controller annotation indicates that a particular class serves the role of a controller.&nbsp;
</div><br />
<div><b><a href="https://www.javaguides.net/2018/11/spring-requestbody-and-responsebody-annotations.html" target="_blank">@ResponseBody Annotation</a></b>
   : The @ResponseBody annotation tells a controller that the object returned is automatically serialized into JSON and passed back into the HttpResponse object.&nbsp;
</div><br />
<div><b><a href="https://www.javaguides.net/2018/11/the-spring-controller-and-restcontroller-annotations-with-examples.html" target="_blank">@RestController Annotation</a></b>
   : Spring 4.0 introduced @RestController, a specialized version of the @Controller which is a convenience annotation that does nothing more than add the @Controller and @ResponseBody annotations.&nbsp;
</div><br />
<div><b><a href="https://www.javaguides.net/2018/11/spring-web-mvc-annotations.html" target="_blank">@RequestMapping Annotation</a></b>
   : <b>@RequestMapping</b> is the most common and widely used annotation in Spring MVC. It is used to map web requests onto specific handler classes and/or handler methods.&nbsp;
</div><br />
<div><b><a href="https://www.javaguides.net/2023/07/getmapping-spring-boot-example.html" target="_blank">@GetMapping Annotation</a></b>
   : The GET HTTP request is used to get single or multiple resources and <i>@GetMapping</i> annotation for mapping HTTP GET requests onto specific handler methods.&nbsp;
</div><br />
<div><b><a href="https://www.javaguides.net/2023/07/postmapping-spring-boot-example.html" target="_blank">@PostMapping Annotation</a></b>
   : The POST HTTP method is used to create a resource and <i>@PostMapping</i> annotation for mapping HTTP POST requests onto specific handler methods.&nbsp;
</div><br />
<div><b><a href="https://www.javaguides.net/2022/04/putmapping-spring-boot-example.html" target="_blank">@PutMapping Annotation</a></b>
   : The PUT HTTP method is used to update the resource and <i>@PutMapping</i> annotation for mapping HTTP PUT requests onto specific handler methods.&nbsp;
</div><br />
<div><b><a href="https://www.javaguides.net/2023/07/deletemapping-spring-boot-example.html" target="_blank">@DeleteMapping Annotation</a></b>
   : The DELETE HTTP method is used to delete the resource and <i>@DeleteMapping</i> annotation for mapping HTTP DELETE requests onto specific handler methods.&nbsp;
</div><br />
<div>
   <b><a href="https://www.javaguides.net/2023/07/patchmapping-spring-boot-example.html" target="_blank">@PatchMapping Annotation</a></b>
   : The PATCH HTTP method is used to update the resource partially and the <i>@PatchMapping</i> annotation is for mapping HTTP PATCH requests onto specific handler methods.<br />
</div><br />
<div><b><a href="https://www.javaguides.net/2019/08/spring-boot-pathvariable-annotation.html" target="_blank">@PathVariable Annotation</a></b>
   : Spring boot @PathVariable annotation is used on a method argument to bind it to the value of a URI template variable.
</div><br />
<div><b><a href="https://www.javaguides.net/2019/08/spring-boot-responsestatus-annotation.html" target="_blank">@ResponseStatus Annotation</a></b>
   : The @ResponseStatus annotation is a Spring Framework annotation that is used to customize the HTTP response status code returned by a controller method in a Spring MVC or Spring Boot application.
</div><br />
<div><b><a href="https://www.javaguides.net/2018/11/spring-service-annotation.html" target="_blank">@Service Annotation</a></b>
   : @Service annotation is used to create Spring beans at the Service layer.
</div><br />
<div><b><a href="https://www.javaguides.net/2018/11/spring-repository-annotation.html" target="_blank">@Repository Annotation</a></b>
   : @Repository is used to create Spring beans for the repositories at the DAO layer.
</div><br />
<div><b><a href="https://www.javaguides.net/2023/07/spring-controller-annotation-example.html" target="_blank">@Controller Annotation</a></b>
   : @Controller is used to create Spring beans at the controller layer.
</div><br />
<h1 style="text-align: left;">3. Spring Boot Annotations</h1>
<div><b><a href="https://www.javaguides.net/2018/09/spring-boot-springbootapplication-annotation-with-example.html" target="_blank">@SpringBootApplication annotation</a></b>
   : The @SpringBootApplication annotation is a core annotation in the Spring Boot framework. It is used to mark the main class of a Spring Boot application. This annotation is a combination of three other annotations: @Configuration, @EnableAutoConfiguration, and @ComponentScan.
</div><br />
<div><b><a href="https://www.javaguides.net/2018/09/spring-boot-enableautoconfiguration-annotation-with-example.html" target="_blank">@EnableAutoConfiguration annotation</a></b>
   : @EnableAutoConfiguration annotation enables Spring Boot's auto-configuration feature, which automatically configures the application based on the classpath dependencies and the environment.&nbsp;<br />
</div><br />
<div><b><a href="https://www.javaguides.net/2018/10/spring-boot-creating-asynchronous-methods-using-async-annotation.html" target="_blank">@Async Annotation</a></b>
   : @Async annotation can be provided on a method so that invocation of that method will occur asynchronously.
</div><br />
<h1 style="text-align: left;">4. Spring Data JPA Annotations</h1>
<div><b><a href="https://www.javaguides.net/2018/11/spring-data-jpa-creating-database-queries-using-query-annotation.html" target="_blank">@Query Annotation</a></b>
   : In Spring Data JPA, the <i>@Query</i> annotation is used to define custom queries. It allows developers to execute both JPQL (Java Persistence Query Language) and native SQL queries.
</div><br />
<div>
<h1 style="text-align: left;">5. Spring Boot Testing Annotations</h1>
<div><b><a href="https://www.javaguides.net/2022/03/springboottest-spring-boot-example.html" target="_blank">@SpringBootTest annotation</a></b>
   : Spring Boot provides @SpringBootTest annotation for Integration testing. This annotation creates an application context and loads the full application context.              
</div><br />
<div><b><a href="https://www.javaguides.net/2022/03/datajpatest-spring-boot-example.html" target="_blank">@DataJpaTest annotation</a></b>
   : Spring Boot provides the @DataJpaTest annotation to test the persistence layer components that will autoconfigure the in-memory embedded database for testing purposes.
</div><br />
<div><b><a href="https://www.javaguides.net/2023/07/spring-boot-webmvctest-annotation.html" target="_blank">@WebMvcTest annotation</a></b>
   :The @WebMvcTest annotation is used to perform unit tests on Spring MVC controllers. It allows you to test the behavior of controllers, request mappings, and HTTP responses in a controlled and isolated environment.
</div><br />

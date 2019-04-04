# spring-boot-oauth2-simple

If you want to add simple oauth2 server to use token to call to apis for example.

Steps:

- Add the dependency spring-cloud-starter-oauth2 (sample in pom.xml)
- Add specifyc properties (sample in application.properties.
- Add SecurityConfiguration.java. This class extends WebSecurityConfigurerAdapter.java and we are overrided one method to call to actuator endpoints without security
- Add the Oauth2AuthenticationServerApplication.

Be water my friend!

# SpringBoot-webapp-security-demo-AppSecurityConfig-InMemDB
Spring boot webapp security demo using InMemDB with default schema

What is it?
----------
Security Configuration class by extending WebSecurityConfigurerAdapter
Override configure(AuthenticationManagerBuilder auth) to add authentication related
loaded with .withDefaultSchema: default schema is created by spring security in H2 in memory database
Added the users in configure method.

override configure(HttpSecurity http) to add the rules for authorization.




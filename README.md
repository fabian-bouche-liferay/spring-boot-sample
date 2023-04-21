# Spring Boot Resource Server trusting Liferay Access Tokens

I've done some similar work a long time ago: https://github.com/raoul-imolczek/spring-security-sample

I've just started to adapt it to Liferay as the OAuth 2.0 Authorization Server and
upgraded it to Spring Boot 3.0

Please have a look at the readme and the code comments of my old sample. Most of it is still relevant.

## To-do

1. For the moment, Liferay does not provide information about roles in the JWT Access Token
I think we should do that.

2. We should also provide a way to register new custom scopes to Liferay. In my example, I'm
currently using a Liferay default scope.

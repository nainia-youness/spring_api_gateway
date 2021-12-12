# spring_api_gateway

spring cloud api gateway app

- redirecting requests to the appropriate services
- does Oauth 2.0/openid authentication with a keycloak auth server
- save sessions in Redis
- implemented a circuit breaker (+retry for temporary fails)

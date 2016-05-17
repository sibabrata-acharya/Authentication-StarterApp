# Sample template application to connect Authentication microservice

### Application steps

1. Create and configure Authentication microservice with the provider AppID and SecretID(Provided from eg.facebook after app configuration)
2. Bind the service to this sample application
3. Check for VCAP_SERVICES provided by Authentication microservice
4. Provide the provider_redirecturi to the provider app configuration. This will redirect from the provider(eg:facebook) to the microservice after authentication
5. send the redirect URIs during the authentication call and logout call. Refer config.js for the same

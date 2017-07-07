# Auth0 - NancyFX

Add the following URL to the list of **Allowed Callback URLs** for your Client in the Auth0 Dashboard:

```
http://localhost:3579/login-callback
```

Replace the following placeholder values in the App.config:

* {DOMAIN}: Your Auth0 domain, e.g. mycompany.auth0.com
* {CLIENT_ID}: The Client ID for your Auth0 Client
* {CLIENT_SECRET}: The Client Secret for your Auth0 Client

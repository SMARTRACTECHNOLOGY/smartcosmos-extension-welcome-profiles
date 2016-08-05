# SMART COSMOS Profiles Welcome Page Service

This microservice adds a Welcome Page and other static assets to SMART COSMOS Profiles.

To integrate this module into Profiles, add the following to your `smartcosmos-gateway.yml`:

```
zuul:
  sensitiveHeaders:
  ignoredServices: "*"
  prefix:
  routes:
    ...
    profiles-ui-welcome: /*
```

Any requests going to the root level will be directed to the ui service accordingly.

### Architecture

```
 ::Spring Boot Admin::
                            Client
                            ┌───────────────────────┐
                        ┌─> │ client-product (8081) │
   Server               │   └───────────────────────┘
 ┌────────────────────┐ │   ┌───────────────────────┐
 │ server      (8761) │ ──> │ client-user    (8082) │
 └────────────────────┘     └───────────────────────┘
```

### Version

- spring boot 2.0.6.RELEASE
- spring boot admin 2.0.4
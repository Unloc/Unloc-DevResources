# Unloc-DevResources
A collection of utils for external developers

## Postman Collections

### Unloc API

This guide assumes you are already somewhat familiar with Postman.
Make sure you import both the collection and the environment, and that the environment is selected.

To use the Unloc API Postman Collection you first need both an Integrator account and a Lock Holder with some locks. Please refer to the Unloc API Documentaton on how to get these.

When you have an Integrator account and a lock holder you start by setting the the collection variables `client_id`, `client_secret`, `lock_holder_country_iso`, `lock_holder_org_id` and `lock_holder_org_id_suffix`.  
If you only have a single lock holder you may set the lock holder variables using the "Get managed Lock Holders" endpoint instead.

Some requests will set variables, for example "Get scoped Access Token" will set `access_token` and `lock_holder_id`. For details check the "Tests" tab on each request.
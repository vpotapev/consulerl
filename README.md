# Consulerl

Erlang client for [Consul](https://consul.io)

## App env vars

These app env vars should be set before using the app:

* `consulerl.hostname` - host name where Consul daemon works
* `consulerl.port` - port used by Consul daemon
* `consulerl.acl` - Consul ACL token (currently used as parameter of any request: `<URL>?acl=<token>`)

## To be done

* Support the `X-Consul-Token <token>` header
* Support the `Authorization: Bearer <token>` header [see (RFC6750](https://tools.ietf.org/html/rfc6750#page-5))

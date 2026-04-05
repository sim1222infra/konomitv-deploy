# KonomiTV Compose Spec

## HTTPS Certificate Generation

```sh
openssl req -x509 -nodes -days 3650 -newkey rsa:2048 -keyout server.key -out server.crt
```

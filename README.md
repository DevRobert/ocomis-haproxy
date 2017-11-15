# Ocomis HA Proxy

## Scope

Accepts all incoming traffic from clients outside of the Ocomis network (e.g. web browsers) and forwards it to the appropriate microservice. This includes UI requests (HTML, JS, CSS) as well as API requests.

## Tech Stack

* HAProxy

## Docker

### Build

`docker build -t blutner/ocomis-haproxy:latest .`

### Publish

`docker push blutner/ocomis-haproxy:latest`
# Docker oauth2_proxy

* Docker image to start a oauth2_proxy running on alpine:latest loads with -config /config/oauth2_proxy.cfg

### Environment Variables
* `OAUTH2_PROXY_VERSION`
* `GO_VERSION`

### Structure
* `/config`: config directory

### Credits
* [skippy/docker-oauth2_proxy](https://github.com/skippy/docker-oauth2_proxy) this is just an update of this fixed to load a hardcoded config
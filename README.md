# nginx-auth-proxy

Add some basic authentication to any webapp by proxying it through this nginx container.

## env vars needed

- `AUTH_TOKEN`

token to be passed as Bearer token for nginx to allow to below

- `PROXY_ADDR`

server to proxy to. Can be DNS or IP

- `PROXY_PORT`

port of server to proxy to

- `PROXY_SCHEME`

optional. default is http

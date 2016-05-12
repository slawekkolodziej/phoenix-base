# Phoenix base image

Base image for phoenix development. It bases on elixir:latest and adds phoenix-related packages including:

- curl
- postgres client
- phoenix
- hex
- rebar

Application will be placed in the /app directory

Default CMD runs `phoenix.server` on default port (4000)


## Get the Container IP of the coolify proxy

`
docker inspect coolify-proxy --format '{{range .NetworkSettings.Networks}}{{.IPAddress}}{{break}}{{end}}'
`
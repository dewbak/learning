# Notes from learning

## Tips and tricks
- Use NOTES.txt to test helm template syntax and for debug printing.

## kind adaptations

Used [this guide][kindLoadBalancerDef] to adapt kind to get LoadBalancer in kind. Need to adapt IP range by checking what kind gets with `docker network inspect -f '{{.IPAM.Config}}' kind`

## weather api

Created a free subscription and api key from [here][weatherApiDef]

[weatherApiDef]: https://rapidapi.com/weatherapi/api/weatherapi-com
[kindLoadBalancerDef]: https://kind.sigs.k8s.io/docs/user/loadbalancer/

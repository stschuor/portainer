# docker_portainer

This helper downloads and launches a Portainer instance

## Requires:
- docker
- docker-compose

Download and run Portainer:
```bash
make
```
Portainer then should be available at http://localhost:9000

Stop Portainer:
```bash
make stop
```

Get rid of Portainer:
```bash
make clean
```
Note: Theres still a portainer_data: volume left behind!

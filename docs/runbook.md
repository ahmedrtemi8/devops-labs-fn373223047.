## Run with Compose

- `docker compose up -d`: Starts all defined services in detached (background) mode.
- `docker compose ps`: Lists the status, ports, and health of active containers.
- `docker compose logs`: Views aggregated stdout/stderr logs from all services.
- `docker compose down`: Stops and removes containers and network, preserving named volumes.
- `docker compose down -v`: Stops and removes containers, networks, AND deletes persistent volumes.
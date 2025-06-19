# Orchestration repo for Timely project apps

## Included apps:
- Nestjs api: https://github.com/MCesarczyk/timely-api
- React todo-list: https://github.com/MCesarczyk/timely-todo-list


## Auxiliary tools:
- Visualizer: https://hub.docker.com/r/dockersamples/visualizer


## Usage:

### Docker compose approach:

- go to `/compose` dir
- run:
```

docker compose up -d

```

### Docker swarm approach:

- initialize swarm `docker swarm init`
- create desired manager and worker nodes
- deploy stack:
```

docker stack deploy --compose-file docker-compose.stack.yml --detach=true

```

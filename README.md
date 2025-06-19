# Orchestration repo for Timely project apps

## Docker compose approach:

- go to `/compose` dir
- run:
```

docker compose up -d

```

## Docker swarm approach:

- initialize swarm `docker swarm init`
- create desired manager and worker nodes
- deploy stack:
```

docker stack deploy --compose-file docker-compose.stack.yml --detach=true

```

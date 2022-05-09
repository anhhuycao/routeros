COMPOSE_FILE = docker-compose.yml

ps:
	docker compose -f ${COMPOSE_FILE} ps
log:
	docker compose -f ${COMPOSE_FILE} logs
down:
	docker compose -f ${COMPOSE_FILE} down
up:
	docker compose -f ${COMPOSE_FILE} up -d
exec:
	docker compose -f ${COMPOSE_FILE} exec api /bin/sh
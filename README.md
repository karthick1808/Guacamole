## Quick start
Clone the GIT repository and start guacamole:

cd guacamole-docker-compose
./prepare.sh
docker-compose up -d
docker stack deploy --compose-file docker-stack.yml vote

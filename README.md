# portainer

# Update the environment
* `git fetch origin && git reset --hard origin/main && git pull`

# Docker-Compose
docker-compose down --volumes && docker image prune -a -f && docker-compose build --no-cache && docker-compose up -d
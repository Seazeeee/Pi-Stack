# Pi-Stack
This is a project to push a Pi-Monitoring stack so that I can make sure that my discord bot is up and running.

Creates an Internal TLS cert with Caddy and well as allowing me to edit the hostfile and target the naming domain for easy access to Grafana dashboard.

Compose allows for easy portability as well as making it super maintainable for future use. Removed metabase and my MTG pipeline as the single Pi was not able to handle it.

## Quick Start
1. Clone the repository
2. Edit your `/etc/hosts` file: `192.168.1.X tiny.lab`
3. Create a .env file
4. Add your preferred Grafana user/pass with the variables located in docker compose. 
5. Run `docker-compose up -d`
6. Access Grafana at `https://tiny.lab`

## Author

Created by Matthew Thompson - [@Seazeeee](https://github.com/Seazeeee)

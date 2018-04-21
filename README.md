# docker-media-center
Docker compose file contains:
* Plex
* Sonarr
* Radarr
* Deluve+VPN
* Transmission
* Ombi
* Tautulli
* Home Assistant
* Node-Red
* Mosquitto MQTT
* InfluxDB
* Grafana
* Portainer
* Traefik reverse proxy

To set up:
1. clone repository
2. Set up and start traefik (edit Traefik.toml)
3. run docker-compose up -d in the main directory
4. check portainer for errors

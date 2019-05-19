# docker-compose
A docker compose file for deploying a nginx reverse proxy with letsencrypt for SSL certification. You can also deploy 

- ghost (free and open source blogging platforming)
- bitwarden (unofficial version of original bitwarden open source password manager)
- plex (media server)
- transmission (torrent client with WebUI while connecting to OpenVPN)
- sonarr (monitor multiple RSS feeds for tv shows)
- radarr (monitor multiple RSS feeds for movies)

Note : Please make sure to add 'A Record' of the subdomain defined in your CONTAINER_URL pointing to the public IP server for VIRTUAL_HOST to work as expected.

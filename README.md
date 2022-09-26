# zigbee2homekit
Docker-based Smart Home

### Portainer

In order to use relative paths for volumes when deploying from Git it's necessary to create a link to the docker volume used by portainer (https://github.com/portainer/portainer/issues/6390#issuecomment-1059848824)

```bash
ln -s /var/lib/docker/volumes/portainer_data/_data /data
```

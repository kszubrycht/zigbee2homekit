# zigbee2homekit
Docker-based Smart Home

### [Mosquitto](https://mosquitto.org/)

mqtt://localhost

### [zigbee2mqtt](https://www.zigbee2mqtt.io/)

http://localhost:8080

### [Homebridge](https://homebridge.io/)

http://localhost:8581

### [Node-RED](https://nodered.org/)

http://localhost:1880

## Portainer

In order to use relative paths for volumes when deploying from Git it's necessary to create a link to the docker volume used by portainer (https://github.com/portainer/portainer/issues/6390#issuecomment-1059848824)

```bash
sudo ln -s /var/lib/docker/volumes/portainer_data/_data /data
```

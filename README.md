### 2P-IOT-Cloud

### dynv6 -> name 2p-cloud.dynv6.net
### build a easy webside / digital ocean with sqlite / bootstrap  bu###/ flask / etc -> https://www.digitalocean.com/community/tutorials/how-to-make-a-web-application-using-flask-in-python-3


### build a flask-webserver in docker -> https://www.digitalocean.com/community/tutorials/how-to-build-and-deploy-a-flask-application-using-docker-on-ubuntu-20-04
# https://learnembeddedsystems.co.uk/easy-raspberry-pi-iot-server

### Install a digital ocean droplet ubuntu 20.04   
https://docs.digitalocean.com/tutorials/recommended-droplet-setup/   

### Initial Server Setup with Ubuntu 20.04    
https://www.digitalocean.com/community/tutorials/initial-server-setup-with-ubuntu-20-04   


### Install Docker       
https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-on-ubuntu-20-04

### Install Docker Compose   
https://docs.docker.com/compose/install/linux/

### Install Portainer   
https://docs.portainer.io/start/install/server/docker/linux

### Install MQTT   
https://blog.feabhas.com/2020/02/running-the-eclipse-mosquitto-mqtt-broker-in-a-docker-container/
https://blog.feabhas.com/2020/02/running-the-eclipse-mosquitto-mqtt-broker-in-a-docker-container/

### for permanent starting mosquitto use this. free console  
docker run -it -d --restart always --name mosquitto -p 1883:1883 -v $(pwd)/mosquitto:/mosquitto/ eclipse-mosquitto 


### Install MQTT, Influxdb, Telegraf und Grafana   
https://gist.github.com/lucassardois

https://lucassardois.medium.com/handling-iot-data-with-mqtt-telegraf-influxdb-and-grafana-5a43148021

---> damit das Beispielprojekt erstellt
---> mosquitto.conf im Container muss editiert werden
---> telegraf.conf muss editiert werden. 

digitalocean droplet: jowi 852685268526
digitalocean droplet: root (normales PasswortSchema) 
account influxdb: admin 852685268526
account grafana: admin 852685268526


### Python-Skript eines mQTT-Clients   
http://www.steves-internet-guide.com/subscribing-topics-mqtt-client/

### HowTo Grafana, InfluxDB, Telegraf, Mosquitto 
https://devconnected.com/how-to-install-influxdb-telegraf-and-grafana-on-docker/   


### Data Logging with MQTT, Node-RED, InfluxDB and Grafana  

https://docs.arduino.cc/tutorials/portenta-x8/datalogging-iot

# MQTT_Broker
Setup of a TLS MQTT Broker. Certificates are assumed that have been previously created by the user.


# How to start the broker
Navigate to the directory  that the docker-composer.yml file is and run the following command in the CLI:
```
sudo docker-compose up -d
```

# Check that the broker is running
In the CLI type:
```
sudo docker ps -a
```

Output will look like this:
```
xxxxxxxxxxxx   eclipse-mosquitto   "/docker-entrypoint.…"   2 months ago   Up 3 seconds   0.0.0.0:8883->8883/tcp, :::8883->8883/tcp, 1883/tcp, 0.0.0.0:9001->9001/tcp, :::9001->9001/tcp   broker_mosquitto_1
```
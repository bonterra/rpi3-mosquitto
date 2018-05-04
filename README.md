# rpi3-mosquitto
# Dockerfile to create Docker container with Eclipse Mosquitto MQTT broker for Raspberry Pi 3
$ docker build -t mosquitto .
$ docker run -d -p 1883:1883 --name mosquitto mosquitto

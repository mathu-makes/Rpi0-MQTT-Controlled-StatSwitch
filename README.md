# Rpi0-MQTT-Controlled-ThermostatSwitch
Rpi0 Access Point + MQTT broker for remote Sonoff control

Goal of project was to modify commercially available Sonoff WiFi smart switch devices and allow for local MQTT switching rather than via Sonoff cloud service. The intended use of the project was to act as thermostat switch for a boiler.
This project helped in my learning to:

    download and install Raspbian to the Rpi0
    update and upgrade the pi via the command line
    follow guides to setup pi as WiFi access-point
    use the command line to install libraries such as Mosquitto
    design a MQTT flow using Node-Red
    understand Tasmota firmware for home automation

Node-Red MQTT flow
![GitHub Logo](/images/Node-Red_flow.jpg)

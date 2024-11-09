# FunTechHouse_DoorBell

## Abstract

This project involves a classic doorbell system with a button outside the door and a bell inside the house. 
However, an Arduino is placed between the button and the bell, enabling actions to be managed via MQTT.

## Goals

When the doorbell button is pressed, two things will occur:
1. The doorbell will ring.
2. An MQTT message will be sent, notifying that the button was pressed.

Additionally, the project subscribes to MQTT messages and will ring the doorbell when a message is received.

The rationale is to connect multiple systems, so all systems are aware when any button is pressed.

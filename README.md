# LoRaWAN Docs

A LoRaWAN network was stablished to collect data from various LoRa supported devices in the lab environment in HumaniSE lab at Monash University Clayton campus.

## The components list
- Chirpstack open source software
- RAK 7244 LoRa gateway with band AS923
- Mosquitto open source MQTT broker.
- Redis open source key value pair database server.
- Grafana to visualize the sensors data.
- PostgreSQL open source database.
- RHS1S001 Temperature & Humidity device.
- TBS220 parking sensor
- PCR2 People counter sensor
- DF702 Smart Bin sensor.
- HP Z2 PC was used a server with 12 Cores Intel Core i5 processor and 32GB RAM.

## Server used.
- Ubuntu Server 20.04.3 LTS (Focal Fossa)

## Network
![plot](./network-diagram/whiteboard/network-20220928-142047.jpg)

## Some Issues faced:
- In order to configure RHF1S001 device I need to manage a window 7 laptop decause device driver was not working on Window 10.

- ChirpStack Network configuration file must have the perfect configuration of Band of LoRa, otherwise you will not get data from device. But you may get REQ, ACCEPT message.

- Failed to add the repository of ChirpStack then downloaded the deb package and install manually.
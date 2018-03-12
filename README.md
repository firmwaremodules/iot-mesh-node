#  Internet of Things Smart City Mesh Node Firmware Core

This IoT Firmware Core enables mesh node functionality on your TI CC13xx MCU based product using the Sub-GHz ISM radio band.  Mesh node functionality allows you to place your devices around the city (subject to radio operating range) where you need them.  Use the Mesh Nodes to control your equipment or read your sensors from your Internet-enabled application.  The Smart City Mesh Node Firmware Core comes configured in UART Data Tunnel mode - send commands to your smart city asset's UART port from anywhere.

## Evaluation Firmware

The evaluation firmware available in this repository is free to use on the specified evaluation platform.  Without an authorization key, the firmware will run for 30 minutes before the radio shuts off.  Simply contact us to receive a free authorization key to enable unlimited evaluation or educational use. Send your device's EUI/UID as reported in the console and we will promptly generate the authorization key specific to your device.

Note that evaluation firmware provided in this repository uses a fixed and public MAC-layer AES-128 security key as specified below. [TBD]


## How Does The Mesh Node Work?

The Smart City Mesh Node Firmware Core communicates to other Mesh Nodes within range of its Sub-GHz radio using an advanced IoT mesh network system called 6LoWPAN.  The mesh network requires a special Mesh Root device to forward packets to and from the Internet.  Mesh Root devices are built using the companion product Smart City Mesh Root Firmware Core.  

## Why Use Devices With Mesh Node Firmware Cores?

You can build your network out quickly with the long range Sub-GHz radio technology, and each device is easily accessed using standard internet protocols. Compared to competing mesh network technologies, the Smart City Mesh Node Firmware Core offers best-in-class power consumption, security and range.  With this system you can eliminate the use of cellular communication technology's cost, complexity and high power consumption.

## Smart City Mesh Use Cases

- Mobile Display Signs
- Sensor Networks
- Telemetry

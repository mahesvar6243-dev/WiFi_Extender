# WiFi_Extender
An ESP32-based Wi-Fi repeater that connects to an existing 2.4 GHz Wi-Fi network and provides an extended wireless access point for improving local network coverage.

ESP32 WiFi Repeater
ESP32-WROOM-32 | Embedded C/C++ | Wi-Fi | TCP/IP | IoT



An ESP32-based wireless networking prototype that connects
to an existing Wi-Fi network and provides an additional
Wi-Fi access point for nearby devices.

Project Overview :

This project implements a dual-radio wireless packet repeater using an ESP32-WROOM-32 and two nRF24L01+ PA/LNA modules.

The ESP32 uses two independent SPI interfaces:

- VSPI for nRF24 #1
- HSPI for nRF24 #2

The first nRF24 receives wireless packets, the ESP32 processes the received data, and the second nRF24 retransmits the packet to another node.

The system is designed to demonstrate packet forwarding, dual-SPI communication, and wireless communication using the nRF24L01+.

 Features:
  - Dual nRF24L01+ wireless interfaces
  - Separate VSPI and HSPI buses
  - Packet reception and retransmission

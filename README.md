# IoT Challenges & Homework
Politecnico di Milano — Internet of Things — _AY 2024–2025_

## About
Four independent works: **three challenges** plus **one homework**.  
Each deliverable is a PDF with reasoning, math, code snippets (where needed), and final answers to the assigned questions/exercises.

Deliverables:
- **Challenge 1 reports**
- **Challenge 2 reports**
- **Challenge 3 reports**
- **Homework reports**

## Goal and requirements
- **Wokwi & Power Consumption**
- **Packet Sniffing**
- **Node-RED + LoRaWAN**
- **Forklift tracking, 802.15.4, RFID**

## Key learnings
- **Architectures:** edge → gateway → cloud; decouple with message brokers for resilience.
- **Embedded coding:** C/C++ on MCUs with tight timing/memory; non-blocking I/O, interrupts, timers, and peripheral drivers (GPIO/ADC/UART/I²C/SPI).
- **ESP32 platform:** task/queue basics (FreeRTOS), deep-sleep/wake sources, Wi-Fi/BLE/ESP-NOW usage, NVS storage, and power-management trade-offs.
- **Device lifecycle & power:** duty-cycle design to balance responsiveness and battery life.
- **Network selection:** choose between short-range (BLE / 802.15.4 / Wi-Fi) and LPWAN (LoRaWAN / NB-IoT) by range, latency, reliability, and energy.
- **Messaging & protocols:** pub/sub (MQTT/MQTT-SN) vs. request/response (CoAP/HTTP); QoS/acks, idempotency, and offline tolerance.
- **Payload design:** compact JSON/CBOR with schema versioning, timestamps, and units.
- **Gateways & brokers:** local broker (e.g., Mosquitto), buffering/backpressure, and optional cloud bridging.
- **Security basics:** TLS/DTLS, device identity (PSK/certs), scoped permissions, and key rotation.
- **Observability & OTA:** structured logs/metrics and safe over-the-air updates for maintainability.
- **Scalability & testing:** topic hierarchies, rate limiting, and reproducible benches/packet captures for performance and energy validation.

## Team Members
- [Andrea Pesciotti](https://github.com/AndreaPes)

## Copyright
This project is licensed under the terms of the [Apache License 2.0](./LICENSE).

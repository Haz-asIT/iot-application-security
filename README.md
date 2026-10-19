# IoT Application Security

This private repository contains the lab activities, security testing results, and supporting evidence for the IoT Application Security course.

## Lab 1 — IoT Security Baseline Assessment

**Objective:** To develop a basic IoT monitoring environment and identify security weaknesses in MQTT communication, device authentication, and the Mobius IN-CSE platform.

### System Architecture

The IoT testbed consists of:

- Ubuntu VirtualBox running the Mosquitto MQTT Broker.
- Two Python-based simulated sensors (`sensor01` and `sensor02`).
- A Python MQTT-to-HTTP bridge.
- Mobius IN-CSE 3.0.1 running on Windows.
- MySQL 8 for IoT resource and telemetry storage.

### Security Testing

The baseline security assessment covers six security tests:

1. MQTT Eavesdropping
2. MQTT Traffic Sniffing using Wireshark
3. Fake Sensor Data Injection
4. Spoofed Originator Testing
5. Service Discovery using Nmap
6. Credential Hunting

### Evidence

All Lab 1 evidence is available in the [evidence/lab1](evidence/lab1/) directory.

The evidence includes screenshots of Checkpoints A1, B1, C1 and C2, security testing results, network packet captures, Nmap scan outputs, and the architecture diagram.

### Security Notice

This repository is intended for authorized educational security testing. Active passwords, authentication tokens, and other sensitive credentials must not be committed to the repository.

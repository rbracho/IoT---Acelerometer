# IoT Accelerator Telemetry System / IoT-Beschleunigungs-Telemetriesystem / Sistema de Telemetría IoT para Acelerómetro

| [Arquitectura-Red](./Arquitectura-Red.md) | [Firmware-ESP32](./Firmware-ESP32.md) | [Node-RED-SQLite](./Node-RED-SQLite.md) |
| :---------------------------------------: | :-----------------------------------: | :-------------------------------------: |
## English

### Overview

This project implements an end-to-end Industrial IoT architecture designed to capture real-time physical sensor data (3-axis acceleration), transmit it securely via MQTT, process it through a Node-RED workflow, persist historical records in an SQLite database, and provide a modern dashboard with a one-click CSV export feature.

### Tech Stack

- **Hardware:** ESP32 Microcontroller (C++ / Arduino Framework).
    
- **Communication:** MQTT Protocol via Eclipse Mosquitto Broker.
    
- **Backend & Processing:** Docker, Node-RED, SQLite.
    
- **Frontend:** Node-RED Dashboard 2.0 (Vue.js / HTML / CSS).
    
- **Cloud Infrastructure:** DigitalOcean Droplet (Ubuntu) with secure firewall configurations (Ports 1883 & 1880).

### Documentation Index

- [Network Architecture & Firewall](https://www.google.com/search?q=./Arquitectura-Red.md) — Security perimeter, DigitalOcean firewall rules, and ports 1883/1880.
    
- [ESP32 Firmware & JSON Payload](https://www.google.com/search?q=./Firmware-ESP32.md) — Hardware peripherals, sensor acquisition, and JSON serialization.
    
- [Node-RED Workflow, SQLite & CSV Export](https://www.google.com/search?q=./Node-RED-SQLite.md) — Event-driven flow processing, database persistence, and client-side web tools.

---
## Deutsch

### Übersicht

Dieses Projekt implementiert eine durchgängige Industrielle IoT-Architektur, die entwickelt wurde, um physikalische Sensordaten in Echtzeit (3-Achsen-Beschleunigung) zu erfassen, sicher via MQTT zu übertragen, über einen Node-RED-Workflow zu verarbeiten, historische Datensätze in einer SQLite-Datenbank zu speichern und ein modernes Dashboard mit einer Ein-Klick-CSV-Exportfunktion bereitzustellen.

### Technologie-Stack

- **Hardware:** ESP32-Mikrocontroller (C++ / Arduino Framework).
    
- **Kommunikation:** MQTT-Protokoll über Eclipse Mosquitto Broker.
    
- **Backend & Verarbeitung:** Docker, Node-RED, SQLite.
    
- **Frontend:** Node-RED Dashboard 2.0 (Vue.js / HTML / CSS).
    
- **Cloud-Infrastruktur:** DigitalOcean Droplet (Ubuntu) mit sicheren Firewall-Konfigurationen (Ports 1883 & 1880).

### Dokumentationsindex

- [Netzwerkarchitektur & Firewall](https://www.google.com/search?q=./Arquitectura-Red.md) — Sicherheitsperimeter, DigitalOcean-Firewall-Regeln und Ports 1883/1880.
    
- [ESP32-Firmware & JSON-Nutzdaten](https://www.google.com/search?q=./Firmware-ESP32.md) — Hardware-Peripherie, Datenerfassung und JSON-Serialisierung.
    
- [Node-RED-Workflow, SQLite & CSV-Export](https://www.google.com/search?q=./Node-RED-SQLite.md) — Ereignisgesteuerte Ablaufverarbeitung, Datenbankpersistenz und Client-seitige Web-Tools.

---
## Español

### Resumen

Este proyecto implementa una arquitectura IoT industrial de extremo a extremo diseñada para capturar datos de sensores físicos en tiempo real (aceleración de 3 ejes), transmitirlos de forma segura mediante MQTT, procesarlos a través de un flujo de Node-RED, persistir registros históricos en una base de datos SQLite y proporcionar un panel de control moderno con una función de exportación CSV en un solo clic.

### Pila Tecnológica

- **Hardware:** Microcontrolador ESP32 (C++ / Framework Arduino).
    
- **Comunicación:** Protocolo MQTT a través del Broker Eclipse Mosquitto.
    
- **Backend y Procesamiento:** Docker, Node-RED, SQLite.
    
- **Frontend:** Node-RED Dashboard 2.0 (Vue.js / HTML / CSS).
    
- **Infraestructura Cloud:** DigitalOcean Droplet (Ubuntu) con configuraciones de firewall seguras (Puertos 1883 y 1880).

### Índice de Documentación

- [Arquitectura de Red y Firewall](https://www.google.com/search?q=./Arquitectura-Red.md) — Perímetro de seguridad, reglas del firewall de DigitalOcean y puertos 1883/1880.
    
- [Firmware del ESP32 y Estructura JSON](https://www.google.com/search?q=./Firmware-ESP32.md) — Periféricos de hardware, adquisición de sensores y serialización JSON.
    
- [Flujo de Node-RED, SQLite y Exportación CSV](https://www.google.com/search?q=./Node-RED-SQLite.md) — Procesamiento de flujos orientados a eventos, persistencia en base de datos y herramientas web del lado del cliente.
 



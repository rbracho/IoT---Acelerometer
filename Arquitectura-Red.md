# Network Architecture & Firewall / Netzwerkarchitektur & Firewall / Arquitectura de Red y Firewall

| [Firmware-ESP32](./Firmware-ESP32.md) | [Node-RED-SQLite](./Node-RED-SQLite.md) | [README](./README.md) |
| :-----------------------------------: | :-------------------------------------: | --------------------- |

## English

### Overview

The network architecture isolates the cloud infrastructure from local hardware and client browsers using a secure perimeter. The **DigitalOcean Firewall** blocks all traffic by default, only allowing explicit ports required for communication.

### Key Ports & Routing

- **Port 1883 (MQTT):** Dedicated persistent channel for the ESP32 microcontroller to publish telemetry data directly to the Eclipse Mosquitto broker.
    
- **Port 1880 (HTTP / WebSockets):** Web channel used by the client browser (running on the user's laptop) to access the Node-RED dashboard and maintain real-time bidirectional communication via WebSockets.
    
- **Client Isolation:** The local laptop's firewall does not interfere with outbound traffic or WebSocket sessions, allowing secure concurrent multi-user visualization.
    

## Deutsch

### Übersicht

Die Netzwerkarchitektur trennt die Cloud-Infrastruktur durch eine sichere Perimeter-Schicht von lokaler Hardware und Client-Browsern. Die **DigitalOcean Firewall** blockiert standardmäßig den gesamten Datenverkehr und lässt nur explizite Ports zu, die für die Kommunikation erforderlich sind.

### Wentliche Ports & Routing

- **Port 1883 (MQTT):** Dedizierter, persistenter Kanal für den ESP32-Mikrocontroller, um Telemetriedaten direkt an den Eclipse Mosquitto Broker zu senden.
    
- **Port 1880 (HTTP / WebSockets):** Webkanal, der vom Client-Browser (auf dem Laptop des Benutzers) verwendet wird, um auf das Node-RED-Dashboard zuzugreifen und eine bidirektionale Echtzeitkommunikation über WebSockets aufrechtzuerhalten.
    
- **Client-Isolierung:** Die Firewall des lokalen Laptops stört den ausgehenden Datenverkehr oder die WebSocket-Sitzungen nicht, was eine sichere, gleichzeitige Multi-User-Visualisierung ermöglicht.
    

## Español

### Resumen

La arquitectura de red aísla la infraestructura en la nube del hardware local y los navegadores de los clientes mediante un perímetro de seguridad. El **Firewall de DigitalOcean** bloquea todo el tráfico por defecto, permitiendo únicamente los puertos explícitos necesarios para la comunicación.

### Puertos Clave y Enrutamiento

- **Puerto 1883 (MQTT):** Canal persistente y dedicado para que el microcontrolador ESP32 publique datos de telemetría directamente en el broker Eclipse Mosquitto.
    
- **Puerto 1880 (HTTP / WebSockets):** Canal web utilizado por el navegador del cliente (ejecutándose en la laptop del usuario) para acceder al panel de Node-RED y mantener una comunicación bidireccional en tiempo real mediante WebSockets.
    
- **Aislamiento del Cliente:** El firewall de la laptop local no interfiere con el tráfico saliente ni con las sesiones de WebSocket, permitiendo una visualización multiusuario concurrente y segura.



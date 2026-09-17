
## ESP32 Firmware & JSON Payload / ESP32-Firmware & JSON-Nutzdaten / Firmware del ESP32 y Estructura JSON

| [[Arquitectura-Red]] | [[Firmware-ESP32]] | [[Node-RED-SQLite]] | [[README]] |
| :------------------: | :----------------: | :-----------------: | ---------- |
## English

### Overview

The firmware running on the ESP32 microcontroller is responsible for initializing the hardware peripherals (such as the 3-axis accelerometer), establishing a reliable Wi-Fi connection, and periodically publishing structured telemetry payloads to the cloud MQTT broker.

### Core Firmware Responsibilities

- **Sensor Data Acquisition:** Reads raw digital acceleration values ($X, Y, Z$) at defined time intervals.
    
- **JSON Serialization:** Packages the sensor readings along with a unique device identifier and sequence number into a standardized JSON format.
    
- **MQTT Publishing:** Connects securely to the broker via TCP/IP and publishes the payload onto a specific telemetry topic.
    

## Deutsch

### Übersicht

Die Firmware, die auf dem ESP32-Mikrocontroller läuft, ist für die Initialisierung der Hardware-Peripheriegeräte (wie dem 3-Achsen-Beschleunigungsmesser), den Aufbau einer stabilen WLAN-Verbindung und die periodische Veröffentlichung strukturierter Telemetriedaten an den Cloud-MQTT-Broker verantwortlich.

### Kernaufgaben der Firmware

- **SensorDatenerfassung:** Liest rohe digitale Beschleunigungswerte ($X, Y, Z$) in definierten Zeitintervallen aus.
    
- **JSON-Serialisierung:** Verpackt die Sensormesswerte zusammen mit einer eindeutigen Geräte-ID und einer Sequenznummer in ein standardisiertes JSON-Format.
    
- **MQTT-Veröffentlichung:** Verbindet sich sicher über TCP/IP mit dem Broker und veröffentlicht die Nutzdaten in einem spezifischen Telemetrie-Topic.
    

## Español

### Resumen

El firmware que se ejecuta en el microcontrolador ESP32 es responsable de inicializar los periféricos de hardware (como el acelerómetro de 3 ejes), establecer una conexión Wi-Fi estable y publicar periódicamente paquetes de telemetría estructurados hacia el broker MQTT en la nube.

### Responsabilidades Clave del Firmware

- **Adquisición de Datos del Sensor:** Lee los valores digitales de aceleración en bruto ($X, Y, Z$) a intervalos de tiempo definidos.
    
- **Serialización JSON:** Empaqueta las lecturas del sensor junto con un identificador de dispositivo único y un número de secuencia en un formato JSON estandarizado.
    
- **Publicación MQTT:** Se conecta de forma segura al broker mediante TCP/IP y publica los datos en un tópico de telemetría específico.


| [[Arquitectura-Red]] | [[Firmware-ESP32]] | [[Node-RED-SQLite]] | [[README]] |
| :------------------: | :----------------: | :-----------------: | ---------- |
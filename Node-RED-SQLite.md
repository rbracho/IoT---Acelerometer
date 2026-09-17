
# Node-RED Workflow, SQLite & CSV Export / Node-RED-Workflow, SQLite & CSV-Export / Flujo de Node-RED, SQLite y Exportación CSV

| [[Arquitectura-Red]] | [[Firmware-ESP32]] | [[README]] |
| :------------------: | :----------------: | ---------- |

## English

### Overview

The server-side data pipeline combines **Node-RED** for asynchronous event-driven flow processing, an **SQLite** database for lightweight historical persistence, and a custom **Vue-based Template node** to handle real-time visualization and single-click CSV exports.

### Core Processing Components

- **Message Broker Ingestion:** Subscribes to the Mosquitto MQTT broker to capture incoming JSON telemetry events from the ESP32 devices asynchronously.
    
- **Database Persistence:** Automatically stores incoming timestamped sensor records into a local SQLite database table, managing brief write-lock cycles efficiently.
    
- **Real-time Distribution & UI:** Broadcasts incoming data points via WebSockets to all connected client browsers simultaneously without session cross-talk.
    
- **Unified CSV Export:** Integrates a custom client-side template leveraging local memory and Blob objects to generate and download a clean CSV file on demand with a single click.
    

## Deutsch

### Übersicht

Die serverseitige Daten-Pipeline kombiniert **Node-RED** für die asynchrone, ereignisgesteuerte Ablaufverarbeitung, eine **SQLite**-Datenbank für eine schlanke historische Persistenz und einen benutzerdefinierten **Vue-basierten Template-Knoten** zur Bewältigung der Echtzeit-Visualisierung und des Ein-Klick-CSV-Exports.

### Hauptverarbeitungskomponenten

- **Message-Broker-Erfassung:** Abonniert den Mosquitto-MQTT-Broker, um eingehende JSON-Telemetrieereignisse von den ESP32-Geräten asynchron zu erfassen.
    
- **Datenbank-Persistenz:** Speichert eintreffende, mit Zeitstempeln versehene Sensordatensätze automatisch in einer lokalen SQLite-Datenbanktabelle und verwaltet kurze Schreibsperr-Zyklen effizient.
    
- **Echtzeit-Verteilung & Benutzeroberfläche:** Überträgt eingehende Datenpunkte über WebSockets gleichzeitig und ohne Sitzungsüberschneidungen an alle verbundenen Client-Browser.
    
- **Einheitlicher CSV-Export:** Integriert ein benutzerdefiniertes Client-seitiges Template, das den lokalen Speicher und Blob-Objekte nutzt, um auf Anfrage mit nur einem Klick eine saubere CSV-Datei zu generieren und herunterzuladen.
    

## Español

### Resumen

La tubería de datos del servidor combina **Node-RED** para el procesamiento de flujos asíncronos orientados a eventos, una base de datos **SQLite** para la persistencia histórica ligera y un **nodo template personalizado basado en Vue** para gestionar la visualización en tiempo real y la exportación de CSV en un solo clic.

### Componentes Clave de Procesamiento

- **Ingesta del Broker de Mensajes:** Se suscribe al broker MQTT Mosquitto para capturar de forma asíncrona los eventos de telemetría JSON entrantes desde los dispositivos ESP32.
    
- **Persistencia en Base de Datos:** Almacena automáticamente los registros de sensores entrantes con marca de tiempo en una tabla de base de datos SQLite local, gestionando eficientemente los breves ciclos de bloqueo de escritura.
    
- **Distribución en Tiempo Real e Interfaz:** Transmite los puntos de datos entrantes a través de WebSockets a todos los navegadores clientes conectados simultáneamente sin interferencias entre sesiones.
    
- **Exportación CSV Unificada:** Integra una plantilla personalizada del lado del cliente que utiliza la memoria local y objetos Blob para generar y descargar un archivo CSV limpio bajo demanda con un solo clic.


| [[Arquitectura-Red]] | [[Firmware-ESP32]] | [[README]] |
| :------------------: | :----------------: | ---------- |
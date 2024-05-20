# WaterWard 

### Smart Water Managment And Monotring System 
###  **Where Every drop counts..!**


# Team 
 - Ayham Al Ali
 - Abdallah Abu Husssein
 - Rama Iron
 - Huba Rashied

# System Requirments 
1. **Water Level Monitoring:**
The system should continuously monitor the water level for each tank.

2. **Water Quality Monitoring:**
The system should continuously monitor the water quality for each tank.

3. **Hub/App Connectivity:**
The system should enable multiple tanks to connect to a single Hub or application.

4. **Motor Control Based on Water Level:**
The system should provide the capability to remotely control the Tank Motor for each tank.

5. **Remote Valve Tank Control:**
The system should provide the capability to remotely control the Tank valve for each tank.

6. **AI-Based Usage Prediction:**
The system should predict upcoming possible water usage using Artificial Intelligence (AI) and notify stakeholders.

7. **Notifications Managment:**
The system should send notifications to stakeholders for specific events including stealing/theft,water leakage, and government/external tank filling status.

8. **Water Flow Managment**
The system shall monitor Water flow coming out of the Tank.

# Hardware
- ESP32 (Microcontroller)
- Ultra Soinc Sensor (Water Level)
- PH Sensor (Water Quality)
- TDS Sensor (Water Quality)
- Turbidity (Water Quality)
- Temperature Sensor
- Water Flow Sensor
- Tank Valve
- Motor Valve



# Software

## Mqtt
MQTT (Message Queuing Telemetry Transport) is a lightweight, publish-subscribe network protocol designed for efficient communication in constrained environments. It was originally developed by IBM in the late 1990s and has since become a widely adopted standard, especially in the realm of the Internet of Things (IoT). MQTT is ideal for applications where bandwidth and battery power are at a premium, such as in sensor networks, mobile devices, and remote monitoring systems.

- Lightweight and Efficient: MQTT's minimal packet overhead makes it ideal for devices with limited processing power and network bandwidth. The protocol's simplicity ensures low data transmission costs, which is critical in many IoT applications.

- Publish-Subscribe Model: Unlike traditional client-server models, MQTT uses a publish-subscribe architecture. Clients (devices) publish messages to topics, and other clients subscribe to these topics to receive the messages. This decouples the message sender from the receiver, enabling scalable and flexible communication.

- Quality of Service (QoS) Levels: MQTT supports three levels of message delivery assurance:

    QoS 0: At most once delivery (fire-and-forget).
    QoS 1: At least once delivery (acknowledged delivery).
    QoS 2: Exactly once delivery (ensured delivery without duplication).

- Persistent Sessions: MQTT allows clients to maintain session information between connections. This is particularly useful for devices that may intermittently lose network connectivity, enabling them to resume communication without losing context.

- Last Will and Testament (LWT): MQTT clients can specify a message that will be sent by the broker if the client unexpectedly disconnects. This feature helps maintain system reliability by informing other clients of sudden outages

![Hive MQ](https://www.hardcopyworld.com/wp-content/uploads/2021/06/publish_flow.png)

## InfluxDB
InfluxDB is an open-source time series NO-SQL database optimized for handling high write and query loads, making it ideal for managing time-stamped data like metrics and events. Developed by InfluxData, it excels in storing, analyzing, and visualizing large volumes of data efficiently.
 ## Key Features

    - Time Series Optimization: Efficiently handles time-based data.
    - High Throughput: Ingests millions of data points per second.
    - Schema Flexibility: Allows easy addition of new data types and fields.
    - Powerful Query Language (Flux): Supports complex data analysis.
    - Retention Policies: Manages storage by expiring old data.

## React Native
React Native is an open-source framework developed by Facebook for building mobile applications using JavaScript and React. It allows developers to create natively rendered apps for both iOS and Android platforms from a single codebase, significantly reducing development time and effort. Leveraging the same design principles as React, such as component-based architecture and state management, React Native enables efficient and scalable app development. Additionally, it provides a rich set of pre-built components and native modules, facilitating seamless integration with platform-specific features and enhancing the overall user experience.


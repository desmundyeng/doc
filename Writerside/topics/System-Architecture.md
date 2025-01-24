# System Architecture
<img src="MDMS-system-architecture.png" alt="Alt text" width="900" thumbnail="true"/>

### Key Components

### Front-end
#### Device Management Portal
This is where users can view real-time data from their IoT devices. It likely includes features like energy consumption readings, device status, and alerts.

####  Work Order Field Mobile App
This app is used by field technicians to perform work orders, such as meter installations, replacements, removal or diagnosis.

#### Field Diagnosis Mobile App
This app assists technicians to retrieve diagnosis information from devices in the field.

#### Mesh Network Visualizer
Provides a visual representation of the OpenWSN mesh network topology.


### Back-end
#### Head End System (HES)
The central hub of the system, responsible for collecting and processing data from devices. It includes modules for data aggregation, storage, and analysis.

#### Meter Data Management System (MDMS)
Handles meter-specific data, such as readings, analytics, reports, work orders, customers and billing information.

#### Health Monitoring Services
Services that monitor the health and status of HES and portals.

#### Machine Learning-enabled Time-series Forecasting
Predicts future trends and patterns in consumption or other relevant data.

#### Machine Learning-enabled Image Recognition/Object Detection
System to identify and classify objects or patterns in images or video data.
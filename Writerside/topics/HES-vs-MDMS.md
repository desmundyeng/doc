# Scopes of HES and MDMS

## Features

> HES interfaces with devices and manage, control and collect data.

> MDMS retrieves data from HES to store, process, validate, and analyze.

| Feature              | Head-End System (HES)                                           | Meter Data Management System (MDMS)                              |
|----------------------|-----------------------------------------------------------------|------------------------------------------------------------------|
| **Primary Function** | Collects raw data from meters and devices                       | Processes, validates, and analyzes meter data                    |
| **Data Handling**    | Retrieves and forwards data to MDMS                             | Stores, cleans, and organizes data for analysis                  |
| **Communication**    | Interfaces with meters via communication protocols              | Interfaces with enterprise applications                          |
| **Storage Duration** | Short-term, typically temporary data storage                    | Long-term storage for historical analysis                        |
| **Data Processing**  | Minimal processing (mostly data relay)                          | Performs validation, estimation, and correction                  |
| **Role in IoT**      | Acts as a gateway between meters and MDMS                       | Provides analytics and decision-making support                   |
| **Integration**      | Connects with meters via AMI (Advanced Metering Infrastructure) | Integrates with billing, analytics, and other enterprise systems |
| **Error Handling**   | Reports raw communication failures                              | Detects anomalies and corrects inconsistencies                   |
| **Security Focus**   | Ensures secure meter communication                              | Enforces data governance and compliance                          |
| **End Users**        | Utility IT teams, network operators                             | Utility analysts, billing teams, and regulators                  |

## Modules

> HES uses MIU Serial Number as identifier.

> MDMS uses Meter Serial Number as identifier.

| **Head-End System (HES)**                                    | **Meter Data Management System (MDMS)**                                  |
|--------------------------------------------------------------|--------------------------------------------------------------------------|
| 🟢 **Login (Authentication & Authorization)**                | 🟢 **Login (Authentication & Authorization)**                            |
| 🟢 **Dashboard**                                             | 🟢 **Dashboard**                                                         |
| 🟢 **Meters (Status, Anomaly)**                              | 🟢 **Meters (Status, Anomaly)**                                          |
| 🟢 **Geographical Information System (GIS)**                 | 🟢 **Geographical Information System (GIS)**                             |
| 🟢 **Users**                                                 | 🟢 **Users**                                                             |
| 🟢 **Groups**                                                | 🟢 **Groups**                                                            |
| 🟢 **Analysis (Consumption, Alarm, KPI)**                    | 🟢 **Analysis (Consumption, Alarm, KPI, Time Series Forecasting, etc.)** |
| 🟢 **Downlink**                                              |                                                                          |
| 🟢 **Firmware Update**                                       |                                                                          |
| 🟢 **Mesh Network Visualizer**                               |                                                                          |
| 🟢 **Data Pusher (data integration to customer own system)** | 🟢 **Data Integration (can be integrated with third-party HES)**         |
|                                                              | 🟢 **Customers**                                                         |
|                                                              | 🟢 **Work Orders (Install, Remove, Replace & Diagnose)**                 |
|                                                              | 🟢 **Data Warehouse**                                                    |
|                                                              | 🟢 **Reports**                                                           |
|                                                              | ⚪ **VEE (Validating, Editing and Estimating)**                           |
|                                                              | ⚪ **Billing Management (eBilling)**                                      |
| 🟡 **Mobile Apps (Field Diagnostic App)**                    | 🟡 **Mobile Apps (Work Order Field App)**                                |
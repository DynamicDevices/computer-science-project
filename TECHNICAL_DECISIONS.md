# Technical Decisions - Finalized

**Last Updated**: January 2026

---

## ✅ Confirmed Technical Decisions

### Programming Language
- **Decision**: Python
- **Justification**: Excellent libraries for sensors, MQTT, web development
- **Status**: ✅ Confirmed

### Development Environment
- **Decision**: VS Code (with Cursor where allowed)
- **Justification**: Free, excellent Python support, widely used, Cursor provides AI assistance
- **Status**: ✅ Confirmed

### Testing Framework
- **Decision**: pytest
- **Justification**: Standard Python testing framework, well-documented, excellent for sensor testing
- **Status**: ✅ Confirmed

### MQTT Broker
- **Decision**: Mosquitto (local broker)
- **Justification**: 
  - Open source, widely used
  - Easy local setup for development
  - Can move to cloud later if needed
  - Good Python library support (paho-mqtt)
- **Status**: ✅ Confirmed
- **Note**: Can migrate to cloud broker (HiveMQ, AWS IoT) later if required

### Data Storage
- **Decision**: Prometheus
- **Justification**: 
  - Time-series database ideal for sensor data
  - Excellent integration with Grafana
  - Industry standard for monitoring
- **Status**: ✅ Confirmed

### Web Visualization
- **Decision**: Grafana
- **Justification**: 
  - Professional monitoring and visualization platform
  - Excellent Prometheus integration
  - Rich dashboard capabilities
  - Industry standard
- **Status**: ✅ Confirmed

### Hardware Platform
- **Decision**: Application Board 3.1 (PN: 0440.AB0.211)
- **Status**: ✅ Received
- **Note**: Need to research if board has its own processor or requires external host

---

## Technology Stack Summary

```
Sensor Board (Application Board 3.1)
    ↓
Python Sensor Drivers (I2C/SPI)
    ↓
Data Processing & Validation
    ↓
MQTT Client (paho-mqtt) → Mosquitto Broker
    ↓
Prometheus (Time-series storage)
    ↓
Grafana (Visualization dashboards)
```

---

## Development Tools

- **IDE**: VS Code (with Cursor where allowed)
- **Version Control**: Git
- **Testing**: pytest
- **Language**: Python 3.x
- **MQTT Library**: paho-mqtt
- **MQTT Broker**: Mosquitto (local)

---

## Setup Requirements

### Software to Install
1. Python 3.x
2. VS Code
3. Cursor (where allowed)
4. Git
5. Mosquitto MQTT broker
6. Prometheus
7. Grafana

### Python Libraries (to be installed)
- paho-mqtt (MQTT client)
- prometheus-client (Prometheus integration)
- [Sensor-specific libraries - to be determined]
- pytest (testing)
- [Other dependencies - to be determined during development]

---

## Next Steps

1. [ ] Set up development environment (VS Code, Python, Git)
2. [ ] Install Mosquitto broker
3. [ ] Install Prometheus
4. [ ] Install Grafana
5. [ ] Research Application Board 3.1 documentation
6. [ ] Set up Python project structure
7. [ ] Begin sensor driver development

---

**Status**: Core technical decisions finalized  
**Ready for**: Development environment setup

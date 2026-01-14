# OCR A Level Computer Science H446 - Project Proposal
## EXAMPLE - Fill in with your specific details

**Student Name**: Anthony Lennon  
**Candidate Number**: [Your candidate number]  
**Centre Number**: [Your centre number]  
**Date**: January 29, 2026  
**Project Title**: Environmental Sensor Board Software System

---

## Project Title

**Environmental Sensor Board Software System**

---

## Project Brief

### Problem Statement

Environmental monitoring is increasingly important for councils, companies, and governments to understand air quality, pollution levels, and environmental conditions. Current solutions are often expensive, inflexible, or require significant technical expertise to deploy and integrate. There is a need for a flexible, cost-effective sensor board system that can monitor multiple environmental parameters (gas concentrations, particulate matter, CO2 levels) and provide real-time data visualization through a web interface.

This project will develop the software component of a multi-sensor environmental monitoring board, focusing on sensor driver development, data acquisition, MQTT communication, and web-based data visualization. The system will integrate with Bosch BME 690 gas sensors, particulate sensors, and CO2 sensors to provide comprehensive environmental monitoring capabilities.

### Why This Problem Lends Itself to a Computational Solution

This problem requires computational methods because:
1. **Real-time Data Processing**: Sensors generate continuous data streams that require efficient processing, filtering, and calibration algorithms
2. **Communication Protocols**: Implementing MQTT protocol for reliable data transmission requires network programming and protocol implementation
3. **Data Visualization**: Creating interactive web interfaces for real-time sensor data visualization requires web development and data processing
4. **Sensor Integration**: Developing drivers for multiple sensor types requires understanding of I2C/SPI communication protocols and hardware abstraction
5. **Error Handling**: Robust error detection and recovery for sensor failures, communication issues, and data validation requires algorithmic problem-solving

The computational solution will demonstrate programming skills in sensor communication, data structures for buffering and processing sensor data, network programming for MQTT, and web development for data visualization.

### Computational Features

The solution will include:
- **Sensor Driver Development**: Low-level communication with Bosch sensors via I2C/SPI protocols
- **Data Processing Algorithms**: Calibration, filtering, and validation of sensor readings
- **MQTT Communication**: Implementation of MQTT client for real-time data transmission
- **Web Interface**: Interactive web application for real-time sensor data visualization
- **Error Handling**: Robust error detection and recovery mechanisms
- **Data Logging**: Storage and retrieval of historical sensor data

---

## Stakeholders

1. **Hardware Team** (Michael Hull, Ollie Hull) - Designing sensor board hardware
2. **Software Lead** (Alex Lennon) - Technical guidance and mentoring
3. **End Users** (Councils, Companies) - Future customers requiring environmental monitoring
4. **Computer Science Teacher** - Project supervisor and OCR assessment
5. **OCR Examiners** - Assessment evaluators

---

## Success Criteria

### Functional (Measurable)
- ✅ System reads data from all three sensors (BME 690, particulate, CO2) with accuracy within manufacturer specifications
- ✅ Sensor data transmitted via MQTT with <1% packet loss and <100ms latency
- ✅ Web interface displays real-time data with <2 second update latency
- ✅ System detects sensor failures within 5 seconds and continues operating (graceful degradation)

### Quality
- ✅ Code test coverage >80% for sensor drivers
- ✅ System processes sensor readings at minimum 1Hz (1 reading per second per sensor)
- ✅ All public APIs fully documented

### Educational
- ✅ Achieve marks in upper bands for all OCR assessment sections
- ✅ Demonstrate A Level programming skills (beyond GCSE)
- ✅ Show evidence of iterative development and team collaboration

---

## Technical Approach

- **Language**: Python (excellent for sensors, MQTT, web development)
- **Sensors**: Bosch BME 690 (gas), particulate sensor, CO2 sensor
- **Communication**: MQTT protocol (paho-mqtt library)
- **Web**: Flask/FastAPI backend, HTML/CSS/JavaScript frontend
- **Development**: Iterative, starting with evaluation boards (EVKs)

---

## Project Scope

### In Scope
- Sensor driver development (3 sensors)
- MQTT communication implementation
- Web interface for data visualization
- Data logging and error handling
- Integration with evaluation boards

### Out of Scope
- Hardware design (hardware team)
- Advanced AI/ML features (future enhancement)
- Mobile applications
- Cloud infrastructure

---

## Timeline

- **Weeks 1-2**: Analysis (research, requirements, success criteria)
- **Weeks 3-4**: Design (algorithms, data structures, test plans)
- **Weeks 5-10**: Development (iterative, sensor by sensor)
- **Weeks 11-12**: Testing and refinement
- **Weeks 13-14**: Evaluation and documentation

**Duration**: Until end of 2026

---

## OCR Assessment Alignment

- ✅ **Analysis (10 marks)**: Problem, stakeholders, research, requirements, success criteria
- ✅ **Design (15 marks)**: Decomposition, algorithms, data structures, test plans
- ✅ **Development (25 marks)**: Substantial Python programming, iterative development, team collaboration
- ✅ **Evaluation (20 marks)**: Measurable criteria, stakeholder feedback, performance analysis

---

## Why Suitable for A Level

1. **Appropriate Complexity**: Sensor protocols, network programming, web development
2. **Programming Skills**: Hardware communication, MQTT, web apps, data structures
3. **Real-World**: Professional engineering project with commercial viability
4. **Sufficient Scope**: Multiple sensors, multiple software components
5. **Beyond GCSE**: Hardware-software integration, professional practices

---

## Approval

**Student Signature**: _________________________ **Date**: _______________

**Teacher Approval**: _________________________ **Date**: _______________

---

*This is a template/example. Customize with your specific details and get teacher approval.*

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

**Specific Use Cases**:
- **Classroom CO2 Monitoring**: Monitor CO2 levels in classrooms to understand impact on learning and cognitive function
- **Indoor Air Quality**: Detect vaping, smoking, and other air quality issues in indoor environments
- **Fire Prevention**: Early detection of burning materials (plastics, wiring) before ignition
- **Presence Detection**: Detect occupancy in rooms through environmental changes
- **Pollution Monitoring**: Track air pollution levels, particularly relevant for monitoring diesel emissions in port areas (e.g., Liverpool docks)

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
   - Anthony will assist with hardware development and prepare test/demonstration software
2. **Software Lead** (Alex Lennon) - Technical guidance and mentoring
   - Primary focus: Software development for OCR assessment
3. **End Users** (Councils, Companies, Schools) - Future customers requiring environmental monitoring
   - Use cases: Classroom monitoring, pollution tracking, safety monitoring
4. **Computer Science Teacher** - Project supervisor and OCR assessment
5. **OCR Examiners** - Assessment evaluators
   - **Note**: OCR assessment focuses on software component (Anthony's primary work)

---

## Success Criteria

### Functional (Measurable)
- ✅ System reads data from BME 690 sensor (8x8 array) via Application Board 3.1 (PN: 0440.AB0.211)
- ✅ System reads data from all sensors (BME 690, particulate, CO2) with accuracy within manufacturer specifications
- ✅ Sensor data transmitted via MQTT with <1% packet loss and <100ms latency
- ✅ Web interface (Grafana) displays real-time data with <2 second update latency
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
- **Hardware Platform**: 
  - Bosch Application Board 3.1 (PN: 0440.AB0.211)
  - BMV080 Shuttle Board with BME 690 sensor (SPN: 0273.SB0.000)
  - Additional sensors: Particulate sensor, CO2 sensor (to be added)
- **Sensors**: 
  - BME 690 gas sensor (8x8 array, APP3.0) - **Received**
  - Particulate sensor - To be received
  - CO2 sensor - To be received
- **Communication**: MQTT protocol (paho-mqtt library) - Cloud or self-hosted broker
- **Data Storage**: Prometheus (time-series database for sensor data)
- **Web Visualization**: Grafana (monitoring and visualization platform)
- **Development**: Iterative, starting with evaluation boards (EVKs) - **EVKs received**

---

## Project Scope

### In Scope
- **Software Development** (Primary - OCR assessment focus):
  - Sensor driver development (3 sensors: BME 690, particulate, CO2)
  - MQTT communication implementation (cloud or self-hosted broker)
  - Prometheus integration for time-series data storage
  - Grafana dashboard configuration for data visualization
  - Data processing algorithms (calibration, filtering, validation)
  - Error handling and sensor failure detection
  - Integration with evaluation boards (EVKs)
- **Hardware Assistance** (Secondary):
  - Assist hardware team with development
  - Prepare test and demonstration software for hardware validation

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

- ✅ **Analysis (10 marks)**: 
  - Problem statement with computational justification
  - Multiple stakeholders identified (hardware team, end users, teacher, examiners)
  - Research plan: 5+ similar solutions (commercial sensor boards, open source projects, visualization platforms)
  - Requirements specification with measurable success criteria
  - Hardware/software requirements (Python, MQTT, Prometheus, Grafana)
- ✅ **Design (15 marks)**: 
  - System decomposition (sensor drivers → data processing → MQTT → Prometheus → Grafana)
  - Algorithm design (sensor communication, data processing, MQTT, Prometheus integration)
  - Data structures (time-series data, sensor data buffering)
  - Test plans (iterative and post-development)
- ✅ **Development (25 marks)**: 
  - **Primary Focus**: Software development (sensor drivers, MQTT, Prometheus, Grafana)
  - Substantial Python programming demonstrating A Level skills
  - Iterative development approach
  - Team collaboration (hardware team, software lead)
  - Version control (Git) with evidence throughout
- ✅ **Evaluation (20 marks)**: 
  - Measurable success criteria (sensor accuracy, latency, reliability)
  - Stakeholder feedback (hardware team, end users)
  - Performance analysis (sensor reading rates, data transmission, visualization latency)
  - Limitations and future development

---

## Why Suitable for A Level

1. **Appropriate Complexity**: Sensor protocols, network programming, web development
2. **Programming Skills**: Hardware communication, MQTT, web apps, data structures
3. **Real-World**: Professional engineering project with commercial viability
4. **Sufficient Scope**: Multiple sensors, multiple software components
5. **Beyond GCSE**: Hardware-software integration, professional practices

---

## Research Plan

### OCR Requirement: Research 5+ Similar Solutions

The Analysis section requires research into at least 5 existing similar solutions. Research will cover:

1. **Commercial Sensor Boards** (2-3 solutions):
   - Arduino sensor shields and libraries (BME680, CO2 sensors)
   - Raspberry Pi sensor HATs (Enviro+, Sense HAT)
   - Commercial environmental monitoring systems (Airthings, PurpleAir)

2. **Open Source Projects** (2-3 solutions):
   - Home Assistant sensor integrations
   - ESPHome/ESP32 MQTT sensor projects
   - Open source sensor driver implementations

3. **Data Visualization Solutions** (1-2 solutions):
   - Grafana sensor dashboards and configurations
   - Prometheus + Grafana monitoring setups
   - Other IoT visualization platforms

**Research Methodology**:
- Analyze architecture, technologies, strengths, weaknesses
- Gather screenshots, diagrams, code examples
- Get stakeholder feedback on solutions
- Justify our approach based on research findings
- Link research to requirements specification

**Timeline**: Weeks 1-2 (Analysis phase)

*See `RESEARCH_PLAN_DETAILED.md` for comprehensive research plan.*

---

## Notes for Teacher

**Questions to Confirm**:
- [ ] OCR submission format requirements (Word? PDF? Template?)
- [ ] Specific deadlines and checkpoints
- [ ] Teacher's expected involvement and meeting schedule
- [ ] Any additional requirements or sections needed

**Current Status**:
- Using OCR template format for now
- Will update based on teacher feedback

---

## Approval

**Student Signature**: _________________________ **Date**: _______________

**Teacher Approval**: _________________________ **Date**: _______________

**Teacher Comments**:

_______________________________________________________________________

_______________________________________________________________________

_______________________________________________________________________

---

*This proposal is based on team meeting decisions and OCR requirements. Will be updated based on teacher feedback.*

# OCR A Level Computer Science H446 - Project Proposal

**Student Name**: Anthony Lennon  
**Candidate Number**: [To be filled in]  
**Centre Number**: [To be filled in]  
**Date**: January 2026  
**Project Title**: [See below]

---

## Project Title

**Environmental Sensor Board Software System**

*Alternative titles to consider:*
- Multi-Sensor Environmental Monitoring System
- IoT Sensor Data Acquisition and Visualization Platform
- Real-Time Environmental Sensor Integration and Web Interface

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

### Primary Stakeholders

1. **Hardware Team** (Michael Hull, Ollie Hull)
   - Role: Designing and manufacturing the sensor board hardware
   - Interest: Ensuring software integrates correctly with hardware, meeting technical specifications
   - Involvement: Providing hardware specifications, testing integration, providing feedback

2. **Software Lead** (Alex Lennon)
   - Role: Software architecture, mentoring, code review
   - Interest: Ensuring professional software development practices, educational value
   - Involvement: Technical guidance, code review, project management

3. **End Users** (Councils, Companies, Governments)
   - Role: Future customers/users of the sensor board system
   - Interest: Reliable, accurate environmental monitoring, easy-to-use interface
   - Involvement: Requirements definition, usability testing (if applicable)

4. **Computer Science Teacher**
   - Role: Project supervisor, OCR assessment
   - Interest: Ensuring project meets OCR requirements, educational value
   - Involvement: Project approval, progress reviews, assessment guidance

5. **OCR Examiners**
   - Role: Assessment evaluators
   - Interest: Evaluating against OCR A Level Computer Science H446 criteria
   - Involvement: Final assessment

### Secondary Stakeholders

- **Anthony Lennon** (Student Developer): Learning software engineering, achieving good marks
- **Business**: Product portfolio expansion, commercial viability

---

## Success Criteria

### Functional Success Criteria (Measurable)

1. **Sensor Integration**
   - ✅ System successfully reads data from BME 690 gas sensor with accuracy within manufacturer specifications
   - ✅ System successfully reads data from particulate sensor with accuracy within manufacturer specifications
   - ✅ System successfully reads data from CO2 sensor with accuracy within manufacturer specifications
   - ✅ All sensors can be read simultaneously without interference

2. **Data Communication**
   - ✅ Sensor data is transmitted via MQTT protocol with <1% packet loss
   - ✅ Data transmission latency is <100ms from sensor read to MQTT publish
   - ✅ System handles network disconnections gracefully and reconnects automatically

3. **Web Interface**
   - ✅ Web interface displays real-time sensor data with <2 second update latency
   - ✅ Historical data can be retrieved and displayed for at least 30 days
   - ✅ Interface is accessible and functional on modern web browsers (Chrome, Firefox, Safari)

4. **Error Handling**
   - ✅ System detects sensor failures and reports errors within 5 seconds
   - ✅ System continues operating when one sensor fails (graceful degradation)
   - ✅ All error conditions are logged with timestamps and error codes

### Quality Success Criteria

1. **Code Quality**
   - ✅ Code test coverage is >80% for all sensor drivers
   - ✅ All public APIs are fully documented
   - ✅ Code follows consistent style guide and is maintainable

2. **Performance**
   - ✅ System can process sensor readings at minimum 1Hz (1 reading per second per sensor)
   - ✅ Web interface loads in <3 seconds on standard broadband connection
   - ✅ System memory usage remains stable (no memory leaks over 24-hour operation)

### Educational Success Criteria

1. **OCR Assessment**
   - ✅ Achieve marks in upper bands for all four assessment sections (Analysis, Design, Development, Evaluation)
   - ✅ Demonstrate A Level programming skills (beyond GCSE standard)
   - ✅ Show evidence of iterative development and testing

2. **Learning Objectives**
   - ✅ Demonstrate understanding of hardware-software integration
   - ✅ Show proficiency in sensor communication protocols (I2C/SPI)
   - ✅ Implement and use MQTT protocol effectively
   - ✅ Create functional web interface for data visualization
   - ✅ Use version control (Git) effectively throughout project

---

## Technical Approach

### Programming Language

**Python** (recommended)
- Excellent libraries for sensor communication (RPi.GPIO, smbus for I2C)
- Strong support for MQTT (paho-mqtt library)
- Good for web development (Flask/FastAPI for backend)
- Easy to demonstrate programming skills
- Widely used in IoT and sensor projects

### Technology Stack

- **Sensor Communication**: Python with I2C/SPI libraries
- **MQTT**: paho-mqtt Python library
- **Web Backend**: Flask or FastAPI (Python)
- **Web Frontend**: HTML, CSS, JavaScript (with charting library like Chart.js)
- **Data Storage**: SQLite or JSON files (for historical data)
- **Version Control**: Git
- **Testing**: pytest (Python testing framework)

### Development Approach

- **Iterative Development**: Start with one sensor, add others incrementally
- **Evaluation Boards**: Begin with Bosch evaluation boards (EVKs) immediately
- **Parallel Development**: Software development proceeds while hardware design is in progress
- **Team Collaboration**: Work as part of professional engineering team

---

## Project Scope

### In Scope

- Development of sensor drivers for BME 690, particulate, and CO2 sensors
- Implementation of MQTT communication protocol
- Creation of web interface for real-time data visualization
- Data logging and historical data retrieval
- Error handling and sensor failure detection
- Integration with hardware evaluation boards
- Testing and validation of all components

### Out of Scope

- Hardware design and manufacturing (handled by hardware team)
- Advanced AI/ML for gas sensor learning (future enhancement)
- Mobile application development
- Cloud infrastructure setup (local/web server only)
- Production deployment and scaling

### Limitations

1. **Hardware Dependency**: Software development depends on availability of evaluation boards
   - *Justification*: Hardware design takes 6+ weeks; using EVKs allows immediate software development

2. **Sensor Learning Features**: Advanced AI-based gas sensor learning will not be implemented
   - *Justification*: Requires significant ML expertise and training data; beyond scope for initial implementation

3. **Multi-board Coordination**: System will focus on single board, not multiple board coordination
   - *Justification*: Adds significant complexity; single board provides sufficient scope for A Level project

---

## Resources Required

### Hardware

- Bosch BME 690 evaluation board (gas sensor)
- Bosch particulate sensor evaluation board
- Bosch CO2 sensor evaluation board
- Development computer/laptop
- Network connection for MQTT testing

### Software

- Python 3.x development environment
- Git for version control
- Code editor/IDE (VS Code, PyCharm, or similar)
- MQTT broker (Mosquitto or cloud-based)
- Web browser for testing

### Support

- Hardware team (Michael Hull, Ollie Hull) for hardware specifications and integration testing
- Software mentor (Alex Lennon) for technical guidance and code review
- Computer Science teacher for project supervision and OCR guidance

---

## Timeline

### Phase 1: Analysis (Weeks 1-2)
- Research existing sensor solutions (5+ similar systems)
- Stakeholder meetings
- Requirements specification
- Success criteria definition
- Hardware/software requirements

### Phase 2: Design (Weeks 3-4)
- System decomposition
- Algorithm design (sensor drivers, data processing, MQTT, web interface)
- Data structure design
- Test plans
- GUI/wireframe design for web interface

### Phase 3: Development (Weeks 5-10)
- Week 5-6: Core sensor driver development (start with one sensor)
- Week 7-8: MQTT implementation and additional sensors
- Week 9-10: Web interface development and integration
- Continuous: Testing, iteration, documentation

### Phase 4: Testing & Refinement (Weeks 11-12)
- Comprehensive testing
- Integration testing with hardware team
- Bug fixes and performance optimization
- Documentation completion

### Phase 5: Evaluation (Weeks 13-14)
- Evaluation against success criteria
- Stakeholder feedback
- Performance analysis
- Final documentation and reflection

**Project Duration**: Until end of 2026 (approximately 10-12 months)

---

## OCR Assessment Alignment

### Analysis Section (10 marks)
- ✅ Clear problem statement with computational justification
- ✅ Multiple stakeholders identified (hardware team, end users, teacher, examiners)
- ✅ Research plan: 5+ similar sensor solutions to analyze
- ✅ Requirements specification with measurable success criteria
- ✅ Hardware/software requirements identified

### Design Section (15 marks)
- ✅ System decomposition (sensor drivers → data processing → MQTT → web interface)
- ✅ Algorithm design required (sensor communication, data processing, MQTT, web backend)
- ✅ Data structures (buffering sensor data, data logging)
- ✅ Test plans (iterative and post-development)
- ✅ All design decisions will be justified

### Development Section (25 marks)
- ✅ Substantial programming work (sensor drivers, MQTT, web interface)
- ✅ High-level programming language (Python)
- ✅ Iterative development approach
- ✅ Team collaboration (professional engineering team)
- ✅ Version control (Git)
- ✅ Evidence recording throughout development

### Evaluation Section (20 marks)
- ✅ Measurable success criteria defined
- ✅ Stakeholder feedback planned (hardware team, end users)
- ✅ Performance metrics defined (accuracy, latency, reliability)
- ✅ Limitations identified and justified
- ✅ Future development opportunities identified

---

## Why This Project is Suitable for A Level

1. **Appropriate Complexity**: 
   - Requires sensor communication protocols (I2C/SPI)
   - Network programming (MQTT)
   - Web development (backend and frontend)
   - Data processing and visualization
   - Error handling and robustness

2. **Demonstrates Programming Skills**:
   - Low-level hardware communication
   - Network protocol implementation
   - Web application development
   - Data structures and algorithms
   - Software engineering practices

3. **Real-World Application**:
   - Professional engineering project
   - Commercial viability
   - Team collaboration
   - Industry-standard technologies

4. **Sufficient Scope**:
   - Multiple sensors (3+)
   - Multiple software components (drivers, communication, web interface)
   - Integration challenges
   - Testing requirements

5. **Beyond GCSE Level**:
   - Hardware-software integration
   - Network programming
   - Professional development practices
   - Team collaboration
   - Real-world constraints

---

## Risk Assessment

### Technical Risks

1. **Hardware Availability**: Evaluation boards may be delayed
   - *Mitigation*: Order immediately, have backup plan for software-only development initially

2. **Sensor Integration Complexity**: Sensors may be more complex than expected
   - *Mitigation*: Start with one sensor, iterate, use manufacturer documentation and support

3. **MQTT Communication Issues**: Network or protocol problems
   - *Mitigation*: Use well-established libraries, test early, have fallback to local storage

### Project Risks

1. **Timeline**: Project may take longer than expected
   - *Mitigation*: Start immediately, work iteratively, prioritize core features

2. **Scope Creep**: Adding too many features
   - *Mitigation*: Clear scope definition, focus on core requirements first

### Educational Risks

1. **Complexity**: Project may be too challenging
   - *Mitigation*: Professional team support, iterative approach, mentor guidance

2. **OCR Requirements**: May not meet all requirements
   - *Mitigation*: Regular reviews against OCR criteria, teacher guidance

---

## Expected Outcomes

### Technical Outcomes

- Working sensor driver software for BME 690, particulate, and CO2 sensors
- Functional MQTT communication system
- Interactive web interface for real-time data visualization
- Comprehensive test suite
- Complete documentation

### Educational Outcomes

- Strong OCR A Level Computer Science project assessment
- Demonstrated programming skills at A Level standard
- Understanding of hardware-software integration
- Experience with professional software development practices
- Team collaboration skills

### Business Outcomes

- Reusable sensor driver libraries for future projects
- Foundation for commercial sensor board product
- Knowledge and experience in environmental sensor technology

---

## Approval

I confirm that:
- This project is my own work
- I have access to the required resources
- The project scope is appropriate for A Level Computer Science
- I understand the OCR assessment requirements
- I will work with my team and supervisor throughout the project

**Student Signature**: _________________________ **Date**: _______________

**Teacher Approval**: _________________________ **Date**: _______________

**Teacher Comments**:

_______________________________________________________________________

_______________________________________________________________________

_______________________________________________________________________

---

## Appendix: Project Proposal Checklist

Before submitting, ensure:

- [ ] Project title is clear and descriptive
- [ ] Problem statement explains why computational solution is needed
- [ ] Stakeholders are identified (avoid friends, yourself, CS teacher)
- [ ] Success criteria are measurable (not vague)
- [ ] Technical approach is defined (language, tools, methods)
- [ ] Scope is clear (in scope vs out of scope)
- [ ] Limitations are identified and justified
- [ ] Resources are available
- [ ] Timeline is realistic
- [ ] Project demonstrates A Level programming skills
- [ ] Project goes beyond GCSE level
- [ ] OCR requirements are addressed
- [ ] Teacher has reviewed and approved

---

**Document Version**: 1.0  
**Last Updated**: January 2026  
**Next Review**: After teacher feedback

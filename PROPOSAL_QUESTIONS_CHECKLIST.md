# Project Proposal - Questions to Answer Before Submission

This checklist identifies questions that need to be answered to complete the project proposal for teacher approval.

---

## Critical Questions (Must Answer Before Submission)

### 1. Programming Language ✅/❌
- **Question**: What programming language will be used?
- **Status**: Python recommended, but not finalized
- **Action Needed**: Confirm Python as final choice
- **Impact**: Required for technical approach section
- **Who**: Alex & Anthony to decide

### 2. Specific Sensor Models/Part Numbers ❌
- **Question**: What are the exact Bosch sensor model numbers and part numbers?
  - BME 690 gas sensor - exact model?
  - Particulate sensor - exact model number?
  - CO2 sensor - exact model number?
- **Status**: Generic names used, need specifics
- **Action Needed**: Get exact model numbers from Michael/Ollie or Bosch datasheets
- **Impact**: Required for hardware requirements section
- **Who**: Michael/Ollie to provide

### 3. MQTT Broker Setup ❌
- **Question**: What MQTT broker will be used?
  - Local broker (Mosquitto on local machine)?
  - Cloud broker (HiveMQ, AWS IoT, etc.)?
  - Self-hosted server?
- **Status**: Not determined
- **Action Needed**: Decide on MQTT broker approach
- **Impact**: Required for technical approach and resources
- **Who**: Alex & Anthony to decide

### 4. Web Interface Technology Stack ❌
- **Question**: Specific web technology choices?
  - Backend: Flask or FastAPI? (both mentioned)
  - Frontend: Plain JavaScript or framework (React, Vue)?
  - Charting library: Chart.js, D3.js, or other?
- **Status**: Generic mention, need specifics
- **Action Needed**: Finalize web stack choices
- **Impact**: Required for technical approach
- **Who**: Alex & Anthony to decide

### 5. Data Storage Approach ❌
- **Question**: How will historical data be stored?
  - SQLite database?
  - JSON files?
  - Both?
  - What retention period?
- **Status**: Mentioned but not specified
- **Action Needed**: Define data storage strategy
- **Impact**: Required for design and scope
- **Who**: Alex & Anthony to decide

### 6. Development Environment ❌
- **Question**: What development environment/IDE?
  - VS Code?
  - PyCharm?
  - Other?
- **Status**: Not specified
- **Action Needed**: Choose IDE
- **Impact**: Required for resources section
- **Who**: Anthony & Alex to decide

### 7. Testing Framework ❌
- **Question**: What testing framework?
  - pytest (mentioned)?
  - unittest?
  - Other?
- **Status**: pytest mentioned but not confirmed
- **Action Needed**: Confirm testing framework
- **Impact**: Required for technical approach
- **Who**: Alex & Anthony to decide

### 8. Anthony's Specific Work Breakdown ❌
- **Question**: Exactly what will Anthony develop vs what Alex will develop?
  - Which sensors will Anthony work on?
  - Will Anthony do MQTT implementation?
  - Will Anthony do web interface?
  - What will be mentor-supported vs independent?
- **Status**: General description, need specifics
- **Action Needed**: Define detailed work breakdown
- **Impact**: Required for OCR assessment (must show Anthony's work)
- **Who**: Alex & Anthony to define

### 9. Research Plan - Specific Solutions ❌
- **Question**: Which 5+ similar solutions will be researched?
  - Arduino sensor libraries?
  - Commercial sensor boards (which ones)?
  - Open-source projects (which ones)?
  - Academic papers?
- **Status**: Generic mention, need specific list
- **Action Needed**: Create research plan with specific solutions
- **Impact**: Required for Analysis section (OCR requirement)
- **Who**: Anthony to research with guidance

### 10. Use Cases/Examples ❌
- **Question**: Specific use case examples for the proposal?
  - Classroom CO2 monitoring (mentioned in meeting)
  - Liverpool docks pollution monitoring (mentioned)
  - Others?
- **Status**: Mentioned in meeting but not in proposal
- **Action Needed**: Add specific use case examples
- **Impact**: Strengthens problem statement
- **Who**: Team to define

---

## Important Questions (Should Answer Soon)

### 11. Hardware Platform ❌
- **Question**: What platform will run the software?
  - Raspberry Pi?
  - Linux computer?
  - Windows?
  - Embedded microcontroller?
- **Status**: Not specified
- **Action Needed**: Define target platform
- **Impact**: Affects development approach
- **Who**: Team to decide

### 12. Communication Protocol Details ❌
- **Question**: Specific I2C/SPI details?
  - Which sensors use I2C vs SPI?
  - What bus speeds?
  - Any protocol-specific requirements?
- **Status**: Generic mention
- **Action Needed**: Get protocol details from sensor datasheets
- **Impact**: Technical accuracy
- **Who**: Michael/Ollie or sensor datasheets

### 13. Success Criteria - Manufacturer Specifications ❌
- **Question**: What are the actual manufacturer accuracy specifications?
  - BME 690 accuracy specs?
  - Particulate sensor accuracy specs?
  - CO2 sensor accuracy specs?
- **Status**: "Within manufacturer specifications" is vague
- **Action Needed**: Get actual specs from datasheets
- **Impact**: Success criteria must be measurable
- **Who**: Michael/Ollie or datasheets

### 14. Timeline - Specific Dates ❌
- **Question**: What are the actual milestone dates?
  - When does Analysis phase start/end?
  - When does Design phase start/end?
  - When is OCR submission deadline?
- **Status**: Generic "weeks 1-2" format
- **Action Needed**: Convert to actual dates
- **Impact**: Realistic timeline
- **Who**: Alex & Anthony with teacher

### 15. Teacher-Specific Requirements ❌
- **Question**: Does the teacher have specific requirements?
  - Format preferences?
  - Additional sections needed?
  - Specific questions to answer?
  - Word count limits?
- **Status**: Unknown
- **Action Needed**: Check with teacher
- **Impact**: Proposal format
- **Who**: Anthony to ask teacher

---

## Nice-to-Have Questions (Can Answer Later)

### 16. Hardware Involvement Details ❌
- **Question**: How will Anthony be involved in hardware?
  - Review schematics?
  - Testing?
  - Documentation?
- **Status**: Michael said "still not quite sure"
- **Action Needed**: Define hardware involvement
- **Impact**: Team collaboration evidence
- **Who**: Michael & Alex to decide

### 17. Version Control Workflow ❌
- **Question**: Specific Git workflow?
  - Branching strategy?
  - Code review process?
  - Commit message format?
- **Status**: Git mentioned but workflow not defined
- **Action Needed**: Define workflow
- **Impact**: Development process
- **Who**: Alex to define

### 18. Documentation Tools ❌
- **Question**: Documentation approach?
  - Markdown (current)?
  - Word document?
  - LaTeX?
  - OCR-specific format?
- **Status**: Using Markdown, but need to confirm OCR format
- **Action Needed**: Check OCR submission format requirements
- **Impact**: Documentation format
- **Who**: Anthony to check with teacher

### 19. Deployment/Testing Environment ❌
- **Question**: Where will system be tested/deployed?
  - Local development only?
  - Test server?
  - Cloud deployment?
- **Status**: Not specified
- **Action Needed**: Define testing environment
- **Impact**: Testing strategy
- **Who**: Team to decide

### 20. Performance Benchmarks ❌
- **Question**: Are the performance targets realistic?
  - <100ms MQTT latency - achievable?
  - <2 second web update - achievable?
  - 1Hz sensor reading - sufficient?
- **Status**: Targets set but not validated
- **Action Needed**: Validate targets are realistic
- **Impact**: Success criteria credibility
- **Who**: Alex to validate

---

## Questions for Teacher

### 21. OCR Submission Format ❌
- **Question**: What format does OCR require for submission?
  - Word document?
  - PDF?
  - Specific template?
- **Action Needed**: Ask teacher
- **Who**: Anthony

### 22. Assessment Timeline ❌
- **Question**: What are the OCR assessment deadlines?
  - When is final submission?
  - Are there intermediate checkpoints?
- **Action Needed**: Get from teacher
- **Who**: Anthony

### 23. Teacher's Role ❌
- **Question**: What is the teacher's expected involvement?
  - How often to meet?
  - What feedback to expect?
  - What approvals needed?
- **Action Needed**: Clarify with teacher
- **Who**: Anthony

### 24. Team Collaboration Evidence ❌
- **Question**: How should team collaboration be documented for OCR?
  - Meeting notes?
  - Code review evidence?
  - Communication logs?
- **Action Needed**: Check with teacher
- **Who**: Anthony

---

## Questions for Hardware Team

### 25. EVK Availability ❌
- **Question**: When will evaluation boards be available?
  - Already have some?
  - Need to order?
  - Delivery timeline?
- **Action Needed**: Confirm with Michael
- **Who**: Michael to confirm

### 26. Sensor Datasheets ❌
- **Question**: Can we get sensor datasheets?
  - Technical specifications
  - Communication protocols
  - Example code
- **Action Needed**: Request from Michael/Ollie
- **Who**: Michael/Ollie to provide

### 27. Hardware Integration Timeline ❌
- **Question**: When will custom hardware be ready for integration?
  - 6 weeks minimum?
  - More specific timeline?
- **Action Needed**: Get timeline from hardware team
- **Who**: Michael/Ollie

---

## Priority Action Items

### Before Proposal Submission (Jan 29)

**Must Answer**:
1. ✅ Confirm Python as programming language
2. ✅ Get exact sensor model numbers
3. ✅ Define MQTT broker approach
4. ✅ Finalize web technology stack
5. ✅ Define data storage approach
6. ✅ Define Anthony's specific work breakdown
7. ✅ Create research plan with 5+ specific solutions
8. ✅ Add specific use case examples
9. ✅ Check teacher-specific requirements
10. ✅ Get OCR submission format requirements

**Should Answer**:
11. Define target hardware platform
12. Get manufacturer accuracy specifications
13. Convert timeline to actual dates
14. Define development environment

### After Proposal Approval

**Can Answer Later**:
- Hardware involvement details
- Version control workflow
- Deployment environment
- Performance validation

---

## Quick Decision Guide

### For Technical Decisions (Alex & Anthony)
- **Programming Language**: Python (recommended, easy decision)
- **MQTT Broker**: Start with local Mosquitto, can move to cloud later
- **Web Stack**: Flask (simpler) or FastAPI (more modern) - recommend Flask for simplicity
- **Data Storage**: SQLite (simple, sufficient for project)
- **Testing**: pytest (standard for Python)
- **IDE**: VS Code (free, widely used, good for Python)

### For Hardware Details (Michael/Ollie)
- Request: Sensor model numbers, datasheets, EVK availability timeline

### For Teacher (Anthony)
- Request: OCR format requirements, submission deadlines, involvement expectations

---

## Next Steps

1. **This Week**: Answer critical questions (1-10)
2. **Before Jan 29**: Complete proposal with all critical answers
3. **Submit**: Get teacher approval
4. **After Approval**: Answer remaining questions as project progresses

---

**Status**: 10 critical questions need answers before submission  
**Deadline**: January 29, 2026  
**Priority**: Focus on critical questions first

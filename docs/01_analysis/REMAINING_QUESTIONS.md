# Remaining Questions to Answer

**Last Updated**: January 2026  
**Status**: After EVK receipt

---

## ✅ Answered Questions

1. ✅ **Programming Language**: Python
2. ✅ **MQTT Broker**: Mosquitto (local, can move to cloud later)
3. ✅ **Web Visualization**: Grafana
4. ✅ **Data Storage**: Prometheus
5. ✅ **Development Environment**: VS Code (with Cursor where allowed)
6. ✅ **Testing Framework**: pytest
7. ✅ **Anthony's Work**: Software focus (OCR), assists hardware, test/demo software
8. ✅ **Research Plan**: Detailed plan created (5+ solutions)
9. ✅ **Use Cases**: Classroom CO2, vaping, burning, presence, docks pollution
10. ✅ **BME 690 Sensor**: Received - BMV080 Shuttle Board (SPN: 0273.SB0.000)
11. ✅ **Application Board**: Received - Application Board 3.1 (PN: 0440.AB0.211)

---

## ❌ Critical Questions Still Open

### 1. Remaining Sensor Model Numbers
- **Question**: What are the exact model numbers for:
  - Particulate sensor (not yet received)
  - CO2 sensor (not yet received)
- **Status**: BME 690 received, others pending
- **Action**: Get from Michael/Ollie or Bosch when ordering
- **Impact**: Hardware requirements section
- **Who**: Michael/Ollie

### 2. Teacher Requirements (Anthony to Ask)
- **Question**: 
  - OCR submission format? (Word/PDF/template)
  - Specific deadlines and checkpoints?
  - Expected involvement/meeting schedule?
  - Any additional requirements?
- **Status**: Template format used for now
- **Action**: Anthony to ask teacher
- **Impact**: Proposal format, timeline
- **Who**: Anthony

### 3. Hardware Platform
- **Question**: What platform will run the software?
  - Raspberry Pi?
  - Linux computer/laptop?
  - Windows?
  - The Application Board 3.1 itself?
- **Status**: Not specified
- **Action**: Define target platform
- **Impact**: Development approach, setup instructions
- **Who**: Alex & Anthony to decide
- **Note**: Application Board 3.1 may have its own processor - need to check

### 4. Development Environment/IDE ✅
- **Question**: What IDE/editor?
  - VS Code?
  - PyCharm?
  - Other?
- **Status**: ✅ **ANSWERED** - VS Code (with Cursor where allowed)
- **Action**: ✅ Complete
- **Impact**: Resources section, setup guide
- **Who**: ✅ Decided

### 5. Testing Framework ✅
- **Question**: What testing framework?
  - pytest?
  - unittest?
  - Other?
- **Status**: ✅ **ANSWERED** - pytest (Python testing framework)
- **Action**: ✅ Complete
- **Impact**: Technical approach
- **Who**: ✅ Decided

### 6. Timeline with Actual Dates
- **Question**: Convert "weeks 1-2" to actual dates
  - When does Analysis phase start/end?
  - When does Design phase start/end?
  - When is OCR submission deadline?
- **Status**: Generic timeline format
- **Action**: Get OCR deadlines from teacher, create actual dates
- **Impact**: Realistic planning
- **Who**: Anthony (get from teacher) + Alex (create timeline)

### 7. Manufacturer Accuracy Specifications
- **Question**: Actual accuracy specs for:
  - BME 690 sensor (need datasheet)
  - Particulate sensor (when model known)
  - CO2 sensor (when model known)
- **Status**: "Within manufacturer specifications" is too vague
- **Action**: Get datasheets, extract accuracy specs
- **Impact**: Success criteria must be measurable
- **Who**: Michael/Ollie or find datasheets online
- **Note**: Can start with BME 690 now that we have the model

### 8. Communication Protocol Details
- **Question**: I2C/SPI details
  - Which sensors use I2C vs SPI?
  - What bus speeds?
  - Protocol-specific requirements?
- **Status**: Generic mention
- **Action**: Get from sensor datasheets
- **Impact**: Technical accuracy, driver development
- **Who**: Datasheets or Michael/Ollie
- **Note**: Can research Application Board 3.1 documentation

### 9. Anthony's Detailed Work Breakdown
- **Question**: Specific breakdown:
  - Which sensors will Anthony develop drivers for? (All 3? Start with BME 690?)
  - Will Anthony implement MQTT client?
  - Will Anthony configure Prometheus integration?
  - Will Anthony configure Grafana dashboards?
  - What is mentor-supported vs independent work?
- **Status**: General description
- **Action**: Define detailed breakdown
- **Impact**: OCR assessment (must show Anthony's work clearly)
- **Who**: Alex & Anthony to define
- **Recommendation**: Start with BME 690 driver (independent), then add others

### 10. MQTT Broker - Specific Choice ✅
- **Question**: Which specific broker?
  - Cloud: HiveMQ Cloud? AWS IoT? Other?
  - Self-hosted: Mosquitto? Where hosted?
- **Status**: ✅ **ANSWERED** - Mosquitto (local broker, can move to cloud later)
- **Action**: ✅ Complete
- **Impact**: Setup instructions, resources
- **Who**: ✅ Decided

---

## ⚠️ Important Questions (Should Answer Soon)

### 11. Prometheus Setup Details
- **Question**: 
  - Local Prometheus server?
  - Cloud Prometheus (Grafana Cloud)?
  - Retention period?
  - Data collection interval?
- **Status**: Prometheus chosen but setup not specified
- **Action**: Define Prometheus setup
- **Impact**: Architecture and setup
- **Who**: Alex & Anthony

### 12. Grafana Configuration
- **Question**:
  - Local Grafana instance?
  - Grafana Cloud?
  - What dashboards to create?
  - Data source configuration?
- **Status**: Grafana chosen but configuration not specified
- **Action**: Define Grafana setup
- **Impact**: Visualization approach
- **Who**: Alex & Anthony

### 13. Application Board 3.1 Capabilities
- **Question**: 
  - Does it have its own processor?
  - What OS does it run?
  - How do we program it?
  - USB connection details?
- **Status**: Received but capabilities not researched
- **Action**: Review Application Board 3.1 documentation
- **Impact**: Development approach
- **Who**: Anthony & Alex to research

### 14. Sensor Integration Order
- **Question**: Which sensor to start with?
  - BME 690 (received) - obvious first choice?
  - Or start with simpler sensor?
- **Status**: BME 690 received, others pending
- **Action**: Decide development order
- **Impact**: Development plan
- **Who**: Alex & Anthony
- **Recommendation**: Start with BME 690 since it's received

---

## 📋 Nice-to-Have Questions (Can Answer Later)

### 15. Version Control Workflow
- Git branching strategy?
- Code review process?
- Commit message format?

### 16. Documentation Format
- OCR submission format (Word/PDF)?
- Markdown for development, convert later?

### 17. Deployment/Testing Environment
- Local development only?
- Test server?
- Cloud deployment?

### 18. Performance Validation
- Are performance targets realistic?
- Need to validate benchmarks?

---

## 🎯 Priority Action Items

### Before Proposal Submission (Jan 29)

**Must Answer**:
1. ❌ Teacher questions (submission format, deadlines) - **Anthony to ask**
2. ⚠️ Hardware platform (what runs software?) - **Alex & Anthony**
3. ✅ Development environment (IDE) - **ANSWERED: VS Code with Cursor**
4. ✅ Testing framework - **ANSWERED: pytest**
5. ✅ MQTT broker specific choice - **ANSWERED: Mosquitto**

**Should Answer**:
6. ⚠️ Timeline with actual dates - **Need OCR deadlines from teacher**
7. ⚠️ Application Board 3.1 capabilities - **Research documentation**

**Can Wait**:
- Remaining sensor model numbers (when received)
- Manufacturer specs (when datasheets available)
- Detailed work breakdown (can refine during development)

---

## 💡 Quick Recommendations

For fast progress, recommend:
- **IDE**: VS Code (free, excellent Python support)
- **Testing**: pytest (standard, well-documented)
- **MQTT**: Start with local Mosquitto (easy setup), can move to cloud later
- **Hardware Platform**: Research Application Board 3.1 - likely has its own processor
- **Development Order**: Start with BME 690 (received), add others as they arrive

---

## 📝 Next Steps

1. **This Week**:
   - Anthony: Ask teacher all questions
   - Alex & Anthony: Decide on IDE, testing framework, MQTT broker
   - Research: Application Board 3.1 documentation

2. **Before Jan 29**:
   - Complete proposal with all critical answers
   - Get teacher approval

3. **After Approval**:
   - Answer remaining questions as project progresses
   - Get remaining sensor model numbers when available

---

**Status**: 10 critical questions remain, 5 can be quick decisions  
**Deadline**: January 29, 2026  
**Priority**: Focus on teacher questions and quick technical decisions

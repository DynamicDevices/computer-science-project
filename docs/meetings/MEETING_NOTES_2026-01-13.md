# Meeting Notes - Project Kickoff
**Date**: January 13, 2026  
**Attendees**: Michael Hull, Ollie Hull, Anthony Lennon, Alex Lennon  
**Duration**: ~48 minutes  
**Transcribed by**: Otter.ai

---

## Meeting Summary

Kickoff meeting to discuss sensor board project for Anthony's OCR A Level Computer Science project. Discussion covered hardware specifications, software approach, project timeline, and how to structure the work to meet both educational (OCR) and business objectives. Key decision: Start software development immediately using Bosch evaluation boards (EVKs) while hardware design proceeds in parallel.

---

## Key Decisions Made

### Hardware Decisions ✅
- **Sensors Selected**:
  - BME 690 gas sensor (latest version, can learn smells/compounds)
  - Particulate sensor (new, no fan required, smaller form factor)
  - CO2 sensor
  - Bosch application board (evaluation kit) as starting point
- **Board Design**: Custom board will include all sensors, can selectively populate during production
- **Communication**: MQTT protocol for data transmission
- **Display**: Web-based display (rather than local display) - "ship all the data off and have a really nice web page"
- **Hardware Timeline**: 6+ weeks minimum for design, schematic, layout, prototyping

### Software Decisions ✅
- **Architecture**: Software on both ends (sensor board + web interface)
- **Protocol**: MQTT for communication
- **Display**: Web page for visualization (better than local display for this project)
- **Development Approach**: Start immediately with evaluation boards (EVKs)
- **Language**: [To be determined - Python recommended for sensor projects]

### Project Approach ✅
- **Start Immediately**: Use Bosch evaluation boards to begin software development now
- **Parallel Development**: Hardware design proceeds in parallel (6+ weeks), software doesn't wait
- **Team Collaboration**: Anthony works as part of team (important for OCR requirements)
- **Real-World Project**: Professional hardware/software integration, not academic exercise
- **Reusability**: Build software/hardware libraries for future use

### Anthony's Work Assignment ✅
- **Primary Focus**: Software development
- **Starting Point**: Work with Bosch evaluation boards (EVKs)
- **Approach**: Part of team, not working in isolation
- **Complexity**: Real-world engineering project with professional standards
- **Hardware Involvement**: [To be determined - Michael mentioned finding way to involve Anthony]

### Timeline Decisions ✅
- **Project Idea Deadline**: January 29, 2026 (one-page document for teacher)
- **Project Duration**: Until end of year (but time goes quickly - need to start now)
- **Hardware Delivery**: 6+ weeks minimum for custom board
- **Software Start**: Immediate (using EVKs)

### Success Criteria ✅
- **Business**: Flexible sensor board for commercial use, reusable components
- **Educational**: Standout project demonstrating depth, real-world engineering
- **Technical**: Working sensor integration, MQTT communication, web display
- **Quality**: Professional standard (not "Noddy" academic project)

---

## Action Items

| Item | Owner | Deadline | Status | Notes |
|------|-------|----------|--------|-------|
| Order Bosch evaluation boards (EVKs) | Michael | ASAP | Pending | BME 690, particulate sensor, CO2 sensor - can use existing ones, may need to buy additional items |
| Create project idea one-pager | Alex & Anthony | Jan 29, 2026 | Pending | For computer science teacher approval |
| Set up WhatsApp group | Alex | ASAP | Pending | For team communication |
| Get EVK links/ordering info | Michael | ASAP | Pending | Share with Alex for ordering |
| Begin software development with EVKs | Anthony & Alex | Immediate | Pending | Start once EVKs available |
| Determine programming language | Alex & Anthony | Week 1 | Pending | Python recommended for sensors |
| Research MQTT implementation | Anthony & Alex | Week 1-2 | Pending | For data transmission |
| Plan web interface approach | Anthony & Alex | Week 2-3 | Pending | Web page for data display |
| Hardware design kickoff | Michael & Ollie | Week 1 | Pending | Schematic, layout, sensor selection |
| Determine Anthony's hardware involvement | Michael & Alex | Week 2-3 | Pending | Find way to involve Anthony in hardware |

---

## Discussion Points by Agenda Item

### 1. Hardware Specifications

**Sensors Discussed**:
- **BME 690 Gas Sensor**: Latest Bosch gas sensor, successor to Kelvin's sensor
  - Can learn smells/compounds (AI model training)
  - Use cases: Detect burning plastics, rodent droppings, vaping/smoking, fires before ignition
  - Has GUI software for learning smells
  - Can detect skin cancer (theoretically)
- **Particulate Sensor**: New Bosch sensor, no fan required (smaller than typical)
  - Use case: Air pollution monitoring (diesel emissions, dirty dock monitoring in Liverpool)
  - Can track pollution changes as ships move up/down Mersey
- **CO2 Sensor**: 
  - Use case: Monitor classroom CO2 levels, impact on learning/functioning
  - Educational relevance: "That's why your kids aren't learning"

**Board Design Philosophy**:
- Pack all sensors on board, selectively populate during production
- Flexible design for various customer needs
- Cost-effective for commercial use
- Reusable design blocks for future projects

**Hardware Development Process**:
- 6+ weeks minimum: Design → Schematic → Layout → Prototype
- Cost: $1000+ per prototype cycle
- Always expect rev 1.1 (never perfect first time)
- Test house costs: £1200/day for CE marking, emissions testing
- Design considerations: Filtering, emissions, enclosure design, certification

### 2. Software Requirements & Scope

**Software Architecture**:
- Two-part system: Sensor board software + Web interface
- Communication: MQTT protocol
- Display: Web page (better than local display for this project)
- Data flow: Sensors → Board → MQTT → Web display

**Development Approach**:
- Start with evaluation boards (EVKs) immediately
- Don't wait for custom hardware (6+ weeks)
- Software libraries become reusable assets
- Example: 4-port Ethernet switch took 10 days hardware + driver work, but now reusable in 10 minutes

**Software Development Philosophy**:
- Iterative: "I don't expect it to work, I test it, I iterate, I fix problems"
- Fast iteration cycles (unlike hardware)
- Test early, get feedback, improve continuously
- Work with hardware team for integration

### 3. Anthony's Work Assignment

**Primary Responsibilities**:
- Software development (sensor drivers, data processing, communication)
- Work with evaluation boards to start immediately
- Part of professional team (not isolated student project)
- Learn real-world engineering practices

**Learning Objectives**:
- Real-world software development
- Hardware-software integration
- Team collaboration
- Professional engineering practices
- Problem-solving and debugging

**Hardware Involvement**:
- Michael: "I'm still not quite sure how we pull you into that bit"
- Challenge: Hardware cycles are 6-8 weeks, expensive, can't iterate quickly
- Solution: Start with EVKs for software, find middle ground for hardware involvement
- Need to avoid requiring Anthony to do everything from scratch

**Advantages for Anthony**:
- Real-world project (not academic exercise)
- Professional team support
- Cutting-edge technology (sensors only 1 year old)
- Standout project: "Very few people are going to have this sort of team around you"
- Depth and quality: "This boy's gone in depth, he's invested time, he's invested effort"

### 4. Project Timeline & Approach

**Immediate Actions**:
- Get evaluation boards ordered/available
- Start software development with EVKs
- Create project idea one-pager (due Jan 29)

**Development Phases**:
- **Now**: Software development with EVKs
- **Parallel**: Hardware design (6+ weeks)
- **Integration**: When hardware ready, integrate with working software
- **Completion**: End of year (but time goes quickly)

**Critical Insight**:
- "If you wait until hardware is ready to start software, you'll be 6 weeks down the track and up against it"
- "The end will come so much more quickly than you are expecting"
- Start now, work in parallel

### 5. Technology & Tools

**Hardware**:
- Bosch application board (evaluation kit)
- BME 690, particulate sensor, CO2 sensor
- Sensors don't stack - work one at a time initially

**Software**:
- MQTT for communication
- Web interface for display
- [Programming language to be determined - Python recommended]

**Development Tools**:
- Evaluation boards for immediate start
- [IDE/development environment to be determined]

### 6. Business Context

**Commercial Value**:
- Environmental sensing is high priority for councils, companies, governments
- Flexible sensor board can solve various problems
- Reusable components reduce future development time/cost
- Cost-effective for volume production

**Reusability Philosophy**:
- 10 days of work becomes 10 minutes in future
- Build libraries (hardware + software) for reuse
- Target valuable components worth investing time in
- Example: Ethernet switch work now reusable forever

**Cost Considerations**:
- Low volume = expensive (setup costs, test house fees)
- High volume = cost-effective
- Never make just one board (make 5-10, costs similar)
- Always expect rev 1.1 (never perfect first time)

### 7. Educational Context

**OCR Requirements Alignment**:
- Team collaboration: "You can burn yourself into a team member, rather than just something working on their own"
- Real-world project: "This is how we do things, this is not a made up project"
- Depth and quality: Will stand out from typical student projects
- Professional standards: Not "Noddy" academic work

**Academic vs Real World**:
- Problem: "People doing the teaching are very divorced from the real world"
- Solution: Show real engineering practices
- Challenge: Academics "don't know what they don't know"
- Reality: Real engineering involves many considerations (CE marking, emissions, enclosures, etc.)

**Anthony's Education Path**:
- Currently: Maths, Physics, Computer Science A Levels
- Need: Good grades (A's, A*'s) for university
- Hardware engineering path: Physics + Maths A Level → University degree → Degree apprenticeship
- Reality: Most complex maths never used again, but need it to get degree

### 8. Risk Assessment

**Hardware Risks**:
- 6+ week cycles for fixes
- $1000+ per prototype
- Test house failures = expensive delays
- Emissions testing can fail in 15 minutes = wasted day (£1200)

**Software Risks**:
- If software doesn't work + hardware doesn't work = don't know which is wrong
- Solution: Get software working on EVKs first, then know it's hardware issue if problems

**Project Risks**:
- Time goes quickly ("it will be six months later, and it just disappears")
- Need to start immediately
- Don't wait for hardware

**Mitigation**:
- Start software now with EVKs
- Work in parallel (hardware + software)
- Get software working first, then integrate
- Narrow down problems quickly

### 9. Key Insights & Philosophy

**Engineering Approach**:
- "You don't know what you don't know" - key insight
- Real engineering: Define problems, reduce variables, test systematically
- Hardware: Must work first time (expensive to fix)
- Software: Iterate quickly, test continuously

**Team Collaboration**:
- Hardware team: Schematic, layout, certification, production
- Software team: Drivers, integration, testing, iteration
- Work together to create products
- Different approaches but complementary

**Technology Lifecycle**:
- Sensors: Latest technology (1 year old), top of range for 3+ years
- Development: 10s of millions spent by manufacturers, 10+ year lifecycle
- For us: Invest time once, reuse for 10-15 years
- Decision point: When next version significantly better, invest in new one

**Professional Standards**:
- Not "Noddy" academic projects
- Real-world constraints (cost, time, certification)
- Professional quality expected
- Reusable, maintainable solutions

---

## Open Questions

1. **Programming Language**: What language will Anthony use? (Python recommended for sensors)
2. **Hardware Involvement**: How will Anthony be involved in hardware design? (Michael: "I'm still not quite sure")
3. **Web Interface**: What technology stack for web display? (To be determined)
4. **MQTT Setup**: What MQTT broker/server approach? (To be determined)
5. **Sensor Priority**: Which sensor to start with? (Can work one at a time)
6. **Project Scope**: Exact features for OCR project? (To be refined in project idea)

---

## OCR Requirements Coverage Check

### Analysis Section (10 marks) ✅
- [x] **Problem Statement**: Environmental sensor board for commercial use + educational project
- [x] **Stakeholders Identified**: 
  - Hardware team (Michael, Ollie)
  - Software team (Alex, Anthony)
  - End users (councils, companies, governments)
  - Computer science teacher
  - OCR examiners
- [x] **Research Plan**: 
  - Research Bosch sensors (latest technology)
  - Research similar sensor boards
  - Research MQTT implementations
  - Research web interface approaches
- [ ] **Requirements Specification**: To be created (measurable success criteria needed)
- [ ] **Success Criteria**: To be defined (must be measurable)
- [x] **Hardware/Software Requirements**: Identified (Bosch sensors, MQTT, web interface)

### Design Section (15 marks) ⚠️
- [ ] **Decomposition**: To be created (sensor reading → data processing → MQTT → web display)
- [ ] **Algorithms**: To be designed (sensor drivers, data processing, communication)
- [ ] **Data Structures**: To be identified and justified
- [ ] **Test Plans**: To be created
- [ ] **Justifications**: All design decisions must be justified

### Development Section (25 marks) ✅
- [x] **Development Approach**: Iterative, start with EVKs
- [x] **Team Collaboration**: Anthony part of professional team
- [x] **Version Control**: Git (already set up)
- [ ] **Evidence Recording**: Plan needed (screenshots, code, testing)
- [ ] **Testing Strategy**: To be defined

### Evaluation Section (20 marks) ⚠️
- [ ] **Success Criteria**: Must be measurable (to be defined)
- [ ] **Stakeholder Feedback**: Plan for hardware team feedback
- [ ] **Performance Analysis**: Sensor accuracy, response time, etc.
- [ ] **Limitations**: To be identified honestly
- [ ] **Future Development**: Extensions and improvements

---

## Next Steps

### Immediate (This Week)
1. [ ] Michael: Share EVK ordering information/links
2. [ ] Alex: Set up WhatsApp group for team communication
3. [ ] Alex & Anthony: Begin project idea one-pager (due Jan 29)
4. [ ] Anthony: Review OCR requirements document
5. [ ] Team: Determine programming language (Python recommended)

### Short-term (Weeks 1-2)
1. [ ] Order and receive evaluation boards
2. [ ] Set up development environment
3. [ ] Begin software development with first sensor (BME 690 or particulate)
4. [ ] Research MQTT implementation
5. [ ] Create requirements specification with measurable success criteria
6. [ ] Begin Analysis phase documentation

### Medium-term (Weeks 3-4)
1. [ ] Complete Analysis phase documentation
2. [ ] Begin Design phase (decomposition, algorithms, data structures)
3. [ ] Continue software development
4. [ ] Hardware design kickoff (Michael & Ollie)
5. [ ] Determine Anthony's hardware involvement approach

---

## Key Quotes & Insights

> "If you wait until hardware is ready to start software, you'll be 6 weeks down the track and up against it"

> "This is how we do things. This is not a kind of a made up project and a made up way of doing things"

> "Very few people are going to have this sort of team around you"

> "This boy's gone in depth. He's invested time, he's invested effort. And I think it will make it stand out"

> "You don't know what you don't know" - Key engineering insight

> "I don't expect my software to work first time. We expect our hardware to work first time"

> "10 days of work becomes 10 minutes in the future" - Reusability value

---

## Next Meeting

**Date**: [To be scheduled]  
**Agenda**: 
- Review project idea one-pager
- EVK status and setup
- Programming language decision
- Requirements specification draft
- Development environment setup

---

## Notes

- **CO2 in room**: Joke about needing CO2 sensor to monitor meeting room!
- **Cutting-edge technology**: Sensors only 1 year old, latest and greatest
- **Professional standards**: This is real engineering, not academic exercise
- **Time management**: Critical to start now, time goes quickly
- **Team advantage**: Anthony has professional team support (rare for students)

---

**Meeting Notes Prepared By**: Alex Lennon  
**Date**: January 13, 2026  
**Next Review**: After project idea submission (Jan 29)

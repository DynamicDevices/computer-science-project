# Research Plan - Detailed Requirements

## OCR Requirement: Research at Least 5 Similar Solutions

The OCR Analysis section (10 marks) requires research into **at least 5 existing similar solutions**. This research must:
- Analyze existing systems that solve similar problems
- Include screenshots, diagrams, or explanations
- Analyze strengths and weaknesses
- Get stakeholder feedback on existing solutions
- Justify chosen approach based on research

---

## Research Categories

### Category 1: Commercial Sensor Boards (2-3 solutions)

Research existing commercial sensor boards that provide similar functionality:

#### 1.1 Arduino Sensor Shields/Libraries
- **What to research**: Arduino environmental sensor shields and libraries
- **Examples**:
  - Arduino BME680 library and shield
  - Arduino CO2 sensor modules (MH-Z19, SCD30)
  - Arduino particulate sensor modules (PMS5003)
- **What to analyze**:
  - How they implement sensor communication
  - Data processing approaches
  - Integration methods
  - Strengths: Easy to use, well-documented
  - Weaknesses: Limited to Arduino ecosystem, may not scale
- **Evidence needed**: Screenshots of libraries, code examples, documentation

#### 1.2 Raspberry Pi Sensor HATs
- **What to research**: Raspberry Pi sensor HATs and modules
- **Examples**:
  - Sense HAT (temperature, humidity, pressure)
  - Enviro+ (environmental monitoring)
  - Commercial CO2 monitoring solutions
- **What to analyze**:
  - Hardware integration approach
  - Software architecture
  - Data visualization methods
  - Strengths: Good integration, Python support
  - Weaknesses: Raspberry Pi specific, may be overkill for simple sensors
- **Evidence needed**: Product pages, documentation, example projects

#### 1.3 Commercial Environmental Monitoring Systems
- **What to research**: Commercial environmental monitoring solutions
- **Examples**:
  - Airthings (commercial air quality monitors)
  - PurpleAir (particulate monitoring)
  - Netatmo (home environmental monitoring)
- **What to analyze**:
  - System architecture
  - Data communication methods
  - User interfaces
  - Strengths: Professional, complete solutions
  - Weaknesses: Proprietary, expensive, may not be flexible
- **Evidence needed**: Product specifications, screenshots of interfaces, architecture diagrams

---

### Category 2: Open Source Projects (2-3 solutions)

Research open source projects that implement similar functionality:

#### 2.1 Open Source Sensor Projects
- **What to research**: GitHub/open source sensor projects
- **Examples**:
  - Home Assistant sensor integrations
  - OpenHAB sensor bindings
  - ESPHome sensor configurations
- **What to analyze**:
  - Code architecture
  - Sensor driver implementations
  - Data handling approaches
  - Strengths: Open source, learn from code
  - Weaknesses: May be incomplete, documentation varies
- **Evidence needed**: GitHub repositories, code snippets, architecture documentation

#### 2.2 MQTT-Based Sensor Projects
- **What to research**: Projects using MQTT for sensor data
- **Examples**:
  - ESP32 MQTT sensor projects
  - Node-RED sensor flows
  - Tasmota sensor integrations
- **What to analyze**:
  - MQTT implementation approaches
  - Topic structure and data formats
  - Integration patterns
  - Strengths: Standard protocol, good examples
  - Weaknesses: May be device-specific
- **Evidence needed**: Project documentation, MQTT topic examples, code samples

---

### Category 3: Data Visualization Solutions (1-2 solutions)

Research how others visualize sensor data:

#### 3.1 Grafana Sensor Dashboards
- **What to research**: Existing Grafana dashboards for sensor data
- **Examples**:
  - Grafana IoT sensor dashboards
  - Prometheus + Grafana sensor monitoring
  - Home automation Grafana dashboards
- **What to analyze**:
  - Dashboard design patterns
  - Data source integration (Prometheus, InfluxDB, etc.)
  - Visualization techniques
  - Strengths: Professional visualization, flexible
  - Weaknesses: Requires data infrastructure setup
- **Evidence needed**: Dashboard screenshots, configuration examples, documentation

#### 3.2 Other Visualization Platforms
- **What to research**: Alternative visualization approaches
- **Examples**:
  - ThingsBoard (IoT platform)
  - Home Assistant dashboards
  - Custom web interfaces for sensors
- **What to analyze**:
  - User interface design
  - Real-time update methods
  - Historical data presentation
  - Strengths: Different approaches to learn from
  - Weaknesses: May be platform-specific
- **Evidence needed**: Interface screenshots, architecture diagrams

---

## Research Methodology

### Step 1: Identify Solutions (Week 1)
- Search for commercial sensor boards
- Search GitHub for open source projects
- Search for MQTT sensor projects
- Search for Grafana sensor dashboards
- Create list of 8-10 potential solutions

### Step 2: Select Top 5+ Solutions (Week 1)
- Choose most relevant solutions
- Ensure mix of commercial, open source, and visualization
- Prioritize solutions most similar to our project

### Step 3: Deep Research (Week 1-2)
For each solution, research:
- **Overview**: What does it do? What problem does it solve?
- **Architecture**: How is it structured? (diagrams if available)
- **Technology**: What technologies does it use?
- **Strengths**: What does it do well?
- **Weaknesses**: What are its limitations?
- **Relevance**: How does it relate to our project?

### Step 4: Stakeholder Feedback (Week 2)
- Present solutions to hardware team (Michael, Ollie)
- Get their feedback on approaches
- Discuss what we can learn/adapt
- Document stakeholder opinions

### Step 5: Analysis and Justification (Week 2)
- Compare solutions
- Identify best practices to adopt
- Justify our chosen approach based on research
- Link research findings to our requirements

---

## Research Documentation Requirements

For each solution researched, document:

1. **Solution Name and Type**
   - Commercial product / Open source project / Academic paper / etc.

2. **Overview**
   - What problem does it solve?
   - What are its main features?
   - Who is it designed for?

3. **Technical Details**
   - Technologies used
   - Architecture (with diagram if available)
   - Data flow
   - Communication methods

4. **Strengths**
   - What does it do well?
   - What can we learn from it?

5. **Weaknesses**
   - What are its limitations?
   - What would we do differently?

6. **Relevance to Our Project**
   - How does it relate to our sensor board?
   - What can we adapt/adopt?
   - What should we avoid?

7. **Evidence**
   - Screenshots
   - Diagrams
   - Code examples
   - Documentation links
   - Product pages

8. **Stakeholder Feedback**
   - What did hardware team think?
   - What did software lead think?
   - How does this inform our approach?

---

## Example Research Template

### Solution 1: [Name]

**Type**: Commercial Product / Open Source Project  
**URL**: [Link]  
**Overview**: [2-3 sentences]

**Technical Approach**:
- Technologies: [List]
- Architecture: [Description + diagram if available]
- Data Flow: [How data moves through system]

**Strengths**:
- [Strength 1]
- [Strength 2]
- [Strength 3]

**Weaknesses**:
- [Weakness 1]
- [Weakness 2]

**Relevance to Our Project**:
- [How it relates]
- [What we can learn]
- [What we'll do differently]

**Evidence**:
- [Screenshot 1]: [Description]
- [Screenshot 2]: [Description]
- [Code Example]: [Description]

**Stakeholder Feedback**:
- Michael: [Feedback]
- Ollie: [Feedback]
- Alex: [Feedback]

---

## Minimum Requirements

To meet OCR requirements, you must research:

✅ **At least 5 different solutions**
✅ **Mix of types** (commercial, open source, academic)
✅ **Screenshots/diagrams** for each
✅ **Strengths and weaknesses** analysis
✅ **Stakeholder feedback** on solutions
✅ **Justification** of your approach based on research
✅ **Links to requirements** - how research informed requirements

---

## Suggested Research List (Starting Point)

### Commercial Solutions
1. **Arduino BME680 Library** - Sensor communication approach
2. **Raspberry Pi Enviro+** - Complete environmental monitoring solution
3. **Airthings Wave Plus** - Commercial air quality monitor

### Open Source Solutions
4. **Home Assistant BME680 Integration** - Open source sensor integration
5. **ESPHome Sensor Configurations** - MQTT-based sensor projects

### Visualization Solutions
6. **Grafana IoT Dashboards** - Data visualization approaches
7. **Prometheus + Grafana Sensor Monitoring** - Time-series data handling

**Total: 7 solutions** (exceeds minimum of 5)

---

## Research Timeline

- **Week 1, Days 1-2**: Identify 8-10 potential solutions
- **Week 1, Days 3-4**: Select top 5-7 solutions, begin research
- **Week 1, Days 5-7**: Deep research on each solution, gather evidence
- **Week 2, Days 1-2**: Stakeholder meetings, get feedback
- **Week 2, Days 3-4**: Analysis and comparison
- **Week 2, Days 5-7**: Document research findings, link to requirements

---

## Research Output

The research will be documented in:
- `docs/01_analysis/research.md` - Main research document
- `docs/01_analysis/research_evidence/` - Screenshots, diagrams, code examples
- Requirements specification will reference research findings

---

**Status**: Research plan defined, ready to begin  
**Next Step**: Start identifying solutions (Week 1)

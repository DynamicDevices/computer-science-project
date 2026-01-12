# OCR A Level Computer Science H446 - Comprehensive Requirements Analysis

Based on: "Tackling A Level Projects in Computer Science OCR H446" by Ceredig Cattanach-Chell

## Overview

This document provides a comprehensive analysis of the OCR A Level Computer Science H446 Programming Project (Component 03) requirements based on the official guide. The project is worth **70 marks** and is divided into four main sections.

## Key Principles

### 1. Quality Over Quantity
- Projects are **not about quantity, but quality**
- Exam boards have specific mark schemes - you must show you meet each point
- Clear and precise documentation makes it easier to identify where criteria are met
- **Many marks are given to your report** - work on it throughout the project

### 2. Realistic Scope
- Choose a project that is **realistic and achievable**
- Well-completed 'smaller' projects often score as well as 'larger' projects
- Ensure the project has **enough scope to meet marking criteria**
- Must be **challenging enough for A Level** (beyond GCSE level)

### 3. Iterative Development
- Projects are usually developed **iteratively**
- Use iterative or Agile development methodologies
- Each iteration should be designed, implemented, and tested
- Document the journey throughout

### 4. Programming Focus
- Must use a **high-level text-based programming language**
- Focus should be on **programming abilities**, not just design
- HTML, CSS, and SQL alone are insufficient
- Must demonstrate programming skills, not just use tools

## Assessment Structure (70 marks total)

### Section 1: Analysis (10 marks)

#### What's Required:

1. **Problem Statement**
   - Clear description of the problem
   - Describe features solvable by computational methods
   - Explain why the problem lends itself to a computational solution
   - Identify and describe stakeholders
   - Explain how solution is appropriate to stakeholders' needs

2. **Research** (Essential for marking criteria)
   - **Product research**: Analyze at least 5 existing similar solutions
   - Include screenshots, diagrams, or explanations
   - Analyze strengths/weaknesses of existing solutions
   - Get stakeholder feedback on existing solutions
   - Justify chosen approach based on research
   - Use **qualitative and quantitative research methods**

3. **Research Methods**
   - **Meetings/Interviews**: At least one meeting with main stakeholder
   - Record ideas, questions, and feedback
   - **Surveys**: Can be used for multiple stakeholders
   - Design high-quality questions
   - Balance between meetings and surveys based on needs

4. **Requirements Specification**
   - Numbered requirements linked to research evidence
   - Each requirement should:
     - Solve a specific problem
     - Link to research evidence (page references)
     - Have clear justification
     - Include **measurable success criteria**
   - Break down into sections (e.g., "Login Screen" → sub-requirements)
   - Avoid vague/unmeasurable criteria

5. **Success Criteria**
   - Must be **measurable**
   - Link to requirements
   - Examples of measurable vs vague:
     - ✅ "System loads within 10 seconds" vs ❌ "Should open quickly"
     - ✅ "Colours match company brand colours" vs ❌ "Colours should be attractive"

6. **Limitations**
   - Identify what will NOT be implemented
   - Justify why (scope, technical, time constraints)
   - **Warning**: "Too complicated" or "Don't know how" are NOT good reasons

7. **Hardware and Software Requirements**
   - List additional hardware/software needed
   - Note unique requirements (sensors, specific OS, libraries)
   - Consider stakeholder needs

8. **Commentary**
   - Written explanations throughout
   - Show journey from idea → research → requirements
   - Explain decisions and alternatives considered
   - Quality over quantity - be concise

#### To-Do Checklist:
- [ ] Clear problem description
- [ ] Identified stakeholders (avoid friends, yourself, or CS teacher)
- [ ] Researched at least 5 similar solutions
- [ ] Conducted meetings with stakeholders
- [ ] Created surveys (if needed)
- [ ] Numbered requirements specification
- [ ] Each requirement linked to research evidence
- [ ] Measurable success criteria for each requirement
- [ ] Identified limitations with justifications
- [ ] Listed hardware/software requirements
- [ ] Commentary explaining decisions

---

### Section 2: Design (15 marks)

#### What's Required:

1. **Justifications**
   - **All design decisions must be justified**
   - Link design to requirements specification
   - Explain from Computer Science perspective (speed, reusability, etc.)

2. **Decomposition**
   - Break problem into smaller parts
   - Use modular design
   - Create decomposition diagrams/tables/lists
   - Show how parts relate to each other

3. **Design Diagrams** (Use 2+ of the following)
   - **Decomposition diagrams**: Show problem breakdown
   - **Class diagrams**: For object-oriented programming
   - **Data Flow Diagrams (DFDs)**: Show data movement
   - **Entity Relationship Diagrams (E-R)**: For databases

4. **Object-Oriented Design** (if using OOP)
   - Class diagrams showing:
     - Classes and their relationships
     - Attributes and methods
     - Multiplicity (1-to-1, 1-to-many, many-to-many)
   - Justify class structure decisions

5. **Database Design** (if using database)
   - **Data tables** for each table showing:
     - Table name
     - Field names
     - Primary/foreign keys
     - Data types
     - Validation rules
   - **E-R diagrams** showing relationships
   - Consider normalization (3NF typically)
   - SQL queries (SELECT, INSERT, UPDATE, DELETE)
   - **Note**: SQL alone is insufficient - must use programming language

6. **Algorithms**
   - Design **all key algorithms** in pseudocode
   - Pseudocode should be close to programming language
   - Algorithms must form **complete solution**
   - Can use flowcharts for complex algorithms
   - Update algorithms if changes needed during development

7. **Data Structures**
   - Identify key variables
   - Justify data structures used:
     - Arrays, lists, stacks, queues, graphs, hash tables, etc.
   - Show structure with sample data
   - Justify choices (simplicity, speed, reusability)

8. **User Interface Design**
   - Design GUI (usually required)
   - Use wireframes (line drawings)
   - Show key features and layout
   - Number components and explain
   - Reference research from Analysis section
   - Include menus, controls, layout

9. **Usability Features**
   - Features that make program accessible
   - Link to requirements specification
   - Examples:
     - Error handling (re-enter data without crashing)
     - Colour/font choices
     - Layout considerations
     - Accessibility (colour blind, visually impaired)
     - Text-to-speech options

10. **Test Plans**
    - **Two types of testing**:
      - **Iterative testing** (white-box): Test during development
      - **Post-development testing** (black-box): Test complete system
    - Test plans should:
      - Reference requirements specification
      - Test normal, boundary, invalid, and erroneous data
      - Test logic paths, runtime errors, validation
      - Include stakeholder scenarios for post-development testing
    - Can plan tests before each iteration

#### To-Do Checklist:
- [ ] Decomposition diagram/table/list
- [ ] Class diagram (if using OOP)
- [ ] Data tables (if using database)
- [ ] E-R diagram (if using database)
- [ ] DFD (if appropriate)
- [ ] Algorithms in pseudocode for complete solution
- [ ] Key variables and data structures identified and justified
- [ ] GUI designs (wireframes)
- [ ] Usability features discussed
- [ ] Iterative test plans
- [ ] Post-development test plans/scenarios
- [ ] All design decisions justified

---

### Section 3: Development & Testing (25 marks)

#### What's Required:

1. **Development Planning**
   - Create development plan before starting
   - Organize into iterations
   - Plan time for testing
   - Include contingency time
   - Simple plan is sufficient (not required by mark scheme)

2. **Evidence of Development**
   - **Record development journey** throughout
   - Quality over quantity
   - Screenshots every 20-30 lines or per function
   - Focus on blocks of code and completed sections
   - **Do NOT wait until end** - evidence must be in order

3. **Evidence Methods**
   - **Screenshots**: Most common, easy to create
     - Ensure readable resolution
     - Crop appropriately
   - **Photos**: For physical computing projects
   - **Code**: Copy/paste code with annotations
   - **Video**: For complex interactions or errors
   - Choose method that best shows evidence

4. **Code Annotation**
   - Annotate code to explain:
     - What it does
     - Why decisions were made
     - Link to design/requirements
   - Use comments in code
   - Explain complex algorithms

5. **Iterative Development Evidence**
   - Show each iteration:
     - What was implemented
     - Testing conducted
     - Results
     - Any changes made
   - Document algorithm changes if needed

6. **Testing Evidence**
   - **Iterative Testing** (white-box):
     - Test each function/method/algorithm
     - Test normal, boundary, invalid, erroneous data
     - Show test inputs and outputs
     - Document failed tests and fixes
   - **Post-Development Testing** (black-box):
     - Test complete system
     - Test against requirements specification
     - Stakeholder testing with scenarios
     - Qualitative testing (speed, feel, accessibility)

7. **Error Handling**
   - Document errors encountered
   - Show how errors were fixed
   - Include screenshots of errors
   - Explain debugging process

8. **Version Control**
   - Use version control (Git recommended)
   - Show development history
   - Evidence of iterative development
   - Commit messages show progress

#### Key Warnings:
- ⚠️ Don't rush into coding without planning
- ⚠️ Don't fail to record journey (hard to backtrack)
- ⚠️ Don't over-evidence (wastes time)
- ⚠️ Ensure screenshots are readable

#### To-Do Checklist:
- [ ] Development plan created
- [ ] Evidence recorded throughout (not at end)
- [ ] Screenshots/photos/code with annotations
- [ ] Each iteration documented
- [ ] Testing evidence for each iteration
- [ ] Failed tests documented with fixes
- [ ] Post-development testing completed
- [ ] Stakeholder testing conducted
- [ ] Version control used and documented

---

### Section 4: Evaluation (20 marks)

#### What's Required:

1. **Success of Solution**
   - Evaluate against **success criteria** from Analysis
   - Evaluate against **requirements specification**
   - Show which requirements were met
   - Identify any unmet requirements

2. **Post-Development Testing Results**
   - Present results from post-development testing
   - Show test results and outcomes
   - Compare expected vs actual results

3. **Usability and Stakeholder Testing**
   - Present stakeholder feedback
   - Include:
     - What worked
     - What errors occurred
     - How errors impact stakeholders
     - Areas for improvement
     - Overall feel for system success
   - Qualitative feedback on usability

4. **Performance Analysis**
   - Analyze system performance
   - Speed, responsiveness
   - Resource usage
   - Compare to requirements

5. **Limitations**
   - Honest assessment of limitations
   - What doesn't work as well as hoped
   - What couldn't be implemented
   - Justify limitations

6. **Future Development**
   - Realistic future enhancements
   - What would be added next
   - How system could be extended
   - Maintenance considerations

7. **Reflection**
   - Critical reflection on development process
   - What went well
   - What could be improved
   - Lessons learned
   - How project met objectives

#### To-Do Checklist:
- [ ] Evaluated against all success criteria
- [ ] Evaluated against requirements specification
- [ ] Post-development test results presented
- [ ] Stakeholder feedback included
- [ ] Performance analyzed
- [ ] Limitations honestly assessed
- [ ] Future development proposed
- [ ] Critical reflection on process

---

## Project-Specific Requirements

### Stakeholders

**Good Stakeholders:**
- Teachers (not CS teacher)
- Local business owners
- Community members
- Professionals in relevant field
- Have backup stakeholders

**Avoid:**
- Friends (biased)
- Yourself
- CS teacher
- People who won't be critical

**Requirements:**
- Available throughout project
- Willing to give time
- Can provide critical feedback
- Understand the problem domain

### Programming Languages

**Appropriate:**
- Python
- Java
- C#
- C++
- JavaScript (with server-side)
- Other high-level text-based languages

**Insufficient Alone:**
- HTML/CSS
- SQL
- Visual programming (Scratch, etc.)

### Design Methodologies

**Options:**
1. **Waterfall**: Sequential (Analysis → Design → Implementation)
2. **Iterative/Agile**: Incremental development (recommended)
3. **Prototyping**: Build prototype, get feedback, refine

**Recommendation**: Iterative/Agile for A Level projects

### Using Libraries and APIs

- ✅ **Allowed** - but project judged on YOUR code
- ⚠️ Don't rely solely on pre-generated libraries
- ✅ Show how you use libraries
- ✅ Test libraries within your system

### Documentation Format

- Professional report format
- Title page
- Table of contents
- Headers/footers
- Page numbers
- References section
- Use styles consistently
- Clear section headings

### Authentication

- Work must be authenticated
- Version control helps
- Regular check-ins with teacher
- Evidence of development journey

## Common Mistakes to Avoid

1. ❌ Spending too much time programming, ignoring documentation
2. ❌ Choosing unrealistic project scope
3. ❌ Moving too quickly through Analysis
4. ❌ Not recording development journey
5. ❌ Over-evidence (wasting time)
6. ❌ Unreadable screenshots
7. ❌ Vague success criteria
8. ❌ Not justifying design decisions
9. ❌ Missing algorithms for key components
10. ❌ Not linking design to requirements

## Success Tips

1. ✅ Understand mark scheme before starting
2. ✅ Quality over quantity
3. ✅ Record evidence throughout
4. ✅ Justify all decisions
5. ✅ Link everything back to requirements
6. ✅ Test thoroughly
7. ✅ Get stakeholder feedback
8. ✅ Be honest about limitations
9. ✅ Reflect critically
10. ✅ Keep documentation professional

## Project Checklist

### Before Starting
- [ ] Understand mark scheme
- [ ] Choose appropriate project
- [ ] Identify stakeholders
- [ ] Check with teacher
- [ ] Set up development environment
- [ ] Set up version control

### Analysis Phase
- [ ] Problem clearly defined
- [ ] Stakeholders identified
- [ ] Research conducted (5+ similar solutions)
- [ ] Requirements specification created
- [ ] Success criteria defined (measurable)
- [ ] Limitations identified
- [ ] Hardware/software requirements listed

### Design Phase
- [ ] Problem decomposed
- [ ] Design diagrams created (2+ types)
- [ ] Algorithms designed (complete solution)
- [ ] Data structures identified and justified
- [ ] GUI designed
- [ ] Usability features considered
- [ ] Test plans created
- [ ] All decisions justified

### Development Phase
- [ ] Development plan created
- [ ] Evidence recorded throughout
- [ ] Code annotated
- [ ] Iterative testing conducted
- [ ] Errors documented and fixed
- [ ] Version control used

### Evaluation Phase
- [ ] Evaluated against success criteria
- [ ] Post-development testing completed
- [ ] Stakeholder feedback gathered
- [ ] Performance analyzed
- [ ] Limitations assessed
- [ ] Future development proposed
- [ ] Reflection written

### Final Checks
- [ ] All sections complete
- [ ] Evidence readable
- [ ] References included
- [ ] Professional formatting
- [ ] Proof-read
- [ ] Checked against mark scheme

---

## Additional Resources

- OCR A Level Computer Science H446 Specification
- OCR Programming Project Guidance
- Teacher support and feedback
- Version control documentation
- Testing frameworks documentation

---

**Document Status**: Complete analysis based on OCR guide  
**Last Updated**: 2026  
**Next Steps**: Use this analysis to guide project development and ensure all requirements are met

# Ticket Template

**TICKET-ID:** [WORKFLOW]-[STAGE]-[SEQUENCE]  
**Created:** [Date]  
**Last Updated:** [Date]  
**Status:** [Not Started / In Progress / Testing / Complete / Blocked]

## Ticket Overview

**Title:** [Action-oriented description of what needs to be accomplished]

**Category:** [Setup / Data / Algorithm / Integration / Validation / Documentation]

**Priority:** [High / Medium / Low]

**Estimated Duration:** [Hours - should be 2-6 hours maximum]

**Actual Duration:** [Hours spent - updated as work progresses]

## Context and Objectives

### Project Context
**Paper:** [Research paper title being implemented]  
**Component:** [System component this ticket relates to]  
**Stage:** [Current workflow stage - Discovery/Investigation/Specification/Planning/Implementation]

### Ticket Objective
**Purpose:** [What this ticket accomplishes in the larger project context]

**Connection to Success Criteria:** [How this ticket contributes to overall project success]

## Dependencies and Sequencing

### Prerequisites
**Must be Complete Before Starting:**
- [ ] [Dependency 1: Ticket ID or external requirement]
- [ ] [Dependency 2: Ticket ID or external requirement]
- [ ] [Dependency 3: Ticket ID or external requirement]

**Nice to Have Complete:**
- [ ] [Optional dependency 1: Would help but not required]
- [ ] [Optional dependency 2: Would help but not required]

### Enables
**This Ticket Unblocks:**
- [Downstream ticket 1: Ticket ID that depends on this work]
- [Downstream ticket 2: Ticket ID that depends on this work]

### Parallel Work
**Can Work Simultaneously With:**
- [Parallel ticket 1: Ticket ID that can run at same time]
- [Parallel ticket 2: Ticket ID that can run at same time]

## Requirements and Specifications

### Functional Requirements  
**What must be implemented:**
1. [Requirement 1: Specific functionality that must work]
2. [Requirement 2: Specific functionality that must work]  
3. [Requirement 3: Specific functionality that must work]

### Technical Requirements
**Implementation Specifications:**
- **Input Format:** [Expected input data, parameters, or dependencies]
- **Output Format:** [Expected output data, results, or artifacts]
- **Performance:** [Speed, memory, accuracy, or scalability requirements]
- **Integration:** [How this connects with other components or systems]

### Quality Requirements
**Standards that must be met:**
- **Code Quality:** [Style, organization, maintainability standards]
- **Documentation:** [Comment, docstring, and external documentation needs]
- **Testing:** [Unit test, integration test, validation requirements]
- **Error Handling:** [Expected error scenarios and recovery approaches]

## Acceptance Criteria

**Definition of Done - All must be checked before marking ticket complete:**

### Functional Acceptance
- [ ] [Criterion 1: Specific, testable functional outcome]
- [ ] [Criterion 2: Specific, testable functional outcome]
- [ ] [Criterion 3: Specific, testable functional outcome]
- [ ] [Criterion 4: Specific, testable functional outcome]

### Quality Acceptance  
- [ ] Code follows project style guidelines and conventions
- [ ] All functions/classes have appropriate documentation
- [ ] Unit tests written and passing with good coverage
- [ ] Integration points tested and verified working
- [ ] Error handling covers expected failure scenarios

### Integration Acceptance
- [ ] Component interfaces match specification requirements
- [ ] Data flows correctly to/from dependent components
- [ ] No breaking changes to existing functionality
- [ ] Configuration and parameters properly managed

## AI Collaboration Strategy

### AI Collaboration Level
**[High Autonomy / Medium Autonomy / Low Autonomy]**

**Rationale:** [Why this collaboration level is appropriate for this ticket]

### AI Role and Responsibilities
**Primary AI Persona:** [Code Generator / Technical Advisor / Research Assistant / Integration Specialist]

**AI Responsibilities:**
- [Responsibility 1: What AI should do]
- [Responsibility 2: What AI should do]
- [Responsibility 3: What AI should do]

**Human Responsibilities:**
- [Responsibility 1: What human should do]
- [Responsibility 2: What human should do]
- [Responsibility 3: What human should do]

### AI Collaboration Instructions

#### Primary AI Prompt Template
```markdown
**Context:** Working on ticket [TICKET-ID]: [TITLE]

**Project Background:**
- Paper: [PAPER_TITLE]
- Component: [COMPONENT_NAME]
- Integration Points: [HOW_THIS_CONNECTS]
- Current State: [WHAT_IS_ALREADY_COMPLETE]

**Task Requirements:**
[COPY_FUNCTIONAL_REQUIREMENTS]

**Technical Specifications:**
[COPY_TECHNICAL_REQUIREMENTS]

**Expected Deliverables:**
[LIST_EXPECTED_OUTPUTS]

**Quality Standards:**
[COPY_QUALITY_REQUIREMENTS]

**Specific Instructions:**
[DETAILED_GUIDANCE_FOR_AI_BASED_ON_TICKET_TYPE]
```

#### AI Tool Selection
**Primary Tools:**
- [Tool 1: GitHub Copilot for code generation]
- [Tool 2: ChatGPT for debugging and explanation]
- [Tool 3: Claude for complex analysis]

**Tool Usage Strategy:**
- **Code Generation:** [Which tool and when]
- **Problem Solving:** [Which tool and when]
- **Validation:** [Which tool and when]
- **Documentation:** [Which tool and when]

### Collaboration Checkpoints

#### AI Self-Assessment Points
**Checkpoint 1: Initial Implementation**
- **Trigger:** After AI generates initial code/solution
- **AI Validates:** [What AI should check about its own work]
- **Success Criteria:** [How AI knows it's on the right track]

**Checkpoint 2: Integration Readiness**
- **Trigger:** Before declaring work complete
- **AI Validates:** [What AI should verify about integration]
- **Success Criteria:** [How AI knows it's ready for human review]

#### Human Review Points
**Review 1: Approach Validation**
- **Trigger:** [When human should review approach]
- **Human Validates:** [What human should check]
- **Decision:** [Continue / Iterate / Change approach]

**Review 2: Quality Validation**
- **Trigger:** [When human should review quality]
- **Human Validates:** [What human should check]
- **Decision:** [Accept / Request improvements / Major revision]

**Final Review: Completion Validation**
- **Trigger:** All acceptance criteria appear to be met
- **Human Validates:** [Complete validation checklist]
- **Decision:** [Complete / Needs iteration / Escalate issue]

## Implementation Guidance

### Recommended Approach
**Implementation Strategy:**
1. [Step 1: Logical first step with rationale]
2. [Step 2: Next logical step with rationale]
3. [Step 3: Integration or validation step]
4. [Step 4: Testing and documentation]

**Key Considerations:**
- [Consideration 1: Important implementation detail or constraint]
- [Consideration 2: Performance or integration concern]
- [Consideration 3: Risk or complexity factor to address]

### Alternative Approaches
**Option 1:** [Alternative implementation approach]
- **Pros:** [Benefits of this approach]
- **Cons:** [Drawbacks or limitations]
- **When to Use:** [Conditions that favor this approach]

**Option 2:** [Alternative implementation approach]
- **Pros:** [Benefits of this approach]
- **Cons:** [Drawbacks or limitations]
- **When to Use:** [Conditions that favor this approach]

### Common Pitfalls
**Pitfall 1:** [Common mistake or issue]
- **How to Avoid:** [Prevention strategy]
- **How to Recover:** [What to do if it happens]

**Pitfall 2:** [Common mistake or issue]
- **How to Avoid:** [Prevention strategy]
- **How to Recovery:** [What to do if it happens]

## Testing and Validation

### Unit Testing Strategy
**Test Cases to Implement:**
- **Normal Cases:** [Expected usage scenarios]
- **Edge Cases:** [Boundary conditions and unusual inputs]
- **Error Cases:** [Invalid inputs and failure scenarios]

**Test Data Requirements:**
- [Data type 1: What kind of test data is needed]
- [Data type 2: What kind of test data is needed]

### Integration Testing
**Integration Points to Test:**
- [Integration 1: Component interface or data flow]
- [Integration 2: Component interface or data flow]

**Integration Test Scenarios:**
- [Scenario 1: End-to-end workflow test]
- [Scenario 2: Error propagation test]

### Validation Approach
**Correctness Validation:**
- [Method 1: How to verify correctness]
- [Method 2: How to verify correctness]

**Performance Validation:**
- [Metric 1: What to measure and target]
- [Metric 2: What to measure and target]

## Risk Management

### Identified Risks
**Technical Risks:**
- **Risk 1:** [Description of technical risk]
  - **Likelihood:** [High / Medium / Low]
  - **Impact:** [High / Medium / Low]
  - **Mitigation:** [How to reduce or handle this risk]

- **Risk 2:** [Description of technical risk]
  - **Likelihood:** [High / Medium / Low]
  - **Impact:** [High / Medium / Low]
  - **Mitigation:** [How to reduce or handle this risk]

**Implementation Risks:**
- **Risk 1:** [Description of implementation risk]
  - **Likelihood:** [High / Medium / Low]
  - **Impact:** [High / Medium / Low]
  - **Mitigation:** [How to reduce or handle this risk]

### Contingency Plans
**If Ticket Takes Significantly Longer Than Estimated:**
- [Action 1: Scope reduction or simplification approach]
- [Action 2: Alternative implementation strategy]
- [Action 3: Escalation or help-seeking approach]

**If Technical Approach Doesn't Work:**
- [Alternative 1: Different technical approach]
- [Alternative 2: Simplified version that still meets core requirements]
- [Alternative 3: External help or research needed]

## Progress Tracking

### Time Tracking
**Time Estimates:**
- **Planning/Setup:** [Hours]
- **Implementation:** [Hours]
- **Testing/Validation:** [Hours]
- **Documentation:** [Hours]
- **Total Estimated:** [Hours]

**Time Actuals:** [Updated as work progresses]
- **Planning/Setup:** [Actual hours]
- **Implementation:** [Actual hours]
- **Testing/Validation:** [Actual hours]
- **Documentation:** [Actual hours]
- **Total Actual:** [Actual hours]

### Progress Milestones
**25% Complete:** [What should be done at quarter progress]
**50% Complete:** [What should be done at half progress]
**75% Complete:** [What should be done at three-quarter progress]
**100% Complete:** [All acceptance criteria met and validated]

### Status Updates
**[Date] - [Status]:** [Progress description and any issues]
**[Date] - [Status]:** [Progress description and any issues]
**[Date] - [Status]:** [Progress description and any issues]

## Completion Documentation

### Implementation Summary
**Approach Taken:** [High-level description of how the ticket was completed]

**Key Technical Decisions:** [Important choices made during implementation]

**Deviations from Plan:** [Any changes from original approach and rationale]

### Quality Validation Results
**Testing Results:**
- **Unit Tests:** [Coverage and results]
- **Integration Tests:** [Results and any issues found]
- **Performance Tests:** [Measurements against requirements]

**Code Review Results:**
- **Quality Assessment:** [Code quality evaluation]
- **Issues Found:** [Problems identified and resolved]
- **Improvements Made:** [Enhancements beyond minimum requirements]

### Integration Impact
**Changes to Interfaces:** [Any modifications to component interfaces]

**Impact on Other Components:** [How this work affects other parts of system]

**Configuration Changes:** [Any parameter or setup modifications needed]

### Lessons Learned
**What Worked Well:** [Successful approaches and techniques]

**What Was Challenging:** [Difficult aspects and how they were handled]

**AI Collaboration Effectiveness:** [How well AI assistance worked for this ticket]

**Recommendations for Similar Tickets:** [Advice for future similar work]

## Handoff Information

### For Dependent Tickets
**Deliverables Available:** [What this ticket produces for downstream work]

**Interface Documentation:** [How other components should interact with this work]

**Configuration Requirements:** [Any setup needed to use this component]

### For Maintenance
**Code Organization:** [How the implemented code is structured]

**Key Functions/Classes:** [Most important code elements and their purposes]

**External Dependencies:** [Libraries, services, or resources this code relies on]

**Known Limitations:** [Current constraints or areas for future improvement]

---

## Notes and Observations
[Space for additional thoughts, insights, or implementation details discovered during work]

---

*This ticket template should be customized for each specific task. Remove sections that don't apply and add task-specific details. The goal is clear, actionable guidance that enables successful completion with appropriate AI collaboration.*
# Stage 1: Problem Discovery

**Duration:** 1-2 hours  
**Started:** [Date/Time]  
**Completed:** [Date/Time]  
**Status:** [Not Started / In Progress / Complete]

## Objective
Define clear technology requirements and evaluation criteria based on business problems and organizational constraints.

## Entry Criteria Checklist
- [ ] Evaluation context document completed
- [ ] Technology category and problem area identified
- [ ] Basic understanding of current solution limitations
- [ ] Stakeholder alignment on evaluation timeline and scope

## AI Collaboration Setup

### AI Persona: Requirements Analyst
**Role:** Senior technology architect and requirements analyst
**Collaboration Level:** Medium autonomy with human validation of business requirements
**Primary Tools:** ChatGPT/Claude for requirements analysis and framework development

## Stage Tasks

### Task 1: Problem Analysis and Validation
**Objective:** Clearly articulate and validate the core problem that technology should solve

#### Problem Definition Worksheet
**Current Problem Statement:**
[Copy from evaluation context and refine as needed]

**Problem Validation Questions:**
1. **Is this problem worth solving?**
   - Business impact if not solved: [Quantify cost, inefficiency, or missed opportunity]
   - Urgency level: [Why now vs. later]
   - Stakeholder pain level: [How much this affects key stakeholders]

2. **Is this problem clearly defined?**
   - Root cause analysis: [What's causing this problem]
   - Problem scope: [Boundaries of what needs to be solved]
   - Success definition: [What does "solved" look like]

3. **Is technology the right solution?**
   - Technology vs. process solution: [Could this be solved without new technology]
   - Technology readiness: [Is suitable technology available and mature]
   - Alternative approaches: [What non-technology alternatives exist]

#### AI Prompt Template
```markdown
**Role:** You are a senior business analyst specializing in technology requirements analysis.

**Context:** I'm evaluating [TECHNOLOGY_CATEGORY] to solve [PROBLEM_DESCRIPTION] in a [BUSINESS_CONTEXT].

**Current Situation:**
- Current Solution: [EXISTING_APPROACH]
- Pain Points: [SPECIFIC_ISSUES]
- Business Impact: [COST_OF_CURRENT_STATE]
- Stakeholders Affected: [WHO_IS_IMPACTED]

**Task:** Help me refine and validate the problem definition to ensure technology evaluation is focused on the right issues.

**Analysis Framework:**
1. **Problem Clarity:** Is the problem clearly and specifically defined?
2. **Problem Scope:** Are the boundaries appropriate for a technology solution?
3. **Root Cause:** What's the underlying cause vs. symptoms?
4. **Solution Fit:** Is technology the right type of solution for this problem?
5. **Business Case:** Is there sufficient business justification for solving this?

**Output Format:**
- **Refined Problem Statement:** [Clear, specific problem description]
- **Root Cause Analysis:** [Why this problem exists]
- **Business Justification:** [Why solving this creates value]
- **Technology Fit Assessment:** [Why technology is appropriate solution]
- **Success Vision:** [What success looks like after solving the problem]
```

#### AI Response Capture
**AI Analysis Results:**
```
[PASTE AI RESPONSE HERE]
```

#### Human Problem Validation
**Problem Validation Review:**
- [ ] Problem statement is specific and actionable
- [ ] Root causes are identified and addressable through technology
- [ ] Business justification is clear and quantifiable
- [ ] Success vision is realistic and measurable
- [ ] Technology approach is appropriate for this problem type

**Problem Statement Refinements:**
[Note any adjustments needed based on AI analysis and human validation]

**Final Problem Statement:**
[Refined, validated problem statement that will guide evaluation]

### Task 2: Requirements Framework Development
**Objective:** Transform problem definition into structured requirements with measurable criteria

#### Functional Requirements Analysis

##### Core Functional Requirements
**Must-Have Capabilities:**
[Copy from evaluation context and refine]

**AI Enhancement Prompt:**
```markdown
**Context:** Help me refine functional requirements for [TECHNOLOGY_CATEGORY] evaluation.

**Problem to Solve:** [REFINED_PROBLEM_STATEMENT]
**Current Requirements:** [LIST_CURRENT_FUNCTIONAL_REQUIREMENTS]

**Task:** Analyze and enhance functional requirements to ensure they are:
1. **Complete:** All necessary functionality covered
2. **Specific:** Clear, testable requirements
3. **Prioritized:** Critical vs. nice-to-have functionality
4. **Testable:** Can be objectively validated

**Output Format:**
```
## Must-Have Functional Requirements
- **[Requirement 1]:** [Description]
  - **Acceptance Criteria:** [How to test this]
  - **Business Justification:** [Why this is critical]
  - **Test Method:** [How to validate during evaluation]

## Should-Have Functional Requirements
- **[Requirement 1]:** [Description]
  - **Acceptance Criteria:** [How to test this]
  - **Business Value:** [Why this is important]
  - **Test Method:** [How to validate during evaluation]

## Could-Have Functional Requirements
- **[Requirement 1]:** [Description]
  - **Acceptance Criteria:** [How to test this]
  - **Nice-to-Have Value:** [Why this would be beneficial]

## Requirements Gaps Analysis
- **[Gap 1]:** [Missing requirement that should be considered]
- **[Gap 2]:** [Missing requirement that should be considered]
```
```

##### AI Response Capture
**Enhanced Functional Requirements:**
```
[PASTE AI RESPONSE HERE]
```

##### Functional Requirements Validation
**Requirements Review:**
- [ ] All critical functionality is captured
- [ ] Requirements are specific and testable
- [ ] Acceptance criteria are clear and measurable
- [ ] Priorities are appropriate for business needs
- [ ] No obvious gaps in functionality coverage

**Requirements Refinements:**
[Note any additional refinements needed]

#### Non-Functional Requirements Analysis

##### Performance and Scalability Requirements
**Current State Baseline:**
- **Performance:** [Current system performance metrics]
- **Scalability:** [Current capacity and growth projections]
- **Availability:** [Current uptime and reliability]

**Target Requirements:**
- **Performance Targets:** [Speed, throughput, response time requirements]
- **Scalability Targets:** [Growth capacity, concurrent users, data volume]
- **Availability Targets:** [Uptime requirements, recovery time objectives]
- **Reliability Targets:** [Error rates, consistency, stability requirements]

##### Security and Compliance Requirements
**Security Requirements:**
- **Data Protection:** [Encryption, privacy, data handling requirements]
- **Access Control:** [Authentication, authorization, audit requirements]
- **Network Security:** [VPN, firewall, network isolation requirements]
- **Compliance:** [Regulatory requirements: GDPR, HIPAA, SOC2, etc.]

**Compliance Validation:**
- [ ] All regulatory requirements identified and documented
- [ ] Security requirements align with organizational policies
- [ ] Audit and reporting requirements specified
- [ ] Data handling requirements clearly defined

##### Integration and Interoperability Requirements
**Integration Points:**
- **System 1:** [Integration requirements and success criteria]
- **System 2:** [Integration requirements and success criteria]
- **System 3:** [Integration requirements and success criteria]

**Data Integration Requirements:**
- **Data Sources:** [Systems that provide data to new technology]
- **Data Destinations:** [Systems that receive data from new technology]
- **Data Formats:** [Required formats, protocols, standards]
- **Real-time vs. Batch:** [Timing requirements for data exchange]

##### Usability and Experience Requirements
**User Experience Requirements:**
- **End User Experience:** [UI/UX requirements for business users]
- **Developer Experience:** [API, tooling, documentation requirements]
- **Administrative Experience:** [Management, configuration, monitoring]

**Learning Curve Requirements:**
- **Acceptable Time to Basic Competency:** [Timeline for team to become functional]
- **Training and Support:** [Available training resources and support model]
- **Documentation Quality:** [Standards for documentation completeness and clarity]

### Task 3: Constraints Analysis and Documentation
**Objective:** Identify and document all constraints that will impact technology selection

#### Technical Constraints Analysis

##### Hard Technical Constraints
**Platform Constraints:**
- **Operating System:** [Required or prohibited platforms]
- **Cloud Provider:** [Required or preferred cloud platforms]
- **Programming Language:** [Required or preferred languages]
- **Architecture:** [Required architectural patterns or approaches]

**Integration Constraints:**
- **Required Protocols:** [Must support specific protocols or standards]
- **API Requirements:** [Must provide specific API types or formats]
- **Data Format Requirements:** [Must support specific data formats]
- **Legacy System Support:** [Must integrate with specific legacy systems]

**Security Constraints:**
- **Security Policies:** [Organizational security requirements]
- **Compliance Requirements:** [Regulatory compliance mandates]
- **Network Requirements:** [Network isolation, VPN, firewall requirements]
- **Audit Requirements:** [Logging, monitoring, audit trail requirements]

##### Soft Technical Constraints
**Preferred Technologies:**
- **Technology Stack Preferences:** [Technologies that would simplify integration]
- **Vendor Preferences:** [Preferred vendors based on existing relationships]
- **Architecture Preferences:** [Preferred architectural approaches]

#### Organizational Constraints Analysis

##### Team and Skill Constraints
**Current Team Assessment:**
- **Team Size:** [Number of people available for implementation and operation]
- **Skill Levels:** [Current expertise levels in relevant technologies]
- **Learning Capacity:** [Available time and budget for skill development]
- **Change Tolerance:** [Team's comfort with adopting new technologies]

**Skill Gap Analysis:**
- **Critical Skill Gaps:** [Skills that must be developed or hired]
- **Nice-to-Have Skills:** [Skills that would be helpful but not essential]
- **Training Timeline:** [How quickly team can develop needed skills]
- **External Support Options:** [Availability of consultants, contractors, vendor support]

##### Process and Cultural Constraints
**Organizational Culture:**
- **Innovation Tolerance:** [Comfort with cutting-edge vs. proven technologies]
- **Risk Tolerance:** [Appetite for technical and business risks]
- **Change Management Capacity:** [Ability to handle organizational change]
- **Decision-Making Style:** [Consensus-driven vs. top-down decision making]

**Process Constraints:**
- **Development Processes:** [Required development methodologies and practices]
- **Approval Processes:** [Required approvals for technology adoption]
- **Procurement Processes:** [Vendor evaluation and purchasing requirements]
- **Change Management:** [Required change management and communication processes]

#### Business Constraints Analysis

##### Budget and Timeline Constraints
**Budget Analysis:**
- **Available Budget:** [Total budget available for technology adoption]
- **Budget Allocation:** [Breakdown of budget by category: licensing, implementation, training]
- **Budget Timeline:** [When budget must be spent and renewal cycles]
- **Cost Sensitivity:** [Tolerance for cost overruns and ongoing expenses]

**Timeline Constraints:**
- **Decision Deadline:** [When adoption decision must be made]
- **Implementation Deadline:** [When technology must be operational]
- **Business Deadlines:** [External deadlines that affect implementation timing]
- **Resource Availability:** [When team members are available for implementation]

##### Strategic and Vendor Constraints
**Strategic Alignment:**
- **Technology Strategy:** [Required alignment with technology roadmap]
- **Business Strategy:** [Required alignment with business objectives]
- **Vendor Strategy:** [Preferences for vendor consolidation or diversification]

**Vendor Constraints:**
- **Preferred Vendors:** [Existing vendor relationships to leverage]
- **Prohibited Vendors:** [Vendors that cannot be used due to conflicts or policies]
- **Vendor Requirements:** [Required vendor capabilities: support, SLAs, financial stability]

### Task 4: Success Criteria and Metrics Definition
**Objective:** Define measurable success criteria for both evaluation process and technology adoption

#### Evaluation Success Criteria

##### Process Success Metrics
**Evaluation Quality:**
- **Decision Confidence:** [Target confidence level in final recommendation - 80%+]
- **Stakeholder Alignment:** [Percentage of stakeholders who support final decision - 90%+]  
- **Evidence Quality:** [Sufficient evidence gathered to support decision]
- **Timeline Adherence:** [Complete evaluation within planned timeframe]

**Evaluation Efficiency:**
- **Resource Utilization:** [Stay within planned evaluation time and budget]
- **Coverage Completeness:** [All critical requirements and criteria evaluated]
- **Risk Assessment:** [All major risks identified and assessed]

##### Decision Quality Metrics
**Decision Clarity:**
- **Clear Recommendation:** [Unambiguous ADOPT/TRIAL/AVOID recommendation]
- **Supporting Rationale:** [Clear reasoning based on evaluation evidence]
- **Implementation Readiness:** [Actionable plan if adoption is recommended]
- **Risk Mitigation:** [Identified risks have viable mitigation strategies]

#### Technology Adoption Success Criteria

##### Implementation Success Metrics
**Technical Implementation:**
- **Functional Requirements:** [Percentage of requirements successfully implemented - 95%+]
- **Performance Requirements:** [Performance targets met or exceeded]
- **Integration Success:** [All required integrations working correctly]
- **Quality Standards:** [Code quality, security, and reliability standards met]

**Timeline and Budget:**
- **Implementation Timeline:** [Complete implementation within planned timeframe]
- **Budget Adherence:** [Stay within approved implementation budget]
- **Resource Efficiency:** [Efficient use of team time and external resources]

##### User Adoption Success Metrics
**Adoption Rates:**
- **User Onboarding:** [Target percentage of users successfully onboarded - 80%+]
- **Feature Utilization:** [Target percentage utilization of key features - 70%+]
- **User Satisfaction:** [Target user satisfaction score - 4.0/5.0+]

**Competency Development:**
- **Team Competency:** [Target percentage of team achieving basic competency - 90%+]
- **Time to Competency:** [Target time for team to become productive - within X weeks]
- **Knowledge Retention:** [Team maintains competency over time]

##### Business Impact Success Metrics
**Quantitative Business Metrics:**
- **[Business Metric 1]:** [Specific measurement, current baseline, target improvement]
- **[Business Metric 2]:** [Specific measurement, current baseline, target improvement]
- **[Business Metric 3]:** [Specific measurement, current baseline, target improvement]

**Qualitative Business Metrics:**
- **Process Improvement:** [How business processes are improved]
- **User Experience:** [How user experience is enhanced]
- **Organizational Capability:** [How organizational capabilities are enhanced]

**ROI and Value Metrics:**
- **Return on Investment:** [Target ROI percentage and timeframe]
- **Payback Period:** [Target time to recover investment]
- **Total Value Created:** [Quantified value created over 3-year period]

### Task 5: Evaluation Framework Development
**Objective:** Create weighted evaluation criteria that enable objective technology comparison

#### Evaluation Criteria Definition

##### AI Prompt for Evaluation Framework
```markdown
**Context:** Create an evaluation framework for [TECHNOLOGY_CATEGORY] that enables objective comparison of alternatives.

**Requirements Context:**
- **Functional Requirements:** [SUMMARY_OF_FUNCTIONAL_REQUIREMENTS]
- **Non-Functional Requirements:** [SUMMARY_OF_NON_FUNCTIONAL_REQUIREMENTS]
- **Constraints:** [SUMMARY_OF_KEY_CONSTRAINTS]
- **Business Context:** [ORGANIZATION_TYPE_AND_PRIORITIES]

**Task:** Develop a weighted evaluation framework with specific criteria and measurement approaches.

**Framework Requirements:**
1. **Comprehensive:** Cover all critical decision factors
2. **Measurable:** Objective scoring criteria for each factor
3. **Weighted:** Appropriate weight based on business priorities
4. **Practical:** Can be evaluated within available time and resources

**Output Format:**
```
## Evaluation Criteria Framework

### Primary Criteria (70-80% of total weight)
**[Criterion 1]: Functional Fit** - Weight: X%
- **Description:** How well technology meets functional requirements
- **Measurement Method:** [Specific approach to scoring this criterion]
- **Scoring Scale:** [1-5 scale with descriptions for each level]
- **Validation Approach:** [How to verify scores during evaluation]

**[Criterion 2]: Performance** - Weight: X%
- **Description:** Speed, scalability, and resource efficiency
- **Measurement Method:** [Benchmarking, load testing, performance analysis]
- **Scoring Scale:** [1-5 scale with performance thresholds]
- **Validation Approach:** [Specific performance tests to conduct]

### Secondary Criteria (15-25% of total weight)
**[Criterion 3]: Integration Complexity** - Weight: X%
- **Description:** Ease of integration with existing systems
- **Measurement Method:** [Integration testing, API evaluation]
- **Scoring Scale:** [1-5 scale based on integration effort]

**[Criterion 4]: Vendor Ecosystem** - Weight: X%
- **Description:** Vendor health, support quality, roadmap clarity
- **Measurement Method:** [Vendor research, reference checks]
- **Scoring Scale:** [1-5 scale based on vendor assessment]

### Supporting Criteria (5-15% of total weight)
**[Criterion 5]: Learning Curve** - Weight: X%
- **Description:** Time for team to achieve competency
- **Measurement Method:** [Documentation review, community assessment]
- **Scoring Scale:** [1-5 scale based on learning requirements]

## Scoring Methodology
**Score Calculation:** [How individual criterion scores combine into overall score]
**Decision Thresholds:** [Minimum scores required for adoption recommendation]
**Tie-Breaking Criteria:** [How to handle close scores between alternatives]
```
```

##### AI Response Capture
**Evaluation Framework:**
```
[PASTE AI RESPONSE HERE]
```

##### Evaluation Framework Validation
**Framework Review:**
- [ ] All critical decision factors are covered
- [ ] Weights reflect business priorities appropriately
- [ ] Scoring methods are objective and measurable
- [ ] Framework can be executed within evaluation timeline
- [ ] Decision thresholds are realistic and appropriate

**Framework Refinements:**
[Note any adjustments needed to the evaluation framework]

#### Final Evaluation Framework
**Weighted Evaluation Criteria:**

| Criterion | Weight | Description | Measurement Method | Score Range |
|-----------|--------|-------------|-------------------|-------------|
| [Criterion 1] | X% | [Description] | [Method] | 1-5 |
| [Criterion 2] | X% | [Description] | [Method] | 1-5 |
| [Criterion 3] | X% | [Description] | [Method] | 1-5 |
| [Criterion 4] | X% | [Description] | [Method] | 1-5 |
| [Criterion 5] | X% | [Description] | [Method] | 1-5 |
| **Total** | **100%** | | | **Weighted Average** |

**Decision Framework:**
- **ADOPT Threshold:** [Minimum weighted score for adoption - e.g., 4.0/5.0]
- **TRIAL Threshold:** [Score range for trial recommendation - e.g., 3.0-3.9/5.0]
- **AVOID Threshold:** [Maximum score for avoid recommendation - e.g., <3.0/5.0]

## Stage Completion

### Deliverables Checklist
- [ ] **Problem Statement:** Clear, validated problem definition
- [ ] **Requirements Specification:** Complete functional and non-functional requirements
- [ ] **Constraints Documentation:** Comprehensive constraints analysis
- [ ] **Success Criteria:** Measurable evaluation and adoption success metrics
- [ ] **Evaluation Framework:** Weighted criteria for objective technology comparison

### Quality Validation
**Requirements Quality:**
- [ ] Problem statement is specific and actionable
- [ ] Requirements are complete, specific, and testable
- [ ] Constraints are comprehensive and realistic
- [ ] Success criteria are measurable and achievable
- [ ] Evaluation framework enables objective comparison

**Stakeholder Validation:**
- [ ] Business stakeholders agree with problem definition and requirements
- [ ] Technical stakeholders confirm technical requirements and constraints
- [ ] Evaluation framework reflects appropriate business priorities
- [ ] Success criteria align with organizational expectations

### Risk Assessment
**Discovery Stage Risks:**
- **Incomplete Requirements:** [Risk that requirements miss critical aspects]
  - **Mitigation:** [Multiple stakeholder review and validation]
- **Unrealistic Constraints:** [Risk that constraints are too restrictive]  
  - **Mitigation:** [Constraint flexibility analysis and prioritization]
- **Biased Evaluation Framework:** [Risk that framework favors particular solution]
  - **Mitigation:** [Multiple perspectives and objective measurement methods]

### Next Steps Planning
**Stage 2 Preparation:**
- [ ] Technology landscape research priorities identified
- [ ] Evaluation framework ready for technology scoring
- [ ] Stakeholder availability confirmed for technology review
- [ ] Initial technology shortlist hypotheses documented

**Outstanding Questions:**
[Key questions that Stage 2 investigation should answer]
- [Question 1: Specific technology landscape question]
- [Question 2: Specific capability or constraint question]
- [Question 3: Specific evaluation approach question]

## Notes and Observations
[Space for additional thoughts, insights, or considerations discovered during requirements analysis]

---

*This stage should take 1-2 hours maximum. Focus on creating clear, actionable requirements rather than perfect specifications. The goal is establishing evaluation criteria that enable confident decision-making, not comprehensive business analysis.*
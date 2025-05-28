# Stage 2: Landscape Investigation

**Duration:** 2-4 hours  
**Started:** [Date/Time]  
**Completed:** [Date/Time]  
**Status:** [Not Started / In Progress / Complete]

## Objective
Research technology landscape, analyze alternatives, and create shortlist of 2-4 technologies for hands-on evaluation.

## Entry Criteria Checklist
- [ ] Stage 1 completed with validated requirements and evaluation framework
- [ ] Clear problem statement and success criteria established
- [ ] Evaluation criteria and weighting defined
- [ ] Stakeholder alignment on requirements and approach

## AI Collaboration Setup

### AI Persona: Technology Scout
**Role:** Senior technology analyst and market researcher with deep knowledge of technology ecosystems
**Collaboration Level:** High autonomy research with human strategic validation
**Primary Tools:** ChatGPT/Claude for market research and analysis

## Stage Tasks

### Task 1: Technology Landscape Research
**Objective:** Map the complete landscape of available technologies in the category

#### Market Landscape Analysis

##### AI Prompt Template
```markdown
**Role:** You are a senior technology analyst specializing in [TECHNOLOGY_CATEGORY] with deep knowledge of market trends and vendor ecosystems.

**Context:** 
- Technology Category: [CATEGORY_FROM_EVALUATION_CONTEXT]
- Problem to Solve: [PROBLEM_STATEMENT_FROM_STAGE_1]
- Organization Type: [BUSINESS_CONTEXT]
- Key Requirements: [TOP_3_FUNCTIONAL_REQUIREMENTS]

**Task:** Conduct comprehensive technology landscape analysis to identify all viable options.

**Research Framework:**
1. **Market Overview:** Current state, trends, and evolution of this technology category
2. **Technology Categories:** Different approaches and architectural patterns available
3. **Vendor Landscape:** Major players, emerging vendors, open source options
4. **Market Positioning:** How different technologies are positioned and differentiated
5. **Technology Maturity:** Assessment of maturity levels across different options

**Output Format:**
```
## Technology Category Overview
**Market Maturity:** [Emerging/Growing/Mature - description of market evolution]
**Market Size:** [Approximate market size and growth rate if available]
**Key Market Drivers:** [Forces driving adoption and technology development]
**Technology Trends:** [Important trends affecting this technology category]
**Adoption Patterns:** [How organizations typically adopt these technologies]

## Technology Approaches and Architectures
### Approach 1: [Architectural Pattern or Technology Type]
**Description:** [How this approach works and key characteristics]
**Strengths:** [Primary advantages of this approach]
**Weaknesses:** [Primary limitations of this approach]
**Use Cases:** [Scenarios where this approach excels]
**Representative Technologies:** [Examples of technologies using this approach]

### Approach 2: [Architectural Pattern or Technology Type]
[Same format as Approach 1]

### Approach 3: [Architectural Pattern or Technology Type]
[Same format as Approach 1]

## Market Segments and Categories
### Enterprise Solutions
**Characteristics:** [Features, positioning, pricing typical of enterprise solutions]
**Key Players:** [Major enterprise vendors in this space]
**Typical Customers:** [Organization types that choose enterprise solutions]

### Mid-Market Solutions
**Characteristics:** [Features, positioning, pricing typical of mid-market solutions]
**Key Players:** [Vendors focused on mid-market segment]
**Typical Customers:** [Organization types that choose mid-market solutions]

### Small Business / Startup Solutions
**Characteristics:** [Features, positioning, pricing for smaller organizations]
**Key Players:** [Vendors or open source projects focused on this segment]
**Typical Customers:** [Organization types that choose these solutions]

### Open Source Ecosystem
**Major Projects:** [Key open source alternatives and their characteristics]
**Commercial Support:** [Companies providing commercial support for open source]
**Community Health:** [Assessment of community activity and sustainability]

## Vendor Landscape Analysis
### Market Leaders
**[Vendor 1]:** [Market position, key strengths, target customers]
**[Vendor 2]:** [Market position, key strengths, target customers]
**[Vendor 3]:** [Market position, key strengths, target customers]

### Strong Challengers
**[Vendor 1]:** [Market position, differentiation, growth trajectory]
**[Vendor 2]:** [Market position, differentiation, growth trajectory]

### Emerging Players
**[Vendor 1]:** [Innovation focus, market traction, potential]
**[Vendor 2]:** [Innovation focus, market traction, potential]

### Niche Specialists
**[Vendor 1]:** [Specialization area, target use cases]
**[Vendor 2]:** [Specialization area, target use cases]

## Technology Evolution and Future Outlook
**Emerging Trends:** [New developments affecting this technology category]
**Future Direction:** [Where the technology category is heading]
**Disruption Risks:** [Potential disruptive technologies or approaches]
**Investment Trends:** [Vendor consolidation, acquisition, investment patterns]
```
```

##### AI Response Capture
**Technology Landscape Analysis:**
```
[PASTE AI RESPONSE HERE]
```

##### Landscape Analysis Validation
**Research Quality Review:**
- [ ] Comprehensive coverage of technology category
- [ ] Current and accurate market information
- [ ] Clear technology approach differentiation
- [ ] Realistic vendor positioning and assessment
- [ ] Useful insights about market trends and evolution

**Landscape Refinements:**
[Note any gaps or corrections needed in the landscape analysis]

### Task 2: Technology Options Identification
**Objective:** Create comprehensive inventory of specific technology options

#### Technology Inventory Development

##### AI Prompt for Technology Options
```markdown
**Context:** Based on the landscape analysis, identify specific technology products and solutions for evaluation.

**Requirements Filter:**
- **Problem to Solve:** [PROBLEM_STATEMENT]
- **Must-Have Requirements:** [TOP_MUST_HAVE_REQUIREMENTS]
- **Key Constraints:** [MAJOR_CONSTRAINTS_FROM_STAGE_1]
- **Organization Profile:** [SIZE_INDUSTRY_TECHNICAL_MATURITY]

**Task:** Generate comprehensive list of specific technologies that could potentially solve the problem.

**Inclusion Criteria:**
- Addresses the core problem we're trying to solve
- Meets basic must-have functional requirements
- Compatible with major organizational constraints
- Commercially available or production-ready open source
- Has sufficient documentation and support

**Output Format:**
For each technology, provide:
```
## [Technology Name]
**Vendor/Provider:** [Company or organization]
**Category:** [Enterprise/Mid-Market/Open Source/Cloud Service]
**Deployment Model:** [On-premise/Cloud/SaaS/Hybrid]
**Pricing Model:** [Subscription/License/Open Source/Usage-based]

### Overview
**Primary Purpose:** [What problem this technology solves]
**Key Value Proposition:** [Main selling points and differentiators]
**Target Market:** [Intended customer types and use cases]

### Technical Overview
**Architecture:** [High-level technical approach]
**Key Technologies:** [Underlying technologies and frameworks]
**Integration Capabilities:** [APIs, protocols, standards supported]
**Scalability Model:** [How it scales and what limits exist]

### Functional Capabilities
**Core Features:**
- [Feature 1]: [Description of capability]
- [Feature 2]: [Description of capability]
- [Feature 3]: [Description of capability]

**Advanced Features:**
- [Feature 1]: [Description of advanced capability]
- [Feature 2]: [Description of advanced capability]

### Requirements Fit (Preliminary)
**Functional Requirements:**
- [Requirement 1]: ✅ Supported / ⚠️ Partial / ❌ Not Supported
- [Requirement 2]: ✅ Supported / ⚠️ Partial / ❌ Not Supported
- [Requirement 3]: ✅ Supported / ⚠️ Partial / ❌ Not Supported

**Constraints Compatibility:**
- [Constraint 1]: ✅ Compatible / ⚠️ Possible / ❌ Incompatible
- [Constraint 2]: ✅ Compatible / ⚠️ Possible / ❌ Incompatible

### Ecosystem and Support
**Vendor Information:**
- **Company Size/Stability:** [Assessment of vendor viability]
- **Market Presence:** [Market share, customer base, reputation]
- **Financial Health:** [Public/private, funding, revenue trends]

**Support and Community:**
- **Documentation Quality:** [Assessment of docs completeness and clarity]
- **Community Size:** [Developer community, user forums, activity level]
- **Training/Certification:** [Available learning resources]
- **Professional Services:** [Implementation and consulting support]

### Pricing and Licensing
**Pricing Structure:** [How pricing works - per user, usage, feature tiers]
**Licensing Model:** [Commercial license terms or open source license]
**Total Cost Factors:** [Implementation, training, operational costs]
**Enterprise Features:** [What's included in different pricing tiers]

### Initial Assessment
**Strengths:** [Top 3 advantages of this technology]
**Weaknesses:** [Top 3 limitations or concerns]
**Best Fit Scenarios:** [When this technology would be ideal choice]
**Red Flags:** [Potential deal-breakers or major concerns]
```
```

##### AI Response Capture
**Technology Options Inventory:**
```
[PASTE AI RESPONSE HERE]
```

##### Technology Options Validation
**Inventory Quality Review:**
- [ ] Comprehensive coverage of viable options
- [ ] Accurate and current information about each technology
- [ ] Clear differentiation between options
- [ ] Realistic assessment of requirements fit
- [ ] Useful vendor and ecosystem information

**Options Refinements:**
[Note any corrections or additions needed]

### Task 3: Requirements Mapping and Fit Analysis
**Objective:** Systematically evaluate how well each technology meets requirements

#### Requirements Fit Assessment Matrix

##### Functional Requirements Mapping
**Requirements Evaluation Matrix:**

| Technology | [Req 1] | [Req 2] | [Req 3] | [Req 4] | [Req 5] | Functional Score |
|------------|---------|---------|---------|---------|---------|------------------|
| [Tech 1] | ✅/⚠️/❌ | ✅/⚠️/❌ | ✅/⚠️/❌ | ✅/⚠️/❌ | ✅/⚠️/❌ | [Score/5] |
| [Tech 2] | ✅/⚠️/❌ | ✅/⚠️/❌ | ✅/⚠️/❌ | ✅/⚠️/❌ | ✅/⚠️/❌ | [Score/5] |
| [Tech 3] | ✅/⚠️/❌ | ✅/⚠️/❌ | ✅/⚠️/❌ | ✅/⚠️/❌ | ✅/⚠️/❌ | [Score/5] |

**Scoring Key:**
- ✅ **Fully Supported** (1.0 points): Native capability, no workarounds needed
- ⚠️ **Partially Supported** (0.5 points): Possible with configuration or workarounds
- ❌ **Not Supported** (0.0 points): Cannot meet this requirement

##### Non-Functional Requirements Assessment
**Performance and Scalability Fit:**

| Technology | Performance | Scalability | Reliability | Security | NFR Score |
|------------|-------------|-------------|-------------|----------|-----------|
| [Tech 1] | [Assessment] | [Assessment] | [Assessment] | [Assessment] | [Score/5] |
| [Tech 2] | [Assessment] | [Assessment] | [Assessment] | [Assessment] | [Score/5] |
| [Tech 3] | [Assessment] | [Assessment] | [Assessment] | [Assessment] | [Score/5] |

##### Constraints Compatibility Assessment
**Technical and Organizational Constraints:**

| Technology | Platform | Integration | Security | Skills | Constraints Score |
|------------|----------|-------------|----------|--------|-------------------|
| [Tech 1] | [Compatible/Issues] | [Easy/Complex] | [Compliant/Gaps] | [Available/Gap] | [Score/5] |
| [Tech 2] | [Compatible/Issues] | [Easy/Complex] | [Compliant/Gaps] | [Available/Gap] | [Score/5] |
| [Tech 3] | [Compatible/Issues] | [Easy/Complex] | [Compliant/Gaps] | [Available/Gap] | [Score/5] |

#### Requirements Gap Analysis
**Critical Gaps Identified:**
- **[Gap 1]:** [Requirement that no technology fully satisfies]
  - **Impact:** [How this affects the evaluation and potential solutions]
  - **Mitigation Options:** [Possible workarounds or alternative approaches]

- **[Gap 2]:** [Requirement that few technologies satisfy well]
  - **Impact:** [How this affects the evaluation and potential solutions]
  - **Mitigation Options:** [Possible workarounds or alternative approaches]

**Requirements Conflicts:**
- **[Conflict 1]:** [Requirements that conflict with each other]
  - **Trade-off Decision:** [How to handle this conflict]
- **[Conflict 2]:** [Requirements that conflict with constraints]
  - **Resolution Approach:** [How to resolve this conflict]

### Task 4: Ecosystem and Vendor Analysis
**Objective:** Assess vendor health, community support, and ecosystem maturity

#### Vendor Health Assessment

##### AI Prompt for Vendor Analysis
```markdown
**Context:** Analyze vendor ecosystem health for shortlisted technologies.

**Technologies to Analyze:** [LIST_OF_TOP_TECHNOLOGIES_FROM_REQUIREMENTS_FIT]

**Vendor Assessment Framework:**
1. **Financial Stability:** Company health, funding, revenue trends
2. **Market Position:** Market share, competitive positioning, customer base
3. **Product Roadmap:** Development velocity, feature roadmap, innovation
4. **Support Quality:** Support options, SLA, response quality
5. **Community Health:** Developer community, user forums, contribution activity
6. **Strategic Direction:** Vision, partnerships, acquisition risk

**Output Format:**
For each technology's vendor/provider:
```
## [Technology Name] - [Vendor Name]
### Company Profile
**Company Type:** [Public/Private/Open Source Foundation/Startup]
**Founded:** [Year and brief history]
**Size:** [Employee count, revenue if available]
**Funding:** [Venture capital, IPO status, financial health indicators]

### Market Position
**Market Share:** [Position in the technology category]
**Customer Base:** [Types and number of customers]
**Competitive Position:** [Strengths vs. competitors]
**Brand Recognition:** [Market awareness and reputation]

### Product and Innovation
**Development Activity:** [Release frequency, feature velocity]
**R&D Investment:** [Innovation focus and investment level]
**Product Roadmap:** [Publicly available roadmap clarity and ambition]
**Technology Leadership:** [Innovation vs. following market trends]

### Support and Services
**Support Tiers:** [Available support options and pricing]
**SLA Commitments:** [Response time and resolution commitments]
**Professional Services:** [Implementation, consulting, training services]
**Partner Ecosystem:** [Integration and implementation partners]

### Community and Ecosystem
**Developer Community:** [Size, activity, contribution level]
**Documentation:** [Quality, completeness, maintenance]
**Training Resources:** [Available learning materials and certification]
**Third-party Ecosystem:** [Plugins, extensions, integrations available]

### Risk Assessment
**Financial Risk:** [Risk of company failure or acquisition]
**Technology Risk:** [Risk of technology becoming obsolete]
**Support Risk:** [Risk of losing support or service quality]
**Strategic Risk:** [Risk of strategic direction changes affecting customers]

### Overall Vendor Score
**Strengths:** [Top 3 vendor advantages]
**Concerns:** [Top 3 vendor risks or weaknesses]
**Recommendation:** [Suitable for enterprise/mid-market/startup use]
```
```

##### AI Response Capture
**Vendor Ecosystem Analysis:**
```
[PASTE AI RESPONSE HERE]
```

##### Vendor Analysis Validation
**Vendor Assessment Quality:**
- [ ] Comprehensive vendor information gathered
- [ ] Realistic assessment of vendor health and risks
- [ ] Clear identification of support and service quality
- [ ] Useful insights about community and ecosystem
- [ ] Actionable risk assessment for each vendor

### Task 5: Technology Shortlisting and Prioritization
**Objective:** Create final shortlist of 2-4 technologies for hands-on evaluation

#### Preliminary Scoring and Ranking

##### Evaluation Framework Application
**Apply Stage 1 Evaluation Framework:**

| Technology | Functional Fit | Performance | Integration | Maturity | Cost | Risk | **Weighted Score** |
|------------|---------------|-------------|-------------|----------|------|------|-------------------|
| | (X% weight) | (X% weight) | (X% weight) | (X% weight) | (X% weight) | (X% weight) | |
| [Tech 1] | [Score/5] | [Score/5] | [Score/5] | [Score/5] | [Score/5] | [Score/5] | **[X.X/5]** |
| [Tech 2] | [Score/5] | [Score/5] | [Score/5] | [Score/5] | [Score/5] | [Score/5] | **[X.X/5]** |
| [Tech 3] | [Score/5] | [Score/5] | [Score/5] | [Score/5] | [Score/5] | [Score/5] | **[X.X/5]** |
| [Tech 4] | [Score/5] | [Score/5] | [Score/5] | [Score/5] | [Score/5] | [Score/5] | **[X.X/5]** |

**Scoring Notes:**
- **Functional Fit:** [Based on requirements mapping results]
- **Performance:** [Based on documented capabilities and benchmarks]
- **Integration:** [Based on API quality and integration complexity]
- **Maturity:** [Based on vendor analysis and market position]
- **Cost:** [Based on pricing model and total cost estimates]
- **Risk:** [Based on vendor risk and technology risk assessment]

#### Shortlist Development

##### Top Candidates Selection
**Primary Candidates (Recommended for Full Evaluation):**

##### Candidate 1: [Technology Name]
**Overall Score:** [X.X/5]
**Ranking:** #1

**Rationale for Inclusion:**
- **Strength 1:** [Specific advantage that makes this a top candidate]
- **Strength 2:** [Specific advantage that makes this a top candidate]
- **Strength 3:** [Specific advantage that makes this a top candidate]

**Key Validation Priorities for Stage 3:**
- **Priority 1:** [Critical capability to validate through hands-on testing]
- **Priority 2:** [Integration or performance concern to resolve]
- **Priority 3:** [Organizational fit factor to assess]

**Expected Evaluation Outcome:** [ADOPT/TRIAL/AVOID - predicted result with confidence level]

**Red Flags to Monitor:**
- **Flag 1:** [Specific concern to watch during hands-on evaluation]
- **Flag 2:** [Potential deal-breaker to validate]

##### Candidate 2: [Technology Name]
**Overall Score:** [X.X/5]
**Ranking:** #2

[Same detailed format as Candidate 1]

##### Candidate 3: [Technology Name] (if applicable)
**Overall Score:** [X.X/5]
**Ranking:** #3

[Same detailed format as Candidate 1]

##### Secondary Candidates (Conditional Evaluation)
**[Technology Name]:** 
- **Condition for Evaluation:** [Under what circumstances this should be evaluated]
- **Key Differentiator:** [What makes this potentially valuable despite lower ranking]

#### Exclusion Rationale

##### Technologies Excluded from Evaluation
**[Technology Name] - Excluded Due to [Primary Reason]**
- **Exclusion Rationale:** [Specific reasons this technology was not shortlisted]
- **Score:** [X.X/5]
- **Deal-breaker Factor:** [Primary factor that eliminated this option]
- **Reconsideration Triggers:** [What would change to make this viable in future]

**[Technology Name] - Excluded Due to [Primary Reason]**
[Same format as above]

### Task 6: Stage 3 Evaluation Strategy
**Objective:** Plan hands-on evaluation approach for shortlisted technologies

#### Evaluation Approach Planning

##### Evaluation Methodology
**Evaluation Strategy:** [Approach for Stage 3 hands-on testing]
- [ ] Sequential evaluation (one technology at a time)
- [ ] Parallel evaluation (multiple technologies simultaneously)
- [ ] Comparative evaluation (direct feature-by-feature comparison)
- [ ] Scenario-based evaluation (common use cases across all technologies)

**Evaluation Order and Rationale:**
1. **[Technology 1]:** [Why to evaluate this first]
2. **[Technology 2]:** [Why to evaluate this second]
3. **[Technology 3]:** [Why to evaluate this third, if applicable]

##### Evaluation Scenarios
**Common Test Scenarios:** [Scenarios to run across all technologies for comparison]
- **Scenario 1:** [Realistic use case that tests core functionality]
  - **Setup Requirements:** [What's needed to test this scenario]
  - **Success Criteria:** [How to measure success for this scenario]
  - **Validation Method:** [How to verify results]

- **Scenario 2:** [Integration or performance test scenario]
  - **Setup Requirements:** [What's needed to test this scenario]
  - **Success Criteria:** [How to measure success for this scenario]
  - **Validation Method:** [How to verify results]

- **Scenario 3:** [User experience or operational test scenario]
  - **Setup Requirements:** [What's needed to test this scenario]
  - **Success Criteria:** [How to measure success for this scenario]
  - **Validation Method:** [How to verify results]

##### Resource Requirements for Stage 3
**Environment and Setup:**
- **Testing Environment:** [Infrastructure needed for hands-on evaluation]
- **Data Requirements:** [Test data or datasets needed]
- **Tool Access:** [Trial licenses, accounts, or access needed]
- **Integration Points:** [Systems needed for integration testing]

**Time and Effort:**
- **Total Evaluation Time:** [Estimated person-hours for Stage 3]
- **Per-Technology Time:** [Time allocation per technology]
- **Team Involvement:** [Who needs to participate in hands-on testing]

## Stage Completion

### Deliverables Checklist
- [ ] **Technology Landscape Analysis:** Comprehensive market and vendor research
- [ ] **Technology Options Inventory:** Complete list of viable technology alternatives
- [ ] **Requirements Fit Analysis:** Systematic evaluation of requirements alignment
- [ ] **Vendor Ecosystem Assessment:** Health and risk analysis of key vendors
- [ ] **Technology Shortlist:** 2-4 technologies recommended for hands-on evaluation
- [ ] **Stage 3 Evaluation Plan:** Strategy and resource requirements for next stage

### Quality Validation
**Research Quality:**
- [ ] Comprehensive coverage of technology landscape without major omissions
- [ ] Current and accurate information about technologies and vendors
- [ ] Objective analysis based on stated requirements and constraints
- [ ] Clear rationale for shortlist inclusion and exclusion decisions

**Analysis Quality:**
- [ ] Requirements fit analysis is systematic and consistent
- [ ] Vendor risk assessment is realistic and actionable
- [ ] Scoring methodology is applied consistently across all options
- [ ] Shortlist represents genuine alternatives worth detailed evaluation

**Strategic Alignment:**
- [ ] Shortlisted technologies align with organizational constraints and priorities
- [ ] Evaluation plan is executable within available time and resources
- [ ] Expected outcomes are realistic based on preliminary analysis

### Risk Assessment
**Investigation Stage Risks:**
- **Information Quality Risk:** [Risk that research information is outdated or inaccurate]
  - **Mitigation:** [Verify key information through multiple sources]
- **Analysis Bias Risk:** [Risk that analysis favors particular solutions]
  - **Mitigation:** [Use consistent evaluation criteria and seek diverse perspectives]
- **Shortlist Risk:** [Risk that shortlist excludes viable alternatives]
  - **Mitigation:** [Document exclusion rationale and reconsideration triggers]

### Stakeholder Communication
**Stage 2 Results Summary:**
- **Technologies Researched:** [Total number of options investigated]
- **Shortlist Recommendations:** [Final shortlist with brief rationale]
- **Key Findings:** [Important insights from landscape research]
- **Stage 3 Plan:** [Approach and timeline for hands-on evaluation]

**Stakeholder Review Requirements:**
- [ ] Business stakeholders review and approve shortlist
- [ ] Technical team confirms evaluation approach and resource requirements
- [ ] Decision makers understand evaluation rationale and next steps

### Next Steps Planning
**Stage 3 Preparation:**
- [ ] Evaluation environment setup requirements identified
- [ ] Trial access and tool requirements documented
- [ ] Test scenarios and validation approaches defined
- [ ] Team assignments and timeline confirmed

**Immediate Actions (Next 1-2 Days):**
- [Action 1: Specific preparation task, owner, deadline]
- [Action 2: Specific preparation task, owner, deadline]
- [Action 3: Specific preparation task, owner, deadline]

## Notes and Observations
[Space for insights, unexpected findings, or important considerations discovered during investigation]

---

*This stage should take 2-4 hours depending on technology category complexity. Focus on creating a manageable shortlist for hands-on evaluation rather than exhaustive analysis. The goal is identifying the most promising candidates for practical validation, not perfect market research.*
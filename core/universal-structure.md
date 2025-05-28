# Universal Structure

The foundation architecture that all AI workflows follow. This structure ensures consistency, predictable AI handoffs, and systematic progress tracking across different project types.

## 🏗️ Architecture Overview

```
Phase → High-Level Goal → AI Prompt → Tasks → Tickets → Checkpoints
```

Every workflow follows this hierarchy:
- **Phases** provide strategic direction and major milestones
- **Tasks** break phases into manageable work units  
- **Tickets** make tasks executable with clear AI collaboration
- **Checkpoints** validate progress and trigger human review

## 📋 Phase Structure

### Phase Template
```yaml
Phase Name: [Clear Strategic Objective]
Duration: [Time estimate] 
Purpose: [What this phase achieves in the larger workflow]

High-Level Goal: 
  - Primary objective in 1-2 sentences
  - Success criteria for phase completion
  - Key deliverable(s)

AI Agent Context:
  - Role/persona for AI to adopt
  - Domain knowledge to apply
  - Expected output format

Entry Criteria:
  - What must be complete before starting
  - Required inputs or dependencies

Exit Criteria:
  - Specific deliverables that must exist
  - Quality gates that must be passed
  - Decision points or approvals needed
```

### Standard Phases (Adapt as Needed)

**Phase 1: Problem Discovery**
- **Purpose:** Define what you're solving before proposing solutions
- **Output:** Problem statement, opportunity brief, or investigation scope
- **AI Role:** Research analyst, domain expert, strategic thinker

**Phase 2: Spike/Investigation** 
- **Purpose:** Time-boxed research to reduce uncertainty and risk
- **Output:** Findings, recommendations, feasibility assessment
- **AI Role:** Technical investigator, solution architect, researcher

**Phase 3: Specification**
- **Purpose:** Design the solution architecture and approach
- **Output:** Technical spec, system design, implementation plan
- **AI Role:** System architect, technical writer, design reviewer

**Phase 4: Ticket Planning**
- **Purpose:** Break specification into executable work items
- **Output:** Structured task list, implementation roadmap, estimates
- **AI Role:** Project planner, task breakdown specialist, estimator

**Phase 5: Implementation**
- **Purpose:** Build, test, and deliver the solution
- **Output:** Working software, documentation, deployment artifacts
- **AI Role:** Coding assistant, test generator, documentation writer

## 🎯 Task Generation

### AI-Driven Task Creation
Each phase uses AI to generate specific tasks based on the high-level goal:

```markdown
**AI Task Generation Prompt Template:**
"Based on the phase goal: [GOAL]
And the current context: [CONTEXT]
Generate 3-7 specific tasks that will achieve this goal.

Each task should:
- Be completable in 2-6 hours 
- Have a clear deliverable
- Build toward the phase objective
- Be suitable for AI-assisted execution

Format each task as:
- Task Name: [Action-oriented title]
- Purpose: [What this accomplishes]
- Deliverable: [Specific output]
- Complexity: [Simple/Medium/Complex]"
```

### Task Validation Criteria
Generated tasks must meet these standards:
- **Atomic:** Single responsibility, clear scope
- **Achievable:** Realistic given time and resources
- **Measurable:** Objective completion criteria
- **Relevant:** Directly contributes to phase goal
- **Time-boxed:** Estimated duration under 1 day

## 🎫 Ticket Format

### Universal Ticket Template
```yaml
TICKET-ID: [WORKFLOW]-[PHASE]-[SEQUENCE]
# Example: RESEARCH-DISCOVERY-001

Title: [Action-oriented description]
# Example: "Analyze paper's core algorithm for implementation feasibility"

Context: |
  Background information the AI agent needs:
  - Current project state
  - Relevant domain knowledge  
  - Connection to larger goal

AI Agent Instructions: |
  Specific prompts and collaboration guidance:
  - Primary prompt to use
  - Expected output format
  - Quality standards
  - Collaboration style (generate vs validate vs iterate)

Acceptance Criteria:
  - [ ] Specific, testable outcome 1
  - [ ] Specific, testable outcome 2
  - [ ] Specific, testable outcome 3

Checkpoints:
  - Checkpoint 1: [Validation point during work]
    - Method: [How to validate]
    - Trigger: [When to check]
  - Checkpoint 2: [Mid-progress validation]
  - Final Review: [Human validation before completion]

Definition of Done:
  - [ ] All acceptance criteria met
  - [ ] All checkpoints passed
  - [ ] Deliverable reviewed and approved
  - [ ] Next task dependencies satisfied

Dependencies:
  - Input: [What this task needs to start]
  - Output: [What this task produces for others]
  - Blockers: [Potential impediments]

Metadata:
  - Estimated Duration: [Time estimate]
  - Complexity: [Simple/Medium/Complex]
  - AI Collaboration Level: [High/Medium/Low]
  - Human Review Required: [Yes/No/Conditional]
```

### Ticket Types by AI Collaboration Level

**High AI Collaboration (Code Generation, Analysis)**
```yaml
AI Agent Instructions: |
  Generate [specific output type] using this prompt:
  "[Detailed prompt with context and requirements]"
  
  Expected format: [Structure/template]
  Quality standards: [Specific criteria]
  Validation method: [How to verify correctness]

Checkpoints:
  - AI Self-Assessment: Agent evaluates its own output
  - Logic Review: Verify reasoning and approach
  - Integration Check: Ensure compatibility with existing work
```

**Medium AI Collaboration (Planning, Documentation)**
```yaml
AI Agent Instructions: |
  Assist with [task type] by:
  1. [Specific helper function]
  2. [Validation or feedback role]
  3. [Iteration suggestions]
  
  Human leads: [What human controls]
  AI supports: [How AI helps]

Checkpoints:
  - Draft Review: AI feedback on human-created content
  - Completeness Check: AI verifies all requirements covered
  - Quality Gate: Human final approval with AI input
```

**Low AI Collaboration (Research, Decision-Making)**
```yaml
AI Agent Instructions: |
  Provide research support:
  - Gather information on [specific topics]
  - Summarize findings in [format]
  - Highlight potential issues or considerations
  
  Final decisions made by: Human
  AI role: Information provider and advisor

Checkpoints:
  - Information Gathering: Verify AI research quality
  - Analysis Review: Human validates AI summaries
  - Decision Rationale: Document reasoning (human-led)
```

## ✅ Checkpoint System

### Checkpoint Types

**Self-Assessment Checkpoints (AI-Driven)**
```yaml
Checkpoint Name: AI Self-Evaluation
Trigger: After AI completes initial output
Method: |
  AI evaluates its own work against criteria:
  - Completeness: "Did I address all requirements?"
  - Quality: "Does this meet the stated standards?"
  - Consistency: "Is this aligned with project context?"
  - Next Steps: "What should happen next?"
```

**Validation Checkpoints (Human-Triggered)**
```yaml
Checkpoint Name: Human Review Gate
Trigger: [Specific condition or milestone]
Method: |
  Human validates:
  - Correctness of AI output
  - Alignment with project goals
  - Quality and completeness
  - Need for iteration or approval
Decision: [Continue/Iterate/Escalate]
```

**Integration Checkpoints (System-Level)**
```yaml
Checkpoint Name: Compatibility Verification
Trigger: Before output becomes input to next task
Method: |
  Verify:
  - Output format matches next task expectations
  - Dependencies are satisfied
  - No conflicts with existing work
  - Documentation is complete
```

### Checkpoint Decision Framework
```yaml
Pass Criteria:
  - All acceptance criteria met
  - Quality standards achieved
  - Dependencies satisfied
  - Documentation complete

Iterate Criteria:
  - Minor gaps or improvements needed
  - Feedback can be addressed quickly
  - Core approach is sound

Escalate Criteria:
  - Fundamental issues with approach
  - Requirements misunderstood
  - Major dependencies missing
  - Quality significantly below standard
```

## 🔄 Workflow Execution Patterns

### Linear Execution (Standard)
```
Phase 1 → Phase 2 → Phase 3 → Phase 4 → Phase 5
   ↓        ↓        ↓        ↓        ↓
 Tasks → Tasks → Tasks → Tasks → Tasks
   ↓        ↓        ↓        ↓        ↓
Tickets→ Tickets→ Tickets→ Tickets→ Tickets
```

### Iterative Execution (Complex Projects)
```
Phase 1 → Phase 2 ──→ Phase 3 ──→ Phase 4 ──→ Phase 5
   ↓        ↓    ↙      ↓    ↙      ↓    ↙      ↓
 Tasks    Tasks ← Iterate ← Tasks ← Review ← Tasks
   ↓        ↓             ↓           ↓        ↓
Tickets  Tickets       Tickets    Tickets  Tickets
```

### Parallel Execution (Independent Workstreams)
```
Phase 1 → Phase 2 ──┬→ Phase 3A → Phase 4A ──┐
   ↓        ↓       │     ↓          ↓      │
 Tasks    Tasks     └→ Phase 3B → Phase 4B ──┤→ Phase 5
   ↓        ↓           ↓          ↓      │     ↓
Tickets  Tickets     Tasks      Tasks    └→  Tasks
                        ↓          ↓           ↓
                     Tickets    Tickets    Tickets
```

## 📊 Progress Tracking

### Phase-Level Metrics
- **Completion:** Percentage of tasks completed
- **Quality:** Checkpoints passed vs. total checkpoints
- **Timeline:** Actual vs. estimated duration
- **AI Efficiency:** Tasks where AI collaboration was effective

### Task-Level Metrics
- **Cycle Time:** Start to completion duration
- **Iteration Count:** Number of checkpoint iterations
- **AI Contribution:** Level of AI assistance used
- **Human Review Time:** Time spent on validation

### Workflow-Level Metrics  
- **End-to-End Duration:** Problem discovery to working solution
- **Success Rate:** Projects completed vs. abandoned
- **Learning Velocity:** Time to proficiency improvement
- **Pattern Recognition:** Reusable solutions identified

## 🔧 Customization Guidelines

### When to Modify the Structure
- **Add Phases:** For domain-specific requirements (e.g., compliance review)
- **Modify Checkpoints:** Based on risk tolerance and quality needs
- **Adjust AI Collaboration:** Based on team AI maturity and tool capabilities
- **Change Ticket Format:** To match existing project management tools

### What to Keep Constant
- **Phase → Task → Ticket hierarchy**
- **AI collaboration at ticket level**
- **Checkpoint validation system**
- **Clear entry/exit criteria**

### Adaptation Examples
```yaml
# High-Risk Project
Additional Checkpoints:
  - Security Review (after each phase)
  - Compliance Validation (before implementation)
  - Stakeholder Approval (at major milestones)

# Experimental Project  
Modified Structure:
  - Expanded Spike Phase (more investigation time)
  - Shortened Specification (lighter planning)
  - Continuous Integration (merge phases 4-5)

# Team Collaboration
Enhanced Coordination:
  - Cross-team checkpoints
  - Shared AI context
  - Integrated review cycles
```
# AI Workflows

A systematic approach to building, evaluating, and prototyping with AI assistance. These workflows combine structured methodologies with AI collaboration to accelerate learning and execution across three core domains.

## 🎯 What This Repository Contains

**Three Specialized AI-Assisted Workflows:**
- **[Research Paper → POC](workflows/research-paper-poc/)** - Transform academic papers into working prototypes
- **[Technology Evaluation](workflows/tech-evaluation/)** - Systematically assess and integrate new technologies  
- **[MVP/POC Builder](workflows/mvp-builder/)** - Rapid prototype development for product concepts

**Core Framework:**
- **[LSC (Looped Skill Compression)](core/lsc-framework.md)** - Meta-learning framework for fast skill acquisition
- **[Universal Structure](core/universal-structure.md)** - Phase → Task → Ticket → Checkpoint architecture
- **[AI Agent Instructions](core/ai-agent-instructions.md)** - Collaboration patterns with AI coding assistants

## 🚀 Quick Start

### Starting a New Project

1. **Choose your workflow:**
   ```bash
   # Research paper implementation
   cp -r templates/research-paper-poc projects/my-paper-poc
   
   # Technology evaluation  
   cp -r templates/tech-evaluation projects/neo4j-evaluation
   
   # MVP development
   cp -r templates/mvp-builder projects/my-app-mvp
   ```

2. **Navigate to your project:**
   ```bash
   cd projects/my-project-name
   ```

3. **Follow the workflow phases:**
   - Each workflow has 5 phases with clear deliverables
   - Use AI prompts provided in templates
   - Track progress through structured tickets

### Example Usage
```bash
# Clone the repository
git clone <repo-url>
cd ai-workflows

# Start a research paper POC
cp -r workflows/research-paper-poc/templates projects/transformer-attention-poc
cd projects/transformer-attention-poc

# Follow Phase 1: Problem Discovery
# Edit phase-1-discovery.md with your paper analysis
# Generate tickets using provided AI prompts
# Execute with AI coding assistance
```

## 📋 Workflow Architecture

Each workflow follows the same universal structure:

```
Phase → High-Level Goal → AI Prompt → Tasks → Tickets → Checkpoints
```

### Universal Phases
1. **Problem Discovery** - Define what you're solving and why
2. **Spike/Investigation** - Time-boxed research and feasibility  
3. **Specification** - Technical design and architecture
4. **Ticket Planning** - Break down into executable tasks
5. **Implementation** - Build with AI assistance and track progress

### Ticket Format
Every task follows a structured format optimized for AI collaboration:
- **Context:** Background for AI agents
- **AI Instructions:** Specific prompts and expected outputs
- **Acceptance Criteria:** Clear success metrics
- **Checkpoints:** Validation points during execution
- **Definition of Done:** Objective completion criteria

## 🧠 AI Integration

### Supported AI Tools
- **Coding Assistants:** GitHub Copilot, Cursor, Claude
- **Analysis & Planning:** ChatGPT, Claude, Perplexity
- **Specialized Tasks:** Research tools, documentation generators

### Collaboration Patterns
- **Phase-Level:** AI helps with strategic planning and analysis
- **Task-Level:** AI generates implementation approaches
- **Ticket-Level:** AI provides code, tests, and documentation
- **Checkpoint-Level:** AI validates progress and suggests improvements

## 📁 Directory Structure

```
ai-workflows/
├── core/                    # Foundational frameworks
│   ├── lsc-framework.md     # Learning methodology
│   ├── universal-structure.md
│   └── ai-agent-instructions.md
├── workflows/               # Complete workflow implementations
│   ├── research-paper-poc/
│   ├── tech-evaluation/
│   └── mvp-builder/
├── templates/               # Reusable components
│   ├── tickets/
│   ├── prompts/
│   └── checkpoints/
├── projects/                # Active and completed projects
│   └── [project-instances]/
└── docs/                    # Documentation and patterns
    ├── pattern-library.md
    ├── decision-log.md
    └── retrospectives.md
```

## 🎯 Success Metrics

**Good Workflow Execution:**
- ✅ Clear problem definition before solution design
- ✅ Time-boxed phases with concrete deliverables  
- ✅ AI-generated tasks validated by human checkpoints
- ✅ Working prototype or clear decision within planned timeframe
- ✅ Documented lessons learned for future iterations

**Workflow Evolution:**
- Track what works/doesn't work in [retrospectives](docs/retrospectives.md)
- Update templates based on real project outcomes
- Build [pattern library](docs/pattern-library.md) of reusable solutions
- Refine AI prompts for better collaboration

## 🔗 Related Resources

- **[Looped Skill Compression](core/lsc-framework.md)** - The meta-learning approach behind these workflows
- **[Pattern Library](docs/pattern-library.md)** - Reusable solutions discovered through workflow execution
- **[Decision Log](docs/decision-log.md)** - Why certain workflow design choices were made
- **[Examples](projects/)** - Real project implementations using these workflows

---

*These workflows are designed to be adapted, not followed blindly. Use your judgment to scale phases up or down based on project complexity and risk.*
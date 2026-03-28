# Product Framing Skill

A systematic questioning framework that helps you uncover and structure product requirements before writing any code.

## Core Philosophy

> "What you don't ask, you don't get."

Before starting a product or feature, many requirements are vague. This skill uses six phases of guided questioning to help you discover the complete picture of what you're building.

## Six Discovery Phases

```
Phase 1: Business Context    → What problem does this product solve?
Phase 2: Roles & Permissions → Who will use it? How is access controlled?
Phase 3: Core Modules        → What features exist? How do they relate?
Phase 4: Data Model          → What data needs managing? What are the relationships?
Phase 5: Boundaries & Integration → What external systems? Scale requirements?
Phase 6: Acceptance Criteria → How do we define success?
```

## Quick Start

### When to Use

- Starting a new product or major feature
- Requirements are vague or incomplete
- Transitioning from idea to implementation
- Need to align stakeholders on scope

### When NOT to Use

- Requirements are already fully documented
- User explicitly wants implementation only
- Simple bug fix or minor feature

## Usage

In Claude Code, simply type:

```
/product-framing
```

The AI will guide you through all six phases with targeted questions.

## Example Conversation

**User**: "I want to build an inventory management system"

**AI (using this skill)**:

> Great, let's work through this systematically. Starting with Phase 1:
>
> **Phase 1 - Business Context:**
> 1. What does this inventory management system do? What problem does it solve?
> 2. What industry/domain is this for?
> 3. What core business processes need managing? (Purchasing? Sales? Manufacturing?)
> 4. Who are the target users? Warehouse staff? Finance? Procurement?

[Continues through all phases]

## Checklist

```
□ Product Background: What problem does it solve?
□ Target Users: Who will use it? How many users?
□ Core Modules: Module list and relationships
□ Roles & Permissions: At least 3 key roles
□ Business Flows: Critical process diagrams
□ Data Entities: Core table structures
□ Integration Needs: External system connections
□ Boundaries: Scale/performance/concurrency
□ Acceptance Criteria: Launch checklist
□ Risks: Known risks and mitigations
```

## Common Mistakes

| Mistake | Why It Matters |
|---------|----------------|
| Skipping Phase 1 and jumping to feature lists | No sense of direction; decisions drift from core value |
| Not asking about boundaries | Performance/scale issues discovered after launch |
| Not confirming roles/permissions | Permission conflicts discovered mid-development |
| Not defining acceptance criteria | Misaligned expectations at delivery |

## Repository Structure

```
product-framing/
├── SKILL.md      # Skill definition file
└── README.md     # This documentation
```

## License

MIT

# Hartwell Pet Daycare & Boarding — Claude Code Setup

## Project Overview

**Project Name:** Hartwell Pet Daycare & Boarding
**Project Type:** Service Business
**Description:** A pet daycare and boarding service for active, playful dogs and pets

This is a Claude Code project with automated agents, commands, and skills for building and scaling your business.

---

## Available Tools & Commands

### Commands (Quick Workflows)

Available commands for common tasks:

- `/start-phase` — Initialize a new development phase with structured planning
- `/end-session` — Document session work and update all context files
- `/status` — Display current project state, progress, and next steps
- `/review-architecture` — Perform comprehensive architecture review
- `/reflect` — Analyze session and propose improvements to skills

### Agents (Specialized Subagents)

Available agents for complex, multi-step tasks (launched automatically):

- **Content Analyzer** — Analyze content trends and opportunities
- **SEO Auditor** — Technical and on-page SEO analysis
- **Keyword Extractor** — Keyword research and opportunity identification
- **Competitor Analyzer** — Competitive intelligence gathering
- **Data Analyzer** — Market intelligence extraction from sources
- **Report Writer** — Executive-level deliverables and documentation
- **Research Coordinator** — Multi-source research and synthesis
- **Market Researcher** — Competitive analysis and opportunity assessment

### Skills (Extended Capabilities)

Available skills for specialized work:

- **frontend-design** — Create production-grade web interfaces and components
- **doc-coauthoring** — Structured workflow for writing documentation
- **xlsx** — Spreadsheet creation, editing, and data analysis
- **pdf** — PDF manipulation and form filling
- **pptx** — Presentation creation and editing
- **web-artifacts-builder** — Complex HTML/React artifacts with state management

---

## Project Structure

```
hartwellpetdaycare/
├── context/
│   └── core/
│       ├── business-profile.json       (Business overview & positioning)
│       ├── voice-dna.json              (Brand voice & messaging)
│       └── icp.json                    (Ideal client profiles)
├── knowledge/
│   ├── drafts/                         (Work in progress)
│   ├── published/                      (Finalized content)
│   ├── notes/                          (Research & ideas)
│   └── research/                       (Detailed research docs)
├── .claude/
│   ├── agents/                         (Specialized subagents)
│   ├── commands/                       (Workflow automation)
│   ├── skills/                         (Extended capabilities)
│   └── config.json                     (Claude Code configuration)
└── CLAUDE.md                           (This file)
```

---

## Getting Started

### 1. Complete Your Profiles

Start by filling out these key files in `context/core/`:

- **business-profile.json** — Define your business overview, positioning, and services
- **voice-dna.json** — Document your brand voice and communication style
- **icp.json** — Create ideal client personas with pain points and goals

These files guide all subsequent decisions and content creation.

### 2. Initialize Your First Phase

Use `/start-phase` to begin your first development phase with:
- Interactive phase goal definition
- Structured task planning
- Documentation generation
- Progress tracking

### 3. Build & Scale

Use available commands and agents to:
- Plan architecture and features (`/start-phase`)
- Create content and documentation (`/doc-coauthoring`, `doc-coauthoring` skill)
- Analyze performance and market (`agents`)
- Review progress (`/status`, `/review-architecture`)

---

## Key Files

### Context Files

- **business-profile.json** — Business positioning, offerings, and operations
- **voice-dna.json** — Brand personality, values, and communication style
- **icp.json** — Ideal client profiles with demographics and psychographics

### Knowledge Management

- **knowledge/drafts/** — Work in progress, ideas, and early drafts
- **knowledge/published/** — Finalized, ready-to-use content
- **knowledge/notes/** — Quick notes, research findings, and ideas
- **knowledge/research/** — Detailed research documents and reports

---

## Workflow Recommendations

### For Planning Work

1. Run `/status` to see current project state
2. Use `/start-phase` to initialize a development phase
3. Use `superpowers:writing-plans` skill to create detailed plans
4. Execute plans with structured progress tracking

### For Content & Documentation

1. Use `doc-coauthoring` skill for collaborative writing
2. Store drafts in `knowledge/drafts/`
3. Move polished content to `knowledge/published/`
4. Reference in business profiles and documentation

### For Design & Frontend

1. Use `frontend-design` skill for web components and pages
2. Create production-grade interfaces with design quality
3. Reference design system standards and patterns

### For Session Management

1. At start: Run `/status` to understand current context
2. During work: Use `/add-todo` to capture new tasks or ideas
3. At end: Run `/end-session` to document progress and update files

---

## Quick Command Reference

```bash
# View project status
/status

# Start a new development phase
/start-phase

# End your work session with documentation
/end-session

# Review project architecture
/review-architecture

# Analyze and improve a skill
/reflect [skill-name]
```

---

## Important Notes

- **All profiles** in `context/core/` should be filled out before starting major work
- **Changes are documented** — Use `/end-session` to record all work and updates
- **Agents work autonomously** — They handle complex, multi-step tasks automatically
- **Flexibility first** — Adapt workflows to your needs; this setup is a starting point

---

## Questions?

Refer to the `/help` command in Claude Code for more information about tools, shortcuts, and workflows.

**Last Updated:** 2026-02-10
**Setup Version:** 1.0


<claude-mem-context>
# Recent Activity

<!-- This section is auto-generated by claude-mem. Edit content outside the tags. -->

*No recent activity*
</claude-mem-context>
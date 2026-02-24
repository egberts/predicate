# Project Structure Overview

This document outlines the directory structure for the project, including the roles and purpose of each folder.

---

## Directory Tree

```plaintext
predicate/
├── axioms/      # Foundational rulesets (always active)
├── personas/    # Context-specific extensions (opt-in)
├── workflows/   # Manually-triggered SOPs
├── templates/   # Project templates (AGENTS.md, PLAN.md, etc.)
└── docs/        # Guides, plans, ADRs, and formal models

---

## Root Directories

- **`predicate/`**
  The main project folder, containing all foundational logic and tools for agents.

---

### Directories

1. **`axioms/`**
   - **Description:** Contains foundational rulesets that are always active and cannot be turned off.
   - **Purpose:** These are your project's core principles, rules, or constants.
   - **Example Files:**
     - `axiom_rule_1.md`
     - `core_logic.py`

2. **`personas/`**
   - **Description:** Contains context-specific extensions. These are optional additions that can be enabled or disabled depending on the task at hand.
   - **Purpose:** Defines specialized roles or agents with specific behaviors.
   - **Example Files:**
     - `persona_chatbot.md`
     - `persona_assistant.py`
 
3. **`workflows/`**
   - **Description:** Holds manually-triggered Standard Operating Procedures (SOPs) for automation or step-by-step guides.
   - **Purpose:** Contains task-driven processes or instructions that can be executed as workflows.
   - **Example Files:**
     - `workflow_start_project.md`
     - `data_processing.py`

4. **`templates/`**
   - **Description:** Holds reusable project templates, documentation, and predefined plans.
   - **Purpose:** Defines basic templates for new agents or projects (e.g., planning documents).
   - **Example Files:**
     - `AGENTS.md`
     - `PLAN.md`

5. **`docs/`**
   - **Description:** Contains guides, plans, Architectural Decision Records (ADRs), and other formal models.
   - **Purpose:** Provides documentation and decision-making records for the project.
   - **Example Files:**
     - `ADR_001.md`
     - `project_overview.md`

---

## Diagram Representation

```plaintext
Your Project
     |
     V
   Axion
     |
     V
  Persona
     |
     V
  Workflow
```

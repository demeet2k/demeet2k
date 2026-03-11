# Multi‑Agent Communication & Operational Guidelines

This document proposes a structured way for *floating agents* to communicate and collaborate within your GitHub ecosystem.  It also defines global goals and rules of operation.  Use it as a living document to align all agents and human contributors.

## Purpose

The intent of these guidelines is to **foster clear communication, shared context, and coherent collaboration** across a team of specialized agents.  Multi‑agent research shows that distributing tasks among functionally distinct agents (a Planner, Coder, Mathematical agent, etc.) enables complex problem solving and reusable partial solutions【664016699785591†L119-L131】.  This document builds on that insight to organize your work on the “crystal” project.

## 1 Communication Structure

To coordinate many agents effectively, adopt a consistent structure for how information flows.  Each agent should clearly document its inputs, outputs, progress, and blockers.

- **Central message board** – Use **GitHub Issues** as the primary asynchronous communication channel.  Each issue represents a task or discussion topic.  Include a descriptive title, a summary of the task, related files, and a dimension label (e.g., `D1-Vision`, `D4-Code`).
- **Issue templates** – Create templates for common tasks (bug report, research task, design proposal) to ensure that all relevant information is captured from the start.  Templates might request problem description, expected outcome, dependencies, and dimension classification.
- **Labels & tags** – Label issues by dimension and by agent type (`Planner`, `Coder`, `Math`, `Researcher`, etc.).  This helps agents quickly filter tasks relevant to their specialization.
- **Weekly synchronization meetings** – Schedule short synchronous check‑ins (in chat or video) where agents summarize progress, raise blockers, and plan next steps.  Keep them concise and action‑oriented.
- **Documentation repository** – Maintain a `/docs` directory for design documents, mathematical derivations, and meeting notes.  Each document should clearly state:
  - **Context and objective**
  - **Inputs and outputs**
  - **Responsible agents**
  - **Dependencies**

## 2 Global Goals

1. **Grow the “crystal” into a multi‑dimensional structure.**  The project draws inspiration from quasicrystals, which are projections of high‑dimensional lattices into lower dimensions【537716418241369†L150-L159】.  Similarly, break down complex problems into orthogonal dimensions (vision, architecture, math, implementation, data, tooling, collaboration, safety, synergy) and ensure each dimension evolves coherently.
2. **Promote specialization with collaboration.**  Assign tasks to agents according to their strengths (planning, coding, math, research, etc.) while fostering cross‑agent communication.  Specialization improves efficiency【664016699785591†L119-L131】; collaboration ensures that partial solutions combine into coherent outcomes.
3. **Maintain high standards of safety and compliance.**  Use dedicated agents to enforce ethical guidelines and legal constraints, as suggested in multi‑agent frameworks【664016699785591†L238-L249】.
4. **Document and share knowledge.**  Every significant decision, assumption, or learning should be captured in issues, commit messages, or documentation files.  This transparency helps new agents ramp up quickly and prevents knowledge loss.
5. **Iterate and improve.**  Periodically review processes and adjust rules when inefficiencies or new requirements emerge.  Treat this document as a living artifact.

## 3 Operational Rules

1. **Clearly define tasks.**  An issue should specify what needs to be done, why it matters, and how success will be evaluated.  Avoid vague requests.
2. **Follow dimension labeling.**  Each task must include at least one dimension label.  If a task spans multiple dimensions, list all applicable labels.  This ensures that relevant agents are alerted.
3. **Provide context when handing off work.**  When one agent finishes a sub‑task, it should document all necessary details (e.g., input assumptions, output formats, potential pitfalls) for the next agent.
4. **Use pull requests for code changes.**  All code should be merged via pull requests.  Assign at least one reviewer (preferably an SWE agent) and ensure tests pass before merging.
5. **Respect safety constraints.**  The Compliance and Safety agents have authority to block or modify outputs that violate policies.  All agents must respond to their feedback promptly【664016699785591†L238-L249】.
6. **Time‑box tasks and report status.**  Set an estimated completion time for each issue.  If delays occur, update the issue with explanations and new estimates.  This helps the Planner agent manage dependencies.
7. **Use citations for external information.**  When an agent references external sources (papers, web pages), include citations or links for transparency.  For instance, cite quasicrystal projections【537716418241369†L150-L159】 or multi‑agent principles【664016699785591†L119-L131】.
8. **Encourage feedback and retrospectives.**  After completing a milestone, hold a retrospective discussion.  Document what went well, what needs improvement, and action items for future iterations.

## 4 Agent Roles Summary

Below is a brief reminder of specialized agent roles (details may evolve as your project grows):

- **Planner** – Decomposes high‑level goals into sub‑tasks, prioritizes work, and monitors progress【664016699785591†L182-L188】.
- **Coder** – Implements code according to specifications; collaborates with SWE on testing and refactoring【664016699785591†L190-L197】.
- **SWE (Software Engineer)** – Reviews code for quality, performance, and maintainability; oversees CI/CD pipelines【664016699785591†L218-L223】.
- **Math Agent** – Handles formal mathematics, optimization, and algorithm design【664016699785591†L224-L231】.
- **Researcher** – Retrieves and summarizes external information relevant to tasks【664016699785591†L207-L211】.
- **Architect** – Designs the overall system and data flow【664016699785591†L214-L217】.
- **Sync / Response Handler** – Coordinates communication between agents and aggregates partial results into final outputs【664016699785591†L199-L205】.
- **Compliance & Safety Agents** – Monitor adherence to ethical guidelines and legal constraints【664016699785591†L238-L249】.

## 5 Next Steps

1. **Create the `/docs` directory and add this guideline.**  Commit this document as `agent_communication_guidelines.md`.
2. **Draft issue templates and labels** in the GitHub repository.
3. **Define dimension labels** as described (e.g., `D1-Vision`, `D2-Architecture`, etc.).
4. **Set up a regular cadence** for sync meetings and retrospectives.
5. **Assign roles** to the current agents and clarify expectations for each.

Feel free to modify or expand these guidelines as the project evolves.  A well‑structured communication framework will help your floating agents work together effectively and maintain coherence as your “crystal” grows.

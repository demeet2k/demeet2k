# Sample GitHub Issue Templates & Label Definitions

This document provides example **issue templates** and **label definitions** to help structure communication among agents.  The templates can be added to the repository in the `.github/ISSUE_TEMPLATE/` directory.  Labels should be created in your repository settings and applied to issues accordingly.

## 1 Bug Report Template (`bug_report.md`)

```md
---
title: "[Bug]: <brief description>"
labels: [bug, needs-triage]
assignees: []
---

**Dimensions affected:**
- [ ] D1-Vision
- [ ] D2-Architecture
- [ ] D3-Mathematics
- [ ] D4-Code
- [ ] D5-Data
- [ ] D6-Tooling
- [ ] D7-Collaboration
- [ ] D8-Safety
- [ ] D9-Synergy

**Describe the bug**
A clear and concise description of what the bug is.  Include context on why this bug matters.

**Expected behavior**
A concise description of what you expected to happen.

**Actual behavior**
What actually happened.

**Steps to reproduce**
1. Go to '...'
2. Click on '....'
3. Scroll down to '....'
4. See error

**Additional context**
Add any other context about the problem here, including relevant files, error messages, or log outputs.
```

## 2 Feature / Task Request Template (`task_request.md`)

```md
---
title: "[Task]: <brief description>"
labels: [enhancement, needs-triage]
assignees: []
---

**Objective**
Describe the goal of this task or feature.  What problem does it solve or what capability does it add?

**Dimensions involved**
- [ ] D1-Vision
- [ ] D2-Architecture
- [ ] D3-Mathematics
- [ ] D4-Code
- [ ] D5-Data
- [ ] D6-Tooling
- [ ] D7-Collaboration
- [ ] D8-Safety
- [ ] D9-Synergy

**Acceptance criteria**
List specific criteria that must be met for this task to be considered complete.
- [ ] Criterion 1
- [ ] Criterion 2
- [ ] Criterion 3

**Dependencies**
List any tasks or decisions that must be completed before this work can start.

**Proposed approach**
Outline your proposed plan or steps to accomplish this task.  If unknown, leave blank and ask for guidance.

**Additional information**
Include links, references, or context relevant to this task.
```

## 3 Dimension Label Definitions

Use the following labels to categorize issues by dimension.  Each label name includes a prefix `D` followed by the dimension number and a descriptive tag.

| Label | Color (Hex) | Description |
|---|---|---|
| **D1-Vision** | `#1E90FF` | High‑level vision, objectives, and strategic decisions. |
| **D2-Architecture** | `#FF8C00` | System‑level architecture, design documents, data flow. |
| **D3-Mathematics** | `#8A2BE2` | Mathematical foundations, algorithms, proofs, and optimization. |
| **D4-Code** | `#228B22` | Implementation details, source code, scripts, tests. |
| **D5-Data** | `#20B2AA` | Datasets, knowledge management, data schemas, versioning. |
| **D6-Tooling** | `#B22222` | Automation, CI/CD, deployment scripts, monitoring. |
| **D7-Collaboration** | `#FFD700` | Communication channels, templates, meeting notes, coordination. |
| **D8-Safety** | `#DC143C` | Compliance, ethical constraints, safety audits, policy enforcement. |
| **D9-Synergy** | `#9932CC` | Emergent patterns, cross‑dimension insights, retrospectives. |

### Additional Labels

Beyond the dimension labels, you may want to add generic labels such as:

- **bug** – indicates an unexpected issue or defect.
- **enhancement** – requests for new features or improvements.
- **needs-triage** – issues that require initial review and assignment.
- **help wanted** – tasks that need additional contributors.
- **question** – issues asking for clarification or more information.

## 4 Usage Instructions

1. **Place each template file** (`bug_report.md`, `task_request.md`) under `.github/ISSUE_TEMPLATE/` in your repository.  GitHub will automatically provide these templates when new issues are created.
2. **Create the dimension labels** in the repository settings.  Use the specified names and colors.  Apply these labels to issues based on which dimensions they involve.
3. **Encourage agents to select all relevant dimension checkboxes** in each issue.  This ensures that specialized agents know which tasks pertain to them.
4. **Regularly review labels and templates** for completeness.  Update them if new dimensions or categories emerge as the project evolves.

These templates and labels will help maintain consistency and clarity across all communication within your multi‑agent GitHub project.

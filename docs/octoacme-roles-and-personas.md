# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## Project Sponsor

### Role Summary
The Project Sponsor champions the project at the executive level. They provide strategic direction, secure funding, and remove organizational obstacles that would otherwise block progress.

### Responsibilities
- Approve project charter, scope, and high-level budget
- Provide executive sponsorship and communicate organizational priority
- Remove escalated blockers and organizational impediments
- Review and sign off on major milestones and go/no-go decisions
- Ensure the project aligns with business strategy

### Goals
- Deliver measurable business outcomes from the project investment
- Maintain organizational buy-in and resource commitment
- Enable the team to move quickly by resolving high-level blockers

### Typical Communication
- Milestone reviews and executive status briefings from the Project Manager
- Ad-hoc escalations routed through the Project Manager or Process Owner
- Quarterly strategy alignment sessions with Product Managers

### Key Interactions
| Interacts With | Nature of Interaction |
|---|---|
| Project Manager | Receives status reports; approves go/no-go decisions |
| Process Owner | Reviews major process changes that affect business outcomes |
| Product Manager | Aligns on product vision and business priorities |
| Stakeholder Group Representative | Communicates strategic decisions; resolves escalated stakeholder concerns |

---

## Process Owner

### Role Summary
The Process Owner is accountable for maintaining and continuously improving the project management process documentation. They ensure that processes are understood, adopted, and updated as the organization learns.

### Responsibilities
- Own, maintain, and version-control all process documentation in `docs/`
- Facilitate process review sessions and capture improvement actions
- Ensure new team members are onboarded to current processes
- Track adoption of defined processes across active projects
- Coordinate with all roles to ensure processes remain relevant and effective

### Goals
- Keep process documentation accurate, discoverable, and actionable
- Reduce ambiguity in roles, handoffs, and decision rights
- Foster a culture of continuous improvement

### Typical Communication
- Regular process review meetings (at minimum quarterly)
- Update notifications to the team when documents change
- Retrospective findings fed into process improvement backlog

### Key Interactions
| Interacts With | Nature of Interaction |
|---|---|
| Project Manager | Collaborates on practical process gaps surfaced during delivery |
| Change Manager | Partners on rolling out significant process changes |
| Project Sponsor | Escalates process blockers that need executive decisions |
| All Roles | Acts as the point of contact for process questions and improvement suggestions |

---

## Stakeholder Group Representative

### Role Summary
The Stakeholder Group Representative advocates for specific stakeholder groups (e.g., end users, clients, QA teams, legal, security). They ensure that group-specific needs and constraints are surfaced and considered throughout the project.

### Responsibilities
- Represent their stakeholder group's requirements, constraints, and concerns
- Communicate project updates and decisions back to their stakeholder group
- Participate in planning and review sessions relevant to their group
- Escalate unresolved concerns to the Project Manager or Project Sponsor
- Gather and relay feedback from their group on deliverables

### Goals
- Ensure stakeholder group needs are included in project scope and design
- Maintain trust and transparency between the project team and their group
- Facilitate timely decisions by surfacing blockers early

### Typical Communication
- Attends sprint reviews, milestone demos, or scheduled review checkpoints
- Provides written feedback on deliverables via agreed channels
- Regular sync with the Project Manager for status and upcoming decisions

### Key Interactions
| Interacts With | Nature of Interaction |
|---|---|
| Project Manager | Reports group concerns; receives project status updates |
| Product Manager | Provides requirements, feedback, and acceptance signals |
| Change Manager | Receives change impact communications; supports adoption within their group |
| Project Sponsor | Escalates unresolved blockers or strategic conflicts |

---

## Change Manager

### Role Summary
The Change Manager oversees significant changes to processes, systems, or ways of working. They plan, communicate, and support the team through transitions to minimize disruption and maximize adoption.

### Responsibilities
- Assess the impact of proposed changes on people, processes, and systems
- Develop and execute change management and communication plans
- Coordinate training and support materials for impacted roles
- Track adoption and address resistance or confusion post-rollout
- Collaborate with the Process Owner to update documentation following changes

### Goals
- Ensure changes are adopted smoothly with minimal productivity loss
- Maintain clear communication so no stakeholder is surprised by a change
- Capture lessons learned from each change to improve future transitions

### Typical Communication
- Change impact assessments and communication plans shared with the Project Manager and Process Owner
- Rollout announcements and training sessions for impacted teams
- Post-change retrospective findings shared with the Process Owner

### Key Interactions
| Interacts With | Nature of Interaction |
|---|---|
| Process Owner | Partners on updating documentation after changes are rolled out |
| Project Manager | Coordinates timeline and communication for project-level changes |
| Stakeholder Group Representative | Communicates change impacts to specific stakeholder groups |
| Project Sponsor | Reports adoption status; escalates major change risks |

---

## Role Interaction Summary

The table below shows the primary collaboration paths across all defined roles.

| Role | Works Closely With |
|---|---|
| Developer | Project Manager, Product Manager |
| Product Manager | Project Manager, Project Sponsor, Stakeholder Group Representative |
| Project Manager | All roles – central coordination point |
| Project Sponsor | Project Manager, Process Owner, Product Manager |
| Process Owner | Project Manager, Change Manager, all roles |
| Stakeholder Group Representative | Project Manager, Product Manager, Change Manager |
| Change Manager | Process Owner, Project Manager, Stakeholder Group Representative |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.


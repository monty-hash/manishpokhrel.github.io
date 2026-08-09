# Business Requirements Document

## Aged Care Daily & Weekly Task Management

**Project Type:** Business Process Improvement
**Role:** Business Analyst
**Industry:** Aged Care
**Document Status:** Portfolio Case Study

---

## 1. Purpose

The purpose of this document is to describe the business requirements for improving the way daily and weekly operational tasks are communicated, assigned and monitored.

The focus is on improving task visibility and reducing reliance on manual communication and follow-up.

This document describes the business needs and proposed system requirements. It does not represent requirements for a live production system.

---

## 2. Business Problem

The current process relies heavily on manual communication.

Tasks may be communicated verbally or through informal channels, which can make it difficult to know:

* Who is responsible for a task
* Whether the task has been completed
* Which tasks are still outstanding
* Which tasks are overdue
* Why a task could not be completed

Recurring tasks can also require repeated communication.

---

## 3. Business Objectives

The proposed solution should help the organisation:

1. Improve communication of daily and weekly tasks.
2. Give staff clearer visibility of assigned work.
3. Improve visibility of outstanding and overdue tasks.
4. Reduce unnecessary manual follow-up.
5. Provide a consistent way to record task completion.
6. Support recurring tasks.
7. Provide an exception process for tasks that cannot be completed.

---

# 4. Business Requirements

| ID    | Requirement                                                                  | Priority |
| ----- | ---------------------------------------------------------------------------- | -------- |
| BR-01 | Staff should have a central place to view assigned tasks.                    | High     |
| BR-02 | Tasks should be assigned to an appropriate staff member or team.             | High     |
| BR-03 | The process should provide clear task statuses.                              | High     |
| BR-04 | The solution should support recurring daily and weekly tasks.                | High     |
| BR-05 | RNs and CCCs should be able to monitor relevant task status.                 | High     |
| BR-06 | Staff should be able to record task completion.                              | High     |
| BR-07 | Staff should be able to record an exception when a task cannot be completed. | High     |
| BR-08 | Overdue tasks should be identifiable for follow-up.                          | Medium   |
| BR-09 | Authorised users should be able to view task history where required.         | Medium   |

---

# 5. Functional Requirements

Functional requirements describe what the proposed solution should be able to do.

### FR-01 — View Tasks

The system should allow care staff to view tasks assigned to them.

### FR-02 — Assign Tasks

The system should allow authorised users to assign tasks to an appropriate staff member or team.

### FR-03 — Task Status

The system should allow task status to be updated.

Possible statuses include:

* Not Started
* In Progress
* Completed
* Overdue
* Exception

### FR-04 — Due Date and Time

Tasks should be able to have a defined due date or time where required.

### FR-05 — Recurring Tasks

The system should support the creation of recurring daily and weekly tasks.

### FR-06 — Notifications

The system should be capable of notifying the relevant staff member when a new task is assigned or requires attention.

### FR-07 — Completion

Care staff should be able to mark an assigned task as completed.

### FR-08 — Exception Recording

Care staff should be able to record an exception when a task cannot be completed.

The exception should include an appropriate reason.

### FR-09 — RN Visibility

Authorised RNs should be able to view relevant outstanding, completed and overdue tasks.

### FR-10 — CCC Visibility

Authorised Clinical Care Coordinators should be able to monitor relevant task activity.

### FR-11 — Overdue Identification

The system should identify tasks that have passed their due time without being completed.

### FR-12 — Task History

Where required, authorised users should be able to view relevant task history.

---

# 6. Non-Functional Requirements

Non-functional requirements describe how the solution should operate rather than what specific function it performs.

### NFR-01 — Usability

The task-management interface should be simple enough for staff to use with minimal training.

### NFR-02 — Performance

Task information should load within a reasonable time during normal operation.

### NFR-03 — Availability

The system should be available during normal operational periods when staff need to access tasks.

### NFR-04 — Security

Access to task information should be restricted to authorised users.

### NFR-05 — Privacy

The solution should follow applicable privacy and information-handling requirements.

### NFR-06 — Auditability

Where appropriate, changes to task status should be traceable.

### NFR-07 — Accessibility

The interface should be usable by staff with different accessibility needs where applicable.

---

# 7. Business Rules

The following business rules were identified for the proposed process.

### BRULE-01

A task should have an identifiable owner or responsible team.

### BRULE-02

Only authorised users should be able to change task assignments or administrative settings.

### BRULE-03

A completed task should not be treated as outstanding.

### BRULE-04

A task that passes its due time without completion should be identifiable as overdue.

### BRULE-05

If a task cannot be completed, the staff member should be able to record an exception rather than incorrectly marking the task as completed.

### BRULE-06

Clinical decisions and follow-up actions remain the responsibility of appropriately authorised staff.

---

# 8. Assumptions

For this portfolio case study, I have made the following assumptions:

* Staff have access to an appropriate digital device or workstation.
* Users have individual accounts or another method of identification.
* The organisation has an existing system or platform that could potentially support task management.
* Recurring tasks can be defined using agreed business rules.
* RNs and CCCs have appropriate permissions to monitor relevant tasks.
* The final technology platform would be selected after further technical and organisational assessment.

---

# 9. Dependencies

Potential dependencies include:

* Availability of an appropriate technology platform
* User access and permissions
* Existing organisational systems
* Staff training
* IT/application support
* Agreement on task ownership
* Agreement on escalation and exception processes
* Privacy and security requirements

---

# 10. Out of Scope

The following items are outside the scope of this portfolio project:

* Replacing existing clinical systems
* Making clinical decisions through automation
* Automated clinical decision-making
* Managing employee payroll
* Managing staff rostering
* Managing resident medical records
* Implementing a production system
* Selecting a final software vendor

The project focuses specifically on **operational task communication, assignment, monitoring and completion**.

---

# 11. Requirement Prioritisation

I used a simple priority approach:

### High

Required for the core process to work.

### Medium

Important for improving the process but not essential to the basic workflow.

### Low

Potential future improvements that could be considered after the core solution is established.

For a real project, I would confirm these priorities with the relevant stakeholders during requirements workshops or discussions.

---

# 12. Traceability

The requirements should be traceable through the rest of the BA lifecycle.

For example:

**BR-01 Central Task Visibility**

→ **US-01 View Assigned Tasks**

→ **AC-01 Assigned Task Visibility**

→ **UAT-01 Staff Views Assigned Tasks**

This helps ensure that requirements are not lost between analysis, development and testing.

---

# 13. Open Questions for Stakeholders

Before implementation, I would clarify the following with stakeholders:

1. Which tasks should be automatically generated?
2. Who should be responsible for each type of task?
3. How should tasks be reassigned when the original staff member is unavailable?
4. Which tasks require RN review?
5. What should happen when a task becomes overdue?
6. How long should task history be retained?
7. What information should be included in notifications?
8. Which existing system should integrate with the task-management process?
9. What reporting does the CCC require?
10. What access permissions should each user type have?

These questions would need to be answered before finalising the solution design.

---

## 14. Summary

The requirements in this document are intended to provide a starting point for designing an improved task-management process.

The main focus is not simply to automate tasks, but to improve the overall process by providing:

**Clear ownership → Better visibility → Simple status tracking → Exception handling → Appropriate follow-up**

The next stage would be to validate these requirements with stakeholders and refine them before moving into detailed solution design.

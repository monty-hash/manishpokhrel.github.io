# User Stories & Acceptance Criteria

## Aged Care Daily & Weekly Task Management

**Project Type:** Business Process Improvement
**Role:** Business Analyst

---

## 1. Purpose

This document translates the business requirements into user stories and acceptance criteria.

The user stories focus on the needs of the main users of the proposed task-management process:

* Care Staff
* Registered Nurses (RNs)
* Clinical Care Coordinators (CCCs)

The acceptance criteria describe how we would determine whether each requirement has been met.

---

# 2. User Story 01 — View Assigned Tasks

### User Story

**As a care staff member, I want to see my assigned tasks in one place so that I know what needs to be completed during my shift.**

### Related Requirement

BR-01 — Central Task Visibility

### Acceptance Criteria

**Given** the staff member has one or more assigned tasks,

**When** they open the task-management system,

**Then** their assigned tasks should be displayed.

**And** each task should show relevant information such as the task name and due time.

**And** the staff member should be able to identify which tasks are still outstanding.

---

# 3. User Story 02 — Complete a Task

### User Story

**As a care staff member, I want to mark a task as completed so that the appropriate RN or CCC can see that the task has been completed.**

### Related Requirements

* BR-03 — Task Status
* BR-06 — Completion Recording

### Acceptance Criteria

**Given** a staff member has an assigned task,

**When** the staff member completes the task,

**Then** they should be able to update the task status to "Completed".

**And** the updated status should be visible to authorised users.

**And** the completed task should no longer appear as an outstanding task.

---

# 4. User Story 03 — View Outstanding Tasks

### User Story

**As an RN, I want to see outstanding tasks so that I can identify tasks that may need follow-up.**

### Related Requirement

BR-05 — Clinical Oversight

### Acceptance Criteria

**Given** there are outstanding tasks,

**When** an authorised RN opens the task view,

**Then** relevant outstanding tasks should be visible.

**And** the RN should be able to identify the current status of each task.

**And** tasks requiring follow-up should be distinguishable from completed tasks.

---

# 5. User Story 04 — Manage Recurring Tasks

### User Story

**As a Clinical Care Coordinator, I want recurring tasks to be generated automatically so that staff do not have to receive the same instructions manually each time.**

### Related Requirement

BR-04 — Recurring Tasks

### Acceptance Criteria

**Given** a recurring task has been configured,

**When** the scheduled date and time are reached,

**Then** the system should create the task according to the configured rule.

**And** the task should be assigned to the appropriate staff member or team.

**And** the task should be visible to the relevant users.

---

# 6. User Story 05 — Identify Overdue Tasks

### User Story

**As an RN or CCC, I want to identify overdue tasks so that appropriate follow-up can occur.**

### Related Requirements

* BR-05 — Clinical Oversight
* BR-08 — Overdue Identification

### Acceptance Criteria

**Given** a task has a defined due time,

**When** the due time passes without completion,

**Then** the task should be identified as "Overdue".

**And** authorised RNs and CCCs should be able to see the overdue status.

**And** the task should remain available for appropriate follow-up.

---

# 7. User Story 06 — Record an Exception

### User Story

**As a care staff member, I want to record why I could not complete a task so that the RN or CCC can review the situation.**

### Related Requirement

BR-07 — Exception Handling

### Acceptance Criteria

**Given** a staff member cannot complete an assigned task,

**When** they select the exception option,

**Then** they should be able to record an appropriate reason.

**And** the task should be identified as requiring follow-up.

**And** the relevant RN or CCC should be able to view the exception.

---

# 8. User Story 07 — Review an Exception

### User Story

**As an RN or CCC, I want to review task exceptions so that I can determine the appropriate follow-up action.**

### Related Requirements

* BR-05 — Clinical Oversight
* BR-07 — Exception Handling

### Acceptance Criteria

**Given** a staff member has recorded an exception,

**When** an authorised RN or CCC reviews the task,

**Then** the exception reason should be visible.

**And** the reviewer should be able to record the appropriate follow-up action.

**And** the task status should be updated when the follow-up is completed.

---

# 9. User Story 08 — View Task History

### User Story

**As an authorised RN or CCC, I want to view relevant task history so that I can understand what happened with a task.**

### Related Requirement

BR-09 — Task History

### Acceptance Criteria

**Given** a task has previous activity,

**When** an authorised user views the task history,

**Then** relevant status changes should be visible.

**And** the user should be able to identify the task outcome.

**And** access should be restricted to authorised users.

---

# 10. User Story Prioritisation

| ID    | User Story             | Priority |
| ----- | ---------------------- | -------- |
| US-01 | View Assigned Tasks    | High     |
| US-02 | Complete a Task        | High     |
| US-03 | View Outstanding Tasks | High     |
| US-04 | Manage Recurring Tasks | High     |
| US-05 | Identify Overdue Tasks | High     |
| US-06 | Record an Exception    | High     |
| US-07 | Review an Exception    | High     |
| US-08 | View Task History      | Medium   |

---

# 11. Definition of Done

For this portfolio project, I would consider a user story ready for acceptance when:

* The requirement has been reviewed.
* Acceptance criteria have been agreed.
* The expected behaviour is clear.
* The user story can be tested.
* Relevant UAT scenarios have been identified.
* No critical acceptance issues remain unresolved.

---

# 12. Notes

These user stories represent the proposed future-state process.

In a real project, I would validate the stories with the relevant stakeholders before development.

The wording may also change as more information becomes available during requirements workshops, process discussions and solution design.

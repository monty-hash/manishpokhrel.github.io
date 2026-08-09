# Requirements Traceability Matrix

## Aged Care Daily & Weekly Task Management

**Project Type:** Business Process Improvement
**Role:** Business Analyst

---

## 1. Purpose

The Requirements Traceability Matrix (RTM) connects the business requirements to the user stories, acceptance criteria and UAT scenarios.

The purpose is to make sure that each important requirement can be followed through the project lifecycle.

The basic traceability flow is:

**Business Requirement → User Story → Acceptance Criteria → UAT**

---

# 2. Requirements Traceability Matrix

| Requirement ID | Business Requirement    | User Story    | Acceptance Criteria | UAT             |
| -------------- | ----------------------- | ------------- | ------------------- | --------------- |
| BR-01          | Central task visibility | US-01         | AC-01               | UAT-01          |
| BR-02          | Task assignment         | US-01         | AC-01               | UAT-02          |
| BR-03          | Task status             | US-02         | AC-02               | UAT-03          |
| BR-04          | Recurring tasks         | US-04         | AC-04               | UAT-04          |
| BR-05          | Clinical oversight      | US-03         | AC-03               | UAT-05          |
| BR-05          | Clinical oversight      | US-05         | AC-03               | UAT-06          |
| BR-06          | Completion recording    | US-02         | AC-02               | UAT-03          |
| BR-07          | Exception handling      | US-06 / US-07 | AC-06 / AC-07       | UAT-09 / UAT-10 |
| BR-08          | Overdue identification  | US-05         | AC-05               | UAT-07 / UAT-08 |
| BR-09          | Task history            | US-08         | AC-08               | UAT-11          |

---

# 3. Detailed Traceability

## BR-01 — Central Task Visibility

**Business Requirement:**
Staff should have a central place to view assigned tasks.

**User Story:**
US-01 — View Assigned Tasks

**Acceptance Criteria:**
AC-01 — Assigned tasks are displayed with relevant task information.

**UAT:**
UAT-01 — Care staff views assigned tasks.

---

## BR-02 — Task Assignment

**Business Requirement:**
Tasks should be assigned to an appropriate staff member or team.

**User Story:**
US-01 — View Assigned Tasks

**Acceptance Criteria:**
AC-01 — Assigned tasks are displayed to the appropriate user.

**UAT:**
UAT-02 — New task is assigned.

---

## BR-03 — Task Status

**Business Requirement:**
The process should provide clear task statuses.

**User Story:**
US-02 — Complete a Task

**Acceptance Criteria:**
AC-02 — Completed tasks are updated to "Completed".

**UAT:**
UAT-03 — Care staff completes a task.

---

## BR-04 — Recurring Tasks

**Business Requirement:**
The solution should support recurring daily and weekly tasks.

**User Story:**
US-04 — Manage Recurring Tasks

**Acceptance Criteria:**
AC-04 — A configured recurring task is generated according to its schedule.

**UAT:**
UAT-04 — Recurring task reaches its scheduled date.

---

## BR-05 — Clinical Oversight

**Business Requirement:**
RNs and CCCs should be able to monitor relevant task status.

**User Stories:**

* US-03 — View Outstanding Tasks
* US-05 — Identify Overdue Tasks

**Acceptance Criteria:**

* AC-03 — RN can view outstanding tasks.
* AC-05 — RN/CCC can identify overdue tasks.

**UAT:**

* UAT-05 — RN views task dashboard.
* UAT-06 — CCC reviews task status.

---

## BR-06 — Completion Recording

**Business Requirement:**
Staff should be able to record task completion.

**User Story:**
US-02 — Complete a Task

**Acceptance Criteria:**
AC-02 — Staff can update the task to "Completed".

**UAT:**
UAT-03 — Staff completes a task.

---

## BR-07 — Exception Handling

**Business Requirement:**
Staff should be able to record an exception when a task cannot be completed.

**User Stories:**

* US-06 — Record an Exception
* US-07 — Review an Exception

**Acceptance Criteria:**

* AC-06 — Staff can record an exception.
* AC-07 — RN/CCC can review the exception.

**UAT:**

* UAT-09 — Staff records an exception.
* UAT-10 — RN/CCC reviews the exception.

---

## BR-08 — Overdue Identification

**Business Requirement:**
Overdue tasks should be identifiable for follow-up.

**User Story:**
US-05 — Identify Overdue Tasks

**Acceptance Criteria:**
AC-05 — Tasks past their due time are identified as overdue.

**UAT:**

* UAT-07 — Task passes its due time.
* UAT-08 — RN/CCC reviews overdue task.

---

## BR-09 — Task History

**Business Requirement:**
Authorised users should be able to view relevant task history where required.

**User Story:**
US-08 — View Task History

**Acceptance Criteria:**
AC-08 — Authorised users can view relevant task activity.

**UAT:**
UAT-11 — Authorised user views task history.

---

# 4. Traceability Coverage

The current matrix provides traceability across the main stages of the project:

| Stage                 | Covered |
| --------------------- | ------- |
| Business Requirements | Yes     |
| User Stories          | Yes     |
| Acceptance Criteria   | Yes     |
| UAT Scenarios         | Yes     |

---

# 5. Why the RTM Matters

The RTM helps answer four important questions:

**Why are we building this?**
→ Business Requirement

**Who needs it?**
→ User Story

**How should it behave?**
→ Acceptance Criteria

**How will we know it works?**
→ UAT

If a requirement cannot be traced to testing, it may be easy for it to be missed during implementation.

---

# 6. Portfolio Note

This RTM is a simplified example created for a Business Analyst portfolio project.

In a real project, the matrix would be maintained throughout the project lifecycle and updated whenever requirements change.

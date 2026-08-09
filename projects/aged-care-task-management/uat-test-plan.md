# User Acceptance Testing (UAT) Plan

## Aged Care Daily & Weekly Task Management

**Project Type:** Business Process Improvement
**Role:** Business Analyst
**Testing Type:** User Acceptance Testing
**Status:** Portfolio Case Study

---

# 1. Purpose

The purpose of this UAT plan is to describe how the proposed task-management process would be tested from a business user's perspective.

The testing focuses on whether the proposed process meets the agreed business requirements and supports the needs of care staff, Registered Nurses (RNs) and Clinical Care Coordinators (CCCs).

This is a simulated UAT plan created for a portfolio project. It is not testing of a live production system.

---

# 2. UAT Objectives

The main objectives are to confirm that:

* Staff can view their assigned tasks.
* Tasks can be assigned correctly.
* Staff can update task status.
* Recurring tasks can be generated according to defined rules.
* RNs and CCCs can monitor relevant tasks.
* Overdue tasks can be identified.
* Staff can record exceptions.
* RNs and CCCs can review exceptions.
* Relevant task history can be viewed by authorised users.

---

# 3. UAT Participants

| Role                      | Responsibility                                        |
| ------------------------- | ----------------------------------------------------- |
| Care Staff                | Test task viewing, completion and exception recording |
| Registered Nurse          | Test task monitoring and follow-up                    |
| Clinical Care Coordinator | Test recurring tasks, monitoring and reporting        |
| Business Analyst          | Coordinate UAT and document results                   |
| IT / Application Support  | Support technical issues during testing               |

---

# 4. Test Environment

For this portfolio case study, the test environment is assumed to be a non-production environment containing sample data.

No real resident or employee information should be used during testing.

---

# 5. UAT Scenarios

## UAT-01 — View Assigned Tasks

**Requirement:** BR-01
**User Story:** US-01
**Acceptance Criteria:** AC-01

### Scenario

A care staff member logs into the task-management system.

### Expected Result

The staff member can see the tasks assigned to them.

Each task displays relevant information such as:

* Task name
* Due date/time
* Current status

**Priority:** High

---

## UAT-02 — Task Assignment

**Requirement:** BR-02
**User Story:** US-01
**Acceptance Criteria:** AC-01

### Scenario

An authorised user creates a new task and assigns it to a staff member or team.

### Expected Result

The task appears for the intended staff member or team.

**Priority:** High

---

## UAT-03 — Complete a Task

**Requirement:** BR-03 / BR-06
**User Story:** US-02
**Acceptance Criteria:** AC-02

### Scenario

A care staff member completes an assigned task.

### Expected Result

The staff member can mark the task as completed.

The task status changes to **Completed**.

The updated status is visible to authorised users.

**Priority:** High

---

## UAT-04 — Recurring Task

**Requirement:** BR-04
**User Story:** US-04
**Acceptance Criteria:** AC-04

### Scenario

A recurring daily or weekly task reaches its scheduled date/time.

### Expected Result

The system creates the task according to the configured recurring rule.

The task is assigned to the appropriate staff member or team.

**Priority:** High

---

## UAT-05 — RN Views Outstanding Tasks

**Requirement:** BR-05
**User Story:** US-03
**Acceptance Criteria:** AC-03

### Scenario

An RN opens the task-management view.

### Expected Result

Relevant outstanding tasks are visible.

The RN can identify the current status of the tasks.

**Priority:** High

---

## UAT-06 — CCC Reviews Task Status

**Requirement:** BR-05
**User Story:** US-05
**Acceptance Criteria:** AC-05

### Scenario

A CCC reviews the task-management view.

### Expected Result

The CCC can identify relevant task statuses, including outstanding and overdue tasks.

**Priority:** High

---

## UAT-07 — Overdue Task

**Requirement:** BR-08
**User Story:** US-05
**Acceptance Criteria:** AC-05

### Scenario

A task passes its due time without being completed.

### Expected Result

The task is identified as **Overdue**.

The overdue status is visible to authorised RNs and CCCs.

**Priority:** High

---

## UAT-08 — Follow Up Overdue Task

**Requirement:** BR-05 / BR-08
**User Story:** US-05
**Acceptance Criteria:** AC-05

### Scenario

An RN or CCC reviews an overdue task.

### Expected Result

The reviewer can identify the overdue task and determine the appropriate follow-up action.

**Priority:** High

---

## UAT-09 — Record Exception

**Requirement:** BR-07
**User Story:** US-06
**Acceptance Criteria:** AC-06

### Scenario

A care staff member cannot complete an assigned task.

### Expected Result

The staff member can record an exception and provide an appropriate reason.

The task is identified as requiring follow-up.

**Priority:** High

---

## UAT-10 — Review Exception

**Requirement:** BR-07
**User Story:** US-07
**Acceptance Criteria:** AC-07

### Scenario

An RN or CCC reviews a task with an exception.

### Expected Result

The exception reason is visible.

The RN or CCC can record the appropriate follow-up action.

**Priority:** High

---

## UAT-11 — View Task History

**Requirement:** BR-09
**User Story:** US-08
**Acceptance Criteria:** AC-08

### Scenario

An authorised RN or CCC views the history of a task.

### Expected Result

Relevant task activity and status changes are visible.

Access is restricted to authorised users.

**Priority:** Medium

---

# 6. UAT Results

For an actual implementation, the following fields would be completed during testing.

| Test ID | Result | Status     | Defect / Comment |
| ------- | ------ | ---------- | ---------------- |
| UAT-01  |        | Not Tested |                  |
| UAT-02  |        | Not Tested |                  |
| UAT-03  |        | Not Tested |                  |
| UAT-04  |        | Not Tested |                  |
| UAT-05  |        | Not Tested |                  |
| UAT-06  |        | Not Tested |                  |
| UAT-07  |        | Not Tested |                  |
| UAT-08  |        | Not Tested |                  |
| UAT-09  |        | Not Tested |                  |
| UAT-10  |        | Not Tested |                  |
| UAT-11  |        | Not Tested |                  |

Possible statuses could include:

* Pass
* Fail
* Blocked
* Not Tested

---

# 7. UAT Entry Criteria

UAT would normally begin when:

* Business requirements have been agreed.
* User stories and acceptance criteria have been reviewed.
* The test environment is available.
* Test data is available.
* Users participating in UAT have been identified.
* The solution is ready for business testing.

---

# 8. UAT Exit Criteria

UAT could be considered complete when:

* All high-priority scenarios have been tested.
* Critical defects have been resolved or formally accepted.
* Business users are satisfied that the core requirements have been met.
* Outstanding issues have been documented.
* Appropriate business sign-off has been obtained.

---

# 9. Defect Handling

If a UAT scenario fails, the issue should be recorded and assessed.

A basic defect workflow could be:

**Issue identified**

↓

**Defect recorded**

↓

**Business impact assessed**

↓

**Issue assigned for investigation**

↓

**Fix implemented**

↓

**Retest**

↓

**Pass / Fail**

This provides a clear link between UAT and the development/support process.

---

# 10. UAT Sign-Off

For a real implementation, sign-off could involve:

| Role                      | Sign-Off |
| ------------------------- | -------- |
| Business Representative   | Pending  |
| Registered Nurse          | Pending  |
| Clinical Care Coordinator | Pending  |
| Business Analyst          | Pending  |
| IT / Application Support  | Pending  |

For this portfolio project, no actual production sign-off is being claimed.

---

# 11. Portfolio Learning

This UAT plan helped me understand the importance of connecting testing back to requirements.

A good UAT scenario should answer:

**What are we testing?**

**Why are we testing it?**

**What should happen?**

**How do we know whether it passed?**

This creates a clear connection between the original business problem, the requirements and the proposed solution.

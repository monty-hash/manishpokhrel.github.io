# Aged Care Daily & Weekly Task Management Process Improvement

**Project type:** Business Process Improvement
**Industry:** Aged Care
**Role:** Business Analyst
**Project:** Portfolio Case Study

---

## Project Overview

For this project, I looked at a common operational problem in an aged care environment: how daily and weekly tasks are communicated to care staff and how managers can keep track of whether those tasks have been completed.

In a busy care environment, tasks can be communicated verbally or through different informal methods. This can work for simple situations, but it becomes harder to keep track when there are multiple staff members, recurring tasks and competing priorities during a shift.

I used this scenario to practise the Business Analyst process from identifying the problem through to requirements, process mapping, user stories, acceptance criteria, future-state design and UAT.

The solution I have proposed is a structured digital task-management process where staff can see their assigned tasks, update the status and flag tasks that cannot be completed. RNs and Clinical Care Coordinators can then have better visibility of outstanding work.

> **Note:** This is a fictionalised/anonymised portfolio project. It does not use confidential resident, staff or organisational information.

---

# 1. The Business Problem

The starting point for this project was a simple question:

**How can we make daily and weekly task communication easier to manage and easier to track?**

Some examples of tasks in an aged care environment could include:

* Daily resident-related checks
* Weekly scheduled activities
* Resident-of-the-day activities
* Weight checks
* Documentation-related tasks
* Other recurring operational activities

I identified three main problems with the current approach.

### 1. Manual communication

Tasks may need to be communicated verbally or through informal communication between staff.

This creates a risk that information may not reach the right person at the right time.

### 2. Tasks can be missed

Care staff can be dealing with several priorities during a shift. When tasks are communicated manually, there is a possibility that a task may be forgotten, misunderstood or not completed.

### 3. Limited visibility

RNs and Clinical Care Coordinators may need to ask staff directly whether a task has been completed.

There isn't necessarily one place where they can quickly see:

* What has been completed
* What is still outstanding
* What is overdue
* Why a task was not completed

---

# 2. Project Objective

The main objective is to improve **communication and visibility of daily and weekly tasks**.

I wanted the future process to make it easier for:

**Care staff** to know what they need to do.

**RNs** to see outstanding tasks and follow up where appropriate.

**Clinical Care Coordinators** to monitor recurring activities and overall task completion.

The proposed process should provide:

* Clear task assignment
* One central place to view tasks
* Simple status updates
* Visibility of outstanding work
* Visibility of completed work
* Support for recurring tasks
* A way to record exceptions
* Easier follow-up

---

# 3. Stakeholder Analysis

I identified the following stakeholders based on how they would interact with the process.

| Stakeholder                         | How they use the process                          | What they need                                      | Involvement |
| ----------------------------------- | ------------------------------------------------- | --------------------------------------------------- | ----------- |
| **Care Staff**                      | Complete assigned tasks                           | Clear instructions and an easy way to update status | High        |
| **Registered Nurse (RN)**           | Monitor relevant tasks and follow up              | Visibility of outstanding and overdue tasks         | High        |
| **Clinical Care Coordinator (CCC)** | Coordinate activities and monitor recurring tasks | Overall visibility and task reporting               | High        |
| **Administration Staff**            | Support operational activities                    | Less manual coordination                            | Medium      |
| **IT / Application Support**        | Support the technology                            | Clear requirements and maintainable solution        | Medium      |
| **Quality / Compliance**            | Monitor process consistency                       | Reliable records and traceability                   | Medium      |

### Stakeholder observation

The needs of each group are slightly different.

For example, care staff need the process to be **quick and easy to use**, while an RN or CCC needs more **visibility and oversight**.

This is something I would consider when gathering and prioritising requirements.

---

# 4. Current-State Process — As-Is

I mapped the current process before thinking about a technology solution.

The basic process is:

**Task identified**

↓

**Task communicated manually**

↓

**Care staff receives instruction**

↓

**Care staff completes task**

↓

**Completion communicated or documented**

↓

**RN / CCC follows up if required**

↓

**Task considered complete**

### Current-State Pain Points

During the analysis, I identified the following areas that could be improved:

* Tasks rely heavily on manual communication
* There may not be one central task list
* Staff may have limited visibility of outstanding tasks
* RNs and CCCs may need to manually follow up
* Recurring tasks may require repeated communication

**Process diagram:**
`as-is-process.png`

---

# 5. Business Requirements

After looking at the current process, I translated the problems into business requirements.

### BR-01 — Central Task Visibility

The solution should provide one central location where care staff can view their assigned tasks.

### BR-02 — Task Assignment

The solution should allow tasks to be assigned to the appropriate staff member or team.

### BR-03 — Task Status

Users should be able to see whether a task is:

* Not Started
* In Progress
* Completed
* Overdue

### BR-04 — Recurring Tasks

The solution should support tasks that need to be repeated daily or weekly.

### BR-05 — Clinical Oversight

RNs and CCCs should be able to view relevant outstanding and completed tasks.

### BR-06 — Completion Recording

Care staff should be able to record when a task has been completed.

### BR-07 — Exception Handling

The process should allow staff to identify a task that cannot be completed and provide a reason for follow-up.

---

# 6. User Stories

I converted some of the requirements into user stories to describe what different users need from the solution.

### US-01 — View Assigned Tasks

**As a care staff member, I want to see my assigned tasks in one place so that I know what needs to be completed during my shift.**

### US-02 — Complete a Task

**As a care staff member, I want to mark a task as completed so that the appropriate RN or CCC can see the current status.**

### US-03 — Monitor Outstanding Tasks

**As an RN, I want to see outstanding tasks so that I can follow up when required.**

### US-04 — Manage Recurring Tasks

**As a CCC, I want recurring tasks to be generated automatically so that staff do not have to receive the same instructions manually each time.**

### US-05 — Identify Overdue Tasks

**As an RN or CCC, I want to identify overdue tasks so that appropriate follow-up can occur.**

---

# 7. Acceptance Criteria

I used acceptance criteria to make the user stories more specific and testable.

### AC-01 — Assigned Task Visibility

**Given** a care staff member has assigned tasks,

**When** they open the task-management system,

**Then** their assigned tasks should be displayed,

**And** the relevant due information should be visible.

### AC-02 — Task Completion

**Given** a care staff member has an assigned task,

**When** they complete the task,

**Then** they should be able to mark it as completed,

**And** the task status should change to "Completed",

**And** authorised RNs and CCCs should be able to see the updated status.

### AC-03 — Overdue Task

**Given** a task has a defined due time,

**When** the due time passes and the task has not been completed,

**Then** the task should be identified as "Overdue",

**And** authorised RNs and CCCs should be able to see the status.

### AC-04 — Exception

**Given** a care staff member cannot complete an assigned task,

**When** they record an exception,

**Then** the reason should be recorded,

**And** the relevant RN or CCC should be able to review it.

---

# 8. Requirements Traceability

I created a simple Requirements Traceability Matrix to make sure the requirements can be followed through to testing.

| Requirement | User Story | Acceptance Criteria | UAT             |
| ----------- | ---------- | ------------------- | --------------- |
| BR-01       | US-01      | AC-01               | UAT-01          |
| BR-02       | US-01      | AC-01               | UAT-02          |
| BR-03       | US-02      | AC-02               | UAT-03          |
| BR-04       | US-04      | AC-04               | UAT-04          |
| BR-05       | US-03      | AC-03               | UAT-05          |
| BR-05       | US-05      | AC-03               | UAT-06          |
| BR-06       | US-02      | AC-02               | UAT-03          |
| BR-07       | US-05      | AC-03 / AC-04       | UAT-07 / UAT-08 |

The purpose of the RTM is to make sure that a requirement doesn't get lost between analysis and testing.

---

# 9. Future-State Process — To-Be

After analysing the current process, I designed a possible future-state workflow.

The proposed process would work like this:

**Recurring task becomes due / New task created**

↓

**System creates the task**

↓

**Task is assigned to the appropriate staff/team**

↓

**Care staff receives the task**

↓

**Care staff views the task and due time**

↓

**Can the task be completed?**

### If YES

**Care staff completes the task**

↓

**Task status is updated**

↓

**RN / CCC can view the updated status**

### If NO

**Staff records an exception/reason**

↓

**RN / CCC reviews the exception**

↓

**Appropriate follow-up action**

↓

**Task status is updated**

**To-Be process diagram:**
`to-be-process.png`

---

# 10. Why I Included Exception Handling

One thing I wanted to avoid in this project was designing an unrealistic "perfect" automated process.

In an actual aged care environment, staff availability and priorities can change during a shift.

For example, a staff member may:

* Become unavailable
* Be reassigned
* Have an urgent competing task
* Need clarification
* Be unable to complete a task for an operational reason

Because of this, I included an exception path in the future-state process.

Instead of simply marking the task as failed, the staff member can record what happened and the RN or CCC can review it.

This keeps the automation focused on **supporting the workflow**, rather than trying to replace human judgement.

---

# 11. Automation Concept

One possible solution would be to use a digital task-management workflow.

For example, a recurring task could work like this:

**Scheduled date/time reached**

↓

**System creates the task**

↓

**Task assigned**

↓

**Staff receives notification**

↓

**Staff completes the task**

↓

**Completion recorded**

↓

**RN / CCC can view the status**

This could reduce repetitive communication and give the team better visibility.

I have intentionally kept the technology solution flexible at this stage. The business requirements should be understood first before deciding whether the final solution should use Microsoft tools, an existing aged-care system, or another platform.

---

# 12. User Acceptance Testing

I created the following UAT scenarios to check whether the proposed process meets the business requirements.

| Test ID | Scenario                                  | Expected Result                                 | Priority |
| ------- | ----------------------------------------- | ----------------------------------------------- | -------- |
| UAT-01  | Care staff views assigned tasks           | Assigned tasks are displayed                    | High     |
| UAT-02  | New task is assigned                      | Correct staff/team receives the task            | High     |
| UAT-03  | Care staff completes a task               | Status changes to Completed                     | High     |
| UAT-04  | Recurring task reaches its scheduled date | New task is generated                           | High     |
| UAT-05  | RN views task dashboard                   | Relevant outstanding tasks are displayed        | High     |
| UAT-06  | CCC reviews task status                   | Relevant task status is displayed               | High     |
| UAT-07  | Task passes its due time                  | Task is identified as Overdue                   | High     |
| UAT-08  | RN/CCC reviews overdue task               | Follow-up information is available              | High     |
| UAT-09  | Staff cannot complete a task              | Exception can be recorded                       | High     |
| UAT-10  | RN/CCC reviews an exception               | Exception and follow-up information are visible | High     |

These are **proposed UAT scenarios** for the portfolio case study. They are not claims that I tested a live production system.

---

# 13. Expected Business Benefits

If implemented successfully, I would expect the improved process to provide several benefits.

### Better communication

Staff would have a central place to see what needs to be completed.

### Better visibility

RNs and CCCs could see outstanding, completed and overdue tasks more easily.

### Less manual follow-up

The team would not need to rely entirely on verbal communication to find out whether routine tasks were completed.

### Better accountability

Task ownership and completion status would be recorded.

### Easier management of recurring tasks

Daily and weekly activities could be generated according to defined rules.

### Better handling of exceptions

Tasks that cannot be completed would be visible rather than simply disappearing from the workflow.

---

# 14. BA Skills Demonstrated

Through this project I practised:

* Stakeholder analysis
* Business problem analysis
* As-Is process mapping
* To-Be process design
* Requirements gathering
* Business requirements
* User stories
* Acceptance criteria
* Requirements traceability
* Exception analysis
* Process improvement
* Automation analysis
* UAT planning
* Business benefits analysis

---

# 15. Tools

Tools considered for this type of solution and analysis include:

* Microsoft Excel
* Microsoft Power BI
* Microsoft Power Automate
* Microsoft Lists / SharePoint
* Jira
* GitHub
* Process mapping tools

The tools are secondary to the requirements. My approach was to first understand the business problem and process, then consider which technology could support the improved process.

---

# 16. What I Learned From This Project

The main lesson from this project was that automation should not be the starting point of a Business Analysis project.

The starting point should be understanding:

**What is the problem?**

**Who is affected?**

**Why is the current process not working well?**

**What does the business actually need?**

Only after answering those questions does it make sense to consider automation or a particular technology.

This project helped me practise turning an operational problem into structured requirements and then linking those requirements through to UAT.

---

## Portfolio Disclaimer

This is a fictionalised/anonymised portfolio case study created to demonstrate my Business Analysis approach.

No confidential resident, employee, organisational or proprietary information has been included.

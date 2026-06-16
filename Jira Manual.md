# Jira Organization-Wide Task Tracking & Utilization Training

## Objective

The objective of this session is to establish a standardized Jira process across all departments for planning, tracking, effort logging, utilization reporting, and visibility of work.

Departments covered:

* BFSI
* Marketing
* Sales
* Technology
* GRC
* Staffing
* HR
* Finance

Each department will have its own Jira Project (Space), while following the same Jira governance model.

---

# Existing Department Spaces

The organization will maintain separate Jira Projects/Spaces for each function.

| Department | Jira Space                    |
| ---------- | ----------------------------- |
| BFSI       | BFSI Delivery                 |
| Marketing  | Marketing Operations          |
| Sales      | Sales Operations              |
| Technology | Technology Delivery           |
| GRC        | Governance, Risk & Compliance |
| Staffing   | Talent Acquisition            |
| HR         | HR Operations                 |
| Finance    | Finance Operations            |

For today's demonstration, the setup will be shown in one project, but the same process applies across all departmental spaces.

---

# Jira Setup Demonstration

## Step 1 – Open Department Space

Open the selected project.

Example:

**Technology Delivery**

Explain:

* Every department works within its own Jira space.
* All work performed by team members should be tracked in Jira.
* Jira becomes the single source of truth for planning, execution, and reporting.

---

## Step 2 – Explain Board Types

### Kanban Board

Best suited for:

* Continuous operational work
* Support activities
* Service requests

Examples:

* HR employee requests
* Finance payment processing
* Recruitment operations
* Compliance ticket management

### Scrum Board

Best suited for:

* Planned work
* Team commitments
* Deliverables with timelines
* Sprint-based execution

Examples:

* Technology development
* BFSI consulting assignments
* Marketing campaigns
* Compliance initiatives

### Organizational Standard

We will use:

**Scrum Boards**

because they provide:

* Better planning
* Sprint commitments
* Progress tracking
* Utilization reporting
* Capacity management

---

# Sprint Planning

## Create Sprint 1

Sprint Name:

**Sprint 1**

Duration:

**01 June – 14 June**

---

## Create Sprint 2

Sprint Name:

**Sprint 2**

Duration:

**15 June – 30 June**

---

## Sprint Rules

* Sprint duration is 2 weeks.
* Work should be planned before sprint start.
* Team members commit to completing assigned work within the sprint.
* Sprint review is conducted at sprint end.

---

# Jira Work Hierarchy

The Jira structure will be:

```text
Epic
 └── Story
      └── Task
```

---

# What is an Epic?

An Epic represents a major business objective or initiative.

Characteristics:

* Large outcome
* Usually spans several weeks or months
* Contains multiple stories

## Examples by Department

### BFSI

**Epic:**
Digital Lending Assessment Program

### Marketing

**Epic:**
FY26 Brand Awareness Initiative

### Sales

**Epic:**
South India Banking Sector Growth Plan

### Technology

**Epic:**
Client Portal Modernization

### GRC

**Epic:**
ISO 27001 Certification Readiness

### Staffing

**Epic:**
Technology Hiring Expansion

### HR

**Epic:**
Performance Management Transformation

### Finance

**Epic:**
Financial Process Automation Program

---

# What is a Story?

A Story represents a significant deliverable that contributes toward completing an Epic.

Characteristics:

* Typically completed within a sprint
* Represents meaningful business value
* Contains multiple Tasks

## Examples

### BFSI Epic:

Digital Lending Assessment Program

Stories:

* Review Lending Workflow
* Conduct Risk Assessment
* Prepare Gap Analysis Report

---

### Marketing Epic:

FY26 Brand Awareness Initiative

Stories:

* Social Media Campaign
* Industry Webinar Series
* Content Marketing Program

---

### Sales Epic:

South India Banking Sector Growth Plan

Stories:

* Prospect Identification
* Customer Engagement
* Proposal Submission

---

### Technology Epic:

Client Portal Modernization

Stories:

* User Authentication Module
* Dashboard Development
* Reporting Module Enhancement

---

### GRC Epic:

ISO 27001 Certification Readiness

Stories:

* Policy Review
* Control Assessment
* Internal Audit Preparation

---

### Staffing Epic:

Technology Hiring Expansion

Stories:

* Candidate Sourcing
* Interview Management
* Offer Management

---

### HR Epic:

Performance Management Transformation

Stories:

* Goal Setting Process
* Manager Assessments
* Employee Review Cycle

---

### Finance Epic:

Financial Process Automation Program

Stories:

* Expense Processing Automation
* Reconciliation Automation
* Reporting Automation

---

# What is a Task?

Tasks represent actual executable work performed by employees.

Characteristics:

* Assigned to an individual
* Logged daily
* Ideally 30 minutes to 3 hours
* Should be completed quickly

## Examples

### BFSI Story:

Conduct Risk Assessment

Tasks:

* Review client risk documents
* Schedule stakeholder interview
* Conduct assessment meeting
* Document findings
* Update assessment tracker

---

### Marketing Story:

Social Media Campaign

Tasks:

* Draft campaign content
* Review messaging
* Design campaign creatives
* Schedule LinkedIn posts
* Monitor campaign performance

---

### Sales Story:

Customer Engagement

Tasks:

* Research target account
* Schedule customer meeting
* Conduct discovery call
* Prepare meeting notes
* Update CRM details

---

### Technology Story:

User Authentication Module

Tasks:

* Design login screen
* Develop authentication API
* Configure database access
* Execute unit testing
* Complete code review fixes

---

### GRC Story:

Control Assessment

Tasks:

* Collect evidence
* Review access controls
* Validate policy compliance
* Record observations
* Update risk register

---

### Staffing Story:

Candidate Sourcing

Tasks:

* Publish job requirement
* Search candidate profiles
* Shortlist applicants
* Conduct screening calls
* Share shortlisted profiles

---

### HR Story:

Manager Assessments

Tasks:

* Schedule review meetings
* Send evaluation forms
* Collect manager feedback
* Consolidate ratings
* Update HR records

---

### Finance Story:

Expense Processing Automation

Tasks:

* Gather process requirements
* Document current workflow
* Configure automation rules
* Test approval workflow
* Validate output reports

---

# Assigning Work

Demonstrate:

1. Open Story
2. Create Task
3. Enter Summary
4. Enter Description
5. Assign Owner
6. Set Priority
7. Add to Sprint
8. Save

Explain:

Every individual should have clearly assigned tasks.

Ownership should always be visible.

---

# Daily Task Management

## Day-to-Day Rule

As work is performed, employees should:

* Create new tasks when required
* Update task status
* Log effort daily
* Keep task descriptions meaningful

Examples:

### Sales

Task:
Prepare proposal for ABC Bank

Estimated Effort:
2 Hours

### Marketing

Task:
Review campaign analytics

Estimated Effort:
1 Hour

### HR

Task:
Conduct candidate interview

Estimated Effort:
2 Hours

### Finance

Task:
Validate expense entries

Estimated Effort:
2 Hours

### Technology

Task:
Fix dashboard validation issue

Estimated Effort:
3 Hours

### GRC

Task:
Review vendor compliance documents

Estimated Effort:
2 Hours

---

# Effort Logging Standards

## Important Rule

Efforts must be logged only against Tasks.

Do not log efforts on:

* Epics
* Stories

Tasks become the source of truth for utilization.

---

## Effort Logging Process

Open Task

Select:

**Log Work**

Enter:

* Date
* Time Spent
* Work Description

Save

---

## Task Size Guidelines

Recommended:

* Minimum: 30 Minutes
* Maximum: 3 Hours

If work exceeds 3 hours:

Break the work into multiple tasks.

Example:

Instead of:

```text
Develop Reporting Module – 12 Hours
```

Use:

```text
Design Report Layout – 3 Hours
Create Backend API – 3 Hours
Develop UI Components – 3 Hours
Execute Testing – 3 Hours
```

---

# Sprint Execution

Task status flow:

```text
To Do
   ↓
In Progress
   ↓
Done
```

## To Do

Planned but not started.

## In Progress

Currently being worked on.

## Done

Completed and verified.

Employees should update status daily.

---

# Utilization Reporting

At month-end, utilization reports can be generated using Jira filters.

---

## Create a Filter

Example:

```text
Project = "Technology Delivery"
AND worklogDate >= startOfMonth()
AND worklogDate <= endOfMonth()
```

---

## Review Information

Display:

* Assignee
* Task
* Story
* Epic
* Logged Hours
* Sprint

---

## Management Reporting

Reports can be used to analyze:

* Individual utilization
* Team utilization
* Department utilization
* Sprint effort
* Story effort
* Epic effort
* Capacity planning
* Work completion trends

---

# Organization-Wide Jira Governance

## Epic

Strategic Initiative

Examples:

* Client Portal Modernization
* ISO Certification Readiness
* Financial Process Automation

---

## Story

Business Deliverable

Examples:

* Dashboard Development
* Policy Review
* Candidate Sourcing

---

## Task

Actual Work Item

Examples:

* Create Dashboard Widget
* Review Policy Document
* Conduct Screening Call

---

## Effort Logging

* Daily
* Task level only
* Maximum 3 hours per task

---

## Sprint Model

* 2-week sprint cycle
* Sprint planning
* Sprint execution
* Sprint review
* Continuous reporting

---

# Key Takeaways

* Every department uses its own Jira space.
* All departments follow the same Jira structure.
* Epic = Initiative.
* Story = Deliverable.
* Task = Actual Work.
* Effort is logged only on Tasks.
* Tasks should typically be 30 minutes to 3 hours.
* Work must be updated daily.
* Sprint duration is 2 weeks.
* Jira serves as the organization's single source of truth for planning, execution, utilization, and reporting.

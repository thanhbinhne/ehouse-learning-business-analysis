# Ehouse Learning – Business Analysis & Mobile Application Design

## Overview

**Ehouse Learning** is an academic Business Analysis project focused on analyzing the current learning-management processes at **Ehouse English Center** and proposing a mobile application to improve student experience and operational efficiency.

The current operating model relies heavily on fragmented channels such as websites, Zalo, Facebook, and spreadsheets for activities including course registration, class scheduling, academic requests, attendance, payment, and learning-progress tracking.

The proposed **Ehouse Learning mobile application** centralizes these interactions and provides students with a single platform to manage learning-related activities.

**Project Duration:** Apr 2026 – Jul 2026
**Role:** Business Analyst / Project Manager
**Project Type:** Academic Group Project

---

## Business Problems

Through stakeholder interviews, surveys, and on-site observations, the project identified several major operational issues:

* Student information and learning activities were distributed across multiple platforms.
* Important notifications could easily be missed when communicated through messaging applications.
* Academic requests such as leave requests, make-up classes, private tutoring, and exam rescheduling were handled manually.
* Students lacked a centralized platform to track attendance, assignments, learning progress, and academic request status.
* Repetitive administrative activities increased the workload of teaching assistants and academic staff.
* Existing processes depended heavily on manual checking and spreadsheet-based management.

---

## My Role

I contributed across the majority of the Business Analysis lifecycle, including:

* Stakeholder interviews and requirement gathering
* Surveys and on-site process observation
* Business problem and pain-point analysis
* Project Charter development
* Business Case analysis
* Stakeholder and process impact analysis
* AS-IS and TO-BE business process modeling
* Business and system requirements analysis
* User Story development
* Use Case analysis and specification
* Business Rule definition
* Functional and Non-functional Requirements
* BPMN modeling
* Class and Sequence Diagram modeling
* Wireframing and UI/UX prototyping
* Data Validation and Flow Validation
* Entity Relationship and database design
* Business impact estimation

---

## Requirement Gathering

The project applied multiple fact-finding techniques to understand the actual operations of Ehouse English Center.

### Stakeholder Interviews

A total of **10 stakeholders** were interviewed across different business roles, including management, academic administration, consulting/customer service staff, teachers, and students.

The interviews focused on:

* Existing business processes
* Operational difficulties
* System limitations
* User expectations
* Business and system requirements

### Surveys & Observation

Questionnaires and on-site observations were used to identify:

* Learning information accessibility issues
* Notification effectiveness
* Academic support request problems
* Learning-progress tracking difficulties
* Repetitive manual activities
* User expectations for the proposed mobile application

---

## Business Process Analysis

### AS-IS Analysis

The existing processes were modeled using **BPMN** to identify operational bottlenecks, manual activities, fragmented communication channels, and information gaps.

The main AS-IS processes analyzed include:

* Course Registration
* Learning Process
* Course Completion

### TO-BE Analysis

Based on the identified pain points, redesigned TO-BE processes were proposed to:

* Centralize student information
* Reduce manual communication
* Automate academic request workflows
* Improve information transparency
* Provide timely notifications
* Enable student self-service
* Improve attendance and learning-progress tracking

---

## Proposed Solution

The proposed Ehouse Learning system contains **6 core functional areas**.

### 1. Course Registration

Allows students to:

* Browse available courses
* View course details
* Submit registration information
* Request consultation
* Track the registration process

### 2. Payment

Supports:

* Payment-method selection
* QR-based payment
* Payment-status tracking
* Payment confirmation

### 3. Class Schedule & Notification

Provides:

* Personal class schedules
* Schedule-change notifications
* Notification details
* Course information

### 4. Academic Support Request

Allows students to submit and track:

* Leave requests
* Make-up class requests
* Private tutoring requests
* Exam rescheduling requests
* Request cancellation

### 5. Attendance & Learning Progress Tracking

Provides centralized access to:

* Attendance information
* Learning progress
* Assignment status
* Submitted assignments
* Overdue assignments
* Grade notifications

### 6. QR Attendance Scanning

Allows students to scan QR codes to record attendance.

The function also considers validation scenarios such as:

* Invalid QR codes
* Expired QR codes
* Closed attendance sessions
* Duplicate attendance attempts
* Scans outside the allowed time
* Network or system errors

---

## Requirements & System Modeling

System analysis was performed at both the **overall system level** and the **function level**.

The project includes:

* Business Requirements
* System Requirements
* Functional Requirements
* Non-functional Requirements
* User Stories
* Acceptance Criteria
* Business Rules
* Use Case Specifications
* BPMN Diagrams
* Use Case Diagrams
* Class Diagrams
* Sequence Diagrams
* Alternative and Exception Scenarios
* Flow Validation

Each of the **6 core functions** contains its own set of analysis artifacts.

---

## UI/UX Design

Business and system requirements were translated into mobile interfaces using **Figma**.

The UI/UX process included:

* Screen Navigation Diagram
* Wireframes
* High-fidelity Mockups
* Interactive Prototype
* Data Validation
* Flow Validation

Wireframes and mockups were organized separately for each core function to demonstrate the progression from early interface concepts to detailed user-interface designs.

---

## Data Design

The project also included data modeling to ensure alignment between business processes and system requirements.

Main deliverables include:

* Entity identification
* Attribute definition
* Data types and constraints
* Entity relationships
* Entity Relationship Diagram (ERD)
* Database normalization
* Database schema design
* Physical database implementation

The physical database was implemented in **Microsoft SQL Server**, consisting of **24 business entity tables and 1 learning-progress view**.

---

## Business Case

A Business Case was developed to evaluate the potential operational value of the proposed system.

Key projected results include:

| Metric                                            |       Estimated Value |
| ------------------------------------------------- | --------------------: |
| Current repetitive administrative processing time |   ~1,065 minutes/week |
| Estimated processing time after implementation    |   ~577.5 minutes/week |
| Estimated time reduction                          |             **45.8%** |
| Estimated monthly savings                         | **~VND 12.3 million** |
| Estimated system investment                       |  **~VND 120 million** |
| Estimated payback period                          |        **~10 months** |

> These figures are projected results from the project's Business Case and have not been validated through production implementation.

---

## Project Methodology

The project applied a **Hybrid methodology**, combining Waterfall and Agile approaches.

### Waterfall

Used mainly for:

* Requirement gathering
* Business analysis
* Scope definition
* Business process modeling
* System specification

### Agile

Used mainly for:

* UI/UX design
* Prototype development
* Iterative validation
* Interface refinement

---

## Tools & Techniques

### Business Analysis

* Requirements Gathering
* Stakeholder Interviews
* Surveys
* Observation
* AS-IS / TO-BE Analysis
* BPMN
* User Stories
* Use Cases
* Business Rules

### System Modeling

* BPMN Diagram
* Use Case Diagram
* Class Diagram
* Sequence Diagram
* ERD
* Flow Validation

### Tools

* Figma
* Microsoft SQL Server
* SQL Server Management Studio

---

## Repository Structure

```text
ehouse-learning-business-analysis/
│
├── README.md
│
├── 01-project-overview/
│   ├── project-charter.pdf
│   └── business-case.pdf
│
├── 02-requirement-gathering/
│   ├── stakeholder-interviews.pdf
│   ├── fact-finding-summary.pdf
│   ├── business-requirements.pdf
│   └── system-requirements.pdf
│
├── 03-business-process/
│   ├── as-is/
│   │   ├── course-registration.png
│   │   ├── learning-process.png
│   │   └── course-completion.png
│   │
│   ├── to-be-overall/
│   │   ├── course-registration.png
│   │   ├── learning-process.png
│   │   └── course-completion.png
│   │
│   └── pain-points-summary.pdf
│
├── 04-system-analysis/
│   ├── 00-overall/
│   │   └── overall-use-case-diagram.png
│   │
│   ├── 01-course-registration/
│   ├── 02-payment/
│   ├── 03-class-schedule-notification/
│   ├── 04-academic-support-request/
│   ├── 05-attendance-learning-progress/
│   └── 06-qr-attendance/
│
├── 05-ui-ux/
│   ├── 01-course-registration/
│   │   ├── wireframes/
│   │   └── mockups/
│   ├── 02-payment/
│   │   ├── wireframes/
│   │   └── mockups/
│   ├── 03-class-schedule-notification/
│   │   ├── wireframes/
│   │   └── mockups/
│   ├── 04-academic-support-request/
│   │   ├── wireframes/
│   │   └── mockups/
│   ├── 05-attendance-learning-progress/
│   │   ├── wireframes/
│   │   └── mockups/
│   └── 06-qr-attendance/
│       ├── wireframes/
│       └── mockups/
│
└── 06-data-design/
    ├── erd.png
    ├── database-design.pdf
    └── sql-server-implementation.pdf
```

---

## Key Deliverables

### Project-level Deliverables

* Project Charter
* Business Case
* Stakeholder Interviews
* Fact-finding Analysis
* Business Requirements
* System Requirements
* AS-IS Business Processes
* Overall TO-BE Business Processes
* Overall Use Case Diagram
* Entity Relationship Diagram

### Function-level Deliverables

For each of the 6 core functions:

* TO-BE BPMN
* Use Case Diagram
* Class Diagram
* Sequence Diagram
* Flow Validation
* Wireframes
* Mockups

---

## Key Takeaways

Through this project, I gained hands-on experience across the end-to-end Business Analysis process, from gathering stakeholder requirements and analyzing current business processes to designing TO-BE workflows, defining system requirements, developing prototypes, validating system flows, and evaluating the potential business impact of a proposed solution.

The project strengthened my ability to bridge **business needs, user requirements, process design, system specifications, and data structure** into a structured solution proposal.

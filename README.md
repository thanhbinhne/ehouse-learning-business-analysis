# Ehouse Learning – Business Analysis & Mobile Application Design

## Overview

**Ehouse Learning** is an academic Business Analysis project focused on analyzing the current learning-management processes at **Ehouse English Center** and proposing a mobile application to improve student experience and operational efficiency.

The current operating model relies heavily on fragmented channels such as websites, Zalo, Facebook, and spreadsheets for activities including course registration, class scheduling, academic requests, attendance, payment, and learning-progress tracking. The proposed Ehouse Learning application centralizes these interactions and enables students to access learning information and submit requests through a single mobile platform.

**Project Duration:** Apr 2026 – Jul 2026
**Role:** Business Analyst / Project Manager
**Project Type:** Academic Group Project

---

## Business Problems

Through stakeholder interviews, surveys, and on-site observations, the project identified several major operational issues:

* Student information and learning activities were distributed across multiple platforms.
* Important class notifications could easily be missed when communicated through messaging applications.
* Academic requests such as leave requests, make-up classes, and private tutoring were handled manually.
* Students lacked a centralized platform to track attendance, assignments, learning progress, and request status.
* Repetitive administrative tasks increased the workload for teaching assistants and academic staff.
* Existing processes depended heavily on manual data checking and spreadsheet-based management.

---

## My Role

I contributed across the majority of the Business Analysis lifecycle, including:

* Stakeholder interviews and requirement gathering
* On-site process observation
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

The project used multiple fact-finding techniques to understand the actual operations of Ehouse English Center.

### Stakeholder Interviews

A total of **10 stakeholders** were interviewed across different business roles, including:

* Management and Academic Administration
* Consulting and Customer Service staff
* Teachers
* Students

The interviews were designed to understand current workflows, operational difficulties, system limitations, and user expectations.

### Surveys

Questionnaires were used to collect quantitative feedback regarding:

* Learning information accessibility
* Notification effectiveness
* Academic support requests
* Learning progress tracking
* User expectations for the proposed mobile application

### Observation

On-site observation was conducted to understand how employees and students actually interact with existing tools such as messaging platforms, spreadsheets, and the current website.

---

## Business Process Analysis

### AS-IS Analysis

The current processes were modeled using **BPMN** to identify inefficiencies, manual activities, fragmented communication channels, and operational bottlenecks.

Key areas analyzed included:

* Course Registration
* Learning Process
* Course Completion
* Academic Support Requests
* Attendance Management
* Learning Progress Tracking

### TO-BE Analysis

Based on the identified pain points, redesigned TO-BE processes were proposed to:

* Centralize student information
* Reduce manual communication
* Automate academic request workflows
* Improve information transparency
* Provide real-time notifications
* Enable student self-service
* Improve attendance and learning-progress tracking

---

## Proposed Solution

The proposed **Ehouse Learning mobile application** contains six major functional areas:

### 1. Course Registration

Allows students to:

* Browse available courses
* View course information and schedules
* Submit registration information
* Request consultation
* Track registration status

### 2. Payment

Supports:

* Online tuition payment
* Payment status tracking
* Payment verification
* Electronic receipts

### 3. Class Schedule & Notification

Provides students with:

* Personal class schedules
* Classroom information
* Schedule-change notifications
* Important learning announcements

### 4. Academic Support Request

Allows students to submit and track requests such as:

* Leave requests
* Make-up class registration
* Private tutoring requests
* Exam rescheduling

### 5. Attendance & Learning Progress Tracking

Provides centralized access to:

* Attendance records
* Absence information
* Assignment status
* Test results
* Learning progress
* Teacher feedback

### 6. QR Attendance Scanning

Students can scan session-specific QR codes to record attendance.

Validation rules were designed for scenarios including:

* Invalid QR codes
* Expired QR codes
* Closed attendance sessions
* Duplicate attendance attempts
* Scans outside the allowed attendance period
* Network or system errors

---

## Requirements & System Modeling

The project translated business findings into structured system specifications, including:

* Business Requirements Document (BRD)
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
* Alternative and Exception Flows
* Requirements Traceability

---

## UI/UX Design

Business and system requirements were translated into mobile application interfaces using **Figma**.

The design process included:

* Screen Navigation Diagram
* Low-fidelity Wireframes
* High-fidelity Mockups
* Interactive Prototype
* Data Validation
* Flow Validation

Mockups were developed for all **6 major application functions**, ensuring that system requirements could be visually validated before implementation.

---

## Data Design

The project also included data modeling to ensure alignment between business processes and system requirements.

Deliverables included:

* Entity identification
* Attribute definition
* Data types and constraints
* Entity relationships
* Entity Relationship Diagram (ERD)
* Database normalization
* Data Dictionary
* Physical database implementation

The physical database was implemented in **Microsoft SQL Server**, consisting of **24 business entity tables and 1 learning-progress view**.

---

## Business Impact

A business case was developed to estimate the potential operational benefits of implementing Ehouse Learning.

| Metric                                            |      Estimated Impact |
| ------------------------------------------------- | --------------------: |
| Current repetitive administrative processing time |   ~1,065 minutes/week |
| Estimated processing time after implementation    |   ~577.5 minutes/week |
| Estimated time reduction                          |             **45.8%** |
| Estimated monthly savings                         | **~VND 12.3 million** |
| Estimated system investment                       |  **~VND 120 million** |
| Estimated payback period                          |        **~10 months** |

> These figures represent projected results from the project Business Case and have not been validated through production implementation.

---

## Project Methodology

The project adopted a **Hybrid methodology**, combining:

**Waterfall**

* Requirement gathering
* Business analysis
* Scope definition
* BPMN modeling
* System specification

**Agile**

* UI/UX design
* Prototype development
* Iterative validation and refinement

This approach provided structured requirement analysis while allowing iterative improvement during interface and prototype development.

---

## Tools & Techniques

**Business Analysis**

* Requirements Gathering
* Stakeholder Interviews
* Surveys
* Observation
* AS-IS / TO-BE Analysis
* BPMN
* User Stories
* Use Cases
* Business Rules

**Modeling & Design**

* BPMN Diagram
* Use Case Diagram
* Class Diagram
* Sequence Diagram
* ERD
* Wireframing
* Prototyping

**Tools**

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
│   ├── business-case.pdf
│   └── project-methodology.pdf
│
├── 02-requirement-gathering/
│   ├── stakeholder-interviews.pdf
│   ├── survey-summary.pdf
│   ├── observation-summary.pdf
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
│   │   ├── user-stories.pdf
│   │   ├── to-be-bpmn.png
│   │   ├── use-case-diagram.png
│   │   ├── use-case-specification.pdf
│   │   ├── class-diagram.png
│   │   ├── sequence-diagram-main-flow.png
│   │   ├── sequence-diagram-alternative-flow.png
│   │   ├── sequence-diagram-exception-flow.png
│   │   └── flow-validation.png
│   │
│   ├── 02-payment/
│   │   ├── user-stories.pdf
│   │   ├── to-be-bpmn.png
│   │   ├── use-case-diagram.png
│   │   ├── use-case-specification.pdf
│   │   ├── class-diagram.png
│   │   ├── sequence-diagram.png
│   │   └── flow-validation.png
│   │
│   ├── 03-class-schedule-notification/
│   │   ├── user-stories.pdf
│   │   ├── to-be-bpmn.png
│   │   ├── use-case-diagram.png
│   │   ├── use-case-specification.pdf
│   │   ├── class-diagram.png
│   │   ├── sequence-diagram.png
│   │   └── flow-validation.png
│   │
│   ├── 04-academic-support-request/
│   │   ├── user-stories.pdf
│   │   ├── to-be-bpmn.png
│   │   ├── use-case-diagram.png
│   │   ├── use-case-specification.pdf
│   │   ├── class-diagram.png
│   │   ├── sequence-diagram.png
│   │   └── flow-validation.png
│   │
│   ├── 05-attendance-learning-progress/
│   │   ├── user-stories.pdf
│   │   ├── to-be-bpmn.png
│   │   ├── use-case-diagram.png
│   │   ├── use-case-specification.pdf
│   │   ├── class-diagram.png
│   │   ├── sequence-diagram.png
│   │   └── flow-validation.png
│   │
│   └── 06-qr-attendance/
│       ├── user-stories.pdf
│       ├── to-be-bpmn.png
│       ├── use-case-diagram.png
│       ├── use-case-specification.pdf
│       ├── class-diagram.png
│       ├── sequence-diagram.png
│       └── flow-validation.png
│
├── 05-ui-ux/
│   ├── screen-navigation-diagram.png
│   ├── 01-course-registration/
│   │   ├── wireframes.pdf
│   │   └── mockups.pdf
│   ├── 02-payment/
│   ├── 03-class-schedule-notification/
│   ├── 04-academic-support-request/
│   ├── 05-attendance-learning-progress/
│   ├── 06-qr-attendance/
│   └── prototype-link.md
│
├── 06-data-design/
│   ├── erd.png
│   ├── data-dictionary.pdf
│   ├── database-design.pdf
│   └── sql-server-implementation.pdf
│
└── 07-business-impact/
    ├── business-impact-summary.pdf
    └── cost-benefit-analysis.pdf
```

---

## Key Takeaways

Through this project, I gained hands-on experience across the end-to-end Business Analysis process, from gathering stakeholder requirements and analyzing existing business processes to designing TO-BE workflows, defining system requirements, developing prototypes, validating system flows, and evaluating the potential business impact of the proposed solution.

The project strengthened my ability to bridge **business needs, user requirements, process design, and system specifications** into a structured solution proposal.

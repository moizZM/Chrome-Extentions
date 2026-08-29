# Chrome-Extentions
I creaat my own extention to solve the problems I face.
# Moiz Job Manager

A Chrome extension for managing job applications, CVs, cover letters, application status, job descriptions, notes, and recruitment history in one place.

> **Project Status:** Active Development

---

## Overview

**Moiz Job Manager** is a Chrome extension I created to make my job search easier to manage.

While applying for many engineering jobs, I noticed that my application information was spread across different places:

* Job websites
* Gmail
* CV folders
* Cover letters
* PDF documents
* Excel files
* Notes
* Browser tabs

It became difficult to remember:

* Which jobs I had already applied to
* Which CV I used
* When I applied
* Which companies rejected me
* Which applications were still pending
* Which documents were submitted
* Whether I had already seen or applied to the same vacancy

I created **Moiz Job Manager** to bring this information into one system.

---

# Main Goal

The long-term goal is to manage the complete job application process:

```text
Find Job
   ↓
Analyse Job
   ↓
Save Job
   ↓
Prepare CV / Documents
   ↓
Apply
   ↓
Track Response
   ↓
Analyse Results
   ↓
Improve Future Applications
```

---

# Current Core Features

## Job Application Management

Each job can be stored as its own application record.

A job record can contain information such as:

* Company
* Job title
* Location
* Job URL
* Application date
* Application status
* Priority
* Full job description
* CV
* Cover letter
* Additional documents
* Notes

This creates a central history of my job applications.

---

## Saved Applications

Applications can be saved and opened again later.

The saved applications section allows me to:

* Review an old application
* Edit application details
* Check application status
* See the submitted documents
* Open the original job information
* Review the job description

---

## Application Status Tracking

Applications can be tracked using statuses such as:

* Saved
* Applied
* Pending
* Interview
* Rejected
* Withdrawn
* Accepted

This makes it easier to quickly see what is happening with each application.

---

## CV and Document Management

Different jobs often need different CV versions.

Moiz Job Manager keeps the application documents connected with the job they were used for.

Documents can include:

* CV
* Cover letter
* Certificates
* Transcript
* Portfolio
* Technical project PDFs
* Other application documents

This is useful when preparing for an interview because I can check exactly what I sent to the company.

---

## Full Job Description Storage

Job advertisements often disappear after the vacancy closes.

The extension therefore keeps the full job description.

This can later be used for:

* Interview preparation
* Checking requirements
* Comparing the job against the submitted CV
* Reviewing rejected applications
* Preparing future applications
* Analysing job types

---

## Excel Import and Export

Application information can be exported and imported.

This can be useful for:

* Backup
* Data migration
* Spreadsheet analysis
* Moving data between extension versions
* Importing old job application records

---

## Dark User Interface

The extension uses a dark interface.

The goal is to keep the design:

* Clean
* Simple
* Easy to read
* Fast to navigate
* Focused on important information

---

# Current Improvements

The extension is still being improved.

Some of the latest improvements include the following.

## Five-Star Priority System

Jobs can be ranked based on importance.

Example:

```text
★☆☆☆☆  Low Priority
★★☆☆☆  Below Average
★★★☆☆  Normal
★★★★☆  High Priority
★★★★★  Very High Priority
```

This helps identify the applications that deserve more preparation or follow-up.

---

## Duplicate Application Warning

The same vacancy can appear on several websites.

For example:

* LinkedIn
* Indeed
* StepStone
* Company website
* Recruitment platforms

The extension is being improved to detect possible duplicate applications.

Possible matching information includes:

* Company
* Job title
* Location
* Job URL
* Job reference number

The goal is to warn the user before creating the same application twice.

---

## Job Numbering

Applications can be numbered to make large application lists easier to manage.

Example:

| #   | Company   | Position             |
| --- | --------- | -------------------- |
| 001 | Company A | Test Engineer        |
| 002 | Company B | Hardware Engineer    |
| 003 | Company C | Application Engineer |

---

## Delete Jobs from Main Page

A delete option is being added/improved so unnecessary application records can be removed directly from the main application list.

---

## Clickable Documents

A planned interface improvement is to make saved documents directly clickable.

Example:

```text
Application
   ↓
CV
   ↓
Click
   ↓
Open PDF
```

This avoids searching manually through computer folders.

---

## Global Notes

Not every note belongs to one application.

A global notes section is being added for information such as:

* Companies to check later
* CV changes
* Job search reminders
* Interview preparation
* Salary notes
* General tasks

These notes remain available until they are edited or deleted.

---

## Hide Empty Sections

Some application sections may contain no information.

Instead of showing large empty tabs, the improved interface should:

* Hide empty sections
* Reduce their size
* Only show them when useful information exists

This keeps the interface cleaner.

---

## Document Request Section

The document request section should only attract attention when action is required.

If no document is needed:

* It should stop glowing
* It should stop unnecessary animation
* It should become smaller

If a document is required, it can become more visible again.

---

# Planned Gmail Integration

One of the largest future features is Gmail-based recruitment tracking.

The idea is to connect recruitment emails with saved applications.

The system could detect emails such as:

* Application confirmation
* Interview invitation
* Rejection
* Offer
* Document request
* Recruitment update

Example workflow:

```text
New Recruitment Email
        ↓
Detect Company / Position
        ↓
Find Matching Application
        ↓
Understand Email Type
        ↓
Update Application
        ↓
Save Response Date
```

For example:

```text
Pending → Rejected
```

could happen automatically after a matching rejection email is detected.

---

# Planned Recruitment Analytics

Once email data and application data are connected, the extension could calculate useful job-search statistics.

Possible statistics include:

* Total applications
* Pending applications
* Rejections
* Interviews
* Offers
* Withdrawn applications
* Average employer response time
* Average rejection time
* Applications per company
* Rejections per company
* Interview rate
* Offer rate

---

## Time to Rejection

The extension could calculate:

```text
Response Time = Response Date - Application Date
```

Example:

| Company   | Applied | Rejected | Response Time |
| --------- | ------- | -------- | ------------- |
| Company A | 01 Aug  | 08 Aug   | 7 days        |
| Company B | 03 Aug  | 20 Aug   | 17 days       |
| Company C | 05 Aug  | 07 Aug   | 2 days        |

This could show which employers respond quickly and which take longer.

---

## Company Rejection Statistics

The system could also calculate:

```text
Rejection Rate =
Rejected Applications / Total Applications × 100
```

This could answer questions such as:

* Which company rejected me most?
* Which company gives me more interviews?
* Where do I still have pending applications?
* Which companies normally reply quickly?

---

# Planned Job Fit Analysis

Another major future feature is automatic job-fit scoring.

The system could compare a job advertisement against information such as:

* Education
* Work experience
* Technical skills
* Projects
* Research
* Previous CVs
* Training
* Job preferences

Example result:

| Category             | Result           |
| -------------------- | ---------------- |
| Overall Fit          | 8.4 / 10         |
| Relevant Experience  | Strong           |
| Hardware Match       | Strong           |
| Testing Match        | Strong           |
| Technical Gaps       | Small            |
| Seniority Gap        | Low              |
| Language Requirement | German preferred |

This could help decide whether a job is worth applying for before spending time creating a tailored application.

---

# Planned Automatic Job Discovery

The long-term system could also help discover new vacancies.

Possible workflow:

```text
Search New Jobs
      ↓
Check if Active
      ↓
Remove Duplicates
      ↓
Analyse Requirements
      ↓
Calculate Job Fit
      ↓
Recommend Best Jobs
```

Possible job sources could include:

* LinkedIn
* StepStep
* Indeed
* XING
* Bundesagentur für Arbeit
* Direct employer career pages
* Other job platforms

---

# Job Search Intelligence

The long-term system could compare previous application results with future jobs.

For example, it could analyse whether I receive more interviews for:

* Hardware Testing
* Test and Validation
* Power Electronics
* Embedded Hardware
* Product Engineering
* Application Engineering
* HIL Systems
* Semiconductor Engineering

This could eventually produce information such as:

> Hardware testing applications currently have a higher interview rate than general embedded engineering applications.

This would allow previous applications to improve future job-search decisions.

---

# Planned Mobile Version

I have also considered making the Job Manager available as a mobile application.

The mobile version could allow quick access to:

* Applications
* Application status
* Company information
* Notes
* Documents
* Interview information
* Rejections
* Notifications
* Analytics

The desktop Chrome extension would remain useful for finding and saving vacancies, while the mobile version could be useful for quickly checking application progress.

---

# Example Application Structure

A simplified application record can look like this:

```text
Application
│
├── ID
├── Company
├── Job Title
├── Location
├── Job URL
├── Application Date
├── Status
├── Priority
├── Full Job Description
│
├── Documents
│   ├── CV
│   ├── Cover Letter
│   ├── Certificates
│   └── Additional Files
│
├── Notes
│
├── Recruitment Events
│   ├── Confirmation
│   ├── Interview
│   ├── Rejection
│   └── Offer
│
└── Response Statistics
```

---

# Future Recruitment Timeline

Instead of storing only the current application status, a future version could store a complete recruitment timeline.

Example:

| Date   | Event                 | Source      |
| ------ | --------------------- | ----------- |
| 10 Aug | Application Submitted | Job Manager |
| 10 Aug | Confirmation Received | Gmail       |
| 20 Aug | Documents Requested   | Gmail       |
| 25 Aug | Interview Invitation  | Gmail       |

This would give each application its own recruitment history.

---

# Privacy

The extension can contain personal information such as:

* CVs
* Cover letters
* Certificates
* Academic records
* Recruitment emails
* Employer communication
* Personal notes

For this reason, privacy will be important if the extension is released publicly.

A future public version should clearly explain:

* Where data is stored
* Which information remains local
* Which external services are used
* Which Gmail permissions are required
* How data can be exported
* How data can be deleted

The goal should always be to request the minimum permissions required.

---

# Development Approach

The project is being developed step by step.

The general process is:

```text
Use Extension
      ↓
Find Problem
      ↓
Design Improvement
      ↓
Implement Feature
      ↓
Test
      ↓
Use Again
```

Many features were added because of problems found while using the extension for real job applications.

Examples include:

* Duplicate applications
* Empty tabs
* Missing documents
* Different CV versions
* Old job ads disappearing
* Global notes
* Rejection tracking
* Importing previous application data

---

# Development Roadmap

## Phase 1 — Core Job Manager

* [x] Job application records
* [x] Saved applications
* [x] Job information management
* [x] Application status
* [x] CV/document management
* [x] Full job description storage
* [x] Import/export concept
* [x] Dark interface

## Phase 2 — Interface Improvements

* [ ] Improve five-star priority system
* [ ] Improve duplicate detection
* [ ] Add/improve job numbering
* [ ] Improve delete workflow
* [ ] Make documents directly clickable
* [ ] Add global notes
* [ ] Hide empty tabs
* [ ] Improve document request section

## Phase 3 — Data Migration

* [ ] Import older Excel application data
* [ ] Automatically recreate old records
* [ ] Preserve document information where possible
* [ ] Validate imported data

## Phase 4 — Gmail Integration

* [ ] Detect application confirmations
* [ ] Detect rejection emails
* [ ] Detect interview invitations
* [ ] Detect document requests
* [ ] Match emails with applications
* [ ] Automatically update application status

## Phase 5 — Analytics

* [ ] Application statistics
* [ ] Rejection statistics
* [ ] Interview statistics
* [ ] Offer statistics
* [ ] Response-time analysis
* [ ] Company-level analysis
* [ ] Role-category analysis

## Phase 6 — Automatic Job Fit

* [ ] Store professional background
* [ ] Analyse job requirements
* [ ] Calculate fit score
* [ ] Identify strongest matches
* [ ] Identify technical gaps
* [ ] Identify seniority gaps
* [ ] Identify language requirements

## Phase 7 — Automatic Job Discovery

* [ ] Search new vacancies
* [ ] Check vacancy status
* [ ] Remove duplicate jobs
* [ ] Analyse job fit
* [ ] Rank vacancies
* [ ] Add selected jobs to Job Manager

## Phase 8 — Mobile Version

* [ ] Mobile dashboard
* [ ] Application cards
* [ ] Status updates
* [ ] Notes
* [ ] Document access
* [ ] Notifications
* [ ] Analytics

---

# Possible Future Features

Additional ideas include:

* Interview calendar
* Follow-up reminders
* Job deadlines
* Recruiter contact tracking
* Salary tracking
* Application source statistics
* CV version comparison
* Interview question notes
* Company-specific notes
* Reapplication reminders
* Automatic backups
* Search by skill
* Search by location
* Application success rate by CV version

---

# Local Chrome Installation

For development/testing:

1. Open Google Chrome.
2. Go to:

```text
chrome://extensions/
```

3. Enable **Developer mode**.
4. Click **Load unpacked**.
5. Select the Moiz Job Manager project folder.
6. Pin the extension if required.
7. Open it and start testing.

After code changes, reload the extension from the Chrome Extensions page when required.

---

# Why I Built This

The project started because I wanted to solve a problem from my own job search.

Instead of using:

```text
Browser
+ Gmail
+ Excel
+ Computer Folders
+ Notes
+ Memory
```

I wanted:

```text
One Job Application Management System
```

The project has gradually grown from a basic application tracker into a larger job-search management platform.

---

# Long-Term Vision

The complete system could eventually work like this:

```text
Job Websites
     ↓
Job Discovery
     ↓
Job Information Extraction
     ↓
Duplicate Detection
     ↓
Job Fit Analysis
     ↓
Moiz Job Manager
     ↓
CV + Cover Letter + Documents
     ↓
Application Submitted
     ↓
Gmail Recruitment Tracking
     ↓
Automatic Status Updates
     ↓
Recruitment Analytics
     ↓
Better Future Job Applications
```

---

# Current Status

As of **29 August 2026**, Moiz Job Manager is still under active development.

The core job management idea and main workflow already exist.

Current work is mainly focused on:

* Better document management
* Better duplicate detection
* Cleaner application pages
* Priority management
* Global notes
* Old application migration
* Gmail integration
* Application analytics
* Automatic job-fit scoring
* Future job discovery
* Mobile access

---

# Project Purpose

This project is not only meant to store job links.

The long-term goal is to manage the full job-search process:

**Find → Analyse → Apply → Track → Measure → Improve**

---

## Author

**Moiz Zaheer Malik**

Engineering graduate and developer of **Moiz Job Manager**.

---

## Project Status

🚧 **Active Development**

Features and interface may continue to change as the project is improved and tested.

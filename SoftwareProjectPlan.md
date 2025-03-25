
# Software Project Plan

## By
- Atakan Sezginer
- Başar Özkaşlı
- İrfan Emre Utkan

## Table of Contents
1. [Overview](#overview)
2. [High Level Functionality](#high-level-functionality)
3. [Project Staffing](#project-staffing)
   - [Assignment Staff](#assignment-staff)
   - [Requirements](#requirements)
   - [Design](#design)
   - [Iteration 1](#iteration-1)
   - [Iteration 2](#iteration-2)
   - [Iteration 3](#iteration-3)
   - [Testers](#testers)
4. [Software Process](#software-process)
   - [Iteration 1](#software-process-iteration-1)
   - [Iteration 2](#software-process-iteration-2)
   - [Iteration 3](#software-process-iteration-3)
5. [Software Engineering Methods](#software-engineering-methods)
   - [Coding Standard Verification](#coding-standard-verification)
   - [Code Reviews](#code-reviews)
   - [Coding Standard](#coding-standard)
6. [Schedule and Effort](#schedule-and-effort)
   - [Schedule](#schedule)
     - [Iteration 1](#iteration-1-schedule)
     - [Iteration 2](#iteration-2-schedule)
     - [Iteration 3](#iteration-3-schedule)
7. [Measurements](#measurements)
8. [Project Risks](#project-risks)
9. [Software Tools](#software-tools)
   - [Git](#git)
   - [Github](#github)
   - [Visual Studio Code](#visual-studio-code)
   - [Azure SQL](#azure-sql)
   - [Postman](#postman)
10. [Hardware Support](#hardware-support)
11. [Software Support](#software-support)
12. [Personnel Support](#personnel-support)

---

## Overview
This document contains the Software Project Plan for the **Library Automation System** that will be produced during the spring semester. The schedule for this project begins in **March 2025** and ends in **June 2025**. Students taking SE 3315 (Software Project Management) will develop this project. The members of this team are as follows:

- Atakan Sezginer  
- Başar Özkaşlı  
- İrfan Emre Utkan  

The Library Automation System product will provide a software package that streamlines and automates the core operations of a library. It is designed to facilitate efficient catalog management, user registration, loan processing, and comprehensive reporting. The intended customers are small to medium-sized libraries seeking to enhance operational efficiency and improve user experience.

The project scope includes:
- A web-based interface for library staff
- A cloud-hosted backend API built using Python Flask
- Persistent storage provided by Azure SQL

The final product is scheduled for completion by the beginning of **June 2025** with functional prototypes delivered at regular intervals throughout the semester. The system will be developed using an iterative development cycle:
- **Iteration 1:** Establish the core backend API and database connectivity.
- **Subsequent Iterations:** Divide the team to develop the web-based interface and enhance backend functionalities (security, data processing, etc.).
- **Final Iteration:** Integrate all components, perform rigorous testing, and optimize performance.

---

## High Level Functionality
The Library Automation System will enable librarians to efficiently manage library operations. Key functionalities include:

- **Master Catalog:**  
  Lists all books and media in a spreadsheet-like format for easy searching, updating, and record maintenance. Daily circulation logs and comprehensive reports can be generated from this catalog.

- **Loan and Reservation Management:**  
  Automatically updates the status of items when borrowed or reserved. Overdue items will be flagged for quick identification and resolution.

- **User Account Management:**  
  Tracks memberships, loan histories, and overdue items, ensuring accurate record keeping.

- **Item Categorization and Notifications:**  
  Organizes items by genre, author, and publication date for easier navigation. Automated notifications alert users when reserved items become available or when due dates are approaching. *(Note: Notification functionality may be limited if Azure credits run out.)*

---

## Project Staffing

### Assignment Staff
- **Software Project Plan:** Atakan Sezginer, İrfan Emre Utkan  
- **Requirements Document:** Atakan Sezginer, Başar Özkaşlı  
- **Implementation Plan:** Başar Özkaşlı, İrfan Emre Utkan  
- **Test Plan:** Atakan Sezginer, Başar Özkaşlı, İrfan Emre Utkan  
- **Presentation:** Atakan Sezginer, Başar Özkaşlı, İrfan Emre Utkan  

### Requirements
The Library Automation System will include:
- Sophisticated book cataloging functions
- User account administration
- Loan scheduling

*Primary contacts:*  
- Atakan Sezginer  
- Başar Özkaşlı

### Design
The system’s design will adhere to fundamental software design principles to ensure robustness, scalability, and user-friendliness.

*Design team:*  
- Başar Özkaşlı  
- İrfan Emre Utkan

### Iteration 1
Focus: Establishing the foundation of the system by determining the overall system architecture, designing the initial database schema, and allocating responsibilities for key system components. User interface work will be deferred to later iterations.

*Team:*  
- Başar Özkaşlı  
- İrfan Emre Utkan

### Iteration 2
Focus: Designing and integrating the user interface with backend services. Key functionalities such as user login, catalog presentation, and loan management will be implemented.

*Team:*  
- Başar Özkaşlı  
- İrfan Emre Utkan

### Iteration 3
Focus: Completing outstanding features and achieving full integration. This includes finalizing user account management, overdue item tracking, and report generation. Extensive testing (unit, integration, and user acceptance) will ensure functionality, data integrity, and interface responsiveness.

*Team:*  
- Başar Özkaşlı  
- İrfan Emre Utkan

### Testers
*Testing team:*  
- Atakan Sezginer  
- Başar Özkaşlı  
- İrfan Emre Utkan

---

## Software Process
The project will follow an iterative development cycle divided into three iterations.

### Software Process Iteration 1
Focus on establishing overall system architecture and detailed design:
- Outline the Python Flask backend framework
- Define API endpoints
- Develop the preliminary database design with Azure SQL

Mid-iteration, commence user interface design alongside finalizing the architectural design.

### Software Process Iteration 2
Focus on frontend development and backend extension:
- Develop the graphical user interface using HTML, CSS, JavaScript, and TypeScript.
- Implement key user operations such as browsing the catalog, login, registration, and book loan transactions.
- Extend the backend with additional endpoints for user and catalog management, reservation, and loan processing.
- Integrate the backend with a cloud-based Azure SQL database via RESTful API calls.

### Software Process Iteration 3
Focus on extensive testing and system completion:
- Perform rigorous testing for functional accuracy and consistency.
- Correct defects encountered during testing.
- Finalize integration with minimal interface or architectural changes.

---

## Software Engineering Methods

### Coding Standard Verification
Frequent code inspections will ensure that the implementation adheres to the established coding standards. Discrepancies will be documented and corrected to maintain codebase consistency.

### Code Reviews
Regular code review sessions will be organized to evaluate new features, detect potential bugs, and verify compliance with coding best practices.

### Coding Standard
All components will follow a unified coding standard covering:
- Naming conventions
- Directory organization
- Documentation
- Formatting standards

---

## Schedule and Effort

### Schedule
The following milestones are planned:

#### Iteration 1
- **Date:** 9 April 2025

#### Iteration 2
- **Date:** 30 April 2025

#### Iteration 3
- **Date:** 21 May 2025

---

## Measurements
We will track the following measurements:

- **Categorized Developer Time:**
  - **Coding:** Time spent writing and implementing application logic using Python Flask (backend) and TypeScript/JavaScript (frontend).
  - **Designing:** Time allocated to system architecture planning, database schema creation, and redesign activities.
  - **Testing:** Time spent on testing.
  
- **Code Metrics:**
  - Source lines
  - Number of classes
  - Number of methods

---

## Project Risks
The project faces the following risks:

- **Incomplete Understanding of Requirements:**  
  Some library-specific workflows (e.g., manual override of loan rules, exception handling in reservation contexts) may be overlooked, forcing potential limitations in the initial release.

- **Misconfiguration of Software Tools Due to Inexperience:**  
  Inexperience with contemporary tools (Python Flask, Azure SQL, TypeScript) could lead to misconfigurations, data loss, or delays. Severe setup failures might necessitate a technology change mid-project.

- **Steep Learning Curve for New Technologies:**  
  Unfamiliarity with Azure-based database deployment and TypeScript frontend development could result in significant time spent on learning, delaying feature implementation.

- **Team Inexperience with Windows Graphic Programming:**  
  Limited experience in integrating multiple system layers may cause issues with API communication, asynchronous request handling, and cross-component debugging, impacting productivity in later phases.

---

## Software Tools

### Git
A distributed version control system for source code management and collaboration. It assists with configuration management and version tracking throughout the project.

### Github
A web-based interface for Git that enables code sharing, issue tracking, pull request management, and team collaboration.

### Visual Studio Code
A cross-platform code editor supporting development in Python Flask (backend) and HTML, CSS, JavaScript, and TypeScript (frontend).

### Azure SQL
A cloud-hosted relational database solution that will serve as the primary data store, ensuring persistent and secure storage.

### Postman
An API development and testing tool used to verify backend endpoints and simulate client-server interactions.

---

## Hardware Support
Planned hardware includes:

- **Git Version Control Server:**  
  A remote-accessible version control system hosted on Github for source code management.

- **Communication Platform:**  
  A cloud-based solution (e.g., Microsoft Teams or Google Drive) for team collaboration.

- **Web Server:**  
  A lightweight server for hosting application deployments for testing and demonstrations.

- **Build Server:**  
  A local or cloud-based server configured for periodic builds and integration testing.

---

## Software Support
The following software will be required:

- **Git:** Version control system for source code management.
- **Github:** Web-based platform for code hosting, issue tracking, and pull request management.
- **Visual Studio Code:** Cross-platform code editor.
- **Azure SQL:** Cloud-based relational database for secure data storage.
- **Postman:** Tool for testing backend API endpoints.

---

## Personnel Support
The Library Automation System team will require support from the following personnel:

- **İrfan Emre Utkan:**  
  Responsible for setting up the development environment, including installing tools (Git, Python, Flask, Node.js) and connecting to Azure SQL. He will also assist with backend deployment and managing local systems as well as cloud service connectivity.

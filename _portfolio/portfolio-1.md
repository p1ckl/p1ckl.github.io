---
title: "Web Based User Management"
excerpt: "An online from request and user management system built using Flask.<br/>"
collection: portfolio
---


## Overview
This project is a web-based user management and academic form request system built using Flask. It incorporates Microsoft authentication through the Microsoft 365 API, which interacts with Azure and PostgreSQL for secure user login and data storage.

[View on GitHub](https://github.com/team-toronto/Web-Based-User-Management)

## Technical Architecture

### Core Components
- **Flask**: Built on Flask with a modular approach using multiple apps
- **Microsoft OAuth**: Microsoft OAuth integration using MSAL for secure, enterprise-ready login
- **PDF Generation**: LaTeX templates with dynamic content insertion for professional PDFs
- **Database**: Flexible configuration using PostgreSQL and SQLAlchemy.
- **Containerization**: Docker and Docker Compose setup for consistent deployment

### Key Features

#### Role-Based Access Control
#### Multi-Level Form Approval Workflow
#### Form Management
#### Dynamic PDF Generation

## Overview of the Systems and Components

### Authentication & Security
Implemented Microsoft OAuth for enterprise-ready authentication while maintaining a secure session management system. Role-based permissions ensure users can only access appropriate system features.

### Approval Workflow Management
Designed a flexible system where administrators can define department approval requirements for each form type. The system tracks which departments have approved and requires appropriate permissions for approvals.

### PDF Generation
Integration of LaTeX and Makefile for high-quality PDF generation required careful handling of user inputs, template management, and proper character escaping. The system generates professional-looking documents with embedded signatures.

These forms are saved in the database, which can be generated again and downloaded for record-keeping.

### User Experience
Created an intuitive interface that guides users through form submission and approval processes with clear status indicators, validation, and helpful error messages.

<iframe width="560" height="315" src="https://www.youtube.com/embed/014NwR_vO1k?si=mgDoYNN3Vwy8d368" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

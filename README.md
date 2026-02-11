# Event Management System (Capstone Project)

**Program**
TCS Salesforce Last Mile

**Organization**
Gyan Ganga Institute of Technology and Science (GGITS)

**Author**
Shubh Namdeo

**Live Site Link**
https://orgfarm-2d53aa5dc7-dev-ed.develop.my.site.com/s

---

## Project Overview
The Event Hub is a centralized web portal designed to eliminate disorganized manual event registrations. It allows administrators to post campus events and enables students to browse and register instantly using a secure, branded interface.

## Key Features
One-Click Registration: A custom Screen Flow handles the logic for student sign-ups.

Google SSO Integration: Students log in using existing college Google accounts via a Salesforce Auth Provider.

Capacity Management: Real-time tracking of available seats to prevent over-booking.

Automated Confirmations: Instant feedback and email notifications upon successful registration.

## Technical Architecture
The system is built on the Salesforce Platform using a Model-View-Controller (MVC) approach.



### Data Model
College Event: Parent object to store event names, dates, and descriptions.

Event Registration: A junction object linking users to events.

### Security
OWD: Set to Private for registrations to ensure student privacy.

Field Level Security: Ensures students can view events but cannot modify them.

### Technology Stack
Frontend: Salesforce Experience Cloud (LWR/Aura templates)

Backend Automation: Salesforce Flow Builder

Identity: Salesforce Auth Provider (Google SSO)

## Repository Structure
force-app/main/default/objects: Definitions for Custom Objects.

force-app/main/default/flows: Source code for the Registration Flows.

force-app/main/default/permissionsets: Security and access configurations.

## Contact
LinkedIn: https://www.linkedin.com/in/shubh-namdeo-8a9902186

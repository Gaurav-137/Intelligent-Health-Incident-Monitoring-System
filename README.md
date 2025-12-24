# Intelligent Health & Incident Monitoring System

## Overview
The Intelligent Health & Incident Monitoring System is a backend application built using Node.js to simulate real-world enterprise application monitoring. The system monitors application health, ingests logs, detects failures, and generates incidents to support debugging and root cause analysis.

This project is designed to reflect production-level application engineering practices used in large IT organizations.

---

## Key Features
- Application health monitoring using scheduled service checks
- Log ingestion and error tracking through RESTful APIs
- Automated incident detection based on failure patterns
- SQL-based incident management with status tracking
- Structured logging and centralized error handling
- API documentation using Swagger (OpenAPI)

---

## Tech Stack
- **Backend:** Node.js, Express.js  
- **Database:** PostgreSQL / MySQL  
- **Logging:** Winston, Morgan  
- **Authentication:** JWT  
- **Scheduling:** Cron Jobs  
- **Documentation:** Swagger  
- **Tools:** Git, Docker, Postman  

---

## System Architecture
- REST-based backend services
- Modular layered architecture (controllers, services, models)
- Centralized logging and error handling
- Relational database for incidents and logs

---

## Core Modules
- Health Check Service
- Log Ingestion Service
- Incident Detection Engine
- Incident Management APIs
- Authentication & Authorization

---

## Database Design
- Applications
- Logs
- Incidents
- Incident Status History
- Users (Admin / Viewer)

---

## How It Works
1. Services send logs to the system via REST APIs.
2. Health checks run periodically to detect failures.
3. Repeated failures trigger automatic incident creation.
4. Incidents are stored in the database with severity and status.
5. APIs allow teams to view, analyze, and resolve incidents.

---

# ObraFlow

### Smart Management for Service Providers

ObraFlow is a full-stack SaaS focused on helping independent service providers and small teams manage clients, services, quotes, payments and daily operations in one place.

This repository is the **public showcase of the project**.

> The main source code and internal infrastructure of ObraFlow are kept private.  
> This repository contains product information, architecture overviews, development progress and public documentation.

---

## The Problem

Many independent professionals and small service teams still manage their daily work using:

- WhatsApp conversations
- Paper notes
- Spreadsheets
- Informal payment records
- Disconnected client information

As the number of clients and services grows, maintaining a reliable history of operations, payments, expenses and completed work becomes increasingly difficult.

---

## The Solution

**ObraFlow** centralizes the operational and financial workflow of service providers into a single system.

The goal is to provide a straightforward management environment where professionals can follow the complete lifecycle of a service:

`Client → Quote → Service → Execution → Payment → History`

---

## Core Features

### Client Management

Centralized client records containing contact information, addresses, notes and service history.

### Service Management

Services can be organized with information such as:

- Client
- Title and description
- Service address
- Service type
- Priority
- Status
- Dates
- Final value

### Quotes

Creation and management of service quotes connected directly to clients and services.

### Payments & Receivables

Financial tracking focused on:

- Pending payments
- Amounts received
- Expected receivables
- Service values
- Operational financial history

### Work Diary

Daily operational records that document what happened during the execution of each service.

### Operational Notebook

A quick-entry environment for recording important information during day-to-day work.

### Service History

Each service maintains its own operational history, allowing records such as:

- Work performed
- Costs
- Amount charged
- Profit
- Notes
- Assigned collaborators

### Team Records

Tracking of collaborators involved in services and operational activities.

### Daily Dashboard

A focused operational view of:

- Today's services
- Overdue services
- Upcoming services
- Services without scheduled dates
- Pending quotes

---

## Technology Stack

### Frontend

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)

### Backend

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)

### Database

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)

### Infrastructure & Testing

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white)

---

## Architecture

ObraFlow follows a modular structure organized by software domains.

The backend uses a layered flow:

```text
HTTP Request
     ↓
Controller
     ↓
Service
     ↓
Repository
     ↓
PostgreSQL
```

Each layer has a specific responsibility:

**Controller**  
Handles HTTP requests and responses.

**Service**  
Contains application rules and business logic.

**Repository**  
Handles communication with the database.

**Model / Database**  
Represents and stores domain information.

This separation helps keep the project maintainable as new modules and business rules are introduced.

---

## Development Environment

The development environment is containerized with Docker.

The main application structure is:

```text
Frontend
   ↓
React + Vite

Backend
   ↓
Node.js + Express

Database
   ↓
PostgreSQL

Infrastructure
   ↓
Docker / Docker Compose
```

Automated workflows and end-to-end tests are also part of the development process.

---

## Current Status

### Active Development

ObraFlow is currently evolving from a Software Engineering academic project into a real SaaS product.

Current development priorities include:

- Product stability
- User experience
- Financial workflows
- Operational history
- Automated testing
- Security
- Maintainability
- Preparation for future beta releases

---

## Software Engineering

ObraFlow is also being developed as part of my **Software Engineering degree at Universidade de Franca — UNIFRAN**.

The project provides a practical environment for applying concepts such as:

- Requirements engineering
- Software architecture
- Database modeling
- User journey and interface design
- Business rules
- Version control
- Automated testing
- Software documentation
- Continuous integration

---

## Product Direction

ObraFlow is designed primarily for professionals such as:

- Electricians
- Plumbers
- Gutter installers
- Painters
- Installers
- Maintenance professionals
- Independent service providers
- Small service teams

The long-term goal is to create a management platform that remains simple enough for small businesses while providing reliable operational and financial control.

---

## Screenshots

Product screenshots and interface previews will be added as the public showcase evolves.

---

## Development

ObraFlow is designed and developed by:

### Elias Rodrigues de Oliveira

Software Engineering Student  
Full-Stack Developer  
Founder & Developer of ObraFlow

[![GitHub](https://img.shields.io/badge/GitHub-Elias819-181717?style=for-the-badge&logo=github)](https://github.com/Elias819)

---

## Repository Purpose

This repository exists exclusively as a **public product showcase**.

It does not contain the complete ObraFlow source code, credentials, production infrastructure or private project information.

Public documentation, screenshots and other visual materials may be added as the project evolves.

---

### ObraFlow

**Building better management tools for people who build, install, repair and deliver services every day.**

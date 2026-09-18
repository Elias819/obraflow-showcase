# ObraFlow

### Smart Management for Service Providers

ObraFlow is a full-stack SaaS designed to help independent service providers and small teams manage clients, quotes, services, payments and daily operations in one place.

> This repository is the **public showcase of ObraFlow**.  
> The main application source code, credentials and internal infrastructure are maintained privately.

---

## The Problem

Many independent professionals and small service teams still manage their daily operations using disconnected tools such as:

- WhatsApp conversations
- Paper notes
- Spreadsheets
- Informal payment records
- Disconnected client information

As the number of clients and services grows, maintaining a reliable history of operations, payments, expenses and completed work becomes increasingly difficult.

---

## The Solution

**ObraFlow** centralizes operational and financial management into a single workflow.

The platform is designed around the complete lifecycle of a service:

```text
Client
  ↓
Quote
  ↓
Service
  ↓
Execution
  ↓
Payment
  ↓
History
```

The goal is to provide a straightforward environment where service providers can organize their work without depending on scattered notes, conversations or spreadsheets.

---

## Core Features

### Client Management

Centralized client records containing:

- Contact information
- Addresses
- Notes
- Service history

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

Daily operational records documenting what happened during the execution of each service.

### Operational Notebook

A quick-entry environment for recording important information during day-to-day work.

### Service History

Each service maintains its own operational history, including:

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

ObraFlow follows a modular architecture organized by software domains.

The backend uses a layered structure:

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

### Responsibilities

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

## How to Run

This repository is a **public showcase** and does not contain the complete application source code.

The full ObraFlow application is maintained in a private repository and therefore cannot be executed directly from this repository.

The production and development source code, credentials and private infrastructure configurations are intentionally not publicly available.

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

## Software Engineering Project

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

ObraFlow is primarily designed for professionals such as:

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

## About the Developer

### Elias Rodrigues de Oliveira

**Software Engineering Student**  
**Full-Stack Developer**  
**Founder & Developer of ObraFlow**

[![GitHub](https://img.shields.io/badge/GitHub-Elias819-181717?style=for-the-badge&logo=github)](https://github.com/Elias819)

---

## Repository Purpose

This repository exists exclusively as the public showcase of **ObraFlow**.

It contains product information, architecture overviews, development progress and public documentation.

The complete source code, credentials, production infrastructure and private project information are not published here.

---

### ObraFlow

**Building better management tools for people who build, install, repair and deliver services every day.**

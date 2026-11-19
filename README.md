# Property Management Platform

A full-stack property management platform designed to simplify the management of residential properties, apartment units, tenants, leases, payments, maintenance requests, and communication.

## Overview

The platform provides property managers and landlords with centralized tools to manage their properties and tenants, while offering tenants a dedicated portal to access lease information, submit maintenance requests, track payments, and receive notifications.

## Tech Stack

### Backend
- Java 21
- Spring Boot
- Spring Security
- Spring Data JPA
- PostgreSQL
- Flyway
- Maven

### Web Frontend
- React
- TypeScript
- Vite
- Tailwind CSS

### Mobile
- React Native
- Expo (planned)

### Infrastructure
- Docker
- GitHub Actions
- REST API
- OpenAPI

## Core Features

- Property and unit management
- Tenant management
- Lease and contract management
- Rent and payment tracking
- Maintenance request management
- Events and scheduling
- Notifications
- Document management
- User roles and permissions
- Financial reporting and analytics

## Architecture

The project follows a modular monolith architecture, with clearly separated domain modules and a shared backend application.

The repository uses a monorepo structure to maintain the web application, backend API, mobile application, infrastructure, and documentation in a single repository.

## Repository Structure

```text
apps/
  web/          React web application
  mobile/       React Native mobile application

backend/
  api/          Spring Boot REST API

infrastructure/
  docker/      Infrastructure configuration

docs/
  architecture/
  requirements/
```

## Project Status

🚧 Under active development.

## License

Not licensed for redistribution or commercial use at this time.

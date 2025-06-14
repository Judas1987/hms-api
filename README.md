# Health Management System API (.NET)

![.NET Version](https://img.shields.io/badge/.NET-6.0-purple.svg)
![Status](https://img.shields.io/badge/Status-Active-brightgreen.svg)
![Version](https://img.shields.io/badge/Version-1.0.0-blue.svg)

A RESTful API built with .NET for managing patient health records, appointments, and medical data.

## Table of Contents
- [Features](#features)
- [Technologies](#technologies)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Configuration](#configuration)
- [Database Setup](#database-setup)
- [API Endpoints](#api-endpoints)
- [Authentication](#authentication)
- [Testing](#testing)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)

## Features

### Core Functionality
- Patient management (CRUD operations)
- Medical records tracking
- Appointment scheduling
- Prescription management
- Reporting and analytics

### Security Features
- JWT Authentication
- Role-based authorization (Admin, Doctor, Patient)
- Data encryption
- Audit logging

## Technologies

**Backend**:
- .NET 6
- ASP.NET Core Web API
- Entity Framework Core
- xUnit (for testing)

**Database**:
- SQL Server (or PostgreSQL)
- Redis (for caching)

**Other**:
- Swagger/OpenAPI
- Serilog (for logging)
- FluentValidation

## Prerequisites

- .NET 6 SDK
- Visual Studio 2022 or VS Code
- SQL Server 2019+
- Redis (optional)

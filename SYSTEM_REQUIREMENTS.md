# System Requirements

This document outlines the software, hardware, and environment requirements needed to run the Healthcare Management System.

---

## Software Requirements

| Component | Requirement |
|------------|-------------|
| Programming Language | Java |
| Java Version | JDK 17 or above |
| IDE Support | IntelliJ IDEA / Eclipse / NetBeans |
| Version Control | Git |
| Operating System | Windows / macOS / Linux |

---

## Required Java Libraries

This project primarily uses native Java libraries:

- Java Swing (GUI Development)
- Java IO (File Handling)
- Java Collections Framework
- Java Security Libraries
- Java Date/Time APIs

External libraries (if applicable):

- PDF generation library
- Excel export library

Add specific library names if used.

---

## Hardware Requirements

| Component | Minimum Requirement |
|------------|---------------------|
| Processor | Dual Core CPU |
| RAM | 4GB |
| Storage | 500MB free space |
| Display | 1366x768 resolution |

Recommended:

- 8GB RAM
- SSD storage

---

## File Storage Requirements

The system uses file-based storage architecture.

Required folder:

```bash
data/
```

This folder stores:

- user credentials
- patient records
- prescriptions
- financial reports
- analytics reports
- audit logs
- insurance records

Deleting these files may cause application failures.

---

## Supported User Roles

The system supports multiple user roles:

- Administrator
- Doctor
- Customer/Patient
- Staff
- Manager
- Pharmacy Personnel

Each role has different system permissions.

---

## Security Requirements

The system includes:

- Password encryption
- Session management
- Access control
- Audit logging
- Role-based permissions

---

## Browser Requirements

Not applicable.

This is a desktop-based Java application.

---

## Deployment Requirements (Future Enhancement)

For future deployment:

- MySQL/PostgreSQL
- Cloud hosting
- REST API server
- Docker containerization

---

## Recommended Development Environment

```bash
IDE: IntelliJ IDEA
JDK: 17
OS: Windows 11
GitHub Desktop / Git CLI
```

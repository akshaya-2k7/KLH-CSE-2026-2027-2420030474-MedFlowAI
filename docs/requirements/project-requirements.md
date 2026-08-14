# Project Requirements

## Functional Requirements

- Authentication, JWT, password security, and role-based authorization
- Patient, doctor, appointment, medical-record, laboratory, pharmacy, billing, emergency, notification, and administration workflows
- Gateway routing, Eureka discovery, OpenFeign/REST interaction, and OpenAPI documentation
- Specialized Patient, Doctor, Emergency, Pharmacy, Billing, and Operations Assistants
- Human approval and audit for sensitive AI-assisted workflows
- Operational dashboards and service monitoring

## Non-Functional Requirements

- Security, privacy, least privilege, and secret protection
- Modular service ownership and maintainability
- Horizontal scalability where justified
- Reliable errors, timeouts, retries, circuit breaking, and AI fallback
- Traceable logs, metrics, and audit events
- Accessibility and responsive role-based interfaces
- Automated unit, integration, API, security, end-to-end, AI, and performance tests

## Major User Stories

- As a patient, I want to book an available appointment.
- As a doctor, I want authorized patient information organized for review.
- As laboratory staff, I want test requests and status to remain traceable.
- As a pharmacist, I want verified prescriptions and stock alerts.
- As billing staff, I want traceable invoices and payment status.
- As emergency staff, I want structured information and priority alerts.
- As an administrator, I want service and operational visibility.
- As a doctor, I want a sourced AI draft summary that I must approve.

## Constraints

- Academic delivery timeframe and student resources
- Synthetic data only
- No autonomous diagnosis, prescribing, or treatment
- No committed credentials or confidential data
- No unsupported implementation, test, deployment, or impact claims


# High-Level Architecture

MedFlow AI is planned as a React frontend behind Spring Cloud Gateway, with Eureka-discovered Spring Boot healthcare services and service-owned PostgreSQL persistence. The AI Service will access Spring AI and Google Gemini API through backend-only communication.

## Service Responsibilities

| Service | Planned responsibility |
|---|---|
| Authentication | Identity, password security, JWT, roles |
| Patient | Profile, demographics, authorized history references |
| Doctor | Doctor profile, availability, care workflow views |
| Appointment | Booking, cancellation, rescheduling, queues |
| Medical Record | Clinical notes, prescriptions, report references |
| Laboratory | Requests, status, reports |
| Pharmacy | Verification, inventory, dispensing, alerts |
| Billing | Invoices, status, components, explanations |
| Notification | Appointment, emergency, pharmacy, system alerts |
| Emergency | Requests, configured priority workflow, staff alerts |
| AI Service | Agent orchestration, authorized tools, Gemini integration, feedback and audit |

## Principles

- Independently deployable services without direct cross-service database writes.
- Database-per-service where practical.
- Gateway routing and service-level authorization.
- Backend-only Gemini access with secret protection.
- Human approval for sensitive AI-assisted outcomes.
- Docker/Kubernetes readiness, automated delivery, security evidence, and observability.
- Pragmatic scope: a complete golden path is more valuable than many unfinished services.

AWS is a possible deployment target when time, budget, and evaluation value justify it.


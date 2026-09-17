# MEENERVA Startup Studios

Welcome to the engineering hub of **MEENERVA Startup Studios**, a venture builder operating modern, scalable, and secure SaaS ecosystems.

---

### About MEENERVA

MEENERVA builds a **digital operating system** for venture building: a unified, enterprise-grade architecture used to create, operate, measure, audit, and when the time comes, cleanly spin off each startup we incubate, with every piece of operational information centralized and traceable from day one.

---

### Repository Architecture & Standards

To keep each venture isolated, auditable, and easy to spin off independently, our repositories follow a consistent naming convention:

- `core-*`: Central infrastructure, identity configuration, and orchestration pipelines.
- `app-*`: Isolated startup applications and products.
- `pkg-*`: Shared internal SDKs, UI components, and utility libraries.

---

### Security & Governance

Security and governance are treated as a foundation, not an afterthought:

- **Identity:** Single sign-on and MFA enforced centrally through Keycloak.
- **Access control:** Role-based permissions, reviewed as the team and venture count grow.
- **Change management:** Code review before merge on every repository that carries production traffic.

We are actively hardening CI/CD automation, branch protection, and automated secret/vulnerability scanning across the organization, if you don't see a badge for it yet, it's on the roadmap, not assumed.

---

### Contact & Ops

For technical inquiries or infrastructure support, reach out to **sysadmin@meenerva.io**.

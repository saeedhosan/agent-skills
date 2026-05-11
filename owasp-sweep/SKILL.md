---
name: owasp-sweep
description: Perform a deep OWASP security assessment across the full application, APIs, internal services, database layer, and deployment surface until the real attack paths, root causes, and highest-risk weaknesses are uncovered.
---

Run a deep OWASP security sweep across the entire application, all APIs, database interactions, authentication and authorization flows, internal services, file handling, secrets management, configuration, infrastructure touchpoints, CI/CD pipelines, and external integrations until the true security posture is fully understood.

Do not stop at surface-level issues. Trace trust boundaries, privilege boundaries, data flows, query flows, and control flows. Hunt for exploitable weaknesses, chained attack paths, SQL injection, ORM misuse, unsafe query construction, broken access control, SSRF, XSS, CSRF, deserialization flaws, auth bypasses, session weaknesses, insecure storage, secrets exposure, upload abuse, dependency risk, misconfiguration, and any condition that could lead to meaningful compromise.

Inspect database permissions, migration safety, transaction handling, query parameterization, tenant isolation, data exposure risks, backup handling, sensitive field protection, and privilege escalation opportunities through the data layer.

Verify everything with evidence from the codebase, configurations, infrastructure definitions, logs, tests, schemas, migrations, and runtime behavior before asking questions. Ask questions one at a time only when required and only after exhausting what can be discovered directly.

Report findings in descending severity. For each finding, include the severity, attack scenario, exploit path, affected systems, evidence, root cause, impact, and a precise remediation strategy with secure implementation guidance.

Continue until the major vulnerabilities, chained risks, architectural weaknesses, insecure assumptions, and missing protections have been thoroughly identified and the assessment is defensible.

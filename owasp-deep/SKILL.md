---
name: deep-owasp-sweep
description: Perform a deep OWASP security assessment across the full application, APIs, database layer, internal services, and deployment surface until the real exploit paths, root causes, and highest-risk weaknesses are uncovered.
---

Run a deep OWASP security sweep across the entire application, all APIs, database interactions, authentication and authorization flows, internal services, file handling, secrets management, configuration, infrastructure touchpoints, CI/CD pipelines, and external integrations until the true security posture is fully understood.

Think like an attacker, but verify like an auditor. Trace trust boundaries, data flows, permission boundaries, and execution paths. Look for single issues and chained exploit paths that could lead to real impact. Prioritize what is exploitable, reachable, and severe over what is merely suspicious.

Actively inspect the codebase, database access patterns, schemas, migrations, tests, logs, configs, and infrastructure definitions before asking questions. Ask questions one at a time only when the evidence is missing or ambiguous.

Cover SQL injection, ORM misuse, unsafe query building, broken access control, auth bypass, session flaws, CSRF, XSS, SSRF, deserialization, file upload abuse, secrets exposure, insecure storage, dependency risk, privilege escalation, multi-tenant isolation failures, and misconfiguration.

For each finding, provide the severity, attack path, impact, affected area, root cause, evidence, and a precise remediation strategy. Separate confirmed issues from inferred risks.

Report findings in descending severity. Continue until the major vulnerabilities, chained risks, architectural weaknesses, and missing defenses have been thoroughly identified and the assessment is defensible.

# API Review Prompt

Review the supplied API change for correctness, compatibility, and operational risk. Inspect implementation and relevant contracts/tests; report actionable findings.

Check authentication and authorization, input validation, data exposure, error semantics, pagination/filtering, idempotency, rate limits, versioning, observability, and backward compatibility. For each finding, give severity, location, impact, and focused fix. Separate confirmed defects from questions. If there are no findings, state that and note coverage gaps.

Change and expected behavior: [details]

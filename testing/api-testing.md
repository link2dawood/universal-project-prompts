# API Testing Prompt

Create or improve tests for **[API endpoint/contract]**. Follow existing test infrastructure and exercise the public contract rather than private implementation details.

Cover valid requests, schema and boundary validation, authentication/authorization, relevant conflict/not-found/rate-limit cases, error response shape, and idempotency or pagination where applicable. Use deterministic fixtures and stub external systems. Include regression coverage for the reported issue and run the narrow endpoint test suite.

Contract and expected behavior: [details]

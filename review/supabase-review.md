# Supabase Review Prompt

Review the supplied Supabase schema, policies, SQL, Edge Functions, and client usage for correctness and security.

Verify least-privilege RLS for exposed tables/views, safe handling of service-role credentials, authenticated ownership checks, storage bucket policies, input validation, migration safety, and client/server boundaries. Check query behavior and tests against intended access. Report evidence-grounded findings with severity, affected object/location, failure condition, and remediation. List unverified assumptions separately.

Schema, policies, code, intended roles: [details]

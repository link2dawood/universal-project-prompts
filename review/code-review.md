# Code Review Prompt

Review the proposed diff as a careful maintainer. Prioritize bugs, regressions, security issues, and missing tests over style preferences.

Trace relevant call sites and existing behavior. Report findings first, ordered by severity, each with precise location, triggering condition, impact, and suggested correction. Do not report speculation as fact. Then list open questions and test gaps. If nothing actionable is found, say so clearly and describe residual risk.

Diff and context: [provide diff, requirements, relevant tests]

# Performance Recommendations Prompt

Diagnose performance in **[system/page/operation]** across relevant frontend, backend, database, and runtime layers using supplied measurements, traces, and code.

Identify the user- or system-visible objective and measured bottleneck before proposing optimization. Examine rendering and asset delivery, network/service latency, database queries, resource use, and runtime behavior without assuming every layer is a problem. For each recommendation, state evidence, expected impact, tradeoffs, and a benchmark or regression check. Separate verified causes from hypotheses; do not claim speedups without measurement.

Performance goals, metrics/traces, environment, workload, code path: [details]

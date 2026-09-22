# Onyx + aiDAPTIV+ Integration

This directory contains the Onyx integration benchmark prompts,
inference logs, and benchmark reports used to evaluate aiDAPTIV+ KV
Cache reuse.


## Benchmark Scope

The current benchmark compares Onyx + aiDAPTIV+ against the llama-server
baseline for long-context inference using:

-   8K-token workload
-   10K-token workload
-   13K-token workload
-   TTFT / prompt-processing latency
-   Generation TPS
-   KV Cache reuse
-   MoE expert cache hit rate

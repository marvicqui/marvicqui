# Mario Vicente

**Cloud & Infrastructure Consultant | Azure · Automation · Applied AI**

I work across cloud architecture, infrastructure operations and automation,
with experience in Microsoft Azure, VMware and Citrix. I focus on repeatable
changes, clear operational boundaries and technical decisions that others can review.

I am extending that foundation into applied AI, with an emphasis on evaluation,
observability and understanding how systems fail.

## Featured engineering labs

### [Agent Eval Platform](https://github.com/marvicqui/agent-eval-platform)

A Python evaluation lab for Azure architecture Q&A and declared agent tool use.
It combines versioned datasets, deterministic trajectory checks, rubric-based
evaluation and instrumentation, with a synthetic demonstration that needs no model calls.

Architecture decisions and historical model results are documented. Human
calibration is pending, and the observed position bias exceeds the stated target.
This is an evaluation lab, not a claim of production reliability.

### [Azure Cost Estimator](https://github.com/marvicqui/azure-cost-estimator-repo)

A local React demonstration of monthly cost scenarios from a user-maintained
catalogue. It includes strict XLSX parsing, quantity-based totals, synthetic
fixtures and tests that exercise malformed inputs and disabled database access.

The demo runs in memory. It does not fetch current Azure prices or demonstrate
verified cloud authentication, and it is not intended for binding financial quotes.

## Infrastructure study

[CycleCloud landing-zone scaffold](https://github.com/marvicqui/cyclecloud-lz)
explores Bicep composition, managed identity wiring, dedicated MySQL networking
and private DNS dependencies. Local compilation and contract tests make the
design inspectable. It does not install CycleCloud or provision an HPC cluster;
cloud provisioning and connectivity remain unvalidated.

## How I work

- Make changes reproducible and reviewable with scripts, tests and explicit boundaries.
- Keep evidence separate from assumptions, especially for cloud cost, security and AI quality.
- Use AI-assisted development while retaining responsibility for design and verification.
- Keep customer systems and private implementation details out of public portfolio material.

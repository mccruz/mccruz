# Mark Cruz — AI Automation & Implementation

I build reliable automation systems that connect APIs, structured data, durable state, human review, and verified handoffs. My focus is implementation work that is observable, testable, and safe to operate—not hands-off black boxes.

Open to remote roles in **AI automation, implementation, workflow engineering, and technical solutions delivery**. Connect with me on [LinkedIn](https://www.linkedin.com/in/markcastillocruz/).

## Quick portfolio tour — no setup required

No software installation is needed to review this portfolio.

- **Start with the workflow:** [n8n Job Monitor](https://github.com/mccruz/n8n-job-monitor#review-this-project-in-3-minutes--no-setup-required) shows deterministic orchestration, duplicate prevention, post-save verification, and Slack reporting.
- **See reliability engineering:** [Reliable AI Agent Ops](https://github.com/mccruz/reliable-ai-agent-ops#review-this-project-in-3-minutes-no-setup-required) shows health evidence, atomic backups, isolated restore verification, and a fail-closed human-review gate.
- **Review safety-critical automation:** [Trade Execution Safety Lab](https://github.com/mccruz/trade-execution-safety-lab#three-minute-recruiter-review--no-setup-required) shows deterministic order handling, venue reconciliation, fail-closed recovery, and restart safety without live trading.
- **Explore the business analysis:** [Chicago Bike-Share Rider Analysis](https://github.com/mccruz/case_study_divvy#review-this-project-in-3-minutes-no-setup-required) connects a validated PostgreSQL workflow to an interactive Tableau story and testable marketing ideas.

Each repository provides a short visual review path first. Local setup is clearly marked as optional for technical reviewers.

## What I build

- Workflow automation and API integrations with explicit failure handling.
- Human-in-the-loop systems with auditable state and approval boundaries.
- Python, SQLite, PostgreSQL, and SQL data workflows with reproducible checks.
- Credential-safe demos, automated tests, and documented operational limits.

## Featured projects

### [n8n Job Monitor](https://github.com/mccruz/n8n-job-monitor)

[![n8n Job Monitor: approved job feeds move through standardization, safe preview, deterministic matching, duplicate checks, verified storage, and Slack reporting.](https://raw.githubusercontent.com/mccruz/n8n-job-monitor/main/assets/workflow-overview.svg)](https://github.com/mccruz/n8n-job-monitor)

A deterministic n8n automation that collects approved job feeds, finds relevant roles, avoids duplicates, verifies saved records, and reports confirmed results to Slack.

- Applies fixed, explainable matching rules after standardizing listings from approved public feeds.
- Uses a safe preview path, stable record keys, duplicate checks, and post-save verification before reporting success.
- Preserves human review state and routes failed executions to a concise, sanitized operator alert.
- Includes importable, credential-free workflows, fictional data, and an offline demo; it never submits applications.

[Explore the repository](https://github.com/mccruz/n8n-job-monitor) · [Review the architecture](https://github.com/mccruz/n8n-job-monitor/blob/main/docs/architecture.md) · [Try the offline demo](https://github.com/mccruz/n8n-job-monitor/blob/main/docs/demo-guide.md)

### [Reliable AI Agent Ops](https://github.com/mccruz/reliable-ai-agent-ops)

[![Reliable AI Agent Ops: health evidence, atomic backup, isolated restore verification, typed receipts, and human review.](https://raw.githubusercontent.com/mccruz/reliable-ai-agent-ops/main/assets/social-preview.png)](https://github.com/mccruz/reliable-ai-agent-ops)

A credential-free Python and Docker Compose case study for operating AI-agent services with evidence, isolation, and explicit human control.

- Uses fault-isolated health probes and typed, freshness-checked evidence receipts.
- Creates atomic checksummed backups and verifies restores in an ephemeral, network-disabled container.
- Blocks recovery readiness when evidence is missing, stale, malformed, failed, future-dated, or mismatched.
- Includes a fully synthetic Docker demonstration, 47 automated tests, and Python 3.11–3.14 CI.

[Explore the repository](https://github.com/mccruz/reliable-ai-agent-ops) · [Review the architecture](https://github.com/mccruz/reliable-ai-agent-ops/blob/main/docs/architecture.md) · [See automated checks](https://github.com/mccruz/reliable-ai-agent-ops/actions/workflows/ci.yml)

### [Trade Execution Safety Lab](https://github.com/mccruz/trade-execution-safety-lab)

[![Trade Execution Safety Lab: deterministic order handling, simulated venue behavior, position reconciliation, and fail-closed recovery.](https://raw.githubusercontent.com/mccruz/trade-execution-safety-lab/main/assets/social-preview.png)](https://github.com/mccruz/trade-execution-safety-lab)

An offline Python engineering lab for safety-critical broker and exchange automation, built around deterministic simulation rather than live accounts or trading strategies.

- Normalizes submissions, fills, cancellations, and rejections while enforcing decimal-safe price, quantity, and minimum-order constraints.
- Treats the simulated venue as the source of truth for position reconciliation and defers action when execution state remains uncertain.
- Exercises partial fills, cancellation races, timeouts, reconnects, restart recovery, and duplicate-submission suppression.
- Includes eight synthetic scenarios, 88 automated tests, and Python 3.11–3.14 CI with no credentials, live network calls, market data, or performance claims.

[Explore the repository](https://github.com/mccruz/trade-execution-safety-lab) · [Review the architecture](https://github.com/mccruz/trade-execution-safety-lab/blob/main/docs/architecture.md) · [See release v1.0.0](https://github.com/mccruz/trade-execution-safety-lab/releases/tag/v1.0.0)

### [Chicago Bike-Share Rider Analysis](https://github.com/mccruz/case_study_divvy)

[![Chicago Bike-Share Rider Analysis: a PostgreSQL data-quality and customer-segmentation case study.](assets/chicago-bike-share-rider-analysis.png)](https://github.com/mccruz/case_study_divvy)

A reproducible PostgreSQL case study that turns a one-file exploratory analysis into a staged data-quality and customer-segmentation workflow.

- Separates source profiling, preparation, analysis, and post-build validation into an auditable SQL pipeline.
- Corrects cross-midnight ride duration and makes duplicate, endpoint, and operational-station rules explicit.
- Preserves historical findings as historical claims and translates observed rider patterns into testable marketing ideas.
- Documents assumptions, limitations, reproduction steps, and dataset rights; raw trip data is not redistributed.

[Explore the repository](https://github.com/mccruz/case_study_divvy) · [Read the methodology](https://github.com/mccruz/case_study_divvy/blob/main/docs/methodology.md) · [Open the Tableau story](https://public.tableau.com/app/profile/mark.cruz4539/viz/CaseStudyDivvy/Story1)

## How I work

- Make assumptions, decisions, failure states, and evidence visible.
- Default to public or synthetic data and keep credentials out of source control.
- Verify outcomes with tests, validation checks, or exact delivery receipts.
- Keep people in control of consequential decisions.
- Document how to reproduce a result and where the system's limits begin.

## Current direction

I am seeking remote AI automation and implementation roles where reliable integrations, operational workflows, clear documentation, and collaboration with nontechnical stakeholders matter.

## Connect

[LinkedIn — Mark Cruz](https://www.linkedin.com/in/markcastillocruz/)

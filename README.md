# Mark Cruz — AI Automation & Implementation

I build reliable automation systems that connect APIs, structured data, persistent records, human review, and verified delivery. My focus is production-minded implementation: clear system behavior, testable decisions, safe failure handling, and documentation that others can follow.

Open to remote roles in **AI automation, implementation, workflow engineering, and technical solutions delivery**. Connect with me on [LinkedIn](https://www.linkedin.com/in/markcastillocruz/).

## Portfolio overview

These projects can be reviewed directly on GitHub. Local setup is optional.

- [n8n Job Monitor](https://github.com/mccruz/n8n-job-monitor#review-this-project-in-3-minutes--no-setup-required) automates job-feed collection, applies explainable matching rules, prevents duplicate records, verifies saved results, and reports confirmed outcomes to Slack.
- [Reddit Community Insights](https://github.com/mccruz/reddit-community-insights-n8n) runs separate scheduled workflows for two communities, collects post and comment evidence, safely creates structured summaries, and delivers separate Slack digests.
- [Affiliate Video Automation](https://github.com/mccruz/affiliate-video-automation) ranks fictional product candidates with visible rules, builds source-grounded scripts and storyboards, and stops at a human-reviewed handoff with generation and publishing disabled.
- [Reliable AI Agent Ops](https://github.com/mccruz/reliable-ai-agent-ops#review-this-project-in-3-minutes-no-setup-required) demonstrates health checks, verified backups and restores, and an explicit human approval gate for recovery work.
- [Trade Execution Safety Lab](https://github.com/mccruz/trade-execution-safety-lab#three-minute-recruiter-review--no-setup-required) demonstrates consistent order processing, reconciliation against a simulated venue, and safe recovery from interruptions without connecting to live trading.
- [Chicago Bike-Share Rider Analysis](https://github.com/mccruz/case_study_divvy#review-this-project-in-3-minutes-no-setup-required) uses a validated PostgreSQL workflow and Tableau story to turn rider patterns into testable marketing ideas.

Each repository begins with a short visual review path and clearly separates the project overview from optional technical setup.

## What I build

- Reliable workflow automation and API integrations with clear failure handling.
- AI-assisted processes that preserve evidence and keep people responsible for important decisions.
- Python and SQL data workflows with repeatable quality checks.
- Public demonstrations that exclude credentials, plus automated tests and clearly documented operating limits.

## Featured projects

### [n8n Job Monitor](https://github.com/mccruz/n8n-job-monitor)

[![Diagram of n8n Job Monitor moving approved feeds through matching, duplicate checks, verified storage, and Slack reporting.](https://raw.githubusercontent.com/mccruz/n8n-job-monitor/main/assets/workflow-overview.svg)](https://github.com/mccruz/n8n-job-monitor)

A reliable n8n automation that collects approved job feeds, finds relevant roles, avoids duplicates, verifies saved records, and reports confirmed results to Slack.

- Applies fixed, explainable matching rules after standardizing listings from approved public feeds.
- Provides a preview before records are saved, uses stable IDs to prevent duplicates, and confirms each saved record before reporting success.
- Preserves human review decisions and sends a concise, sanitized alert when a run fails.
- Includes importable, credential-free workflows, fictional data, and an offline demo; it never submits applications.

[Repository](https://github.com/mccruz/n8n-job-monitor) · [Architecture](https://github.com/mccruz/n8n-job-monitor/blob/main/docs/architecture.md) · [Offline demo](https://github.com/mccruz/n8n-job-monitor/blob/main/docs/demo-guide.md)

### [Reddit Community Insights with n8n](https://github.com/mccruz/reddit-community-insights-n8n)

[![Diagram showing separate r/codex and r/AI_Agents inputs flowing through evidence collection, isolated summarization, and separate Slack digests.](https://raw.githubusercontent.com/mccruz/reddit-community-insights-n8n/main/assets/architecture.svg)](https://github.com/mccruz/reddit-community-insights-n8n)

A self-hosted n8n workflow that reviews daily top discussions in `r/codex` and `r/AI_Agents`, samples comments from the exact Reddit threads, creates evidence-grounded summaries, and sends one Slack digest per community.

- Runs a separate schedule for each subreddit, with independent manual tests and Slack messages.
- Defines “top” as the first three valid posts returned by Reddit's public `Top/day` RSS feed and preserves source links for review.
- Treats all Reddit content as untrusted. Summarization runs in an isolated container with restricted inputs, no tools or network access, and validated JSON output.
- Includes an importable workflow with no embedded credentials, 13 tests for the isolated summarization service, dependency auditing, automated workflow-structure checks, and public CI.

[Repository](https://github.com/mccruz/reddit-community-insights-n8n) · [Architecture](https://github.com/mccruz/reddit-community-insights-n8n/blob/main/docs/architecture.md) · [Security model](https://github.com/mccruz/reddit-community-insights-n8n/blob/main/SECURITY.md)

### [Affiliate Video Automation](https://github.com/mccruz/affiliate-video-automation)

[![Diagram showing fictional product input flowing through explainable ranking, creative planning, disabled generation, human review, and a not-published affiliate-platform handoff.](https://raw.githubusercontent.com/mccruz/affiliate-video-automation/main/assets/architecture.svg)](https://github.com/mccruz/affiliate-video-automation)

A credential-free n8n demonstration for affiliate content operations across marketplaces and social networks, with deterministic product selection and explicit safety gates.

- Parses supplied product text into a consistent candidate schema without scraping a marketplace.
- Ranks candidates using visible weights for economics, demand, trust, commuter fit, video fit, angle depth, and seasonality.
- Builds a source-grounded hook, proof, CTA, disclosure, storyboard, and provider-neutral generation brief.
- Keeps paid generation disabled, requires human review, and ends with a manual package marked `NOT_PUBLISHED`.

[Repository](https://github.com/mccruz/affiliate-video-automation) · [Architecture](https://github.com/mccruz/affiliate-video-automation/blob/main/docs/architecture.md) · [Offline demo](https://github.com/mccruz/affiliate-video-automation/blob/main/docs/demo-guide.md)

### [Reliable AI Agent Ops](https://github.com/mccruz/reliable-ai-agent-ops)

[![Diagram of health checks, backups, isolated restore tests, recovery evidence, and human approval.](https://raw.githubusercontent.com/mccruz/reliable-ai-agent-ops/main/assets/social-preview.png)](https://github.com/mccruz/reliable-ai-agent-ops)

A credential-free Python and Docker Compose case study for operating AI services with health checks, verified recovery evidence, isolation, and explicit human approval.

- Uses independent health checks and structured records that must be current and valid.
- Creates checksummed backups as a single safe operation and tests restores in a temporary container with networking disabled.
- Marks recovery as not ready when required evidence is missing, outdated, invalid, failed, future-dated, or inconsistent.
- Includes a fully synthetic Docker demonstration, 47 automated tests, and Python 3.11–3.14 CI.

[Repository](https://github.com/mccruz/reliable-ai-agent-ops) · [Architecture](https://github.com/mccruz/reliable-ai-agent-ops/blob/main/docs/architecture.md) · [Automated checks](https://github.com/mccruz/reliable-ai-agent-ops/actions/workflows/ci.yml)

### [Trade Execution Safety Lab](https://github.com/mccruz/trade-execution-safety-lab)

[![Diagram of simulated order handling, venue behavior, position checks, and safe recovery.](https://raw.githubusercontent.com/mccruz/trade-execution-safety-lab/main/assets/social-preview.png)](https://github.com/mccruz/trade-execution-safety-lab)

An offline Python engineering lab for safety-critical broker and exchange automation, built around repeatable simulation rather than live accounts or trading strategies.

- Handles submissions, fills, cancellations, and rejections consistently while using precise decimal calculations for price, quantity, and minimum-order checks.
- Compares local position records with the simulated venue and pauses action when execution status is uncertain.
- Tests partial fills, cancellation races, timeouts, reconnects, restart recovery, and prevention of duplicate submissions.
- Includes eight synthetic scenarios, 88 automated tests, and Python 3.11–3.14 CI with no credentials, live network calls, market data, or performance claims.

[Repository](https://github.com/mccruz/trade-execution-safety-lab) · [Architecture](https://github.com/mccruz/trade-execution-safety-lab/blob/main/docs/architecture.md) · [Release v1.0.0](https://github.com/mccruz/trade-execution-safety-lab/releases/tag/v1.0.0)

### [Chicago Bike-Share Rider Analysis](https://github.com/mccruz/case_study_divvy)

[![Chicago Bike-Share Rider Analysis: a PostgreSQL data-quality and customer-segmentation case study.](assets/chicago-bike-share-rider-analysis.png)](https://github.com/mccruz/case_study_divvy)

A reproducible PostgreSQL case study that turns an exploratory analysis into a structured data-quality and customer-segmentation workflow.

- Separates source review, preparation, analysis, and final validation into a traceable SQL workflow.
- Corrects cross-midnight ride duration and makes duplicate, endpoint, and operational-station rules explicit.
- Preserves historical findings as historical claims and translates observed rider patterns into testable marketing ideas.
- Documents assumptions, limitations, reproduction steps, and dataset rights; raw trip data is not redistributed.

[Repository](https://github.com/mccruz/case_study_divvy) · [Methodology](https://github.com/mccruz/case_study_divvy/blob/main/docs/methodology.md) · [Tableau story](https://public.tableau.com/app/profile/mark.cruz4539/viz/CaseStudyDivvy/Story1)

## How I work

- Make assumptions, decisions, failure states, and supporting evidence easy to inspect.
- Use public or synthetic data by default and keep credentials out of source control.
- Verify results with automated tests, validation checks, or delivery confirmations.
- Keep people responsible for consequential decisions.
- Document setup, reproduction steps, and known limitations.

## Current direction

I am seeking remote AI automation and implementation roles where reliable integrations, operational workflows, clear documentation, and collaboration with nontechnical stakeholders matter.

## Connect

[LinkedIn — Mark Cruz](https://www.linkedin.com/in/markcastillocruz/)

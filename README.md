# Mu Abbaas

**Rust Backend & Systems Engineer**

I build production-oriented backend and systems software in Rust, with a focus on payment infrastructure, distributed state, Solana, AI-agent infrastructure, protocol boundaries, and failure-safe execution.

## Engineering focus

- Rust, Tokio, Axum
- PostgreSQL, SQLx
- Solana and non-custodial payment workflows
- Distributed state, idempotency, replay protection, reconciliation
- AI-agent architecture, deterministic authority, privacy boundaries
- MCP, x402, MPP
- Testing, CI, threat modeling, operational reliability

## Selected work

### [Rust Agent Commerce Kit (RACK)](https://github.com/rock19380-ai/rack-engineering)
Production-oriented commerce infrastructure for paid MCP tools and machine-facing APIs. The private implementation covers protocol-neutral commerce authority, x402/MPP payment lifecycles, replay/idempotency, fenced execution, durable results, reconciliation, and operational observability. The public repository contains disclosure-reviewed architecture material and independently written engineering examples.

### [Basalt](https://github.com/rock19380-ai/basalt-engineering)
Solana-first, non-custodial stablecoin payment-operations infrastructure for invoice verification, signed webhooks, organization/RBAC workflows, approval-gated payouts, batch payout reconciliation, audit records, and operational tooling without server custody of customer private keys.

### [Twin](https://github.com/rock19380-ai/twin-engineering)
A user-controlled digital-twin system built around persistent identity, user modeling, memory, context isolation, judgment learning, privacy filtering, and deterministic authority boundaries around model-proposed actions. The AI model is a replaceable reasoning component, not the authority layer.

### [NeuRust](https://github.com/rock19380-ai/neurust-workspace)
Public Rust AI developer-agent experiment with a Rust CLI, Axum backend, PostgreSQL/SQLx persistence, OpenRouter integration, bounded project memory/context, and Solana-oriented tooling.

### [Axum AI Starter](https://github.com/rock19380-ai/axum-ai-starter-showcase)
A production-minded Rust foundation for streaming AI applications, covering typed errors, bounded retries, SSE, persistence, request tracing, cancellation, testing, and containerized local development. The public showcase is deliberately separated from the commercial source.

## Public engineering repositories

| Repository | Public evidence |
|---|---|
| [RACK Engineering](https://github.com/rock19380-ai/rack-engineering) | machine-commerce lifecycle, exact money, replay/idempotency, execution and reconciliation |
| [Basalt Engineering](https://github.com/rock19380-ai/basalt-engineering) | non-custodial payment operations, approval separation and payout lifecycle |
| [Twin Engineering](https://github.com/rock19380-ai/twin-engineering) | deterministic authority, action lifecycle, privacy/context boundaries |
| [NeuRust](https://github.com/rock19380-ai/neurust-workspace) | full public Rust/Axum/PostgreSQL/Next.js project |
| [Axum AI Starter Showcase](https://github.com/rock19380-ai/axum-ai-starter-showcase) | streaming API and backend reliability patterns |

## Public/private boundary

Some production and commercial repositories remain private. Public showcase repositories are curated separately so recruiters and collaborators can review architecture, engineering decisions, tests, and selected safe examples without exposing private implementation history, credentials, or commercial IP.

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

### Rust Agent Commerce Kit (RACK)
Production-oriented commerce infrastructure for paid MCP tools and machine-facing APIs. The private implementation covers protocol-neutral commerce authority, x402/MPP payment lifecycles, replay/idempotency, fenced execution, durable results, reconciliation, and operational observability. Public engineering material is maintained separately from the commercial source.

### Basalt
Solana-first, non-custodial stablecoin payment-operations infrastructure for invoice verification, signed webhooks, organization/RBAC workflows, approval-gated payouts, batch payout reconciliation, audit records, and operational tooling without server custody of customer private keys.

### Twin
A user-controlled digital-twin system built around persistent identity, user modeling, memory, context isolation, judgment learning, privacy filtering, and deterministic authority boundaries around model-proposed actions. The AI model is a replaceable reasoning component, not the authority layer.

### NeuRust
Public Rust AI developer-agent experiment with a Rust CLI, Axum backend, PostgreSQL/SQLx persistence, OpenRouter integration, bounded project memory/context, and Solana-oriented tooling.

**Public source:** https://github.com/rock19380-ai/neurust-workspace

### Axum AI Starter
A production-minded Rust foundation for streaming AI applications, covering backend reliability patterns such as typed errors, timeouts/retries, SSE, persistence, request tracing, cancellation, testing, and containerized local development. Commercial/source distribution remains separate from this portfolio profile.

## Current public/private boundary

Some production and commercial repositories are private. Public showcase repositories are curated separately so that recruiters and collaborators can review architecture, engineering decisions, tests, and selected safe examples without exposing private implementation history, credentials, or commercial IP.

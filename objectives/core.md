---
schemaVersion: treeseed.objective/v1
id: api-core
projectId: api
title: "TreeSeed API Core Objective"
outcome: "TreeSeed API exists to operate the Treeseed backend control plane, HTTP API, PostgreSQL-backed state, backend auth, operations runner, migrations, seed application, route descriptors, provider sessions, assignment leases, mode-run persistence, capacity ledger settlement, and public TreeDX federation hosting while preserving its package boundary."
status: active
---

TreeSeed API exists to operate the Treeseed backend control plane, HTTP API, PostgreSQL-backed state, backend auth, operations runner, migrations, seed application, route descriptors, provider sessions, assignment leases, mode-run persistence, capacity ledger settlement, and public TreeDX federation hosting.

This core objective is the starting direction for the TreeSeed API Knowledge Hub. It should influence every package-local workday, research note, implementation proposal, generated artifact, approval request, and release-readiness summary.

API owns durable coordination records and backend behavior behind HTTP surfaces. It must not import web UI implementation, run provider-local execution, bypass reconciliation, or expose raw provider and TreeDX credentials.

Agents working in this project should keep outputs grounded in the package README, package-local source evidence, and the TreeSeed package ownership map. When a task would cross into another package's authority, the agent should describe the boundary and route the work to the correct project instead of mutating outside this hub.

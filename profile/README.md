Below is a **public-facing GitHub README** for **NONOMOUS AI**.
Neutral, doctrine-first, OSS-friendly. Ready to paste.

---

# NONOMOUS AI

**Anti-Autonomous AI Orchestration for Software Engineering**

NONOMOUS is an open-source system that puts **intent, planning, and human approval** back at the center of AI-driven software development.

It is **anti-autonomous by design**.

---

## Why NONOMOUS Exists

AI agents can already:

* Clone repositories
* Modify code
* Run tests
* Commit changes
* Raise pull requests

The problem is not capability.

The problem is **uncontrolled autonomy**.

Most tools collapse *intent → planning → execution* into a single opaque step.
NONOMOUS separates them — deliberately.

---

## What NONOMOUS Is

NONOMOUS is an **intent-first orchestration layer** for AI executors.

It:

* Defines **how intent is expressed**
* Enforces **planning before execution**
* Requires **human approval**
* Delegates execution to **replaceable executors**
* Makes every action **auditable and reproducible**

NONOMOUS does **not** execute code itself.

---

## Executors (Pluggable)

NONOMOUS works with multiple executors, including:

* Google Jules (async AI executor)
* VM-based executors (spin up VM → clone repo → change code → test → PR)
* Self-hosted or custom agents

Executors are tools.
NONOMOUS is the governing system.

---

## Core Principles

* **Intent is mandatory**
* **Plans precede actions**
* **Human approval is structural**
* **Executors are replaceable**
* **No silent autonomy**
* **Failure is a first-class artifact**

If it cannot be inspected, it cannot be trusted.

---

## What NONOMOUS Builds (OSS)

* Intent & Plan schemas
* Executor contracts
* Reference orchestration console
* Sample executors
* Tooling for replay, inspection, and iteration

No vendor lock-in.
No proprietary workflows.
No hidden reasoning.

---

## What NONOMOUS Refuses

* Black-box agents
* Prompt-only execution
* Autonomous merges or deployments
* “Trust the model” thinking

Speed without clarity is not progress.

---

## Who This Is For

* Developers who distrust magic
* Teams running AI in production
* Engineers who want AI as infrastructure
* Organizations that value accountability over automation

---

## Project Structure (High Level)

```
nononomous/
├── core/          # Doctrine, schemas, contracts
├── executors/     # Jules, VM, and reference executors
├── console/       # Reference orchestration UI
├── sdk/           # Client SDKs
└── docs/          # Specifications and philosophy
```

---

## Status

🚧 Early-stage, doctrine-first OSS
🧠 Specs before code
🧪 Reference implementations, not production mandates

---

## Contributing

NONOMOUS welcomes contributions that:

* Improve clarity
* Strengthen contracts
* Reduce magic
* Increase inspectability

PRs that introduce hidden autonomy will be rejected.

---

## License

Apache 2.0 (planned)
Final license will be declared before v0.1.

---

## Philosophy

NONOMOUS is not here to replace engineers.

It exists to ensure that **AI never replaces engineering judgment**.

---

**NONOMOUS AI**
*Anti-Autonomous by Principle.*

---

If you want next, I can:

* Create `docs/DOCTRINE.md`
* Define `Executor Interface v1`
* Write `CONTRIBUTING.md`
* Design Console UX flow

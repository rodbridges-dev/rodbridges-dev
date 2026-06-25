# Rod Bridges

Founder & CTO, Eric AI
Building infrastructure for governed AI workflows

---

# Eric AI

## One Governance Layer. Every Workflow. Any Model.

Most organizations don't have one AI application anymore. They have many.

Customer-facing assistants, internal copilots, document workflows, automation tools, and AI-powered business applications are often developed independently. As AI adoption grows, governance becomes fragmented. Different applications implement different controls, different audit trails, different policies, and often different AI providers.

Eric provides a centralized governance layer for AI workflows.

Organizations define workflows once and govern execution consistently across teams, applications, and AI providers. Applications invoke workflows through Eric, where authorization, policy enforcement, validation, provider routing, PII protection, and audit logging are applied before execution reaches an AI model.

https://ericaicontrol.dev

---

## Focus

* AI workflow governance
* Policy enforcement and authorization
* AI execution infrastructure
* Audit and compliance systems
* Multi-provider AI architecture
* Node.js / TypeScript backend engineering

---

## What Eric Does

* Organizations define AI workflows
* Applications invoke workflows instead of models
* Eric governs execution before AI models are called
* Applies authorization, policy enforcement, validation, and audit logging consistently
* Maintains governance across applications, teams, and AI providers
* Supports Bring Your Own Key (BYOK) and provider independence

---

## How Eric Works

Applications invoke governed workflows through Eric.

```text
Applications
      │
      ▼
 Workflow
      │
      ▼
┌─────────────────────────────┐
│     Eric Governance Layer   │
│                             │
│  • Authorization            │
│  • Policy Enforcement       │
│  • Validation               │
│  • Provider Routing         │
│  • PII Protection           │
│  • Audit Logging            │
└─────────────────────────────┘
      │
      ▼
 Claude • GPT • Gemini • Other Providers
```

When applications don't specify a workflow, Eric can intelligently select an authorized workflow based on the request while still applying the same governance controls.

---

## Example Use Cases

* Support ticket classification
* Contract review
* Vendor risk assessment
* Claims processing
* Customer response review
* Clinical summary generation
* Organizations operating multiple AI applications
* Regulated environments requiring centralized governance

---

## Selected Projects

### Eric AI

A centralized governance platform for AI workflows that enables organizations to define workflows once and govern execution consistently across applications and AI providers.

### Workflow Builder *(In Progress)*

A visual workflow designer that allows organizations to create governed AI workflows without building orchestration logic by hand.

### Governed RAG Sandbox

Experimental environment for retrieval-augmented generation with centralized governance controls.

### BridgeBase

Reference Android application demonstrating modern architecture using Jetpack Compose, MVVM, and Firebase.

---

## Technologies

* TypeScript
* Node.js
* Firebase
* Cloud Functions
* REST APIs
* AI Governance
* Workflow Execution
* LLM Runtime Architecture
* Android (Kotlin / Jetpack Compose)
* iOS (Swift / SwiftUI)

---

## Philosophy

I enjoy building backend infrastructure where correctness, governance, and reliability matter more than hype.

My current work focuses on making enterprise AI systems predictable, auditable, and easier to govern at scale while allowing organizations to evolve their AI providers and workflows independently.

---

## Location

New York City Metropolitan Area

# UnderwriteAI

**Intelligence at Every Layer of the Commercial Underwriting Decision.**

---

Commercial insurers have spent decades building tools to support underwriting decisions — pricing models, risk scorecards, CAT aggregation systems, portfolio dashboards.

Most of them work. That is not the problem.

The problem is what they cannot do — regardless of how well they are built.

They cannot read a 40-page risk engineering survey and extract what actually matters. They cannot cross-reference a broker's cover note against a geocoded hazard score and flag the inconsistency. They cannot tell an underwriter — at the point of quoting — what binding this risk does to net treaty consumption. They cannot capture why a pricing deviation was made, so that six months later, when the risk attrites, anyone can reconstruct the reasoning.

Every one of those gaps is a decision made with less information than it should have been made with.

**UnderwriteAI builds agentic AI systems that close those gaps — at the point of decision, not after it.**

---

## The Underwriter's Decision Stack

All UnderwriteAI systems are built on a single framework: **The Underwriter's Decision Stack** — an 8-layer model of the commercial underwriting decision where AI inserts at every layer.

```
┌─────────────────────────────────────────────────────────────┐
│  LAYER 8 — LEARNING       Portfolio feedback, drift detect  │
├─────────────────────────────────────────────────────────────┤
│  LAYER 7 — DECISION       Bind · Decline · Refer · Counter  │
├─────────────────────────────────────────────────────────────┤
│  LAYER 6 — REINSURANCE    Net position · Treaty economics   │
├─────────────────────────────────────────────────────────────┤
│  LAYER 5 — JUDGMENT       Underwriter overlay · Audit trail │
├─────────────────────────────────────────────────────────────┤
│  LAYER 4 — PRICING        Technical premium · Deviation log │
├─────────────────────────────────────────────────────────────┤
│  LAYER 3 — COVERAGE & T&C Terms · Limits · Conditions       │
├─────────────────────────────────────────────────────────────┤
│  LAYER 2 — SIGNAL         Risk grades · Anomaly detection   │
├─────────────────────────────────────────────────────────────┤
│  LAYER 1 — DATA           Extraction · Enrichment · Gaps    │
└─────────────────────────────────────────────────────────────┘
         ▲  Evidence flows up · Learning flows down  ▼
```

The Stack is not a diagram. It is a build specification. Every repository in this organisation addresses one or more layers — with a working system, not a demo.

---

## Project Portfolio

| Project | What It Does | Stack Layers | Status |
|---|---|---|---|
| [**SubmissionIQ**](#) | Reads submission packages, extracts signals, produces structured underwriting briefs | 1, 2, 3, 4 | 🔨 In Build |
| [**PriceDesk**](#) | Technical pricing with scenario analysis, comparable retrieval, and deviation audit trails | 4, 2, 6, 8 | 📋 Scoped |
| [**RiskReader**](#) | Extracts structured risk signals from engineering survey reports | 2, 1, 3 | 📋 Scoped |
| [**LossLens**](#) | Maps claims experience back to underwriting signals, closes the UW-claims loop | 7, 1, 2, 8 | 📋 Scoped |
| [**TreatyDesk**](#) | Real-time treaty consumption monitoring and net pricing at point of decision | 6, 5, 4 | 📋 Scoped |
| [**PortfolioMind**](#) | Live accumulation intelligence and portfolio steering | 5, 3, 6, 8 | 📋 Scoped |
| [**AuditStack**](#) | Underwriting decision governance, bias detection, closed-loop learning | 8, 7, 5 | 📋 Scoped |

Every project produces:
- ✅ Working POC — Python + Claude agentic pipeline
- ✅ Architecture documentation
- ✅ Executive whitepaper
- ✅ Consulting offer

---

## Design Principles

**Human-in-the-loop at every consequential decision.**
Every agentic workflow has defined human checkpoints. The agent does the work. The underwriter owns the decision. This is not a limitation — it is the architecture.

**Closing gaps, not replacing tools.**
Existing pricing models, risk scorecards, and dashboards stay. UnderwriteAI connects them, reads what they cannot read, and captures what they cannot retain.

**Built in public.**
Every system is documented as it is built — architecture, decisions, failure modes, and lessons. Nothing is a black box.

**Practitioner-designed.**
Every system is designed by someone who has held underwriting authority, priced catastrophe-exposed portfolios, and structured reinsurance programmes. Domain depth is not a feature — it is the foundation.

---

## Technical Stack

```
Primary AI       Claude (Anthropic) — reasoning, extraction, generation
Orchestration    Python — agentic pipelines, multi-step workflows
Data             Structured + unstructured insurance documents
Architecture     Multi-agent · RAG · Human-in-the-loop checkpoints
```

---

## About

UnderwriteAI is built by **Dev Vaibhav Markandey** — IIT Bombay, ARe, 15+ years across commercial property underwriting, reinsurance pricing, actuarial analytics, and CAT modelling at AXA Gulf, RSA Oman, AXA Business Services, Fractal Analytics, and Flagstone Reinsurance.

→ [LinkedIn](https://www.linkedin.com/in/devvaibhav/)
→ [The Underwriter's Decision Stack — Framework Document](#)
→ [underwriteailabs.com](https://underwriteailabs.com)

---

*© UnderwriteAI · underwriteailabs.com*
*Built at the intersection of commercial insurance and agentic AI.*

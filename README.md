# AI-Powered Customer Success Workflows

**6 agentic workflows that bring AI into practice across the full customer lifecycle.**

This repository is a collection of designed-and-documented AI agent workflows for Customer Success teams. Each workflow describes a real-world CS problem, maps the agentic logic an AI system would follow, and outlines the tools, data sources, and integrations required to bring it to life.

These aren't theoretical. They're built from hands-on experience running CS motions across high-touch named accounts, scaled digital programs, support, training, and renewals.

---

## Why Agentic Workflows for CS?

Traditional CS automation is rule-based: *if health score drops below 60, send an email*. Agentic workflows are fundamentally different. An AI agent can:

- **Observe** signals across multiple systems (CRM, product usage, support tickets, billing)
- **Reason** about what those signals mean in context (a usage drop after onboarding means something different than a usage drop 30 days before renewal)
- **Act** by drafting communications, creating tasks, updating records, or escalating to humans
- **Learn** from outcomes to refine future actions

The result is a CS team that operates with the coverage of a digital program and the intelligence of a strategic CSM.

---

## The Workflows

| # | Workflow | CS Function | Description |
|---|----------|-------------|-------------|
| 1 | [Health Score Risk Intervention](01-health-score-risk-intervention.md) | High-Touch CS | Agent monitors account health, synthesizes risk signals, and drafts personalized outreach for named CSMs |
| 2 | [Digital Onboarding Orchestrator](02-digital-onboarding-orchestrator.md) | Digital CS | Agent guides new customers through onboarding milestones with adaptive, behavior-driven engagement |
| 3 | [Support Ticket Intelligence](03-support-ticket-intelligence.md) | Support | Agent enriches and triages incoming tickets with full customer context, flags risk, and routes to the right team |
| 4 | [Training Gap Identifier](04-training-gap-identifier.md) | Customer Training | Agent analyzes product usage patterns to identify skill gaps and recommend targeted training content |
| 5 | [Renewal Forecasting & Expansion](05-renewal-forecasting-expansion.md) | Renewals | Agent builds a rolling renewal risk forecast and surfaces expansion-ready accounts for sales |
| 6 | [Voice of Customer Aggregator](06-voice-of-customer-aggregator.md) | Cross-Functional | Agent synthesizes customer sentiment across every touchpoint into a single, actionable account narrative |

---

## How to Read Each Workflow

Every workflow follows the same structure:

1. **The Problem** - What CS challenge this solves
2. **Agent Architecture** - Visual flow diagram of how the agent thinks and acts
3. **Data Sources & Integrations** - What systems the agent connects to
4. **Agent Logic** - Step-by-step breakdown of the decision-making process
5. **Sample Output** - What the agent actually produces
6. **Success Metrics** - How you measure whether it's working
7. **Implementation Notes** - Practical considerations for building it

---

## Tech Stack Assumptions

These workflows are designed to be platform-flexible. They reference common CS tools but can be adapted:

- **CRM**: Salesforce, HubSpot, or similar
- **Product Analytics**: Pendo, Amplitude, Mixpanel, or telemetry APIs
- **Support**: Zendesk, Intercom, Freshdesk, or similar
- **Communication**: Email (SendGrid/customer.io), Slack, in-app messaging
- **AI/LLM Layer**: Claude API, OpenAI, or similar large language model
- **Orchestration**: n8n, Make, LangChain, or custom Python

---

## About the Author

Customer Success leader with experience building and scaling CS teams from the ground up, including both high-touch strategic programs for enterprise accounts and digital-led motions for scaled engagement. This repository reflects how I think about putting AI into practice to make CS teams more effective, not to replace the human element, but to amplify it.

---

*Built with practical CS experience and a bias toward making AI useful, not just interesting.*

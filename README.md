# Assembled (assembled)

Assembled is a San Francisco-headquartered support operations platform that unifies workforce management (WFM), AI agents, and AI Copilot for modern customer support teams. Founded in 2020 by former Stripe operations engineers, Assembled lets support leaders plan, schedule, and orchestrate a hybrid workforce of in-house agents, BPO vendors, and AI agents from a single system. The platform delivers ML-based volume forecasting, automated schedule generation, real-time adherence, time-off and shift-swap automation, vendor capacity planning, multichannel routing, and structured reporting across phone, email, chat, SMS, social, and back-office channels. Its AI surface includes autonomous AI Agents that resolve customer conversations end-to-end across chat, email, SMS, and voice, plus AI Copilot, which drafts replies, translates in real time, and surfaces knowledge for human agents. The Assembled REST API (api.assembledhq.com/v0) exposes people, queues, sites, teams, skills, activities, agent states, forecasts, time-off requests, requirements, working hours, QA scores, structured reports, and the Assist endpoints for AI chat responses and knowledge articles. Assembled is used by Stripe, Etsy, Robinhood, Webflow, Canva, Duolingo, Autodesk, HubSpot, Intercom, and Ramp, and integrates with Zendesk, Salesforce Service Cloud, Intercom, Kustomer, Gladly, Gorgias, Dixa, ServiceNow, Five9, Genesys Cloud, Talkdesk, Amazon Connect, NiCE, UJET, Zoom Contact Center, Slack, Okta, Workday, HiBob, Google Calendar, Shopify, Notion, Confluence, Guru, SharePoint, Fivetran, and quality tools like Klaus, Rippit (MaestroQA), evaluagent, and Observe.AI.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/assembled/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/assembled/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider
- **Access:** 3rd-Party

## Tags

- Customer Support
- Workforce Management
- WFM
- AI Agents
- AI Copilot
- Contact Center
- Customer Experience
- Support Operations
- Scheduling
- Forecasting
- Quality Assurance
- Vendor Management
- BPO

## Timestamps

- **Created:** 2026-05-24
- **Modified:** 2026-05-24

## APIs

### Assembled People API

Manage agents (people) in the Assembled workforce. List, retrieve, create, and update agents along with their roles, channels, skills, and team assignments. The People API is the entry point for syncing agents between Assembled and upstream HRIS, identity, and CRM systems and is the canonical reference for who can be scheduled or routed to in Assembled.

- **Human URL:** [https://docs.assembled.com/](https://docs.assembled.com/)

#### Tags

- People
- Agents
- Roles
- Workforce Management

#### Properties

- [Documentation](https://docs.assembled.com/)
- [OpenAPI](openapi/assembled-people-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/assembled-people-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/assembled-people-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/assembled-person-schema.json) — [JSON Schema](https://json-schema.org/specification)

### Assembled Agent State API

Read and write real-time agent state used to drive adherence reporting, live dashboards, and dynamic routing. Supports bulk state ingestion from upstream telephony and CRM platforms, a condensed non-overlapping timeline view, edit history, and platform-ID associations that link Assembled people to identities in Zendesk, Salesforce, Five9, and other integrated systems.

- **Human URL:** [https://docs.assembled.com/](https://docs.assembled.com/)

#### Tags

- Agent State
- Real-Time
- Adherence
- Operations

#### Properties

- [Documentation](https://docs.assembled.com/)
- [OpenAPI](openapi/assembled-agent-state-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/assembled-agent-state-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/assembled-agent-state-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Assembled Activities API

Create, list, and delete activities — the scheduled shifts, breaks, time off, training, and meetings that make up an agent's calendar. Includes bulk creation, soft-delete semantics, and management of activity types with their color coding. Companion event_changes endpoint surfaces the audit trail for schedule modifications.

- **Human URL:** [https://docs.assembled.com/](https://docs.assembled.com/)

#### Tags

- Activities
- Shifts
- Scheduling
- Workforce Management

#### Properties

- [Documentation](https://docs.assembled.com/)
- [OpenAPI](openapi/assembled-activities-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/assembled-activities-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/assembled-activities-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/assembled-activity-schema.json) — [JSON Schema](https://json-schema.org/specification)

### Assembled Filters API

Manage the four organizational filter dimensions used throughout Assembled — Queues, Sites, Teams, and Skills. Each filter is fully CRUD-capable and is referenced by people, activities, forecasts, requirements, and reports. Queues map to channels and case types, Sites represent physical or virtual locations, Teams group people, and Skills describe routing-relevant capabilities.

- **Human URL:** [https://docs.assembled.com/](https://docs.assembled.com/)

#### Tags

- Queues
- Sites
- Teams
- Skills
- Organization

#### Properties

- [Documentation](https://docs.assembled.com/)
- [OpenAPI](openapi/assembled-filters-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/assembled-filters-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/assembled-filters-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Assembled Forecasts API

Retrieve Assembled's ML-generated forecasts, forecast totals, manual adjustments, and detected outliers. The forecasted-vs-actuals endpoint compares predicted to realised volume so support leaders can tune models, identify drift, and validate >90% forecast accuracy claims. Forecasts drive AI-powered schedule generation and staffing recommendations across human and AI agents.

- **Human URL:** [https://docs.assembled.com/](https://docs.assembled.com/)

#### Tags

- Forecasts
- ML
- Volume
- Workforce Planning

#### Properties

- [Documentation](https://docs.assembled.com/)
- [OpenAPI](openapi/assembled-forecasts-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/assembled-forecasts-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/assembled-forecasts-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Assembled Time Off API

Programmatically create, list, and cancel time-off requests, and pull a stream of time-off updates for downstream HRIS or payroll synchronisation. The endpoint underpins the automated time-off and shift-swap workflows offered in Assembled's Pro and Enterprise plans.

- **Human URL:** [https://docs.assembled.com/](https://docs.assembled.com/)

#### Tags

- Time Off
- Leave
- Workforce Management

#### Properties

- [Documentation](https://docs.assembled.com/)
- [OpenAPI](openapi/assembled-time-off-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/assembled-time-off-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/assembled-time-off-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Assembled Requirements API

Create and list staffing requirements that express how many agents are needed by queue, site, team, or skill across time intervals. Requirement types describe the family of need (for example, headcount vs. occupancy targets). Requirements feed AI scheduling and real-time staffing recommendations.

- **Human URL:** [https://docs.assembled.com/](https://docs.assembled.com/)

#### Tags

- Requirements
- Coverage
- Staffing

#### Properties

- [Documentation](https://docs.assembled.com/)
- [OpenAPI](openapi/assembled-requirements-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/assembled-requirements-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/assembled-requirements-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Assembled Scheduling Rules API

Retrieve the working-hours rules that constrain when each agent may be scheduled. Working hours are the structured replacement for the now-deprecated shift_patterns endpoints and are honoured by Assembled's AI-powered schedule generation engine.

- **Human URL:** [https://docs.assembled.com/](https://docs.assembled.com/)

#### Tags

- Scheduling
- Working Hours
- Rules

#### Properties

- [Documentation](https://docs.assembled.com/)
- [OpenAPI](openapi/assembled-scheduling-rules-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/assembled-scheduling-rules-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/assembled-scheduling-rules-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Assembled Conversations API

Bulk-ingest and bulk-update customer conversation records — phone, email, chat, SMS, social, and back-office — so they can be associated with agents, queues, and channels for reporting, QA, and analytics. Used by customers running on non-Zendesk/Salesforce stacks or merging multiple CRMs into a unified support view.

- **Human URL:** [https://docs.assembled.com/](https://docs.assembled.com/)

#### Tags

- Conversations
- Channels
- Customer Interactions

#### Properties

- [Documentation](https://docs.assembled.com/)
- [OpenAPI](openapi/assembled-conversations-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/assembled-conversations-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/assembled-conversations-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/assembled-conversation-schema.json) — [JSON Schema](https://json-schema.org/specification)

### Assembled Reports API

Asynchronously generate and retrieve structured reports including adherence, ticket statistics, and handle times. Reports are kicked off with a POST /v0/reports/:reportType call and polled via GET /v0/reports/:reportID for results, enabling automated weekly and monthly KPI exports into BI tools.

- **Human URL:** [https://docs.assembled.com/](https://docs.assembled.com/)

#### Tags

- Reports
- Analytics
- Adherence
- Handle Time

#### Properties

- [Documentation](https://docs.assembled.com/)
- [OpenAPI](openapi/assembled-reports-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/assembled-reports-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/assembled-reports-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Assembled QA API

Upload QA scores in bulk so external quality-management tools such as Klaus, Rippit (MaestroQA), evaluagent, and Observe.AI can feed conversation scores back into Assembled for adherence-vs-quality analysis and coaching workflows.

- **Human URL:** [https://docs.assembled.com/](https://docs.assembled.com/)

#### Tags

- Quality Assurance
- Scoring
- Coaching

#### Properties

- [Documentation](https://docs.assembled.com/)
- [OpenAPI](openapi/assembled-qa-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/assembled-qa-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/assembled-qa-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Assembled Assist API

The AI surface of Assembled. Submit chat responses generated by AI Agents, manage the knowledge articles AI Agents draw from, retrieve conversation histories and handoff payloads, and (beta) post AI replies. Powers autonomous resolution across chat, email, SMS, and voice plus smart handoffs to human agents.

- **Human URL:** [https://docs.assembled.com/](https://docs.assembled.com/)

#### Tags

- Assist
- AI Copilot
- AI Agents
- Knowledge

#### Properties

- [Documentation](https://docs.assembled.com/)
- [OpenAPI](openapi/assembled-assist-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/assembled-assist-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/assembled-assist-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/assembled-assist-response-schema.json) — [JSON Schema](https://json-schema.org/specification)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [Website](https://www.assembled.com)
- [Portal](https://docs.assembled.com/)
- [Documentation](https://docs.assembled.com/)
- [Getting Started](https://docs.assembled.com/)
- [Sign Up](https://app.assembledhq.com/signup)
- [Login](https://app.assembledhq.com/login)
- [Pricing](https://www.assembled.com/pricing)
- [Plans](plans/assembled-plans-pricing.yml)
- [Rate Limits](rate-limits/assembled-rate-limits.yml)
- [Fin Ops](finops/assembled-finops.yml)
- [Status Page](https://status.assembled.com)
- [Blog](https://www.assembled.com/blog)
- [Customers](https://www.assembled.com/customers)
- [About](https://www.assembled.com/about)
- [Careers](https://www.assembled.com/careers)
- [Contact](https://www.assembled.com/contact)
- [Support](https://support.assembled.com)
- [Privacy Policy](https://www.assembled.com/privacy)
- [Terms of Service](https://www.assembled.com/terms)
- [Trust Center](https://trust.assembled.com)
- [Security Policy](https://www.assembled.com/security)
- [GitHub Organization](https://github.com/assembledhq)
- [SDK](https://github.com/assembledhq/assembled-chat-ios-sdk)
- [SDK](https://github.com/assembledhq/assembled-chat-android-sdk)
- [LinkedIn](https://www.linkedin.com/company/assembledhq)
- [Twitter](https://twitter.com/assembledhq)
- [YouTube](https://www.youtube.com/@assembledhq)
- [App Exchange](https://appexchange.salesforce.com/appxListingDetail?listingId=22604eaa-c6cf-4357-bec0-297e4236345f)
- [Integrations](https://www.assembled.com/integrations)
- [Product](https://www.assembled.com/products/workforce-management)
- [Product](https://www.assembled.com/products/ai-agents)
- [Product](https://www.assembled.com/products/ai-copilot)
- [Product](https://www.assembled.com/products/vendor-management)
- [JSON-LD](json-ld/assembled-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Vocabulary](vocabulary/assembled-vocabulary.yml)
- [Spectral Ruleset](rules/assembled-rules.yml)
- [Features](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com
**URL:** https://apievangelist.com

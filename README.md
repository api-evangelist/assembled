# Assembled (assembled)

Assembled is a San Francisco-headquartered support operations platform that unifies workforce management (WFM), AI agents, and AI Copilot for modern customer support teams. Founded in 2020 by former Stripe operations engineers, Assembled lets support leaders plan, schedule, and orchestrate a hybrid workforce of in-house agents, BPO vendors, and AI agents from a single system. The Assembled REST API (`https://api.assembledhq.com/v0/`) exposes people, queues, sites, teams, skills, activities, agent states, forecasts, time-off requests, requirements, working hours, QA scores, structured reports, and the Assist endpoints for AI chat responses and knowledge articles. Customers include Stripe, Etsy, Robinhood, Webflow, Canva, Duolingo, Autodesk, HubSpot, Intercom, and Ramp.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/assembled/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

- Customer Support, Workforce Management, WFM, AI Agents, AI Copilot, Contact Center, Customer Experience, Support Operations, Scheduling, Forecasting, Quality Assurance, Vendor Management, BPO

## Timestamps

- **Created:** 2026-05-24
- **Modified:** 2026-05-24

## Platform at a Glance

| Surface | Description |
|---|---|
| Workforce Management | ML forecasting, AI-powered scheduling, real-time adherence, time off, shift swaps |
| AI Agents | Autonomous resolution across chat, email, SMS, voice with smart handoffs |
| AI Copilot | Reply drafting, real-time translation, summarisation, agent guidance, tone modifiers |
| Vendor Management (Add-on) | Capacity planning, scheduling integration, coverage heatmaps, billing reports |
| REST API (`/v0`) | 12 logical APIs covering people, scheduling, forecasting, QA, reporting, and Assist |
| Mobile SDKs | Official iOS (Swift) and Android (Kotlin) chat widget SDKs |

## Authentication and Conventions

- Base URL: `https://api.assembledhq.com/v0/`
- Auth: HTTP Basic Auth — API key (`sk_live_...`) as username, blank password
- Versioning: date-based `API-Version` header
- Rate limit: 300 req/min (5 req/s) per API key with bursts up to 20; `429` on throttling
- Bulk operations supported on most write endpoints; soft-delete semantics for activities and filters

## APIs

### Assembled People API
Manage agents (people) in the workforce and discover available roles.

**Human URL:** [https://docs.assembled.com/](https://docs.assembled.com/)

- [OpenAPI](openapi/assembled-people-api-openapi.yml)
- [JSON Schema — Person](json-schema/assembled-person-schema.json)
- [Naftiko Capability — People](capabilities/people-people.yaml)
- [Naftiko Capability — Roles](capabilities/people-roles.yaml)

### Assembled Agent State API
Real-time agent state, condensed timelines, state edits, and platform-ID associations.

- [OpenAPI](openapi/assembled-agent-state-api-openapi.yml)
- [Naftiko Capability — Agent State](capabilities/agent-state-state.yaml)

### Assembled Activities API
Shifts, breaks, time off, meetings; activity types and event-change audit trail.

- [OpenAPI](openapi/assembled-activities-api-openapi.yml)
- [JSON Schema — Activity](json-schema/assembled-activity-schema.json)
- [Naftiko Capability — Activities](capabilities/activities-activities.yaml)
- [Naftiko Capability — Activity Types](capabilities/activities-activity-types.yaml)

### Assembled Filters API
CRUD for Queues, Sites, Teams, and Skills — the four organisational filter dimensions.

- [OpenAPI](openapi/assembled-filters-api-openapi.yml)
- [Naftiko Capability — Queues](capabilities/filters-queues.yaml)
- [Naftiko Capability — Sites](capabilities/filters-sites.yaml)
- [Naftiko Capability — Teams](capabilities/filters-teams.yaml)
- [Naftiko Capability — Skills](capabilities/filters-skills.yaml)

### Assembled Forecasts API
ML forecasts, totals, manual adjustments, outliers, and forecasted-vs-actuals comparison.

- [OpenAPI](openapi/assembled-forecasts-api-openapi.yml)
- [Naftiko Capability — Forecasts](capabilities/forecasts-forecasts.yaml)
- [Naftiko Capability — Adjustments](capabilities/forecasts-adjustments.yaml)
- [Naftiko Capability — Outliers](capabilities/forecasts-outliers.yaml)

### Assembled Time Off API
Create, list, cancel time-off requests and stream updates for HRIS/payroll sync.

- [OpenAPI](openapi/assembled-time-off-api-openapi.yml)
- [Naftiko Capability — Time Off](capabilities/time-off-requests.yaml)

### Assembled Requirements API
Staffing requirements by queue/site/team/skill across intervals; requirement types.

- [OpenAPI](openapi/assembled-requirements-api-openapi.yml)
- [Naftiko Capability — Requirements](capabilities/requirements-requirements.yaml)

### Assembled Scheduling Rules API
Per-agent working-hours rules honoured by AI-powered schedule generation.

- [OpenAPI](openapi/assembled-scheduling-rules-api-openapi.yml)
- [Naftiko Capability — Working Hours](capabilities/scheduling-rules-working-hours.yaml)

### Assembled Conversations API
Bulk upsert and update customer conversation records across all channels.

- [OpenAPI](openapi/assembled-conversations-api-openapi.yml)
- [JSON Schema — Conversation](json-schema/assembled-conversation-schema.json)
- [Naftiko Capability — Conversations](capabilities/conversations-conversations.yaml)

### Assembled Reports API
Async generation and retrieval of adherence, ticket-stats, and handle-time reports.

- [OpenAPI](openapi/assembled-reports-api-openapi.yml)
- [Naftiko Capability — Reports](capabilities/reports-reports.yaml)

### Assembled QA API
Bulk-upload QA scores from Klaus, Rippit (MaestroQA), evaluagent, and Observe.AI.

- [OpenAPI](openapi/assembled-qa-api-openapi.yml)
- [Naftiko Capability — QA Scores](capabilities/qa-scores.yaml)

### Assembled Assist API
AI Agent responses, knowledge articles, AI conversation history, smart-handoff payloads.

- [OpenAPI](openapi/assembled-assist-api-openapi.yml)
- [JSON Schema — Assist Response](json-schema/assembled-assist-response-schema.json)
- [Naftiko Capability — Assist Responses](capabilities/assist-responses.yaml)
- [Naftiko Capability — Assist Articles](capabilities/assist-articles.yaml)
- [Naftiko Capability — Assist Conversations](capabilities/assist-conversations.yaml)

## Customers

Stripe, Etsy, Robinhood, Webflow, Canva, Duolingo, Autodesk, HubSpot, Intercom, Ramp, and many more.

## Integrations

| Category | Integrations |
|---|---|
| CCaaS / Telephony | Amazon Connect, Five9, Genesys Cloud, NiCE (inContact), Regal, Talkdesk, UJET, Zoom Contact Center |
| CRM / Helpdesk | Dixa, Gladly, Gorgias, Intercom, Kustomer, Salesforce Service Cloud, ServiceNow, Zendesk, Zoom |
| HRIS | HiBob, Workday |
| Knowledge Base | Confluence, Google Drive, Guru, Helpjuice, Notion, SharePoint |
| Quality Management | evaluagent, Klaus, Observe.AI, Rippit (formerly MaestroQA) |
| Productivity / Other | Fivetran, Google Calendar, Shopify, Slack |

## Common Properties

- [Website — assembled.com](https://www.assembled.com)
- [Documentation — docs.assembled.com](https://docs.assembled.com/)
- [Pricing](https://www.assembled.com/pricing)
- [Customers](https://www.assembled.com/customers)
- [Integrations](https://www.assembled.com/integrations)
- [StatusPage](https://status.assembled.com)
- [Blog](https://www.assembled.com/blog)
- [Support](https://support.assembled.com)
- [TrustCenter](https://trust.assembled.com)
- [GitHubOrganization — assembledhq](https://github.com/assembledhq)
- [SDK — iOS Chat Widget](https://github.com/assembledhq/assembled-chat-ios-sdk)
- [SDK — Android Chat Widget](https://github.com/assembledhq/assembled-chat-android-sdk)
- [Salesforce AppExchange Listing](https://appexchange.salesforce.com/appxListingDetail?listingId=22604eaa-c6cf-4357-bec0-297e4236345f)
- [LinkedIn](https://www.linkedin.com/company/assembledhq)
- [Twitter — @assembledhq](https://twitter.com/assembledhq)

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Assembled People API](openapi/assembled-people-api-openapi.yml)
- [Assembled Agent State API](openapi/assembled-agent-state-api-openapi.yml)
- [Assembled Activities API](openapi/assembled-activities-api-openapi.yml)
- [Assembled Filters API](openapi/assembled-filters-api-openapi.yml)
- [Assembled Forecasts API](openapi/assembled-forecasts-api-openapi.yml)
- [Assembled Time Off API](openapi/assembled-time-off-api-openapi.yml)
- [Assembled Requirements API](openapi/assembled-requirements-api-openapi.yml)
- [Assembled Scheduling Rules API](openapi/assembled-scheduling-rules-api-openapi.yml)
- [Assembled Conversations API](openapi/assembled-conversations-api-openapi.yml)
- [Assembled Reports API](openapi/assembled-reports-api-openapi.yml)
- [Assembled QA API](openapi/assembled-qa-api-openapi.yml)
- [Assembled Assist API](openapi/assembled-assist-api-openapi.yml)

### JSON Schema

- [Person](json-schema/assembled-person-schema.json)
- [Activity](json-schema/assembled-activity-schema.json)
- [Conversation](json-schema/assembled-conversation-schema.json)
- [Assist Response](json-schema/assembled-assist-response-schema.json)

### JSON-LD

- [Assembled Context](json-ld/assembled-context.jsonld)

### Examples

- [List People](examples/assembled-list-people-example.json)
- [Create Activity](examples/assembled-create-activity-example.json)
- [Bulk Agent State](examples/assembled-bulk-agent-state-example.json)
- [Forecasted vs Actuals](examples/assembled-forecasted-vs-actuals-example.json)
- [Assist Response](examples/assembled-assist-response-example.json)

### Spectral

- [Assembled API Conventions Ruleset](rules/assembled-rules.yml)

### Vocabulary

- [Assembled Vocabulary](vocabulary/assembled-vocabulary.yml)

### Capabilities (Naftiko)

- [People — People](capabilities/people-people.yaml)
- [People — Roles](capabilities/people-roles.yaml)
- [Agent State](capabilities/agent-state-state.yaml)
- [Activities](capabilities/activities-activities.yaml)
- [Activity Types](capabilities/activities-activity-types.yaml)
- [Filters — Queues](capabilities/filters-queues.yaml)
- [Filters — Sites](capabilities/filters-sites.yaml)
- [Filters — Teams](capabilities/filters-teams.yaml)
- [Filters — Skills](capabilities/filters-skills.yaml)
- [Forecasts](capabilities/forecasts-forecasts.yaml)
- [Forecast Adjustments](capabilities/forecasts-adjustments.yaml)
- [Forecast Outliers](capabilities/forecasts-outliers.yaml)
- [Time Off](capabilities/time-off-requests.yaml)
- [Requirements](capabilities/requirements-requirements.yaml)
- [Working Hours](capabilities/scheduling-rules-working-hours.yaml)
- [Conversations](capabilities/conversations-conversations.yaml)
- [Reports](capabilities/reports-reports.yaml)
- [QA Scores](capabilities/qa-scores.yaml)
- [Assist Responses](capabilities/assist-responses.yaml)
- [Assist Articles](capabilities/assist-articles.yaml)
- [Assist Conversations](capabilities/assist-conversations.yaml)

### Commercial artifacts

- [Plans / Pricing](plans/assembled-plans-pricing.yml)
- [Rate Limits](rate-limits/assembled-rate-limits.yml)
- [FinOps Definition](finops/assembled-finops.yml)

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com

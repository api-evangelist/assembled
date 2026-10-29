# Assembled

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Assembled is a San Francisco-headquartered support operations platform that unifies workforce management (WFM), AI agents, and AI Copilot for modern customer support teams. Founded in 2020 by former Stripe operations engineers, Assembled lets support leaders plan, schedule, and orchestrate a hybrid workforce of in-house agents, BPO vendors, and AI agents from a single system. The platform delivers ML-based volume forecasting, automated schedule generation, real-time adherence, time-off and shift-swap automation, vendor capacity planning, multichannel routing, and structured reporting across phone, email, chat, SMS, social, and back-office channels. Its AI surface includes autonomous AI Agents that resolve customer conversations end-to-end across chat, email, SMS, and voice, plus AI Copilot, which drafts replies, translates in real time, and surfaces knowledge for human agents. The Assembled REST API (api.assembledhq.com/v0) exposes people, queues, sites, teams, skills, activities, agent states, forecasts, time-off requests, requirements, working hours, QA scores, structured reports, and the Assist endpoints for AI chat responses and knowledge articles. Assembled is used by Stripe, Etsy, Robinhood, Webflow, Canva, Duolingo, Autodesk, HubSpot, Intercom, and Ramp, and integrates with Zendesk, Salesforce Service Cloud, Intercom, Kustomer, Gladly, Gorgias, Dixa, ServiceNow, Five9, Genesys Cloud, Talkdesk, Amazon Connect, NiCE, UJET, Zoom Contact Center, Slack, Okta, Workday, HiBob, Google Calendar, Shopify, Notion, Confluence, Guru, SharePoint, Fivetran, and quality tools like Klaus, Rippit (MaestroQA), evaluagent, and Observe.AI.

**Areas:** Customer Service · Workforce Management · WFM · AI Agents · AI Copilot · Contact Center · Customer Experience · Support Operations · Scheduling · Forecasting · Quality Assurance · Vendor Management

## Assembled on APIs.io

Everything profiled for Assembled is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/assembled/](https://apis.io/providers/assembled/)** — or go straight to one of the APIs or properties below.

### APIs (27)

- [Assembled People API](https://apis.io/apis/assembled/assembled-people-api/) — Manage agents (people) in the Assembled workforce. List, retrieve, create, and update agents along with their roles, channels, skills, and team assignments.…
- [Assembled Agent State API](https://apis.io/apis/assembled/assembled-agent-state-api/) — Read and write real-time agent state used to drive adherence reporting, live dashboards, and dynamic routing. Supports bulk state ingestion from upstream…
- [Assembled Activities API](https://apis.io/apis/assembled/assembled-activities-api/) — Create, list, and delete activities — the scheduled shifts, breaks, time off, training, and meetings that make up an agent's calendar. Includes bulk…
- [Assembled Forecasts API](https://apis.io/apis/assembled/assembled-forecasts-api/) — Retrieve Assembled's ML-generated forecasts, forecast totals, manual adjustments, and detected outliers. The forecasted-vs-actuals endpoint compares…
- [Assembled Time Off API](https://apis.io/apis/assembled/assembled-time-off-api/) — Programmatically create, list, and cancel time-off requests, and pull a stream of time-off updates for downstream HRIS or payroll synchronisation. The…
- [Assembled Requirements API](https://apis.io/apis/assembled/assembled-requirements-api/) — Create and list staffing requirements that express how many agents are needed by queue, site, team, or skill across time intervals. Requirement types…
- [Assembled Conversations API](https://apis.io/apis/assembled/assembled-conversations-api/) — Bulk-ingest and bulk-update customer conversation records — phone, email, chat, SMS, social, and back-office — so they can be associated with agents,…
- [Assembled Reports API](https://apis.io/apis/assembled/assembled-reports-api/) — Asynchronously generate and retrieve structured reports including adherence, ticket statistics, and handle times. Reports are kicked off with a POST…
- [Assembled Activity Types API](https://apis.io/apis/assembled/assembled-activity-types-api/) — Types/categories of activity
- [Assembled Agent Associations API](https://apis.io/apis/assembled/assembled-agent-associations-api/) — Map platform IDs to Assembled people
- [Assembled Assist Articles API](https://apis.io/apis/assembled/assembled-assist-articles-api/) — The Assist Articles API from Assembled — 2 operation(s) for assist articles.
- [Assembled Assist Conversations API](https://apis.io/apis/assembled/assembled-assist-conversations-api/) — The Assist Conversations API from Assembled — 2 operation(s) for assist conversations.
- [Assembled Assist Replies API](https://apis.io/apis/assembled/assembled-assist-replies-api/) — The Assist Replies API from Assembled — 1 operation(s) for assist replies.
- [Assembled Assist Responses API](https://apis.io/apis/assembled/assembled-assist-responses-api/) — The Assist Responses API from Assembled — 2 operation(s) for assist responses.
- [Assembled Event Changes API](https://apis.io/apis/assembled/assembled-event-changes-api/) — Audit trail of schedule modifications
- [Assembled Forecast Adjustments API](https://apis.io/apis/assembled/assembled-forecast-adjustments-api/) — The Forecast Adjustments API from Assembled — 3 operation(s) for forecast adjustments.
- [Assembled Forecast Outliers API](https://apis.io/apis/assembled/assembled-forecast-outliers-api/) — The Forecast Outliers API from Assembled — 3 operation(s) for forecast outliers.
- [Assembled Forecast Totals API](https://apis.io/apis/assembled/assembled-forecast-totals-api/) — The Forecast Totals API from Assembled — 2 operation(s) for forecast totals.
- [Assembled Forecasts Vs Actuals API](https://apis.io/apis/assembled/assembled-forecasts-vs-actuals-api/) — The Forecasts Vs Actuals API from Assembled — 1 operation(s) for forecasts vs actuals.
- [Assembled Quality Assurance API](https://apis.io/apis/assembled/assembled-quality-assurance-api/) — The Quality Assurance API from Assembled — 1 operation(s) for quality assurance.
- [Assembled Queues API](https://apis.io/apis/assembled/assembled-queues-api/) — The Queues API from Assembled — 2 operation(s) for queues.
- [Assembled Requirement Types API](https://apis.io/apis/assembled/assembled-requirement-types-api/) — The Requirement Types API from Assembled — 1 operation(s) for requirement types.
- [Assembled Roles API](https://apis.io/apis/assembled/assembled-roles-api/) — Available roles that can be assigned to people
- [Assembled Sites API](https://apis.io/apis/assembled/assembled-sites-api/) — The Sites API from Assembled — 2 operation(s) for sites.
- [Assembled Skills API](https://apis.io/apis/assembled/assembled-skills-api/) — The Skills API from Assembled — 2 operation(s) for skills.
- [Assembled Teams API](https://apis.io/apis/assembled/assembled-teams-api/) — The Teams API from Assembled — 2 operation(s) for teams.
- [Assembled Working Hours API](https://apis.io/apis/assembled/assembled-working-hours-api/) — The Working Hours API from Assembled — 2 operation(s) for working hours.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Arazzo workflows (15)

Multi-step workflows that chain operations into a business task.

- [Assembled Update an Agent Profile](https://apis.io/arazzos/assembled/assembled-agent-profile-update-workflow/)
- [Assembled Associate Platform IDs to an Agent](https://apis.io/arazzos/assembled/assembled-associate-agent-platforms-workflow/)
- [Assembled Audit Schedule Changes](https://apis.io/arazzos/assembled/assembled-audit-schedule-changes-workflow/)
- [Assembled Review and Cancel a Time Off Request](https://apis.io/arazzos/assembled/assembled-cancel-time-off-workflow/)
- [Assembled Turn a Forecast into a Staffing Requirement](https://apis.io/arazzos/assembled/assembled-forecast-to-requirement-workflow/)
- [Assembled Generate and Retrieve a Report](https://apis.io/arazzos/assembled/assembled-generate-report-workflow/)
- [Assembled Ingest and Enrich Conversations](https://apis.io/arazzos/assembled/assembled-ingest-conversations-workflow/)
- [Assembled Create and Read a Forecast Total](https://apis.io/arazzos/assembled/assembled-manage-forecast-total-workflow/)
- [Assembled Provision a New Agent](https://apis.io/arazzos/assembled/assembled-provision-agent-workflow/)
- [Assembled Provision a Queue and Staff It](https://apis.io/arazzos/assembled/assembled-provision-queue-and-staff-workflow/)
- [Assembled Request Time Off for an Agent](https://apis.io/arazzos/assembled/assembled-request-time-off-workflow/)
- [Assembled Review an Agent's Working Hours](https://apis.io/arazzos/assembled/assembled-review-working-hours-workflow/)
- [Assembled Schedule an Agent Shift](https://apis.io/arazzos/assembled/assembled-schedule-agent-shift-workflow/)
- [Assembled Staff a Shift for a Workforce Agent](https://apis.io/arazzos/assembled/assembled-staff-agent-shift-workflow/)
- [Assembled Stream and Verify Agent State](https://apis.io/arazzos/assembled/assembled-stream-agent-state-workflow/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Assembled Agentic Access](https://apis.io/agentic-access/assembled/assembled-agentic-access/)

#### JSON Schema (4)

The data models the API reads and writes.

- [AssembledActivity](https://apis.io/schemas/assembled/assembled-activity/)
- [AssembledAssistResponse](https://apis.io/schemas/assembled/assembled-assist-response/)
- [AssembledConversation](https://apis.io/schemas/assembled/assembled-conversation/)
- [AssembledPerson](https://apis.io/schemas/assembled/assembled-person/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Assembled Context](https://apis.io/jsonld/assembled/assembled-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Assembled Vocabulary](https://apis.io/vocabularies/assembled/assembled-vocabulary/)

#### Examples (5)

Example requests and responses.

- [Assembled Assist Response Example](https://apis.io/examples/assembled/assembled-assist-response-example/)
- [Assembled Bulk Agent State Example](https://apis.io/examples/assembled/assembled-bulk-agent-state-example/)
- [Assembled Create Activity Example](https://apis.io/examples/assembled/assembled-create-activity-example/)
- [Assembled Forecasted Vs Actuals Example](https://apis.io/examples/assembled/assembled-forecasted-vs-actuals-example/)
- [Assembled List People Example](https://apis.io/examples/assembled/assembled-list-people-example/)

#### Collections (43)

Postman and Open Collection request collections.

- [Assembled Activities API](https://apis.io/collections/assembled/open-assembled-activities-api/)
- [Assembled Activities Activity Types API](https://apis.io/collections/assembled/open-assembled-activity-types-api/)
- [Assembled Activities Agent Associations API](https://apis.io/collections/assembled/open-assembled-agent-associations-api/)
- [Assembled Activities Agent State API](https://apis.io/collections/assembled/open-assembled-agent-state-api/)
- [Assembled Assist API](https://apis.io/collections/assembled/open-assembled-assist-api/)
- [Assembled Activities Assist Articles API](https://apis.io/collections/assembled/open-assembled-assist-articles-api/)
- [Assembled Activities Assist Conversations API](https://apis.io/collections/assembled/open-assembled-assist-conversations-api/)
- [Assembled Activities Assist Replies API](https://apis.io/collections/assembled/open-assembled-assist-replies-api/)
- [Assembled Activities Assist Responses API](https://apis.io/collections/assembled/open-assembled-assist-responses-api/)
- [Assembled Activities Conversations API](https://apis.io/collections/assembled/open-assembled-conversations-api/)
- [Assembled Activities Event Changes API](https://apis.io/collections/assembled/open-assembled-event-changes-api/)
- [Assembled Filters API](https://apis.io/collections/assembled/open-assembled-filters-api/)
- [Assembled Activities Forecast Adjustments API](https://apis.io/collections/assembled/open-assembled-forecast-adjustments-api/)
- [Assembled Activities Forecast Outliers API](https://apis.io/collections/assembled/open-assembled-forecast-outliers-api/)
- [Assembled Activities Forecast Totals API](https://apis.io/collections/assembled/open-assembled-forecast-totals-api/)
- [Assembled Activities Forecasts API](https://apis.io/collections/assembled/open-assembled-forecasts-api/)
- [Assembled Activities Forecasts Vs Actuals API](https://apis.io/collections/assembled/open-assembled-forecasts-vs-actuals-api/)
- [Assembled Activities People API](https://apis.io/collections/assembled/open-assembled-people-api/)
- [Assembled QA API](https://apis.io/collections/assembled/open-assembled-qa-api/)
- [Assembled Activities Quality Assurance API](https://apis.io/collections/assembled/open-assembled-quality-assurance-api/)
- [Assembled Activities Queues API](https://apis.io/collections/assembled/open-assembled-queues-api/)
- [Assembled Activities Reports API](https://apis.io/collections/assembled/open-assembled-reports-api/)
- [Assembled Activities Requirement Types API](https://apis.io/collections/assembled/open-assembled-requirement-types-api/)
- [Assembled Activities Requirements API](https://apis.io/collections/assembled/open-assembled-requirements-api/)
- [Assembled Activities Roles API](https://apis.io/collections/assembled/open-assembled-roles-api/)
- …and 18 more published on APIs.io

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Assembled — jsonschema rules](https://apis.io/rules/assembled/assembled-jsonschema-spectral-rules/)
- [Assembled API Rules](https://apis.io/rules/assembled/assembled-rules/)

#### Security (4)

Authentication, trust centre, and vulnerability disclosure.

- [Assembled Authentication](https://apis.io/security/assembled/assembled-authentication/)
- [Assembled Domain Security](https://apis.io/security/assembled/assembled-domain-security/)
- [Assembled Trust Center](https://apis.io/security/assembled/assembled-trust-center/)
- [Assembled Vulnerability Disclosure](https://apis.io/security/assembled/assembled-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Assembled Plans Pricing](https://apis.io/plans/assembled/assembled-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Assembled Rate Limits](https://apis.io/rate-limits/assembled/assembled-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Assembled Finops](https://apis.io/finops/assembled/assembled-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.assembled.com)
- [Documentation](https://docs.assembled.com/)
- [Getting started](https://docs.assembled.com/)
- [Pricing](https://www.assembled.com/pricing)
- [Support](https://support.assembled.com)
- [Blog](https://www.assembled.com/blog)
- [Trust centre](https://trust.assembled.com)
- [Terms of service](https://www.assembled.com/terms)
- [Privacy policy](https://www.assembled.com/privacy)
- [GitHub](https://github.com/assembledhq)
- [Status](https://status.assembled.com)

## API Evangelist rating

**Kin Score 51.7** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 62.5 |
| Contract quality | 56.3 |
| Contract governance | 27.3 |
| Operational transparency | 34.2 |
| Developer ergonomics | 58.3 |
| Access clarity | 32.9 |

**Agent readiness 23.0** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | partial |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | distinct |

**Regulatory alignment 22.5** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/assembled/](https://apis.io/providers/assembled/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Assembled: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/assembled/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).

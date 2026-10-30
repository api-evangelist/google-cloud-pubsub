# Google Cloud Pub/Sub

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

Google Cloud Pub/Sub is a fully managed, real-time messaging service that allows you to send and receive messages between independent applications. It provides reliable, many-to-many, asynchronous messaging that decouples senders and receivers.

**Areas:** Event-Driven · Google Cloud · Messaging · Pub/Sub

## Google Cloud Pub/Sub on APIs.io

Everything profiled for Google Cloud Pub/Sub is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/google-cloud-pubsub/](https://apis.io/providers/google-cloud-pubsub/)** — or go straight to one of the APIs or properties below.

### APIs (3)

- [Google Cloud Pub/Sub Schemas API](https://apis.io/apis/google-cloud-pubsub/google-cloud-pubsub-schemas-api/) — Operations for managing Pub/Sub schemas
- [Google Cloud Pub/Sub Subscriptions API](https://apis.io/apis/google-cloud-pubsub/google-cloud-pubsub-subscriptions-api/) — Operations for managing Pub/Sub subscriptions
- [Google Cloud Pub/Sub Topics API](https://apis.io/apis/google-cloud-pubsub/google-cloud-pubsub-topics-api/) — Operations for managing Pub/Sub topics

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Google Cloud Pub/Sub Messaging Surface](https://apis.io/asyncapis/google-cloud-pubsub/google-cloud-pubsub-asyncapi/)

#### Event channels (6)

Individual events and webhooks the provider emits.

- [projects/{projectId}/schemas/{schemaId}](https://apis.io/channels/google-cloud-pubsub/projects-projectid-schemas-schemaid/)
- [projects/{projectId}/subscriptions/{subscriptionId}:bigquery](https://apis.io/channels/google-cloud-pubsub/projects-projectid-subscriptions-subscriptionid-bigquery/)
- [projects/{projectId}/subscriptions/{subscriptionId}:cloudstorage](https://apis.io/channels/google-cloud-pubsub/projects-projectid-subscriptions-subscriptionid-cloudstorage/)
- [projects/{projectId}/subscriptions/{subscriptionId}:pull](https://apis.io/channels/google-cloud-pubsub/projects-projectid-subscriptions-subscriptionid-pull/)
- [projects/{projectId}/topics/{topicId}](https://apis.io/channels/google-cloud-pubsub/projects-projectid-topics-topicid/)
- [{pushEndpoint}](https://apis.io/channels/google-cloud-pubsub/pushendpoint/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Google Cloud Pubsub Agentic Access](https://apis.io/agentic-access/google-cloud-pubsub/google-cloud-pubsub-agentic-access/)

#### JSON Schema (1)

The data models the API reads and writes.

- [Google Cloud Pub/Sub Topic](https://apis.io/schemas/google-cloud-pubsub/google-cloud-pubsub-topic/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Google Cloud Pubsub Context](https://apis.io/jsonld/google-cloud-pubsub/google-cloud-pubsub-context/)

#### Collections (4)

Postman and Open Collection request collections.

- [Google Cloud Pub/Sub API](https://apis.io/collections/google-cloud-pubsub/open-google-cloud-pubsub/)
- [Google Cloud Pub/Sub Schemas API](https://apis.io/collections/google-cloud-pubsub/open-google-cloud-pubsub-schemas-api/)
- [Google Cloud Pub/Sub Schemas Subscriptions API](https://apis.io/collections/google-cloud-pubsub/open-google-cloud-pubsub-subscriptions-api/)
- [Google Cloud Pub/Sub Schemas Topics API](https://apis.io/collections/google-cloud-pubsub/open-google-cloud-pubsub-topics-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Google Cloud Pub/Sub — asyncapi rules](https://apis.io/rules/google-cloud-pubsub/google-cloud-pubsub-asyncapi-spectral-rules/)
- [Google Cloud Pub/Sub — jsonschema rules](https://apis.io/rules/google-cloud-pubsub/google-cloud-pubsub-jsonschema-spectral-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Google Cloud Pubsub Authentication](https://apis.io/security/google-cloud-pubsub/google-cloud-pubsub-authentication/)
- [Google Cloud Pubsub Domain Security](https://apis.io/security/google-cloud-pubsub/google-cloud-pubsub-domain-security/)
- [Google Cloud Pubsub Vulnerability Disclosure](https://apis.io/security/google-cloud-pubsub/google-cloud-pubsub-vulnerability-disclosure/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Google Cloud Pubsub Scopes](https://apis.io/scopes/google-cloud-pubsub/google-cloud-pubsub-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Google Cloud Pubsub Plans Pricing](https://apis.io/plans/google-cloud-pubsub/google-cloud-pubsub-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Google Cloud Pubsub Rate Limits](https://apis.io/rate-limits/google-cloud-pubsub/google-cloud-pubsub-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Google Cloud Pubsub Finops](https://apis.io/finops/google-cloud-pubsub/google-cloud-pubsub-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.google.com/)
- [Getting started](https://cloud.google.com/pubsub/docs/quickstarts)
- [Pricing](https://cloud.google.com/pubsub/pricing)
- [GitHub](https://github.com/GoogleCloudPlatform)

## API Evangelist rating

**Kin Score 37.3** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 57.1 |
| Contract quality | 65.4 |
| Contract governance | 13.6 |
| Operational transparency | 10.5 |
| Developer ergonomics | 33.3 |
| Access clarity | 18.4 |

**Agent readiness 24.0** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | negotiable (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | derived (partial credit) |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | documented (partial credit) |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 32.4** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/google-cloud-pubsub/](https://apis.io/providers/google-cloud-pubsub/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Google Cloud Pub/Sub: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/google-cloud-pubsub/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).

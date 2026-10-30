# Flyte

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

Flyte is a Kubernetes-native, open-source workflow orchestration platform for machine learning, data, and analytics pipelines. It provides reproducibility, type safety, strong versioning of tasks and workflows, and a multi-tenant control plane with native first-class scheduling on Kubernetes. Flyte is a Cloud Native Computing Foundation (CNCF) incubating project. Beyond the Python and Go SDKs, Flyte exposes a JSON-over-HTTP REST control-plane API (the Flyte Admin API) generated from the flyteidl protocol buffer definitions via gRPC-Gateway, which is used to register and manage projects, tasks, workflows, and launch plans, to create and inspect executions, to receive lifecycle events, and to read and write matchable attribute overrides.

**Areas:** CNCF · Data Orchestration · Kubernetes · Machine Learning · Workflow Automation

## Flyte on APIs.io

Everything profiled for Flyte is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/flyte/](https://apis.io/providers/flyte/)** — or go straight to one of the APIs or properties below.

### APIs (12)

- [Flyte DataProxy API](https://apis.io/apis/flyte/flyte-dataproxy-api/) — Signed URL retrieval for execution data inputs and outputs.
- [Flyte Events API](https://apis.io/apis/flyte/flyte-events-api/) — Workflow, node, and task execution events.
- [Flyte Executions API](https://apis.io/apis/flyte/flyte-executions-api/) — Workflow execution creation, listing, retrieval, and termination.
- [Flyte MatchableAttributes API](https://apis.io/apis/flyte/flyte-matchableattributes-api/) — Matchable attribute configuration at project, domain, and workflow levels.
- [Flyte NamedEntities API](https://apis.io/apis/flyte/flyte-namedentities-api/) — Named entity metadata for tasks, workflows, and launch plans.
- [Flyte Projects API](https://apis.io/apis/flyte/flyte-projects-api/) — Project registration and listing.
- [Flyte Tasks API](https://apis.io/apis/flyte/flyte-tasks-api/) — Task entity registration, listing, and retrieval.
- [Flyte Version API](https://apis.io/apis/flyte/flyte-version-api/) — Admin server version information.
- [Flyte Workflows API](https://apis.io/apis/flyte/flyte-workflows-api/) — Workflow entity registration, listing, and retrieval.
- [Flyte Launch Plans API](https://apis.io/apis/flyte/flyte-launch-plans-api/) — Launch plan registration, listing, retrieval, and activation.
- [Flyte Node Executions API](https://apis.io/apis/flyte/flyte-node-executions-api/) — Node execution listing and retrieval.
- [Flyte Task Executions API](https://apis.io/apis/flyte/flyte-task-executions-api/) — Task execution listing and retrieval.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Flyte Agentic Access](https://apis.io/agentic-access/flyte/flyte-agentic-access/)

#### Collections (13)

Postman and Open Collection request collections.

- [Flyte Admin API](https://apis.io/collections/flyte/open-flyte-admin-api/)
- [Flyte Admin DataProxy API](https://apis.io/collections/flyte/open-flyte-dataproxy-api/)
- [Flyte Admin DataProxy Events API](https://apis.io/collections/flyte/open-flyte-events-api/)
- [Flyte Admin DataProxy Executions API](https://apis.io/collections/flyte/open-flyte-executions-api/)
- [Flyte Admin DataProxy LaunchPlans API](https://apis.io/collections/flyte/open-flyte-launchplans-api/)
- [Flyte Admin DataProxy MatchableAttributes API](https://apis.io/collections/flyte/open-flyte-matchableattributes-api/)
- [Flyte Admin DataProxy NamedEntities API](https://apis.io/collections/flyte/open-flyte-namedentities-api/)
- [Flyte Admin DataProxy NodeExecutions API](https://apis.io/collections/flyte/open-flyte-nodeexecutions-api/)
- [Flyte Admin DataProxy Projects API](https://apis.io/collections/flyte/open-flyte-projects-api/)
- [Flyte Admin DataProxy TaskExecutions API](https://apis.io/collections/flyte/open-flyte-taskexecutions-api/)
- [Flyte Admin DataProxy Tasks API](https://apis.io/collections/flyte/open-flyte-tasks-api/)
- [Flyte Admin DataProxy Version API](https://apis.io/collections/flyte/open-flyte-version-api/)
- [Flyte Admin DataProxy Workflows API](https://apis.io/collections/flyte/open-flyte-workflows-api/)

#### Security (1)

Authentication, trust centre, and vulnerability disclosure.

- [Flyte Domain Security](https://apis.io/security/flyte/flyte-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Flyte Plans Pricing](https://apis.io/plans/flyte/flyte-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Flyte Rate Limits](https://apis.io/rate-limits/flyte/flyte-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Flyte Finops](https://apis.io/finops/flyte/flyte-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://flyte.org)
- [Documentation](https://docs.flyte.org)
- [Blog](https://flyte.org/blog)
- [GitHub](https://github.com/flyteorg)

## API Evangelist rating

**Kin Score 22.8** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 57.1 |
| Contract quality | 36.1 |
| Contract governance | 0.0 |
| Operational transparency | 26.3 |
| Developer ergonomics | 11.9 |
| Access clarity | 7.9 |

**Agent readiness 15.4** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | — |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
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

**Regulatory alignment 5.5** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/flyte/](https://apis.io/providers/flyte/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Flyte: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/flyte/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).

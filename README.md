# Flyte (flyte)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Flyte is a Kubernetes-native, open-source workflow orchestration platform for machine learning, data, and analytics pipelines. It provides reproducibility, type safety, strong versioning of tasks and workflows, and a multi-tenant control plane with native first-class scheduling on Kubernetes. Flyte is a Cloud Native Computing Foundation (CNCF) incubating project. Beyond the Python and Go SDKs, Flyte exposes a JSON-over-HTTP REST control-plane API (the Flyte Admin API) generated from the flyteidl protocol buffer definitions via gRPC-Gateway, which is used to register and manage projects, tasks, workflows, and launch plans, to create and inspect executions, to receive lifecycle events, and to read and write matchable attribute overrides.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/flyte/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/flyte/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- CNCF
- Data Orchestration
- Kubernetes
- Machine Learning
- Workflow Automation

## Timestamps

- **Created:** 2026-03-27
- **Modified:** 2026-05-19

## APIs

### Flyte Admin API

The Flyte Admin API is the control-plane REST API exposed by the flyteadmin service. It is generated from the flyteidl protocol buffer definitions via gRPC-Gateway and provides JSON over HTTP access to the same operations exposed via gRPC. The API is used to register and manage projects, tasks, workflows, and launch plans, to create and inspect workflow, node, and task executions, to receive lifecycle events, to proxy data to and from upstream object stores, and to read and write matchable attribute overrides at the project, domain, and workflow levels. The same REST API powers the Flyte Console UI and is the primary programmatic interface for operating a Flyte cluster.

- **Human URL:** [https://docs.flyte.org](https://docs.flyte.org)
- **Base URL:** `http://localhost:30080`

#### Tags

- Workflow Orchestration
- Control Plane
- Executions
- Launch Plans
- Projects
- Tasks
- Workflows

#### Properties

- [Documentation](https://docs.flyte.org)
- [OpenAPI](openapi/flyte-admin-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/flyte-admin-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/flyte-admin-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [GitHub Repository](https://github.com/flyteorg/flyte)
- [Source Swagger](https://raw.githubusercontent.com/flyteorg/flyteidl/master/gen/pb-go/flyteidl/service/admin.swagger.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/showcase/flyte-oss)
- [Website](https://flyte.org)
- [Documentation](https://docs.flyte.org)
- [GitHub Repository](https://github.com/flyteorg/flyte)
- [GitHub Organization](https://github.com/flyteorg)
- [Blog](https://flyte.org/blog)
- [Community](https://flyte.org/community)
- [Slack](https://slack.flyte.org)
- [Integrations](https://flyte.org/integrations)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com

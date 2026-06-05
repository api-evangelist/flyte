# Flyte (flyte)

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

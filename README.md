# Flyte (flyte)

Flyte is a Kubernetes-native, open-source workflow orchestration platform for machine learning, data, and analytics pipelines. It provides reproducibility, type safety, strong versioning of tasks and workflows, and a multi-tenant control plane with native first-class scheduling on Kubernetes. Flyte is a Cloud Native Computing Foundation (CNCF) incubating project.

Beyond its Python and Go SDKs, Flyte exposes a JSON-over-HTTP REST control-plane API — the Flyte Admin API — generated from the flyteidl protocol buffer definitions via gRPC-Gateway. The same REST API powers the Flyte Console UI and is the primary programmatic interface for registering and managing projects, tasks, workflows, and launch plans, for creating and inspecting workflow, node, and task executions, for receiving lifecycle events, and for reading and writing matchable attribute overrides.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/flyte/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- CNCF
- Data Orchestration
- Kubernetes
- Machine Learning
- Workflow Automation

## APIs

### Flyte Admin API

The Flyte Admin API is exposed by the flyteadmin service and provides REST access to the Flyte control plane. The API surface mirrors the gRPC services defined in flyteidl and covers project, task, workflow, and launch plan registration; execution lifecycle; named entity metadata; matchable attribute configuration; lifecycle events; and signed-URL data proxying.

Endpoint categories include:

- **Projects** — `/api/v1/projects`, `/api/v1/projects/{id}`
- **Tasks** — `/api/v1/tasks`, `/api/v1/tasks/{id.project}/{id.domain}`, `/api/v1/tasks/{id.project}/{id.domain}/{id.name}`, `/api/v1/tasks/{id.project}/{id.domain}/{id.name}/{id.version}`, `/api/v1/task_ids/{project}/{domain}`
- **Workflows** — `/api/v1/workflows`, `/api/v1/workflows/{id.project}/{id.domain}`, `/api/v1/workflows/{id.project}/{id.domain}/{id.name}`, `/api/v1/workflows/{id.project}/{id.domain}/{id.name}/{id.version}`, `/api/v1/workflow_ids/{project}/{domain}`
- **Launch Plans** — `/api/v1/launch_plans`, `/api/v1/launch_plans/{id.project}/{id.domain}/{id.name}/{id.version}`, `/api/v1/active_launch_plans/{project}/{domain}`, `/api/v1/launch_plan_ids/{project}/{domain}`
- **Executions** — `/api/v1/executions`, `/api/v1/executions/{id.project}/{id.domain}/{id.name}`, `/api/v1/executions/relaunch`, `/api/v1/executions/recover`, `/api/v1/metrics/executions/{id.project}/{id.domain}/{id.name}`
- **Node Executions** — `/api/v1/node_executions/{workflow_execution_id.project}/{workflow_execution_id.domain}/{workflow_execution_id.name}`
- **Task Executions** — `/api/v1/task_executions/{node_execution_id.execution_id.project}/{node_execution_id.execution_id.domain}/{node_execution_id.execution_id.name}/{node_execution_id.node_id}`
- **Events** — `/api/v1/events/workflows`, `/api/v1/events/nodes`, `/api/v1/events/tasks`
- **Data Proxy** — `/api/v1/data/executions/{id.project}/{id.domain}/{id.name}`
- **Named Entities** — `/api/v1/named_entities/{resource_type}/{project}/{domain}`, `/api/v1/named_entities/{resource_type}/{id.project}/{id.domain}/{id.name}`
- **Matchable Attributes** — `/api/v1/matchable_attributes`, `/api/v1/project_attributes/{project}`, `/api/v1/project_domain_attributes/{project}/{domain}`, `/api/v1/workflow_attributes/{project}/{domain}/{workflow}`
- **Version** — `/api/v1/version`

**Documentation:** [https://docs.flyte.org](https://docs.flyte.org)

**OpenAPI:** [openapi/flyte-admin-api-openapi.yml](openapi/flyte-admin-api-openapi.yml)

**Source Swagger:** [admin.swagger.json](https://raw.githubusercontent.com/flyteorg/flyteidl/master/gen/pb-go/flyteidl/service/admin.swagger.json)

## Common Properties

- [Website](https://flyte.org)
- [Documentation](https://docs.flyte.org)
- [GitHub Repository](https://github.com/flyteorg/flyte)
- [GitHub Organization](https://github.com/flyteorg)
- [Blog](https://flyte.org/blog)
- [Community](https://flyte.org/community)
- [Slack](https://slack.flyte.org)

## Timestamps

- **Created:** 2026-03-27
- **Modified:** 2026-04-28

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com

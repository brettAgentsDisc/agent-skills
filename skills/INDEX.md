# Skills Index
Generated from repository contents under `skills/`.

## cloud/access-management
Description: Manage Elastic Cloud organization access: invite users, assign roles to Serverless projects, and create or revoke Cloud API keys. Use when granting, modifying, or auditing user access.
Files:
- skills/cloud/access-management/SKILL.md
- skills/cloud/access-management/references/api-reference.md

## cloud/create-project
Description: Creates Elastic Cloud Serverless projects (Elasticsearch, Observability, or Security) via the REST API, saves credentials to file, and bootstraps a scoped Elasticsearch API key. Use when creating a new serverless project, provisioning a search or observability environment, or spinning up a new Elastic Cloud project.
Files:
- skills/cloud/create-project/SKILL.md
- skills/cloud/create-project/references/api-reference.md

## cloud/manage-project
Description: Manages existing Elastic Cloud Serverless projects: list, get, update, delete, reset credentials, resume, and load saved credentials. Connects to existing projects by resolving endpoints and acquiring scoped Elasticsearch API keys. Use when performing day-2 operations on serverless projects, connecting to an existing project, loading or resetting project credentials, or looking up project details.
Files:
- skills/cloud/manage-project/SKILL.md
- skills/cloud/manage-project/references/credential-file-format.md

## cloud/network-security
Description: Manage Serverless network security (traffic filters): create, update, and delete IP filters and AWS PrivateLink VPC filters. Use when restricting network access or configuring private connectivity.
Files:
- skills/cloud/network-security/SKILL.md
- skills/cloud/network-security/references/api-reference.md

## cloud/setup
Description: Configures Elastic Cloud authentication and environment defaults. Use when setting up EC_API_KEY, configuring Cloud API access, or when another cloud skill requires credentials.
Files:
- skills/cloud/setup/SKILL.md

## elasticsearch/elasticsearch-audit
Description: Enable, configure, and query Elasticsearch security audit logs. Use when the task involves audit logging setup, event filtering, or investigating security incidents like failed logins.
Files:
- skills/elasticsearch/elasticsearch-audit/SKILL.md
- skills/elasticsearch/elasticsearch-audit/references/api-reference.md

## elasticsearch/elasticsearch-authn
Description: Authenticate to Elasticsearch using native, file-based, LDAP/AD, SAML, OIDC, Kerberos, JWT, or certificate realms. Use when connecting with credentials, choosing a realm, or managing API keys. Assumes the target realms are already configured.
Files:
- skills/elasticsearch/elasticsearch-authn/SKILL.md
- skills/elasticsearch/elasticsearch-authn/references/api-reference.md

## elasticsearch/elasticsearch-authz
Description: Manage Elasticsearch RBAC: native users, roles, role mappings, document- and field-level security. Use when creating users or roles, assigning privileges, or mapping external realms like LDAP/SAML.
Files:
- skills/elasticsearch/elasticsearch-authz/SKILL.md
- skills/elasticsearch/elasticsearch-authz/references/api-reference.md
- skills/elasticsearch/elasticsearch-authz/references/deployment-compatibility.md

## elasticsearch/elasticsearch-esql
Description: Execute ES|QL (Elasticsearch Query Language) queries, use when the user wants to query Elasticsearch data, analyze logs, aggregate metrics, explore data, or create charts and dashboards from ES|QL results.
Files:
- skills/elasticsearch/elasticsearch-esql/SKILL.md
- skills/elasticsearch/elasticsearch-esql/references/dsl-to-esql-migration.md
- skills/elasticsearch/elasticsearch-esql/references/environment-setup.md
- skills/elasticsearch/elasticsearch-esql/references/esql-reference.md
- skills/elasticsearch/elasticsearch-esql/references/esql-search-strategy.md
- skills/elasticsearch/elasticsearch-esql/references/esql-search.md
- skills/elasticsearch/elasticsearch-esql/references/esql-version-history.md
- skills/elasticsearch/elasticsearch-esql/references/generation-tips.md
- skills/elasticsearch/elasticsearch-esql/references/query-patterns.md
- skills/elasticsearch/elasticsearch-esql/references/time-series-queries.md

## elasticsearch/elasticsearch-file-ingest
Description: Ingest and transform data files (CSV/JSON/Parquet/Arrow IPC) into Elasticsearch with stream processing and custom transforms. Use when loading files or batch importing data — not for reindexing, general ingest pipeline design, or bulk API patterns.
Files:
- skills/elasticsearch/elasticsearch-file-ingest/SKILL.md
- skills/elasticsearch/elasticsearch-file-ingest/references/patterns.md
- skills/elasticsearch/elasticsearch-file-ingest/references/troubleshooting.md

## elasticsearch/elasticsearch-onboarding
Description: Help developers new to Elasticsearch get from zero to a working search experience. Guide them through understanding their intent, mapping their data, and building a search experience with best practices baked in. Use this when developers are new to Elasticsearch and need help getting started with their search use case.
Files:
- skills/elasticsearch/elasticsearch-onboarding/SKILL.md
- skills/elasticsearch/elasticsearch-onboarding/references/catalog-ecommerce/ecommerce.md
- skills/elasticsearch/elasticsearch-onboarding/references/elasticsearch-onboarding-playbook.md
- skills/elasticsearch/elasticsearch-onboarding/references/hybrid-search/hybrid-search.md
- skills/elasticsearch/elasticsearch-onboarding/references/keyword-search/keyword-search.md
- skills/elasticsearch/elasticsearch-onboarding/references/rag-chatbot/rag-chatbot.md
- skills/elasticsearch/elasticsearch-onboarding/references/semantic-search/semantic-search.md
- skills/elasticsearch/elasticsearch-onboarding/references/vector-database/vector-database.md

## elasticsearch/elasticsearch-security-troubleshooting
Description: Diagnose and resolve Elasticsearch security errors: 401/403 failures, TLS problems, expired API keys, role mapping mismatches, and Kibana login issues. Use when the user reports a security error.
Files:
- skills/elasticsearch/elasticsearch-security-troubleshooting/SKILL.md
- skills/elasticsearch/elasticsearch-security-troubleshooting/references/api-reference.md

## kibana/agent-builder
Description: Create and manage Agent Builder agents and custom tools in Kibana. Use when asked to create, update, delete, test, or inspect agents or tools in Agent Builder.
Files:
- skills/kibana/agent-builder/SKILL.md
- skills/kibana/agent-builder/references/architecture-guide.md
- skills/kibana/agent-builder/references/use-cases.md

## kibana/kibana-alerting-rules
Description: Create and manage Kibana alerting rules via REST API or Terraform. Use when creating, updating, or managing rule lifecycle (enable, disable, mute, snooze) or rules-as-code workflows.
Files:
- skills/kibana/kibana-alerting-rules/SKILL.md

## kibana/kibana-audit
Description: Enable and configure Kibana audit logging for saved object access, logins, and space operations. Use when setting up Kibana audit, filtering events, or correlating Kibana and ES audit logs.
Files:
- skills/kibana/kibana-audit/SKILL.md
- skills/kibana/kibana-audit/references/api-reference.md

## kibana/kibana-connectors
Description: Create and manage Kibana connectors for Slack, PagerDuty, Jira, webhooks, and more via REST API or Terraform. Use when configuring third-party integrations or managing connectors as code.
Files:
- skills/kibana/kibana-connectors/SKILL.md
- skills/kibana/kibana-connectors/references/action-design.md
- skills/kibana/kibana-connectors/references/workflows.md

## kibana/kibana-dashboards
Description: Create and manage Kibana Dashboards and Lens visualizations. Use when you need to define dashboards and visualizations declaratively, version control them, or automate their deployment.
Files:
- skills/kibana/kibana-dashboards/SKILL.md
- skills/kibana/kibana-dashboards/references/chart-types-reference.md
- skills/kibana/kibana-dashboards/references/dashboard-api-reference.md
- skills/kibana/kibana-dashboards/references/lens-api-reference.md

## kibana/kibana-vega
Description: Create Vega and Vega-Lite visualizations with ES|QL data sources in Kibana. Use when building custom charts, dashboards, or programmatic panel layouts beyond standard Lens charts.
Files:
- skills/kibana/kibana-vega/SKILL.md
- skills/kibana/kibana-vega/references/dashboard-layout-reference.md
- skills/kibana/kibana-vega/references/vega-esql-reference.md
- skills/kibana/kibana-vega/references/vega-lite-reference.md

## kibana/streams
Description: List, inspect, enable, disable, and resync Kibana Streams via the REST API. Use when the user needs stream details, ingest/query settings, queries, significant events, or attachments.
Files:
- skills/kibana/streams/SKILL.md
- skills/kibana/streams/references/streams-api-reference.md

## observability/edot-dotnet-instrument
Description: Instrument a .NET application with the Elastic Distribution of OpenTelemetry (EDOT) .NET SDK for automatic tracing, metrics, and logs. Use when adding observability to a .NET service that has no existing APM agent.
Files:
- skills/observability/edot-dotnet-instrument/SKILL.md

## observability/edot-dotnet-migrate
Description: Migrate a .NET application from the classic Elastic APM .NET agent to the EDOT .NET SDK. Use when switching from Elastic.Apm.* packages to Elastic.OpenTelemetry.
Files:
- skills/observability/edot-dotnet-migrate/SKILL.md

## observability/edot-java-instrument
Description: Instrument a Java application with the Elastic Distribution of OpenTelemetry (EDOT) Java agent for automatic tracing, metrics, and logs. Use when adding observability to a Java service that has no existing APM agent.
Files:
- skills/observability/edot-java-instrument/SKILL.md

## observability/edot-java-migrate
Description: Migrate a Java application from the classic Elastic APM Java agent to the EDOT Java agent. Use when switching from elastic-apm-agent.jar to elastic-otel-javaagent.jar.
Files:
- skills/observability/edot-java-migrate/SKILL.md

## observability/edot-python-instrument
Description: Instrument a Python application with the Elastic Distribution of OpenTelemetry (EDOT) Python agent for automatic tracing, metrics, and logs. Use when adding observability to a Python service that has no existing APM agent.
Files:
- skills/observability/edot-python-instrument/SKILL.md

## observability/edot-python-migrate
Description: Migrate a Python application from the classic Elastic APM Python agent to the EDOT Python agent. Use when switching from elastic-apm to elastic-opentelemetry.
Files:
- skills/observability/edot-python-migrate/SKILL.md

## observability/llm-obs
Description: Monitor LLMs and agentic apps: performance, token/cost, response quality, and workflow orchestration. Use when the user asks about LLM monitoring, GenAI observability, or AI cost/quality.
Files:
- skills/observability/llm-obs/SKILL.md

## observability/logs-search
Description: Search and filter Observability logs using ES|QL. Use when investigating log spikes, errors, or anomalies; getting volume and trends; or drilling into services or containers during incidents.
Files:
- skills/observability/logs-search/SKILL.md
- skills/observability/logs-search/references/log-search-reference.md

## observability/manage-slos
Description: Create and manage SLOs in Elastic Observability using the Kibana API. Use when defining SLIs, setting error budgets, or managing SLO lifecycle.
Files:
- skills/observability/manage-slos/SKILL.md

## observability/service-health
Description: Assess APM service health using SLOs, alerts, ML, throughput, latency, error rate, and dependencies. Use when checking service status, performance, or when the user asks about service health.
Files:
- skills/observability/service-health/SKILL.md
- skills/observability/service-health/references/api-reference.md

## security/alert-triage
Description: Triage Elastic Security alerts — gather context, classify threats, create cases, and acknowledge. Use when triaging alerts, performing SOC analysis, or investigating detections.
Files:
- skills/security/alert-triage/SKILL.md
- skills/security/alert-triage/references/classification-guide.md

## security/case-management
Description: Create, search, update, and manage SOC cases via the Kibana Cases API. Use when tracking incidents, linking alerts to cases, adding investigation notes, or managing triage output.
Files:
- skills/security/case-management/SKILL.md
- skills/security/case-management/references/kibana-cases-api.md

## security/detection-rule-management
Description: Create, tune, and manage Elastic Security detection rules (SIEM and Endpoint). Use for false positives, exceptions, new coverage, noisy rules, or rule management via Kibana API.
Files:
- skills/security/detection-rule-management/SKILL.md
- skills/security/detection-rule-management/references/detection-api-reference.md
- skills/security/detection-rule-management/references/endpoint-behavior-tuning-workflow.md
- skills/security/detection-rule-management/references/endpoint-exceptions-guide.md
- skills/security/detection-rule-management/references/endpoint-rule-exclusion-best-practices.md

## security/generate-security-sample-data
Description: Generate sample security events, attack scenarios, and synthetic alerts for Elastic Security. Use when demoing, populating dashboards, testing detection rules, or setting up a POC.
Files:
- skills/security/generate-security-sample-data/SKILL.md
- skills/security/generate-security-sample-data/references/sample-data-reference.md

## Flat File List
- skills/cloud/access-management/SKILL.md
- skills/cloud/access-management/references/api-reference.md
- skills/cloud/create-project/SKILL.md
- skills/cloud/create-project/references/api-reference.md
- skills/cloud/manage-project/SKILL.md
- skills/cloud/manage-project/references/credential-file-format.md
- skills/cloud/network-security/SKILL.md
- skills/cloud/network-security/references/api-reference.md
- skills/cloud/setup/SKILL.md
- skills/elasticsearch/elasticsearch-audit/SKILL.md
- skills/elasticsearch/elasticsearch-audit/references/api-reference.md
- skills/elasticsearch/elasticsearch-authn/SKILL.md
- skills/elasticsearch/elasticsearch-authn/references/api-reference.md
- skills/elasticsearch/elasticsearch-authz/SKILL.md
- skills/elasticsearch/elasticsearch-authz/references/api-reference.md
- skills/elasticsearch/elasticsearch-authz/references/deployment-compatibility.md
- skills/elasticsearch/elasticsearch-esql/SKILL.md
- skills/elasticsearch/elasticsearch-esql/references/dsl-to-esql-migration.md
- skills/elasticsearch/elasticsearch-esql/references/environment-setup.md
- skills/elasticsearch/elasticsearch-esql/references/esql-reference.md
- skills/elasticsearch/elasticsearch-esql/references/esql-search-strategy.md
- skills/elasticsearch/elasticsearch-esql/references/esql-search.md
- skills/elasticsearch/elasticsearch-esql/references/esql-version-history.md
- skills/elasticsearch/elasticsearch-esql/references/generation-tips.md
- skills/elasticsearch/elasticsearch-esql/references/query-patterns.md
- skills/elasticsearch/elasticsearch-esql/references/time-series-queries.md
- skills/elasticsearch/elasticsearch-file-ingest/SKILL.md
- skills/elasticsearch/elasticsearch-file-ingest/references/patterns.md
- skills/elasticsearch/elasticsearch-file-ingest/references/troubleshooting.md
- skills/elasticsearch/elasticsearch-onboarding/SKILL.md
- skills/elasticsearch/elasticsearch-onboarding/references/catalog-ecommerce/ecommerce.md
- skills/elasticsearch/elasticsearch-onboarding/references/elasticsearch-onboarding-playbook.md
- skills/elasticsearch/elasticsearch-onboarding/references/hybrid-search/hybrid-search.md
- skills/elasticsearch/elasticsearch-onboarding/references/keyword-search/keyword-search.md
- skills/elasticsearch/elasticsearch-onboarding/references/rag-chatbot/rag-chatbot.md
- skills/elasticsearch/elasticsearch-onboarding/references/semantic-search/semantic-search.md
- skills/elasticsearch/elasticsearch-onboarding/references/vector-database/vector-database.md
- skills/elasticsearch/elasticsearch-security-troubleshooting/SKILL.md
- skills/elasticsearch/elasticsearch-security-troubleshooting/references/api-reference.md
- skills/kibana/agent-builder/SKILL.md
- skills/kibana/agent-builder/references/architecture-guide.md
- skills/kibana/agent-builder/references/use-cases.md
- skills/kibana/kibana-alerting-rules/SKILL.md
- skills/kibana/kibana-audit/SKILL.md
- skills/kibana/kibana-audit/references/api-reference.md
- skills/kibana/kibana-connectors/SKILL.md
- skills/kibana/kibana-connectors/references/action-design.md
- skills/kibana/kibana-connectors/references/workflows.md
- skills/kibana/kibana-dashboards/SKILL.md
- skills/kibana/kibana-dashboards/references/chart-types-reference.md
- skills/kibana/kibana-dashboards/references/dashboard-api-reference.md
- skills/kibana/kibana-dashboards/references/lens-api-reference.md
- skills/kibana/kibana-vega/SKILL.md
- skills/kibana/kibana-vega/references/dashboard-layout-reference.md
- skills/kibana/kibana-vega/references/vega-esql-reference.md
- skills/kibana/kibana-vega/references/vega-lite-reference.md
- skills/kibana/streams/SKILL.md
- skills/kibana/streams/references/streams-api-reference.md
- skills/observability/edot-dotnet-instrument/SKILL.md
- skills/observability/edot-dotnet-migrate/SKILL.md
- skills/observability/edot-java-instrument/SKILL.md
- skills/observability/edot-java-migrate/SKILL.md
- skills/observability/edot-python-instrument/SKILL.md
- skills/observability/edot-python-migrate/SKILL.md
- skills/observability/llm-obs/SKILL.md
- skills/observability/logs-search/SKILL.md
- skills/observability/logs-search/references/log-search-reference.md
- skills/observability/manage-slos/SKILL.md
- skills/observability/service-health/SKILL.md
- skills/observability/service-health/references/api-reference.md
- skills/security/alert-triage/SKILL.md
- skills/security/alert-triage/references/classification-guide.md
- skills/security/case-management/SKILL.md
- skills/security/case-management/references/kibana-cases-api.md
- skills/security/detection-rule-management/SKILL.md
- skills/security/detection-rule-management/references/detection-api-reference.md
- skills/security/detection-rule-management/references/endpoint-behavior-tuning-workflow.md
- skills/security/detection-rule-management/references/endpoint-exceptions-guide.md
- skills/security/detection-rule-management/references/endpoint-rule-exclusion-best-practices.md
- skills/security/generate-security-sample-data/SKILL.md
- skills/security/generate-security-sample-data/references/sample-data-reference.md

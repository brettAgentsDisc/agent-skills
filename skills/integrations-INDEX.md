# Elastic Integrations Index
Generated for agent-assisted navigation.

## Overview
- Purpose: This repository contains source packages for Elastic Integrations. Each package defines how to observe a specific product or service with the Elastic Stack (Elastic Agent, Kibana dashboards, Elasticsearch index templates).
- Total integrations: 434
- Categories: advanced_analytics_ueba, analytics_engine, application_observability, asset_inventory, auditd, authentication, aws, azure, big_data, cdn_security, cloud, cloudsecurity_cdr, config_management, connector, containers, credential_management, crm, custom, custom_logs, database_security, datastore, dns_security, edr_xdr, elastic_stack, email_security, enterprise_search, firewall_security, google_cloud, iam, ids_ips, infrastructure, java_observability, kubernetes, load_balancer, message_queue, misconfiguration_workflow, monitoring, network, network_security, observability, opentelemetry, os_system, process_manager, productivity, productivity_security, proxy_security, security, siem, stream_processing, threat_intel, virtualization, vpn_security, vulnerability_management, vulnerability_workflow, web, web_application_firewall, websphere
- Package format: Each integration lives under packages/<name>/ with a manifest.yml, docs/, data_stream/, and optionally _dev/ directories
- Public docs: https://www.elastic.co/docs/current/integrations

## Repository Structure
```
integrations/
  packages/           # All integration packages (434 total)
    <name>/
      manifest.yml    # Package metadata, version, categories, inputs
      docs/           # Documentation (README.md)
      data_stream/    # Data stream definitions (logs, metrics)
      _dev/           # Development/test resources
      img/            # Icons and screenshots
  docs/               # Repository-level documentation
  CONTRIBUTING.md     # Contribution guide
  README.md           # Repository overview
```

## Key Integrations (most commonly used)

### System
- Name: `system`
- Path: `packages/system/`
- Description: Collect system logs and metrics from your servers with Elastic Agent.
- Version: 2.16.1
- Categories: os_system, monitoring, observability
- Docs: `packages/system/docs/README.md`

### Windows
- Name: `windows`
- Path: `packages/windows/`
- Description: Collect logs and metrics from Windows OS and services with Elastic Agent.
- Version: 3.8.1
- Categories: os_system, security, observability
- Docs: `packages/windows/docs/README.md`

### Linux Metrics
- Name: `linux`
- Path: `packages/linux/`
- Description: Collect metrics from Linux servers with Elastic Agent.
- Version: 1.1.0
- Categories: os_system
- Docs: `packages/linux/docs/README.md`

### macOS Security Events
- Name: `macos`
- Path: `packages/macos/`
- Description: Collect logs from macOS with Elastic Agent.
- Version: 1.0.0
- Categories: security
- Docs: `packages/macos/docs/README.md`

### AWS
- Name: `aws`
- Path: `packages/aws/`
- Description: Collect logs and metrics from Amazon Web Services (AWS) with Elastic Agent.
- Version: 6.5.0
- Categories: aws, cloud, observability, security, containers, network, datastore
- Docs: `packages/aws/docs/README.md`

### Amazon Bedrock
- Name: `aws_bedrock`
- Path: `packages/aws_bedrock/`
- Description: Collect Amazon Bedrock model invocation logs and runtime metrics with Elastic Agent.
- Version: 1.5.1
- Categories: aws, cloud, observability, security
- Docs: `packages/aws_bedrock/docs/README.md`

### Custom AWS Logs
- Name: `aws_logs`
- Path: `packages/aws_logs/`
- Description: Collect raw logs from AWS S3 or CloudWatch with Elastic Agent.
- Version: 1.8.3
- Categories: cloud, observability, custom, aws
- Docs: `packages/aws_logs/docs/README.md`

### AWS Cost and Usage Report (CUR 2.0)
- Name: `aws_billing`
- Path: `packages/aws_billing/`
- Description: Collect AWS CUR 2.0 billing data from S3 with Elastic Agent.
- Version: 0.2.1
- Categories: aws, cloud, observability
- Docs: `packages/aws_billing/docs/README.md`

### Google Cloud Platform
- Name: `gcp`
- Path: `packages/gcp/`
- Description: Collect logs and metrics from Google Cloud Platform with Elastic Agent.
- Version: 2.49.0
- Categories: google_cloud, cloud, observability, containers, datastore, security
- Docs: `packages/gcp/docs/README.md`

### GCP Metrics Input
- Name: `gcp_metrics`
- Path: `packages/gcp_metrics/`
- Description: GCP Metrics Input
- Version: 0.3.1
- Categories: cloud, observability, google_cloud, custom
- Docs: `packages/gcp_metrics/docs/README.md`

### Custom Google Pub/Sub Logs
- Name: `gcp_pubsub`
- Path: `packages/gcp_pubsub/`
- Description: Collect Logs from Google Pub/Sub topics
- Version: 2.2.1
- Categories: observability, google_cloud, cloud, custom
- Docs: `packages/gcp_pubsub/docs/README.md`

### GCP Vertex AI
- Name: `gcp_vertexai`
- Path: `packages/gcp_vertexai/`
- Description: Collect GCP Vertex AI metrics and logs with Elastic Agent
- Version: 1.4.0
- Categories: cloud, google_cloud, observability
- Docs: `packages/gcp_vertexai/docs/README.md`

### Azure Logs
- Name: `azure`
- Path: `packages/azure/`
- Description: This Elastic integration collects logs from Azure
- Version: 1.36.1
- Categories: cloud, azure, observability, security
- Docs: `packages/azure/docs/README.md`

### Azure Resource Metrics
- Name: `azure_metrics`
- Path: `packages/azure_metrics/`
- Description: Collect metrics from Azure resources with Elastic Agent.
- Version: 1.11.0
- Categories: cloud, observability, azure, custom, containers, datastore
- Docs: `packages/azure_metrics/docs/README.md`

### Azure Billing Metrics
- Name: `azure_billing`
- Path: `packages/azure_billing/`
- Description: Collect billing metrics with Elastic Agent.
- Version: 1.9.0
- Categories: cloud, observability, azure
- Docs: `packages/azure_billing/docs/README.md`

### Custom Azure Blob Storage Input
- Name: `azure_blob_storage`
- Path: `packages/azure_blob_storage/`
- Description: Collect log data from configured Azure Blob Storage Container with Elastic Agent.
- Version: 2.3.0
- Categories: azure, observability, cloud, custom
- Docs: `packages/azure_blob_storage/docs/README.md`

### Kubernetes
- Name: `kubernetes`
- Path: `packages/kubernetes/`
- Description: Collect logs and metrics from Kubernetes clusters with Elastic Agent.
- Version: 1.85.0
- Categories: observability, containers, kubernetes
- Docs: `packages/kubernetes/docs/README.md`

### Docker
- Name: `docker`
- Path: `packages/docker/`
- Description: Collect metrics and logs from Docker instances with Elastic Agent.
- Version: 2.15.1
- Categories: observability, containers
- Docs: `packages/docker/docs/README.md`

### Nginx
- Name: `nginx`
- Path: `packages/nginx/`
- Description: Collect logs and metrics from Nginx HTTP servers with Elastic Agent.
- Version: 3.0.0
- Categories: web, observability
- Docs: `packages/nginx/docs/README.md`

### Apache HTTP Server
- Name: `apache`
- Path: `packages/apache/`
- Description: Collect logs and metrics from Apache servers with Elastic Agent.
- Version: 3.0.0
- Categories: web, observability
- Docs: `packages/apache/docs/README.md`

### Apache Tomcat
- Name: `apache_tomcat`
- Path: `packages/apache_tomcat/`
- Description: Collect and parse logs and metrics from Apache Tomcat servers with Elastic Agent.
- Version: 1.13.0
- Categories: web, observability, application_observability
- Docs: `packages/apache_tomcat/docs/README.md`

### Elasticsearch
- Name: `elasticsearch`
- Path: `packages/elasticsearch/`
- Description: Elasticsearch Integration
- Version: 1.20.1
- Categories: elastic_stack, datastore
- Docs: `packages/elasticsearch/docs/README.md`

### Kibana
- Name: `kibana`
- Path: `packages/kibana/`
- Description: Collect logs and metrics from Kibana with Elastic Agent.
- Version: 2.8.0
- Categories: elastic_stack
- Docs: `packages/kibana/docs/README.md`

### Logstash
- Name: `logstash`
- Path: `packages/logstash/`
- Description: Collect logs and metrics from Logstash with Elastic Agent.
- Version: 2.10.1
- Categories: observability, elastic_stack
- Docs: `packages/logstash/docs/README.md`

### Elastic APM
- Name: `apm`
- Path: `packages/apm/`
- Description: Monitor, detect, and diagnose complex application performance issues.
- Version: 9.1.0-preview-1747764883
- Categories: elastic_stack, monitoring, observability
- Docs: `packages/apm/docs/README.md`

### Elastic Agent
- Name: `elastic_agent`
- Path: `packages/elastic_agent/`
- Description: Collect logs and metrics from Elastic Agents.
- Version: 2.7.6
- Categories: elastic_stack
- Docs: `packages/elastic_agent/docs/README.md`

### Microsoft Office 365
- Name: `o365`
- Path: `packages/o365/`
- Description: Collect logs from Microsoft Office 365 with Elastic Agent.
- Version: 3.8.0
- Categories: security, productivity_security, iam, observability
- Docs: `packages/o365/docs/README.md`

### Microsoft Defender for Cloud
- Name: `microsoft_defender_cloud`
- Path: `packages/microsoft_defender_cloud/`
- Description: Collect logs from Microsoft Defender for Cloud with Elastic Agent.
- Version: 3.4.0
- Categories: security, cloudsecurity_cdr, vulnerability_workflow, misconfiguration_workflow
- Docs: `packages/microsoft_defender_cloud/docs/README.md`

### Microsoft Defender XDR
- Name: `m365_defender`
- Path: `packages/m365_defender/`
- Description: Collect logs from Microsoft Defender XDR with Elastic Agent.
- Version: 5.13.0
- Categories: security, edr_xdr, vulnerability_workflow, cloudsecurity_cdr
- Docs: `packages/m365_defender/docs/README.md`

### CrowdStrike
- Name: `crowdstrike`
- Path: `packages/crowdstrike/`
- Description: Collect logs from Crowdstrike with Elastic Agent.
- Version: 3.14.0
- Categories: security, edr_xdr
- Docs: `packages/crowdstrike/docs/README.md`

### SentinelOne
- Name: `sentinel_one`
- Path: `packages/sentinel_one/`
- Description: Collect logs from SentinelOne with Elastic Agent.
- Version: 2.6.0
- Categories: security, edr_xdr
- Docs: `packages/sentinel_one/docs/README.md`

### Okta
- Name: `okta`
- Path: `packages/okta/`
- Description: Collect and parse event logs from Okta API with Elastic Agent.
- Version: 3.14.1
- Categories: security, iam
- Docs: `packages/okta/docs/README.md`

### Auth0
- Name: `auth0`
- Path: `packages/auth0/`
- Description: Collect logs from Auth0 with Elastic Agent.
- Version: 1.23.1
- Categories: security, iam
- Docs: `packages/auth0/docs/README.md`

### PostgreSQL
- Name: `postgresql`
- Path: `packages/postgresql/`
- Description: Collect logs and metrics from PostgreSQL servers with Elastic Agent.
- Version: 1.32.1
- Categories: datastore, observability
- Docs: `packages/postgresql/docs/README.md`

### MySQL
- Name: `mysql`
- Path: `packages/mysql/`
- Description: Collect logs and metrics from MySQL servers with Elastic Agent.
- Version: 1.29.2
- Categories: datastore, observability
- Docs: `packages/mysql/docs/README.md`

### MongoDB
- Name: `mongodb`
- Path: `packages/mongodb/`
- Description: Collect logs and metrics from MongoDB instances with Elastic Agent.
- Version: 1.24.0
- Categories: datastore, observability
- Docs: `packages/mongodb/docs/README.md`

### Redis
- Name: `redis`
- Path: `packages/redis/`
- Description: Collect logs and metrics from Redis servers with Elastic Agent.
- Version: 1.20.0
- Categories: datastore, observability
- Docs: `packages/redis/docs/README.md`

### Kafka
- Name: `kafka`
- Path: `packages/kafka/`
- Description: Collect logs and metrics from Kafka servers with Elastic Agent.
- Version: 1.27.0
- Categories: stream_processing, observability
- Docs: `packages/kafka/docs/README.md`

### RabbitMQ Logs and Metrics
- Name: `rabbitmq`
- Path: `packages/rabbitmq/`
- Description: Collect and parse logs from RabbitMQ servers with Elastic Agent.
- Version: 1.22.0
- Categories: message_queue, observability
- Docs: `packages/rabbitmq/docs/README.md`

### Prometheus
- Name: `prometheus`
- Path: `packages/prometheus/`
- Description: Collect metrics from Prometheus servers with Elastic Agent.
- Version: 1.24.2
- Categories: observability, monitoring, containers
- Docs: `packages/prometheus/docs/README.md`

### Network Packet Capture
- Name: `network_traffic`
- Path: `packages/network_traffic/`
- Description: Capture and analyze network traffic from a host with Elastic Agent.
- Version: 1.34.2
- Categories: network, security
- Docs: `packages/network_traffic/docs/README.md`

### Cloudflare
- Name: `cloudflare`
- Path: `packages/cloudflare/`
- Description: Collect logs from Cloudflare with Elastic Agent.
- Version: 2.33.0
- Categories: security, network, cdn_security
- Docs: `packages/cloudflare/docs/README.md`

### Cloudflare Logpush
- Name: `cloudflare_logpush`
- Path: `packages/cloudflare_logpush/`
- Description: Collect and parse logs from Cloudflare API with Elastic Agent.
- Version: 1.43.4
- Categories: security, network, cdn_security
- Docs: `packages/cloudflare_logpush/docs/README.md`

### Cisco ASA
- Name: `cisco_asa`
- Path: `packages/cisco_asa/`
- Description: Collect logs from Cisco ASA with Elastic Agent.
- Version: 2.45.0
- Categories: network, security, firewall_security
- Docs: `packages/cisco_asa/docs/README.md`

### Cisco Duo
- Name: `cisco_duo`
- Path: `packages/cisco_duo/`
- Description: Collect logs from Cisco Duo with Elastic Agent.
- Version: 2.9.0
- Categories: security, iam
- Docs: `packages/cisco_duo/docs/README.md`

### Cisco Meraki
- Name: `cisco_meraki`
- Path: `packages/cisco_meraki/`
- Description: Collect logs from Cisco Meraki with Elastic Agent.
- Version: 1.31.1
- Categories: network, security, cloud
- Docs: `packages/cisco_meraki/docs/README.md`

### Palo Alto Next-Gen Firewall
- Name: `panw`
- Path: `packages/panw/`
- Description: Collect logs from Palo Alto next-gen firewalls with Elastic Agent.
- Version: 5.5.0
- Categories: security, network
- Docs: `packages/panw/docs/README.md`

### Fortinet FortiGate Firewall Logs
- Name: `fortinet_fortigate`
- Path: `packages/fortinet_fortigate/`
- Description: Collect logs from Fortinet FortiGate firewalls with Elastic Agent.
- Version: 1.36.5
- Categories: security, network, firewall_security
- Docs: `packages/fortinet_fortigate/docs/README.md`

### GitHub
- Name: `github`
- Path: `packages/github/`
- Description: Collect logs from GitHub with Elastic Agent.
- Version: 2.22.1
- Categories: security, productivity_security
- Docs: `packages/github/docs/README.md`

### GitLab
- Name: `gitlab`
- Path: `packages/gitlab/`
- Description: Collect logs from GitLab with Elastic Agent.
- Version: 2.6.0
- Categories: security, productivity_security
- Docs: `packages/gitlab/docs/README.md`

### Google Workspace
- Name: `google_workspace`
- Path: `packages/google_workspace/`
- Description: Collect logs from Google Workspace with Elastic Agent.
- Version: 3.3.1
- Categories: security, productivity_security
- Docs: `packages/google_workspace/docs/README.md`

### Google Security Command Center
- Name: `google_scc`
- Path: `packages/google_scc/`
- Description: Collect logs from Google Security Command Center with Elastic Agent.
- Version: 2.4.0
- Categories: google_cloud, security, cloudsecurity_cdr, vulnerability_workflow, misconfiguration_workflow
- Docs: `packages/google_scc/docs/README.md`

### CrowdStrike Falcon Intelligence
- Name: `ti_crowdstrike`
- Path: `packages/ti_crowdstrike/`
- Description: Collect logs from CrowdStrike Falcon Intelligence with Elastic Agent.
- Version: 2.7.1
- Categories: security, threat_intel
- Docs: `packages/ti_crowdstrike/docs/README.md`

### abuse.ch
- Name: `ti_abusech`
- Path: `packages/ti_abusech/`
- Description: Ingest threat intelligence indicators from URL Haus, Malware Bazaar, and Threat Fox feeds with Elastic Agent.
- Version: 3.6.0
- Categories: security, threat_intel
- Docs: `packages/ti_abusech/docs/README.md`

### Osquery Logs
- Name: `osquery`
- Path: `packages/osquery/`
- Description: Collect logs from Osquery with Elastic Agent.
- Version: 1.24.1
- Categories: security
- Docs: `packages/osquery/docs/README.md`

### File Integrity Monitoring
- Name: `fim`
- Path: `packages/fim/`
- Description: The File Integrity Monitoring integration reports filesystem changes in real time.
- Version: 1.16.0
- Categories: security
- Docs: `packages/fim/docs/README.md`

### Auditd Logs
- Name: `auditd`
- Path: `packages/auditd/`
- Description: Collect logs from Linux audit daemon with Elastic Agent.
- Version: 3.22.2
- Categories: security, auditd
- Docs: `packages/auditd/docs/README.md`

### HAProxy
- Name: `haproxy`
- Path: `packages/haproxy/`
- Description: Collect logs and metrics from HAProxy servers with Elastic Agent.
- Version: 1.18.0
- Categories: load_balancer, observability
- Docs: `packages/haproxy/docs/README.md`

### Envoyproxy
- Name: `envoyproxy`
- Path: `packages/envoyproxy/`
- Description: Envoyproxy Integration
- Version: 0.4.0
- Categories: observability
- Docs: `packages/envoyproxy/docs/README.md`

### Istio
- Name: `istio`
- Path: `packages/istio/`
- Description: Collect logs and metrics from the service mesh Istio with Elastic Agent.
- Version: 0.8.0
- Categories: observability, network, containers, kubernetes
- Docs: `packages/istio/docs/README.md`

### Ceph
- Name: `ceph`
- Path: `packages/ceph/`
- Description: This Elastic integration collects metrics from Ceph instance.
- Version: 1.9.0
- Categories: datastore, os_system, observability
- Docs: `packages/ceph/docs/README.md`

### Cassandra
- Name: `cassandra`
- Path: `packages/cassandra/`
- Description: This Elastic integration collects logs and metrics from cassandra.
- Version: 1.20.0
- Categories: datastore, observability
- Docs: `packages/cassandra/docs/README.md`

### CockroachDB Metrics
- Name: `cockroachdb`
- Path: `packages/cockroachdb/`
- Description: Collect metrics from CockroachDB servers with Elastic Agent.
- Version: 1.13.1
- Categories: observability, datastore
- Docs: `packages/cockroachdb/docs/README.md`

### Slack Logs
- Name: `slack`
- Path: `packages/slack/`
- Description: Slack Logs Integration
- Version: 1.27.0
- Categories: productivity, security
- Docs: `packages/slack/docs/README.md`

### Zoom
- Name: `zoom`
- Path: `packages/zoom/`
- Description: Collect logs from Zoom with Elastic Agent.
- Version: 1.23.0
- Categories: security, productivity_security, observability
- Docs: `packages/zoom/docs/README.md`

### Snort
- Name: `snort`
- Path: `packages/snort/`
- Description: Collect logs from Snort with Elastic Agent.
- Version: 1.21.1
- Categories: ids_ips, security, network_security
- Docs: `packages/snort/docs/README.md`

### Suricata
- Name: `suricata`
- Path: `packages/suricata/`
- Description: Collect logs from Suricata with Elastic Agent.
- Version: 2.27.0
- Categories: network, security, ids_ips, network_security
- Docs: `packages/suricata/docs/README.md`

### Zeek
- Name: `zeek`
- Path: `packages/zeek/`
- Description: Collect logs from Zeek with Elastic Agent.
- Version: 4.1.0
- Categories: network, security
- Docs: `packages/zeek/docs/README.md`

## Complete Integration List

- **1password** (1.34.0) -- Collect logs from 1Password with Elastic Agent.
- **abnormal_security** (1.14.0) -- Collect logs from Abnormal AI with Elastic Agent.
- **activemq** (1.9.0) -- Collect logs and metrics from ActiveMQ instances with Elastic Agent.
- **activemq_otel** (0.1.0) -- ActiveMQ Assets for OpenTelemetry Collector
- **admin_by_request_epm** (1.1.2) -- Collect logs from Admin By Request EPM with Elastic Agent.
- **agentless_hello_world** (0.1.0) -- A sample integration to exercise the Agentless infrastructure by fetching https://epr.elastic.co every minute.
- **airflow** (1.0.0) -- Airflow Integration.
- **airflow_otel** (0.1.0) -- Airflow OpenTelemetry Integration.
- **airlock_digital** (0.3.0) -- Collect logs from Airlock Digital with Elastic Agent.
- **akamai** (3.1.1) -- Collect logs from Akamai with Elastic Agent.
- **amazon_security_lake** (2.8.2) -- Collect logs from Amazon Security Lake with Elastic Agent.
- **apache** (3.0.0) -- Collect logs and metrics from Apache servers with Elastic Agent.
- **apache_input_otel** (0.1.0) -- Collect Apache HTTP Server status metrics using OpenTelemetry Collector
- **apache_otel** (0.3.0) -- Apache HTTP Server Assets for OpenTelemetry Collector
- **apache_spark** (1.5.0) -- Collect metrics from Apache Spark with Elastic Agent.
- **apache_tomcat** (1.13.0) -- Collect and parse logs and metrics from Apache Tomcat servers with Elastic Agent.
- **apache_tomcat_otel** (0.1.0) -- Apache Tomcat Assets from OpenTelemetry Collector
- **apm** (9.1.0-preview-1747764883) -- Monitor, detect, and diagnose complex application performance issues.
- **arista_ngfw** (1.6.2) -- Collect logs and metrics from Arista NG Firewall.
- **armis** (0.4.1) -- Collect logs from Armis with Elastic Agent.
- **atlassian_bitbucket** (2.6.0) -- Collect logs from Atlassian Bitbucket with Elastic Agent.
- **atlassian_confluence** (1.30.0) -- Collect logs from Atlassian Confluence with Elastic Agent.
- **atlassian_jira** (1.31.0) -- Collect logs from Atlassian Jira with Elastic Agent.
- **auditd** (3.22.2) -- Collect logs from Linux audit daemon with Elastic Agent.
- **auditd_manager** (1.19.1) -- The Auditd Manager Integration receives audit events from the Linux Audit Framework that is a part of the Linux kernel.
- **auth0** (1.23.1) -- Collect logs from Auth0 with Elastic Agent.
- **authentik** (1.8.0) -- Collect logs from authentik with Elastic Agent.
- **aws** (6.5.0) -- Collect logs and metrics from Amazon Web Services (AWS) with Elastic Agent.
- **aws_bedrock** (1.5.1) -- Collect Amazon Bedrock model invocation logs and runtime metrics with Elastic Agent.
- **aws_bedrock_agentcore** (0.7.0) -- Collect Amazon Bedrock AgentCore's Agent runtime, Gateway, Identity, Memory, Browser Tools and Code Interpreter metri...
- **aws_billing** (0.2.1) -- Collect AWS CUR 2.0 billing data from S3 with Elastic Agent.
- **aws_cloudtrail_otel** (0.1.0) -- AWS CloudTrail Logs OpenTelemetry Assets
- **aws_elb_otel** (0.1.1) -- AWS ELB logs for OpenTelemetry Collector
- **aws_logs** (1.8.3) -- Collect raw logs from AWS S3 or CloudWatch with Elastic Agent.
- **aws_mq** (1.0.0) -- Collect Amazon MQ metrics and logs with Elastic Agent
- **aws_securityhub** (0.3.0) -- Collect logs from AWS Security Hub with Elastic Agent.
- **aws_vpcflow_otel** (0.2.0) -- AWS VPC Flow Logs OpenTelemetry Assets
- **aws_waf_otel** (0.1.0) -- AWS WAF Logs OpenTelemetry Assets
- **awsfargate** (1.3.0) -- Collects metrics from containers and tasks running on Amazon ECS clusters with Elastic Agent.
- **awsfirehose** (1.9.0) -- Stream logs and metrics from Amazon Data Firehose into Elastic Cloud.
- **azure** (1.36.1) -- This Elastic integration collects logs from Azure
- **azure_ai_foundry** (0.9.1) -- Collects Microsoft Foundry logs and metrics
- **azure_app_service** (1.1.0) -- Collect logs from Azure App Service with Elastic Agent.
- **azure_application_insights** (1.10.0) -- Collect application insights metrics from Azure Monitor with Elastic Agent.
- **azure_billing** (1.9.0) -- Collect billing metrics with Elastic Agent.
- **azure_blob_storage** (2.3.0) -- Collect log data from configured Azure Blob Storage Container with Elastic Agent.
- **azure_frontdoor** (2.3.0) -- This Elastic integration collects logs from Azure Frontdoor.
- **azure_functions** (0.12.0) -- Get metrics and logs from Azure Functions
- **azure_logs** (0.6.0) -- Collect log events from Azure Event Hubs with Elastic Agent
- **azure_metrics** (1.11.0) -- Collect metrics from Azure resources with Elastic Agent.
- **azure_network_watcher_nsg** (1.5.1) -- Collect logs from Azure Network Watcher NSG with Elastic Agent.
- **azure_network_watcher_vnet** (1.6.0) -- Collect logs from Azure Network Watcher VNet with Elastic Agent.
- **azure_openai** (1.11.0) -- Collects Azure OpenAI Logs and Metrics
- **barracuda** (1.18.0) -- Collect logs from Barracuda Web Application Firewall with Elastic Agent.
- **barracuda_cloudgen_firewall** (1.16.0) -- Collect logs from Barracuda CloudGen Firewall devices with Elastic Agent.
- **bbot** (1.4.0) -- BBOT is a recursive internet scanner inspired by Spiderfoot, but designed to be faster, more reliable, and friendlier...
- **beaconing** (1.5.3) -- Package to identify beaconing activity in your network events.
- **beat** (1.0.1) -- Beat Integration
- **beelzebub** (0.4.0) -- Beelzebub is an advanced honeypot framework designed to provide a highly secure environment for detecting and analyzi...
- **beyondinsight_password_safe** (1.0.0) -- Ingest privileged access management (PAM) data from BeyondTrust's BeyondInsight PAM Reporting Platform and Password S...
- **beyondtrust_pra** (0.3.3) -- Collect logs from BeyondTrust PRA with Elastic Agent.
- **bitdefender** (2.8.0) -- Ingest BitDefender GravityZone logs and data
- **bitsight** (0.1.1) -- Ingest data from the Bitsight API.
- **bitwarden** (1.18.0) -- Collect logs from Bitwarden with Elastic Agent.
- **blacklens** (1.0.1) -- Collect logs from blacklens.io with Elastic Agent
- **bluecoat** (0.18.1) -- Deprecated. Director is no longer supported.
- **box_events** (3.1.2) -- Collect logs from Box with Elastic Agent
- **canva** (1.0.0) -- Collect logs from Canva with Elastic Agent.
- **carbon_black_cloud** (4.2.0) -- Collect logs from VMWare Carbon Black Cloud with Elastic Agent.
- **carbonblack_edr** (1.21.0) -- Collect logs from VMware Carbon Black EDR with Elastic Agent.
- **cassandra** (1.20.0) -- This Elastic integration collects logs and metrics from cassandra.
- **cassandra_otel** (0.1.0) -- Apache Cassandra Assets from OpenTelemetry Collector
- **cef** (2.23.1) -- Collect logs from CEF Logs with Elastic Agent.
- **cel** (1.19.0) -- Collect custom events from an API with Elastic agent
- **ceph** (1.9.0) -- This Elastic integration collects metrics from Ceph instance.
- **checkpoint** (1.45.4) -- Collect logs from Check Point with Elastic Agent.
- **checkpoint_email** (1.4.0) -- Collect logs from Check Point Harmony Email & Collaboration with Elastic Agent.
- **checkpoint_harmony_endpoint** (1.2.0) -- Collect logs from Check Point Harmony Endpoint
- **cisa_kevs** (1.7.0) -- This package allows the ingest of known exploited vulnerabilities according to the Cybersecurity and Infrastructure S...
- **cisco_aironet** (1.20.0) -- Integration for Cisco Aironet WLC Logs
- **cisco_asa** (2.45.0) -- Collect logs from Cisco ASA with Elastic Agent.
- **cisco_duo** (2.9.0) -- Collect logs from Cisco Duo with Elastic Agent.
- **cisco_ftd** (3.13.2) -- Collect logs from Cisco FTD with Elastic Agent.
- **cisco_ios** (1.35.2) -- Collect logs from Cisco IOS with Elastic Agent.
- **cisco_ise** (1.32.3) -- Collect logs from Cisco ISE with Elastic Agent.
- **cisco_meraki** (1.31.1) -- Collect logs from Cisco Meraki with Elastic Agent.
- **cisco_meraki_metrics** (0.4.3) -- Collect metrics from Cisco Meraki with Elastic Agent.
- **cisco_nexus** (1.6.0) -- Collect logs from Cisco Nexus with Elastic Agent.
- **cisco_secure_email_gateway** (1.29.0) -- Collect logs from Cisco Secure Email Gateway with Elastic Agent.
- **cisco_secure_endpoint** (2.33.1) -- Collect logs from Cisco Secure Endpoint (AMP) with Elastic Agent.
- **cisco_umbrella** (1.33.1) -- Collect logs from Cisco Umbrella with Elastic Agent.
- **citrix_adc** (1.18.4) -- This Elastic integration collects logs and metrics from Citrix ADC product.
- **citrix_waf** (1.20.0) -- Ingest events from Citrix Systems Web App Firewall.
- **claroty_ctd** (1.2.0) -- Collect logs from Claroty CTD using Elastic Agent.
- **claroty_xdome** (1.0.2) -- Collect logs from Claroty xDome with Elastic Agent.
- **cloud_asset_inventory** (1.5.0) -- Discover and Create Cloud Assets Discovery
- **cloud_defend** (1.4.0) -- Elastic Defend for Containers (BETA) provides cloud-native runtime protections for containerized environments.
- **cloud_security_posture** (3.3.0) -- Identify & remediate configuration risks in your Cloud infrastructure
- **cloudflare** (2.33.0) -- Collect logs from Cloudflare with Elastic Agent.
- **cloudflare_logpush** (1.43.4) -- Collect and parse logs from Cloudflare API with Elastic Agent.
- **cockroachdb** (1.13.1) -- Collect metrics from CockroachDB servers with Elastic Agent.
- **cockroachdb_otel** (0.1.0) -- CockroachDB Assets from OpenTelemetry Collector
- **containerd** (0.6.0) -- Collect metrics from containerd containers.
- **coredns** (0.10.0) -- Collect logs from CoreDNS instances with Elastic Agent.
- **corelight** (1.1.0) -- Collect logs from Corelight with Elastic Agent.
- **couchbase** (1.9.1) -- Collect metrics from Couchbase databases with Elastic Agent.
- **couchdb** (1.5.1) -- Collect metrics from CouchDB with Elastic Agent.
- **couchdb_otel** (0.1.0) -- CouchDB Assets for OpenTelemetry Collector
- **cribl** (1.1.1) -- Stream logs from Cribl into Elastic.
- **crowdstrike** (3.14.0) -- Collect logs from Crowdstrike with Elastic Agent.
- **cyberark_epm** (1.3.3) -- Collect logs from CyberArk EPM with Elastic Agent.
- **cyberark_pta** (1.15.0) -- Collect security logs from Cyberark PTA integration.
- **cyberarkpas** (2.28.0) -- Collect logs from CyberArk Privileged Access Security with Elastic Agent.
- **cybereason** (1.5.0) -- Collect logs from Cybereason with Elastic Agent.
- **cyera** (0.6.0) -- Collect logs from Cyera with Elastic Agent.
- **cylance** (0.24.0) -- Collect logs from CylanceProtect devices with Elastic Agent.
- **darktrace** (2.0.0) -- Collect logs from Darktrace with Elastic Agent.
- **ded** (2.4.2) -- ML package to detect data exfiltration in your network and file data.
- **dga** (2.3.7) -- ML solution package to detect domain generation algorithm (DGA) activity in your network data.
- **digital_guardian** (1.8.0) -- Collect logs from Digital Guardian with Elastic Agent.
- **docker** (2.15.1) -- Collect metrics and logs from Docker instances with Elastic Agent.
- **docker_input_otel** (0.1.0) -- Collect Docker container metrics using OpenTelemetry Collector
- **docker_otel** (0.2.0) -- Utilise the pre-built dashboard for OTel-native metrics of Docker hosts and their running containers
- **ece** (0.0.2) -- This is a helpful integration for all customers using ECE and need to track the events generated within the ECE admin...
- **elastic_agent** (2.7.6) -- Collect logs and metrics from Elastic Agents.
- **elastic_connectors** (1.0.3) -- Sync data from source to the Elasticsearch index.
- **elastic_package_registry** (0.3.1) -- Collect metrics from a Elastic Package Registry instance
- **elastic_security** (0.4.0) -- Collect logs from Elastic Instance with Elastic Agent.
- **elasticsearch** (1.20.1) -- Elasticsearch Integration
- **endace** (0.2.0) -- This Endace integration configures Network Packet Capture for flow generation and adds a pivot field to your Endace p...
- **enterprisesearch** (1.0.1) -- Enterprise Search Integration
- **entityanalytics_ad** (0.18.0) -- Collect User Identities from Active Directory Entity with Elastic Agent.
- **entityanalytics_entra_id** (1.9.1) -- Collect identities from Microsoft Entra ID (formerly Azure Active Directory) with Elastic Agent.
- **entityanalytics_okta** (3.0.0) -- Collect Identities from Okta with Elastic Agent.
- **entro** (0.2.0) -- Collect logs from Entro with Elastic Agent.
- **envoyproxy** (0.4.0) -- Envoyproxy Integration
- **envoyproxy_otel** (0.1.0) -- Envoyproxy Assets for OpenTelemetry Collector
- **eset_protect** (2.1.1) -- Collect logs from ESET PROTECT with Elastic Agent.
- **ess_billing** (1.7.1) -- Collects billing metrics from Elasticsearch Service billing API
- **etcd** (1.4.1) -- Collect metrics from etcd instances with Elastic Agent.
- **etcd_otel** (0.1.0) -- etcd Assets from OpenTelemetry Collector
- **extrahop** (0.2.1) -- Collect logs from ExtraHop RevealX 360 with Elastic Agent.
- **f5_bigip** (1.27.3) -- Collect logs from F5 BIG-IP with Elastic Agent.
- **falco** (2.0.2) -- Collect events and alerts from Falco using Elastic Agent
- **filelog_otel** (0.2.0) -- Tails and parses logs from files using the filelog receiver of the OTel collector.
- **filestream** (2.4.0) -- Collect log data using filestream with Elastic Agent.
- **fim** (1.16.0) -- The File Integrity Monitoring integration reports filesystem changes in real time.
- **fireeye** (1.27.1) -- Collect logs from FireEye NX with Elastic Agent.
- **first_epss** (1.2.0) -- Collect exploit prediction score data from the First EPSS API with Elastic Agent.
- **fleet_server** (1.6.1) -- Centrally manage Elastic Agents with the Fleet Server integration.
- **forcepoint_web** (1.13.0) -- Forcepoint Web Security
- **forgerock** (1.22.0) -- Collect audit logs from ForgeRock with Elastic Agent.
- **fortinet_forticlient** (1.12.1) -- Deprecated. Fortinet FortiClient Logs is no longer supported.
- **fortinet_fortiedr** (1.21.0) -- Collect logs from Fortinet FortiEDR instances with Elastic Agent.
- **fortinet_fortigate** (1.36.5) -- Collect logs from Fortinet FortiGate firewalls with Elastic Agent.
- **fortinet_fortimail** (2.19.0) -- Collect logs from Fortinet FortiMail instances with Elastic Agent.
- **fortinet_fortimanager** (2.18.0) -- Collect logs from Fortinet FortiManager instances with Elastic Agent.
- **fortinet_fortiproxy** (1.4.0) -- Collect logs from Fortinet FortiProxy with Elastic Agent.
- **gcp** (2.49.0) -- Collect logs and metrics from Google Cloud Platform with Elastic Agent.
- **gcp_audit_otel** (0.1.0) -- GCP Audit Logs OpenTelemetry Assets
- **gcp_metrics** (0.3.1) -- GCP Metrics Input
- **gcp_pubsub** (2.2.1) -- Collect Logs from Google Pub/Sub topics
- **gcp_vertexai** (1.4.0) -- Collect GCP Vertex AI metrics and logs with Elastic Agent
- **gcp_vpcflow_otel** (0.1.0) -- GCP VPC Flow Logs OpenTelemetry Assets
- **gigamon** (2.2.0) -- Collect logs from Gigamon with Elastic Agent.
- **github** (2.22.1) -- Collect logs from GitHub with Elastic Agent.
- **gitlab** (2.6.0) -- Collect logs from GitLab with Elastic Agent.
- **goflow2** (0.7.0) -- Collect logs from goflow2 with Elastic Agent.
- **golang** (1.9.0) -- This Elastic integration collects metrics from Golang applications.
- **google_cloud_storage** (2.2.0) -- Collect JSON data from configured GCS Bucket with Elastic Agent.
- **google_scc** (2.4.0) -- Collect logs from Google Security Command Center with Elastic Agent.
- **google_secops** (1.2.2) -- Collect alerts from Google SecOps with Elastic Agent.
- **google_workspace** (3.3.1) -- Collect logs from Google Workspace with Elastic Agent.
- **grafana** (0.1.0) -- Collect metrics and logs from Grafana instances with Elastic Agent.
- **greenhouse** (0.1.0) -- Collect audit logs from Greenhouse ATS with Elastic Agent.
- **hadoop** (1.9.0) -- Collect metrics from Apache Hadoop with Elastic Agent.
- **haproxy** (1.18.0) -- Collect logs and metrics from HAProxy servers with Elastic Agent.
- **haproxy_otel** (0.1.0) -- Haproxy Assets for OpenTelemetry Collector
- **hashicorp_vault** (1.30.1) -- Collect logs and metrics from Hashicorp Vault with Elastic Agent.
- **hid_bravura_monitor** (1.21.0) -- Collect logs from Bravura Security Fabric with Elastic Agent.
- **hostmetrics_input_otel** (0.1.0) -- Collect system metrics using OpenTelemetry Collector
- **hpe_aruba_cx** (0.4.1) -- Collect logs from HPE Aruba CX with Elastic Agent
- **hta** (1.0.2) -- Prebuilt dashboard for Machine Learning module Security: Host.
- **http_endpoint** (2.5.0) -- Collect JSON data from listening HTTP port with Elastic Agent.
- **httpcheck_otel** (0.1.0) -- Perform HTTP checks using the HTTP Check receiver of the OTel Collector.
- **httpjson** (1.24.0) -- Collect custom events from an API endpoint with Elastic agent
- **ibm_qradar** (0.2.0) -- Collect logs from IBM QRadar with Elastic Agent.
- **ibmmq** (1.8.0) -- Collect logs and metrics from IBM MQ with Elastic Agent.
- **ibmmq_otel** (0.1.0) -- IBM MQ Assets from OpenTelemetry Collector
- **iis** (1.24.4) -- Collect logs and metrics from Internet Information Services (IIS) servers with Elastic Agent.
- **iis_input_otel** (0.1.0) -- IIS OpenTelemetry Input Package
- **iis_otel** (0.3.0) -- IIS Assets for OpenTelemetry Collector
- **imperva** (1.10.0) -- Collect logs from Imperva devices with Elastic Agent.
- **imperva_cloud_waf** (1.13.1) -- Collect logs from Imperva Cloud WAF with Elastic Agent.
- **influxdb** (0.11.0) -- Collect metrics from Influxdb database
- **influxdb_otel** (0.1.0) -- InfluxDb Assets for OpenTelemetry Collector
- **infoblox_bloxone_ddi** (1.22.0) -- Collect logs from Infoblox BloxOne DDI with Elastic Agent.
- **infoblox_nios** (2.1.1) -- Collect logs from Infoblox NIOS with Elastic Agent.
- **infoblox_threat_defense** (0.1.0) -- Collect logs from Infoblox Threat Defense with Elastic Agent.
- **iptables** (1.23.0) -- Collect logs from Iptables with Elastic Agent.
- **ironscales** (0.1.0) -- Collect logs from IRONSCALES with Elastic Agent.
- **island_browser** (1.0.0) -- Collect logs from Island Browser with Elastic Agent.
- **istio** (0.8.0) -- Collect logs and metrics from the service mesh Istio with Elastic Agent.
- **jamf_compliance_reporter** (1.16.0) -- Collect logs from Jamf Compliance Reporter with Elastic Agent.
- **jamf_pro** (1.1.0) -- Collect logs and inventory data from Jamf Pro with Elastic Agent
- **jamf_protect** (3.3.0) -- Receives events from Jamf Protect with Elastic Agent.
- **jolokia_input** (1.0.0) -- Collects Metrics from Jolokia Agents
- **journald** (1.2.1) -- Collect logs from journald with Elastic Agent.
- **jumpcloud** (1.17.1) -- Collect logs from JumpCloud Directory as a Service
- **juniper_junos** (0.12.1) -- Deprecated. Use the Juniper SRX package instead.
- **juniper_netscreen** (0.12.1) -- Deprecated. Juniper NetScreen is no longer supported.
- **juniper_srx** (1.27.0) -- Collect logs from Juniper SRX devices with Elastic Agent.
- **jupiter_one** (0.1.0) -- Collect logs from JupiterOne with Elastic Agent.
- **kafka** (1.27.0) -- Collect logs and metrics from Kafka servers with Elastic Agent.
- **kafka_connect** (0.1.0) -- Collect metrics from Kafka Connect instances with Elastic Agent.
- **kafka_log** (1.9.1) -- Collect data from kafka topic with Elastic Agent.
- **kafka_otel** (0.1.0) -- Kafka Assets for OpenTelemetry Collector
- **keeper_security_siem_integration** (0.1.0) -- Keeper Security agentless integration for collecting audit events directly via Elasticsearch Bulk API. No agents requ...
- **keycloak** (1.31.2) -- Collect logs from Keycloak with Elastic Agent.
- **kibana** (2.8.0) -- Collect logs and metrics from Kibana with Elastic Agent.
- **kubeletstats_input_otel** (0.1.0) -- Collect Kubernetes node, pod, container, and volume metrics from the Kubelet API using the OpenTelemetry Collector.
- **kubernetes** (1.85.0) -- Collect logs and metrics from Kubernetes clusters with Elastic Agent.
- **kubernetes_otel** (2.0.0-preview5) -- Utilise the pre-built dashboard for OTel-native metrics and events collected from a Kubernetes cluster
- **lastpass** (1.21.0) -- Collect logs from LastPass with Elastic Agent.
- **linux** (1.1.0) -- Collect metrics from Linux servers with Elastic Agent.
- **lmd** (2.6.3) -- ML package to detect lateral movement based on file transfer activity and Windows RDP events.
- **log** (2.4.4) -- Collect custom logs with Elastic Agent.
- **logstash** (2.10.1) -- Collect logs and metrics from Logstash with Elastic Agent.
- **lumos** (1.6.0) -- An integration with Lumos to ship your Activity logs to your Elastic instance.
- **lyve_cloud** (1.17.0) -- Collect S3 API audit log from Lyve Cloud with Elastic Agent.
- **m365_defender** (5.13.0) -- Collect logs from Microsoft Defender XDR with Elastic Agent.
- **macos** (1.0.0) -- Collect logs from macOS with Elastic Agent.
- **mattermost** (2.5.0) -- Collect logs from Mattermost with Elastic Agent.
- **memcached** (1.8.0) -- Memcached Integration
- **memcached_otel** (0.1.0) -- Memcached Assets for OpenTelemetry Collector
- **menlo** (1.7.1) -- Collect logs from Menlo Security products with Elastic Agent
- **microsoft_defender_cloud** (3.4.0) -- Collect logs from Microsoft Defender for Cloud with Elastic Agent.
- **microsoft_defender_endpoint** (4.6.0) -- Collect logs from Microsoft Defender for Endpoint with Elastic Agent.
- **microsoft_dhcp** (1.27.0) -- Collect logs from Microsoft DHCP with Elastic Agent.
- **microsoft_dnsserver** (1.5.1) -- Collect logs from Microsoft DNS Server with Elastic Agent.
- **microsoft_exchange_online_message_trace** (2.0.4) -- Microsoft Exchange Online Message Trace Integration
- **microsoft_exchange_server** (1.5.1) -- Collect logs from Microsoft Exchange Server with Elastic Agent.
- **microsoft_sentinel** (1.3.1) -- Collect logs from Microsoft Sentinel with Elastic Agent.
- **microsoft_sqlserver** (2.16.0) -- Collect events from Microsoft SQL Server with Elastic Agent
- **microsoft_sqlserver_otel** (0.1.0) -- Microsoft SQL Server Assets
- **mimecast** (3.3.1) -- Collect logs from Mimecast with Elastic Agent.
- **miniflux** (1.0.1) -- Collect RSS feed content from the Miniflux API with Elastic Agent.
- **modsecurity** (1.23.1) -- Collect logs from ModSecurity with Elastic Agent
- **mongodb** (1.24.0) -- Collect logs and metrics from MongoDB instances with Elastic Agent.
- **mongodb_atlas** (1.1.0) -- This Elastic integration collects logs and metrics from MongoDB Atlas instance.
- **mongodb_otel** (0.1.0) -- MongoDB Assets for OpenTelemetry Collector
- **mysql** (1.29.2) -- Collect logs and metrics from MySQL servers with Elastic Agent.
- **mysql_enterprise** (1.17.0) -- Collect audit logs from MySQL Enterprise with Elastic Agent.
- **mysql_input_otel** (0.2.1) -- Collect MySQL metrics and logs using OpenTelemetry Collector
- **mysql_otel** (0.4.0) -- MySQL Assets for OpenTelemetry Collector
- **nagios_xi** (1.8.0) -- Collect Logs and Metrics from Nagios XI with Elastic Agent.
- **nats** (1.12.0) -- Collect logs and metrics from NATS servers with Elastic Agent.
- **neon_cyber** (0.1.0) -- The Neon Cyber integration for the Elastic Stack
- **netflow** (2.25.0) -- Collect flow records from NetFlow and IPFIX exporters with Elastic Agent.
- **netscout** (0.22.1) -- Deprecated. Netscout Arbor Peakflow SP is no longer supported.
- **netskope** (3.1.4) -- Collect logs from Netskope with Elastic Agent.
- **network_traffic** (1.34.2) -- Capture and analyze network traffic from a host with Elastic Agent.
- **nextron_thor** (0.0.1) -- Integration for Nextron Thor APT Scanner
- **nginx** (3.0.0) -- Collect logs and metrics from Nginx HTTP servers with Elastic Agent.
- **nginx_ingress_controller** (1.14.0) -- Collect Nginx Ingress Controller logs.
- **nginx_ingress_controller_otel** (0.2.2) -- Collect Nginx Ingress Controller logs using the OpenTelemetry collector.
- **nginx_input_otel** (0.2.0) -- NGINX OpenTelemetry Input Package
- **nginx_otel** (0.3.0) -- NGINX Assets from OpenTelemetry Collector
- **nozomi_networks** (0.2.1) -- Collect logs from Nozomi Networks with Elastic Agent.
- **nvidia_gpu** (0.4.1) -- Monitor NVIDIA GPUs via NVIDIA Data Center GPU Manager
- **nvidia_gpu_otel** (0.1.0) -- NVIDIA GPU Assets for OpenTelemetry Collector
- **o365** (3.8.0) -- Collect logs from Microsoft Office 365 with Elastic Agent.
- **o365_metrics** (1.1.1) -- Collect metrics from Microsoft Office 365 with Elastic Agent.
- **okta** (3.14.1) -- Collect and parse event logs from Okta API with Elastic Agent.
- **openai** (1.2.1) -- Collect OpenAI usage metrics with Elastic Agent.
- **opencanary** (1.0.0) -- This integration collects and parses logs from OpenCanary honeypots.
- **oracle** (1.31.1) -- Collect Oracle Audit Log, Performance metrics, Tablespace metrics, Sysmetrics metrics, System statistics metrics, mem...
- **oracle_otel** (0.1.0) -- Oracle Assets for OpenTelemetry Collector
- **oracle_weblogic** (1.9.1) -- Collect logs and metrics from Oracle WebLogic with Elastic Agent.
- **osquery** (1.24.1) -- Collect logs from Osquery with Elastic Agent.
- **osquery_manager** (1.28.0) -- Deploy Osquery with Elastic Agent, then run and schedule queries in Kibana
- **otel_android_dashboards** (0.1.0) -- Dashboards for visualizing Android application's telemetry
- **otel_collector_internal_telemetry** (1.1.0) -- This package contains dashboards that visualize the internal telemetry from the OpenTelemetry Collector
- **otel_rum_dashboards** (0.0.2) -- RUM status metrics from OpenTelemetry JS SDKs
- **pad** (1.1.2) -- ML package to detect anomalous privileged access activity in Windows, Linux and Okta logs
- **panw** (5.5.0) -- Collect logs from Palo Alto next-gen firewalls with Elastic Agent.
- **panw_cortex_xdr** (2.5.2) -- Collect logs from Palo Alto Cortex XDR with Elastic Agent.
- **panw_metrics** (0.2.0) -- Collect metrics from Palo Alto Networks with Elastic Agent.
- **pfsense** (1.25.2) -- Collect logs from pfSense and OPNsense with Elastic Agent.
- **php_fpm** (1.6.0) -- This Elastic integration collects metrics from PHP-FPM.
- **ping_federate** (1.2.0) -- Collect logs from PingFederate with Elastic Agent.
- **ping_one** (1.23.0) -- Collect logs from PingOne with Elastic-Agent.
- **platform_observability** (0.1.0) -- Collect stack component logs with Elastic Agent
- **postgresql** (1.32.1) -- Collect logs and metrics from PostgreSQL servers with Elastic Agent.
- **postgresql_otel** (0.3.0) -- PostgreSQL Assets for OpenTelemetry Collector
- **pps** (1.2.1) -- Integration for Pleasant Password Server Syslog Messages
- **prisma_access** (1.7.1) -- Collect logs from Palo Alto Prisma Access with Elastic Agent.
- **prisma_cloud** (4.1.0) -- Collect logs from Prisma Cloud with Elastic Agent.
- **problemchild** (2.4.6) -- ML solution package to detect Living off the Land (LotL) attacks in your environment. Requires a Platinum subscription.
- **profilingmetrics_otel** (0.0.5) -- Create metrics from profiling data.
- **prometheus** (1.24.2) -- Collect metrics from Prometheus servers with Elastic Agent.
- **prometheus_input** (1.0.0) -- Collects metrics from Prometheus exporter.
- **prometheus_input_otel** (0.1.0) -- Scrape Prometheus metrics endpoints using the OpenTelemetry Collector Prometheus receiver with guided configuration
- **prometheus_input_otel_raw** (0.1.0) -- Scrape Prometheus metrics endpoints using the OpenTelemetry Collector Prometheus receiver with raw scrape configuration
- **proofpoint_365totalprotection** (0.1.0) -- The Proofpoint 365 Total Protection integration for Elastic collects detailed email security and delivery logs via a ...
- **proofpoint_essentials** (0.1.0) -- Collect logs from Proofpoint Essentials with Elastic Agent.
- **proofpoint_itm** (1.0.1) -- Collect logs from Proofpoint ITM using Elastic Agent.
- **proofpoint_on_demand** (1.9.0) -- Collect logs from Proofpoint On Demand with Elastic Agent.
- **proofpoint_tap** (1.29.1) -- Collect logs from Proofpoint TAP with Elastic Agent.
- **proxysg** (0.8.0) -- Collect access logs from Broadcom ProxySG with Elastic Agent.
- **pulse_connect_secure** (2.6.1) -- Collect logs from Pulse Connect Secure with Elastic Agent.
- **qnap_nas** (1.25.2) -- Collect logs from QNAP NAS devices with Elastic Agent.
- **qualys_gav** (0.7.2) -- Collect logs from Qualys Global AssetView with Elastic Agent.
- **qualys_vmdr** (6.18.0) -- Collect data from Qualys VMDR platform with Elastic Agent.
- **qualys_was** (0.3.1) -- Collect data from Qualys Web Application Scanning platform with Elastic Agent or Agentless
- **rabbitmq** (1.22.0) -- Collect and parse logs from RabbitMQ servers with Elastic Agent.
- **rabbitmq_otel** (0.1.0) -- RabbitMQ Assets for OpenTelemetry Collector
- **radware** (0.20.1) -- Deprecated. Radware DefensePro Logs is no longer supported.
- **rapid7_insightvm** (2.8.0) -- Collect logs from Rapid7 InsightVM with Elastic Agent.
- **redis** (1.20.0) -- Collect logs and metrics from Redis servers with Elastic Agent.
- **redis_input_otel** (0.1.0) -- Redis OpenTelemetry Input Package
- **redis_otel** (0.1.0) -- Redis Assets for OpenTelemetry Collector
- **redisenterprise** (0.12.0) -- Collect metrics from Redis Enterprise Cluster
- **redisenterprise_otel** (0.1.0) -- Redis Enterprise Assets for OpenTelemetry Collector
- **rubrik** (0.9.3) -- Collect Metrics from Rubrik RSC with Elastic Agent.
- **sailpoint_identity_sc** (1.2.0) -- Sailpoint identity security cloud provides enterprise identity governance and security capabilities. The integration ...
- **salesforce** (1.7.1) -- Collect logs from Salesforce instances using the Elastic Agent. This integration enables monitoring and analysis of v...
- **santa** (3.24.0) -- Collect logs from Google Santa with Elastic Agent.
- **security_ai_prompts** (1.0.13) -- Prompts used by Security AI features, including the Security Assistant, and Attack discovery
- **security_detection_engine** (9.3.8) -- Prebuilt detection rules for Elastic Security
- **sentinel_one** (2.6.0) -- Collect logs from SentinelOne with Elastic Agent.
- **sentinel_one_cloud_funnel** (1.13.1) -- Collect logs from SentinelOne Cloud Funnel with Elastic Agent.
- **servicenow** (2.0.0) -- Collect logs from ServiceNow with Elastic Agent.
- **slack** (1.27.0) -- Slack Logs Integration
- **snort** (1.21.1) -- Collect logs from Snort with Elastic Agent.
- **snyk** (3.4.1) -- Collect logs from Snyk with Elastic Agent.
- **sonicwall_firewall** (1.22.0) -- Integration for SonicWall firewall logs
- **sophos** (3.17.0) -- Collect logs from Sophos with Elastic Agent.
- **sophos_central** (1.21.0) -- This Elastic integration collects logs from Sophos Central with Elastic Agent.
- **splunk** (1.0.1) -- Collect logs from Splunk with Elastic Agent.
- **spring_boot** (1.9.1) -- This Elastic integration collects logs and metrics from Spring Boot integration.
- **spycloud** (1.6.0) -- Collect data from SpyCloud Enterprise Protection with Elastic Agent.
- **sql_input** (1.1.0) -- Collects Metrics by querying SQL Databases
- **sql_server_input_otel** (0.1.1) -- Collect SQL Server metrics and logs using OpenTelemetry Collector
- **squid** (1.5.0) -- Collect and parse logs from Squid devices with Elastic Agent.
- **stan** (1.11.0) -- Collect logs and metrics from STAN servers with Elastic Agent.
- **statsd_input** (1.0.0) -- StatsD Input Package
- **statsd_input_otel** (0.1.0) -- StatsD OpenTelemetry Input Package
- **stormshield** (1.5.1) -- Stormshield SNS integration.
- **sublime_security** (1.11.2) -- Collect logs from Sublime Security with Elastic Agent.
- **suricata** (2.27.0) -- Collect logs from Suricata with Elastic Agent.
- **swimlane** (0.4.2) -- Collect Swimlane Turbine Audit logs with Elastic Agent
- **symantec_endpoint** (2.20.0) -- Collect logs from Symantec Endpoint Protection with Elastic Agent.
- **symantec_endpoint_security** (1.14.2) -- Collect logs from Symantec Endpoint Security with Elastic Agent.
- **synthetics** (1.6.1) -- Internal Elastic integration for providing access to private locations.
- **synthetics_dashboards** (1.0.1) -- Explore Elastic Synthetics metrics with these dashboards.
- **sysdig** (2.3.0) -- Collect logs from Sysdig using Elastic Agent.
- **syslog_router** (1.0.1) -- Route syslog events to integrations with Elastic Agent.
- **sysmon_linux** (1.9.0) -- Collect Sysmon Linux logs with Elastic Agent.
- **system** (2.16.1) -- Collect system logs and metrics from your servers with Elastic Agent.
- **system_audit** (1.11.0) -- Collect various logs & metrics from System Audit modules with Elastic Agent.
- **system_otel** (0.2.6) -- Dashboards for the OpenTelemetry data collected with the `hostmetrics` receiver.
- **tanium** (1.17.0) -- This Elastic integration collects logs from Tanium with Elastic Agent.
- **tcp** (2.3.0) -- Collect raw TCP data from listening TCP port with Elastic Agent.
- **teleport** (1.6.0) -- Collect logs from Teleport with Elastic Agent.
- **tenable_io** (4.10.0) -- Collect logs from Tenable Vulnerability Management with Elastic Agent.
- **tenable_ot_security** (1.1.1) -- Tenable OT Security
- **tenable_sc** (2.2.0) -- Collect data from Tenable Security Center with Elastic Agent.
- **tencent_cloud** (0.2.0) -- 从腾讯云的 COS 中采集基础设施日志
- **tetragon** (0.4.0) -- Collect Cilium Tetragon logs from Kubernetes environments.
- **threat_map** (1.1.0) -- The Threat Map integration includes a dashboard for analyzing network traffic data.
- **thycotic_ss** (1.12.1) -- Thycotic Secret Server logs
- **ti_abusech** (3.6.0) -- Ingest threat intelligence indicators from URL Haus, Malware Bazaar, and Threat Fox feeds with Elastic Agent.
- **ti_anomali** (2.6.1) -- Ingest threat intelligence indicators from Anomali ThreatStream with Elastic Agent.
- **ti_anyrun** (1.0.0) -- Ingest Threat Intelligence indicators from ANY.RUN TI Feeds with Elastic Agent
- **ti_cif3** (1.18.2) -- Ingest threat indicators from a Collective Intelligence Framework v3 instance with Elastic Agent.
- **ti_crowdstrike** (2.7.1) -- Collect logs from CrowdStrike Falcon Intelligence with Elastic Agent.
- **ti_custom** (1.5.0) -- Ingest threat intelligence data in STIX 2.1 format with Elastic Agent
- **ti_cybersixgill** (1.34.1) -- Ingest threat intelligence indicators from Cybersixgill with Elastic Agent.
- **ti_cyware_intel_exchange** (0.2.0) -- Collect logs from Cyware Intel Exchange with Elastic Agent.
- **ti_domaintools** (1.3.0) -- DomainTools Feeds provide data on the different stages of the domain lifecycle: from first-observed in the wild, to n...
- **ti_eclecticiq** (1.5.0) -- Ingest threat intelligence from EclecticIQ with Elastic Agent
- **ti_eset** (1.9.0) -- Ingest threat intelligence indicators from ESET Threat Intelligence with Elastic Agent.
- **ti_flashpoint** (0.1.0) -- Collect logs from Flashpoint with Elastic Agent.
- **ti_google_threat_intelligence** (0.8.1) -- Collect Threat Intelligence Events from Google Threat Intelligence using Elastic Agent, and perform enrichment on Ela...
- **ti_greynoise** (0.7.3) -- Collect Threat Intelligence Indicators from GreyNoise using Elastic Agent, and perform enrichment on Elasticsearch by...
- **ti_maltiverse** (1.6.0) -- Ingest threat intelligence indicators from Maltiverse feeds with Elastic Agent
- **ti_mandiant_advantage** (1.10.0) -- Collect Threat Intelligence from products within the Mandiant Advantage platform.
- **ti_misp** (1.41.3) -- Ingest threat intelligence indicators from MISP platform with Elastic Agent.
- **ti_opencti** (2.13.0) -- Ingest threat intelligence indicators from OpenCTI with Elastic Agent.
- **ti_otx** (1.30.1) -- Ingest threat intelligence indicators from AlienVault Open Threat Exchange (OTX) with Elastic Agent.
- **ti_rapid7_threat_command** (2.7.1) -- Collect threat intelligence from Threat Command API with Elastic Agent.
- **ti_recordedfuture** (2.4.2) -- Ingest threat intelligence and alert data from Recorded Future with Elastic Agent.
- **ti_strider** (0.0.1) -- Ingest threat intelligence indicators from Strider Shield with Elastic Agent.
- **ti_threatconnect** (2.0.0) -- Collects Indicators from ThreatConnect using the Elastic Agent and saves them as logs inside Elastic
- **ti_threatq** (1.37.1) -- Ingest threat intelligence indicators from ThreatQuotient with Elastic Agent.
- **ti_util** (1.7.1) -- Prebuilt Threat Intelligence dashboard for Elastic Security
- **tines** (1.16.0) -- Tines Logs & Time Saved Reports
- **tomcat** (1.14.0) -- Collect and parse logs from Apache Tomcat servers with Elastic Agent.
- **traefik** (2.7.0) -- Collect logs from Traefik servers with Elastic Agent.
- **traefik_otel** (0.1.0) -- Traefik Assets for OpenTelemetry Collector
- **trellix_edr_cloud** (1.9.0) -- Collect logs from Trellix EDR Cloud with Elastic Agent.
- **trellix_epo_cloud** (1.15.0) -- Collect logs from Trellix ePO Cloud with Elastic Agent.
- **trend_micro_vision_one** (2.11.0) -- Collect logs from TrendAI Vision One with Elastic Agent.
- **trendmicro** (2.8.2) -- Collect logs from TrendAI Deep Security with Elastic Agent.
- **tychon** (1.1.0) -- Collect complete master endpoint datasets including vulnerability and STIG to comply with DISA endpoint requirements ...
- **udp** (2.5.0) -- Collect raw UDP data from listening UDP port with Elastic Agent.
- **unifiedlogs** (0.5.1) -- Collect and parse logs from macOS unified logs with Elastic Agent.
- **universal_profiling_agent** (8.17.3) -- Fleet-wide, whole-system, continuous profiling with zero instrumentation.
- **universal_profiling_collector** (8.17.3) -- Fleet-wide, whole-system, continuous profiling with zero instrumentation.
- **universal_profiling_symbolizer** (8.17.3) -- Fleet-wide, whole-system, continuous profiling with zero instrumentation.
- **varonis** (1.0.0) -- Collect Varonis syslog alerts using TCP/UDP input.
- **vectra_detect** (1.14.0) -- Collect logs from Vectra Detect with Elastic Agent.
- **vectra_rux** (0.3.3) -- Collect logs from Vectra RUX with Elastic Agent.
- **verifier_otel** (0.0.1) -- Verify identity federation based integration permissions and report results to Elasticsearch using the Verifier recei...
- **vsphere** (1.23.1) -- This Elastic integration collects metrics and logs from vSphere/vCenter servers
- **vsphere_otel** (0.1.0) -- VMware vSphere Assets for OpenTelemetry Collector
- **watchguard_firebox** (1.6.3) -- Collect logs from WatchGuard Firebox with Elastic Agent.
- **websocket** (1.0.1) -- Collect custom events from a socket server with Elastic agent.
- **websphere_application_server** (1.6.1) -- Collects metrics from IBM WebSphere Application Server with Elastic Agent.
- **windows** (3.8.1) -- Collect logs and metrics from Windows OS and services with Elastic Agent.
- **windows_etw** (1.0.0) -- Collect and parse logs from any Windows ETW provider with Elastic Agent.
- **winlog** (2.5.0) -- Collect and parse logs from any Windows event log channel with Elastic Agent.
- **withsecure_elements** (0.2.0) -- Ingest WithSecure Elements incidents and security events data
- **wiz** (4.2.0) -- Collect logs from Wiz with Elastic Agent.
- **wmi** (0.0.2) -- Custom WMI Input Package
- **zeek** (4.1.0) -- Collect logs from Zeek with Elastic Agent.
- **zerofox** (1.29.0) -- Collect logs from ZeroFox with Elastic Agent.
- **zeronetworks** (1.19.0) -- Zero Networks Logs integration
- **zookeeper** (1.14.0) -- Collect metrics from ZooKeeper service with Elastic Agent.
- **zookeeper_otel** (0.1.1) -- Zookeeper OTel Assets
- **zoom** (1.23.0) -- Collect logs from Zoom with Elastic Agent.
- **zscaler_zia** (3.17.1) -- Collect logs from Zscaler Internet Access (ZIA) with Elastic Agent.
- **zscaler_zpa** (1.23.3) -- Collect logs from Zscaler Private Access (ZPA) with Elastic Agent.

## Documentation Files

### Top-level documentation
- `README.md`
- `CONTRIBUTING.md`
- `CODE_OF_CONDUCT.md`
- `LICENSE.txt`
- `docs/ci_pipelines.md`
- `docs/dashboard_guidelines.md`
- `docs/definitions.md`
- `docs/developer_tsdb_migration_guidelines.md`
- `docs/developer_workflow_bug_fix_older_package_version.md`
- `docs/developer_workflow_design_build_test_integration.md`
- `docs/developer_workflow_fleet_ui.md`
- `docs/documentation_guidelines.md`
- `docs/fine_tune_integration.md`
- `docs/generic_guidelines.md`
- `docs/how_to_test_new_indexing_features.md`
- `docs/import_from_beats.md`
- `docs/subobjects_adoption_guide.md`
- `docs/testing_and_validation.md`
- `docs/tips_for_building_integrations.md`
- `docs/yaml_dashboards.md`

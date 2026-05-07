# Elastic Integrations Index
Generated for agent-assisted navigation.

## Overview
- Purpose: This repository contains source packages for Elastic Integrations. Each package defines how to observe a specific product or service with the Elastic Stack (Elastic Agent, Kibana dashboards, Elasticsearch index templates).
- Total integrations: 434
- Package format: Each integration lives under packages/<name>/ with a manifest.yml, docs/, data_stream/, and optionally _dev/ directories
- Public docs: https://www.elastic.co/docs/current/integrations

## Repository Structure
```
integrations/
  packages/           # All integration packages
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

## All Integrations

### 1Password
- Name: `1password`
- Path: `packages/1password/`
- Description: Collect logs from 1Password with Elastic Agent.
- Version: 1.34.0
- Categories: security, credential_management
- Docs: `packages/1password/docs/README.md`

### Abnormal AI
- Name: `abnormal_security`
- Path: `packages/abnormal_security/`
- Description: Collect logs from Abnormal AI with Elastic Agent.
- Version: 1.14.0
- Categories: security
- Docs: `packages/abnormal_security/docs/README.md`

### ActiveMQ
- Name: `activemq`
- Path: `packages/activemq/`
- Description: Collect logs and metrics from ActiveMQ instances with Elastic Agent.
- Version: 1.9.0
- Categories: message_queue, observability
- Docs: `packages/activemq/docs/README.md`

### ActiveMQ OpenTelemetry Assets
- Name: `activemq_otel`
- Path: `packages/activemq_otel/`
- Description: ActiveMQ Assets for OpenTelemetry Collector
- Version: 0.1.0
- Categories: observability, message_queue, opentelemetry
- Docs: `packages/activemq_otel/docs/README.md`

### Admin By Request EPM
- Name: `admin_by_request_epm`
- Path: `packages/admin_by_request_epm/`
- Description: Collect logs from Admin By Request EPM with Elastic Agent.
- Version: 1.2.0
- Categories: security
- Docs: `packages/admin_by_request_epm/docs/README.md`

### Agentless Hello World
- Name: `agentless_hello_world`
- Path: `packages/agentless_hello_world/`
- Description: A sample integration to exercise the Agentless infrastructure by fetching https://epr.elastic.co every minute. Optionally includes a counter data stream for high-rate mock metric ingestion testing.
- Version: 0.4.0
- Categories: observability
- Docs: `packages/agentless_hello_world/docs/README.md`

### Airflow
- Name: `airflow`
- Path: `packages/airflow/`
- Description: Airflow Integration.
- Version: 1.0.0
- Categories: observability
- Docs: `packages/airflow/docs/README.md`

### Airflow OpenTelemetry
- Name: `airflow_otel`
- Path: `packages/airflow_otel/`
- Description: Airflow OpenTelemetry Integration.
- Version: 0.1.0
- Categories: opentelemetry, observability, process_manager
- Docs: `packages/airflow_otel/docs/README.md`

### Airlock Digital
- Name: `airlock_digital`
- Path: `packages/airlock_digital/`
- Description: Collect logs from Airlock Digital with Elastic Agent.
- Version: 0.3.0
- Categories: security
- Docs: `packages/airlock_digital/docs/README.md`

### Akamai
- Name: `akamai`
- Path: `packages/akamai/`
- Description: Collect logs from Akamai with Elastic Agent.
- Version: 3.1.1
- Docs: `packages/akamai/docs/README.md`

### Amazon Security Lake
- Name: `amazon_security_lake`
- Path: `packages/amazon_security_lake/`
- Description: Collect logs from Amazon Security Lake with Elastic Agent.
- Version: 2.8.2
- Categories: aws, security
- Docs: `packages/amazon_security_lake/docs/README.md`

### Apache HTTP Server
- Name: `apache`
- Path: `packages/apache/`
- Description: Collect logs and metrics from Apache servers with Elastic Agent.
- Version: 3.0.0
- Categories: web, observability
- Docs: `packages/apache/docs/README.md`

### Apache HTTP Server OpenTelemetry Input Package
- Name: `apache_input_otel`
- Path: `packages/apache_input_otel/`
- Description: Collect Apache HTTP Server status metrics using OpenTelemetry Collector
- Version: 0.1.0
- Categories: web, observability, opentelemetry
- Docs: `packages/apache_input_otel/docs/README.md`

### Apache OpenTelemetry Assets
- Name: `apache_otel`
- Path: `packages/apache_otel/`
- Description: Apache HTTP Server Assets for OpenTelemetry Collector
- Version: 0.3.0
- Categories: observability, web, opentelemetry
- Docs: `packages/apache_otel/docs/README.md`

### Apache Spark
- Name: `apache_spark`
- Path: `packages/apache_spark/`
- Description: Collect metrics from Apache Spark with Elastic Agent.
- Version: 1.5.0
- Categories: observability, analytics_engine
- Docs: `packages/apache_spark/docs/README.md`

### Apache Tomcat
- Name: `apache_tomcat`
- Path: `packages/apache_tomcat/`
- Description: Collect and parse logs and metrics from Apache Tomcat servers with Elastic Agent.
- Version: 1.13.0
- Categories: web, observability
- Docs: `packages/apache_tomcat/docs/README.md`

### Apache Tomcat OpenTelemetry Assets
- Name: `apache_tomcat_otel`
- Path: `packages/apache_tomcat_otel/`
- Description: Apache Tomcat Assets from OpenTelemetry Collector
- Version: 0.1.0
- Categories: observability, web, application_observability, opentelemetry
- Docs: `packages/apache_tomcat_otel/docs/README.md`

### Elastic APM
- Name: `apm`
- Path: `packages/apm/`
- Description: Monitor, detect, and diagnose complex application performance issues.
- Version: 9.1.0-preview-1747764883
- Categories: elastic_stack, monitoring
- Docs: `packages/apm/docs/README.md`

### Arista NG Firewall
- Name: `arista_ngfw`
- Path: `packages/arista_ngfw/`
- Description: Collect logs and metrics from Arista NG Firewall.
- Version: 1.6.2
- Categories: network
- Docs: `packages/arista_ngfw/docs/README.md`

### Armis
- Name: `armis`
- Path: `packages/armis/`
- Description: Collect logs from Armis with Elastic Agent.
- Version: 0.4.1
- Categories: security
- Docs: `packages/armis/docs/README.md`

### Atlassian Bitbucket
- Name: `atlassian_bitbucket`
- Path: `packages/atlassian_bitbucket/`
- Description: Collect logs from Atlassian Bitbucket with Elastic Agent.
- Version: 2.6.0
- Categories: security, productivity_security
- Docs: `packages/atlassian_bitbucket/docs/README.md`

### Atlassian Confluence
- Name: `atlassian_confluence`
- Path: `packages/atlassian_confluence/`
- Description: Collect logs from Atlassian Confluence with Elastic Agent.
- Version: 1.30.0
- Categories: security, productivity_security
- Docs: `packages/atlassian_confluence/docs/README.md`

### Atlassian Jira
- Name: `atlassian_jira`
- Path: `packages/atlassian_jira/`
- Description: Collect logs from Atlassian Jira with Elastic Agent.
- Version: 1.31.0
- Categories: security, productivity_security
- Docs: `packages/atlassian_jira/docs/README.md`

### Auditd Logs
- Name: `auditd`
- Path: `packages/auditd/`
- Description: Collect logs from Linux audit daemon with Elastic Agent.
- Version: 3.22.2
- Categories: security, auditd
- Docs: `packages/auditd/docs/README.md`

### Auditd Manager
- Name: `auditd_manager`
- Path: `packages/auditd_manager/`
- Description: The Auditd Manager Integration receives audit events from the Linux Audit Framework that is a part of the Linux kernel.
- Version: 1.20.0
- Categories: security, auditd
- Docs: `packages/auditd_manager/docs/README.md`

### Auth0
- Name: `auth0`
- Path: `packages/auth0/`
- Description: Collect logs from Auth0 with Elastic Agent.
- Version: 1.23.1
- Categories: security, iam
- Docs: `packages/auth0/docs/README.md`

### authentik
- Name: `authentik`
- Path: `packages/authentik/`
- Description: Collect logs from authentik with Elastic Agent.
- Version: 1.9.0
- Categories: security
- Docs: `packages/authentik/docs/README.md`

### AWS
- Name: `aws`
- Path: `packages/aws/`
- Description: Collect logs and metrics from Amazon Web Services (AWS) with Elastic Agent.
- Version: 6.14.1
- Categories: aws, cloud
- Docs: `packages/aws/docs/README.md`

### Amazon Bedrock
- Name: `aws_bedrock`
- Path: `packages/aws_bedrock/`
- Description: Collect Amazon Bedrock model invocation logs and runtime metrics with Elastic Agent.
- Version: 1.5.1
- Categories: aws, cloud, observability, security
- Docs: `packages/aws_bedrock/docs/README.md`

### Amazon Bedrock AgentCore
- Name: `aws_bedrock_agentcore`
- Path: `packages/aws_bedrock_agentcore/`
- Description: Collect Amazon Bedrock AgentCore's Agent runtime, Gateway, Identity, Memory, Browser Tools and Code Interpreter metrics and logs using Elastic Agent
- Version: 0.7.0
- Categories: aws, cloud, observability
- Docs: `packages/aws_bedrock_agentcore/docs/README.md`

### AWS Cost and Usage Report (CUR 2.0)
- Name: `aws_billing`
- Path: `packages/aws_billing/`
- Description: Collect AWS CUR 2.0 billing data from S3 with Elastic Agent.
- Version: 0.2.1
- Categories: aws, cloud, observability
- Docs: `packages/aws_billing/docs/README.md`

### AWS CloudTrail Logs OpenTelemetry Assets
- Name: `aws_cloudtrail_otel`
- Path: `packages/aws_cloudtrail_otel/`
- Description: AWS CloudTrail Logs OpenTelemetry Assets
- Version: 0.1.0
- Categories: aws, cloud, web, observability, opentelemetry
- Docs: `packages/aws_cloudtrail_otel/docs/README.md`

### AWS ELB OpenTelemetry Assets
- Name: `aws_elb_otel`
- Path: `packages/aws_elb_otel/`
- Description: AWS ELB logs for OpenTelemetry Collector
- Version: 0.1.1
- Categories: aws, cloud, web, observability, opentelemetry
- Docs: `packages/aws_elb_otel/docs/README.md`

### Custom AWS Logs
- Name: `aws_logs`
- Path: `packages/aws_logs/`
- Description: Collect raw logs from AWS S3 or CloudWatch with Elastic Agent.
- Version: 1.8.3
- Categories: cloud, observability, custom, aws
- Docs: `packages/aws_logs/docs/README.md`

### Amazon MQ
- Name: `aws_mq`
- Path: `packages/aws_mq/`
- Description: Collect Amazon MQ metrics and logs with Elastic Agent
- Version: 1.0.0
- Categories: aws, cloud, message_queue, observability
- Docs: `packages/aws_mq/docs/README.md`

### AWS Security Hub
- Name: `aws_securityhub`
- Path: `packages/aws_securityhub/`
- Description: Collect logs from AWS Security Hub with Elastic Agent.
- Version: 1.0.0
- Categories: aws, security, cloudsecurity_cdr, vulnerability_workflow
- Docs: `packages/aws_securityhub/docs/README.md`

### AWS VPC Flow Logs OpenTelemetry Assets
- Name: `aws_vpcflow_otel`
- Path: `packages/aws_vpcflow_otel/`
- Description: AWS VPC Flow Logs OpenTelemetry Assets
- Version: 0.2.0
- Categories: aws, cloud, web, observability, opentelemetry
- Docs: `packages/aws_vpcflow_otel/docs/README.md`

### AWS WAF Logs OpenTelemetry Assets
- Name: `aws_waf_otel`
- Path: `packages/aws_waf_otel/`
- Description: AWS WAF Logs OpenTelemetry Assets
- Version: 0.1.0
- Categories: aws, cloud, web, observability, opentelemetry, security, web_application_firewall
- Docs: `packages/aws_waf_otel/docs/README.md`

### AWS Fargate (for ECS clusters)
- Name: `awsfargate`
- Path: `packages/awsfargate/`
- Description: Collects metrics from containers and tasks running on Amazon ECS clusters with Elastic Agent.
- Version: 1.3.0
- Categories: cloud, observability, aws
- Docs: `packages/awsfargate/docs/README.md`

### Amazon Data Firehose
- Name: `awsfirehose`
- Path: `packages/awsfirehose/`
- Description: Stream logs and metrics from Amazon Data Firehose into Elastic Cloud.
- Version: 1.9.1
- Categories: cloud, observability, aws
- Docs: `packages/awsfirehose/docs/README.md`

### Azure Logs
- Name: `azure`
- Path: `packages/azure/`
- Description: This Elastic integration collects logs from Azure
- Version: 1.36.1
- Categories: cloud, azure, observability
- Docs: `packages/azure/docs/README.md`

### Microsoft Foundry
- Name: `azure_ai_foundry`
- Path: `packages/azure_ai_foundry/`
- Description: Collects Microsoft Foundry logs and metrics
- Version: 0.9.1
- Categories: azure, cloud, observability
- Docs: `packages/azure_ai_foundry/docs/README.md`

### Azure App Service
- Name: `azure_app_service`
- Path: `packages/azure_app_service/`
- Description: Collect logs from Azure App Service with Elastic Agent.
- Version: 1.1.0
- Categories: azure, cloud, observability
- Docs: `packages/azure_app_service/docs/README.md`

### Azure Application Insights Metrics Overview
- Name: `azure_application_insights`
- Path: `packages/azure_application_insights/`
- Description: Collect application insights metrics from Azure Monitor with Elastic Agent.
- Version: 1.11.0
- Categories: azure, cloud, observability
- Docs: `packages/azure_application_insights/docs/README.md`

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

### Azure Frontdoor
- Name: `azure_frontdoor`
- Path: `packages/azure_frontdoor/`
- Description: This Elastic integration collects logs from Azure Frontdoor.
- Version: 2.3.0
- Categories: azure, cloud, network
- Docs: `packages/azure_frontdoor/docs/README.md`

### Azure Functions
- Name: `azure_functions`
- Path: `packages/azure_functions/`
- Description: Get metrics and logs from Azure Functions
- Version: 0.12.0
- Categories: azure, cloud, observability
- Docs: `packages/azure_functions/docs/README.md`

### Custom Azure Logs
- Name: `azure_logs`
- Path: `packages/azure_logs/`
- Description: Collect log events from Azure Event Hubs with Elastic Agent
- Version: 0.6.0
- Categories: azure, custom, observability
- Docs: `packages/azure_logs/docs/README.md`

### Azure Resource Metrics
- Name: `azure_metrics`
- Path: `packages/azure_metrics/`
- Description: Collect metrics from Azure resources with Elastic Agent.
- Version: 1.11.1
- Categories: cloud, observability, azure, custom
- Docs: `packages/azure_metrics/docs/README.md`

### Azure Network Watcher NSG
- Name: `azure_network_watcher_nsg`
- Path: `packages/azure_network_watcher_nsg/`
- Description: Collect logs from Azure Network Watcher NSG with Elastic Agent.
- Version: 1.5.1
- Categories: cloud, azure, security
- Docs: `packages/azure_network_watcher_nsg/docs/README.md`

### Azure Network Watcher VNet
- Name: `azure_network_watcher_vnet`
- Path: `packages/azure_network_watcher_vnet/`
- Description: Collect logs from Azure Network Watcher VNet with Elastic Agent.
- Version: 1.6.0
- Categories: cloud, azure, security
- Docs: `packages/azure_network_watcher_vnet/docs/README.md`

### Azure OpenAI
- Name: `azure_openai`
- Path: `packages/azure_openai/`
- Description: Collects Azure OpenAI Logs and Metrics
- Version: 1.11.0
- Categories: azure, cloud, observability
- Docs: `packages/azure_openai/docs/README.md`

### Barracuda Web Application Firewall
- Name: `barracuda`
- Path: `packages/barracuda/`
- Description: Collect logs from Barracuda Web Application Firewall with Elastic Agent.
- Version: 1.18.0
- Categories: network, security, web_application_firewall
- Docs: `packages/barracuda/docs/README.md`

### Barracuda CloudGen Firewall Logs
- Name: `barracuda_cloudgen_firewall`
- Path: `packages/barracuda_cloudgen_firewall/`
- Description: Collect logs from Barracuda CloudGen Firewall devices with Elastic Agent.
- Version: 1.16.0
- Docs: `packages/barracuda_cloudgen_firewall/docs/README.md`

### BBOT (Bighuge BLS OSINT Tool)
- Name: `bbot`
- Path: `packages/bbot/`
- Description: BBOT is a recursive internet scanner inspired by Spiderfoot, but designed to be faster, more reliable, and friendlier to pentesters, bug bounty hunters, and developers. 
- Version: 1.4.0
- Categories: security
- Docs: `packages/bbot/docs/README.md`

### Network Beaconing Identification
- Name: `beaconing`
- Path: `packages/beaconing/`
- Description: Package to identify beaconing activity in your network events.
- Version: 1.6.0
- Categories: security, advanced_analytics_ueba
- Docs: `packages/beaconing/docs/README.md`

### Beat
- Name: `beat`
- Path: `packages/beat/`
- Description: Beat Integration
- Version: 1.0.1
- Docs: `packages/beat/docs/README.md`

### Beelzebub
- Name: `beelzebub`
- Path: `packages/beelzebub/`
- Description: Beelzebub is an advanced honeypot framework designed to provide a highly secure environment for detecting and analyzing cyber attacks. It offers a low code approach for easy implementation and uses AI to mimic the behavior of a high-interaction honeypot.
- Version: 0.4.0
- Categories: network, security
- Docs: `packages/beelzebub/docs/README.md`

### BeyondInsight and Password Safe
- Name: `beyondinsight_password_safe`
- Path: `packages/beyondinsight_password_safe/`
- Description: Ingest privileged access management (PAM) data from BeyondTrust's BeyondInsight PAM Reporting Platform and Password Safe, using Elastic Agent.
- Version: 1.1.0
- Categories: security
- Docs: `packages/beyondinsight_password_safe/docs/README.md`

### BeyondTrust PRA
- Name: `beyondtrust_pra`
- Path: `packages/beyondtrust_pra/`
- Description: Collect logs from BeyondTrust PRA with Elastic Agent.
- Version: 0.4.0
- Categories: security
- Docs: `packages/beyondtrust_pra/docs/README.md`

### BitDefender
- Name: `bitdefender`
- Path: `packages/bitdefender/`
- Description: Ingest BitDefender GravityZone logs and data
- Version: 2.9.0
- Categories: security
- Docs: `packages/bitdefender/docs/README.md`

### Bitsight
- Name: `bitsight`
- Path: `packages/bitsight/`
- Description: Ingest data from the Bitsight API.
- Version: 0.2.0
- Categories: custom, security
- Docs: `packages/bitsight/docs/README.md`

### Bitwarden
- Name: `bitwarden`
- Path: `packages/bitwarden/`
- Description: Collect logs from Bitwarden with Elastic Agent.
- Version: 1.19.0
- Categories: security, credential_management
- Docs: `packages/bitwarden/docs/README.md`

### blacklens.io
- Name: `blacklens`
- Path: `packages/blacklens/`
- Description: Collect logs from blacklens.io with Elastic Agent
- Version: 1.0.1
- Categories: security
- Docs: `packages/blacklens/docs/README.md`

### Blue Coat Director Logs (Deprecated)
- Name: `bluecoat`
- Path: `packages/bluecoat/`
- Description: Deprecated. Director is no longer supported.
- Version: 0.18.1
- Docs: `packages/bluecoat/docs/README.md`

### Box Events
- Name: `box_events`
- Path: `packages/box_events/`
- Description: Collect logs from Box with Elastic Agent
- Version: 3.1.2
- Categories: security, productivity_security
- Docs: `packages/box_events/docs/README.md`

### Canva
- Name: `canva`
- Path: `packages/canva/`
- Description: Collect logs from Canva with Elastic Agent.
- Version: 1.0.0
- Categories: security, productivity
- Docs: `packages/canva/docs/README.md`

### VMware Carbon Black Cloud
- Name: `carbon_black_cloud`
- Path: `packages/carbon_black_cloud/`
- Description: Collect logs from VMWare Carbon Black Cloud with Elastic Agent.
- Version: 4.2.0
- Categories: security, edr_xdr
- Docs: `packages/carbon_black_cloud/docs/README.md`

### VMware Carbon Black EDR
- Name: `carbonblack_edr`
- Path: `packages/carbonblack_edr/`
- Description: Collect logs from VMware Carbon Black EDR with Elastic Agent.
- Version: 1.21.0
- Docs: `packages/carbonblack_edr/docs/README.md`

### Cassandra
- Name: `cassandra`
- Path: `packages/cassandra/`
- Description: This Elastic integration collects logs and metrics from cassandra.
- Version: 1.20.0
- Categories: datastore, observability
- Docs: `packages/cassandra/docs/README.md`

### Cassandra OpenTelemetry Assets
- Name: `cassandra_otel`
- Path: `packages/cassandra_otel/`
- Description: Apache Cassandra Assets from OpenTelemetry Collector
- Version: 0.1.0
- Categories: observability, datastore, opentelemetry
- Docs: `packages/cassandra_otel/docs/README.md`

### Common Event Format (CEF)
- Name: `cef`
- Path: `packages/cef/`
- Description: Collect logs from CEF Logs with Elastic Agent.
- Version: 2.23.1
- Categories: security
- Docs: `packages/cef/docs/README.md`

### Custom API using Common Expression Language
- Name: `cel`
- Path: `packages/cel/`
- Description: Collect custom events from an API with Elastic agent
- Version: 1.19.0
- Categories: custom
- Docs: `packages/cel/docs/README.md`

### Ceph
- Name: `ceph`
- Path: `packages/ceph/`
- Description: This Elastic integration collects metrics from Ceph instance.
- Version: 1.9.0
- Categories: datastore, os_system, observability
- Docs: `packages/ceph/docs/README.md`

### Check Point
- Name: `checkpoint`
- Path: `packages/checkpoint/`
- Description: Collect logs from Check Point with Elastic Agent.
- Version: 1.45.5
- Docs: `packages/checkpoint/docs/README.md`

### Check Point Harmony Email & Collaboration
- Name: `checkpoint_email`
- Path: `packages/checkpoint_email/`
- Description: Collect logs from Check Point Harmony Email & Collaboration with Elastic Agent.
- Version: 1.4.0
- Categories: security
- Docs: `packages/checkpoint_email/docs/README.md`

### Check Point Harmony Endpoint
- Name: `checkpoint_harmony_endpoint`
- Path: `packages/checkpoint_harmony_endpoint/`
- Description: Collect logs from Check Point Harmony Endpoint
- Version: 1.2.0
- Categories: security
- Docs: `packages/checkpoint_harmony_endpoint/docs/README.md`

### CISA Known Exploited Vulnerabilities
- Name: `cisa_kevs`
- Path: `packages/cisa_kevs/`
- Description: This package allows the ingest of known exploited vulnerabilities according to the Cybersecurity and Infrastructure Security Agency of the United States of America. This information could be used to enrich or track exisiting vulnerabilities that are known to be exploited in the wild.
- Version: 1.8.0
- Categories: security
- Docs: `packages/cisa_kevs/docs/README.md`

### Cisco Aironet
- Name: `cisco_aironet`
- Path: `packages/cisco_aironet/`
- Description: Integration for Cisco Aironet WLC Logs
- Version: 1.20.0
- Categories: security, network
- Docs: `packages/cisco_aironet/docs/README.md`

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

### Cisco FTD
- Name: `cisco_ftd`
- Path: `packages/cisco_ftd/`
- Description: Collect logs from Cisco FTD with Elastic Agent.
- Version: 3.13.3
- Categories: network, security, firewall_security
- Docs: `packages/cisco_ftd/docs/README.md`

### Cisco IOS
- Name: `cisco_ios`
- Path: `packages/cisco_ios/`
- Description: Collect logs from Cisco IOS with Elastic Agent.
- Version: 1.35.3
- Categories: network, security
- Docs: `packages/cisco_ios/docs/README.md`

### Cisco ISE
- Name: `cisco_ise`
- Path: `packages/cisco_ise/`
- Description: Collect logs from Cisco ISE with Elastic Agent.
- Version: 1.32.3
- Categories: security, network
- Docs: `packages/cisco_ise/docs/README.md`

### Cisco Meraki
- Name: `cisco_meraki`
- Path: `packages/cisco_meraki/`
- Description: Collect logs from Cisco Meraki with Elastic Agent.
- Version: 1.31.1
- Categories: network, security
- Docs: `packages/cisco_meraki/docs/README.md`

### Cisco Meraki Metrics
- Name: `cisco_meraki_metrics`
- Path: `packages/cisco_meraki_metrics/`
- Description: Collect metrics from Cisco Meraki with Elastic Agent.
- Version: 0.4.3
- Categories: network, observability, security
- Docs: `packages/cisco_meraki_metrics/docs/README.md`

### Cisco Nexus
- Name: `cisco_nexus`
- Path: `packages/cisco_nexus/`
- Description: Collect logs from Cisco Nexus with Elastic Agent.
- Version: 1.6.0
- Categories: network, security
- Docs: `packages/cisco_nexus/docs/README.md`

### Cisco Secure Email Gateway
- Name: `cisco_secure_email_gateway`
- Path: `packages/cisco_secure_email_gateway/`
- Description: Collect logs from Cisco Secure Email Gateway with Elastic Agent.
- Version: 1.29.1
- Categories: security, network, email_security
- Docs: `packages/cisco_secure_email_gateway/docs/README.md`

### Cisco Secure Endpoint
- Name: `cisco_secure_endpoint`
- Path: `packages/cisco_secure_endpoint/`
- Description: Collect logs from Cisco Secure Endpoint (AMP) with Elastic Agent.
- Version: 2.33.1
- Categories: security, edr_xdr
- Docs: `packages/cisco_secure_endpoint/docs/README.md`

### Cisco Umbrella
- Name: `cisco_umbrella`
- Path: `packages/cisco_umbrella/`
- Description: Collect logs from Cisco Umbrella with Elastic Agent.
- Version: 1.33.1
- Categories: network, security, dns_security
- Docs: `packages/cisco_umbrella/docs/README.md`

### Citrix ADC
- Name: `citrix_adc`
- Path: `packages/citrix_adc/`
- Description: This Elastic integration collects logs and metrics from Citrix ADC product.
- Version: 1.18.5
- Categories: observability, network
- Docs: `packages/citrix_adc/docs/README.md`

### Citrix Web App Firewall
- Name: `citrix_waf`
- Path: `packages/citrix_waf/`
- Description: Ingest events from Citrix Systems Web App Firewall.
- Version: 1.20.0
- Categories: network, security, web_application_firewall
- Docs: `packages/citrix_waf/docs/README.md`

### Claroty CTD
- Name: `claroty_ctd`
- Path: `packages/claroty_ctd/`
- Description: Collect logs from Claroty CTD using Elastic Agent.
- Version: 1.2.0
- Categories: security
- Docs: `packages/claroty_ctd/docs/README.md`

### Claroty xDome
- Name: `claroty_xdome`
- Path: `packages/claroty_xdome/`
- Description: Collect logs from Claroty xDome with Elastic Agent.
- Version: 1.0.2
- Categories: security, vulnerability_management
- Docs: `packages/claroty_xdome/docs/README.md`

### Cloud Asset Discovery
- Name: `cloud_asset_inventory`
- Path: `packages/cloud_asset_inventory/`
- Description: Discover and Create Cloud Assets Discovery
- Version: 1.5.0
- Categories: security, asset_inventory, cloudsecurity_cdr
- Docs: `packages/cloud_asset_inventory/docs/README.md`

### Defend for Containers (BETA)
- Name: `cloud_defend`
- Path: `packages/cloud_defend/`
- Description: Elastic Defend for Containers (BETA) provides cloud-native runtime protections for containerized environments.
- Version: 1.4.1-beta
- Categories: containers, kubernetes
- Docs: `packages/cloud_defend/docs/README.md`

### Security Posture Management
- Name: `cloud_security_posture`
- Path: `packages/cloud_security_posture/`
- Description: Identify & remediate configuration risks in your Cloud infrastructure
- Version: 3.3.0
- Categories: security, cloudsecurity_cdr, misconfiguration_workflow, vulnerability_workflow
- Docs: `packages/cloud_security_posture/docs/README.md`

### Cloudflare
- Name: `cloudflare`
- Path: `packages/cloudflare/`
- Description: Collect logs from Cloudflare with Elastic Agent.
- Version: 2.33.0
- Docs: `packages/cloudflare/docs/README.md`

### Cloudflare Logpush
- Name: `cloudflare_logpush`
- Path: `packages/cloudflare_logpush/`
- Description: Collect and parse logs from Cloudflare API with Elastic Agent.
- Version: 1.44.0
- Categories: security, network, cdn_security
- Docs: `packages/cloudflare_logpush/docs/README.md`

### CockroachDB Metrics
- Name: `cockroachdb`
- Path: `packages/cockroachdb/`
- Description: Collect metrics from CockroachDB servers with Elastic Agent.
- Version: 1.13.1
- Categories: observability, datastore
- Docs: `packages/cockroachdb/docs/README.md`

### CockroachDB OpenTelemetry Assets
- Name: `cockroachdb_otel`
- Path: `packages/cockroachdb_otel/`
- Description: CockroachDB Assets from OpenTelemetry Collector
- Version: 0.1.0
- Categories: observability, datastore, opentelemetry
- Docs: `packages/cockroachdb_otel/docs/README.md`

### Containerd
- Name: `containerd`
- Path: `packages/containerd/`
- Description: Collect metrics from containerd containers.
- Version: 0.6.0
- Categories: observability, containers
- Docs: `packages/containerd/docs/README.md`

### CoreDNS
- Name: `coredns`
- Path: `packages/coredns/`
- Description: Collect logs from CoreDNS instances with Elastic Agent.
- Version: 0.10.0
- Categories: observability
- Docs: `packages/coredns/docs/README.md`

### Corelight
- Name: `corelight`
- Path: `packages/corelight/`
- Description: Collect logs from Corelight with Elastic Agent.
- Version: 1.1.0
- Categories: security, dns_security, network, network_security, vpn_security
- Docs: `packages/corelight/docs/README.md`

### Couchbase
- Name: `couchbase`
- Path: `packages/couchbase/`
- Description: Collect metrics from Couchbase databases with Elastic Agent.
- Version: 1.9.1
- Categories: datastore, observability
- Docs: `packages/couchbase/docs/README.md`

### CouchDB
- Name: `couchdb`
- Path: `packages/couchdb/`
- Description: Collect metrics from CouchDB with Elastic Agent.
- Version: 1.5.1
- Categories: datastore, observability
- Docs: `packages/couchdb/docs/README.md`

### CouchDB OpenTelemetry Assets
- Name: `couchdb_otel`
- Path: `packages/couchdb_otel/`
- Description: CouchDB Assets for OpenTelemetry Collector
- Version: 0.1.0
- Categories: observability, datastore, opentelemetry
- Docs: `packages/couchdb_otel/docs/README.md`

### Cribl
- Name: `cribl`
- Path: `packages/cribl/`
- Description: Stream logs from Cribl into Elastic.
- Version: 1.1.1
- Categories: custom
- Docs: `packages/cribl/docs/README.md`

### CrowdStrike
- Name: `crowdstrike`
- Path: `packages/crowdstrike/`
- Description: Collect logs from Crowdstrike with Elastic Agent.
- Version: 3.16.1
- Docs: `packages/crowdstrike/docs/README.md`

### CyberArk EPM
- Name: `cyberark_epm`
- Path: `packages/cyberark_epm/`
- Description: Collect logs from CyberArk EPM with Elastic Agent.
- Version: 1.3.3
- Categories: security
- Docs: `packages/cyberark_epm/docs/README.md`

### Cyberark Privileged Threat Analytics
- Name: `cyberark_pta`
- Path: `packages/cyberark_pta/`
- Description: Collect security logs from Cyberark PTA integration.
- Version: 1.15.0
- Docs: `packages/cyberark_pta/docs/README.md`

### CyberArk Privileged Access Security
- Name: `cyberarkpas`
- Path: `packages/cyberarkpas/`
- Description: Collect logs from CyberArk Privileged Access Security with Elastic Agent.
- Version: 2.28.0
- Docs: `packages/cyberarkpas/docs/README.md`

### Cybereason
- Name: `cybereason`
- Path: `packages/cybereason/`
- Description: Collect logs from Cybereason with Elastic Agent.
- Version: 1.5.0
- Categories: security, edr_xdr
- Docs: `packages/cybereason/docs/README.md`

### Cyera
- Name: `cyera`
- Path: `packages/cyera/`
- Description: Collect logs from Cyera with Elastic Agent.
- Version: 0.6.0
- Categories: security
- Docs: `packages/cyera/docs/README.md`

### CylanceProtect Logs (Deprecated)
- Name: `cylance`
- Path: `packages/cylance/`
- Description: Collect logs from CylanceProtect devices with Elastic Agent.
- Version: 0.24.0
- Docs: `packages/cylance/docs/README.md`

### Darktrace
- Name: `darktrace`
- Path: `packages/darktrace/`
- Description: Collect logs from Darktrace with Elastic Agent.
- Version: 2.0.0
- Categories: security, network_security
- Docs: `packages/darktrace/docs/README.md`

### Data Exfiltration Detection
- Name: `ded`
- Path: `packages/ded/`
- Description: ML package to detect data exfiltration in your network and file data.
- Version: 3.1.0
- Categories: security, network, advanced_analytics_ueba
- Docs: `packages/ded/docs/README.md`

### Domain Generation Algorithm Detection
- Name: `dga`
- Path: `packages/dga/`
- Description: ML solution package to detect domain generation algorithm (DGA) activity in your network data.
- Version: 3.0.0
- Categories: security, network_security, advanced_analytics_ueba
- Docs: `packages/dga/docs/README.md`

### Digital Guardian
- Name: `digital_guardian`
- Path: `packages/digital_guardian/`
- Description: Collect logs from Digital Guardian with Elastic Agent.
- Version: 1.8.0
- Categories: security, network
- Docs: `packages/digital_guardian/docs/README.md`

### Docker
- Name: `docker`
- Path: `packages/docker/`
- Description: Collect metrics and logs from Docker instances with Elastic Agent.
- Version: 2.15.1
- Categories: observability, containers
- Docs: `packages/docker/docs/README.md`

### Docker OpenTelemetry Input Package
- Name: `docker_input_otel`
- Path: `packages/docker_input_otel/`
- Description: Collect Docker container metrics using OpenTelemetry Collector
- Version: 0.1.0
- Categories: containers, monitoring, observability, opentelemetry
- Docs: `packages/docker_input_otel/docs/README.md`

### Docker OpenTelemetry Assets
- Name: `docker_otel`
- Path: `packages/docker_otel/`
- Description: Utilise the pre-built dashboard for OTel-native metrics of Docker hosts and their running containers
- Version: 0.2.0
- Categories: containers, monitoring
- Docs: `packages/docker_otel/docs/README.md`

### Elastic Cloud Enterprise
- Name: `ece`
- Path: `packages/ece/`
- Description: This is a helpful integration for all customers using ECE and need to track the events generated within the ECE admin UI or against the ECE API.
- Version: 0.0.2
- Categories: elastic_stack
- Docs: `packages/ece/docs/README.md`

### Elastic Agent
- Name: `elastic_agent`
- Path: `packages/elastic_agent/`
- Description: Collect logs and metrics from Elastic Agents.
- Version: 2.8.0
- Docs: `packages/elastic_agent/docs/README.md`

### Elastic Connectors
- Name: `elastic_connectors`
- Path: `packages/elastic_connectors/`
- Description: Sync data from source to the Elasticsearch index.
- Version: 1.0.3
- Categories: connector
- Docs: `packages/elastic_connectors/docs/README.md`

### Elastic Package Registry
- Name: `elastic_package_registry`
- Path: `packages/elastic_package_registry/`
- Description: Collect metrics from a Elastic Package Registry instance
- Version: 0.3.1
- Categories: elastic_stack
- Docs: `packages/elastic_package_registry/docs/README.md`

### Elastic Security
- Name: `elastic_security`
- Path: `packages/elastic_security/`
- Description: Collect logs from Elastic Instance with Elastic Agent.
- Version: 0.4.0
- Categories: security, siem
- Docs: `packages/elastic_security/docs/README.md`

### Elasticsearch
- Name: `elasticsearch`
- Path: `packages/elasticsearch/`
- Description: Elasticsearch Integration
- Version: 1.20.2
- Docs: `packages/elasticsearch/docs/README.md`

### Endace
- Name: `endace`
- Path: `packages/endace/`
- Description: This Endace integration configures Network Packet Capture for flow generation and adds a pivot field to your Endace platform.
- Version: 0.2.0
- Categories: aws, cloud, custom, network
- Docs: `packages/endace/docs/README.md`

### Enterprise Search
- Name: `enterprisesearch`
- Path: `packages/enterprisesearch/`
- Description: Enterprise Search Integration
- Version: 1.0.1
- Docs: `packages/enterprisesearch/docs/README.md`

### Active Directory Entity Analytics
- Name: `entityanalytics_ad`
- Path: `packages/entityanalytics_ad/`
- Description: Collect User Identities from Active Directory Entity with Elastic Agent.
- Version: 0.18.0
- Categories: security
- Docs: `packages/entityanalytics_ad/docs/README.md`

### Microsoft Entra ID Entity Analytics
- Name: `entityanalytics_entra_id`
- Path: `packages/entityanalytics_entra_id/`
- Description: Collect identities from Microsoft Entra ID (formerly Azure Active Directory) with Elastic Agent.
- Version: 1.9.1
- Categories: azure, cloud, security
- Docs: `packages/entityanalytics_entra_id/docs/README.md`

### Okta Entity Analytics
- Name: `entityanalytics_okta`
- Path: `packages/entityanalytics_okta/`
- Description: Collect Identities from Okta with Elastic Agent.
- Version: 3.0.0
- Categories: security
- Docs: `packages/entityanalytics_okta/docs/README.md`

### Entro
- Name: `entro`
- Path: `packages/entro/`
- Description: Collect logs from Entro with Elastic Agent.
- Version: 0.2.0
- Categories: cloud, security
- Docs: `packages/entro/docs/README.md`

### Envoyproxy
- Name: `envoyproxy`
- Path: `packages/envoyproxy/`
- Description: Envoyproxy Integration
- Version: 0.4.0
- Categories: observability
- Docs: `packages/envoyproxy/docs/README.md`

### Envoyproxy OpenTelemetry assets
- Name: `envoyproxy_otel`
- Path: `packages/envoyproxy_otel/`
- Description: Envoyproxy Assets for OpenTelemetry Collector
- Version: 0.1.0
- Categories: observability, opentelemetry
- Docs: `packages/envoyproxy_otel/docs/README.md`

### ESET PROTECT
- Name: `eset_protect`
- Path: `packages/eset_protect/`
- Description: Collect logs from ESET PROTECT with Elastic Agent.
- Version: 2.2.0
- Categories: security, edr_xdr
- Docs: `packages/eset_protect/docs/README.md`

### Elasticsearch Service Billing
- Name: `ess_billing`
- Path: `packages/ess_billing/`
- Description: Collects billing metrics from Elasticsearch Service billing API
- Version: 1.7.1
- Categories: cloud
- Docs: `packages/ess_billing/docs/README.md`

### etcd
- Name: `etcd`
- Path: `packages/etcd/`
- Description: Collect metrics from etcd instances with Elastic Agent.
- Version: 1.4.1
- Categories: datastore, observability
- Docs: `packages/etcd/docs/README.md`

### etcd OpenTelemetry Assets
- Name: `etcd_otel`
- Path: `packages/etcd_otel/`
- Description: etcd Assets from OpenTelemetry Collector
- Version: 0.1.0
- Categories: observability, datastore, opentelemetry
- Docs: `packages/etcd_otel/docs/README.md`

### ExtraHop
- Name: `extrahop`
- Path: `packages/extrahop/`
- Description: Collect logs from ExtraHop RevealX 360 with Elastic Agent.
- Version: 0.2.1
- Categories: security
- Docs: `packages/extrahop/docs/README.md`

### F5 BIG-IP
- Name: `f5_bigip`
- Path: `packages/f5_bigip/`
- Description: Collect logs from F5 BIG-IP with Elastic Agent.
- Version: 1.27.3
- Categories: security
- Docs: `packages/f5_bigip/docs/README.md`

### Falco
- Name: `falco`
- Path: `packages/falco/`
- Description: Collect events and alerts from Falco using Elastic Agent
- Version: 2.0.2
- Categories: containers, kubernetes, monitoring
- Docs: `packages/falco/docs/README.md`

### File Log OpenTelemetry input
- Name: `filelog_otel`
- Path: `packages/filelog_otel/`
- Description: Tails and parses logs from files using the filelog receiver of the OTel collector.
- Version: 0.2.0
- Categories: custom, custom_logs, opentelemetry
- Docs: `packages/filelog_otel/docs/README.md`

### Custom Logs (Filestream)
- Name: `filestream`
- Path: `packages/filestream/`
- Description: Collect log data using filestream with Elastic Agent.
- Version: 2.5.0
- Categories: custom, custom_logs
- Docs: `packages/filestream/docs/README.md`

### File Integrity Monitoring
- Name: `fim`
- Path: `packages/fim/`
- Description: The File Integrity Monitoring integration reports filesystem changes in real time.
- Version: 1.17.0
- Categories: security
- Docs: `packages/fim/docs/README.md`

### FireEye Network Security
- Name: `fireeye`
- Path: `packages/fireeye/`
- Description: Collect logs from FireEye NX with Elastic Agent.
- Version: 1.27.1
- Categories: network, security
- Docs: `packages/fireeye/docs/README.md`

### First EPSS
- Name: `first_epss`
- Path: `packages/first_epss/`
- Description: Collect exploit prediction score data from the First EPSS API with Elastic Agent.
- Version: 1.2.0
- Categories: security, vulnerability_management
- Docs: `packages/first_epss/docs/README.md`

### Fleet Server
- Name: `fleet_server`
- Path: `packages/fleet_server/`
- Description: Centrally manage Elastic Agents with the Fleet Server integration.
- Version: 1.6.1
- Docs: `packages/fleet_server/docs/README.md`

### Forcepoint Web Security
- Name: `forcepoint_web`
- Path: `packages/forcepoint_web/`
- Description: Forcepoint Web Security
- Version: 1.13.0
- Categories: network, security
- Docs: `packages/forcepoint_web/docs/README.md`

### ForgeRock
- Name: `forgerock`
- Path: `packages/forgerock/`
- Description: Collect audit logs from ForgeRock with Elastic Agent.
- Version: 1.22.0
- Docs: `packages/forgerock/docs/README.md`

### Fortinet FortiClient Logs (Deprecated)
- Name: `fortinet_forticlient`
- Path: `packages/fortinet_forticlient/`
- Description: Deprecated. Fortinet FortiClient Logs is no longer supported.
- Version: 1.12.1
- Docs: `packages/fortinet_forticlient/docs/README.md`

### Fortinet FortiEDR Logs
- Name: `fortinet_fortiedr`
- Path: `packages/fortinet_fortiedr/`
- Description: Collect logs from Fortinet FortiEDR instances with Elastic Agent.
- Version: 1.21.0
- Docs: `packages/fortinet_fortiedr/docs/README.md`

### Fortinet FortiGate Firewall Logs
- Name: `fortinet_fortigate`
- Path: `packages/fortinet_fortigate/`
- Description: Collect logs from Fortinet FortiGate firewalls with Elastic Agent.
- Version: 1.36.5
- Docs: `packages/fortinet_fortigate/docs/README.md`

### Fortinet FortiMail
- Name: `fortinet_fortimail`
- Path: `packages/fortinet_fortimail/`
- Description: Collect logs from Fortinet FortiMail instances with Elastic Agent.
- Version: 2.19.0
- Docs: `packages/fortinet_fortimail/docs/README.md`

### Fortinet FortiManager Logs
- Name: `fortinet_fortimanager`
- Path: `packages/fortinet_fortimanager/`
- Description: Collect logs from Fortinet FortiManager instances with Elastic Agent.
- Version: 2.18.0
- Docs: `packages/fortinet_fortimanager/docs/README.md`

### Fortinet FortiProxy
- Name: `fortinet_fortiproxy`
- Path: `packages/fortinet_fortiproxy/`
- Description: Collect logs from Fortinet FortiProxy with Elastic Agent.
- Version: 1.4.0
- Categories: network
- Docs: `packages/fortinet_fortiproxy/docs/README.md`

### Google Cloud Platform
- Name: `gcp`
- Path: `packages/gcp/`
- Description: Collect logs and metrics from Google Cloud Platform with Elastic Agent.
- Version: 2.49.0
- Categories: google_cloud, cloud, observability
- Docs: `packages/gcp/docs/README.md`

### GCP Audit Logs OpenTelemetry Assets
- Name: `gcp_audit_otel`
- Path: `packages/gcp_audit_otel/`
- Description: GCP Audit Logs OpenTelemetry Assets
- Version: 0.1.0
- Categories: google_cloud, cloud, security, observability, opentelemetry
- Docs: `packages/gcp_audit_otel/docs/README.md`

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

### GCP VPC Flow Logs OpenTelemetry Assets
- Name: `gcp_vpcflow_otel`
- Path: `packages/gcp_vpcflow_otel/`
- Description: GCP VPC Flow Logs OpenTelemetry Assets
- Version: 0.1.0
- Categories: google_cloud, cloud, web, observability, opentelemetry
- Docs: `packages/gcp_vpcflow_otel/docs/README.md`

### Gigamon
- Name: `gigamon`
- Path: `packages/gigamon/`
- Description: Collect logs from Gigamon with Elastic Agent.
- Version: 2.2.0
- Categories: custom, security, network, application_observability
- Docs: `packages/gigamon/docs/README.md`

### GitHub
- Name: `github`
- Path: `packages/github/`
- Description: Collect logs from GitHub with Elastic Agent.
- Version: 2.23.1
- Docs: `packages/github/docs/README.md`

### GitLab
- Name: `gitlab`
- Path: `packages/gitlab/`
- Description: Collect logs from GitLab with Elastic Agent.
- Version: 2.6.0
- Categories: security, productivity_security
- Docs: `packages/gitlab/docs/README.md`

### GoFlow2 logs
- Name: `goflow2`
- Path: `packages/goflow2/`
- Description: Collect logs from goflow2 with Elastic Agent.
- Version: 0.7.0
- Categories: network
- Docs: `packages/goflow2/docs/README.md`

### Golang
- Name: `golang`
- Path: `packages/golang/`
- Description: This Elastic integration collects metrics from Golang applications.
- Version: 1.9.0
- Categories: observability
- Docs: `packages/golang/docs/README.md`

### Custom GCS (Google Cloud Storage) Input
- Name: `google_cloud_storage`
- Path: `packages/google_cloud_storage/`
- Description: Collect JSON data from configured GCS Bucket with Elastic Agent.
- Version: 2.2.0
- Categories: custom, cloud
- Docs: `packages/google_cloud_storage/docs/README.md`

### Google Security Command Center
- Name: `google_scc`
- Path: `packages/google_scc/`
- Description: Collect logs from Google Security Command Center with Elastic Agent.
- Version: 2.4.0
- Categories: google_cloud, security, cloudsecurity_cdr, vulnerability_workflow, misconfiguration_workflow
- Docs: `packages/google_scc/docs/README.md`

### Google SecOps
- Name: `google_secops`
- Path: `packages/google_secops/`
- Description: Collect alerts from Google SecOps with Elastic Agent.
- Version: 1.2.2
- Categories: google_cloud, security, siem
- Docs: `packages/google_secops/docs/README.md`

### Google Workspace
- Name: `google_workspace`
- Path: `packages/google_workspace/`
- Description: Collect logs from Google Workspace with Elastic Agent.
- Version: 3.3.1
- Categories: security, productivity_security
- Docs: `packages/google_workspace/docs/README.md`

### Grafana
- Name: `grafana`
- Path: `packages/grafana/`
- Description: Collect metrics and logs from Grafana instances with Elastic Agent.
- Version: 0.1.0
- Categories: observability, monitoring
- Docs: `packages/grafana/docs/README.md`

### Greenhouse
- Name: `greenhouse`
- Path: `packages/greenhouse/`
- Description: Collect audit logs from Greenhouse ATS with Elastic Agent.
- Version: 0.1.0
- Categories: security
- Docs: `packages/greenhouse/docs/README.md`

### Hadoop
- Name: `hadoop`
- Path: `packages/hadoop/`
- Description: Collect metrics from Apache Hadoop with Elastic Agent.
- Version: 1.9.0
- Categories: datastore, observability, big_data
- Docs: `packages/hadoop/docs/README.md`

### HAProxy
- Name: `haproxy`
- Path: `packages/haproxy/`
- Description: Collect logs and metrics from HAProxy servers with Elastic Agent.
- Version: 1.19.0
- Categories: load_balancer, observability
- Docs: `packages/haproxy/docs/README.md`

### Haproxy OpenTelemetry Assets
- Name: `haproxy_otel`
- Path: `packages/haproxy_otel/`
- Description: Haproxy Assets for OpenTelemetry Collector
- Version: 0.1.0
- Categories: observability, web, opentelemetry
- Docs: `packages/haproxy_otel/docs/README.md`

### Hashicorp Vault
- Name: `hashicorp_vault`
- Path: `packages/hashicorp_vault/`
- Description: Collect logs and metrics from Hashicorp Vault with Elastic Agent.
- Version: 1.30.1
- Categories: security, iam
- Docs: `packages/hashicorp_vault/docs/README.md`

### Bravura Monitor
- Name: `hid_bravura_monitor`
- Path: `packages/hid_bravura_monitor/`
- Description: Collect logs from Bravura Security Fabric with Elastic Agent.
- Version: 1.21.0
- Docs: `packages/hid_bravura_monitor/docs/README.md`

### Host Metrics OpenTelemetry Input Package
- Name: `hostmetrics_input_otel`
- Path: `packages/hostmetrics_input_otel/`
- Description: Collect system metrics using OpenTelemetry Collector
- Version: 0.1.0
- Categories: monitoring, os_system, observability, opentelemetry
- Docs: `packages/hostmetrics_input_otel/docs/README.md`

### HPE Aruba CX
- Name: `hpe_aruba_cx`
- Path: `packages/hpe_aruba_cx/`
- Description: Collect logs from HPE Aruba CX with Elastic Agent
- Version: 0.4.1
- Categories: config_management, network, security
- Docs: `packages/hpe_aruba_cx/docs/README.md`

### Host Traffic Anomalies
- Name: `hta`
- Path: `packages/hta/`
- Description: Prebuilt dashboard for Machine Learning module Security: Host.
- Version: 2.0.0
- Categories: security
- Docs: `packages/hta/docs/README.md`

### Custom HTTP Endpoint Logs
- Name: `http_endpoint`
- Path: `packages/http_endpoint/`
- Description: Collect JSON data from listening HTTP port with Elastic Agent.
- Version: 2.5.0
- Categories: custom, observability
- Docs: `packages/http_endpoint/docs/README.md`

### Simple HTTP Check
- Name: `httpcheck_otel`
- Path: `packages/httpcheck_otel/`
- Description: Perform HTTP checks using the HTTP Check receiver of the OTel Collector.
- Version: 0.1.0
- Categories: monitoring, network, opentelemetry, web
- Docs: `packages/httpcheck_otel/docs/README.md`

### Custom API
- Name: `httpjson`
- Path: `packages/httpjson/`
- Description: Collect custom events from an API endpoint with Elastic agent
- Version: 1.24.0
- Categories: custom
- Docs: `packages/httpjson/docs/README.md`

### IBM QRadar
- Name: `ibm_qradar`
- Path: `packages/ibm_qradar/`
- Description: Collect logs from IBM QRadar with Elastic Agent.
- Version: 0.2.0
- Categories: security, siem
- Docs: `packages/ibm_qradar/docs/README.md`

### IBM MQ
- Name: `ibmmq`
- Path: `packages/ibmmq/`
- Description: Collect logs and metrics from IBM MQ with Elastic Agent.
- Version: 1.9.0
- Categories: message_queue, observability
- Docs: `packages/ibmmq/docs/README.md`

### IBM MQ OpenTelemetry Assets
- Name: `ibmmq_otel`
- Path: `packages/ibmmq_otel/`
- Description: IBM MQ Assets from OpenTelemetry Collector
- Version: 0.1.0
- Categories: message_queue, opentelemetry, observability
- Docs: `packages/ibmmq_otel/docs/README.md`

### IIS
- Name: `iis`
- Path: `packages/iis/`
- Description: Collect logs and metrics from Internet Information Services (IIS) servers with Elastic Agent.
- Version: 1.24.5
- Categories: web, observability
- Docs: `packages/iis/docs/README.md`

### IIS OpenTelemetry Input Package
- Name: `iis_otel_input`
- Path: `packages/iis_input_otel/`
- Description: IIS OpenTelemetry Input Package
- Version: 0.1.0
- Categories: web, observability, opentelemetry
- Docs: `packages/iis_input_otel/docs/README.md`

### IIS OpenTelemetry assets
- Name: `iis_otel`
- Path: `packages/iis_otel/`
- Description: IIS Assets for OpenTelemetry Collector
- Version: 0.3.0
- Categories: web, observability, opentelemetry
- Docs: `packages/iis_otel/docs/README.md`

### Imperva
- Name: `imperva`
- Path: `packages/imperva/`
- Description: Collect logs from Imperva devices with Elastic Agent.
- Version: 1.10.0
- Docs: `packages/imperva/docs/README.md`

### Imperva Cloud WAF
- Name: `imperva_cloud_waf`
- Path: `packages/imperva_cloud_waf/`
- Description: Collect logs from Imperva Cloud WAF with Elastic Agent.
- Version: 1.13.1
- Categories: security
- Docs: `packages/imperva_cloud_waf/docs/README.md`

### InfluxDb
- Name: `influxdb`
- Path: `packages/influxdb/`
- Description: Collect metrics from Influxdb database
- Version: 0.11.0
- Categories: datastore, observability
- Docs: `packages/influxdb/docs/README.md`

### InfluxDb OpenTelemetry Assets
- Name: `influxdb_otel`
- Path: `packages/influxdb_otel/`
- Description: InfluxDb Assets for OpenTelemetry Collector
- Version: 0.1.0
- Categories: datastore, observability, opentelemetry
- Docs: `packages/influxdb_otel/docs/README.md`

### Infoblox BloxOne DDI
- Name: `infoblox_bloxone_ddi`
- Path: `packages/infoblox_bloxone_ddi/`
- Description: Collect logs from Infoblox BloxOne DDI with Elastic Agent.
- Version: 1.22.0
- Categories: security, network, dns_security
- Docs: `packages/infoblox_bloxone_ddi/docs/README.md`

### Infoblox NIOS
- Name: `infoblox_nios`
- Path: `packages/infoblox_nios/`
- Description: Collect logs from Infoblox NIOS with Elastic Agent.
- Version: 2.1.1
- Categories: security, network, dns_security
- Docs: `packages/infoblox_nios/docs/README.md`

### Infoblox Threat Defense
- Name: `infoblox_threat_defense`
- Path: `packages/infoblox_threat_defense/`
- Description: Collect logs from Infoblox Threat Defense with Elastic Agent.
- Version: 0.1.0
- Categories: security
- Docs: `packages/infoblox_threat_defense/docs/README.md`

### Iptables
- Name: `iptables`
- Path: `packages/iptables/`
- Description: Collect logs from Iptables with Elastic Agent.
- Version: 1.23.0
- Categories: network, security
- Docs: `packages/iptables/docs/README.md`

### IRONSCALES
- Name: `ironscales`
- Path: `packages/ironscales/`
- Description: Collect logs from IRONSCALES with Elastic Agent.
- Version: 0.1.0
- Categories: security
- Docs: `packages/ironscales/docs/README.md`

### Island Browser
- Name: `island_browser`
- Path: `packages/island_browser/`
- Description: Collect logs from Island Browser with Elastic Agent.
- Version: 1.0.0
- Categories: security
- Docs: `packages/island_browser/docs/README.md`

### Istio
- Name: `istio`
- Path: `packages/istio/`
- Description: Collect logs and metrics from the service mesh Istio with Elastic Agent.
- Version: 0.8.0
- Categories: observability, network, containers, kubernetes
- Docs: `packages/istio/docs/README.md`

### Jamf Compliance Reporter
- Name: `jamf_compliance_reporter`
- Path: `packages/jamf_compliance_reporter/`
- Description: Collect logs from Jamf Compliance Reporter with Elastic Agent.
- Version: 1.16.0
- Categories: security
- Docs: `packages/jamf_compliance_reporter/docs/README.md`

### Jamf Pro
- Name: `jamf_pro`
- Path: `packages/jamf_pro/`
- Description: Collect logs and inventory data from Jamf Pro with Elastic Agent
- Version: 1.1.0
- Categories: cloud, custom
- Docs: `packages/jamf_pro/docs/README.md`

### Jamf Protect
- Name: `jamf_protect`
- Path: `packages/jamf_protect/`
- Description: Receives events from Jamf Protect with Elastic Agent.
- Version: 3.3.1
- Categories: security, edr_xdr
- Docs: `packages/jamf_protect/docs/README.md`

### Jolokia Input
- Name: `jolokia`
- Path: `packages/jolokia_input/`
- Description: Collects Metrics from Jolokia Agents
- Version: 1.0.0
- Categories: observability, custom
- Docs: `packages/jolokia_input/docs/README.md`

### Custom Journald logs
- Name: `journald`
- Path: `packages/journald/`
- Description: Collect logs from journald with Elastic Agent.
- Version: 1.2.1
- Categories: observability, custom
- Docs: `packages/journald/docs/README.md`

### JumpCloud
- Name: `jumpcloud`
- Path: `packages/jumpcloud/`
- Description: Collect logs from JumpCloud Directory as a Service
- Version: 1.17.1
- Categories: cloud, security
- Docs: `packages/jumpcloud/docs/README.md`

### Juniper JunOS (Deprecated)
- Name: `juniper_junos`
- Path: `packages/juniper_junos/`
- Description: Deprecated. Use the Juniper SRX package instead.
- Version: 0.12.1
- Docs: `packages/juniper_junos/docs/README.md`

### Juniper NetScreen (Deprecated)
- Name: `juniper_netscreen`
- Path: `packages/juniper_netscreen/`
- Description: Deprecated. Juniper NetScreen is no longer supported.
- Version: 0.12.1
- Docs: `packages/juniper_netscreen/docs/README.md`

### Juniper SRX
- Name: `juniper_srx`
- Path: `packages/juniper_srx/`
- Description: Collect logs from Juniper SRX devices with Elastic Agent.
- Version: 1.27.0
- Docs: `packages/juniper_srx/docs/README.md`

### JupiterOne
- Name: `jupiter_one`
- Path: `packages/jupiter_one/`
- Description: Collect logs from JupiterOne with Elastic Agent.
- Version: 0.1.0
- Categories: security
- Docs: `packages/jupiter_one/docs/README.md`

### Kafka
- Name: `kafka`
- Path: `packages/kafka/`
- Description: Collect logs and metrics from Kafka servers with Elastic Agent.
- Version: 1.27.0
- Categories: stream_processing, observability
- Docs: `packages/kafka/docs/README.md`

### Kafka Connect
- Name: `kafka_connect`
- Path: `packages/kafka_connect/`
- Description: Collect metrics from Kafka Connect instances with Elastic Agent.
- Version: 0.1.0
- Categories: message_queue, observability, monitoring, infrastructure
- Docs: `packages/kafka_connect/docs/README.md`

### Custom Kafka Logs
- Name: `kafka_log`
- Path: `packages/kafka_log/`
- Description: Collect data from kafka topic with Elastic Agent.
- Version: 2.0.0
- Categories: observability, custom
- Docs: `packages/kafka_log/docs/README.md`

### Kafka OpenTelemetry Assets
- Name: `kafka_otel`
- Path: `packages/kafka_otel/`
- Description: Kafka Assets for OpenTelemetry Collector
- Version: 0.1.0
- Categories: observability, message_queue, opentelemetry
- Docs: `packages/kafka_otel/docs/README.md`

### Keeper Security
- Name: `keeper`
- Path: `packages/keeper_security_siem_integration/`
- Description: Keeper Security agentless integration for collecting audit events directly via Elasticsearch Bulk API. No agents required - Keeper pushes data directly to Elasticsearch.
- Version: 0.1.0
- Categories: security, authentication, custom
- Docs: `packages/keeper_security_siem_integration/docs/README.md`

### Keycloak
- Name: `keycloak`
- Path: `packages/keycloak/`
- Description: Collect logs from Keycloak with Elastic Agent.
- Version: 1.31.2
- Docs: `packages/keycloak/docs/README.md`

### Kibana
- Name: `kibana`
- Path: `packages/kibana/`
- Description: Collect logs and metrics from Kibana with Elastic Agent.
- Version: 2.8.0
- Docs: `packages/kibana/docs/README.md`

### Kubelet Stats OpenTelemetry Input
- Name: `kubeletstats_input_otel`
- Path: `packages/kubeletstats_input_otel/`
- Description: Collect Kubernetes node, pod, container, and volume metrics from the Kubelet API using the OpenTelemetry Collector.
- Version: 0.1.0
- Categories: containers, kubernetes, observability, opentelemetry
- Docs: `packages/kubeletstats_input_otel/docs/README.md`

### Kubernetes
- Name: `kubernetes`
- Path: `packages/kubernetes/`
- Description: Collect logs and metrics from Kubernetes clusters with Elastic Agent.
- Version: 1.85.0
- Categories: observability, containers, kubernetes
- Docs: `packages/kubernetes/docs/README.md`

### Kubernetes OpenTelemetry Assets
- Name: `kubernetes_otel`
- Path: `packages/kubernetes_otel/`
- Description: Utilise the pre-built dashboard for OTel-native metrics and events collected from a Kubernetes cluster
- Version: 2.1.0-preview1
- Categories: kubernetes
- Docs: `packages/kubernetes_otel/docs/README.md`

### LastPass
- Name: `lastpass`
- Path: `packages/lastpass/`
- Description: Collect logs from LastPass with Elastic Agent.
- Version: 1.21.0
- Categories: security, credential_management
- Docs: `packages/lastpass/docs/README.md`

### Linux Metrics
- Name: `linux`
- Path: `packages/linux/`
- Description: Collect metrics from Linux servers with Elastic Agent.
- Version: 1.1.0
- Categories: os_system
- Docs: `packages/linux/docs/README.md`

### Lateral Movement Detection
- Name: `lmd`
- Path: `packages/lmd/`
- Description: ML package to detect lateral movement based on file transfer activity and Windows RDP events.
- Version: 3.1.1
- Categories: security, advanced_analytics_ueba
- Docs: `packages/lmd/docs/README.md`

### Custom Logs (Deprecated)
- Name: `log`
- Path: `packages/log/`
- Description: Collect custom logs with Elastic Agent.
- Version: 2.4.4
- Categories: custom, custom_logs
- Docs: `packages/log/docs/README.md`

### Logstash
- Name: `logstash`
- Path: `packages/logstash/`
- Description: Collect logs and metrics from Logstash with Elastic Agent.
- Version: 2.10.1
- Categories: observability, elastic_stack
- Docs: `packages/logstash/docs/README.md`

### Lumos
- Name: `lumos`
- Path: `packages/lumos/`
- Description: An integration with Lumos to ship your Activity logs to your Elastic instance.
- Version: 1.6.0
- Categories: security
- Docs: `packages/lumos/docs/README.md`

### Lyve Cloud
- Name: `lyve_cloud`
- Path: `packages/lyve_cloud/`
- Description: Collect S3 API audit log from Lyve Cloud with Elastic Agent.
- Version: 1.17.1
- Categories: security
- Docs: `packages/lyve_cloud/docs/README.md`

### Microsoft Defender XDR
- Name: `m365_defender`
- Path: `packages/m365_defender/`
- Description: Collect logs from Microsoft Defender XDR with Elastic Agent.
- Version: 5.13.0
- Categories: security, edr_xdr, vulnerability_workflow, cloudsecurity_cdr
- Docs: `packages/m365_defender/docs/README.md`

### macOS Security Events
- Name: `macos`
- Path: `packages/macos/`
- Description: Collect logs from macOS with Elastic Agent.
- Version: 1.0.0
- Categories: security
- Docs: `packages/macos/docs/README.md`

### Mattermost
- Name: `mattermost`
- Path: `packages/mattermost/`
- Description: Collect logs from Mattermost with Elastic Agent.
- Version: 2.5.0
- Categories: security, productivity_security
- Docs: `packages/mattermost/docs/README.md`

### Memcached
- Name: `memcached`
- Path: `packages/memcached/`
- Description: Memcached Integration
- Version: 1.8.0
- Categories: observability
- Docs: `packages/memcached/docs/README.md`

### Memcached OpenTelemetry assets
- Name: `memcached_otel`
- Path: `packages/memcached_otel/`
- Description: Memcached Assets for OpenTelemetry Collector
- Version: 0.1.0
- Categories: observability, opentelemetry
- Docs: `packages/memcached_otel/docs/README.md`

### Menlo Security
- Name: `menlo`
- Path: `packages/menlo/`
- Description: Collect logs from Menlo Security products with Elastic Agent
- Version: 1.7.1
- Categories: monitoring, network
- Docs: `packages/menlo/docs/README.md`

### Microsoft Defender for Cloud
- Name: `microsoft_defender_cloud`
- Path: `packages/microsoft_defender_cloud/`
- Description: Collect logs from Microsoft Defender for Cloud with Elastic Agent.
- Version: 3.4.0
- Categories: security, cloudsecurity_cdr, vulnerability_workflow, misconfiguration_workflow
- Docs: `packages/microsoft_defender_cloud/docs/README.md`

### Microsoft Defender for Endpoint
- Name: `microsoft_defender_endpoint`
- Path: `packages/microsoft_defender_endpoint/`
- Description: Collect logs from Microsoft Defender for Endpoint with Elastic Agent.
- Version: 4.6.0
- Categories: security, edr_xdr
- Docs: `packages/microsoft_defender_endpoint/docs/README.md`

### Microsoft DHCP
- Name: `microsoft_dhcp`
- Path: `packages/microsoft_dhcp/`
- Description: Collect logs from Microsoft DHCP with Elastic Agent.
- Version: 1.27.0
- Categories: security
- Docs: `packages/microsoft_dhcp/docs/README.md`

### Microsoft DNS Server
- Name: `microsoft_dnsserver`
- Path: `packages/microsoft_dnsserver/`
- Description: Collect logs from Microsoft DNS Server with Elastic Agent.
- Version: 1.5.1
- Categories: network, security
- Docs: `packages/microsoft_dnsserver/docs/README.md`

### Microsoft Exchange Online Message Trace
- Name: `microsoft_exchange_online_message_trace`
- Path: `packages/microsoft_exchange_online_message_trace/`
- Description: Microsoft Exchange Online Message Trace Integration
- Version: 2.0.4
- Categories: security, email_security
- Docs: `packages/microsoft_exchange_online_message_trace/docs/README.md`

### Microsoft Exchange Server
- Name: `microsoft_exchange_server`
- Path: `packages/microsoft_exchange_server/`
- Description: Collect logs from Microsoft Exchange Server with Elastic Agent.
- Version: 1.5.1
- Categories: security
- Docs: `packages/microsoft_exchange_server/docs/README.md`

### Microsoft Sentinel
- Name: `microsoft_sentinel`
- Path: `packages/microsoft_sentinel/`
- Description: Collect logs from Microsoft Sentinel with Elastic Agent.
- Version: 1.3.1
- Categories: azure, security, siem
- Docs: `packages/microsoft_sentinel/docs/README.md`

### Microsoft SQL Server
- Name: `microsoft_sqlserver`
- Path: `packages/microsoft_sqlserver/`
- Description: Collect events from Microsoft SQL Server with Elastic Agent
- Version: 2.16.0
- Categories: database_security, security, observability
- Docs: `packages/microsoft_sqlserver/docs/README.md`

### Microsoft SQL Server Assets
- Name: `microsoft_sqlserver_otel`
- Path: `packages/microsoft_sqlserver_otel/`
- Description: Microsoft SQL Server Assets
- Version: 0.1.0
- Categories: datastore, opentelemetry, observability
- Docs: `packages/microsoft_sqlserver_otel/docs/README.md`

### Mimecast
- Name: `mimecast`
- Path: `packages/mimecast/`
- Description: Collect logs from Mimecast with Elastic Agent.
- Version: 3.3.2
- Docs: `packages/mimecast/docs/README.md`

### Miniflux RSS reader
- Name: `miniflux`
- Path: `packages/miniflux/`
- Description: Collect RSS feed content from the Miniflux API with Elastic Agent.
- Version: 1.0.1
- Docs: `packages/miniflux/docs/README.md`

### ModSecurity Audit
- Name: `modsecurity`
- Path: `packages/modsecurity/`
- Description: Collect logs from ModSecurity with Elastic Agent
- Version: 1.23.1
- Categories: security, network, web_application_firewall
- Docs: `packages/modsecurity/docs/README.md`

### MongoDB
- Name: `mongodb`
- Path: `packages/mongodb/`
- Description: Collect logs and metrics from MongoDB instances with Elastic Agent.
- Version: 1.24.0
- Categories: datastore, observability
- Docs: `packages/mongodb/docs/README.md`

### MongoDB Atlas
- Name: `mongodb_atlas`
- Path: `packages/mongodb_atlas/`
- Description: This Elastic integration collects logs and metrics from MongoDB Atlas instance.
- Version: 1.2.1
- Categories: cloud, datastore, observability
- Docs: `packages/mongodb_atlas/docs/README.md`

### MongoDB OpenTelemetry Assets
- Name: `mongodb_otel`
- Path: `packages/mongodb_otel/`
- Description: MongoDB Assets for OpenTelemetry Collector
- Version: 0.1.0
- Categories: observability, datastore, opentelemetry
- Docs: `packages/mongodb_otel/docs/README.md`

### MySQL
- Name: `mysql`
- Path: `packages/mysql/`
- Description: Collect logs and metrics from MySQL servers with Elastic Agent.
- Version: 1.29.2
- Categories: datastore, observability
- Docs: `packages/mysql/docs/README.md`

### MySQL Enterprise
- Name: `mysql_enterprise`
- Path: `packages/mysql_enterprise/`
- Description: Collect audit logs from MySQL Enterprise with Elastic Agent.
- Version: 1.17.0
- Categories: security
- Docs: `packages/mysql_enterprise/docs/README.md`

### MySQL OpenTelemetry Input Package
- Name: `mysql_input_otel`
- Path: `packages/mysql_input_otel/`
- Description: Collect MySQL metrics and logs using OpenTelemetry Collector
- Version: 0.2.1
- Categories: datastore, observability, opentelemetry
- Docs: `packages/mysql_input_otel/docs/README.md`

### MySQL OpenTelemetry Assets
- Name: `mysql_otel`
- Path: `packages/mysql_otel/`
- Description: MySQL Assets for OpenTelemetry Collector
- Version: 0.4.0
- Categories: datastore, observability, opentelemetry
- Docs: `packages/mysql_otel/docs/README.md`

### Nagios XI
- Name: `nagios_xi`
- Path: `packages/nagios_xi/`
- Description: Collect Logs and Metrics from Nagios XI with Elastic Agent.
- Version: 1.8.0
- Categories: observability, monitoring
- Docs: `packages/nagios_xi/docs/README.md`

### NATS
- Name: `nats`
- Path: `packages/nats/`
- Description: Collect logs and metrics from NATS servers with Elastic Agent.
- Version: 1.12.0
- Categories: observability, message_queue
- Docs: `packages/nats/docs/README.md`

### Neon Cyber
- Name: `neon_cyber`
- Path: `packages/neon_cyber/`
- Description: The Neon Cyber integration for the Elastic Stack
- Version: 0.1.0
- Categories: security, edr_xdr
- Docs: `packages/neon_cyber/docs/README.md`

### NetFlow Records
- Name: `netflow`
- Path: `packages/netflow/`
- Description: Collect flow records from NetFlow and IPFIX exporters with Elastic Agent.
- Version: 2.25.0
- Categories: network, security
- Docs: `packages/netflow/docs/README.md`

### Arbor Peakflow SP Logs (Deprecated)
- Name: `netscout`
- Path: `packages/netscout/`
- Description: Deprecated. Netscout Arbor Peakflow SP is no longer supported.
- Version: 0.22.1
- Categories: security, network
- Docs: `packages/netscout/docs/README.md`

### Netskope
- Name: `netskope`
- Path: `packages/netskope/`
- Description: Collect logs from Netskope with Elastic Agent.
- Version: 3.1.4
- Categories: security, network
- Docs: `packages/netskope/docs/README.md`

### Network Packet Capture
- Name: `network_traffic`
- Path: `packages/network_traffic/`
- Description: Capture and analyze network traffic from a host with Elastic Agent.
- Version: 1.34.2
- Categories: network, security
- Docs: `packages/network_traffic/docs/README.md`

### Nextron Thor APT Scanner
- Name: `nextron_thor_apt_scanner`
- Path: `packages/nextron_thor/`
- Description: Integration for Nextron Thor APT Scanner
- Version: 0.0.1
- Categories: security
- Docs: `packages/nextron_thor/docs/README.md`

### Nginx
- Name: `nginx`
- Path: `packages/nginx/`
- Description: Collect logs and metrics from Nginx HTTP servers with Elastic Agent.
- Version: 3.1.0
- Categories: web, observability
- Docs: `packages/nginx/docs/README.md`

### Nginx Ingress Controller Logs
- Name: `nginx_ingress_controller`
- Path: `packages/nginx_ingress_controller/`
- Description: Collect Nginx Ingress Controller logs.
- Version: 1.14.0
- Categories: observability, containers, kubernetes
- Docs: `packages/nginx_ingress_controller/docs/README.md`

### Nginx Ingress Controller OpenTelemetry Logs
- Name: `nginx_ingress_controller_otel`
- Path: `packages/nginx_ingress_controller_otel/`
- Description: Collect Nginx Ingress Controller logs using the OpenTelemetry collector.
- Version: 0.2.2
- Categories: observability, containers, kubernetes, opentelemetry
- Docs: `packages/nginx_ingress_controller_otel/docs/README.md`

### NGINX OpenTelemetry Input Package
- Name: `nginx_otel_input`
- Path: `packages/nginx_input_otel/`
- Description: NGINX OpenTelemetry Input Package
- Version: 0.2.0
- Categories: web, observability, opentelemetry
- Docs: `packages/nginx_input_otel/docs/README.md`

### NGINX OpenTelemetry Assets
- Name: `nginx_otel`
- Path: `packages/nginx_otel/`
- Description: NGINX Assets from OpenTelemetry Collector
- Version: 0.3.0
- Categories: observability, web, opentelemetry
- Docs: `packages/nginx_otel/docs/README.md`

### Nozomi Networks
- Name: `nozomi_networks`
- Path: `packages/nozomi_networks/`
- Description: Collect logs from Nozomi Networks with Elastic Agent.
- Version: 0.2.1
- Categories: security, network
- Docs: `packages/nozomi_networks/docs/README.md`

### NVIDIA GPU Monitoring
- Name: `nvidia_gpu`
- Path: `packages/nvidia_gpu/`
- Description: Monitor NVIDIA GPUs via NVIDIA Data Center GPU Manager
- Version: 0.4.1
- Categories: cloud, observability, custom, kubernetes, os_system
- Docs: `packages/nvidia_gpu/docs/README.md`

### NVIDIA GPU OpenTelemetry Assets
- Name: `nvidia_gpu_otel`
- Path: `packages/nvidia_gpu_otel/`
- Description: NVIDIA GPU Assets for OpenTelemetry Collector
- Version: 0.1.0
- Categories: cloud, observability, opentelemetry, os_system
- Docs: `packages/nvidia_gpu_otel/docs/README.md`

### Microsoft Office 365
- Name: `o365`
- Path: `packages/o365/`
- Description: Collect logs from Microsoft Office 365 with Elastic Agent.
- Version: 3.8.1
- Categories: security, productivity_security
- Docs: `packages/o365/docs/README.md`

### Microsoft Office 365 Metrics
- Name: `o365_metrics`
- Path: `packages/o365_metrics/`
- Description: Collect metrics from Microsoft Office 365 with Elastic Agent.
- Version: 1.2.0
- Categories: observability, security
- Docs: `packages/o365_metrics/docs/README.md`

### Okta
- Name: `okta`
- Path: `packages/okta/`
- Description: Collect and parse event logs from Okta API with Elastic Agent.
- Version: 3.14.1
- Docs: `packages/okta/docs/README.md`

### OpenAI
- Name: `openai`
- Path: `packages/openai/`
- Description: Collect OpenAI usage metrics with Elastic Agent.
- Version: 1.2.1
- Categories: observability, monitoring
- Docs: `packages/openai/docs/README.md`

### OpenCanary
- Name: `opencanary`
- Path: `packages/opencanary/`
- Description: This integration collects and parses logs from OpenCanary honeypots.
- Version: 1.0.0
- Categories: security
- Docs: `packages/opencanary/docs/README.md`

### Oracle
- Name: `oracle`
- Path: `packages/oracle/`
- Description: Collect Oracle Audit Log, Performance metrics, Tablespace metrics, Sysmetrics metrics, System statistics metrics, memory metrics from Oracle database.
- Version: 1.31.2
- Categories: observability, datastore
- Docs: `packages/oracle/docs/README.md`

### Oracle OpenTelemetry Assets
- Name: `oracle_otel`
- Path: `packages/oracle_otel/`
- Description: Oracle Assets for OpenTelemetry Collector
- Version: 0.1.0
- Categories: observability, message_queue, opentelemetry
- Docs: `packages/oracle_otel/docs/README.md`

### Oracle WebLogic
- Name: `oracle_weblogic`
- Path: `packages/oracle_weblogic/`
- Description: Collect logs and metrics from Oracle WebLogic with Elastic Agent.
- Version: 1.9.1
- Categories: web, observability
- Docs: `packages/oracle_weblogic/docs/README.md`

### Osquery Logs
- Name: `osquery`
- Path: `packages/osquery/`
- Description: Collect logs from Osquery with Elastic Agent.
- Version: 1.24.1
- Categories: security
- Docs: `packages/osquery/docs/README.md`

### Osquery Manager
- Name: `osquery_manager`
- Path: `packages/osquery_manager/`
- Description: Deploy Osquery with Elastic Agent, then run and schedule queries in Kibana
- Version: 1.28.1
- Categories: security
- Docs: `packages/osquery_manager/docs/README.md`

### Android OpenTelemetry Assets
- Name: `otel_android_dashboards`
- Path: `packages/otel_android_dashboards/`
- Description: Dashboards for visualizing Android application's telemetry
- Version: 0.1.0
- Categories: observability, application_observability, opentelemetry
- Docs: `packages/otel_android_dashboards/docs/README.md`

### OpenTelemetry Collector Internal Telemetry
- Name: `otel_collector_internal_telemetry`
- Path: `packages/otel_collector_internal_telemetry/`
- Description: This package contains dashboards that visualize the internal telemetry from the OpenTelemetry Collector
- Version: 1.2.0
- Categories: monitoring, observability, opentelemetry
- Docs: `packages/otel_collector_internal_telemetry/docs/README.md`

### RUM OpenTelemetry Assets
- Name: `otel_rum_dashboards`
- Path: `packages/otel_rum_dashboards/`
- Description: RUM status metrics from OpenTelemetry JS SDKs
- Version: 0.0.3
- Categories: observability, web, opentelemetry
- Docs: `packages/otel_rum_dashboards/docs/README.md`

### Privileged Access Detection
- Name: `pad`
- Path: `packages/pad/`
- Description: ML package to detect anomalous privileged access activity in Windows, Linux and Okta logs
- Version: 2.1.0
- Categories: security, advanced_analytics_ueba
- Docs: `packages/pad/docs/README.md`

### Palo Alto Next-Gen Firewall
- Name: `panw`
- Path: `packages/panw/`
- Description: Collect logs from Palo Alto next-gen firewalls with Elastic Agent.
- Version: 5.5.0
- Categories: security, network
- Docs: `packages/panw/docs/README.md`

### Palo Alto Cortex XDR
- Name: `panw_cortex_xdr`
- Path: `packages/panw_cortex_xdr/`
- Description: Collect logs from Palo Alto Cortex XDR with Elastic Agent.
- Version: 2.5.2
- Categories: security, edr_xdr
- Docs: `packages/panw_cortex_xdr/docs/README.md`

### Palo Alto Networks Metrics
- Name: `panw_metrics`
- Path: `packages/panw_metrics/`
- Description: Collect metrics from Palo Alto Networks with Elastic Agent.
- Version: 0.2.0
- Categories: network, security, observability
- Docs: `packages/panw_metrics/docs/README.md`

### pfSense
- Name: `pfsense`
- Path: `packages/pfsense/`
- Description: Collect logs from pfSense and OPNsense with Elastic Agent.
- Version: 1.25.2
- Categories: network, security, firewall_security
- Docs: `packages/pfsense/docs/README.md`

### PHP-FPM
- Name: `php_fpm`
- Path: `packages/php_fpm/`
- Description: This Elastic integration collects metrics from PHP-FPM.
- Version: 1.6.0
- Categories: observability, process_manager
- Docs: `packages/php_fpm/docs/README.md`

### PingFederate
- Name: `ping_federate`
- Path: `packages/ping_federate/`
- Description: Collect logs from PingFederate with Elastic Agent.
- Version: 1.2.0
- Categories: security, authentication
- Docs: `packages/ping_federate/docs/README.md`

### PingOne
- Name: `ping_one`
- Path: `packages/ping_one/`
- Description: Collect logs from PingOne with Elastic-Agent.
- Version: 1.23.0
- Categories: security, iam
- Docs: `packages/ping_one/docs/README.md`

### Platform Observability
- Name: `platform_observability`
- Path: `packages/platform_observability/`
- Description: Collect stack component logs with Elastic Agent
- Version: 0.1.0
- Docs: `packages/platform_observability/docs/README.md`

### PostgreSQL
- Name: `postgresql`
- Path: `packages/postgresql/`
- Description: Collect logs and metrics from PostgreSQL servers with Elastic Agent.
- Version: 1.32.1
- Categories: datastore, observability
- Docs: `packages/postgresql/docs/README.md`

### PostgreSQL OpenTelemetry Assets
- Name: `postgresql_otel`
- Path: `packages/postgresql_otel/`
- Description: PostgreSQL Assets for OpenTelemetry Collector
- Version: 0.3.0
- Categories: observability, datastore, opentelemetry
- Docs: `packages/postgresql_otel/docs/README.md`

### Pleasant Password Server
- Name: `pps`
- Path: `packages/pps/`
- Description: Integration for Pleasant Password Server Syslog Messages
- Version: 1.2.1
- Categories: custom, productivity, security
- Docs: `packages/pps/docs/README.md`

### Palo Alto Prisma Access
- Name: `prisma_access`
- Path: `packages/prisma_access/`
- Description: Collect logs from Palo Alto Prisma Access with Elastic Agent.
- Version: 1.7.3
- Categories: security, network
- Docs: `packages/prisma_access/docs/README.md`

### Palo Alto Prisma Cloud
- Name: `prisma_cloud`
- Path: `packages/prisma_cloud/`
- Description: Collect logs from Prisma Cloud with Elastic Agent.
- Version: 4.1.0
- Categories: security, cloudsecurity_cdr, misconfiguration_workflow, vulnerability_workflow
- Docs: `packages/prisma_cloud/docs/README.md`

### Living off the Land Attack Detection
- Name: `problemchild`
- Path: `packages/problemchild/`
- Description: ML solution package to detect Living off the Land (LotL) attacks in your environment. Requires a Platinum subscription.
- Version: 3.0.1
- Categories: security, advanced_analytics_ueba
- Docs: `packages/problemchild/docs/README.md`

### Profilingmetrics OpenTelemetry Assets
- Name: `profilingmetrics_otel`
- Path: `packages/profilingmetrics_otel/`
- Description: Create metrics from profiling data.
- Version: 0.0.6
- Categories: custom, observability, opentelemetry
- Docs: `packages/profilingmetrics_otel/docs/README.md`

### Prometheus
- Name: `prometheus`
- Path: `packages/prometheus/`
- Description: Collect metrics from Prometheus servers with Elastic Agent.
- Version: 1.24.2
- Categories: observability, monitoring, containers
- Docs: `packages/prometheus/docs/README.md`

### Prometheus Input
- Name: `prometheus_input`
- Path: `packages/prometheus_input/`
- Description: Collects metrics from Prometheus exporter.
- Version: 1.0.0
- Categories: monitoring, containers, custom, observability
- Docs: `packages/prometheus_input/docs/README.md`

### Prometheus OTel Scrape (Guided)
- Name: `prometheus_input_otel`
- Path: `packages/prometheus_input_otel/`
- Description: Scrape Prometheus metrics endpoints using the OpenTelemetry Collector Prometheus receiver with guided configuration
- Version: 0.1.0
- Categories: monitoring, observability, opentelemetry
- Docs: `packages/prometheus_input_otel/docs/README.md`

### Prometheus OTel Scrape (Bring Your Own Config)
- Name: `prometheus_input_otel_raw`
- Path: `packages/prometheus_input_otel_raw/`
- Description: Scrape Prometheus metrics endpoints using the OpenTelemetry Collector Prometheus receiver with raw scrape configuration
- Version: 0.1.0
- Categories: monitoring, observability, opentelemetry
- Docs: `packages/prometheus_input_otel_raw/docs/README.md`

### Proofpoint 365 Total Protection
- Name: `proofpoint_365totalprotection`
- Path: `packages/proofpoint_365totalprotection/`
- Description: The Proofpoint 365 Total Protection integration for Elastic collects detailed email security and delivery logs via a REST API. It provides security teams with centralized visibility into email traffic, threat activity, and message disposition directly in Elastic.
- Version: 0.1.0
- Categories: security, email_security
- Docs: `packages/proofpoint_365totalprotection/docs/README.md`

### Proofpoint Essentials
- Name: `proofpoint_essentials`
- Path: `packages/proofpoint_essentials/`
- Description: Collect logs from Proofpoint Essentials with Elastic Agent.
- Version: 0.1.0
- Categories: security
- Docs: `packages/proofpoint_essentials/docs/README.md`

### Proofpoint ITM
- Name: `proofpoint_itm`
- Path: `packages/proofpoint_itm/`
- Description: Collect logs from Proofpoint ITM using Elastic Agent.
- Version: 1.0.1
- Categories: security
- Docs: `packages/proofpoint_itm/docs/README.md`

### Proofpoint On Demand
- Name: `proofpoint_on_demand`
- Path: `packages/proofpoint_on_demand/`
- Description: Collect logs from Proofpoint On Demand with Elastic Agent.
- Version: 1.9.1
- Categories: security
- Docs: `packages/proofpoint_on_demand/docs/README.md`

### Proofpoint TAP
- Name: `proofpoint_tap`
- Path: `packages/proofpoint_tap/`
- Description: Collect logs from Proofpoint TAP with Elastic Agent.
- Version: 1.29.1
- Categories: security, email_security
- Docs: `packages/proofpoint_tap/docs/README.md`

### Broadcom ProxySG
- Name: `proxysg`
- Path: `packages/proxysg/`
- Description: Collect access logs from Broadcom ProxySG with Elastic Agent.
- Version: 0.8.0
- Categories: network, security
- Docs: `packages/proxysg/docs/README.md`

### Pulse Connect Secure
- Name: `pulse_connect_secure`
- Path: `packages/pulse_connect_secure/`
- Description: Collect logs from Pulse Connect Secure with Elastic Agent.
- Version: 2.6.1
- Docs: `packages/pulse_connect_secure/docs/README.md`

### QNAP NAS
- Name: `qnap_nas`
- Path: `packages/qnap_nas/`
- Description: Collect logs from QNAP NAS devices with Elastic Agent.
- Version: 1.25.2
- Docs: `packages/qnap_nas/docs/README.md`

### Qualys Global AssetView
- Name: `qualys_gav`
- Path: `packages/qualys_gav/`
- Description: Collect logs from Qualys Global AssetView with Elastic Agent.
- Version: 0.7.2
- Categories: security
- Docs: `packages/qualys_gav/docs/README.md`

### Qualys VMDR
- Name: `qualys_vmdr`
- Path: `packages/qualys_vmdr/`
- Description: Collect data from Qualys VMDR platform with Elastic Agent.
- Version: 6.18.0
- Categories: security, vulnerability_management, vulnerability_workflow, cloudsecurity_cdr
- Docs: `packages/qualys_vmdr/docs/README.md`

### Qualys Web Application Scanning (WAS)
- Name: `qualys_was`
- Path: `packages/qualys_was/`
- Description: Collect data from Qualys Web Application Scanning platform with Elastic Agent or Agentless
- Version: 0.3.1
- Categories: security, vulnerability_management
- Docs: `packages/qualys_was/docs/README.md`

### RabbitMQ Logs and Metrics
- Name: `rabbitmq`
- Path: `packages/rabbitmq/`
- Description: Collect and parse logs from RabbitMQ servers with Elastic Agent.
- Version: 1.22.0
- Categories: message_queue, observability
- Docs: `packages/rabbitmq/docs/README.md`

### RabbitMQ OpenTelemetry assets
- Name: `rabbitmq_otel`
- Path: `packages/rabbitmq_otel/`
- Description: RabbitMQ Assets for OpenTelemetry Collector
- Version: 0.1.0
- Categories: message_queue, observability, opentelemetry
- Docs: `packages/rabbitmq_otel/docs/README.md`

### Radware DefensePro Logs (Deprecated)
- Name: `radware`
- Path: `packages/radware/`
- Description: Deprecated. Radware DefensePro Logs is no longer supported.
- Version: 0.20.1
- Docs: `packages/radware/docs/README.md`

### Rapid7 InsightVM
- Name: `rapid7_insightvm`
- Path: `packages/rapid7_insightvm/`
- Description: Collect logs from Rapid7 InsightVM with Elastic Agent.
- Version: 2.8.0
- Categories: security, vulnerability_management, vulnerability_workflow, cloudsecurity_cdr
- Docs: `packages/rapid7_insightvm/docs/README.md`

### Redis
- Name: `redis`
- Path: `packages/redis/`
- Description: Collect logs and metrics from Redis servers with Elastic Agent.
- Version: 1.20.0
- Categories: datastore, observability
- Docs: `packages/redis/docs/README.md`

### Redis OpenTelemetry Input Package
- Name: `redis_input_otel`
- Path: `packages/redis_input_otel/`
- Description: Redis OpenTelemetry Input Package
- Version: 0.1.0
- Categories: datastore, observability, opentelemetry
- Docs: `packages/redis_input_otel/docs/README.md`

### Redis OpenTelemetry Assets
- Name: `redis_otel`
- Path: `packages/redis_otel/`
- Description: Redis Assets for OpenTelemetry Collector
- Version: 0.1.0
- Categories: datastore, observability, opentelemetry
- Docs: `packages/redis_otel/docs/README.md`

### Redis Enterprise
- Name: `redisenterprise`
- Path: `packages/redisenterprise/`
- Description: Collect metrics from Redis Enterprise Cluster
- Version: 0.12.0
- Categories: datastore, observability
- Docs: `packages/redisenterprise/docs/README.md`

### Redis Enterprise OpenTelemetry Assets
- Name: `redisenterprise_otel`
- Path: `packages/redisenterprise_otel/`
- Description: Redis Enterprise Assets for OpenTelemetry Collector
- Version: 0.1.0
- Categories: datastore, observability, opentelemetry
- Docs: `packages/redisenterprise_otel/docs/README.md`

### Rubrik RSC Metrics
- Name: `rubrik`
- Path: `packages/rubrik/`
- Description: Collect Metrics from Rubrik RSC with Elastic Agent.
- Version: 0.9.3
- Categories: observability
- Docs: `packages/rubrik/docs/README.md`

### Sailpoint Identity Security Cloud
- Name: `sailpoint_identity_sc`
- Path: `packages/sailpoint_identity_sc/`
- Description: Sailpoint identity security cloud provides enterprise identity governance and security capabilities. The integration allows users to extract audit information from their identity security cloud tenant using the ISC's AuditEvent API.
- Version: 1.2.0
- Categories: security
- Docs: `packages/sailpoint_identity_sc/docs/README.md`

### Salesforce
- Name: `salesforce`
- Path: `packages/salesforce/`
- Description: Collect logs from Salesforce instances using the Elastic Agent. This integration enables monitoring and analysis of various Salesforce logs, including Login, Logout, Setup Audit Trail, and Apex execution logs. Gain insights into user activity, security events, and application performance.
- Version: 1.7.1
- Categories: observability
- Docs: `packages/salesforce/docs/README.md`

### Google Santa
- Name: `santa`
- Path: `packages/santa/`
- Description: Collect logs from Google Santa with Elastic Agent.
- Version: 3.24.0
- Categories: security
- Docs: `packages/santa/docs/README.md`

### Security AI Prompts
- Name: `security_ai_prompts`
- Path: `packages/security_ai_prompts/`
- Description: Prompts used by Security AI features, including the Security Assistant, and Attack discovery
- Version: 1.0.13
- Categories: security
- Docs: `packages/security_ai_prompts/docs/README.md`

### Prebuilt Security Detection Rules
- Name: `security_detection_engine`
- Path: `packages/security_detection_engine/`
- Description: Prebuilt detection rules for Elastic Security
- Version: 9.4.3
- Categories: security, siem
- Docs: `packages/security_detection_engine/docs/README.md`

### SentinelOne
- Name: `sentinel_one`
- Path: `packages/sentinel_one/`
- Description: Collect logs from SentinelOne with Elastic Agent.
- Version: 2.6.0
- Categories: security, edr_xdr
- Docs: `packages/sentinel_one/docs/README.md`

### SentinelOne Cloud Funnel
- Name: `sentinel_one_cloud_funnel`
- Path: `packages/sentinel_one_cloud_funnel/`
- Description: Collect logs from SentinelOne Cloud Funnel with Elastic Agent.
- Version: 1.13.1
- Categories: security, edr_xdr
- Docs: `packages/sentinel_one_cloud_funnel/docs/README.md`

### ServiceNow
- Name: `servicenow`
- Path: `packages/servicenow/`
- Description: Collect logs from ServiceNow with Elastic Agent.
- Version: 2.0.0
- Categories: security
- Docs: `packages/servicenow/docs/README.md`

### Slack Logs
- Name: `slack`
- Path: `packages/slack/`
- Description: Slack Logs Integration
- Version: 1.27.0
- Categories: productivity, security
- Docs: `packages/slack/docs/README.md`

### Snort
- Name: `snort`
- Path: `packages/snort/`
- Description: Collect logs from Snort with Elastic Agent.
- Version: 1.21.1
- Categories: ids_ips, security
- Docs: `packages/snort/docs/README.md`

### Snyk
- Name: `snyk`
- Path: `packages/snyk/`
- Description: Collect logs from Snyk with Elastic Agent.
- Version: 3.4.2
- Categories: security, cloudsecurity_cdr
- Docs: `packages/snyk/docs/README.md`

### SonicWall Firewall
- Name: `sonicwall_firewall`
- Path: `packages/sonicwall_firewall/`
- Description: Integration for SonicWall firewall logs
- Version: 1.22.0
- Categories: network, security, firewall_security
- Docs: `packages/sonicwall_firewall/docs/README.md`

### Sophos
- Name: `sophos`
- Path: `packages/sophos/`
- Description: Collect logs from Sophos with Elastic Agent.
- Version: 3.17.0
- Categories: security, network, firewall_security
- Docs: `packages/sophos/docs/README.md`

### Sophos Central
- Name: `sophos_central`
- Path: `packages/sophos_central/`
- Description: This Elastic integration collects logs from Sophos Central with Elastic Agent.
- Version: 1.21.0
- Categories: security, edr_xdr
- Docs: `packages/sophos_central/docs/README.md`

### Splunk
- Name: `splunk`
- Path: `packages/splunk/`
- Description: Collect logs from Splunk with Elastic Agent.
- Version: 1.0.1
- Categories: security, siem
- Docs: `packages/splunk/docs/README.md`

### Spring Boot
- Name: `spring_boot`
- Path: `packages/spring_boot/`
- Description: This Elastic integration collects logs and metrics from Spring Boot integration.
- Version: 1.9.1
- Categories: observability, java_observability
- Docs: `packages/spring_boot/docs/README.md`

### SpyCloud Enterprise Protection
- Name: `spycloud`
- Path: `packages/spycloud/`
- Description: Collect data from SpyCloud Enterprise Protection with Elastic Agent.
- Version: 1.6.0
- Categories: security
- Docs: `packages/spycloud/docs/README.md`

### SQL Input
- Name: `sql`
- Path: `packages/sql_input/`
- Description: Collects Metrics by querying SQL Databases
- Version: 1.1.0
- Categories: custom, observability
- Docs: `packages/sql_input/docs/README.md`

### SQL Server OpenTelemetry Input Package
- Name: `sql_server_input_otel`
- Path: `packages/sql_server_input_otel/`
- Description: Collect SQL Server metrics and logs using OpenTelemetry Collector
- Version: 0.1.1
- Categories: datastore, observability, opentelemetry
- Docs: `packages/sql_server_input_otel/docs/README.md`

### Squid Proxy
- Name: `squid`
- Path: `packages/squid/`
- Description: Collect and parse logs from Squid devices with Elastic Agent.
- Version: 1.5.0
- Docs: `packages/squid/docs/README.md`

### STAN
- Name: `stan`
- Path: `packages/stan/`
- Description: Collect logs and metrics from STAN servers with Elastic Agent.
- Version: 1.11.0
- Categories: observability
- Docs: `packages/stan/docs/README.md`

### StatsD Input
- Name: `statsd_input`
- Path: `packages/statsd_input/`
- Description: StatsD Input Package
- Version: 1.0.0
- Categories: observability, custom
- Docs: `packages/statsd_input/docs/README.md`

### StatsD OpenTelemetry Input Package
- Name: `statsd_input_otel`
- Path: `packages/statsd_input_otel/`
- Description: StatsD OpenTelemetry Input Package
- Version: 0.1.0
- Categories: observability, opentelemetry, custom
- Docs: `packages/statsd_input_otel/docs/README.md`

### StormShield SNS
- Name: `stormshield`
- Path: `packages/stormshield/`
- Description: Stormshield SNS integration.
- Version: 1.5.1
- Categories: network, security, firewall_security
- Docs: `packages/stormshield/docs/README.md`

### Sublime Security
- Name: `sublime_security`
- Path: `packages/sublime_security/`
- Description: Collect logs from Sublime Security with Elastic Agent.
- Version: 1.11.2
- Categories: security, email_security
- Docs: `packages/sublime_security/docs/README.md`

### Suricata
- Name: `suricata`
- Path: `packages/suricata/`
- Description: Collect logs from Suricata with Elastic Agent.
- Version: 2.27.0
- Categories: network, security, ids_ips
- Docs: `packages/suricata/docs/README.md`

### Swimlane Turbine
- Name: `swimlane`
- Path: `packages/swimlane/`
- Description: Collect Swimlane Turbine Audit logs with Elastic Agent
- Version: 0.4.2
- Categories: security
- Docs: `packages/swimlane/docs/README.md`

### Symantec Endpoint Protection
- Name: `symantec_endpoint`
- Path: `packages/symantec_endpoint/`
- Description: Collect logs from Symantec Endpoint Protection with Elastic Agent.
- Version: 2.20.0
- Categories: security, edr_xdr
- Docs: `packages/symantec_endpoint/docs/README.md`

### Symantec Endpoint Security
- Name: `symantec_endpoint_security`
- Path: `packages/symantec_endpoint_security/`
- Description: Collect logs from Symantec Endpoint Security with Elastic Agent.
- Version: 1.14.2
- Categories: security, edr_xdr
- Docs: `packages/symantec_endpoint_security/docs/README.md`

### Elastic Synthetics
- Name: `synthetics`
- Path: `packages/synthetics/`
- Description: Internal Elastic integration for providing access to private locations.
- Version: 1.6.1
- Categories: observability
- Docs: `packages/synthetics/docs/README.md`

### Elastic Synthetics Dashboards
- Name: `synthetics_dashboards`
- Path: `packages/synthetics_dashboards/`
- Description: Explore Elastic Synthetics metrics with these dashboards.
- Version: 1.0.1
- Docs: `packages/synthetics_dashboards/docs/README.md`

### Sysdig
- Name: `sysdig`
- Path: `packages/sysdig/`
- Description: Collect logs from Sysdig using Elastic Agent.
- Version: 2.3.0
- Categories: containers, kubernetes, monitoring
- Docs: `packages/sysdig/docs/README.md`

### Syslog Router
- Name: `syslog_router`
- Path: `packages/syslog_router/`
- Description: Route syslog events to integrations with Elastic Agent.
- Version: 1.0.1
- Categories: custom
- Docs: `packages/syslog_router/docs/README.md`

### Sysmon for Linux
- Name: `sysmon_linux`
- Path: `packages/sysmon_linux/`
- Description: Collect Sysmon Linux logs with Elastic Agent.
- Version: 1.9.0
- Categories: os_system, security
- Docs: `packages/sysmon_linux/docs/README.md`

### System
- Name: `system`
- Path: `packages/system/`
- Description: Collect system logs and metrics from your servers with Elastic Agent.
- Version: 2.17.0
- Categories: os_system
- Docs: `packages/system/docs/README.md`

### System Audit
- Name: `system_audit`
- Path: `packages/system_audit/`
- Description: Collect various logs & metrics from System Audit modules with Elastic Agent.
- Version: 1.11.0
- Categories: custom, os_system
- Docs: `packages/system_audit/docs/README.md`

### System OpenTelemetry Assets
- Name: `system_otel`
- Path: `packages/system_otel/`
- Description: Dashboards for the OpenTelemetry data collected with the `hostmetrics` receiver.
- Version: 0.2.7
- Categories: os_system
- Docs: `packages/system_otel/docs/README.md`

### Tanium
- Name: `tanium`
- Path: `packages/tanium/`
- Description: This Elastic integration collects logs from Tanium with Elastic Agent.
- Version: 1.17.0
- Categories: security
- Docs: `packages/tanium/docs/README.md`

### Custom TCP Logs
- Name: `tcp`
- Path: `packages/tcp/`
- Description: Collect raw TCP data from listening TCP port with Elastic Agent.
- Version: 2.3.0
- Categories: custom, custom_logs
- Docs: `packages/tcp/docs/README.md`

### Teleport
- Name: `teleport`
- Path: `packages/teleport/`
- Description: Collect logs from Teleport with Elastic Agent.
- Version: 1.6.0
- Categories: monitoring, network
- Docs: `packages/teleport/docs/README.md`

### Tenable Vulnerability Management
- Name: `tenable_io`
- Path: `packages/tenable_io/`
- Description: Collect logs from Tenable Vulnerability Management with Elastic Agent.
- Version: 4.10.0
- Categories: security, vulnerability_management, vulnerability_workflow, cloudsecurity_cdr
- Docs: `packages/tenable_io/docs/README.md`

### Tenable OT Security
- Name: `tenable_ot_security`
- Path: `packages/tenable_ot_security/`
- Description: Tenable OT Security
- Version: 2.0.0
- Categories: security
- Docs: `packages/tenable_ot_security/docs/README.md`

### Tenable Security Center
- Name: `tenable_sc`
- Path: `packages/tenable_sc/`
- Description: Collect data from Tenable Security Center with Elastic Agent.
- Version: 2.2.0
- Categories: security, vulnerability_management
- Docs: `packages/tenable_sc/docs/README.md`

### Tencent Cloud
- Name: `tencent_cloud`
- Path: `packages/tencent_cloud/`
- Description: 从腾讯云的 COS 中采集基础设施日志
- Version: 0.2.0
- Categories: security, iam, cloud, observability
- Docs: `packages/tencent_cloud/docs/README.md`

### Cilium Tetragon
- Name: `cilium_tetragon`
- Path: `packages/tetragon/`
- Description: Collect Cilium Tetragon logs from Kubernetes environments.
- Version: 0.4.0
- Categories: security, cloud, cloudsecurity_cdr, kubernetes
- Docs: `packages/tetragon/docs/README.md`

### Threat Map
- Name: `threat_map`
- Path: `packages/threat_map/`
- Description: The Threat Map integration includes a dashboard for analyzing network traffic data.
- Version: 1.1.0
- Categories: custom, security
- Docs: `packages/threat_map/docs/README.md`

### Thycotic Secret Server
- Name: `thycotic_ss`
- Path: `packages/thycotic_ss/`
- Description: Thycotic Secret Server logs
- Version: 1.12.1
- Categories: security
- Docs: `packages/thycotic_ss/docs/README.md`

### abuse.ch
- Name: `ti_abusech`
- Path: `packages/ti_abusech/`
- Description: Ingest threat intelligence indicators from URL Haus, Malware Bazaar, and Threat Fox feeds with Elastic Agent.
- Version: 3.6.0
- Categories: security, threat_intel
- Docs: `packages/ti_abusech/docs/README.md`

### Anomali ThreatStream
- Name: `ti_anomali`
- Path: `packages/ti_anomali/`
- Description: Ingest threat intelligence indicators from Anomali ThreatStream with Elastic Agent.
- Version: 2.6.1
- Categories: security, threat_intel
- Docs: `packages/ti_anomali/docs/README.md`

### ANY.RUN Threat Intelligence Feeds
- Name: `ti_anyrun`
- Path: `packages/ti_anyrun/`
- Description: Ingest Threat Intelligence indicators from ANY.RUN TI Feeds with Elastic Agent
- Version: 1.0.1
- Categories: security, threat_intel
- Docs: `packages/ti_anyrun/docs/README.md`

### Collective Intelligence Framework v3
- Name: `ti_cif3`
- Path: `packages/ti_cif3/`
- Description: Ingest threat indicators from a Collective Intelligence Framework v3 instance with Elastic Agent.
- Version: 1.18.2
- Categories: security, threat_intel
- Docs: `packages/ti_cif3/docs/README.md`

### CrowdStrike Falcon Intelligence
- Name: `ti_crowdstrike`
- Path: `packages/ti_crowdstrike/`
- Description: Collect logs from CrowdStrike Falcon Intelligence with Elastic Agent.
- Version: 2.7.1
- Categories: security, threat_intel
- Docs: `packages/ti_crowdstrike/docs/README.md`

### Custom Threat Intelligence
- Name: `ti_custom`
- Path: `packages/ti_custom/`
- Description: Ingest threat intelligence data in STIX 2.1 format with Elastic Agent
- Version: 1.5.0
- Categories: custom, security, threat_intel
- Docs: `packages/ti_custom/docs/README.md`

### Cybersixgill
- Name: `ti_cybersixgill`
- Path: `packages/ti_cybersixgill/`
- Description: Ingest threat intelligence indicators from Cybersixgill with Elastic Agent.
- Version: 1.34.1
- Categories: security, threat_intel
- Docs: `packages/ti_cybersixgill/docs/README.md`

### Cyware Intel Exchange
- Name: `ti_cyware_intel_exchange`
- Path: `packages/ti_cyware_intel_exchange/`
- Description: Collect logs from Cyware Intel Exchange with Elastic Agent.
- Version: 0.2.0
- Docs: `packages/ti_cyware_intel_exchange/docs/README.md`

### DomainTools Feeds
- Name: `ti_domaintools`
- Path: `packages/ti_domaintools/`
- Description: DomainTools Feeds provide data on the different stages of the domain lifecycle: from first-observed in the wild, to newly re-activated after a period of quiet.
- Version: 1.3.0
- Categories: security, threat_intel
- Docs: `packages/ti_domaintools/docs/README.md`

### EclecticIQ
- Name: `ti_eclecticiq`
- Path: `packages/ti_eclecticiq/`
- Description: Ingest threat intelligence from EclecticIQ with Elastic Agent
- Version: 1.5.0
- Categories: security, threat_intel
- Docs: `packages/ti_eclecticiq/docs/README.md`

### ESET Threat Intelligence
- Name: `ti_eset`
- Path: `packages/ti_eset/`
- Description: Ingest threat intelligence indicators from ESET Threat Intelligence with Elastic Agent.
- Version: 1.9.0
- Categories: security, threat_intel
- Docs: `packages/ti_eset/docs/README.md`

### Flashpoint
- Name: `ti_flashpoint`
- Path: `packages/ti_flashpoint/`
- Description: Collect logs from Flashpoint with Elastic Agent.
- Version: 0.1.0
- Categories: security, threat_intel
- Docs: `packages/ti_flashpoint/docs/README.md`

### Google Threat Intelligence
- Name: `ti_google_threat_intelligence`
- Path: `packages/ti_google_threat_intelligence/`
- Description: Collect Threat Intelligence Events from Google Threat Intelligence using Elastic Agent, and perform enrichment on Elasticsearch by correlating Indicators of Compromise (IOCs).
- Version: 0.8.1
- Categories: security, threat_intel
- Docs: `packages/ti_google_threat_intelligence/docs/README.md`

### GreyNoise
- Name: `ti_greynoise`
- Path: `packages/ti_greynoise/`
- Description: Collect Threat Intelligence Indicators from GreyNoise using Elastic Agent, and perform enrichment on Elasticsearch by correlating Indicators of Compromise (IOCs).
- Version: 0.7.3
- Categories: threat_intel, security
- Docs: `packages/ti_greynoise/docs/README.md`

### Maltiverse
- Name: `ti_maltiverse`
- Path: `packages/ti_maltiverse/`
- Description: Ingest threat intelligence indicators from Maltiverse feeds with Elastic Agent
- Version: 1.6.0
- Categories: security, threat_intel
- Docs: `packages/ti_maltiverse/docs/README.md`

### Mandiant Advantage
- Name: `ti_mandiant_advantage`
- Path: `packages/ti_mandiant_advantage/`
- Description: Collect Threat Intelligence from products within the Mandiant Advantage platform.
- Version: 1.10.0
- Categories: threat_intel, security
- Docs: `packages/ti_mandiant_advantage/docs/README.md`

### MISP
- Name: `ti_misp`
- Path: `packages/ti_misp/`
- Description: Ingest threat intelligence indicators from MISP platform with Elastic Agent.
- Version: 1.42.0
- Categories: security, threat_intel
- Docs: `packages/ti_misp/docs/README.md`

### OpenCTI
- Name: `ti_opencti`
- Path: `packages/ti_opencti/`
- Description: Ingest threat intelligence indicators from OpenCTI with Elastic Agent.
- Version: 2.13.0
- Categories: security, threat_intel
- Docs: `packages/ti_opencti/docs/README.md`

### AlienVault OTX
- Name: `ti_otx`
- Path: `packages/ti_otx/`
- Description: Ingest threat intelligence indicators from AlienVault Open Threat Exchange (OTX) with Elastic Agent.
- Version: 1.30.1
- Categories: security, threat_intel
- Docs: `packages/ti_otx/docs/README.md`

### Rapid7 Threat Command
- Name: `ti_rapid7_threat_command`
- Path: `packages/ti_rapid7_threat_command/`
- Description: Collect threat intelligence from Threat Command API with Elastic Agent.
- Version: 2.8.0
- Categories: security, threat_intel
- Docs: `packages/ti_rapid7_threat_command/docs/README.md`

### Recorded Future
- Name: `ti_recordedfuture`
- Path: `packages/ti_recordedfuture/`
- Description: Ingest threat intelligence and alert data from Recorded Future with Elastic Agent.
- Version: 2.4.2
- Categories: security, threat_intel
- Docs: `packages/ti_recordedfuture/docs/README.md`

### Strider Shield
- Name: `ti_strider`
- Path: `packages/ti_strider/`
- Description: Ingest threat intelligence indicators from Strider Shield with Elastic Agent.
- Version: 0.0.1
- Docs: `packages/ti_strider/docs/README.md`

### ThreatConnect
- Name: `ti_threatconnect`
- Path: `packages/ti_threatconnect/`
- Description: Collects Indicators from ThreatConnect using the Elastic Agent and saves them as logs inside Elastic
- Version: 2.0.0
- Categories: security, threat_intel
- Docs: `packages/ti_threatconnect/docs/README.md`

### ThreatQuotient
- Name: `ti_threatq`
- Path: `packages/ti_threatq/`
- Description: Ingest threat intelligence indicators from ThreatQuotient with Elastic Agent.
- Version: 1.37.1
- Categories: security, threat_intel
- Docs: `packages/ti_threatq/docs/README.md`

### Threat Intelligence Utilities
- Name: `ti_util`
- Path: `packages/ti_util/`
- Description: Prebuilt Threat Intelligence dashboard for Elastic Security
- Version: 1.7.1
- Categories: security, threat_intel
- Docs: `packages/ti_util/docs/README.md`

### Tines
- Name: `tines`
- Path: `packages/tines/`
- Description: Tines Logs & Time Saved Reports
- Version: 1.16.0
- Categories: cloud, security
- Docs: `packages/tines/docs/README.md`

### Tomcat NetWitness Logs (Deprecated)
- Name: `tomcat`
- Path: `packages/tomcat/`
- Description: Collect and parse logs from Apache Tomcat servers with Elastic Agent.
- Version: 1.14.0
- Categories: web, observability
- Docs: `packages/tomcat/docs/README.md`

### Traefik
- Name: `traefik`
- Path: `packages/traefik/`
- Description: Collect logs from Traefik servers with Elastic Agent.
- Version: 2.7.0
- Categories: observability
- Docs: `packages/traefik/docs/README.md`

### Traefik OpenTelemetry Assets
- Name: `traefik_otel`
- Path: `packages/traefik_otel/`
- Description: Traefik Assets for OpenTelemetry Collector
- Version: 0.1.0
- Categories: opentelemetry, observability
- Docs: `packages/traefik_otel/docs/README.md`

### Trellix EDR Cloud
- Name: `trellix_edr_cloud`
- Path: `packages/trellix_edr_cloud/`
- Description: Collect logs from Trellix EDR Cloud with Elastic Agent.
- Version: 1.9.0
- Categories: cloud, security
- Docs: `packages/trellix_edr_cloud/docs/README.md`

### Trellix ePO Cloud
- Name: `trellix_epo_cloud`
- Path: `packages/trellix_epo_cloud/`
- Description: Collect logs from Trellix ePO Cloud with Elastic Agent.
- Version: 1.15.0
- Categories: security
- Docs: `packages/trellix_epo_cloud/docs/README.md`

### TrendAI Vision One
- Name: `trend_micro_vision_one`
- Path: `packages/trend_micro_vision_one/`
- Description: Collect logs from TrendAI Vision One with Elastic Agent.
- Version: 2.11.0
- Categories: security, edr_xdr
- Docs: `packages/trend_micro_vision_one/docs/README.md`

### TrendAI Deep Security
- Name: `trendmicro`
- Path: `packages/trendmicro/`
- Description: Collect logs from TrendAI Deep Security with Elastic Agent.
- Version: 2.8.2
- Categories: network, edr_xdr, security
- Docs: `packages/trendmicro/docs/README.md`

### TYCHON Agentless
- Name: `tychon`
- Path: `packages/tychon/`
- Description: Collect complete master endpoint datasets including vulnerability and STIG to comply with DISA endpoint requirements and C2C without adding services to your endpoints.
- Version: 1.1.0
- Categories: security, config_management, vulnerability_management
- Docs: `packages/tychon/docs/README.md`

### Custom UDP Logs
- Name: `udp`
- Path: `packages/udp/`
- Description: Collect raw UDP data from listening UDP port with Elastic Agent.
- Version: 2.5.0
- Categories: custom, custom_logs
- Docs: `packages/udp/docs/README.md`

### Custom macOS Unified Logs
- Name: `unifiedlogs`
- Path: `packages/unifiedlogs/`
- Description: Collect and parse logs from macOS unified logs with Elastic Agent.
- Version: 0.5.1
- Categories: custom, os_system
- Docs: `packages/unifiedlogs/docs/README.md`

### Universal Profiling Agent
- Name: `profiler_agent`
- Path: `packages/universal_profiling_agent/`
- Description: Fleet-wide, whole-system, continuous profiling with zero instrumentation.
- Version: 8.17.3
- Categories: elastic_stack, monitoring
- Docs: `packages/universal_profiling_agent/docs/README.md`

### Universal Profiling Collector
- Name: `profiler_collector`
- Path: `packages/universal_profiling_collector/`
- Description: Fleet-wide, whole-system, continuous profiling with zero instrumentation.
- Version: 8.17.3
- Categories: elastic_stack, monitoring
- Docs: `packages/universal_profiling_collector/docs/README.md`

### Universal Profiling Symbolizer
- Name: `profiler_symbolizer`
- Path: `packages/universal_profiling_symbolizer/`
- Description: Fleet-wide, whole-system, continuous profiling with zero instrumentation.
- Version: 8.17.3
- Categories: elastic_stack, monitoring
- Docs: `packages/universal_profiling_symbolizer/docs/README.md`

### Varonis
- Name: `varonis`
- Path: `packages/varonis/`
- Description: Collect Varonis syslog alerts using TCP/UDP input.
- Version: 1.0.0
- Categories: security
- Docs: `packages/varonis/docs/README.md`

### Vectra Detect
- Name: `vectra_detect`
- Path: `packages/vectra_detect/`
- Description: Collect logs from Vectra Detect with Elastic Agent.
- Version: 1.14.0
- Categories: security, network_security
- Docs: `packages/vectra_detect/docs/README.md`

### Vectra RUX
- Name: `vectra_rux`
- Path: `packages/vectra_rux/`
- Description: Collect logs from Vectra RUX with Elastic Agent.
- Version: 0.3.3
- Categories: security, edr_xdr
- Docs: `packages/vectra_rux/docs/README.md`

### Permission Verifier
- Name: `verifier_otel`
- Path: `packages/verifier_otel/`
- Description: Verify identity federation based integration permissions and report results to Elasticsearch using the Verifier receiver of the OTel Collector.
- Version: 0.0.1
- Categories: monitoring, security, opentelemetry, cloud
- Docs: `packages/verifier_otel/docs/README.md`

### VMware vSphere
- Name: `vsphere`
- Path: `packages/vsphere/`
- Description: This Elastic integration collects metrics and logs from vSphere/vCenter servers
- Version: 1.24.0
- Categories: observability, virtualization
- Docs: `packages/vsphere/docs/README.md`

### VMware vSphere OpenTelemetry Assets
- Name: `vsphere_otel`
- Path: `packages/vsphere_otel/`
- Description: VMware vSphere Assets for OpenTelemetry Collector
- Version: 0.1.0
- Categories: observability, opentelemetry, virtualization
- Docs: `packages/vsphere_otel/docs/README.md`

### WatchGuard Firebox
- Name: `watchguard_firebox`
- Path: `packages/watchguard_firebox/`
- Description: Collect logs from WatchGuard Firebox with Elastic Agent.
- Version: 1.6.3
- Categories: security, network, firewall_security
- Docs: `packages/watchguard_firebox/docs/README.md`

### Custom Websocket logs
- Name: `websocket`
- Path: `packages/websocket/`
- Description: Collect custom events from a socket server with Elastic agent.
- Version: 1.0.1
- Categories: custom
- Docs: `packages/websocket/docs/README.md`

### WebSphere Application Server
- Name: `websphere_application_server`
- Path: `packages/websphere_application_server/`
- Description: Collects metrics from IBM WebSphere Application Server with Elastic Agent.
- Version: 1.6.1
- Categories: websphere, observability
- Docs: `packages/websphere_application_server/docs/README.md`

### Windows
- Name: `windows`
- Path: `packages/windows/`
- Description: Collect logs and metrics from Windows OS and services with Elastic Agent.
- Version: 3.8.3
- Categories: os_system, security
- Docs: `packages/windows/docs/README.md`

### Custom Windows ETW logs
- Name: `windows_etw`
- Path: `packages/windows_etw/`
- Description: Collect and parse logs from any Windows ETW provider with Elastic Agent.
- Version: 1.0.0
- Categories: custom, os_system
- Docs: `packages/windows_etw/docs/README.md`

### Custom Windows Event Logs
- Name: `winlog`
- Path: `packages/winlog/`
- Description: Collect and parse logs from any Windows event log channel with Elastic Agent.
- Version: 2.6.0
- Categories: custom, os_system
- Docs: `packages/winlog/docs/README.md`

### WithSecure Elements
- Name: `withsecure_elements`
- Path: `packages/withsecure_elements/`
- Description: Ingest WithSecure Elements incidents and security events data
- Version: 0.2.0
- Categories: security, edr_xdr
- Docs: `packages/withsecure_elements/docs/README.md`

### Wiz
- Name: `wiz`
- Path: `packages/wiz/`
- Description: Collect logs from Wiz with Elastic Agent.
- Version: 4.2.0
- Categories: security, cloudsecurity_cdr, vulnerability_workflow, misconfiguration_workflow
- Docs: `packages/wiz/docs/README.md`

### Custom WMI Input Package
- Name: `wmi`
- Path: `packages/wmi/`
- Description: Custom WMI Input Package
- Version: 0.0.2
- Categories: observability, custom
- Docs: `packages/wmi/docs/README.md`

### Zeek
- Name: `zeek`
- Path: `packages/zeek/`
- Description: Collect logs from Zeek with Elastic Agent.
- Version: 5.0.0
- Categories: network, security
- Docs: `packages/zeek/docs/README.md`

### ZeroFox
- Name: `zerofox`
- Path: `packages/zerofox/`
- Description: Collect logs from ZeroFox with Elastic Agent.
- Version: 1.29.0
- Categories: security
- Docs: `packages/zerofox/docs/README.md`

### Zero Networks
- Name: `zeronetworks`
- Path: `packages/zeronetworks/`
- Description: Zero Networks Logs integration
- Version: 1.19.0
- Categories: security
- Docs: `packages/zeronetworks/docs/README.md`

### ZooKeeper Metrics
- Name: `zookeeper`
- Path: `packages/zookeeper/`
- Description: Collect metrics from ZooKeeper service with Elastic Agent.
- Version: 1.14.0
- Categories: observability
- Docs: `packages/zookeeper/docs/README.md`

### Zookeeper OTel Assets
- Name: `zookeeper_otel`
- Path: `packages/zookeeper_otel/`
- Description: Zookeeper OTel Assets
- Version: 0.1.1
- Categories: observability, opentelemetry
- Docs: `packages/zookeeper_otel/docs/README.md`

### Zoom
- Name: `zoom`
- Path: `packages/zoom/`
- Description: Collect logs from Zoom with Elastic Agent.
- Version: 1.23.0
- Categories: security, productivity_security
- Docs: `packages/zoom/docs/README.md`

### Zscaler Internet Access
- Name: `zscaler_zia`
- Path: `packages/zscaler_zia/`
- Description: Collect logs from Zscaler Internet Access (ZIA) with Elastic Agent.
- Version: 3.17.1
- Categories: security, network
- Docs: `packages/zscaler_zia/docs/README.md`

### Zscaler Private Access
- Name: `zscaler_zpa`
- Path: `packages/zscaler_zpa/`
- Description: Collect logs from Zscaler Private Access (ZPA) with Elastic Agent.
- Version: 1.23.3
- Categories: security, network, vpn_security
- Docs: `packages/zscaler_zpa/docs/README.md`


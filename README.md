# Oracle Integration (oracle-integration)
Oracle Integration provides native connectivity to Oracle and non-Oracle Software as a Service (SaaS) and on-premises applications, such as Oracle ERP Cloud, Oracle Service Cloud, HCM Cloud, Salesforce, Workday, EBS, SAP, NetSuite and others. It combines application integration, process automation, visual application building, and integration analytics into a single unified cloud service.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/oracle-integration/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - API Management, Automation, B2B Integration, Cloud Integration, Enterprise Integration, Integration, iPaaS, Process Automation

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-18

## APIs

### Oracle Integration Developer API
Developer API for Oracle Integration 3 providing day-to-day management of integrations, connections, packages, libraries, lookups, certificates, scheduled integrations, monitoring, B2B trading partner operations, and rapid adapter building.

**Human URL:** [https://docs.oracle.com/en/cloud/paas/application-integration/rest-api/index.html](https://docs.oracle.com/en/cloud/paas/application-integration/rest-api/index.html)

#### Tags:

 - B2B, Connections, Integration Management, Monitoring, Orchestration, Packages, REST API, Scheduled Integrations

#### Properties

- [Documentation](https://docs.oracle.com/en/cloud/paas/application-integration/rest-api/index.html)
- [APIReference](https://docs.oracle.com/en/cloud/paas/application-integration/rest-api/rest-endpoints.html)
- [Authentication](https://docs.oracle.com/en/cloud/paas/application-integration/rest-api/Authentication.html)
- [OpenAPI](openapi/oracle-integration-developer-api.yaml)
- [JSONSchema - Connection Schema](json-schema/developer-api-connection-schema.json)
- [JSONSchema - Integration Schema](json-schema/developer-api-integration-schema.json)
- [JSONSchema - Monitoring Instance Schema](json-schema/developer-api-monitoring-instance-schema.json)
- [JSONSchema - Trading Partner Schema](json-schema/developer-api-trading-partner-schema.json)
- [JSONLD](json-ld/oracle-integration-developer-api-context.jsonld)

### Oracle Integration Process Automation API
REST API for Oracle Cloud Infrastructure Process Automation enabling management of process definitions, process instances, tasks, decision models, dynamic processes, identities, spaces, analytics, and QuickStart applications.

**Human URL:** [https://docs.oracle.com/en/cloud/paas/process-automation/rest-api-proca/index.html](https://docs.oracle.com/en/cloud/paas/process-automation/rest-api-proca/index.html)

#### Tags:

 - BPM, Decision Models, Process Automation, Tasks, Workflows

#### Properties

- [Documentation](https://docs.oracle.com/en/cloud/paas/process-automation/rest-api-proca/index.html)
- [APIReference](https://docs.oracle.com/en/cloud/paas/process-automation/rest-api-proca/rest-endpoints.html)
- [OpenAPI](openapi/oracle-integration-process-automation-api.yaml)
- [JSONSchema - Process Instance Schema](json-schema/process-automation-api-process-instance-schema.json)
- [JSONSchema - Task Schema](json-schema/process-automation-api-task-schema.json)
- [JSONLD](json-ld/oracle-integration-process-automation-api-context.jsonld)

### Oracle Integration File Server API
REST API for configuring and administering the Oracle Integration File Server, an SFTP-compliant file repository for managing file-based integrations.

**Human URL:** [https://docs.oracle.com/en/cloud/paas/application-integration/rest-api-fs/index.html](https://docs.oracle.com/en/cloud/paas/application-integration/rest-api-fs/index.html)

#### Tags:

 - File Management, File Server, SFTP

#### Properties

- [Documentation](https://docs.oracle.com/en/cloud/paas/application-integration/rest-api-fs/index.html)

### Oracle Integration Administrative API
OCI control plane API for provisioning and managing Oracle Integration instances, custom endpoints, and data retention configuration.

**Human URL:** [https://docs.oracle.com/en-us/iaas/api/#/en/integration/20190131/](https://docs.oracle.com/en-us/iaas/api/#/en/integration/20190131/)

#### Tags:

 - Administration, Lifecycle Management, Provisioning

#### Properties

- [Documentation](https://docs.oracle.com/en-us/iaas/api/#/en/integration/20190131/)
- [APIReference](https://docs.oracle.com/en-us/iaas/api/#/en/integration/20190131/)

## Common Properties

- [Portal](https://cloud.oracle.com/integration)
- [GettingStarted](https://docs.oracle.com/en/cloud/paas/application-integration/oracle-integration-oci/explore-oracle-integration-apis.html)
- [Tutorials](https://docs.oracle.com/en/cloud/paas/integration-cloud/tutorials.html)
- [Documentation](https://docs.oracle.com/en/cloud/paas/application-integration/index.html)
- [Blog](https://blogs.oracle.com/integration/)
- [ChangeLog](https://docs.oracle.com/en/cloud/paas/integration-cloud/whats-new/)
- [Support](https://www.oracle.com/support/)
- [TermsOfService](https://www.oracle.com/legal/terms.html)
- [PrivacyPolicy](https://www.oracle.com/legal/privacy/)
- [StatusPage](https://ocistatus.oraclecloud.com/)
- [Pricing](https://www.oracle.com/integration/pricing/)
- [Console](https://cloud.oracle.com/integration)
- [SDK - OCI SDKs](https://docs.oracle.com/en-us/iaas/Content/API/Concepts/sdks.htm)
- [CLI - OCI CLI](https://github.com/oracle/oci-cli)
- [GitHubOrganization](https://github.com/oracle)
- [GitHubRepository - OCI CLI Repository](https://github.com/oracle/oci-cli)
- [GitHubRepository - Python SDK Repository](https://github.com/oracle/oci-python-sdk)
- [GitHubRepository - Go SDK Repository](https://github.com/oracle/oci-go-sdk)
- [Training](https://education.oracle.com/)
- [Marketplace](https://cloudmarketplace.oracle.com/marketplace/en_US/homeLinkPage)

## Features

| Name | Description |
|------|-------------|
| Prebuilt Integrations | Library of prebuilt integration recipes and adapters for rapid deployment of common integration patterns. |
| Application Adapters | Native connectivity to Oracle SaaS, on-premises applications, and third-party services including Salesforce, SAP, Workday, and ServiceNow. |
| Visual Integration Designer | Low-code drag-and-drop integration designer for building integration flows without extensive coding. |
| B2B Document Exchange | EDI and B2B document processing with support for trading partner management, document standards, and agreement lifecycle. |
| Process Automation | Business process management with structured and unstructured workflows, case management, and task management. |
| Decision Modeling | DMN-based decision model management for business rules execution and deployment. |
| Scheduled Integrations | Time-based scheduling of integration flows with pause, resume, start, and stop controls. |
| Integration Monitoring | Real-time monitoring of integration instances, error tracking, activity streams, and audit records. |
| File Server | SFTP-compliant embedded file server for file-based integration scenarios. |
| Rapid Adapter Builder | Custom adapter development framework for building reusable connectivity to proprietary or niche systems. |
| AI Agents | AI agent capabilities within integration projects for intelligent automation patterns and prompt templates. |
| Machine Learning Recommendations | ML-based guidance and recommendations for building and optimizing integrations. |
| Integration Analytics | Built-in analytics and process analytics with custom query builders and data visualization. |
| FHIR Support | Native Fast Healthcare Interoperability Resources support for healthcare integration workflows. |

## Use Cases

| Name | Description |
|------|-------------|
| SaaS Application Integration | Connect Oracle SaaS applications like ERP Cloud, HCM Cloud, and CX Cloud with third-party SaaS platforms. |
| ERP Integration | Integrate Oracle ERP Cloud or on-premises EBS with procurement, supply chain, and financial systems. |
| HCM Integration | Synchronize human capital management data across Oracle HCM Cloud, Workday, and other HR systems. |
| B2B Trading Partner Onboarding | Automate EDI-based trading partner setup, agreement management, and document exchange. |
| Process Automation | Automate business processes with approval workflows, case management, and task orchestration. |
| Healthcare Data Exchange | Build FHIR-compliant healthcare integration workflows for patient data exchange and interoperability. |
| Hybrid Cloud Integration | Connect on-premises applications to Oracle Cloud and third-party cloud services via connectivity agents. |
| File-Based Integration | Automate file transfers and processing with the embedded SFTP-compliant file server. |
| CI/CD For Integrations | Manage integration lifecycle with export, import, and deployment APIs for DevOps automation. |
| Real-Time Event Processing | Process events and messages in real time using event-driven integration patterns and stream analytics. |

## Integrations

| Name | Description |
|------|-------------|
| Oracle ERP Cloud | Native adapter for Oracle Enterprise Resource Planning Cloud including financials, procurement, and supply chain. |
| Oracle HCM Cloud | Native adapter for Oracle Human Capital Management Cloud for HR, payroll, and talent management. |
| Oracle CX Cloud | Native adapter for Oracle Customer Experience Cloud including sales, service, and marketing. |
| Oracle NetSuite | Native adapter for Oracle NetSuite ERP and CRM cloud services. |
| Salesforce | Prebuilt adapter for Salesforce CRM integration with Oracle cloud and on-premises applications. |
| SAP | Adapter for SAP ERP and S/4HANA integration via IDoc, BAPI, and RFC protocols. |
| Workday | Prebuilt adapter for Workday HCM and financial management integration. |
| ServiceNow | Adapter for ServiceNow ITSM and ITOM integration with Oracle applications. |
| Shopify | Adapter for Shopify e-commerce platform integration with order management and inventory systems. |
| Snowflake | Adapter for Snowflake data warehouse integration for analytics and data pipelines. |
| Microsoft Azure | Connectivity to Microsoft Azure services and applications for multi-cloud integration. |
| AWS | Connectivity to Amazon Web Services for multi-cloud integration scenarios. |
| Slack | Adapter for Slack messaging integration with workflow notifications and approvals. |
| JIRA | Adapter for Atlassian JIRA project management and issue tracking integration. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Oracle Integration Developer API](openapi/oracle-integration-developer-api.yaml)
- [Oracle Integration Process Automation API](openapi/oracle-integration-process-automation-api.yaml)

### JSON Schema

- [Connection](json-schema/developer-api-connection-schema.json)
- [Integration](json-schema/developer-api-integration-schema.json)
- [MonitoringInstance](json-schema/developer-api-monitoring-instance-schema.json)
- [TradingPartner](json-schema/developer-api-trading-partner-schema.json)
- [ProcessInstance](json-schema/process-automation-api-process-instance-schema.json)
- [Task](json-schema/process-automation-api-task-schema.json)

### JSON Structure

- [Connection](json-structure/developer-api-connection-structure.json)
- [Integration](json-structure/developer-api-integration-structure.json)
- [MonitoringInstance](json-structure/developer-api-monitoring-instance-structure.json)
- [TradingPartner](json-structure/developer-api-trading-partner-structure.json)
- [ProcessInstance](json-structure/process-automation-api-process-instance-structure.json)
- [Task](json-structure/process-automation-api-task-structure.json)

### JSON-LD

- [Developer API Context](json-ld/oracle-integration-developer-api-context.jsonld)
- [Process Automation API Context](json-ld/oracle-integration-process-automation-api-context.jsonld)

### Examples

- [Connection Example](examples/developer-api-connection-example.json)
- [Integration Example](examples/developer-api-integration-example.json)
- [MonitoringInstance Example](examples/developer-api-monitoring-instance-example.json)
- [TradingPartner Example](examples/developer-api-trading-partner-example.json)
- [ProcessInstance Example](examples/process-automation-api-process-instance-example.json)
- [Task Example](examples/process-automation-api-task-example.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Oracle Integration Developer API](capabilities/shared/developer-api.yaml) -- 18 operations for integration, connection, monitoring, and B2B management
- [Oracle Integration Process Automation API](capabilities/shared/process-automation-api.yaml) -- 10 operations for process, task, decision model, and analytics management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Integration Management](capabilities/integration-management.yaml) | Developer API + Process Automation API | 17 | Integration Developer, Platform Administrator |

## Vocabulary

- [Oracle Integration Vocabulary](vocabulary/oracle-integration-vocabulary.yaml) -- Unified taxonomy mapping 22 resources, 17 actions, 1 workflow, and 4 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Oracle Integration Spectral Rules](rules/oracle-integration-spectral-rules.yml) -- 38 rules across 13 categories enforcing Oracle Integration API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com

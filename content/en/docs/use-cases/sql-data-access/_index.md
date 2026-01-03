---
title: SQL Data Access
description: This is a database integration focused implementation of the Naftiko Capability, making APIs accessible via SQL, and common database connectors.
date: 2025-11-05
weight: 6
toc_hide: true
---
d
{{% pageinfo %}}
Unlocking the data available across many different SaaS services and legacy database connections for use in AI integrations.
{{% /pageinfo %}}

This use case seeks to consistently unlock the data companies currently depend upon across multiple third-party SaaS providers and a variety of existing database connections via JDBC and ODBC to ensure AI integrations have the data they require. Data today is spread across many internal and external systems, and making it consistently available as part of AI integrations has significantly slowed the delivery of new products and features.

Teams benefit from consistent SQL access to data sources via ODBC/JDBC interfaces, and expanding this access to third-party SaaS will help teams provide the context, resources, tooling, and data needed to deliver AI integrations across the enterprise. The capability and resulting engine deployment for this use case provides a unified, consolidated, and simplified approach to providing the data needed to power individual AI integrations within specific business domains.

**Google:** [Doc](https://docs.google.com/document/d/19RyQHGFPm4qWlRBfkXXFeX4GFOIFSRdvGtp330UxiQA/edit?tab=t.0#heading=h.1lcg6p9rm6it)

### Capability([Page](https://psychic-bassoon-z2vjvn4.pages.github.io/docs/capabilities/))
This outline describes the capability—or eventually an aggregate capability—to help define and deliver SQL access to internal data sources and third-party API--leveraging the capability metamodel to shape requirements and provide the context needed for AI integration.

#### Adapters
There are three capability adapters used to support this use case, with other adapters available.

* Source Port: HTTP Adapter(s)
* Artificial Intelligence Port: MCP Adapter
* Automation Port: OpenAPI Adapter
* Data Query Ports: SQL Adapter

#### Use Case

* **Pain**

    1. No Access to SaaS Data for AI Integration
    2. No Access to Data Sources for AIN Integration
    3. Unmanaged Usage
    4. Unmanaged Spend
    5. Unmanaged API Tokens
    6. Unmanaged Encryption
    7. Unmanaged Discovery

* **Gains**

    1. Access to SaaS Data via SQL
    2. Access to Data Sources via SQL
    3. Manage Budget Across
    4. Managed Risk Involved
    5. Optimize SaaS Usage
    6. Create More Visibility
    7. Create More Discovery
    8. Create More Reusability

* **Actor(s)**

    1. Architect
    2. Head of API Platform
    3. Head of AI
    4. Head of Engineering
    5. Head of Integration
    6. Head of Platform Engineering
    7. Data Scientist
    8. Analyst

### Services
These are the services used as part of the capability applied for this use case, but can be expanded as needed to support individual customers, and does not have to include all operations for each service APIs.

* GitHub ([Page](docs/services/github/))
* Atlassian Jira ([Page](docs/services/jira/))
* Amazon S3 ([Page](docs/services/amazon-s3/))
* Snowflake ([Page](docs/services/snowflake/))
* Google Apps ([Gmail](docs/services/gmail/), [Calendar](docs/services/google-calendar/), [Docs](docs/services/google-docs/), [Drive](docs/services/google-drive/), [Sheets](docs/services/google-sheets/))
* Microsoft Graph ([Page](docs/services/microsoft-graph/))
* Zoom ([Page](docs/services/zoom/))
* Facebook ([Page](docs/services/facebook/))
* Instagram ([Page](docs/services/intstagra/))
* LinkedIn ([Page](docs/services/linkedin/))

OpenAPI is available for all of these APIs, with others available on-demand. Next, we can build a list of which OpenAPI operationId we want to include as the available function list, which can be used by the HTTP adapter to connect to each service.

### Engine ([Page](docs/services/facebook/))
This is the information we are fleshing out about what is needed at the Nafitko Engine level to execute capabilities for this use case. So far, we have the outbound and inbound consumption policies, but should expand to include whatever else needed from the engine metamodel.

#### Outbound Consumption Policies

* API Authentication
* API Token Refresh
* API Rate Limiting
* API Pagination
* API Mocking
* Session Management

#### Inbound Consumption Policies

* Internal Client Authentication
* Internal Client Authorization
* Internal Quota Management
* Internal Rate Limitation
* Network Management
* Encryption
* Session Management

This engine definition is being used to develop content for the website and maintain documentation to support team work, but also eventually customers and the ecosystem. Next we can begin documenting each of the features via our documentation site.

### Fabric ([Page](docs/services/facebook/))
This is the information we need to flesh out what is needed at the Naftiko Fabric level for this use case. Taking our market research and Signals conversations, we can continue to expand and validate this list over time.

* Discovery ([Ford](https://turbo-goggles-5l9zlnj.pages.github.io/docs/targets/ford/)) - Explore and discover services and functions.
* Spending - Managing the spend across 3rd-party services.
* Security ([Ford](https://turbo-goggles-5l9zlnj.pages.github.io/docs/targets/ford/)) - Managing authentication and encryption across.
* Change - Managing the changes across any of the services.

We need to eventually validate everything here, and gather anything from other word to help get us closer to something we can talk with Naftiko Signals companies about what they will be paying for in 2027, or even in 2026. Expanding, validating, and shaping our commercial fabric.

### Narrative ([Cvent](https://turbo-goggles-5l9zlnj.pages.github.io/docs/targets/cvent/), [Ford](https://turbo-goggles-5l9zlnj.pages.github.io/docs/targets/ford/))
This is the narrative to support this use case, taking actual conversation with Naftiko Signals conversations and market research to produce and iterate upon a compelling narrative that we can share with investors, customers, and via other go to market activities.

**Title:** Our AI Proof of Concepts Keep Failing Because We Don't The Data We Need

**Body:**

[Need Narrative]

**References:** NONE
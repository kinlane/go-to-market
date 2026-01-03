---
title: Data Sovereignty
description: Actively control your data across the cloud and other platforms you depend upon.
date: 2025-11-05
weight: 6
toc_hide: true
---

{{% pageinfo %}}
Providing more control over company data that resides in 3rd-party systems and platforms.
{{% /pageinfo %}}

This use case focuses on empowering companies to take control of their data that resides across the third-party SaaS solutions they use regularly. The data sovereignty movement is centered on establishing more control over the data generated across the different services you depend on, ensuring data is integrated, migrated, and synced to data and object stores where a company has full control and access.

Data sovereignty enables teams to localize data and train local AI models using the data they produce across third-party platforms. This use case may be aligned with country or regional regulations, or it may simply be part of enterprise compliance programs. Data sovereignty investments have increased as part of the growth of AI integrations and the need for context across third-party systems, as well as the increasing value of data itself.

**Google:** [Doc](http://localhost:1313/docs/docs/use-cases/ai-model-context/)

### Capability ([Page](docs/services/facebook/))
This outline describes the capability—or eventually an aggregate capability—to help define and deliver MCP servers using third-party APIs. This capability uses the capability metamodel to shape requirements and provide the context needed for AI integration.

#### Adapters
There are three capability adapters used to support this use case, with other adapters available.

* Source Port: HTTP Adapter(s)
* Artificial Intelligence Port: MCP Adapter
* Automation Port: OpenAPI Adapter

#### Use Case

* **Pain**

    1. Regulatory Mandate for Data Sovereignty
    2. Regulatory Mandate for Data Sovereignty
    3. Unmanaged Discovery

* **Gains**

    1. Aggregate 3rd-Party SaaS data
    2. Create More Visibility
    3. Create More Discovery
    4. Create More Reusability 

* **Actor(s)**

    1. Architect
    2. Head of API Platform
    3. Head of AI
    4. Head of Engineering
    5. Head of Integration
    6. Head of Platform Engineering
    7. Compliance

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

- **Discovery** - Explore and discover capabilities.
- **Spending** - Managing the spend across APIs.
- **Security** - Managing authentication and encryption.
- **Change** - Managing the changes in services.
- **Scheduling** - Being able to manage the pulling of data.
- **Coverage** - Understanding the service coverage.
- **Regional** - Having a clear understanding of regions.

We need to eventually validate everything here, and gather anything from other word to help get us closer to something we can talk with Naftiko Signals companies about what they will be paying for in 2027, or even in 2026. Expanding, validating, and shaping our commercial fabric.

### Narrative ([Cvent](https://turbo-goggles-5l9zlnj.pages.github.io/docs/targets/cvent/), [Ford](https://turbo-goggles-5l9zlnj.pages.github.io/docs/targets/ford/))
This is the narrative to support this use case, taking actual conversation with Naftiko Signals conversations and market research to produce and iterate upon a compelling narrative that we can share with investors, customers, and via other go to market activities.

**Title:** We Need to Protect Our Valuable Data Assets

**Body:**

[Need Body]

**References:** NONE
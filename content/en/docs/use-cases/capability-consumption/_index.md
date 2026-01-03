---
title: Capability Consumption
description: This is the default use of Naftiko, providing a general purpose use case for managing any SaaS provider.
date: 2025-11-05
weight: 6
toc_hide: true
---

{{% pageinfo %}}
The general purpose use case that covers any SaaS service needed as part of integration.
{{% /pageinfo %}}

This use case is designed to cover the general needs of the enterprise when it comes to integration with third-party SaaS. This use case allows for the widest possible definition of what is needed within a single domain, enabling exploration of which third-party services are required. This use case tends to focus specifically on the cost, velocity, and risk concerns of leadership, then identifying the services that are of particular concern.

Teams need a way to centralize and standardize the usage and billing for third-party SaaS used as part of web, mobile, AI, or other types of applications. There is no consistent way to manage tokens, ensure encryption is used, and address other areas of concern when it comes to the risk across APIs. The capability consumption use case helps abstract away the general concerns of developers while providing the oversight leadership needs over different SaaS services.

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

    1. Copilot Leadership Mandate ([Cvent](https://turbo-goggles-5l9zlnj.pages.github.io/docs/targets/cvent/))
    2. MCP Leadership Mandate ([Ford](https://turbo-goggles-5l9zlnj.pages.github.io/docs/targets/ford/))
    3. Unmanaged Usage
    4. Unmanaged Spend
    5. Unmanaged API Tokens
    6. Unmanaged Encryption ([Ford](https://turbo-goggles-5l9zlnj.pages.github.io/docs/targets/ford/))
    7. Unmanaged Discovery ([Cvent](https://turbo-goggles-5l9zlnj.pages.github.io/docs/targets/cvent/), [Ford](https://turbo-goggles-5l9zlnj.pages.github.io/docs/targets/ford/))

* **Gains**

    1. Copilot Source of 3rd-party
    2. 3rd-Party MCP Available
    3. Manage Budget Across
    4. Managed Risk Involved
    5. Optimize SaaS Usage
    6. Create More Visibility ([Ford](https://turbo-goggles-5l9zlnj.pages.github.io/docs/targets/ford/))
    7. Create More Discovery ([Ford](https://turbo-goggles-5l9zlnj.pages.github.io/docs/targets/ford/))
    8. Create More Reusability ([[Chase](https://turbo-goggles-5l9zlnj.pages.github.io/docs/targets/chase/)](https://turbo-goggles-5l9zlnj.pages.github.io/docs/targets/chase/))

* **Actor(s)**

    1. Architect ([Cvent](https://turbo-goggles-5l9zlnj.pages.github.io/docs/targets/cvent/))
    2. Head of API Platform
    3. Head of AI ([Ford](https://turbo-goggles-5l9zlnj.pages.github.io/docs/targets/ford/))
    4. Head of Engineering
    5. Head of Integration
    6. Head of Platform Engineering

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

**Title:** Our Partners and Customers Need an AI Copilot

**Body:**



**References:** [Ford](https://turbo-goggles-5l9zlnj.pages.github.io/docs/targets/ford/), [Cvent](https://turbo-goggles-5l9zlnj.pages.github.io/docs/targets/cvent/), Goldman Sachs, [[Chase](https://turbo-goggles-5l9zlnj.pages.github.io/docs/targets/chase/)](https://turbo-goggles-5l9zlnj.pages.github.io/docs/targets/chase/)
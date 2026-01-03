---
title: AI Model Context
description: Provide more context by deploying an MCP server that has all the context needed to power artificial intelligence.
date: 2025-11-05
weight: 6
toc_hide: true
---

{{% pageinfo %}}
Targeting MCP deployment solutions based upon need from customer conversations.
{{% /pageinfo %}}

This use case focuses on providing Model Context Protocol (MCP) servers on top of common third-party engineering, business, marketing, and financial APIs using declarative capabilities that simplify onboarding and configuration, saving time. These simple, easy-to-use MCP servers have security and governance built in.

Teams need a reliable way to deliver MCP servers from internal and third-party APIs without having to discover and learn about each API and the technical details of integration. This use case provides the fundamentals for integrating legacy data and systems into artificial intelligence copilots and agents.

**Google:** [Doc](https://docs.google.com/document/d/19RyQHGFPm4qWlRBfkXXFeX4GFOIFSRdvGtp330UxiQA/edit?tab=t.0#heading=h.h8yoy5xyficq)

### Capability ([Page](https://psychic-bassoon-z2vjvn4.pages.github.io/docs/capabilities/))
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

We have been extremely successful with our API-first transformation over the last decade here at Acme Corp.. Our 500+ distributed engineers are roughly 75% design-first and are producing a solid base of OpenAPI-defined HTTP APIs, with Webhooks, GraphQL, gRPC, and Kafka APIs. Then earlier this year, the boss came and said we were going all-in on AI, and we needed a copilot for our partners and eventually our customers.

We didn't know what to do. We've spent the last six months rallying teams to produce compelling prototypes that would get us closer to something meeting our leadership's mandate for an AI copilot. Luckily, we've had a somewhat centralized API governance effort in motion for the last five years and were beginning to consider how we would also govern third-party APIs—the usage of Claude, ChatGPT, Gemini APIs, Hugging Face, Ollama, and local SLM/LLMs but also other third-party APIs delivered to any of those LLMs. This demonstrated that the problem was growing.

Clearly we needed MCP servers. Teams published many different solutions using existing OpenAPI and AsyncAPI specifications to generate MCP servers in various programming languages. As it stands today, there isn't any notion of discovery across these MCP servers. Teams don't have any consistent or organized way of doing MCP. Everything is only used internally so far, with mixed results across the copilots and agents being deployed on top of MCP servers. Like with our federated API development and our recent investment in our API platform, we need more standardization of MCP deployment alongside SDKs, Jupyter Notebooks, and other clients.

Nothing has made it to production—well, a handful of very safe, low-risk projects, but nothing customer-facing. The result of eight months of exploration is that we need more context to make our AI integrations work. We need the real-world context present in the third-party services we use each day available as part of our AI chats and agentic workflows. We also find that AI integrations are much more useful and relevant when they have a JDBC adapter to connect local databases in addition to source HTTP adapters, providing access to data they need—leaving us realizing we need more legacy data access as well. Right now, we are most concerned with giving teams guidance on how to consistently and dynamically generate MCP servers from existing OpenAPI and AsyncAPI artifacts—work that would benefit from guided, declarative, and composite set of capabilities that are mapped to various sources as defined by the consumers of our AI integrations.

Once we standardize how we deliver MCP servers across teams, we need a way to make them discoverable alongside other API resources. We need to encourage more reuse and interoperability, as well as discovery and onboarding across APIs and MCP servers—taking the base of OpenAPI-defined HTTP APIs, with Webhooks, GraphQL, gRPC, and Kafka APIs, and aggregating or splitting them up depending on their shape and form as reusable source capabilities that can be assembled into use-case and domain-specific composite capabilities. We are just learning and adapting right now, trying to do as much as we can with fewer team members by leveraging open-source solutions. In these uncertain times, we are most concerned with the complexity of our operations, maximizing productivity across short-handed teams, and managing risk and cost by leveraging AI automation. We need to be able to do more with less and do not have the time to learn new processes or purchase new services—we just need help.

**References:** [Ford](https://turbo-goggles-5l9zlnj.pages.github.io/docs/targets/ford/), [Cvent](https://turbo-goggles-5l9zlnj.pages.github.io/docs/targets/cvent/), Goldman Sachs, [[Chase](https://turbo-goggles-5l9zlnj.pages.github.io/docs/targets/chase/)](https://turbo-goggles-5l9zlnj.pages.github.io/docs/targets/chase/)
---
title: AI Model Mediation
description: Provide model routing across multiple API providers to manage cost, velocity, and risk with AI integrations.
date: 2025-11-05
weight: 6
toc_hide: true
---

{{% pageinfo %}}
Provide model routing across multiple API providers to manage cost, velocity, and risk with AI integrations.
{{% /pageinfo %}}

This use case focuses on managing different artificial intelligence models, providing an open-source alternative to OpenRouter that helps teams manage development across multiple public and private API models. Model routing is primarily done using the APIs of leading AI service providers, which has led to the emergence of companies like OpenRouter that broker the usage of different AI models from various providers for diverse business use cases.

Teams need a reliable way to deliver applications and automation using many different public or private, open-source or commercial models. This use case provides the fundamentals for integrating across multiple AI model providers and immediately gaining more control over how small and large language models are being used as part of applications, automation, and direct integrations—optimizing cost, velocity, and risk across AI integrations.

**Google:** [Doc](https://docs.google.com/document/d/19RyQHGFPm4qWlRBfkXXFeX4GFOIFSRdvGtp330UxiQA/edit?tab=t.0#heading=h.39toszmzdsxz)

### Capability([Page](https://psychic-bassoon-z2vjvn4.pages.github.io/docs/capabilities/))
This outline describes the capability—or eventually an aggregate capability—to help define and provide small and large language model routing across public and private AI integrations. This capability uses the capability metamodel to shape requirements and provide the context needed for AI integration across SLM and LLMs.

#### Adapters
There are three capability adapters used to support this use case, with other adapters available.

* Source Port: HTTP Adapter(s)
* Artificial Intelligence Port: MCP Adapter
* Automation Port: OpenAPI Adapter

#### Use Case

* **Pain**

    1. Bring AI Model Usage in House ([Ford](https://turbo-goggles-5l9zlnj.pages.github.io/docs/targets/ford/))
    3. Unmanaged AI Model Usage
    4. Unmanaged AI Model Spend
    5. Unmanaged API Tokens
    6. Unmanaged Encryption
    7. Unmanaged Discovery ([Cvent](https://turbo-goggles-5l9zlnj.pages.github.io/docs/targets/cvent/), [Ford](https://turbo-goggles-5l9zlnj.pages.github.io/docs/targets/ford/))

* **Gains**

    1. Switch to Internal SLMs/LLMs
    2. Reduce AI Provider Spend
    3. Manage Budget Across
    4. Managed Risk Involved
    5. Optimize AI Usage
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

* OpenAI ChatGPT ([Page](docs/services/openai/))
* Anthropic Claude ([Page](docs/services/claude/))
* Google Gemini ([Page](docs/services/gemini/))
* Hugging Face ([Page](docs/services/hugging-face/))
* Ollama  ([Page](docs/services/ollama/))

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

**Title:** 

**Body:**



**References:** [Ford](https://turbo-goggles-5l9zlnj.pages.github.io/docs/targets/ford/), [Cvent](https://turbo-goggles-5l9zlnj.pages.github.io/docs/targets/cvent/), Goldman Sachs, [[Chase](https://turbo-goggles-5l9zlnj.pages.github.io/docs/targets/chase/)](https://turbo-goggles-5l9zlnj.pages.github.io/docs/targets/chase/)
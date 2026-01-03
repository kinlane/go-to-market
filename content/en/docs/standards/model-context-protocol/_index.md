---
title: Model Context Protocol (MCP)
description: MCP (Model Context Protocol) is an open protocol that standardizes how applications provide context to large language models (LLMs). It offers a consistent way to connect AI models to diverse data sources and tools, enabling agents and complex workflows that link models to the outside world.
date: 2025-09-19
weight: 35
toc_hide: true
---

{{% pageinfo %}}
Allowing applications to connect to large language models (LLMs).
{{% /pageinfo %}}

MCP (Model Context Protocol) is an open protocol that standardizes how applications provide context to large language models (LLMs). It offers a consistent way to connect AI models to diverse data sources and tools, enabling agents and complex workflows that link models to the outside world.

Introduced by Anthropic as an open-source effort, MCP addresses the challenge of integrating AI models with external tools and data. It aims to serve as a universal “USB port” for AI, allowing models to access real-time information and perform actions.

MCP defines concepts and properties such as hosts, clients, servers, protocol negotiation, lifecycle, transports, authorization, resources, prompts, tools, sampling, roots, elicitation, progress, cancellation, errors, and logging—providing a standardized approach to connecting applications with LLMs.

The MCP community organizes around a GitHub repository (with issues and discussions), plus a Discord, blog, and RSS feed to track updates and changes to the specification.

MCP is seeing growing adoption among API and tooling providers for agent interactions. Many related API/AI specifications reference, integrate with, or overlap with MCP—despite the project being an open-source protocol currently stewarded by a single company, which has not been contributed to a foundation.

**Owner:** Anthropic 

**License:** MIT License

**Tags:** agents, workflows

**Properties:** hosts, clients, servers, protocols, negotiation, lifecycle, transports, authorization, resources, prompts, tools, sampling, roots, elicitation, progress, cancellation, errors, logging

**Website:** https://modelcontextprotocol.io/

**Standards:** JSON-RPC 2.0, JSON Schema
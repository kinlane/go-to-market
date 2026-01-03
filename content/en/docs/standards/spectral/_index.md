---
title: Spectral
description: Spectral is an open-source API linter for enforcing style guides and best practices across JSON Schema, OpenAPI, and AsyncAPI documents. It helps teams ensure consistency, quality, and adherence to organizational standards in API design and development.
date: 2025-09-19
weight: 60
toc_hide: true
---

{{% pageinfo %}}
Enforcing style guides across JSON artifacts to govern schema.
{{% /pageinfo %}}

Spectral is an open-source API linter for enforcing style guides and best practices across JSON Schema, OpenAPI, and AsyncAPI documents. It helps teams ensure consistency, quality, and adherence to organizational standards in API design and development.

While Spectral is a tool, its rules format is increasingly treated as a de facto standard. Spectral traces its roots to Speccy, an API linting engine created by Phil Sturgeon at WeWork. Phil later brought the concept to Stoplight, where Spectral and the next iteration of the rules format were developed; Stoplight was subsequently acquired by SmartBear.

With Spectral, you define rules and rulesets using properties such as given, then, description, message, severity, formats, recommended, and resolved. These can be applied to any JSON or YAML artifact, with primary adoption to date around OpenAPI and AsyncAPI.

The project’s GitHub repository hosts active issues and discussions, largely focused on the CLI. Development continues under SmartBear, including expanding how rules are applied across API operations and support for Arazzo workflow use cases.

Most commonly, Spectral is used to lint and govern OpenAPI and AsyncAPI specifications during design and development. It is expanding into Arazzo workflows and can be applied to any standardized JSON or YAML artifact validated with JSON Schema—making it a flexible foundation for governance across the API lifecycle.

**License:** Apache

**Tags:** Rules, Governance

**Properties:** rules, rulesets, given, then, description, message, severity, formats, recommended, and resolved properties

**GitHub:** https://github.com/stoplightio/spectral

**Standards:** JSON Schema
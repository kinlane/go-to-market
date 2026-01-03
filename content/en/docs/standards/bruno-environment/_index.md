---
title: Bruno Environment
description: A Bruno environment is a set of key–value variables that let you switch configurations—such as URLs, tokens, or credentials—so you can run the same API requests across different contexts like development, staging, or production.
date: 2025-11-24
weight: 16
toc_hide: true
---

{{% pageinfo %}}
A open-source client environment.
{{% /pageinfo %}}

A Bruno environment is a configurable set of key–value variables that allows you to run the same API requests across different deployment contexts, such as local development, staging, and production. Environments typically store values like base URLs, authentication tokens, headers, or other parameters that may change depending on where an API is being tested. By separating these values from the requests themselves, Bruno makes it easy to switch contexts, maintain cleaner collections, and ensure consistency when collaborating with others or automating API workflows.

**License:** MIT license

**Tags:** Name, Variables, Enabled, Secret, Ephemeral, Persisted Value

**Properties:** Name, Type, Version, Description, Variables, Environment, Folders, Requests, Auth, Headers, Scripts, Settings

**Website:** https://www.usebruno.com/

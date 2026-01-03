---
title: JSON RPC
description: JSON-RPC is a lightweight, transport-agnostic remote procedure call (RPC) protocol that uses JSON to encode requests and responses. A client sends an object with jsonrpc "2.0", a method name, optional params (positional or named), and an id; the server replies with either a result or an error (including standardized error codes), and it also supports notifications (no id, no response) and request batching.
date: 2025-09-19
weight: 32
toc_hide: true
---

{{% pageinfo %}}
Lightweight transport-agnostic remote procedure call protocol.
{{% /pageinfo %}}

JSON-RPC is a lightweight, transport-agnostic remote procedure call (RPC) protocol that uses JSON to encode requests and responses: a client sends an object with jsonrpc:"2.0", a method name, optional params (positional or named), and an id; the server replies with either a result or an error (including standardized error codes), and it also supports notifications (no id, no response) and request batching.

JSON-RPC emerged in the mid-2000s as a community-driven, lightweight RPC protocol using JSON, with an informal 1.0 spec (c. 2005) that defined simple request/response messaging and “notifications” (no reply). A 1.1 working draft (around 2008) tried to broaden and formalize features but never became canonical. The widely adopted JSON-RPC 2.0 specification (2010) simplified and standardized the model—introducing the mandatory "jsonrpc":"2.0" version tag, clearer error objects, support for both positional and named parameters, and request batching—while remaining transport-agnostic (HTTP, WebSocket, pipes, etc.).

**License:** Apache License 2.0 or MIT License

**Tags:** RPC

**Properties:** methods, parameters, identifier, results, errors, codes, messages, data

**Website:** https://www.jsonrpc.org/

**Forum**:** https://groups.google.com/g/json-rpc


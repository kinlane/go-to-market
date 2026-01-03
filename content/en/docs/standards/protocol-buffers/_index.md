---
title: Protocol Buffers
description: Protocol Buffers (protobuf) are Google’s language-neutral, platform-neutral way to define structured data and serialize it efficiently (small, fast). You write a schema in a .proto file, generate code for your language (Go, Java, Python, JS, etc.), and use the generated classes to read/write binary messages.
date: 2025-09-19
weight: 52
toc_hide: true
---

{{% pageinfo %}}
Fast binary serialized structured data.
{{% /pageinfo %}}

Protocol Buffers (protobuf) are Google’s language-neutral, platform-neutral way to define structured data and serialize it efficiently (small, fast). You write a schema in a .proto file, generate code for your language (Go, Java, Python, JS, etc.), and use the generated classes to read/write binary messages.

Protocol Buffers began inside Google in the early 2000s as an internal, compact, schema-driven serialization format; in 2008 Google open-sourced it as proto2.  Most recently in 2023, Google introduced “Protobuf Editions” to evolve semantics without fragmenting the language into proto2 vs. proto3, while the project continues to refine tooling, compatibility guidance, and release processes across a broad open-source community.

Owner: Google

License: BSD-3-Clause License

Tags: Schema, Data, Binary, Serialization

Properties: messages, types, fields, cardinality, comments, reserved values, scalars, defaults, enumerations, nested types, vinary, unknown fields, oneOf, maps, packages, and services

Website: https://protobuf.dev/
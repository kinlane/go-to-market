---
title: YAML
description: YAML (“YAML Ain’t Markup Language”) is a human-friendly data serialization format used for configuration and data exchange, built around indentation to express structure (mappings/objects, sequences/arrays, and scalars). It supports comments (#), multi-document streams (---), anchors/aliases for reuse (&id, *id), and optional type tags.
date: 2025-09-19
weight: 72
toc_hide: true
---

{{% pageinfo %}}
Human-friendly data serialization format for data exchange.
{{% /pageinfo %}}

YAML (“YAML Ain’t Markup Language”) is a human-friendly data serialization format used for configuration and data exchange, built around indentation to express structure (mappings/objects, sequences/arrays, and scalars). It supports comments (#), multi-document streams (---), anchors/aliases for reuse (&id, *id), and optional type tags. YAML 1.2 aligns closely with JSON (JSON is a subset of YAML 1.2), but YAML is more concise and readable for humans—hence its popularity in app configs, CI/CD pipelines, Kubernetes manifests, and Docker Compose—while also being sensitive to whitespace and, historically, to schema ambiguities (e.g., 1.1 vs 1.2 boolean parsing).

YAML was introduced in 2001 by Clark Evans (with Oren Ben-Kiki and Ingy döt Net) as a human-friendly data serialization format inspired by scripting languages and intended to be simpler than XML for configs and data exchange. The 1.1 spec (mid-2000s) broadened typing via schemas but also introduced notorious ambiguities (e.g., unquoted strings like “on”/“off” parsing as booleans). YAML 1.2 (2009) realigned the language with JSON—making JSON a subset of YAML—and clarified many edge cases, after which YAML gained wide adoption across developer tooling and ops: Rails configs, Ansible playbooks, Docker Compose files, CI/CD pipelines, and, most visibly, Kubernetes manifests in the 2010s. The spec continues to be maintained under the 1.2 line with incremental clarifications and errata.

**License:** MIT License

**Tags:** Data Formats

**Properties:** Scalars, Comments, Documents, Streams, Anchors, Aliases, Tags, Types

**GitHub:** https://yaml.org/

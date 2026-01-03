---
title: HTTP 2.0
description: HTTP/2 is a binary, multiplexed version of HTTP that uses streams, header compression (HPACK), and optional server push to reduce latency and improve performance over a single TCP connection.
date: 2025-09-19
weight: 111
toc_hide: true
---

{{% pageinfo %}}
The last version of HTTP that was quickly interated upon.
{{% /pageinfo %}}

HTTP/2 is a binary, multiplexed version of HTTP that uses streams, header compression (HPACK), and optional server push to reduce latency and improve performance over a single TCP connection.

HTTP/2 speeds up web communication by sending many HTTP requests and responses concurrently over a single TCP connection using lightweight streams, eliminating the HTTP/1.1 head-of-line blocking at the application layer. It encodes headers efficiently with HPACK to cut bandwidth, supports stream prioritization and flow control so more important resources arrive sooner, and frames messages in a binary format that’s faster and less error-prone to parse. While TLS isn’t required by the spec, it’s almost always used in practice, and HTTP/2 is backward-compatible with existing HTTP semantics (methods, status codes, URIs). It also introduced server push for proactively sending assets—though many platforms now discourage or disable push in favor of alternatives like 103 Early Hints or preload hints.
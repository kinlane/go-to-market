---
title: HTTP 3.0
description: HTTP/3 is the latest HTTP version that runs over QUIC (on UDP), providing multiplexed streams with built-in TLS 1.3 and connection migration to avoid TCP head-of-line blocking and improve performance.
date: 2025-09-19
weight: 112
toc_hide: true
---

{{% pageinfo %}}
The latest high performance version of HTTP.
{{% /pageinfo %}}

HTTP/3 is the latest HTTP version that runs over QUIC (on UDP), providing multiplexed streams with built-in TLS 1.3 and connection migration to avoid TCP head-of-line blocking and improve performance.

HTTP/3 is the newest version of the Hypertext Transfer Protocol that runs over QUIC, a transport built on UDP, to deliver faster and more reliable web transfers—especially on mobile and lossy networks. By multiplexing many streams within one connection, it avoids TCP’s head-of-line blocking, integrates TLS 1.3 by design (with 0-RTT/1-RTT handshakes), and supports connection migration so downloads continue smoothly when a device changes networks. HTTP/3 keeps the same HTTP semantics (methods, status codes, headers) while using binary framing and QPACK header compression for efficiency, and it’s now widely supported by major browsers and CDNs.
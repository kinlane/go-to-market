---
title: HTTP
description: HTTP (Hypertext Transfer Protocol) is a stateless application-layer protocol that defines how web clients and servers format and exchange requests and responses over the internet.
date: 2025-09-19
weight: 110
toc_hide: true
---

{{% pageinfo %}}
The foundation of the World Wide Web.
{{% /pageinfo %}}

HTTP (Hypertext Transfer Protocol) is a stateless application-layer protocol that defines how web clients and servers format and exchange requests and responses over the internet.

HTTP (Hypertext Transfer Protocol) is the stateless application-layer protocol that underpins the web, defining how clients (like browsers) and servers exchange requests and responses to retrieve or modify resources identified by URLs. It specifies methods (e.g., GET, POST, PUT, DELETE), headers for metadata and content negotiation, and status codes that indicate outcomes. Although HTTP is stateless, features like cookies and authentication headers enable sessions and identity. HTTP traditionally runs over TCP (HTTP/1.1 and HTTP/2 with multiplexing and header compression) and, in its latest version HTTP/3, over QUIC to reduce latency and improve reliability, almost always secured with TLS.
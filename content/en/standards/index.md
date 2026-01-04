---
title: Standards
linkTitle: Standards
menu: {main: {weight: 70}}
---

{{% blocks/lead color="dark" %}}

## HTTP Standards
The HTTP (Hypertext Transfer Protocol) standard is an application-layer protocol that defines how messages are formatted and transmitted between web browsers and servers, forming the foundation of data communication on the World Wide Web.

{{% /blocks/lead %}}

{{% blocks/section color="white" type="row" %}}

{{% blocks/feature icon="fab fa-chart-network" title="HTTP 1.1" url="/docs/standards/http" %}}
HTTP (Hypertext Transfer Protocol) is a stateless application-layer protocol that defines how web clients and servers format and exchange requests and responses over the internet.
{{% /blocks/feature %}}

{{% blocks/feature icon="fab fa-puzzle-piece-simple" title="HTTP/2" url="/docs/standards/http-20" %}}
HTTP/2 is a binary, multiplexed version of HTTP that uses streams, header compression (HPACK), and optional server push to reduce latency and improve performance over a single TCP connection.
{{% /blocks/feature %}}

{{% blocks/feature icon="fab fa-puzzle-piece-simple" title="HTTP/3" url="/docs/standards/http-30" %}}
HTTP/3 is the latest HTTP version that runs over QUIC (on UDP), providing multiplexed streams with built-in TLS 1.3 and connection migration to avoid TCP head-of-line blocking and improve performance.
{{% /blocks/feature %}}

{{% /blocks/section %}}

{{% blocks/lead color="dark" %}}

## Schema Formats
JSON Schema is central to everything here, playing a central role in defining schema, but also validating all the other specifications that are listed on this page.

{{% /blocks/lead %}}

{{% blocks/section color="white" type="row" %}}

{{% blocks/feature icon="fab" %}}{{% /blocks/feature %}}

{{% blocks/feature icon="fab fa-puzzle-piece-simple" title="JSON Schema" url="/docs/standards/json-schema" %}}
JSON Schema is a vocabulary for annotating and validating JSON documents. It defines the structure, content, and constraints of data—often authored in either JSON or YAML—and can be leveraged by documentation generators, validators, and other tooling.
{{% /blocks/feature %}}

{{% blocks/feature icon="fab" %}}{{% /blocks/feature %}}

{{% /blocks/section %}}

{{% blocks/lead color="dark" %}}

## Data Formats
Data formats are standardized ways of encoding and structuring information so software can store, transmit, and interpret it consistently as text (CSV, JSON, XML, YAML), using schema for validation.

{{% /blocks/lead %}}

{{% blocks/section color="white" type="row" %}}

{{% blocks/feature icon="fab fa-chart-network" title="CSV" url="/docs/standards/csv" %}}
CSV (Comma-Separated Values) is a simple text format for storing tabular data where each line represents a row and values within rows are separated by commas (or other delimiters). CSV is common import and export format for spreadsheets, making it a ubiquitous data format.
{{% /blocks/feature %}}

{{% blocks/feature icon="fab fa-puzzle-piece-simple" title="JSON" url="/docs/standards/json" %}}
JSON (JavaScript Object Notation) is a lightweight, text-based data interchange format that uses human-readable syntax with key-value pairs, arrays, and primitive data types (strings, numbers, booleans, null) to represent structured data. JSON reduced the size of data over the wire with mobile applications, then achieved wider adoption.
{{% /blocks/feature %}}

{{% blocks/feature icon="fab fa-puzzle-piece-simple" title="XML" url="/docs/standards/xml" %}}
XML (eXtensible Markup Language) is a text-based, Unicode-friendly format for representing structured data using nested elements (tags) and attributes, making documents both human- and machine-readable. It’s “extensible” because you define your own vocabulary (element and attribute names), organize data hierarchically, and use namespaces to avoid naming collisions.
{{% /blocks/feature %}}

{{% blocks/feature icon="fab fa-puzzle-piece-simple" title="YAML" url="/docs/standards/yaml" %}}
YAML (“YAML Ain’t Markup Language”) is a human-friendly data serialization format used for configuration and data exchange, built around indentation to express structure (mappings/objects, sequences/arrays, and scalars). It supports comments (#), multi-document streams (---), anchors/aliases for reuse (&id, *id), and optional type tags.
{{% /blocks/feature %}}

{{% blocks/feature icon="fab fa-puzzle-piece-simple" title="HTML" url="/docs/standards/html" %}}
HTML (HyperText Markup Language) is the standard markup language used to create and structure content on web pages, defining elements like headings, paragraphs, links, images, and forms through a system of tags that web browsers interpret and render as visual displays.
{{% /blocks/feature %}}

{{% blocks/feature icon="fab fa-puzzle-piece-simple" title="Markdown" url="/docs/standards/markdown" %}}
Markdown is a lightweight markup language that uses plain text formatting syntax (such as asterisks for emphasis, hashes for headings, and brackets for links) to create formatted documents that are easy to read in raw form and can be converted to HTML and other formats.
{{% /blocks/feature %}}

{{% /blocks/section %}}

{{% blocks/lead color="dark" %}}

## Binary Data Formats
Binary data formats encode information as compact, machine-readable byte sequences—often with schemas for type safety and fast serialization—to reduce size and speed I/O (e.g., Protocol Buffers, Avro, MessagePack, CBOR, Parquet, ORC).

{{% /blocks/lead %}}

{{% blocks/section color="white" type="row" %}}

{{% blocks/feature icon="fab fa-puzzle-piece-simple" title="Avro" url="/docs/standards/avro" %}}
Apache Avro is a data serialization system that provides compact binary encoding of structured data along with schema definitions, enabling efficient data exchange and storage with built-in schema evolution capabilities that allow data structures to change over time while maintaining compatibility between different versions.
{{% /blocks/feature %}}

{{% blocks/feature icon="fab fa-puzzle-piece-simple" title="Parquet" url="/docs/standards/parquet" %}}
Apache Parquet is a columnar storage file format designed for efficient data storage and retrieval in big data processing frameworks, optimizing for analytics workloads by storing data column-by-column rather than row-by-row, which enables compression, encoding, and query performance optimizations.
{{% /blocks/feature %}}

{{% blocks/feature icon="fab fa-puzzle-piece-simple" title="Protocol Buffers" url="/docs/standards/protocol-buffers" %}}
Protocol Buffers (protobuf) are Google’s language-neutral, platform-neutral way to define structured data and serialize it efficiently (small, fast). You write a schema in a .proto file, generate code for your language (Go, Java, Python, JS, etc.), and use the generated classes to read/write binary messages.
{{% /blocks/feature %}}

{{% /blocks/section %}}

{{% blocks/lead color="dark" %}}

## Data Connectors
Database connectors are drivers/adapters that let applications talk to databases by implementing the database’s wire protocol or a standardized API, handling auth, connections, type mapping, queries, and results.

{{% /blocks/lead %}}

{{% blocks/section color="white" type="row" %}}

{{% blocks/feature icon="fab fa-puzzle-piece-simple" title="JDBC" url="/docs/standards/jdbc" %}}
JDBC (Java Database Connectivity) is a Java API that provides a standard interface for Java applications to connect to and interact with relational databases, allowing developers to execute SQL queries, retrieve results, and manage database transactions in a database-agnostic way.
{{% /blocks/feature %}}

{{% blocks/feature icon="fab" %}}{{% /blocks/feature %}}

{{% blocks/feature icon="fab fa-puzzle-piece-simple" title="ODBC" url="/docs/standards/odbc" %}}
ODBC (Open Database Connectivity) is a standard API specification that provides a database-agnostic interface for applications to connect to and interact with various relational database management systems through database-specific drivers, enabling cross-platform database access without requiring application code changes.
{{% /blocks/feature %}}

{{% /blocks/section %}}

{{% blocks/lead color="dark" %}}

## OpenAPI Standards
OpenAPI is the leading standard for describing the surface area of HTTP APIs, expanding to provide overlays to artifacts, as well as workflows using the Arazzo specification.
{{% /blocks/lead %}}

{{% blocks/section color="white" type="row" %}}

{{% blocks/feature icon="fab fa-chart-network" title="OpenAPI" url="/docs/standards/openapi" %}}
The OpenAPI Specification (OAS) is a formal standard for describing HTTP APIs. It enables teams to understand how an API works and how multiple APIs interoperate, generate client code, create tests, apply design standards, and more.
{{% /blocks/feature %}}

{{% blocks/feature icon="fab fa-puzzle-piece-simple" title="Overlays" url="/docs/standards/openapi-overlays" %}}
The Overlay Specification is an auxiliary standard that complements the OpenAPI Specification. An OpenAPI description defines API operations, data structures, and metadata—the overall shape of an API. 
{{% /blocks/feature %}}

{{% blocks/feature icon="fab fa-puzzle-piece-simple" title="Arazzo" url="/docs/standards/arazzo" %}}
The Arazzo Specification is a community-driven standard for defining a programming-language-agnostic way to express sequences of calls and the dependencies between them to achieve a specific outcome.
{{% /blocks/feature %}}

{{% /blocks/section %}}

{{% blocks/lead color="dark" %}}

## AsyncAPI Standard
AsyncAPI emerged as a sister specification to OpenAPI, focusing on event-driven APIs, providing the ability to describe the surface area of Kafka, Websockets, and other event-driven approaches to doing APIs.

{{% /blocks/lead %}}

{{% blocks/section color="white" type="row" %}}

{{% blocks/feature icon="fab" %}}{{% /blocks/feature %}}

{{% blocks/feature icon="fab fa-puzzle-piece-simple" title="AsyncAPI" url="/docs/standards/asyncapi" %}}
AsyncAPI is an open-source, protocol-agnostic specification for describing event-driven APIs and message-driven applications. It serves as the OpenAPI of the asynchronous, event-driven world—overlapping with, and often going beyond, what OpenAPI covers.
{{% /blocks/feature %}}

{{% blocks/feature icon="fab" %}}{{% /blocks/feature %}}

{{% /blocks/section %}}


{{% blocks/lead color="dark" %}}

## Governance Policies
We use Spectral, Vacuum, and Open Policy Agents (OPA) to govern all of the schema and APIs in use as part of delivering capabilities reliably via Naftiko Engines.

{{% /blocks/lead %}}

{{% blocks/section color="white" type="row" %}}

{{% blocks/feature icon="fab fa-chart-network" title="Spectral" url="/docs/standards/spectral" %}}
Spectral is an open-source API linter for enforcing style guides and best practices across JSON Schema, OpenAPI, and AsyncAPI documents. It helps teams ensure consistency, quality, and adherence to organizational standards in API design and development.
{{% /blocks/feature %}}

{{% blocks/feature icon="fab fa-puzzle-piece-simple" title="Vacuum" url="/docs/standards/vacuum" %}}
Vacuum rules are how to configure vacuum to know which rules to run for each specification, and how it should evaluate those rules, and a RuleSet is a style guide with each rule being an individual requirement as a part of the overall guide.
{{% /blocks/feature %}}

{{% blocks/feature icon="fab fa-puzzle-piece-simple" title="Open Policy Agent (OPA)" url="/docs/standards/open-policy-agent" %}}
OPA (Open Policy Agent) is a general-purpose policy engine that unifies policy enforcement across your stack—improving developer velocity, security, and auditability. It provides a high-level, declarative language (Rego) for expressing policies across a wide range of use cases.
{{% /blocks/feature %}}


{{% /blocks/section %}}

{{% blocks/lead color="dark" %}}

## Artificial Intelligence Standards
There are many new standards emerging to support AI integration, and these are the formats we are currently supporting, with additional ones being evaluated as part of market research and being added regularly.

{{% /blocks/lead %}}

{{% blocks/section color="white" type="row" %}}

{{% blocks/feature icon="fab fa-chart-network" title="Model Context Protocol (MCP)" url="/docs/standards/spectral" %}}
MCP (Model Context Protocol) is an open protocol that standardizes how applications provide context to large language models (LLMs). It offers a consistent way to connect AI models to diverse data sources and tools, enabling agents and complex workflows that link models to the outside world.
{{% /blocks/feature %}}

{{% blocks/feature icon="fab" %}}{{% /blocks/feature %}}

{{% blocks/feature icon="fab fa-puzzle-piece-simple" title="Agent2Agent (A2A)" url="/docs/standards/vacuum" %}}
The Agent2Agent (A2A) Protocol is an open standard for communication and interoperability among independent—often opaque—AI agent systems. Because agents may be built with different frameworks, languages, and vendors, A2A provides a common language and interaction model.
{{% /blocks/feature %}}

{{% /blocks/section %}}

{{% blocks/lead color="dark" %}}

## API Client Standards
Multiple derivatives of API standards have evolved over the years to support API clients and automation, providing for competing formats that augment and compliment existing API standards.

{{% /blocks/lead %}}

{{% blocks/section color="white" type="row" %}}

{{% blocks/feature icon="fab fa-chart-network" title="Postman Collections" url="/docs/standards/postman-collections" %}}
A Postman Collection is a portable JSON artifacts that organizes one or more API requests—plus their params, headers, auth, scripts, and examples—so you can run, share, and automate them in the Postman desktop or web client application. Collections can include folders, collection- and environment-level variables, pre-request and test scripts, examples, mock server definitions, and documentation.
{{% /blocks/feature %}}

{{% blocks/feature icon="fab fa-chart-network" title="Bruno Collections" url="/docs/standards/spectral" %}}
Bruno collections are structured groups of API requests, variables, and environments used within the Bruno API client to help developers organize and manage their API workflows. Each collection acts as a self-contained workspace where you can store requests, define authentication, set environment values, document behaviors, and run tests.
{{% /blocks/feature %}}

{{% blocks/feature icon="fab fa-puzzle-piece-simple" title="Open Collections" url="/docs/standards/vacuum" %}}
The Agent2Agent (A2A) Protocol is an open standard for communication and interoperability among independent—often opaque—AI agent systems. Because agents may be built with different frameworks, languages, and vendors, A2A provides a common language and interaction model.
{{% /blocks/feature %}}

{{% /blocks/section %}}

{{% blocks/lead color="dark" %}}

## API Client Environment Standards
Augmenting the API client standards above, each of the providers have their own environment standard for storing of key / value pairs that can be used during testing and automation.

{{% /blocks/lead %}}

{{% blocks/section color="white" type="row" %}}

{{% blocks/feature icon="fab fa-chart-network" title="Postman Environments" url="/docs/standards/postman-collections" %}}
Postman environments are a powerful feature that allow you to manage different sets of variables for your API testing and development workflow. An environment is essentially a named collection of key-value pairs (variables) that you can switch between depending on your context—such as development, staging, or production. 
{{% /blocks/feature %}}

{{% blocks/feature icon="fab" %}}{{% /blocks/feature %}}

{{% blocks/feature icon="fab fa-chart-network" title="Bruno Environments" url="/docs/standards/spectral" %}}
A Bruno environment is a configurable set of key–value variables that allows you to run the same API requests across different deployment contexts, such as local development, staging, and production, storing values like base URLs, authentication tokens, headers, or other parameters that may change depending on where an API is being tested. 
{{% /blocks/feature %}}

{{% /blocks/section %}}

{{% blocks/lead color="dark" %}}

## Authentication Standards
While API keys are dominant pattern, there are two authentication standards at the top of the list when building Naftiko, which help secure the data and resources being made available.

{{% /blocks/lead %}}

{{% blocks/section color="white" type="row" %}}

{{% blocks/feature icon="fab fa-chart-network" title="OAuth 2.0" url="/docs/standards/oauth-20" %}}
OAuth 2.0 is an industry-standard protocol that enables secure, delegated access to APIs without requiring users to share their passwords with applications. Instead of handing over credentials, a user authorizes a trusted identity provider—such as Google, Microsoft, or an enterprise login system—to issue short-lived access tokens to a client application.
{{% /blocks/feature %}}

{{% blocks/feature icon="fab" %}}{{% /blocks/feature %}}

{{% blocks/feature icon="fab fa-puzzle-piece-simple" title="JWT" url="/docs/standards/jwt" %}}
A JSON Web Token (JWT) enables secure transmission of information between a client and server by encoding user identity and claims into a digitally signed token. When a user logs in, the server generates a JWT containing information like the user's ID and permissions, then sends it to the client. The client stores this token (typically in local storage or a cookie) and includes it in subsequent requests to prove their identity without needing to send credentials each time.
{{% /blocks/feature %}}

{{% /blocks/section %}}

{{% blocks/lead color="dark" %}}

## Semantic Standards
Semantics are needed to enrich data and the interfaces used to access the data, with Schema.org leading the way defining the vocabulary, and JSON-LD used to augment existing artifacts with that vocablary.

{{% /blocks/lead %}}

{{% blocks/section color="white" type="row" %}}

{{% blocks/feature icon="fab fa-chart-network" title="Schema.org" url="/docs/standards/schema-org" %}}
Schema.org is a collaborative, community-driven vocabulary (launched in 2011 by Google, Microsoft, Yahoo!, and Yandex) that defines shared types and properties to describe things on the web—people, places, products, events, and more—so search engines and other consumers can understand page content. 
{{% /blocks/feature %}}

{{% blocks/feature icon="fab" %}}{{% /blocks/feature %}}

{{% blocks/feature icon="fab fa-puzzle-piece-simple" title="JSON-LD" url="/docs/standards/json-led" %}}
JSON-LD (JavaScript Object Notation for Linking Data) is a W3C standard for expressing linked data in JSON. It adds lightweight semantics to ordinary JSON so machines can understand what the data means, not just its shape—by mapping keys to globally unique identifiers (IRIs) via a @context. Common features include @id (identity), @type (class), and optional graph constructs (@graph).
{{% /blocks/feature %}}

{{% /blocks/section %}}

{{% blocks/lead color="dark" %}}

## Discovery Standards
We are using APIs.json and API Commons to describe the technical and business details of the services we are making available as part of the development of capabilities.

{{% /blocks/lead %}}

{{% blocks/section color="white" type="row" %}}

{{% blocks/feature icon="fab fa-chart-network" title="APIs.json" url="/docs/standards/apis-json" %}}
APIs.json is a machine-readable specification that API providers use to describe their API operations—much like sitemap.xml describes a website. It offers an index of internal, partner, and public APIs that includes not only machine-readable artifacts (OpenAPI, JSON Schema, etc.) but also traditionally human-readable assets such as documentation, pricing, and terms of service.
{{% /blocks/feature %}}

{{% blocks/feature icon="fab" %}}{{% /blocks/feature %}}

{{% blocks/feature icon="fab fa-puzzle-piece-simple" title="API Commons" url="/docs/standards/api-commons" %}}
API Commons is a collection of open-source building blocks for API operations. It began as a machine-readable way to define the parts of an API, and works in concert with APIs.json to translate human-readable aspects of your API program into machine-readable artifacts that can standardize and automate your ecosystem.
{{% /blocks/feature %}}

{{% /blocks/section %}}

{{% blocks/lead color="dark" %}}

## Examples Standard
OpenAPI and AsyncAPI both provide the ability to include examples of API requests, responses, and messages, but Microcks has begun to develop a standard dedicated to mocking and testing examples.

{{% /blocks/lead %}}

{{% blocks/section color="white" type="row" %}}

{{% blocks/feature icon="fab" %}}{{% /blocks/feature %}}

{{% blocks/feature icon="fab fa-puzzle-piece-simple" title="Microcks Examples" url="/docs/standards/microcks-examples" %}}
APIExamples format is Microcks’ own specification format for defining examples intended to be used by Microcks mocks. It can be seen as a lightweight, general purpose specification to solely serve the need to provide mock datasets. The goal of this specification is to keep the Microcks adoption curve very smooth with development teams but also for non developers.

{{% /blocks/feature %}}

{{% blocks/feature icon="fab" %}}{{% /blocks/feature %}}

{{% /blocks/section %}}
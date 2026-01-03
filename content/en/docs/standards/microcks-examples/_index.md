---
title: Microcks Examples
description: APIExamples format is Microcks’ own specification format for defining examples intended to be used by Microcks mocks. 
date: 2025-12-16
weight: 125
toc_hide: true
---

{{% pageinfo %}}
APIExamples documents are intended to be imported as secondary artifacts only ; thanks to the Multi-Artifacts support.
{{% /pageinfo %}}

APIExamples format is Microcks’ own specification format for defining examples intended to be used by Microcks mocks. It can be seen as a lightweight, general purpose specification to solely serve the need to provide mock datasets. The goal of this specification is to keep the Microcks adoption curve very smooth with development teams but also for non developers.

APIExamples files are simple YAML and aim to be very easy to understand and edit. More over, the description is independent from the API protocol! We’re rather attached to describe examples depending on the API interaction style: Request/Response based or Event-driven/Asynchronous.

For ease of use, we provide a JSON Schema that you can download here. Thus, you can integrate it in your code editor and benefit from code completion and validation.

**License:** Apache 2.0

**Tags:** Examples

**Website:** https://microcks.io/documentation/references/examples/

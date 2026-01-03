---
title: API Reusability
date: 2026-01-03
description: Prototyping an API reusability capability to help drive conversation with different stakeholders when it comes to reusing APIs. We are still understanding what exactly this means, and this capability is driving that conversation out in the open on GitHub, our blog, and social media.
weight: 30
---

# API Reusability
This is an exploratory proof of concept to quantify what API reuse is across a catalog of APIs for a domain, report it to the rest of the company using existing services, and then incentivize API reuse in VSCode, encouraging developers to reuse existing patterns across the APIs they are producing and consuming.

API reusaability has been identified as a need across multiple conversations Naftiko is having with companies, and this repository is mean to explore what is possible across many different providers, helping better understand what API reuse means in way that others can use.

## Use Case
This is an implementation of the API reusable use cases for multiple pilot customers, leveraging the use case schema being developed to drive use case conversations, as well as how they are applied to each individual capability.

- [API Reusability](use-case/api-reusability.yml) - Defining and driving API reusability across a domain.

## Capabilities
This end-to-end use cases has six separate capabilities, providing five individual capabilities that can be applied individually, as well as an aggregate capability that brings them all together to provide the right-size context window for an MCP server incentivizing reuse in VSCode, while also updating leadership and other teams of the reuse.

- [API Reusability](capability-api-reusability.yml) - An aggregate capability to help manage API reusability for a domain.
    - [Establish API Catalog](capability-api-reusability-catalog.yml) - An individual capability to establish an API catalog being assessed.
    - [Define API Reuse](capability-api-reusability-definition.yml) - An individual capability to define the state of API reuse.
    - [Communicate API Reuse](capability-api-reusability-communicate.yml) - An individual capability to communicate API reusability to different audiences.
    - [Incentivize API Reuse](capability-api-reusability-incentivize.yml) - An individual capability to incentivize the reuse of APIs during development.

As many of the steps as possible are executed and validated using Bruno, when an HTTP adapter is used, which was pushed further with this iteration, using Bruno pre and post request scripts to calculate the API reuse definition using API catalog data gathered.

## Image
This is an image of this aggregate events AI context capability to try and capture everything going on in the visual language we already use for our deck.

![Alt text](diagrams/api-reusability.png "API Resuability")

## Links

- [**GitHub Repository**](https://github.com/naftiko/api-reusability)
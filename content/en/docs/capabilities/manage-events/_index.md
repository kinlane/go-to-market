---
title: Manage Events
date: 2026-01-03
description: Prototyping an events management capability to assist in conversations we are having, but also explore how Naftiko could manage events and meetups we are planning on producing, helping develop a capability out in the open as we are working to build the product, iterating on capabilities we can use.
weight: 30
---

This is an exploratory proof of concept to explore what and end-to-end event management capability could look like--assembling all the existing standards in a single place to help inform what the capability schema might look like to support our ai context use case, while providing governance along the way.

## Use Case
This is an application for our AI Context use cases, leveraging the use case schema being developed to drive use case conversations, as well as how they are applied to each individual capability.

- [AI Context](use-case/ai-context.yml) - Using a capability as the context window for producing MCP servers.

## Capabilities
This end-to-end use cases has six separate capabilities, providing five individual capabilities that can be applied individually, as well as an aggregate capability that brings them all together to provide the right-size context window for an MCP server.

- [Events (Aggregate)](capability-event-context.yml) - A single aggregate events capability.
- [Events](capability-event-context-events.yml) - An individual events capability.
- [Atendees](capability-event-context-attendees.yml) - An individual attendees capability.
- [Exhibitors](capability-event-context-exhibitors.yml) - An individual exhibitors capability.
- [Sessions](capability-event-context-sessions.yml) - An individual sessions capability.
- [Speakers](capability-event-context-speakers.yml) - An individual speakers capability.

## Image
This is an image of this aggregate events AI context capability to try and capture everything going on in the visual language we already use for our deck.

![Alt text](diagrams/event-ai-context-engine.png "Event Management Capability")

## Links

- [**GitHub Repository**](https://github.com/naftiko/manage-events)
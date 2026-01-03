---
title: Vacuum
description: RuleSets are how to configure vacuum to know which rules to run for each specification, and how it should evaluate those rules, and a RuleSet is a style guide with each rule being an individual requirement as a part of the overall guide.
date: 2025-09-19
weight: 60
toc_hide: true
---

{{% pageinfo %}}
Enforcing style guides across JSON artifacts to govern schema.
{{% /pageinfo %}}

VACUUM rules in the context of API linting are configuration definitions that specify quality and style requirements for OpenAPI specifications. RuleSets serve as comprehensive style guides where each individual rule represents a specific requirement that the API specification must meet. These rules are configured using YAML or JSON and follow the Spectral Ruleset model, making them fully compatible with Spectral rulesets while adding vacuum-specific enhancements like an id property for backward compatibility and flexible naming. A RuleSet contains a collection of rules that define what to check, where to check it, and how violations should be handled, allowing organizations to enforce consistent API design standards across their specifications.

Each rule within a RuleSet consists of several key components: a given property that uses JSONPath expressions (supporting both RFC 9535 and JSON Path Plus) to target specific sections of the OpenAPI document, a severity level (such as error, warning, or info) that indicates the importance of the rule, and a then clause that specifies which built-in function to apply and what field to evaluate. For example, a rule might target all tag objects in an API specification using $.tags[*] as the JSONPath expression, then apply the truthy function to verify that each tag has a description field populated. Built-in core functions like casing, truthy, and pattern provide the logic for evaluating whether specifications comply with the defined rules, enabling automated validation of API documentation quality, consistency, and adherence to organizational or industry standards.

Vacuum is a soft fork of Spectral, keeping the base format for interoperability, while also taking the specification into a new direction to support OpenAPI Doctor and Vacuum linting rules functionality in tooling and pipelines.

**License:** Apache

**Tags:** Rules, Governance

**Properties:** rules, rulesets, given, then, description, message, severity, formats, recommended, and resolved properties

**GitHub:** https://quobix.com/vacuum/rulesets/understanding/

**Standards:** JSON Schema, Spectral
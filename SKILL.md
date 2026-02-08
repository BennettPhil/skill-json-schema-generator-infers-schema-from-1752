---
name: json-schema-generator-infers-schema-from-1752
description: A JSON Schema generator that infers a schema from sample JSON data. Given one or more JSON examples, produc...
version: 0.1.0
license: Apache-2.0
---

# json-schema-generator-infers-schema-from-1752

## Purpose

Use this skill to implement and operate: A JSON Schema generator that infers a schema from sample JSON data. Given one or more JSON examples, produce a JSON Schema that validates all samples with appropriate types, required fields, and constraints..

## Instructions

1. Run `./scripts/run.sh --help` to inspect supported inputs.
2. Run `./scripts/run.sh "<target>"` to generate an execution plan and recommended checks.
3. Review the emitted checklist and adapt it for your repository or environment.

## Inputs

- A target name or path as the main argument.
- Optional `--context` text to provide extra constraints.

## Outputs

- A structured checklist printed to stdout.
- Exit code `0` on success and non-zero on invalid usage.

## Constraints

- This starter implementation is intentionally minimal.
- Tailor the generated checklist before using it in production workflows.

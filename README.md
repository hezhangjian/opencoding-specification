# OpenCoding

OpenCoding aims to generate code from a single language-neutral schema, reducing the effort of defining and maintaining the same data models across different technology stacks.

This repository contains the OpenCoding specification and examples. The specification is a draft, and the sections below describe its design goals. See [Current Status](#current-status) for what has been implemented.

## Design Goals

- **Shared data definitions**: Describe data models in readable YAML or JSON as a common input for code generation across languages.
- **Rich type system**: Support primitive types, enums, nested models, lists, and maps.

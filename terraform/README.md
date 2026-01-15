# Terraform (Platform Layer)

This directory will contain **reusable, versioned Terraform modules**
that provide platform-level infrastructure primitives.

## Principles

- Modules must be cloud-agnostic where reasonable
- Provider-specific modules are clearly separated
- No application-specific logic
- No environment-specific values

## Examples (Future)

- Networking (VPC / VNet)
- IAM / Identity
- Logging and monitoring foundations

## Status

No modules are implemented yet.
Modules will be added only when at least one application requires them.

# Jenkins Pipeline Patterns

Opinionated Jenkins pipeline library with job templating and reusable stages to standardize CI and operational hooks.

## Features
- Reusable stages for build/test/scan/deploy
- Job templates for common app types
- Operational hooks (backup, drift checks, health tests)

## Quickstart
```groovy
// Coming soon: shared library usage example
@Library('pipeline-patterns') _
```

## Architecture
- Jenkins shared library structure
- Guardrails for deploy with rollback hooks

## Roadmap
- Kubernetes-native agents
- GitOps promotion workflows

## License
MIT

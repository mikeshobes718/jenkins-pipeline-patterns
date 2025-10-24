# Jenkins Pipeline Patterns

[![CI](https://github.com/mikeshobes718/jenkins-pipeline-patterns/actions/workflows/ci.yml/badge.svg)](https://github.com/mikeshobes718/jenkins-pipeline-patterns/actions/workflows/ci.yml) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

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

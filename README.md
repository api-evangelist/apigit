# APIGit (apigit)
APIGit is a Git-native platform for full lifecycle API development that combines version control, API design, documentation generation, governance, testing, and dynamic mock servers in a single integrated environment. Teams can build, publish, share, and secure APIs through Git-based workflows.

**URL:** [https://apigit.com/](https://apigit.com/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - API Design, API Lifecycle, Documentation, Git, Governance, Mocking, Platform, Testing

## Timestamps

- **Created:** 2025-01-08
- **Modified:** 2026-04-19

## APIs

### APIGit
APIGit provides a Git-native API lifecycle platform with native Git repositories, visual API design, documentation generation, governance policies, automated testing, and dynamic mock servers.

**Human URL:** [https://apigit.com/](https://apigit.com/)

#### Tags:

 - API Design, API Lifecycle, Git, Mocking

#### Properties

- [Documentation](https://apigit.com/)
- [Pricing](https://apigit.com/pricing)
- [OpenAPI](openapi/apigit-api.yaml)
- [JSONSchema](json-schema/apigit-repository-schema.json)
- [JSONSchema](json-schema/apigit-mock-server-schema.json)
- [JSON-LD](json-ld/apigit-context.jsonld)

## Common Properties

- [Website](https://apigit.com/)
- [Documentation](https://apigit.com/doc)
- [Pricing](https://apigit.com/pricing)
- [Blog](https://apigit.com/blog)
- [GitHubOrganization](https://github.com/apigitlabs)
- [YouTube](https://www.youtube.com/@apigit)

## Features

| Name | Description |
|------|-------------|
| Native Git Repository | Version-controlled API repositories with Git-native workflows for teams. |
| API Design | Visual OpenAPI designer for designing APIs without writing YAML manually. |
| API Documentation | Automatic documentation generation and publishing with custom domains. |
| API Governance | Policy management and compliance controls for API standards enforcement. |
| API Testing | Built-in automated API testing with test case management. |
| Dynamic Mock Server | Zero-configuration dynamic mock servers generated from API definitions. |

## Use Cases

| Name | Description |
|------|-------------|
| Design-First API Development | Design APIs visually before implementation using Git-tracked OpenAPI definitions. |
| Parallel Frontend-Backend Development | Enable frontend teams to develop against mock servers while backends are being built. |
| Team API Governance | Enforce API standards and policies across teams with built-in governance tools. |

## Solutions

| Name | Description |
|------|-------------|
| Free Plan | 1 API repository, mock server, and document publication with up to 1,000 mock calls/month. |
| Team Plan | $8/user/month with 5 seats, 5 organizations, and 2,000 mock calls/month/seat. |
| Enterprise Plan | $18/user/month with 20 organizations, custom domains, SSO, webhooks, and 4,000 mock calls/month/seat. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [APIGit API](openapi/apigit-api.yaml)

### JSON Schema

- [apigit-repository-schema.json](json-schema/apigit-repository-schema.json)
- [apigit-mock-server-schema.json](json-schema/apigit-mock-server-schema.json)

### JSON Structure

- [apigit-repository-structure.json](json-structure/apigit-repository-structure.json)
- [apigit-mock-server-structure.json](json-structure/apigit-mock-server-structure.json)

### JSON-LD

- [apigit-context.jsonld](json-ld/apigit-context.jsonld)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [APIGit API](capabilities/shared/apigit.yaml) — 3 operations for repository and mock server management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [API Lifecycle Development](capabilities/api-lifecycle-development.yaml) | APIGit API | 3 | API Developer, Backend Engineer |

## Vocabulary

- [APIGit Vocabulary](vocabulary/apigit-vocabulary.yaml) — Unified taxonomy mapping 4 resources, 4 actions, 1 workflow, and 2 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [apigit-spectral-rules.yml](rules/apigit-spectral-rules.yml) — 6 rules across 4 categories enforcing APIGit API conventions

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com

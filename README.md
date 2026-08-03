# APIGit (apigit)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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

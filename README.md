# Akamai (akamai)
Akamai is a global content delivery network (CDN), cloud services, and cybersecurity company that helps organizations deliver fast, reliable, and secure digital experiences. Akamai's intelligent edge platform spans over 4,000 locations in 130+ countries, enabling customers to accelerate content delivery, protect against cyberattacks, and run cloud applications at the edge of the internet.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/akamai/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - CDN, Cloud, Edge Computing, Networks, Platform, Security

## Timestamps

- **Created:** 2025-01-08
- **Modified:** 2026-04-19

## Common Properties

- [Website](https://www.akamai.com/)
- [Portal](https://techdocs.akamai.com/home/page/apis)
- [Documentation](https://techdocs.akamai.com/)
- [Authentication](https://techdocs.akamai.com/developer/docs/set-up-authentication-credentials)
- [GitHubOrganization](https://github.com/akamai)
- [GitHubRepository](https://github.com/akamai/akamai-apis)
- [Blog](https://www.akamai.com/blog)
- [Support](https://www.akamai.com/support)
- [StatusPage](https://www.akamaistatus.com/)

## Features

| Name | Description |
|------|-------------|
| Content Delivery Network | Global CDN with 4,000+ locations in 130+ countries for fast, reliable content delivery. |
| EdgeWorkers | Serverless JavaScript execution at the edge enabling custom logic for traffic management and content manipulation. |
| EdgeKV | Distributed key-value store at the edge for low-latency data access in EdgeWorkers applications. |
| Property Manager | Configuration management for edge delivery rules, caching, security, and performance optimizations. |
| DDoS Protection | Prolexic DDoS mitigation service protecting networks and applications from volumetric attacks. |
| Web Application Firewall | Application security protecting against OWASP Top 10, bots, and API attacks via App and API Protector. |
| Identity Cloud | Customer identity and access management (CIAM) platform for registration, authentication, and social login. |
| Cloud Computing | Linode cloud platform providing virtual machines, Kubernetes, databases, and storage services worldwide. |

## Use Cases

| Name | Description |
|------|-------------|
| Media Streaming | Broadcasters and OTT platforms deliver live and on-demand video at scale using Akamai Media Services. |
| E-Commerce Acceleration | Retailers accelerate page load times and checkout flows with Ion and adaptive acceleration. |
| Zero Trust Security | Enterprises implement zero trust access for applications using Enterprise Application Access. |
| API Security | Organizations discover and protect APIs from threats using Akamai API Security platform. |
| Gaming | Game publishers distribute updates, reduce latency, and prevent DDoS attacks on gaming platforms. |
| IoT Firmware Updates | Automotive and device manufacturers deliver secure over-the-air firmware updates via IoT OTA. |

## Integrations

| Name | Description |
|------|-------------|
| Terraform | Official Akamai Terraform provider for infrastructure-as-code management of Akamai configurations. |
| GitHub Actions | CI/CD integration for deploying Akamai configurations and properties via GitHub Actions. |
| Splunk | DataStream and SIEM integration for streaming Akamai logs to Splunk for analysis. |
| AWS | Cloud connectivity between Akamai edge and AWS origins for accelerated cloud delivery. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Akamai EdgeWorkers API](openapi/akamai-edgeworkers-openapi.json)
- [Akamai EdgeKV API](openapi/akamai-edgekv-openapi.json)
- [Akamai Network Lists API](openapi/akamai-network-lists-openapi.json)
- [Akamai Property Manager API](openapi/akamai-papi-openapi.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [EdgeWorkers](capabilities/shared/edgeworkers.yaml) — 2 operations for EdgeWorker serverless function management
- [Network Lists](capabilities/shared/network-lists.yaml) — 1 operation for network list management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Edge Platform Management](capabilities/edge-platform-management.yaml) | EdgeWorkers, Network Lists | 3 | Platform Engineer, DevOps Engineer |

## Vocabulary

- [Akamai Vocabulary](vocabulary/akamai-vocabulary.yaml) — Unified taxonomy mapping 6 resources, 6 actions, 1 workflow, and 2 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Akamai Spectral Rules](rules/akamai-spectral-rules.yml) — 21 rules across 9 categories enforcing Akamai API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com

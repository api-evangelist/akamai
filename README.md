# Akamai (akamai)
Akamai is a global content delivery network (CDN), cloud services, and cybersecurity company that helps organizations deliver fast, reliable, and secure digital experiences. Akamai's intelligent edge platform spans over 4,000 locations in 130+ countries, enabling customers to accelerate content delivery, protect against cyberattacks, and run cloud applications at the edge of the internet.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/akamai/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

- CDN, Cloud, Edge Computing, Networks, Platform, Security

## Timestamps

- **Created:** 2025-01-08
- **Modified:** 2026-05-22

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
- [LinkedIn](https://www.linkedin.com/company/akamai-technologies)

## Features

| Name | Description |
|------|-------------|
| Content Delivery Network | Global CDN with 4,000+ locations in 130+ countries for fast, reliable content delivery. |
| EdgeWorkers | Serverless JavaScript execution at the edge enabling custom logic for traffic management and content manipulation. |
| EdgeKV | Distributed key-value store at the edge for low-latency data access in EdgeWorkers applications. |
| Property Manager | Configuration management for edge delivery rules, caching, security, and performance optimizations. |
| App & API Protector | WAF + DDoS + Bot Manager protecting web apps and APIs (Behavioral DDoS, JA4 fingerprinting, CVE Protections). |
| API Security | ML-based API Discovery and Posture (formerly Noname Security) including detection of GenAI, LLM, and MCP server APIs. |
| API Endpoint Definition | Programmatically register and govern API endpoints with API privacy, JWT validation, CORS, caching, and GraphQL controls. |
| Prolexic DDoS | Network-cloud DDoS mitigation including IP Protect with Network Cloud Firewall and Prolexic Analytics. |
| Identity Cloud | Customer identity and access management (CIAM) for registration, hosted login, social login, and webhooks. |
| Akamai Cloud Computing | Linode-derived cloud platform with Shared/Dedicated/Premium/GPU VMs, Block + Object Storage, NodeBalancers, LKE (Kubernetes), and Managed Databases. |

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

### OpenAPI (12)

- [Akamai API Endpoint Definition API](openapi/akamai-api-definitions-openapi.json) — 39 operations
- [Akamai Application Security API](openapi/akamai-application-security-openapi.json) — 144 operations, 83 schemas (WAF + Behavioral DDoS + Discovered APIs)
- [Akamai Certificate Provisioning System API](openapi/akamai-cps-openapi.json) — 12 operations
- [Akamai CP Codes and Reporting Groups API](openapi/akamai-cp-codes-openapi.json) — 7 operations
- [Akamai EdgeKV API](openapi/akamai-edgekv-openapi.json) — 12 operations
- [Akamai EdgeWorkers API](openapi/akamai-edgeworkers-openapi.json) — 31 operations
- [Akamai Fast Purge API](openapi/akamai-fast-purge-openapi.json) — 7 operations
- [Akamai Network Lists API](openapi/akamai-network-lists-openapi.json) — 11 operations
- [Akamai Property Manager API (PAPI)](openapi/akamai-papi-openapi.json) — 58 operations
- [Akamai Sandbox API](openapi/akamai-sandbox-openapi.json) — 8 operations
- [Akamai SIEM Integration API](openapi/akamai-siem-openapi.json) — 1 operation, 5 schemas
- [Akamai Site Shield API](openapi/akamai-site-shield-openapi.json) — 3 operations, 4 schemas

## Capabilities

Naftiko capabilities organized as one YAML per API tag/business surface. 151 capability files across 12 APIs, each covering one self-contained business surface.

| API | Capability Files |
|-----|------------------|
| API Endpoint Definition | 14 (Endpoints, Versions, JWT, API Privacy, CORS, GraphQL, Cache, ...) |
| Application Security | 69 (WAF Rules, Behavioral DDoS, Discovered APIs, Rate Policies, Reputation, Match Targets, ...) |
| Certificate Provisioning | 3 (Enrollments, Changes, Deployments) |
| CP Codes / Reporting Groups | 4 (CP Codes, Reporting Groups, Products, Watermark Limits) |
| EdgeKV | 5 (Namespaces, Items, Access Tokens, Permission Groups, Status) |
| EdgeWorkers | 13 (Activations, Versions, Reports, Validations, Resource Tiers, ...) |
| Fast Purge | 4 (URL/ARL, CP Code, Cache Tag, Rate Limits) |
| Network Lists | 4 (Network Lists, Elements, Activations, Subscriptions) |
| Property Manager (PAPI) | 29 (Properties, Versions, Hostnames, Includes, Bulk Activations, Rules, ...) |
| Sandbox | 4 (Sandboxes, EdgeWorkers, Properties, Rotate JWT) |
| SIEM | 1 (Events) |
| Site Shield | 1 (Maps) |

## JSON Schemas

- 25 schemas extracted from Application Security (Behavioral DDoS profiles, Match Targets, Custom Rules, Rate Policies, Reputation Profiles, ...)
- 4 schemas from Fast Purge
- 5 schemas from SIEM
- 4 schemas from Site Shield

See [`json-schema/`](json-schema/).

## Vocabulary

- [Akamai Vocabulary](vocabulary/akamai-vocabulary.yaml) — Unified taxonomy mapping resources, actions, workflows, and personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Akamai Spectral Rules](rules/akamai-spectral-rules.yml) — Rules enforcing Akamai API conventions (Title Case summaries, EdgeGrid auth, accountSwitchKey, hostname-templated baseUri, error envelope, pagination)

## Plans, Rate Limits, and FinOps

- [Plans & Pricing](plans/akamai-plans-pricing.yml) — API Commons Plans 0.1 covering multi-service enterprise pricing, committed-use discounts, and per-service families
- [Rate Limits](rate-limits/akamai-rate-limits.yml) — Documented per-API rate-limit policies (Fast Purge, EdgeWorkers, PAPI)
- [FinOps](finops/akamai-finops.yml) — FOCUS-aligned billing dimensions for cost attribution across CDN, Cloud Compute, and Security services

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com

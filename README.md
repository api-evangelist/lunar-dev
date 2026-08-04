# Lunar.dev (lunar-dev)

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

Lunar.dev is an enterprise-grade gateway platform for AI governance and third-party API consumption control. It unifies an MCP Gateway, AI Gateway, and API Consumption Gateway into a single control point that gives organizations observability, access control, policy enforcement, quota management, rate limiting, and real-time monitoring over how applications and AI agents authenticate, discover tools, and consume third-party APIs.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/lunar-dev/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/lunar-dev/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- AI Gateway
- Automation
- Consumption Gateway
- Control
- Deployment
- Integrations
- MCP Gateway
- Performance
- Platform
- Version Control
- Visibility
- Workflows

## Timestamps

- **Created:** 2025-01-08
- **Modified:** 2026-05-19

## APIs

### Lunar.dev Gateway Admin API

The Lunar.dev Gateway Admin API provides administrative endpoints for managing and monitoring the Lunar API Consumption Gateway. It enables health monitoring, endpoint discovery, flow validation, and policy management for the running gateway instance.

- **Human URL:** [https://docs.lunar.dev/](https://docs.lunar.dev/)

#### Tags

- AI Gateway
- Consumption Gateway
- Control
- Discovery
- Flows
- Health
- Integrations
- MCP Gateway
- Performance
- Platform
- Policies
- Visibility

#### Properties

- [Documentation](https://docs.lunar.dev/)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/lunar-dev/refs/heads/main/openapi/lunar-dev-gateway-admin-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/health-status.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/discovered-endpoint.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/policy.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/flow.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/validation-result.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/lunar-dev-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Postman Collection](collections/lunar-dev-gateway-admin.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/lunar-dev-gateway-admin.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/lunar-dev-gateway-proxy.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/lunar-dev-gateway-proxy.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Lunar.dev Gateway Proxy API

The Lunar.dev Gateway Proxy API handles routing of outbound egress API traffic through the Lunar Gateway. Client applications send third-party API requests through this proxy, which provides traffic management, policy enforcement, caching, rate limiting, quota management, and real-time observability.

- **Human URL:** [https://docs.lunar.dev/](https://docs.lunar.dev/)

#### Tags

- AI Gateway
- Consumption Gateway
- Egress
- Integrations
- MCP Gateway
- Platform
- Proxy
- Quota Management
- Rate Limiting
- Traffic Management

#### Properties

- [Documentation](https://docs.lunar.dev/)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/lunar-dev/refs/heads/main/openapi/lunar-dev-gateway-proxy-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/lunar-dev-gateway-admin.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/lunar-dev-gateway-admin.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/lunar-dev-gateway-proxy.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/lunar-dev-gateway-proxy.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/lunar-api)
- [Youtube](https://www.youtube.com/channel/UCgWge-0djZcm-JWU82FbR7A)
- [GitHub Organization](https://github.com/TheLunarCompany)
- [Website](https://www.lunar.dev/)
- [Blog](https://www.lunar.dev/lunar-blog)
- [Guide](https://www.lunar.dev/guides-resources)
- [F A Q](https://www.lunar.dev/faqs)
- [Customers](https://www.lunar.dev/case-study)
- [Customers](https://www.lunar.dev/case-study)
- [Use Cases](https://www.lunar.dev/use-cases)
- [Documentation](https://docs.lunar.dev/)
- [Getting Started](https://docs.lunar.dev/quick-start-guide/)
- [Quotas](https://docs.lunar.dev/quotas/quotas-overview)
- [F A Q](https://docs.lunar.dev/additional-resources/faqs/faqIndex)
- [About](https://www.lunar.dev/about-us)
- [Login](https://login.lunar.dev/u/login?state=hKFo2SBYaVVrZmZpMHhLN3M3RFlmV0s1WUZCYzZjb2Nwa2FNWaFur3VuaXZlcnNhbC1sb2dpbqN0aWTZIEtDRC1iM2d3Z1ltMTNSYmpKZEloOHFHUFp3aG5FMk9vo2NpZNkgQTZBOVRoUnJ6anp2eEx6cFUwRm5JZE1Id0xUUmdnSFE)
- [Sign Up](https://login.lunar.dev/u/login?state=hKFo2SBkZkoxMlV1VVFQQmZ3ejlTQjU2QWdteFBEbG1tSWNERaFur3VuaXZlcnNhbC1sb2dpbqN0aWTZIFVCVnEySHI0MHlSLTdmRU0ydzBGeTd6aFlxLTFYUlhMo2NpZNkgQTZBOVRoUnJ6anp2eEx6cFUwRm5JZE1Id0xUUmdnSFE)
- [Privacy Policy](https://www.lunar.dev/privacy-policy)
- [Terms of Service](https://www.lunar.dev/terms-of-use)
- [Blog](https://www.lunar.dev/lunar-blog)
- [Support](https://www.lunar.dev/demo)
- [Pricing](https://www.lunar.dev/pricing)
- [Features](undefined)
- [Use Cases](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com

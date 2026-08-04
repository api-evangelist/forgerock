# ForgeRock (forgerock)

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

ForgeRock, now part of Ping Identity, provides digital identity and access management solutions for secure authentication, authorization, and identity governance across cloud and hybrid environments.

**APIs.json:** [https://www.forgerock.com](https://www.forgerock.com)

## Scope

- **Type:** Index

## Tags

- Access Management
- Authentication
- Authorization
- Identity Governance
- Identity Management
- OAuth
- OpenID Connect

## Timestamps

- **Created:** 2024
- **Modified:** 2026-05-19

## APIs

### ForgeRock Identity Cloud REST API

REST API for managing identities, authentication, and authorization in ForgeRock Identity Cloud, providing access management and identity management endpoints for Advanced Identity Cloud tenant environments.

- **Human URL:** [https://backstage.forgerock.com/docs/idcloud/latest](https://backstage.forgerock.com/docs/idcloud/latest)
- **Base URL:** `https://{tenant}.forgeblocks.com`

#### Tags

- Access Management
- Authentication
- Cloud
- Identity
- REST

#### Properties

- [Documentation](https://backstage.forgerock.com/docs/idcloud/latest/)
- [OpenAPI](openapi/forgerock-identity-cloud-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/forgerock-identity-cloud.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/forgerock-identity-cloud.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [OpenAPI](https://backstage.forgerock.com/docs/idcloud/latest/openapi/) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [API Reference](https://apidocs.id.forgerock.io/)
- [Getting Started](https://backstage.forgerock.com/docs/idcloud/latest/home.html)
- [Authentication](https://backstage.forgerock.com/docs/idcloud/latest/developer-docs/authenticate-to-rest-api-overview.html)
- [S D Ks](https://backstage.forgerock.com/docs/idcloud/latest/end-user/sdks.html)

### ForgeRock Access Management API

API for authentication, authorization, session management, and policy evaluation. Supports OAuth 2.0 and OpenID Connect flows for secure token-based access.

- **Human URL:** [https://backstage.forgerock.com/docs/am/7.3](https://backstage.forgerock.com/docs/am/7.3)
- **Base URL:** `https://{deployment}/am`

#### Tags

- Access Management
- Authentication
- Authorization
- OAuth
- Sessions

#### Properties

- [Documentation](https://backstage.forgerock.com/docs/am/7.3/)
- [OpenAPI](openapi/forgerock-access-management-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/forgerock-access-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/forgerock-access-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [API Reference](https://backstage.forgerock.com/docs/am/7.3/apidocs/)
- [Authentication](https://backstage.forgerock.com/docs/am/7/authentication-guide/)
- [Getting Started](https://backstage.forgerock.com/docs/am/7.1/REST-guide/basic-rest-authentication.html)
- [Changelog](https://backstage.forgerock.com/docs/am/7/release-notes/)

### ForgeRock Identity Management API

REST API for CRUD operations on managed objects and identity lifecycle management. Supports provisioning, synchronization, reconciliation, and workflow-driven identity operations.

- **Human URL:** [https://backstage.forgerock.com/docs/idm/7.4](https://backstage.forgerock.com/docs/idm/7.4)
- **Base URL:** `https://{deployment}/openidm`

#### Tags

- Identity Management
- Lifecycle Management
- Provisioning
- Synchronization

#### Properties

- [Documentation](https://backstage.forgerock.com/docs/idm/7.4/)
- [OpenAPI](openapi/forgerock-identity-management-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/forgerock-identity-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/forgerock-identity-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [R E S T  A P I  Guide](https://backstage.forgerock.com/docs/idm/7.4/rest-api-reference/)
- [Getting Started](https://backstage.forgerock.com/docs/idm/7.4/getting-started/)
- [Changelog](https://backstage.forgerock.com/docs/idm/7.4/release-notes/preface.html)

### ForgeRock Identity Gateway API

API for reverse proxy functionality, policy enforcement, and request transformation. Integrates web applications, APIs, and microservices with the ForgeRock Identity Platform.

- **Human URL:** [https://backstage.forgerock.com/docs/ig/7.3](https://backstage.forgerock.com/docs/ig/7.3)
- **Base URL:** `https://{deployment}/ig`

#### Tags

- API Security
- Gateway
- Policy Enforcement
- Reverse Proxy

#### Properties

- [Documentation](https://backstage.forgerock.com/docs/ig/7.3/)
- [OpenAPI](openapi/forgerock-identity-gateway-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/forgerock-identity-gateway.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/forgerock-identity-gateway.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Reference](https://backstage.forgerock.com/docs/ig/7.3/reference/)
- [Getting Started](https://backstage.forgerock.com/docs/ig/7/gateway-guide/)

### ForgeRock Directory Services API

LDAP and REST API for directory operations and data management. Provides HDAP endpoints for accessing directory data as JSON resources.

- **Human URL:** [https://backstage.forgerock.com/docs/ds/7.4](https://backstage.forgerock.com/docs/ds/7.4)
- **Base URL:** `https://{deployment}/ds`

#### Tags

- Data Storage
- Directory
- HDAP
- LDAP

#### Properties

- [Documentation](https://backstage.forgerock.com/docs/ds/7.4/)
- [OpenAPI](openapi/forgerock-directory-services-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [R E S T  A P I](https://backstage.forgerock.com/docs/ds/7.4/rest-guide/)
- [Getting Started](https://backstage.forgerock.com/docs/ds/7.4/getting-started/rest.html)
- [Reference](https://backstage.forgerock.com/docs/ds/7.4/rest-guide/rest-operations.html)

### ForgeRock Identity Governance API

REST API for identity governance operations including access reviews, certifications, role management, and policy enforcement. Provides endpoints for managing entitlements and compliance workflows.

- **Human URL:** [https://backstage.forgerock.com/docs/identity-governance/7.1/api-guide/preface.html](https://backstage.forgerock.com/docs/identity-governance/7.1/api-guide/preface.html)
- **Base URL:** `https://{deployment}/iga`

#### Tags

- Access Reviews
- Compliance
- Entitlements
- Identity Governance

#### Properties

- [Documentation](https://backstage.forgerock.com/docs/identity-governance/7.1/api-guide/preface.html)
- [OpenAPI](openapi/forgerock-identity-governance-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/forgerock-identity-governance.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/forgerock-identity-governance.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [API Reference](https://backstage.forgerock.com/docs/idcloud/latest/identity-governance/rest-api/endpoints/rest-iga.html)

### ForgeRock Autonomous Identity API

REST API for the Autonomous Identity analytics platform that uses AI-driven analysis to determine confidence scores, predictions, and recommendations for entitlement assignments.

- **Human URL:** [https://backstage.forgerock.com/docs/autonomous-identity/2022.11.0/api-guide/preface.html](https://backstage.forgerock.com/docs/autonomous-identity/2022.11.0/api-guide/preface.html)
- **Base URL:** `https://{deployment}/autoid`

#### Tags

- Analytics
- Artificial Intelligence
- Autonomous Identity
- Entitlements

#### Properties

- [Documentation](https://backstage.forgerock.com/docs/autonomous-identity/2022.11.0/api-guide/preface.html)
- [OpenAPI](openapi/forgerock-autonomous-identity-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/forgerock-autonomous-identity.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/forgerock-autonomous-identity.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/forgerock)
- [Portal](https://backstage.forgerock.com)
- [Documentation](https://backstage.forgerock.com/docs)
- [Getting Started](https://community.forgerock.com/c/getting-started-guides/36)
- [Authentication](https://backstage.forgerock.com/docs/idcloud/latest/developer-docs/authenticate-to-rest-api-overview.html)
- [Blog](https://www.forgerock.com/blog)
- [Status Page](https://status.id.forgerock.io)
- [Support](https://backstage.forgerock.com/support)
- [Terms of Service](https://www.forgerock.com/terms)
- [Privacy Policy](https://www.forgerock.com/privacy-policy)
- [GitHub Organization](https://github.com/ForgeRock)
- [Community](https://community.forgerock.com/)
- [Website](https://www.forgerock.com)
- [Login](https://backstage.forgerock.com/account)
- [Sign Up](https://backstage.forgerock.com/account/register)
- [S D Ks](https://docs.pingidentity.com/sdks/latest/index.html)
- [J S O N- L D  Context](json-ld/forgerock-context.jsonld)
- [J S O N  Schema](json-schema/forgerock-managed-user-schema.json)
- [J S O N  Schema](json-schema/forgerock-session-schema.json)
- [J S O N  Schema](json-schema/forgerock-policy-schema.json)
- [J S O N  Schema](json-schema/forgerock-oauth2-token-schema.json)
- [J S O N  Schema](json-schema/forgerock-managed-role-schema.json)
- [J S O N  Schema](json-schema/forgerock-entitlement-schema.json)
- [J S O N  Schema](json-schema/forgerock-directory-entry-schema.json)

## Maintainers

**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com

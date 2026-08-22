# PropelAuth (propelauth)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

PropelAuth is a B2B SaaS authentication and multi-tenant user management platform purpose-built for organizations that sell to other organizations. It provides hosted login UIs, first-class organizations / tenants with custom roles and permissions, enterprise SSO via SAML and OIDC, SCIM directory sync, end-user API keys with validation and usage reporting, OAuth 2.0 / OpenID Connect identity-provider endpoints, and OAuth 2.1 MCP server authentication with dynamic client registration for AI agents. Backend SDKs span Node, Express, FastAPI, Flask, Django REST Framework, Python, Go, Rust, .NET, Ruby, and Cloudflare Workers; frontend SDKs cover React, JavaScript, and Next.js (App + Pages Router). A Terraform provider and official CLI back infrastructure-as-code workflows. Pricing starts free with 10,000 MAU and scales through Growth ($150/mo) and Growth Plus ($500/mo) to custom Enterprise contracts.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/propelauth/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/propelauth/refs/heads/main/apis.yml)

## Scope

- **Position:** Providing
- **Access:** 3rd-Party

## Tags

- Authentication
- Identity
- B2B
- Multi-Tenancy
- Authorization
- RBAC
- SSO
- SCIM
- MCP
- API Keys

## Timestamps

- **Created:** 2026-05-25T00:00:00.000Z
- **Modified:** 2026-05-25

## APIs

### PropelAuth User API

Backend REST API for managing PropelAuth-managed end users. Create, fetch, query, update, delete, enable/disable, and migrate users; issue magic links and short-lived access tokens; manage 2FA and force-logout sessions. Authenticated with a PropelAuth Backend Integration API key as a Bearer token.

- **Human URL:** [https://docs.propelauth.com/reference/api/user](https://docs.propelauth.com/reference/api/user)

#### Tags

- Authentication
- Users
- B2B
- Identity

#### Properties

- [Documentation](https://docs.propelauth.com/reference/api/user)
- [Getting Started](https://docs.propelauth.com/reference/api/getting-started)
- [OpenAPI](openapi/propelauth-user-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/propelauth-user-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/propelauth-user-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/propelauth-user-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/propelauth-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Example](examples/propelauth-create-user-example.json)
- [Example](examples/propelauth-create-magic-link-example.json)

### PropelAuth Organization API

Backend REST API for managing tenant organizations in PropelAuth. CRUD on organizations, member management (add, remove, change role), invite flows, custom role mappings, and pending invite revocation. The multi-tenant core of every B2B SaaS PropelAuth deployment.

- **Human URL:** [https://docs.propelauth.com/reference/api/org](https://docs.propelauth.com/reference/api/org)

#### Tags

- Authentication
- Organizations
- Multi-Tenancy
- B2B

#### Properties

- [Documentation](https://docs.propelauth.com/reference/api/org)
- [OpenAPI](openapi/propelauth-org-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/propelauth-org-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/propelauth-org-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/propelauth-org-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/propelauth-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Example](examples/propelauth-create-org-example.json)

### PropelAuth End-User API Keys API

Backend REST API for issuing, validating, listing, updating, and revoking end-user API keys that PropelAuth manages on behalf of your users and tenant organizations. Includes personal and org-scoped keys, imported legacy keys, and per-key usage reporting. Up to 5M validations / month with the Advanced API Keys add-on.

- **Human URL:** [https://docs.propelauth.com/reference/api/apikey](https://docs.propelauth.com/reference/api/apikey)

#### Tags

- Authentication
- API Keys
- Machine-to-Machine
- B2B

#### Properties

- [Documentation](https://docs.propelauth.com/reference/api/apikey)
- [OpenAPI](openapi/propelauth-api-keys-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/propelauth-api-keys-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/propelauth-api-keys-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/propelauth-api-key-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Example](examples/propelauth-validate-api-key-example.json)

### PropelAuth OAuth2 API

OAuth 2.0 / OpenID Connect identity-provider endpoints exposed by your PropelAuth Auth URL. Use PropelAuth as an OIDC provider for first-party and third-party OAuth clients, including no-code / low-code and OIDC-aware backends. Authorize, token exchange, refresh, userinfo, logout, and OIDC discovery.

- **Human URL:** [https://docs.propelauth.com/reference/api/oauth2](https://docs.propelauth.com/reference/api/oauth2)

#### Tags

- Authentication
- OAuth 2.0
- OpenID Connect
- Identity Provider

#### Properties

- [Documentation](https://docs.propelauth.com/reference/api/oauth2)
- [OpenAPI](openapi/propelauth-oauth2-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/propelauth-oauth2-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/propelauth-oauth2-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### PropelAuth MCP Authentication API

OAuth 2.1 authorization-server endpoints for Model Context Protocol (MCP) clients and AI agents. Authorize with PKCE, exchange and refresh tokens, introspect access tokens, dynamically register MCP clients (RFC 7591), and discover OAuth 2.1 server metadata. Secure MCP servers with PropelAuth identities and organization-scoped permissions.

- **Human URL:** [https://docs.propelauth.com/mcp-authentication/overview](https://docs.propelauth.com/mcp-authentication/overview)

#### Tags

- Authentication
- MCP
- OAuth 2.1
- AI Agents
- Beta

#### Properties

- [Documentation](https://docs.propelauth.com/mcp-authentication/overview)
- [OpenAPI](openapi/propelauth-mcp-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/propelauth-mcp-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/propelauth-mcp-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [Portal](https://www.propelauth.com)
- [Documentation](https://docs.propelauth.com)
- [Getting Started](https://docs.propelauth.com/getting-started)
- [Documentation](https://docs.propelauth.com/reference)
- [Documentation](https://docs.propelauth.com/reference/api/getting-started)
- [Documentation](https://docs.propelauth.com/reference/api/user)
- [Documentation](https://docs.propelauth.com/reference/api/org)
- [Documentation](https://docs.propelauth.com/reference/api/apikey)
- [Documentation](https://docs.propelauth.com/reference/api/oauth2)
- [Documentation](https://docs.propelauth.com/mcp-authentication/overview)
- [Pricing](https://www.propelauth.com/pricing)
- [Status Page](https://status.propelauth.com/)
- [Status Page](https://status.propelauth.com/default/history.rss)
- [Blog](https://www.propelauth.com/blog)
- [Terms of Service](https://www.propelauth.com/legal/terms-of-service)
- [Privacy Policy](https://www.propelauth.com/legal/privacy-policy)
- [Sign Up](https://auth.propelauth.com/en/signup)
- [Documentation](https://byo.propelauth.com)
- [Documentation](https://docs.propelauth.com/files/PropelAuth.postman_collection.json)
- [Support](support@propelauth.com)
- [GitHub Organization](https://github.com/PropelAuth)
- [SDK](https://github.com/PropelAuth/react)
- [SDK](https://github.com/PropelAuth/javascript)
- [SDK](https://github.com/PropelAuth/nextjs)
- [SDK](https://github.com/PropelAuth/node)
- [SDK](https://github.com/PropelAuth/express)
- [SDK](https://github.com/PropelAuth/propelauth-fastapi)
- [SDK](https://github.com/PropelAuth/propelauth-flask)
- [SDK](https://github.com/PropelAuth/propelauth-py)
- [SDK](https://github.com/PropelAuth/propelauth-django-rest-framework)
- [SDK](https://github.com/PropelAuth/propelauth-go)
- [SDK](https://github.com/PropelAuth/rust)
- [SDK](https://github.com/PropelAuth/dotnet)
- [SDK](https://github.com/PropelAuth/propelauth-rb)
- [SDK](https://github.com/PropelAuth/cloudflare-worker)
- [SDK](https://github.com/PropelAuth/frontend-apis)
- [SDK](https://github.com/PropelAuth/node-apis)
- [Tool](https://github.com/PropelAuth/cli)
- [Tool](https://github.com/PropelAuth/terraform-provider-propelauth)
- [Tool](https://github.com/PropelAuth/byo-go)
- [Tool](https://github.com/PropelAuth/propelauth-byo-java)
- [Tool](https://github.com/PropelAuth/base-elements)
- [Documentation](https://github.com/PropelAuth/documentation)
- [Code Examples](https://github.com/PropelAuth/react-frontend-starter)
- [Code Examples](https://github.com/PropelAuth/express-backend-starter)
- [Code Examples](https://github.com/PropelAuth/flask-backend-starter)
- [Code Examples](https://github.com/PropelAuth/fastapi-backend-starter)
- [Code Examples](https://github.com/PropelAuth/python-chalice-backend-starter)
- [Code Examples](https://github.com/PropelAuth/rust-axum-starter)
- [Code Examples](https://github.com/PropelAuth/redwood)
- [Code Examples](https://github.com/PropelAuth/postgraphile-propelauth-starter)
- [Code Examples](https://github.com/PropelAuth/nextjs-example-app)
- [Code Examples](https://github.com/PropelAuth/react-express-comment-example)
- [Code Examples](https://github.com/PropelAuth/demo-genai-api-keys)
- [Code Examples](https://github.com/PropelAuth/demo-b2b-coupon-generator)
- [Code Examples](https://github.com/PropelAuth/windows-login-pages)
- [Plans](plans/propelauth-plans-pricing.yml)
- [Rate Limits](rate-limits/propelauth-rate-limits.yml)
- [Fin Ops](finops/propelauth-finops.yml)
- [Vocabulary](vocabulary/propelauth-vocabulary.yml)
- [Spectral Ruleset](rules/propelauth-rules.yml)
- [Features](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com
**URL:** https://apievangelist.com

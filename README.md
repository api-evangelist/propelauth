# PropelAuth (propelauth)

PropelAuth is a B2B SaaS authentication and multi-tenant user management platform purpose-built for organizations that sell to other organizations. It provides hosted login UIs, first-class organizations / tenants with custom roles and permissions, enterprise SSO (SAML and OIDC), SCIM directory sync, end-user API keys with validation and usage reporting, OAuth 2.0 / OpenID Connect identity-provider endpoints, and OAuth 2.1 MCP server authentication with dynamic client registration for AI agents.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/propelauth/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

- Authentication, Identity, B2B, Multi-Tenancy, Authorization, RBAC, SSO, SCIM, MCP, API Keys

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## Plans

| Tier | Price / Month | Included MAU | Overage | Key Features |
|---|---|---|---|---|
| Free | $0 | 10,000 | n/a | Hosted UIs, custom domain, 2FA, RBAC, unlimited orgs |
| Growth | $150 | 10,000 | $0.05 / MAU | + impersonation, unlimited SAML SSO, staging env, API keys / M2M, MCP auth |
| Growth Plus | $500 | 10,000 | $0.05 / MAU (volume discounts) | + SCIM directory sync, advanced org and security controls |
| Enterprise | Contact | Custom | Custom | Custom SLAs, dedicated support, tailored contracts |

**Add-Ons:** Advanced API Keys (5M validations/month), Data Explorer (enhanced insights).

## APIs

### PropelAuth User API

Backend REST API for managing PropelAuth-managed end users — create, fetch, query, update, delete, enable / disable, and migrate users; issue magic links and short-lived access tokens; manage 2FA and force-logout sessions. Authenticated with a PropelAuth Backend Integration API key as a Bearer token.

**Human URL:** [https://docs.propelauth.com/reference/api/user](https://docs.propelauth.com/reference/api/user)

- [Documentation](https://docs.propelauth.com/reference/api/user)
- [Getting Started](https://docs.propelauth.com/reference/api/getting-started)
- [OpenAPI](openapi/propelauth-user-api-openapi.yml)
- [JSON Schema — User](json-schema/propelauth-user-schema.json)
- [JSON-LD](json-ld/propelauth-context.jsonld)
- [Example — Create User](examples/propelauth-create-user-example.json)
- [Example — Create Magic Link](examples/propelauth-create-magic-link-example.json)
- [Naftiko Capability — User Management](capabilities/user-management.yaml)

### PropelAuth Organization API

Backend REST API for managing tenant organizations — CRUD on orgs, member management, invite flows, custom role mappings, and pending invite revocation. The multi-tenant core of every B2B SaaS PropelAuth deployment.

**Human URL:** [https://docs.propelauth.com/reference/api/org](https://docs.propelauth.com/reference/api/org)

- [Documentation](https://docs.propelauth.com/reference/api/org)
- [OpenAPI](openapi/propelauth-org-api-openapi.yml)
- [JSON Schema — Organization](json-schema/propelauth-org-schema.json)
- [Example — Create Org](examples/propelauth-create-org-example.json)
- [Naftiko Capability — Org Management](capabilities/org-management.yaml)

### PropelAuth End-User API Keys API

Backend REST API for issuing, validating, listing, updating, and revoking end-user API keys (personal and org-scoped) managed by PropelAuth on behalf of your users and tenant organizations. Supports importing legacy keys and per-key usage reporting; up to 5M validations/month with the Advanced API Keys add-on.

**Human URL:** [https://docs.propelauth.com/reference/api/apikey](https://docs.propelauth.com/reference/api/apikey)

- [Documentation](https://docs.propelauth.com/reference/api/apikey)
- [OpenAPI](openapi/propelauth-api-keys-api-openapi.yml)
- [JSON Schema — API Key](json-schema/propelauth-api-key-schema.json)
- [Example — Validate API Key](examples/propelauth-validate-api-key-example.json)
- [Naftiko Capability — API Key Validation](capabilities/api-key-validation.yaml)

### PropelAuth OAuth2 API

OAuth 2.0 / OpenID Connect identity-provider endpoints exposed by your PropelAuth Auth URL. Use PropelAuth as an OIDC provider for first-party and third-party OAuth clients, including no-code, low-code, and OIDC-aware backends. Authorize, token exchange, refresh, userinfo, logout, and OIDC discovery.

**Human URL:** [https://docs.propelauth.com/reference/api/oauth2](https://docs.propelauth.com/reference/api/oauth2)

- [Documentation](https://docs.propelauth.com/reference/api/oauth2)
- [OpenAPI](openapi/propelauth-oauth2-api-openapi.yml)
- [Naftiko Capability — OAuth2 Identity Provider](capabilities/oauth2-identity-provider.yaml)

### PropelAuth MCP Authentication API

OAuth 2.1 authorization-server endpoints for Model Context Protocol (MCP) clients and AI agents. Authorize with PKCE, exchange and refresh tokens, introspect access tokens, dynamically register MCP clients (RFC 7591), and discover OAuth 2.1 authorization server metadata. Secure MCP servers with PropelAuth identities and organization-scoped permissions.

**Human URL:** [https://docs.propelauth.com/mcp-authentication/overview](https://docs.propelauth.com/mcp-authentication/overview)

- [Documentation](https://docs.propelauth.com/mcp-authentication/overview)
- [OpenAPI](openapi/propelauth-mcp-api-openapi.yml)
- [Naftiko Capability — MCP Authentication](capabilities/mcp-authentication.yaml)

## Common Properties

- [Portal](https://www.propelauth.com)
- [Documentation — PropelAuth Docs](https://docs.propelauth.com)
- [GettingStarted](https://docs.propelauth.com/getting-started)
- [Documentation — Reference](https://docs.propelauth.com/reference)
- [Documentation — Backend API Getting Started](https://docs.propelauth.com/reference/api/getting-started)
- [Documentation — User API](https://docs.propelauth.com/reference/api/user)
- [Documentation — Organization API](https://docs.propelauth.com/reference/api/org)
- [Documentation — API Keys](https://docs.propelauth.com/reference/api/apikey)
- [Documentation — OAuth2 API](https://docs.propelauth.com/reference/api/oauth2)
- [Documentation — MCP Authentication](https://docs.propelauth.com/mcp-authentication/overview)
- [Pricing](https://www.propelauth.com/pricing)
- [StatusPage](https://status.propelauth.com/)
- [StatusPage RSS](https://status.propelauth.com/default/history.rss)
- [Blog](https://www.propelauth.com/blog)
- [TermsOfService](https://www.propelauth.com/legal/terms-of-service)
- [PrivacyPolicy](https://www.propelauth.com/legal/privacy-policy)
- [SignUp](https://auth.propelauth.com/en/signup)
- [Documentation — Bring Your Own Auth](https://byo.propelauth.com)
- [Documentation — Postman Collection](https://docs.propelauth.com/files/PropelAuth.postman_collection.json)
- [Support](mailto:support@propelauth.com)
- [GitHubOrganization](https://github.com/PropelAuth)

## SDKs

### Backend

- [Node.js SDK](https://github.com/PropelAuth/node)
- [Express Middleware](https://github.com/PropelAuth/express)
- [FastAPI SDK](https://github.com/PropelAuth/propelauth-fastapi)
- [Flask SDK](https://github.com/PropelAuth/propelauth-flask)
- [Python SDK](https://github.com/PropelAuth/propelauth-py)
- [Django REST Framework SDK](https://github.com/PropelAuth/propelauth-django-rest-framework)
- [Go SDK](https://github.com/PropelAuth/propelauth-go)
- [Rust Crate](https://github.com/PropelAuth/rust)
- [.NET SDK](https://github.com/PropelAuth/dotnet)
- [Ruby SDK](https://github.com/PropelAuth/propelauth-rb)
- [Cloudflare Worker SDK](https://github.com/PropelAuth/cloudflare-worker)
- [Node Backend APIs](https://github.com/PropelAuth/node-apis)

### Frontend

- [React SDK](https://github.com/PropelAuth/react)
- [JavaScript SDK](https://github.com/PropelAuth/javascript)
- [Next.js SDK (App + Pages)](https://github.com/PropelAuth/nextjs)
- [Frontend APIs](https://github.com/PropelAuth/frontend-apis)
- [React Base Elements](https://github.com/PropelAuth/base-elements)

### Tools

- [PropelAuth CLI](https://github.com/PropelAuth/cli)
- [Terraform Provider](https://github.com/PropelAuth/terraform-provider-propelauth)
- [BYO Auth (Go)](https://github.com/PropelAuth/byo-go)
- [BYO Auth (Java)](https://github.com/PropelAuth/propelauth-byo-java)

### Starters and Examples

- [React Frontend Starter](https://github.com/PropelAuth/react-frontend-starter)
- [Express Backend Starter](https://github.com/PropelAuth/express-backend-starter)
- [Flask Backend Starter](https://github.com/PropelAuth/flask-backend-starter)
- [FastAPI Backend Starter](https://github.com/PropelAuth/fastapi-backend-starter)
- [Python Chalice Backend Starter](https://github.com/PropelAuth/python-chalice-backend-starter)
- [Rust Axum Starter](https://github.com/PropelAuth/rust-axum-starter)
- [RedwoodJS Starter](https://github.com/PropelAuth/redwood)
- [PostGraphile Starter](https://github.com/PropelAuth/postgraphile-propelauth-starter)
- [Next.js Example App](https://github.com/PropelAuth/nextjs-example-app)
- [React + Express Comment Example](https://github.com/PropelAuth/react-express-comment-example)
- [GenAI API Keys Demo](https://github.com/PropelAuth/demo-genai-api-keys)
- [B2B Coupon Generator Demo](https://github.com/PropelAuth/demo-b2b-coupon-generator)
- [Windows Login Pages](https://github.com/PropelAuth/windows-login-pages)

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [PropelAuth User API](openapi/propelauth-user-api-openapi.yml)
- [PropelAuth Organization API](openapi/propelauth-org-api-openapi.yml)
- [PropelAuth End-User API Keys API](openapi/propelauth-api-keys-api-openapi.yml)
- [PropelAuth OAuth2 API](openapi/propelauth-oauth2-api-openapi.yml)
- [PropelAuth MCP Authentication API](openapi/propelauth-mcp-api-openapi.yml)

### JSON Schema

- [PropelAuth User Schema](json-schema/propelauth-user-schema.json)
- [PropelAuth Organization Schema](json-schema/propelauth-org-schema.json)
- [PropelAuth API Key Schema](json-schema/propelauth-api-key-schema.json)

### JSON-LD

- [PropelAuth Context](json-ld/propelauth-context.jsonld)

### Examples

- [Create User](examples/propelauth-create-user-example.json)
- [Create Organization](examples/propelauth-create-org-example.json)
- [Create Magic Link](examples/propelauth-create-magic-link-example.json)
- [Validate API Key](examples/propelauth-validate-api-key-example.json)

### Capabilities (Naftiko)

- [User Management](capabilities/user-management.yaml)
- [Organization Management](capabilities/org-management.yaml)
- [API Key Validation](capabilities/api-key-validation.yaml)
- [MCP Authentication](capabilities/mcp-authentication.yaml)
- [OAuth2 Identity Provider](capabilities/oauth2-identity-provider.yaml)

### Governance and Vocabulary

- [Spectral Ruleset](rules/propelauth-rules.yml)
- [Vocabulary](vocabulary/propelauth-vocabulary.yml)

### Commercial Artifacts

- [Plans / Pricing](plans/propelauth-plans-pricing.yml)
- [Rate Limits](rate-limits/propelauth-rate-limits.yml)
- [FinOps Definition](finops/propelauth-finops.yml)

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com

**X:** apievangelist

**URL:** https://apievangelist.com

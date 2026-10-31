# PropelAuth

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

**Areas:** Authentication · Identity · B2B · Multi-Tenancy · Authorization · RBAC · SSO · SCIM · MCP · APIKeys · Identity Federation

## PropelAuth on APIs.io

Everything profiled for PropelAuth is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/propelauth/](https://apis.io/providers/propelauth/)** — or go straight to one of the APIs or properties below.

### APIs (18)

- [PropelAuth End-User API Keys API](https://apis.io/apis/propelauth/propelauth-api-keys-api/) — Backend REST API for issuing, validating, listing, updating, and revoking end-user API keys that PropelAuth manages on behalf of your users and tenant…
- [PropelAuth Access Tokens API](https://apis.io/apis/propelauth/propelauth-access-tokens-api/) — Mint short-lived access tokens for impersonation and testing
- [PropelAuth Discovery API](https://apis.io/apis/propelauth/propelauth-discovery-api/) — OpenID Connect discovery
- [PropelAuth Dynamic Client Registration API](https://apis.io/apis/propelauth/propelauth-dynamic-client-registration-api/) — RFC 7591 dynamic client registration
- [PropelAuth Employees API](https://apis.io/apis/propelauth/propelauth-employees-api/) — Inspect PropelAuth dashboard employees (internal team)
- [PropelAuth Invites API](https://apis.io/apis/propelauth/propelauth-invites-api/) — Inspect and revoke pending organization invites
- [PropelAuth Magic Links API](https://apis.io/apis/propelauth/propelauth-magic-links-api/) — Issue one-time magic links for login flows
- [PropelAuth MCP OAuth 2.1 API](https://apis.io/apis/propelauth/propelauth-mcp-oauth-2-1-api/) — OAuth 2.1 flows for MCP clients
- [PropelAuth Members API](https://apis.io/apis/propelauth/propelauth-members-api/) — Add, remove, invite, and change roles for users within an organization
- [PropelAuth Metadata API](https://apis.io/apis/propelauth/propelauth-metadata-api/) — Authorization server metadata discovery
- [PropelAuth Migration API](https://apis.io/apis/propelauth/propelauth-migration-api/) — Migrate users from external authentication providers
- [PropelAuth Organizations API](https://apis.io/apis/propelauth/propelauth-organizations-api/) — Create, read, update, and delete tenant organizations
- [PropelAuth Role Mappings API](https://apis.io/apis/propelauth/propelauth-role-mappings-api/) — Manage custom role mappings per organization
- [PropelAuth Sessions API](https://apis.io/apis/propelauth/propelauth-sessions-api/) — Manage user sessions and forced logout
- [PropelAuth Usage API](https://apis.io/apis/propelauth/propelauth-usage-api/) — Inspect API key usage statistics
- [PropelAuth Users API](https://apis.io/apis/propelauth/propelauth-users-api/) — Create, query, update, disable, delete, and inspect users
- [PropelAuth Validation API](https://apis.io/apis/propelauth/propelauth-validation-api/) — Validate end-user, personal, organization, and imported API keys
- [PropelAuth O Auth2 API](https://apis.io/apis/propelauth/propelauth-oauth2-api/) — Authorize, token, refresh, and userinfo endpoints

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Arazzo workflows (13)

Multi-step workflows that chain operations into a business task.

- [PropelAuth Create And Update User](https://apis.io/arazzos/propelauth/propelauth-create-and-update-user-workflow/)
- [PropelAuth Invite Existing User By ID](https://apis.io/arazzos/propelauth/propelauth-invite-existing-user-by-id-workflow/)
- [PropelAuth Invite User To Org](https://apis.io/arazzos/propelauth/propelauth-invite-user-to-org-workflow/)
- [PropelAuth Issue Magic Link For New User](https://apis.io/arazzos/propelauth/propelauth-issue-magic-link-for-new-user-workflow/)
- [PropelAuth Migrate User With Password](https://apis.io/arazzos/propelauth/propelauth-migrate-user-with-password-workflow/)
- [PropelAuth Offboard User From Org](https://apis.io/arazzos/propelauth/propelauth-offboard-user-from-org-workflow/)
- [PropelAuth Onboard User Into Org](https://apis.io/arazzos/propelauth/propelauth-onboard-user-into-org-workflow/)
- [PropelAuth Promote Org Member](https://apis.io/arazzos/propelauth/propelauth-promote-org-member-workflow/)
- [PropelAuth Provision Org API Key](https://apis.io/arazzos/propelauth/propelauth-provision-org-api-key-workflow/)
- [PropelAuth Provision Org With Admin](https://apis.io/arazzos/propelauth/propelauth-provision-org-with-admin-workflow/)
- [PropelAuth Revoke Pending Invite](https://apis.io/arazzos/propelauth/propelauth-revoke-pending-invite-workflow/)
- [PropelAuth Rotate User API Key](https://apis.io/arazzos/propelauth/propelauth-rotate-user-api-key-workflow/)
- [PropelAuth Upsert User By Email](https://apis.io/arazzos/propelauth/propelauth-upsert-user-by-email-workflow/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Propelauth Agentic Access](https://apis.io/agentic-access/propelauth/propelauth-agentic-access/)

#### JSON Schema (3)

The data models the API reads and writes.

- [PropelAuth End-User API Key](https://apis.io/schemas/propelauth/propelauth-api-key/)
- [PropelAuth Organization](https://apis.io/schemas/propelauth/propelauth-org/)
- [PropelAuth User](https://apis.io/schemas/propelauth/propelauth-user/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Propelauth Context](https://apis.io/jsonld/propelauth/propelauth-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Propelauth Vocabulary](https://apis.io/vocabularies/propelauth/propelauth-vocabulary/)

#### Examples (4)

Example requests and responses.

- [Propelauth Create Magic Link Example](https://apis.io/examples/propelauth/propelauth-create-magic-link-example/)
- [Propelauth Create Org Example](https://apis.io/examples/propelauth/propelauth-create-org-example/)
- [Propelauth Create User Example](https://apis.io/examples/propelauth/propelauth-create-user-example/)
- [Propelauth Validate Api Key Example](https://apis.io/examples/propelauth/propelauth-validate-api-key-example/)

#### Collections (26)

Postman and Open Collection request collections.

- [PropelAuth End-User API Keys Access Tokens API](https://apis.io/collections/propelauth/open-propelauth-access-tokens-api/)
- [PropelAuth End-User Access Tokens API Keys API](https://apis.io/collections/propelauth/open-propelauth-api-keys-api/)
- [PropelAuth End-User API Keys Access Tokens Discovery API](https://apis.io/collections/propelauth/open-propelauth-discovery-api/)
- [PropelAuth End-User API Keys Access Tokens Dynamic Client Registration API](https://apis.io/collections/propelauth/open-propelauth-dynamic-client-registration-api/)
- [PropelAuth End-User API Keys Access Tokens Employees API](https://apis.io/collections/propelauth/open-propelauth-employees-api/)
- [PropelAuth End-User API Keys Access Tokens Invites API](https://apis.io/collections/propelauth/open-propelauth-invites-api/)
- [PropelAuth End-User API Keys Access Tokens Magic Links API](https://apis.io/collections/propelauth/open-propelauth-magic-links-api/)
- [PropelAuth MCP Authentication API](https://apis.io/collections/propelauth/open-propelauth-mcp-api/)
- [PropelAuth End-User API Keys Access Tokens MCP OAuth 2.1 API](https://apis.io/collections/propelauth/open-propelauth-mcp-oauth-2-1-api/)
- [PropelAuth End-User API Keys Access Tokens Members API](https://apis.io/collections/propelauth/open-propelauth-members-api/)
- [PropelAuth End-User API Keys Access Tokens Metadata API](https://apis.io/collections/propelauth/open-propelauth-metadata-api/)
- [PropelAuth End-User API Keys Access Tokens Migration API](https://apis.io/collections/propelauth/open-propelauth-migration-api/)
- [PropelAuth End-User API Keys Access Tokens OAuth2 API](https://apis.io/collections/propelauth/open-propelauth-oauth2-api/)
- [PropelAuth Organization API](https://apis.io/collections/propelauth/open-propelauth-org-api/)
- [PropelAuth End-User API Keys Access Tokens Organizations API](https://apis.io/collections/propelauth/open-propelauth-organizations-api/)
- [PropelAuth End-User API Keys Access Tokens Role Mappings API](https://apis.io/collections/propelauth/open-propelauth-role-mappings-api/)
- [PropelAuth End-User API Keys Access Tokens Sessions API](https://apis.io/collections/propelauth/open-propelauth-sessions-api/)
- [PropelAuth End-User API Keys Access Tokens Usage API](https://apis.io/collections/propelauth/open-propelauth-usage-api/)
- [PropelAuth User API](https://apis.io/collections/propelauth/open-propelauth-user-api/)
- [PropelAuth End-User API Keys Access Tokens Users API](https://apis.io/collections/propelauth/open-propelauth-users-api/)
- [PropelAuth End-User API Keys Access Tokens Validation API](https://apis.io/collections/propelauth/open-propelauth-validation-api/)
- [PropelAuth End-User API Keys API](https://apis.io/collections/propelauth/postman-propelauth-api-keys-api/)
- [PropelAuth MCP Authentication API](https://apis.io/collections/propelauth/postman-propelauth-mcp-api/)
- [PropelAuth OAuth2 API](https://apis.io/collections/propelauth/postman-propelauth-oauth2-api/)
- [PropelAuth Organization API](https://apis.io/collections/propelauth/postman-propelauth-org-api/)
- …and 1 more published on APIs.io

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [PropelAuth — jsonschema rules](https://apis.io/rules/propelauth/propelauth-jsonschema-spectral-rules/)
- [PropelAuth API Rules](https://apis.io/rules/propelauth/propelauth-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Propelauth Authentication](https://apis.io/security/propelauth/propelauth-authentication/)
- [Propelauth Domain Security](https://apis.io/security/propelauth/propelauth-domain-security/)
- [Propelauth Trust Center](https://apis.io/security/propelauth/propelauth-trust-center/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Propelauth Plans Pricing](https://apis.io/plans/propelauth/propelauth-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Propelauth Rate Limits](https://apis.io/rate-limits/propelauth/propelauth-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Propelauth Finops](https://apis.io/finops/propelauth/propelauth-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.propelauth.com/)
- [Documentation](https://docs.propelauth.com)
- [Getting started](https://docs.propelauth.com/getting-started)
- [Pricing](https://www.propelauth.com/pricing)
- [Blog](https://www.propelauth.com/blog)
- [Terms of service](https://www.propelauth.com/legal/terms-of-service)
- [Privacy policy](https://www.propelauth.com/legal/privacy-policy)
- [GitHub](https://github.com/PropelAuth)
- [Status](https://status.propelauth.com/)

## API Evangelist rating

**Kin Score 56.5** — strong · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 62.5 |
| Contract quality | 61.9 |
| Contract governance | 27.3 |
| Operational transparency | 28.9 |
| Developer ergonomics | 63.1 |
| Access clarity | 68.4 |

**Agent readiness 22.1** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | partial |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |

**Regulatory alignment 29.4** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/propelauth/](https://apis.io/providers/propelauth/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for PropelAuth: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/propelauth/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).

# Clerk (clerk-dev)

Clerk is a complete authentication and user management platform for web and mobile apps, providing embeddable UI components, SDKs, and REST APIs to handle sign-up and sign-in, users, organizations and memberships, sessions, multi-factor authentication, JWTs and JWT templates, JWKS, SAML/enterprise SSO, OAuth applications, and email/SMS verification. The Clerk Backend API (base `https://api.clerk.com/v1`, secret-key authenticated) manages these resources server-side, the Frontend API drives client auth flows, and change events are delivered as Svix-powered HTTP webhooks.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/clerk-dev/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/clerk-dev/refs/heads/main/apis.yml)

## Tags

- Authentication
- User Management
- Identity
- Sessions
- Organizations
- SSO
- JWT
- MFA

## Timestamps

- **Created:** 2026-07-02
- **Modified:** 2026-07-02

## APIs

### Clerk Users API

Create, list, count, retrieve, update, and delete users, plus ban/unban, lock/unlock, manage public/private/unsafe metadata, verify passwords and TOTP, and remove MFA factors, passkeys, and external accounts.

- **Human URL:** [https://clerk.com/docs/reference/backend-api/tag/Users](https://clerk.com/docs/reference/backend-api/tag/Users)
- **Base URL:** `https://api.clerk.com/v1`

#### Tags

- Users
- Identity
- User Management

#### Properties

- [Documentation](https://clerk.com/docs/reference/backend-api)
- [API Reference](https://clerk.com/docs/reference/backend-api/tag/Users)
- [OpenAPI](openapi/clerk-dev-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/clerk-dev.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/clerk-dev.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Clerk Organizations API

Create, list, retrieve, update, and delete organizations, manage organization metadata and logos, and read organization billing subscriptions and credits for multi-tenant B2B applications.

- **Human URL:** [https://clerk.com/docs/reference/backend-api/tag/Organizations](https://clerk.com/docs/reference/backend-api/tag/Organizations)
- **Base URL:** `https://api.clerk.com/v1`

#### Tags

- Organizations
- B2B
- Tenancy

#### Properties

- [API Reference](https://clerk.com/docs/reference/backend-api/tag/Organizations)
- [OpenAPI](openapi/clerk-dev-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/clerk-dev.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/clerk-dev.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Clerk Organization Memberships API

Add members to an organization, list an organization's memberships, update a member's role, update membership metadata, and remove members from an organization.

- **Human URL:** [https://clerk.com/docs/reference/backend-api/tag/Organization-Memberships](https://clerk.com/docs/reference/backend-api/tag/Organization-Memberships)
- **Base URL:** `https://api.clerk.com/v1`

#### Tags

- Organizations
- Memberships
- Roles

#### Properties

- [API Reference](https://clerk.com/docs/reference/backend-api/tag/Organization-Memberships)
- [OpenAPI](openapi/clerk-dev-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/clerk-dev.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/clerk-dev.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Clerk Organization Invitations API

Create single and bulk organization invitations, list all or pending invitations for an organization, retrieve an invitation, and revoke a pending organization invitation.

- **Human URL:** [https://clerk.com/docs/reference/backend-api/tag/Organization-Invitations](https://clerk.com/docs/reference/backend-api/tag/Organization-Invitations)
- **Base URL:** `https://api.clerk.com/v1`

#### Tags

- Organizations
- Invitations
- Onboarding

#### Properties

- [API Reference](https://clerk.com/docs/reference/backend-api/tag/Organization-Invitations)
- [OpenAPI](openapi/clerk-dev-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/clerk-dev.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/clerk-dev.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Clerk Sessions API

List and create sessions, retrieve a session, refresh or revoke a session, and mint short-lived session tokens - including tokens shaped by a named JWT template - for authenticating requests to your own backend.

- **Human URL:** [https://clerk.com/docs/reference/backend-api/tag/Sessions](https://clerk.com/docs/reference/backend-api/tag/Sessions)
- **Base URL:** `https://api.clerk.com/v1`

#### Tags

- Sessions
- Tokens
- Authentication

#### Properties

- [API Reference](https://clerk.com/docs/reference/backend-api/tag/Sessions)
- [OpenAPI](openapi/clerk-dev-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/clerk-dev.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/clerk-dev.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Clerk Clients API

List clients, retrieve a client by ID, and verify a client token. A client represents a browser or mobile device and tracks the sessions active on that device.

- **Human URL:** [https://clerk.com/docs/reference/backend-api/tag/Clients](https://clerk.com/docs/reference/backend-api/tag/Clients)
- **Base URL:** `https://api.clerk.com/v1`

#### Tags

- Clients
- Devices
- Sessions

#### Properties

- [API Reference](https://clerk.com/docs/reference/backend-api/tag/Clients)
- [OpenAPI](openapi/clerk-dev-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/clerk-dev.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/clerk-dev.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Clerk Sign-ups & Sign-in Tokens API

Retrieve and update sign-up attempts, mint and revoke one-time sign-in tokens for passwordless entry, and issue and revoke actor tokens that let a privileged user impersonate another user.

- **Human URL:** [https://clerk.com/docs/reference/backend-api/tag/Sign-in-Tokens](https://clerk.com/docs/reference/backend-api/tag/Sign-in-Tokens)
- **Base URL:** `https://api.clerk.com/v1`

#### Tags

- Sign Up
- Sign In
- Tokens

#### Properties

- [API Reference](https://clerk.com/docs/reference/backend-api/tag/Sign-in-Tokens)
- [OpenAPI](openapi/clerk-dev-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/clerk-dev.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/clerk-dev.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Clerk JWT Templates API

Create, list, retrieve, update, and delete JWT templates - named claim shapes used to mint custom session tokens for third-party integrations (Supabase, Hasura, Firebase, and your own services).

- **Human URL:** [https://clerk.com/docs/reference/backend-api/tag/JWT-Templates](https://clerk.com/docs/reference/backend-api/tag/JWT-Templates)
- **Base URL:** `https://api.clerk.com/v1`

#### Tags

- JWT
- Templates
- Tokens

#### Properties

- [API Reference](https://clerk.com/docs/reference/backend-api/tag/JWT-Templates)
- [OpenAPI](openapi/clerk-dev-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/clerk-dev.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/clerk-dev.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Clerk JWKS API

Retrieve the JSON Web Key Set (JWKS) of public keys used to verify the signatures of Clerk-issued JWTs. This endpoint is unauthenticated and not rate limited.

- **Human URL:** [https://clerk.com/docs/reference/backend-api/tag/JWKS](https://clerk.com/docs/reference/backend-api/tag/JWKS)
- **Base URL:** `https://api.clerk.com/v1`

#### Tags

- JWKS
- Public Keys
- JWT

#### Properties

- [API Reference](https://clerk.com/docs/reference/backend-api/tag/JWKS)
- [OpenAPI](openapi/clerk-dev-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/clerk-dev.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/clerk-dev.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Clerk Email & SMS API

Create and manage user email addresses and phone numbers, prepare and attempt their verification, and read, edit, preview, revert, and toggle delivery of the instance's email and SMS templates.

- **Human URL:** [https://clerk.com/docs/reference/backend-api/tag/Email-Addresses](https://clerk.com/docs/reference/backend-api/tag/Email-Addresses)
- **Base URL:** `https://api.clerk.com/v1`

#### Tags

- Email
- SMS
- Verification

#### Properties

- [API Reference](https://clerk.com/docs/reference/backend-api/tag/Email-Addresses)
- [OpenAPI](openapi/clerk-dev-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/clerk-dev.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/clerk-dev.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Clerk Allowlist & Blocklist API

List, add, and delete allowlist and blocklist identifiers (email addresses, phone numbers, or web3 wallets) to restrict which identifiers may or may not sign up to an instance.

- **Human URL:** [https://clerk.com/docs/reference/backend-api/tag/Allow-list-Block-list](https://clerk.com/docs/reference/backend-api/tag/Allow-list-Block-list)
- **Base URL:** `https://api.clerk.com/v1`

#### Tags

- Allowlist
- Blocklist
- Access Control

#### Properties

- [API Reference](https://clerk.com/docs/reference/backend-api/tag/Allow-list-Block-list)
- [OpenAPI](openapi/clerk-dev-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/clerk-dev.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/clerk-dev.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Clerk Invitations API

Create single and bulk application invitations that email a user a link to sign up, list all invitations, and revoke a pending invitation.

- **Human URL:** [https://clerk.com/docs/reference/backend-api/tag/Invitations](https://clerk.com/docs/reference/backend-api/tag/Invitations)
- **Base URL:** `https://api.clerk.com/v1`

#### Tags

- Invitations
- Onboarding
- Email

#### Properties

- [API Reference](https://clerk.com/docs/reference/backend-api/tag/Invitations)
- [OpenAPI](openapi/clerk-dev-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/clerk-dev.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/clerk-dev.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Clerk SAML & Enterprise Connections API

Create, list, retrieve, update, and delete SAML connections and enterprise (SAML/OIDC) connections that let organizations sign in via their own identity provider, plus run connection test runs.

- **Human URL:** [https://clerk.com/docs/reference/backend-api/tag/SAML-Connections](https://clerk.com/docs/reference/backend-api/tag/SAML-Connections)
- **Base URL:** `https://api.clerk.com/v1`

#### Tags

- SAML
- SSO
- Enterprise

#### Properties

- [API Reference](https://clerk.com/docs/reference/backend-api/tag/SAML-Connections)
- [OpenAPI](openapi/clerk-dev-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/clerk-dev.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/clerk-dev.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Clerk OAuth Applications API

Create, list, retrieve, update, and delete OAuth applications where Clerk acts as the identity provider, rotate client secrets, upload a logo, revoke access tokens, and verify OAuth access tokens.

- **Human URL:** [https://clerk.com/docs/reference/backend-api/tag/OAuth-Applications](https://clerk.com/docs/reference/backend-api/tag/OAuth-Applications)
- **Base URL:** `https://api.clerk.com/v1`

#### Tags

- OAuth
- Applications
- Authorization

#### Properties

- [API Reference](https://clerk.com/docs/reference/backend-api/tag/OAuth-Applications)
- [OpenAPI](openapi/clerk-dev-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/clerk-dev.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/clerk-dev.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Clerk Webhooks API

Create and delete the Svix-powered webhook portal that delivers Clerk events (user.created, session.created, organization.updated, and more) as signed HTTP POST requests, and generate a Svix dashboard URL for managing endpoints.

- **Human URL:** [https://clerk.com/docs/reference/backend-api/tag/Webhooks](https://clerk.com/docs/reference/backend-api/tag/Webhooks)
- **Base URL:** `https://api.clerk.com/v1`

#### Tags

- Webhooks
- Svix
- Events

#### Properties

- [Documentation](https://clerk.com/docs/webhooks/overview)
- [API Reference](https://clerk.com/docs/reference/backend-api/tag/Webhooks)
- [OpenAPI](openapi/clerk-dev-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/clerk-dev.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/clerk-dev.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/clerk)
- [LinkedIn](https://www.linkedin.com/company/clerkinc)
- [Website](https://clerk.com/)
- [Documentation](https://clerk.com/docs)
- [Plans](plans/clerk-dev-plans-pricing.yml)
- [Rate Limits](rate-limits/clerk-dev-rate-limits.yml)
- [Fin Ops](finops/clerk-dev-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com

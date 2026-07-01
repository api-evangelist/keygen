# Keygen (keygen)

Keygen is a software licensing, entitlements, and distribution API for desktop, on-prem, IoT, and other installed applications. It issues license keys, activates and tracks machines, enforces policy-based entitlements, and distributes releases and artifacts for auto-updates. Keygen ships as the source-available, self-hostable Keygen CE / EE and as the managed Keygen Cloud, exposing a JSON:API interface under api.keygen.sh.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/keygen/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/keygen/refs/heads/main/apis.yml)

## Tags

- Software Licensing
- Entitlements
- License Keys
- Machine Activation
- Distribution
- Auto-Update

## Timestamps

- **Created:** 2026-07-01
- **Modified:** 2026-07-01

## APIs

### Keygen Licenses API

Create, retrieve, update, delete, suspend, reinstate, and renew license keys; validate a license key by ID or key, and check licenses out or in for offline use. JSON:API over application/vnd.api+json.

- **Human URL:** [https://keygen.sh/docs/api/licenses/](https://keygen.sh/docs/api/licenses/)
- **Base URL:** `https://api.keygen.sh/v1/accounts/{account}`

#### Tags

- Licenses
- License Keys
- Validation

#### Properties

- [Documentation](https://keygen.sh/docs/api/licenses/)
- [API Reference](https://keygen.sh/docs/api/licenses/)
- [OpenAPI](openapi/keygen-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/keygen.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/keygen.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Keygen Machines / Activation API

Activate a machine against a license by hardware fingerprint, list and manage activated machines, send heartbeat pings to keep node-locked activations alive, and check machines out or in for offline activation.

- **Human URL:** [https://keygen.sh/docs/api/machines/](https://keygen.sh/docs/api/machines/)
- **Base URL:** `https://api.keygen.sh/v1/accounts/{account}`

#### Tags

- Machines
- Activation
- Fingerprint

#### Properties

- [Documentation](https://keygen.sh/docs/api/machines/)
- [OpenAPI](openapi/keygen-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/keygen.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/keygen.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Keygen Policies API

Define the licensing model - expiration, machine and core limits, floating vs node-locked, check-in cadence, encryption and cryptographic scheme, and overage strategy - that governs the licenses derived from a policy.

- **Human URL:** [https://keygen.sh/docs/api/policies/](https://keygen.sh/docs/api/policies/)
- **Base URL:** `https://api.keygen.sh/v1/accounts/{account}`

#### Tags

- Policies
- Rules
- Enforcement

#### Properties

- [Documentation](https://keygen.sh/docs/api/policies/)
- [OpenAPI](openapi/keygen-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/keygen.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/keygen.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Keygen Products API

Manage the products (applications) an account licenses and distributes, including distribution strategy, platforms, and the product tokens used for server-side automation.

- **Human URL:** [https://keygen.sh/docs/api/products/](https://keygen.sh/docs/api/products/)
- **Base URL:** `https://api.keygen.sh/v1/accounts/{account}`

#### Tags

- Products
- Applications

#### Properties

- [Documentation](https://keygen.sh/docs/api/products/)
- [OpenAPI](openapi/keygen-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/keygen.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/keygen.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Keygen Users API

Create and manage end users and license owners, assign roles, ban or unban users, and update passwords - the identities that own and validate licenses.

- **Human URL:** [https://keygen.sh/docs/api/users/](https://keygen.sh/docs/api/users/)
- **Base URL:** `https://api.keygen.sh/v1/accounts/{account}`

#### Tags

- Users
- Accounts
- Owners

#### Properties

- [Documentation](https://keygen.sh/docs/api/users/)
- [OpenAPI](openapi/keygen-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/keygen.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/keygen.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Keygen Entitlements API

Define named entitlements (feature flags) and attach or detach them from policies and licenses to gate product features and enforce fine-grained permissions per customer.

- **Human URL:** [https://keygen.sh/docs/api/entitlements/](https://keygen.sh/docs/api/entitlements/)
- **Base URL:** `https://api.keygen.sh/v1/accounts/{account}`

#### Tags

- Entitlements
- Feature Flags
- Permissions

#### Properties

- [Documentation](https://keygen.sh/docs/api/entitlements/)
- [OpenAPI](openapi/keygen-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/keygen.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/keygen.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Keygen Releases / Distribution API

Publish, list, and manage semver-tagged releases for software distribution and auto-update, resolving upgrades for an entitled license across channels (stable, beta, alpha, rc) and platforms.

- **Human URL:** [https://keygen.sh/docs/api/releases/](https://keygen.sh/docs/api/releases/)
- **Base URL:** `https://api.keygen.sh/v1/accounts/{account}`

#### Tags

- Releases
- Distribution
- Auto-Update

#### Properties

- [Documentation](https://keygen.sh/docs/api/releases/)
- [OpenAPI](openapi/keygen-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/keygen.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/keygen.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Keygen Artifacts API

Upload, download, and yank the binary artifacts attached to a release - installers, packages, and update files - with redirect-based downloads gated by license entitlement.

- **Human URL:** [https://keygen.sh/docs/api/artifacts/](https://keygen.sh/docs/api/artifacts/)
- **Base URL:** `https://api.keygen.sh/v1/accounts/{account}`

#### Tags

- Artifacts
- Binaries
- Downloads

#### Properties

- [Documentation](https://keygen.sh/docs/api/artifacts/)
- [OpenAPI](openapi/keygen-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/keygen.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/keygen.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Keygen Tokens / Auth API

Generate, list, retrieve, regenerate, and revoke bearer tokens - admin, environment, product, user, and license tokens - and authenticate via HTTP Basic or license-key auth to obtain scoped access.

- **Human URL:** [https://keygen.sh/docs/api/tokens/](https://keygen.sh/docs/api/tokens/)
- **Base URL:** `https://api.keygen.sh/v1/accounts/{account}`

#### Tags

- Tokens
- Authentication
- API Keys

#### Properties

- [Documentation](https://keygen.sh/docs/api/authentication/)
- [API Reference](https://keygen.sh/docs/api/tokens/)
- [OpenAPI](openapi/keygen-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/keygen.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/keygen.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Keygen Webhooks API

Register webhook endpoints and consume signed webhook events for license, machine, user, release, and process lifecycle changes; retrieve and retry recorded webhook event deliveries.

- **Human URL:** [https://keygen.sh/docs/api/webhooks/](https://keygen.sh/docs/api/webhooks/)
- **Base URL:** `https://api.keygen.sh/v1/accounts/{account}`

#### Tags

- Webhooks
- Events
- Notifications

#### Properties

- [Documentation](https://keygen.sh/docs/api/webhooks/)
- [OpenAPI](openapi/keygen-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/keygen.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/keygen.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Keygen Machine Components API

Track individual hardware components (CPUs, drives, GPUs) that make up a machine fingerprint for stricter, component-level node-locking and anti-tamper enforcement.

- **Human URL:** [https://keygen.sh/docs/api/components/](https://keygen.sh/docs/api/components/)
- **Base URL:** `https://api.keygen.sh/v1/accounts/{account}`

#### Tags

- Components
- Hardware
- Fingerprint

#### Properties

- [Documentation](https://keygen.sh/docs/api/components/)
- [OpenAPI](openapi/keygen-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/keygen.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/keygen.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Keygen Machine Processes API

Spawn, heartbeat, and kill concurrent processes running on an activated machine to enforce per-process concurrency limits and meter floating-license usage.

- **Human URL:** [https://keygen.sh/docs/api/processes/](https://keygen.sh/docs/api/processes/)
- **Base URL:** `https://api.keygen.sh/v1/accounts/{account}`

#### Tags

- Processes
- Concurrency
- Metering

#### Properties

- [Documentation](https://keygen.sh/docs/api/processes/)
- [OpenAPI](openapi/keygen-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/keygen.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/keygen.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/keygen-sh)
- [LinkedIn](https://www.linkedin.com/company/keygen-sh)
- [Website](https://keygen.sh/)
- [Documentation](https://keygen.sh/docs/api/)
- [Plans](plans/keygen-plans-pricing.yml)
- [Rate Limits](rate-limits/keygen-rate-limits.yml)
- [Fin Ops](finops/keygen-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com

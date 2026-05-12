# deriv-api-schemas

JSON schema bundles for the Deriv WebSocket and REST trading APIs.

Each [release](../../releases) contains `schemas.zip` — a versioned snapshot of
all WebSocket and REST API schemas, published automatically when schemas change.

## Download

**Latest release:**

```
https://github.com/deriv-com/deriv-api-schemas/releases/latest/download/schemas.zip
```

**Pinned version (recommended for integrations):**

```
https://github.com/deriv-com/deriv-api-schemas/releases/download/{tag}/schemas.zip
```

Example:

```
https://github.com/deriv-com/deriv-api-schemas/releases/download/production_v20260430_0/schemas.zip
```

No authentication required — this repository is public.

## What's in schemas.zip

- `*.schema.json` — WebSocket API request and response schemas
- `rest-api-openapi.json` — REST API OpenAPI specification

## Latest schemas

The `schemas/` directory in this repository always contains the latest versions
of all schema files. You can browse them directly on the
[main branch](../../tree/master/schemas).

To track changes over time, view the
[commit history for the schemas directory](../../commits/master/schemas).

## Releases

Browse all releases and changelogs at
[github.com/deriv-com/deriv-api-schemas/releases](https://github.com/deriv-com/deriv-api-schemas/releases).

Release notes list only the schema files changed in each version.

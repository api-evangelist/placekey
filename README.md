# Placekey (placekey)

Placekey is a free, universal identifier for any physical place, designed to make it easy to join and match address and point-of-interest data across disparate datasets. The Placekey API resolves an address or latitude/longitude into a single Placekey, supporting both single and bulk (up to 100 per batch) lookups for address matching, deduplication, and data enrichment.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/placekey/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/placekey/refs/heads/main/apis.yml)

## Tags

- Location
- Geocoding
- Address Matching
- Identifiers
- POI

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Placekey Lookup API

Resolves a single address, point-of-interest, or latitude/longitude coordinate pair into a universal Placekey identifier via POST /placekey, using the apikey header for authentication.

- **Human URL:** [https://docs.placekey.io/documentation/placekey-api/quick-start](https://docs.placekey.io/documentation/placekey-api/quick-start)
- **Base URL:** `https://api.placekey.io/v1`

#### Tags

- Lookup
- Address Matching
- Geocoding

#### Properties

- [Documentation](https://docs.placekey.io/documentation/placekey-api/quick-start)
- [API Reference](https://docs.placekey.io/documentation/placekey-api/response)
- [OpenAPI](openapi/placekey-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/placekey.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/placekey.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Placekey Bulk Lookup API

Resolves up to 100 queries per request into Placekey identifiers via POST /placekeys, with an optional per-query query_id echoed back; all queries in a batch must share the same iso_country_code.

- **Human URL:** [https://docs.placekey.io/documentation/placekey-api/bulk-api](https://docs.placekey.io/documentation/placekey-api/bulk-api)
- **Base URL:** `https://api.placekey.io/v1`

#### Tags

- Bulk
- Batch
- Address Matching

#### Properties

- [Documentation](https://docs.placekey.io/documentation/placekey-api/bulk-api)
- [API Reference](https://docs.placekey.io/documentation/placekey-api/response)
- [OpenAPI](openapi/placekey-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/placekey.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/placekey.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/Placekey)
- [LinkedIn](https://www.linkedin.com/company/placekey)
- [Website](https://www.placekey.io)
- [Documentation](https://docs.placekey.io)
- [Plans](plans/placekey-plans-pricing.yml)
- [Rate Limits](rate-limits/placekey-rate-limits.yml)
- [Fin Ops](finops/placekey-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com

# SearchStax (searchstax)

SearchStax is a managed Solr search infrastructure company that provides cloud-hosted Apache Solr deployments and a Site Search platform. SearchStax eliminates the complexity of running and scaling Solr by offering fully managed dedicated and serverless deployments on AWS, Azure, and Google Cloud. The platform exposes a comprehensive REST Provisioning API for managing deployments, backup and restore, authentication, webhooks, and infrastructure configuration, along with a Site Search API for delivering search results from SearchStax Studio applications.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/searchstax/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/searchstax/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Search
- Solr
- Managed Search
- Search Infrastructure
- Full-Text Search
- Site Search

## Timestamps

- **Created:** 2026-05-02
- **Modified:** 2026-05-19

## APIs

### SearchStax Provisioning API

The SearchStax Provisioning API is a REST interface for creating and managing Solr deployments in the SearchStax Managed Search cloud. It supports deployment lifecycle management, backup and restore operations, node management, plan listing, usage reporting, authentication configuration, webhook management, and ZooKeeper configuration. Token-based authentication is used for most operations, with API key authentication available for a subset of deployment management functions.

- **Human URL:** [https://www.searchstax.com/docs/searchstax-cloud-apis-overview/](https://www.searchstax.com/docs/searchstax-cloud-apis-overview/)
- **Base URL:** `https://app.searchstax.com/api/rest/v2`

#### Tags

- Provisioning
- Solr
- Deployments
- Infrastructure

#### Properties

- [OpenAPI](openapi/searchstax-provisioning-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/searchstax-provisioning.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/searchstax-provisioning.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://www.searchstax.com/docs/searchstax-cloud-apis-overview/)
- [Documentation](https://www.searchstax.com/docs/searchstax-cloud-deployment-api/)

### SearchStax Site Search API

The SearchStax Site Search API returns JSON search results from a SearchStax Studio Site Search application. It provides real-time search via the /emselect endpoint, supporting faceted search, auto-suggest, popular searches, related searches, and search analytics tracking.

- **Human URL:** [https://www.searchstax.com/docs/searchstudio/searchstax-studio-search-api/](https://www.searchstax.com/docs/searchstudio/searchstax-studio-search-api/)
- **Base URL:** `https://search.searchstax.com`

#### Tags

- Search
- Site Search
- Studio
- Full-Text Search

#### Properties

- [Documentation](https://www.searchstax.com/docs/searchstudio/searchstax-studio-search-api/)
- [Postman Collection](collections/searchstax-provisioning.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/searchstax-provisioning.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/searchstax)
- [Website](https://www.searchstax.com)
- [Documentation](https://www.searchstax.com/docs/hc/searchstax-api-library/)
- [Documentation](https://www.searchstax.com/docs/searchstax-cloud-apis-overview/)
- [GitHub Organization](https://github.com/searchstax)
- [Documentation](https://www.searchstax.com/docs/searchstax-cloud-deployment-api/)
- [Documentation](https://www.searchstax.com/docs/searchstax-cloud-backup-restore-api/)
- [Documentation](https://www.searchstax.com/docs/searchstax-cloud-authentication-api/)
- [JSON Schema](json-schema/searchstax-deployment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/searchstax-deployment-structure.json)
- [J S O N L D Context](json-ld/searchstax-context.jsonld)
- [Example](examples/searchstax-list-deployments-example.json)
- [Spectral Ruleset](rules/searchstax-rules.yml)
- [Vocabulary](vocabulary/searchstax-vocabulary.yml)
- [Integrations](https://www.searchstax.com/partners/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com

# SearchStax (searchstax)

SearchStax is a managed Solr search infrastructure company that provides cloud-hosted Apache Solr deployments and a Site Search platform. SearchStax eliminates the complexity of running and scaling Solr by offering fully managed dedicated and serverless deployments on AWS, Azure, and Google Cloud. The platform exposes a comprehensive REST Provisioning API for managing deployments, backup and restore, authentication, webhooks, and infrastructure configuration, along with a Site Search API for delivering search results from SearchStax Studio applications.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/searchstax/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
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
- **Modified:** 2026-05-02

## APIs

### SearchStax Provisioning API

The SearchStax Provisioning API is a REST interface for creating and managing Solr deployments in the SearchStax Managed Search cloud. It supports deployment lifecycle management including creation, deletion, restart, backup and restore, node management, authentication configuration, webhook management, and usage reporting. Token-based authentication is used for most operations, with API key authentication available for a subset of deployment management functions.

#### Properties

- [OpenAPI](openapi/searchstax-provisioning-openapi.yml)
- [Managed Search APIs Overview](https://www.searchstax.com/docs/searchstax-cloud-apis-overview/)
- [Deployment API Documentation](https://www.searchstax.com/docs/searchstax-cloud-deployment-api/)

### SearchStax Site Search API

The SearchStax Site Search API returns JSON search results from a SearchStax Studio Site Search application. It provides real-time search via the /emselect endpoint, supporting faceted search, auto-suggest, popular searches, related searches, and search analytics tracking.

#### Properties

- [Documentation](https://www.searchstax.com/docs/searchstudio/searchstax-studio-search-api/)

## Common Properties

- [Website](https://www.searchstax.com)
- [API Library Overview](https://www.searchstax.com/docs/hc/searchstax-api-library/)
- [GitHub Organization](https://github.com/searchstax)

## Artifacts

### JSON Schema

- [Deployment Schema](json-schema/searchstax-deployment-schema.json)

### JSON Structure

- [Deployment Structure](json-structure/searchstax-deployment-structure.json)

### JSON-LD

- [Context](json-ld/searchstax-context.jsonld)

### Examples

- [List Deployments](examples/searchstax-list-deployments-example.json)

### Rules

- [Spectral Ruleset](rules/searchstax-rules.yml)

### Capabilities

- [Search Infrastructure Management](capabilities/search-infrastructure-management.yaml)
  - Shared: [Provisioning](capabilities/shared/provisioning.yaml)

### Vocabulary

- [SearchStax Vocabulary](vocabulary/searchstax-vocabulary.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com

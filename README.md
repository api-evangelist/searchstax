# SearchStax (searchstax)

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

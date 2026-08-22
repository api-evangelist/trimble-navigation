# Trimble Navigation (trimble-navigation)

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

Trimble Navigation Limited (now Trimble Inc.) is a global technology company founded in 1978 that pioneered commercial GPS technology. Trimble develops positioning, navigation, and geospatial solutions spanning construction, agriculture, transportation, and surveying industries. The company rebranded from Trimble Navigation Limited to Trimble Inc. in 2016. Its developer APIs cover GPS/GNSS positioning through Trimble Mobile Manager, high-accuracy survey integration via the Trimble Precision SDK, and geospatial data services. The positioning technology integrates GPS, laser, optical, and inertial technologies to deliver centimeter-level accuracy for professional applications.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/trimble-navigation/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/trimble-navigation/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- GPS
- GNSS
- Positioning
- Navigation
- Surveying
- Geospatial
- Construction

## Timestamps

- **Created:** 2026-05-03
- **Modified:** 2026-05-19

## APIs

### Trimble Mobile Manager API

The Trimble Mobile Manager (TMM) API provides developer interfaces for integrating high-accuracy GNSS positioning from connected Trimble receivers into custom mobile applications. Offers a local REST API for configuration and a WebSocket stream for real-time GNSS position delivery. Supports Trimble Catalyst DA2, R580, R780, R12i, R980, and SP100 receivers. Abstracts receiver hardware to enable forward-compatible precision positioning apps.

- **Human URL:** [https://developer.trimble.com/docs/mobile-manager/](https://developer.trimble.com/docs/mobile-manager/)

#### Tags

- GPS
- GNSS
- Positioning
- Surveying
- Mobile
- WebSocket

#### Properties

- [Documentation](https://developer.trimble.com/docs/mobile-manager/)
- [Getting Started](https://developer.trimble.com/docs/mobile-manager/guides/integrate/)
- [OpenAPI](openapi/trimble-mobile-manager-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/trimble-mobile-manager.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/trimble-mobile-manager.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Trimble Positioning Services API

The Trimble Advanced Positioning (TAP) Store API is a REST-based eCommerce API for purchasing and managing Trimble positioning service subscriptions including RTX correction services. Enables automated provisioning of high-accuracy correction subscriptions for fleet and field deployments.

- **Human URL:** [https://www.trimble.com/en/developer/docs](https://www.trimble.com/en/developer/docs)

#### Tags

- GPS
- GNSS Corrections
- RTX
- Positioning Services
- Subscriptions

#### Properties

- [Documentation](https://www.trimble.com/en/developer/docs)
- [Postman Collection](collections/trimble-mobile-manager.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/trimble-mobile-manager.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/trimble-oss)
- [LinkedIn](https://www.linkedin.com/company/trimble-navigation)
- [Website](https://www.trimble.com)
- [Developer Portal](https://www.trimble.com/en/developer/docs)
- [Documentation](https://developer.trimble.com/docs/mobile-manager/)
- [Getting Started](https://developer.trimble.com/docs/mobile-manager/guides/integrate/)
- [Integrations](https://www.trimble.com/en/partners)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com

# Templated (templated)

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

Templated is an API for automated image, video, and PDF generation from reusable templates. Designers build templates in a drag-and-drop editor, then the REST API renders them at scale by overriding layer content, with synchronous and asynchronous rendering, batch and multi-page output, and webhook callbacks.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/templated/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/templated/refs/heads/main/apis.yml)

## Tags

- Image Generation
- PDF Generation
- Templates
- Rendering
- Automation

## Timestamps

- **Created:** 2026-06-25
- **Modified:** 2026-06-25

## APIs

### Templated Render API

Generates an image, PDF, or video from a template by overriding layer content, with synchronous or asynchronous rendering, batch templates, custom dimensions, transparent backgrounds, multi-page merging, and webhook callbacks.

- **Human URL:** [https://templated.io/docs/renders/create/](https://templated.io/docs/renders/create/)
- **Base URL:** `https://api.templated.io/v1`

#### Tags

- Render
- Image
- PDF
- Video

#### Properties

- [Documentation](https://templated.io/docs/renders/create/)
- [API Reference](https://templated.io/docs/renders/)
- [OpenAPI](openapi/templated-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/templated.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/templated.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Templated Templates API

Lists and retrieves Template objects with optional layer and page data, supporting search, tag, dimension, and external-ID filtering plus pagination.

- **Human URL:** [https://templated.io/docs/templates/list/](https://templated.io/docs/templates/list/)
- **Base URL:** `https://api.templated.io/v1`

#### Tags

- Templates
- Layers
- Designs

#### Properties

- [Documentation](https://templated.io/docs/templates/list/)
- [API Reference](https://templated.io/docs/templates/retrieve/)
- [OpenAPI](openapi/templated-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/templated.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/templated.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Templated Renders API

Retrieves and lists previously generated Render objects, exposing their status (PENDING, COMPLETED, FAILED), output URL, dimensions, format, and source template.

- **Human URL:** [https://templated.io/docs/renders/](https://templated.io/docs/renders/)
- **Base URL:** `https://api.templated.io/v1`

#### Tags

- Renders
- Status
- History

#### Properties

- [Documentation](https://templated.io/docs/renders/)
- [API Reference](https://templated.io/docs/renders/)
- [OpenAPI](openapi/templated-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/templated.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/templated.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Templated Webhooks API

Asynchronous renders POST the completed Render object to a caller-supplied webhook_url on completion, with optional Base64-encoded JSON metadata for tracking context.

- **Human URL:** [https://templated.io/docs/renders/create/](https://templated.io/docs/renders/create/)
- **Base URL:** `https://api.templated.io/v1`

#### Tags

- Webhooks
- Async
- Callbacks

#### Properties

- [Documentation](https://templated.io/docs/renders/create/)
- [OpenAPI](openapi/templated-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/templated.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/templated.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/templated-io)
- [LinkedIn](https://www.linkedin.com/company/templated-io)
- [Website](https://templated.io/)
- [Documentation](https://templated.io/docs/)
- [Plans](plans/templated-plans-pricing.yml)
- [Rate Limits](rate-limits/templated-rate-limits.yml)
- [Fin Ops](finops/templated-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com

# Templated (templated)

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

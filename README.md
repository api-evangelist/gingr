# Gingr (gingr)

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

Gingr is pet-care business management software for dog daycare, boarding, training, and grooming facilities, covering reservations, check-in/checkout, client and pet records, feeding and medication schedules, immunizations, report cards, point of sale, and payments. Gingr publishes a JSON:API-style Partner API (api.gingr.io, X-Api-Key header, live OpenAPI/Swagger and Postman collection at docs.gingr.io) covering owners (parents), pets, bookings/reservations, invoices and payments, immunizations, and report cards, alongside an older subdomain-scoped legacy reporting API used for read-only pulls of owners and reservations.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/gingr/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/gingr/refs/heads/main/apis.yml)

## Tags

- Pet Care
- Pet Daycare
- Boarding
- Grooming
- Vertical SaaS
- Scheduling
- Payments

## Timestamps

- **Created:** 2026-07-04
- **Modified:** 2026-07-04

## APIs

### Gingr Owners API

Manage owner/client (called "parents" in Gingr) records - create, list, search, update, delete, and merge duplicate parent accounts; validate email/phone uniqueness; manage cards on file, store credit, reward points, memberships, packages, subscriptions, and signed agreements for each owner.

- **Human URL:** [https://support.gingrapp.com/hc/en-us/articles/25722122517517-Gingr-API-Functions-Reference](https://support.gingrapp.com/hc/en-us/articles/25722122517517-Gingr-API-Functions-Reference)
- **Base URL:** `https://api.gingr.io/v1`

#### Tags

- Owners
- Clients
- Parents
- CRM

#### Properties

- [Documentation](https://docs.gingr.io/documentation)
- [Documentation](https://support.gingrapp.com/hc/en-us/sections/26779521691661-Gingr-s-API)
- [OpenAPI](openapi/gingr-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/gingr.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gingr.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Gingr Pets API

Manage pet profiles belonging to an owner - create, list, get, update, delete, and merge pets; manage feeding schedules and medication schedules attached to a pet, and pet-level employee notes.

- **Human URL:** [https://support.gingrapp.com/hc/en-us/articles/25722122517517-Gingr-API-Functions-Reference](https://support.gingrapp.com/hc/en-us/articles/25722122517517-Gingr-API-Functions-Reference)
- **Base URL:** `https://api.gingr.io/v1`

#### Tags

- Pets
- Animals
- Profiles

#### Properties

- [Documentation](https://docs.gingr.io/documentation)
- [OpenAPI](openapi/gingr-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/gingr.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gingr.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Gingr Reservations API

Create and manage bookings/reservations for daycare, boarding, training, and grooming - list and filter by date, status, pet, or location; check availability of lodgings and specialists; check in, check out, accept, cancel, and estimate pricing for a booking; add services to an existing booking.

- **Human URL:** [https://support.gingrapp.com/hc/en-us/articles/25722122517517-Gingr-API-Functions-Reference](https://support.gingrapp.com/hc/en-us/articles/25722122517517-Gingr-API-Functions-Reference)
- **Base URL:** `https://api.gingr.io/v1`

#### Tags

- Reservations
- Bookings
- Scheduling
- Check-In

#### Properties

- [Documentation](https://docs.gingr.io/documentation)
- [OpenAPI](openapi/gingr-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/gingr.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gingr.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Gingr Services API

Read the facility's service catalog and operational configuration - service types and rates, booking types and categories, lodgings, locations, hours of operation, and package/membership types offered to owners.

- **Human URL:** [https://support.gingrapp.com/hc/en-us/articles/25722122517517-Gingr-API-Functions-Reference](https://support.gingrapp.com/hc/en-us/articles/25722122517517-Gingr-API-Functions-Reference)
- **Base URL:** `https://api.gingr.io/v1`

#### Tags

- Services
- Booking Types
- Locations
- Lodgings
- Configuration

#### Properties

- [Documentation](https://docs.gingr.io/documentation)
- [OpenAPI](openapi/gingr-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/gingr.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gingr.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Gingr Invoices & Payments API

List and retrieve invoices and charges, refund invoice line items, charge a card on file, pay or refund an invoice or a deposit. Complements the point-of-sale and billing flows inside the Gingr application.

- **Human URL:** [https://support.gingrapp.com/hc/en-us/articles/25722122517517-Gingr-API-Functions-Reference](https://support.gingrapp.com/hc/en-us/articles/25722122517517-Gingr-API-Functions-Reference)
- **Base URL:** `https://api.gingr.io/v1`

#### Tags

- Invoices
- Payments
- Point of Sale
- Billing

#### Properties

- [Documentation](https://docs.gingr.io/documentation)
- [OpenAPI](openapi/gingr-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/gingr.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gingr.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Gingr Vaccinations API

List and update a pet's immunization/vaccination records against the facility's configured immunization types, and pull a facility-wide list of expired pet immunizations for compliance follow-up before boarding or daycare check-in.

- **Human URL:** [https://support.gingrapp.com/hc/en-us/articles/25722122517517-Gingr-API-Functions-Reference](https://support.gingrapp.com/hc/en-us/articles/25722122517517-Gingr-API-Functions-Reference)
- **Base URL:** `https://api.gingr.io/v1`

#### Tags

- Vaccinations
- Immunizations
- Compliance
- Health Records

#### Properties

- [Documentation](https://docs.gingr.io/documentation)
- [OpenAPI](openapi/gingr-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/gingr.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gingr.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Gingr Report Cards API

Read the daily report cards Gingr generates for a pet's stay - activities, notes, and attached photo/video media shared back with the owner - plus the facility's configured report card form fields.

- **Human URL:** [https://support.gingrapp.com/hc/en-us/articles/25722122517517-Gingr-API-Functions-Reference](https://support.gingrapp.com/hc/en-us/articles/25722122517517-Gingr-API-Functions-Reference)
- **Base URL:** `https://api.gingr.io/v1`

#### Tags

- Report Cards
- Media
- Owner Communication

#### Properties

- [Documentation](https://docs.gingr.io/documentation)
- [OpenAPI](openapi/gingr-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/gingr.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gingr.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Gingr Waitlist API

Move a booking onto the waitlist when a facility is at capacity, and list/filter bookings by the wait_listed status to work the queue as space opens up.

- **Human URL:** [https://support.gingrapp.com/hc/en-us/articles/25722122517517-Gingr-API-Functions-Reference](https://support.gingrapp.com/hc/en-us/articles/25722122517517-Gingr-API-Functions-Reference)
- **Base URL:** `https://api.gingr.io/v1`

#### Tags

- Waitlist
- Capacity
- Bookings

#### Properties

- [Documentation](https://docs.gingr.io/documentation)
- [OpenAPI](openapi/gingr-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/gingr.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gingr.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/gingr-llc)
- [Website](https://www.gingrapp.com)
- [Documentation](https://support.gingrapp.com/hc/en-us)
- [Plans](plans/gingr-plans-pricing.yml)
- [Rate Limits](rate-limits/gingr-rate-limits.yml)
- [Fin Ops](finops/gingr-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com

# Gingr (gingr)

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

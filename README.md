# Hospitable (hospitable)

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

Hospitable (formerly Smartbnb) is a short-term and vacation rental automation platform for Airbnb, Vrbo, Booking.com, and direct-booking hosts and property managers. It centralizes multi-channel calendar syncing, AI-powered guest messaging in a unified inbox, cleaning and operations tasks, reviews, and a branded direct booking website. The Hospitable Public API v2 is a REST API at `https://public.api.hospitable.com/v2` that lets hosts and vendors programmatically manage properties, channel listings, reservations, guest messaging, calendar availability and pricing, and reviews, authenticated with OAuth 2.0 (for vendors) or Personal Access Tokens (for personal use). v2 webhooks push reservation, property, message, and review events to a host's server.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/hospitable/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/hospitable/refs/heads/main/apis.yml)

## Tags

- Vacation Rental
- Short-Term Rental
- Property Management
- Airbnb
- Hospitality
- Automation

## Timestamps

- **Created:** 2026-07-03
- **Modified:** 2026-07-03

## APIs

### Hospitable Properties API

List and retrieve the vacation rental properties connected to a Hospitable account, including address, capacity, amenities, house rules, photos, and the channel listings mapped to each property. The parent resource for calendar, reservations, and reviews.

- **Human URL:** [https://developer.hospitable.com/docs/public-api-docs/qc4x36uhxinx3-get-properties](https://developer.hospitable.com/docs/public-api-docs/qc4x36uhxinx3-get-properties)
- **Base URL:** `https://public.api.hospitable.com/v2`

#### Tags

- Properties
- Rentals
- Inventory

#### Properties

- [Documentation](https://developer.hospitable.com/docs/public-api-docs/d862b3ee512e6-introduction)
- [API Reference](https://developer.hospitable.com/docs/public-api-docs/qc4x36uhxinx3-get-properties)
- [OpenAPI](openapi/hospitable-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hospitable.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hospitable.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Hospitable Listings API

Access the individual channel listings (Airbnb, Vrbo, Booking.com, and Hospitable direct) that map to a property, so a single Hospitable property can be reconciled across every OTA it is published on for cross-listing aggregation.

- **Human URL:** [https://developer.hospitable.com/docs/public-api-docs/d862b3ee512e6-introduction](https://developer.hospitable.com/docs/public-api-docs/d862b3ee512e6-introduction)
- **Base URL:** `https://public.api.hospitable.com/v2`

#### Tags

- Listings
- Channels
- Airbnb

#### Properties

- [Documentation](https://developer.hospitable.com/docs/public-api-docs/d862b3ee512e6-introduction)
- [OpenAPI](openapi/hospitable-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hospitable.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hospitable.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Hospitable Reservations API

List and retrieve reservations across all connected channels, with guest details, check-in and check-out dates, status, platform, and financial breakdown (payout, host fees, taxes). Reservations can be filtered by property and date range.

- **Human URL:** [https://developer.hospitable.com/docs/public-api-docs/ih7nc1ovefrcs-get-reservations](https://developer.hospitable.com/docs/public-api-docs/ih7nc1ovefrcs-get-reservations)
- **Base URL:** `https://public.api.hospitable.com/v2`

#### Tags

- Reservations
- Bookings
- Guests

#### Properties

- [API Reference](https://developer.hospitable.com/docs/public-api-docs/ih7nc1ovefrcs-get-reservations)
- [OpenAPI](openapi/hospitable-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hospitable.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hospitable.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Hospitable Messages API

Read the guest-host message thread for a reservation and send new messages back to the guest through Hospitable's unified inbox, which relays to the underlying channel (Airbnb, Vrbo, Booking.com, or direct).

- **Human URL:** [https://developer.hospitable.com/docs/public-api-docs/n6jr1z9iwhm8w-get-reservation-messages](https://developer.hospitable.com/docs/public-api-docs/n6jr1z9iwhm8w-get-reservation-messages)
- **Base URL:** `https://public.api.hospitable.com/v2`

#### Tags

- Messaging
- Inbox
- Guest Communication

#### Properties

- [API Reference](https://developer.hospitable.com/docs/public-api-docs/n6jr1z9iwhm8w-get-reservation-messages)
- [OpenAPI](openapi/hospitable-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hospitable.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hospitable.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Hospitable Calendar API

Read a property's calendar of nightly availability, prices, and minimum-stay restrictions, and (with write access) update pricing and availability per date, which Hospitable syncs out to the connected channels.

- **Human URL:** [https://developer.hospitable.com/docs/public-api-docs/d862b3ee512e6-introduction](https://developer.hospitable.com/docs/public-api-docs/d862b3ee512e6-introduction)
- **Base URL:** `https://public.api.hospitable.com/v2`

#### Tags

- Calendar
- Availability
- Pricing

#### Properties

- [Documentation](https://developer.hospitable.com/docs/public-api-docs/d862b3ee512e6-introduction)
- [OpenAPI](openapi/hospitable-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hospitable.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hospitable.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Hospitable Reviews API

Retrieve guest reviews for a property from Airbnb and direct bookings, including rating, category scores, and public content, and respond to reviews on behalf of the host.

- **Human URL:** [https://developer.hospitable.com/docs/public-api-docs/d862b3ee512e6-introduction](https://developer.hospitable.com/docs/public-api-docs/d862b3ee512e6-introduction)
- **Base URL:** `https://public.api.hospitable.com/v2`

#### Tags

- Reviews
- Ratings
- Reputation

#### Properties

- [Documentation](https://developer.hospitable.com/docs/public-api-docs/d862b3ee512e6-introduction)
- [OpenAPI](openapi/hospitable-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hospitable.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hospitable.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Hospitable Webhooks API

Hospitable v2 webhooks push near-real-time event notifications (`reservation.created`, `reservation.changed`, `property.created/changed/deleted/merged`, `message.created`, `review.created`) as JSON POST requests to a host-configured endpoint. Webhooks are configured in the dashboard (Apps > Webhooks); delivery is retried up to five times with exponential back-off.

- **Human URL:** [https://developer.hospitable.com/docs/public-api-docs/k4ctofvqu0w8g-hospitable-api-v2](https://developer.hospitable.com/docs/public-api-docs/k4ctofvqu0w8g-hospitable-api-v2)
- **Base URL:** `https://public.api.hospitable.com/v2`

#### Tags

- Webhooks
- Events
- Notifications

#### Properties

- [Documentation](https://developer.hospitable.com/docs/public-api-docs/k4ctofvqu0w8g-hospitable-api-v2)
- [Documentation](https://help.hospitable.com/en/articles/10008203-webhooks-for-reservations-properties-messages-and-reviews)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/hospitable)
- [Website](https://hospitable.com/)
- [Documentation](https://developer.hospitable.com/docs/public-api-docs/)
- [Plans](plans/hospitable-plans-pricing.yml)
- [Rate Limits](rate-limits/hospitable-rate-limits.yml)
- [Fin Ops](finops/hospitable-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com

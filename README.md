# Hospitable (hospitable)

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

# Subaru of America (subaru-of-america)

Subaru of America, Inc. is the United States subsidiary of Subaru Corporation (Japan), headquartered in Camden, New Jersey. Founded in 1968 in Bala Cynwyd, Pennsylvania, SOA sells, services, and supports the Subaru lineup through more than 600 U.S. dealers and operates the MySubaru / STARLINK connected-vehicle platform that powers the MySubaru mobile app, owner portal, remote vehicle commands, safety and security services, in-vehicle Wi-Fi, and dealer integration. None of these surfaces are exposed as a public developer API; all known interfaces are private, OEM-internal, or partner-only.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/subaru-of-america/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** OEM / Consumer
- **Access:** Private (no public developer portal)

## Tags

- Automobiles, Automotive, Cars, Vehicles, Connected Vehicle, Telematics, OEM

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

### MySubaru Connected Services API

Private connected-vehicle backend (formerly branded Subaru STARLINK) that powers the MySubaru mobile app and owner portal. Supports remote lock / unlock, remote engine start with climate control, vehicle locate, horn and lights, door / window / sunroof status, tire pressure, fuel economy, odometer, PHEV charging, SOS emergency assistance, enhanced roadside assistance, and vehicle service reminders. No public developer portal, no published OpenAPI, no documented authentication scheme. Surface is reverse-engineered by community projects (e.g., `G-two/subarulink`) and may change without notice.

**Human URL:** [https://www.subaru.com/owners/starlink.html](https://www.subaru.com/owners/starlink.html)

#### Tags

- Connected Vehicle, Telematics, Remote Commands, Safety, Security, Mobile App Backend

#### Properties

- [Marketing](https://www.subaru.com/owners/starlink.html)
- [Owner Portal](https://www.mysubaru.com/)
- [Mobile App iOS](https://apps.apple.com/us/app/mysubaru/id1454853263)
- [Mobile App Android](https://play.google.com/store/apps/details?id=com.subaru.telematics.app.remote)
- [Third Party Client (subarulink)](https://github.com/G-two/subarulink)
- [Third Party Research](https://github.com/sgayou/subaru-starlink-research)

### MySubaru Companion Plan API

Plan tier surface (2026+ model years) covering SOS Emergency Assistance, Enhanced Roadside Assistance, Locate Vehicle, plus the premium Remote Engine Start and climate control add-ons. Subscription, plan eligibility, and entitlements are managed inside the MySubaru account; no documented public API for plan administration.

**Human URL:** [https://www.subaru.com/owners/starlink.html](https://www.subaru.com/owners/starlink.html)

#### Tags

- Subscriptions, Entitlements, Safety, Connected Vehicle

### MySubaru Safety & Security Plan API

Plan tier surface (2016-2025 model years) covering safety and security protection services with an upper tier adding Remote Engine Start and Remote Vehicle Locate. Same private backend as MySubaru Connected Services; not exposed publicly.

**Human URL:** [https://www.subaru.com/owners/starlink.html](https://www.subaru.com/owners/starlink.html)

#### Tags

- Subscriptions, Entitlements, Safety, Security, Connected Vehicle

### Subaru AT&T Wi-Fi Hotspot API

In-vehicle 4G LTE Wi-Fi hotspot service delivered through a partnership with AT&T. Activation, plan management, and data billing are handled by AT&T's connected-car backend, not by Subaru. No Subaru-side public API.

**Human URL:** [https://www.subaru.com/owners/connected-services.html](https://www.subaru.com/owners/connected-services.html)

#### Tags

- In Car Wi-Fi, Connectivity, Partner Service

### Subaru SiriusXM API

In-vehicle satellite and streaming audio service delivered through SiriusXM. Trial activation, subscription, and entitlements are managed by SiriusXM. Subaru does not expose a developer API for this surface.

**Human URL:** [https://www.subaru.com/owners/connected-services.html](https://www.subaru.com/owners/connected-services.html)

#### Tags

- Audio, Streaming, Partner Service

### Subaru Dealer Locator API

Web-facing dealer locator and inventory search powering subaru.com. Backed by an internal HTTP service; not documented or offered as a public developer API.

**Human URL:** [https://www.subaru.com/find-a-retailer.html](https://www.subaru.com/find-a-retailer.html)

#### Tags

- Dealer Locator, Inventory, Retail

### Subaru Recall Lookup API

VIN-based recall lookup exposed through subaru.com. Backed by an internal service that aggregates Subaru and NHTSA recall data; not offered as a public API. NHTSA itself provides a public VIN recall API that mirrors most of this data.

**Human URL:** [https://www.subaru.com/owners/vehicle-recalls.html](https://www.subaru.com/owners/vehicle-recalls.html)

#### Tags

- Recalls, VIN Lookup, Safety

## Common Properties

- [Website](https://www.subaru.com/)
- [Owner Portal](https://www.mysubaru.com/)
- [About](https://www.subaru.com/our-company/about-us.html)
- [Connected Services](https://www.subaru.com/owners/connected-services.html)
- [STARLINK / MySubaru](https://www.subaru.com/owners/starlink.html)
- [Customer Service](https://www.subaru.com/customer-support.html)
- [Vehicle Recalls](https://www.subaru.com/owners/vehicle-recalls.html)
- [Press Room](https://media.subaru.com/)
- [LinkedIn](https://www.linkedin.com/company/subaru-of-america)
- [X](https://x.com/subaru_usa)
- [Plans Pricing](plans/subaru-of-america-plans-pricing.yml)
- [Rate Limits](rate-limits/subaru-of-america-rate-limits.yml)
- [FinOps](finops/subaru-of-america-finops.yml)

## Notable Absences

- No public developer portal (no `developer.subaru.com`).
- No published OpenAPI, AsyncAPI, JSON Schema, or SDK from Subaru.
- No Subaru GitHub organization (`github.com/subaru-corp` and `github.com/subaru-of-america` return 404).
- No public pricing for MySubaru Connected Services tiers; pricing is surfaced inside the MySubaru account.
- No public RSS / changelog for connected-services updates.

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com

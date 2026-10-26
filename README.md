# Subaru of America (subaru-of-america)

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

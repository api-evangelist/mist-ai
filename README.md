# Juniper Mist AI (mist-ai)

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

Juniper Mist AI is the AI-driven enterprise networking platform that powers Juniper Networks' AI-Native Networking portfolio. Acquired by Juniper Networks in 2019, Mist pioneered cloud-native, microservices Wi-Fi and extended its AIOps approach across Wired Assurance (EX/QFX switches), WAN Assurance (SSR/SRX gateways), and Access Assurance (cloud NAC). The platform is anchored by Marvis — a conversational virtual network assistant — and the Mist Cloud API, an OpenAPI 3.1 surface of 736 paths and 2832 schemas served across 13 regional clouds (Global, EMEA, APAC, Federal). Real-time event flow ships over WebSocket subscriptions and outbound Webhooks; infrastructure-as-code is supported by an official Terraform provider; and indoor location is delivered through Virtual BLE with native iOS and Android SDKs.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/mist-ai/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/mist-ai/refs/heads/main/apis.yml)

## Scope

- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- AI
- AIOps
- Artificial Intelligence
- Networking
- Wi-Fi
- Wireless LAN
- WAN
- SD-WAN
- Wired
- LAN
- Access Points
- Switches
- Routers
- Marvis
- NAC
- Access Assurance
- Location Services
- Bluetooth LE
- Indoor Location
- Cloud Networking
- Microservices
- Enterprise Networking
- AI Native Networking

## Timestamps

- **Created:** 2026-05-25T00:00:00.000Z
- **Modified:** 2026-05-25

## APIs

### Juniper Mist Cloud API

The Juniper Mist Cloud API is a comprehensive REST API exposing the entire Mist AI-driven enterprise networking platform — MSPs, Organizations, Sites, Access Points, Switches, SSRs/SRX gateways, WLANs, WxLANs, RFTemplates, NACTags, PSKs, Webhooks, Marvis, SLEs, Alarms, Locations, Maps, Zones, Beacons, Assets, Clients, Guests, Inventory, Licenses, PCAPs, Stats, Insights, RRM, and Constants. 736 paths, 2832 schemas, 209 tag groups. Three authentication schemes (API token, basic auth, CSRF token) and 13 regional cloud endpoints spanning Global, EMEA, APAC. Versioning uses AABB.C.D (year/month/release/patch); current 2604.1.1.

- **Human URL:** [https://www.juniper.net/documentation/us/en/software/mist/api/http/getting-started/how-to-get-started](https://www.juniper.net/documentation/us/en/software/mist/api/http/getting-started/how-to-get-started)
- **Base URL:** `https://api.mist.com/api/v1`

#### Tags

- Networking
- Wi-Fi
- WAN
- Wired
- AIOps
- Marvis
- Access Points
- Switches
- Organizations
- Sites
- MSP

#### Properties

- [Documentation](https://www.juniper.net/documentation/us/en/software/mist/api/http/getting-started/how-to-get-started)
- [Documentation](https://www.juniper.net/documentation/us/en/software/mist/api/http/api/)
- [OpenAPI](openapi/mist-ai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/mist-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mist-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Source Code](https://github.com/mistsys/mist_openapi)

### Juniper Mist WebSocket Streaming API

Mist exposes a WebSocket channel for real-time event subscriptions including device events, location updates, presence, RSSI, stats, and Marvis events. Clients authenticate with an API token and subscribe to one or more channels scoped to an organization or site. Used to drive live dashboards, location services, and event-driven automation without polling REST.

- **Human URL:** [https://www.juniper.net/documentation/us/en/software/mist/api/http/guides/websockets/getting-started](https://www.juniper.net/documentation/us/en/software/mist/api/http/guides/websockets/getting-started)

#### Tags

- Networking
- WebSocket
- Streaming
- Real-Time
- Telemetry

#### Properties

- [Documentation](https://www.juniper.net/documentation/us/en/software/mist/api/http/guides/websockets/getting-started)
- [Code Examples](https://github.com/Mist-Automation-Programmability/mist_websocket_examples)
- [Postman Collection](collections/mist-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mist-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Juniper Mist Webhooks API

Mist Webhooks deliver outbound HTTP POST notifications for events at the Organization or Site scope. Supported topics include audits, alarms, device events, client join/disconnect/sessions, Zone enter/exit (location), occupancy, RSSI/SDK clients, and Marvis Actions. Webhooks can be configured per-topic with HTTPS targets and optional secret for signature verification.

- **Human URL:** [https://www.juniper.net/documentation/us/en/software/mist/api/http/guides/webhooks/topics](https://www.juniper.net/documentation/us/en/software/mist/api/http/guides/webhooks/topics)

#### Tags

- Networking
- Webhooks
- Events
- Notifications

#### Properties

- [Documentation](https://www.juniper.net/documentation/us/en/software/mist/api/http/guides/webhooks/topics)
- [Code Examples](https://github.com/Mist-Automation-Programmability/mist_webhook_monitor)
- [Code Examples](https://github.com/Mist-Automation-Programmability/mist_webhook_translator)
- [Code Examples](https://github.com/Mist-Automation-Programmability/mist_lambda_webhook)
- [Postman Collection](collections/mist-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mist-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Portal](https://www.mist.com/)
- [Portal](https://www.juniper.net/us/en/solutions/ai-driven-enterprise.html)
- [Documentation](https://www.juniper.net/documentation/product/us/en/mist/)
- [Documentation](https://www.juniper.net/documentation/us/en/software/mist/api/http/api/)
- [Getting Started](https://www.juniper.net/documentation/us/en/software/mist/api/http/getting-started/how-to-get-started)
- [Status Page](https://status.mist.com/)
- [Support](https://www.mist.com/support/)
- [Documentation](https://www.juniper.net/documentation/us/en/software/mist/mist-wireless/index.html)
- [Documentation](https://www.juniper.net/documentation/us/en/software/mist/mist-wired/index.html)
- [Documentation](https://www.juniper.net/documentation/us/en/software/mist/mist-wan-assurance/index.html)
- [Documentation](https://www.juniper.net/documentation/us/en/software/mist/mist-access-assurance/index.html)
- [Training](https://learningportal.juniper.net/juniper/user_activity_info.aspx?id=11584)
- [Forum](https://community.juniper.net/communities/community-home?CommunityKey=eef41fa9-dd0c-4eaf-93b6-94f08a0bf09a)
- [GitHub Organization](https://github.com/mistsys)
- [GitHub Organization](https://github.com/Mist-Automation-Programmability)
- [GitHub Organization](https://github.com/Juniper)
- [Source Code](https://github.com/mistsys/mist_openapi)
- [SDK](https://github.com/Juniper/terraform-provider-mist)
- [SDK](https://github.com/Juniper/terraform-mist-modules)
- [SDK](https://github.com/mistsys/mist-vble-ios-sdk)
- [SDK](https://github.com/mistsys/mist-vble-android-sdk)
- [Tool](https://github.com/Mist-Automation-Programmability/mist_browser_extension)
- [Tool](https://github.com/Mist-Automation-Programmability/mist_psk)
- [Tool](https://github.com/Mist-Automation-Programmability/mist_switch_operator)
- [Tool](https://github.com/Mist-Automation-Programmability/mist_switch_converter)
- [Code Examples](https://github.com/Mist-Automation-Programmability/Mist-API-Cookbook)
- [Code Examples](https://github.com/Mist-Automation-Programmability/mist_websocket_examples)
- [Terms of Service](https://www.juniper.net/us/en/legal-notices.html)
- [Privacy Policy](https://www.juniper.net/us/en/privacy-policy.html)
- [Blog](https://blogs.juniper.net/category/mist)
- [LinkedIn](https://www.linkedin.com/showcase/juniper-mist-ai/)
- [Twitter](https://twitter.com/JuniperNetworks)
- [YouTube](https://www.youtube.com/c/MistSystemsInc)
- [Changelog](https://github.com/mistsys/mist_openapi/blob/master/CHANGELOG.md)
- [Documentation](https://www.juniper.net/documentation/us/en/software/mist/api/http/getting-started/regions)
- [Features](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com
**URL:** https://apievangelist.com

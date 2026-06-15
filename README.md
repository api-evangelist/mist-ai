# Juniper Mist AI (mist-ai)

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

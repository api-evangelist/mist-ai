# Juniper Mist AI

Juniper Mist AI is the AI-driven enterprise networking platform that powers Juniper Networks' AI-Native Networking portfolio. Acquired by Juniper Networks in 2019, Mist pioneered cloud-native, microservices Wi-Fi and extended its AIOps approach across **Wired Assurance** (EX/QFX switches), **WAN Assurance** (SSR/SRX gateways), and **Access Assurance** (cloud-delivered NAC). The platform is anchored by **Marvis** — a conversational virtual network assistant — and the **Mist Cloud API**, an OpenAPI 3.1 surface of 736 paths and 2,832 schemas served across 13 regional clouds.

This repository profiles the Mist AI APIs, SDKs, and developer tools as an [APIs.json](https://apisjson.org) catalog entry.

- [API Reference](https://www.juniper.net/documentation/us/en/software/mist/api/http/api/)
- [Getting Started](https://www.juniper.net/documentation/us/en/software/mist/api/http/getting-started/how-to-get-started)
- [Status Page](https://status.mist.com/)
- [Official OpenAPI Spec](https://github.com/mistsys/mist_openapi)
- [Terraform Provider](https://github.com/Juniper/terraform-provider-mist)

## APIs Profiled

| API | Description |
|---|---|
| Juniper Mist Cloud API | The full REST surface covering MSPs, Orgs, Sites, Devices (APs, Switches, Gateways), WLANs, RFTemplates, Marvis, SLEs, Alarms, Webhooks, Locations, Maps, Zones, PSKs, NACTags, PCAPs, Stats, and Constants. |
| Juniper Mist WebSocket Streaming API | Real-time event subscriptions for device, location, presence, RSSI, stats, and Marvis events. |
| Juniper Mist Webhooks API | Outbound HTTP POST notifications for alarms, audits, device events, clients, zone enter/exit, occupancy, and Marvis Actions. |

## Artifacts

- [`openapi/mist-ai-openapi.yml`](openapi/mist-ai-openapi.yml) — Official Mist OpenAPI 3.1 specification (version 2604.1.1)
- [`apis.yml`](apis.yml) — APIs.json 0.16 catalog entry
- [`review.yml`](review.yml) — APIs.json validation review

## Regional Clouds

Mist operates 13 regional cloud endpoints across four geographies:

- **Global**: `api.mist.com`, `api.gc1.mist.com`, `api.ac2.mist.com`, `api.gc2.mist.com`, `api.gc4.mist.com`
- **EMEA**: `api.eu.mist.com`, `api.gc3.mist.com`, `api.ac6.mist.com`, `api.gc6.mist.com`
- **APAC**: `api.ac5.mist.com`, `api.gc5.mist.com`, `api.gc7.mist.com`
- **Federal**: dedicated Mist Federal Cloud (separate status)

## Authentication

- **API Token** — `Authorization: Token <api_token>` header (per-User or per-Org)
- **Basic Auth** — username/password, optional 2FA
- **OAuth2** — federated login through SAML/Azure AD/Okta/Google

## Maintainers

- Kin Lane — [API Evangelist](https://apievangelist.com)

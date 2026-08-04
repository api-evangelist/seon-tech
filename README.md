# SEON (seon-tech)

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

SEON is a Budapest-headquartered fraud prevention, AML compliance, and digital footprint analysis platform that exposes a modular REST API for fraud scoring, identity verification, email enrichment, phone enrichment, IP intelligence, BIN lookup, AML screening, device intelligence, and identity verification (IDV). SEON combines real-time enrichment of email, phone, IP, BIN, and device signals with customer-defined rules and machine learning to score risk and prevent fraud, account takeover, multi-accounting, and money laundering across digital channels.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/seon-tech/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/seon-tech/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- AML Compliance
- Device Intelligence
- Digital Footprint
- Fraud Prevention
- Identity Verification
- Risk Scoring

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

### SEON Fraud API

The SEON Fraud API is a modular API that combines email, phone number, IP, BIN, and AML APIs with device fingerprinting so customers can request and receive enriched data, applied rules, and risk scoring in a single API call to detect and prevent fraud.

- **Human URL:** [https://docs.seon.io/api-reference/fraud-api](https://docs.seon.io/api-reference/fraud-api)
- **Base URL:** `https://api.seon.io/SeonRestService/fraud-api/v2/`

#### Tags

- Fraud Detection
- Identity
- Risk Scoring

#### Properties

- [Documentation](https://docs.seon.io/api-reference/fraud-api)
- [Getting Started](https://docs.seon.io/getting-started)
- [Authentication](https://docs.seon.io/api-reference/introduction)
- [OpenAPI](openapi/seon-tech-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/seon-tech.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/seon-tech.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Plans](plans/seon-tech-plans-pricing.yml)
- [Rate Limits](rate-limits/seon-tech-rate-limits.yml)
- [Fin Ops](finops/seon-tech-finops.yml)

### SEON Email API

The SEON Email API is a standalone email enrichment endpoint that returns digital footprint data tied to an email address, including approximate minimum account age, registration status across dozens of social and online services, domain details, and disposable / free provider flags.

- **Human URL:** [https://docs.seon.io/api-reference/email-api](https://docs.seon.io/api-reference/email-api)
- **Base URL:** `https://api.seon.io/SeonRestService/email-api/v3`

#### Tags

- Email
- Enrichment
- Fraud Prevention

#### Properties

- [Documentation](https://docs.seon.io/api-reference/email-api)
- [OpenAPI](openapi/seon-tech-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/seon-tech.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/seon-tech.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SEON Phone API

The SEON Phone API returns phone-number intelligence including carrier and line-type detail, account presence across major social and messaging services (WhatsApp, Telegram, Viber, social networks), and risk signals tied to the number.

- **Human URL:** [https://docs.seon.io/api-reference/phone-api](https://docs.seon.io/api-reference/phone-api)
- **Base URL:** `https://api.seon.io/SeonRestService/phone-api/v2`

#### Tags

- Enrichment
- Fraud Prevention
- Phone

#### Properties

- [Documentation](https://docs.seon.io/api-reference/phone-api)
- [OpenAPI](openapi/seon-tech-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/seon-tech.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/seon-tech.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SEON IP API

The SEON IP API returns IP intelligence including geolocation, ISP, proxy/VPN/Tor detection, residential-proxy detection, datacenter classification, and a history of risk flags observed against the IP address.

- **Human URL:** [https://docs.seon.io/api-reference/ip-api](https://docs.seon.io/api-reference/ip-api)
- **Base URL:** `https://api.seon.io/SeonRestService/ip-api/v1`

#### Tags

- Enrichment
- Fraud Prevention
- IP Intelligence

#### Properties

- [Documentation](https://docs.seon.io/api-reference/ip-api)
- [OpenAPI](openapi/seon-tech-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/seon-tech.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/seon-tech.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SEON BIN API

The SEON BIN API returns information about a payment card given its Bank Identification Number, including issuing bank, country, card brand, card type, and validity, supporting card-not-present fraud decisions.

- **Human URL:** [https://docs.seon.io/api-reference/bin-api](https://docs.seon.io/api-reference/bin-api)
- **Base URL:** `https://api.seon.io/SeonRestService/bin-api/v1`

#### Tags

- BIN
- Enrichment
- Payments

#### Properties

- [Documentation](https://docs.seon.io/api-reference/bin-api)
- [OpenAPI](openapi/seon-tech-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/seon-tech.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/seon-tech.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SEON AML API

The SEON AML API screens individuals and entities against politically-exposed-person (PEP), sanctions, watchlist, and adverse-media data sources for anti-money-laundering compliance, with optional ongoing monitoring.

- **Human URL:** [https://docs.seon.io/api-reference/aml-api](https://docs.seon.io/api-reference/aml-api)
- **Base URL:** `https://api.seon.io/SeonRestService/aml-api/v1`

#### Tags

- AML Compliance
- PEP Screening
- Sanctions Screening

#### Properties

- [Documentation](https://docs.seon.io/api-reference/aml-api)
- [OpenAPI](openapi/seon-tech-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/seon-tech.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/seon-tech.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SEON Device Intelligence

SEON Device Intelligence is the device-fingerprinting product surfaced through JavaScript, iOS, Android, Flutter, React Native, Cordova, and Unity SDKs. Captured device signals (True Device ID, hashes, behavioral biometrics, geolocation, remote-access detection, residential-proxy and VPN detection) are returned via the Fraud API or User Session Monitoring stream.

- **Human URL:** [https://docs.seon.io/knowledge-base/device-intelligence/device-intelligence-overview](https://docs.seon.io/knowledge-base/device-intelligence/device-intelligence-overview)

#### Tags

- Device Fingerprinting
- Device Intelligence
- Fraud Prevention

#### Properties

- [Documentation](https://docs.seon.io/knowledge-base/device-intelligence/device-intelligence-overview)
- [SDK](https://github.com/seontechnologies/seon-web-sdk-public)
- [SDK](https://github.com/seontechnologies/seon-ios-sdk-public)
- [SDK](https://github.com/seontechnologies/seon-android-sdk-public)
- [SDK](https://github.com/seontechnologies/seon-sdk-flutter-plugin)
- [SDK](https://github.com/seontechnologies/seon-unity-sdk-plugin)
- [Postman Collection](collections/seon-tech.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/seon-tech.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SEON Identity Verification

SEON Identity Verification (IDV) is an AI-powered identity verification product combining document checks, biometric liveness, and enriched fraud signals. Integration is via native iOS and Android SDKs.

- **Human URL:** [https://docs.seon.io/knowledge-base/idv/identity-verification-solution](https://docs.seon.io/knowledge-base/idv/identity-verification-solution)

#### Tags

- Biometrics
- Document Verification
- Identity Verification
- KYC

#### Properties

- [Documentation](https://docs.seon.io/knowledge-base/idv/identity-verification-solution)
- [SDK](https://github.com/seontechnologies/seon-idv-sdk-ios-public)
- [SDK](https://github.com/seontechnologies/seon-idv-sdk-android-public)
- [Postman Collection](collections/seon-tech.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/seon-tech.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SEON Orchestration

SEON Orchestration lets customers compose multi-step fraud, KYC, and risk workflows that combine SEON enrichment with third-party providers. Integration is via the Orchestration SDKs for iOS, Android, Flutter, React Native, and Cordova.

- **Human URL:** [https://seon.io/products/fraud-orchestration/](https://seon.io/products/fraud-orchestration/)

#### Tags

- Fraud Orchestration
- Workflow

#### Properties

- [Documentation](https://seon.io/products/fraud-orchestration/)
- [SDK](https://github.com/seontechnologies/seon-orchestration-sdk-ios-public)
- [SDK](https://github.com/seontechnologies/seon-orchestration-sdk-android-public)
- [SDK](https://github.com/seontechnologies/seon-orchestration-sdk-flutter-public)
- [SDK](https://github.com/seontechnologies/seon-orchestration-sdk-react-native-public)
- [SDK](https://github.com/seontechnologies/seon-orchestration-sdk-cordova-public)
- [Postman Collection](collections/seon-tech.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/seon-tech.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SEON User Session Monitoring

User Session Monitoring streams in-session behavioral, device, and risk signals for continuous account-takeover and session-hijacking detection across web, iOS, and Android. Delivered via dedicated Stream SDKs.

- **Human URL:** [https://docs.seon.io/knowledge-base/device-intelligence/device-intelligence-overview](https://docs.seon.io/knowledge-base/device-intelligence/device-intelligence-overview)

#### Tags

- Account Takeover
- Behavioral Biometrics
- Session Monitoring

#### Properties

- [SDK](https://github.com/seontechnologies/seon-web-stream-sdk-public)
- [SDK](https://github.com/seontechnologies/seon-ios-stream-sdk-public)
- [SDK](https://github.com/seontechnologies/seon-android-stream-sdk-public)
- [Postman Collection](collections/seon-tech.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/seon-tech.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://seon.io/)
- [Portal](https://docs.seon.io/)
- [Documentation](https://docs.seon.io/api-reference)
- [Getting Started](https://docs.seon.io/getting-started)
- [Authentication](https://docs.seon.io/api-reference/introduction)
- [Sign Up](https://admin.seon.io/sign-up)
- [Sign In](https://admin.seon.io/)
- [Pricing](https://seon.io/pricing/)
- [Status Page](https://status.seon.io/)
- [Blog](https://seon.io/resources/)
- [Blog R S S](https://seon.io/resources/feed/)
- [Terms of Service](https://seon.io/terms-and-conditions/)
- [Privacy Policy](https://seon.io/privacy-policy/)
- [Security Policy](https://seon.io/security/)
- [Responsible Disclosure](https://seon.io/rdp/)
- [GitHub Organization](https://github.com/seontechnologies)
- [LinkedIn](https://www.linkedin.com/company/seon-tech)
- [Twitter](https://twitter.com/seon_tech)
- [Crunchbase](https://www.crunchbase.com/organization/seon-technologies)
- [Integrations](https://seon.io/partners/)
- [Customers](https://seon.io/customers/)
- [Case Studies](https://seon.io/case-studies/)
- [Careers](https://seon.io/careers/)
- [Contact Us](https://seon.io/contact-us/)
- [L L Ms Txt](https://docs.seon.io/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com

# SEON (seon-tech)

SEON is a Budapest-headquartered fraud prevention, AML compliance, and digital footprint analysis platform.
SEON exposes a modular REST API for fraud scoring, identity verification, email enrichment, phone enrichment,
IP intelligence, BIN lookup, AML screening, device intelligence, and identity verification (IDV). The platform
combines real-time enrichment of email, phone, IP, BIN, and device signals with customer-defined rules and
machine learning to score risk and prevent fraud, account takeover, multi-accounting, and money laundering
across digital channels.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/seon-tech/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- AML Compliance, Device Intelligence, Digital Footprint, Fraud Prevention, Identity Verification, Risk Scoring

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

### SEON Fraud API

Modular fraud-decision endpoint that combines email, phone, IP, BIN, and AML enrichment with device
fingerprinting and applied rules to return a risk score in a single call.

- **Docs:** https://docs.seon.io/api-reference/fraud-api
- **Base URL:** `https://api.seon.io/SeonRestService/fraud-api/v2/`
- **Tags:** Fraud Detection, Identity, Risk Scoring

### SEON Email API

Standalone email enrichment endpoint returning digital-footprint data (registration presence across dozens of
social and online services, approximate minimum age, domain detail, disposable/free flags).

- **Docs:** https://docs.seon.io/api-reference/email-api
- **Base URL:** `https://api.seon.io/SeonRestService/email-api/v3`
- **Tags:** Email, Enrichment, Fraud Prevention

### SEON Phone API

Phone-number intelligence (carrier, line-type, social presence on WhatsApp/Telegram/Viber and social networks,
risk flags).

- **Docs:** https://docs.seon.io/api-reference/phone-api
- **Base URL:** `https://api.seon.io/SeonRestService/phone-api/v2`
- **Tags:** Enrichment, Fraud Prevention, Phone

### SEON IP API

IP intelligence including geolocation, ISP, proxy/VPN/Tor/residential-proxy detection, datacenter
classification, and flag history.

- **Docs:** https://docs.seon.io/api-reference/ip-api
- **Base URL:** `https://api.seon.io/SeonRestService/ip-api/v1`
- **Tags:** Enrichment, Fraud Prevention, IP Intelligence

### SEON BIN API

Card BIN lookup returning issuing bank, country, brand, card type, and validity.

- **Docs:** https://docs.seon.io/api-reference/bin-api
- **Base URL:** `https://api.seon.io/SeonRestService/bin-api/v1`
- **Tags:** BIN, Enrichment, Payments

### SEON AML API

Screens individuals and entities against PEP, sanctions, watchlist, and adverse-media data sources with
optional ongoing monitoring.

- **Docs:** https://docs.seon.io/api-reference/aml-api
- **Base URL:** `https://api.seon.io/SeonRestService/aml-api/v1`
- **Tags:** AML Compliance, PEP Screening, Sanctions Screening

### SEON Device Intelligence

Device fingerprinting via JavaScript, iOS, Android, Flutter, React Native, Cordova, and Unity SDKs. Captures
True Device ID, hashes, behavioral biometrics, geolocation, remote-access detection, and residential-proxy/VPN
detection; signals are returned through the Fraud API or User Session Monitoring.

- **Docs:** https://docs.seon.io/knowledge-base/device-intelligence/device-intelligence-overview

### SEON Identity Verification (IDV)

AI-powered IDV product combining document verification, biometric liveness, and enriched fraud signals via
native iOS and Android SDKs.

- **Docs:** https://docs.seon.io/knowledge-base/idv/identity-verification-solution

### SEON Orchestration

Composes multi-step fraud, KYC, and risk workflows blending SEON enrichment with third-party providers via
mobile SDKs (iOS, Android, Flutter, React Native, Cordova).

- **Docs:** https://seon.io/products/fraud-orchestration/

### SEON User Session Monitoring

Streams in-session behavioral, device, and risk signals for continuous account-takeover and session-hijacking
detection across web, iOS, and Android via Stream SDKs.

## Regional Hosts

The SEON API is multi-region. Customers select the region tied to their account:

- `https://api.seon.io` — Default (EU)
- `https://api.us-east-1-main.seon.io` — US
- `https://api.ap-southeast-1-main.seon.io` — APAC
- `https://api.me-central-1-main.seon.io` — Middle East

## Authentication

All REST endpoints authenticate via an API license key passed as `X-API-KEY` in the request header. License keys
are issued from the SEON Admin Panel and can be scoped per-environment.

## Artifacts

- **OpenAPI:** [openapi/seon-tech-openapi.yml](openapi/seon-tech-openapi.yml)
- **Naftiko capabilities:** [capabilities/](capabilities/)
  - Fraud, Email, Phone, IP, BIN, AML
- **Plans:** [plans/seon-tech-plans-pricing.yml](plans/seon-tech-plans-pricing.yml)
- **Rate Limits:** [rate-limits/seon-tech-rate-limits.yml](rate-limits/seon-tech-rate-limits.yml)
- **FinOps:** [finops/seon-tech-finops.yml](finops/seon-tech-finops.yml)

## Common Properties

- [Website](https://seon.io/)
- [Portal](https://docs.seon.io/)
- [Documentation](https://docs.seon.io/api-reference)
- [Getting Started](https://docs.seon.io/getting-started)
- [Authentication](https://docs.seon.io/api-reference/introduction)
- [Sign Up](https://admin.seon.io/sign-up)
- [Pricing](https://seon.io/pricing/)
- [Status](https://status.seon.io/)
- [Blog](https://seon.io/resources/)
- [Responsible Disclosure](https://seon.io/rdp/)
- [GitHub Organization](https://github.com/seontechnologies)
- [LinkedIn](https://www.linkedin.com/company/seon-tech)
- [Integrations](https://seon.io/partners/)
- [LLMs.txt](https://docs.seon.io/llms.txt)

## Maintainers

- **FN:** Kin Lane
- **Email:** kin@apievangelist.com

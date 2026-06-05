# Circle (circle)

Circle Internet Financial is the issuer of USDC and EURC and operates a developer platform for moving regulated stablecoin money across the internet. Their APIs cover programmable wallets (developer- and user-controlled), gas sponsorship, the Cross-Chain Transfer Protocol (CCTP), Gateway unified balances, the Smart Contract Platform, the Circle Payments Network (CPN) for cross-border payments, compliance, StableFX trading on Arc, and xReserve for issuing USDC-backed stablecoins.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/circle/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/circle/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Blockchain
- Compliance
- Cross-Chain
- Currency
- Money
- Payments
- Stablecoin
- Transfers
- USDC
- Wallets

## Timestamps

- **Created:** 2024-11-07
- **Modified:** 2026-05-30

## APIs

### Developer-Controlled Wallets

Create and manage server-side wallets where the application controls private keys via Circle's secure key management. Supports balances, transfers, signing, and webhook notifications.

- **Human URL:** [https://developers.circle.com/w3s/programmable-wallets](https://developers.circle.com/w3s/programmable-wallets)
- **Base URL:** `https://api.circle.com/v1/w3s`

#### Tags

- Custody
- USDC
- Wallets

#### Properties

- [Documentation](https://developers.circle.com/w3s/programmable-wallets)
- [OpenAPI](https://developers.circle.com/openapi/developer-controlled-wallets.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/circle.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/circle.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### User-Controlled Wallets

Create wallets that end users control via PIN, biometrics, or social recovery while Circle handles the cryptography. Used to embed non-custodial USDC wallets directly inside consumer apps.

- **Human URL:** [https://developers.circle.com/w3s/user-controlled-wallets](https://developers.circle.com/w3s/user-controlled-wallets)
- **Base URL:** `https://api.circle.com/v1/w3s`

#### Tags

- Custody
- End-User
- USDC
- Wallets

#### Properties

- [Documentation](https://developers.circle.com/w3s/user-controlled-wallets)
- [OpenAPI](https://developers.circle.com/openapi/user-controlled-wallets.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/circle.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/circle.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Gas Station and Paymaster

Sponsor gas fees on behalf of users or let users pay gas in USDC via Circle Paymaster, removing native-token friction from onboarding.

- **Human URL:** [https://developers.circle.com/w3s/gas-station](https://developers.circle.com/w3s/gas-station)
- **Base URL:** `https://api.circle.com/v1/w3s`

#### Tags

- Gas Sponsorship
- Paymaster
- USDC

#### Properties

- [Documentation](https://developers.circle.com/w3s/gas-station)
- [Postman Collection](collections/circle.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/circle.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cross-Chain Transfer Protocol (CCTP)

Burn-and-mint protocol for moving native USDC between supported blockchains without wrapped assets. Provides REST endpoints for attestations and a Bridge Kit SDK for frontend integration.

- **Human URL:** [https://developers.circle.com/cctp](https://developers.circle.com/cctp)

#### Tags

- Bridging
- Cross-Chain
- USDC

#### Properties

- [Documentation](https://developers.circle.com/cctp)
- [OpenAPI](https://developers.circle.com/openapi/cctp.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/circle.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/circle.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Circle Gateway

Unified USDC balance across multiple EVM chains and support for nanopayments down to $0.000001 of USDC.

- **Human URL:** [https://developers.circle.com/gateway](https://developers.circle.com/gateway)

#### Tags

- Cross-Chain
- Liquidity
- USDC

#### Properties

- [Documentation](https://developers.circle.com/gateway)
- [OpenAPI](https://developers.circle.com/openapi/gateway.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/circle.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/circle.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Smart Contract Platform

Deploy, query, and interact with smart contracts across supported blockchains, including ERC-20 and ERC-721 templates and arbitrary contract calls.

- **Human URL:** [https://developers.circle.com/w3s/smart-contract-platform](https://developers.circle.com/w3s/smart-contract-platform)
- **Base URL:** `https://api.circle.com/v1/w3s`

#### Tags

- Contracts
- EVM
- Web3

#### Properties

- [Documentation](https://developers.circle.com/w3s/smart-contract-platform)
- [OpenAPI](https://developers.circle.com/openapi/smart-contract-platform.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/circle.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/circle.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Circle Payments Network (CPN)

A network for regulated financial institutions to settle cross-border payments using USDC, with originating and beneficiary financial institution (OFI/BFI) APIs.

- **Human URL:** [https://developers.circle.com/cpn](https://developers.circle.com/cpn)

#### Tags

- Cross-Border
- Payments
- Settlement

#### Properties

- [Documentation](https://developers.circle.com/cpn)
- [OpenAPI](https://developers.circle.com/openapi/cpn-ofi.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/circle.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/circle.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Compliance Engine

Screen wallet addresses and transactions against sanctions lists and risk signals; configure rule sets and review queues for AML programs.

- **Human URL:** [https://developers.circle.com/w3s/compliance-engine](https://developers.circle.com/w3s/compliance-engine)

#### Tags

- AML
- Compliance
- Risk

#### Properties

- [Documentation](https://developers.circle.com/w3s/compliance-engine)
- [OpenAPI](https://developers.circle.com/openapi/compliance.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/circle.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/circle.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### StableFX

Stablecoin foreign-exchange trading API on the Arc blockchain for converting between USDC, EURC, and other regulated stablecoins.

- **Human URL:** [https://developers.circle.com/stablefx](https://developers.circle.com/stablefx)

#### Tags

- Arc
- FX
- Trading

#### Properties

- [Documentation](https://developers.circle.com/stablefx)
- [OpenAPI](https://developers.circle.com/openapi/stablefx.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/circle.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/circle.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### xReserve

Issue and redeem regulated stablecoins backed by USDC reserves; manage minting, burning, and reserve attestations.

- **Human URL:** [https://developers.circle.com/xreserve](https://developers.circle.com/xreserve)

#### Tags

- Issuance
- Reserves
- Stablecoin

#### Properties

- [Documentation](https://developers.circle.com/xreserve)
- [OpenAPI](https://developers.circle.com/openapi/xreserve.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/circle.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/circle.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/circleco)
- [Website](https://www.circle.com/)
- [Portal](https://developers.circle.com/)
- [Console](https://console.circle.com/)
- [Authentication](https://developers.circle.com/w3s/authentication)
- [Getting Started](https://developers.circle.com/w3s/getting-started)
- [Status Page](https://status.circle.com/)
- [Support](https://support.usdc.circle.com/)
- [Blog](https://www.circle.com/blog)
- [Community](https://discord.com/invite/buildoncircle)
- [GitHub Organization](https://github.com/circlefin)
- [Privacy Policy](https://www.circle.com/legal/privacy-policy)
- [Terms of Service](https://www.circle.com/legal/terms-of-service)
- [JSON-LD](json-ld/circle-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/circle-wallet-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/circle-transaction-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [AsyncAPI](asyncapi/circle-webhooks-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Spectral Rules](rules/circle-rules.yml) — [Spectral](https://docs.stoplight.io/docs/spectral)
- [L L Ms Txt](https://developers.circle.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com

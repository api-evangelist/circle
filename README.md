# Circle (circle)

Circle Internet Financial is the issuer of USDC and EURC and operates a developer platform for moving regulated stablecoin money across the internet. Their APIs cover programmable wallets (developer- and user-controlled), gas sponsorship, the Cross-Chain Transfer Protocol (CCTP), Gateway unified balances, the Smart Contract Platform, the Circle Payments Network (CPN) for cross-border payments, compliance, StableFX trading on Arc, and xReserve for issuing USDC-backed stablecoins.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/circle/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
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
- **Modified:** 2026-04-23

## APIs

### Developer-Controlled Wallets
Create and manage server-side wallets where the application controls private keys via Circle's secure key management. Supports balances, transfers, signing, and webhook notifications.

**Human URL:** [https://developers.circle.com/w3s/programmable-wallets](https://developers.circle.com/w3s/programmable-wallets)

#### Tags

- Custody, USDC, Wallets

#### Properties

- [Documentation](https://developers.circle.com/w3s/programmable-wallets)
- [OpenAPI](https://developers.circle.com/openapi/developer-controlled-wallets.yaml)

### User-Controlled Wallets
Create wallets that end users control via PIN, biometrics, or social recovery while Circle handles the cryptography. Used to embed non-custodial USDC wallets directly inside consumer apps.

**Human URL:** [https://developers.circle.com/w3s/user-controlled-wallets](https://developers.circle.com/w3s/user-controlled-wallets)

#### Tags

- Custody, End-User, USDC, Wallets

#### Properties

- [Documentation](https://developers.circle.com/w3s/user-controlled-wallets)
- [OpenAPI](https://developers.circle.com/openapi/user-controlled-wallets.yaml)

### Gas Station and Paymaster
Sponsor gas fees on behalf of users or let users pay gas in USDC via Circle Paymaster, removing native-token friction from onboarding.

**Human URL:** [https://developers.circle.com/w3s/gas-station](https://developers.circle.com/w3s/gas-station)

#### Tags

- Gas Sponsorship, Paymaster, USDC

#### Properties

- [Documentation](https://developers.circle.com/w3s/gas-station)

### Cross-Chain Transfer Protocol (CCTP)
Burn-and-mint protocol for moving native USDC between supported blockchains without wrapped assets. Provides REST endpoints for attestations and a Bridge Kit SDK for frontend integration.

**Human URL:** [https://developers.circle.com/cctp](https://developers.circle.com/cctp)

#### Tags

- Bridging, Cross-Chain, USDC

#### Properties

- [Documentation](https://developers.circle.com/cctp)
- [OpenAPI](https://developers.circle.com/openapi/cctp.yaml)

### Circle Gateway
Unified USDC balance across multiple EVM chains and support for nanopayments down to $0.000001 of USDC.

**Human URL:** [https://developers.circle.com/gateway](https://developers.circle.com/gateway)

#### Tags

- Cross-Chain, Liquidity, USDC

#### Properties

- [Documentation](https://developers.circle.com/gateway)
- [OpenAPI](https://developers.circle.com/openapi/gateway.yaml)

### Smart Contract Platform
Deploy, query, and interact with smart contracts across supported blockchains, including ERC-20 and ERC-721 templates and arbitrary contract calls.

**Human URL:** [https://developers.circle.com/w3s/smart-contract-platform](https://developers.circle.com/w3s/smart-contract-platform)

#### Tags

- Contracts, EVM, Web3

#### Properties

- [Documentation](https://developers.circle.com/w3s/smart-contract-platform)
- [OpenAPI](https://developers.circle.com/openapi/smart-contract-platform.yaml)

### Circle Payments Network (CPN)
A network for regulated financial institutions to settle cross-border payments using USDC, with originating and beneficiary financial institution (OFI/BFI) APIs.

**Human URL:** [https://developers.circle.com/cpn](https://developers.circle.com/cpn)

#### Tags

- Cross-Border, Payments, Settlement

#### Properties

- [Documentation](https://developers.circle.com/cpn)
- [OpenAPI](https://developers.circle.com/openapi/cpn-ofi.yaml)

### Compliance Engine
Screen wallet addresses and transactions against sanctions lists and risk signals; configure rule sets and review queues for AML programs.

**Human URL:** [https://developers.circle.com/w3s/compliance-engine](https://developers.circle.com/w3s/compliance-engine)

#### Tags

- AML, Compliance, Risk

#### Properties

- [Documentation](https://developers.circle.com/w3s/compliance-engine)
- [OpenAPI](https://developers.circle.com/openapi/compliance.yaml)

### StableFX
Stablecoin foreign-exchange trading API on the Arc blockchain for converting between USDC, EURC, and other regulated stablecoins.

**Human URL:** [https://developers.circle.com/stablefx](https://developers.circle.com/stablefx)

#### Tags

- Arc, FX, Trading

#### Properties

- [Documentation](https://developers.circle.com/stablefx)
- [OpenAPI](https://developers.circle.com/openapi/stablefx.yaml)

### xReserve
Issue and redeem regulated stablecoins backed by USDC reserves; manage minting, burning, and reserve attestations.

**Human URL:** [https://developers.circle.com/xreserve](https://developers.circle.com/xreserve)

#### Tags

- Issuance, Reserves, Stablecoin

#### Properties

- [Documentation](https://developers.circle.com/xreserve)
- [OpenAPI](https://developers.circle.com/openapi/xreserve.yaml)

## Common Properties

- [Website](https://www.circle.com/)
- [Portal](https://developers.circle.com/)
- [Console](https://console.circle.com/)
- [Authentication](https://developers.circle.com/w3s/authentication)
- [Getting Started](https://developers.circle.com/w3s/getting-started)
- [Status](https://status.circle.com/)
- [Support](https://support.usdc.circle.com/)
- [Blog](https://www.circle.com/blog)
- [Community Discord](https://discord.com/invite/buildoncircle)
- [GitHub Organization](https://github.com/circlefin)
- [Privacy Policy](https://www.circle.com/legal/privacy-policy)
- [Terms of Service](https://www.circle.com/legal/terms-of-service)
- [JSON-LD Context](json-ld/circle-context.jsonld)
- [Wallet JSON Schema](json-schema/circle-wallet-schema.json)
- [Transaction JSON Schema](json-schema/circle-transaction-schema.json)
- [Spectral Ruleset](rules/circle-rules.yml)
- [Naftiko Capabilities](capabilities/circle-capabilities.yml)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com

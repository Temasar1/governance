# Project Catalyst Fund 16

## Programmable Tokens Infrastructure for UTXOS — Cardano CIP-113

UTXOS proposes the development and integration of programmable token infrastructure based on Cardano CIP-113 into the UTXOS platform.

The project will extend UTXOS beyond traditional token and wallet infrastructure by enabling developers and businesses to create tokens with programmable rules governing their supply, transfers, vesting, compliance, and lifecycle.

The infrastructure will be built around reusable programmable-token contracts and exposed through UTXOS developer infrastructure, allowing applications to use programmable assets without having to independently implement complex on-chain logic.

The project will also develop and open-source a complete, working off-chain implementation of the CIP-113 infrastructure, enabling the wider Cardano developer ecosystem to inspect, integrate, and build upon the implementation.

### Key Use Cases

The project will demonstrate programmable tokens through several practical use cases:

- **Fully Autonomous Vested Tokens**
  - Assets released gradually according to predefined schedules or conditions without requiring manual claiming or intervention.

- **Event-Triggered Assets**
  - Tokens whose transfers, lockups, or burns are automatically executed when predefined on-chain conditions are satisfied.

- **Maximum Supply Tokens**
  - Tokens with enforceable maximum supply constraints preventing additional issuance beyond a predefined limit.

- **KYC/KYB Enabled Tokens**
  - Programmable tokens that can restrict participation or transfers based on verified KYC/KYB status through Fairway infrastructure.

- **Risk-Adjusted Stablecoin Prototype**
  - A programmable asset demonstrating how collateralization requirements or supported collateral composition can be adjusted according to predefined risk parameters.

---

## Milestone 1 — CIP-113 Foundation & Open-Source Implementation

### Goal

Develop the core CIP-113 programmable-token infrastructure and establish a working implementation that can be integrated into UTXOS.

### Deliverables

- Implement the core CIP-113 programmable-token contracts required for the project.
- Extend the existing `utxos-PG-contracts` infrastructure with reusable programmable-token components.
- Develop the complete off-chain transaction-building and interaction layer required to operate the programmable-token contracts.
- Implement basic programmable-token lifecycle operations:
  - Token creation
  - Minting
  - Burning
  - Transfers
  - Token configuration
- Implement transaction validation and error handling for programmable-token operations.
- Build automated tests covering core programmable-token functionality.
- Demonstrate a complete programmable-token lifecycle on Cardano Preview/Testnet.
- Publish the completed CIP-113 off-chain implementation as open-source code on GitHub under an Apache 2.0 licence.
- Provide initial technical documentation explaining the architecture and how the contracts and off-chain components work together.

### Expected Outcome

A complete and working CIP-113 programmable-token implementation that can serve as the foundation for the UTXOS programmable-token infrastructure and can also be independently inspected and reused by Cardano developers.

---

## Milestone 2 — UTXOS Programmable Token Infrastructure

### Goal

Integrate the CIP-113 implementation into UTXOS and provide reusable infrastructure for developers to create and manage programmable assets.

### Deliverables

- Integrate the programmable-token contracts and off-chain components into UTXOS.
- Provide UTXOS APIs/SDK abstractions for creating and configuring programmable tokens.
- Implement reusable programmable-token rules.
- Implement maximum supply enforcement.
- Implement time-based and schedule-based token vesting.
- Implement programmable transfer restrictions.
- Implement configurable token lock and burn conditions.
- Implement event-triggered token actions based on predefined on-chain conditions.
- Add transaction-building and submission support through UTXOS infrastructure.
- Add automated integration tests for the UTXOS programmable-token infrastructure.
- Deploy and demonstrate the infrastructure on Cardano Preview/Testnet.

### Expected Outcome

Developers using UTXOS can create and interact with programmable tokens without having to independently build the underlying CIP-113 contracts and transaction infrastructure.

---

## Milestone 3 — Compliance & Programmable Asset Demonstrators

### Goal

Demonstrate practical applications of the UTXOS programmable-token infrastructure using real-world tokenization and compliance requirements.

### Deliverables

- Integrate Fairway infrastructure for KYC/KYB verification.
- Implement programmable-token rules that can use verified KYC/KYB status as a condition for participation or transfers.
- Demonstrate a compliance-enabled programmable token.
- Implement and demonstrate a fully autonomous vested-token use case.
- Implement and demonstrate an event-triggered asset use case.
- Implement and demonstrate a maximum-supply token.
- Develop a prototype demonstrating risk-adjusted stablecoin behavior using programmable token rules.
- Document how developers can build additional programmable-token use cases on top of UTXOS.
- Publish reference implementations for the demonstrated use cases.

### Expected Outcome

A set of working reference applications demonstrating how UTXOS programmable tokens can support token vesting, automated asset behavior, supply controls, compliance, and programmable financial assets.

---

## Milestone 4 — Developer Release, Documentation & Ecosystem Adoption

### Goal

Make the programmable-token infrastructure accessible and useful to Cardano developers and businesses building on UTXOS.

### Deliverables

- Finalize the UTXOS programmable-token APIs and SDK abstractions.
- Provide developer documentation covering:
  - Creating programmable tokens
  - Configuring token rules
  - Minting and burning
  - Transfers
  - Maximum supply
  - Vesting
  - Event-triggered actions
  - KYC/KYB restrictions
- Publish end-to-end tutorials and working examples.
- Publish reference applications demonstrating the major programmable-token use cases.
- Add comprehensive unit and integration test coverage.
- Publish the final programmable-token infrastructure and supporting code under an Apache 2.0 open-source licence.
- Make the complete implementation available through the UTXOS GitHub repositories.
- Provide a final technical report documenting:
  - Architecture
  - Implementation
  - Supported programmable-token capabilities
  - Testing results
  - Known limitations
  - Future development opportunities
- Demonstrate the final implementation to the Cardano developer community.

### Expected Outcome

A documented and open-source programmable-token infrastructure integrated into UTXOS, providing Cardano developers with reusable infrastructure for building programmable assets and tokenized applications.

---

## Milestone Summary

| Milestone | Focus | Primary Outcome |
|---|---|---|
| **1. CIP-113 Foundation & Open-Source Implementation** | Contracts + complete off-chain implementation | Working and open-source CIP-113 implementation |
| **2. UTXOS Programmable Token Infrastructure** | UTXOS integration + reusable token rules | Programmable-token infrastructure available through UTXOS |
| **3. Compliance & Programmable Asset Demonstrators** | KYC/KYB + real-world use cases | Working programmable-token applications |
| **4. Developer Release & Ecosystem Adoption** | Documentation + release + adoption | Open-source, documented UTXOS programmable-token infrastructure |

## Mesh SDK Integration

Mesh SDK integration will be treated as a supporting ecosystem integration rather than the primary objective of the project.

Where appropriate, the project will provide the necessary transaction-building and developer-facing integrations to allow the programmable-token infrastructure to be consumed through existing Cardano developer tooling, including Mesh.

The primary infrastructure, contracts, off-chain implementation, APIs, examples, and use cases will remain centered on **UTXOS** and its existing `utxos-PG-contracts` architecture.

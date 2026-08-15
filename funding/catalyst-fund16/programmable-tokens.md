# Project Catalyst Fund 16 Proposal Template
Proposal title: - 
Requested Amount: 200,000 ADA

## Setup

### Applicant name
MeshJs/UTXOS.DEV
### Submitting as

### Supporting links
- Repository
  - https://github.com/utxos-dev/utxos-sdk
  - https://github.com/utxos-dev/utxos-PG-contracts
- Website
  - https://utxos.dev

### Is the underlying project open source?
No

---

## Product & Problem


### What solution are you building, and what specific problem does it solve — for whom?
The solution we are building is integrating a seemless, onboarding platform to usage of programmable tokens and it's integration to the cardano ecosystem, supporting the cip-113 from cardano foundation, we hope that UTXOS as a wallet infrastructure can easily implement the onboarding through our easy access to the creation of the smart wallets for the programmable tokens itself, which wou;ld take sometime to achieve by the extension or connect wallet service providers, we would create an infrastructure for smart wallets holders and easy accessibility signup and interactions to the programmable tokens, example demo minting of a max supply token same as integrating other programmable tokens substandards

### short video pitch
- 

## Business case

### Who is your target market, and what evidence shows real demand/product-market fit?
our target markets are basically enterprises and companies within and outside the cardano ecosystem interested in trying out and interactimg with the programmable token, decentralized applications which we would expose our functionalities thorugh the `@utxos/sdk` package so they can just integrate to their platforms, 

we have multiple monthly active users already, parters with Andamio for seemless transaction sponsorship and user onboarding
here are our already made stats
- over 700 MAU
- over 4,000 sdk monthly downloads
- over 1000 mothly transatcions on testnet and mainnet
- trusted and used by the ecosystem and developers

### Who else solves this today — competitors/alternatives, and why does your approach win?
The actual fact is on cardano we are the first and currently only platform that gives the wallet as a service infrastructure, No big competitor.

Our approach would win cause we already have experience, we are building on this with years of onboarding developers with the meshsdk in onboarding with track records of building what is needed and would be used rather than reinventing the wheel

### What is your business model, and what keeps this running after the pilot?
- This is where we actually specialize and one of the reasons utxos was built in the first place, utxos is strictly business first in mind
    -  we already have existing Monthly recurring revenue whereby devs pay for our sponsorship integrations, we want to extend this by making programmable tokens as a service integrating with our smart wallet payments
    - In UTXOS payments are done in teirs, for programmable token payment would follow this teir payment plan according to the complexity of the substandards integrated.
### Who pays, and why does usage continue once grant funding ends?
- Who pays? Enterprises and customers attracted does, we are well known and trusted in the communinity, good at marketing and interacting with business and consumers
- UTXOS solves a problem the Cardano ecosystem has never addressed: how to permanently fund critical open-source infrastructure without perpetual grants.The reason usage would continue when fund grant ends is because utxos has been a self-funded project, which means we've been working without funding to complemwnt with our work on MeshJs, with funds it motivates to do more and provide these services effortlessly.
- What We Built (Self-Funded)
    Complete wallet creation and management API
    Email/password authentication system
    Multi-sig wallet support
    Transaction building and signing infrastructure
    Comprehensive SDK and documentation
    Production-ready key management system


### How will you reach and onboard real users — and what evidence backs your channels?
- We'll target recently funded Catalyst proposals (F13/F14) as qualified leads - projects with fresh funding are ready to invest in infrastructure. We're also leveraging existing relationships in gaming, supply chain, and DeFi to accelerate adoption.
- We have track record to make this happen, the team is filled with experienced founders, product managers and developers, either in the blockchain space, in various ecosystem

---

## Team
Jingles K.
Founder & CEO 
      GitHub: @jinglescode
      Twitter: @jinglescode
Relevant Experience:
    - Creator and maintainer of Mesh, Cardano's most popular web3 framework
    - 10+ successful Catalyst proposals delivered (all closed out, zero outstanding reports)
    - Full-stack blockchain developer with 8+ years experience
    - Multiple Cardano ecosystem contributions (open source tools, documentation, education)
Track Record:
    - Shipped and maintained production infrastructure used by thousands of developers
    - Proven ability to deliver on funding commitments (100% Catalyst completion rate)
    - Deep understanding of Cardano technical architecture
    - Strong community standing and reputation

Emmanuel A.
Tech Lead
    GitHub: @temasar1
    twitter: @temasar_1
Relevant Experience:

Track Record:



### Why is your team well-suited to deliver this?
The UTXOS team created and maintains Mesh (https://meshjs.dev), which has:
- ~2,000,000 downloads on NPM
- Powered major Cardano applications including Minswap, FluidTokens, and NMKR
- Delivered 10+ successful Catalyst proposals (all closed out - see https://gov.meshjs.dev/catalyst-proposals)
- Comprehensive documentation and developer education materials
- Active maintenance and continuous improvement for 5+ years
UTXOS applies the same rigorous approach to wallet infrastructure that made Mesh successful.

---

## Integration

### Which integration(s) will you leverage?
- Firstly, we would leverage our time being with time interation with the programmable tokens contract, also two of our developers ontributed to the offchain temasar and Rice, with close follow up with the integrators and contributors on shaping the contract work.
- we have an offchain ready built but with old comtracts as at this time of writing still yet to have a finalized cip-113 contracts https://github.com/MeshJS/contracts/tree/main/src/programmable-tokens
- we would also leverage on following the patterns of what has been built already for example this https://github.com/cardano-foundation/cip113-programmable-tokens , https://github.com/cardano-foundation/cip113-programmable-tokens-platform/tree/main/src/substandards 

### What is the current status and Technology Readiness Level (TRL) of your existing product?
Actual system proven in operational Environment

### Please provide details about the Technology Readiness Level selected for your existing product.
UTXOS as an operational blockchain infrastructure platform that has progressed beyond the prototype and development stage into real-world use. The platform currently provides infrastructure and developer tooling across three blockchain networks; 
- Cardano,
- Bitcoin,
- and spark a l2 on bitcoin network

Our development has been driven by actual developer requirements rather than a purely theoretical roadmap, with new capabilities being developed, tested, deployed, and iterated based on real usage.

This proposal therefore does not fund the creation of UTXOS itself. It extends an already operational infrastructure platform with a new programmable-token capability based on CIP-113.

### How far along is the integration you're proposing, today?
Technology demonstrated in relevant environment

### Please provide details about the Technology Readiness Level selected for your proposed integration.

There is also strong evidence from the wider ecosystem that programmable asset rules can be integrated into higher-level wallet and financial infrastructure which really shows we are the best fit for this. For example, platforms such as Privy https://privy.io/ expose programmable wallet infrastructure, transaction controls, and APIs that allow applications to incorporate programmable rules into asset-management workflows. 

we can also replicate this on cardano using cip-113 with UTXOS by moving to the asset level abstraction which is a perfect match for our wallet as a service infrastructure, and smart wallet management.

### What is your on-chain architecture, and why is it the right fit for the selected integration(s) and this area of interest's technical requirements?

1. CIP-113 Programmable Token substandard contracts
The core token rules will be implemented through CIP-113-compatible Aiken validators because the CIP-113 programmable-token implementation is built around Aiken. This allows us to remain aligned with the existing CIP-113 architecture

2. Token Policy & Configuration Layer
Each programmable token substandards will have an associated configuration and parameters defining the rules governing its lifecycle. Depending on the use case, these parameters are being exposed in a plug-and-play style through our sdk(APIs) and the platform itself.

3. smart wallet integration: as a wallet as a service provider, this part is where we are mostly interested about cause the idea of smart wallet which holds the programmable token can be seemlessly integrated inside utxos, all tools and library already made and working fine.

4. Compliance / Identity Integration: For applicable use cases, the architecture can consume verified KYC/KYB status from Fairway infrastructure whom we've been communicating with months before now, so this translate verification into programmable-token conditions. The verification itself does not need to expose sensitive identity information on-chain; instead, the architecture can use appropriate attestations or verification state as the input to the programmable-token rules.

### What does this funding enable that wouldn't happen otherwise — and, at a high level, what will it be spent on?

This funding is important for the work that sits between "Yes, it works" and "If so, can developers can safely depend on it?" These contracts control the behavior of assets therefore  security, testing, and operational reliability are critical.

Funding will be focused on
- Core engineering and integration: completing the integration of CIP-113 contracts and off-chain infrastructure
- Security and independent review: allocating resources toward professional security review and contract auditing of the programmable token implementation
- Scalability and operational infrastructure: improving transaction construction, monitoring infrastructure capacity.
- Contract correctness and testing: developing comprehensive unit, integration, property-based, and end-to-end tests.
---

## Adoption & Fee Target

### [Integration] — expected transaction count

### [Integration] — fee target (ADA)

### How will your product generate genuine usage — who transacts, why, and how often?
### Justify your previously declared targets as reasonable but ambitious enough to be considered valid.

### Our plan complies with the Transaction Integrity Standard

---

## Milestones

### M1 outputs: What measurable, tangible deliverables will you complete within the 3-month window to reach mainnet?

# M1 Deliverables & Budget Allocation

## 1. Contracts - 40%

- **Programmable Native Asset (PNA):** User, Admin, Owner roles, mint/burn controls, max mint, max supply, blacklist and global pause.

- **Security Programmable Asset (SPA):** Extends PNA with KYC/KYB registry, compliance, verifier roles, freeze, seize, force-transfer and compliance controls.

- Contract on testnet, deployment scripts and on-chain configuration.

## 2. Security & Audit - 30%

- Unit, integration and end-to-end testing.

- Threat modelling and security review.

## 3. Wallet Infrastructure & SDK - 20%

- Social-login auth and smart wallet interactions.

- Programmable asset transaction construction and signing.

- PNA/SPA SDK APIs and on-chain to off-chain state interaction.

## 4. Infrastructure & Documentation - 10%

- Mainnet deployment and contract configuration.

- API documentation, integration guides, release notes and test evidence.

**Total: 100%**
---

## Beyond the Pilot

### Optional: Voluntary give-back pledge
N/A

---

## Acknowledgements

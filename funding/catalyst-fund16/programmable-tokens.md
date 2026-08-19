# Project Catalyst Fund 16 Proposal Template
## Proposal title:
- UTXOS Smart Wallet and Contract infra for programmable tokens???

## Requested Amount: 
- 200,000 ADA

## Tagline

## Setup

### Applicant name
UTXOS
### Submitting as
Incorporated Entity

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
The solution combines **CIP-113 substandard smart contracts with UTXOS Wallet social-login infrastructure**, allowing applications to create smart wallets through social-login (google, discord, twitter) authentication and immediately construct, sign and submit programmable-token transactions. This removes the friction of requiring users to first connect or configure specialized wallet providers and gives DApps a simpler path to integrating programmable assets.

One of the problems right now is that major non-custodian are yet to implement the smart wallet feature which holds programmable tokens, our wallet infra achieves the same result on the non-custodian part also with a touch of social login authentication which gives us an edge to onboarding users and developers quickly to interact with the programmable tokens, without having to build complex wallet and transaction infrastructure themselves.

The initial infrastructure will support what we call the **Programmable Native Assets (PNA)** with configurable minting, burning, supply limits, transfer controls and administration, alongside **Security Programmable Assets (SPA)** supporting compliance-oriented capabilities such as KYC and KYB, freeze, seize and force-transfer.

Developers will be able to integrate these capabilities through the SDK and demonstrate flows such as creating a programmable token with minting according to defined rules, transferring it through a smart wallet, and extending the same infrastructure

### short video pitch
- 

## Business case

### Who is your target market, and what evidence shows real demand/product-market fit?
Our target markets are enterprises, companies, and DApps within and outside the Cardano ecosystem that want to experiment with and integrate programmable tokens to their platform. UTXOS will expose the functionality through the @utxos/sdk, enabling developers to easily integrate programmable-asset creation, wallet interactions, and transaction capabilities directly into their platforms.

Since our mainnet launch, we've achieved:
- over 500 MAU
- over 4,000 sdk monthly downloads
- over 1000 monthly transactions on testnet and mainnet
- trusted and used by the ecosystem and developers
- 5 Active Projects in production using UTXOS infrastructure
- Stable v1 live on mainnet with proven reliability
- $200 Monthly Recurring Revenue from 1 paying enterprise customer
  
### Who else solves this today — competitors/alternatives, and why does your approach win?
The actual fact is UTXOS is Cardano's first production-ready Wallet-as-a-Service (WaaS) platform, enabling developers to integrate wallets into their applications with a single API call.

Our approach would win cause we already have experience, we are building on this with years of onboarding developers with the meshsdk in onboarding with track records of building what is needed and would be used rather than reinventing the wheel

### What is your business model, and what keeps this running after the pilot? Who pays, and why does usage continue once grant funding ends?

Our Existing business model is based on subscription in Tiers

Free, Pro ($199 Discounted Price), and Scale of $499 for Wallet as a Service, Transaction Sponsorship, Onramp

Programmable Tokens as a Service tiers:

### Free

- Limited Smart Wallet services
- Limited access to Programmable Native Asset features

### Pro

- Access capabilities to Free tier
- Increased number of managed smart wallets
- Limited access to Security Programmable Asset features

### Scale

- Access Free and Pro with advanced substandards
- Transaction sponsorship
- Dedicated support

We would keep running after the pilot because UTXOS was a self-funded project; the funds granted would accelerate the CIP-113 integration at an early stage.

On who pays, though the Basic Tier is free to experiment with, Paid tiers are targeted at enterprises, token issuers and DApps that require mainnet deployment and are serious about our infrastructure integration.

Product-market fit drives continued paid usage.

### How will you reach and onboard real users — and what evidence backs your channels?
As infrastructure builders we will reach and onboard real users through direct developer outreach, targeted email campaigns and partnerships with projects preparing for production-scale adoption.

We are also part of CIP-113 Working Group on Telegram together with our dedicated Discord channel for UTXOS in mesh discord server filled with over 700 technical builders and executives building dapps, wallets and token infrastructures, also other various discord servers and developer channels, where we can directly identify teams interested in programmable-token infrastructure. Onboarding will be through our tokenization dashboard, Smart Wallets and SDK, supported by integration guides, demos and direct technical assistance with evidence from usage and adoption

## Team

The UTXOS team created and maintains Mesh (https://meshjs.dev), which has:
- ~2,000,000 downloads on NPM
- Powered major Cardano applications including Minswap, FluidTokens, and NMKR
- Delivered 10+ successful Catalyst proposals (all closed out - see https://gov.meshjs.dev/catalyst-proposals)
- Comprehensive documentation and developer education materials
- Active maintenance and continuous improvement for 5+ years

UTXOS applies the same rigorous approach that made Mesh successful.

We include:

### Jingles K.
**Founder & CEO** 
     - GitHub: @jinglescode
     - x: @jinglescode

Relevant Experience:
    - Creator and maintainer of Mesh, Cardano's most popular web3 framework
    - Full-stack blockchain developer with 8+ years experience
    - Multiple Cardano ecosystem contributions (open source tools, documentation, education)

**Track Record:**
    - Shipped and maintained production infrastructure used by thousands of developers
    - Proven ability to deliver on funding commitments (100% Catalyst completion rate)
    - Deep understanding of Cardano technical architecture
    - Strong community standing and reputation

### Emmanuel A.

**Tech Lead**  

- GitHub: @temasar1  
- x: @temasar_1  

**Relevant Experience:**

- 5+ years of experience in blockchain with software and developer infrastructure.
- Lead developer and contributor across Cardano ecosystem projects and open-source tooling.
- Active contributor to Mesh and Gimbalabs.
---

## Integration

### Which integration(s) will you leverage?
- Programmable tokens cip-113

### What is the current status and Technology Readiness Level (TRL) of your existing product?
- TRL-9 Actual system proven in operational Environment

### Please provide details about the Technology Readiness Level selected for your existing product.
Readiness includes:
- Reliable API infrastructure
- Proven Cardano transaction and Wallet infrastructure with SDKs already operating in production
- Active documentation and developer integration resources

UTXOS has progressed beyond the prototype and development stage into real-world use. The platform currently provides infrastructure and developer tooling across three blockchain networks; 

- Cardano
- Bitcoin,
- and spark a layer-2 on bitcoin

Our development has been driven by actual developer requirements rather than a purely theoretical roadmap, with new capabilities being developed, tested, deployed, and iterated based on real usage.
This proposal therefore does not fund the creation of UTXOS itself. It extends an already operational infrastructure platform with cip-113

### How far along is the integration you're proposing, today?
TRL-6 Technology demonstrated in relevant environment

### Please provide details about the Technology Readiness Level selected for your proposed integration.

We assessed at TRL-6 because our already made infrastructure has already been demonstrated in relevant Cardano environments, while the programmable-asset layer is being integrated and validated on top of this existing infrastructure.

There is also strong evidence from the wider ecosystem these already built infrastructure can be exposed to a higher-level programmable platform. example Privy (https://privy.io/) demonstrate how wallet infrastructure, controls and hosts tokenization on ethereum which are can be abstracted for application developers, can also be demonstrated on cardano

we will apply this proven infrastructure model to architect and demonste a cardano's Programmable native assets and Security programmable assets with the cip-113 substandards

### What is your on-chain architecture, and why is it the right fit for the selected integration(s) and this area of interest's technical requirements?

- CIP-113 Token substandard contracts
  The core token rules will be implemented through CIP-113 compatible Aiken validators because the CIP's implementation is built around Aiken. This allows us to remain aligned with the existing architecture
- Token parameters & Configuration Layer
  Each programmable token substandards will have an associated configuration and parameters defining the rules governing its lifecycle. Depending on the use case, these parameters are being exposed in a plug-and-play style through our sdk(APIs) and the platform itself.
- Dashboard management
  Our platform includes self-managed dashboards that allow developers and issuers to directly configure and interact with deployed programmable-token contracts. 
- smart wallet integration: as a wallet as a service provider, this part is where we are mostly interested about cause the idea of smart wallet which holds the programmable token can be seemlessly integrated inside utxos, all tools and library already made and working fine.
- Compliance / Identity Integration: For applicable use cases, the architecture can consume verified KYC/KYB status, we've been meeting with Fairway infrastructure as credentials verifiers, so this translate verification into programmable-token conditions. The verification itself does not need to expose sensitive identity information on-chain; instead, the architecture can use appropriate attestations or verification state as the input to the programmable-token rules.

### What does this funding enable that wouldn't happen otherwise — and, at a high level, what will it be spent on?

This funding is important for the work that sits between "Yes, it works" and "If so, can developers can safely depend on it?" These contracts control the behavior of assets therefore  security, testing, and operational reliability are critical.

Funding will be focused on
- Core engineering and integration: completing the integration of CIP-113 substandard contracts and off-chain infrastructure
- Security and independent review: allocating resources toward professional security review and contract auditing of the programmable token implementation
- Scalability and operational infrastructure: improving on high scalability, monitoring infrastructure capacity.
- Contract correctness and testing: developing comprehensive unit, integration, property-based, and end-to-end tests.

---

## Adoption & Fee Target

### [Integration] — expected transaction count
700 Transactions

### [Integration] — fee target (ADA)
210 ADA

### How will your product generate genuine usage — who transacts, why, and how often?

- The product would generate genuine users through email campaigns, marketing and advertising across the general blockchain ecosystem, also our onramp feature which allows ADA purchase directly with credit card would contribute to the seemless onboarding from other ecosystem, we would also linkup users to bridges like wan-chain or galaxy swap.

- In cardano, we already have some serious projects like Andamio among others who are always ready to integrate our products.

with the social-login infrastructure our programmable native assets substandards would be much useful to game developers, while security programmable assets would be useful for compliance seekers.

- 210 fees in ADA and 700 transactions targets should be considered ambitious because the cip-113 is a new concept to cardano, in as much as we want to serve old and already aware cardano integrators we believe users would also come from other ecosystem, So it takes some level of technical understanding to get familiar to start using product.

Usage intervals depends on multiple factors like platforms demands but speculatively with the right user experience we expect consistent interval that would match the integrity standard.

---

## Milestones

### M1 outputs: What measurable, tangible deliverables will you complete within the 3-month window to reach mainnet?

# M1 Deliverables & Budget Allocation

## 1. Contracts/Substandards 

- **Programmable Native Asset (PNA):** User, Admin, Owner roles, mint/burn controls, max mint, max supply, blacklist and global pause, holding limits.

- **Security Programmable Asset (SPA):** Extends PNA with KYC/KYB registry, compliance, verifier roles, freeze, seize, force-transfer and compliance controls.

- **Event triggered assets:** Milestone-triggered release, Time/event expiry, bounties unlock, token vesting.

## 2. Security & Audit

- Unit, integration and end-to-end testing.
- Threat modelling and security review.

## 3. Wallet Infrastructure & SDK

- Social-login auth and smart wallet interactions.
- Programmable asset transaction construction and signing.
- PNA/SPA and Event triggered SDK APIs and on-chain to off-chain state interaction.

## 4. Infrastructure & Documentation

- Mainnet deployment and contract configuration.
- API documentation, integration guides, release notes and test evidence.

---

## Beyond the Pilot

### Optional: Voluntary give-back pledge
N/A

---

## Acknowledgements

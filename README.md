# HACKFLOW

**Independent On-Chain Forensic Research**

HACKFLOW is an independent blockchain-forensics research project focused on tracing, classifying, and documenting cryptocurrency fund flows related to security incidents, exploits, and illicit activity.

> Evidence first. Attribution second.

## Project Status

**ACTIVE RESEARCH / ACTIVE MONITORING**

Current focus:
- Bitget Security Incident — September 2026
- Cross-chain fund tracing
- Taint and exposure propagation
- Wallet/entity classification
- Freezeable endpoint detection

## Core Capabilities

- Transaction flow tracing
- Cross-chain fund tracking
- Taint and exposure analysis
- Wallet and entity classification
- DEX / CEX / bridge / router identification
- Evidence-linked forensic reporting
- High-risk address monitoring
- Public explorer label preparation

## Forensic Principles

HACKFLOW follows several core rules:

1. Taint belongs to funds and exposure, not automatically to a person.
2. A wallet receiving traced funds is not automatically classified as attacker-controlled.
3. Public labels must distinguish between:
   - confirmed exploiter addresses;
   - directly traced fund recipients;
   - cross-chain hubs;
   - consolidation wallets;
   - service endpoints;
   - mixed-exposure wallets;
   - unknown addresses.
4. Every high-confidence classification should be supported by transaction evidence.
5. Cross-chain tracing should preserve provenance across bridges and asset transformations.

## Current Case

### Bitget Security Incident — September 2026

HACKFLOW is independently reconstructing selected EVM and cross-chain fund flows associated with the incident.

Current work includes:

- primary EVM seed analysis;
- Ethereum and Arbitrum flow reconstruction;
- bridge tracing;
- swap-related asset transformation;
- downstream ETH consolidation;
- parked-wallet monitoring;
- public explorer label preparation.

Case status:

**ACTIVE MONITORING**

## Methodology

HACKFLOW combines:

- deterministic transaction parsing;
- exact-flow reconstruction where possible;
- proportional taint propagation for mixed balances;
- transaction-level evidence;
- entity classification;
- cross-chain reconciliation;
- risk scoring.

See:

- [Methodology](docs/methodology.md)
- [Labeling Policy](docs/labeling-policy.md)
- [Bitget 2026 Case](docs/bitget-2026.md)

## Public Labeling Policy

HACKFLOW avoids assigning accusatory labels without sufficient evidence.

Preferred terminology:

- `CONFIRMED_EXPLOITER_SEED`
- `TRACED_FUNDS`
- `CROSS_CHAIN_HUB`
- `CONSOLIDATION_HUB`
- `PARKED_TRACED_FUNDS`
- `SERVICE_EXPOSURE`
- `UNKNOWN`

The term `HACKER WALLET` should only be used when ownership/control is independently established by reliable evidence.

## Disclaimer

HACKFLOW is an independent research project.

Labels and classifications describe on-chain fund-flow exposure and do not, by themselves, establish the identity, intent, or legal culpability of any wallet owner.

All findings should be independently verified against blockchain data and primary sources.

## Repository

Maintained under:

**VuBounty / HACKFLOW**

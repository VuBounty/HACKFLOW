# HACKFLOW Methodology

## 1. Evidence-First Analysis

All classifications should be traceable to observable on-chain evidence.

## 2. Taint Model

HACKFLOW uses:

- exact-flow attribution where transaction semantics are known;
- proportional/haircut propagation when assets are mixed;
- asset-preserving provenance across transfers;
- provenance transfer across swaps and bridges when input/output mapping is established.

## 3. Address Classification

Addresses are classified separately from fund exposure.

Examples:

- CONFIRMED_EXPLOITER_SEED
- DIRECT_DOWNSTREAM
- CROSS_CHAIN_HUB
- CONSOLIDATION_HUB
- PARKED_TRACED_FUNDS
- CEX
- DEX
- BRIDGE
- ROUTER
- CUSTODIAN
- UNKNOWN

## 4. Confidence

Suggested confidence levels:

- CONFIRMED
- HIGH
- MEDIUM
- LOW
- UNKNOWN

## 5. Public Reporting

Public reporting should distinguish:

- fact;
- inference;
- attribution;
- unresolved uncertainty.
